Linux in Bosnia and Herzegovina - Tested Hardware & Statistics
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Bosnia and Herzegovina.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Bosnia_and_Herzegovina/Desktop/README.md) and [notebooks](/Location/Bosnia_and_Herzegovina/Notebook/README.md).

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

Total: 182

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [512acddb70](https://linux-hardware.org/?probe=512acddb70) | Oct 30, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [73799d57b3](https://linux-hardware.org/?probe=73799d57b3) | Oct 22, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [bef64e98af](https://linux-hardware.org/?probe=bef64e98af) | Oct 21, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [4241008f07](https://linux-hardware.org/?probe=4241008f07) | Oct 16, 2022 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [b7a5ca0670](https://linux-hardware.org/?probe=b7a5ca0670) | Oct 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [03a74f0a7b](https://linux-hardware.org/?probe=03a74f0a7b) | Oct 06, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [bdcb5090f0](https://linux-hardware.org/?probe=bdcb5090f0) | Sep 26, 2022 |
| HP            | ProBook 6560b               | Notebook    | [96637a94a6](https://linux-hardware.org/?probe=96637a94a6) | Sep 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [bbc3c68696](https://linux-hardware.org/?probe=bbc3c68696) | Sep 14, 2022 |
| ASRock        | H61M-HVGS                   | Desktop     | [f646dceb7c](https://linux-hardware.org/?probe=f646dceb7c) | Aug 10, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [eeb9068dca](https://linux-hardware.org/?probe=eeb9068dca) | Jul 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [fc99c10d57](https://linux-hardware.org/?probe=fc99c10d57) | Jul 13, 2022 |
| Dell          | Latitude E6410              | Notebook    | [cde668d556](https://linux-hardware.org/?probe=cde668d556) | Jul 12, 2022 |
| Dell          | Latitude E6410              | Notebook    | [a15b38ef5e](https://linux-hardware.org/?probe=a15b38ef5e) | Jul 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [b7d2767b67](https://linux-hardware.org/?probe=b7d2767b67) | Jun 23, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [cf8d972149](https://linux-hardware.org/?probe=cf8d972149) | Jun 09, 2022 |
| Lenovo        | ThinkPad X301 277418G       | Notebook    | [0d9a530751](https://linux-hardware.org/?probe=0d9a530751) | May 24, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [654d58c254](https://linux-hardware.org/?probe=654d58c254) | May 07, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [3fff5f40c3](https://linux-hardware.org/?probe=3fff5f40c3) | Apr 24, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [090b87ad9b](https://linux-hardware.org/?probe=090b87ad9b) | Apr 24, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [26ac9971a3](https://linux-hardware.org/?probe=26ac9971a3) | Apr 13, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [f26ffb9177](https://linux-hardware.org/?probe=f26ffb9177) | Apr 11, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [636817086a](https://linux-hardware.org/?probe=636817086a) | Apr 08, 2022 |
| Lenovo        | ThinkPad T420 4180WAP       | Notebook    | [1e90438c11](https://linux-hardware.org/?probe=1e90438c11) | Apr 06, 2022 |
| Lenovo        | ThinkPad T420 4180WAP       | Notebook    | [f72ea7fb49](https://linux-hardware.org/?probe=f72ea7fb49) | Apr 06, 2022 |
| HP            | 0A54h                       | Desktop     | [0efed10555](https://linux-hardware.org/?probe=0efed10555) | Mar 29, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [076c89e071](https://linux-hardware.org/?probe=076c89e071) | Mar 22, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [565a9dc93c](https://linux-hardware.org/?probe=565a9dc93c) | Mar 22, 2022 |
| Dell          | Inspiron 5323               | Notebook    | [0f8594072f](https://linux-hardware.org/?probe=0f8594072f) | Feb 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d606848435](https://linux-hardware.org/?probe=d606848435) | Feb 27, 2022 |
| Toshiba       | Satellite C850-1GF          | Notebook    | [9ace91eeb9](https://linux-hardware.org/?probe=9ace91eeb9) | Feb 24, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [456ab60c06](https://linux-hardware.org/?probe=456ab60c06) | Feb 22, 2022 |
| Lenovo        | ThinkPad T430 2349G2G       | Notebook    | [14f905c347](https://linux-hardware.org/?probe=14f905c347) | Feb 19, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [95ccf112af](https://linux-hardware.org/?probe=95ccf112af) | Feb 14, 2022 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [bc32230a7f](https://linux-hardware.org/?probe=bc32230a7f) | Feb 09, 2022 |
| HP            | 550                         | Notebook    | [7e286dd830](https://linux-hardware.org/?probe=7e286dd830) | Feb 08, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [b09926b5fc](https://linux-hardware.org/?probe=b09926b5fc) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [de0a100d06](https://linux-hardware.org/?probe=de0a100d06) | Jan 24, 2022 |
| HP            | 3396                        | Desktop     | [97720dddd1](https://linux-hardware.org/?probe=97720dddd1) | Jan 10, 2022 |
| MSI           | B150 GAMING M3              | Desktop     | [3514e82b43](https://linux-hardware.org/?probe=3514e82b43) | Jan 07, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [1a04f6b354](https://linux-hardware.org/?probe=1a04f6b354) | Dec 26, 2021 |
| MSI           | MS-AA1511                   | All in one  | [ef477f6784](https://linux-hardware.org/?probe=ef477f6784) | Dec 24, 2021 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [531a29caeb](https://linux-hardware.org/?probe=531a29caeb) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f6f5b0f374](https://linux-hardware.org/?probe=f6f5b0f374) | Dec 01, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [b99fd7100e](https://linux-hardware.org/?probe=b99fd7100e) | Nov 28, 2021 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [a86286c5da](https://linux-hardware.org/?probe=a86286c5da) | Nov 24, 2021 |
| Acer          | Okinawa                     | Notebook    | [2953f32ed9](https://linux-hardware.org/?probe=2953f32ed9) | Nov 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [9f4e86b760](https://linux-hardware.org/?probe=9f4e86b760) | Nov 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [07d8d5b1ae](https://linux-hardware.org/?probe=07d8d5b1ae) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6c7411070d](https://linux-hardware.org/?probe=6c7411070d) | Nov 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [52eb9930ad](https://linux-hardware.org/?probe=52eb9930ad) | Nov 14, 2021 |
| Medion        | MS-7366                     | Desktop     | [da9961f1ee](https://linux-hardware.org/?probe=da9961f1ee) | Nov 04, 2021 |
| HP            | ProBook 470 G0              | Notebook    | [e2c740a317](https://linux-hardware.org/?probe=e2c740a317) | Nov 01, 2021 |
| Acer          | AO725                       | Notebook    | [f6819a066a](https://linux-hardware.org/?probe=f6819a066a) | Oct 31, 2021 |
| ASUSTek       | X540SAA                     | Notebook    | [2ce3b8f43c](https://linux-hardware.org/?probe=2ce3b8f43c) | Oct 27, 2021 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [5d292b28e6](https://linux-hardware.org/?probe=5d292b28e6) | Oct 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [63b6ade950](https://linux-hardware.org/?probe=63b6ade950) | Sep 13, 2021 |
| Dell          | G3 3590                     | Notebook    | [caaab11f09](https://linux-hardware.org/?probe=caaab11f09) | Sep 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [1f7bf82ef4](https://linux-hardware.org/?probe=1f7bf82ef4) | Aug 10, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| eMachines     | eME728                      | Notebook    | [30f7a1ede8](https://linux-hardware.org/?probe=30f7a1ede8) | Jul 27, 2021 |
| eMachines     | eME728                      | Notebook    | [41f6735286](https://linux-hardware.org/?probe=41f6735286) | Jul 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fb1170efa6](https://linux-hardware.org/?probe=fb1170efa6) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [19f5976aa3](https://linux-hardware.org/?probe=19f5976aa3) | Jul 25, 2021 |
| HP            | 1497                        | Desktop     | [e68557fd01](https://linux-hardware.org/?probe=e68557fd01) | Jul 07, 2021 |
| Dell          | Latitude E7470              | Notebook    | [09cc29de1a](https://linux-hardware.org/?probe=09cc29de1a) | Jun 27, 2021 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [bc2d293d15](https://linux-hardware.org/?probe=bc2d293d15) | Jun 18, 2021 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [ef21ac93c3](https://linux-hardware.org/?probe=ef21ac93c3) | Jun 18, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [c425b0dc44](https://linux-hardware.org/?probe=c425b0dc44) | Jun 01, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [035b3cdc60](https://linux-hardware.org/?probe=035b3cdc60) | May 31, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e9148788a7](https://linux-hardware.org/?probe=e9148788a7) | May 30, 2021 |
| Acer          | Aspire 8950G                | Notebook    | [7955f23581](https://linux-hardware.org/?probe=7955f23581) | May 18, 2021 |
| HP            | ProBook 4710s               | Notebook    | [7c743eff61](https://linux-hardware.org/?probe=7c743eff61) | May 17, 2021 |
| HP            | ProBook 4710s               | Notebook    | [e0c66c6a52](https://linux-hardware.org/?probe=e0c66c6a52) | May 16, 2021 |
| ASRock        | H61M-HVGS                   | Desktop     | [3f3962df59](https://linux-hardware.org/?probe=3f3962df59) | May 16, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [10dd12b38c](https://linux-hardware.org/?probe=10dd12b38c) | May 15, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [30aeb41807](https://linux-hardware.org/?probe=30aeb41807) | May 14, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [57a865992b](https://linux-hardware.org/?probe=57a865992b) | May 10, 2021 |
| HP            | ProBook 470 G2              | Notebook    | [fc85d1a891](https://linux-hardware.org/?probe=fc85d1a891) | May 08, 2021 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [19df1ffb17](https://linux-hardware.org/?probe=19df1ffb17) | Apr 27, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [dba745086d](https://linux-hardware.org/?probe=dba745086d) | Apr 09, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [54a2c5f349](https://linux-hardware.org/?probe=54a2c5f349) | Apr 09, 2021 |
| HP            | EliteBook 850 G3            | Notebook    | [f4c0a5e9a8](https://linux-hardware.org/?probe=f4c0a5e9a8) | Mar 25, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [bee3da385c](https://linux-hardware.org/?probe=bee3da385c) | Mar 23, 2021 |
| HP            | 198E                        | Desktop     | [85ba542969](https://linux-hardware.org/?probe=85ba542969) | Mar 10, 2021 |
| HP            | 198E                        | Desktop     | [8a79f9e398](https://linux-hardware.org/?probe=8a79f9e398) | Mar 10, 2021 |
| Dell          | G3 3590                     | Notebook    | [3576fa9deb](https://linux-hardware.org/?probe=3576fa9deb) | Feb 26, 2021 |
| Dell          | G3 3590                     | Notebook    | [c5592b0bc0](https://linux-hardware.org/?probe=c5592b0bc0) | Feb 26, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [9b37eaa9f8](https://linux-hardware.org/?probe=9b37eaa9f8) | Feb 02, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [7d18048067](https://linux-hardware.org/?probe=7d18048067) | Jan 26, 2021 |
| Acer          | AO756                       | Notebook    | [d734ecb46e](https://linux-hardware.org/?probe=d734ecb46e) | Jan 05, 2021 |
| Acer          | AO756                       | Notebook    | [be84cd377c](https://linux-hardware.org/?probe=be84cd377c) | Jan 05, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [4914bab0b2](https://linux-hardware.org/?probe=4914bab0b2) | Jan 03, 2021 |
| HP            | 1496                        | Desktop     | [7d2d9cd210](https://linux-hardware.org/?probe=7d2d9cd210) | Dec 22, 2020 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [1cfdffe4cb](https://linux-hardware.org/?probe=1cfdffe4cb) | Dec 22, 2020 |
| Acer          | Aspire 5349                 | Notebook    | [e52d1fe780](https://linux-hardware.org/?probe=e52d1fe780) | Dec 01, 2020 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | Notebook    | [3cd2e0b42b](https://linux-hardware.org/?probe=3cd2e0b42b) | Nov 29, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [d5cb1091b6](https://linux-hardware.org/?probe=d5cb1091b6) | Nov 21, 2020 |
| ASUSTek       | H97-PRO                     | Desktop     | [5532ead8e7](https://linux-hardware.org/?probe=5532ead8e7) | Nov 21, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [092c6bbcaa](https://linux-hardware.org/?probe=092c6bbcaa) | Nov 17, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [2fbaebc961](https://linux-hardware.org/?probe=2fbaebc961) | Nov 16, 2020 |
| Acer          | Aspire 8950G                | Notebook    | [47e8b425f8](https://linux-hardware.org/?probe=47e8b425f8) | Nov 15, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [986307a038](https://linux-hardware.org/?probe=986307a038) | Nov 15, 2020 |
| Acer          | Aspire 8950G                | Notebook    | [bae73407d5](https://linux-hardware.org/?probe=bae73407d5) | Nov 11, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [78a6736f7b](https://linux-hardware.org/?probe=78a6736f7b) | Nov 07, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [61f58ab0e6](https://linux-hardware.org/?probe=61f58ab0e6) | Nov 07, 2020 |
| HP            | Laptop 15-rb0xx             | Notebook    | [aaa00c2c2f](https://linux-hardware.org/?probe=aaa00c2c2f) | Nov 05, 2020 |
| HP            | 3032h                       | Desktop     | [63d3c61c19](https://linux-hardware.org/?probe=63d3c61c19) | Nov 03, 2020 |
| HP            | 3032h                       | Desktop     | [d8cfe55684](https://linux-hardware.org/?probe=d8cfe55684) | Nov 03, 2020 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [1f8e16d74f](https://linux-hardware.org/?probe=1f8e16d74f) | Oct 25, 2020 |
| Acer          | Aspire 7741                 | Notebook    | [a87b79b8e8](https://linux-hardware.org/?probe=a87b79b8e8) | Oct 01, 2020 |
| Lenovo        | Legion 7 15IMHg05 81YU      | Notebook    | [e8a84ca3be](https://linux-hardware.org/?probe=e8a84ca3be) | Oct 01, 2020 |
| ASUSTek       | Z170-P                      | Desktop     | [188328b998](https://linux-hardware.org/?probe=188328b998) | Sep 27, 2020 |
| HP            | 8446                        | All in one  | [a12a0781b1](https://linux-hardware.org/?probe=a12a0781b1) | Sep 25, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [35560a3a70](https://linux-hardware.org/?probe=35560a3a70) | Sep 16, 2020 |
| Unknown       | Unknown                     | Notebook    | [c24817ee80](https://linux-hardware.org/?probe=c24817ee80) | Sep 15, 2020 |
| ECS           | G31T-M7                     | Desktop     | [70c5208ec6](https://linux-hardware.org/?probe=70c5208ec6) | Sep 13, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2726ac41f8](https://linux-hardware.org/?probe=2726ac41f8) | Sep 07, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [92e454c839](https://linux-hardware.org/?probe=92e454c839) | Sep 07, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cac26af0fc](https://linux-hardware.org/?probe=cac26af0fc) | Sep 07, 2020 |
| ASUSTek       | X75VBP                      | Notebook    | [2556ede7e8](https://linux-hardware.org/?probe=2556ede7e8) | Aug 14, 2020 |
| Dell          | 0M858N A01                  | Desktop     | [5b7ae4f768](https://linux-hardware.org/?probe=5b7ae4f768) | Aug 13, 2020 |
| Lenovo        | G505 20240                  | Notebook    | [828da8bdbe](https://linux-hardware.org/?probe=828da8bdbe) | Aug 10, 2020 |
| HP            | ENVY 6                      | Notebook    | [a703adc052](https://linux-hardware.org/?probe=a703adc052) | Aug 08, 2020 |
| HP            | ENVY 6                      | Notebook    | [d64f914478](https://linux-hardware.org/?probe=d64f914478) | Aug 08, 2020 |
| Dell          | 0RF703                      | Desktop     | [e23b194d28](https://linux-hardware.org/?probe=e23b194d28) | Jul 25, 2020 |
| ASUSTek       | Z97-P                       | Desktop     | [d0375fe030](https://linux-hardware.org/?probe=d0375fe030) | Jul 15, 2020 |
| Acer          | Aspire M1200                | Desktop     | [9311c4fa37](https://linux-hardware.org/?probe=9311c4fa37) | Jun 27, 2020 |
| Acer          | Aspire M1200                | Desktop     | [8d9a1aefd5](https://linux-hardware.org/?probe=8d9a1aefd5) | Jun 27, 2020 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [1a6102d9f3](https://linux-hardware.org/?probe=1a6102d9f3) | Jun 17, 2020 |
| HP            | ENVY TS 15                  | Notebook    | [bd072980c8](https://linux-hardware.org/?probe=bd072980c8) | Jun 02, 2020 |
| NEC Comput... | VERSAP550 NN951700753       | Notebook    | [ccd46d5757](https://linux-hardware.org/?probe=ccd46d5757) | May 29, 2020 |
| Acer          | Aspire M1200                | Desktop     | [2cbc71cc6f](https://linux-hardware.org/?probe=2cbc71cc6f) | May 24, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [05094356e1](https://linux-hardware.org/?probe=05094356e1) | May 22, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [9f6782d583](https://linux-hardware.org/?probe=9f6782d583) | May 14, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [a8fb846d8b](https://linux-hardware.org/?probe=a8fb846d8b) | May 14, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [6935018ae2](https://linux-hardware.org/?probe=6935018ae2) | May 14, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [31f5dfadff](https://linux-hardware.org/?probe=31f5dfadff) | May 04, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [c668c517d8](https://linux-hardware.org/?probe=c668c517d8) | Apr 24, 2020 |
| HP            | Compaq CQ58                 | Notebook    | [82172cc7b5](https://linux-hardware.org/?probe=82172cc7b5) | Apr 21, 2020 |
| ASUSTek       | X550ZE                      | Notebook    | [c3165ccdcd](https://linux-hardware.org/?probe=c3165ccdcd) | Apr 21, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [4e3e7a0cca](https://linux-hardware.org/?probe=4e3e7a0cca) | Apr 20, 2020 |
| HP            | 255 G2                      | Notebook    | [2e24d05e40](https://linux-hardware.org/?probe=2e24d05e40) | Apr 19, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [6e83174540](https://linux-hardware.org/?probe=6e83174540) | Apr 18, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | Notebook    | [878a9628b9](https://linux-hardware.org/?probe=878a9628b9) | Apr 18, 2020 |
| Gigabyte      | nForce                      | Desktop     | [46e8276491](https://linux-hardware.org/?probe=46e8276491) | Apr 03, 2020 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [fa5624c697](https://linux-hardware.org/?probe=fa5624c697) | Mar 27, 2020 |
| Acer          | Aspire 9300                 | Notebook    | [de8a03d251](https://linux-hardware.org/?probe=de8a03d251) | Mar 26, 2020 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [0dbb663114](https://linux-hardware.org/?probe=0dbb663114) | Mar 26, 2020 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [ce73a67dba](https://linux-hardware.org/?probe=ce73a67dba) | Mar 26, 2020 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [84bed079c2](https://linux-hardware.org/?probe=84bed079c2) | Mar 23, 2020 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [10793053f1](https://linux-hardware.org/?probe=10793053f1) | Mar 23, 2020 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [e8e644cb4c](https://linux-hardware.org/?probe=e8e644cb4c) | Mar 09, 2020 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [7121b34b5e](https://linux-hardware.org/?probe=7121b34b5e) | Feb 21, 2020 |
| ASUSTek       | X751MD                      | Notebook    | [cdb3c77ebd](https://linux-hardware.org/?probe=cdb3c77ebd) | Feb 07, 2020 |
| MSI           | GF615M-P33                  | Desktop     | [34605f2e7f](https://linux-hardware.org/?probe=34605f2e7f) | Feb 06, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [815e8a2b8e](https://linux-hardware.org/?probe=815e8a2b8e) | Jan 04, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [64c7222709](https://linux-hardware.org/?probe=64c7222709) | Dec 22, 2019 |
| Dell          | 0RF703                      | Desktop     | [3cc8664913](https://linux-hardware.org/?probe=3cc8664913) | Nov 09, 2019 |
| Pegatron      | Eureka3                     | Desktop     | [5d42e73d08](https://linux-hardware.org/?probe=5d42e73d08) | Oct 20, 2019 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [5dd5ad47e3](https://linux-hardware.org/?probe=5dd5ad47e3) | Sep 06, 2019 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [8bce9c814b](https://linux-hardware.org/?probe=8bce9c814b) | Sep 05, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1db130e5eb](https://linux-hardware.org/?probe=1db130e5eb) | Aug 30, 2019 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [761fad2410](https://linux-hardware.org/?probe=761fad2410) | Aug 06, 2019 |
| Dell          | 0RF703                      | Desktop     | [e97de552d8](https://linux-hardware.org/?probe=e97de552d8) | Jul 29, 2019 |
| Dell          | 0RF703                      | Desktop     | [08019d8b5f](https://linux-hardware.org/?probe=08019d8b5f) | Jul 29, 2019 |
| Dell          | 0MM599                      | Desktop     | [0b9fef01ec](https://linux-hardware.org/?probe=0b9fef01ec) | Jun 19, 2019 |
| Dell          | 0MM599                      | Desktop     | [8376d2c77c](https://linux-hardware.org/?probe=8376d2c77c) | Jun 19, 2019 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [aa5f7a836b](https://linux-hardware.org/?probe=aa5f7a836b) | May 04, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3aed29ae25](https://linux-hardware.org/?probe=3aed29ae25) | Apr 27, 2019 |
| HP            | 0A64h                       | Desktop     | [ab563902ff](https://linux-hardware.org/?probe=ab563902ff) | Apr 22, 2019 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [3ce6d97f47](https://linux-hardware.org/?probe=3ce6d97f47) | Apr 21, 2019 |
| Gigabyte      | Z390 UD                     | Desktop     | [48041296ca](https://linux-hardware.org/?probe=48041296ca) | Mar 15, 2019 |
| Sony          | VGN-BX41VN                  | Notebook    | [3a190d628a](https://linux-hardware.org/?probe=3a190d628a) | Dec 02, 2018 |
| Sony          | VGN-BX41VN                  | Notebook    | [7f3d5f5bf2](https://linux-hardware.org/?probe=7f3d5f5bf2) | Dec 02, 2018 |
| Acer          | Aspire A315-31              | Notebook    | [e67c4f6668](https://linux-hardware.org/?probe=e67c4f6668) | Nov 18, 2018 |
| Acer          | Aspire A315-31              | Notebook    | [a46cebd58a](https://linux-hardware.org/?probe=a46cebd58a) | Nov 18, 2018 |
| HP            | 250 G6 Notebook PC          | Notebook    | [e8386ee291](https://linux-hardware.org/?probe=e8386ee291) | Sep 22, 2018 |
| HP            | 250 G6 Notebook PC          | Notebook    | [fa8425dcca](https://linux-hardware.org/?probe=fa8425dcca) | Aug 12, 2018 |
| ASUSTek       | M2N-SLI                     | Desktop     | [77800cbaf6](https://linux-hardware.org/?probe=77800cbaf6) | Mar 30, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 21        | 16.15%  |
| Ubuntu 18.04        | 9         | 6.92%   |
| Pop!_OS 21.04       | 6         | 4.62%   |
| OpenMandriva 4.3    | 6         | 4.62%   |
| Ubuntu 22.04        | 5         | 3.85%   |
| Manjaro             | 4         | 3.08%   |
| Linux Mint 20.2     | 4         | 3.08%   |
| Linux Mint 19.3     | 4         | 3.08%   |
| Zorin 16            | 3         | 2.31%   |
| Xubuntu 20.04       | 3         | 2.31%   |
| Ubuntu 20.10        | 3         | 2.31%   |
| Pop!_OS 20.04       | 3         | 2.31%   |
| Linux Mint 19.1     | 3         | 2.31%   |
| KDE neon 20.04      | 3         | 2.31%   |
| Fedora 32           | 3         | 2.31%   |
| Debian 10           | 3         | 2.31%   |
| ArcoLinux Rolling   | 3         | 2.31%   |
| Zorin 15            | 2         | 1.54%   |
| Ubuntu 21.10        | 2         | 1.54%   |
| Ubuntu 19.04        | 2         | 1.54%   |
| ROSA R10            | 2         | 1.54%   |
| Pop!_OS 20.10       | 2         | 1.54%   |
| Lubuntu 19.10       | 2         | 1.54%   |
| Linux Mint 20.1     | 2         | 1.54%   |
| Fedora 33           | 2         | 1.54%   |
| Endless 3.7.8       | 2         | 1.54%   |
| Xubuntu 18.04       | 1         | 0.77%   |
| Ubuntu Unity 21.10  | 1         | 0.77%   |
| Ubuntu Unity 18.04  | 1         | 0.77%   |
| Ubuntu Studio 20.04 | 1         | 0.77%   |
| Ubuntu 21.04        | 1         | 0.77%   |
| Ubuntu 16.04        | 1         | 0.77%   |
| PureOS 9.0          | 1         | 0.77%   |
| Pop!_OS 21.10       | 1         | 0.77%   |
| Manjaro 21.2.5      | 1         | 0.77%   |
| Manjaro 21.0.7      | 1         | 0.77%   |
| Manjaro 20.2        | 1         | 0.77%   |
| Lubuntu 18.04       | 1         | 0.77%   |
| Linux Mint 21       | 1         | 0.77%   |
| Linux Mint 20       | 1         | 0.77%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 41        | 32.54%  |
| Linux Mint    | 14        | 11.11%  |
| Pop!_OS       | 12        | 9.52%   |
| Manjaro       | 7         | 5.56%   |
| OpenMandriva  | 6         | 4.76%   |
| Fedora        | 6         | 4.76%   |
| Debian        | 6         | 4.76%   |
| Zorin         | 5         | 3.97%   |
| Endless       | 5         | 3.97%   |
| Xubuntu       | 4         | 3.17%   |
| KDE neon      | 4         | 3.17%   |
| Lubuntu       | 3         | 2.38%   |
| ArcoLinux     | 3         | 2.38%   |
| Ubuntu Unity  | 2         | 1.59%   |
| ROSA          | 2         | 1.59%   |
| Arch          | 2         | 1.59%   |
| Ubuntu Studio | 1         | 0.79%   |
| PureOS        | 1         | 0.79%   |
| Kubuntu       | 1         | 0.79%   |
| Elementary    | 1         | 0.79%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 6         | 4.35%   |
| 5.3.0-28-generic                | 5         | 3.62%   |
| 5.4.0-52-generic                | 4         | 2.9%    |
| 5.3.0-46-generic                | 3         | 2.17%   |
| 5.15.0-48-generic               | 3         | 2.17%   |
| 5.13.0-39-generic               | 3         | 2.17%   |
| 5.8.0-7630-generic              | 2         | 1.45%   |
| 5.8.0-59-generic                | 2         | 1.45%   |
| 5.4.0-89-generic                | 2         | 1.45%   |
| 5.4.0-67-generic                | 2         | 1.45%   |
| 5.3.0-42-generic                | 2         | 1.45%   |
| 5.15.0-50-generic               | 2         | 1.45%   |
| 5.15.0-39-generic               | 2         | 1.45%   |
| 5.15.0-25-generic               | 2         | 1.45%   |
| 5.13.0-7620-generic             | 2         | 1.45%   |
| 5.13.0-7614-generic             | 2         | 1.45%   |
| 5.11.0-40-generic               | 2         | 1.45%   |
| 5.11.0-38-generic               | 2         | 1.45%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 1.45%   |
| 4.19.0-13-amd64                 | 2         | 1.45%   |
| 4.18.0-15-generic               | 2         | 1.45%   |
| 4.15.0-94-generic               | 2         | 1.45%   |
| 4.15.0-47-generic               | 2         | 1.45%   |
| 4.15.0-20-generic               | 2         | 1.45%   |
| 5.9.8-2-MANJARO                 | 1         | 0.72%   |
| 5.9.0-3-amd64                   | 1         | 0.72%   |
| 5.8.9-200.fc32.x86_64           | 1         | 0.72%   |
| 5.8.11-200.fc32.x86_64          | 1         | 0.72%   |
| 5.8.0-53-generic                | 1         | 0.72%   |
| 5.8.0-49-generic                | 1         | 0.72%   |
| 5.8.0-44-generic                | 1         | 0.72%   |
| 5.8.0-34-generic                | 1         | 0.72%   |
| 5.8.0-26-generic                | 1         | 0.72%   |
| 5.8.0-19-generic                | 1         | 0.72%   |
| 5.7.0-1-librem5                 | 1         | 0.72%   |
| 5.6.6-300.fc32.x86_64           | 1         | 0.72%   |
| 5.4.52-1-MANJARO                | 1         | 0.72%   |
| 5.4.33-3-MANJARO                | 1         | 0.72%   |
| 5.4.23-1-MANJARO                | 1         | 0.72%   |
| 5.4.0-90-generic                | 1         | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 25        | 18.8%   |
| 5.13.0  | 13        | 9.77%   |
| 5.3.0   | 11        | 8.27%   |
| 5.8.0   | 10        | 7.52%   |
| 4.15.0  | 10        | 7.52%   |
| 5.15.0  | 9         | 6.77%   |
| 5.11.0  | 9         | 6.77%   |
| 5.16.7  | 6         | 4.51%   |
| 5.0.0   | 5         | 3.76%   |
| 4.18.0  | 4         | 3.01%   |
| 5.10.0  | 2         | 1.5%    |
| 4.9.60  | 2         | 1.5%    |
| 4.19.0  | 2         | 1.5%    |
| 5.9.8   | 1         | 0.75%   |
| 5.9.0   | 1         | 0.75%   |
| 5.8.9   | 1         | 0.75%   |
| 5.8.11  | 1         | 0.75%   |
| 5.7.0   | 1         | 0.75%   |
| 5.6.6   | 1         | 0.75%   |
| 5.4.52  | 1         | 0.75%   |
| 5.4.33  | 1         | 0.75%   |
| 5.4.23  | 1         | 0.75%   |
| 5.19.8  | 1         | 0.75%   |
| 5.16.14 | 1         | 0.75%   |
| 5.16.11 | 1         | 0.75%   |
| 5.15.23 | 1         | 0.75%   |
| 5.15.11 | 1         | 0.75%   |
| 5.15.10 | 1         | 0.75%   |
| 5.14.18 | 1         | 0.75%   |
| 5.13.9  | 1         | 0.75%   |
| 5.11.19 | 1         | 0.75%   |
| 5.11.18 | 1         | 0.75%   |
| 5.11.16 | 1         | 0.75%   |
| 5.10.60 | 1         | 0.75%   |
| 5.10.42 | 1         | 0.75%   |
| 5.10.37 | 1         | 0.75%   |
| 5.10.34 | 1         | 0.75%   |
| 4.9.0   | 1         | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 28        | 21.21%  |
| 5.13    | 14        | 10.61%  |
| 5.8     | 12        | 9.09%   |
| 5.15    | 12        | 9.09%   |
| 5.11    | 12        | 9.09%   |
| 5.3     | 11        | 8.33%   |
| 4.15    | 10        | 7.58%   |
| 5.16    | 8         | 6.06%   |
| 5.10    | 5         | 3.79%   |
| 5.0     | 5         | 3.79%   |
| 4.18    | 4         | 3.03%   |
| 4.9     | 3         | 2.27%   |
| 5.9     | 2         | 1.52%   |
| 4.19    | 2         | 1.52%   |
| 5.7     | 1         | 0.76%   |
| 5.6     | 1         | 0.76%   |
| 5.19    | 1         | 0.76%   |
| 5.14    | 1         | 0.76%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 116       | 93.55%  |
| i686    | 7         | 5.65%   |
| aarch64 | 1         | 0.81%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 65        | 50.78%  |
| XFCE       | 16        | 12.5%   |
| Unknown    | 15        | 11.72%  |
| KDE5       | 12        | 9.38%   |
| X-Cinnamon | 6         | 4.69%   |
| KDE        | 3         | 2.34%   |
| Unity      | 2         | 1.56%   |
| LXQt       | 2         | 1.56%   |
| KDE4       | 2         | 1.56%   |
| Pantheon   | 1         | 0.78%   |
| MATE       | 1         | 0.78%   |
| LXDE       | 1         | 0.78%   |
| Cinnamon   | 1         | 0.78%   |
| bspwm      | 1         | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 102       | 80.95%  |
| Wayland | 18        | 14.29%  |
| Unknown | 6         | 4.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 78        | 60.94%  |
| SDDM    | 15        | 11.72%  |
| GDM     | 12        | 9.38%   |
| LightDM | 9         | 7.03%   |
| GDM3    | 8         | 6.25%   |
| TDM     | 4         | 3.13%   |
| KDM     | 2         | 1.56%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 89        | 70.08%  |
| Unknown | 16        | 12.6%   |
| bs_BA   | 7         | 5.51%   |
| hr_HR   | 6         | 4.72%   |
| en_AU   | 2         | 1.57%   |
| C       | 2         | 1.57%   |
| sr_RS   | 1         | 0.79%   |
| it_IT   | 1         | 0.79%   |
| en_GB   | 1         | 0.79%   |
| en_CA   | 1         | 0.79%   |
| de_CH   | 1         | 0.79%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 83        | 66.4%   |
| EFI  | 42        | 33.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 102       | 82.26%  |
| Overlay | 8         | 6.45%   |
| Unknown | 7         | 5.65%   |
| Btrfs   | 6         | 4.84%   |
| Ext2    | 1         | 0.81%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 88        | 69.84%  |
| GPT     | 27        | 21.43%  |
| MBR     | 11        | 8.73%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 112       | 91.06%  |
| Yes       | 11        | 8.94%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 95        | 77.24%  |
| Yes       | 28        | 22.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 32        | 26.02%  |
| ASUSTek Computer    | 29        | 23.58%  |
| Lenovo              | 16        | 13.01%  |
| Dell                | 13        | 10.57%  |
| Acer                | 11        | 8.94%   |
| Gigabyte Technology | 5         | 4.07%   |
| MSI                 | 3         | 2.44%   |
| Fujitsu Siemens     | 2         | 1.63%   |
| Wistron             | 1         | 0.81%   |
| Toshiba             | 1         | 0.81%   |
| Sony                | 1         | 0.81%   |
| Pegatron            | 1         | 0.81%   |
| NEC Computers       | 1         | 0.81%   |
| Microsoft           | 1         | 0.81%   |
| Medion              | 1         | 0.81%   |
| HUAWEI              | 1         | 0.81%   |
| eMachines           | 1         | 0.81%   |
| ECS                 | 1         | 0.81%   |
| ASRock              | 1         | 0.81%   |
| Unknown             | 1         | 0.81%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| ASUS All Series                                   | 4         | 3.25%   |
| HP EliteBook 8460p                                | 2         | 1.63%   |
| Dell OptiPlex 745                                 | 2         | 1.63%   |
| Dell G3 3590                                      | 2         | 1.63%   |
| ASUS VivoBook_ASUSLaptop X509DA_D509DA            | 2         | 1.63%   |
| ASUS P8H61-M LX3 R2.0                             | 2         | 1.63%   |
| ASUS P5KPL-AM SE                                  | 2         | 1.63%   |
| Wistron ProLiant ML110 G5                         | 1         | 0.81%   |
| Toshiba Satellite C850-1GF                        | 1         | 0.81%   |
| Sony VGN-BX41VN                                   | 1         | 0.81%   |
| Pegatron VS170AA-UUZ p6244ch                      | 1         | 0.81%   |
| NEC Computers VERSAP550 NN951700753               | 1         | 0.81%   |
| MSI MS-AA1511                                     | 1         | 0.81%   |
| MSI MS-7978                                       | 1         | 0.81%   |
| MSI MS-7597                                       | 1         | 0.81%   |
| Microsoft Surface Pro 4                           | 1         | 0.81%   |
| Medion MS-7366                                    | 1         | 0.81%   |
| Lenovo Yoga 910-13IKB 80VF                        | 1         | 0.81%   |
| Lenovo ThinkPad X301 277418G                      | 1         | 0.81%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A7008AMZ          | 1         | 0.81%   |
| Lenovo ThinkPad T430 2349G2G                      | 1         | 0.81%   |
| Lenovo ThinkPad T420 4180WAP                      | 1         | 0.81%   |
| Lenovo ThinkPad T14s Gen 1 20UH0056SC             | 1         | 0.81%   |
| Lenovo ThinkPad S1 Yoga 20CD0038MZ                | 1         | 0.81%   |
| Lenovo ThinkPad E15 Gen 2 20TD003LSC              | 1         | 0.81%   |
| Lenovo Legion 7 15IMHg05 81YU                     | 1         | 0.81%   |
| Lenovo IdeaPad Y570 20091                         | 1         | 0.81%   |
| Lenovo IdeaPad L340-15IWL 81LG                    | 1         | 0.81%   |
| Lenovo IdeaPad C340-14IWL 81N4                    | 1         | 0.81%   |
| Lenovo IdeaPad 330-15IKB 81DE                     | 1         | 0.81%   |
| Lenovo IdeaPad 320-15IKB 81BG                     | 1         | 0.81%   |
| Lenovo IdeaPad 110S-11IBR 80WG                    | 1         | 0.81%   |
| Lenovo G505 20240                                 | 1         | 0.81%   |
| HUAWEI BOHK-WAX9X                                 | 1         | 0.81%   |
| HP ZBook Firefly 14 inch G8 Mobile Workstation PC | 1         | 0.81%   |
| HP ProDesk 400 G2 MT (TPM DP)                     | 1         | 0.81%   |
| HP ProBook 6560b                                  | 1         | 0.81%   |
| HP ProBook 650 G1                                 | 1         | 0.81%   |
| HP ProBook 4710s                                  | 1         | 0.81%   |
| HP ProBook 470 G2                                 | 1         | 0.81%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| HP EliteBook            | 8         | 6.5%    |
| Acer Aspire             | 8         | 6.5%    |
| Lenovo ThinkPad         | 7         | 5.69%   |
| HP Compaq               | 7         | 5.69%   |
| Lenovo IdeaPad          | 6         | 4.88%   |
| HP ProBook              | 5         | 4.07%   |
| ASUS VivoBook           | 4         | 3.25%   |
| ASUS All                | 4         | 3.25%   |
| HP ENVY                 | 3         | 2.44%   |
| Dell OptiPlex           | 3         | 2.44%   |
| Dell Latitude           | 3         | 2.44%   |
| HP 250                  | 2         | 1.63%   |
| Dell XPS                | 2         | 1.63%   |
| Dell Inspiron           | 2         | 1.63%   |
| Dell G3                 | 2         | 1.63%   |
| ASUS TUF                | 2         | 1.63%   |
| ASUS PRIME              | 2         | 1.63%   |
| ASUS P8H61-M            | 2         | 1.63%   |
| ASUS P5KPL-AM           | 2         | 1.63%   |
| ASUS P5G41T-M           | 2         | 1.63%   |
| Wistron ProLiant        | 1         | 0.81%   |
| Toshiba Satellite       | 1         | 0.81%   |
| Sony VGN-BX41VN         | 1         | 0.81%   |
| Pegatron VS170AA-UUZ    | 1         | 0.81%   |
| NEC Computers VERSAP550 | 1         | 0.81%   |
| MSI MS-AA1511           | 1         | 0.81%   |
| MSI MS-7978             | 1         | 0.81%   |
| MSI MS-7597             | 1         | 0.81%   |
| Microsoft Surface       | 1         | 0.81%   |
| Medion MS-7366          | 1         | 0.81%   |
| Lenovo Yoga             | 1         | 0.81%   |
| Lenovo Legion           | 1         | 0.81%   |
| Lenovo G505             | 1         | 0.81%   |
| HUAWEI BOHK-WAX9X       | 1         | 0.81%   |
| HP ZBook                | 1         | 0.81%   |
| HP ProDesk              | 1         | 0.81%   |
| HP Pavilion             | 1         | 0.81%   |
| HP Laptop               | 1         | 0.81%   |
| HP All-in-One           | 1         | 0.81%   |
| HP 550                  | 1         | 0.81%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 14        | 11.38%  |
| 2019    | 12        | 9.76%   |
| 2012    | 11        | 8.94%   |
| 2016    | 10        | 8.13%   |
| 2014    | 9         | 7.32%   |
| 2013    | 9         | 7.32%   |
| 2009    | 9         | 7.32%   |
| 2018    | 8         | 6.5%    |
| 2020    | 6         | 4.88%   |
| 2017    | 6         | 4.88%   |
| 2008    | 6         | 4.88%   |
| 2007    | 6         | 4.88%   |
| 2010    | 4         | 3.25%   |
| 2021    | 3         | 2.44%   |
| 2015    | 3         | 2.44%   |
| 2006    | 3         | 2.44%   |
| 2005    | 2         | 1.63%   |
| 2022    | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 75        | 60.98%  |
| Desktop     | 41        | 33.33%  |
| Convertible | 4         | 3.25%   |
| All in one  | 2         | 1.63%   |
| Tablet      | 1         | 0.81%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 117       | 95.12%  |
| Enabled  | 6         | 4.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 123       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 36        | 28.8%   |
| 3.01-4.0    | 25        | 20%     |
| 16.01-24.0  | 19        | 15.2%   |
| 8.01-16.0   | 18        | 14.4%   |
| 1.01-2.0    | 15        | 12%     |
| 2.01-3.0    | 6         | 4.8%    |
| 32.01-64.0  | 2         | 1.6%    |
| 0.51-1.0    | 2         | 1.6%    |
| 64.01-256.0 | 1         | 0.8%    |
| 0.01-0.5    | 1         | 0.8%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 54        | 40.91%  |
| 2.01-3.0  | 32        | 24.24%  |
| 4.01-8.0  | 14        | 10.61%  |
| 0.51-1.0  | 14        | 10.61%  |
| 3.01-4.0  | 12        | 9.09%   |
| 8.01-16.0 | 4         | 3.03%   |
| 0.01-0.5  | 2         | 1.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 92        | 72.44%  |
| 2      | 29        | 22.83%  |
| 3      | 3         | 2.36%   |
| 5      | 1         | 0.79%   |
| 4      | 1         | 0.79%   |
| 0      | 1         | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 67        | 53.6%   |
| Yes       | 58        | 46.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 83.2%   |
| No        | 21        | 16.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 73.98%  |
| No        | 32        | 26.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 64        | 51.61%  |
| No        | 60        | 48.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| Bosnia and Herzegovina | 123       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sarajevo          | 39        | 30.95%  |
| Banja Luka        | 21        | 16.67%  |
| Tuzla             | 7         | 5.56%   |
| Gracanica         | 5         | 3.97%   |
| Doboj             | 4         | 3.17%   |
| Zenica            | 3         | 2.38%   |
| Teslic            | 3         | 2.38%   |
| Prijedor          | 3         | 2.38%   |
| Novi Travnik      | 3         | 2.38%   |
| Brcko             | 3         | 2.38%   |
| Zepce             | 2         | 1.59%   |
| Srebrenik         | 2         | 1.59%   |
| Prnjavor          | 2         | 1.59%   |
| Maglaj            | 2         | 1.59%   |
| Lukavac           | 2         | 1.59%   |
| Zvornik           | 1         | 0.79%   |
| Zivinice          | 1         | 0.79%   |
| Vitez             | 1         | 0.79%   |
| Velika KladuÅ¡a | 1         | 0.79%   |
| Trebinje          | 1         | 0.79%   |
| Tarcin            | 1         | 0.79%   |
| Stjepan-Polje     | 1         | 0.79%   |
| Solina            | 1         | 0.79%   |
| Posusje           | 1         | 0.79%   |
| Pale              | 1         | 0.79%   |
| Orahovica Donja   | 1         | 0.79%   |
| Nova Topola       | 1         | 0.79%   |
| Nevesinje         | 1         | 0.79%   |
| Mostar            | 1         | 0.79%   |
| Lukavica          | 1         | 0.79%   |
| Ljubuski          | 1         | 0.79%   |
| Kobilja Glava     | 1         | 0.79%   |
| Jablanica         | 1         | 0.79%   |
| Ilidza            | 1         | 0.79%   |
| Grude             | 1         | 0.79%   |
| Gradacac          | 1         | 0.79%   |
| Foca              | 1         | 0.79%   |
| Drvar             | 1         | 0.79%   |
| Bijeljina         | 1         | 0.79%   |
| Banovici          | 1         | 0.79%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 33     | 14.29%  |
| Kingston            | 21        | 23     | 13.64%  |
| Seagate             | 19        | 26     | 12.34%  |
| Samsung Electronics | 19        | 23     | 12.34%  |
| Toshiba             | 17        | 18     | 11.04%  |
| Hitachi             | 14        | 14     | 9.09%   |
| SanDisk             | 9         | 11     | 5.84%   |
| SK hynix            | 7         | 8      | 4.55%   |
| Unknown             | 4         | 4      | 2.6%    |
| Intel               | 4         | 4      | 2.6%    |
| A-DATA Technology   | 2         | 2      | 1.3%    |
| Vaseky              | 1         | 1      | 0.65%   |
| Transcend           | 1         | 2      | 0.65%   |
| Team                | 1         | 1      | 0.65%   |
| Patriot             | 1         | 1      | 0.65%   |
| ORGE                | 1         | 1      | 0.65%   |
| OCZ                 | 1         | 2      | 0.65%   |
| Micron Technology   | 1         | 1      | 0.65%   |
| Maxtor              | 1         | 1      | 0.65%   |
| KIOXIA              | 1         | 1      | 0.65%   |
| Intenso             | 1         | 1      | 0.65%   |
| HGST                | 1         | 1      | 0.65%   |
| GOODRAM             | 1         | 1      | 0.65%   |
| Fujitsu             | 1         | 1      | 0.65%   |
| Crucial             | 1         | 1      | 0.65%   |
| China               | 1         | 3      | 0.65%   |
| ASMT                | 1         | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB           | 5         | 3.07%   |
| Kingston SA400S37240G 240GB SSD  | 5         | 3.07%   |
| SK hynix NVMe SSD Drive 512GB    | 3         | 1.84%   |
| Kingston SHFS37A120G 120GB SSD   | 3         | 1.84%   |
| Kingston SA400S37120G 120GB SSD  | 3         | 1.84%   |
| Hitachi HDS721050CLA362 500GB    | 3         | 1.84%   |
| Unknown SD/MMC/MS PRO 1TB        | 2         | 1.23%   |
| Unknown MMC Card  32GB           | 2         | 1.23%   |
| Toshiba DT01ACA100 1TB           | 2         | 1.23%   |
| Toshiba DT01ACA050 500GB         | 2         | 1.23%   |
| Seagate ST3500413AS 500GB        | 2         | 1.23%   |
| Seagate ST250LT021-1AF14C 250GB  | 2         | 1.23%   |
| SanDisk NVMe SSD Drive 256GB     | 2         | 1.23%   |
| Samsung NVMe SSD Drive 512GB     | 2         | 1.23%   |
| Kingston SHFS37A240G 240GB SSD   | 2         | 1.23%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 1         | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 0.61%   |
| WDC WDS240G1G0A-00SS50 240GB SSD | 1         | 0.61%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD | 1         | 0.61%   |
| WDC WD800JD-75MSA3 80GB          | 1         | 0.61%   |
| WDC WD800JD-60LSA5 80GB          | 1         | 0.61%   |
| WDC WD800JD-00MSA1 80GB          | 1         | 0.61%   |
| WDC WD7500BPVX-22JC3T0 752GB     | 1         | 0.61%   |
| WDC WD7500BPVT-75HXZT3 752GB     | 1         | 0.61%   |
| WDC WD7500BPVT-24HXZT3 752GB     | 1         | 0.61%   |
| WDC WD7500AACS-00D6B0 752GB      | 1         | 0.61%   |
| WDC WD5000LPVT-75G33T0 500GB     | 1         | 0.61%   |
| WDC WD5000LPVT-22G33T0 500GB     | 1         | 0.61%   |
| WDC WD5000BEKT-22KA9T0 500GB     | 1         | 0.61%   |
| WDC WD5000AZLX-60K2TA0 500GB     | 1         | 0.61%   |
| WDC WD5000AAKX-00ERMA0 500GB     | 1         | 0.61%   |
| WDC WD40EZRZ-75GXCB0 4TB         | 1         | 0.61%   |
| WDC WD40EZAZ-00ZGHB0 4TB         | 1         | 0.61%   |
| WDC WD3200SD-01KNB0 320GB        | 1         | 0.61%   |
| WDC WD3200AAJS-00L7A0 320GB      | 1         | 0.61%   |
| WDC WD20EARX-00PASB0 2TB         | 1         | 0.61%   |
| WDC WD2000JD-00HBB0 200GB        | 1         | 0.61%   |
| WDC WD1600BEVT-22ZCT0 160GB      | 1         | 0.61%   |
| WDC WD1600AAJS-00B4A0 160GB      | 1         | 0.61%   |
| WDC WD15EARS-00S8B1 1TB          | 1         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 19        | 29     | 26.03%  |
| Seagate             | 19        | 26     | 26.03%  |
| Toshiba             | 14        | 14     | 19.18%  |
| Hitachi             | 14        | 14     | 19.18%  |
| Unknown             | 2         | 2      | 2.74%   |
| Samsung Electronics | 2         | 2      | 2.74%   |
| Maxtor              | 1         | 1      | 1.37%   |
| HGST                | 1         | 1      | 1.37%   |
| Fujitsu             | 1         | 1      | 1.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 18        | 20     | 34.62%  |
| Samsung Electronics | 10        | 12     | 19.23%  |
| WDC                 | 4         | 4      | 7.69%   |
| SanDisk             | 4         | 5      | 7.69%   |
| Intel               | 3         | 3      | 5.77%   |
| A-DATA Technology   | 2         | 2      | 3.85%   |
| Vaseky              | 1         | 1      | 1.92%   |
| Transcend           | 1         | 2      | 1.92%   |
| Team                | 1         | 1      | 1.92%   |
| SK hynix            | 1         | 1      | 1.92%   |
| Patriot             | 1         | 1      | 1.92%   |
| OCZ                 | 1         | 2      | 1.92%   |
| Micron Technology   | 1         | 1      | 1.92%   |
| Intenso             | 1         | 1      | 1.92%   |
| GOODRAM             | 1         | 1      | 1.92%   |
| China               | 1         | 3      | 1.92%   |
| ASMT                | 1         | 1      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 67        | 90     | 46.21%  |
| SSD     | 48        | 61     | 33.1%   |
| NVMe    | 26        | 31     | 17.93%  |
| MMC     | 3         | 3      | 2.07%   |
| Unknown | 1         | 1      | 0.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 95        | 148    | 74.22%  |
| NVMe | 26        | 31     | 20.31%  |
| SAS  | 4         | 4      | 3.13%   |
| MMC  | 3         | 3      | 2.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 87        | 121    | 78.38%  |
| 0.51-1.0   | 19        | 22     | 17.12%  |
| 1.01-2.0   | 2         | 3      | 1.8%    |
| 3.01-4.0   | 1         | 2      | 0.9%    |
| 2.01-3.0   | 1         | 2      | 0.9%    |
| 4.01-10.0  | 1         | 1      | 0.9%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 38        | 29.92%  |
| 251-500        | 31        | 24.41%  |
| 51-100         | 15        | 11.81%  |
| 501-1000       | 14        | 11.02%  |
| 21-50          | 11        | 8.66%   |
| 1-20           | 9         | 7.09%   |
| More than 3000 | 3         | 2.36%   |
| 1001-2000      | 3         | 2.36%   |
| Unknown        | 2         | 1.57%   |
| 2001-3000      | 1         | 0.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 55        | 40.15%  |
| 21-50     | 39        | 28.47%  |
| 51-100    | 18        | 13.14%  |
| 101-250   | 11        | 8.03%   |
| 501-1000  | 6         | 4.38%   |
| 251-500   | 5         | 3.65%   |
| Unknown   | 2         | 1.46%   |
| 2001-3000 | 1         | 0.73%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Computers | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD              | 1         | 1      | 12.5%   |
| WDC WD3200AAJS-00L7A0 320GB                   | 1         | 1      | 12.5%   |
| Seagate ST3120813AS 120GB                     | 1         | 1      | 12.5%   |
| Seagate ST3000DM001-1CH166 3TB                | 1         | 2      | 12.5%   |
| Seagate ST250LT021-1AF14C 250GB               | 1         | 1      | 12.5%   |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD | 1         | 1      | 12.5%   |
| Hitachi HDS721050CLA362 500GB                 | 1         | 1      | 12.5%   |
| Crucial CT500P1SSD8 500GB                     | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 4      | 37.5%   |
| WDC                 | 2         | 2      | 25%     |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |
| Crucial             | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 60%     |
| WDC     | 1         | 1      | 20%     |
| Hitachi | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 6      | 57.14%  |
| SSD  | 2         | 2      | 28.57%  |
| NVMe | 1         | 1      | 14.29%  |

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
| Detected | 91        | 137    | 71.65%  |
| Works    | 29        | 40     | 22.83%  |
| Malfunc  | 7         | 9      | 5.51%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 90        | 65.69%  |
| AMD                          | 15        | 10.95%  |
| Samsung Electronics          | 7         | 5.11%   |
| SK hynix                     | 6         | 4.38%   |
| Nvidia                       | 6         | 4.38%   |
| SanDisk                      | 4         | 2.92%   |
| Toshiba America Info Systems | 3         | 2.19%   |
| Kingston Technology Company  | 3         | 2.19%   |
| Micron/Crucial Technology    | 1         | 0.73%   |
| KIOXIA                       | 1         | 0.73%   |
| JMicron Technology           | 1         | 0.73%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 12        | 7.32%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 10        | 6.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 8         | 4.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 8         | 4.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 3.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 5         | 3.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 3.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 2.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 2.44%   |
| Samsung NVMe SSD Controller 980                                                         | 3         | 1.83%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 1.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 3         | 1.83%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 1.83%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 3         | 1.83%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 2         | 1.22%   |
| SK hynix Gold P31 SSD                                                                   | 2         | 1.22%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 1.22%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 2         | 1.22%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 2         | 1.22%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 2         | 1.22%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 1.22%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 1.22%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2         | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 2         | 1.22%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 1.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.22%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 2         | 1.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 1.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 2         | 1.22%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.61%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                             | 1         | 0.61%   |
| SK hynix Non-Volatile memory controller                                                 | 1         | 0.61%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 1         | 0.61%   |
| SanDisk PC SN520 NVMe SSD                                                               | 1         | 0.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 1         | 0.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 1         | 0.61%   |
| Nvidia nForce3 Serial ATA Controller                                                    | 1         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 81        | 55.86%  |
| IDE  | 28        | 19.31%  |
| NVMe | 26        | 17.93%  |
| RAID | 10        | 6.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 99        | 80.49%  |
| AMD    | 23        | 18.7%   |
| ARM    | 1         | 0.81%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 2.44%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 3         | 2.44%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 2         | 1.63%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz   | 2         | 1.63%   |
| Intel Pentium CPU G630 @ 2.70GHz              | 2         | 1.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.63%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.63%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.63%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.63%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 1.63%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 1.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.63%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.63%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 1.63%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 2         | 1.63%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.63%   |
| Intel Celeron CPU 430 @ 1.80GHz               | 2         | 1.63%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.63%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.63%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 2         | 1.63%   |
| Intel Xeon CPU X3210 @ 2.13GHz                | 1         | 0.81%   |
| Intel Pentium M processor 1.73GHz             | 1         | 0.81%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 1         | 0.81%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz   | 1         | 0.81%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.81%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.81%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 1         | 0.81%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.81%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 1         | 0.81%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 1         | 0.81%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 0.81%   |
| Intel Core i7-4550U CPU @ 1.50GHz             | 1         | 0.81%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 1         | 0.81%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 1         | 0.81%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.81%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 0.81%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.81%   |
| Intel Core i5-9400T CPU @ 1.80GHz             | 1         | 0.81%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 0.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.81%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 29        | 23.58%  |
| Intel Core i7           | 23        | 18.7%   |
| Intel Core i3           | 9         | 7.32%   |
| Intel Celeron           | 9         | 7.32%   |
| Other                   | 6         | 4.88%   |
| Intel Pentium Dual-Core | 6         | 4.88%   |
| Intel Core 2 Duo        | 6         | 4.88%   |
| AMD Ryzen 5             | 5         | 4.07%   |
| Intel Pentium           | 3         | 2.44%   |
| AMD E1                  | 3         | 2.44%   |
| Intel Core 2 Quad       | 2         | 1.63%   |
| Intel Core 2            | 2         | 1.63%   |
| AMD Ryzen 9             | 2         | 1.63%   |
| AMD Athlon 64 X2        | 2         | 1.63%   |
| Intel Xeon              | 1         | 0.81%   |
| Intel Pentium M         | 1         | 0.81%   |
| Intel Pentium Dual      | 1         | 0.81%   |
| Intel Celeron D         | 1         | 0.81%   |
| Intel Atom              | 1         | 0.81%   |
| AMD Turion 64 Mobile    | 1         | 0.81%   |
| AMD Ryzen 7             | 1         | 0.81%   |
| AMD Ryzen 5 PRO         | 1         | 0.81%   |
| AMD Phenom              | 1         | 0.81%   |
| AMD FX                  | 1         | 0.81%   |
| AMD E2                  | 1         | 0.81%   |
| AMD C-60                | 1         | 0.81%   |
| AMD Athlon X4           | 1         | 0.81%   |
| AMD Athlon II X3        | 1         | 0.81%   |
| AMD Athlon 64           | 1         | 0.81%   |
| AMD A10                 | 1         | 0.81%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 62        | 50.41%  |
| 4      | 42        | 34.15%  |
| 6      | 6         | 4.88%   |
| 1      | 6         | 4.88%   |
| 8      | 3         | 2.44%   |
| 3      | 2         | 1.63%   |
| 14     | 1         | 0.81%   |
| 12     | 1         | 0.81%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 123       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 67        | 54.47%  |
| 1      | 56        | 45.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 116       | 94.31%  |
| Unknown        | 6         | 4.88%   |
| 32-bit         | 1         | 0.81%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 31        | 24.8%   |
| 0x206a7    | 12        | 9.6%    |
| 0x306a9    | 9         | 7.2%    |
| 0x1067a    | 8         | 6.4%    |
| 0x306c3    | 7         | 5.6%    |
| 0x406e3    | 4         | 3.2%    |
| 0x806ec    | 3         | 2.4%    |
| 0x806c1    | 3         | 2.4%    |
| 0x506e3    | 3         | 2.4%    |
| 0x40651    | 3         | 2.4%    |
| 0x10676    | 3         | 2.4%    |
| 0x806eb    | 2         | 1.6%    |
| 0x806ea    | 2         | 1.6%    |
| 0x806e9    | 2         | 1.6%    |
| 0x506c9    | 2         | 1.6%    |
| 0x08108109 | 2         | 1.6%    |
| 0x05000119 | 2         | 1.6%    |
| 0xf65      | 1         | 0.8%    |
| 0xa0652    | 1         | 0.8%    |
| 0x906ec    | 1         | 0.8%    |
| 0x906eb    | 1         | 0.8%    |
| 0x906ea    | 1         | 0.8%    |
| 0x906a3    | 1         | 0.8%    |
| 0x706e5    | 1         | 0.8%    |
| 0x6fd      | 1         | 0.8%    |
| 0x6fb      | 1         | 0.8%    |
| 0x6fa      | 1         | 0.8%    |
| 0x6f6      | 1         | 0.8%    |
| 0x6f2      | 1         | 0.8%    |
| 0x6d8      | 1         | 0.8%    |
| 0x406c4    | 1         | 0.8%    |
| 0x406c3    | 1         | 0.8%    |
| 0x30678    | 1         | 0.8%    |
| 0x20655    | 1         | 0.8%    |
| 0x106e5    | 1         | 0.8%    |
| 0x10661    | 1         | 0.8%    |
| 0x0a50000c | 1         | 0.8%    |
| 0x08701021 | 1         | 0.8%    |
| 0x08600106 | 1         | 0.8%    |
| 0x08108102 | 1         | 0.8%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 18        | 14.63%  |
| SandyBridge      | 16        | 13.01%  |
| Penryn           | 12        | 9.76%   |
| Haswell          | 11        | 8.94%   |
| IvyBridge        | 10        | 8.13%   |
| Core             | 8         | 6.5%    |
| Skylake          | 7         | 5.69%   |
| Zen+             | 6         | 4.88%   |
| TigerLake        | 4         | 3.25%   |
| Silvermont       | 4         | 3.25%   |
| K8 Hammer        | 4         | 3.25%   |
| Zen 2            | 2         | 1.63%   |
| K10              | 2         | 1.63%   |
| Jaguar           | 2         | 1.63%   |
| Goldmont         | 2         | 1.63%   |
| Excavator        | 2         | 1.63%   |
| Bobcat           | 2         | 1.63%   |
| Zen 3            | 1         | 0.81%   |
| Westmere         | 1         | 0.81%   |
| Steamroller      | 1         | 0.81%   |
| P6               | 1         | 0.81%   |
| NetBurst         | 1         | 0.81%   |
| Nehalem          | 1         | 0.81%   |
| IceLake          | 1         | 0.81%   |
| CometLake        | 1         | 0.81%   |
| Bulldozer        | 1         | 0.81%   |
| Alderlake Hybrid | 1         | 0.81%   |
| Unknown          | 1         | 0.81%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 72        | 48.32%  |
| AMD                        | 39        | 26.17%  |
| Nvidia                     | 37        | 24.83%  |
| Matrox Electronics Systems | 1         | 0.67%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 7.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 4.52%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 3.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 3.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 2.58%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 2.58%   |
| Nvidia GM108M [GeForce MX110]                                                            | 3         | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.94%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.94%   |
| Intel HD Graphics 620                                                                    | 3         | 1.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.94%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 1.29%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 1.29%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 1.29%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.29%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 1.29%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.29%   |
| Intel HD Graphics 500                                                                    | 2         | 1.29%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.29%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 1.29%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.29%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 1.29%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 1.29%   |
| AMD Kabini [Radeon HD 8210]                                                              | 2         | 1.29%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 1.29%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 1         | 0.65%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.65%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile]                                                 | 1         | 0.65%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1         | 0.65%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.65%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1         | 0.65%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.65%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.65%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 0.65%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.65%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.65%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 47        | 37.9%   |
| 1 x AMD        | 30        | 24.19%  |
| Intel + Nvidia | 20        | 16.13%  |
| 1 x Nvidia     | 16        | 12.9%   |
| Intel + AMD    | 4         | 3.23%   |
| 2 x AMD        | 3         | 2.42%   |
| Other          | 1         | 0.81%   |
| 3 x AMD        | 1         | 0.81%   |
| 1 x Matrox     | 1         | 0.81%   |
| AMD + Nvidia   | 1         | 0.81%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 98        | 79.03%  |
| Proprietary | 20        | 16.13%  |
| Unknown     | 6         | 4.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 50.79%  |
| 1.01-2.0   | 21        | 16.67%  |
| 0.01-0.5   | 17        | 13.49%  |
| 0.51-1.0   | 13        | 10.32%  |
| 3.01-4.0   | 6         | 4.76%   |
| 5.01-6.0   | 3         | 2.38%   |
| 7.01-8.0   | 2         | 1.59%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 19        | 15.32%  |
| Samsung Electronics     | 18        | 14.52%  |
| AU Optronics            | 17        | 13.71%  |
| BOE                     | 11        | 8.87%   |
| Chimei Innolux          | 10        | 8.06%   |
| Goldstar                | 6         | 4.84%   |
| AOC                     | 6         | 4.84%   |
| Philips                 | 4         | 3.23%   |
| Dell                    | 4         | 3.23%   |
| Sharp                   | 3         | 2.42%   |
| Unknown                 | 2         | 1.61%   |
| Sony                    | 2         | 1.61%   |
| LG Philips              | 2         | 1.61%   |
| IBM                     | 2         | 1.61%   |
| Hewlett-Packard         | 2         | 1.61%   |
| Fujitsu Siemens         | 2         | 1.61%   |
| Chi Mei Optoelectronics | 2         | 1.61%   |
| ViewSonic               | 1         | 0.81%   |
| Vestel Elektronik       | 1         | 0.81%   |
| PANDA                   | 1         | 0.81%   |
| NEC Computers           | 1         | 0.81%   |
| MSI                     | 1         | 0.81%   |
| Mi                      | 1         | 0.81%   |
| Lenovo                  | 1         | 0.81%   |
| InfoVision              | 1         | 0.81%   |
| BenQ                    | 1         | 0.81%   |
| Belinea                 | 1         | 0.81%   |
| ASUSTek Computer        | 1         | 0.81%   |
| Ancor Communications    | 1         | 0.81%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 4         | 3.1%    |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch            | 3         | 2.33%   |
| LG Display LCD Monitor LGD05E4 1920x1080 344x194mm 15.5-inch           | 2         | 1.55%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch            | 2         | 1.55%   |
| IBM C170 CRT IBM1A51 1280x1024 310x230mm 15.2-inch                     | 2         | 1.55%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 2         | 1.55%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.55%   |
| AOC 917W AOC1917 1440x900 410x256mm 19.0-inch                          | 2         | 1.55%   |
| ViewSonic VA702 VSC1C1C 1280x1024 338x270mm 17.0-inch                  | 1         | 0.78%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 1         | 0.78%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                   | 1         | 0.78%   |
| Unknown LCD Monitor Maxdata/XXXXXXX B_101920 1280x1024                 | 1         | 0.78%   |
| Sony TV SNY4D04 1920x1080 1600x900mm 72.3-inch                         | 1         | 0.78%   |
| Sony TV *00 SNY4904 3840x2160                                          | 1         | 0.78%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 0.78%   |
| Sharp LCD Monitor SHP14A2 1920x1080 309x174mm 14.0-inch                | 1         | 0.78%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM0579 1920x1080                       | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch    | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM03E2 1680x1050 433x271mm 20.1-inch   | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM01F9 1280x1024 376x301mm 19.0-inch   | 1         | 0.78%   |
| Samsung Electronics SyncMaster SAM0169 1280x1024 376x301mm 19.0-inch   | 1         | 0.78%   |
| Samsung Electronics SAMTRON 50X/V STN0011 1024x768 304x228mm 15.0-inch | 1         | 0.78%   |
| Samsung Electronics S27D590 SAM0B49 1920x1080 598x336mm 27.0-inch      | 1         | 0.78%   |
| Samsung Electronics S24D391 SAM0B87 1920x1080 521x293mm 23.5-inch      | 1         | 0.78%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 1         | 0.78%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 477x268mm 21.5-inch      | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3554 1600x900 382x215mm 17.3-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch  | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 700x390mm 31.5-inch   | 1         | 0.78%   |
| Samsung Electronics LCD Monitor SAM0659 1920x1080                      | 1         | 0.78%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch                | 1         | 0.78%   |
| Philips LCD Monitor FTV                                                | 1         | 0.78%   |
| Philips LCD Monitor 170S 3200x1080                                     | 1         | 0.78%   |
| Philips 192EL PHLC04E 1366x768 410x230mm 18.5-inch                     | 1         | 0.78%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 48        | 39.67%  |
| 1366x768 (WXGA)    | 23        | 19.01%  |
| 1600x900 (HD+)     | 13        | 10.74%  |
| 1280x1024 (SXGA)   | 10        | 8.26%   |
| 1680x1050 (WSXGA+) | 6         | 4.96%   |
| 3840x2160 (4K)     | 5         | 4.13%   |
| 1440x900 (WXGA+)   | 5         | 4.13%   |
| 2560x1440 (QHD)    | 2         | 1.65%   |
| 1280x800 (WXGA)    | 2         | 1.65%   |
| 3440x1440          | 1         | 0.83%   |
| 3200x1080          | 1         | 0.83%   |
| 2736x1824          | 1         | 0.83%   |
| 1920x1200 (WUXGA)  | 1         | 0.83%   |
| 1360x768           | 1         | 0.83%   |
| 1024x768 (XGA)     | 1         | 0.83%   |
| Unknown            | 1         | 0.83%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 43        | 34.4%   |
| 17      | 13        | 10.4%   |
| 14      | 12        | 9.6%    |
| Unknown | 8         | 6.4%    |
| 13      | 7         | 5.6%    |
| 24      | 6         | 4.8%    |
| 21      | 6         | 4.8%    |
| 23      | 4         | 3.2%    |
| 19      | 4         | 3.2%    |
| 27      | 3         | 2.4%    |
| 22      | 3         | 2.4%    |
| 18      | 3         | 2.4%    |
| 11      | 3         | 2.4%    |
| 72      | 2         | 1.6%    |
| 20      | 2         | 1.6%    |
| 12      | 2         | 1.6%    |
| 84      | 1         | 0.8%    |
| 34      | 1         | 0.8%    |
| 33      | 1         | 0.8%    |
| 31      | 1         | 0.8%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 63        | 51.64%  |
| 401-500     | 16        | 13.11%  |
| 501-600     | 11        | 9.02%   |
| 351-400     | 10        | 8.2%    |
| 201-300     | 8         | 6.56%   |
| Unknown     | 8         | 6.56%   |
| 1501-2000   | 3         | 2.46%   |
| 701-800     | 2         | 1.64%   |
| 601-700     | 1         | 0.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 84        | 73.04%  |
| 16/10   | 12        | 10.43%  |
| 5/4     | 7         | 6.09%   |
| Unknown | 6         | 5.22%   |
| 4/3     | 3         | 2.61%   |
| 3/2     | 2         | 1.74%   |
| 21/9    | 1         | 0.87%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 40        | 32.79%  |
| 81-90          | 16        | 13.11%  |
| 201-250        | 13        | 10.66%  |
| 151-200        | 9         | 7.38%   |
| Unknown        | 8         | 6.56%   |
| 141-150        | 7         | 5.74%   |
| 121-130        | 6         | 4.92%   |
| More than 1000 | 3         | 2.46%   |
| 71-80          | 3         | 2.46%   |
| 51-60          | 3         | 2.46%   |
| 351-500        | 3         | 2.46%   |
| 301-350        | 3         | 2.46%   |
| 61-70          | 2         | 1.64%   |
| 131-140        | 2         | 1.64%   |
| 111-120        | 2         | 1.64%   |
| 251-300        | 1         | 0.82%   |
| 91-100         | 1         | 0.82%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 40        | 33.33%  |
| 101-120       | 32        | 26.67%  |
| 51-100        | 32        | 26.67%  |
| Unknown       | 8         | 6.67%   |
| 161-240       | 4         | 3.33%   |
| More than 240 | 2         | 1.67%   |
| 1-50          | 2         | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 103       | 82.4%   |
| 2     | 15        | 12%     |
| 0     | 5         | 4%      |
| 3     | 2         | 1.6%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 58        | 32.95%  |
| Intel                                  | 41        | 23.3%   |
| Qualcomm Atheros                       | 29        | 16.48%  |
| Broadcom                               | 11        | 6.25%   |
| Ralink Technology                      | 5         | 2.84%   |
| TP-Link                                | 4         | 2.27%   |
| Ralink                                 | 4         | 2.27%   |
| Qualcomm Atheros Communications        | 4         | 2.27%   |
| Nvidia                                 | 4         | 2.27%   |
| Marvell Technology Group               | 4         | 2.27%   |
| Broadcom Limited                       | 3         | 1.7%    |
| Sony Ericsson Mobile Communications AB | 2         | 1.14%   |
| Sierra Wireless                        | 1         | 0.57%   |
| Mercucys                               | 1         | 0.57%   |
| MediaTek                               | 1         | 0.57%   |
| ICS Advent                             | 1         | 0.57%   |
| HTC (High Tech Computer)               | 1         | 0.57%   |
| Hewlett-Packard                        | 1         | 0.57%   |
| D-Link                                 | 1         | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 19.32%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 4.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 3.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 3.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 3.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 2.9%    |
| Ralink MT7601U Wireless Adapter                                   | 5         | 2.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 1.93%   |
| Qualcomm Atheros AR9271 802.11n                                   | 4         | 1.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.45%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 1.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.45%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3         | 1.45%   |
| Intel Wireless 7260                                               | 3         | 1.45%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.45%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 1.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.45%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.97%   |
| Sony Ericsson Mobile AB D2005                                     | 2         | 0.97%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.97%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.97%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.97%   |
| Intel Wireless 8260                                               | 2         | 0.97%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.97%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 0.97%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 0.97%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.48%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                               | 1         | 0.48%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.48%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.48%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.48%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 30.93%  |
| Qualcomm Atheros                | 23        | 23.71%  |
| Realtek Semiconductor           | 15        | 15.46%  |
| Broadcom                        | 8         | 8.25%   |
| Ralink Technology               | 5         | 5.15%   |
| Ralink                          | 4         | 4.12%   |
| Qualcomm Atheros Communications | 4         | 4.12%   |
| TP-Link                         | 3         | 3.09%   |
| Sierra Wireless                 | 1         | 1.03%   |
| Mercucys                        | 1         | 1.03%   |
| MediaTek                        | 1         | 1.03%   |
| Marvell Technology Group        | 1         | 1.03%   |
| D-Link                          | 1         | 1.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 7.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 7.22%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 6.19%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 5.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 4.12%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 4.12%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 3.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 3.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 3.09%   |
| Intel Wireless 7260                                                     | 3         | 3.09%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 3.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 3.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 3.09%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 2.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 2.06%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 2.06%   |
| Intel Wireless 8260                                                     | 2         | 2.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 2.06%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 2.06%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 1.03%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 1.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 1.03%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 1.03%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 1.03%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 1.03%   |
| Realtek Realtek Network controller                                      | 1         | 1.03%   |
| Realtek 802.11ac NIC                                                    | 1         | 1.03%   |
| Ralink RT2561/RT61 802.11g PCI                                          | 1         | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 1.03%   |
| Qualcomm Atheros AR2417 Wireless Network Adapter [AR5007G 802.11bg]     | 1         | 1.03%   |
| Mercucys 802.11n NIC                                                    | 1         | 1.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 1.03%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                       | 1         | 1.03%   |
| Intel Wireless 8265 / 8275                                              | 1         | 1.03%   |
| Intel Wi-Fi 6 AX200                                                     | 1         | 1.03%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 1.03%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 1.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 1.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 54        | 50.94%  |
| Intel                                  | 25        | 23.58%  |
| Qualcomm Atheros                       | 9         | 8.49%   |
| Nvidia                                 | 4         | 3.77%   |
| Broadcom                               | 4         | 3.77%   |
| Marvell Technology Group               | 3         | 2.83%   |
| Broadcom Limited                       | 3         | 2.83%   |
| Sony Ericsson Mobile Communications AB | 2         | 1.89%   |
| TP-Link                                | 1         | 0.94%   |
| ICS Advent                             | 1         | 0.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 37.38%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 10        | 9.35%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 7.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.8%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 3         | 2.8%    |
| Sony Ericsson Mobile AB D2005                                     | 2         | 1.87%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 1.87%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.87%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.87%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 2         | 1.87%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.93%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.93%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.93%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.93%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.93%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.93%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.93%   |
| Nvidia MCP73 Ethernet                                             | 1         | 0.93%   |
| Nvidia MCP51 Ethernet Controller                                  | 1         | 0.93%   |
| Nvidia CK8S Ethernet Controller                                   | 1         | 0.93%   |
| Nvidia CK804 Ethernet Controller                                  | 1         | 0.93%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.93%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.93%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.93%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.93%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.93%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.93%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.93%   |
| Intel Ethernet Connection (2) I218-V                              | 1         | 0.93%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.93%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.93%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.93%   |
| Intel 82566DM Gigabit Network Connection                          | 1         | 0.93%   |
| Intel 82562GT 10/100 Network Connection                           | 1         | 0.93%   |
| ICS Advent DM9601 Fast Ethernet Adapter                           | 1         | 0.93%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.93%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.93%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 104       | 52.53%  |
| WiFi     | 91        | 45.96%  |
| Modem    | 3         | 1.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 62.7%   |
| Ethernet | 46        | 36.51%  |
| Modem    | 1         | 0.79%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 64        | 51.61%  |
| 1     | 53        | 42.74%  |
| 0     | 7         | 5.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 120       | 97.56%  |
| Yes  | 3         | 2.44%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 16        | 25%     |
| Qualcomm Atheros Communications | 10        | 15.63%  |
| IMC Networks                    | 7         | 10.94%  |
| Realtek Semiconductor           | 6         | 9.38%   |
| Broadcom                        | 6         | 9.38%   |
| Lite-On Technology              | 4         | 6.25%   |
| Ralink                          | 3         | 4.69%   |
| Hewlett-Packard                 | 2         | 3.13%   |
| Foxconn / Hon Hai               | 2         | 3.13%   |
| Cambridge Silicon Radio         | 2         | 3.13%   |
| Toshiba                         | 1         | 1.56%   |
| Realtek                         | 1         | 1.56%   |
| Marvell Semiconductor           | 1         | 1.56%   |
| Integrated System Solution      | 1         | 1.56%   |
| Dell                            | 1         | 1.56%   |
| Alps Electric                   | 1         | 1.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                  | 5         | 7.81%   |
| Intel Bluetooth wireless interface                  | 5         | 7.81%   |
| Intel AX201 Bluetooth                               | 4         | 6.25%   |
| IMC Networks Bluetooth Radio                        | 4         | 6.25%   |
| Realtek Bluetooth Radio                             | 3         | 4.69%   |
| Ralink RT3290 Bluetooth                             | 3         | 4.69%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 4.69%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 3.13%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 3.13%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 3.13%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 3.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 2         | 3.13%   |
| IMC Networks Bluetooth Device                       | 2         | 3.13%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 3.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 3.13%   |
| Toshiba RT Bluetooth Radio                          | 1         | 1.56%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.56%   |
| Realtek Bluetooth Radio                             | 1         | 1.56%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.56%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.56%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 1.56%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.56%   |
| Intel Bluetooth Device                              | 1         | 1.56%   |
| Intel AX200 Bluetooth                               | 1         | 1.56%   |
| Integrated System Solution Bluetooth Device         | 1         | 1.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.56%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 1.56%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 1.56%   |
| Dell DW375 Bluetooth Module                         | 1         | 1.56%   |
| Broadcom HP Portable Valentine                      | 1         | 1.56%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.56%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 1.56%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 UHE Dongle | 1         | 1.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.56%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.56%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)     | 1         | 1.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 95        | 59.75%  |
| AMD                 | 34        | 21.38%  |
| Nvidia              | 22        | 13.84%  |
| Logitech            | 3         | 1.89%   |
| VIA Technologies    | 1         | 0.63%   |
| Texas Instruments   | 1         | 0.63%   |
| JMTek               | 1         | 0.63%   |
| Creative Labs       | 1         | 0.63%   |
| C-Media Electronics | 1         | 0.63%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 8.74%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 10        | 5.46%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 5.46%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 7         | 3.83%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 3.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 2.73%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 2.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 2.73%   |
| AMD FCH Azalia Controller                                                                         | 5         | 2.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 2.19%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 2.19%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 2.19%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 1.64%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.64%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 3         | 1.64%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 1.64%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 1.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.09%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 1.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.09%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 1.09%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 1.09%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.09%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 2         | 1.09%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 1.09%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 1.09%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.09%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.09%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.09%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 1.09%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 1.09%   |
| VIA Technologies ICE1712 [Envy24] PCI Multi-Channel I/O Controller                                | 1         | 0.55%   |
| Texas Instruments PCM2902C Audio CODEC                                                            | 1         | 0.55%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.55%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 14        | 25.45%  |
| Kingston            | 13        | 23.64%  |
| Micron Technology   | 10        | 18.18%  |
| Samsung Electronics | 7         | 12.73%  |
| Unknown             | 4         | 7.27%   |
| A-DATA Technology   | 3         | 5.45%   |
| Crucial             | 2         | 3.64%   |
| Corsair             | 2         | 3.64%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 3.17%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 3.17%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 2         | 3.17%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 2         | 3.17%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s            | 2         | 3.17%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 1.59%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                      | 1         | 1.59%   |
| Unknown RAM Module 2048MB DIMM 1066MT/s                          | 1         | 1.59%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                         | 1         | 1.59%   |
| Unknown RAM Module 1024MB DIMM DDR 800MT/s                       | 1         | 1.59%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB DIMM DDR2 2048MT/s          | 1         | 1.59%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB DIMM SDRAM 2048MT/s            | 1         | 1.59%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 1.59%   |
| SK hynix RAM HMT351U6CFR8C 4GB DIMM DDR3 1333MT/s                | 1         | 1.59%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 1         | 1.59%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s             | 1         | 1.59%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 1         | 1.59%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 1.59%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.59%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.59%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.59%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                  | 1         | 1.59%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.59%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.59%   |
| Samsung RAM M425R4GA3BB0-CQKOL 32GB SODIMM 4800MT/s              | 1         | 1.59%   |
| Micron RAM MT52L512M32D2PF-09 4GB Row Of Chips LPDDR3 2133MT/s   | 1         | 1.59%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 1         | 1.59%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 1         | 1.59%   |
| Micron RAM 8JTF51264HZ-1G6D 1 4GB SODIMM DDR3 1600MT/s           | 1         | 1.59%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 1         | 1.59%   |
| Micron RAM 16KTF51264HZ-1G4M1 4096MB SODIMM DDR3 1333MT/s        | 1         | 1.59%   |
| Micron RAM 16JSF25664HY-1G1D1 2048MB SODIMM 1066MT/s             | 1         | 1.59%   |
| Micron RAM 16HTF25664AY-800G1 2GB DIMM DDR2 800MT/s              | 1         | 1.59%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s            | 1         | 1.59%   |
| Kingston RAM KKN2NM-MIE 4GB SODIMM DDR4 2667MT/s                 | 1         | 1.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 22        | 44.9%   |
| DDR4    | 16        | 32.65%  |
| DDR2    | 4         | 8.16%   |
| LPDDR3  | 2         | 4.08%   |
| Unknown | 2         | 4.08%   |
| SDRAM   | 1         | 2.04%   |
| LPDDR4  | 1         | 2.04%   |
| DDR     | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 28        | 58.33%  |
| DIMM         | 17        | 35.42%  |
| Row Of Chips | 3         | 6.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 21        | 38.89%  |
| 8192  | 18        | 33.33%  |
| 2048  | 8         | 14.81%  |
| 1024  | 4         | 7.41%   |
| 16384 | 2         | 3.7%    |
| 32768 | 1         | 1.85%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 1600  | 16        | 29.09%  |
| 3200  | 5         | 9.09%   |
| 2667  | 5         | 9.09%   |
| 800   | 4         | 7.27%   |
| 2400  | 3         | 5.45%   |
| 2133  | 3         | 5.45%   |
| 1333  | 3         | 5.45%   |
| 1867  | 2         | 3.64%   |
| 1866  | 2         | 3.64%   |
| 1334  | 2         | 3.64%   |
| 1066  | 2         | 3.64%   |
| 4800  | 1         | 1.82%   |
| 3600  | 1         | 1.82%   |
| 3400  | 1         | 1.82%   |
| 3266  | 1         | 1.82%   |
| 2800  | 1         | 1.82%   |
| 2048  | 1         | 1.82%   |
| 1800  | 1         | 1.82%   |
| 333   | 1         | 1.82%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 2         | 66.67%  |
| Lexmark International | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Lexmark International InkJet Color Printer | 1         | 33.33%  |
| HP LaserJet 1000                           | 1         | 33.33%  |
| HP DeskJet F2100 Printer series            | 1         | 33.33%  |

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
| Chicony Electronics                    | 18        | 23.68%  |
| Realtek Semiconductor                  | 9         | 11.84%  |
| IMC Networks                           | 8         | 10.53%  |
| Logitech                               | 5         | 6.58%   |
| Acer                                   | 5         | 6.58%   |
| Sunplus Innovation Technology          | 4         | 5.26%   |
| Quanta                                 | 4         | 5.26%   |
| Microdia                               | 4         | 5.26%   |
| Suyin                                  | 3         | 3.95%   |
| Lite-On Technology                     | 3         | 3.95%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.95%   |
| Syntek                                 | 2         | 2.63%   |
| Ricoh                                  | 2         | 2.63%   |
| Primax Electronics                     | 1         | 1.32%   |
| Luxvisions Innotech Limited            | 1         | 1.32%   |
| Lenovo                                 | 1         | 1.32%   |
| Guillemot                              | 1         | 1.32%   |
| Apple                                  | 1         | 1.32%   |
| ALi                                    | 1         | 1.32%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                          | 5         | 6.58%   |
| Microdia Integrated_Webcam_HD                               | 4         | 5.26%   |
| Chicony Integrated Camera                                   | 3         | 3.95%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 2.63%   |
| Realtek Integrated_Webcam_HD                                | 2         | 2.63%   |
| Realtek HD WebCam                                           | 2         | 2.63%   |
| Lite-On HP HD Webcam                                        | 2         | 2.63%   |
| Chicony HP Truevision HD                                    | 2         | 2.63%   |
| Acer EasyCamera                                             | 2         | 2.63%   |
| Syntek Lenovo EasyCamera                                    | 1         | 1.32%   |
| Syntek Integrated Camera                                    | 1         | 1.32%   |
| Suyin HP TrueVision HD                                      | 1         | 1.32%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 1.32%   |
| Sunplus HP Universal Camera                                 | 1         | 1.32%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 1.32%   |
| Sunplus HD WebCam                                           | 1         | 1.32%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870]         | 1         | 1.32%   |
| Ricoh Laptop_Integrated_Webcam_3M                           | 1         | 1.32%   |
| Realtek VGA WebCam                                          | 1         | 1.32%   |
| Realtek USB Camera                                          | 1         | 1.32%   |
| Realtek Laptop_Integrated_Webcam_HD                         | 1         | 1.32%   |
| Realtek Integrated Webcam HD                                | 1         | 1.32%   |
| Realtek HP Wide Vision FHD Camera                           | 1         | 1.32%   |
| Quanta HP Wide Vision HD Camera                             | 1         | 1.32%   |
| Quanta HP Webcam                                            | 1         | 1.32%   |
| Quanta HP TrueVision HD Camera                              | 1         | 1.32%   |
| Quanta HP HD Camera                                         | 1         | 1.32%   |
| Primax HP HD Webcam [Fixed]                                 | 1         | 1.32%   |
| Luxvisions Innotech Limited HP HD Camera                    | 1         | 1.32%   |
| Logitech Webcam C270                                        | 1         | 1.32%   |
| Logitech Webcam C210                                        | 1         | 1.32%   |
| Logitech Webcam C170                                        | 1         | 1.32%   |
| Logitech QuickCam Vision Pro                                | 1         | 1.32%   |
| Logitech HD Webcam C510                                     | 1         | 1.32%   |
| Lite-On HP Wide Vision HD Camera                            | 1         | 1.32%   |
| Lenovo UVC Camera                                           | 1         | 1.32%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 1.32%   |
| IMC Networks USB2.0 HD IR UVC WebCam                        | 1         | 1.32%   |
| IMC Networks ov9734_azurewave_camera                        | 1         | 1.32%   |
| Guillemot Hercules HD Twist                                 | 1         | 1.32%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 55%     |
| Synaptics                  | 5         | 25%     |
| Shenzhen Goodix Technology | 2         | 10%     |
| LighTuning Technology      | 1         | 5%      |
| AuthenTec                  | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 4         | 20%     |
| Validity Sensors VFS471 Fingerprint Reader        | 4         | 20%     |
| Unknown                                           | 4         | 20%     |
| Shenzhen Goodix  FingerPrint Device               | 2         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 5%      |
| Validity Sensors Synaptics WBDI                   | 1         | 5%      |
| Validity Sensors Swipe Fingerprint Sensor         | 1         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 5%      |
| LighTuning Fingerprint Reader                     | 1         | 5%      |
| AuthenTec AES2810                                 | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 60%     |
| Upek        | 1         | 20%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |
| Broadcom 5880                                                                | 1         | 20%     |
| Broadcom 58200                                                               | 1         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 84        | 67.2%   |
| 1     | 36        | 28.8%   |
| 2     | 4         | 3.2%    |
| 3     | 1         | 0.8%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 20        | 45.45%  |
| Graphics card         | 9         | 20.45%  |
| Chipcard              | 5         | 11.36%  |
| Net/wireless          | 4         | 9.09%   |
| Bluetooth             | 3         | 6.82%   |
| Sound                 | 1         | 2.27%   |
| Multimedia controller | 1         | 2.27%   |
| Modem                 | 1         | 2.27%   |

