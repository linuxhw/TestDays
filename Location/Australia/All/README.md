Linux in Australia - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for Linux in Australia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Australia/Desktop/README.md) and [notebooks](/Location/Australia/Notebook/README.md).

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

Total: 4302

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | 1005HA                      | Notebook    | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Cube          | i18-BL                      | Notebook    | [725100a829](https://linux-hardware.org/?probe=725100a829) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| HP            | Notebook                    | Notebook    | [27d097b522](https://linux-hardware.org/?probe=27d097b522) | Nov 01, 2022 |
| Acer          | Aspire 3000                 | Notebook    | [02693e03ca](https://linux-hardware.org/?probe=02693e03ca) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| ASUSTek       | X501A                       | Notebook    | [d5a34df414](https://linux-hardware.org/?probe=d5a34df414) | Nov 01, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [722ae37952](https://linux-hardware.org/?probe=722ae37952) | Nov 01, 2022 |
| ASUSTek       | B150M-V PLUS                | Desktop     | [a451844625](https://linux-hardware.org/?probe=a451844625) | Nov 01, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [a2a8473e4b](https://linux-hardware.org/?probe=a2a8473e4b) | Oct 31, 2022 |
| ASRock        | X670E Pro RS                | Desktop     | [5ebdf73c67](https://linux-hardware.org/?probe=5ebdf73c67) | Oct 31, 2022 |
| HP            | 8653 A                      | Desktop     | [9c19089f51](https://linux-hardware.org/?probe=9c19089f51) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [1c5d979ba1](https://linux-hardware.org/?probe=1c5d979ba1) | Oct 29, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [883100c74f](https://linux-hardware.org/?probe=883100c74f) | Oct 29, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [1d3ff229c6](https://linux-hardware.org/?probe=1d3ff229c6) | Oct 29, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [c3ea4065c4](https://linux-hardware.org/?probe=c3ea4065c4) | Oct 29, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [629858e96c](https://linux-hardware.org/?probe=629858e96c) | Oct 29, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [af4751bfcf](https://linux-hardware.org/?probe=af4751bfcf) | Oct 28, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [2e4153161f](https://linux-hardware.org/?probe=2e4153161f) | Oct 28, 2022 |
| ASUSTek       | U50Vg                       | Notebook    | [5f2997ec95](https://linux-hardware.org/?probe=5f2997ec95) | Oct 28, 2022 |
| HP            | 829B                        | All in one  | [1f8f75d1c0](https://linux-hardware.org/?probe=1f8f75d1c0) | Oct 27, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [b096155d39](https://linux-hardware.org/?probe=b096155d39) | Oct 27, 2022 |
| HP            | 8653 A                      | Desktop     | [92b68870ca](https://linux-hardware.org/?probe=92b68870ca) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [cca0d420fe](https://linux-hardware.org/?probe=cca0d420fe) | Oct 27, 2022 |
| HP            | G71                         | Notebook    | [3223e2fcc8](https://linux-hardware.org/?probe=3223e2fcc8) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [df069d17c5](https://linux-hardware.org/?probe=df069d17c5) | Oct 26, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [54f6493d11](https://linux-hardware.org/?probe=54f6493d11) | Oct 26, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [3848afd2c8](https://linux-hardware.org/?probe=3848afd2c8) | Oct 26, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [6896f337ab](https://linux-hardware.org/?probe=6896f337ab) | Oct 25, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [be4c6573cd](https://linux-hardware.org/?probe=be4c6573cd) | Oct 25, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [82fb357322](https://linux-hardware.org/?probe=82fb357322) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4ffd604fea](https://linux-hardware.org/?probe=4ffd604fea) | Oct 25, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [23be2713d2](https://linux-hardware.org/?probe=23be2713d2) | Oct 24, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [6331b122dc](https://linux-hardware.org/?probe=6331b122dc) | Oct 24, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [6f72d6443c](https://linux-hardware.org/?probe=6f72d6443c) | Oct 23, 2022 |
| HP            | 0B40h                       | Desktop     | [981b4e9553](https://linux-hardware.org/?probe=981b4e9553) | Oct 23, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [edd13bcc76](https://linux-hardware.org/?probe=edd13bcc76) | Oct 23, 2022 |
| Notebook      | W650EH                      | Notebook    | [6bb1a8b1f1](https://linux-hardware.org/?probe=6bb1a8b1f1) | Oct 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | Desktop     | [32cd9cd246](https://linux-hardware.org/?probe=32cd9cd246) | Oct 22, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3e2bd05f56](https://linux-hardware.org/?probe=3e2bd05f56) | Oct 22, 2022 |
| Purism        | Librem 13 v2                | Notebook    | [5296ed1e19](https://linux-hardware.org/?probe=5296ed1e19) | Oct 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [cb901021a7](https://linux-hardware.org/?probe=cb901021a7) | Oct 21, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [63751816bc](https://linux-hardware.org/?probe=63751816bc) | Oct 21, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [1ab730c85c](https://linux-hardware.org/?probe=1ab730c85c) | Oct 21, 2022 |
| Gigabyte      | X570S AORUS ELITE           | Desktop     | [bc75d3cc30](https://linux-hardware.org/?probe=bc75d3cc30) | Oct 21, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [60d4787bb7](https://linux-hardware.org/?probe=60d4787bb7) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire 5600                 | Notebook    | [202a7e570e](https://linux-hardware.org/?probe=202a7e570e) | Oct 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [502ae94f8f](https://linux-hardware.org/?probe=502ae94f8f) | Oct 20, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [2cd92a7da8](https://linux-hardware.org/?probe=2cd92a7da8) | Oct 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [5086e64fed](https://linux-hardware.org/?probe=5086e64fed) | Oct 19, 2022 |
| Intel         | NUC11PABi5 K90634-302       | Mini pc     | [4c9eafcd7f](https://linux-hardware.org/?probe=4c9eafcd7f) | Oct 19, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [026a7a8cd3](https://linux-hardware.org/?probe=026a7a8cd3) | Oct 18, 2022 |
| HP            | 2B21 A01                    | All in one  | [8a8935ed07](https://linux-hardware.org/?probe=8a8935ed07) | Oct 18, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [926d661756](https://linux-hardware.org/?probe=926d661756) | Oct 17, 2022 |
| HP            | G71                         | Notebook    | [46b6033e1e](https://linux-hardware.org/?probe=46b6033e1e) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [f30aab43b6](https://linux-hardware.org/?probe=f30aab43b6) | Oct 16, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [d9928a4ee9](https://linux-hardware.org/?probe=d9928a4ee9) | Oct 16, 2022 |
| System76      | Galago Pro                  | Notebook    | [ec92c5a918](https://linux-hardware.org/?probe=ec92c5a918) | Oct 14, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [79eba98b95](https://linux-hardware.org/?probe=79eba98b95) | Oct 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [5f0c4b3acb](https://linux-hardware.org/?probe=5f0c4b3acb) | Oct 13, 2022 |
| Acer          | Aspire XC100A               | Desktop     | [6fade2c77f](https://linux-hardware.org/?probe=6fade2c77f) | Oct 13, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [705e4f406a](https://linux-hardware.org/?probe=705e4f406a) | Oct 13, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [cd65876f22](https://linux-hardware.org/?probe=cd65876f22) | Oct 12, 2022 |
| HP            | 1497                        | Desktop     | [ff6d690da4](https://linux-hardware.org/?probe=ff6d690da4) | Oct 12, 2022 |
| Gigabyte      | X570S GAMING X              | Desktop     | [e966aea162](https://linux-hardware.org/?probe=e966aea162) | Oct 12, 2022 |
| Lenovo        | 3129 SDK0J40700 WIN 3258... | Desktop     | [1798dba7f1](https://linux-hardware.org/?probe=1798dba7f1) | Oct 12, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [4bc40092b2](https://linux-hardware.org/?probe=4bc40092b2) | Oct 11, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [56fc798c2e](https://linux-hardware.org/?probe=56fc798c2e) | Oct 11, 2022 |
| Dell          | 07WJF3 A00                  | Desktop     | [62f8858433](https://linux-hardware.org/?probe=62f8858433) | Oct 11, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [dde4a94108](https://linux-hardware.org/?probe=dde4a94108) | Oct 11, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [07870a3cde](https://linux-hardware.org/?probe=07870a3cde) | Oct 11, 2022 |
| Gigabyte      | H410M DS2V                  | Desktop     | [bd9d9e10c7](https://linux-hardware.org/?probe=bd9d9e10c7) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [1ae81569dd](https://linux-hardware.org/?probe=1ae81569dd) | Oct 11, 2022 |
| Dell          | Inspiron 16 5620            | Notebook    | [72151cd0e8](https://linux-hardware.org/?probe=72151cd0e8) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | Notebook    | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | Notebook    | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [a7b96649da](https://linux-hardware.org/?probe=a7b96649da) | Oct 09, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [e26fca4929](https://linux-hardware.org/?probe=e26fca4929) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | Notebook    | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | Notebook    | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [6b62586012](https://linux-hardware.org/?probe=6b62586012) | Oct 09, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [027504f861](https://linux-hardware.org/?probe=027504f861) | Oct 08, 2022 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [2ad7a0c296](https://linux-hardware.org/?probe=2ad7a0c296) | Oct 08, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [e26911cff6](https://linux-hardware.org/?probe=e26911cff6) | Oct 08, 2022 |
| Shuttle       | FS81                        | Desktop     | [ba7c22e135](https://linux-hardware.org/?probe=ba7c22e135) | Oct 07, 2022 |
| Shuttle       | FS81                        | Desktop     | [63ec5c8971](https://linux-hardware.org/?probe=63ec5c8971) | Oct 07, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [e05dbad108](https://linux-hardware.org/?probe=e05dbad108) | Oct 07, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [9dc72dc357](https://linux-hardware.org/?probe=9dc72dc357) | Oct 07, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [3ea8d4d25e](https://linux-hardware.org/?probe=3ea8d4d25e) | Oct 06, 2022 |
| HP            | Presario V4000 (EQ608PA#... | Notebook    | [f462d80b2a](https://linux-hardware.org/?probe=f462d80b2a) | Oct 06, 2022 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [9ad9a1c969](https://linux-hardware.org/?probe=9ad9a1c969) | Oct 06, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [2e57f97484](https://linux-hardware.org/?probe=2e57f97484) | Oct 06, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [9232451f1a](https://linux-hardware.org/?probe=9232451f1a) | Oct 06, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b5cf733c51](https://linux-hardware.org/?probe=b5cf733c51) | Oct 06, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [4f3856c8f0](https://linux-hardware.org/?probe=4f3856c8f0) | Oct 06, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [5ff1f9c5c3](https://linux-hardware.org/?probe=5ff1f9c5c3) | Oct 05, 2022 |
| Lenovo        | ThinkStation S30 0569BE3    | Desktop     | [026d1ee25e](https://linux-hardware.org/?probe=026d1ee25e) | Oct 05, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [99f16967b2](https://linux-hardware.org/?probe=99f16967b2) | Oct 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [ca81117136](https://linux-hardware.org/?probe=ca81117136) | Oct 05, 2022 |
| Gigabyte      | AORUS 7 SB                  | Notebook    | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| Dell          | 0WF810                      | Desktop     | [dd24119965](https://linux-hardware.org/?probe=dd24119965) | Oct 04, 2022 |
| Acer          | TravelMate 8572T            | Notebook    | [6abaaf4aa6](https://linux-hardware.org/?probe=6abaaf4aa6) | Oct 03, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [47d31ff25c](https://linux-hardware.org/?probe=47d31ff25c) | Oct 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a7e31149f2](https://linux-hardware.org/?probe=a7e31149f2) | Oct 02, 2022 |
| Dell          | 0XCR8D A00                  | Desktop     | [82e52ab722](https://linux-hardware.org/?probe=82e52ab722) | Oct 02, 2022 |
| Dell          | 0XCR8D A00                  | Desktop     | [a6db1f5075](https://linux-hardware.org/?probe=a6db1f5075) | Oct 02, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [521636075a](https://linux-hardware.org/?probe=521636075a) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [9c6340e585](https://linux-hardware.org/?probe=9c6340e585) | Oct 01, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FE00... | Convertible | [4eaeb1d5ad](https://linux-hardware.org/?probe=4eaeb1d5ad) | Oct 01, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [4275ef3653](https://linux-hardware.org/?probe=4275ef3653) | Oct 01, 2022 |
| MSI           | PRO X670-P WIFI             | Desktop     | [64299c7b4a](https://linux-hardware.org/?probe=64299c7b4a) | Oct 01, 2022 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [1aa913c010](https://linux-hardware.org/?probe=1aa913c010) | Oct 01, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [4662cb1d99](https://linux-hardware.org/?probe=4662cb1d99) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [3f01bbaa12](https://linux-hardware.org/?probe=3f01bbaa12) | Sep 30, 2022 |
| Acer          | TravelMate 8572T            | Notebook    | [927bf01e34](https://linux-hardware.org/?probe=927bf01e34) | Sep 30, 2022 |
| Gigabyte      | AORUS 17 YE5                | Notebook    | [54b271c3fd](https://linux-hardware.org/?probe=54b271c3fd) | Sep 30, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [cc7ad91815](https://linux-hardware.org/?probe=cc7ad91815) | Sep 29, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [354a9c2bc2](https://linux-hardware.org/?probe=354a9c2bc2) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | Notebook    | [ac3079df8c](https://linux-hardware.org/?probe=ac3079df8c) | Sep 29, 2022 |
| Dell          | Inspiron 7347               | Notebook    | [144cad649c](https://linux-hardware.org/?probe=144cad649c) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [fbc4f29134](https://linux-hardware.org/?probe=fbc4f29134) | Sep 28, 2022 |
| HP            | EliteBook 8770w             | Notebook    | [e5ec559da4](https://linux-hardware.org/?probe=e5ec559da4) | Sep 28, 2022 |
| Dell          | Latitude E7450              | Notebook    | [daeb4afb69](https://linux-hardware.org/?probe=daeb4afb69) | Sep 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [76aac25208](https://linux-hardware.org/?probe=76aac25208) | Sep 28, 2022 |
| Acer          | Spin SP314-53               | Convertible | [ce95ade177](https://linux-hardware.org/?probe=ce95ade177) | Sep 27, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [565d46fb85](https://linux-hardware.org/?probe=565d46fb85) | Sep 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [2c69225287](https://linux-hardware.org/?probe=2c69225287) | Sep 27, 2022 |
| Gigabyte      | P34V7                       | Notebook    | [27b9651432](https://linux-hardware.org/?probe=27b9651432) | Sep 27, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [1b2f7b8972](https://linux-hardware.org/?probe=1b2f7b8972) | Sep 27, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | Notebook    | [2154b531c9](https://linux-hardware.org/?probe=2154b531c9) | Sep 26, 2022 |
| System76      | Galago Pro                  | Notebook    | [6b2de473b7](https://linux-hardware.org/?probe=6b2de473b7) | Sep 26, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [dce9d30a10](https://linux-hardware.org/?probe=dce9d30a10) | Sep 26, 2022 |
| Gigabyte      | AORUS 7 SB                  | Notebook    | [3e8222ad7c](https://linux-hardware.org/?probe=3e8222ad7c) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming FX505DV          | Notebook    | [6b3be4af70](https://linux-hardware.org/?probe=6b3be4af70) | Sep 26, 2022 |
| Dell          | G15 5511                    | Notebook    | [f960f38940](https://linux-hardware.org/?probe=f960f38940) | Sep 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f61a736922](https://linux-hardware.org/?probe=f61a736922) | Sep 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [1ecfe379e7](https://linux-hardware.org/?probe=1ecfe379e7) | Sep 26, 2022 |
| Apple         | Mac-A369DDC4E67F1C45 iMa... | All in one  | [a96f37005a](https://linux-hardware.org/?probe=a96f37005a) | Sep 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [6c0c9c0037](https://linux-hardware.org/?probe=6c0c9c0037) | Sep 25, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [479dfeae74](https://linux-hardware.org/?probe=479dfeae74) | Sep 25, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [6c8a53f608](https://linux-hardware.org/?probe=6c8a53f608) | Sep 25, 2022 |
| MSI           | H170M PRO-VDH               | Desktop     | [f7254adff2](https://linux-hardware.org/?probe=f7254adff2) | Sep 25, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [93dd525100](https://linux-hardware.org/?probe=93dd525100) | Sep 25, 2022 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [cedbd8909f](https://linux-hardware.org/?probe=cedbd8909f) | Sep 25, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [66b5b65077](https://linux-hardware.org/?probe=66b5b65077) | Sep 25, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [05dc7a54c7](https://linux-hardware.org/?probe=05dc7a54c7) | Sep 25, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [a35dda8c10](https://linux-hardware.org/?probe=a35dda8c10) | Sep 25, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [33a0b663ea](https://linux-hardware.org/?probe=33a0b663ea) | Sep 25, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [b598ecc4f8](https://linux-hardware.org/?probe=b598ecc4f8) | Sep 24, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ae43d0bbce](https://linux-hardware.org/?probe=ae43d0bbce) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [24b2810c64](https://linux-hardware.org/?probe=24b2810c64) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [0299e4f7b1](https://linux-hardware.org/?probe=0299e4f7b1) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [cad0f6f375](https://linux-hardware.org/?probe=cad0f6f375) | Sep 24, 2022 |
| MSI           | C236A WORKSTATION           | Desktop     | [67432a461e](https://linux-hardware.org/?probe=67432a461e) | Sep 24, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [91d179670c](https://linux-hardware.org/?probe=91d179670c) | Sep 23, 2022 |
| Acer          | TMP645-M                    | Notebook    | [83b27c389c](https://linux-hardware.org/?probe=83b27c389c) | Sep 23, 2022 |
| Dell          | 0KV62T A01                  | Desktop     | [d8d21241de](https://linux-hardware.org/?probe=d8d21241de) | Sep 23, 2022 |
| ASUSTek       | P6T                         | Desktop     | [612682c52d](https://linux-hardware.org/?probe=612682c52d) | Sep 23, 2022 |
| Dell          | Precision 7760              | Notebook    | [f47fe0314b](https://linux-hardware.org/?probe=f47fe0314b) | Sep 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [accc831d30](https://linux-hardware.org/?probe=accc831d30) | Sep 23, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | Notebook    | [a01352810a](https://linux-hardware.org/?probe=a01352810a) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | Notebook    | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [aa3088ed0e](https://linux-hardware.org/?probe=aa3088ed0e) | Sep 22, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [d97b8fc0ed](https://linux-hardware.org/?probe=d97b8fc0ed) | Sep 21, 2022 |
| ASRock        | Z690 Pro RS                 | Desktop     | [787589762f](https://linux-hardware.org/?probe=787589762f) | Sep 21, 2022 |
| Shuttle       | FS81                        | Desktop     | [4c1fb942aa](https://linux-hardware.org/?probe=4c1fb942aa) | Sep 20, 2022 |
| ASRock        | HM55-HT                     | Desktop     | [64fff8f065](https://linux-hardware.org/?probe=64fff8f065) | Sep 20, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [5cf4494f07](https://linux-hardware.org/?probe=5cf4494f07) | Sep 20, 2022 |
| ASRock        | H610M-HDV/M.2               | Desktop     | [02a5a10d7a](https://linux-hardware.org/?probe=02a5a10d7a) | Sep 20, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [7c7043ad0f](https://linux-hardware.org/?probe=7c7043ad0f) | Sep 19, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [48d71b12fc](https://linux-hardware.org/?probe=48d71b12fc) | Sep 19, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [ecc3b7e71d](https://linux-hardware.org/?probe=ecc3b7e71d) | Sep 19, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [43fbf9fec9](https://linux-hardware.org/?probe=43fbf9fec9) | Sep 19, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [850e17ede5](https://linux-hardware.org/?probe=850e17ede5) | Sep 19, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [6c63c03b9f](https://linux-hardware.org/?probe=6c63c03b9f) | Sep 19, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [3b5d6a5b1d](https://linux-hardware.org/?probe=3b5d6a5b1d) | Sep 18, 2022 |
| ASUSTek       | 1005HA                      | Notebook    | [3b1ce0471e](https://linux-hardware.org/?probe=3b1ce0471e) | Sep 18, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [126b3ed209](https://linux-hardware.org/?probe=126b3ed209) | Sep 14, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [08c270ce3d](https://linux-hardware.org/?probe=08c270ce3d) | Sep 14, 2022 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [fbd66d36f4](https://linux-hardware.org/?probe=fbd66d36f4) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [03ba2808d7](https://linux-hardware.org/?probe=03ba2808d7) | Sep 13, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [6121dfd67d](https://linux-hardware.org/?probe=6121dfd67d) | Sep 13, 2022 |
| HP            | ENVY 15                     | Notebook    | [fdb07294df](https://linux-hardware.org/?probe=fdb07294df) | Sep 13, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [ebd7ab6202](https://linux-hardware.org/?probe=ebd7ab6202) | Sep 12, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [613f741235](https://linux-hardware.org/?probe=613f741235) | Sep 12, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [491242ea90](https://linux-hardware.org/?probe=491242ea90) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [21ae14e7a0](https://linux-hardware.org/?probe=21ae14e7a0) | Sep 11, 2022 |
| Inventec      | C CLASS A01                 | Desktop     | [3ddd0d7aa0](https://linux-hardware.org/?probe=3ddd0d7aa0) | Sep 11, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [c3ceb9c38b](https://linux-hardware.org/?probe=c3ceb9c38b) | Sep 11, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [d477c1084d](https://linux-hardware.org/?probe=d477c1084d) | Sep 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [2cb423c8e7](https://linux-hardware.org/?probe=2cb423c8e7) | Sep 10, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1e8c2730c9](https://linux-hardware.org/?probe=1e8c2730c9) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [3c454664b0](https://linux-hardware.org/?probe=3c454664b0) | Sep 09, 2022 |
| Dell          | Latitude E7470              | Notebook    | [4a2f647549](https://linux-hardware.org/?probe=4a2f647549) | Sep 08, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [e36022370b](https://linux-hardware.org/?probe=e36022370b) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| ASUSTek       | X99-E WS/USB                | Desktop     | [56357e3cc7](https://linux-hardware.org/?probe=56357e3cc7) | Sep 07, 2022 |
| ASUSTek       | X99-E WS/USB                | Desktop     | [3432790e95](https://linux-hardware.org/?probe=3432790e95) | Sep 07, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [01dbdc3b29](https://linux-hardware.org/?probe=01dbdc3b29) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| Gigabyte      | Z690 AERO G DDR4            | Desktop     | [ccd383a106](https://linux-hardware.org/?probe=ccd383a106) | Sep 05, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [c37bace401](https://linux-hardware.org/?probe=c37bace401) | Sep 05, 2022 |
| Gigabyte      | AB350M-HD3-CF se1           | Desktop     | [0859dbdb1c](https://linux-hardware.org/?probe=0859dbdb1c) | Sep 04, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [a746f6faa6](https://linux-hardware.org/?probe=a746f6faa6) | Sep 04, 2022 |
| HP            | 2AF3                        | Desktop     | [58eae39fe2](https://linux-hardware.org/?probe=58eae39fe2) | Sep 03, 2022 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [e03d937610](https://linux-hardware.org/?probe=e03d937610) | Sep 02, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [a1b5555512](https://linux-hardware.org/?probe=a1b5555512) | Sep 02, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [0a1de8a406](https://linux-hardware.org/?probe=0a1de8a406) | Sep 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ac65980e25](https://linux-hardware.org/?probe=ac65980e25) | Sep 02, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [888ed47bbe](https://linux-hardware.org/?probe=888ed47bbe) | Sep 02, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [dc37712dfc](https://linux-hardware.org/?probe=dc37712dfc) | Sep 02, 2022 |
| Dell          | 0WPG9H A00                  | All in one  | [67aeed6eb1](https://linux-hardware.org/?probe=67aeed6eb1) | Sep 01, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [2cf98644bc](https://linux-hardware.org/?probe=2cf98644bc) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [8ac8531142](https://linux-hardware.org/?probe=8ac8531142) | Sep 01, 2022 |
| Toshiba       | Satellite C850              | Notebook    | [6cf6d8fca8](https://linux-hardware.org/?probe=6cf6d8fca8) | Sep 01, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [21f3eb8b1d](https://linux-hardware.org/?probe=21f3eb8b1d) | Sep 01, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [6e245e4c63](https://linux-hardware.org/?probe=6e245e4c63) | Sep 01, 2022 |
| HP            | Notebook                    | Notebook    | [ee135c3930](https://linux-hardware.org/?probe=ee135c3930) | Aug 31, 2022 |
| Toshiba       | Satellite C850              | Notebook    | [5d7cb36794](https://linux-hardware.org/?probe=5d7cb36794) | Aug 31, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [53af4f5de7](https://linux-hardware.org/?probe=53af4f5de7) | Aug 30, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [897046248f](https://linux-hardware.org/?probe=897046248f) | Aug 30, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [eaa574481f](https://linux-hardware.org/?probe=eaa574481f) | Aug 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [fd4ab67b77](https://linux-hardware.org/?probe=fd4ab67b77) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| IT Channel... | NH5xAx                      | Notebook    | [66573b4b48](https://linux-hardware.org/?probe=66573b4b48) | Aug 28, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [a0f47aaaa7](https://linux-hardware.org/?probe=a0f47aaaa7) | Aug 28, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [459c7c1eee](https://linux-hardware.org/?probe=459c7c1eee) | Aug 27, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [137641269c](https://linux-hardware.org/?probe=137641269c) | Aug 27, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [f30320f76e](https://linux-hardware.org/?probe=f30320f76e) | Aug 27, 2022 |
| Acer          | Aspire V5-531               | Notebook    | [75b841b0b8](https://linux-hardware.org/?probe=75b841b0b8) | Aug 26, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [51e23209a4](https://linux-hardware.org/?probe=51e23209a4) | Aug 26, 2022 |
| Dell          | Latitude 5300               | Notebook    | [f336b3aeaf](https://linux-hardware.org/?probe=f336b3aeaf) | Aug 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [f37ee1975e](https://linux-hardware.org/?probe=f37ee1975e) | Aug 26, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | Notebook    | [416e5db831](https://linux-hardware.org/?probe=416e5db831) | Aug 26, 2022 |
| Lenovo        | 1046 NO DPK                 | Desktop     | [e21e07827d](https://linux-hardware.org/?probe=e21e07827d) | Aug 26, 2022 |
| Acer          | Aspire V5-531               | Notebook    | [4ae228e219](https://linux-hardware.org/?probe=4ae228e219) | Aug 25, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2388b95ce9](https://linux-hardware.org/?probe=2388b95ce9) | Aug 25, 2022 |
| ASUSTek       | Z97-AR                      | Desktop     | [a766ce2d5a](https://linux-hardware.org/?probe=a766ce2d5a) | Aug 24, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [fda9abd530](https://linux-hardware.org/?probe=fda9abd530) | Aug 24, 2022 |
| HP            | 1905                        | Desktop     | [6693a2b3c7](https://linux-hardware.org/?probe=6693a2b3c7) | Aug 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [18102e8a9a](https://linux-hardware.org/?probe=18102e8a9a) | Aug 24, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [738a69419b](https://linux-hardware.org/?probe=738a69419b) | Aug 24, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [d609bf3253](https://linux-hardware.org/?probe=d609bf3253) | Aug 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [7dae220687](https://linux-hardware.org/?probe=7dae220687) | Aug 23, 2022 |
| Alienware     | 15 R4                       | Notebook    | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [a6726b8439](https://linux-hardware.org/?probe=a6726b8439) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [aff9259c2c](https://linux-hardware.org/?probe=aff9259c2c) | Aug 22, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [75f94f8fa5](https://linux-hardware.org/?probe=75f94f8fa5) | Aug 21, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [4be47e3738](https://linux-hardware.org/?probe=4be47e3738) | Aug 21, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [c369daf6b0](https://linux-hardware.org/?probe=c369daf6b0) | Aug 21, 2022 |
| ASRock        | Z77 Extreme6                | Desktop     | [660091e5bb](https://linux-hardware.org/?probe=660091e5bb) | Aug 20, 2022 |
| Google        | Teemo                       | Desktop     | [4cc9295e6d](https://linux-hardware.org/?probe=4cc9295e6d) | Aug 20, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [7a8fee05aa](https://linux-hardware.org/?probe=7a8fee05aa) | Aug 20, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [c9738d69e9](https://linux-hardware.org/?probe=c9738d69e9) | Aug 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [9bfc03d98e](https://linux-hardware.org/?probe=9bfc03d98e) | Aug 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [ed2076bba5](https://linux-hardware.org/?probe=ed2076bba5) | Aug 20, 2022 |
| ASUSTek       | X756UAK                     | Notebook    | [6db3b2a7bc](https://linux-hardware.org/?probe=6db3b2a7bc) | Aug 20, 2022 |
| Dell          | G3 3779                     | Notebook    | [a2b721ca15](https://linux-hardware.org/?probe=a2b721ca15) | Aug 19, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [9e6a3e80b4](https://linux-hardware.org/?probe=9e6a3e80b4) | Aug 19, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [266f9fc41d](https://linux-hardware.org/?probe=266f9fc41d) | Aug 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e500790878](https://linux-hardware.org/?probe=e500790878) | Aug 18, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [1e4e125d11](https://linux-hardware.org/?probe=1e4e125d11) | Aug 17, 2022 |
| Lenovo        | ThinkPad T480s 20L70044A... | Notebook    | [f90559618b](https://linux-hardware.org/?probe=f90559618b) | Aug 17, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [1efeb7be2c](https://linux-hardware.org/?probe=1efeb7be2c) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [26f646cca0](https://linux-hardware.org/?probe=26f646cca0) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [125fdc6af1](https://linux-hardware.org/?probe=125fdc6af1) | Aug 17, 2022 |
| Dell          | 0WPG9H A00                  | All in one  | [87ba9f4be1](https://linux-hardware.org/?probe=87ba9f4be1) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [98b5311ef6](https://linux-hardware.org/?probe=98b5311ef6) | Aug 17, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [e68748c0f1](https://linux-hardware.org/?probe=e68748c0f1) | Aug 16, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [171a797c22](https://linux-hardware.org/?probe=171a797c22) | Aug 16, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [f882fcbe3a](https://linux-hardware.org/?probe=f882fcbe3a) | Aug 16, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [8072e15459](https://linux-hardware.org/?probe=8072e15459) | Aug 15, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | Notebook    | [e32eeecfaa](https://linux-hardware.org/?probe=e32eeecfaa) | Aug 15, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [20d9ba44b5](https://linux-hardware.org/?probe=20d9ba44b5) | Aug 15, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [be0b70efdb](https://linux-hardware.org/?probe=be0b70efdb) | Aug 15, 2022 |
| MSI           | H61M-P20                    | Desktop     | [9adc2fa427](https://linux-hardware.org/?probe=9adc2fa427) | Aug 15, 2022 |
| HP            | 1493                        | Desktop     | [e5d0f16bbc](https://linux-hardware.org/?probe=e5d0f16bbc) | Aug 14, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [2c210a5825](https://linux-hardware.org/?probe=2c210a5825) | Aug 14, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [dc9013cc44](https://linux-hardware.org/?probe=dc9013cc44) | Aug 14, 2022 |
| ASRock        | AB350 Gaming K4             | Desktop     | [8a6141848a](https://linux-hardware.org/?probe=8a6141848a) | Aug 13, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [0d58c17039](https://linux-hardware.org/?probe=0d58c17039) | Aug 13, 2022 |
| MSI           | H61M-P20                    | Desktop     | [acc2520058](https://linux-hardware.org/?probe=acc2520058) | Aug 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [26c131aca1](https://linux-hardware.org/?probe=26c131aca1) | Aug 13, 2022 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [762d78160d](https://linux-hardware.org/?probe=762d78160d) | Aug 12, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [662f0801b7](https://linux-hardware.org/?probe=662f0801b7) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [166edbd7db](https://linux-hardware.org/?probe=166edbd7db) | Aug 12, 2022 |
| Dell          | Latitude 6430U              | Notebook    | [d21ca8c2e6](https://linux-hardware.org/?probe=d21ca8c2e6) | Aug 11, 2022 |
| Gigabyte      | Z87M-D3HP                   | Desktop     | [b6612680e2](https://linux-hardware.org/?probe=b6612680e2) | Aug 11, 2022 |
| ASRock        | X58 Extreme3                | Desktop     | [81f68d4fc7](https://linux-hardware.org/?probe=81f68d4fc7) | Aug 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [dc354e0b4f](https://linux-hardware.org/?probe=dc354e0b4f) | Aug 10, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [62d813423e](https://linux-hardware.org/?probe=62d813423e) | Aug 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [e74a95c4d9](https://linux-hardware.org/?probe=e74a95c4d9) | Aug 09, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [42d32cdfda](https://linux-hardware.org/?probe=42d32cdfda) | Aug 09, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7f1e38b57b](https://linux-hardware.org/?probe=7f1e38b57b) | Aug 07, 2022 |
| HP            | 2B21 A01                    | All in one  | [aba1a53f52](https://linux-hardware.org/?probe=aba1a53f52) | Aug 07, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [6a73917b78](https://linux-hardware.org/?probe=6a73917b78) | Aug 07, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [db3d9f24c6](https://linux-hardware.org/?probe=db3d9f24c6) | Aug 07, 2022 |
| ASUSTek       | ET2701I-W8                  | Desktop     | [5f9c4b50db](https://linux-hardware.org/?probe=5f9c4b50db) | Aug 07, 2022 |
| Unknown       | Unknown                     | Soc         | [9efd347024](https://linux-hardware.org/?probe=9efd347024) | Aug 06, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [fd6cf872ae](https://linux-hardware.org/?probe=fd6cf872ae) | Aug 06, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [1798c25088](https://linux-hardware.org/?probe=1798c25088) | Aug 05, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [72a09e7b69](https://linux-hardware.org/?probe=72a09e7b69) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | Notebook    | [abaec227ae](https://linux-hardware.org/?probe=abaec227ae) | Aug 05, 2022 |
| Lenovo        | XiaoXinPro 16 ARH7 82SN     | Notebook    | [a1effa04c3](https://linux-hardware.org/?probe=a1effa04c3) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [209cd4bc66](https://linux-hardware.org/?probe=209cd4bc66) | Aug 05, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [caa404d4c6](https://linux-hardware.org/?probe=caa404d4c6) | Aug 05, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [8b737740c3](https://linux-hardware.org/?probe=8b737740c3) | Aug 05, 2022 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [e477bf9f83](https://linux-hardware.org/?probe=e477bf9f83) | Aug 05, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [3ef0714d78](https://linux-hardware.org/?probe=3ef0714d78) | Aug 04, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [360447806b](https://linux-hardware.org/?probe=360447806b) | Aug 04, 2022 |
| Dell          | 06WXJT A02                  | Server      | [424b1059df](https://linux-hardware.org/?probe=424b1059df) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | Notebook    | [302749341d](https://linux-hardware.org/?probe=302749341d) | Aug 03, 2022 |
| Lenovo        | 3102                        | Desktop     | [73e0fee2bc](https://linux-hardware.org/?probe=73e0fee2bc) | Aug 03, 2022 |
| Dell          | 06WXJT A07                  | Server      | [e0b1ede266](https://linux-hardware.org/?probe=e0b1ede266) | Aug 03, 2022 |
| Dell          | 06WXJT A02                  | Server      | [fcf7baab04](https://linux-hardware.org/?probe=fcf7baab04) | Aug 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [713884d2c8](https://linux-hardware.org/?probe=713884d2c8) | Aug 03, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [b81c8578b9](https://linux-hardware.org/?probe=b81c8578b9) | Aug 03, 2022 |
| Dell          | XPS 9320                    | Notebook    | [9b24b29553](https://linux-hardware.org/?probe=9b24b29553) | Aug 03, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [63553d673b](https://linux-hardware.org/?probe=63553d673b) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | Notebook    | [e6189ba78c](https://linux-hardware.org/?probe=e6189ba78c) | Aug 02, 2022 |
| Hardkernel    | ODROID-C4                   | Soc         | [85ed0f33f0](https://linux-hardware.org/?probe=85ed0f33f0) | Aug 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | Notebook    | [a67d881d6f](https://linux-hardware.org/?probe=a67d881d6f) | Aug 02, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [b352b7e051](https://linux-hardware.org/?probe=b352b7e051) | Aug 02, 2022 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [2de5d5cf8a](https://linux-hardware.org/?probe=2de5d5cf8a) | Aug 02, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [77687a9bac](https://linux-hardware.org/?probe=77687a9bac) | Aug 02, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [6127d6e7a3](https://linux-hardware.org/?probe=6127d6e7a3) | Aug 02, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [9983a0cc64](https://linux-hardware.org/?probe=9983a0cc64) | Aug 02, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [dcccfd1beb](https://linux-hardware.org/?probe=dcccfd1beb) | Aug 01, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [e1fa8ab12b](https://linux-hardware.org/?probe=e1fa8ab12b) | Aug 01, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [370b872aa5](https://linux-hardware.org/?probe=370b872aa5) | Aug 01, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [81c46b891f](https://linux-hardware.org/?probe=81c46b891f) | Aug 01, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [d58be7b6d1](https://linux-hardware.org/?probe=d58be7b6d1) | Aug 01, 2022 |
| Unknown       | Unknown                     | Soc         | [9ebddaa953](https://linux-hardware.org/?probe=9ebddaa953) | Jul 31, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [e8dba6ab7e](https://linux-hardware.org/?probe=e8dba6ab7e) | Jul 31, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [f6a106d6df](https://linux-hardware.org/?probe=f6a106d6df) | Jul 31, 2022 |
| Intel         | NUC7i5BNB J31144-302        | Mini pc     | [638275ad97](https://linux-hardware.org/?probe=638275ad97) | Jul 31, 2022 |
| HP            | 82F2                        | Desktop     | [0c2d091c2e](https://linux-hardware.org/?probe=0c2d091c2e) | Jul 31, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [c7ed484a1f](https://linux-hardware.org/?probe=c7ed484a1f) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [51695dd3ea](https://linux-hardware.org/?probe=51695dd3ea) | Jul 29, 2022 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [2381ee35c0](https://linux-hardware.org/?probe=2381ee35c0) | Jul 29, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [73c8bc2ae1](https://linux-hardware.org/?probe=73c8bc2ae1) | Jul 28, 2022 |
| Lenovo        | 3717 SDK0R32862 WIN 3258... | Desktop     | [757ba0f252](https://linux-hardware.org/?probe=757ba0f252) | Jul 28, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [1357e3b3d3](https://linux-hardware.org/?probe=1357e3b3d3) | Jul 28, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [e42501aacb](https://linux-hardware.org/?probe=e42501aacb) | Jul 28, 2022 |
| ASUSTek       | X555YA                      | Notebook    | [ddd00fbeea](https://linux-hardware.org/?probe=ddd00fbeea) | Jul 28, 2022 |
| Unknown       | HX90                        | Desktop     | [1594710372](https://linux-hardware.org/?probe=1594710372) | Jul 28, 2022 |
| Dell          | Latitude E7250              | Notebook    | [26a8591f1d](https://linux-hardware.org/?probe=26a8591f1d) | Jul 27, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [761563e485](https://linux-hardware.org/?probe=761563e485) | Jul 27, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [5e7b9f2b14](https://linux-hardware.org/?probe=5e7b9f2b14) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [331a99ef9a](https://linux-hardware.org/?probe=331a99ef9a) | Jul 26, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [1f3433b9e1](https://linux-hardware.org/?probe=1f3433b9e1) | Jul 26, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [876c60188f](https://linux-hardware.org/?probe=876c60188f) | Jul 26, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [050aa57cb4](https://linux-hardware.org/?probe=050aa57cb4) | Jul 26, 2022 |
| Dell          | Latitude 3400               | Notebook    | [3412e8deac](https://linux-hardware.org/?probe=3412e8deac) | Jul 26, 2022 |
| Lenovo        | G570 4334                   | Notebook    | [e4c223e83e](https://linux-hardware.org/?probe=e4c223e83e) | Jul 25, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [7af6c5cebe](https://linux-hardware.org/?probe=7af6c5cebe) | Jul 24, 2022 |
| Lenovo        | 3702 SDK0J40700 WIN 3258... | All in one  | [95af4e4f8e](https://linux-hardware.org/?probe=95af4e4f8e) | Jul 23, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [ede7f6cdae](https://linux-hardware.org/?probe=ede7f6cdae) | Jul 23, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [85f2ffe45a](https://linux-hardware.org/?probe=85f2ffe45a) | Jul 22, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [d57e35934f](https://linux-hardware.org/?probe=d57e35934f) | Jul 22, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [2723b19c18](https://linux-hardware.org/?probe=2723b19c18) | Jul 22, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [80dcd8a0f7](https://linux-hardware.org/?probe=80dcd8a0f7) | Jul 22, 2022 |
| Google        | Peppy                       | Notebook    | [3bfdae8e5e](https://linux-hardware.org/?probe=3bfdae8e5e) | Jul 21, 2022 |
| Acer          | Aspire One 753              | Notebook    | [eff74923d7](https://linux-hardware.org/?probe=eff74923d7) | Jul 21, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [89e0889e94](https://linux-hardware.org/?probe=89e0889e94) | Jul 21, 2022 |
| Dell          | Latitude 5430               | Notebook    | [f02c4072c1](https://linux-hardware.org/?probe=f02c4072c1) | Jul 21, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [c3722806fe](https://linux-hardware.org/?probe=c3722806fe) | Jul 21, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [add1e46d7e](https://linux-hardware.org/?probe=add1e46d7e) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [2360c35ac1](https://linux-hardware.org/?probe=2360c35ac1) | Jul 20, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [5cb9487776](https://linux-hardware.org/?probe=5cb9487776) | Jul 20, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [85df5dd7a2](https://linux-hardware.org/?probe=85df5dd7a2) | Jul 19, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [b0e3b75c3b](https://linux-hardware.org/?probe=b0e3b75c3b) | Jul 19, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [a5082efd70](https://linux-hardware.org/?probe=a5082efd70) | Jul 19, 2022 |
| Acer          | TravelMate 8572T            | Notebook    | [54e7b50fc7](https://linux-hardware.org/?probe=54e7b50fc7) | Jul 18, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [870cda5796](https://linux-hardware.org/?probe=870cda5796) | Jul 17, 2022 |
| ReachingTe... | Dream Quest Office 2021     | Mini pc     | [662e59e904](https://linux-hardware.org/?probe=662e59e904) | Jul 17, 2022 |
| Alienware     | x17 R1                      | Notebook    | [9fc2d6416d](https://linux-hardware.org/?probe=9fc2d6416d) | Jul 16, 2022 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [713765e224](https://linux-hardware.org/?probe=713765e224) | Jul 16, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a1a565d211](https://linux-hardware.org/?probe=a1a565d211) | Jul 16, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [950542a4a3](https://linux-hardware.org/?probe=950542a4a3) | Jul 16, 2022 |
| HP            | 802E                        | Desktop     | [c86ddd647b](https://linux-hardware.org/?probe=c86ddd647b) | Jul 16, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | Notebook    | [5fd8a1dcf4](https://linux-hardware.org/?probe=5fd8a1dcf4) | Jul 15, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [f655a34cc1](https://linux-hardware.org/?probe=f655a34cc1) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [de83d4ef43](https://linux-hardware.org/?probe=de83d4ef43) | Jul 15, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [a27d53815e](https://linux-hardware.org/?probe=a27d53815e) | Jul 15, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [01e6c30eff](https://linux-hardware.org/?probe=01e6c30eff) | Jul 15, 2022 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [73be4f7864](https://linux-hardware.org/?probe=73be4f7864) | Jul 14, 2022 |
| Acer          | Nitro AN515-56              | Notebook    | [2418745195](https://linux-hardware.org/?probe=2418745195) | Jul 14, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [56be64f444](https://linux-hardware.org/?probe=56be64f444) | Jul 14, 2022 |
| ASUSTek       | GL702ZC                     | Notebook    | [755f571a3e](https://linux-hardware.org/?probe=755f571a3e) | Jul 14, 2022 |
| Dell          | 0W2F8G A01                  | Desktop     | [77f2181e08](https://linux-hardware.org/?probe=77f2181e08) | Jul 13, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [ff67056edc](https://linux-hardware.org/?probe=ff67056edc) | Jul 13, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [29602ec66f](https://linux-hardware.org/?probe=29602ec66f) | Jul 13, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [ef3bc84295](https://linux-hardware.org/?probe=ef3bc84295) | Jul 13, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [0c70241041](https://linux-hardware.org/?probe=0c70241041) | Jul 13, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [4126a95603](https://linux-hardware.org/?probe=4126a95603) | Jul 13, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [0ce6078768](https://linux-hardware.org/?probe=0ce6078768) | Jul 12, 2022 |
| Unknown       | Unknown                     | Soc         | [d3742575fd](https://linux-hardware.org/?probe=d3742575fd) | Jul 12, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [facbace782](https://linux-hardware.org/?probe=facbace782) | Jul 12, 2022 |
| MSI           | X99S GAMING 9 AC            | Desktop     | [5f682aadd5](https://linux-hardware.org/?probe=5f682aadd5) | Jul 12, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [4929b942aa](https://linux-hardware.org/?probe=4929b942aa) | Jul 12, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [07a37c99cb](https://linux-hardware.org/?probe=07a37c99cb) | Jul 11, 2022 |
| Acer          | Aspire 1830T                | Notebook    | [d2ff08ade8](https://linux-hardware.org/?probe=d2ff08ade8) | Jul 10, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [cdf7b9a4d1](https://linux-hardware.org/?probe=cdf7b9a4d1) | Jul 10, 2022 |
| Gigabyte      | H170N-WIFI-CF               | Desktop     | [2f3e59dc30](https://linux-hardware.org/?probe=2f3e59dc30) | Jul 09, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [60d115ad0c](https://linux-hardware.org/?probe=60d115ad0c) | Jul 09, 2022 |
| ASRock        | Z77 Extreme6                | Desktop     | [fd8bd29c03](https://linux-hardware.org/?probe=fd8bd29c03) | Jul 09, 2022 |
| Acer          | Aspire Z3-710               | All in one  | [5f7d41a8ae](https://linux-hardware.org/?probe=5f7d41a8ae) | Jul 09, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [36fa61e21d](https://linux-hardware.org/?probe=36fa61e21d) | Jul 09, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [4b7c20d75e](https://linux-hardware.org/?probe=4b7c20d75e) | Jul 09, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [fb5a2ac873](https://linux-hardware.org/?probe=fb5a2ac873) | Jul 09, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [c048bb9697](https://linux-hardware.org/?probe=c048bb9697) | Jul 09, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [663a6c9413](https://linux-hardware.org/?probe=663a6c9413) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [48bd0906cf](https://linux-hardware.org/?probe=48bd0906cf) | Jul 08, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [749a597089](https://linux-hardware.org/?probe=749a597089) | Jul 08, 2022 |
| Gigabyte      | B550 AORUS PRO AX           | Desktop     | [9ad45447d4](https://linux-hardware.org/?probe=9ad45447d4) | Jul 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [e34a9c3166](https://linux-hardware.org/?probe=e34a9c3166) | Jul 08, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [4da61d3e61](https://linux-hardware.org/?probe=4da61d3e61) | Jul 07, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [503c38154f](https://linux-hardware.org/?probe=503c38154f) | Jul 07, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [1a2485b399](https://linux-hardware.org/?probe=1a2485b399) | Jul 06, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [ce6d3ec137](https://linux-hardware.org/?probe=ce6d3ec137) | Jul 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [e24a6dd845](https://linux-hardware.org/?probe=e24a6dd845) | Jul 05, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [d6dccd6ed7](https://linux-hardware.org/?probe=d6dccd6ed7) | Jul 05, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [422a12c217](https://linux-hardware.org/?probe=422a12c217) | Jul 05, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0cd693879d](https://linux-hardware.org/?probe=0cd693879d) | Jul 05, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [76d6073818](https://linux-hardware.org/?probe=76d6073818) | Jul 05, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [e69b07f3e9](https://linux-hardware.org/?probe=e69b07f3e9) | Jul 05, 2022 |
| Dell          | Precision M4700             | Notebook    | [48cbbf8dd2](https://linux-hardware.org/?probe=48cbbf8dd2) | Jul 05, 2022 |
| ASRock        | 990FX Killer                | Desktop     | [28b0984086](https://linux-hardware.org/?probe=28b0984086) | Jul 05, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [e795477a20](https://linux-hardware.org/?probe=e795477a20) | Jul 05, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [748f42be21](https://linux-hardware.org/?probe=748f42be21) | Jul 05, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [40d0cb89c5](https://linux-hardware.org/?probe=40d0cb89c5) | Jul 04, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [e165fd805c](https://linux-hardware.org/?probe=e165fd805c) | Jul 04, 2022 |
| HP            | 3646h                       | Desktop     | [9e0737f23f](https://linux-hardware.org/?probe=9e0737f23f) | Jul 04, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [e99c8ae46f](https://linux-hardware.org/?probe=e99c8ae46f) | Jul 04, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [4600681149](https://linux-hardware.org/?probe=4600681149) | Jul 03, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [85c5a62101](https://linux-hardware.org/?probe=85c5a62101) | Jul 03, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [bcc3835be5](https://linux-hardware.org/?probe=bcc3835be5) | Jul 03, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [fc29bb14e9](https://linux-hardware.org/?probe=fc29bb14e9) | Jul 03, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [5f3197f581](https://linux-hardware.org/?probe=5f3197f581) | Jul 03, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [f2a1afe8eb](https://linux-hardware.org/?probe=f2a1afe8eb) | Jul 03, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [1295c3de55](https://linux-hardware.org/?probe=1295c3de55) | Jul 03, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [dd9610011c](https://linux-hardware.org/?probe=dd9610011c) | Jul 02, 2022 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [4044d76f9b](https://linux-hardware.org/?probe=4044d76f9b) | Jul 02, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [ef2f004b52](https://linux-hardware.org/?probe=ef2f004b52) | Jul 02, 2022 |
| ASRock        | Z390 Pro4                   | Desktop     | [25bd784ca6](https://linux-hardware.org/?probe=25bd784ca6) | Jul 02, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [4f6364d861](https://linux-hardware.org/?probe=4f6364d861) | Jul 02, 2022 |
| Dell          | Inspiron M5010              | Notebook    | [14b9aa33d2](https://linux-hardware.org/?probe=14b9aa33d2) | Jul 01, 2022 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [9b8bb163d3](https://linux-hardware.org/?probe=9b8bb163d3) | Jul 01, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [d82f88e20c](https://linux-hardware.org/?probe=d82f88e20c) | Jul 01, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [cea6c9ea52](https://linux-hardware.org/?probe=cea6c9ea52) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [cd488e4f64](https://linux-hardware.org/?probe=cd488e4f64) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [52dfa0a4ee](https://linux-hardware.org/?probe=52dfa0a4ee) | Jun 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3a423eae14](https://linux-hardware.org/?probe=3a423eae14) | Jun 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [af29dc9fe1](https://linux-hardware.org/?probe=af29dc9fe1) | Jun 30, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [1b5babe2aa](https://linux-hardware.org/?probe=1b5babe2aa) | Jun 29, 2022 |
| AMI           | Intel                       | Notebook    | [2b592e2f4a](https://linux-hardware.org/?probe=2b592e2f4a) | Jun 29, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [909e3e3c2e](https://linux-hardware.org/?probe=909e3e3c2e) | Jun 29, 2022 |
| Dell          | Latitude 5430               | Notebook    | [119502eddb](https://linux-hardware.org/?probe=119502eddb) | Jun 29, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [b6cfc5d2df](https://linux-hardware.org/?probe=b6cfc5d2df) | Jun 28, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [20de16a046](https://linux-hardware.org/?probe=20de16a046) | Jun 28, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [d2034a53b8](https://linux-hardware.org/?probe=d2034a53b8) | Jun 28, 2022 |
| ASUSTek       | A88X-GAMER                  | Desktop     | [b7e193f50c](https://linux-hardware.org/?probe=b7e193f50c) | Jun 28, 2022 |
| Dell          | G3 3500                     | Notebook    | [0df1b9607c](https://linux-hardware.org/?probe=0df1b9607c) | Jun 27, 2022 |
| Dell          | 051FJ8 A02                  | Desktop     | [5b997790f1](https://linux-hardware.org/?probe=5b997790f1) | Jun 27, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [b947b14fe4](https://linux-hardware.org/?probe=b947b14fe4) | Jun 27, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [d703a63932](https://linux-hardware.org/?probe=d703a63932) | Jun 26, 2022 |
| MSI           | PRO Z690-A                  | Desktop     | [34a2f4f726](https://linux-hardware.org/?probe=34a2f4f726) | Jun 26, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [2f4500ddad](https://linux-hardware.org/?probe=2f4500ddad) | Jun 26, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [bd52209b2a](https://linux-hardware.org/?probe=bd52209b2a) | Jun 24, 2022 |
| Alienware     | 14                          | Notebook    | [8846f2e474](https://linux-hardware.org/?probe=8846f2e474) | Jun 24, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [015aa87271](https://linux-hardware.org/?probe=015aa87271) | Jun 24, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [e6f1068c91](https://linux-hardware.org/?probe=e6f1068c91) | Jun 24, 2022 |
| HP            | Presario CQ62               | Notebook    | [2f136051c9](https://linux-hardware.org/?probe=2f136051c9) | Jun 24, 2022 |
| HP            | Presario CQ62               | Notebook    | [9beeb6d3c2](https://linux-hardware.org/?probe=9beeb6d3c2) | Jun 23, 2022 |
| Lenovo        | ThinkPad E490s 20NG0002A... | Notebook    | [4cce05dc1c](https://linux-hardware.org/?probe=4cce05dc1c) | Jun 23, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [3656b8227f](https://linux-hardware.org/?probe=3656b8227f) | Jun 23, 2022 |
| Toshiba       | TECRA A40-D                 | Notebook    | [6307594332](https://linux-hardware.org/?probe=6307594332) | Jun 23, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [989b450d8b](https://linux-hardware.org/?probe=989b450d8b) | Jun 23, 2022 |
| Dell          | 0W2F8G A01                  | Desktop     | [4610c38358](https://linux-hardware.org/?probe=4610c38358) | Jun 22, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ae30cadddf](https://linux-hardware.org/?probe=ae30cadddf) | Jun 22, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [b65a5020db](https://linux-hardware.org/?probe=b65a5020db) | Jun 22, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [bc159b637c](https://linux-hardware.org/?probe=bc159b637c) | Jun 22, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [d5098cc011](https://linux-hardware.org/?probe=d5098cc011) | Jun 22, 2022 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [20cf9d2706](https://linux-hardware.org/?probe=20cf9d2706) | Jun 21, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [30d0a46d81](https://linux-hardware.org/?probe=30d0a46d81) | Jun 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [ecc6e0f4ef](https://linux-hardware.org/?probe=ecc6e0f4ef) | Jun 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [f013ebb91b](https://linux-hardware.org/?probe=f013ebb91b) | Jun 20, 2022 |
| Acer          | Iconia                      | Notebook    | [2d1f1a2c32](https://linux-hardware.org/?probe=2d1f1a2c32) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [b3da04a3af](https://linux-hardware.org/?probe=b3da04a3af) | Jun 20, 2022 |
| Framework     | Laptop                      | Notebook    | [f5ece7ce85](https://linux-hardware.org/?probe=f5ece7ce85) | Jun 19, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [a59676f7be](https://linux-hardware.org/?probe=a59676f7be) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [b88b88ba84](https://linux-hardware.org/?probe=b88b88ba84) | Jun 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [ec132b0ba5](https://linux-hardware.org/?probe=ec132b0ba5) | Jun 19, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [66d09f029f](https://linux-hardware.org/?probe=66d09f029f) | Jun 18, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [dfed0867e1](https://linux-hardware.org/?probe=dfed0867e1) | Jun 17, 2022 |
| Dell          | Precision 5540              | Notebook    | [6d3f2c188b](https://linux-hardware.org/?probe=6d3f2c188b) | Jun 17, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [0d4c3d0c10](https://linux-hardware.org/?probe=0d4c3d0c10) | Jun 17, 2022 |
| Acer          | Aspire TC-230               | Desktop     | [ac205eb1ec](https://linux-hardware.org/?probe=ac205eb1ec) | Jun 17, 2022 |
| Acer          | ConceptD CN315-71P          | Notebook    | [9b162f339b](https://linux-hardware.org/?probe=9b162f339b) | Jun 16, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [17e9f5a71f](https://linux-hardware.org/?probe=17e9f5a71f) | Jun 16, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [527aea0d6e](https://linux-hardware.org/?probe=527aea0d6e) | Jun 16, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [4c97b8cc3a](https://linux-hardware.org/?probe=4c97b8cc3a) | Jun 16, 2022 |
| Alienware     | m15 R7                      | Notebook    | [9775a12e11](https://linux-hardware.org/?probe=9775a12e11) | Jun 16, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [bb631825e3](https://linux-hardware.org/?probe=bb631825e3) | Jun 15, 2022 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [57ad2e9147](https://linux-hardware.org/?probe=57ad2e9147) | Jun 15, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [8ded20d82b](https://linux-hardware.org/?probe=8ded20d82b) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [76fd9cba2e](https://linux-hardware.org/?probe=76fd9cba2e) | Jun 15, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [cc88cec642](https://linux-hardware.org/?probe=cc88cec642) | Jun 14, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [b3259c0af4](https://linux-hardware.org/?probe=b3259c0af4) | Jun 14, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [bd16d5829c](https://linux-hardware.org/?probe=bd16d5829c) | Jun 14, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [848f1d55c8](https://linux-hardware.org/?probe=848f1d55c8) | Jun 14, 2022 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [aca5883c17](https://linux-hardware.org/?probe=aca5883c17) | Jun 14, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [fb157585e5](https://linux-hardware.org/?probe=fb157585e5) | Jun 14, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [57b90afcda](https://linux-hardware.org/?probe=57b90afcda) | Jun 14, 2022 |
| Intel         | DH67BL AAG10189-211         | Desktop     | [8bb84d5aaf](https://linux-hardware.org/?probe=8bb84d5aaf) | Jun 14, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [f9e74fdcd3](https://linux-hardware.org/?probe=f9e74fdcd3) | Jun 13, 2022 |
| Unknown       | Unknown                     | Desktop     | [c62add2d70](https://linux-hardware.org/?probe=c62add2d70) | Jun 13, 2022 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [94abe2c8af](https://linux-hardware.org/?probe=94abe2c8af) | Jun 13, 2022 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [0c6a9f5dff](https://linux-hardware.org/?probe=0c6a9f5dff) | Jun 13, 2022 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [aeec9e715d](https://linux-hardware.org/?probe=aeec9e715d) | Jun 13, 2022 |
| Dell          | Vostro 1500                 | Notebook    | [748a8a831b](https://linux-hardware.org/?probe=748a8a831b) | Jun 12, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [db209b6bf1](https://linux-hardware.org/?probe=db209b6bf1) | Jun 12, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [0c0715a9b2](https://linux-hardware.org/?probe=0c0715a9b2) | Jun 12, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [1e3a9647e9](https://linux-hardware.org/?probe=1e3a9647e9) | Jun 12, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [23fa842567](https://linux-hardware.org/?probe=23fa842567) | Jun 11, 2022 |
| HP            | Compaq 6730b                | Notebook    | [dd94c9145b](https://linux-hardware.org/?probe=dd94c9145b) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [576fc8e8ed](https://linux-hardware.org/?probe=576fc8e8ed) | Jun 11, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [fd1478145b](https://linux-hardware.org/?probe=fd1478145b) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | Desktop     | [a4277bcba9](https://linux-hardware.org/?probe=a4277bcba9) | Jun 11, 2022 |
| ASUSTek       | TUF B360M-E GAMING          | Desktop     | [b1e492c444](https://linux-hardware.org/?probe=b1e492c444) | Jun 10, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [b771c75e31](https://linux-hardware.org/?probe=b771c75e31) | Jun 10, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [9198e2d64c](https://linux-hardware.org/?probe=9198e2d64c) | Jun 10, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [267db233fa](https://linux-hardware.org/?probe=267db233fa) | Jun 10, 2022 |
| Gigabyte      | GA-990FXA-UD5               | Desktop     | [b33d07af6c](https://linux-hardware.org/?probe=b33d07af6c) | Jun 09, 2022 |
| ASUSTek       | Unknown                     | Notebook    | [1cc4adfa36](https://linux-hardware.org/?probe=1cc4adfa36) | Jun 09, 2022 |
| Alienware     | x17 R2                      | Notebook    | [78b867a06e](https://linux-hardware.org/?probe=78b867a06e) | Jun 08, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [75d6b8489b](https://linux-hardware.org/?probe=75d6b8489b) | Jun 08, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [2ac69cc327](https://linux-hardware.org/?probe=2ac69cc327) | Jun 08, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [9342f5c46b](https://linux-hardware.org/?probe=9342f5c46b) | Jun 08, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [fdba6d0041](https://linux-hardware.org/?probe=fdba6d0041) | Jun 08, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [d984f403e9](https://linux-hardware.org/?probe=d984f403e9) | Jun 08, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [73e68df88c](https://linux-hardware.org/?probe=73e68df88c) | Jun 08, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [bfa4e4ff74](https://linux-hardware.org/?probe=bfa4e4ff74) | Jun 07, 2022 |
| Lenovo        | 0B98401 PRO                 | Desktop     | [67cfa56623](https://linux-hardware.org/?probe=67cfa56623) | Jun 07, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [1dab354de2](https://linux-hardware.org/?probe=1dab354de2) | Jun 07, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | Desktop     | [1196dd3b41](https://linux-hardware.org/?probe=1196dd3b41) | Jun 06, 2022 |
| Gigabyte      | Z690 AORUS PRO DDR4         | Desktop     | [15efe8a0a2](https://linux-hardware.org/?probe=15efe8a0a2) | Jun 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [4ab9f94abe](https://linux-hardware.org/?probe=4ab9f94abe) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | Notebook    | [d98f987b46](https://linux-hardware.org/?probe=d98f987b46) | Jun 06, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [8f496dbb19](https://linux-hardware.org/?probe=8f496dbb19) | Jun 06, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2KW1... | Notebook    | [686fcbebd3](https://linux-hardware.org/?probe=686fcbebd3) | Jun 06, 2022 |
| Lenovo        | Yoga710-14ISK 80TY          | Notebook    | [116abb675e](https://linux-hardware.org/?probe=116abb675e) | Jun 06, 2022 |
| Lenovo        | ThinkPad Edge E531 6885C... | Notebook    | [1b09ad54c8](https://linux-hardware.org/?probe=1b09ad54c8) | Jun 05, 2022 |
| Acer          | Veriton N4670G              | Desktop     | [0b85f95c4c](https://linux-hardware.org/?probe=0b85f95c4c) | Jun 05, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3b4483236d](https://linux-hardware.org/?probe=3b4483236d) | Jun 05, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [9207d2f2d8](https://linux-hardware.org/?probe=9207d2f2d8) | Jun 04, 2022 |
| Intel         | NUC5i5RYB H40999-503        | Mini pc     | [a77acb5d89](https://linux-hardware.org/?probe=a77acb5d89) | Jun 04, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [57e7433cc5](https://linux-hardware.org/?probe=57e7433cc5) | Jun 04, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4bbee9909a](https://linux-hardware.org/?probe=4bbee9909a) | Jun 04, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [f770ece55b](https://linux-hardware.org/?probe=f770ece55b) | Jun 03, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [24c8a035ac](https://linux-hardware.org/?probe=24c8a035ac) | Jun 03, 2022 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | Notebook    | [b5bb3c0725](https://linux-hardware.org/?probe=b5bb3c0725) | Jun 02, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [86902cb11f](https://linux-hardware.org/?probe=86902cb11f) | Jun 02, 2022 |
| Dell          | G15 5515                    | Notebook    | [24ddbd70dc](https://linux-hardware.org/?probe=24ddbd70dc) | Jun 02, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0ddfd77617](https://linux-hardware.org/?probe=0ddfd77617) | Jun 02, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [878274dbce](https://linux-hardware.org/?probe=878274dbce) | Jun 02, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [b63e54900e](https://linux-hardware.org/?probe=b63e54900e) | Jun 02, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9cbdc3f892](https://linux-hardware.org/?probe=9cbdc3f892) | Jun 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ae39e96b1a](https://linux-hardware.org/?probe=ae39e96b1a) | Jun 01, 2022 |
| Alienware     | 0XJKKD A00                  | Desktop     | [ae3a750f2e](https://linux-hardware.org/?probe=ae3a750f2e) | Jun 01, 2022 |
| HP            | 1632                        | Desktop     | [4f7993cf34](https://linux-hardware.org/?probe=4f7993cf34) | Jun 01, 2022 |
| HP            | 1632                        | Desktop     | [9e69c11025](https://linux-hardware.org/?probe=9e69c11025) | Jun 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 D... | Notebook    | [57f540db26](https://linux-hardware.org/?probe=57f540db26) | Jun 01, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [20de61bf9f](https://linux-hardware.org/?probe=20de61bf9f) | Jun 01, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [0faa61f3a9](https://linux-hardware.org/?probe=0faa61f3a9) | May 31, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [9f5906337b](https://linux-hardware.org/?probe=9f5906337b) | May 31, 2022 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [ec75dd8324](https://linux-hardware.org/?probe=ec75dd8324) | May 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [02b32c935c](https://linux-hardware.org/?probe=02b32c935c) | May 31, 2022 |
| IT Channel... | PA70Hx                      | Notebook    | [091ad22c2d](https://linux-hardware.org/?probe=091ad22c2d) | May 30, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [33ac99c04e](https://linux-hardware.org/?probe=33ac99c04e) | May 30, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [3bb74db496](https://linux-hardware.org/?probe=3bb74db496) | May 30, 2022 |
| Dell          | 0C522T A03                  | Desktop     | [b1323f0c11](https://linux-hardware.org/?probe=b1323f0c11) | May 29, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [96cd8abf05](https://linux-hardware.org/?probe=96cd8abf05) | May 29, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [9c69f7b836](https://linux-hardware.org/?probe=9c69f7b836) | May 29, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [6fe2c4a416](https://linux-hardware.org/?probe=6fe2c4a416) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [e34608096b](https://linux-hardware.org/?probe=e34608096b) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [d21454c335](https://linux-hardware.org/?probe=d21454c335) | May 29, 2022 |
| MSI           | GT70 2OC/2OD                | Notebook    | [43144c3166](https://linux-hardware.org/?probe=43144c3166) | May 28, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [b810bd52cc](https://linux-hardware.org/?probe=b810bd52cc) | May 28, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [719fe6db76](https://linux-hardware.org/?probe=719fe6db76) | May 28, 2022 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [31f246f96e](https://linux-hardware.org/?probe=31f246f96e) | May 27, 2022 |
| Gigabyte      | B560M AORUS PRO             | Desktop     | [1d381d6ec9](https://linux-hardware.org/?probe=1d381d6ec9) | May 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6e7b6eddea](https://linux-hardware.org/?probe=6e7b6eddea) | May 27, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [37d87b9245](https://linux-hardware.org/?probe=37d87b9245) | May 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [3302c5de16](https://linux-hardware.org/?probe=3302c5de16) | May 27, 2022 |
| HP            | 0AECh D                     | Desktop     | [ee3f56c60e](https://linux-hardware.org/?probe=ee3f56c60e) | May 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [9011cf0a9b](https://linux-hardware.org/?probe=9011cf0a9b) | May 27, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [ac41fb756c](https://linux-hardware.org/?probe=ac41fb756c) | May 26, 2022 |
| Acer          | Seawolf                     | Desktop     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| Toshiba       | Satellite P850              | Notebook    | [9ec49310ff](https://linux-hardware.org/?probe=9ec49310ff) | May 25, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [18427eddde](https://linux-hardware.org/?probe=18427eddde) | May 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [4738560555](https://linux-hardware.org/?probe=4738560555) | May 25, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [89927eb8f5](https://linux-hardware.org/?probe=89927eb8f5) | May 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [6e45ae9f7c](https://linux-hardware.org/?probe=6e45ae9f7c) | May 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [00baf8a2ff](https://linux-hardware.org/?probe=00baf8a2ff) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [32f7f3aa4b](https://linux-hardware.org/?probe=32f7f3aa4b) | May 24, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [4ea6883bee](https://linux-hardware.org/?probe=4ea6883bee) | May 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [43a374c1d4](https://linux-hardware.org/?probe=43a374c1d4) | May 23, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [293712cc51](https://linux-hardware.org/?probe=293712cc51) | May 23, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [40d33cea3f](https://linux-hardware.org/?probe=40d33cea3f) | May 23, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [1d8684d1f5](https://linux-hardware.org/?probe=1d8684d1f5) | May 23, 2022 |
| Gigabyte      | P34V5                       | Notebook    | [6fa844b91e](https://linux-hardware.org/?probe=6fa844b91e) | May 23, 2022 |
| Gigabyte      | P34V5                       | Notebook    | [3ad8e4b239](https://linux-hardware.org/?probe=3ad8e4b239) | May 23, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [192f2ac212](https://linux-hardware.org/?probe=192f2ac212) | May 23, 2022 |
| Toshiba       | TECRA R850                  | Notebook    | [aa0bfd6c6a](https://linux-hardware.org/?probe=aa0bfd6c6a) | May 22, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [0ea1ce7372](https://linux-hardware.org/?probe=0ea1ce7372) | May 22, 2022 |
| Dell          | G3 3500                     | Notebook    | [49f86cc226](https://linux-hardware.org/?probe=49f86cc226) | May 22, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [eaf9e6332b](https://linux-hardware.org/?probe=eaf9e6332b) | May 21, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [890010e793](https://linux-hardware.org/?probe=890010e793) | May 21, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [81360dffcc](https://linux-hardware.org/?probe=81360dffcc) | May 21, 2022 |
| HP            | 0A08h                       | Desktop     | [86c65b6b1f](https://linux-hardware.org/?probe=86c65b6b1f) | May 21, 2022 |
| HP            | 0A08h                       | Desktop     | [18b2ce1297](https://linux-hardware.org/?probe=18b2ce1297) | May 21, 2022 |
| Unknown       | Unknown                     | Soc         | [3028420085](https://linux-hardware.org/?probe=3028420085) | May 20, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [acbead429c](https://linux-hardware.org/?probe=acbead429c) | May 20, 2022 |
| HP            | 8053                        | Desktop     | [53c0148d64](https://linux-hardware.org/?probe=53c0148d64) | May 20, 2022 |
| ECS           | P67H2-A3                    | Desktop     | [2bc21b9c81](https://linux-hardware.org/?probe=2bc21b9c81) | May 20, 2022 |
| HP            | 8381 1000                   | All in one  | [04684aee01](https://linux-hardware.org/?probe=04684aee01) | May 19, 2022 |
| HP            | 8381 1000                   | All in one  | [57e63582bf](https://linux-hardware.org/?probe=57e63582bf) | May 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [d94f4b0a43](https://linux-hardware.org/?probe=d94f4b0a43) | May 19, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | Notebook    | [5d150789cb](https://linux-hardware.org/?probe=5d150789cb) | May 19, 2022 |
| Dell          | Inspiron 7572               | Notebook    | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [c3438d922b](https://linux-hardware.org/?probe=c3438d922b) | May 19, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [98752f9fb4](https://linux-hardware.org/?probe=98752f9fb4) | May 18, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [c01f14c77f](https://linux-hardware.org/?probe=c01f14c77f) | May 18, 2022 |
| Dell          | Latitude E7450              | Notebook    | [26b07c8dfc](https://linux-hardware.org/?probe=26b07c8dfc) | May 18, 2022 |
| Gigabyte      | AX370M-DS3H-CF              | Desktop     | [2f7a99c28b](https://linux-hardware.org/?probe=2f7a99c28b) | May 17, 2022 |
| Toshiba       | Satellite C850              | Notebook    | [5927aac0b7](https://linux-hardware.org/?probe=5927aac0b7) | May 17, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [ee4e4a7bc7](https://linux-hardware.org/?probe=ee4e4a7bc7) | May 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d4f9f894b6](https://linux-hardware.org/?probe=d4f9f894b6) | May 16, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [faf97fa9a0](https://linux-hardware.org/?probe=faf97fa9a0) | May 16, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [c831b3937a](https://linux-hardware.org/?probe=c831b3937a) | May 16, 2022 |
| Gigabyte      | MQLP7AP-00                  | Desktop     | [3c99b8d861](https://linux-hardware.org/?probe=3c99b8d861) | May 16, 2022 |
| Gigabyte      | A7 K1                       | Notebook    | [9cd1ec32e4](https://linux-hardware.org/?probe=9cd1ec32e4) | May 16, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [a58685906f](https://linux-hardware.org/?probe=a58685906f) | May 15, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [655afd62e6](https://linux-hardware.org/?probe=655afd62e6) | May 14, 2022 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [9161d40357](https://linux-hardware.org/?probe=9161d40357) | May 14, 2022 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [e34d9464b2](https://linux-hardware.org/?probe=e34d9464b2) | May 14, 2022 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [45a26a9322](https://linux-hardware.org/?probe=45a26a9322) | May 14, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [04f0e074cb](https://linux-hardware.org/?probe=04f0e074cb) | May 14, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [3a07cc7daf](https://linux-hardware.org/?probe=3a07cc7daf) | May 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [91730625e9](https://linux-hardware.org/?probe=91730625e9) | May 14, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [b31c3ee2d6](https://linux-hardware.org/?probe=b31c3ee2d6) | May 14, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [210d27dd90](https://linux-hardware.org/?probe=210d27dd90) | May 14, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [30a7bebcd3](https://linux-hardware.org/?probe=30a7bebcd3) | May 14, 2022 |
| HP            | 82B4                        | Desktop     | [3a1723a2ee](https://linux-hardware.org/?probe=3a1723a2ee) | May 13, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [78c64b498b](https://linux-hardware.org/?probe=78c64b498b) | May 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [6251446c92](https://linux-hardware.org/?probe=6251446c92) | May 13, 2022 |
| Intel         | DH67BL AAG10189-210         | Desktop     | [2340d530cd](https://linux-hardware.org/?probe=2340d530cd) | May 13, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [fca86a854a](https://linux-hardware.org/?probe=fca86a854a) | May 13, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [602289ad13](https://linux-hardware.org/?probe=602289ad13) | May 13, 2022 |
| Dell          | Inspiron 15 3515            | Notebook    | [dd8e112250](https://linux-hardware.org/?probe=dd8e112250) | May 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [05b277774e](https://linux-hardware.org/?probe=05b277774e) | May 12, 2022 |
| HP            | 8526 MVB, A                 | Desktop     | [50b2aa8de2](https://linux-hardware.org/?probe=50b2aa8de2) | May 12, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [d2b843c446](https://linux-hardware.org/?probe=d2b843c446) | May 12, 2022 |
| HP            | Pavilion g6                 | Notebook    | [5662b515c3](https://linux-hardware.org/?probe=5662b515c3) | May 12, 2022 |
| Acer          | Aspire V5-573G              | Notebook    | [4477112f3a](https://linux-hardware.org/?probe=4477112f3a) | May 11, 2022 |
| Acer          | Aspire X3990                | Desktop     | [c6753ff37f](https://linux-hardware.org/?probe=c6753ff37f) | May 11, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | Notebook    | [a22c347eaf](https://linux-hardware.org/?probe=a22c347eaf) | May 11, 2022 |
| Lenovo        | Yoga 720-13IKB 80X6         | Convertible | [9797dc24f1](https://linux-hardware.org/?probe=9797dc24f1) | May 11, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [f2f010a36d](https://linux-hardware.org/?probe=f2f010a36d) | May 11, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [0d9616886e](https://linux-hardware.org/?probe=0d9616886e) | May 11, 2022 |
| MSI           | H97M-E35                    | Desktop     | [fdd0f51b46](https://linux-hardware.org/?probe=fdd0f51b46) | May 10, 2022 |
| Gigabyte      | H370M D3H-CF                | Desktop     | [ffc3d3cf27](https://linux-hardware.org/?probe=ffc3d3cf27) | May 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [ce3addb8a4](https://linux-hardware.org/?probe=ce3addb8a4) | May 10, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [7d146e5dec](https://linux-hardware.org/?probe=7d146e5dec) | May 10, 2022 |
| ASRock        | H87M                        | Desktop     | [9c031f1e71](https://linux-hardware.org/?probe=9c031f1e71) | May 09, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [89f0b017b1](https://linux-hardware.org/?probe=89f0b017b1) | May 09, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [bd7335e1cd](https://linux-hardware.org/?probe=bd7335e1cd) | May 09, 2022 |
| Acer          | Aspire XC-603               | Desktop     | [3d806cb212](https://linux-hardware.org/?probe=3d806cb212) | May 08, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [7ff6997105](https://linux-hardware.org/?probe=7ff6997105) | May 08, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [0d213120b4](https://linux-hardware.org/?probe=0d213120b4) | May 08, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [9d27bd494e](https://linux-hardware.org/?probe=9d27bd494e) | May 08, 2022 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [e4340f1707](https://linux-hardware.org/?probe=e4340f1707) | May 07, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [3d921b618b](https://linux-hardware.org/?probe=3d921b618b) | May 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [5c5f2f2b5c](https://linux-hardware.org/?probe=5c5f2f2b5c) | May 07, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [79c87fe48c](https://linux-hardware.org/?probe=79c87fe48c) | May 07, 2022 |
| MSI           | C236A WORKSTATION           | Desktop     | [57d0654584](https://linux-hardware.org/?probe=57d0654584) | May 06, 2022 |
| HP            | Folio 13 - 2000             | Notebook    | [e859aed666](https://linux-hardware.org/?probe=e859aed666) | May 06, 2022 |
| ASRock        | AD2700-ITX                  | Desktop     | [c44c5e8931](https://linux-hardware.org/?probe=c44c5e8931) | May 06, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [f99b5cee66](https://linux-hardware.org/?probe=f99b5cee66) | May 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [3d07e8a45e](https://linux-hardware.org/?probe=3d07e8a45e) | May 05, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [46adc67882](https://linux-hardware.org/?probe=46adc67882) | May 05, 2022 |
| Dell          | Studio 1555                 | Notebook    | [c02949a388](https://linux-hardware.org/?probe=c02949a388) | May 05, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [3ed5a6d961](https://linux-hardware.org/?probe=3ed5a6d961) | May 04, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [2b6338d755](https://linux-hardware.org/?probe=2b6338d755) | May 04, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [ba7fe58d02](https://linux-hardware.org/?probe=ba7fe58d02) | May 03, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | Notebook    | [43dcfa4094](https://linux-hardware.org/?probe=43dcfa4094) | May 03, 2022 |
| Dell          | 0NC2VH A01                  | Desktop     | [f05a6e7d31](https://linux-hardware.org/?probe=f05a6e7d31) | May 03, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [9645231d87](https://linux-hardware.org/?probe=9645231d87) | May 03, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [c6da7b776e](https://linux-hardware.org/?probe=c6da7b776e) | May 03, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1d6bcd7320](https://linux-hardware.org/?probe=1d6bcd7320) | May 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [8e220517f5](https://linux-hardware.org/?probe=8e220517f5) | May 02, 2022 |
| Framework     | Laptop                      | Notebook    | [0d35134041](https://linux-hardware.org/?probe=0d35134041) | May 02, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [0e6717d54b](https://linux-hardware.org/?probe=0e6717d54b) | May 02, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [579cadce96](https://linux-hardware.org/?probe=579cadce96) | May 02, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [42067d196a](https://linux-hardware.org/?probe=42067d196a) | May 02, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [ab86c0118b](https://linux-hardware.org/?probe=ab86c0118b) | May 02, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [6203143b59](https://linux-hardware.org/?probe=6203143b59) | May 02, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [7206b41211](https://linux-hardware.org/?probe=7206b41211) | May 01, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c396021a33](https://linux-hardware.org/?probe=c396021a33) | May 01, 2022 |
| Lenovo        | Legion Y9000X 2020 81TH     | Notebook    | [c335cbb270](https://linux-hardware.org/?probe=c335cbb270) | May 01, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [faa7213f5c](https://linux-hardware.org/?probe=faa7213f5c) | Apr 30, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [8826e1d451](https://linux-hardware.org/?probe=8826e1d451) | Apr 30, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [f948921cba](https://linux-hardware.org/?probe=f948921cba) | Apr 30, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [71fee7e383](https://linux-hardware.org/?probe=71fee7e383) | Apr 29, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [6755ed2aa6](https://linux-hardware.org/?probe=6755ed2aa6) | Apr 29, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [64cb392628](https://linux-hardware.org/?probe=64cb392628) | Apr 28, 2022 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [1f26415f58](https://linux-hardware.org/?probe=1f26415f58) | Apr 28, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [6165b0554d](https://linux-hardware.org/?probe=6165b0554d) | Apr 28, 2022 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [910da71dd2](https://linux-hardware.org/?probe=910da71dd2) | Apr 28, 2022 |
| ASUSTek       | VANGUARD B85                | Desktop     | [d591002039](https://linux-hardware.org/?probe=d591002039) | Apr 27, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [77c2b99e9b](https://linux-hardware.org/?probe=77c2b99e9b) | Apr 27, 2022 |
| Lenovo        | ThinkPad X250 20CLS52P0F    | Notebook    | [a4d291ccda](https://linux-hardware.org/?probe=a4d291ccda) | Apr 27, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [3a96bf8237](https://linux-hardware.org/?probe=3a96bf8237) | Apr 27, 2022 |
| Unknown       | Unknown                     | Soc         | [5937b60f18](https://linux-hardware.org/?probe=5937b60f18) | Apr 26, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [e06fd46729](https://linux-hardware.org/?probe=e06fd46729) | Apr 26, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [93c883ef59](https://linux-hardware.org/?probe=93c883ef59) | Apr 26, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [205ae74d07](https://linux-hardware.org/?probe=205ae74d07) | Apr 26, 2022 |
| HP            | ProBook 4710s               | Notebook    | [03d5c4c5b2](https://linux-hardware.org/?probe=03d5c4c5b2) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [981d5e03b3](https://linux-hardware.org/?probe=981d5e03b3) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0b3a1039fb](https://linux-hardware.org/?probe=0b3a1039fb) | Apr 25, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [973e161bd9](https://linux-hardware.org/?probe=973e161bd9) | Apr 25, 2022 |
| HP            | 0AACh                       | Desktop     | [f9e511945d](https://linux-hardware.org/?probe=f9e511945d) | Apr 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b1b4ea439d](https://linux-hardware.org/?probe=b1b4ea439d) | Apr 25, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [e0def5bddc](https://linux-hardware.org/?probe=e0def5bddc) | Apr 25, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [f0aea29124](https://linux-hardware.org/?probe=f0aea29124) | Apr 25, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [a771d771b2](https://linux-hardware.org/?probe=a771d771b2) | Apr 24, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [1a195527a4](https://linux-hardware.org/?probe=1a195527a4) | Apr 24, 2022 |
| Gigabyte      | H110M-S2PV-CF               | Desktop     | [d076b5c763](https://linux-hardware.org/?probe=d076b5c763) | Apr 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [fabaa5b3ab](https://linux-hardware.org/?probe=fabaa5b3ab) | Apr 24, 2022 |
| Dell          | Latitude E5500              | Notebook    | [c954cb4ba4](https://linux-hardware.org/?probe=c954cb4ba4) | Apr 24, 2022 |
| Dell          | Latitude E5500              | Notebook    | [ab88dc2482](https://linux-hardware.org/?probe=ab88dc2482) | Apr 24, 2022 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [e686789a94](https://linux-hardware.org/?probe=e686789a94) | Apr 24, 2022 |
| ASRock        | B85M Pro3                   | Desktop     | [551ea1b91f](https://linux-hardware.org/?probe=551ea1b91f) | Apr 23, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [2da43c32a4](https://linux-hardware.org/?probe=2da43c32a4) | Apr 23, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [8ff97fd246](https://linux-hardware.org/?probe=8ff97fd246) | Apr 23, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [bfaeba4483](https://linux-hardware.org/?probe=bfaeba4483) | Apr 22, 2022 |
| Dell          | Latitude 7490               | Notebook    | [2b8d24f8ae](https://linux-hardware.org/?probe=2b8d24f8ae) | Apr 22, 2022 |
| HP            | EliteBook 2530p             | Notebook    | [a68c57ea30](https://linux-hardware.org/?probe=a68c57ea30) | Apr 22, 2022 |
| Lenovo        | Gardenia CRB SDK0J40709 ... | All in one  | [e8e0b5fd5d](https://linux-hardware.org/?probe=e8e0b5fd5d) | Apr 22, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [c32d394b3a](https://linux-hardware.org/?probe=c32d394b3a) | Apr 21, 2022 |
| MSI           | GS65 Stealth Thin 8RE       | Notebook    | [cbb3f353a5](https://linux-hardware.org/?probe=cbb3f353a5) | Apr 21, 2022 |
| Lenovo        | Gardenia CRB SDK0J40709 ... | All in one  | [df18833e16](https://linux-hardware.org/?probe=df18833e16) | Apr 21, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [fc1fd7355c](https://linux-hardware.org/?probe=fc1fd7355c) | Apr 21, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [1c54ba7a0c](https://linux-hardware.org/?probe=1c54ba7a0c) | Apr 21, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3e69787ee4](https://linux-hardware.org/?probe=3e69787ee4) | Apr 21, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [a6bd59cad3](https://linux-hardware.org/?probe=a6bd59cad3) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0V    | Notebook    | [d6bf3c27ef](https://linux-hardware.org/?probe=d6bf3c27ef) | Apr 20, 2022 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [7969fc986b](https://linux-hardware.org/?probe=7969fc986b) | Apr 20, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [350979cb0a](https://linux-hardware.org/?probe=350979cb0a) | Apr 19, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [80c38b1425](https://linux-hardware.org/?probe=80c38b1425) | Apr 19, 2022 |
| Unknown       | Unknown                     | Soc         | [290d2ba979](https://linux-hardware.org/?probe=290d2ba979) | Apr 19, 2022 |
| Timi          | A35S                        | Notebook    | [e7d8adf61f](https://linux-hardware.org/?probe=e7d8adf61f) | Apr 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [4c845dc459](https://linux-hardware.org/?probe=4c845dc459) | Apr 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [179b76718e](https://linux-hardware.org/?probe=179b76718e) | Apr 18, 2022 |
| Dell          | 0X9M3X A05                  | Desktop     | [f049c88dfe](https://linux-hardware.org/?probe=f049c88dfe) | Apr 18, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [170db82573](https://linux-hardware.org/?probe=170db82573) | Apr 18, 2022 |
| ASRock        | AD525PV3                    | Desktop     | [b5c71cfdef](https://linux-hardware.org/?probe=b5c71cfdef) | Apr 18, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [5cb8325ed4](https://linux-hardware.org/?probe=5cb8325ed4) | Apr 18, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [48f584f713](https://linux-hardware.org/?probe=48f584f713) | Apr 17, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [918fef81c3](https://linux-hardware.org/?probe=918fef81c3) | Apr 17, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [69fdb71a72](https://linux-hardware.org/?probe=69fdb71a72) | Apr 16, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [6e722019b4](https://linux-hardware.org/?probe=6e722019b4) | Apr 16, 2022 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [7c4882a4ef](https://linux-hardware.org/?probe=7c4882a4ef) | Apr 16, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [2bc3cb42bb](https://linux-hardware.org/?probe=2bc3cb42bb) | Apr 16, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [eeccee9c29](https://linux-hardware.org/?probe=eeccee9c29) | Apr 15, 2022 |
| Dell          | Inspiron 1012               | Notebook    | [4659a757bf](https://linux-hardware.org/?probe=4659a757bf) | Apr 15, 2022 |
| Dell          | Inspiron 1012               | Notebook    | [ebfcf670fc](https://linux-hardware.org/?probe=ebfcf670fc) | Apr 15, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | Notebook    | [c43bc1fcba](https://linux-hardware.org/?probe=c43bc1fcba) | Apr 15, 2022 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [568ce07bd0](https://linux-hardware.org/?probe=568ce07bd0) | Apr 15, 2022 |
| Dell          | Latitude E6530              | Notebook    | [d6f985e2ca](https://linux-hardware.org/?probe=d6f985e2ca) | Apr 15, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [2b32ed7311](https://linux-hardware.org/?probe=2b32ed7311) | Apr 14, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [bbd732b5ca](https://linux-hardware.org/?probe=bbd732b5ca) | Apr 14, 2022 |
| Intel         | S5520UR E22554-752          | Server      | [476430304c](https://linux-hardware.org/?probe=476430304c) | Apr 14, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [930c18b320](https://linux-hardware.org/?probe=930c18b320) | Apr 14, 2022 |
| Dell          | 0H7TGR A00                  | Desktop     | [70bdc97d85](https://linux-hardware.org/?probe=70bdc97d85) | Apr 14, 2022 |
| Dell          | 01J90F A09                  | Server      | [a42e535407](https://linux-hardware.org/?probe=a42e535407) | Apr 14, 2022 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [794fbc68d8](https://linux-hardware.org/?probe=794fbc68d8) | Apr 14, 2022 |
| HP            | ProLiant ML330 G6           | Desktop     | [a62736690a](https://linux-hardware.org/?probe=a62736690a) | Apr 14, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [43aa5ccd47](https://linux-hardware.org/?probe=43aa5ccd47) | Apr 14, 2022 |
| Dell          | Latitude E6230              | Notebook    | [19e2fe3c97](https://linux-hardware.org/?probe=19e2fe3c97) | Apr 14, 2022 |
| Dell          | Latitude 5590               | Notebook    | [c306b97fcd](https://linux-hardware.org/?probe=c306b97fcd) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 4291IU6       | Notebook    | [a4c2a2bff9](https://linux-hardware.org/?probe=a4c2a2bff9) | Apr 14, 2022 |
| Lenovo        | ThinkPad T430 2350BC6       | Notebook    | [c2ffb2a421](https://linux-hardware.org/?probe=c2ffb2a421) | Apr 14, 2022 |
| HP            | 805D                        | Desktop     | [56634964fb](https://linux-hardware.org/?probe=56634964fb) | Apr 13, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [4c5ccfbe60](https://linux-hardware.org/?probe=4c5ccfbe60) | Apr 12, 2022 |
| Acer          | Aspire Z5801                | All in one  | [b1f38ece1e](https://linux-hardware.org/?probe=b1f38ece1e) | Apr 12, 2022 |
| Lenovo        | ThinkCentre A55 8982A48     | Desktop     | [8de4cd1654](https://linux-hardware.org/?probe=8de4cd1654) | Apr 12, 2022 |
| ASUSTek       | PRIME X299-A                | Desktop     | [3cfaa62e07](https://linux-hardware.org/?probe=3cfaa62e07) | Apr 11, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [8cdc4f4558](https://linux-hardware.org/?probe=8cdc4f4558) | Apr 10, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [e4fc7cc2cc](https://linux-hardware.org/?probe=e4fc7cc2cc) | Apr 10, 2022 |
| ASUSTek       | H87M-PRO                    | Desktop     | [0d2b6aaa56](https://linux-hardware.org/?probe=0d2b6aaa56) | Apr 10, 2022 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [e890c4c2f7](https://linux-hardware.org/?probe=e890c4c2f7) | Apr 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [aa7db96c10](https://linux-hardware.org/?probe=aa7db96c10) | Apr 09, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [9a4f7c7381](https://linux-hardware.org/?probe=9a4f7c7381) | Apr 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [28b5efd5f1](https://linux-hardware.org/?probe=28b5efd5f1) | Apr 09, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [ce1ec01972](https://linux-hardware.org/?probe=ce1ec01972) | Apr 09, 2022 |
| ASUSTek       | P8H67-V                     | Desktop     | [a2ae5eb5b9](https://linux-hardware.org/?probe=a2ae5eb5b9) | Apr 09, 2022 |
| ASRock        | X299 Gaming K6              | Desktop     | [86fc074c1f](https://linux-hardware.org/?probe=86fc074c1f) | Apr 09, 2022 |
| ASUSTek       | H87M-PRO                    | Desktop     | [86b82467fd](https://linux-hardware.org/?probe=86b82467fd) | Apr 08, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [2e37b66578](https://linux-hardware.org/?probe=2e37b66578) | Apr 08, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [e7b1a0df67](https://linux-hardware.org/?probe=e7b1a0df67) | Apr 08, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO ... | Desktop     | [10458d0000](https://linux-hardware.org/?probe=10458d0000) | Apr 08, 2022 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [8ee23e0e96](https://linux-hardware.org/?probe=8ee23e0e96) | Apr 08, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [3524c0ef61](https://linux-hardware.org/?probe=3524c0ef61) | Apr 08, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [8ae799c372](https://linux-hardware.org/?probe=8ae799c372) | Apr 08, 2022 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [1592895310](https://linux-hardware.org/?probe=1592895310) | Apr 07, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [bc01cf4afc](https://linux-hardware.org/?probe=bc01cf4afc) | Apr 05, 2022 |
| HP            | Spectre 13-SMB Pro Ultra... | Notebook    | [c8a1f60191](https://linux-hardware.org/?probe=c8a1f60191) | Apr 05, 2022 |
| HP            | Pavilion g6                 | Notebook    | [a2d8dcb1bf](https://linux-hardware.org/?probe=a2d8dcb1bf) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [403a6830d9](https://linux-hardware.org/?probe=403a6830d9) | Apr 04, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [b51d99ad47](https://linux-hardware.org/?probe=b51d99ad47) | Apr 04, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [e12e7fdd89](https://linux-hardware.org/?probe=e12e7fdd89) | Apr 04, 2022 |
| Kogan         | KAL11C250SB                 | Notebook    | [ea426eda5e](https://linux-hardware.org/?probe=ea426eda5e) | Apr 03, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [a517bb6633](https://linux-hardware.org/?probe=a517bb6633) | Apr 03, 2022 |
| MSI           | A88XM-E35 V2                | Desktop     | [2366707e2c](https://linux-hardware.org/?probe=2366707e2c) | Apr 03, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [6154972f18](https://linux-hardware.org/?probe=6154972f18) | Apr 03, 2022 |
| ASUSTek       | P552LA                      | Notebook    | [94ef2678d5](https://linux-hardware.org/?probe=94ef2678d5) | Apr 03, 2022 |
| ASUSTek       | P552LA                      | Notebook    | [9166f15878](https://linux-hardware.org/?probe=9166f15878) | Apr 03, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [c5df2732a7](https://linux-hardware.org/?probe=c5df2732a7) | Apr 02, 2022 |
| ASRock        | B85M Pro3                   | Desktop     | [8d14068c4b](https://linux-hardware.org/?probe=8d14068c4b) | Apr 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [e94a772f2b](https://linux-hardware.org/?probe=e94a772f2b) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [3bcc5c9790](https://linux-hardware.org/?probe=3bcc5c9790) | Apr 02, 2022 |
| Lenovo        | ThinkPad T410s 2912BR7      | Notebook    | [04098ae404](https://linux-hardware.org/?probe=04098ae404) | Apr 02, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [348ccc5750](https://linux-hardware.org/?probe=348ccc5750) | Apr 01, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [32eabd9ac8](https://linux-hardware.org/?probe=32eabd9ac8) | Apr 01, 2022 |
| Toshiba       | TECRA M11                   | Notebook    | [c81e18c0f3](https://linux-hardware.org/?probe=c81e18c0f3) | Apr 01, 2022 |
| Acer          | Aspire Z24-880              | All in one  | [7df055cfac](https://linux-hardware.org/?probe=7df055cfac) | Apr 01, 2022 |
| Dell          | Precision 5540              | Notebook    | [d923ae2736](https://linux-hardware.org/?probe=d923ae2736) | Apr 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [39b70e2f99](https://linux-hardware.org/?probe=39b70e2f99) | Apr 01, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [0e27c2feb0](https://linux-hardware.org/?probe=0e27c2feb0) | Mar 31, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [55572b8a7e](https://linux-hardware.org/?probe=55572b8a7e) | Mar 31, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | Notebook    | [339d70da8c](https://linux-hardware.org/?probe=339d70da8c) | Mar 30, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [d5b2536b95](https://linux-hardware.org/?probe=d5b2536b95) | Mar 30, 2022 |
| Unknown       | Unknown                     | Soc         | [509d960112](https://linux-hardware.org/?probe=509d960112) | Mar 30, 2022 |
| Dell          | Studio 1555                 | Notebook    | [db9f06343c](https://linux-hardware.org/?probe=db9f06343c) | Mar 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [01f1ca7f9d](https://linux-hardware.org/?probe=01f1ca7f9d) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d299b01a23](https://linux-hardware.org/?probe=d299b01a23) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1b9e12b8fb](https://linux-hardware.org/?probe=1b9e12b8fb) | Mar 29, 2022 |
| Toshiba       | Satellite Radius L10W-C     | Notebook    | [fc18e171f3](https://linux-hardware.org/?probe=fc18e171f3) | Mar 29, 2022 |
| HP            | Notebook                    | Notebook    | [c53a6a41a2](https://linux-hardware.org/?probe=c53a6a41a2) | Mar 29, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [235c763f19](https://linux-hardware.org/?probe=235c763f19) | Mar 28, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [5c65461fe1](https://linux-hardware.org/?probe=5c65461fe1) | Mar 28, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [756231c2f0](https://linux-hardware.org/?probe=756231c2f0) | Mar 27, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [70413280df](https://linux-hardware.org/?probe=70413280df) | Mar 26, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [296d97246f](https://linux-hardware.org/?probe=296d97246f) | Mar 26, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [1272ec27ff](https://linux-hardware.org/?probe=1272ec27ff) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [33ae998152](https://linux-hardware.org/?probe=33ae998152) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [90242bb090](https://linux-hardware.org/?probe=90242bb090) | Mar 26, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [a9caf3d428](https://linux-hardware.org/?probe=a9caf3d428) | Mar 25, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [f3f6025791](https://linux-hardware.org/?probe=f3f6025791) | Mar 25, 2022 |
| ASRock        | B560M-HDV                   | Desktop     | [f54eafc909](https://linux-hardware.org/?probe=f54eafc909) | Mar 23, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [e7181d25ff](https://linux-hardware.org/?probe=e7181d25ff) | Mar 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [fc5cdc4595](https://linux-hardware.org/?probe=fc5cdc4595) | Mar 23, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [20f2d24112](https://linux-hardware.org/?probe=20f2d24112) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [64718709d1](https://linux-hardware.org/?probe=64718709d1) | Mar 23, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [f123e292b9](https://linux-hardware.org/?probe=f123e292b9) | Mar 23, 2022 |
| ASRock        | FM2A75M-DGS R2.0            | Desktop     | [35f8ba571f](https://linux-hardware.org/?probe=35f8ba571f) | Mar 22, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [57038c6fd7](https://linux-hardware.org/?probe=57038c6fd7) | Mar 21, 2022 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [f2fb8fc533](https://linux-hardware.org/?probe=f2fb8fc533) | Mar 21, 2022 |
| ASRock        | FM2A75M-DGS R2.0            | Desktop     | [db394898e7](https://linux-hardware.org/?probe=db394898e7) | Mar 20, 2022 |
| HP            | 1906                        | Desktop     | [5a67de9420](https://linux-hardware.org/?probe=5a67de9420) | Mar 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [fef247389a](https://linux-hardware.org/?probe=fef247389a) | Mar 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [7dcf73063d](https://linux-hardware.org/?probe=7dcf73063d) | Mar 19, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [7a933d9603](https://linux-hardware.org/?probe=7a933d9603) | Mar 19, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [05780b53fa](https://linux-hardware.org/?probe=05780b53fa) | Mar 19, 2022 |
| Raspberry ... | Raspberry Pi 3 Model A P... | Soc         | [4d8ff799cd](https://linux-hardware.org/?probe=4d8ff799cd) | Mar 18, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [191c15c66b](https://linux-hardware.org/?probe=191c15c66b) | Mar 18, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [3001c43eca](https://linux-hardware.org/?probe=3001c43eca) | Mar 18, 2022 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [207eca584c](https://linux-hardware.org/?probe=207eca584c) | Mar 17, 2022 |
| Toshiba       | TECRA M11                   | Notebook    | [34167a6878](https://linux-hardware.org/?probe=34167a6878) | Mar 17, 2022 |
| Intel         | NUC8i7HVB J68196-503        | Mini pc     | [690ba35870](https://linux-hardware.org/?probe=690ba35870) | Mar 17, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [24314627ac](https://linux-hardware.org/?probe=24314627ac) | Mar 16, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [cb51b4388f](https://linux-hardware.org/?probe=cb51b4388f) | Mar 16, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [7bdb7d2aeb](https://linux-hardware.org/?probe=7bdb7d2aeb) | Mar 16, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [dceb87e505](https://linux-hardware.org/?probe=dceb87e505) | Mar 16, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [34da0f3cdb](https://linux-hardware.org/?probe=34da0f3cdb) | Mar 16, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [3d7949b20c](https://linux-hardware.org/?probe=3d7949b20c) | Mar 16, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [84c03a7952](https://linux-hardware.org/?probe=84c03a7952) | Mar 16, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [f1f12206d5](https://linux-hardware.org/?probe=f1f12206d5) | Mar 15, 2022 |
| HP            | Pavilion g6                 | Notebook    | [378424911d](https://linux-hardware.org/?probe=378424911d) | Mar 15, 2022 |
| ASUSTek       | VANGUARD B85                | Desktop     | [26090e1618](https://linux-hardware.org/?probe=26090e1618) | Mar 15, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2efb1bd4db](https://linux-hardware.org/?probe=2efb1bd4db) | Mar 15, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [527b0d7066](https://linux-hardware.org/?probe=527b0d7066) | Mar 14, 2022 |
| Toshiba       | Satellite P850              | Notebook    | [0cd9132f27](https://linux-hardware.org/?probe=0cd9132f27) | Mar 14, 2022 |
| ASRock        | Z490 Phantom Gaming 4       | Desktop     | [1a1f571027](https://linux-hardware.org/?probe=1a1f571027) | Mar 14, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [7b54425ba2](https://linux-hardware.org/?probe=7b54425ba2) | Mar 13, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [4e85fcd677](https://linux-hardware.org/?probe=4e85fcd677) | Mar 13, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [3e67ab27db](https://linux-hardware.org/?probe=3e67ab27db) | Mar 13, 2022 |
| Lenovo        | ThinkCentre M71e 3132B7M    | Desktop     | [fe771db462](https://linux-hardware.org/?probe=fe771db462) | Mar 13, 2022 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [ed5eba97e9](https://linux-hardware.org/?probe=ed5eba97e9) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [ab25401c99](https://linux-hardware.org/?probe=ab25401c99) | Mar 12, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [a93650d1a2](https://linux-hardware.org/?probe=a93650d1a2) | Mar 12, 2022 |
| ASRock        | B560M-HDV                   | Desktop     | [45e9c424b0](https://linux-hardware.org/?probe=45e9c424b0) | Mar 12, 2022 |
| Dell          | 0M863N A01                  | Desktop     | [b8bdf93d55](https://linux-hardware.org/?probe=b8bdf93d55) | Mar 12, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [639e7361ef](https://linux-hardware.org/?probe=639e7361ef) | Mar 12, 2022 |
| Dell          | Latitude E5450              | Notebook    | [3d2d8b93fe](https://linux-hardware.org/?probe=3d2d8b93fe) | Mar 12, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [36aa2f932e](https://linux-hardware.org/?probe=36aa2f932e) | Mar 12, 2022 |
| Metabox       | Edge-Pro NS50MU             | Notebook    | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| HP            | 3647h                       | Desktop     | [fd6766aabb](https://linux-hardware.org/?probe=fd6766aabb) | Mar 11, 2022 |
| Lenovo        | ThinkPad T480 20L5A07TAU    | Notebook    | [755854f7d4](https://linux-hardware.org/?probe=755854f7d4) | Mar 11, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [f486888101](https://linux-hardware.org/?probe=f486888101) | Mar 10, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b979165379](https://linux-hardware.org/?probe=b979165379) | Mar 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [4f65353f3e](https://linux-hardware.org/?probe=4f65353f3e) | Mar 10, 2022 |
| Gigabyte      | HA65M-D2H-B3                | Desktop     | [313e83e0ef](https://linux-hardware.org/?probe=313e83e0ef) | Mar 10, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [89ef99bd01](https://linux-hardware.org/?probe=89ef99bd01) | Mar 09, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | Notebook    | [a83a1ffe1a](https://linux-hardware.org/?probe=a83a1ffe1a) | Mar 09, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [d55f23484e](https://linux-hardware.org/?probe=d55f23484e) | Mar 09, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [7eea4038f0](https://linux-hardware.org/?probe=7eea4038f0) | Mar 09, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [fe3e35f15b](https://linux-hardware.org/?probe=fe3e35f15b) | Mar 09, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [97bb5e5628](https://linux-hardware.org/?probe=97bb5e5628) | Mar 08, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [a27291e807](https://linux-hardware.org/?probe=a27291e807) | Mar 08, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [5fb0149650](https://linux-hardware.org/?probe=5fb0149650) | Mar 08, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [b227e92b83](https://linux-hardware.org/?probe=b227e92b83) | Mar 07, 2022 |
| Apple         | MacBookPro6,1               | Notebook    | [ef72c023ac](https://linux-hardware.org/?probe=ef72c023ac) | Mar 07, 2022 |
| Toshiba       | Satellite Radius L10W-C     | Notebook    | [db90921ddd](https://linux-hardware.org/?probe=db90921ddd) | Mar 07, 2022 |
| HP            | ENVY TS 15                  | Notebook    | [c2305ed449](https://linux-hardware.org/?probe=c2305ed449) | Mar 06, 2022 |
| Gigabyte      | H110M-S2PV-CF               | Desktop     | [87bffb084f](https://linux-hardware.org/?probe=87bffb084f) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [2d5c05af33](https://linux-hardware.org/?probe=2d5c05af33) | Mar 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [aff575b483](https://linux-hardware.org/?probe=aff575b483) | Mar 05, 2022 |
| HP            | Notebook                    | Notebook    | [d8b2e4567e](https://linux-hardware.org/?probe=d8b2e4567e) | Mar 05, 2022 |
| HP            | Notebook                    | Notebook    | [cafa2c6f1a](https://linux-hardware.org/?probe=cafa2c6f1a) | Mar 05, 2022 |
| ASUSTek       | H87M-PRO                    | Desktop     | [99effa6921](https://linux-hardware.org/?probe=99effa6921) | Mar 05, 2022 |
| HP            | 2187 A01                    | Desktop     | [fa0949ca91](https://linux-hardware.org/?probe=fa0949ca91) | Mar 05, 2022 |
| HP            | 802E                        | Desktop     | [14c73a40e0](https://linux-hardware.org/?probe=14c73a40e0) | Mar 05, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [9b130dbcb5](https://linux-hardware.org/?probe=9b130dbcb5) | Mar 04, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [98d5649b75](https://linux-hardware.org/?probe=98d5649b75) | Mar 03, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ef4029185f](https://linux-hardware.org/?probe=ef4029185f) | Mar 03, 2022 |
| ASRock        | X470 Gaming K4              | Desktop     | [a5070f4f7a](https://linux-hardware.org/?probe=a5070f4f7a) | Mar 03, 2022 |
| Gigabyte      | B560M GAMING HD             | Desktop     | [e9ed858ae7](https://linux-hardware.org/?probe=e9ed858ae7) | Mar 03, 2022 |
| Acer          | Aspire V3-371               | Notebook    | [038cc99ead](https://linux-hardware.org/?probe=038cc99ead) | Mar 02, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [daef2e33ab](https://linux-hardware.org/?probe=daef2e33ab) | Mar 01, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [7a24cb7e43](https://linux-hardware.org/?probe=7a24cb7e43) | Feb 28, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [0da8223b4e](https://linux-hardware.org/?probe=0da8223b4e) | Feb 28, 2022 |
| Gigabyte      | GA-990FXA-D3                | Desktop     | [67943c7786](https://linux-hardware.org/?probe=67943c7786) | Feb 27, 2022 |
| Gigabyte      | GA-990FXA-D3                | Desktop     | [badbd8817c](https://linux-hardware.org/?probe=badbd8817c) | Feb 27, 2022 |
| Acer          | Aspire U5-620               | All in one  | [5114fbe445](https://linux-hardware.org/?probe=5114fbe445) | Feb 26, 2022 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [66c0fc8423](https://linux-hardware.org/?probe=66c0fc8423) | Feb 26, 2022 |
| Acer          | Aspire U5-620               | All in one  | [271e991a95](https://linux-hardware.org/?probe=271e991a95) | Feb 26, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [678e1eb19b](https://linux-hardware.org/?probe=678e1eb19b) | Feb 26, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [e6ee79f80e](https://linux-hardware.org/?probe=e6ee79f80e) | Feb 25, 2022 |
| HP            | 870C                        | Desktop     | [619268c318](https://linux-hardware.org/?probe=619268c318) | Feb 25, 2022 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [7adb11305e](https://linux-hardware.org/?probe=7adb11305e) | Feb 25, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [f3ec55a392](https://linux-hardware.org/?probe=f3ec55a392) | Feb 25, 2022 |
| ASRock        | P55 Pro/USB3                | Desktop     | [a251cf49af](https://linux-hardware.org/?probe=a251cf49af) | Feb 24, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [1f26dfd88f](https://linux-hardware.org/?probe=1f26dfd88f) | Feb 22, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [b9cb7cad60](https://linux-hardware.org/?probe=b9cb7cad60) | Feb 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [03aa2b6723](https://linux-hardware.org/?probe=03aa2b6723) | Feb 21, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [c5079e020e](https://linux-hardware.org/?probe=c5079e020e) | Feb 21, 2022 |
| Gigabyte      | EP45-DS4                    | Desktop     | [a679fc7402](https://linux-hardware.org/?probe=a679fc7402) | Feb 21, 2022 |
| Dell          | Precision 3561              | Notebook    | [d46fbe1d5f](https://linux-hardware.org/?probe=d46fbe1d5f) | Feb 21, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [8a6f28fc9d](https://linux-hardware.org/?probe=8a6f28fc9d) | Feb 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [b75534890a](https://linux-hardware.org/?probe=b75534890a) | Feb 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [9130546637](https://linux-hardware.org/?probe=9130546637) | Feb 21, 2022 |
| Toshiba       | Satellite Pro C850          | Notebook    | [132557a51b](https://linux-hardware.org/?probe=132557a51b) | Feb 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [fb981fe5b0](https://linux-hardware.org/?probe=fb981fe5b0) | Feb 20, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [f08a9db4fb](https://linux-hardware.org/?probe=f08a9db4fb) | Feb 20, 2022 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [794369f273](https://linux-hardware.org/?probe=794369f273) | Feb 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [70de36a2bb](https://linux-hardware.org/?probe=70de36a2bb) | Feb 19, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [50b1c22625](https://linux-hardware.org/?probe=50b1c22625) | Feb 19, 2022 |
| HP            | Notebook                    | Notebook    | [1e57c317b4](https://linux-hardware.org/?probe=1e57c317b4) | Feb 19, 2022 |
| HP            | Notebook                    | Notebook    | [583b61ead6](https://linux-hardware.org/?probe=583b61ead6) | Feb 19, 2022 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [eb3ca47cd7](https://linux-hardware.org/?probe=eb3ca47cd7) | Feb 19, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [3d816cc71a](https://linux-hardware.org/?probe=3d816cc71a) | Feb 19, 2022 |
| IT Channel... | P95xER                      | Notebook    | [c8add471fb](https://linux-hardware.org/?probe=c8add471fb) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [f7e1ab4276](https://linux-hardware.org/?probe=f7e1ab4276) | Feb 18, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [fd7702ea67](https://linux-hardware.org/?probe=fd7702ea67) | Feb 18, 2022 |
| HP            | ProBook x360 435 G7         | Convertible | [0747de6777](https://linux-hardware.org/?probe=0747de6777) | Feb 18, 2022 |
| HP            | 0AACh                       | Desktop     | [5a45fe2b9b](https://linux-hardware.org/?probe=5a45fe2b9b) | Feb 18, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [0ef953e74d](https://linux-hardware.org/?probe=0ef953e74d) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [8791991562](https://linux-hardware.org/?probe=8791991562) | Feb 17, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [983c62bf72](https://linux-hardware.org/?probe=983c62bf72) | Feb 17, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Australia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 419       | 14.66%  |
| Ubuntu 18.04      | 172       | 6.02%   |
| Ubuntu 22.04      | 72        | 2.52%   |
| KDE neon 20.04    | 70        | 2.45%   |
| Debian 11         | 70        | 2.45%   |
| OpenMandriva 4.3  | 68        | 2.38%   |
| Pop!_OS 21.04     | 64        | 2.24%   |
| Fedora 36         | 59        | 2.06%   |
| Linux Mint 20.3   | 58        | 2.03%   |
| OpenMandriva 4.2  | 56        | 1.96%   |
| Zorin 16          | 50        | 1.75%   |
| Pop!_OS 20.04     | 50        | 1.75%   |
| Pop!_OS 22.04     | 48        | 1.68%   |
| Pop!_OS 20.10     | 48        | 1.68%   |
| Ubuntu 21.10      | 46        | 1.61%   |
| Linux Mint 20.2   | 46        | 1.61%   |
| Arch              | 44        | 1.54%   |
| Linux Mint 20.1   | 42        | 1.47%   |
| Fedora 35         | 42        | 1.47%   |
| Ubuntu 19.04      | 41        | 1.43%   |
| Fedora 33         | 41        | 1.43%   |
| Ubuntu 20.10      | 39        | 1.36%   |
| Fedora 34         | 38        | 1.33%   |
| Arch Rolling      | 38        | 1.33%   |
| Ubuntu 21.04      | 37        | 1.29%   |
| Ubuntu 19.10      | 37        | 1.29%   |
| Manjaro           | 37        | 1.29%   |
| Linux Mint 19.3   | 34        | 1.19%   |
| Linux Mint 20     | 32        | 1.12%   |
| Pop!_OS 21.10     | 30        | 1.05%   |
| ArcoLinux Rolling | 30        | 1.05%   |
| Fedora 32         | 29        | 1.01%   |
| Xubuntu 20.04     | 28        | 0.98%   |
| Xubuntu 18.04     | 28        | 0.98%   |
| Ubuntu 18.10      | 26        | 0.91%   |
| Zorin 15          | 24        | 0.84%   |
| ClearOS 7         | 23        | 0.8%    |
| Debian 10         | 21        | 0.73%   |
| Fedora 31         | 19        | 0.66%   |
| Kubuntu 20.04     | 17        | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 857       | 31.97%  |
| Linux Mint    | 243       | 9.06%   |
| Pop!_OS       | 227       | 8.47%   |
| Fedora        | 192       | 7.16%   |
| OpenMandriva  | 143       | 5.33%   |
| Debian        | 117       | 4.36%   |
| Zorin         | 83        | 3.1%    |
| Arch          | 82        | 3.06%   |
| Manjaro       | 81        | 3.02%   |
| KDE neon      | 81        | 3.02%   |
| Xubuntu       | 75        | 2.8%    |
| Kubuntu       | 55        | 2.05%   |
| ArcoLinux     | 31        | 1.16%   |
| Elementary    | 29        | 1.08%   |
| ROSA          | 28        | 1.04%   |
| Gentoo        | 26        | 0.97%   |
| Kali          | 24        | 0.9%    |
| ClearOS       | 23        | 0.86%   |
| Clear Linux   | 22        | 0.82%   |
| Ubuntu MATE   | 21        | 0.78%   |
| openSUSE      | 20        | 0.75%   |
| Lubuntu       | 18        | 0.67%   |
| Endless       | 17        | 0.63%   |
| BlackPanther  | 17        | 0.63%   |
| EndeavourOS   | 14        | 0.52%   |
| Ubuntu Unity  | 13        | 0.48%   |
| LMDE          | 12        | 0.45%   |
| CentOS        | 10        | 0.37%   |
| Ubuntu Budgie | 8         | 0.3%    |
| MX            | 8         | 0.3%    |
| Raspbian      | 7         | 0.26%   |
| LinuxFX       | 7         | 0.26%   |
| Feren OS      | 7         | 0.26%   |
| Reborn OS     | 6         | 0.22%   |
| Parrot        | 6         | 0.22%   |
| Solus         | 5         | 0.19%   |
| Rocky Linux   | 5         | 0.19%   |
| Manjaro-ARM   | 5         | 0.19%   |
| Garuda Linux  | 4         | 0.15%   |
| Ubuntu Studio | 3         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 65        | 1.96%   |
| 5.4.0-42-generic         | 64        | 1.93%   |
| 5.10.14-desktop-1omv4002 | 52        | 1.57%   |
| 5.4.0-40-generic         | 30        | 0.9%    |
| 5.11.0-7620-generic      | 30        | 0.9%    |
| 5.4.0-58-generic         | 29        | 0.87%   |
| 5.4.0-48-generic         | 27        | 0.81%   |
| 5.4.0-26-generic         | 24        | 0.72%   |
| 5.3.0-46-generic         | 24        | 0.72%   |
| 5.4.0-52-generic         | 23        | 0.69%   |
| 5.11.0-37-generic        | 23        | 0.69%   |
| 5.4.0-29-generic         | 22        | 0.66%   |
| 5.3.0-40-generic         | 22        | 0.66%   |
| 5.3.0-28-generic         | 22        | 0.66%   |
| 5.17.5-76051705-generic  | 21        | 0.63%   |
| 5.11.0-27-generic        | 20        | 0.6%    |
| 5.4.0-7634-generic       | 19        | 0.57%   |
| 5.15.0-48-generic        | 19        | 0.57%   |
| 5.4.0-47-generic         | 18        | 0.54%   |
| 5.15.0-46-generic        | 18        | 0.54%   |
| 5.4.0-74-generic         | 17        | 0.51%   |
| 5.13.0-7620-generic      | 17        | 0.51%   |
| 5.8.0-7630-generic       | 16        | 0.48%   |
| 5.8.0-44-generic         | 16        | 0.48%   |
| 5.4.0-91-generic         | 16        | 0.48%   |
| 5.4.0-65-generic         | 16        | 0.48%   |
| 5.13.0-40-generic        | 16        | 0.48%   |
| 4.15.0-99-generic        | 16        | 0.48%   |
| 5.8.0-7642-generic       | 15        | 0.45%   |
| 5.8.0-63-generic         | 15        | 0.45%   |
| 5.4.0-66-generic         | 15        | 0.45%   |
| 5.4.0-54-generic         | 15        | 0.45%   |
| 5.8.0-55-generic         | 14        | 0.42%   |
| 5.8.0-50-generic         | 14        | 0.42%   |
| 5.4.0-7642-generic       | 14        | 0.42%   |
| 5.13.0-39-generic        | 14        | 0.42%   |
| 5.13.0-30-generic        | 14        | 0.42%   |
| 5.11.0-34-generic        | 14        | 0.42%   |
| 5.11.0-25-generic        | 14        | 0.42%   |
| 5.0.0-13-generic         | 14        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 547       | 17.94%  |
| 5.11.0  | 228       | 7.48%   |
| 5.13.0  | 183       | 6%      |
| 5.8.0   | 180       | 5.9%    |
| 4.15.0  | 158       | 5.18%   |
| 5.15.0  | 140       | 4.59%   |
| 5.3.0   | 128       | 4.2%    |
| 5.0.0   | 86        | 2.82%   |
| 5.10.0  | 72        | 2.36%   |
| 5.16.7  | 66        | 2.16%   |
| 4.18.0  | 61        | 2%      |
| 5.10.14 | 52        | 1.71%   |
| 4.19.0  | 35        | 1.15%   |
| 5.17.5  | 31        | 1.02%   |
| 3.10.0  | 29        | 0.95%   |
| 5.19.0  | 19        | 0.62%   |
| 5.16.11 | 14        | 0.46%   |
| 5.18.10 | 13        | 0.43%   |
| 5.18.0  | 13        | 0.43%   |
| 5.16.0  | 13        | 0.43%   |
| 4.4.0   | 12        | 0.39%   |
| 5.17.0  | 11        | 0.36%   |
| 5.14.0  | 11        | 0.36%   |
| 5.9.16  | 10        | 0.33%   |
| 5.6.14  | 10        | 0.33%   |
| 5.18.12 | 10        | 0.33%   |
| 5.15.11 | 10        | 0.33%   |
| 5.13.13 | 10        | 0.33%   |
| 5.11.12 | 10        | 0.33%   |
| 4.9.60  | 10        | 0.33%   |
| 5.16.19 | 9         | 0.3%    |
| 5.13.12 | 9         | 0.3%    |
| 5.12.4  | 9         | 0.3%    |
| 4.18.16 | 9         | 0.3%    |
| 5.8.16  | 8         | 0.26%   |
| 5.7.0   | 8         | 0.26%   |
| 5.6.6   | 8         | 0.26%   |
| 5.3.18  | 8         | 0.26%   |
| 5.19.16 | 8         | 0.26%   |
| 5.17.15 | 8         | 0.26%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 597       | 20.16%  |
| 5.11    | 267       | 9.01%   |
| 5.13    | 229       | 7.73%   |
| 5.8     | 227       | 7.66%   |
| 5.15    | 227       | 7.66%   |
| 5.10    | 185       | 6.25%   |
| 4.15    | 158       | 5.33%   |
| 5.16    | 147       | 4.96%   |
| 5.3     | 143       | 4.83%   |
| 5.0     | 95        | 3.21%   |
| 5.17    | 83        | 2.8%    |
| 5.18    | 76        | 2.57%   |
| 4.18    | 72        | 2.43%   |
| 5.19    | 60        | 2.03%   |
| 5.12    | 46        | 1.55%   |
| 5.6     | 45        | 1.52%   |
| 4.19    | 45        | 1.52%   |
| 5.14    | 42        | 1.42%   |
| 5.9     | 38        | 1.28%   |
| 4.9     | 30        | 1.01%   |
| 3.10    | 29        | 0.98%   |
| 5.5     | 26        | 0.88%   |
| 5.7     | 25        | 0.84%   |
| 5.2     | 17        | 0.57%   |
| 4.4     | 13        | 0.44%   |
| 5.1     | 9         | 0.3%    |
| 6.0     | 8         | 0.27%   |
| 4.1     | 4         | 0.14%   |
| 4.20    | 3         | 0.1%    |
| 4.14    | 3         | 0.1%    |
| 4.13    | 3         | 0.1%    |
| 3.16    | 2         | 0.07%   |
| 5       | 1         | 0.03%   |
| 4.8     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 4.16    | 1         | 0.03%   |
| 4.11    | 1         | 0.03%   |
| 4.10    | 1         | 0.03%   |
| 3.9     | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2466      | 96.48%  |
| i686    | 47        | 1.84%   |
| aarch64 | 28        | 1.1%    |
| armv7l  | 11        | 0.43%   |
| i586    | 2         | 0.08%   |
| riscv64 | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1188      | 43.92%  |
| KDE5            | 374       | 13.83%  |
| Unknown         | 362       | 13.38%  |
| X-Cinnamon      | 204       | 7.54%   |
| XFCE            | 187       | 6.91%   |
| KDE             | 100       | 3.7%    |
| MATE            | 72        | 2.66%   |
| Cinnamon        | 48        | 1.77%   |
| Pantheon        | 27        | 1%      |
| LXQt            | 20        | 0.74%   |
| Unity           | 18        | 0.67%   |
| KDE4            | 18        | 0.67%   |
| LXDE            | 16        | 0.59%   |
| Budgie          | 16        | 0.59%   |
| i3              | 13        | 0.48%   |
| Deepin          | 7         | 0.26%   |
| awesome         | 7         | 0.26%   |
| Openbox         | 6         | 0.22%   |
| GNOME Flashback | 4         | 0.15%   |
| GNOME Classic   | 4         | 0.15%   |
| xmonad          | 3         | 0.11%   |
| qtile           | 2         | 0.07%   |
| Trinity         | 1         | 0.04%   |
| sway            | 1         | 0.04%   |
| pop             | 1         | 0.04%   |
| Phosh:GNOME     | 1         | 0.04%   |
| icewm           | 1         | 0.04%   |
| GNUstep         | 1         | 0.04%   |
| DWM             | 1         | 0.04%   |
| dusk            | 1         | 0.04%   |
| bspwm           | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2089      | 78.98%  |
| Wayland | 299       | 11.3%   |
| Unknown | 162       | 6.12%   |
| Tty     | 94        | 3.55%   |
| Web     | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1517      | 57.07%  |
| SDDM    | 325       | 12.23%  |
| GDM     | 283       | 10.65%  |
| LightDM | 238       | 8.95%   |
| GDM3    | 175       | 6.58%   |
| TDM     | 85        | 3.2%    |
| KDM     | 17        | 0.64%   |
| SLiM    | 6         | 0.23%   |
| LXDM    | 5         | 0.19%   |
| XDM     | 4         | 0.15%   |
| Ly      | 2         | 0.08%   |
| GREETD  | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_AU   | 1871      | 70.82%  |
| en_US   | 354       | 13.4%   |
| Unknown | 317       | 12%     |
| C       | 60        | 2.27%   |
| en_GB   | 27        | 1.02%   |
| C.UTF8  | 5         | 0.19%   |
| zh_CN   | 2         | 0.08%   |
| ru_RU   | 1         | 0.04%   |
| POSIX   | 1         | 0.04%   |
| es_ES   | 1         | 0.04%   |
| en_IN   | 1         | 0.04%   |
| en_CA   | 1         | 0.04%   |
| de_DE   | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1380      | 52.81%  |
| EFI  | 1233      | 47.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2005      | 76.47%  |
| Btrfs   | 203       | 7.74%   |
| Overlay | 183       | 6.98%   |
| Unknown | 100       | 3.81%   |
| Xfs     | 72        | 2.75%   |
| Zfs     | 34        | 1.3%    |
| Ext2    | 8         | 0.31%   |
| Tmpfs   | 5         | 0.19%   |
| Ext3    | 5         | 0.19%   |
| XXXXXXX | 3         | 0.11%   |
| F2fs    | 2         | 0.08%   |
| Jfs     | 1         | 0.04%   |
| Aufs    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1593      | 61.03%  |
| GPT     | 747       | 28.62%  |
| MBR     | 270       | 10.34%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2202      | 84.34%  |
| Yes       | 409       | 15.66%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1908      | 73.13%  |
| Yes       | 701       | 26.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 370       | 14.51%  |
| Hewlett-Packard         | 345       | 13.53%  |
| Dell                    | 330       | 12.94%  |
| Gigabyte Technology     | 327       | 12.82%  |
| Lenovo                  | 259       | 10.16%  |
| MSI                     | 155       | 6.08%   |
| Acer                    | 128       | 5.02%   |
| Apple                   | 104       | 4.08%   |
| ASRock                  | 102       | 4%      |
| Toshiba                 | 89        | 3.49%   |
| Intel                   | 73        | 2.86%   |
| Raspberry Pi Foundation | 26        | 1.02%   |
| Microsoft               | 26        | 1.02%   |
| Alienware               | 19        | 0.75%   |
| Unknown                 | 15        | 0.59%   |
| Samsung Electronics     | 12        | 0.47%   |
| Sony                    | 10        | 0.39%   |
| Notebook                | 10        | 0.39%   |
| Timi                    | 8         | 0.31%   |
| AMI                     | 8         | 0.31%   |
| Pegatron                | 7         | 0.27%   |
| Medion                  | 7         | 0.27%   |
| IT Channel Pty          | 7         | 0.27%   |
| Panasonic               | 6         | 0.24%   |
| Metabox                 | 6         | 0.24%   |
| HUAWEI                  | 6         | 0.24%   |
| Google                  | 6         | 0.24%   |
| Supermicro              | 5         | 0.2%    |
| Pine Microsystems       | 5         | 0.2%    |
| Kogan                   | 5         | 0.2%    |
| ECS                     | 5         | 0.2%    |
| System76                | 4         | 0.16%   |
| Razer                   | 4         | 0.16%   |
| IBM                     | 4         | 0.16%   |
| Hardkernel              | 4         | 0.16%   |
| Shuttle                 | 3         | 0.12%   |
| LG Electronics          | 3         | 0.12%   |
| Purism                  | 2         | 0.08%   |
| IP3 Tech                | 2         | 0.08%   |
| Intel Client Systems    | 2         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| ASUS All Series               | 28        | 1.1%    |
| Dell OptiPlex 9020            | 22        | 0.86%   |
| Unknown                       | 19        | 0.75%   |
| HP Pavilion dv6               | 14        | 0.55%   |
| HP Pavilion g6                | 11        | 0.43%   |
| RPi Raspberry Pi              | 10        | 0.39%   |
| Gigabyte 970A-D3P             | 10        | 0.39%   |
| HP Notebook                   | 9         | 0.35%   |
| Apple iMac12,2                | 9         | 0.35%   |
| MSI MS-7B89                   | 8         | 0.31%   |
| HP Pavilion 15                | 8         | 0.31%   |
| MSI MS-7C37                   | 7         | 0.27%   |
| MSI MS-7817                   | 7         | 0.27%   |
| Dell OptiPlex 780             | 7         | 0.27%   |
| Apple MacBookPro9,2           | 7         | 0.27%   |
| MSI MS-7C84                   | 6         | 0.24%   |
| Gigabyte X58A-UD3R            | 6         | 0.24%   |
| Gigabyte B75M-D3H             | 6         | 0.24%   |
| Dell OptiPlex 9010            | 6         | 0.24%   |
| Apple MacBookPro10,1          | 6         | 0.24%   |
| Acer ConceptD CN315-71P       | 6         | 0.24%   |
| Gigabyte X570 AORUS PRO WIFI  | 5         | 0.2%    |
| Gigabyte GA-870A-UD3          | 5         | 0.2%    |
| Dell XPS 15 9560              | 5         | 0.2%    |
| Dell OptiPlex 3010            | 5         | 0.2%    |
| ASUS ROG CROSSHAIR VIII HERO  | 5         | 0.2%    |
| Apple MacBookPro8,1           | 5         | 0.2%    |
| Acer Aspire 5750G             | 5         | 0.2%    |
| Toshiba Satellite P750        | 4         | 0.16%   |
| Toshiba Satellite L850        | 4         | 0.16%   |
| Toshiba Satellite L500        | 4         | 0.16%   |
| Toshiba Satellite L50-A       | 4         | 0.16%   |
| MSI MS-7C02                   | 4         | 0.16%   |
| MSI MS-7B79                   | 4         | 0.16%   |
| MSI MS-7A38                   | 4         | 0.16%   |
| MSI MS-7A37                   | 4         | 0.16%   |
| Microsoft Surface Book 2      | 4         | 0.16%   |
| Lenovo IdeaPad 1 14IGL05 81VU | 4         | 0.16%   |
| Lenovo G50-45 80E3            | 4         | 0.16%   |
| Intel NUC11PAHi5              | 4         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 119       | 4.67%   |
| Acer Aspire            | 89        | 3.49%   |
| Dell OptiPlex          | 80        | 3.14%   |
| HP Pavilion            | 73        | 2.86%   |
| Toshiba Satellite      | 72        | 2.82%   |
| Dell Inspiron          | 66        | 2.59%   |
| Dell Latitude          | 65        | 2.55%   |
| ASUS PRIME             | 51        | 2%      |
| Dell XPS               | 49        | 1.92%   |
| ASUS ROG               | 47        | 1.84%   |
| HP EliteBook           | 46        | 1.8%    |
| HP Compaq              | 37        | 1.45%   |
| Dell Precision         | 34        | 1.33%   |
| Lenovo IdeaPad         | 30        | 1.18%   |
| Lenovo ThinkCentre     | 29        | 1.14%   |
| Lenovo Yoga            | 28        | 1.1%    |
| ASUS All               | 28        | 1.1%    |
| RPi Raspberry          | 26        | 1.02%   |
| Microsoft Surface      | 26        | 1.02%   |
| HP ProBook             | 26        | 1.02%   |
| ASUS TUF               | 23        | 0.9%    |
| HP ENVY                | 19        | 0.75%   |
| Unknown                | 19        | 0.75%   |
| Gigabyte X570          | 18        | 0.71%   |
| HP Laptop              | 17        | 0.67%   |
| Gigabyte B450          | 15        | 0.59%   |
| Dell Vostro            | 14        | 0.55%   |
| Gigabyte B450M         | 12        | 0.47%   |
| Apple iMac12           | 11        | 0.43%   |
| HP ProDesk             | 10        | 0.39%   |
| Gigabyte 970A-D3P      | 10        | 0.39%   |
| ASUS ZenBook           | 10        | 0.39%   |
| HP Notebook            | 9         | 0.35%   |
| Apple MacBookPro10     | 9         | 0.35%   |
| Acer Swift             | 9         | 0.35%   |
| Toshiba PORTEGE        | 8         | 0.31%   |
| MSI MS-7B89            | 8         | 0.31%   |
| HP Spectre             | 8         | 0.31%   |
| HP 250                 | 8         | 0.31%   |
| Gigabyte GA-78LMT-USB3 | 8         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 245       | 9.61%   |
| 2018    | 245       | 9.61%   |
| 2020    | 214       | 8.39%   |
| 2012    | 204       | 8%      |
| 2013    | 200       | 7.84%   |
| 2011    | 191       | 7.49%   |
| 2017    | 182       | 7.14%   |
| 2014    | 160       | 6.27%   |
| 2016    | 147       | 5.76%   |
| 2010    | 137       | 5.37%   |
| 2015    | 134       | 5.25%   |
| 2021    | 128       | 5.02%   |
| 2009    | 106       | 4.16%   |
| 2008    | 104       | 4.08%   |
| 2007    | 49        | 1.92%   |
| Unknown | 38        | 1.49%   |
| 2022    | 32        | 1.25%   |
| 2006    | 19        | 0.75%   |
| 2005    | 11        | 0.43%   |
| 2004    | 2         | 0.08%   |
| 2003    | 1         | 0.04%   |
| 2002    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 1161      | 45.53%  |
| Notebook       | 1093      | 42.86%  |
| Convertible    | 80        | 3.14%   |
| All in one     | 65        | 2.55%   |
| Mini pc        | 54        | 2.12%   |
| Tablet         | 39        | 1.53%   |
| System on chip | 33        | 1.29%   |
| Server         | 20        | 0.78%   |
| Phone          | 3         | 0.12%   |
| Stick pc       | 2         | 0.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2362      | 92.09%  |
| Enabled  | 203       | 7.91%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2539      | 99.57%  |
| Yes  | 11        | 0.43%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 642       | 24.59%  |
| 4.01-8.0        | 525       | 20.11%  |
| 8.01-16.0       | 445       | 17.04%  |
| 3.01-4.0        | 435       | 16.66%  |
| 32.01-64.0      | 309       | 11.83%  |
| 1.01-2.0        | 93        | 3.56%   |
| 64.01-256.0     | 82        | 3.14%   |
| 24.01-32.0      | 40        | 1.53%   |
| 2.01-3.0        | 18        | 0.69%   |
| 0.51-1.0        | 13        | 0.5%    |
| 0.01-0.5        | 6         | 0.23%   |
| More than 256.0 | 2         | 0.08%   |
| Unknown         | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1008      | 34.4%   |
| 2.01-3.0    | 736       | 25.12%  |
| 4.01-8.0    | 402       | 13.72%  |
| 3.01-4.0    | 360       | 12.29%  |
| 0.51-1.0    | 212       | 7.24%   |
| 8.01-16.0   | 133       | 4.54%   |
| 0.01-0.5    | 45        | 1.54%   |
| 16.01-24.0  | 22        | 0.75%   |
| 24.01-32.0  | 6         | 0.2%    |
| 64.01-256.0 | 2         | 0.07%   |
| 0           | 2         | 0.07%   |
| Unknown     | 2         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1453      | 53.97%  |
| 2       | 630       | 23.4%   |
| 3       | 273       | 10.14%  |
| 4       | 153       | 5.68%   |
| 5       | 68        | 2.53%   |
| 6       | 37        | 1.37%   |
| 0       | 29        | 1.08%   |
| 7       | 20        | 0.74%   |
| 8       | 14        | 0.52%   |
| 9       | 6         | 0.22%   |
| 10      | 3         | 0.11%   |
| 13      | 2         | 0.07%   |
| 36      | 1         | 0.04%   |
| 14      | 1         | 0.04%   |
| 11      | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1500      | 58.09%  |
| Yes       | 1082      | 41.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2231      | 87.32%  |
| No        | 324       | 12.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1869      | 72.47%  |
| No        | 710       | 27.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1432      | 55.27%  |
| No        | 1159      | 44.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Computers | Percent |
|-----------|-----------|---------|
| Australia | 2550      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sydney         | 719       | 26.15%  |
| Melbourne      | 503       | 18.29%  |
| Brisbane       | 386       | 14.04%  |
| Perth          | 230       | 8.36%   |
| Adelaide       | 165       | 6%      |
| Canberra       | 58        | 2.11%   |
| Wahroonga      | 39        | 1.42%   |
| Hobart         | 28        | 1.02%   |
| Launceston     | 21        | 0.76%   |
| Alexandria     | 19        | 0.69%   |
| Surry Hills    | 17        | 0.62%   |
| Lane Cove      | 11        | 0.4%    |
| Gold Coast     | 11        | 0.4%    |
| Geelong        | 11        | 0.4%    |
| Woolloongabba  | 10        | 0.36%   |
| Newcastle      | 10        | 0.36%   |
| Mitcham        | 10        | 0.36%   |
| Richmond       | 9         | 0.33%   |
| Central Coast  | 9         | 0.33%   |
| Brighton       | 9         | 0.33%   |
| Traralgon      | 8         | 0.29%   |
| Townsville     | 7         | 0.25%   |
| Southport      | 7         | 0.25%   |
| Parramatta     | 7         | 0.25%   |
| Artarmon       | 7         | 0.25%   |
| Wollongong     | 6         | 0.22%   |
| West End       | 6         | 0.22%   |
| Point Cook     | 6         | 0.22%   |
| North Sydney   | 6         | 0.22%   |
| Mount Waverley | 6         | 0.22%   |
| Mandurah       | 6         | 0.22%   |
| Macquarie Park | 6         | 0.22%   |
| Spring Field   | 5         | 0.18%   |
| Ringwood East  | 5         | 0.18%   |
| Northcote      | 5         | 0.18%   |
| Mascot         | 5         | 0.18%   |
| Hawthorn       | 5         | 0.18%   |
| Doncaster      | 5         | 0.18%   |
| Clifton Hill   | 5         | 0.18%   |
| Buderim        | 5         | 0.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 720       | 1281   | 18.4%   |
| Seagate                   | 686       | 1295   | 17.53%  |
| WDC                       | 633       | 1185   | 16.17%  |
| Toshiba                   | 207       | 295    | 5.29%   |
| Crucial                   | 200       | 301    | 5.11%   |
| Kingston                  | 177       | 231    | 4.52%   |
| Intel                     | 149       | 264    | 3.81%   |
| SanDisk                   | 147       | 193    | 3.76%   |
| Unknown                   | 146       | 221    | 3.73%   |
| Hitachi                   | 133       | 211    | 3.4%    |
| SK hynix                  | 78        | 95     | 1.99%   |
| HGST                      | 61        | 88     | 1.56%   |
| Apple                     | 57        | 74     | 1.46%   |
| Micron Technology         | 44        | 56     | 1.12%   |
| Phison                    | 34        | 52     | 0.87%   |
| Micron/Crucial Technology | 33        | 48     | 0.84%   |
| OCZ                       | 29        | 44     | 0.74%   |
| A-DATA Technology         | 26        | 35     | 0.66%   |
| KIOXIA                    | 25        | 27     | 0.64%   |
| SPCC                      | 21        | 27     | 0.54%   |
| Corsair                   | 17        | 29     | 0.43%   |
| LITEON                    | 16        | 24     | 0.41%   |
| JMicron Technology        | 15        | 18     | 0.38%   |
| LITEONIT                  | 14        | 19     | 0.36%   |
| Fujitsu                   | 14        | 18     | 0.36%   |
| KingSpec                  | 13        | 29     | 0.33%   |
| Patriot                   | 12        | 17     | 0.31%   |
| Transcend                 | 11        | 17     | 0.28%   |
| LaCie                     | 11        | 18     | 0.28%   |
| Maxtor                    | 9         | 11     | 0.23%   |
| Gigabyte Technology       | 9         | 12     | 0.23%   |
| ASMT                      | 9         | 15     | 0.23%   |
| Hewlett-Packard           | 8         | 12     | 0.2%    |
| Unknown                   | 8         | 9      | 0.2%    |
| Silicon Motion            | 7         | 17     | 0.18%   |
| Realtek Semiconductor     | 7         | 9      | 0.18%   |
| China                     | 7         | 9      | 0.18%   |
| XPG                       | 6         | 7      | 0.15%   |
| TO Exter                  | 6         | 6      | 0.15%   |
| OWC                       | 6         | 13     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB              | 51        | 1.13%   |
| Samsung SSD 850 EVO 250GB              | 41        | 0.9%    |
| Unknown MMC Card  32GB                 | 34        | 0.75%   |
| Samsung NVMe SSD Drive 1TB             | 32        | 0.71%   |
| Seagate ST500DM002-1BD142 500GB        | 30        | 0.66%   |
| Seagate Expansion Desk 8TB             | 30        | 0.66%   |
| Crucial CT240BX500SSD1 240GB           | 30        | 0.66%   |
| Seagate ST1000DM010-2EP102 1TB         | 29        | 0.64%   |
| Samsung SSD 850 EVO 500GB              | 29        | 0.64%   |
| Unknown MMC Card  64GB                 | 28        | 0.62%   |
| Samsung NVMe SSD Drive 512GB           | 28        | 0.62%   |
| Samsung NVMe SSD Drive 500GB           | 28        | 0.62%   |
| Seagate ST4000DM004-2CV104 4TB         | 26        | 0.57%   |
| Seagate ST2000DM008-2FR102 2TB         | 26        | 0.57%   |
| Seagate ST2000DM001-1ER164 2TB         | 26        | 0.57%   |
| Seagate Expansion 2TB                  | 26        | 0.57%   |
| Seagate ST3500418AS 500GB              | 23        | 0.51%   |
| Seagate ST2000DM001-1CH164 2TB         | 23        | 0.51%   |
| Kingston SA400S37240G 240GB SSD        | 23        | 0.51%   |
| Crucial CT480BX500SSD1 480GB           | 23        | 0.51%   |
| Samsung SSD 860 EVO 1TB                | 22        | 0.49%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 22        | 0.49%   |
| Toshiba MQ01ABD100 1TB                 | 21        | 0.46%   |
| Crucial CT500MX500SSD1 500GB           | 21        | 0.46%   |
| Crucial CT1000MX500SSD1 1TB            | 21        | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB         | 19        | 0.42%   |
| Samsung SSD 860 QVO 1TB                | 19        | 0.42%   |
| Kingston SV300S37A120G 120GB SSD       | 19        | 0.42%   |
| Kingston SA400S37120G 120GB SSD        | 19        | 0.42%   |
| Seagate ST31000528AS 1TB               | 18        | 0.4%    |
| Seagate ST2000DM006-2DM164 2TB         | 18        | 0.4%    |
| Seagate ST2000DL003-9VT166 2TB         | 18        | 0.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 18        | 0.4%    |
| Seagate ST1000DM003-1ER162 1TB         | 18        | 0.4%    |
| SanDisk NVMe SSD Drive 512GB           | 18        | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB         | 18        | 0.4%    |
| Intel NVMe SSD Drive 512GB             | 18        | 0.4%    |
| WDC WD20EARX-00PASB0 2TB               | 17        | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 16        | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB           | 16        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 674       | 1256   | 39.69%  |
| WDC                 | 516       | 980    | 30.39%  |
| Toshiba             | 145       | 217    | 8.54%   |
| Hitachi             | 133       | 211    | 7.83%   |
| Samsung Electronics | 88        | 192    | 5.18%   |
| HGST                | 59        | 86     | 3.47%   |
| Unknown             | 15        | 25     | 0.88%   |
| Apple               | 15        | 20     | 0.88%   |
| Fujitsu             | 13        | 17     | 0.77%   |
| Maxtor              | 9         | 11     | 0.53%   |
| LaCie               | 9         | 15     | 0.53%   |
| ASMT                | 4         | 9      | 0.24%   |
| Hewlett-Packard     | 3         | 4      | 0.18%   |
| USB                 | 2         | 3      | 0.12%   |
| SABRENT             | 2         | 2      | 0.12%   |
| KESU                | 2         | 2      | 0.12%   |
| HGST HUS            | 2         | 2      | 0.12%   |
| USB3.0              | 1         | 2      | 0.06%   |
| MaxDigital          | 1         | 1      | 0.06%   |
| IBM/Hitachi         | 1         | 1      | 0.06%   |
| HPE                 | 1         | 1      | 0.06%   |
| Hajaan              | 1         | 1      | 0.06%   |
| DAS                 | 1         | 1      | 0.06%   |
| AAPL                | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 416       | 685    | 31.3%   |
| Crucial             | 177       | 271    | 13.32%  |
| Kingston            | 133       | 171    | 10.01%  |
| WDC                 | 108       | 140    | 8.13%   |
| SanDisk             | 98        | 126    | 7.37%   |
| Intel               | 78        | 152    | 5.87%   |
| Apple               | 32        | 35     | 2.41%   |
| OCZ                 | 29        | 44     | 2.18%   |
| SK hynix            | 27        | 33     | 2.03%   |
| Toshiba             | 21        | 28     | 1.58%   |
| SPCC                | 20        | 25     | 1.5%    |
| Micron Technology   | 19        | 22     | 1.43%   |
| A-DATA Technology   | 15        | 20     | 1.13%   |
| LITEONIT            | 14        | 19     | 1.05%   |
| LITEON              | 14        | 22     | 1.05%   |
| Seagate             | 12        | 17     | 0.9%    |
| Patriot             | 12        | 17     | 0.9%    |
| Transcend           | 11        | 17     | 0.83%   |
| KingSpec            | 11        | 26     | 0.83%   |
| Corsair             | 11        | 23     | 0.83%   |
| China               | 7         | 9      | 0.53%   |
| TO Exter            | 6         | 6      | 0.45%   |
| OWC                 | 6         | 13     | 0.45%   |
| Plextor             | 5         | 16     | 0.38%   |
| Gigabyte Technology | 5         | 5      | 0.38%   |
| ASMT                | 4         | 5      | 0.3%    |
| Team                | 3         | 4      | 0.23%   |
| Vaseky              | 2         | 3      | 0.15%   |
| T-CREATE            | 2         | 2      | 0.15%   |
| Lexar               | 2         | 2      | 0.15%   |
| KingFast            | 2         | 2      | 0.15%   |
| Hajaan              | 2         | 2      | 0.15%   |
| FORESEE             | 2         | 2      | 0.15%   |
| Unknown             | 1         | 1      | 0.08%   |
| SATA3 12            | 1         | 1      | 0.08%   |
| SAMSWEET            | 1         | 1      | 0.08%   |
| Radeon              | 1         | 1      | 0.08%   |
| PNY                 | 1         | 1      | 0.08%   |
| OCZ-VERTEX3         | 1         | 1      | 0.08%   |
| Netac               | 1         | 1      | 0.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1375      | 3060   | 39.64%  |
| SSD     | 1153      | 1990   | 33.24%  |
| NVMe    | 763       | 1161   | 21.99%  |
| MMC     | 127       | 186    | 3.66%   |
| Unknown | 51        | 68     | 1.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1980      | 4789   | 64.41%  |
| NVMe | 759       | 1148   | 24.69%  |
| SAS  | 208       | 342    | 6.77%   |
| MMC  | 127       | 186    | 4.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1427      | 2636   | 51.59%  |
| 0.51-1.0   | 733       | 1295   | 26.5%   |
| 1.01-2.0   | 331       | 592    | 11.97%  |
| 3.01-4.0   | 104       | 210    | 3.76%   |
| 4.01-10.0  | 98        | 194    | 3.54%   |
| 2.01-3.0   | 66        | 114    | 2.39%   |
| 10.01-20.0 | 6         | 8      | 0.22%   |
| 0          | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 613       | 22.25%  |
| 251-500        | 578       | 20.98%  |
| 501-1000       | 425       | 15.43%  |
| 1001-2000      | 253       | 9.18%   |
| More than 3000 | 212       | 7.7%    |
| 1-20           | 212       | 7.7%    |
| 51-100         | 193       | 7.01%   |
| 2001-3000      | 103       | 3.74%   |
| 21-50          | 84        | 3.05%   |
| Unknown        | 82        | 2.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1100      | 37.96%  |
| 21-50          | 473       | 16.32%  |
| 101-250        | 323       | 11.15%  |
| 51-100         | 290       | 10.01%  |
| 251-500        | 232       | 8.01%   |
| 501-1000       | 156       | 5.38%   |
| 1001-2000      | 109       | 3.76%   |
| More than 3000 | 89        | 3.07%   |
| Unknown        | 82        | 2.83%   |
| 2001-3000      | 43        | 1.48%   |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Intel SSDSC2CT120A3 120GB               | 7         | 25     | 2.98%   |
| Seagate ST3500418AS 500GB               | 5         | 11     | 2.13%   |
| Hitachi HDS721010DLE630 1TB             | 5         | 7      | 2.13%   |
| Seagate ST500DM002-1BD142 500GB         | 4         | 4      | 1.7%    |
| WDC WD20EARX-00PASB0 2TB                | 3         | 3      | 1.28%   |
| Seagate ST9500325AS 500GB               | 3         | 3      | 1.28%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 4      | 1.28%   |
| Maxtor 6Y080L0 81GB                     | 3         | 4      | 1.28%   |
| Maxtor 6L200M0 208GB                    | 3         | 4      | 1.28%   |
| Kingston SV300S37A120G 120GB SSD        | 3         | 3      | 1.28%   |
| HGST HTS725050A7E630 500GB              | 3         | 3      | 1.28%   |
| WDC WDS500G1X0E-00AFY0 500GB            | 2         | 2      | 0.85%   |
| WDC WD30EZRX-00DC0B0 3TB                | 2         | 2      | 0.85%   |
| WDC WD20EFRX-68EUZN0 2TB                | 2         | 2      | 0.85%   |
| WDC WD2002FAEX-007BA0 2TB               | 2         | 3      | 0.85%   |
| WDC WD1600AVVS-63L2B0 160GB             | 2         | 5      | 0.85%   |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 3      | 0.85%   |
| WDC WD10EFRX-68FYTN0 1TB                | 2         | 2      | 0.85%   |
| WDC WD1003FZEX-00K3CA0 1TB              | 2         | 2      | 0.85%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD    | 2         | 2      | 0.85%   |
| Seagate ST9320423AS 320GB               | 2         | 3      | 0.85%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 4      | 0.85%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 2      | 0.85%   |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 0.85%   |
| Seagate ST3500413AS 500GB               | 2         | 2      | 0.85%   |
| Seagate ST31000333AS 1TB                | 2         | 4      | 0.85%   |
| Seagate ST2000DM001-9YN164 2TB          | 2         | 2      | 0.85%   |
| Seagate ST2000DM001-1ER164 2TB          | 2         | 2      | 0.85%   |
| Seagate ST2000DM001-1CH164 2TB          | 2         | 2      | 0.85%   |
| Seagate ST1000DX001-1CM162 1TB          | 2         | 2      | 0.85%   |
| Seagate ST1000DM010-2EP102 1TB          | 2         | 2      | 0.85%   |
| Seagate ST1000DM003-1ER162 1TB          | 2         | 6      | 0.85%   |
| Samsung Electronics HD501LJ 500GB       | 2         | 24     | 0.85%   |
| Samsung Electronics HD154UI 1TB         | 2         | 3      | 0.85%   |
| Samsung Electronics HD103UJ 1TB         | 2         | 13     | 0.85%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 2         | 2      | 0.85%   |
| Intel SSDSC2KW010T8 1TB                 | 2         | 2      | 0.85%   |
| HGST HTS545050A7E680 500GB              | 2         | 3      | 0.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 1         | 1      | 0.43%   |
| WDC WD6400BEVT-22A0RT0 640GB            | 1         | 1      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 61        | 90     | 27.73%  |
| WDC                 | 43        | 72     | 19.55%  |
| Samsung Electronics | 25        | 64     | 11.36%  |
| Intel               | 18        | 44     | 8.18%   |
| Hitachi             | 16        | 19     | 7.27%   |
| Kingston            | 9         | 9      | 4.09%   |
| Toshiba             | 8         | 11     | 3.64%   |
| HGST                | 7         | 8      | 3.18%   |
| Maxtor              | 6         | 8      | 2.73%   |
| Crucial             | 4         | 5      | 1.82%   |
| Corsair             | 4         | 5      | 1.82%   |
| SanDisk             | 3         | 3      | 1.36%   |
| Fujitsu             | 3         | 3      | 1.36%   |
| SK hynix            | 2         | 2      | 0.91%   |
| SPCC                | 1         | 1      | 0.45%   |
| OCZ                 | 1         | 1      | 0.45%   |
| Netac               | 1         | 1      | 0.45%   |
| MaxDigital          | 1         | 1      | 0.45%   |
| KingSpec            | 1         | 3      | 0.45%   |
| KingFast            | 1         | 1      | 0.45%   |
| HPE                 | 1         | 1      | 0.45%   |
| Hewlett-Packard     | 1         | 2      | 0.45%   |
| Gigabyte Technology | 1         | 1      | 0.45%   |
| Apple               | 1         | 1      | 0.45%   |
| A-DATA Technology   | 1         | 1      | 0.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 61        | 90     | 38.85%  |
| WDC                 | 42        | 69     | 26.75%  |
| Hitachi             | 16        | 19     | 10.19%  |
| Samsung Electronics | 13        | 51     | 8.28%   |
| HGST                | 7         | 8      | 4.46%   |
| Toshiba             | 6         | 9      | 3.82%   |
| Maxtor              | 6         | 8      | 3.82%   |
| Fujitsu             | 3         | 3      | 1.91%   |
| MaxDigital          | 1         | 1      | 0.64%   |
| HPE                 | 1         | 1      | 0.64%   |
| Hewlett-Packard     | 1         | 2      | 0.64%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 139       | 261    | 68.14%  |
| SSD  | 55        | 85     | 26.96%  |
| NVMe | 10        | 11     | 4.9%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD3200AAJS-40RYA0 320GB | 1         | 1      | 50%     |
| Hitachi HDS721010DLE630 1TB | 1         | 6      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Hitachi | 1         | 6      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1690      | 3871   | 61.05%  |
| Works    | 879       | 2230   | 31.76%  |
| Malfunc  | 197       | 357    | 7.12%   |
| Failed   | 2         | 7      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1723      | 52.31%  |
| AMD                              | 505       | 15.33%  |
| Samsung Electronics              | 317       | 9.62%   |
| SanDisk                          | 85        | 2.58%   |
| Marvell Technology Group         | 77        | 2.34%   |
| JMicron Technology               | 66        | 2%      |
| ASMedia Technology               | 62        | 1.88%   |
| Micron/Crucial Technology        | 57        | 1.73%   |
| SK hynix                         | 52        | 1.58%   |
| Phison Electronics               | 49        | 1.49%   |
| Kingston Technology Company      | 49        | 1.49%   |
| Toshiba America Info Systems     | 43        | 1.31%   |
| Micron Technology                | 25        | 0.76%   |
| Nvidia                           | 23        | 0.7%    |
| KIOXIA                           | 23        | 0.7%    |
| ADATA Technology                 | 19        | 0.58%   |
| LSI Logic / Symbios Logic        | 16        | 0.49%   |
| Silicon Motion                   | 12        | 0.36%   |
| VIA Technologies                 | 11        | 0.33%   |
| Realtek Semiconductor            | 10        | 0.3%    |
| Apple                            | 10        | 0.3%    |
| Integrated Technology Express    | 7         | 0.21%   |
| Silicon Image                    | 6         | 0.18%   |
| Seagate Technology               | 6         | 0.18%   |
| Broadcom / LSI                   | 6         | 0.18%   |
| Lite-On Technology               | 5         | 0.15%   |
| Union Memory (Shenzhen)          | 4         | 0.12%   |
| Solid State Storage Technology   | 4         | 0.12%   |
| Hewlett-Packard                  | 4         | 0.12%   |
| ULi Electronics                  | 3         | 0.09%   |
| Silicon Integrated Systems [SiS] | 3         | 0.09%   |
| Adaptec                          | 3         | 0.09%   |
| Shenzhen Longsys Electronics     | 2         | 0.06%   |
| Lenovo                           | 2         | 0.06%   |
| 3ware                            | 2         | 0.06%   |
| Promise Technology               | 1         | 0.03%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 342       | 8.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 179       | 4.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 132       | 3.42%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 105       | 2.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 94        | 2.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 91        | 2.36%   |
| AMD 400 Series Chipset SATA Controller                                                  | 83        | 2.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 74        | 1.92%   |
| Intel SATA Controller [RAID mode]                                                       | 71        | 1.84%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 68        | 1.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 68        | 1.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 66        | 1.71%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 60        | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 60        | 1.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 58        | 1.5%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 56        | 1.45%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 55        | 1.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 53        | 1.37%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 52        | 1.35%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 47        | 1.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 46        | 1.19%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 45        | 1.16%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 40        | 1.04%   |
| AMD 500 Series Chipset SATA Controller                                                  | 40        | 1.04%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 35        | 0.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 34        | 0.88%   |
| Samsung NVMe SSD Controller 980                                                         | 32        | 0.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 32        | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 31        | 0.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 31        | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 31        | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 31        | 0.8%    |
| Intel SSD 660P Series                                                                   | 30        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 30        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 29        | 0.75%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 27        | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 26        | 0.67%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 26        | 0.67%   |
| Micron Non-Volatile memory controller                                                   | 24        | 0.62%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 24        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1830      | 56.24%  |
| NVMe | 764       | 23.48%  |
| IDE  | 400       | 12.29%  |
| RAID | 240       | 7.38%   |
| SAS  | 13        | 0.4%    |
| SCSI | 7         | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1943      | 76.2%   |
| AMD          | 566       | 22.2%   |
| ARM          | 39        | 1.53%   |
| CentaurHauls | 1         | 0.04%   |
| Unknown      | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor       | 34        | 1.33%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 33        | 1.29%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 30        | 1.17%   |
| ARM Processor                           | 28        | 1.1%    |
| Intel Core i7-8550U CPU @ 1.80GHz       | 27        | 1.06%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 26        | 1.02%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 26        | 1.02%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 24        | 0.94%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 22        | 0.86%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 21        | 0.82%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 21        | 0.82%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 21        | 0.82%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 21        | 0.82%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 20        | 0.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 19        | 0.74%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 19        | 0.74%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 18        | 0.7%    |
| Intel Core i7-4790 CPU @ 3.60GHz        | 18        | 0.7%    |
| Intel Core i7-8650U CPU @ 1.90GHz       | 17        | 0.67%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 17        | 0.67%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 17        | 0.67%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 16        | 0.63%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 16        | 0.63%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 15        | 0.59%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 15        | 0.59%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 15        | 0.59%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 15        | 0.59%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 14        | 0.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 13        | 0.51%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 13        | 0.51%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 13        | 0.51%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 13        | 0.51%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 13        | 0.51%   |
| AMD FX-6300 Six-Core Processor          | 13        | 0.51%   |
| Intel Core i7-3770K CPU @ 3.50GHz       | 12        | 0.47%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 12        | 0.47%   |
| AMD Ryzen 7 1700 Eight-Core Processor   | 12        | 0.47%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 11        | 0.43%   |
| Intel Core i7-3610QM CPU @ 2.30GHz      | 11        | 0.43%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 11        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 693       | 27.16%  |
| Intel Core i5           | 577       | 22.61%  |
| Other                   | 133       | 5.21%   |
| AMD Ryzen 5             | 133       | 5.21%   |
| Intel Core 2 Duo        | 115       | 4.51%   |
| Intel Core i3           | 113       | 4.43%   |
| AMD Ryzen 7             | 103       | 4.04%   |
| Intel Celeron           | 87        | 3.41%   |
| Intel Xeon              | 61        | 2.39%   |
| AMD Ryzen 9             | 58        | 2.27%   |
| AMD FX                  | 43        | 1.68%   |
| Intel Pentium           | 42        | 1.65%   |
| Intel Atom              | 31        | 1.21%   |
| AMD A6                  | 24        | 0.94%   |
| Intel Core 2            | 22        | 0.86%   |
| AMD Ryzen 3             | 21        | 0.82%   |
| AMD A4                  | 21        | 0.82%   |
| Intel Core 2 Quad       | 20        | 0.78%   |
| AMD A8                  | 19        | 0.74%   |
| Intel Core i9           | 16        | 0.63%   |
| Intel Pentium Dual-Core | 14        | 0.55%   |
| AMD Phenom II X4        | 14        | 0.55%   |
| AMD E2                  | 14        | 0.55%   |
| AMD A10                 | 13        | 0.51%   |
| AMD Phenom II X6        | 10        | 0.39%   |
| ARM BCM                 | 9         | 0.35%   |
| AMD Ryzen Threadripper  | 9         | 0.35%   |
| AMD Athlon              | 9         | 0.35%   |
| Intel Genuine           | 8         | 0.31%   |
| Intel Core m3           | 8         | 0.31%   |
| Intel Pentium D         | 7         | 0.27%   |
| AMD Ryzen 7 PRO         | 7         | 0.27%   |
| AMD E1                  | 7         | 0.27%   |
| Intel Pentium 4         | 5         | 0.2%    |
| AMD Phenom II X2        | 5         | 0.2%    |
| AMD E                   | 5         | 0.2%    |
| AMD Athlon II X4        | 5         | 0.2%    |
| AMD Athlon II X2        | 5         | 0.2%    |
| AMD Athlon 64 X2        | 5         | 0.2%    |
| Intel Pentium Dual      | 4         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1020      | 39.95%  |
| 2       | 879       | 34.43%  |
| 6       | 297       | 11.63%  |
| 8       | 178       | 6.97%   |
| 12      | 53        | 2.08%   |
| 1       | 51        | 2%      |
| 16      | 27        | 1.06%   |
| 3       | 18        | 0.71%   |
| 10      | 11        | 0.43%   |
| 14      | 6         | 0.24%   |
| 24      | 5         | 0.2%    |
| Unknown | 3         | 0.12%   |
| 40      | 2         | 0.08%   |
| 32      | 2         | 0.08%   |
| 128     | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2512      | 98.47%  |
| 2       | 35        | 1.37%   |
| Unknown | 3         | 0.12%   |
| 4       | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1717      | 67.25%  |
| 1       | 831       | 32.55%  |
| Unknown | 3         | 0.12%   |
| 8       | 1         | 0.04%   |
| 4       | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2466      | 96.33%  |
| Unknown        | 66        | 2.58%   |
| 32-bit         | 22        | 0.86%   |
| 64-bit         | 6         | 0.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 634       | 23.93%  |
| 0x206a7    | 158       | 5.96%   |
| 0x306a9    | 151       | 5.7%    |
| 0x306c3    | 129       | 4.87%   |
| 0x1067a    | 87        | 3.28%   |
| 0x906ea    | 75        | 2.83%   |
| 0x906e9    | 60        | 2.27%   |
| 0x506e3    | 58        | 2.19%   |
| 0x806e9    | 55        | 2.08%   |
| 0x806ea    | 52        | 1.96%   |
| 0x40651    | 52        | 1.96%   |
| 0x806ec    | 51        | 1.93%   |
| 0x406e3    | 50        | 1.89%   |
| 0x08701021 | 48        | 1.81%   |
| 0x20655    | 41        | 1.55%   |
| 0x806c1    | 37        | 1.4%    |
| 0x306d4    | 37        | 1.4%    |
| 0x08701013 | 33        | 1.25%   |
| 0x106e5    | 28        | 1.06%   |
| 0x0800820d | 28        | 1.06%   |
| 0x30678    | 24        | 0.91%   |
| 0x20652    | 24        | 0.91%   |
| 0x10676    | 23        | 0.87%   |
| 0x06000852 | 21        | 0.79%   |
| 0xa0652    | 20        | 0.76%   |
| 0x906ed    | 18        | 0.68%   |
| 0x106a5    | 18        | 0.68%   |
| 0x010000c8 | 18        | 0.68%   |
| 0x0a50000c | 17        | 0.64%   |
| 0x06001119 | 17        | 0.64%   |
| 0x806eb    | 16        | 0.6%    |
| 0x706e5    | 16        | 0.6%    |
| 0x6fb      | 16        | 0.6%    |
| 0x6f6      | 16        | 0.6%    |
| 0x206c2    | 15        | 0.57%   |
| 0x08108109 | 15        | 0.57%   |
| 0x08001138 | 15        | 0.57%   |
| 0x06006705 | 15        | 0.57%   |
| 0x07030105 | 14        | 0.53%   |
| 0x6fd      | 13        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 425       | 16.64%  |
| Haswell          | 255       | 9.98%   |
| SandyBridge      | 202       | 7.91%   |
| IvyBridge        | 198       | 7.75%   |
| Skylake          | 148       | 5.79%   |
| Zen 2            | 134       | 5.25%   |
| Penryn           | 129       | 5.05%   |
| Westmere         | 98        | 3.84%   |
| Zen 3            | 73        | 2.86%   |
| Unknown          | 73        | 2.86%   |
| Zen+             | 64        | 2.51%   |
| Core             | 63        | 2.47%   |
| Zen              | 59        | 2.31%   |
| CometLake        | 59        | 2.31%   |
| Silvermont       | 58        | 2.27%   |
| Nehalem          | 57        | 2.23%   |
| Piledriver       | 52        | 2.04%   |
| K10              | 51        | 2%      |
| Broadwell        | 51        | 2%      |
| TigerLake        | 46        | 1.8%    |
| IceLake          | 37        | 1.45%   |
| Excavator        | 31        | 1.21%   |
| Goldmont plus    | 23        | 0.9%    |
| Puma             | 19        | 0.74%   |
| Goldmont         | 17        | 0.67%   |
| Bonnell          | 16        | 0.63%   |
| Steamroller      | 14        | 0.55%   |
| NetBurst         | 14        | 0.55%   |
| Alderlake Hybrid | 14        | 0.55%   |
| Jaguar           | 13        | 0.51%   |
| P6               | 12        | 0.47%   |
| K8 Hammer        | 12        | 0.47%   |
| Bulldozer        | 12        | 0.47%   |
| K10 Llano        | 10        | 0.39%   |
| Bobcat           | 9         | 0.35%   |
| Tremont          | 4         | 0.16%   |
| K8 & K10 hybrid  | 2         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1350      | 45.35%  |
| Nvidia                           | 934       | 31.37%  |
| AMD                              | 668       | 22.44%  |
| Matrox Electronics Systems       | 14        | 0.47%   |
| VIA Technologies                 | 4         | 0.13%   |
| Silicon Integrated Systems [SiS] | 3         | 0.1%    |
| Neomagic                         | 2         | 0.07%   |
| ASPEED Technology                | 2         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 133       | 4.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 87        | 2.83%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 70        | 2.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 65        | 2.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 64        | 2.08%   |
| Intel UHD Graphics 620                                                                   | 64        | 2.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 58        | 1.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 58        | 1.89%   |
| Intel HD Graphics 620                                                                    | 52        | 1.69%   |
| Intel Core Processor Integrated Graphics Controller                                      | 51        | 1.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 43        | 1.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 43        | 1.4%    |
| Intel HD Graphics 530                                                                    | 42        | 1.37%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 39        | 1.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 39        | 1.27%   |
| Intel HD Graphics 630                                                                    | 38        | 1.24%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 32        | 1.04%   |
| Intel HD Graphics 5500                                                                   | 31        | 1.01%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 31        | 1.01%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 27        | 0.88%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 27        | 0.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 27        | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 26        | 0.85%   |
| AMD Cezanne                                                                              | 25        | 0.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 24        | 0.78%   |
| AMD Renoir                                                                               | 24        | 0.78%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 23        | 0.75%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 22        | 0.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 22        | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 21        | 0.68%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 21        | 0.68%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 20        | 0.65%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 20        | 0.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 20        | 0.65%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 19        | 0.62%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 19        | 0.62%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 17        | 0.55%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 17        | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 16        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 938       | 36.31%  |
| 1 x Nvidia               | 593       | 22.96%  |
| 1 x AMD                  | 531       | 20.56%  |
| Intel + Nvidia           | 303       | 11.73%  |
| Intel + AMD              | 63        | 2.44%   |
| 2 x AMD                  | 48        | 1.86%   |
| Other                    | 40        | 1.55%   |
| AMD + Nvidia             | 28        | 1.08%   |
| 1 x Matrox               | 11        | 0.43%   |
| 2 x Nvidia               | 8         | 0.31%   |
| 1 x VIA                  | 4         | 0.15%   |
| 1 x SiS                  | 3         | 0.12%   |
| Nvidia + Matrox          | 3         | 0.12%   |
| Intel + AMD + 1 x Nvidia | 3         | 0.12%   |
| 2 x Intel                | 2         | 0.08%   |
| Nvidia + ASPEED          | 2         | 0.08%   |
| 1 x Neomagic             | 2         | 0.08%   |
| Intel + 2 x AMD          | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1957      | 74.78%  |
| Proprietary | 524       | 20.02%  |
| Unknown     | 136       | 5.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1331      | 50.42%  |
| 1.01-2.0   | 349       | 13.22%  |
| 0.01-0.5   | 243       | 9.2%    |
| 0.51-1.0   | 223       | 8.45%   |
| 3.01-4.0   | 200       | 7.58%   |
| 7.01-8.0   | 152       | 5.76%   |
| 5.01-6.0   | 68        | 2.58%   |
| 8.01-16.0  | 38        | 1.44%   |
| 2.01-3.0   | 26        | 0.98%   |
| 16.01-24.0 | 8         | 0.3%    |
| 32.01-64.0 | 1         | 0.04%   |
| 4.01-5.0   | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 365       | 12.63%  |
| AU Optronics            | 274       | 9.48%   |
| LG Display              | 214       | 7.4%    |
| Dell                    | 214       | 7.4%    |
| Chimei Innolux          | 164       | 5.67%   |
| Acer                    | 142       | 4.91%   |
| Goldstar                | 130       | 4.5%    |
| BOE                     | 122       | 4.22%   |
| BenQ                    | 119       | 4.12%   |
| Hewlett-Packard         | 116       | 4.01%   |
| Apple                   | 97        | 3.36%   |
| Philips                 | 90        | 3.11%   |
| Ancor Communications    | 90        | 3.11%   |
| AOC                     | 66        | 2.28%   |
| Sharp                   | 61        | 2.11%   |
| ViewSonic               | 59        | 2.04%   |
| Lenovo                  | 58        | 2.01%   |
| Unknown                 | 52        | 1.8%    |
| Chi Mei Optoelectronics | 42        | 1.45%   |
| Sony                    | 32        | 1.11%   |
| ASUSTek Computer        | 30        | 1.04%   |
| ___                     | 27        | 0.93%   |
| LG Electronics          | 25        | 0.86%   |
| Panasonic               | 22        | 0.76%   |
| Kogan                   | 19        | 0.66%   |
| GKK                     | 16        | 0.55%   |
| PANDA                   | 15        | 0.52%   |
| Toshiba                 | 13        | 0.45%   |
| SAC                     | 11        | 0.38%   |
| Unknown (XXX)           | 10        | 0.35%   |
| Hitachi                 | 10        | 0.35%   |
| MSI                     | 8         | 0.28%   |
| CVT                     | 8         | 0.28%   |
| TCL                     | 7         | 0.24%   |
| MStar                   | 7         | 0.24%   |
| eMachines               | 7         | 0.24%   |
| MiTAC                   | 6         | 0.21%   |
| LG Philips              | 6         | 0.21%   |
| InfoVision              | 6         | 0.21%   |
| Gigabyte Technology     | 6         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch      | 21        | 0.69%   |
| ___ LCD TV ___0101 1366x768                                              | 19        | 0.62%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 15        | 0.49%   |
| ViewSonic VA2226w-3 VSC2051 1680x1050 490x290mm 22.4-inch                | 12        | 0.39%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch             | 10        | 0.33%   |
| ___ LCD TV ___9000 1360x768                                              | 9         | 0.3%    |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                      | 9         | 0.3%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 9         | 0.3%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 9         | 0.3%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 9         | 0.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.3%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 8         | 0.26%   |
| Samsung Electronics LCD Monitor SAM2C35 1024x768 280x210mm 13.8-inch     | 8         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 8         | 0.26%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                        | 8         | 0.26%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                       | 8         | 0.26%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 8         | 0.26%   |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                         | 8         | 0.26%   |
| Unknown (XXX) Beyond TV XXX2851 1920x1080 1209x680mm 54.6-inch           | 7         | 0.23%   |
| SAC LED MONITOR SAC952D 1920x1080 480x270mm 21.7-inch                    | 7         | 0.23%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch             | 7         | 0.23%   |
| CVT CVTE TV CVT0003 1920x1080 575x323mm 26.0-inch                        | 7         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.23%   |
| Chimei Innolux LCD Monitor CMN1514 1920x1080 344x193mm 15.5-inch         | 7         | 0.23%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                          | 7         | 0.23%   |
| Ancor Communications MW221 ACI22B1 1680x1050 473x296mm 22.0-inch         | 7         | 0.23%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                       | 6         | 0.2%    |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 6         | 0.2%    |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 6         | 0.2%    |
| eMachines E190HQV EMA0212 1366x768 409x230mm 18.5-inch                   | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 6         | 0.2%    |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                     | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.2%    |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 6         | 0.2%    |
| Acer ET322QR ACR0568 1920x1080 698x393mm 31.5-inch                       | 6         | 0.2%    |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 5         | 0.16%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 5         | 0.16%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                  | 5         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1164      | 42.34%  |
| 1366x768 (WXGA)    | 413       | 15.02%  |
| 3840x2160 (4K)     | 241       | 8.77%   |
| 2560x1440 (QHD)    | 138       | 5.02%   |
| 1680x1050 (WSXGA+) | 109       | 3.97%   |
| 1280x1024 (SXGA)   | 102       | 3.71%   |
| 1440x900 (WXGA+)   | 81        | 2.95%   |
| 1920x1200 (WUXGA)  | 74        | 2.69%   |
| 1600x900 (HD+)     | 61        | 2.22%   |
| 1280x800 (WXGA)    | 53        | 1.93%   |
| Unknown            | 46        | 1.67%   |
| 3440x1440          | 31        | 1.13%   |
| 3840x1080          | 24        | 0.87%   |
| 2560x1600          | 23        | 0.84%   |
| 1360x768           | 19        | 0.69%   |
| 2560x1080          | 17        | 0.62%   |
| 3840x2400          | 12        | 0.44%   |
| 2880x1800          | 11        | 0.4%    |
| 2736x1824          | 10        | 0.36%   |
| 1920x540           | 9         | 0.33%   |
| 1280x768           | 9         | 0.33%   |
| 3200x1800 (QHD+)   | 7         | 0.25%   |
| 2160x1440          | 7         | 0.25%   |
| 1280x720 (HD)      | 6         | 0.22%   |
| 1024x600           | 6         | 0.22%   |
| 3840x1600          | 5         | 0.18%   |
| 1024x768 (XGA)     | 5         | 0.18%   |
| 5760x2160          | 4         | 0.15%   |
| 5120x1440          | 4         | 0.15%   |
| 4480x1440          | 4         | 0.15%   |
| 3600x1080          | 4         | 0.15%   |
| 3072x1920          | 4         | 0.15%   |
| 1920x1280          | 4         | 0.15%   |
| 1600x1200          | 4         | 0.15%   |
| 2256x1504          | 3         | 0.11%   |
| 7680x2160          | 2         | 0.07%   |
| 3456x2160          | 2         | 0.07%   |
| 3286x1080          | 2         | 0.07%   |
| 3200x2000          | 2         | 0.07%   |
| 3200x1080          | 2         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 539       | 18.83%  |
| 27      | 283       | 9.88%   |
| 13      | 231       | 8.07%   |
| 24      | 223       | 7.79%   |
| 23      | 214       | 7.47%   |
| Unknown | 198       | 6.92%   |
| 21      | 165       | 5.76%   |
| 14      | 153       | 5.34%   |
| 19      | 120       | 4.19%   |
| 17      | 117       | 4.09%   |
| 31      | 85        | 2.97%   |
| 22      | 76        | 2.65%   |
| 12      | 52        | 1.82%   |
| 72      | 46        | 1.61%   |
| 34      | 44        | 1.54%   |
| 20      | 44        | 1.54%   |
| 11      | 38        | 1.33%   |
| 18      | 31        | 1.08%   |
| 84      | 21        | 0.73%   |
| 26      | 19        | 0.66%   |
| 54      | 16        | 0.56%   |
| 32      | 16        | 0.56%   |
| 52      | 13        | 0.45%   |
| 16      | 13        | 0.45%   |
| 40      | 12        | 0.42%   |
| 48      | 11        | 0.38%   |
| 37      | 8         | 0.28%   |
| 25      | 8         | 0.28%   |
| 10      | 8         | 0.28%   |
| 29      | 7         | 0.24%   |
| 42      | 6         | 0.21%   |
| 55      | 5         | 0.17%   |
| 49      | 5         | 0.17%   |
| 46      | 5         | 0.17%   |
| 35      | 5         | 0.17%   |
| 63      | 4         | 0.14%   |
| 36      | 3         | 0.1%    |
| 75      | 2         | 0.07%   |
| 65      | 2         | 0.07%   |
| 60      | 2         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 795       | 28.39%  |
| 501-600     | 650       | 23.21%  |
| 401-500     | 350       | 12.5%   |
| 201-300     | 245       | 8.75%   |
| Unknown     | 198       | 7.07%   |
| 351-400     | 187       | 6.68%   |
| 601-700     | 141       | 5.04%   |
| 1501-2000   | 71        | 2.54%   |
| 1001-1500   | 67        | 2.39%   |
| 701-800     | 60        | 2.14%   |
| 801-900     | 27        | 0.96%   |
| 901-1000    | 7         | 0.25%   |
| 101-200     | 2         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1819      | 71.17%  |
| 16/10   | 344       | 13.46%  |
| Unknown | 166       | 6.49%   |
| 5/4     | 90        | 3.52%   |
| 21/9    | 54        | 2.11%   |
| 3/2     | 33        | 1.29%   |
| 4/3     | 26        | 1.02%   |
| 32/9    | 13        | 0.51%   |
| 6/5     | 10        | 0.39%   |
| 0.62    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 562       | 19.87%  |
| 101-110        | 539       | 19.06%  |
| 301-350        | 295       | 10.43%  |
| 81-90          | 267       | 9.44%   |
| 151-200        | 199       | 7.04%   |
| Unknown        | 198       | 7%      |
| 351-500        | 152       | 5.37%   |
| 71-80          | 120       | 4.24%   |
| More than 1000 | 118       | 4.17%   |
| 251-300        | 84        | 2.97%   |
| 121-130        | 81        | 2.86%   |
| 501-1000       | 49        | 1.73%   |
| 141-150        | 42        | 1.49%   |
| 61-70          | 41        | 1.45%   |
| 51-60          | 39        | 1.38%   |
| 111-120        | 12        | 0.42%   |
| 131-140        | 10        | 0.35%   |
| 91-100         | 10        | 0.35%   |
| 41-50          | 8         | 0.28%   |
| 1-40           | 2         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 999       | 36.73%  |
| 101-120       | 637       | 23.42%  |
| 121-160       | 536       | 19.71%  |
| Unknown       | 198       | 7.28%   |
| 161-240       | 160       | 5.88%   |
| 1-50          | 97        | 3.57%   |
| More than 240 | 93        | 3.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2031      | 76.41%  |
| 2     | 446       | 16.78%  |
| 0     | 122       | 4.59%   |
| 3     | 54        | 2.03%   |
| 4     | 5         | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1327      | 33.78%  |
| Realtek Semiconductor           | 1300      | 33.1%   |
| Qualcomm Atheros                | 422       | 10.74%  |
| Broadcom                        | 258       | 6.57%   |
| Broadcom Limited                | 56        | 1.43%   |
| Marvell Technology Group        | 53        | 1.35%   |
| Ralink                          | 51        | 1.3%    |
| TP-Link                         | 37        | 0.94%   |
| Ralink Technology               | 37        | 0.94%   |
| Samsung Electronics             | 28        | 0.71%   |
| NetGear                         | 21        | 0.53%   |
| MediaTek                        | 20        | 0.51%   |
| D-Link                          | 18        | 0.46%   |
| DisplayLink                     | 17        | 0.43%   |
| D-Link System                   | 17        | 0.43%   |
| Nvidia                          | 16        | 0.41%   |
| Huawei Technologies             | 16        | 0.41%   |
| Sierra Wireless                 | 14        | 0.36%   |
| Microsoft                       | 14        | 0.36%   |
| Edimax Technology               | 14        | 0.36%   |
| Dell                            | 14        | 0.36%   |
| Aquantia                        | 13        | 0.33%   |
| ASIX Electronics                | 11        | 0.28%   |
| Lenovo                          | 10        | 0.25%   |
| Apple                           | 10        | 0.25%   |
| ZTE WCDMA Technologies MSM      | 9         | 0.23%   |
| Motorola PCS                    | 9         | 0.23%   |
| ASUSTek Computer                | 9         | 0.23%   |
| VIA Technologies                | 7         | 0.18%   |
| Google                          | 7         | 0.18%   |
| Qualcomm Atheros Communications | 6         | 0.15%   |
| OPPO Electronics                | 6         | 0.15%   |
| Hewlett-Packard                 | 6         | 0.15%   |
| Mellanox Technologies           | 5         | 0.13%   |
| Arduino SA                      | 5         | 0.13%   |
| Standard Microsystems           | 4         | 0.1%    |
| Qualcomm                        | 4         | 0.1%    |
| JMicron Technology              | 4         | 0.1%    |
| ICS Advent                      | 4         | 0.1%    |
| Xiaomi                          | 3         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 897       | 19.49%  |
| Intel Wi-Fi 6 AX200                                               | 127       | 2.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 109       | 2.37%   |
| Intel I211 Gigabit Network Connection                             | 105       | 2.28%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 101       | 2.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 89        | 1.93%   |
| Intel Wireless 8265 / 8275                                        | 68        | 1.48%   |
| Intel Wireless 8260                                               | 61        | 1.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 57        | 1.24%   |
| Intel Ethernet Connection (2) I219-V                              | 54        | 1.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 53        | 1.15%   |
| Intel Ethernet Connection I217-LM                                 | 49        | 1.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 48        | 1.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 47        | 1.02%   |
| Intel Wireless 7260                                               | 47        | 1.02%   |
| Intel Wireless 7265                                               | 46        | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                   | 43        | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 41        | 0.89%   |
| Intel Wireless 3165                                               | 40        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                              | 39        | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 38        | 0.83%   |
| Intel Wi-Fi 6 AX201                                               | 36        | 0.78%   |
| Intel Wireless-AC 9260                                            | 35        | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 34        | 0.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 33        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 33        | 0.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 33        | 0.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 31        | 0.67%   |
| Intel Ethernet Controller I225-V                                  | 31        | 0.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 31        | 0.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 30        | 0.65%   |
| Intel Centrino Ultimate-N 6300                                    | 28        | 0.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 27        | 0.59%   |
| Realtek 802.11ac NIC                                              | 25        | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 24        | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 24        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 24        | 0.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 24        | 0.52%   |
| Intel 82579V Gigabit Network Connection                           | 23        | 0.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 22        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 914       | 45.7%   |
| Qualcomm Atheros                | 314       | 15.7%   |
| Realtek Semiconductor           | 283       | 14.15%  |
| Broadcom                        | 175       | 8.75%   |
| Ralink                          | 51        | 2.55%   |
| Ralink Technology               | 37        | 1.85%   |
| Broadcom Limited                | 37        | 1.85%   |
| TP-Link                         | 35        | 1.75%   |
| NetGear                         | 20        | 1%      |
| Marvell Technology Group        | 18        | 0.9%    |
| MediaTek                        | 16        | 0.8%    |
| Sierra Wireless                 | 14        | 0.7%    |
| Edimax Technology               | 14        | 0.7%    |
| D-Link System                   | 12        | 0.6%    |
| Microsoft                       | 10        | 0.5%    |
| D-Link                          | 10        | 0.5%    |
| ASUSTek Computer                | 9         | 0.45%   |
| Dell                            | 8         | 0.4%    |
| Qualcomm Atheros Communications | 6         | 0.3%    |
| BUFFALO                         | 3         | 0.15%   |
| Belkin Components               | 3         | 0.15%   |
| Wacom                           | 2         | 0.1%    |
| Linksys                         | 2         | 0.1%    |
| Xiaomi                          | 1         | 0.05%   |
| Wilocity                        | 1         | 0.05%   |
| Toshiba                         | 1         | 0.05%   |
| Qualcomm                        | 1         | 0.05%   |
| IMC Networks                    | 1         | 0.05%   |
| Hewlett-Packard                 | 1         | 0.05%   |
| AboCom Systems                  | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 127       | 6.31%   |
| Intel Wireless 8265 / 8275                                     | 68        | 3.38%   |
| Intel Wireless 8260                                            | 61        | 3.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 53        | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 48        | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 47        | 2.33%   |
| Intel Wireless 7260                                            | 47        | 2.33%   |
| Intel Wireless 7265                                            | 46        | 2.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 43        | 2.14%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 41        | 2.04%   |
| Intel Wireless 3165                                            | 40        | 1.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 38        | 1.89%   |
| Intel Wi-Fi 6 AX201                                            | 36        | 1.79%   |
| Intel Wireless-AC 9260                                         | 35        | 1.74%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 34        | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 33        | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 33        | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 31        | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 31        | 1.54%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 30        | 1.49%   |
| Intel Centrino Ultimate-N 6300                                 | 28        | 1.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 27        | 1.34%   |
| Realtek 802.11ac NIC                                           | 25        | 1.24%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 24        | 1.19%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 22        | 1.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 21        | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 21        | 1.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 21        | 1.04%   |
| Intel Wireless 3160                                            | 20        | 0.99%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 19        | 0.94%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 19        | 0.94%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 18        | 0.89%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 17        | 0.84%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 17        | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 16        | 0.79%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 16        | 0.79%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 16        | 0.79%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 16        | 0.79%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 15        | 0.75%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 15        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1161      | 47.23%  |
| Intel                            | 757       | 30.8%   |
| Qualcomm Atheros                 | 154       | 6.27%   |
| Broadcom                         | 127       | 5.17%   |
| Marvell Technology Group         | 35        | 1.42%   |
| Samsung Electronics              | 28        | 1.14%   |
| Broadcom Limited                 | 19        | 0.77%   |
| DisplayLink                      | 17        | 0.69%   |
| Nvidia                           | 16        | 0.65%   |
| Aquantia                         | 13        | 0.53%   |
| Huawei Technologies              | 12        | 0.49%   |
| ASIX Electronics                 | 11        | 0.45%   |
| Lenovo                           | 10        | 0.41%   |
| Apple                            | 10        | 0.41%   |
| ZTE WCDMA Technologies MSM       | 9         | 0.37%   |
| D-Link                           | 8         | 0.33%   |
| VIA Technologies                 | 7         | 0.28%   |
| Google                           | 7         | 0.28%   |
| OPPO Electronics                 | 6         | 0.24%   |
| Motorola PCS                     | 5         | 0.2%    |
| D-Link System                    | 5         | 0.2%    |
| Standard Microsystems            | 4         | 0.16%   |
| JMicron Technology               | 4         | 0.16%   |
| ICS Advent                       | 4         | 0.16%   |
| Microsoft                        | 3         | 0.12%   |
| Microchip Technology             | 3         | 0.12%   |
| MediaTek                         | 3         | 0.12%   |
| Xiaomi                           | 2         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.08%   |
| Qualcomm                         | 2         | 0.08%   |
| NetGear                          | 2         | 0.08%   |
| Mellanox Technologies            | 2         | 0.08%   |
| Hewlett-Packard                  | 2         | 0.08%   |
| vivo                             | 1         | 0.04%   |
| TP-Link                          | 1         | 0.04%   |
| T & A Mobile Phones              | 1         | 0.04%   |
| IBM                              | 1         | 0.04%   |
| HMD Global                       | 1         | 0.04%   |
| Cypress Semiconductor            | 1         | 0.04%   |
| Attansic Technology              | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 897       | 35.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 109       | 4.3%    |
| Intel I211 Gigabit Network Connection                             | 105       | 4.14%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 101       | 3.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 89        | 3.51%   |
| Realtek RTL8125 2.5GbE Controller                                 | 57        | 2.25%   |
| Intel Ethernet Connection (2) I219-V                              | 54        | 2.13%   |
| Intel Ethernet Connection I217-LM                                 | 49        | 1.93%   |
| Intel Ethernet Connection (7) I219-V                              | 39        | 1.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 33        | 1.3%    |
| Intel Ethernet Controller I225-V                                  | 31        | 1.22%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 24        | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                             | 24        | 0.95%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 24        | 0.95%   |
| Intel 82579V Gigabit Network Connection                           | 23        | 0.91%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 22        | 0.87%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 0.87%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 21        | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 20        | 0.79%   |
| Intel Ethernet Connection I217-V                                  | 20        | 0.79%   |
| Intel 82577LM Gigabit Network Connection                          | 19        | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 16        | 0.63%   |
| Intel Ethernet Connection (2) I218-V                              | 16        | 0.63%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 16        | 0.63%   |
| Intel I210 Gigabit Network Connection                             | 15        | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 15        | 0.59%   |
| Intel 82574L Gigabit Network Connection                           | 15        | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14        | 0.55%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.51%   |
| Intel Ethernet Connection I219-V                                  | 12        | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11        | 0.43%   |
| Intel 82578DM Gigabit Network Connection                          | 11        | 0.43%   |
| Intel 82546EB Gigabit Ethernet Controller (Copper)                | 11        | 0.43%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.39%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 0.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 0.39%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 10        | 0.39%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 10        | 0.39%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 0.36%   |
| Intel Ethernet Connection (10) I219-V                             | 9         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2225      | 53.71%  |
| WiFi     | 1864      | 44.99%  |
| Modem    | 39        | 0.94%   |
| Unknown  | 15        | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1404      | 53.16%  |
| Ethernet | 1236      | 46.8%   |
| Unknown  | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1354      | 52.6%   |
| 1     | 1033      | 40.13%  |
| 3     | 92        | 3.57%   |
| 0     | 68        | 2.64%   |
| 4     | 17        | 0.66%   |
| 5     | 7         | 0.27%   |
| 6     | 3         | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2329      | 89.71%  |
| Yes  | 267       | 10.29%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 734       | 50.45%  |
| Broadcom                        | 102       | 7.01%   |
| Apple                           | 97        | 6.67%   |
| Cambridge Silicon Radio         | 93        | 6.39%   |
| Qualcomm Atheros Communications | 90        | 6.19%   |
| Realtek Semiconductor           | 81        | 5.57%   |
| Lite-On Technology              | 39        | 2.68%   |
| Toshiba                         | 35        | 2.41%   |
| IMC Networks                    | 35        | 2.41%   |
| Foxconn / Hon Hai               | 33        | 2.27%   |
| ASUSTek Computer                | 22        | 1.51%   |
| Ralink                          | 16        | 1.1%    |
| Marvell Semiconductor           | 16        | 1.1%    |
| Hewlett-Packard                 | 16        | 1.1%    |
| Dell                            | 15        | 1.03%   |
| Alps Electric                   | 6         | 0.41%   |
| Realtek                         | 5         | 0.34%   |
| Ralink Technology               | 3         | 0.21%   |
| MediaTek                        | 3         | 0.21%   |
| Edimax Technology               | 3         | 0.21%   |
| USI                             | 2         | 0.14%   |
| TP-Link                         | 2         | 0.14%   |
| Integrated System Solution      | 2         | 0.14%   |
| Belkin Components               | 2         | 0.14%   |
| Opticis                         | 1         | 0.07%   |
| Logitech                        | 1         | 0.07%   |
| Creative Technology             | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 268       | 18.39%  |
| Intel AX200 Bluetooth                               | 123       | 8.44%   |
| Intel AX201 Bluetooth                               | 120       | 8.24%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 93        | 6.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 89        | 6.11%   |
| Realtek Bluetooth Radio                             | 40        | 2.75%   |
| Intel Wireless-AC 3168 Bluetooth                    | 38        | 2.61%   |
| Qualcomm Atheros  Bluetooth Device                  | 37        | 2.54%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 37        | 2.54%   |
| Apple Bluetooth USB Host Controller                 | 33        | 2.26%   |
| Apple Bluetooth Host Controller                     | 33        | 2.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 32        | 2.2%    |
| Realtek  Bluetooth 4.2 Adapter                      | 30        | 2.06%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 23        | 1.58%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 21        | 1.44%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 20        | 1.37%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 1.24%   |
| Intel AX210 Bluetooth                               | 18        | 1.24%   |
| Ralink RT3290 Bluetooth                             | 16        | 1.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 15        | 1.03%   |
| Intel Bluetooth Device                              | 14        | 0.96%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 0.96%   |
| Marvell Bluetooth and Wireless LAN Composite        | 13        | 0.89%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 0.89%   |
| Toshiba Bluetooth Device                            | 12        | 0.82%   |
| Lite-On Bluetooth Device                            | 12        | 0.82%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 11        | 0.75%   |
| Apple Bluetooth HCI                                 | 11        | 0.75%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 0.69%   |
| IMC Networks Bluetooth Radio                        | 10        | 0.69%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 0.69%   |
| Broadcom HP Portable Bumble Bee                     | 9         | 0.62%   |
| Toshiba Integrated Bluetooth HCI                    | 8         | 0.55%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.55%   |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.41%   |
| IMC Networks Bluetooth Device                       | 6         | 0.41%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.41%   |
| Toshiba Askey Bluetooth Module                      | 5         | 0.34%   |
| Realtek Bluetooth Radio                             | 5         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1855      | 49.59%  |
| AMD                                  | 750       | 20.05%  |
| Nvidia                               | 698       | 18.66%  |
| C-Media Electronics                  | 50        | 1.34%   |
| Logitech                             | 40        | 1.07%   |
| Creative Labs                        | 23        | 0.61%   |
| Realtek Semiconductor                | 21        | 0.56%   |
| Texas Instruments                    | 17        | 0.45%   |
| Kingston Technology                  | 16        | 0.43%   |
| Creative Technology                  | 15        | 0.4%    |
| Plantronics                          | 13        | 0.35%   |
| GN Netcom                            | 12        | 0.32%   |
| Generalplus Technology               | 12        | 0.32%   |
| RODE Microphones                     | 11        | 0.29%   |
| Razer USA                            | 10        | 0.27%   |
| Apple                                | 10        | 0.27%   |
| VIA Technologies                     | 7         | 0.19%   |
| SteelSeries ApS                      | 7         | 0.19%   |
| Lenovo                               | 7         | 0.19%   |
| Dell                                 | 7         | 0.19%   |
| Corsair                              | 7         | 0.19%   |
| Blue Microphones                     | 7         | 0.19%   |
| JMTek                                | 6         | 0.16%   |
| Hewlett-Packard                      | 6         | 0.16%   |
| Thesycon Systemsoftware & Consulting | 5         | 0.13%   |
| Sennheiser Communications            | 5         | 0.13%   |
| OPPO Electronics                     | 5         | 0.13%   |
| Microsoft                            | 5         | 0.13%   |
| Cambridge Silicon Radio              | 5         | 0.13%   |
| Astro Gaming                         | 5         | 0.13%   |
| M-Audio                              | 4         | 0.11%   |
| Giga-Byte Technology                 | 4         | 0.11%   |
| Chicony Electronics                  | 4         | 0.11%   |
| Audio-Technica                       | 4         | 0.11%   |
| ASUSTek Computer                     | 4         | 0.11%   |
| Unknown                              | 3         | 0.08%   |
| ULi Electronics                      | 3         | 0.08%   |
| Turtle Beach                         | 3         | 0.08%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.08%   |
| Samson Technologies                  | 3         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                   | 196       | 4.51%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 193       | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 183       | 4.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 153       | 3.52%   |
| AMD Starship/Matisse HD Audio Controller                                          | 151       | 3.48%   |
| AMD Family 17h/19h HD Audio Controller                                            | 113       | 2.6%    |
| Intel Cannon Lake PCH cAVS                                                        | 112       | 2.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 112       | 2.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 108       | 2.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 87        | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 79        | 1.82%   |
| AMD FCH Azalia Controller                                                         | 79        | 1.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 70        | 1.61%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 69        | 1.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 68        | 1.57%   |
| Intel 8 Series HD Audio Controller                                                | 67        | 1.54%   |
| Intel Haswell-ULT HD Audio Controller                                             | 66        | 1.52%   |
| Intel 200 Series PCH HD Audio                                                     | 63        | 1.45%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 57        | 1.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 55        | 1.27%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 52        | 1.2%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 50        | 1.15%   |
| Nvidia TU116 High Definition Audio Controller                                     | 48        | 1.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                       | 45        | 1.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                            | 45        | 1.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                           | 44        | 1.01%   |
| Intel Broadwell-U Audio Controller                                                | 44        | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 43        | 0.99%   |
| Nvidia GP104 High Definition Audio Controller                                     | 43        | 0.99%   |
| Intel Comet Lake PCH-LP cAVS                                                      | 43        | 0.99%   |
| Nvidia TU106 High Definition Audio Controller                                     | 41        | 0.94%   |
| Intel Comet Lake PCH cAVS                                                         | 41        | 0.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 40        | 0.92%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 40        | 0.92%   |
| AMD Kabini HDMI/DP Audio                                                          | 37        | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                    | 35        | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                                     | 35        | 0.81%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 33        | 0.76%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                  | 31        | 0.71%   |
| Nvidia GK107 HDMI Audio Controller                                                | 30        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 285       | 20.91%  |
| SK hynix            | 229       | 16.8%   |
| Kingston            | 154       | 11.3%   |
| Corsair             | 129       | 9.46%   |
| Micron Technology   | 124       | 9.1%    |
| Unknown             | 123       | 9.02%   |
| Crucial             | 80        | 5.87%   |
| G.Skill             | 77        | 5.65%   |
| Team                | 24        | 1.76%   |
| Nanya Technology    | 22        | 1.61%   |
| Elpida              | 22        | 1.61%   |
| Ramaxel Technology  | 14        | 1.03%   |
| Patriot             | 13        | 0.95%   |
| A-DATA Technology   | 9         | 0.66%   |
| Transcend           | 8         | 0.59%   |
| Apacer              | 8         | 0.59%   |
| Unknown             | 6         | 0.44%   |
| Neo Forza           | 4         | 0.29%   |
| GeIL                | 4         | 0.29%   |
| Unknown (ABCD)      | 2         | 0.15%   |
| Strontium           | 2         | 0.15%   |
| Smart               | 2         | 0.15%   |
| Silicon Power       | 2         | 0.15%   |
| pqi                 | 2         | 0.15%   |
| Unknown (0x89AD)    | 1         | 0.07%   |
| Unknown (0x873E)    | 1         | 0.07%   |
| Unknown (0x0562)    | 1         | 0.07%   |
| Undefi              | 1         | 0.07%   |
| Toshiba             | 1         | 0.07%   |
| Qimonda             | 1         | 0.07%   |
| Princeton           | 1         | 0.07%   |
| PNY                 | 1         | 0.07%   |
| Netlist             | 1         | 0.07%   |
| Innodisk            | 1         | 0.07%   |
| Hewlett-Packard     | 1         | 0.07%   |
| GSkill              | 1         | 0.07%   |
| Goldenmars          | 1         | 0.07%   |
| Golden Empire       | 1         | 0.07%   |
| CSX                 | 1         | 0.07%   |
| Avant               | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s         | 16        | 1.08%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s      | 13        | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 12        | 0.81%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s         | 12        | 0.81%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 10        | 0.67%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 9         | 0.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 9         | 0.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 9         | 0.61%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s        | 9         | 0.61%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                       | 8         | 0.54%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s         | 8         | 0.54%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s         | 8         | 0.54%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                        | 7         | 0.47%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 7         | 0.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 7         | 0.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s         | 7         | 0.47%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 7         | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 6         | 0.4%    |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s       | 6         | 0.4%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 6         | 0.4%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 6         | 0.4%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 6         | 0.4%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 6         | 0.4%    |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s         | 6         | 0.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s         | 6         | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s          | 6         | 0.4%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s         | 6         | 0.4%    |
| Unknown                                                       | 6         | 0.4%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                          | 5         | 0.34%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s          | 5         | 0.34%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 5         | 0.34%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 5         | 0.34%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 5         | 0.34%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s     | 5         | 0.34%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s         | 5         | 0.34%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 5         | 0.34%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s        | 5         | 0.34%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s         | 5         | 0.34%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s          | 5         | 0.34%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s           | 5         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 547       | 45.77%  |
| DDR3    | 415       | 34.73%  |
| Unknown | 61        | 5.1%    |
| LPDDR3  | 59        | 4.94%   |
| DDR2    | 48        | 4.02%   |
| LPDDR4  | 26        | 2.18%   |
| SDRAM   | 17        | 1.42%   |
| DDR     | 9         | 0.75%   |
| DDR5    | 6         | 0.5%    |
| LPDDR5  | 5         | 0.42%   |
| DRAM    | 2         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 567       | 47.61%  |
| DIMM         | 521       | 43.74%  |
| Row Of Chips | 91        | 7.64%   |
| Chip         | 8         | 0.67%   |
| FB-DIMM      | 2         | 0.17%   |
| Unknown      | 2         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 494       | 38.84%  |
| 4096  | 343       | 26.97%  |
| 16384 | 197       | 15.49%  |
| 2048  | 161       | 12.66%  |
| 32768 | 36        | 2.83%   |
| 1024  | 31        | 2.44%   |
| 512   | 7         | 0.55%   |
| 65536 | 2         | 0.16%   |
| 256   | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 269       | 20.71%  |
| 2667    | 180       | 13.86%  |
| 3200    | 132       | 10.16%  |
| 1333    | 109       | 8.39%   |
| 2133    | 87        | 6.7%    |
| 2400    | 74        | 5.7%    |
| 3600    | 50        | 3.85%   |
| 1334    | 43        | 3.31%   |
| 800     | 41        | 3.16%   |
| 1867    | 32        | 2.46%   |
| 667     | 32        | 2.46%   |
| 1067    | 21        | 1.62%   |
| 3400    | 18        | 1.39%   |
| 3000    | 18        | 1.39%   |
| Unknown | 18        | 1.39%   |
| 4267    | 14        | 1.08%   |
| 3466    | 14        | 1.08%   |
| 1066    | 13        | 1%      |
| 1866    | 11        | 0.85%   |
| 4800    | 9         | 0.69%   |
| 3266    | 9         | 0.69%   |
| 3733    | 8         | 0.62%   |
| 2666    | 8         | 0.62%   |
| 8400    | 7         | 0.54%   |
| 2933    | 7         | 0.54%   |
| 3866    | 6         | 0.46%   |
| 6400    | 5         | 0.38%   |
| 3800    | 5         | 0.38%   |
| 3100    | 5         | 0.38%   |
| 2800    | 5         | 0.38%   |
| 2048    | 5         | 0.38%   |
| 400     | 5         | 0.38%   |
| 533     | 4         | 0.31%   |
| 4000    | 3         | 0.23%   |
| 3500    | 3         | 0.23%   |
| 1800    | 3         | 0.23%   |
| 933     | 3         | 0.23%   |
| 333     | 3         | 0.23%   |
| 4199    | 2         | 0.15%   |
| 4133    | 2         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Brother Industries     | 25        | 25.25%  |
| Hewlett-Packard        | 24        | 24.24%  |
| Canon                  | 16        | 16.16%  |
| Fuji Xerox             | 7         | 7.07%   |
| Samsung Electronics    | 6         | 6.06%   |
| Prolific Technology    | 6         | 6.06%   |
| Seiko Epson            | 5         | 5.05%   |
| Lexmark International  | 2         | 2.02%   |
| Dymo-CoStar            | 2         | 2.02%   |
| Zebra                  | 1         | 1.01%   |
| Xerox                  | 1         | 1.01%   |
| Ricoh                  | 1         | 1.01%   |
| Kyocera                | 1         | 1.01%   |
| Custom Engineering SPA | 1         | 1.01%   |
| BIXOLON                | 1         | 1.01%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| HP DeskJet 2620 All-in-One Printer           | 8         | 7.92%   |
| Prolific PL2305 Parallel Port                | 6         | 5.94%   |
| HP DeskJet 2130 series                       | 4         | 3.96%   |
| Brother HL-2130 series                       | 4         | 3.96%   |
| Fuji Xerox DocuPrint CM215 fw                | 3         | 2.97%   |
| Brother HL-1110 series                       | 3         | 2.97%   |
| HP ENVY 5000 series                          | 2         | 1.98%   |
| HP DeskJet F2100 Printer series              | 2         | 1.98%   |
| Canon TR8500 series                          | 2         | 1.98%   |
| Canon PIXMA MX920 Series                     | 2         | 1.98%   |
| Canon PIXMA MG2500 Series                    | 2         | 1.98%   |
| Canon MG5600 series                          | 2         | 1.98%   |
| Brother MFC-L8690CDW series                  | 2         | 1.98%   |
| Brother HL-L3230CDW series                   | 2         | 1.98%   |
| Zebra ZTC LP2844-Z-200dpi                    | 1         | 0.99%   |
| Xerox Phaser 8400N                           | 1         | 0.99%   |
| Seiko Epson XP-4100 Series                   | 1         | 0.99%   |
| Seiko Epson XP-243 245 247 Series            | 1         | 0.99%   |
| Seiko Epson WF-5190 Series                   | 1         | 0.99%   |
| Seiko Epson TM-T20                           | 1         | 0.99%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.99%   |
| Samsung ML-2010P Mono Laser Printer          | 1         | 0.99%   |
| Samsung ML-1865                              | 1         | 0.99%   |
| Samsung ML-1640 Series Laser Printer         | 1         | 0.99%   |
| Samsung ML-1450                              | 1         | 0.99%   |
| Samsung M267x 287x Series                    | 1         | 0.99%   |
| Samsung M2020 Series                         | 1         | 0.99%   |
| Ricoh Printer                                | 1         | 0.99%   |
| Lexmark International Lexmark E260dn         | 1         | 0.99%   |
| Lexmark International CX410de                | 1         | 0.99%   |
| Kyocera FS-1100                              | 1         | 0.99%   |
| HP OfficeJet 5200 series                     | 1         | 0.99%   |
| HP LaserJet Professional P 1102w             | 1         | 0.99%   |
| HP ENVY Photo 7100 series                    | 1         | 0.99%   |
| HP ENVY 4520 series                          | 1         | 0.99%   |
| HP DeskJet 3630 series                       | 1         | 0.99%   |
| HP Deskjet 3520 series                       | 1         | 0.99%   |
| HP DeskJet 2300 series                       | 1         | 0.99%   |
| HP Deskjet 1050 J410                         | 1         | 0.99%   |
| Fuji Xerox DocuPrint P355 d                  | 1         | 0.99%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 9         | 60%     |
| Seiko Epson    | 4         | 26.67%  |
| Syscan         | 1         | 6.67%   |
| Mustek Systems | 1         | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                                  | 2         | 13.33%  |
| Canon CanoScan LiDE 210                                 | 2         | 13.33%  |
| Syscan TravelScan 460/464                               | 1         | 6.67%   |
| Seiko Epson Scanner                                     | 1         | 6.67%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1         | 6.67%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 6.67%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]       | 1         | 6.67%   |
| Mustek Systems BearPaw 2448 TA Plus                     | 1         | 6.67%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 6.67%   |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 6.67%   |
| Canon CanoScan LiDE 220                                 | 1         | 6.67%   |
| Canon CanoScan LiDE 200                                 | 1         | 6.67%   |
| Canon CanoScan LiDE 110                                 | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 307       | 21.87%  |
| Logitech                               | 133       | 9.47%   |
| Microdia                               | 116       | 8.26%   |
| Realtek Semiconductor                  | 111       | 7.91%   |
| Sunplus Innovation Technology          | 100       | 7.12%   |
| Apple                                  | 96        | 6.84%   |
| IMC Networks                           | 87        | 6.2%    |
| Acer                                   | 71        | 5.06%   |
| Quanta                                 | 49        | 3.49%   |
| Suyin                                  | 47        | 3.35%   |
| Cheng Uei Precision Industry (Foxlink) | 47        | 3.35%   |
| Microsoft                              | 34        | 2.42%   |
| Lite-On Technology                     | 26        | 1.85%   |
| Samsung Electronics                    | 20        | 1.42%   |
| Syntek                                 | 18        | 1.28%   |
| Luxvisions Innotech Limited            | 11        | 0.78%   |
| Silicon Motion                         | 10        | 0.71%   |
| Importek                               | 10        | 0.71%   |
| Ricoh                                  | 9         | 0.64%   |
| Lenovo                                 | 9         | 0.64%   |
| Alcor Micro                            | 8         | 0.57%   |
| Primax Electronics                     | 7         | 0.5%    |
| GEMBIRD                                | 7         | 0.5%    |
| Razer USA                              | 5         | 0.36%   |
| Generalplus Technology                 | 5         | 0.36%   |
| OmniVision Technologies                | 4         | 0.28%   |
| Magic Control Technology               | 4         | 0.28%   |
| LG Electronics                         | 4         | 0.28%   |
| Genesys Logic                          | 4         | 0.28%   |
| Cubeternet                             | 4         | 0.28%   |
| Z-Star Microelectronics                | 3         | 0.21%   |
| Sonix Technology                       | 3         | 0.21%   |
| DigiTech                               | 3         | 0.21%   |
| ALi                                    | 3         | 0.21%   |
| Unknown                                | 2         | 0.14%   |
| SunplusIT                              | 2         | 0.14%   |
| Asuscom Network                        | 2         | 0.14%   |
| Tobii Technology AB                    | 1         | 0.07%   |
| T & A Mobile Phones                    | 1         | 0.07%   |
| Sunplus Technology                     | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 55        | 3.84%   |
| Chicony Integrated Camera                               | 39        | 2.72%   |
| Realtek Integrated_Webcam_HD                            | 30        | 2.09%   |
| Apple FaceTime HD Camera (Built-in)                     | 30        | 2.09%   |
| IMC Networks Integrated Camera                          | 26        | 1.82%   |
| Sunplus Integrated_Webcam_HD                            | 24        | 1.68%   |
| Chicony TOSHIBA Web Camera - HD                         | 24        | 1.68%   |
| Chicony HD WebCam                                       | 24        | 1.68%   |
| Apple Built-in iSight                                   | 24        | 1.68%   |
| Apple iPhone 5/5C/5S/6/SE                               | 22        | 1.54%   |
| Acer Integrated Camera                                  | 21        | 1.47%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 20        | 1.4%    |
| Logitech HD Pro Webcam C920                             | 19        | 1.33%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 17        | 1.19%   |
| Logitech Webcam C270                                    | 15        | 1.05%   |
| Chicony HP TrueVision HD Camera                         | 14        | 0.98%   |
| Chicony HP HD Camera                                    | 14        | 0.98%   |
| Syntek Integrated Camera                                | 13        | 0.91%   |
| Chicony USB 2.0 Camera                                  | 13        | 0.91%   |
| Chicony HP Truevision HD                                | 13        | 0.91%   |
| Apple FaceTime HD Camera                                | 13        | 0.91%   |
| Sunplus HD WebCam                                       | 12        | 0.84%   |
| Chicony HD User Facing                                  | 12        | 0.84%   |
| Realtek USB Camera                                      | 11        | 0.77%   |
| Microsoft LifeCam HD-3000                               | 11        | 0.77%   |
| Logitech Webcam C930e                                   | 11        | 0.77%   |
| Lite-On Integrated Camera                               | 11        | 0.77%   |
| Chicony USB2.0 Camera                                   | 11        | 0.77%   |
| Acer EasyCamera                                         | 11        | 0.77%   |
| Quanta HD User Facing                                   | 10        | 0.7%    |
| Logitech C922 Pro Stream Webcam                         | 10        | 0.7%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 10        | 0.7%    |
| Microdia Integrated Webcam                              | 9         | 0.63%   |
| Logitech Webcam C170                                    | 9         | 0.63%   |
| Chicony EasyCamera                                      | 9         | 0.63%   |
| Chicony CNF9055 Toshiba Webcam                          | 9         | 0.63%   |
| Suyin HP Truevision HD                                  | 8         | 0.56%   |
| Quanta HP TrueVision HD Camera                          | 8         | 0.56%   |
| Microdia Integrated_Webcam_FHD                          | 8         | 0.56%   |
| Logitech HD Webcam C910                                 | 8         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 106       | 40%     |
| Synaptics                  | 67        | 25.28%  |
| Shenzhen Goodix Technology | 30        | 11.32%  |
| LighTuning Technology      | 18        | 6.79%   |
| AuthenTec                  | 14        | 5.28%   |
| Upek                       | 12        | 4.53%   |
| Elan Microelectronics      | 12        | 4.53%   |
| STMicroelectronics         | 6         | 2.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 19        | 7.17%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 18        | 6.79%   |
| Unknown                                                                    | 18        | 6.79%   |
| Shenzhen Goodix Fingerprint Reader                                         | 14        | 5.28%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 12        | 4.53%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 4.53%   |
| Synaptics  WBDI                                                            | 10        | 3.77%   |
| Validity Sensors VFS491                                                    | 9         | 3.4%    |
| Shenzhen Goodix  Fingerprint Device                                        | 9         | 3.4%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 8         | 3.02%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 3.02%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 3.02%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 3.02%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 3.02%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 2.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 7         | 2.64%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 2.64%   |
| Elan ELAN:Fingerprint                                                      | 7         | 2.64%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 2.26%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 2.26%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 2.26%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.89%   |
| Synaptics WBDI Device                                                      | 5         | 1.89%   |
| LighTuning EgisTec_ES603                                                   | 5         | 1.89%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.89%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 1.51%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 1.51%   |
| AuthenTec AES1600                                                          | 4         | 1.51%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.13%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.13%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.13%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 1.13%   |
| AuthenTec AES2810                                                          | 2         | 0.75%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.38%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.38%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.38%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 29        | 61.7%   |
| Alcor Micro           | 11        | 23.4%   |
| Upek                  | 2         | 4.26%   |
| O2 Micro              | 2         | 4.26%   |
| Lenovo                | 2         | 4.26%   |
| Advanced Card Systems | 1         | 2.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 29.79%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 23.4%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 10.64%  |
| Broadcom 5880                                                                | 5         | 10.64%  |
| Broadcom 58200                                                               | 5         | 10.64%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 4.26%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 4.26%   |
| Advanced Card Systems ACR122U                                                | 1         | 2.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1873      | 70.79%  |
| 1     | 641       | 24.23%  |
| 2     | 101       | 3.82%   |
| 3     | 22        | 0.83%   |
| 4     | 8         | 0.3%    |
| 7     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 264       | 29.66%  |
| Graphics card            | 193       | 21.69%  |
| Net/wireless             | 139       | 15.62%  |
| Multimedia controller    | 49        | 5.51%   |
| Chipcard                 | 43        | 4.83%   |
| Communication controller | 40        | 4.49%   |
| Camera                   | 28        | 3.15%   |
| Bluetooth                | 28        | 3.15%   |
| Unassigned class         | 25        | 2.81%   |
| Sound                    | 15        | 1.69%   |
| Net/ethernet             | 15        | 1.69%   |
| Storage                  | 10        | 1.12%   |
| Modem                    | 8         | 0.9%    |
| Dvb card                 | 8         | 0.9%    |
| Network                  | 7         | 0.79%   |
| Card reader              | 7         | 0.79%   |
| Video                    | 2         | 0.22%   |
| Storage/raid             | 2         | 0.22%   |
| Storage/ata              | 2         | 0.22%   |
| Unclassified device      | 1         | 0.11%   |
| Tv card                  | 1         | 0.11%   |
| Storage/nvme             | 1         | 0.11%   |
| Storage/ide              | 1         | 0.11%   |
| Firewire controller      | 1         | 0.11%   |

