Kubuntu 23.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Kubuntu 23.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu_23.04/Desktop/README.md) and [notebooks](/Dist/Kubuntu_23.04/Notebook/README.md).

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

Total: 150

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | G3 3779                     | Notebook    | [a6c5553133](https://linux-hardware.org/?probe=a6c5553133) | Jun 30, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [581282a150](https://linux-hardware.org/?probe=581282a150) | Jun 29, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0081fa215e](https://linux-hardware.org/?probe=0081fa215e) | Jun 28, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [7dd7d8e8ea](https://linux-hardware.org/?probe=7dd7d8e8ea) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [c0c2f3ba48](https://linux-hardware.org/?probe=c0c2f3ba48) | Jun 28, 2023 |
| MSI           | H81M-P32                    | Desktop     | [75cbcde6b8](https://linux-hardware.org/?probe=75cbcde6b8) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [9619e6fb09](https://linux-hardware.org/?probe=9619e6fb09) | Jun 27, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7a5a27ddd7](https://linux-hardware.org/?probe=7a5a27ddd7) | Jun 27, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [16c312b7be](https://linux-hardware.org/?probe=16c312b7be) | Jun 26, 2023 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [bd98bbb8c0](https://linux-hardware.org/?probe=bd98bbb8c0) | Jun 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [aab1616d0e](https://linux-hardware.org/?probe=aab1616d0e) | Jun 25, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [f043aedf3c](https://linux-hardware.org/?probe=f043aedf3c) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Google        | Kohaku                      | Notebook    | [f9c3a3efb6](https://linux-hardware.org/?probe=f9c3a3efb6) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [852dad5b6a](https://linux-hardware.org/?probe=852dad5b6a) | Jun 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bf18f8c7dc](https://linux-hardware.org/?probe=bf18f8c7dc) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [ed127d8c21](https://linux-hardware.org/?probe=ed127d8c21) | Jun 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [e4f7f39784](https://linux-hardware.org/?probe=e4f7f39784) | Jun 23, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [e5efed1ac5](https://linux-hardware.org/?probe=e5efed1ac5) | Jun 23, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [f224dfda17](https://linux-hardware.org/?probe=f224dfda17) | Jun 22, 2023 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | Notebook    | [c5f46a6955](https://linux-hardware.org/?probe=c5f46a6955) | Jun 21, 2023 |
| Fujitsu       | D3600-A1 S26361-D3600-A1    | Desktop     | [29e7fc8e13](https://linux-hardware.org/?probe=29e7fc8e13) | Jun 20, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [37292d4c84](https://linux-hardware.org/?probe=37292d4c84) | Jun 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [bfa769b311](https://linux-hardware.org/?probe=bfa769b311) | Jun 20, 2023 |
| Apple         | Mac-F2268DAE                | All in one  | [7cb19a32ac](https://linux-hardware.org/?probe=7cb19a32ac) | Jun 20, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [ac41230354](https://linux-hardware.org/?probe=ac41230354) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [ce819ae3d3](https://linux-hardware.org/?probe=ce819ae3d3) | Jun 18, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [945376fe33](https://linux-hardware.org/?probe=945376fe33) | Jun 17, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [6ecfbb88a0](https://linux-hardware.org/?probe=6ecfbb88a0) | Jun 16, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [e2e55f5267](https://linux-hardware.org/?probe=e2e55f5267) | Jun 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [39d273ec86](https://linux-hardware.org/?probe=39d273ec86) | Jun 15, 2023 |
| Dell          | Latitude E6420              | Notebook    | [f05e0e10e5](https://linux-hardware.org/?probe=f05e0e10e5) | Jun 14, 2023 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | Desktop     | [01f33d2c9b](https://linux-hardware.org/?probe=01f33d2c9b) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [b1eabf98f6](https://linux-hardware.org/?probe=b1eabf98f6) | Jun 14, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [0ec1b06d0c](https://linux-hardware.org/?probe=0ec1b06d0c) | Jun 13, 2023 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [787fa3215e](https://linux-hardware.org/?probe=787fa3215e) | Jun 12, 2023 |
| Dell          | G3 3779                     | Notebook    | [0190c87b35](https://linux-hardware.org/?probe=0190c87b35) | Jun 10, 2023 |
| Seco          | C40 C                       | Desktop     | [4d990c8a0c](https://linux-hardware.org/?probe=4d990c8a0c) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [53ba4689ae](https://linux-hardware.org/?probe=53ba4689ae) | Jun 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [58f4272bee](https://linux-hardware.org/?probe=58f4272bee) | Jun 10, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [cbf7ed91a7](https://linux-hardware.org/?probe=cbf7ed91a7) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [e8b6d763e4](https://linux-hardware.org/?probe=e8b6d763e4) | Jun 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S5... | Notebook    | [0372aa0747](https://linux-hardware.org/?probe=0372aa0747) | Jun 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [6b694e4b4a](https://linux-hardware.org/?probe=6b694e4b4a) | Jun 08, 2023 |
| AZW           | SER V01                     | Mini pc     | [0b7fb76a0b](https://linux-hardware.org/?probe=0b7fb76a0b) | Jun 08, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [810e331444](https://linux-hardware.org/?probe=810e331444) | Jun 07, 2023 |
| Gigabyte      | GA-MA770-US3                | Desktop     | [c22850601d](https://linux-hardware.org/?probe=c22850601d) | Jun 07, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [cb8797fce5](https://linux-hardware.org/?probe=cb8797fce5) | Jun 07, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [53341e2d0d](https://linux-hardware.org/?probe=53341e2d0d) | Jun 07, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [b06a0c9b89](https://linux-hardware.org/?probe=b06a0c9b89) | Jun 06, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [1b78246ef7](https://linux-hardware.org/?probe=1b78246ef7) | Jun 06, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [776a9fb064](https://linux-hardware.org/?probe=776a9fb064) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [b9cd465d98](https://linux-hardware.org/?probe=b9cd465d98) | Jun 05, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [9636642e65](https://linux-hardware.org/?probe=9636642e65) | Jun 04, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [8ef447b2f3](https://linux-hardware.org/?probe=8ef447b2f3) | Jun 03, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [fc8a306ca0](https://linux-hardware.org/?probe=fc8a306ca0) | Jun 03, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [b7a585d1f1](https://linux-hardware.org/?probe=b7a585d1f1) | Jun 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [23e94c534e](https://linux-hardware.org/?probe=23e94c534e) | Jun 01, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [16c536cda1](https://linux-hardware.org/?probe=16c536cda1) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [fc4e2630c0](https://linux-hardware.org/?probe=fc4e2630c0) | Jun 01, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [f02c7845e5](https://linux-hardware.org/?probe=f02c7845e5) | Jun 01, 2023 |
| MSI           | Titan GT77HX 13VH           | Notebook    | [7c3b8ed81d](https://linux-hardware.org/?probe=7c3b8ed81d) | May 29, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [cdc924595c](https://linux-hardware.org/?probe=cdc924595c) | May 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [8fd2003b01](https://linux-hardware.org/?probe=8fd2003b01) | May 28, 2023 |
| ASUSTek       | H81M-A                      | Desktop     | [70714d71f5](https://linux-hardware.org/?probe=70714d71f5) | May 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [2b9c4431c2](https://linux-hardware.org/?probe=2b9c4431c2) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [f5b571be32](https://linux-hardware.org/?probe=f5b571be32) | May 26, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [0d6c86d757](https://linux-hardware.org/?probe=0d6c86d757) | May 25, 2023 |
| Google        | Bluebird                    | Notebook    | [5b41bdf767](https://linux-hardware.org/?probe=5b41bdf767) | May 25, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [b880d4f8c1](https://linux-hardware.org/?probe=b880d4f8c1) | May 23, 2023 |
| ASRock        | X99 Extreme6/ac             | Desktop     | [8e255dc13b](https://linux-hardware.org/?probe=8e255dc13b) | May 22, 2023 |
| Alienware     | 04VWF2 A00                  | Desktop     | [7c09c55150](https://linux-hardware.org/?probe=7c09c55150) | May 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [71ac41efb8](https://linux-hardware.org/?probe=71ac41efb8) | May 20, 2023 |
| BOSGAME       | B95                         | Notebook    | [3d1805a2eb](https://linux-hardware.org/?probe=3d1805a2eb) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| Acer          | Aspire E5-521               | Notebook    | [05227be8bc](https://linux-hardware.org/?probe=05227be8bc) | May 18, 2023 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [61b0585530](https://linux-hardware.org/?probe=61b0585530) | May 18, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [166ec29ce0](https://linux-hardware.org/?probe=166ec29ce0) | May 18, 2023 |
| Unknown       | V00                         | Mini pc     | [79cb590ea8](https://linux-hardware.org/?probe=79cb590ea8) | May 17, 2023 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [0906223758](https://linux-hardware.org/?probe=0906223758) | May 17, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [0331ab9725](https://linux-hardware.org/?probe=0331ab9725) | May 16, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [14edb35e71](https://linux-hardware.org/?probe=14edb35e71) | May 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [98ebdcd589](https://linux-hardware.org/?probe=98ebdcd589) | May 15, 2023 |
| HP            | 3397                        | Desktop     | [17d9dcc121](https://linux-hardware.org/?probe=17d9dcc121) | May 15, 2023 |
| HP            | ENVY TS 15                  | Notebook    | [f90de81324](https://linux-hardware.org/?probe=f90de81324) | May 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [58557ae6a2](https://linux-hardware.org/?probe=58557ae6a2) | May 12, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [d8c0bd3bff](https://linux-hardware.org/?probe=d8c0bd3bff) | May 12, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [094fd8b39a](https://linux-hardware.org/?probe=094fd8b39a) | May 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [c071e02f0d](https://linux-hardware.org/?probe=c071e02f0d) | May 12, 2023 |
| Dell          | Latitude E5470              | Notebook    | [59c95182ec](https://linux-hardware.org/?probe=59c95182ec) | May 11, 2023 |
| Intel         | H61                         | Desktop     | [57ef0f0f97](https://linux-hardware.org/?probe=57ef0f0f97) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c80f41d509](https://linux-hardware.org/?probe=c80f41d509) | May 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [8d1f016621](https://linux-hardware.org/?probe=8d1f016621) | May 08, 2023 |
| HP            | Laptop 15-da2xxx            | Notebook    | [8f08aa189f](https://linux-hardware.org/?probe=8f08aa189f) | May 08, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [c075073dd8](https://linux-hardware.org/?probe=c075073dd8) | May 07, 2023 |
| Biostar       | AM1MHP                      | Desktop     | [1f21e13fcd](https://linux-hardware.org/?probe=1f21e13fcd) | May 07, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | Notebook    | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Google        | Lars                        | Notebook    | [db3ba59095](https://linux-hardware.org/?probe=db3ba59095) | May 06, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [68b1e1e6cb](https://linux-hardware.org/?probe=68b1e1e6cb) | May 05, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [f6251eeeb1](https://linux-hardware.org/?probe=f6251eeeb1) | May 05, 2023 |
| Medion        | E11201                      | Notebook    | [f0bfd835f8](https://linux-hardware.org/?probe=f0bfd835f8) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [1f2d88bfae](https://linux-hardware.org/?probe=1f2d88bfae) | May 04, 2023 |
| Gigabyte      | H87-HD3                     | Desktop     | [f0e4057e5f](https://linux-hardware.org/?probe=f0e4057e5f) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [861ca2dca3](https://linux-hardware.org/?probe=861ca2dca3) | May 03, 2023 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [1846ea93e7](https://linux-hardware.org/?probe=1846ea93e7) | May 01, 2023 |
| HP            | 828A                        | Desktop     | [f1590b355f](https://linux-hardware.org/?probe=f1590b355f) | Apr 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1ccae7d268](https://linux-hardware.org/?probe=1ccae7d268) | Apr 28, 2023 |
| ASUSTek       | X51RL                       | Notebook    | [0d18de9922](https://linux-hardware.org/?probe=0d18de9922) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [442a827555](https://linux-hardware.org/?probe=442a827555) | Apr 27, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [fee636a549](https://linux-hardware.org/?probe=fee636a549) | Apr 26, 2023 |
| Samsung       | 950XED                      | Notebook    | [02586ee1ba](https://linux-hardware.org/?probe=02586ee1ba) | Apr 26, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [4285b1a3d9](https://linux-hardware.org/?probe=4285b1a3d9) | Apr 25, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [b03c4808b0](https://linux-hardware.org/?probe=b03c4808b0) | Apr 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [38806ed70c](https://linux-hardware.org/?probe=38806ed70c) | Apr 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [0fde788ea5](https://linux-hardware.org/?probe=0fde788ea5) | Apr 24, 2023 |
| Foxconn       | H67M-S/H67M-V/H67           | Desktop     | [92fa61186f](https://linux-hardware.org/?probe=92fa61186f) | Apr 23, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [fa5d5b4733](https://linux-hardware.org/?probe=fa5d5b4733) | Apr 23, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [d7648edaab](https://linux-hardware.org/?probe=d7648edaab) | Apr 23, 2023 |
| Dell          | Precision 5520              | Notebook    | [4d1dd8b673](https://linux-hardware.org/?probe=4d1dd8b673) | Apr 23, 2023 |
| Gigabyte      | AORUS 15P XD                | Notebook    | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [475a4d151d](https://linux-hardware.org/?probe=475a4d151d) | Apr 22, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [f7528e9759](https://linux-hardware.org/?probe=f7528e9759) | Apr 22, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [3165ab3194](https://linux-hardware.org/?probe=3165ab3194) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [918115dc84](https://linux-hardware.org/?probe=918115dc84) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [3d241113f4](https://linux-hardware.org/?probe=3d241113f4) | Apr 21, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [cb295448b6](https://linux-hardware.org/?probe=cb295448b6) | Apr 21, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [93f1374055](https://linux-hardware.org/?probe=93f1374055) | Apr 01, 2023 |
| Samsung       | 950QDB                      | Convertible | [09717388fb](https://linux-hardware.org/?probe=09717388fb) | Mar 31, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [cdc4b03fe2](https://linux-hardware.org/?probe=cdc4b03fe2) | Mar 26, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [b20f8089c3](https://linux-hardware.org/?probe=b20f8089c3) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [d3821bdbab](https://linux-hardware.org/?probe=d3821bdbab) | Feb 26, 2023 |
| Samsung       | 950QDB                      | Convertible | [2545626207](https://linux-hardware.org/?probe=2545626207) | Feb 23, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [1942c9f528](https://linux-hardware.org/?probe=1942c9f528) | Feb 11, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [a84d546f50](https://linux-hardware.org/?probe=a84d546f50) | Feb 02, 2023 |
| Dell          | G3 3779                     | Notebook    | [c4c13ca86b](https://linux-hardware.org/?probe=c4c13ca86b) | Jan 19, 2023 |
| MSI           | Bravo 17 A4DDK              | Notebook    | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 6.2.0-20-generic        | 72        | 59.5%   |
| 6.2.0-23-generic        | 15        | 12.4%   |
| 6.2.0-18-generic        | 4         | 3.31%   |
| 6.2.0-1003-lowlatency   | 3         | 2.48%   |
| 6.2.0-24-generic        | 2         | 1.65%   |
| 6.2.0-1005-lowlatency   | 2         | 1.65%   |
| 5.19.0-28-generic       | 2         | 1.65%   |
| 6.3.8-x64v3-xanmod1     | 1         | 0.83%   |
| 6.3.8                   | 1         | 0.83%   |
| 6.3.6-custom            | 1         | 0.83%   |
| 6.3.5-060305-generic    | 1         | 0.83%   |
| 6.3.4-060304-generic    | 1         | 0.83%   |
| 6.3.3-060303-generic    | 1         | 0.83%   |
| 6.3.1-custom            | 1         | 0.83%   |
| 6.3.1-060301-generic    | 1         | 0.83%   |
| 6.2.5-060205-generic    | 1         | 0.83%   |
| 6.2.10-060210-generic   | 1         | 0.83%   |
| 6.2.0-21-generic        | 1         | 0.83%   |
| 6.2.0-060200-generic    | 1         | 0.83%   |
| 6.1.12-060112-generic   | 1         | 0.83%   |
| 6.1.11-custom           | 1         | 0.83%   |
| 6.1.0-16-generic        | 1         | 0.83%   |
| 6.1.0-14-generic        | 1         | 0.83%   |
| 6.1.0-060100rc4-generic | 1         | 0.83%   |
| 5.19.0-42-generic       | 1         | 0.83%   |
| 5.19.0-40-generic       | 1         | 0.83%   |
| 5.19.0-21-generic       | 1         | 0.83%   |
| 5.19.0-1023-lowlatency  | 1         | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.0   | 98        | 82.35%  |
| 5.19.0  | 6         | 5.04%   |
| 6.1.0   | 3         | 2.52%   |
| 6.3.8   | 2         | 1.68%   |
| 6.3.1   | 2         | 1.68%   |
| 6.3.6   | 1         | 0.84%   |
| 6.3.5   | 1         | 0.84%   |
| 6.3.4   | 1         | 0.84%   |
| 6.3.3   | 1         | 0.84%   |
| 6.2.5   | 1         | 0.84%   |
| 6.2.10  | 1         | 0.84%   |
| 6.1.12  | 1         | 0.84%   |
| 6.1.11  | 1         | 0.84%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 100       | 84.03%  |
| 6.3     | 8         | 6.72%   |
| 5.19    | 6         | 5.04%   |
| 6.1     | 5         | 4.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 117       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| KDE5  | 111       | 94.87%  |
| KDE   | 4         | 3.42%   |
| LXQt  | 1         | 0.85%   |
| GNOME | 1         | 0.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 93        | 78.81%  |
| Wayland | 24        | 20.34%  |
| Tty     | 1         | 0.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 68        | 58.12%  |
| Unknown | 44        | 37.61%  |
| GDM3    | 3         | 2.56%   |
| LightDM | 2         | 1.71%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang   | Computers | Percent |
|--------|-----------|---------|
| en_US  | 54        | 46.15%  |
| de_DE  | 11        | 9.4%    |
| en_GB  | 8         | 6.84%   |
| ru_RU  | 5         | 4.27%   |
| it_IT  | 5         | 4.27%   |
| fr_FR  | 5         | 4.27%   |
| pl_PL  | 4         | 3.42%   |
| pt_BR  | 2         | 1.71%   |
| es_CR  | 2         | 1.71%   |
| es_CL  | 2         | 1.71%   |
| en_NZ  | 2         | 1.71%   |
| en_IN  | 2         | 1.71%   |
| en_AU  | 2         | 1.71%   |
| zh_TW  | 1         | 0.85%   |
| sv_SE  | 1         | 0.85%   |
| pt_PT  | 1         | 0.85%   |
| nl_NL  | 1         | 0.85%   |
| hu_HU  | 1         | 0.85%   |
| fr_BE  | 1         | 0.85%   |
| es_MX  | 1         | 0.85%   |
| es_ES  | 1         | 0.85%   |
| es_CO  | 1         | 0.85%   |
| es_419 | 1         | 0.85%   |
| en_IL  | 1         | 0.85%   |
| en_CA  | 1         | 0.85%   |
| C      | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 63        | 53.39%  |
| EFI  | 55        | 46.61%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 81        | 68.07%  |
| Tmpfs   | 23        | 19.33%  |
| Btrfs   | 8         | 6.72%   |
| Overlay | 3         | 2.52%   |
| Zfs     | 2         | 1.68%   |
| Xfs     | 1         | 0.84%   |
| F2fs    | 1         | 0.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 69        | 58.97%  |
| Unknown | 44        | 37.61%  |
| MBR     | 4         | 3.42%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 109       | 91.6%   |
| Yes       | 10        | 8.4%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 86        | 73.5%   |
| Yes       | 31        | 26.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 20        | 17.09%  |
| ASUSTek Computer    | 19        | 16.24%  |
| Hewlett-Packard     | 18        | 15.38%  |
| Gigabyte Technology | 9         | 7.69%   |
| Dell                | 8         | 6.84%   |
| Apple               | 7         | 5.98%   |
| MSI                 | 5         | 4.27%   |
| Acer                | 4         | 3.42%   |
| Intel               | 3         | 2.56%   |
| HUAWEI              | 3         | 2.56%   |
| Google              | 3         | 2.56%   |
| Samsung Electronics | 2         | 1.71%   |
| Fujitsu             | 2         | 1.71%   |
| AZW                 | 2         | 1.71%   |
| ASRock              | 2         | 1.71%   |
| Unknown             | 2         | 1.71%   |
| Seco                | 1         | 0.85%   |
| Medion              | 1         | 0.85%   |
| Framework           | 1         | 0.85%   |
| Foxconn             | 1         | 0.85%   |
| BOSGAME             | 1         | 0.85%   |
| Biostar             | 1         | 0.85%   |
| BESSTAR Tech        | 1         | 0.85%   |
| Alienware           | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                               | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Dell G3 3779                                       | 2         | 1.71%   |
| AZW SER                                            | 2         | 1.71%   |
| ASUS ASUS TUF Gaming F17 FX706LI_FX706LI           | 2         | 1.71%   |
| Unknown                                            | 2         | 1.71%   |
| Seco C40                                           | 1         | 0.85%   |
| Samsung 950XED                                     | 1         | 0.85%   |
| Samsung 950QDB                                     | 1         | 0.85%   |
| MSI Titan GT77HX 13VH                              | 1         | 0.85%   |
| MSI Raider GE67HX 12UGS                            | 1         | 0.85%   |
| MSI MS-7846                                        | 1         | 0.85%   |
| MSI MS-7693                                        | 1         | 0.85%   |
| MSI Bravo 17 A4DDK                                 | 1         | 0.85%   |
| Medion E11201                                      | 1         | 0.85%   |
| Lenovo Yoga 6 13ALC7 82UD                          | 1         | 0.85%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HMCTO1WW        | 1         | 0.85%   |
| Lenovo ThinkPad P15s Gen 2i 20W7S0SM01             | 1         | 0.85%   |
| Lenovo ThinkPad P14s Gen 1 20S5S01V00              | 1         | 0.85%   |
| Lenovo ThinkPad P1 Gen 2 20QT000LGE                | 1         | 0.85%   |
| Lenovo ThinkPad L15 Gen 2a 20X7S05600              | 1         | 0.85%   |
| Lenovo ThinkPad E15 Gen 4 21EES00100               | 1         | 0.85%   |
| Lenovo ThinkPad E15 Gen 4 21EDCTO1WW               | 1         | 0.85%   |
| Lenovo ThinkPad E15 Gen 2 20TD00GSPB               | 1         | 0.85%   |
| Lenovo ThinkPad E14 Gen 4 21ECS00000               | 1         | 0.85%   |
| Lenovo ThinkPad E14 Gen 3 20YDS02D00               | 1         | 0.85%   |
| Lenovo ThinkBook 14 G4 ABA 21DK                    | 1         | 0.85%   |
| Lenovo Slim 7 ProX 14ARH7 82V2                     | 1         | 0.85%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                   | 1         | 0.85%   |
| Lenovo IdeaPad Y700-15ISK 80NV                     | 1         | 0.85%   |
| Lenovo IdeaPad S340-14IIL 81VV                     | 1         | 0.85%   |
| Lenovo IdeaPad 700-17ISK 80RV                      | 1         | 0.85%   |
| Lenovo IdeaPad 5 Pro 16ARH7 82SN                   | 1         | 0.85%   |
| Lenovo IdeaPad 3 15IAU7 82RK                       | 1         | 0.85%   |
| Lenovo IdeaPad 3 15ALC6 82MF                       | 1         | 0.85%   |
| Intel SHARKBAY                                     | 1         | 0.85%   |
| Intel NUC12WSHi7                                   | 1         | 0.85%   |
| Intel H61                                          | 1         | 0.85%   |
| HUAWEI NBD-WXX9                                    | 1         | 0.85%   |
| HUAWEI HN-WX9X                                     | 1         | 0.85%   |
| HUAWEI BOHB-WAX9                                   | 1         | 0.85%   |
| HP ZBook Studio 15.6 inch G8 Mobile Workstation PC | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 10        | 8.55%   |
| Lenovo IdeaPad    | 6         | 5.13%   |
| HP Pavilion       | 4         | 3.42%   |
| HP ENVY           | 3         | 2.56%   |
| Dell Latitude     | 3         | 2.56%   |
| ASUS ROG          | 3         | 2.56%   |
| ASUS ASUS         | 3         | 2.56%   |
| Acer Aspire       | 3         | 2.56%   |
| HP ProBook        | 2         | 1.71%   |
| HP Laptop         | 2         | 1.71%   |
| HP EliteBook      | 2         | 1.71%   |
| HP Compaq         | 2         | 1.71%   |
| Gigabyte G5       | 2         | 1.71%   |
| Dell Inspiron     | 2         | 1.71%   |
| Dell G3           | 2         | 1.71%   |
| AZW SER           | 2         | 1.71%   |
| ASUS Zenbook      | 2         | 1.71%   |
| ASUS VivoBook     | 2         | 1.71%   |
| ASUS PRIME        | 2         | 1.71%   |
| Apple MacBookPro9 | 2         | 1.71%   |
| Unknown           | 2         | 1.71%   |
| Seco C40          | 1         | 0.85%   |
| Samsung 950XED    | 1         | 0.85%   |
| Samsung 950QDB    | 1         | 0.85%   |
| MSI Titan         | 1         | 0.85%   |
| MSI Raider        | 1         | 0.85%   |
| MSI MS-7846       | 1         | 0.85%   |
| MSI MS-7693       | 1         | 0.85%   |
| MSI Bravo         | 1         | 0.85%   |
| Medion E11201     | 1         | 0.85%   |
| Lenovo Yoga       | 1         | 0.85%   |
| Lenovo ThinkBook  | 1         | 0.85%   |
| Lenovo Slim       | 1         | 0.85%   |
| Lenovo Legion     | 1         | 0.85%   |
| Intel SHARKBAY    | 1         | 0.85%   |
| Intel NUC12WSHi7  | 1         | 0.85%   |
| Intel H61         | 1         | 0.85%   |
| HUAWEI NBD-WXX9   | 1         | 0.85%   |
| HUAWEI HN-WX9X    | 1         | 0.85%   |
| HUAWEI BOHB-WAX9  | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2022 | 27        | 23.08%  |
| 2021 | 22        | 18.8%   |
| 2019 | 12        | 10.26%  |
| 2020 | 7         | 5.98%   |
| 2018 | 7         | 5.98%   |
| 2012 | 7         | 5.98%   |
| 2023 | 5         | 4.27%   |
| 2013 | 5         | 4.27%   |
| 2011 | 5         | 4.27%   |
| 2016 | 4         | 3.42%   |
| 2014 | 4         | 3.42%   |
| 2017 | 3         | 2.56%   |
| 2015 | 3         | 2.56%   |
| 2009 | 3         | 2.56%   |
| 2010 | 2         | 1.71%   |
| 2007 | 1         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 76        | 64.96%  |
| Desktop     | 28        | 23.93%  |
| Convertible | 5         | 4.27%   |
| Mini pc     | 4         | 3.42%   |
| All in one  | 3         | 2.56%   |
| Tablet      | 1         | 0.85%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 110       | 94.02%  |
| Enabled  | 7         | 5.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 114       | 97.44%  |
| Yes  | 3         | 2.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 35        | 29.91%  |
| 16.01-24.0  | 23        | 19.66%  |
| 4.01-8.0    | 20        | 17.09%  |
| 32.01-64.0  | 15        | 12.82%  |
| 3.01-4.0    | 12        | 10.26%  |
| 64.01-256.0 | 7         | 5.98%   |
| 24.01-32.0  | 4         | 3.42%   |
| 2.01-3.0    | 1         | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 40        | 33.33%  |
| 2.01-3.0   | 30        | 25%     |
| 3.01-4.0   | 21        | 17.5%   |
| 1.01-2.0   | 21        | 17.5%   |
| 8.01-16.0  | 7         | 5.83%   |
| 32.01-64.0 | 1         | 0.83%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 73        | 60.83%  |
| 2      | 32        | 26.67%  |
| 3      | 10        | 8.33%   |
| 4      | 3         | 2.5%    |
| 7      | 2         | 1.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 94        | 79.66%  |
| Yes       | 24        | 20.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 75.42%  |
| No        | 29        | 24.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 87.18%  |
| No        | 15        | 12.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 75.21%  |
| No        | 29        | 24.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 25        | 21.37%  |
| Germany      | 15        | 12.82%  |
| UK           | 9         | 7.69%   |
| Poland       | 6         | 5.13%   |
| Russia       | 5         | 4.27%   |
| Italy        | 5         | 4.27%   |
| France       | 5         | 4.27%   |
| Belgium      | 4         | 3.42%   |
| India        | 3         | 2.56%   |
| Canada       | 3         | 2.56%   |
| Turkey       | 2         | 1.71%   |
| Sweden       | 2         | 1.71%   |
| Spain        | 2         | 1.71%   |
| Serbia       | 2         | 1.71%   |
| Portugal     | 2         | 1.71%   |
| New Zealand  | 2         | 1.71%   |
| Netherlands  | 2         | 1.71%   |
| Mexico       | 2         | 1.71%   |
| Israel       | 2         | 1.71%   |
| Costa Rica   | 2         | 1.71%   |
| Colombia     | 2         | 1.71%   |
| Chile        | 2         | 1.71%   |
| Brazil       | 2         | 1.71%   |
| Australia    | 2         | 1.71%   |
| Taiwan       | 1         | 0.85%   |
| Saudi Arabia | 1         | 0.85%   |
| Lithuania    | 1         | 0.85%   |
| Ivory Coast  | 1         | 0.85%   |
| Indonesia    | 1         | 0.85%   |
| Hungary      | 1         | 0.85%   |
| Bulgaria     | 1         | 0.85%   |
| Armenia      | 1         | 0.85%   |
| Argentina    | 1         | 0.85%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| London                  | 3         | 2.56%   |
| Valley Center           | 2         | 1.71%   |
| Munich                  | 2         | 1.71%   |
| Moscow                  | 2         | 1.71%   |
| Istanbul                | 2         | 1.71%   |
| Hamburg                 | 2         | 1.71%   |
| Grecia                  | 2         | 1.71%   |
| Brussels                | 2         | 1.71%   |
| Berlin                  | 2         | 1.71%   |
| Yerevan                 | 1         | 0.85%   |
| West Des Moines         | 1         | 0.85%   |
| Weilmuenster            | 1         | 0.85%   |
| Warsaw                  | 1         | 0.85%   |
| Waldorf                 | 1         | 0.85%   |
| Waianae                 | 1         | 0.85%   |
| Vsevolozhsk             | 1         | 0.85%   |
| Viña del Mar           | 1         | 0.85%   |
| Vilnius                 | 1         | 0.85%   |
| Villa Dominico          | 1         | 0.85%   |
| Vienna                  | 1         | 0.85%   |
| Thunder Bay             | 1         | 0.85%   |
| Theydon Bois            | 1         | 0.85%   |
| Tel Aviv                | 1         | 0.85%   |
| Taichung                | 1         | 0.85%   |
| Szczecin                | 1         | 0.85%   |
| Sydney                  | 1         | 0.85%   |
| Sutton                  | 1         | 0.85%   |
| Sumter                  | 1         | 0.85%   |
| Stavropol               | 1         | 0.85%   |
| Shumen                  | 1         | 0.85%   |
| Sherbrooke              | 1         | 0.85%   |
| Santiago                | 1         | 0.85%   |
| Santa Maria di Sala     | 1         | 0.85%   |
| Salt Lake City          | 1         | 0.85%   |
| Saint-Georges-sur-Meuse | 1         | 0.85%   |
| Saarbrücken            | 1         | 0.85%   |
| Rzeszów                | 1         | 0.85%   |
| Roubaix                 | 1         | 0.85%   |
| Rewal                   | 1         | 0.85%   |
| Remeteszolos            | 1         | 0.85%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 30        | 46     | 17.96%  |
| WDC                         | 17        | 21     | 10.18%  |
| Seagate                     | 14        | 19     | 8.38%   |
| SanDisk                     | 11        | 11     | 6.59%   |
| Micron Technology           | 10        | 10     | 5.99%   |
| Kingston                    | 10        | 12     | 5.99%   |
| SK hynix                    | 9         | 9      | 5.39%   |
| Toshiba                     | 8         | 9      | 4.79%   |
| Intel                       | 7         | 8      | 4.19%   |
| Crucial                     | 6         | 6      | 3.59%   |
| Unknown                     | 4         | 4      | 2.4%    |
| Phison Electronics          | 4         | 4      | 2.4%    |
| Hitachi                     | 3         | 3      | 1.8%    |
| A-DATA Technology           | 3         | 3      | 1.8%    |
| UMIS                        | 2         | 3      | 1.2%    |
| Solid State Storage         | 2         | 2      | 1.2%    |
| Silicon Motion              | 2         | 2      | 1.2%    |
| Patriot                     | 2         | 2      | 1.2%    |
| Micron/Crucial Technology   | 2         | 2      | 1.2%    |
| Kingston Technology Company | 2         | 2      | 1.2%    |
| WALRAM                      | 1         | 1      | 0.6%    |
| Union Memory (Shenzhen)     | 1         | 1      | 0.6%    |
| SSSTC                       | 1         | 1      | 0.6%    |
| SSDPR-CX                    | 1         | 1      | 0.6%    |
| SPCC                        | 1         | 5      | 0.6%    |
| PNY                         | 1         | 1      | 0.6%    |
| Phison                      | 1         | 1      | 0.6%    |
| Maxtor                      | 1         | 1      | 0.6%    |
| Lexar                       | 1         | 1      | 0.6%    |
| Lenovo                      | 1         | 1      | 0.6%    |
| JMicron Technology          | 1         | 1      | 0.6%    |
| Hoodisk                     | 1         | 1      | 0.6%    |
| HGST                        | 1         | 1      | 0.6%    |
| Gigabyte Technology         | 1         | 1      | 0.6%    |
| FURY                        | 1         | 2      | 0.6%    |
| CT2000BX                    | 1         | 1      | 0.6%    |
| China                       | 1         | 1      | 0.6%    |
| Apple                       | 1         | 1      | 0.6%    |
| Unknown                     | 1         | 1      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Intel SSD 660P Series 512GB                        | 4         | 2.15%   |
| Seagate ST4000DM004-2CV104 4TB                     | 3         | 1.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 3         | 1.61%   |
| Phison E16 PCIe4 NVMe Controller 1TB               | 3         | 1.61%   |
| WDC WD5000AAKX-60U6AA0 500GB                       | 2         | 1.08%   |
| Unknown MMC Card  32GB                             | 2         | 1.08%   |
| UMIS RPJTJ512MGE1QDQ 512GB                         | 2         | 1.08%   |
| Seagate ST1000DM003-1ER162 1TB                     | 2         | 1.08%   |
| SanDisk NVMe SSD Drive 2TB                         | 2         | 1.08%   |
| SanDisk NVMe SSD Drive 1TB                         | 2         | 1.08%   |
| Samsung SSD 980 PRO 2TB                            | 2         | 1.08%   |
| Samsung SSD 850 PRO 512GB                          | 2         | 1.08%   |
| Samsung MZVLQ256HAJD-000H1 256GB                   | 2         | 1.08%   |
| Samsung MZVL21T0HCLR-00B00 1TB                     | 2         | 1.08%   |
| Kingston SNVS500G 500GB                            | 2         | 1.08%   |
| Kingston SA400S37480G 480GB SSD                    | 2         | 1.08%   |
| Kingston SA400S37120G 120GB SSD                    | 2         | 1.08%   |
| Crucial CT1000MX500SSD1 1TB                        | 2         | 1.08%   |
| WDC WDS500G2B0A 500GB SSD                          | 1         | 0.54%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                     | 1         | 0.54%   |
| WDC WDS200T2B0A-00SM50 2TB SSD                     | 1         | 0.54%   |
| WDC WDBNCE5000PNC 500GB SSD                        | 1         | 0.54%   |
| WDC WD5000AAKS-40V2B0 500GB                        | 1         | 0.54%   |
| WDC WD3200AAJS-65M0A0 320GB                        | 1         | 0.54%   |
| WDC WD20EARX-00PASB0 2TB                           | 1         | 0.54%   |
| WDC WD16 00AVBB-63SYA0 160GB                       | 1         | 0.54%   |
| WDC WD10SPZX-24Z10 1TB                             | 1         | 0.54%   |
| WDC WD10EZEX-08M2NA0 1TB                           | 1         | 0.54%   |
| WDC WD10EFRX-68JCSN0 1TB                           | 1         | 0.54%   |
| WDC WD10EAVS-32D7B1 1TB                            | 1         | 0.54%   |
| WDC WD1001FALS-40U9B0 1TB                          | 1         | 0.54%   |
| WDC WD10 JPVX-00JC3T0 1TB                          | 1         | 0.54%   |
| WDC WD Green 2.5 1000GB SSD                        | 1         | 0.54%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB               | 1         | 0.54%   |
| WDC PC SN520 SDAPMUW-256G-1101 256GB               | 1         | 0.54%   |
| WALRAM 240G                                        | 1         | 0.54%   |
| Unknown SD/MMC/MS PRO 250GB                        | 1         | 0.54%   |
| Unknown Biwin  64GB                                | 1         | 0.54%   |
| Union Memory (Shenzhen) RPFTJ256PDD2MWX 256GB      | 1         | 0.54%   |
| Toshiba XG6 NVMe SSD Controller 2TB                | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 19     | 37.84%  |
| WDC                 | 11        | 13     | 29.73%  |
| Toshiba             | 5         | 5      | 13.51%  |
| Hitachi             | 3         | 3      | 8.11%   |
| Unknown             | 1         | 1      | 2.7%    |
| Samsung Electronics | 1         | 1      | 2.7%    |
| Maxtor              | 1         | 1      | 2.7%    |
| HGST                | 1         | 1      | 2.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 7         | 13     | 15.22%  |
| Kingston            | 7         | 9      | 15.22%  |
| WDC                 | 5         | 6      | 10.87%  |
| Crucial             | 5         | 5      | 10.87%  |
| Micron Technology   | 4         | 4      | 8.7%    |
| SanDisk             | 3         | 3      | 6.52%   |
| Patriot             | 2         | 2      | 4.35%   |
| Intel               | 2         | 3      | 4.35%   |
| A-DATA Technology   | 2         | 2      | 4.35%   |
| SPCC                | 1         | 5      | 2.17%   |
| SK hynix            | 1         | 1      | 2.17%   |
| PNY                 | 1         | 1      | 2.17%   |
| Lenovo              | 1         | 1      | 2.17%   |
| Hoodisk             | 1         | 1      | 2.17%   |
| Gigabyte Technology | 1         | 1      | 2.17%   |
| FURY                | 1         | 1      | 2.17%   |
| CT2000BX            | 1         | 1      | 2.17%   |
| China               | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 72        | 91     | 46.75%  |
| SSD     | 44        | 60     | 28.57%  |
| HDD     | 31        | 44     | 20.13%  |
| Unknown | 4         | 4      | 2.6%    |
| MMC     | 3         | 3      | 1.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 71        | 90     | 50.35%  |
| SATA | 60        | 102    | 42.55%  |
| SAS  | 7         | 7      | 4.96%   |
| MMC  | 3         | 3      | 2.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 41        | 55     | 51.25%  |
| 0.51-1.0   | 26        | 32     | 32.5%   |
| 1.01-2.0   | 10        | 13     | 12.5%   |
| 3.01-4.0   | 3         | 4      | 3.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 33        | 27.73%  |
| 501-1000       | 25        | 21.01%  |
| 251-500        | 21        | 17.65%  |
| 1001-2000      | 14        | 11.76%  |
| More than 3000 | 10        | 8.4%    |
| 2001-3000      | 5         | 4.2%    |
| 1-20           | 4         | 3.36%   |
| 51-100         | 4         | 3.36%   |
| 21-50          | 3         | 2.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 30        | 24.79%  |
| 1-20           | 26        | 21.49%  |
| 101-250        | 16        | 13.22%  |
| 251-500        | 14        | 11.57%  |
| 51-100         | 14        | 11.57%  |
| 1001-2000      | 9         | 7.44%   |
| 501-1000       | 8         | 6.61%   |
| More than 3000 | 3         | 2.48%   |
| 2001-3000      | 1         | 0.83%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-65M0A0 320GB                  | 1         | 1      | 25%     |
| Toshiba MQ01ABD075 752GB                     | 1         | 1      | 25%     |
| SK hynix HFS256G32MND-2900A 256GB SSD        | 1         | 1      | 25%     |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 2      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 25%     |
| Toshiba             | 1         | 1      | 25%     |
| SK hynix            | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 2      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Toshiba | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 3      | 50%     |
| HDD  | 2         | 2      | 50%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 960 EVO 250GB | 1         | 2      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 75        | 131    | 60.48%  |
| Works    | 44        | 64     | 35.48%  |
| Malfunc  | 4         | 5      | 3.23%   |
| Failed   | 1         | 2      | 0.81%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 61        | 38.13%  |
| Samsung Electronics            | 24        | 15%     |
| AMD                            | 22        | 13.75%  |
| SanDisk                        | 10        | 6.25%   |
| SK hynix                       | 8         | 5%      |
| Micron Technology              | 6         | 3.75%   |
| Phison Electronics             | 5         | 3.13%   |
| Kingston Technology Company    | 4         | 2.5%    |
| Union Memory (Shenzhen)        | 3         | 1.88%   |
| Toshiba America Info Systems   | 3         | 1.88%   |
| Solid State Storage Technology | 3         | 1.88%   |
| Micron/Crucial Technology      | 3         | 1.88%   |
| Silicon Motion                 | 2         | 1.25%   |
| Silicon Image                  | 1         | 0.63%   |
| Shenzhen Longsys Electronics   | 1         | 0.63%   |
| Nvidia                         | 1         | 0.63%   |
| JMicron Technology             | 1         | 0.63%   |
| Apple                          | 1         | 0.63%   |
| ADATA Technology               | 1         | 0.63%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 16        | 9.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 5.29%   |
| Samsung NVMe SSD Controller 980                                                | 8         | 4.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 4.71%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 7         | 4.12%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 3.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 2.94%   |
| Micron NVMe Storage Controller                                                 | 5         | 2.94%   |
| Intel Volume Management Device NVMe RAID Controller                            | 5         | 2.94%   |
| SanDisk Non-Volatile memory controller                                         | 4         | 2.35%   |
| Intel SSD 660P Series                                                          | 4         | 2.35%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 1.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 1.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.76%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.76%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 1.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 3         | 1.76%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.76%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 x4 NVMe SSD Controller                  | 2         | 1.18%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.18%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                 | 2         | 1.18%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.18%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 1.18%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 1.18%   |
| Kingston Company NVMe Controller                                               | 2         | 1.18%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 1.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.18%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 2         | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 1.18%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 1.18%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.59%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.59%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.59%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.59%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.59%   |
| Silicon Motion Non-Volatile memory controller                                  | 1         | 0.59%   |
| Silicon Image SiI 3132 Serial ATA Raid II Controller                           | 1         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 74        | 46.84%  |
| NVMe | 71        | 44.94%  |
| RAID | 10        | 6.33%   |
| IDE  | 3         | 1.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 78        | 66.67%  |
| AMD    | 39        | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 5 5500U with Radeon Graphics      | 7         | 5.98%   |
| Intel 12th Gen Core i7-1260P                | 3         | 2.56%   |
| AMD Ryzen 7 6800H with Radeon Graphics      | 3         | 2.56%   |
| AMD Ryzen 7 5825U with Radeon Graphics      | 3         | 2.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 1.71%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2         | 1.71%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.71%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 2         | 1.71%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 1.71%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.71%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 1.71%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 2         | 1.71%   |
| AMD Ryzen 5 5600U with Radeon Graphics      | 2         | 1.71%   |
| Intel Xeon CPU E3-1240 v3 @ 3.40GHz         | 1         | 0.85%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz      | 1         | 0.85%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.85%   |
| Intel Pentium CPU G3220 @ 3.00GHz           | 1         | 0.85%   |
| Intel Pentium CPU 6405U @ 2.40GHz           | 1         | 0.85%   |
| Intel N95                                   | 1         | 0.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.85%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 1         | 0.85%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.85%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz          | 1         | 0.85%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 1         | 0.85%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 1         | 0.85%   |
| Intel Core i7-5820K CPU @ 3.30GHz           | 1         | 0.85%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 1         | 0.85%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz          | 1         | 0.85%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 1         | 0.85%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 1         | 0.85%   |
| Intel Core i7-3615QM CPU @ 2.30GHz          | 1         | 0.85%   |
| Intel Core i7-3537U CPU @ 2.00GHz           | 1         | 0.85%   |
| Intel Core i7-2640M CPU @ 2.80GHz           | 1         | 0.85%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 1         | 0.85%   |
| Intel Core i7-10610U CPU @ 1.80GHz          | 1         | 0.85%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 1         | 0.85%   |
| Intel Core i5-9600KF CPU @ 3.70GHz          | 1         | 0.85%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 0.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Other                   | 22        | 18.8%   |
| Intel Core i7           | 22        | 18.8%   |
| Intel Core i5           | 21        | 17.95%  |
| AMD Ryzen 7             | 15        | 12.82%  |
| AMD Ryzen 5             | 12        | 10.26%  |
| Intel Celeron           | 5         | 4.27%   |
| AMD Ryzen 9             | 4         | 3.42%   |
| Intel Pentium           | 2         | 1.71%   |
| Intel Core 2 Duo        | 2         | 1.71%   |
| AMD FX                  | 2         | 1.71%   |
| Intel Xeon              | 1         | 0.85%   |
| Intel Pentium Gold      | 1         | 0.85%   |
| Intel Pentium Dual-Core | 1         | 0.85%   |
| Intel Core i3           | 1         | 0.85%   |
| AMD Ryzen Embedded      | 1         | 0.85%   |
| AMD Ryzen 5 PRO         | 1         | 0.85%   |
| AMD Ryzen 3 PRO         | 1         | 0.85%   |
| AMD Athlon II X3        | 1         | 0.85%   |
| AMD Athlon              | 1         | 0.85%   |
| AMD A4                  | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 43        | 36.75%  |
| 2      | 22        | 18.8%   |
| 8      | 19        | 16.24%  |
| 6      | 19        | 16.24%  |
| 12     | 5         | 4.27%   |
| 10     | 3         | 2.56%   |
| 14     | 2         | 1.71%   |
| 3      | 2         | 1.71%   |
| 24     | 1         | 0.85%   |
| 16     | 1         | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 117       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 92        | 78.63%  |
| 1      | 25        | 21.37%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 117       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 95        | 79.83%  |
| 0x0a50000c | 5         | 4.2%    |
| 0x0a404102 | 4         | 3.36%   |
| 0x08608103 | 3         | 2.52%   |
| 0x0a404101 | 2         | 1.68%   |
| 0x0a20120a | 2         | 1.68%   |
| 0x08600104 | 2         | 1.68%   |
| 0x906a3    | 1         | 0.84%   |
| 0x90672    | 1         | 0.84%   |
| 0x08108109 | 1         | 0.84%   |
| 0x0810100b | 1         | 0.84%   |
| 0x0700010f | 1         | 0.84%   |
| 0x06000852 | 1         | 0.84%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 22        | 18.8%   |
| KabyLake         | 16        | 13.68%  |
| Zen 3            | 12        | 10.26%  |
| Haswell          | 9         | 7.69%   |
| Skylake          | 8         | 6.84%   |
| Alderlake Hybrid | 8         | 6.84%   |
| TigerLake        | 6         | 5.13%   |
| SandyBridge      | 6         | 5.13%   |
| IvyBridge        | 6         | 5.13%   |
| Zen 2            | 4         | 3.42%   |
| Zen+             | 3         | 2.56%   |
| Piledriver       | 2         | 1.71%   |
| Penryn           | 2         | 1.71%   |
| Nehalem          | 2         | 1.71%   |
| CometLake        | 2         | 1.71%   |
| Zen              | 1         | 0.85%   |
| Tremont          | 1         | 0.85%   |
| Puma             | 1         | 0.85%   |
| K10              | 1         | 0.85%   |
| Jaguar           | 1         | 0.85%   |
| IceLake          | 1         | 0.85%   |
| Goldmont plus    | 1         | 0.85%   |
| Goldmont         | 1         | 0.85%   |
| Core             | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 66        | 44.3%   |
| AMD    | 46        | 30.87%  |
| Nvidia | 37        | 24.83%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Rembrandt [Radeon 680M]                                                 | 7         | 4.67%   |
| AMD Lucienne                                                                | 7         | 4.67%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 6         | 4%      |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 3.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 3.33%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 5         | 3.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 2.67%   |
| AMD Renoir                                                                  | 4         | 2.67%   |
| AMD Barcelo                                                                 | 4         | 2.67%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 3         | 2%      |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                               | 3         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 2%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 3         | 2%      |
| Intel HD Graphics 530                                                       | 3         | 2%      |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3         | 2%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 3         | 2%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 2%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 3         | 2%      |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 2         | 1.33%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 1.33%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 2         | 1.33%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                   | 2         | 1.33%   |
| Intel HD Graphics 620                                                       | 2         | 1.33%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 2         | 1.33%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 2         | 1.33%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                        | 1         | 0.67%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                       | 1         | 0.67%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                      | 1         | 0.67%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 1         | 0.67%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1         | 0.67%   |
| Nvidia MCP7A [GeForce 9400]                                                 | 1         | 0.67%   |
| Nvidia GT218 [GeForce G210]                                                 | 1         | 0.67%   |
| Nvidia GP108GLM [Quadro P520]                                               | 1         | 0.67%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 1         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 0.67%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 1         | 0.67%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 1         | 0.67%   |
| Nvidia GM107M [GeForce GTX 950M]                                            | 1         | 0.67%   |
| Nvidia GM107M [GeForce GTX 860M]                                            | 1         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 41        | 35.04%  |
| 1 x AMD         | 35        | 29.91%  |
| Intel + Nvidia  | 20        | 17.09%  |
| 1 x Nvidia      | 9         | 7.69%   |
| AMD + Nvidia    | 7         | 5.98%   |
| Intel + AMD     | 2         | 1.71%   |
| Other           | 1         | 0.85%   |
| 2 x AMD         | 1         | 0.85%   |
| Intel + 2 x AMD | 1         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 88        | 74.58%  |
| Proprietary | 28        | 23.73%  |
| Unknown     | 2         | 1.69%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 80        | 67.8%   |
| 3.01-4.0   | 9         | 7.63%   |
| 1.01-2.0   | 9         | 7.63%   |
| 0.01-0.5   | 7         | 5.93%   |
| 7.01-8.0   | 4         | 3.39%   |
| 0.51-1.0   | 4         | 3.39%   |
| 5.01-6.0   | 2         | 1.69%   |
| 8.01-16.0  | 2         | 1.69%   |
| 2.01-3.0   | 1         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 24        | 18.18%  |
| BOE                     | 18        | 13.64%  |
| AU Optronics            | 18        | 13.64%  |
| Chimei Innolux          | 11        | 8.33%   |
| LG Display              | 6         | 4.55%   |
| Goldstar                | 6         | 4.55%   |
| Apple                   | 6         | 4.55%   |
| Philips                 | 4         | 3.03%   |
| Dell                    | 4         | 3.03%   |
| PANDA                   | 3         | 2.27%   |
| Lenovo                  | 3         | 2.27%   |
| Iiyama                  | 3         | 2.27%   |
| Sharp                   | 2         | 1.52%   |
| InfoVision              | 2         | 1.52%   |
| BenQ                    | 2         | 1.52%   |
| Ancor Communications    | 2         | 1.52%   |
| VIZ                     | 1         | 0.76%   |
| UGD                     | 1         | 0.76%   |
| Sceptre Tech            | 1         | 0.76%   |
| Panasonic               | 1         | 0.76%   |
| ONN                     | 1         | 0.76%   |
| Medion Akoya            | 1         | 0.76%   |
| LOE                     | 1         | 0.76%   |
| KDC                     | 1         | 0.76%   |
| KDB                     | 1         | 0.76%   |
| INS                     | 1         | 0.76%   |
| Hewlett-Packard         | 1         | 0.76%   |
| Denver                  | 1         | 0.76%   |
| DENON                   | 1         | 0.76%   |
| CSO                     | 1         | 0.76%   |
| Chi Mei Optoelectronics | 1         | 0.76%   |
| ASUSTek Computer        | 1         | 0.76%   |
| AOC                     | 1         | 0.76%   |
| Acer                    | 1         | 0.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch        | 3         | 2.14%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch     | 2         | 1.43%   |
| Samsung Electronics LCD Monitor SDC4159 1920x1080 344x194mm 15.5-inch | 2         | 1.43%   |
| AU Optronics LCD Monitor AUO139D 1920x1080 381x214mm 17.2-inch        | 2         | 1.43%   |
| VIZ LCD Monitor D32h-J04 1920x1080                                    | 1         | 0.71%   |
| UGD CD220F (H) UGD2210 1920x1080 527x296mm 23.8-inch                  | 1         | 0.71%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 1         | 0.71%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.71%   |
| Sceptre Tech Sceptre F27 SPT0AD7 1920x1080 600x330mm 27.0-inch        | 1         | 0.71%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch     | 1         | 0.71%   |
| Samsung Electronics U32H85x SAM0E3C 3840x2160 697x392mm 31.5-inch     | 1         | 0.71%   |
| Samsung Electronics SyncMaster SAM05E8 1920x1080                      | 1         | 0.71%   |
| Samsung Electronics SyncMaster SAM04D3 1920x1080 531x298mm 24.0-inch  | 1         | 0.71%   |
| Samsung Electronics SyncMaster SAM0498 1600x900 443x249mm 20.0-inch   | 1         | 0.71%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 509x286mm 23.0-inch    | 1         | 0.71%   |
| Samsung Electronics SMBX2250 SAM071B 1920x1080 480x270mm 21.7-inch    | 1         | 0.71%   |
| Samsung Electronics S24R35x SAM100E 1920x1080 527x296mm 23.8-inch     | 1         | 0.71%   |
| Samsung Electronics S24B150 SAM0983 1920x1080 521x293mm 23.5-inch     | 1         | 0.71%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 1         | 0.71%   |
| Samsung Electronics LF24T35 SAM707E 1920x1080 528x297mm 23.9-inch     | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4A49 2736x1824 260x173mm 12.3-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4179 2560x1440 344x194mm 15.5-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC415F 3840x2160 344x194mm 15.5-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC415D 3840x2400 344x215mm 16.0-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC4142 3840x2160 294x165mm 13.3-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 1         | 0.71%   |
| Samsung Electronics LCD Monitor SAM0679 1360x768 410x256mm 19.0-inch  | 1         | 0.71%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch     | 1         | 0.71%   |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch     | 1         | 0.71%   |
| Philips PHL 241B8Q PHL0929 1920x1080 527x296mm 23.8-inch              | 1         | 0.71%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 1         | 0.71%   |
| Philips 27M1N3200V PHLC279 1920x1080 598x336mm 27.0-inch              | 1         | 0.71%   |
| Philips 191V PHL0887 1366x768 409x230mm 18.5-inch                     | 1         | 0.71%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch               | 1         | 0.71%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 1         | 0.71%   |
| PANDA LCD Monitor NCP003F 1920x1080 344x194mm 15.5-inch               | 1         | 0.71%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 66        | 51.16%  |
| 1366x768 (WXGA)    | 15        | 11.63%  |
| 3840x2160 (4K)     | 11        | 8.53%   |
| 2560x1440 (QHD)    | 7         | 5.43%   |
| 1920x1200 (WUXGA)  | 4         | 3.1%    |
| 1600x900 (HD+)     | 4         | 3.1%    |
| 3440x1440          | 2         | 1.55%   |
| 2880x1800          | 2         | 1.55%   |
| 2560x1600          | 2         | 1.55%   |
| 2560x1080          | 2         | 1.55%   |
| 1440x900 (WXGA+)   | 2         | 1.55%   |
| 1280x800 (WXGA)    | 2         | 1.55%   |
| 3840x2400          | 1         | 0.78%   |
| 3840x1100          | 1         | 0.78%   |
| 3072x1920          | 1         | 0.78%   |
| 2736x1824          | 1         | 0.78%   |
| 2256x1504          | 1         | 0.78%   |
| 2160x1440          | 1         | 0.78%   |
| 1920x540           | 1         | 0.78%   |
| 1680x1050 (WSXGA+) | 1         | 0.78%   |
| 1360x768           | 1         | 0.78%   |
| 1280x720 (HD)      | 1         | 0.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 36        | 26.67%  |
| 13      | 14        | 10.37%  |
| 24      | 11        | 8.15%   |
| 14      | 11        | 8.15%   |
| 17      | 10        | 7.41%   |
| 27      | 9         | 6.67%   |
| 23      | 8         | 5.93%   |
| 31      | 7         | 5.19%   |
| 21      | 5         | 3.7%    |
| 16      | 5         | 3.7%    |
| 34      | 3         | 2.22%   |
| 19      | 3         | 2.22%   |
| 11      | 3         | 2.22%   |
| 18      | 2         | 1.48%   |
| Unknown | 2         | 1.48%   |
| 72      | 1         | 0.74%   |
| 69      | 1         | 0.74%   |
| 40      | 1         | 0.74%   |
| 22      | 1         | 0.74%   |
| 20      | 1         | 0.74%   |
| 12      | 1         | 0.74%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 57        | 42.54%  |
| 501-600     | 27        | 20.15%  |
| 401-500     | 12        | 8.96%   |
| 351-400     | 11        | 8.21%   |
| 201-300     | 11        | 8.21%   |
| 601-700     | 8         | 5.97%   |
| 701-800     | 3         | 2.24%   |
| 1501-2000   | 2         | 1.49%   |
| Unknown     | 2         | 1.49%   |
| 801-900     | 1         | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 96        | 80%     |
| 16/10   | 16        | 13.33%  |
| 3/2     | 3         | 2.5%    |
| 21/9    | 3         | 2.5%    |
| 3.40    | 1         | 0.83%   |
| Unknown | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 36        | 26.87%  |
| 201-250        | 21        | 15.67%  |
| 81-90          | 18        | 13.43%  |
| 351-500        | 10        | 7.46%   |
| 121-130        | 10        | 7.46%   |
| 301-350        | 9         | 6.72%   |
| 111-120        | 5         | 3.73%   |
| 71-80          | 4         | 2.99%   |
| 51-60          | 4         | 2.99%   |
| 151-200        | 4         | 2.99%   |
| 251-300        | 3         | 2.24%   |
| More than 1000 | 2         | 1.49%   |
| 141-150        | 2         | 1.49%   |
| 91-100         | 2         | 1.49%   |
| Unknown        | 2         | 1.49%   |
| 61-70          | 1         | 0.75%   |
| 501-1000       | 1         | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 50        | 38.76%  |
| 51-100        | 36        | 27.91%  |
| 101-120       | 20        | 15.5%   |
| 161-240       | 13        | 10.08%  |
| More than 240 | 7         | 5.43%   |
| Unknown       | 2         | 1.55%   |
| 1-50          | 1         | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 91        | 77.78%  |
| 2     | 22        | 18.8%   |
| 0     | 2         | 1.71%   |
| 4     | 1         | 0.85%   |
| 3     | 1         | 0.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 71        | 40.8%   |
| Intel                 | 50        | 28.74%  |
| MediaTek              | 14        | 8.05%   |
| Qualcomm Atheros      | 10        | 5.75%   |
| Broadcom              | 10        | 5.75%   |
| ASUSTek Computer      | 3         | 1.72%   |
| TP-Link               | 2         | 1.15%   |
| Ralink                | 2         | 1.15%   |
| Hewlett-Packard       | 2         | 1.15%   |
| ASIX Electronics      | 2         | 1.15%   |
| U-Blox                | 1         | 0.57%   |
| Texas Instruments     | 1         | 0.57%   |
| Samsung Electronics   | 1         | 0.57%   |
| Nvidia                | 1         | 0.57%   |
| Lenovo                | 1         | 0.57%   |
| Google                | 1         | 0.57%   |
| Broadcom Limited      | 1         | 0.57%   |
| Aquantia              | 1         | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 22.06%  |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 8         | 3.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 3.43%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 3.43%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 6         | 2.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 2.45%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 4         | 1.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.96%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 1.47%   |
| Intel Wireless 8265 / 8275                                        | 3         | 1.47%   |
| Intel Wireless 8260                                               | 3         | 1.47%   |
| Intel Wireless 7265                                               | 3         | 1.47%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 1.47%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 1.47%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 2         | 0.98%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 0.98%   |
| Intel Wireless 7260                                               | 2         | 0.98%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.98%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.98%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.98%   |
| U-Blox [u-blox 8]                                                 | 1         | 0.49%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.49%   |
| TP-Link 802.11n NIC                                               | 1         | 0.49%   |
| Texas Instruments TI CC2540 USB CDC                               | 1         | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.49%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.49%   |
| Ralink RT5392 PCIe Wireless Network Adapter                       | 1         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 46        | 44.23%  |
| Realtek Semiconductor | 19        | 18.27%  |
| MediaTek              | 14        | 13.46%  |
| Qualcomm Atheros      | 9         | 8.65%   |
| Broadcom              | 7         | 6.73%   |
| ASUSTek Computer      | 3         | 2.88%   |
| TP-Link               | 2         | 1.92%   |
| Ralink                | 2         | 1.92%   |
| Hewlett-Packard       | 1         | 0.96%   |
| Broadcom Limited      | 1         | 0.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 8         | 7.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                              | 7         | 6.73%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 6         | 5.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 5         | 4.81%   |
| Intel Wi-Fi 6 AX200                                                           | 5         | 4.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 4         | 3.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                 | 4         | 3.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                        | 4         | 3.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 3         | 2.88%   |
| Intel Wireless 8265 / 8275                                                    | 3         | 2.88%   |
| Intel Wireless 8260                                                           | 3         | 2.88%   |
| Intel Wireless 7265                                                           | 3         | 2.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 3         | 2.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 3         | 2.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                                | 3         | 2.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 2         | 1.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 2         | 1.92%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                       | 2         | 1.92%   |
| Intel Wireless 7260                                                           | 2         | 1.92%   |
| Intel Wi-Fi 6 AX201                                                           | 2         | 1.92%   |
| Intel Tiger Lake PCH CNVi WiFi                                                | 2         | 1.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 1.92%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                           | 1         | 0.96%   |
| TP-Link 802.11n NIC                                                           | 1         | 0.96%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 1         | 0.96%   |
| Ralink RT5392 PCIe Wireless Network Adapter                                   | 1         | 0.96%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                        | 1         | 0.96%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                              | 1         | 0.96%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 1         | 0.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1         | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 1         | 0.96%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 1         | 0.96%   |
| Intel Wireless 3165                                                           | 1         | 0.96%   |
| Intel Gemini Lake PCH CNVi WiFi                                               | 1         | 0.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 1         | 0.96%   |
| Intel Centrino Wireless-N 2230                                                | 1         | 0.96%   |
| Intel Alder Lake-U CNVi: Wireless-AC                                          | 1         | 0.96%   |
| Intel Alder Lake-S PCH CNVi WiFi                                              | 1         | 0.96%   |
| Intel 700 Series Chipset Family Wi-Fi                                         | 1         | 0.96%   |
| HP lt4112 Gobi 4G Module Network Device                                       | 1         | 0.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 62        | 65.26%  |
| Intel                 | 16        | 16.84%  |
| Broadcom              | 7         | 7.37%   |
| Qualcomm Atheros      | 3         | 3.16%   |
| ASIX Electronics      | 2         | 2.11%   |
| Samsung Electronics   | 1         | 1.05%   |
| Nvidia                | 1         | 1.05%   |
| Lenovo                | 1         | 1.05%   |
| Google                | 1         | 1.05%   |
| Aquantia              | 1         | 1.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 46.39%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 7.22%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 5.15%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 4.12%   |
| Intel Ethernet Controller I225-V                                  | 3         | 3.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.09%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 3.09%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 2.06%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 2.06%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 2.06%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.03%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.03%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.03%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 1.03%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.03%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 1.03%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.03%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.03%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 1.03%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.03%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 1.03%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.03%   |
| Intel Ethernet Connection (10) I219-LM                            | 1         | 1.03%   |
| Google Pixel 7 Pro                                                | 1         | 1.03%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 1.03%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 1.03%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 1.03%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.03%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.03%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 102       | 52.85%  |
| Ethernet | 88        | 45.6%   |
| Modem    | 3         | 1.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 83        | 69.17%  |
| Ethernet | 37        | 30.83%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 62        | 52.99%  |
| 1     | 54        | 46.15%  |
| 5     | 1         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 79        | 67.52%  |
| Yes  | 38        | 32.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 47.78%  |
| Realtek Semiconductor           | 17        | 18.89%  |
| Apple                           | 7         | 7.78%   |
| IMC Networks                    | 5         | 5.56%   |
| Foxconn / Hon Hai               | 5         | 5.56%   |
| Lite-On Technology              | 3         | 3.33%   |
| MediaTek                        | 2         | 2.22%   |
| TP-Link                         | 1         | 1.11%   |
| Toshiba                         | 1         | 1.11%   |
| Realtek                         | 1         | 1.11%   |
| Qualcomm Atheros Communications | 1         | 1.11%   |
| Dell                            | 1         | 1.11%   |
| Cambridge Silicon Radio         | 1         | 1.11%   |
| Broadcom                        | 1         | 1.11%   |
| ASUSTek Computer                | 1         | 1.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 16        | 17.78%  |
| Intel Bluetooth wireless interface                  | 13        | 14.44%  |
| Intel Bluetooth Device                              | 9         | 10%     |
| Intel AX201 Bluetooth                               | 7         | 7.78%   |
| Intel AX200 Bluetooth                               | 5         | 5.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 4.44%   |
| Intel AX210 Bluetooth                               | 4         | 4.44%   |
| IMC Networks Wireless_Device                        | 4         | 4.44%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 3.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 3.33%   |
| Apple Bluetooth USB Host Controller                 | 3         | 3.33%   |
| MediaTek Wireless_Device                            | 2         | 2.22%   |
| Lite-On Wireless_Device                             | 2         | 2.22%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 2.22%   |
| TP-Link UB500 Adapter                               | 1         | 1.11%   |
| Toshiba RT Bluetooth Radio                          | 1         | 1.11%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.11%   |
| Realtek Bluetooth Radio                             | 1         | 1.11%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 1.11%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 1.11%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.11%   |
| IMC Networks BCM20702A0                             | 1         | 1.11%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.11%   |
| Broadcom BCM20702A0                                 | 1         | 1.11%   |
| ASUS ASUS USB-BT500                                 | 1         | 1.11%   |
| Apple Bluetooth Host Controller                     | 1         | 1.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 77        | 46.11%  |
| AMD                      | 49        | 29.34%  |
| Nvidia                   | 25        | 14.97%  |
| C-Media Electronics      | 3         | 1.8%    |
| Hewlett-Packard          | 2         | 1.2%    |
| Trust                    | 1         | 0.6%    |
| Texas Instruments        | 1         | 0.6%    |
| Realtek Semiconductor    | 1         | 0.6%    |
| Nordic Semiconductor ASA | 1         | 0.6%    |
| Mackie Designs           | 1         | 0.6%    |
| M-Audio                  | 1         | 0.6%    |
| Lenovo                   | 1         | 0.6%    |
| Dell                     | 1         | 0.6%    |
| Corsair                  | 1         | 0.6%    |
| AudioQuest               | 1         | 0.6%    |
| 2.4G Composite Device    | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 31        | 15.05%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 18        | 8.74%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 8         | 3.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 3.88%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 3.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 2.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 2.91%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 6         | 2.91%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 2.43%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 2.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 2.43%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 2.43%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2.43%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1.94%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 1.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.46%   |
| Nvidia Audio device                                                        | 3         | 1.46%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1.46%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.46%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 1.46%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 1.46%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.97%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.97%   |
| Intel Alder Lake-S HD Audio Controller                                     | 2         | 0.97%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 2         | 0.97%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 2         | 0.97%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2         | 0.97%   |
| AMD FCH Azalia Controller                                                  | 2         | 0.97%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 0.97%   |
| Trust Microphone                                                           | 1         | 0.49%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                          | 1         | 0.49%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.49%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.49%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.49%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.49%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.49%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 26.09%  |
| Micron Technology   | 14        | 20.29%  |
| SK hynix            | 12        | 17.39%  |
| Crucial             | 6         | 8.7%    |
| Kingston            | 5         | 7.25%   |
| Ramaxel Technology  | 3         | 4.35%   |
| G.Skill             | 2         | 2.9%    |
| Corsair             | 2         | 2.9%    |
| Unknown (ABCD)      | 1         | 1.45%   |
| Unknown             | 1         | 1.45%   |
| Transcend           | 1         | 1.45%   |
| Team                | 1         | 1.45%   |
| Patriot             | 1         | 1.45%   |
| Micron/Elpida       | 1         | 1.45%   |
| 4ea5                | 1         | 1.45%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 4.17%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 4.17%   |
| Unknown RAM Module 8GB DIMM 667MT/s                              | 1         | 1.39%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 1.39%   |
| Transcend RAM JM2666HSE-16G 16GB SODIMM DDR4 2667MT/s            | 1         | 1.39%   |
| Team RAM TEAMGROUP-UD3-1600 4GB DIMM DDR3 1600MT/s               | 1         | 1.39%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 1.39%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.39%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                     | 1         | 1.39%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.39%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.39%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.39%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.39%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 1         | 1.39%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.39%   |
| SK hynix RAM H58G66AK6BX070 4GB Row Of Chips LPDDR5 6400MT/s     | 1         | 1.39%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.39%   |
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.39%   |
| Samsung RAM Module 8GB SODIMM DDR5 4800MT/s                      | 1         | 1.39%   |
| Samsung RAM Module 4GB Row Of Chips LPDDR3 2133MT/s              | 1         | 1.39%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.39%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 1         | 1.39%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.39%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 1.39%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.39%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM 4800MT/s              | 1         | 1.39%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.39%   |
| Samsung RAM K4F6E3S4HM-MGCJ 2GB LPDDR4 2400MT/s                  | 1         | 1.39%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s             | 1         | 1.39%   |
| Samsung RAM 53D512M64D4RQ-046 8GB Row Of Chips LPDDR4 3733MT/s   | 1         | 1.39%   |
| Ramaxel RAM RMSA3320ME88HBF-3200 16GB SODIMM DDR4 3200MT/s       | 1         | 1.39%   |
| Ramaxel RAM RMSA3310MF96HAF-3200 8GB SODIMM DDR4 3200MT/s        | 1         | 1.39%   |
| Ramaxel RAM RMSA3260MB78HAF2400 8GB SODIMM DDR4 2400MT/s         | 1         | 1.39%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3266MT/s               | 1         | 1.39%   |
| Micron/Elpida RAM Module 4GB Row Of Chips LPDDR3 1867MT/s        | 1         | 1.39%   |
| Micron RAM MT62F2G32D8DR-031 WT 8GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.39%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB SODIMM LPDDR5 6400MT/s       | 1         | 1.39%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.39%   |
| Micron RAM MT53E512M32D2NP-046 4GB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 27        | 46.55%  |
| DDR3    | 11        | 18.97%  |
| LPDDR5  | 7         | 12.07%  |
| LPDDR4  | 6         | 10.34%  |
| DDR5    | 4         | 6.9%    |
| LPDDR3  | 2         | 3.45%   |
| Unknown | 1         | 1.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 33        | 55%     |
| Row Of Chips | 15        | 25%     |
| DIMM         | 11        | 18.33%  |
| Unknown      | 1         | 1.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 30        | 47.62%  |
| 4096  | 16        | 25.4%   |
| 16384 | 10        | 15.87%  |
| 32768 | 4         | 6.35%   |
| 2048  | 3         | 4.76%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 15        | 25%     |
| 6400  | 7         | 11.67%  |
| 1600  | 6         | 10%     |
| 2400  | 5         | 8.33%   |
| 4800  | 4         | 6.67%   |
| 2667  | 4         | 6.67%   |
| 4267  | 3         | 5%      |
| 3733  | 2         | 3.33%   |
| 2933  | 2         | 3.33%   |
| 2133  | 2         | 3.33%   |
| 1800  | 2         | 3.33%   |
| 3600  | 1         | 1.67%   |
| 3266  | 1         | 1.67%   |
| 2473  | 1         | 1.67%   |
| 1867  | 1         | 1.67%   |
| 1334  | 1         | 1.67%   |
| 1333  | 1         | 1.67%   |
| 1067  | 1         | 1.67%   |
| 667   | 1         | 1.67%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Brother Industries | 2         | 66.67%  |
| Canon              | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Canon PIXMA MX490 Series | 1         | 33.33%  |
| Brother HL-L2310D series | 1         | 33.33%  |
| Brother HL-3142CW series | 1         | 33.33%  |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 13        | 17.33%  |
| Quanta                                 | 8         | 10.67%  |
| IMC Networks                           | 7         | 9.33%   |
| Apple                                  | 7         | 9.33%   |
| Microdia                               | 5         | 6.67%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 6.67%   |
| Bison Electronics                      | 5         | 6.67%   |
| Realtek Semiconductor                  | 4         | 5.33%   |
| Luxvisions Innotech Limited            | 4         | 5.33%   |
| Acer                                   | 4         | 5.33%   |
| Syntek                                 | 3         | 4%      |
| Sunplus Innovation Technology          | 3         | 4%      |
| SunplusIT                              | 1         | 1.33%   |
| SN0002                                 | 1         | 1.33%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 1.33%   |
| Samsung Electronics                    | 1         | 1.33%   |
| OYT Tech                               | 1         | 1.33%   |
| Logitech                               | 1         | 1.33%   |
| GEMBIRD                                | 1         | 1.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 6.49%   |
| Chicony Integrated Camera                           | 4         | 5.19%   |
| Apple FaceTime HD Camera                            | 3         | 3.9%    |
| Acer Integrated Camera                              | 3         | 3.9%    |
| Syntek Integrated Camera                            | 2         | 2.6%    |
| Sunplus Integrated_Webcam_HD                        | 2         | 2.6%    |
| Realtek HP Truevision HD                            | 2         | 2.6%    |
| Quanta USB2.0 HD UVC WebCam                         | 2         | 2.6%    |
| Luxvisions Innotech Limited Integrated RGB Camera   | 2         | 2.6%    |
| Chicony HD WebCam                                   | 2         | 2.6%    |
| Chicony 720p HD Camera                              | 2         | 2.6%    |
| Bison Integrated RGB Camera                         | 2         | 2.6%    |
| Apple FaceTime HD Camera (Built-in)                 | 2         | 2.6%    |
| Apple Built-in iSight                               | 2         | 2.6%    |
| Syntek Lenovo EasyCamera                            | 1         | 1.3%    |
| SunplusIT 1080p FHD Camera                          | 1         | 1.3%    |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 1.3%    |
| SN0002 1080P Web Camera                             | 1         | 1.3%    |
| Shenzhen Kingcome Optoelectronic 720p HD Camera     | 1         | 1.3%    |
| Samsung Galaxy A5 (MTP)                             | 1         | 1.3%    |
| Realtek Laptop Camera                               | 1         | 1.3%    |
| Realtek Integrated Webcam                           | 1         | 1.3%    |
| Quanta ov9734_techfront_camera                      | 1         | 1.3%    |
| Quanta HP Wide Vision HD Camera                     | 1         | 1.3%    |
| Quanta HP HD Camera                                 | 1         | 1.3%    |
| Quanta HP 5MP Camera                                | 1         | 1.3%    |
| Quanta HD User Facing                               | 1         | 1.3%    |
| Quanta HD Camera                                    | 1         | 1.3%    |
| OYT Tech OYV1RDFF1                                  | 1         | 1.3%    |
| Microdia Webcam Vitade AF                           | 1         | 1.3%    |
| Microdia Integrated_Webcam_HD                       | 1         | 1.3%    |
| Microdia Integrated_Webcam_FHD                      | 1         | 1.3%    |
| Microdia Dell Laptop Integrated Webcam HD           | 1         | 1.3%    |
| Microdia Camera                                     | 1         | 1.3%    |
| Luxvisions Innotech Limited Integrated Camera       | 1         | 1.3%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.3%    |
| Logitech Webcam C925e                               | 1         | 1.3%    |
| IMC Networks USB2.0 UVC HD Webcam                   | 1         | 1.3%    |
| IMC Networks Integrated Camera                      | 1         | 1.3%    |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311]   | 1         | 1.3%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 5         | 31.25%  |
| Shenzhen Goodix Technology         | 5         | 31.25%  |
| Validity Sensors                   | 4         | 25%     |
| Realtek USB2.0 Finger Print Bridge | 1         | 6.25%   |
| Elan Microelectronics              | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                             | 3         | 18.75%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 12.5%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 2         | 12.5%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 6.25%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 6.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 1         | 6.25%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 6.25%   |
| Synaptics UWP WBDI                                              | 1         | 6.25%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 6.25%   |
| Elan ELAN:ARM-M4                                                | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 40%     |
| Alcor Micro | 2         | 40%     |
| O2 Micro    | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader            | 2         | 40%     |
| O2 Micro OZ776 CCID Smartcard Reader           | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor | 1         | 20%     |
| Broadcom 5880                                  | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 80        | 68.38%  |
| 1     | 30        | 25.64%  |
| 2     | 7         | 5.98%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 16        | 37.21%  |
| Multimedia controller    | 5         | 11.63%  |
| Chipcard                 | 5         | 11.63%  |
| Camera                   | 5         | 11.63%  |
| Net/wireless             | 4         | 9.3%    |
| Graphics card            | 4         | 9.3%    |
| Unassigned class         | 1         | 2.33%   |
| Storage                  | 1         | 2.33%   |
| Communication controller | 1         | 2.33%   |
| Card reader              | 1         | 2.33%   |

