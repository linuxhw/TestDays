Linux in Russia - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Russia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Russia/Desktop/README.md) and [notebooks](/Location/Russia/Notebook/README.md).

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

Total: 30868

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Intel         | D2700DC AAG32420-602        | Desktop     | [a55bb5f425](https://linux-hardware.org/?probe=a55bb5f425) | Jun 01, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [3a12e41029](https://linux-hardware.org/?probe=3a12e41029) | Jun 01, 2022 |
| Lenovo        | 3190 NOK                    | Mini pc     | [5f6f023f22](https://linux-hardware.org/?probe=5f6f023f22) | Jun 01, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [60eba56233](https://linux-hardware.org/?probe=60eba56233) | Jun 01, 2022 |
| Acer          | AO756                       | Notebook    | [dd33104b58](https://linux-hardware.org/?probe=dd33104b58) | May 31, 2022 |
| Gigabyte      | N3160TN                     | Desktop     | [e2f44a8274](https://linux-hardware.org/?probe=e2f44a8274) | May 31, 2022 |
| Maibenben     | XiaoMai5                    | Notebook    | [db343bc7eb](https://linux-hardware.org/?probe=db343bc7eb) | May 31, 2022 |
| Gigabyte      | P31-S3L                     | Desktop     | [329c96c5af](https://linux-hardware.org/?probe=329c96c5af) | May 31, 2022 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [139f0688be](https://linux-hardware.org/?probe=139f0688be) | May 31, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [6d4b89571e](https://linux-hardware.org/?probe=6d4b89571e) | May 31, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [4dad4a323a](https://linux-hardware.org/?probe=4dad4a323a) | May 31, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [acc0a6ae9c](https://linux-hardware.org/?probe=acc0a6ae9c) | May 31, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [8188c1e0a8](https://linux-hardware.org/?probe=8188c1e0a8) | May 31, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [11f3206539](https://linux-hardware.org/?probe=11f3206539) | May 31, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [ee18866cf0](https://linux-hardware.org/?probe=ee18866cf0) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [44bd30c95d](https://linux-hardware.org/?probe=44bd30c95d) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [2a7545f0f9](https://linux-hardware.org/?probe=2a7545f0f9) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [12e45f7665](https://linux-hardware.org/?probe=12e45f7665) | May 31, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [2d6ef8ef23](https://linux-hardware.org/?probe=2d6ef8ef23) | May 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ec1c8e7378](https://linux-hardware.org/?probe=ec1c8e7378) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [c420e4cafb](https://linux-hardware.org/?probe=c420e4cafb) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [e562931a35](https://linux-hardware.org/?probe=e562931a35) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [26a3362040](https://linux-hardware.org/?probe=26a3362040) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [51595712dd](https://linux-hardware.org/?probe=51595712dd) | May 31, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [c60a969370](https://linux-hardware.org/?probe=c60a969370) | May 31, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [ce5695fd2a](https://linux-hardware.org/?probe=ce5695fd2a) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [0d31fa737e](https://linux-hardware.org/?probe=0d31fa737e) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [6e5a613444](https://linux-hardware.org/?probe=6e5a613444) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [7744e6a785](https://linux-hardware.org/?probe=7744e6a785) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [828c791c7c](https://linux-hardware.org/?probe=828c791c7c) | May 31, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [bc4e085e40](https://linux-hardware.org/?probe=bc4e085e40) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [ff8ca3e68b](https://linux-hardware.org/?probe=ff8ca3e68b) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [dbbe2e1b71](https://linux-hardware.org/?probe=dbbe2e1b71) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [099918e5b2](https://linux-hardware.org/?probe=099918e5b2) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [bdcf61dc44](https://linux-hardware.org/?probe=bdcf61dc44) | May 31, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [4ad9ca01bd](https://linux-hardware.org/?probe=4ad9ca01bd) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [3693e77fee](https://linux-hardware.org/?probe=3693e77fee) | May 31, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [7bd2b1490a](https://linux-hardware.org/?probe=7bd2b1490a) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [e41a23ba31](https://linux-hardware.org/?probe=e41a23ba31) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [a8aa698844](https://linux-hardware.org/?probe=a8aa698844) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [f0c6dbeb87](https://linux-hardware.org/?probe=f0c6dbeb87) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [ff453a32b6](https://linux-hardware.org/?probe=ff453a32b6) | May 31, 2022 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [bd7e895652](https://linux-hardware.org/?probe=bd7e895652) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [1ed72b7951](https://linux-hardware.org/?probe=1ed72b7951) | May 31, 2022 |
| iRU           | v1.0                        | Mini pc     | [15b125fb9e](https://linux-hardware.org/?probe=15b125fb9e) | May 31, 2022 |
| iRU           | v1.0                        | Mini pc     | [991e061d78](https://linux-hardware.org/?probe=991e061d78) | May 31, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [3ddbd38a08](https://linux-hardware.org/?probe=3ddbd38a08) | May 31, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [451572720e](https://linux-hardware.org/?probe=451572720e) | May 31, 2022 |
| Acer          | Aspire AV15-51              | Notebook    | [a9183103ee](https://linux-hardware.org/?probe=a9183103ee) | May 31, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [6960eaa85b](https://linux-hardware.org/?probe=6960eaa85b) | May 31, 2022 |
| Aquarius      | NS585                       | Notebook    | [222ff0011e](https://linux-hardware.org/?probe=222ff0011e) | May 31, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [eede963720](https://linux-hardware.org/?probe=eede963720) | May 31, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [e2dd690b16](https://linux-hardware.org/?probe=e2dd690b16) | May 31, 2022 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [5f44d47258](https://linux-hardware.org/?probe=5f44d47258) | May 31, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [eec83e91f0](https://linux-hardware.org/?probe=eec83e91f0) | May 31, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ece9950c65](https://linux-hardware.org/?probe=ece9950c65) | May 31, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [0368b3543a](https://linux-hardware.org/?probe=0368b3543a) | May 31, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [b450673fc0](https://linux-hardware.org/?probe=b450673fc0) | May 31, 2022 |
| Acer          | Aspire V5-571G              | Notebook    | [b1c8a97e57](https://linux-hardware.org/?probe=b1c8a97e57) | May 31, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [6f8785bd56](https://linux-hardware.org/?probe=6f8785bd56) | May 30, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [c39f904361](https://linux-hardware.org/?probe=c39f904361) | May 30, 2022 |
| Supermicro    | X10SRH-CFA                  | Server      | [775d543d9c](https://linux-hardware.org/?probe=775d543d9c) | May 30, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [d593c93e62](https://linux-hardware.org/?probe=d593c93e62) | May 30, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [8eda28a8d4](https://linux-hardware.org/?probe=8eda28a8d4) | May 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [2c33cbbbe2](https://linux-hardware.org/?probe=2c33cbbbe2) | May 30, 2022 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [3de5695c62](https://linux-hardware.org/?probe=3de5695c62) | May 30, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [b002ab0fe8](https://linux-hardware.org/?probe=b002ab0fe8) | May 30, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [e63df7d890](https://linux-hardware.org/?probe=e63df7d890) | May 30, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [ed0b412ea1](https://linux-hardware.org/?probe=ed0b412ea1) | May 30, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [1a67c11533](https://linux-hardware.org/?probe=1a67c11533) | May 30, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [a5eee874a5](https://linux-hardware.org/?probe=a5eee874a5) | May 30, 2022 |
| Huanan        | X99-TF                      | Desktop     | [cb08cd42a9](https://linux-hardware.org/?probe=cb08cd42a9) | May 30, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [90c386e917](https://linux-hardware.org/?probe=90c386e917) | May 30, 2022 |
| Gigabyte      | M52L-S3                     | Desktop     | [1add8e904e](https://linux-hardware.org/?probe=1add8e904e) | May 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [217b497fa9](https://linux-hardware.org/?probe=217b497fa9) | May 30, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [6a48092da4](https://linux-hardware.org/?probe=6a48092da4) | May 30, 2022 |
| ASUSTek       | VM40B                       | Desktop     | [7ca55e50b4](https://linux-hardware.org/?probe=7ca55e50b4) | May 30, 2022 |
| Intel         | DH55TC AAE70932-204         | Desktop     | [774da6cf18](https://linux-hardware.org/?probe=774da6cf18) | May 30, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [28bb098deb](https://linux-hardware.org/?probe=28bb098deb) | May 30, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [cc7ddb2cbc](https://linux-hardware.org/?probe=cc7ddb2cbc) | May 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [7b22d97da7](https://linux-hardware.org/?probe=7b22d97da7) | May 30, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [990a8757b8](https://linux-hardware.org/?probe=990a8757b8) | May 30, 2022 |
| Gigabyte      | M52L-S3                     | Desktop     | [e49b2962df](https://linux-hardware.org/?probe=e49b2962df) | May 30, 2022 |
| Toshiba       | Satellite U400              | Notebook    | [cbcfeeeb48](https://linux-hardware.org/?probe=cbcfeeeb48) | May 30, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [6dd26d47b1](https://linux-hardware.org/?probe=6dd26d47b1) | May 30, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [b7404d28e0](https://linux-hardware.org/?probe=b7404d28e0) | May 30, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [dab3ef3dee](https://linux-hardware.org/?probe=dab3ef3dee) | May 30, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [44e2ec7714](https://linux-hardware.org/?probe=44e2ec7714) | May 30, 2022 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [c70d152830](https://linux-hardware.org/?probe=c70d152830) | May 29, 2022 |
| Lenovo        | 3129 SDK0J40679 WIN 3273... | Desktop     | [0314182c7f](https://linux-hardware.org/?probe=0314182c7f) | May 29, 2022 |
| Dell          | Vostro 5468                 | Notebook    | [551400dba1](https://linux-hardware.org/?probe=551400dba1) | May 29, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [1a8dbccc21](https://linux-hardware.org/?probe=1a8dbccc21) | May 29, 2022 |
| ASUSTek       | UX51VZA                     | Notebook    | [c7c6e27cae](https://linux-hardware.org/?probe=c7c6e27cae) | May 29, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [5d2f3565ff](https://linux-hardware.org/?probe=5d2f3565ff) | May 29, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [b261adaa93](https://linux-hardware.org/?probe=b261adaa93) | May 29, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [458bf7fd6d](https://linux-hardware.org/?probe=458bf7fd6d) | May 29, 2022 |
| Chuwi         | LarkBook                    | Notebook    | [46e805f477](https://linux-hardware.org/?probe=46e805f477) | May 29, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [b1670ac481](https://linux-hardware.org/?probe=b1670ac481) | May 29, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [4fec6454b4](https://linux-hardware.org/?probe=4fec6454b4) | May 29, 2022 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [70e20c1143](https://linux-hardware.org/?probe=70e20c1143) | May 29, 2022 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [75d42068ac](https://linux-hardware.org/?probe=75d42068ac) | May 29, 2022 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [f4a35d313c](https://linux-hardware.org/?probe=f4a35d313c) | May 29, 2022 |
| HP            | Pavilion g6                 | Notebook    | [49471ad092](https://linux-hardware.org/?probe=49471ad092) | May 29, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [d1c4685112](https://linux-hardware.org/?probe=d1c4685112) | May 29, 2022 |
| KLLISRE       | X99-B5 V1.1                 | Desktop     | [a4e80143d1](https://linux-hardware.org/?probe=a4e80143d1) | May 29, 2022 |
| Acer          | Acadia V1.45                | Notebook    | [3734fbcb7d](https://linux-hardware.org/?probe=3734fbcb7d) | May 29, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [4e2d37a90d](https://linux-hardware.org/?probe=4e2d37a90d) | May 29, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [4647f374ee](https://linux-hardware.org/?probe=4647f374ee) | May 28, 2022 |
| HP            | ProBook 4540s               | Notebook    | [bb0ac4bfa9](https://linux-hardware.org/?probe=bb0ac4bfa9) | May 28, 2022 |
| Notebook      | W65_67SF                    | Notebook    | [c8ba646143](https://linux-hardware.org/?probe=c8ba646143) | May 28, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [44b220163b](https://linux-hardware.org/?probe=44b220163b) | May 28, 2022 |
| Dell          | Vostro 5468                 | Notebook    | [2784f8c927](https://linux-hardware.org/?probe=2784f8c927) | May 28, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [7e68528d56](https://linux-hardware.org/?probe=7e68528d56) | May 28, 2022 |
| Gigabyte      | 965P-S3                     | Desktop     | [2058a25c1e](https://linux-hardware.org/?probe=2058a25c1e) | May 28, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b861a73ade](https://linux-hardware.org/?probe=b861a73ade) | May 28, 2022 |
| Intel         | X79 V2.72B                  | Desktop     | [15d19c724b](https://linux-hardware.org/?probe=15d19c724b) | May 28, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [c7eceb86c2](https://linux-hardware.org/?probe=c7eceb86c2) | May 28, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b78390767c](https://linux-hardware.org/?probe=b78390767c) | May 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c3d1916e14](https://linux-hardware.org/?probe=c3d1916e14) | May 28, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [b42b75bb92](https://linux-hardware.org/?probe=b42b75bb92) | May 28, 2022 |
| ASRock        | H87 Pro4                    | Desktop     | [c2bbd20120](https://linux-hardware.org/?probe=c2bbd20120) | May 28, 2022 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [6c8e83728c](https://linux-hardware.org/?probe=6c8e83728c) | May 28, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [4f55b87c44](https://linux-hardware.org/?probe=4f55b87c44) | May 28, 2022 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [11bdd69dc0](https://linux-hardware.org/?probe=11bdd69dc0) | May 28, 2022 |
| Lenovo        | 3000 G410                   | Notebook    | [e745b05a55](https://linux-hardware.org/?probe=e745b05a55) | May 28, 2022 |
| ASUSTek       | X541UVK                     | Notebook    | [af4a83b898](https://linux-hardware.org/?probe=af4a83b898) | May 28, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [45ec66aa68](https://linux-hardware.org/?probe=45ec66aa68) | May 28, 2022 |
| Intel         | X79 V2.72B                  | Desktop     | [a1a4ad8594](https://linux-hardware.org/?probe=a1a4ad8594) | May 28, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [a634794de3](https://linux-hardware.org/?probe=a634794de3) | May 28, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [df2d7a274d](https://linux-hardware.org/?probe=df2d7a274d) | May 28, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [f276d6c00a](https://linux-hardware.org/?probe=f276d6c00a) | May 28, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [f67fdd8166](https://linux-hardware.org/?probe=f67fdd8166) | May 28, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [30fc2ddbf0](https://linux-hardware.org/?probe=30fc2ddbf0) | May 28, 2022 |
| Toshiba       | Satellite U300              | Notebook    | [1635f05f8d](https://linux-hardware.org/?probe=1635f05f8d) | May 28, 2022 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [f61c44c7b4](https://linux-hardware.org/?probe=f61c44c7b4) | May 28, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [a2f2dc2eee](https://linux-hardware.org/?probe=a2f2dc2eee) | May 27, 2022 |
| Gigabyte      | MCMLUCB-00                  | Desktop     | [90c886e471](https://linux-hardware.org/?probe=90c886e471) | May 27, 2022 |
| Acer          | Veriton X2665G              | Desktop     | [b07be0c2aa](https://linux-hardware.org/?probe=b07be0c2aa) | May 27, 2022 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [93de227774](https://linux-hardware.org/?probe=93de227774) | May 27, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [8cdbd043a4](https://linux-hardware.org/?probe=8cdbd043a4) | May 27, 2022 |
| AMI           | PCHK-Z83 Poslab_ECO         | Desktop     | [a3d73b70b2](https://linux-hardware.org/?probe=a3d73b70b2) | May 27, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [6c505927be](https://linux-hardware.org/?probe=6c505927be) | May 27, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [e5dd5ddffe](https://linux-hardware.org/?probe=e5dd5ddffe) | May 27, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [dc5f3161bd](https://linux-hardware.org/?probe=dc5f3161bd) | May 27, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [7c13c36e57](https://linux-hardware.org/?probe=7c13c36e57) | May 27, 2022 |
| Lenovo        | ThinkPad L460 20FVS14V00    | Notebook    | [63b7b8022c](https://linux-hardware.org/?probe=63b7b8022c) | May 27, 2022 |
| Panasonic     | CF-20-1                     | Notebook    | [a0a97f2bd1](https://linux-hardware.org/?probe=a0a97f2bd1) | May 27, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [6c5eea6e0a](https://linux-hardware.org/?probe=6c5eea6e0a) | May 27, 2022 |
| ASRock        | FM2A75M-DGS                 | Desktop     | [73260214ee](https://linux-hardware.org/?probe=73260214ee) | May 27, 2022 |
| Lenovo        | G575 20081                  | Notebook    | [14e84df65f](https://linux-hardware.org/?probe=14e84df65f) | May 27, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [e28ecda6a9](https://linux-hardware.org/?probe=e28ecda6a9) | May 27, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [5b4a1a0b2d](https://linux-hardware.org/?probe=5b4a1a0b2d) | May 27, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [8a9debf1da](https://linux-hardware.org/?probe=8a9debf1da) | May 27, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [c34cf96051](https://linux-hardware.org/?probe=c34cf96051) | May 27, 2022 |
| Intel         | DX58SO AAE29331-501         | Desktop     | [c574de14a5](https://linux-hardware.org/?probe=c574de14a5) | May 27, 2022 |
| Intel         | DX58SO AAE29331-501         | Desktop     | [7bbcdf39b4](https://linux-hardware.org/?probe=7bbcdf39b4) | May 27, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [c6088aecb4](https://linux-hardware.org/?probe=c6088aecb4) | May 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [4728993173](https://linux-hardware.org/?probe=4728993173) | May 27, 2022 |
| ONDA          | OBOOK 20 PLUS               | Notebook    | [c0152b04cb](https://linux-hardware.org/?probe=c0152b04cb) | May 27, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [2cca2a7979](https://linux-hardware.org/?probe=2cca2a7979) | May 27, 2022 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [d7adff5a41](https://linux-hardware.org/?probe=d7adff5a41) | May 27, 2022 |
| ASUSTek       | UX51VZA                     | Notebook    | [5507c9109e](https://linux-hardware.org/?probe=5507c9109e) | May 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0e98027e39](https://linux-hardware.org/?probe=0e98027e39) | May 26, 2022 |
| HP            | EliteBook x360 830 G6       | Convertible | [f9df0f4196](https://linux-hardware.org/?probe=f9df0f4196) | May 26, 2022 |
| HP            | 0B54h D                     | Desktop     | [d36988a09b](https://linux-hardware.org/?probe=d36988a09b) | May 26, 2022 |
| ASUSTek       | K43E                        | Notebook    | [968007a0a9](https://linux-hardware.org/?probe=968007a0a9) | May 26, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [305a4aa2be](https://linux-hardware.org/?probe=305a4aa2be) | May 26, 2022 |
| Acer          | AOD257                      | Notebook    | [149baf3a7b](https://linux-hardware.org/?probe=149baf3a7b) | May 26, 2022 |
| Lenovo        | 3000 G410                   | Notebook    | [3ebbe29445](https://linux-hardware.org/?probe=3ebbe29445) | May 26, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [36d7baa56d](https://linux-hardware.org/?probe=36d7baa56d) | May 26, 2022 |
| ASRock        | B85M Pro3                   | Desktop     | [661f30003c](https://linux-hardware.org/?probe=661f30003c) | May 26, 2022 |
| Dell          | Latitude E6430              | Notebook    | [5a914a9c89](https://linux-hardware.org/?probe=5a914a9c89) | May 26, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [e692b2a091](https://linux-hardware.org/?probe=e692b2a091) | May 26, 2022 |
| Intel         | DH55TC AAE70932-204         | Desktop     | [63c6e6a359](https://linux-hardware.org/?probe=63c6e6a359) | May 26, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3a8329a411](https://linux-hardware.org/?probe=3a8329a411) | May 26, 2022 |
| MSI           | A520M PRO                   | Desktop     | [3eb8006c14](https://linux-hardware.org/?probe=3eb8006c14) | May 26, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [f50e4f5314](https://linux-hardware.org/?probe=f50e4f5314) | May 26, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [134bd88895](https://linux-hardware.org/?probe=134bd88895) | May 26, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [3fc005308d](https://linux-hardware.org/?probe=3fc005308d) | May 26, 2022 |
| ASUSTek       | H87-PLUS                    | Desktop     | [b3abdcf25f](https://linux-hardware.org/?probe=b3abdcf25f) | May 26, 2022 |
| Gigabyte      | P61A-D3                     | Desktop     | [2ec61142d0](https://linux-hardware.org/?probe=2ec61142d0) | May 26, 2022 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [4198598e6f](https://linux-hardware.org/?probe=4198598e6f) | May 26, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [d5df82a4ce](https://linux-hardware.org/?probe=d5df82a4ce) | May 25, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [8bacf91a6b](https://linux-hardware.org/?probe=8bacf91a6b) | May 25, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [a34b43d64c](https://linux-hardware.org/?probe=a34b43d64c) | May 25, 2022 |
| Acer          | Extensa 5630                | Notebook    | [9728bad307](https://linux-hardware.org/?probe=9728bad307) | May 25, 2022 |
| Gigabyte      | Z590 AORUS ULTRA            | Desktop     | [544888143f](https://linux-hardware.org/?probe=544888143f) | May 25, 2022 |
| ECS           | G31T-M9                     | Desktop     | [cbc52e0724](https://linux-hardware.org/?probe=cbc52e0724) | May 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [74796bddc6](https://linux-hardware.org/?probe=74796bddc6) | May 25, 2022 |
| Gigabyte      | H67M-UD2H-B3                | Desktop     | [e355a95cfd](https://linux-hardware.org/?probe=e355a95cfd) | May 25, 2022 |
| Foxconn       | H61MXL/H61MXL-K             | Desktop     | [c44b877046](https://linux-hardware.org/?probe=c44b877046) | May 25, 2022 |
| IP3 Techno... | APN23                       | Notebook    | [4395a91f24](https://linux-hardware.org/?probe=4395a91f24) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [30207c3cdc](https://linux-hardware.org/?probe=30207c3cdc) | May 25, 2022 |
| IP3 Techno... | APN23                       | Notebook    | [281f1263dc](https://linux-hardware.org/?probe=281f1263dc) | May 25, 2022 |
| HONOR         | NMH-WCX9                    | Notebook    | [afdda4edc0](https://linux-hardware.org/?probe=afdda4edc0) | May 25, 2022 |
| HONOR         | NMH-WCX9                    | Notebook    | [222e1d3dd4](https://linux-hardware.org/?probe=222e1d3dd4) | May 25, 2022 |
| ZoomSmart     | A8006                       | Tablet      | [c5ae648f10](https://linux-hardware.org/?probe=c5ae648f10) | May 25, 2022 |
| HP            | Notebook                    | Notebook    | [05e785c8c2](https://linux-hardware.org/?probe=05e785c8c2) | May 25, 2022 |
| ASUSTek       | PRO H410T                   | Desktop     | [7d7a4c7536](https://linux-hardware.org/?probe=7d7a4c7536) | May 25, 2022 |
| HP            | Notebook                    | Notebook    | [17ca21b3a4](https://linux-hardware.org/?probe=17ca21b3a4) | May 25, 2022 |
| Gigabyte      | P75-D3                      | Desktop     | [becf8cce19](https://linux-hardware.org/?probe=becf8cce19) | May 25, 2022 |
| MSI           | A520M PRO                   | Desktop     | [9766bbe4c0](https://linux-hardware.org/?probe=9766bbe4c0) | May 25, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [dd46d19f05](https://linux-hardware.org/?probe=dd46d19f05) | May 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [dcbaf5defc](https://linux-hardware.org/?probe=dcbaf5defc) | May 25, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [93d4bd3b14](https://linux-hardware.org/?probe=93d4bd3b14) | May 25, 2022 |
| Samsung       | 530U3C/530U4C               | Notebook    | [a52fc8f40a](https://linux-hardware.org/?probe=a52fc8f40a) | May 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [dd0ffbf45b](https://linux-hardware.org/?probe=dd0ffbf45b) | May 25, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [37a8e41d00](https://linux-hardware.org/?probe=37a8e41d00) | May 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [213e81318d](https://linux-hardware.org/?probe=213e81318d) | May 25, 2022 |
| ASRock        | G41M-GS3                    | Desktop     | [85e26d9b09](https://linux-hardware.org/?probe=85e26d9b09) | May 25, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [5410acf8ab](https://linux-hardware.org/?probe=5410acf8ab) | May 25, 2022 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [28b7e84c50](https://linux-hardware.org/?probe=28b7e84c50) | May 24, 2022 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [5d78835d90](https://linux-hardware.org/?probe=5d78835d90) | May 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c8051b3bfc](https://linux-hardware.org/?probe=c8051b3bfc) | May 24, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [cab2025064](https://linux-hardware.org/?probe=cab2025064) | May 24, 2022 |
| OrangePi      | 3                           | Soc         | [657a314985](https://linux-hardware.org/?probe=657a314985) | May 24, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [35ba2b5a7a](https://linux-hardware.org/?probe=35ba2b5a7a) | May 24, 2022 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [64552194de](https://linux-hardware.org/?probe=64552194de) | May 24, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [4bf981574e](https://linux-hardware.org/?probe=4bf981574e) | May 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [692cdfaf7e](https://linux-hardware.org/?probe=692cdfaf7e) | May 24, 2022 |
| Acer          | Aspire TC-705               | Desktop     | [57bd3c5501](https://linux-hardware.org/?probe=57bd3c5501) | May 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [f680d813d7](https://linux-hardware.org/?probe=f680d813d7) | May 24, 2022 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [ea7f269697](https://linux-hardware.org/?probe=ea7f269697) | May 24, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [7e4dbd239c](https://linux-hardware.org/?probe=7e4dbd239c) | May 24, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [5f3d17f133](https://linux-hardware.org/?probe=5f3d17f133) | May 24, 2022 |
| HPE           | ProLiant DL160 Gen10        | Server      | [dc086873ea](https://linux-hardware.org/?probe=dc086873ea) | May 24, 2022 |
| ICL           | Unknown                     | Notebook    | [07ff87175d](https://linux-hardware.org/?probe=07ff87175d) | May 24, 2022 |
| Intel         | D2500HN AAG81480-500        | Desktop     | [bc39db0484](https://linux-hardware.org/?probe=bc39db0484) | May 24, 2022 |
| Acer          | Acadia V1.45                | Notebook    | [f99b47321c](https://linux-hardware.org/?probe=f99b47321c) | May 24, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [2979dfecb7](https://linux-hardware.org/?probe=2979dfecb7) | May 24, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [068b759d6e](https://linux-hardware.org/?probe=068b759d6e) | May 24, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [5514e95c95](https://linux-hardware.org/?probe=5514e95c95) | May 24, 2022 |
| HP            | 0B54h D                     | Desktop     | [9dc982847a](https://linux-hardware.org/?probe=9dc982847a) | May 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [322f05198a](https://linux-hardware.org/?probe=322f05198a) | May 24, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [873dd31f8e](https://linux-hardware.org/?probe=873dd31f8e) | May 23, 2022 |
| Acer          | Aspire C24-865              | All in one  | [e61762236d](https://linux-hardware.org/?probe=e61762236d) | May 23, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [1613ab8b42](https://linux-hardware.org/?probe=1613ab8b42) | May 23, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [0e8f0ed773](https://linux-hardware.org/?probe=0e8f0ed773) | May 23, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [13c83f5c47](https://linux-hardware.org/?probe=13c83f5c47) | May 23, 2022 |
| HP            | 8523 A01                    | Mini pc     | [d3affbbdf4](https://linux-hardware.org/?probe=d3affbbdf4) | May 23, 2022 |
| ASUSTek       | C60M1-I                     | Desktop     | [169d96b73b](https://linux-hardware.org/?probe=169d96b73b) | May 23, 2022 |
| HP            | Notebook                    | Notebook    | [3e5ee0fcbb](https://linux-hardware.org/?probe=3e5ee0fcbb) | May 23, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [413a708e81](https://linux-hardware.org/?probe=413a708e81) | May 23, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [193d7daf36](https://linux-hardware.org/?probe=193d7daf36) | May 23, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [0d1907cc6f](https://linux-hardware.org/?probe=0d1907cc6f) | May 23, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [ea8294c786](https://linux-hardware.org/?probe=ea8294c786) | May 23, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [a888bc633f](https://linux-hardware.org/?probe=a888bc633f) | May 23, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [4277ebe7e7](https://linux-hardware.org/?probe=4277ebe7e7) | May 23, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [6bfc4ef24f](https://linux-hardware.org/?probe=6bfc4ef24f) | May 23, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [3629d7c796](https://linux-hardware.org/?probe=3629d7c796) | May 23, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [9938056162](https://linux-hardware.org/?probe=9938056162) | May 23, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [02393f8ed7](https://linux-hardware.org/?probe=02393f8ed7) | May 23, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [f8257427c6](https://linux-hardware.org/?probe=f8257427c6) | May 23, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [3c545f2940](https://linux-hardware.org/?probe=3c545f2940) | May 23, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [9450237ae3](https://linux-hardware.org/?probe=9450237ae3) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [5c74b9f6e4](https://linux-hardware.org/?probe=5c74b9f6e4) | May 23, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [b3b2ee08af](https://linux-hardware.org/?probe=b3b2ee08af) | May 23, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [765d22e752](https://linux-hardware.org/?probe=765d22e752) | May 23, 2022 |
| ASUSTek       | Z87-A                       | Desktop     | [861da6e999](https://linux-hardware.org/?probe=861da6e999) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [68b7552bfa](https://linux-hardware.org/?probe=68b7552bfa) | May 23, 2022 |
| Samsung       | SR70S/SR71S                 | Notebook    | [53642077bd](https://linux-hardware.org/?probe=53642077bd) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [be23737ca8](https://linux-hardware.org/?probe=be23737ca8) | May 22, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [bee7a3bfc6](https://linux-hardware.org/?probe=bee7a3bfc6) | May 22, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5ab3662d65](https://linux-hardware.org/?probe=5ab3662d65) | May 22, 2022 |
| Acer          | TravelMate P2510-G2-MG      | Notebook    | [d736bb9da8](https://linux-hardware.org/?probe=d736bb9da8) | May 22, 2022 |
| Gigabyte      | H55M-USB3                   | Desktop     | [08e7d1f0d2](https://linux-hardware.org/?probe=08e7d1f0d2) | May 22, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [ed2bf9256c](https://linux-hardware.org/?probe=ed2bf9256c) | May 22, 2022 |
| Sony          | VPCSA2Z9R                   | Notebook    | [5697622de7](https://linux-hardware.org/?probe=5697622de7) | May 22, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [1af89e5ffb](https://linux-hardware.org/?probe=1af89e5ffb) | May 22, 2022 |
| Intel         | X79                         | Desktop     | [904bf5297c](https://linux-hardware.org/?probe=904bf5297c) | May 22, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [2a6ba92f67](https://linux-hardware.org/?probe=2a6ba92f67) | May 22, 2022 |
| Unknown       | Intel X79                   | Desktop     | [52d19fdb12](https://linux-hardware.org/?probe=52d19fdb12) | May 22, 2022 |
| ASUSTek       | P8P67-M                     | Desktop     | [83917315b7](https://linux-hardware.org/?probe=83917315b7) | May 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [c986b274be](https://linux-hardware.org/?probe=c986b274be) | May 22, 2022 |
| HP            | 15-dc1018ur                 | Notebook    | [aceb1a1011](https://linux-hardware.org/?probe=aceb1a1011) | May 22, 2022 |
| ASUSTek       | N53Jq                       | Notebook    | [f8e79d7221](https://linux-hardware.org/?probe=f8e79d7221) | May 22, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [b64b85418b](https://linux-hardware.org/?probe=b64b85418b) | May 22, 2022 |
| Acer          | Aspire 5734Z                | Notebook    | [6c47938031](https://linux-hardware.org/?probe=6c47938031) | May 22, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [58dcd147b7](https://linux-hardware.org/?probe=58dcd147b7) | May 22, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [aeb22efb30](https://linux-hardware.org/?probe=aeb22efb30) | May 22, 2022 |
| ASUSTek       | N61Da                       | Notebook    | [e96feda0f9](https://linux-hardware.org/?probe=e96feda0f9) | May 22, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [092f8be315](https://linux-hardware.org/?probe=092f8be315) | May 22, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [1993c161fd](https://linux-hardware.org/?probe=1993c161fd) | May 22, 2022 |
| Samsung       | 530U3C/530U4C               | Notebook    | [cd12ece868](https://linux-hardware.org/?probe=cd12ece868) | May 22, 2022 |
| ASUSTek       | N61Da                       | Notebook    | [406255b638](https://linux-hardware.org/?probe=406255b638) | May 22, 2022 |
| Intel         | Unknown                     | Notebook    | [9f704ad203](https://linux-hardware.org/?probe=9f704ad203) | May 22, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [0e14154fc0](https://linux-hardware.org/?probe=0e14154fc0) | May 22, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [27be8e7d2f](https://linux-hardware.org/?probe=27be8e7d2f) | May 21, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [a94464dc7e](https://linux-hardware.org/?probe=a94464dc7e) | May 21, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [aaf4857517](https://linux-hardware.org/?probe=aaf4857517) | May 21, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [85974104c5](https://linux-hardware.org/?probe=85974104c5) | May 21, 2022 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [bd3a571c95](https://linux-hardware.org/?probe=bd3a571c95) | May 21, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [f697c39b33](https://linux-hardware.org/?probe=f697c39b33) | May 21, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [1c63e5e513](https://linux-hardware.org/?probe=1c63e5e513) | May 21, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [77ba979b27](https://linux-hardware.org/?probe=77ba979b27) | May 21, 2022 |
| ASUSTek       | N53Jq                       | Notebook    | [a0d24cad99](https://linux-hardware.org/?probe=a0d24cad99) | May 21, 2022 |
| Lenovo        | Z710 20250                  | Notebook    | [ce719211e5](https://linux-hardware.org/?probe=ce719211e5) | May 21, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [12aa7cac29](https://linux-hardware.org/?probe=12aa7cac29) | May 21, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [4dce3bdb3a](https://linux-hardware.org/?probe=4dce3bdb3a) | May 21, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [082a1ac531](https://linux-hardware.org/?probe=082a1ac531) | May 21, 2022 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [9fbbff1973](https://linux-hardware.org/?probe=9fbbff1973) | May 21, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [280302cc7b](https://linux-hardware.org/?probe=280302cc7b) | May 20, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [0245a34484](https://linux-hardware.org/?probe=0245a34484) | May 20, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [d29d7ee0ad](https://linux-hardware.org/?probe=d29d7ee0ad) | May 20, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [6e8eed720d](https://linux-hardware.org/?probe=6e8eed720d) | May 20, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [91fe66d159](https://linux-hardware.org/?probe=91fe66d159) | May 20, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [193e7d05a0](https://linux-hardware.org/?probe=193e7d05a0) | May 20, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [327da044de](https://linux-hardware.org/?probe=327da044de) | May 20, 2022 |
| Acer          | Aspire 8940G                | Notebook    | [f6f8622b30](https://linux-hardware.org/?probe=f6f8622b30) | May 20, 2022 |
| Chatreey      | AC1-DP                      | Desktop     | [aefe90ce82](https://linux-hardware.org/?probe=aefe90ce82) | May 20, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [e2a3654000](https://linux-hardware.org/?probe=e2a3654000) | May 20, 2022 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [9330599ada](https://linux-hardware.org/?probe=9330599ada) | May 20, 2022 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [4ae1475168](https://linux-hardware.org/?probe=4ae1475168) | May 20, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [a9d54e08c9](https://linux-hardware.org/?probe=a9d54e08c9) | May 20, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [ad85836549](https://linux-hardware.org/?probe=ad85836549) | May 20, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [71797f9336](https://linux-hardware.org/?probe=71797f9336) | May 20, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [de4e9f2e03](https://linux-hardware.org/?probe=de4e9f2e03) | May 20, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [25cf1b1ec9](https://linux-hardware.org/?probe=25cf1b1ec9) | May 20, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [afce6e6cee](https://linux-hardware.org/?probe=afce6e6cee) | May 20, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [da744c49fd](https://linux-hardware.org/?probe=da744c49fd) | May 20, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [d26b453c29](https://linux-hardware.org/?probe=d26b453c29) | May 20, 2022 |
| Acer          | Unknown                     | Notebook    | [c8e97c31be](https://linux-hardware.org/?probe=c8e97c31be) | May 20, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [696932f291](https://linux-hardware.org/?probe=696932f291) | May 20, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [be0659ce93](https://linux-hardware.org/?probe=be0659ce93) | May 20, 2022 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | Notebook    | [88882c2c94](https://linux-hardware.org/?probe=88882c2c94) | May 19, 2022 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | Notebook    | [08638290ff](https://linux-hardware.org/?probe=08638290ff) | May 19, 2022 |
| HP            | Pavilion dv6                | Notebook    | [b83a85cdbb](https://linux-hardware.org/?probe=b83a85cdbb) | May 19, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [f87ba7a410](https://linux-hardware.org/?probe=f87ba7a410) | May 19, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [ee3726a591](https://linux-hardware.org/?probe=ee3726a591) | May 19, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [9f4f14ebd1](https://linux-hardware.org/?probe=9f4f14ebd1) | May 19, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [04c26fdb1b](https://linux-hardware.org/?probe=04c26fdb1b) | May 19, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [db9d229530](https://linux-hardware.org/?probe=db9d229530) | May 19, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [be383d0db4](https://linux-hardware.org/?probe=be383d0db4) | May 19, 2022 |
| Lenovo        | G585 20137                  | Notebook    | [5eae6b5a34](https://linux-hardware.org/?probe=5eae6b5a34) | May 19, 2022 |
| ASUSTek       | F5RL                        | Notebook    | [30e7f880d5](https://linux-hardware.org/?probe=30e7f880d5) | May 19, 2022 |
| HP            | Pavilion dv6                | Notebook    | [50fc292dd2](https://linux-hardware.org/?probe=50fc292dd2) | May 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d61129ec0f](https://linux-hardware.org/?probe=d61129ec0f) | May 19, 2022 |
| Sony          | SVE1512H1RB                 | Notebook    | [3894ca4fe2](https://linux-hardware.org/?probe=3894ca4fe2) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [0e0fc0905a](https://linux-hardware.org/?probe=0e0fc0905a) | May 19, 2022 |
| MSI           | H510TI-S01                  | Desktop     | [efe42ef07a](https://linux-hardware.org/?probe=efe42ef07a) | May 19, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [b78055bf57](https://linux-hardware.org/?probe=b78055bf57) | May 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [94d2bd3233](https://linux-hardware.org/?probe=94d2bd3233) | May 19, 2022 |
| iRU           | LPGR.469559.012             | Desktop     | [9163b267bc](https://linux-hardware.org/?probe=9163b267bc) | May 19, 2022 |
| ZoomSmart     | A8006                       | Tablet      | [2db4f5f5ff](https://linux-hardware.org/?probe=2db4f5f5ff) | May 19, 2022 |
| ASUSTek       | P6T WS PRO                  | Desktop     | [1064f07721](https://linux-hardware.org/?probe=1064f07721) | May 19, 2022 |
| ASUSTek       | V241IC-R                    | All in one  | [48add8dc01](https://linux-hardware.org/?probe=48add8dc01) | May 19, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [d5649e5a3a](https://linux-hardware.org/?probe=d5649e5a3a) | May 19, 2022 |
| ASUSTek       | N53Jq                       | Notebook    | [b8c3bdc3de](https://linux-hardware.org/?probe=b8c3bdc3de) | May 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [7a6f957def](https://linux-hardware.org/?probe=7a6f957def) | May 18, 2022 |
| Gigabyte      | B365 HD3                    | Desktop     | [82bd3dbfe9](https://linux-hardware.org/?probe=82bd3dbfe9) | May 18, 2022 |
| HP            | 2820h                       | Desktop     | [af311c3a41](https://linux-hardware.org/?probe=af311c3a41) | May 18, 2022 |
| Gigabyte      | H55-UD3H                    | Desktop     | [e766ad4581](https://linux-hardware.org/?probe=e766ad4581) | May 18, 2022 |
| Gigabyte      | B75-D3V                     | Desktop     | [81bd72f465](https://linux-hardware.org/?probe=81bd72f465) | May 18, 2022 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [23879a78d3](https://linux-hardware.org/?probe=23879a78d3) | May 18, 2022 |
| ASUSTek       | P5E                         | Desktop     | [4038be4f49](https://linux-hardware.org/?probe=4038be4f49) | May 18, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [cc38925ca1](https://linux-hardware.org/?probe=cc38925ca1) | May 18, 2022 |
| Lenovo        | ThinkPad L520 5017BK4       | Notebook    | [087884b808](https://linux-hardware.org/?probe=087884b808) | May 18, 2022 |
| ICL           | H310SB-TM                   | All in one  | [72c2889a81](https://linux-hardware.org/?probe=72c2889a81) | May 18, 2022 |
| Gigabyte      | E350N WIN8                  | Desktop     | [31923a075f](https://linux-hardware.org/?probe=31923a075f) | May 18, 2022 |
| Gigabyte      | P61A-D3                     | Desktop     | [dd4b8bf4e7](https://linux-hardware.org/?probe=dd4b8bf4e7) | May 18, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [01dc038814](https://linux-hardware.org/?probe=01dc038814) | May 18, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [ee6e90c751](https://linux-hardware.org/?probe=ee6e90c751) | May 17, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [5f2fb2e8bd](https://linux-hardware.org/?probe=5f2fb2e8bd) | May 17, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [1f15f778fd](https://linux-hardware.org/?probe=1f15f778fd) | May 17, 2022 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [a54f021132](https://linux-hardware.org/?probe=a54f021132) | May 17, 2022 |
| ASUSTek       | GL703VD                     | Notebook    | [4e6962ed18](https://linux-hardware.org/?probe=4e6962ed18) | May 17, 2022 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [5feb18b37b](https://linux-hardware.org/?probe=5feb18b37b) | May 17, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9a7ac94310](https://linux-hardware.org/?probe=9a7ac94310) | May 17, 2022 |
| EPoX Compu... | nForce3 DDR: 8KDA3I Seri... | Desktop     | [4b38991c7a](https://linux-hardware.org/?probe=4b38991c7a) | May 17, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [6eba5e9bf2](https://linux-hardware.org/?probe=6eba5e9bf2) | May 17, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [0d1a3da50a](https://linux-hardware.org/?probe=0d1a3da50a) | May 17, 2022 |
| ICL           | NJ50_70CU                   | Notebook    | [c16ccbe95b](https://linux-hardware.org/?probe=c16ccbe95b) | May 17, 2022 |
| Foxconn       | 945 7MD Series              | Desktop     | [523af6afbd](https://linux-hardware.org/?probe=523af6afbd) | May 17, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [ef70fd2699](https://linux-hardware.org/?probe=ef70fd2699) | May 17, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7fe3dc4301](https://linux-hardware.org/?probe=7fe3dc4301) | May 17, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [eb3f9d541e](https://linux-hardware.org/?probe=eb3f9d541e) | May 17, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [2a8a53c628](https://linux-hardware.org/?probe=2a8a53c628) | May 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [153dab147a](https://linux-hardware.org/?probe=153dab147a) | May 17, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [63fd31813f](https://linux-hardware.org/?probe=63fd31813f) | May 17, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [d71e59e4ef](https://linux-hardware.org/?probe=d71e59e4ef) | May 17, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [a3b4c84c89](https://linux-hardware.org/?probe=a3b4c84c89) | May 17, 2022 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [1589892eec](https://linux-hardware.org/?probe=1589892eec) | May 17, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [a38bac0479](https://linux-hardware.org/?probe=a38bac0479) | May 17, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1ab7586d5f](https://linux-hardware.org/?probe=1ab7586d5f) | May 17, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [c024e69cf4](https://linux-hardware.org/?probe=c024e69cf4) | May 17, 2022 |
| Gigabyte      | H67N-USB3-B3                | Desktop     | [8feeed71b7](https://linux-hardware.org/?probe=8feeed71b7) | May 17, 2022 |
| Packard Be... | EasyNote TV44HC             | Notebook    | [5186d57b24](https://linux-hardware.org/?probe=5186d57b24) | May 17, 2022 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [aee504bd13](https://linux-hardware.org/?probe=aee504bd13) | May 17, 2022 |
| Gigabyte      | P61A-D3                     | Desktop     | [d495e3aa63](https://linux-hardware.org/?probe=d495e3aa63) | May 17, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [ac65146c38](https://linux-hardware.org/?probe=ac65146c38) | May 17, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [acd5c94fc8](https://linux-hardware.org/?probe=acd5c94fc8) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [909b5d9be4](https://linux-hardware.org/?probe=909b5d9be4) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [4487dba8aa](https://linux-hardware.org/?probe=4487dba8aa) | May 16, 2022 |
| MSI           | GL62M 7REX                  | Notebook    | [767733bb1e](https://linux-hardware.org/?probe=767733bb1e) | May 16, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [486b786e45](https://linux-hardware.org/?probe=486b786e45) | May 16, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [86de85c736](https://linux-hardware.org/?probe=86de85c736) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [e3b15e462d](https://linux-hardware.org/?probe=e3b15e462d) | May 16, 2022 |
| Sony          | VPCSB1V9R                   | Notebook    | [9dfafea956](https://linux-hardware.org/?probe=9dfafea956) | May 16, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [0de514cd0b](https://linux-hardware.org/?probe=0de514cd0b) | May 16, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [cad77c8a2c](https://linux-hardware.org/?probe=cad77c8a2c) | May 16, 2022 |
| HP            | 86F1 10100                  | All in one  | [6790e43c6e](https://linux-hardware.org/?probe=6790e43c6e) | May 16, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [bcc80f9edc](https://linux-hardware.org/?probe=bcc80f9edc) | May 16, 2022 |
| Acer          | Aspire TC-705               | Desktop     | [b0873a64d2](https://linux-hardware.org/?probe=b0873a64d2) | May 16, 2022 |
| Acer          | Extensa 2519                | Notebook    | [e07a5704a8](https://linux-hardware.org/?probe=e07a5704a8) | May 16, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [9646d7027f](https://linux-hardware.org/?probe=9646d7027f) | May 16, 2022 |
| ASUSTek       | 1011PX                      | Notebook    | [fb414ad293](https://linux-hardware.org/?probe=fb414ad293) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [633d4d525b](https://linux-hardware.org/?probe=633d4d525b) | May 16, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [e99a8117ba](https://linux-hardware.org/?probe=e99a8117ba) | May 16, 2022 |
| ASUSTek       | PRO H410T                   | Desktop     | [8ededa12ef](https://linux-hardware.org/?probe=8ededa12ef) | May 16, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [697a89162e](https://linux-hardware.org/?probe=697a89162e) | May 16, 2022 |
| ASUSTek       | K52JT                       | Notebook    | [66067f39a0](https://linux-hardware.org/?probe=66067f39a0) | May 16, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f5817a11ec](https://linux-hardware.org/?probe=f5817a11ec) | May 16, 2022 |
| ASUSTek       | K52JT                       | Notebook    | [68862e338e](https://linux-hardware.org/?probe=68862e338e) | May 16, 2022 |
| Sony          | SVE1512H1RW                 | Notebook    | [0a75cef1f7](https://linux-hardware.org/?probe=0a75cef1f7) | May 16, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [fb9fa22053](https://linux-hardware.org/?probe=fb9fa22053) | May 16, 2022 |
| Gigabyte      | MCMLUCB-00                  | Desktop     | [1ad57be6ad](https://linux-hardware.org/?probe=1ad57be6ad) | May 16, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f64f274146](https://linux-hardware.org/?probe=f64f274146) | May 16, 2022 |
| MSI           | GL62M 7REX                  | Notebook    | [79f61f478d](https://linux-hardware.org/?probe=79f61f478d) | May 16, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [1cabcd1318](https://linux-hardware.org/?probe=1cabcd1318) | May 16, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [e12a8b383f](https://linux-hardware.org/?probe=e12a8b383f) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6767fef6cf](https://linux-hardware.org/?probe=6767fef6cf) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [28c62dd04c](https://linux-hardware.org/?probe=28c62dd04c) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [f37b79c82d](https://linux-hardware.org/?probe=f37b79c82d) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [086e18d971](https://linux-hardware.org/?probe=086e18d971) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [75dc798956](https://linux-hardware.org/?probe=75dc798956) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6881a4923e](https://linux-hardware.org/?probe=6881a4923e) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [040dc0a951](https://linux-hardware.org/?probe=040dc0a951) | May 16, 2022 |
| Sony          | SVE1512H1RB                 | Notebook    | [60dba4994d](https://linux-hardware.org/?probe=60dba4994d) | May 16, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [44da55727f](https://linux-hardware.org/?probe=44da55727f) | May 16, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [91700e1cb8](https://linux-hardware.org/?probe=91700e1cb8) | May 16, 2022 |
| HP            | ProBook 6470b               | Notebook    | [9cdf33bcc1](https://linux-hardware.org/?probe=9cdf33bcc1) | May 16, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [ea483c055f](https://linux-hardware.org/?probe=ea483c055f) | May 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [a15788c695](https://linux-hardware.org/?probe=a15788c695) | May 15, 2022 |
| HP            | Compaq 6830s                | Notebook    | [edca070359](https://linux-hardware.org/?probe=edca070359) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF               | Server      | [60ec07883b](https://linux-hardware.org/?probe=60ec07883b) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF               | Server      | [912e712657](https://linux-hardware.org/?probe=912e712657) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF               | Server      | [3229b1f14c](https://linux-hardware.org/?probe=3229b1f14c) | May 15, 2022 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [45da577bc5](https://linux-hardware.org/?probe=45da577bc5) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF               | Server      | [ad5b15b222](https://linux-hardware.org/?probe=ad5b15b222) | May 15, 2022 |
| ECS           | BSWI-D2                     | Desktop     | [f5ad79fb60](https://linux-hardware.org/?probe=f5ad79fb60) | May 15, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [a777a043ac](https://linux-hardware.org/?probe=a777a043ac) | May 15, 2022 |
| ASRock        | 880GMH/U3S3                 | Desktop     | [57c85dd37a](https://linux-hardware.org/?probe=57c85dd37a) | May 15, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [e5121153f7](https://linux-hardware.org/?probe=e5121153f7) | May 15, 2022 |
| Acer          | Acadia V1.45                | Notebook    | [778c730721](https://linux-hardware.org/?probe=778c730721) | May 15, 2022 |
| MSI           | J1900I                      | Desktop     | [86f37a71f5](https://linux-hardware.org/?probe=86f37a71f5) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF               | Server      | [6539922005](https://linux-hardware.org/?probe=6539922005) | May 15, 2022 |
| MSI           | J1900I                      | Desktop     | [5a48d83596](https://linux-hardware.org/?probe=5a48d83596) | May 15, 2022 |
| Supermicro    | B11SPE-CPU-TF               | Server      | [0c77bbd30d](https://linux-hardware.org/?probe=0c77bbd30d) | May 15, 2022 |
| Samsung       | SQ45S70S                    | Notebook    | [fd62971ba0](https://linux-hardware.org/?probe=fd62971ba0) | May 15, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [28b47bc364](https://linux-hardware.org/?probe=28b47bc364) | May 15, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [0e5792fc9f](https://linux-hardware.org/?probe=0e5792fc9f) | May 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [021f95ce24](https://linux-hardware.org/?probe=021f95ce24) | May 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9ce2f8b28b](https://linux-hardware.org/?probe=9ce2f8b28b) | May 15, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [bedc08df5b](https://linux-hardware.org/?probe=bedc08df5b) | May 15, 2022 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [18cf20e9a2](https://linux-hardware.org/?probe=18cf20e9a2) | May 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ce128aaf56](https://linux-hardware.org/?probe=ce128aaf56) | May 15, 2022 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [15d32c7578](https://linux-hardware.org/?probe=15d32c7578) | May 15, 2022 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [770fbfefd3](https://linux-hardware.org/?probe=770fbfefd3) | May 15, 2022 |
| Acer          | AO532h                      | Notebook    | [6055013560](https://linux-hardware.org/?probe=6055013560) | May 15, 2022 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [eab1bcc17e](https://linux-hardware.org/?probe=eab1bcc17e) | May 15, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [59b99933d2](https://linux-hardware.org/?probe=59b99933d2) | May 14, 2022 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [8baee6f2e6](https://linux-hardware.org/?probe=8baee6f2e6) | May 14, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [289c04b1dd](https://linux-hardware.org/?probe=289c04b1dd) | May 14, 2022 |
| ECS           | P43T-A2                     | Desktop     | [d3be091ef5](https://linux-hardware.org/?probe=d3be091ef5) | May 14, 2022 |
| ECS           | P43T-A2                     | Desktop     | [412be434c0](https://linux-hardware.org/?probe=412be434c0) | May 14, 2022 |
| Unknown       | GB01                        | Stick pc    | [8bbc53c60c](https://linux-hardware.org/?probe=8bbc53c60c) | May 14, 2022 |
| HP            | Pavilion g6                 | Notebook    | [6106cdb29d](https://linux-hardware.org/?probe=6106cdb29d) | May 14, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [5fb1304e59](https://linux-hardware.org/?probe=5fb1304e59) | May 14, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [b202236bb9](https://linux-hardware.org/?probe=b202236bb9) | May 14, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [5a53456915](https://linux-hardware.org/?probe=5a53456915) | May 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [2cb841c94e](https://linux-hardware.org/?probe=2cb841c94e) | May 14, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [1e48c58c4d](https://linux-hardware.org/?probe=1e48c58c4d) | May 14, 2022 |
| ASUSTek       | N73SV                       | Notebook    | [062b80185f](https://linux-hardware.org/?probe=062b80185f) | May 14, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [7781811703](https://linux-hardware.org/?probe=7781811703) | May 14, 2022 |
| Gigabyte      | P61A-D3                     | Desktop     | [5abe5033c6](https://linux-hardware.org/?probe=5abe5033c6) | May 14, 2022 |
| Acer          | Aspire 5349                 | Notebook    | [17c18c2202](https://linux-hardware.org/?probe=17c18c2202) | May 14, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [6846e2d548](https://linux-hardware.org/?probe=6846e2d548) | May 14, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [c4a3491741](https://linux-hardware.org/?probe=c4a3491741) | May 14, 2022 |
| ASRock        | G41M-VS2                    | Desktop     | [9cf93ac497](https://linux-hardware.org/?probe=9cf93ac497) | May 14, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [abbad40394](https://linux-hardware.org/?probe=abbad40394) | May 14, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [9fece02922](https://linux-hardware.org/?probe=9fece02922) | May 14, 2022 |
| Supermicro    | B11SPE-CPU-TF               | Server      | [85a5b4c02f](https://linux-hardware.org/?probe=85a5b4c02f) | May 14, 2022 |
| ASUSTek       | M2A-VM                      | Desktop     | [7708e385fb](https://linux-hardware.org/?probe=7708e385fb) | May 14, 2022 |
| ASRock        | B75M-DGS R2.0               | Desktop     | [1d61892cb0](https://linux-hardware.org/?probe=1d61892cb0) | May 14, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [607d5b3c79](https://linux-hardware.org/?probe=607d5b3c79) | May 14, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [a8033573ef](https://linux-hardware.org/?probe=a8033573ef) | May 14, 2022 |
| Supermicro    | B11SPE-CPU-TF               | Server      | [d9f3fb8d37](https://linux-hardware.org/?probe=d9f3fb8d37) | May 14, 2022 |
| Supermicro    | B11SPE-CPU-TF               | Server      | [fdf91b6130](https://linux-hardware.org/?probe=fdf91b6130) | May 13, 2022 |
| Supermicro    | B11SPE-CPU-TF               | Server      | [9c97cfa2bc](https://linux-hardware.org/?probe=9c97cfa2bc) | May 13, 2022 |
| Supermicro    | B11SPE-CPU-TF               | Server      | [6f63fd533c](https://linux-hardware.org/?probe=6f63fd533c) | May 13, 2022 |
| Toshiba       | Satellite C850-D1W          | Notebook    | [7d7d976bad](https://linux-hardware.org/?probe=7d7d976bad) | May 13, 2022 |
| Lenovo        | ThinkPad X200 7455FPG       | Notebook    | [9c403ef686](https://linux-hardware.org/?probe=9c403ef686) | May 13, 2022 |
| Unknown       | GB01                        | Stick pc    | [68de5db99f](https://linux-hardware.org/?probe=68de5db99f) | May 13, 2022 |
| Intel         | S5000VSA                    | Server      | [0f7afc638d](https://linux-hardware.org/?probe=0f7afc638d) | May 13, 2022 |
| Pegatron      | H36ST                       | Notebook    | [7795d9059b](https://linux-hardware.org/?probe=7795d9059b) | May 13, 2022 |
| T-Platform... | TF307-MB-S-C                | Soc         | [9c8a709fe8](https://linux-hardware.org/?probe=9c8a709fe8) | May 13, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [30085d6f41](https://linux-hardware.org/?probe=30085d6f41) | May 13, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [4aeb51ba34](https://linux-hardware.org/?probe=4aeb51ba34) | May 13, 2022 |
| Acer          | Aspire ES1-511              | Notebook    | [0b5faf442b](https://linux-hardware.org/?probe=0b5faf442b) | May 13, 2022 |
| eMachines     | eME732ZG                    | Notebook    | [459bdc2a9c](https://linux-hardware.org/?probe=459bdc2a9c) | May 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5ea934bd19](https://linux-hardware.org/?probe=5ea934bd19) | May 12, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [9f9e071e39](https://linux-hardware.org/?probe=9f9e071e39) | May 12, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [531749d46b](https://linux-hardware.org/?probe=531749d46b) | May 12, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [b1ef2f3b4f](https://linux-hardware.org/?probe=b1ef2f3b4f) | May 12, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [fad48ff5dd](https://linux-hardware.org/?probe=fad48ff5dd) | May 12, 2022 |
| eMachines     | eME732ZG                    | Notebook    | [6304ba86ef](https://linux-hardware.org/?probe=6304ba86ef) | May 12, 2022 |
| MSI           | 870S-C45                    | Desktop     | [eefd6f4979](https://linux-hardware.org/?probe=eefd6f4979) | May 12, 2022 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [4293bc4b1c](https://linux-hardware.org/?probe=4293bc4b1c) | May 12, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [e50b53ba02](https://linux-hardware.org/?probe=e50b53ba02) | May 12, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [5674fc5620](https://linux-hardware.org/?probe=5674fc5620) | May 12, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [0b80003bf8](https://linux-hardware.org/?probe=0b80003bf8) | May 12, 2022 |
| ASUSTek       | H110-PLUS                   | Desktop     | [56b6d0f154](https://linux-hardware.org/?probe=56b6d0f154) | May 12, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [319f70da4e](https://linux-hardware.org/?probe=319f70da4e) | May 12, 2022 |
| ASUSTek       | H110-PLUS                   | Desktop     | [cf7ae5c07b](https://linux-hardware.org/?probe=cf7ae5c07b) | May 12, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [41c7fd7bcc](https://linux-hardware.org/?probe=41c7fd7bcc) | May 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [53aed63d64](https://linux-hardware.org/?probe=53aed63d64) | May 12, 2022 |
| ICL           | Unknown                     | Notebook    | [cfb2a7c82f](https://linux-hardware.org/?probe=cfb2a7c82f) | May 12, 2022 |
| ICL           | Unknown                     | Notebook    | [858558d9fe](https://linux-hardware.org/?probe=858558d9fe) | May 12, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [c0b6c60fb0](https://linux-hardware.org/?probe=c0b6c60fb0) | May 12, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [367b6b7bcb](https://linux-hardware.org/?probe=367b6b7bcb) | May 12, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [9baa4a9f57](https://linux-hardware.org/?probe=9baa4a9f57) | May 12, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [4cd5815707](https://linux-hardware.org/?probe=4cd5815707) | May 12, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [a4f4e7c199](https://linux-hardware.org/?probe=a4f4e7c199) | May 12, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [e4107f3e84](https://linux-hardware.org/?probe=e4107f3e84) | May 12, 2022 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [658347ec76](https://linux-hardware.org/?probe=658347ec76) | May 12, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [3494019436](https://linux-hardware.org/?probe=3494019436) | May 11, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [d14b68d592](https://linux-hardware.org/?probe=d14b68d592) | May 11, 2022 |
| HP            | 2AA6 PVT                    | Desktop     | [18fb552bc2](https://linux-hardware.org/?probe=18fb552bc2) | May 11, 2022 |
| Dell          | G3 3590                     | Notebook    | [4dbfe959b2](https://linux-hardware.org/?probe=4dbfe959b2) | May 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | Notebook    | [7360a98fae](https://linux-hardware.org/?probe=7360a98fae) | May 11, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [c37decd47b](https://linux-hardware.org/?probe=c37decd47b) | May 11, 2022 |
| Unknown       | Unknown                     | Notebook    | [c01cff4387](https://linux-hardware.org/?probe=c01cff4387) | May 11, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [9e60c12b38](https://linux-hardware.org/?probe=9e60c12b38) | May 11, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [e405d209d4](https://linux-hardware.org/?probe=e405d209d4) | May 11, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | Desktop     | [cfb12880a5](https://linux-hardware.org/?probe=cfb12880a5) | May 11, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [a6873c7d7b](https://linux-hardware.org/?probe=a6873c7d7b) | May 11, 2022 |
| ASUSTek       | B75M-A                      | Desktop     | [70ef1387b3](https://linux-hardware.org/?probe=70ef1387b3) | May 11, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [819ca99934](https://linux-hardware.org/?probe=819ca99934) | May 11, 2022 |
| mtech         | MTL1578                     | Notebook    | [bf25c26ea0](https://linux-hardware.org/?probe=bf25c26ea0) | May 11, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [66bb3248d5](https://linux-hardware.org/?probe=66bb3248d5) | May 11, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [610c48d5c2](https://linux-hardware.org/?probe=610c48d5c2) | May 11, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [67db373009](https://linux-hardware.org/?probe=67db373009) | May 11, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [74f198b961](https://linux-hardware.org/?probe=74f198b961) | May 11, 2022 |
| ASUSTek       | UX310UQK                    | Notebook    | [1af1efeb46](https://linux-hardware.org/?probe=1af1efeb46) | May 11, 2022 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [4060102b0d](https://linux-hardware.org/?probe=4060102b0d) | May 11, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [06a97b74c2](https://linux-hardware.org/?probe=06a97b74c2) | May 11, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [e118437b55](https://linux-hardware.org/?probe=e118437b55) | May 11, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [083ee33b93](https://linux-hardware.org/?probe=083ee33b93) | May 11, 2022 |
| Samsung       | R519/R719                   | Notebook    | [8deee99c2d](https://linux-hardware.org/?probe=8deee99c2d) | May 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [04df39ea84](https://linux-hardware.org/?probe=04df39ea84) | May 11, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [dba988f81d](https://linux-hardware.org/?probe=dba988f81d) | May 10, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [657c27be04](https://linux-hardware.org/?probe=657c27be04) | May 10, 2022 |
| HP            | ENVY dv6                    | Notebook    | [81f03e297f](https://linux-hardware.org/?probe=81f03e297f) | May 10, 2022 |
| Huanan        | X99 F8D V2.2                | Desktop     | [af98aacde1](https://linux-hardware.org/?probe=af98aacde1) | May 10, 2022 |
| MSI           | Z370 TOMAHAWK               | Desktop     | [89222d6d5a](https://linux-hardware.org/?probe=89222d6d5a) | May 10, 2022 |
| ASRock        | 880GMH/U3S3                 | Desktop     | [73e6cb3b6b](https://linux-hardware.org/?probe=73e6cb3b6b) | May 10, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [0b131ecdc3](https://linux-hardware.org/?probe=0b131ecdc3) | May 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [03fc6852e2](https://linux-hardware.org/?probe=03fc6852e2) | May 10, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [a940d31b37](https://linux-hardware.org/?probe=a940d31b37) | May 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [4932c3cd73](https://linux-hardware.org/?probe=4932c3cd73) | May 10, 2022 |
| Acer          | Nitro AN515-56              | Notebook    | [897ae85fd2](https://linux-hardware.org/?probe=897ae85fd2) | May 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [7b42128ef0](https://linux-hardware.org/?probe=7b42128ef0) | May 10, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [38838b0da0](https://linux-hardware.org/?probe=38838b0da0) | May 10, 2022 |
| Supermicro    | X8DTU                       | Server      | [a421259aa2](https://linux-hardware.org/?probe=a421259aa2) | May 10, 2022 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [b0a089f59e](https://linux-hardware.org/?probe=b0a089f59e) | May 10, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [81cd3de099](https://linux-hardware.org/?probe=81cd3de099) | May 09, 2022 |
| Supermicro    | X8DTU                       | Server      | [1aa81c04d0](https://linux-hardware.org/?probe=1aa81c04d0) | May 09, 2022 |
| Supermicro    | X8DTU                       | Server      | [730652a210](https://linux-hardware.org/?probe=730652a210) | May 09, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [a5deca63d5](https://linux-hardware.org/?probe=a5deca63d5) | May 09, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [21b06f22da](https://linux-hardware.org/?probe=21b06f22da) | May 09, 2022 |
| Lenovo        | Kabini CRB 31900059 STD ... | Desktop     | [a862dd454d](https://linux-hardware.org/?probe=a862dd454d) | May 09, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [876ec3c7c3](https://linux-hardware.org/?probe=876ec3c7c3) | May 09, 2022 |
| ASUSTek       | M2N-VM HDMI                 | Desktop     | [28ef8fe01d](https://linux-hardware.org/?probe=28ef8fe01d) | May 09, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [36fe76c490](https://linux-hardware.org/?probe=36fe76c490) | May 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [0d64940271](https://linux-hardware.org/?probe=0d64940271) | May 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [86acc529d3](https://linux-hardware.org/?probe=86acc529d3) | May 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c3da40525e](https://linux-hardware.org/?probe=c3da40525e) | May 09, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [5fbac11232](https://linux-hardware.org/?probe=5fbac11232) | May 09, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [7da59c1f4c](https://linux-hardware.org/?probe=7da59c1f4c) | May 09, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [48a7e74662](https://linux-hardware.org/?probe=48a7e74662) | May 09, 2022 |
| Dell          | Latitude 7400               | Notebook    | [a0600c38f3](https://linux-hardware.org/?probe=a0600c38f3) | May 09, 2022 |
| Timi          | TM1607                      | Notebook    | [3cdd16d975](https://linux-hardware.org/?probe=3cdd16d975) | May 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [11cb46c902](https://linux-hardware.org/?probe=11cb46c902) | May 08, 2022 |
| Gigabyte      | P31-S3G                     | Desktop     | [98c00acfd0](https://linux-hardware.org/?probe=98c00acfd0) | May 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [ff7a5266e3](https://linux-hardware.org/?probe=ff7a5266e3) | May 08, 2022 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | Notebook    | [98439b17f3](https://linux-hardware.org/?probe=98439b17f3) | May 08, 2022 |
| HP            | Notebook                    | Notebook    | [3e346da5bf](https://linux-hardware.org/?probe=3e346da5bf) | May 08, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [c7e61a8776](https://linux-hardware.org/?probe=c7e61a8776) | May 08, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [b532438c73](https://linux-hardware.org/?probe=b532438c73) | May 08, 2022 |
| KLLISRE       | X79 V2.72S                  | Desktop     | [24c5f93b26](https://linux-hardware.org/?probe=24c5f93b26) | May 08, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [05b35ee0cc](https://linux-hardware.org/?probe=05b35ee0cc) | May 08, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [ee12f03755](https://linux-hardware.org/?probe=ee12f03755) | May 08, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [61776a02d4](https://linux-hardware.org/?probe=61776a02d4) | May 07, 2022 |
| K-Systems     | Crestline+ICH8M             | Notebook    | [e94aa3f1ff](https://linux-hardware.org/?probe=e94aa3f1ff) | May 07, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [2effde38b7](https://linux-hardware.org/?probe=2effde38b7) | May 07, 2022 |
| MSI           | 970A-G43                    | Desktop     | [3338da03cc](https://linux-hardware.org/?probe=3338da03cc) | May 07, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [7a595e57da](https://linux-hardware.org/?probe=7a595e57da) | May 07, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [6371d77b5d](https://linux-hardware.org/?probe=6371d77b5d) | May 07, 2022 |
| Lenovo        | G565 20071                  | Notebook    | [ef5983ea64](https://linux-hardware.org/?probe=ef5983ea64) | May 07, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [38c0346cf7](https://linux-hardware.org/?probe=38c0346cf7) | May 07, 2022 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [b8505af5d6](https://linux-hardware.org/?probe=b8505af5d6) | May 07, 2022 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [1f6748931c](https://linux-hardware.org/?probe=1f6748931c) | May 07, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [720be5218f](https://linux-hardware.org/?probe=720be5218f) | May 07, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [0f0a3c0728](https://linux-hardware.org/?probe=0f0a3c0728) | May 07, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [7f0c87b783](https://linux-hardware.org/?probe=7f0c87b783) | May 07, 2022 |
| ASUSTek       | P5QL-E                      | Desktop     | [7847a3091b](https://linux-hardware.org/?probe=7847a3091b) | May 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [835b5af3c7](https://linux-hardware.org/?probe=835b5af3c7) | May 07, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [c1143872e6](https://linux-hardware.org/?probe=c1143872e6) | May 07, 2022 |
| Acer          | Aspire TC-391               | Desktop     | [ec090fb244](https://linux-hardware.org/?probe=ec090fb244) | May 07, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [addef0004e](https://linux-hardware.org/?probe=addef0004e) | May 06, 2022 |
| Lenovo        | 3000 G410                   | Notebook    | [1865fb9b1c](https://linux-hardware.org/?probe=1865fb9b1c) | May 06, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ec38b16f17](https://linux-hardware.org/?probe=ec38b16f17) | May 06, 2022 |
| Acer          | Extensa 2519                | Notebook    | [86f643f1bb](https://linux-hardware.org/?probe=86f643f1bb) | May 06, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [eb70f159f4](https://linux-hardware.org/?probe=eb70f159f4) | May 06, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [d58aad0813](https://linux-hardware.org/?probe=d58aad0813) | May 06, 2022 |
| ASUSTek       | Strix GL504GM_GL504GM       | Notebook    | [cf1b0002d6](https://linux-hardware.org/?probe=cf1b0002d6) | May 06, 2022 |
| Google        | Peppy                       | Notebook    | [03dc670128](https://linux-hardware.org/?probe=03dc670128) | May 06, 2022 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [ad8ee15b6d](https://linux-hardware.org/?probe=ad8ee15b6d) | May 06, 2022 |
| ASUSTek       | VivoBook S15 X530UF         | Notebook    | [3d6fe0b407](https://linux-hardware.org/?probe=3d6fe0b407) | May 06, 2022 |
| Acer          | Aspire C27-1655             | All in one  | [96e5d68181](https://linux-hardware.org/?probe=96e5d68181) | May 06, 2022 |
| KLLISRE       | X79 V2.72S                  | Desktop     | [4f3f76f020](https://linux-hardware.org/?probe=4f3f76f020) | May 06, 2022 |
| KLLISRE       | X79 V2.72S                  | Desktop     | [73d339904d](https://linux-hardware.org/?probe=73d339904d) | May 06, 2022 |
| Huanan        | X99-BD4 V1.1, NALEX         | Desktop     | [e69b3ef962](https://linux-hardware.org/?probe=e69b3ef962) | May 06, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [a395b8eda0](https://linux-hardware.org/?probe=a395b8eda0) | May 06, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [d0e53387f7](https://linux-hardware.org/?probe=d0e53387f7) | May 05, 2022 |
| ASRock        | H61M-GE                     | Desktop     | [fefe67c0d4](https://linux-hardware.org/?probe=fefe67c0d4) | May 05, 2022 |
| Gigabyte      | GA-M55PLUS-S3G              | Desktop     | [ff948aad6c](https://linux-hardware.org/?probe=ff948aad6c) | May 05, 2022 |
| ICL           | H310SB-TM                   | All in one  | [8aca897292](https://linux-hardware.org/?probe=8aca897292) | May 05, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [24e9a90d68](https://linux-hardware.org/?probe=24e9a90d68) | May 05, 2022 |
| ASUSTek       | X551MA                      | Notebook    | [4a12d6b5d9](https://linux-hardware.org/?probe=4a12d6b5d9) | May 05, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [8f15e66f2d](https://linux-hardware.org/?probe=8f15e66f2d) | May 05, 2022 |
| Huanan        | X99-F8                      | Desktop     | [f9699aaa3e](https://linux-hardware.org/?probe=f9699aaa3e) | May 05, 2022 |
| MSI           | H410I PRO WIFI              | Desktop     | [bc1d89fabc](https://linux-hardware.org/?probe=bc1d89fabc) | May 05, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [e533455f48](https://linux-hardware.org/?probe=e533455f48) | May 05, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [0bbc6c64c2](https://linux-hardware.org/?probe=0bbc6c64c2) | May 05, 2022 |
| HP            | Pavilion Laptop 14-ce1xx... | Notebook    | [5c730dc365](https://linux-hardware.org/?probe=5c730dc365) | May 05, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [ab6c74c421](https://linux-hardware.org/?probe=ab6c74c421) | May 05, 2022 |
| ASUSTek       | 1005P                       | Notebook    | [ef0e05c7aa](https://linux-hardware.org/?probe=ef0e05c7aa) | May 05, 2022 |
| HP            | Pavilion Laptop 14-ce1xx... | Notebook    | [cc78e4f439](https://linux-hardware.org/?probe=cc78e4f439) | May 05, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [61c02ee0e9](https://linux-hardware.org/?probe=61c02ee0e9) | May 04, 2022 |
| MSI           | 970A-G43                    | Desktop     | [8b6588eada](https://linux-hardware.org/?probe=8b6588eada) | May 04, 2022 |
| MSI           | B360M PRO-VDH               | Desktop     | [23b80ec93e](https://linux-hardware.org/?probe=23b80ec93e) | May 04, 2022 |
| Pegatron      | IPPPV-D3G                   | Desktop     | [bf56539e57](https://linux-hardware.org/?probe=bf56539e57) | May 04, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [280a764142](https://linux-hardware.org/?probe=280a764142) | May 04, 2022 |
| Panasonic     | CF-19THRAXF9                | Notebook    | [3e2d64f517](https://linux-hardware.org/?probe=3e2d64f517) | May 04, 2022 |
| Digma         | CITI 10 C402T CS1044EW      | Tablet      | [eefe92e281](https://linux-hardware.org/?probe=eefe92e281) | May 04, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [302e27b974](https://linux-hardware.org/?probe=302e27b974) | May 04, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [a9cf3bc268](https://linux-hardware.org/?probe=a9cf3bc268) | May 04, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4891bdbd5c](https://linux-hardware.org/?probe=4891bdbd5c) | May 04, 2022 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [c3ae8f35f9](https://linux-hardware.org/?probe=c3ae8f35f9) | May 04, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [899a0e8999](https://linux-hardware.org/?probe=899a0e8999) | May 04, 2022 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [506ffac23c](https://linux-hardware.org/?probe=506ffac23c) | May 04, 2022 |
| ICL           | H310SB-TM                   | All in one  | [5e24e4a45d](https://linux-hardware.org/?probe=5e24e4a45d) | May 04, 2022 |
| Lenovo        | 3130 NOK                    | Mini pc     | [6e3858143b](https://linux-hardware.org/?probe=6e3858143b) | May 04, 2022 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [374070d210](https://linux-hardware.org/?probe=374070d210) | May 04, 2022 |
| Lenovo        | 3130 NOK                    | Mini pc     | [d1fb23854f](https://linux-hardware.org/?probe=d1fb23854f) | May 04, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [78e4325ae6](https://linux-hardware.org/?probe=78e4325ae6) | May 04, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [dd95306834](https://linux-hardware.org/?probe=dd95306834) | May 04, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [c25a0f8526](https://linux-hardware.org/?probe=c25a0f8526) | May 04, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [653adf4036](https://linux-hardware.org/?probe=653adf4036) | May 04, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [c89b45b9ad](https://linux-hardware.org/?probe=c89b45b9ad) | May 04, 2022 |
| Lenovo        | ThinkCentre M55 8795B1G     | Desktop     | [295fe2b588](https://linux-hardware.org/?probe=295fe2b588) | May 04, 2022 |
| Lenovo        | ThinkCentre M55 8795B1G     | Desktop     | [b88ff00133](https://linux-hardware.org/?probe=b88ff00133) | May 04, 2022 |
| Unknown       | RS690-SB600                 | Desktop     | [a5a63d87df](https://linux-hardware.org/?probe=a5a63d87df) | May 04, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [5e1f408239](https://linux-hardware.org/?probe=5e1f408239) | May 04, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [256b7b7658](https://linux-hardware.org/?probe=256b7b7658) | May 03, 2022 |
| Lenovo        | ThinkPad T480 20L5000ART    | Notebook    | [f4cd0ce06c](https://linux-hardware.org/?probe=f4cd0ce06c) | May 03, 2022 |
| Lenovo        | ThinkPad T480 20L5000ART    | Notebook    | [4360d63d4a](https://linux-hardware.org/?probe=4360d63d4a) | May 03, 2022 |
| Acer          | Aspire V5-552G              | Notebook    | [caa6467c0e](https://linux-hardware.org/?probe=caa6467c0e) | May 03, 2022 |
| Acer          | Aspire V5-552G              | Notebook    | [c3255ca484](https://linux-hardware.org/?probe=c3255ca484) | May 03, 2022 |
| Unknown       | RS690-SB600                 | Desktop     | [cdda671470](https://linux-hardware.org/?probe=cdda671470) | May 03, 2022 |
| Irbis         | TW39                        | Notebook    | [38844a7f5e](https://linux-hardware.org/?probe=38844a7f5e) | May 03, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [ee0d654e52](https://linux-hardware.org/?probe=ee0d654e52) | May 03, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [9fa64d179d](https://linux-hardware.org/?probe=9fa64d179d) | May 03, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a134998640](https://linux-hardware.org/?probe=a134998640) | May 03, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [2010f5f8cc](https://linux-hardware.org/?probe=2010f5f8cc) | May 03, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [6649f5164e](https://linux-hardware.org/?probe=6649f5164e) | May 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [755bcaa97c](https://linux-hardware.org/?probe=755bcaa97c) | May 03, 2022 |
| ABIT          | F-I90HD                     | Desktop     | [a76a1e15a0](https://linux-hardware.org/?probe=a76a1e15a0) | May 03, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [73358636b6](https://linux-hardware.org/?probe=73358636b6) | May 03, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [ca68b014a7](https://linux-hardware.org/?probe=ca68b014a7) | May 03, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [6b961e699a](https://linux-hardware.org/?probe=6b961e699a) | May 03, 2022 |
| Acer          | Aspire A517-51G             | Notebook    | [1dc71986aa](https://linux-hardware.org/?probe=1dc71986aa) | May 03, 2022 |
| Acer          | Aspire A517-51G             | Notebook    | [d0ad1ff2fe](https://linux-hardware.org/?probe=d0ad1ff2fe) | May 03, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [6a9e757624](https://linux-hardware.org/?probe=6a9e757624) | May 02, 2022 |
| MSI           | Z87-G43                     | Desktop     | [d5612db7ca](https://linux-hardware.org/?probe=d5612db7ca) | May 02, 2022 |
| ASUSTek       | B150-PRO D3                 | Desktop     | [1620040802](https://linux-hardware.org/?probe=1620040802) | May 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [68a966265b](https://linux-hardware.org/?probe=68a966265b) | May 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [58ff4a1984](https://linux-hardware.org/?probe=58ff4a1984) | May 02, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [d874b5668c](https://linux-hardware.org/?probe=d874b5668c) | May 02, 2022 |
| ASUSTek       | X551CAP                     | Notebook    | [c4f8ae2abf](https://linux-hardware.org/?probe=c4f8ae2abf) | May 02, 2022 |
| MSI           | NF520T-C35                  | Desktop     | [626f45376a](https://linux-hardware.org/?probe=626f45376a) | May 02, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [4e6ed2eaa3](https://linux-hardware.org/?probe=4e6ed2eaa3) | May 02, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [ab4b021f1b](https://linux-hardware.org/?probe=ab4b021f1b) | May 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [d9878767eb](https://linux-hardware.org/?probe=d9878767eb) | May 02, 2022 |
| Dell          | Vostro A860                 | Notebook    | [c314c4b269](https://linux-hardware.org/?probe=c314c4b269) | May 02, 2022 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [f776c43073](https://linux-hardware.org/?probe=f776c43073) | May 02, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [e0983f2b8c](https://linux-hardware.org/?probe=e0983f2b8c) | May 02, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [1e0e1acbd3](https://linux-hardware.org/?probe=1e0e1acbd3) | May 02, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [fa46d0866b](https://linux-hardware.org/?probe=fa46d0866b) | May 02, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [ccabd73c80](https://linux-hardware.org/?probe=ccabd73c80) | May 02, 2022 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [e6a2ee3ec5](https://linux-hardware.org/?probe=e6a2ee3ec5) | May 02, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [4a93a15de8](https://linux-hardware.org/?probe=4a93a15de8) | May 02, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [f77de23642](https://linux-hardware.org/?probe=f77de23642) | May 02, 2022 |
| Lenovo        | ThinkPad T480 20L50000RT    | Notebook    | [b636694d0c](https://linux-hardware.org/?probe=b636694d0c) | May 02, 2022 |
| Lenovo        | ThinkPad T480 20L50000RT    | Notebook    | [142fb350da](https://linux-hardware.org/?probe=142fb350da) | May 02, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d13bc7aee3](https://linux-hardware.org/?probe=d13bc7aee3) | May 02, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [c19f2858f0](https://linux-hardware.org/?probe=c19f2858f0) | May 01, 2022 |
| ASUSTek       | K53SM                       | Notebook    | [69ea783c88](https://linux-hardware.org/?probe=69ea783c88) | May 01, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [59e65b422b](https://linux-hardware.org/?probe=59e65b422b) | May 01, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [8532d4b88f](https://linux-hardware.org/?probe=8532d4b88f) | May 01, 2022 |
| ASRock        | Z270 Gaming K4              | Desktop     | [c497e3c5a9](https://linux-hardware.org/?probe=c497e3c5a9) | May 01, 2022 |
| Intel         | Unknown                     | Notebook    | [8353c6d487](https://linux-hardware.org/?probe=8353c6d487) | May 01, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [57d77dbfdd](https://linux-hardware.org/?probe=57d77dbfdd) | May 01, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [67404fab24](https://linux-hardware.org/?probe=67404fab24) | May 01, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [c7ac6032f5](https://linux-hardware.org/?probe=c7ac6032f5) | May 01, 2022 |
| Acer          | Aspire TC-705               | Desktop     | [0e4b8cfff4](https://linux-hardware.org/?probe=0e4b8cfff4) | May 01, 2022 |
| Supermicro    | X11SSE-F                    | Mini pc     | [01c5f4fe66](https://linux-hardware.org/?probe=01c5f4fe66) | May 01, 2022 |
| Lenovo        | H420                        | Desktop     | [2f22f32e19](https://linux-hardware.org/?probe=2f22f32e19) | May 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [467c181d49](https://linux-hardware.org/?probe=467c181d49) | May 01, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [95d109769d](https://linux-hardware.org/?probe=95d109769d) | May 01, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [8538f5cbeb](https://linux-hardware.org/?probe=8538f5cbeb) | May 01, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [da9df39f8c](https://linux-hardware.org/?probe=da9df39f8c) | Apr 30, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [72ea7f5155](https://linux-hardware.org/?probe=72ea7f5155) | Apr 30, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [23a77acbe8](https://linux-hardware.org/?probe=23a77acbe8) | Apr 30, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a4adaba544](https://linux-hardware.org/?probe=a4adaba544) | Apr 30, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [a788b08450](https://linux-hardware.org/?probe=a788b08450) | Apr 30, 2022 |
| Dell          | Vostro 5581                 | Notebook    | [cdcb310766](https://linux-hardware.org/?probe=cdcb310766) | Apr 30, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [f253fe8221](https://linux-hardware.org/?probe=f253fe8221) | Apr 30, 2022 |
| Dell          | G7 7700                     | Notebook    | [462862ed56](https://linux-hardware.org/?probe=462862ed56) | Apr 30, 2022 |
| ASRock        | 880GM-LE FX                 | Desktop     | [f695420d7e](https://linux-hardware.org/?probe=f695420d7e) | Apr 30, 2022 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [c934f2e590](https://linux-hardware.org/?probe=c934f2e590) | Apr 30, 2022 |
| MSI           | GP65 Leopard 10SFK          | Notebook    | [4523d433d4](https://linux-hardware.org/?probe=4523d433d4) | Apr 30, 2022 |
| MSI           | GP65 Leopard 10SFK          | Notebook    | [a30f4b3e9f](https://linux-hardware.org/?probe=a30f4b3e9f) | Apr 30, 2022 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [b6658c2ada](https://linux-hardware.org/?probe=b6658c2ada) | Apr 30, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [9328531b5a](https://linux-hardware.org/?probe=9328531b5a) | Apr 30, 2022 |
| Acer          | Aspire A517-51G             | Notebook    | [a7e637b1af](https://linux-hardware.org/?probe=a7e637b1af) | Apr 30, 2022 |
| ASUSTek       | P5QL                        | Desktop     | [121da21f08](https://linux-hardware.org/?probe=121da21f08) | Apr 30, 2022 |
| MSI           | PS63 Modern 8M              | Notebook    | [06f3f7a100](https://linux-hardware.org/?probe=06f3f7a100) | Apr 30, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [24faa6d3b2](https://linux-hardware.org/?probe=24faa6d3b2) | Apr 30, 2022 |
| ASRock        | B75M-ITX                    | Desktop     | [dbc851e0d3](https://linux-hardware.org/?probe=dbc851e0d3) | Apr 30, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [5220d21e84](https://linux-hardware.org/?probe=5220d21e84) | Apr 30, 2022 |
| Timi          | TM1701                      | Notebook    | [f81bb7efbe](https://linux-hardware.org/?probe=f81bb7efbe) | Apr 30, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [d5d92c2890](https://linux-hardware.org/?probe=d5d92c2890) | Apr 30, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [6bba4f2274](https://linux-hardware.org/?probe=6bba4f2274) | Apr 30, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a53000596e](https://linux-hardware.org/?probe=a53000596e) | Apr 30, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [3d56136487](https://linux-hardware.org/?probe=3d56136487) | Apr 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [55e76f131d](https://linux-hardware.org/?probe=55e76f131d) | Apr 30, 2022 |
| Gigabyte      | H610I DDR4                  | Desktop     | [b9ee954651](https://linux-hardware.org/?probe=b9ee954651) | Apr 30, 2022 |
| Gigabyte      | H610I DDR4                  | Desktop     | [ead878ad96](https://linux-hardware.org/?probe=ead878ad96) | Apr 29, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [56fabb8cec](https://linux-hardware.org/?probe=56fabb8cec) | Apr 29, 2022 |
| Acer          | Aspire A715-71G             | Notebook    | [ec6c90818c](https://linux-hardware.org/?probe=ec6c90818c) | Apr 29, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [442670a18f](https://linux-hardware.org/?probe=442670a18f) | Apr 29, 2022 |
| ASUSTek       | K52N                        | Notebook    | [29f3f98ad0](https://linux-hardware.org/?probe=29f3f98ad0) | Apr 29, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [2c284d0f8c](https://linux-hardware.org/?probe=2c284d0f8c) | Apr 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f842336794](https://linux-hardware.org/?probe=f842336794) | Apr 29, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [e750916955](https://linux-hardware.org/?probe=e750916955) | Apr 29, 2022 |
| ASUSTek       | M4N68T                      | Desktop     | [8113a96dff](https://linux-hardware.org/?probe=8113a96dff) | Apr 29, 2022 |
| HP            | ENVY dv7                    | Notebook    | [dbd8feaee0](https://linux-hardware.org/?probe=dbd8feaee0) | Apr 29, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [2614591cf9](https://linux-hardware.org/?probe=2614591cf9) | Apr 29, 2022 |
| MSI           | Katana GF76 11SC            | Notebook    | [15dcec28fc](https://linux-hardware.org/?probe=15dcec28fc) | Apr 29, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [48af028244](https://linux-hardware.org/?probe=48af028244) | Apr 29, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [d5828a8f9f](https://linux-hardware.org/?probe=d5828a8f9f) | Apr 29, 2022 |
| Dell          | Latitude 3420               | Notebook    | [d1239521b9](https://linux-hardware.org/?probe=d1239521b9) | Apr 29, 2022 |
| Acer          | Aspire ES1-311              | Notebook    | [aa4612575b](https://linux-hardware.org/?probe=aa4612575b) | Apr 29, 2022 |
| MSI           | GE66 Raider 11UH            | Notebook    | [9bdf866ebc](https://linux-hardware.org/?probe=9bdf866ebc) | Apr 29, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [9b29aa0e0e](https://linux-hardware.org/?probe=9b29aa0e0e) | Apr 29, 2022 |
| Lite-On       | 08FCh E01                   | Desktop     | [876d70350c](https://linux-hardware.org/?probe=876d70350c) | Apr 29, 2022 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [9686556653](https://linux-hardware.org/?probe=9686556653) | Apr 29, 2022 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [12e326fab8](https://linux-hardware.org/?probe=12e326fab8) | Apr 28, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [c4fc81307d](https://linux-hardware.org/?probe=c4fc81307d) | Apr 28, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [03c0f64a6e](https://linux-hardware.org/?probe=03c0f64a6e) | Apr 28, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [02b4a9bd72](https://linux-hardware.org/?probe=02b4a9bd72) | Apr 28, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [22369d04ff](https://linux-hardware.org/?probe=22369d04ff) | Apr 28, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [f98b9b686e](https://linux-hardware.org/?probe=f98b9b686e) | Apr 28, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [674c8c1bf3](https://linux-hardware.org/?probe=674c8c1bf3) | Apr 28, 2022 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [7669e97557](https://linux-hardware.org/?probe=7669e97557) | Apr 28, 2022 |
| Lenovo        | NOK                         | Desktop     | [4ea735896c](https://linux-hardware.org/?probe=4ea735896c) | Apr 28, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [96739891ab](https://linux-hardware.org/?probe=96739891ab) | Apr 28, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [c75ef7f42d](https://linux-hardware.org/?probe=c75ef7f42d) | Apr 28, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [af1b36d1f6](https://linux-hardware.org/?probe=af1b36d1f6) | Apr 28, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [9bf9254f54](https://linux-hardware.org/?probe=9bf9254f54) | Apr 28, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [7050d2a05f](https://linux-hardware.org/?probe=7050d2a05f) | Apr 28, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [94a47b7e85](https://linux-hardware.org/?probe=94a47b7e85) | Apr 28, 2022 |
| Sony          | VPCEH3F1R                   | Notebook    | [2d78f4b2b5](https://linux-hardware.org/?probe=2d78f4b2b5) | Apr 28, 2022 |
| ECS           | A780LM-M2                   | Desktop     | [ae8fabafb3](https://linux-hardware.org/?probe=ae8fabafb3) | Apr 28, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [31f358fdd0](https://linux-hardware.org/?probe=31f358fdd0) | Apr 28, 2022 |
| ECS           | GeForce7050M-M              | Desktop     | [7b99513a4a](https://linux-hardware.org/?probe=7b99513a4a) | Apr 27, 2022 |
| ECS           | GeForce7050M-M              | Desktop     | [d957db1716](https://linux-hardware.org/?probe=d957db1716) | Apr 27, 2022 |
| Dell          | Latitude 5310               | Notebook    | [1bfa3e6f27](https://linux-hardware.org/?probe=1bfa3e6f27) | Apr 27, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [4dd8fa1d2f](https://linux-hardware.org/?probe=4dd8fa1d2f) | Apr 27, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [c5f3191403](https://linux-hardware.org/?probe=c5f3191403) | Apr 27, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [f0c8ad777d](https://linux-hardware.org/?probe=f0c8ad777d) | Apr 27, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [155297b5da](https://linux-hardware.org/?probe=155297b5da) | Apr 27, 2022 |
| ASUSTek       | PRIME H570-PLUS             | Desktop     | [217e24d827](https://linux-hardware.org/?probe=217e24d827) | Apr 27, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [8332dfca0b](https://linux-hardware.org/?probe=8332dfca0b) | Apr 27, 2022 |
| Lenovo        | SHARKBAY 31900059 STD       | All in one  | [910be59af9](https://linux-hardware.org/?probe=910be59af9) | Apr 27, 2022 |
| Acer          | Aspire 5625G                | Notebook    | [654e51fb7c](https://linux-hardware.org/?probe=654e51fb7c) | Apr 27, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [e1f76d9f38](https://linux-hardware.org/?probe=e1f76d9f38) | Apr 27, 2022 |
| HP            | 2000                        | Notebook    | [65891d90cc](https://linux-hardware.org/?probe=65891d90cc) | Apr 27, 2022 |
| ASUSTek       | K50IE                       | Notebook    | [5d8cdec08c](https://linux-hardware.org/?probe=5d8cdec08c) | Apr 27, 2022 |
| MSI           | B85M-P33                    | Desktop     | [b18d0beead](https://linux-hardware.org/?probe=b18d0beead) | Apr 27, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [8bca69a0a8](https://linux-hardware.org/?probe=8bca69a0a8) | Apr 27, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e612a2bab1](https://linux-hardware.org/?probe=e612a2bab1) | Apr 27, 2022 |
| HP            | ProBook 470 G0              | Notebook    | [d0c294728b](https://linux-hardware.org/?probe=d0c294728b) | Apr 27, 2022 |
| IBM           | 94Y7718 SIT                 | Server      | [074e80349e](https://linux-hardware.org/?probe=074e80349e) | Apr 27, 2022 |
| Lenovo        | NOK                         | Desktop     | [6d17068770](https://linux-hardware.org/?probe=6d17068770) | Apr 27, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [32fd06793f](https://linux-hardware.org/?probe=32fd06793f) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6c1227313d](https://linux-hardware.org/?probe=6c1227313d) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [4f49f3d6c2](https://linux-hardware.org/?probe=4f49f3d6c2) | Apr 27, 2022 |
| ASUSTek       | X505BA                      | Notebook    | [30972759d1](https://linux-hardware.org/?probe=30972759d1) | Apr 27, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [2670b60f3c](https://linux-hardware.org/?probe=2670b60f3c) | Apr 27, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [21763ed6a1](https://linux-hardware.org/?probe=21763ed6a1) | Apr 27, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [31217e01e3](https://linux-hardware.org/?probe=31217e01e3) | Apr 27, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [67c03df307](https://linux-hardware.org/?probe=67c03df307) | Apr 27, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [7630e097d9](https://linux-hardware.org/?probe=7630e097d9) | Apr 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [003eab04ae](https://linux-hardware.org/?probe=003eab04ae) | Apr 26, 2022 |
| Acer          | Aspire 5625G                | Notebook    | [6dfe24b002](https://linux-hardware.org/?probe=6dfe24b002) | Apr 26, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [65d778f931](https://linux-hardware.org/?probe=65d778f931) | Apr 26, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [fc283a78af](https://linux-hardware.org/?probe=fc283a78af) | Apr 26, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [9fc1163ba6](https://linux-hardware.org/?probe=9fc1163ba6) | Apr 26, 2022 |
| Lenovo        | B450 1S16800336100RT        | Notebook    | [ddaca02cbd](https://linux-hardware.org/?probe=ddaca02cbd) | Apr 26, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [bbb54a4f60](https://linux-hardware.org/?probe=bbb54a4f60) | Apr 26, 2022 |
| Acer          | Aspire 7736                 | Notebook    | [a0b8522191](https://linux-hardware.org/?probe=a0b8522191) | Apr 26, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [458eb421b9](https://linux-hardware.org/?probe=458eb421b9) | Apr 26, 2022 |
| ZoomSmart     | A8006                       | Tablet      | [988bb3eda7](https://linux-hardware.org/?probe=988bb3eda7) | Apr 26, 2022 |
| ASUSTek       | ZenBook UX434FQ_UX434FQ     | Notebook    | [9f8c80ed7d](https://linux-hardware.org/?probe=9f8c80ed7d) | Apr 26, 2022 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [26a7e61215](https://linux-hardware.org/?probe=26a7e61215) | Apr 26, 2022 |
| ZoomSmart     | A8006                       | Tablet      | [fcc5f522b3](https://linux-hardware.org/?probe=fcc5f522b3) | Apr 26, 2022 |
| HP            | Notebook                    | Notebook    | [975bc190a2](https://linux-hardware.org/?probe=975bc190a2) | Apr 26, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [a8934b94b8](https://linux-hardware.org/?probe=a8934b94b8) | Apr 26, 2022 |
| ASUSTek       | K50ID                       | Notebook    | [7d7776358b](https://linux-hardware.org/?probe=7d7776358b) | Apr 26, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [6dcece8c55](https://linux-hardware.org/?probe=6dcece8c55) | Apr 26, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [b48dc21646](https://linux-hardware.org/?probe=b48dc21646) | Apr 26, 2022 |
| ASUSTek       | ROG Strix G733QR_G733QR     | Notebook    | [e4c1fa069d](https://linux-hardware.org/?probe=e4c1fa069d) | Apr 26, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [7e8c222029](https://linux-hardware.org/?probe=7e8c222029) | Apr 26, 2022 |
| Gigabyte      | B85M-D2V                    | Desktop     | [ca876d7b83](https://linux-hardware.org/?probe=ca876d7b83) | Apr 26, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [feea6c0d76](https://linux-hardware.org/?probe=feea6c0d76) | Apr 25, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [c26bb7d11c](https://linux-hardware.org/?probe=c26bb7d11c) | Apr 25, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [5ac12e226f](https://linux-hardware.org/?probe=5ac12e226f) | Apr 25, 2022 |
| Sony          | SVE1712V1RB                 | Notebook    | [e63891da73](https://linux-hardware.org/?probe=e63891da73) | Apr 25, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [5991a49238](https://linux-hardware.org/?probe=5991a49238) | Apr 25, 2022 |
| ASRock        | G31M-VS2                    | Desktop     | [912aa8341f](https://linux-hardware.org/?probe=912aa8341f) | Apr 25, 2022 |
| iRU           | LPGR.469559.001             | Notebook    | [3758808bc5](https://linux-hardware.org/?probe=3758808bc5) | Apr 25, 2022 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [7c068a38f3](https://linux-hardware.org/?probe=7c068a38f3) | Apr 25, 2022 |
| ICL           | H310SB-TM                   | All in one  | [11db07be56](https://linux-hardware.org/?probe=11db07be56) | Apr 25, 2022 |
| ASUSTek       | UX303LN                     | Notebook    | [13a99f1912](https://linux-hardware.org/?probe=13a99f1912) | Apr 25, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [643eb9c031](https://linux-hardware.org/?probe=643eb9c031) | Apr 25, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [a1b9c91836](https://linux-hardware.org/?probe=a1b9c91836) | Apr 25, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [82c13f2b01](https://linux-hardware.org/?probe=82c13f2b01) | Apr 25, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [1b1bf8dddf](https://linux-hardware.org/?probe=1b1bf8dddf) | Apr 25, 2022 |
| Toshiba       | Satellite U300              | Notebook    | [1fa01f4156](https://linux-hardware.org/?probe=1fa01f4156) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [f1e5d5715f](https://linux-hardware.org/?probe=f1e5d5715f) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [a0e3085b4c](https://linux-hardware.org/?probe=a0e3085b4c) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [9819b3fc78](https://linux-hardware.org/?probe=9819b3fc78) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [d27d03b7e4](https://linux-hardware.org/?probe=d27d03b7e4) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [a8784c861a](https://linux-hardware.org/?probe=a8784c861a) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [b970feef75](https://linux-hardware.org/?probe=b970feef75) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [6bfffcf96a](https://linux-hardware.org/?probe=6bfffcf96a) | Apr 25, 2022 |
| Dell          | G15 5510                    | Notebook    | [8cf81514fa](https://linux-hardware.org/?probe=8cf81514fa) | Apr 25, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [4479bed84f](https://linux-hardware.org/?probe=4479bed84f) | Apr 25, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [4fd4202535](https://linux-hardware.org/?probe=4fd4202535) | Apr 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [4b41ff5fb9](https://linux-hardware.org/?probe=4b41ff5fb9) | Apr 24, 2022 |
| HP            | Pavilion dv6000             | Notebook    | [f41a09331b](https://linux-hardware.org/?probe=f41a09331b) | Apr 24, 2022 |
| ASUSTek       | PRIME H570-PLUS             | Desktop     | [deb39edb0a](https://linux-hardware.org/?probe=deb39edb0a) | Apr 24, 2022 |
| ASUSTek       | S400CA                      | Notebook    | [b9b3e314e5](https://linux-hardware.org/?probe=b9b3e314e5) | Apr 24, 2022 |
| Notebook      | W65_67SF                    | Notebook    | [37712c1d2b](https://linux-hardware.org/?probe=37712c1d2b) | Apr 24, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [9d244bbdcc](https://linux-hardware.org/?probe=9d244bbdcc) | Apr 24, 2022 |
| Lenovo        | ThinkPad W520 4284BL9       | Notebook    | [a7dd5a566e](https://linux-hardware.org/?probe=a7dd5a566e) | Apr 24, 2022 |
| MSI           | G31TM-P35                   | Desktop     | [711f26a820](https://linux-hardware.org/?probe=711f26a820) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [de4fb8782a](https://linux-hardware.org/?probe=de4fb8782a) | Apr 24, 2022 |
| HP            | Pavilion dv6000 (RE386EA... | Notebook    | [9d00048a2d](https://linux-hardware.org/?probe=9d00048a2d) | Apr 24, 2022 |
| ASUSTek       | UX32A                       | Notebook    | [0cbf3a6f80](https://linux-hardware.org/?probe=0cbf3a6f80) | Apr 24, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [a4c9b28b0f](https://linux-hardware.org/?probe=a4c9b28b0f) | Apr 24, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [6dad6af75e](https://linux-hardware.org/?probe=6dad6af75e) | Apr 24, 2022 |
| MSI           | G31M3 V2                    | Desktop     | [4c1d75729a](https://linux-hardware.org/?probe=4c1d75729a) | Apr 24, 2022 |
| MSI           | G31TM-P35                   | Desktop     | [2c1b91769f](https://linux-hardware.org/?probe=2c1b91769f) | Apr 24, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [9cda67e701](https://linux-hardware.org/?probe=9cda67e701) | Apr 24, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [12060212f8](https://linux-hardware.org/?probe=12060212f8) | Apr 24, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [fee9fe1263](https://linux-hardware.org/?probe=fee9fe1263) | Apr 24, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [52259207bb](https://linux-hardware.org/?probe=52259207bb) | Apr 24, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [f82141025b](https://linux-hardware.org/?probe=f82141025b) | Apr 24, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [734fbc9db6](https://linux-hardware.org/?probe=734fbc9db6) | Apr 24, 2022 |
| Dell          | Latitude 7280               | Notebook    | [7ad22b030d](https://linux-hardware.org/?probe=7ad22b030d) | Apr 24, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [6c717bc636](https://linux-hardware.org/?probe=6c717bc636) | Apr 24, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [c3e874826b](https://linux-hardware.org/?probe=c3e874826b) | Apr 24, 2022 |
| Acer          | Aspire ES1-521              | Notebook    | [0d1857219f](https://linux-hardware.org/?probe=0d1857219f) | Apr 24, 2022 |
| Acer          | Aspire TC-390               | Desktop     | [69a7263b5a](https://linux-hardware.org/?probe=69a7263b5a) | Apr 24, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [6d624aee80](https://linux-hardware.org/?probe=6d624aee80) | Apr 24, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [096a0bc434](https://linux-hardware.org/?probe=096a0bc434) | Apr 24, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [3e5e1e7137](https://linux-hardware.org/?probe=3e5e1e7137) | Apr 24, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [fa2c44bf71](https://linux-hardware.org/?probe=fa2c44bf71) | Apr 24, 2022 |
| Haier         | U1520SD                     | Notebook    | [a546af91bb](https://linux-hardware.org/?probe=a546af91bb) | Apr 24, 2022 |
| Acer          | AOD270                      | Notebook    | [50198f1c2f](https://linux-hardware.org/?probe=50198f1c2f) | Apr 24, 2022 |
| Haier         | S424                        | Notebook    | [9dcf76fcf7](https://linux-hardware.org/?probe=9dcf76fcf7) | Apr 24, 2022 |
| Dell          | XPS 15 9575                 | Convertible | [380fefab43](https://linux-hardware.org/?probe=380fefab43) | Apr 24, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d68949ed95](https://linux-hardware.org/?probe=d68949ed95) | Apr 23, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [9c45d7cb78](https://linux-hardware.org/?probe=9c45d7cb78) | Apr 23, 2022 |
| ASUSTek       | AM1I-A                      | Desktop     | [b041f2cde0](https://linux-hardware.org/?probe=b041f2cde0) | Apr 23, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3d101a3380](https://linux-hardware.org/?probe=3d101a3380) | Apr 23, 2022 |
| Sony          | SVE1512H1RW                 | Notebook    | [0fc6ea9996](https://linux-hardware.org/?probe=0fc6ea9996) | Apr 23, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [187db4f8e4](https://linux-hardware.org/?probe=187db4f8e4) | Apr 23, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [acbc0ffb3b](https://linux-hardware.org/?probe=acbc0ffb3b) | Apr 23, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [5d81eb4631](https://linux-hardware.org/?probe=5d81eb4631) | Apr 23, 2022 |
| Acer          | TravelMate P259-MG          | Notebook    | [debe4697b9](https://linux-hardware.org/?probe=debe4697b9) | Apr 23, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [d01bcb69ea](https://linux-hardware.org/?probe=d01bcb69ea) | Apr 23, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [7f7ea99704](https://linux-hardware.org/?probe=7f7ea99704) | Apr 23, 2022 |
| MSI           | 770-G45                     | Desktop     | [5c1bce29f2](https://linux-hardware.org/?probe=5c1bce29f2) | Apr 23, 2022 |
| Acer          | AOD270                      | Notebook    | [b53cedd40c](https://linux-hardware.org/?probe=b53cedd40c) | Apr 23, 2022 |
| Gigabyte      | E2500N                      | Desktop     | [92784cd549](https://linux-hardware.org/?probe=92784cd549) | Apr 23, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [661b8cc46d](https://linux-hardware.org/?probe=661b8cc46d) | Apr 23, 2022 |
| ASUSTek       | X401A1                      | Notebook    | [883c933519](https://linux-hardware.org/?probe=883c933519) | Apr 23, 2022 |
| Toshiba       | Satellite U300              | Notebook    | [9db41e52eb](https://linux-hardware.org/?probe=9db41e52eb) | Apr 23, 2022 |
| ASUSTek       | X401A1                      | Notebook    | [9b960298ef](https://linux-hardware.org/?probe=9b960298ef) | Apr 23, 2022 |
| ASRock        | H410M-HVS                   | Desktop     | [5357a4e149](https://linux-hardware.org/?probe=5357a4e149) | Apr 23, 2022 |
| ASRock        | H410M-HVS                   | Desktop     | [97f2c666ff](https://linux-hardware.org/?probe=97f2c666ff) | Apr 23, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [da2e3a603d](https://linux-hardware.org/?probe=da2e3a603d) | Apr 23, 2022 |
| Lenovo        | IdeaPad Z470                | Notebook    | [0033f5692b](https://linux-hardware.org/?probe=0033f5692b) | Apr 23, 2022 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [dcfad64d9d](https://linux-hardware.org/?probe=dcfad64d9d) | Apr 23, 2022 |
| ASRock        | QC5000M                     | Desktop     | [b9341a0704](https://linux-hardware.org/?probe=b9341a0704) | Apr 23, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [9ba9e35d88](https://linux-hardware.org/?probe=9ba9e35d88) | Apr 23, 2022 |
| Acer          | Aspire 7110                 | Notebook    | [6e46dbc582](https://linux-hardware.org/?probe=6e46dbc582) | Apr 22, 2022 |
| Lenovo        | ThinkPad X230 2325I63       | Notebook    | [22522f125f](https://linux-hardware.org/?probe=22522f125f) | Apr 22, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [1d8b10f388](https://linux-hardware.org/?probe=1d8b10f388) | Apr 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [4033356f39](https://linux-hardware.org/?probe=4033356f39) | Apr 22, 2022 |
| ASRock        | H110M-DVS R2.0              | Desktop     | [f682ddf4ed](https://linux-hardware.org/?probe=f682ddf4ed) | Apr 22, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [36386a3115](https://linux-hardware.org/?probe=36386a3115) | Apr 22, 2022 |
| ASUSTek       | P5B                         | Desktop     | [223154e54d](https://linux-hardware.org/?probe=223154e54d) | Apr 22, 2022 |
| Gigabyte      | B360M H                     | Desktop     | [ec4003c77d](https://linux-hardware.org/?probe=ec4003c77d) | Apr 22, 2022 |
| ASUSTek       | K54HR                       | Notebook    | [9d42053630](https://linux-hardware.org/?probe=9d42053630) | Apr 22, 2022 |
| HONOR         | NBD-WXX9                    | Notebook    | [135c98b96d](https://linux-hardware.org/?probe=135c98b96d) | Apr 22, 2022 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [6ba25a4781](https://linux-hardware.org/?probe=6ba25a4781) | Apr 22, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [c80263e88a](https://linux-hardware.org/?probe=c80263e88a) | Apr 22, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4bb685c310](https://linux-hardware.org/?probe=4bb685c310) | Apr 22, 2022 |
| ASUSTek       | P5B                         | Desktop     | [00f8e07a8d](https://linux-hardware.org/?probe=00f8e07a8d) | Apr 22, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [508d41c597](https://linux-hardware.org/?probe=508d41c597) | Apr 22, 2022 |
| ASUSTek       | Z87-A                       | Desktop     | [ef07d8d824](https://linux-hardware.org/?probe=ef07d8d824) | Apr 22, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [95a2757020](https://linux-hardware.org/?probe=95a2757020) | Apr 22, 2022 |
| Pegatron      | A15W8                       | Notebook    | [93ddbc3b82](https://linux-hardware.org/?probe=93ddbc3b82) | Apr 22, 2022 |
| Colorful T... | C.H81A-BTC V20              | Desktop     | [1f0dab0203](https://linux-hardware.org/?probe=1f0dab0203) | Apr 22, 2022 |
| Pegatron      | A15W8                       | Notebook    | [c02c5b8796](https://linux-hardware.org/?probe=c02c5b8796) | Apr 22, 2022 |
| Gigabyte      | U2152                       | Notebook    | [0226fcddee](https://linux-hardware.org/?probe=0226fcddee) | Apr 22, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [2b17dd2971](https://linux-hardware.org/?probe=2b17dd2971) | Apr 22, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [de27893552](https://linux-hardware.org/?probe=de27893552) | Apr 22, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [1b5a8b5542](https://linux-hardware.org/?probe=1b5a8b5542) | Apr 21, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [98eb9909d0](https://linux-hardware.org/?probe=98eb9909d0) | Apr 21, 2022 |
| Acer          | Aspire 7540                 | Notebook    | [0700a2eb31](https://linux-hardware.org/?probe=0700a2eb31) | Apr 21, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [7ab5ec522c](https://linux-hardware.org/?probe=7ab5ec522c) | Apr 21, 2022 |
| Dell          | 02X6YT A01                  | Desktop     | [f672bdbf0e](https://linux-hardware.org/?probe=f672bdbf0e) | Apr 21, 2022 |
| KLLISRE       | X99-B5 V1.1                 | Desktop     | [14e557ad2d](https://linux-hardware.org/?probe=14e557ad2d) | Apr 21, 2022 |
| MSI           | 0A48                        | Desktop     | [1e73c16d0c](https://linux-hardware.org/?probe=1e73c16d0c) | Apr 21, 2022 |
| Gigabyte      | G41MT-USB3                  | Desktop     | [10f3a0eaae](https://linux-hardware.org/?probe=10f3a0eaae) | Apr 21, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [a2452e4824](https://linux-hardware.org/?probe=a2452e4824) | Apr 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [c7c9ed4c0e](https://linux-hardware.org/?probe=c7c9ed4c0e) | Apr 21, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [725dad09bf](https://linux-hardware.org/?probe=725dad09bf) | Apr 21, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [cba42e1765](https://linux-hardware.org/?probe=cba42e1765) | Apr 21, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [bf030ccfa0](https://linux-hardware.org/?probe=bf030ccfa0) | Apr 21, 2022 |
| ASUSTek       | F5SL                        | Notebook    | [a5cf2fd4ca](https://linux-hardware.org/?probe=a5cf2fd4ca) | Apr 21, 2022 |
| MSI           | Sword 15 A11UE              | Notebook    | [c9316aedb8](https://linux-hardware.org/?probe=c9316aedb8) | Apr 21, 2022 |
| Gigabyte      | H310M S2                    | Desktop     | [0f18c98ee7](https://linux-hardware.org/?probe=0f18c98ee7) | Apr 21, 2022 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [8ed5a0f97a](https://linux-hardware.org/?probe=8ed5a0f97a) | Apr 21, 2022 |
| MSI           | Z97-G43 GAMING              | Desktop     | [a4d2dc6c95](https://linux-hardware.org/?probe=a4d2dc6c95) | Apr 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [aa8173a46a](https://linux-hardware.org/?probe=aa8173a46a) | Apr 20, 2022 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [089f66bac4](https://linux-hardware.org/?probe=089f66bac4) | Apr 20, 2022 |
| ASUSTek       | U35JC                       | Notebook    | [d5ba4e2fdf](https://linux-hardware.org/?probe=d5ba4e2fdf) | Apr 20, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [54084b1049](https://linux-hardware.org/?probe=54084b1049) | Apr 20, 2022 |
| Digma         | CITI 10 C402T CS1044EW      | Tablet      | [c9719f58e9](https://linux-hardware.org/?probe=c9719f58e9) | Apr 20, 2022 |
| Dell          | Precision M2300             | Notebook    | [05928bee5f](https://linux-hardware.org/?probe=05928bee5f) | Apr 20, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [76bcd3a380](https://linux-hardware.org/?probe=76bcd3a380) | Apr 20, 2022 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [1d8b7fa1f2](https://linux-hardware.org/?probe=1d8b7fa1f2) | Apr 20, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [96e7ccb1b4](https://linux-hardware.org/?probe=96e7ccb1b4) | Apr 20, 2022 |
| Unknown       | RS690-SB600                 | Desktop     | [0cb86e267f](https://linux-hardware.org/?probe=0cb86e267f) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a58503065e](https://linux-hardware.org/?probe=a58503065e) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c9f37aca9b](https://linux-hardware.org/?probe=c9f37aca9b) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [4505d43267](https://linux-hardware.org/?probe=4505d43267) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [bc8b33e0d2](https://linux-hardware.org/?probe=bc8b33e0d2) | Apr 20, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [f1881dec46](https://linux-hardware.org/?probe=f1881dec46) | Apr 20, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [790b162fa0](https://linux-hardware.org/?probe=790b162fa0) | Apr 20, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [8794debb03](https://linux-hardware.org/?probe=8794debb03) | Apr 20, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b09a55b7ad](https://linux-hardware.org/?probe=b09a55b7ad) | Apr 19, 2022 |
| ASUSTek       | X301A1                      | Notebook    | [b935ecb34c](https://linux-hardware.org/?probe=b935ecb34c) | Apr 19, 2022 |
| Foxconn       | G41MXP/G41MXP-V             | Desktop     | [61c0639dae](https://linux-hardware.org/?probe=61c0639dae) | Apr 19, 2022 |
| HP            | 8437                        | Desktop     | [f359fffed7](https://linux-hardware.org/?probe=f359fffed7) | Apr 19, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [b1eb98dd6a](https://linux-hardware.org/?probe=b1eb98dd6a) | Apr 19, 2022 |
| Huanan        | X79 V2.47                   | Desktop     | [7441d98b6a](https://linux-hardware.org/?probe=7441d98b6a) | Apr 19, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [6838edcb15](https://linux-hardware.org/?probe=6838edcb15) | Apr 19, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [4fd2fa24e4](https://linux-hardware.org/?probe=4fd2fa24e4) | Apr 19, 2022 |
| MSI           | MS-7388                     | Desktop     | [2d133cd746](https://linux-hardware.org/?probe=2d133cd746) | Apr 19, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [80950d86dc](https://linux-hardware.org/?probe=80950d86dc) | Apr 19, 2022 |
| Lenovo        | 312F NOK                    | Mini pc     | [98fdf4128a](https://linux-hardware.org/?probe=98fdf4128a) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fa53bb24d9](https://linux-hardware.org/?probe=fa53bb24d9) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9590ee5812](https://linux-hardware.org/?probe=9590ee5812) | Apr 19, 2022 |
| ASUSTek       | 1011PX                      | Notebook    | [264d31f34e](https://linux-hardware.org/?probe=264d31f34e) | Apr 19, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [72972fdcd8](https://linux-hardware.org/?probe=72972fdcd8) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [ccf6fb39e5](https://linux-hardware.org/?probe=ccf6fb39e5) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [ca58a7218c](https://linux-hardware.org/?probe=ca58a7218c) | Apr 19, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [b405ce3a31](https://linux-hardware.org/?probe=b405ce3a31) | Apr 19, 2022 |
| Acer          | Aspire A315-41G             | Notebook    | [a5ca05763e](https://linux-hardware.org/?probe=a5ca05763e) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [2da4cb3427](https://linux-hardware.org/?probe=2da4cb3427) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [77b103e672](https://linux-hardware.org/?probe=77b103e672) | Apr 19, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ec99a4a73b](https://linux-hardware.org/?probe=ec99a4a73b) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [25b490f8a8](https://linux-hardware.org/?probe=25b490f8a8) | Apr 19, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [f31bad1291](https://linux-hardware.org/?probe=f31bad1291) | Apr 19, 2022 |
| ASRock        | FM2A88X Pro+                | Desktop     | [fecedeccaf](https://linux-hardware.org/?probe=fecedeccaf) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [1f7e277528](https://linux-hardware.org/?probe=1f7e277528) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e03dec259a](https://linux-hardware.org/?probe=e03dec259a) | Apr 19, 2022 |
| Intel         | SKYBAY                      | Desktop     | [807bf178aa](https://linux-hardware.org/?probe=807bf178aa) | Apr 19, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [10f79ec4bc](https://linux-hardware.org/?probe=10f79ec4bc) | Apr 19, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [1c3459c038](https://linux-hardware.org/?probe=1c3459c038) | Apr 19, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [26c006e6e3](https://linux-hardware.org/?probe=26c006e6e3) | Apr 19, 2022 |
| Samsung       | 700T                        | Notebook    | [089fd14dad](https://linux-hardware.org/?probe=089fd14dad) | Apr 19, 2022 |
| ASUSTek       | M2N68-AM                    | Desktop     | [15c9b8ea76](https://linux-hardware.org/?probe=15c9b8ea76) | Apr 18, 2022 |
| Samsung       | 700T                        | Notebook    | [64407fe818](https://linux-hardware.org/?probe=64407fe818) | Apr 18, 2022 |
| MSI           | Z97-G43 GAMING              | Desktop     | [927a1a0b8d](https://linux-hardware.org/?probe=927a1a0b8d) | Apr 18, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [ec0d75d365](https://linux-hardware.org/?probe=ec0d75d365) | Apr 18, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [651d569b66](https://linux-hardware.org/?probe=651d569b66) | Apr 18, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [f3b566f07e](https://linux-hardware.org/?probe=f3b566f07e) | Apr 18, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [bee196bace](https://linux-hardware.org/?probe=bee196bace) | Apr 18, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [8070a851f2](https://linux-hardware.org/?probe=8070a851f2) | Apr 18, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [f94fb1535f](https://linux-hardware.org/?probe=f94fb1535f) | Apr 18, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [3ad8717f9a](https://linux-hardware.org/?probe=3ad8717f9a) | Apr 18, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [3ebe403371](https://linux-hardware.org/?probe=3ebe403371) | Apr 18, 2022 |
| AMI           | Intel                       | Convertible | [ed2743ce85](https://linux-hardware.org/?probe=ed2743ce85) | Apr 18, 2022 |
| Acer          | P7YE0                       | Notebook    | [5e81ff3f2e](https://linux-hardware.org/?probe=5e81ff3f2e) | Apr 18, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [8d13032194](https://linux-hardware.org/?probe=8d13032194) | Apr 18, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [f8696ef7df](https://linux-hardware.org/?probe=f8696ef7df) | Apr 18, 2022 |
| MSI           | G41M-P33 Combo              | Desktop     | [b3c127802c](https://linux-hardware.org/?probe=b3c127802c) | Apr 18, 2022 |
| ASUSTek       | N56VV                       | Notebook    | [2e4a4c394e](https://linux-hardware.org/?probe=2e4a4c394e) | Apr 18, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [2369e789c7](https://linux-hardware.org/?probe=2369e789c7) | Apr 18, 2022 |
| ASUSTek       | N56VV                       | Notebook    | [2ad328ebc8](https://linux-hardware.org/?probe=2ad328ebc8) | Apr 18, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [b97ab9e5ca](https://linux-hardware.org/?probe=b97ab9e5ca) | Apr 18, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [71ace683c7](https://linux-hardware.org/?probe=71ace683c7) | Apr 18, 2022 |
| ICL           | H310SB-TM                   | All in one  | [75dab395ac](https://linux-hardware.org/?probe=75dab395ac) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [39189517e8](https://linux-hardware.org/?probe=39189517e8) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [d0a06db2b3](https://linux-hardware.org/?probe=d0a06db2b3) | Apr 18, 2022 |
| ASUSTek       | M4A88T-I DELUXE             | Desktop     | [24d5e6293f](https://linux-hardware.org/?probe=24d5e6293f) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [33a738be3b](https://linux-hardware.org/?probe=33a738be3b) | Apr 18, 2022 |
| Acer          | RS780HVF                    | Desktop     | [cfccb88227](https://linux-hardware.org/?probe=cfccb88227) | Apr 18, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [a5bb696691](https://linux-hardware.org/?probe=a5bb696691) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a6631d6c9a](https://linux-hardware.org/?probe=a6631d6c9a) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7b60ea8e45](https://linux-hardware.org/?probe=7b60ea8e45) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [d78747839a](https://linux-hardware.org/?probe=d78747839a) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [faeb46556e](https://linux-hardware.org/?probe=faeb46556e) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [65fa83d729](https://linux-hardware.org/?probe=65fa83d729) | Apr 18, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [aa2de26f4f](https://linux-hardware.org/?probe=aa2de26f4f) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [41a7060cbe](https://linux-hardware.org/?probe=41a7060cbe) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5ce5f89e30](https://linux-hardware.org/?probe=5ce5f89e30) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [016707b662](https://linux-hardware.org/?probe=016707b662) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6225568c92](https://linux-hardware.org/?probe=6225568c92) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [1ec31e58eb](https://linux-hardware.org/?probe=1ec31e58eb) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [558e7d71c5](https://linux-hardware.org/?probe=558e7d71c5) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [58d8d12597](https://linux-hardware.org/?probe=58d8d12597) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [352ed8f1aa](https://linux-hardware.org/?probe=352ed8f1aa) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [f23db30412](https://linux-hardware.org/?probe=f23db30412) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [3fa8965015](https://linux-hardware.org/?probe=3fa8965015) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [287eb4cfbb](https://linux-hardware.org/?probe=287eb4cfbb) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [8c69097ae0](https://linux-hardware.org/?probe=8c69097ae0) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [be57c6ecd1](https://linux-hardware.org/?probe=be57c6ecd1) | Apr 18, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [472e946f77](https://linux-hardware.org/?probe=472e946f77) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [9202f2e9ef](https://linux-hardware.org/?probe=9202f2e9ef) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [f51e697243](https://linux-hardware.org/?probe=f51e697243) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [7e24715646](https://linux-hardware.org/?probe=7e24715646) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f227fe1fc7](https://linux-hardware.org/?probe=f227fe1fc7) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [a739d61b7b](https://linux-hardware.org/?probe=a739d61b7b) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [86a59150d4](https://linux-hardware.org/?probe=86a59150d4) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [e83eeef31e](https://linux-hardware.org/?probe=e83eeef31e) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [49039d6324](https://linux-hardware.org/?probe=49039d6324) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [39553516dd](https://linux-hardware.org/?probe=39553516dd) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [a0246c4b50](https://linux-hardware.org/?probe=a0246c4b50) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [9f87ee8978](https://linux-hardware.org/?probe=9f87ee8978) | Apr 18, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [f3d574e81e](https://linux-hardware.org/?probe=f3d574e81e) | Apr 18, 2022 |
| Biostar       | A320MH                      | Desktop     | [9beb151bac](https://linux-hardware.org/?probe=9beb151bac) | Apr 18, 2022 |
| Toshiba       | Satellite Pro L300          | Notebook    | [6b08a26a10](https://linux-hardware.org/?probe=6b08a26a10) | Apr 18, 2022 |
| ECS           | H310H5-M2                   | Desktop     | [653fae2086](https://linux-hardware.org/?probe=653fae2086) | Apr 18, 2022 |
| ASUSTek       | P5QL-E                      | Desktop     | [f5e7c2d5a1](https://linux-hardware.org/?probe=f5e7c2d5a1) | Apr 18, 2022 |
| Gigabyte      | G41MT-USB3                  | Desktop     | [4618c00b42](https://linux-hardware.org/?probe=4618c00b42) | Apr 17, 2022 |
| ASRock        | N68C-GS UCC                 | Desktop     | [444d0034c0](https://linux-hardware.org/?probe=444d0034c0) | Apr 17, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0e97aa77b4](https://linux-hardware.org/?probe=0e97aa77b4) | Apr 17, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [28836e512c](https://linux-hardware.org/?probe=28836e512c) | Apr 17, 2022 |
| HP            | Laptop 17-ca3xxx            | Notebook    | [3fa04a4195](https://linux-hardware.org/?probe=3fa04a4195) | Apr 17, 2022 |
| ASUSTek       | X550EP                      | Notebook    | [fbc44882a3](https://linux-hardware.org/?probe=fbc44882a3) | Apr 17, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [a245e4681b](https://linux-hardware.org/?probe=a245e4681b) | Apr 17, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [b3dd50d275](https://linux-hardware.org/?probe=b3dd50d275) | Apr 17, 2022 |
| Samsung       | R425D/R525D                 | Notebook    | [84fdb88779](https://linux-hardware.org/?probe=84fdb88779) | Apr 17, 2022 |
| MACHINIST     | B75 PRO V1.0                | Desktop     | [bc17af5881](https://linux-hardware.org/?probe=bc17af5881) | Apr 17, 2022 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [a61fc6c54e](https://linux-hardware.org/?probe=a61fc6c54e) | Apr 17, 2022 |
| HP            | EliteBook 8560w             | Notebook    | [1c7ab231f3](https://linux-hardware.org/?probe=1c7ab231f3) | Apr 17, 2022 |
| ASUSTek       | TUF Gaming H570-PRO         | Desktop     | [94b69dd7bc](https://linux-hardware.org/?probe=94b69dd7bc) | Apr 17, 2022 |
| Lenovo        | 3714 NOK                    | Desktop     | [80ed454cc3](https://linux-hardware.org/?probe=80ed454cc3) | Apr 17, 2022 |
| ASRock        | N68-GS                      | Desktop     | [b2c1441699](https://linux-hardware.org/?probe=b2c1441699) | Apr 17, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [1675f1f8a1](https://linux-hardware.org/?probe=1675f1f8a1) | Apr 17, 2022 |
| Acer          | Aspire F5-571G              | Notebook    | [16518ad895](https://linux-hardware.org/?probe=16518ad895) | Apr 17, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [c354af5ec4](https://linux-hardware.org/?probe=c354af5ec4) | Apr 17, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [211859a28f](https://linux-hardware.org/?probe=211859a28f) | Apr 17, 2022 |
| Acer          | Aspire C24-865              | All in one  | [873c58a401](https://linux-hardware.org/?probe=873c58a401) | Apr 17, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [ae0700c71c](https://linux-hardware.org/?probe=ae0700c71c) | Apr 17, 2022 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [5aa8ec8c7e](https://linux-hardware.org/?probe=5aa8ec8c7e) | Apr 17, 2022 |
| Acer          | Aspire 5720Z                | Notebook    | [e8155eac20](https://linux-hardware.org/?probe=e8155eac20) | Apr 16, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [4c505489d5](https://linux-hardware.org/?probe=4c505489d5) | Apr 16, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [861c47b139](https://linux-hardware.org/?probe=861c47b139) | Apr 16, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [c2a4357527](https://linux-hardware.org/?probe=c2a4357527) | Apr 16, 2022 |
| Lenovo        | IdeaPad Z565 20066          | Notebook    | [258c94f58b](https://linux-hardware.org/?probe=258c94f58b) | Apr 16, 2022 |
| Acer          | IPISB-AG                    | All in one  | [e263b7e641](https://linux-hardware.org/?probe=e263b7e641) | Apr 16, 2022 |
| DNS           | W510LU                      | Notebook    | [b3f74317f2](https://linux-hardware.org/?probe=b3f74317f2) | Apr 16, 2022 |
| Dell          | Precision M6800             | Notebook    | [a632e8de16](https://linux-hardware.org/?probe=a632e8de16) | Apr 16, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [690867d18c](https://linux-hardware.org/?probe=690867d18c) | Apr 16, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [2fe297dc4b](https://linux-hardware.org/?probe=2fe297dc4b) | Apr 16, 2022 |
| Samsung       | NB30P                       | Notebook    | [a64bf01edf](https://linux-hardware.org/?probe=a64bf01edf) | Apr 16, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [c9510b64e8](https://linux-hardware.org/?probe=c9510b64e8) | Apr 16, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [559213734d](https://linux-hardware.org/?probe=559213734d) | Apr 16, 2022 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [f9d5ba9c1c](https://linux-hardware.org/?probe=f9d5ba9c1c) | Apr 16, 2022 |
| Fujitsu       | LIFEBOOK P771               | Notebook    | [a6580631d1](https://linux-hardware.org/?probe=a6580631d1) | Apr 16, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [c20f1de565](https://linux-hardware.org/?probe=c20f1de565) | Apr 16, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [cb64383c99](https://linux-hardware.org/?probe=cb64383c99) | Apr 16, 2022 |
| MSI           | Z270-A PRO                  | Desktop     | [55c72a253b](https://linux-hardware.org/?probe=55c72a253b) | Apr 16, 2022 |
| Acer          | Aspire C24-865              | All in one  | [961f1373a2](https://linux-hardware.org/?probe=961f1373a2) | Apr 16, 2022 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [65116c3b59](https://linux-hardware.org/?probe=65116c3b59) | Apr 16, 2022 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [c8146beb84](https://linux-hardware.org/?probe=c8146beb84) | Apr 16, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [b097841482](https://linux-hardware.org/?probe=b097841482) | Apr 16, 2022 |
| Gigabyte      | EP31-DS3L                   | Desktop     | [13324a7aea](https://linux-hardware.org/?probe=13324a7aea) | Apr 15, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [5bff5642ba](https://linux-hardware.org/?probe=5bff5642ba) | Apr 15, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [3e7ec0a1bb](https://linux-hardware.org/?probe=3e7ec0a1bb) | Apr 15, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [bf274bc0f4](https://linux-hardware.org/?probe=bf274bc0f4) | Apr 15, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a01b211bb4](https://linux-hardware.org/?probe=a01b211bb4) | Apr 15, 2022 |
| ASUSTek       | M2NPV-MX                    | Desktop     | [8192abd2c4](https://linux-hardware.org/?probe=8192abd2c4) | Apr 15, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [83edb7e224](https://linux-hardware.org/?probe=83edb7e224) | Apr 15, 2022 |
| Dell          | Precision 5760              | Notebook    | [ba2ce021d0](https://linux-hardware.org/?probe=ba2ce021d0) | Apr 15, 2022 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [b9913d6c6b](https://linux-hardware.org/?probe=b9913d6c6b) | Apr 15, 2022 |
| Timi          | TM1701                      | Notebook    | [1eb7df8700](https://linux-hardware.org/?probe=1eb7df8700) | Apr 15, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [c58a4b9726](https://linux-hardware.org/?probe=c58a4b9726) | Apr 15, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cc6e57929e](https://linux-hardware.org/?probe=cc6e57929e) | Apr 15, 2022 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [aa36281de8](https://linux-hardware.org/?probe=aa36281de8) | Apr 15, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [e2e025dd4f](https://linux-hardware.org/?probe=e2e025dd4f) | Apr 15, 2022 |
| Insignia      | NS-P89W6100 V1.0            | Notebook    | [dabc8a93a8](https://linux-hardware.org/?probe=dabc8a93a8) | Apr 15, 2022 |
| MSI           | G31TM-P35                   | Desktop     | [f5aba83efe](https://linux-hardware.org/?probe=f5aba83efe) | Apr 15, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [4cf37abd8d](https://linux-hardware.org/?probe=4cf37abd8d) | Apr 15, 2022 |
| ASRock        | G41M-VGS3                   | Desktop     | [62f424c896](https://linux-hardware.org/?probe=62f424c896) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [c9c0498d72](https://linux-hardware.org/?probe=c9c0498d72) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [0735862439](https://linux-hardware.org/?probe=0735862439) | Apr 15, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [a9e2d5e0ef](https://linux-hardware.org/?probe=a9e2d5e0ef) | Apr 15, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [8b4c83d150](https://linux-hardware.org/?probe=8b4c83d150) | Apr 15, 2022 |
| KREZ          | TY1103B                     | Tablet      | [cea21e2ae8](https://linux-hardware.org/?probe=cea21e2ae8) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [f9202afa63](https://linux-hardware.org/?probe=f9202afa63) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [c5048041ee](https://linux-hardware.org/?probe=c5048041ee) | Apr 15, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [0b5246a205](https://linux-hardware.org/?probe=0b5246a205) | Apr 15, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [90559719b1](https://linux-hardware.org/?probe=90559719b1) | Apr 15, 2022 |
| Biostar       | G31M+                       | Desktop     | [bbc349a405](https://linux-hardware.org/?probe=bbc349a405) | Apr 15, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2aac95b872](https://linux-hardware.org/?probe=2aac95b872) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [6476542bc7](https://linux-hardware.org/?probe=6476542bc7) | Apr 14, 2022 |
| Huanan        | X99-AD3 V4.0                | Desktop     | [186bccefad](https://linux-hardware.org/?probe=186bccefad) | Apr 14, 2022 |
| HP            | Compaq 8710w                | Notebook    | [cd5964d073](https://linux-hardware.org/?probe=cd5964d073) | Apr 14, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [1e26bb146f](https://linux-hardware.org/?probe=1e26bb146f) | Apr 14, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [3a0df7b88f](https://linux-hardware.org/?probe=3a0df7b88f) | Apr 14, 2022 |
| HP            | ENVY 6                      | Notebook    | [deb09d7d7c](https://linux-hardware.org/?probe=deb09d7d7c) | Apr 14, 2022 |
| HP            | ENVY 6                      | Notebook    | [6cde3d35d8](https://linux-hardware.org/?probe=6cde3d35d8) | Apr 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [53137ae702](https://linux-hardware.org/?probe=53137ae702) | Apr 14, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [d23bd1d06f](https://linux-hardware.org/?probe=d23bd1d06f) | Apr 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | Notebook    | [62c216e798](https://linux-hardware.org/?probe=62c216e798) | Apr 14, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [ee523553f4](https://linux-hardware.org/?probe=ee523553f4) | Apr 14, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [3a04e2b5f2](https://linux-hardware.org/?probe=3a04e2b5f2) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [efa4160e79](https://linux-hardware.org/?probe=efa4160e79) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [d2c072abdf](https://linux-hardware.org/?probe=d2c072abdf) | Apr 14, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [3cde2f0fd5](https://linux-hardware.org/?probe=3cde2f0fd5) | Apr 14, 2022 |
| Acer          | TravelMate P215-53          | Notebook    | [124fdb3b64](https://linux-hardware.org/?probe=124fdb3b64) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [a98b8b4304](https://linux-hardware.org/?probe=a98b8b4304) | Apr 14, 2022 |
| Intel         | SKYBAY                      | Desktop     | [0d3978670a](https://linux-hardware.org/?probe=0d3978670a) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [3829d7dfca](https://linux-hardware.org/?probe=3829d7dfca) | Apr 14, 2022 |
| Intel         | SKYBAY                      | Desktop     | [13122b16be](https://linux-hardware.org/?probe=13122b16be) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [86164212e5](https://linux-hardware.org/?probe=86164212e5) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [37ebd7e15e](https://linux-hardware.org/?probe=37ebd7e15e) | Apr 14, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [14eacf8520](https://linux-hardware.org/?probe=14eacf8520) | Apr 14, 2022 |
| Samsung       | R425D/R525D                 | Notebook    | [bd5a2f5943](https://linux-hardware.org/?probe=bd5a2f5943) | Apr 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [a4da99355b](https://linux-hardware.org/?probe=a4da99355b) | Apr 14, 2022 |
| HP            | Pavilion m6                 | Notebook    | [2886b9d0c1](https://linux-hardware.org/?probe=2886b9d0c1) | Apr 13, 2022 |
| Acer          | Extensa 5620                | Notebook    | [b19ed102e0](https://linux-hardware.org/?probe=b19ed102e0) | Apr 13, 2022 |
| Gigabyte      | GA-A55M-S2HP                | Desktop     | [68c70673ef](https://linux-hardware.org/?probe=68c70673ef) | Apr 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [080a434f1e](https://linux-hardware.org/?probe=080a434f1e) | Apr 13, 2022 |
| HPE           | ProLiant MicroServer Gen... | Server      | [3c0b8415b8](https://linux-hardware.org/?probe=3c0b8415b8) | Apr 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [26a879283d](https://linux-hardware.org/?probe=26a879283d) | Apr 13, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [567d83946c](https://linux-hardware.org/?probe=567d83946c) | Apr 13, 2022 |
| Acer          | AOA110                      | Notebook    | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| Dell          | Latitude 3420               | Notebook    | [f3278afeb0](https://linux-hardware.org/?probe=f3278afeb0) | Apr 13, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [dd7e61aef2](https://linux-hardware.org/?probe=dd7e61aef2) | Apr 13, 2022 |
| Dell          | Latitude 3420               | Notebook    | [2388ba39b8](https://linux-hardware.org/?probe=2388ba39b8) | Apr 13, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [fcc2e4ef69](https://linux-hardware.org/?probe=fcc2e4ef69) | Apr 13, 2022 |
| MSI           | B360M PRO-VDH               | Desktop     | [33af7f8008](https://linux-hardware.org/?probe=33af7f8008) | Apr 13, 2022 |
| ONDA          | OBOOK 20 PLUS               | Notebook    | [f4f58931b7](https://linux-hardware.org/?probe=f4f58931b7) | Apr 13, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [f420769b88](https://linux-hardware.org/?probe=f420769b88) | Apr 13, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [87deb321d4](https://linux-hardware.org/?probe=87deb321d4) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [82df5d5154](https://linux-hardware.org/?probe=82df5d5154) | Apr 13, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [2b8e6fdd29](https://linux-hardware.org/?probe=2b8e6fdd29) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [c55e8d0780](https://linux-hardware.org/?probe=c55e8d0780) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [46344da31f](https://linux-hardware.org/?probe=46344da31f) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [906a9f0a46](https://linux-hardware.org/?probe=906a9f0a46) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [482922befd](https://linux-hardware.org/?probe=482922befd) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [2cb7352d17](https://linux-hardware.org/?probe=2cb7352d17) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [54f3bbf0af](https://linux-hardware.org/?probe=54f3bbf0af) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f7d3604a6b](https://linux-hardware.org/?probe=f7d3604a6b) | Apr 13, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [7c6efad935](https://linux-hardware.org/?probe=7c6efad935) | Apr 13, 2022 |
| Lenovo        | ThinkPad E480 20KN001VRT    | Notebook    | [43b93d84fd](https://linux-hardware.org/?probe=43b93d84fd) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [40083e1990](https://linux-hardware.org/?probe=40083e1990) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ecf34aa4f0](https://linux-hardware.org/?probe=ecf34aa4f0) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [c2e18d9346](https://linux-hardware.org/?probe=c2e18d9346) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [0e2380e59d](https://linux-hardware.org/?probe=0e2380e59d) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [baf8cdeb1a](https://linux-hardware.org/?probe=baf8cdeb1a) | Apr 13, 2022 |
| Intel         | X79 V1.3                    | Desktop     | [7f3431a44d](https://linux-hardware.org/?probe=7f3431a44d) | Apr 13, 2022 |
| MSI           | C847IS-P33                  | Desktop     | [1d421862e1](https://linux-hardware.org/?probe=1d421862e1) | Apr 13, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [e517f230fa](https://linux-hardware.org/?probe=e517f230fa) | Apr 13, 2022 |
| HP            | Notebook                    | Notebook    | [e15febc7e4](https://linux-hardware.org/?probe=e15febc7e4) | Apr 13, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [123febbcd2](https://linux-hardware.org/?probe=123febbcd2) | Apr 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [ce4447422d](https://linux-hardware.org/?probe=ce4447422d) | Apr 13, 2022 |
| Haier         | S424                        | Notebook    | [c0b23cd835](https://linux-hardware.org/?probe=c0b23cd835) | Apr 13, 2022 |
| Lenovo        | ThinkPad T440p              | Notebook    | [45a1ee6fbf](https://linux-hardware.org/?probe=45a1ee6fbf) | Apr 12, 2022 |
| ASRock        | B560 Steel Legend           | Desktop     | [2b96c77aae](https://linux-hardware.org/?probe=2b96c77aae) | Apr 12, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [9d1d134940](https://linux-hardware.org/?probe=9d1d134940) | Apr 12, 2022 |
| Dell          | Latitude E6530              | Notebook    | [597013072b](https://linux-hardware.org/?probe=597013072b) | Apr 12, 2022 |
| ASUSTek       | N56VJ                       | Notebook    | [02581c1388](https://linux-hardware.org/?probe=02581c1388) | Apr 12, 2022 |
| Gigabyte      | U2152                       | Notebook    | [f668079691](https://linux-hardware.org/?probe=f668079691) | Apr 12, 2022 |
| Intel         | DP43TF AAE34878-401         | Desktop     | [69a9b1705c](https://linux-hardware.org/?probe=69a9b1705c) | Apr 12, 2022 |
| Dell          | Vostro 14-5459              | Notebook    | [89d65f0a36](https://linux-hardware.org/?probe=89d65f0a36) | Apr 12, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1eacb6915d](https://linux-hardware.org/?probe=1eacb6915d) | Apr 12, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [deda69fa6d](https://linux-hardware.org/?probe=deda69fa6d) | Apr 12, 2022 |
| ASUSTek       | P5K Premium                 | Desktop     | [93ea12ef83](https://linux-hardware.org/?probe=93ea12ef83) | Apr 12, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [eaf3d1ac6f](https://linux-hardware.org/?probe=eaf3d1ac6f) | Apr 12, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0622e51d45](https://linux-hardware.org/?probe=0622e51d45) | Apr 12, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [2ed1b1bd6f](https://linux-hardware.org/?probe=2ed1b1bd6f) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [84e70046d5](https://linux-hardware.org/?probe=84e70046d5) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [92f6d24bde](https://linux-hardware.org/?probe=92f6d24bde) | Apr 12, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [3cd8b545ab](https://linux-hardware.org/?probe=3cd8b545ab) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [8e924a50c1](https://linux-hardware.org/?probe=8e924a50c1) | Apr 12, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [0fecbe6cdc](https://linux-hardware.org/?probe=0fecbe6cdc) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [99d19658b8](https://linux-hardware.org/?probe=99d19658b8) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [b6bcbc6a65](https://linux-hardware.org/?probe=b6bcbc6a65) | Apr 12, 2022 |
| Dell          | Latitude 3420               | Notebook    | [ecdf7b8de0](https://linux-hardware.org/?probe=ecdf7b8de0) | Apr 12, 2022 |
| Lenovo        | M5400 20281                 | Notebook    | [dd1a23fe3f](https://linux-hardware.org/?probe=dd1a23fe3f) | Apr 12, 2022 |
| Dell          | Latitude 3420               | Notebook    | [4361233072](https://linux-hardware.org/?probe=4361233072) | Apr 12, 2022 |
| Lenovo        | ThinkPad Z61m 94528QG       | Notebook    | [0da32925f1](https://linux-hardware.org/?probe=0da32925f1) | Apr 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [e41a749271](https://linux-hardware.org/?probe=e41a749271) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [19f3a71bf4](https://linux-hardware.org/?probe=19f3a71bf4) | Apr 12, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [0860ee5a64](https://linux-hardware.org/?probe=0860ee5a64) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [97d94278ea](https://linux-hardware.org/?probe=97d94278ea) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [4f1aa9470b](https://linux-hardware.org/?probe=4f1aa9470b) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [7537241f1d](https://linux-hardware.org/?probe=7537241f1d) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [d6792fe869](https://linux-hardware.org/?probe=d6792fe869) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [e3236de077](https://linux-hardware.org/?probe=e3236de077) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5ebaca158a](https://linux-hardware.org/?probe=5ebaca158a) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7e40f60767](https://linux-hardware.org/?probe=7e40f60767) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ce83b095fe](https://linux-hardware.org/?probe=ce83b095fe) | Apr 12, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [3e7d8951a2](https://linux-hardware.org/?probe=3e7d8951a2) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [105088d6de](https://linux-hardware.org/?probe=105088d6de) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [126b987221](https://linux-hardware.org/?probe=126b987221) | Apr 12, 2022 |
| Lenovo        | ThinkPad E570 20H500BWRT    | Notebook    | [4a77c37654](https://linux-hardware.org/?probe=4a77c37654) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5d59afae00](https://linux-hardware.org/?probe=5d59afae00) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [442de26b34](https://linux-hardware.org/?probe=442de26b34) | Apr 12, 2022 |
| Lenovo        | V570c HuronRiver Platfor... | Notebook    | [0858e6ff56](https://linux-hardware.org/?probe=0858e6ff56) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [9d7fc26276](https://linux-hardware.org/?probe=9d7fc26276) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e07ab03ffb](https://linux-hardware.org/?probe=e07ab03ffb) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [b4b977309d](https://linux-hardware.org/?probe=b4b977309d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [bff39744bc](https://linux-hardware.org/?probe=bff39744bc) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [01cd534e80](https://linux-hardware.org/?probe=01cd534e80) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [2d62dd7b61](https://linux-hardware.org/?probe=2d62dd7b61) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [0eae0dfd04](https://linux-hardware.org/?probe=0eae0dfd04) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [669e6289c0](https://linux-hardware.org/?probe=669e6289c0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d49df4c170](https://linux-hardware.org/?probe=d49df4c170) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [01aa1a4299](https://linux-hardware.org/?probe=01aa1a4299) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [65b8e561ab](https://linux-hardware.org/?probe=65b8e561ab) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [a85817bb6d](https://linux-hardware.org/?probe=a85817bb6d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [25955c9bb1](https://linux-hardware.org/?probe=25955c9bb1) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [b95e628a8f](https://linux-hardware.org/?probe=b95e628a8f) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [0c81aeca67](https://linux-hardware.org/?probe=0c81aeca67) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e72fe0a0a9](https://linux-hardware.org/?probe=e72fe0a0a9) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [33b61b457e](https://linux-hardware.org/?probe=33b61b457e) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d6c6259cc0](https://linux-hardware.org/?probe=d6c6259cc0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f2444b315d](https://linux-hardware.org/?probe=f2444b315d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [aa745aba70](https://linux-hardware.org/?probe=aa745aba70) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [d05023771a](https://linux-hardware.org/?probe=d05023771a) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [655584ea45](https://linux-hardware.org/?probe=655584ea45) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [a6527519c6](https://linux-hardware.org/?probe=a6527519c6) | Apr 12, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [6b70f0a384](https://linux-hardware.org/?probe=6b70f0a384) | Apr 12, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [b6f41e002d](https://linux-hardware.org/?probe=b6f41e002d) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [f8931a9e1e](https://linux-hardware.org/?probe=f8931a9e1e) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [3b73c79a3c](https://linux-hardware.org/?probe=3b73c79a3c) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d1a4cd1698](https://linux-hardware.org/?probe=d1a4cd1698) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [54713393ec](https://linux-hardware.org/?probe=54713393ec) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [56d2022832](https://linux-hardware.org/?probe=56d2022832) | Apr 12, 2022 |
| MSI           | GS60 2QE                    | Notebook    | [e4d200b4fe](https://linux-hardware.org/?probe=e4d200b4fe) | Apr 12, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [0025682d7d](https://linux-hardware.org/?probe=0025682d7d) | Apr 12, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d751a52423](https://linux-hardware.org/?probe=d751a52423) | Apr 11, 2022 |
| eMachines     | E725                        | Notebook    | [cd03638757](https://linux-hardware.org/?probe=cd03638757) | Apr 11, 2022 |
| Acer          | Aspire 5734Z                | Notebook    | [982dccf136](https://linux-hardware.org/?probe=982dccf136) | Apr 11, 2022 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [a0ff638057](https://linux-hardware.org/?probe=a0ff638057) | Apr 11, 2022 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [3b949d56a9](https://linux-hardware.org/?probe=3b949d56a9) | Apr 11, 2022 |
| Acer          | Aspire A514-52K             | Notebook    | [085e03c893](https://linux-hardware.org/?probe=085e03c893) | Apr 11, 2022 |
| Acer          | Aspire A514-52K             | Notebook    | [0157eea2f6](https://linux-hardware.org/?probe=0157eea2f6) | Apr 11, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1c15e67e64](https://linux-hardware.org/?probe=1c15e67e64) | Apr 11, 2022 |
| Intel         | DP43TF AAE34878-401         | Desktop     | [7ddb79a059](https://linux-hardware.org/?probe=7ddb79a059) | Apr 11, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [259f72f743](https://linux-hardware.org/?probe=259f72f743) | Apr 11, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c2de5fcfd5](https://linux-hardware.org/?probe=c2de5fcfd5) | Apr 11, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [5cc893af9c](https://linux-hardware.org/?probe=5cc893af9c) | Apr 11, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [816c91bfcd](https://linux-hardware.org/?probe=816c91bfcd) | Apr 11, 2022 |
| Intel         | Tiger Hill                  | Desktop     | [1fbea29754](https://linux-hardware.org/?probe=1fbea29754) | Apr 11, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [3e5dde6b49](https://linux-hardware.org/?probe=3e5dde6b49) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [71dfb9a346](https://linux-hardware.org/?probe=71dfb9a346) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [7cf5bcdb89](https://linux-hardware.org/?probe=7cf5bcdb89) | Apr 11, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [d43f5778b1](https://linux-hardware.org/?probe=d43f5778b1) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [efbe0a9eca](https://linux-hardware.org/?probe=efbe0a9eca) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [60fbf7929d](https://linux-hardware.org/?probe=60fbf7929d) | Apr 11, 2022 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [a52c5e98af](https://linux-hardware.org/?probe=a52c5e98af) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [6aaab98810](https://linux-hardware.org/?probe=6aaab98810) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e9a0bae6e6](https://linux-hardware.org/?probe=e9a0bae6e6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4fb63d6dfe](https://linux-hardware.org/?probe=4fb63d6dfe) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [dde0916ae5](https://linux-hardware.org/?probe=dde0916ae5) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [8ee5753b25](https://linux-hardware.org/?probe=8ee5753b25) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [6fb5a857e1](https://linux-hardware.org/?probe=6fb5a857e1) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [613ea0ab6b](https://linux-hardware.org/?probe=613ea0ab6b) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [2aeec4566f](https://linux-hardware.org/?probe=2aeec4566f) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [7289268e39](https://linux-hardware.org/?probe=7289268e39) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5751abaf6c](https://linux-hardware.org/?probe=5751abaf6c) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [31b40a1aa0](https://linux-hardware.org/?probe=31b40a1aa0) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d3bbe595ba](https://linux-hardware.org/?probe=d3bbe595ba) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [24d5b7f6c6](https://linux-hardware.org/?probe=24d5b7f6c6) | Apr 11, 2022 |
| Dell          | Latitude 3420               | Notebook    | [d436f78355](https://linux-hardware.org/?probe=d436f78355) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f94dbbfc1f](https://linux-hardware.org/?probe=f94dbbfc1f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [960168908f](https://linux-hardware.org/?probe=960168908f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [71610e6e10](https://linux-hardware.org/?probe=71610e6e10) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d2407bd778](https://linux-hardware.org/?probe=d2407bd778) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [88fc4d57ec](https://linux-hardware.org/?probe=88fc4d57ec) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [a1cbc192aa](https://linux-hardware.org/?probe=a1cbc192aa) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [66d94b1220](https://linux-hardware.org/?probe=66d94b1220) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e8c2f02ba1](https://linux-hardware.org/?probe=e8c2f02ba1) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [7ef15ed6c9](https://linux-hardware.org/?probe=7ef15ed6c9) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [8bcad9c229](https://linux-hardware.org/?probe=8bcad9c229) | Apr 11, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [958de67015](https://linux-hardware.org/?probe=958de67015) | Apr 11, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [a03ff53e01](https://linux-hardware.org/?probe=a03ff53e01) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5486388fa0](https://linux-hardware.org/?probe=5486388fa0) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [68041f0a96](https://linux-hardware.org/?probe=68041f0a96) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [87858c448c](https://linux-hardware.org/?probe=87858c448c) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [a7e615a620](https://linux-hardware.org/?probe=a7e615a620) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [5b340e2b7f](https://linux-hardware.org/?probe=5b340e2b7f) | Apr 11, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [237634ce8d](https://linux-hardware.org/?probe=237634ce8d) | Apr 11, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [e027a7672d](https://linux-hardware.org/?probe=e027a7672d) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [83b01e222e](https://linux-hardware.org/?probe=83b01e222e) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [5f90eb0f80](https://linux-hardware.org/?probe=5f90eb0f80) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [a20cfb8d86](https://linux-hardware.org/?probe=a20cfb8d86) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [c6f290816a](https://linux-hardware.org/?probe=c6f290816a) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [60c4fc315b](https://linux-hardware.org/?probe=60c4fc315b) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [faad64ac67](https://linux-hardware.org/?probe=faad64ac67) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [19d0ee846e](https://linux-hardware.org/?probe=19d0ee846e) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [9e2f7749b8](https://linux-hardware.org/?probe=9e2f7749b8) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f3fe662dcb](https://linux-hardware.org/?probe=f3fe662dcb) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [5293db1b11](https://linux-hardware.org/?probe=5293db1b11) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7d3b364ff0](https://linux-hardware.org/?probe=7d3b364ff0) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d8307a4138](https://linux-hardware.org/?probe=d8307a4138) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [bffde28b59](https://linux-hardware.org/?probe=bffde28b59) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d31dd74d7](https://linux-hardware.org/?probe=7d31dd74d7) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d03a291a2](https://linux-hardware.org/?probe=7d03a291a2) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [91f33b247d](https://linux-hardware.org/?probe=91f33b247d) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [2628069096](https://linux-hardware.org/?probe=2628069096) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7c2a257e92](https://linux-hardware.org/?probe=7c2a257e92) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [868b030342](https://linux-hardware.org/?probe=868b030342) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4088112a18](https://linux-hardware.org/?probe=4088112a18) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [68820282cb](https://linux-hardware.org/?probe=68820282cb) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [5a5a1a7ae6](https://linux-hardware.org/?probe=5a5a1a7ae6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [936252dfca](https://linux-hardware.org/?probe=936252dfca) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [67ed2ddd29](https://linux-hardware.org/?probe=67ed2ddd29) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [fde95ea3ed](https://linux-hardware.org/?probe=fde95ea3ed) | Apr 11, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5dbdb89f95](https://linux-hardware.org/?probe=5dbdb89f95) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [de01821ecf](https://linux-hardware.org/?probe=de01821ecf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [67f41bf764](https://linux-hardware.org/?probe=67f41bf764) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [77aadf6511](https://linux-hardware.org/?probe=77aadf6511) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [cb9ae4e880](https://linux-hardware.org/?probe=cb9ae4e880) | Apr 11, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [0199b0b388](https://linux-hardware.org/?probe=0199b0b388) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d2a24f0327](https://linux-hardware.org/?probe=d2a24f0327) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [498dd8c409](https://linux-hardware.org/?probe=498dd8c409) | Apr 11, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [a473baa2ff](https://linux-hardware.org/?probe=a473baa2ff) | Apr 11, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [12009b21d8](https://linux-hardware.org/?probe=12009b21d8) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [fa2978c8db](https://linux-hardware.org/?probe=fa2978c8db) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [150ce1c4dd](https://linux-hardware.org/?probe=150ce1c4dd) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [76e9ddaa30](https://linux-hardware.org/?probe=76e9ddaa30) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [43c08af7bf](https://linux-hardware.org/?probe=43c08af7bf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [093a6488c3](https://linux-hardware.org/?probe=093a6488c3) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [730280aef1](https://linux-hardware.org/?probe=730280aef1) | Apr 11, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [cb60e697d1](https://linux-hardware.org/?probe=cb60e697d1) | Apr 11, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1b2b5e921d](https://linux-hardware.org/?probe=1b2b5e921d) | Apr 11, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [95ae38af4e](https://linux-hardware.org/?probe=95ae38af4e) | Apr 11, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [eb62b9de81](https://linux-hardware.org/?probe=eb62b9de81) | Apr 11, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [a32957f98c](https://linux-hardware.org/?probe=a32957f98c) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [3f2bf77788](https://linux-hardware.org/?probe=3f2bf77788) | Apr 11, 2022 |
| KLLISRE       | X99-B5 V1.1                 | Desktop     | [5c1d47d9c9](https://linux-hardware.org/?probe=5c1d47d9c9) | Apr 11, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [34fa61f6bd](https://linux-hardware.org/?probe=34fa61f6bd) | Apr 11, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [5de4abca91](https://linux-hardware.org/?probe=5de4abca91) | Apr 11, 2022 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [67018740b8](https://linux-hardware.org/?probe=67018740b8) | Apr 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [c913cb5a4a](https://linux-hardware.org/?probe=c913cb5a4a) | Apr 11, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [379db407c7](https://linux-hardware.org/?probe=379db407c7) | Apr 10, 2022 |
| Gigabyte      | B75-D3V                     | Desktop     | [ea939b5214](https://linux-hardware.org/?probe=ea939b5214) | Apr 10, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [335125845e](https://linux-hardware.org/?probe=335125845e) | Apr 10, 2022 |
| Intel         | X99                         | Desktop     | [ecea2585e1](https://linux-hardware.org/?probe=ecea2585e1) | Apr 10, 2022 |
| Dell          | Inspiron 5759               | Notebook    | [315fcfc017](https://linux-hardware.org/?probe=315fcfc017) | Apr 10, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [5abfaa2b99](https://linux-hardware.org/?probe=5abfaa2b99) | Apr 10, 2022 |
| Digma         | CITI 10 C402T CS1044EW      | Tablet      | [86b7cacae8](https://linux-hardware.org/?probe=86b7cacae8) | Apr 10, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [071e82f576](https://linux-hardware.org/?probe=071e82f576) | Apr 10, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [40dd641006](https://linux-hardware.org/?probe=40dd641006) | Apr 10, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [2e80786e39](https://linux-hardware.org/?probe=2e80786e39) | Apr 10, 2022 |
| HP            | 15                          | Notebook    | [43254accc2](https://linux-hardware.org/?probe=43254accc2) | Apr 10, 2022 |
| HP            | Pavilion 15                 | Notebook    | [f69f54968e](https://linux-hardware.org/?probe=f69f54968e) | Apr 10, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [7bc4dfd917](https://linux-hardware.org/?probe=7bc4dfd917) | Apr 10, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [f4b5ca3229](https://linux-hardware.org/?probe=f4b5ca3229) | Apr 10, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [63aaae3d92](https://linux-hardware.org/?probe=63aaae3d92) | Apr 10, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [8737781637](https://linux-hardware.org/?probe=8737781637) | Apr 10, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [a71131cba6](https://linux-hardware.org/?probe=a71131cba6) | Apr 10, 2022 |
| Lenovo        | Legion Y540-17IRH 81UJ      | Notebook    | [d29d125641](https://linux-hardware.org/?probe=d29d125641) | Apr 10, 2022 |
| ASUSTek       | F5RL                        | Notebook    | [c4f44cce57](https://linux-hardware.org/?probe=c4f44cce57) | Apr 10, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [9014595f74](https://linux-hardware.org/?probe=9014595f74) | Apr 10, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [8760e3254a](https://linux-hardware.org/?probe=8760e3254a) | Apr 10, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [dd55fda409](https://linux-hardware.org/?probe=dd55fda409) | Apr 10, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [18063bba4f](https://linux-hardware.org/?probe=18063bba4f) | Apr 10, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [97e92ead43](https://linux-hardware.org/?probe=97e92ead43) | Apr 10, 2022 |
| Sony          | VGN-TT31MR_N                | Notebook    | [d8eb5d22da](https://linux-hardware.org/?probe=d8eb5d22da) | Apr 10, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [cff76ec96f](https://linux-hardware.org/?probe=cff76ec96f) | Apr 10, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [d61b8a12b8](https://linux-hardware.org/?probe=d61b8a12b8) | Apr 10, 2022 |
| Lenovo        | B560                        | Notebook    | [276b375e4a](https://linux-hardware.org/?probe=276b375e4a) | Apr 09, 2022 |
| eMachines     | G525                        | Notebook    | [6ba45c519c](https://linux-hardware.org/?probe=6ba45c519c) | Apr 09, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [645fb7bb30](https://linux-hardware.org/?probe=645fb7bb30) | Apr 09, 2022 |
| Intel         | NUC5i3MYBE H47781-203       | Mini pc     | [0f2cd9d89c](https://linux-hardware.org/?probe=0f2cd9d89c) | Apr 09, 2022 |
| Irbis         | NB211                       | Notebook    | [75ad10cc68](https://linux-hardware.org/?probe=75ad10cc68) | Apr 09, 2022 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [43c15ac73b](https://linux-hardware.org/?probe=43c15ac73b) | Apr 09, 2022 |
| Dell          | Latitude 7275               | Notebook    | [fe36710853](https://linux-hardware.org/?probe=fe36710853) | Apr 09, 2022 |
| Dell          | Latitude 7275               | Notebook    | [e6bc45d8d9](https://linux-hardware.org/?probe=e6bc45d8d9) | Apr 09, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [00d95f7a3a](https://linux-hardware.org/?probe=00d95f7a3a) | Apr 09, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [f728cf4c2c](https://linux-hardware.org/?probe=f728cf4c2c) | Apr 09, 2022 |
| Acer          | Aspire E5-532               | Notebook    | [d2135748fe](https://linux-hardware.org/?probe=d2135748fe) | Apr 09, 2022 |
| Sony          | VGN-NR31ZR_S                | Notebook    | [aa9e4ae485](https://linux-hardware.org/?probe=aa9e4ae485) | Apr 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [81955f7534](https://linux-hardware.org/?probe=81955f7534) | Apr 09, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [d19ae9b1d5](https://linux-hardware.org/?probe=d19ae9b1d5) | Apr 09, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [01bc8ef97c](https://linux-hardware.org/?probe=01bc8ef97c) | Apr 09, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [0326b913dd](https://linux-hardware.org/?probe=0326b913dd) | Apr 09, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [6f7d1fdcbf](https://linux-hardware.org/?probe=6f7d1fdcbf) | Apr 09, 2022 |
| ASRock        | P43DE3                      | Desktop     | [21eed63d16](https://linux-hardware.org/?probe=21eed63d16) | Apr 09, 2022 |
| Acer          | Nitro AN515-56              | Notebook    | [c46bf4b738](https://linux-hardware.org/?probe=c46bf4b738) | Apr 09, 2022 |
| Intel         | DP35DP AAD81073-206         | Desktop     | [b257e3cf76](https://linux-hardware.org/?probe=b257e3cf76) | Apr 09, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [272c9f107a](https://linux-hardware.org/?probe=272c9f107a) | Apr 09, 2022 |
| Acer          | Nitro AN515-56              | Notebook    | [3c444ad400](https://linux-hardware.org/?probe=3c444ad400) | Apr 09, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [31ecc9c776](https://linux-hardware.org/?probe=31ecc9c776) | Apr 09, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [457adc950f](https://linux-hardware.org/?probe=457adc950f) | Apr 09, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [ea4da8fb23](https://linux-hardware.org/?probe=ea4da8fb23) | Apr 09, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [bb210a31b5](https://linux-hardware.org/?probe=bb210a31b5) | Apr 09, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [09946e9edf](https://linux-hardware.org/?probe=09946e9edf) | Apr 09, 2022 |
| Supermicro    | H12SSL-i                    | Server      | [7bdae699e5](https://linux-hardware.org/?probe=7bdae699e5) | Apr 09, 2022 |
| DNS           | Unknown                     | Notebook    | [ce4a6e5c43](https://linux-hardware.org/?probe=ce4a6e5c43) | Apr 09, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [387e498dfc](https://linux-hardware.org/?probe=387e498dfc) | Apr 09, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [f5ee5fd187](https://linux-hardware.org/?probe=f5ee5fd187) | Apr 09, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [10c3b376de](https://linux-hardware.org/?probe=10c3b376de) | Apr 09, 2022 |
| Acer          | Aspire A317-32              | Notebook    | [208930d29c](https://linux-hardware.org/?probe=208930d29c) | Apr 09, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [b40816245c](https://linux-hardware.org/?probe=b40816245c) | Apr 09, 2022 |
| ASUSTek       | 1011PX                      | Notebook    | [3d06c8719d](https://linux-hardware.org/?probe=3d06c8719d) | Apr 08, 2022 |
| Acer          | Aspire C24-320              | All in one  | [54cb792966](https://linux-hardware.org/?probe=54cb792966) | Apr 08, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [f2af37f520](https://linux-hardware.org/?probe=f2af37f520) | Apr 08, 2022 |
| ASRock        | H61M-S                      | Desktop     | [7f0b28837f](https://linux-hardware.org/?probe=7f0b28837f) | Apr 08, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [be7a7cb25f](https://linux-hardware.org/?probe=be7a7cb25f) | Apr 08, 2022 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [74c07daf2f](https://linux-hardware.org/?probe=74c07daf2f) | Apr 08, 2022 |
| Acer          | Aspire 1830T                | Notebook    | [b5348b2c70](https://linux-hardware.org/?probe=b5348b2c70) | Apr 08, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [ac9ab2383f](https://linux-hardware.org/?probe=ac9ab2383f) | Apr 08, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [9a2939bd71](https://linux-hardware.org/?probe=9a2939bd71) | Apr 08, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [16ac7687a0](https://linux-hardware.org/?probe=16ac7687a0) | Apr 08, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [7a337eb0a8](https://linux-hardware.org/?probe=7a337eb0a8) | Apr 08, 2022 |
| Packard Be... | EasyNote LM85               | Notebook    | [56cf496cf2](https://linux-hardware.org/?probe=56cf496cf2) | Apr 08, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [5da93676f7](https://linux-hardware.org/?probe=5da93676f7) | Apr 08, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [8ab0db4e45](https://linux-hardware.org/?probe=8ab0db4e45) | Apr 08, 2022 |
| Packard Be... | EasyNote LM85               | Notebook    | [32140f5b90](https://linux-hardware.org/?probe=32140f5b90) | Apr 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [bce81d50a8](https://linux-hardware.org/?probe=bce81d50a8) | Apr 08, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [0291e8b387](https://linux-hardware.org/?probe=0291e8b387) | Apr 08, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [256fd58a92](https://linux-hardware.org/?probe=256fd58a92) | Apr 08, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [8986d7abf1](https://linux-hardware.org/?probe=8986d7abf1) | Apr 08, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b7b2d796d9](https://linux-hardware.org/?probe=b7b2d796d9) | Apr 08, 2022 |
| Supermicro    | H12SSL-i                    | Server      | [4f88fe663e](https://linux-hardware.org/?probe=4f88fe663e) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| Dell          | Latitude E7470              | Notebook    | [bf1da3bb88](https://linux-hardware.org/?probe=bf1da3bb88) | Apr 08, 2022 |
| eMachines     | eM355                       | Notebook    | [76ddd795cc](https://linux-hardware.org/?probe=76ddd795cc) | Apr 08, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [304330a609](https://linux-hardware.org/?probe=304330a609) | Apr 08, 2022 |
| Acer          | AOD255                      | Notebook    | [f1a5682c95](https://linux-hardware.org/?probe=f1a5682c95) | Apr 08, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [7e98fd7db9](https://linux-hardware.org/?probe=7e98fd7db9) | Apr 08, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [256bfd0a56](https://linux-hardware.org/?probe=256bfd0a56) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [043d63cc06](https://linux-hardware.org/?probe=043d63cc06) | Apr 08, 2022 |
| Dell          | Latitude 7300               | Notebook    | [239c1feb38](https://linux-hardware.org/?probe=239c1feb38) | Apr 08, 2022 |
| ASUSTek       | N551JB                      | Notebook    | [edbf102771](https://linux-hardware.org/?probe=edbf102771) | Apr 08, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [1ffbc3333e](https://linux-hardware.org/?probe=1ffbc3333e) | Apr 07, 2022 |
| MSI           | Z270 TOMAHAWK               | Desktop     | [4063e06462](https://linux-hardware.org/?probe=4063e06462) | Apr 07, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [ce26da001a](https://linux-hardware.org/?probe=ce26da001a) | Apr 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bc8934f133](https://linux-hardware.org/?probe=bc8934f133) | Apr 07, 2022 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [f1f94d1273](https://linux-hardware.org/?probe=f1f94d1273) | Apr 07, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [7b41cf9275](https://linux-hardware.org/?probe=7b41cf9275) | Apr 07, 2022 |
| Digma         | EVE 10 C301 ES1050EW        | Notebook    | [7db1a321e8](https://linux-hardware.org/?probe=7db1a321e8) | Apr 07, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [1c1830c301](https://linux-hardware.org/?probe=1c1830c301) | Apr 07, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [2dce0bfd4f](https://linux-hardware.org/?probe=2dce0bfd4f) | Apr 07, 2022 |
| Acer          | Aspire 5560                 | Notebook    | [0e302a5bc7](https://linux-hardware.org/?probe=0e302a5bc7) | Apr 07, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [0b8ce7d654](https://linux-hardware.org/?probe=0b8ce7d654) | Apr 07, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [0579a9b7d8](https://linux-hardware.org/?probe=0579a9b7d8) | Apr 07, 2022 |
| ASUSTek       | 1015B                       | Notebook    | [e271b0d0f3](https://linux-hardware.org/?probe=e271b0d0f3) | Apr 07, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [5d846383e8](https://linux-hardware.org/?probe=5d846383e8) | Apr 07, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [9e7f22efa7](https://linux-hardware.org/?probe=9e7f22efa7) | Apr 07, 2022 |
| Maibenben     | DaMai E series              | Notebook    | [3a37c71f1e](https://linux-hardware.org/?probe=3a37c71f1e) | Apr 07, 2022 |
| ECS           | IC55H-A                     | Desktop     | [932ee208e2](https://linux-hardware.org/?probe=932ee208e2) | Apr 07, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [49c1cb4d2b](https://linux-hardware.org/?probe=49c1cb4d2b) | Apr 07, 2022 |
| HP            | 550                         | Notebook    | [5b302acef8](https://linux-hardware.org/?probe=5b302acef8) | Apr 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [6e12ed717c](https://linux-hardware.org/?probe=6e12ed717c) | Apr 07, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [c049a4a3a5](https://linux-hardware.org/?probe=c049a4a3a5) | Apr 07, 2022 |
| HP            | ProBook 4520s               | Notebook    | [938de7402b](https://linux-hardware.org/?probe=938de7402b) | Apr 07, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2dc40369ce](https://linux-hardware.org/?probe=2dc40369ce) | Apr 07, 2022 |
| Samsung       | N150/N210/N220              | Notebook    | [d431ef7f66](https://linux-hardware.org/?probe=d431ef7f66) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [1097c7afa9](https://linux-hardware.org/?probe=1097c7afa9) | Apr 07, 2022 |
| Samsung       | R519/R719                   | Notebook    | [4bc0e89e19](https://linux-hardware.org/?probe=4bc0e89e19) | Apr 07, 2022 |
| Acer          | TravelMate 5620             | Notebook    | [fe6508476e](https://linux-hardware.org/?probe=fe6508476e) | Apr 07, 2022 |
| Lenovo        | ThinkPad W540 20BHS07808    | Notebook    | [3c88ca7afd](https://linux-hardware.org/?probe=3c88ca7afd) | Apr 07, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [3b8c5ecec8](https://linux-hardware.org/?probe=3b8c5ecec8) | Apr 07, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [b30a3c00f9](https://linux-hardware.org/?probe=b30a3c00f9) | Apr 07, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [1b6a57154d](https://linux-hardware.org/?probe=1b6a57154d) | Apr 07, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [632f031e00](https://linux-hardware.org/?probe=632f031e00) | Apr 07, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [92e741954d](https://linux-hardware.org/?probe=92e741954d) | Apr 07, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [db01c6669b](https://linux-hardware.org/?probe=db01c6669b) | Apr 07, 2022 |
| ASRock        | A520M Pro4                  | Desktop     | [28320f2e89](https://linux-hardware.org/?probe=28320f2e89) | Apr 07, 2022 |
| ASUSTek       | N551JB                      | Notebook    | [e1f0b15197](https://linux-hardware.org/?probe=e1f0b15197) | Apr 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b8b32cb958](https://linux-hardware.org/?probe=b8b32cb958) | Apr 07, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [ba0958caab](https://linux-hardware.org/?probe=ba0958caab) | Apr 07, 2022 |
| Acer          | AOD255                      | Notebook    | [20bbc537d6](https://linux-hardware.org/?probe=20bbc537d6) | Apr 07, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [311f56085c](https://linux-hardware.org/?probe=311f56085c) | Apr 07, 2022 |
| Acer          | Aspire 1830T                | Notebook    | [5517b27bee](https://linux-hardware.org/?probe=5517b27bee) | Apr 07, 2022 |
| Toshiba       | QOSMIO F60                  | Notebook    | [225135dedb](https://linux-hardware.org/?probe=225135dedb) | Apr 07, 2022 |
| ASRock        | A520M Pro4                  | Desktop     | [1eecc7b812](https://linux-hardware.org/?probe=1eecc7b812) | Apr 07, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b925472f54](https://linux-hardware.org/?probe=b925472f54) | Apr 07, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [f488ae3a24](https://linux-hardware.org/?probe=f488ae3a24) | Apr 07, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [aa5806bcd5](https://linux-hardware.org/?probe=aa5806bcd5) | Apr 07, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [3cb9a7fe16](https://linux-hardware.org/?probe=3cb9a7fe16) | Apr 07, 2022 |
| Lenovo        | V570c HuronRiver Platfor... | Notebook    | [b39c0569bb](https://linux-hardware.org/?probe=b39c0569bb) | Apr 07, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [9f6e1da5bd](https://linux-hardware.org/?probe=9f6e1da5bd) | Apr 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [ba5fa5ac1d](https://linux-hardware.org/?probe=ba5fa5ac1d) | Apr 07, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [91c32e3a92](https://linux-hardware.org/?probe=91c32e3a92) | Apr 07, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [ff329f98b5](https://linux-hardware.org/?probe=ff329f98b5) | Apr 07, 2022 |
| ASUSTek       | P5BV-C/4L                   | Desktop     | [b1eba1811a](https://linux-hardware.org/?probe=b1eba1811a) | Apr 07, 2022 |
| ASUSTek       | P5G41C-M                    | Desktop     | [438a8f1001](https://linux-hardware.org/?probe=438a8f1001) | Apr 07, 2022 |
| Dell          | Inspiron 5565               | Notebook    | [265b99f9a2](https://linux-hardware.org/?probe=265b99f9a2) | Apr 07, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [1724b1c64e](https://linux-hardware.org/?probe=1724b1c64e) | Apr 07, 2022 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [d61b85b58c](https://linux-hardware.org/?probe=d61b85b58c) | Apr 07, 2022 |
| Clevo         | M1110M                      | Notebook    | [6094ad097f](https://linux-hardware.org/?probe=6094ad097f) | Apr 07, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [682206ff84](https://linux-hardware.org/?probe=682206ff84) | Apr 07, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [8cf7fd2319](https://linux-hardware.org/?probe=8cf7fd2319) | Apr 07, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c5b2bc51dc](https://linux-hardware.org/?probe=c5b2bc51dc) | Apr 06, 2022 |
| Dell          | Latitude 7480               | Notebook    | [b088dbb113](https://linux-hardware.org/?probe=b088dbb113) | Apr 06, 2022 |
| MSI           | B360-A PRO                  | Desktop     | [9db9a23b5d](https://linux-hardware.org/?probe=9db9a23b5d) | Apr 06, 2022 |
| ASUSTek       | M51Vr                       | Notebook    | [8c372dbb91](https://linux-hardware.org/?probe=8c372dbb91) | Apr 06, 2022 |
| MSI           | Z87I GAMING AC              | Desktop     | [f9596aa625](https://linux-hardware.org/?probe=f9596aa625) | Apr 06, 2022 |
| MSI           | MS-N0E1 Ver                 | Notebook    | [95f1378c78](https://linux-hardware.org/?probe=95f1378c78) | Apr 06, 2022 |
| ASUSTek       | M51Vr                       | Notebook    | [c59285fd20](https://linux-hardware.org/?probe=c59285fd20) | Apr 06, 2022 |
| MSI           | G41M-P28                    | Desktop     | [b19249859b](https://linux-hardware.org/?probe=b19249859b) | Apr 06, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [f26f24743f](https://linux-hardware.org/?probe=f26f24743f) | Apr 06, 2022 |
| Supermicro    | X9DRW                       | Server      | [cbd2d7d7b8](https://linux-hardware.org/?probe=cbd2d7d7b8) | Apr 06, 2022 |
| Biostar       | H61MHV2                     | Desktop     | [c14aa9ce1a](https://linux-hardware.org/?probe=c14aa9ce1a) | Apr 06, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [679df55359](https://linux-hardware.org/?probe=679df55359) | Apr 06, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [3fd567de05](https://linux-hardware.org/?probe=3fd567de05) | Apr 06, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [2803fbf2ab](https://linux-hardware.org/?probe=2803fbf2ab) | Apr 06, 2022 |
| HP            | Pavilion g6                 | Notebook    | [24ebf3af72](https://linux-hardware.org/?probe=24ebf3af72) | Apr 06, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [91224772eb](https://linux-hardware.org/?probe=91224772eb) | Apr 06, 2022 |
| Unknown       | H510I                       | Desktop     | [ff0188e03f](https://linux-hardware.org/?probe=ff0188e03f) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [eff608a49e](https://linux-hardware.org/?probe=eff608a49e) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [a2cbf77c20](https://linux-hardware.org/?probe=a2cbf77c20) | Apr 06, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [0107774596](https://linux-hardware.org/?probe=0107774596) | Apr 06, 2022 |
| Samsung       | R19/R20/R21                 | Notebook    | [77b19cd7c5](https://linux-hardware.org/?probe=77b19cd7c5) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [281a36cc7d](https://linux-hardware.org/?probe=281a36cc7d) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [b498ef386c](https://linux-hardware.org/?probe=b498ef386c) | Apr 06, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [f25aa95e78](https://linux-hardware.org/?probe=f25aa95e78) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [5f0fbae656](https://linux-hardware.org/?probe=5f0fbae656) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [e543d9b013](https://linux-hardware.org/?probe=e543d9b013) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [0bfc08cf7d](https://linux-hardware.org/?probe=0bfc08cf7d) | Apr 06, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [6e2067ac48](https://linux-hardware.org/?probe=6e2067ac48) | Apr 06, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [7e10ceda79](https://linux-hardware.org/?probe=7e10ceda79) | Apr 06, 2022 |
| ASUSTek       | K8N-VM                      | Desktop     | [ec2a4f7170](https://linux-hardware.org/?probe=ec2a4f7170) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [9e22b32d6b](https://linux-hardware.org/?probe=9e22b32d6b) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [d11fa87811](https://linux-hardware.org/?probe=d11fa87811) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [01f4e56f26](https://linux-hardware.org/?probe=01f4e56f26) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [360473d244](https://linux-hardware.org/?probe=360473d244) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [7154fae7e4](https://linux-hardware.org/?probe=7154fae7e4) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [b5dcbdd4b0](https://linux-hardware.org/?probe=b5dcbdd4b0) | Apr 06, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [22e3c6f830](https://linux-hardware.org/?probe=22e3c6f830) | Apr 06, 2022 |
| SYWZ          | S200 Series                 | Desktop     | [8c4c52cd9b](https://linux-hardware.org/?probe=8c4c52cd9b) | Apr 06, 2022 |
| MSI           | CX61 0OC/CX61 0OD/CX61 0... | Notebook    | [4aaa2a3959](https://linux-hardware.org/?probe=4aaa2a3959) | Apr 06, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [39ab6f56fb](https://linux-hardware.org/?probe=39ab6f56fb) | Apr 06, 2022 |
| ASUSTek       | F5SL                        | Notebook    | [76272ce111](https://linux-hardware.org/?probe=76272ce111) | Apr 06, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [2ab4d273c1](https://linux-hardware.org/?probe=2ab4d273c1) | Apr 06, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [203b65a3f5](https://linux-hardware.org/?probe=203b65a3f5) | Apr 06, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [41f654dc20](https://linux-hardware.org/?probe=41f654dc20) | Apr 06, 2022 |
| Dell          | Vostro A860                 | Notebook    | [72c05fd9ee](https://linux-hardware.org/?probe=72c05fd9ee) | Apr 06, 2022 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [e5cdfad4e6](https://linux-hardware.org/?probe=e5cdfad4e6) | Apr 06, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [0cca11beab](https://linux-hardware.org/?probe=0cca11beab) | Apr 05, 2022 |
| Unknown       | RS690-SB600                 | Desktop     | [19ae42107e](https://linux-hardware.org/?probe=19ae42107e) | Apr 05, 2022 |
| ASUSTek       | 1011CX                      | Notebook    | [39035efe16](https://linux-hardware.org/?probe=39035efe16) | Apr 05, 2022 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [200d7fafb9](https://linux-hardware.org/?probe=200d7fafb9) | Apr 05, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [55622262b1](https://linux-hardware.org/?probe=55622262b1) | Apr 05, 2022 |
| Maibenben     | MaiBook M                   | Notebook    | [0c0daddfa1](https://linux-hardware.org/?probe=0c0daddfa1) | Apr 05, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [d6ef15453d](https://linux-hardware.org/?probe=d6ef15453d) | Apr 05, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1a090182c2](https://linux-hardware.org/?probe=1a090182c2) | Apr 05, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [68512f2b49](https://linux-hardware.org/?probe=68512f2b49) | Apr 05, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [011cc4e8f8](https://linux-hardware.org/?probe=011cc4e8f8) | Apr 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3403cf3b8a](https://linux-hardware.org/?probe=3403cf3b8a) | Apr 05, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [b642303f8e](https://linux-hardware.org/?probe=b642303f8e) | Apr 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [4c7231b52a](https://linux-hardware.org/?probe=4c7231b52a) | Apr 05, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [a3d0521e54](https://linux-hardware.org/?probe=a3d0521e54) | Apr 05, 2022 |
| MSI           | G41M-P33 Combo              | Desktop     | [2290edabe7](https://linux-hardware.org/?probe=2290edabe7) | Apr 05, 2022 |
| ASUSTek       | B560M-A PRIME               | Desktop     | [1aff04b3de](https://linux-hardware.org/?probe=1aff04b3de) | Apr 05, 2022 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [6c25d1250d](https://linux-hardware.org/?probe=6c25d1250d) | Apr 05, 2022 |
| ASUSTek       | K8N-VM                      | Desktop     | [d914bc84e9](https://linux-hardware.org/?probe=d914bc84e9) | Apr 05, 2022 |
| Supermicro    | X11DDW-NT                   | Server      | [a593b1b67e](https://linux-hardware.org/?probe=a593b1b67e) | Apr 05, 2022 |
| HP            | ENVY 17                     | Notebook    | [060904cd87](https://linux-hardware.org/?probe=060904cd87) | Apr 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [d57ec60736](https://linux-hardware.org/?probe=d57ec60736) | Apr 05, 2022 |
| Acer          | Aspire Z3730                | All in one  | [6fdf5d94d7](https://linux-hardware.org/?probe=6fdf5d94d7) | Apr 05, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ee0a7bc711](https://linux-hardware.org/?probe=ee0a7bc711) | Apr 05, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [1737ff348a](https://linux-hardware.org/?probe=1737ff348a) | Apr 05, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [be41efbec8](https://linux-hardware.org/?probe=be41efbec8) | Apr 05, 2022 |
| ONDA          | OBOOK 20 PLUS               | Notebook    | [1b39269806](https://linux-hardware.org/?probe=1b39269806) | Apr 05, 2022 |
| ONDA          | OBOOK 20 PLUS               | Notebook    | [279c2a3de8](https://linux-hardware.org/?probe=279c2a3de8) | Apr 05, 2022 |
| ASUSTek       | H87-PRO                     | Desktop     | [0d18744bdf](https://linux-hardware.org/?probe=0d18744bdf) | Apr 05, 2022 |
| ASUSTek       | P5Q SE PLUS                 | Desktop     | [bb16122030](https://linux-hardware.org/?probe=bb16122030) | Apr 05, 2022 |
| Acer          | Aspire 5734Z                | Notebook    | [12ff3844f5](https://linux-hardware.org/?probe=12ff3844f5) | Apr 05, 2022 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [cb0794850f](https://linux-hardware.org/?probe=cb0794850f) | Apr 05, 2022 |
| ASUSTek       | M3A78-EH                    | Desktop     | [4298b6c9dc](https://linux-hardware.org/?probe=4298b6c9dc) | Apr 05, 2022 |
| Packard Be... | EasyNote TJ71               | Notebook    | [9afad803e0](https://linux-hardware.org/?probe=9afad803e0) | Apr 05, 2022 |
| Dell          | Inspiron 5565               | Notebook    | [ec32d093d4](https://linux-hardware.org/?probe=ec32d093d4) | Apr 05, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [d7bf7b48a1](https://linux-hardware.org/?probe=d7bf7b48a1) | Apr 05, 2022 |
| HP            | Pavilion 15                 | Notebook    | [470ca0bc41](https://linux-hardware.org/?probe=470ca0bc41) | Apr 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [8f491b9fc2](https://linux-hardware.org/?probe=8f491b9fc2) | Apr 05, 2022 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [75da1802c3](https://linux-hardware.org/?probe=75da1802c3) | Apr 05, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [1c37d5b9ed](https://linux-hardware.org/?probe=1c37d5b9ed) | Apr 04, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [47ff657a18](https://linux-hardware.org/?probe=47ff657a18) | Apr 04, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [c474b8d1a2](https://linux-hardware.org/?probe=c474b8d1a2) | Apr 04, 2022 |
| ASUSTek       | H61M-D                      | Desktop     | [d22d7d52dc](https://linux-hardware.org/?probe=d22d7d52dc) | Apr 04, 2022 |
| ASRock        | G31M-VS2                    | Desktop     | [e618635f7e](https://linux-hardware.org/?probe=e618635f7e) | Apr 04, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [bc5ffea6a3](https://linux-hardware.org/?probe=bc5ffea6a3) | Apr 04, 2022 |
| Acer          | Aspire M1470                | Desktop     | [6612952747](https://linux-hardware.org/?probe=6612952747) | Apr 04, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [1167744ae0](https://linux-hardware.org/?probe=1167744ae0) | Apr 04, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [0134ef08d6](https://linux-hardware.org/?probe=0134ef08d6) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [02c8690b96](https://linux-hardware.org/?probe=02c8690b96) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [52cdca6be2](https://linux-hardware.org/?probe=52cdca6be2) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [04078826f9](https://linux-hardware.org/?probe=04078826f9) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [beff3d022a](https://linux-hardware.org/?probe=beff3d022a) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [b50bb2ee16](https://linux-hardware.org/?probe=b50bb2ee16) | Apr 04, 2022 |
| ASUSTek       | P8H67-M                     | Desktop     | [e49282700d](https://linux-hardware.org/?probe=e49282700d) | Apr 04, 2022 |
| ECS           | IC55H-A                     | Desktop     | [a0287a7cca](https://linux-hardware.org/?probe=a0287a7cca) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [b78fd6db36](https://linux-hardware.org/?probe=b78fd6db36) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [7482990555](https://linux-hardware.org/?probe=7482990555) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [8b9056398a](https://linux-hardware.org/?probe=8b9056398a) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [6243da846e](https://linux-hardware.org/?probe=6243da846e) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [42553daa02](https://linux-hardware.org/?probe=42553daa02) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [f8fa4a854a](https://linux-hardware.org/?probe=f8fa4a854a) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [5e53b0911d](https://linux-hardware.org/?probe=5e53b0911d) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [1029c094d5](https://linux-hardware.org/?probe=1029c094d5) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [fcc9bc2d30](https://linux-hardware.org/?probe=fcc9bc2d30) | Apr 04, 2022 |
| Acer          | Aspire M1470                | Desktop     | [d32d46984e](https://linux-hardware.org/?probe=d32d46984e) | Apr 04, 2022 |
| Gigabyte      | H67A-UD3H-B3                | Desktop     | [5ccef6f1fe](https://linux-hardware.org/?probe=5ccef6f1fe) | Apr 04, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [a88a724049](https://linux-hardware.org/?probe=a88a724049) | Apr 04, 2022 |
| Lenovo        | ThinkPad P51s 20HB000URT    | Notebook    | [0f3902ac09](https://linux-hardware.org/?probe=0f3902ac09) | Apr 04, 2022 |
| Dell          | Precision M6800             | Notebook    | [d3510b5479](https://linux-hardware.org/?probe=d3510b5479) | Apr 04, 2022 |
| ASUSTek       | P5B                         | Desktop     | [fd9454ab7a](https://linux-hardware.org/?probe=fd9454ab7a) | Apr 04, 2022 |
| Acer          | AO725                       | Notebook    | [2dbcfcbab4](https://linux-hardware.org/?probe=2dbcfcbab4) | Apr 04, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [864d69baab](https://linux-hardware.org/?probe=864d69baab) | Apr 04, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [7910aaf4cb](https://linux-hardware.org/?probe=7910aaf4cb) | Apr 04, 2022 |
| Acer          | Aspire A317-32              | Notebook    | [8980c8b316](https://linux-hardware.org/?probe=8980c8b316) | Apr 04, 2022 |
| MSI           | G41M-P28                    | Desktop     | [afb7898d63](https://linux-hardware.org/?probe=afb7898d63) | Apr 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [214ae5185b](https://linux-hardware.org/?probe=214ae5185b) | Apr 04, 2022 |
| HP            | ProBook 4535s               | Notebook    | [89adb58230](https://linux-hardware.org/?probe=89adb58230) | Apr 04, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [eae759532b](https://linux-hardware.org/?probe=eae759532b) | Apr 04, 2022 |
| MSI           | Sword 15 A11UE              | Notebook    | [dfc5aa7490](https://linux-hardware.org/?probe=dfc5aa7490) | Apr 04, 2022 |
| ASUSTek       | Maximus V EXTREME           | Desktop     | [01ef29c80a](https://linux-hardware.org/?probe=01ef29c80a) | Apr 04, 2022 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [99f04e1724](https://linux-hardware.org/?probe=99f04e1724) | Apr 04, 2022 |
| MSI           | B75A-G41                    | Desktop     | [80ec6aed14](https://linux-hardware.org/?probe=80ec6aed14) | Apr 04, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [2904ae2343](https://linux-hardware.org/?probe=2904ae2343) | Apr 03, 2022 |
| ASUSTek       | Maximus V EXTREME           | Desktop     | [6e91f5c899](https://linux-hardware.org/?probe=6e91f5c899) | Apr 03, 2022 |
| EPoX Compu... | NF550/570 DDR2: AF550/57... | Desktop     | [2ad5eecadc](https://linux-hardware.org/?probe=2ad5eecadc) | Apr 03, 2022 |
| ASUSTek       | A55BM-K                     | Desktop     | [c0832d15d0](https://linux-hardware.org/?probe=c0832d15d0) | Apr 03, 2022 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [ec65d243a5](https://linux-hardware.org/?probe=ec65d243a5) | Apr 03, 2022 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [c092681184](https://linux-hardware.org/?probe=c092681184) | Apr 03, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4368fb5c23](https://linux-hardware.org/?probe=4368fb5c23) | Apr 03, 2022 |
| Acer          | Aspire 7110                 | Notebook    | [eb141ad92d](https://linux-hardware.org/?probe=eb141ad92d) | Apr 03, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [60bc55e587](https://linux-hardware.org/?probe=60bc55e587) | Apr 03, 2022 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [e8ed38bd3d](https://linux-hardware.org/?probe=e8ed38bd3d) | Apr 03, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [2de94117ab](https://linux-hardware.org/?probe=2de94117ab) | Apr 03, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [68793d8d5a](https://linux-hardware.org/?probe=68793d8d5a) | Apr 03, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [d2abd78cfc](https://linux-hardware.org/?probe=d2abd78cfc) | Apr 03, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [03bf711ab6](https://linux-hardware.org/?probe=03bf711ab6) | Apr 03, 2022 |
| Gigabyte      | P41-ES3G                    | Desktop     | [3db559b0cb](https://linux-hardware.org/?probe=3db559b0cb) | Apr 03, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c6cb4c0d83](https://linux-hardware.org/?probe=c6cb4c0d83) | Apr 03, 2022 |
| Gigabyte      | P41-ES3G                    | Desktop     | [ba5297b664](https://linux-hardware.org/?probe=ba5297b664) | Apr 03, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [45f577da9e](https://linux-hardware.org/?probe=45f577da9e) | Apr 03, 2022 |
| Biostar       | B450MH                      | Desktop     | [13317b700c](https://linux-hardware.org/?probe=13317b700c) | Apr 03, 2022 |
| MSI           | B360M PRO-VDH               | Desktop     | [b2da2d7cc2](https://linux-hardware.org/?probe=b2da2d7cc2) | Apr 03, 2022 |
| Jumper        | EZpad                       | Notebook    | [4ebe3328db](https://linux-hardware.org/?probe=4ebe3328db) | Apr 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [bdb683ff40](https://linux-hardware.org/?probe=bdb683ff40) | Apr 03, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [b3dfc0ae31](https://linux-hardware.org/?probe=b3dfc0ae31) | Apr 02, 2022 |
| ASUSTek       | B75M-A                      | Desktop     | [06415c4f91](https://linux-hardware.org/?probe=06415c4f91) | Apr 02, 2022 |
| ASUSTek       | P5P41T-LE                   | Desktop     | [1ccfd166ec](https://linux-hardware.org/?probe=1ccfd166ec) | Apr 02, 2022 |
| Digma         | EVE 10 C301 ES1050EW        | Notebook    | [21b48c0c97](https://linux-hardware.org/?probe=21b48c0c97) | Apr 02, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [49aec76409](https://linux-hardware.org/?probe=49aec76409) | Apr 02, 2022 |
| MSI           | GX70 3CC                    | Notebook    | [0b706f83d3](https://linux-hardware.org/?probe=0b706f83d3) | Apr 02, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [736e44b59d](https://linux-hardware.org/?probe=736e44b59d) | Apr 02, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [273eefb222](https://linux-hardware.org/?probe=273eefb222) | Apr 02, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [9919bf1e95](https://linux-hardware.org/?probe=9919bf1e95) | Apr 02, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [2b0ff22151](https://linux-hardware.org/?probe=2b0ff22151) | Apr 02, 2022 |
| Intel         | D2500CC AAG81477-401        | Desktop     | [5beb419727](https://linux-hardware.org/?probe=5beb419727) | Apr 02, 2022 |
| eMachines     | E625                        | Notebook    | [d2e61292e0](https://linux-hardware.org/?probe=d2e61292e0) | Apr 02, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [4a26394306](https://linux-hardware.org/?probe=4a26394306) | Apr 02, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [77e2c60730](https://linux-hardware.org/?probe=77e2c60730) | Apr 02, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [c7cc0b8ae7](https://linux-hardware.org/?probe=c7cc0b8ae7) | Apr 02, 2022 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [9bc98bf38e](https://linux-hardware.org/?probe=9bc98bf38e) | Apr 02, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c3dcb61dd5](https://linux-hardware.org/?probe=c3dcb61dd5) | Apr 02, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [0a4247912e](https://linux-hardware.org/?probe=0a4247912e) | Apr 02, 2022 |
| Unknown       | Unknown                     | Notebook    | [110d7ffd9f](https://linux-hardware.org/?probe=110d7ffd9f) | Apr 02, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [73d3ef24bb](https://linux-hardware.org/?probe=73d3ef24bb) | Apr 02, 2022 |
| Sony          | VGN-P688E                   | Notebook    | [bd0b916fe7](https://linux-hardware.org/?probe=bd0b916fe7) | Apr 02, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [044dde3226](https://linux-hardware.org/?probe=044dde3226) | Apr 02, 2022 |
| MSI           | P55M-SD40                   | Desktop     | [3232f9fb77](https://linux-hardware.org/?probe=3232f9fb77) | Apr 02, 2022 |
| eMachines     | Unknown                     | Notebook    | [177156159a](https://linux-hardware.org/?probe=177156159a) | Apr 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [db66abcb6a](https://linux-hardware.org/?probe=db66abcb6a) | Apr 02, 2022 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [f5a5374d7f](https://linux-hardware.org/?probe=f5a5374d7f) | Apr 02, 2022 |
| ASUSTek       | 1005P                       | Notebook    | [df93928fb7](https://linux-hardware.org/?probe=df93928fb7) | Apr 02, 2022 |
| ASUSTek       | K40IJ                       | Notebook    | [f05cdebfd9](https://linux-hardware.org/?probe=f05cdebfd9) | Apr 02, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [8ed3394de0](https://linux-hardware.org/?probe=8ed3394de0) | Apr 02, 2022 |
| ASUSTek       | P7P55D                      | Desktop     | [626d7d9cf9](https://linux-hardware.org/?probe=626d7d9cf9) | Apr 02, 2022 |
| ECS           | G31T-M7                     | Desktop     | [c6f5fbd8ff](https://linux-hardware.org/?probe=c6f5fbd8ff) | Apr 02, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [cd49e5d099](https://linux-hardware.org/?probe=cd49e5d099) | Apr 02, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [80007d3994](https://linux-hardware.org/?probe=80007d3994) | Apr 02, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [ae5976d302](https://linux-hardware.org/?probe=ae5976d302) | Apr 01, 2022 |
| Supermicro    | X9DRW                       | Server      | [0ebc379f84](https://linux-hardware.org/?probe=0ebc379f84) | Apr 01, 2022 |
| ASUSTek       | N551ZU                      | Notebook    | [30a4ec4504](https://linux-hardware.org/?probe=30a4ec4504) | Apr 01, 2022 |
| HP            | Notebook                    | Notebook    | [81df1f83df](https://linux-hardware.org/?probe=81df1f83df) | Apr 01, 2022 |
| Dell          | Inspiron 1521               | Notebook    | [ddd74ed487](https://linux-hardware.org/?probe=ddd74ed487) | Apr 01, 2022 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [0b410c35cf](https://linux-hardware.org/?probe=0b410c35cf) | Apr 01, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [4246affe99](https://linux-hardware.org/?probe=4246affe99) | Apr 01, 2022 |
| HP            | Notebook                    | Notebook    | [dd28d6de9b](https://linux-hardware.org/?probe=dd28d6de9b) | Apr 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [fe5fe3040c](https://linux-hardware.org/?probe=fe5fe3040c) | Apr 01, 2022 |
| Gigabyte      | GA-A55M-S2HP                | Desktop     | [6655b05056](https://linux-hardware.org/?probe=6655b05056) | Apr 01, 2022 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [dfdb44695a](https://linux-hardware.org/?probe=dfdb44695a) | Apr 01, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [08db8019f3](https://linux-hardware.org/?probe=08db8019f3) | Apr 01, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [d648ac5ab2](https://linux-hardware.org/?probe=d648ac5ab2) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [7b4861c8af](https://linux-hardware.org/?probe=7b4861c8af) | Apr 01, 2022 |
| Supermicro    | X9DRW                       | Server      | [30644d34ca](https://linux-hardware.org/?probe=30644d34ca) | Apr 01, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [ce851fba8f](https://linux-hardware.org/?probe=ce851fba8f) | Apr 01, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [198fed544f](https://linux-hardware.org/?probe=198fed544f) | Apr 01, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [86b685b176](https://linux-hardware.org/?probe=86b685b176) | Apr 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [bd224d9eb3](https://linux-hardware.org/?probe=bd224d9eb3) | Apr 01, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [9d86d8119a](https://linux-hardware.org/?probe=9d86d8119a) | Apr 01, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [27836be76e](https://linux-hardware.org/?probe=27836be76e) | Apr 01, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | Notebook    | [0b475b4bac](https://linux-hardware.org/?probe=0b475b4bac) | Apr 01, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [ee8cf37d90](https://linux-hardware.org/?probe=ee8cf37d90) | Apr 01, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [0eb7c0d9b2](https://linux-hardware.org/?probe=0eb7c0d9b2) | Apr 01, 2022 |
| Gigabyte      | B460M D3H                   | Desktop     | [7c159eefd8](https://linux-hardware.org/?probe=7c159eefd8) | Apr 01, 2022 |
| ASUSTek       | K42F                        | Notebook    | [29766a27d6](https://linux-hardware.org/?probe=29766a27d6) | Apr 01, 2022 |
| ASRock        | H55M-LE                     | Desktop     | [6284bd7200](https://linux-hardware.org/?probe=6284bd7200) | Apr 01, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [7c61bf8ce7](https://linux-hardware.org/?probe=7c61bf8ce7) | Apr 01, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [7cba7f428a](https://linux-hardware.org/?probe=7cba7f428a) | Apr 01, 2022 |
| ASUSTek       | P5K                         | Desktop     | [544e656548](https://linux-hardware.org/?probe=544e656548) | Apr 01, 2022 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [0190cbbd27](https://linux-hardware.org/?probe=0190cbbd27) | Apr 01, 2022 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [4da992cdb7](https://linux-hardware.org/?probe=4da992cdb7) | Apr 01, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [477f340ef4](https://linux-hardware.org/?probe=477f340ef4) | Mar 31, 2022 |
| ASUSTek       | X55VD                       | Notebook    | [36e2e9943a](https://linux-hardware.org/?probe=36e2e9943a) | Mar 31, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [d8f7bd6e5d](https://linux-hardware.org/?probe=d8f7bd6e5d) | Mar 31, 2022 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [667310c4b8](https://linux-hardware.org/?probe=667310c4b8) | Mar 31, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [391a692100](https://linux-hardware.org/?probe=391a692100) | Mar 31, 2022 |
| MSI           | P67A-C45                    | Desktop     | [5ec0cd08a4](https://linux-hardware.org/?probe=5ec0cd08a4) | Mar 31, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [18f5f3d92a](https://linux-hardware.org/?probe=18f5f3d92a) | Mar 31, 2022 |
| Intel         | ChiefRiver                  | Notebook    | [619464014d](https://linux-hardware.org/?probe=619464014d) | Mar 31, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [e4059f2c1d](https://linux-hardware.org/?probe=e4059f2c1d) | Mar 31, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [fe17eb0fec](https://linux-hardware.org/?probe=fe17eb0fec) | Mar 31, 2022 |
| ASUSTek       | P8H61-M PRO                 | Desktop     | [a30091eb45](https://linux-hardware.org/?probe=a30091eb45) | Mar 31, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [96487ebeb0](https://linux-hardware.org/?probe=96487ebeb0) | Mar 31, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [efae9a6cb7](https://linux-hardware.org/?probe=efae9a6cb7) | Mar 31, 2022 |
| ASRock        | Z170 Pro4/D3                | Desktop     | [275edd1533](https://linux-hardware.org/?probe=275edd1533) | Mar 31, 2022 |
| MSI           | GT72 2QE                    | Notebook    | [ff49dc0593](https://linux-hardware.org/?probe=ff49dc0593) | Mar 31, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [9113320f2f](https://linux-hardware.org/?probe=9113320f2f) | Mar 31, 2022 |
| Gigabyte      | B360M H                     | Desktop     | [c6d64363b9](https://linux-hardware.org/?probe=c6d64363b9) | Mar 31, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f2dc785121](https://linux-hardware.org/?probe=f2dc785121) | Mar 31, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [fd66ebbeee](https://linux-hardware.org/?probe=fd66ebbeee) | Mar 31, 2022 |
| Dell          | Latitude E6430              | Notebook    | [a045dc014b](https://linux-hardware.org/?probe=a045dc014b) | Mar 31, 2022 |
| Lenovo        | ThinkPad T540p 20BEA00FR... | Notebook    | [c9323a9c40](https://linux-hardware.org/?probe=c9323a9c40) | Mar 31, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [97f38615e3](https://linux-hardware.org/?probe=97f38615e3) | Mar 31, 2022 |
| HP            | Pavilion g6                 | Notebook    | [a9a0826520](https://linux-hardware.org/?probe=a9a0826520) | Mar 31, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [8781d04da2](https://linux-hardware.org/?probe=8781d04da2) | Mar 31, 2022 |
| Gigabyte      | AX370-Gaming K3             | Desktop     | [63f7d865d3](https://linux-hardware.org/?probe=63f7d865d3) | Mar 31, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [1f74cc9211](https://linux-hardware.org/?probe=1f74cc9211) | Mar 31, 2022 |
| Lenovo        | E43                         | Notebook    | [356aa25045](https://linux-hardware.org/?probe=356aa25045) | Mar 30, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [790d42fec8](https://linux-hardware.org/?probe=790d42fec8) | Mar 30, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [d8166d09e9](https://linux-hardware.org/?probe=d8166d09e9) | Mar 30, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [e9508b7cce](https://linux-hardware.org/?probe=e9508b7cce) | Mar 30, 2022 |
| HP            | Pavilion dv6                | Notebook    | [b456c7a1a3](https://linux-hardware.org/?probe=b456c7a1a3) | Mar 30, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [9359d0549c](https://linux-hardware.org/?probe=9359d0549c) | Mar 30, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [d02cab0935](https://linux-hardware.org/?probe=d02cab0935) | Mar 30, 2022 |
| ASRock        | H61MV-ITX                   | Desktop     | [da935498ad](https://linux-hardware.org/?probe=da935498ad) | Mar 30, 2022 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [75a190fb7c](https://linux-hardware.org/?probe=75a190fb7c) | Mar 30, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [e299a5abe8](https://linux-hardware.org/?probe=e299a5abe8) | Mar 30, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [cefeb9762e](https://linux-hardware.org/?probe=cefeb9762e) | Mar 30, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [b8ff95c0f1](https://linux-hardware.org/?probe=b8ff95c0f1) | Mar 30, 2022 |
| ASUSTek       | M2N                         | Desktop     | [1d11c3c0f9](https://linux-hardware.org/?probe=1d11c3c0f9) | Mar 30, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [34c82e4845](https://linux-hardware.org/?probe=34c82e4845) | Mar 30, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [8167ee62f2](https://linux-hardware.org/?probe=8167ee62f2) | Mar 30, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [d783ed375d](https://linux-hardware.org/?probe=d783ed375d) | Mar 30, 2022 |
| HONOR         | NBD-WXX9                    | Notebook    | [dd51589f73](https://linux-hardware.org/?probe=dd51589f73) | Mar 30, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [03f276b46f](https://linux-hardware.org/?probe=03f276b46f) | Mar 30, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [4374d376e6](https://linux-hardware.org/?probe=4374d376e6) | Mar 30, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [0fa8cd8737](https://linux-hardware.org/?probe=0fa8cd8737) | Mar 30, 2022 |
| MSI           | Sword 15 A11UE              | Notebook    | [8c5b2e9648](https://linux-hardware.org/?probe=8c5b2e9648) | Mar 30, 2022 |
| Fujitsu Si... | AMILO Pi 2550               | Notebook    | [2ab7c6e8e9](https://linux-hardware.org/?probe=2ab7c6e8e9) | Mar 30, 2022 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [a30f5893f6](https://linux-hardware.org/?probe=a30f5893f6) | Mar 30, 2022 |
| eMachines     | E725                        | Notebook    | [b9538ae9f6](https://linux-hardware.org/?probe=b9538ae9f6) | Mar 30, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [a1f8e27996](https://linux-hardware.org/?probe=a1f8e27996) | Mar 30, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [759b8d297d](https://linux-hardware.org/?probe=759b8d297d) | Mar 30, 2022 |
| eMachines     | E725                        | Notebook    | [df552113fb](https://linux-hardware.org/?probe=df552113fb) | Mar 30, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5cdca2d9b2](https://linux-hardware.org/?probe=5cdca2d9b2) | Mar 30, 2022 |
| Toshiba       | Satellite Pro L300          | Notebook    | [ee5a484f5e](https://linux-hardware.org/?probe=ee5a484f5e) | Mar 30, 2022 |
| Samsung       | R519/R719                   | Notebook    | [2d46b53c07](https://linux-hardware.org/?probe=2d46b53c07) | Mar 29, 2022 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [a220b7b7cc](https://linux-hardware.org/?probe=a220b7b7cc) | Mar 29, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [c0d1cdbeaf](https://linux-hardware.org/?probe=c0d1cdbeaf) | Mar 29, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [1b4b237c62](https://linux-hardware.org/?probe=1b4b237c62) | Mar 29, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [a015b46fec](https://linux-hardware.org/?probe=a015b46fec) | Mar 29, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [c29c76ec93](https://linux-hardware.org/?probe=c29c76ec93) | Mar 29, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [c879b8be1c](https://linux-hardware.org/?probe=c879b8be1c) | Mar 29, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [8b6f847c8e](https://linux-hardware.org/?probe=8b6f847c8e) | Mar 29, 2022 |
| eMachines     | E725                        | Notebook    | [b248c29df3](https://linux-hardware.org/?probe=b248c29df3) | Mar 29, 2022 |
| MSI           | H81M-P33                    | Desktop     | [853b5b2236](https://linux-hardware.org/?probe=853b5b2236) | Mar 29, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [5c10e8ed7d](https://linux-hardware.org/?probe=5c10e8ed7d) | Mar 29, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [3c24d3510d](https://linux-hardware.org/?probe=3c24d3510d) | Mar 29, 2022 |
| Foxconn       | H61MXL-K                    | Desktop     | [50b743dab8](https://linux-hardware.org/?probe=50b743dab8) | Mar 29, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [ce8992d4dd](https://linux-hardware.org/?probe=ce8992d4dd) | Mar 29, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [16e1a01da4](https://linux-hardware.org/?probe=16e1a01da4) | Mar 29, 2022 |
| ASRock        | H470M-HDV                   | Desktop     | [19ee7b1fbc](https://linux-hardware.org/?probe=19ee7b1fbc) | Mar 29, 2022 |
| Dell          | Inspiron 3558               | Notebook    | [66daa065a8](https://linux-hardware.org/?probe=66daa065a8) | Mar 29, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [0ff3da859e](https://linux-hardware.org/?probe=0ff3da859e) | Mar 29, 2022 |
| Hampoo        | C1W6_AP123C_6GB Reserved    | Notebook    | [ff622b910d](https://linux-hardware.org/?probe=ff622b910d) | Mar 29, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [2812792752](https://linux-hardware.org/?probe=2812792752) | Mar 28, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [54f0933a0a](https://linux-hardware.org/?probe=54f0933a0a) | Mar 28, 2022 |
| ECS           | H67H2-M3                    | Desktop     | [d6abbba502](https://linux-hardware.org/?probe=d6abbba502) | Mar 28, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [6d4270f045](https://linux-hardware.org/?probe=6d4270f045) | Mar 28, 2022 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [c785b6b54b](https://linux-hardware.org/?probe=c785b6b54b) | Mar 28, 2022 |
| Dell          | 500                         | Notebook    | [885884468f](https://linux-hardware.org/?probe=885884468f) | Mar 28, 2022 |
| Dell          | Vostro 3590                 | Notebook    | [30c6e7abd0](https://linux-hardware.org/?probe=30c6e7abd0) | Mar 28, 2022 |
| Intel         | DP965LT AAD41694-206        | Desktop     | [b6f8d31fa5](https://linux-hardware.org/?probe=b6f8d31fa5) | Mar 28, 2022 |
| Intel         | D2500HN AAG34776-402        | Desktop     | [990923b5a7](https://linux-hardware.org/?probe=990923b5a7) | Mar 28, 2022 |
| Gigabyte      | H97M-HD3                    | Desktop     | [9027088a52](https://linux-hardware.org/?probe=9027088a52) | Mar 28, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [7fe672d3a9](https://linux-hardware.org/?probe=7fe672d3a9) | Mar 28, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [2b900adf8e](https://linux-hardware.org/?probe=2b900adf8e) | Mar 28, 2022 |
| HONOR         | HGE-WX6                     | Notebook    | [d59a8be353](https://linux-hardware.org/?probe=d59a8be353) | Mar 28, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [dbdd71e8b8](https://linux-hardware.org/?probe=dbdd71e8b8) | Mar 28, 2022 |
| ECS           | G41T-M7                     | Desktop     | [9bd8c1ef5a](https://linux-hardware.org/?probe=9bd8c1ef5a) | Mar 28, 2022 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [8d596570ed](https://linux-hardware.org/?probe=8d596570ed) | Mar 28, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [6741a3f9dc](https://linux-hardware.org/?probe=6741a3f9dc) | Mar 28, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [4cfedd9c7a](https://linux-hardware.org/?probe=4cfedd9c7a) | Mar 28, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [59daa69177](https://linux-hardware.org/?probe=59daa69177) | Mar 28, 2022 |
| Lenovo        | H420                        | Desktop     | [3da1375d85](https://linux-hardware.org/?probe=3da1375d85) | Mar 28, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c2ae1d8052](https://linux-hardware.org/?probe=c2ae1d8052) | Mar 28, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [cc14ce52f7](https://linux-hardware.org/?probe=cc14ce52f7) | Mar 28, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [45513b120d](https://linux-hardware.org/?probe=45513b120d) | Mar 28, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [915761391f](https://linux-hardware.org/?probe=915761391f) | Mar 28, 2022 |
| ASUSTek       | P8H61-M PRO                 | Desktop     | [870dc37754](https://linux-hardware.org/?probe=870dc37754) | Mar 28, 2022 |
| Acer          | Aspire 5560                 | Notebook    | [6c3b8c6e6c](https://linux-hardware.org/?probe=6c3b8c6e6c) | Mar 28, 2022 |
| ASRock        | AB350M-HDV R3.0             | Desktop     | [7024cc263a](https://linux-hardware.org/?probe=7024cc263a) | Mar 28, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [c9368e5a4a](https://linux-hardware.org/?probe=c9368e5a4a) | Mar 28, 2022 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [11d32dddf9](https://linux-hardware.org/?probe=11d32dddf9) | Mar 28, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [7829bdde58](https://linux-hardware.org/?probe=7829bdde58) | Mar 28, 2022 |
| ECS           | G41T-M7                     | Desktop     | [cdeda3b238](https://linux-hardware.org/?probe=cdeda3b238) | Mar 27, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [6fffff17df](https://linux-hardware.org/?probe=6fffff17df) | Mar 27, 2022 |
| HONOR         | NMH-WCX9                    | Notebook    | [b8f4b2750d](https://linux-hardware.org/?probe=b8f4b2750d) | Mar 27, 2022 |
| Acer          | Aspire Z3101                | All in one  | [180a248108](https://linux-hardware.org/?probe=180a248108) | Mar 27, 2022 |
| ASRock        | A785GXH/128M                | Desktop     | [e644d9e545](https://linux-hardware.org/?probe=e644d9e545) | Mar 27, 2022 |
| MSI           | 970A-G46                    | Desktop     | [c1543a34cf](https://linux-hardware.org/?probe=c1543a34cf) | Mar 27, 2022 |
| ASRock        | B250 Pro4                   | Desktop     | [052897615f](https://linux-hardware.org/?probe=052897615f) | Mar 27, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [a9ce7cfa0b](https://linux-hardware.org/?probe=a9ce7cfa0b) | Mar 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [b2884ac582](https://linux-hardware.org/?probe=b2884ac582) | Mar 27, 2022 |
| ASUSTek       | K52F                        | Notebook    | [37baf143fa](https://linux-hardware.org/?probe=37baf143fa) | Mar 27, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [1727b6bd44](https://linux-hardware.org/?probe=1727b6bd44) | Mar 27, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [7a70776029](https://linux-hardware.org/?probe=7a70776029) | Mar 27, 2022 |
| HP            | 09F8h                       | Desktop     | [dbfc9b9f29](https://linux-hardware.org/?probe=dbfc9b9f29) | Mar 27, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [a79e7dc9c5](https://linux-hardware.org/?probe=a79e7dc9c5) | Mar 27, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [450dae5049](https://linux-hardware.org/?probe=450dae5049) | Mar 27, 2022 |
| ASUSTek       | N56VJ                       | Notebook    | [e5a80caf47](https://linux-hardware.org/?probe=e5a80caf47) | Mar 27, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [6ca9c192ee](https://linux-hardware.org/?probe=6ca9c192ee) | Mar 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [0a94255553](https://linux-hardware.org/?probe=0a94255553) | Mar 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [4d4d8a247d](https://linux-hardware.org/?probe=4d4d8a247d) | Mar 27, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e7211c8a24](https://linux-hardware.org/?probe=e7211c8a24) | Mar 27, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [c5dac7978e](https://linux-hardware.org/?probe=c5dac7978e) | Mar 27, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [bbb38ea950](https://linux-hardware.org/?probe=bbb38ea950) | Mar 27, 2022 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [ab14b95970](https://linux-hardware.org/?probe=ab14b95970) | Mar 27, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ddd1434a1d](https://linux-hardware.org/?probe=ddd1434a1d) | Mar 27, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [2e240346e4](https://linux-hardware.org/?probe=2e240346e4) | Mar 27, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [b055956ef9](https://linux-hardware.org/?probe=b055956ef9) | Mar 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [1aef88fee8](https://linux-hardware.org/?probe=1aef88fee8) | Mar 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a8f5aed110](https://linux-hardware.org/?probe=a8f5aed110) | Mar 27, 2022 |
| Gigabyte      | GA-E6010N                   | Desktop     | [92e299d57a](https://linux-hardware.org/?probe=92e299d57a) | Mar 27, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [9e095340f3](https://linux-hardware.org/?probe=9e095340f3) | Mar 27, 2022 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [f4e7cba010](https://linux-hardware.org/?probe=f4e7cba010) | Mar 27, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [5b484e3ef3](https://linux-hardware.org/?probe=5b484e3ef3) | Mar 26, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [0cfc174313](https://linux-hardware.org/?probe=0cfc174313) | Mar 26, 2022 |
| Acer          | Aspire C24-320              | All in one  | [34813dfad2](https://linux-hardware.org/?probe=34813dfad2) | Mar 26, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [792fcd62f8](https://linux-hardware.org/?probe=792fcd62f8) | Mar 26, 2022 |
| Gigabyte      | P41T-D3P                    | Desktop     | [3952f72348](https://linux-hardware.org/?probe=3952f72348) | Mar 26, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [b47822d246](https://linux-hardware.org/?probe=b47822d246) | Mar 26, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [65bf9736b3](https://linux-hardware.org/?probe=65bf9736b3) | Mar 26, 2022 |
| Haier         | U144S                       | Notebook    | [9a4827b852](https://linux-hardware.org/?probe=9a4827b852) | Mar 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [01a39ed63c](https://linux-hardware.org/?probe=01a39ed63c) | Mar 26, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [0e02af9ab7](https://linux-hardware.org/?probe=0e02af9ab7) | Mar 26, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [80db7a4eb7](https://linux-hardware.org/?probe=80db7a4eb7) | Mar 26, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [be693ce006](https://linux-hardware.org/?probe=be693ce006) | Mar 26, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [1aa66a62c4](https://linux-hardware.org/?probe=1aa66a62c4) | Mar 26, 2022 |
| ASUSTek       | K54C                        | Notebook    | [07db23bedc](https://linux-hardware.org/?probe=07db23bedc) | Mar 26, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [e37db9015b](https://linux-hardware.org/?probe=e37db9015b) | Mar 26, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [733309bfe7](https://linux-hardware.org/?probe=733309bfe7) | Mar 26, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [5baa3973a9](https://linux-hardware.org/?probe=5baa3973a9) | Mar 26, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [a1b46c124a](https://linux-hardware.org/?probe=a1b46c124a) | Mar 26, 2022 |
| ECS           | G31T-M7                     | Desktop     | [6ae60fc846](https://linux-hardware.org/?probe=6ae60fc846) | Mar 26, 2022 |
| Gigabyte      | EP31-DS3L                   | Desktop     | [349383626b](https://linux-hardware.org/?probe=349383626b) | Mar 26, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [819be626ab](https://linux-hardware.org/?probe=819be626ab) | Mar 26, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [10b27986c9](https://linux-hardware.org/?probe=10b27986c9) | Mar 26, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6690115e22](https://linux-hardware.org/?probe=6690115e22) | Mar 25, 2022 |
| MSI           | H61M-P31                    | Desktop     | [0b50659b44](https://linux-hardware.org/?probe=0b50659b44) | Mar 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [4fb374e78b](https://linux-hardware.org/?probe=4fb374e78b) | Mar 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | Notebook    | [fa8d5965d7](https://linux-hardware.org/?probe=fa8d5965d7) | Mar 25, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [419c6047da](https://linux-hardware.org/?probe=419c6047da) | Mar 25, 2022 |
| ASUSTek       | F2A55-M LE                  | Desktop     | [e027562517](https://linux-hardware.org/?probe=e027562517) | Mar 25, 2022 |
| Infomash      | MS-163A                     | Notebook    | [90c92e916b](https://linux-hardware.org/?probe=90c92e916b) | Mar 25, 2022 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [9fb63e991c](https://linux-hardware.org/?probe=9fb63e991c) | Mar 25, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [a955ba8b71](https://linux-hardware.org/?probe=a955ba8b71) | Mar 25, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [77f39ed5ef](https://linux-hardware.org/?probe=77f39ed5ef) | Mar 25, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [1d0229f697](https://linux-hardware.org/?probe=1d0229f697) | Mar 25, 2022 |
| Dell          | Inspiron 3558               | Notebook    | [b7b20fc2d5](https://linux-hardware.org/?probe=b7b20fc2d5) | Mar 25, 2022 |
| Haier         | U1520EM                     | Notebook    | [5fde1c39e9](https://linux-hardware.org/?probe=5fde1c39e9) | Mar 25, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [00e8da8c29](https://linux-hardware.org/?probe=00e8da8c29) | Mar 25, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [811ccad24d](https://linux-hardware.org/?probe=811ccad24d) | Mar 25, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [40ec2200ee](https://linux-hardware.org/?probe=40ec2200ee) | Mar 25, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [cb639d5f0a](https://linux-hardware.org/?probe=cb639d5f0a) | Mar 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [1381f81018](https://linux-hardware.org/?probe=1381f81018) | Mar 25, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [f758ccfcbe](https://linux-hardware.org/?probe=f758ccfcbe) | Mar 25, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [3ff575d2e1](https://linux-hardware.org/?probe=3ff575d2e1) | Mar 25, 2022 |
| Acer          | Extensa 2540                | Notebook    | [15f6f446ee](https://linux-hardware.org/?probe=15f6f446ee) | Mar 25, 2022 |
| Unknown       | YL-J1900-V1                 | Desktop     | [835f68900c](https://linux-hardware.org/?probe=835f68900c) | Mar 25, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [d60719a932](https://linux-hardware.org/?probe=d60719a932) | Mar 25, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [36f716cd9b](https://linux-hardware.org/?probe=36f716cd9b) | Mar 25, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [1a9b30af2a](https://linux-hardware.org/?probe=1a9b30af2a) | Mar 25, 2022 |
| Infomash      | MS-163A                     | Notebook    | [d620350f18](https://linux-hardware.org/?probe=d620350f18) | Mar 25, 2022 |
| Supermicro    | X11SSH-F                    | Server      | [a50c6c203e](https://linux-hardware.org/?probe=a50c6c203e) | Mar 25, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [2a059657b4](https://linux-hardware.org/?probe=2a059657b4) | Mar 24, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [a2db3c2cab](https://linux-hardware.org/?probe=a2db3c2cab) | Mar 24, 2022 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [4f717acbaa](https://linux-hardware.org/?probe=4f717acbaa) | Mar 24, 2022 |
| Acer          | Aspire C22-760              | All in one  | [212ddc6fe7](https://linux-hardware.org/?probe=212ddc6fe7) | Mar 24, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [150e438d6e](https://linux-hardware.org/?probe=150e438d6e) | Mar 24, 2022 |
| ASUSTek       | K53U                        | Notebook    | [71a6293088](https://linux-hardware.org/?probe=71a6293088) | Mar 24, 2022 |
| Intel         | B75                         | Desktop     | [e536726a62](https://linux-hardware.org/?probe=e536726a62) | Mar 24, 2022 |
| Irbis         | NB656                       | Notebook    | [b151b2e16e](https://linux-hardware.org/?probe=b151b2e16e) | Mar 24, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [f1b11a1c3a](https://linux-hardware.org/?probe=f1b11a1c3a) | Mar 24, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [b4c23c72de](https://linux-hardware.org/?probe=b4c23c72de) | Mar 24, 2022 |
| ASUSTek       | K53SM                       | Notebook    | [4e1401bc98](https://linux-hardware.org/?probe=4e1401bc98) | Mar 24, 2022 |
| Biostar       | H81MHV3                     | Desktop     | [66b47eae5d](https://linux-hardware.org/?probe=66b47eae5d) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [95628eab40](https://linux-hardware.org/?probe=95628eab40) | Mar 24, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [29ede999bb](https://linux-hardware.org/?probe=29ede999bb) | Mar 24, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c10b664e4e](https://linux-hardware.org/?probe=c10b664e4e) | Mar 24, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [3d513e3c6c](https://linux-hardware.org/?probe=3d513e3c6c) | Mar 24, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [9590cc2288](https://linux-hardware.org/?probe=9590cc2288) | Mar 24, 2022 |
| Acer          | Aspire C24-320              | All in one  | [a41d66f593](https://linux-hardware.org/?probe=a41d66f593) | Mar 24, 2022 |
| ASUSTek       | P5Q SE                      | Desktop     | [926ae629bd](https://linux-hardware.org/?probe=926ae629bd) | Mar 24, 2022 |
| Sony          | VPCF13E1R                   | Notebook    | [361546db94](https://linux-hardware.org/?probe=361546db94) | Mar 24, 2022 |
| MSI           | Z270-A PRO                  | Desktop     | [d9e98611b8](https://linux-hardware.org/?probe=d9e98611b8) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [ebd44c18a4](https://linux-hardware.org/?probe=ebd44c18a4) | Mar 23, 2022 |
| ASRock        | H510M-HVS                   | Desktop     | [f47c9449b9](https://linux-hardware.org/?probe=f47c9449b9) | Mar 23, 2022 |
| Acer          | TravelMate B118-M           | Notebook    | [30b2718a46](https://linux-hardware.org/?probe=30b2718a46) | Mar 23, 2022 |
| MSI           | Z270-A PRO                  | Desktop     | [e0fefdb7c8](https://linux-hardware.org/?probe=e0fefdb7c8) | Mar 23, 2022 |
| Dell          | G3 3590                     | Notebook    | [2181ac62a9](https://linux-hardware.org/?probe=2181ac62a9) | Mar 23, 2022 |
| ASUSTek       | UX310UQ                     | Notebook    | [275534757b](https://linux-hardware.org/?probe=275534757b) | Mar 23, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [4bef3efcae](https://linux-hardware.org/?probe=4bef3efcae) | Mar 23, 2022 |
| Dell          | G3 3590                     | Notebook    | [8081671504](https://linux-hardware.org/?probe=8081671504) | Mar 23, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [8f801104d1](https://linux-hardware.org/?probe=8f801104d1) | Mar 23, 2022 |
| ASUSTek       | K84L                        | Notebook    | [4c12e53ed1](https://linux-hardware.org/?probe=4c12e53ed1) | Mar 23, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [61a3132b66](https://linux-hardware.org/?probe=61a3132b66) | Mar 23, 2022 |
| ASRock        | N68-VS3 FX                  | Desktop     | [c675421a82](https://linux-hardware.org/?probe=c675421a82) | Mar 23, 2022 |
| Sony          | SVE1711G1RB                 | Notebook    | [f6c732711b](https://linux-hardware.org/?probe=f6c732711b) | Mar 23, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [66d2a3d28a](https://linux-hardware.org/?probe=66d2a3d28a) | Mar 23, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [cc1efbead4](https://linux-hardware.org/?probe=cc1efbead4) | Mar 23, 2022 |
| Lenovo        | ThinkPad L450 20DT0013RT    | Notebook    | [3feee1f95c](https://linux-hardware.org/?probe=3feee1f95c) | Mar 23, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [42e6c66cbd](https://linux-hardware.org/?probe=42e6c66cbd) | Mar 23, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [57c001c06e](https://linux-hardware.org/?probe=57c001c06e) | Mar 23, 2022 |
| ASUSTek       | M5A97                       | Desktop     | [ea157e214f](https://linux-hardware.org/?probe=ea157e214f) | Mar 23, 2022 |
| Dell          | Studio 1558                 | Notebook    | [7004b83ddf](https://linux-hardware.org/?probe=7004b83ddf) | Mar 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [e0dc423b2a](https://linux-hardware.org/?probe=e0dc423b2a) | Mar 23, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ae49c43f44](https://linux-hardware.org/?probe=ae49c43f44) | Mar 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0ac448a13f](https://linux-hardware.org/?probe=0ac448a13f) | Mar 23, 2022 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [d9fc74e94c](https://linux-hardware.org/?probe=d9fc74e94c) | Mar 23, 2022 |
| Lenovo        | 3000 G430 4153/200          | Notebook    | [19a8b8118b](https://linux-hardware.org/?probe=19a8b8118b) | Mar 23, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [6ae3b7ae99](https://linux-hardware.org/?probe=6ae3b7ae99) | Mar 23, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [e76e5359b7](https://linux-hardware.org/?probe=e76e5359b7) | Mar 23, 2022 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [a2055267ff](https://linux-hardware.org/?probe=a2055267ff) | Mar 23, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [1564427e82](https://linux-hardware.org/?probe=1564427e82) | Mar 23, 2022 |
| Unknown       | YL-J1900-V1                 | Desktop     | [add4b942ef](https://linux-hardware.org/?probe=add4b942ef) | Mar 23, 2022 |
| MSI           | H61M-P21                    | Desktop     | [99db7fcf53](https://linux-hardware.org/?probe=99db7fcf53) | Mar 23, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [305ac1dddd](https://linux-hardware.org/?probe=305ac1dddd) | Mar 23, 2022 |
| ASUSTek       | M2N-MX                      | Desktop     | [6d2cb7a6f5](https://linux-hardware.org/?probe=6d2cb7a6f5) | Mar 22, 2022 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [3625536523](https://linux-hardware.org/?probe=3625536523) | Mar 22, 2022 |
| Gigabyte      | P55-UD3L                    | Desktop     | [ee3e9ec967](https://linux-hardware.org/?probe=ee3e9ec967) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | Notebook    | [247859eb78](https://linux-hardware.org/?probe=247859eb78) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | Notebook    | [b9e82b8490](https://linux-hardware.org/?probe=b9e82b8490) | Mar 22, 2022 |
| ASRock        | Z370 Extreme4               | Desktop     | [f39b16204a](https://linux-hardware.org/?probe=f39b16204a) | Mar 22, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [1b06197c8b](https://linux-hardware.org/?probe=1b06197c8b) | Mar 22, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [56f9ebba91](https://linux-hardware.org/?probe=56f9ebba91) | Mar 22, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [59daba0b8a](https://linux-hardware.org/?probe=59daba0b8a) | Mar 22, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [6788522a8a](https://linux-hardware.org/?probe=6788522a8a) | Mar 22, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [fbf5a85733](https://linux-hardware.org/?probe=fbf5a85733) | Mar 22, 2022 |
| Aquarius      | NS585                       | Notebook    | [2cc901ad54](https://linux-hardware.org/?probe=2cc901ad54) | Mar 22, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [91d5c07184](https://linux-hardware.org/?probe=91d5c07184) | Mar 22, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [22983e54a4](https://linux-hardware.org/?probe=22983e54a4) | Mar 22, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [0a9892ebf9](https://linux-hardware.org/?probe=0a9892ebf9) | Mar 22, 2022 |
| HP            | 859C                        | Desktop     | [4c598fdb6d](https://linux-hardware.org/?probe=4c598fdb6d) | Mar 22, 2022 |
| Unknown       | YL-J1900-V1                 | Desktop     | [396ac36ac2](https://linux-hardware.org/?probe=396ac36ac2) | Mar 22, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [1462cd20b7](https://linux-hardware.org/?probe=1462cd20b7) | Mar 22, 2022 |
| ASUSTek       | P5K                         | Desktop     | [da0019c5d0](https://linux-hardware.org/?probe=da0019c5d0) | Mar 22, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [4346995b24](https://linux-hardware.org/?probe=4346995b24) | Mar 22, 2022 |
| MSI           | MS-7250                     | Desktop     | [c115855cc4](https://linux-hardware.org/?probe=c115855cc4) | Mar 22, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [7662478d56](https://linux-hardware.org/?probe=7662478d56) | Mar 22, 2022 |
| Lenovo        | B5400 20278                 | Notebook    | [ef29445841](https://linux-hardware.org/?probe=ef29445841) | Mar 22, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [416808d28d](https://linux-hardware.org/?probe=416808d28d) | Mar 22, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [8d1459408f](https://linux-hardware.org/?probe=8d1459408f) | Mar 22, 2022 |
| Acer          | Iconia W700                 | Notebook    | [e4ed6bd52d](https://linux-hardware.org/?probe=e4ed6bd52d) | Mar 22, 2022 |
| ASUSTek       | K40AD                       | Notebook    | [fb42294eb8](https://linux-hardware.org/?probe=fb42294eb8) | Mar 21, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [069849c461](https://linux-hardware.org/?probe=069849c461) | Mar 21, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [6f9fd785de](https://linux-hardware.org/?probe=6f9fd785de) | Mar 21, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [6cd511ea30](https://linux-hardware.org/?probe=6cd511ea30) | Mar 21, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [273b204272](https://linux-hardware.org/?probe=273b204272) | Mar 21, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [9c0d4c37d8](https://linux-hardware.org/?probe=9c0d4c37d8) | Mar 21, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [e18b80073c](https://linux-hardware.org/?probe=e18b80073c) | Mar 21, 2022 |
| Samsung       | 530U4E/540U4E               | Notebook    | [2a013dea90](https://linux-hardware.org/?probe=2a013dea90) | Mar 21, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [c795f0ba68](https://linux-hardware.org/?probe=c795f0ba68) | Mar 21, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [a9acd08c72](https://linux-hardware.org/?probe=a9acd08c72) | Mar 21, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [d8f482f916](https://linux-hardware.org/?probe=d8f482f916) | Mar 21, 2022 |
| Acer          | Aspire ES1-521              | Notebook    | [7c8de8440e](https://linux-hardware.org/?probe=7c8de8440e) | Mar 21, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [80ef8b623c](https://linux-hardware.org/?probe=80ef8b623c) | Mar 21, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [b379b1157c](https://linux-hardware.org/?probe=b379b1157c) | Mar 21, 2022 |
| Aquarius      | NS585                       | Notebook    | [c0f64e7b67](https://linux-hardware.org/?probe=c0f64e7b67) | Mar 21, 2022 |
| Aquarius      | NS585                       | Notebook    | [2bd62b79af](https://linux-hardware.org/?probe=2bd62b79af) | Mar 21, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [26545ed686](https://linux-hardware.org/?probe=26545ed686) | Mar 21, 2022 |
| Aquarius      | NS585                       | Notebook    | [77fe07b69f](https://linux-hardware.org/?probe=77fe07b69f) | Mar 21, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [0b69dcafad](https://linux-hardware.org/?probe=0b69dcafad) | Mar 21, 2022 |
| IBM           | 94Y7718 SIT                 | Server      | [9c5faf3552](https://linux-hardware.org/?probe=9c5faf3552) | Mar 21, 2022 |
| Samsung       | 530U4E/540U4E               | Notebook    | [95b1b45b99](https://linux-hardware.org/?probe=95b1b45b99) | Mar 21, 2022 |
| Lenovo        | 3111 NOK                    | Mini pc     | [fe298dc766](https://linux-hardware.org/?probe=fe298dc766) | Mar 21, 2022 |
| Lenovo        | ThinkPad P51s 20HB000URT    | Notebook    | [595bf8f0af](https://linux-hardware.org/?probe=595bf8f0af) | Mar 21, 2022 |
| Lenovo        | ThinkPad X220 4291G26       | Notebook    | [c2f45496d1](https://linux-hardware.org/?probe=c2f45496d1) | Mar 21, 2022 |
| MSI           | Sword 15 A11UE              | Notebook    | [c9d9ef0d26](https://linux-hardware.org/?probe=c9d9ef0d26) | Mar 21, 2022 |
| ASUSTek       | B150 PRO GAMING             | Desktop     | [fce8e3cc98](https://linux-hardware.org/?probe=fce8e3cc98) | Mar 21, 2022 |
| HP            | Pavilion 17                 | Notebook    | [d09f6d15a2](https://linux-hardware.org/?probe=d09f6d15a2) | Mar 21, 2022 |
| ASUSTek       | X542UA                      | Notebook    | [37f9251b2d](https://linux-hardware.org/?probe=37f9251b2d) | Mar 20, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [dad19ddec6](https://linux-hardware.org/?probe=dad19ddec6) | Mar 20, 2022 |
| ASRock        | G41C-GS                     | Desktop     | [baab4934ee](https://linux-hardware.org/?probe=baab4934ee) | Mar 20, 2022 |
| eMachines     | E525                        | Notebook    | [269a5e5794](https://linux-hardware.org/?probe=269a5e5794) | Mar 20, 2022 |
| Pegatron      | A15                         | Notebook    | [624909f9a0](https://linux-hardware.org/?probe=624909f9a0) | Mar 20, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f8f92ef73d](https://linux-hardware.org/?probe=f8f92ef73d) | Mar 20, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [d9a23e9bfb](https://linux-hardware.org/?probe=d9a23e9bfb) | Mar 20, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [b632c4a0c5](https://linux-hardware.org/?probe=b632c4a0c5) | Mar 20, 2022 |
| HP            | Pavilion 15                 | Notebook    | [dc84500611](https://linux-hardware.org/?probe=dc84500611) | Mar 20, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [d54a831153](https://linux-hardware.org/?probe=d54a831153) | Mar 20, 2022 |
| Intel         | B75                         | Desktop     | [242c4cde30](https://linux-hardware.org/?probe=242c4cde30) | Mar 20, 2022 |
| HP            | Notebook                    | Notebook    | [e15e8a7e88](https://linux-hardware.org/?probe=e15e8a7e88) | Mar 20, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [739ed6ff81](https://linux-hardware.org/?probe=739ed6ff81) | Mar 20, 2022 |
| Lenovo        | V570c HuronRiver Platfor... | Notebook    | [bcbde01649](https://linux-hardware.org/?probe=bcbde01649) | Mar 20, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [eed3c9f6e5](https://linux-hardware.org/?probe=eed3c9f6e5) | Mar 20, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [7247904393](https://linux-hardware.org/?probe=7247904393) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [a9ac1b42ff](https://linux-hardware.org/?probe=a9ac1b42ff) | Mar 20, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [15e53dcce2](https://linux-hardware.org/?probe=15e53dcce2) | Mar 20, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [bee5c791e6](https://linux-hardware.org/?probe=bee5c791e6) | Mar 20, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [daa5dd8024](https://linux-hardware.org/?probe=daa5dd8024) | Mar 20, 2022 |
| Prestigio     | PSB133S01ZFH                | Notebook    | [c1e54c7eab](https://linux-hardware.org/?probe=c1e54c7eab) | Mar 20, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [e6e5a08814](https://linux-hardware.org/?probe=e6e5a08814) | Mar 20, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8847624b97](https://linux-hardware.org/?probe=8847624b97) | Mar 20, 2022 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [5b7201b789](https://linux-hardware.org/?probe=5b7201b789) | Mar 20, 2022 |
| ASRock        | B560 Steel Legend           | Desktop     | [29e1abc7b1](https://linux-hardware.org/?probe=29e1abc7b1) | Mar 20, 2022 |
| Foxconn       | H67M-S/H67M-V/H67M          | Desktop     | [ced87dc2b5](https://linux-hardware.org/?probe=ced87dc2b5) | Mar 20, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [a6674cd472](https://linux-hardware.org/?probe=a6674cd472) | Mar 20, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [bb400c5756](https://linux-hardware.org/?probe=bb400c5756) | Mar 20, 2022 |
| Lenovo        | B50-45 20388                | Notebook    | [ca3ab5bf1d](https://linux-hardware.org/?probe=ca3ab5bf1d) | Mar 20, 2022 |
| Lenovo        | B50-45 20388                | Notebook    | [5269284471](https://linux-hardware.org/?probe=5269284471) | Mar 20, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [7f0fe8a60c](https://linux-hardware.org/?probe=7f0fe8a60c) | Mar 20, 2022 |
| Dell          | XPS 12-9Q33                 | Notebook    | [f4829632f8](https://linux-hardware.org/?probe=f4829632f8) | Mar 20, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [779e8733bd](https://linux-hardware.org/?probe=779e8733bd) | Mar 20, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [8740fa2680](https://linux-hardware.org/?probe=8740fa2680) | Mar 20, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [2fd6e0b6e8](https://linux-hardware.org/?probe=2fd6e0b6e8) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [ba50ffd3f8](https://linux-hardware.org/?probe=ba50ffd3f8) | Mar 20, 2022 |
| ASUSTek       | 1015BX                      | Notebook    | [e0b95ee4e6](https://linux-hardware.org/?probe=e0b95ee4e6) | Mar 19, 2022 |
| ASRock        | H55M-LE                     | Desktop     | [f789f4563a](https://linux-hardware.org/?probe=f789f4563a) | Mar 19, 2022 |
| Lenovo        | ThinkPad X250 20CLS2JX00    | Notebook    | [c70a6de9d2](https://linux-hardware.org/?probe=c70a6de9d2) | Mar 19, 2022 |
| Samsung       | R528/R728                   | Notebook    | [0c8e6339bc](https://linux-hardware.org/?probe=0c8e6339bc) | Mar 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [2b2b775570](https://linux-hardware.org/?probe=2b2b775570) | Mar 19, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [2b99f73675](https://linux-hardware.org/?probe=2b99f73675) | Mar 19, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [29e36c8581](https://linux-hardware.org/?probe=29e36c8581) | Mar 19, 2022 |
| Dell          | Vostro 5481                 | Notebook    | [0b4c6544c1](https://linux-hardware.org/?probe=0b4c6544c1) | Mar 19, 2022 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [fb3415d61d](https://linux-hardware.org/?probe=fb3415d61d) | Mar 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [90adc19337](https://linux-hardware.org/?probe=90adc19337) | Mar 19, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [3ca3cc710d](https://linux-hardware.org/?probe=3ca3cc710d) | Mar 19, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [da9b5fc00d](https://linux-hardware.org/?probe=da9b5fc00d) | Mar 19, 2022 |
| ASRock        | Z270 Gaming K4              | Desktop     | [fd96a47e75](https://linux-hardware.org/?probe=fd96a47e75) | Mar 19, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [b07f0b09c6](https://linux-hardware.org/?probe=b07f0b09c6) | Mar 19, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [3e78d0dff1](https://linux-hardware.org/?probe=3e78d0dff1) | Mar 19, 2022 |
| ASUSTek       | B150M-PLUS D3               | Desktop     | [3ab8a178e9](https://linux-hardware.org/?probe=3ab8a178e9) | Mar 19, 2022 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [97e0d86243](https://linux-hardware.org/?probe=97e0d86243) | Mar 19, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [db1d7d479d](https://linux-hardware.org/?probe=db1d7d479d) | Mar 19, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [92215486d6](https://linux-hardware.org/?probe=92215486d6) | Mar 19, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [6efb7791bb](https://linux-hardware.org/?probe=6efb7791bb) | Mar 19, 2022 |
| ASUSTek       | X551CAP                     | Notebook    | [c0a4d8f9b3](https://linux-hardware.org/?probe=c0a4d8f9b3) | Mar 19, 2022 |
| Gigabyte      | GA-78LMT-S2 R2              | Desktop     | [550ded7f81](https://linux-hardware.org/?probe=550ded7f81) | Mar 19, 2022 |
| ECS           | P4M900T-M2                  | Desktop     | [262211610d](https://linux-hardware.org/?probe=262211610d) | Mar 19, 2022 |
| Acer          | Aspire V5-572PG             | Notebook    | [71bde2a34c](https://linux-hardware.org/?probe=71bde2a34c) | Mar 19, 2022 |
| Lenovo        | 3000 G410                   | Notebook    | [4ed6a8bd15](https://linux-hardware.org/?probe=4ed6a8bd15) | Mar 19, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [85a667aa69](https://linux-hardware.org/?probe=85a667aa69) | Mar 19, 2022 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [f7c5c30266](https://linux-hardware.org/?probe=f7c5c30266) | Mar 18, 2022 |
| Biostar       | H61MHV2                     | Desktop     | [7215b0c338](https://linux-hardware.org/?probe=7215b0c338) | Mar 18, 2022 |
| Gigabyte      | B560M GAMING HD             | Desktop     | [7fb3161cf4](https://linux-hardware.org/?probe=7fb3161cf4) | Mar 18, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [4d4f3f2f75](https://linux-hardware.org/?probe=4d4f3f2f75) | Mar 18, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [29db8ae2f8](https://linux-hardware.org/?probe=29db8ae2f8) | Mar 18, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [e1abb8fa21](https://linux-hardware.org/?probe=e1abb8fa21) | Mar 18, 2022 |
| ASUSTek       | X751MD                      | Notebook    | [28ea617ca1](https://linux-hardware.org/?probe=28ea617ca1) | Mar 18, 2022 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [520707aa61](https://linux-hardware.org/?probe=520707aa61) | Mar 18, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [a164112f8d](https://linux-hardware.org/?probe=a164112f8d) | Mar 18, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [5f407ad359](https://linux-hardware.org/?probe=5f407ad359) | Mar 18, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [e9e34594e8](https://linux-hardware.org/?probe=e9e34594e8) | Mar 18, 2022 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [b8ad1b22aa](https://linux-hardware.org/?probe=b8ad1b22aa) | Mar 18, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [4b2329edf6](https://linux-hardware.org/?probe=4b2329edf6) | Mar 18, 2022 |
| ASUSTek       | P50IJ                       | Notebook    | [1c1bbe3dad](https://linux-hardware.org/?probe=1c1bbe3dad) | Mar 18, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [b9822ea50b](https://linux-hardware.org/?probe=b9822ea50b) | Mar 18, 2022 |
| Dell          | G5 5590                     | Notebook    | [459123608b](https://linux-hardware.org/?probe=459123608b) | Mar 18, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [f2011ec78e](https://linux-hardware.org/?probe=f2011ec78e) | Mar 18, 2022 |
| Lenovo        | ThinkPad E470 20H2S17C00    | Notebook    | [10ad5ccfbe](https://linux-hardware.org/?probe=10ad5ccfbe) | Mar 18, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [0833c34819](https://linux-hardware.org/?probe=0833c34819) | Mar 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [dc42360c90](https://linux-hardware.org/?probe=dc42360c90) | Mar 18, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [a3c7a555df](https://linux-hardware.org/?probe=a3c7a555df) | Mar 18, 2022 |
| Lenovo        | H420                        | Desktop     | [b6aa4d1454](https://linux-hardware.org/?probe=b6aa4d1454) | Mar 18, 2022 |
| Gigabyte      | GA-MA74GM-S2                | Desktop     | [af8d9c8c06](https://linux-hardware.org/?probe=af8d9c8c06) | Mar 18, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [9f2b618c06](https://linux-hardware.org/?probe=9f2b618c06) | Mar 17, 2022 |
| MSI           | H81M-P33                    | Desktop     | [3cfbfd5eae](https://linux-hardware.org/?probe=3cfbfd5eae) | Mar 17, 2022 |
| Acer          | Veriton S2610G              | Desktop     | [f386a19d48](https://linux-hardware.org/?probe=f386a19d48) | Mar 17, 2022 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | Notebook    | [6848ceabc3](https://linux-hardware.org/?probe=6848ceabc3) | Mar 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [b928348a02](https://linux-hardware.org/?probe=b928348a02) | Mar 17, 2022 |
| Biostar       | H61MHV2                     | Desktop     | [e35ee37a65](https://linux-hardware.org/?probe=e35ee37a65) | Mar 17, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [30bcf38da7](https://linux-hardware.org/?probe=30bcf38da7) | Mar 17, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [a40f7ff51b](https://linux-hardware.org/?probe=a40f7ff51b) | Mar 17, 2022 |
| Gigabyte      | GA-78LMT-S2 R2              | Desktop     | [715a4f0c38](https://linux-hardware.org/?probe=715a4f0c38) | Mar 17, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [1fb2262bcc](https://linux-hardware.org/?probe=1fb2262bcc) | Mar 17, 2022 |
| Dell          | Precision 7510              | Notebook    | [b245b3fbbe](https://linux-hardware.org/?probe=b245b3fbbe) | Mar 17, 2022 |
| Acer          | Veriton N4660G              | Desktop     | [d388b291e1](https://linux-hardware.org/?probe=d388b291e1) | Mar 17, 2022 |
| Acer          | TravelMate P259-MG          | Notebook    | [cff272c0eb](https://linux-hardware.org/?probe=cff272c0eb) | Mar 17, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [c9c40c34bd](https://linux-hardware.org/?probe=c9c40c34bd) | Mar 17, 2022 |
| ASUSTek       | P5K/EPU                     | Desktop     | [38de085421](https://linux-hardware.org/?probe=38de085421) | Mar 17, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [90b9116ab3](https://linux-hardware.org/?probe=90b9116ab3) | Mar 17, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [45a830000a](https://linux-hardware.org/?probe=45a830000a) | Mar 17, 2022 |
| HUAWEI        | HBB-WX9                     | Notebook    | [2bc705b7f0](https://linux-hardware.org/?probe=2bc705b7f0) | Mar 17, 2022 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [7067f88bee](https://linux-hardware.org/?probe=7067f88bee) | Mar 17, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [9b36863bd5](https://linux-hardware.org/?probe=9b36863bd5) | Mar 17, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [d71d1c794b](https://linux-hardware.org/?probe=d71d1c794b) | Mar 17, 2022 |
| Gigabyte      | B360M H                     | Desktop     | [3190c29544](https://linux-hardware.org/?probe=3190c29544) | Mar 17, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| Dell          | 0V8F20 A01                  | Desktop     | [4ebf0529e9](https://linux-hardware.org/?probe=4ebf0529e9) | Mar 17, 2022 |
| HP            | 876C SMVB                   | Desktop     | [70e0a9f8cd](https://linux-hardware.org/?probe=70e0a9f8cd) | Mar 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [58fdf49095](https://linux-hardware.org/?probe=58fdf49095) | Mar 17, 2022 |
| HP            | 876C SMVB                   | Desktop     | [f077c079e1](https://linux-hardware.org/?probe=f077c079e1) | Mar 17, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [d011070d04](https://linux-hardware.org/?probe=d011070d04) | Mar 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [b289d3d5b9](https://linux-hardware.org/?probe=b289d3d5b9) | Mar 17, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [fdc892fa82](https://linux-hardware.org/?probe=fdc892fa82) | Mar 16, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XRT    | Notebook    | [54a5b7d556](https://linux-hardware.org/?probe=54a5b7d556) | Mar 16, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [43a66e755d](https://linux-hardware.org/?probe=43a66e755d) | Mar 16, 2022 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [5dc9563e82](https://linux-hardware.org/?probe=5dc9563e82) | Mar 16, 2022 |
| Lenovo        | Legion Y730-17ICH 81HG      | Notebook    | [f351aaa28f](https://linux-hardware.org/?probe=f351aaa28f) | Mar 16, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [a62b3060e7](https://linux-hardware.org/?probe=a62b3060e7) | Mar 16, 2022 |
| Acer          | AOD260                      | Notebook    | [a2c202021a](https://linux-hardware.org/?probe=a2c202021a) | Mar 16, 2022 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [bde043ea5f](https://linux-hardware.org/?probe=bde043ea5f) | Mar 16, 2022 |
| ASUSTek       | K53SM                       | Notebook    | [8b4b50fef2](https://linux-hardware.org/?probe=8b4b50fef2) | Mar 16, 2022 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [0a84cfb575](https://linux-hardware.org/?probe=0a84cfb575) | Mar 16, 2022 |
| Acer          | AOD260                      | Notebook    | [ad3082d89c](https://linux-hardware.org/?probe=ad3082d89c) | Mar 16, 2022 |
| ASRock        | M3A770DE                    | Desktop     | [5d198542ea](https://linux-hardware.org/?probe=5d198542ea) | Mar 16, 2022 |
| Dell          | Latitude E6330              | Notebook    | [860a9593af](https://linux-hardware.org/?probe=860a9593af) | Mar 16, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [fedff7063c](https://linux-hardware.org/?probe=fedff7063c) | Mar 16, 2022 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [1137a7fe46](https://linux-hardware.org/?probe=1137a7fe46) | Mar 16, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [58397d6bc1](https://linux-hardware.org/?probe=58397d6bc1) | Mar 16, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [c187336160](https://linux-hardware.org/?probe=c187336160) | Mar 16, 2022 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [8016ca75e5](https://linux-hardware.org/?probe=8016ca75e5) | Mar 16, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [a72345ecaa](https://linux-hardware.org/?probe=a72345ecaa) | Mar 16, 2022 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [1d88facac1](https://linux-hardware.org/?probe=1d88facac1) | Mar 16, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [c0afeb0060](https://linux-hardware.org/?probe=c0afeb0060) | Mar 16, 2022 |
| HP            | Pavilion g7                 | Notebook    | [7b01e72658](https://linux-hardware.org/?probe=7b01e72658) | Mar 16, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [d45d4a8339](https://linux-hardware.org/?probe=d45d4a8339) | Mar 15, 2022 |
| ASUSTek       | X75VD                       | Notebook    | [e4e91f90ab](https://linux-hardware.org/?probe=e4e91f90ab) | Mar 15, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [116bb6c003](https://linux-hardware.org/?probe=116bb6c003) | Mar 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [6fb5a4b51e](https://linux-hardware.org/?probe=6fb5a4b51e) | Mar 15, 2022 |
| Gigabyte      | E3000N                      | Desktop     | [10118ff80d](https://linux-hardware.org/?probe=10118ff80d) | Mar 15, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [0d18f0227e](https://linux-hardware.org/?probe=0d18f0227e) | Mar 15, 2022 |
| HP            | Notebook                    | Notebook    | [2a54a0b644](https://linux-hardware.org/?probe=2a54a0b644) | Mar 15, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [16371f42e1](https://linux-hardware.org/?probe=16371f42e1) | Mar 15, 2022 |
| Khadas        | VIM3                        | Soc         | [6ad73c849b](https://linux-hardware.org/?probe=6ad73c849b) | Mar 15, 2022 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | Notebook    | [c4ce1fa83f](https://linux-hardware.org/?probe=c4ce1fa83f) | Mar 15, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [84a794e739](https://linux-hardware.org/?probe=84a794e739) | Mar 15, 2022 |
| ECS           | GeForce6100PM-M2            | Desktop     | [ebabbc9e72](https://linux-hardware.org/?probe=ebabbc9e72) | Mar 15, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | Notebook    | [c0fcc559b7](https://linux-hardware.org/?probe=c0fcc559b7) | Mar 15, 2022 |
| ASUSTek       | K53U                        | Notebook    | [e2c08bf0fd](https://linux-hardware.org/?probe=e2c08bf0fd) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [a10cf12536](https://linux-hardware.org/?probe=a10cf12536) | Mar 15, 2022 |
| ASUSTek       | P5K                         | Desktop     | [28f94dd7f7](https://linux-hardware.org/?probe=28f94dd7f7) | Mar 15, 2022 |
| ASUSTek       | X551CA                      | Notebook    | [9f824eb133](https://linux-hardware.org/?probe=9f824eb133) | Mar 15, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [aa7912e58f](https://linux-hardware.org/?probe=aa7912e58f) | Mar 15, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [f1844c7ecb](https://linux-hardware.org/?probe=f1844c7ecb) | Mar 15, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [2a0c9b98d8](https://linux-hardware.org/?probe=2a0c9b98d8) | Mar 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [b0f276ec2e](https://linux-hardware.org/?probe=b0f276ec2e) | Mar 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [08329ea1a9](https://linux-hardware.org/?probe=08329ea1a9) | Mar 15, 2022 |
| ASUSTek       | P5KPL-AM IN/GB              | Desktop     | [ccc391b2d8](https://linux-hardware.org/?probe=ccc391b2d8) | Mar 15, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [a0a0ba299e](https://linux-hardware.org/?probe=a0a0ba299e) | Mar 15, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [eda8848760](https://linux-hardware.org/?probe=eda8848760) | Mar 15, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [8e0a8d6f39](https://linux-hardware.org/?probe=8e0a8d6f39) | Mar 15, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [0bfaf3176d](https://linux-hardware.org/?probe=0bfaf3176d) | Mar 14, 2022 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [b7592d46e1](https://linux-hardware.org/?probe=b7592d46e1) | Mar 14, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [eaa9fb6aad](https://linux-hardware.org/?probe=eaa9fb6aad) | Mar 14, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [834e2eaf27](https://linux-hardware.org/?probe=834e2eaf27) | Mar 14, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [937c0097ca](https://linux-hardware.org/?probe=937c0097ca) | Mar 14, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | Notebook    | [a503416ccd](https://linux-hardware.org/?probe=a503416ccd) | Mar 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [cc44f7c610](https://linux-hardware.org/?probe=cc44f7c610) | Mar 14, 2022 |
| Acer          | Calpella                    | Notebook    | [038e7b15ee](https://linux-hardware.org/?probe=038e7b15ee) | Mar 14, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [7e9674d806](https://linux-hardware.org/?probe=7e9674d806) | Mar 14, 2022 |
| ASRock        | Z370 Gaming K6              | Desktop     | [90bedd5ff6](https://linux-hardware.org/?probe=90bedd5ff6) | Mar 14, 2022 |
| AQUARIUS      | AQH310CM                    | Desktop     | [e2d2a06fac](https://linux-hardware.org/?probe=e2d2a06fac) | Mar 14, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [72eefd2811](https://linux-hardware.org/?probe=72eefd2811) | Mar 14, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [7f4d5a9689](https://linux-hardware.org/?probe=7f4d5a9689) | Mar 14, 2022 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [b511160401](https://linux-hardware.org/?probe=b511160401) | Mar 14, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [893a0b24ad](https://linux-hardware.org/?probe=893a0b24ad) | Mar 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [9ec78dcd40](https://linux-hardware.org/?probe=9ec78dcd40) | Mar 14, 2022 |
| MSI           | P43T-C51                    | Desktop     | [62e6cbd351](https://linux-hardware.org/?probe=62e6cbd351) | Mar 14, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [2720add6c2](https://linux-hardware.org/?probe=2720add6c2) | Mar 14, 2022 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [29373ba448](https://linux-hardware.org/?probe=29373ba448) | Mar 14, 2022 |
| ASRock        | B75M-DGS                    | Desktop     | [2d0363d0ee](https://linux-hardware.org/?probe=2d0363d0ee) | Mar 14, 2022 |
| Sony          | VPCEJ3L1R                   | Notebook    | [dbe66e9e9c](https://linux-hardware.org/?probe=dbe66e9e9c) | Mar 14, 2022 |
| ASRock        | H470M-HDV                   | Desktop     | [72a6f7ef1b](https://linux-hardware.org/?probe=72a6f7ef1b) | Mar 13, 2022 |
| ASUSTek       | X542UA                      | Notebook    | [60343e7f21](https://linux-hardware.org/?probe=60343e7f21) | Mar 13, 2022 |
| Acer          | Swift SF113-31              | Notebook    | [52d4aeefe6](https://linux-hardware.org/?probe=52d4aeefe6) | Mar 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [368bf3c9c6](https://linux-hardware.org/?probe=368bf3c9c6) | Mar 13, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [801998f12b](https://linux-hardware.org/?probe=801998f12b) | Mar 13, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [f4746b80f4](https://linux-hardware.org/?probe=f4746b80f4) | Mar 13, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [a4e0cb6c6e](https://linux-hardware.org/?probe=a4e0cb6c6e) | Mar 13, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [739b74effe](https://linux-hardware.org/?probe=739b74effe) | Mar 13, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [5ee92a3245](https://linux-hardware.org/?probe=5ee92a3245) | Mar 13, 2022 |
| ASRock        | M3A785GM-LE/128M            | Desktop     | [c975b33785](https://linux-hardware.org/?probe=c975b33785) | Mar 13, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [35a45d8ad1](https://linux-hardware.org/?probe=35a45d8ad1) | Mar 13, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [a1d347d586](https://linux-hardware.org/?probe=a1d347d586) | Mar 13, 2022 |
| ASUSTek       | K43SJ                       | Notebook    | [e761c99715](https://linux-hardware.org/?probe=e761c99715) | Mar 13, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [2012897e8d](https://linux-hardware.org/?probe=2012897e8d) | Mar 13, 2022 |
| ASRock        | M3A785GM-LE/128M            | Desktop     | [f53d1d8915](https://linux-hardware.org/?probe=f53d1d8915) | Mar 13, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [84d1a5e923](https://linux-hardware.org/?probe=84d1a5e923) | Mar 13, 2022 |
| Dell          | Latitude 3490               | Notebook    | [1dba55d488](https://linux-hardware.org/?probe=1dba55d488) | Mar 13, 2022 |
| Q87IX-06 1... | Unknown                     | Desktop     | [76207bc752](https://linux-hardware.org/?probe=76207bc752) | Mar 13, 2022 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [4ff0a96ca0](https://linux-hardware.org/?probe=4ff0a96ca0) | Mar 13, 2022 |
| ASUSTek       | X542UQ                      | Notebook    | [420374cb35](https://linux-hardware.org/?probe=420374cb35) | Mar 13, 2022 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [ac0b0cf98a](https://linux-hardware.org/?probe=ac0b0cf98a) | Mar 13, 2022 |
| Intel         | NUC7i3DNB J57625-513        | Mini pc     | [d23d5b7f32](https://linux-hardware.org/?probe=d23d5b7f32) | Mar 13, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [91c5ac0437](https://linux-hardware.org/?probe=91c5ac0437) | Mar 13, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [8ab5133b14](https://linux-hardware.org/?probe=8ab5133b14) | Mar 13, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [207cbc96ad](https://linux-hardware.org/?probe=207cbc96ad) | Mar 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [65301eac1a](https://linux-hardware.org/?probe=65301eac1a) | Mar 13, 2022 |
| MSI           | MS-7388                     | Desktop     | [fdd664b3fe](https://linux-hardware.org/?probe=fdd664b3fe) | Mar 13, 2022 |
| Dell          | Latitude 5511               | Notebook    | [ec15afa8e7](https://linux-hardware.org/?probe=ec15afa8e7) | Mar 12, 2022 |
| Sony          | VPCSA3Z9R                   | Notebook    | [3a61548567](https://linux-hardware.org/?probe=3a61548567) | Mar 12, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [8bef130be1](https://linux-hardware.org/?probe=8bef130be1) | Mar 12, 2022 |
| HP            | EliteBook 2170p             | Notebook    | [7e8c13d66a](https://linux-hardware.org/?probe=7e8c13d66a) | Mar 12, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [dc8b7b9927](https://linux-hardware.org/?probe=dc8b7b9927) | Mar 12, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [0198690333](https://linux-hardware.org/?probe=0198690333) | Mar 12, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [9bb5bb3bd4](https://linux-hardware.org/?probe=9bb5bb3bd4) | Mar 12, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [2bb86501da](https://linux-hardware.org/?probe=2bb86501da) | Mar 12, 2022 |
| Lenovo        | ThinkPad W530 24472SU       | Notebook    | [caac8b7b3d](https://linux-hardware.org/?probe=caac8b7b3d) | Mar 12, 2022 |
| MSI           | H81M-P33                    | Desktop     | [95d1b63c52](https://linux-hardware.org/?probe=95d1b63c52) | Mar 12, 2022 |
| Sony          | VPCEB2M1R                   | Notebook    | [aa365b6983](https://linux-hardware.org/?probe=aa365b6983) | Mar 12, 2022 |
| ASUSTek       | M2A74-AM SE                 | Desktop     | [7b20c55003](https://linux-hardware.org/?probe=7b20c55003) | Mar 12, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [2894a9c0be](https://linux-hardware.org/?probe=2894a9c0be) | Mar 12, 2022 |
| ASUSTek       | X551CA                      | Notebook    | [6822444b1c](https://linux-hardware.org/?probe=6822444b1c) | Mar 12, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [01c90d7554](https://linux-hardware.org/?probe=01c90d7554) | Mar 12, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [5f10f7d1af](https://linux-hardware.org/?probe=5f10f7d1af) | Mar 12, 2022 |
| Dell          | Inspiron M5040              | Notebook    | [d765287ece](https://linux-hardware.org/?probe=d765287ece) | Mar 12, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c378755487](https://linux-hardware.org/?probe=c378755487) | Mar 12, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [33a860d059](https://linux-hardware.org/?probe=33a860d059) | Mar 12, 2022 |
| Lenovo        | ThinkPad E580 20KS004GRT    | Notebook    | [4b3ecbe68e](https://linux-hardware.org/?probe=4b3ecbe68e) | Mar 11, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [30fd47f18c](https://linux-hardware.org/?probe=30fd47f18c) | Mar 11, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [7297101144](https://linux-hardware.org/?probe=7297101144) | Mar 11, 2022 |
| ASUSTek       | P5G41-M LE                  | Desktop     | [b6f7044980](https://linux-hardware.org/?probe=b6f7044980) | Mar 11, 2022 |
| Unknown       | Intel X79                   | Desktop     | [c848063fc1](https://linux-hardware.org/?probe=c848063fc1) | Mar 11, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [5a356066ca](https://linux-hardware.org/?probe=5a356066ca) | Mar 11, 2022 |
| ASUSTek       | X551MA                      | Notebook    | [ba5f39003e](https://linux-hardware.org/?probe=ba5f39003e) | Mar 11, 2022 |
| ASUSTek       | P8H61-V                     | Desktop     | [566a8ae873](https://linux-hardware.org/?probe=566a8ae873) | Mar 11, 2022 |
| Lenovo        | 20208                       | Notebook    | [533a09b178](https://linux-hardware.org/?probe=533a09b178) | Mar 11, 2022 |
| ASUSTek       | P5KPL-AM IN/GB              | Desktop     | [927be27436](https://linux-hardware.org/?probe=927be27436) | Mar 11, 2022 |
| Acer          | Aspire V5-571G              | Notebook    | [10a01b6a76](https://linux-hardware.org/?probe=10a01b6a76) | Mar 11, 2022 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [0da436fc26](https://linux-hardware.org/?probe=0da436fc26) | Mar 11, 2022 |
| Clevo         | M770SUA                     | Notebook    | [25b6849aa9](https://linux-hardware.org/?probe=25b6849aa9) | Mar 11, 2022 |
| AZW           | Gemini J45                  | Desktop     | [6705e1afd9](https://linux-hardware.org/?probe=6705e1afd9) | Mar 11, 2022 |
| MSI           | GP60 2OD                    | Notebook    | [14ec7ffbca](https://linux-hardware.org/?probe=14ec7ffbca) | Mar 11, 2022 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [093ff734b6](https://linux-hardware.org/?probe=093ff734b6) | Mar 11, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [725cbb4998](https://linux-hardware.org/?probe=725cbb4998) | Mar 11, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [f6068483ce](https://linux-hardware.org/?probe=f6068483ce) | Mar 11, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | All in one  | [83881d4eb6](https://linux-hardware.org/?probe=83881d4eb6) | Mar 11, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [37c37094b9](https://linux-hardware.org/?probe=37c37094b9) | Mar 11, 2022 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [5c45b0b08a](https://linux-hardware.org/?probe=5c45b0b08a) | Mar 11, 2022 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [2b68e9fabf](https://linux-hardware.org/?probe=2b68e9fabf) | Mar 11, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [cb8afcb315](https://linux-hardware.org/?probe=cb8afcb315) | Mar 11, 2022 |
| ASUSTek       | PRIME A520M-A               | Desktop     | [63d555c391](https://linux-hardware.org/?probe=63d555c391) | Mar 11, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [2d3f5f0f14](https://linux-hardware.org/?probe=2d3f5f0f14) | Mar 11, 2022 |
| Acer          | Aspire V5-571G              | Notebook    | [e909e31559](https://linux-hardware.org/?probe=e909e31559) | Mar 11, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [11b61d2b8a](https://linux-hardware.org/?probe=11b61d2b8a) | Mar 11, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [c10003c041](https://linux-hardware.org/?probe=c10003c041) | Mar 11, 2022 |
| Acer          | IPISB-AG                    | All in one  | [520a9bc6a0](https://linux-hardware.org/?probe=520a9bc6a0) | Mar 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [dab731fd45](https://linux-hardware.org/?probe=dab731fd45) | Mar 11, 2022 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [1a144a142f](https://linux-hardware.org/?probe=1a144a142f) | Mar 11, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [d82602f02f](https://linux-hardware.org/?probe=d82602f02f) | Mar 11, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [cbfe261386](https://linux-hardware.org/?probe=cbfe261386) | Mar 11, 2022 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [0a534cf272](https://linux-hardware.org/?probe=0a534cf272) | Mar 11, 2022 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [f58bb47a42](https://linux-hardware.org/?probe=f58bb47a42) | Mar 11, 2022 |
| HP            | Notebook                    | Notebook    | [de3091d5d4](https://linux-hardware.org/?probe=de3091d5d4) | Mar 11, 2022 |
| ASUSTek       | M4N68T V2                   | Desktop     | [5b061fa374](https://linux-hardware.org/?probe=5b061fa374) | Mar 11, 2022 |
| ASUSTek       | P6T WS PRO                  | Desktop     | [4414e91602](https://linux-hardware.org/?probe=4414e91602) | Mar 11, 2022 |
| ASUSTek       | N56VJ                       | Notebook    | [a1d8d94b5f](https://linux-hardware.org/?probe=a1d8d94b5f) | Mar 11, 2022 |
| ASRock        | B75M-DGS                    | Desktop     | [01d3e72fe4](https://linux-hardware.org/?probe=01d3e72fe4) | Mar 11, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [2ab16bfcee](https://linux-hardware.org/?probe=2ab16bfcee) | Mar 10, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [b5a4e6051e](https://linux-hardware.org/?probe=b5a4e6051e) | Mar 10, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [95b79e0953](https://linux-hardware.org/?probe=95b79e0953) | Mar 10, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [8bbf7f5495](https://linux-hardware.org/?probe=8bbf7f5495) | Mar 10, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [b4738fcf35](https://linux-hardware.org/?probe=b4738fcf35) | Mar 10, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [0a1f5e9bed](https://linux-hardware.org/?probe=0a1f5e9bed) | Mar 10, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [85c103c654](https://linux-hardware.org/?probe=85c103c654) | Mar 10, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [25518274da](https://linux-hardware.org/?probe=25518274da) | Mar 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [74aa64e60f](https://linux-hardware.org/?probe=74aa64e60f) | Mar 10, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [e8e38c1cf0](https://linux-hardware.org/?probe=e8e38c1cf0) | Mar 10, 2022 |
| HP            | Presario CQ58               | Notebook    | [2d71998513](https://linux-hardware.org/?probe=2d71998513) | Mar 10, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [db28c629ec](https://linux-hardware.org/?probe=db28c629ec) | Mar 10, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [698af00b9c](https://linux-hardware.org/?probe=698af00b9c) | Mar 10, 2022 |
| ASUSTek       | X541UA                      | Notebook    | [629d92121b](https://linux-hardware.org/?probe=629d92121b) | Mar 10, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [45beec1b7c](https://linux-hardware.org/?probe=45beec1b7c) | Mar 10, 2022 |
| Acer          | Aspire C22-760              | All in one  | [8952d0f7d8](https://linux-hardware.org/?probe=8952d0f7d8) | Mar 10, 2022 |
| JW Technol... | JW-A61PM-D3 Ver1.0          | Desktop     | [36d5ff9438](https://linux-hardware.org/?probe=36d5ff9438) | Mar 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [9bb17a1c87](https://linux-hardware.org/?probe=9bb17a1c87) | Mar 10, 2022 |
| ASUSTek       | K53U                        | Notebook    | [262bd2b6b5](https://linux-hardware.org/?probe=262bd2b6b5) | Mar 10, 2022 |
| ASRock        | G31M-GS                     | Desktop     | [fffba31b29](https://linux-hardware.org/?probe=fffba31b29) | Mar 10, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [85d36fac37](https://linux-hardware.org/?probe=85d36fac37) | Mar 10, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [e3ff8d781a](https://linux-hardware.org/?probe=e3ff8d781a) | Mar 10, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [f07a9bd206](https://linux-hardware.org/?probe=f07a9bd206) | Mar 10, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [57531c7393](https://linux-hardware.org/?probe=57531c7393) | Mar 10, 2022 |
| ASUSTek       | 1005P                       | Notebook    | [e138dde726](https://linux-hardware.org/?probe=e138dde726) | Mar 09, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [83dc415e28](https://linux-hardware.org/?probe=83dc415e28) | Mar 09, 2022 |
| KLLISRE       | X99-B5 V1.1                 | Desktop     | [d6c85ec83f](https://linux-hardware.org/?probe=d6c85ec83f) | Mar 09, 2022 |
| Dell          | Latitude E5550              | Notebook    | [38404c5760](https://linux-hardware.org/?probe=38404c5760) | Mar 09, 2022 |
| Toshiba       | Satellite A660              | Notebook    | [d52ba5f273](https://linux-hardware.org/?probe=d52ba5f273) | Mar 09, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e168d8e955](https://linux-hardware.org/?probe=e168d8e955) | Mar 09, 2022 |
| Dell          | 0RJ291                      | Desktop     | [52526b4a77](https://linux-hardware.org/?probe=52526b4a77) | Mar 09, 2022 |
| Lenovo        | ThinkPad T410 2537VGY       | Notebook    | [4601c3aa77](https://linux-hardware.org/?probe=4601c3aa77) | Mar 09, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [d3ad998dfa](https://linux-hardware.org/?probe=d3ad998dfa) | Mar 09, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8bb70cc1a1](https://linux-hardware.org/?probe=8bb70cc1a1) | Mar 09, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [17dd3a82ae](https://linux-hardware.org/?probe=17dd3a82ae) | Mar 09, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [2af2bba8da](https://linux-hardware.org/?probe=2af2bba8da) | Mar 09, 2022 |
| 3Logic Gro... | APM Graviton A15i-K2        | Notebook    | [e93bcf2f42](https://linux-hardware.org/?probe=e93bcf2f42) | Mar 09, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [e8e64665a6](https://linux-hardware.org/?probe=e8e64665a6) | Mar 09, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [e323bc4a41](https://linux-hardware.org/?probe=e323bc4a41) | Mar 09, 2022 |
| HONOR         | NMH-WCX9                    | Notebook    | [fab21c122b](https://linux-hardware.org/?probe=fab21c122b) | Mar 09, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [2379c7546f](https://linux-hardware.org/?probe=2379c7546f) | Mar 09, 2022 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [ccbd207ebd](https://linux-hardware.org/?probe=ccbd207ebd) | Mar 09, 2022 |
| ASUSTek       | H110-PLUS                   | Desktop     | [5074891336](https://linux-hardware.org/?probe=5074891336) | Mar 09, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [fc064cce68](https://linux-hardware.org/?probe=fc064cce68) | Mar 09, 2022 |
| Samsung       | R425D/R525D                 | Notebook    | [7e3a87a955](https://linux-hardware.org/?probe=7e3a87a955) | Mar 09, 2022 |
| MSI           | G41M-P26                    | Desktop     | [b6af52fe64](https://linux-hardware.org/?probe=b6af52fe64) | Mar 09, 2022 |
| ASUSTek       | P5K                         | Desktop     | [1232b6173b](https://linux-hardware.org/?probe=1232b6173b) | Mar 09, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [2f29bf2f45](https://linux-hardware.org/?probe=2f29bf2f45) | Mar 09, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [6f9fd5c747](https://linux-hardware.org/?probe=6f9fd5c747) | Mar 09, 2022 |
| HONOR         | NMH-WCX9                    | Notebook    | [9bd4914d8e](https://linux-hardware.org/?probe=9bd4914d8e) | Mar 08, 2022 |
| ASUSTek       | Z87-C                       | Desktop     | [50bb4c65ab](https://linux-hardware.org/?probe=50bb4c65ab) | Mar 08, 2022 |
| MSI           | H97 PC Mate                 | Desktop     | [0f042a9f94](https://linux-hardware.org/?probe=0f042a9f94) | Mar 08, 2022 |
| ASUSTek       | H81M-D                      | Desktop     | [4a77df037b](https://linux-hardware.org/?probe=4a77df037b) | Mar 08, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [321af0eb17](https://linux-hardware.org/?probe=321af0eb17) | Mar 08, 2022 |
| Acer          | Aspire TC-391               | Desktop     | [146505adee](https://linux-hardware.org/?probe=146505adee) | Mar 08, 2022 |
| Dell          | Latitude 5520               | Notebook    | [2b53b85cd9](https://linux-hardware.org/?probe=2b53b85cd9) | Mar 08, 2022 |
| Lenovo        | H420                        | Desktop     | [79b5590711](https://linux-hardware.org/?probe=79b5590711) | Mar 08, 2022 |
| Lenovo        | G580                        | Notebook    | [b9824d8702](https://linux-hardware.org/?probe=b9824d8702) | Mar 08, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [92fc99440a](https://linux-hardware.org/?probe=92fc99440a) | Mar 08, 2022 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [a16ebd0f29](https://linux-hardware.org/?probe=a16ebd0f29) | Mar 08, 2022 |
| Dell          | Vostro 5391                 | Notebook    | [2dddd7b8df](https://linux-hardware.org/?probe=2dddd7b8df) | Mar 08, 2022 |
| Dell          | Latitude 7400               | Notebook    | [85fb049c80](https://linux-hardware.org/?probe=85fb049c80) | Mar 08, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c28b8c26c1](https://linux-hardware.org/?probe=c28b8c26c1) | Mar 08, 2022 |
| ASRock        | H55M-LE                     | Desktop     | [e8067701ed](https://linux-hardware.org/?probe=e8067701ed) | Mar 08, 2022 |
| MSI           | G31M2                       | Desktop     | [b801fd62b9](https://linux-hardware.org/?probe=b801fd62b9) | Mar 08, 2022 |
| Intel         | Unknown                     | Notebook    | [9390bef13c](https://linux-hardware.org/?probe=9390bef13c) | Mar 08, 2022 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [21926a008c](https://linux-hardware.org/?probe=21926a008c) | Mar 08, 2022 |
| ASUSTek       | M2N-MX SE                   | Desktop     | [6b9596628e](https://linux-hardware.org/?probe=6b9596628e) | Mar 08, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [ced72ee9f4](https://linux-hardware.org/?probe=ced72ee9f4) | Mar 08, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [2704174c66](https://linux-hardware.org/?probe=2704174c66) | Mar 07, 2022 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [ad52f27969](https://linux-hardware.org/?probe=ad52f27969) | Mar 07, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [061074980c](https://linux-hardware.org/?probe=061074980c) | Mar 07, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [826909597b](https://linux-hardware.org/?probe=826909597b) | Mar 07, 2022 |
| Toshiba       | Satellite L875              | Notebook    | [ad99a6a57b](https://linux-hardware.org/?probe=ad99a6a57b) | Mar 07, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [6add82ce5c](https://linux-hardware.org/?probe=6add82ce5c) | Mar 07, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [a013213da6](https://linux-hardware.org/?probe=a013213da6) | Mar 07, 2022 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [20a55aa1f3](https://linux-hardware.org/?probe=20a55aa1f3) | Mar 07, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [c42d057b96](https://linux-hardware.org/?probe=c42d057b96) | Mar 07, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [7d4fb351f4](https://linux-hardware.org/?probe=7d4fb351f4) | Mar 07, 2022 |
| ASUSTek       | M2N-MX SE                   | Desktop     | [439d12c6fc](https://linux-hardware.org/?probe=439d12c6fc) | Mar 07, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [ba45148aae](https://linux-hardware.org/?probe=ba45148aae) | Mar 07, 2022 |
| Toshiba       | Satellite L875              | Notebook    | [a5487c84f8](https://linux-hardware.org/?probe=a5487c84f8) | Mar 07, 2022 |
| Acer          | Aspire 3650                 | Notebook    | [29dcfad748](https://linux-hardware.org/?probe=29dcfad748) | Mar 07, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7df453dfd2](https://linux-hardware.org/?probe=7df453dfd2) | Mar 07, 2022 |
| GTZS          | Unknown                     | Notebook    | [7fe0316acf](https://linux-hardware.org/?probe=7fe0316acf) | Mar 07, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [cca7575f29](https://linux-hardware.org/?probe=cca7575f29) | Mar 07, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [1f42efe596](https://linux-hardware.org/?probe=1f42efe596) | Mar 07, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [160615bea7](https://linux-hardware.org/?probe=160615bea7) | Mar 07, 2022 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [b3d65c3dfe](https://linux-hardware.org/?probe=b3d65c3dfe) | Mar 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [9c45f031b3](https://linux-hardware.org/?probe=9c45f031b3) | Mar 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [07d3e9d934](https://linux-hardware.org/?probe=07d3e9d934) | Mar 06, 2022 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [0bb1088899](https://linux-hardware.org/?probe=0bb1088899) | Mar 06, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [7535a8d317](https://linux-hardware.org/?probe=7535a8d317) | Mar 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [a544689bd5](https://linux-hardware.org/?probe=a544689bd5) | Mar 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4d84ed2405](https://linux-hardware.org/?probe=4d84ed2405) | Mar 06, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [4e3d7eb078](https://linux-hardware.org/?probe=4e3d7eb078) | Mar 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [8170747d86](https://linux-hardware.org/?probe=8170747d86) | Mar 06, 2022 |
| Gigabyte      | U2442                       | Notebook    | [24abf055f8](https://linux-hardware.org/?probe=24abf055f8) | Mar 06, 2022 |
| ASRock        | P43DE                       | Desktop     | [08da43be7f](https://linux-hardware.org/?probe=08da43be7f) | Mar 06, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [dff557f92e](https://linux-hardware.org/?probe=dff557f92e) | Mar 06, 2022 |
| DNS           | MB40IA1                     | Notebook    | [e2df5b5d37](https://linux-hardware.org/?probe=e2df5b5d37) | Mar 06, 2022 |
| Gigabyte      | H61M-D2H                    | Desktop     | [de63f89d08](https://linux-hardware.org/?probe=de63f89d08) | Mar 06, 2022 |
| GTZS          | Unknown                     | Notebook    | [c6cfedc194](https://linux-hardware.org/?probe=c6cfedc194) | Mar 06, 2022 |
| Gigabyte      | H55-UD3H                    | Desktop     | [d95c52bff7](https://linux-hardware.org/?probe=d95c52bff7) | Mar 06, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [b371240959](https://linux-hardware.org/?probe=b371240959) | Mar 06, 2022 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [80b844d396](https://linux-hardware.org/?probe=80b844d396) | Mar 06, 2022 |
| Lenovo        | 36FA No DPK                 | All in one  | [231da9915b](https://linux-hardware.org/?probe=231da9915b) | Mar 06, 2022 |
| HP            | Notebook                    | Notebook    | [57ce8d33b8](https://linux-hardware.org/?probe=57ce8d33b8) | Mar 06, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [8a30ea3dc6](https://linux-hardware.org/?probe=8a30ea3dc6) | Mar 06, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [3210667e8d](https://linux-hardware.org/?probe=3210667e8d) | Mar 06, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [ee546897fd](https://linux-hardware.org/?probe=ee546897fd) | Mar 06, 2022 |
| Dell          | G5 5590                     | Notebook    | [9b95f2ae1d](https://linux-hardware.org/?probe=9b95f2ae1d) | Mar 06, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [bc59a5a32b](https://linux-hardware.org/?probe=bc59a5a32b) | Mar 06, 2022 |
| DNS           | MB40IA1                     | Notebook    | [b7e3afe5b7](https://linux-hardware.org/?probe=b7e3afe5b7) | Mar 06, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [7301ac3b25](https://linux-hardware.org/?probe=7301ac3b25) | Mar 06, 2022 |
| HP            | 650                         | Notebook    | [7b018f66df](https://linux-hardware.org/?probe=7b018f66df) | Mar 06, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [85a405bce4](https://linux-hardware.org/?probe=85a405bce4) | Mar 06, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [9a0f2a2848](https://linux-hardware.org/?probe=9a0f2a2848) | Mar 06, 2022 |
| Gigabyte      | M68MT-S2                    | Desktop     | [b57d637fce](https://linux-hardware.org/?probe=b57d637fce) | Mar 06, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [8d2f324da4](https://linux-hardware.org/?probe=8d2f324da4) | Mar 06, 2022 |
| Sony          | SVS1512U1RW                 | Notebook    | [a8c9c44e7d](https://linux-hardware.org/?probe=a8c9c44e7d) | Mar 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [8512aba5f1](https://linux-hardware.org/?probe=8512aba5f1) | Mar 05, 2022 |
| Lenovo        | IdeaPad S20-30              | Notebook    | [d1282ebbca](https://linux-hardware.org/?probe=d1282ebbca) | Mar 05, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [31f37e7748](https://linux-hardware.org/?probe=31f37e7748) | Mar 05, 2022 |
| FIC           | GE2 Series                  | Desktop     | [9bb3496465](https://linux-hardware.org/?probe=9bb3496465) | Mar 05, 2022 |
| Sony          | SVS1512U1RW                 | Notebook    | [007a73bc6e](https://linux-hardware.org/?probe=007a73bc6e) | Mar 05, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [18b6ca38b8](https://linux-hardware.org/?probe=18b6ca38b8) | Mar 05, 2022 |
| ASUSTek       | Zenbook UP5401EA_UP5401E... | Convertible | [f23d0b2728](https://linux-hardware.org/?probe=f23d0b2728) | Mar 05, 2022 |
| AIO           | H61H-G11                    | Desktop     | [0d7e8c7568](https://linux-hardware.org/?probe=0d7e8c7568) | Mar 05, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [d62cbb546d](https://linux-hardware.org/?probe=d62cbb546d) | Mar 05, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [eeb665e3dc](https://linux-hardware.org/?probe=eeb665e3dc) | Mar 05, 2022 |
| FIC           | GE2 Series                  | Desktop     | [0e3eefdbbd](https://linux-hardware.org/?probe=0e3eefdbbd) | Mar 05, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [fb109e5618](https://linux-hardware.org/?probe=fb109e5618) | Mar 05, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [4f93db2c52](https://linux-hardware.org/?probe=4f93db2c52) | Mar 05, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [2df5098230](https://linux-hardware.org/?probe=2df5098230) | Mar 05, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [53b6a5c6bd](https://linux-hardware.org/?probe=53b6a5c6bd) | Mar 05, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [c972c35bde](https://linux-hardware.org/?probe=c972c35bde) | Mar 05, 2022 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [30ff404b05](https://linux-hardware.org/?probe=30ff404b05) | Mar 05, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [b52536f8a4](https://linux-hardware.org/?probe=b52536f8a4) | Mar 05, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [034f4d4131](https://linux-hardware.org/?probe=034f4d4131) | Mar 05, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [88e2ccd4e5](https://linux-hardware.org/?probe=88e2ccd4e5) | Mar 05, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [19345d9a81](https://linux-hardware.org/?probe=19345d9a81) | Mar 04, 2022 |
| ASRock        | Q370M vPro                  | Desktop     | [4f6fe9951a](https://linux-hardware.org/?probe=4f6fe9951a) | Mar 04, 2022 |
| ASRock        | H55M-LE                     | Desktop     | [7ba52b85fe](https://linux-hardware.org/?probe=7ba52b85fe) | Mar 04, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [015cea29f4](https://linux-hardware.org/?probe=015cea29f4) | Mar 04, 2022 |
| ASRock        | G31M-S                      | Desktop     | [f4f545a858](https://linux-hardware.org/?probe=f4f545a858) | Mar 04, 2022 |
| ASUSTek       | 1201T                       | Notebook    | [0c5ab272e7](https://linux-hardware.org/?probe=0c5ab272e7) | Mar 04, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [5886b2f027](https://linux-hardware.org/?probe=5886b2f027) | Mar 04, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [a93cb7c85e](https://linux-hardware.org/?probe=a93cb7c85e) | Mar 04, 2022 |
| Cube          | SurfTab twin 11.6           | Convertible | [d8659d7018](https://linux-hardware.org/?probe=d8659d7018) | Mar 03, 2022 |
| Cube          | SurfTab twin 11.6           | Convertible | [fde2a4b713](https://linux-hardware.org/?probe=fde2a4b713) | Mar 03, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [eb84a61b0d](https://linux-hardware.org/?probe=eb84a61b0d) | Mar 03, 2022 |
| ASUSTek       | B150M-D                     | Desktop     | [98291d2c13](https://linux-hardware.org/?probe=98291d2c13) | Mar 03, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [0d5303fc1a](https://linux-hardware.org/?probe=0d5303fc1a) | Mar 03, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [1dd9830ab5](https://linux-hardware.org/?probe=1dd9830ab5) | Mar 03, 2022 |
| Gigabyte      | F2A55-DS3                   | Desktop     | [a1086c2436](https://linux-hardware.org/?probe=a1086c2436) | Mar 03, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [957c478b74](https://linux-hardware.org/?probe=957c478b74) | Mar 03, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [f4e226bea7](https://linux-hardware.org/?probe=f4e226bea7) | Mar 03, 2022 |
| Biostar       | P4M90-M7 Ver:1.0            | Desktop     | [9e310a9389](https://linux-hardware.org/?probe=9e310a9389) | Mar 03, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [36cd8309bc](https://linux-hardware.org/?probe=36cd8309bc) | Mar 03, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [0195fe9da4](https://linux-hardware.org/?probe=0195fe9da4) | Mar 03, 2022 |
| ASUSTek       | P5B-V                       | Desktop     | [2bca34990f](https://linux-hardware.org/?probe=2bca34990f) | Mar 03, 2022 |
| Dell          | 0RM5DR A00                  | Desktop     | [2a8f42bdc3](https://linux-hardware.org/?probe=2a8f42bdc3) | Mar 03, 2022 |
| Timi          | Mi Laptop Pro 15            | Notebook    | [43e046672b](https://linux-hardware.org/?probe=43e046672b) | Mar 03, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [fd7ea23a2a](https://linux-hardware.org/?probe=fd7ea23a2a) | Mar 03, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [c67a313947](https://linux-hardware.org/?probe=c67a313947) | Mar 03, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [ca53435b36](https://linux-hardware.org/?probe=ca53435b36) | Mar 03, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [75a505dc2e](https://linux-hardware.org/?probe=75a505dc2e) | Mar 03, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [4a4fd37e32](https://linux-hardware.org/?probe=4a4fd37e32) | Mar 02, 2022 |
| HP            | ENVY 6                      | Notebook    | [23f60a7428](https://linux-hardware.org/?probe=23f60a7428) | Mar 02, 2022 |
| Lenovo        | HuronRiver Platform         | Notebook    | [a34efebccf](https://linux-hardware.org/?probe=a34efebccf) | Mar 02, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [2861edc794](https://linux-hardware.org/?probe=2861edc794) | Mar 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [95296f29bb](https://linux-hardware.org/?probe=95296f29bb) | Mar 02, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [4fc1001606](https://linux-hardware.org/?probe=4fc1001606) | Mar 02, 2022 |
| Acer          | Acadia V1.45                | Notebook    | [3ff1cac0c2](https://linux-hardware.org/?probe=3ff1cac0c2) | Mar 02, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f7989573c3](https://linux-hardware.org/?probe=f7989573c3) | Mar 02, 2022 |
| HP            | G62                         | Notebook    | [5cb594a70d](https://linux-hardware.org/?probe=5cb594a70d) | Mar 02, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [9ab077cead](https://linux-hardware.org/?probe=9ab077cead) | Mar 02, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [312b86f0cc](https://linux-hardware.org/?probe=312b86f0cc) | Mar 02, 2022 |
| AQUARIUS      | AQH410T                     | Desktop     | [f02c2d0259](https://linux-hardware.org/?probe=f02c2d0259) | Mar 02, 2022 |
| Lenovo        | ThinkPad W530 243857U       | Notebook    | [21c4433bf2](https://linux-hardware.org/?probe=21c4433bf2) | Mar 02, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a90b7bb57e](https://linux-hardware.org/?probe=a90b7bb57e) | Mar 02, 2022 |
| ASUSTek       | P5BV-C/4L                   | Desktop     | [d05dbacfb2](https://linux-hardware.org/?probe=d05dbacfb2) | Mar 02, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [89e589ec6b](https://linux-hardware.org/?probe=89e589ec6b) | Mar 02, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [4dd2db58c8](https://linux-hardware.org/?probe=4dd2db58c8) | Mar 02, 2022 |
| HP            | Notebook PC                 | Notebook    | [2297e2813f](https://linux-hardware.org/?probe=2297e2813f) | Mar 02, 2022 |
| Acer          | Aspire C24-1650             | All in one  | [32ecaac328](https://linux-hardware.org/?probe=32ecaac328) | Mar 02, 2022 |
| Gigabyte      | H310M S2                    | Desktop     | [af747fddc7](https://linux-hardware.org/?probe=af747fddc7) | Mar 02, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [c272aff72c](https://linux-hardware.org/?probe=c272aff72c) | Mar 02, 2022 |
| Acer          | P5WE0                       | Notebook    | [c79056479e](https://linux-hardware.org/?probe=c79056479e) | Mar 01, 2022 |
| Irbis         | G04NB6602812000702          | Desktop     | [9aca90e6d5](https://linux-hardware.org/?probe=9aca90e6d5) | Mar 01, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [d200cdb05c](https://linux-hardware.org/?probe=d200cdb05c) | Mar 01, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [f26f40aa50](https://linux-hardware.org/?probe=f26f40aa50) | Mar 01, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [6708cd0723](https://linux-hardware.org/?probe=6708cd0723) | Mar 01, 2022 |
| ASUSTek       | M4A785D-M PRO               | Desktop     | [36e3089b38](https://linux-hardware.org/?probe=36e3089b38) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [4fe25f775d](https://linux-hardware.org/?probe=4fe25f775d) | Mar 01, 2022 |
| ASUSTek       | F5SL                        | Notebook    | [f9f7087cdf](https://linux-hardware.org/?probe=f9f7087cdf) | Mar 01, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [6e98976f1a](https://linux-hardware.org/?probe=6e98976f1a) | Mar 01, 2022 |
| MSI           | H55M-P31                    | Desktop     | [cde1b92fdc](https://linux-hardware.org/?probe=cde1b92fdc) | Mar 01, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [e683855566](https://linux-hardware.org/?probe=e683855566) | Mar 01, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [884adfefd3](https://linux-hardware.org/?probe=884adfefd3) | Mar 01, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [14b646834e](https://linux-hardware.org/?probe=14b646834e) | Mar 01, 2022 |
| Aquarius      | AQB560M                     | All in one  | [4d3df118f0](https://linux-hardware.org/?probe=4d3df118f0) | Mar 01, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [c5b8c08527](https://linux-hardware.org/?probe=c5b8c08527) | Mar 01, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [e61dde5545](https://linux-hardware.org/?probe=e61dde5545) | Mar 01, 2022 |
| Aquarius      | AQB560M                     | Desktop     | [091fa6d697](https://linux-hardware.org/?probe=091fa6d697) | Mar 01, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [6d5acc6be7](https://linux-hardware.org/?probe=6d5acc6be7) | Mar 01, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [a40ff918fe](https://linux-hardware.org/?probe=a40ff918fe) | Mar 01, 2022 |
| Samsung       | 940X5N                      | Convertible | [ff8e77c616](https://linux-hardware.org/?probe=ff8e77c616) | Mar 01, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [693e94bdb6](https://linux-hardware.org/?probe=693e94bdb6) | Mar 01, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7b08a801d1](https://linux-hardware.org/?probe=7b08a801d1) | Mar 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS0LW00    | Notebook    | [c781fc668f](https://linux-hardware.org/?probe=c781fc668f) | Mar 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [87e1eb605a](https://linux-hardware.org/?probe=87e1eb605a) | Feb 28, 2022 |
| Lenovo        | B560                        | Notebook    | [a860ecebe5](https://linux-hardware.org/?probe=a860ecebe5) | Feb 28, 2022 |
| ASUSTek       | F5SL                        | Notebook    | [01accf63ad](https://linux-hardware.org/?probe=01accf63ad) | Feb 28, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [a73f7ae919](https://linux-hardware.org/?probe=a73f7ae919) | Feb 28, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [23c2a93047](https://linux-hardware.org/?probe=23c2a93047) | Feb 28, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [6cf3696f35](https://linux-hardware.org/?probe=6cf3696f35) | Feb 28, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [4d274afb4a](https://linux-hardware.org/?probe=4d274afb4a) | Feb 28, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [87083d1a0f](https://linux-hardware.org/?probe=87083d1a0f) | Feb 28, 2022 |
| Dell          | Inspiron 3558               | Notebook    | [e6b604b9dc](https://linux-hardware.org/?probe=e6b604b9dc) | Feb 28, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [dccdb6871d](https://linux-hardware.org/?probe=dccdb6871d) | Feb 28, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [efcd8651f8](https://linux-hardware.org/?probe=efcd8651f8) | Feb 28, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [a032cb00cd](https://linux-hardware.org/?probe=a032cb00cd) | Feb 28, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [c2d198ab83](https://linux-hardware.org/?probe=c2d198ab83) | Feb 28, 2022 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [5485738b5a](https://linux-hardware.org/?probe=5485738b5a) | Feb 28, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | All in one  | [04a1a09e43](https://linux-hardware.org/?probe=04a1a09e43) | Feb 28, 2022 |
| ASUSTek       | P5LD2-X                     | Desktop     | [c8826083d1](https://linux-hardware.org/?probe=c8826083d1) | Feb 28, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [d4d9841cbe](https://linux-hardware.org/?probe=d4d9841cbe) | Feb 28, 2022 |
| ASRock        | 760GM-HDV                   | Desktop     | [7f7cbc5231](https://linux-hardware.org/?probe=7f7cbc5231) | Feb 28, 2022 |
| Lenovo        | ThinkPad L420 7829W8S       | Notebook    | [beb58a9384](https://linux-hardware.org/?probe=beb58a9384) | Feb 28, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [eb150521bc](https://linux-hardware.org/?probe=eb150521bc) | Feb 28, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [905f4927f5](https://linux-hardware.org/?probe=905f4927f5) | Feb 28, 2022 |
| Samsung       | Q310                        | Notebook    | [88aa731039](https://linux-hardware.org/?probe=88aa731039) | Feb 28, 2022 |
| Biostar       | A68MHE                      | Desktop     | [b2146327c4](https://linux-hardware.org/?probe=b2146327c4) | Feb 28, 2022 |
| Acer          | Aspire A114-33              | Notebook    | [cf0275bc41](https://linux-hardware.org/?probe=cf0275bc41) | Feb 28, 2022 |
| Intel         | NUC5PPYB H76558-102         | Mini pc     | [207e311cfc](https://linux-hardware.org/?probe=207e311cfc) | Feb 28, 2022 |
| Intel         | DN2820FYK H24582-203        | Desktop     | [a1f5264c5a](https://linux-hardware.org/?probe=a1f5264c5a) | Feb 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [ee935ed8be](https://linux-hardware.org/?probe=ee935ed8be) | Feb 28, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [f4a068f57c](https://linux-hardware.org/?probe=f4a068f57c) | Feb 27, 2022 |
| Dell          | Latitude E6540              | Notebook    | [cb7e492cd9](https://linux-hardware.org/?probe=cb7e492cd9) | Feb 27, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [78cc2173d9](https://linux-hardware.org/?probe=78cc2173d9) | Feb 27, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [f8f7e8ac88](https://linux-hardware.org/?probe=f8f7e8ac88) | Feb 27, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [c97a79e04f](https://linux-hardware.org/?probe=c97a79e04f) | Feb 27, 2022 |
| Toshiba       | QOSMIO F60                  | Notebook    | [71e17539c9](https://linux-hardware.org/?probe=71e17539c9) | Feb 27, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [b73a01ebca](https://linux-hardware.org/?probe=b73a01ebca) | Feb 27, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [9ae863d68c](https://linux-hardware.org/?probe=9ae863d68c) | Feb 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [abed4a5863](https://linux-hardware.org/?probe=abed4a5863) | Feb 27, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [ee2e8bab58](https://linux-hardware.org/?probe=ee2e8bab58) | Feb 27, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | Notebook    | [4bd308dadf](https://linux-hardware.org/?probe=4bd308dadf) | Feb 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [ed1b593603](https://linux-hardware.org/?probe=ed1b593603) | Feb 26, 2022 |
| Samsung       | NC110P/NC108P/NC111P        | Notebook    | [fd3aa1b379](https://linux-hardware.org/?probe=fd3aa1b379) | Feb 26, 2022 |
| Fujitsu Si... | LIFEBOOK S7020              | Notebook    | [ec2491adc1](https://linux-hardware.org/?probe=ec2491adc1) | Feb 26, 2022 |
| HP            | Pavilion dv6                | Notebook    | [073fabe370](https://linux-hardware.org/?probe=073fabe370) | Feb 26, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [1cddab051d](https://linux-hardware.org/?probe=1cddab051d) | Feb 26, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [441141c87d](https://linux-hardware.org/?probe=441141c87d) | Feb 26, 2022 |
| Gigabyte      | N3160TN                     | Desktop     | [f080ac90fa](https://linux-hardware.org/?probe=f080ac90fa) | Feb 26, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [dfcdd05598](https://linux-hardware.org/?probe=dfcdd05598) | Feb 26, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [4722b6373e](https://linux-hardware.org/?probe=4722b6373e) | Feb 26, 2022 |
| ASUSTek       | P8H61 R2.0                  | Desktop     | [e762babc96](https://linux-hardware.org/?probe=e762babc96) | Feb 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [8559bbe9c1](https://linux-hardware.org/?probe=8559bbe9c1) | Feb 26, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [d7b0ae17c0](https://linux-hardware.org/?probe=d7b0ae17c0) | Feb 26, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [9773c6c6bd](https://linux-hardware.org/?probe=9773c6c6bd) | Feb 26, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [fb4c469104](https://linux-hardware.org/?probe=fb4c469104) | Feb 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ef592cb1a7](https://linux-hardware.org/?probe=ef592cb1a7) | Feb 26, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9013eb37ee](https://linux-hardware.org/?probe=9013eb37ee) | Feb 25, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [8e648c583a](https://linux-hardware.org/?probe=8e648c583a) | Feb 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [261cea53b5](https://linux-hardware.org/?probe=261cea53b5) | Feb 25, 2022 |
| ASRock        | N68-GS3 UCC                 | Desktop     | [b2ba0fabdc](https://linux-hardware.org/?probe=b2ba0fabdc) | Feb 25, 2022 |
| AIO           | H61H-G11                    | Desktop     | [137ec871e7](https://linux-hardware.org/?probe=137ec871e7) | Feb 25, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c4d875ab4f](https://linux-hardware.org/?probe=c4d875ab4f) | Feb 25, 2022 |
| HP            | 2AF7                        | Desktop     | [4487f8d05d](https://linux-hardware.org/?probe=4487f8d05d) | Feb 25, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [9f18f01c7a](https://linux-hardware.org/?probe=9f18f01c7a) | Feb 25, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [50f19dd349](https://linux-hardware.org/?probe=50f19dd349) | Feb 25, 2022 |
| Gigabyte      | 8I945GZME-RH                | Desktop     | [4afdb1534e](https://linux-hardware.org/?probe=4afdb1534e) | Feb 25, 2022 |
| MSI           | Z97-G43 GAMING              | Desktop     | [c1d3cbc93c](https://linux-hardware.org/?probe=c1d3cbc93c) | Feb 25, 2022 |
| Lenovo        | B50-80 80LT                 | Notebook    | [b5dd44876a](https://linux-hardware.org/?probe=b5dd44876a) | Feb 25, 2022 |
| Lenovo        | B50-80 80LT                 | Notebook    | [d4775df51b](https://linux-hardware.org/?probe=d4775df51b) | Feb 25, 2022 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [e97bd26a11](https://linux-hardware.org/?probe=e97bd26a11) | Feb 25, 2022 |
| ASUSTek       | 1005PXD                     | Notebook    | [600a38a244](https://linux-hardware.org/?probe=600a38a244) | Feb 25, 2022 |
| Intel         | X79M-S                      | Desktop     | [a175e713d6](https://linux-hardware.org/?probe=a175e713d6) | Feb 25, 2022 |
| ECS           | G31T-M9                     | Desktop     | [4de828bf82](https://linux-hardware.org/?probe=4de828bf82) | Feb 25, 2022 |
| HP            | ENVY 6                      | Notebook    | [988417aaa7](https://linux-hardware.org/?probe=988417aaa7) | Feb 25, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c3347258f5](https://linux-hardware.org/?probe=c3347258f5) | Feb 24, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [11aee9d1c8](https://linux-hardware.org/?probe=11aee9d1c8) | Feb 24, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [6f1958559b](https://linux-hardware.org/?probe=6f1958559b) | Feb 24, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [0b5555f2ed](https://linux-hardware.org/?probe=0b5555f2ed) | Feb 24, 2022 |
| Gigabyte      | 8I945GZME-RH                | Desktop     | [a7414ad5c1](https://linux-hardware.org/?probe=a7414ad5c1) | Feb 24, 2022 |
| ASUSTek       | M4A785D-M PRO               | Desktop     | [cfb97398c6](https://linux-hardware.org/?probe=cfb97398c6) | Feb 24, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [c5e6e53bf0](https://linux-hardware.org/?probe=c5e6e53bf0) | Feb 24, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [5e687a3ff4](https://linux-hardware.org/?probe=5e687a3ff4) | Feb 24, 2022 |
| ECS           | G31T-M9                     | Desktop     | [a5898e6474](https://linux-hardware.org/?probe=a5898e6474) | Feb 24, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [1c753ca45b](https://linux-hardware.org/?probe=1c753ca45b) | Feb 24, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [e6c9e3133f](https://linux-hardware.org/?probe=e6c9e3133f) | Feb 24, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [00e3cebb2f](https://linux-hardware.org/?probe=00e3cebb2f) | Feb 24, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [cbf876b408](https://linux-hardware.org/?probe=cbf876b408) | Feb 24, 2022 |
| Lenovo        | IdeaPad S206 20154          | Notebook    | [8c712aa419](https://linux-hardware.org/?probe=8c712aa419) | Feb 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [ff0c4fc3a1](https://linux-hardware.org/?probe=ff0c4fc3a1) | Feb 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [604009e029](https://linux-hardware.org/?probe=604009e029) | Feb 24, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [db8b03c5b3](https://linux-hardware.org/?probe=db8b03c5b3) | Feb 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5710ee5e2e](https://linux-hardware.org/?probe=5710ee5e2e) | Feb 23, 2022 |
| Acer          | Spin SP111-32N              | Convertible | [d7b0376061](https://linux-hardware.org/?probe=d7b0376061) | Feb 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d271d58ebd](https://linux-hardware.org/?probe=d271d58ebd) | Feb 23, 2022 |
| Supermicro    | X10DAI                      | Desktop     | [4de85d4700](https://linux-hardware.org/?probe=4de85d4700) | Feb 23, 2022 |
| Acer          | Extensa 5620                | Notebook    | [d814497f9a](https://linux-hardware.org/?probe=d814497f9a) | Feb 23, 2022 |
| HP            | 15                          | Notebook    | [fa8d20b53f](https://linux-hardware.org/?probe=fa8d20b53f) | Feb 23, 2022 |
| Lenovo        | IdeaPad S10-2 20027         | Notebook    | [35ffcaed33](https://linux-hardware.org/?probe=35ffcaed33) | Feb 23, 2022 |
| Apple         | MacBookAir2,1               | Notebook    | [70a8d35e9e](https://linux-hardware.org/?probe=70a8d35e9e) | Feb 23, 2022 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [90c43679f7](https://linux-hardware.org/?probe=90c43679f7) | Feb 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f09566c9ee](https://linux-hardware.org/?probe=f09566c9ee) | Feb 23, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [3f8ccee299](https://linux-hardware.org/?probe=3f8ccee299) | Feb 23, 2022 |
| Packard Be... | DOT S                       | Notebook    | [337bbf93b3](https://linux-hardware.org/?probe=337bbf93b3) | Feb 23, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [30a18704d2](https://linux-hardware.org/?probe=30a18704d2) | Feb 23, 2022 |
| ASUSTek       | X55A                        | Notebook    | [2549eae4a5](https://linux-hardware.org/?probe=2549eae4a5) | Feb 23, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6cbbd9a058](https://linux-hardware.org/?probe=6cbbd9a058) | Feb 23, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [c2ed3df75c](https://linux-hardware.org/?probe=c2ed3df75c) | Feb 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f7f5346da6](https://linux-hardware.org/?probe=f7f5346da6) | Feb 23, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [c6aaa68e9c](https://linux-hardware.org/?probe=c6aaa68e9c) | Feb 23, 2022 |
| Acer          | Aspire M1470                | Desktop     | [1bbfd129de](https://linux-hardware.org/?probe=1bbfd129de) | Feb 23, 2022 |
| eMachines     | E725                        | Notebook    | [312a83e700](https://linux-hardware.org/?probe=312a83e700) | Feb 23, 2022 |
| Sony          | SVE1412E1RW                 | Notebook    | [3e0ba8aacd](https://linux-hardware.org/?probe=3e0ba8aacd) | Feb 23, 2022 |
| HP            | ProBook 4520s               | Notebook    | [c60e1c19e1](https://linux-hardware.org/?probe=c60e1c19e1) | Feb 23, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [03e3c857ce](https://linux-hardware.org/?probe=03e3c857ce) | Feb 23, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [d8a9c2e960](https://linux-hardware.org/?probe=d8a9c2e960) | Feb 23, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [95b1251334](https://linux-hardware.org/?probe=95b1251334) | Feb 23, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0327cb408a](https://linux-hardware.org/?probe=0327cb408a) | Feb 23, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2dc15462eb](https://linux-hardware.org/?probe=2dc15462eb) | Feb 23, 2022 |
| Lenovo        | 30D2 NOK                    | Desktop     | [108296cf9b](https://linux-hardware.org/?probe=108296cf9b) | Feb 22, 2022 |
| Samsung       | N150/N210/N220              | Notebook    | [c0ce4da770](https://linux-hardware.org/?probe=c0ce4da770) | Feb 22, 2022 |
| ASUSTek       | P5P800-VM                   | Desktop     | [134186f7a6](https://linux-hardware.org/?probe=134186f7a6) | Feb 22, 2022 |
| Acer          | Aspire M1470                | Desktop     | [216efdea1e](https://linux-hardware.org/?probe=216efdea1e) | Feb 22, 2022 |
| Lenovo        | 316E SDK0J40697 WIN 3305... | Mini pc     | [bf51c93832](https://linux-hardware.org/?probe=bf51c93832) | Feb 22, 2022 |
| Intel         | HuronRiver Platform         | Notebook    | [a2763becf2](https://linux-hardware.org/?probe=a2763becf2) | Feb 22, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [8dd91322d5](https://linux-hardware.org/?probe=8dd91322d5) | Feb 22, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [8580399323](https://linux-hardware.org/?probe=8580399323) | Feb 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [b431a936fd](https://linux-hardware.org/?probe=b431a936fd) | Feb 22, 2022 |
| Lenovo        | 3130 NOK                    | Mini pc     | [cc222d78b9](https://linux-hardware.org/?probe=cc222d78b9) | Feb 22, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [d529f24512](https://linux-hardware.org/?probe=d529f24512) | Feb 22, 2022 |
| Lenovo        | 316E SDK0J40697 WIN 3305... | Mini pc     | [a831ba5c10](https://linux-hardware.org/?probe=a831ba5c10) | Feb 22, 2022 |
| ASUSTek       | P5QL-CM                     | Desktop     | [448c00878c](https://linux-hardware.org/?probe=448c00878c) | Feb 22, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [611cfcfbaa](https://linux-hardware.org/?probe=611cfcfbaa) | Feb 22, 2022 |
| Pegatron      | 2A99                        | Desktop     | [f6351515fa](https://linux-hardware.org/?probe=f6351515fa) | Feb 22, 2022 |
| ASUSTek       | P5QL                        | Desktop     | [2714d59901](https://linux-hardware.org/?probe=2714d59901) | Feb 22, 2022 |
| eMachines     | eM250                       | Notebook    | [ebd724598b](https://linux-hardware.org/?probe=ebd724598b) | Feb 21, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c0e22044ea](https://linux-hardware.org/?probe=c0e22044ea) | Feb 21, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [035b0766cc](https://linux-hardware.org/?probe=035b0766cc) | Feb 21, 2022 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | Notebook    | [9cb3e0a667](https://linux-hardware.org/?probe=9cb3e0a667) | Feb 21, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [6921a2b793](https://linux-hardware.org/?probe=6921a2b793) | Feb 21, 2022 |
| ECS           | G31T-M9                     | Desktop     | [a1c64c22b2](https://linux-hardware.org/?probe=a1c64c22b2) | Feb 21, 2022 |
| Insyde        | N116                        | Notebook    | [a6dd43dfb4](https://linux-hardware.org/?probe=a6dd43dfb4) | Feb 21, 2022 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [d4f94f7b98](https://linux-hardware.org/?probe=d4f94f7b98) | Feb 21, 2022 |
| Foxconn       | H61MXL-K                    | Desktop     | [2a9136e1ad](https://linux-hardware.org/?probe=2a9136e1ad) | Feb 21, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [62161a1c28](https://linux-hardware.org/?probe=62161a1c28) | Feb 21, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [aeba2103e0](https://linux-hardware.org/?probe=aeba2103e0) | Feb 21, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [debfe75b31](https://linux-hardware.org/?probe=debfe75b31) | Feb 21, 2022 |
| Gigabyte      | E2500N                      | Desktop     | [ca6fbcaf48](https://linux-hardware.org/?probe=ca6fbcaf48) | Feb 21, 2022 |
| ASUSTek       | Leonite2                    | Desktop     | [a90bf8db74](https://linux-hardware.org/?probe=a90bf8db74) | Feb 21, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [a4a377f7fe](https://linux-hardware.org/?probe=a4a377f7fe) | Feb 21, 2022 |
| Acer          | Extensa 2530                | Notebook    | [208565c7ea](https://linux-hardware.org/?probe=208565c7ea) | Feb 21, 2022 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [03491eae09](https://linux-hardware.org/?probe=03491eae09) | Feb 21, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c98a25e545](https://linux-hardware.org/?probe=c98a25e545) | Feb 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [aabaad1b1e](https://linux-hardware.org/?probe=aabaad1b1e) | Feb 20, 2022 |
| ASUSTek       | U24E                        | Notebook    | [c11b6b6a56](https://linux-hardware.org/?probe=c11b6b6a56) | Feb 20, 2022 |
| DEXP          | NH5BT15                     | Notebook    | [c6ef26c1ae](https://linux-hardware.org/?probe=c6ef26c1ae) | Feb 20, 2022 |
| Intel         | AB2L .A001                  | All in one  | [be0c93c06e](https://linux-hardware.org/?probe=be0c93c06e) | Feb 20, 2022 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [2164cfa14f](https://linux-hardware.org/?probe=2164cfa14f) | Feb 20, 2022 |
| MSI           | H81I                        | Desktop     | [c556e9c713](https://linux-hardware.org/?probe=c556e9c713) | Feb 20, 2022 |
| Timi          | TM1701                      | Notebook    | [587e166278](https://linux-hardware.org/?probe=587e166278) | Feb 20, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [99514a7dd5](https://linux-hardware.org/?probe=99514a7dd5) | Feb 20, 2022 |
| Lenovo        | E43                         | Notebook    | [4af9ba3590](https://linux-hardware.org/?probe=4af9ba3590) | Feb 20, 2022 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [9bdd0a91ca](https://linux-hardware.org/?probe=9bdd0a91ca) | Feb 20, 2022 |
| ASUSTek       | 1015BX                      | Notebook    | [9b3fb4a52b](https://linux-hardware.org/?probe=9b3fb4a52b) | Feb 20, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [51b531d8e7](https://linux-hardware.org/?probe=51b531d8e7) | Feb 20, 2022 |
| Notebook      | W65_W670SR                  | Notebook    | [53c885fa6e](https://linux-hardware.org/?probe=53c885fa6e) | Feb 20, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [90154b9001](https://linux-hardware.org/?probe=90154b9001) | Feb 20, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [b42d2ce48e](https://linux-hardware.org/?probe=b42d2ce48e) | Feb 20, 2022 |
| MSI           | H55M-P31                    | Desktop     | [f87bc52ff4](https://linux-hardware.org/?probe=f87bc52ff4) | Feb 20, 2022 |
| Gigabyte      | Z590M                       | Desktop     | [561cf3500e](https://linux-hardware.org/?probe=561cf3500e) | Feb 20, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [f20c485a7b](https://linux-hardware.org/?probe=f20c485a7b) | Feb 20, 2022 |
| Samsung       | R720                        | Notebook    | [c8a1e45c7f](https://linux-hardware.org/?probe=c8a1e45c7f) | Feb 20, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [4482b4bb18](https://linux-hardware.org/?probe=4482b4bb18) | Feb 20, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [e12ba75c05](https://linux-hardware.org/?probe=e12ba75c05) | Feb 19, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [263d909f47](https://linux-hardware.org/?probe=263d909f47) | Feb 19, 2022 |
| ASUSTek       | TP401CA                     | Convertible | [47c03e4dee](https://linux-hardware.org/?probe=47c03e4dee) | Feb 19, 2022 |
| Intel         | D945GCLF2 AAE46416-101      | Desktop     | [4f5fc5f5da](https://linux-hardware.org/?probe=4f5fc5f5da) | Feb 19, 2022 |
| Acer          | Aspire M1470                | Desktop     | [ff70969c70](https://linux-hardware.org/?probe=ff70969c70) | Feb 19, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [8233027724](https://linux-hardware.org/?probe=8233027724) | Feb 19, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [f41ff1607c](https://linux-hardware.org/?probe=f41ff1607c) | Feb 19, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [3bc582ad91](https://linux-hardware.org/?probe=3bc582ad91) | Feb 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [bcb0d0c077](https://linux-hardware.org/?probe=bcb0d0c077) | Feb 19, 2022 |
| MSI           | MS-B1711                    | Desktop     | [24a0b63540](https://linux-hardware.org/?probe=24a0b63540) | Feb 19, 2022 |
| HP            | Pavilion dv6                | Notebook    | [5c76391813](https://linux-hardware.org/?probe=5c76391813) | Feb 19, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [859adc5b97](https://linux-hardware.org/?probe=859adc5b97) | Feb 19, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [124b030ac3](https://linux-hardware.org/?probe=124b030ac3) | Feb 19, 2022 |
| Digma         | CITI E401 ET4007EW          | Notebook    | [a4a57f2b26](https://linux-hardware.org/?probe=a4a57f2b26) | Feb 19, 2022 |
| Pegatron      | 2A73h                       | Desktop     | [018ca406e2](https://linux-hardware.org/?probe=018ca406e2) | Feb 19, 2022 |
| MSI           | 970A-G43 PLUS               | Desktop     | [c3c6ed6429](https://linux-hardware.org/?probe=c3c6ed6429) | Feb 19, 2022 |
| MSI           | PH61-P33                    | Desktop     | [1bddbbedba](https://linux-hardware.org/?probe=1bddbbedba) | Feb 18, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [4cbc6b81bf](https://linux-hardware.org/?probe=4cbc6b81bf) | Feb 18, 2022 |
| Gigabyte      | M52L-S3P                    | Desktop     | [b8aecf78e9](https://linux-hardware.org/?probe=b8aecf78e9) | Feb 18, 2022 |
| MSI           | H81M-P33                    | Desktop     | [ee22059bf7](https://linux-hardware.org/?probe=ee22059bf7) | Feb 18, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [63a5e1d0ad](https://linux-hardware.org/?probe=63a5e1d0ad) | Feb 18, 2022 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [0c75e0962a](https://linux-hardware.org/?probe=0c75e0962a) | Feb 18, 2022 |
| ASRock        | H570M-ITX/ac                | Desktop     | [3eb9652b7e](https://linux-hardware.org/?probe=3eb9652b7e) | Feb 18, 2022 |
| Gigabyte      | B360M H                     | Desktop     | [17959e46ab](https://linux-hardware.org/?probe=17959e46ab) | Feb 18, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [14f6daa0b9](https://linux-hardware.org/?probe=14f6daa0b9) | Feb 18, 2022 |
| Huanan        | X99 F8D V2.2                | Desktop     | [b024b95162](https://linux-hardware.org/?probe=b024b95162) | Feb 18, 2022 |
| Gigabyte      | B560M DS3H                  | Desktop     | [9db1aef186](https://linux-hardware.org/?probe=9db1aef186) | Feb 18, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [37b0807b22](https://linux-hardware.org/?probe=37b0807b22) | Feb 18, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [c1b7bc8432](https://linux-hardware.org/?probe=c1b7bc8432) | Feb 18, 2022 |
| ECS           | G31T-M9                     | Desktop     | [c239ee9817](https://linux-hardware.org/?probe=c239ee9817) | Feb 17, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [866eb72e69](https://linux-hardware.org/?probe=866eb72e69) | Feb 17, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [ac7c6763e3](https://linux-hardware.org/?probe=ac7c6763e3) | Feb 17, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [42b94e096d](https://linux-hardware.org/?probe=42b94e096d) | Feb 17, 2022 |
| ASUSTek       | M5A78L                      | Desktop     | [5d05f6fc45](https://linux-hardware.org/?probe=5d05f6fc45) | Feb 17, 2022 |
| Gigabyte      | M61PME-S2                   | Desktop     | [9dca95891f](https://linux-hardware.org/?probe=9dca95891f) | Feb 17, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [7652292ba2](https://linux-hardware.org/?probe=7652292ba2) | Feb 17, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [83e6228c44](https://linux-hardware.org/?probe=83e6228c44) | Feb 17, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [87de36a11b](https://linux-hardware.org/?probe=87de36a11b) | Feb 17, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [f7f470651e](https://linux-hardware.org/?probe=f7f470651e) | Feb 17, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [dc90cd578a](https://linux-hardware.org/?probe=dc90cd578a) | Feb 17, 2022 |
| ASUSTek       | H87-PRO                     | Desktop     | [2e068751d5](https://linux-hardware.org/?probe=2e068751d5) | Feb 17, 2022 |
| ASUSTek       | H61M-E                      | Desktop     | [8500cd1a03](https://linux-hardware.org/?probe=8500cd1a03) | Feb 17, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [d0f6143b51](https://linux-hardware.org/?probe=d0f6143b51) | Feb 17, 2022 |
| HP            | 255 G4                      | Notebook    | [52e97dffc1](https://linux-hardware.org/?probe=52e97dffc1) | Feb 17, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [86257153d8](https://linux-hardware.org/?probe=86257153d8) | Feb 17, 2022 |
| ASUSTek       | M2A74-AM SE                 | Desktop     | [d8b6a265a1](https://linux-hardware.org/?probe=d8b6a265a1) | Feb 17, 2022 |
| ASUSTek       | ZenBook UX334FL_UX334FL     | Notebook    | [89c2a0f939](https://linux-hardware.org/?probe=89c2a0f939) | Feb 17, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [1b648c8fc9](https://linux-hardware.org/?probe=1b648c8fc9) | Feb 16, 2022 |
| ASRock        | G41M-VGS3                   | Desktop     | [b0d8f9faed](https://linux-hardware.org/?probe=b0d8f9faed) | Feb 16, 2022 |
| Timi          | RedmiBook 14 II             | Notebook    | [9fdad76c68](https://linux-hardware.org/?probe=9fdad76c68) | Feb 16, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [b9aeffa5f3](https://linux-hardware.org/?probe=b9aeffa5f3) | Feb 16, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [6228810562](https://linux-hardware.org/?probe=6228810562) | Feb 16, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [a1d172dbc0](https://linux-hardware.org/?probe=a1d172dbc0) | Feb 16, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [0938ea75fa](https://linux-hardware.org/?probe=0938ea75fa) | Feb 16, 2022 |
| ASRock        | G31M-GS                     | Desktop     | [8968aa239b](https://linux-hardware.org/?probe=8968aa239b) | Feb 16, 2022 |
| ASUSTek       | 1005PXD                     | Notebook    | [b454702c84](https://linux-hardware.org/?probe=b454702c84) | Feb 16, 2022 |
| ASRock        | 760GM-HDV                   | Desktop     | [c561b5d4a6](https://linux-hardware.org/?probe=c561b5d4a6) | Feb 16, 2022 |
| HP            | ENVY dv7                    | Notebook    | [64d7869867](https://linux-hardware.org/?probe=64d7869867) | Feb 16, 2022 |
| Lenovo        | V580c 20160                 | Notebook    | [94bc64002a](https://linux-hardware.org/?probe=94bc64002a) | Feb 16, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [e5e7379587](https://linux-hardware.org/?probe=e5e7379587) | Feb 16, 2022 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [357bc81fab](https://linux-hardware.org/?probe=357bc81fab) | Feb 16, 2022 |
| Intel         | DH61CR AAG14064-202         | Desktop     | [6a470e1659](https://linux-hardware.org/?probe=6a470e1659) | Feb 16, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [f0f81900f5](https://linux-hardware.org/?probe=f0f81900f5) | Feb 16, 2022 |
| HP            | Laptop 14s-dq3xxx           | Notebook    | [81c6849a8d](https://linux-hardware.org/?probe=81c6849a8d) | Feb 15, 2022 |
| ASUSTek       | F2A55-M LK                  | Desktop     | [131de7d020](https://linux-hardware.org/?probe=131de7d020) | Feb 15, 2022 |
| iRU           | J231                        | All in one  | [8259fb58ce](https://linux-hardware.org/?probe=8259fb58ce) | Feb 15, 2022 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [28c2882750](https://linux-hardware.org/?probe=28c2882750) | Feb 15, 2022 |
| Lenovo        | ThinkPad X200T 7449G6G      | Notebook    | [9a9f646438](https://linux-hardware.org/?probe=9a9f646438) | Feb 15, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [227a2658d0](https://linux-hardware.org/?probe=227a2658d0) | Feb 15, 2022 |
| ASUSTek       | V221ID                      | All in one  | [ef42b78dc5](https://linux-hardware.org/?probe=ef42b78dc5) | Feb 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [890fea8813](https://linux-hardware.org/?probe=890fea8813) | Feb 15, 2022 |
| Acer          | E1-510                      | Notebook    | [0120aaf250](https://linux-hardware.org/?probe=0120aaf250) | Feb 15, 2022 |
| Acer          | E1-510                      | Notebook    | [7a3678f7d1](https://linux-hardware.org/?probe=7a3678f7d1) | Feb 15, 2022 |
| Acer          | Aspire A315-35              | Notebook    | [9986615814](https://linux-hardware.org/?probe=9986615814) | Feb 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3986a62bca](https://linux-hardware.org/?probe=3986a62bca) | Feb 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [e8455d8225](https://linux-hardware.org/?probe=e8455d8225) | Feb 15, 2022 |
| ECS           | A740GM-M                    | Desktop     | [f8ac8fed60](https://linux-hardware.org/?probe=f8ac8fed60) | Feb 15, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [3a32b98a30](https://linux-hardware.org/?probe=3a32b98a30) | Feb 15, 2022 |
| MSI           | 970A-G43                    | Desktop     | [ee48ba78a8](https://linux-hardware.org/?probe=ee48ba78a8) | Feb 15, 2022 |
| MSI           | GP72M 7RDX                  | Notebook    | [2a55fc3b23](https://linux-hardware.org/?probe=2a55fc3b23) | Feb 15, 2022 |
| ASUSTek       | M4A785T-M                   | Desktop     | [f5e313fff6](https://linux-hardware.org/?probe=f5e313fff6) | Feb 14, 2022 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [e9fdc5bbc4](https://linux-hardware.org/?probe=e9fdc5bbc4) | Feb 14, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [40f0863805](https://linux-hardware.org/?probe=40f0863805) | Feb 14, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [6f8f7c786e](https://linux-hardware.org/?probe=6f8f7c786e) | Feb 14, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [4fb06cfe97](https://linux-hardware.org/?probe=4fb06cfe97) | Feb 14, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [b4c976a541](https://linux-hardware.org/?probe=b4c976a541) | Feb 14, 2022 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [6c1363e7b7](https://linux-hardware.org/?probe=6c1363e7b7) | Feb 14, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [64f2e3e9ce](https://linux-hardware.org/?probe=64f2e3e9ce) | Feb 14, 2022 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [bfadfad800](https://linux-hardware.org/?probe=bfadfad800) | Feb 14, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [3496364e83](https://linux-hardware.org/?probe=3496364e83) | Feb 14, 2022 |
| ASUSTek       | Z97-PRO                     | Desktop     | [7da7e083a2](https://linux-hardware.org/?probe=7da7e083a2) | Feb 14, 2022 |
| ASUSTek       | M2NPV-VM                    | Desktop     | [1c60918a3d](https://linux-hardware.org/?probe=1c60918a3d) | Feb 14, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [2effd1e9c6](https://linux-hardware.org/?probe=2effd1e9c6) | Feb 14, 2022 |
| Pegatron      | 2A73h                       | Desktop     | [ca29e05afe](https://linux-hardware.org/?probe=ca29e05afe) | Feb 14, 2022 |
| Pegatron      | 2A73h                       | Desktop     | [fa19ca0049](https://linux-hardware.org/?probe=fa19ca0049) | Feb 14, 2022 |
| Dell          | Inspiron 3558               | Notebook    | [9a70b72ce5](https://linux-hardware.org/?probe=9a70b72ce5) | Feb 13, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [eba09c169c](https://linux-hardware.org/?probe=eba09c169c) | Feb 13, 2022 |
| ASUSTek       | 1011PX                      | Notebook    | [81437151b6](https://linux-hardware.org/?probe=81437151b6) | Feb 13, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [7a19abc29f](https://linux-hardware.org/?probe=7a19abc29f) | Feb 13, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [92eab3e301](https://linux-hardware.org/?probe=92eab3e301) | Feb 13, 2022 |
| HP            | G7000                       | Notebook    | [77d8f165c0](https://linux-hardware.org/?probe=77d8f165c0) | Feb 13, 2022 |
| Lenovo        | IdeaPad 730S-13IWL 81JB     | Notebook    | [98d7355c52](https://linux-hardware.org/?probe=98d7355c52) | Feb 13, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [39b082fe06](https://linux-hardware.org/?probe=39b082fe06) | Feb 13, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [085add9a8c](https://linux-hardware.org/?probe=085add9a8c) | Feb 13, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [ab412a55d6](https://linux-hardware.org/?probe=ab412a55d6) | Feb 13, 2022 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [cebe791ff7](https://linux-hardware.org/?probe=cebe791ff7) | Feb 13, 2022 |
| Gigabyte      | H510M S2H V2                | Desktop     | [25ae1cdef0](https://linux-hardware.org/?probe=25ae1cdef0) | Feb 13, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [9078420067](https://linux-hardware.org/?probe=9078420067) | Feb 13, 2022 |
| Lenovo        | ThinkPad P50 20EQS0VV02     | Notebook    | [7a7b9fa959](https://linux-hardware.org/?probe=7a7b9fa959) | Feb 13, 2022 |
| HP            | ProBook 4535s               | Notebook    | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [c970d00ddd](https://linux-hardware.org/?probe=c970d00ddd) | Feb 12, 2022 |
| ASUSTek       | P5K                         | Desktop     | [b6d1577be5](https://linux-hardware.org/?probe=b6d1577be5) | Feb 12, 2022 |
| HP            | Pavilion 15                 | Notebook    | [01960d4a72](https://linux-hardware.org/?probe=01960d4a72) | Feb 12, 2022 |
| Gigabyte      | H97M-HD3                    | Desktop     | [46b9019417](https://linux-hardware.org/?probe=46b9019417) | Feb 12, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [39e19c2b14](https://linux-hardware.org/?probe=39e19c2b14) | Feb 12, 2022 |
| ASUSTek       | N751JK                      | Notebook    | [aed08889fc](https://linux-hardware.org/?probe=aed08889fc) | Feb 12, 2022 |
| ASUSTek       | K52F                        | Notebook    | [46e3780be8](https://linux-hardware.org/?probe=46e3780be8) | Feb 12, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [e31651076d](https://linux-hardware.org/?probe=e31651076d) | Feb 12, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [44da109aed](https://linux-hardware.org/?probe=44da109aed) | Feb 12, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [5795d9b341](https://linux-hardware.org/?probe=5795d9b341) | Feb 12, 2022 |
| Acer          | Extensa 2511G               | Notebook    | [c1cd812a42](https://linux-hardware.org/?probe=c1cd812a42) | Feb 12, 2022 |
| ASUSTek       | ROG STRIX B560-E GAMING ... | Desktop     | [9b5ea5d470](https://linux-hardware.org/?probe=9b5ea5d470) | Feb 12, 2022 |
| Gigabyte      | X79-UD3                     | Desktop     | [452ebf6a67](https://linux-hardware.org/?probe=452ebf6a67) | Feb 12, 2022 |
| HP            | 09F8h                       | Desktop     | [a3d99bd1ad](https://linux-hardware.org/?probe=a3d99bd1ad) | Feb 12, 2022 |
| HP            | 255 G4                      | Notebook    | [9ee2c88cb4](https://linux-hardware.org/?probe=9ee2c88cb4) | Feb 12, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [d601a2b4ee](https://linux-hardware.org/?probe=d601a2b4ee) | Feb 12, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [92246486de](https://linux-hardware.org/?probe=92246486de) | Feb 12, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [2c41d85640](https://linux-hardware.org/?probe=2c41d85640) | Feb 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [921e224ec5](https://linux-hardware.org/?probe=921e224ec5) | Feb 12, 2022 |
| ASUSTek       | X200MA                      | Notebook    | [b2f1d59884](https://linux-hardware.org/?probe=b2f1d59884) | Feb 12, 2022 |
| ASUSTek       | P5P43TD                     | Desktop     | [d1aaa12f3c](https://linux-hardware.org/?probe=d1aaa12f3c) | Feb 12, 2022 |
| ASRock        | P43DE3                      | Desktop     | [a90b00597e](https://linux-hardware.org/?probe=a90b00597e) | Feb 12, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [469a5d773b](https://linux-hardware.org/?probe=469a5d773b) | Feb 12, 2022 |
| HUAWEI        | HLY-WX9XX                   | Notebook    | [4e250e6a7e](https://linux-hardware.org/?probe=4e250e6a7e) | Feb 11, 2022 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [8a37ffb80e](https://linux-hardware.org/?probe=8a37ffb80e) | Feb 11, 2022 |
| MSI           | MS-7345                     | Desktop     | [3bbbb89ce1](https://linux-hardware.org/?probe=3bbbb89ce1) | Feb 11, 2022 |
| Pegatron      | E60                         | Desktop     | [ea6a720ebf](https://linux-hardware.org/?probe=ea6a720ebf) | Feb 11, 2022 |
| Pegatron      | E60                         | Desktop     | [cb064b517f](https://linux-hardware.org/?probe=cb064b517f) | Feb 11, 2022 |
| ASRock        | J4205-ITX                   | Desktop     | [1decffbafb](https://linux-hardware.org/?probe=1decffbafb) | Feb 11, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [a814e7ba37](https://linux-hardware.org/?probe=a814e7ba37) | Feb 11, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [c8ff899a05](https://linux-hardware.org/?probe=c8ff899a05) | Feb 11, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [9b7b4aa697](https://linux-hardware.org/?probe=9b7b4aa697) | Feb 11, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [a8d3ef29f1](https://linux-hardware.org/?probe=a8d3ef29f1) | Feb 11, 2022 |
| Lenovo        | ThinkPad SL410 2842RN9      | Notebook    | [c0180c17d9](https://linux-hardware.org/?probe=c0180c17d9) | Feb 11, 2022 |
| ASUSTek       | N61Vn                       | Notebook    | [a933b77b15](https://linux-hardware.org/?probe=a933b77b15) | Feb 11, 2022 |
| Lenovo        | ThinkPad X230 2325V4D       | Notebook    | [a6d2aed78b](https://linux-hardware.org/?probe=a6d2aed78b) | Feb 11, 2022 |
| Gigabyte      | B360M H                     | Desktop     | [565dc78c67](https://linux-hardware.org/?probe=565dc78c67) | Feb 11, 2022 |
| Lenovo        | ThinkPad X230 2325V4D       | Notebook    | [48f266c11e](https://linux-hardware.org/?probe=48f266c11e) | Feb 11, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [4c500fd383](https://linux-hardware.org/?probe=4c500fd383) | Feb 11, 2022 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [8b6707f9c9](https://linux-hardware.org/?probe=8b6707f9c9) | Feb 11, 2022 |
| MSI           | GP60 2OD                    | Notebook    | [dce2436e3a](https://linux-hardware.org/?probe=dce2436e3a) | Feb 11, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [3055523150](https://linux-hardware.org/?probe=3055523150) | Feb 11, 2022 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [3ac8f883ab](https://linux-hardware.org/?probe=3ac8f883ab) | Feb 11, 2022 |
| HONOR         | HLYL-WXX9                   | Notebook    | [56b8d26422](https://linux-hardware.org/?probe=56b8d26422) | Feb 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [046ea2d5dc](https://linux-hardware.org/?probe=046ea2d5dc) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | Notebook    | [14ba525422](https://linux-hardware.org/?probe=14ba525422) | Feb 10, 2022 |
| ASUSTek       | B75M-A                      | Desktop     | [f9377b6de3](https://linux-hardware.org/?probe=f9377b6de3) | Feb 10, 2022 |
| ASUSTek       | A58M-K                      | Desktop     | [340256ddb2](https://linux-hardware.org/?probe=340256ddb2) | Feb 10, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [e0619a1fd7](https://linux-hardware.org/?probe=e0619a1fd7) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [3fe8db326e](https://linux-hardware.org/?probe=3fe8db326e) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [b6494cc86c](https://linux-hardware.org/?probe=b6494cc86c) | Feb 10, 2022 |
| Timi          | RedmiBook 14 II             | Notebook    | [3c1248a9d9](https://linux-hardware.org/?probe=3c1248a9d9) | Feb 10, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [44a8558637](https://linux-hardware.org/?probe=44a8558637) | Feb 10, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [6edb773462](https://linux-hardware.org/?probe=6edb773462) | Feb 10, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [c010a2df07](https://linux-hardware.org/?probe=c010a2df07) | Feb 10, 2022 |
| ASUSTek       | P5B SE                      | Desktop     | [cf067d000a](https://linux-hardware.org/?probe=cf067d000a) | Feb 10, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [3643285f59](https://linux-hardware.org/?probe=3643285f59) | Feb 09, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [698e174402](https://linux-hardware.org/?probe=698e174402) | Feb 09, 2022 |
| MSI           | 970A-G43                    | Desktop     | [9675bd9aaa](https://linux-hardware.org/?probe=9675bd9aaa) | Feb 09, 2022 |
| Acer          | Extensa 2540                | Notebook    | [f4d594d720](https://linux-hardware.org/?probe=f4d594d720) | Feb 09, 2022 |
| HONOR         | NBD-WXX9                    | Notebook    | [83ab33660d](https://linux-hardware.org/?probe=83ab33660d) | Feb 09, 2022 |
| HONOR         | NBD-WXX9                    | Notebook    | [52bec77385](https://linux-hardware.org/?probe=52bec77385) | Feb 09, 2022 |
| ASRock        | G31M-VS2                    | Desktop     | [9ec5d393d6](https://linux-hardware.org/?probe=9ec5d393d6) | Feb 09, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [516754657f](https://linux-hardware.org/?probe=516754657f) | Feb 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d31f5e23d5](https://linux-hardware.org/?probe=d31f5e23d5) | Feb 09, 2022 |
| Huanan        | X99-F8                      | Desktop     | [b8d5df2c09](https://linux-hardware.org/?probe=b8d5df2c09) | Feb 09, 2022 |
| Lenovo        | Aptio CRB No DPK            | Mini pc     | [bd46c4bac3](https://linux-hardware.org/?probe=bd46c4bac3) | Feb 09, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [ee510b7924](https://linux-hardware.org/?probe=ee510b7924) | Feb 09, 2022 |
| eMachines     | eME728                      | Notebook    | [345b9ef3cd](https://linux-hardware.org/?probe=345b9ef3cd) | Feb 09, 2022 |
| HONOR         | NMH-WCX9                    | Notebook    | [854a761f9f](https://linux-hardware.org/?probe=854a761f9f) | Feb 09, 2022 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [ba54a33408](https://linux-hardware.org/?probe=ba54a33408) | Feb 09, 2022 |
| Prestigio     | Multipad Visconte V         | Notebook    | [2c20ec8149](https://linux-hardware.org/?probe=2c20ec8149) | Feb 09, 2022 |
| eMachines     | D620                        | Notebook    | [db4b538b87](https://linux-hardware.org/?probe=db4b538b87) | Feb 09, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [40808dc413](https://linux-hardware.org/?probe=40808dc413) | Feb 08, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [5e040d4846](https://linux-hardware.org/?probe=5e040d4846) | Feb 08, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [9f05ddfb03](https://linux-hardware.org/?probe=9f05ddfb03) | Feb 08, 2022 |
| ASRock        | H55M-LE                     | Desktop     | [4d4434a1ae](https://linux-hardware.org/?probe=4d4434a1ae) | Feb 08, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [55fda8de04](https://linux-hardware.org/?probe=55fda8de04) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [2656f9019e](https://linux-hardware.org/?probe=2656f9019e) | Feb 08, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [bf3e4dae03](https://linux-hardware.org/?probe=bf3e4dae03) | Feb 08, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [d0e07d420c](https://linux-hardware.org/?probe=d0e07d420c) | Feb 08, 2022 |
| ECS           | MCP61M-M3                   | Desktop     | [3e1e057d1f](https://linux-hardware.org/?probe=3e1e057d1f) | Feb 08, 2022 |
| Acer          | Aspire V5-121               | Notebook    | [d0e38ff5e5](https://linux-hardware.org/?probe=d0e38ff5e5) | Feb 08, 2022 |
| MSI           | G41M-P28                    | Desktop     | [bf1ae3ecc9](https://linux-hardware.org/?probe=bf1ae3ecc9) | Feb 08, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [49cf4eba76](https://linux-hardware.org/?probe=49cf4eba76) | Feb 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | Notebook    | [fc5afec8d7](https://linux-hardware.org/?probe=fc5afec8d7) | Feb 08, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ea7fe617bc](https://linux-hardware.org/?probe=ea7fe617bc) | Feb 08, 2022 |
| MSI           | 760GM-P21                   | Desktop     | [2d1f440712](https://linux-hardware.org/?probe=2d1f440712) | Feb 08, 2022 |
| Intel         | D945GNT AAC96315-405        | Desktop     | [050a95af06](https://linux-hardware.org/?probe=050a95af06) | Feb 08, 2022 |
| Acer          | Aspire E1-571G              | Notebook    | [6db3ca9f6d](https://linux-hardware.org/?probe=6db3ca9f6d) | Feb 08, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [0600816ba9](https://linux-hardware.org/?probe=0600816ba9) | Feb 08, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [4b6abf8148](https://linux-hardware.org/?probe=4b6abf8148) | Feb 08, 2022 |
| HP            | ProBook 4520s               | Notebook    | [76f916dd4d](https://linux-hardware.org/?probe=76f916dd4d) | Feb 08, 2022 |
| eMachines     | eME728                      | Notebook    | [c04471203f](https://linux-hardware.org/?probe=c04471203f) | Feb 08, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [e159605a22](https://linux-hardware.org/?probe=e159605a22) | Feb 08, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [7c09c25b46](https://linux-hardware.org/?probe=7c09c25b46) | Feb 08, 2022 |
| HP            | 339A                        | Desktop     | [eccd4901fd](https://linux-hardware.org/?probe=eccd4901fd) | Feb 08, 2022 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [02fcb19f44](https://linux-hardware.org/?probe=02fcb19f44) | Feb 08, 2022 |
| Acer          | Aspire A515-52G             | Notebook    | [01b863976d](https://linux-hardware.org/?probe=01b863976d) | Feb 08, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [24a7621237](https://linux-hardware.org/?probe=24a7621237) | Feb 08, 2022 |
| ASRock        | J4125M                      | Desktop     | [fa6797fc35](https://linux-hardware.org/?probe=fa6797fc35) | Feb 08, 2022 |
| Gigabyte      | EP43-DS3L                   | Desktop     | [869ae4b0e8](https://linux-hardware.org/?probe=869ae4b0e8) | Feb 08, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [5b8ad7499b](https://linux-hardware.org/?probe=5b8ad7499b) | Feb 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3ce22a5559](https://linux-hardware.org/?probe=3ce22a5559) | Feb 07, 2022 |
| Dell          | Inspiron 17-7778            | Notebook    | [5713c1770f](https://linux-hardware.org/?probe=5713c1770f) | Feb 07, 2022 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [8291648326](https://linux-hardware.org/?probe=8291648326) | Feb 07, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [b21be94001](https://linux-hardware.org/?probe=b21be94001) | Feb 07, 2022 |
| ASUSTek       | AM1I-A                      | Desktop     | [5f6867fad7](https://linux-hardware.org/?probe=5f6867fad7) | Feb 07, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [c0ddaf9205](https://linux-hardware.org/?probe=c0ddaf9205) | Feb 07, 2022 |
| Gigabyte      | Z170-HD3-CF                 | Desktop     | [f570e38ccd](https://linux-hardware.org/?probe=f570e38ccd) | Feb 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [05e8132fd3](https://linux-hardware.org/?probe=05e8132fd3) | Feb 07, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [2e1512ed5d](https://linux-hardware.org/?probe=2e1512ed5d) | Feb 07, 2022 |
| MSI           | 970A-G46                    | Desktop     | [b31d6b3fdb](https://linux-hardware.org/?probe=b31d6b3fdb) | Feb 07, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [9a0a4874ac](https://linux-hardware.org/?probe=9a0a4874ac) | Feb 07, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [7d8714b9f8](https://linux-hardware.org/?probe=7d8714b9f8) | Feb 07, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [b2bc043c0b](https://linux-hardware.org/?probe=b2bc043c0b) | Feb 07, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [20b4867308](https://linux-hardware.org/?probe=20b4867308) | Feb 07, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [292fa356f7](https://linux-hardware.org/?probe=292fa356f7) | Feb 07, 2022 |
| ASUSTek       | P7H55                       | Desktop     | [1ac17e6259](https://linux-hardware.org/?probe=1ac17e6259) | Feb 07, 2022 |
| Inventec      | DQ Class A02                | Desktop     | [07853bea89](https://linux-hardware.org/?probe=07853bea89) | Feb 07, 2022 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [87ed1a4a22](https://linux-hardware.org/?probe=87ed1a4a22) | Feb 07, 2022 |
| ASUSTek       | 1225C                       | Notebook    | [b780589dd0](https://linux-hardware.org/?probe=b780589dd0) | Feb 07, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [b1d68da487](https://linux-hardware.org/?probe=b1d68da487) | Feb 07, 2022 |
| Notebook      | WA50SRQ                     | Notebook    | [d7188c65fe](https://linux-hardware.org/?probe=d7188c65fe) | Feb 07, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [21b0ce3a44](https://linux-hardware.org/?probe=21b0ce3a44) | Feb 06, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [2e55ebbf9f](https://linux-hardware.org/?probe=2e55ebbf9f) | Feb 06, 2022 |
| HP            | ProBook 4520s               | Notebook    | [4d0ca52180](https://linux-hardware.org/?probe=4d0ca52180) | Feb 06, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [546b3e4c0b](https://linux-hardware.org/?probe=546b3e4c0b) | Feb 06, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [88146657b7](https://linux-hardware.org/?probe=88146657b7) | Feb 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [87c57369ab](https://linux-hardware.org/?probe=87c57369ab) | Feb 06, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [dcdaeb15ce](https://linux-hardware.org/?probe=dcdaeb15ce) | Feb 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [fcff45ddb4](https://linux-hardware.org/?probe=fcff45ddb4) | Feb 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [b75541868b](https://linux-hardware.org/?probe=b75541868b) | Feb 06, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [6d6a3d2ac4](https://linux-hardware.org/?probe=6d6a3d2ac4) | Feb 06, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [b9e58087b7](https://linux-hardware.org/?probe=b9e58087b7) | Feb 05, 2022 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [cced3f9eec](https://linux-hardware.org/?probe=cced3f9eec) | Feb 05, 2022 |
| HP            | Pavilion dv6                | Notebook    | [9d6680df17](https://linux-hardware.org/?probe=9d6680df17) | Feb 05, 2022 |
| ASUSTek       | M4N68T                      | Desktop     | [5052fa9dac](https://linux-hardware.org/?probe=5052fa9dac) | Feb 05, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [cd81e5ce82](https://linux-hardware.org/?probe=cd81e5ce82) | Feb 05, 2022 |
| Acer          | Extensa 2519                | Notebook    | [6ac9948350](https://linux-hardware.org/?probe=6ac9948350) | Feb 05, 2022 |
| Timi          | TM1701                      | Notebook    | [4edeb14964](https://linux-hardware.org/?probe=4edeb14964) | Feb 05, 2022 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [5256293dec](https://linux-hardware.org/?probe=5256293dec) | Feb 05, 2022 |
| Acer          | Aspire 5610                 | Notebook    | [fb5b6d4c90](https://linux-hardware.org/?probe=fb5b6d4c90) | Feb 05, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [731f4c84e6](https://linux-hardware.org/?probe=731f4c84e6) | Feb 05, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [b3ba3d3112](https://linux-hardware.org/?probe=b3ba3d3112) | Feb 04, 2022 |
| HP            | Mini 110-3500               | Notebook    | [c64c9ca5ce](https://linux-hardware.org/?probe=c64c9ca5ce) | Feb 04, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [25fa8ea018](https://linux-hardware.org/?probe=25fa8ea018) | Feb 04, 2022 |
| Samsung       | R40/R41                     | Notebook    | [b53c8e5ef4](https://linux-hardware.org/?probe=b53c8e5ef4) | Feb 04, 2022 |
| ASUSTek       | P5P41D                      | Desktop     | [d7264306f6](https://linux-hardware.org/?probe=d7264306f6) | Feb 04, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [8d4968c10a](https://linux-hardware.org/?probe=8d4968c10a) | Feb 04, 2022 |
| ASUSTek       | K53E                        | Notebook    | [7e4a0fcc49](https://linux-hardware.org/?probe=7e4a0fcc49) | Feb 04, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [84e2ee1e04](https://linux-hardware.org/?probe=84e2ee1e04) | Feb 04, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [1831792a32](https://linux-hardware.org/?probe=1831792a32) | Feb 04, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [6214ebbf3e](https://linux-hardware.org/?probe=6214ebbf3e) | Feb 04, 2022 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [5c841a935a](https://linux-hardware.org/?probe=5c841a935a) | Feb 04, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [fa05c49b58](https://linux-hardware.org/?probe=fa05c49b58) | Feb 04, 2022 |
| Samsung       | QX310/QX410/QX510/SF310/... | Notebook    | [adb5d9b8b9](https://linux-hardware.org/?probe=adb5d9b8b9) | Feb 04, 2022 |
| Gigabyte      | Z490 UD                     | Desktop     | [b571c22d4f](https://linux-hardware.org/?probe=b571c22d4f) | Feb 04, 2022 |
| Dell          | Latitude E4310              | Notebook    | [d4816ebcdc](https://linux-hardware.org/?probe=d4816ebcdc) | Feb 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [eed6d95df2](https://linux-hardware.org/?probe=eed6d95df2) | Feb 03, 2022 |
| Dell          | G7 7700                     | Notebook    | [1edff1ad2b](https://linux-hardware.org/?probe=1edff1ad2b) | Feb 03, 2022 |
| Intel         | NUC10i5FNB K61361-306       | Mini pc     | [0d9b753498](https://linux-hardware.org/?probe=0d9b753498) | Feb 03, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [8c7268f192](https://linux-hardware.org/?probe=8c7268f192) | Feb 03, 2022 |
| DEPO Compu... | DPC156                      | Notebook    | [4fb49336e5](https://linux-hardware.org/?probe=4fb49336e5) | Feb 03, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [075f4c7c9d](https://linux-hardware.org/?probe=075f4c7c9d) | Feb 03, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [182aaf7542](https://linux-hardware.org/?probe=182aaf7542) | Feb 03, 2022 |
| Dell          | G7 7700                     | Notebook    | [4b9b8ca3cf](https://linux-hardware.org/?probe=4b9b8ca3cf) | Feb 02, 2022 |
| HP            | 872E                        | Mini pc     | [8366a84cdb](https://linux-hardware.org/?probe=8366a84cdb) | Feb 02, 2022 |
| HP            | 872E                        | Mini pc     | [533e06f8ac](https://linux-hardware.org/?probe=533e06f8ac) | Feb 02, 2022 |
| Fujitsu       | LIFEBOOK T734               | Notebook    | [652d71c771](https://linux-hardware.org/?probe=652d71c771) | Feb 02, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7808ed67c3](https://linux-hardware.org/?probe=7808ed67c3) | Feb 02, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [edcd28a541](https://linux-hardware.org/?probe=edcd28a541) | Feb 02, 2022 |
| Pegatron      | 2A73h                       | Desktop     | [b31d0806f5](https://linux-hardware.org/?probe=b31d0806f5) | Feb 02, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [dace307da3](https://linux-hardware.org/?probe=dace307da3) | Feb 02, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | Desktop     | [bb7c4c5854](https://linux-hardware.org/?probe=bb7c4c5854) | Feb 02, 2022 |
| HP            | Pavilion g7                 | Notebook    | [520f4ed91f](https://linux-hardware.org/?probe=520f4ed91f) | Feb 02, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [91c6112da4](https://linux-hardware.org/?probe=91c6112da4) | Feb 02, 2022 |
| HP            | Pavilion g7                 | Notebook    | [7ff4adf123](https://linux-hardware.org/?probe=7ff4adf123) | Feb 02, 2022 |
| Unknown       | X99H                        | Desktop     | [29bd27d08f](https://linux-hardware.org/?probe=29bd27d08f) | Feb 02, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [71569beb05](https://linux-hardware.org/?probe=71569beb05) | Feb 02, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [f267f7d8d6](https://linux-hardware.org/?probe=f267f7d8d6) | Feb 02, 2022 |
| Toshiba       | Satellite L850D-BJS         | Notebook    | [d3897cf605](https://linux-hardware.org/?probe=d3897cf605) | Feb 02, 2022 |
| Toshiba       | Satellite C850-C3K          | Notebook    | [9b7c25ddbc](https://linux-hardware.org/?probe=9b7c25ddbc) | Feb 02, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [443b05e506](https://linux-hardware.org/?probe=443b05e506) | Feb 01, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [5d4dc0566d](https://linux-hardware.org/?probe=5d4dc0566d) | Feb 01, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [f49bc45f96](https://linux-hardware.org/?probe=f49bc45f96) | Feb 01, 2022 |
| ASUSTek       | P8H67-M LX                  | Desktop     | [5e92f5c961](https://linux-hardware.org/?probe=5e92f5c961) | Feb 01, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c1f9ad0faf](https://linux-hardware.org/?probe=c1f9ad0faf) | Feb 01, 2022 |
| T-Platform... | TF307-MB                    | Soc         | [c34cd190e4](https://linux-hardware.org/?probe=c34cd190e4) | Feb 01, 2022 |
| Lenovo        | IdeaPad Z470                | Notebook    | [63443cfe31](https://linux-hardware.org/?probe=63443cfe31) | Feb 01, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Russia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| ROSA R10                     | 3114      | 13.52%  |
| ROSA R11                     | 3102      | 13.47%  |
| ROSA R8.1                    | 2217      | 9.63%   |
| ROSA R8                      | 1995      | 8.66%   |
| ROSA R9                      | 1813      | 7.87%   |
| ROSA R11.1                   | 1559      | 6.77%   |
| ROSA 12.2                    | 847       | 3.68%   |
| Ubuntu 20.04                 | 799       | 3.47%   |
| Debian 11                    | 588       | 2.55%   |
| Ubuntu 18.04                 | 477       | 2.07%   |
| OpenMandriva 4.2             | 382       | 1.66%   |
| ROSA 12.1                    | 233       | 1.01%   |
| KDE neon 20.04               | 176       | 0.76%   |
| Debian 10                    | 166       | 0.72%   |
| Kometa P10                   | 165       | 0.72%   |
| Arch                         | 152       | 0.66%   |
| Arch Rolling                 | 140       | 0.61%   |
| ROSA 12                      | 130       | 0.56%   |
| Linux Mint 19.3              | 127       | 0.55%   |
| OpenMandriva 4.3             | 119       | 0.52%   |
| Linux Mint 18.3              | 111       | 0.48%   |
| Kubuntu 20.04                | 111       | 0.48%   |
| Fedora 35                    | 107       | 0.46%   |
| Manjaro                      | 106       | 0.46%   |
| Linux Mint 20.1              | 106       | 0.46%   |
| Linux Mint 19.1              | 105       | 0.46%   |
| Linux Mint 20                | 90        | 0.39%   |
| RED X3                       | 86        | 0.37%   |
| Linux Mint 19.2              | 86        | 0.37%   |
| Fedora 34                    | 84        | 0.36%   |
| Linux Mint 20.2              | 82        | 0.36%   |
| Ubuntu 19.10                 | 79        | 0.34%   |
| Xubuntu 18.04                | 78        | 0.34%   |
| Linux Mint 19                | 76        | 0.33%   |
| Xubuntu 20.04                | 74        | 0.32%   |
| Ubuntu 21.10                 | 73        | 0.32%   |
| Ubuntu 20.10                 | 70        | 0.3%    |
| ROSA R7                      | 70        | 0.3%    |
| Fedora 33                    | 69        | 0.3%    |
| Fedora 32                    | 69        | 0.3%    |
| Ubuntu 21.04                 | 68        | 0.3%    |
| RED X4                       | 68        | 0.3%    |
| Linux Mint 20.3              | 67        | 0.29%   |
| ALT Linux 9.1                | 64        | 0.28%   |
| ROSA R12                     | 62        | 0.27%   |
| Ubuntu 16.04                 | 60        | 0.26%   |
| Ubuntu 19.04                 | 56        | 0.24%   |
| Gentoo 2.7                   | 51        | 0.22%   |
| Manjaro 20.2.1               | 44        | 0.19%   |
| Manjaro 20.0                 | 43        | 0.19%   |
| Debian 9                     | 43        | 0.19%   |
| OpenMandriva 4.50            | 42        | 0.18%   |
| openSUSE Tumbleweed-XXXXXXXX | 38        | 0.16%   |
| Fedora 31                    | 38        | 0.16%   |
| ROSA R6                      | 37        | 0.16%   |
| CentOS 7                     | 37        | 0.16%   |
| Pop!_OS 20.04                | 36        | 0.16%   |
| Debian Testing               | 35        | 0.15%   |
| Ubuntu 22.04                 | 33        | 0.14%   |
| Gentoo 2.6                   | 31        | 0.13%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| ROSA          | 13062     | 63.7%   |
| Ubuntu        | 1695      | 8.27%   |
| Linux Mint    | 840       | 4.1%    |
| Debian        | 838       | 4.09%   |
| OpenMandriva  | 543       | 2.65%   |
| Manjaro       | 477       | 2.33%   |
| Fedora        | 400       | 1.95%   |
| ALT Linux     | 334       | 1.63%   |
| Arch          | 286       | 1.39%   |
| Endless       | 276       | 1.35%   |
| KDE neon      | 205       | 1%      |
| Kubuntu       | 199       | 0.97%   |
| Xubuntu       | 179       | 0.87%   |
| RED           | 163       | 0.79%   |
| Pop!_OS       | 109       | 0.53%   |
| Gentoo        | 94        | 0.46%   |
| openSUSE      | 66        | 0.32%   |
| Clear Linux   | 52        | 0.25%   |
| CentOS        | 52        | 0.25%   |
| Red OS        | 51        | 0.25%   |
| Elementary    | 51        | 0.25%   |
| Ubuntu MATE   | 50        | 0.24%   |
| Lubuntu       | 48        | 0.23%   |
| Zorin         | 42        | 0.2%    |
| Kali          | 42        | 0.2%    |
| RELS          | 41        | 0.2%    |
| LMDE          | 29        | 0.14%   |
| ArcoLinux     | 21        | 0.1%    |
| Astra Linux   | 15        | 0.07%   |
| Ubuntu Budgie | 13        | 0.06%   |
| Calculate     | 13        | 0.06%   |
| MX            | 12        | 0.06%   |
| PCS           | 11        | 0.05%   |
| Cyber Infra   | 10        | 0.05%   |
| Artix         | 10        | 0.05%   |
| Parrot        | 9         | 0.04%   |
| Devuan        | 9         | 0.04%   |
| Alpine        | 9         | 0.04%   |
| Void Linux    | 8         | 0.04%   |
| Virtuozzo     | 8         | 0.04%   |
| Raspbian      | 8         | 0.04%   |
| EndeavourOS   | 8         | 0.04%   |
| BlackPanther  | 8         | 0.04%   |
| Solus         | 7         | 0.03%   |
| Reborn OS     | 6         | 0.03%   |
| Peppermint    | 6         | 0.03%   |
| antergos      | 6         | 0.03%   |
| NixOS         | 5         | 0.02%   |
| Garuda Linux  | 5         | 0.02%   |
| Deepin        | 5         | 0.02%   |
| antiX         | 5         | 0.02%   |
| Slackware     | 4         | 0.02%   |
| RHEL          | 4         | 0.02%   |
| PostmarketOS  | 3         | 0.01%   |
| Parabola      | 3         | 0.01%   |
| Mageia        | 3         | 0.01%   |
| Linux Lite    | 3         | 0.01%   |
| Ubuntu Studio | 2         | 0.01%   |
| SLES          | 2         | 0.01%   |
| Rocky Linux   | 2         | 0.01%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 1356      | 5.48%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 1342      | 5.42%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 1279      | 5.17%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 974       | 3.94%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 761       | 3.08%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 619       | 2.5%    |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 558       | 2.26%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 545       | 2.2%    |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 476       | 1.92%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 394       | 1.59%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 391       | 1.58%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 377       | 1.52%   |
| 5.10.0-7-amd64                      | 373       | 1.51%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 369       | 1.49%   |
| 5.10.14-desktop-1omv4002            | 368       | 1.49%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 363       | 1.47%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 345       | 1.39%   |
| 4.15.0-desktop-45.1rosa-i586        | 340       | 1.37%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 307       | 1.24%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 297       | 1.2%    |
| 4.1.34-nrj-desktop-2rosa-i586       | 297       | 1.2%    |
| 5.4.32-generic-2rosa-x86_64         | 292       | 1.18%   |
| 5.4.83-generic-2rosa-x86_64         | 267       | 1.08%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 251       | 1.01%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 251       | 1.01%   |
| 4.1.38-nrj-desktop-2rosa-i586       | 220       | 0.89%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 204       | 0.82%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 192       | 0.78%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 167       | 0.67%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 143       | 0.58%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 143       | 0.58%   |
| 5.4.0-42-generic                    | 125       | 0.51%   |
| 4.1.38-nrj-desktop-1rosa-x86_64     | 124       | 0.5%    |
| 5.10.71-generic-1rosa2021.1-x86_64  | 123       | 0.5%    |
| 5.16.7-desktop-1omv4003             | 117       | 0.47%   |
| 4.9.155-nrj-desktop-1rosa-i586      | 117       | 0.47%   |
| 4.9.41-nrj-desktop-1rosa-i586       | 116       | 0.47%   |
| 4.9.87-nrj-desktop-2rosa-x86_64     | 109       | 0.44%   |
| 4.9.76-nrj-desktop-1rosa-i586       | 101       | 0.41%   |
| 5.4.32-generic-2rosa-i586           | 99        | 0.4%    |
| 5.10.0-2-amd64                      | 96        | 0.39%   |
| 4.15.0-desktop-51.4rosa-x86_64      | 89        | 0.36%   |
| 5.10.109-std-def-alt1               | 85        | 0.34%   |
| 4.15.0-desktop-54.1rosa-x86_64      | 84        | 0.34%   |
| 4.15.0-desktop-68.5rosa-i586        | 82        | 0.33%   |
| 5.10.102-std-def-alt1               | 77        | 0.31%   |
| 4.15.0-desktop-47.2rosa-i586        | 74        | 0.3%    |
| 5.3.0-28-generic                    | 72        | 0.29%   |
| 5.4.0-52-generic                    | 70        | 0.28%   |
| 5.4.0-58-generic                    | 69        | 0.28%   |
| 4.9.14-nrj-desktop-2rosa-x86_64     | 65        | 0.26%   |
| 5.4.83-generic-2rosa-i586           | 62        | 0.25%   |
| 4.15.0-desktop-122.124.1rosa-i586   | 60        | 0.24%   |
| 5.4.40-generic-1rosa-x86_64         | 57        | 0.23%   |
| 5.4.0-48-generic                    | 57        | 0.23%   |
| 4.9.95-nrj-desktop-2rosa-i586       | 57        | 0.23%   |
| 4.15.0-desktop-54.3rosa-x86_64      | 53        | 0.21%   |
| 4.15.0-desktop-94.1rosa-i586        | 52        | 0.21%   |
| 5.4.0-65-generic                    | 51        | 0.21%   |
| 5.3.0-46-generic                    | 47        | 0.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 4.15.0   | 3930      | 16.44%  |
| 4.9.60   | 1748      | 7.31%   |
| 4.9.20   | 1641      | 6.87%   |
| 5.4.0    | 1190      | 4.98%   |
| 4.1.34   | 1057      | 4.42%   |
| 5.10.74  | 999       | 4.18%   |
| 4.1.38   | 841       | 3.52%   |
| 4.9.9    | 792       | 3.31%   |
| 4.9.124  | 765       | 3.2%    |
| 4.1.25   | 763       | 3.19%   |
| 5.10.0   | 618       | 2.59%   |
| 4.9.76   | 494       | 2.07%   |
| 4.9.41   | 493       | 2.06%   |
| 4.9.155  | 468       | 1.96%   |
| 5.3.0    | 399       | 1.67%   |
| 5.4.32   | 390       | 1.63%   |
| 5.10.14  | 372       | 1.56%   |
| 5.8.0    | 371       | 1.55%   |
| 5.11.0   | 334       | 1.4%    |
| 5.4.83   | 333       | 1.39%   |
| 5.0.0    | 295       | 1.23%   |
| 5.13.0   | 259       | 1.08%   |
| 4.9.95   | 251       | 1.05%   |
| 4.18.0   | 189       | 0.79%   |
| 4.9.111  | 187       | 0.78%   |
| 4.19.0   | 149       | 0.62%   |
| 4.13.0   | 145       | 0.61%   |
| 4.9.87   | 142       | 0.59%   |
| 5.10.71  | 124       | 0.52%   |
| 5.16.7   | 120       | 0.5%    |
| 4.9.14   | 93        | 0.39%   |
| 5.10.109 | 86        | 0.36%   |
| 3.10.0   | 80        | 0.33%   |
| 5.10.102 | 77        | 0.32%   |
| 5.4.40   | 71        | 0.3%    |
| 5.15.0   | 71        | 0.3%    |
| 4.9.34   | 67        | 0.28%   |
| 4.1.15   | 66        | 0.28%   |
| 5.15.32  | 65        | 0.27%   |
| 4.4.0    | 52        | 0.22%   |
| 4.10.0   | 47        | 0.2%    |
| 4.9.0    | 37        | 0.15%   |
| 3.14.44  | 37        | 0.15%   |
| 5.11.6   | 32        | 0.13%   |
| 5.9.16   | 29        | 0.12%   |
| 4.16.18  | 29        | 0.12%   |
| 5.12.4   | 28        | 0.12%   |
| 5.14.0   | 27        | 0.11%   |
| 4.16.0   | 26        | 0.11%   |
| 5.4.72   | 25        | 0.1%    |
| 5.11.12  | 25        | 0.1%    |
| 5.6.0    | 24        | 0.1%    |
| 5.9.0    | 23        | 0.1%    |
| 5.3.18   | 23        | 0.1%    |
| 5.15.10  | 22        | 0.09%   |
| 5.4.28   | 21        | 0.09%   |
| 5.13.19  | 21        | 0.09%   |
| 5.16.0   | 20        | 0.08%   |
| 5.14.10  | 20        | 0.08%   |
| 4.8.14   | 20        | 0.08%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 6218      | 27.74%  |
| 4.15    | 3967      | 17.7%   |
| 4.1     | 2601      | 11.6%   |
| 5.10    | 2548      | 11.37%  |
| 5.4     | 2247      | 10.02%  |
| 5.8     | 494       | 2.2%    |
| 5.3     | 494       | 2.2%    |
| 5.11    | 487       | 2.17%   |
| 5.13    | 356       | 1.59%   |
| 5.15    | 324       | 1.45%   |
| 5.0     | 324       | 1.45%   |
| 5.16    | 242       | 1.08%   |
| 4.19    | 232       | 1.04%   |
| 4.18    | 215       | 0.96%   |
| 4.13    | 175       | 0.78%   |
| 5.6     | 155       | 0.69%   |
| 5.14    | 140       | 0.62%   |
| 5.9     | 137       | 0.61%   |
| 4.4     | 101       | 0.45%   |
| 5.12    | 99        | 0.44%   |
| 5.7     | 91        | 0.41%   |
| 5.17    | 85        | 0.38%   |
| 3.10    | 83        | 0.37%   |
| 4.8     | 76        | 0.34%   |
| 4.16    | 76        | 0.34%   |
| 5.5     | 68        | 0.3%    |
| 4.10    | 59        | 0.26%   |
| 4.14    | 48        | 0.21%   |
| 3.14    | 43        | 0.19%   |
| 5.2     | 40        | 0.18%   |
| 4.12    | 30        | 0.13%   |
| 4.17    | 27        | 0.12%   |
| 4.11    | 24        | 0.11%   |
| 5.1     | 18        | 0.08%   |
| 4.7     | 17        | 0.08%   |
| 4.20    | 16        | 0.07%   |
| 2.6     | 14        | 0.06%   |
| 3.16    | 11        | 0.05%   |
| 4.5     | 8         | 0.04%   |
| 4.6     | 5         | 0.02%   |
| 3.13    | 4         | 0.02%   |
| 5.18    | 3         | 0.01%   |
| 4.3     | 3         | 0.01%   |
| 3.2     | 3         | 0.01%   |
| 3.17    | 2         | 0.01%   |
| 4.2     | 1         | 0.004%  |
| 3.19    | 1         | 0.004%  |
| 3.18    | 1         | 0.004%  |
| 3.0     | 1         | 0.004%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 17039     | 83.98%  |
| i686    | 3197      | 15.76%  |
| aarch64 | 33        | 0.16%   |
| armv7l  | 10        | 0.05%   |
| armv6l  | 5         | 0.02%   |
| e2k     | 3         | 0.01%   |
| ppc64   | 1         | 0.005%  |
| mips    | 1         | 0.005%  |
| armv8l  | 1         | 0.005%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KDE4             | 8948      | 41.9%   |
| KDE5             | 5150      | 24.11%  |
| GNOME            | 2670      | 12.5%   |
| Unknown          | 1588      | 7.44%   |
| XFCE             | 683       | 3.2%    |
| LXQt             | 530       | 2.48%   |
| MATE             | 499       | 2.34%   |
| Cinnamon         | 406       | 1.9%    |
| KDE              | 310       | 1.45%   |
| X-Cinnamon       | 284       | 1.33%   |
| Pantheon         | 46        | 0.22%   |
| LXDE             | 46        | 0.22%   |
| Unity            | 39        | 0.18%   |
| i3               | 34        | 0.16%   |
| Budgie           | 30        | 0.14%   |
| GNOME Flashback  | 21        | 0.1%    |
| Deepin           | 12        | 0.06%   |
| sway             | 9         | 0.04%   |
| Openbox          | 8         | 0.04%   |
| GNOME Classic    | 8         | 0.04%   |
| fly              | 8         | 0.04%   |
| awesome          | 7         | 0.03%   |
| icewm            | 4         | 0.02%   |
| xmonad           | 3         | 0.01%   |
| lightdm-xsession | 3         | 0.01%   |
| dwm              | 3         | 0.01%   |
| Trinity          | 1         | 0.005%  |
| none+i3          | 1         | 0.005%  |
| Lumina           | 1         | 0.005%  |
| Lubuntu          | 1         | 0.005%  |
| fvwm2            | 1         | 0.005%  |
| fluxbox          | 1         | 0.005%  |
| Enlightenment    | 1         | 0.005%  |
| bspwm            | 1         | 0.005%  |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 17690     | 86.67%  |
| Wayland | 1572      | 7.7%    |
| Unknown | 967       | 4.74%   |
| Tty     | 180       | 0.88%   |
| Web     | 1         | 0.005%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDM     | 9010      | 42.4%   |
| SDDM    | 5452      | 25.66%  |
| Unknown | 3391      | 15.96%  |
| GDM     | 1722      | 8.1%    |
| TDM     | 798       | 3.76%   |
| LightDM | 574       | 2.7%    |
| GDM3    | 206       | 0.97%   |
| MDM     | 43        | 0.2%    |
| XDM     | 23        | 0.11%   |
| SLiM    | 13        | 0.06%   |
| LXDM    | 6         | 0.03%   |
| Ly      | 4         | 0.02%   |
| NODM    | 3         | 0.01%   |
| FLY-DM  | 3         | 0.01%   |
| LDM     | 1         | 0.005%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 12207     | 58.52%  |
| ru_RU       | 6891      | 33.03%  |
| en_US       | 1514      | 7.26%   |
| C           | 88        | 0.42%   |
| en_GB       | 58        | 0.28%   |
| ru_RU.UTF_8 | 28        | 0.13%   |
| ru_UA       | 14        | 0.07%   |
| C.UTF8      | 9         | 0.04%   |
| ru_RU.UTF8  | 8         | 0.04%   |
| POSIX       | 8         | 0.04%   |
| cv_RU       | 6         | 0.03%   |
| zh_CN       | 5         | 0.02%   |
| en_CA       | 4         | 0.02%   |
| de_DE       | 4         | 0.02%   |
| tt_RU       | 3         | 0.01%   |
| uk_UA       | 2         | 0.01%   |
| tr_TR       | 2         | 0.01%   |
| myv_RU      | 2         | 0.01%   |
| en_DK       | 2         | 0.01%   |
| ja_JP       | 1         | 0.005%  |
| fr_FR       | 1         | 0.005%  |
| es_ES       | 1         | 0.005%  |
| en_NZ       | 1         | 0.005%  |
| en_GB.utf-8 | 1         | 0.005%  |
| ba_RU       | 1         | 0.005%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 13863     | 67.73%  |
| EFI  | 6605      | 32.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 11464     | 53.93%  |
| Unknown  | 7576      | 35.64%  |
| Overlay  | 1078      | 5.07%   |
| Btrfs    | 762       | 3.58%   |
| Xfs      | 147       | 0.69%   |
| Ext3     | 60        | 0.28%   |
| Zfs      | 56        | 0.26%   |
| Ext2     | 37        | 0.17%   |
| F2fs     | 28        | 0.13%   |
| Aufs     | 21        | 0.1%    |
| Tmpfs    | 5         | 0.02%   |
| Rootfs   | 5         | 0.02%   |
| Reiserfs | 5         | 0.02%   |
| XXXXXXX  | 4         | 0.02%   |
| Jfs      | 4         | 0.02%   |
| SAMSUNG  | 3         | 0.01%   |
| XXXXX    | 2         | 0.01%   |
| Ufs      | 1         | 0.005%  |
| Exfat    | 1         | 0.005%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 9387      | 44.14%  |
| Unknown | 6102      | 28.69%  |
| GPT     | 5778      | 27.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 18043     | 87.43%  |
| Yes       | 2593      | 12.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 14648     | 70.09%  |
| Yes       | 6251      | 29.91%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 5323      | 26.58%  |
| Gigabyte Technology     | 2386      | 11.91%  |
| Lenovo                  | 1937      | 9.67%   |
| Hewlett-Packard         | 1662      | 8.3%    |
| Acer                    | 1552      | 7.75%   |
| MSI                     | 1241      | 6.2%    |
| ASRock                  | 1081      | 5.4%    |
| Dell                    | 819       | 4.09%   |
| Samsung Electronics     | 596       | 2.98%   |
| Intel                   | 381       | 1.9%    |
| Toshiba                 | 259       | 1.29%   |
| Sony                    | 241       | 1.2%    |
| ECS                     | 225       | 1.12%   |
| Unknown                 | 210       | 1.05%   |
| Packard Bell            | 172       | 0.86%   |
| Pegatron                | 132       | 0.66%   |
| Apple                   | 113       | 0.56%   |
| Foxconn                 | 108       | 0.54%   |
| eMachines               | 108       | 0.54%   |
| Biostar                 | 101       | 0.5%    |
| Supermicro              | 98        | 0.49%   |
| HUAWEI                  | 98        | 0.49%   |
| Notebook                | 65        | 0.32%   |
| Clevo                   | 63        | 0.31%   |
| Timi                    | 52        | 0.26%   |
| Fujitsu Siemens         | 52        | 0.26%   |
| Aquarius                | 51        | 0.25%   |
| Huanan                  | 47        | 0.23%   |
| Fujitsu                 | 47        | 0.23%   |
| Digma                   | 43        | 0.21%   |
| DNS                     | 37        | 0.18%   |
| Quanta                  | 34        | 0.17%   |
| Irbis                   | 32        | 0.16%   |
| AMI                     | 31        | 0.15%   |
| Prestigio               | 30        | 0.15%   |
| DEXP                    | 28        | 0.14%   |
| 3Logic Group            | 23        | 0.11%   |
| EPoX Computer           | 21        | 0.1%    |
| DEPO Computers          | 21        | 0.1%    |
| WinFast                 | 20        | 0.1%    |
| ICL                     | 18        | 0.09%   |
| Raspberry Pi Foundation | 17        | 0.08%   |
| IBM                     | 17        | 0.08%   |
| Chuwi                   | 16        | 0.08%   |
| Nvidia                  | 13        | 0.06%   |
| HONOR                   | 13        | 0.06%   |
| Maibenben               | 12        | 0.06%   |
| Hampoo                  | 12        | 0.06%   |
| iRU                     | 10        | 0.05%   |
| Insyde                  | 10        | 0.05%   |
| Infomash                | 10        | 0.05%   |
| AMD                     | 10        | 0.05%   |
| Panasonic               | 9         | 0.04%   |
| LG Electronics          | 9         | 0.04%   |
| Kraftway                | 8         | 0.04%   |
| JW Technology           | 8         | 0.04%   |
| Compal                  | 8         | 0.04%   |
| ZOTAC                   | 7         | 0.03%   |
| SiS Technology          | 7         | 0.03%   |
| Shuttle                 | 7         | 0.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 308       | 1.54%   |
| Unknown                                    | 290       | 1.45%   |
| HP Pavilion g6                             | 112       | 0.56%   |
| HP Notebook                                | 71        | 0.35%   |
| HP Pavilion dv6                            | 68        | 0.34%   |
| HP Laptop 15-bw0xx                         | 68        | 0.34%   |
| Gigabyte 970A-DS3P                         | 63        | 0.31%   |
| ASUS M5A78L-M LX3                          | 61        | 0.3%    |
| MSI MS-7817                                | 57        | 0.28%   |
| ASUS P8H61-M LX3 R2.0                      | 52        | 0.26%   |
| Acer Aspire V3-571G                        | 51        | 0.25%   |
| Lenovo G570 20079                          | 50        | 0.25%   |
| ASUS H110M-R                               | 48        | 0.24%   |
| Intel SKYBAY                               | 46        | 0.23%   |
| MSI MS-7996                                | 44        | 0.22%   |
| ASRock G31M-S                              | 44        | 0.22%   |
| Gigabyte H61M-S1                           | 41        | 0.2%    |
| Gigabyte G31M-ES2L                         | 40        | 0.2%    |
| ASUS M5A97 R2.0                            | 40        | 0.2%    |
| ASUS P5K                                   | 39        | 0.19%   |
| MSI MS-7529                                | 38        | 0.19%   |
| ASUS P5KPL-AM                              | 38        | 0.19%   |
| ASRock N68C-S UCC                          | 37        | 0.18%   |
| Packard Bell EasyNote TE11HC               | 36        | 0.18%   |
| MSI MS-7592                                | 36        | 0.18%   |
| Lenovo B570e HuronRiver Platform           | 36        | 0.18%   |
| ASUS P5G41T-M LX2/GB                       | 36        | 0.18%   |
| ASUS M5A78L-M/USB3                         | 36        | 0.18%   |
| Lenovo B590 20206                          | 35        | 0.17%   |
| HP Pavilion dv7                            | 35        | 0.17%   |
| HP Pavilion 15                             | 35        | 0.17%   |
| Gigabyte H61M-S2PV                         | 35        | 0.17%   |
| ASUS M5A97 LE R2.0                         | 35        | 0.17%   |
| Lenovo G50-45 80E3                         | 34        | 0.17%   |
| Aquarius NS585                             | 34        | 0.17%   |
| Gigabyte Z77-DS3H                          | 32        | 0.16%   |
| Lenovo G500 20236                          | 31        | 0.15%   |
| Lenovo B590 20208                          | 31        | 0.15%   |
| HUAWEI NBLK-WAX9X                          | 31        | 0.15%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 31        | 0.15%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 30        | 0.15%   |
| Lenovo G50-30 80G0                         | 30        | 0.15%   |
| HP Pavilion g7                             | 30        | 0.15%   |
| ASUS P8Z77-V LX                            | 30        | 0.15%   |
| ASUS P5KPL-AM IN/ROEM/SI                   | 30        | 0.15%   |
| ASUS P5B                                   | 30        | 0.15%   |
| MSI MS-7693                                | 29        | 0.14%   |
| ASUS P5Q SE2                               | 29        | 0.14%   |
| ASRock G41M-VS3                            | 29        | 0.14%   |
| Toshiba Satellite C660                     | 28        | 0.14%   |
| Lenovo G580 20150                          | 28        | 0.14%   |
| Gigabyte GA-78LMT-S2P                      | 28        | 0.14%   |
| Dell Inspiron N5110                        | 28        | 0.14%   |
| ASUS PRIME A320M-K                         | 28        | 0.14%   |
| ASUS A68HM-K                               | 28        | 0.14%   |
| Acer Aspire 5750G                          | 28        | 0.14%   |
| Lenovo B560                                | 27        | 0.13%   |
| Gigabyte GA-78LMT-S2                       | 27        | 0.13%   |
| ASUS H110M-K                               | 27        | 0.13%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 25        | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 1060      | 5.29%   |
| Lenovo IdeaPad        | 501       | 2.5%    |
| HP Pavilion           | 450       | 2.25%   |
| Dell Inspiron         | 379       | 1.89%   |
| Lenovo ThinkPad       | 367       | 1.83%   |
| ASUS All              | 308       | 1.54%   |
| ASUS PRIME            | 290       | 1.45%   |
| Unknown               | 290       | 1.45%   |
| Toshiba Satellite     | 240       | 1.2%    |
| HP Laptop             | 240       | 1.2%    |
| ASUS VivoBook         | 235       | 1.17%   |
| HP ProBook            | 210       | 1.05%   |
| ASUS P8H61-M          | 164       | 0.82%   |
| ASUS M5A78L-M         | 158       | 0.79%   |
| HP Compaq             | 150       | 0.75%   |
| Packard Bell EasyNote | 145       | 0.72%   |
| Dell Latitude         | 145       | 0.72%   |
| Acer Extensa          | 134       | 0.67%   |
| ASUS P5KPL-AM         | 114       | 0.57%   |
| Dell Vostro           | 104       | 0.52%   |
| ASUS M5A97            | 99        | 0.49%   |
| ASUS P5G41T-M         | 91        | 0.45%   |
| ASUS P5K              | 86        | 0.43%   |
| ASUS P8Z77-V          | 80        | 0.4%    |
| Acer TravelMate       | 77        | 0.38%   |
| ASUS ROG              | 74        | 0.37%   |
| Lenovo G580           | 72        | 0.36%   |
| HP Notebook           | 72        | 0.36%   |
| ASUS P5Q              | 69        | 0.34%   |
| HP EliteBook          | 68        | 0.34%   |
| Lenovo B590           | 66        | 0.33%   |
| ASUS TUF              | 66        | 0.33%   |
| Gigabyte 970A-DS3P    | 64        | 0.32%   |
| Dell OptiPlex         | 61        | 0.3%    |
| MSI MS-7817           | 57        | 0.28%   |
| HP ENVY               | 56        | 0.28%   |
| Lenovo ThinkCentre    | 54        | 0.27%   |
| Lenovo G570           | 51        | 0.25%   |
| ASUS H110M-R          | 48        | 0.24%   |
| ASUS P8H67-M          | 47        | 0.23%   |
| Intel SKYBAY          | 46        | 0.23%   |
| HP 250                | 45        | 0.22%   |
| MSI MS-7996           | 44        | 0.22%   |
| ASRock G31M-S         | 44        | 0.22%   |
| Gigabyte B450M        | 43        | 0.21%   |
| ASUS SABERTOOTH       | 43        | 0.21%   |
| Acer Veriton          | 43        | 0.21%   |
| Gigabyte H61M-S1      | 41        | 0.2%    |
| Dell XPS              | 41        | 0.2%    |
| Samsung 355V4C        | 40        | 0.2%    |
| Gigabyte G31M-ES2L    | 40        | 0.2%    |
| ASUS P8H77-V          | 40        | 0.2%    |
| Samsung 300V3A        | 39        | 0.19%   |
| MSI MS-7529           | 38        | 0.19%   |
| Lenovo IdeaCentre     | 38        | 0.19%   |
| ASUS P8B75-M          | 38        | 0.19%   |
| ASRock N68C-S         | 38        | 0.19%   |
| Acer Swift            | 38        | 0.19%   |
| Notebook W65          | 36        | 0.18%   |
| MSI MS-7592           | 36        | 0.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 2653      | 13.25%  |
| 2011    | 2276      | 11.36%  |
| 2010    | 1730      | 8.64%   |
| 2013    | 1494      | 7.46%   |
| 2009    | 1442      | 7.2%    |
| 2018    | 1292      | 6.45%   |
| 2008    | 1247      | 6.23%   |
| 2007    | 1094      | 5.46%   |
| 2017    | 1004      | 5.01%   |
| 2019    | 964       | 4.81%   |
| 2016    | 929       | 4.64%   |
| 2014    | 913       | 4.56%   |
| 2015    | 791       | 3.95%   |
| 2020    | 762       | 3.8%    |
| 2006    | 598       | 2.99%   |
| 2021    | 409       | 2.04%   |
| 2005    | 235       | 1.17%   |
| 2004    | 74        | 0.37%   |
| Unknown | 58        | 0.29%   |
| 2003    | 41        | 0.2%    |
| 2022    | 13        | 0.06%   |
| 2002    | 7         | 0.03%   |
| 2001    | 4         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 9711      | 48.48%  |
| Notebook       | 9576      | 47.81%  |
| All in one     | 250       | 1.25%   |
| Server         | 150       | 0.75%   |
| Mini pc        | 143       | 0.71%   |
| Convertible    | 82        | 0.41%   |
| Tablet         | 74        | 0.37%   |
| System on chip | 38        | 0.19%   |
| Phone          | 3         | 0.01%   |
| Stick pc       | 2         | 0.01%   |
| Firewall       | 1         | 0.005%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 19639     | 97.8%   |
| Enabled  | 442       | 2.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 20016     | 99.93%  |
| Yes  | 14        | 0.07%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 5972      | 28.82%  |
| 4.01-8.0        | 4199      | 20.27%  |
| 8.01-16.0       | 3629      | 17.52%  |
| 1.01-2.0        | 2307      | 11.13%  |
| 16.01-24.0      | 1952      | 9.42%   |
| 2.01-3.0        | 1350      | 6.52%   |
| 32.01-64.0      | 557       | 2.69%   |
| 0.51-1.0        | 396       | 1.91%   |
| 64.01-256.0     | 168       | 0.81%   |
| 24.01-32.0      | 138       | 0.67%   |
| 0.01-0.5        | 28        | 0.14%   |
| More than 256.0 | 16        | 0.08%   |
| Unknown         | 7         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 8698      | 38.53%  |
| 0.51-1.0        | 7842      | 34.73%  |
| 2.01-3.0        | 2745      | 12.16%  |
| 4.01-8.0        | 1182      | 5.24%   |
| 3.01-4.0        | 1126      | 4.99%   |
| 0.01-0.5        | 550       | 2.44%   |
| 8.01-16.0       | 300       | 1.33%   |
| 16.01-24.0      | 57        | 0.25%   |
| Unknown         | 32        | 0.14%   |
| 32.01-64.0      | 21        | 0.09%   |
| 24.01-32.0      | 17        | 0.08%   |
| 64.01-256.0     | 6         | 0.03%   |
| More than 256.0 | 1         | 0.004%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 13324     | 63.77%  |
| 2       | 4871      | 23.31%  |
| 3       | 1557      | 7.45%   |
| 4       | 596       | 2.85%   |
| 5       | 235       | 1.12%   |
| 0       | 156       | 0.75%   |
| 6       | 74        | 0.35%   |
| 7       | 29        | 0.14%   |
| 8       | 21        | 0.1%    |
| 9       | 9         | 0.04%   |
| Unknown | 9         | 0.04%   |
| 17      | 2         | 0.01%   |
| 11      | 2         | 0.01%   |
| 10      | 2         | 0.01%   |
| 209     | 1         | 0.005%  |
| 18      | 1         | 0.005%  |
| 16      | 1         | 0.005%  |
| 15      | 1         | 0.005%  |
| 13      | 1         | 0.005%  |
| 12      | 1         | 0.005%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 10356     | 50.78%  |
| No        | 10037     | 49.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 18733     | 93.44%  |
| No        | 1315      | 6.56%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 12096     | 59.88%  |
| No        | 8103      | 40.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 12204     | 60.15%  |
| Yes       | 8084      | 39.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 20030     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Moscow           | 3908      | 18.24%  |
| St Petersburg    | 1687      | 7.87%   |
| Voronezh         | 783       | 3.65%   |
| Pecherskoye      | 765       | 3.57%   |
| Novosibirsk      | 641       | 2.99%   |
| Yekaterinburg    | 555       | 2.59%   |
| Krasnodar        | 539       | 2.52%   |
| Nizhniy Novgorod | 424       | 1.98%   |
| Samara           | 416       | 1.94%   |
| Rostov-on-Don    | 364       | 1.7%    |
| Perm             | 352       | 1.64%   |
| Chelyabinsk      | 342       | 1.6%    |
| Krasnoyarsk      | 254       | 1.19%   |
| Saratov          | 241       | 1.12%   |
| Kazan’         | 239       | 1.12%   |
| Omsk             | 222       | 1.04%   |
| Ufa              | 199       | 0.93%   |
| Volgograd        | 185       | 0.86%   |
| Khabarovsk       | 181       | 0.84%   |
| Barnaul          | 178       | 0.83%   |
| Tyumen           | 177       | 0.83%   |
| Irkutsk          | 168       | 0.78%   |
| Vladivostok      | 165       | 0.77%   |
| Stavropol        | 157       | 0.73%   |
| Kaliningrad      | 136       | 0.63%   |
| Yaroslavl        | 129       | 0.6%    |
| Kemerovo         | 128       | 0.6%    |
| Belgorod         | 126       | 0.59%   |
| Ulyanovsk        | 122       | 0.57%   |
| Tula             | 122       | 0.57%   |
| Tomsk            | 119       | 0.56%   |
| Orenburg         | 115       | 0.54%   |
| Kirov            | 114       | 0.53%   |
| Ryazan           | 113       | 0.53%   |
| Bryansk          | 112       | 0.52%   |
| Novokuznetsk     | 107       | 0.5%    |
| Izhevsk          | 106       | 0.49%   |
| Surgut           | 105       | 0.49%   |
| Tolyatti         | 101       | 0.47%   |
| Ivanovo          | 100       | 0.47%   |
| Penza            | 99        | 0.46%   |
| Lipetsk          | 98        | 0.46%   |
| Astrakhan        | 97        | 0.45%   |
| Murmansk         | 91        | 0.42%   |
| Smolensk         | 87        | 0.41%   |
| Tver             | 85        | 0.4%    |
| Kaluga           | 82        | 0.38%   |
| Abakan           | 75        | 0.35%   |
| Oryol            | 74        | 0.35%   |
| Vladimir         | 73        | 0.34%   |
| Kurgan           | 73        | 0.34%   |
| Pskov            | 71        | 0.33%   |
| Petrozavodsk     | 70        | 0.33%   |
| Cheboksary       | 70        | 0.33%   |
| Arkhangelsk      | 70        | 0.33%   |
| Kostroma         | 68        | 0.32%   |
| Sochi            | 65        | 0.3%    |
| Chita            | 65        | 0.3%    |
| Lyubertsy        | 61        | 0.28%   |
| Yoshkar-Ola      | 59        | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives  | Percent |
|-----------------------|-----------|---------|---------|
| WDC                   | 6335      | 10149   | 22.45%  |
| Seagate               | 6233      | 9401    | 22.09%  |
| Samsung Electronics   | 2440      | 3460    | 8.65%   |
| Toshiba               | 2349      | 3199    | 8.33%   |
| Hitachi               | 1786      | 2339    | 6.33%   |
| Kingston              | 1362      | 1751    | 4.83%   |
| HGST                  | 689       | 998     | 2.44%   |
| Unknown               | 640       | 836     | 2.27%   |
| SanDisk               | 554       | 724     | 1.96%   |
| Intel                 | 478       | 718     | 1.69%   |
| A-DATA Technology     | 418       | 563     | 1.48%   |
| China                 | 388       | 508     | 1.38%   |
| SPCC                  | 327       | 410     | 1.16%   |
| SK Hynix              | 301       | 365     | 1.07%   |
| OCZ                   | 290       | 373     | 1.03%   |
| Crucial               | 284       | 378     | 1.01%   |
| MAXTOR                | 255       | 324     | 0.9%    |
| PLEXTOR               | 237       | 350     | 0.84%   |
| Smartbuy              | 175       | 211     | 0.62%   |
| Apacer                | 172       | 222     | 0.61%   |
| Fujitsu               | 160       | 191     | 0.57%   |
| HUAWEI                | 156       | 191     | 0.55%   |
| Transcend             | 137       | 175     | 0.49%   |
| Micron Technology     | 124       | 165     | 0.44%   |
| KingSpec              | 117       | 147     | 0.41%   |
| Patriot               | 102       | 132     | 0.36%   |
| AMD                   | 101       | 117     | 0.36%   |
| Corsair               | 99        | 136     | 0.35%   |
| GOODRAM               | 88        | 112     | 0.31%   |
| KingDian              | 71        | 104     | 0.25%   |
| Silicon Motion        | 66        | 83      | 0.23%   |
| Phison                | 66        | 74      | 0.23%   |
| Netac                 | 56        | 101     | 0.2%    |
| KIOXIA                | 55        | 63      | 0.19%   |
| Apple                 | 54        | 69      | 0.19%   |
| JMicron               | 46        | 47      | 0.16%   |
| Kingmax               | 45        | 78      | 0.16%   |
| TF CARD               | 40        | 55      | 0.14%   |
| Gigabyte Technology   | 40        | 48      | 0.14%   |
| XPG                   | 39        | 47      | 0.14%   |
| FOXLINE               | 38        | 42      | 0.13%   |
| LITEON                | 34        | 41      | 0.12%   |
| Mass                  | 30        | Unknown | 0.11%   |
| ZTE                   | 29        | 32      | 0.1%    |
| XrayDisk              | 27        | 35      | 0.1%    |
| AXIOMTEK              | 26        | 26      | 0.09%   |
| LONDISK               | 25        | 27      | 0.09%   |
| Hewlett-Packard       | 25        | 38      | 0.09%   |
| LITEONIT              | 24        | 42      | 0.09%   |
| KingFast              | 24        | 31      | 0.09%   |
| Realtek Semiconductor | 18        | 19      | 0.06%   |
| Zheino                | 17        | 22      | 0.06%   |
| TO Exter              | 17        | 17      | 0.06%   |
| IBM/Hitachi           | 17        | 20      | 0.06%   |
| Unknown               | 16        | 17      | 0.06%   |
| QUMO                  | 14        | 16      | 0.05%   |
| FORESEE               | 14        | 16      | 0.05%   |
| SSSTC                 | 13        | 14      | 0.05%   |
| Lenovo                | 13        | 24      | 0.05%   |
| Union Memory          | 12        | 14      | 0.04%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 347       | 1.12%   |
| Seagate ST500LT012-1DG142 500GB     | 262       | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 259       | 0.84%   |
| Toshiba MQ01ABF050 500GB            | 250       | 0.81%   |
| Seagate ST3500418AS 500GB           | 226       | 0.73%   |
| Toshiba DT01ACA050 500GB            | 216       | 0.7%    |
| Seagate ST9500325AS 500GB           | 213       | 0.69%   |
| Kingston SA400S37120G 120GB SSD     | 209       | 0.68%   |
| Seagate ST1000DM010-2EP102 1TB      | 197       | 0.64%   |
| Toshiba HDWD110 1TB                 | 193       | 0.62%   |
| Kingston SV300S37A120G 120GB SSD    | 189       | 0.61%   |
| WDC WD10EZEX-08WN4A0 1TB            | 183       | 0.59%   |
| Kingston SA400S37240G 240GB SSD     | 176       | 0.57%   |
| Toshiba DT01ACA100 1TB              | 173       | 0.56%   |
| Seagate ST1000DM003-1CH162 1TB      | 172       | 0.56%   |
| Seagate ST1000LM035-1RK172 1TB      | 169       | 0.55%   |
| HGST HTS545050A7E680 500GB          | 161       | 0.52%   |
| Seagate ST9320325AS 320GB           | 159       | 0.51%   |
| Samsung SSD 860 EVO 250GB           | 152       | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 148       | 0.48%   |
| Toshiba MQ01ABD100 1TB              | 133       | 0.43%   |
| WDC WD5000AAKX-001CA0 500GB         | 129       | 0.42%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 126       | 0.41%   |
| Seagate ST380011A 80GB              | 126       | 0.41%   |
| Seagate ST3250410AS 250GB           | 120       | 0.39%   |
| Seagate ST380815AS 80GB             | 117       | 0.38%   |
| Hitachi HTS543232A7A384 320GB       | 113       | 0.37%   |
| Seagate ST31000528AS 1TB            | 112       | 0.36%   |
| Seagate ST31000524AS 1TB            | 111       | 0.36%   |
| Seagate ST9250315AS 250GB           | 107       | 0.35%   |
| Seagate ST500LT012-9WS142 500GB     | 107       | 0.35%   |
| Seagate ST3160815AS 160GB           | 106       | 0.34%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 103       | 0.33%   |
| HGST HTS545050A7E380 500GB          | 103       | 0.33%   |
| HGST HTS721010A9E630 1TB            | 101       | 0.33%   |
| Seagate ST3250310AS 250GB           | 100       | 0.32%   |
| Toshiba MQ04ABF100 1TB              | 99        | 0.32%   |
| Seagate ST1000DM003-1ER162 1TB      | 99        | 0.32%   |
| SPCC Solid State Disk 120GB         | 97        | 0.31%   |
| Seagate ST1000DM003-9YN162 1TB      | 95        | 0.31%   |
| Samsung SSD 860 EVO 500GB           | 95        | 0.31%   |
| Hitachi HDS721050CLA362 500GB       | 95        | 0.31%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 94        | 0.3%    |
| Seagate ST320LT020-9YG142 320GB     | 91        | 0.29%   |
| HGST HTS541010A9E680 1TB            | 90        | 0.29%   |
| Hitachi HTS545025B9A300 250GB       | 86        | 0.28%   |
| Samsung SSD 850 EVO 250GB           | 85        | 0.27%   |
| Hitachi HTS547550A9E384 500GB       | 84        | 0.27%   |
| Seagate ST3500413AS 500GB           | 83        | 0.27%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 82        | 0.27%   |
| Toshiba HDWD105 500GB               | 82        | 0.27%   |
| HUAWEI TF CARD Storage 16GB         | 81        | 0.26%   |
| SPCC Solid State Disk 64GB          | 78        | 0.25%   |
| Smartbuy SSD 120GB                  | 78        | 0.25%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 76        | 0.25%   |
| Seagate ST3250318AS 250GB           | 76        | 0.25%   |
| Seagate ST250DM000-1BD141 250GB     | 76        | 0.25%   |
| Seagate ST2000DM001-1CH164 2TB      | 75        | 0.24%   |
| WDC WD10JPVX-22JC3T0 1TB            | 74        | 0.24%   |
| Hitachi HTS547575A9E384 752GB       | 74        | 0.24%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6209      | 9348   | 34.28%  |
| WDC                 | 5801      | 9077   | 32.03%  |
| Toshiba             | 2174      | 2945   | 12%     |
| Hitachi             | 1786      | 2339   | 9.86%   |
| Samsung Electronics | 906       | 1258   | 5%      |
| HGST                | 689       | 998    | 3.8%    |
| MAXTOR              | 254       | 323    | 1.4%    |
| Fujitsu             | 158       | 189    | 0.87%   |
| Unknown             | 39        | 52     | 0.22%   |
| Apple               | 19        | 24     | 0.1%    |
| IBM/Hitachi         | 17        | 20     | 0.09%   |
| Hewlett-Packard     | 9         | 13     | 0.05%   |
| IBM                 | 5         | 5      | 0.03%   |
| asmedia             | 4         | 5      | 0.02%   |
| WD MediaMax         | 3         | 4      | 0.02%   |
| QUANTUM             | 3         | 3      | 0.02%   |
| PHD 3.0             | 3         | 3      | 0.02%   |
| KESU                | 3         | 3      | 0.02%   |
| CLOVER              | 3         | 3      | 0.02%   |
| Synology            | 2         | 3      | 0.01%   |
| Lenovo              | 2         | 9      | 0.01%   |
| HPE                 | 2         | 2      | 0.01%   |
| HGST HTS            | 2         | 2      | 0.01%   |
| ExcelStor           | 2         | 2      | 0.01%   |
| ASMT106x            | 2         | 2      | 0.01%   |
| ZALMAN              | 1         | 1      | 0.01%   |
| USB 3.0             | 1         | 1      | 0.01%   |
| USB                 | 1         | 1      | 0.01%   |
| SILICONMOTION       | 1         | 1      | 0.01%   |
| SILICON             | 1         | 1      | 0.01%   |
| sage                | 1         | 1      | 0.01%   |
| QNAP                | 1         | 2      | 0.01%   |
| OEM                 | 1         | 2      | 0.01%   |
| MSCC                | 1         | 1      | 0.01%   |
| MR2020              | 1         | 1      | 0.01%   |
| MARVELL             | 1         | 1      | 0.01%   |
| MARSHAL             | 1         | 1      | 0.01%   |
| LIO-ORG             | 1         | 1      | 0.01%   |
| IET                 | 1         | 2      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 1205      | 1553   | 16.68%  |
| Samsung Electronics | 977       | 1357   | 13.53%  |
| WDC                 | 534       | 668    | 7.39%   |
| SanDisk             | 391       | 528    | 5.41%   |
| China               | 386       | 506    | 5.34%   |
| A-DATA Technology   | 360       | 481    | 4.98%   |
| SPCC                | 314       | 393    | 4.35%   |
| OCZ                 | 289       | 372    | 4%      |
| Crucial             | 276       | 365    | 3.82%   |
| Intel               | 273       | 439    | 3.78%   |
| PLEXTOR             | 223       | 316    | 3.09%   |
| Smartbuy            | 168       | 202    | 2.33%   |
| Apacer              | 147       | 195    | 2.04%   |
| Transcend           | 130       | 166    | 1.8%    |
| KingSpec            | 117       | 147    | 1.62%   |
| Toshiba             | 112       | 159    | 1.55%   |
| Patriot             | 98        | 127    | 1.36%   |
| Corsair             | 94        | 130    | 1.3%    |
| AMD                 | 94        | 108    | 1.3%    |
| GOODRAM             | 84        | 108    | 1.16%   |
| SK Hynix            | 75        | 91     | 1.04%   |
| KingDian            | 70        | 103    | 0.97%   |
| Micron Technology   | 62        | 96     | 0.86%   |
| Netac               | 51        | 95     | 0.71%   |
| Kingmax             | 45        | 78     | 0.62%   |
| JMicron             | 31        | 32     | 0.43%   |
| FOXLINE             | 30        | 34     | 0.42%   |
| Gigabyte Technology | 29        | 34     | 0.4%    |
| Apple               | 29        | 35     | 0.4%    |
| LITEON              | 28        | 35     | 0.39%   |
| AXIOMTEK            | 26        | 26     | 0.36%   |
| LONDISK             | 25        | 27     | 0.35%   |
| LITEONIT            | 24        | 42     | 0.33%   |
| XrayDisk            | 19        | 26     | 0.26%   |
| KingFast            | 19        | 24     | 0.26%   |
| Zheino              | 17        | 22     | 0.24%   |
| TO Exter            | 17        | 17     | 0.24%   |
| Seagate             | 16        | 28     | 0.22%   |
| QUMO                | 14        | 16     | 0.19%   |
| Hewlett-Packard     | 14        | 20     | 0.19%   |
| PALIT               | 12        | 14     | 0.17%   |
| FORESEE             | 12        | 14     | 0.17%   |
| PNY                 | 11        | 12     | 0.15%   |
| Unknown             | 10        | 14     | 0.14%   |
| Team                | 10        | 12     | 0.14%   |
| OCZ-VERTEX3         | 10        | 13     | 0.14%   |
| e2e4                | 9         | 15     | 0.12%   |
| Teclast             | 6         | 7      | 0.08%   |
| Lenovo              | 6         | 8      | 0.08%   |
| KINGRICH            | 6         | 8      | 0.08%   |
| faspeed             | 6         | 6      | 0.08%   |
| External            | 6         | 7      | 0.08%   |
| Verbatim            | 5         | 5      | 0.07%   |
| GLOWAY              | 5         | 5      | 0.07%   |
| Dell                | 5         | 7      | 0.07%   |
| ASUS-PHISON         | 5         | 12     | 0.07%   |
| Unknown             | 5         | 5      | 0.07%   |
| Xinhaike            | 4         | 6      | 0.06%   |
| Pioneer             | 4         | 4      | 0.06%   |
| OCZ-VERTEX2         | 4         | 4      | 0.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 15312     | 26649  | 61.84%  |
| SSD     | 6434      | 9604   | 25.99%  |
| NVMe    | 2038      | 2733   | 8.23%   |
| MMC     | 618       | 827    | 2.5%    |
| Unknown | 357       | 606    | 1.44%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 18271     | 35885  | 84.78%  |
| NVMe | 2038      | 2731   | 9.46%   |
| SAS  | 624       | 976    | 2.9%    |
| MMC  | 618       | 827    | 2.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 15336     | 25450  | 69.5%   |
| 0.51-1.0   | 5322      | 8453   | 24.12%  |
| 1.01-2.0   | 902       | 1491   | 4.09%   |
| 3.01-4.0   | 207       | 311    | 0.94%   |
| 2.01-3.0   | 202       | 334    | 0.92%   |
| 4.01-10.0  | 83        | 185    | 0.38%   |
| 10.01-20.0 | 12        | 27     | 0.05%   |
| 20.01-50.0 | 1         | 1      | 0.005%  |
| 0          | 1         | 1      | 0.005%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 5961      | 26.95%  |
| 251-500        | 4803      | 21.71%  |
| 501-1000       | 2535      | 11.46%  |
| 1-20           | 2443      | 11.04%  |
| 51-100         | 2251      | 10.18%  |
| 21-50          | 1597      | 7.22%   |
| 1001-2000      | 1168      | 5.28%   |
| Unknown        | 690       | 3.12%   |
| 2001-3000      | 359       | 1.62%   |
| More than 3000 | 313       | 1.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 12687     | 56.61%  |
| 21-50          | 2585      | 11.53%  |
| 101-250        | 1920      | 8.57%   |
| 51-100         | 1715      | 7.65%   |
| 251-500        | 1315      | 5.87%   |
| 501-1000       | 839       | 3.74%   |
| Unknown        | 690       | 3.08%   |
| 1001-2000      | 410       | 1.83%   |
| More than 3000 | 132       | 0.59%   |
| 2001-3000      | 117       | 0.52%   |
| 0              | 2         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 143       | 194    | 1.9%    |
| Seagate ST500DM002-1BD142 500GB     | 126       | 159    | 1.67%   |
| Seagate ST500LT012-9WS142 500GB     | 98        | 117    | 1.3%    |
| Seagate ST3500418AS 500GB           | 95        | 121    | 1.26%   |
| Seagate ST9320325AS 320GB           | 89        | 110    | 1.18%   |
| Seagate ST3250410AS 250GB           | 81        | 103    | 1.07%   |
| Seagate ST9250315AS 250GB           | 76        | 95     | 1.01%   |
| Seagate ST500LT012-1DG142 500GB     | 71        | 86     | 0.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 70        | 87     | 0.93%   |
| HGST HTS545050A7E680 500GB          | 70        | 104    | 0.93%   |
| WDC WD5000AAKX-001CA0 500GB         | 60        | 78     | 0.8%    |
| Seagate ST3250310AS 250GB           | 56        | 91     | 0.74%   |
| Seagate ST320LT020-9YG142 320GB     | 56        | 81     | 0.74%   |
| Seagate ST3320613AS 320GB           | 53        | 71     | 0.7%    |
| Seagate ST31000528AS 1TB            | 52        | 62     | 0.69%   |
| HGST HTS545050A7E380 500GB          | 51        | 80     | 0.68%   |
| Seagate ST1000DM003-9YN162 1TB      | 48        | 56     | 0.64%   |
| Seagate ST1000DM003-1CH162 1TB      | 46        | 67     | 0.61%   |
| Seagate ST380011A 80GB              | 44        | 47     | 0.58%   |
| Hitachi HTS543232A7A384 320GB       | 43        | 49     | 0.57%   |
| Hitachi HTS545025B9A300 250GB       | 42        | 50     | 0.56%   |
| WDC WD5000AADS-00S9B0 500GB         | 40        | 45     | 0.53%   |
| Seagate ST320LT012-9WS14C 320GB     | 40        | 49     | 0.53%   |
| Hitachi HDS721050CLA362 500GB       | 40        | 46     | 0.53%   |
| Seagate ST3160815AS 160GB           | 39        | 50     | 0.52%   |
| Seagate ST31000524AS 1TB            | 39        | 51     | 0.52%   |
| Seagate ST250DM000-1BD141 250GB     | 39        | 49     | 0.52%   |
| Hitachi HTS547550A9E384 500GB       | 36        | 47     | 0.48%   |
| WDC WD10EARS-00Y5B1 1TB             | 35        | 58     | 0.46%   |
| Seagate ST380815AS 80GB             | 35        | 47     | 0.46%   |
| Seagate ST3160811AS 160GB           | 34        | 48     | 0.45%   |
| WDC WD3200AAJS-00L7A0 320GB         | 33        | 38     | 0.44%   |
| Seagate ST3250318AS 250GB           | 33        | 38     | 0.44%   |
| Hitachi HTS547575A9E384 752GB       | 33        | 48     | 0.44%   |
| Hitachi HTS541612J9SA00 120GB       | 33        | 43     | 0.44%   |
| Toshiba MQ01ABD050 500GB            | 32        | 39     | 0.42%   |
| Samsung Electronics HD160JJ 160GB   | 32        | 52     | 0.42%   |
| Samsung Electronics HD080HJ 80GB    | 31        | 41     | 0.41%   |
| Kingston SV300S37A120G 120GB SSD    | 31        | 32     | 0.41%   |
| Kingston SHFS37A120G 120GB SSD      | 31        | 39     | 0.41%   |
| Hitachi HDS721616PLA380 164GB       | 31        | 44     | 0.41%   |
| Hitachi HDS721010CLA332 1TB         | 31        | 38     | 0.41%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 30        | 37     | 0.4%    |
| MAXTOR STM3250310AS 250GB           | 30        | 39     | 0.4%    |
| Toshiba MQ01ABF050 500GB            | 29        | 33     | 0.38%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 27        | 36     | 0.36%   |
| Seagate ST31500341AS 1TB            | 27        | 34     | 0.36%   |
| Samsung Electronics HM160HI 160GB   | 26        | 28     | 0.34%   |
| Hitachi HTS542512K9SA00 120GB       | 26        | 28     | 0.34%   |
| Hitachi HTS541680J9SA00 80GB        | 25        | 31     | 0.33%   |
| Hitachi HDP725050GLA360 500GB       | 25        | 37     | 0.33%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 24        | 34     | 0.32%   |
| Toshiba MK3265GSX 320GB             | 24        | 30     | 0.32%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 24        | 30     | 0.32%   |
| Seagate ST3500413AS 500GB           | 24        | 26     | 0.32%   |
| HGST HTS541010A9E680 1TB            | 24        | 37     | 0.32%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 23        | 28     | 0.3%    |
| WDC WD5000AAKS-00V1A0 500GB         | 23        | 26     | 0.3%    |
| Toshiba MQ01ABD100 1TB              | 23        | 29     | 0.3%    |
| Seagate ST9500420AS 500GB           | 23        | 39     | 0.3%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2523      | 3462   | 35.04%  |
| WDC                 | 1766      | 2442   | 24.52%  |
| Hitachi             | 883       | 1139   | 12.26%  |
| Toshiba             | 523       | 679    | 7.26%   |
| Samsung Electronics | 468       | 634    | 6.5%    |
| HGST                | 197       | 292    | 2.74%   |
| MAXTOR              | 149       | 179    | 2.07%   |
| Kingston            | 121       | 142    | 1.68%   |
| OCZ                 | 59        | 74     | 0.82%   |
| SanDisk             | 56        | 69     | 0.78%   |
| Fujitsu             | 46        | 60     | 0.64%   |
| Intel               | 44        | 61     | 0.61%   |
| SPCC                | 43        | 50     | 0.6%    |
| A-DATA Technology   | 42        | 59     | 0.58%   |
| Corsair             | 33        | 44     | 0.46%   |
| Kingmax             | 27        | 44     | 0.37%   |
| Crucial             | 20        | 32     | 0.28%   |
| KingSpec            | 19        | 19     | 0.26%   |
| SK Hynix            | 18        | 24     | 0.25%   |
| PLEXTOR             | 16        | 28     | 0.22%   |
| IBM/Hitachi         | 16        | 19     | 0.22%   |
| China               | 15        | 18     | 0.21%   |
| LITEON              | 10        | 12     | 0.14%   |
| AMD                 | 9         | 13     | 0.12%   |
| LITEONIT            | 8         | 13     | 0.11%   |
| Micron Technology   | 6         | 11     | 0.08%   |
| KingDian            | 6         | 10     | 0.08%   |
| OCZ-VERTEX3         | 5         | 8      | 0.07%   |
| Apple               | 5         | 6      | 0.07%   |
| Transcend           | 4         | 4      | 0.06%   |
| Smartbuy            | 4         | 4      | 0.06%   |
| SSSTC               | 3         | 4      | 0.04%   |
| QUMO                | 3         | 3      | 0.04%   |
| IBM                 | 3         | 3      | 0.04%   |
| Zheino              | 2         | 2      | 0.03%   |
| Verbatim            | 2         | 2      | 0.03%   |
| Unknown             | 2         | 2      | 0.03%   |
| Team                | 2         | 2      | 0.03%   |
| Silicon Motion      | 2         | 3      | 0.03%   |
| QUANTUM             | 2         | 2      | 0.03%   |
| Patriot             | 2         | 2      | 0.03%   |
| Mushkin             | 2         | 2      | 0.03%   |
| Intenso             | 2         | 6      | 0.03%   |
| Hewlett-Packard     | 2         | 3      | 0.03%   |
| Espada              | 2         | 3      | 0.03%   |
| XPG                 | 1         | 1      | 0.01%   |
| WD MediaMax         | 1         | 1      | 0.01%   |
| TopSunligt          | 1         | 1      | 0.01%   |
| SuperTalent         | 1         | 1      | 0.01%   |
| SandForce           | 1         | 1      | 0.01%   |
| Netac               | 1         | 1      | 0.01%   |
| MD300               | 1         | 1      | 0.01%   |
| MARSHAL             | 1         | 1      | 0.01%   |
| Kingrich            | 1         | 1      | 0.01%   |
| KingFast            | 1         | 1      | 0.01%   |
| INDMEM              | 1         | 1      | 0.01%   |
| HYPERDISK           | 1         | 1      | 0.01%   |
| HGST HTS            | 1         | 1      | 0.01%   |
| GOWE                | 1         | 1      | 0.01%   |
| Goldenfir           | 1         | 2      | 0.01%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2522      | 3459   | 38.66%  |
| WDC                 | 1736      | 2399   | 26.61%  |
| Hitachi             | 883       | 1139   | 13.53%  |
| Toshiba             | 518       | 674    | 7.94%   |
| Samsung Electronics | 443       | 608    | 6.79%   |
| HGST                | 197       | 292    | 3.02%   |
| MAXTOR              | 149       | 179    | 2.28%   |
| Fujitsu             | 46        | 60     | 0.71%   |
| IBM/Hitachi         | 16        | 19     | 0.25%   |
| IBM                 | 3         | 3      | 0.05%   |
| QUANTUM             | 2         | 2      | 0.03%   |
| Hewlett-Packard     | 2         | 3      | 0.03%   |
| Apple               | 2         | 3      | 0.03%   |
| WD MediaMax         | 1         | 1      | 0.02%   |
| MARSHAL             | 1         | 1      | 0.02%   |
| HGST HTS            | 1         | 1      | 0.02%   |
| ExcelStor           | 1         | 1      | 0.02%   |
| Asmedia             | 1         | 1      | 0.02%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5999      | 8845   | 89.91%  |
| SSD  | 652       | 847    | 9.77%   |
| NVMe | 21        | 30     | 0.31%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST31000528AS 1TB           | 7         | 9      | 2.79%   |
| Seagate ST31000524AS 1TB           | 7         | 9      | 2.79%   |
| Seagate ST3500418AS 500GB          | 5         | 6      | 1.99%   |
| Seagate ST3500412AS 500GB          | 5         | 6      | 1.99%   |
| Samsung Electronics HM321HI 320GB  | 5         | 7      | 1.99%   |
| Hitachi HDS721010DLE630 1TB        | 5         | 6      | 1.99%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 4         | 5      | 1.59%   |
| Seagate ST9500325AS 500GB          | 4         | 4      | 1.59%   |
| Seagate ST9320325AS 320GB          | 4         | 5      | 1.59%   |
| HGST HTS721010A9E630 1TB           | 4         | 5      | 1.59%   |
| HGST HTS545050A7E680 500GB         | 4         | 4      | 1.59%   |
| WDC WD1600BEVS-22RST0 160GB        | 3         | 4      | 1.2%    |
| Toshiba MQ01ABD050 500GB           | 3         | 3      | 1.2%    |
| Toshiba MK6465GSX 640GB            | 3         | 3      | 1.2%    |
| Toshiba MK3265GSX 320GB            | 3         | 3      | 1.2%    |
| Seagate ST31000333AS 1TB           | 3         | 3      | 1.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 3      | 1.2%    |
| Samsung Electronics SP0411N 34GB   | 3         | 4      | 1.2%    |
| MAXTOR 6Y080L0 82GB                | 3         | 3      | 1.2%    |
| HGST HTS545050A7E380 500GB         | 3         | 3      | 1.2%    |
| WDC WD5000AAKS-00V1A0 500GB        | 2         | 2      | 0.8%    |
| WDC WD3200BEVT-22ZCT0 320GB        | 2         | 2      | 0.8%    |
| WDC WD3200AAJS-00L7A0 320GB        | 2         | 2      | 0.8%    |
| WDC WD15EARS-00MVWB0 1TB           | 2         | 4      | 0.8%    |
| Toshiba MK3259GSXP 320GB           | 2         | 2      | 0.8%    |
| Seagate STM3500418AS 500GB         | 2         | 2      | 0.8%    |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 0.8%    |
| Seagate ST500DM005 HD502HJ 500GB   | 2         | 3      | 0.8%    |
| Seagate ST500DM002-1BC142 500GB    | 2         | 2      | 0.8%    |
| Seagate ST3750528AS 752GB          | 2         | 2      | 0.8%    |
| Seagate ST3320613AS 320GB          | 2         | 3      | 0.8%    |
| Seagate ST3250318AS 250GB          | 2         | 2      | 0.8%    |
| Seagate ST32000542AS 2TB           | 2         | 4      | 0.8%    |
| Seagate ST3160318AS 160GB          | 2         | 2      | 0.8%    |
| Samsung Electronics HM160HI 160GB  | 2         | 2      | 0.8%    |
| Samsung Electronics HD204UI 2TB    | 2         | 2      | 0.8%    |
| Samsung Electronics HD105SI 1TB    | 2         | 2      | 0.8%    |
| Hitachi HTS547550A9E384 500GB      | 2         | 2      | 0.8%    |
| Hitachi HTS543225A7A384 250GB      | 2         | 3      | 0.8%    |
| Hitachi HDT721032SLA380 320GB      | 2         | 2      | 0.8%    |
| Hitachi HDS721025CLA382 250GB      | 2         | 2      | 0.8%    |
| Hitachi HDS721010CLA332 1TB        | 2         | 2      | 0.8%    |
| HGST HTS725050A7E630 500GB         | 2         | 3      | 0.8%    |
| HGST HTS541010A9E680 1TB           | 2         | 2      | 0.8%    |
| WDC WD800JD-22LSA0 80GB            | 1         | 1      | 0.4%    |
| WDC WD800BEVS-22RST0 80GB          | 1         | 1      | 0.4%    |
| WDC WD800BB-55JKC0 80GB            | 1         | 2      | 0.4%    |
| WDC WD800BB-00JKC0 80GB            | 1         | 2      | 0.4%    |
| WDC WD800BB-00JHC0 80GB            | 1         | 1      | 0.4%    |
| WDC WD7500BPVT-22HXZT3 752GB       | 1         | 1      | 0.4%    |
| WDC WD7500BPVT-22HXZT1 752GB       | 1         | 1      | 0.4%    |
| WDC WD6400AACS-00G8B0 640GB        | 1         | 1      | 0.4%    |
| WDC WD5001AALS-00E3A0 500GB        | 1         | 1      | 0.4%    |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB   | 1         | 1      | 0.4%    |
| WDC WD5000BPVT-80HXZT1 500GB       | 1         | 1      | 0.4%    |
| WDC WD5000BPVT-24HXZT3 500GB       | 1         | 1      | 0.4%    |
| WDC WD5000BPVT-00HXZT1 500GB       | 1         | 1      | 0.4%    |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 1      | 0.4%    |
| WDC WD5000BEVT-00ZAT0 500GB        | 1         | 2      | 0.4%    |
| WDC WD5000BEVT-00A0RT0 500GB       | 1         | 1      | 0.4%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 79        | 96     | 31.6%   |
| WDC                 | 67        | 81     | 26.8%   |
| Samsung Electronics | 30        | 33     | 12%     |
| Hitachi             | 22        | 24     | 8.8%    |
| Toshiba             | 21        | 22     | 8.4%    |
| HGST                | 15        | 17     | 6%      |
| MAXTOR              | 7         | 7      | 2.8%    |
| Transcend           | 1         | 1      | 0.4%    |
| OCZ                 | 1         | 1      | 0.4%    |
| Hewlett-Packard     | 1         | 1      | 0.4%    |
| GOODRAM             | 1         | 1      | 0.4%    |
| Fujitsu             | 1         | 1      | 0.4%    |
| Crucial             | 1         | 1      | 0.4%    |
| Corsair             | 1         | 1      | 0.4%    |
| Apple               | 1         | 2      | 0.4%    |
| A-DATA Technology   | 1         | 1      | 0.4%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 12738     | 23282  | 54.2%   |
| Malfunc  | 6508      | 9722   | 27.69%  |
| Detected | 4009      | 7124   | 17.06%  |
| Failed   | 248       | 290    | 1.06%   |
| Limited  | 1         | 1      | 0.004%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 13951     | 60.71%  |
| AMD                              | 4336      | 18.87%  |
| Nvidia                           | 817       | 3.56%   |
| JMicron Technology               | 723       | 3.15%   |
| Samsung Electronics              | 658       | 2.86%   |
| Marvell Technology Group         | 382       | 1.66%   |
| ASMedia Technology               | 320       | 1.39%   |
| Sandisk                          | 245       | 1.07%   |
| SK Hynix                         | 211       | 0.92%   |
| VIA Technologies                 | 205       | 0.89%   |
| Kingston Technology Company      | 166       | 0.72%   |
| Phison Electronics               | 127       | 0.55%   |
| Silicon Integrated Systems [SiS] | 110       | 0.48%   |
| Silicon Motion                   | 105       | 0.46%   |
| Toshiba America Info Systems     | 82        | 0.36%   |
| KIOXIA                           | 67        | 0.29%   |
| Micron Technology                | 62        | 0.27%   |
| ADATA Technology                 | 62        | 0.27%   |
| Realtek Semiconductor            | 49        | 0.21%   |
| Union Memory (Shenzhen)          | 45        | 0.2%    |
| Silicon Image                    | 33        | 0.14%   |
| Lite-On Technology               | 32        | 0.14%   |
| Integrated Technology Express    | 28        | 0.12%   |
| Broadcom / LSI                   | 28        | 0.12%   |
| Solid State Storage Technology   | 22        | 0.1%    |
| LSI Logic / Symbios Logic        | 21        | 0.09%   |
| Adaptec                          | 16        | 0.07%   |
| Hewlett-Packard                  | 12        | 0.05%   |
| Micron/Crucial Technology        | 11        | 0.05%   |
| Apple                            | 6         | 0.03%   |
| ULi Electronics                  | 5         | 0.02%   |
| Shenzhen Longsys Electronics     | 5         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 5         | 0.02%   |
| Lenovo                           | 5         | 0.02%   |
| Promise Technology               | 4         | 0.02%   |
| Huawei Technologies              | 4         | 0.02%   |
| Yangtze Memory Technologies      | 3         | 0.01%   |
| OCZ Technology Group             | 3         | 0.01%   |
| MCST                             | 3         | 0.01%   |
| 3ware                            | 3         | 0.01%   |
| Seagate Technology               | 2         | 0.01%   |
| Broadcom                         | 2         | 0.01%   |
| Biwin Storage Technology         | 2         | 0.01%   |
| ATI Technologies                 | 1         | 0.004%  |
| Artop Electronic                 | 1         | 0.004%  |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 2168      | 7.33%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1317      | 4.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1222      | 4.13%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1062      | 3.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1051      | 3.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 941       | 3.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 831       | 2.81%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 809       | 2.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 737       | 2.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 619       | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 537       | 1.82%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 536       | 1.81%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 535       | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 530       | 1.79%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 471       | 1.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 458       | 1.55%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 415       | 1.4%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 404       | 1.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 373       | 1.26%   |
| Nvidia MCP61 SATA Controller                                                            | 364       | 1.23%   |
| Nvidia MCP61 IDE                                                                        | 341       | 1.15%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 337       | 1.14%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 335       | 1.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 326       | 1.1%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 306       | 1.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 294       | 0.99%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 286       | 0.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 278       | 0.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 276       | 0.93%   |
| JMicron JMB368 IDE controller                                                           | 268       | 0.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 268       | 0.91%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 255       | 0.86%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 254       | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 239       | 0.81%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 236       | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 204       | 0.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 199       | 0.67%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 197       | 0.67%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 191       | 0.65%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 190       | 0.64%   |
| AMD FCH IDE Controller                                                                  | 190       | 0.64%   |
| AMD SB600 IDE                                                                           | 188       | 0.64%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 163       | 0.55%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 163       | 0.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 161       | 0.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 159       | 0.54%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 158       | 0.53%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 148       | 0.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 144       | 0.49%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 143       | 0.48%   |
| AMD FCH SATA Controller D                                                               | 142       | 0.48%   |
| Samsung NVMe SSD Controller 980                                                         | 141       | 0.48%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 140       | 0.47%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 140       | 0.47%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 117       | 0.4%    |
| AMD 300 Series Chipset SATA Controller                                                  | 113       | 0.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 112       | 0.38%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 110       | 0.37%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 108       | 0.37%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 105       | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 14362     | 60.19%  |
| IDE  | 6721      | 28.17%  |
| NVMe | 2070      | 8.67%   |
| RAID | 662       | 2.77%   |
| SAS  | 35        | 0.15%   |
| SCSI | 12        | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 14741     | 73.59%  |
| AMD          | 5231      | 26.11%  |
| ARM          | 40        | 0.2%    |
| CentaurHauls | 6         | 0.03%   |
| Hisilicon    | 4         | 0.02%   |
| QUALCOMM     | 2         | 0.01%   |
| Unknown      | 2         | 0.01%   |
| PowerMac7,2  | 1         | 0.005%  |
| MIPS         | 1         | 0.005%  |
| MBE8C-PC     | 1         | 0.005%  |
| E8C/EATX     | 1         | 0.005%  |
| E8C-SWTX     | 1         | 0.005%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 153       | 0.76%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 143       | 0.71%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 129       | 0.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 123       | 0.61%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 122       | 0.6%    |
| Intel Pentium CPU B960 @ 2.20GHz              | 112       | 0.56%   |
| Intel Pentium 4 CPU 3.00GHz                   | 112       | 0.56%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 108       | 0.54%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 106       | 0.53%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 103       | 0.51%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 103       | 0.51%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 102       | 0.51%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 102       | 0.51%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 101       | 0.5%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 100       | 0.5%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 100       | 0.5%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 97        | 0.48%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 95        | 0.47%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 94        | 0.47%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 94        | 0.47%   |
| AMD FX-6300 Six-Core Processor                | 92        | 0.46%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 89        | 0.44%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 89        | 0.44%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 89        | 0.44%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 87        | 0.43%   |
| AMD Athlon II X2 250 Processor                | 83        | 0.41%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 82        | 0.41%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 82        | 0.41%   |
| AMD E-450 APU with Radeon HD Graphics         | 82        | 0.41%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 79        | 0.39%   |
| AMD FX-8350 Eight-Core Processor              | 79        | 0.39%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 77        | 0.38%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 75        | 0.37%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 74        | 0.37%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 74        | 0.37%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 69        | 0.34%   |
| AMD Ryzen 5 3600 6-Core Processor             | 69        | 0.34%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 68        | 0.34%   |
| AMD FX-4300 Quad-Core Processor               | 68        | 0.34%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 67        | 0.33%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 67        | 0.33%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 67        | 0.33%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 66        | 0.33%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 66        | 0.33%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 66        | 0.33%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 65        | 0.32%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 64        | 0.32%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 64        | 0.32%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 63        | 0.31%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz          | 62        | 0.31%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 61        | 0.3%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 61        | 0.3%    |
| AMD A10-4600M APU with Radeon HD Graphics     | 61        | 0.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 60        | 0.3%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 59        | 0.29%   |
| AMD FX-8320 Eight-Core Processor              | 59        | 0.29%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 58        | 0.29%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 57        | 0.28%   |
| Intel Atom CPU N570 @ 1.66GHz                 | 57        | 0.28%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 55        | 0.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 3203      | 15.9%   |
| Intel Core i3                  | 2359      | 11.71%  |
| Intel Core i7                  | 1533      | 7.61%   |
| Intel Celeron                  | 1428      | 7.09%   |
| Intel Pentium                  | 1360      | 6.75%   |
| Intel Core 2 Duo               | 1247      | 6.19%   |
| Intel Atom                     | 815       | 4.05%   |
| AMD Ryzen 5                    | 646       | 3.21%   |
| AMD FX                         | 553       | 2.75%   |
| Intel Pentium Dual-Core        | 516       | 2.56%   |
| Intel Xeon                     | 480       | 2.38%   |
| AMD Athlon 64 X2               | 398       | 1.98%   |
| Intel Core 2 Quad              | 308       | 1.53%   |
| AMD Athlon II X2               | 297       | 1.47%   |
| AMD A6                         | 289       | 1.43%   |
| Other                          | 282       | 1.4%    |
| AMD Ryzen 7                    | 256       | 1.27%   |
| Intel Pentium 4                | 251       | 1.25%   |
| AMD A8                         | 239       | 1.19%   |
| AMD A4                         | 236       | 1.17%   |
| Intel Pentium Dual             | 223       | 1.11%   |
| AMD A10                        | 215       | 1.07%   |
| Intel Core 2                   | 210       | 1.04%   |
| AMD Ryzen 3                    | 208       | 1.03%   |
| AMD Phenom II X4               | 176       | 0.87%   |
| AMD E                          | 153       | 0.76%   |
| AMD Athlon II X4               | 139       | 0.69%   |
| Intel Genuine                  | 131       | 0.65%   |
| AMD E1                         | 115       | 0.57%   |
| AMD E2                         | 104       | 0.52%   |
| AMD Athlon II X3               | 104       | 0.52%   |
| Intel Pentium D                | 101       | 0.5%    |
| AMD Athlon                     | 91        | 0.45%   |
| AMD Phenom                     | 90        | 0.45%   |
| AMD Athlon 64                  | 86        | 0.43%   |
| Intel Celeron M                | 70        | 0.35%   |
| Intel Pentium Silver           | 68        | 0.34%   |
| Intel Pentium Gold             | 68        | 0.34%   |
| AMD Phenom II X6               | 66        | 0.33%   |
| AMD Athlon X4                  | 66        | 0.33%   |
| AMD Turion 64 X2 Mobile        | 65        | 0.32%   |
| AMD Phenom II                  | 65        | 0.32%   |
| Intel Celeron Dual-Core        | 64        | 0.32%   |
| AMD Sempron                    | 50        | 0.25%   |
| Intel Pentium M                | 47        | 0.23%   |
| AMD Ryzen 9                    | 41        | 0.2%    |
| AMD C-60                       | 37        | 0.18%   |
| AMD Athlon X2                  | 36        | 0.18%   |
| AMD Phenom II X2               | 32        | 0.16%   |
| AMD Athlon II                  | 32        | 0.16%   |
| Intel Celeron D                | 28        | 0.14%   |
| Intel Core i9                  | 27        | 0.13%   |
| AMD Ryzen 7 PRO                | 27        | 0.13%   |
| Intel Xeon Silver              | 25        | 0.12%   |
| AMD C-50                       | 25        | 0.12%   |
| AMD Turion II Dual-Core        | 24        | 0.12%   |
| AMD Turion X2 Dual-Core Mobile | 20        | 0.1%    |
| Intel Core Duo                 | 19        | 0.09%   |
| AMD Phenom II X3               | 19        | 0.09%   |
| Intel Core m3                  | 18        | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 10676     | 52.32%  |
| 4       | 5435      | 26.64%  |
| 1       | 1227      | 6.01%   |
| Unknown | 1100      | 5.39%   |
| 6       | 1017      | 4.98%   |
| 8       | 482       | 2.36%   |
| 3       | 286       | 1.4%    |
| 12      | 74        | 0.36%   |
| 16      | 37        | 0.18%   |
| 10      | 21        | 0.1%    |
| 24      | 15        | 0.07%   |
| 20      | 10        | 0.05%   |
| 32      | 6         | 0.03%   |
| 96      | 4         | 0.02%   |
| 40      | 3         | 0.01%   |
| 28      | 2         | 0.01%   |
| 18      | 2         | 0.01%   |
| 14      | 2         | 0.01%   |
| 192     | 1         | 0.005%  |
| 72      | 1         | 0.005%  |
| 22      | 1         | 0.005%  |
| 15      | 1         | 0.005%  |
| 5       | 1         | 0.005%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 19861     | 99.08%  |
| 2       | 143       | 0.71%   |
| Unknown | 32        | 0.16%   |
| 4       | 6         | 0.03%   |
| 8       | 1         | 0.005%  |
| 3       | 1         | 0.005%  |
| 0       | 1         | 0.005%  |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 10331     | 50.63%  |
| 2       | 8972      | 43.97%  |
| Unknown | 1100      | 5.39%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 19301     | 96.21%  |
| 32-bit         | 525       | 2.62%   |
| Unknown        | 225       | 1.12%   |
| 64-bit         | 10        | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 2016      | 9.84%   |
| Unknown    | 1846      | 9.01%   |
| 0x306a9    | 1686      | 8.23%   |
| 0x1067a    | 1331      | 6.5%    |
| 0x306c3    | 921       | 4.49%   |
| 0x010000c8 | 591       | 2.88%   |
| 0x6fd      | 562       | 2.74%   |
| 0x20655    | 514       | 2.51%   |
| 0x10676    | 393       | 1.92%   |
| 0x506e3    | 385       | 1.88%   |
| 0x906ea    | 372       | 1.82%   |
| 0x06001119 | 357       | 1.74%   |
| 0x106ca    | 336       | 1.64%   |
| 0x906e9    | 329       | 1.61%   |
| 0x30678    | 315       | 1.54%   |
| 0x40651    | 281       | 1.37%   |
| 0x6fb      | 253       | 1.23%   |
| 0x806ea    | 236       | 1.15%   |
| 0x406c4    | 232       | 1.13%   |
| 0x406e3    | 223       | 1.09%   |
| 0x806ec    | 220       | 1.07%   |
| 0x806e9    | 218       | 1.06%   |
| 0x06000852 | 207       | 1.01%   |
| 0x08108109 | 199       | 0.97%   |
| 0x03000027 | 197       | 0.96%   |
| 0x20652    | 189       | 0.92%   |
| 0x05000119 | 182       | 0.89%   |
| 0x0600084f | 171       | 0.83%   |
| 0x306d4    | 159       | 0.78%   |
| 0x6f6      | 146       | 0.71%   |
| 0x07030105 | 143       | 0.7%    |
| 0x30661    | 136       | 0.66%   |
| 0x010000db | 136       | 0.66%   |
| 0x106e5    | 132       | 0.64%   |
| 0x106c2    | 132       | 0.64%   |
| 0x10661    | 132       | 0.64%   |
| 0x06006705 | 131       | 0.64%   |
| 0x406c3    | 128       | 0.62%   |
| 0x506c9    | 125       | 0.61%   |
| 0x0800820d | 117       | 0.57%   |
| 0x706a1    | 113       | 0.55%   |
| 0xa0653    | 112       | 0.55%   |
| 0x08701021 | 111       | 0.54%   |
| 0x08108102 | 111       | 0.54%   |
| 0x906eb    | 108       | 0.53%   |
| 0x806c1    | 106       | 0.52%   |
| 0x6f2      | 95        | 0.46%   |
| 0x06003106 | 92        | 0.45%   |
| 0x0810100b | 87        | 0.42%   |
| 0x0700010f | 84        | 0.41%   |
| 0xf49      | 82        | 0.4%    |
| 0x6e8      | 75        | 0.37%   |
| 0x08600106 | 75        | 0.37%   |
| 0x010000c7 | 73        | 0.36%   |
| 0xf41      | 72        | 0.35%   |
| 0x08001138 | 71        | 0.35%   |
| 0x706e5    | 69        | 0.34%   |
| 0x206d7    | 68        | 0.33%   |
| 0x06006704 | 68        | 0.33%   |
| 0x0600063d | 68        | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 2153      | 10.69%  |
| IvyBridge        | 1816      | 9.02%   |
| KabyLake         | 1783      | 8.85%   |
| Penryn           | 1751      | 8.69%   |
| Haswell          | 1322      | 6.56%   |
| Core             | 1316      | 6.53%   |
| K10              | 1106      | 5.49%   |
| Piledriver       | 804       | 3.99%   |
| Westmere         | 767       | 3.81%   |
| Silvermont       | 742       | 3.68%   |
| Skylake          | 708       | 3.52%   |
| K8 Hammer        | 607       | 3.01%   |
| Bonnell          | 571       | 2.84%   |
| Zen+             | 476       | 2.36%   |
| NetBurst         | 463       | 2.3%    |
| Zen 2            | 346       | 1.72%   |
| Unknown          | 336       | 1.67%   |
| Zen              | 314       | 1.56%   |
| Excavator        | 297       | 1.47%   |
| Bobcat           | 268       | 1.33%   |
| CometLake        | 222       | 1.1%    |
| K10 Llano        | 215       | 1.07%   |
| Broadwell        | 196       | 0.97%   |
| Puma             | 185       | 0.92%   |
| Nehalem          | 177       | 0.88%   |
| P6               | 168       | 0.83%   |
| Goldmont plus    | 164       | 0.81%   |
| Goldmont         | 141       | 0.7%    |
| Bulldozer        | 132       | 0.66%   |
| TigerLake        | 122       | 0.61%   |
| Jaguar           | 108       | 0.54%   |
| Steamroller      | 102       | 0.51%   |
| Icelake          | 101       | 0.5%    |
| Zen 3            | 79        | 0.39%   |
| K8 & K10 hybrid  | 63        | 0.31%   |
| K6               | 11        | 0.05%   |
| Tremont          | 5         | 0.02%   |
| Alderlake Hybrid | 4         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 9400      | 40.19%  |
| Nvidia                                       | 7901      | 33.78%  |
| AMD                                          | 5854      | 25.03%  |
| Matrox Electronics Systems                   | 81        | 0.35%   |
| ASPEED Technology                            | 71        | 0.3%    |
| Silicon Integrated Systems [SiS]             | 34        | 0.15%   |
| VIA Technologies                             | 26        | 0.11%   |
| ATI Technologies                             | 10        | 0.04%   |
| Huawei Technologies                          | 6         | 0.03%   |
| S3 Graphics                                  | 3         | 0.01%   |
| Silicon Motion                               | 2         | 0.01%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.004%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1437      | 5.8%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 989       | 3.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 381       | 1.54%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 358       | 1.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 346       | 1.4%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 322       | 1.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 319       | 1.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 317       | 1.28%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 310       | 1.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 295       | 1.19%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 293       | 1.18%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 240       | 0.97%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 229       | 0.92%   |
| Nvidia GT218 [GeForce 210]                                                               | 225       | 0.91%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 223       | 0.9%    |
| Intel UHD Graphics 620                                                                   | 221       | 0.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 218       | 0.88%   |
| Intel HD Graphics 620                                                                    | 210       | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 209       | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 209       | 0.84%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 205       | 0.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 200       | 0.81%   |
| Intel HD Graphics 630                                                                    | 199       | 0.8%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 199       | 0.8%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 198       | 0.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 197       | 0.8%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 188       | 0.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 184       | 0.74%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 181       | 0.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 178       | 0.72%   |
| Intel HD Graphics 530                                                                    | 177       | 0.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 176       | 0.71%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 173       | 0.7%    |
| AMD Renoir                                                                               | 165       | 0.67%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 160       | 0.65%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 156       | 0.63%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 155       | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 147       | 0.59%   |
| Intel HD Graphics 5500                                                                   | 141       | 0.57%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 140       | 0.57%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 136       | 0.55%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 132       | 0.53%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 132       | 0.53%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 131       | 0.53%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 129       | 0.52%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 124       | 0.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 117       | 0.47%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 115       | 0.46%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 109       | 0.44%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 109       | 0.44%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 108       | 0.44%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 106       | 0.43%   |
| Intel HD Graphics 500                                                                    | 104       | 0.42%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 102       | 0.41%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 102       | 0.41%   |
| AMD RS780L [Radeon 3000]                                                                 | 102       | 0.41%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 100       | 0.4%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 100       | 0.4%    |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 99        | 0.4%    |
| Nvidia GK208B [GeForce GT 730]                                                           | 98        | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| 1 x Intel                     | 6343      | 31.29%  |
| 1 x Nvidia                    | 5388      | 26.58%  |
| 1 x AMD                       | 4446      | 21.93%  |
| Intel + Nvidia                | 2354      | 11.61%  |
| 2 x AMD                       | 756       | 3.73%   |
| Intel + AMD                   | 543       | 2.68%   |
| AMD + Nvidia                  | 124       | 0.61%   |
| 1 x Matrox                    | 77        | 0.38%   |
| 1 x ASPEED                    | 61        | 0.3%    |
| Other                         | 57        | 0.28%   |
| 1 x SiS                       | 34        | 0.17%   |
| 2 x Nvidia                    | 29        | 0.14%   |
| 1 x VIA                       | 26        | 0.13%   |
| Nvidia + ASPEED               | 6         | 0.03%   |
| 1 x Huawei Technologies       | 6         | 0.03%   |
| Nvidia + Matrox               | 4         | 0.02%   |
| AMD + ASPEED                  | 4         | 0.02%   |
| 3 x Nvidia                    | 3         | 0.01%   |
| 3 x AMD                       | 2         | 0.01%   |
| 1 x Silicon Motion            | 2         | 0.01%   |
| 1 x S3 Graphics               | 2         | 0.01%   |
| 2 x AMD + 1 x Nvidia          | 1         | 0.005%  |
| 1 x XGI                       | 1         | 0.005%  |
| Intel + 2 x Nvidia            | 1         | 0.005%  |
| Intel + 2 x AMD               | 1         | 0.005%  |
| Intel + SiS + 1 x S3 Graphics | 1         | 0.005%  |
| Intel + AMD + 4 x Nvidia      | 1         | 0.005%  |
| AMD + 2 x Nvidia              | 1         | 0.005%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 16265     | 78.29%  |
| Proprietary | 2932      | 14.11%  |
| Unknown     | 1579      | 7.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5831      | 27.73%  |
| 1.01-2.0   | 5442      | 25.88%  |
| 0.01-0.5   | 4723      | 22.46%  |
| 0.51-1.0   | 2939      | 13.98%  |
| 3.01-4.0   | 1429      | 6.8%    |
| 7.01-8.0   | 278       | 1.32%   |
| 5.01-6.0   | 199       | 0.95%   |
| 2.01-3.0   | 141       | 0.67%   |
| 8.01-16.0  | 37        | 0.18%   |
| 16.01-24.0 | 4         | 0.02%   |
| 4.01-5.0   | 1         | 0.005%  |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 3794      | 19.33%  |
| AU Optronics            | 2180      | 11.11%  |
| LG Display              | 1574      | 8.02%   |
| Goldstar                | 1483      | 7.56%   |
| Acer                    | 1167      | 5.95%   |
| Chimei Innolux          | 1113      | 5.67%   |
| BOE                     | 975       | 4.97%   |
| BenQ                    | 918       | 4.68%   |
| Chi Mei Optoelectronics | 728       | 3.71%   |
| Philips                 | 671       | 3.42%   |
| Dell                    | 515       | 2.62%   |
| ViewSonic               | 511       | 2.6%    |
| AOC                     | 462       | 2.35%   |
| Ancor Communications    | 358       | 1.82%   |
| Hewlett-Packard         | 299       | 1.52%   |
| Lenovo                  | 271       | 1.38%   |
| NEC Computers           | 257       | 1.31%   |
| LG Philips              | 204       | 1.04%   |
| HannStar                | 179       | 0.91%   |
| Sony                    | 146       | 0.74%   |
| Iiyama                  | 142       | 0.72%   |
| CPT                     | 110       | 0.56%   |
| InfoVision              | 106       | 0.54%   |
| PANDA                   | 102       | 0.52%   |
| Apple                   | 102       | 0.52%   |
| Sharp                   | 87        | 0.44%   |
| Unknown                 | 75        | 0.38%   |
| Plain Tree Systems      | 55        | 0.28%   |
| Envision Peripherals    | 53        | 0.27%   |
| LG Electronics          | 47        | 0.24%   |
| HHT                     | 44        | 0.22%   |
| ASUSTek Computer        | 44        | 0.22%   |
| Toshiba                 | 40        | 0.2%    |
| Packard Bell            | 34        | 0.17%   |
| ___                     | 32        | 0.16%   |
| InnoLux Display         | 29        | 0.15%   |
| Quanta Display          | 26        | 0.13%   |
| MiTAC                   | 26        | 0.13%   |
| Panasonic               | 23        | 0.12%   |
| Fujitsu Siemens         | 22        | 0.11%   |
| ECS                     | 22        | 0.11%   |
| CHR                     | 20        | 0.1%    |
| MStar                   | 19        | 0.1%    |
| KTC                     | 17        | 0.09%   |
| JRY                     | 17        | 0.09%   |
| VIE                     | 15        | 0.08%   |
| Mi                      | 15        | 0.08%   |
| HKC                     | 15        | 0.08%   |
| S2-Tek                  | 14        | 0.07%   |
| Nvidia                  | 14        | 0.07%   |
| MSI                     | 14        | 0.07%   |
| Hitachi                 | 14        | 0.07%   |
| Haier                   | 14        | 0.07%   |
| CVT                     | 11        | 0.06%   |
| CSO                     | 11        | 0.06%   |
| BBK                     | 11        | 0.06%   |
| RTK                     | 10        | 0.05%   |
| Belinea                 | 10        | 0.05%   |
| AGO                     | 10        | 0.05%   |
| GDH                     | 9         | 0.05%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 212       | 1.06%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 171       | 0.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 152       | 0.76%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 145       | 0.72%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 138       | 0.69%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 93        | 0.46%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 331x207mm 15.4-inch      | 88        | 0.44%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 84        | 0.42%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 79        | 0.39%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 79        | 0.39%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 79        | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 78        | 0.39%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch      | 77        | 0.38%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 73        | 0.36%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch      | 68        | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 66        | 0.33%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch             | 65        | 0.32%   |
| Acer AL1716 ACRAD46 1280x1024 338x270mm 17.0-inch                         | 64        | 0.32%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 63        | 0.31%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch      | 61        | 0.3%    |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 61        | 0.3%    |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch      | 59        | 0.29%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                   | 59        | 0.29%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 58        | 0.29%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 58        | 0.29%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 57        | 0.28%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                       | 56        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 56        | 0.28%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 54        | 0.27%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 53        | 0.26%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch      | 52        | 0.26%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 47        | 0.23%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 46        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch           | 46        | 0.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 46        | 0.23%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 46        | 0.23%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                   | 45        | 0.22%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch               | 45        | 0.22%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 45        | 0.22%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 44        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 44        | 0.22%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch       | 43        | 0.21%   |
| HHT ActviPanel V5 HHT0030 3840x2160 944x398mm 40.3-inch                   | 43        | 0.21%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 43        | 0.21%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                   | 42        | 0.21%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 41        | 0.2%    |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 376x301mm 19.0-inch       | 40        | 0.2%    |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch               | 40        | 0.2%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 39        | 0.19%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                       | 39        | 0.19%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                  | 39        | 0.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch  | 39        | 0.19%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 38        | 0.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 37        | 0.18%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch      | 36        | 0.18%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch      | 34        | 0.17%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch      | 33        | 0.16%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 33        | 0.16%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 33        | 0.16%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 33        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 6831      | 35.46%  |
| 1366x768 (WXGA)    | 4691      | 24.35%  |
| 1280x1024 (SXGA)   | 2186      | 11.35%  |
| 1600x900 (HD+)     | 1051      | 5.46%   |
| 1280x800 (WXGA)    | 704       | 3.65%   |
| 1440x900 (WXGA+)   | 666       | 3.46%   |
| 1680x1050 (WSXGA+) | 648       | 3.36%   |
| 3840x2160 (4K)     | 412       | 2.14%   |
| 1024x600           | 356       | 1.85%   |
| 2560x1440 (QHD)    | 339       | 1.76%   |
| 1920x1200 (WUXGA)  | 282       | 1.46%   |
| 1360x768           | 188       | 0.98%   |
| 1024x768 (XGA)     | 187       | 0.97%   |
| 2560x1080          | 101       | 0.52%   |
| 1600x1200          | 90        | 0.47%   |
| Unknown            | 82        | 0.43%   |
| 1280x720 (HD)      | 46        | 0.24%   |
| 3440x1440          | 40        | 0.21%   |
| 1400x1050          | 33        | 0.17%   |
| 1920x540           | 31        | 0.16%   |
| 2160x1440          | 28        | 0.15%   |
| 2288x1287          | 24        | 0.12%   |
| 3840x1080          | 21        | 0.11%   |
| 2560x1600          | 19        | 0.1%    |
| 2880x1800          | 17        | 0.09%   |
| 2048x1536          | 14        | 0.07%   |
| 1680x945           | 14        | 0.07%   |
| 1152x864           | 13        | 0.07%   |
| 1280x960           | 11        | 0.06%   |
| 2048x1152          | 9         | 0.05%   |
| 1920x1440          | 8         | 0.04%   |
| 4480x1440          | 7         | 0.04%   |
| 3200x1800 (QHD+)   | 6         | 0.03%   |
| 3000x2000          | 6         | 0.03%   |
| 3840x2400          | 5         | 0.03%   |
| 2736x1824          | 5         | 0.03%   |
| 5760x1080          | 4         | 0.02%   |
| 3600x1080          | 4         | 0.02%   |
| 3200x1080          | 4         | 0.02%   |
| 2880x1920          | 4         | 0.02%   |
| 2256x1504          | 4         | 0.02%   |
| 2160x1200          | 4         | 0.02%   |
| 1280x768           | 4         | 0.02%   |
| 1024x576           | 4         | 0.02%   |
| 7680x2160          | 3         | 0.02%   |
| 5760x2160          | 3         | 0.02%   |
| 3840x1600          | 3         | 0.02%   |
| 3456x2160          | 3         | 0.02%   |
| 2520x1680          | 3         | 0.02%   |
| 2240x1400          | 3         | 0.02%   |
| 4000x1440          | 2         | 0.01%   |
| 3840x1200          | 2         | 0.01%   |
| 3286x1080          | 2         | 0.01%   |
| 3200x900           | 2         | 0.01%   |
| 3200x2000          | 2         | 0.01%   |
| 2960x1050          | 2         | 0.01%   |
| 2560x1024          | 2         | 0.01%   |
| 1920x1280          | 2         | 0.01%   |
| 8704x2160          | 1         | 0.01%   |
| 800x1280           | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 5929      | 30.16%  |
| 17      | 1953      | 9.94%   |
| 21      | 1697      | 8.63%   |
| 19      | 1534      | 7.8%    |
| 23      | 1418      | 7.21%   |
| 24      | 1072      | 5.45%   |
| 13      | 805       | 4.1%    |
| 14      | 708       | 3.6%    |
| 27      | 675       | 3.43%   |
| 18      | 618       | 3.14%   |
| 20      | 518       | 2.64%   |
| Unknown | 418       | 2.13%   |
| 10      | 387       | 1.97%   |
| 22      | 376       | 1.91%   |
| 11      | 237       | 1.21%   |
| 12      | 196       | 1%      |
| 31      | 156       | 0.79%   |
| 34      | 116       | 0.59%   |
| 40      | 108       | 0.55%   |
| 54      | 96        | 0.49%   |
| 72      | 87        | 0.44%   |
| 32      | 84        | 0.43%   |
| 16      | 84        | 0.43%   |
| 26      | 51        | 0.26%   |
| 52      | 47        | 0.24%   |
| 25      | 36        | 0.18%   |
| 84      | 29        | 0.15%   |
| 48      | 28        | 0.14%   |
| 42      | 24        | 0.12%   |
| 8       | 22        | 0.11%   |
| 43      | 15        | 0.08%   |
| 142     | 14        | 0.07%   |
| 28      | 14        | 0.07%   |
| 46      | 10        | 0.05%   |
| 37      | 10        | 0.05%   |
| 65      | 8         | 0.04%   |
| 55      | 8         | 0.04%   |
| 33      | 8         | 0.04%   |
| 50      | 7         | 0.04%   |
| 47      | 7         | 0.04%   |
| 39      | 7         | 0.04%   |
| 29      | 7         | 0.04%   |
| 99      | 4         | 0.02%   |
| 60      | 4         | 0.02%   |
| 49      | 3         | 0.02%   |
| 9       | 3         | 0.02%   |
| 74      | 2         | 0.01%   |
| 64      | 2         | 0.01%   |
| 57      | 2         | 0.01%   |
| 44      | 2         | 0.01%   |
| 41      | 2         | 0.01%   |
| 36      | 2         | 0.01%   |
| 115     | 1         | 0.01%   |
| 75      | 1         | 0.01%   |
| 66      | 1         | 0.01%   |
| 59      | 1         | 0.01%   |
| 35      | 1         | 0.01%   |
| 3       | 1         | 0.01%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 7919      | 40.68%  |
| 401-500        | 3669      | 18.85%  |
| 501-600        | 3081      | 15.83%  |
| 351-400        | 2125      | 10.92%  |
| 201-300        | 1286      | 6.61%   |
| Unknown        | 418       | 2.15%   |
| 1001-1500      | 221       | 1.14%   |
| 601-700        | 209       | 1.07%   |
| 701-800        | 207       | 1.06%   |
| 1501-2000      | 119       | 0.61%   |
| 801-900        | 85        | 0.44%   |
| 901-1000       | 85        | 0.44%   |
| 101-200        | 22        | 0.11%   |
| More than 2000 | 19        | 0.1%    |
| 1-100          | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 13243     | 70.62%  |
| 16/10   | 2272      | 12.12%  |
| 5/4     | 2059      | 10.98%  |
| 4/3     | 489       | 2.61%   |
| Unknown | 292       | 1.56%   |
| 21/9    | 166       | 0.89%   |
| 3/2     | 164       | 0.87%   |
| 6/5     | 41        | 0.22%   |
| 1.00    | 14        | 0.07%   |
| 32/9    | 8         | 0.04%   |
| 2.00    | 1         | 0.01%   |
| 1.96    | 1         | 0.01%   |
| 0.80    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |
| 0.45    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 5804      | 29.69%  |
| 201-250        | 3878      | 19.84%  |
| 151-200        | 2533      | 12.96%  |
| 141-150        | 1529      | 7.82%   |
| 81-90          | 1107      | 5.66%   |
| 121-130        | 733       | 3.75%   |
| 301-350        | 721       | 3.69%   |
| Unknown        | 418       | 2.14%   |
| 71-80          | 396       | 2.03%   |
| 41-50          | 390       | 2%      |
| 351-500        | 370       | 1.89%   |
| More than 1000 | 337       | 1.72%   |
| 251-300        | 302       | 1.54%   |
| 51-60          | 237       | 1.21%   |
| 501-1000       | 194       | 0.99%   |
| 131-140        | 189       | 0.97%   |
| 61-70          | 167       | 0.85%   |
| 111-120        | 134       | 0.69%   |
| 91-100         | 86        | 0.44%   |
| 1-40           | 23        | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 8448      | 44.22%  |
| 101-120       | 6515      | 34.1%   |
| 121-160       | 2861      | 14.98%  |
| Unknown       | 418       | 2.19%   |
| 1-50          | 395       | 2.07%   |
| 161-240       | 376       | 1.97%   |
| More than 240 | 90        | 0.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 17691     | 86.78%  |
| 2     | 1512      | 7.42%   |
| 0     | 1093      | 5.36%   |
| 3     | 87        | 0.43%   |
| 4     | 3         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 12776     | 42.83%  |
| Qualcomm Atheros                       | 5516      | 18.49%  |
| Intel                                  | 4324      | 14.49%  |
| Broadcom                               | 1785      | 5.98%   |
| Nvidia                                 | 674       | 2.26%   |
| Marvell Technology Group               | 639       | 2.14%   |
| Ralink                                 | 498       | 1.67%   |
| Broadcom Limited                       | 481       | 1.61%   |
| Huawei Technologies                    | 455       | 1.53%   |
| Ralink Technology                      | 389       | 1.3%    |
| TP-Link                                | 205       | 0.69%   |
| VIA Technologies                       | 176       | 0.59%   |
| D-Link                                 | 153       | 0.51%   |
| MediaTek                               | 151       | 0.51%   |
| D-Link System                          | 137       | 0.46%   |
| ASUSTek Computer                       | 122       | 0.41%   |
| JMicron Technology                     | 110       | 0.37%   |
| Qualcomm Atheros Communications        | 108       | 0.36%   |
| Attansic Technology                    | 101       | 0.34%   |
| Xiaomi                                 | 98        | 0.33%   |
| ZTE WCDMA Technologies MSM             | 95        | 0.32%   |
| Silicon Integrated Systems [SiS]       | 75        | 0.25%   |
| Samsung Electronics                    | 68        | 0.23%   |
| Gemtek                                 | 34        | 0.11%   |
| Sundance Technology Inc / IC Plus      | 32        | 0.11%   |
| 3Com                                   | 31        | 0.1%    |
| ASIX Electronics                       | 29        | 0.1%    |
| Qualcomm                               | 26        | 0.09%   |
| HTC (High Tech Computer)               | 23        | 0.08%   |
| Ericsson Business Mobile Networks      | 23        | 0.08%   |
| Hewlett-Packard                        | 22        | 0.07%   |
| Microsoft                              | 21        | 0.07%   |
| Sierra Wireless                        | 20        | 0.07%   |
| IBM                                    | 18        | 0.06%   |
| Vimtron Electronics                    | 17        | 0.06%   |
| NetGear                                | 16        | 0.05%   |
| Mercucys                               | 16        | 0.05%   |
| Lenovo                                 | 16        | 0.05%   |
| Sony Ericsson Mobile Communications AB | 15        | 0.05%   |
| ZyXEL Communications                   | 14        | 0.05%   |
| HMD Global                             | 14        | 0.05%   |
| Dell                                   | 14        | 0.05%   |
| Microchip Technology                   | 13        | 0.04%   |
| IMC Networks                           | 13        | 0.04%   |
| T & A Mobile Phones                    | 12        | 0.04%   |
| Spreadtrum Communications              | 12        | 0.04%   |
| GCT Semiconductor                      | 12        | 0.04%   |
| Fibocom                                | 12        | 0.04%   |
| U-Blox                                 | 11        | 0.04%   |
| Mellanox Technologies                  | 10        | 0.03%   |
| LSI                                    | 9         | 0.03%   |
| Tenda                                  | 8         | 0.03%   |
| NTmore                                 | 8         | 0.03%   |
| Xilinx                                 | 7         | 0.02%   |
| Aquantia                               | 7         | 0.02%   |
| Android                                | 7         | 0.02%   |
| STMicroelectronics                     | 6         | 0.02%   |
| Micro Star International               | 6         | 0.02%   |
| ICS Advent                             | 6         | 0.02%   |
| Apple                                  | 6         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 9397      | 28.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1892      | 5.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1298      | 3.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 787       | 2.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 546       | 1.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 512       | 1.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 497       | 1.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 426       | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 415       | 1.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 384       | 1.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 325       | 0.97%   |
| Nvidia MCP61 Ethernet                                                   | 323       | 0.97%   |
| Broadcom BCM43142 802.11b/g/n                                           | 271       | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 269       | 0.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 247       | 0.74%   |
| Huawei Modem/Networkcard                                                | 236       | 0.71%   |
| Ralink MT7601U Wireless Adapter                                         | 234       | 0.7%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 220       | 0.66%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 215       | 0.64%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 212       | 0.64%   |
| Intel Wi-Fi 6 AX200                                                     | 212       | 0.64%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 201       | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 200       | 0.6%    |
| Intel Wireless 8265 / 8275                                              | 200       | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 192       | 0.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 183       | 0.55%   |
| Intel Ethernet Connection (2) I219-V                                    | 181       | 0.54%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                           | 178       | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 176       | 0.53%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 176       | 0.53%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 176       | 0.53%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 168       | 0.5%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 168       | 0.5%    |
| Intel 82579V Gigabit Network Connection                                 | 166       | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 162       | 0.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 160       | 0.48%   |
| Intel Wireless 3165                                                     | 159       | 0.48%   |
| Intel I211 Gigabit Network Connection                                   | 153       | 0.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 153       | 0.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 146       | 0.44%   |
| Intel Wireless 7265                                                     | 144       | 0.43%   |
| Intel WiFi Link 5100                                                    | 138       | 0.41%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 131       | 0.39%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 127       | 0.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 121       | 0.36%   |
| Intel Centrino Wireless-N 130                                           | 116       | 0.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 113       | 0.34%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 112       | 0.34%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 111       | 0.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 111       | 0.33%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 110       | 0.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 110       | 0.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 107       | 0.32%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 106       | 0.32%   |
| Intel Wireless 7260                                                     | 106       | 0.32%   |
| Attansic AR8152 v2.0 Fast Ethernet                                      | 101       | 0.3%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 98        | 0.29%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 98        | 0.29%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 95        | 0.28%   |
| Intel Wi-Fi 6 AX201                                                     | 94        | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros                | 4003      | 32.07%  |
| Intel                           | 3024      | 24.22%  |
| Realtek Semiconductor           | 2233      | 17.89%  |
| Broadcom                        | 1251      | 10.02%  |
| Ralink                          | 498       | 3.99%   |
| Ralink Technology               | 389       | 3.12%   |
| Broadcom Limited                | 236       | 1.89%   |
| TP-Link                         | 180       | 1.44%   |
| D-Link                          | 135       | 1.08%   |
| ASUSTek Computer                | 111       | 0.89%   |
| Qualcomm Atheros Communications | 108       | 0.87%   |
| MEDIATEK                        | 82        | 0.66%   |
| D-Link System                   | 62        | 0.5%    |
| Microsoft                       | 21        | 0.17%   |
| Sierra Wireless                 | 20        | 0.16%   |
| Mercucys                        | 16        | 0.13%   |
| NetGear                         | 15        | 0.12%   |
| IMC Networks                    | 13        | 0.1%    |
| ZyXEL Communications            | 12        | 0.1%    |
| Fibocom                         | 12        | 0.1%    |
| Tenda                           | 8         | 0.06%   |
| Dell                            | 8         | 0.06%   |
| Micro Star International        | 6         | 0.05%   |
| Marvell Technology Group        | 5         | 0.04%   |
| Edimax Technology               | 5         | 0.04%   |
| ZyDAS                           | 3         | 0.02%   |
| VIA Technologies                | 3         | 0.02%   |
| Texas Instruments               | 3         | 0.02%   |
| Hewlett-Packard                 | 3         | 0.02%   |
| TRENDnet                        | 2         | 0.02%   |
| Linksys                         | 2         | 0.02%   |
| Fujitsu Siemens Computers       | 2         | 0.02%   |
| ASUSTek Computer (wrong ID)     | 2         | 0.02%   |
| Z-Com                           | 1         | 0.01%   |
| Wilocity                        | 1         | 0.01%   |
| Wacom                           | 1         | 0.01%   |
| Qualcomm                        | 1         | 0.01%   |
| Qcom                            | 1         | 0.01%   |
| Chu Yuen Enterprise             | 1         | 0.01%   |
| BUFFALO                         | 1         | 0.01%   |
| Belkin Components               | 1         | 0.01%   |
| Askey Computer                  | 1         | 0.01%   |
| Accton Technology               | 1         | 0.01%   |
| AboCom Systems                  | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1298      | 10.35%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 787       | 6.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 546       | 4.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 512       | 4.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 426       | 3.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 384       | 3.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 325       | 2.59%   |
| Broadcom BCM43142 802.11b/g/n                                           | 271       | 2.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 269       | 2.14%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 247       | 1.97%   |
| Ralink MT7601U Wireless Adapter                                         | 234       | 1.87%   |
| Intel Wi-Fi 6 AX200                                                     | 212       | 1.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 200       | 1.59%   |
| Intel Wireless 8265 / 8275                                              | 200       | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 183       | 1.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 176       | 1.4%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 176       | 1.4%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 168       | 1.34%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 160       | 1.28%   |
| Intel Wireless 3165                                                     | 159       | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 153       | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 146       | 1.16%   |
| Intel Wireless 7265                                                     | 144       | 1.15%   |
| Intel WiFi Link 5100                                                    | 138       | 1.1%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 131       | 1.04%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 127       | 1.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 121       | 0.96%   |
| Intel Centrino Wireless-N 130                                           | 116       | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 113       | 0.9%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 111       | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 110       | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 110       | 0.88%   |
| Intel Wireless 7260                                                     | 106       | 0.84%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 98        | 0.78%   |
| Intel Wi-Fi 6 AX201                                                     | 94        | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 93        | 0.74%   |
| Qualcomm Atheros AR9271 802.11n                                         | 89        | 0.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 84        | 0.67%   |
| Intel Centrino Wireless-N 2230                                          | 83        | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 82        | 0.65%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 78        | 0.62%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 76        | 0.61%   |
| Intel WiMAX/WiFi Link 5150                                              | 75        | 0.6%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 72        | 0.57%   |
| Ralink RT5370 Wireless Adapter                                          | 69        | 0.55%   |
| Intel Wireless 8260                                                     | 69        | 0.55%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 68        | 0.54%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 61        | 0.49%   |
| Intel Centrino Wireless-N 100                                           | 60        | 0.48%   |
| Intel Wireless-AC 9260                                                  | 58        | 0.46%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 57        | 0.45%   |
| Intel Centrino Advanced-N 6235                                          | 56        | 0.45%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 54        | 0.43%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 52        | 0.41%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 50        | 0.4%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 47        | 0.37%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 46        | 0.37%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 46        | 0.37%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 44        | 0.35%   |
| Broadcom BCM43227 802.11b/g/n                                           | 42        | 0.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 12039     | 60.26%  |
| Qualcomm Atheros                       | 2203      | 11.03%  |
| Intel                                  | 2025      | 10.14%  |
| Broadcom                               | 702       | 3.51%   |
| Nvidia                                 | 673       | 3.37%   |
| Marvell Technology Group               | 634       | 3.17%   |
| Broadcom Limited                       | 254       | 1.27%   |
| VIA Technologies                       | 171       | 0.86%   |
| Huawei Technologies                    | 131       | 0.66%   |
| JMicron Technology                     | 110       | 0.55%   |
| Attansic Technology                    | 101       | 0.51%   |
| Xiaomi                                 | 98        | 0.49%   |
| ZTE WCDMA Technologies MSM             | 91        | 0.46%   |
| D-Link System                          | 76        | 0.38%   |
| Silicon Integrated Systems [SiS]       | 74        | 0.37%   |
| Samsung Electronics                    | 68        | 0.34%   |
| MediaTek                               | 68        | 0.34%   |
| Gemtek                                 | 34        | 0.17%   |
| Sundance Technology Inc / IC Plus      | 32        | 0.16%   |
| 3Com                                   | 31        | 0.16%   |
| ASIX Electronics                       | 29        | 0.15%   |
| TP-Link                                | 25        | 0.13%   |
| Qualcomm                               | 25        | 0.13%   |
| HTC (High Tech Computer)               | 23        | 0.12%   |
| IBM                                    | 18        | 0.09%   |
| D-Link                                 | 18        | 0.09%   |
| Vimtron Electronics                    | 17        | 0.09%   |
| Lenovo                                 | 16        | 0.08%   |
| Sony Ericsson Mobile Communications AB | 15        | 0.08%   |
| HMD Global                             | 14        | 0.07%   |
| Spreadtrum Communications              | 12        | 0.06%   |
| GCT Semiconductor                      | 12        | 0.06%   |
| ASUSTek Computer                       | 12        | 0.06%   |
| T & A Mobile Phones                    | 10        | 0.05%   |
| NTmore                                 | 8         | 0.04%   |
| Microchip Technology                   | 8         | 0.04%   |
| Aquantia                               | 7         | 0.04%   |
| Android                                | 7         | 0.04%   |
| Mellanox Technologies                  | 6         | 0.03%   |
| ICS Advent                             | 6         | 0.03%   |
| Hewlett-Packard                        | 6         | 0.03%   |
| Apple                                  | 6         | 0.03%   |
| LG Electronics                         | 5         | 0.03%   |
| American Megatrends                    | 5         | 0.03%   |
| ULi Electronics                        | 4         | 0.02%   |
| OPPO Electronics                       | 3         | 0.02%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.02%   |
| MCST                                   | 3         | 0.02%   |
| Emulex                                 | 3         | 0.02%   |
| DisplayLink                            | 3         | 0.02%   |
| Digitech Systems                       | 3         | 0.02%   |
| ZyXEL Communications                   | 2         | 0.01%   |
| NetXen Incorporated                    | 2         | 0.01%   |
| National Semiconductor                 | 2         | 0.01%   |
| Motorola PCS                           | 2         | 0.01%   |
| Google                                 | 2         | 0.01%   |
| FS406                                  | 2         | 0.01%   |
| Davicom Semiconductor                  | 2         | 0.01%   |
| Yulong                                 | 1         | 0.01%   |
| vivo                                   | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 9397      | 46.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1892      | 9.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 497       | 2.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 415       | 2.04%   |
| Nvidia MCP61 Ethernet                                                          | 323       | 1.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 220       | 1.08%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 215       | 1.06%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 212       | 1.04%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 201       | 0.99%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 192       | 0.95%   |
| Intel Ethernet Connection (2) I219-V                                           | 181       | 0.89%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 178       | 0.88%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 176       | 0.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 168       | 0.83%   |
| Intel 82579V Gigabit Network Connection                                        | 166       | 0.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 162       | 0.8%    |
| Intel I211 Gigabit Network Connection                                          | 153       | 0.75%   |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 112       | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 111       | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 107       | 0.53%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 106       | 0.52%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 101       | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 98        | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 95        | 0.47%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 92        | 0.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 91        | 0.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 86        | 0.42%   |
| Intel WiMAX Connection 2400m                                                   | 86        | 0.42%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 79        | 0.39%   |
| ZTE WCDMA MSM ZTE MSM                                                          | 77        | 0.38%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 77        | 0.38%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 77        | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 75        | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 74        | 0.36%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 72        | 0.35%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 72        | 0.35%   |
| Intel Ethernet Connection I217-V                                               | 72        | 0.35%   |
| Nvidia MCP77 Ethernet                                                          | 70        | 0.34%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 67        | 0.33%   |
| Huawei MAR-LX1A                                                                | 66        | 0.32%   |
| Intel 82574L Gigabit Network Connection                                        | 64        | 0.32%   |
| Realtek RTL8125 2.5GbE Controller                                              | 63        | 0.31%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 63        | 0.31%   |
| Nvidia CK804 Ethernet Controller                                               | 62        | 0.31%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 58        | 0.29%   |
| Intel Ethernet Connection I219-LM                                              | 57        | 0.28%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 56        | 0.28%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 56        | 0.28%   |
| Intel I210 Gigabit Network Connection                                          | 55        | 0.27%   |
| Huawei E353/E3131                                                              | 55        | 0.27%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 54        | 0.27%   |
| MediaTek Vodafone Smart N10                                                    | 52        | 0.26%   |
| Intel Ethernet Connection (2) I218-V                                           | 51        | 0.25%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 51        | 0.25%   |
| Nvidia MCP55 Ethernet                                                          | 48        | 0.24%   |
| Nvidia MCP51 Ethernet Controller                                               | 48        | 0.24%   |
| Intel Ethernet Connection (7) I219-V                                           | 48        | 0.24%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 47        | 0.23%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 46        | 0.23%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 45        | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 18696     | 59.74%  |
| WiFi     | 12091     | 38.64%  |
| Modem    | 477       | 1.52%   |
| Unknown  | 30        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 10667     | 52.93%  |
| WiFi     | 9479      | 47.04%  |
| Modem    | 5         | 0.02%   |
| Unknown  | 2         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 10198     | 50.69%  |
| 1     | 9326      | 46.36%  |
| 0     | 363       | 1.8%    |
| 3     | 154       | 0.77%   |
| 4     | 42        | 0.21%   |
| 6     | 15        | 0.07%   |
| 8     | 7         | 0.03%   |
| 5     | 4         | 0.02%   |
| 12    | 3         | 0.01%   |
| 33    | 1         | 0.005%  |
| 20    | 1         | 0.005%  |
| 14    | 1         | 0.005%  |
| 13    | 1         | 0.005%  |
| 11    | 1         | 0.005%  |
| 7     | 1         | 0.005%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 19861     | 98.88%  |
| Yes  | 224       | 1.12%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2001      | 24.47%  |
| Qualcomm Atheros Communications | 1082      | 13.23%  |
| Realtek Semiconductor           | 934       | 11.42%  |
| Cambridge Silicon Radio         | 656       | 8.02%   |
| Broadcom                        | 620       | 7.58%   |
| IMC Networks                    | 573       | 7.01%   |
| Lite-On Technology              | 525       | 6.42%   |
| Foxconn / Hon Hai               | 436       | 5.33%   |
| ASUSTek Computer                | 296       | 3.62%   |
| Ralink                          | 176       | 2.15%   |
| Foxconn International           | 133       | 1.63%   |
| Toshiba                         | 128       | 1.56%   |
| Apple                           | 110       | 1.34%   |
| Hewlett-Packard                 | 108       | 1.32%   |
| Dell                            | 99        | 1.21%   |
| Realtek                         | 78        | 0.95%   |
| Alps Electric                   | 59        | 0.72%   |
| Ralink Technology               | 36        | 0.44%   |
| Integrated System Solution      | 26        | 0.32%   |
| Chicony Electronics             | 22        | 0.27%   |
| MediaTek                        | 15        | 0.18%   |
| Micro Star International        | 13        | 0.16%   |
| USI                             | 7         | 0.09%   |
| Conwise Technology              | 7         | 0.09%   |
| Askey Computer                  | 7         | 0.09%   |
| Roper                           | 5         | 0.06%   |
| Qcom                            | 5         | 0.06%   |
| Taiyo Yuden                     | 4         | 0.05%   |
| Logitech                        | 4         | 0.05%   |
| HTC (High Tech Computer)        | 4         | 0.05%   |
| D-Link System                   | 3         | 0.04%   |
| Samsung Electronics             | 2         | 0.02%   |
| Marvell Semiconductor           | 2         | 0.02%   |
| TRENDnet                        | 1         | 0.01%   |
| Syntek                          | 1         | 0.01%   |
| Edimax Technology               | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 734       | 8.97%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 656       | 8.01%   |
| Realtek Bluetooth Radio                                                             | 461       | 5.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 361       | 4.41%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 352       | 4.3%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 349       | 4.26%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 263       | 3.21%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 227       | 2.77%   |
| Intel AX201 Bluetooth                                                               | 211       | 2.58%   |
| Intel AX200 Bluetooth                                                               | 210       | 2.57%   |
| Ralink RT3290 Bluetooth                                                             | 176       | 2.15%   |
| IMC Networks Bluetooth Radio                                                        | 162       | 1.98%   |
| IMC Networks Bluetooth Device                                                       | 152       | 1.86%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 142       | 1.73%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 141       | 1.72%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 141       | 1.72%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 137       | 1.67%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 137       | 1.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 133       | 1.62%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 131       | 1.6%    |
| Lite-On Bluetooth Device                                                            | 128       | 1.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 114       | 1.39%   |
| Realtek RTL8723B Bluetooth                                                          | 99        | 1.21%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 97        | 1.19%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 89        | 1.09%   |
| Broadcom BCM2045 Bluetooth                                                          | 80        | 0.98%   |
| Realtek Bluetooth Radio                                                             | 78        | 0.95%   |
| Qualcomm Atheros Bluetooth                                                          | 65        | 0.79%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 61        | 0.75%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 61        | 0.75%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 60        | 0.73%   |
| Broadcom HP Portable Valentine                                                      | 58        | 0.71%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 55        | 0.67%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 53        | 0.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 51        | 0.62%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 51        | 0.62%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 49        | 0.6%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 48        | 0.59%   |
| Realtek RTL8723A Bluetooth                                                          | 47        | 0.57%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 47        | 0.57%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 47        | 0.57%   |
| Toshiba Integrated Bluetooth HCI                                                    | 46        | 0.56%   |
| IMC Networks Bluetooth module                                                       | 45        | 0.55%   |
| Apple Bluetooth USB Host Controller                                                 | 45        | 0.55%   |
| Apple Bluetooth Host Controller                                                     | 41        | 0.5%    |
| Realtek 802.11ac WLAN Adapter                                                       | 40        | 0.49%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 40        | 0.49%   |
| IMC Networks Bluetooth                                                              | 33        | 0.4%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 30        | 0.37%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 29        | 0.35%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 29        | 0.35%   |
| Toshiba RT Bluetooth Radio                                                          | 28        | 0.34%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 26        | 0.32%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 26        | 0.32%   |
| Alps Electric BCM2046 Bluetooth Device                                              | 26        | 0.32%   |
| Qualcomm Atheros Bluetooth (AR3011)                                                 | 25        | 0.31%   |
| IMC Networks Bluetooth USB Host Controller                                          | 25        | 0.31%   |
| Dell Wireless 360 Bluetooth                                                         | 25        | 0.31%   |
| Dell Wireless 355 Bluetooth                                                         | 24        | 0.29%   |
| Foxconn / Hon Hai BT                                                                | 23        | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 13851     | 51.85%  |
| AMD                                             | 6061      | 22.69%  |
| Nvidia                                          | 5102      | 19.1%   |
| C-Media Electronics                             | 440       | 1.65%   |
| Creative Labs                                   | 274       | 1.03%   |
| VIA Technologies                                | 126       | 0.47%   |
| Silicon Integrated Systems [SiS]                | 108       | 0.4%    |
| Creative Technology                             | 74        | 0.28%   |
| Logitech                                        | 70        | 0.26%   |
| JMTek                                           | 54        | 0.2%    |
| Texas Instruments                               | 36        | 0.13%   |
| Generalplus Technology                          | 33        | 0.12%   |
| Plantronics                                     | 27        | 0.1%    |
| Realtek Semiconductor                           | 20        | 0.07%   |
| ASUSTek Computer                                | 19        | 0.07%   |
| Yamaha                                          | 15        | 0.06%   |
| A4Tech                                          | 15        | 0.06%   |
| Kingston Technology                             | 14        | 0.05%   |
| Samson Technologies                             | 12        | 0.04%   |
| Lenovo                                          | 12        | 0.04%   |
| Focusrite-Novation                              | 12        | 0.04%   |
| Pixart Imaging                                  | 11        | 0.04%   |
| SteelSeries ApS                                 | 10        | 0.04%   |
| Sony                                            | 10        | 0.04%   |
| Razer USA                                       | 10        | 0.04%   |
| M-Audio                                         | 10        | 0.04%   |
| Ensoniq                                         | 10        | 0.04%   |
| GN Netcom                                       | 9         | 0.03%   |
| Thesycon Systemsoftware & Consulting            | 8         | 0.03%   |
| Conexant Systems                                | 8         | 0.03%   |
| XMOS                                            | 7         | 0.03%   |
| Sennheiser Communications                       | 7         | 0.03%   |
| ESS Technology                                  | 7         | 0.03%   |
| Elite Silicon                                   | 7         | 0.03%   |
| ATI Technologies                                | 7         | 0.03%   |
| Shenzhen Rapoo Technology                       | 6         | 0.02%   |
| SAVITECH                                        | 6         | 0.02%   |
| Microsoft                                       | 6         | 0.02%   |
| BEHRINGER International                         | 6         | 0.02%   |
| Aureal Semiconductor                            | 6         | 0.02%   |
| ULi Electronics                                 | 5         | 0.02%   |
| Tenx Technology                                 | 5         | 0.02%   |
| Licensed by Sony Computer Entertainment America | 5         | 0.02%   |
| GYROCOM C&C                                     | 5         | 0.02%   |
| Cambridge Silicon Radio                         | 5         | 0.02%   |
| Apple                                           | 5         | 0.02%   |
| Philips (or NXP)                                | 4         | 0.01%   |
| Nordic Semiconductor ASA                        | 4         | 0.01%   |
| KORG                                            | 4         | 0.01%   |
| Fortemedia                                      | 4         | 0.01%   |
| DigiTech                                        | 4         | 0.01%   |
| Corsair                                         | 4         | 0.01%   |
| Blue Microphones                                | 4         | 0.01%   |
| Yealink Network Technology                      | 3         | 0.01%   |
| Unknown                                         | 3         | 0.01%   |
| Shenzhen Riitek Technology                      | 3         | 0.01%   |
| Samsung Electronics                             | 3         | 0.01%   |
| Roland                                          | 3         | 0.01%   |
| Numark                                          | 3         | 0.01%   |
| MCST                                            | 3         | 0.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 1943      | 6.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1918      | 6.18%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1882      | 6.07%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1797      | 5.79%   |
| AMD FCH Azalia Controller                                                                         | 1063      | 3.43%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 854       | 2.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 839       | 2.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 805       | 2.6%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 758       | 2.44%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 757       | 2.44%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 666       | 2.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 543       | 1.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 538       | 1.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 510       | 1.64%   |
| Nvidia High Definition Audio Controller                                                           | 508       | 1.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 446       | 1.44%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 403       | 1.3%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 401       | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 392       | 1.26%   |
| AMD Kabini HDMI/DP Audio                                                                          | 376       | 1.21%   |
| Intel Cannon Lake PCH cAVS                                                                        | 369       | 1.19%   |
| Nvidia MCP61 High Definition Audio                                                                | 352       | 1.13%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 351       | 1.13%   |
| Intel 200 Series PCH HD Audio                                                                     | 337       | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 309       | 1%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 297       | 0.96%   |
| Intel 8 Series HD Audio Controller                                                                | 297       | 0.96%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 292       | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 290       | 0.93%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 281       | 0.91%   |
| AMD Trinity HDMI Audio Controller                                                                 | 262       | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 257       | 0.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 240       | 0.77%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 235       | 0.76%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 229       | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 228       | 0.74%   |
| AMD Wrestler HDMI Audio                                                                           | 228       | 0.74%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 227       | 0.73%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 206       | 0.66%   |
| AMD High Definition Audio Controller                                                              | 205       | 0.66%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 203       | 0.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 202       | 0.65%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 192       | 0.62%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 190       | 0.61%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 181       | 0.58%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 177       | 0.57%   |
| Intel Broadwell-U Audio Controller                                                                | 173       | 0.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 171       | 0.55%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 167       | 0.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 163       | 0.53%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 159       | 0.51%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 154       | 0.5%    |
| Nvidia GK104 HDMI Audio Controller                                                                | 152       | 0.49%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 144       | 0.46%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 138       | 0.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 138       | 0.44%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 131       | 0.42%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 127       | 0.41%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 123       | 0.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 122       | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 5539      | 27.86%  |
| Samsung Electronics          | 2972      | 14.95%  |
| Kingston                     | 2972      | 14.95%  |
| SK Hynix                     | 2430      | 12.22%  |
| Crucial                      | 996       | 5.01%   |
| Micron Technology            | 936       | 4.71%   |
| Corsair                      | 482       | 2.42%   |
| Elpida                       | 450       | 2.26%   |
| Nanya Technology             | 424       | 2.13%   |
| A-DATA Technology            | 345       | 1.74%   |
| Ramaxel Technology           | 344       | 1.73%   |
| Patriot                      | 295       | 1.48%   |
| AMD                          | 277       | 1.39%   |
| ASint Technology             | 121       | 0.61%   |
| Goldkey                      | 118       | 0.59%   |
| GOODRAM                      | 91        | 0.46%   |
| 48spaces                     | 77        | 0.39%   |
| Transcend                    | 66        | 0.33%   |
| Qumo                         | 66        | 0.33%   |
| Apacer                       | 66        | 0.33%   |
| Unknown (ABCD)               | 65        | 0.33%   |
| G.Skill                      | 62        | 0.31%   |
| Kingmax                      | 60        | 0.3%    |
| Silicon Power                | 52        | 0.26%   |
| Kllisre                      | 52        | 0.26%   |
| SHARETRONIC                  | 49        | 0.25%   |
| Unifosa                      | 47        | 0.24%   |
| Foxline                      | 43        | 0.22%   |
| Qimonda                      | 36        | 0.18%   |
| Unknown                      | 27        | 0.14%   |
| GeIL                         | 26        | 0.13%   |
| KETECH                       | 21        | 0.11%   |
| Hikvision                    | 21        | 0.11%   |
| Toshiba                      | 17        | 0.09%   |
| Team                         | 17        | 0.09%   |
| Ramos Technology             | 13        | 0.07%   |
| atermiter                    | 13        | 0.07%   |
| Kingmax Semiconductor        | 11        | 0.06%   |
| Neo Forza                    | 9         | 0.05%   |
| Hexon                        | 9         | 0.05%   |
| TakeMS                       | 8         | 0.04%   |
| OCZ                          | 7         | 0.04%   |
| Wilk Elektronik              | 4         | 0.02%   |
| Veineda                      | 4         | 0.02%   |
| SGS/Thomson                  | 4         | 0.02%   |
| PLEXHD                       | 4         | 0.02%   |
| Patriot Memory (PDP Systems) | 4         | 0.02%   |
| MLLSE                        | 4         | 0.02%   |
| Hewlett-Packard              | 4         | 0.02%   |
| Exceleram                    | 4         | 0.02%   |
| Unknown (094A)               | 3         | 0.02%   |
| Unknown (08AE)               | 3         | 0.02%   |
| Teikon                       | 3         | 0.02%   |
| Reboto                       | 3         | 0.02%   |
| KingTiger                    | 3         | 0.02%   |
| Kembona                      | 3         | 0.02%   |
| Infineon                     | 3         | 0.02%   |
| Hyundai lnc                  | 3         | 0.02%   |
| HPE                          | 3         | 0.02%   |
| Golden Empire                | 3         | 0.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                                  | 284       | 1.27%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                         | 269       | 1.2%    |
| Unknown RAM Module 2048MB DIMM 800MT/s                                       | 261       | 1.17%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                         | 222       | 0.99%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                                      | 210       | 0.94%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 208       | 0.93%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                                      | 199       | 0.89%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                                  | 179       | 0.8%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 148       | 0.66%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                                       | 139       | 0.62%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                                  | 137       | 0.61%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                        | 133       | 0.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                        | 127       | 0.57%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                        | 123       | 0.55%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                                  | 121       | 0.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 119       | 0.53%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 118       | 0.53%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                                | 116       | 0.52%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s                     | 114       | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                        | 112       | 0.5%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                        | 104       | 0.46%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 101       | 0.45%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s                       | 97        | 0.43%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                                 | 96        | 0.43%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                        | 94        | 0.42%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                                       | 92        | 0.41%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 88        | 0.39%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 88        | 0.39%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                                | 85        | 0.38%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                                       | 85        | 0.38%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                        | 85        | 0.38%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                                 | 84        | 0.37%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                                      | 83        | 0.37%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                                       | 83        | 0.37%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s                        | 83        | 0.37%   |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s                       | 81        | 0.36%   |
| Unknown RAM Module 4096MB SODIMM DDR3                                        | 77        | 0.34%   |
| Unknown RAM Module 512MB DIMM SDRAM                                          | 76        | 0.34%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                        | 76        | 0.34%   |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s                            | 74        | 0.33%   |
| 48spaces RAM 012345678901234567890123456789012345 2048MB SODIMM DDR2 667MT/s | 72        | 0.32%   |
| Unknown RAM Module 1024MB DIMM                                               | 71        | 0.32%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                                | 70        | 0.31%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                       | 69        | 0.31%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                                       | 63        | 0.28%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s                                  | 63        | 0.28%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                         | 63        | 0.28%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                                 | 62        | 0.28%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                                  | 62        | 0.28%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                       | 59        | 0.26%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s                       | 59        | 0.26%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s                        | 58        | 0.26%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                       | 52        | 0.23%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s               | 52        | 0.23%   |
| Kingston RAM 99U5584-005.A00LF 4096MB DIMM DDR3 1600MT/s                     | 52        | 0.23%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s                        | 52        | 0.23%   |
| Unknown RAM Module 2GB DIMM SDRAM                                            | 49        | 0.22%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                               | 49        | 0.22%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s                        | 49        | 0.22%   |
| Kingston RAM KHX1600C10D3/8G 4096MB DIMM DDR3 1600MT/s                       | 48        | 0.21%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 7949      | 45.52%  |
| DDR4    | 3463      | 19.83%  |
| DDR2    | 2142      | 12.27%  |
| Unknown | 1865      | 10.68%  |
| SDRAM   | 1308      | 7.49%   |
| DDR     | 373       | 2.14%   |
| LPDDR4  | 173       | 0.99%   |
| DRAM    | 102       | 0.58%   |
| LPDDR3  | 84        | 0.48%   |
| SRAM    | 1         | 0.01%   |
| EEPROM  | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 8673      | 50.49%  |
| SODIMM       | 8239      | 47.96%  |
| Row Of Chips | 227       | 1.32%   |
| Chip         | 19        | 0.11%   |
| FB-DIMM      | 13        | 0.08%   |
| Unknown      | 7         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 7016      | 35%     |
| 2048    | 5845      | 29.16%  |
| 8192    | 3362      | 16.77%  |
| 1024    | 2458      | 12.26%  |
| 16384   | 643       | 3.21%   |
| 512     | 497       | 2.48%   |
| 32768   | 102       | 0.51%   |
| 256     | 98        | 0.49%   |
| 1536    | 6         | 0.03%   |
| 32      | 5         | 0.02%   |
| Unknown | 5         | 0.02%   |
| 65536   | 3         | 0.01%   |
| 128     | 2         | 0.01%   |
| 16      | 2         | 0.01%   |
| 258496  | 1         | 0.005%  |
| 129408  | 1         | 0.005%  |
| 1       | 1         | 0.005%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 4596      | 24.06%  |
| 1333    | 2420      | 12.67%  |
| Unknown | 1477      | 7.73%   |
| 800     | 1344      | 7.04%   |
| 2667    | 1306      | 6.84%   |
| 1334    | 1247      | 6.53%   |
| 667     | 1244      | 6.51%   |
| 2400    | 915       | 4.79%   |
| 3200    | 648       | 3.39%   |
| 2133    | 575       | 3.01%   |
| 1067    | 298       | 1.56%   |
| 400     | 281       | 1.47%   |
| 1066    | 280       | 1.47%   |
| 1867    | 260       | 1.36%   |
| 533     | 251       | 1.31%   |
| 4199    | 233       | 1.22%   |
| 1866    | 186       | 0.97%   |
| 333     | 161       | 0.84%   |
| 3266    | 127       | 0.66%   |
| 2933    | 112       | 0.59%   |
| 2048    | 106       | 0.55%   |
| 2666    | 87        | 0.46%   |
| 3600    | 73        | 0.38%   |
| 1800    | 62        | 0.32%   |
| 3466    | 57        | 0.3%    |
| 266     | 57        | 0.3%    |
| 975     | 56        | 0.29%   |
| 3000    | 44        | 0.23%   |
| 3400    | 40        | 0.21%   |
| 2800    | 33        | 0.17%   |
| 66      | 33        | 0.17%   |
| 2134    | 32        | 0.17%   |
| 1639    | 30        | 0.16%   |
| 3533    | 29        | 0.15%   |
| 3066    | 28        | 0.15%   |
| 2000    | 27        | 0.14%   |
| 1400    | 23        | 0.12%   |
| 200     | 21        | 0.11%   |
| 3334    | 19        | 0.1%    |
| 4267    | 16        | 0.08%   |
| 3733    | 16        | 0.08%   |
| 3333    | 13        | 0.07%   |
| 2866    | 13        | 0.07%   |
| 3151    | 12        | 0.06%   |
| 2934    | 11        | 0.06%   |
| 2733    | 11        | 0.06%   |
| 2187    | 11        | 0.06%   |
| 4333    | 10        | 0.05%   |
| 1648    | 10        | 0.05%   |
| 49926   | 9         | 0.05%   |
| 3500    | 9         | 0.05%   |
| 4266    | 8         | 0.04%   |
| 2200    | 8         | 0.04%   |
| 65535   | 7         | 0.04%   |
| 5354    | 6         | 0.03%   |
| 2747    | 6         | 0.03%   |
| 50410   | 5         | 0.03%   |
| 3800    | 5         | 0.03%   |
| 3467    | 5         | 0.03%   |
| 2176    | 5         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 302       | 28.71%  |
| Canon                           | 220       | 20.91%  |
| Samsung Electronics             | 186       | 17.68%  |
| Seiko Epson                     | 103       | 9.79%   |
| Brother Industries              | 76        | 7.22%   |
| Xerox                           | 34        | 3.23%   |
| Panasonic (Matsushita)          | 33        | 3.14%   |
| Pantum                          | 24        | 2.28%   |
| Kyocera                         | 20        | 1.9%    |
| Ricoh                           | 18        | 1.71%   |
| QinHeng Electronics             | 11        | 1.05%   |
| Prolific Technology             | 6         | 0.57%   |
| Lexmark International           | 3         | 0.29%   |
| TSC Auto ID Technology          | 2         | 0.19%   |
| Konica Minolta                  | 2         | 0.19%   |
| Datamax-O'Neil                  | 2         | 0.19%   |
| cab Produkttechnik GmbH & Co KG | 2         | 0.19%   |
| STMicroelectronics              | 1         | 0.1%    |
| Sharp                           | 1         | 0.1%    |
| Samsung Info. Systems America   | 1         | 0.1%    |
| NXP Semiconductors              | 1         | 0.1%    |
| Kodak                           | 1         | 0.1%    |
| GODEX INTERNATIONAL             | 1         | 0.1%    |
| Fuji Xerox                      | 1         | 0.1%    |
| Apple                           | 1         | 0.1%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                             | 36        | 3.4%    |
| Samsung SCX-4200 series                                      | 33        | 3.11%   |
| Canon LBP2900                                                | 28        | 2.64%   |
| HP LaserJet P1102                                            | 27        | 2.55%   |
| HP LaserJet 1018                                             | 26        | 2.45%   |
| Panasonic (Matsushita) KX-MB1500CX                           | 21        | 1.98%   |
| Samsung SCX-3400 Series                                      | 19        | 1.79%   |
| Seiko Epson Printer                                          | 17        | 1.6%    |
| HP LaserJet 1010                                             | 17        | 1.6%    |
| Samsung SCX-3200 Series                                      | 16        | 1.51%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                        | 14        | 1.32%   |
| Canon MF3010                                                 | 13        | 1.23%   |
| HP LaserJet 1320                                             | 12        | 1.13%   |
| HP LaserJet 1200                                             | 12        | 1.13%   |
| Canon MF4010 series                                          | 12        | 1.13%   |
| Brother HL-1110 series                                       | 12        | 1.13%   |
| Samsung ML-1210 Printer                                      | 11        | 1.04%   |
| Samsung M2070 Series                                         | 11        | 1.04%   |
| QinHeng CH340S                                               | 11        | 1.04%   |
| HP LaserJet P1005                                            | 11        | 1.04%   |
| Canon LBP3010/LBP3018/LBP3050                                | 11        | 1.04%   |
| Seiko Epson L210 Series                                      | 10        | 0.94%   |
| Samsung ML-1640 Series Laser Printer                         | 10        | 0.94%   |
| Pantum P2200 series                                          | 10        | 0.94%   |
| HP LaserJet 1300                                             | 10        | 0.94%   |
| HP DeskJet 2130 series                                       | 10        | 0.94%   |
| Canon PIXMA MG2500 Series                                    | 10        | 0.94%   |
| Canon MF4410                                                 | 10        | 0.94%   |
| Samsung SCX-4100 Scanner                                     | 9         | 0.85%   |
| Samsung ML-2010P Mono Laser Printer                          | 9         | 0.85%   |
| Samsung M2020 Series                                         | 9         | 0.85%   |
| Pantum M6500 series                                          | 9         | 0.85%   |
| Canon LBP810                                                 | 9         | 0.85%   |
| Canon LBP6000                                                | 9         | 0.85%   |
| Canon LaserShot LBP-1120 Printer                             | 9         | 0.85%   |
| Brother HL-2030 Laser Printer                                | 9         | 0.85%   |
| Xerox WorkCentre 3119 Series                                 | 8         | 0.75%   |
| Panasonic (Matsushita) KX-MB2030 Multifunction Laser Printer | 8         | 0.75%   |
| HP LaserJet 1022                                             | 8         | 0.75%   |
| Canon MG2400 series                                          | 8         | 0.75%   |
| Xerox Phaser 3020                                            | 7         | 0.66%   |
| Samsung ML-1865                                              | 7         | 0.66%   |
| HP LaserJet 1000                                             | 7         | 0.66%   |
| Canon iP7200 series                                          | 7         | 0.66%   |
| Xerox Phaser 3140 and 3155                                   | 6         | 0.57%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series                | 6         | 0.57%   |
| Seiko Epson L110 Series                                      | 6         | 0.57%   |
| Samsung ML-216x Series Laser Printer                         | 6         | 0.57%   |
| Samsung ML-1610 Mono Laser Printer                           | 6         | 0.57%   |
| Prolific PL2305 Parallel Port                                | 6         | 0.57%   |
| HP LaserJet P1006                                            | 6         | 0.57%   |
| Canon LBP7010C/7018C                                         | 6         | 0.57%   |
| Canon LBP6020                                                | 6         | 0.57%   |
| Brother DCP-7010                                             | 6         | 0.57%   |
| Seiko Epson L805 Series                                      | 5         | 0.47%   |
| Seiko Epson L312 Series                                      | 5         | 0.47%   |
| HP Deskjet 2050 J510                                         | 5         | 0.47%   |
| Canon MF3200 series                                          | 5         | 0.47%   |
| Canon iP2700 series                                          | 5         | 0.47%   |
| Brother DCP-7057 scanner/printer                             | 5         | 0.47%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 103       | 35.15%  |
| Seiko Epson                 | 76        | 25.94%  |
| Hewlett-Packard             | 51        | 17.41%  |
| Mustek Systems              | 32        | 10.92%  |
| Ultima Electronics          | 12        | 4.1%    |
| Acer Peripherals (now BenQ) | 11        | 3.75%   |
| KYE Systems (Mouse Systems) | 5         | 1.71%   |
| Avision                     | 2         | 0.68%   |
| Canon Electronics           | 1         | 0.34%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                                                                | 19        | 6.46%   |
| HP ScanJet 2400c                                                                      | 18        | 6.12%   |
| Canon CanoScan LiDE 120                                                               | 17        | 5.78%   |
| Canon CanoScan LiDE 110                                                               | 17        | 5.78%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 11        | 3.74%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 11        | 3.74%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 11        | 3.74%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 10        | 3.4%    |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 10        | 3.4%    |
| Canon CanoScan LiDE 210                                                               | 9         | 3.06%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 8         | 2.72%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 8         | 2.72%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 7         | 2.38%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 6         | 2.04%   |
| Mustek Systems SNAPSCAN e22                                                           | 6         | 2.04%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 6         | 2.04%   |
| Canon CanoScan LiDE 60                                                                | 6         | 2.04%   |
| Canon CanoScan LiDE 220                                                               | 5         | 1.7%    |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 4         | 1.36%   |
| HP ScanJet 3800c                                                                      | 4         | 1.36%   |
| Canon CanoScan LiDE 70                                                                | 4         | 1.36%   |
| Canon CanoScan LiDE 100                                                               | 4         | 1.36%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 3         | 1.02%   |
| HP ScanJet 3970c                                                                      | 3         | 1.02%   |
| HP ScanJet 3770                                                                       | 3         | 1.02%   |
| HP Scanjet 200                                                                        | 3         | 1.02%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 3         | 1.02%   |
| Acer Peripherals (now BenQ) Benq 5560                                                 | 3         | 1.02%   |
| Seiko Epson Perfection 660                                                            | 2         | 0.68%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 2         | 0.68%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 2         | 0.68%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 2         | 0.68%   |
| Mustek Systems BearPaw 2448 TA Plus                                                   | 2         | 0.68%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 2         | 0.68%   |
| Mustek Systems BearPaw 2400 TA Plus                                                   | 2         | 0.68%   |
| Mustek Systems BearPaw 1200 TA/CS                                                     | 2         | 0.68%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4                                          | 2         | 0.68%   |
| HP ScanJet G4050                                                                      | 2         | 0.68%   |
| HP ScanJet G3010                                                                      | 2         | 0.68%   |
| HP ScanJet 4300c                                                                      | 2         | 0.68%   |
| HP ScanJet 2300c                                                                      | 2         | 0.68%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2         | 0.68%   |
| Canon CanoScan LiDE 700F                                                              | 2         | 0.68%   |
| Canon CanoScan                                                                        | 2         | 0.68%   |
| Avision iVina FB1600/UMAX Astra 4500                                                  | 2         | 0.68%   |
| Acer Peripherals (now BenQ) Color FlatbedScanner39                                    | 2         | 0.68%   |
| Acer Peripherals (now BenQ) Benq 5150/5250                                            | 2         | 0.68%   |
| Acer Peripherals (now BenQ) Benq 5000                                                 | 2         | 0.68%   |
| Ultima Umax Astraslim                                                                 | 1         | 0.34%   |
| Seiko Epson Stylus Photo RX500/510                                                    | 1         | 0.34%   |
| Seiko Epson Scanner                                                                   | 1         | 0.34%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 1         | 0.34%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 1         | 0.34%   |
| Seiko Epson GT-9800F [Perfection 3200]                                                | 1         | 0.34%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1         | 0.34%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1         | 0.34%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1         | 0.34%   |
| Seiko Epson ES-8500 [Expression 1640 XL]                                              | 1         | 0.34%   |
| Mustek Systems ScanExpress 1200 USB Plus                                              | 1         | 0.34%   |
| Mustek Systems BearPaw 2448 TA Pro                                                    | 1         | 0.34%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2321      | 21.54%  |
| IMC Networks                           | 1007      | 9.34%   |
| Acer                                   | 808       | 7.5%    |
| Logitech                               | 721       | 6.69%   |
| Realtek Semiconductor                  | 674       | 6.25%   |
| Microdia                               | 607       | 5.63%   |
| Suyin                                  | 576       | 5.35%   |
| Z-Star Microelectronics                | 525       | 4.87%   |
| Sunplus Innovation Technology          | 402       | 3.73%   |
| Silicon Motion                         | 379       | 3.52%   |
| Alcor Micro                            | 335       | 3.11%   |
| Cheng Uei Precision Industry (Foxlink) | 333       | 3.09%   |
| Quanta                                 | 287       | 2.66%   |
| Syntek                                 | 272       | 2.52%   |
| Apple                                  | 133       | 1.23%   |
| Ricoh                                  | 111       | 1.03%   |
| Microsoft                              | 106       | 0.98%   |
| Lite-On Technology                     | 104       | 0.97%   |
| ALi                                    | 90        | 0.84%   |
| KYE Systems (Mouse Systems)            | 83        | 0.77%   |
| DigiTech                               | 77        | 0.71%   |
| GEMBIRD                                | 73        | 0.68%   |
| Arkmicro Technologies                  | 71        | 0.66%   |
| Aveo Technology                        | 59        | 0.55%   |
| Pixart Imaging                         | 54        | 0.5%    |
| Samsung Electronics                    | 52        | 0.48%   |
| Luxvisions Innotech Limited            | 50        | 0.46%   |
| Cubeternet                             | 47        | 0.44%   |
| Creative Technology                    | 39        | 0.36%   |
| Lenovo                                 | 37        | 0.34%   |
| Primax Electronics                     | 31        | 0.29%   |
| Genesys Logic                          | 26        | 0.24%   |
| Importek                               | 20        | 0.19%   |
| Sunplus Technology                     | 19        | 0.18%   |
| OmniVision Technologies                | 15        | 0.14%   |
| Sonix Technology                       | 14        | 0.13%   |
| A4Tech                                 | 14        | 0.13%   |
| Unknown                                | 13        | 0.12%   |
| Guillemot                              | 13        | 0.12%   |
| lihappe8                               | 12        | 0.11%   |
| Philips (or NXP)                       | 10        | 0.09%   |
| Nokia Mobile Phones                    | 9         | 0.08%   |
| Hewlett-Packard                        | 9         | 0.08%   |
| Generalplus Technology                 | 9         | 0.08%   |
| SunplusIT                              | 8         | 0.07%   |
| SiGma Micro                            | 8         | 0.07%   |
| Image Processor                        | 8         | 0.07%   |
| MacroSilicon                           | 7         | 0.06%   |
| Denron                                 | 6         | 0.06%   |
| Trust                                  | 5         | 0.05%   |
| AVerMedia Technologies                 | 5         | 0.05%   |
| Nebraska Furniture Mart                | 4         | 0.04%   |
| Foxconn / Hon Hai                      | 4         | 0.04%   |
| YJX                                    | 3         | 0.03%   |
| Xiaomi                                 | 3         | 0.03%   |
| USB Camera                             | 3         | 0.03%   |
| Sony                                   | 3         | 0.03%   |
| O2 Micro                               | 3         | 0.03%   |
| Fitipower Integrated Technology        | 3         | 0.03%   |
| Canon                                  | 3         | 0.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Logitech Webcam C270                             | 252       | 2.33%   |
| Chicony HD WebCam                                | 248       | 2.3%    |
| IMC Networks USB2.0 VGA UVC WebCam               | 209       | 1.94%   |
| Chicony Lenovo EasyCamera                        | 198       | 1.83%   |
| Chicony Integrated Camera                        | 182       | 1.69%   |
| Acer Lenovo EasyCamera                           | 167       | 1.55%   |
| Z-Star Venus USB2.0 Camera                       | 163       | 1.51%   |
| Acer Lenovo Integrated Webcam                    | 140       | 1.3%    |
| Acer BisonCam, NB Pro                            | 136       | 1.26%   |
| Sunplus HD WebCam                                | 131       | 1.21%   |
| IMC Networks UVC VGA Webcam                      | 130       | 1.2%    |
| IMC Networks USB2.0 HD UVC WebCam                | 126       | 1.17%   |
| Microdia Integrated_Webcam_HD                    | 125       | 1.16%   |
| Chicony USB2.0 HD UVC WebCam                     | 115       | 1.06%   |
| Chicony USB 2.0 Camera                           | 109       | 1.01%   |
| IMC Networks Integrated Camera                   | 108       | 1%      |
| Z-Star A4 TECH USB2.0 PC Camera J                | 107       | 0.99%   |
| Realtek Integrated_Webcam_HD                     | 102       | 0.94%   |
| Microdia Camera                                  | 102       | 0.94%   |
| Chicony HP Webcam                                | 96        | 0.89%   |
| Realtek Lenovo EasyCamera                        | 88        | 0.81%   |
| Chicony VGA Webcam                               | 88        | 0.81%   |
| Alcor Micro SHUNCCM2MP                           | 87        | 0.81%   |
| Acer Integrated Camera                           | 83        | 0.77%   |
| Chicony USB2.0 VGA UVC WebCam                    | 80        | 0.74%   |
| Silicon Motion WebCam SC-0311139N                | 79        | 0.73%   |
| IMC Networks Integrated Webcam                   | 74        | 0.69%   |
| Alcor Micro Asus Integrated Webcam               | 74        | 0.69%   |
| Z-Star Vimicro USB Camera (Altair)               | 73        | 0.68%   |
| Chicony 2.0M UVC Webcam / CNF7129                | 72        | 0.67%   |
| Syntek Lenovo EasyCamera                         | 71        | 0.66%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 71        | 0.66%   |
| Realtek USB Camera                               | 71        | 0.66%   |
| Quanta VGA WebCam                                | 71        | 0.66%   |
| DigiTech USB 2.0 PC Camera                       | 69        | 0.64%   |
| Arkmicro USB2.0 PC CAMERA                        | 65        | 0.6%    |
| Chicony HP TrueVision HD                         | 64        | 0.59%   |
| Logitech Webcam C170                             | 62        | 0.57%   |
| ALi Gateway Webcam                               | 62        | 0.57%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 61        | 0.56%   |
| Apple iPhone 5/5C/5S/6/SE                        | 61        | 0.56%   |
| Microdia Sonix USB 2.0 Camera                    | 60        | 0.56%   |
| Syntek Integrated Camera                         | 59        | 0.55%   |
| Suyin 1.3M HD WebCam                             | 59        | 0.55%   |
| Sunplus Integrated_Webcam_HD                     | 58        | 0.54%   |
| Logitech HD Webcam C525                          | 57        | 0.53%   |
| Silicon Motion WebCam SCB-1100N                  | 56        | 0.52%   |
| Chicony 1.3M Webcam                              | 56        | 0.52%   |
| Realtek Acer 640 x 480 laptop camera             | 55        | 0.51%   |
| Logitech Webcam C310                             | 54        | 0.5%    |
| Chicony EasyCamera                               | 54        | 0.5%    |
| Sunplus ASUS Webcam                              | 52        | 0.48%   |
| Chicony USB2.0 0.3M UVC WebCam                   | 52        | 0.48%   |
| Acer EasyCamera                                  | 52        | 0.48%   |
| Suyin HP TrueVision HD                           | 51        | 0.47%   |
| IMC Networks USB 2.0 UVC VGA WebCam              | 51        | 0.47%   |
| Samsung Galaxy A5 (MTP)                          | 50        | 0.46%   |
| Quanta HP Webcam                                 | 49        | 0.45%   |
| Chicony HP HD Camera                             | 48        | 0.44%   |
| Logitech Webcam C210                             | 46        | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 366       | 35.09%  |
| Synaptics                  | 152       | 14.57%  |
| Shenzhen Goodix Technology | 127       | 12.18%  |
| AuthenTec                  | 122       | 11.7%   |
| Upek                       | 98        | 9.4%    |
| LighTuning Technology      | 78        | 7.48%   |
| Elan Microelectronics      | 62        | 5.94%   |
| STMicroelectronics         | 32        | 3.07%   |
| Focal-systems.Corp         | 5         | 0.48%   |
| Samsung Electronics        | 1         | 0.1%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 89        | 8.53%   |
| Validity Sensors Fingerprint scanner                                       | 84        | 8.05%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 84        | 8.05%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 78        | 7.48%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 61        | 5.85%   |
| Elan ELAN:Fingerprint                                                      | 46        | 4.41%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 45        | 4.31%   |
| AuthenTec AES1600                                                          | 38        | 3.64%   |
| LighTuning Fingerprint Reader                                              | 35        | 3.36%   |
| Shenzhen Goodix Fingerprint Reader                                         | 33        | 3.16%   |
| STMicroelectronics Fingerprint Reader                                      | 32        | 3.07%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 31        | 2.97%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 27        | 2.59%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 26        | 2.49%   |
| AuthenTec AES2810                                                          | 26        | 2.49%   |
| Validity Sensors VFS491                                                    | 23        | 2.21%   |
| Unknown                                                                    | 19        | 1.82%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 18        | 1.73%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 18        | 1.73%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 17        | 1.63%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 16        | 1.53%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 16        | 1.53%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 16        | 1.53%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 16        | 1.53%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 16        | 1.53%   |
| Synaptics  WBDI                                                            | 15        | 1.44%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 15        | 1.44%   |
| Upek TCS5B Fingerprint sensor                                              | 14        | 1.34%   |
| Elan ELAN:ARM-M4                                                           | 13        | 1.25%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 1.15%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 1.15%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 0.77%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 0.67%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 7         | 0.67%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 0.58%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 0.48%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 0.48%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.38%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.29%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.29%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 3         | 0.29%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.1%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 81        | 31.76%  |
| Broadcom                   | 69        | 27.06%  |
| Upek                       | 21        | 8.24%   |
| O2 Micro                   | 21        | 8.24%   |
| Lenovo                     | 14        | 5.49%   |
| Aladdin Knowledge Systems  | 13        | 5.1%    |
| Aktiv                      | 9         | 3.53%   |
| ARDS                       | 6         | 2.35%   |
| Advanced Card Systems      | 6         | 2.35%   |
| Gemalto (was Gemplus)      | 5         | 1.96%   |
| Athena Smartcard Solutions | 4         | 1.57%   |
| Yubico.com                 | 3         | 1.18%   |
| OmniKey                    | 1         | 0.39%   |
| Microchip Technology       | 1         | 0.39%   |
| Castles Technology         | 1         | 0.39%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 77        | 30.2%   |
| Broadcom BCM5880 Secure Applications Processor                               | 30        | 11.76%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 21        | 8.24%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 7.06%   |
| Broadcom 5880                                                                | 16        | 6.27%   |
| Lenovo Integrated Smart Card Reader                                          | 14        | 5.49%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 13        | 5.1%    |
| Aladdin Knowledge Systems Token JC                                           | 13        | 5.1%    |
| Broadcom 58200                                                               | 10        | 3.92%   |
| Aktiv Rutoken lite                                                           | 9         | 3.53%   |
| ARDS JaCarta                                                                 | 6         | 2.35%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 4         | 1.57%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 1.57%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 1.18%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.18%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.18%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.78%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 0.78%   |
| OmniKey Smart Card Reader USB                                                | 1         | 0.39%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.39%   |
| Castles Technology EZCCID Smart Card Reader                                  | 1         | 0.39%   |
| Advanced Card Systems Token USB 64K                                          | 1         | 0.39%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.39%   |
| Advanced Card Systems ACR3901U                                               | 1         | 0.39%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.39%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 15635     | 75.62%  |
| 1     | 4135      | 20%     |
| 2     | 707       | 3.42%   |
| 3     | 127       | 0.61%   |
| 4     | 50        | 0.24%   |
| 5     | 11        | 0.05%   |
| 6     | 8         | 0.04%   |
| 7     | 2         | 0.01%   |
| 9     | 1         | 0.005%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 2518      | 44.06%  |
| Fingerprint reader       | 1038      | 18.16%  |
| Net/wireless             | 571       | 9.99%   |
| Multimedia controller    | 275       | 4.81%   |
| Communication controller | 269       | 4.71%   |
| Bluetooth                | 234       | 4.09%   |
| Chipcard                 | 229       | 4.01%   |
| Unassigned class         | 118       | 2.06%   |
| Camera                   | 116       | 2.03%   |
| Sound                    | 67        | 1.17%   |
| Storage                  | 63        | 1.1%    |
| Flash memory             | 55        | 0.96%   |
| Net/ethernet             | 32        | 0.56%   |
| Card reader              | 27        | 0.47%   |
| Modem                    | 26        | 0.45%   |
| Network                  | 21        | 0.37%   |
| Dvb card                 | 18        | 0.31%   |
| Storage/raid             | 12        | 0.21%   |
| Firewire controller      | 8         | 0.14%   |
| Storage/ide              | 6         | 0.1%    |
| Storage/ata              | 5         | 0.09%   |
| Tv card                  | 3         | 0.05%   |
| Unclassified device      | 2         | 0.03%   |
| Wireless                 | 1         | 0.02%   |
| Video                    | 1         | 0.02%   |

