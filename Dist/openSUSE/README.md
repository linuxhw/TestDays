openSUSE - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for openSUSE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/openSUSE/Desktop/README.md) and [notebooks](/Dist/openSUSE/Notebook/README.md).

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

Total: 3054

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Notebook      | NS50_70MU                   | Notebook    | [87b818815c](https://linux-hardware.org/?probe=87b818815c) | Jun 10, 2023 |
| HP            | 2B4B                        | Desktop     | [3ade78a07e](https://linux-hardware.org/?probe=3ade78a07e) | Jun 10, 2023 |
| HP            | 2B4B                        | Desktop     | [2da60252b5](https://linux-hardware.org/?probe=2da60252b5) | Jun 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [758afab931](https://linux-hardware.org/?probe=758afab931) | Jun 10, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d9e9a51e48](https://linux-hardware.org/?probe=d9e9a51e48) | Jun 10, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [5648ca2620](https://linux-hardware.org/?probe=5648ca2620) | Jun 09, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [30dbebd931](https://linux-hardware.org/?probe=30dbebd931) | Jun 09, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [6d70667d42](https://linux-hardware.org/?probe=6d70667d42) | Jun 09, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [77145a587d](https://linux-hardware.org/?probe=77145a587d) | Jun 09, 2023 |
| Gigabyte      | AORUS 17X AXF               | Notebook    | [685ba556b4](https://linux-hardware.org/?probe=685ba556b4) | Jun 09, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [797dea9c96](https://linux-hardware.org/?probe=797dea9c96) | Jun 09, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1bae25f67b](https://linux-hardware.org/?probe=1bae25f67b) | Jun 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [cc1f571000](https://linux-hardware.org/?probe=cc1f571000) | Jun 09, 2023 |
| ASUSTek       | G771JW                      | Notebook    | [6d989f49b6](https://linux-hardware.org/?probe=6d989f49b6) | Jun 09, 2023 |
| Fujitsu       | D2942-B1 S26361-D2942-B1    | Desktop     | [9fb55abc56](https://linux-hardware.org/?probe=9fb55abc56) | Jun 08, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [e68e693394](https://linux-hardware.org/?probe=e68e693394) | Jun 08, 2023 |
| Dell          | Precision 5540              | Notebook    | [0e925c8b3c](https://linux-hardware.org/?probe=0e925c8b3c) | Jun 08, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [ad5baed526](https://linux-hardware.org/?probe=ad5baed526) | Jun 08, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [a2c63b86b0](https://linux-hardware.org/?probe=a2c63b86b0) | Jun 08, 2023 |
| Lenovo        | 317C SDK0J40700 WIN 3258... | Desktop     | [d5d7ffe9df](https://linux-hardware.org/?probe=d5d7ffe9df) | Jun 08, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [f6fddfcd65](https://linux-hardware.org/?probe=f6fddfcd65) | Jun 07, 2023 |
| MSI           | P67A-C45                    | Desktop     | [673f3774bc](https://linux-hardware.org/?probe=673f3774bc) | Jun 07, 2023 |
| MSI           | CreatorPro X17 A12UKS       | Notebook    | [ee827c186c](https://linux-hardware.org/?probe=ee827c186c) | Jun 07, 2023 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [1d36e85f27](https://linux-hardware.org/?probe=1d36e85f27) | Jun 07, 2023 |
| Gigabyte      | AORUS 17X AXF               | Notebook    | [87bd8323b6](https://linux-hardware.org/?probe=87bd8323b6) | Jun 07, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [e45ed702a4](https://linux-hardware.org/?probe=e45ed702a4) | Jun 07, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [47c5d7587a](https://linux-hardware.org/?probe=47c5d7587a) | Jun 06, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [5fb7d63e80](https://linux-hardware.org/?probe=5fb7d63e80) | Jun 06, 2023 |
| Lenovo        | 317C SDK0J40700 WIN 3258... | Desktop     | [23b41d16db](https://linux-hardware.org/?probe=23b41d16db) | Jun 06, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [2508cbfdd2](https://linux-hardware.org/?probe=2508cbfdd2) | Jun 06, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [3d0f46c6ed](https://linux-hardware.org/?probe=3d0f46c6ed) | Jun 06, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [acae4ee06e](https://linux-hardware.org/?probe=acae4ee06e) | Jun 06, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [8d150fb2b0](https://linux-hardware.org/?probe=8d150fb2b0) | Jun 05, 2023 |
| Sony          | VPCEH25EN                   | Notebook    | [2b47c1b9a5](https://linux-hardware.org/?probe=2b47c1b9a5) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [b4f165f28d](https://linux-hardware.org/?probe=b4f165f28d) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [e0ce9df73c](https://linux-hardware.org/?probe=e0ce9df73c) | Jun 05, 2023 |
| Acer          | Aspire 3820                 | Notebook    | [edbf91844a](https://linux-hardware.org/?probe=edbf91844a) | Jun 04, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [8e0a13cdd1](https://linux-hardware.org/?probe=8e0a13cdd1) | Jun 04, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [4d82d8bf8b](https://linux-hardware.org/?probe=4d82d8bf8b) | Jun 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [cdbebd8a7e](https://linux-hardware.org/?probe=cdbebd8a7e) | Jun 04, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [a8baa03316](https://linux-hardware.org/?probe=a8baa03316) | Jun 03, 2023 |
| MSI           | Modern 14 B5M               | Notebook    | [25ffe9ad37](https://linux-hardware.org/?probe=25ffe9ad37) | Jun 03, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [76cd01b045](https://linux-hardware.org/?probe=76cd01b045) | Jun 03, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [75ba9fba2f](https://linux-hardware.org/?probe=75ba9fba2f) | Jun 03, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d8f3391b68](https://linux-hardware.org/?probe=d8f3391b68) | Jun 02, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [e91c644324](https://linux-hardware.org/?probe=e91c644324) | Jun 02, 2023 |
| Dell          | G15 5520                    | Notebook    | [5880c98c54](https://linux-hardware.org/?probe=5880c98c54) | Jun 02, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [ab7c62da47](https://linux-hardware.org/?probe=ab7c62da47) | Jun 02, 2023 |
| Panasonic     | CF-SX2JDHYS                 | Notebook    | [2bcfc48199](https://linux-hardware.org/?probe=2bcfc48199) | Jun 02, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [2cf19f7b32](https://linux-hardware.org/?probe=2cf19f7b32) | Jun 02, 2023 |
| Portwell      | RuggedBookJ10               | Tablet      | [828336f149](https://linux-hardware.org/?probe=828336f149) | Jun 01, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [71c2818f01](https://linux-hardware.org/?probe=71c2818f01) | Jun 01, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [976fcb80b0](https://linux-hardware.org/?probe=976fcb80b0) | Jun 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [01692ad602](https://linux-hardware.org/?probe=01692ad602) | May 31, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [bb8f972443](https://linux-hardware.org/?probe=bb8f972443) | May 31, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [a313036ec2](https://linux-hardware.org/?probe=a313036ec2) | May 31, 2023 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [2881299761](https://linux-hardware.org/?probe=2881299761) | May 30, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [c75d4298dc](https://linux-hardware.org/?probe=c75d4298dc) | May 30, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [5bd3cb3a3a](https://linux-hardware.org/?probe=5bd3cb3a3a) | May 29, 2023 |
| ASRock        | J3355B-ITX                  | Desktop     | [02f6d0b74b](https://linux-hardware.org/?probe=02f6d0b74b) | May 29, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [a9ff8334b4](https://linux-hardware.org/?probe=a9ff8334b4) | May 28, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [d3afe375cf](https://linux-hardware.org/?probe=d3afe375cf) | May 28, 2023 |
| ASUSTek       | Z87I-DELUXE                 | Desktop     | [5d683647ae](https://linux-hardware.org/?probe=5d683647ae) | May 28, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [a890415f0e](https://linux-hardware.org/?probe=a890415f0e) | May 28, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [4feb3e3196](https://linux-hardware.org/?probe=4feb3e3196) | May 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [0f3f548ff0](https://linux-hardware.org/?probe=0f3f548ff0) | May 27, 2023 |
| ASUSTek       | Z77-A                       | Desktop     | [eb9ee9f38e](https://linux-hardware.org/?probe=eb9ee9f38e) | May 27, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [aeb6fa2258](https://linux-hardware.org/?probe=aeb6fa2258) | May 26, 2023 |
| Dell          | Latitude 3440               | Notebook    | [1d32fe235f](https://linux-hardware.org/?probe=1d32fe235f) | May 26, 2023 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [f4de9c8a5f](https://linux-hardware.org/?probe=f4de9c8a5f) | May 26, 2023 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [1c272c65dc](https://linux-hardware.org/?probe=1c272c65dc) | May 26, 2023 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [5b0dffc2c3](https://linux-hardware.org/?probe=5b0dffc2c3) | May 26, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [c8c9f63237](https://linux-hardware.org/?probe=c8c9f63237) | May 25, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [e0920f015d](https://linux-hardware.org/?probe=e0920f015d) | May 25, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [f3e564d17d](https://linux-hardware.org/?probe=f3e564d17d) | May 25, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [776f5c2411](https://linux-hardware.org/?probe=776f5c2411) | May 25, 2023 |
| Acer          | Aspire A314-22              | Notebook    | [e2110ab5da](https://linux-hardware.org/?probe=e2110ab5da) | May 25, 2023 |
| ASRock        | 890GX Extreme3              | Desktop     | [016f2a8ada](https://linux-hardware.org/?probe=016f2a8ada) | May 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [61b85cdced](https://linux-hardware.org/?probe=61b85cdced) | May 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [b167237d46](https://linux-hardware.org/?probe=b167237d46) | May 24, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [585b85e476](https://linux-hardware.org/?probe=585b85e476) | May 23, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ca5f5ee7bf](https://linux-hardware.org/?probe=ca5f5ee7bf) | May 23, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [f133543500](https://linux-hardware.org/?probe=f133543500) | May 23, 2023 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [56fba05f01](https://linux-hardware.org/?probe=56fba05f01) | May 22, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [926421c6be](https://linux-hardware.org/?probe=926421c6be) | May 22, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [c903e06758](https://linux-hardware.org/?probe=c903e06758) | May 22, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [8b4b66a085](https://linux-hardware.org/?probe=8b4b66a085) | May 22, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [93074475ac](https://linux-hardware.org/?probe=93074475ac) | May 22, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [b34371b4ba](https://linux-hardware.org/?probe=b34371b4ba) | May 21, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [3fb6e257a6](https://linux-hardware.org/?probe=3fb6e257a6) | May 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [87bf7a95c8](https://linux-hardware.org/?probe=87bf7a95c8) | May 21, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | Notebook    | [a6e8e03e74](https://linux-hardware.org/?probe=a6e8e03e74) | May 21, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a69a8746ff](https://linux-hardware.org/?probe=a69a8746ff) | May 20, 2023 |
| Fujitsu       | D3009-B1 S26361-D3009-B1    | Desktop     | [d5213cca3c](https://linux-hardware.org/?probe=d5213cca3c) | May 20, 2023 |
| Dell          | 0F3KHR A01                  | Desktop     | [c48ab194c6](https://linux-hardware.org/?probe=c48ab194c6) | May 20, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [5352a94049](https://linux-hardware.org/?probe=5352a94049) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1f6220f21a](https://linux-hardware.org/?probe=1f6220f21a) | May 19, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [12da248164](https://linux-hardware.org/?probe=12da248164) | May 19, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [c571a25585](https://linux-hardware.org/?probe=c571a25585) | May 19, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [c2f9737977](https://linux-hardware.org/?probe=c2f9737977) | May 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S8EG0... | Notebook    | [0735cab104](https://linux-hardware.org/?probe=0735cab104) | May 18, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [7087600ab6](https://linux-hardware.org/?probe=7087600ab6) | May 17, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [ad17e04f3b](https://linux-hardware.org/?probe=ad17e04f3b) | May 17, 2023 |
| Dell          | Inspiron 7573               | Convertible | [8f57130549](https://linux-hardware.org/?probe=8f57130549) | May 17, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [74c412b40a](https://linux-hardware.org/?probe=74c412b40a) | May 16, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [8517139acb](https://linux-hardware.org/?probe=8517139acb) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [c33be8e25c](https://linux-hardware.org/?probe=c33be8e25c) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [5e8463c682](https://linux-hardware.org/?probe=5e8463c682) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [093e6a63c8](https://linux-hardware.org/?probe=093e6a63c8) | May 16, 2023 |
| Dell          | Inspiron 7573               | Convertible | [6f1d226305](https://linux-hardware.org/?probe=6f1d226305) | May 16, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7d44c65f86](https://linux-hardware.org/?probe=7d44c65f86) | May 16, 2023 |
| ASRock        | J3355B-ITX                  | Desktop     | [443ee2bf3a](https://linux-hardware.org/?probe=443ee2bf3a) | May 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [61499d189f](https://linux-hardware.org/?probe=61499d189f) | May 15, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a438db6a33](https://linux-hardware.org/?probe=a438db6a33) | May 15, 2023 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [1560f547ad](https://linux-hardware.org/?probe=1560f547ad) | May 14, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [2dc2bdd057](https://linux-hardware.org/?probe=2dc2bdd057) | May 14, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [6335ace28b](https://linux-hardware.org/?probe=6335ace28b) | May 14, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [8d819952c9](https://linux-hardware.org/?probe=8d819952c9) | May 14, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [aa5dc9770e](https://linux-hardware.org/?probe=aa5dc9770e) | May 13, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [51c66f0f57](https://linux-hardware.org/?probe=51c66f0f57) | May 13, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ab7d27081e](https://linux-hardware.org/?probe=ab7d27081e) | May 13, 2023 |
| Dell          | 0F0XJ6 A11                  | Server      | [4bc8e971f7](https://linux-hardware.org/?probe=4bc8e971f7) | May 13, 2023 |
| Dell          | 0F0XJ6 A11                  | Server      | [be75daf81a](https://linux-hardware.org/?probe=be75daf81a) | May 13, 2023 |
| HP            | 339A                        | Desktop     | [2ba14f8397](https://linux-hardware.org/?probe=2ba14f8397) | May 12, 2023 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [30bda7d8cb](https://linux-hardware.org/?probe=30bda7d8cb) | May 12, 2023 |
| Lenovo        | ThinkPad L540 20AUS01H00    | Notebook    | [d39599a293](https://linux-hardware.org/?probe=d39599a293) | May 12, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3d43aab6fd](https://linux-hardware.org/?probe=3d43aab6fd) | May 12, 2023 |
| Huanan        | B75 V10.1 376               | Desktop     | [3293d10187](https://linux-hardware.org/?probe=3293d10187) | May 12, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [99ad79383e](https://linux-hardware.org/?probe=99ad79383e) | May 11, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [17282aeeb3](https://linux-hardware.org/?probe=17282aeeb3) | May 11, 2023 |
| HP            | Laptop 14s-cf0xxx           | Notebook    | [6d0f055f82](https://linux-hardware.org/?probe=6d0f055f82) | May 11, 2023 |
| HP            | Laptop 14s-cf0xxx           | Notebook    | [7f90473be2](https://linux-hardware.org/?probe=7f90473be2) | May 11, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [165d6e12b4](https://linux-hardware.org/?probe=165d6e12b4) | May 11, 2023 |
| Lenovo        | ThinkPad T530 23926CU       | Notebook    | [4e7cab81f3](https://linux-hardware.org/?probe=4e7cab81f3) | May 11, 2023 |
| Lenovo        | ThinkPad W541 20EF001UGE    | Notebook    | [29c8170a0e](https://linux-hardware.org/?probe=29c8170a0e) | May 10, 2023 |
| ASUSTek       | TUF Gaming B550M-ZAKU       | Desktop     | [cde6cec9c8](https://linux-hardware.org/?probe=cde6cec9c8) | May 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [49e9002825](https://linux-hardware.org/?probe=49e9002825) | May 10, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0a3aa24894](https://linux-hardware.org/?probe=0a3aa24894) | May 10, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [8eae6560cb](https://linux-hardware.org/?probe=8eae6560cb) | May 10, 2023 |
| Lenovo        | RD450X                      | Server      | [6fca1885fc](https://linux-hardware.org/?probe=6fca1885fc) | May 10, 2023 |
| Lenovo        | RD450X                      | Server      | [5cd314b0af](https://linux-hardware.org/?probe=5cd314b0af) | May 10, 2023 |
| Lenovo        | ThinkPad T570 20HAS0UU00    | Notebook    | [c0ad43f440](https://linux-hardware.org/?probe=c0ad43f440) | May 09, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [922a392eee](https://linux-hardware.org/?probe=922a392eee) | May 09, 2023 |
| Lenovo        | ThinkPad T570 20HAS0UU00    | Notebook    | [f3572c500c](https://linux-hardware.org/?probe=f3572c500c) | May 09, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [c74bb83ac9](https://linux-hardware.org/?probe=c74bb83ac9) | May 08, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [9430b8c328](https://linux-hardware.org/?probe=9430b8c328) | May 08, 2023 |
| Lenovo        | ThinkPad T410 2522K3U       | Notebook    | [55756e1659](https://linux-hardware.org/?probe=55756e1659) | May 07, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [2a321db63e](https://linux-hardware.org/?probe=2a321db63e) | May 07, 2023 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [eeb37c9c4f](https://linux-hardware.org/?probe=eeb37c9c4f) | May 07, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [05c9e752a5](https://linux-hardware.org/?probe=05c9e752a5) | May 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b661127bb7](https://linux-hardware.org/?probe=b661127bb7) | May 06, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | Notebook    | [9cb4890df2](https://linux-hardware.org/?probe=9cb4890df2) | May 06, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [aaad2fda16](https://linux-hardware.org/?probe=aaad2fda16) | May 06, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [c6b9cf8729](https://linux-hardware.org/?probe=c6b9cf8729) | May 05, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [2a4b061b07](https://linux-hardware.org/?probe=2a4b061b07) | May 05, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [54417e14cf](https://linux-hardware.org/?probe=54417e14cf) | May 05, 2023 |
| HP            | 304Ah                       | Desktop     | [d9a160845c](https://linux-hardware.org/?probe=d9a160845c) | May 05, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [98d7593057](https://linux-hardware.org/?probe=98d7593057) | May 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [f9a56b49f3](https://linux-hardware.org/?probe=f9a56b49f3) | May 05, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [0d4ad3c608](https://linux-hardware.org/?probe=0d4ad3c608) | May 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ab21408c4c](https://linux-hardware.org/?probe=ab21408c4c) | May 03, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [99870f2da6](https://linux-hardware.org/?probe=99870f2da6) | May 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [9ff86ca1f1](https://linux-hardware.org/?probe=9ff86ca1f1) | May 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e9bd630708](https://linux-hardware.org/?probe=e9bd630708) | May 01, 2023 |
| MSI           | B365M PRO-VDH               | Desktop     | [82d7303d5c](https://linux-hardware.org/?probe=82d7303d5c) | May 01, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [0cb8947c84](https://linux-hardware.org/?probe=0cb8947c84) | Apr 30, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [9109b0a7ed](https://linux-hardware.org/?probe=9109b0a7ed) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9876205c45](https://linux-hardware.org/?probe=9876205c45) | Apr 30, 2023 |
| AMI           | INTEL                       | Convertible | [3a67944d4f](https://linux-hardware.org/?probe=3a67944d4f) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [fcd7a6a42b](https://linux-hardware.org/?probe=fcd7a6a42b) | Apr 30, 2023 |
| HP            | 1998                        | Desktop     | [4ba5ef1211](https://linux-hardware.org/?probe=4ba5ef1211) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [c36b7b72de](https://linux-hardware.org/?probe=c36b7b72de) | Apr 29, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI D... | Desktop     | [c880b8dcdd](https://linux-hardware.org/?probe=c880b8dcdd) | Apr 29, 2023 |
| Lenovo        | ThinkPad P50 20EQS5C701     | Notebook    | [e84690f2d5](https://linux-hardware.org/?probe=e84690f2d5) | Apr 29, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [33e30c562d](https://linux-hardware.org/?probe=33e30c562d) | Apr 29, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [0295ab04a7](https://linux-hardware.org/?probe=0295ab04a7) | Apr 28, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [a1584c31ec](https://linux-hardware.org/?probe=a1584c31ec) | Apr 28, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [5f191f449f](https://linux-hardware.org/?probe=5f191f449f) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ca70475f8a](https://linux-hardware.org/?probe=ca70475f8a) | Apr 28, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [0e403fcd17](https://linux-hardware.org/?probe=0e403fcd17) | Apr 27, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [6c35501215](https://linux-hardware.org/?probe=6c35501215) | Apr 27, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [ec41184680](https://linux-hardware.org/?probe=ec41184680) | Apr 27, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [5c5fece872](https://linux-hardware.org/?probe=5c5fece872) | Apr 27, 2023 |
| Lenovo        | QIWY3                       | Notebook    | [a7c04857e4](https://linux-hardware.org/?probe=a7c04857e4) | Apr 27, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [29d2a588e0](https://linux-hardware.org/?probe=29d2a588e0) | Apr 27, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [3ec3c7aa7b](https://linux-hardware.org/?probe=3ec3c7aa7b) | Apr 26, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [53c0f79af9](https://linux-hardware.org/?probe=53c0f79af9) | Apr 26, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [018ade4782](https://linux-hardware.org/?probe=018ade4782) | Apr 26, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [48e88f7bd1](https://linux-hardware.org/?probe=48e88f7bd1) | Apr 25, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2ccfcd2b27](https://linux-hardware.org/?probe=2ccfcd2b27) | Apr 25, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [45199e8296](https://linux-hardware.org/?probe=45199e8296) | Apr 25, 2023 |
| ASUSTek       | A55BM-PLUS                  | Desktop     | [19c145fab1](https://linux-hardware.org/?probe=19c145fab1) | Apr 25, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d73e1b6350](https://linux-hardware.org/?probe=d73e1b6350) | Apr 24, 2023 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [46a27a7551](https://linux-hardware.org/?probe=46a27a7551) | Apr 23, 2023 |
| Notebook      | W54_55_94_95_97AU,AUQ       | Notebook    | [f4e4c58948](https://linux-hardware.org/?probe=f4e4c58948) | Apr 23, 2023 |
| Google        | Kefka                       | Notebook    | [2802d83837](https://linux-hardware.org/?probe=2802d83837) | Apr 23, 2023 |
| ASUSTek       | GL703VM                     | Notebook    | [f3c76b5075](https://linux-hardware.org/?probe=f3c76b5075) | Apr 23, 2023 |
| HP            | 8433 11                     | Desktop     | [e885f0469c](https://linux-hardware.org/?probe=e885f0469c) | Apr 22, 2023 |
| Lenovo        | ThinkPad T460s 20F9005CM... | Notebook    | [2aa36b9cfd](https://linux-hardware.org/?probe=2aa36b9cfd) | Apr 22, 2023 |
| Allview       | Allbook J                   | Notebook    | [96a3d7d3ef](https://linux-hardware.org/?probe=96a3d7d3ef) | Apr 22, 2023 |
| HP            | Spectre x360 Convertible    | Convertible | [1a3ff160a7](https://linux-hardware.org/?probe=1a3ff160a7) | Apr 21, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [4fad4d4a09](https://linux-hardware.org/?probe=4fad4d4a09) | Apr 21, 2023 |
| Gateway       | NV55C                       | Notebook    | [e77192c3b1](https://linux-hardware.org/?probe=e77192c3b1) | Apr 20, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [50f90c0b1f](https://linux-hardware.org/?probe=50f90c0b1f) | Apr 20, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [e299a6ed8e](https://linux-hardware.org/?probe=e299a6ed8e) | Apr 20, 2023 |
| Dell          | Latitude 7410               | Notebook    | [36e2aea9ea](https://linux-hardware.org/?probe=36e2aea9ea) | Apr 19, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1943314777](https://linux-hardware.org/?probe=1943314777) | Apr 19, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [69b2b1c95f](https://linux-hardware.org/?probe=69b2b1c95f) | Apr 19, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [17eb54bee6](https://linux-hardware.org/?probe=17eb54bee6) | Apr 18, 2023 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [17b3242021](https://linux-hardware.org/?probe=17b3242021) | Apr 18, 2023 |
| Allview       | Allbook J                   | Notebook    | [4ff8627338](https://linux-hardware.org/?probe=4ff8627338) | Apr 18, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [f44b68cf93](https://linux-hardware.org/?probe=f44b68cf93) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [482a8c29cc](https://linux-hardware.org/?probe=482a8c29cc) | Apr 16, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [55309d71c2](https://linux-hardware.org/?probe=55309d71c2) | Apr 16, 2023 |
| Toshiba       | Satellite C45-A             | Notebook    | [3fd496c5f8](https://linux-hardware.org/?probe=3fd496c5f8) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [0dfc78d12a](https://linux-hardware.org/?probe=0dfc78d12a) | Apr 15, 2023 |
| HP            | Mini 210-1000               | Notebook    | [e8b0b26e10](https://linux-hardware.org/?probe=e8b0b26e10) | Apr 15, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c5f2678609](https://linux-hardware.org/?probe=c5f2678609) | Apr 15, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [11b817e884](https://linux-hardware.org/?probe=11b817e884) | Apr 15, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [c4f2e4e7d8](https://linux-hardware.org/?probe=c4f2e4e7d8) | Apr 14, 2023 |
| Lenovo        | ThinkPad X201 3680HTG       | Notebook    | [f7029b5f3b](https://linux-hardware.org/?probe=f7029b5f3b) | Apr 14, 2023 |
| ASUSTek       | GL502VM                     | Notebook    | [4d31e0eb90](https://linux-hardware.org/?probe=4d31e0eb90) | Apr 13, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [b7786541c0](https://linux-hardware.org/?probe=b7786541c0) | Apr 13, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [356ff49c7c](https://linux-hardware.org/?probe=356ff49c7c) | Apr 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bba5f185af](https://linux-hardware.org/?probe=bba5f185af) | Apr 13, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [76f2d6b30c](https://linux-hardware.org/?probe=76f2d6b30c) | Apr 13, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [3ac19a6abf](https://linux-hardware.org/?probe=3ac19a6abf) | Apr 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [6e34f5a7b8](https://linux-hardware.org/?probe=6e34f5a7b8) | Apr 13, 2023 |
| ASRock        | H410M-HVS                   | Desktop     | [23371691ec](https://linux-hardware.org/?probe=23371691ec) | Apr 12, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [dc40d51336](https://linux-hardware.org/?probe=dc40d51336) | Apr 12, 2023 |
| ASUSTek       | TP500LAG                    | Notebook    | [ae048d3165](https://linux-hardware.org/?probe=ae048d3165) | Apr 12, 2023 |
| HP            | 8433 11                     | Desktop     | [61c92812be](https://linux-hardware.org/?probe=61c92812be) | Apr 12, 2023 |
| MSI           | Stealth 14Studio A13VF      | Notebook    | [8297ce2712](https://linux-hardware.org/?probe=8297ce2712) | Apr 11, 2023 |
| MSI           | Stealth 14Studio A13VF      | Notebook    | [e3fc8c8f43](https://linux-hardware.org/?probe=e3fc8c8f43) | Apr 11, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [6037aee790](https://linux-hardware.org/?probe=6037aee790) | Apr 11, 2023 |
| MSI           | P67A-C45                    | Desktop     | [25a90d2595](https://linux-hardware.org/?probe=25a90d2595) | Apr 10, 2023 |
| ASUSTek       | TP500LAG                    | Notebook    | [b67954cc59](https://linux-hardware.org/?probe=b67954cc59) | Apr 10, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [0f078152ca](https://linux-hardware.org/?probe=0f078152ca) | Apr 10, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [5bd37d599e](https://linux-hardware.org/?probe=5bd37d599e) | Apr 09, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [19fd2b6d0d](https://linux-hardware.org/?probe=19fd2b6d0d) | Apr 09, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [7dc7e5e5c3](https://linux-hardware.org/?probe=7dc7e5e5c3) | Apr 09, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [d938c02967](https://linux-hardware.org/?probe=d938c02967) | Apr 09, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [bc402eee2e](https://linux-hardware.org/?probe=bc402eee2e) | Apr 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1ab81a719b](https://linux-hardware.org/?probe=1ab81a719b) | Apr 08, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [840f96a7df](https://linux-hardware.org/?probe=840f96a7df) | Apr 08, 2023 |
| Dell          | Latitude 5431               | Notebook    | [d85ac2917b](https://linux-hardware.org/?probe=d85ac2917b) | Apr 07, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [241572fcea](https://linux-hardware.org/?probe=241572fcea) | Apr 07, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a9882c4012](https://linux-hardware.org/?probe=a9882c4012) | Apr 06, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [7e3ef5fa45](https://linux-hardware.org/?probe=7e3ef5fa45) | Apr 06, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [b949468335](https://linux-hardware.org/?probe=b949468335) | Apr 05, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [62debd585f](https://linux-hardware.org/?probe=62debd585f) | Apr 05, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [f1398d5ada](https://linux-hardware.org/?probe=f1398d5ada) | Apr 05, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [dcf97ad331](https://linux-hardware.org/?probe=dcf97ad331) | Apr 05, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [dad967cc87](https://linux-hardware.org/?probe=dad967cc87) | Apr 05, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [0f75295895](https://linux-hardware.org/?probe=0f75295895) | Apr 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f89b2c8b2a](https://linux-hardware.org/?probe=f89b2c8b2a) | Apr 05, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [9f251621b1](https://linux-hardware.org/?probe=9f251621b1) | Apr 04, 2023 |
| Dell          | Precision 5530              | Notebook    | [bf568860cb](https://linux-hardware.org/?probe=bf568860cb) | Apr 04, 2023 |
| Lenovo        | Unknown                     | Notebook    | [4216d2969c](https://linux-hardware.org/?probe=4216d2969c) | Apr 04, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [a03fbcf098](https://linux-hardware.org/?probe=a03fbcf098) | Apr 03, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [6906a8d309](https://linux-hardware.org/?probe=6906a8d309) | Apr 03, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [d447871547](https://linux-hardware.org/?probe=d447871547) | Apr 03, 2023 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [82a3b55b60](https://linux-hardware.org/?probe=82a3b55b60) | Apr 02, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [fabc275714](https://linux-hardware.org/?probe=fabc275714) | Apr 01, 2023 |
| MSI           | P67A-C43                    | Desktop     | [f3e7913310](https://linux-hardware.org/?probe=f3e7913310) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [36e57fb4cf](https://linux-hardware.org/?probe=36e57fb4cf) | Apr 01, 2023 |
| ASRock        | Z87 Extreme11/ac            | Desktop     | [283593a105](https://linux-hardware.org/?probe=283593a105) | Mar 31, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c3f0c2a691](https://linux-hardware.org/?probe=c3f0c2a691) | Mar 30, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [cdb78d0527](https://linux-hardware.org/?probe=cdb78d0527) | Mar 30, 2023 |
| MSI           | 2AE0                        | Desktop     | [29c86e9653](https://linux-hardware.org/?probe=29c86e9653) | Mar 29, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [872733b74c](https://linux-hardware.org/?probe=872733b74c) | Mar 29, 2023 |
| MSI           | 2AE0                        | Desktop     | [53e6254c56](https://linux-hardware.org/?probe=53e6254c56) | Mar 29, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [6de889ae8a](https://linux-hardware.org/?probe=6de889ae8a) | Mar 29, 2023 |
| ASUSTek       | N550JX                      | Notebook    | [a505a62a71](https://linux-hardware.org/?probe=a505a62a71) | Mar 28, 2023 |
| ASUSTek       | A78M-A                      | Desktop     | [e2ee931df2](https://linux-hardware.org/?probe=e2ee931df2) | Mar 28, 2023 |
| Fujitsu       | LIFEBOOK U938               | Notebook    | [e972904a83](https://linux-hardware.org/?probe=e972904a83) | Mar 28, 2023 |
| HP            | Compaq 6730s                | Notebook    | [8d4cea5a81](https://linux-hardware.org/?probe=8d4cea5a81) | Mar 28, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [6dac36ba2d](https://linux-hardware.org/?probe=6dac36ba2d) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [6f4e3ec28b](https://linux-hardware.org/?probe=6f4e3ec28b) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [9dd1b67b2f](https://linux-hardware.org/?probe=9dd1b67b2f) | Mar 28, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [42601709f3](https://linux-hardware.org/?probe=42601709f3) | Mar 27, 2023 |
| Gigabyte      | H110M-S2PV DDR3-CF          | Desktop     | [022acc16f7](https://linux-hardware.org/?probe=022acc16f7) | Mar 27, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [98df8e769b](https://linux-hardware.org/?probe=98df8e769b) | Mar 26, 2023 |
| MSI           | GT72 2QE                    | Notebook    | [438f4cb9d9](https://linux-hardware.org/?probe=438f4cb9d9) | Mar 26, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [6c942c5a39](https://linux-hardware.org/?probe=6c942c5a39) | Mar 26, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [3c68ddf942](https://linux-hardware.org/?probe=3c68ddf942) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [f78ca791e0](https://linux-hardware.org/?probe=f78ca791e0) | Mar 25, 2023 |
| HP            | ProBook 645 G4              | Notebook    | [6a03f43f29](https://linux-hardware.org/?probe=6a03f43f29) | Mar 25, 2023 |
| HP            | 8433 11                     | Desktop     | [5ab010ffd4](https://linux-hardware.org/?probe=5ab010ffd4) | Mar 25, 2023 |
| Purism        | Librem 13 v2                | Notebook    | [ef5cf3e08f](https://linux-hardware.org/?probe=ef5cf3e08f) | Mar 25, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [f2a2593a06](https://linux-hardware.org/?probe=f2a2593a06) | Mar 24, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [6a2a55ca61](https://linux-hardware.org/?probe=6a2a55ca61) | Mar 24, 2023 |
| Lenovo        | ThinkPad T460s 20F9005CM... | Notebook    | [640a9ac505](https://linux-hardware.org/?probe=640a9ac505) | Mar 24, 2023 |
| Lenovo        | ThinkCentre Edge 91Z 707... | Desktop     | [2f50a76b96](https://linux-hardware.org/?probe=2f50a76b96) | Mar 22, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | Notebook    | [b618258a5c](https://linux-hardware.org/?probe=b618258a5c) | Mar 22, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [982f47fec3](https://linux-hardware.org/?probe=982f47fec3) | Mar 22, 2023 |
| Dell          | Latitude D530               | Notebook    | [92cf04edba](https://linux-hardware.org/?probe=92cf04edba) | Mar 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7b772c82ca](https://linux-hardware.org/?probe=7b772c82ca) | Mar 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bd045deb23](https://linux-hardware.org/?probe=bd045deb23) | Mar 21, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | Notebook    | [c87a678cf5](https://linux-hardware.org/?probe=c87a678cf5) | Mar 21, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [c7c5415a8c](https://linux-hardware.org/?probe=c7c5415a8c) | Mar 21, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [de1c89d1b0](https://linux-hardware.org/?probe=de1c89d1b0) | Mar 21, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [0c0bff4f29](https://linux-hardware.org/?probe=0c0bff4f29) | Mar 20, 2023 |
| HP            | 304Ah                       | Desktop     | [49adbe8acf](https://linux-hardware.org/?probe=49adbe8acf) | Mar 20, 2023 |
| Lenovo        | LEGION5PRO-16ACH6H 82JQ     | Notebook    | [4f3cbedf85](https://linux-hardware.org/?probe=4f3cbedf85) | Mar 20, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [b7cf9d91ee](https://linux-hardware.org/?probe=b7cf9d91ee) | Mar 20, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [888ec192b4](https://linux-hardware.org/?probe=888ec192b4) | Mar 19, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [729a1432a0](https://linux-hardware.org/?probe=729a1432a0) | Mar 19, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [9cdd00c854](https://linux-hardware.org/?probe=9cdd00c854) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [f35715c399](https://linux-hardware.org/?probe=f35715c399) | Mar 18, 2023 |
| Gigabyte      | Z68XP-UD4                   | Desktop     | [9d5f79bbf4](https://linux-hardware.org/?probe=9d5f79bbf4) | Mar 18, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [87ba801b00](https://linux-hardware.org/?probe=87ba801b00) | Mar 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [2cb5e6ce4f](https://linux-hardware.org/?probe=2cb5e6ce4f) | Mar 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [5d43e434bc](https://linux-hardware.org/?probe=5d43e434bc) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [92d818d184](https://linux-hardware.org/?probe=92d818d184) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [60114cc9c8](https://linux-hardware.org/?probe=60114cc9c8) | Mar 16, 2023 |
| Dell          | 0PGKWF A00                  | Desktop     | [d03e035ed6](https://linux-hardware.org/?probe=d03e035ed6) | Mar 16, 2023 |
| Dell          | 0PGKWF A00                  | Desktop     | [2b34503276](https://linux-hardware.org/?probe=2b34503276) | Mar 16, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [4a47120f89](https://linux-hardware.org/?probe=4a47120f89) | Mar 15, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [a1e7a34896](https://linux-hardware.org/?probe=a1e7a34896) | Mar 14, 2023 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [6e2a63edaa](https://linux-hardware.org/?probe=6e2a63edaa) | Mar 14, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [bc12f3e2e4](https://linux-hardware.org/?probe=bc12f3e2e4) | Mar 14, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [dfd3b8546c](https://linux-hardware.org/?probe=dfd3b8546c) | Mar 14, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [2b69e73996](https://linux-hardware.org/?probe=2b69e73996) | Mar 14, 2023 |
| Lenovo        | ThinkPad Edge E530 3259H... | Notebook    | [74348d01f3](https://linux-hardware.org/?probe=74348d01f3) | Mar 13, 2023 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [8dc295e39b](https://linux-hardware.org/?probe=8dc295e39b) | Mar 13, 2023 |
| Wortmann      | Terra 3100                  | Desktop     | [126586f434](https://linux-hardware.org/?probe=126586f434) | Mar 12, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [2002eaa403](https://linux-hardware.org/?probe=2002eaa403) | Mar 12, 2023 |
| Lenovo        | ThinkPad T520 42435GG       | Notebook    | [fac1ee2528](https://linux-hardware.org/?probe=fac1ee2528) | Mar 12, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [8f3c49d011](https://linux-hardware.org/?probe=8f3c49d011) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK U939X              | Convertible | [359ca913fe](https://linux-hardware.org/?probe=359ca913fe) | Mar 12, 2023 |
| ASUSTek       | PN50                        | Mini pc     | [9ce749e52e](https://linux-hardware.org/?probe=9ce749e52e) | Mar 12, 2023 |
| ASRock        | AB350M-HDV                  | Desktop     | [45a5fbc5e7](https://linux-hardware.org/?probe=45a5fbc5e7) | Mar 12, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [5bf763c288](https://linux-hardware.org/?probe=5bf763c288) | Mar 11, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e5cdf2201f](https://linux-hardware.org/?probe=e5cdf2201f) | Mar 11, 2023 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [97741c600c](https://linux-hardware.org/?probe=97741c600c) | Mar 11, 2023 |
| Jumper        | EZbook                      | Notebook    | [ed607c4113](https://linux-hardware.org/?probe=ed607c4113) | Mar 11, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [5cb06ca8ce](https://linux-hardware.org/?probe=5cb06ca8ce) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [54e498fb2e](https://linux-hardware.org/?probe=54e498fb2e) | Mar 10, 2023 |
| ASRock        | H410M-HVS                   | Desktop     | [689186d7de](https://linux-hardware.org/?probe=689186d7de) | Mar 10, 2023 |
| HP            | ProBook 6460b               | Notebook    | [4374107e07](https://linux-hardware.org/?probe=4374107e07) | Mar 10, 2023 |
| HP            | ProBook 6460b               | Notebook    | [7a01d6124d](https://linux-hardware.org/?probe=7a01d6124d) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [661125aac2](https://linux-hardware.org/?probe=661125aac2) | Mar 10, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [d524e6c586](https://linux-hardware.org/?probe=d524e6c586) | Mar 10, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [2d75f5ea8b](https://linux-hardware.org/?probe=2d75f5ea8b) | Mar 10, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [e72ba8b8aa](https://linux-hardware.org/?probe=e72ba8b8aa) | Mar 08, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [d7ac4c2edb](https://linux-hardware.org/?probe=d7ac4c2edb) | Mar 08, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [c1339ac8de](https://linux-hardware.org/?probe=c1339ac8de) | Mar 08, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [30221f1500](https://linux-hardware.org/?probe=30221f1500) | Mar 07, 2023 |
| MSI           | P67A-C45                    | Desktop     | [52e013338c](https://linux-hardware.org/?probe=52e013338c) | Mar 07, 2023 |
| Acer          | Veriton X4610G              | Desktop     | [7f5cb2ac6a](https://linux-hardware.org/?probe=7f5cb2ac6a) | Mar 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [4ca3d88758](https://linux-hardware.org/?probe=4ca3d88758) | Mar 07, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1490c281bd](https://linux-hardware.org/?probe=1490c281bd) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [9b1357d5c0](https://linux-hardware.org/?probe=9b1357d5c0) | Mar 06, 2023 |
| Gigabyte      | Z68XP-UD3P                  | Desktop     | [bfb7053ff8](https://linux-hardware.org/?probe=bfb7053ff8) | Mar 06, 2023 |
| MSI           | B550 GAMING GEN3            | Desktop     | [09e8aaf103](https://linux-hardware.org/?probe=09e8aaf103) | Mar 05, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [386fe6d7ab](https://linux-hardware.org/?probe=386fe6d7ab) | Mar 05, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [d81384080b](https://linux-hardware.org/?probe=d81384080b) | Mar 05, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [3e4fdfbb73](https://linux-hardware.org/?probe=3e4fdfbb73) | Mar 05, 2023 |
| HP            | 1905                        | Desktop     | [3a15a8a255](https://linux-hardware.org/?probe=3a15a8a255) | Mar 05, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [4b47face39](https://linux-hardware.org/?probe=4b47face39) | Mar 05, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [38e61e3fb5](https://linux-hardware.org/?probe=38e61e3fb5) | Mar 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [daefae334b](https://linux-hardware.org/?probe=daefae334b) | Mar 04, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [19bd4c1e4e](https://linux-hardware.org/?probe=19bd4c1e4e) | Mar 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [f9a2075d54](https://linux-hardware.org/?probe=f9a2075d54) | Mar 04, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [066ce423c0](https://linux-hardware.org/?probe=066ce423c0) | Mar 03, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [587096ec48](https://linux-hardware.org/?probe=587096ec48) | Mar 03, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [3edae4d4f7](https://linux-hardware.org/?probe=3edae4d4f7) | Mar 03, 2023 |
| HP            | 2B4B                        | Desktop     | [6fe13bec4d](https://linux-hardware.org/?probe=6fe13bec4d) | Mar 02, 2023 |
| HP            | 2B4B                        | Desktop     | [d97467e5aa](https://linux-hardware.org/?probe=d97467e5aa) | Mar 02, 2023 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [e87ce2454c](https://linux-hardware.org/?probe=e87ce2454c) | Mar 02, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [5cb58db69b](https://linux-hardware.org/?probe=5cb58db69b) | Mar 02, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a279108842](https://linux-hardware.org/?probe=a279108842) | Mar 02, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [d008353c16](https://linux-hardware.org/?probe=d008353c16) | Mar 01, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [0242801bbc](https://linux-hardware.org/?probe=0242801bbc) | Mar 01, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [0f19d5c037](https://linux-hardware.org/?probe=0f19d5c037) | Mar 01, 2023 |
| Intel         | D34010WYK H14771-303        | Desktop     | [5bc379ea65](https://linux-hardware.org/?probe=5bc379ea65) | Mar 01, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [268413a47c](https://linux-hardware.org/?probe=268413a47c) | Mar 01, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [169e938f25](https://linux-hardware.org/?probe=169e938f25) | Mar 01, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [71b8cbeda5](https://linux-hardware.org/?probe=71b8cbeda5) | Feb 28, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [0710c7be6e](https://linux-hardware.org/?probe=0710c7be6e) | Feb 28, 2023 |
| HP            | ProBook 4540s               | Notebook    | [a52b9c7637](https://linux-hardware.org/?probe=a52b9c7637) | Feb 27, 2023 |
| HP            | ProBook 4540s               | Notebook    | [45e989b539](https://linux-hardware.org/?probe=45e989b539) | Feb 27, 2023 |
| HP            | Notebook                    | Notebook    | [ee2645efa8](https://linux-hardware.org/?probe=ee2645efa8) | Feb 27, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [8c0dc3ba82](https://linux-hardware.org/?probe=8c0dc3ba82) | Feb 27, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [ca878d6577](https://linux-hardware.org/?probe=ca878d6577) | Feb 27, 2023 |
| HP            | Notebook                    | Notebook    | [0d838134b7](https://linux-hardware.org/?probe=0d838134b7) | Feb 27, 2023 |
| AXDIA Inte... | WINDESK9 3G v2              | Notebook    | [49282044d3](https://linux-hardware.org/?probe=49282044d3) | Feb 26, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [c3156c3f23](https://linux-hardware.org/?probe=c3156c3f23) | Feb 26, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [899c2066a1](https://linux-hardware.org/?probe=899c2066a1) | Feb 25, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [b367bf6276](https://linux-hardware.org/?probe=b367bf6276) | Feb 25, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [86ab345b56](https://linux-hardware.org/?probe=86ab345b56) | Feb 24, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [f7d1c79daa](https://linux-hardware.org/?probe=f7d1c79daa) | Feb 24, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [105209c356](https://linux-hardware.org/?probe=105209c356) | Feb 24, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5027942f8b](https://linux-hardware.org/?probe=5027942f8b) | Feb 24, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [2c490934fb](https://linux-hardware.org/?probe=2c490934fb) | Feb 24, 2023 |
| MSI           | X58 Pro                     | Desktop     | [22509b3e42](https://linux-hardware.org/?probe=22509b3e42) | Feb 23, 2023 |
| HP            | Compaq 6720s                | Notebook    | [48cbefb8f6](https://linux-hardware.org/?probe=48cbefb8f6) | Feb 23, 2023 |
| HP            | Compaq 6720s                | Notebook    | [0dac92bb9d](https://linux-hardware.org/?probe=0dac92bb9d) | Feb 23, 2023 |
| Dell          | XPS 9320                    | Notebook    | [896a21551e](https://linux-hardware.org/?probe=896a21551e) | Feb 22, 2023 |
| HP            | 2B4B                        | Desktop     | [92c45eb54f](https://linux-hardware.org/?probe=92c45eb54f) | Feb 21, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [892b3930a6](https://linux-hardware.org/?probe=892b3930a6) | Feb 21, 2023 |
| Lenovo        | IdeaPad Y900-17ISK 80Q1     | Notebook    | [d852e3306a](https://linux-hardware.org/?probe=d852e3306a) | Feb 20, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e434f7f85a](https://linux-hardware.org/?probe=e434f7f85a) | Feb 20, 2023 |
| SK hynix      | HyBook                      | Notebook    | [494c1a322d](https://linux-hardware.org/?probe=494c1a322d) | Feb 20, 2023 |
| Acer          | Aspire X3950                | Desktop     | [f5b4a3baa3](https://linux-hardware.org/?probe=f5b4a3baa3) | Feb 20, 2023 |
| HP            | ProBook 4540s               | Notebook    | [079a5f512d](https://linux-hardware.org/?probe=079a5f512d) | Feb 20, 2023 |
| ASUSTek       | G771JW                      | Notebook    | [e5b5f4792c](https://linux-hardware.org/?probe=e5b5f4792c) | Feb 19, 2023 |
| ASUSTek       | G771JW                      | Notebook    | [c73a9b9ee2](https://linux-hardware.org/?probe=c73a9b9ee2) | Feb 19, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [19bdc55bfd](https://linux-hardware.org/?probe=19bdc55bfd) | Feb 19, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [2a35f99890](https://linux-hardware.org/?probe=2a35f99890) | Feb 18, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [f4065623e5](https://linux-hardware.org/?probe=f4065623e5) | Feb 18, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | Notebook    | [5fb2330e71](https://linux-hardware.org/?probe=5fb2330e71) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [8942075e7b](https://linux-hardware.org/?probe=8942075e7b) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [76c8c6f7ba](https://linux-hardware.org/?probe=76c8c6f7ba) | Feb 17, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | Notebook    | [9497d288f6](https://linux-hardware.org/?probe=9497d288f6) | Feb 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [4a5c7432ae](https://linux-hardware.org/?probe=4a5c7432ae) | Feb 17, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [beabc46f67](https://linux-hardware.org/?probe=beabc46f67) | Feb 14, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [fb1ff4a6d9](https://linux-hardware.org/?probe=fb1ff4a6d9) | Feb 14, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [2947200c5c](https://linux-hardware.org/?probe=2947200c5c) | Feb 14, 2023 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [84a46ec9ce](https://linux-hardware.org/?probe=84a46ec9ce) | Feb 14, 2023 |
| Google        | Lillipup                    | Notebook    | [af7451beff](https://linux-hardware.org/?probe=af7451beff) | Feb 14, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9b84a7339e](https://linux-hardware.org/?probe=9b84a7339e) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [20428fc0ed](https://linux-hardware.org/?probe=20428fc0ed) | Feb 13, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [762dd6fa2e](https://linux-hardware.org/?probe=762dd6fa2e) | Feb 13, 2023 |
| HP            | ProBook 6460b               | Notebook    | [5436445da0](https://linux-hardware.org/?probe=5436445da0) | Feb 13, 2023 |
| HP            | ProBook 6460b               | Notebook    | [ba14b45543](https://linux-hardware.org/?probe=ba14b45543) | Feb 13, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [0a6d50bc2a](https://linux-hardware.org/?probe=0a6d50bc2a) | Feb 13, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [75980f2f55](https://linux-hardware.org/?probe=75980f2f55) | Feb 13, 2023 |
| Samsung       | 550XDA                      | Notebook    | [0c3e0dd389](https://linux-hardware.org/?probe=0c3e0dd389) | Feb 13, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [86026e4f54](https://linux-hardware.org/?probe=86026e4f54) | Feb 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [df52d514c9](https://linux-hardware.org/?probe=df52d514c9) | Feb 12, 2023 |
| Toshiba       | PORTEGE Z830                | Notebook    | [a384bb740c](https://linux-hardware.org/?probe=a384bb740c) | Feb 11, 2023 |
| Sun Micros... | Ultra 24 50                 | Desktop     | [e1dc99210d](https://linux-hardware.org/?probe=e1dc99210d) | Feb 11, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [79204339d0](https://linux-hardware.org/?probe=79204339d0) | Feb 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [df97c92c82](https://linux-hardware.org/?probe=df97c92c82) | Feb 11, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [9621fdeccb](https://linux-hardware.org/?probe=9621fdeccb) | Feb 11, 2023 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [523c8db418](https://linux-hardware.org/?probe=523c8db418) | Feb 11, 2023 |
| Dell          | Precision 5570              | Notebook    | [8398c80e6b](https://linux-hardware.org/?probe=8398c80e6b) | Feb 11, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [92cbb2e876](https://linux-hardware.org/?probe=92cbb2e876) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2f721ad33a](https://linux-hardware.org/?probe=2f721ad33a) | Feb 10, 2023 |
| Acer          | Veriton N4680G              | Desktop     | [4198835011](https://linux-hardware.org/?probe=4198835011) | Feb 10, 2023 |
| Dell          | Latitude 5421               | Notebook    | [e7c6fbfeb8](https://linux-hardware.org/?probe=e7c6fbfeb8) | Feb 09, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [3b71a70207](https://linux-hardware.org/?probe=3b71a70207) | Feb 09, 2023 |
| Unknown       | M-140BI5                    | Notebook    | [a07b2a4444](https://linux-hardware.org/?probe=a07b2a4444) | Feb 09, 2023 |
| Schenker      | VIA 15                      | Notebook    | [8096682644](https://linux-hardware.org/?probe=8096682644) | Feb 09, 2023 |
| Lenovo        | ThinkPad T440s 20ARS2V90... | Notebook    | [a2e7b3b9b7](https://linux-hardware.org/?probe=a2e7b3b9b7) | Feb 08, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [acbbbca6e7](https://linux-hardware.org/?probe=acbbbca6e7) | Feb 08, 2023 |
| ASRock        | X399M Taichi                | Desktop     | [c6bf333a82](https://linux-hardware.org/?probe=c6bf333a82) | Feb 08, 2023 |
| HP            | 1494                        | Desktop     | [ba7c61bf23](https://linux-hardware.org/?probe=ba7c61bf23) | Feb 07, 2023 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [dc2172d485](https://linux-hardware.org/?probe=dc2172d485) | Feb 07, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3b6bf45c6b](https://linux-hardware.org/?probe=3b6bf45c6b) | Feb 07, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [70f715ffb4](https://linux-hardware.org/?probe=70f715ffb4) | Feb 06, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [f7ca9a94c5](https://linux-hardware.org/?probe=f7ca9a94c5) | Feb 06, 2023 |
| HP            | 0B54h D                     | Desktop     | [fa38931f1f](https://linux-hardware.org/?probe=fa38931f1f) | Feb 06, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [9b92561723](https://linux-hardware.org/?probe=9b92561723) | Feb 06, 2023 |
| Medion        | P6624                       | Notebook    | [5a31124376](https://linux-hardware.org/?probe=5a31124376) | Feb 06, 2023 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [16f0d33c85](https://linux-hardware.org/?probe=16f0d33c85) | Feb 06, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [4a971615e8](https://linux-hardware.org/?probe=4a971615e8) | Feb 05, 2023 |
| Dell          | Latitude E7470              | Notebook    | [88a8b69cc3](https://linux-hardware.org/?probe=88a8b69cc3) | Feb 05, 2023 |
| HP            | 845A                        | Desktop     | [3e744bcf5b](https://linux-hardware.org/?probe=3e744bcf5b) | Feb 05, 2023 |
| Lenovo        | ThinkPad P50 20EN001SUS     | Notebook    | [bbe182e4c2](https://linux-hardware.org/?probe=bbe182e4c2) | Feb 04, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [81c4e4ce60](https://linux-hardware.org/?probe=81c4e4ce60) | Feb 03, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [fd8c9d9ccf](https://linux-hardware.org/?probe=fd8c9d9ccf) | Feb 03, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9b0a8de7a1](https://linux-hardware.org/?probe=9b0a8de7a1) | Feb 02, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [f05a20fe00](https://linux-hardware.org/?probe=f05a20fe00) | Feb 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [bd22f26ad1](https://linux-hardware.org/?probe=bd22f26ad1) | Jan 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [28ea3cafe8](https://linux-hardware.org/?probe=28ea3cafe8) | Jan 31, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [f2636de53b](https://linux-hardware.org/?probe=f2636de53b) | Jan 31, 2023 |
| Lenovo        | 3717 SDK0J40697 WIN 3305... | Desktop     | [175a0fcf9a](https://linux-hardware.org/?probe=175a0fcf9a) | Jan 31, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [e0e7acce8d](https://linux-hardware.org/?probe=e0e7acce8d) | Jan 31, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [32dfb5ebe2](https://linux-hardware.org/?probe=32dfb5ebe2) | Jan 31, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [fc09442b7c](https://linux-hardware.org/?probe=fc09442b7c) | Jan 30, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [b78602c91d](https://linux-hardware.org/?probe=b78602c91d) | Jan 30, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [8d7c1dbf4d](https://linux-hardware.org/?probe=8d7c1dbf4d) | Jan 30, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [6bf8eb9c73](https://linux-hardware.org/?probe=6bf8eb9c73) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [78d987fedf](https://linux-hardware.org/?probe=78d987fedf) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [a178301183](https://linux-hardware.org/?probe=a178301183) | Jan 30, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [1746dfe4b1](https://linux-hardware.org/?probe=1746dfe4b1) | Jan 30, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [9b0891d54d](https://linux-hardware.org/?probe=9b0891d54d) | Jan 30, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b61ed06b1e](https://linux-hardware.org/?probe=b61ed06b1e) | Jan 30, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [de8c055a8a](https://linux-hardware.org/?probe=de8c055a8a) | Jan 29, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [327e2d4e3e](https://linux-hardware.org/?probe=327e2d4e3e) | Jan 28, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b5ca740834](https://linux-hardware.org/?probe=b5ca740834) | Jan 28, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [f20e47b9d7](https://linux-hardware.org/?probe=f20e47b9d7) | Jan 28, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [4a33511e43](https://linux-hardware.org/?probe=4a33511e43) | Jan 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [de71656929](https://linux-hardware.org/?probe=de71656929) | Jan 27, 2023 |
| Lenovo        | ThinkPad R500 2718WA3       | Notebook    | [2bb86279a8](https://linux-hardware.org/?probe=2bb86279a8) | Jan 27, 2023 |
| Intel         | X99                         | Desktop     | [1fbd6cf5bd](https://linux-hardware.org/?probe=1fbd6cf5bd) | Jan 27, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [463c397bb0](https://linux-hardware.org/?probe=463c397bb0) | Jan 26, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ff3fd2b8f1](https://linux-hardware.org/?probe=ff3fd2b8f1) | Jan 26, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [cf662e2730](https://linux-hardware.org/?probe=cf662e2730) | Jan 25, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [c2ff1b1e23](https://linux-hardware.org/?probe=c2ff1b1e23) | Jan 25, 2023 |
| Fujitsu       | LIFEBOOK U7511              | Notebook    | [7b9b00eccb](https://linux-hardware.org/?probe=7b9b00eccb) | Jan 24, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [723d6a91bb](https://linux-hardware.org/?probe=723d6a91bb) | Jan 24, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5abd524783](https://linux-hardware.org/?probe=5abd524783) | Jan 24, 2023 |
| HP            | 2B34                        | Desktop     | [ca97840b4b](https://linux-hardware.org/?probe=ca97840b4b) | Jan 24, 2023 |
| Biostar       | Hi-Fi A85W                  | Desktop     | [4da9f87ebb](https://linux-hardware.org/?probe=4da9f87ebb) | Jan 23, 2023 |
| Acer          | Swift SFX16-52G             | Notebook    | [62e1cc77f9](https://linux-hardware.org/?probe=62e1cc77f9) | Jan 23, 2023 |
| HP            | 8399                        | Desktop     | [db427c8bc9](https://linux-hardware.org/?probe=db427c8bc9) | Jan 22, 2023 |
| HP            | 8399                        | Desktop     | [cdf9d12bb4](https://linux-hardware.org/?probe=cdf9d12bb4) | Jan 22, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [ffc0fa7fb5](https://linux-hardware.org/?probe=ffc0fa7fb5) | Jan 22, 2023 |
| HP            | Pavilion dv4                | Notebook    | [9fd79086c8](https://linux-hardware.org/?probe=9fd79086c8) | Jan 22, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [7933a58a32](https://linux-hardware.org/?probe=7933a58a32) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 20RD0019RT     | Notebook    | [282161cc92](https://linux-hardware.org/?probe=282161cc92) | Jan 22, 2023 |
| Lenovo        | ThinkPad E15 20RD0019RT     | Notebook    | [8d235b1b8d](https://linux-hardware.org/?probe=8d235b1b8d) | Jan 22, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [5e28e4cbdc](https://linux-hardware.org/?probe=5e28e4cbdc) | Jan 21, 2023 |
| Dell          | Latitude 9420               | Notebook    | [4b847961df](https://linux-hardware.org/?probe=4b847961df) | Jan 21, 2023 |
| Fujitsu       | LIFEBOOK P1630              | Notebook    | [5ee218deb4](https://linux-hardware.org/?probe=5ee218deb4) | Jan 21, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [bd51c2a953](https://linux-hardware.org/?probe=bd51c2a953) | Jan 20, 2023 |
| Medion        | P6624                       | Notebook    | [344d427f44](https://linux-hardware.org/?probe=344d427f44) | Jan 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [31698019a3](https://linux-hardware.org/?probe=31698019a3) | Jan 20, 2023 |
| ASUSTek       | X555LF                      | Notebook    | [7220c25a3b](https://linux-hardware.org/?probe=7220c25a3b) | Jan 20, 2023 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [f6b68c1767](https://linux-hardware.org/?probe=f6b68c1767) | Jan 19, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [6c8d492f56](https://linux-hardware.org/?probe=6c8d492f56) | Jan 19, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [e7548596d1](https://linux-hardware.org/?probe=e7548596d1) | Jan 19, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [1f56f8cb21](https://linux-hardware.org/?probe=1f56f8cb21) | Jan 19, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [890980b6a9](https://linux-hardware.org/?probe=890980b6a9) | Jan 19, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [28a15ffc38](https://linux-hardware.org/?probe=28a15ffc38) | Jan 19, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [b0716d3518](https://linux-hardware.org/?probe=b0716d3518) | Jan 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [004b2669ef](https://linux-hardware.org/?probe=004b2669ef) | Jan 18, 2023 |
| Fujitsu       | LIFEBOOK P1630              | Notebook    | [5a9662e39b](https://linux-hardware.org/?probe=5a9662e39b) | Jan 17, 2023 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [de3dde0785](https://linux-hardware.org/?probe=de3dde0785) | Jan 17, 2023 |
| HP            | ProBook 4540s               | Notebook    | [3f9e3a1cbb](https://linux-hardware.org/?probe=3f9e3a1cbb) | Jan 17, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [9dba648ced](https://linux-hardware.org/?probe=9dba648ced) | Jan 17, 2023 |
| HP            | ProBook 4540s               | Notebook    | [7b9cd1b51c](https://linux-hardware.org/?probe=7b9cd1b51c) | Jan 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [17fd020689](https://linux-hardware.org/?probe=17fd020689) | Jan 16, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [9b874af8a4](https://linux-hardware.org/?probe=9b874af8a4) | Jan 16, 2023 |
| HP            | Pavilion dv7                | Notebook    | [ae33b4bb24](https://linux-hardware.org/?probe=ae33b4bb24) | Jan 16, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [aae8dcf220](https://linux-hardware.org/?probe=aae8dcf220) | Jan 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [64bb2953ec](https://linux-hardware.org/?probe=64bb2953ec) | Jan 15, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [6309c0f057](https://linux-hardware.org/?probe=6309c0f057) | Jan 15, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [212fa962a2](https://linux-hardware.org/?probe=212fa962a2) | Jan 15, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [9bfcd0f555](https://linux-hardware.org/?probe=9bfcd0f555) | Jan 14, 2023 |
| MSI           | P67A-C45                    | Desktop     | [625a573f22](https://linux-hardware.org/?probe=625a573f22) | Jan 13, 2023 |
| Dell          | 0WG261                      | Desktop     | [c994d9e8ee](https://linux-hardware.org/?probe=c994d9e8ee) | Jan 13, 2023 |
| Dell          | Latitude 5414               | Notebook    | [bc4fdb0971](https://linux-hardware.org/?probe=bc4fdb0971) | Jan 13, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8674044a95](https://linux-hardware.org/?probe=8674044a95) | Jan 13, 2023 |
| Dell          | 0WG261                      | Desktop     | [5d1fe40a1f](https://linux-hardware.org/?probe=5d1fe40a1f) | Jan 13, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [64a9cc7b90](https://linux-hardware.org/?probe=64a9cc7b90) | Jan 13, 2023 |
| ASUSTek       | G56JR                       | Notebook    | [3665659d26](https://linux-hardware.org/?probe=3665659d26) | Jan 13, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [6b20e87c33](https://linux-hardware.org/?probe=6b20e87c33) | Jan 13, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [e8bf140d81](https://linux-hardware.org/?probe=e8bf140d81) | Jan 12, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | Convertible | [f3bf17dba0](https://linux-hardware.org/?probe=f3bf17dba0) | Jan 11, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [a5ea710efd](https://linux-hardware.org/?probe=a5ea710efd) | Jan 11, 2023 |
| Dell          | Latitude 9420               | Convertible | [1446885eb7](https://linux-hardware.org/?probe=1446885eb7) | Jan 11, 2023 |
| ASUSTek       | P5B                         | Desktop     | [9fd56e9b73](https://linux-hardware.org/?probe=9fd56e9b73) | Jan 08, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [2f2f7a3a60](https://linux-hardware.org/?probe=2f2f7a3a60) | Jan 08, 2023 |
| HP            | ENVY 15                     | Notebook    | [bff59f1d42](https://linux-hardware.org/?probe=bff59f1d42) | Jan 08, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [a6d6bf8d28](https://linux-hardware.org/?probe=a6d6bf8d28) | Jan 08, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c272167e6a](https://linux-hardware.org/?probe=c272167e6a) | Jan 08, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [da3dc83a74](https://linux-hardware.org/?probe=da3dc83a74) | Jan 07, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [be1be100c9](https://linux-hardware.org/?probe=be1be100c9) | Jan 07, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [a4b5bc192d](https://linux-hardware.org/?probe=a4b5bc192d) | Jan 06, 2023 |
| Dell          | 081VG9 A05                  | Server      | [23031aa11a](https://linux-hardware.org/?probe=23031aa11a) | Jan 06, 2023 |
| Dell          | G7 7790                     | Notebook    | [ffaafd92cf](https://linux-hardware.org/?probe=ffaafd92cf) | Jan 05, 2023 |
| Dell          | Latitude 5430               | Notebook    | [4e8033e0f6](https://linux-hardware.org/?probe=4e8033e0f6) | Jan 05, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [6b475a50fc](https://linux-hardware.org/?probe=6b475a50fc) | Jan 05, 2023 |
| ASRock        | H410M-HVS                   | Desktop     | [922db531b3](https://linux-hardware.org/?probe=922db531b3) | Jan 05, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [e11b38ed14](https://linux-hardware.org/?probe=e11b38ed14) | Jan 05, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [ed1bc83961](https://linux-hardware.org/?probe=ed1bc83961) | Jan 04, 2023 |
| Dell          | G3 3579                     | Notebook    | [becea24616](https://linux-hardware.org/?probe=becea24616) | Jan 04, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [9e01a37071](https://linux-hardware.org/?probe=9e01a37071) | Jan 04, 2023 |
| Dell          | 0VTJVC A00                  | Desktop     | [8a502c849f](https://linux-hardware.org/?probe=8a502c849f) | Jan 03, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [138a853640](https://linux-hardware.org/?probe=138a853640) | Jan 02, 2023 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [704cc86124](https://linux-hardware.org/?probe=704cc86124) | Jan 01, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [092aa8fe44](https://linux-hardware.org/?probe=092aa8fe44) | Jan 01, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [a8ce1c44a8](https://linux-hardware.org/?probe=a8ce1c44a8) | Jan 01, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [b68fa80860](https://linux-hardware.org/?probe=b68fa80860) | Dec 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [2508c5972e](https://linux-hardware.org/?probe=2508c5972e) | Dec 31, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [270ba62d9d](https://linux-hardware.org/?probe=270ba62d9d) | Dec 31, 2022 |
| Gigabyte      | W480 VISION D               | Desktop     | [133d8a7f70](https://linux-hardware.org/?probe=133d8a7f70) | Dec 31, 2022 |
| Intel Clie... | LAPRC710                    | Notebook    | [47e562afc7](https://linux-hardware.org/?probe=47e562afc7) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [60989ad0c4](https://linux-hardware.org/?probe=60989ad0c4) | Dec 31, 2022 |
| Dell          | XPS 9320                    | Notebook    | [c7a7749a95](https://linux-hardware.org/?probe=c7a7749a95) | Dec 30, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [0053ddb3c9](https://linux-hardware.org/?probe=0053ddb3c9) | Dec 30, 2022 |
| Dell          | XPS 9320                    | Notebook    | [458727c26e](https://linux-hardware.org/?probe=458727c26e) | Dec 30, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [250104c525](https://linux-hardware.org/?probe=250104c525) | Dec 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [0447771b4f](https://linux-hardware.org/?probe=0447771b4f) | Dec 29, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [c6325d4647](https://linux-hardware.org/?probe=c6325d4647) | Dec 29, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [23fe358945](https://linux-hardware.org/?probe=23fe358945) | Dec 29, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [a8b80cb4f6](https://linux-hardware.org/?probe=a8b80cb4f6) | Dec 28, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b073c04bea](https://linux-hardware.org/?probe=b073c04bea) | Dec 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [442fcdba27](https://linux-hardware.org/?probe=442fcdba27) | Dec 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [4ad973e635](https://linux-hardware.org/?probe=4ad973e635) | Dec 26, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [1c5b59d2e4](https://linux-hardware.org/?probe=1c5b59d2e4) | Dec 26, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [730469b496](https://linux-hardware.org/?probe=730469b496) | Dec 26, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [7e46b9fd5b](https://linux-hardware.org/?probe=7e46b9fd5b) | Dec 26, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [dde339b7c9](https://linux-hardware.org/?probe=dde339b7c9) | Dec 26, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [7b965d8da8](https://linux-hardware.org/?probe=7b965d8da8) | Dec 25, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [410ac6980a](https://linux-hardware.org/?probe=410ac6980a) | Dec 25, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [2ef0101186](https://linux-hardware.org/?probe=2ef0101186) | Dec 25, 2022 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | Notebook    | [cc51ba5d49](https://linux-hardware.org/?probe=cc51ba5d49) | Dec 24, 2022 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | Notebook    | [660e3a6511](https://linux-hardware.org/?probe=660e3a6511) | Dec 24, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [a640541ee0](https://linux-hardware.org/?probe=a640541ee0) | Dec 24, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [83203eef25](https://linux-hardware.org/?probe=83203eef25) | Dec 24, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [d5702b0c66](https://linux-hardware.org/?probe=d5702b0c66) | Dec 24, 2022 |
| Sony          | SVS1311N9ES                 | Notebook    | [5c1a4bed5b](https://linux-hardware.org/?probe=5c1a4bed5b) | Dec 24, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [ab0eabbb89](https://linux-hardware.org/?probe=ab0eabbb89) | Dec 24, 2022 |
| HP            | Pavilion 17                 | Notebook    | [0adc0d708b](https://linux-hardware.org/?probe=0adc0d708b) | Dec 23, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [8a3788aa78](https://linux-hardware.org/?probe=8a3788aa78) | Dec 23, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [c17fe8cbe0](https://linux-hardware.org/?probe=c17fe8cbe0) | Dec 23, 2022 |
| Lenovo        | Y50-70 Touch 20349          | Notebook    | [b26dc749a5](https://linux-hardware.org/?probe=b26dc749a5) | Dec 23, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [258dc5c40d](https://linux-hardware.org/?probe=258dc5c40d) | Dec 23, 2022 |
| Samsung       | 750QUA                      | Convertible | [19db82224d](https://linux-hardware.org/?probe=19db82224d) | Dec 22, 2022 |
| Schenker      | VIA 15 Pro                  | Notebook    | [b1a40c91d2](https://linux-hardware.org/?probe=b1a40c91d2) | Dec 22, 2022 |
| Schenker      | VIA 15 Pro                  | Notebook    | [75efe6fb52](https://linux-hardware.org/?probe=75efe6fb52) | Dec 22, 2022 |
| Acer          | Nitro AN515-51              | Notebook    | [9dca0f7674](https://linux-hardware.org/?probe=9dca0f7674) | Dec 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3a505870ba](https://linux-hardware.org/?probe=3a505870ba) | Dec 22, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [13e778509f](https://linux-hardware.org/?probe=13e778509f) | Dec 22, 2022 |
| Dell          | Latitude 5510               | Notebook    | [b4f32be15b](https://linux-hardware.org/?probe=b4f32be15b) | Dec 22, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [3dae14f00f](https://linux-hardware.org/?probe=3dae14f00f) | Dec 22, 2022 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [70695e9f3b](https://linux-hardware.org/?probe=70695e9f3b) | Dec 21, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [5ea57fb331](https://linux-hardware.org/?probe=5ea57fb331) | Dec 21, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [6ec5c4fc19](https://linux-hardware.org/?probe=6ec5c4fc19) | Dec 21, 2022 |
| Dell          | 0K071D A01                  | Desktop     | [49612bc7d4](https://linux-hardware.org/?probe=49612bc7d4) | Dec 21, 2022 |
| Dell          | 0K071D A01                  | Desktop     | [94204a7d2c](https://linux-hardware.org/?probe=94204a7d2c) | Dec 21, 2022 |
| Dell          | XPS 9320                    | Notebook    | [ce5835b58d](https://linux-hardware.org/?probe=ce5835b58d) | Dec 20, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [a4549398af](https://linux-hardware.org/?probe=a4549398af) | Dec 20, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [79cf1b618f](https://linux-hardware.org/?probe=79cf1b618f) | Dec 20, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [da35f3ec23](https://linux-hardware.org/?probe=da35f3ec23) | Dec 19, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [2a2f618c62](https://linux-hardware.org/?probe=2a2f618c62) | Dec 19, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [533bf9eafc](https://linux-hardware.org/?probe=533bf9eafc) | Dec 19, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [1212530d94](https://linux-hardware.org/?probe=1212530d94) | Dec 18, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [c0b006673c](https://linux-hardware.org/?probe=c0b006673c) | Dec 18, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [19e8973a92](https://linux-hardware.org/?probe=19e8973a92) | Dec 18, 2022 |
| Dell          | Latitude 5590               | Notebook    | [83e177278e](https://linux-hardware.org/?probe=83e177278e) | Dec 17, 2022 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [5fca69ae89](https://linux-hardware.org/?probe=5fca69ae89) | Dec 17, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [adc5196d64](https://linux-hardware.org/?probe=adc5196d64) | Dec 17, 2022 |
| Lenovo        | 1S20UDCT01WWPF1ARBNP 29U... | Notebook    | [b5e9681592](https://linux-hardware.org/?probe=b5e9681592) | Dec 17, 2022 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [05519b281d](https://linux-hardware.org/?probe=05519b281d) | Dec 16, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [665bd04471](https://linux-hardware.org/?probe=665bd04471) | Dec 16, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [64bdae140b](https://linux-hardware.org/?probe=64bdae140b) | Dec 16, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [0fe564693b](https://linux-hardware.org/?probe=0fe564693b) | Dec 16, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [e2a4ba00cd](https://linux-hardware.org/?probe=e2a4ba00cd) | Dec 16, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [e7334e3ced](https://linux-hardware.org/?probe=e7334e3ced) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [143d2059a6](https://linux-hardware.org/?probe=143d2059a6) | Dec 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [f5a317963c](https://linux-hardware.org/?probe=f5a317963c) | Dec 15, 2022 |
| Dell          | Precision 7760              | Notebook    | [cbe51e9db3](https://linux-hardware.org/?probe=cbe51e9db3) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [8df2e8b58c](https://linux-hardware.org/?probe=8df2e8b58c) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [1d57f3ab30](https://linux-hardware.org/?probe=1d57f3ab30) | Dec 15, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [a1d6879fab](https://linux-hardware.org/?probe=a1d6879fab) | Dec 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f18b9184ca](https://linux-hardware.org/?probe=f18b9184ca) | Dec 15, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [77fcf302d4](https://linux-hardware.org/?probe=77fcf302d4) | Dec 14, 2022 |
| Irbis         | NB264                       | Notebook    | [d137aad605](https://linux-hardware.org/?probe=d137aad605) | Dec 14, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1e2ba2a16d](https://linux-hardware.org/?probe=1e2ba2a16d) | Dec 14, 2022 |
| Samsung       | 750QUA                      | Convertible | [6c39114e7d](https://linux-hardware.org/?probe=6c39114e7d) | Dec 14, 2022 |
| ASUSTek       | Zenbook UP6502ZA_UP6502Z... | Convertible | [85c2b907d7](https://linux-hardware.org/?probe=85c2b907d7) | Dec 14, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [9369afea1b](https://linux-hardware.org/?probe=9369afea1b) | Dec 14, 2022 |
| ASRock        | 4X4-R1000                   | Desktop     | [f6b7e164dc](https://linux-hardware.org/?probe=f6b7e164dc) | Dec 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [4a3ac966fc](https://linux-hardware.org/?probe=4a3ac966fc) | Dec 13, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [ea3dbee733](https://linux-hardware.org/?probe=ea3dbee733) | Dec 13, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [441dc6d8a0](https://linux-hardware.org/?probe=441dc6d8a0) | Dec 13, 2022 |
| Lenovo        | ThinkPad T440s 20AQ004EU... | Notebook    | [8d04dfe3a5](https://linux-hardware.org/?probe=8d04dfe3a5) | Dec 12, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [780eecc5e8](https://linux-hardware.org/?probe=780eecc5e8) | Dec 12, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [b5d4116615](https://linux-hardware.org/?probe=b5d4116615) | Dec 11, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [144f698515](https://linux-hardware.org/?probe=144f698515) | Dec 11, 2022 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [e4fe543570](https://linux-hardware.org/?probe=e4fe543570) | Dec 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c715acf0ea](https://linux-hardware.org/?probe=c715acf0ea) | Dec 10, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [947534b3be](https://linux-hardware.org/?probe=947534b3be) | Dec 09, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [aea1c7da95](https://linux-hardware.org/?probe=aea1c7da95) | Dec 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [b1ac2fbabe](https://linux-hardware.org/?probe=b1ac2fbabe) | Dec 09, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [62212b2baa](https://linux-hardware.org/?probe=62212b2baa) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [29c71a771b](https://linux-hardware.org/?probe=29c71a771b) | Dec 08, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [4acc1d38e8](https://linux-hardware.org/?probe=4acc1d38e8) | Dec 08, 2022 |
| MSI           | P67A-C45                    | Desktop     | [44c8da681d](https://linux-hardware.org/?probe=44c8da681d) | Dec 07, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [31ae5769eb](https://linux-hardware.org/?probe=31ae5769eb) | Dec 07, 2022 |
| ASRock        | H410M-HVS                   | Desktop     | [a8aa92bfed](https://linux-hardware.org/?probe=a8aa92bfed) | Dec 07, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [57a9a5fbf8](https://linux-hardware.org/?probe=57a9a5fbf8) | Dec 07, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [799ba39d5e](https://linux-hardware.org/?probe=799ba39d5e) | Dec 06, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [7a2d061568](https://linux-hardware.org/?probe=7a2d061568) | Dec 06, 2022 |
| MSI           | B85-G41 PC Mate             | Desktop     | [a54611689d](https://linux-hardware.org/?probe=a54611689d) | Dec 06, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [6fc850bb3e](https://linux-hardware.org/?probe=6fc850bb3e) | Dec 06, 2022 |
| HUAWEI        | HUAWEIPGU-WBY0              | Soc         | [b4f452d2d8](https://linux-hardware.org/?probe=b4f452d2d8) | Dec 06, 2022 |
| MSI           | MS-B1711                    | Desktop     | [1fbaa02605](https://linux-hardware.org/?probe=1fbaa02605) | Dec 05, 2022 |
| Dell          | Latitude E5400              | Notebook    | [ab5b64fe8a](https://linux-hardware.org/?probe=ab5b64fe8a) | Dec 05, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [5827ea2fa5](https://linux-hardware.org/?probe=5827ea2fa5) | Dec 05, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [7f8dcdb666](https://linux-hardware.org/?probe=7f8dcdb666) | Dec 05, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [930b8d0ff2](https://linux-hardware.org/?probe=930b8d0ff2) | Dec 04, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [f2a555fb1b](https://linux-hardware.org/?probe=f2a555fb1b) | Dec 04, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [8fc8a7552b](https://linux-hardware.org/?probe=8fc8a7552b) | Dec 04, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | Desktop     | [5326fede0a](https://linux-hardware.org/?probe=5326fede0a) | Dec 04, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [50bcdd33eb](https://linux-hardware.org/?probe=50bcdd33eb) | Dec 04, 2022 |
| HP            | 2B52                        | Desktop     | [e2e8bdd4f6](https://linux-hardware.org/?probe=e2e8bdd4f6) | Dec 03, 2022 |
| TYAN Compu... | S8026GM2NRE-HOV-B           | Server      | [d2813c6963](https://linux-hardware.org/?probe=d2813c6963) | Dec 03, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [8d4e2bdcb9](https://linux-hardware.org/?probe=8d4e2bdcb9) | Dec 03, 2022 |
| Medion        | D3F3-EM2                    | Desktop     | [e46ba957f0](https://linux-hardware.org/?probe=e46ba957f0) | Dec 02, 2022 |
| ASUSTek       | A8N-E                       | Desktop     | [a1020380dd](https://linux-hardware.org/?probe=a1020380dd) | Dec 02, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [87b13a5112](https://linux-hardware.org/?probe=87b13a5112) | Dec 02, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [82c0eb6155](https://linux-hardware.org/?probe=82c0eb6155) | Dec 02, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [ee17f7d657](https://linux-hardware.org/?probe=ee17f7d657) | Dec 02, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [a4ed7efef9](https://linux-hardware.org/?probe=a4ed7efef9) | Dec 01, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [5eebfea632](https://linux-hardware.org/?probe=5eebfea632) | Dec 01, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [961f58c143](https://linux-hardware.org/?probe=961f58c143) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [0461e6b5d2](https://linux-hardware.org/?probe=0461e6b5d2) | Dec 01, 2022 |
| ASRock        | 970 Extreme3                | Desktop     | [4951da34da](https://linux-hardware.org/?probe=4951da34da) | Nov 30, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [a41d7dbfb1](https://linux-hardware.org/?probe=a41d7dbfb1) | Nov 29, 2022 |
| VA_IP3        | GMLR_V1                     | Mini pc     | [ac6676f125](https://linux-hardware.org/?probe=ac6676f125) | Nov 29, 2022 |
| Supermicro    | X8DTG-D                     | Server      | [9e977b651e](https://linux-hardware.org/?probe=9e977b651e) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [ffe997080f](https://linux-hardware.org/?probe=ffe997080f) | Nov 28, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [944ade9560](https://linux-hardware.org/?probe=944ade9560) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4c6d3faf86](https://linux-hardware.org/?probe=4c6d3faf86) | Nov 28, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [cd98ebccb9](https://linux-hardware.org/?probe=cd98ebccb9) | Nov 28, 2022 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [cc1637d7e2](https://linux-hardware.org/?probe=cc1637d7e2) | Nov 27, 2022 |
| Lenovo        | ThinkPad X260 20F6005HUS    | Notebook    | [6418eda1a9](https://linux-hardware.org/?probe=6418eda1a9) | Nov 27, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [ffd2220d21](https://linux-hardware.org/?probe=ffd2220d21) | Nov 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [fc5f72597d](https://linux-hardware.org/?probe=fc5f72597d) | Nov 25, 2022 |
| MSI           | GE72VR 7RF                  | Notebook    | [a034af6b70](https://linux-hardware.org/?probe=a034af6b70) | Nov 25, 2022 |
| Dell          | Inspiron 14 Plus 7420       | Notebook    | [a35ca4bbbe](https://linux-hardware.org/?probe=a35ca4bbbe) | Nov 24, 2022 |
| Dell          | Latitude E5570              | Notebook    | [ed2e9cfb4f](https://linux-hardware.org/?probe=ed2e9cfb4f) | Nov 24, 2022 |
| HP            | Pavilion 15                 | Notebook    | [b0d1e2e0ba](https://linux-hardware.org/?probe=b0d1e2e0ba) | Nov 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [96a68d5d80](https://linux-hardware.org/?probe=96a68d5d80) | Nov 24, 2022 |
| HP            | 212B                        | Desktop     | [3ac96bbb45](https://linux-hardware.org/?probe=3ac96bbb45) | Nov 24, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [ca7045ed57](https://linux-hardware.org/?probe=ca7045ed57) | Nov 24, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [eaab6a8319](https://linux-hardware.org/?probe=eaab6a8319) | Nov 23, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [9758f3268e](https://linux-hardware.org/?probe=9758f3268e) | Nov 23, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [17b880ceb9](https://linux-hardware.org/?probe=17b880ceb9) | Nov 23, 2022 |
| Dell          | Latitude 5401               | Notebook    | [f964652e0c](https://linux-hardware.org/?probe=f964652e0c) | Nov 22, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [a38b2f2f2a](https://linux-hardware.org/?probe=a38b2f2f2a) | Nov 22, 2022 |
| Timi          | TM1612                      | Notebook    | [abd08d53c7](https://linux-hardware.org/?probe=abd08d53c7) | Nov 22, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [be2c23e33c](https://linux-hardware.org/?probe=be2c23e33c) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [8b8ac358e4](https://linux-hardware.org/?probe=8b8ac358e4) | Nov 21, 2022 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [07210e29c5](https://linux-hardware.org/?probe=07210e29c5) | Nov 21, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [2890235d49](https://linux-hardware.org/?probe=2890235d49) | Nov 21, 2022 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | Notebook    | [d9a74ee60a](https://linux-hardware.org/?probe=d9a74ee60a) | Nov 20, 2022 |
| Acer          | Aspire A317-51              | Notebook    | [43c8f9b08b](https://linux-hardware.org/?probe=43c8f9b08b) | Nov 19, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [4f3c7d5501](https://linux-hardware.org/?probe=4f3c7d5501) | Nov 19, 2022 |
| Acer          | Aspire A317-51              | Notebook    | [a4a3dabbb4](https://linux-hardware.org/?probe=a4a3dabbb4) | Nov 19, 2022 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | Notebook    | [05c9ad6f4a](https://linux-hardware.org/?probe=05c9ad6f4a) | Nov 19, 2022 |
| Dell          | Latitude 5414               | Notebook    | [a408bec327](https://linux-hardware.org/?probe=a408bec327) | Nov 18, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [7139ac864a](https://linux-hardware.org/?probe=7139ac864a) | Nov 17, 2022 |
| HP            | 8055                        | Desktop     | [4195a9765a](https://linux-hardware.org/?probe=4195a9765a) | Nov 17, 2022 |
| MSI           | A75MA-G55                   | Desktop     | [b678f31b24](https://linux-hardware.org/?probe=b678f31b24) | Nov 16, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [371368cfe7](https://linux-hardware.org/?probe=371368cfe7) | Nov 16, 2022 |
| HP            | Compaq 6830s                | Notebook    | [074c3a8b43](https://linux-hardware.org/?probe=074c3a8b43) | Nov 14, 2022 |
| HP            | Notebook                    | Notebook    | [b0d1cd283f](https://linux-hardware.org/?probe=b0d1cd283f) | Nov 14, 2022 |
| HP            | Notebook                    | Notebook    | [95ecccf4c7](https://linux-hardware.org/?probe=95ecccf4c7) | Nov 14, 2022 |
| SLIMBOOK      | PROX14                      | Notebook    | [a109c5bf52](https://linux-hardware.org/?probe=a109c5bf52) | Nov 14, 2022 |
| Gigabyte      | Z370XP SLI-CF               | Desktop     | [3b6d611387](https://linux-hardware.org/?probe=3b6d611387) | Nov 14, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [3eb034e033](https://linux-hardware.org/?probe=3eb034e033) | Nov 13, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [18b42b8ead](https://linux-hardware.org/?probe=18b42b8ead) | Nov 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [e4470c4bda](https://linux-hardware.org/?probe=e4470c4bda) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b2dbd8f602](https://linux-hardware.org/?probe=b2dbd8f602) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [59a0a26e78](https://linux-hardware.org/?probe=59a0a26e78) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [59d3c93814](https://linux-hardware.org/?probe=59d3c93814) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [dc0e46c7b3](https://linux-hardware.org/?probe=dc0e46c7b3) | Nov 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [75f7a51f9e](https://linux-hardware.org/?probe=75f7a51f9e) | Nov 12, 2022 |
| MSI           | B450M BAZOOKA PLUS          | Desktop     | [f63b2757ea](https://linux-hardware.org/?probe=f63b2757ea) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [57368a1129](https://linux-hardware.org/?probe=57368a1129) | Nov 12, 2022 |
| Lenovo        | ThinkPad T530 2394D56       | Notebook    | [3d44b768e5](https://linux-hardware.org/?probe=3d44b768e5) | Nov 12, 2022 |
| Gigabyte      | Z370XP SLI-CF               | Desktop     | [4e0b0368b8](https://linux-hardware.org/?probe=4e0b0368b8) | Nov 12, 2022 |
| Samsung       | 730QDA                      | Convertible | [a7a2ca6941](https://linux-hardware.org/?probe=a7a2ca6941) | Nov 12, 2022 |
| Toshiba       | IS 1422+                    | Notebook    | [0c948c9926](https://linux-hardware.org/?probe=0c948c9926) | Nov 11, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [969fa6c183](https://linux-hardware.org/?probe=969fa6c183) | Nov 11, 2022 |
| Intel         | (R) Education Tablet        | Notebook    | [13286af46e](https://linux-hardware.org/?probe=13286af46e) | Nov 10, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [8a5e954190](https://linux-hardware.org/?probe=8a5e954190) | Nov 10, 2022 |
| HP            | ZBook 17                    | Notebook    | [e866fa1319](https://linux-hardware.org/?probe=e866fa1319) | Nov 09, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [776a9bc0b6](https://linux-hardware.org/?probe=776a9bc0b6) | Nov 09, 2022 |
| Lenovo        | B50-80 80LT                 | Notebook    | [c16106686d](https://linux-hardware.org/?probe=c16106686d) | Nov 08, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [be071c7456](https://linux-hardware.org/?probe=be071c7456) | Nov 08, 2022 |
| HP            | ZBook 17                    | Notebook    | [af26e94623](https://linux-hardware.org/?probe=af26e94623) | Nov 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e13f29fc81](https://linux-hardware.org/?probe=e13f29fc81) | Nov 07, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [3f80a8a4c4](https://linux-hardware.org/?probe=3f80a8a4c4) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [db62973b36](https://linux-hardware.org/?probe=db62973b36) | Nov 06, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [912bfcc57e](https://linux-hardware.org/?probe=912bfcc57e) | Nov 06, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [0f119b6000](https://linux-hardware.org/?probe=0f119b6000) | Nov 06, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [e872fcb5f7](https://linux-hardware.org/?probe=e872fcb5f7) | Nov 06, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [b5470f4f19](https://linux-hardware.org/?probe=b5470f4f19) | Nov 06, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [ec3bc58f50](https://linux-hardware.org/?probe=ec3bc58f50) | Nov 05, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7590df932b](https://linux-hardware.org/?probe=7590df932b) | Nov 05, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c177c82021](https://linux-hardware.org/?probe=c177c82021) | Nov 05, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [99e32a37ff](https://linux-hardware.org/?probe=99e32a37ff) | Nov 04, 2022 |
| ASUSTek       | A55BM-PLUS                  | Desktop     | [2d2c00b163](https://linux-hardware.org/?probe=2d2c00b163) | Nov 04, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [011d776675](https://linux-hardware.org/?probe=011d776675) | Nov 04, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [442942f712](https://linux-hardware.org/?probe=442942f712) | Nov 04, 2022 |
| MSI           | B350M GAMING PRO            | Desktop     | [7255a61579](https://linux-hardware.org/?probe=7255a61579) | Nov 03, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [b3613b84ad](https://linux-hardware.org/?probe=b3613b84ad) | Nov 02, 2022 |
| ASUSTek       | F2A55-M LK                  | Desktop     | [40cedc7d2c](https://linux-hardware.org/?probe=40cedc7d2c) | Nov 02, 2022 |
| HP            | 829B                        | All in one  | [23122cba32](https://linux-hardware.org/?probe=23122cba32) | Nov 01, 2022 |
| Dell          | 0C522T A01                  | Desktop     | [efee8139b0](https://linux-hardware.org/?probe=efee8139b0) | Nov 01, 2022 |
| HP            | Notebook                    | Notebook    | [27d097b522](https://linux-hardware.org/?probe=27d097b522) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0131299a9e](https://linux-hardware.org/?probe=0131299a9e) | Nov 01, 2022 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [4833a609c3](https://linux-hardware.org/?probe=4833a609c3) | Oct 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d7e9fb65d0](https://linux-hardware.org/?probe=d7e9fb65d0) | Oct 30, 2022 |
| Lenovo        | ThinkPad W510 431965U       | Notebook    | [56dd93206a](https://linux-hardware.org/?probe=56dd93206a) | Oct 29, 2022 |
| Acer          | Extensa 215-54              | Notebook    | [0fe46d7655](https://linux-hardware.org/?probe=0fe46d7655) | Oct 29, 2022 |
| Dell          | Vostro 3580                 | Notebook    | [74a79dbdb6](https://linux-hardware.org/?probe=74a79dbdb6) | Oct 29, 2022 |
| Samsung       | 930QDB                      | Convertible | [453d856b8d](https://linux-hardware.org/?probe=453d856b8d) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [6314ec0dd1](https://linux-hardware.org/?probe=6314ec0dd1) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [dcd40f9f78](https://linux-hardware.org/?probe=dcd40f9f78) | Oct 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [033cc83715](https://linux-hardware.org/?probe=033cc83715) | Oct 28, 2022 |
| Dell          | Latitude E6430              | Notebook    | [cb4eb1f556](https://linux-hardware.org/?probe=cb4eb1f556) | Oct 28, 2022 |
| Lenovo        | Unknown                     | Notebook    | [6a3e704d70](https://linux-hardware.org/?probe=6a3e704d70) | Oct 27, 2022 |
| Radxa         | Zero                        | Soc         | [e35d41a9a6](https://linux-hardware.org/?probe=e35d41a9a6) | Oct 27, 2022 |
| Dell          | Latitude 9420               | Notebook    | [a601281b46](https://linux-hardware.org/?probe=a601281b46) | Oct 27, 2022 |
| MSI           | X58 Pro                     | Desktop     | [6c449246c8](https://linux-hardware.org/?probe=6c449246c8) | Oct 27, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [a943d9879c](https://linux-hardware.org/?probe=a943d9879c) | Oct 26, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [5fa9b60268](https://linux-hardware.org/?probe=5fa9b60268) | Oct 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [3d86f7ccac](https://linux-hardware.org/?probe=3d86f7ccac) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [9e63ba2bf9](https://linux-hardware.org/?probe=9e63ba2bf9) | Oct 23, 2022 |
| Dell          | 0D90HM A00                  | All in one  | [3a60ac01f4](https://linux-hardware.org/?probe=3a60ac01f4) | Oct 23, 2022 |
| MSI           | X58 Pro                     | Desktop     | [96db21189e](https://linux-hardware.org/?probe=96db21189e) | Oct 22, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [94f3d7aa9d](https://linux-hardware.org/?probe=94f3d7aa9d) | Oct 22, 2022 |
| Dell          | 0D90HM A00                  | All in one  | [fbc271b648](https://linux-hardware.org/?probe=fbc271b648) | Oct 22, 2022 |
| Lenovo        | 3111 NOK                    | Desktop     | [185e1ca963](https://linux-hardware.org/?probe=185e1ca963) | Oct 21, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [4c699ac628](https://linux-hardware.org/?probe=4c699ac628) | Oct 21, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [5e59c8933b](https://linux-hardware.org/?probe=5e59c8933b) | Oct 20, 2022 |
| HP            | ZBook 17                    | Notebook    | [6dc9848327](https://linux-hardware.org/?probe=6dc9848327) | Oct 20, 2022 |
| Sony          | VPCEL3S1R                   | Notebook    | [5c37559c2d](https://linux-hardware.org/?probe=5c37559c2d) | Oct 20, 2022 |
| Fujitsu Si... | D2399 S26361-D2399          | Desktop     | [77a5931c66](https://linux-hardware.org/?probe=77a5931c66) | Oct 20, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [46b9d8c126](https://linux-hardware.org/?probe=46b9d8c126) | Oct 19, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [a078a2f2ae](https://linux-hardware.org/?probe=a078a2f2ae) | Oct 19, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [a66d2944a8](https://linux-hardware.org/?probe=a66d2944a8) | Oct 18, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [e4769fb9e0](https://linux-hardware.org/?probe=e4769fb9e0) | Oct 18, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [76bb60e5ee](https://linux-hardware.org/?probe=76bb60e5ee) | Oct 17, 2022 |
| MSI           | GE70 2PE                    | Notebook    | [ff621f681e](https://linux-hardware.org/?probe=ff621f681e) | Oct 17, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [8b1714d48d](https://linux-hardware.org/?probe=8b1714d48d) | Oct 17, 2022 |
| MSI           | H170I PRO AC                | Desktop     | [ea4ecf6238](https://linux-hardware.org/?probe=ea4ecf6238) | Oct 17, 2022 |
| MSI           | A75MA-G55                   | Desktop     | [79c4c3b21f](https://linux-hardware.org/?probe=79c4c3b21f) | Oct 16, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [f1e08df02d](https://linux-hardware.org/?probe=f1e08df02d) | Oct 16, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [2dd0b46420](https://linux-hardware.org/?probe=2dd0b46420) | Oct 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [b11fa8e1dd](https://linux-hardware.org/?probe=b11fa8e1dd) | Oct 16, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [6ccc41cf96](https://linux-hardware.org/?probe=6ccc41cf96) | Oct 15, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [a29fae2a74](https://linux-hardware.org/?probe=a29fae2a74) | Oct 14, 2022 |
| MSI           | Prestige 14 A11SCS          | Notebook    | [e552920463](https://linux-hardware.org/?probe=e552920463) | Oct 13, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [61eb97192e](https://linux-hardware.org/?probe=61eb97192e) | Oct 12, 2022 |
| Toshiba       | Satellite P55t-A            | Notebook    | [60d52e85a0](https://linux-hardware.org/?probe=60d52e85a0) | Oct 12, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [31fbbb40a0](https://linux-hardware.org/?probe=31fbbb40a0) | Oct 11, 2022 |
| Lenovo        | ThinkPad T430 2347DS3       | Notebook    | [970542656e](https://linux-hardware.org/?probe=970542656e) | Oct 11, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [52997332e0](https://linux-hardware.org/?probe=52997332e0) | Oct 11, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [50b8cde0ed](https://linux-hardware.org/?probe=50b8cde0ed) | Oct 10, 2022 |
| Intel         | (R) Education Tablet        | Notebook    | [9d1756d283](https://linux-hardware.org/?probe=9d1756d283) | Oct 09, 2022 |
| Gateway       | NV54 Series                 | Notebook    | [88b57ed4e4](https://linux-hardware.org/?probe=88b57ed4e4) | Oct 09, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [7d71e688f4](https://linux-hardware.org/?probe=7d71e688f4) | Oct 08, 2022 |
| ASUSTek       | F3Sv                        | Notebook    | [042104bbc2](https://linux-hardware.org/?probe=042104bbc2) | Oct 08, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [b8f7c25d91](https://linux-hardware.org/?probe=b8f7c25d91) | Oct 07, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [79268bac9b](https://linux-hardware.org/?probe=79268bac9b) | Oct 06, 2022 |
| Dell          | 0D90HM A00                  | All in one  | [9ef16d569e](https://linux-hardware.org/?probe=9ef16d569e) | Oct 06, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [cf2e5dae86](https://linux-hardware.org/?probe=cf2e5dae86) | Oct 06, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [c12ce7288b](https://linux-hardware.org/?probe=c12ce7288b) | Oct 05, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [c3306965d6](https://linux-hardware.org/?probe=c3306965d6) | Oct 05, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [b07d3b7b7f](https://linux-hardware.org/?probe=b07d3b7b7f) | Oct 05, 2022 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [33a0cb05e8](https://linux-hardware.org/?probe=33a0cb05e8) | Oct 04, 2022 |
| Acer          | S50-54                      | Notebook    | [7680195105](https://linux-hardware.org/?probe=7680195105) | Oct 04, 2022 |
| Dell          | Latitude 3340               | Notebook    | [100b89b0a9](https://linux-hardware.org/?probe=100b89b0a9) | Oct 04, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [daec61299a](https://linux-hardware.org/?probe=daec61299a) | Oct 03, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [79f922d367](https://linux-hardware.org/?probe=79f922d367) | Oct 02, 2022 |
| Acer          | S50-54                      | Notebook    | [a7ff4f9792](https://linux-hardware.org/?probe=a7ff4f9792) | Oct 02, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [59c14fb5c0](https://linux-hardware.org/?probe=59c14fb5c0) | Oct 02, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [9121550ca1](https://linux-hardware.org/?probe=9121550ca1) | Oct 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6e3b616977](https://linux-hardware.org/?probe=6e3b616977) | Oct 02, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [921b395e9c](https://linux-hardware.org/?probe=921b395e9c) | Oct 02, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [bf657c61f5](https://linux-hardware.org/?probe=bf657c61f5) | Oct 02, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2c82f3311d](https://linux-hardware.org/?probe=2c82f3311d) | Sep 28, 2022 |
| Dell          | Latitude E5250              | Notebook    | [6116460e52](https://linux-hardware.org/?probe=6116460e52) | Sep 27, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [d6d9af3173](https://linux-hardware.org/?probe=d6d9af3173) | Sep 26, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [ff70118578](https://linux-hardware.org/?probe=ff70118578) | Sep 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [6c0c9c0037](https://linux-hardware.org/?probe=6c0c9c0037) | Sep 25, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [e0ae893d39](https://linux-hardware.org/?probe=e0ae893d39) | Sep 25, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | Notebook    | [911a73323d](https://linux-hardware.org/?probe=911a73323d) | Sep 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a2b3fd8ea8](https://linux-hardware.org/?probe=a2b3fd8ea8) | Sep 24, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [fd63352b24](https://linux-hardware.org/?probe=fd63352b24) | Sep 24, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1bec04d42d](https://linux-hardware.org/?probe=1bec04d42d) | Sep 21, 2022 |
| Timi          | A35S                        | Notebook    | [a57a688f31](https://linux-hardware.org/?probe=a57a688f31) | Sep 21, 2022 |
| Dell          | Latitude 7400               | Notebook    | [466bd310ef](https://linux-hardware.org/?probe=466bd310ef) | Sep 21, 2022 |
| ASUSTek       | WS C422 PRO_SE              | Desktop     | [e278a4ab5e](https://linux-hardware.org/?probe=e278a4ab5e) | Sep 21, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [ed6f75ec9f](https://linux-hardware.org/?probe=ed6f75ec9f) | Sep 20, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [af2eb79f4c](https://linux-hardware.org/?probe=af2eb79f4c) | Sep 20, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [5b0c60618f](https://linux-hardware.org/?probe=5b0c60618f) | Sep 20, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [a7f0e24464](https://linux-hardware.org/?probe=a7f0e24464) | Sep 20, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [7f7ef47d4b](https://linux-hardware.org/?probe=7f7ef47d4b) | Sep 20, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [167d69530f](https://linux-hardware.org/?probe=167d69530f) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d3b972d870](https://linux-hardware.org/?probe=d3b972d870) | Sep 19, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [959330d9c1](https://linux-hardware.org/?probe=959330d9c1) | Sep 19, 2022 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [2daced0309](https://linux-hardware.org/?probe=2daced0309) | Sep 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [43bc9e36cd](https://linux-hardware.org/?probe=43bc9e36cd) | Sep 17, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [42f1c1aee1](https://linux-hardware.org/?probe=42f1c1aee1) | Sep 17, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1d4585c98a](https://linux-hardware.org/?probe=1d4585c98a) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [e85965bc82](https://linux-hardware.org/?probe=e85965bc82) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [0278cf2e45](https://linux-hardware.org/?probe=0278cf2e45) | Sep 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a4dad191d2](https://linux-hardware.org/?probe=a4dad191d2) | Sep 15, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [889c55b24d](https://linux-hardware.org/?probe=889c55b24d) | Sep 15, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [337ccff161](https://linux-hardware.org/?probe=337ccff161) | Sep 15, 2022 |
| ASUSTek       | X55CR                       | Notebook    | [43b77d436c](https://linux-hardware.org/?probe=43b77d436c) | Sep 14, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [f9c010c1a9](https://linux-hardware.org/?probe=f9c010c1a9) | Sep 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c0e411a96d](https://linux-hardware.org/?probe=c0e411a96d) | Sep 13, 2022 |
| MSI           | X58 Pro                     | Desktop     | [60406c82e8](https://linux-hardware.org/?probe=60406c82e8) | Sep 12, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [6d70631176](https://linux-hardware.org/?probe=6d70631176) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [a30032ef92](https://linux-hardware.org/?probe=a30032ef92) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [0645f03606](https://linux-hardware.org/?probe=0645f03606) | Sep 11, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [7532844cd7](https://linux-hardware.org/?probe=7532844cd7) | Sep 11, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [cae551826b](https://linux-hardware.org/?probe=cae551826b) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [706514d122](https://linux-hardware.org/?probe=706514d122) | Sep 10, 2022 |
| ASUSTek       | V161GAR                     | All in one  | [668d4ac33b](https://linux-hardware.org/?probe=668d4ac33b) | Sep 09, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [921b9580f4](https://linux-hardware.org/?probe=921b9580f4) | Sep 09, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [b11b5bcba5](https://linux-hardware.org/?probe=b11b5bcba5) | Sep 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [ea53dc8c02](https://linux-hardware.org/?probe=ea53dc8c02) | Sep 07, 2022 |
| MSI           | P67A-C45                    | Desktop     | [4221289e11](https://linux-hardware.org/?probe=4221289e11) | Sep 07, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [492849d42d](https://linux-hardware.org/?probe=492849d42d) | Sep 07, 2022 |
| Dell          | Precision 5530              | Notebook    | [d588e96ddc](https://linux-hardware.org/?probe=d588e96ddc) | Sep 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [068c169aa0](https://linux-hardware.org/?probe=068c169aa0) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [f0ce37ab5a](https://linux-hardware.org/?probe=f0ce37ab5a) | Sep 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | Desktop     | [6e0984d7ff](https://linux-hardware.org/?probe=6e0984d7ff) | Sep 06, 2022 |
| Biostar       | H77MU3                      | Desktop     | [20ba4d44ed](https://linux-hardware.org/?probe=20ba4d44ed) | Sep 05, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [312e65fd07](https://linux-hardware.org/?probe=312e65fd07) | Sep 05, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8c4261ac4f](https://linux-hardware.org/?probe=8c4261ac4f) | Sep 04, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [b298d162b1](https://linux-hardware.org/?probe=b298d162b1) | Sep 04, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [f79c38f9ff](https://linux-hardware.org/?probe=f79c38f9ff) | Sep 02, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ede97805ec](https://linux-hardware.org/?probe=ede97805ec) | Sep 02, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [3772ec2911](https://linux-hardware.org/?probe=3772ec2911) | Sep 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [e5ae0e72ca](https://linux-hardware.org/?probe=e5ae0e72ca) | Sep 02, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [0104e26464](https://linux-hardware.org/?probe=0104e26464) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [dea9852124](https://linux-hardware.org/?probe=dea9852124) | Sep 02, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [2615743a16](https://linux-hardware.org/?probe=2615743a16) | Sep 02, 2022 |
| ASUSTek       | Z97-PRO                     | Desktop     | [60865c8ded](https://linux-hardware.org/?probe=60865c8ded) | Sep 02, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [68170e253f](https://linux-hardware.org/?probe=68170e253f) | Sep 01, 2022 |
| Notebook      | N24_25JU                    | Notebook    | [50f570f3d9](https://linux-hardware.org/?probe=50f570f3d9) | Aug 31, 2022 |
| Positivo      | W942SW_SW1                  | Notebook    | [bec76a1474](https://linux-hardware.org/?probe=bec76a1474) | Aug 30, 2022 |
| HP            | ZBook 17                    | Notebook    | [98e643f5af](https://linux-hardware.org/?probe=98e643f5af) | Aug 30, 2022 |
| ASRock        | B85 Pro4                    | Desktop     | [db3bc987b6](https://linux-hardware.org/?probe=db3bc987b6) | Aug 29, 2022 |
| Positivo      | W942SW_SW1                  | Notebook    | [62dcad10f0](https://linux-hardware.org/?probe=62dcad10f0) | Aug 29, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [e27f786190](https://linux-hardware.org/?probe=e27f786190) | Aug 28, 2022 |
| MSI           | P67A-C45                    | Desktop     | [5ffb676e01](https://linux-hardware.org/?probe=5ffb676e01) | Aug 27, 2022 |
| Google        | Eldrid                      | Notebook    | [6a0c6eb1de](https://linux-hardware.org/?probe=6a0c6eb1de) | Aug 27, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | Notebook    | [04f9f63255](https://linux-hardware.org/?probe=04f9f63255) | Aug 26, 2022 |
| Gigabyte      | 965P-DS3                    | Desktop     | [38a4407789](https://linux-hardware.org/?probe=38a4407789) | Aug 25, 2022 |
| Eluktronic... | MAX-17                      | Notebook    | [0a454665e0](https://linux-hardware.org/?probe=0a454665e0) | Aug 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8021bbb58b](https://linux-hardware.org/?probe=8021bbb58b) | Aug 24, 2022 |
| HP            | 802F                        | Desktop     | [2c52215323](https://linux-hardware.org/?probe=2c52215323) | Aug 23, 2022 |
| HP            | 802F                        | Desktop     | [e181d03426](https://linux-hardware.org/?probe=e181d03426) | Aug 23, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [57727c2af7](https://linux-hardware.org/?probe=57727c2af7) | Aug 23, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [a9f2cced08](https://linux-hardware.org/?probe=a9f2cced08) | Aug 22, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [9590ddbb06](https://linux-hardware.org/?probe=9590ddbb06) | Aug 22, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [c956ba84ed](https://linux-hardware.org/?probe=c956ba84ed) | Aug 22, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [68fa656563](https://linux-hardware.org/?probe=68fa656563) | Aug 21, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [a80c24ae6b](https://linux-hardware.org/?probe=a80c24ae6b) | Aug 21, 2022 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [20a816d976](https://linux-hardware.org/?probe=20a816d976) | Aug 21, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a69a02f102](https://linux-hardware.org/?probe=a69a02f102) | Aug 20, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [b0579e2127](https://linux-hardware.org/?probe=b0579e2127) | Aug 19, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [8620d444d4](https://linux-hardware.org/?probe=8620d444d4) | Aug 19, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [5893f7215e](https://linux-hardware.org/?probe=5893f7215e) | Aug 19, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [9e6a3e80b4](https://linux-hardware.org/?probe=9e6a3e80b4) | Aug 19, 2022 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [f10fe1f561](https://linux-hardware.org/?probe=f10fe1f561) | Aug 18, 2022 |
| ASRock        | Z490 Phantom Gaming 4       | Desktop     | [7b66b20b9f](https://linux-hardware.org/?probe=7b66b20b9f) | Aug 17, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [0e2658915d](https://linux-hardware.org/?probe=0e2658915d) | Aug 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW1F    | Notebook    | [88ad38d9f7](https://linux-hardware.org/?probe=88ad38d9f7) | Aug 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW1F    | Notebook    | [73b611ea50](https://linux-hardware.org/?probe=73b611ea50) | Aug 17, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [1ef086a230](https://linux-hardware.org/?probe=1ef086a230) | Aug 16, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a05b95b836](https://linux-hardware.org/?probe=a05b95b836) | Aug 15, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [aea2bfde6a](https://linux-hardware.org/?probe=aea2bfde6a) | Aug 15, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [d9fa82e283](https://linux-hardware.org/?probe=d9fa82e283) | Aug 15, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [fd64b105a4](https://linux-hardware.org/?probe=fd64b105a4) | Aug 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [73f2db9159](https://linux-hardware.org/?probe=73f2db9159) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [b3df3a51e0](https://linux-hardware.org/?probe=b3df3a51e0) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [2043908eed](https://linux-hardware.org/?probe=2043908eed) | Aug 14, 2022 |
| Dell          | Latitude E6430              | Notebook    | [91a44f9b39](https://linux-hardware.org/?probe=91a44f9b39) | Aug 13, 2022 |
| Dell          | Latitude E6430              | Notebook    | [864ad41c22](https://linux-hardware.org/?probe=864ad41c22) | Aug 13, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [b1498c810e](https://linux-hardware.org/?probe=b1498c810e) | Aug 12, 2022 |
| ASRock        | X570 Steel Legend WiFi a... | Desktop     | [36a169c447](https://linux-hardware.org/?probe=36a169c447) | Aug 11, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [42f35776a6](https://linux-hardware.org/?probe=42f35776a6) | Aug 10, 2022 |
| HP            | Laptop 17-by1xxx            | Notebook    | [1be4a11102](https://linux-hardware.org/?probe=1be4a11102) | Aug 09, 2022 |
| ASUSTek       | H81M-CS/BR                  | Desktop     | [8c2dc32c37](https://linux-hardware.org/?probe=8c2dc32c37) | Aug 09, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [119cdc7bf8](https://linux-hardware.org/?probe=119cdc7bf8) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [0aada24b1e](https://linux-hardware.org/?probe=0aada24b1e) | Aug 07, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [054c0beb4f](https://linux-hardware.org/?probe=054c0beb4f) | Aug 07, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [73027b2cca](https://linux-hardware.org/?probe=73027b2cca) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [37f87e94fc](https://linux-hardware.org/?probe=37f87e94fc) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [6880ac8488](https://linux-hardware.org/?probe=6880ac8488) | Aug 06, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [ec98a546e1](https://linux-hardware.org/?probe=ec98a546e1) | Aug 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [904bd1db44](https://linux-hardware.org/?probe=904bd1db44) | Aug 06, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [169fcf7943](https://linux-hardware.org/?probe=169fcf7943) | Aug 05, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [ddd717c7e6](https://linux-hardware.org/?probe=ddd717c7e6) | Aug 05, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [1498e07a4b](https://linux-hardware.org/?probe=1498e07a4b) | Aug 04, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [99f7986364](https://linux-hardware.org/?probe=99f7986364) | Aug 02, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [fbe4f4d2ce](https://linux-hardware.org/?probe=fbe4f4d2ce) | Aug 02, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [eeccdc2b7f](https://linux-hardware.org/?probe=eeccdc2b7f) | Aug 02, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [15bb5d1160](https://linux-hardware.org/?probe=15bb5d1160) | Aug 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2e2f0ef440](https://linux-hardware.org/?probe=2e2f0ef440) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [80007c0939](https://linux-hardware.org/?probe=80007c0939) | Jul 31, 2022 |
| Dell          | 052RF2 A01                  | Server      | [abe955b96f](https://linux-hardware.org/?probe=abe955b96f) | Jul 31, 2022 |
| Dell          | 052RF2 A01                  | Server      | [8ffda4cfe7](https://linux-hardware.org/?probe=8ffda4cfe7) | Jul 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ae030e58fb](https://linux-hardware.org/?probe=ae030e58fb) | Jul 31, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [24fa962b0b](https://linux-hardware.org/?probe=24fa962b0b) | Jul 28, 2022 |
| Lenovo        | ThinkPad W510 431965U       | Notebook    | [ab6b15eef4](https://linux-hardware.org/?probe=ab6b15eef4) | Jul 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [4d9a472691](https://linux-hardware.org/?probe=4d9a472691) | Jul 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [ded9f7587a](https://linux-hardware.org/?probe=ded9f7587a) | Jul 27, 2022 |
| Lenovo        | ThinkPad W510 431965U       | Notebook    | [8ba9959c19](https://linux-hardware.org/?probe=8ba9959c19) | Jul 27, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [af32973765](https://linux-hardware.org/?probe=af32973765) | Jul 26, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [56c2008bb6](https://linux-hardware.org/?probe=56c2008bb6) | Jul 25, 2022 |
| Gigabyte      | W480 VISION D               | Desktop     | [7f2dde6f76](https://linux-hardware.org/?probe=7f2dde6f76) | Jul 25, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [b874a0aa8e](https://linux-hardware.org/?probe=b874a0aa8e) | Jul 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [0c4182ee0a](https://linux-hardware.org/?probe=0c4182ee0a) | Jul 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [7a29580deb](https://linux-hardware.org/?probe=7a29580deb) | Jul 23, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [df5bd62f9a](https://linux-hardware.org/?probe=df5bd62f9a) | Jul 23, 2022 |
| HP            | 8715                        | Mini pc     | [75c873bb8e](https://linux-hardware.org/?probe=75c873bb8e) | Jul 23, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [7cb795f428](https://linux-hardware.org/?probe=7cb795f428) | Jul 22, 2022 |
| Biostar       | B450MH                      | Desktop     | [f69c4e3a03](https://linux-hardware.org/?probe=f69c4e3a03) | Jul 21, 2022 |
| Biostar       | B450MH                      | Desktop     | [79084ef4c9](https://linux-hardware.org/?probe=79084ef4c9) | Jul 21, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [5a6d4e8ba4](https://linux-hardware.org/?probe=5a6d4e8ba4) | Jul 21, 2022 |
| HP            | 158B                        | Desktop     | [017875f5a5](https://linux-hardware.org/?probe=017875f5a5) | Jul 21, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7b128b9e7a](https://linux-hardware.org/?probe=7b128b9e7a) | Jul 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/openSUSE/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| openSUSE Tumbleweed-XXXXXXXX | 1321      | 64.66%  |
| openSUSE Leap-15.2           | 211       | 10.33%  |
| openSUSE Leap-15.3           | 134       | 6.56%   |
| openSUSE Leap-15.4           | 125       | 6.12%   |
| openSUSE Leap-15.1           | 123       | 6.02%   |
| openSUSE Leap-15.0           | 48        | 2.35%   |
| openSUSE Microos-XXXXXXXX    | 43        | 2.1%    |
| openSUSE Leap-15.5           | 21        | 1.03%   |
| openSUSE 13.2                | 5         | 0.24%   |
| openSUSE Leap-42.2           | 3         | 0.15%   |
| openSUSE                     | 3         | 0.15%   |
| openSUSE Leap-42.3           | 2         | 0.1%    |
| openSUSE 42.3                | 2         | 0.1%    |
| openSUSE Leap-42.1           | 1         | 0.05%   |
| openSUSE 13.1                | 1         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| openSUSE | 1983      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.17.4-1-default             | 49        | 2.05%   |
| 4.12.14-lp151.28.44-default  | 43        | 1.8%    |
| 6.0.8-1-default              | 35        | 1.47%   |
| 5.6.0-1-default              | 31        | 1.3%    |
| 6.2.12-1-default             | 28        | 1.17%   |
| 6.3.2-1-default              | 27        | 1.13%   |
| 6.3.4-1-default              | 26        | 1.09%   |
| 6.0.12-1-default             | 26        | 1.09%   |
| 6.1.8-1-default              | 25        | 1.05%   |
| 6.2.9-1-default              | 24        | 1.01%   |
| 6.1.12-1-default             | 24        | 1.01%   |
| 5.19.2-1-default             | 24        | 1.01%   |
| 5.14.21-150400.22-default    | 24        | 1.01%   |
| 6.0.10-1-default             | 23        | 0.96%   |
| 4.18.15-1-default            | 23        | 0.96%   |
| 5.3.18-lp152.63-default      | 22        | 0.92%   |
| 6.2.1-1-default              | 21        | 0.88%   |
| 6.1.10-1-default             | 21        | 0.88%   |
| 6.3.1-1-default              | 20        | 0.84%   |
| 6.2.6-1-default              | 20        | 0.84%   |
| 5.16.11-1-default            | 20        | 0.84%   |
| 5.14.14-1-default            | 20        | 0.84%   |
| 5.6.2-1-default              | 19        | 0.8%    |
| 5.17.9-1-default             | 19        | 0.8%    |
| 5.17.1-1-default             | 19        | 0.8%    |
| 5.3.18-lp152.57-default      | 18        | 0.75%   |
| 5.3.18-59.37-default         | 18        | 0.75%   |
| 5.11.6-1-default             | 18        | 0.75%   |
| 5.8.4-1-default              | 17        | 0.71%   |
| 5.3.18-lp152.41-default      | 17        | 0.71%   |
| 5.19.8-1-default             | 17        | 0.71%   |
| 5.18.6-1-default             | 17        | 0.71%   |
| 5.14.21-150400.24.46-default | 17        | 0.71%   |
| 5.10.7-1-default             | 17        | 0.71%   |
| 6.2.10-1-default             | 16        | 0.67%   |
| 5.3.18-lp152.36-default      | 16        | 0.67%   |
| 5.14.21-150400.24.21-default | 16        | 0.67%   |
| 6.1.1-1-default              | 15        | 0.63%   |
| 6.0.3-1-default              | 15        | 0.63%   |
| 5.10.16-1-default            | 15        | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3.18  | 314       | 13.61%  |
| 4.12.14 | 158       | 6.85%   |
| 5.14.21 | 141       | 6.11%   |
| 5.17.4  | 49        | 2.12%   |
| 6.0.8   | 35        | 1.52%   |
| 5.6.0   | 33        | 1.43%   |
| 6.3.1   | 30        | 1.3%    |
| 5.14.14 | 30        | 1.3%    |
| 6.2.12  | 28        | 1.21%   |
| 6.3.2   | 27        | 1.17%   |
| 6.0.12  | 27        | 1.17%   |
| 6.3.4   | 26        | 1.13%   |
| 6.2.9   | 25        | 1.08%   |
| 6.1.8   | 25        | 1.08%   |
| 6.1.12  | 24        | 1.04%   |
| 6.0.10  | 24        | 1.04%   |
| 5.19.2  | 24        | 1.04%   |
| 6.1.10  | 23        | 1%      |
| 4.18.15 | 23        | 1%      |
| 6.2.1   | 21        | 0.91%   |
| 5.6.2   | 21        | 0.91%   |
| 6.2.6   | 20        | 0.87%   |
| 5.17.1  | 20        | 0.87%   |
| 5.16.11 | 20        | 0.87%   |
| 5.17.9  | 19        | 0.82%   |
| 5.12.4  | 19        | 0.82%   |
| 5.11.6  | 19        | 0.82%   |
| 5.8.4   | 18        | 0.78%   |
| 5.14.6  | 18        | 0.78%   |
| 5.10.7  | 18        | 0.78%   |
| 5.19.8  | 17        | 0.74%   |
| 5.18.6  | 17        | 0.74%   |
| 6.2.10  | 16        | 0.69%   |
| 6.0.3   | 16        | 0.69%   |
| 6.1.1   | 15        | 0.65%   |
| 5.12.9  | 15        | 0.65%   |
| 5.12.0  | 15        | 0.65%   |
| 5.10.16 | 15        | 0.65%   |
| 5.9.1   | 14        | 0.61%   |
| 5.6.12  | 14        | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3     | 335       | 14.96%  |
| 5.14    | 228       | 10.18%  |
| 4.12    | 158       | 7.05%   |
| 6.0     | 144       | 6.43%   |
| 6.1     | 139       | 6.21%   |
| 6.2     | 129       | 5.76%   |
| 5.17    | 113       | 5.04%   |
| 6.3     | 84        | 3.75%   |
| 5.6     | 82        | 3.66%   |
| 5.16    | 77        | 3.44%   |
| 5.18    | 76        | 3.39%   |
| 5.12    | 72        | 3.21%   |
| 5.8     | 70        | 3.13%   |
| 5.10    | 68        | 3.04%   |
| 5.19    | 67        | 2.99%   |
| 5.11    | 59        | 2.63%   |
| 5.15    | 58        | 2.59%   |
| 5.13    | 49        | 2.19%   |
| 5.9     | 40        | 1.79%   |
| 5.7     | 36        | 1.61%   |
| 5.5     | 34        | 1.52%   |
| 4.18    | 27        | 1.21%   |
| 5.4     | 21        | 0.94%   |
| 5.0     | 14        | 0.63%   |
| 5.2     | 13        | 0.58%   |
| 4.17    | 11        | 0.49%   |
| 4.4     | 9         | 0.4%    |
| 5.1     | 5         | 0.22%   |
| 4.20    | 5         | 0.22%   |
| 4.3     | 4         | 0.18%   |
| 3.16    | 4         | 0.18%   |
| 4.19    | 3         | 0.13%   |
| 4.16    | 2         | 0.09%   |
| 6.4     | 1         | 0.04%   |
| 4.7     | 1         | 0.04%   |
| 4.1     | 1         | 0.04%   |
| 3.12    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1963      | 98.94%  |
| i686    | 14        | 0.71%   |
| aarch64 | 7         | 0.35%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 1120      | 54.47%  |
| GNOME         | 359       | 17.46%  |
| KDE           | 213       | 10.36%  |
| Unknown       | 148       | 7.2%    |
| XFCE          | 103       | 5.01%   |
| MATE          | 22        | 1.07%   |
| X-Cinnamon    | 17        | 0.83%   |
| Cinnamon      | 12        | 0.58%   |
| LXQt          | 10        | 0.49%   |
| KDE4          | 9         | 0.44%   |
| ICEWM         | 7         | 0.34%   |
| LXDE          | 6         | 0.29%   |
| Budgie        | 5         | 0.24%   |
| Deepin        | 4         | 0.19%   |
| sway          | 3         | 0.15%   |
| GNOME Classic | 3         | 0.15%   |
| WindowMaker   | 2         | 0.1%    |
| Pantheon      | 2         | 0.1%    |
| i3            | 2         | 0.1%    |
| awesome       | 2         | 0.1%    |
| Trinity       | 1         | 0.05%   |
| plasma5       | 1         | 0.05%   |
| openbox       | 1         | 0.05%   |
| Herbstluftwm  | 1         | 0.05%   |
| fvwm2         | 1         | 0.05%   |
| default       | 1         | 0.05%   |
| custom        | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1608      | 78.75%  |
| Wayland     | 352       | 17.24%  |
| Tty         | 40        | 1.96%   |
| Unknown     | 40        | 1.96%   |
| Unspecified | 2         | 0.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 830       | 40.71%  |
| LightDM | 594       | 29.13%  |
| SDDM    | 476       | 23.34%  |
| XDM     | 122       | 5.98%   |
| GDM     | 16        | 0.78%   |
| GREETD  | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 724       | 35.46%  |
| de_DE   | 251       | 12.29%  |
| POSIX   | 192       | 9.4%    |
| Unknown | 179       | 8.77%   |
| en_GB   | 136       | 6.66%   |
| pt_BR   | 87        | 4.26%   |
| ru_RU   | 77        | 3.77%   |
| es_ES   | 66        | 3.23%   |
| it_IT   | 46        | 2.25%   |
| fr_FR   | 45        | 2.2%    |
| pl_PL   | 29        | 1.42%   |
| pt_PT   | 20        | 0.98%   |
| nl_NL   | 20        | 0.98%   |
| zh_CN   | 13        | 0.64%   |
| cs_CZ   | 11        | 0.54%   |
| fi_FI   | 9         | 0.44%   |
| hu_HU   | 8         | 0.39%   |
| sv_SE   | 6         | 0.29%   |
| es_MX   | 6         | 0.29%   |
| es_AR   | 6         | 0.29%   |
| en_IN   | 6         | 0.29%   |
| en_IE   | 6         | 0.29%   |
| en_DE   | 6         | 0.29%   |
| C       | 6         | 0.29%   |
| bg_BG   | 5         | 0.24%   |
| tr_TR   | 4         | 0.2%    |
| nn_NO   | 4         | 0.2%    |
| nl_BE   | 4         | 0.2%    |
| nb_NO   | 4         | 0.2%    |
| en_AU   | 4         | 0.2%    |
| ro_RO   | 3         | 0.15%   |
| ja_JP   | 3         | 0.15%   |
| hr_HR   | 3         | 0.15%   |
| en_FI   | 3         | 0.15%   |
| en_CH   | 3         | 0.15%   |
| cv_RU   | 3         | 0.15%   |
| ca_ES   | 3         | 0.15%   |
| sk_SK   | 2         | 0.1%    |
| ru_UA   | 2         | 0.1%    |
| ko_KR   | 2         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1328      | 66.33%  |
| BIOS | 674       | 33.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Btrfs    | 1404      | 69.99%  |
| Ext4     | 429       | 21.39%  |
| Xfs      | 84        | 4.19%   |
| Unknown  | 61        | 3.04%   |
| Overlay  | 18        | 0.9%    |
| Tmpfs    | 3         | 0.15%   |
| Ext3     | 3         | 0.15%   |
| Ext2     | 2         | 0.1%    |
| Reiserfs | 1         | 0.05%   |
| F2fs     | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1092      | 53.98%  |
| Unknown | 757       | 37.42%  |
| MBR     | 174       | 8.6%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1713      | 84.63%  |
| Yes       | 311       | 15.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1481      | 73.54%  |
| Yes       | 533       | 26.46%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 322       | 16.24%  |
| Lenovo                  | 307       | 15.48%  |
| Hewlett-Packard         | 292       | 14.73%  |
| Dell                    | 235       | 11.85%  |
| Gigabyte Technology     | 159       | 8.02%   |
| MSI                     | 146       | 7.36%   |
| ASRock                  | 93        | 4.69%   |
| Acer                    | 87        | 4.39%   |
| Apple                   | 48        | 2.42%   |
| Fujitsu                 | 26        | 1.31%   |
| Toshiba                 | 21        | 1.06%   |
| TUXEDO                  | 18        | 0.91%   |
| HUAWEI                  | 17        | 0.86%   |
| Intel                   | 16        | 0.81%   |
| Sony                    | 13        | 0.66%   |
| Samsung Electronics     | 13        | 0.66%   |
| Supermicro              | 9         | 0.45%   |
| Biostar                 | 9         | 0.45%   |
| Notebook                | 8         | 0.4%    |
| Medion                  | 8         | 0.4%    |
| Fujitsu Siemens         | 7         | 0.35%   |
| Unknown                 | 7         | 0.35%   |
| Pegatron                | 6         | 0.3%    |
| Google                  | 5         | 0.25%   |
| Foxconn                 | 5         | 0.25%   |
| Alienware               | 5         | 0.25%   |
| Raspberry Pi Foundation | 4         | 0.2%    |
| Positivo                | 4         | 0.2%    |
| Microsoft               | 4         | 0.2%    |
| Timi                    | 3         | 0.15%   |
| SLIMBOOK                | 3         | 0.15%   |
| Schenker                | 3         | 0.15%   |
| Razer                   | 3         | 0.15%   |
| LG Electronics          | 3         | 0.15%   |
| Gateway                 | 3         | 0.15%   |
| Clevo                   | 3         | 0.15%   |
| BESSTAR Tech            | 3         | 0.15%   |
| Avell High Performance  | 3         | 0.15%   |
| Wortmann AG             | 2         | 0.1%    |
| TYAN Computer           | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUS All Series                      | 24        | 1.21%   |
| Unknown                              | 13        | 0.66%   |
| Dell OptiPlex 9020                   | 10        | 0.5%    |
| MSI MS-7B86                          | 8         | 0.4%    |
| HP Notebook                          | 8         | 0.4%    |
| MSI MS-7C37                          | 6         | 0.3%    |
| MSI MS-7B89                          | 6         | 0.3%    |
| Gigabyte 970A-DS3P                   | 6         | 0.3%    |
| Dell Precision 5530                  | 6         | 0.3%    |
| ASUS TUF Gaming X570-PLUS            | 6         | 0.3%    |
| ASRock B450M Pro4                    | 6         | 0.3%    |
| Apple MacBookPro9,2                  | 6         | 0.3%    |
| MSI MS-7C02                          | 5         | 0.25%   |
| HP Pavilion dv7                      | 5         | 0.25%   |
| HP Pavilion dv6                      | 5         | 0.25%   |
| HP Laptop 17-ca0xxx                  | 5         | 0.25%   |
| Gigabyte B450M DS3H                  | 5         | 0.25%   |
| Gigabyte B450 AORUS M                | 5         | 0.25%   |
| Dell Latitude 7490                   | 5         | 0.25%   |
| TUXEDO Pulse 15 Gen1                 | 4         | 0.2%    |
| MSI MS-7B79                          | 4         | 0.2%    |
| MSI MS-7A34                          | 4         | 0.2%    |
| Lenovo IdeaPad 5 14ARE05 81YM        | 4         | 0.2%    |
| HP Pavilion g6                       | 4         | 0.2%    |
| HP OMEN Laptop 15-en0xxx             | 4         | 0.2%    |
| HP ENVY x360 2-in-1 Laptop 15-ey0xxx | 4         | 0.2%    |
| Gigabyte X570 AORUS MASTER           | 4         | 0.2%    |
| Dell XPS 15 9560                     | 4         | 0.2%    |
| Dell Latitude E7470                  | 4         | 0.2%    |
| ASUS PRIME B550-PLUS                 | 4         | 0.2%    |
| ASUS PRIME A320M-K                   | 4         | 0.2%    |
| ASUS M5A78L-M/USB3                   | 4         | 0.2%    |
| ASUS CROSSHAIR V FORMULA-Z           | 4         | 0.2%    |
| ASRock X570 Steel Legend             | 4         | 0.2%    |
| Apple Macmini7,1                     | 4         | 0.2%    |
| Acer Swift SF314-43                  | 4         | 0.2%    |
| Samsung 550XDA                       | 3         | 0.15%   |
| MSI MS-7C91                          | 3         | 0.15%   |
| MSI MS-7A38                          | 3         | 0.15%   |
| MSI MS-7A33                          | 3         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 160       | 8.07%   |
| Dell Latitude      | 55        | 2.77%   |
| Dell Inspiron      | 55        | 2.77%   |
| Acer Aspire        | 54        | 2.72%   |
| Lenovo IdeaPad     | 50        | 2.52%   |
| HP Pavilion        | 47        | 2.37%   |
| ASUS PRIME         | 44        | 2.22%   |
| HP EliteBook       | 41        | 2.07%   |
| Dell OptiPlex      | 33        | 1.66%   |
| ASUS ROG           | 33        | 1.66%   |
| ASUS TUF           | 31        | 1.56%   |
| Dell XPS           | 30        | 1.51%   |
| HP Laptop          | 25        | 1.26%   |
| HP ENVY            | 25        | 1.26%   |
| Dell Precision     | 25        | 1.26%   |
| ASUS VivoBook      | 24        | 1.21%   |
| ASUS All           | 24        | 1.21%   |
| HP ProBook         | 22        | 1.11%   |
| Lenovo Yoga        | 21        | 1.06%   |
| Toshiba Satellite  | 19        | 0.96%   |
| HP Compaq          | 19        | 0.96%   |
| HP ZBook           | 18        | 0.91%   |
| Lenovo ThinkCentre | 15        | 0.76%   |
| Fujitsu LIFEBOOK   | 14        | 0.71%   |
| Dell PowerEdge     | 13        | 0.66%   |
| Unknown            | 13        | 0.66%   |
| HP OMEN            | 12        | 0.61%   |
| Gigabyte X570      | 12        | 0.61%   |
| ASUS Zenbook       | 11        | 0.55%   |
| Gigabyte B550      | 10        | 0.5%    |
| Lenovo Legion      | 9         | 0.45%   |
| Dell Vostro        | 9         | 0.45%   |
| ASUS M5A78L-M      | 9         | 0.45%   |
| ASRock B450M       | 9         | 0.45%   |
| Acer Swift         | 9         | 0.45%   |
| MSI MS-7B86        | 8         | 0.4%    |
| HP Notebook        | 8         | 0.4%    |
| Gigabyte B450      | 8         | 0.4%    |
| ASUS ASUS          | 8         | 0.4%    |
| Gigabyte B450M     | 7         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 237       | 11.95%  |
| 2018 | 211       | 10.64%  |
| 2019 | 198       | 9.98%   |
| 2021 | 174       | 8.77%   |
| 2017 | 157       | 7.92%   |
| 2013 | 143       | 7.21%   |
| 2012 | 133       | 6.71%   |
| 2015 | 123       | 6.2%    |
| 2011 | 109       | 5.5%    |
| 2014 | 97        | 4.89%   |
| 2016 | 91        | 4.59%   |
| 2010 | 81        | 4.08%   |
| 2022 | 80        | 4.03%   |
| 2009 | 55        | 2.77%   |
| 2008 | 48        | 2.42%   |
| 2007 | 21        | 1.06%   |
| 2006 | 9         | 0.45%   |
| 2023 | 8         | 0.4%    |
| 2005 | 5         | 0.25%   |
| 2004 | 2         | 0.1%    |
| 2000 | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1013      | 51.08%  |
| Desktop        | 803       | 40.49%  |
| Convertible    | 77        | 3.88%   |
| Mini pc        | 29        | 1.46%   |
| Server         | 26        | 1.31%   |
| All in one     | 20        | 1.01%   |
| Tablet         | 8         | 0.4%    |
| System on chip | 6         | 0.3%    |
| Firewall       | 1         | 0.05%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1705      | 84.7%   |
| Enabled  | 308       | 15.3%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1975      | 99.6%   |
| Yes  | 8         | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 502       | 25.02%  |
| 4.01-8.0        | 430       | 21.44%  |
| 8.01-16.0       | 402       | 20.04%  |
| 32.01-64.0      | 304       | 15.15%  |
| 3.01-4.0        | 174       | 8.67%   |
| 64.01-256.0     | 85        | 4.24%   |
| 24.01-32.0      | 50        | 2.49%   |
| 1.01-2.0        | 27        | 1.35%   |
| 2.01-3.0        | 11        | 0.55%   |
| Unknown         | 10        | 0.5%    |
| 0.51-1.0        | 7         | 0.35%   |
| More than 256.0 | 3         | 0.15%   |
| 0.01-0.5        | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 558       | 25.64%  |
| 4.01-8.0   | 534       | 24.54%  |
| 1.01-2.0   | 453       | 20.82%  |
| 3.01-4.0   | 367       | 16.87%  |
| 8.01-16.0  | 140       | 6.43%   |
| 0.51-1.0   | 72        | 3.31%   |
| 16.01-24.0 | 20        | 0.92%   |
| 0.01-0.5   | 15        | 0.69%   |
| Unknown    | 10        | 0.46%   |
| 24.01-32.0 | 6         | 0.28%   |
| 32.01-64.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1012      | 49.51%  |
| 2       | 556       | 27.2%   |
| 3       | 212       | 10.37%  |
| 4       | 126       | 6.16%   |
| 5       | 67        | 3.28%   |
| 6       | 36        | 1.76%   |
| 7       | 19        | 0.93%   |
| 8       | 4         | 0.2%    |
| 0       | 3         | 0.15%   |
| 13      | 2         | 0.1%    |
| 10      | 2         | 0.1%    |
| 9       | 2         | 0.1%    |
| 35      | 1         | 0.05%   |
| 16      | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1293      | 64.75%  |
| Yes       | 704       | 35.25%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1724      | 86.76%  |
| No        | 263       | 13.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1480      | 74.37%  |
| No        | 510       | 25.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1273      | 63.52%  |
| No        | 731       | 36.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 359       | 18.03%  |
| Germany      | 353       | 17.73%  |
| Brazil       | 123       | 6.18%   |
| Russia       | 92        | 4.62%   |
| Italy        | 80        | 4.02%   |
| France       | 72        | 3.62%   |
| UK           | 71        | 3.57%   |
| Netherlands  | 65        | 3.26%   |
| Spain        | 53        | 2.66%   |
| Switzerland  | 46        | 2.31%   |
| Poland       | 43        | 2.16%   |
| Canada       | 42        | 2.11%   |
| India        | 32        | 1.61%   |
| Sweden       | 31        | 1.56%   |
| Australia    | 29        | 1.46%   |
| Belgium      | 27        | 1.36%   |
| Austria      | 27        | 1.36%   |
| China        | 25        | 1.26%   |
| Czechia      | 24        | 1.21%   |
| Mexico       | 23        | 1.16%   |
| Finland      | 20        | 1%      |
| Hungary      | 19        | 0.95%   |
| Romania      | 18        | 0.9%    |
| Portugal     | 18        | 0.9%    |
| Norway       | 18        | 0.9%    |
| Bulgaria     | 17        | 0.85%   |
| Ukraine      | 16        | 0.8%    |
| Turkey       | 15        | 0.75%   |
| Greece       | 14        | 0.7%    |
| Argentina    | 14        | 0.7%    |
| Serbia       | 12        | 0.6%    |
| Chile        | 10        | 0.5%    |
| Belarus      | 9         | 0.45%   |
| Thailand     | 8         | 0.4%    |
| Peru         | 8         | 0.4%    |
| Japan        | 8         | 0.4%    |
| Indonesia    | 8         | 0.4%    |
| Croatia      | 8         | 0.4%    |
| Luxembourg   | 7         | 0.35%   |
| South Africa | 6         | 0.3%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 30        | 1.43%   |
| Moscow            | 27        | 1.28%   |
| Vienna            | 16        | 0.76%   |
| Sao Paulo         | 16        | 0.76%   |
| Rio de Janeiro    | 16        | 0.76%   |
| Munich            | 15        | 0.71%   |
| Zurich            | 14        | 0.67%   |
| Amsterdam         | 14        | 0.67%   |
| St Petersburg     | 13        | 0.62%   |
| Paris             | 13        | 0.62%   |
| Prague            | 12        | 0.57%   |
| Milan             | 12        | 0.57%   |
| Warsaw            | 11        | 0.52%   |
| Los Angeles       | 11        | 0.52%   |
| Littleton         | 11        | 0.52%   |
| Frankfurt am Main | 11        | 0.52%   |
| Sydney            | 10        | 0.48%   |
| Budapest          | 10        | 0.48%   |
| Sofia             | 9         | 0.43%   |
| Neuchatel         | 9         | 0.43%   |
| Hamburg           | 9         | 0.43%   |
| Rome              | 8         | 0.38%   |
| Riverton          | 8         | 0.38%   |
| Madrid            | 8         | 0.38%   |
| Bengaluru         | 8         | 0.38%   |
| Athens            | 8         | 0.38%   |
| Montreal          | 7         | 0.33%   |
| Melbourne         | 7         | 0.33%   |
| Houston           | 7         | 0.33%   |
| Gothenburg        | 7         | 0.33%   |
| Belgrade          | 7         | 0.33%   |
| Stuttgart         | 6         | 0.29%   |
| Stockholm         | 6         | 0.29%   |
| Schrobenhausen    | 6         | 0.29%   |
| Santiago          | 6         | 0.29%   |
| Halle             | 6         | 0.29%   |
| Essen             | 6         | 0.29%   |
| Cologne           | 6         | 0.29%   |
| Bucharest         | 6         | 0.29%   |
| Barcelona         | 6         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 647       | 1001   | 19.67%  |
| WDC                         | 482       | 824    | 14.65%  |
| Seagate                     | 477       | 841    | 14.5%   |
| Toshiba                     | 208       | 264    | 6.32%   |
| Kingston                    | 181       | 235    | 5.5%    |
| Sandisk                     | 171       | 227    | 5.2%    |
| Crucial                     | 135       | 181    | 4.1%    |
| Intel                       | 93        | 120    | 2.83%   |
| SK hynix                    | 92        | 124    | 2.8%    |
| Unknown                     | 76        | 109    | 2.31%   |
| Hitachi                     | 63        | 76     | 1.92%   |
| HGST                        | 53        | 75     | 1.61%   |
| Micron Technology           | 42        | 53     | 1.28%   |
| A-DATA Technology           | 37        | 49     | 1.12%   |
| PNY                         | 25        | 33     | 0.76%   |
| KIOXIA                      | 25        | 28     | 0.76%   |
| Phison                      | 23        | 33     | 0.7%    |
| Silicon Motion              | 22        | 23     | 0.67%   |
| Intenso                     | 22        | 32     | 0.67%   |
| Phison Electronics          | 21        | 27     | 0.64%   |
| Apple                       | 21        | 26     | 0.64%   |
| China                       | 19        | 21     | 0.58%   |
| SPCC                        | 18        | 23     | 0.55%   |
| Kingston Technology Company | 15        | 15     | 0.46%   |
| Transcend                   | 13        | 14     | 0.4%    |
| LITEON                      | 13        | 14     | 0.4%    |
| Hewlett-Packard             | 13        | 18     | 0.4%    |
| Micron/Crucial Technology   | 12        | 18     | 0.36%   |
| Fujitsu                     | 12        | 15     | 0.36%   |
| Corsair                     | 11        | 12     | 0.33%   |
| OCZ                         | 9         | 14     | 0.27%   |
| Maxtor                      | 9         | 9      | 0.27%   |
| JMicron Technology          | 9         | 9      | 0.27%   |
| GOODRAM                     | 9         | 9      | 0.27%   |
| Patriot                     | 8         | 8      | 0.24%   |
| XPG                         | 7         | 9      | 0.21%   |
| Team                        | 7         | 7      | 0.21%   |
| Realtek Semiconductor       | 6         | 6      | 0.18%   |
| Plextor                     | 6         | 8      | 0.18%   |
| MAXIO Technology (Hangzhou) | 6         | 6      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 47        | 1.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 46        | 1.23%   |
| Samsung SSD 850 EVO 250GB                           | 34        | 0.91%   |
| Samsung SSD 860 EVO 1TB                             | 31        | 0.83%   |
| Seagate ST2000DM008-2FR102 2TB                      | 28        | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 27        | 0.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 26        | 0.69%   |
| Kingston SA400S37480G 480GB SSD                     | 25        | 0.67%   |
| Seagate ST1000LM035-1RK172 1TB                      | 24        | 0.64%   |
| Kingston SA400S37240G 240GB SSD                     | 24        | 0.64%   |
| Crucial CT500MX500SSD1 500GB                        | 21        | 0.56%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 20        | 0.53%   |
| HGST HTS721010A9E630 1TB                            | 20        | 0.53%   |
| Samsung SSD 850 EVO 500GB                           | 19        | 0.51%   |
| Kingston SA400S37120G 120GB SSD                     | 19        | 0.51%   |
| Seagate ST2000DM001-1ER164 2TB                      | 18        | 0.48%   |
| Seagate ST1000DM010-2EP102 1TB                      | 18        | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB                        | 18        | 0.48%   |
| Samsung SSD 840 EVO 250GB                           | 18        | 0.48%   |
| Samsung SSD 860 EVO 250GB                           | 17        | 0.45%   |
| Toshiba MQ04ABF100 1TB                              | 16        | 0.43%   |
| Toshiba MQ01ABD100 1TB                              | 16        | 0.43%   |
| Seagate ST1000DM003-1CH162 1TB                      | 16        | 0.43%   |
| Unknown SD/MMC/MS PRO 64GB                          | 15        | 0.4%    |
| Seagate Expansion 1TB                               | 15        | 0.4%    |
| Samsung SSD 970 EVO 500GB                           | 15        | 0.4%    |
| Crucial CT240BX500SSD1 240GB                        | 15        | 0.4%    |
| Crucial CT1000MX500SSD1 1TB                         | 15        | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 14        | 0.37%   |
| Toshiba DT01ACA100 1TB                              | 14        | 0.37%   |
| Seagate ST500DM002-1BD142 500GB                     | 14        | 0.37%   |
| Samsung SSD 970 EVO Plus 500GB                      | 14        | 0.37%   |
| Samsung SSD 860 QVO 1TB                             | 14        | 0.37%   |
| Samsung NVMe SSD Drive 1TB                          | 14        | 0.37%   |
| Seagate ST3500418AS 500GB                           | 13        | 0.35%   |
| Samsung SSD 850 PRO 256GB                           | 13        | 0.35%   |
| Samsung NVMe SSD Drive 500GB                        | 13        | 0.35%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 13        | 0.35%   |
| Kingston SV300S37A120G 120GB SSD                    | 13        | 0.35%   |
| Toshiba DT01ACA200 2TB                              | 12        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 468       | 816    | 37.2%   |
| WDC                 | 384       | 657    | 30.52%  |
| Toshiba             | 147       | 192    | 11.69%  |
| Samsung Electronics | 69        | 102    | 5.48%   |
| Hitachi             | 63        | 76     | 5.01%   |
| HGST                | 53        | 75     | 4.21%   |
| Unknown             | 16        | 18     | 1.27%   |
| Fujitsu             | 12        | 15     | 0.95%   |
| Maxtor              | 8         | 8      | 0.64%   |
| Apple               | 7         | 9      | 0.56%   |
| Hewlett-Packard     | 5         | 8      | 0.4%    |
| WD MediaMax         | 3         | 3      | 0.24%   |
| Intenso             | 3         | 8      | 0.24%   |
| USB3.0              | 2         | 3      | 0.16%   |
| SSK                 | 2         | 3      | 0.16%   |
| Pioneer             | 2         | 7      | 0.16%   |
| JMicron Technology  | 2         | 2      | 0.16%   |
| USB                 | 1         | 1      | 0.08%   |
| UD0401              | 1         | 1      | 0.08%   |
| Synology            | 1         | 1      | 0.08%   |
| Maxone              | 1         | 1      | 0.08%   |
| MaxDigital          | 1         | 1      | 0.08%   |
| Magnetic Data       | 1         | 2      | 0.08%   |
| Inateck             | 1         | 1      | 0.08%   |
| IBM-207x            | 1         | 8      | 0.08%   |
| HGST HTS            | 1         | 1      | 0.08%   |
| DELLBOSS            | 1         | 1      | 0.08%   |
| ASMT                | 1         | 2      | 0.08%   |
| ASMedia             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 323       | 478    | 28.31%  |
| Kingston            | 137       | 179    | 12.01%  |
| Crucial             | 123       | 164    | 10.78%  |
| SanDisk             | 107       | 132    | 9.38%   |
| WDC                 | 82        | 104    | 7.19%   |
| A-DATA Technology   | 27        | 34     | 2.37%   |
| Intel               | 26        | 37     | 2.28%   |
| Toshiba             | 22        | 26     | 1.93%   |
| SK hynix            | 21        | 32     | 1.84%   |
| PNY                 | 20        | 24     | 1.75%   |
| China               | 19        | 21     | 1.67%   |
| Micron Technology   | 17        | 25     | 1.49%   |
| Intenso             | 17        | 21     | 1.49%   |
| SPCC                | 13        | 18     | 1.14%   |
| LITEON              | 13        | 14     | 1.14%   |
| Apple               | 12        | 15     | 1.05%   |
| Transcend           | 10        | 11     | 0.88%   |
| OCZ                 | 9         | 14     | 0.79%   |
| Patriot             | 8         | 8      | 0.7%    |
| GOODRAM             | 8         | 8      | 0.7%    |
| Corsair             | 7         | 7      | 0.61%   |
| Team                | 6         | 6      | 0.53%   |
| Seagate             | 6         | 7      | 0.53%   |
| LITEONIT            | 6         | 6      | 0.53%   |
| SABRENT             | 5         | 6      | 0.44%   |
| Plextor             | 5         | 7      | 0.44%   |
| JMicron Technology  | 5         | 5      | 0.44%   |
| Hewlett-Packard     | 5         | 7      | 0.44%   |
| XrayDisk            | 4         | 4      | 0.35%   |
| TO Exter            | 4         | 4      | 0.35%   |
| Mushkin             | 4         | 7      | 0.35%   |
| KingSpec            | 4         | 9      | 0.35%   |
| Smartbuy            | 3         | 5      | 0.26%   |
| Netac               | 3         | 3      | 0.26%   |
| Biostar             | 3         | 5      | 0.26%   |
| ASMT                | 3         | 3      | 0.26%   |
| Apacer              | 3         | 6      | 0.26%   |
| Unknown             | 3         | 3      | 0.26%   |
| Smart               | 2         | 2      | 0.18%   |
| S3+                 | 2         | 2      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 993       | 2023   | 34.56%  |
| SSD     | 968       | 1523   | 33.69%  |
| NVMe    | 822       | 1180   | 28.61%  |
| MMC     | 58        | 80     | 2.02%   |
| Unknown | 32        | 41     | 1.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1464      | 3400   | 59.32%  |
| NVMe | 822       | 1179   | 33.31%  |
| SAS  | 124       | 188    | 5.02%   |
| MMC  | 58        | 80     | 2.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1066      | 1745   | 49.86%  |
| 0.51-1.0   | 641       | 1060   | 29.98%  |
| 1.01-2.0   | 240       | 415    | 11.23%  |
| 3.01-4.0   | 76        | 135    | 3.55%   |
| 2.01-3.0   | 64        | 91     | 2.99%   |
| 4.01-10.0  | 41        | 83     | 1.92%   |
| 10.01-20.0 | 10        | 17     | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 638       | 30.81%  |
| 1001-2000      | 448       | 21.63%  |
| 501-1000       | 306       | 14.78%  |
| 2001-3000      | 269       | 12.99%  |
| 251-500        | 192       | 9.27%   |
| 101-250        | 111       | 5.36%   |
| Unknown        | 42        | 2.03%   |
| 51-100         | 32        | 1.55%   |
| 1-20           | 18        | 0.87%   |
| 21-50          | 15        | 0.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 424       | 19.65%  |
| 251-500        | 364       | 16.87%  |
| 51-100         | 317       | 14.69%  |
| 501-1000       | 303       | 14.04%  |
| 1001-2000      | 265       | 12.28%  |
| More than 3000 | 130       | 6.02%   |
| 1-20           | 121       | 5.61%   |
| 2001-3000      | 97        | 4.49%   |
| 21-50          | 94        | 4.36%   |
| Unknown        | 42        | 1.95%   |
| 0              | 1         | 0.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 6         | 8      | 2.26%   |
| Seagate ST3500418AS 500GB             | 5         | 5      | 1.89%   |
| Samsung Electronics SSD 840 EVO 120GB | 5         | 6      | 1.89%   |
| Seagate ST2000DM001-1CH164 2TB        | 4         | 5      | 1.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4         | 4      | 1.51%   |
| HGST HTS725050A7E630 500GB            | 4         | 4      | 1.51%   |
| WDC WD10JFCX-68N6GN0 1TB              | 3         | 4      | 1.13%   |
| Seagate ST2000DM001-1ER164 2TB        | 3         | 3      | 1.13%   |
| Seagate ST1000DM003-1SB102 1TB        | 3         | 4      | 1.13%   |
| Samsung Electronics HD501LJ 500GB     | 3         | 4      | 1.13%   |
| WDC WD6400AAKS-22A7B2 640GB           | 2         | 2      | 0.75%   |
| WDC WD20EZRX-00DC0B0 2TB              | 2         | 3      | 0.75%   |
| WDC WD20EFRX-68EUZN0 2TB              | 2         | 2      | 0.75%   |
| WD MediaMax WL5000GSA12872B 5TB       | 2         | 2      | 0.75%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 0.75%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.75%   |
| Toshiba MK5055GSX 500GB               | 2         | 4      | 0.75%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 0.75%   |
| Seagate ST500LM000-1EJ162 500GB       | 2         | 2      | 0.75%   |
| Seagate ST31000528AS 1TB              | 2         | 5      | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2      | 0.75%   |
| Seagate ST1000DM003-1CH162 1TB        | 2         | 2      | 0.75%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD   | 2         | 2      | 0.75%   |
| Samsung Electronics HN-M500MBB 500GB  | 2         | 2      | 0.75%   |
| Samsung Electronics HD322HJ 320GB     | 2         | 2      | 0.75%   |
| Samsung Electronics HD103SJ 1TB       | 2         | 3      | 0.75%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 3      | 0.75%   |
| Kingston SMS200S3240G 240GB SSD       | 2         | 2      | 0.75%   |
| Kingston SHFS37A120G 120GB SSD        | 2         | 2      | 0.75%   |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 0.75%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 0.75%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 0.75%   |
| Crucial CT1000P1SSD8 1TB              | 2         | 2      | 0.75%   |
| XrayDisk SSD 256GB                    | 1         | 1      | 0.38%   |
| XPG GAMMIX S41 256GB                  | 1         | 1      | 0.38%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.38%   |
| WDC WD800AAJS-75M0A0 80GB             | 1         | 1      | 0.38%   |
| WDC WD7500AAKS-00RBA0 752GB           | 1         | 1      | 0.38%   |
| WDC WD6400BEVT-22A0RT0 640GB          | 1         | 1      | 0.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate                  | 67        | 84     | 26.07%  |
| WDC                      | 46        | 53     | 17.9%   |
| Samsung Electronics      | 32        | 41     | 12.45%  |
| Toshiba                  | 24        | 34     | 9.34%   |
| Hitachi                  | 13        | 15     | 5.06%   |
| Kingston                 | 10        | 14     | 3.89%   |
| Crucial                  | 9         | 10     | 3.5%    |
| Intel                    | 7         | 8      | 2.72%   |
| HGST                     | 7         | 7      | 2.72%   |
| SanDisk                  | 6         | 6      | 2.33%   |
| Maxtor                   | 4         | 4      | 1.56%   |
| WD MediaMax              | 2         | 2      | 0.78%   |
| SK hynix                 | 2         | 2      | 0.78%   |
| Patriot                  | 2         | 2      | 0.78%   |
| OCZ                      | 2         | 2      | 0.78%   |
| LITEONIT                 | 2         | 2      | 0.78%   |
| Fujitsu                  | 2         | 3      | 0.78%   |
| Corsair                  | 2         | 2      | 0.78%   |
| XrayDisk                 | 1         | 1      | 0.39%   |
| XPG                      | 1         | 1      | 0.39%   |
| Transcend                | 1         | 1      | 0.39%   |
| SuperTalent              | 1         | 1      | 0.39%   |
| SSSTC                    | 1         | 1      | 0.39%   |
| SPCC                     | 1         | 1      | 0.39%   |
| Silicon Motion           | 1         | 1      | 0.39%   |
| Phison                   | 1         | 1      | 0.39%   |
| Netac                    | 1         | 1      | 0.39%   |
| Micron Technology        | 1         | 1      | 0.39%   |
| LEQIXIANG                | 1         | 1      | 0.39%   |
| KingFast                 | 1         | 1      | 0.39%   |
| Intenso                  | 1         | 1      | 0.39%   |
| Hewlett-Packard          | 1         | 1      | 0.39%   |
| GOODRAM                  | 1         | 1      | 0.39%   |
| Biwin Storage Technology | 1         | 1      | 0.39%   |
| Apple                    | 1         | 1      | 0.39%   |
| A-DATA Technology        | 1         | 2      | 0.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 67        | 84     | 37.02%  |
| WDC                 | 44        | 51     | 24.31%  |
| Toshiba             | 23        | 33     | 12.71%  |
| Samsung Electronics | 17        | 23     | 9.39%   |
| Hitachi             | 13        | 15     | 7.18%   |
| HGST                | 7         | 7      | 3.87%   |
| Maxtor              | 4         | 4      | 2.21%   |
| WD MediaMax         | 2         | 2      | 1.1%    |
| Fujitsu             | 2         | 3      | 1.1%    |
| Hewlett-Packard     | 1         | 1      | 0.55%   |
| Apple               | 1         | 1      | 0.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 163       | 224    | 68.78%  |
| SSD  | 60        | 72     | 25.32%  |
| NVMe | 14        | 14     | 5.91%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD20EADS-00R6B0 2TB           | 1         | 1      | 33.33%  |
| Samsung Electronics HD502HJ 500GB | 1         | 3      | 33.33%  |
| Hitachi HDS721025CLA382 250GB     | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 3      | 33.33%  |
| Hitachi             | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1171      | 2452   | 52.18%  |
| Detected | 841       | 2080   | 37.48%  |
| Malfunc  | 229       | 310    | 10.2%   |
| Failed   | 3         | 5      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1187      | 43.12%  |
| AMD                              | 536       | 19.47%  |
| Samsung Electronics              | 313       | 11.37%  |
| SanDisk                          | 115       | 4.18%   |
| SK hynix                         | 71        | 2.58%   |
| Kingston Technology Company      | 63        | 2.29%   |
| ASMedia Technology               | 61        | 2.22%   |
| Phison Electronics               | 54        | 1.96%   |
| Toshiba America Info Systems     | 44        | 1.6%    |
| Marvell Technology Group         | 32        | 1.16%   |
| JMicron Technology               | 29        | 1.05%   |
| Silicon Motion                   | 27        | 0.98%   |
| Micron Technology                | 26        | 0.94%   |
| Nvidia                           | 24        | 0.87%   |
| Micron/Crucial Technology        | 24        | 0.87%   |
| KIOXIA                           | 23        | 0.84%   |
| LSI Logic / Symbios Logic        | 17        | 0.62%   |
| ADATA Technology                 | 16        | 0.58%   |
| Broadcom / LSI                   | 13        | 0.47%   |
| Realtek Semiconductor            | 12        | 0.44%   |
| Solid State Storage Technology   | 8         | 0.29%   |
| MAXIO Technology (Hangzhou)      | 7         | 0.25%   |
| Union Memory (Shenzhen)          | 6         | 0.22%   |
| Seagate Technology               | 6         | 0.22%   |
| Silicon Image                    | 5         | 0.18%   |
| Yangtze Memory Technologies      | 4         | 0.15%   |
| VIA Technologies                 | 4         | 0.15%   |
| Adaptec                          | 4         | 0.15%   |
| Shenzhen Longsys Electronics     | 3         | 0.11%   |
| Lite-On Technology               | 3         | 0.11%   |
| Lenovo                           | 3         | 0.11%   |
| Promise Technology               | 2         | 0.07%   |
| Biwin Storage Technology         | 2         | 0.07%   |
| Apple                            | 2         | 0.07%   |
| Tekram Technology                | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Netac Technology                 | 1         | 0.04%   |
| Huawei Technologies              | 1         | 0.04%   |
| Hewlett-Packard                  | 1         | 0.04%   |
| ATTO Technology                  | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 368       | 11.68%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 169       | 5.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 106       | 3.36%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 98        | 3.11%   |
| AMD 400 Series Chipset SATA Controller                                         | 81        | 2.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 73        | 2.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 63        | 2%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 58        | 1.84%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 56        | 1.78%   |
| Intel Volume Management Device NVMe RAID Controller                            | 55        | 1.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 53        | 1.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 52        | 1.65%   |
| AMD 500 Series Chipset SATA Controller                                         | 50        | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 47        | 1.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 44        | 1.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 43        | 1.36%   |
| Samsung NVMe SSD Controller 980                                                | 39        | 1.24%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 39        | 1.24%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 38        | 1.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 38        | 1.21%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 36        | 1.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 36        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 35        | 1.11%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 34        | 1.08%   |
| Intel SSD 660P Series                                                          | 33        | 1.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 32        | 1.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 31        | 0.98%   |
| Phison E12 NVMe Controller                                                     | 30        | 0.95%   |
| AMD 300 Series Chipset SATA Controller                                         | 30        | 0.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 28        | 0.89%   |
| Micron NVMe Storage Controller                                                 | 26        | 0.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 26        | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 26        | 0.82%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 25        | 0.79%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 25        | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                          | 24        | 0.76%   |
| Intel SATA Controller [RAID mode]                                              | 22        | 0.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 20        | 0.63%   |
| JMicron JMB363 SATA/IDE Controller                                             | 18        | 0.57%   |
| Intel Tiger Lake-LP SATA Controller                                            | 18        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1506      | 55.25%  |
| NVMe | 815       | 29.9%   |
| IDE  | 207       | 7.59%   |
| RAID | 173       | 6.35%   |
| SAS  | 13        | 0.48%   |
| SCSI | 12        | 0.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Intel     | 1326      | 66.87%  |
| AMD       | 650       | 32.78%  |
| ARM       | 6         | 0.3%    |
| HISILICON | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 27        | 1.36%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 23        | 1.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 21        | 1.06%   |
| AMD Ryzen 5 3600 6-Core Processor             | 21        | 1.06%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 19        | 0.96%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 0.91%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 18        | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 0.86%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 17        | 0.86%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 17        | 0.86%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 16        | 0.81%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 16        | 0.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 16        | 0.81%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 16        | 0.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 16        | 0.81%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 16        | 0.81%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 16        | 0.81%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 15        | 0.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 0.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 14        | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 13        | 0.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 13        | 0.65%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 13        | 0.65%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 0.65%   |
| AMD FX-8350 Eight-Core Processor              | 13        | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 12        | 0.6%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 12        | 0.6%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 12        | 0.6%    |
| Intel Core i7-4770 CPU @ 3.40GHz              | 11        | 0.55%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 11        | 0.55%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 11        | 0.55%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 11        | 0.55%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 11        | 0.55%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 11        | 0.55%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 11        | 0.55%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 11        | 0.55%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 10        | 0.5%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 10        | 0.5%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 10        | 0.5%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 10        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 420       | 21.16%  |
| Intel Core i5           | 388       | 19.55%  |
| AMD Ryzen 5             | 183       | 9.22%   |
| Other                   | 160       | 8.06%   |
| AMD Ryzen 7             | 149       | 7.51%   |
| Intel Core i3           | 95        | 4.79%   |
| Intel Xeon              | 73        | 3.68%   |
| AMD Ryzen 9             | 57        | 2.87%   |
| Intel Core 2 Duo        | 50        | 2.52%   |
| AMD FX                  | 45        | 2.27%   |
| Intel Celeron           | 42        | 2.12%   |
| Intel Pentium           | 28        | 1.41%   |
| AMD Ryzen 3             | 27        | 1.36%   |
| Intel Core i9           | 18        | 0.91%   |
| AMD Ryzen 7 PRO         | 18        | 0.91%   |
| AMD A10                 | 18        | 0.91%   |
| AMD A8                  | 17        | 0.86%   |
| AMD Phenom II X4        | 16        | 0.81%   |
| Intel Atom              | 14        | 0.71%   |
| Intel Pentium Dual-Core | 12        | 0.6%    |
| Intel Core 2 Quad       | 11        | 0.55%   |
| AMD Athlon              | 11        | 0.55%   |
| AMD A6                  | 11        | 0.55%   |
| Intel Pentium Silver    | 10        | 0.5%    |
| AMD Phenom II X6        | 10        | 0.5%    |
| AMD Ryzen 5 PRO         | 9         | 0.45%   |
| AMD Athlon II X2        | 7         | 0.35%   |
| AMD A4                  | 7         | 0.35%   |
| AMD Ryzen Threadripper  | 6         | 0.3%    |
| Intel Core 2            | 5         | 0.25%   |
| AMD Opteron             | 5         | 0.25%   |
| AMD E2                  | 5         | 0.25%   |
| Intel Genuine           | 3         | 0.15%   |
| AMD Ryzen 3 PRO         | 3         | 0.15%   |
| AMD EPYC                | 3         | 0.15%   |
| AMD E                   | 3         | 0.15%   |
| Intel Xeon Gold         | 2         | 0.1%    |
| Intel Pentium Dual      | 2         | 0.1%    |
| Intel Pentium 4         | 2         | 0.1%    |
| Intel Core m3           | 2         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 731       | 36.77%  |
| 2       | 600       | 30.18%  |
| 6       | 255       | 12.83%  |
| 8       | 224       | 11.27%  |
| 12      | 54        | 2.72%   |
| 16      | 27        | 1.36%   |
| 1       | 27        | 1.36%   |
| 10      | 17        | 0.86%   |
| 3       | 15        | 0.75%   |
| 24      | 10        | 0.5%    |
| 14      | 10        | 0.5%    |
| 32      | 4         | 0.2%    |
| Unknown | 4         | 0.2%    |
| 40      | 3         | 0.15%   |
| 20      | 2         | 0.1%    |
| 64      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |
| 44      | 1         | 0.05%   |
| 36      | 1         | 0.05%   |
| 18      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1945      | 98.03%  |
| 2       | 32        | 1.61%   |
| 4       | 4         | 0.2%    |
| Unknown | 3         | 0.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1505      | 75.74%  |
| 1       | 477       | 24.01%  |
| Unknown | 4         | 0.2%    |
| 8       | 1         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1925      | 96.78%  |
| Unknown        | 55        | 2.77%   |
| 32-bit         | 7         | 0.35%   |
| 64-bit         | 2         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 328       | 16.15%  |
| 0x306c3    | 101       | 4.97%   |
| 0x206a7    | 96        | 4.73%   |
| 0x306a9    | 92        | 4.53%   |
| 0x806c1    | 61        | 3%      |
| 0x906ea    | 58        | 2.86%   |
| 0x506e3    | 58        | 2.86%   |
| 0x406e3    | 48        | 2.36%   |
| 0x806ec    | 46        | 2.26%   |
| 0x08701021 | 46        | 2.26%   |
| 0x0a50000c | 44        | 2.17%   |
| 0x806ea    | 42        | 2.07%   |
| 0x0800820d | 41        | 2.02%   |
| 0x906e9    | 40        | 1.97%   |
| 0x806e9    | 38        | 1.87%   |
| 0x1067a    | 37        | 1.82%   |
| 0x40651    | 35        | 1.72%   |
| 0x08600106 | 35        | 1.72%   |
| 0x08108109 | 34        | 1.67%   |
| 0x06000852 | 33        | 1.62%   |
| 0x306d4    | 31        | 1.53%   |
| 0x010000c8 | 24        | 1.18%   |
| 0x20655    | 21        | 1.03%   |
| 0x08600104 | 19        | 0.94%   |
| 0x08001138 | 19        | 0.94%   |
| 0x08608103 | 18        | 0.89%   |
| 0x08108102 | 18        | 0.89%   |
| 0x906a3    | 17        | 0.84%   |
| 0x08701013 | 17        | 0.84%   |
| 0x06001119 | 17        | 0.84%   |
| 0x0a50000d | 16        | 0.79%   |
| 0x0a201009 | 16        | 0.79%   |
| 0x806eb    | 14        | 0.69%   |
| 0x706a8    | 13        | 0.64%   |
| 0x0810100b | 13        | 0.64%   |
| 0x906ed    | 12        | 0.59%   |
| 0x806d1    | 12        | 0.59%   |
| 0x706e5    | 12        | 0.59%   |
| 0x706a1    | 12        | 0.59%   |
| 0x08001137 | 12        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 312       | 15.71%  |
| Haswell          | 187       | 9.42%   |
| Zen 2            | 138       | 6.95%   |
| Skylake          | 133       | 6.7%    |
| IvyBridge        | 123       | 6.19%   |
| SandyBridge      | 112       | 5.64%   |
| Zen 3            | 107       | 5.39%   |
| Zen+             | 102       | 5.14%   |
| Zen              | 73        | 3.68%   |
| TigerLake        | 73        | 3.68%   |
| Penryn           | 59        | 2.97%   |
| Piledriver       | 55        | 2.77%   |
| Unknown          | 55        | 2.77%   |
| Westmere         | 48        | 2.42%   |
| Alderlake Hybrid | 48        | 2.42%   |
| K10              | 47        | 2.37%   |
| Broadwell        | 40        | 2.01%   |
| CometLake        | 37        | 1.86%   |
| IceLake          | 34        | 1.71%   |
| Core             | 31        | 1.56%   |
| Goldmont plus    | 27        | 1.36%   |
| Nehalem          | 23        | 1.16%   |
| Excavator        | 21        | 1.06%   |
| Steamroller      | 13        | 0.65%   |
| Silvermont       | 13        | 0.65%   |
| Puma             | 10        | 0.5%    |
| Bulldozer        | 9         | 0.45%   |
| Bobcat           | 9         | 0.45%   |
| Jaguar           | 8         | 0.4%    |
| Bonnell          | 8         | 0.4%    |
| Goldmont         | 7         | 0.35%   |
| K8 Hammer        | 6         | 0.3%    |
| K10 Llano        | 6         | 0.3%    |
| Tremont          | 4         | 0.2%    |
| P6               | 3         | 0.15%   |
| K8 & K10 hybrid  | 3         | 0.15%   |
| NetBurst         | 2         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 992       | 42.21%  |
| Nvidia                     | 674       | 28.68%  |
| AMD                        | 662       | 28.17%  |
| Matrox Electronics Systems | 14        | 0.6%    |
| ASPEED Technology          | 5         | 0.21%   |
| S3 Graphics                | 2         | 0.09%   |
| VIA Technologies           | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 74        | 3.04%   |
| AMD Renoir                                                                  | 68        | 2.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 66        | 2.71%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 64        | 2.63%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 63        | 2.59%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 57        | 2.34%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 55        | 2.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 54        | 2.22%   |
| Intel UHD Graphics 620                                                      | 53        | 2.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 47        | 1.93%   |
| Intel HD Graphics 620                                                       | 44        | 1.81%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 44        | 1.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 42        | 1.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 42        | 1.73%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 41        | 1.69%   |
| Intel HD Graphics 530                                                       | 37        | 1.52%   |
| Intel HD Graphics 630                                                       | 32        | 1.32%   |
| Intel Core Processor Integrated Graphics Controller                         | 30        | 1.23%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 27        | 1.11%   |
| Intel HD Graphics 5500                                                      | 26        | 1.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 26        | 1.07%   |
| AMD Lucienne                                                                | 26        | 1.07%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 25        | 1.03%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 24        | 0.99%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 18        | 0.74%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 18        | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 17        | 0.7%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 17        | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 16        | 0.66%   |
| Nvidia GK208B [GeForce GT 710]                                              | 16        | 0.66%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 16        | 0.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 14        | 0.58%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 14        | 0.58%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 13        | 0.53%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 13        | 0.53%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 13        | 0.53%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 12        | 0.49%   |
| Nvidia GK208B [GeForce GT 730]                                              | 12        | 0.49%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 12        | 0.49%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 11        | 0.45%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 679       | 34.09%  |
| 1 x AMD            | 525       | 26.36%  |
| 1 x Nvidia         | 360       | 18.07%  |
| Intel + Nvidia     | 246       | 12.35%  |
| AMD + Nvidia       | 55        | 2.76%   |
| 2 x AMD            | 41        | 2.06%   |
| Intel + AMD        | 41        | 2.06%   |
| 1 x Matrox         | 11        | 0.55%   |
| Other              | 8         | 0.4%    |
| 2 x Nvidia         | 8         | 0.4%    |
| 2 x Intel          | 5         | 0.25%   |
| Nvidia + ASPEED    | 3         | 0.15%   |
| 1 x S3 Graphics    | 2         | 0.1%    |
| Nvidia + Matrox    | 2         | 0.1%    |
| 1 x ASPEED         | 2         | 0.1%    |
| 1 x VIA            | 1         | 0.05%   |
| Intel + 2 x Nvidia | 1         | 0.05%   |
| AMD + 2 x Nvidia   | 1         | 0.05%   |
| AMD + Matrox       | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1591      | 79.19%  |
| Proprietary | 379       | 18.87%  |
| Unknown     | 39        | 1.94%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 944       | 46.53%  |
| 1.01-2.0   | 250       | 12.32%  |
| 0.01-0.5   | 250       | 12.32%  |
| 3.01-4.0   | 175       | 8.62%   |
| 0.51-1.0   | 145       | 7.15%   |
| 7.01-8.0   | 140       | 6.9%    |
| 5.01-6.0   | 52        | 2.56%   |
| 8.01-16.0  | 47        | 2.32%   |
| 2.01-3.0   | 17        | 0.84%   |
| 16.01-24.0 | 7         | 0.34%   |
| 4.01-5.0   | 1         | 0.05%   |
| 24.01-32.0 | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 272       | 11.85%  |
| AU Optronics            | 244       | 10.63%  |
| Chimei Innolux          | 182       | 7.93%   |
| BOE                     | 179       | 7.8%    |
| LG Display              | 177       | 7.71%   |
| Dell                    | 171       | 7.45%   |
| Goldstar                | 129       | 5.62%   |
| Hewlett-Packard         | 95        | 4.14%   |
| Acer                    | 79        | 3.44%   |
| Ancor Communications    | 72        | 3.14%   |
| BenQ                    | 70        | 3.05%   |
| AOC                     | 53        | 2.31%   |
| Philips                 | 50        | 2.18%   |
| Lenovo                  | 49        | 2.13%   |
| Sharp                   | 44        | 1.92%   |
| Apple                   | 40        | 1.74%   |
| ASUSTek Computer        | 27        | 1.18%   |
| Iiyama                  | 25        | 1.09%   |
| PANDA                   | 23        | 1%      |
| InfoVision              | 23        | 1%      |
| ViewSonic               | 20        | 0.87%   |
| Fujitsu Siemens         | 17        | 0.74%   |
| Chi Mei Optoelectronics | 16        | 0.7%    |
| Unknown                 | 15        | 0.65%   |
| Eizo                    | 15        | 0.65%   |
| LG Electronics          | 13        | 0.57%   |
| Vizio                   | 9         | 0.39%   |
| Sony                    | 9         | 0.39%   |
| NEC Computers           | 8         | 0.35%   |
| LG Philips              | 8         | 0.35%   |
| Sceptre Tech            | 7         | 0.3%    |
| Pixio                   | 7         | 0.3%    |
| Panasonic               | 7         | 0.3%    |
| CSO                     | 7         | 0.3%    |
| Medion                  | 6         | 0.26%   |
| TMX                     | 5         | 0.22%   |
| MSI                     | 5         | 0.22%   |
| Insignia                | 5         | 0.22%   |
| Toshiba                 | 4         | 0.17%   |
| HKC                     | 4         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 12        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 11        | 0.46%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 10        | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 9         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 9         | 0.37%   |
| BenQ GW2760HS BNQ78CA 1920x1080 598x336mm 27.0-inch                  | 9         | 0.37%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 9         | 0.37%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 8         | 0.33%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 7         | 0.29%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                    | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 7         | 0.29%   |
| Samsung Electronics U28E590 SAM0C4D 1680x1050 610x350mm 27.7-inch    | 6         | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 6         | 0.25%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 6         | 0.25%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 6         | 0.25%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch               | 6         | 0.25%   |
| Fujitsu Siemens P19-2 FUS0552 1280x1024 376x301mm 19.0-inch          | 6         | 0.25%   |
| Dell U2415 DELA0B8 1920x1200 520x320mm 24.0-inch                     | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch     | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 6         | 0.25%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 6         | 0.25%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 6         | 0.25%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 6         | 0.25%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 6         | 0.25%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 5         | 0.21%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 5         | 0.21%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 5         | 0.21%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 5         | 0.21%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch              | 5         | 0.21%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 5         | 0.21%   |
| Dell U2410 DELF017 1920x1200 518x324mm 24.1-inch                     | 5         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 5         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 5         | 0.21%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 5         | 0.21%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                | 5         | 0.21%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                 | 5         | 0.21%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch       | 5         | 0.21%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 5         | 0.21%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 5         | 0.21%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 4         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1068      | 48.3%   |
| 1366x768 (WXGA)    | 257       | 11.62%  |
| 2560x1440 (QHD)    | 154       | 6.97%   |
| 3840x2160 (4K)     | 146       | 6.6%    |
| 1600x900 (HD+)     | 76        | 3.44%   |
| 1920x1200 (WUXGA)  | 70        | 3.17%   |
| 1280x1024 (SXGA)   | 59        | 2.67%   |
| 1680x1050 (WSXGA+) | 54        | 2.44%   |
| 1440x900 (WXGA+)   | 40        | 1.81%   |
| 1280x800 (WXGA)    | 38        | 1.72%   |
| 2560x1080          | 34        | 1.54%   |
| Unknown            | 29        | 1.31%   |
| 3440x1440          | 27        | 1.22%   |
| 2560x1600          | 20        | 0.9%    |
| 3840x1080          | 17        | 0.77%   |
| 1024x768 (XGA)     | 15        | 0.68%   |
| 2880x1800          | 13        | 0.59%   |
| 1360x768           | 10        | 0.45%   |
| 3200x1800 (QHD+)   | 6         | 0.27%   |
| 2160x1440          | 5         | 0.23%   |
| 1920x540           | 5         | 0.23%   |
| 1600x1200          | 5         | 0.23%   |
| 3840x2400          | 4         | 0.18%   |
| 3840x1600          | 4         | 0.18%   |
| 3840x1200          | 4         | 0.18%   |
| 1024x600           | 4         | 0.18%   |
| 2288x1287          | 3         | 0.14%   |
| 1280x720 (HD)      | 3         | 0.14%   |
| 4480x1440          | 2         | 0.09%   |
| 3456x2160          | 2         | 0.09%   |
| 3200x2000          | 2         | 0.09%   |
| 2520x1680          | 2         | 0.09%   |
| 2240x1400          | 2         | 0.09%   |
| 2048x1536          | 2         | 0.09%   |
| 2048x1152          | 2         | 0.09%   |
| 1400x1050          | 2         | 0.09%   |
| 1280x960           | 2         | 0.09%   |
| 8960x2160          | 1         | 0.05%   |
| 800x1280           | 1         | 0.05%   |
| 7680x1440          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 526       | 22.87%  |
| 27      | 236       | 10.26%  |
| 24      | 194       | 8.43%   |
| 14      | 182       | 7.91%   |
| 13      | 179       | 7.78%   |
| 21      | 152       | 6.61%   |
| 23      | 136       | 5.91%   |
| 17      | 120       | 5.22%   |
| Unknown | 86        | 3.74%   |
| 19      | 59        | 2.57%   |
| 31      | 52        | 2.26%   |
| 34      | 46        | 2%      |
| 12      | 44        | 1.91%   |
| 22      | 36        | 1.57%   |
| 18      | 34        | 1.48%   |
| 20      | 26        | 1.13%   |
| 32      | 20        | 0.87%   |
| 16      | 19        | 0.83%   |
| 84      | 18        | 0.78%   |
| 11      | 15        | 0.65%   |
| 26      | 14        | 0.61%   |
| 25      | 12        | 0.52%   |
| 72      | 10        | 0.43%   |
| 54      | 10        | 0.43%   |
| 29      | 10        | 0.43%   |
| 40      | 8         | 0.35%   |
| 37      | 6         | 0.26%   |
| 42      | 4         | 0.17%   |
| 28      | 4         | 0.17%   |
| 10      | 4         | 0.17%   |
| 142     | 3         | 0.13%   |
| 74      | 3         | 0.13%   |
| 52      | 3         | 0.13%   |
| 49      | 3         | 0.13%   |
| 43      | 3         | 0.13%   |
| 35      | 3         | 0.13%   |
| 60      | 2         | 0.09%   |
| 48      | 2         | 0.09%   |
| 47      | 2         | 0.09%   |
| 38      | 2         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 800       | 35.51%  |
| 501-600        | 525       | 23.3%   |
| 401-500        | 265       | 11.76%  |
| 201-300        | 162       | 7.19%   |
| 351-400        | 160       | 7.1%    |
| 601-700        | 98        | 4.35%   |
| Unknown        | 86        | 3.82%   |
| 701-800        | 67        | 2.97%   |
| 1501-2000      | 32        | 1.42%   |
| 1001-1500      | 26        | 1.15%   |
| 801-900        | 20        | 0.89%   |
| 901-1000       | 6         | 0.27%   |
| More than 2000 | 3         | 0.13%   |
| 101-200        | 2         | 0.09%   |
| 1-100          | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1556      | 76.01%  |
| 16/10   | 245       | 11.97%  |
| Unknown | 70        | 3.42%   |
| 21/9    | 54        | 2.64%   |
| 5/4     | 50        | 2.44%   |
| 4/3     | 34        | 1.66%   |
| 3/2     | 20        | 0.98%   |
| 6/5     | 6         | 0.29%   |
| 32/9    | 4         | 0.2%    |
| 2.65    | 4         | 0.2%    |
| 1.00    | 3         | 0.15%   |
| 3.20    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 526       | 23.09%  |
| 201-250        | 403       | 17.69%  |
| 81-90          | 283       | 12.42%  |
| 301-350        | 244       | 10.71%  |
| 351-500        | 132       | 5.79%   |
| 151-200        | 131       | 5.75%   |
| 121-130        | 92        | 4.04%   |
| Unknown        | 86        | 3.78%   |
| 251-300        | 84        | 3.69%   |
| 71-80          | 81        | 3.56%   |
| More than 1000 | 55        | 2.41%   |
| 61-70          | 39        | 1.71%   |
| 141-150        | 39        | 1.71%   |
| 501-1000       | 28        | 1.23%   |
| 51-60          | 15        | 0.66%   |
| 111-120        | 15        | 0.66%   |
| 131-140        | 13        | 0.57%   |
| 41-50          | 5         | 0.22%   |
| 91-100         | 5         | 0.22%   |
| 1-40           | 2         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 737       | 33.45%  |
| 121-160       | 609       | 27.64%  |
| 101-120       | 525       | 23.83%  |
| 161-240       | 150       | 6.81%   |
| Unknown       | 86        | 3.9%    |
| More than 240 | 57        | 2.59%   |
| 1-50          | 39        | 1.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1530      | 75.07%  |
| 2     | 407       | 19.97%  |
| 0     | 53        | 2.6%    |
| 3     | 44        | 2.16%   |
| 4     | 4         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1088      | 36.67%  |
| Intel                             | 1041      | 35.09%  |
| Qualcomm Atheros                  | 260       | 8.76%   |
| Broadcom                          | 157       | 5.29%   |
| MediaTek                          | 53        | 1.79%   |
| Broadcom Limited                  | 31        | 1.04%   |
| Ralink Technology                 | 30        | 1.01%   |
| TP-Link                           | 26        | 0.88%   |
| Ralink                            | 22        | 0.74%   |
| ASIX Electronics                  | 22        | 0.74%   |
| Nvidia                            | 20        | 0.67%   |
| Marvell Technology Group          | 19        | 0.64%   |
| Sierra Wireless                   | 13        | 0.44%   |
| DisplayLink                       | 10        | 0.34%   |
| Samsung Electronics               | 9         | 0.3%    |
| Dell                              | 9         | 0.3%    |
| D-Link                            | 9         | 0.3%    |
| NetGear                           | 8         | 0.27%   |
| Lenovo                            | 8         | 0.27%   |
| Edimax Technology                 | 8         | 0.27%   |
| Huawei Technologies               | 6         | 0.2%    |
| Hewlett-Packard                   | 6         | 0.2%    |
| Aquantia                          | 6         | 0.2%    |
| Microsoft                         | 5         | 0.17%   |
| Ericsson Business Mobile Networks | 5         | 0.17%   |
| D-Link System                     | 5         | 0.17%   |
| Xiaomi                            | 4         | 0.13%   |
| Qualcomm Atheros Communications   | 4         | 0.13%   |
| Linksys                           | 4         | 0.13%   |
| Cypress Semiconductor             | 4         | 0.13%   |
| Belkin Components                 | 4         | 0.13%   |
| ASUSTek Computer                  | 4         | 0.13%   |
| U-Blox                            | 3         | 0.1%    |
| Motorola PCS                      | 3         | 0.1%    |
| Microchip Technology              | 3         | 0.1%    |
| JMicron Technology                | 3         | 0.1%    |
| ICS Advent                        | 3         | 0.1%    |
| AVM                               | 3         | 0.1%    |
| VIA Technologies                  | 2         | 0.07%   |
| Texas Instruments                 | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 795       | 22.49%  |
| Intel Wi-Fi 6 AX200                                               | 138       | 3.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 74        | 2.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 73        | 2.07%   |
| Intel Wireless 8265 / 8275                                        | 69        | 1.95%   |
| Intel I211 Gigabit Network Connection                             | 68        | 1.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 67        | 1.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 57        | 1.61%   |
| Intel Wi-Fi 6 AX201                                               | 56        | 1.58%   |
| Realtek RTL8125 2.5GbE Controller                                 | 52        | 1.47%   |
| Intel Wireless 8260                                               | 52        | 1.47%   |
| Intel Wireless 7260                                               | 48        | 1.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 47        | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 40        | 1.13%   |
| Intel Wireless 7265                                               | 39        | 1.1%    |
| Intel Wireless-AC 9260                                            | 37        | 1.05%   |
| Intel Ethernet Connection (2) I219-V                              | 35        | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 33        | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 33        | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 31        | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 30        | 0.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 30        | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 27        | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 25        | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 25        | 0.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 25        | 0.71%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 25        | 0.71%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 25        | 0.71%   |
| Intel Ethernet Connection I217-V                                  | 22        | 0.62%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 22        | 0.62%   |
| Intel Ethernet Controller I225-V                                  | 21        | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                     | 20        | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 19        | 0.54%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 19        | 0.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 19        | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 18        | 0.51%   |
| Intel I210 Gigabit Network Connection                             | 18        | 0.51%   |
| Intel Ethernet Connection I219-LM                                 | 18        | 0.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 18        | 0.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 16        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 789       | 50.74%  |
| Realtek Semiconductor                 | 242       | 15.56%  |
| Qualcomm Atheros                      | 203       | 13.05%  |
| Broadcom                              | 102       | 6.56%   |
| MediaTek                              | 48        | 3.09%   |
| Ralink Technology                     | 30        | 1.93%   |
| Ralink                                | 22        | 1.41%   |
| TP-Link                               | 18        | 1.16%   |
| Broadcom Limited                      | 17        | 1.09%   |
| Sierra Wireless                       | 13        | 0.84%   |
| D-Link                                | 9         | 0.58%   |
| NetGear                               | 8         | 0.51%   |
| Edimax Technology                     | 8         | 0.51%   |
| Dell                                  | 6         | 0.39%   |
| Qualcomm Atheros Communications       | 4         | 0.26%   |
| Microsoft                             | 4         | 0.26%   |
| Linksys                               | 4         | 0.26%   |
| Belkin Components                     | 4         | 0.26%   |
| ASUSTek Computer                      | 4         | 0.26%   |
| D-Link System                         | 3         | 0.19%   |
| AVM                                   | 3         | 0.19%   |
| Qualcomm                              | 2         | 0.13%   |
| Marvell Technology Group              | 2         | 0.13%   |
| ZyXEL Communications                  | 1         | 0.06%   |
| Xiaomi                                | 1         | 0.06%   |
| Wacom                                 | 1         | 0.06%   |
| Samsung Electronics                   | 1         | 0.06%   |
| Realtek                               | 1         | 0.06%   |
| Intersil                              | 1         | 0.06%   |
| IMC Networks                          | 1         | 0.06%   |
| Hewlett-Packard                       | 1         | 0.06%   |
| BUFFALO                               | 1         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 138       | 8.79%   |
| Intel Wireless 8265 / 8275                                     | 69        | 4.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 57        | 3.63%   |
| Intel Wi-Fi 6 AX201                                            | 56        | 3.57%   |
| Intel Wireless 8260                                            | 52        | 3.31%   |
| Intel Wireless 7260                                            | 48        | 3.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 47        | 2.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 40        | 2.55%   |
| Intel Wireless 7265                                            | 39        | 2.48%   |
| Intel Wireless-AC 9260                                         | 37        | 2.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 33        | 2.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 31        | 1.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 30        | 1.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 30        | 1.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 25        | 1.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 25        | 1.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 25        | 1.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 25        | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 25        | 1.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 22        | 1.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 19        | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 19        | 1.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 19        | 1.21%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 18        | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 18        | 1.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 16        | 1.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 16        | 1.02%   |
| Intel Wireless 3160                                            | 15        | 0.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 15        | 0.96%   |
| Intel Centrino Ultimate-N 6300                                 | 15        | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 0.89%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 13        | 0.83%   |
| Intel Centrino Advanced-N 6235                                 | 13        | 0.83%   |
| Ralink MT7601U Wireless Adapter                                | 12        | 0.76%   |
| Intel Wireless 3165                                            | 12        | 0.76%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 11        | 0.7%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 11        | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 10        | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 10        | 0.64%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 10        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 994       | 52.87%  |
| Intel                                  | 565       | 30.05%  |
| Qualcomm Atheros                       | 78        | 4.15%   |
| Broadcom                               | 78        | 4.15%   |
| ASIX Electronics                       | 22        | 1.17%   |
| Nvidia                                 | 20        | 1.06%   |
| Marvell Technology Group               | 17        | 0.9%    |
| Broadcom Limited                       | 14        | 0.74%   |
| DisplayLink                            | 10        | 0.53%   |
| TP-Link                                | 8         | 0.43%   |
| Lenovo                                 | 8         | 0.43%   |
| Samsung Electronics                    | 6         | 0.32%   |
| Aquantia                               | 6         | 0.32%   |
| MediaTek                               | 5         | 0.27%   |
| Huawei Technologies                    | 5         | 0.27%   |
| Cypress Semiconductor                  | 4         | 0.21%   |
| Xiaomi                                 | 3         | 0.16%   |
| Motorola PCS                           | 3         | 0.16%   |
| JMicron Technology                     | 3         | 0.16%   |
| ICS Advent                             | 3         | 0.16%   |
| VIA Technologies                       | 2         | 0.11%   |
| NetXen Incorporated                    | 2         | 0.11%   |
| HMD Global                             | 2         | 0.11%   |
| Dell                                   | 2         | 0.11%   |
| D-Link System                          | 2         | 0.11%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Solarflare Communications              | 1         | 0.05%   |
| Sitecom Europe                         | 1         | 0.05%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.05%   |
| National Semiconductor                 | 1         | 0.05%   |
| MosChip Semiconductor                  | 1         | 0.05%   |
| Microsoft                              | 1         | 0.05%   |
| Microchip Technology                   | 1         | 0.05%   |
| IBM                                    | 1         | 0.05%   |
| Hewlett-Packard                        | 1         | 0.05%   |
| Google                                 | 1         | 0.05%   |
| Foxconn / Hon Hai                      | 1         | 0.05%   |
| Emulex                                 | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 795       | 41.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 74        | 3.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 73        | 3.79%   |
| Intel I211 Gigabit Network Connection                             | 68        | 3.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 67        | 3.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 52        | 2.7%    |
| Intel Ethernet Connection (2) I219-V                              | 35        | 1.82%   |
| Intel Ethernet Connection I217-LM                                 | 33        | 1.71%   |
| Intel Ethernet Connection (4) I219-LM                             | 27        | 1.4%    |
| Intel Ethernet Connection I217-V                                  | 22        | 1.14%   |
| Intel Ethernet Controller I225-V                                  | 21        | 1.09%   |
| ASIX AX88179 Gigabit Ethernet                                     | 20        | 1.04%   |
| Intel I210 Gigabit Network Connection                             | 18        | 0.93%   |
| Intel Ethernet Connection I219-LM                                 | 18        | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                             | 16        | 0.83%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 15        | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 14        | 0.73%   |
| Intel Ethernet Connection (7) I219-V                              | 14        | 0.73%   |
| Intel Ethernet Connection (2) I218-V                              | 14        | 0.73%   |
| Intel 82574L Gigabit Network Connection                           | 14        | 0.73%   |
| Intel Ethernet Connection I219-V                                  | 13        | 0.67%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.67%   |
| Intel 82579V Gigabit Network Connection                           | 13        | 0.67%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.67%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 0.62%   |
| Intel Ethernet Connection (7) I219-LM                             | 12        | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 0.57%   |
| Intel Ethernet Connection (10) I219-V                             | 9         | 0.47%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 9         | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8         | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 8         | 0.42%   |
| Nvidia MCP79 Ethernet                                             | 8         | 0.42%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 8         | 0.42%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 7         | 0.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 0.36%   |
| Intel Ethernet Connection (11) I219-V                             | 7         | 0.36%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 7         | 0.36%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.31%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 6         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1722      | 53.23%  |
| WiFi     | 1477      | 45.66%  |
| Modem    | 26        | 0.8%    |
| Unknown  | 10        | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1102      | 51.96%  |
| Ethernet | 1018      | 48%     |
| Unknown  | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1078      | 54.23%  |
| 1     | 796       | 40.04%  |
| 3     | 68        | 3.42%   |
| 0     | 23        | 1.16%   |
| 4     | 17        | 0.86%   |
| 5     | 4         | 0.2%    |
| 8     | 1         | 0.05%   |
| 6     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1616      | 79.72%  |
| Yes  | 411       | 20.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 652       | 50.66%  |
| Realtek Semiconductor           | 125       | 9.71%   |
| Cambridge Silicon Radio         | 98        | 7.61%   |
| Qualcomm Atheros Communications | 81        | 6.29%   |
| Broadcom                        | 56        | 4.35%   |
| Lite-On Technology              | 49        | 3.81%   |
| IMC Networks                    | 49        | 3.81%   |
| Apple                           | 48        | 3.73%   |
| Foxconn / Hon Hai               | 33        | 2.56%   |
| ASUSTek Computer                | 23        | 1.79%   |
| Hewlett-Packard                 | 11        | 0.85%   |
| Dell                            | 10        | 0.78%   |
| Realtek                         | 9         | 0.7%    |
| MediaTek                        | 9         | 0.7%    |
| Toshiba                         | 6         | 0.47%   |
| Belkin Components               | 3         | 0.23%   |
| TP-Link                         | 2         | 0.16%   |
| Taiyo Yuden                     | 2         | 0.16%   |
| Smart Modular Technologies      | 2         | 0.16%   |
| Ralink                          | 2         | 0.16%   |
| Marvell Semiconductor           | 2         | 0.16%   |
| HTC (High Tech Computer)        | 2         | 0.16%   |
| Foxconn International           | 2         | 0.16%   |
| Alps Electric                   | 2         | 0.16%   |
| USI                             | 1         | 0.08%   |
| Unknown                         | 1         | 0.08%   |
| SINO WEALTH                     | 1         | 0.08%   |
| Ralink Technology               | 1         | 0.08%   |
| Qcom                            | 1         | 0.08%   |
| Mobile Action Technology        | 1         | 0.08%   |
| Kensington                      | 1         | 0.08%   |
| Integrated System Solution      | 1         | 0.08%   |
| Edimax Technology               | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 213       | 16.51%  |
| Intel AX200 Bluetooth                               | 130       | 10.08%  |
| Intel AX201 Bluetooth                               | 106       | 8.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 98        | 7.6%    |
| Realtek Bluetooth Radio                             | 80        | 6.2%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 68        | 5.27%   |
| Qualcomm Atheros  Bluetooth Device                  | 40        | 3.1%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 36        | 2.79%   |
| Realtek  Bluetooth 4.2 Adapter                      | 32        | 2.48%   |
| Intel Bluetooth Device                              | 31        | 2.4%    |
| Apple Bluetooth Host Controller                     | 30        | 2.33%   |
| Intel Wireless-AC 3168 Bluetooth                    | 28        | 2.17%   |
| Intel AX210 Bluetooth                               | 23        | 1.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 19        | 1.47%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 19        | 1.47%   |
| IMC Networks Bluetooth Radio                        | 18        | 1.4%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 1.24%   |
| IMC Networks Wireless_Device                        | 14        | 1.09%   |
| Broadcom BCM2045B (BDC-2.1)                         | 13        | 1.01%   |
| IMC Networks Bluetooth Device                       | 11        | 0.85%   |
| Realtek Bluetooth Radio                             | 9         | 0.7%    |
| MediaTek Wireless_Device                            | 9         | 0.7%    |
| Lite-On Wireless_Device                             | 9         | 0.7%    |
| Lite-On Bluetooth Device                            | 9         | 0.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 9         | 0.7%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 0.62%   |
| Apple Bluetooth USB Host Controller                 | 8         | 0.62%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 0.54%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.54%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 0.54%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 0.54%   |
| ASUS ASUS USB-BT500                                 | 7         | 0.54%   |
| Realtek RTL8821A Bluetooth                          | 6         | 0.47%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.47%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 6         | 0.47%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 6         | 0.47%   |
| Broadcom BCM43142A0 Bluetooth Device                | 5         | 0.39%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.31%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 0.31%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1267      | 44.88%  |
| AMD                        | 730       | 25.86%  |
| Nvidia                     | 439       | 15.55%  |
| C-Media Electronics        | 55        | 1.95%   |
| Logitech                   | 30        | 1.06%   |
| Creative Labs              | 28        | 0.99%   |
| Texas Instruments          | 21        | 0.74%   |
| Realtek Semiconductor      | 14        | 0.5%    |
| Creative Technology        | 11        | 0.39%   |
| Razer USA                  | 10        | 0.35%   |
| Lenovo                     | 10        | 0.35%   |
| Kingston Technology        | 10        | 0.35%   |
| JMTek                      | 10        | 0.35%   |
| Generalplus Technology     | 10        | 0.35%   |
| GN Netcom                  | 9         | 0.32%   |
| M-Audio                    | 8         | 0.28%   |
| ASUSTek Computer           | 8         | 0.28%   |
| Plantronics                | 7         | 0.25%   |
| SteelSeries ApS            | 6         | 0.21%   |
| RODE Microphones           | 6         | 0.21%   |
| Focusrite-Novation         | 6         | 0.21%   |
| Corsair                    | 6         | 0.21%   |
| BEHRINGER International    | 6         | 0.21%   |
| Yamaha                     | 5         | 0.18%   |
| Hewlett-Packard            | 5         | 0.18%   |
| DSEA A/S                   | 5         | 0.18%   |
| VIA Technologies           | 4         | 0.14%   |
| Samson Technologies        | 4         | 0.14%   |
| Guangzhou FiiO Electronics | 4         | 0.14%   |
| Sennheiser Communications  | 3         | 0.11%   |
| SAVITECH                   | 3         | 0.11%   |
| Micro Star International   | 3         | 0.11%   |
| Dell                       | 3         | 0.11%   |
| Apple                      | 3         | 0.11%   |
| ZOOM                       | 2         | 0.07%   |
| Tenx Technology            | 2         | 0.07%   |
| Solid State Logic          | 2         | 0.07%   |
| No brand                   | 2         | 0.07%   |
| Microsoft                  | 2         | 0.07%   |
| Huawei Technologies        | 2         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 254       | 7.28%   |
| Intel Sunrise Point-LP HD Audio                                            | 159       | 4.56%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 143       | 4.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 115       | 3.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 111       | 3.18%   |
| AMD Starship/Matisse HD Audio Controller                                   | 105       | 3.01%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 99        | 2.84%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 89        | 2.55%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 84        | 2.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 78        | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 77        | 2.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 77        | 2.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 73        | 2.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 70        | 2.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 66        | 1.89%   |
| AMD FCH Azalia Controller                                                  | 54        | 1.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 52        | 1.49%   |
| Intel 8 Series HD Audio Controller                                         | 44        | 1.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 43        | 1.23%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 43        | 1.23%   |
| Intel 200 Series PCH HD Audio                                              | 37        | 1.06%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 37        | 1.06%   |
| AMD Navi 10 HDMI Audio                                                     | 35        | 1%      |
| Intel Broadwell-U Audio Controller                                         | 34        | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                            | 33        | 0.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 33        | 0.95%   |
| Nvidia GP104 High Definition Audio Controller                              | 32        | 0.92%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 31        | 0.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 29        | 0.83%   |
| Intel Comet Lake PCH-LP cAVS                                               | 28        | 0.8%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 28        | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 27        | 0.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 27        | 0.77%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 27        | 0.77%   |
| Nvidia TU116 High Definition Audio Controller                              | 26        | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 26        | 0.74%   |
| AMD Kabini HDMI/DP Audio                                                   | 26        | 0.74%   |
| Intel Comet Lake PCH cAVS                                                  | 25        | 0.72%   |
| Intel CM238 HD Audio Controller                                            | 23        | 0.66%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 21        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 340       | 22.16%  |
| SK hynix                                | 255       | 16.62%  |
| Kingston                                | 184       | 11.99%  |
| Micron Technology                       | 157       | 10.23%  |
| Unknown                                 | 120       | 7.82%   |
| Crucial                                 | 106       | 6.91%   |
| Corsair                                 | 99        | 6.45%   |
| G.Skill                                 | 82        | 5.35%   |
| A-DATA Technology                       | 23        | 1.5%    |
| Ramaxel Technology                      | 19        | 1.24%   |
| Elpida                                  | 16        | 1.04%   |
| Patriot                                 | 15        | 0.98%   |
| Unknown (ABCD)                          | 14        | 0.91%   |
| Team                                    | 13        | 0.85%   |
| Nanya Technology                        | 11        | 0.72%   |
| Smart                                   | 9         | 0.59%   |
| Unknown                                 | 8         | 0.52%   |
| Transcend                               | 7         | 0.46%   |
| Avant                                   | 7         | 0.46%   |
| GOODRAM                                 | 6         | 0.39%   |
| AMD                                     | 4         | 0.26%   |
| Teikon                                  | 2         | 0.13%   |
| Qimonda                                 | 2         | 0.13%   |
| Lexar                                   | 2         | 0.13%   |
| Kingmax                                 | 2         | 0.13%   |
| Exceleram                               | 2         | 0.13%   |
| ChangXin Memory                         | 2         | 0.13%   |
| ASint Technology                        | 2         | 0.13%   |
| Apacer                                  | 2         | 0.13%   |
| Unknown (0x02BA)                        | 1         | 0.07%   |
| Unknown (07FB)                          | 1         | 0.07%   |
| Unknown (000004B30000)                  | 1         | 0.07%   |
| Unifosa                                 | 1         | 0.07%   |
| Toshiba                                 | 1         | 0.07%   |
| TakeMS                                  | 1         | 0.07%   |
| Super Talent                            | 1         | 0.07%   |
| Smart Modular                           | 1         | 0.07%   |
| Smart Brazil                            | 1         | 0.07%   |
| Silicon Power Computer & Communications | 1         | 0.07%   |
| Silicon Power                           | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 16        | 0.98%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 16        | 0.98%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 14        | 0.86%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 12        | 0.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.74%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 10        | 0.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 10        | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 9         | 0.55%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 0.55%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 9         | 0.55%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.55%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 9         | 0.55%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 8         | 0.49%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.49%   |
| Unknown                                                          | 8         | 0.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.43%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 7         | 0.43%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.43%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 7         | 0.43%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.43%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.43%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 7         | 0.43%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s           | 7         | 0.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.37%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 6         | 0.37%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.37%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.37%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.37%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 6         | 0.37%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.37%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 6         | 0.37%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.37%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s             | 6         | 0.37%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 6         | 0.37%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 5         | 0.31%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 5         | 0.31%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 5         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 687       | 52.64%  |
| DDR3    | 391       | 29.96%  |
| LPDDR4  | 52        | 3.98%   |
| DDR2    | 42        | 3.22%   |
| Unknown | 40        | 3.07%   |
| LPDDR3  | 33        | 2.53%   |
| SDRAM   | 22        | 1.69%   |
| DDR5    | 18        | 1.38%   |
| LPDDR5  | 10        | 0.77%   |
| DDR     | 8         | 0.61%   |
| DRAM    | 2         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 709       | 53.96%  |
| DIMM         | 497       | 37.82%  |
| Row Of Chips | 90        | 6.85%   |
| Chip         | 13        | 0.99%   |
| RIMM         | 2         | 0.15%   |
| FB-DIMM      | 2         | 0.15%   |
| Unknown      | 1         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 591       | 41.24%  |
| 4096  | 378       | 26.38%  |
| 16384 | 244       | 17.03%  |
| 2048  | 123       | 8.58%   |
| 32768 | 58        | 4.05%   |
| 1024  | 36        | 2.51%   |
| 512   | 2         | 0.14%   |
| 128   | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 260       | 18.21%  |
| 3200    | 227       | 15.9%   |
| 2667    | 219       | 15.34%  |
| 2400    | 110       | 7.7%    |
| 1333    | 103       | 7.21%   |
| 2133    | 88        | 6.16%   |
| 3600    | 45        | 3.15%   |
| 1334    | 38        | 2.66%   |
| 1867    | 25        | 1.75%   |
| 800     | 25        | 1.75%   |
| 667     | 23        | 1.61%   |
| 4267    | 19        | 1.33%   |
| 3266    | 17        | 1.19%   |
| 3400    | 15        | 1.05%   |
| 4800    | 13        | 0.91%   |
| Unknown | 13        | 0.91%   |
| 1067    | 12        | 0.84%   |
| 1066    | 12        | 0.84%   |
| 3800    | 11        | 0.77%   |
| 2666    | 11        | 0.77%   |
| 6400    | 10        | 0.7%    |
| 3000    | 10        | 0.7%    |
| 4266    | 9         | 0.63%   |
| 3533    | 9         | 0.63%   |
| 1866    | 9         | 0.63%   |
| 2933    | 8         | 0.56%   |
| 8400    | 7         | 0.49%   |
| 2048    | 7         | 0.49%   |
| 3733    | 6         | 0.42%   |
| 2800    | 6         | 0.42%   |
| 3666    | 5         | 0.35%   |
| 975     | 5         | 0.35%   |
| 5600    | 4         | 0.28%   |
| 4199    | 4         | 0.28%   |
| 3866    | 4         | 0.28%   |
| 3466    | 4         | 0.28%   |
| 1800    | 4         | 0.28%   |
| 533     | 4         | 0.28%   |
| 3933    | 3         | 0.21%   |
| 333     | 3         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 27        | 42.19%  |
| Samsung Electronics | 10        | 15.63%  |
| Brother Industries  | 9         | 14.06%  |
| Seiko Epson         | 8         | 12.5%   |
| Canon               | 5         | 7.81%   |
| Prolific Technology | 2         | 3.13%   |
| Star Micronics      | 1         | 1.56%   |
| Pantum              | 1         | 1.56%   |
| Kyocera             | 1         | 1.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                      | 2         | 2.99%   |
| Samsung M267x 287x Series                       | 2         | 2.99%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 2         | 2.99%   |
| Prolific PL2305 Parallel Port                   | 2         | 2.99%   |
| HP Officejet 4500 G510g-m                       | 2         | 2.99%   |
| HP LaserJet 1320                                | 2         | 2.99%   |
| HP ENVY 4520 series                             | 2         | 2.99%   |
| HP Color LaserJet CP1215                        | 2         | 2.99%   |
| Brother Printer                                 | 2         | 2.99%   |
| Star Micronics TSP100ECO/TSP100II               | 1         | 1.49%   |
| Seiko Epson XP-4200 Series                      | 1         | 1.49%   |
| Seiko Epson XP-243 245 247 Series               | 1         | 1.49%   |
| Seiko Epson XP-230 Series                       | 1         | 1.49%   |
| Seiko Epson WF-2510 Series                      | 1         | 1.49%   |
| Seiko Epson L1300 Series                        | 1         | 1.49%   |
| Seiko Epson ET-3840 Series                      | 1         | 1.49%   |
| Seiko Epson ET-2720 Series                      | 1         | 1.49%   |
| Samsung SCX-4200 series                         | 1         | 1.49%   |
| Samsung SCX-3400 Series                         | 1         | 1.49%   |
| Samsung Phaser 3121                             | 1         | 1.49%   |
| Samsung ML-191x/ML-252x Laser Printer           | 1         | 1.49%   |
| Samsung ML-1865                                 | 1         | 1.49%   |
| Samsung M2020 Series                            | 1         | 1.49%   |
| Pantum P2500W-series                            | 1         | 1.49%   |
| Kyocera FS-1030D printer                        | 1         | 1.49%   |
| HP Smart Tank Plus 550 series                   | 1         | 1.49%   |
| HP Smart Install                                | 1         | 1.49%   |
| HP Officejet Pro 6230                           | 1         | 1.49%   |
| HP Officejet 7110 series                        | 1         | 1.49%   |
| HP OfficeJet 5200 series                        | 1         | 1.49%   |
| HP Officejet 4620 series                        | 1         | 1.49%   |
| HP OfficeJet 3830 series                        | 1         | 1.49%   |
| HP LaserJet Professional P 1102w                | 1         | 1.49%   |
| HP LaserJet P1102                               | 1         | 1.49%   |
| HP LaserJet CM1415fn                            | 1         | 1.49%   |
| HP LaserJet 1020                                | 1         | 1.49%   |
| HP LaserJet 1018                                | 1         | 1.49%   |
| HP ENVY 4500 series                             | 1         | 1.49%   |
| HP Deskjet Ink Advant K209a-z                   | 1         | 1.49%   |
| HP DeskJet 6940 series                          | 1         | 1.49%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 9         | 42.86%  |
| Seiko Epson     | 6         | 28.57%  |
| Hewlett-Packard | 3         | 14.29%  |
| AGFA-Gevaert NV | 2         | 9.52%   |
| Mustek Systems  | 1         | 4.76%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                       | 4         | 19.05%  |
| Canon CanoScan N670U/N676U/LiDE 20                            | 2         | 9.52%   |
| Canon CanoScan LiDE 110                                       | 2         | 9.52%   |
| Seiko Epson Scanner                                           | 1         | 4.76%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]              | 1         | 4.76%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 1         | 4.76%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 1         | 4.76%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]           | 1         | 4.76%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 4.76%   |
| Mustek Systems ScanExpress A3 USB                             | 1         | 4.76%   |
| HP Scanjet G2710                                              | 1         | 4.76%   |
| HP ScanJet 5300c/5370c                                        | 1         | 4.76%   |
| HP ScanJet 3970c                                              | 1         | 4.76%   |
| Canon CanoScan N1240U/LiDE 30                                 | 1         | 4.76%   |
| AGFA-Gevaert NV SnapScan e20                                  | 1         | 4.76%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 1         | 4.76%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 272       | 22.78%  |
| IMC Networks                           | 119       | 9.97%   |
| Microdia                               | 106       | 8.88%   |
| Logitech                               | 104       | 8.71%   |
| Realtek Semiconductor                  | 85        | 7.12%   |
| Sunplus Innovation Technology          | 64        | 5.36%   |
| Quanta                                 | 63        | 5.28%   |
| Bison Electronics                      | 59        | 4.94%   |
| Cheng Uei Precision Industry (Foxlink) | 37        | 3.1%    |
| Acer                                   | 37        | 3.1%    |
| Apple                                  | 35        | 2.93%   |
| Luxvisions Innotech Limited            | 28        | 2.35%   |
| Syntek                                 | 26        | 2.18%   |
| Lite-On Technology                     | 25        | 2.09%   |
| Suyin                                  | 18        | 1.51%   |
| Microsoft                              | 12        | 1.01%   |
| Silicon Motion                         | 9         | 0.75%   |
| Alcor Micro                            | 8         | 0.67%   |
| Lenovo                                 | 7         | 0.59%   |
| Generalplus Technology                 | 6         | 0.5%    |
| Samsung Electronics                    | 5         | 0.42%   |
| Z-Star Microelectronics                | 4         | 0.34%   |
| Sonix Technology                       | 4         | 0.34%   |
| Ricoh                                  | 4         | 0.34%   |
| Primax Electronics                     | 4         | 0.34%   |
| Hewlett-Packard                        | 3         | 0.25%   |
| ARC International                      | 3         | 0.25%   |
| Y Media                                | 2         | 0.17%   |
| webcam                                 | 2         | 0.17%   |
| Trust                                  | 2         | 0.17%   |
| Tobii Technology AB                    | 2         | 0.17%   |
| SunplusIT                              | 2         | 0.17%   |
| LG Electronics                         | 2         | 0.17%   |
| Cubeternet                             | 2         | 0.17%   |
| Creative Technology                    | 2         | 0.17%   |
| Arkmicro Technologies                  | 2         | 0.17%   |
| ALi                                    | 2         | 0.17%   |
| vivo                                   | 1         | 0.08%   |
| USB Camera CS                          | 1         | 0.08%   |
| Unknown                                | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 66        | 5.48%   |
| IMC Networks Integrated Camera                       | 44        | 3.65%   |
| Microdia Integrated_Webcam_HD                        | 43        | 3.57%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 36        | 2.99%   |
| Realtek Integrated_Webcam_HD                         | 32        | 2.66%   |
| Logitech Webcam C270                                 | 32        | 2.66%   |
| Chicony HD WebCam                                    | 27        | 2.24%   |
| Bison Integrated Camera                              | 22        | 1.83%   |
| Sunplus Integrated_Webcam_HD                         | 19        | 1.58%   |
| Chicony HP HD Camera                                 | 17        | 1.41%   |
| Syntek Integrated Camera                             | 15        | 1.25%   |
| Apple Built-in iSight                                | 13        | 1.08%   |
| Quanta HP HD Camera                                  | 12        | 1%      |
| Logitech HD Pro Webcam C920                          | 12        | 1%      |
| IMC Networks USB2.0 VGA UVC WebCam                   | 10        | 0.83%   |
| Chicony USB2.0 Camera                                | 10        | 0.83%   |
| Chicony Integrated Camera (1280x720@30)              | 10        | 0.83%   |
| Acer HD Webcam                                       | 10        | 0.83%   |
| Realtek USB Camera                                   | 9         | 0.75%   |
| Realtek Integrated Webcam HD                         | 9         | 0.75%   |
| Quanta HD User Facing                                | 9         | 0.75%   |
| Microdia USB 2.0 Camera                              | 9         | 0.75%   |
| Lite-On Integrated Camera                            | 9         | 0.75%   |
| Chicony HP HD Webcam                                 | 9         | 0.75%   |
| Apple FaceTime HD Camera                             | 9         | 0.75%   |
| Quanta VGA WebCam                                    | 8         | 0.66%   |
| Microdia CameraA                                     | 8         | 0.66%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 8         | 0.66%   |
| Logitech HD Webcam C615                              | 8         | 0.66%   |
| Chicony HD User Facing                               | 8         | 0.66%   |
| Chicony FJ Camera                                    | 8         | 0.66%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 8         | 0.66%   |
| Acer Integrated Camera                               | 8         | 0.66%   |
| Sunplus HD WebCam                                    | 7         | 0.58%   |
| Microdia Integrated Webcam                           | 7         | 0.58%   |
| Luxvisions Innotech Limited HP HD Camera             | 7         | 0.58%   |
| Chicony USB 2.0 Camera                               | 7         | 0.58%   |
| Logitech HD Webcam C525                              | 6         | 0.5%    |
| Logitech C922 Pro Stream Webcam                      | 6         | 0.5%    |
| Chicony TOSHIBA Web Camera - HD                      | 6         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 93        | 38.75%  |
| Synaptics                  | 86        | 35.83%  |
| Shenzhen Goodix Technology | 29        | 12.08%  |
| Upek                       | 11        | 4.58%   |
| AuthenTec                  | 9         | 3.75%   |
| Elan Microelectronics      | 8         | 3.33%   |
| LighTuning Technology      | 2         | 0.83%   |
| STMicroelectronics         | 1         | 0.42%   |
| Samsung Electronics        | 1         | 0.42%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 25        | 10.42%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 23        | 9.58%   |
| Shenzhen Goodix  FingerPrint Device                                        | 19        | 7.92%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 5.42%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 5%      |
| Validity Sensors Synaptics WBDI                                            | 11        | 4.58%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 4.58%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 4.17%   |
| Synaptics UWP WBDI                                                         | 9         | 3.75%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 3.75%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 2.92%   |
| Synaptics WBDI                                                             | 7         | 2.92%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 2.92%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 2.5%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 2.08%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 2.08%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.08%   |
| Validity Sensors VFS491                                                    | 4         | 1.67%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 1.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.67%   |
| Synaptics  WBDI                                                            | 4         | 1.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.67%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.67%   |
| Synaptics WBDI Device                                                      | 3         | 1.25%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 1.25%   |
| Unknown                                                                    | 3         | 1.25%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.83%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.83%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.83%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.83%   |
| Elan ELAN:Fingerprint                                                      | 2         | 0.83%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.83%   |
| AuthenTec AES1600                                                          | 2         | 0.83%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.42%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.42%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.42%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.42%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.42%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.42%   |
| Samsung Fingerprint Device                                                 | 1         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 39        | 40.21%  |
| Broadcom                   | 35        | 36.08%  |
| Gemalto (was Gemplus)      | 6         | 6.19%   |
| Upek                       | 4         | 4.12%   |
| O2 Micro                   | 3         | 3.09%   |
| Hewlett-Packard            | 3         | 3.09%   |
| Lenovo                     | 2         | 2.06%   |
| Yubico.com                 | 1         | 1.03%   |
| Watchdata                  | 1         | 1.03%   |
| Clay Logic                 | 1         | 1.03%   |
| Castles Technology         | 1         | 1.03%   |
| Athena Smartcard Solutions | 1         | 1.03%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 37        | 38.14%  |
| Broadcom 5880                                                                | 13        | 13.4%   |
| Broadcom 58200                                                               | 11        | 11.34%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 7.22%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 5.15%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 4.12%   |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 4.12%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 3.09%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 3         | 3.09%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 2.06%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.03%   |
| Watchdata USB Key                                                            | 1         | 1.03%   |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 1.03%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 1.03%   |
| Castles Technology EZCCID Smart Card Reader                                  | 1         | 1.03%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 1.03%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 1.03%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 1.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1429      | 69.61%  |
| 1     | 495       | 24.11%  |
| 2     | 108       | 5.26%   |
| 3     | 17        | 0.83%   |
| 4     | 3         | 0.15%   |
| 5     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 238       | 32.25%  |
| Graphics card            | 157       | 21.27%  |
| Chipcard                 | 87        | 11.79%  |
| Net/wireless             | 77        | 10.43%  |
| Multimedia controller    | 46        | 6.23%   |
| Sound                    | 28        | 3.79%   |
| Unassigned class         | 22        | 2.98%   |
| Camera                   | 22        | 2.98%   |
| Communication controller | 17        | 2.3%    |
| Card reader              | 12        | 1.63%   |
| Storage                  | 8         | 1.08%   |
| Bluetooth                | 7         | 0.95%   |
| Network                  | 5         | 0.68%   |
| Net/ethernet             | 4         | 0.54%   |
| Firewire controller      | 4         | 0.54%   |
| Modem                    | 2         | 0.27%   |
| Storage/raid             | 1         | 0.14%   |
| Flash memory             | 1         | 0.14%   |

