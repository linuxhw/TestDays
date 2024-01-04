CentOS 8 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for CentOS 8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 173

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Vostro 3558                 | [61cb58f13b](https://linux-hardware.org/?probe=61cb58f13b) | Aug 23, 2023 |
| Lenovo        | ThinkPad T430 2349JN0       | [fceb17b32c](https://linux-hardware.org/?probe=fceb17b32c) | Jan 10, 2023 |
| Lenovo        | ThinkPad T430 2349JN0       | [04a54f4c2f](https://linux-hardware.org/?probe=04a54f4c2f) | Jan 09, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [1b0b5a798f](https://linux-hardware.org/?probe=1b0b5a798f) | Dec 20, 2022 |
| Lenovo        | ThinkPad X260 20F6007KKR    | [9b788f857e](https://linux-hardware.org/?probe=9b788f857e) | Dec 14, 2022 |
| Acer          | Aspire E1-531               | [e9161d7c33](https://linux-hardware.org/?probe=e9161d7c33) | Jul 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [8bf06ee1c1](https://linux-hardware.org/?probe=8bf06ee1c1) | Jul 21, 2022 |
| ASUSTek       | X455LJ                      | [0c08648c4d](https://linux-hardware.org/?probe=0c08648c4d) | Jul 15, 2022 |
| Dell          | G3 3500                     | [3b770a574b](https://linux-hardware.org/?probe=3b770a574b) | Jun 11, 2022 |
| Dell          | Latitude 5591               | [0bc1368ac5](https://linux-hardware.org/?probe=0bc1368ac5) | Feb 28, 2022 |
| Dell          | Latitude 3420               | [5690460ebd](https://linux-hardware.org/?probe=5690460ebd) | Jan 31, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [6db6689862](https://linux-hardware.org/?probe=6db6689862) | Jan 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [dfe95d1e0a](https://linux-hardware.org/?probe=dfe95d1e0a) | Jan 24, 2022 |
| Fujitsu       | LIFEBOOK E752               | [e6e4d232a9](https://linux-hardware.org/?probe=e6e4d232a9) | Jan 02, 2022 |
| MSI           | GP75 Leopard 10SFK          | [f165698d96](https://linux-hardware.org/?probe=f165698d96) | Dec 29, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d14a949e3d](https://linux-hardware.org/?probe=d14a949e3d) | Dec 27, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [3af644f11a](https://linux-hardware.org/?probe=3af644f11a) | Dec 26, 2021 |
| Dell          | Latitude E6430              | [a7435eb4c7](https://linux-hardware.org/?probe=a7435eb4c7) | Nov 28, 2021 |
| ASUSTek       | N56VJ                       | [f39e92a1f3](https://linux-hardware.org/?probe=f39e92a1f3) | Nov 16, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d0fb953c7e](https://linux-hardware.org/?probe=d0fb953c7e) | Oct 11, 2021 |
| Dell          | Latitude E6430              | [3d605c2c36](https://linux-hardware.org/?probe=3d605c2c36) | Oct 05, 2021 |
| Dell          | Latitude E5470              | [17d97e59de](https://linux-hardware.org/?probe=17d97e59de) | Sep 23, 2021 |
| Dell          | Latitude E5470              | [82aca1d7b4](https://linux-hardware.org/?probe=82aca1d7b4) | Sep 16, 2021 |
| Dell          | Latitude E5470              | [c898d2b210](https://linux-hardware.org/?probe=c898d2b210) | Sep 16, 2021 |
| Sony          | SVT11215CGW                 | [0e12747ab1](https://linux-hardware.org/?probe=0e12747ab1) | Sep 12, 2021 |
| Dell          | Latitude 3420               | [1c1ef48be6](https://linux-hardware.org/?probe=1c1ef48be6) | Sep 06, 2021 |
| Dell          | Latitude E7450              | [090d2bd5c7](https://linux-hardware.org/?probe=090d2bd5c7) | Sep 05, 2021 |
| Dell          | Latitude E7450              | [c2d943414c](https://linux-hardware.org/?probe=c2d943414c) | Sep 04, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [9f3d5555ce](https://linux-hardware.org/?probe=9f3d5555ce) | Aug 26, 2021 |
| HP            | NOTEBOOKE 15-AY084TU        | [fe06a5029a](https://linux-hardware.org/?probe=fe06a5029a) | Aug 22, 2021 |
| Lenovo        | ThinkPad P50 20EN001PUS     | [38843da0aa](https://linux-hardware.org/?probe=38843da0aa) | Aug 18, 2021 |
| Lenovo        | ThinkPad P50 20EN001PUS     | [322b1fb2ba](https://linux-hardware.org/?probe=322b1fb2ba) | Aug 18, 2021 |
| Dell          | Latitude 7420               | [67165b9d66](https://linux-hardware.org/?probe=67165b9d66) | Aug 12, 2021 |
| Dell          | XPS 15 7590                 | [1778263a70](https://linux-hardware.org/?probe=1778263a70) | Aug 08, 2021 |
| Dell          | XPS 15 9570                 | [e329149eb4](https://linux-hardware.org/?probe=e329149eb4) | Aug 06, 2021 |
| HP            | EliteBook 8440p             | [80cb2748cf](https://linux-hardware.org/?probe=80cb2748cf) | Aug 02, 2021 |
| Acer          | Nitro AN515-51              | [130fff31f2](https://linux-hardware.org/?probe=130fff31f2) | Jul 12, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [8cf37f7d3d](https://linux-hardware.org/?probe=8cf37f7d3d) | Jul 11, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [3ec82c9dc0](https://linux-hardware.org/?probe=3ec82c9dc0) | Jul 11, 2021 |
| COPELION I... | QX-350                      | [6fd40c02da](https://linux-hardware.org/?probe=6fd40c02da) | Jul 01, 2021 |
| HP            | EliteBook 820 G2            | [4993490f00](https://linux-hardware.org/?probe=4993490f00) | Jul 01, 2021 |
| HP            | EliteBook 820 G2            | [69346a0102](https://linux-hardware.org/?probe=69346a0102) | Jul 01, 2021 |
| ASUSTek       | X455LJ                      | [b8a939ca9c](https://linux-hardware.org/?probe=b8a939ca9c) | Jun 27, 2021 |
| HP            | EliteBook 8740w             | [9b54339e9b](https://linux-hardware.org/?probe=9b54339e9b) | Jun 16, 2021 |
| HP            | EliteBook 8740w             | [9ad5884fca](https://linux-hardware.org/?probe=9ad5884fca) | Jun 16, 2021 |
| COPELION I... | QX-350                      | [7672d01a80](https://linux-hardware.org/?probe=7672d01a80) | Jun 08, 2021 |
| COPELION I... | QX-350                      | [4181e36f84](https://linux-hardware.org/?probe=4181e36f84) | Jun 07, 2021 |
| Dell          | Latitude E6530              | [eaf1c46fce](https://linux-hardware.org/?probe=eaf1c46fce) | May 29, 2021 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [5742c8e4e5](https://linux-hardware.org/?probe=5742c8e4e5) | May 28, 2021 |
| HP            | EliteBook 840 G5            | [ef516b4f37](https://linux-hardware.org/?probe=ef516b4f37) | May 17, 2021 |
| Lenovo        | ThinkPad W540 20BG001KUK    | [ce71038513](https://linux-hardware.org/?probe=ce71038513) | May 14, 2021 |
| Lenovo        | ThinkPad E490 20N8007NTX    | [e9efa41cf8](https://linux-hardware.org/?probe=e9efa41cf8) | May 12, 2021 |
| HP            | ZBook 15 G6                 | [ea363ea07e](https://linux-hardware.org/?probe=ea363ea07e) | May 07, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [1133f762f5](https://linux-hardware.org/?probe=1133f762f5) | Apr 15, 2021 |
| Dell          | Precision 3551              | [4e9b5b097e](https://linux-hardware.org/?probe=4e9b5b097e) | Apr 15, 2021 |
| Lenovo        | ThinkPad W540 20BHS20700    | [30edeadde3](https://linux-hardware.org/?probe=30edeadde3) | Apr 13, 2021 |
| Lenovo        | ThinkPad T460p 20FXS0220... | [3aef8ed384](https://linux-hardware.org/?probe=3aef8ed384) | Apr 11, 2021 |
| Lenovo        | ThinkPad E15 20RD0066TX     | [c3c1d01480](https://linux-hardware.org/?probe=c3c1d01480) | Apr 09, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [d4b7cef21b](https://linux-hardware.org/?probe=d4b7cef21b) | Apr 06, 2021 |
| HP            | ZBook 17 G2                 | [c974cb6fc7](https://linux-hardware.org/?probe=c974cb6fc7) | Apr 06, 2021 |
| Lenovo        | ThinkPad E15 20RD0066TX     | [3ab392c848](https://linux-hardware.org/?probe=3ab392c848) | Apr 05, 2021 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [4b9332ae3a](https://linux-hardware.org/?probe=4b9332ae3a) | Apr 05, 2021 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [d4a7fbec30](https://linux-hardware.org/?probe=d4a7fbec30) | Apr 01, 2021 |
| HP            | EliteBook 2540p             | [46c15e3b14](https://linux-hardware.org/?probe=46c15e3b14) | Apr 01, 2021 |
| LG Electro... | Z435-GE40K                  | [41dfc50f20](https://linux-hardware.org/?probe=41dfc50f20) | Mar 27, 2021 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [ba68c7c065](https://linux-hardware.org/?probe=ba68c7c065) | Mar 09, 2021 |
| HP            | ProBook 450 G5              | [fcc71c0314](https://linux-hardware.org/?probe=fcc71c0314) | Feb 13, 2021 |
| Acer          | Aspire V5-571G              | [6f498cb661](https://linux-hardware.org/?probe=6f498cb661) | Jan 27, 2021 |
| ASUSTek       | K54C                        | [ac91a40e03](https://linux-hardware.org/?probe=ac91a40e03) | Jan 24, 2021 |
| Sony          | VPCEG15FB                   | [badcac9c3d](https://linux-hardware.org/?probe=badcac9c3d) | Jan 17, 2021 |
| Lenovo        | V330-15IKB 81AX             | [48d877b127](https://linux-hardware.org/?probe=48d877b127) | Jan 07, 2021 |
| Acer          | Aspire 5750G                | [a448a76b2e](https://linux-hardware.org/?probe=a448a76b2e) | Jan 06, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [1ad69ae9c9](https://linux-hardware.org/?probe=1ad69ae9c9) | Jan 04, 2021 |
| Dell          | XPS L521X                   | [c109644955](https://linux-hardware.org/?probe=c109644955) | Dec 28, 2020 |
| Dell          | Latitude E7240              | [39e57b6b18](https://linux-hardware.org/?probe=39e57b6b18) | Dec 28, 2020 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [7038da6d94](https://linux-hardware.org/?probe=7038da6d94) | Dec 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [55e2883ca5](https://linux-hardware.org/?probe=55e2883ca5) | Dec 24, 2020 |
| Lenovo        | ThinkPad T460p 20FXS0220... | [048b297665](https://linux-hardware.org/?probe=048b297665) | Dec 23, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | [d87cdee8cb](https://linux-hardware.org/?probe=d87cdee8cb) | Dec 19, 2020 |
| Acer          | Aspire A715-75G             | [814f906095](https://linux-hardware.org/?probe=814f906095) | Dec 15, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [da43f75c0c](https://linux-hardware.org/?probe=da43f75c0c) | Dec 14, 2020 |
| ASUSTek       | X455LJ                      | [9938aa76cf](https://linux-hardware.org/?probe=9938aa76cf) | Dec 10, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | [9d12f4f222](https://linux-hardware.org/?probe=9d12f4f222) | Dec 10, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | [c26814bfc2](https://linux-hardware.org/?probe=c26814bfc2) | Dec 10, 2020 |
| Lenovo        | G70-70 80HW005XUK           | [a57125fe89](https://linux-hardware.org/?probe=a57125fe89) | Dec 07, 2020 |
| Acer          | Aspire V5-431P              | [831f0df544](https://linux-hardware.org/?probe=831f0df544) | Dec 03, 2020 |
| Dell          | Studio 1747                 | [dd0085228f](https://linux-hardware.org/?probe=dd0085228f) | Nov 29, 2020 |
| HP            | ZBook 15                    | [033521235f](https://linux-hardware.org/?probe=033521235f) | Nov 29, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | [c58ad8f5e8](https://linux-hardware.org/?probe=c58ad8f5e8) | Nov 28, 2020 |
| Lenovo        | ThinkPad X240 20AMS7XW00    | [b7783af763](https://linux-hardware.org/?probe=b7783af763) | Nov 19, 2020 |
| Sony          | VPCEH15FX                   | [cc8c7bc4c9](https://linux-hardware.org/?probe=cc8c7bc4c9) | Nov 19, 2020 |
| Acer          | Aspire V5-571G              | [b8d43abe6e](https://linux-hardware.org/?probe=b8d43abe6e) | Nov 18, 2020 |
| Acer          | Aspire V5-571G              | [49707be15c](https://linux-hardware.org/?probe=49707be15c) | Nov 16, 2020 |
| Dell          | Latitude 3440               | [17db1f31f6](https://linux-hardware.org/?probe=17db1f31f6) | Nov 13, 2020 |
| HP            | EliteBook 830 G6            | [0e0009bcfc](https://linux-hardware.org/?probe=0e0009bcfc) | Nov 13, 2020 |
| Lenovo        | ThinkPad T420 4238AB9       | [9c7ec388e0](https://linux-hardware.org/?probe=9c7ec388e0) | Nov 11, 2020 |
| ASUSTek       | X455LJ                      | [d0085b85ad](https://linux-hardware.org/?probe=d0085b85ad) | Nov 09, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [dbc5336b07](https://linux-hardware.org/?probe=dbc5336b07) | Nov 01, 2020 |
| Lenovo        | ThinkPad E590 20NBS03S00    | [29ae827508](https://linux-hardware.org/?probe=29ae827508) | Oct 29, 2020 |
| Unknown       | Unknown                     | [98cd8695de](https://linux-hardware.org/?probe=98cd8695de) | Oct 21, 2020 |
| Unknown       | Unknown                     | [a0e3328769](https://linux-hardware.org/?probe=a0e3328769) | Oct 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [50534bc0e0](https://linux-hardware.org/?probe=50534bc0e0) | Oct 01, 2020 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [b00098bf37](https://linux-hardware.org/?probe=b00098bf37) | Sep 29, 2020 |
| ASUSTek       | X556UB                      | [15790fbe92](https://linux-hardware.org/?probe=15790fbe92) | Sep 28, 2020 |
| Timi          | TM1709                      | [9d4bd50d80](https://linux-hardware.org/?probe=9d4bd50d80) | Sep 25, 2020 |
| Gigabyte      | P35V3                       | [55580f63c2](https://linux-hardware.org/?probe=55580f63c2) | Sep 14, 2020 |
| Apple         | MacBookPro12,1              | [daceea1b39](https://linux-hardware.org/?probe=daceea1b39) | Sep 08, 2020 |
| Lenovo        | ThinkPad T430s 2356CZ4      | [585b5cd200](https://linux-hardware.org/?probe=585b5cd200) | Aug 22, 2020 |
| Lenovo        | ThinkPad T430s 2356CZ4      | [b16e78abbf](https://linux-hardware.org/?probe=b16e78abbf) | Aug 21, 2020 |
| HP            | ProBook 440 G2              | [b19e6b64a7](https://linux-hardware.org/?probe=b19e6b64a7) | Aug 07, 2020 |
| MSI           | GE73VR 7RF                  | [8f05f68c7d](https://linux-hardware.org/?probe=8f05f68c7d) | Aug 04, 2020 |
| HP            | Notebook                    | [00a853f189](https://linux-hardware.org/?probe=00a853f189) | Aug 01, 2020 |
| Samsung       | 270E5J/2570EJ               | [8907cdddd5](https://linux-hardware.org/?probe=8907cdddd5) | Jul 24, 2020 |
| Samsung       | R560                        | [4d35b24594](https://linux-hardware.org/?probe=4d35b24594) | Jul 23, 2020 |
| HP            | EliteBook 850 G3            | [529b5be1b5](https://linux-hardware.org/?probe=529b5be1b5) | Jul 14, 2020 |
| HP            | ProBook 640 G2              | [53ba25afcd](https://linux-hardware.org/?probe=53ba25afcd) | Jul 14, 2020 |
| HP            | ProBook 450 G0              | [8566dd2843](https://linux-hardware.org/?probe=8566dd2843) | Jul 11, 2020 |
| HP            | ProBook 450 G0              | [116cbdcf22](https://linux-hardware.org/?probe=116cbdcf22) | Jul 09, 2020 |
| HP            | EliteBook 840 G5            | [8c28479e2e](https://linux-hardware.org/?probe=8c28479e2e) | Jun 19, 2020 |
| HP            | Laptop 14-bp0xx             | [6efe053f69](https://linux-hardware.org/?probe=6efe053f69) | Jun 18, 2020 |
| HP            | Laptop 14-bp0xx             | [e1611d4a8f](https://linux-hardware.org/?probe=e1611d4a8f) | Jun 18, 2020 |
| Lenovo        | Z50-70 20354                | [765261db4d](https://linux-hardware.org/?probe=765261db4d) | Jun 17, 2020 |
| Lenovo        | Z50-70 20354                | [08a9f86f96](https://linux-hardware.org/?probe=08a9f86f96) | Jun 17, 2020 |
| Dell          | Inspiron 5570               | [3d59a7abfb](https://linux-hardware.org/?probe=3d59a7abfb) | Jun 14, 2020 |
| Dell          | Inspiron 3520               | [0fe6cc7ec2](https://linux-hardware.org/?probe=0fe6cc7ec2) | Jun 11, 2020 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [4660651265](https://linux-hardware.org/?probe=4660651265) | Jun 09, 2020 |
| Sony          | VPCEG15FB                   | [764c88fff0](https://linux-hardware.org/?probe=764c88fff0) | May 30, 2020 |
| HP            | EliteBook 8440p             | [cc3e01ff0f](https://linux-hardware.org/?probe=cc3e01ff0f) | May 29, 2020 |
| Lenovo        | ThinkPad E580 20KS001JRT    | [a9b9b6f30e](https://linux-hardware.org/?probe=a9b9b6f30e) | May 29, 2020 |
| Acer          | Aspire 5750G                | [e99f24b527](https://linux-hardware.org/?probe=e99f24b527) | May 15, 2020 |
| ASUSTek       | X556UB                      | [ae412b00e1](https://linux-hardware.org/?probe=ae412b00e1) | May 02, 2020 |
| HP            | EliteBook 8440p             | [5856d8fd4a](https://linux-hardware.org/?probe=5856d8fd4a) | Apr 30, 2020 |
| Medion        | P6622                       | [57721ffc8f](https://linux-hardware.org/?probe=57721ffc8f) | Apr 29, 2020 |
| HP            | Laptop 14-dq1xxx            | [16dbe6c7cf](https://linux-hardware.org/?probe=16dbe6c7cf) | Apr 28, 2020 |
| Lenovo        | ThinkPad T500 2242CTO       | [8d383c8ba6](https://linux-hardware.org/?probe=8d383c8ba6) | Apr 25, 2020 |
| Lenovo        | ThinkPad T500 2242CTO       | [82c9bdc55a](https://linux-hardware.org/?probe=82c9bdc55a) | Apr 25, 2020 |
| Dell          | Inspiron 3520               | [30d580cc9d](https://linux-hardware.org/?probe=30d580cc9d) | Apr 23, 2020 |
| Dell          | Inspiron 3520               | [e18488f436](https://linux-hardware.org/?probe=e18488f436) | Apr 23, 2020 |
| Apple         | MacBookPro12,1              | [bf90b17b91](https://linux-hardware.org/?probe=bf90b17b91) | Apr 15, 2020 |
| Lenovo        | ThinkPad T440 20B7004JUS    | [7e54937ed3](https://linux-hardware.org/?probe=7e54937ed3) | Apr 15, 2020 |
| Apple         | MacBookPro12,1              | [e3673127d2](https://linux-hardware.org/?probe=e3673127d2) | Apr 14, 2020 |
| HP            | EliteBook Folio 9470m       | [9439de5a1c](https://linux-hardware.org/?probe=9439de5a1c) | Apr 12, 2020 |
| RM Educati... | RM                          | [548492cfc9](https://linux-hardware.org/?probe=548492cfc9) | Apr 11, 2020 |
| HP            | ProBook 430 G5              | [a1f59e373b](https://linux-hardware.org/?probe=a1f59e373b) | Apr 10, 2020 |
| Lenovo        | Z50-70 20354                | [03322f98e6](https://linux-hardware.org/?probe=03322f98e6) | Mar 24, 2020 |
| Lenovo        | B50-70 80EU                 | [32162d2fcb](https://linux-hardware.org/?probe=32162d2fcb) | Mar 19, 2020 |
| Acer          | One 14 Z2-485               | [d7c11b1573](https://linux-hardware.org/?probe=d7c11b1573) | Feb 24, 2020 |
| Acer          | One 14 Z2-485               | [22a7ce37ed](https://linux-hardware.org/?probe=22a7ce37ed) | Feb 24, 2020 |
| HP            | EliteBook 8570w             | [f2997e7cab](https://linux-hardware.org/?probe=f2997e7cab) | Feb 24, 2020 |
| HP            | ProBook 450 G5              | [d38140cd66](https://linux-hardware.org/?probe=d38140cd66) | Feb 24, 2020 |
| HP            | ProBook 450 G5              | [7d51d0400f](https://linux-hardware.org/?probe=7d51d0400f) | Feb 24, 2020 |
| Dell          | Precision 5510              | [97fdd683cd](https://linux-hardware.org/?probe=97fdd683cd) | Feb 23, 2020 |
| HP            | Laptop 15-bs1xx             | [891cb66753](https://linux-hardware.org/?probe=891cb66753) | Feb 06, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [10a7b3c4f3](https://linux-hardware.org/?probe=10a7b3c4f3) | Feb 01, 2020 |
| Acer          | TravelMate P257-M           | [5dbe9649a7](https://linux-hardware.org/?probe=5dbe9649a7) | Jan 28, 2020 |
| Clevo         | P15xEMx                     | [e41e485e3b](https://linux-hardware.org/?probe=e41e485e3b) | Jan 25, 2020 |
| ASUSTek       | X550MJ                      | [16470618ab](https://linux-hardware.org/?probe=16470618ab) | Jan 09, 2020 |
| Dell          | Inspiron N4010              | [5b5d5fc395](https://linux-hardware.org/?probe=5b5d5fc395) | Jan 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [95488c6be1](https://linux-hardware.org/?probe=95488c6be1) | Jan 02, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [925412ddcd](https://linux-hardware.org/?probe=925412ddcd) | Jan 02, 2020 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | [46bfb60272](https://linux-hardware.org/?probe=46bfb60272) | Dec 14, 2019 |
| Dell          | Studio 1747                 | [e572489472](https://linux-hardware.org/?probe=e572489472) | Dec 05, 2019 |
| Toshiba       | Satellite L15W-B            | [c90b14d1e5](https://linux-hardware.org/?probe=c90b14d1e5) | Dec 03, 2019 |
| Dell          | Studio 1747                 | [24d64d118b](https://linux-hardware.org/?probe=24d64d118b) | Dec 02, 2019 |
| ASUSTek       | E202SA                      | [e052cf247b](https://linux-hardware.org/?probe=e052cf247b) | Nov 23, 2019 |
| Toshiba       | Satellite L15W-B            | [c96da5df5e](https://linux-hardware.org/?probe=c96da5df5e) | Nov 20, 2019 |
| Toshiba       | Satellite L15W-B            | [bf3a6bb4c3](https://linux-hardware.org/?probe=bf3a6bb4c3) | Nov 20, 2019 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [df76fe3ea4](https://linux-hardware.org/?probe=df76fe3ea4) | Nov 14, 2019 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [448a81eb7c](https://linux-hardware.org/?probe=448a81eb7c) | Nov 14, 2019 |
| HP            | Notebook                    | [4aae147ff7](https://linux-hardware.org/?probe=4aae147ff7) | Nov 01, 2019 |
| Sony          | VPCEH26EN                   | [28024462ac](https://linux-hardware.org/?probe=28024462ac) | Oct 22, 2019 |
| RM Educati... | RM                          | [4d22671841](https://linux-hardware.org/?probe=4d22671841) | Oct 03, 2019 |
| RM Educati... | RM                          | [43aad9067d](https://linux-hardware.org/?probe=43aad9067d) | Oct 02, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.18.0-147.8.1.el8_1.x86_64  | 11        | 8.4%    |
| 4.18.0-193.6.3.el8_2.x86_64  | 9         | 6.87%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 8         | 6.11%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 7         | 5.34%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 7         | 5.34%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 6         | 4.58%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 5         | 3.82%   |
| 4.18.0-193.14.2.el8_2.x86_64 | 5         | 3.82%   |
| 4.18.0-305.3.1.el8.x86_64    | 4         | 3.05%   |
| 4.18.0-294.el8.x86_64        | 4         | 3.05%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 4         | 3.05%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 4         | 3.05%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 2.29%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 3         | 2.29%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 3         | 2.29%   |
| 4.18.0-277.el8.x86_64        | 3         | 2.29%   |
| 4.18.0-240.el8.x86_64        | 3         | 2.29%   |
| 4.18.0-193.el8.x86_64        | 3         | 2.29%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 3         | 2.29%   |
| 4.18.0-147.6.el8.x86_64      | 3         | 2.29%   |
| 5.15.11-1.el8.elrepo.x86_64  | 2         | 1.53%   |
| 4.18.0-80.el8.x86_64         | 2         | 1.53%   |
| 4.18.0-408.el8.x86_64        | 2         | 1.53%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 2         | 1.53%   |
| 4.18.0-301.1.el8.x86_64      | 2         | 1.53%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 2         | 1.53%   |
| 4.18.0-147.el8.x86_64        | 2         | 1.53%   |
| 5.9.12-1.el8.elrepo.x86_64   | 1         | 0.76%   |
| 5.9.1-1.el8.elrepo.x86_64    | 1         | 0.76%   |
| 5.8.11-1.el8.elrepo.x86_64   | 1         | 0.76%   |
| 5.17.2-1.el8.elrepo.x86_64   | 1         | 0.76%   |
| 5.13.7-1.el8.elrepo.x86_64   | 1         | 0.76%   |
| 4.18.0-80.7.1.el8_0.x86_64   | 1         | 0.76%   |
| 4.18.0-500.el8.x86_64        | 1         | 0.76%   |
| 4.18.0-365.el8.x86_64        | 1         | 0.76%   |
| 4.18.0-358.el8.x86_64        | 1         | 0.76%   |
| 4.18.0-348.el8.x86_64        | 1         | 0.76%   |
| 4.18.0-338.el8.x86_64        | 1         | 0.76%   |
| 4.18.0-315.el8.x86_64        | 1         | 0.76%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 1         | 0.76%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 112       | 94.12%  |
| 5.15.11 | 2         | 1.68%   |
| 5.9.12  | 1         | 0.84%   |
| 5.9.1   | 1         | 0.84%   |
| 5.8.11  | 1         | 0.84%   |
| 5.17.2  | 1         | 0.84%   |
| 5.13.7  | 1         | 0.84%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 112       | 94.12%  |
| 5.9     | 2         | 1.68%   |
| 5.15    | 2         | 1.68%   |
| 5.8     | 1         | 0.84%   |
| 5.17    | 1         | 0.84%   |
| 5.13    | 1         | 0.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 119       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 108       | 89.26%  |
| GNOME Classic | 4         | 3.31%   |
| Unknown       | 3         | 2.48%   |
| XFCE          | 2         | 1.65%   |
| MATE          | 2         | 1.65%   |
| KDE5          | 1         | 0.83%   |
| KDE           | 1         | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 79        | 62.7%   |
| X11     | 43        | 34.13%  |
| Unknown | 3         | 2.38%   |
| Web     | 1         | 0.79%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 72        | 59.02%  |
| GDM     | 48        | 39.34%  |
| TDM     | 1         | 0.82%   |
| LightDM | 1         | 0.82%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 62        | 51.24%  |
| en_GB   | 10        | 8.26%   |
| Unknown | 10        | 8.26%   |
| de_DE   | 7         | 5.79%   |
| pt_BR   | 6         | 4.96%   |
| ru_RU   | 4         | 3.31%   |
| fr_FR   | 4         | 3.31%   |
| ko_KR   | 3         | 2.48%   |
| en_IN   | 3         | 2.48%   |
| en_CA   | 3         | 2.48%   |
| nb_NO   | 2         | 1.65%   |
| zh_CN   | 1         | 0.83%   |
| it_IT   | 1         | 0.83%   |
| es_PE   | 1         | 0.83%   |
| es_MX   | 1         | 0.83%   |
| es_AR   | 1         | 0.83%   |
| en_IE   | 1         | 0.83%   |
| da_DK   | 1         | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 78        | 65%     |
| BIOS | 42        | 35%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 106       | 87.6%   |
| Ext4    | 11        | 9.09%   |
| Unknown | 4         | 3.31%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 73        | 60.33%  |
| GPT     | 35        | 28.93%  |
| MBR     | 13        | 10.74%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 108       | 90.76%  |
| Yes       | 11        | 9.24%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 101       | 84.17%  |
| Yes       | 19        | 15.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 34        | 28.57%  |
| Hewlett-Packard        | 25        | 21.01%  |
| Dell                   | 21        | 17.65%  |
| ASUSTek Computer       | 9         | 7.56%   |
| Acer                   | 8         | 6.72%   |
| Samsung Electronics    | 5         | 4.2%    |
| Sony                   | 4         | 3.36%   |
| MSI                    | 2         | 1.68%   |
| Toshiba                | 1         | 0.84%   |
| Timi                   | 1         | 0.84%   |
| RM Education           | 1         | 0.84%   |
| Medion                 | 1         | 0.84%   |
| LG Electronics         | 1         | 0.84%   |
| Gigabyte Technology    | 1         | 0.84%   |
| Fujitsu                | 1         | 0.84%   |
| COPELION INTERNATIONAL | 1         | 0.84%   |
| Clevo                  | 1         | 0.84%   |
| Apple                  | 1         | 0.84%   |
| Unknown                | 1         | 0.84%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Lenovo Z50-70 20354                               | 2         | 1.68%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK             | 2         | 1.68%   |
| HP ProBook 450 G5                                 | 2         | 1.68%   |
| HP Notebook                                       | 2         | 1.68%   |
| Dell Studio 1747                                  | 2         | 1.68%   |
| Dell Latitude E5470                               | 2         | 1.68%   |
| Toshiba Satellite L15W-B                          | 1         | 0.84%   |
| Timi TM1709                                       | 1         | 0.84%   |
| Sony VPCEH26EN                                    | 1         | 0.84%   |
| Sony VPCEH15FX                                    | 1         | 0.84%   |
| Sony VPCEG15FB                                    | 1         | 0.84%   |
| Sony SVT11215CGW                                  | 1         | 0.84%   |
| Samsung R560                                      | 1         | 0.84%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B               | 1         | 0.84%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.84%   |
| Samsung 300E4A/300E5A/300E7A                      | 1         | 0.84%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.84%   |
| RM Education RM                                   | 1         | 0.84%   |
| MSI GP75 Leopard 10SFK                            | 1         | 0.84%   |
| MSI GE73VR 7RF                                    | 1         | 0.84%   |
| Medion P6622                                      | 1         | 0.84%   |
| LG Z435-GE40K                                     | 1         | 0.84%   |
| Lenovo V330-15IKB 81AX                            | 1         | 0.84%   |
| Lenovo ThinkPad X260 20F6007KKR                   | 1         | 0.84%   |
| Lenovo ThinkPad X240 20AMS7XW00                   | 1         | 0.84%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00          | 1         | 0.84%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A7CT01WW          | 1         | 0.84%   |
| Lenovo ThinkPad W540 20BHS20700                   | 1         | 0.84%   |
| Lenovo ThinkPad W540 20BG001KUK                   | 1         | 0.84%   |
| Lenovo ThinkPad T500 2242CTO                      | 1         | 0.84%   |
| Lenovo ThinkPad T490s 20NYS02900                  | 1         | 0.84%   |
| Lenovo ThinkPad T480s 20L8002WMX                  | 1         | 0.84%   |
| Lenovo ThinkPad T460p 20FXS02200                  | 1         | 0.84%   |
| Lenovo ThinkPad T440 20B7004JUS                   | 1         | 0.84%   |
| Lenovo ThinkPad T430s 2356CZ4                     | 1         | 0.84%   |
| Lenovo ThinkPad T430 2349JN0                      | 1         | 0.84%   |
| Lenovo ThinkPad T420 4238AB9                      | 1         | 0.84%   |
| Lenovo ThinkPad T14s Gen 2i 20WNS5JQ00            | 1         | 0.84%   |
| Lenovo ThinkPad P51 W10DG 20MNS08X00              | 1         | 0.84%   |
| Lenovo ThinkPad P50 20EN001PUS                    | 1         | 0.84%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 22        | 18.49%  |
| HP EliteBook      | 9         | 7.56%   |
| Dell Latitude     | 9         | 7.56%   |
| Lenovo IdeaPad    | 7         | 5.88%   |
| HP ProBook        | 6         | 5.04%   |
| Acer Aspire       | 5         | 4.2%    |
| HP ZBook          | 3         | 2.52%   |
| HP Laptop         | 3         | 2.52%   |
| Dell XPS          | 3         | 2.52%   |
| Dell Inspiron     | 3         | 2.52%   |
| Lenovo Z50-70     | 2         | 1.68%   |
| HP Notebook       | 2         | 1.68%   |
| Dell Studio       | 2         | 1.68%   |
| Dell Precision    | 2         | 1.68%   |
| ASUS VivoBook     | 2         | 1.68%   |
| Toshiba Satellite | 1         | 0.84%   |
| Timi TM1709       | 1         | 0.84%   |
| Sony VPCEH26EN    | 1         | 0.84%   |
| Sony VPCEH15FX    | 1         | 0.84%   |
| Sony VPCEG15FB    | 1         | 0.84%   |
| Sony SVT11215CGW  | 1         | 0.84%   |
| Samsung R560      | 1         | 0.84%   |
| Samsung 700Z3A    | 1         | 0.84%   |
| Samsung 500R4K    | 1         | 0.84%   |
| Samsung 300E4A    | 1         | 0.84%   |
| Samsung 270E5J    | 1         | 0.84%   |
| RM Education RM   | 1         | 0.84%   |
| MSI GP75          | 1         | 0.84%   |
| MSI GE73VR        | 1         | 0.84%   |
| Medion P6622      | 1         | 0.84%   |
| LG Z435-GE40K     | 1         | 0.84%   |
| Lenovo V330-15IKB | 1         | 0.84%   |
| Lenovo G70-70     | 1         | 0.84%   |
| Lenovo B50-70     | 1         | 0.84%   |
| HP Pavilion       | 1         | 0.84%   |
| HP NOTEBOOKE      | 1         | 0.84%   |
| Gigabyte P35V3    | 1         | 0.84%   |
| Fujitsu LIFEBOOK  | 1         | 0.84%   |
| Dell Vostro       | 1         | 0.84%   |
| Dell G3           | 1         | 0.84%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 19        | 15.97%  |
| 2019 | 15        | 12.61%  |
| 2014 | 14        | 11.76%  |
| 2016 | 13        | 10.92%  |
| 2020 | 9         | 7.56%   |
| 2018 | 9         | 7.56%   |
| 2015 | 9         | 7.56%   |
| 2017 | 8         | 6.72%   |
| 2010 | 7         | 5.88%   |
| 2013 | 6         | 5.04%   |
| 2011 | 6         | 5.04%   |
| 2021 | 2         | 1.68%   |
| 2008 | 2         | 1.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 119       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 105       | 87.5%   |
| Enabled  | 15        | 12.5%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 119       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 45        | 37.82%  |
| 16.01-24.0  | 23        | 19.33%  |
| 3.01-4.0    | 21        | 17.65%  |
| 8.01-16.0   | 14        | 11.76%  |
| 32.01-64.0  | 13        | 10.92%  |
| 24.01-32.0  | 1         | 0.84%   |
| 64.01-256.0 | 1         | 0.84%   |
| 1.01-2.0    | 1         | 0.84%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 44        | 34.38%  |
| 4.01-8.0   | 26        | 20.31%  |
| 3.01-4.0   | 25        | 19.53%  |
| 1.01-2.0   | 21        | 16.41%  |
| 8.01-16.0  | 9         | 7.03%   |
| 0.51-1.0   | 2         | 1.56%   |
| 24.01-32.0 | 1         | 0.78%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 86        | 72.27%  |
| 2      | 26        | 21.85%  |
| 3      | 4         | 3.36%   |
| 4      | 3         | 2.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 72        | 60.5%   |
| Yes       | 47        | 39.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 88.24%  |
| No        | 14        | 11.76%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 99.16%  |
| No        | 1         | 0.84%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 79.83%  |
| No        | 24        | 20.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 21        | 17.5%   |
| Germany      | 12        | 10%     |
| UK           | 7         | 5.83%   |
| Brazil       | 7         | 5.83%   |
| India        | 6         | 5%      |
| Sweden       | 5         | 4.17%   |
| Belgium      | 5         | 4.17%   |
| Russia       | 4         | 3.33%   |
| Mexico       | 4         | 3.33%   |
| France       | 4         | 3.33%   |
| China        | 4         | 3.33%   |
| Spain        | 3         | 2.5%    |
| South Korea  | 3         | 2.5%    |
| Italy        | 3         | 2.5%    |
| Canada       | 3         | 2.5%    |
| Turkey       | 2         | 1.67%   |
| Peru         | 2         | 1.67%   |
| Norway       | 2         | 1.67%   |
| Netherlands  | 2         | 1.67%   |
| Indonesia    | 2         | 1.67%   |
| Austria      | 2         | 1.67%   |
| Vietnam      | 1         | 0.83%   |
| Ukraine      | 1         | 0.83%   |
| South Africa | 1         | 0.83%   |
| Serbia       | 1         | 0.83%   |
| Morocco      | 1         | 0.83%   |
| Malaysia     | 1         | 0.83%   |
| Lithuania    | 1         | 0.83%   |
| Israel       | 1         | 0.83%   |
| Ireland      | 1         | 0.83%   |
| Greece       | 1         | 0.83%   |
| Egypt        | 1         | 0.83%   |
| Burkina Faso | 1         | 0.83%   |
| Bulgaria     | 1         | 0.83%   |
| Belarus      | 1         | 0.83%   |
| Bangladesh   | 1         | 0.83%   |
| Argentina    | 1         | 0.83%   |
| Afghanistan  | 1         | 0.83%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Sollentuna      | 2         | 1.61%   |
| Sao Paulo       | 2         | 1.61%   |
| Munich          | 2         | 1.61%   |
| Moscow          | 2         | 1.61%   |
| Mexico City     | 2         | 1.61%   |
| Lima            | 2         | 1.61%   |
| Denver          | 2         | 1.61%   |
| Zirndorf        | 1         | 0.81%   |
| Yeonsu-gu       | 1         | 0.81%   |
| Yekaterinburg   | 1         | 0.81%   |
| Yangpu          | 1         | 0.81%   |
| Xuhui           | 1         | 0.81%   |
| Wheeling        | 1         | 0.81%   |
| Vilnius         | 1         | 0.81%   |
| Viladecans      | 1         | 0.81%   |
| Vancouver       | 1         | 0.81%   |
| Utrecht         | 1         | 0.81%   |
| Turnhout        | 1         | 0.81%   |
| Touget          | 1         | 0.81%   |
| Toronto         | 1         | 0.81%   |
| Tolosa          | 1         | 0.81%   |
| Tel Aviv        | 1         | 0.81%   |
| Subotica        | 1         | 0.81%   |
| Southend-on-Sea | 1         | 0.81%   |
| Sofia           | 1         | 0.81%   |
| Sleman          | 1         | 0.81%   |
| Skreia          | 1         | 0.81%   |
| Sillod          | 1         | 0.81%   |
| Sheffield       | 1         | 0.81%   |
| Shah Alam       | 1         | 0.81%   |
| Seoul           | 1         | 0.81%   |
| San Antonio     | 1         | 0.81%   |
| Salé           | 1         | 0.81%   |
| Rethymno        | 1         | 0.81%   |
| Puebla          | 1         | 0.81%   |
| Portland        | 1         | 0.81%   |
| Port Elizabeth  | 1         | 0.81%   |
| Plano           | 1         | 0.81%   |
| Pirganj         | 1         | 0.81%   |
| Piacenza        | 1         | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 25        | 36     | 16.23%  |
| Seagate                 | 20        | 23     | 12.99%  |
| Toshiba                 | 14        | 17     | 9.09%   |
| WDC                     | 13        | 16     | 8.44%   |
| SanDisk                 | 13        | 14     | 8.44%   |
| Unknown                 | 10        | 12     | 6.49%   |
| Kingston                | 8         | 9      | 5.19%   |
| HGST                    | 7         | 8      | 4.55%   |
| Crucial                 | 6         | 7      | 3.9%    |
| Intel                   | 5         | 6      | 3.25%   |
| SK hynix                | 4         | 4      | 2.6%    |
| Hitachi                 | 3         | 4      | 1.95%   |
| SPCC                    | 2         | 2      | 1.3%    |
| Micron Technology       | 2         | 2      | 1.3%    |
| LITEON                  | 2         | 3      | 1.3%    |
| Lenovo                  | 2         | 3      | 1.3%    |
| KIOXIA                  | 2         | 3      | 1.3%    |
| A-DATA Technology       | 2         | 2      | 1.3%    |
| XrayDisk                | 1         | 1      | 0.65%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.65%   |
| Union Memory            | 1         | 1      | 0.65%   |
| UMIS                    | 1         | 1      | 0.65%   |
| Transcend               | 1         | 2      | 0.65%   |
| SSD                     | 1         | 1      | 0.65%   |
| Silicon Motion          | 1         | 1      | 0.65%   |
| Plextor                 | 1         | 1      | 0.65%   |
| LITEONIT                | 1         | 1      | 0.65%   |
| Lexar                   | 1         | 1      | 0.65%   |
| JetFlash                | 1         | 1      | 0.65%   |
| Biostar                 | 1         | 1      | 0.65%   |
| Apple                   | 1         | 1      | 0.65%   |
| 980Plus                 | 1         | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                  | 5         | 3.11%   |
| Seagate ST1000LM035-1RK172 1TB          | 4         | 2.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4         | 2.48%   |
| Samsung NVMe SSD Drive 512GB            | 4         | 2.48%   |
| Unknown MMC Card  32GB                  | 3         | 1.86%   |
| SanDisk NVMe SSD Drive 512GB            | 3         | 1.86%   |
| Kingston SA400M8240G 240GB SSD          | 3         | 1.86%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 1.24%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 1.24%   |
| SanDisk NVMe SSD Drive 500GB            | 2         | 1.24%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB  | 2         | 1.24%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD    | 2         | 1.24%   |
| Kingston SA400S37120G 120GB SSD         | 2         | 1.24%   |
| Hitachi HTS547550A9E384 500GB           | 2         | 1.24%   |
| HGST HTS545050A7E680 500GB              | 2         | 1.24%   |
| HGST HTS545050A7E380 500GB              | 2         | 1.24%   |
| XrayDisk SSD 240GB                      | 1         | 0.62%   |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 1         | 0.62%   |
| WDC WDS500G1R0B-68A4Z0 500GB SSD        | 1         | 0.62%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 1         | 0.62%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD          | 1         | 0.62%   |
| WDC WD7500BPKX-22HPJT0 752GB            | 1         | 0.62%   |
| WDC WD5000BEVT-00A0RT0 500GB            | 1         | 0.62%   |
| WDC WD3200BEKT-60PVMT0 320GB            | 1         | 0.62%   |
| WDC WD1600BEVT-75ZCT2 160GB             | 1         | 0.62%   |
| WDC WD10SPZX-24Z10 1TB                  | 1         | 0.62%   |
| WDC WD10SPZX-22Z10T1 1TB                | 1         | 0.62%   |
| WDC WD10JPVX-60JC3T0 1TB                | 1         | 0.62%   |
| WDC WD10JPLX-00MBPT0 1TB                | 1         | 0.62%   |
| WDC WD10JPCX-24UE4T0 1TB                | 1         | 0.62%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB    | 1         | 0.62%   |
| Unknown SD02G  2GB                      | 1         | 0.62%   |
| Unknown SD/MMC/MS PRO 512GB             | 1         | 0.62%   |
| Unknown MMC Card  976MB                 | 1         | 0.62%   |
| Unknown MMC Card  4GB                   | 1         | 0.62%   |
| Unknown MMC Card  33GB                  | 1         | 0.62%   |
| Unknown MMC Card  2GB                   | 1         | 0.62%   |
| Unknown MMC Card  1GB                   | 1         | 0.62%   |
| Unknown 00000  4GB                      | 1         | 0.62%   |
| Union Memory UMIS RPJTJ256MED1OWX 256GB | 1         | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 22     | 38.78%  |
| WDC                 | 9         | 11     | 18.37%  |
| Toshiba             | 9         | 12     | 18.37%  |
| HGST                | 7         | 8      | 14.29%  |
| Hitachi             | 3         | 4      | 6.12%   |
| Unknown             | 1         | 1      | 2.04%   |
| Samsung Electronics | 1         | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 25     | 28.57%  |
| Kingston            | 8         | 9      | 12.7%   |
| SanDisk             | 7         | 8      | 11.11%  |
| Crucial             | 5         | 6      | 7.94%   |
| Toshiba             | 4         | 4      | 6.35%   |
| WDC                 | 3         | 4      | 4.76%   |
| Intel               | 3         | 3      | 4.76%   |
| SPCC                | 2         | 2      | 3.17%   |
| SK hynix            | 2         | 2      | 3.17%   |
| LITEON              | 2         | 3      | 3.17%   |
| XrayDisk            | 1         | 1      | 1.59%   |
| Transcend           | 1         | 2      | 1.59%   |
| SSD                 | 1         | 1      | 1.59%   |
| Plextor             | 1         | 1      | 1.59%   |
| LITEONIT            | 1         | 1      | 1.59%   |
| Lenovo              | 1         | 2      | 1.59%   |
| Biostar             | 1         | 1      | 1.59%   |
| Apple               | 1         | 1      | 1.59%   |
| A-DATA Technology   | 1         | 1      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 60        | 77     | 39.47%  |
| HDD     | 48        | 59     | 31.58%  |
| NVMe    | 32        | 36     | 21.05%  |
| MMC     | 9         | 11     | 5.92%   |
| Unknown | 3         | 3      | 1.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 97        | 135    | 69.29%  |
| NVMe | 32        | 36     | 22.86%  |
| MMC  | 9         | 11     | 6.43%   |
| SAS  | 2         | 4      | 1.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 69        | 88     | 63.89%  |
| 0.51-1.0   | 33        | 42     | 30.56%  |
| 1.01-2.0   | 5         | 5      | 4.63%   |
| 3.01-4.0   | 1         | 1      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 38        | 31.93%  |
| 101-250        | 29        | 24.37%  |
| 501-1000       | 21        | 17.65%  |
| 51-100         | 8         | 6.72%   |
| 1001-2000      | 7         | 5.88%   |
| 21-50          | 5         | 4.2%    |
| Unknown        | 4         | 3.36%   |
| 1-20           | 3         | 2.52%   |
| More than 3000 | 2         | 1.68%   |
| 2001-3000      | 2         | 1.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 42        | 33.6%   |
| 21-50     | 30        | 24%     |
| 51-100    | 20        | 16%     |
| 101-250   | 13        | 10.4%   |
| 251-500   | 7         | 5.6%    |
| 501-1000  | 6         | 4.8%    |
| Unknown   | 4         | 3.2%    |
| 1001-2000 | 3         | 2.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB         | 2         | 4      | 28.57%  |
| Seagate ST9750420AS 752GB      | 1         | 1      | 14.29%  |
| Seagate ST1000LM014-1EJ164 1TB | 1         | 1      | 14.29%  |
| SanDisk SSD PLUS 480GB         | 1         | 1      | 14.29%  |
| LITEON CV8-8E128-HP 128GB SSD  | 1         | 1      | 14.29%  |
| Hitachi HTS545032B9A302 320GB  | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 4      | 28.57%  |
| Seagate | 2         | 2      | 28.57%  |
| SanDisk | 1         | 1      | 14.29%  |
| LITEON  | 1         | 1      | 14.29%  |
| Hitachi | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 4      | 40%     |
| Seagate | 2         | 2      | 40%     |
| Hitachi | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 7      | 71.43%  |
| SSD  | 2         | 2      | 28.57%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-00A0RT0 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 79        | 128    | 61.72%  |
| Works    | 41        | 48     | 32.03%  |
| Malfunc  | 7         | 9      | 5.47%   |
| Failed   | 1         | 1      | 0.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 106       | 73.61%  |
| Samsung Electronics          | 10        | 6.94%   |
| SanDisk                      | 6         | 4.17%   |
| AMD                          | 6         | 4.17%   |
| Union Memory (Shenzhen)      | 3         | 2.08%   |
| SK hynix                     | 2         | 1.39%   |
| Micron Technology            | 2         | 1.39%   |
| KIOXIA                       | 2         | 1.39%   |
| Toshiba America Info Systems | 1         | 0.69%   |
| Silicon Motion               | 1         | 0.69%   |
| Shenzhen Longsys Electronics | 1         | 0.69%   |
| Micron/Crucial Technology    | 1         | 0.69%   |
| Marvell Technology Group     | 1         | 0.69%   |
| Lenovo                       | 1         | 0.69%   |
| ADATA Technology             | 1         | 0.69%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 17        | 11.49%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 14        | 9.46%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 7.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 6.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 4.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 4.05%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 4.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 6         | 4.05%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 4.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 3.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 2.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.03%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 2.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 2.03%   |
| Union Memory (Shenzhen) AM610 PCIe 3.0 x2 NVMe SSD 128GB, 256GB                | 2         | 1.35%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2         | 1.35%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 1.35%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 2         | 1.35%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 1.35%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.35%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 1.35%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 1.35%   |
| Union Memory (Shenzhen) AM611 PCIe 3.0 x2 NVMe SSD 256GB                       | 1         | 0.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.68%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.68%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.68%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 1         | 0.68%   |
| Shenzhen Longsys FORESEE P900 BGA NVMe SSD (DRAM-less)                         | 1         | 0.68%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 1         | 0.68%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                          | 1         | 0.68%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 1         | 0.68%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 1         | 0.68%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 1         | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.68%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 1         | 0.68%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 1         | 0.68%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 1         | 0.68%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 104       | 71.23%  |
| NVMe | 32        | 21.92%  |
| RAID | 8         | 5.48%   |
| IDE  | 2         | 1.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 113       | 94.96%  |
| AMD    | 6         | 5.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 3.36%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 3.36%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.52%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 2.52%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 2.52%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 2.52%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 2.52%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 2.52%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.68%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.68%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 1.68%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.68%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.68%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.68%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 1.68%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 2         | 1.68%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 2         | 1.68%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.68%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.68%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.84%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.84%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.84%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.84%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.84%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.84%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.84%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.84%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.84%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.84%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.84%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.84%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.84%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 0.84%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 1         | 0.84%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.84%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.84%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.84%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.84%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 43        | 36.13%  |
| Intel Core i7    | 42        | 35.29%  |
| Intel Core i3    | 12        | 10.08%  |
| Other            | 5         | 4.2%    |
| Intel Pentium    | 4         | 3.36%   |
| Intel Celeron    | 4         | 3.36%   |
| Intel Core 2 Duo | 2         | 1.68%   |
| AMD Ryzen 7      | 2         | 1.68%   |
| Intel Xeon       | 1         | 0.84%   |
| Intel Core i9    | 1         | 0.84%   |
| AMD Ryzen 5      | 1         | 0.84%   |
| AMD Ryzen 3      | 1         | 0.84%   |
| AMD A4           | 1         | 0.84%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 67        | 56.3%   |
| 4      | 43        | 36.13%  |
| 6      | 8         | 6.72%   |
| 8      | 1         | 0.84%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 119       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 104       | 87.39%  |
| 1      | 15        | 12.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 118       | 98.33%  |
| Unknown        | 2         | 1.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 13        | 10.83%  |
| 0x40651    | 11        | 9.17%   |
| 0x206a7    | 11        | 9.17%   |
| 0x406e3    | 10        | 8.33%   |
| 0x306d4    | 9         | 7.5%    |
| 0x806ea    | 8         | 6.67%   |
| 0x306c3    | 6         | 5%      |
| 0x806ec    | 5         | 4.17%   |
| 0x20655    | 5         | 4.17%   |
| 0xa0652    | 4         | 3.33%   |
| 0x906ea    | 4         | 3.33%   |
| 0x806c1    | 4         | 3.33%   |
| 0x506e3    | 4         | 3.33%   |
| Unknown    | 4         | 3.33%   |
| 0x806e9    | 3         | 2.5%    |
| 0x706e5    | 3         | 2.5%    |
| 0x906ed    | 2         | 1.67%   |
| 0x906e9    | 2         | 1.67%   |
| 0x30678    | 2         | 1.67%   |
| 0x106e5    | 2         | 1.67%   |
| 0x06006705 | 2         | 1.67%   |
| 0x406c3    | 1         | 0.83%   |
| 0x20652    | 1         | 0.83%   |
| 0x1067a    | 1         | 0.83%   |
| 0x10676    | 1         | 0.83%   |
| 0x08108109 | 1         | 0.83%   |
| 0x08108102 | 1         | 0.83%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 25        | 21.01%  |
| Haswell     | 17        | 14.29%  |
| Skylake     | 14        | 11.76%  |
| IvyBridge   | 13        | 10.92%  |
| SandyBridge | 11        | 9.24%   |
| Broadwell   | 9         | 7.56%   |
| Westmere    | 6         | 5.04%   |
| TigerLake   | 4         | 3.36%   |
| CometLake   | 4         | 3.36%   |
| Zen+        | 3         | 2.52%   |
| Silvermont  | 3         | 2.52%   |
| IceLake     | 3         | 2.52%   |
| Penryn      | 2         | 1.68%   |
| Nehalem     | 2         | 1.68%   |
| Excavator   | 2         | 1.68%   |
| Zen 2       | 1         | 0.84%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 102       | 63.75%  |
| Nvidia | 41        | 25.63%  |
| AMD    | 17        | 10.63%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 12        | 7.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 10        | 6.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 10        | 6.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 10        | 6.25%   |
| Intel UHD Graphics 620                                                                | 9         | 5.63%   |
| Intel HD Graphics 5500                                                                | 7         | 4.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 5         | 3.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 4         | 2.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 4         | 2.5%    |
| Intel Core Processor Integrated Graphics Controller                                   | 4         | 2.5%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 4         | 2.5%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 2.5%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 4         | 2.5%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 3         | 1.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 3         | 1.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 3         | 1.88%   |
| Intel HD Graphics 620                                                                 | 3         | 1.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 3         | 1.88%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 2         | 1.25%   |
| Nvidia GM108M [GeForce 840M]                                                          | 2         | 1.25%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 2         | 1.25%   |
| Nvidia GK107GLM [Quadro K1100M]                                                       | 2         | 1.25%   |
| Intel HD Graphics 630                                                                 | 2         | 1.25%   |
| Intel HD Graphics 530                                                                 | 2         | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 2         | 1.25%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 2         | 1.25%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                          | 2         | 1.25%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                 | 1         | 0.63%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                               | 1         | 0.63%   |
| Nvidia GT218M [GeForce 310M]                                                          | 1         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 0.63%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 0.63%   |
| Nvidia GP107GLM [Quadro P620]                                                         | 1         | 0.63%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                               | 1         | 0.63%   |
| Nvidia GM204M [GeForce GTX 980M]                                                      | 1         | 0.63%   |
| Nvidia GM108M [GeForce MX130]                                                         | 1         | 0.63%   |
| Nvidia GM108M [GeForce 940M]                                                          | 1         | 0.63%   |
| Nvidia GM107M [GeForce GTX 850M]                                                      | 1         | 0.63%   |
| Nvidia GM107GLM [Quadro M2000M]                                                       | 1         | 0.63%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                 | 1         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 62        | 52.1%   |
| Intel + Nvidia | 32        | 26.89%  |
| 1 x Nvidia     | 8         | 6.72%   |
| Intel + AMD    | 8         | 6.72%   |
| 1 x AMD        | 8         | 6.72%   |
| AMD + Nvidia   | 1         | 0.84%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 113       | 94.96%  |
| Proprietary | 3         | 2.52%   |
| Unknown     | 3         | 2.52%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 58.82%  |
| 1.01-2.0   | 23        | 19.33%  |
| 3.01-4.0   | 14        | 11.76%  |
| 0.51-1.0   | 6         | 5.04%   |
| 0.01-0.5   | 5         | 4.2%    |
| 7.01-8.0   | 1         | 0.84%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 28        | 20%     |
| Chimei Innolux          | 24        | 17.14%  |
| LG Display              | 19        | 13.57%  |
| Samsung Electronics     | 17        | 12.14%  |
| BOE                     | 17        | 12.14%  |
| Dell                    | 7         | 5%      |
| Panasonic               | 4         | 2.86%   |
| Sharp                   | 3         | 2.14%   |
| Lenovo                  | 3         | 2.14%   |
| Acer                    | 3         | 2.14%   |
| PANDA                   | 2         | 1.43%   |
| Hewlett-Packard         | 2         | 1.43%   |
| Goldstar                | 2         | 1.43%   |
| Vizio                   | 1         | 0.71%   |
| Philips                 | 1         | 0.71%   |
| Onkyo                   | 1         | 0.71%   |
| MSI                     | 1         | 0.71%   |
| InfoVision              | 1         | 0.71%   |
| Gateway                 | 1         | 0.71%   |
| Chi Mei Optoelectronics | 1         | 0.71%   |
| Apple                   | 1         | 0.71%   |
| AOC                     | 1         | 0.71%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch              | 3         | 2.11%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.41%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 2         | 1.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.41%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 1.41%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 2         | 1.41%   |
| Vizio M220VA VIZ0070 1920x1080 476x268mm 21.5-inch                    | 1         | 0.7%    |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.7%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.7%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.7%    |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 1         | 0.7%    |
| Samsung Electronics SMBX2450 SAM0721 1920x1080 531x299mm 24.0-inch    | 1         | 0.7%    |
| Samsung Electronics S22B420 SAM0979 1680x1050 473x291mm 21.9-inch     | 1         | 0.7%    |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3848 1920x1200 367x230mm 17.1-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3646 1680x1050 330x210mm 15.4-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3147 1600x900 332x187mm 15.0-inch  | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC834E 1920x1080 309x174mm 14.0-inch | 1         | 0.7%    |
| Samsung Electronics LCD Monitor SDC364D 1920x1080 309x174mm 14.0-inch | 1         | 0.7%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.7%    |
| Philips PHL 278E9Q PHLC17F 1920x1080 598x336mm 27.0-inch              | 1         | 0.7%    |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.7%    |
| PANDA LCD Monitor NCP002A 1920x1080 344x194mm 15.5-inch               | 1         | 0.7%    |
| Panasonic TV MEIC122 1280x720 697x392mm 31.5-inch                     | 1         | 0.7%    |
| Onkyo AV Receiver ONK1151 1280x720 609x347mm 27.6-inch                | 1         | 0.7%    |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch               | 1         | 0.7%    |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD061C 1920x1080 294x165mm 13.3-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD05D5 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |
| LG Display LCD Monitor LGD05D1 1920x1080 344x194mm 15.5-inch          | 1         | 0.7%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 62        | 46.97%  |
| 1366x768 (WXGA)    | 37        | 28.03%  |
| 1600x900 (HD+)     | 11        | 8.33%   |
| 3840x2160 (4K)     | 6         | 4.55%   |
| 1680x1050 (WSXGA+) | 4         | 3.03%   |
| 2560x1600          | 2         | 1.52%   |
| 2560x1440 (QHD)    | 2         | 1.52%   |
| 1920x1200 (WUXGA)  | 2         | 1.52%   |
| 1280x800 (WXGA)    | 2         | 1.52%   |
| 1280x1024 (SXGA)   | 2         | 1.52%   |
| 3440x1440          | 1         | 0.76%   |
| 1280x720 (HD)      | 1         | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 59        | 41.84%  |
| 14      | 17        | 12.06%  |
| 13      | 17        | 12.06%  |
| 17      | 13        | 9.22%   |
| 24      | 6         | 4.26%   |
| 23      | 5         | 3.55%   |
| 12      | 5         | 3.55%   |
| 21      | 4         | 2.84%   |
| 27      | 3         | 2.13%   |
| 11      | 2         | 1.42%   |
| 42      | 1         | 0.71%   |
| 40      | 1         | 0.71%   |
| 34      | 1         | 0.71%   |
| 32      | 1         | 0.71%   |
| 31      | 1         | 0.71%   |
| 29      | 1         | 0.71%   |
| 28      | 1         | 0.71%   |
| 20      | 1         | 0.71%   |
| 16      | 1         | 0.71%   |
| Unknown | 1         | 0.71%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 88        | 63.31%  |
| 351-400     | 14        | 10.07%  |
| 501-600     | 11        | 7.91%   |
| 201-300     | 10        | 7.19%   |
| 401-500     | 6         | 4.32%   |
| 601-700     | 5         | 3.6%    |
| 701-800     | 2         | 1.44%   |
| 801-900     | 1         | 0.72%   |
| 901-1000    | 1         | 0.72%   |
| Unknown     | 1         | 0.72%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 109       | 89.34%  |
| 16/10   | 8         | 6.56%   |
| 5/4     | 2         | 1.64%   |
| 3/2     | 1         | 0.82%   |
| 21/9    | 1         | 0.82%   |
| Unknown | 1         | 0.82%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 58        | 40.85%  |
| 81-90          | 32        | 22.54%  |
| 201-250        | 13        | 9.15%   |
| 121-130        | 11        | 7.75%   |
| 61-70          | 5         | 3.52%   |
| 351-500        | 5         | 3.52%   |
| 301-350        | 3         | 2.11%   |
| 71-80          | 2         | 1.41%   |
| 51-60          | 2         | 1.41%   |
| 251-300        | 2         | 1.41%   |
| 151-200        | 2         | 1.41%   |
| 141-150        | 2         | 1.41%   |
| 501-1000       | 2         | 1.41%   |
| 131-140        | 1         | 0.7%    |
| 91-100         | 1         | 0.7%    |
| Unknown        | 1         | 0.7%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 65        | 47.45%  |
| 101-120       | 38        | 27.74%  |
| 51-100        | 24        | 17.52%  |
| More than 240 | 4         | 2.92%   |
| 161-240       | 4         | 2.92%   |
| 1-50          | 1         | 0.73%   |
| Unknown       | 1         | 0.73%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 97        | 78.86%  |
| 2     | 21        | 17.07%  |
| 3     | 3         | 2.44%   |
| 0     | 2         | 1.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 73        | 39.89%  |
| Realtek Semiconductor             | 60        | 32.79%  |
| Qualcomm Atheros                  | 27        | 14.75%  |
| Broadcom                          | 7         | 3.83%   |
| Ralink                            | 2         | 1.09%   |
| Dell                              | 2         | 1.09%   |
| Broadcom Limited                  | 2         | 1.09%   |
| Xiaomi                            | 1         | 0.55%   |
| Sierra Wireless                   | 1         | 0.55%   |
| Samsung Electronics               | 1         | 0.55%   |
| Ralink Technology                 | 1         | 0.55%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.55%   |
| Marvell Technology Group          | 1         | 0.55%   |
| Ericsson Business Mobile Networks | 1         | 0.55%   |
| DisplayLink                       | 1         | 0.55%   |
| D-Link                            | 1         | 0.55%   |
| ASIX Electronics                  | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 19.49%  |
| Intel Wireless 7260                                               | 11        | 4.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 3.81%   |
| Intel Wireless 8260                                               | 7         | 2.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 2.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.12%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.12%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.12%   |
| Intel Wireless 7265                                               | 4         | 1.69%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.69%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.69%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.69%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.27%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 1.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 1.27%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 1.27%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.85%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.85%   |
| Intel Wireless-AC 9260                                            | 2         | 0.85%   |
| Intel Wireless 3165                                               | 2         | 0.85%   |
| Intel Wireless 3160                                               | 2         | 0.85%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.85%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.85%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.85%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.85%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.85%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.85%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.85%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 70        | 56.45%  |
| Qualcomm Atheros      | 23        | 18.55%  |
| Realtek Semiconductor | 17        | 13.71%  |
| Broadcom              | 5         | 4.03%   |
| Ralink                | 2         | 1.61%   |
| Dell                  | 2         | 1.61%   |
| Broadcom Limited      | 2         | 1.61%   |
| Sierra Wireless       | 1         | 0.81%   |
| Ralink Technology     | 1         | 0.81%   |
| D-Link                | 1         | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 11        | 8.87%   |
| Intel Wireless 8260                                            | 7         | 5.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 4.84%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 4.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 4.03%   |
| Intel Wireless 8265 / 8275                                     | 5         | 4.03%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 4.03%   |
| Intel Wireless 7265                                            | 4         | 3.23%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 3.23%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 3.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.42%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 2.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 2.42%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 2.42%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 2.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 2.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.61%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 1.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.61%   |
| Intel Wireless-AC 9260                                         | 2         | 1.61%   |
| Intel Wireless 3165                                            | 2         | 1.61%   |
| Intel Wireless 3160                                            | 2         | 1.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.61%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 1.61%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.61%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 0.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.81%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.81%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.81%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.81%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.81%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.81%   |
| Intel WiFi Link 5100                                           | 1         | 0.81%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 56        | 51.38%  |
| Intel                         | 38        | 34.86%  |
| Qualcomm Atheros              | 7         | 6.42%   |
| Broadcom                      | 2         | 1.83%   |
| Xiaomi                        | 1         | 0.92%   |
| Samsung Electronics           | 1         | 0.92%   |
| OnePlus Technology (Shenzhen) | 1         | 0.92%   |
| Marvell Technology Group      | 1         | 0.92%   |
| DisplayLink                   | 1         | 0.92%   |
| ASIX Electronics              | 1         | 0.92%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 41.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 8.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 5.41%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 3.6%    |
| Intel Ethernet Connection I218-LM                                 | 4         | 3.6%    |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.7%    |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.8%    |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.8%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.8%    |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.8%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.8%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.8%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.9%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.9%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.9%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.9%    |
| OnePlus (Shenzhen) Android                                        | 1         | 0.9%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.9%    |
| Intel Ethernet Connection I219-V                                  | 1         | 0.9%    |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.9%    |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.9%    |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.9%    |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.9%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.9%    |
| DisplayLink USB Port Replicator PR8.1                             | 1         | 0.9%    |
| ASIX AX88772                                                      | 1         | 0.9%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 118       | 52.68%  |
| Ethernet | 105       | 46.88%  |
| Modem    | 1         | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 75.38%  |
| Ethernet | 32        | 24.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 101       | 84.87%  |
| 1     | 18        | 15.13%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 103       | 86.55%  |
| Yes  | 16        | 13.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 51        | 52.58%  |
| Qualcomm Atheros Communications | 17        | 17.53%  |
| Realtek Semiconductor           | 13        | 13.4%   |
| Broadcom                        | 5         | 5.15%   |
| IMC Networks                    | 2         | 2.06%   |
| Hewlett-Packard                 | 2         | 2.06%   |
| Cambridge Silicon Radio         | 2         | 2.06%   |
| Toshiba                         | 1         | 1.03%   |
| Ralink                          | 1         | 1.03%   |
| Lite-On Technology              | 1         | 1.03%   |
| Foxconn / Hon Hai               | 1         | 1.03%   |
| Apple                           | 1         | 1.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 29        | 29.9%   |
| Realtek Bluetooth Radio                             | 9         | 9.28%   |
| Intel Bluetooth Device                              | 7         | 7.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 6.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 5.15%   |
| Intel AX200 Bluetooth                               | 5         | 5.15%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 4.12%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 3.09%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 2.06%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.06%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.06%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 2.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.06%   |
| Toshiba Bluetooth Radio                             | 1         | 1.03%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.03%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.03%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.03%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.03%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.03%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.03%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.03%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 1.03%   |
| IMC Networks Bluetooth Device                       | 1         | 1.03%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.03%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.03%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.03%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1         | 1.03%   |
| Broadcom BCM20702A0                                 | 1         | 1.03%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.03%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.03%   |
| Apple Bluetooth Host Controller                     | 1         | 1.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 112       | 75.17%  |
| Nvidia                   | 20        | 13.42%  |
| AMD                      | 9         | 6.04%   |
| Logitech                 | 2         | 1.34%   |
| GN Netcom                | 2         | 1.34%   |
| Tenx Technology          | 1         | 0.67%   |
| Plantronics              | 1         | 0.67%   |
| Kingston Technology      | 1         | 0.67%   |
| Asahi Kasei Microsystems | 1         | 0.67%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 21        | 11.8%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15        | 8.43%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 6.18%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 5.62%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 9         | 5.06%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 5.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 5.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 4.49%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 3.37%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 3.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 3.37%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 2.25%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 2.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.25%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 2.25%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.69%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.69%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.12%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 1.12%   |
| AMD High Definition Audio Controller                                       | 2         | 1.12%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.12%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.56%   |
| Plantronics Calisto 800 Series                                             | 1         | 0.56%   |
| Plantronics Blackwire C210                                                 | 1         | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.56%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.56%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.56%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.56%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.56%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.56%   |
| Logitech Headset H340                                                      | 1         | 0.56%   |
| Logitech Clear Chat Comfort USB Headset                                    | 1         | 0.56%   |
| Kingston Technology HyperX 7.1 Audio                                       | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 16        | 27.12%  |
| Samsung Electronics | 15        | 25.42%  |
| Kingston            | 11        | 18.64%  |
| Micron Technology   | 4         | 6.78%   |
| Unknown             | 3         | 5.08%   |
| A-DATA Technology   | 3         | 5.08%   |
| Elpida              | 2         | 3.39%   |
| Ramaxel Technology  | 1         | 1.69%   |
| Nanya Technology    | 1         | 1.69%   |
| Crucial             | 1         | 1.69%   |
| Corsair             | 1         | 1.69%   |
| Apacer              | 1         | 1.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 3.23%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s         | 2         | 3.23%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 1         | 1.61%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                     | 1         | 1.61%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                 | 1         | 1.61%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                   | 1         | 1.61%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                | 1         | 1.61%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                | 1         | 1.61%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                  | 1         | 1.61%   |
| SK hynix RAM HMT851S6AMR6R-PB N0 4GB Chip DDR3 1600MT/s        | 1         | 1.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.61%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s      | 1         | 1.61%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 1.61%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s         | 1         | 1.61%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM 1333MT/s              | 1         | 1.61%   |
| SK hynix RAM HMT125S6AFP8C-G7 2GB SODIMM 1066MT/s              | 1         | 1.61%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s   | 1         | 1.61%   |
| SK hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s         | 1         | 1.61%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s     | 1         | 1.61%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s         | 1         | 1.61%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s     | 1         | 1.61%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s               | 1         | 1.61%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.61%   |
| Samsung RAM M471B5273CM0-CH9 4GB SODIMM 1334MT/s               | 1         | 1.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 1         | 1.61%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s          | 1         | 1.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 1         | 1.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 1         | 1.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s    | 1         | 1.61%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s          | 1         | 1.61%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s       | 1         | 1.61%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s          | 1         | 1.61%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s      | 1         | 1.61%   |
| Nanya RAM NT2GC64B8HC0NS-CG 2GB SODIMM DDR3 1334MT/s           | 1         | 1.61%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s  | 1         | 1.61%   |
| Micron RAM 8ATF1G64HZ-2G6D1 8GB SODIMM DDR4 2667MT/s           | 1         | 1.61%   |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s | 1         | 1.61%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 1         | 1.61%   |
| Kingston RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 1.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 25        | 49.02%  |
| DDR4   | 22        | 43.14%  |
| LPDDR4 | 2         | 3.92%   |
| LPDDR3 | 1         | 1.96%   |
| DDR2   | 1         | 1.96%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 45        | 88.24%  |
| Row Of Chips | 5         | 9.8%    |
| Chip         | 1         | 1.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 23        | 41.82%  |
| 8192  | 17        | 30.91%  |
| 16384 | 9         | 16.36%  |
| 2048  | 6         | 10.91%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 16        | 29.63%  |
| 2667  | 14        | 25.93%  |
| 1333  | 5         | 9.26%   |
| 2133  | 4         | 7.41%   |
| 1334  | 4         | 7.41%   |
| 2400  | 3         | 5.56%   |
| 4267  | 2         | 3.7%    |
| 3266  | 1         | 1.85%   |
| 3200  | 1         | 1.85%   |
| 1866  | 1         | 1.85%   |
| 1067  | 1         | 1.85%   |
| 1066  | 1         | 1.85%   |
| 667   | 1         | 1.85%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 34        | 31.48%  |
| Microdia                               | 14        | 12.96%  |
| Bison Electronics                      | 10        | 9.26%   |
| Realtek Semiconductor                  | 7         | 6.48%   |
| Lite-On Technology                     | 7         | 6.48%   |
| IMC Networks                           | 7         | 6.48%   |
| Sunplus Innovation Technology          | 6         | 5.56%   |
| Quanta                                 | 4         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.7%    |
| Syntek                                 | 2         | 1.85%   |
| Suyin                                  | 2         | 1.85%   |
| Silicon Motion                         | 2         | 1.85%   |
| Microsoft                              | 2         | 1.85%   |
| Acer                                   | 2         | 1.85%   |
| Sunplus Technology                     | 1         | 0.93%   |
| Samsung Electronics                    | 1         | 0.93%   |
| Logitech                               | 1         | 0.93%   |
| Intel                                  | 1         | 0.93%   |
| Alcor Micro                            | 1         | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 7         | 6.48%   |
| Microdia Integrated_Webcam_HD           | 4         | 3.7%    |
| Lite-On Integrated Camera               | 3         | 2.78%   |
| Lite-On HP HD Camera                    | 3         | 2.78%   |
| IMC Networks USB2.0 HD UVC WebCam       | 3         | 2.78%   |
| IMC Networks Integrated Camera          | 3         | 2.78%   |
| Chicony USB2.0 VGA UVC WebCam           | 3         | 2.78%   |
| Chicony Integrated Camera (1280x720@30) | 3         | 2.78%   |
| Chicony HP TrueVision HD                | 3         | 2.78%   |
| Chicony HP HD Camera                    | 3         | 2.78%   |
| Chicony HD WebCam                       | 3         | 2.78%   |
| Bison Lenovo EasyCamera                 | 3         | 2.78%   |
| Sunplus Integrated_Webcam_HD            | 2         | 1.85%   |
| Quanta HP TrueVision HD Camera          | 2         | 1.85%   |
| Microdia Laptop_Integrated_Webcam_HD    | 2         | 1.85%   |
| Microdia Laptop_Integrated_Webcam_2M    | 2         | 1.85%   |
| Chicony HP Webcam [2 MP Macro]          | 2         | 1.85%   |
| Chicony HP HD Webcam                    | 2         | 1.85%   |
| Acer Integrated Camera                  | 2         | 1.85%   |
| Syntek USB2.0 UVC PC Camera             | 1         | 0.93%   |
| Syntek Lenovo EasyCamera                | 1         | 0.93%   |
| Suyin Sony Visual Communication Camera  | 1         | 0.93%   |
| Suyin Integrated_Webcam_HD              | 1         | 0.93%   |
| Sunplus 1.3M WebCam                     | 1         | 0.93%   |
| Sunplus USB Video Device                | 1         | 0.93%   |
| Sunplus Integrated_Webcam_FHD           | 1         | 0.93%   |
| Sunplus HD WebCam                       | 1         | 0.93%   |
| Sunplus ASUS USB2.0 Webcam              | 1         | 0.93%   |
| Silicon Motion WebCam SC-13HDL11431N    | 1         | 0.93%   |
| Silicon Motion ATIV VGA Camera          | 1         | 0.93%   |
| Samsung Galaxy series, misc. (MTP mode) | 1         | 0.93%   |
| Realtek USB Camera                      | 1         | 0.93%   |
| Realtek Rear Camera                     | 1         | 0.93%   |
| Realtek Integrated Webcam_HD            | 1         | 0.93%   |
| Realtek Integrated Webcam               | 1         | 0.93%   |
| Realtek HD Webcam - Realtek             | 1         | 0.93%   |
| Realtek HD Webcam                       | 1         | 0.93%   |
| Realtek EasyCamera                      | 1         | 0.93%   |
| Quanta HD Webcam                        | 1         | 0.93%   |
| Quanta HD User Facing                   | 1         | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 19        | 55.88%  |
| Synaptics                  | 7         | 20.59%  |
| Shenzhen Goodix Technology | 3         | 8.82%   |
| Upek                       | 2         | 5.88%   |
| Elan Microelectronics      | 2         | 5.88%   |
| AuthenTec                  | 1         | 2.94%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 7         | 20.59%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 4         | 11.76%  |
| Validity Sensors VFS451 Fingerprint Reader             | 3         | 8.82%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 2         | 5.88%   |
| Validity Sensors VFS491                                | 2         | 5.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 5.88%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 2         | 5.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 5.88%   |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 5.88%   |
| Elan ELAN:Fingerprint                                  | 2         | 5.88%   |
| Validity Sensors Synaptics WBDI                        | 1         | 2.94%   |
| Synaptics UWP WBDI Device                              | 1         | 2.94%   |
| Synaptics  WBDI                                        | 1         | 2.94%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 2.94%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 2.94%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 2.94%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 62.5%   |
| Upek        | 1         | 12.5%   |
| O2 Micro    | 1         | 12.5%   |
| Alcor Micro | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 2         | 25%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 12.5%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 12.5%   |
| Broadcom 5880                                                                | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 60        | 50%     |
| 1     | 53        | 44.17%  |
| 2     | 5         | 4.17%   |
| 6     | 1         | 0.83%   |
| 3     | 1         | 0.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 34        | 48.57%  |
| Graphics card            | 13        | 18.57%  |
| Net/wireless             | 6         | 8.57%   |
| Chipcard                 | 6         | 8.57%   |
| Multimedia controller    | 4         | 5.71%   |
| Bluetooth                | 2         | 2.86%   |
| Storage                  | 1         | 1.43%   |
| Sound                    | 1         | 1.43%   |
| Net/ethernet             | 1         | 1.43%   |
| Communication controller | 1         | 1.43%   |
| Camera                   | 1         | 1.43%   |

