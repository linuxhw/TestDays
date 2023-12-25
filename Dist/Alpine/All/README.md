Alpine - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Alpine.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Alpine/Desktop/README.md) and [notebooks](/Dist/Alpine/Notebook/README.md).

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

Total: 233

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | TDPS05                      | Desktop     | [ce9b5d0c48](https://linux-hardware.org/?probe=ce9b5d0c48) | Dec 23, 2023 |
| Acer          | TDPS05                      | Desktop     | [d0260b1327](https://linux-hardware.org/?probe=d0260b1327) | Dec 23, 2023 |
| HP            | 886C                        | Desktop     | [2432d4f585](https://linux-hardware.org/?probe=2432d4f585) | Dec 22, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [d33b5845ef](https://linux-hardware.org/?probe=d33b5845ef) | Dec 20, 2023 |
| HP            | 886C                        | Desktop     | [4b404f8509](https://linux-hardware.org/?probe=4b404f8509) | Dec 15, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [a91d567af3](https://linux-hardware.org/?probe=a91d567af3) | Dec 14, 2023 |
| Dell          | Latitude 3420               | Notebook    | [b344d71410](https://linux-hardware.org/?probe=b344d71410) | Dec 13, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [2199caf331](https://linux-hardware.org/?probe=2199caf331) | Dec 10, 2023 |
| Compaq        | 0684h                       | Desktop     | [54c2d84103](https://linux-hardware.org/?probe=54c2d84103) | Dec 02, 2023 |
| Compaq        | 0684h                       | Desktop     | [b2d96b48dc](https://linux-hardware.org/?probe=b2d96b48dc) | Dec 02, 2023 |
| ECS           | M789CG                      | Desktop     | [7c2e2de188](https://linux-hardware.org/?probe=7c2e2de188) | Dec 01, 2023 |
| ASUSTek       | 1001PX                      | Notebook    | [74bc5aeded](https://linux-hardware.org/?probe=74bc5aeded) | Nov 22, 2023 |
| ASUSTek       | 1001PX                      | Notebook    | [2069694d95](https://linux-hardware.org/?probe=2069694d95) | Nov 22, 2023 |
| HP            | 886C                        | Desktop     | [b312b34d74](https://linux-hardware.org/?probe=b312b34d74) | Nov 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [f576d94ac0](https://linux-hardware.org/?probe=f576d94ac0) | Nov 17, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [1909f3fbff](https://linux-hardware.org/?probe=1909f3fbff) | Nov 15, 2023 |
| HP            | 886C                        | Desktop     | [f48f05994e](https://linux-hardware.org/?probe=f48f05994e) | Nov 14, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [60e418e27f](https://linux-hardware.org/?probe=60e418e27f) | Nov 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [80774e2d18](https://linux-hardware.org/?probe=80774e2d18) | Nov 14, 2023 |
| Unknown       | MT6737 (DT)                 | Soc         | [ed82b4c1c7](https://linux-hardware.org/?probe=ed82b4c1c7) | Nov 12, 2023 |
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [bfd62247aa](https://linux-hardware.org/?probe=bfd62247aa) | Nov 12, 2023 |
| HP            | 886C                        | Desktop     | [65a7263504](https://linux-hardware.org/?probe=65a7263504) | Nov 09, 2023 |
| ECS           | M789CG                      | Desktop     | [49edfe005c](https://linux-hardware.org/?probe=49edfe005c) | Nov 07, 2023 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [c714bf35c2](https://linux-hardware.org/?probe=c714bf35c2) | Nov 06, 2023 |
| HP            | 886C                        | Desktop     | [ccc7d658ea](https://linux-hardware.org/?probe=ccc7d658ea) | Nov 06, 2023 |
| ECS           | M789CG                      | Desktop     | [87fe73ee84](https://linux-hardware.org/?probe=87fe73ee84) | Nov 02, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [0656d1a0a8](https://linux-hardware.org/?probe=0656d1a0a8) | Oct 28, 2023 |
| HP            | 886C                        | Desktop     | [e116ef83e9](https://linux-hardware.org/?probe=e116ef83e9) | Oct 27, 2023 |
| HP            | 886C                        | Desktop     | [6df3cd6820](https://linux-hardware.org/?probe=6df3cd6820) | Oct 20, 2023 |
| ECS           | M789CG                      | Desktop     | [b767549953](https://linux-hardware.org/?probe=b767549953) | Oct 15, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [8625166ef3](https://linux-hardware.org/?probe=8625166ef3) | Oct 14, 2023 |
| ECS           | M789CG                      | Desktop     | [6f446a6f77](https://linux-hardware.org/?probe=6f446a6f77) | Oct 14, 2023 |
| ECS           | M789CG                      | Desktop     | [0a0df79fcd](https://linux-hardware.org/?probe=0a0df79fcd) | Oct 14, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [9559c016fb](https://linux-hardware.org/?probe=9559c016fb) | Oct 13, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [560aec8a01](https://linux-hardware.org/?probe=560aec8a01) | Oct 06, 2023 |
| HP            | 886C                        | Desktop     | [8356867b4d](https://linux-hardware.org/?probe=8356867b4d) | Oct 04, 2023 |
| HP            | 886C                        | Desktop     | [1d2bd102c6](https://linux-hardware.org/?probe=1d2bd102c6) | Sep 28, 2023 |
| HP            | 886C                        | Desktop     | [6295f7193c](https://linux-hardware.org/?probe=6295f7193c) | Sep 27, 2023 |
| HP            | 886C                        | Desktop     | [793c32918d](https://linux-hardware.org/?probe=793c32918d) | Sep 23, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [6b7e52fd8c](https://linux-hardware.org/?probe=6b7e52fd8c) | Sep 20, 2023 |
| ASRock        | H55M-LE                     | Desktop     | [ceefe742e2](https://linux-hardware.org/?probe=ceefe742e2) | Sep 20, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [b858f753b2](https://linux-hardware.org/?probe=b858f753b2) | Sep 19, 2023 |
| Dell          | 0RY007                      | Desktop     | [3bcbd1f6c3](https://linux-hardware.org/?probe=3bcbd1f6c3) | Sep 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [cc13e0926e](https://linux-hardware.org/?probe=cc13e0926e) | Sep 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [416798463e](https://linux-hardware.org/?probe=416798463e) | Sep 16, 2023 |
| LG Electro... | LW25-B7HG                   | Notebook    | [e9998203e6](https://linux-hardware.org/?probe=e9998203e6) | Sep 12, 2023 |
| HP            | 886C                        | Desktop     | [d59c2170bb](https://linux-hardware.org/?probe=d59c2170bb) | Sep 08, 2023 |
| Unknown       | MT6737 (DT)                 | Soc         | [ca65758798](https://linux-hardware.org/?probe=ca65758798) | Sep 07, 2023 |
| HP            | 886C                        | Desktop     | [ed1061dbb1](https://linux-hardware.org/?probe=ed1061dbb1) | Sep 07, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [00e5bebc6a](https://linux-hardware.org/?probe=00e5bebc6a) | Sep 06, 2023 |
| HP            | 886C                        | Desktop     | [30368099b8](https://linux-hardware.org/?probe=30368099b8) | Sep 06, 2023 |
| HP            | 886C                        | Desktop     | [f71590bc2b](https://linux-hardware.org/?probe=f71590bc2b) | Sep 03, 2023 |
| HP            | Presario V2000 (ES307UA#... | Notebook    | [6c727b9e00](https://linux-hardware.org/?probe=6c727b9e00) | Aug 23, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [1eab959e9a](https://linux-hardware.org/?probe=1eab959e9a) | Aug 15, 2023 |
| HP            | 886C                        | Desktop     | [d81314b86d](https://linux-hardware.org/?probe=d81314b86d) | Aug 12, 2023 |
| HP            | 886C                        | Desktop     | [4d26902a65](https://linux-hardware.org/?probe=4d26902a65) | Aug 12, 2023 |
| HP            | 886C                        | Desktop     | [d4a16b0b3e](https://linux-hardware.org/?probe=d4a16b0b3e) | Aug 10, 2023 |
| HP            | 886C                        | Desktop     | [294dcce02b](https://linux-hardware.org/?probe=294dcce02b) | Aug 04, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [2ea9aa9b27](https://linux-hardware.org/?probe=2ea9aa9b27) | Aug 02, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [3dcdce4c6d](https://linux-hardware.org/?probe=3dcdce4c6d) | Aug 02, 2023 |
| Dell          | Latitude 5430 Rugged        | Notebook    | [051aebd1a2](https://linux-hardware.org/?probe=051aebd1a2) | Jul 24, 2023 |
| ASUSTek       | A3AC                        | Notebook    | [1bf0a25c8e](https://linux-hardware.org/?probe=1bf0a25c8e) | Jul 22, 2023 |
| ASUSTek       | A3AC                        | Notebook    | [f7fb9875de](https://linux-hardware.org/?probe=f7fb9875de) | Jul 22, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [de055c3a95](https://linux-hardware.org/?probe=de055c3a95) | Jul 17, 2023 |
| ASUSTek       | Z170-E                      | Desktop     | [8be9720ca6](https://linux-hardware.org/?probe=8be9720ca6) | Jun 29, 2023 |
| Toshiba       | Satellite Pro L50-A         | Notebook    | [f1907449fa](https://linux-hardware.org/?probe=f1907449fa) | Jun 24, 2023 |
| Google        | Kefka                       | Notebook    | [c5d9002e23](https://linux-hardware.org/?probe=c5d9002e23) | Jun 23, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [4dca77df51](https://linux-hardware.org/?probe=4dca77df51) | Jun 21, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [b303b8ce0d](https://linux-hardware.org/?probe=b303b8ce0d) | Jun 07, 2023 |
| Dell          | 007MXD A00                  | Mini pc     | [8b904db6cf](https://linux-hardware.org/?probe=8b904db6cf) | Jun 06, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [0ad2309a50](https://linux-hardware.org/?probe=0ad2309a50) | Jun 05, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [c058d92130](https://linux-hardware.org/?probe=c058d92130) | Jun 05, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [374a3fef00](https://linux-hardware.org/?probe=374a3fef00) | Jun 05, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [413d6e5373](https://linux-hardware.org/?probe=413d6e5373) | Jun 05, 2023 |
| Toshiba       | WT8-A                       | Notebook    | [4dc30f1c10](https://linux-hardware.org/?probe=4dc30f1c10) | Jun 04, 2023 |
| MSI           | U200                        | Notebook    | [2fe4d70ea1](https://linux-hardware.org/?probe=2fe4d70ea1) | Jun 02, 2023 |
| HP            | 83E2                        | Desktop     | [0db8dcbc23](https://linux-hardware.org/?probe=0db8dcbc23) | May 28, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [da74cacf64](https://linux-hardware.org/?probe=da74cacf64) | May 18, 2023 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [429dc207a6](https://linux-hardware.org/?probe=429dc207a6) | May 15, 2023 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [f887e6f037](https://linux-hardware.org/?probe=f887e6f037) | May 15, 2023 |
| UGREEN        | DX4600                      | Desktop     | [cbe70de89c](https://linux-hardware.org/?probe=cbe70de89c) | Apr 19, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [125884d17a](https://linux-hardware.org/?probe=125884d17a) | Apr 05, 2023 |
| Olivetti      | Spring Peak                 | Notebook    | [9678c685d7](https://linux-hardware.org/?probe=9678c685d7) | Mar 31, 2023 |
| Olivetti      | Spring Peak                 | Notebook    | [7878f53f36](https://linux-hardware.org/?probe=7878f53f36) | Mar 31, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [8cf7b9cc76](https://linux-hardware.org/?probe=8cf7b9cc76) | Mar 23, 2023 |
| Fujitsu       | FMVNP8AE                    | Notebook    | [10efc9f976](https://linux-hardware.org/?probe=10efc9f976) | Mar 21, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [590309a32b](https://linux-hardware.org/?probe=590309a32b) | Mar 18, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [bc847b4586](https://linux-hardware.org/?probe=bc847b4586) | Mar 09, 2023 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d02959f9ad](https://linux-hardware.org/?probe=d02959f9ad) | Mar 02, 2023 |
| Lenovo        | ThinkPad E590 20NB0012RT    | Notebook    | [4c9bfc239a](https://linux-hardware.org/?probe=4c9bfc239a) | Feb 26, 2023 |
| Acer          | Aspire ES1-132              | Notebook    | [386da062e2](https://linux-hardware.org/?probe=386da062e2) | Feb 23, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [3bd522dc2c](https://linux-hardware.org/?probe=3bd522dc2c) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [cfa774a092](https://linux-hardware.org/?probe=cfa774a092) | Feb 13, 2023 |
| HP            | 886C                        | Desktop     | [b3d00219b0](https://linux-hardware.org/?probe=b3d00219b0) | Feb 07, 2023 |
| Google        | Leona                       | Notebook    | [59b146e197](https://linux-hardware.org/?probe=59b146e197) | Jan 21, 2023 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [d8f1121a19](https://linux-hardware.org/?probe=d8f1121a19) | Jan 19, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [68a73ee517](https://linux-hardware.org/?probe=68a73ee517) | Jan 19, 2023 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [6b6a4929de](https://linux-hardware.org/?probe=6b6a4929de) | Jan 16, 2023 |
| ASRock        | X470 Master SLI/ac          | Desktop     | [8775308115](https://linux-hardware.org/?probe=8775308115) | Jan 15, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [473b4d0e6e](https://linux-hardware.org/?probe=473b4d0e6e) | Jan 11, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [747c3d8c1f](https://linux-hardware.org/?probe=747c3d8c1f) | Jan 11, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [9635348d10](https://linux-hardware.org/?probe=9635348d10) | Jan 09, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | Notebook    | [3336313cae](https://linux-hardware.org/?probe=3336313cae) | Jan 06, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [053b8697ce](https://linux-hardware.org/?probe=053b8697ce) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33711Q7      | Notebook    | [7e0f8a38bf](https://linux-hardware.org/?probe=7e0f8a38bf) | Jan 04, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [5da7f2d3a9](https://linux-hardware.org/?probe=5da7f2d3a9) | Dec 27, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [389475ec30](https://linux-hardware.org/?probe=389475ec30) | Dec 25, 2022 |
| Dell          | 03V7GF A01                  | Desktop     | [3847c61b81](https://linux-hardware.org/?probe=3847c61b81) | Dec 17, 2022 |
| Dell          | 03V7GF A01                  | Desktop     | [e491b54a3c](https://linux-hardware.org/?probe=e491b54a3c) | Dec 17, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [bbf4464c41](https://linux-hardware.org/?probe=bbf4464c41) | Nov 27, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [ec837e35d6](https://linux-hardware.org/?probe=ec837e35d6) | Nov 22, 2022 |
| Fujitsu       | FujitsuTP7000 -1            | Desktop     | [89198d262f](https://linux-hardware.org/?probe=89198d262f) | Nov 17, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [d7cc344b2f](https://linux-hardware.org/?probe=d7cc344b2f) | Oct 31, 2022 |
| Supermicro    | X10SLL-F                    | Server      | [ab9f37ab3a](https://linux-hardware.org/?probe=ab9f37ab3a) | Oct 27, 2022 |
| Dell          | Inspiron 5447               | Notebook    | [735ac089ab](https://linux-hardware.org/?probe=735ac089ab) | Oct 17, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [9f7158b883](https://linux-hardware.org/?probe=9f7158b883) | Oct 16, 2022 |
| HP            | Presario V4000 (EQ608PA#... | Notebook    | [f462d80b2a](https://linux-hardware.org/?probe=f462d80b2a) | Oct 06, 2022 |
| HP            | 1493                        | Desktop     | [60ebd1d8dd](https://linux-hardware.org/?probe=60ebd1d8dd) | Sep 29, 2022 |
| Gateway       | SX2185                      | Desktop     | [8372be8fe3](https://linux-hardware.org/?probe=8372be8fe3) | Sep 29, 2022 |
| ASRock        | H81M                        | Desktop     | [d59c4705a2](https://linux-hardware.org/?probe=d59c4705a2) | Aug 17, 2022 |
| Toshiba       | Satellite M645              | Notebook    | [b342f11704](https://linux-hardware.org/?probe=b342f11704) | Aug 16, 2022 |
| Toshiba       | Satellite M645              | Notebook    | [f64d98a9e1](https://linux-hardware.org/?probe=f64d98a9e1) | Aug 16, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [d4dbaf9ec8](https://linux-hardware.org/?probe=d4dbaf9ec8) | Aug 14, 2022 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [fdbe6c32cd](https://linux-hardware.org/?probe=fdbe6c32cd) | Aug 06, 2022 |
| Unknown       | Unknown                     | Soc         | [9ebddaa953](https://linux-hardware.org/?probe=9ebddaa953) | Jul 31, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [5a3ed0cf62](https://linux-hardware.org/?probe=5a3ed0cf62) | Jul 30, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [719bbf817c](https://linux-hardware.org/?probe=719bbf817c) | Jul 30, 2022 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [9a4907d88c](https://linux-hardware.org/?probe=9a4907d88c) | Jul 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [d857b93614](https://linux-hardware.org/?probe=d857b93614) | Jul 13, 2022 |
| Sony          | VGN-UX27GN                  | Notebook    | [ed20bd45a4](https://linux-hardware.org/?probe=ed20bd45a4) | Jun 20, 2022 |
| IBM           | ThinkPad X40 2371LBG        | Notebook    | [e7610b86d4](https://linux-hardware.org/?probe=e7610b86d4) | Jun 20, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [a0a6c37152](https://linux-hardware.org/?probe=a0a6c37152) | Jun 19, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [2f6356a177](https://linux-hardware.org/?probe=2f6356a177) | Jun 17, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [e47cf70de1](https://linux-hardware.org/?probe=e47cf70de1) | Jun 17, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [582fd88dbe](https://linux-hardware.org/?probe=582fd88dbe) | Jun 14, 2022 |
| MSI           | Z170A GAMING PRO            | Desktop     | [73b3e29101](https://linux-hardware.org/?probe=73b3e29101) | Jun 14, 2022 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [a7f61e2b9b](https://linux-hardware.org/?probe=a7f61e2b9b) | May 28, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [e692b2a091](https://linux-hardware.org/?probe=e692b2a091) | May 26, 2022 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [28b7e84c50](https://linux-hardware.org/?probe=28b7e84c50) | May 24, 2022 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [5d78835d90](https://linux-hardware.org/?probe=5d78835d90) | May 24, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [cab2025064](https://linux-hardware.org/?probe=cab2025064) | May 24, 2022 |
| MSI           | J1900I                      | Desktop     | [86f37a71f5](https://linux-hardware.org/?probe=86f37a71f5) | May 15, 2022 |
| MSI           | J1900I                      | Desktop     | [5a48d83596](https://linux-hardware.org/?probe=5a48d83596) | May 15, 2022 |
| ASUSTek       | N10Jc                       | Notebook    | [ae20ca4c7c](https://linux-hardware.org/?probe=ae20ca4c7c) | May 05, 2022 |
| ASUSTek       | N10Jc                       | Notebook    | [1f688a5b2d](https://linux-hardware.org/?probe=1f688a5b2d) | May 05, 2022 |
| HP            | ProBook 4310s               | Notebook    | [a37901ae30](https://linux-hardware.org/?probe=a37901ae30) | Apr 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f0671e360b](https://linux-hardware.org/?probe=f0671e360b) | Apr 25, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [53cba6b4f8](https://linux-hardware.org/?probe=53cba6b4f8) | Apr 14, 2022 |
| Haier         | U144S                       | Notebook    | [9a4827b852](https://linux-hardware.org/?probe=9a4827b852) | Mar 26, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [930cc740b2](https://linux-hardware.org/?probe=930cc740b2) | Mar 24, 2022 |
| Lenovo        | ThinkPad T420 42364F2       | Notebook    | [d82acaba71](https://linux-hardware.org/?probe=d82acaba71) | Mar 23, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [df2a40363b](https://linux-hardware.org/?probe=df2a40363b) | Mar 18, 2022 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [b3cbed05f5](https://linux-hardware.org/?probe=b3cbed05f5) | Mar 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [94cf359935](https://linux-hardware.org/?probe=94cf359935) | Feb 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [822688debe](https://linux-hardware.org/?probe=822688debe) | Feb 16, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [a72ab8595e](https://linux-hardware.org/?probe=a72ab8595e) | Jan 30, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [908edb3724](https://linux-hardware.org/?probe=908edb3724) | Jan 27, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [6deddd3d32](https://linux-hardware.org/?probe=6deddd3d32) | Jan 25, 2022 |
| ASUSTek       | ZenBook UX431FA             | Notebook    | [519a7a72ab](https://linux-hardware.org/?probe=519a7a72ab) | Jan 24, 2022 |
| HP            | EliteBook 1040 G3 Notebo... | Notebook    | [465c51678d](https://linux-hardware.org/?probe=465c51678d) | Jan 01, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [f483ddc44f](https://linux-hardware.org/?probe=f483ddc44f) | Jan 01, 2022 |
| MSI           | GL72M 7REX                  | Notebook    | [6ada534c8b](https://linux-hardware.org/?probe=6ada534c8b) | Dec 13, 2021 |
| Dell          | 02YRK5 A02                  | Desktop     | [58c2ed388b](https://linux-hardware.org/?probe=58c2ed388b) | Dec 02, 2021 |
| Lenovo        | ThinkPad W700 2752RZ2       | Notebook    | [66ea0a02cb](https://linux-hardware.org/?probe=66ea0a02cb) | Nov 25, 2021 |
| Supermicro    | X10SLL-F                    | Server      | [84ed224f36](https://linux-hardware.org/?probe=84ed224f36) | Nov 24, 2021 |
| HP            | 21B4 A01                    | Desktop     | [98accc83e4](https://linux-hardware.org/?probe=98accc83e4) | Nov 11, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [e293d0cf05](https://linux-hardware.org/?probe=e293d0cf05) | Nov 02, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [0297d0f732](https://linux-hardware.org/?probe=0297d0f732) | Oct 25, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [45b1bba577](https://linux-hardware.org/?probe=45b1bba577) | Oct 24, 2021 |
| ASUSTek       | X550EA                      | Notebook    | [bbed87466a](https://linux-hardware.org/?probe=bbed87466a) | Oct 05, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [6f87d9f9b8](https://linux-hardware.org/?probe=6f87d9f9b8) | Oct 01, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [2668fd795b](https://linux-hardware.org/?probe=2668fd795b) | Oct 01, 2021 |
| HP            | Compaq Mini CQ10-600        | Notebook    | [4603b3336e](https://linux-hardware.org/?probe=4603b3336e) | Oct 01, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [9ff8561f02](https://linux-hardware.org/?probe=9ff8561f02) | Sep 30, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | Notebook    | [9fa77d455d](https://linux-hardware.org/?probe=9fa77d455d) | Sep 30, 2021 |
| Unknown       | Unknown                     | Notebook    | [d3c742bac9](https://linux-hardware.org/?probe=d3c742bac9) | Sep 26, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [254589b0bd](https://linux-hardware.org/?probe=254589b0bd) | Sep 16, 2021 |
| HP            | Stream 7 Tablet             | Tablet      | [f5bdbbea34](https://linux-hardware.org/?probe=f5bdbbea34) | Sep 15, 2021 |
| Dell          | 0T10XW A00                  | Desktop     | [585636f7fe](https://linux-hardware.org/?probe=585636f7fe) | Sep 08, 2021 |
| Shuttle       | FS81                        | Desktop     | [9a98a31681](https://linux-hardware.org/?probe=9a98a31681) | Sep 06, 2021 |
| Pegatron      | Deepcam                     | Notebook    | [5326e6bf39](https://linux-hardware.org/?probe=5326e6bf39) | Jul 18, 2021 |
| HP            | 886C                        | Desktop     | [3199a22608](https://linux-hardware.org/?probe=3199a22608) | Jul 15, 2021 |
| HP            | EliteBook 2740p             | Notebook    | [66479cb1dd](https://linux-hardware.org/?probe=66479cb1dd) | Jul 09, 2021 |
| HP            | EliteBook 2740p             | Notebook    | [652fa48f49](https://linux-hardware.org/?probe=652fa48f49) | Jul 08, 2021 |
| ASUSTek       | X200MA                      | Notebook    | [c9edeec38a](https://linux-hardware.org/?probe=c9edeec38a) | Jun 26, 2021 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [f1b8c01b96](https://linux-hardware.org/?probe=f1b8c01b96) | Jun 22, 2021 |
| IBM           | 264070A                     | Notebook    | [c057e54603](https://linux-hardware.org/?probe=c057e54603) | Jun 08, 2021 |
| HP            | Mini 110-3500               | Notebook    | [be40a38710](https://linux-hardware.org/?probe=be40a38710) | Jun 06, 2021 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [0a2464e592](https://linux-hardware.org/?probe=0a2464e592) | Jun 06, 2021 |
| Dell          | 0VRWRC A00                  | Desktop     | [37a6ad6e02](https://linux-hardware.org/?probe=37a6ad6e02) | Apr 09, 2021 |
| Dell          | 0DPRKF A07                  | Server      | [dee1f70644](https://linux-hardware.org/?probe=dee1f70644) | Mar 28, 2021 |
| ASUSTek       | P8H67-V                     | Desktop     | [89edd8b343](https://linux-hardware.org/?probe=89edd8b343) | Mar 17, 2021 |
| F5 Network... | PCA-0377-05                 | Server      | [14c76e0c83](https://linux-hardware.org/?probe=14c76e0c83) | Feb 28, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [0a01176cbe](https://linux-hardware.org/?probe=0a01176cbe) | Feb 23, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [af637820c2](https://linux-hardware.org/?probe=af637820c2) | Feb 12, 2021 |
| Acer          | Aspire ES1-512              | Notebook    | [01ad8fc793](https://linux-hardware.org/?probe=01ad8fc793) | Jan 30, 2021 |
| Acer          | Aspire 5920G                | Notebook    | [7cf5d7b04a](https://linux-hardware.org/?probe=7cf5d7b04a) | Jan 08, 2021 |
| HP            | Compaq Mini CQ10-600        | Notebook    | [fe7ee46763](https://linux-hardware.org/?probe=fe7ee46763) | Jan 08, 2021 |
| Gateway       | MX3631m                     | Notebook    | [15d8283384](https://linux-hardware.org/?probe=15d8283384) | Jan 03, 2021 |
| Dell          | Studio 1747                 | Notebook    | [b4e0e289f6](https://linux-hardware.org/?probe=b4e0e289f6) | Dec 29, 2020 |
| VIA Techno... | KM266APro-835               | Desktop     | [1334ad3f74](https://linux-hardware.org/?probe=1334ad3f74) | Dec 22, 2020 |
| Dell          | Inspiron 3180               | Notebook    | [4b05b65d0e](https://linux-hardware.org/?probe=4b05b65d0e) | Dec 16, 2020 |
| Dell          | Inspiron 3180               | Notebook    | [0bc140f6f6](https://linux-hardware.org/?probe=0bc140f6f6) | Dec 16, 2020 |
| ASUSTek       | E502SA                      | Notebook    | [0a25648158](https://linux-hardware.org/?probe=0a25648158) | Dec 05, 2020 |
| IBM           | 26446AG                     | Notebook    | [f004231106](https://linux-hardware.org/?probe=f004231106) | Nov 15, 2020 |
| IBM           | 26446AG                     | Notebook    | [29affa3577](https://linux-hardware.org/?probe=29affa3577) | Nov 15, 2020 |
| HP            | 2B0D A01                    | All in one  | [5c13b7bb96](https://linux-hardware.org/?probe=5c13b7bb96) | Nov 03, 2020 |
| Google        | Samus                       | Notebook    | [efe40a5a38](https://linux-hardware.org/?probe=efe40a5a38) | Oct 13, 2020 |
| Fujitsu       | D2779 S26361-D2779-A1       | Desktop     | [07795a357a](https://linux-hardware.org/?probe=07795a357a) | Oct 09, 2020 |
| Dell          | Inspiron 5566               | Notebook    | [a12b4d304a](https://linux-hardware.org/?probe=a12b4d304a) | Sep 29, 2020 |
| Lenovo        | 314C SDK0J40697 WIN 3305... | Mini pc     | [0f66b49a44](https://linux-hardware.org/?probe=0f66b49a44) | Sep 17, 2020 |
| Dell          | 0PU052                      | Desktop     | [9a31999f07](https://linux-hardware.org/?probe=9a31999f07) | Aug 31, 2020 |
| Apple         | MacBook7,1                  | Notebook    | [6445bfa9bd](https://linux-hardware.org/?probe=6445bfa9bd) | Aug 31, 2020 |
| Supermicro    | X10SLL-F                    | Server      | [dfbdbb0676](https://linux-hardware.org/?probe=dfbdbb0676) | Aug 25, 2020 |
| ASUSTek       | TS10                        | Desktop     | [71d7f6e110](https://linux-hardware.org/?probe=71d7f6e110) | Aug 20, 2020 |
| VIA Techno... | KM266APro-835               | Desktop     | [25ec3d44ff](https://linux-hardware.org/?probe=25ec3d44ff) | Aug 16, 2020 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [58dce1215c](https://linux-hardware.org/?probe=58dce1215c) | Aug 13, 2020 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [0c50242cc5](https://linux-hardware.org/?probe=0c50242cc5) | Aug 09, 2020 |
| HP            | 886C                        | Desktop     | [d05c262e67](https://linux-hardware.org/?probe=d05c262e67) | Aug 06, 2020 |
| ASRock        | J3455M                      | Desktop     | [05f9d5c3b4](https://linux-hardware.org/?probe=05f9d5c3b4) | Aug 06, 2020 |
| Lenovo        | ThinkPad 11e 20ED001HUS     | Notebook    | [364afb4113](https://linux-hardware.org/?probe=364afb4113) | Aug 06, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [c99b05cc07](https://linux-hardware.org/?probe=c99b05cc07) | Jul 30, 2020 |
| eMachines     | EL1352G                     | Desktop     | [4513d2931f](https://linux-hardware.org/?probe=4513d2931f) | Jul 03, 2020 |
| eMachines     | EL1352G                     | Desktop     | [4b26717c89](https://linux-hardware.org/?probe=4b26717c89) | Jul 03, 2020 |
| ASRock        | J3455M                      | Desktop     | [3719f96b60](https://linux-hardware.org/?probe=3719f96b60) | Jul 03, 2020 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [aa287cffbe](https://linux-hardware.org/?probe=aa287cffbe) | Jun 18, 2020 |
| Intel         | Merrifield                  | Tablet      | [d1f5e15d8c](https://linux-hardware.org/?probe=d1f5e15d8c) | May 23, 2020 |
| HP            | ZBook 15 G5                 | Notebook    | [3f3b1f2237](https://linux-hardware.org/?probe=3f3b1f2237) | Apr 05, 2020 |
| Synology      | DS1019+                     | Notebook    | [622ced4019](https://linux-hardware.org/?probe=622ced4019) | Feb 09, 2020 |
| Synology      | DS1019+                     | Notebook    | [c8a69e1c12](https://linux-hardware.org/?probe=c8a69e1c12) | Jan 21, 2020 |
| Synology      | DS1019+                     | Notebook    | [43a8c9674e](https://linux-hardware.org/?probe=43a8c9674e) | Jan 18, 2020 |
| Unknown       | i855GM/E-ITE8712            | Desktop     | [7b9cbd816b](https://linux-hardware.org/?probe=7b9cbd816b) | Dec 27, 2019 |
| ASRock        | D1800B-ITX                  | Desktop     | [f962d4bbf9](https://linux-hardware.org/?probe=f962d4bbf9) | Dec 22, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Alpine 3.12.0               | 11        | 6.67%   |
| Alpine 3.18.0               | 10        | 6.06%   |
| Alpine 3.15.0               | 10        | 6.06%   |
| Alpine 3.16.0               | 9         | 5.45%   |
| Alpine 3.15.4               | 8         | 4.85%   |
| Alpine 3.18.3               | 7         | 4.24%   |
| Alpine 3.15.0_alpha20210804 | 7         | 4.24%   |
| Alpine 3.19_alpha20230901   | 6         | 3.64%   |
| Alpine 3.18.4               | 6         | 3.64%   |
| Alpine 3.17_alpha20220809   | 5         | 3.03%   |
| Alpine 3.17.2               | 5         | 3.03%   |
| Alpine 3.14.0               | 5         | 3.03%   |
| Alpine 3.18.2               | 4         | 2.42%   |
| Alpine 3.17.1               | 4         | 2.42%   |
| Alpine 3.17.0               | 4         | 2.42%   |
| Alpine 3.16.1               | 4         | 2.42%   |
| Alpine 3.14.2               | 4         | 2.42%   |
| Alpine 3.13.0_alpha20200917 | 4         | 2.42%   |
| Alpine 3.13.0_alpha20200626 | 4         | 2.42%   |
| Alpine 3.11.2               | 4         | 2.42%   |
| Alpine 3.19.0               | 3         | 1.82%   |
| Alpine 3.16.2               | 3         | 1.82%   |
| Alpine 3.13.1               | 3         | 1.82%   |
| Alpine 3.13.0_alpha20201218 | 3         | 1.82%   |
| Alpine 3.18_alpha20230329   | 2         | 1.21%   |
| Alpine 3.18.5               | 2         | 1.21%   |
| Alpine 3.16.3               | 2         | 1.21%   |
| Alpine 3.15.6               | 2         | 1.21%   |
| Alpine 3.14.3               | 2         | 1.21%   |
| Alpine 3.13.5               | 2         | 1.21%   |
| Alpine 3.13.2               | 2         | 1.21%   |
| Alpine 3.12.3               | 2         | 1.21%   |
| Alpine 3.8.4                | 1         | 0.61%   |
| Alpine 3.19.0_rc2           | 1         | 0.61%   |
| Alpine 3.17.4               | 1         | 0.61%   |
| Alpine 3.17.3               | 1         | 0.61%   |
| Alpine 3.16.0_alpha20220328 | 1         | 0.61%   |
| Alpine 3.16.0_alpha20220316 | 1         | 0.61%   |
| Alpine 3.15.2               | 1         | 0.61%   |
| Alpine 3.15.0_rc5           | 1         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Alpine | 152       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version          | Computers | Percent |
|------------------|-----------|---------|
| 5.4.43-1-lts     | 8         | 4.73%   |
| 6.1.57-0-lts     | 3         | 1.78%   |
| 6.1.32-0-lts     | 3         | 1.78%   |
| 5.15.86-0-lts    | 3         | 1.78%   |
| 5.15.60-0-lts    | 3         | 1.78%   |
| 5.15.16-0-lts    | 3         | 1.78%   |
| 5.10.61-0-lts    | 3         | 1.78%   |
| 6.6.7-0-lts      | 2         | 1.18%   |
| 6.6.1-0-edge     | 2         | 1.18%   |
| 6.1.62-0-lts     | 2         | 1.18%   |
| 6.1.55-0-lts     | 2         | 1.18%   |
| 6.1.51-0-lts     | 2         | 1.18%   |
| 6.1.28-2-lts     | 2         | 1.18%   |
| 5.4.84-0-lts     | 2         | 1.18%   |
| 5.4.83-0-lts     | 2         | 1.18%   |
| 5.17.9-0-edge    | 2         | 1.18%   |
| 5.15.74-0-lts    | 2         | 1.18%   |
| 5.15.59-0-lts    | 2         | 1.18%   |
| 5.15.47-0-lts    | 2         | 1.18%   |
| 5.15.46-1-lts    | 2         | 1.18%   |
| 5.15.41-0-lts    | 2         | 1.18%   |
| 5.15.4-0-lts     | 2         | 1.18%   |
| 5.15.12-0-lts    | 2         | 1.18%   |
| 5.10.68-0-lts    | 2         | 1.18%   |
| 5.10.16-0-lts    | 2         | 1.18%   |
| 6.6.6-0-lts      | 1         | 0.59%   |
| 6.6.4-0-lts      | 1         | 0.59%   |
| 6.4.4-0-edge     | 1         | 0.59%   |
| 6.3.3-0-edge     | 1         | 0.59%   |
| 6.2.0-37-generic | 1         | 0.59%   |
| 6.2.0-36-generic | 1         | 0.59%   |
| 6.1.64-0-lts     | 1         | 0.59%   |
| 6.1.61-0-lts     | 1         | 0.59%   |
| 6.1.60-0-lts     | 1         | 0.59%   |
| 6.1.55-2-lts     | 1         | 0.59%   |
| 6.1.54-0-lts     | 1         | 0.59%   |
| 6.1.53-0-lts     | 1         | 0.59%   |
| 6.1.52-0-lts     | 1         | 0.59%   |
| 6.1.46-0-lts     | 1         | 0.59%   |
| 6.1.42-0-lts     | 1         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.43  | 8         | 4.79%   |
| 6.1.57  | 3         | 1.8%    |
| 6.1.55  | 3         | 1.8%    |
| 6.1.32  | 3         | 1.8%    |
| 5.15.86 | 3         | 1.8%    |
| 5.15.60 | 3         | 1.8%    |
| 5.15.16 | 3         | 1.8%    |
| 5.15.0  | 3         | 1.8%    |
| 5.10.61 | 3         | 1.8%    |
| 6.6.7   | 2         | 1.2%    |
| 6.6.1   | 2         | 1.2%    |
| 6.1.62  | 2         | 1.2%    |
| 6.1.51  | 2         | 1.2%    |
| 6.1.34  | 2         | 1.2%    |
| 6.1.28  | 2         | 1.2%    |
| 5.4.84  | 2         | 1.2%    |
| 5.4.83  | 2         | 1.2%    |
| 5.19.0  | 2         | 1.2%    |
| 5.17.9  | 2         | 1.2%    |
| 5.15.74 | 2         | 1.2%    |
| 5.15.59 | 2         | 1.2%    |
| 5.15.47 | 2         | 1.2%    |
| 5.15.46 | 2         | 1.2%    |
| 5.15.41 | 2         | 1.2%    |
| 5.15.4  | 2         | 1.2%    |
| 5.15.12 | 2         | 1.2%    |
| 5.10.68 | 2         | 1.2%    |
| 5.10.16 | 2         | 1.2%    |
| 6.6.6   | 1         | 0.6%    |
| 6.6.4   | 1         | 0.6%    |
| 6.4.4   | 1         | 0.6%    |
| 6.3.3   | 1         | 0.6%    |
| 6.2.0   | 1         | 0.6%    |
| 6.1.64  | 1         | 0.6%    |
| 6.1.61  | 1         | 0.6%    |
| 6.1.60  | 1         | 0.6%    |
| 6.1.54  | 1         | 0.6%    |
| 6.1.53  | 1         | 0.6%    |
| 6.1.52  | 1         | 0.6%    |
| 6.1.46  | 1         | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 51        | 31.68%  |
| 6.1     | 29        | 18.01%  |
| 5.4     | 23        | 14.29%  |
| 5.10    | 23        | 14.29%  |
| 6.6     | 6         | 3.73%   |
| 5.17    | 4         | 2.48%   |
| 3.10    | 3         | 1.86%   |
| 5.8     | 2         | 1.24%   |
| 5.19    | 2         | 1.24%   |
| 5.14    | 2         | 1.24%   |
| 4.4     | 2         | 1.24%   |
| 3.18    | 2         | 1.24%   |
| 6.4     | 1         | 0.62%   |
| 6.3     | 1         | 0.62%   |
| 6.2     | 1         | 0.62%   |
| 6.0     | 1         | 0.62%   |
| 5.7     | 1         | 0.62%   |
| 5.6     | 1         | 0.62%   |
| 5.18    | 1         | 0.62%   |
| 5.16    | 1         | 0.62%   |
| 5.13    | 1         | 0.62%   |
| 5.12    | 1         | 0.62%   |
| 4.20    | 1         | 0.62%   |
| 4.14    | 1         | 0.62%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 126       | 82.89%  |
| i686    | 18        | 11.84%  |
| aarch64 | 4         | 2.63%   |
| armv7l  | 3         | 1.97%   |
| i586    | 1         | 0.66%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 120       | 78.95%  |
| XFCE    | 15        | 9.87%   |
| GNOME   | 7         | 4.61%   |
| KDE5    | 4         | 2.63%   |
| sway    | 2         | 1.32%   |
| LXQt    | 2         | 1.32%   |
| KDE     | 1         | 0.66%   |
| i3      | 1         | 0.66%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 90        | 58.06%  |
| X11     | 53        | 34.19%  |
| Wayland | 11        | 7.1%    |
| Tty     | 1         | 0.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 122       | 79.74%  |
| LightDM | 21        | 13.73%  |
| SDDM    | 4         | 2.61%   |
| GDM     | 3         | 1.96%   |
| LXDM    | 2         | 1.31%   |
| XDM     | 1         | 0.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| C       | 94        | 60.26%  |
| Unknown | 49        | 31.41%  |
| en_US   | 7         | 4.49%   |
| ru_RU   | 3         | 1.92%   |
| en_GB   | 2         | 1.28%   |
| pt_BR   | 1         | 0.64%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 99        | 64.29%  |
| EFI  | 55        | 35.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 122       | 78.71%  |
| Btrfs   | 11        | 7.1%    |
| Overlay | 8         | 5.16%   |
| Tmpfs   | 6         | 3.87%   |
| F2fs    | 2         | 1.29%   |
| Unknown | 2         | 1.29%   |
| Zfs     | 1         | 0.65%   |
| Rootfs  | 1         | 0.65%   |
| Fake    | 1         | 0.65%   |
| Ext2    | 1         | 0.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 97        | 61.39%  |
| GPT     | 43        | 27.22%  |
| MBR     | 18        | 11.39%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 133       | 86.36%  |
| Yes       | 21        | 13.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 143       | 92.26%  |
| Yes       | 12        | 7.74%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 22        | 14.47%  |
| Hewlett-Packard         | 21        | 13.82%  |
| ASUSTek Computer        | 17        | 11.18%  |
| Lenovo                  | 15        | 9.87%   |
| ASRock                  | 8         | 5.26%   |
| Gigabyte Technology     | 7         | 4.61%   |
| Unknown                 | 7         | 4.61%   |
| Intel                   | 6         | 3.95%   |
| Acer                    | 6         | 3.95%   |
| Fujitsu                 | 4         | 2.63%   |
| Toshiba                 | 3         | 1.97%   |
| MSI                     | 3         | 1.97%   |
| IBM                     | 3         | 1.97%   |
| Google                  | 3         | 1.97%   |
| Apple                   | 3         | 1.97%   |
| ZOTAC                   | 2         | 1.32%   |
| Raspberry Pi Foundation | 2         | 1.32%   |
| Gateway                 | 2         | 1.32%   |
| VIA Technologies        | 1         | 0.66%   |
| UGREEN                  | 1         | 0.66%   |
| Synology                | 1         | 0.66%   |
| Supermicro              | 1         | 0.66%   |
| Sony                    | 1         | 0.66%   |
| Shuttle                 | 1         | 0.66%   |
| Pegatron                | 1         | 0.66%   |
| Olivetti                | 1         | 0.66%   |
| Notebook                | 1         | 0.66%   |
| LG Electronics          | 1         | 0.66%   |
| Inventec                | 1         | 0.66%   |
| Haier                   | 1         | 0.66%   |
| Fanless Mini PC         | 1         | 0.66%   |
| F5 Networks             | 1         | 0.66%   |
| eMachines               | 1         | 0.66%   |
| ECS                     | 1         | 0.66%   |
| Compaq                  | 1         | 0.66%   |
| AMI                     | 1         | 0.66%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 8         | 5.26%   |
| Dell Dell Thin Client Desktop 3030 LT    | 3         | 1.97%   |
| HP ProLiant DL360 G6                     | 2         | 1.32%   |
| Gigabyte Z490I AORUS ULTRA               | 2         | 1.32%   |
| ASUS All Series                          | 2         | 1.32%   |
| ZOTAC ZBOX-EN1070/1060,EN1070K/1060K     | 1         | 0.66%   |
| VIA KM266APro-835                        | 1         | 0.66%   |
| UGREEN DX4600                            | 1         | 0.66%   |
| Toshiba WT8-A                            | 1         | 0.66%   |
| Toshiba Satellite Pro L50-A              | 1         | 0.66%   |
| Toshiba Satellite M645                   | 1         | 0.66%   |
| Synology DS1019+                         | 1         | 0.66%   |
| Supermicro X10SLL-F                      | 1         | 0.66%   |
| Sony VGN-UX27GN                          | 1         | 0.66%   |
| Shuttle DS81D                            | 1         | 0.66%   |
| RPi Raspberry Pi 4 Model B Rev 1.5       | 1         | 0.66%   |
| RPi Raspberry Pi                         | 1         | 0.66%   |
| Pegatron Deepcam                         | 1         | 0.66%   |
| Olivetti Spring Peak                     | 1         | 0.66%   |
| Notebook NV4XMB,ME,MZ                    | 1         | 0.66%   |
| MSI MS-7C82                              | 1         | 0.66%   |
| MSI MS-7877                              | 1         | 0.66%   |
| MSI GL72M 7REX                           | 1         | 0.66%   |
| LG LW25-B7HG                             | 1         | 0.66%   |
| Lenovo Yoga 14sARH 2021 82LB             | 1         | 0.66%   |
| Lenovo V15 G3 IAP 82TT                   | 1         | 0.66%   |
| Lenovo V14-ADA 82C6                      | 1         | 0.66%   |
| Lenovo ThinkPad X131e 33711Q7            | 1         | 0.66%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS17D00 | 1         | 0.66%   |
| Lenovo ThinkPad W700 2752RZ2             | 1         | 0.66%   |
| Lenovo ThinkPad T420 42364F2             | 1         | 0.66%   |
| Lenovo ThinkPad E590 20NB0012RT          | 1         | 0.66%   |
| Lenovo ThinkPad E485 20KUCTO1WW          | 1         | 0.66%   |
| Lenovo ThinkPad 11e 20ED001HUS           | 1         | 0.66%   |
| Lenovo ThinkCentre M93p 10AB0016US       | 1         | 0.66%   |
| Lenovo ThinkCentre M90n-1 11AD000YMX     | 1         | 0.66%   |
| Lenovo IdeaPad 320-15AST 80XV            | 1         | 0.66%   |
| Lenovo H535 10117                        | 1         | 0.66%   |
| Lenovo Flex 2-14 20404                   | 1         | 0.66%   |
| Inventec D CLASS                         | 1         | 0.66%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell Inspiron       | 8         | 5.26%   |
| Unknown             | 8         | 5.26%   |
| Lenovo ThinkPad     | 7         | 4.61%   |
| Dell OptiPlex       | 5         | 3.29%   |
| Acer Aspire         | 5         | 3.29%   |
| HP ProLiant         | 3         | 1.97%   |
| HP EliteBook        | 3         | 1.97%   |
| Dell Dell           | 3         | 1.97%   |
| Toshiba Satellite   | 2         | 1.32%   |
| RPi Raspberry       | 2         | 1.32%   |
| Lenovo ThinkCentre  | 2         | 1.32%   |
| HP Presario         | 2         | 1.32%   |
| HP Laptop           | 2         | 1.32%   |
| HP Compaq           | 2         | 1.32%   |
| Gigabyte Z490I      | 2         | 1.32%   |
| Dell XPS            | 2         | 1.32%   |
| Dell Latitude       | 2         | 1.32%   |
| ASUS PRIME          | 2         | 1.32%   |
| ASUS All            | 2         | 1.32%   |
| ZOTAC ZBOX-EN1070   | 1         | 0.66%   |
| VIA KM266APro-835   | 1         | 0.66%   |
| UGREEN DX4600       | 1         | 0.66%   |
| Toshiba WT8-A       | 1         | 0.66%   |
| Synology DS1019+    | 1         | 0.66%   |
| Supermicro X10SLL-F | 1         | 0.66%   |
| Sony VGN-UX27GN     | 1         | 0.66%   |
| Shuttle DS81D       | 1         | 0.66%   |
| Pegatron Deepcam    | 1         | 0.66%   |
| Olivetti Spring     | 1         | 0.66%   |
| Notebook NV4XMB     | 1         | 0.66%   |
| MSI MS-7C82         | 1         | 0.66%   |
| MSI MS-7877         | 1         | 0.66%   |
| MSI GL72M           | 1         | 0.66%   |
| LG LW25-B7HG        | 1         | 0.66%   |
| Lenovo Yoga         | 1         | 0.66%   |
| Lenovo V15          | 1         | 0.66%   |
| Lenovo V14-ADA      | 1         | 0.66%   |
| Lenovo IdeaPad      | 1         | 0.66%   |
| Lenovo H535         | 1         | 0.66%   |
| Lenovo Flex         | 1         | 0.66%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2014    | 18        | 11.84%  |
| 2012    | 12        | 7.89%   |
| 2018    | 11        | 7.24%   |
| 2010    | 11        | 7.24%   |
| 2019    | 10        | 6.58%   |
| 2016    | 9         | 5.92%   |
| 2013    | 9         | 5.92%   |
| Unknown | 9         | 5.92%   |
| 2020    | 8         | 5.26%   |
| 2017    | 8         | 5.26%   |
| 2021    | 7         | 4.61%   |
| 2015    | 6         | 3.95%   |
| 2011    | 6         | 3.95%   |
| 2006    | 6         | 3.95%   |
| 2009    | 5         | 3.29%   |
| 2022    | 4         | 2.63%   |
| 2007    | 4         | 2.63%   |
| 2023    | 2         | 1.32%   |
| 2005    | 2         | 1.32%   |
| 2001    | 2         | 1.32%   |
| 2008    | 1         | 0.66%   |
| 2004    | 1         | 0.66%   |
| 1999    | 1         | 0.66%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 73        | 48.03%  |
| Desktop        | 55        | 36.18%  |
| Mini pc        | 11        | 7.24%   |
| Server         | 5         | 3.29%   |
| System on chip | 4         | 2.63%   |
| Tablet         | 2         | 1.32%   |
| Convertible    | 1         | 0.66%   |
| All in one     | 1         | 0.66%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 151       | 98.69%  |
| Enabled  | 2         | 1.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 149       | 98.03%  |
| Yes  | 3         | 1.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 32        | 20.13%  |
| 3.01-4.0        | 31        | 19.5%   |
| 16.01-24.0      | 25        | 15.72%  |
| 8.01-16.0       | 19        | 11.95%  |
| 1.01-2.0        | 13        | 8.18%   |
| 0.51-1.0        | 13        | 8.18%   |
| 32.01-64.0      | 10        | 6.29%   |
| 2.01-3.0        | 5         | 3.14%   |
| 64.01-256.0     | 5         | 3.14%   |
| 0.01-0.5        | 5         | 3.14%   |
| More than 256.0 | 1         | 0.63%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 47        | 29.19%  |
| 1.01-2.0  | 34        | 21.12%  |
| 0.51-1.0  | 29        | 18.01%  |
| 2.01-3.0  | 16        | 9.94%   |
| 4.01-8.0  | 11        | 6.83%   |
| 3.01-4.0  | 11        | 6.83%   |
| 8.01-16.0 | 5         | 3.11%   |
| 0         | 4         | 2.48%   |
| Unknown   | 4         | 2.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 99        | 63.06%  |
| 2      | 30        | 19.11%  |
| 3      | 10        | 6.37%   |
| 4      | 7         | 4.46%   |
| 5      | 3         | 1.91%   |
| 0      | 3         | 1.91%   |
| 14     | 2         | 1.27%   |
| 12     | 1         | 0.64%   |
| 10     | 1         | 0.64%   |
| 7      | 1         | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 124       | 80.52%  |
| Yes       | 30        | 19.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 129       | 84.87%  |
| No        | 23        | 15.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 60%     |
| No        | 62        | 40%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 88        | 57.14%  |
| Yes       | 66        | 42.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 37        | 23.27%  |
| Germany      | 19        | 11.95%  |
| Canada       | 13        | 8.18%   |
| Russia       | 12        | 7.55%   |
| UK           | 9         | 5.66%   |
| Brazil       | 7         | 4.4%    |
| Sweden       | 5         | 3.14%   |
| Spain        | 5         | 3.14%   |
| Australia    | 4         | 2.52%   |
| Norway       | 3         | 1.89%   |
| China        | 3         | 1.89%   |
| Slovakia     | 2         | 1.26%   |
| Portugal     | 2         | 1.26%   |
| Poland       | 2         | 1.26%   |
| Netherlands  | 2         | 1.26%   |
| Mexico       | 2         | 1.26%   |
| Italy        | 2         | 1.26%   |
| Israel       | 2         | 1.26%   |
| Guatemala    | 2         | 1.26%   |
| Finland      | 2         | 1.26%   |
| Austria      | 2         | 1.26%   |
| Argentina    | 2         | 1.26%   |
| Vietnam      | 1         | 0.63%   |
| Venezuela    | 1         | 0.63%   |
| Ukraine      | 1         | 0.63%   |
| UAE          | 1         | 0.63%   |
| Switzerland  | 1         | 0.63%   |
| South Korea  | 1         | 0.63%   |
| South Africa | 1         | 0.63%   |
| Philippines  | 1         | 0.63%   |
| Pakistan     | 1         | 0.63%   |
| Kenya        | 1         | 0.63%   |
| Jamaica      | 1         | 0.63%   |
| Ireland      | 1         | 0.63%   |
| Indonesia    | 1         | 0.63%   |
| Hungary      | 1         | 0.63%   |
| Greece       | 1         | 0.63%   |
| France       | 1         | 0.63%   |
| Egypt        | 1         | 0.63%   |
| Denmark      | 1         | 0.63%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Springfield       | 7         | 4.32%   |
| St Petersburg     | 6         | 3.7%    |
| Manitowoc         | 5         | 3.09%   |
| Vernon            | 4         | 2.47%   |
| Moscow            | 3         | 1.85%   |
| Traunstein        | 2         | 1.23%   |
| Sydney            | 2         | 1.23%   |
| Stratford         | 2         | 1.23%   |
| Siegsdorf         | 2         | 1.23%   |
| Harrisonburg      | 2         | 1.23%   |
| Guatemala City    | 2         | 1.23%   |
| Gothenburg        | 2         | 1.23%   |
| Fulham            | 2         | 1.23%   |
| Frankfurt am Main | 2         | 1.23%   |
| As                | 2         | 1.23%   |
| Zurich            | 1         | 0.62%   |
| Zhangzhou         | 1         | 0.62%   |
| Yakima            | 1         | 0.62%   |
| Vienna            | 1         | 0.62%   |
| Vejle             | 1         | 0.62%   |
| Vancouver         | 1         | 0.62%   |
| Tymovskoye        | 1         | 0.62%   |
| Tuusula           | 1         | 0.62%   |
| Turin             | 1         | 0.62%   |
| Topeka            | 1         | 0.62%   |
| Tinh Binh Duong   | 1         | 0.62%   |
| Thornhill         | 1         | 0.62%   |
| Thame             | 1         | 0.62%   |
| Tampa             | 1         | 0.62%   |
| Stuttgart         | 1         | 0.62%   |
| Stockholm         | 1         | 0.62%   |
| Stewartstown      | 1         | 0.62%   |
| Somerset          | 1         | 0.62%   |
| Ski               | 1         | 0.62%   |
| Sisteron          | 1         | 0.62%   |
| Semily            | 1         | 0.62%   |
| Seattle           | 1         | 0.62%   |
| Sao Paulo         | 1         | 0.62%   |
| San Mateo         | 1         | 0.62%   |
| San Francisco     | 1         | 0.62%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 28        | 53     | 12.84%  |
| WDC                         | 26        | 58     | 11.93%  |
| Seagate                     | 21        | 51     | 9.63%   |
| Unknown                     | 20        | 26     | 9.17%   |
| Toshiba                     | 16        | 19     | 7.34%   |
| Hitachi                     | 12        | 12     | 5.5%    |
| Kingston                    | 10        | 14     | 4.59%   |
| HGST                        | 10        | 10     | 4.59%   |
| Crucial                     | 10        | 18     | 4.59%   |
| Sandisk                     | 8         | 11     | 3.67%   |
| A-DATA Technology           | 8         | 10     | 3.67%   |
| Intel                       | 7         | 11     | 3.21%   |
| SK hynix                    | 6         | 8      | 2.75%   |
| SPCC                        | 3         | 3      | 1.38%   |
| Micron Technology           | 3         | 3      | 1.38%   |
| Transcend                   | 2         | 2      | 0.92%   |
| LITEON                      | 2         | 2      | 0.92%   |
| Intenso                     | 2         | 2      | 0.92%   |
| Fujitsu                     | 2         | 2      | 0.92%   |
| STEC                        | 1         | 1      | 0.46%   |
| SINTECHI                    | 1         | 1      | 0.46%   |
| Secure                      | 1         | 1      | 0.46%   |
| PNY                         | 1         | 1      | 0.46%   |
| Phison Electronics          | 1         | 1      | 0.46%   |
| NETAPP                      | 1         | 1      | 0.46%   |
| Maxtor                      | 1         | 1      | 0.46%   |
| Lexar                       | 1         | 1      | 0.46%   |
| KIOXIA                      | 1         | 1      | 0.46%   |
| Kingston Technology Company | 1         | 1      | 0.46%   |
| Kingmax                     | 1         | 1      | 0.46%   |
| KC600                       | 1         | 1      | 0.46%   |
| JMicron Technology          | 1         | 1      | 0.46%   |
| INNOVATION IT               | 1         | 1      | 0.46%   |
| IBM                         | 1         | 1      | 0.46%   |
| Emtec                       | 1         | 1      | 0.46%   |
| Dell                        | 1         | 2      | 0.46%   |
| China                       | 1         | 1      | 0.46%   |
| Aura                        | 1         | 1      | 0.46%   |
| Apple                       | 1         | 3      | 0.46%   |
| AMD                         | 1         | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  16GB                              | 5         | 1.93%   |
| Unknown MMC Card  4GB                               | 4         | 1.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 4         | 1.54%   |
| Unknown MMC Card  32GB                              | 3         | 1.16%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2         | 0.77%   |
| WDC WD3000BLFS-60YBU2 304GB                         | 2         | 0.77%   |
| Unknown SD/MMC/MS PRO 128GB                         | 2         | 0.77%   |
| Unknown MMC Card  64GB                              | 2         | 0.77%   |
| Unknown MMC Card                                    | 2         | 0.77%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.77%   |
| Toshiba MQ01ABD075 752GB                            | 2         | 0.77%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 2         | 0.77%   |
| Seagate ST4000VN008-2DR1 4TB                        | 2         | 0.77%   |
| Seagate ST380815AS 80GB                             | 2         | 0.77%   |
| Samsung SSD 980 PRO 1TB                             | 2         | 0.77%   |
| Samsung SSD 960 EVO 500GB                           | 2         | 0.77%   |
| Samsung SSD 870 QVO 1TB                             | 2         | 0.77%   |
| Samsung SSD 870 EVO 1TB                             | 2         | 0.77%   |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 0.77%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 0.77%   |
| Kingston SA400S37120G 120GB SSD                     | 2         | 0.77%   |
| Kingston SA400S3 120GB SSD                          | 2         | 0.77%   |
| Intenso SSD 128GB                                   | 2         | 0.77%   |
| Crucial CT500MX500SSD1 500GB                        | 2         | 0.77%   |
| Crucial CT120BX500SSD1 120GB                        | 2         | 0.77%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 0.77%   |
| A-DATA SU800 128GB SSD                              | 2         | 0.77%   |
| WDC WDS500G2X0C-00L350 500GB                        | 1         | 0.39%   |
| WDC WDS500G2B0A 500GB SSD                           | 1         | 0.39%   |
| WDC WDS250G2B0B-00YS70 250GB SSD                    | 1         | 0.39%   |
| WDC WDS250G2B0B 250GB SSD                           | 1         | 0.39%   |
| WDC WDS250G2B0A 250GB SSD                           | 1         | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.39%   |
| WDC WD80EMAZ-00WJTA0 8TB                            | 1         | 0.39%   |
| WDC WD80EFAX-68LHPN0 8TB                            | 1         | 0.39%   |
| WDC WD800AAJS-00 80GB                               | 1         | 0.39%   |
| WDC WD7500BPKT-80PK4T0 752GB                        | 1         | 0.39%   |
| WDC WD5003ABYZ-0 500GB                              | 1         | 0.39%   |
| WDC WD5000BEVT-7 500GB                              | 1         | 0.39%   |
| WDC WD5000BEVT-22ZAT0 500GB                         | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 51     | 24.14%  |
| WDC                 | 20        | 47     | 22.99%  |
| Toshiba             | 13        | 15     | 14.94%  |
| Hitachi             | 12        | 12     | 13.79%  |
| HGST                | 10        | 10     | 11.49%  |
| Samsung Electronics | 4         | 8      | 4.6%    |
| Unknown             | 2         | 2      | 2.3%    |
| Fujitsu             | 2         | 2      | 2.3%    |
| SINTECHI            | 1         | 1      | 1.15%   |
| Maxtor              | 1         | 1      | 1.15%   |
| IBM                 | 1         | 1      | 1.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 20     | 14.86%  |
| Kingston            | 10        | 12     | 13.51%  |
| Crucial             | 10        | 18     | 13.51%  |
| WDC                 | 5         | 7      | 6.76%   |
| Intel               | 5         | 7      | 6.76%   |
| A-DATA Technology   | 5         | 5      | 6.76%   |
| SanDisk             | 4         | 5      | 5.41%   |
| SPCC                | 3         | 3      | 4.05%   |
| Transcend           | 2         | 2      | 2.7%    |
| SK hynix            | 2         | 3      | 2.7%    |
| LITEON              | 2         | 2      | 2.7%    |
| Intenso             | 2         | 2      | 2.7%    |
| Toshiba             | 1         | 1      | 1.35%   |
| Secure              | 1         | 1      | 1.35%   |
| PNY                 | 1         | 1      | 1.35%   |
| Micron Technology   | 1         | 1      | 1.35%   |
| Lexar               | 1         | 1      | 1.35%   |
| Kingmax             | 1         | 1      | 1.35%   |
| KC600               | 1         | 1      | 1.35%   |
| JMicron Technology  | 1         | 1      | 1.35%   |
| INNOVATION IT       | 1         | 1      | 1.35%   |
| Emtec               | 1         | 1      | 1.35%   |
| Dell                | 1         | 2      | 1.35%   |
| China               | 1         | 1      | 1.35%   |
| AMD                 | 1         | 1      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 74        | 150    | 39.57%  |
| SSD     | 59        | 100    | 31.55%  |
| NVMe    | 34        | 62     | 18.18%  |
| MMC     | 18        | 25     | 9.63%   |
| Unknown | 2         | 3      | 1.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 111       | 242    | 64.91%  |
| NVMe | 34        | 62     | 19.88%  |
| MMC  | 18        | 25     | 10.53%  |
| SAS  | 8         | 11     | 4.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 91        | 153    | 66.91%  |
| 0.51-1.0   | 25        | 37     | 18.38%  |
| 4.01-10.0  | 6         | 22     | 4.41%   |
| 3.01-4.0   | 5         | 16     | 3.68%   |
| 1.01-2.0   | 4         | 7      | 2.94%   |
| 10.01-20.0 | 3         | 13     | 2.21%   |
| 2.01-3.0   | 2         | 2      | 1.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 30        | 19.11%  |
| Unknown        | 29        | 18.47%  |
| 1-20           | 27        | 17.2%   |
| 251-500        | 16        | 10.19%  |
| 501-1000       | 15        | 9.55%   |
| 21-50          | 13        | 8.28%   |
| More than 3000 | 8         | 5.1%    |
| 1001-2000      | 8         | 5.1%    |
| 51-100         | 7         | 4.46%   |
| 2001-3000      | 4         | 2.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 86        | 55.13%  |
| Unknown        | 29        | 18.59%  |
| 251-500        | 10        | 6.41%   |
| 21-50          | 10        | 6.41%   |
| 51-100         | 9         | 5.77%   |
| 501-1000       | 4         | 2.56%   |
| 101-250        | 3         | 1.92%   |
| 2001-3000      | 2         | 1.28%   |
| 1001-2000      | 2         | 1.28%   |
| More than 3000 | 1         | 0.64%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD3000BLFS-60YBU2 304GB                    | 2         | 14     | 7.69%   |
| WDC WD3200AAKX-0 320GB                         | 1         | 1      | 3.85%   |
| Toshiba MK4009GAL 40GB                         | 1         | 1      | 3.85%   |
| Toshiba MK3252GS 320GB                         | 1         | 1      | 3.85%   |
| Secure Net 256GB SSD                           | 1         | 1      | 3.85%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 3.85%   |
| Seagate ST500LM021-1KJ152 500GB                | 1         | 1      | 3.85%   |
| Seagate ST2000LM015-2E81 2TB                   | 1         | 1      | 3.85%   |
| SanDisk SDSA6MM 16GB SSD                       | 1         | 1      | 3.85%   |
| Samsung Electronics SSD PM81 128GB             | 1         | 1      | 3.85%   |
| Samsung Electronics SP0411N 40GB               | 1         | 2      | 3.85%   |
| Samsung Electronics HM160HI 160GB              | 1         | 2      | 3.85%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 1         | 1      | 3.85%   |
| Maxtor 2B020H1 20GB                            | 1         | 1      | 3.85%   |
| Kingmax SSD 120G                               | 1         | 1      | 3.85%   |
| Hitachi HTS725025A9A364 250GB                  | 1         | 1      | 3.85%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 1      | 3.85%   |
| Hitachi HTS722080K9A300 80GB                   | 1         | 1      | 3.85%   |
| Hitachi HTS72101 99GB                          | 1         | 1      | 3.85%   |
| Hitachi HTC426040G9AT00 40GB                   | 1         | 1      | 3.85%   |
| HGST HTS725050A7 500GB                         | 1         | 1      | 3.85%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 3.85%   |
| HGST HTS545050A7E380 500GB                     | 1         | 1      | 3.85%   |
| A-DATA Technology SU800 128GB SSD              | 1         | 1      | 3.85%   |
| A-DATA Technology IM2P33F8ABR1-1TB             | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 19.23%  |
| WDC                 | 3         | 15     | 11.54%  |
| Seagate             | 3         | 3      | 11.54%  |
| Samsung Electronics | 3         | 5      | 11.54%  |
| HGST                | 3         | 3      | 11.54%  |
| Toshiba             | 2         | 2      | 7.69%   |
| A-DATA Technology   | 2         | 2      | 7.69%   |
| Secure              | 1         | 1      | 3.85%   |
| SanDisk             | 1         | 1      | 3.85%   |
| Micron Technology   | 1         | 1      | 3.85%   |
| Maxtor              | 1         | 1      | 3.85%   |
| Kingmax             | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 5         | 5      | 26.32%  |
| WDC                 | 3         | 15     | 15.79%  |
| Seagate             | 3         | 3      | 15.79%  |
| HGST                | 3         | 3      | 15.79%  |
| Toshiba             | 2         | 2      | 10.53%  |
| Samsung Electronics | 2         | 4      | 10.53%  |
| Maxtor              | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 33     | 73.08%  |
| SSD  | 6         | 6      | 23.08%  |
| NVMe | 1         | 1      | 3.85%   |

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
| Works    | 92        | 212    | 54.44%  |
| Detected | 53        | 88     | 31.36%  |
| Malfunc  | 24        | 40     | 14.2%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 101       | 56.74%  |
| AMD                          | 20        | 11.24%  |
| Samsung Electronics          | 17        | 9.55%   |
| SanDisk                      | 6         | 3.37%   |
| LSI Logic / Symbios Logic    | 4         | 2.25%   |
| ADATA Technology             | 4         | 2.25%   |
| SK hynix                     | 3         | 1.69%   |
| Marvell Technology Group     | 3         | 1.69%   |
| VIA Technologies             | 2         | 1.12%   |
| Nvidia                       | 2         | 1.12%   |
| Micron Technology            | 2         | 1.12%   |
| KIOXIA                       | 2         | 1.12%   |
| Hewlett-Packard              | 2         | 1.12%   |
| ASMedia Technology           | 2         | 1.12%   |
| Adaptec                      | 2         | 1.12%   |
| Toshiba America Info Systems | 1         | 0.56%   |
| Promise Technology           | 1         | 0.56%   |
| Phison Electronics           | 1         | 0.56%   |
| Micron/Crucial Technology    | 1         | 0.56%   |
| Kingston Technology Company  | 1         | 0.56%   |
| Broadcom / LSI               | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 16        | 7.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11        | 5.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 4.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 7         | 3.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 2.31%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 2.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 5         | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 2.31%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 4         | 1.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 4         | 1.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4         | 1.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 1.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.39%   |
| Marvell Group 88SE9235 PCIe 2.0 x2 4-port SATA 6 Gb/s Controller               | 3         | 1.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.39%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.39%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.39%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 1.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 1.39%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 3         | 1.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.39%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 2         | 0.93%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.93%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 2         | 0.93%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 0.93%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.93%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 2         | 0.93%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 0.93%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 2         | 0.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 0.93%   |
| Intel 82371AB/EB/MB PIIX4 IDE                                                  | 2         | 0.93%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family IDE-r Controller                     | 2         | 0.93%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 2         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 0.93%   |
| AMD 400 Series Chipset SATA Controller                                         | 2         | 0.93%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 97        | 56.07%  |
| NVMe | 33        | 19.08%  |
| IDE  | 25        | 14.45%  |
| RAID | 14        | 8.09%   |
| SAS  | 4         | 2.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 121       | 78.57%  |
| AMD          | 24        | 15.58%  |
| ARM          | 6         | 3.9%    |
| iSH          | 1         | 0.65%   |
| CentaurHauls | 1         | 0.65%   |
| Unknown      | 1         | 0.65%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Celeron CPU N2807 @ 1.58GHz       | 3         | 1.89%   |
| Intel Xeon CPU L5640 @ 2.27GHz          | 2         | 1.26%   |
| Intel Pentium M processor 1.70GHz       | 2         | 1.26%   |
| Intel Pentium III (Coppermine)          | 2         | 1.26%   |
| Intel Core i9-10900 CPU @ 2.80GHz       | 2         | 1.26%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 2         | 1.26%   |
| Intel Core i5-4590T CPU @ 2.00GHz       | 2         | 1.26%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 1.26%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 1.26%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 2         | 1.26%   |
| Intel Core i3-4150 CPU @ 3.50GHz        | 2         | 1.26%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 2         | 1.26%   |
| Intel Celeron CPU J3455 @ 1.50GHz       | 2         | 1.26%   |
| Intel Celeron CPU J1900 @ 1.99GHz       | 2         | 1.26%   |
| Intel Atom CPU N455 @ 1.66GHz           | 2         | 1.26%   |
| Intel Atom CPU D525 @ 1.80GHz           | 2         | 1.26%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 1.26%   |
| ARM Processor                           | 2         | 1.26%   |
| AMD FX-8350 Eight-Core Processor        | 2         | 1.26%   |
| iSH Processor                           | 1         | 0.63%   |
| Intel Xeon Gold 5218 CPU @ 2.30GHz      | 1         | 0.63%   |
| Intel Xeon E-2176M CPU @ 2.70GHz        | 1         | 0.63%   |
| Intel Xeon CPU X3430 @ 2.40GHz          | 1         | 0.63%   |
| Intel Xeon CPU L5630 @ 2.13GHz          | 1         | 0.63%   |
| Intel Xeon CPU E3-1240L v3 @ 2.00GHz    | 1         | 0.63%   |
| Intel Pentium M processor 1.60GHz       | 1         | 0.63%   |
| Intel Pentium M processor 1.50GHz       | 1         | 0.63%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz  | 1         | 0.63%   |
| Intel Pentium CPU N4200 @ 1.10GHz       | 1         | 0.63%   |
| Intel Pentium CPU N3710 @ 1.60GHz       | 1         | 0.63%   |
| Intel Pentium CPU E5700 @ 3.00GHz       | 1         | 0.63%   |
| Intel Pentium CPU D1508 @ 2.20GHz       | 1         | 0.63%   |
| Intel Mobile Pentium MMX                | 1         | 0.63%   |
| Intel Genuine CPU T2400 @ 1.83GHz       | 1         | 0.63%   |
| Intel Genuine CPU 4000 @ 500MHz         | 1         | 0.63%   |
| Intel Core Solo CPU U1500 @ 1.33GHz     | 1         | 0.63%   |
| Intel Core m3-8100Y CPU @ 1.10GHz       | 1         | 0.63%   |
| Intel Core i9-9980HK CPU @ 2.40GHz      | 1         | 0.63%   |
| Intel Core i7-8700T CPU @ 2.40GHz       | 1         | 0.63%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 1         | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 32        | 20.38%  |
| Intel Celeron        | 18        | 11.46%  |
| Other                | 17        | 10.83%  |
| Intel Core i7        | 12        | 7.64%   |
| Intel Core i3        | 11        | 7.01%   |
| Intel Atom           | 11        | 7.01%   |
| Intel Xeon           | 6         | 3.82%   |
| AMD Ryzen 7          | 5         | 3.18%   |
| Intel Pentium M      | 4         | 2.55%   |
| Intel Pentium        | 4         | 2.55%   |
| Intel Core i9        | 3         | 1.91%   |
| Intel Core 2 Duo     | 3         | 1.91%   |
| AMD Ryzen 5          | 3         | 1.91%   |
| Intel Pentium III    | 2         | 1.27%   |
| Intel Genuine        | 2         | 1.27%   |
| Intel Core 2         | 2         | 1.27%   |
| AMD FX               | 2         | 1.27%   |
| AMD A4               | 2         | 1.27%   |
| Intel Xeon Gold      | 1         | 0.64%   |
| Intel Pentium Dual   | 1         | 0.64%   |
| Intel Core Solo      | 1         | 0.64%   |
| Intel Core m3        | 1         | 0.64%   |
| Intel Celeron M      | 1         | 0.64%   |
| ARM BCM              | 1         | 0.64%   |
| ARM ARMv7            | 1         | 0.64%   |
| ARM AArch64          | 1         | 0.64%   |
| AMD Turion 64 Mobile | 1         | 0.64%   |
| AMD Sempron          | 1         | 0.64%   |
| AMD Ryzen 9          | 1         | 0.64%   |
| AMD Ryzen 3          | 1         | 0.64%   |
| AMD G                | 1         | 0.64%   |
| AMD E2               | 1         | 0.64%   |
| AMD E1               | 1         | 0.64%   |
| AMD A8               | 1         | 0.64%   |
| AMD A6               | 1         | 0.64%   |
| AMD A10              | 1         | 0.64%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 61        | 39.1%   |
| 4       | 48        | 30.77%  |
| 1       | 18        | 11.54%  |
| 8       | 7         | 4.49%   |
| 6       | 6         | 3.85%   |
| Unknown | 5         | 3.21%   |
| 12      | 4         | 2.56%   |
| 10      | 2         | 1.28%   |
| 32      | 1         | 0.64%   |
| 24      | 1         | 0.64%   |
| 16      | 1         | 0.64%   |
| 14      | 1         | 0.64%   |
| 3       | 1         | 0.64%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 143       | 93.46%  |
| Unknown | 5         | 3.27%   |
| 2       | 4         | 2.61%   |
| 0       | 1         | 0.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 77        | 50.66%  |
| 2       | 70        | 46.05%  |
| Unknown | 5         | 3.29%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 81        | 52.26%  |
| 32-bit, 64-bit | 68        | 43.87%  |
| 32-bit         | 5         | 3.23%   |
| 64-bit         | 1         | 0.65%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 90        | 55.56%  |
| 0x306c3    | 7         | 4.32%   |
| 0x306a9    | 5         | 3.09%   |
| 0x30678    | 5         | 3.09%   |
| 0x906ea    | 4         | 2.47%   |
| 0x206c2    | 3         | 1.85%   |
| 0x106ca    | 3         | 1.85%   |
| 0x806eb    | 2         | 1.23%   |
| 0x806c1    | 2         | 1.23%   |
| 0x506e3    | 2         | 1.23%   |
| 0x506c9    | 2         | 1.23%   |
| 0x406c4    | 2         | 1.23%   |
| 0x206a7    | 2         | 1.23%   |
| 0x20655    | 2         | 1.23%   |
| 0x106e5    | 2         | 1.23%   |
| 0x1067a    | 2         | 1.23%   |
| 0x08108102 | 2         | 1.23%   |
| 0x06006704 | 2         | 1.23%   |
| 0xb0671    | 1         | 0.62%   |
| 0xa0671    | 1         | 0.62%   |
| 0xa0655    | 1         | 0.62%   |
| 0x906a3    | 1         | 0.62%   |
| 0x90672    | 1         | 0.62%   |
| 0x806ec    | 1         | 0.62%   |
| 0x806ea    | 1         | 0.62%   |
| 0x706e5    | 1         | 0.62%   |
| 0x6fd      | 1         | 0.62%   |
| 0x6f2      | 1         | 0.62%   |
| 0x6d8      | 1         | 0.62%   |
| 0x68a      | 1         | 0.62%   |
| 0x683      | 1         | 0.62%   |
| 0x306d4    | 1         | 0.62%   |
| 0x0a20120e | 1         | 0.62%   |
| 0x08701021 | 1         | 0.62%   |
| 0x08608103 | 1         | 0.62%   |
| 0x08108109 | 1         | 0.62%   |
| 0x0810100b | 1         | 0.62%   |
| 0x0800820d | 1         | 0.62%   |
| 0x06000817 | 1         | 0.62%   |
| 0x05000101 | 1         | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Silvermont       | 16        | 10.19%  |
| KabyLake         | 15        | 9.55%   |
| Unknown          | 14        | 8.92%   |
| Haswell          | 13        | 8.28%   |
| P6               | 9         | 5.73%   |
| IvyBridge        | 8         | 5.1%    |
| Westmere         | 7         | 4.46%   |
| Skylake          | 7         | 4.46%   |
| SandyBridge      | 7         | 4.46%   |
| Bonnell          | 6         | 3.82%   |
| Penryn           | 5         | 3.18%   |
| Goldmont         | 5         | 3.18%   |
| Zen+             | 4         | 2.55%   |
| Broadwell        | 4         | 2.55%   |
| Alderlake Hybrid | 4         | 2.55%   |
| TigerLake        | 3         | 1.91%   |
| Piledriver       | 3         | 1.91%   |
| Excavator        | 3         | 1.91%   |
| Core             | 3         | 1.91%   |
| CometLake        | 3         | 1.91%   |
| Zen 3            | 2         | 1.27%   |
| Zen 2            | 2         | 1.27%   |
| Nehalem          | 2         | 1.27%   |
| Jaguar           | 2         | 1.27%   |
| IceLake          | 2         | 1.27%   |
| Bobcat           | 2         | 1.27%   |
| Zen              | 1         | 0.64%   |
| Puma             | 1         | 0.64%   |
| K8 Hammer        | 1         | 0.64%   |
| K6               | 1         | 0.64%   |
| K10              | 1         | 0.64%   |
| Goldmont plus    | 1         | 0.64%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 103       | 63.98%  |
| AMD                        | 33        | 20.5%   |
| Nvidia                     | 15        | 9.32%   |
| Matrox Electronics Systems | 4         | 2.48%   |
| VIA Technologies           | 2         | 1.24%   |
| Neomagic                   | 2         | 1.24%   |
| S3 Graphics                | 1         | 0.62%   |
| ASPEED Technology          | 1         | 0.62%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 12        | 6.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 3.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 3.23%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 2.69%   |
| Intel HD Graphics 500                                                                    | 4         | 2.15%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.15%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 2.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 2.15%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 2.15%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 2.15%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.61%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.61%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 3         | 1.61%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.61%   |
| AMD ES1000                                                                               | 3         | 1.61%   |
| Intel UHD Graphics 620                                                                   | 2         | 1.08%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 1.08%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 1.08%   |
| Intel HD Graphics 630                                                                    | 2         | 1.08%   |
| Intel HD Graphics 620                                                                    | 2         | 1.08%   |
| Intel HD Graphics 530                                                                    | 2         | 1.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 1.08%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 2         | 1.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.08%   |
| Intel AlderLake-S GT1                                                                    | 2         | 1.08%   |
| Intel 82852/855GM Integrated Graphics Device                                             | 2         | 1.08%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 1.08%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 1.08%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 1.08%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 2         | 1.08%   |
| AMD Lucienne                                                                             | 2         | 1.08%   |
| VIA Technologies VT8623 [Apollo CLE266] integrated CastleRock graphics                   | 1         | 0.54%   |
| VIA Technologies KM400/KN400/P4M800 [S3 UniChrome]                                       | 1         | 0.54%   |
| S3 Graphics Savage 4                                                                     | 1         | 0.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.54%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.54%   |
| Nvidia GT218 [ION]                                                                       | 1         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 84        | 53.5%   |
| 1 x AMD         | 27        | 17.2%   |
| Other           | 9         | 5.73%   |
| 2 x Intel       | 8         | 5.1%    |
| Intel + Nvidia  | 7         | 4.46%   |
| 1 x Nvidia      | 6         | 3.82%   |
| Intel + AMD     | 4         | 2.55%   |
| 1 x Matrox      | 3         | 1.91%   |
| 1 x Neomagic    | 2         | 1.27%   |
| 2 x AMD         | 1         | 0.64%   |
| 1 x VIA         | 1         | 0.64%   |
| 1 x S3 Graphics | 1         | 0.64%   |
| Nvidia + Matrox | 1         | 0.64%   |
| 1 x ASPEED      | 1         | 0.64%   |
| AMD + VIA       | 1         | 0.64%   |
| AMD + Nvidia    | 1         | 0.64%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 128       | 82.05%  |
| Unknown     | 25        | 16.03%  |
| Proprietary | 3         | 1.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 129       | 83.77%  |
| 0.01-0.5   | 11        | 7.14%   |
| 1.01-2.0   | 4         | 2.6%    |
| 7.01-8.0   | 3         | 1.95%   |
| 0.51-1.0   | 3         | 1.95%   |
| 3.01-4.0   | 2         | 1.3%    |
| 2.01-3.0   | 1         | 0.65%   |
| 8.01-16.0  | 1         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 15        | 11.36%  |
| LG Display              | 12        | 9.09%   |
| BOE                     | 11        | 8.33%   |
| Samsung Electronics     | 10        | 7.58%   |
| Dell                    | 10        | 7.58%   |
| Chimei Innolux          | 8         | 6.06%   |
| Goldstar                | 7         | 5.3%    |
| BenQ                    | 5         | 3.79%   |
| AOC                     | 5         | 3.79%   |
| LG Philips              | 3         | 2.27%   |
| InfoVision              | 3         | 2.27%   |
| Hewlett-Packard         | 3         | 2.27%   |
| Chi Mei Optoelectronics | 3         | 2.27%   |
| Acer                    | 3         | 2.27%   |
| Sharp                   | 2         | 1.52%   |
| Philips                 | 2         | 1.52%   |
| Lenovo                  | 2         | 1.52%   |
| Jean                    | 2         | 1.52%   |
| HannStar                | 2         | 1.52%   |
| Belinea                 | 2         | 1.52%   |
| Apple                   | 2         | 1.52%   |
| Vizio                   | 1         | 0.76%   |
| ViewSonic               | 1         | 0.76%   |
| Sony                    | 1         | 0.76%   |
| SKY                     | 1         | 0.76%   |
| Sceptre Tech            | 1         | 0.76%   |
| Quanta Display          | 1         | 0.76%   |
| PANDA                   | 1         | 0.76%   |
| ONN                     | 1         | 0.76%   |
| Mi                      | 1         | 0.76%   |
| KVM                     | 1         | 0.76%   |
| Huion                   | 1         | 0.76%   |
| Envision                | 1         | 0.76%   |
| Elo Touch               | 1         | 0.76%   |
| Element                 | 1         | 0.76%   |
| EDI                     | 1         | 0.76%   |
| DENON                   | 1         | 0.76%   |
| CTC                     | 1         | 0.76%   |
| CSO                     | 1         | 0.76%   |
| CPT                     | 1         | 0.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch      | 3         | 2.08%   |
| Dell 2009W DEL4041 1680x1050 433x270mm 20.1-inch                      | 3         | 2.08%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 2         | 1.39%   |
| Jean JT229x6-4 JEN51C6 1680x1050 474x297mm 22.0-inch                  | 2         | 1.39%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch             | 2         | 1.39%   |
| Belinea B101555 MAX05DF 1024x768 304x228mm 15.0-inch                  | 2         | 1.39%   |
| Vizio D40f-J09 VIZ1044 1920x1080 890x490mm 40.0-inch                  | 1         | 0.69%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch              | 1         | 0.69%   |
| Sony TV *02 SNY9703 1920x1080 1439x809mm 65.0-inch                    | 1         | 0.69%   |
| SKY TV-monitor SKY0001 1920x1080 890x500mm 40.2-inch                  | 1         | 0.69%   |
| Sharp LCD Monitor SHP1513 1920x1080 309x174mm 14.0-inch               | 1         | 0.69%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch               | 1         | 0.69%   |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 520x320mm 24.0-inch        | 1         | 0.69%   |
| Samsung Electronics SyncMaster SAM0320 1680x1050 474x296mm 22.0-inch  | 1         | 0.69%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 380x300mm 19.1-inch  | 1         | 0.69%   |
| Samsung Electronics S27A950D SAM079E 1920x1080 598x336mm 27.0-inch    | 1         | 0.69%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 1         | 0.69%   |
| Samsung Electronics LS24AG30x SAM7179 1920x1080 527x296mm 23.8-inch   | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SEC5642 1280x768 305x183mm 14.0-inch  | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.69%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch  | 1         | 0.69%   |
| Quanta Display LCD Monitor QDS0020 1280x768 305x183mm 14.0-inch       | 1         | 0.69%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch               | 1         | 0.69%   |
| Philips PHL 216V6 PHLC10D 1920x1080 419x262mm 19.5-inch               | 1         | 0.69%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 1         | 0.69%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 1         | 0.69%   |
| Mi Monitor XMI2701 2560x1440 597x336mm 27.0-inch                      | 1         | 0.69%   |
| LG Philips LCD Monitor LPLE100 1280x800 331x207mm 15.4-inch           | 1         | 0.69%   |
| LG Philips LCD Monitor LPLB600 1280x800 260x160mm 12.0-inch           | 1         | 0.69%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch           | 1         | 0.69%   |
| LG Display LP116WH2-TLC1 LGD0232 1366x768 256x144mm 11.6-inch         | 1         | 0.69%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD0446 1920x1080 309x174mm 14.0-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD042E 2560x1700 272x181mm 12.9-inch          | 1         | 0.69%   |
| LG Display LCD Monitor LGD03DB 1366x768 345x194mm 15.6-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD0266 1366x768 344x194mm 15.5-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch           | 1         | 0.69%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 1         | 0.69%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 35        | 27.78%  |
| 1366x768 (WXGA)    | 27        | 21.43%  |
| 1680x1050 (WSXGA+) | 7         | 5.56%   |
| 3840x2160 (4K)     | 6         | 4.76%   |
| 2560x1440 (QHD)    | 6         | 4.76%   |
| 1280x800 (WXGA)    | 6         | 4.76%   |
| 1280x1024 (SXGA)   | 6         | 4.76%   |
| 1024x768 (XGA)     | 5         | 3.97%   |
| 3440x1440          | 4         | 3.17%   |
| 1920x1200 (WUXGA)  | 4         | 3.17%   |
| 1600x900 (HD+)     | 4         | 3.17%   |
| 1024x600           | 4         | 3.17%   |
| 1440x900 (WXGA+)   | 3         | 2.38%   |
| 2560x1080          | 2         | 1.59%   |
| 1360x768           | 2         | 1.59%   |
| 1280x768           | 2         | 1.59%   |
| 2880x1800          | 1         | 0.79%   |
| 2560x1700          | 1         | 0.79%   |
| 1280x960           | 1         | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 28        | 21.21%  |
| 14     | 13        | 9.85%   |
| 13     | 11        | 8.33%   |
| 17     | 10        | 7.58%   |
| 27     | 7         | 5.3%    |
| 23     | 7         | 5.3%    |
| 24     | 6         | 4.55%   |
| 20     | 5         | 3.79%   |
| 19     | 5         | 3.79%   |
| 11     | 5         | 3.79%   |
| 34     | 4         | 3.03%   |
| 21     | 4         | 3.03%   |
| 12     | 4         | 3.03%   |
| 10     | 4         | 3.03%   |
| 31     | 3         | 2.27%   |
| 22     | 3         | 2.27%   |
| 18     | 3         | 2.27%   |
| 40     | 2         | 1.52%   |
| 32     | 2         | 1.52%   |
| 72     | 1         | 0.76%   |
| 65     | 1         | 0.76%   |
| 60     | 1         | 0.76%   |
| 29     | 1         | 0.76%   |
| 25     | 1         | 0.76%   |
| 16     | 1         | 0.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 51        | 40.8%   |
| 501-600     | 18        | 14.4%   |
| 201-300     | 17        | 13.6%   |
| 401-500     | 15        | 12%     |
| 351-400     | 9         | 7.2%    |
| 701-800     | 5         | 4%      |
| 601-700     | 5         | 4%      |
| 801-900     | 2         | 1.6%    |
| 1001-1500   | 2         | 1.6%    |
| 1501-2000   | 1         | 0.8%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 76        | 66.09%  |
| 16/10 | 21        | 18.26%  |
| 5/4   | 6         | 5.22%   |
| 4/3   | 5         | 4.35%   |
| 21/9  | 5         | 4.35%   |
| 6/5   | 1         | 0.87%   |
| 3/2   | 1         | 0.87%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 27        | 21.43%  |
| 81-90          | 20        | 15.87%  |
| 201-250        | 15        | 11.9%   |
| 151-200        | 11        | 8.73%   |
| 351-500        | 8         | 6.35%   |
| 301-350        | 8         | 6.35%   |
| 141-150        | 6         | 4.76%   |
| 71-80          | 5         | 3.97%   |
| 51-60          | 5         | 3.97%   |
| 41-50          | 4         | 3.17%   |
| 121-130        | 4         | 3.17%   |
| More than 1000 | 3         | 2.38%   |
| 61-70          | 3         | 2.38%   |
| 251-300        | 2         | 1.59%   |
| 131-140        | 2         | 1.59%   |
| 501-1000       | 2         | 1.59%   |
| 111-120        | 1         | 0.79%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 43        | 36.44%  |
| 101-120       | 33        | 27.97%  |
| 121-160       | 29        | 24.58%  |
| 1-50          | 7         | 5.93%   |
| 161-240       | 4         | 3.39%   |
| More than 240 | 2         | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 103       | 65.61%  |
| 0     | 41        | 26.11%  |
| 2     | 11        | 7.01%   |
| 4     | 1         | 0.64%   |
| 3     | 1         | 0.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 78        | 34.82%  |
| Intel                           | 70        | 31.25%  |
| Qualcomm Atheros                | 23        | 10.27%  |
| Broadcom                        | 20        | 8.93%   |
| Xiaomi                          | 3         | 1.34%   |
| Marvell Technology Group        | 3         | 1.34%   |
| VIA Technologies                | 2         | 0.89%   |
| Qualcomm Atheros Communications | 2         | 0.89%   |
| Qualcomm                        | 2         | 0.89%   |
| MediaTek                        | 2         | 0.89%   |
| LSI                             | 2         | 0.89%   |
| Broadcom Limited                | 2         | 0.89%   |
| TP-Link                         | 1         | 0.45%   |
| T & A Mobile Phones             | 1         | 0.45%   |
| Sigma Designs                   | 1         | 0.45%   |
| Nvidia                          | 1         | 0.45%   |
| NetGear                         | 1         | 0.45%   |
| Microchip Technology            | 1         | 0.45%   |
| Mellanox Technologies           | 1         | 0.45%   |
| Google                          | 1         | 0.45%   |
| Dresden Elektronik              | 1         | 0.45%   |
| DisplayLink                     | 1         | 0.45%   |
| D-Link System                   | 1         | 0.45%   |
| D-Link                          | 1         | 0.45%   |
| Belkin Components               | 1         | 0.45%   |
| ASIX Electronics                | 1         | 0.45%   |
| AMD                             | 1         | 0.45%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 48        | 17.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 3.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 3.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 2.9%    |
| Intel Ethernet Controller I225-V                                  | 5         | 1.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 1.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 1.45%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.45%   |
| Intel I210 Gigabit Network Connection                             | 4         | 1.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 1.09%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 1.09%   |
| Intel Wireless 7265                                               | 3         | 1.09%   |
| Intel Wireless 3160                                               | 3         | 1.09%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.09%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.09%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.09%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 3         | 1.09%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.72%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.72%   |
| Qualcomm Atheros AR9271 802.11n                                   | 2         | 0.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.72%   |
| Intel Wireless-AC 9260                                            | 2         | 0.72%   |
| Intel Wireless 8260                                               | 2         | 0.72%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 0.72%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection          | 2         | 0.72%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.72%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.72%   |
| Intel Ethernet Connection (17) I219-LM                            | 2         | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 46        | 45.1%   |
| Qualcomm Atheros                | 20        | 19.61%  |
| Broadcom                        | 13        | 12.75%  |
| Realtek Semiconductor           | 12        | 11.76%  |
| Qualcomm Atheros Communications | 2         | 1.96%   |
| MediaTek                        | 2         | 1.96%   |
| Broadcom Limited                | 2         | 1.96%   |
| TP-Link                         | 1         | 0.98%   |
| NetGear                         | 1         | 0.98%   |
| Marvell Technology Group        | 1         | 0.98%   |
| D-Link                          | 1         | 0.98%   |
| Belkin Components               | 1         | 0.98%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 9         | 8.41%   |
| Intel Wireless 8265 / 8275                                                            | 4         | 3.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 4         | 3.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 3         | 2.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 3         | 2.8%    |
| Intel Wireless 7265                                                                   | 3         | 2.8%    |
| Intel Wireless 3160                                                                   | 3         | 2.8%    |
| Intel Wi-Fi 6 AX200                                                                   | 3         | 2.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 3         | 2.8%    |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 3         | 2.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 2         | 1.87%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 2         | 1.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 2         | 1.87%   |
| Intel Wireless-AC 9260                                                                | 2         | 1.87%   |
| Intel Wireless 8260                                                                   | 2         | 1.87%   |
| Intel Wi-Fi 6 AX201                                                                   | 2         | 1.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 2         | 1.87%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                              | 2         | 1.87%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 2         | 1.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 2         | 1.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 2         | 1.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 2         | 1.87%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 1.87%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                   | 1         | 0.93%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                                    | 1         | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 0.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.93%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                            | 1         | 0.93%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.93%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.93%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                             | 1         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 1         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 0.93%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.93%   |
| Qualcomm Atheros AR5413/AR5414 Wireless Network Adapter [AR5006X(S) 802.11abg]        | 1         | 0.93%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                                 | 1         | 0.93%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 1         | 0.93%   |
| NetGear WNDA3100v1 802.11abgn [Atheros AR9170+AR9104]                                 | 1         | 0.93%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 1         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 72        | 48.65%  |
| Intel                    | 43        | 29.05%  |
| Broadcom                 | 11        | 7.43%   |
| Qualcomm Atheros         | 5         | 3.38%   |
| Xiaomi                   | 3         | 2.03%   |
| VIA Technologies         | 2         | 1.35%   |
| Qualcomm                 | 2         | 1.35%   |
| Marvell Technology Group | 2         | 1.35%   |
| T & A Mobile Phones      | 1         | 0.68%   |
| Nvidia                   | 1         | 0.68%   |
| Microchip Technology     | 1         | 0.68%   |
| Mellanox Technologies    | 1         | 0.68%   |
| LSI                      | 1         | 0.68%   |
| DisplayLink              | 1         | 0.68%   |
| D-Link System            | 1         | 0.68%   |
| ASIX Electronics         | 1         | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 48        | 30.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 6.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 5.03%   |
| Intel Ethernet Controller I225-V                                  | 5         | 3.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 3.14%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 2.52%   |
| Intel I210 Gigabit Network Connection                             | 4         | 2.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 1.89%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.89%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.89%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 1.26%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 1.26%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.26%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.26%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.26%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.26%   |
| Intel Ethernet Connection (17) I219-LM                            | 2         | 1.26%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.26%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 1.26%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.63%   |
| T & A Mobile Phones TCL 20E                                       | 1         | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.63%   |
| Qualcomm Redmi 9T                                                 | 1         | 0.63%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.63%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.63%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 0.63%   |
| Mellanox MT26448 [ConnectX EN 10GigE, PCIe 2.0 5GT/s]             | 1         | 0.63%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.63%   |
| LSI ET-131x PCI-E Ethernet Controller                             | 1         | 0.63%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.63%   |
| Intel Ethernet Controller I226-V                                  | 1         | 0.63%   |
| Intel Ethernet Controller I219-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 128       | 55.41%  |
| WiFi     | 93        | 40.26%  |
| Modem    | 8         | 3.46%   |
| Unknown  | 2         | 0.87%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 86        | 61.43%  |
| WiFi     | 54        | 38.57%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 78        | 50.65%  |
| 1     | 55        | 35.71%  |
| 0     | 12        | 7.79%   |
| 3     | 4         | 2.6%    |
| 4     | 3         | 1.95%   |
| 5     | 2         | 1.3%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 123       | 79.87%  |
| Yes  | 31        | 20.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 41.89%  |
| Qualcomm Atheros Communications | 5         | 6.76%   |
| IMC Networks                    | 5         | 6.76%   |
| Cambridge Silicon Radio         | 5         | 6.76%   |
| Broadcom                        | 5         | 6.76%   |
| Realtek Semiconductor           | 4         | 5.41%   |
| Apple                           | 4         | 5.41%   |
| Lite-On Technology              | 3         | 4.05%   |
| Foxconn / Hon Hai               | 2         | 2.7%    |
| ASUSTek Computer                | 2         | 2.7%    |
| Toshiba                         | 1         | 1.35%   |
| MediaTek                        | 1         | 1.35%   |
| Marvell Semiconductor           | 1         | 1.35%   |
| Hewlett-Packard                 | 1         | 1.35%   |
| Edimax Technology               | 1         | 1.35%   |
| Dell                            | 1         | 1.35%   |
| Alps Electric                   | 1         | 1.35%   |
| Actions                         | 1         | 1.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 16%     |
| Intel AX201 Bluetooth                               | 6         | 8%      |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 5.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 4%      |
| Intel AX200 Bluetooth                               | 3         | 4%      |
| Realtek 802.11ac WLAN Adapter                       | 2         | 2.67%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 2.67%   |
| IMC Networks Bluetooth Device                       | 2         | 2.67%   |
| Apple Bluetooth Host Controller                     | 2         | 2.67%   |
| Toshiba Bluetooth Device                            | 1         | 1.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.33%   |
| Realtek Bluetooth Radio                             | 1         | 1.33%   |
| MediaTek Wireless_Device                            | 1         | 1.33%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 1         | 1.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.33%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.33%   |
| Intel Bluetooth Device                              | 1         | 1.33%   |
| Intel AX210 Bluetooth                               | 1         | 1.33%   |
| IMC Networks Wireless_Device                        | 1         | 1.33%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.33%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.33%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 1.33%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 1.33%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth     | 1         | 1.33%   |
| Edimax Bluetooth Adapter                            | 1         | 1.33%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 1.33%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.33%   |
| Broadcom BCM20702A0                                 | 1         | 1.33%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 1         | 1.33%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.33%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.33%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 1         | 1.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 1.33%   |
| Apple Bluetooth USB Host Controller                 | 1         | 1.33%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.33%   |
| Actions general adapter                             | 1         | 1.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 105       | 65.22%  |
| AMD                                  | 29        | 18.01%  |
| Nvidia                               | 8         | 4.97%   |
| C-Media Electronics                  | 3         | 1.86%   |
| VIA Technologies                     | 2         | 1.24%   |
| Logitech                             | 2         | 1.24%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.62%   |
| Texas Instruments                    | 1         | 0.62%   |
| SteelSeries ApS                      | 1         | 0.62%   |
| Sennheiser Communications            | 1         | 0.62%   |
| RODE Microphones                     | 1         | 0.62%   |
| Realtek Semiconductor                | 1         | 0.62%   |
| Native Instruments                   | 1         | 0.62%   |
| Generalplus Technology               | 1         | 0.62%   |
| Focusrite-Novation                   | 1         | 0.62%   |
| Creative Labs                        | 1         | 0.62%   |
| Cirrus Logic                         | 1         | 0.62%   |
| Apple                                | 1         | 0.62%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 4.81%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 4.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 3.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 3.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 3.37%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 3.37%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 6         | 2.88%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 2.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 2.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 2.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 2.4%    |
| AMD FCH Azalia Controller                                                                         | 5         | 2.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 1.44%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.44%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.44%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.44%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.44%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.44%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 2         | 0.96%   |
| Nvidia GA102 High Definition Audio Controller                                                     | 2         | 0.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 0.96%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.96%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 0.96%   |
| Intel DG2 Audio Controller                                                                        | 2         | 0.96%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.96%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 2         | 0.96%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 0.96%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 0.96%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.96%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.96%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 0.96%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.96%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 2         | 0.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 17.88%  |
| Unknown             | 24        | 15.89%  |
| SK hynix            | 23        | 15.23%  |
| Crucial             | 16        | 10.6%   |
| Micron Technology   | 14        | 9.27%   |
| Kingston            | 10        | 6.62%   |
| Elpida              | 10        | 6.62%   |
| Corsair             | 5         | 3.31%   |
| A-DATA Technology   | 4         | 2.65%   |
| Nanya Technology    | 2         | 1.32%   |
| Unknown             | 2         | 1.32%   |
| Visipro             | 1         | 0.66%   |
| Unknown (ABCD)      | 1         | 0.66%   |
| Transcend           | 1         | 0.66%   |
| Team                | 1         | 0.66%   |
| Ramaxel Technology  | 1         | 0.66%   |
| Qimonda             | 1         | 0.66%   |
| PNY                 | 1         | 0.66%   |
| Patriot             | 1         | 0.66%   |
| Novatech            | 1         | 0.66%   |
| Lexar               | 1         | 0.66%   |
| Hewlett-Packard     | 1         | 0.66%   |
| Gold Key            | 1         | 0.66%   |
| G.Skill             | 1         | 0.66%   |
| Cors                | 1         | 0.66%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 512MB SODIMM DDR                              | 3         | 1.72%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 2         | 1.15%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.15%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.15%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s            | 2         | 1.15%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 1.15%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.15%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.15%   |
| Elpida RAM EBJ41UF8BDW0-GN-F 4GB DIMM DDR3 1600MT/s              | 2         | 1.15%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s         | 2         | 1.15%   |
| Unknown                                                          | 2         | 1.15%   |
| Visipro RAM T2G88S1-H9H 2GB DIMM DDR3 1333MT/s                   | 1         | 0.57%   |
| Unknown RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 0.57%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 1         | 0.57%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 0.57%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.57%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.57%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 1         | 0.57%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 1         | 0.57%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.57%   |
| Unknown RAM Module 2GB SODIMM LPDDR4 2133MT/s                    | 1         | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR3 800MT/s                         | 1         | 0.57%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.57%   |
| Unknown RAM Module 256MB SODIMM DDR                              | 1         | 0.57%   |
| Unknown RAM Module 2048MB DIMM DDR3 1600MT/s                     | 1         | 0.57%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.57%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.57%   |
| Unknown RAM Module 1GB SODIMM DRAM                               | 1         | 0.57%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                      | 1         | 0.57%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.57%   |
| Unknown RAM Module 128MB DIMM DRAM                               | 1         | 0.57%   |
| Unknown RAM Module 128MB DIMM                                    | 1         | 0.57%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.57%   |
| Transcend RAM TS512MSK64W3N 4GB DIMM DDR3 1333MT/s               | 1         | 0.57%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s              | 1         | 0.57%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 58        | 47.93%  |
| DDR4    | 32        | 26.45%  |
| SDRAM   | 8         | 6.61%   |
| LPDDR3  | 5         | 4.13%   |
| DDR2    | 5         | 4.13%   |
| DDR     | 4         | 3.31%   |
| LPDDR4  | 3         | 2.48%   |
| DRAM    | 2         | 1.65%   |
| DDR5    | 2         | 1.65%   |
| Unknown | 2         | 1.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 66        | 54.55%  |
| DIMM         | 46        | 38.02%  |
| Row Of Chips | 7         | 5.79%   |
| Unknown      | 2         | 1.65%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 42        | 30.88%  |
| 4096  | 39        | 28.68%  |
| 2048  | 21        | 15.44%  |
| 1024  | 11        | 8.09%   |
| 16384 | 8         | 5.88%   |
| 512   | 6         | 4.41%   |
| 32768 | 5         | 3.68%   |
| 128   | 3         | 2.21%   |
| 256   | 1         | 0.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 37        | 27.01%  |
| Unknown | 12        | 8.76%   |
| 2667    | 11        | 8.03%   |
| 1333    | 11        | 8.03%   |
| 2400    | 10        | 7.3%    |
| 3200    | 9         | 6.57%   |
| 1334    | 7         | 5.11%   |
| 2133    | 5         | 3.65%   |
| 3600    | 4         | 2.92%   |
| 667     | 4         | 2.92%   |
| 1867    | 3         | 2.19%   |
| 1067    | 3         | 2.19%   |
| 3800    | 2         | 1.46%   |
| 1866    | 2         | 1.46%   |
| 1066    | 2         | 1.46%   |
| 8400    | 1         | 0.73%   |
| 5808    | 1         | 0.73%   |
| 4800    | 1         | 0.73%   |
| 4267    | 1         | 0.73%   |
| 4199    | 1         | 0.73%   |
| 3266    | 1         | 0.73%   |
| 3000    | 1         | 0.73%   |
| 2200    | 1         | 0.73%   |
| 1800    | 1         | 0.73%   |
| 1400    | 1         | 0.73%   |
| 1331    | 1         | 0.73%   |
| 1200    | 1         | 0.73%   |
| 800     | 1         | 0.73%   |
| 533     | 1         | 0.73%   |
| 133     | 1         | 0.73%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intermec Technologies | 1         | 33.33%  |
| Hewlett-Packard       | 1         | 33.33%  |
| Brother Industries    | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Intermec PC43t           | 1         | 25%     |
| HP LaserJet 1020         | 1         | 25%     |
| HP Deskjet 3050A         | 1         | 25%     |
| Brother HL-L2360D series | 1         | 25%     |

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
| Chicony Electronics                    | 14        | 18.92%  |
| Realtek Semiconductor                  | 8         | 10.81%  |
| Microdia                               | 8         | 10.81%  |
| IMC Networks                           | 8         | 10.81%  |
| Suyin                                  | 4         | 5.41%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 5.41%   |
| Bison Electronics                      | 4         | 5.41%   |
| Quanta                                 | 3         | 4.05%   |
| Apple                                  | 3         | 4.05%   |
| Z-Star Microelectronics                | 2         | 2.7%    |
| Syntek                                 | 2         | 2.7%    |
| Sunplus Innovation Technology          | 2         | 2.7%    |
| Acer                                   | 2         | 2.7%    |
| Trust                                  | 1         | 1.35%   |
| Silicon Motion                         | 1         | 1.35%   |
| Samsung Electronics                    | 1         | 1.35%   |
| Ricoh                                  | 1         | 1.35%   |
| MacroSilicon                           | 1         | 1.35%   |
| Luxvisions Innotech Limited            | 1         | 1.35%   |
| Logitech                               | 1         | 1.35%   |
| Lite-On Technology                     | 1         | 1.35%   |
| Linux Foundation                       | 1         | 1.35%   |
| Lenovo                                 | 1         | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 4         | 5.33%   |
| Microdia Integrated_Webcam_HD                       | 4         | 5.33%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 3         | 4%      |
| IMC Networks Integrated Camera                      | 3         | 4%      |
| Chicony HD Webcam                                   | 3         | 4%      |
| Realtek Acer 640 x 480 laptop camera                | 2         | 2.67%   |
| Microdia Laptop_Integrated_Webcam_2M                | 2         | 2.67%   |
| Chicony Integrated Camera                           | 2         | 2.67%   |
| Z-Star Vimicro USB2.0 Camera                        | 1         | 1.33%   |
| Z-Star A4 TECH USB2.0 PC Camera J                   | 1         | 1.33%   |
| Trust QHD Webcam                                    | 1         | 1.33%   |
| Syntek Integrated Camera                            | 1         | 1.33%   |
| Syntek EasyCamera                                   | 1         | 1.33%   |
| Suyin Integrated_Webcam_HD                          | 1         | 1.33%   |
| Suyin HP TrueVision HD                              | 1         | 1.33%   |
| Suyin HP High Definition 1MP Webcam                 | 1         | 1.33%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 1.33%   |
| Sunplus HP Universal Camera                         | 1         | 1.33%   |
| Sunplus HD WebCam                                   | 1         | 1.33%   |
| Silicon Motion NCM-G102                             | 1         | 1.33%   |
| Samsung Galaxy series, misc. (MTP mode)             | 1         | 1.33%   |
| Ricoh Visual Communication Camera VGP-VCC3 [R5U870] | 1         | 1.33%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 1.33%   |
| Realtek USB Camera                                  | 1         | 1.33%   |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 1.33%   |
| Quanta HP Wide Vision HD Camera                     | 1         | 1.33%   |
| Quanta HP TrueVision HD Camera                      | 1         | 1.33%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam      | 1         | 1.33%   |
| Microdia Integrated Webcam                          | 1         | 1.33%   |
| MacroSilicon MS210x Video Grabber [EasierCAP]       | 1         | 1.33%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 1.33%   |
| Logitech Webcam C270                                | 1         | 1.33%   |
| Logitech Webcam C170                                | 1         | 1.33%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 1.33%   |
| Linux Foundation EEM Gadget                         | 1         | 1.33%   |
| Lenovo Integrated Webcam                            | 1         | 1.33%   |
| IMC Networks VGA UVC WebCam                         | 1         | 1.33%   |
| IMC Networks USB2.0 UVC VGA WebCam                  | 1         | 1.33%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 1.33%   |
| Chicony USB2.0 FHD UVC WebCam                       | 1         | 1.33%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 3         | 33.33%  |
| Synaptics                  | 2         | 22.22%  |
| AuthenTec                  | 2         | 22.22%  |
| STMicroelectronics         | 1         | 11.11%  |
| Shenzhen Goodix Technology | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AuthenTec AES2810                                                          | 2         | 22.22%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 11.11%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 11.11%  |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 11.11%  |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 11.11%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 11.11%  |
| STMicroelectronics Fingerprint Reader                                      | 1         | 11.11%  |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Lenovo      | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 100       | 62.5%   |
| 1     | 36        | 22.5%   |
| 2     | 15        | 9.38%   |
| 4     | 5         | 3.13%   |
| 3     | 3         | 1.88%   |
| 7     | 1         | 0.63%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 28        | 29.79%  |
| Communication controller | 12        | 12.77%  |
| Net/wireless             | 10        | 10.64%  |
| Fingerprint reader       | 8         | 8.51%   |
| Modem                    | 7         | 7.45%   |
| Camera                   | 5         | 5.32%   |
| Bluetooth                | 5         | 5.32%   |
| Network                  | 3         | 3.19%   |
| Multimedia controller    | 3         | 3.19%   |
| Unassigned class         | 2         | 2.13%   |
| Storage/ata              | 2         | 2.13%   |
| Sound                    | 2         | 2.13%   |
| Net/ethernet             | 2         | 2.13%   |
| Chipcard                 | 2         | 2.13%   |
| Unclassified device      | 1         | 1.06%   |
| Storage                  | 1         | 1.06%   |
| Card reader              | 1         | 1.06%   |

