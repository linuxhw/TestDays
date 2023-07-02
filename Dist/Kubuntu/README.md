Kubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Kubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu/Desktop/README.md) and [notebooks](/Dist/Kubuntu/Notebook/README.md).

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

Total: 5521

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [cb6f37ea2b](https://linux-hardware.org/?probe=cb6f37ea2b) | Jul 01, 2023 |
| Dell          | G3 3779                     | Notebook    | [a6c5553133](https://linux-hardware.org/?probe=a6c5553133) | Jun 30, 2023 |
| Dell          | Latitude E5450              | Notebook    | [e0826ab83a](https://linux-hardware.org/?probe=e0826ab83a) | Jun 30, 2023 |
| Schenker      | XMG PRO (E23)               | Notebook    | [c70da63bd9](https://linux-hardware.org/?probe=c70da63bd9) | Jun 30, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [581282a150](https://linux-hardware.org/?probe=581282a150) | Jun 29, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [171e61b165](https://linux-hardware.org/?probe=171e61b165) | Jun 29, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [bbd13c14eb](https://linux-hardware.org/?probe=bbd13c14eb) | Jun 29, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [802b3686d4](https://linux-hardware.org/?probe=802b3686d4) | Jun 28, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0081fa215e](https://linux-hardware.org/?probe=0081fa215e) | Jun 28, 2023 |
| Huanan        | Unknown                     | Desktop     | [397d33202e](https://linux-hardware.org/?probe=397d33202e) | Jun 28, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [7dd7d8e8ea](https://linux-hardware.org/?probe=7dd7d8e8ea) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [c0c2f3ba48](https://linux-hardware.org/?probe=c0c2f3ba48) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [75cbcde6b8](https://linux-hardware.org/?probe=75cbcde6b8) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [9619e6fb09](https://linux-hardware.org/?probe=9619e6fb09) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [abf9b9909f](https://linux-hardware.org/?probe=abf9b9909f) | Jun 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [1726bb80ec](https://linux-hardware.org/?probe=1726bb80ec) | Jun 27, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7a5a27ddd7](https://linux-hardware.org/?probe=7a5a27ddd7) | Jun 27, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [42e304c777](https://linux-hardware.org/?probe=42e304c777) | Jun 26, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [77d2d3d01b](https://linux-hardware.org/?probe=77d2d3d01b) | Jun 26, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [16c312b7be](https://linux-hardware.org/?probe=16c312b7be) | Jun 26, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e5c848cc49](https://linux-hardware.org/?probe=e5c848cc49) | Jun 25, 2023 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [bd98bbb8c0](https://linux-hardware.org/?probe=bd98bbb8c0) | Jun 25, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [589dd91af9](https://linux-hardware.org/?probe=589dd91af9) | Jun 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [aab1616d0e](https://linux-hardware.org/?probe=aab1616d0e) | Jun 25, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [1c4e016f20](https://linux-hardware.org/?probe=1c4e016f20) | Jun 25, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [f043aedf3c](https://linux-hardware.org/?probe=f043aedf3c) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Google        | Kohaku                      | Notebook    | [f9c3a3efb6](https://linux-hardware.org/?probe=f9c3a3efb6) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [852dad5b6a](https://linux-hardware.org/?probe=852dad5b6a) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bf18f8c7dc](https://linux-hardware.org/?probe=bf18f8c7dc) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [ed127d8c21](https://linux-hardware.org/?probe=ed127d8c21) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [e4f7f39784](https://linux-hardware.org/?probe=e4f7f39784) | Jun 23, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [e5efed1ac5](https://linux-hardware.org/?probe=e5efed1ac5) | Jun 23, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [aa50925a16](https://linux-hardware.org/?probe=aa50925a16) | Jun 23, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [f224dfda17](https://linux-hardware.org/?probe=f224dfda17) | Jun 22, 2023 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [dda587b759](https://linux-hardware.org/?probe=dda587b759) | Jun 22, 2023 |
| Dell          | G3 3590                     | Notebook    | [14ab83043b](https://linux-hardware.org/?probe=14ab83043b) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | Notebook    | [c5f46a6955](https://linux-hardware.org/?probe=c5f46a6955) | Jun 21, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [3dffeb35fa](https://linux-hardware.org/?probe=3dffeb35fa) | Jun 20, 2023 |
| HP            | Notebook                    | Notebook    | [db641e216c](https://linux-hardware.org/?probe=db641e216c) | Jun 20, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [29e7fc8e13](https://linux-hardware.org/?probe=29e7fc8e13) | Jun 20, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [233b6c3412](https://linux-hardware.org/?probe=233b6c3412) | Jun 20, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [fa33088329](https://linux-hardware.org/?probe=fa33088329) | Jun 20, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [37292d4c84](https://linux-hardware.org/?probe=37292d4c84) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [7d00ddf4fc](https://linux-hardware.org/?probe=7d00ddf4fc) | Jun 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [bfa769b311](https://linux-hardware.org/?probe=bfa769b311) | Jun 20, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7cb19a32ac](https://linux-hardware.org/?probe=7cb19a32ac) | Jun 20, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | Notebook    | [9e06717237](https://linux-hardware.org/?probe=9e06717237) | Jun 19, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [5daecd88f5](https://linux-hardware.org/?probe=5daecd88f5) | Jun 19, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [260297ab72](https://linux-hardware.org/?probe=260297ab72) | Jun 19, 2023 |
| XFX           | MI-9300-7AS9                | Desktop     | [e2c3a51177](https://linux-hardware.org/?probe=e2c3a51177) | Jun 18, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [ce819ae3d3](https://linux-hardware.org/?probe=ce819ae3d3) | Jun 18, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [83d17fd3bd](https://linux-hardware.org/?probe=83d17fd3bd) | Jun 17, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [739c466bf0](https://linux-hardware.org/?probe=739c466bf0) | Jun 17, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [587c48c954](https://linux-hardware.org/?probe=587c48c954) | Jun 17, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [945376fe33](https://linux-hardware.org/?probe=945376fe33) | Jun 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [6ecfbb88a0](https://linux-hardware.org/?probe=6ecfbb88a0) | Jun 16, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [e2e55f5267](https://linux-hardware.org/?probe=e2e55f5267) | Jun 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b8d24f1cc8](https://linux-hardware.org/?probe=b8d24f1cc8) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [e0a00a71de](https://linux-hardware.org/?probe=e0a00a71de) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [76433ab03f](https://linux-hardware.org/?probe=76433ab03f) | Jun 15, 2023 |
| HP            | 86F0 11000                  | All in one  | [45026f50ef](https://linux-hardware.org/?probe=45026f50ef) | Jun 15, 2023 |
| HP            | 86F0 11000                  | All in one  | [f074cca59a](https://linux-hardware.org/?probe=f074cca59a) | Jun 15, 2023 |
| Dell          | Latitude 3310               | Notebook    | [40aa328d98](https://linux-hardware.org/?probe=40aa328d98) | Jun 15, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [39d273ec86](https://linux-hardware.org/?probe=39d273ec86) | Jun 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [f7049b2256](https://linux-hardware.org/?probe=f7049b2256) | Jun 15, 2023 |
| Proline       | V1165C4                     | Notebook    | [89f6135da3](https://linux-hardware.org/?probe=89f6135da3) | Jun 14, 2023 |
| Dell          | Latitude E6420              | Notebook    | [f05e0e10e5](https://linux-hardware.org/?probe=f05e0e10e5) | Jun 14, 2023 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | Desktop     | [01f33d2c9b](https://linux-hardware.org/?probe=01f33d2c9b) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [b1eabf98f6](https://linux-hardware.org/?probe=b1eabf98f6) | Jun 14, 2023 |
| Lenovo        | ThinkPad T440p 20AN009CU... | Notebook    | [54fd87b596](https://linux-hardware.org/?probe=54fd87b596) | Jun 14, 2023 |
| Irbis         | NB123                       | Notebook    | [f6dae4c3c4](https://linux-hardware.org/?probe=f6dae4c3c4) | Jun 14, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [a0cdda9a4d](https://linux-hardware.org/?probe=a0cdda9a4d) | Jun 14, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Gigabyte      | C246-WU4-CF                 | Desktop     | [8babb9b5f1](https://linux-hardware.org/?probe=8babb9b5f1) | Jun 13, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [0ec1b06d0c](https://linux-hardware.org/?probe=0ec1b06d0c) | Jun 13, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [7f974cd282](https://linux-hardware.org/?probe=7f974cd282) | Jun 12, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [787fa3215e](https://linux-hardware.org/?probe=787fa3215e) | Jun 12, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [679fb4f6ab](https://linux-hardware.org/?probe=679fb4f6ab) | Jun 11, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [36f0bbcb6d](https://linux-hardware.org/?probe=36f0bbcb6d) | Jun 11, 2023 |
| Lenovo        | 312A SDK0R32862 WIN 3258... | Desktop     | [1e8ab337a5](https://linux-hardware.org/?probe=1e8ab337a5) | Jun 11, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [b599a55609](https://linux-hardware.org/?probe=b599a55609) | Jun 10, 2023 |
| Dell          | G3 3779                     | Notebook    | [0190c87b35](https://linux-hardware.org/?probe=0190c87b35) | Jun 10, 2023 |
| Lenovo        | ThinkPad T570 20H9000UUS    | Notebook    | [606989ab70](https://linux-hardware.org/?probe=606989ab70) | Jun 10, 2023 |
| Seco          | C40 C                       | Desktop     | [4d990c8a0c](https://linux-hardware.org/?probe=4d990c8a0c) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [53ba4689ae](https://linux-hardware.org/?probe=53ba4689ae) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [58f4272bee](https://linux-hardware.org/?probe=58f4272bee) | Jun 10, 2023 |
| Dell          | XPS 13 9333                 | Notebook    | [88020aee75](https://linux-hardware.org/?probe=88020aee75) | Jun 09, 2023 |
| Supermicro    | C7H61                       | Desktop     | [7eef5b7873](https://linux-hardware.org/?probe=7eef5b7873) | Jun 08, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [e8b6d763e4](https://linux-hardware.org/?probe=e8b6d763e4) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S5... | Notebook    | [0372aa0747](https://linux-hardware.org/?probe=0372aa0747) | Jun 08, 2023 |
| HP            | Notebook                    | Notebook    | [1b099710b7](https://linux-hardware.org/?probe=1b099710b7) | Jun 08, 2023 |
| HP            | Notebook                    | Notebook    | [9bf82397c3](https://linux-hardware.org/?probe=9bf82397c3) | Jun 08, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [610c9c318f](https://linux-hardware.org/?probe=610c9c318f) | Jun 08, 2023 |
| PC Special... | Initia Ii 15                | Notebook    | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [6b694e4b4a](https://linux-hardware.org/?probe=6b694e4b4a) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [0b7fb76a0b](https://linux-hardware.org/?probe=0b7fb76a0b) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [810e331444](https://linux-hardware.org/?probe=810e331444) | Jun 07, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [c22850601d](https://linux-hardware.org/?probe=c22850601d) | Jun 07, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [f02195de51](https://linux-hardware.org/?probe=f02195de51) | Jun 07, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [cb8797fce5](https://linux-hardware.org/?probe=cb8797fce5) | Jun 07, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [646e1db08d](https://linux-hardware.org/?probe=646e1db08d) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [53341e2d0d](https://linux-hardware.org/?probe=53341e2d0d) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| MSI           | 2AE0                        | Desktop     | [15b3c478d3](https://linux-hardware.org/?probe=15b3c478d3) | Jun 06, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [b06a0c9b89](https://linux-hardware.org/?probe=b06a0c9b89) | Jun 06, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [1b78246ef7](https://linux-hardware.org/?probe=1b78246ef7) | Jun 06, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [776a9fb064](https://linux-hardware.org/?probe=776a9fb064) | Jun 05, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e9fd3f392](https://linux-hardware.org/?probe=5e9fd3f392) | Jun 05, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| Biostar       | B350GT3                     | Desktop     | [b425f8d45a](https://linux-hardware.org/?probe=b425f8d45a) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [9636642e65](https://linux-hardware.org/?probe=9636642e65) | Jun 04, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [8ef447b2f3](https://linux-hardware.org/?probe=8ef447b2f3) | Jun 03, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [fc8a306ca0](https://linux-hardware.org/?probe=fc8a306ca0) | Jun 03, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [b7a585d1f1](https://linux-hardware.org/?probe=b7a585d1f1) | Jun 03, 2023 |
| Dell          | Latitude E6500              | Notebook    | [4053ff5676](https://linux-hardware.org/?probe=4053ff5676) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [767241151a](https://linux-hardware.org/?probe=767241151a) | Jun 03, 2023 |
| Lenovo        | ThinkPad T460 20FN004BMN    | Notebook    | [dafbbaeb0f](https://linux-hardware.org/?probe=dafbbaeb0f) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [6ae18b11ab](https://linux-hardware.org/?probe=6ae18b11ab) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [05a99cf128](https://linux-hardware.org/?probe=05a99cf128) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [963b30ca7f](https://linux-hardware.org/?probe=963b30ca7f) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [23e94c534e](https://linux-hardware.org/?probe=23e94c534e) | Jun 01, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [906dbab25c](https://linux-hardware.org/?probe=906dbab25c) | Jun 01, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [7baed02e0e](https://linux-hardware.org/?probe=7baed02e0e) | Jun 01, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [16c536cda1](https://linux-hardware.org/?probe=16c536cda1) | Jun 01, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [d936c663d3](https://linux-hardware.org/?probe=d936c663d3) | Jun 01, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [8720e6163e](https://linux-hardware.org/?probe=8720e6163e) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [fc4e2630c0](https://linux-hardware.org/?probe=fc4e2630c0) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [f02c7845e5](https://linux-hardware.org/?probe=f02c7845e5) | Jun 01, 2023 |
| MSI           | GF63 Thin 11SC              | Notebook    | [8f8afcc010](https://linux-hardware.org/?probe=8f8afcc010) | Jun 01, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [0586d2c0e2](https://linux-hardware.org/?probe=0586d2c0e2) | Jun 01, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ebd7782079](https://linux-hardware.org/?probe=ebd7782079) | May 31, 2023 |
| ASUSTek       | P5Q                         | Desktop     | [e936e44332](https://linux-hardware.org/?probe=e936e44332) | May 31, 2023 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [2723d218b7](https://linux-hardware.org/?probe=2723d218b7) | May 31, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [c677ff5b2d](https://linux-hardware.org/?probe=c677ff5b2d) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [bd1740c7b2](https://linux-hardware.org/?probe=bd1740c7b2) | May 31, 2023 |
| AZW           | GTR V02                     | Desktop     | [cab90f1838](https://linux-hardware.org/?probe=cab90f1838) | May 31, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [2ac99b8909](https://linux-hardware.org/?probe=2ac99b8909) | May 30, 2023 |
| Dell          | G15 5525                    | Notebook    | [f7e5d0ae57](https://linux-hardware.org/?probe=f7e5d0ae57) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [4f23de2827](https://linux-hardware.org/?probe=4f23de2827) | May 30, 2023 |
| MSI           | Titan GT77HX 13VH           | Notebook    | [7c3b8ed81d](https://linux-hardware.org/?probe=7c3b8ed81d) | May 29, 2023 |
| Packard Be... | MCP73                       | Desktop     | [e180017a10](https://linux-hardware.org/?probe=e180017a10) | May 29, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [bca463af6d](https://linux-hardware.org/?probe=bca463af6d) | May 28, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [cdc924595c](https://linux-hardware.org/?probe=cdc924595c) | May 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [70714d71f5](https://linux-hardware.org/?probe=70714d71f5) | May 28, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [e429db5b0b](https://linux-hardware.org/?probe=e429db5b0b) | May 27, 2023 |
| Dell          | Precision 5530              | Notebook    | [cb116bdfd2](https://linux-hardware.org/?probe=cb116bdfd2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [2b9c4431c2](https://linux-hardware.org/?probe=2b9c4431c2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [f5b571be32](https://linux-hardware.org/?probe=f5b571be32) | May 26, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [a8fd95ce79](https://linux-hardware.org/?probe=a8fd95ce79) | May 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [1c62418caf](https://linux-hardware.org/?probe=1c62418caf) | May 25, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [0d6c86d757](https://linux-hardware.org/?probe=0d6c86d757) | May 25, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [3e1fb6f93b](https://linux-hardware.org/?probe=3e1fb6f93b) | May 25, 2023 |
| Google        | Bluebird                    | Notebook    | [5b41bdf767](https://linux-hardware.org/?probe=5b41bdf767) | May 25, 2023 |
| Acer          | Aspire M3920                | Desktop     | [5e61c22a26](https://linux-hardware.org/?probe=5e61c22a26) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [174a3139c4](https://linux-hardware.org/?probe=174a3139c4) | May 24, 2023 |
| Dell          | Inspiron 14 5401            | Notebook    | [16d8b1c945](https://linux-hardware.org/?probe=16d8b1c945) | May 24, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [9568d26302](https://linux-hardware.org/?probe=9568d26302) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [3eb016e8c7](https://linux-hardware.org/?probe=3eb016e8c7) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3d4cdd163c](https://linux-hardware.org/?probe=3d4cdd163c) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c3251b8c63](https://linux-hardware.org/?probe=c3251b8c63) | May 23, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [27819563b9](https://linux-hardware.org/?probe=27819563b9) | May 23, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [7f3dae82d3](https://linux-hardware.org/?probe=7f3dae82d3) | May 23, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [185b65bf34](https://linux-hardware.org/?probe=185b65bf34) | May 22, 2023 |
| Packard Be... | MCP73                       | Desktop     | [1203dc5301](https://linux-hardware.org/?probe=1203dc5301) | May 22, 2023 |
| COM1          | NBINF-X5-9G5                | Notebook    | [8d8c13c10c](https://linux-hardware.org/?probe=8d8c13c10c) | May 22, 2023 |
| ASRock        | X99 Extreme6/ac             | Desktop     | [8e255dc13b](https://linux-hardware.org/?probe=8e255dc13b) | May 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [434372d228](https://linux-hardware.org/?probe=434372d228) | May 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [1c178d1658](https://linux-hardware.org/?probe=1c178d1658) | May 21, 2023 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [a8d8e219a2](https://linux-hardware.org/?probe=a8d8e219a2) | May 21, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [80c62a0473](https://linux-hardware.org/?probe=80c62a0473) | May 21, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [7c09c55150](https://linux-hardware.org/?probe=7c09c55150) | May 21, 2023 |
| HP            | 350 G1                      | Notebook    | [7629c78328](https://linux-hardware.org/?probe=7629c78328) | May 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [71ac41efb8](https://linux-hardware.org/?probe=71ac41efb8) | May 20, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [610c8c1a42](https://linux-hardware.org/?probe=610c8c1a42) | May 19, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [1e7af790ed](https://linux-hardware.org/?probe=1e7af790ed) | May 19, 2023 |
| BOSGAME       | B95                         | Notebook    | [3d1805a2eb](https://linux-hardware.org/?probe=3d1805a2eb) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| Acer          | Aspire E5-521               | Notebook    | [05227be8bc](https://linux-hardware.org/?probe=05227be8bc) | May 18, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [61b0585530](https://linux-hardware.org/?probe=61b0585530) | May 18, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [166ec29ce0](https://linux-hardware.org/?probe=166ec29ce0) | May 18, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [7da21ce089](https://linux-hardware.org/?probe=7da21ce089) | May 18, 2023 |
| Unknown       | V00                         | Mini pc     | [79cb590ea8](https://linux-hardware.org/?probe=79cb590ea8) | May 17, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [28b96d7d6a](https://linux-hardware.org/?probe=28b96d7d6a) | May 17, 2023 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [0906223758](https://linux-hardware.org/?probe=0906223758) | May 17, 2023 |
| Samsung       | 730QFG                      | Convertible | [134377c283](https://linux-hardware.org/?probe=134377c283) | May 17, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [8cb1f28963](https://linux-hardware.org/?probe=8cb1f28963) | May 16, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [0331ab9725](https://linux-hardware.org/?probe=0331ab9725) | May 16, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [c8250719d9](https://linux-hardware.org/?probe=c8250719d9) | May 16, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [98ebdcd589](https://linux-hardware.org/?probe=98ebdcd589) | May 15, 2023 |
| HP            | 3397                        | Desktop     | [17d9dcc121](https://linux-hardware.org/?probe=17d9dcc121) | May 15, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| ASUSTek       | F1A75-V PRO                 | Desktop     | [9ee8a0ca50](https://linux-hardware.org/?probe=9ee8a0ca50) | May 14, 2023 |
| AMI           | Intel                       | Desktop     | [569d80a4a0](https://linux-hardware.org/?probe=569d80a4a0) | May 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [e81d6a8a69](https://linux-hardware.org/?probe=e81d6a8a69) | May 14, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Dell          | Latitude E6500              | Notebook    | [b223b17c87](https://linux-hardware.org/?probe=b223b17c87) | May 14, 2023 |
| PC Special... | P65_67RSRP                  | Notebook    | [892b6d56c8](https://linux-hardware.org/?probe=892b6d56c8) | May 13, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [0701f94970](https://linux-hardware.org/?probe=0701f94970) | May 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [696d2d38df](https://linux-hardware.org/?probe=696d2d38df) | May 13, 2023 |
| Samsung       | R425/R525                   | Notebook    | [a7719ea5d3](https://linux-hardware.org/?probe=a7719ea5d3) | May 13, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [f8c0bd3176](https://linux-hardware.org/?probe=f8c0bd3176) | May 12, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [9ca71ebd01](https://linux-hardware.org/?probe=9ca71ebd01) | May 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [d8c0bd3bff](https://linux-hardware.org/?probe=d8c0bd3bff) | May 12, 2023 |
| Dell          | Latitude 7490               | Notebook    | [a187ae7b7e](https://linux-hardware.org/?probe=a187ae7b7e) | May 12, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [9448d89bb6](https://linux-hardware.org/?probe=9448d89bb6) | May 12, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [094fd8b39a](https://linux-hardware.org/?probe=094fd8b39a) | May 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c071e02f0d](https://linux-hardware.org/?probe=c071e02f0d) | May 12, 2023 |
| Dell          | Latitude E5470              | Notebook    | [59c95182ec](https://linux-hardware.org/?probe=59c95182ec) | May 11, 2023 |
| Intel         | H61                         | Desktop     | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [e360693145](https://linux-hardware.org/?probe=e360693145) | May 11, 2023 |
| Dell          | Latitude 5420               | Notebook    | [a3c2a7c9bf](https://linux-hardware.org/?probe=a3c2a7c9bf) | May 11, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [63e082c879](https://linux-hardware.org/?probe=63e082c879) | May 10, 2023 |
| HP            | ProBook x360 440 G1         | Convertible | [c85cc0e79c](https://linux-hardware.org/?probe=c85cc0e79c) | May 10, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d567c1f954](https://linux-hardware.org/?probe=d567c1f954) | May 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c80f41d509](https://linux-hardware.org/?probe=c80f41d509) | May 09, 2023 |
| IBM           | 00AM544                     | Server      | [4c011ef794](https://linux-hardware.org/?probe=4c011ef794) | May 09, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [cbafd29abc](https://linux-hardware.org/?probe=cbafd29abc) | May 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [8d1f016621](https://linux-hardware.org/?probe=8d1f016621) | May 08, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| Dell          | Latitude 3570               | Notebook    | [8209fc06f4](https://linux-hardware.org/?probe=8209fc06f4) | May 08, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c075073dd8](https://linux-hardware.org/?probe=c075073dd8) | May 07, 2023 |
| TerraQue      | W65_W67RB                   | Notebook    | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Acer          | Aspire M3920                | Desktop     | [aed14c1e20](https://linux-hardware.org/?probe=aed14c1e20) | May 07, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [a062cb2ab6](https://linux-hardware.org/?probe=a062cb2ab6) | May 07, 2023 |
| Biostar       | AM1MHP                      | Desktop     | [1f21e13fcd](https://linux-hardware.org/?probe=1f21e13fcd) | May 07, 2023 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | Notebook    | [4229be0afa](https://linux-hardware.org/?probe=4229be0afa) | May 07, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | Notebook    | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7bbdc5e568](https://linux-hardware.org/?probe=7bbdc5e568) | May 07, 2023 |
| Google        | Lars                        | Notebook    | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [167229560a](https://linux-hardware.org/?probe=167229560a) | May 05, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [68b1e1e6cb](https://linux-hardware.org/?probe=68b1e1e6cb) | May 05, 2023 |
| Razer         | Blade Pro 17 (2019)         | Notebook    | [4b2265c354](https://linux-hardware.org/?probe=4b2265c354) | May 05, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [f6251eeeb1](https://linux-hardware.org/?probe=f6251eeeb1) | May 05, 2023 |
| Medion        | E11201                      | Notebook    | [f0bfd835f8](https://linux-hardware.org/?probe=f0bfd835f8) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [1f2d88bfae](https://linux-hardware.org/?probe=1f2d88bfae) | May 04, 2023 |
| Dell          | Latitude 5480               | Notebook    | [1ab8b910e4](https://linux-hardware.org/?probe=1ab8b910e4) | May 04, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [00a1158a86](https://linux-hardware.org/?probe=00a1158a86) | May 04, 2023 |
| ASUSTek       | X750JB                      | Notebook    | [02a5481254](https://linux-hardware.org/?probe=02a5481254) | May 03, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ae1618c708](https://linux-hardware.org/?probe=ae1618c708) | May 03, 2023 |
| Gigabyte      | H87-HD3                     | Desktop     | [f0e4057e5f](https://linux-hardware.org/?probe=f0e4057e5f) | May 03, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [63015eecb0](https://linux-hardware.org/?probe=63015eecb0) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [861ca2dca3](https://linux-hardware.org/?probe=861ca2dca3) | May 03, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [36574d4502](https://linux-hardware.org/?probe=36574d4502) | May 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [2da8ff7129](https://linux-hardware.org/?probe=2da8ff7129) | May 03, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [263099c212](https://linux-hardware.org/?probe=263099c212) | May 02, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ee8e81add2](https://linux-hardware.org/?probe=ee8e81add2) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [e8ce8c11c0](https://linux-hardware.org/?probe=e8ce8c11c0) | May 01, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [1846ea93e7](https://linux-hardware.org/?probe=1846ea93e7) | May 01, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [a3c89effff](https://linux-hardware.org/?probe=a3c89effff) | May 01, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [45a7e28db1](https://linux-hardware.org/?probe=45a7e28db1) | Apr 30, 2023 |
| HP            | 828A                        | Desktop     | [f1590b355f](https://linux-hardware.org/?probe=f1590b355f) | Apr 30, 2023 |
| Intel         | H81                         | Desktop     | [c70b10516b](https://linux-hardware.org/?probe=c70b10516b) | Apr 30, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [d215d36b64](https://linux-hardware.org/?probe=d215d36b64) | Apr 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [a31fa8f985](https://linux-hardware.org/?probe=a31fa8f985) | Apr 28, 2023 |
| ASUSTek       | X51RL                       | Notebook    | [0d18de9922](https://linux-hardware.org/?probe=0d18de9922) | Apr 28, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [dd76e10243](https://linux-hardware.org/?probe=dd76e10243) | Apr 28, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7feb43607e](https://linux-hardware.org/?probe=7feb43607e) | Apr 27, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [44c5943019](https://linux-hardware.org/?probe=44c5943019) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [442a827555](https://linux-hardware.org/?probe=442a827555) | Apr 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [a6845d78e4](https://linux-hardware.org/?probe=a6845d78e4) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [812906148b](https://linux-hardware.org/?probe=812906148b) | Apr 27, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fee636a549](https://linux-hardware.org/?probe=fee636a549) | Apr 26, 2023 |
| Samsung       | 950XED                      | Notebook    | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| ASUSTek       | P5K/EPU                     | Desktop     | [33ef71c7e7](https://linux-hardware.org/?probe=33ef71c7e7) | Apr 26, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | Notebook    | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [4285b1a3d9](https://linux-hardware.org/?probe=4285b1a3d9) | Apr 25, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b03c4808b0](https://linux-hardware.org/?probe=b03c4808b0) | Apr 25, 2023 |
| Alienware     | Aurora R15 AMD              | Desktop     | [f2e22848d1](https://linux-hardware.org/?probe=f2e22848d1) | Apr 25, 2023 |
| MSI           | FM2-A75MA-E35               | Desktop     | [011f691ce1](https://linux-hardware.org/?probe=011f691ce1) | Apr 25, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [76646ac40d](https://linux-hardware.org/?probe=76646ac40d) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [3d8d7c49f8](https://linux-hardware.org/?probe=3d8d7c49f8) | Apr 24, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [e9a3b8f1d1](https://linux-hardware.org/?probe=e9a3b8f1d1) | Apr 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [2a8a92135b](https://linux-hardware.org/?probe=2a8a92135b) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [0fde788ea5](https://linux-hardware.org/?probe=0fde788ea5) | Apr 24, 2023 |
| Foxconn       | H67M-S/H67M-V/H67           | Desktop     | [92fa61186f](https://linux-hardware.org/?probe=92fa61186f) | Apr 23, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [bee14868f2](https://linux-hardware.org/?probe=bee14868f2) | Apr 23, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [10cd21aba6](https://linux-hardware.org/?probe=10cd21aba6) | Apr 23, 2023 |
| Dell          | 00V16R A00                  | All in one  | [cb94924faa](https://linux-hardware.org/?probe=cb94924faa) | Apr 23, 2023 |
| Dell          | Precision 5520              | Notebook    | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| Dell          | Precision 7550              | Notebook    | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c4a5aad8a1](https://linux-hardware.org/?probe=c4a5aad8a1) | Apr 22, 2023 |
| Gigabyte      | AORUS 15P XD                | Notebook    | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [475a4d151d](https://linux-hardware.org/?probe=475a4d151d) | Apr 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [0dcc2eaa50](https://linux-hardware.org/?probe=0dcc2eaa50) | Apr 22, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [3165ab3194](https://linux-hardware.org/?probe=3165ab3194) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [918115dc84](https://linux-hardware.org/?probe=918115dc84) | Apr 21, 2023 |
| HP            | 82F2 A01                    | Desktop     | [fbcf679bae](https://linux-hardware.org/?probe=fbcf679bae) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| Supermicro    | C7H61                       | Desktop     | [f5e17f37d4](https://linux-hardware.org/?probe=f5e17f37d4) | Apr 21, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [3d241113f4](https://linux-hardware.org/?probe=3d241113f4) | Apr 21, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [cb295448b6](https://linux-hardware.org/?probe=cb295448b6) | Apr 21, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [af5e3d750a](https://linux-hardware.org/?probe=af5e3d750a) | Apr 20, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [970c4dfa6f](https://linux-hardware.org/?probe=970c4dfa6f) | Apr 20, 2023 |
| Supermicro    | C7H61                       | Desktop     | [d975325f4b](https://linux-hardware.org/?probe=d975325f4b) | Apr 20, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [f83e11ca39](https://linux-hardware.org/?probe=f83e11ca39) | Apr 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cd58803d5c](https://linux-hardware.org/?probe=cd58803d5c) | Apr 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7adb4b2000](https://linux-hardware.org/?probe=7adb4b2000) | Apr 19, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [d96138627b](https://linux-hardware.org/?probe=d96138627b) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [cccb2ff44c](https://linux-hardware.org/?probe=cccb2ff44c) | Apr 18, 2023 |
| HP            | 630                         | Notebook    | [daeae9f12e](https://linux-hardware.org/?probe=daeae9f12e) | Apr 18, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [26a430e092](https://linux-hardware.org/?probe=26a430e092) | Apr 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [cc18450a32](https://linux-hardware.org/?probe=cc18450a32) | Apr 17, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [7ed9078ed9](https://linux-hardware.org/?probe=7ed9078ed9) | Apr 17, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [d76555e7e6](https://linux-hardware.org/?probe=d76555e7e6) | Apr 16, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [7aef52516b](https://linux-hardware.org/?probe=7aef52516b) | Apr 16, 2023 |
| ASRock        | B560M Pro4                  | Desktop     | [af72ecc689](https://linux-hardware.org/?probe=af72ecc689) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [073b59d558](https://linux-hardware.org/?probe=073b59d558) | Apr 16, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [c34c2e032c](https://linux-hardware.org/?probe=c34c2e032c) | Apr 15, 2023 |
| AXIOO         | SlimBook 11                 | Notebook    | [b0c639ab77](https://linux-hardware.org/?probe=b0c639ab77) | Apr 15, 2023 |
| HP            | ProBook 650 G3              | Notebook    | [00526690c9](https://linux-hardware.org/?probe=00526690c9) | Apr 15, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [ffa823032e](https://linux-hardware.org/?probe=ffa823032e) | Apr 14, 2023 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [c17cfe4d6d](https://linux-hardware.org/?probe=c17cfe4d6d) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [9518f3e6d8](https://linux-hardware.org/?probe=9518f3e6d8) | Apr 13, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [91946b965a](https://linux-hardware.org/?probe=91946b965a) | Apr 13, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [8d235a410a](https://linux-hardware.org/?probe=8d235a410a) | Apr 13, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [d21971f30f](https://linux-hardware.org/?probe=d21971f30f) | Apr 13, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [5e772c9376](https://linux-hardware.org/?probe=5e772c9376) | Apr 13, 2023 |
| Casper        | NIRVANA NOTEBOOK            | Notebook    | [624fa75f43](https://linux-hardware.org/?probe=624fa75f43) | Apr 12, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [139f5f3aca](https://linux-hardware.org/?probe=139f5f3aca) | Apr 12, 2023 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [674533c5cd](https://linux-hardware.org/?probe=674533c5cd) | Apr 12, 2023 |
| Dell          | Latitude E5450              | Notebook    | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| ASUSTek       | X51RL                       | Notebook    | [ca3fb7f6d5](https://linux-hardware.org/?probe=ca3fb7f6d5) | Apr 11, 2023 |
| HP            | 829C                        | All in one  | [91f5a10ba1](https://linux-hardware.org/?probe=91f5a10ba1) | Apr 11, 2023 |
| Dell          | 0RW199                      | Desktop     | [8c41f4ff91](https://linux-hardware.org/?probe=8c41f4ff91) | Apr 11, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [5875837a8d](https://linux-hardware.org/?probe=5875837a8d) | Apr 10, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [e42bdc9769](https://linux-hardware.org/?probe=e42bdc9769) | Apr 09, 2023 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [0ddbf6cc2e](https://linux-hardware.org/?probe=0ddbf6cc2e) | Apr 07, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [8187fc54a3](https://linux-hardware.org/?probe=8187fc54a3) | Apr 07, 2023 |
| Unknown       | Unknown                     | Notebook    | [0bf91f3219](https://linux-hardware.org/?probe=0bf91f3219) | Apr 06, 2023 |
| Lenovo        | ThinkPad T420 4177RVU       | Notebook    | [994fccf5d0](https://linux-hardware.org/?probe=994fccf5d0) | Apr 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [ec673ad1c1](https://linux-hardware.org/?probe=ec673ad1c1) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [917714b1be](https://linux-hardware.org/?probe=917714b1be) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [ad148ede52](https://linux-hardware.org/?probe=ad148ede52) | Apr 06, 2023 |
| Gigabyte      | M61SME-S2                   | Desktop     | [25d436d2cb](https://linux-hardware.org/?probe=25d436d2cb) | Apr 06, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [b7d43d9e23](https://linux-hardware.org/?probe=b7d43d9e23) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [edd397551c](https://linux-hardware.org/?probe=edd397551c) | Apr 05, 2023 |
| HP            | 0A9Ch                       | Desktop     | [178046626f](https://linux-hardware.org/?probe=178046626f) | Apr 05, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [6ec3c125d5](https://linux-hardware.org/?probe=6ec3c125d5) | Apr 05, 2023 |
| HP            | 3397                        | Desktop     | [175b460d57](https://linux-hardware.org/?probe=175b460d57) | Apr 05, 2023 |
| HP            | 3397                        | Desktop     | [b512b25055](https://linux-hardware.org/?probe=b512b25055) | Apr 05, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [32f708c916](https://linux-hardware.org/?probe=32f708c916) | Apr 05, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [0779903086](https://linux-hardware.org/?probe=0779903086) | Apr 05, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [7cce222ce2](https://linux-hardware.org/?probe=7cce222ce2) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [7eeea6ba29](https://linux-hardware.org/?probe=7eeea6ba29) | Apr 04, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [62f7197973](https://linux-hardware.org/?probe=62f7197973) | Apr 04, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [6e750dfaa5](https://linux-hardware.org/?probe=6e750dfaa5) | Apr 04, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | Notebook    | [1c9d684eba](https://linux-hardware.org/?probe=1c9d684eba) | Apr 04, 2023 |
| Alienware     | 0VDT73 A00                  | Desktop     | [ed92305da6](https://linux-hardware.org/?probe=ed92305da6) | Apr 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFS... | Notebook    | [0cff652e48](https://linux-hardware.org/?probe=0cff652e48) | Apr 03, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [72dc18dacb](https://linux-hardware.org/?probe=72dc18dacb) | Apr 03, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [8ba82ca424](https://linux-hardware.org/?probe=8ba82ca424) | Apr 03, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [f8e61fd850](https://linux-hardware.org/?probe=f8e61fd850) | Apr 03, 2023 |
| ASUSTek       | ASUS ExpertBook P2451FA_... | Notebook    | [05261a9b98](https://linux-hardware.org/?probe=05261a9b98) | Apr 03, 2023 |
| Google        | Eve                         | Convertible | [551ff8d7c2](https://linux-hardware.org/?probe=551ff8d7c2) | Apr 03, 2023 |
| Gigabyte      | X570 AORUS XTREME           | Desktop     | [35c3ae13c5](https://linux-hardware.org/?probe=35c3ae13c5) | Apr 02, 2023 |
| WeiBu         | ADL-N Prod                  | Desktop     | [9b96a245f1](https://linux-hardware.org/?probe=9b96a245f1) | Apr 02, 2023 |
| Thomson       | SPNEOX13-4RD64              | Notebook    | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e800b0ff2e](https://linux-hardware.org/?probe=e800b0ff2e) | Apr 02, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [a0dddcbb95](https://linux-hardware.org/?probe=a0dddcbb95) | Apr 02, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [12647b9601](https://linux-hardware.org/?probe=12647b9601) | Apr 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [46e8dbcdc8](https://linux-hardware.org/?probe=46e8dbcdc8) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [37beaa5cbb](https://linux-hardware.org/?probe=37beaa5cbb) | Apr 02, 2023 |
| Notebook      | PD5x_7xSNC_SND_SNE          | Notebook    | [4809c76aba](https://linux-hardware.org/?probe=4809c76aba) | Apr 02, 2023 |
| AAEON         | MF-001 V1.0                 | Desktop     | [ddceb8b5b0](https://linux-hardware.org/?probe=ddceb8b5b0) | Apr 02, 2023 |
| Lenovo        | ThinkPad X280 20KF001UUS    | Notebook    | [49e740bc77](https://linux-hardware.org/?probe=49e740bc77) | Apr 02, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [0fbed59931](https://linux-hardware.org/?probe=0fbed59931) | Apr 02, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [98f2b162e1](https://linux-hardware.org/?probe=98f2b162e1) | Apr 01, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [bc77efa103](https://linux-hardware.org/?probe=bc77efa103) | Apr 01, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [93f1374055](https://linux-hardware.org/?probe=93f1374055) | Apr 01, 2023 |
| MSI           | MAG A520M VECTOR WIFI       | Desktop     | [3c08cf9aba](https://linux-hardware.org/?probe=3c08cf9aba) | Apr 01, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [4a1b8f3f21](https://linux-hardware.org/?probe=4a1b8f3f21) | Apr 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [89ca656f30](https://linux-hardware.org/?probe=89ca656f30) | Apr 01, 2023 |
| Lenovo        | ThinkCentre M58 9728AHG     | Desktop     | [cb0fa70953](https://linux-hardware.org/?probe=cb0fa70953) | Apr 01, 2023 |
| Gigabyte      | A7 K1                       | Notebook    | [e5e7751054](https://linux-hardware.org/?probe=e5e7751054) | Mar 31, 2023 |
| Chuwi         | CoreBook XPro               | Notebook    | [85ad17d246](https://linux-hardware.org/?probe=85ad17d246) | Mar 31, 2023 |
| Intel         | Whiskey Platform            | Notebook    | [36b9d4d898](https://linux-hardware.org/?probe=36b9d4d898) | Mar 31, 2023 |
| Samsung       | 950QDB                      | Convertible | [09717388fb](https://linux-hardware.org/?probe=09717388fb) | Mar 31, 2023 |
| ASUSTek       | EB1036                      | Desktop     | [955d389e06](https://linux-hardware.org/?probe=955d389e06) | Mar 30, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [3636f7f999](https://linux-hardware.org/?probe=3636f7f999) | Mar 30, 2023 |
| Motion Com... | J3600                       | Notebook    | [0980fe0a37](https://linux-hardware.org/?probe=0980fe0a37) | Mar 30, 2023 |
| Intel         | Whiskey Platform            | Notebook    | [a96edb2321](https://linux-hardware.org/?probe=a96edb2321) | Mar 30, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [278ed0e013](https://linux-hardware.org/?probe=278ed0e013) | Mar 30, 2023 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [49f246c5e7](https://linux-hardware.org/?probe=49f246c5e7) | Mar 29, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4f9eed1de2](https://linux-hardware.org/?probe=4f9eed1de2) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | Notebook    | [cf75eeabd5](https://linux-hardware.org/?probe=cf75eeabd5) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| Intel         | DQ67OW AAG28716-309         | Desktop     | [3a82d680e5](https://linux-hardware.org/?probe=3a82d680e5) | Mar 29, 2023 |
| Dell          | 0200DY A01                  | Desktop     | [722b28547b](https://linux-hardware.org/?probe=722b28547b) | Mar 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [548224967e](https://linux-hardware.org/?probe=548224967e) | Mar 28, 2023 |
| HP            | 0AACh                       | Desktop     | [e313c99b98](https://linux-hardware.org/?probe=e313c99b98) | Mar 28, 2023 |
| MSI           | B85-G43                     | Desktop     | [3dac8c76c2](https://linux-hardware.org/?probe=3dac8c76c2) | Mar 28, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [fd1273ed2e](https://linux-hardware.org/?probe=fd1273ed2e) | Mar 28, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [046b4b7497](https://linux-hardware.org/?probe=046b4b7497) | Mar 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0f38ea375f](https://linux-hardware.org/?probe=0f38ea375f) | Mar 28, 2023 |
| Lenovo        | SHARKBAY SDK0J40709 WIN ... | Desktop     | [22e3e1831c](https://linux-hardware.org/?probe=22e3e1831c) | Mar 28, 2023 |
| HP            | 0AACh                       | Desktop     | [f354a2f03e](https://linux-hardware.org/?probe=f354a2f03e) | Mar 27, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [84092aca44](https://linux-hardware.org/?probe=84092aca44) | Mar 27, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [ccae23c5a7](https://linux-hardware.org/?probe=ccae23c5a7) | Mar 27, 2023 |
| GEO           | GeoFlex 340                 | Convertible | [d18cb08996](https://linux-hardware.org/?probe=d18cb08996) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6553d2c85a](https://linux-hardware.org/?probe=6553d2c85a) | Mar 26, 2023 |
| HP            | 1998                        | Desktop     | [346f37956b](https://linux-hardware.org/?probe=346f37956b) | Mar 26, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | Notebook    | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [ffb310e799](https://linux-hardware.org/?probe=ffb310e799) | Mar 26, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | Notebook    | [369363c3a9](https://linux-hardware.org/?probe=369363c3a9) | Mar 26, 2023 |
| Intel         | NUC5i3RYB H41000-502        | Mini pc     | [fac3426827](https://linux-hardware.org/?probe=fac3426827) | Mar 26, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [cdc4b03fe2](https://linux-hardware.org/?probe=cdc4b03fe2) | Mar 26, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [2246abad85](https://linux-hardware.org/?probe=2246abad85) | Mar 25, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [4262f0e159](https://linux-hardware.org/?probe=4262f0e159) | Mar 25, 2023 |
| MSI           | Z170A PC MATE               | Desktop     | [ad4b4f6a8f](https://linux-hardware.org/?probe=ad4b4f6a8f) | Mar 25, 2023 |
| Intel         | Whiskey Platform            | Notebook    | [e90c029740](https://linux-hardware.org/?probe=e90c029740) | Mar 25, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [30d5652df2](https://linux-hardware.org/?probe=30d5652df2) | Mar 25, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [a0bba69c40](https://linux-hardware.org/?probe=a0bba69c40) | Mar 25, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [98d0daa764](https://linux-hardware.org/?probe=98d0daa764) | Mar 25, 2023 |
| Dell          | Latitude E6420              | Notebook    | [2613e5a6ef](https://linux-hardware.org/?probe=2613e5a6ef) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [bf5cc186ea](https://linux-hardware.org/?probe=bf5cc186ea) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [c37a546614](https://linux-hardware.org/?probe=c37a546614) | Mar 25, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [e7f9195a1d](https://linux-hardware.org/?probe=e7f9195a1d) | Mar 25, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [e7b44d994b](https://linux-hardware.org/?probe=e7b44d994b) | Mar 25, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [444375922e](https://linux-hardware.org/?probe=444375922e) | Mar 25, 2023 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [9a8b9b917f](https://linux-hardware.org/?probe=9a8b9b917f) | Mar 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c114580013](https://linux-hardware.org/?probe=c114580013) | Mar 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [1f256fa102](https://linux-hardware.org/?probe=1f256fa102) | Mar 24, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [63fafca0ac](https://linux-hardware.org/?probe=63fafca0ac) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [2d8268e40f](https://linux-hardware.org/?probe=2d8268e40f) | Mar 24, 2023 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [c50deee021](https://linux-hardware.org/?probe=c50deee021) | Mar 24, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [4e2b8b9de9](https://linux-hardware.org/?probe=4e2b8b9de9) | Mar 24, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [6d1a1f7bd2](https://linux-hardware.org/?probe=6d1a1f7bd2) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [16b93bfe5d](https://linux-hardware.org/?probe=16b93bfe5d) | Mar 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [42d5b573c4](https://linux-hardware.org/?probe=42d5b573c4) | Mar 24, 2023 |
| Dell          | Latitude E7470              | Notebook    | [ca8a2d9579](https://linux-hardware.org/?probe=ca8a2d9579) | Mar 24, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [9b048b064d](https://linux-hardware.org/?probe=9b048b064d) | Mar 24, 2023 |
| Dell          | 0W13NR A08                  | Server      | [13bd99e4bc](https://linux-hardware.org/?probe=13bd99e4bc) | Mar 23, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [43113791e9](https://linux-hardware.org/?probe=43113791e9) | Mar 23, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [4077bee378](https://linux-hardware.org/?probe=4077bee378) | Mar 23, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [529a2febf7](https://linux-hardware.org/?probe=529a2febf7) | Mar 23, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [74d70a3568](https://linux-hardware.org/?probe=74d70a3568) | Mar 23, 2023 |
| Lenovo        | ThinkCentre M58 9728AHG     | Desktop     | [e1cfc1c76d](https://linux-hardware.org/?probe=e1cfc1c76d) | Mar 23, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [84f93bfcf1](https://linux-hardware.org/?probe=84f93bfcf1) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [631968d54b](https://linux-hardware.org/?probe=631968d54b) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [61dcde6523](https://linux-hardware.org/?probe=61dcde6523) | Mar 22, 2023 |
| Dell          | Latitude E7470              | Notebook    | [9595c39422](https://linux-hardware.org/?probe=9595c39422) | Mar 22, 2023 |
| Sony          | VGN-NW270F                  | Notebook    | [48080babd0](https://linux-hardware.org/?probe=48080babd0) | Mar 22, 2023 |
| MSI           | GE70 2PE                    | Notebook    | [5e68fcc30d](https://linux-hardware.org/?probe=5e68fcc30d) | Mar 22, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [ae63ffa582](https://linux-hardware.org/?probe=ae63ffa582) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [2da4187f91](https://linux-hardware.org/?probe=2da4187f91) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [d9c0447b0d](https://linux-hardware.org/?probe=d9c0447b0d) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [293e9a941a](https://linux-hardware.org/?probe=293e9a941a) | Mar 20, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [2787c4bf42](https://linux-hardware.org/?probe=2787c4bf42) | Mar 20, 2023 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [0cfaf0934d](https://linux-hardware.org/?probe=0cfaf0934d) | Mar 20, 2023 |
| HP            | 21F5                        | Desktop     | [865a85e5bc](https://linux-hardware.org/?probe=865a85e5bc) | Mar 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [83fbe3a3d6](https://linux-hardware.org/?probe=83fbe3a3d6) | Mar 20, 2023 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [ede048bc5d](https://linux-hardware.org/?probe=ede048bc5d) | Mar 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [619a36ed2f](https://linux-hardware.org/?probe=619a36ed2f) | Mar 19, 2023 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [420f476f82](https://linux-hardware.org/?probe=420f476f82) | Mar 19, 2023 |
| ASUSTek       | T300CHI                     | Notebook    | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [5e5fd3788e](https://linux-hardware.org/?probe=5e5fd3788e) | Mar 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [efaf7d4a30](https://linux-hardware.org/?probe=efaf7d4a30) | Mar 18, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [99e92fa4df](https://linux-hardware.org/?probe=99e92fa4df) | Mar 18, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [7eaededaac](https://linux-hardware.org/?probe=7eaededaac) | Mar 18, 2023 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [8cf99eb521](https://linux-hardware.org/?probe=8cf99eb521) | Mar 18, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [c70e1d7e98](https://linux-hardware.org/?probe=c70e1d7e98) | Mar 18, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [5a429f93a7](https://linux-hardware.org/?probe=5a429f93a7) | Mar 18, 2023 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [ef3e267972](https://linux-hardware.org/?probe=ef3e267972) | Mar 18, 2023 |
| Clevo         | W340EU                      | Notebook    | [b90ad98b0a](https://linux-hardware.org/?probe=b90ad98b0a) | Mar 18, 2023 |
| HP            | 8266                        | Desktop     | [8bac7f79e8](https://linux-hardware.org/?probe=8bac7f79e8) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [786fded1ce](https://linux-hardware.org/?probe=786fded1ce) | Mar 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e0fa4709db](https://linux-hardware.org/?probe=e0fa4709db) | Mar 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3e5167941c](https://linux-hardware.org/?probe=3e5167941c) | Mar 17, 2023 |
| Clevo         | W340EU                      | Notebook    | [240779648a](https://linux-hardware.org/?probe=240779648a) | Mar 17, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [9ca1015389](https://linux-hardware.org/?probe=9ca1015389) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [1ed7ccd033](https://linux-hardware.org/?probe=1ed7ccd033) | Mar 16, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [d1edfbc4b3](https://linux-hardware.org/?probe=d1edfbc4b3) | Mar 16, 2023 |
| Acer          | Aspire M3920                | Desktop     | [bb2e9ec8a1](https://linux-hardware.org/?probe=bb2e9ec8a1) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [b20f8089c3](https://linux-hardware.org/?probe=b20f8089c3) | Mar 15, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [0ace5375f4](https://linux-hardware.org/?probe=0ace5375f4) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [b0b8ac79d9](https://linux-hardware.org/?probe=b0b8ac79d9) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| Lenovo        | ThinkPad E480 20KNA01HIG    | Notebook    | [c8054d1090](https://linux-hardware.org/?probe=c8054d1090) | Mar 15, 2023 |
| Supermicro    | X9DRD-C/iT+                 | Desktop     | [57c78aa4db](https://linux-hardware.org/?probe=57c78aa4db) | Mar 15, 2023 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [f85336fbca](https://linux-hardware.org/?probe=f85336fbca) | Mar 15, 2023 |
| HP            | ZBook 15                    | Notebook    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f424a1dc42](https://linux-hardware.org/?probe=f424a1dc42) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [b5ef4ae548](https://linux-hardware.org/?probe=b5ef4ae548) | Mar 14, 2023 |
| HP            | 2B52                        | Desktop     | [b541e6085e](https://linux-hardware.org/?probe=b541e6085e) | Mar 14, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [783ff991d4](https://linux-hardware.org/?probe=783ff991d4) | Mar 14, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [c5a25ab496](https://linux-hardware.org/?probe=c5a25ab496) | Mar 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [21fc92246e](https://linux-hardware.org/?probe=21fc92246e) | Mar 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [7e9ce07cb8](https://linux-hardware.org/?probe=7e9ce07cb8) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [3c4e911c6d](https://linux-hardware.org/?probe=3c4e911c6d) | Mar 13, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e79cdeaf10](https://linux-hardware.org/?probe=e79cdeaf10) | Mar 13, 2023 |
| MSI           | B85-G43                     | Desktop     | [9a9a70ade3](https://linux-hardware.org/?probe=9a9a70ade3) | Mar 13, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [007f595264](https://linux-hardware.org/?probe=007f595264) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [456057e6af](https://linux-hardware.org/?probe=456057e6af) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [7ee93079fb](https://linux-hardware.org/?probe=7ee93079fb) | Mar 13, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [11116a9517](https://linux-hardware.org/?probe=11116a9517) | Mar 13, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [6a0673f946](https://linux-hardware.org/?probe=6a0673f946) | Mar 13, 2023 |
| ASRockRack    | ROMED6U-2L2T                | Desktop     | [1af076312d](https://linux-hardware.org/?probe=1af076312d) | Mar 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [6fe2914b41](https://linux-hardware.org/?probe=6fe2914b41) | Mar 12, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [60bc8c1ef5](https://linux-hardware.org/?probe=60bc8c1ef5) | Mar 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [4ee87a1213](https://linux-hardware.org/?probe=4ee87a1213) | Mar 12, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [77b7a9348b](https://linux-hardware.org/?probe=77b7a9348b) | Mar 12, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [d550e765ac](https://linux-hardware.org/?probe=d550e765ac) | Mar 12, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [f2ffca7459](https://linux-hardware.org/?probe=f2ffca7459) | Mar 12, 2023 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [cb1be19cd3](https://linux-hardware.org/?probe=cb1be19cd3) | Mar 11, 2023 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | Notebook    | [bcbf6544cd](https://linux-hardware.org/?probe=bcbf6544cd) | Mar 11, 2023 |
| MSI           | B85-G43                     | Desktop     | [47ac638c2e](https://linux-hardware.org/?probe=47ac638c2e) | Mar 11, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [1b49e21822](https://linux-hardware.org/?probe=1b49e21822) | Mar 11, 2023 |
| HP            | 0AACh                       | Desktop     | [83f0c7df93](https://linux-hardware.org/?probe=83f0c7df93) | Mar 10, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [d039d459d7](https://linux-hardware.org/?probe=d039d459d7) | Mar 10, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [9f02108ada](https://linux-hardware.org/?probe=9f02108ada) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [5a0eb5bfed](https://linux-hardware.org/?probe=5a0eb5bfed) | Mar 09, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [2750a8a462](https://linux-hardware.org/?probe=2750a8a462) | Mar 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [b7fd2dfa30](https://linux-hardware.org/?probe=b7fd2dfa30) | Mar 09, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [f658e58c98](https://linux-hardware.org/?probe=f658e58c98) | Mar 09, 2023 |
| Dell          | Inspiron 15-3565            | Notebook    | [a71845e346](https://linux-hardware.org/?probe=a71845e346) | Mar 09, 2023 |
| ASUSTek       | ZenBook UX463FL_UX463FL     | Convertible | [8fbb4566ac](https://linux-hardware.org/?probe=8fbb4566ac) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [2b74ad2ed1](https://linux-hardware.org/?probe=2b74ad2ed1) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [e777d1af00](https://linux-hardware.org/?probe=e777d1af00) | Mar 08, 2023 |
| Maibenben     | JinMai6 series              | Notebook    | [ace44d9872](https://linux-hardware.org/?probe=ace44d9872) | Mar 08, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [fdc9f52c81](https://linux-hardware.org/?probe=fdc9f52c81) | Mar 08, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [7bd6e95116](https://linux-hardware.org/?probe=7bd6e95116) | Mar 08, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [d3cd7ae3e8](https://linux-hardware.org/?probe=d3cd7ae3e8) | Mar 07, 2023 |
| Lenovo        | IdeaPad C340-14IWL 81RL     | Convertible | [9625716631](https://linux-hardware.org/?probe=9625716631) | Mar 07, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [b48c76be97](https://linux-hardware.org/?probe=b48c76be97) | Mar 07, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [22569ee1f4](https://linux-hardware.org/?probe=22569ee1f4) | Mar 07, 2023 |
| HP            | ENVY TS 17                  | Notebook    | [c915d51f5e](https://linux-hardware.org/?probe=c915d51f5e) | Mar 07, 2023 |
| Datto         | 1000                        | Notebook    | [9df2913c36](https://linux-hardware.org/?probe=9df2913c36) | Mar 07, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [2f8d0ff7f5](https://linux-hardware.org/?probe=2f8d0ff7f5) | Mar 06, 2023 |
| ASUSTek       | K52JT                       | Notebook    | [802fe86b5c](https://linux-hardware.org/?probe=802fe86b5c) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | Notebook    | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [ca2ad0edee](https://linux-hardware.org/?probe=ca2ad0edee) | Mar 05, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [28dbdcfbb7](https://linux-hardware.org/?probe=28dbdcfbb7) | Mar 05, 2023 |
| Dell          | Latitude E6420              | Notebook    | [569d016799](https://linux-hardware.org/?probe=569d016799) | Mar 05, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2311f1da09](https://linux-hardware.org/?probe=2311f1da09) | Mar 05, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [483a11d21e](https://linux-hardware.org/?probe=483a11d21e) | Mar 05, 2023 |
| Gigabyte      | EX58-UD5                    | Desktop     | [8805f0bce5](https://linux-hardware.org/?probe=8805f0bce5) | Mar 05, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7d43df02db](https://linux-hardware.org/?probe=7d43df02db) | Mar 04, 2023 |
| HP            | 89B5 A                      | Desktop     | [b1f4e34d2d](https://linux-hardware.org/?probe=b1f4e34d2d) | Mar 04, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [63e9a399f8](https://linux-hardware.org/?probe=63e9a399f8) | Mar 04, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [8a4cc5192e](https://linux-hardware.org/?probe=8a4cc5192e) | Mar 04, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [a7860ee046](https://linux-hardware.org/?probe=a7860ee046) | Mar 04, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [c654c1809d](https://linux-hardware.org/?probe=c654c1809d) | Mar 04, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5a15c4c2b0](https://linux-hardware.org/?probe=5a15c4c2b0) | Mar 03, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [9a3c215b30](https://linux-hardware.org/?probe=9a3c215b30) | Mar 03, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [fdee05953f](https://linux-hardware.org/?probe=fdee05953f) | Mar 03, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [a5939aa47c](https://linux-hardware.org/?probe=a5939aa47c) | Mar 03, 2023 |
| Dell          | Latitude 5420               | Notebook    | [b763e54ded](https://linux-hardware.org/?probe=b763e54ded) | Mar 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4d68c19c3e](https://linux-hardware.org/?probe=4d68c19c3e) | Mar 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [6c007c983c](https://linux-hardware.org/?probe=6c007c983c) | Mar 02, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [82847b3b1f](https://linux-hardware.org/?probe=82847b3b1f) | Mar 02, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [cc8c299b5d](https://linux-hardware.org/?probe=cc8c299b5d) | Mar 01, 2023 |
| Dell          | 05R2TK A01                  | All in one  | [efa9d9069d](https://linux-hardware.org/?probe=efa9d9069d) | Mar 01, 2023 |
| Pegatron      | SM3330B 0500B               | Desktop     | [7ec6d4d881](https://linux-hardware.org/?probe=7ec6d4d881) | Mar 01, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [727ce4b27e](https://linux-hardware.org/?probe=727ce4b27e) | Mar 01, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [bbc9bc409c](https://linux-hardware.org/?probe=bbc9bc409c) | Mar 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [131f94f213](https://linux-hardware.org/?probe=131f94f213) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [8fd450db03](https://linux-hardware.org/?probe=8fd450db03) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [41439f6b61](https://linux-hardware.org/?probe=41439f6b61) | Feb 28, 2023 |
| Dell          | Latitude 5530               | Notebook    | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| ASRock        | Z790 PG Lightning           | Desktop     | [86c7144757](https://linux-hardware.org/?probe=86c7144757) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [ad20f98122](https://linux-hardware.org/?probe=ad20f98122) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [a5f5bdc903](https://linux-hardware.org/?probe=a5f5bdc903) | Feb 26, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [d3821bdbab](https://linux-hardware.org/?probe=d3821bdbab) | Feb 26, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [d6e0c6c0ac](https://linux-hardware.org/?probe=d6e0c6c0ac) | Feb 26, 2023 |
| ASRock        | G41C-GS                     | Desktop     | [6a698dda57](https://linux-hardware.org/?probe=6a698dda57) | Feb 26, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [575e6a8c55](https://linux-hardware.org/?probe=575e6a8c55) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [b410d220e6](https://linux-hardware.org/?probe=b410d220e6) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [67b8b5ad09](https://linux-hardware.org/?probe=67b8b5ad09) | Feb 26, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [c872892cfd](https://linux-hardware.org/?probe=c872892cfd) | Feb 26, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c6ca9e8499](https://linux-hardware.org/?probe=c6ca9e8499) | Feb 26, 2023 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [bd6c07d84d](https://linux-hardware.org/?probe=bd6c07d84d) | Feb 26, 2023 |
| HP            | G62                         | Notebook    | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2943aa6cd7](https://linux-hardware.org/?probe=2943aa6cd7) | Feb 25, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [0b9491b3a0](https://linux-hardware.org/?probe=0b9491b3a0) | Feb 25, 2023 |
| ASRock        | H97 Pro4                    | Desktop     | [f703af2e6b](https://linux-hardware.org/?probe=f703af2e6b) | Feb 25, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [844de888cd](https://linux-hardware.org/?probe=844de888cd) | Feb 25, 2023 |
| System76      | Gazelle                     | Notebook    | [64fcb063eb](https://linux-hardware.org/?probe=64fcb063eb) | Feb 25, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e7bf168729](https://linux-hardware.org/?probe=e7bf168729) | Feb 25, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [0a44dcc29e](https://linux-hardware.org/?probe=0a44dcc29e) | Feb 24, 2023 |
| Dell          | Latitude 5530               | Notebook    | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Alienware     | m15 R7 AMD                  | Notebook    | [3ba05d49d8](https://linux-hardware.org/?probe=3ba05d49d8) | Feb 24, 2023 |
| ASRock        | M3A770DE                    | Desktop     | [b025c7a092](https://linux-hardware.org/?probe=b025c7a092) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [463265c999](https://linux-hardware.org/?probe=463265c999) | Feb 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [4aec81f692](https://linux-hardware.org/?probe=4aec81f692) | Feb 24, 2023 |
| MSI           | GE75 Raider 9SE             | Notebook    | [6d0782da8e](https://linux-hardware.org/?probe=6d0782da8e) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [471b84b6d4](https://linux-hardware.org/?probe=471b84b6d4) | Feb 23, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [2f9c2ec647](https://linux-hardware.org/?probe=2f9c2ec647) | Feb 23, 2023 |
| Samsung       | 950QDB                      | Convertible | [2545626207](https://linux-hardware.org/?probe=2545626207) | Feb 23, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [27f07447f7](https://linux-hardware.org/?probe=27f07447f7) | Feb 23, 2023 |
| Shuttle       | FL10J                       | Desktop     | [943316a9c5](https://linux-hardware.org/?probe=943316a9c5) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [c81213c25e](https://linux-hardware.org/?probe=c81213c25e) | Feb 22, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [4a3b8e0755](https://linux-hardware.org/?probe=4a3b8e0755) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d6ec8781f4](https://linux-hardware.org/?probe=d6ec8781f4) | Feb 21, 2023 |
| MSI           | B85-G43                     | Desktop     | [62273631b2](https://linux-hardware.org/?probe=62273631b2) | Feb 21, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [ce7bdb1ddf](https://linux-hardware.org/?probe=ce7bdb1ddf) | Feb 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS3E20... | Notebook    | [012b54b31c](https://linux-hardware.org/?probe=012b54b31c) | Feb 21, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [0d286f12f4](https://linux-hardware.org/?probe=0d286f12f4) | Feb 21, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [5fa20b737f](https://linux-hardware.org/?probe=5fa20b737f) | Feb 21, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [39718b8983](https://linux-hardware.org/?probe=39718b8983) | Feb 20, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [1e0de945b7](https://linux-hardware.org/?probe=1e0de945b7) | Feb 20, 2023 |
| Gigabyte      | X99-Ultra Gaming-CF         | Desktop     | [031c13ea35](https://linux-hardware.org/?probe=031c13ea35) | Feb 19, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [6824ee9944](https://linux-hardware.org/?probe=6824ee9944) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [7e5327c1ed](https://linux-hardware.org/?probe=7e5327c1ed) | Feb 19, 2023 |
| HP            | ProBook 4730s               | Notebook    | [99232fe32d](https://linux-hardware.org/?probe=99232fe32d) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| HP            | Victus by Laptop 16z-e10... | Notebook    | [a48460122c](https://linux-hardware.org/?probe=a48460122c) | Feb 19, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [25c9923614](https://linux-hardware.org/?probe=25c9923614) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [b3c5c043ea](https://linux-hardware.org/?probe=b3c5c043ea) | Feb 18, 2023 |
| Acer          | Aspire A515-46              | Notebook    | [46a8b61785](https://linux-hardware.org/?probe=46a8b61785) | Feb 18, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [1c1470c8a2](https://linux-hardware.org/?probe=1c1470c8a2) | Feb 18, 2023 |
| Intel         | DP965LT AAD41694-206        | Desktop     | [2744ec3c4a](https://linux-hardware.org/?probe=2744ec3c4a) | Feb 18, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [7daf230ef2](https://linux-hardware.org/?probe=7daf230ef2) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [eb64c99981](https://linux-hardware.org/?probe=eb64c99981) | Feb 18, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [542553dd55](https://linux-hardware.org/?probe=542553dd55) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [4baabf8013](https://linux-hardware.org/?probe=4baabf8013) | Feb 18, 2023 |
| Dell          | Precision 7540              | Notebook    | [2a511e3e78](https://linux-hardware.org/?probe=2a511e3e78) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [6538791548](https://linux-hardware.org/?probe=6538791548) | Feb 17, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [2da59271fe](https://linux-hardware.org/?probe=2da59271fe) | Feb 17, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [e192547cd3](https://linux-hardware.org/?probe=e192547cd3) | Feb 17, 2023 |
| Alienware     | 17 R2                       | Notebook    | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [a59b4a2c12](https://linux-hardware.org/?probe=a59b4a2c12) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | Notebook    | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [6f0ca25023](https://linux-hardware.org/?probe=6f0ca25023) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | Notebook    | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| Acer          | Aspire A717-71G             | Notebook    | [488a80bcda](https://linux-hardware.org/?probe=488a80bcda) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [a16c82308f](https://linux-hardware.org/?probe=a16c82308f) | Feb 16, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [146c38cbdf](https://linux-hardware.org/?probe=146c38cbdf) | Feb 16, 2023 |
| Lenovo        | ThinkPad E14 20RAS1AQ00     | Notebook    | [b534643d92](https://linux-hardware.org/?probe=b534643d92) | Feb 16, 2023 |
| Dell          | G15 5515                    | Notebook    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [361eb28148](https://linux-hardware.org/?probe=361eb28148) | Feb 16, 2023 |
| Pegatron      | SM3330B 0500B               | Desktop     | [701fdae932](https://linux-hardware.org/?probe=701fdae932) | Feb 16, 2023 |
| Gigabyte      | B760I AORUS PRO DDR4        | Desktop     | [62a320f515](https://linux-hardware.org/?probe=62a320f515) | Feb 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [043e92c2ee](https://linux-hardware.org/?probe=043e92c2ee) | Feb 15, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [b2a1267353](https://linux-hardware.org/?probe=b2a1267353) | Feb 15, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5d2153f4f2](https://linux-hardware.org/?probe=5d2153f4f2) | Feb 14, 2023 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [05bc165699](https://linux-hardware.org/?probe=05bc165699) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [695abe8c65](https://linux-hardware.org/?probe=695abe8c65) | Feb 14, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [02ae55d12c](https://linux-hardware.org/?probe=02ae55d12c) | Feb 13, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [4cc741a70a](https://linux-hardware.org/?probe=4cc741a70a) | Feb 13, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [08a9c049a1](https://linux-hardware.org/?probe=08a9c049a1) | Feb 13, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [5b93510482](https://linux-hardware.org/?probe=5b93510482) | Feb 13, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [d517411fc5](https://linux-hardware.org/?probe=d517411fc5) | Feb 13, 2023 |
| HP            | ProBook 6470b               | Notebook    | [e747086309](https://linux-hardware.org/?probe=e747086309) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [920b8786c6](https://linux-hardware.org/?probe=920b8786c6) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [067646f7f8](https://linux-hardware.org/?probe=067646f7f8) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [50163cfc72](https://linux-hardware.org/?probe=50163cfc72) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [566c6a5316](https://linux-hardware.org/?probe=566c6a5316) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [a833fa9a0c](https://linux-hardware.org/?probe=a833fa9a0c) | Feb 12, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [3542104e07](https://linux-hardware.org/?probe=3542104e07) | Feb 12, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [874ccdcf1a](https://linux-hardware.org/?probe=874ccdcf1a) | Feb 12, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| HP            | 3397                        | Desktop     | [cc5cdaf09b](https://linux-hardware.org/?probe=cc5cdaf09b) | Feb 12, 2023 |
| Google        | Blooguard                   | Notebook    | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [dec32b9b60](https://linux-hardware.org/?probe=dec32b9b60) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | Notebook    | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| HP            | Notebook                    | Notebook    | [94c42af775](https://linux-hardware.org/?probe=94c42af775) | Feb 11, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82Q1       | Notebook    | [4ab5181634](https://linux-hardware.org/?probe=4ab5181634) | Feb 11, 2023 |
| HP            | Notebook                    | Notebook    | [e19e0407ec](https://linux-hardware.org/?probe=e19e0407ec) | Feb 11, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [3af9191e4f](https://linux-hardware.org/?probe=3af9191e4f) | Feb 11, 2023 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [c65e5f04d0](https://linux-hardware.org/?probe=c65e5f04d0) | Feb 11, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [b2c120d8d7](https://linux-hardware.org/?probe=b2c120d8d7) | Feb 11, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [1942c9f528](https://linux-hardware.org/?probe=1942c9f528) | Feb 11, 2023 |
| HP            | Notebook                    | Notebook    | [4daf49165c](https://linux-hardware.org/?probe=4daf49165c) | Feb 10, 2023 |
| Gigabyte      | B660M GAMING X DDR4         | Desktop     | [845d2e4d52](https://linux-hardware.org/?probe=845d2e4d52) | Feb 10, 2023 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [a19717f948](https://linux-hardware.org/?probe=a19717f948) | Feb 10, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [200150e4e3](https://linux-hardware.org/?probe=200150e4e3) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [f493bc6d9d](https://linux-hardware.org/?probe=f493bc6d9d) | Feb 10, 2023 |
| HP            | 86F0 11000                  | All in one  | [2fab63e976](https://linux-hardware.org/?probe=2fab63e976) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [5b22c1a20a](https://linux-hardware.org/?probe=5b22c1a20a) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | Notebook    | [ccbec1376d](https://linux-hardware.org/?probe=ccbec1376d) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | Notebook    | [0d5a38a089](https://linux-hardware.org/?probe=0d5a38a089) | Feb 09, 2023 |
| Gigabyte      | B560 HD3                    | Desktop     | [b4fa86401f](https://linux-hardware.org/?probe=b4fa86401f) | Feb 09, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [552d730c6d](https://linux-hardware.org/?probe=552d730c6d) | Feb 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [b79b2f3f75](https://linux-hardware.org/?probe=b79b2f3f75) | Feb 09, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [3d1b70c4af](https://linux-hardware.org/?probe=3d1b70c4af) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [ee5a11ee81](https://linux-hardware.org/?probe=ee5a11ee81) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5df3b5ad7e](https://linux-hardware.org/?probe=5df3b5ad7e) | Feb 08, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [518a58b5ca](https://linux-hardware.org/?probe=518a58b5ca) | Feb 08, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [556b064487](https://linux-hardware.org/?probe=556b064487) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [be25e0c930](https://linux-hardware.org/?probe=be25e0c930) | Feb 07, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [d139473252](https://linux-hardware.org/?probe=d139473252) | Feb 07, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [7dcb345b45](https://linux-hardware.org/?probe=7dcb345b45) | Feb 06, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [8c3dd4055e](https://linux-hardware.org/?probe=8c3dd4055e) | Feb 06, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [223378c538](https://linux-hardware.org/?probe=223378c538) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | Notebook    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [00006691a6](https://linux-hardware.org/?probe=00006691a6) | Feb 05, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [bb420e8f71](https://linux-hardware.org/?probe=bb420e8f71) | Feb 05, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [ce7bdb0a98](https://linux-hardware.org/?probe=ce7bdb0a98) | Feb 05, 2023 |
| ECS           | H81H3-MV                    | Desktop     | [e60810d8e6](https://linux-hardware.org/?probe=e60810d8e6) | Feb 05, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| ONN           | 100002435                   | Tablet      | [35d8a4ce58](https://linux-hardware.org/?probe=35d8a4ce58) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [c614e44344](https://linux-hardware.org/?probe=c614e44344) | Feb 05, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [ad59fdb4e4](https://linux-hardware.org/?probe=ad59fdb4e4) | Feb 05, 2023 |
| HP            | G60                         | Notebook    | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| Lenovo        | IdeaPad U310 Touch          | Notebook    | [6fd17687a4](https://linux-hardware.org/?probe=6fd17687a4) | Feb 04, 2023 |
| HP            | 0AACh                       | Desktop     | [86d994993f](https://linux-hardware.org/?probe=86d994993f) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| ASUSTek       | X550JK                      | Notebook    | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [2aa4452578](https://linux-hardware.org/?probe=2aa4452578) | Feb 02, 2023 |
| Chuwi         | Hi10 Go                     | Notebook    | [a1b6911dc1](https://linux-hardware.org/?probe=a1b6911dc1) | Feb 02, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [a84d546f50](https://linux-hardware.org/?probe=a84d546f50) | Feb 02, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [c91d5b265b](https://linux-hardware.org/?probe=c91d5b265b) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | Notebook    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [690d45db9f](https://linux-hardware.org/?probe=690d45db9f) | Feb 02, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [ef1817a829](https://linux-hardware.org/?probe=ef1817a829) | Feb 02, 2023 |
| Lenovo        | ThinkPad W530 2463A49       | Notebook    | [374c21a672](https://linux-hardware.org/?probe=374c21a672) | Feb 02, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [4b6904f9b1](https://linux-hardware.org/?probe=4b6904f9b1) | Feb 01, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| Dell          | Precision 7540              | Notebook    | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ab92a33bdf](https://linux-hardware.org/?probe=ab92a33bdf) | Feb 01, 2023 |
| HP            | 0AACh                       | Desktop     | [f41abcf7f9](https://linux-hardware.org/?probe=f41abcf7f9) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [7e78833b8b](https://linux-hardware.org/?probe=7e78833b8b) | Feb 01, 2023 |
| Medion        | E15410                      | Notebook    | [24135c324e](https://linux-hardware.org/?probe=24135c324e) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [ebbe861495](https://linux-hardware.org/?probe=ebbe861495) | Jan 31, 2023 |
| HP            | Notebook                    | Notebook    | [f352309997](https://linux-hardware.org/?probe=f352309997) | Jan 31, 2023 |
| HP            | 0AACh                       | Desktop     | [32961ffb11](https://linux-hardware.org/?probe=32961ffb11) | Jan 31, 2023 |
| Google        | Lillipup                    | Notebook    | [45f9b8c3cf](https://linux-hardware.org/?probe=45f9b8c3cf) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | Notebook    | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| HP            | 0AACh                       | Desktop     | [94baf3c57c](https://linux-hardware.org/?probe=94baf3c57c) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [949ea399fb](https://linux-hardware.org/?probe=949ea399fb) | Jan 31, 2023 |
| HP            | 829A                        | Mini pc     | [a6925c200b](https://linux-hardware.org/?probe=a6925c200b) | Jan 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [96671141f9](https://linux-hardware.org/?probe=96671141f9) | Jan 30, 2023 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [bf112866e3](https://linux-hardware.org/?probe=bf112866e3) | Jan 30, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [8f3278e68a](https://linux-hardware.org/?probe=8f3278e68a) | Jan 30, 2023 |
| Acer          | Swift SF114-31              | Notebook    | [9d7f73242e](https://linux-hardware.org/?probe=9d7f73242e) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [2f0ffeb3be](https://linux-hardware.org/?probe=2f0ffeb3be) | Jan 29, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | Notebook    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | Notebook    | [50eb066d41](https://linux-hardware.org/?probe=50eb066d41) | Jan 29, 2023 |
| Acer          | Nitro AN517-41              | Notebook    | [ecb7c49d2e](https://linux-hardware.org/?probe=ecb7c49d2e) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [0abc762f30](https://linux-hardware.org/?probe=0abc762f30) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [1a9e67408e](https://linux-hardware.org/?probe=1a9e67408e) | Jan 28, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f447127e74](https://linux-hardware.org/?probe=f447127e74) | Jan 28, 2023 |
| AZW           | GTR V02                     | Desktop     | [b1b34f10a2](https://linux-hardware.org/?probe=b1b34f10a2) | Jan 28, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [cd55d1ec5d](https://linux-hardware.org/?probe=cd55d1ec5d) | Jan 28, 2023 |
| Dell          | Precision 7730              | Notebook    | [058f16ac84](https://linux-hardware.org/?probe=058f16ac84) | Jan 28, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [fa464af5fb](https://linux-hardware.org/?probe=fa464af5fb) | Jan 27, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [36db3e5d78](https://linux-hardware.org/?probe=36db3e5d78) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [b265f91d10](https://linux-hardware.org/?probe=b265f91d10) | Jan 27, 2023 |
| Dell          | 0XPDFK A01                  | Desktop     | [4611591cc9](https://linux-hardware.org/?probe=4611591cc9) | Jan 27, 2023 |
| HP            | 3397                        | Desktop     | [764f737fcf](https://linux-hardware.org/?probe=764f737fcf) | Jan 27, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [32a666b611](https://linux-hardware.org/?probe=32a666b611) | Jan 27, 2023 |
| ASUSTek       | GL503VD                     | Notebook    | [f4095c61ff](https://linux-hardware.org/?probe=f4095c61ff) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| HP            | 3397                        | Desktop     | [10b6614763](https://linux-hardware.org/?probe=10b6614763) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| Medion        | E15410                      | Notebook    | [5ba9ffd6a8](https://linux-hardware.org/?probe=5ba9ffd6a8) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | Notebook    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | Notebook    | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [b7dea81a92](https://linux-hardware.org/?probe=b7dea81a92) | Jan 25, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [34882391f3](https://linux-hardware.org/?probe=34882391f3) | Jan 25, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [6462d71b74](https://linux-hardware.org/?probe=6462d71b74) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| Dell          | 0Y2K8N A00                  | Desktop     | [7f135346af](https://linux-hardware.org/?probe=7f135346af) | Jan 24, 2023 |
| MSI           | MS-B1831                    | Desktop     | [64348a9180](https://linux-hardware.org/?probe=64348a9180) | Jan 24, 2023 |
| Dell          | Latitude 5491               | Notebook    | [37746d7f71](https://linux-hardware.org/?probe=37746d7f71) | Jan 24, 2023 |
| Medion        | E15410                      | Notebook    | [f7e27f2ba9](https://linux-hardware.org/?probe=f7e27f2ba9) | Jan 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b20da22e41](https://linux-hardware.org/?probe=b20da22e41) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | Notebook    | [4f83721cab](https://linux-hardware.org/?probe=4f83721cab) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | Notebook    | [9e12a145fd](https://linux-hardware.org/?probe=9e12a145fd) | Jan 23, 2023 |
| HP            | ProBook 6470b               | Notebook    | [3319221b9c](https://linux-hardware.org/?probe=3319221b9c) | Jan 23, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3951ddfe72](https://linux-hardware.org/?probe=3951ddfe72) | Jan 23, 2023 |
| MSI           | MS-AEC21                    | All in one  | [e541cd3043](https://linux-hardware.org/?probe=e541cd3043) | Jan 23, 2023 |
| MACHENIKE     | MACHCREATOR-16              | Notebook    | [df35617170](https://linux-hardware.org/?probe=df35617170) | Jan 22, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [8d5c313d43](https://linux-hardware.org/?probe=8d5c313d43) | Jan 22, 2023 |
| HP            | ProBook 6570b               | Notebook    | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| Dell          | Latitude E6430s             | Notebook    | [8f9185a327](https://linux-hardware.org/?probe=8f9185a327) | Jan 22, 2023 |
| Carbon Sys... | Iridium 14                  | Notebook    | [7fcc79f37c](https://linux-hardware.org/?probe=7fcc79f37c) | Jan 22, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d2b797f3de](https://linux-hardware.org/?probe=d2b797f3de) | Jan 21, 2023 |
| Dell          | Vostro 1014                 | Notebook    | [f7ff3312f2](https://linux-hardware.org/?probe=f7ff3312f2) | Jan 21, 2023 |
| Acer          | TravelMate B118-M           | Notebook    | [029850a46e](https://linux-hardware.org/?probe=029850a46e) | Jan 21, 2023 |
| Dell          | Vostro 1014                 | Notebook    | [724939f0cf](https://linux-hardware.org/?probe=724939f0cf) | Jan 21, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [bfaffed5d2](https://linux-hardware.org/?probe=bfaffed5d2) | Jan 21, 2023 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [a6f80e64b2](https://linux-hardware.org/?probe=a6f80e64b2) | Jan 21, 2023 |
| Lenovo        | 3148 SDK0L22692 WIN 3792... | Desktop     | [f66c33020e](https://linux-hardware.org/?probe=f66c33020e) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | Notebook    | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [29d770594e](https://linux-hardware.org/?probe=29d770594e) | Jan 21, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [0072a47bce](https://linux-hardware.org/?probe=0072a47bce) | Jan 20, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [732a1b992a](https://linux-hardware.org/?probe=732a1b992a) | Jan 20, 2023 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [49f0bb23ea](https://linux-hardware.org/?probe=49f0bb23ea) | Jan 20, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Dell          | Latitude 5320               | Notebook    | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| Sony          | SVE1513B4E                  | Notebook    | [cbd9f98f30](https://linux-hardware.org/?probe=cbd9f98f30) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [2b7ce5b726](https://linux-hardware.org/?probe=2b7ce5b726) | Jan 20, 2023 |
| Dell          | 03NVJ6 A03                  | Desktop     | [4269f0e624](https://linux-hardware.org/?probe=4269f0e624) | Jan 20, 2023 |
| Dell          | G3 3779                     | Notebook    | [c4c13ca86b](https://linux-hardware.org/?probe=c4c13ca86b) | Jan 19, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [d9e9f47ad4](https://linux-hardware.org/?probe=d9e9f47ad4) | Jan 19, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [a9d66d6af6](https://linux-hardware.org/?probe=a9d66d6af6) | Jan 18, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [0bc976587f](https://linux-hardware.org/?probe=0bc976587f) | Jan 18, 2023 |
| HP            | Notebook                    | Notebook    | [1c935be3b1](https://linux-hardware.org/?probe=1c935be3b1) | Jan 18, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [3dfd98d007](https://linux-hardware.org/?probe=3dfd98d007) | Jan 17, 2023 |
| ASRock        | Z370 Killer SLI/ac          | Desktop     | [8f20499728](https://linux-hardware.org/?probe=8f20499728) | Jan 17, 2023 |
| Dell          | 0D881F A05                  | Desktop     | [0426ee9130](https://linux-hardware.org/?probe=0426ee9130) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [dcbf101b59](https://linux-hardware.org/?probe=dcbf101b59) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [3964c82d71](https://linux-hardware.org/?probe=3964c82d71) | Jan 17, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | Notebook    | [21ed6bd75d](https://linux-hardware.org/?probe=21ed6bd75d) | Jan 17, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [542c3d1ef4](https://linux-hardware.org/?probe=542c3d1ef4) | Jan 16, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [8493fa353c](https://linux-hardware.org/?probe=8493fa353c) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [3715650f46](https://linux-hardware.org/?probe=3715650f46) | Jan 16, 2023 |
| ASUSTek       | P5K/EPU                     | Desktop     | [c159b4d65b](https://linux-hardware.org/?probe=c159b4d65b) | Jan 16, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [de76cee99a](https://linux-hardware.org/?probe=de76cee99a) | Jan 16, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [bf8115e391](https://linux-hardware.org/?probe=bf8115e391) | Jan 15, 2023 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [ba8e771128](https://linux-hardware.org/?probe=ba8e771128) | Jan 15, 2023 |
| Notebook      | W35xSS_370SS                | Notebook    | [2337667e0f](https://linux-hardware.org/?probe=2337667e0f) | Jan 15, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [4621c0d31b](https://linux-hardware.org/?probe=4621c0d31b) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [86039b3063](https://linux-hardware.org/?probe=86039b3063) | Jan 15, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [7d0bdd8606](https://linux-hardware.org/?probe=7d0bdd8606) | Jan 15, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [614c167f82](https://linux-hardware.org/?probe=614c167f82) | Jan 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [2687f89612](https://linux-hardware.org/?probe=2687f89612) | Jan 14, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [aa35c556bc](https://linux-hardware.org/?probe=aa35c556bc) | Jan 13, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [709045636c](https://linux-hardware.org/?probe=709045636c) | Jan 13, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [77a4e207cd](https://linux-hardware.org/?probe=77a4e207cd) | Jan 13, 2023 |
| ASUSTek       | G10AJ                       | Desktop     | [e300c19806](https://linux-hardware.org/?probe=e300c19806) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c3a30838c3](https://linux-hardware.org/?probe=c3a30838c3) | Jan 13, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [3a97589bc9](https://linux-hardware.org/?probe=3a97589bc9) | Jan 12, 2023 |
| Dell          | 0GXM1W A01                  | Desktop     | [dc468fd3a8](https://linux-hardware.org/?probe=dc468fd3a8) | Jan 12, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Dell          | Latitude 3420               | Notebook    | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| Alienware     | 0H869M A00                  | Desktop     | [6dc1967760](https://linux-hardware.org/?probe=6dc1967760) | Jan 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [ed648f1f72](https://linux-hardware.org/?probe=ed648f1f72) | Jan 12, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [1987221c12](https://linux-hardware.org/?probe=1987221c12) | Jan 12, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [6286dbdb0b](https://linux-hardware.org/?probe=6286dbdb0b) | Jan 11, 2023 |
| ASUSTek       | P5K/EPU                     | Desktop     | [c6ffd59fb2](https://linux-hardware.org/?probe=c6ffd59fb2) | Jan 11, 2023 |
| MSI           | Bravo 17 A4DDK              | Notebook    | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c5e0e8163f](https://linux-hardware.org/?probe=c5e0e8163f) | Jan 10, 2023 |
| Google        | Rammus                      | Notebook    | [489d09eaa7](https://linux-hardware.org/?probe=489d09eaa7) | Jan 10, 2023 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [8434b565c3](https://linux-hardware.org/?probe=8434b565c3) | Jan 10, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [1a619ff898](https://linux-hardware.org/?probe=1a619ff898) | Jan 10, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [b9df733a47](https://linux-hardware.org/?probe=b9df733a47) | Jan 10, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [75209e7521](https://linux-hardware.org/?probe=75209e7521) | Jan 10, 2023 |
| HP            | ProBook 6570b               | Notebook    | [e5c0ea26d1](https://linux-hardware.org/?probe=e5c0ea26d1) | Jan 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [5d3f8e9948](https://linux-hardware.org/?probe=5d3f8e9948) | Jan 09, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [a43ad3cbf7](https://linux-hardware.org/?probe=a43ad3cbf7) | Jan 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [774322328a](https://linux-hardware.org/?probe=774322328a) | Jan 09, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [5bc41d3659](https://linux-hardware.org/?probe=5bc41d3659) | Jan 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [d94fa63122](https://linux-hardware.org/?probe=d94fa63122) | Jan 08, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [3b3f695b94](https://linux-hardware.org/?probe=3b3f695b94) | Jan 08, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [eb562a1e24](https://linux-hardware.org/?probe=eb562a1e24) | Jan 08, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [4ebc1e97c5](https://linux-hardware.org/?probe=4ebc1e97c5) | Jan 07, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [86b0308f38](https://linux-hardware.org/?probe=86b0308f38) | Jan 07, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [929ff5acbb](https://linux-hardware.org/?probe=929ff5acbb) | Jan 07, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [1ff445305d](https://linux-hardware.org/?probe=1ff445305d) | Jan 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c7a6fdbf55](https://linux-hardware.org/?probe=c7a6fdbf55) | Jan 06, 2023 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [cb25b352e0](https://linux-hardware.org/?probe=cb25b352e0) | Jan 06, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [aae608e132](https://linux-hardware.org/?probe=aae608e132) | Jan 06, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [e4f0b0506b](https://linux-hardware.org/?probe=e4f0b0506b) | Jan 06, 2023 |
| Microsoft     | Surface Laptop              | Tablet      | [391d13c7ba](https://linux-hardware.org/?probe=391d13c7ba) | Jan 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [78ab02a131](https://linux-hardware.org/?probe=78ab02a131) | Jan 05, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [ce4648337e](https://linux-hardware.org/?probe=ce4648337e) | Jan 05, 2023 |
| Dell          | 0WPMFG A00                  | Desktop     | [02a8ab8bdc](https://linux-hardware.org/?probe=02a8ab8bdc) | Jan 05, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [c19db82125](https://linux-hardware.org/?probe=c19db82125) | Jan 05, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [697abed1c0](https://linux-hardware.org/?probe=697abed1c0) | Jan 05, 2023 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [efb1372825](https://linux-hardware.org/?probe=efb1372825) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [1c58ea8841](https://linux-hardware.org/?probe=1c58ea8841) | Jan 05, 2023 |
| Acer          | Swift SF314-71              | Notebook    | [21ebb26df9](https://linux-hardware.org/?probe=21ebb26df9) | Jan 05, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [90cbbe6b1d](https://linux-hardware.org/?probe=90cbbe6b1d) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [e780ec3e2a](https://linux-hardware.org/?probe=e780ec3e2a) | Jan 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | Notebook    | [ace1cd7d4d](https://linux-hardware.org/?probe=ace1cd7d4d) | Jan 04, 2023 |
| Acer          | Aspire M5-583P              | Notebook    | [1182d7305d](https://linux-hardware.org/?probe=1182d7305d) | Jan 04, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [2e047c3ad5](https://linux-hardware.org/?probe=2e047c3ad5) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e24802533e](https://linux-hardware.org/?probe=e24802533e) | Jan 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [7a85f424f5](https://linux-hardware.org/?probe=7a85f424f5) | Jan 03, 2023 |
| HUAWEI        | NBLL-WXX9                   | Notebook    | [7e5acbf050](https://linux-hardware.org/?probe=7e5acbf050) | Jan 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [059e72c9a0](https://linux-hardware.org/?probe=059e72c9a0) | Jan 03, 2023 |
| MSI           | Raider GE76 12UGS           | Notebook    | [8552e25872](https://linux-hardware.org/?probe=8552e25872) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [2e2e7afb8a](https://linux-hardware.org/?probe=2e2e7afb8a) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | Notebook    | [d8d521b964](https://linux-hardware.org/?probe=d8d521b964) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | Notebook    | [54bd1d5aae](https://linux-hardware.org/?probe=54bd1d5aae) | Jan 03, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [27a4df28b2](https://linux-hardware.org/?probe=27a4df28b2) | Jan 03, 2023 |
| MSI           | Alpha 17 B5EEK              | Notebook    | [a5881c627c](https://linux-hardware.org/?probe=a5881c627c) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | Notebook    | [ccebb5dd27](https://linux-hardware.org/?probe=ccebb5dd27) | Jan 02, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [54403a8bbf](https://linux-hardware.org/?probe=54403a8bbf) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a35156e0c3](https://linux-hardware.org/?probe=a35156e0c3) | Jan 02, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [3140fe0512](https://linux-hardware.org/?probe=3140fe0512) | Jan 02, 2023 |
| MSI           | Prestige 14 A10RAS          | Notebook    | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [20c4d1a764](https://linux-hardware.org/?probe=20c4d1a764) | Jan 02, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [e75694d9a6](https://linux-hardware.org/?probe=e75694d9a6) | Jan 02, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [0fb41a5066](https://linux-hardware.org/?probe=0fb41a5066) | Jan 02, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [9346b2e1bc](https://linux-hardware.org/?probe=9346b2e1bc) | Jan 01, 2023 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [a96e5b892b](https://linux-hardware.org/?probe=a96e5b892b) | Jan 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a5b2453630](https://linux-hardware.org/?probe=a5b2453630) | Jan 01, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | Notebook    | [8eada9744e](https://linux-hardware.org/?probe=8eada9744e) | Jan 01, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| ASUSTek       | G15CF                       | Desktop     | [93e783c74a](https://linux-hardware.org/?probe=93e783c74a) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [2c31fd54e4](https://linux-hardware.org/?probe=2c31fd54e4) | Jan 01, 2023 |
| Acer          | Spin SP513-54N              | Convertible | [0cb6dfa7ce](https://linux-hardware.org/?probe=0cb6dfa7ce) | Dec 31, 2022 |
| Dell          | 0PTTT9 A00                  | Desktop     | [7f2851fcf5](https://linux-hardware.org/?probe=7f2851fcf5) | Dec 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [c4eccac7c7](https://linux-hardware.org/?probe=c4eccac7c7) | Dec 31, 2022 |
| MSI           | B360M BAZOOKA               | Desktop     | [ad26afeb83](https://linux-hardware.org/?probe=ad26afeb83) | Dec 31, 2022 |
| HP            | Notebook                    | Notebook    | [d25df9daf4](https://linux-hardware.org/?probe=d25df9daf4) | Dec 31, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [d326e34afc](https://linux-hardware.org/?probe=d326e34afc) | Dec 31, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| Radxa         | ROCK 5B                     | Soc         | [d864d2a31b](https://linux-hardware.org/?probe=d864d2a31b) | Dec 30, 2022 |
| Notebook      | P17SM                       | Notebook    | [18605208b6](https://linux-hardware.org/?probe=18605208b6) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | Notebook    | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [5e6dc18098](https://linux-hardware.org/?probe=5e6dc18098) | Dec 30, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [fdd6af96b3](https://linux-hardware.org/?probe=fdd6af96b3) | Dec 30, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [1c7a329282](https://linux-hardware.org/?probe=1c7a329282) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [816ab16fd0](https://linux-hardware.org/?probe=816ab16fd0) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [43e6103cd0](https://linux-hardware.org/?probe=43e6103cd0) | Dec 29, 2022 |
| BESSTAR Te... | HM80                        | Desktop     | [9af0f05e7e](https://linux-hardware.org/?probe=9af0f05e7e) | Dec 29, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [87e8ae1350](https://linux-hardware.org/?probe=87e8ae1350) | Dec 29, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Carbon Sys... | Iridium 14                  | Notebook    | [d2275f6785](https://linux-hardware.org/?probe=d2275f6785) | Dec 29, 2022 |
| HP            | 8399                        | Desktop     | [204c8c0a3f](https://linux-hardware.org/?probe=204c8c0a3f) | Dec 29, 2022 |
| Acer          | Aspire X3960                | Desktop     | [f045d61192](https://linux-hardware.org/?probe=f045d61192) | Dec 29, 2022 |
| Acer          | Aspire X3960                | Desktop     | [75e053c90f](https://linux-hardware.org/?probe=75e053c90f) | Dec 29, 2022 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [52b38cee5c](https://linux-hardware.org/?probe=52b38cee5c) | Dec 28, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [742c9ebcca](https://linux-hardware.org/?probe=742c9ebcca) | Dec 28, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [9e95c7e7c7](https://linux-hardware.org/?probe=9e95c7e7c7) | Dec 28, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [f58bb411b8](https://linux-hardware.org/?probe=f58bb411b8) | Dec 28, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [2c2bf7f512](https://linux-hardware.org/?probe=2c2bf7f512) | Dec 28, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [19f962298b](https://linux-hardware.org/?probe=19f962298b) | Dec 28, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [3d9a51ce6e](https://linux-hardware.org/?probe=3d9a51ce6e) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [9d2542cf36](https://linux-hardware.org/?probe=9d2542cf36) | Dec 27, 2022 |
| Dell          | 0PV9DG A01                  | Server      | [7f408923fa](https://linux-hardware.org/?probe=7f408923fa) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | Notebook    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [f2998cdede](https://linux-hardware.org/?probe=f2998cdede) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [4a2d0b56d6](https://linux-hardware.org/?probe=4a2d0b56d6) | Dec 27, 2022 |
| HP            | Beats 15                    | Notebook    | [d000f23d61](https://linux-hardware.org/?probe=d000f23d61) | Dec 27, 2022 |
| Dell          | Inspiron 5775               | Notebook    | [cfb1c3fcd6](https://linux-hardware.org/?probe=cfb1c3fcd6) | Dec 26, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | Notebook    | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [227a5cc570](https://linux-hardware.org/?probe=227a5cc570) | Dec 26, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9df04c213d](https://linux-hardware.org/?probe=9df04c213d) | Dec 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8d9b11c617](https://linux-hardware.org/?probe=8d9b11c617) | Dec 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [d66772a936](https://linux-hardware.org/?probe=d66772a936) | Dec 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Kubuntu 20.04   | 1407      | 35.34%  |
| Kubuntu 22.04   | 890       | 22.36%  |
| Kubuntu 22.10   | 295       | 7.41%   |
| Kubuntu 20.10   | 256       | 6.43%   |
| Kubuntu 21.10   | 242       | 6.08%   |
| Kubuntu 21.04   | 214       | 5.38%   |
| Kubuntu 18.04   | 201       | 5.05%   |
| Kubuntu 19.10   | 178       | 4.47%   |
| Kubuntu 23.04   | 117       | 2.94%   |
| Kubuntu 11      | 90        | 2.26%   |
| Kubuntu 11.1    | 26        | 0.65%   |
| Kubuntu 19.04   | 22        | 0.55%   |
| Kubuntu 16.04   | 13        | 0.33%   |
| Kubuntu         | 8         | 0.2%    |
| Kubuntu 18.10   | 7         | 0.18%   |
| Kubuntu 2.0     | 6         | 0.15%   |
| Kubuntu 17.10   | 3         | 0.08%   |
| Kubuntu 17.04   | 2         | 0.05%   |
| Kubuntu 14.04   | 2         | 0.05%   |
| Kubuntu 20.08.3 | 1         | 0.03%   |
| Kubuntu 12.04   | 1         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Kubuntu | 3802      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 103       | 2.36%   |
| 5.15.0-52-generic | 84        | 1.92%   |
| 5.15.0-56-generic | 79        | 1.81%   |
| 6.2.0-20-generic  | 72        | 1.65%   |
| 5.19.0-35-generic | 70        | 1.6%    |
| 5.4.0-52-generic  | 68        | 1.56%   |
| 5.4.0-58-generic  | 59        | 1.35%   |
| 5.4.0-48-generic  | 59        | 1.35%   |
| 5.15.0-48-generic | 58        | 1.33%   |
| 5.15.0-46-generic | 53        | 1.21%   |
| 5.13.0-39-generic | 53        | 1.21%   |
| 5.19.0-23-generic | 52        | 1.19%   |
| 5.4.0-40-generic  | 47        | 1.08%   |
| 5.19.0-38-generic | 47        | 1.08%   |
| 5.13.0-28-generic | 44        | 1.01%   |
| 5.19.0-31-generic | 43        | 0.98%   |
| 5.19.0-26-generic | 42        | 0.96%   |
| 5.15.0-58-generic | 42        | 0.96%   |
| 5.15.0-43-generic | 42        | 0.96%   |
| 5.15.0-47-generic | 40        | 0.92%   |
| 5.15.0-41-generic | 39        | 0.89%   |
| 5.11.0-37-generic | 38        | 0.87%   |
| 5.11.0-25-generic | 38        | 0.87%   |
| 5.15.0-53-generic | 37        | 0.85%   |
| 5.13.0-30-generic | 37        | 0.85%   |
| 5.4.0-47-generic  | 36        | 0.82%   |
| 5.4.0-65-generic  | 35        | 0.8%    |
| 5.8.0-48-generic  | 34        | 0.78%   |
| 5.3.0-40-generic  | 34        | 0.78%   |
| 5.4.0-37-generic  | 33        | 0.76%   |
| 5.4.0-29-generic  | 33        | 0.76%   |
| 5.19.0-29-generic | 32        | 0.73%   |
| 5.15.0-60-generic | 32        | 0.73%   |
| 5.13.0-22-generic | 32        | 0.73%   |
| 5.4.0-45-generic  | 30        | 0.69%   |
| 5.8.0-50-generic  | 29        | 0.66%   |
| 5.15.0-67-generic | 29        | 0.66%   |
| 5.13.0-35-generic | 29        | 0.66%   |
| 5.8.0-63-generic  | 28        | 0.64%   |
| 5.4.0-54-generic  | 28        | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 942       | 23.25%  |
| 5.15.0  | 808       | 19.95%  |
| 5.13.0  | 409       | 10.1%   |
| 5.8.0   | 406       | 10.02%  |
| 5.19.0  | 405       | 10%     |
| 5.11.0  | 327       | 8.07%   |
| 5.3.0   | 224       | 5.53%   |
| 6.2.0   | 99        | 2.44%   |
| 4.15.0  | 69        | 1.7%    |
| 5.0.0   | 36        | 0.89%   |
| 5.17.0  | 21        | 0.52%   |
| 5.10.0  | 18        | 0.44%   |
| 5.6.0   | 15        | 0.37%   |
| 4.4.0   | 10        | 0.25%   |
| 6.0.0   | 9         | 0.22%   |
| 6.1.0   | 8         | 0.2%    |
| 5.14.0  | 8         | 0.2%    |
| 4.18.0  | 8         | 0.2%    |
| 6.0.9   | 5         | 0.12%   |
| 5.9.0   | 5         | 0.12%   |
| 5.7.0   | 4         | 0.1%    |
| 6.3.8   | 3         | 0.07%   |
| 6.3.1   | 3         | 0.07%   |
| 6.1.5   | 3         | 0.07%   |
| 5.8.18  | 3         | 0.07%   |
| 5.18.4  | 3         | 0.07%   |
| 5.18.10 | 3         | 0.07%   |
| 5.16.0  | 3         | 0.07%   |
| 5.12.8  | 3         | 0.07%   |
| 5.12.0  | 3         | 0.07%   |
| 4.13.0  | 3         | 0.07%   |
| 4.10.0  | 3         | 0.07%   |
| 6.3.6   | 2         | 0.05%   |
| 6.3.4   | 2         | 0.05%   |
| 6.2.5   | 2         | 0.05%   |
| 6.2.2   | 2         | 0.05%   |
| 6.1.9   | 2         | 0.05%   |
| 6.1.8   | 2         | 0.05%   |
| 6.1.12  | 2         | 0.05%   |
| 6.1.11  | 2         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 949       | 23.46%  |
| 5.15    | 822       | 20.32%  |
| 5.8     | 422       | 10.43%  |
| 5.13    | 419       | 10.36%  |
| 5.19    | 411       | 10.16%  |
| 5.11    | 333       | 8.23%   |
| 5.3     | 227       | 5.61%   |
| 6.2     | 107       | 2.65%   |
| 4.15    | 70        | 1.73%   |
| 5.0     | 37        | 0.91%   |
| 5.10    | 30        | 0.74%   |
| 5.17    | 28        | 0.69%   |
| 6.1     | 23        | 0.57%   |
| 6.0     | 21        | 0.52%   |
| 5.6     | 20        | 0.49%   |
| 5.14    | 17        | 0.42%   |
| 6.3     | 14        | 0.35%   |
| 5.9     | 13        | 0.32%   |
| 5.12    | 13        | 0.32%   |
| 5.18    | 12        | 0.3%    |
| 5.7     | 11        | 0.27%   |
| 5.16    | 10        | 0.25%   |
| 4.4     | 10        | 0.25%   |
| 4.18    | 10        | 0.25%   |
| 5.5     | 5         | 0.12%   |
| 4.13    | 3         | 0.07%   |
| 4.10    | 3         | 0.07%   |
| 5.1     | 2         | 0.05%   |
| 4.17    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 3.13    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3784      | 99.53%  |
| i686    | 12        | 0.32%   |
| aarch64 | 5         | 0.13%   |
| riscv64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 2897      | 74.86%  |
| KDE        | 914       | 23.62%  |
| GNOME      | 20        | 0.52%   |
| Cinnamon   | 11        | 0.28%   |
| Budgie     | 8         | 0.21%   |
| MATE       | 6         | 0.16%   |
| XFCE       | 3         | 0.08%   |
| LXQt       | 3         | 0.08%   |
| KDE4       | 3         | 0.08%   |
| X-Cinnamon | 1         | 0.03%   |
| Unity      | 1         | 0.03%   |
| i3         | 1         | 0.03%   |
| GNUstep    | 1         | 0.03%   |
| Unknown    | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3641      | 95.14%  |
| Wayland | 143       | 3.74%   |
| Tty     | 42        | 1.1%    |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 2270      | 58.57%  |
| Unknown | 1335      | 34.44%  |
| GDM     | 111       | 2.86%   |
| GDM3    | 72        | 1.86%   |
| LightDM | 64        | 1.65%   |
| TDM     | 21        | 0.54%   |
| SLiM    | 2         | 0.05%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1628      | 42.43%  |
| de_DE   | 315       | 8.21%   |
| ru_RU   | 197       | 5.13%   |
| en_GB   | 180       | 4.69%   |
| fr_FR   | 177       | 4.61%   |
| pt_BR   | 169       | 4.4%    |
| it_IT   | 162       | 4.22%   |
| en_CA   | 81        | 2.11%   |
| es_ES   | 78        | 2.03%   |
| Unknown | 77        | 2.01%   |
| en_AU   | 74        | 1.93%   |
| pl_PL   | 70        | 1.82%   |
| en_IN   | 70        | 1.82%   |
| C       | 39        | 1.02%   |
| hu_HU   | 30        | 0.78%   |
| es_MX   | 26        | 0.68%   |
| ru_UA   | 23        | 0.6%    |
| nl_NL   | 22        | 0.57%   |
| es_AR   | 22        | 0.57%   |
| en_ZA   | 22        | 0.57%   |
| de_AT   | 21        | 0.55%   |
| cs_CZ   | 21        | 0.55%   |
| en_NZ   | 18        | 0.47%   |
| tr_TR   | 15        | 0.39%   |
| sv_SE   | 13        | 0.34%   |
| de_CH   | 13        | 0.34%   |
| pt_PT   | 12        | 0.31%   |
| zh_CN   | 11        | 0.29%   |
| es_CO   | 11        | 0.29%   |
| es_CL   | 11        | 0.29%   |
| en_IE   | 11        | 0.29%   |
| el_GR   | 11        | 0.29%   |
| en_PH   | 10        | 0.26%   |
| es_VE   | 9         | 0.23%   |
| en_IL   | 9         | 0.23%   |
| uk_UA   | 8         | 0.21%   |
| nl_BE   | 8         | 0.21%   |
| fr_BE   | 8         | 0.21%   |
| fi_FI   | 8         | 0.21%   |
| sl_SI   | 7         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2125      | 54.99%  |
| BIOS | 1739      | 45.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3451      | 90.03%  |
| Btrfs    | 155       | 4.04%   |
| Overlay  | 97        | 2.53%   |
| Tmpfs    | 46        | 1.2%    |
| Xfs      | 37        | 0.97%   |
| Zfs      | 21        | 0.55%   |
| Unknown  | 12        | 0.31%   |
| Ext3     | 5         | 0.13%   |
| Ext2     | 4         | 0.1%    |
| XXXX     | 1         | 0.03%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |
| F2fs     | 1         | 0.03%   |
| ExX4     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1948      | 50.34%  |
| Unknown | 1574      | 40.67%  |
| MBR     | 348       | 8.99%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3335      | 86.76%  |
| Yes       | 509       | 13.24%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2366      | 61.53%  |
| Yes       | 1479      | 38.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 621       | 16.33%  |
| Lenovo              | 583       | 15.33%  |
| Dell                | 524       | 13.78%  |
| Hewlett-Packard     | 506       | 13.31%  |
| Gigabyte Technology | 304       | 8%      |
| MSI                 | 253       | 6.65%   |
| Acer                | 178       | 4.68%   |
| ASRock              | 134       | 3.52%   |
| Apple               | 59        | 1.55%   |
| Samsung Electronics | 47        | 1.24%   |
| Intel               | 45        | 1.18%   |
| HUAWEI              | 44        | 1.16%   |
| Unknown             | 29        | 0.76%   |
| Toshiba             | 25        | 0.66%   |
| Notebook            | 24        | 0.63%   |
| Google              | 23        | 0.6%    |
| Fujitsu             | 22        | 0.58%   |
| Sony                | 21        | 0.55%   |
| TUXEDO              | 19        | 0.5%    |
| Alienware           | 16        | 0.42%   |
| Pegatron            | 14        | 0.37%   |
| Timi                | 13        | 0.34%   |
| Positivo            | 13        | 0.34%   |
| Medion              | 13        | 0.34%   |
| Biostar             | 13        | 0.34%   |
| Foxconn             | 10        | 0.26%   |
| AZW                 | 10        | 0.26%   |
| Supermicro          | 9         | 0.24%   |
| Packard Bell        | 9         | 0.24%   |
| Microsoft           | 9         | 0.24%   |
| ZOTAC               | 8         | 0.21%   |
| PC Specialist       | 8         | 0.21%   |
| ECS                 | 8         | 0.21%   |
| Chuwi               | 8         | 0.21%   |
| System76            | 7         | 0.18%   |
| Shuttle             | 6         | 0.16%   |
| Razer               | 6         | 0.16%   |
| LG Electronics      | 6         | 0.16%   |
| Huanan              | 6         | 0.16%   |
| GPU Company         | 6         | 0.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 46        | 1.21%   |
| Unknown                            | 43        | 1.13%   |
| Gigabyte B450M DS3H                | 11        | 0.29%   |
| ASUS ROG STRIX B550-F GAMING       | 11        | 0.29%   |
| HP Notebook                        | 10        | 0.26%   |
| MSI MS-7C37                        | 9         | 0.24%   |
| MSI MS-7B79                        | 9         | 0.24%   |
| HP Pavilion g6                     | 9         | 0.24%   |
| HP Pavilion dv6                    | 9         | 0.24%   |
| Dell XPS 15 9560                   | 9         | 0.24%   |
| Dell OptiPlex 9020                 | 9         | 0.24%   |
| Dell OptiPlex 7010                 | 9         | 0.24%   |
| HUAWEI NBLK-WAX9X                  | 8         | 0.21%   |
| ASUS ROG STRIX X570-E GAMING       | 8         | 0.21%   |
| ASUS PRIME B350-PLUS               | 8         | 0.21%   |
| MSI MS-7C91                        | 7         | 0.18%   |
| MSI MS-7817                        | 7         | 0.18%   |
| HP Pavilion dv7                    | 7         | 0.18%   |
| Gigabyte X570 AORUS MASTER         | 7         | 0.18%   |
| Gigabyte A320M-S2H                 | 7         | 0.18%   |
| Gigabyte 970A-DS3P                 | 7         | 0.18%   |
| Dell XPS 15 9570                   | 7         | 0.18%   |
| ASUS PRIME B450M-A                 | 7         | 0.18%   |
| ASUS PRIME A320M-K                 | 7         | 0.18%   |
| MSI MS-7A34                        | 6         | 0.16%   |
| MSI MS-7693                        | 6         | 0.16%   |
| HUAWEI HVY-WXX9                    | 6         | 0.16%   |
| HP Pavilion 15                     | 6         | 0.16%   |
| HP ENVY x360 Convertible 13-ay0xxx | 6         | 0.16%   |
| HP EliteBook 840 G5                | 6         | 0.16%   |
| HP EliteBook 840 G3                | 6         | 0.16%   |
| Dell XPS 15 7590                   | 6         | 0.16%   |
| Dell Latitude 5480                 | 6         | 0.16%   |
| ASRock A320M-HDV R4.0              | 6         | 0.16%   |
| MSI MS-7C02                        | 5         | 0.13%   |
| HP EliteBook 840 G6                | 5         | 0.13%   |
| HP Compaq Elite 8300 SFF           | 5         | 0.13%   |
| HP 255 G8 Notebook PC              | 5         | 0.13%   |
| GPU Company GWTC116-2              | 5         | 0.13%   |
| Dell XPS 8700                      | 5         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 271       | 7.13%   |
| Dell Latitude      | 138       | 3.63%   |
| Dell Inspiron      | 129       | 3.39%   |
| Acer Aspire        | 113       | 2.97%   |
| Lenovo IdeaPad     | 109       | 2.87%   |
| HP Pavilion        | 103       | 2.71%   |
| ASUS ROG           | 86        | 2.26%   |
| ASUS PRIME         | 82        | 2.16%   |
| Dell XPS           | 77        | 2.03%   |
| HP ProBook         | 63        | 1.66%   |
| HP EliteBook       | 61        | 1.6%    |
| Dell Precision     | 56        | 1.47%   |
| HP Laptop          | 54        | 1.42%   |
| Dell OptiPlex      | 53        | 1.39%   |
| ASUS VivoBook      | 50        | 1.32%   |
| ASUS All           | 46        | 1.21%   |
| ASUS TUF           | 44        | 1.16%   |
| Unknown            | 43        | 1.13%   |
| Lenovo ThinkCentre | 34        | 0.89%   |
| HP ENVY            | 32        | 0.84%   |
| HP Compaq          | 32        | 0.84%   |
| Dell Vostro        | 31        | 0.82%   |
| Lenovo Yoga        | 29        | 0.76%   |
| Lenovo Legion      | 25        | 0.66%   |
| Acer Nitro         | 25        | 0.66%   |
| Lenovo ThinkBook   | 22        | 0.58%   |
| ASUS ASUS          | 22        | 0.58%   |
| Toshiba Satellite  | 21        | 0.55%   |
| ASUS ZenBook       | 20        | 0.53%   |
| Gigabyte B450M     | 19        | 0.5%    |
| Gigabyte X570      | 18        | 0.47%   |
| Acer Swift         | 18        | 0.47%   |
| HP ZBook           | 13        | 0.34%   |
| HP Spectre         | 11        | 0.29%   |
| HP EliteDesk       | 11        | 0.29%   |
| Gigabyte B550      | 11        | 0.29%   |
| Gigabyte A320M-S2H | 11        | 0.29%   |
| Dell G3            | 11        | 0.29%   |
| ASUS M5A78L-M      | 11        | 0.29%   |
| HP Notebook        | 10        | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 464       | 12.2%   |
| 2019    | 453       | 11.91%  |
| 2018    | 414       | 10.89%  |
| 2021    | 334       | 8.78%   |
| 2017    | 282       | 7.42%   |
| 2012    | 258       | 6.79%   |
| 2013    | 254       | 6.68%   |
| 2014    | 226       | 5.94%   |
| 2011    | 218       | 5.73%   |
| 2016    | 183       | 4.81%   |
| 2015    | 174       | 4.58%   |
| 2022    | 154       | 4.05%   |
| 2010    | 121       | 3.18%   |
| 2008    | 98        | 2.58%   |
| 2009    | 95        | 2.5%    |
| 2007    | 38        | 1%      |
| 2023    | 16        | 0.42%   |
| 2006    | 9         | 0.24%   |
| Unknown | 7         | 0.18%   |
| 2005    | 3         | 0.08%   |
| 2004    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2113      | 55.58%  |
| Desktop        | 1414      | 37.19%  |
| Convertible    | 129       | 3.39%   |
| Mini pc        | 58        | 1.53%   |
| All in one     | 42        | 1.1%    |
| Tablet         | 26        | 0.68%   |
| Server         | 15        | 0.39%   |
| System on chip | 5         | 0.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3482      | 90.96%  |
| Enabled  | 346       | 9.04%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3773      | 99.24%  |
| Yes  | 29        | 0.76%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 987       | 25.74%  |
| 4.01-8.0        | 848       | 22.12%  |
| 8.01-16.0       | 715       | 18.65%  |
| 32.01-64.0      | 526       | 13.72%  |
| 3.01-4.0        | 442       | 11.53%  |
| 64.01-256.0     | 132       | 3.44%   |
| 24.01-32.0      | 105       | 2.74%   |
| 1.01-2.0        | 53        | 1.38%   |
| 2.01-3.0        | 23        | 0.6%    |
| More than 256.0 | 3         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 1060      | 25.78%  |
| 4.01-8.0    | 971       | 23.62%  |
| 1.01-2.0    | 919       | 22.35%  |
| 3.01-4.0    | 703       | 17.1%   |
| 8.01-16.0   | 293       | 7.13%   |
| 0.51-1.0    | 88        | 2.14%   |
| 16.01-24.0  | 47        | 1.14%   |
| 24.01-32.0  | 13        | 0.32%   |
| 32.01-64.0  | 9         | 0.22%   |
| 0.01-0.5    | 6         | 0.15%   |
| 64.01-256.0 | 1         | 0.02%   |
| Unknown     | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2099      | 53.74%  |
| 2      | 1052      | 26.93%  |
| 3      | 357       | 9.14%   |
| 4      | 196       | 5.02%   |
| 5      | 98        | 2.51%   |
| 6      | 45        | 1.15%   |
| 7      | 27        | 0.69%   |
| 0      | 13        | 0.33%   |
| 8      | 6         | 0.15%   |
| 9      | 5         | 0.13%   |
| 10     | 3         | 0.08%   |
| 12     | 2         | 0.05%   |
| 11     | 2         | 0.05%   |
| 13     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2599      | 67.86%  |
| Yes       | 1231      | 32.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3200      | 84.06%  |
| No        | 607       | 15.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2969      | 77.72%  |
| No        | 851       | 22.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2555      | 66.64%  |
| No        | 1279      | 33.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 747       | 19.6%   |
| Germany      | 424       | 11.12%  |
| Russia       | 263       | 6.9%    |
| France       | 220       | 5.77%   |
| Brazil       | 219       | 5.75%   |
| Italy        | 207       | 5.43%   |
| UK           | 169       | 4.43%   |
| Spain        | 113       | 2.96%   |
| Canada       | 98        | 2.57%   |
| Poland       | 96        | 2.52%   |
| Netherlands  | 89        | 2.33%   |
| India        | 73        | 1.92%   |
| Australia    | 72        | 1.89%   |
| Ukraine      | 63        | 1.65%   |
| Mexico       | 48        | 1.26%   |
| Hungary      | 46        | 1.21%   |
| Switzerland  | 44        | 1.15%   |
| Czechia      | 38        | 1%      |
| Belgium      | 37        | 0.97%   |
| Argentina    | 35        | 0.92%   |
| Austria      | 33        | 0.87%   |
| Turkey       | 31        | 0.81%   |
| Sweden       | 27        | 0.71%   |
| Indonesia    | 27        | 0.71%   |
| Greece       | 26        | 0.68%   |
| South Africa | 24        | 0.63%   |
| Bulgaria     | 24        | 0.63%   |
| Finland      | 23        | 0.6%    |
| Portugal     | 22        | 0.58%   |
| Slovenia     | 21        | 0.55%   |
| Romania      | 21        | 0.55%   |
| Denmark      | 20        | 0.52%   |
| Serbia       | 18        | 0.47%   |
| New Zealand  | 18        | 0.47%   |
| Colombia     | 18        | 0.47%   |
| China        | 16        | 0.42%   |
| Belarus      | 16        | 0.42%   |
| Slovakia     | 15        | 0.39%   |
| Chile        | 15        | 0.39%   |
| Israel       | 14        | 0.37%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 73        | 1.83%   |
| Berlin            | 42        | 1.06%   |
| Paris             | 37        | 0.93%   |
| St Petersburg     | 31        | 0.78%   |
| Milan             | 30        | 0.75%   |
| Hamburg           | 29        | 0.73%   |
| Warsaw            | 28        | 0.7%    |
| Rome              | 25        | 0.63%   |
| Sao Paulo         | 24        | 0.6%    |
| Madrid            | 22        | 0.55%   |
| Budapest          | 21        | 0.53%   |
| Sydney            | 20        | 0.5%    |
| Amsterdam         | 20        | 0.5%    |
| Vienna            | 19        | 0.48%   |
| Rio de Janeiro    | 19        | 0.48%   |
| Munich            | 19        | 0.48%   |
| Cologne           | 19        | 0.48%   |
| Kyiv              | 18        | 0.45%   |
| Zurich            | 17        | 0.43%   |
| London            | 17        | 0.43%   |
| Melbourne         | 16        | 0.4%    |
| Frankfurt am Main | 16        | 0.4%    |
| Prague            | 14        | 0.35%   |
| Dallas            | 14        | 0.35%   |
| Sofia             | 13        | 0.33%   |
| Minsk             | 13        | 0.33%   |
| Seattle           | 12        | 0.3%    |
| Novosibirsk       | 12        | 0.3%    |
| Montreal          | 12        | 0.3%    |
| Jakarta           | 12        | 0.3%    |
| Belgrade          | 12        | 0.3%    |
| Athens            | 12        | 0.3%    |
| Los Angeles       | 11        | 0.28%   |
| Auckland          | 11        | 0.28%   |
| Wroclaw           | 10        | 0.25%   |
| Phoenix           | 10        | 0.25%   |
| Miami             | 10        | 0.25%   |
| Leipzig           | 10        | 0.25%   |
| Krakow            | 10        | 0.25%   |
| Dublin            | 10        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1073      | 1638   | 17.94%  |
| WDC                         | 877       | 1385   | 14.66%  |
| Seagate                     | 765       | 1160   | 12.79%  |
| Toshiba                     | 353       | 475    | 5.9%    |
| Kingston                    | 351       | 419    | 5.87%   |
| SanDisk                     | 325       | 404    | 5.43%   |
| Crucial                     | 242       | 299    | 4.05%   |
| Unknown                     | 202       | 253    | 3.38%   |
| Intel                       | 181       | 240    | 3.03%   |
| SK hynix                    | 157       | 188    | 2.62%   |
| Hitachi                     | 151       | 185    | 2.52%   |
| Micron Technology           | 110       | 122    | 1.84%   |
| HGST                        | 110       | 140    | 1.84%   |
| A-DATA Technology           | 89        | 96     | 1.49%   |
| Phison                      | 51        | 66     | 0.85%   |
| KIOXIA                      | 49        | 56     | 0.82%   |
| China                       | 45        | 61     | 0.75%   |
| Silicon Motion              | 36        | 41     | 0.6%    |
| PNY                         | 35        | 45     | 0.59%   |
| Apple                       | 35        | 41     | 0.59%   |
| SPCC                        | 33        | 42     | 0.55%   |
| Intenso                     | 30        | 34     | 0.5%    |
| Transcend                   | 28        | 30     | 0.47%   |
| Patriot                     | 28        | 39     | 0.47%   |
| Phison Electronics          | 25        | 25     | 0.42%   |
| OCZ                         | 25        | 32     | 0.42%   |
| Maxtor                      | 24        | 27     | 0.4%    |
| LITEON                      | 24        | 26     | 0.4%    |
| Corsair                     | 23        | 36     | 0.38%   |
| Micron/Crucial Technology   | 21        | 27     | 0.35%   |
| Unknown                     | 20        | 21     | 0.33%   |
| JMicron Technology          | 19        | 21     | 0.32%   |
| GOODRAM                     | 19        | 34     | 0.32%   |
| XPG                         | 14        | 15     | 0.23%   |
| SABRENT                     | 14        | 17     | 0.23%   |
| LITEONIT                    | 14        | 16     | 0.23%   |
| Team                        | 13        | 14     | 0.22%   |
| KingSpec                    | 13        | 15     | 0.22%   |
| Gigabyte Technology         | 13        | 14     | 0.22%   |
| Kingston Technology Company | 12        | 13     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 60        | 0.89%   |
| Kingston SA400S37240G 240GB SSD                     | 59        | 0.88%   |
| Samsung SSD 850 EVO 250GB                           | 51        | 0.76%   |
| Samsung SSD 850 EVO 500GB                           | 49        | 0.73%   |
| Kingston SA400S37480G 480GB SSD                     | 42        | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB                      | 41        | 0.61%   |
| Samsung SSD 860 EVO 1TB                             | 39        | 0.58%   |
| Crucial CT1000MX500SSD1 1TB                         | 36        | 0.54%   |
| Unknown MMC Card  32GB                              | 34        | 0.51%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 34        | 0.51%   |
| Samsung NVMe SSD Drive 500GB                        | 33        | 0.49%   |
| Unknown MMC Card  64GB                              | 31        | 0.46%   |
| Toshiba MQ04ABF100 1TB                              | 31        | 0.46%   |
| Toshiba MQ01ABD100 1TB                              | 31        | 0.46%   |
| Samsung SSD 970 EVO Plus 1TB                        | 31        | 0.46%   |
| HGST HTS721010A9E630 1TB                            | 31        | 0.46%   |
| Samsung NVMe SSD Drive 1TB                          | 30        | 0.45%   |
| Samsung SSD 970 EVO Plus 500GB                      | 29        | 0.43%   |
| Samsung NVMe SSD Drive 512GB                        | 28        | 0.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 28        | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 26        | 0.39%   |
| Samsung SSD 860 EVO 250GB                           | 26        | 0.39%   |
| Seagate ST4000DM004-2CV104 4TB                      | 25        | 0.37%   |
| Seagate ST500DM002-1BD142 500GB                     | 24        | 0.36%   |
| Seagate ST1000DM010-2EP102 1TB                      | 24        | 0.36%   |
| Toshiba HDWD110 1TB                                 | 23        | 0.34%   |
| Toshiba DT01ACA100 1TB                              | 23        | 0.34%   |
| Seagate ST1000DM003-1CH162 1TB                      | 23        | 0.34%   |
| Seagate ST2000DM008-2FR102 2TB                      | 22        | 0.33%   |
| Seagate ST1000DM003-1ER162 1TB                      | 22        | 0.33%   |
| Kingston SA400S37120G 120GB SSD                     | 22        | 0.33%   |
| Seagate Expansion 1TB                               | 21        | 0.31%   |
| SanDisk SSD PLUS 240GB                              | 21        | 0.31%   |
| Crucial CT500MX500SSD1 500GB                        | 21        | 0.31%   |
| Seagate ST500LT012-1DG142 500GB                     | 20        | 0.3%    |
| Seagate ST2000DM001-1ER164 2TB                      | 20        | 0.3%    |
| SanDisk NVMe SSD Drive 512GB                        | 20        | 0.3%    |
| Unknown                                             | 20        | 0.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 19        | 0.28%   |
| Samsung SSD 840 EVO 250GB                           | 19        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 746       | 1122   | 35.47%  |
| WDC                 | 659       | 1075   | 31.34%  |
| Toshiba             | 244       | 331    | 11.6%   |
| Hitachi             | 151       | 185    | 7.18%   |
| HGST                | 109       | 139    | 5.18%   |
| Samsung Electronics | 104       | 159    | 4.95%   |
| Maxtor              | 23        | 26     | 1.09%   |
| Unknown             | 22        | 26     | 1.05%   |
| Apple               | 13        | 13     | 0.62%   |
| Fujitsu             | 10        | 13     | 0.48%   |
| Hewlett-Packard     | 3         | 5      | 0.14%   |
| USB3.0              | 2         | 2      | 0.1%    |
| SAGE                | 2         | 2      | 0.1%    |
| JMicron Technology  | 2         | 2      | 0.1%    |
| ASMT                | 2         | 2      | 0.1%    |
| WD MediaMax         | 1         | 1      | 0.05%   |
| USB                 | 1         | 1      | 0.05%   |
| Magnetic Data       | 1         | 2      | 0.05%   |
| LIO-ORG             | 1         | 1      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| KESU                | 1         | 1      | 0.05%   |
| ipTIME              | 1         | 1      | 0.05%   |
| IET                 | 1         | 1      | 0.05%   |
| HPE                 | 1         | 6      | 0.05%   |
| HGST HTS            | 1         | 1      | 0.05%   |
| ASMedia             | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 542       | 772    | 26.67%  |
| Kingston            | 257       | 305    | 12.65%  |
| Crucial             | 205       | 259    | 10.09%  |
| SanDisk             | 197       | 238    | 9.69%   |
| WDC                 | 108       | 142    | 5.31%   |
| A-DATA Technology   | 63        | 69     | 3.1%    |
| Intel               | 56        | 71     | 2.76%   |
| China               | 44        | 60     | 2.17%   |
| Micron Technology   | 37        | 40     | 1.82%   |
| Toshiba             | 35        | 50     | 1.72%   |
| PNY                 | 31        | 41     | 1.53%   |
| Patriot             | 28        | 39     | 1.38%   |
| SPCC                | 27        | 35     | 1.33%   |
| SK hynix            | 26        | 28     | 1.28%   |
| Intenso             | 26        | 29     | 1.28%   |
| OCZ                 | 25        | 32     | 1.23%   |
| Transcend           | 22        | 22     | 1.08%   |
| LITEON              | 19        | 20     | 0.94%   |
| GOODRAM             | 19        | 34     | 0.94%   |
| LITEONIT            | 14        | 16     | 0.69%   |
| KingSpec            | 13        | 15     | 0.64%   |
| Corsair             | 13        | 24     | 0.64%   |
| Team                | 12        | 12     | 0.59%   |
| Apple               | 12        | 12     | 0.59%   |
| Apacer              | 11        | 16     | 0.54%   |
| Mushkin             | 10        | 11     | 0.49%   |
| Emtec               | 7         | 7      | 0.34%   |
| Verbatim            | 6         | 8      | 0.3%    |
| Plextor             | 6         | 7      | 0.3%    |
| Netac               | 6         | 7      | 0.3%    |
| Lexar               | 6         | 7      | 0.3%    |
| Dogfish             | 6         | 6      | 0.3%    |
| ASMT                | 6         | 7      | 0.3%    |
| Unknown             | 6         | 6      | 0.3%    |
| Seagate             | 5         | 10     | 0.25%   |
| Gigabyte Technology | 5         | 5      | 0.25%   |
| External            | 5         | 6      | 0.25%   |
| Unknown             | 4         | 4      | 0.2%    |
| KingDian            | 4         | 5      | 0.2%    |
| Hewlett-Packard     | 4         | 4      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1742      | 2608   | 32.87%  |
| HDD     | 1698      | 3119   | 32.04%  |
| NVMe    | 1597      | 2154   | 30.13%  |
| MMC     | 178       | 219    | 3.36%   |
| Unknown | 85        | 119    | 1.6%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2651      | 5541   | 57.11%  |
| NVMe | 1581      | 2123   | 34.06%  |
| SAS  | 232       | 336    | 5%      |
| MMC  | 178       | 219    | 3.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1862      | 2925   | 50.6%   |
| 0.51-1.0   | 1146      | 1713   | 31.14%  |
| 1.01-2.0   | 379       | 591    | 10.3%   |
| 3.01-4.0   | 130       | 233    | 3.53%   |
| 2.01-3.0   | 79        | 113    | 2.15%   |
| 4.01-10.0  | 73        | 130    | 1.98%   |
| 10.01-20.0 | 11        | 22     | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 965       | 24.48%  |
| 251-500        | 938       | 23.8%   |
| 501-1000       | 722       | 18.32%  |
| 1001-2000      | 420       | 10.65%  |
| More than 3000 | 301       | 7.64%   |
| 51-100         | 198       | 5.02%   |
| 2001-3000      | 183       | 4.64%   |
| 1-20           | 107       | 2.71%   |
| 21-50          | 91        | 2.31%   |
| Unknown        | 17        | 0.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 920       | 22.65%  |
| 101-250        | 697       | 17.16%  |
| 21-50          | 636       | 15.66%  |
| 51-100         | 540       | 13.29%  |
| 251-500        | 476       | 11.72%  |
| 501-1000       | 357       | 8.79%   |
| 1001-2000      | 213       | 5.24%   |
| More than 3000 | 139       | 3.42%   |
| 2001-3000      | 67        | 1.65%   |
| Unknown        | 17        | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB             | 6         | 7      | 1.44%   |
| Seagate ST500DM002-1BD142 500GB      | 5         | 5      | 1.2%    |
| Seagate ST31000524AS 1TB             | 5         | 6      | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 5      | 1.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 11     | 1.2%    |
| Toshiba MQ04ABF100 1TB               | 4         | 4      | 0.96%   |
| Seagate ST500LT012-9WS142 500GB      | 4         | 4      | 0.96%   |
| Seagate ST1000DM003-1CH162 1TB       | 4         | 9      | 0.96%   |
| Crucial CT525MX300SSD1 528GB         | 4         | 4      | 0.96%   |
| Crucial CT1050MX300SSD1 1050GB       | 4         | 4      | 0.96%   |
| WDC WD5000AAKS-00V1A0 500GB          | 3         | 4      | 0.72%   |
| WDC WD20EFRX-68EUZN0 2TB             | 3         | 6      | 0.72%   |
| Toshiba MQ01ABD100 1TB               | 3         | 5      | 0.72%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 3      | 0.72%   |
| Seagate ST31000528AS 1TB             | 3         | 3      | 0.72%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 3      | 0.72%   |
| Kingston SV300S37A120G 120GB SSD     | 3         | 3      | 0.72%   |
| Hitachi HTS547564A9E384 640GB        | 3         | 3      | 0.72%   |
| HGST HTS545050A7E680 500GB           | 3         | 3      | 0.72%   |
| WDC WD5000AAKS-00A7B0 500GB          | 2         | 2      | 0.48%   |
| WDC WD40EZRZ-00GXCB0 4TB             | 2         | 2      | 0.48%   |
| WDC WD3200JD-22KLB0 320GB            | 2         | 2      | 0.48%   |
| WDC WD30EZRX-00MMMB0 3TB             | 2         | 2      | 0.48%   |
| WDC WD20EARX-00PASB0 2TB             | 2         | 2      | 0.48%   |
| WDC WD15EARS-00Z5B1 1TB              | 2         | 2      | 0.48%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 2      | 0.48%   |
| WDC WD10EZEX-00BN5A0 1TB             | 2         | 2      | 0.48%   |
| WDC WD10EARS-00MVWB0 1TB             | 2         | 4      | 0.48%   |
| WDC WD10EADS-00L5B1 1TB              | 2         | 2      | 0.48%   |
| WDC WD1001FALS-40U9B0 1TB            | 2         | 2      | 0.48%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD | 2         | 2      | 0.48%   |
| Toshiba MQ01ABD075 752GB             | 2         | 3      | 0.48%   |
| Toshiba MK1652GSX 160GB              | 2         | 2      | 0.48%   |
| Toshiba HDWD110 1TB                  | 2         | 2      | 0.48%   |
| SK hynix SC401 SATA 512GB SSD        | 2         | 2      | 0.48%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 2         | 2      | 0.48%   |
| SK hynix BC711 HFM256GD3JX013N 256GB | 2         | 2      | 0.48%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 0.48%   |
| Seagate ST9250315AS 250GB            | 2         | 3      | 0.48%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 2      | 0.48%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 88        | 111    | 21.89%  |
| Seagate             | 88        | 112    | 21.89%  |
| Samsung Electronics | 39        | 50     | 9.7%    |
| Toshiba             | 34        | 39     | 8.46%   |
| Hitachi             | 27        | 27     | 6.72%   |
| Crucial             | 20        | 24     | 4.98%   |
| SanDisk             | 14        | 15     | 3.48%   |
| HGST                | 14        | 15     | 3.48%   |
| Intel               | 12        | 15     | 2.99%   |
| SK hynix            | 11        | 11     | 2.74%   |
| Kingston            | 10        | 10     | 2.49%   |
| A-DATA Technology   | 6         | 6      | 1.49%   |
| Micron Technology   | 5         | 5      | 1.24%   |
| Maxtor              | 5         | 6      | 1.24%   |
| OCZ                 | 4         | 4      | 1%      |
| Apple               | 3         | 3      | 0.75%   |
| LITEONIT            | 2         | 2      | 0.5%    |
| Intenso             | 2         | 2      | 0.5%    |
| Fujitsu             | 2         | 2      | 0.5%    |
| Zheino              | 1         | 2      | 0.25%   |
| XPG                 | 1         | 1      | 0.25%   |
| VISIPRO             | 1         | 2      | 0.25%   |
| VENO                | 1         | 1      | 0.25%   |
| tecmiyo             | 1         | 3      | 0.25%   |
| T-FORCE             | 1         | 1      | 0.25%   |
| SPCC                | 1         | 1      | 0.25%   |
| R580                | 1         | 1      | 0.25%   |
| Phison Electronics  | 1         | 1      | 0.25%   |
| ORTIAL              | 1         | 1      | 0.25%   |
| Neo                 | 1         | 1      | 0.25%   |
| Mushkin             | 1         | 1      | 0.25%   |
| Drevo               | 1         | 1      | 0.25%   |
| BAITITON            | 1         | 3      | 0.25%   |
| ASMT                | 1         | 1      | 0.25%   |
| ASENNO              | 1         | 1      | 0.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 88        | 112    | 32.35%  |
| WDC                 | 86        | 109    | 31.62%  |
| Toshiba             | 29        | 34     | 10.66%  |
| Hitachi             | 27        | 27     | 9.93%   |
| Samsung Electronics | 17        | 26     | 6.25%   |
| HGST                | 14        | 15     | 5.15%   |
| Maxtor              | 5         | 6      | 1.84%   |
| Apple               | 3         | 3      | 1.1%    |
| Fujitsu             | 2         | 2      | 0.74%   |
| ASMT                | 1         | 1      | 0.37%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 249       | 335    | 66.05%  |
| SSD  | 105       | 123    | 27.85%  |
| NVMe | 23        | 23     | 6.1%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 2      | 14.29%  |
| Samsung Electronics HD502IJ 500GB     | 1         | 1      | 14.29%  |
| OCZ VERTEX460A 480GB SSD              | 1         | 1      | 14.29%  |
| Intel SSDSC2KB960G8 960GB             | 1         | 1      | 14.29%  |
| Hitachi HTS547550A9E384 500GB         | 1         | 1      | 14.29%  |
| Acer SSD FA100 256GB                  | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 28.57%  |
| Seagate             | 1         | 1      | 14.29%  |
| OCZ                 | 1         | 1      | 14.29%  |
| Intel               | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 1      | 14.29%  |
| Acer                | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1955      | 3434   | 45.72%  |
| Detected | 1948      | 4296   | 45.56%  |
| Malfunc  | 367       | 481    | 8.58%   |
| Failed   | 6         | 8      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2400      | 47.12%  |
| AMD                              | 854       | 16.77%  |
| Samsung Electronics              | 521       | 10.23%  |
| SanDisk                          | 270       | 5.3%    |
| SK hynix                         | 130       | 2.55%   |
| Kingston Technology Company      | 107       | 2.1%    |
| Phison Electronics               | 94        | 1.85%   |
| Toshiba America Info Systems     | 85        | 1.67%   |
| ASMedia Technology               | 84        | 1.65%   |
| Micron Technology                | 73        | 1.43%   |
| Micron/Crucial Technology        | 58        | 1.14%   |
| Silicon Motion                   | 50        | 0.98%   |
| JMicron Technology               | 50        | 0.98%   |
| KIOXIA                           | 46        | 0.9%    |
| Marvell Technology Group         | 42        | 0.82%   |
| Nvidia                           | 41        | 0.81%   |
| ADATA Technology                 | 40        | 0.79%   |
| Realtek Semiconductor            | 22        | 0.43%   |
| Solid State Storage Technology   | 17        | 0.33%   |
| Union Memory (Shenzhen)          | 15        | 0.29%   |
| Broadcom / LSI                   | 13        | 0.26%   |
| LSI Logic / Symbios Logic        | 11        | 0.22%   |
| Lite-On Technology               | 10        | 0.2%    |
| Silicon Image                    | 9         | 0.18%   |
| Apple                            | 8         | 0.16%   |
| VIA Technologies                 | 7         | 0.14%   |
| Seagate Technology               | 6         | 0.12%   |
| Lenovo                           | 4         | 0.08%   |
| Netac Technology                 | 3         | 0.06%   |
| INNOGRIT                         | 3         | 0.06%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| Silicon Integrated Systems [SiS] | 2         | 0.04%   |
| Shenzhen Longsys Electronics     | 2         | 0.04%   |
| Integrated Technology Express    | 2         | 0.04%   |
| Adaptec                          | 2         | 0.04%   |
| Zhaoxin                          | 1         | 0.02%   |
| Solidigm                         | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 609       | 10.53%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 293       | 5.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 206       | 3.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 187       | 3.23%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 157       | 2.71%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 151       | 2.61%   |
| Intel Volume Management Device NVMe RAID Controller                            | 120       | 2.07%   |
| AMD 400 Series Chipset SATA Controller                                         | 118       | 2.04%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 97        | 1.68%   |
| Samsung NVMe SSD Controller 980                                                | 96        | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 96        | 1.66%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 91        | 1.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 85        | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 84        | 1.45%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 78        | 1.35%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 77        | 1.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 74        | 1.28%   |
| AMD 500 Series Chipset SATA Controller                                         | 74        | 1.28%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 72        | 1.24%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 71        | 1.23%   |
| Intel SSD 660P Series                                                          | 65        | 1.12%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 64        | 1.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 63        | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                          | 61        | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 60        | 1.04%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 59        | 1.02%   |
| Intel SATA Controller [RAID mode]                                              | 57        | 0.99%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 53        | 0.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 52        | 0.9%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 51        | 0.88%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 47        | 0.81%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 46        | 0.8%    |
| Micron NVMe Storage Controller                                                 | 45        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 44        | 0.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 43        | 0.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 43        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 42        | 0.73%   |
| AMD 300 Series Chipset SATA Controller                                         | 42        | 0.73%   |
| AMD FCH SATA Controller D                                                      | 41        | 0.71%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 39        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2788      | 54.59%  |
| NVMe | 1577      | 30.88%  |
| RAID | 382       | 7.48%   |
| IDE  | 338       | 6.62%   |
| SAS  | 14        | 0.27%   |
| SCSI | 8         | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 2729      | 71.78%  |
| AMD           | 1066      | 28.04%  |
| ARM           | 3         | 0.08%   |
| sifive,u74-mc | 1         | 0.03%   |
| QUALCOMM      | 1         | 0.03%   |
| Phytium       | 1         | 0.03%   |
| CentaurHauls  | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 62        | 1.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 50        | 1.31%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 47        | 1.23%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 43        | 1.13%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 40        | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 40        | 1.05%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 39        | 1.02%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 38        | 1%      |
| Intel Core i7-8565U CPU @ 1.80GHz             | 38        | 1%      |
| Intel Core i7-8550U CPU @ 1.80GHz             | 38        | 1%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 38        | 1%      |
| AMD Ryzen 5 3600 6-Core Processor             | 37        | 0.97%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 35        | 0.92%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 35        | 0.92%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 33        | 0.87%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 0.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 30        | 0.79%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 30        | 0.79%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 29        | 0.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 28        | 0.74%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 26        | 0.68%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 25        | 0.66%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 23        | 0.6%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 23        | 0.6%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 23        | 0.6%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 23        | 0.6%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 22        | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 21        | 0.55%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 21        | 0.55%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 20        | 0.53%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 20        | 0.53%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 19        | 0.5%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 19        | 0.5%    |
| AMD FX-8350 Eight-Core Processor              | 19        | 0.5%    |
| Intel 12th Gen Core i7-12700H                 | 18        | 0.47%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 17        | 0.45%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 17        | 0.45%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 17        | 0.45%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 16        | 0.42%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 16        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 885       | 23.23%  |
| Intel Core i5           | 813       | 21.34%  |
| Other                   | 307       | 8.06%   |
| AMD Ryzen 5             | 298       | 7.82%   |
| AMD Ryzen 7             | 256       | 6.72%   |
| Intel Core i3           | 201       | 5.28%   |
| Intel Celeron           | 132       | 3.47%   |
| AMD Ryzen 9             | 91        | 2.39%   |
| Intel Core 2 Duo        | 90        | 2.36%   |
| Intel Xeon              | 85        | 2.23%   |
| AMD FX                  | 67        | 1.76%   |
| Intel Pentium           | 66        | 1.73%   |
| AMD Ryzen 3             | 45        | 1.18%   |
| Intel Core i9           | 35        | 0.92%   |
| AMD A10                 | 31        | 0.81%   |
| AMD A6                  | 30        | 0.79%   |
| AMD Ryzen 7 PRO         | 28        | 0.74%   |
| AMD A8                  | 28        | 0.74%   |
| Intel Atom              | 26        | 0.68%   |
| Intel Pentium Dual-Core | 25        | 0.66%   |
| Intel Core 2 Quad       | 22        | 0.58%   |
| AMD Phenom II X4        | 22        | 0.58%   |
| Intel Pentium Silver    | 16        | 0.42%   |
| AMD Ryzen 5 PRO         | 14        | 0.37%   |
| AMD Athlon II X4        | 14        | 0.37%   |
| AMD A4                  | 14        | 0.37%   |
| AMD Athlon              | 13        | 0.34%   |
| AMD Ryzen Threadripper  | 10        | 0.26%   |
| AMD Athlon II X2        | 9         | 0.24%   |
| Intel Pentium Dual      | 8         | 0.21%   |
| Intel Genuine           | 8         | 0.21%   |
| AMD E1                  | 8         | 0.21%   |
| AMD E                   | 8         | 0.21%   |
| AMD Athlon 64 X2        | 8         | 0.21%   |
| Intel Core m3           | 6         | 0.16%   |
| AMD Phenom II X6        | 6         | 0.16%   |
| AMD E2                  | 6         | 0.16%   |
| Intel Core 2            | 5         | 0.13%   |
| Intel Celeron Dual-Core | 5         | 0.13%   |
| AMD Sempron             | 5         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1521      | 39.94%  |
| 2       | 1180      | 30.99%  |
| 6       | 495       | 13%     |
| 8       | 369       | 9.69%   |
| 12      | 80        | 2.1%    |
| 16      | 42        | 1.1%    |
| 1       | 37        | 0.97%   |
| 14      | 26        | 0.68%   |
| 10      | 25        | 0.66%   |
| 3       | 10        | 0.26%   |
| 24      | 9         | 0.24%   |
| 32      | 4         | 0.11%   |
| 20      | 3         | 0.08%   |
| 18      | 2         | 0.05%   |
| Unknown | 2         | 0.05%   |
| 64      | 1         | 0.03%   |
| 36      | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3771      | 99.18%  |
| 2       | 26        | 0.68%   |
| 4       | 2         | 0.05%   |
| Unknown | 2         | 0.05%   |
| 3       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2873      | 75.39%  |
| 1       | 936       | 24.56%  |
| Unknown | 2         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3797      | 99.87%  |
| 32-bit         | 2         | 0.05%   |
| Unknown        | 2         | 0.05%   |
| 64-bit         | 1         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1079      | 27.55%  |
| 0x306a9    | 175       | 4.47%   |
| 0x306c3    | 161       | 4.11%   |
| 0x206a7    | 155       | 3.96%   |
| 0x906ea    | 126       | 3.22%   |
| 0x806ec    | 111       | 2.83%   |
| 0x806c1    | 107       | 2.73%   |
| 0x806ea    | 98        | 2.5%    |
| 0x40651    | 81        | 2.07%   |
| 0x1067a    | 78        | 1.99%   |
| 0x906e9    | 76        | 1.94%   |
| 0x806e9    | 76        | 1.94%   |
| 0x08701021 | 74        | 1.89%   |
| 0x506e3    | 73        | 1.86%   |
| 0x406e3    | 61        | 1.56%   |
| 0x0a50000c | 56        | 1.43%   |
| 0x08108109 | 54        | 1.38%   |
| 0x08600106 | 46        | 1.17%   |
| 0x306d4    | 45        | 1.15%   |
| 0x0800820d | 45        | 1.15%   |
| 0x06000852 | 40        | 1.02%   |
| 0x906a3    | 38        | 0.97%   |
| 0x08701013 | 38        | 0.97%   |
| 0x706e5    | 37        | 0.94%   |
| 0x08108102 | 37        | 0.94%   |
| 0xa0652    | 36        | 0.92%   |
| 0x806eb    | 32        | 0.82%   |
| 0x906ed    | 31        | 0.79%   |
| 0x010000c8 | 28        | 0.72%   |
| 0x706a1    | 27        | 0.69%   |
| 0x20655    | 27        | 0.69%   |
| 0x08608103 | 27        | 0.69%   |
| 0x706a8    | 23        | 0.59%   |
| 0x406c4    | 23        | 0.59%   |
| 0x08600104 | 21        | 0.54%   |
| 0x30678    | 20        | 0.51%   |
| 0x06001119 | 20        | 0.51%   |
| 0xa0653    | 19        | 0.49%   |
| 0x806d1    | 19        | 0.49%   |
| 0x506c9    | 19        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 728       | 19.1%   |
| Haswell          | 364       | 9.55%   |
| IvyBridge        | 260       | 6.82%   |
| Zen 2            | 247       | 6.48%   |
| SandyBridge      | 217       | 5.69%   |
| Skylake          | 189       | 4.96%   |
| Zen+             | 187       | 4.91%   |
| TigerLake        | 158       | 4.15%   |
| Zen 3            | 153       | 4.01%   |
| Unknown          | 140       | 3.67%   |
| Penryn           | 126       | 3.31%   |
| CometLake        | 103       | 2.7%    |
| Zen              | 90        | 2.36%   |
| Piledriver       | 87        | 2.28%   |
| IceLake          | 79        | 2.07%   |
| Goldmont plus    | 71        | 1.86%   |
| K10              | 69        | 1.81%   |
| Westmere         | 66        | 1.73%   |
| Broadwell        | 65        | 1.71%   |
| Alderlake Hybrid | 63        | 1.65%   |
| Silvermont       | 61        | 1.6%    |
| Core             | 53        | 1.39%   |
| Excavator        | 44        | 1.15%   |
| Nehalem          | 43        | 1.13%   |
| Goldmont         | 25        | 0.66%   |
| Puma             | 19        | 0.5%    |
| Steamroller      | 18        | 0.47%   |
| K10 Llano        | 18        | 0.47%   |
| K8 Hammer        | 15        | 0.39%   |
| Jaguar           | 15        | 0.39%   |
| Bobcat           | 14        | 0.37%   |
| NetBurst         | 7         | 0.18%   |
| Bulldozer        | 7         | 0.18%   |
| Bonnell          | 5         | 0.13%   |
| Tremont          | 2         | 0.05%   |
| K8 & K10 hybrid  | 2         | 0.05%   |
| K6               | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2109      | 45.69%  |
| Nvidia                           | 1393      | 30.18%  |
| AMD                              | 1094      | 23.7%   |
| Matrox Electronics Systems       | 8         | 0.17%   |
| ASPEED Technology                | 8         | 0.17%   |
| ATI Technologies                 | 2         | 0.04%   |
| Zhaoxin                          | 1         | 0.02%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 148       | 3.14%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 145       | 3.07%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 144       | 3.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 127       | 2.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 121       | 2.56%   |
| AMD Renoir                                                                               | 111       | 2.35%   |
| Intel UHD Graphics 620                                                                   | 108       | 2.29%   |
| Intel HD Graphics 620                                                                    | 95        | 2.01%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 93        | 1.97%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 90        | 1.91%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 85        | 1.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 82        | 1.74%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 79        | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 75        | 1.59%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 75        | 1.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 73        | 1.55%   |
| Intel HD Graphics 530                                                                    | 59        | 1.25%   |
| Intel HD Graphics 630                                                                    | 58        | 1.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 56        | 1.19%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 53        | 1.12%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 52        | 1.1%    |
| Intel HD Graphics 5500                                                                   | 51        | 1.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 46        | 0.97%   |
| AMD Lucienne                                                                             | 45        | 0.95%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 42        | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 41        | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 39        | 0.83%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 36        | 0.76%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 35        | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 34        | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 31        | 0.66%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 30        | 0.64%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 29        | 0.61%   |
| Intel Core Processor Integrated Graphics Controller                                      | 28        | 0.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 27        | 0.57%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 26        | 0.55%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 26        | 0.55%   |
| AMD Rembrandt [Radeon 680M]                                                              | 26        | 0.55%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 25        | 0.53%   |
| Intel Iris Plus Graphics G7                                                              | 25        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1389      | 36.38%  |
| 1 x AMD                  | 854       | 22.37%  |
| 1 x Nvidia               | 712       | 18.65%  |
| Intel + Nvidia           | 576       | 15.09%  |
| Intel + AMD              | 99        | 2.59%   |
| AMD + Nvidia             | 81        | 2.12%   |
| 2 x AMD                  | 60        | 1.57%   |
| 2 x Nvidia               | 16        | 0.42%   |
| Other                    | 8         | 0.21%   |
| Nvidia + ASPEED          | 4         | 0.1%    |
| 1 x ASPEED               | 4         | 0.1%    |
| Nvidia + Matrox          | 3         | 0.08%   |
| 1 x Matrox               | 3         | 0.08%   |
| 3 x Nvidia               | 2         | 0.05%   |
| AMD + Matrox             | 2         | 0.05%   |
| 2 x Intel                | 1         | 0.03%   |
| 1 x Zhaoxin              | 1         | 0.03%   |
| 1 x SiS                  | 1         | 0.03%   |
| Intel + 2 x AMD          | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2765      | 71.84%  |
| Proprietary | 1006      | 26.14%  |
| Unknown     | 78        | 2.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2120      | 54.41%  |
| 1.01-2.0   | 452       | 11.6%   |
| 0.01-0.5   | 341       | 8.75%   |
| 3.01-4.0   | 300       | 7.7%    |
| 0.51-1.0   | 278       | 7.14%   |
| 7.01-8.0   | 197       | 5.06%   |
| 5.01-6.0   | 112       | 2.87%   |
| 8.01-16.0  | 49        | 1.26%   |
| 2.01-3.0   | 35        | 0.9%    |
| 16.01-24.0 | 8         | 0.21%   |
| 4.01-5.0   | 3         | 0.08%   |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 569       | 12.72%  |
| AU Optronics            | 478       | 10.68%  |
| BOE                     | 406       | 9.07%   |
| LG Display              | 379       | 8.47%   |
| Chimei Innolux          | 366       | 8.18%   |
| Dell                    | 291       | 6.5%    |
| Goldstar                | 243       | 5.43%   |
| Acer                    | 156       | 3.49%   |
| Hewlett-Packard         | 154       | 3.44%   |
| BenQ                    | 119       | 2.66%   |
| Philips                 | 110       | 2.46%   |
| Ancor Communications    | 110       | 2.46%   |
| Sharp                   | 108       | 2.41%   |
| AOC                     | 105       | 2.35%   |
| Lenovo                  | 61        | 1.36%   |
| ASUSTek Computer        | 57        | 1.27%   |
| ViewSonic               | 55        | 1.23%   |
| Iiyama                  | 50        | 1.12%   |
| Apple                   | 48        | 1.07%   |
| PANDA                   | 45        | 1.01%   |
| Chi Mei Optoelectronics | 43        | 0.96%   |
| InfoVision              | 34        | 0.76%   |
| LG Electronics          | 31        | 0.69%   |
| Unknown                 | 23        | 0.51%   |
| Sony                    | 23        | 0.51%   |
| NEC Computers           | 20        | 0.45%   |
| Panasonic               | 19        | 0.42%   |
| CSO                     | 15        | 0.34%   |
| Sceptre Tech            | 14        | 0.31%   |
| HannStar                | 14        | 0.31%   |
| Eizo                    | 13        | 0.29%   |
| MSI                     | 11        | 0.25%   |
| Medion                  | 11        | 0.25%   |
| Vizio                   | 10        | 0.22%   |
| Toshiba                 | 10        | 0.22%   |
| Vestel Elektronik       | 8         | 0.18%   |
| Idek Iiyama             | 8         | 0.18%   |
| LG Philips              | 7         | 0.16%   |
| Fujitsu Siemens         | 6         | 0.13%   |
| Unknown                 | 6         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 21        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 20        | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 20        | 0.43%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 19        | 0.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 18        | 0.39%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 17        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 16        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 16        | 0.34%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 15        | 0.32%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 14        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 12        | 0.26%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 12        | 0.26%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 12        | 0.26%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 11        | 0.24%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 11        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 11        | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 11        | 0.24%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 10        | 0.21%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 9         | 0.19%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 9         | 0.19%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 9         | 0.19%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch          | 9         | 0.19%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 8         | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 8         | 0.17%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 8         | 0.17%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 8         | 0.17%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 8         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 8         | 0.17%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 8         | 0.17%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 8         | 0.17%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 8         | 0.17%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch  | 7         | 0.15%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 7         | 0.15%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch   | 7         | 0.15%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 7         | 0.15%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch          | 7         | 0.15%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch          | 7         | 0.15%   |
| Goldstar LG Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch            | 7         | 0.15%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 7         | 0.15%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 7         | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2036      | 48.3%   |
| 1366x768 (WXGA)    | 599       | 14.21%  |
| 3840x2160 (4K)     | 297       | 7.05%   |
| 2560x1440 (QHD)    | 223       | 5.29%   |
| 1600x900 (HD+)     | 148       | 3.51%   |
| 1920x1200 (WUXGA)  | 135       | 3.2%    |
| 1680x1050 (WSXGA+) | 103       | 2.44%   |
| 1280x1024 (SXGA)   | 86        | 2.04%   |
| Unknown            | 76        | 1.8%    |
| 1440x900 (WXGA+)   | 55        | 1.3%    |
| 3440x1440          | 53        | 1.26%   |
| 2560x1080          | 45        | 1.07%   |
| 1280x800 (WXGA)    | 40        | 0.95%   |
| 3840x1080          | 34        | 0.81%   |
| 2560x1600          | 32        | 0.76%   |
| 1360x768           | 30        | 0.71%   |
| 2880x1800          | 26        | 0.62%   |
| 3840x2400          | 19        | 0.45%   |
| 2160x1440          | 19        | 0.45%   |
| 1920x540           | 13        | 0.31%   |
| 1600x1200          | 12        | 0.28%   |
| 1024x768 (XGA)     | 12        | 0.28%   |
| 3840x1200          | 9         | 0.21%   |
| 3200x1800 (QHD+)   | 7         | 0.17%   |
| 2256x1504          | 7         | 0.17%   |
| 4480x1440          | 6         | 0.14%   |
| 2240x1400          | 6         | 0.14%   |
| 3840x1600          | 5         | 0.12%   |
| 1920x1280          | 5         | 0.12%   |
| 1280x720 (HD)      | 5         | 0.12%   |
| 5760x1080          | 4         | 0.09%   |
| 2736x1824          | 4         | 0.09%   |
| 2520x1680          | 4         | 0.09%   |
| 2288x1287          | 4         | 0.09%   |
| 5760x2160          | 3         | 0.07%   |
| 3600x1080          | 3         | 0.07%   |
| 3456x2160          | 3         | 0.07%   |
| 3200x1080          | 3         | 0.07%   |
| 3072x1920          | 3         | 0.07%   |
| 7680x2160          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1072      | 24.04%  |
| 27      | 378       | 8.48%   |
| 24      | 371       | 8.32%   |
| 13      | 371       | 8.32%   |
| 14      | 349       | 7.83%   |
| 23      | 314       | 7.04%   |
| 17      | 259       | 5.81%   |
| 21      | 246       | 5.52%   |
| Unknown | 239       | 5.36%   |
| 31      | 104       | 2.33%   |
| 34      | 85        | 1.91%   |
| 19      | 84        | 1.88%   |
| 22      | 65        | 1.46%   |
| 20      | 55        | 1.23%   |
| 12      | 52        | 1.17%   |
| 18      | 50        | 1.12%   |
| 11      | 50        | 1.12%   |
| 16      | 48        | 1.08%   |
| 32      | 30        | 0.67%   |
| 84      | 27        | 0.61%   |
| 25      | 24        | 0.54%   |
| 72      | 23        | 0.52%   |
| 54      | 21        | 0.47%   |
| 40      | 20        | 0.45%   |
| 26      | 12        | 0.27%   |
| 48      | 8         | 0.18%   |
| 47      | 8         | 0.18%   |
| 28      | 8         | 0.18%   |
| 46      | 7         | 0.16%   |
| 42      | 7         | 0.16%   |
| 37      | 6         | 0.13%   |
| 65      | 5         | 0.11%   |
| 36      | 5         | 0.11%   |
| 10      | 5         | 0.11%   |
| 69      | 4         | 0.09%   |
| 60      | 4         | 0.09%   |
| 52      | 4         | 0.09%   |
| 49      | 4         | 0.09%   |
| 39      | 4         | 0.09%   |
| 142     | 3         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1642      | 37.79%  |
| 501-600        | 969       | 22.3%   |
| 401-500        | 445       | 10.24%  |
| 351-400        | 305       | 7.02%   |
| 201-300        | 292       | 6.72%   |
| Unknown        | 239       | 5.5%    |
| 601-700        | 156       | 3.59%   |
| 701-800        | 122       | 2.81%   |
| 1001-1500      | 68        | 1.57%   |
| 1501-2000      | 58        | 1.33%   |
| 801-900        | 34        | 0.78%   |
| 901-1000       | 9         | 0.21%   |
| More than 2000 | 3         | 0.07%   |
| 1-100          | 2         | 0.05%   |
| 101-200        | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2978      | 76.52%  |
| 16/10   | 426       | 10.95%  |
| Unknown | 209       | 5.37%   |
| 21/9    | 96        | 2.47%   |
| 5/4     | 79        | 2.03%   |
| 3/2     | 50        | 1.28%   |
| 4/3     | 29        | 0.75%   |
| 32/9    | 14        | 0.36%   |
| 1.00    | 3         | 0.08%   |
| 6/5     | 2         | 0.05%   |
| 1.96    | 2         | 0.05%   |
| 3.40    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |
| 0.25    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1072      | 24.49%  |
| 201-250        | 758       | 17.31%  |
| 81-90          | 562       | 12.84%  |
| 301-350        | 387       | 8.84%   |
| Unknown        | 239       | 5.46%   |
| 351-500        | 228       | 5.21%   |
| 151-200        | 200       | 4.57%   |
| 121-130        | 193       | 4.41%   |
| 71-80          | 162       | 3.7%    |
| 251-300        | 142       | 3.24%   |
| More than 1000 | 103       | 2.35%   |
| 141-150        | 80        | 1.83%   |
| 501-1000       | 70        | 1.6%    |
| 51-60          | 51        | 1.16%   |
| 61-70          | 44        | 1.01%   |
| 111-120        | 41        | 0.94%   |
| 131-140        | 27        | 0.62%   |
| 91-100         | 11        | 0.25%   |
| 41-50          | 5         | 0.11%   |
| 1-40           | 3         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1323      | 31.12%  |
| 121-160       | 1251      | 29.43%  |
| 101-120       | 929       | 21.85%  |
| 161-240       | 279       | 6.56%   |
| Unknown       | 239       | 5.62%   |
| More than 240 | 131       | 3.08%   |
| 1-50          | 99        | 2.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2871      | 74.01%  |
| 2     | 812       | 20.93%  |
| 3     | 101       | 2.6%    |
| 0     | 82        | 2.11%   |
| 4     | 13        | 0.34%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2163      | 37.73%  |
| Intel                             | 1955      | 34.1%   |
| Qualcomm Atheros                  | 570       | 9.94%   |
| Broadcom                          | 243       | 4.24%   |
| MediaTek                          | 111       | 1.94%   |
| Ralink Technology                 | 65        | 1.13%   |
| TP-Link                           | 63        | 1.1%    |
| Ralink                            | 51        | 0.89%   |
| Broadcom Limited                  | 40        | 0.7%    |
| Nvidia                            | 33        | 0.58%   |
| Marvell Technology Group          | 31        | 0.54%   |
| Samsung Electronics               | 27        | 0.47%   |
| ASIX Electronics                  | 26        | 0.45%   |
| Aquantia                          | 22        | 0.38%   |
| Qualcomm Atheros Communications   | 20        | 0.35%   |
| Lenovo                            | 19        | 0.33%   |
| DisplayLink                       | 18        | 0.31%   |
| NetGear                           | 17        | 0.3%    |
| Xiaomi                            | 16        | 0.28%   |
| Qualcomm                          | 16        | 0.28%   |
| Microsoft                         | 16        | 0.28%   |
| Huawei Technologies               | 15        | 0.26%   |
| Sierra Wireless                   | 14        | 0.24%   |
| D-Link                            | 14        | 0.24%   |
| Dell                              | 11        | 0.19%   |
| ASUSTek Computer                  | 11        | 0.19%   |
| Ericsson Business Mobile Networks | 10        | 0.17%   |
| Edimax Technology                 | 9         | 0.16%   |
| JMicron Technology                | 7         | 0.12%   |
| Hewlett-Packard                   | 7         | 0.12%   |
| Apple                             | 7         | 0.12%   |
| Linksys                           | 6         | 0.1%    |
| D-Link System                     | 6         | 0.1%    |
| Belkin Components                 | 6         | 0.1%    |
| Google                            | 5         | 0.09%   |
| Fibocom                           | 5         | 0.09%   |
| AVM                               | 5         | 0.09%   |
| VIA Technologies                  | 4         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.05%   |
| Wacom                             | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1485      | 22.11%  |
| Intel Wi-Fi 6 AX200                                               | 228       | 3.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 190       | 2.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 134       | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 131       | 1.95%   |
| Intel Wireless 8265 / 8275                                        | 121       | 1.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 118       | 1.76%   |
| Intel I211 Gigabit Network Connection                             | 115       | 1.71%   |
| Intel Wi-Fi 6 AX201                                               | 111       | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 102       | 1.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 98        | 1.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 91        | 1.35%   |
| Intel Wireless 7260                                               | 90        | 1.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 86        | 1.28%   |
| Intel Wireless 7265                                               | 83        | 1.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 80        | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 73        | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 72        | 1.07%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 67        | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 67        | 1%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 62        | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 62        | 0.92%   |
| Intel Wireless 3165                                               | 61        | 0.91%   |
| Intel Wireless 8260                                               | 55        | 0.82%   |
| Intel Ethernet Connection I217-LM                                 | 55        | 0.82%   |
| Intel Ethernet Controller I225-V                                  | 53        | 0.79%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 53        | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 51        | 0.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 51        | 0.76%   |
| Intel Wireless-AC 9260                                            | 48        | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 46        | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 40        | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 39        | 0.58%   |
| Intel Ethernet Connection (7) I219-V                              | 38        | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 36        | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 36        | 0.54%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 33        | 0.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 33        | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 31        | 0.46%   |
| Ralink MT7601U Wireless Adapter                                   | 30        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1509      | 48.38%  |
| Realtek Semiconductor                 | 517       | 16.58%  |
| Qualcomm Atheros                      | 448       | 14.36%  |
| Broadcom                              | 160       | 5.13%   |
| MediaTek                              | 107       | 3.43%   |
| Ralink Technology                     | 65        | 2.08%   |
| TP-Link                               | 57        | 1.83%   |
| Ralink                                | 51        | 1.64%   |
| Broadcom Limited                      | 33        | 1.06%   |
| Qualcomm Atheros Communications       | 20        | 0.64%   |
| NetGear                               | 17        | 0.55%   |
| Microsoft                             | 15        | 0.48%   |
| Sierra Wireless                       | 14        | 0.45%   |
| D-Link                                | 14        | 0.45%   |
| Qualcomm                              | 11        | 0.35%   |
| ASUSTek Computer                      | 11        | 0.35%   |
| Edimax Technology                     | 9         | 0.29%   |
| Marvell Technology Group              | 6         | 0.19%   |
| Dell                                  | 6         | 0.19%   |
| Belkin Components                     | 6         | 0.19%   |
| Linksys                               | 5         | 0.16%   |
| Fibocom                               | 5         | 0.16%   |
| AVM                                   | 5         | 0.16%   |
| D-Link System                         | 4         | 0.13%   |
| Wacom                                 | 3         | 0.1%    |
| ZyDAS                                 | 2         | 0.06%   |
| Mercucys                              | 2         | 0.06%   |
| Hewlett-Packard                       | 2         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.06%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| Wilocity                              | 1         | 0.03%   |
| Texas Instruments                     | 1         | 0.03%   |
| Sitecom Europe                        | 1         | 0.03%   |
| Realtek                               | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Micro Star International              | 1         | 0.03%   |
| LG Electronics                        | 1         | 0.03%   |
| IMC Networks                          | 1         | 0.03%   |
| Guillemot                             | 1         | 0.03%   |
| Gemtek                                | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 228       | 7.25%   |
| Intel Wireless 8265 / 8275                                     | 121       | 3.85%   |
| Intel Wi-Fi 6 AX201                                            | 111       | 3.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 102       | 3.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 98        | 3.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 91        | 2.9%    |
| Intel Wireless 7260                                            | 90        | 2.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 86        | 2.74%   |
| Intel Wireless 7265                                            | 83        | 2.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 80        | 2.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 73        | 2.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 72        | 2.29%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 67        | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 62        | 1.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 62        | 1.97%   |
| Intel Wireless 3165                                            | 61        | 1.94%   |
| Intel Wireless 8260                                            | 55        | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 53        | 1.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 51        | 1.62%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 51        | 1.62%   |
| Intel Wireless-AC 9260                                         | 48        | 1.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 46        | 1.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 40        | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 36        | 1.15%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 33        | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 33        | 1.05%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 31        | 0.99%   |
| Ralink MT7601U Wireless Adapter                                | 30        | 0.95%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 29        | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 27        | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 27        | 0.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 26        | 0.83%   |
| Intel Wireless 3160                                            | 26        | 0.83%   |
| Realtek 802.11ac NIC                                           | 25        | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 25        | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 24        | 0.76%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 24        | 0.76%   |
| Broadcom BCM43142 802.11b/g/n                                  | 23        | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 22        | 0.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 20        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1934      | 56.55%  |
| Intel                            | 957       | 27.98%  |
| Qualcomm Atheros                 | 159       | 4.65%   |
| Broadcom                         | 107       | 3.13%   |
| Nvidia                           | 33        | 0.96%   |
| ASIX Electronics                 | 26        | 0.76%   |
| Marvell Technology Group         | 25        | 0.73%   |
| Aquantia                         | 22        | 0.64%   |
| Lenovo                           | 19        | 0.56%   |
| Samsung Electronics              | 18        | 0.53%   |
| DisplayLink                      | 18        | 0.53%   |
| Xiaomi                           | 16        | 0.47%   |
| Huawei Technologies              | 12        | 0.35%   |
| Broadcom Limited                 | 8         | 0.23%   |
| JMicron Technology               | 7         | 0.2%    |
| Apple                            | 7         | 0.2%    |
| TP-Link                          | 6         | 0.18%   |
| Qualcomm                         | 5         | 0.15%   |
| Google                           | 5         | 0.15%   |
| VIA Technologies                 | 4         | 0.12%   |
| MediaTek                         | 4         | 0.12%   |
| T & A Mobile Phones              | 3         | 0.09%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.06%   |
| Silicon Integrated Systems [SiS] | 2         | 0.06%   |
| Motorola PCS                     | 2         | 0.06%   |
| Mellanox Technologies            | 2         | 0.06%   |
| D-Link System                    | 2         | 0.06%   |
| 3Com                             | 2         | 0.06%   |
| QNAP System                      | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.03%   |
| Motorola BCS                     | 1         | 0.03%   |
| Microsoft                        | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |
| IBM                              | 1         | 0.03%   |
| HMD Global                       | 1         | 0.03%   |
| Hewlett-Packard                  | 1         | 0.03%   |
| Elecom                           | 1         | 0.03%   |
| Davicom Semiconductor            | 1         | 0.03%   |
| American Megatrends              | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1485      | 42.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 190       | 5.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 134       | 3.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 131       | 3.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 118       | 3.35%   |
| Intel I211 Gigabit Network Connection                             | 115       | 3.27%   |
| Intel Ethernet Connection (2) I219-V                              | 67        | 1.9%    |
| Intel Ethernet Connection I217-LM                                 | 55        | 1.56%   |
| Intel Ethernet Controller I225-V                                  | 53        | 1.51%   |
| Intel Ethernet Connection (4) I219-LM                             | 39        | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 38        | 1.08%   |
| Intel Ethernet Connection (7) I219-LM                             | 36        | 1.02%   |
| Intel 82579V Gigabit Network Connection                           | 30        | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 26        | 0.74%   |
| Intel Ethernet Connection (2) I218-V                              | 26        | 0.74%   |
| Intel Ethernet Connection I218-LM                                 | 24        | 0.68%   |
| ASIX AX88179 Gigabit Ethernet                                     | 24        | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 23        | 0.65%   |
| Intel I210 Gigabit Network Connection                             | 22        | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 21        | 0.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 19        | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 19        | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19        | 0.54%   |
| Intel Ethernet Connection I217-V                                  | 19        | 0.54%   |
| Intel Ethernet Connection (6) I219-V                              | 19        | 0.54%   |
| Intel 82574L Gigabit Network Connection                           | 19        | 0.54%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 19        | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 18        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 17        | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 17        | 0.48%   |
| Intel Ethernet Connection (10) I219-V                             | 17        | 0.48%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 16        | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 15        | 0.43%   |
| Intel Ethernet Connection (13) I219-V                             | 15        | 0.43%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14        | 0.4%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 14        | 0.4%    |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.37%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 13        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3195      | 51.38%  |
| WiFi     | 2969      | 47.75%  |
| Modem    | 50        | 0.8%    |
| Unknown  | 4         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2323      | 57.8%   |
| Ethernet | 1694      | 42.15%  |
| Modem    | 2         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2047      | 53.8%   |
| 1     | 1596      | 41.94%  |
| 3     | 86        | 2.26%   |
| 0     | 57        | 1.5%    |
| 4     | 14        | 0.37%   |
| 6     | 3         | 0.08%   |
| 5     | 2         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 3106      | 80.57%  |
| Yes     | 748       | 19.4%   |
| Unknown | 1         | 0.03%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1299      | 50.08%  |
| Realtek Semiconductor           | 270       | 10.41%  |
| Qualcomm Atheros Communications | 199       | 7.67%   |
| Cambridge Silicon Radio         | 175       | 6.75%   |
| Broadcom                        | 119       | 4.59%   |
| IMC Networks                    | 104       | 4.01%   |
| Lite-On Technology              | 82        | 3.16%   |
| Foxconn / Hon Hai               | 78        | 3.01%   |
| Apple                           | 51        | 1.97%   |
| ASUSTek Computer                | 41        | 1.58%   |
| Dell                            | 33        | 1.27%   |
| Realtek                         | 28        | 1.08%   |
| Ralink                          | 14        | 0.54%   |
| MediaTek                        | 13        | 0.5%    |
| Hewlett-Packard                 | 13        | 0.5%    |
| Toshiba                         | 11        | 0.42%   |
| Foxconn International           | 8         | 0.31%   |
| TP-Link                         | 7         | 0.27%   |
| Marvell Semiconductor           | 7         | 0.27%   |
| Ralink Technology               | 5         | 0.19%   |
| ISSC                            | 4         | 0.15%   |
| Edimax Technology               | 4         | 0.15%   |
| Dynex                           | 4         | 0.15%   |
| Alps Electric                   | 4         | 0.15%   |
| USI                             | 2         | 0.08%   |
| Taiyo Yuden                     | 2         | 0.08%   |
| Smart Modular Technologies      | 2         | 0.08%   |
| Micro Star International        | 2         | 0.08%   |
| Integrated System Solution      | 2         | 0.08%   |
| D-Link                          | 2         | 0.08%   |
| Belkin Components               | 2         | 0.08%   |
| SINO WEALTH                     | 1         | 0.04%   |
| Kensington                      | 1         | 0.04%   |
| Creative Technology             | 1         | 0.04%   |
| Corsair                         | 1         | 0.04%   |
| Conwise Technology              | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 421       | 16.21%  |
| Intel AX201 Bluetooth                               | 260       | 10.01%  |
| Intel AX200 Bluetooth                               | 222       | 8.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 187       | 7.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 175       | 6.74%   |
| Realtek Bluetooth Radio                             | 169       | 6.51%   |
| Qualcomm Atheros  Bluetooth Device                  | 107       | 4.12%   |
| Realtek  Bluetooth 4.2 Adapter                      | 75        | 2.89%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 46        | 1.77%   |
| Intel Wireless-AC 3168 Bluetooth                    | 44        | 1.69%   |
| Intel Bluetooth Device                              | 43        | 1.66%   |
| IMC Networks Bluetooth Radio                        | 33        | 1.27%   |
| Intel AX210 Bluetooth                               | 32        | 1.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 30        | 1.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 30        | 1.16%   |
| IMC Networks Wireless_Device                        | 30        | 1.16%   |
| Realtek Bluetooth Radio                             | 28        | 1.08%   |
| Lite-On Bluetooth Device                            | 28        | 1.08%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 28        | 1.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 27        | 1.04%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 22        | 0.85%   |
| Foxconn / Hon Hai Bluetooth Device                  | 22        | 0.85%   |
| IMC Networks Bluetooth Device                       | 20        | 0.77%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 20        | 0.77%   |
| Apple Bluetooth USB Host Controller                 | 20        | 0.77%   |
| Lite-On Wireless_Device                             | 18        | 0.69%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 0.69%   |
| Apple Bluetooth Host Controller                     | 18        | 0.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 0.62%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.62%   |
| Ralink RT3290 Bluetooth                             | 14        | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 0.5%    |
| MediaTek Wireless_Device                            | 13        | 0.5%    |
| Realtek RTL8723B Bluetooth                          | 12        | 0.46%   |
| Dell BCM20702A0 Bluetooth Module                    | 12        | 0.46%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 12        | 0.46%   |
| ASUS ASUS USB-BT500                                 | 12        | 0.46%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 12        | 0.46%   |
| Foxconn / Hon Hai Wireless_Device                   | 11        | 0.42%   |
| Broadcom HP Portable SoftSailing                    | 11        | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 2656      | 47.46%  |
| AMD                        | 1251      | 22.36%  |
| Nvidia                     | 1010      | 18.05%  |
| C-Media Electronics        | 105       | 1.88%   |
| Logitech                   | 40        | 0.71%   |
| GN Netcom                  | 36        | 0.64%   |
| Creative Labs              | 36        | 0.64%   |
| JMTek                      | 31        | 0.55%   |
| Realtek Semiconductor      | 29        | 0.52%   |
| Texas Instruments          | 23        | 0.41%   |
| ASUSTek Computer           | 20        | 0.36%   |
| Corsair                    | 19        | 0.34%   |
| Razer USA                  | 18        | 0.32%   |
| Lenovo                     | 17        | 0.3%    |
| Generalplus Technology     | 17        | 0.3%    |
| Creative Technology        | 16        | 0.29%   |
| Plantronics                | 14        | 0.25%   |
| Hewlett-Packard            | 14        | 0.25%   |
| SteelSeries ApS            | 12        | 0.21%   |
| Kingston Technology        | 12        | 0.21%   |
| VIA Technologies           | 9         | 0.16%   |
| Focusrite-Novation         | 9         | 0.16%   |
| Blue Microphones           | 9         | 0.16%   |
| Tenx Technology            | 8         | 0.14%   |
| Sony                       | 7         | 0.13%   |
| Dell                       | 7         | 0.13%   |
| SAVITECH                   | 5         | 0.09%   |
| Yamaha                     | 4         | 0.07%   |
| Trust                      | 4         | 0.07%   |
| Sennheiser Communications  | 4         | 0.07%   |
| Scarlett                   | 4         | 0.07%   |
| PreSonus Audio Electronics | 4         | 0.07%   |
| Micro Star International   | 4         | 0.07%   |
| M-Audio                    | 4         | 0.07%   |
| GYROCOM C&C                | 4         | 0.07%   |
| BEHRINGER International    | 4         | 0.07%   |
| ZOOM                       | 3         | 0.05%   |
| TerraTec Electronic        | 3         | 0.05%   |
| TEAC                       | 3         | 0.05%   |
| Samson Technologies        | 3         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 439       | 6.57%   |
| Intel Sunrise Point-LP HD Audio                                            | 300       | 4.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 238       | 3.56%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 221       | 3.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 209       | 3.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 206       | 3.08%   |
| Intel Cannon Lake PCH cAVS                                                 | 190       | 2.84%   |
| AMD Starship/Matisse HD Audio Controller                                   | 188       | 2.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 167       | 2.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 158       | 2.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 146       | 2.18%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 128       | 1.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 119       | 1.78%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 110       | 1.65%   |
| Nvidia GP107GL High Definition Audio Controller                            | 109       | 1.63%   |
| AMD FCH Azalia Controller                                                  | 102       | 1.53%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 99        | 1.48%   |
| Intel Haswell-ULT HD Audio Controller                                      | 92        | 1.38%   |
| Intel 8 Series HD Audio Controller                                         | 91        | 1.36%   |
| Intel Comet Lake PCH-LP cAVS                                               | 89        | 1.33%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 81        | 1.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 78        | 1.17%   |
| Intel 200 Series PCH HD Audio                                              | 75        | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 72        | 1.08%   |
| Intel Comet Lake PCH cAVS                                                  | 72        | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 71        | 1.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 71        | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                              | 67        | 1%      |
| Nvidia TU106 High Definition Audio Controller                              | 63        | 0.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 63        | 0.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 61        | 0.91%   |
| Nvidia GP106 High Definition Audio Controller                              | 59        | 0.88%   |
| Intel Broadwell-U Audio Controller                                         | 58        | 0.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 57        | 0.85%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 57        | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 51        | 0.76%   |
| AMD Kabini HDMI/DP Audio                                                   | 50        | 0.75%   |
| Nvidia GP104 High Definition Audio Controller                              | 49        | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                              | 47        | 0.7%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 47        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 622       | 21.88%  |
| SK hynix            | 454       | 15.97%  |
| Kingston            | 364       | 12.8%   |
| Micron Technology   | 294       | 10.34%  |
| Crucial             | 212       | 7.46%   |
| Unknown             | 190       | 6.68%   |
| Corsair             | 173       | 6.09%   |
| G.Skill             | 131       | 4.61%   |
| A-DATA Technology   | 52        | 1.83%   |
| Ramaxel Technology  | 49        | 1.72%   |
| Unknown (ABCD)      | 37        | 1.3%    |
| Elpida              | 31        | 1.09%   |
| Nanya Technology    | 29        | 1.02%   |
| Team                | 23        | 0.81%   |
| Patriot             | 19        | 0.67%   |
| Unknown             | 16        | 0.56%   |
| Transcend           | 15        | 0.53%   |
| Smart               | 15        | 0.53%   |
| GOODRAM             | 8         | 0.28%   |
| AMD                 | 8         | 0.28%   |
| Silicon Power       | 7         | 0.25%   |
| Apacer              | 6         | 0.21%   |
| Wilk                | 5         | 0.18%   |
| Teikon              | 5         | 0.18%   |
| Smart Brazil        | 5         | 0.18%   |
| Avant               | 5         | 0.18%   |
| PNY                 | 4         | 0.14%   |
| ASint Technology    | 4         | 0.14%   |
| SHARETRONIC         | 3         | 0.11%   |
| Goldkey             | 3         | 0.11%   |
| CSX                 | 3         | 0.11%   |
| V-GeN               | 2         | 0.07%   |
| Unifosa             | 2         | 0.07%   |
| Reboto              | 2         | 0.07%   |
| Kllisre             | 2         | 0.07%   |
| Kingmax             | 2         | 0.07%   |
| Imation             | 2         | 0.07%   |
| Hewlett-Packard     | 2         | 0.07%   |
| GLOWAY              | 2         | 0.07%   |
| GeIL                | 2         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 30        | 0.98%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 28        | 0.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 27        | 0.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 0.85%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 0.76%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 22        | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 21        | 0.69%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 19        | 0.62%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 0.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 17        | 0.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.53%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 16        | 0.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 0.53%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 16        | 0.53%   |
| Unknown                                                          | 16        | 0.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 0.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.46%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 13        | 0.43%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 13        | 0.43%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 12        | 0.39%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.39%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.39%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 12        | 0.39%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 12        | 0.39%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 12        | 0.39%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 0.36%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.36%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 0.36%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 11        | 0.36%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 10        | 0.33%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 10        | 0.33%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 10        | 0.33%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.33%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 10        | 0.33%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.3%    |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 9         | 0.3%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.3%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1397      | 57.42%  |
| DDR3    | 664       | 27.29%  |
| LPDDR4  | 105       | 4.32%   |
| Unknown | 57        | 2.34%   |
| LPDDR3  | 56        | 2.3%    |
| DDR2    | 49        | 2.01%   |
| DDR5    | 39        | 1.6%    |
| SDRAM   | 35        | 1.44%   |
| LPDDR5  | 20        | 0.82%   |
| DDR     | 10        | 0.41%   |
| DRAM    | 1         | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1405      | 57.44%  |
| DIMM         | 823       | 33.65%  |
| Row Of Chips | 190       | 7.77%   |
| Chip         | 14        | 0.57%   |
| Unknown      | 9         | 0.37%   |
| FB-DIMM      | 3         | 0.12%   |
| RIMM         | 2         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1156      | 43.51%  |
| 4096  | 659       | 24.8%   |
| 16384 | 504       | 18.97%  |
| 2048  | 214       | 8.05%   |
| 32768 | 92        | 3.46%   |
| 1024  | 29        | 1.09%   |
| 512   | 1         | 0.04%   |
| 256   | 1         | 0.04%   |
| 128   | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 477       | 18.1%   |
| 3200    | 457       | 17.34%  |
| 1600    | 456       | 17.3%   |
| 2400    | 233       | 8.84%   |
| 1333    | 151       | 5.73%   |
| 2133    | 131       | 4.97%   |
| 3600    | 87        | 3.3%    |
| 1334    | 59        | 2.24%   |
| 4267    | 45        | 1.71%   |
| 1867    | 40        | 1.52%   |
| 800     | 33        | 1.25%   |
| 4800    | 30        | 1.14%   |
| 667     | 29        | 1.1%    |
| 3266    | 27        | 1.02%   |
| 2666    | 23        | 0.87%   |
| 6400    | 22        | 0.83%   |
| Unknown | 22        | 0.83%   |
| 3800    | 21        | 0.8%    |
| 3400    | 21        | 0.8%    |
| 3000    | 21        | 0.8%    |
| 2933    | 20        | 0.76%   |
| 3733    | 18        | 0.68%   |
| 1067    | 16        | 0.61%   |
| 1066    | 16        | 0.61%   |
| 8400    | 13        | 0.49%   |
| 1866    | 13        | 0.49%   |
| 3866    | 12        | 0.46%   |
| 4199    | 10        | 0.38%   |
| 2800    | 10        | 0.38%   |
| 1800    | 9         | 0.34%   |
| 4266    | 8         | 0.3%    |
| 3533    | 8         | 0.3%    |
| 400     | 8         | 0.3%    |
| 3333    | 7         | 0.27%   |
| 3666    | 6         | 0.23%   |
| 3066    | 6         | 0.23%   |
| 3466    | 5         | 0.19%   |
| 3151    | 5         | 0.19%   |
| 2048    | 5         | 0.19%   |
| 2000    | 5         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 48        | 39.34%  |
| Brother Industries     | 27        | 22.13%  |
| Seiko Epson            | 12        | 9.84%   |
| Samsung Electronics    | 11        | 9.02%   |
| Canon                  | 9         | 7.38%   |
| Xerox                  | 2         | 1.64%   |
| Prolific Technology    | 2         | 1.64%   |
| Dymo-CoStar            | 2         | 1.64%   |
| Zebra                  | 1         | 0.82%   |
| QinHeng Electronics    | 1         | 0.82%   |
| Pantum                 | 1         | 0.82%   |
| Panasonic (Matsushita) | 1         | 0.82%   |
| Kyocera                | 1         | 0.82%   |
| ICS Advent             | 1         | 0.82%   |
| Datamax-O'Neil         | 1         | 0.82%   |
| BESTEASY               | 1         | 0.82%   |
| Apple                  | 1         | 0.82%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| HP OfficeJet Pro 8020 series                           | 3         | 2.42%   |
| Seiko Epson L3110 Series                               | 2         | 1.61%   |
| Seiko Epson L220 Series                                | 2         | 1.61%   |
| Samsung M2070 Series                                   | 2         | 1.61%   |
| Prolific PL2305 Parallel Port                          | 2         | 1.61%   |
| HP OfficeJet Pro 7740 series                           | 2         | 1.61%   |
| HP LaserJet P2015 series                               | 2         | 1.61%   |
| HP LaserJet 1020                                       | 2         | 1.61%   |
| HP LaserJet 1018                                       | 2         | 1.61%   |
| HP ENVY 4500 series                                    | 2         | 1.61%   |
| HP DeskJet 2700 series                                 | 2         | 1.61%   |
| HP DeskJet 2620 All-in-One Printer                     | 2         | 1.61%   |
| Brother MFC-J460DW                                     | 2         | 1.61%   |
| Brother HL-L2320D series                               | 2         | 1.61%   |
| Brother HL-2230 series                                 | 2         | 1.61%   |
| Zebra ZTC LP2844-Z-200dpi                              | 1         | 0.81%   |
| Xerox Phaser 6500DN                                    | 1         | 0.81%   |
| Xerox Phaser 3140 and 3155                             | 1         | 0.81%   |
| Seiko Epson XP-3100 Series                             | 1         | 0.81%   |
| Seiko Epson XP-2100 Series                             | 1         | 0.81%   |
| Seiko Epson WF-2530 Series                             | 1         | 0.81%   |
| Seiko Epson Printer                                    | 1         | 0.81%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 0.81%   |
| Seiko Epson L120 Series                                | 1         | 0.81%   |
| Seiko Epson ET-2710 Series                             | 1         | 0.81%   |
| Seiko Epson ET-2700 Series                             | 1         | 0.81%   |
| Samsung Xerox Phaser 3117 Laser Printer                | 1         | 0.81%   |
| Samsung SCX-3200 Series                                | 1         | 0.81%   |
| Samsung ML-2250 Series                                 | 1         | 0.81%   |
| Samsung ML-216x Series Laser Printer                   | 1         | 0.81%   |
| Samsung M262x/M282x Xpress Series Laser Printer        | 1         | 0.81%   |
| Samsung M2020 Series                                   | 1         | 0.81%   |
| Samsung CLX-3180 Series                                | 1         | 0.81%   |
| Samsung CLX-3170 Series                                | 1         | 0.81%   |
| Samsung CLP-360 Series                                 | 1         | 0.81%   |
| QinHeng CH340S                                         | 1         | 0.81%   |
| Pantum P2200 series                                    | 1         | 0.81%   |
| Panasonic (Matsushita) KX-MB1500RU                     | 1         | 0.81%   |
| Kyocera Mita FS-820                                    | 1         | 0.81%   |
| ICS Advent Parallel Adapter                            | 1         | 0.81%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 13        | 50%     |
| Seiko Epson     | 7         | 26.92%  |
| Mustek Systems  | 3         | 11.54%  |
| Hewlett-Packard | 3         | 11.54%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 3         | 11.54%  |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 2         | 7.69%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 2         | 7.69%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 2         | 7.69%   |
| Canon CanoScan LiDE 220                                 | 2         | 7.69%   |
| Canon CanoScan LiDE 210                                 | 2         | 7.69%   |
| Canon CanoScan LiDE 110                                 | 2         | 7.69%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 3.85%   |
| Seiko Epson ES-D200 [GT-S50]                            | 1         | 3.85%   |
| Mustek Systems SNAPSCAN e22                             | 1         | 3.85%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO              | 1         | 3.85%   |
| Mustek Systems BearPaw 1200 CU Plus                     | 1         | 3.85%   |
| HP ScanJet G4010                                        | 1         | 3.85%   |
| HP ScanJet 82x0C                                        | 1         | 3.85%   |
| HP ScanJet 3770                                         | 1         | 3.85%   |
| Canon CanoScan LiDE 60                                  | 1         | 3.85%   |
| Canon CanoScan LIDE 25                                  | 1         | 3.85%   |
| Canon CanoScan LiDE 120                                 | 1         | 3.85%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 470       | 18.45%  |
| IMC Networks                           | 255       | 10.01%  |
| Microdia                               | 230       | 9.03%   |
| Realtek Semiconductor                  | 193       | 7.57%   |
| Logitech                               | 190       | 7.46%   |
| Quanta                                 | 142       | 5.57%   |
| Sunplus Innovation Technology          | 132       | 5.18%   |
| Bison Electronics                      | 110       | 4.32%   |
| Acer                                   | 110       | 4.32%   |
| Cheng Uei Precision Industry (Foxlink) | 101       | 3.96%   |
| Syntek                                 | 55        | 2.16%   |
| Apple                                  | 49        | 1.92%   |
| Suyin                                  | 47        | 1.84%   |
| Silicon Motion                         | 43        | 1.69%   |
| Luxvisions Innotech Limited            | 40        | 1.57%   |
| Lite-On Technology                     | 40        | 1.57%   |
| Microsoft                              | 34        | 1.33%   |
| Samsung Electronics                    | 29        | 1.14%   |
| Alcor Micro                            | 28        | 1.1%    |
| Generalplus Technology                 | 17        | 0.67%   |
| Ricoh                                  | 16        | 0.63%   |
| Z-Star Microelectronics                | 13        | 0.51%   |
| Lenovo                                 | 13        | 0.51%   |
| Sonix Technology                       | 12        | 0.47%   |
| KYE Systems (Mouse Systems)            | 9         | 0.35%   |
| ARC International                      | 9         | 0.35%   |
| SunplusIT                              | 8         | 0.31%   |
| Genesys Logic                          | 8         | 0.31%   |
| Y Media                                | 7         | 0.27%   |
| Huawei Technologies                    | 7         | 0.27%   |
| Sunplus Technology                     | 6         | 0.24%   |
| MacroSilicon                           | 6         | 0.24%   |
| GEMBIRD                                | 6         | 0.24%   |
| Cubeternet                             | 6         | 0.24%   |
| USB Camera                             | 5         | 0.2%    |
| Importek                               | 5         | 0.2%    |
| Creative Technology                    | 5         | 0.2%    |
| Razer USA                              | 4         | 0.16%   |
| Intel                                  | 4         | 0.16%   |
| USB Camera CS                          | 3         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 110       | 4.28%   |
| Microdia Integrated_Webcam_HD                                              | 100       | 3.89%   |
| Realtek Integrated_Webcam_HD                                               | 80        | 3.11%   |
| IMC Networks Integrated Camera                                             | 78        | 3.04%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 77        | 3%      |
| Sunplus Integrated_Webcam_HD                                               | 56        | 2.18%   |
| Chicony HD WebCam                                                          | 49        | 1.91%   |
| Logitech HD Pro Webcam C920                                                | 42        | 1.63%   |
| Bison Integrated Camera                                                    | 41        | 1.6%    |
| Syntek Integrated Camera                                                   | 39        | 1.52%   |
| Logitech Webcam C270                                                       | 37        | 1.44%   |
| Acer Integrated Camera                                                     | 32        | 1.25%   |
| Chicony USB2.0 Camera                                                      | 31        | 1.21%   |
| Samsung Galaxy A5 (MTP)                                                    | 28        | 1.09%   |
| Chicony HP HD Camera                                                       | 28        | 1.09%   |
| Quanta HD User Facing                                                      | 27        | 1.05%   |
| Chicony HD User Facing                                                     | 25        | 0.97%   |
| Acer HD Webcam                                                             | 23        | 0.89%   |
| Microdia Integrated Webcam                                                 | 22        | 0.86%   |
| Quanta HP TrueVision HD Camera                                             | 20        | 0.78%   |
| Microdia Webcam Vitade AF                                                  | 20        | 0.78%   |
| Chicony HP Wide Vision HD Camera                                           | 20        | 0.78%   |
| Quanta HP HD Camera                                                        | 18        | 0.7%    |
| Chicony Integrated Camera (1280x720@30)                                    | 17        | 0.66%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 17        | 0.66%   |
| Acer Lenovo EasyCamera                                                     | 17        | 0.66%   |
| Lite-On Integrated Camera                                                  | 16        | 0.62%   |
| Chicony HP Truevision HD                                                   | 16        | 0.62%   |
| Microsoft LifeCam HD-3000                                                  | 14        | 0.54%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 14        | 0.54%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 14        | 0.54%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 14        | 0.54%   |
| Alcor Micro USB 2.0 Camera                                                 | 14        | 0.54%   |
| Realtek Integrated Webcam                                                  | 13        | 0.51%   |
| Logitech C922 Pro Stream Webcam                                            | 13        | 0.51%   |
| Chicony HP TrueVision HD Camera                                            | 13        | 0.51%   |
| Sunplus HD WebCam                                                          | 12        | 0.47%   |
| Realtek Integrated Webcam HD                                               | 12        | 0.47%   |
| Quanta HP Wide Vision HD Camera                                            | 12        | 0.47%   |
| Quanta HD Webcam                                                           | 12        | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 168       | 32.37%  |
| Validity Sensors                   | 132       | 25.43%  |
| Shenzhen Goodix Technology         | 107       | 20.62%  |
| Elan Microelectronics              | 38        | 7.32%   |
| Upek                               | 21        | 4.05%   |
| AuthenTec                          | 21        | 4.05%   |
| LighTuning Technology              | 20        | 3.85%   |
| STMicroelectronics                 | 6         | 1.16%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.58%   |
| Focal-systems.Corp                 | 2         | 0.39%   |
| DigitalPersona                     | 1         | 0.19%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 60        | 11.56%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 55        | 10.6%   |
| Shenzhen Goodix Fingerprint Reader                                         | 30        | 5.78%   |
| Elan ELAN:Fingerprint                                                      | 22        | 4.24%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 21        | 4.05%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 20        | 3.85%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 20        | 3.85%   |
| Synaptics UWP WBDI                                                         | 20        | 3.85%   |
| Shenzhen Goodix FingerPrint                                                | 17        | 3.28%   |
| Validity Sensors Synaptics WBDI                                            | 16        | 3.08%   |
| Elan ELAN:ARM-M4                                                           | 14        | 2.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 2.5%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 12        | 2.31%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 12        | 2.31%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 2.12%   |
| Synaptics WBDI                                                             | 11        | 2.12%   |
| Synaptics  WBDI                                                            | 11        | 2.12%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.12%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 10        | 1.93%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 1.73%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.73%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 8         | 1.54%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.35%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 1.35%   |
| AuthenTec AES2810                                                          | 7         | 1.35%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 1.16%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.16%   |
| Validity Sensors VFS491                                                    | 6         | 1.16%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.16%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.16%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.16%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 0.96%   |
| Unknown                                                                    | 5         | 0.96%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 0.77%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.77%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.77%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.58%   |
| Synaptics WBDI Device                                                      | 2         | 0.39%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 92        | 41.44%  |
| Alcor Micro               | 64        | 28.83%  |
| Upek                      | 14        | 6.31%   |
| O2 Micro                  | 9         | 4.05%   |
| Lenovo                    | 7         | 3.15%   |
| Advanced Card Systems     | 6         | 2.7%    |
| SCM Microsystems          | 4         | 1.8%    |
| Yubico.com                | 3         | 1.35%   |
| OmniKey                   | 3         | 1.35%   |
| Gemalto (was Gemplus)     | 3         | 1.35%   |
| Reiner SCT Kartensysteme  | 2         | 0.9%    |
| Realtek Semiconductor     | 2         | 0.9%    |
| Fujitsu Siemens Computers | 2         | 0.9%    |
| Clay Logic                | 2         | 0.9%    |
| BIT4ID                    | 2         | 0.9%    |
| Watchdata                 | 1         | 0.45%   |
| In Focus Systems          | 1         | 0.45%   |
| Giesecke & Devrient       | 1         | 0.45%   |
| Chicony Electronics       | 1         | 0.45%   |
| Aladdin R.D.              | 1         | 0.45%   |
| Aladdin Knowledge Systems | 1         | 0.45%   |
| Aktiv                     | 1         | 0.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 62        | 27.93%  |
| Broadcom 5880                                                                | 26        | 11.71%  |
| Broadcom 58200                                                               | 25        | 11.26%  |
| Broadcom BCM5880 Secure Applications Processor                               | 24        | 10.81%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 6.76%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 14        | 6.31%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 4.05%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 3.15%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 1.8%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 1.35%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.35%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 2         | 0.9%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.9%    |
| OmniKey CardMan 1021                                                         | 2         | 0.9%    |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.9%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.9%    |
| BIT4ID miniLector EVO                                                        | 2         | 0.9%    |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.9%    |
| Advanced Card Systems ACR39U                                                 | 2         | 0.9%    |
| Watchdata USB Key                                                            | 1         | 0.45%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.45%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.45%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.45%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.45%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.45%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.45%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.45%   |
| Fujitsu Siemens Computers Smartcard Reader D323                              | 1         | 0.45%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.45%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.45%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.45%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.45%   |
| Aktiv Rutoken lite                                                           | 1         | 0.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2651      | 68.4%   |
| 1     | 991       | 25.57%  |
| 2     | 194       | 5.01%   |
| 3     | 20        | 0.52%   |
| 4     | 9         | 0.23%   |
| 6     | 4         | 0.1%    |
| 7     | 3         | 0.08%   |
| 5     | 3         | 0.08%   |
| 9     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 510       | 34.65%  |
| Graphics card            | 244       | 16.58%  |
| Chipcard                 | 192       | 13.04%  |
| Net/wireless             | 174       | 11.82%  |
| Camera                   | 70        | 4.76%   |
| Multimedia controller    | 60        | 4.08%   |
| Sound                    | 41        | 2.79%   |
| Bluetooth                | 40        | 2.72%   |
| Communication controller | 35        | 2.38%   |
| Unassigned class         | 33        | 2.24%   |
| Card reader              | 21        | 1.43%   |
| Storage                  | 16        | 1.09%   |
| Net/ethernet             | 10        | 0.68%   |
| Network                  | 8         | 0.54%   |
| Modem                    | 6         | 0.41%   |
| Storage/ide              | 5         | 0.34%   |
| Firewire controller      | 4         | 0.27%   |
| Dvb card                 | 3         | 0.2%    |

