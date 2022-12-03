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

Total: 168

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| 4.18.0-147.8.1.el8_1.x86_64  | 11        | 8.66%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 9         | 7.09%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 8         | 6.3%    |
| 4.18.0-80.11.2.el8_0.x86_64  | 7         | 5.51%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 7         | 5.51%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 6         | 4.72%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 5         | 3.94%   |
| 4.18.0-193.14.2.el8_2.x86_64 | 5         | 3.94%   |
| 4.18.0-305.3.1.el8.x86_64    | 4         | 3.15%   |
| 4.18.0-294.el8.x86_64        | 4         | 3.15%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 4         | 3.15%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 4         | 3.15%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 3         | 2.36%   |
| 4.18.0-305.17.1.el8_4.x86_64 | 3         | 2.36%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 3         | 2.36%   |
| 4.18.0-277.el8.x86_64        | 3         | 2.36%   |
| 4.18.0-193.el8.x86_64        | 3         | 2.36%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 3         | 2.36%   |
| 4.18.0-147.6.el8.x86_64      | 3         | 2.36%   |
| 5.15.11-1.el8.elrepo.x86_64  | 2         | 1.57%   |
| 4.18.0-80.el8.x86_64         | 2         | 1.57%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 2         | 1.57%   |
| 4.18.0-301.1.el8.x86_64      | 2         | 1.57%   |
| 4.18.0-240.el8.x86_64        | 2         | 1.57%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 2         | 1.57%   |
| 4.18.0-147.el8.x86_64        | 2         | 1.57%   |
| 5.9.12-1.el8.elrepo.x86_64   | 1         | 0.79%   |
| 5.9.1-1.el8.elrepo.x86_64    | 1         | 0.79%   |
| 5.8.11-1.el8.elrepo.x86_64   | 1         | 0.79%   |
| 5.13.7-1.el8.elrepo.x86_64   | 1         | 0.79%   |
| 4.18.0-80.7.1.el8_0.x86_64   | 1         | 0.79%   |
| 4.18.0-408.el8.x86_64        | 1         | 0.79%   |
| 4.18.0-365.el8.x86_64        | 1         | 0.79%   |
| 4.18.0-358.el8.x86_64        | 1         | 0.79%   |
| 4.18.0-348.el8.x86_64        | 1         | 0.79%   |
| 4.18.0-338.el8.x86_64        | 1         | 0.79%   |
| 4.18.0-315.el8.x86_64        | 1         | 0.79%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 1         | 0.79%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 1         | 0.79%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 1         | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 109       | 94.78%  |
| 5.15.11 | 2         | 1.74%   |
| 5.9.12  | 1         | 0.87%   |
| 5.9.1   | 1         | 0.87%   |
| 5.8.11  | 1         | 0.87%   |
| 5.13.7  | 1         | 0.87%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 109       | 94.78%  |
| 5.9     | 2         | 1.74%   |
| 5.15    | 2         | 1.74%   |
| 5.8     | 1         | 0.87%   |
| 5.13    | 1         | 0.87%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 115       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 104       | 88.89%  |
| GNOME Classic | 4         | 3.42%   |
| Unknown       | 3         | 2.56%   |
| XFCE          | 2         | 1.71%   |
| MATE          | 2         | 1.71%   |
| KDE5          | 1         | 0.85%   |
| KDE           | 1         | 0.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 75        | 61.48%  |
| X11     | 43        | 35.25%  |
| Unknown | 3         | 2.46%   |
| Web     | 1         | 0.82%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 69        | 58.47%  |
| GDM     | 47        | 39.83%  |
| TDM     | 1         | 0.85%   |
| LightDM | 1         | 0.85%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 61        | 52.14%  |
| Unknown | 10        | 8.55%   |
| en_GB   | 9         | 7.69%   |
| de_DE   | 7         | 5.98%   |
| pt_BR   | 6         | 5.13%   |
| ru_RU   | 4         | 3.42%   |
| fr_FR   | 4         | 3.42%   |
| en_CA   | 3         | 2.56%   |
| nb_NO   | 2         | 1.71%   |
| ko_KR   | 2         | 1.71%   |
| en_IN   | 2         | 1.71%   |
| zh_CN   | 1         | 0.85%   |
| it_IT   | 1         | 0.85%   |
| es_PE   | 1         | 0.85%   |
| es_MX   | 1         | 0.85%   |
| es_AR   | 1         | 0.85%   |
| en_IE   | 1         | 0.85%   |
| da_DK   | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 75        | 64.66%  |
| BIOS | 41        | 35.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 103       | 88.03%  |
| Ext4    | 10        | 8.55%   |
| Unknown | 4         | 3.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 70        | 59.83%  |
| GPT     | 35        | 29.91%  |
| MBR     | 12        | 10.26%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 105       | 91.3%   |
| Yes       | 10        | 8.7%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 99        | 85.34%  |
| Yes       | 17        | 14.66%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 32        | 27.83%  |
| Hewlett-Packard        | 25        | 21.74%  |
| Dell                   | 20        | 17.39%  |
| ASUSTek Computer       | 9         | 7.83%   |
| Acer                   | 8         | 6.96%   |
| Sony                   | 4         | 3.48%   |
| Samsung Electronics    | 4         | 3.48%   |
| MSI                    | 2         | 1.74%   |
| Toshiba                | 1         | 0.87%   |
| Timi                   | 1         | 0.87%   |
| RM Education           | 1         | 0.87%   |
| Medion                 | 1         | 0.87%   |
| LG Electronics         | 1         | 0.87%   |
| Gigabyte Technology    | 1         | 0.87%   |
| Fujitsu                | 1         | 0.87%   |
| COPELION INTERNATIONAL | 1         | 0.87%   |
| Clevo                  | 1         | 0.87%   |
| Apple                  | 1         | 0.87%   |
| Unknown                | 1         | 0.87%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Lenovo Z50-70 20354                               | 2         | 1.74%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK             | 2         | 1.74%   |
| HP ProBook 450 G5                                 | 2         | 1.74%   |
| HP Notebook                                       | 2         | 1.74%   |
| Dell Studio 1747                                  | 2         | 1.74%   |
| Dell Latitude E5470                               | 2         | 1.74%   |
| Toshiba Satellite L15W-B                          | 1         | 0.87%   |
| Timi TM1709                                       | 1         | 0.87%   |
| Sony VPCEH26EN                                    | 1         | 0.87%   |
| Sony VPCEH15FX                                    | 1         | 0.87%   |
| Sony VPCEG15FB                                    | 1         | 0.87%   |
| Sony SVT11215CGW                                  | 1         | 0.87%   |
| Samsung R560                                      | 1         | 0.87%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B               | 1         | 0.87%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.87%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.87%   |
| RM Education RM                                   | 1         | 0.87%   |
| MSI GP75 Leopard 10SFK                            | 1         | 0.87%   |
| MSI GE73VR 7RF                                    | 1         | 0.87%   |
| Medion P6622                                      | 1         | 0.87%   |
| LG Z435-GE40K                                     | 1         | 0.87%   |
| Lenovo V330-15IKB 81AX                            | 1         | 0.87%   |
| Lenovo ThinkPad X240 20AMS7XW00                   | 1         | 0.87%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00          | 1         | 0.87%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A7CT01WW          | 1         | 0.87%   |
| Lenovo ThinkPad W540 20BHS20700                   | 1         | 0.87%   |
| Lenovo ThinkPad W540 20BG001KUK                   | 1         | 0.87%   |
| Lenovo ThinkPad T500 2242CTO                      | 1         | 0.87%   |
| Lenovo ThinkPad T490s 20NYS02900                  | 1         | 0.87%   |
| Lenovo ThinkPad T480s 20L8002WMX                  | 1         | 0.87%   |
| Lenovo ThinkPad T460p 20FXS02200                  | 1         | 0.87%   |
| Lenovo ThinkPad T440 20B7004JUS                   | 1         | 0.87%   |
| Lenovo ThinkPad T430s 2356CZ4                     | 1         | 0.87%   |
| Lenovo ThinkPad T420 4238AB9                      | 1         | 0.87%   |
| Lenovo ThinkPad T14s Gen 2i 20WNS5JQ00            | 1         | 0.87%   |
| Lenovo ThinkPad P51 W10DG 20MNS08X00              | 1         | 0.87%   |
| Lenovo ThinkPad P50 20EN001PUS                    | 1         | 0.87%   |
| Lenovo ThinkPad E595 20NF0000GE                   | 1         | 0.87%   |
| Lenovo ThinkPad E590 20NBS03S00                   | 1         | 0.87%   |
| Lenovo ThinkPad E580 20KS001JRT                   | 1         | 0.87%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 20        | 17.39%  |
| HP EliteBook                  | 9         | 7.83%   |
| Dell Latitude                 | 9         | 7.83%   |
| Lenovo IdeaPad                | 7         | 6.09%   |
| HP ProBook                    | 6         | 5.22%   |
| Acer Aspire                   | 5         | 4.35%   |
| HP ZBook                      | 3         | 2.61%   |
| HP Laptop                     | 3         | 2.61%   |
| Dell XPS                      | 3         | 2.61%   |
| Dell Inspiron                 | 3         | 2.61%   |
| Lenovo Z50-70                 | 2         | 1.74%   |
| HP Notebook                   | 2         | 1.74%   |
| Dell Studio                   | 2         | 1.74%   |
| Dell Precision                | 2         | 1.74%   |
| ASUS VivoBook                 | 2         | 1.74%   |
| Toshiba Satellite             | 1         | 0.87%   |
| Timi TM1709                   | 1         | 0.87%   |
| Sony VPCEH26EN                | 1         | 0.87%   |
| Sony VPCEH15FX                | 1         | 0.87%   |
| Sony VPCEG15FB                | 1         | 0.87%   |
| Sony SVT11215CGW              | 1         | 0.87%   |
| Samsung R560                  | 1         | 0.87%   |
| Samsung 700Z3A                | 1         | 0.87%   |
| Samsung 500R4K                | 1         | 0.87%   |
| Samsung 270E5J                | 1         | 0.87%   |
| RM Education RM               | 1         | 0.87%   |
| MSI GP75                      | 1         | 0.87%   |
| MSI GE73VR                    | 1         | 0.87%   |
| Medion P6622                  | 1         | 0.87%   |
| LG Z435-GE40K                 | 1         | 0.87%   |
| Lenovo V330-15IKB             | 1         | 0.87%   |
| Lenovo G70-70                 | 1         | 0.87%   |
| Lenovo B50-70                 | 1         | 0.87%   |
| HP Pavilion                   | 1         | 0.87%   |
| HP NOTEBOOKE                  | 1         | 0.87%   |
| Gigabyte P35V3                | 1         | 0.87%   |
| Fujitsu LIFEBOOK              | 1         | 0.87%   |
| Dell G3                       | 1         | 0.87%   |
| COPELION INTERNATIONAL QX-350 | 1         | 0.87%   |
| Clevo P15xEMx                 | 1         | 0.87%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 16        | 13.91%  |
| 2012 | 16        | 13.91%  |
| 2016 | 13        | 11.3%   |
| 2014 | 12        | 10.43%  |
| 2020 | 9         | 7.83%   |
| 2018 | 9         | 7.83%   |
| 2015 | 9         | 7.83%   |
| 2017 | 8         | 6.96%   |
| 2013 | 7         | 6.09%   |
| 2010 | 7         | 6.09%   |
| 2011 | 5         | 4.35%   |
| 2021 | 2         | 1.74%   |
| 2008 | 2         | 1.74%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 115       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 102       | 87.93%  |
| Enabled  | 14        | 12.07%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 115       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 43        | 37.39%  |
| 16.01-24.0  | 22        | 19.13%  |
| 3.01-4.0    | 21        | 18.26%  |
| 32.01-64.0  | 13        | 11.3%   |
| 8.01-16.0   | 13        | 11.3%   |
| 24.01-32.0  | 1         | 0.87%   |
| 64.01-256.0 | 1         | 0.87%   |
| 1.01-2.0    | 1         | 0.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 44        | 35.48%  |
| 4.01-8.0   | 25        | 20.16%  |
| 3.01-4.0   | 24        | 19.35%  |
| 1.01-2.0   | 20        | 16.13%  |
| 8.01-16.0  | 8         | 6.45%   |
| 0.51-1.0   | 2         | 1.61%   |
| 24.01-32.0 | 1         | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 83        | 72.17%  |
| 2      | 25        | 21.74%  |
| 3      | 4         | 3.48%   |
| 4      | 3         | 2.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 71        | 61.74%  |
| Yes       | 44        | 38.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 86.96%  |
| No        | 15        | 13.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 99.13%  |
| No        | 1         | 0.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 80%     |
| No        | 23        | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 21        | 18.1%   |
| Germany      | 12        | 10.34%  |
| Brazil       | 7         | 6.03%   |
| UK           | 6         | 5.17%   |
| Sweden       | 5         | 4.31%   |
| India        | 5         | 4.31%   |
| Belgium      | 5         | 4.31%   |
| Russia       | 4         | 3.45%   |
| Mexico       | 4         | 3.45%   |
| France       | 4         | 3.45%   |
| China        | 4         | 3.45%   |
| Spain        | 3         | 2.59%   |
| Italy        | 3         | 2.59%   |
| Canada       | 3         | 2.59%   |
| Turkey       | 2         | 1.72%   |
| South Korea  | 2         | 1.72%   |
| Peru         | 2         | 1.72%   |
| Norway       | 2         | 1.72%   |
| Netherlands  | 2         | 1.72%   |
| Indonesia    | 2         | 1.72%   |
| Austria      | 2         | 1.72%   |
| Vietnam      | 1         | 0.86%   |
| Ukraine      | 1         | 0.86%   |
| South Africa | 1         | 0.86%   |
| Morocco      | 1         | 0.86%   |
| Malaysia     | 1         | 0.86%   |
| Lithuania    | 1         | 0.86%   |
| Israel       | 1         | 0.86%   |
| Ireland      | 1         | 0.86%   |
| Greece       | 1         | 0.86%   |
| Egypt        | 1         | 0.86%   |
| Burkina Faso | 1         | 0.86%   |
| Bulgaria     | 1         | 0.86%   |
| Belarus      | 1         | 0.86%   |
| Bangladesh   | 1         | 0.86%   |
| Argentina    | 1         | 0.86%   |
| Afghanistan  | 1         | 0.86%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Sollentuna      | 2         | 1.67%   |
| Sao Paulo       | 2         | 1.67%   |
| Munich          | 2         | 1.67%   |
| Moscow          | 2         | 1.67%   |
| Mexico City     | 2         | 1.67%   |
| Lima            | 2         | 1.67%   |
| Denver          | 2         | 1.67%   |
| Zirndorf        | 1         | 0.83%   |
| Yeonsu-gu       | 1         | 0.83%   |
| Yekaterinburg   | 1         | 0.83%   |
| Yangpu          | 1         | 0.83%   |
| Xuhui           | 1         | 0.83%   |
| Wheeling        | 1         | 0.83%   |
| Vilnius         | 1         | 0.83%   |
| Viladecans      | 1         | 0.83%   |
| Vancouver       | 1         | 0.83%   |
| Utrecht         | 1         | 0.83%   |
| Turnhout        | 1         | 0.83%   |
| Touget          | 1         | 0.83%   |
| Toronto         | 1         | 0.83%   |
| Tolosa          | 1         | 0.83%   |
| Tel Aviv        | 1         | 0.83%   |
| Southend-on-Sea | 1         | 0.83%   |
| Sofia           | 1         | 0.83%   |
| Sleman          | 1         | 0.83%   |
| Skreia          | 1         | 0.83%   |
| Sillod          | 1         | 0.83%   |
| Sheffield       | 1         | 0.83%   |
| Shah Alam       | 1         | 0.83%   |
| San Antonio     | 1         | 0.83%   |
| Salé           | 1         | 0.83%   |
| Rethymno        | 1         | 0.83%   |
| Puebla          | 1         | 0.83%   |
| Portland        | 1         | 0.83%   |
| Port Elizabeth  | 1         | 0.83%   |
| Plano           | 1         | 0.83%   |
| Pirganj         | 1         | 0.83%   |
| Piacenza        | 1         | 0.83%   |
| Phoenix         | 1         | 0.83%   |
| Passo Fundo     | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Samsung Electronics     | 23        | 34     | 15.44%  |
| Seagate                 | 20        | 23     | 13.42%  |
| WDC                     | 13        | 16     | 8.72%   |
| Toshiba                 | 13        | 16     | 8.72%   |
| SanDisk                 | 13        | 14     | 8.72%   |
| Unknown                 | 9         | 11     | 6.04%   |
| Kingston                | 8         | 9      | 5.37%   |
| HGST                    | 6         | 7      | 4.03%   |
| Crucial                 | 6         | 7      | 4.03%   |
| Intel                   | 5         | 6      | 3.36%   |
| SK hynix                | 4         | 4      | 2.68%   |
| Hitachi                 | 3         | 4      | 2.01%   |
| SPCC                    | 2         | 2      | 1.34%   |
| Micron Technology       | 2         | 2      | 1.34%   |
| LITEON                  | 2         | 3      | 1.34%   |
| Lenovo                  | 2         | 3      | 1.34%   |
| KIOXIA                  | 2         | 3      | 1.34%   |
| A-DATA Technology       | 2         | 2      | 1.34%   |
| XrayDisk                | 1         | 1      | 0.67%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.67%   |
| Union Memory            | 1         | 1      | 0.67%   |
| UMIS                    | 1         | 1      | 0.67%   |
| Transcend               | 1         | 2      | 0.67%   |
| SSD                     | 1         | 1      | 0.67%   |
| Silicon Motion          | 1         | 1      | 0.67%   |
| Plextor                 | 1         | 1      | 0.67%   |
| LITEONIT                | 1         | 1      | 0.67%   |
| Lexar                   | 1         | 1      | 0.67%   |
| JetFlash                | 1         | 1      | 0.67%   |
| Biostar                 | 1         | 1      | 0.67%   |
| Apple                   | 1         | 1      | 0.67%   |
| 980Plus                 | 1         | 1      | 0.67%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                       | 4         | 2.56%   |
| Seagate ST1000LM035-1RK172 1TB               | 4         | 2.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 4         | 2.56%   |
| Samsung NVMe SSD Drive 512GB                 | 4         | 2.56%   |
| Unknown MMC Card  32GB                       | 3         | 1.92%   |
| SanDisk NVMe SSD Drive 512GB                 | 3         | 1.92%   |
| Kingston SA400M8240G 240GB SSD               | 3         | 1.92%   |
| Seagate ST500LT012-1DG142 500GB              | 2         | 1.28%   |
| Seagate ST500LM012 HN-M500MBB 500GB          | 2         | 1.28%   |
| SanDisk NVMe SSD Drive 500GB                 | 2         | 1.28%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB       | 2         | 1.28%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD         | 2         | 1.28%   |
| Kingston SA400S37120G 120GB SSD              | 2         | 1.28%   |
| Hitachi HTS547550A9E384 500GB                | 2         | 1.28%   |
| HGST HTS545050A7E380 500GB                   | 2         | 1.28%   |
| XrayDisk SSD 240GB                           | 1         | 0.64%   |
| WDC WDS500G2B0B-00YS70 500GB SSD             | 1         | 0.64%   |
| WDC WDS500G1R0B-68A4Z0 500GB SSD             | 1         | 0.64%   |
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1         | 0.64%   |
| WDC WDS100T1R0A-68A4W0 1TB SSD               | 1         | 0.64%   |
| WDC WD7500BPKX-22HPJT0 752GB                 | 1         | 0.64%   |
| WDC WD5000BEVT-00A0RT0 500GB                 | 1         | 0.64%   |
| WDC WD3200BEKT-60PVMT0 320GB                 | 1         | 0.64%   |
| WDC WD1600BEVT-75ZCT2 160GB                  | 1         | 0.64%   |
| WDC WD10SPZX-24Z10 1TB                       | 1         | 0.64%   |
| WDC WD10SPZX-22Z10T1 1TB                     | 1         | 0.64%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1         | 0.64%   |
| WDC WD10JPLX-00MBPT0 1TB                     | 1         | 0.64%   |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 0.64%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB         | 1         | 0.64%   |
| Unknown SD02G  2GB                           | 1         | 0.64%   |
| Unknown SD/MMC/MS PRO 8GB                    | 1         | 0.64%   |
| Unknown MMC Card  976MB                      | 1         | 0.64%   |
| Unknown MMC Card  4GB                        | 1         | 0.64%   |
| Unknown MMC Card  33GB                       | 1         | 0.64%   |
| Unknown MMC Card  2GB                        | 1         | 0.64%   |
| Unknown MMC Card  1GB                        | 1         | 0.64%   |
| Union Memory UMIS RPJTJ256MED1OWX 256GB      | 1         | 0.64%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 0.64%   |
| UMIS RPFTJ128PDD2EWX 128GB                   | 1         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 19        | 22     | 41.3%   |
| WDC     | 9         | 11     | 19.57%  |
| Toshiba | 8         | 11     | 17.39%  |
| HGST    | 6         | 7      | 13.04%  |
| Hitachi | 3         | 4      | 6.52%   |
| Unknown | 1         | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 24     | 27.42%  |
| Kingston            | 8         | 9      | 12.9%   |
| SanDisk             | 7         | 8      | 11.29%  |
| Crucial             | 5         | 6      | 8.06%   |
| Toshiba             | 4         | 4      | 6.45%   |
| WDC                 | 3         | 4      | 4.84%   |
| Intel               | 3         | 3      | 4.84%   |
| SPCC                | 2         | 2      | 3.23%   |
| SK hynix            | 2         | 2      | 3.23%   |
| LITEON              | 2         | 3      | 3.23%   |
| XrayDisk            | 1         | 1      | 1.61%   |
| Transcend           | 1         | 2      | 1.61%   |
| SSD                 | 1         | 1      | 1.61%   |
| Plextor             | 1         | 1      | 1.61%   |
| LITEONIT            | 1         | 1      | 1.61%   |
| Lenovo              | 1         | 2      | 1.61%   |
| Biostar             | 1         | 1      | 1.61%   |
| Apple               | 1         | 1      | 1.61%   |
| A-DATA Technology   | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 59        | 76     | 40.14%  |
| HDD     | 45        | 56     | 30.61%  |
| NVMe    | 32        | 36     | 21.77%  |
| MMC     | 8         | 10     | 5.44%   |
| Unknown | 3         | 3      | 2.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 93        | 131    | 68.89%  |
| NVMe | 32        | 36     | 23.7%   |
| MMC  | 8         | 10     | 5.93%   |
| SAS  | 2         | 4      | 1.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 87     | 64.42%  |
| 0.51-1.0   | 32        | 40     | 30.77%  |
| 1.01-2.0   | 4         | 4      | 3.85%   |
| 3.01-4.0   | 1         | 1      | 0.96%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 36        | 31.3%   |
| 101-250        | 28        | 24.35%  |
| 501-1000       | 20        | 17.39%  |
| 51-100         | 8         | 6.96%   |
| 1001-2000      | 7         | 6.09%   |
| 21-50          | 5         | 4.35%   |
| Unknown        | 4         | 3.48%   |
| 1-20           | 3         | 2.61%   |
| More than 3000 | 2         | 1.74%   |
| 2001-3000      | 2         | 1.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 41        | 33.88%  |
| 21-50     | 30        | 24.79%  |
| 51-100    | 18        | 14.88%  |
| 101-250   | 12        | 9.92%   |
| 251-500   | 7         | 5.79%   |
| 501-1000  | 6         | 4.96%   |
| Unknown   | 4         | 3.31%   |
| 1001-2000 | 3         | 2.48%   |

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
| Detected | 76        | 124    | 61.29%  |
| Works    | 40        | 47     | 32.26%  |
| Malfunc  | 7         | 9      | 5.65%   |
| Failed   | 1         | 1      | 0.81%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 102       | 72.86%  |
| Samsung Electronics          | 10        | 7.14%   |
| SanDisk                      | 6         | 4.29%   |
| AMD                          | 6         | 4.29%   |
| Union Memory (Shenzhen)      | 3         | 2.14%   |
| SK hynix                     | 2         | 1.43%   |
| Micron Technology            | 2         | 1.43%   |
| KIOXIA                       | 2         | 1.43%   |
| Toshiba America Info Systems | 1         | 0.71%   |
| Silicon Motion               | 1         | 0.71%   |
| Shenzhen Longsys Electronics | 1         | 0.71%   |
| Micron/Crucial Technology    | 1         | 0.71%   |
| Marvell Technology Group     | 1         | 0.71%   |
| Lenovo                       | 1         | 0.71%   |
| ADATA Technology             | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 11.11%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 9.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 7.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 8         | 5.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 4.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 6         | 4.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 4.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 6         | 4.17%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 6         | 4.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 3.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 2.78%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 3         | 2.08%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 2.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 2.08%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 2.08%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 2.08%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 1.39%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 1.39%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 1.39%   |
| Micron Non-Volatile memory controller                                          | 2         | 1.39%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 2         | 1.39%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.39%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 1.39%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 1.39%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 1         | 0.69%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 1         | 0.69%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.69%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.69%   |
| Shenzhen Longsys Non-Volatile memory controller                                | 1         | 0.69%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 0.69%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 1         | 0.69%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.69%   |
| SanDisk Non-Volatile memory controller                                         | 1         | 0.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 1         | 0.69%   |
| Samsung Electronics SATA controller                                            | 1         | 0.69%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 0.69%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.69%   |
| Lenovo Non-Volatile memory controller                                          | 1         | 0.69%   |
| Intel Tiger Lake-LP SATA Controller                                            | 1         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 100       | 70.42%  |
| NVMe | 32        | 22.54%  |
| RAID | 8         | 5.63%   |
| IDE  | 2         | 1.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 109       | 94.78%  |
| AMD    | 6         | 5.22%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 3.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.61%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 2.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 2.61%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 2.61%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 2.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.74%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.74%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 1.74%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.74%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.74%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.74%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 2         | 1.74%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.74%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.74%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.87%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.87%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.87%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.87%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.87%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.87%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.87%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.87%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.87%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.87%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.87%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.87%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.87%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.87%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 0.87%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 1         | 0.87%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.87%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.87%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.87%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.87%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.87%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.87%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 42        | 36.52%  |
| Intel Core i5    | 41        | 35.65%  |
| Intel Core i3    | 10        | 8.7%    |
| Other            | 5         | 4.35%   |
| Intel Pentium    | 4         | 3.48%   |
| Intel Celeron    | 4         | 3.48%   |
| Intel Core 2 Duo | 2         | 1.74%   |
| AMD Ryzen 7      | 2         | 1.74%   |
| Intel Xeon       | 1         | 0.87%   |
| Intel Core i9    | 1         | 0.87%   |
| AMD Ryzen 5      | 1         | 0.87%   |
| AMD Ryzen 3      | 1         | 0.87%   |
| AMD A4           | 1         | 0.87%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 63        | 54.78%  |
| 4      | 43        | 37.39%  |
| 6      | 8         | 6.96%   |
| 8      | 1         | 0.87%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 115       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 100       | 86.96%  |
| 1      | 15        | 13.04%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 114       | 98.28%  |
| Unknown        | 2         | 1.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306a9    | 12        | 10.34%  |
| 0x40651    | 11        | 9.48%   |
| 0x206a7    | 10        | 8.62%   |
| 0x406e3    | 9         | 7.76%   |
| 0x806ea    | 8         | 6.9%    |
| 0x306d4    | 8         | 6.9%    |
| 0x306c3    | 6         | 5.17%   |
| 0x806ec    | 5         | 4.31%   |
| 0x20655    | 5         | 4.31%   |
| 0xa0652    | 4         | 3.45%   |
| 0x906ea    | 4         | 3.45%   |
| 0x806c1    | 4         | 3.45%   |
| 0x506e3    | 4         | 3.45%   |
| Unknown    | 4         | 3.45%   |
| 0x806e9    | 3         | 2.59%   |
| 0x706e5    | 3         | 2.59%   |
| 0x906ed    | 2         | 1.72%   |
| 0x906e9    | 2         | 1.72%   |
| 0x30678    | 2         | 1.72%   |
| 0x106e5    | 2         | 1.72%   |
| 0x06006705 | 2         | 1.72%   |
| 0x406c3    | 1         | 0.86%   |
| 0x20652    | 1         | 0.86%   |
| 0x1067a    | 1         | 0.86%   |
| 0x10676    | 1         | 0.86%   |
| 0x08108109 | 1         | 0.86%   |
| 0x08108102 | 1         | 0.86%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 25        | 21.74%  |
| Haswell     | 17        | 14.78%  |
| Skylake     | 13        | 11.3%   |
| IvyBridge   | 12        | 10.43%  |
| SandyBridge | 10        | 8.7%    |
| Broadwell   | 8         | 6.96%   |
| Westmere    | 6         | 5.22%   |
| TigerLake   | 4         | 3.48%   |
| CometLake   | 4         | 3.48%   |
| Zen+        | 3         | 2.61%   |
| Silvermont  | 3         | 2.61%   |
| IceLake     | 3         | 2.61%   |
| Penryn      | 2         | 1.74%   |
| Nehalem     | 2         | 1.74%   |
| Excavator   | 2         | 1.74%   |
| Zen 2       | 1         | 0.87%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 98        | 63.23%  |
| Nvidia | 40        | 25.81%  |
| AMD    | 17        | 10.97%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 11        | 7.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 10        | 6.45%   |
| Intel UHD Graphics 620                                                                | 9         | 5.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 9         | 5.81%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 9         | 5.81%   |
| Intel HD Graphics 5500                                                                | 6         | 3.87%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 5         | 3.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 4         | 2.58%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 4         | 2.58%   |
| Intel Core Processor Integrated Graphics Controller                                   | 4         | 2.58%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 4         | 2.58%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 4         | 2.58%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 4         | 2.58%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 3         | 1.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 3         | 1.94%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 3         | 1.94%   |
| Intel HD Graphics 620                                                                 | 3         | 1.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 3         | 1.94%   |
| Nvidia GM108M [GeForce 930MX]                                                         | 2         | 1.29%   |
| Nvidia GM108M [GeForce 840M]                                                          | 2         | 1.29%   |
| Nvidia GK208BM [GeForce 920M]                                                         | 2         | 1.29%   |
| Nvidia GK107GLM [Quadro K1100M]                                                       | 2         | 1.29%   |
| Intel HD Graphics 630                                                                 | 2         | 1.29%   |
| Intel HD Graphics 530                                                                 | 2         | 1.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 2         | 1.29%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 2         | 1.29%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                          | 2         | 1.29%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                 | 1         | 0.65%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                               | 1         | 0.65%   |
| Nvidia GT218M [GeForce 310M]                                                          | 1         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 1         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 1         | 0.65%   |
| Nvidia GP107GLM [Quadro P620]                                                         | 1         | 0.65%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                               | 1         | 0.65%   |
| Nvidia GM204M [GeForce GTX 980M]                                                      | 1         | 0.65%   |
| Nvidia GM108M [GeForce MX130]                                                         | 1         | 0.65%   |
| Nvidia GM108M [GeForce 940M]                                                          | 1         | 0.65%   |
| Nvidia GM107M [GeForce GTX 850M]                                                      | 1         | 0.65%   |
| Nvidia GM107GLM [Quadro M2000M]                                                       | 1         | 0.65%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                 | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 59        | 51.3%   |
| Intel + Nvidia | 31        | 26.96%  |
| 1 x Nvidia     | 8         | 6.96%   |
| Intel + AMD    | 8         | 6.96%   |
| 1 x AMD        | 8         | 6.96%   |
| AMD + Nvidia   | 1         | 0.87%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 109       | 94.78%  |
| Proprietary | 3         | 2.61%   |
| Unknown     | 3         | 2.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 58.26%  |
| 1.01-2.0   | 23        | 20%     |
| 3.01-4.0   | 14        | 12.17%  |
| 0.51-1.0   | 5         | 4.35%   |
| 0.01-0.5   | 5         | 4.35%   |
| 7.01-8.0   | 1         | 0.87%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 27        | 19.85%  |
| Chimei Innolux          | 23        | 16.91%  |
| LG Display              | 19        | 13.97%  |
| BOE                     | 17        | 12.5%   |
| Samsung Electronics     | 16        | 11.76%  |
| Dell                    | 7         | 5.15%   |
| Sharp                   | 3         | 2.21%   |
| Panasonic               | 3         | 2.21%   |
| Lenovo                  | 3         | 2.21%   |
| Acer                    | 3         | 2.21%   |
| PANDA                   | 2         | 1.47%   |
| Hewlett-Packard         | 2         | 1.47%   |
| Goldstar                | 2         | 1.47%   |
| Vizio                   | 1         | 0.74%   |
| Philips                 | 1         | 0.74%   |
| Onkyo                   | 1         | 0.74%   |
| MSI                     | 1         | 0.74%   |
| InfoVision              | 1         | 0.74%   |
| Gateway                 | 1         | 0.74%   |
| Chi Mei Optoelectronics | 1         | 0.74%   |
| Apple                   | 1         | 0.74%   |
| AOC                     | 1         | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch           | 3         | 2.17%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.45%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 2         | 1.45%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.45%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 1.45%   |
| Vizio E370VL VIZ0070 1920x1080 820x461mm 37.0-inch                    | 1         | 0.72%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.72%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.72%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.72%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 340x270mm 17.1-inch  | 1         | 0.72%   |
| Samsung Electronics SMBX2450 SAM0721 1920x1080 530x300mm 24.0-inch    | 1         | 0.72%   |
| Samsung Electronics S22B420 SAM0979 1680x1050 473x291mm 21.9-inch     | 1         | 0.72%   |
| Samsung Electronics LU28R55 SAM1017 3840x2160 632x360mm 28.6-inch     | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC5341 1366x768 344x193mm 15.5-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3848 1920x1200 367x230mm 17.1-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3646 1680x1050 330x210mm 15.4-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3147 1600x900 332x187mm 15.0-inch  | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC834E 1920x1080 309x174mm 14.0-inch | 1         | 0.72%   |
| Samsung Electronics LCD Monitor SDC364D 1920x1080 309x174mm 14.0-inch | 1         | 0.72%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.72%   |
| Philips PHL 278E9Q PHLC17F 1920x1080 598x336mm 27.0-inch              | 1         | 0.72%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch               | 1         | 0.72%   |
| PANDA LCD Monitor NCP002A 1920x1080 344x194mm 15.5-inch               | 1         | 0.72%   |
| Onkyo AV Receiver ONK1151 1920x1080                                   | 1         | 0.72%   |
| MSI PRO 22X 10M MSI1462 1920x1080 595x336mm 26.9-inch                 | 1         | 0.72%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD061C 1920x1080 294x165mm 13.3-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD05D5 1920x1080 344x194mm 15.5-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD05D1 1920x1080 344x194mm 15.5-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD0490 1920x1080 309x174mm 14.0-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 0.72%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x174mm 14.0-inch          | 1         | 0.72%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 62        | 48.44%  |
| 1366x768 (WXGA)    | 36        | 28.13%  |
| 1600x900 (HD+)     | 9         | 7.03%   |
| 3840x2160 (4K)     | 6         | 4.69%   |
| 1680x1050 (WSXGA+) | 4         | 3.13%   |
| 2560x1600          | 2         | 1.56%   |
| 2560x1440 (QHD)    | 2         | 1.56%   |
| 1920x1200 (WUXGA)  | 2         | 1.56%   |
| 1280x800 (WXGA)    | 2         | 1.56%   |
| 1280x1024 (SXGA)   | 2         | 1.56%   |
| 3440x1440          | 1         | 0.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 59        | 43.07%  |
| 13      | 17        | 12.41%  |
| 14      | 16        | 11.68%  |
| 17      | 13        | 9.49%   |
| 24      | 6         | 4.38%   |
| 23      | 5         | 3.65%   |
| 21      | 4         | 2.92%   |
| 12      | 4         | 2.92%   |
| 27      | 3         | 2.19%   |
| 11      | 2         | 1.46%   |
| Unknown | 2         | 1.46%   |
| 42      | 1         | 0.73%   |
| 34      | 1         | 0.73%   |
| 32      | 1         | 0.73%   |
| 29      | 1         | 0.73%   |
| 28      | 1         | 0.73%   |
| 20      | 1         | 0.73%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 86        | 63.7%   |
| 351-400     | 14        | 10.37%  |
| 501-600     | 12        | 8.89%   |
| 201-300     | 9         | 6.67%   |
| 401-500     | 6         | 4.44%   |
| 601-700     | 3         | 2.22%   |
| 701-800     | 2         | 1.48%   |
| Unknown     | 2         | 1.48%   |
| 901-1000    | 1         | 0.74%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 106       | 89.08%  |
| 16/10   | 8         | 6.72%   |
| 5/4     | 2         | 1.68%   |
| 3/2     | 1         | 0.84%   |
| 21/9    | 1         | 0.84%   |
| Unknown | 1         | 0.84%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 58        | 42.03%  |
| 81-90          | 31        | 22.46%  |
| 201-250        | 13        | 9.42%   |
| 121-130        | 10        | 7.25%   |
| 61-70          | 4         | 2.9%    |
| 351-500        | 4         | 2.9%    |
| 301-350        | 3         | 2.17%   |
| 71-80          | 2         | 1.45%   |
| 51-60          | 2         | 1.45%   |
| 251-300        | 2         | 1.45%   |
| 151-200        | 2         | 1.45%   |
| 141-150        | 2         | 1.45%   |
| Unknown        | 2         | 1.45%   |
| 131-140        | 1         | 0.72%   |
| 501-1000       | 1         | 0.72%   |
| 91-100         | 1         | 0.72%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 65        | 48.87%  |
| 101-120       | 36        | 27.07%  |
| 51-100        | 23        | 17.29%  |
| More than 240 | 4         | 3.01%   |
| 161-240       | 3         | 2.26%   |
| Unknown       | 2         | 1.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 94        | 78.99%  |
| 2     | 20        | 16.81%  |
| 3     | 3         | 2.52%   |
| 0     | 2         | 1.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 69        | 39.66%  |
| Realtek Semiconductor             | 58        | 33.33%  |
| Qualcomm Atheros                  | 26        | 14.94%  |
| Broadcom                          | 7         | 4.02%   |
| Ralink                            | 2         | 1.15%   |
| Dell                              | 2         | 1.15%   |
| Broadcom Limited                  | 2         | 1.15%   |
| Xiaomi                            | 1         | 0.57%   |
| Sierra Wireless                   | 1         | 0.57%   |
| Ralink Technology                 | 1         | 0.57%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.57%   |
| Marvell Technology Group          | 1         | 0.57%   |
| Ericsson Business Mobile Networks | 1         | 0.57%   |
| D-Link                            | 1         | 0.57%   |
| ASIX Electronics                  | 1         | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 19.47%  |
| Intel Wireless 7260                                               | 11        | 4.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 3.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.65%   |
| Intel Wireless 8260                                               | 6         | 2.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 2.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.21%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.21%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.21%   |
| Intel Wireless 7265                                               | 4         | 1.77%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.77%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.77%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.77%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.77%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 1.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 1.33%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 1.33%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 1.33%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.88%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.88%   |
| Intel Wireless-AC 9260                                            | 2         | 0.88%   |
| Intel Wireless 3165                                               | 2         | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.88%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.88%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.88%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.88%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.88%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.88%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 67        | 55.83%  |
| Qualcomm Atheros      | 22        | 18.33%  |
| Realtek Semiconductor | 17        | 14.17%  |
| Broadcom              | 5         | 4.17%   |
| Ralink                | 2         | 1.67%   |
| Dell                  | 2         | 1.67%   |
| Broadcom Limited      | 2         | 1.67%   |
| Sierra Wireless       | 1         | 0.83%   |
| Ralink Technology     | 1         | 0.83%   |
| D-Link                | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 11        | 9.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 5%      |
| Intel Wireless 8260                                            | 6         | 5%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 4.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 4.17%   |
| Intel Wireless 8265 / 8275                                     | 5         | 4.17%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 4.17%   |
| Intel Wireless 7265                                            | 4         | 3.33%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 3.33%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 2.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 2.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 2.5%    |
| Intel Centrino Ultimate-N 6300                                 | 3         | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 2.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.67%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 1.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.67%   |
| Intel Wireless-AC 9260                                         | 2         | 1.67%   |
| Intel Wireless 3165                                            | 2         | 1.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.67%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 1.67%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.67%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 0.83%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.83%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 1         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.83%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.83%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.83%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.83%   |
| Intel Wireless 3160                                            | 1         | 0.83%   |
| Intel WiFi Link 5100                                           | 1         | 0.83%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 54        | 52.43%  |
| Intel                         | 36        | 34.95%  |
| Qualcomm Atheros              | 7         | 6.8%    |
| Broadcom                      | 2         | 1.94%   |
| Xiaomi                        | 1         | 0.97%   |
| OnePlus Technology (Shenzhen) | 1         | 0.97%   |
| Marvell Technology Group      | 1         | 0.97%   |
| ASIX Electronics              | 1         | 0.97%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 41.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 8.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.76%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 3.81%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 3.81%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 3.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.86%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.9%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1.9%    |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.9%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.9%    |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.9%    |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.9%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.9%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 1.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.95%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.95%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.95%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.95%   |
| OnePlus (Shenzhen) AC2003                                         | 1         | 0.95%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.95%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.95%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.95%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 0.95%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.95%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.95%   |
| ASIX AX88772                                                      | 1         | 0.95%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 114       | 53.02%  |
| Ethernet | 100       | 46.51%  |
| Modem    | 1         | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 95        | 75.4%   |
| Ethernet | 31        | 24.6%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 97        | 84.35%  |
| 1     | 18        | 15.65%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 99        | 86.09%  |
| Yes  | 16        | 13.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 51.06%  |
| Qualcomm Atheros Communications | 17        | 18.09%  |
| Realtek Semiconductor           | 13        | 13.83%  |
| Broadcom                        | 5         | 5.32%   |
| IMC Networks                    | 2         | 2.13%   |
| Hewlett-Packard                 | 2         | 2.13%   |
| Cambridge Silicon Radio         | 2         | 2.13%   |
| Toshiba                         | 1         | 1.06%   |
| Ralink                          | 1         | 1.06%   |
| Lite-On Technology              | 1         | 1.06%   |
| Foxconn / Hon Hai               | 1         | 1.06%   |
| Apple                           | 1         | 1.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 27        | 28.72%  |
| Realtek Bluetooth Radio                             | 10        | 10.64%  |
| Intel AX201 Bluetooth                               | 7         | 7.45%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 6.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 5.32%   |
| Intel AX200 Bluetooth                               | 5         | 5.32%   |
| Qualcomm Atheros  Bluetooth Device                  | 4         | 4.26%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 3.19%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 2.13%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.13%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 2.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.13%   |
| Toshiba Bluetooth Radio                             | 1         | 1.06%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.06%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.06%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.06%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.06%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.06%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.06%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.06%   |
| IMC Networks Bluetooth Device                       | 1         | 1.06%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 1.06%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.06%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.06%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1         | 1.06%   |
| Broadcom BCM20702A0                                 | 1         | 1.06%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.06%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.06%   |
| Apple Bluetooth Host Controller                     | 1         | 1.06%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 108       | 75%     |
| Nvidia                   | 19        | 13.19%  |
| AMD                      | 9         | 6.25%   |
| Logitech                 | 2         | 1.39%   |
| GN Netcom                | 2         | 1.39%   |
| Tenx Technology          | 1         | 0.69%   |
| Plantronics              | 1         | 0.69%   |
| Kingston Technology      | 1         | 0.69%   |
| Asahi Kasei Microsystems | 1         | 0.69%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 20        | 11.63%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14        | 8.14%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 6.4%    |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 5.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 4.65%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 4.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 4.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 4.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 3.49%   |
| Intel Cannon Lake PCH cAVS                                                 | 6         | 3.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 3.49%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 2.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 2.33%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 2.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.33%   |
| AMD Family 17h/19h HD Audio Controller                                     | 4         | 2.33%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.74%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.74%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.74%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.16%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 2         | 1.16%   |
| AMD High Definition Audio Controller                                       | 2         | 1.16%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2         | 1.16%   |
| Tenx Technology USB AUDIO                                                  | 1         | 0.58%   |
| Plantronics Calisto 800 Series                                             | 1         | 0.58%   |
| Plantronics Blackwire C210                                                 | 1         | 0.58%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.58%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.58%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.58%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.58%   |
| Nvidia GK106 HDMI Audio Controller                                         | 1         | 0.58%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.58%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.58%   |
| Logitech Headset H340                                                      | 1         | 0.58%   |
| Logitech Clear Chat Comfort USB Headset                                    | 1         | 0.58%   |
| Kingston Technology HyperX 7.1 Audio                                       | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 16        | 28.07%  |
| Samsung Electronics | 14        | 24.56%  |
| Kingston            | 11        | 19.3%   |
| Micron Technology   | 4         | 7.02%   |
| Unknown             | 3         | 5.26%   |
| A-DATA Technology   | 3         | 5.26%   |
| Elpida              | 2         | 3.51%   |
| Ramaxel Technology  | 1         | 1.75%   |
| Nanya Technology    | 1         | 1.75%   |
| Crucial             | 1         | 1.75%   |
| Corsair             | 1         | 1.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s         | 2         | 3.33%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s        | 2         | 3.33%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                   | 1         | 1.67%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                    | 1         | 1.67%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                | 1         | 1.67%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                  | 1         | 1.67%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s               | 1         | 1.67%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s               | 1         | 1.67%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                 | 1         | 1.67%   |
| SK hynix RAM HMT851S6AMR6R-PB N0 4GB Chip DDR3 1600MT/s       | 1         | 1.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.67%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.67%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.67%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s        | 1         | 1.67%   |
| SK hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s     | 1         | 1.67%   |
| SK hynix RAM HMT125S6AFP8C-G7 2GB SODIMM DDR3 1066MT/s        | 1         | 1.67%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 1866MT/s  | 1         | 1.67%   |
| SK hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s        | 1         | 1.67%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s       | 1         | 1.67%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s        | 1         | 1.67%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.67%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s         | 1         | 1.67%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.67%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.67%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s         | 1         | 1.67%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s      | 1         | 1.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s         | 1         | 1.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s   | 1         | 1.67%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s         | 1         | 1.67%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s         | 1         | 1.67%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s         | 1         | 1.67%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s     | 1         | 1.67%   |
| Nanya RAM NT2GC64B8HC0NS-CG 2GB SODIMM DDR3 1334MT/s          | 1         | 1.67%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 1.67%   |
| Micron RAM 8ATF1G64HZ-2G6D1 8192MB SODIMM DDR4 2667MT/s       | 1         | 1.67%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.67%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s         | 1         | 1.67%   |
| Kingston RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 1.67%   |
| Kingston RAM KF1866C11S3L/8G 8GB SODIMM DDR3 1600MT/s         | 1         | 1.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 24        | 48%     |
| DDR4   | 22        | 44%     |
| LPDDR4 | 2         | 4%      |
| LPDDR3 | 1         | 2%      |
| DDR2   | 1         | 2%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 44        | 88%     |
| Row Of Chips | 5         | 10%     |
| Chip         | 1         | 2%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 23        | 43.4%   |
| 8192  | 17        | 32.08%  |
| 16384 | 8         | 15.09%  |
| 2048  | 5         | 9.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 16        | 30.77%  |
| 2667  | 14        | 26.92%  |
| 2133  | 4         | 7.69%   |
| 1333  | 4         | 7.69%   |
| 2400  | 3         | 5.77%   |
| 1334  | 3         | 5.77%   |
| 4267  | 2         | 3.85%   |
| 3266  | 1         | 1.92%   |
| 3200  | 1         | 1.92%   |
| 1866  | 1         | 1.92%   |
| 1067  | 1         | 1.92%   |
| 1066  | 1         | 1.92%   |
| 667   | 1         | 1.92%   |

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
| Chicony Electronics                    | 33        | 31.43%  |
| Microdia                               | 14        | 13.33%  |
| Acer                                   | 12        | 11.43%  |
| Realtek Semiconductor                  | 7         | 6.67%   |
| Lite-On Technology                     | 7         | 6.67%   |
| IMC Networks                           | 7         | 6.67%   |
| Sunplus Innovation Technology          | 6         | 5.71%   |
| Quanta                                 | 4         | 3.81%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.81%   |
| Syntek                                 | 2         | 1.9%    |
| Silicon Motion                         | 2         | 1.9%    |
| Microsoft                              | 2         | 1.9%    |
| Suyin                                  | 1         | 0.95%   |
| Sunplus Technology                     | 1         | 0.95%   |
| Logitech                               | 1         | 0.95%   |
| Intel                                  | 1         | 0.95%   |
| Alcor Micro                            | 1         | 0.95%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 7         | 6.67%   |
| Microdia Integrated_Webcam_HD           | 4         | 3.81%   |
| Lite-On Integrated Camera               | 3         | 2.86%   |
| Lite-On HP HD Camera                    | 3         | 2.86%   |
| IMC Networks USB2.0 HD UVC WebCam       | 3         | 2.86%   |
| IMC Networks Integrated Camera          | 3         | 2.86%   |
| Chicony USB2.0 VGA UVC WebCam           | 3         | 2.86%   |
| Chicony Integrated Camera (1280x720@30) | 3         | 2.86%   |
| Chicony HP TrueVision HD                | 3         | 2.86%   |
| Chicony HP HD Camera                    | 3         | 2.86%   |
| Chicony HD WebCam                       | 3         | 2.86%   |
| Acer Lenovo EasyCamera                  | 3         | 2.86%   |
| Acer Integrated Camera                  | 3         | 2.86%   |
| Sunplus Integrated_Webcam_HD            | 2         | 1.9%    |
| Quanta HP TrueVision HD Camera          | 2         | 1.9%    |
| Microdia Laptop_Integrated_Webcam_HD    | 2         | 1.9%    |
| Microdia Laptop_Integrated_Webcam_2M    | 2         | 1.9%    |
| Chicony HP Webcam [2 MP Macro]          | 2         | 1.9%    |
| Chicony HP HD Webcam                    | 2         | 1.9%    |
| Syntek USB2.0 UVC PC Camera             | 1         | 0.95%   |
| Syntek Lenovo EasyCamera                | 1         | 0.95%   |
| Suyin Sony Visual Communication Camera  | 1         | 0.95%   |
| Sunplus 1.3M WebCam                     | 1         | 0.95%   |
| Sunplus USB Video Device                | 1         | 0.95%   |
| Sunplus Integrated_Webcam_FHD           | 1         | 0.95%   |
| Sunplus HD WebCam                       | 1         | 0.95%   |
| Sunplus Asus Webcam                     | 1         | 0.95%   |
| Silicon Motion WebCam SC-13HDL11431N    | 1         | 0.95%   |
| Silicon Motion ATIV VGA Camera          | 1         | 0.95%   |
| Realtek USB Camera                      | 1         | 0.95%   |
| Realtek Rear Camera                     | 1         | 0.95%   |
| Realtek Integrated Webcam_HD            | 1         | 0.95%   |
| Realtek Integrated Webcam               | 1         | 0.95%   |
| Realtek HD Webcam - Realtek             | 1         | 0.95%   |
| Realtek HD Webcam                       | 1         | 0.95%   |
| Realtek EasyCamera                      | 1         | 0.95%   |
| Quanta HD Webcam                        | 1         | 0.95%   |
| Quanta HD User Facing                   | 1         | 0.95%   |
| Microsoft LifeCam VX-500 [1357]         | 1         | 0.95%   |
| Microsoft LifeCam HD-3000               | 1         | 0.95%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 18        | 56.25%  |
| Synaptics                  | 6         | 18.75%  |
| Shenzhen Goodix Technology | 3         | 9.38%   |
| Upek                       | 2         | 6.25%   |
| Elan Microelectronics      | 2         | 6.25%   |
| AuthenTec                  | 1         | 3.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 7         | 21.88%  |
| Validity Sensors VFS451 Fingerprint Reader             | 3         | 9.38%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 9.38%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 2         | 6.25%   |
| Validity Sensors VFS491                                | 2         | 6.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 6.25%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 2         | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 6.25%   |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 6.25%   |
| Elan ELAN:Fingerprint                                  | 2         | 6.25%   |
| Validity Sensors Synaptics WBDI                        | 1         | 3.13%   |
| Synaptics  WBDI                                        | 1         | 3.13%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 3.13%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 3.13%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 3.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 71.43%  |
| O2 Micro    | 1         | 14.29%  |
| Alcor Micro | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 2         | 28.57%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 60        | 51.72%  |
| 1     | 49        | 42.24%  |
| 2     | 5         | 4.31%   |
| 6     | 1         | 0.86%   |
| 3     | 1         | 0.86%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 32        | 48.48%  |
| Graphics card            | 12        | 18.18%  |
| Net/wireless             | 6         | 9.09%   |
| Chipcard                 | 5         | 7.58%   |
| Multimedia controller    | 4         | 6.06%   |
| Bluetooth                | 2         | 3.03%   |
| Storage                  | 1         | 1.52%   |
| Sound                    | 1         | 1.52%   |
| Net/ethernet             | 1         | 1.52%   |
| Communication controller | 1         | 1.52%   |
| Camera                   | 1         | 1.52%   |

