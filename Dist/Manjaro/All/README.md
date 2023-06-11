Manjaro - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Manjaro.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Manjaro/Desktop/README.md) and [notebooks](/Dist/Manjaro/Notebook/README.md).

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

Total: 10033

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | X370 GAMING M7 ACK          | Desktop     | [450b8ab5a7](https://linux-hardware.org/?probe=450b8ab5a7) | Jun 10, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [ab5b79d6fd](https://linux-hardware.org/?probe=ab5b79d6fd) | Jun 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [fa84ae9906](https://linux-hardware.org/?probe=fa84ae9906) | Jun 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [4c9c3d929b](https://linux-hardware.org/?probe=4c9c3d929b) | Jun 10, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [03ef8fea42](https://linux-hardware.org/?probe=03ef8fea42) | Jun 10, 2023 |
| ASUSTek       | UX530UQ                     | Notebook    | [71d0ddd2f0](https://linux-hardware.org/?probe=71d0ddd2f0) | Jun 09, 2023 |
| HP            | 82C9                        | Desktop     | [b696990030](https://linux-hardware.org/?probe=b696990030) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [3742e80123](https://linux-hardware.org/?probe=3742e80123) | Jun 09, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [f4f543eaa6](https://linux-hardware.org/?probe=f4f543eaa6) | Jun 09, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [f7470e08b0](https://linux-hardware.org/?probe=f7470e08b0) | Jun 08, 2023 |
| HP            | 3397                        | Desktop     | [c754fea198](https://linux-hardware.org/?probe=c754fea198) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [31a7447d8b](https://linux-hardware.org/?probe=31a7447d8b) | Jun 08, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [bb571d888d](https://linux-hardware.org/?probe=bb571d888d) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [267154b0d2](https://linux-hardware.org/?probe=267154b0d2) | Jun 08, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [5be9db17d1](https://linux-hardware.org/?probe=5be9db17d1) | Jun 08, 2023 |
| WOOKING       | X16                         | Notebook    | [aa543651fc](https://linux-hardware.org/?probe=aa543651fc) | Jun 08, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [302bb0628a](https://linux-hardware.org/?probe=302bb0628a) | Jun 08, 2023 |
| Multilaser    | UB820                       | All in one  | [7a1e5beb6e](https://linux-hardware.org/?probe=7a1e5beb6e) | Jun 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9f3038c25e](https://linux-hardware.org/?probe=9f3038c25e) | Jun 07, 2023 |
| HP            | 3397                        | Desktop     | [d86a6fc258](https://linux-hardware.org/?probe=d86a6fc258) | Jun 07, 2023 |
| HP            | 2B36                        | Desktop     | [45ee697eed](https://linux-hardware.org/?probe=45ee697eed) | Jun 07, 2023 |
| HP            | 2B36                        | Desktop     | [0f36ecaa7e](https://linux-hardware.org/?probe=0f36ecaa7e) | Jun 07, 2023 |
| Google        | Chell                       | Notebook    | [cace26f9f9](https://linux-hardware.org/?probe=cace26f9f9) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [cbb39d8d29](https://linux-hardware.org/?probe=cbb39d8d29) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [47fd407976](https://linux-hardware.org/?probe=47fd407976) | Jun 07, 2023 |
| DIEBOLD       | B85H3-M5                    | Desktop     | [7e56b1fd68](https://linux-hardware.org/?probe=7e56b1fd68) | Jun 07, 2023 |
| Acer          | Aspire A314-36M             | Notebook    | [7cab0d1591](https://linux-hardware.org/?probe=7cab0d1591) | Jun 06, 2023 |
| Dell          | Latitude 5530               | Notebook    | [44aa9db289](https://linux-hardware.org/?probe=44aa9db289) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [ae164f9998](https://linux-hardware.org/?probe=ae164f9998) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [6ae325ff9d](https://linux-hardware.org/?probe=6ae325ff9d) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [77e1fa9533](https://linux-hardware.org/?probe=77e1fa9533) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [c33bc572fd](https://linux-hardware.org/?probe=c33bc572fd) | Jun 06, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [bbbe24d6b6](https://linux-hardware.org/?probe=bbbe24d6b6) | Jun 06, 2023 |
| HP            | 8918                        | Desktop     | [6f94c9caa9](https://linux-hardware.org/?probe=6f94c9caa9) | Jun 06, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [964cd10c8e](https://linux-hardware.org/?probe=964cd10c8e) | Jun 05, 2023 |
| Dell          | 055H3G A01                  | Desktop     | [3fc296df33](https://linux-hardware.org/?probe=3fc296df33) | Jun 05, 2023 |
| Dell          | Latitude 3340               | Notebook    | [4ac9bd4101](https://linux-hardware.org/?probe=4ac9bd4101) | Jun 05, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [13f3f67373](https://linux-hardware.org/?probe=13f3f67373) | Jun 04, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [84f237f434](https://linux-hardware.org/?probe=84f237f434) | Jun 04, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [88fbd57dac](https://linux-hardware.org/?probe=88fbd57dac) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [06752ca793](https://linux-hardware.org/?probe=06752ca793) | Jun 04, 2023 |
| MSI           | GS60 6QE                    | Notebook    | [65ea70f7fa](https://linux-hardware.org/?probe=65ea70f7fa) | Jun 03, 2023 |
| HONOR         | HGF-WX6                     | Notebook    | [13d0d7b145](https://linux-hardware.org/?probe=13d0d7b145) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [ccc6b5c4b5](https://linux-hardware.org/?probe=ccc6b5c4b5) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [6a01df1d69](https://linux-hardware.org/?probe=6a01df1d69) | Jun 03, 2023 |
| HP            | 3397                        | Desktop     | [530b98edd5](https://linux-hardware.org/?probe=530b98edd5) | Jun 03, 2023 |
| HP            | 8918                        | Desktop     | [b03f8a6eb3](https://linux-hardware.org/?probe=b03f8a6eb3) | Jun 02, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [31400c0b8a](https://linux-hardware.org/?probe=31400c0b8a) | Jun 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [359d31bb8c](https://linux-hardware.org/?probe=359d31bb8c) | Jun 02, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [3bc50c5ccb](https://linux-hardware.org/?probe=3bc50c5ccb) | Jun 02, 2023 |
| Pegatron      | H81-M1                      | Desktop     | [cdb426bfb4](https://linux-hardware.org/?probe=cdb426bfb4) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b34bb8b33a](https://linux-hardware.org/?probe=b34bb8b33a) | Jun 02, 2023 |
| Pegatron      | H81-M1                      | Desktop     | [35eb509619](https://linux-hardware.org/?probe=35eb509619) | Jun 02, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [24ccc7665f](https://linux-hardware.org/?probe=24ccc7665f) | Jun 01, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [af6c8f3355](https://linux-hardware.org/?probe=af6c8f3355) | Jun 01, 2023 |
| MSI           | U200                        | Notebook    | [a217267eb0](https://linux-hardware.org/?probe=a217267eb0) | Jun 01, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [d25f4736b7](https://linux-hardware.org/?probe=d25f4736b7) | Jun 01, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [fd232702db](https://linux-hardware.org/?probe=fd232702db) | Jun 01, 2023 |
| Lenovo        | 370B SDK0J40700 WIN 3258... | All in one  | [e98c5409ac](https://linux-hardware.org/?probe=e98c5409ac) | Jun 01, 2023 |
| MSI           | P55-GD55                    | Desktop     | [1400fdf705](https://linux-hardware.org/?probe=1400fdf705) | May 31, 2023 |
| Acer          | Aspire 3830TG               | Notebook    | [abd7d9a412](https://linux-hardware.org/?probe=abd7d9a412) | May 31, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [10f4ef3e86](https://linux-hardware.org/?probe=10f4ef3e86) | May 31, 2023 |
| Dell          | Precision 3550              | Notebook    | [bddf57400b](https://linux-hardware.org/?probe=bddf57400b) | May 31, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [f77ea94512](https://linux-hardware.org/?probe=f77ea94512) | May 31, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [a5ebbfe1ef](https://linux-hardware.org/?probe=a5ebbfe1ef) | May 31, 2023 |
| HP            | Pavilion dv4                | Notebook    | [75797b5ec9](https://linux-hardware.org/?probe=75797b5ec9) | May 31, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [3f08f70d3a](https://linux-hardware.org/?probe=3f08f70d3a) | May 31, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [8092b65afc](https://linux-hardware.org/?probe=8092b65afc) | May 31, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [2139621391](https://linux-hardware.org/?probe=2139621391) | May 31, 2023 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [ebc3d97429](https://linux-hardware.org/?probe=ebc3d97429) | May 30, 2023 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [97382e45f8](https://linux-hardware.org/?probe=97382e45f8) | May 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [7fed965224](https://linux-hardware.org/?probe=7fed965224) | May 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [ac2f40b972](https://linux-hardware.org/?probe=ac2f40b972) | May 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [f45bc9a282](https://linux-hardware.org/?probe=f45bc9a282) | May 30, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [676d83919f](https://linux-hardware.org/?probe=676d83919f) | May 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [c507b25480](https://linux-hardware.org/?probe=c507b25480) | May 30, 2023 |
| HP            | 0B54h D                     | Desktop     | [c7813156eb](https://linux-hardware.org/?probe=c7813156eb) | May 30, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [7de5857b40](https://linux-hardware.org/?probe=7de5857b40) | May 29, 2023 |
| HP            | 2B36                        | Desktop     | [8e4fc0d41f](https://linux-hardware.org/?probe=8e4fc0d41f) | May 29, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [ebb5445720](https://linux-hardware.org/?probe=ebb5445720) | May 29, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [e29eb3dfcc](https://linux-hardware.org/?probe=e29eb3dfcc) | May 29, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d8aa236e2d](https://linux-hardware.org/?probe=d8aa236e2d) | May 28, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [40ba623a3e](https://linux-hardware.org/?probe=40ba623a3e) | May 28, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [c78b5e28f1](https://linux-hardware.org/?probe=c78b5e28f1) | May 28, 2023 |
| Lenovo        | ThinkPad X230 2325SV7       | Notebook    | [6affd0b8ee](https://linux-hardware.org/?probe=6affd0b8ee) | May 28, 2023 |
| HP            | ProBook 6560b               | Notebook    | [972d01f49f](https://linux-hardware.org/?probe=972d01f49f) | May 28, 2023 |
| HP            | ProBook 6560b               | Notebook    | [9fd712c62d](https://linux-hardware.org/?probe=9fd712c62d) | May 28, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [4f1ff269d2](https://linux-hardware.org/?probe=4f1ff269d2) | May 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [b294c91e3a](https://linux-hardware.org/?probe=b294c91e3a) | May 28, 2023 |
| MSI           | Katana GF76 12UGSO          | Notebook    | [fb534d212e](https://linux-hardware.org/?probe=fb534d212e) | May 28, 2023 |
| MSI           | Katana GF76 12UGSO          | Notebook    | [6b753016ff](https://linux-hardware.org/?probe=6b753016ff) | May 28, 2023 |
| Tactus        | GeoFlex 110                 | Convertible | [9ea6e59b81](https://linux-hardware.org/?probe=9ea6e59b81) | May 27, 2023 |
| Tactus        | GeoFlex 110                 | Convertible | [f898014dd5](https://linux-hardware.org/?probe=f898014dd5) | May 27, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | Notebook    | [b7f46e7180](https://linux-hardware.org/?probe=b7f46e7180) | May 27, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [4945ea3fba](https://linux-hardware.org/?probe=4945ea3fba) | May 26, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [5098185f54](https://linux-hardware.org/?probe=5098185f54) | May 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | Notebook    | [a5301f505d](https://linux-hardware.org/?probe=a5301f505d) | May 25, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [1987af2458](https://linux-hardware.org/?probe=1987af2458) | May 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1fea1a6529](https://linux-hardware.org/?probe=1fea1a6529) | May 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [c5baa41ff7](https://linux-hardware.org/?probe=c5baa41ff7) | May 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5c4649a83e](https://linux-hardware.org/?probe=5c4649a83e) | May 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [a03284052b](https://linux-hardware.org/?probe=a03284052b) | May 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [957b9f9de8](https://linux-hardware.org/?probe=957b9f9de8) | May 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [b5e28ef2ab](https://linux-hardware.org/?probe=b5e28ef2ab) | May 23, 2023 |
| HP            | 8876 11                     | Desktop     | [889144e990](https://linux-hardware.org/?probe=889144e990) | May 23, 2023 |
| AMI           | Intel                       | Desktop     | [9ddb291be3](https://linux-hardware.org/?probe=9ddb291be3) | May 22, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [f9103674dc](https://linux-hardware.org/?probe=f9103674dc) | May 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [781e226978](https://linux-hardware.org/?probe=781e226978) | May 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [68caefd4e9](https://linux-hardware.org/?probe=68caefd4e9) | May 22, 2023 |
| Lenovo        | 3753 NOK                    | Desktop     | [f2971c14a7](https://linux-hardware.org/?probe=f2971c14a7) | May 21, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [60ec2d6e04](https://linux-hardware.org/?probe=60ec2d6e04) | May 21, 2023 |
| AMI           | Intel                       | Desktop     | [13f87e64f1](https://linux-hardware.org/?probe=13f87e64f1) | May 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [fa899a9a41](https://linux-hardware.org/?probe=fa899a9a41) | May 21, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [2a95b22ac3](https://linux-hardware.org/?probe=2a95b22ac3) | May 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [19416d3973](https://linux-hardware.org/?probe=19416d3973) | May 21, 2023 |
| Unknown       | HX90                        | Desktop     | [d640a32296](https://linux-hardware.org/?probe=d640a32296) | May 21, 2023 |
| Getac         | V110G3                      | Notebook    | [4a80145aac](https://linux-hardware.org/?probe=4a80145aac) | May 21, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [953734fc80](https://linux-hardware.org/?probe=953734fc80) | May 20, 2023 |
| Lenovo        | 3714 NOK                    | Desktop     | [0da1ff78c6](https://linux-hardware.org/?probe=0da1ff78c6) | May 20, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | Notebook    | [3976703e20](https://linux-hardware.org/?probe=3976703e20) | May 20, 2023 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [c59f2a4b1e](https://linux-hardware.org/?probe=c59f2a4b1e) | May 19, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [09ae9aca26](https://linux-hardware.org/?probe=09ae9aca26) | May 19, 2023 |
| Getac         | V110G3                      | Notebook    | [1b04290d0e](https://linux-hardware.org/?probe=1b04290d0e) | May 19, 2023 |
| ASRock        | 890FX Deluxe4               | Desktop     | [c00eb20149](https://linux-hardware.org/?probe=c00eb20149) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [6c83146909](https://linux-hardware.org/?probe=6c83146909) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [1ed7f81c69](https://linux-hardware.org/?probe=1ed7f81c69) | May 18, 2023 |
| ASUSTek       | ROG Strix G733CX_G743CX     | Notebook    | [744f091c75](https://linux-hardware.org/?probe=744f091c75) | May 18, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [d98feea8ad](https://linux-hardware.org/?probe=d98feea8ad) | May 17, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [a776d86dad](https://linux-hardware.org/?probe=a776d86dad) | May 17, 2023 |
| Gigabyte      | X99-Gaming 5                | Desktop     | [81eee33114](https://linux-hardware.org/?probe=81eee33114) | May 17, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [77675ecccd](https://linux-hardware.org/?probe=77675ecccd) | May 17, 2023 |
| Dell          | 0W0CHX A00                  | Desktop     | [a74974308d](https://linux-hardware.org/?probe=a74974308d) | May 16, 2023 |
| Acer          | Swift SFA16-41              | Notebook    | [8b1e6a5baf](https://linux-hardware.org/?probe=8b1e6a5baf) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [9dd2c4cbee](https://linux-hardware.org/?probe=9dd2c4cbee) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [dfc49eb820](https://linux-hardware.org/?probe=dfc49eb820) | May 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [a4cbf66286](https://linux-hardware.org/?probe=a4cbf66286) | May 16, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [a1d85d1caf](https://linux-hardware.org/?probe=a1d85d1caf) | May 16, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [aeb8c0e04f](https://linux-hardware.org/?probe=aeb8c0e04f) | May 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [0770462dab](https://linux-hardware.org/?probe=0770462dab) | May 15, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [a6ffd0df31](https://linux-hardware.org/?probe=a6ffd0df31) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [bfd8d8244b](https://linux-hardware.org/?probe=bfd8d8244b) | May 15, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [9ed74f5d63](https://linux-hardware.org/?probe=9ed74f5d63) | May 15, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [b4ffbbf7d3](https://linux-hardware.org/?probe=b4ffbbf7d3) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a54f1f4e15](https://linux-hardware.org/?probe=a54f1f4e15) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c01a4de2f3](https://linux-hardware.org/?probe=c01a4de2f3) | May 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2df8fbd5a5](https://linux-hardware.org/?probe=2df8fbd5a5) | May 15, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [f732fbd488](https://linux-hardware.org/?probe=f732fbd488) | May 14, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [59214a0e61](https://linux-hardware.org/?probe=59214a0e61) | May 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [fb58a4d348](https://linux-hardware.org/?probe=fb58a4d348) | May 14, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [745ae69749](https://linux-hardware.org/?probe=745ae69749) | May 14, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [acc449dad2](https://linux-hardware.org/?probe=acc449dad2) | May 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [c164fc1080](https://linux-hardware.org/?probe=c164fc1080) | May 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b4c4fde79d](https://linux-hardware.org/?probe=b4c4fde79d) | May 14, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [970443eea3](https://linux-hardware.org/?probe=970443eea3) | May 14, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [beb403e4e0](https://linux-hardware.org/?probe=beb403e4e0) | May 14, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [65374a707a](https://linux-hardware.org/?probe=65374a707a) | May 14, 2023 |
| Intel         | X79F1 V2.0                  | Desktop     | [a2446b63b3](https://linux-hardware.org/?probe=a2446b63b3) | May 14, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [f5cbf650c3](https://linux-hardware.org/?probe=f5cbf650c3) | May 14, 2023 |
| Schenker      | VISION (E22)                | Notebook    | [582ac3cbf5](https://linux-hardware.org/?probe=582ac3cbf5) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [58c658819c](https://linux-hardware.org/?probe=58c658819c) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [ef9c6905f1](https://linux-hardware.org/?probe=ef9c6905f1) | May 13, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [7f4f38aeb1](https://linux-hardware.org/?probe=7f4f38aeb1) | May 13, 2023 |
| Sony          | SVE1513Z1EB                 | Notebook    | [d47ba48012](https://linux-hardware.org/?probe=d47ba48012) | May 12, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2674c1ddb6](https://linux-hardware.org/?probe=2674c1ddb6) | May 12, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [bb8fe2215b](https://linux-hardware.org/?probe=bb8fe2215b) | May 12, 2023 |
| HP            | 3047h                       | Desktop     | [bb0087d307](https://linux-hardware.org/?probe=bb0087d307) | May 12, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | Desktop     | [f9a67e4a1f](https://linux-hardware.org/?probe=f9a67e4a1f) | May 11, 2023 |
| MSI           | GT70 2PC                    | Notebook    | [c98c889dbf](https://linux-hardware.org/?probe=c98c889dbf) | May 11, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [e855bafa57](https://linux-hardware.org/?probe=e855bafa57) | May 11, 2023 |
| Dell          | Precision 7520              | Notebook    | [184802dbab](https://linux-hardware.org/?probe=184802dbab) | May 11, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [4d4946eec9](https://linux-hardware.org/?probe=4d4946eec9) | May 11, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | Desktop     | [18a4110763](https://linux-hardware.org/?probe=18a4110763) | May 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [ec8e4b5f19](https://linux-hardware.org/?probe=ec8e4b5f19) | May 11, 2023 |
| Itautec       | Infoway w7440               | Notebook    | [41eee30825](https://linux-hardware.org/?probe=41eee30825) | May 11, 2023 |
| Lenovo        | ThinkCentre M71z 1761E4U    | Desktop     | [a865f3d92e](https://linux-hardware.org/?probe=a865f3d92e) | May 11, 2023 |
| Dell          | Latitude E6440              | Notebook    | [ea902a82a4](https://linux-hardware.org/?probe=ea902a82a4) | May 10, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1e4f2a0daf](https://linux-hardware.org/?probe=1e4f2a0daf) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57a74239f8](https://linux-hardware.org/?probe=57a74239f8) | May 10, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [8886b2b825](https://linux-hardware.org/?probe=8886b2b825) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [962ca6e507](https://linux-hardware.org/?probe=962ca6e507) | May 10, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [5921d78ceb](https://linux-hardware.org/?probe=5921d78ceb) | May 10, 2023 |
| Acer          | TravelMate P653-M           | Notebook    | [a0f805c8ca](https://linux-hardware.org/?probe=a0f805c8ca) | May 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [0b797e8428](https://linux-hardware.org/?probe=0b797e8428) | May 10, 2023 |
| Intel         | NUC13ANBi7 M89645-202       | Mini pc     | [6f1e53a7ec](https://linux-hardware.org/?probe=6f1e53a7ec) | May 10, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [69f4dd51d9](https://linux-hardware.org/?probe=69f4dd51d9) | May 10, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [532e5b78de](https://linux-hardware.org/?probe=532e5b78de) | May 09, 2023 |
| MSI           | B85-G43                     | Desktop     | [878fbbb243](https://linux-hardware.org/?probe=878fbbb243) | May 09, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [462a9b182b](https://linux-hardware.org/?probe=462a9b182b) | May 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [fa734dc49a](https://linux-hardware.org/?probe=fa734dc49a) | May 09, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [86136dd98f](https://linux-hardware.org/?probe=86136dd98f) | May 09, 2023 |
| ASRock        | N68-S3 UCC                  | Desktop     | [8a1fbe8e3c](https://linux-hardware.org/?probe=8a1fbe8e3c) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [503204d798](https://linux-hardware.org/?probe=503204d798) | May 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e0fc6f7617](https://linux-hardware.org/?probe=e0fc6f7617) | May 08, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [7b102d2ecc](https://linux-hardware.org/?probe=7b102d2ecc) | May 08, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [5e78ff90cc](https://linux-hardware.org/?probe=5e78ff90cc) | May 08, 2023 |
| TUXEDO        | N24_25BU                    | Notebook    | [9cd4e499ae](https://linux-hardware.org/?probe=9cd4e499ae) | May 07, 2023 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [a9fe0fdf88](https://linux-hardware.org/?probe=a9fe0fdf88) | May 07, 2023 |
| Gateway       | RS780                       | Desktop     | [e04207a390](https://linux-hardware.org/?probe=e04207a390) | May 07, 2023 |
| Dell          | Inspiron 5585               | Notebook    | [f838e48bd3](https://linux-hardware.org/?probe=f838e48bd3) | May 07, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [87e972803c](https://linux-hardware.org/?probe=87e972803c) | May 07, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [c1a5a5b4d9](https://linux-hardware.org/?probe=c1a5a5b4d9) | May 07, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [a86bd404e0](https://linux-hardware.org/?probe=a86bd404e0) | May 07, 2023 |
| Intel         | H61                         | Desktop     | [c359f42a22](https://linux-hardware.org/?probe=c359f42a22) | May 07, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [0c0ad48cc6](https://linux-hardware.org/?probe=0c0ad48cc6) | May 07, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [812ae9a763](https://linux-hardware.org/?probe=812ae9a763) | May 06, 2023 |
| Gigabyte      | G5 MD                       | Notebook    | [7ad914a8a9](https://linux-hardware.org/?probe=7ad914a8a9) | May 06, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [0a66f5d4e4](https://linux-hardware.org/?probe=0a66f5d4e4) | May 06, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [9b843f40a1](https://linux-hardware.org/?probe=9b843f40a1) | May 05, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [dd6f6a940f](https://linux-hardware.org/?probe=dd6f6a940f) | May 05, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [c7b66fbdc3](https://linux-hardware.org/?probe=c7b66fbdc3) | May 05, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [4d21a72bfb](https://linux-hardware.org/?probe=4d21a72bfb) | May 05, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ffab85a31a](https://linux-hardware.org/?probe=ffab85a31a) | May 05, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [dd238f7e60](https://linux-hardware.org/?probe=dd238f7e60) | May 04, 2023 |
| Gigabyte      | X99-Gaming 5                | Desktop     | [e1d1bdef81](https://linux-hardware.org/?probe=e1d1bdef81) | May 04, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [51ae873492](https://linux-hardware.org/?probe=51ae873492) | May 04, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [ce70c65f11](https://linux-hardware.org/?probe=ce70c65f11) | May 03, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [6a70490cd6](https://linux-hardware.org/?probe=6a70490cd6) | May 03, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [8c62d76e28](https://linux-hardware.org/?probe=8c62d76e28) | May 03, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [19a489c33e](https://linux-hardware.org/?probe=19a489c33e) | May 03, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [c26b48854d](https://linux-hardware.org/?probe=c26b48854d) | May 03, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [5989cc1ac0](https://linux-hardware.org/?probe=5989cc1ac0) | May 03, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [9258699383](https://linux-hardware.org/?probe=9258699383) | May 03, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [1909560f36](https://linux-hardware.org/?probe=1909560f36) | May 02, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [553a101cf8](https://linux-hardware.org/?probe=553a101cf8) | May 02, 2023 |
| Lenovo        | 310C SDK0J40697 WIN 3305... | Mini pc     | [c0f2b10022](https://linux-hardware.org/?probe=c0f2b10022) | May 02, 2023 |
| MECHREVO      | WUJIE16 Pro                 | Notebook    | [c19e8370e5](https://linux-hardware.org/?probe=c19e8370e5) | May 02, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [9cee4296b5](https://linux-hardware.org/?probe=9cee4296b5) | May 02, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [a9406a1851](https://linux-hardware.org/?probe=a9406a1851) | May 02, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [17097573de](https://linux-hardware.org/?probe=17097573de) | May 02, 2023 |
| Dell          | 073MMW A02                  | Desktop     | [09a404ced5](https://linux-hardware.org/?probe=09a404ced5) | May 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [7ffccfda78](https://linux-hardware.org/?probe=7ffccfda78) | May 01, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [cf6a478eb1](https://linux-hardware.org/?probe=cf6a478eb1) | May 01, 2023 |
| ASRock        | B650 LiveMixer              | Desktop     | [aecb4b61b4](https://linux-hardware.org/?probe=aecb4b61b4) | May 01, 2023 |
| Shuttle       | DL20N                       | Desktop     | [3f97bcaa08](https://linux-hardware.org/?probe=3f97bcaa08) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [558cde0a43](https://linux-hardware.org/?probe=558cde0a43) | Apr 30, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [2e2b57b3ae](https://linux-hardware.org/?probe=2e2b57b3ae) | Apr 30, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [a1c1008bf1](https://linux-hardware.org/?probe=a1c1008bf1) | Apr 29, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [e47ae2080c](https://linux-hardware.org/?probe=e47ae2080c) | Apr 29, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [3586d79ce4](https://linux-hardware.org/?probe=3586d79ce4) | Apr 29, 2023 |
| HP            | 845A                        | Desktop     | [d0aa2a4a7a](https://linux-hardware.org/?probe=d0aa2a4a7a) | Apr 29, 2023 |
| HP            | 845A                        | Desktop     | [f8bc4601ef](https://linux-hardware.org/?probe=f8bc4601ef) | Apr 29, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [f4eea7ce60](https://linux-hardware.org/?probe=f4eea7ce60) | Apr 29, 2023 |
| Sony          | VPCSB2A7R                   | Notebook    | [f089770d02](https://linux-hardware.org/?probe=f089770d02) | Apr 28, 2023 |
| Sony          | VPCSB2A7R                   | Notebook    | [89f52ca147](https://linux-hardware.org/?probe=89f52ca147) | Apr 28, 2023 |
| HP            | ENVY Notebook               | Notebook    | [89e8149d6e](https://linux-hardware.org/?probe=89e8149d6e) | Apr 28, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [d4bb8a135d](https://linux-hardware.org/?probe=d4bb8a135d) | Apr 28, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [2461a8058f](https://linux-hardware.org/?probe=2461a8058f) | Apr 28, 2023 |
| Pegatron      | Benicia                     | Desktop     | [930452646c](https://linux-hardware.org/?probe=930452646c) | Apr 28, 2023 |
| ASUSTek       | P9D-M Series                | Server      | [44b55b4721](https://linux-hardware.org/?probe=44b55b4721) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | Desktop     | [e8886a7521](https://linux-hardware.org/?probe=e8886a7521) | Apr 28, 2023 |
| Multilaser    | UB820                       | All in one  | [3796d857b1](https://linux-hardware.org/?probe=3796d857b1) | Apr 28, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [3342a295e8](https://linux-hardware.org/?probe=3342a295e8) | Apr 28, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [38c117ee87](https://linux-hardware.org/?probe=38c117ee87) | Apr 28, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [fe959d51ab](https://linux-hardware.org/?probe=fe959d51ab) | Apr 27, 2023 |
| MECHREVO      | X3 Series GK7CP6R           | Notebook    | [c764a98c9d](https://linux-hardware.org/?probe=c764a98c9d) | Apr 27, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [2499c633a5](https://linux-hardware.org/?probe=2499c633a5) | Apr 27, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [4fb9a937f3](https://linux-hardware.org/?probe=4fb9a937f3) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [f810923e5f](https://linux-hardware.org/?probe=f810923e5f) | Apr 27, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [3a1d89d5a0](https://linux-hardware.org/?probe=3a1d89d5a0) | Apr 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [d470349226](https://linux-hardware.org/?probe=d470349226) | Apr 26, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [a0f1823b8e](https://linux-hardware.org/?probe=a0f1823b8e) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [6dec479f55](https://linux-hardware.org/?probe=6dec479f55) | Apr 25, 2023 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [a2875a31b2](https://linux-hardware.org/?probe=a2875a31b2) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [20bf63821f](https://linux-hardware.org/?probe=20bf63821f) | Apr 25, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [5ac7debff3](https://linux-hardware.org/?probe=5ac7debff3) | Apr 25, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [861431db35](https://linux-hardware.org/?probe=861431db35) | Apr 25, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [3c50d5d61c](https://linux-hardware.org/?probe=3c50d5d61c) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [25ac3a297e](https://linux-hardware.org/?probe=25ac3a297e) | Apr 24, 2023 |
| Emdoor        | AG958                       | Notebook    | [a925cf244e](https://linux-hardware.org/?probe=a925cf244e) | Apr 24, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [0e85243397](https://linux-hardware.org/?probe=0e85243397) | Apr 23, 2023 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [f2d4f962d2](https://linux-hardware.org/?probe=f2d4f962d2) | Apr 23, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [e5c6fc2738](https://linux-hardware.org/?probe=e5c6fc2738) | Apr 23, 2023 |
| Intel         | NUC6i7KYB H90766-403        | Mini pc     | [f75685d3be](https://linux-hardware.org/?probe=f75685d3be) | Apr 23, 2023 |
| HUAWEI        | PUM-WDX9-PCB-B1 M1060       | Desktop     | [2c8835f2e2](https://linux-hardware.org/?probe=2c8835f2e2) | Apr 22, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [112a18b586](https://linux-hardware.org/?probe=112a18b586) | Apr 22, 2023 |
| Medion        | E4251                       | Notebook    | [76820d982c](https://linux-hardware.org/?probe=76820d982c) | Apr 22, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [d7ad0ed423](https://linux-hardware.org/?probe=d7ad0ed423) | Apr 22, 2023 |
| Google        | Fleex                       | Notebook    | [19603bb256](https://linux-hardware.org/?probe=19603bb256) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [519c11a569](https://linux-hardware.org/?probe=519c11a569) | Apr 21, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [51ef82c2fd](https://linux-hardware.org/?probe=51ef82c2fd) | Apr 21, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [6e1df0f6ee](https://linux-hardware.org/?probe=6e1df0f6ee) | Apr 21, 2023 |
| Emdoor        | AG958                       | Notebook    | [f7408488b4](https://linux-hardware.org/?probe=f7408488b4) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [888b7bed45](https://linux-hardware.org/?probe=888b7bed45) | Apr 21, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [cc1233b9b9](https://linux-hardware.org/?probe=cc1233b9b9) | Apr 21, 2023 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [15cc4335c7](https://linux-hardware.org/?probe=15cc4335c7) | Apr 21, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [3efc88e5df](https://linux-hardware.org/?probe=3efc88e5df) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [b0b94f2462](https://linux-hardware.org/?probe=b0b94f2462) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [d429a2c865](https://linux-hardware.org/?probe=d429a2c865) | Apr 21, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [84a6fd49fa](https://linux-hardware.org/?probe=84a6fd49fa) | Apr 21, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [aaecae8f5a](https://linux-hardware.org/?probe=aaecae8f5a) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5a9a6c553f](https://linux-hardware.org/?probe=5a9a6c553f) | Apr 20, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [87538ce2ba](https://linux-hardware.org/?probe=87538ce2ba) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8c9f6ec7ef](https://linux-hardware.org/?probe=8c9f6ec7ef) | Apr 20, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [648c4c3622](https://linux-hardware.org/?probe=648c4c3622) | Apr 20, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [f8519c5a20](https://linux-hardware.org/?probe=f8519c5a20) | Apr 20, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [a815ec2fa2](https://linux-hardware.org/?probe=a815ec2fa2) | Apr 19, 2023 |
| HP            | ProBook 4540s               | Notebook    | [1bf512ee24](https://linux-hardware.org/?probe=1bf512ee24) | Apr 19, 2023 |
| Dell          | Precision 3550              | Notebook    | [2f1a7d66f4](https://linux-hardware.org/?probe=2f1a7d66f4) | Apr 19, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [cb5a9be901](https://linux-hardware.org/?probe=cb5a9be901) | Apr 19, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [701110cf4e](https://linux-hardware.org/?probe=701110cf4e) | Apr 19, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [023e96a6fd](https://linux-hardware.org/?probe=023e96a6fd) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [3d2366f479](https://linux-hardware.org/?probe=3d2366f479) | Apr 18, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [6041b126fa](https://linux-hardware.org/?probe=6041b126fa) | Apr 18, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [e816e4de38](https://linux-hardware.org/?probe=e816e4de38) | Apr 18, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [e8e85fe2af](https://linux-hardware.org/?probe=e8e85fe2af) | Apr 18, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [49d7cdd068](https://linux-hardware.org/?probe=49d7cdd068) | Apr 18, 2023 |
| ASRock        | Z790 Taichi                 | Desktop     | [0d25cf28bc](https://linux-hardware.org/?probe=0d25cf28bc) | Apr 17, 2023 |
| MSI           | MS-B0A41                    | Desktop     | [5950f6e73c](https://linux-hardware.org/?probe=5950f6e73c) | Apr 17, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6696ce8fd6](https://linux-hardware.org/?probe=6696ce8fd6) | Apr 17, 2023 |
| Dell          | Precision 3571              | Notebook    | [d1fcff8b8f](https://linux-hardware.org/?probe=d1fcff8b8f) | Apr 17, 2023 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [058029e9f7](https://linux-hardware.org/?probe=058029e9f7) | Apr 17, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [ed2675881e](https://linux-hardware.org/?probe=ed2675881e) | Apr 17, 2023 |
| Dell          | Latitude 5500               | Notebook    | [f4ac637463](https://linux-hardware.org/?probe=f4ac637463) | Apr 16, 2023 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [286c8ef93c](https://linux-hardware.org/?probe=286c8ef93c) | Apr 16, 2023 |
| HP            | 158A                        | Desktop     | [56694ce9a3](https://linux-hardware.org/?probe=56694ce9a3) | Apr 16, 2023 |
| HP            | Pro x360 435 13.3 inch G... | Convertible | [0c49ead576](https://linux-hardware.org/?probe=0c49ead576) | Apr 16, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [3924bb4eb5](https://linux-hardware.org/?probe=3924bb4eb5) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2eb96e4d6e](https://linux-hardware.org/?probe=2eb96e4d6e) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7d34909c86](https://linux-hardware.org/?probe=7d34909c86) | Apr 16, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [3e9d210a94](https://linux-hardware.org/?probe=3e9d210a94) | Apr 16, 2023 |
| Positivo      | C14CR01                     | Notebook    | [a5fc85315a](https://linux-hardware.org/?probe=a5fc85315a) | Apr 16, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [502263c435](https://linux-hardware.org/?probe=502263c435) | Apr 15, 2023 |
| HP            | 802E                        | Desktop     | [d6a1c8ad74](https://linux-hardware.org/?probe=d6a1c8ad74) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3a6ad12afa](https://linux-hardware.org/?probe=3a6ad12afa) | Apr 15, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [33c25e0c22](https://linux-hardware.org/?probe=33c25e0c22) | Apr 15, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [33936188c8](https://linux-hardware.org/?probe=33936188c8) | Apr 15, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [b6615d2b7b](https://linux-hardware.org/?probe=b6615d2b7b) | Apr 15, 2023 |
| ASUSTek       | GR6                         | Desktop     | [9cccf46449](https://linux-hardware.org/?probe=9cccf46449) | Apr 15, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [988cd72346](https://linux-hardware.org/?probe=988cd72346) | Apr 15, 2023 |
| AZW           | GT-R                        | Notebook    | [c37dabb7a7](https://linux-hardware.org/?probe=c37dabb7a7) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [8aa8fd23c6](https://linux-hardware.org/?probe=8aa8fd23c6) | Apr 15, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [2b7836fd04](https://linux-hardware.org/?probe=2b7836fd04) | Apr 14, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [c99626b458](https://linux-hardware.org/?probe=c99626b458) | Apr 14, 2023 |
| MSI           | B85-G43                     | Desktop     | [0363360efa](https://linux-hardware.org/?probe=0363360efa) | Apr 14, 2023 |
| Chuwi         | LapBook Pro                 | Notebook    | [3c8bbf6ec3](https://linux-hardware.org/?probe=3c8bbf6ec3) | Apr 14, 2023 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [b5ce8ee6ec](https://linux-hardware.org/?probe=b5ce8ee6ec) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bbc081e43e](https://linux-hardware.org/?probe=bbc081e43e) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a59a28162e](https://linux-hardware.org/?probe=a59a28162e) | Apr 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [cfe1766d1a](https://linux-hardware.org/?probe=cfe1766d1a) | Apr 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [7ff7c0642f](https://linux-hardware.org/?probe=7ff7c0642f) | Apr 13, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [ea58c893c1](https://linux-hardware.org/?probe=ea58c893c1) | Apr 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [3637a41ac7](https://linux-hardware.org/?probe=3637a41ac7) | Apr 13, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [1b97e4ffc5](https://linux-hardware.org/?probe=1b97e4ffc5) | Apr 12, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [7c28a5666c](https://linux-hardware.org/?probe=7c28a5666c) | Apr 12, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [402a94b1c0](https://linux-hardware.org/?probe=402a94b1c0) | Apr 12, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [d1ecfaf06b](https://linux-hardware.org/?probe=d1ecfaf06b) | Apr 12, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [426140ece2](https://linux-hardware.org/?probe=426140ece2) | Apr 12, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [16ce6e54e0](https://linux-hardware.org/?probe=16ce6e54e0) | Apr 12, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [2d599510b8](https://linux-hardware.org/?probe=2d599510b8) | Apr 12, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f4e6c5f4b6](https://linux-hardware.org/?probe=f4e6c5f4b6) | Apr 12, 2023 |
| Dell          | Precision 5520              | Notebook    | [32eb960b25](https://linux-hardware.org/?probe=32eb960b25) | Apr 12, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [6a1c34f539](https://linux-hardware.org/?probe=6a1c34f539) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1429799ca6](https://linux-hardware.org/?probe=1429799ca6) | Apr 11, 2023 |
| HP            | 1495                        | Desktop     | [762886dcb0](https://linux-hardware.org/?probe=762886dcb0) | Apr 11, 2023 |
| Sony          | VPCSB2A7R                   | Notebook    | [1620c38937](https://linux-hardware.org/?probe=1620c38937) | Apr 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8b8b7e1e4e](https://linux-hardware.org/?probe=8b8b7e1e4e) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [192ca29359](https://linux-hardware.org/?probe=192ca29359) | Apr 11, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [8e2b7b11ec](https://linux-hardware.org/?probe=8e2b7b11ec) | Apr 11, 2023 |
| Lenovo        | ThinkPad T480 20L5S12H00    | Notebook    | [c550410c5b](https://linux-hardware.org/?probe=c550410c5b) | Apr 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [d5e608b74e](https://linux-hardware.org/?probe=d5e608b74e) | Apr 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [e9ba143773](https://linux-hardware.org/?probe=e9ba143773) | Apr 11, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [1daf1b0ff6](https://linux-hardware.org/?probe=1daf1b0ff6) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [1dad85ccf1](https://linux-hardware.org/?probe=1dad85ccf1) | Apr 10, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [1c3cfd94a3](https://linux-hardware.org/?probe=1c3cfd94a3) | Apr 09, 2023 |
| Lenovo        | SKYBAY SDK0J40679 WIN 32... | All in one  | [810692eb45](https://linux-hardware.org/?probe=810692eb45) | Apr 09, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [9f2644807d](https://linux-hardware.org/?probe=9f2644807d) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [bf531c6e34](https://linux-hardware.org/?probe=bf531c6e34) | Apr 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [6aae769b7a](https://linux-hardware.org/?probe=6aae769b7a) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [5a4d307476](https://linux-hardware.org/?probe=5a4d307476) | Apr 09, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [e553db41a3](https://linux-hardware.org/?probe=e553db41a3) | Apr 08, 2023 |
| MACHENIKE     | T58-V                       | Notebook    | [9a70cca135](https://linux-hardware.org/?probe=9a70cca135) | Apr 08, 2023 |
| Huanan        | X99-F8                      | Desktop     | [4b020d6c5a](https://linux-hardware.org/?probe=4b020d6c5a) | Apr 08, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [15c7f69a52](https://linux-hardware.org/?probe=15c7f69a52) | Apr 07, 2023 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [11cc5eca09](https://linux-hardware.org/?probe=11cc5eca09) | Apr 06, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [c2195f003d](https://linux-hardware.org/?probe=c2195f003d) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [62b5ed7cdf](https://linux-hardware.org/?probe=62b5ed7cdf) | Apr 06, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [be741560b8](https://linux-hardware.org/?probe=be741560b8) | Apr 06, 2023 |
| HP            | 21D0                        | Desktop     | [be69723341](https://linux-hardware.org/?probe=be69723341) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [1190aa9be8](https://linux-hardware.org/?probe=1190aa9be8) | Apr 06, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [6611343c84](https://linux-hardware.org/?probe=6611343c84) | Apr 05, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [1dcee27dff](https://linux-hardware.org/?probe=1dcee27dff) | Apr 05, 2023 |
| HP            | 84FD                        | Desktop     | [7e80c3baf0](https://linux-hardware.org/?probe=7e80c3baf0) | Apr 05, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [770d8a9253](https://linux-hardware.org/?probe=770d8a9253) | Apr 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [8c29713fe9](https://linux-hardware.org/?probe=8c29713fe9) | Apr 05, 2023 |
| LG Electro... | Kabylake Platform           | Notebook    | [8b66f7c170](https://linux-hardware.org/?probe=8b66f7c170) | Apr 05, 2023 |
| Dell          | Latitude 5320               | Notebook    | [5549de9c5c](https://linux-hardware.org/?probe=5549de9c5c) | Apr 05, 2023 |
| Dell          | Latitude 5320               | Notebook    | [69e3bad969](https://linux-hardware.org/?probe=69e3bad969) | Apr 05, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [ba4ee67415](https://linux-hardware.org/?probe=ba4ee67415) | Apr 05, 2023 |
| Toshiba       | QOSMIO F750                 | Notebook    | [695bc9e499](https://linux-hardware.org/?probe=695bc9e499) | Apr 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [56119c4c93](https://linux-hardware.org/?probe=56119c4c93) | Apr 05, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [73056011a2](https://linux-hardware.org/?probe=73056011a2) | Apr 04, 2023 |
| ASUSTek       | X99-A II                    | Desktop     | [882dc981fb](https://linux-hardware.org/?probe=882dc981fb) | Apr 04, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [0d1d784767](https://linux-hardware.org/?probe=0d1d784767) | Apr 04, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [5fb3f8e0ef](https://linux-hardware.org/?probe=5fb3f8e0ef) | Apr 04, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [906d900083](https://linux-hardware.org/?probe=906d900083) | Apr 04, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [74a232499a](https://linux-hardware.org/?probe=74a232499a) | Apr 04, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [303d201aa6](https://linux-hardware.org/?probe=303d201aa6) | Apr 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [04afa2e378](https://linux-hardware.org/?probe=04afa2e378) | Apr 04, 2023 |
| MSI           | H81M-E34                    | Desktop     | [5e24c6a44a](https://linux-hardware.org/?probe=5e24c6a44a) | Apr 03, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4061ae40b8](https://linux-hardware.org/?probe=4061ae40b8) | Apr 03, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [c487bcedab](https://linux-hardware.org/?probe=c487bcedab) | Apr 03, 2023 |
| Timi          | RedmiBook 16                | Notebook    | [681c9f1403](https://linux-hardware.org/?probe=681c9f1403) | Apr 03, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [fc6e550ca1](https://linux-hardware.org/?probe=fc6e550ca1) | Apr 03, 2023 |
| Sony          | VPCF236FM                   | Notebook    | [d02623453c](https://linux-hardware.org/?probe=d02623453c) | Apr 03, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [161e53a104](https://linux-hardware.org/?probe=161e53a104) | Apr 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ed69a3bba9](https://linux-hardware.org/?probe=ed69a3bba9) | Apr 02, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [022324033e](https://linux-hardware.org/?probe=022324033e) | Apr 02, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [9ccae5a498](https://linux-hardware.org/?probe=9ccae5a498) | Apr 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [fe4d7e3bd0](https://linux-hardware.org/?probe=fe4d7e3bd0) | Apr 02, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [7d6ecc10d8](https://linux-hardware.org/?probe=7d6ecc10d8) | Apr 02, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [bb490db4a9](https://linux-hardware.org/?probe=bb490db4a9) | Apr 02, 2023 |
| ASRock        | B550 Taichi                 | Desktop     | [cff286981b](https://linux-hardware.org/?probe=cff286981b) | Apr 01, 2023 |
| ASRock        | B550 Taichi                 | Desktop     | [01517a396d](https://linux-hardware.org/?probe=01517a396d) | Apr 01, 2023 |
| HP            | 1495                        | Desktop     | [96ea87fbce](https://linux-hardware.org/?probe=96ea87fbce) | Apr 01, 2023 |
| Star Labs     | StarBook                    | Notebook    | [8712994e3c](https://linux-hardware.org/?probe=8712994e3c) | Apr 01, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [3093c50d3d](https://linux-hardware.org/?probe=3093c50d3d) | Mar 31, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [e670f092d7](https://linux-hardware.org/?probe=e670f092d7) | Mar 31, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [47557561a9](https://linux-hardware.org/?probe=47557561a9) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [d35ddee3e1](https://linux-hardware.org/?probe=d35ddee3e1) | Mar 31, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [40489044a0](https://linux-hardware.org/?probe=40489044a0) | Mar 31, 2023 |
| HP            | 250 G3                      | Notebook    | [519b0e31a8](https://linux-hardware.org/?probe=519b0e31a8) | Mar 30, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [1b3629b77e](https://linux-hardware.org/?probe=1b3629b77e) | Mar 30, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [0672578da7](https://linux-hardware.org/?probe=0672578da7) | Mar 30, 2023 |
| Dell          | Precision M6400             | Notebook    | [293957e2c0](https://linux-hardware.org/?probe=293957e2c0) | Mar 30, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [c6e4da00ac](https://linux-hardware.org/?probe=c6e4da00ac) | Mar 30, 2023 |
| Framework     | Laptop                      | Notebook    | [ef17714efa](https://linux-hardware.org/?probe=ef17714efa) | Mar 30, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [13c66b0e69](https://linux-hardware.org/?probe=13c66b0e69) | Mar 30, 2023 |
| MSI           | H81M-E34                    | Desktop     | [ac06c6037f](https://linux-hardware.org/?probe=ac06c6037f) | Mar 30, 2023 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [eb153b5f5d](https://linux-hardware.org/?probe=eb153b5f5d) | Mar 29, 2023 |
| HP            | Notebook                    | Notebook    | [ea7c0e1a2c](https://linux-hardware.org/?probe=ea7c0e1a2c) | Mar 29, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [0921fd9096](https://linux-hardware.org/?probe=0921fd9096) | Mar 28, 2023 |
| ASRock        | B550 Taichi                 | Desktop     | [94d97c5e0c](https://linux-hardware.org/?probe=94d97c5e0c) | Mar 28, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [497266ad29](https://linux-hardware.org/?probe=497266ad29) | Mar 28, 2023 |
| HP            | 82BF                        | Mini pc     | [305883be65](https://linux-hardware.org/?probe=305883be65) | Mar 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [c393e49ce3](https://linux-hardware.org/?probe=c393e49ce3) | Mar 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e7608e5c20](https://linux-hardware.org/?probe=e7608e5c20) | Mar 28, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [20df1488bd](https://linux-hardware.org/?probe=20df1488bd) | Mar 28, 2023 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [d6a9697313](https://linux-hardware.org/?probe=d6a9697313) | Mar 28, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [384f58a6b1](https://linux-hardware.org/?probe=384f58a6b1) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [66a10dc91a](https://linux-hardware.org/?probe=66a10dc91a) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [ef962f373f](https://linux-hardware.org/?probe=ef962f373f) | Mar 27, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [01a09bc2c7](https://linux-hardware.org/?probe=01a09bc2c7) | Mar 27, 2023 |
| Dell          | Precision 3571              | Notebook    | [13d1ce389d](https://linux-hardware.org/?probe=13d1ce389d) | Mar 27, 2023 |
| Toshiba       | QOSMIO F750                 | Notebook    | [b52a3268f6](https://linux-hardware.org/?probe=b52a3268f6) | Mar 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [a438a0c994](https://linux-hardware.org/?probe=a438a0c994) | Mar 27, 2023 |
| Dell          | G15 5515                    | Notebook    | [9c13066534](https://linux-hardware.org/?probe=9c13066534) | Mar 27, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [a45bc637c9](https://linux-hardware.org/?probe=a45bc637c9) | Mar 27, 2023 |
| MSI           | GT70 2PE                    | Notebook    | [be727f6f39](https://linux-hardware.org/?probe=be727f6f39) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [eef16c5e09](https://linux-hardware.org/?probe=eef16c5e09) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [aaae412a63](https://linux-hardware.org/?probe=aaae412a63) | Mar 26, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [91e01e5646](https://linux-hardware.org/?probe=91e01e5646) | Mar 26, 2023 |
| Lenovo        | ThinkPad T580 20LAS1KA0R    | Notebook    | [db00c2ed37](https://linux-hardware.org/?probe=db00c2ed37) | Mar 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [13e0523db8](https://linux-hardware.org/?probe=13e0523db8) | Mar 26, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [cf11e69c46](https://linux-hardware.org/?probe=cf11e69c46) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [9e318501f5](https://linux-hardware.org/?probe=9e318501f5) | Mar 25, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [bc2447e1e5](https://linux-hardware.org/?probe=bc2447e1e5) | Mar 25, 2023 |
| Lenovo        | 30D2 NOK                    | Desktop     | [dc62baadff](https://linux-hardware.org/?probe=dc62baadff) | Mar 25, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [51276a5f00](https://linux-hardware.org/?probe=51276a5f00) | Mar 25, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [f027c9ca09](https://linux-hardware.org/?probe=f027c9ca09) | Mar 25, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [e6ee9fc566](https://linux-hardware.org/?probe=e6ee9fc566) | Mar 25, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [e678dd580c](https://linux-hardware.org/?probe=e678dd580c) | Mar 25, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [36fece4941](https://linux-hardware.org/?probe=36fece4941) | Mar 24, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [38079fceb0](https://linux-hardware.org/?probe=38079fceb0) | Mar 24, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [5377aa4b23](https://linux-hardware.org/?probe=5377aa4b23) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4731c6e59f](https://linux-hardware.org/?probe=4731c6e59f) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [127173d60b](https://linux-hardware.org/?probe=127173d60b) | Mar 23, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [f1292785cd](https://linux-hardware.org/?probe=f1292785cd) | Mar 23, 2023 |
| Multilaser    | UB820                       | All in one  | [9d056bd8e0](https://linux-hardware.org/?probe=9d056bd8e0) | Mar 23, 2023 |
| realme        | CloudProXXXX                | Notebook    | [aaafa41631](https://linux-hardware.org/?probe=aaafa41631) | Mar 23, 2023 |
| Dell          | XPS 9315                    | Notebook    | [b082aa6edf](https://linux-hardware.org/?probe=b082aa6edf) | Mar 22, 2023 |
| Dell          | XPS 9315                    | Notebook    | [9a14590477](https://linux-hardware.org/?probe=9a14590477) | Mar 22, 2023 |
| Dell          | 0X9M3X A01                  | Desktop     | [38f83864e4](https://linux-hardware.org/?probe=38f83864e4) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | Desktop     | [4b80817d4b](https://linux-hardware.org/?probe=4b80817d4b) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | Desktop     | [9c01b0ee80](https://linux-hardware.org/?probe=9c01b0ee80) | Mar 22, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [821914dc88](https://linux-hardware.org/?probe=821914dc88) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [90ef1729ef](https://linux-hardware.org/?probe=90ef1729ef) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [48f86bde7c](https://linux-hardware.org/?probe=48f86bde7c) | Mar 22, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [88d49f423d](https://linux-hardware.org/?probe=88d49f423d) | Mar 22, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [893f51c005](https://linux-hardware.org/?probe=893f51c005) | Mar 21, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [a1e76aa5c1](https://linux-hardware.org/?probe=a1e76aa5c1) | Mar 21, 2023 |
| MSI           | PRO B660M-A WIFI            | Desktop     | [2184cf01f3](https://linux-hardware.org/?probe=2184cf01f3) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [cd12accab0](https://linux-hardware.org/?probe=cd12accab0) | Mar 21, 2023 |
| Intel         | NUC12WSBv7 M36952-400       | Mini pc     | [f7ecd6ff17](https://linux-hardware.org/?probe=f7ecd6ff17) | Mar 21, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [1400f9afc9](https://linux-hardware.org/?probe=1400f9afc9) | Mar 20, 2023 |
| ASUSTek       | TP500LB                     | Notebook    | [20b2caf568](https://linux-hardware.org/?probe=20b2caf568) | Mar 20, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [0a71696d3b](https://linux-hardware.org/?probe=0a71696d3b) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [3f233b6f9d](https://linux-hardware.org/?probe=3f233b6f9d) | Mar 20, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [b6ffb56057](https://linux-hardware.org/?probe=b6ffb56057) | Mar 20, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [5eee23b1db](https://linux-hardware.org/?probe=5eee23b1db) | Mar 20, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [3b81f87409](https://linux-hardware.org/?probe=3b81f87409) | Mar 20, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [e1c4772d0d](https://linux-hardware.org/?probe=e1c4772d0d) | Mar 19, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [68cf28bafe](https://linux-hardware.org/?probe=68cf28bafe) | Mar 19, 2023 |
| Lenovo        | ThinkPad T480 20L6S64C00    | Notebook    | [d91384b02c](https://linux-hardware.org/?probe=d91384b02c) | Mar 19, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [d7ed5ce80d](https://linux-hardware.org/?probe=d7ed5ce80d) | Mar 19, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [a6fa212cf2](https://linux-hardware.org/?probe=a6fa212cf2) | Mar 19, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [e5be65dd5e](https://linux-hardware.org/?probe=e5be65dd5e) | Mar 19, 2023 |
| HP            | 8056                        | Desktop     | [fa7f589aea](https://linux-hardware.org/?probe=fa7f589aea) | Mar 19, 2023 |
| HP            | 245 G8                      | Notebook    | [5b1606146f](https://linux-hardware.org/?probe=5b1606146f) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [add9634ad5](https://linux-hardware.org/?probe=add9634ad5) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [e2cfab15ef](https://linux-hardware.org/?probe=e2cfab15ef) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [75dd9244fb](https://linux-hardware.org/?probe=75dd9244fb) | Mar 18, 2023 |
| Sony          | SVZ1311C5E                  | Notebook    | [e433359eb9](https://linux-hardware.org/?probe=e433359eb9) | Mar 18, 2023 |
| Dell          | Latitude E5470              | Notebook    | [6565aa43e3](https://linux-hardware.org/?probe=6565aa43e3) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [8a94a38026](https://linux-hardware.org/?probe=8a94a38026) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [31851c4e15](https://linux-hardware.org/?probe=31851c4e15) | Mar 18, 2023 |
| Itautec       | Infoway w7440               | Notebook    | [c1e90dd1a3](https://linux-hardware.org/?probe=c1e90dd1a3) | Mar 18, 2023 |
| HP            | 1495                        | Desktop     | [d83e879ba0](https://linux-hardware.org/?probe=d83e879ba0) | Mar 18, 2023 |
| HP            | 1495                        | Desktop     | [b7b5d46ce0](https://linux-hardware.org/?probe=b7b5d46ce0) | Mar 18, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [3b10072541](https://linux-hardware.org/?probe=3b10072541) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [ecc76a5003](https://linux-hardware.org/?probe=ecc76a5003) | Mar 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [4ff2145364](https://linux-hardware.org/?probe=4ff2145364) | Mar 17, 2023 |
| HP            | 2B36                        | Desktop     | [85c11ec746](https://linux-hardware.org/?probe=85c11ec746) | Mar 17, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [dd58f68013](https://linux-hardware.org/?probe=dd58f68013) | Mar 17, 2023 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [fe5cfbcd29](https://linux-hardware.org/?probe=fe5cfbcd29) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [728c9ad9f5](https://linux-hardware.org/?probe=728c9ad9f5) | Mar 17, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [fbf7dd9d94](https://linux-hardware.org/?probe=fbf7dd9d94) | Mar 17, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c325d4fcb0](https://linux-hardware.org/?probe=c325d4fcb0) | Mar 17, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [e41f82bcfd](https://linux-hardware.org/?probe=e41f82bcfd) | Mar 16, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [8ab2befd31](https://linux-hardware.org/?probe=8ab2befd31) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d6def0b0aa](https://linux-hardware.org/?probe=d6def0b0aa) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [abe67692b9](https://linux-hardware.org/?probe=abe67692b9) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [1a4e62a4a5](https://linux-hardware.org/?probe=1a4e62a4a5) | Mar 16, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [b34a55307e](https://linux-hardware.org/?probe=b34a55307e) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [2eff18f570](https://linux-hardware.org/?probe=2eff18f570) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [2c0d31ff9e](https://linux-hardware.org/?probe=2c0d31ff9e) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [a99c892744](https://linux-hardware.org/?probe=a99c892744) | Mar 16, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [56b19568ce](https://linux-hardware.org/?probe=56b19568ce) | Mar 16, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [40c232c45d](https://linux-hardware.org/?probe=40c232c45d) | Mar 16, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [175eb36378](https://linux-hardware.org/?probe=175eb36378) | Mar 16, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [73a4a38e57](https://linux-hardware.org/?probe=73a4a38e57) | Mar 15, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [eaa24cb538](https://linux-hardware.org/?probe=eaa24cb538) | Mar 15, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | Notebook    | [4853be01f6](https://linux-hardware.org/?probe=4853be01f6) | Mar 14, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [c4be4f7d67](https://linux-hardware.org/?probe=c4be4f7d67) | Mar 14, 2023 |
| Sony          | VPCEB4L1E                   | Notebook    | [d91d243c75](https://linux-hardware.org/?probe=d91d243c75) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [39ded01df5](https://linux-hardware.org/?probe=39ded01df5) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [529e83761c](https://linux-hardware.org/?probe=529e83761c) | Mar 14, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [3afad06d79](https://linux-hardware.org/?probe=3afad06d79) | Mar 14, 2023 |
| Dell          | G5 5587                     | Notebook    | [4ff3c98faf](https://linux-hardware.org/?probe=4ff3c98faf) | Mar 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [5997bff822](https://linux-hardware.org/?probe=5997bff822) | Mar 14, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [b4f32e23c4](https://linux-hardware.org/?probe=b4f32e23c4) | Mar 14, 2023 |
| Gigabyte      | P55M-UD2                    | Desktop     | [74cdc2f679](https://linux-hardware.org/?probe=74cdc2f679) | Mar 14, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [d53fa296bf](https://linux-hardware.org/?probe=d53fa296bf) | Mar 14, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [954055245e](https://linux-hardware.org/?probe=954055245e) | Mar 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [3dc28679cc](https://linux-hardware.org/?probe=3dc28679cc) | Mar 14, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [e1c3ac639e](https://linux-hardware.org/?probe=e1c3ac639e) | Mar 14, 2023 |
| Positivo      | Q464B                       | Notebook    | [5bd9649f43](https://linux-hardware.org/?probe=5bd9649f43) | Mar 14, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [1872bc8b57](https://linux-hardware.org/?probe=1872bc8b57) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [9f6119111f](https://linux-hardware.org/?probe=9f6119111f) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [e1fc53bd25](https://linux-hardware.org/?probe=e1fc53bd25) | Mar 13, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [22ae0716b2](https://linux-hardware.org/?probe=22ae0716b2) | Mar 13, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | Notebook    | [41cee24fa8](https://linux-hardware.org/?probe=41cee24fa8) | Mar 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b0834fe20e](https://linux-hardware.org/?probe=b0834fe20e) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [5329567562](https://linux-hardware.org/?probe=5329567562) | Mar 13, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [4c890ba150](https://linux-hardware.org/?probe=4c890ba150) | Mar 13, 2023 |
| Biostar       | A960D+V3                    | Desktop     | [e18f6a3a84](https://linux-hardware.org/?probe=e18f6a3a84) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [abb73d2e5f](https://linux-hardware.org/?probe=abb73d2e5f) | Mar 13, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [44fc80c7d5](https://linux-hardware.org/?probe=44fc80c7d5) | Mar 13, 2023 |
| Huanan        | X99-F8                      | Desktop     | [2bd21ce3b3](https://linux-hardware.org/?probe=2bd21ce3b3) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [8f1fe0703b](https://linux-hardware.org/?probe=8f1fe0703b) | Mar 12, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [999c455869](https://linux-hardware.org/?probe=999c455869) | Mar 12, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [d5a4dbf55c](https://linux-hardware.org/?probe=d5a4dbf55c) | Mar 12, 2023 |
| EVGA          | X570 FTW WIFI.0             | Desktop     | [ebb7252eb5](https://linux-hardware.org/?probe=ebb7252eb5) | Mar 12, 2023 |
| EVGA          | X570 FTW WIFI.0             | Desktop     | [74001bfcc3](https://linux-hardware.org/?probe=74001bfcc3) | Mar 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ad61830c15](https://linux-hardware.org/?probe=ad61830c15) | Mar 12, 2023 |
| GPD           | G1621-02                    | Notebook    | [21394d0975](https://linux-hardware.org/?probe=21394d0975) | Mar 12, 2023 |
| Medion        | E4251                       | Notebook    | [8b057f3a15](https://linux-hardware.org/?probe=8b057f3a15) | Mar 12, 2023 |
| Lenovo        | ThinkPad T420s 4174CN5      | Notebook    | [2fde637fe7](https://linux-hardware.org/?probe=2fde637fe7) | Mar 12, 2023 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [f4d8b766a9](https://linux-hardware.org/?probe=f4d8b766a9) | Mar 12, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [593c3e084d](https://linux-hardware.org/?probe=593c3e084d) | Mar 12, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [cc73320a47](https://linux-hardware.org/?probe=cc73320a47) | Mar 12, 2023 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [9e24f3fc16](https://linux-hardware.org/?probe=9e24f3fc16) | Mar 12, 2023 |
| HP            | 212B                        | Desktop     | [0d3860ffc6](https://linux-hardware.org/?probe=0d3860ffc6) | Mar 11, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [ac6452184d](https://linux-hardware.org/?probe=ac6452184d) | Mar 11, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [77566542fd](https://linux-hardware.org/?probe=77566542fd) | Mar 11, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [2a7d9091ff](https://linux-hardware.org/?probe=2a7d9091ff) | Mar 11, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [5dfc4ceb2a](https://linux-hardware.org/?probe=5dfc4ceb2a) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [e5f5d4a3d5](https://linux-hardware.org/?probe=e5f5d4a3d5) | Mar 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [5d585fb91b](https://linux-hardware.org/?probe=5d585fb91b) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [e7682656f1](https://linux-hardware.org/?probe=e7682656f1) | Mar 11, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [b53c65e6c9](https://linux-hardware.org/?probe=b53c65e6c9) | Mar 10, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [4492e72dd8](https://linux-hardware.org/?probe=4492e72dd8) | Mar 10, 2023 |
| Medion        | Akoya E6412T                | Notebook    | [d8941697fd](https://linux-hardware.org/?probe=d8941697fd) | Mar 09, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [29a2c22865](https://linux-hardware.org/?probe=29a2c22865) | Mar 09, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [dba3d6498b](https://linux-hardware.org/?probe=dba3d6498b) | Mar 09, 2023 |
| Dell          | Latitude 5590               | Notebook    | [d7d667d45f](https://linux-hardware.org/?probe=d7d667d45f) | Mar 09, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [add9ea7c34](https://linux-hardware.org/?probe=add9ea7c34) | Mar 09, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [e8e1e04dbd](https://linux-hardware.org/?probe=e8e1e04dbd) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | Notebook    | [3f6f0bc1a2](https://linux-hardware.org/?probe=3f6f0bc1a2) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | Notebook    | [04d6eb5847](https://linux-hardware.org/?probe=04d6eb5847) | Mar 08, 2023 |
| MSI           | B75MA-P45                   | Desktop     | [f066452d7d](https://linux-hardware.org/?probe=f066452d7d) | Mar 08, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [2dd91e2cd2](https://linux-hardware.org/?probe=2dd91e2cd2) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [141222a198](https://linux-hardware.org/?probe=141222a198) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [2f2541bbf1](https://linux-hardware.org/?probe=2f2541bbf1) | Mar 08, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [4cc3cc4c17](https://linux-hardware.org/?probe=4cc3cc4c17) | Mar 08, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [4b82b56d82](https://linux-hardware.org/?probe=4b82b56d82) | Mar 08, 2023 |
| Dell          | 0TTDMJ A00                  | Desktop     | [3d321d8069](https://linux-hardware.org/?probe=3d321d8069) | Mar 07, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [3d14886d4c](https://linux-hardware.org/?probe=3d14886d4c) | Mar 07, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [124b1af920](https://linux-hardware.org/?probe=124b1af920) | Mar 07, 2023 |
| Dell          | Latitude 5330               | Notebook    | [c99cbe9970](https://linux-hardware.org/?probe=c99cbe9970) | Mar 07, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [0faa2cd96c](https://linux-hardware.org/?probe=0faa2cd96c) | Mar 06, 2023 |
| ASRock        | H97 Pro4                    | Desktop     | [9ef8ff0b68](https://linux-hardware.org/?probe=9ef8ff0b68) | Mar 06, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [be51d02a20](https://linux-hardware.org/?probe=be51d02a20) | Mar 06, 2023 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [d62df340f9](https://linux-hardware.org/?probe=d62df340f9) | Mar 06, 2023 |
| ASRock        | AB350 Gaming K4             | Desktop     | [896ea5798f](https://linux-hardware.org/?probe=896ea5798f) | Mar 06, 2023 |
| Acer          | Predator PH315-55           | Notebook    | [8465c0241c](https://linux-hardware.org/?probe=8465c0241c) | Mar 06, 2023 |
| Alienware     | Area-51m R2                 | Notebook    | [5726561947](https://linux-hardware.org/?probe=5726561947) | Mar 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [8b7f7b9440](https://linux-hardware.org/?probe=8b7f7b9440) | Mar 05, 2023 |
| Dell          | Inspiron 17-7779            | Notebook    | [24b5bddf1d](https://linux-hardware.org/?probe=24b5bddf1d) | Mar 05, 2023 |
| HP            | 8597                        | Desktop     | [17c1e6efd7](https://linux-hardware.org/?probe=17c1e6efd7) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [ec707b621c](https://linux-hardware.org/?probe=ec707b621c) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [36699f94c9](https://linux-hardware.org/?probe=36699f94c9) | Mar 05, 2023 |
| Google        | Delbin                      | Notebook    | [3817b0d62d](https://linux-hardware.org/?probe=3817b0d62d) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [859a660d90](https://linux-hardware.org/?probe=859a660d90) | Mar 05, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [cb13decef3](https://linux-hardware.org/?probe=cb13decef3) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [ab48c17484](https://linux-hardware.org/?probe=ab48c17484) | Mar 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [ce8df757cc](https://linux-hardware.org/?probe=ce8df757cc) | Mar 04, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [47df9846bb](https://linux-hardware.org/?probe=47df9846bb) | Mar 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [50a27abb52](https://linux-hardware.org/?probe=50a27abb52) | Mar 04, 2023 |
| LG Electro... | 22V240 FAB3                 | All in one  | [163c52fd3c](https://linux-hardware.org/?probe=163c52fd3c) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [645b47cfa2](https://linux-hardware.org/?probe=645b47cfa2) | Mar 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [1fb81359e0](https://linux-hardware.org/?probe=1fb81359e0) | Mar 03, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [c3043c0cba](https://linux-hardware.org/?probe=c3043c0cba) | Mar 03, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [4a80c78c43](https://linux-hardware.org/?probe=4a80c78c43) | Mar 03, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [7dfed91b1f](https://linux-hardware.org/?probe=7dfed91b1f) | Mar 03, 2023 |
| HP            | 212B                        | Desktop     | [45dec8a39c](https://linux-hardware.org/?probe=45dec8a39c) | Mar 03, 2023 |
| Dell          | Latitude 5421               | Notebook    | [16d34b8b56](https://linux-hardware.org/?probe=16d34b8b56) | Mar 03, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [3c74542aad](https://linux-hardware.org/?probe=3c74542aad) | Mar 02, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [7b7db7c319](https://linux-hardware.org/?probe=7b7db7c319) | Mar 02, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [150a75757b](https://linux-hardware.org/?probe=150a75757b) | Mar 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [8bc604606b](https://linux-hardware.org/?probe=8bc604606b) | Mar 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [d209549d77](https://linux-hardware.org/?probe=d209549d77) | Mar 02, 2023 |
| ASUSTek       | PRO A320M-R WI-FI           | Desktop     | [2b64b38f7a](https://linux-hardware.org/?probe=2b64b38f7a) | Mar 01, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [4e540e33b1](https://linux-hardware.org/?probe=4e540e33b1) | Mar 01, 2023 |
| Positivo      | C14CR21                     | Notebook    | [d0041f93e1](https://linux-hardware.org/?probe=d0041f93e1) | Mar 01, 2023 |
| HP            | EliteBook 755 G5            | Notebook    | [4ce3aba673](https://linux-hardware.org/?probe=4ce3aba673) | Feb 28, 2023 |
| Dell          | Latitude E7450              | Notebook    | [0e5fe9d2a7](https://linux-hardware.org/?probe=0e5fe9d2a7) | Feb 28, 2023 |
| ASUSTek       | X550JD                      | Notebook    | [6804351029](https://linux-hardware.org/?probe=6804351029) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [3ab9ad10d8](https://linux-hardware.org/?probe=3ab9ad10d8) | Feb 28, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [e888e1330d](https://linux-hardware.org/?probe=e888e1330d) | Feb 27, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [18fdb45ec1](https://linux-hardware.org/?probe=18fdb45ec1) | Feb 27, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [66b1256bd3](https://linux-hardware.org/?probe=66b1256bd3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [4630f9a67c](https://linux-hardware.org/?probe=4630f9a67c) | Feb 27, 2023 |
| AZW           | GTR V01                     | Mini pc     | [c788211e6d](https://linux-hardware.org/?probe=c788211e6d) | Feb 27, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [4f55a08266](https://linux-hardware.org/?probe=4f55a08266) | Feb 27, 2023 |
| Kllisre       | X79 V2.72S                  | Desktop     | [eb7e4b521c](https://linux-hardware.org/?probe=eb7e4b521c) | Feb 26, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [169d8ef4a8](https://linux-hardware.org/?probe=169d8ef4a8) | Feb 26, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [1213e49ca8](https://linux-hardware.org/?probe=1213e49ca8) | Feb 26, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | Notebook    | [da19f23a14](https://linux-hardware.org/?probe=da19f23a14) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [97b08529eb](https://linux-hardware.org/?probe=97b08529eb) | Feb 26, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [d3d04b2a1e](https://linux-hardware.org/?probe=d3d04b2a1e) | Feb 26, 2023 |
| HP            | Pavilion g6                 | Notebook    | [556c1057a8](https://linux-hardware.org/?probe=556c1057a8) | Feb 26, 2023 |
| System76      | Serval WS                   | Notebook    | [1b136ec80d](https://linux-hardware.org/?probe=1b136ec80d) | Feb 25, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [f80e5503fc](https://linux-hardware.org/?probe=f80e5503fc) | Feb 25, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [6765309d07](https://linux-hardware.org/?probe=6765309d07) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [562517eab4](https://linux-hardware.org/?probe=562517eab4) | Feb 25, 2023 |
| HP            | G60                         | Notebook    | [6e4b159708](https://linux-hardware.org/?probe=6e4b159708) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [e63cbac447](https://linux-hardware.org/?probe=e63cbac447) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [4af0524a44](https://linux-hardware.org/?probe=4af0524a44) | Feb 25, 2023 |
| AZW           | SER                         | Mini pc     | [bca19a22d8](https://linux-hardware.org/?probe=bca19a22d8) | Feb 25, 2023 |
| ASUSTek       | TP500LB                     | Notebook    | [63f7dd2e91](https://linux-hardware.org/?probe=63f7dd2e91) | Feb 24, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [2ea850fc7e](https://linux-hardware.org/?probe=2ea850fc7e) | Feb 24, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [e27e1cd0e8](https://linux-hardware.org/?probe=e27e1cd0e8) | Feb 24, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [408bb96959](https://linux-hardware.org/?probe=408bb96959) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [fea6031cfe](https://linux-hardware.org/?probe=fea6031cfe) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4cf00365ff](https://linux-hardware.org/?probe=4cf00365ff) | Feb 24, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [6d36ab1fcf](https://linux-hardware.org/?probe=6d36ab1fcf) | Feb 24, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [93dfbdd8cd](https://linux-hardware.org/?probe=93dfbdd8cd) | Feb 24, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [aef7584b8c](https://linux-hardware.org/?probe=aef7584b8c) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [79aa51c612](https://linux-hardware.org/?probe=79aa51c612) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [a0bf98bcab](https://linux-hardware.org/?probe=a0bf98bcab) | Feb 23, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [300d88af87](https://linux-hardware.org/?probe=300d88af87) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [f3bb3aa940](https://linux-hardware.org/?probe=f3bb3aa940) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [7d1b0e3db5](https://linux-hardware.org/?probe=7d1b0e3db5) | Feb 23, 2023 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [b2ae4d0b42](https://linux-hardware.org/?probe=b2ae4d0b42) | Feb 23, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [ead0af8ae4](https://linux-hardware.org/?probe=ead0af8ae4) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | Notebook    | [6829c25808](https://linux-hardware.org/?probe=6829c25808) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | Notebook    | [ca9a037662](https://linux-hardware.org/?probe=ca9a037662) | Feb 23, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [235831e22a](https://linux-hardware.org/?probe=235831e22a) | Feb 23, 2023 |
| Dell          | Latitude E5470              | Notebook    | [12a8a55fca](https://linux-hardware.org/?probe=12a8a55fca) | Feb 23, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [af2a414265](https://linux-hardware.org/?probe=af2a414265) | Feb 23, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [0a1b4d8122](https://linux-hardware.org/?probe=0a1b4d8122) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [55c6dbae70](https://linux-hardware.org/?probe=55c6dbae70) | Feb 23, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f0cb288b9f](https://linux-hardware.org/?probe=f0cb288b9f) | Feb 23, 2023 |
| Dell          | Latitude 7410               | Notebook    | [dfa449b870](https://linux-hardware.org/?probe=dfa449b870) | Feb 23, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [2c74210fed](https://linux-hardware.org/?probe=2c74210fed) | Feb 23, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [a39eba7e6a](https://linux-hardware.org/?probe=a39eba7e6a) | Feb 22, 2023 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [87a9510543](https://linux-hardware.org/?probe=87a9510543) | Feb 22, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [63636ce164](https://linux-hardware.org/?probe=63636ce164) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [f98cec9924](https://linux-hardware.org/?probe=f98cec9924) | Feb 22, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [8be573974d](https://linux-hardware.org/?probe=8be573974d) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | Notebook    | [d2aa21118e](https://linux-hardware.org/?probe=d2aa21118e) | Feb 21, 2023 |
| Gigabyte      | AORUS 17 XE4                | Notebook    | [b674e3e1e0](https://linux-hardware.org/?probe=b674e3e1e0) | Feb 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [64b7226700](https://linux-hardware.org/?probe=64b7226700) | Feb 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c61a513a81](https://linux-hardware.org/?probe=c61a513a81) | Feb 20, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [cb6168e276](https://linux-hardware.org/?probe=cb6168e276) | Feb 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [97b147476a](https://linux-hardware.org/?probe=97b147476a) | Feb 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [42750c43b5](https://linux-hardware.org/?probe=42750c43b5) | Feb 20, 2023 |
| ASUSTek       | X99-M WS                    | Desktop     | [69eb540783](https://linux-hardware.org/?probe=69eb540783) | Feb 20, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [d8afec7717](https://linux-hardware.org/?probe=d8afec7717) | Feb 20, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [a3f369f79b](https://linux-hardware.org/?probe=a3f369f79b) | Feb 20, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [4a77848908](https://linux-hardware.org/?probe=4a77848908) | Feb 20, 2023 |
| ASRock        | X570 Taichi Razer Editio... | Desktop     | [3f44c52c3e](https://linux-hardware.org/?probe=3f44c52c3e) | Feb 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [35d0544ea5](https://linux-hardware.org/?probe=35d0544ea5) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [cc447f6c07](https://linux-hardware.org/?probe=cc447f6c07) | Feb 19, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [470ceee356](https://linux-hardware.org/?probe=470ceee356) | Feb 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [703cc27199](https://linux-hardware.org/?probe=703cc27199) | Feb 19, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [f8e02626c5](https://linux-hardware.org/?probe=f8e02626c5) | Feb 19, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [2c41f563a1](https://linux-hardware.org/?probe=2c41f563a1) | Feb 19, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [28e6263489](https://linux-hardware.org/?probe=28e6263489) | Feb 19, 2023 |
| MSI           | B85M-P33 V2                 | Desktop     | [b78aee1c5a](https://linux-hardware.org/?probe=b78aee1c5a) | Feb 19, 2023 |
| HP            | Notebook                    | Notebook    | [2c17c1256f](https://linux-hardware.org/?probe=2c17c1256f) | Feb 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [f73ae7038f](https://linux-hardware.org/?probe=f73ae7038f) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [5ff3cab69f](https://linux-hardware.org/?probe=5ff3cab69f) | Feb 19, 2023 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [45631ae666](https://linux-hardware.org/?probe=45631ae666) | Feb 18, 2023 |
| Dell          | 0X9M3X A04                  | Desktop     | [9b13a670c5](https://linux-hardware.org/?probe=9b13a670c5) | Feb 18, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ab3e07326a](https://linux-hardware.org/?probe=ab3e07326a) | Feb 18, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [3599b137c4](https://linux-hardware.org/?probe=3599b137c4) | Feb 18, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [d6b212b427](https://linux-hardware.org/?probe=d6b212b427) | Feb 18, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | Notebook    | [df01e5357c](https://linux-hardware.org/?probe=df01e5357c) | Feb 18, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [5ecce23878](https://linux-hardware.org/?probe=5ecce23878) | Feb 18, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [13485dcee3](https://linux-hardware.org/?probe=13485dcee3) | Feb 18, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [06d9c4427a](https://linux-hardware.org/?probe=06d9c4427a) | Feb 18, 2023 |
| Dell          | G3 3590                     | Notebook    | [a8a3df007f](https://linux-hardware.org/?probe=a8a3df007f) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [2f3a14eeaa](https://linux-hardware.org/?probe=2f3a14eeaa) | Feb 18, 2023 |
| Intel         | H61                         | Desktop     | [c1a0ccd450](https://linux-hardware.org/?probe=c1a0ccd450) | Feb 17, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [9be992efd0](https://linux-hardware.org/?probe=9be992efd0) | Feb 17, 2023 |
| MSI           | 970A-G43                    | Desktop     | [e02e6e5509](https://linux-hardware.org/?probe=e02e6e5509) | Feb 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [43fbbe7df5](https://linux-hardware.org/?probe=43fbbe7df5) | Feb 17, 2023 |
| HP            | 8053                        | Desktop     | [adbabb5537](https://linux-hardware.org/?probe=adbabb5537) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [7e8c7de460](https://linux-hardware.org/?probe=7e8c7de460) | Feb 17, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | Notebook    | [5e35f0aecc](https://linux-hardware.org/?probe=5e35f0aecc) | Feb 17, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [dc2acd10eb](https://linux-hardware.org/?probe=dc2acd10eb) | Feb 17, 2023 |
| Jumper        | EZbook                      | Notebook    | [82ba62c4b0](https://linux-hardware.org/?probe=82ba62c4b0) | Feb 16, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [e01cd81ae1](https://linux-hardware.org/?probe=e01cd81ae1) | Feb 16, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d98e6087da](https://linux-hardware.org/?probe=d98e6087da) | Feb 16, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [baa2750a13](https://linux-hardware.org/?probe=baa2750a13) | Feb 16, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [c113bd50f3](https://linux-hardware.org/?probe=c113bd50f3) | Feb 16, 2023 |
| Dell          | 0W2F8G A00                  | Desktop     | [aa7bf98168](https://linux-hardware.org/?probe=aa7bf98168) | Feb 16, 2023 |
| Jumper        | EZbook                      | Notebook    | [1009011b57](https://linux-hardware.org/?probe=1009011b57) | Feb 16, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e5e721aaf2](https://linux-hardware.org/?probe=e5e721aaf2) | Feb 16, 2023 |
| Google        | Robo360                     | Notebook    | [744490a82c](https://linux-hardware.org/?probe=744490a82c) | Feb 16, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [a3b4daa09d](https://linux-hardware.org/?probe=a3b4daa09d) | Feb 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e8dc5253a3](https://linux-hardware.org/?probe=e8dc5253a3) | Feb 15, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [3e6dcbc3f9](https://linux-hardware.org/?probe=3e6dcbc3f9) | Feb 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [b53cdde5a7](https://linux-hardware.org/?probe=b53cdde5a7) | Feb 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [e4ee3e1438](https://linux-hardware.org/?probe=e4ee3e1438) | Feb 15, 2023 |
| Google        | Robo360                     | Notebook    | [573d036948](https://linux-hardware.org/?probe=573d036948) | Feb 15, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [713f522b92](https://linux-hardware.org/?probe=713f522b92) | Feb 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6569b3d50d](https://linux-hardware.org/?probe=6569b3d50d) | Feb 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [65a5587c6d](https://linux-hardware.org/?probe=65a5587c6d) | Feb 14, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [1ebc6ae882](https://linux-hardware.org/?probe=1ebc6ae882) | Feb 14, 2023 |
| Acer          | H410H6-M17 P21-A1           | Desktop     | [beaef7f0ab](https://linux-hardware.org/?probe=beaef7f0ab) | Feb 14, 2023 |
| Dell          | XPS 9320                    | Notebook    | [10eb3017b5](https://linux-hardware.org/?probe=10eb3017b5) | Feb 13, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [b4ac56b67d](https://linux-hardware.org/?probe=b4ac56b67d) | Feb 13, 2023 |
| Acer          | Aspire E5-771G              | Notebook    | [d1abb191dd](https://linux-hardware.org/?probe=d1abb191dd) | Feb 13, 2023 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [348fef3dbb](https://linux-hardware.org/?probe=348fef3dbb) | Feb 13, 2023 |
| Shuttle       | FX79R                       | Desktop     | [b1631ebb53](https://linux-hardware.org/?probe=b1631ebb53) | Feb 13, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [8583704242](https://linux-hardware.org/?probe=8583704242) | Feb 13, 2023 |
| Dell          | Latitude 7490               | Notebook    | [c3f07cbb13](https://linux-hardware.org/?probe=c3f07cbb13) | Feb 13, 2023 |
| Dell          | Precision 3571              | Notebook    | [8f7f52dcaa](https://linux-hardware.org/?probe=8f7f52dcaa) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7711c96063](https://linux-hardware.org/?probe=7711c96063) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [88b290f249](https://linux-hardware.org/?probe=88b290f249) | Feb 13, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [6eb24e6e38](https://linux-hardware.org/?probe=6eb24e6e38) | Feb 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [59c1fdfad6](https://linux-hardware.org/?probe=59c1fdfad6) | Feb 12, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [769e8c51f0](https://linux-hardware.org/?probe=769e8c51f0) | Feb 12, 2023 |
| Lenovo        | ThinkPad T430s 2356BQ5      | Notebook    | [fb8b46669e](https://linux-hardware.org/?probe=fb8b46669e) | Feb 12, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [785e6e2876](https://linux-hardware.org/?probe=785e6e2876) | Feb 12, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [f12982699d](https://linux-hardware.org/?probe=f12982699d) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [0a3aa89ac9](https://linux-hardware.org/?probe=0a3aa89ac9) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [69cd397ac6](https://linux-hardware.org/?probe=69cd397ac6) | Feb 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [35781b31c5](https://linux-hardware.org/?probe=35781b31c5) | Feb 12, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [ca16764b59](https://linux-hardware.org/?probe=ca16764b59) | Feb 12, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [5afe7ebf87](https://linux-hardware.org/?probe=5afe7ebf87) | Feb 11, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [2e006be72e](https://linux-hardware.org/?probe=2e006be72e) | Feb 11, 2023 |
| HP            | 3397                        | Desktop     | [b22590d882](https://linux-hardware.org/?probe=b22590d882) | Feb 11, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [cb5573dd52](https://linux-hardware.org/?probe=cb5573dd52) | Feb 11, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [cbdda8d7e0](https://linux-hardware.org/?probe=cbdda8d7e0) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [07eabc1dbf](https://linux-hardware.org/?probe=07eabc1dbf) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [335f1a844e](https://linux-hardware.org/?probe=335f1a844e) | Feb 11, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [270400302e](https://linux-hardware.org/?probe=270400302e) | Feb 10, 2023 |
| Dell          | 0T568R A00                  | Desktop     | [fedf0db748](https://linux-hardware.org/?probe=fedf0db748) | Feb 10, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [e6bcd546ae](https://linux-hardware.org/?probe=e6bcd546ae) | Feb 10, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [2a39868a05](https://linux-hardware.org/?probe=2a39868a05) | Feb 10, 2023 |
| MSI           | GE60 2QE                    | Notebook    | [4d8865f2bd](https://linux-hardware.org/?probe=4d8865f2bd) | Feb 10, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [ef2d2504b8](https://linux-hardware.org/?probe=ef2d2504b8) | Feb 10, 2023 |
| Dell          | Precision 3571              | Notebook    | [85985612ac](https://linux-hardware.org/?probe=85985612ac) | Feb 10, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [a068db4d61](https://linux-hardware.org/?probe=a068db4d61) | Feb 10, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [c81083cd55](https://linux-hardware.org/?probe=c81083cd55) | Feb 10, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [0efa8164b3](https://linux-hardware.org/?probe=0efa8164b3) | Feb 10, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [7a116a53c6](https://linux-hardware.org/?probe=7a116a53c6) | Feb 09, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [530627f086](https://linux-hardware.org/?probe=530627f086) | Feb 09, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [7f27fb0a83](https://linux-hardware.org/?probe=7f27fb0a83) | Feb 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [1f4b88ad7f](https://linux-hardware.org/?probe=1f4b88ad7f) | Feb 09, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [9decf03532](https://linux-hardware.org/?probe=9decf03532) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [157c2ef73f](https://linux-hardware.org/?probe=157c2ef73f) | Feb 09, 2023 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [29e3ebe102](https://linux-hardware.org/?probe=29e3ebe102) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [f5dbc828f3](https://linux-hardware.org/?probe=f5dbc828f3) | Feb 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [95f88cc4d8](https://linux-hardware.org/?probe=95f88cc4d8) | Feb 08, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [dd0daa720e](https://linux-hardware.org/?probe=dd0daa720e) | Feb 08, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [4684c0511e](https://linux-hardware.org/?probe=4684c0511e) | Feb 08, 2023 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [d1f6f6da3a](https://linux-hardware.org/?probe=d1f6f6da3a) | Feb 08, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [9baaf935a7](https://linux-hardware.org/?probe=9baaf935a7) | Feb 08, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [5c86b33fdd](https://linux-hardware.org/?probe=5c86b33fdd) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [3089398556](https://linux-hardware.org/?probe=3089398556) | Feb 08, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [9a73dfae3f](https://linux-hardware.org/?probe=9a73dfae3f) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [07d8f7c1da](https://linux-hardware.org/?probe=07d8f7c1da) | Feb 08, 2023 |
| Lenovo        | Legion S7 16ARHA7 82UG      | Notebook    | [7a2dd12cd8](https://linux-hardware.org/?probe=7a2dd12cd8) | Feb 08, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [dd8fbe3d62](https://linux-hardware.org/?probe=dd8fbe3d62) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [9d81046c8b](https://linux-hardware.org/?probe=9d81046c8b) | Feb 07, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [df487953da](https://linux-hardware.org/?probe=df487953da) | Feb 07, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [a8aa5d2d58](https://linux-hardware.org/?probe=a8aa5d2d58) | Feb 07, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [ad723064e1](https://linux-hardware.org/?probe=ad723064e1) | Feb 06, 2023 |
| ASUSTek       | X550VXK                     | Notebook    | [e7a0aa4ff9](https://linux-hardware.org/?probe=e7a0aa4ff9) | Feb 06, 2023 |
| Dell          | 0W2F8G A00                  | Desktop     | [b0694cfc5c](https://linux-hardware.org/?probe=b0694cfc5c) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [66201d26d7](https://linux-hardware.org/?probe=66201d26d7) | Feb 06, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [97421f92a6](https://linux-hardware.org/?probe=97421f92a6) | Feb 05, 2023 |
| HP            | 3397                        | Desktop     | [a8f8381e48](https://linux-hardware.org/?probe=a8f8381e48) | Feb 05, 2023 |
| HP            | 3397                        | Desktop     | [c41ab8c19e](https://linux-hardware.org/?probe=c41ab8c19e) | Feb 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [add74ba4b4](https://linux-hardware.org/?probe=add74ba4b4) | Feb 05, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [4d3066b96e](https://linux-hardware.org/?probe=4d3066b96e) | Feb 05, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [30d8845f10](https://linux-hardware.org/?probe=30d8845f10) | Feb 05, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [898b87361c](https://linux-hardware.org/?probe=898b87361c) | Feb 05, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [f3cc45d12e](https://linux-hardware.org/?probe=f3cc45d12e) | Feb 05, 2023 |
| Timi          | A34S                        | Notebook    | [97aed45fe2](https://linux-hardware.org/?probe=97aed45fe2) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [66a494b2ec](https://linux-hardware.org/?probe=66a494b2ec) | Feb 04, 2023 |
| MSI           | MEG Z390 ACE                | Desktop     | [0528b7476a](https://linux-hardware.org/?probe=0528b7476a) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [3f0bf3e580](https://linux-hardware.org/?probe=3f0bf3e580) | Feb 04, 2023 |
| Timi          | A34S                        | Notebook    | [55208c4210](https://linux-hardware.org/?probe=55208c4210) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [1998f6f225](https://linux-hardware.org/?probe=1998f6f225) | Feb 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [a9e735ed75](https://linux-hardware.org/?probe=a9e735ed75) | Feb 03, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [139605fcc1](https://linux-hardware.org/?probe=139605fcc1) | Feb 03, 2023 |
| Intel         | H61                         | Desktop     | [4189171d59](https://linux-hardware.org/?probe=4189171d59) | Feb 03, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [62882a0c3e](https://linux-hardware.org/?probe=62882a0c3e) | Feb 03, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [19b6a074e8](https://linux-hardware.org/?probe=19b6a074e8) | Feb 03, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [81f824a063](https://linux-hardware.org/?probe=81f824a063) | Feb 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [5505a27d5e](https://linux-hardware.org/?probe=5505a27d5e) | Feb 03, 2023 |
| Acer          | Predator PH315-55           | Notebook    | [9f90c06d52](https://linux-hardware.org/?probe=9f90c06d52) | Feb 03, 2023 |
| Lenovo        | ThinkPad X230 2324A82       | Notebook    | [2793159580](https://linux-hardware.org/?probe=2793159580) | Feb 03, 2023 |
| GPD           | G1619-04                    | Notebook    | [958fa49a0e](https://linux-hardware.org/?probe=958fa49a0e) | Feb 02, 2023 |
| Acer          | TravelMate P633-M           | Notebook    | [b9bb5f3746](https://linux-hardware.org/?probe=b9bb5f3746) | Feb 02, 2023 |
| Dell          | Vostro 5481                 | Notebook    | [40bc04540d](https://linux-hardware.org/?probe=40bc04540d) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [3a2665872a](https://linux-hardware.org/?probe=3a2665872a) | Feb 02, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [9b2f47d039](https://linux-hardware.org/?probe=9b2f47d039) | Feb 02, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [4f59d41c11](https://linux-hardware.org/?probe=4f59d41c11) | Feb 02, 2023 |
| Dell          | Latitude 7430               | Notebook    | [44d6dd63ce](https://linux-hardware.org/?probe=44d6dd63ce) | Feb 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [b829e9afbd](https://linux-hardware.org/?probe=b829e9afbd) | Feb 01, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [4f06c55846](https://linux-hardware.org/?probe=4f06c55846) | Feb 01, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [115de2faed](https://linux-hardware.org/?probe=115de2faed) | Feb 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [4e438c4768](https://linux-hardware.org/?probe=4e438c4768) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [66459fc07c](https://linux-hardware.org/?probe=66459fc07c) | Jan 31, 2023 |
| Unknown       | ARM5                        | Mini pc     | [aad3a07e37](https://linux-hardware.org/?probe=aad3a07e37) | Jan 31, 2023 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [41ad246a0b](https://linux-hardware.org/?probe=41ad246a0b) | Jan 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f2a2476d45](https://linux-hardware.org/?probe=f2a2476d45) | Jan 31, 2023 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [02c8ae01d1](https://linux-hardware.org/?probe=02c8ae01d1) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [93f5ac8f6d](https://linux-hardware.org/?probe=93f5ac8f6d) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [bacea93055](https://linux-hardware.org/?probe=bacea93055) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [88de348bef](https://linux-hardware.org/?probe=88de348bef) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [070a09add8](https://linux-hardware.org/?probe=070a09add8) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [8cca3cb036](https://linux-hardware.org/?probe=8cca3cb036) | Jan 30, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [a5d6a22838](https://linux-hardware.org/?probe=a5d6a22838) | Jan 30, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [3c0723977c](https://linux-hardware.org/?probe=3c0723977c) | Jan 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [02580dd501](https://linux-hardware.org/?probe=02580dd501) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [8a324e4189](https://linux-hardware.org/?probe=8a324e4189) | Jan 30, 2023 |
| HP            | OMEN by Laptop 15z-en100    | Notebook    | [0c91238954](https://linux-hardware.org/?probe=0c91238954) | Jan 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [830de1d797](https://linux-hardware.org/?probe=830de1d797) | Jan 29, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [42a753536d](https://linux-hardware.org/?probe=42a753536d) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [2fee4a59ba](https://linux-hardware.org/?probe=2fee4a59ba) | Jan 29, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [72e0a3fde5](https://linux-hardware.org/?probe=72e0a3fde5) | Jan 28, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [a1cb8edb5a](https://linux-hardware.org/?probe=a1cb8edb5a) | Jan 28, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [8b5c80cad4](https://linux-hardware.org/?probe=8b5c80cad4) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [2658d00cd2](https://linux-hardware.org/?probe=2658d00cd2) | Jan 28, 2023 |
| MSI           | Modern 14 A10RB             | Notebook    | [619a49b55d](https://linux-hardware.org/?probe=619a49b55d) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [31bda5eb31](https://linux-hardware.org/?probe=31bda5eb31) | Jan 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1aa83fb987](https://linux-hardware.org/?probe=1aa83fb987) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [d4c609c373](https://linux-hardware.org/?probe=d4c609c373) | Jan 27, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [49e82c2714](https://linux-hardware.org/?probe=49e82c2714) | Jan 27, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4a33dd0b76](https://linux-hardware.org/?probe=4a33dd0b76) | Jan 27, 2023 |
| HP            | Compaq 6530b                | Notebook    | [15b987981b](https://linux-hardware.org/?probe=15b987981b) | Jan 27, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [bdfb4aecf9](https://linux-hardware.org/?probe=bdfb4aecf9) | Jan 27, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [65e298b3ee](https://linux-hardware.org/?probe=65e298b3ee) | Jan 27, 2023 |
| Unknown       | ARM5                        | Mini pc     | [1b3ea4360c](https://linux-hardware.org/?probe=1b3ea4360c) | Jan 27, 2023 |
| HUAWEI        | VLT-WX0                     | Notebook    | [270e8da18d](https://linux-hardware.org/?probe=270e8da18d) | Jan 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [5f1e1e4d00](https://linux-hardware.org/?probe=5f1e1e4d00) | Jan 27, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [1ae85a6add](https://linux-hardware.org/?probe=1ae85a6add) | Jan 27, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [7f9b52e91c](https://linux-hardware.org/?probe=7f9b52e91c) | Jan 27, 2023 |
| Lenovo        | ThinkPad X230 23254UY       | Notebook    | [130aeb9cc4](https://linux-hardware.org/?probe=130aeb9cc4) | Jan 27, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5269e78083](https://linux-hardware.org/?probe=5269e78083) | Jan 26, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [b1e29a464f](https://linux-hardware.org/?probe=b1e29a464f) | Jan 26, 2023 |
| Lenovo        | ThinkPad T490 20N20048GE    | Notebook    | [54915be6bc](https://linux-hardware.org/?probe=54915be6bc) | Jan 26, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [5c55d923ff](https://linux-hardware.org/?probe=5c55d923ff) | Jan 26, 2023 |
| Intel         | DG965SS AAD41678-306        | Desktop     | [fde41db330](https://linux-hardware.org/?probe=fde41db330) | Jan 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [26f46d5b40](https://linux-hardware.org/?probe=26f46d5b40) | Jan 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [f1e6112f8c](https://linux-hardware.org/?probe=f1e6112f8c) | Jan 25, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [027f04536c](https://linux-hardware.org/?probe=027f04536c) | Jan 25, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [78a1bfaac7](https://linux-hardware.org/?probe=78a1bfaac7) | Jan 25, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [6f06d51c7a](https://linux-hardware.org/?probe=6f06d51c7a) | Jan 25, 2023 |
| HP            | EliteBook x360 830 G6       | Convertible | [d23feafd62](https://linux-hardware.org/?probe=d23feafd62) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | Desktop     | [026efbc485](https://linux-hardware.org/?probe=026efbc485) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | Desktop     | [184de230c5](https://linux-hardware.org/?probe=184de230c5) | Jan 25, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [405a60b1e3](https://linux-hardware.org/?probe=405a60b1e3) | Jan 24, 2023 |
| realme        | CloudProXXXX                | Notebook    | [520d929687](https://linux-hardware.org/?probe=520d929687) | Jan 24, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [51d8d1eb34](https://linux-hardware.org/?probe=51d8d1eb34) | Jan 24, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [bf22d53528](https://linux-hardware.org/?probe=bf22d53528) | Jan 24, 2023 |
| Dell          | Inspiron 7573               | Convertible | [855d0fd69b](https://linux-hardware.org/?probe=855d0fd69b) | Jan 24, 2023 |
| Dell          | Inspiron 7573               | Convertible | [f2df75c3db](https://linux-hardware.org/?probe=f2df75c3db) | Jan 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a715541f02](https://linux-hardware.org/?probe=a715541f02) | Jan 24, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [213b4b45e5](https://linux-hardware.org/?probe=213b4b45e5) | Jan 24, 2023 |
| Dell          | XPS 9320                    | Notebook    | [e6a308392c](https://linux-hardware.org/?probe=e6a308392c) | Jan 23, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [996a0567b6](https://linux-hardware.org/?probe=996a0567b6) | Jan 23, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [b67d126993](https://linux-hardware.org/?probe=b67d126993) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [7f1bb5c3c3](https://linux-hardware.org/?probe=7f1bb5c3c3) | Jan 23, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [495cd98904](https://linux-hardware.org/?probe=495cd98904) | Jan 23, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [f74d2ca84b](https://linux-hardware.org/?probe=f74d2ca84b) | Jan 23, 2023 |
| realme        | CloudProXXXX                | Notebook    | [8ba70a4617](https://linux-hardware.org/?probe=8ba70a4617) | Jan 23, 2023 |
| realme        | CloudProXXXX                | Notebook    | [e5cbb75254](https://linux-hardware.org/?probe=e5cbb75254) | Jan 23, 2023 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [3afbe94c21](https://linux-hardware.org/?probe=3afbe94c21) | Jan 23, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [f45af20da6](https://linux-hardware.org/?probe=f45af20da6) | Jan 23, 2023 |
| Acer          | Aspire C22-865              | All in one  | [eb0191f969](https://linux-hardware.org/?probe=eb0191f969) | Jan 23, 2023 |
| System76      | Darter UltraThin            | Notebook    | [47f56a1f2d](https://linux-hardware.org/?probe=47f56a1f2d) | Jan 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [a8d203f94b](https://linux-hardware.org/?probe=a8d203f94b) | Jan 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [a8ee7729d5](https://linux-hardware.org/?probe=a8ee7729d5) | Jan 23, 2023 |
| Medion        | E4251                       | Notebook    | [7c90da8c5f](https://linux-hardware.org/?probe=7c90da8c5f) | Jan 23, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [75f64e4cd4](https://linux-hardware.org/?probe=75f64e4cd4) | Jan 22, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [8a68388e16](https://linux-hardware.org/?probe=8a68388e16) | Jan 22, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [394be1956b](https://linux-hardware.org/?probe=394be1956b) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [348a78bb64](https://linux-hardware.org/?probe=348a78bb64) | Jan 22, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [1261e08a8a](https://linux-hardware.org/?probe=1261e08a8a) | Jan 22, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [8e4b1011d8](https://linux-hardware.org/?probe=8e4b1011d8) | Jan 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [c6a463e92f](https://linux-hardware.org/?probe=c6a463e92f) | Jan 22, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [d1e0b2e009](https://linux-hardware.org/?probe=d1e0b2e009) | Jan 22, 2023 |
| Samsung       | 730QDA                      | Convertible | [4796f92a58](https://linux-hardware.org/?probe=4796f92a58) | Jan 22, 2023 |
| Samsung       | 730QDA                      | Convertible | [bbd0fe538f](https://linux-hardware.org/?probe=bbd0fe538f) | Jan 22, 2023 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [a51b58dfbb](https://linux-hardware.org/?probe=a51b58dfbb) | Jan 22, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [21f62b0eac](https://linux-hardware.org/?probe=21f62b0eac) | Jan 21, 2023 |
| Toshiba       | Satellite C50-C             | Notebook    | [3512195f65](https://linux-hardware.org/?probe=3512195f65) | Jan 21, 2023 |
| Dell          | G7 7700                     | Notebook    | [427a79e665](https://linux-hardware.org/?probe=427a79e665) | Jan 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bc55bf24ac](https://linux-hardware.org/?probe=bc55bf24ac) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [be39389c7f](https://linux-hardware.org/?probe=be39389c7f) | Jan 21, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0d8275b0de](https://linux-hardware.org/?probe=0d8275b0de) | Jan 21, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [8de3cfc52e](https://linux-hardware.org/?probe=8de3cfc52e) | Jan 21, 2023 |
| Acer          | Swift SF314-57              | Notebook    | [6a813e0dd0](https://linux-hardware.org/?probe=6a813e0dd0) | Jan 20, 2023 |
| HP            | 85A2                        | All in one  | [13fcd2dd69](https://linux-hardware.org/?probe=13fcd2dd69) | Jan 20, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [d77592ccf0](https://linux-hardware.org/?probe=d77592ccf0) | Jan 20, 2023 |
| Acer          | Aspire C22-865              | All in one  | [90ea1c9655](https://linux-hardware.org/?probe=90ea1c9655) | Jan 19, 2023 |
| Dell          | Latitude E5440              | Notebook    | [b1ac8af8ad](https://linux-hardware.org/?probe=b1ac8af8ad) | Jan 19, 2023 |
| Dell          | Latitude E5440              | Notebook    | [9b6d732a7c](https://linux-hardware.org/?probe=9b6d732a7c) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [9620f447dd](https://linux-hardware.org/?probe=9620f447dd) | Jan 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [2135c30983](https://linux-hardware.org/?probe=2135c30983) | Jan 19, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [19eabab270](https://linux-hardware.org/?probe=19eabab270) | Jan 19, 2023 |
| AZW           | SER V01                     | Mini pc     | [b209807db5](https://linux-hardware.org/?probe=b209807db5) | Jan 19, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [96e072d33f](https://linux-hardware.org/?probe=96e072d33f) | Jan 18, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d0a387f425](https://linux-hardware.org/?probe=d0a387f425) | Jan 18, 2023 |
| Gigabyte      | H77-D3H                     | Desktop     | [15da5de3ae](https://linux-hardware.org/?probe=15da5de3ae) | Jan 18, 2023 |
| MSI           | H81I                        | Desktop     | [f51db4589d](https://linux-hardware.org/?probe=f51db4589d) | Jan 18, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [39591416ac](https://linux-hardware.org/?probe=39591416ac) | Jan 18, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [b796ac9a1d](https://linux-hardware.org/?probe=b796ac9a1d) | Jan 17, 2023 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [d8d6e517e0](https://linux-hardware.org/?probe=d8d6e517e0) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | Notebook    | [a49c7ed379](https://linux-hardware.org/?probe=a49c7ed379) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | Notebook    | [9d20f03ffd](https://linux-hardware.org/?probe=9d20f03ffd) | Jan 17, 2023 |
| HP            | 805A                        | Desktop     | [0f9521809b](https://linux-hardware.org/?probe=0f9521809b) | Jan 17, 2023 |
| HP            | 805A                        | Desktop     | [4061c209e2](https://linux-hardware.org/?probe=4061c209e2) | Jan 17, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [4df4c5ecc8](https://linux-hardware.org/?probe=4df4c5ecc8) | Jan 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c2c13271fd](https://linux-hardware.org/?probe=c2c13271fd) | Jan 17, 2023 |
| Dell          | Inspiron 5585               | Notebook    | [b92481ca4e](https://linux-hardware.org/?probe=b92481ca4e) | Jan 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [6c8a25d916](https://linux-hardware.org/?probe=6c8a25d916) | Jan 16, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [9816a244b2](https://linux-hardware.org/?probe=9816a244b2) | Jan 16, 2023 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [9c5bf0d05c](https://linux-hardware.org/?probe=9c5bf0d05c) | Jan 16, 2023 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [8cd20f181b](https://linux-hardware.org/?probe=8cd20f181b) | Jan 16, 2023 |
| Biostar       | A320MH                      | Desktop     | [1736406da7](https://linux-hardware.org/?probe=1736406da7) | Jan 16, 2023 |
| Acer          | Aspire 8942G                | Notebook    | [907b837cec](https://linux-hardware.org/?probe=907b837cec) | Jan 16, 2023 |
| Intel         | X99                         | Desktop     | [9c0ea1f762](https://linux-hardware.org/?probe=9c0ea1f762) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [a159136180](https://linux-hardware.org/?probe=a159136180) | Jan 16, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [6a0a4494d3](https://linux-hardware.org/?probe=6a0a4494d3) | Jan 16, 2023 |
| HP            | ProBook 655 G1              | Notebook    | [e5f3b2835d](https://linux-hardware.org/?probe=e5f3b2835d) | Jan 16, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [02178066f5](https://linux-hardware.org/?probe=02178066f5) | Jan 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [958ecc4388](https://linux-hardware.org/?probe=958ecc4388) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | Desktop     | [7d1227f25f](https://linux-hardware.org/?probe=7d1227f25f) | Jan 15, 2023 |
| ASUSTek       | GD30CI                      | Desktop     | [2ed7e76dbe](https://linux-hardware.org/?probe=2ed7e76dbe) | Jan 15, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [436a4fc2a0](https://linux-hardware.org/?probe=436a4fc2a0) | Jan 15, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [06dfad94f5](https://linux-hardware.org/?probe=06dfad94f5) | Jan 15, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [4b877715b1](https://linux-hardware.org/?probe=4b877715b1) | Jan 15, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [9ac53f405e](https://linux-hardware.org/?probe=9ac53f405e) | Jan 15, 2023 |
| LG Electro... | 17Z90N-R.AAS9U1             | Notebook    | [9d6736bccd](https://linux-hardware.org/?probe=9d6736bccd) | Jan 15, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ebe7fa8c2a](https://linux-hardware.org/?probe=ebe7fa8c2a) | Jan 14, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [52b5182480](https://linux-hardware.org/?probe=52b5182480) | Jan 14, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [47aa34eddd](https://linux-hardware.org/?probe=47aa34eddd) | Jan 14, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [e92f01ff78](https://linux-hardware.org/?probe=e92f01ff78) | Jan 14, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [4a0fec8aef](https://linux-hardware.org/?probe=4a0fec8aef) | Jan 14, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [699d727f84](https://linux-hardware.org/?probe=699d727f84) | Jan 14, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [05744a666a](https://linux-hardware.org/?probe=05744a666a) | Jan 13, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [5bcda073b3](https://linux-hardware.org/?probe=5bcda073b3) | Jan 13, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [00348d3769](https://linux-hardware.org/?probe=00348d3769) | Jan 13, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [7a7e087ebb](https://linux-hardware.org/?probe=7a7e087ebb) | Jan 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [73533cda86](https://linux-hardware.org/?probe=73533cda86) | Jan 13, 2023 |
| Lenovo        | ThinkPad X270 20K5S1A524    | Notebook    | [e4eaef80f8](https://linux-hardware.org/?probe=e4eaef80f8) | Jan 13, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [ff2c48315e](https://linux-hardware.org/?probe=ff2c48315e) | Jan 13, 2023 |
| realme        | CloudProXXXX                | Notebook    | [25d1a9b890](https://linux-hardware.org/?probe=25d1a9b890) | Jan 13, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3cd650450c](https://linux-hardware.org/?probe=3cd650450c) | Jan 12, 2023 |
| MACHENIKE     | MACHCREATOR-16              | Notebook    | [fbb327effe](https://linux-hardware.org/?probe=fbb327effe) | Jan 12, 2023 |
| Shuttle       | FS61                        | Desktop     | [9034ce313b](https://linux-hardware.org/?probe=9034ce313b) | Jan 12, 2023 |
| HP            | Pavilion 15                 | Notebook    | [1dc150e9db](https://linux-hardware.org/?probe=1dc150e9db) | Jan 12, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Manjaro        | 2800      | 38.83%  |
| Manjaro 22.0.0 | 323       | 4.48%   |
| Manjaro 20.1   | 291       | 4.04%   |
| Manjaro 20.2.1 | 283       | 3.93%   |
| Manjaro 20.2   | 243       | 3.37%   |
| Manjaro 20.0.3 | 223       | 3.09%   |
| Manjaro 21.2.6 | 176       | 2.44%   |
| Manjaro 21.1.0 | 149       | 2.07%   |
| Manjaro 18.1.5 | 143       | 1.98%   |
| Manjaro 21.2.0 | 127       | 1.76%   |
| Manjaro 21.2.5 | 126       | 1.75%   |
| Manjaro 21.1.6 | 114       | 1.58%   |
| Manjaro 21.0.7 | 113       | 1.57%   |
| Manjaro 20.0   | 101       | 1.4%    |
| Manjaro 19.0.2 | 97        | 1.35%   |
| Manjaro 18.0.4 | 96        | 1.33%   |
| Manjaro 21.0   | 87        | 1.21%   |
| Manjaro 21.0.5 | 80        | 1.11%   |
| Manjaro 20.1.2 | 80        | 1.11%   |
| Manjaro 21.2.3 | 74        | 1.03%   |
| Manjaro 21.2.1 | 73        | 1.01%   |
| Manjaro 22.1.0 | 72        | 1%      |
| Manjaro 20.1.1 | 71        | 0.98%   |
| Manjaro 20.0.1 | 69        | 0.96%   |
| Manjaro 22.0.4 | 56        | 0.78%   |
| Manjaro 21.3.7 | 56        | 0.78%   |
| Manjaro 21.3.6 | 50        | 0.69%   |
| Manjaro 21.0.4 | 50        | 0.69%   |
| Manjaro 21.2.2 | 46        | 0.64%   |
| Manjaro 21.2.4 | 45        | 0.62%   |
| Manjaro 21.1.2 | 41        | 0.57%   |
| Manjaro 21.1.4 | 37        | 0.51%   |
| Manjaro 21.0.1 | 36        | 0.5%    |
| Manjaro 22.0.5 | 35        | 0.49%   |
| Manjaro 21.0.2 | 34        | 0.47%   |
| Manjaro 21.3.1 | 32        | 0.44%   |
| Manjaro 21.3.0 | 31        | 0.43%   |
| Manjaro 21.0.3 | 31        | 0.43%   |
| Manjaro 22.1.1 | 30        | 0.42%   |
| Manjaro 21.1.1 | 30        | 0.42%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Manjaro | 6610      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.9.16-1-MANJARO  | 294       | 3.74%   |
| 5.13.19-2-MANJARO | 180       | 2.29%   |
| 5.8.6-1-MANJARO   | 140       | 1.78%   |
| 5.9.11-3-MANJARO  | 129       | 1.64%   |
| 5.8.11-1-MANJARO  | 122       | 1.55%   |
| 5.15.28-1-MANJARO | 118       | 1.5%    |
| 5.10.42-1-MANJARO | 102       | 1.3%    |
| 6.1.1-1-MANJARO   | 101       | 1.28%   |
| 5.8.18-1-MANJARO  | 101       | 1.28%   |
| 5.15.32-1-MANJARO | 100       | 1.27%   |
| 6.1.12-1-MANJARO  | 86        | 1.09%   |
| 5.15.12-1-MANJARO | 82        | 1.04%   |
| 5.6.16-1-MANJARO  | 74        | 0.94%   |
| 5.15.60-1-MANJARO | 74        | 0.94%   |
| 5.8.16-2-MANJARO  | 73        | 0.93%   |
| 5.10.2-2-MANJARO  | 65        | 0.83%   |
| 5.15.65-1-MANJARO | 62        | 0.79%   |
| 5.7.9-1-MANJARO   | 61        | 0.78%   |
| 5.10.36-2-MANJARO | 61        | 0.78%   |
| 5.6.19-2-MANJARO  | 60        | 0.76%   |
| 5.10.7-3-MANJARO  | 60        | 0.76%   |
| 5.7.0-3-MANJARO   | 58        | 0.74%   |
| 5.8.3-2-MANJARO   | 57        | 0.72%   |
| 5.6.15-1-MANJARO  | 57        | 0.72%   |
| 5.12.9-1-MANJARO  | 54        | 0.69%   |
| 5.7.17-2-MANJARO  | 52        | 0.66%   |
| 5.15.78-1-MANJARO | 51        | 0.65%   |
| 5.15.41-1-MANJARO | 51        | 0.65%   |
| 5.14.10-1-MANJARO | 51        | 0.65%   |
| 5.9.1-1-MANJARO   | 50        | 0.64%   |
| 5.17.1-3-MANJARO  | 49        | 0.62%   |
| 5.10.23-1-MANJARO | 49        | 0.62%   |
| 5.16.14-1-MANJARO | 48        | 0.61%   |
| 5.15.74-3-MANJARO | 48        | 0.61%   |
| 5.15.7-1-MANJARO  | 48        | 0.61%   |
| 5.11.6-1-MANJARO  | 47        | 0.6%    |
| 5.15.85-1-MANJARO | 45        | 0.57%   |
| 5.15.25-1-MANJARO | 45        | 0.57%   |
| 5.10.34-1-MANJARO | 45        | 0.57%   |
| 5.6.12-1-MANJARO  | 44        | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.16  | 294       | 3.74%   |
| 5.13.19 | 181       | 2.3%    |
| 5.8.6   | 140       | 1.78%   |
| 5.9.11  | 136       | 1.73%   |
| 5.8.11  | 123       | 1.56%   |
| 5.15.28 | 118       | 1.5%    |
| 5.10.42 | 102       | 1.3%    |
| 6.1.1   | 101       | 1.28%   |
| 5.8.18  | 101       | 1.28%   |
| 5.15.32 | 101       | 1.28%   |
| 6.1.12  | 86        | 1.09%   |
| 5.15.12 | 82        | 1.04%   |
| 5.8.16  | 74        | 0.94%   |
| 5.6.16  | 74        | 0.94%   |
| 5.15.60 | 74        | 0.94%   |
| 5.7.0   | 73        | 0.93%   |
| 5.9.1   | 69        | 0.88%   |
| 5.6.19  | 66        | 0.84%   |
| 5.10.2  | 65        | 0.83%   |
| 5.15.65 | 62        | 0.79%   |
| 5.10.7  | 62        | 0.79%   |
| 5.7.9   | 61        | 0.78%   |
| 5.17.1  | 61        | 0.78%   |
| 5.10.36 | 61        | 0.78%   |
| 5.8.3   | 58        | 0.74%   |
| 5.6.15  | 57        | 0.72%   |
| 5.12.9  | 54        | 0.69%   |
| 5.7.17  | 53        | 0.67%   |
| 5.15.78 | 51        | 0.65%   |
| 5.15.41 | 51        | 0.65%   |
| 5.14.10 | 51        | 0.65%   |
| 5.15.7  | 50        | 0.64%   |
| 5.15.74 | 49        | 0.62%   |
| 5.10.23 | 49        | 0.62%   |
| 5.16.14 | 48        | 0.61%   |
| 5.11.6  | 48        | 0.61%   |
| 5.6.12  | 46        | 0.58%   |
| 5.15.2  | 46        | 0.58%   |
| 5.15.85 | 45        | 0.57%   |
| 5.15.25 | 45        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 1243      | 16.82%  |
| 5.10    | 919       | 12.44%  |
| 5.4     | 629       | 8.51%   |
| 5.9     | 590       | 7.98%   |
| 5.8     | 553       | 7.48%   |
| 6.1     | 494       | 6.69%   |
| 5.6     | 393       | 5.32%   |
| 5.13    | 358       | 4.85%   |
| 5.7     | 264       | 3.57%   |
| 4.19    | 198       | 2.68%   |
| 5.11    | 185       | 2.5%    |
| 5.16    | 175       | 2.37%   |
| 5.12    | 157       | 2.12%   |
| 5.14    | 153       | 2.07%   |
| 6.0     | 151       | 2.04%   |
| 5.17    | 142       | 1.92%   |
| 5.19    | 138       | 1.87%   |
| 5.18    | 130       | 1.76%   |
| 5.5     | 109       | 1.48%   |
| 5.3     | 92        | 1.25%   |
| 6.2     | 80        | 1.08%   |
| 4.14    | 60        | 0.81%   |
| 5.2     | 41        | 0.55%   |
| 6.3     | 37        | 0.5%    |
| 5.0     | 30        | 0.41%   |
| 5.1     | 26        | 0.35%   |
| 4.20    | 14        | 0.19%   |
| 4.18    | 12        | 0.16%   |
| 4.9     | 4         | 0.05%   |
| 4.16    | 4         | 0.05%   |
| 4.17    | 3         | 0.04%   |
| 4.7     | 2         | 0.03%   |
| 4.4     | 2         | 0.03%   |
| 6.4     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6607      | 99.95%  |
| i686    | 2         | 0.03%   |
| aarch64 | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| KDE5                     | 2488      | 36.34%  |
| XFCE                     | 1465      | 21.4%   |
| GNOME                    | 1429      | 20.87%  |
| KDE                      | 560       | 8.18%   |
| Unknown                  | 314       | 4.59%   |
| X-Cinnamon               | 177       | 2.59%   |
| i3                       | 130       | 1.9%    |
| MATE                     | 61        | 0.89%   |
| Cinnamon                 | 56        | 0.82%   |
| Deepin                   | 50        | 0.73%   |
| Budgie                   | 30        | 0.44%   |
| awesome                  | 17        | 0.25%   |
| LXQt                     | 16        | 0.23%   |
| sway                     | 12        | 0.18%   |
| LXDE                     | 7         | 0.1%    |
| Bspwm                    | 5         | 0.07%   |
| i3-with-shmlog           | 4         | 0.06%   |
| GNOME Classic            | 3         | 0.04%   |
| DWM                      | 3         | 0.04%   |
| Yaru:ubuntu:GNOME        | 2         | 0.03%   |
| qtile                    | 2         | 0.03%   |
| LeftWM                   | 2         | 0.03%   |
| ICEWM                    | 2         | 0.03%   |
| GNOME Flashback          | 2         | 0.03%   |
| Enlightenment            | 2         | 0.03%   |
| xinitrc                  | 1         | 0.01%   |
| Unity                    | 1         | 0.01%   |
| swayLANG=en_CA.UTF-8     | 1         | 0.01%   |
| openbox                  | 1         | 0.01%   |
| Hyprland                 | 1         | 0.01%   |
| herbstluftwm             | 1         | 0.01%   |
| /usr/bin/openbox-session | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5712      | 84.99%  |
| Wayland | 806       | 11.99%  |
| Unknown | 138       | 2.05%   |
| Tty     | 65        | 0.97%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2780      | 40.97%  |
| SDDM    | 1725      | 25.42%  |
| LightDM | 1167      | 17.2%   |
| GDM     | 870       | 12.82%  |
| TDM     | 218       | 3.21%   |
| LXDM    | 10        | 0.15%   |
| GREETD  | 7         | 0.1%    |
| SLiM    | 3         | 0.04%   |
| XDM     | 2         | 0.03%   |
| Ly      | 2         | 0.03%   |
| LYNDE   | 1         | 0.01%   |
| CDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2775      | 41.39%  |
| de_DE   | 529       | 7.89%   |
| ru_RU   | 470       | 7.01%   |
| en_GB   | 452       | 6.74%   |
| Unknown | 417       | 6.22%   |
| pt_BR   | 278       | 4.15%   |
| fr_FR   | 180       | 2.68%   |
| en_CA   | 146       | 2.18%   |
| it_IT   | 144       | 2.15%   |
| es_ES   | 142       | 2.12%   |
| pl_PL   | 122       | 1.82%   |
| en_AU   | 88        | 1.31%   |
| en_IN   | 80        | 1.19%   |
| es_MX   | 58        | 0.87%   |
| zh_CN   | 51        | 0.76%   |
| de_AT   | 46        | 0.69%   |
| nl_NL   | 41        | 0.61%   |
| ru_UA   | 39        | 0.58%   |
| es_AR   | 33        | 0.49%   |
| en_IE   | 29        | 0.43%   |
| sv_SE   | 27        | 0.4%    |
| fi_FI   | 24        | 0.36%   |
| es_CL   | 23        | 0.34%   |
| cs_CZ   | 23        | 0.34%   |
| hu_HU   | 22        | 0.33%   |
| C       | 22        | 0.33%   |
| pt_PT   | 21        | 0.31%   |
| de_CH   | 21        | 0.31%   |
| tr_TR   | 20        | 0.3%    |
| en_ZA   | 19        | 0.28%   |
| en_NZ   | 19        | 0.28%   |
| en_DK   | 19        | 0.28%   |
| uk_UA   | 17        | 0.25%   |
| es_CO   | 17        | 0.25%   |
| fr_CA   | 16        | 0.24%   |
| en_PH   | 16        | 0.24%   |
| nl_BE   | 12        | 0.18%   |
| en_IL   | 12        | 0.18%   |
| da_DK   | 12        | 0.18%   |
| en_DE   | 11        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3718      | 55.25%  |
| EFI  | 3012      | 44.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 5588      | 83.54%  |
| Btrfs    | 659       | 9.85%   |
| Overlay  | 138       | 2.06%   |
| Unknown  | 129       | 1.93%   |
| Xfs      | 80        | 1.2%    |
| Tmpfs    | 49        | 0.73%   |
| F2fs     | 26        | 0.39%   |
| Ext3     | 5         | 0.07%   |
| Ext2     | 5         | 0.07%   |
| Zfs      | 4         | 0.06%   |
| Reiserfs | 3         | 0.04%   |
| XXXX     | 1         | 0.01%   |
| XXXfs    | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3134      | 46.43%  |
| Unknown | 3024      | 44.8%   |
| MBR     | 592       | 8.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5869      | 87.43%  |
| Yes       | 844       | 12.57%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4560      | 67.82%  |
| Yes       | 2164      | 32.18%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 1218      | 18.43%  |
| Lenovo              | 1059      | 16.02%  |
| Hewlett-Packard     | 854       | 12.92%  |
| Dell                | 712       | 10.77%  |
| Gigabyte Technology | 531       | 8.03%   |
| MSI                 | 514       | 7.78%   |
| Acer                | 332       | 5.02%   |
| ASRock              | 279       | 4.22%   |
| Apple               | 134       | 2.03%   |
| Intel               | 94        | 1.42%   |
| Samsung Electronics | 66        | 1%      |
| Toshiba             | 65        | 0.98%   |
| HUAWEI              | 63        | 0.95%   |
| Unknown             | 45        | 0.68%   |
| Timi                | 38        | 0.57%   |
| Fujitsu             | 36        | 0.54%   |
| Sony                | 32        | 0.48%   |
| Notebook            | 29        | 0.44%   |
| Google              | 29        | 0.44%   |
| Microsoft           | 20        | 0.3%    |
| Biostar             | 20        | 0.3%    |
| TUXEDO              | 18        | 0.27%   |
| Pegatron            | 18        | 0.27%   |
| Medion              | 18        | 0.27%   |
| Alienware           | 17        | 0.26%   |
| AZW                 | 16        | 0.24%   |
| Razer               | 15        | 0.23%   |
| Positivo            | 15        | 0.23%   |
| Huanan              | 13        | 0.2%    |
| Schenker            | 12        | 0.18%   |
| LG Electronics      | 11        | 0.17%   |
| Foxconn             | 11        | 0.17%   |
| Packard Bell        | 10        | 0.15%   |
| HONOR               | 10        | 0.15%   |
| System76            | 9         | 0.14%   |
| BESSTAR Tech        | 9         | 0.14%   |
| ZOTAC               | 7         | 0.11%   |
| TrekStor            | 7         | 0.11%   |
| Panasonic           | 7         | 0.11%   |
| ECS                 | 7         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| ASUS All Series                     | 71        | 1.07%   |
| Unknown                             | 57        | 0.86%   |
| MSI MS-7C37                         | 28        | 0.42%   |
| Gigabyte B450M DS3H                 | 27        | 0.41%   |
| MSI MS-7C02                         | 26        | 0.39%   |
| HP Notebook                         | 22        | 0.33%   |
| ASUS TUF Gaming X570-PLUS           | 22        | 0.33%   |
| ASUS PRIME A320M-K                  | 19        | 0.29%   |
| MSI MS-7C91                         | 17        | 0.26%   |
| MSI MS-7B86                         | 17        | 0.26%   |
| ASRock B450M Pro4                   | 16        | 0.24%   |
| MSI MS-7B79                         | 15        | 0.23%   |
| Lenovo IdeaPad 5 15ARE05 81YQ       | 14        | 0.21%   |
| ASUS ROG STRIX B450-F GAMING        | 14        | 0.21%   |
| Lenovo Legion 5 15ARH05 82B5        | 13        | 0.2%    |
| Gigabyte X570 AORUS ELITE           | 13        | 0.2%    |
| Dell XPS 15 9500                    | 13        | 0.2%    |
| Dell XPS 13 9310                    | 13        | 0.2%    |
| MSI MS-7A38                         | 12        | 0.18%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2   | 12        | 0.18%   |
| HP Pavilion Notebook                | 12        | 0.18%   |
| Dell OptiPlex 9020                  | 12        | 0.18%   |
| ASUS TUF Gaming B550M-PLUS          | 12        | 0.18%   |
| ASUS ROG STRIX B550-F GAMING        | 12        | 0.18%   |
| ASUS PRIME B450M-A                  | 12        | 0.18%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 11        | 0.17%   |
| Gigabyte B450 AORUS M               | 11        | 0.17%   |
| Gigabyte 970A-DS3P                  | 11        | 0.17%   |
| Dell OptiPlex 7010                  | 11        | 0.17%   |
| ASUS PRIME B350-PLUS                | 11        | 0.17%   |
| MSI MS-7B89                         | 10        | 0.15%   |
| HP Pavilion dv7                     | 10        | 0.15%   |
| HP Laptop 15-bs0xx                  | 10        | 0.15%   |
| Gigabyte X570 AORUS MASTER          | 10        | 0.15%   |
| Gigabyte X470 AORUS ULTRA GAMING    | 10        | 0.15%   |
| Dell Inspiron 3542                  | 10        | 0.15%   |
| ASUS ROG STRIX X570-E GAMING        | 10        | 0.15%   |
| MSI MS-7817                         | 9         | 0.14%   |
| MSI MS-7693                         | 9         | 0.14%   |
| HP Pavilion g6                      | 9         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 443       | 6.7%    |
| Lenovo IdeaPad     | 254       | 3.84%   |
| ASUS ROG           | 206       | 3.12%   |
| Acer Aspire        | 206       | 3.12%   |
| Dell Inspiron      | 201       | 3.04%   |
| HP Pavilion        | 169       | 2.56%   |
| ASUS PRIME         | 160       | 2.42%   |
| Dell Latitude      | 146       | 2.21%   |
| Dell XPS           | 118       | 1.79%   |
| ASUS TUF           | 113       | 1.71%   |
| HP Laptop          | 101       | 1.53%   |
| HP ProBook         | 99        | 1.5%    |
| HP EliteBook       | 96        | 1.45%   |
| Dell OptiPlex      | 85        | 1.29%   |
| ASUS VivoBook      | 79        | 1.2%    |
| HP ENVY            | 72        | 1.09%   |
| Lenovo Legion      | 71        | 1.07%   |
| ASUS All           | 71        | 1.07%   |
| Dell Precision     | 68        | 1.03%   |
| Unknown            | 57        | 0.86%   |
| Toshiba Satellite  | 56        | 0.85%   |
| Lenovo Yoga        | 52        | 0.79%   |
| HP Compaq          | 52        | 0.79%   |
| Gigabyte X570      | 47        | 0.71%   |
| Gigabyte B450M     | 44        | 0.67%   |
| Dell Vostro        | 44        | 0.67%   |
| Acer Swift         | 38        | 0.57%   |
| ASUS ZenBook       | 37        | 0.56%   |
| Gigabyte B450      | 34        | 0.51%   |
| HP OMEN            | 33        | 0.5%    |
| Acer Nitro         | 31        | 0.47%   |
| MSI MS-7C37        | 28        | 0.42%   |
| MSI MS-7C02        | 26        | 0.39%   |
| Lenovo ThinkBook   | 26        | 0.39%   |
| ASUS ASUS          | 26        | 0.39%   |
| ASRock B450M       | 26        | 0.39%   |
| Lenovo ThinkCentre | 25        | 0.38%   |
| Fujitsu LIFEBOOK   | 25        | 0.38%   |
| Lenovo IdeaPadFlex | 22        | 0.33%   |
| HP Notebook        | 22        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 891       | 13.48%  |
| 2018    | 839       | 12.69%  |
| 2020    | 829       | 12.54%  |
| 2017    | 558       | 8.44%   |
| 2021    | 488       | 7.38%   |
| 2012    | 481       | 7.28%   |
| 2013    | 390       | 5.9%    |
| 2014    | 363       | 5.49%   |
| 2011    | 344       | 5.2%    |
| 2015    | 341       | 5.16%   |
| 2016    | 335       | 5.07%   |
| 2010    | 203       | 3.07%   |
| 2022    | 176       | 2.66%   |
| 2009    | 135       | 2.04%   |
| 2008    | 122       | 1.85%   |
| 2007    | 72        | 1.09%   |
| 2006    | 20        | 0.3%    |
| 2023    | 13        | 0.2%    |
| 2005    | 5         | 0.08%   |
| Unknown | 5         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 3653      | 55.26%  |
| Desktop     | 2538      | 38.4%   |
| Convertible | 238       | 3.6%    |
| Mini pc     | 79        | 1.2%    |
| All in one  | 50        | 0.76%   |
| Tablet      | 43        | 0.65%   |
| Server      | 8         | 0.12%   |
| Phone       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6606      | 99.89%  |
| Enabled  | 7         | 0.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6563      | 99.29%  |
| Yes  | 47        | 0.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1812      | 27.04%  |
| 4.01-8.0        | 1476      | 22.02%  |
| 8.01-16.0       | 1327      | 19.8%   |
| 32.01-64.0      | 852       | 12.71%  |
| 3.01-4.0        | 757       | 11.3%   |
| 64.01-256.0     | 181       | 2.7%    |
| 24.01-32.0      | 154       | 2.3%    |
| 1.01-2.0        | 106       | 1.58%   |
| 2.01-3.0        | 34        | 0.51%   |
| More than 256.0 | 2         | 0.03%   |
| 0.51-1.0        | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 2.01-3.0        | 1904      | 25.8%   |
| 1.01-2.0        | 1764      | 23.91%  |
| 4.01-8.0        | 1637      | 22.18%  |
| 3.01-4.0        | 1250      | 16.94%  |
| 8.01-16.0       | 494       | 6.69%   |
| 0.51-1.0        | 214       | 2.9%    |
| 16.01-24.0      | 62        | 0.84%   |
| 24.01-32.0      | 21        | 0.28%   |
| 0.01-0.5        | 20        | 0.27%   |
| 32.01-64.0      | 11        | 0.15%   |
| More than 256.0 | 1         | 0.01%   |
| 64.01-256.0     | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3449      | 50.59%  |
| 2      | 1947      | 28.56%  |
| 3      | 685       | 10.05%  |
| 4      | 361       | 5.29%   |
| 5      | 199       | 2.92%   |
| 6      | 74        | 1.09%   |
| 7      | 38        | 0.56%   |
| 0      | 31        | 0.45%   |
| 8      | 15        | 0.22%   |
| 9      | 9         | 0.13%   |
| 11     | 4         | 0.06%   |
| 10     | 3         | 0.04%   |
| 12     | 2         | 0.03%   |
| 20     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4826      | 72.39%  |
| Yes       | 1841      | 27.61%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5523      | 83.38%  |
| No        | 1101      | 16.62%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5208      | 78.3%   |
| No        | 1443      | 21.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4422      | 66.18%  |
| No        | 2260      | 33.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1115      | 16.75%  |
| Germany      | 778       | 11.69%  |
| Russia       | 592       | 8.89%   |
| Brazil       | 392       | 5.89%   |
| France       | 247       | 3.71%   |
| UK           | 236       | 3.55%   |
| Italy        | 218       | 3.28%   |
| Canada       | 214       | 3.22%   |
| Spain        | 195       | 2.93%   |
| Poland       | 194       | 2.91%   |
| Netherlands  | 154       | 2.31%   |
| Ukraine      | 146       | 2.19%   |
| India        | 127       | 1.91%   |
| Australia    | 98        | 1.47%   |
| Austria      | 95        | 1.43%   |
| Mexico       | 93        | 1.4%    |
| Sweden       | 90        | 1.35%   |
| China        | 70        | 1.05%   |
| Switzerland  | 65        | 0.98%   |
| Belgium      | 62        | 0.93%   |
| Turkey       | 61        | 0.92%   |
| Finland      | 61        | 0.92%   |
| Romania      | 59        | 0.89%   |
| Czechia      | 53        | 0.8%    |
| Portugal     | 51        | 0.77%   |
| Argentina    | 51        | 0.77%   |
| Hungary      | 50        | 0.75%   |
| Indonesia    | 47        | 0.71%   |
| Greece       | 46        | 0.69%   |
| Bulgaria     | 46        | 0.69%   |
| Norway       | 45        | 0.68%   |
| Belarus      | 42        | 0.63%   |
| Denmark      | 39        | 0.59%   |
| Colombia     | 31        | 0.47%   |
| Chile        | 31        | 0.47%   |
| Taiwan       | 28        | 0.42%   |
| Bangladesh   | 28        | 0.42%   |
| South Africa | 27        | 0.41%   |
| Israel       | 25        | 0.38%   |
| Ireland      | 25        | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 136       | 1.94%   |
| St Petersburg     | 78        | 1.11%   |
| Vienna            | 57        | 0.81%   |
| Berlin            | 55        | 0.78%   |
| Paris             | 47        | 0.67%   |
| Sao Paulo         | 44        | 0.63%   |
| Warsaw            | 43        | 0.61%   |
| Kyiv              | 42        | 0.6%    |
| Amsterdam         | 40        | 0.57%   |
| Milan             | 33        | 0.47%   |
| Frankfurt am Main | 33        | 0.47%   |
| Toronto           | 32        | 0.46%   |
| Madrid            | 31        | 0.44%   |
| Hamburg           | 30        | 0.43%   |
| Rome              | 28        | 0.4%    |
| Munich            | 28        | 0.4%    |
| Helsinki          | 28        | 0.4%    |
| Stockholm         | 26        | 0.37%   |
| Minsk             | 25        | 0.36%   |
| Melbourne         | 25        | 0.36%   |
| Istanbul          | 25        | 0.36%   |
| Athens            | 25        | 0.36%   |
| Barcelona         | 24        | 0.34%   |
| Bucharest         | 23        | 0.33%   |
| Bengaluru         | 23        | 0.33%   |
| Sydney            | 22        | 0.31%   |
| Novosibirsk       | 22        | 0.31%   |
| London            | 22        | 0.31%   |
| Sofia             | 21        | 0.3%    |
| Mexico City       | 21        | 0.3%    |
| Krakow            | 21        | 0.3%    |
| Cologne           | 21        | 0.3%    |
| Rio de Janeiro    | 20        | 0.28%   |
| Prague            | 20        | 0.28%   |
| Yekaterinburg     | 19        | 0.27%   |
| Dhaka             | 19        | 0.27%   |
| Budapest          | 19        | 0.27%   |
| Montreal          | 18        | 0.26%   |
| Los Angeles       | 18        | 0.26%   |
| Stuttgart         | 17        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1885      | 2898   | 17.29%  |
| WDC                         | 1542      | 2344   | 14.14%  |
| Seagate                     | 1482      | 2227   | 13.59%  |
| Toshiba                     | 696       | 855    | 6.38%   |
| SanDisk                     | 649       | 844    | 5.95%   |
| Kingston                    | 627       | 822    | 5.75%   |
| Crucial                     | 465       | 657    | 4.27%   |
| Unknown                     | 332       | 441    | 3.05%   |
| Intel                       | 309       | 408    | 2.83%   |
| SK hynix                    | 306       | 372    | 2.81%   |
| Hitachi                     | 226       | 302    | 2.07%   |
| HGST                        | 211       | 274    | 1.94%   |
| Micron Technology           | 169       | 211    | 1.55%   |
| A-DATA Technology           | 148       | 197    | 1.36%   |
| Phison                      | 130       | 179    | 1.19%   |
| China                       | 102       | 133    | 0.94%   |
| Apple                       | 79        | 98     | 0.72%   |
| KIOXIA                      | 78        | 92     | 0.72%   |
| Silicon Motion              | 76        | 103    | 0.7%    |
| Micron/Crucial Technology   | 70        | 86     | 0.64%   |
| Transcend                   | 57        | 63     | 0.52%   |
| Phison Electronics          | 57        | 62     | 0.52%   |
| PNY                         | 53        | 79     | 0.49%   |
| SPCC                        | 51        | 60     | 0.47%   |
| Intenso                     | 48        | 65     | 0.44%   |
| Patriot                     | 47        | 56     | 0.43%   |
| OCZ                         | 47        | 65     | 0.43%   |
| GOODRAM                     | 45        | 69     | 0.41%   |
| XPG                         | 43        | 54     | 0.39%   |
| JMicron Technology          | 42        | 50     | 0.39%   |
| Plextor                     | 36        | 48     | 0.33%   |
| Corsair                     | 35        | 46     | 0.32%   |
| LITEONIT                    | 33        | 42     | 0.3%    |
| LITEON                      | 32        | 35     | 0.29%   |
| Realtek Semiconductor       | 30        | 37     | 0.28%   |
| Kingston Technology Company | 29        | 30     | 0.27%   |
| Team                        | 23        | 30     | 0.21%   |
| Lexar                       | 23        | 25     | 0.21%   |
| Hewlett-Packard             | 21        | 29     | 0.19%   |
| Apacer                      | 21        | 23     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 130       | 1.06%   |
| Samsung SSD 860 EVO 500GB                           | 110       | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB                      | 107       | 0.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 103       | 0.84%   |
| Samsung SSD 850 EVO 500GB                           | 87        | 0.71%   |
| Samsung NVMe SSD Drive 512GB                        | 86        | 0.7%    |
| Samsung NVMe SSD Drive 500GB                        | 83        | 0.68%   |
| Samsung NVMe SSD Drive 1TB                          | 82        | 0.67%   |
| Samsung SSD 850 EVO 250GB                           | 80        | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB                      | 79        | 0.65%   |
| Crucial CT500MX500SSD1 500GB                        | 79        | 0.65%   |
| Kingston SA400S37120G 120GB SSD                     | 78        | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB                      | 74        | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 69        | 0.56%   |
| Samsung SSD 860 EVO 1TB                             | 66        | 0.54%   |
| Crucial CT1000MX500SSD1 1TB                         | 66        | 0.54%   |
| Kingston SA400S37480G 480GB SSD                     | 64        | 0.52%   |
| HGST HTS721010A9E630 1TB                            | 64        | 0.52%   |
| Toshiba MQ01ABD100 1TB                              | 62        | 0.51%   |
| Samsung NVMe SSD Drive 256GB                        | 61        | 0.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 61        | 0.5%    |
| Toshiba MQ04ABF100 1TB                              | 58        | 0.47%   |
| Samsung SSD 860 EVO 250GB                           | 58        | 0.47%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 57        | 0.47%   |
| Toshiba DT01ACA100 1TB                              | 57        | 0.47%   |
| SK hynix NVMe SSD Drive 512GB                       | 55        | 0.45%   |
| Seagate Expansion 1TB                               | 54        | 0.44%   |
| Crucial CT240BX500SSD1 240GB                        | 53        | 0.43%   |
| SanDisk NVMe SSD Drive 512GB                        | 52        | 0.43%   |
| Unknown SD/MMC/MS PRO 64GB                          | 47        | 0.38%   |
| Unknown MMC Card  64GB                              | 47        | 0.38%   |
| Toshiba MQ01ABF050 500GB                            | 46        | 0.38%   |
| Seagate ST500DM002-1BD142 500GB                     | 45        | 0.37%   |
| SanDisk NVMe SSD Drive 500GB                        | 45        | 0.37%   |
| Intel NVMe SSD Drive 512GB                          | 44        | 0.36%   |
| Seagate ST1000DM003-1ER162 1TB                      | 42        | 0.34%   |
| SanDisk NVMe SSD Drive 1TB                          | 42        | 0.34%   |
| Seagate ST2000DM006-2DM164 2TB                      | 41        | 0.34%   |
| Kingston SV300S37A120G 120GB SSD                    | 39        | 0.32%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 38        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1446      | 2159   | 36.71%  |
| WDC                 | 1229      | 1857   | 31.2%   |
| Toshiba             | 508       | 623    | 12.9%   |
| Hitachi             | 226       | 302    | 5.74%   |
| HGST                | 210       | 273    | 5.33%   |
| Samsung Electronics | 154       | 233    | 3.91%   |
| Unknown             | 53        | 65     | 1.35%   |
| Fujitsu             | 18        | 19     | 0.46%   |
| Apple               | 17        | 22     | 0.43%   |
| Maxtor              | 13        | 15     | 0.33%   |
| USB3.0              | 8         | 8      | 0.2%    |
| Intenso             | 8         | 12     | 0.2%    |
| ASMT                | 7         | 13     | 0.18%   |
| External            | 6         | 8      | 0.15%   |
| ASMedia             | 5         | 7      | 0.13%   |
| JMicron Technology  | 4         | 8      | 0.1%    |
| Hewlett-Packard     | 4         | 4      | 0.1%    |
| HGST HTS            | 3         | 3      | 0.08%   |
| USB                 | 2         | 2      | 0.05%   |
| SSK                 | 2         | 3      | 0.05%   |
| Maxone              | 2         | 2      | 0.05%   |
| Apricorn            | 2         | 2      | 0.05%   |
| SABRENT             | 1         | 1      | 0.03%   |
| QNAP                | 1         | 1      | 0.03%   |
| Pioneer             | 1         | 3      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| MARSHAL             | 1         | 1      | 0.03%   |
| Lenovo              | 1         | 1      | 0.03%   |
| KESU                | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| IBM/Hitachi         | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 923       | 1303   | 24.83%  |
| Kingston            | 504       | 652    | 13.56%  |
| Crucial             | 424       | 607    | 11.4%   |
| SanDisk             | 311       | 405    | 8.36%   |
| WDC                 | 226       | 299    | 6.08%   |
| A-DATA Technology   | 119       | 158    | 3.2%    |
| China               | 101       | 132    | 2.72%   |
| Intel               | 95        | 120    | 2.56%   |
| Micron Technology   | 70        | 88     | 1.88%   |
| SK hynix            | 59        | 69     | 1.59%   |
| Toshiba             | 54        | 69     | 1.45%   |
| Transcend           | 50        | 55     | 1.34%   |
| PNY                 | 47        | 73     | 1.26%   |
| OCZ                 | 47        | 65     | 1.26%   |
| Apple               | 45        | 51     | 1.21%   |
| Patriot             | 44        | 53     | 1.18%   |
| GOODRAM             | 43        | 67     | 1.16%   |
| SPCC                | 40        | 48     | 1.08%   |
| Plextor             | 33        | 45     | 0.89%   |
| LITEONIT            | 33        | 42     | 0.89%   |
| Intenso             | 32        | 43     | 0.86%   |
| LITEON              | 26        | 29     | 0.7%    |
| Corsair             | 24        | 33     | 0.65%   |
| Lexar               | 22        | 24     | 0.59%   |
| Apacer              | 20        | 22     | 0.54%   |
| Team                | 19        | 26     | 0.51%   |
| JMicron Technology  | 18        | 19     | 0.48%   |
| Seagate             | 17        | 24     | 0.46%   |
| KingSpec            | 16        | 18     | 0.43%   |
| SABRENT             | 13        | 13     | 0.35%   |
| Netac               | 13        | 20     | 0.35%   |
| Gigabyte Technology | 13        | 18     | 0.35%   |
| Leven               | 11        | 12     | 0.3%    |
| KingDian            | 11        | 11     | 0.3%    |
| TO Exter            | 9         | 11     | 0.24%   |
| Hewlett-Packard     | 9         | 13     | 0.24%   |
| ASMT                | 8         | 12     | 0.22%   |
| Unknown             | 8         | 11     | 0.22%   |
| Mushkin             | 7         | 8      | 0.19%   |
| NGFF                | 6         | 6      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3202      | 5654   | 33.52%  |
| SSD     | 3139      | 4967   | 32.86%  |
| NVMe    | 2795      | 4026   | 29.26%  |
| MMC     | 256       | 330    | 2.68%   |
| Unknown | 161       | 211    | 1.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4783      | 10171  | 57.68%  |
| NVMe | 2794      | 4013   | 33.7%   |
| SAS  | 459       | 674    | 5.54%   |
| MMC  | 256       | 330    | 3.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3475      | 5694   | 51.34%  |
| 0.51-1.0   | 2191      | 3223   | 32.37%  |
| 1.01-2.0   | 625       | 916    | 9.23%   |
| 3.01-4.0   | 195       | 319    | 2.88%   |
| 2.01-3.0   | 131       | 201    | 1.94%   |
| 4.01-10.0  | 124       | 225    | 1.83%   |
| 10.01-20.0 | 28        | 43     | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1596      | 23.01%  |
| 251-500        | 1547      | 22.3%   |
| 501-1000       | 1106      | 15.94%  |
| 1001-2000      | 786       | 11.33%  |
| More than 3000 | 468       | 6.75%   |
| Unknown        | 402       | 5.8%    |
| 51-100         | 364       | 5.25%   |
| 2001-3000      | 307       | 4.43%   |
| 1-20           | 196       | 2.83%   |
| 21-50          | 165       | 2.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1431      | 19.74%  |
| 21-50          | 1179      | 16.26%  |
| 101-250        | 1179      | 16.26%  |
| 51-100         | 984       | 13.57%  |
| 251-500        | 790       | 10.9%   |
| 501-1000       | 614       | 8.47%   |
| Unknown        | 402       | 5.55%   |
| 1001-2000      | 359       | 4.95%   |
| More than 3000 | 177       | 2.44%   |
| 2001-3000      | 129       | 1.78%   |
| 0              | 5         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 11        | 12     | 1.98%   |
| HGST HTS545050A7E680 500GB                          | 10        | 10     | 1.8%    |
| HGST HTS721010A9E630 1TB                            | 9         | 9      | 1.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 8         | 8      | 1.44%   |
| Seagate ST500DM002-1BD142 500GB                     | 7         | 9      | 1.26%   |
| HGST HTS545050A7E380 500GB                          | 7         | 7      | 1.26%   |
| Toshiba MQ01ABD100 1TB                              | 6         | 8      | 1.08%   |
| Toshiba MQ01ABD050 500GB                            | 6         | 6      | 1.08%   |
| Seagate ST500LT012-9WS142 500GB                     | 6         | 23     | 1.08%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 6         | 6      | 1.08%   |
| WDC WD5000AAKX-001CA0 500GB                         | 5         | 7      | 0.9%    |
| WDC WD10EARS-00Y5B1 1TB                             | 5         | 5      | 0.9%    |
| Seagate ST9320325AS 320GB                           | 5         | 6      | 0.9%    |
| Samsung Electronics HD103SJ 1TB                     | 5         | 5      | 0.9%    |
| Hitachi HDS721010CLA332 1TB                         | 5         | 5      | 0.9%    |
| Crucial CT525MX300SSD1 528GB                        | 5         | 5      | 0.9%    |
| WDC WD1002FAEX-00Z3A0 1TB                           | 4         | 4      | 0.72%   |
| Toshiba MQ01ABF050 500GB                            | 4         | 4      | 0.72%   |
| Seagate ST9500325AS 500GB                           | 4         | 5      | 0.72%   |
| Seagate ST3500413AS 500GB                           | 4         | 5      | 0.72%   |
| Seagate ST1000DX001-1CM162 1TB                      | 4         | 6      | 0.72%   |
| Samsung Electronics SSD 960 EVO 250GB               | 4         | 5      | 0.72%   |
| Samsung Electronics HD103UJ 1TB                     | 4         | 6      | 0.72%   |
| Hitachi HTS723232A7A364 320GB                       | 4         | 4      | 0.72%   |
| HGST HTS725050A7E630 500GB                          | 4         | 4      | 0.72%   |
| HGST HTS541010A9E680 1TB                            | 4         | 4      | 0.72%   |
| WDC WD15EARS-00MVWB0 1TB                            | 3         | 3      | 0.54%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 4      | 0.54%   |
| WDC WD10EZEX-00RKKA0 1TB                            | 3         | 3      | 0.54%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 3         | 3      | 0.54%   |
| WDC WD10EARX-00N0YB0 1TB                            | 3         | 4      | 0.54%   |
| Seagate ST9750420AS 752GB                           | 3         | 3      | 0.54%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 4      | 0.54%   |
| Seagate ST4000DM000-1F2168 4TB                      | 3         | 10     | 0.54%   |
| Seagate ST31000524AS 1TB                            | 3         | 5      | 0.54%   |
| Seagate ST2000DM001-1CH164 2TB                      | 3         | 3      | 0.54%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 3         | 3      | 0.54%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 3         | 3      | 0.54%   |
| Kingston SV300S37A120G 120GB SSD                    | 3         | 3      | 0.54%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 3      | 0.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 144       | 211    | 26.62%  |
| WDC                 | 125       | 145    | 23.11%  |
| Samsung Electronics | 42        | 49     | 7.76%   |
| HGST                | 41        | 41     | 7.58%   |
| Hitachi             | 38        | 41     | 7.02%   |
| Toshiba             | 35        | 42     | 6.47%   |
| Crucial             | 16        | 19     | 2.96%   |
| SanDisk             | 15        | 18     | 2.77%   |
| Kingston            | 15        | 15     | 2.77%   |
| Intel               | 15        | 17     | 2.77%   |
| SK hynix            | 9         | 14     | 1.66%   |
| A-DATA Technology   | 8         | 9      | 1.48%   |
| Micron Technology   | 6         | 8      | 1.11%   |
| LITEON              | 3         | 3      | 0.55%   |
| Transcend           | 2         | 2      | 0.37%   |
| OCZ                 | 2         | 2      | 0.37%   |
| KingSpec            | 2         | 3      | 0.37%   |
| Corsair             | 2         | 6      | 0.37%   |
| ASMT                | 2         | 6      | 0.37%   |
| Apacer              | 2         | 2      | 0.37%   |
| TwinMOS             | 1         | 1      | 0.18%   |
| SPCC                | 1         | 1      | 0.18%   |
| Realtek             | 1         | 1      | 0.18%   |
| Phison              | 1         | 2      | 0.18%   |
| Patriot             | 1         | 1      | 0.18%   |
| Maxtor              | 1         | 1      | 0.18%   |
| MaxDigital          | 1         | 1      | 0.18%   |
| MARSHAL             | 1         | 1      | 0.18%   |
| LITEONIT            | 1         | 1      | 0.18%   |
| Intenso             | 1         | 4      | 0.18%   |
| IM3D                | 1         | 1      | 0.18%   |
| Hewlett-Packard     | 1         | 1      | 0.18%   |
| Fujitsu             | 1         | 1      | 0.18%   |
| Faspeed             | 1         | 1      | 0.18%   |
| Drevo               | 1         | 1      | 0.18%   |
| Apple               | 1         | 1      | 0.18%   |
| Unknown             | 1         | 1      | 0.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 143       | 208    | 35.84%  |
| WDC                 | 122       | 142    | 30.58%  |
| HGST                | 41        | 41     | 10.28%  |
| Hitachi             | 38        | 41     | 9.52%   |
| Toshiba             | 31        | 38     | 7.77%   |
| Samsung Electronics | 20        | 25     | 5.01%   |
| Maxtor              | 1         | 1      | 0.25%   |
| MaxDigital          | 1         | 1      | 0.25%   |
| MARSHAL             | 1         | 1      | 0.25%   |
| Fujitsu             | 1         | 1      | 0.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 379       | 499    | 73.17%  |
| SSD  | 116       | 149    | 22.39%  |
| NVMe | 23        | 26     | 4.44%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WDS256G1X0C-00ENX0 256GB                     | 1         | 1      | 6.67%   |
| WDC WD3200BPVT-24ZEST0 320GB                     | 1         | 1      | 6.67%   |
| WDC WD1600BEKT-75PVMT0 160GB                     | 1         | 1      | 6.67%   |
| WDC WD1600AAJS-65WAA0 160GB                      | 1         | 1      | 6.67%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 6.67%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 6.67%   |
| Toshiba MK1059GSM 1TB                            | 1         | 1      | 6.67%   |
| Seagate ST9640320AS 640GB                        | 1         | 1      | 6.67%   |
| Seagate ST3500418AS 500GB                        | 1         | 1      | 6.67%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 6.67%   |
| Seagate ST31000524AS 1TB                         | 1         | 2      | 6.67%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 6.67%   |
| Samsung Electronics HD321HJ 320GB                | 1         | 1      | 6.67%   |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 6.67%   |
| Hitachi HDS721010CLA332 1TB                      | 1         | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 33.33%  |
| Seagate             | 4         | 5      | 26.67%  |
| Toshiba             | 2         | 2      | 13.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |
| Kingston            | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4251      | 9389   | 58%     |
| Works    | 2564      | 5109   | 34.98%  |
| Malfunc  | 499       | 674    | 6.81%   |
| Failed   | 15        | 16     | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3937      | 43.78%  |
| AMD                              | 1764      | 19.62%  |
| Samsung Electronics              | 1032      | 11.48%  |
| SanDisk                          | 474       | 5.27%   |
| SK hynix                         | 244       | 2.71%   |
| Phison Electronics               | 204       | 2.27%   |
| ASMedia Technology               | 165       | 1.83%   |
| Kingston Technology Company      | 155       | 1.72%   |
| Toshiba America Info Systems     | 128       | 1.42%   |
| Micron/Crucial Technology        | 112       | 1.25%   |
| Micron Technology                | 98        | 1.09%   |
| Silicon Motion                   | 93        | 1.03%   |
| KIOXIA                           | 90        | 1%      |
| Marvell Technology Group         | 78        | 0.87%   |
| ADATA Technology                 | 74        | 0.82%   |
| JMicron Technology               | 63        | 0.7%    |
| Nvidia                           | 61        | 0.68%   |
| Realtek Semiconductor            | 44        | 0.49%   |
| Union Memory (Shenzhen)          | 30        | 0.33%   |
| Solid State Storage Technology   | 19        | 0.21%   |
| Lite-On Technology               | 17        | 0.19%   |
| Apple                            | 17        | 0.19%   |
| Seagate Technology               | 14        | 0.16%   |
| Shenzhen Longsys Electronics     | 11        | 0.12%   |
| LSI Logic / Symbios Logic        | 9         | 0.1%    |
| VIA Technologies                 | 8         | 0.09%   |
| Silicon Image                    | 6         | 0.07%   |
| Lenovo                           | 6         | 0.07%   |
| Broadcom / LSI                   | 6         | 0.07%   |
| Biwin Storage Technology         | 5         | 0.06%   |
| Yangtze Memory Technologies      | 4         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.04%   |
| Adaptec                          | 4         | 0.04%   |
| Transcend                        | 3         | 0.03%   |
| Integrated Technology Express    | 3         | 0.03%   |
| Silicon Integrated Systems [SiS] | 2         | 0.02%   |
| INNOGRIT                         | 2         | 0.02%   |
| Promise Technology               | 1         | 0.01%   |
| PMC-Sierra                       | 1         | 0.01%   |
| OCZ Technology Group             | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1330      | 13.05%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 571       | 5.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 371       | 3.64%   |
| AMD 400 Series Chipset SATA Controller                                         | 347       | 3.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 277       | 2.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 262       | 2.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 237       | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 167       | 1.64%   |
| Samsung NVMe SSD Controller 980                                                | 164       | 1.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 163       | 1.6%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 162       | 1.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 156       | 1.53%   |
| AMD 500 Series Chipset SATA Controller                                         | 156       | 1.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 144       | 1.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 139       | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 139       | 1.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 134       | 1.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 129       | 1.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 129       | 1.27%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 125       | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 120       | 1.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 116       | 1.14%   |
| Intel SSD 660P Series                                                          | 115       | 1.13%   |
| Intel Volume Management Device NVMe RAID Controller                            | 113       | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 109       | 1.07%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 105       | 1.03%   |
| Micron NVMe Storage Controller                                                 | 97        | 0.95%   |
| Phison E12 NVMe Controller                                                     | 96        | 0.94%   |
| Intel SATA Controller [RAID mode]                                              | 94        | 0.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 91        | 0.89%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 88        | 0.86%   |
| AMD 300 Series Chipset SATA Controller                                         | 86        | 0.84%   |
| Intel Comet Lake SATA AHCI Controller                                          | 85        | 0.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 75        | 0.74%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 72        | 0.71%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 72        | 0.71%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 71        | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 68        | 0.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 61        | 0.6%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 60        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5025      | 56.85%  |
| NVMe | 2804      | 31.72%  |
| IDE  | 495       | 5.6%    |
| RAID | 492       | 5.57%   |
| SAS  | 20        | 0.23%   |
| SCSI | 3         | 0.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 4474      | 67.68%  |
| AMD    | 2136      | 32.31%  |
| ARM    | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 132       | 1.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 93        | 1.4%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 81        | 1.22%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 79        | 1.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 75        | 1.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 73        | 1.1%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 73        | 1.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 71        | 1.07%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 69        | 1.04%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 69        | 1.04%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 64        | 0.97%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 63        | 0.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 62        | 0.94%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 62        | 0.94%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 61        | 0.92%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 54        | 0.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 53        | 0.8%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 50        | 0.75%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 50        | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 47        | 0.71%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 47        | 0.71%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 45        | 0.68%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 44        | 0.66%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 44        | 0.66%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 43        | 0.65%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 41        | 0.62%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 40        | 0.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 40        | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 39        | 0.59%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 35        | 0.53%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 35        | 0.53%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 34        | 0.51%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 34        | 0.51%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 33        | 0.5%    |
| AMD Ryzen 5 1600 Six-Core Processor           | 33        | 0.5%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 32        | 0.48%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 32        | 0.48%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 29        | 0.44%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 29        | 0.44%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 29        | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1483      | 22.39%  |
| Intel Core i7           | 1398      | 21.11%  |
| AMD Ryzen 5             | 708       | 10.69%  |
| AMD Ryzen 7             | 577       | 8.71%   |
| Intel Core i3           | 402       | 6.07%   |
| Other                   | 355       | 5.36%   |
| Intel Celeron           | 211       | 3.19%   |
| AMD Ryzen 9             | 163       | 2.46%   |
| Intel Core 2 Duo        | 143       | 2.16%   |
| Intel Xeon              | 131       | 1.98%   |
| Intel Pentium           | 120       | 1.81%   |
| AMD FX                  | 114       | 1.72%   |
| AMD Ryzen 3             | 103       | 1.56%   |
| Intel Core i9           | 48        | 0.72%   |
| Intel Atom              | 47        | 0.71%   |
| AMD A10                 | 44        | 0.66%   |
| Intel Pentium Dual-Core | 42        | 0.63%   |
| AMD Ryzen 7 PRO         | 41        | 0.62%   |
| AMD A8                  | 40        | 0.6%    |
| AMD A4                  | 35        | 0.53%   |
| AMD Ryzen Threadripper  | 30        | 0.45%   |
| AMD A6                  | 30        | 0.45%   |
| AMD Phenom II X4        | 29        | 0.44%   |
| Intel Core 2 Quad       | 28        | 0.42%   |
| Intel Pentium Silver    | 23        | 0.35%   |
| Intel Core 2            | 23        | 0.35%   |
| AMD E1                  | 21        | 0.32%   |
| AMD Athlon II X2        | 21        | 0.32%   |
| AMD Athlon              | 21        | 0.32%   |
| AMD E                   | 19        | 0.29%   |
| AMD Ryzen 5 PRO         | 14        | 0.21%   |
| AMD Phenom II X6        | 12        | 0.18%   |
| AMD Athlon 64 X2        | 12        | 0.18%   |
| AMD E2                  | 10        | 0.15%   |
| Intel Pentium Gold      | 9         | 0.14%   |
| Intel Genuine           | 9         | 0.14%   |
| AMD Athlon X4           | 9         | 0.14%   |
| AMD Athlon II X4        | 9         | 0.14%   |
| Intel Pentium Dual      | 7         | 0.11%   |
| AMD Turion 64 X2 Mobile | 7         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2431      | 36.72%  |
| 2       | 2060      | 31.11%  |
| 6       | 1003      | 15.15%  |
| 8       | 746       | 11.27%  |
| 12      | 137       | 2.07%   |
| 16      | 74        | 1.12%   |
| 3       | 49        | 0.74%   |
| 1       | 45        | 0.68%   |
| 10      | 30        | 0.45%   |
| 14      | 29        | 0.44%   |
| 24      | 7         | 0.11%   |
| 32      | 5         | 0.08%   |
| Unknown | 3         | 0.05%   |
| 20      | 2         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 6586      | 99.64%  |
| 2      | 23        | 0.35%   |
| 4      | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5025      | 75.92%  |
| 1       | 1591      | 24.04%  |
| Unknown | 3         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6514      | 98.44%  |
| Unknown        | 102       | 1.54%   |
| 64-bit         | 1         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3345      | 48.9%   |
| 0x306a9    | 215       | 3.14%   |
| 0x906ea    | 182       | 2.66%   |
| 0x306c3    | 166       | 2.43%   |
| 0x206a7    | 146       | 2.13%   |
| 0x08701021 | 136       | 1.99%   |
| 0x806ea    | 130       | 1.9%    |
| 0x806ec    | 127       | 1.86%   |
| 0x806c1    | 108       | 1.58%   |
| 0x0800820d | 102       | 1.49%   |
| 0x806e9    | 96        | 1.4%    |
| 0x906e9    | 87        | 1.27%   |
| 0x406e3    | 84        | 1.23%   |
| 0x506e3    | 82        | 1.2%    |
| 0x08701013 | 78        | 1.14%   |
| 0x40651    | 76        | 1.11%   |
| 0x0a50000c | 72        | 1.05%   |
| 0x08108102 | 70        | 1.02%   |
| 0x08600106 | 69        | 1.01%   |
| 0x1067a    | 68        | 0.99%   |
| 0x08108109 | 66        | 0.96%   |
| 0x306d4    | 61        | 0.89%   |
| 0x706e5    | 49        | 0.72%   |
| 0x06000852 | 48        | 0.7%    |
| 0xa0652    | 47        | 0.69%   |
| 0x08600104 | 47        | 0.69%   |
| 0x08600103 | 46        | 0.67%   |
| 0x806eb    | 45        | 0.66%   |
| 0x08608103 | 40        | 0.58%   |
| 0x20655    | 33        | 0.48%   |
| 0x08001138 | 32        | 0.47%   |
| 0x010000c8 | 28        | 0.41%   |
| 0x906a3    | 26        | 0.38%   |
| 0x0810100b | 26        | 0.38%   |
| 0x906ed    | 24        | 0.35%   |
| 0x406c4    | 24        | 0.35%   |
| 0x0a201016 | 24        | 0.35%   |
| 0x306f2    | 23        | 0.34%   |
| 0x08600102 | 23        | 0.34%   |
| 0x06001119 | 23        | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1284      | 19.38%  |
| Zen 2            | 609       | 9.19%   |
| Haswell          | 573       | 8.65%   |
| IvyBridge        | 431       | 6.51%   |
| Zen+             | 426       | 6.43%   |
| SandyBridge      | 376       | 5.68%   |
| Skylake          | 350       | 5.28%   |
| Zen 3            | 288       | 4.35%   |
| Unknown          | 223       | 3.37%   |
| Zen              | 211       | 3.19%   |
| Penryn           | 192       | 2.9%    |
| TigerLake        | 188       | 2.84%   |
| Broadwell        | 168       | 2.54%   |
| CometLake        | 154       | 2.32%   |
| Piledriver       | 147       | 2.22%   |
| Westmere         | 128       | 1.93%   |
| Silvermont       | 117       | 1.77%   |
| IceLake          | 106       | 1.6%    |
| K10              | 94        | 1.42%   |
| Goldmont plus    | 80        | 1.21%   |
| Core             | 78        | 1.18%   |
| Excavator        | 67        | 1.01%   |
| Alderlake Hybrid | 50        | 0.75%   |
| Goldmont         | 46        | 0.69%   |
| Nehalem          | 44        | 0.66%   |
| Bobcat           | 32        | 0.48%   |
| Steamroller      | 31        | 0.47%   |
| Puma             | 25        | 0.38%   |
| Jaguar           | 24        | 0.36%   |
| K8 Hammer        | 23        | 0.35%   |
| Bulldozer        | 18        | 0.27%   |
| K10 Llano        | 14        | 0.21%   |
| Bonnell          | 13        | 0.2%    |
| NetBurst         | 6         | 0.09%   |
| K8 & K10 hybrid  | 5         | 0.08%   |
| Tremont          | 3         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 3415      | 42.12%  |
| Nvidia                     | 2620      | 32.31%  |
| AMD                        | 2064      | 25.46%  |
| ASPEED Technology          | 5         | 0.06%   |
| ATI Technologies           | 3         | 0.04%   |
| Matrox Electronics Systems | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 258       | 3.11%   |
| AMD Renoir                                                                               | 254       | 3.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 240       | 2.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 229       | 2.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 220       | 2.65%   |
| Intel UHD Graphics 620                                                                   | 209       | 2.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 207       | 2.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 173       | 2.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 169       | 2.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 166       | 2%      |
| Intel HD Graphics 620                                                                    | 153       | 1.84%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 141       | 1.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 131       | 1.58%   |
| Intel HD Graphics 5500                                                                   | 130       | 1.57%   |
| Intel HD Graphics 630                                                                    | 121       | 1.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 118       | 1.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 104       | 1.25%   |
| Intel HD Graphics 530                                                                    | 98        | 1.18%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 96        | 1.16%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 90        | 1.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 90        | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 88        | 1.06%   |
| AMD Lucienne                                                                             | 81        | 0.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 74        | 0.89%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 73        | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 72        | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 70        | 0.84%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 70        | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 68        | 0.82%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 63        | 0.76%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 62        | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 61        | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 58        | 0.7%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 55        | 0.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 54        | 0.65%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 52        | 0.63%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 50        | 0.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 48        | 0.58%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 45        | 0.54%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 45        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2156      | 32.36%  |
| 1 x AMD            | 1620      | 24.31%  |
| 1 x Nvidia         | 1348      | 20.23%  |
| Intel + Nvidia     | 1042      | 15.64%  |
| AMD + Nvidia       | 199       | 2.99%   |
| Intel + AMD        | 142       | 2.13%   |
| 2 x AMD            | 113       | 1.7%    |
| 2 x Nvidia         | 29        | 0.44%   |
| 1 x ASPEED         | 4         | 0.06%   |
| Other              | 3         | 0.05%   |
| 2 x Intel          | 2         | 0.03%   |
| Intel + 2 x Nvidia | 2         | 0.03%   |
| Nvidia + ASPEED    | 1         | 0.02%   |
| 1 x Matrox         | 1         | 0.02%   |
| Intel + 2 x AMD    | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4849      | 72.52%  |
| Proprietary | 1822      | 27.25%  |
| Unknown     | 15        | 0.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4211      | 62.36%  |
| 1.01-2.0   | 571       | 8.46%   |
| 7.01-8.0   | 435       | 6.44%   |
| 0.01-0.5   | 432       | 6.4%    |
| 3.01-4.0   | 393       | 5.82%   |
| 0.51-1.0   | 280       | 4.15%   |
| 5.01-6.0   | 239       | 3.54%   |
| 8.01-16.0  | 114       | 1.69%   |
| 2.01-3.0   | 61        | 0.9%    |
| 16.01-24.0 | 15        | 0.22%   |
| 4.01-5.0   | 2         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 859       | 11.06%  |
| AU Optronics            | 796       | 10.25%  |
| BOE                     | 696       | 8.96%   |
| LG Display              | 695       | 8.95%   |
| Chimei Innolux          | 680       | 8.75%   |
| Goldstar                | 441       | 5.68%   |
| Dell                    | 422       | 5.43%   |
| Acer                    | 291       | 3.75%   |
| AOC                     | 236       | 3.04%   |
| BenQ                    | 222       | 2.86%   |
| Ancor Communications    | 220       | 2.83%   |
| Hewlett-Packard         | 206       | 2.65%   |
| Philips                 | 171       | 2.2%    |
| Sharp                   | 163       | 2.1%    |
| Lenovo                  | 125       | 1.61%   |
| Apple                   | 118       | 1.52%   |
| LG Electronics          | 106       | 1.36%   |
| PANDA                   | 98        | 1.26%   |
| ViewSonic               | 92        | 1.18%   |
| ASUSTek Computer        | 82        | 1.06%   |
| Chi Mei Optoelectronics | 81        | 1.04%   |
| Iiyama                  | 61        | 0.79%   |
| Unknown                 | 48        | 0.62%   |
| Sony                    | 41        | 0.53%   |
| InfoVision              | 41        | 0.53%   |
| Unknown                 | 38        | 0.49%   |
| CSO                     | 27        | 0.35%   |
| Panasonic               | 26        | 0.33%   |
| MSI                     | 25        | 0.32%   |
| Vizio                   | 24        | 0.31%   |
| Eizo                    | 24        | 0.31%   |
| NEC Computers           | 22        | 0.28%   |
| Fujitsu Siemens         | 21        | 0.27%   |
| TMX                     | 19        | 0.24%   |
| Toshiba                 | 18        | 0.23%   |
| Sceptre Tech            | 18        | 0.23%   |
| LGD                     | 17        | 0.22%   |
| AUS                     | 17        | 0.22%   |
| LG Philips              | 16        | 0.21%   |
| Gigabyte Technology     | 16        | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 45        | 0.56%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 43        | 0.53%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 41        | 0.51%   |
| Unknown                                                                  | 38        | 0.47%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 34        | 0.42%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 30        | 0.37%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 29        | 0.36%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 22        | 0.27%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 21        | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 20        | 0.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 20        | 0.25%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 20        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 19        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 19        | 0.23%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 18        | 0.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 17        | 0.21%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 17        | 0.21%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 16        | 0.2%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 16        | 0.2%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 16        | 0.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 0.2%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 15        | 0.19%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 15        | 0.19%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 14        | 0.17%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.17%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 14        | 0.17%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                 | 13        | 0.16%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 13        | 0.16%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 13        | 0.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 12        | 0.15%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch             | 12        | 0.15%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 12        | 0.15%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 12        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3528      | 47.68%  |
| 1366x768 (WXGA)    | 1083      | 14.64%  |
| 3840x2160 (4K)     | 498       | 6.73%   |
| 2560x1440 (QHD)    | 432       | 5.84%   |
| 1600x900 (HD+)     | 201       | 2.72%   |
| Unknown            | 195       | 2.64%   |
| 1920x1200 (WUXGA)  | 162       | 2.19%   |
| 1680x1050 (WSXGA+) | 158       | 2.14%   |
| 1280x1024 (SXGA)   | 140       | 1.89%   |
| 1440x900 (WXGA+)   | 131       | 1.77%   |
| 3440x1440          | 101       | 1.36%   |
| 2560x1080          | 100       | 1.35%   |
| 1280x800 (WXGA)    | 87        | 1.18%   |
| 3840x1080          | 80        | 1.08%   |
| 2560x1600          | 63        | 0.85%   |
| 1360x768           | 43        | 0.58%   |
| 2880x1800          | 41        | 0.55%   |
| 3840x2400          | 25        | 0.34%   |
| 2160x1440          | 24        | 0.32%   |
| 1920x540           | 18        | 0.24%   |
| 4480x1440          | 13        | 0.18%   |
| 3840x1600          | 13        | 0.18%   |
| 3200x1800 (QHD+)   | 13        | 0.18%   |
| 5120x1440          | 11        | 0.15%   |
| 5760x1080          | 10        | 0.14%   |
| 3456x2160          | 10        | 0.14%   |
| 1280x720 (HD)      | 10        | 0.14%   |
| 1024x768 (XGA)     | 10        | 0.14%   |
| 3200x2000          | 9         | 0.12%   |
| 2256x1504          | 9         | 0.12%   |
| 1600x1200          | 9         | 0.12%   |
| 5760x2160          | 8         | 0.11%   |
| 2736x1824          | 8         | 0.11%   |
| 3600x1080          | 7         | 0.09%   |
| 3286x1080          | 7         | 0.09%   |
| 1920x1280          | 7         | 0.09%   |
| 3840x1200          | 6         | 0.08%   |
| 3000x2000          | 6         | 0.08%   |
| 3520x1080          | 5         | 0.07%   |
| 3360x1080          | 5         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1917      | 25.13%  |
| 13      | 734       | 9.62%   |
| Unknown | 607       | 7.96%   |
| 14      | 597       | 7.83%   |
| 27      | 585       | 7.67%   |
| 24      | 580       | 7.6%    |
| 23      | 474       | 6.21%   |
| 21      | 400       | 5.24%   |
| 17      | 325       | 4.26%   |
| 31      | 174       | 2.28%   |
| 34      | 157       | 2.06%   |
| 19      | 151       | 1.98%   |
| 12      | 107       | 1.4%    |
| 22      | 104       | 1.36%   |
| 18      | 94        | 1.23%   |
| 20      | 79        | 1.04%   |
| 11      | 65        | 0.85%   |
| 16      | 58        | 0.76%   |
| 84      | 50        | 0.66%   |
| 40      | 35        | 0.46%   |
| 32      | 33        | 0.43%   |
| 72      | 28        | 0.37%   |
| 54      | 28        | 0.37%   |
| 25      | 26        | 0.34%   |
| 28      | 19        | 0.25%   |
| 26      | 19        | 0.25%   |
| 48      | 16        | 0.21%   |
| 37      | 16        | 0.21%   |
| 65      | 15        | 0.2%    |
| 49      | 13        | 0.17%   |
| 33      | 12        | 0.16%   |
| 42      | 10        | 0.13%   |
| 29      | 10        | 0.13%   |
| 43      | 9         | 0.12%   |
| 52      | 8         | 0.1%    |
| 36      | 8         | 0.1%    |
| 35      | 8         | 0.1%    |
| 46      | 7         | 0.09%   |
| 10      | 7         | 0.09%   |
| 39      | 6         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 2931      | 39.28%  |
| 501-600     | 1486      | 19.91%  |
| 401-500     | 733       | 9.82%   |
| Unknown     | 607       | 8.13%   |
| 201-300     | 545       | 7.3%    |
| 351-400     | 406       | 5.44%   |
| 601-700     | 262       | 3.51%   |
| 701-800     | 209       | 2.8%    |
| 1001-1500   | 102       | 1.37%   |
| 1501-2000   | 88        | 1.18%   |
| 801-900     | 70        | 0.94%   |
| 901-1000    | 19        | 0.25%   |
| 101-200     | 3         | 0.04%   |
| 1-100       | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5081      | 74.68%  |
| 16/10   | 680       | 9.99%   |
| Unknown | 560       | 8.23%   |
| 21/9    | 180       | 2.65%   |
| 5/4     | 130       | 1.91%   |
| 3/2     | 91        | 1.34%   |
| 4/3     | 41        | 0.6%    |
| 32/9    | 21        | 0.31%   |
| 6/5     | 6         | 0.09%   |
| 0.62    | 3         | 0.04%   |
| 3.40    | 2         | 0.03%   |
| 1.96    | 2         | 0.03%   |
| 0.56    | 2         | 0.03%   |
| 3.20    | 1         | 0.01%   |
| 1.03    | 1         | 0.01%   |
| 0.80    | 1         | 0.01%   |
| 0.67    | 1         | 0.01%   |
| 0.58    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1914      | 25.35%  |
| 201-250        | 1257      | 16.65%  |
| 81-90          | 1032      | 13.67%  |
| Unknown        | 607       | 8.04%   |
| 301-350        | 596       | 7.9%    |
| 351-500        | 405       | 5.36%   |
| 151-200        | 322       | 4.27%   |
| 71-80          | 303       | 4.01%   |
| 121-130        | 231       | 3.06%   |
| 251-300        | 196       | 2.6%    |
| More than 1000 | 163       | 2.16%   |
| 141-150        | 129       | 1.71%   |
| 501-1000       | 113       | 1.5%    |
| 61-70          | 91        | 1.21%   |
| 51-60          | 68        | 0.9%    |
| 111-120        | 51        | 0.68%   |
| 131-140        | 42        | 0.56%   |
| 91-100         | 19        | 0.25%   |
| 41-50          | 6         | 0.08%   |
| 1-40           | 4         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 2136      | 29.16%  |
| 51-100        | 2124      | 28.99%  |
| 101-120       | 1647      | 22.48%  |
| Unknown       | 607       | 8.29%   |
| 161-240       | 473       | 6.46%   |
| More than 240 | 201       | 2.74%   |
| 1-50          | 138       | 1.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5222      | 77.34%  |
| 2     | 1304      | 19.31%  |
| 3     | 155       | 2.3%    |
| 0     | 58        | 0.86%   |
| 4     | 13        | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3739      | 37.66%  |
| Intel                             | 3421      | 34.46%  |
| Qualcomm Atheros                  | 994       | 10.01%  |
| Broadcom                          | 410       | 4.13%   |
| MediaTek                          | 132       | 1.33%   |
| TP-Link                           | 128       | 1.29%   |
| Ralink Technology                 | 128       | 1.29%   |
| Broadcom Limited                  | 94        | 0.95%   |
| Ralink                            | 71        | 0.72%   |
| Marvell Technology Group          | 58        | 0.58%   |
| Microsoft                         | 50        | 0.5%    |
| Nvidia                            | 44        | 0.44%   |
| Xiaomi                            | 42        | 0.42%   |
| Samsung Electronics               | 40        | 0.4%    |
| ASIX Electronics                  | 38        | 0.38%   |
| Sierra Wireless                   | 34        | 0.34%   |
| Qualcomm Atheros Communications   | 32        | 0.32%   |
| Aquantia                          | 32        | 0.32%   |
| Huawei Technologies               | 29        | 0.29%   |
| ASUSTek Computer                  | 28        | 0.28%   |
| Lenovo                            | 27        | 0.27%   |
| NetGear                           | 24        | 0.24%   |
| DisplayLink                       | 23        | 0.23%   |
| Dell                              | 22        | 0.22%   |
| D-Link                            | 22        | 0.22%   |
| Qualcomm                          | 21        | 0.21%   |
| Linksys                           | 19        | 0.19%   |
| JMicron Technology                | 17        | 0.17%   |
| Hewlett-Packard                   | 16        | 0.16%   |
| Edimax Technology                 | 13        | 0.13%   |
| Ericsson Business Mobile Networks | 11        | 0.11%   |
| D-Link System                     | 10        | 0.1%    |
| OnePlus Technology (Shenzhen)     | 9         | 0.09%   |
| Microchip Technology              | 9         | 0.09%   |
| Google                            | 9         | 0.09%   |
| Fibocom                           | 8         | 0.08%   |
| Motorola PCS                      | 7         | 0.07%   |
| Apple                             | 7         | 0.07%   |
| ZyXEL Communications              | 6         | 0.06%   |
| Mellanox Technologies             | 6         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2622      | 22.48%  |
| Intel Wi-Fi 6 AX200                                               | 502       | 4.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 351       | 3.01%   |
| Intel I211 Gigabit Network Connection                             | 284       | 2.43%   |
| Intel Wireless 8265 / 8275                                        | 236       | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 204       | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 199       | 1.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 186       | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 179       | 1.53%   |
| Realtek RTL8125 2.5GbE Controller                                 | 170       | 1.46%   |
| Intel Wireless 7265                                               | 166       | 1.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 154       | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 144       | 1.23%   |
| Intel Wireless 7260                                               | 141       | 1.21%   |
| Intel Wi-Fi 6 AX201                                               | 137       | 1.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 129       | 1.11%   |
| Intel Ethernet Connection (2) I219-V                              | 127       | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 122       | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 111       | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 109       | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 108       | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 105       | 0.9%    |
| Intel Wireless 8260                                               | 104       | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 99        | 0.85%   |
| Intel Wireless 3165                                               | 96        | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 93        | 0.8%    |
| Intel Wireless-AC 9260                                            | 92        | 0.79%   |
| Intel Ethernet Controller I225-V                                  | 88        | 0.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 84        | 0.72%   |
| Intel Ethernet Connection I217-LM                                 | 76        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 74        | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 73        | 0.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 66        | 0.57%   |
| Intel Ethernet Connection (7) I219-V                              | 62        | 0.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 57        | 0.49%   |
| Intel 82579V Gigabit Network Connection                           | 57        | 0.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 55        | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 53        | 0.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 53        | 0.45%   |
| Intel Ethernet Connection I217-V                                  | 50        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2673      | 48.42%  |
| Realtek Semiconductor                 | 959       | 17.37%  |
| Qualcomm Atheros                      | 775       | 14.04%  |
| Broadcom                              | 301       | 5.45%   |
| Ralink Technology                     | 128       | 2.32%   |
| MediaTek                              | 119       | 2.16%   |
| TP-Link                               | 110       | 1.99%   |
| Ralink                                | 71        | 1.29%   |
| Broadcom Limited                      | 70        | 1.27%   |
| Microsoft                             | 47        | 0.85%   |
| Sierra Wireless                       | 34        | 0.62%   |
| Qualcomm Atheros Communications       | 32        | 0.58%   |
| ASUSTek Computer                      | 26        | 0.47%   |
| NetGear                               | 24        | 0.43%   |
| D-Link                                | 22        | 0.4%    |
| Linksys                               | 18        | 0.33%   |
| Dell                                  | 16        | 0.29%   |
| Marvell Technology Group              | 14        | 0.25%   |
| Edimax Technology                     | 13        | 0.24%   |
| Qualcomm                              | 10        | 0.18%   |
| Fibocom                               | 8         | 0.14%   |
| D-Link System                         | 7         | 0.13%   |
| ZyXEL Communications                  | 6         | 0.11%   |
| Hewlett-Packard                       | 5         | 0.09%   |
| Belkin Components                     | 4         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.07%   |
| ZyDAS                                 | 3         | 0.05%   |
| Quectel Wireless Solutions            | 3         | 0.05%   |
| Mercucys                              | 3         | 0.05%   |
| IMC Networks                          | 3         | 0.05%   |
| Samsung Electronics                   | 2         | 0.04%   |
| Realtek                               | 2         | 0.04%   |
| AVM                                   | 2         | 0.04%   |
| Xiaomi                                | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Senao                                 | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Fujitsu Siemens Computers             | 1         | 0.02%   |
| Encore Electronics                    | 1         | 0.02%   |
| Apple                                 | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 502       | 9.02%   |
| Intel Wireless 8265 / 8275                                     | 236       | 4.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 186       | 3.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 179       | 3.22%   |
| Intel Wireless 7265                                            | 166       | 2.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 154       | 2.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 144       | 2.59%   |
| Intel Wireless 7260                                            | 141       | 2.53%   |
| Intel Wi-Fi 6 AX201                                            | 137       | 2.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 129       | 2.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 122       | 2.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 111       | 1.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 109       | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 108       | 1.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 105       | 1.89%   |
| Intel Wireless 8260                                            | 104       | 1.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 99        | 1.78%   |
| Intel Wireless 3165                                            | 96        | 1.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 93        | 1.67%   |
| Intel Wireless-AC 9260                                         | 92        | 1.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 84        | 1.51%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 74        | 1.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 73        | 1.31%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 66        | 1.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 57        | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 55        | 0.99%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 53        | 0.95%   |
| Intel Wireless 3160                                            | 48        | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 45        | 0.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 44        | 0.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 44        | 0.79%   |
| Realtek 802.11ac NIC                                           | 43        | 0.77%   |
| Ralink MT7601U Wireless Adapter                                | 42        | 0.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 42        | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 41        | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 41        | 0.74%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 41        | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                  | 40        | 0.72%   |
| Intel Centrino Wireless-N 2230                                 | 37        | 0.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 36        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3352      | 57.22%  |
| Intel                                  | 1585      | 27.06%  |
| Qualcomm Atheros                       | 303       | 5.17%   |
| Broadcom                               | 164       | 2.8%    |
| Nvidia                                 | 44        | 0.75%   |
| Marvell Technology Group               | 44        | 0.75%   |
| Xiaomi                                 | 40        | 0.68%   |
| ASIX Electronics                       | 38        | 0.65%   |
| Aquantia                               | 32        | 0.55%   |
| Lenovo                                 | 27        | 0.46%   |
| Broadcom Limited                       | 27        | 0.46%   |
| DisplayLink                            | 23        | 0.39%   |
| Samsung Electronics                    | 21        | 0.36%   |
| Huawei Technologies                    | 19        | 0.32%   |
| TP-Link                                | 18        | 0.31%   |
| JMicron Technology                     | 17        | 0.29%   |
| MediaTek                               | 11        | 0.19%   |
| Qualcomm                               | 10        | 0.17%   |
| Google                                 | 9         | 0.15%   |
| OnePlus Technology (Shenzhen)          | 6         | 0.1%    |
| Mellanox Technologies                  | 6         | 0.1%    |
| Apple                                  | 6         | 0.1%    |
| ZTE WCDMA Technologies MSM             | 5         | 0.09%   |
| OPPO Electronics                       | 5         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.07%   |
| Motorola PCS                           | 4         | 0.07%   |
| T & A Mobile Phones                    | 3         | 0.05%   |
| Microsoft                              | 3         | 0.05%   |
| ICS Advent                             | 3         | 0.05%   |
| Hewlett-Packard                        | 3         | 0.05%   |
| D-Link System                          | 3         | 0.05%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.03%   |
| Spreadtrum Communications              | 2         | 0.03%   |
| National Semiconductor                 | 2         | 0.03%   |
| HMD Global                             | 2         | 0.03%   |
| Foxconn / Hon Hai                      | 2         | 0.03%   |
| Attansic Technology                    | 2         | 0.03%   |
| ASUSTek Computer                       | 2         | 0.03%   |
| VIA Technologies                       | 1         | 0.02%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2622      | 43.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 351       | 5.85%   |
| Intel I211 Gigabit Network Connection                             | 284       | 4.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 204       | 3.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 199       | 3.32%   |
| Realtek RTL8125 2.5GbE Controller                                 | 170       | 2.83%   |
| Intel Ethernet Connection (2) I219-V                              | 127       | 2.12%   |
| Intel Ethernet Controller I225-V                                  | 88        | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 76        | 1.27%   |
| Intel Ethernet Connection (7) I219-V                              | 62        | 1.03%   |
| Intel 82579V Gigabit Network Connection                           | 57        | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 53        | 0.88%   |
| Intel Ethernet Connection I217-V                                  | 50        | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                             | 48        | 0.8%    |
| Intel Ethernet Connection (4) I219-V                              | 47        | 0.78%   |
| Intel Ethernet Connection (2) I218-V                              | 43        | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 42        | 0.7%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 40        | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 36        | 0.6%    |
| Intel Ethernet Connection I218-LM                                 | 34        | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 32        | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                             | 32        | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 31        | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 31        | 0.52%   |
| Intel Ethernet Connection (2) I219-LM                             | 31        | 0.52%   |
| Intel Ethernet Connection I219-LM                                 | 28        | 0.47%   |
| ASIX AX88179 Gigabit Ethernet                                     | 28        | 0.47%   |
| Intel Ethernet Connection (6) I219-V                              | 27        | 0.45%   |
| Intel 82577LM Gigabit Network Connection                          | 27        | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 26        | 0.43%   |
| Intel Ethernet Connection (10) I219-V                             | 26        | 0.43%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 25        | 0.42%   |
| Intel 82574L Gigabit Network Connection                           | 23        | 0.38%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 23        | 0.38%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 23        | 0.38%   |
| Intel I210 Gigabit Network Connection                             | 22        | 0.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 21        | 0.35%   |
| Intel Ethernet Connection I219-V                                  | 21        | 0.35%   |
| Intel Ethernet Connection (6) I219-LM                             | 21        | 0.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 20        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5510      | 50.94%  |
| WiFi     | 5208      | 48.15%  |
| Modem    | 88        | 0.81%   |
| Unknown  | 11        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4079      | 58.94%  |
| Ethernet | 2842      | 41.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3480      | 52.41%  |
| 1     | 2914      | 43.89%  |
| 3     | 156       | 2.35%   |
| 0     | 71        | 1.07%   |
| 4     | 9         | 0.14%   |
| 5     | 8         | 0.12%   |
| 8     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5597      | 83.2%   |
| Yes  | 1130      | 16.8%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2283      | 50.85%  |
| Realtek Semiconductor           | 492       | 10.96%  |
| Cambridge Silicon Radio         | 340       | 7.57%   |
| Qualcomm Atheros Communications | 331       | 7.37%   |
| IMC Networks                    | 186       | 4.14%   |
| Broadcom                        | 153       | 3.41%   |
| Lite-On Technology              | 144       | 3.21%   |
| Apple                           | 116       | 2.58%   |
| ASUSTek Computer                | 109       | 2.43%   |
| Foxconn / Hon Hai               | 91        | 2.03%   |
| Realtek                         | 43        | 0.96%   |
| Ralink                          | 25        | 0.56%   |
| Dell                            | 24        | 0.53%   |
| MediaTek                        | 19        | 0.42%   |
| Hewlett-Packard                 | 19        | 0.42%   |
| Toshiba                         | 15        | 0.33%   |
| TP-Link                         | 14        | 0.31%   |
| Marvell Semiconductor           | 11        | 0.24%   |
| Foxconn International           | 9         | 0.2%    |
| Edimax Technology               | 8         | 0.18%   |
| Opticis                         | 7         | 0.16%   |
| Dynex                           | 7         | 0.16%   |
| Ralink Technology               | 6         | 0.13%   |
| HTC (High Tech Computer)        | 5         | 0.11%   |
| Belkin Components               | 5         | 0.11%   |
| Alps Electric                   | 5         | 0.11%   |
| SINO WEALTH                     | 4         | 0.09%   |
| Conwise Technology              | 4         | 0.09%   |
| Askey Computer                  | 4         | 0.09%   |
| Integrated System Solution      | 3         | 0.07%   |
| Fujitsu                         | 2         | 0.04%   |
| USI                             | 1         | 0.02%   |
| Sitecom Europe                  | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |
| Chicony Electronics             | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 744       | 16.54%  |
| Intel AX200 Bluetooth                               | 475       | 10.56%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 346       | 7.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 340       | 7.56%   |
| Intel AX201 Bluetooth                               | 336       | 7.47%   |
| Realtek Bluetooth Radio                             | 316       | 7.03%   |
| Qualcomm Atheros  Bluetooth Device                  | 165       | 3.67%   |
| Realtek  Bluetooth 4.2 Adapter                      | 127       | 2.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 107       | 2.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 87        | 1.93%   |
| IMC Networks Bluetooth Radio                        | 76        | 1.69%   |
| Intel Bluetooth Device                              | 67        | 1.49%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 64        | 1.42%   |
| Intel AX210 Bluetooth                               | 62        | 1.38%   |
| Apple Bluetooth Host Controller                     | 56        | 1.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 48        | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 45        | 1%      |
| Lite-On Bluetooth Device                            | 44        | 0.98%   |
| Realtek Bluetooth Radio                             | 43        | 0.96%   |
| IMC Networks Bluetooth Device                       | 43        | 0.96%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 40        | 0.89%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 40        | 0.89%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 39        | 0.87%   |
| Apple Bluetooth USB Host Controller                 | 39        | 0.87%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 38        | 0.85%   |
| IMC Networks Wireless_Device                        | 37        | 0.82%   |
| Foxconn / Hon Hai Bluetooth Device                  | 35        | 0.78%   |
| Ralink RT3290 Bluetooth                             | 25        | 0.56%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 22        | 0.49%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 19        | 0.42%   |
| MediaTek Wireless_Device                            | 17        | 0.38%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.38%   |
| ASUS Bluetooth Radio                                | 17        | 0.38%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 16        | 0.36%   |
| Realtek RTL8821A Bluetooth                          | 16        | 0.36%   |
| Foxconn / Hon Hai Wireless_Device                   | 16        | 0.36%   |
| ASUS ASUS USB-BT500                                 | 16        | 0.36%   |
| TP-Link UB500 Adapter                               | 14        | 0.31%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 14        | 0.31%   |
| Realtek RTL8723B Bluetooth                          | 13        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 4364      | 43.96%  |
| AMD                                  | 2433      | 24.51%  |
| Nvidia                               | 1781      | 17.94%  |
| C-Media Electronics                  | 228       | 2.3%    |
| Logitech                             | 94        | 0.95%   |
| Creative Labs                        | 71        | 0.72%   |
| Kingston Technology                  | 61        | 0.61%   |
| JMTek                                | 53        | 0.53%   |
| Texas Instruments                    | 46        | 0.46%   |
| SteelSeries ApS                      | 41        | 0.41%   |
| Realtek Semiconductor                | 38        | 0.38%   |
| Focusrite-Novation                   | 38        | 0.38%   |
| Corsair                              | 36        | 0.36%   |
| Razer USA                            | 35        | 0.35%   |
| Generalplus Technology               | 35        | 0.35%   |
| Creative Technology                  | 35        | 0.35%   |
| ASUSTek Computer                     | 29        | 0.29%   |
| Blue Microphones                     | 28        | 0.28%   |
| Lenovo                               | 27        | 0.27%   |
| Plantronics                          | 26        | 0.26%   |
| GN Netcom                            | 26        | 0.26%   |
| BEHRINGER International              | 22        | 0.22%   |
| GYROCOM C&C                          | 17        | 0.17%   |
| Sony                                 | 16        | 0.16%   |
| Apple                                | 14        | 0.14%   |
| Samson Technologies                  | 13        | 0.13%   |
| M-Audio                              | 11        | 0.11%   |
| VIA Technologies                     | 10        | 0.1%    |
| RODE Microphones                     | 10        | 0.1%    |
| DSEA A/S                             | 10        | 0.1%    |
| Turtle Beach                         | 9         | 0.09%   |
| SAVITECH                             | 9         | 0.09%   |
| XMOS                                 | 8         | 0.08%   |
| Giga-Byte Technology                 | 8         | 0.08%   |
| Audio-Technica                       | 8         | 0.08%   |
| Astro Gaming                         | 8         | 0.08%   |
| Yamaha                               | 7         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 7         | 0.07%   |
| Sennheiser Communications            | 7         | 0.07%   |
| Microsoft                            | 7         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 868       | 7.23%   |
| Intel Sunrise Point-LP HD Audio                                            | 545       | 4.54%   |
| AMD Starship/Matisse HD Audio Controller                                   | 442       | 3.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 431       | 3.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 421       | 3.51%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 338       | 2.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 327       | 2.73%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 303       | 2.53%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 302       | 2.52%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 272       | 2.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 242       | 2.02%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 205       | 1.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 197       | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 190       | 1.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 188       | 1.57%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 179       | 1.49%   |
| Intel 8 Series HD Audio Controller                                         | 173       | 1.44%   |
| Intel Haswell-ULT HD Audio Controller                                      | 172       | 1.43%   |
| AMD FCH Azalia Controller                                                  | 160       | 1.33%   |
| Nvidia GP107GL High Definition Audio Controller                            | 154       | 1.28%   |
| Intel Broadwell-U Audio Controller                                         | 153       | 1.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 152       | 1.27%   |
| Nvidia GP106 High Definition Audio Controller                              | 149       | 1.24%   |
| Intel 200 Series PCH HD Audio                                              | 142       | 1.18%   |
| Nvidia GP104 High Definition Audio Controller                              | 140       | 1.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 139       | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                               | 137       | 1.14%   |
| AMD Navi 10 HDMI Audio                                                     | 120       | 1%      |
| Nvidia TU106 High Definition Audio Controller                              | 104       | 0.87%   |
| Intel Comet Lake PCH cAVS                                                  | 103       | 0.86%   |
| Intel CM238 HD Audio Controller                                            | 103       | 0.86%   |
| Nvidia TU116 High Definition Audio Controller                              | 102       | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 99        | 0.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 98        | 0.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 96        | 0.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 91        | 0.76%   |
| Nvidia GF108 High Definition Audio Controller                              | 85        | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 83        | 0.69%   |
| Nvidia GA104 High Definition Audio Controller                              | 83        | 0.69%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 83        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 1049      | 22.64%  |
| SK hynix                     | 696       | 15.02%  |
| Kingston                     | 558       | 12.04%  |
| Micron Technology            | 476       | 10.27%  |
| Corsair                      | 345       | 7.44%   |
| Unknown                      | 307       | 6.62%   |
| Crucial                      | 302       | 6.52%   |
| G.Skill                      | 256       | 5.52%   |
| A-DATA Technology            | 109       | 2.35%   |
| Ramaxel Technology           | 72        | 1.55%   |
| Elpida                       | 60        | 1.29%   |
| Team                         | 50        | 1.08%   |
| Patriot                      | 46        | 0.99%   |
| Nanya Technology             | 42        | 0.91%   |
| Unknown (ABCD)               | 31        | 0.67%   |
| GOODRAM                      | 28        | 0.6%    |
| Smart                        | 22        | 0.47%   |
| Transcend                    | 20        | 0.43%   |
| Unknown                      | 19        | 0.41%   |
| Apacer                       | 10        | 0.22%   |
| AMD                          | 10        | 0.22%   |
| Silicon Power                | 7         | 0.15%   |
| Kllisre                      | 7         | 0.15%   |
| ASint Technology             | 7         | 0.15%   |
| GeIL                         | 5         | 0.11%   |
| Teikon                       | 4         | 0.09%   |
| Qumo                         | 4         | 0.09%   |
| PNY                          | 4         | 0.09%   |
| Kingmax                      | 4         | 0.09%   |
| Goldkey                      | 4         | 0.09%   |
| Atermiter                    | 4         | 0.09%   |
| Smart Brazil                 | 3         | 0.06%   |
| SHARETRONIC                  | 3         | 0.06%   |
| Patriot Memory (PDP Systems) | 3         | 0.06%   |
| Neo Forza                    | 3         | 0.06%   |
| CSX                          | 3         | 0.06%   |
| Avant                        | 3         | 0.06%   |
| Unknown (08C8)               | 2         | 0.04%   |
| TwinMOS                      | 2         | 0.04%   |
| Timetec                      | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 58        | 1.17%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 57        | 1.15%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 46        | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 45        | 0.91%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 44        | 0.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 40        | 0.81%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 37        | 0.75%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 36        | 0.73%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 34        | 0.69%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 32        | 0.65%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 32        | 0.65%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 29        | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 28        | 0.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 27        | 0.54%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 27        | 0.54%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 26        | 0.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 26        | 0.52%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 25        | 0.5%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.48%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 21        | 0.42%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 20        | 0.4%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 20        | 0.4%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 20        | 0.4%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 20        | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 19        | 0.38%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.38%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 19        | 0.38%   |
| Unknown                                                          | 19        | 0.38%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.36%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.34%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 17        | 0.34%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 17        | 0.34%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s          | 17        | 0.34%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.32%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 16        | 0.32%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 16        | 0.32%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 16        | 0.32%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s           | 16        | 0.32%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2264      | 56.67%  |
| DDR3    | 1131      | 28.31%  |
| LPDDR4  | 163       | 4.08%   |
| LPDDR3  | 126       | 3.15%   |
| Unknown | 83        | 2.08%   |
| DDR2    | 75        | 1.88%   |
| SDRAM   | 72        | 1.8%    |
| DDR5    | 49        | 1.23%   |
| LPDDR5  | 15        | 0.38%   |
| DDR     | 14        | 0.35%   |
| DRAM    | 3         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2176      | 54.55%  |
| DIMM         | 1426      | 35.75%  |
| Row Of Chips | 349       | 8.75%   |
| Chip         | 21        | 0.53%   |
| Unknown      | 11        | 0.28%   |
| RIMM         | 3         | 0.08%   |
| FB-DIMM      | 3         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1923      | 44.35%  |
| 4096  | 1152      | 26.57%  |
| 16384 | 686       | 15.82%  |
| 2048  | 353       | 8.14%   |
| 32768 | 147       | 3.39%   |
| 1024  | 68        | 1.57%   |
| 512   | 5         | 0.12%   |
| 65536 | 1         | 0.02%   |
| 3072  | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 786       | 17.95%  |
| 2667    | 750       | 17.13%  |
| 3200    | 736       | 16.81%  |
| 2400    | 344       | 7.86%   |
| 2133    | 238       | 5.44%   |
| 1333    | 205       | 4.68%   |
| 3600    | 180       | 4.11%   |
| 1867    | 101       | 2.31%   |
| 1334    | 100       | 2.28%   |
| 3266    | 72        | 1.64%   |
| 4267    | 70        | 1.6%    |
| 800     | 57        | 1.3%    |
| 3400    | 53        | 1.21%   |
| 3000    | 52        | 1.19%   |
| 667     | 48        | 1.1%    |
| Unknown | 39        | 0.89%   |
| 4800    | 38        | 0.87%   |
| 1866    | 35        | 0.8%    |
| 3733    | 33        | 0.75%   |
| 3533    | 33        | 0.75%   |
| 1067    | 33        | 0.75%   |
| 3800    | 32        | 0.73%   |
| 3866    | 28        | 0.64%   |
| 4199    | 25        | 0.57%   |
| 3466    | 25        | 0.57%   |
| 2933    | 22        | 0.5%    |
| 1066    | 22        | 0.5%    |
| 4266    | 19        | 0.43%   |
| 2666    | 16        | 0.37%   |
| 6400    | 15        | 0.34%   |
| 2800    | 15        | 0.34%   |
| 1800    | 15        | 0.34%   |
| 2048    | 11        | 0.25%   |
| 3666    | 10        | 0.23%   |
| 975     | 9         | 0.21%   |
| 8400    | 7         | 0.16%   |
| 333     | 7         | 0.16%   |
| 5200    | 6         | 0.14%   |
| 3334    | 6         | 0.14%   |
| 2448    | 6         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 58        | 38.93%  |
| Brother Industries    | 25        | 16.78%  |
| Canon                 | 20        | 13.42%  |
| Seiko Epson           | 14        | 9.4%    |
| Samsung Electronics   | 9         | 6.04%   |
| Pantum                | 3         | 2.01%   |
| Apple                 | 3         | 2.01%   |
| Xerox                 | 2         | 1.34%   |
| Ricoh                 | 2         | 1.34%   |
| Prolific Technology   | 2         | 1.34%   |
| Dymo-CoStar           | 2         | 1.34%   |
| Zebra                 | 1         | 0.67%   |
| Xiaomi                | 1         | 0.67%   |
| STMicroelectronics    | 1         | 0.67%   |
| Sagem                 | 1         | 0.67%   |
| QinHeng Electronics   | 1         | 0.67%   |
| Oki Data              | 1         | 0.67%   |
| Lexmark International | 1         | 0.67%   |
| Kyocera               | 1         | 0.67%   |
| Graphtec America      | 1         | 0.67%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP OfficeJet 5200 series                                  | 4         | 2.67%   |
| HP LaserJet 1300                                          | 3         | 2%      |
| HP ENVY 4520 series                                       | 3         | 2%      |
| Apple Gamesir-T1s 2.0b                                    | 3         | 2%      |
| Xerox Phaser 3020                                         | 2         | 1.33%   |
| Seiko Epson L120 Series                                   | 2         | 1.33%   |
| Samsung ML-1640 Series Laser Printer                      | 2         | 1.33%   |
| Prolific PL2305 Parallel Port                             | 2         | 1.33%   |
| HP Officejet 2620 series                                  | 2         | 1.33%   |
| HP DeskJet 4530 series                                    | 2         | 1.33%   |
| HP DeskJet 3630 series                                    | 2         | 1.33%   |
| HP DeskJet 2700 series                                    | 2         | 1.33%   |
| HP DeskJet 2600 series                                    | 2         | 1.33%   |
| HP DeskJet 2130 series                                    | 2         | 1.33%   |
| HP Color LaserJet Pro M453-4                              | 2         | 1.33%   |
| Canon PIXMA MX340                                         | 2         | 1.33%   |
| Canon PIXMA MG2500 Series                                 | 2         | 1.33%   |
| Canon MG5700 series                                       | 2         | 1.33%   |
| Canon G3010 series                                        | 2         | 1.33%   |
| Brother MFC-L2710DW series                                | 2         | 1.33%   |
| Brother HL-L2300D series                                  | 2         | 1.33%   |
| Brother HL-5370DW series                                  | 2         | 1.33%   |
| Brother DCP-7040                                          | 2         | 1.33%   |
| Zebra ZTC ZC100                                           | 1         | 0.67%   |
| Xiaomi MiMouse 2                                          | 1         | 0.67%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 0.67%   |
| Seiko Epson XP-4100 Series                                | 1         | 0.67%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1         | 0.67%   |
| Seiko Epson Printer                                       | 1         | 0.67%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 0.67%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 0.67%   |
| Seiko Epson L805 Series                                   | 1         | 0.67%   |
| Seiko Epson L4260 Series                                  | 1         | 0.67%   |
| Seiko Epson L365 Series                                   | 1         | 0.67%   |
| Seiko Epson L355 Series                                   | 1         | 0.67%   |
| Seiko Epson ET-4760 Series                                | 1         | 0.67%   |
| Seiko Epson ET-3850 Series                                | 1         | 0.67%   |
| Seiko Epson ET-2810 Series                                | 1         | 0.67%   |
| Seiko Epson ET-2710 Series                                | 1         | 0.67%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 0.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 20        | 64.52%  |
| Seiko Epson        | 5         | 16.13%  |
| Hewlett-Packard    | 2         | 6.45%   |
| Visioneer          | 1         | 3.23%   |
| Ultima Electronics | 1         | 3.23%   |
| Mustek Systems     | 1         | 3.23%   |
| AGFA-Gevaert NV    | 1         | 3.23%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                                               | 5         | 16.13%  |
| Canon CanoScan LiDE 110                                                               | 5         | 16.13%  |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2         | 6.45%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 2         | 6.45%   |
| Canon CanoScan LIDE 25                                                                | 2         | 6.45%   |
| Visioneer OneTouch 5300 USB                                                           | 1         | 3.23%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 3.23%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 3.23%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 3.23%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1         | 3.23%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1         | 3.23%   |
| HP ScanJet 3500c                                                                      | 1         | 3.23%   |
| HP ScanJet 3400cse                                                                    | 1         | 3.23%   |
| Canon CanoScan LiDE 90                                                                | 1         | 3.23%   |
| Canon CanoScan LiDE 500F                                                              | 1         | 3.23%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1         | 3.23%   |
| Canon CanoScan LiDE 210                                                               | 1         | 3.23%   |
| Canon CanoScan LiDE 200                                                               | 1         | 3.23%   |
| Canon CanoScan LiDE 120                                                               | 1         | 3.23%   |
| AGFA-Gevaert NV SnapScan e26                                                          | 1         | 3.23%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 856       | 20.06%  |
| IMC Networks                           | 497       | 11.65%  |
| Microdia                               | 329       | 7.71%   |
| Realtek Semiconductor                  | 313       | 7.34%   |
| Logitech                               | 310       | 7.27%   |
| Quanta                                 | 226       | 5.3%    |
| Sunplus Innovation Technology          | 190       | 4.45%   |
| Bison Electronics                      | 163       | 3.82%   |
| Acer                                   | 157       | 3.68%   |
| Cheng Uei Precision Industry (Foxlink) | 147       | 3.45%   |
| Syntek                                 | 117       | 2.74%   |
| Lite-On Technology                     | 115       | 2.7%    |
| Apple                                  | 97        | 2.27%   |
| Suyin                                  | 93        | 2.18%   |
| Microsoft                              | 68        | 1.59%   |
| Silicon Motion                         | 57        | 1.34%   |
| Luxvisions Innotech Limited            | 56        | 1.31%   |
| Alcor Micro                            | 52        | 1.22%   |
| Samsung Electronics                    | 48        | 1.12%   |
| Z-Star Microelectronics                | 26        | 0.61%   |
| Ricoh                                  | 20        | 0.47%   |
| Sonix Technology                       | 17        | 0.4%    |
| Creative Technology                    | 15        | 0.35%   |
| Lenovo                                 | 14        | 0.33%   |
| Importek                               | 13        | 0.3%    |
| GEMBIRD                                | 13        | 0.3%    |
| MacroSilicon                           | 12        | 0.28%   |
| Generalplus Technology                 | 11        | 0.26%   |
| Primax Electronics                     | 10        | 0.23%   |
| LG Electronics                         | 9         | 0.21%   |
| Genesys Logic                          | 9         | 0.21%   |
| ARC International                      | 9         | 0.21%   |
| SunplusIT                              | 8         | 0.19%   |
| KYE Systems (Mouse Systems)            | 8         | 0.19%   |
| Google                                 | 8         | 0.19%   |
| DigiTech                               | 7         | 0.16%   |
| Cubeternet                             | 7         | 0.16%   |
| ALi                                    | 7         | 0.16%   |
| webcam                                 | 6         | 0.14%   |
| Valve Software                         | 5         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 217       | 5.05%   |
| IMC Networks Integrated Camera                      | 165       | 3.84%   |
| Microdia Integrated_Webcam_HD                       | 145       | 3.37%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 125       | 2.91%   |
| Realtek Integrated_Webcam_HD                        | 116       | 2.7%    |
| Chicony HD WebCam                                   | 88        | 2.05%   |
| Syntek Integrated Camera                            | 79        | 1.84%   |
| Logitech Webcam C270                                | 73        | 1.7%    |
| Logitech HD Pro Webcam C920                         | 66        | 1.54%   |
| Bison Integrated Camera                             | 61        | 1.42%   |
| Sunplus Integrated_Webcam_HD                        | 57        | 1.33%   |
| Samsung Galaxy series, misc. (MTP mode)             | 48        | 1.12%   |
| Acer Integrated Camera                              | 47        | 1.09%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 45        | 1.05%   |
| Lite-On Integrated Camera                           | 39        | 0.91%   |
| Chicony HP Wide Vision HD Camera                    | 36        | 0.84%   |
| Quanta HP TrueVision HD Camera                      | 35        | 0.81%   |
| Acer HD Webcam                                      | 34        | 0.79%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 33        | 0.77%   |
| Quanta HD User Facing                               | 31        | 0.72%   |
| Chicony HP HD Camera                                | 31        | 0.72%   |
| Chicony USB2.0 Camera                               | 29        | 0.67%   |
| Lite-On HP HD Camera                                | 28        | 0.65%   |
| Chicony HD User Facing                              | 27        | 0.63%   |
| Microsoft LifeCam HD-3000                           | 26        | 0.61%   |
| Realtek USB Camera                                  | 25        | 0.58%   |
| Logitech C922 Pro Stream Webcam                     | 25        | 0.58%   |
| Chicony USB2.0 HD UVC WebCam                        | 25        | 0.58%   |
| Bison SunplusIT Integrated Camera                   | 25        | 0.58%   |
| Quanta HP Wide Vision HD Camera                     | 24        | 0.56%   |
| Microdia Integrated Webcam                          | 24        | 0.56%   |
| Chicony EasyCamera                                  | 24        | 0.56%   |
| Chicony Lenovo EasyCamera                           | 23        | 0.54%   |
| Chicony HP Truevision HD                            | 23        | 0.54%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 22        | 0.51%   |
| IMC Networks HD Camera                              | 22        | 0.51%   |
| Syntek Lenovo EasyCamera                            | 21        | 0.49%   |
| Microdia Webcam Vitade AF                           | 21        | 0.49%   |
| Chicony HP TrueVision HD Camera                     | 21        | 0.49%   |
| Apple FaceTime HD Camera (Built-in)                 | 21        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 273       | 31.09%  |
| Validity Sensors                   | 252       | 28.7%   |
| Shenzhen Goodix Technology         | 180       | 20.5%   |
| Elan Microelectronics              | 64        | 7.29%   |
| LighTuning Technology              | 37        | 4.21%   |
| Upek                               | 27        | 3.08%   |
| AuthenTec                          | 22        | 2.51%   |
| STMicroelectronics                 | 8         | 0.91%   |
| Samsung Electronics                | 6         | 0.68%   |
| Focal-systems.Corp                 | 4         | 0.46%   |
| DigitalPersona                     | 2         | 0.23%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.11%   |
| HOLTEK                             | 1         | 0.11%   |
| Futronic Technology                | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 86        | 9.79%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 66        | 7.52%   |
| Shenzhen Goodix Fingerprint Reader                                         | 65        | 7.4%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 51        | 5.81%   |
| Elan ELAN:Fingerprint                                                      | 40        | 4.56%   |
| Synaptics UWP WBDI                                                         | 37        | 4.21%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 36        | 4.1%    |
| Validity Sensors Synaptics WBDI                                            | 30        | 3.42%   |
| Synaptics WBDI                                                             | 29        | 3.3%    |
| Shenzhen Goodix FingerPrint                                                | 29        | 3.3%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 27        | 3.08%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 2.73%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 24        | 2.73%   |
| Synaptics  WBDI                                                            | 23        | 2.62%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 23        | 2.62%   |
| Elan ELAN:ARM-M4                                                           | 20        | 2.28%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2.16%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 18        | 2.05%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 1.94%   |
| Validity Sensors VFS491                                                    | 16        | 1.82%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 1.71%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 14        | 1.59%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 1.48%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 1.37%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 12        | 1.37%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 1.14%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.03%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 9         | 1.03%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 0.91%   |
| Synaptics UWP WBDI Device                                                  | 7         | 0.8%    |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.8%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 6         | 0.68%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 0.68%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 0.57%   |
| Synaptics WBDI Device                                                      | 5         | 0.57%   |
| AuthenTec AES2810                                                          | 5         | 0.57%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.46%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 4         | 0.46%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 4         | 0.46%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.46%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 95        | 34.8%   |
| Broadcom                          | 92        | 33.7%   |
| Upek                              | 16        | 5.86%   |
| O2 Micro                          | 16        | 5.86%   |
| Lenovo                            | 16        | 5.86%   |
| Yubico.com                        | 9         | 3.3%    |
| Gemalto (was Gemplus)             | 9         | 3.3%    |
| VASCO Data Security International | 4         | 1.47%   |
| Realtek Semiconductor             | 4         | 1.47%   |
| OmniKey                           | 3         | 1.1%    |
| SCM Microsystems                  | 1         | 0.37%   |
| Reiner SCT Kartensysteme          | 1         | 0.37%   |
| Hewlett-Packard                   | 1         | 0.37%   |
| Clay Logic                        | 1         | 0.37%   |
| Cherry                            | 1         | 0.37%   |
| C3PO                              | 1         | 0.37%   |
| BIT4ID                            | 1         | 0.37%   |
| Aladdin Knowledge Systems         | 1         | 0.37%   |
| Advanced Card Systems             | 1         | 0.37%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 94        | 34.43%  |
| Broadcom BCM5880 Secure Applications Processor                               | 35        | 12.82%  |
| Broadcom 5880                                                                | 26        | 9.52%   |
| Broadcom 58200                                                               | 19        | 6.96%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 16        | 5.86%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 5.86%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 15        | 5.49%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 4.4%    |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 7         | 2.56%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 6         | 2.2%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 1.47%   |
| OmniKey 3x21 Smart Card Reader                                               | 3         | 1.1%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.73%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 2         | 0.73%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.73%   |
| VASCO Data Security International DIGIPASS 920                               | 1         | 0.37%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.37%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.37%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.37%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.37%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.37%   |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 0.37%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.37%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.37%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.37%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.37%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.37%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.37%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.37%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4686      | 69.48%  |
| 1     | 1684      | 24.97%  |
| 2     | 343       | 5.09%   |
| 3     | 28        | 0.42%   |
| 4     | 3         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 862       | 36.1%   |
| Graphics card            | 409       | 17.13%  |
| Net/wireless             | 313       | 13.11%  |
| Chipcard                 | 239       | 10.01%  |
| Multimedia controller    | 192       | 8.04%   |
| Camera                   | 83        | 3.48%   |
| Net/ethernet             | 62        | 2.6%    |
| Unassigned class         | 55        | 2.3%    |
| Bluetooth                | 46        | 1.93%   |
| Sound                    | 26        | 1.09%   |
| Communication controller | 24        | 1.01%   |
| Storage                  | 21        | 0.88%   |
| Card reader              | 16        | 0.67%   |
| Dvb card                 | 13        | 0.54%   |
| Network                  | 8         | 0.34%   |
| Storage/raid             | 6         | 0.25%   |
| Modem                    | 5         | 0.21%   |
| Video                    | 2         | 0.08%   |
| Storage/nvme             | 2         | 0.08%   |
| Storage/ide              | 2         | 0.08%   |
| Tv card                  | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |

