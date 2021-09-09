CentOS 8 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for CentOS 8.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=centos-8

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| ASUSTek       | X455LJ                      | [0b78463a71](https://linux-hardware.org/?probe=0b78463a71) | Jun 26, 2021 |
| HP            | EliteBook 8740w             | [9b54339e9b](https://linux-hardware.org/?probe=9b54339e9b) | Jun 16, 2021 |
| HP            | EliteBook 8740w             | [9ad5884fca](https://linux-hardware.org/?probe=9ad5884fca) | Jun 16, 2021 |
| COPELION I... | QX-350                      | [afd819962a](https://linux-hardware.org/?probe=afd819962a) | Jun 16, 2021 |
| COPELION I... | QX-350                      | [7672d01a80](https://linux-hardware.org/?probe=7672d01a80) | Jun 08, 2021 |
| COPELION I... | QX-350                      | [4181e36f84](https://linux-hardware.org/?probe=4181e36f84) | Jun 07, 2021 |
| Dell          | Latitude E6530              | [eaf1c46fce](https://linux-hardware.org/?probe=eaf1c46fce) | May 29, 2021 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [5742c8e4e5](https://linux-hardware.org/?probe=5742c8e4e5) | May 28, 2021 |
| HP            | EliteBook 840 G5            | [ef516b4f37](https://linux-hardware.org/?probe=ef516b4f37) | May 17, 2021 |
| Lenovo        | ThinkPad W540 20BG001KUK    | [ce71038513](https://linux-hardware.org/?probe=ce71038513) | May 14, 2021 |
| Lenovo        | ThinkPad E490 20N8007NTX    | [e9efa41cf8](https://linux-hardware.org/?probe=e9efa41cf8) | May 12, 2021 |
| HP            | ZBook 15 G6                 | [ea363ea07e](https://linux-hardware.org/?probe=ea363ea07e) | May 07, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [cb93a75f6a](https://linux-hardware.org/?probe=cb93a75f6a) | Apr 28, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [1133f762f5](https://linux-hardware.org/?probe=1133f762f5) | Apr 15, 2021 |
| Dell          | Precision 3551              | [4e9b5b097e](https://linux-hardware.org/?probe=4e9b5b097e) | Apr 15, 2021 |
| Lenovo        | ThinkPad W540 20BHS20700    | [30edeadde3](https://linux-hardware.org/?probe=30edeadde3) | Apr 13, 2021 |
| Lenovo        | ThinkPad T460p 20FXS0220... | [3aef8ed384](https://linux-hardware.org/?probe=3aef8ed384) | Apr 11, 2021 |
| Lenovo        | ThinkPad E15 20RD0066TX     | [c3c1d01480](https://linux-hardware.org/?probe=c3c1d01480) | Apr 09, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [d4b7cef21b](https://linux-hardware.org/?probe=d4b7cef21b) | Apr 06, 2021 |
| HP            | Zbook 17 G2                 | [c974cb6fc7](https://linux-hardware.org/?probe=c974cb6fc7) | Apr 06, 2021 |
| Lenovo        | ThinkPad E15 20RD0066TX     | [3ab392c848](https://linux-hardware.org/?probe=3ab392c848) | Apr 05, 2021 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [4b9332ae3a](https://linux-hardware.org/?probe=4b9332ae3a) | Apr 05, 2021 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [d4a7fbec30](https://linux-hardware.org/?probe=d4a7fbec30) | Apr 01, 2021 |
| HP            | EliteBook 2540p             | [46c15e3b14](https://linux-hardware.org/?probe=46c15e3b14) | Apr 01, 2021 |
| LG Electro... | Z435-GE40K                  | [41dfc50f20](https://linux-hardware.org/?probe=41dfc50f20) | Mar 27, 2021 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [ba68c7c065](https://linux-hardware.org/?probe=ba68c7c065) | Mar 09, 2021 |
| Unknown       | Unknown                     | [fcc71c0314](https://linux-hardware.org/?probe=fcc71c0314) | Feb 13, 2021 |
| Acer          | Aspire V5-571G              | [6f498cb661](https://linux-hardware.org/?probe=6f498cb661) | Jan 27, 2021 |
| ASUSTek       | K54C                        | [ac91a40e03](https://linux-hardware.org/?probe=ac91a40e03) | Jan 24, 2021 |
| Sony          | VPCEG15FB                   | [badcac9c3d](https://linux-hardware.org/?probe=badcac9c3d) | Jan 17, 2021 |
| Lenovo        | V330-15IKB 81AX             | [48d877b127](https://linux-hardware.org/?probe=48d877b127) | Jan 07, 2021 |
| Acer          | Aspire V5-571G              | [a1499db9fc](https://linux-hardware.org/?probe=a1499db9fc) | Jan 07, 2021 |
| Acer          | Aspire V5-571G              | [7f0fa0a296](https://linux-hardware.org/?probe=7f0fa0a296) | Jan 07, 2021 |
| Acer          | Aspire 5750G                | [a448a76b2e](https://linux-hardware.org/?probe=a448a76b2e) | Jan 06, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [1ad69ae9c9](https://linux-hardware.org/?probe=1ad69ae9c9) | Jan 04, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [f13f9a9cdc](https://linux-hardware.org/?probe=f13f9a9cdc) | Dec 31, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [752f1e24cf](https://linux-hardware.org/?probe=752f1e24cf) | Dec 31, 2020 |
| Dell          | XPS L521X                   | [c109644955](https://linux-hardware.org/?probe=c109644955) | Dec 28, 2020 |
| Dell          | Latitude E7240              | [39e57b6b18](https://linux-hardware.org/?probe=39e57b6b18) | Dec 28, 2020 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [7038da6d94](https://linux-hardware.org/?probe=7038da6d94) | Dec 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [55e2883ca5](https://linux-hardware.org/?probe=55e2883ca5) | Dec 24, 2020 |
| Lenovo        | ThinkPad T460p 20FXS0220... | [048b297665](https://linux-hardware.org/?probe=048b297665) | Dec 23, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | [d87cdee8cb](https://linux-hardware.org/?probe=d87cdee8cb) | Dec 19, 2020 |
| Acer          | Aspire A715-75G             | [814f906095](https://linux-hardware.org/?probe=814f906095) | Dec 15, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [f050339a1d](https://linux-hardware.org/?probe=f050339a1d) | Dec 14, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [da43f75c0c](https://linux-hardware.org/?probe=da43f75c0c) | Dec 14, 2020 |
| ASUSTek       | X455LJ                      | [9938aa76cf](https://linux-hardware.org/?probe=9938aa76cf) | Dec 10, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | [9d12f4f222](https://linux-hardware.org/?probe=9d12f4f222) | Dec 10, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | [c26814bfc2](https://linux-hardware.org/?probe=c26814bfc2) | Dec 10, 2020 |
| ASUSTek       | X455LJ                      | [fa97344b41](https://linux-hardware.org/?probe=fa97344b41) | Dec 08, 2020 |
| Lenovo        | G70-70 80HW005XUK           | [a57125fe89](https://linux-hardware.org/?probe=a57125fe89) | Dec 07, 2020 |
| Acer          | Aspire V5-431P              | [831f0df544](https://linux-hardware.org/?probe=831f0df544) | Dec 03, 2020 |
| Dell          | Studio 1747                 | [dd0085228f](https://linux-hardware.org/?probe=dd0085228f) | Nov 29, 2020 |
| HP            | ZBook 15                    | [033521235f](https://linux-hardware.org/?probe=033521235f) | Nov 29, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | [c58ad8f5e8](https://linux-hardware.org/?probe=c58ad8f5e8) | Nov 28, 2020 |
| Lenovo        | ThinkPad X240 20AMS7XW00    | [b7783af763](https://linux-hardware.org/?probe=b7783af763) | Nov 19, 2020 |
| Sony          | VPCEH15FX                   | [cc8c7bc4c9](https://linux-hardware.org/?probe=cc8c7bc4c9) | Nov 19, 2020 |
| Acer          | Aspire V5-571G              | [f55cd22b43](https://linux-hardware.org/?probe=f55cd22b43) | Nov 18, 2020 |
| Acer          | Aspire V5-571G              | [b8d43abe6e](https://linux-hardware.org/?probe=b8d43abe6e) | Nov 18, 2020 |
| Acer          | Aspire V5-571G              | [49707be15c](https://linux-hardware.org/?probe=49707be15c) | Nov 16, 2020 |
| Dell          | Latitude 3440               | [17db1f31f6](https://linux-hardware.org/?probe=17db1f31f6) | Nov 13, 2020 |
| HP            | EliteBook 830 G6            | [0e0009bcfc](https://linux-hardware.org/?probe=0e0009bcfc) | Nov 13, 2020 |
| CompuLab      | fit-PC3                     | [2e92dc00d4](https://linux-hardware.org/?probe=2e92dc00d4) | Nov 12, 2020 |
| Lenovo        | ThinkPad T420 4238AB9       | [9c7ec388e0](https://linux-hardware.org/?probe=9c7ec388e0) | Nov 11, 2020 |
| ASUSTek       | X455LJ                      | [d0085b85ad](https://linux-hardware.org/?probe=d0085b85ad) | Nov 09, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [dbc5336b07](https://linux-hardware.org/?probe=dbc5336b07) | Nov 01, 2020 |
| Lenovo        | ThinkPad E590 20NBS03S00    | [29ae827508](https://linux-hardware.org/?probe=29ae827508) | Oct 29, 2020 |
| Unknown       | Unknown                     | [98cd8695de](https://linux-hardware.org/?probe=98cd8695de) | Oct 21, 2020 |
| Unknown       | Unknown                     | [a0e3328769](https://linux-hardware.org/?probe=a0e3328769) | Oct 21, 2020 |
| Sony          | VPCEG15FB                   | [aed7cd4193](https://linux-hardware.org/?probe=aed7cd4193) | Oct 20, 2020 |
| Sony          | VPCEG15FB                   | [3b5beb4162](https://linux-hardware.org/?probe=3b5beb4162) | Oct 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [50534bc0e0](https://linux-hardware.org/?probe=50534bc0e0) | Oct 01, 2020 |
| Lenovo        | ThinkPad X140e 20BL000BU... | [b00098bf37](https://linux-hardware.org/?probe=b00098bf37) | Sep 29, 2020 |
| ASUSTek       | X556UB                      | [15790fbe92](https://linux-hardware.org/?probe=15790fbe92) | Sep 28, 2020 |
| Timi          | TM1709                      | [9d4bd50d80](https://linux-hardware.org/?probe=9d4bd50d80) | Sep 25, 2020 |
| Gigabyte      | P35V3                       | [55580f63c2](https://linux-hardware.org/?probe=55580f63c2) | Sep 14, 2020 |
| Apple         | MacBookPro12,1              | [daceea1b39](https://linux-hardware.org/?probe=daceea1b39) | Sep 08, 2020 |
| Lenovo        | ThinkPad T430s 2356CZ4      | [585b5cd200](https://linux-hardware.org/?probe=585b5cd200) | Aug 22, 2020 |
| Lenovo        | ThinkPad T430s 2356CZ4      | [b16e78abbf](https://linux-hardware.org/?probe=b16e78abbf) | Aug 21, 2020 |
| Sony          | VPCEG15FB                   | [23685585c9](https://linux-hardware.org/?probe=23685585c9) | Aug 14, 2020 |
| HP            | ProBook 440 G2              | [b19e6b64a7](https://linux-hardware.org/?probe=b19e6b64a7) | Aug 07, 2020 |
| MSI           | GE73VR 7RF                  | [8f05f68c7d](https://linux-hardware.org/?probe=8f05f68c7d) | Aug 04, 2020 |
| HP            | Notebook                    | [00a853f189](https://linux-hardware.org/?probe=00a853f189) | Aug 01, 2020 |
| Sony          | VPCEG15FB                   | [a161c57e9f](https://linux-hardware.org/?probe=a161c57e9f) | Jul 29, 2020 |
| Samsung       | 270E5J/2570EJ               | [8907cdddd5](https://linux-hardware.org/?probe=8907cdddd5) | Jul 24, 2020 |
| Samsung       | R560                        | [4d35b24594](https://linux-hardware.org/?probe=4d35b24594) | Jul 23, 2020 |
| HP            | EliteBook 850 G3            | [529b5be1b5](https://linux-hardware.org/?probe=529b5be1b5) | Jul 14, 2020 |
| HP            | ProBook 640 G2              | [53ba25afcd](https://linux-hardware.org/?probe=53ba25afcd) | Jul 14, 2020 |
| HP            | ProBook 450 G0              | [8566dd2843](https://linux-hardware.org/?probe=8566dd2843) | Jul 11, 2020 |
| HP            | ProBook 450 G0              | [116cbdcf22](https://linux-hardware.org/?probe=116cbdcf22) | Jul 09, 2020 |
| Sony          | VPCEG15FB                   | [2fc3e05c67](https://linux-hardware.org/?probe=2fc3e05c67) | Jul 03, 2020 |
| HP            | EliteBook 840 G5            | [8c28479e2e](https://linux-hardware.org/?probe=8c28479e2e) | Jun 19, 2020 |
| HP            | Laptop 14-bp0xx             | [6efe053f69](https://linux-hardware.org/?probe=6efe053f69) | Jun 18, 2020 |
| HP            | Laptop 14-bp0xx             | [e1611d4a8f](https://linux-hardware.org/?probe=e1611d4a8f) | Jun 18, 2020 |
| Lenovo        | Z50-70 20354                | [765261db4d](https://linux-hardware.org/?probe=765261db4d) | Jun 17, 2020 |
| Lenovo        | Z50-70 20354                | [08a9f86f96](https://linux-hardware.org/?probe=08a9f86f96) | Jun 17, 2020 |
| Dell          | Inspiron 5570               | [3d59a7abfb](https://linux-hardware.org/?probe=3d59a7abfb) | Jun 14, 2020 |
| Dell          | Inspiron 3520               | [0fe6cc7ec2](https://linux-hardware.org/?probe=0fe6cc7ec2) | Jun 11, 2020 |
| Lenovo        | ThinkPad T480s 20L8002WM... | [4660651265](https://linux-hardware.org/?probe=4660651265) | Jun 09, 2020 |
| Sony          | VPCEG15FB                   | [54a9778aab](https://linux-hardware.org/?probe=54a9778aab) | May 30, 2020 |
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
| RM Educati... | RM                          | [9b2c6616dd](https://linux-hardware.org/?probe=9b2c6616dd) | Mar 03, 2020 |
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
| Dell          | Studio 1747                 | [57919c3018](https://linux-hardware.org/?probe=57919c3018) | Dec 02, 2019 |
| Dell          | Studio 1747                 | [24d64d118b](https://linux-hardware.org/?probe=24d64d118b) | Dec 02, 2019 |
| ASUSTek       | E202SA                      | [e052cf247b](https://linux-hardware.org/?probe=e052cf247b) | Nov 23, 2019 |
| Toshiba       | Satellite L15W-B            | [c96da5df5e](https://linux-hardware.org/?probe=c96da5df5e) | Nov 20, 2019 |
| Toshiba       | Satellite L15W-B            | [bf3a6bb4c3](https://linux-hardware.org/?probe=bf3a6bb4c3) | Nov 20, 2019 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [df76fe3ea4](https://linux-hardware.org/?probe=df76fe3ea4) | Nov 14, 2019 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [448a81eb7c](https://linux-hardware.org/?probe=448a81eb7c) | Nov 14, 2019 |
| HP            | Notebook                    | [4aae147ff7](https://linux-hardware.org/?probe=4aae147ff7) | Nov 01, 2019 |
| Sony          | VPCEH26EN                   | [28024462ac](https://linux-hardware.org/?probe=28024462ac) | Oct 22, 2019 |
| RM Educati... | RM                          | [4d22671841](https://linux-hardware.org/?probe=4d22671841) | Oct 03, 2019 |
| RM Educati... | RM                          | [4b2e9b1800](https://linux-hardware.org/?probe=4b2e9b1800) | Oct 02, 2019 |
| RM Educati... | RM                          | [43aad9067d](https://linux-hardware.org/?probe=43aad9067d) | Oct 02, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Notebooks | Percent |
|------------------------------|-----------|---------|
| 4.18.0-147.8.1.el8_1.x86_64  | 11        | 9.73%   |
| 4.18.0-193.6.3.el8_2.x86_64  | 10        | 8.85%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 9         | 7.96%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 7         | 6.19%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 7         | 6.19%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 7         | 6.19%   |
| 4.18.0-193.14.2.el8_2.x86_64 | 6         | 5.31%   |
| 4.18.0-305.3.1.el8.x86_64    | 4         | 3.54%   |
| 4.18.0-294.el8.x86_64        | 4         | 3.54%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 4         | 3.54%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 4         | 3.54%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 4         | 3.54%   |
| 4.18.0-305.12.1.el8_4.x86_64 | 3         | 2.65%   |
| 4.18.0-277.el8.x86_64        | 3         | 2.65%   |
| 4.18.0-193.el8.x86_64        | 3         | 2.65%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 3         | 2.65%   |
| 4.18.0-147.6.el8.x86_64      | 3         | 2.65%   |
| 4.18.0-80.el8.x86_64         | 2         | 1.77%   |
| 4.18.0-301.1.el8.x86_64      | 2         | 1.77%   |
| 4.18.0-240.el8.x86_64        | 2         | 1.77%   |
| 4.18.0-147.el8.x86_64        | 2         | 1.77%   |
| 5.9.12-1.el8.elrepo.x86_64   | 1         | 0.88%   |
| 5.9.1-1.el8.elrepo.x86_64    | 1         | 0.88%   |
| 5.8.11-1.el8.elrepo.x86_64   | 1         | 0.88%   |
| 5.13.7-1.el8.elrepo.x86_64   | 1         | 0.88%   |
| 4.18.0-80.7.1.el8_0.x86_64   | 1         | 0.88%   |
| 4.18.0-315.el8.x86_64        | 1         | 0.88%   |
| 4.18.0-305.7.1.el8_4.x86_64  | 1         | 0.88%   |
| 4.18.0-305.10.2.el8_4.x86_64 | 1         | 0.88%   |
| 4.18.0-259.el8.x86_64        | 1         | 0.88%   |
| 4.18.0-257.el8.x86_64        | 1         | 0.88%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 1         | 0.88%   |
| 4.18.0-177.el8.x86_64        | 1         | 0.88%   |
| 4.18.0-151.el8.x86_64        | 1         | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.0  | 97        | 96.04%  |
| 5.9.12  | 1         | 0.99%   |
| 5.9.1   | 1         | 0.99%   |
| 5.8.11  | 1         | 0.99%   |
| 5.13.7  | 1         | 0.99%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 97        | 96.04%  |
| 5.9     | 2         | 1.98%   |
| 5.8     | 1         | 0.99%   |
| 5.13    | 1         | 0.99%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 101       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 93        | 90.29%  |
| Unknown       | 3         | 2.91%   |
| MATE          | 2         | 1.94%   |
| GNOME Classic | 2         | 1.94%   |
| XFCE          | 1         | 0.97%   |
| KDE5          | 1         | 0.97%   |
| KDE           | 1         | 0.97%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 67        | 62.62%  |
| X11     | 36        | 33.64%  |
| Unknown | 3         | 2.8%    |
| Web     | 1         | 0.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 59        | 56.73%  |
| GDM     | 44        | 42.31%  |
| LightDM | 1         | 0.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 57        | 55.34%  |
| Unknown | 10        | 9.71%   |
| en_GB   | 9         | 8.74%   |
| de_DE   | 5         | 4.85%   |
| ru_RU   | 4         | 3.88%   |
| pt_BR   | 4         | 3.88%   |
| fr_FR   | 4         | 3.88%   |
| ko_KR   | 2         | 1.94%   |
| en_IN   | 2         | 1.94%   |
| es_PE   | 1         | 0.97%   |
| es_MX   | 1         | 0.97%   |
| es_AR   | 1         | 0.97%   |
| en_IE   | 1         | 0.97%   |
| en_CA   | 1         | 0.97%   |
| da_DK   | 1         | 0.97%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 62        | 60.19%  |
| BIOS | 41        | 39.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| Xfs  | 91        | 90.1%   |
| Ext4 | 9         | 8.91%   |
| Ext3 | 1         | 0.99%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 61        | 59.22%  |
| GPT     | 30        | 29.13%  |
| MBR     | 12        | 11.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 94        | 93.07%  |
| Yes       | 7         | 6.93%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 87        | 85.29%  |
| Yes       | 15        | 14.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 29        | 28.71%  |
| Hewlett-Packard        | 23        | 22.77%  |
| Dell                   | 15        | 14.85%  |
| ASUSTek Computer       | 7         | 6.93%   |
| Acer                   | 7         | 6.93%   |
| Samsung Electronics    | 4         | 3.96%   |
| Sony                   | 3         | 2.97%   |
| Unknown                | 2         | 1.98%   |
| Toshiba                | 1         | 0.99%   |
| Timi                   | 1         | 0.99%   |
| RM Education           | 1         | 0.99%   |
| MSI                    | 1         | 0.99%   |
| Medion                 | 1         | 0.99%   |
| LG Electronics         | 1         | 0.99%   |
| Gigabyte Technology    | 1         | 0.99%   |
| COPELION INTERNATIONAL | 1         | 0.99%   |
| CompuLab               | 1         | 0.99%   |
| Clevo                  | 1         | 0.99%   |
| Apple                  | 1         | 0.99%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Lenovo Z50-70 20354                               | 2         | 1.98%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK             | 2         | 1.98%   |
| HP Notebook                                       | 2         | 1.98%   |
| Dell Studio 1747                                  | 2         | 1.98%   |
| Unknown                                           | 2         | 1.98%   |
| Toshiba Satellite L15W-B                          | 1         | 0.99%   |
| Timi TM1709                                       | 1         | 0.99%   |
| Sony VPCEH26EN                                    | 1         | 0.99%   |
| Sony VPCEH15FX                                    | 1         | 0.99%   |
| Sony VPCEG15FB                                    | 1         | 0.99%   |
| Samsung R560                                      | 1         | 0.99%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B               | 1         | 0.99%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.99%   |
| Samsung 270E5J/2570EJ                             | 1         | 0.99%   |
| RM Education RM                                   | 1         | 0.99%   |
| MSI GE73VR 7RF                                    | 1         | 0.99%   |
| Medion P6622                                      | 1         | 0.99%   |
| LG Z435-GE40K                                     | 1         | 0.99%   |
| Lenovo V330-15IKB 81AX                            | 1         | 0.99%   |
| Lenovo ThinkPad X240 20AMS7XW00                   | 1         | 0.99%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS23S00          | 1         | 0.99%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A7CT01WW          | 1         | 0.99%   |
| Lenovo ThinkPad W540 20BHS20700                   | 1         | 0.99%   |
| Lenovo ThinkPad W540 20BG001KUK                   | 1         | 0.99%   |
| Lenovo ThinkPad T500 2242CTO                      | 1         | 0.99%   |
| Lenovo ThinkPad T490s 20NYS02900                  | 1         | 0.99%   |
| Lenovo ThinkPad T480s 20L8002WMX                  | 1         | 0.99%   |
| Lenovo ThinkPad T460p 20FXS02200                  | 1         | 0.99%   |
| Lenovo ThinkPad T440 20B7004JUS                   | 1         | 0.99%   |
| Lenovo ThinkPad T430s 2356CZ4                     | 1         | 0.99%   |
| Lenovo ThinkPad T420 4238AB9                      | 1         | 0.99%   |
| Lenovo ThinkPad P51 W10DG 20MNS08X00              | 1         | 0.99%   |
| Lenovo ThinkPad P50 20EN001PUS                    | 1         | 0.99%   |
| Lenovo ThinkPad E595 20NF0000GE                   | 1         | 0.99%   |
| Lenovo ThinkPad E590 20NBS03S00                   | 1         | 0.99%   |
| Lenovo ThinkPad E580 20KS001JRT                   | 1         | 0.99%   |
| Lenovo ThinkPad E490 20N8007NTX                   | 1         | 0.99%   |
| Lenovo ThinkPad E15 20RD0066TX                    | 1         | 0.99%   |
| Lenovo IdeaPad 500-15ISK 80NT                     | 1         | 0.99%   |
| Lenovo IdeaPad 330-14AST 81D5                     | 1         | 0.99%   |
| Lenovo IdeaPad 3 15IIL05 81WE                     | 1         | 0.99%   |
| Lenovo G70-70 80HW005XUK                          | 1         | 0.99%   |
| Lenovo B50-70 80EU                                | 1         | 0.99%   |
| HP Zbook 17 G2                                    | 1         | 0.99%   |
| HP ZBook 15 G6                                    | 1         | 0.99%   |
| HP ZBook 15                                       | 1         | 0.99%   |
| HP ProBook 640 G2                                 | 1         | 0.99%   |
| HP ProBook 450 G5                                 | 1         | 0.99%   |
| HP ProBook 450 G0                                 | 1         | 0.99%   |
| HP ProBook 440 G2                                 | 1         | 0.99%   |
| HP ProBook 430 G5                                 | 1         | 0.99%   |
| HP NOTEBOOKE 15-AY084TU                           | 1         | 0.99%   |
| HP Laptop 15-bs1xx                                | 1         | 0.99%   |
| HP Laptop 14-dq1xxx                               | 1         | 0.99%   |
| HP Laptop 14-bp0xx                                | 1         | 0.99%   |
| HP EliteBook Folio 9470m                          | 1         | 0.99%   |
| HP EliteBook 8740w                                | 1         | 0.99%   |
| HP EliteBook 8570w                                | 1         | 0.99%   |
| HP EliteBook 850 G3                               | 1         | 0.99%   |
| HP EliteBook 8440p                                | 1         | 0.99%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 19        | 18.81%  |
| HP EliteBook                  | 9         | 8.91%   |
| Lenovo IdeaPad                | 5         | 4.95%   |
| HP ProBook                    | 5         | 4.95%   |
| Dell Latitude                 | 5         | 4.95%   |
| Acer Aspire                   | 4         | 3.96%   |
| HP ZBook                      | 3         | 2.97%   |
| HP Laptop                     | 3         | 2.97%   |
| Dell XPS                      | 3         | 2.97%   |
| Dell Inspiron                 | 3         | 2.97%   |
| Lenovo Z50-70                 | 2         | 1.98%   |
| HP Notebook                   | 2         | 1.98%   |
| Dell Studio                   | 2         | 1.98%   |
| Dell Precision                | 2         | 1.98%   |
| Unknown                       | 2         | 1.98%   |
| Toshiba Satellite             | 1         | 0.99%   |
| Timi TM1709                   | 1         | 0.99%   |
| Sony VPCEH26EN                | 1         | 0.99%   |
| Sony VPCEH15FX                | 1         | 0.99%   |
| Sony VPCEG15FB                | 1         | 0.99%   |
| Samsung R560                  | 1         | 0.99%   |
| Samsung 700Z3A                | 1         | 0.99%   |
| Samsung 500R4K                | 1         | 0.99%   |
| Samsung 270E5J                | 1         | 0.99%   |
| RM Education RM               | 1         | 0.99%   |
| MSI GE73VR                    | 1         | 0.99%   |
| Medion P6622                  | 1         | 0.99%   |
| LG Z435-GE40K                 | 1         | 0.99%   |
| Lenovo V330-15IKB             | 1         | 0.99%   |
| Lenovo G70-70                 | 1         | 0.99%   |
| Lenovo B50-70                 | 1         | 0.99%   |
| HP NOTEBOOKE                  | 1         | 0.99%   |
| Gigabyte P35V3                | 1         | 0.99%   |
| COPELION INTERNATIONAL QX-350 | 1         | 0.99%   |
| CompuLab fit-PC3              | 1         | 0.99%   |
| Clevo P15xEMx                 | 1         | 0.99%   |
| ASUS ZenBook                  | 1         | 0.99%   |
| ASUS X556UB                   | 1         | 0.99%   |
| ASUS X550MJ                   | 1         | 0.99%   |
| ASUS X455LJ                   | 1         | 0.99%   |
| ASUS VivoBook                 | 1         | 0.99%   |
| ASUS K54C                     | 1         | 0.99%   |
| ASUS E202SA                   | 1         | 0.99%   |
| Apple MacBookPro12            | 1         | 0.99%   |
| Acer TravelMate               | 1         | 0.99%   |
| Acer One                      | 1         | 0.99%   |
| Acer Nitro                    | 1         | 0.99%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 23        | 22.77%  |
| 2020 | 15        | 14.85%  |
| 2012 | 13        | 12.87%  |
| 2015 | 12        | 11.88%  |
| 2014 | 8         | 7.92%   |
| 2016 | 7         | 6.93%   |
| 2018 | 6         | 5.94%   |
| 2011 | 6         | 5.94%   |
| 2021 | 4         | 3.96%   |
| 2017 | 3         | 2.97%   |
| 2013 | 2         | 1.98%   |
| 2010 | 1         | 0.99%   |
| 2008 | 1         | 0.99%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 101       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 91        | 90.1%   |
| Enabled  | 10        | 9.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 101       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 40        | 39.22%  |
| 16.01-24.0  | 19        | 18.63%  |
| 3.01-4.0    | 18        | 17.65%  |
| 32.01-64.0  | 13        | 12.75%  |
| 8.01-16.0   | 10        | 9.8%    |
| 64.01-256.0 | 1         | 0.98%   |
| 1.01-2.0    | 1         | 0.98%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 41        | 37.27%  |
| 4.01-8.0   | 21        | 19.09%  |
| 3.01-4.0   | 20        | 18.18%  |
| 1.01-2.0   | 18        | 16.36%  |
| 8.01-16.0  | 7         | 6.36%   |
| 0.51-1.0   | 2         | 1.82%   |
| 24.01-32.0 | 1         | 0.91%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 73        | 72.28%  |
| 2      | 22        | 21.78%  |
| 3      | 4         | 3.96%   |
| 4      | 2         | 1.98%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 59.41%  |
| Yes       | 41        | 40.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 89.11%  |
| No        | 11        | 10.89%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 99.01%  |
| No        | 1         | 0.99%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 82        | 81.19%  |
| No        | 19        | 18.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 19        | 18.63%  |
| Germany      | 9         | 8.82%   |
| UK           | 6         | 5.88%   |
| Sweden       | 5         | 4.9%    |
| India        | 5         | 4.9%    |
| Brazil       | 5         | 4.9%    |
| Russia       | 4         | 3.92%   |
| France       | 4         | 3.92%   |
| Belgium      | 4         | 3.92%   |
| Spain        | 3         | 2.94%   |
| Mexico       | 3         | 2.94%   |
| China        | 3         | 2.94%   |
| Turkey       | 2         | 1.96%   |
| South Korea  | 2         | 1.96%   |
| Peru         | 2         | 1.96%   |
| Netherlands  | 2         | 1.96%   |
| Indonesia    | 2         | 1.96%   |
| Canada       | 2         | 1.96%   |
| Austria      | 2         | 1.96%   |
| Vietnam      | 1         | 0.98%   |
| Ukraine      | 1         | 0.98%   |
| South Africa | 1         | 0.98%   |
| Puerto Rico  | 1         | 0.98%   |
| Morocco      | 1         | 0.98%   |
| Malaysia     | 1         | 0.98%   |
| Lithuania    | 1         | 0.98%   |
| Italy        | 1         | 0.98%   |
| Israel       | 1         | 0.98%   |
| Ireland      | 1         | 0.98%   |
| Greece       | 1         | 0.98%   |
| Egypt        | 1         | 0.98%   |
| Burkina Faso | 1         | 0.98%   |
| Bulgaria     | 1         | 0.98%   |
| Belarus      | 1         | 0.98%   |
| Bangladesh   | 1         | 0.98%   |
| Argentina    | 1         | 0.98%   |
| Afghanistan  | 1         | 0.98%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Sollentuna          | 2         | 1.9%    |
| S??o Paulo          | 2         | 1.9%    |
| Munich              | 2         | 1.9%    |
| Moscow              | 2         | 1.9%    |
| Mexico City         | 2         | 1.9%    |
| Lima                | 2         | 1.9%    |
| Hamburg             | 2         | 1.9%    |
| Denver              | 2         | 1.9%    |
| Chicago             | 2         | 1.9%    |
| Berlin              | 2         | 1.9%    |
| Yekaterinburg       | 1         | 0.95%   |
| Yangquan            | 1         | 0.95%   |
| Yangpu              | 1         | 0.95%   |
| Whitley Bay         | 1         | 0.95%   |
| Vireux-Molhain      | 1         | 0.95%   |
| Vilnius             | 1         | 0.95%   |
| Viladecans          | 1         | 0.95%   |
| Vancouver           | 1         | 0.95%   |
| Valatie             | 1         | 0.95%   |
| Utrecht             | 1         | 0.95%   |
| Upplands Vasby      | 1         | 0.95%   |
| Umbauba             | 1         | 0.95%   |
| Turnhout            | 1         | 0.95%   |
| Toronto             | 1         | 0.95%   |
| Tolosa              | 1         | 0.95%   |
| Thane               | 1         | 0.95%   |
| Tel Aviv            | 1         | 0.95%   |
| Tassin-la-Demi-Lune | 1         | 0.95%   |
| Springville         | 1         | 0.95%   |
| Southend-on-Sea     | 1         | 0.95%   |
| Sofia               | 1         | 0.95%   |
| Sheffield           | 1         | 0.95%   |
| Semarang            | 1         | 0.95%   |
| San Juan            | 1         | 0.95%   |
| San Antonio         | 1         | 0.95%   |
| Rethymno            | 1         | 0.95%   |
| Rennes              | 1         | 0.95%   |
| Rabat               | 1         | 0.95%   |
| Portland            | 1         | 0.95%   |
| Port Elizabeth      | 1         | 0.95%   |
| Plano               | 1         | 0.95%   |
| Piacenza            | 1         | 0.95%   |
| Phoenix             | 1         | 0.95%   |
| Petaling Jaya       | 1         | 0.95%   |
| Parnaiba            | 1         | 0.95%   |
| North Shields       | 1         | 0.95%   |
| Nivelles            | 1         | 0.95%   |
| New York            | 1         | 0.95%   |
| Minsk               | 1         | 0.95%   |
| Marylebone          | 1         | 0.95%   |
| Mandelbachtal       | 1         | 0.95%   |
| Lubbeek             | 1         | 0.95%   |
| Louisville          | 1         | 0.95%   |
| London              | 1         | 0.95%   |
| Leigh-on-Sea        | 1         | 0.95%   |
| Landskrona          | 1         | 0.95%   |
| Landeck             | 1         | 0.95%   |
| Kyiv                | 1         | 0.95%   |
| Kaunas              | 1         | 0.95%   |
| Kalispell           | 1         | 0.95%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Seagate                 | 20        | 23     | 15.15%  |
| Samsung Electronics     | 20        | 29     | 15.15%  |
| Toshiba                 | 12        | 14     | 9.09%   |
| WDC                     | 11        | 14     | 8.33%   |
| Unknown                 | 8         | 13     | 6.06%   |
| SanDisk                 | 8         | 9      | 6.06%   |
| Kingston                | 8         | 9      | 6.06%   |
| HGST                    | 6         | 7      | 4.55%   |
| Crucial                 | 5         | 6      | 3.79%   |
| SK Hynix                | 4         | 4      | 3.03%   |
| Intel                   | 4         | 4      | 3.03%   |
| Hitachi                 | 3         | 7      | 2.27%   |
| Union Memory            | 2         | 2      | 1.52%   |
| SPCC                    | 2         | 2      | 1.52%   |
| LITEON                  | 2         | 3      | 1.52%   |
| Lenovo                  | 2         | 3      | 1.52%   |
| XrayDisk                | 1         | 1      | 0.76%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.76%   |
| Transcend               | 1         | 2      | 0.76%   |
| SSD                     | 1         | 1      | 0.76%   |
| Silicon Motion          | 1         | 1      | 0.76%   |
| PNY                     | 1         | 1      | 0.76%   |
| PLEXTOR                 | 1         | 1      | 0.76%   |
| Micron Technology       | 1         | 1      | 0.76%   |
| LITEONIT                | 1         | 1      | 0.76%   |
| Lexar                   | 1         | 1      | 0.76%   |
| KIOXIA                  | 1         | 1      | 0.76%   |
| Biostar                 | 1         | 1      | 0.76%   |
| Apple                   | 1         | 1      | 0.76%   |
| A-DATA Technology       | 1         | 1      | 0.76%   |
| 980Plus                 | 1         | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                       | 4         | 2.94%   |
| Seagate ST1000LM035-1RK172 1TB               | 4         | 2.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 4         | 2.94%   |
| Unknown MMC Card  32GB                       | 3         | 2.21%   |
| Samsung NVMe SSD Drive 512GB                 | 3         | 2.21%   |
| Kingston SA400M8240G 240GB SSD               | 3         | 2.21%   |
| Seagate ST500LT012-1DG142 500GB              | 2         | 1.47%   |
| Seagate ST500LM012 HN-M500MBB 500GB          | 2         | 1.47%   |
| Sandisk NVMe SSD Drive 512GB                 | 2         | 1.47%   |
| Samsung NVMe SSD Drive 256GB                 | 2         | 1.47%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD         | 2         | 1.47%   |
| Kingston SA400S37120G 120GB SSD              | 2         | 1.47%   |
| Hitachi HTS547550A9E384 500GB                | 2         | 1.47%   |
| HGST HTS545050A7E380 500GB                   | 2         | 1.47%   |
| XrayDisk SSD 240GB                           | 1         | 0.74%   |
| WDC WDS500G2B0B-00YS70 500GB SSD             | 1         | 0.74%   |
| WDC WDS100T2B0A-00SM50 1TB SSD               | 1         | 0.74%   |
| WDC WD7500BPKX-22HPJT0 752GB                 | 1         | 0.74%   |
| WDC WD5000BEVT-00A0RT0 500GB                 | 1         | 0.74%   |
| WDC WD1600BEVT-75ZCT2 160GB                  | 1         | 0.74%   |
| WDC WD10SPZX-24Z10 1TB                       | 1         | 0.74%   |
| WDC WD10SPZX-22Z10T1 1TB                     | 1         | 0.74%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1         | 0.74%   |
| WDC WD10JPLX-00MBPT0 1TB                     | 1         | 0.74%   |
| WDC WD10JPCX-24UE4T0 1TB                     | 1         | 0.74%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB         | 1         | 0.74%   |
| Unknown SD02G  2GB                           | 1         | 0.74%   |
| Unknown MMC Card  976MB                      | 1         | 0.74%   |
| Unknown MMC Card  4GB                        | 1         | 0.74%   |
| Unknown MMC Card  33GB                       | 1         | 0.74%   |
| Unknown MMC Card  2GB                        | 1         | 0.74%   |
| Unknown MMC Card  1GB                        | 1         | 0.74%   |
| Union Memory UMIS RPJTJ256MED1OWX 256GB      | 1         | 0.74%   |
| Union Memory RPFTJ256PDD2MWX 256GB           | 1         | 0.74%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB | 1         | 0.74%   |
| Transcend TS128GMTS430S 128GB SSD            | 1         | 0.74%   |
| Toshiba THNSNH512GDNT 512GB SSD              | 1         | 0.74%   |
| Toshiba THNSNH128GCST 128GB SSD              | 1         | 0.74%   |
| Toshiba THNSNF128GCSS 128GB SSD              | 1         | 0.74%   |
| Toshiba MK5065GSX 500GB                      | 1         | 0.74%   |
| Toshiba MK5056GSY 500GB                      | 1         | 0.74%   |
| Toshiba MK1633GSG 160GB                      | 1         | 0.74%   |
| Toshiba KXG60ZNV1T02 KIOXIA 1TB              | 1         | 0.74%   |
| Toshiba HDWL120 2TB                          | 1         | 0.74%   |
| SSD SSD G2 series 64GB                       | 1         | 0.74%   |
| SPCC Solid State Disk 256GB                  | 1         | 0.74%   |
| SPCC M.2 SSD 240GB                           | 1         | 0.74%   |
| SK Hynix SC210 mSATA 256GB SSD               | 1         | 0.74%   |
| SK Hynix PC401 NVMe 512GB                    | 1         | 0.74%   |
| SK Hynix HFS128G39TNF-N3A0A 128GB SSD        | 1         | 0.74%   |
| SK Hynix HFM512GDJTNG-8310A 512GB            | 1         | 0.74%   |
| Silicon Motion NVMe SSD Drive 1TB            | 1         | 0.74%   |
| Seagate ST9750420AS 752GB                    | 1         | 0.74%   |
| Seagate ST500LM030-2E717D 500GB              | 1         | 0.74%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 0.74%   |
| Seagate ST500LM000-1EJ162 500GB              | 1         | 0.74%   |
| Seagate ST2000LM007-1R8174 2TB               | 1         | 0.74%   |
| Seagate ST1000LM014-SSHD-8GB                 | 1         | 0.74%   |
| Seagate ST1000LM014-1EJ164 1TB               | 1         | 0.74%   |
| Seagate M3 Portable 1TB                      | 1         | 0.74%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 19        | 22     | 43.18%  |
| WDC     | 8         | 11     | 18.18%  |
| Toshiba | 8         | 10     | 18.18%  |
| HGST    | 6         | 7      | 13.64%  |
| Hitachi | 3         | 7      | 6.82%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 20     | 25.45%  |
| Kingston            | 8         | 9      | 14.55%  |
| SanDisk             | 5         | 6      | 9.09%   |
| Crucial             | 4         | 5      | 7.27%   |
| Toshiba             | 3         | 3      | 5.45%   |
| Intel               | 3         | 3      | 5.45%   |
| WDC                 | 2         | 2      | 3.64%   |
| SPCC                | 2         | 2      | 3.64%   |
| SK Hynix            | 2         | 2      | 3.64%   |
| LITEON              | 2         | 3      | 3.64%   |
| XrayDisk            | 1         | 1      | 1.82%   |
| Transcend           | 1         | 2      | 1.82%   |
| SSD                 | 1         | 1      | 1.82%   |
| PNY                 | 1         | 1      | 1.82%   |
| PLEXTOR             | 1         | 1      | 1.82%   |
| LITEONIT            | 1         | 1      | 1.82%   |
| Lenovo              | 1         | 2      | 1.82%   |
| Biostar             | 1         | 1      | 1.82%   |
| Apple               | 1         | 1      | 1.82%   |
| A-DATA Technology   | 1         | 1      | 1.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 52        | 67     | 40%     |
| HDD     | 43        | 57     | 33.08%  |
| NVMe    | 25        | 26     | 19.23%  |
| MMC     | 8         | 13     | 6.15%   |
| Unknown | 2         | 2      | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 86        | 125    | 71.67%  |
| NVMe | 25        | 26     | 20.83%  |
| MMC  | 8         | 13     | 6.67%   |
| SAS  | 1         | 1      | 0.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 61        | 84     | 64.21%  |
| 0.51-1.0   | 28        | 34     | 29.47%  |
| 1.01-2.0   | 5         | 5      | 5.26%   |
| 3.01-4.0   | 1         | 1      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 27        | 26.73%  |
| 251-500        | 26        | 25.74%  |
| 501-1000       | 19        | 18.81%  |
| 51-100         | 7         | 6.93%   |
| 1001-2000      | 6         | 5.94%   |
| 21-50          | 5         | 4.95%   |
| Unknown        | 4         | 3.96%   |
| 1-20           | 3         | 2.97%   |
| More than 3000 | 2         | 1.98%   |
| 2001-3000      | 2         | 1.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 39        | 36.11%  |
| 21-50     | 26        | 24.07%  |
| 51-100    | 15        | 13.89%  |
| 101-250   | 11        | 10.19%  |
| 251-500   | 5         | 4.63%   |
| 501-1000  | 5         | 4.63%   |
| Unknown   | 4         | 3.7%    |
| 1001-2000 | 3         | 2.78%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB         | 2         | 3      | 33.33%  |
| Seagate ST9750420AS 752GB      | 1         | 1      | 16.67%  |
| Seagate ST1000LM014-1EJ164 1TB | 1         | 1      | 16.67%  |
| LITEON CV8-8E128-HP 128GB SSD  | 1         | 1      | 16.67%  |
| Hitachi HTS545032B9A302 320GB  | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 3      | 33.33%  |
| Seagate | 2         | 2      | 33.33%  |
| LITEON  | 1         | 1      | 16.67%  |
| Hitachi | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 3      | 40%     |
| Seagate | 2         | 2      | 40%     |
| Hitachi | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 6      | 83.33%  |
| SSD  | 1         | 1      | 16.67%  |

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
| Detected | 68        | 117    | 61.82%  |
| Works    | 35        | 40     | 31.82%  |
| Malfunc  | 6         | 7      | 5.45%   |
| Failed   | 1         | 1      | 0.91%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 91        | 74.59%  |
| Samsung Electronics          | 9         | 7.38%   |
| AMD                          | 6         | 4.92%   |
| Union Memory (Shenzhen)      | 3         | 2.46%   |
| Sandisk                      | 3         | 2.46%   |
| SK Hynix                     | 2         | 1.64%   |
| Toshiba America Info Systems | 1         | 0.82%   |
| Silicon Motion               | 1         | 0.82%   |
| Shenzhen Longsys Electronics | 1         | 0.82%   |
| Micron/Crucial Technology    | 1         | 0.82%   |
| Micron Technology            | 1         | 0.82%   |
| Marvell Technology Group     | 1         | 0.82%   |
| Lenovo                       | 1         | 0.82%   |
| KIOXIA                       | 1         | 0.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 12.8%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 8%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 9         | 7.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 8         | 6.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 4.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 4.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 4%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 4%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 4%      |
| AMD FCH SATA Controller [AHCI mode]                                              | 5         | 4%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 3.2%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 3         | 2.4%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 2.4%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.4%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 2.4%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 1.6%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 2         | 1.6%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.8%    |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.8%    |
| SK Hynix BC501 NVMe Solid State Drive                                            | 1         | 0.8%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.8%    |
| Shenzhen Longsys Non-Volatile memory controller                                  | 1         | 0.8%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.8%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.8%    |
| Sandisk PC SN520 NVMe SSD                                                        | 1         | 0.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.8%    |
| Samsung NVMe Controller                                                          | 1         | 0.8%    |
| Samsung Electronics SATA controller                                              | 1         | 0.8%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.8%    |
| Micron Non-Volatile memory controller                                            | 1         | 0.8%    |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 1         | 0.8%    |
| Lenovo Non-Volatile memory controller                                            | 1         | 0.8%    |
| KIOXIA Non-Volatile memory controller                                            | 1         | 0.8%    |
| Intel Volume Management Device NVMe RAID Controller                              | 1         | 0.8%    |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.8%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.8%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 1         | 0.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 1         | 0.8%    |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 1         | 0.8%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 91        | 73.98%  |
| NVMe | 24        | 19.51%  |
| RAID | 6         | 4.88%   |
| IDE  | 2         | 1.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 96        | 95.05%  |
| AMD    | 5         | 4.95%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 3.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 2.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.97%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 2.97%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 2.97%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 2.97%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 2.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.98%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 1.98%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 1.98%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.98%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 2         | 1.98%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.98%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.99%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.99%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.99%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.99%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.99%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.99%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.99%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.99%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.99%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.99%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 1         | 0.99%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.99%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 0.99%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 1         | 0.99%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.99%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.99%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.99%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 1         | 0.99%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.99%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.99%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 0.99%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 1         | 0.99%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 0.99%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.99%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.99%   |
| Intel Core i7 CPU Q 820 @ 1.73GHz             | 1         | 0.99%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 1         | 0.99%   |
| Intel Core i7 CPU M 640 @ 2.80GHz             | 1         | 0.99%   |
| Intel Core i7 CPU M 620 @ 2.67GHz             | 1         | 0.99%   |
| Intel Core i7 CPU L 640 @ 2.13GHz             | 1         | 0.99%   |
| Intel Core i5-9300HF CPU @ 2.40GHz            | 1         | 0.99%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1         | 0.99%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.99%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz            | 1         | 0.99%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.99%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 1         | 0.99%   |
| Intel Core i5-5257U CPU @ 2.70GHz             | 1         | 0.99%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.99%   |
| Intel Core i5-3437U CPU @ 1.90GHz             | 1         | 0.99%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 1         | 0.99%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.99%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 1         | 0.99%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 0.99%   |
| Intel Core i5-2467M CPU @ 1.60GHz             | 1         | 0.99%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.99%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i7    | 38        | 37.62%  |
| Intel Core i5    | 35        | 34.65%  |
| Intel Core i3    | 10        | 9.9%    |
| Intel Pentium    | 4         | 3.96%   |
| Intel Celeron    | 3         | 2.97%   |
| Other            | 2         | 1.98%   |
| Intel Core 2 Duo | 2         | 1.98%   |
| AMD Ryzen 7      | 2         | 1.98%   |
| Intel Xeon       | 1         | 0.99%   |
| Intel Core i9    | 1         | 0.99%   |
| AMD Ryzen 3      | 1         | 0.99%   |
| AMD G            | 1         | 0.99%   |
| AMD A4           | 1         | 0.99%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 57        | 56.44%  |
| 4      | 38        | 37.62%  |
| 6      | 5         | 4.95%   |
| 8      | 1         | 0.99%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 101       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 88        | 87.13%  |
| 1      | 13        | 12.87%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 100       | 98.04%  |
| Unknown        | 2         | 1.96%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x40651    | 10        | 9.71%   |
| 0x306a9    | 9         | 8.74%   |
| 0x206a7    | 9         | 8.74%   |
| 0x806ea    | 8         | 7.77%   |
| 0x306d4    | 8         | 7.77%   |
| 0x406e3    | 7         | 6.8%    |
| 0x306c3    | 6         | 5.83%   |
| 0x806ec    | 5         | 4.85%   |
| 0x20655    | 5         | 4.85%   |
| 0x506e3    | 4         | 3.88%   |
| Unknown    | 4         | 3.88%   |
| 0x906ea    | 3         | 2.91%   |
| 0x806e9    | 3         | 2.91%   |
| 0xa0652    | 2         | 1.94%   |
| 0x906ed    | 2         | 1.94%   |
| 0x906e9    | 2         | 1.94%   |
| 0x806c1    | 2         | 1.94%   |
| 0x706e5    | 2         | 1.94%   |
| 0x30678    | 2         | 1.94%   |
| 0x106e5    | 2         | 1.94%   |
| 0x406c3    | 1         | 0.97%   |
| 0x20652    | 1         | 0.97%   |
| 0x1067a    | 1         | 0.97%   |
| 0x10676    | 1         | 0.97%   |
| 0x08108109 | 1         | 0.97%   |
| 0x08108102 | 1         | 0.97%   |
| 0x06006705 | 1         | 0.97%   |
| 0x05000119 | 1         | 0.97%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| KabyLake    | 24        | 23.76%  |
| Haswell     | 16        | 15.84%  |
| Skylake     | 11        | 10.89%  |
| SandyBridge | 9         | 8.91%   |
| IvyBridge   | 9         | 8.91%   |
| Broadwell   | 8         | 7.92%   |
| Westmere    | 6         | 5.94%   |
| Zen+        | 3         | 2.97%   |
| Silvermont  | 3         | 2.97%   |
| TigerLake   | 2         | 1.98%   |
| Penryn      | 2         | 1.98%   |
| Nehalem     | 2         | 1.98%   |
| IceLake     | 2         | 1.98%   |
| CometLake   | 2         | 1.98%   |
| Excavator   | 1         | 0.99%   |
| Bobcat      | 1         | 0.99%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 85        | 62.5%   |
| Nvidia | 35        | 25.74%  |
| AMD    | 16        | 11.76%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 7.35%   |
| Intel UHD Graphics 620                                                                   | 9         | 6.62%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 5.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 5.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 5.15%   |
| Intel HD Graphics 5500                                                                   | 6         | 4.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 3.68%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.94%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 2.94%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 2.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 2.21%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 2.21%   |
| Intel HD Graphics 620                                                                    | 3         | 2.21%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 2.21%   |
| AMD Picasso                                                                              | 3         | 2.21%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 2         | 1.47%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 1.47%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 1.47%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 2         | 1.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 1.47%   |
| Intel HD Graphics 630                                                                    | 2         | 1.47%   |
| Intel HD Graphics 530                                                                    | 2         | 1.47%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.47%   |
| AMD RV730/M96 [Mobility Radeon HD 4650/5165]                                             | 2         | 1.47%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.74%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.74%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 1         | 0.74%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.74%   |
| Nvidia GP107GLM [Quadro P620]                                                            | 1         | 0.74%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                  | 1         | 0.74%   |
| Nvidia GM204M [GeForce GTX 980M]                                                         | 1         | 0.74%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.74%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.74%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 1         | 0.74%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 1         | 0.74%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 1         | 0.74%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 1         | 0.74%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 1         | 0.74%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 1         | 0.74%   |
| Nvidia GK104GLM [Quadro K3100M]                                                          | 1         | 0.74%   |
| Nvidia GF119M [GeForce 410M]                                                             | 1         | 0.74%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.74%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 1         | 0.74%   |
| Nvidia G92GLM [Quadro FX 2800M]                                                          | 1         | 0.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1         | 0.74%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 0.74%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.74%   |
| Intel Iris Graphics 6100                                                                 | 1         | 0.74%   |
| Intel HD Graphics P530                                                                   | 1         | 0.74%   |
| Intel HD Graphics                                                                        | 1         | 0.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 0.74%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 1         | 0.74%   |
| AMD Wimbledon XT [Radeon HD 7970M]                                                       | 1         | 0.74%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 1         | 0.74%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1         | 0.74%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 0.74%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 1         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 50        | 49.5%   |
| Intel + Nvidia | 27        | 26.73%  |
| 1 x Nvidia     | 8         | 7.92%   |
| Intel + AMD    | 8         | 7.92%   |
| 1 x AMD        | 8         | 7.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 95        | 94.06%  |
| Proprietary | 3         | 2.97%   |
| Unknown     | 3         | 2.97%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 55.34%  |
| 1.01-2.0   | 22        | 21.36%  |
| 3.01-4.0   | 13        | 12.62%  |
| 0.51-1.0   | 5         | 4.85%   |
| 0.01-0.5   | 5         | 4.85%   |
| 7.01-8.0   | 1         | 0.97%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 24        | 20.34%  |
| Chimei Innolux          | 19        | 16.1%   |
| LG Display              | 18        | 15.25%  |
| BOE                     | 15        | 12.71%  |
| Samsung Electronics     | 11        | 9.32%   |
| Dell                    | 6         | 5.08%   |
| Sharp                   | 3         | 2.54%   |
| Lenovo                  | 3         | 2.54%   |
| PANDA                   | 2         | 1.69%   |
| Panasonic               | 2         | 1.69%   |
| Hewlett-Packard         | 2         | 1.69%   |
| Goldstar                | 2         | 1.69%   |
| Acer                    | 2         | 1.69%   |
| Vizio                   | 1         | 0.85%   |
| Philips                 | 1         | 0.85%   |
| Onkyo                   | 1         | 0.85%   |
| MSI                     | 1         | 0.85%   |
| InfoVision              | 1         | 0.85%   |
| Gateway                 | 1         | 0.85%   |
| Chi Mei Optoelectronics | 1         | 0.85%   |
| Apple                   | 1         | 0.85%   |
| AOC                     | 1         | 0.85%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Panasonic VVX13F009G00 MEI96A2 1920x1080 290x170mm 13.2-inch          | 2         | 1.67%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.67%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch           | 2         | 1.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch        | 2         | 1.67%   |
| Vizio M320NV VIZ0070 1920x1080 700x390mm 31.5-inch                    | 1         | 0.83%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch               | 1         | 0.83%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.83%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.83%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 1         | 0.83%   |
| Samsung Electronics SMBX2450 SAM0721 1920x1080 530x300mm 24.0-inch    | 1         | 0.83%   |
| Samsung Electronics S22B420 SAM0979 1680x1050 473x291mm 21.9-inch     | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x170mm 13.9-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 344x194mm 15.5-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3848 1920x1200 367x230mm 17.1-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3646 1680x1050 331x207mm 15.4-inch | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC324C 1366x768 353x198mm 15.9-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SEC3147 1600x900 332x187mm 15.0-inch  | 1         | 0.83%   |
| Samsung Electronics LCD Monitor SDC364D 1920x1080 309x174mm 14.0-inch | 1         | 0.83%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 1         | 0.83%   |
| Philips PHL 278E9Q PHLC17F 1920x1080 598x336mm 27.0-inch              | 1         | 0.83%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 1         | 0.83%   |
| PANDA LCD Monitor NCP002A 1920x1080 344x194mm 15.5-inch               | 1         | 0.83%   |
| Onkyo AV Receiver ONK1151 1920x1080                                   | 1         | 0.83%   |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch               | 1         | 0.83%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD061C 1920x1080 294x165mm 13.3-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD05D5 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD05D1 1920x1080 344x194mm 15.5-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD0418 2560x1440 310x174mm 14.0-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD03FB 1920x1080 382x215mm 17.3-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD03D9 1366x768 350x190mm 15.7-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD03D2 1366x768 309x174mm 14.0-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD02CA 1366x768 345x194mm 15.6-inch           | 1         | 0.83%   |
| LG Display LCD Monitor LGD0259 1920x1080 350x190mm 15.7-inch          | 1         | 0.83%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch          | 1         | 0.83%   |
| Lenovo LEN P32u-10 LEN61C1 3840x2160 708x399mm 32.0-inch              | 1         | 0.83%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 1         | 0.83%   |
| Lenovo LCD Monitor LEN4057 1280x800 331x207mm 15.4-inch               | 1         | 0.83%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch           | 1         | 0.83%   |
| Hewlett-Packard ZR2440w HWP2955 1920x1080 520x320mm 24.0-inch         | 1         | 0.83%   |
| Hewlett-Packard LP3065 HWP2690 2560x1600 640x400mm 29.7-inch          | 1         | 0.83%   |
| Hewlett-Packard 25xw HWP3192 1920x1080 553x309mm 24.9-inch            | 1         | 0.83%   |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                  | 1         | 0.83%   |
| Goldstar W2240 GSM57A1 1920x1080 477x268mm 21.5-inch                  | 1         | 0.83%   |
| Gateway FPD2185W GWY0889 1680x1050 450x280mm 20.9-inch                | 1         | 0.83%   |
| Dell U2414H DELA0A4 1920x1080 530x300mm 24.0-inch                     | 1         | 0.83%   |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                    | 1         | 0.83%   |
| Dell SE2416H DELD082 1920x1080 527x296mm 23.8-inch                    | 1         | 0.83%   |
| Dell SE2216H DELF071 1920x1080 476x268mm 21.5-inch                    | 1         | 0.83%   |
| Dell P2314H DEL4099 1920x1080 510x290mm 23.1-inch                     | 1         | 0.83%   |
| Dell E177FP DELA023 1280x1024 338x270mm 17.0-inch                     | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch      | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch       | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 1         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 1         | 0.83%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 51        | 45.95%  |
| 1366x768 (WXGA)    | 34        | 30.63%  |
| 1600x900 (HD+)     | 8         | 7.21%   |
| 3840x2160 (4K)     | 4         | 3.6%    |
| 1680x1050 (WSXGA+) | 4         | 3.6%    |
| 2560x1600          | 2         | 1.8%    |
| 1920x1200 (WUXGA)  | 2         | 1.8%    |
| 1280x800 (WXGA)    | 2         | 1.8%    |
| 1280x1024 (SXGA)   | 2         | 1.8%    |
| 3440x1440          | 1         | 0.9%    |
| 2560x1440 (QHD)    | 1         | 0.9%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 53        | 44.54%  |
| 13      | 16        | 13.45%  |
| 14      | 12        | 10.08%  |
| 17      | 10        | 8.4%    |
| 24      | 5         | 4.2%    |
| 23      | 4         | 3.36%   |
| 12      | 4         | 3.36%   |
| 27      | 3         | 2.52%   |
| 21      | 3         | 2.52%   |
| 11      | 2         | 1.68%   |
| Unknown | 2         | 1.68%   |
| 42      | 1         | 0.84%   |
| 34      | 1         | 0.84%   |
| 32      | 1         | 0.84%   |
| 29      | 1         | 0.84%   |
| 20      | 1         | 0.84%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 76        | 64.96%  |
| 501-600     | 10        | 8.55%   |
| 351-400     | 10        | 8.55%   |
| 201-300     | 9         | 7.69%   |
| 401-500     | 5         | 4.27%   |
| 701-800     | 2         | 1.71%   |
| 601-700     | 2         | 1.71%   |
| Unknown     | 2         | 1.71%   |
| 901-1000    | 1         | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 92        | 87.62%  |
| 16/10   | 8         | 7.62%   |
| 5/4     | 2         | 1.9%    |
| 3/2     | 1         | 0.95%   |
| 21/9    | 1         | 0.95%   |
| Unknown | 1         | 0.95%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 52        | 43.33%  |
| 81-90          | 26        | 21.67%  |
| 201-250        | 10        | 8.33%   |
| 121-130        | 7         | 5.83%   |
| 61-70          | 4         | 3.33%   |
| 351-500        | 3         | 2.5%    |
| 301-350        | 3         | 2.5%    |
| 71-80          | 2         | 1.67%   |
| 51-60          | 2         | 1.67%   |
| 251-300        | 2         | 1.67%   |
| 151-200        | 2         | 1.67%   |
| 141-150        | 2         | 1.67%   |
| Unknown        | 2         | 1.67%   |
| 131-140        | 1         | 0.83%   |
| 501-1000       | 1         | 0.83%   |
| 91-100         | 1         | 0.83%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 56        | 47.46%  |
| 101-120       | 33        | 27.97%  |
| 51-100        | 21        | 17.8%   |
| More than 240 | 3         | 2.54%   |
| 161-240       | 3         | 2.54%   |
| Unknown       | 2         | 1.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 83        | 79.81%  |
| 2     | 17        | 16.35%  |
| 3     | 2         | 1.92%   |
| 0     | 2         | 1.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 58        | 37.42%  |
| Realtek Semiconductor             | 56        | 36.13%  |
| Qualcomm Atheros                  | 23        | 14.84%  |
| Broadcom                          | 5         | 3.23%   |
| Ralink                            | 2         | 1.29%   |
| Broadcom Limited                  | 2         | 1.29%   |
| Xiaomi                            | 1         | 0.65%   |
| Sierra Wireless                   | 1         | 0.65%   |
| Ralink Technology                 | 1         | 0.65%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.65%   |
| Marvell Technology Group          | 1         | 0.65%   |
| Ericsson Business Mobile Networks | 1         | 0.65%   |
| Dell                              | 1         | 0.65%   |
| D-Link                            | 1         | 0.65%   |
| ASIX Electronics                  | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 42        | 21%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 4.5%    |
| Intel Wireless 7260                                               | 9         | 4.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 3%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 2.5%    |
| Intel Wireless 8265 / 8275                                        | 5         | 2.5%    |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2%      |
| Intel Wireless 8260                                               | 4         | 2%      |
| Intel Wireless 7265                                               | 4         | 2%      |
| Intel Ethernet Connection I218-LM                                 | 4         | 2%      |
| Intel Ethernet Connection I217-LM                                 | 4         | 2%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 1.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 1.5%    |
| Intel Centrino Ultimate-N 6300                                    | 3         | 1.5%    |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.5%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 1%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 1%      |
| Intel Wireless-AC 9260                                            | 2         | 1%      |
| Intel Wireless 3165                                               | 2         | 1%      |
| Intel Wi-Fi 6 AX201                                               | 2         | 1%      |
| Intel Ethernet Connection I219-LM                                 | 2         | 1%      |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1%      |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1%      |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1%      |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1%      |
| Intel Centrino Advanced-N 6235                                    | 2         | 1%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 1%      |
| Intel Centrino Advanced-N 6200                                    | 2         | 1%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1%      |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1%      |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.5%    |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.5%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.5%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                   | 1         | 0.5%    |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 1         | 0.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.5%    |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.5%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.5%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.5%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 1         | 0.5%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.5%    |
| OnePlus (Shenzhen) IN2013                                         | 1         | 0.5%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.5%    |
| Intel Wireless 3160                                               | 1         | 0.5%    |
| Intel WiFi Link 5100                                              | 1         | 0.5%    |
| Intel Ultimate N WiFi Link 5300                                   | 1         | 0.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 1         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 57        | 54.81%  |
| Qualcomm Atheros      | 19        | 18.27%  |
| Realtek Semiconductor | 17        | 16.35%  |
| Broadcom              | 4         | 3.85%   |
| Ralink                | 2         | 1.92%   |
| Broadcom Limited      | 2         | 1.92%   |
| Ralink Technology     | 1         | 0.96%   |
| Dell                  | 1         | 0.96%   |
| D-Link                | 1         | 0.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                  | 9         | 8.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 6         | 5.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 5         | 4.81%   |
| Intel Wireless 8265 / 8275                                           | 5         | 4.81%   |
| Intel Wi-Fi 6 AX200                                                  | 5         | 4.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 4         | 3.85%   |
| Intel Wireless 8260                                                  | 4         | 3.85%   |
| Intel Wireless 7265                                                  | 4         | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 3         | 2.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 3         | 2.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 3         | 2.88%   |
| Intel Centrino Ultimate-N 6300                                       | 3         | 2.88%   |
| Realtek RTL8723DE Wireless Network Adapter                           | 2         | 1.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 2         | 1.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 2         | 1.92%   |
| Intel Wireless-AC 9260                                               | 2         | 1.92%   |
| Intel Wireless 3165                                                  | 2         | 1.92%   |
| Intel Wi-Fi 6 AX201                                                  | 2         | 1.92%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 1.92%   |
| Intel Centrino Advanced-N 6235                                       | 2         | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 2         | 1.92%   |
| Intel Centrino Advanced-N 6200                                       | 2         | 1.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 2         | 1.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 2         | 1.92%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 1         | 0.96%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 0.96%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 1         | 0.96%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 1         | 0.96%   |
| Realtek RTL8191SEvB Wireless LAN Controller                          | 1         | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 1         | 0.96%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 1         | 0.96%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 1         | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 1         | 0.96%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 1         | 0.96%   |
| Intel Wireless 3160                                                  | 1         | 0.96%   |
| Intel WiFi Link 5100                                                 | 1         | 0.96%   |
| Intel Ultimate N WiFi Link 5300                                      | 1         | 0.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 1         | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 1         | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 1         | 0.96%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 1         | 0.96%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                        | 1         | 0.96%   |
| Dell DW5811e Snapdragon???�?? X7 LTE                                 | 1         | 0.96%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 1         | 0.96%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                              | 1         | 0.96%   |
| Broadcom Limited BCM43142 802.11b/g/n                                | 1         | 0.96%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 1         | 0.96%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 1         | 0.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 52        | 55.32%  |
| Intel                         | 30        | 31.91%  |
| Qualcomm Atheros              | 6         | 6.38%   |
| Xiaomi                        | 1         | 1.06%   |
| Sierra Wireless               | 1         | 1.06%   |
| OnePlus Technology (Shenzhen) | 1         | 1.06%   |
| Marvell Technology Group      | 1         | 1.06%   |
| Broadcom                      | 1         | 1.06%   |
| ASIX Electronics              | 1         | 1.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 42        | 44.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 9.47%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 4.21%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 4.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.21%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 3.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 2.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 2.11%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 2.11%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.11%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 2.11%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 2.11%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 2.11%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 2.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.05%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 1.05%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.05%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 1.05%   |
| OnePlus (Shenzhen) IN2013                                         | 1         | 1.05%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 1.05%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (11) I219-LM                            | 1         | 1.05%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.05%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.05%   |
| ASIX AX88772                                                      | 1         | 1.05%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 100       | 52.36%  |
| Ethernet | 90        | 47.12%  |
| Modem    | 1         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 88        | 55.7%   |
| Ethernet | 69        | 43.67%  |
| Modem    | 1         | 0.63%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 87        | 86.14%  |
| 1     | 14        | 13.86%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 92        | 91.09%  |
| Yes  | 9         | 8.91%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 47.62%  |
| Qualcomm Atheros Communications | 16        | 19.05%  |
| Realtek Semiconductor           | 13        | 15.48%  |
| Broadcom                        | 5         | 5.95%   |
| Hewlett-Packard                 | 2         | 2.38%   |
| Cambridge Silicon Radio         | 2         | 2.38%   |
| Toshiba                         | 1         | 1.19%   |
| Ralink                          | 1         | 1.19%   |
| Lite-On Technology              | 1         | 1.19%   |
| IMC Networks                    | 1         | 1.19%   |
| Foxconn / Hon Hai               | 1         | 1.19%   |
| Apple                           | 1         | 1.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 27        | 32.14%  |
| Realtek Bluetooth Radio                             | 8         | 9.52%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 7.14%   |
| Intel Bluetooth wireless interface                  | 6         | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 3.57%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 3.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 3.57%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 2.38%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 2.38%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 2.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.38%   |
| Toshiba Bluetooth Radio                             | 1         | 1.19%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 1.19%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.19%   |
| Realtek RTL8723A Bluetooth                          | 1         | 1.19%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.19%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 1.19%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 1.19%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.19%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.19%   |
| IMC Networks Bluetooth Device                       | 1         | 1.19%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.19%   |
| Broadcom HP Portable SoftSailing                    | 1         | 1.19%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1         | 1.19%   |
| Broadcom BCM20702A0                                 | 1         | 1.19%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 1.19%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 1.19%   |
| Apple Bluetooth Host Controller                     | 1         | 1.19%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 95        | 77.24%  |
| Nvidia                   | 15        | 12.2%   |
| AMD                      | 8         | 6.5%    |
| GN Netcom                | 2         | 1.63%   |
| Tenx Technology          | 1         | 0.81%   |
| Plantronics              | 1         | 0.81%   |
| Asahi Kasei Microsystems | 1         | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 12%     |
| Intel 8 Series HD Audio Controller                                                                | 10        | 6.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 6.67%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 6%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 5.33%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 5.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 5.33%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 4%      |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 3.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 2.67%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 2.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 2.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 2.67%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 3         | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2%      |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 3         | 2%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2         | 1.33%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.33%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.33%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.33%   |
| Tenx Technology USB AUDIO                                                                         | 1         | 0.67%   |
| Plantronics Calisto 800 Series                                                                    | 1         | 0.67%   |
| Plantronics Blackwire C210                                                                        | 1         | 0.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.67%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.67%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.67%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.67%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.67%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.67%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.67%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.67%   |
| GN Netcom Jabra Link 370                                                                          | 1         | 0.67%   |
| GN Netcom Jabra EVOLVE 20 MS                                                                      | 1         | 0.67%   |
| Asahi Kasei Microsystems AK5370 I/F A/D Converter                                                 | 1         | 0.67%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.67%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.67%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.67%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 15        | 28.3%   |
| Samsung Electronics | 12        | 22.64%  |
| Kingston            | 10        | 18.87%  |
| Unknown             | 4         | 7.55%   |
| Micron Technology   | 3         | 5.66%   |
| A-DATA Technology   | 3         | 5.66%   |
| Elpida              | 2         | 3.77%   |
| Ramaxel Technology  | 1         | 1.89%   |
| Nanya Technology    | 1         | 1.89%   |
| Crucial             | 1         | 1.89%   |
| Corsair             | 1         | 1.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s           | 2         | 3.57%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s          | 2         | 3.57%   |
| Unknown SODIMM 4GB SODIMM DDR2 667MT/s                          | 1         | 1.79%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.79%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                  | 1         | 1.79%   |
| Unknown RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s | 1         | 1.79%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s                    | 1         | 1.79%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                 | 1         | 1.79%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 1         | 1.79%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 2667MT/s                   | 1         | 1.79%   |
| SK Hynix RAM HMT851S6AMR6R-PB N0 4096MB Chip DDR3 1600MT/s      | 1         | 1.79%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.79%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.79%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.79%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.79%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s          | 1         | 1.79%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s       | 1         | 1.79%   |
| SK Hynix RAM HMT125S6AFP8C-G7 2048MB SODIMM DDR3 1066MT/s       | 1         | 1.79%   |
| SK Hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s          | 1         | 1.79%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s      | 1         | 1.79%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s          | 1         | 1.79%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s        | 1         | 1.79%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.79%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.79%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 2667MT/s           | 1         | 1.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s     | 1         | 1.79%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 2667MT/s        | 1         | 1.79%   |
| Samsung RAM M471A5143DB0-CPB 4096MB SODIMM DDR4 2133MT/s        | 1         | 1.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s           | 1         | 1.79%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 1.79%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s       | 1         | 1.79%   |
| Nanya RAM NT2GC64B8HC0NS-CG 2GB SODIMM DDR3 1334MT/s            | 1         | 1.79%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s   | 1         | 1.79%   |
| Micron RAM 8ATF1G64HZ-2G6D1 8GB SODIMM DDR4 2667MT/s            | 1         | 1.79%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s           | 1         | 1.79%   |
| Kingston RAM Module 4GB SODIMM DDR3 1600MT/s                    | 1         | 1.79%   |
| Kingston RAM ACR26D4S9S8HJ-8 8GB SODIMM DDR4 2667MT/s           | 1         | 1.79%   |
| Kingston RAM ACR16D3LS1KNG/4G 4096MB SODIMM DDR3 1600MT/s       | 1         | 1.79%   |
| Kingston RAM 99U5704-001.A00G 4GB SODIMM DDR4 2400MT/s          | 1         | 1.79%   |
| Kingston RAM 99U5663-007.A00G 16GB SODIMM DDR4 2667MT/s         | 1         | 1.79%   |
| Kingston RAM 99U5663-003.A00G 16384MB SODIMM DDR4 2400MT/s      | 1         | 1.79%   |
| Kingston RAM 99U5469-041.A00LF 4GB SODIMM DDR3 1600MT/s         | 1         | 1.79%   |
| Kingston RAM 99U5428-101.A00LF 8GB SODIMM DDR3 1600MT/s         | 1         | 1.79%   |
| Kingston RAM 9905744-006.A00G 16GB SODIMM DDR4 2667MT/s         | 1         | 1.79%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s         | 1         | 1.79%   |
| Kingston RAM 9905428-087.A00G 8192MB SODIMM DDR3 1600MT/s       | 1         | 1.79%   |
| Kingston RAM 9905428-043.A00LF 4GB SODIMM DDR3 1334MT/s         | 1         | 1.79%   |
| Elpida RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.79%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s        | 1         | 1.79%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s         | 1         | 1.79%   |
| Corsair RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 1.79%   |
| A-DATA RAM Module 8192MB SODIMM DDR4 2400MT/s                   | 1         | 1.79%   |
| A-DATA RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.79%   |
| A-DATA RAM AO1L16BC4R1-BX7S 4096MB SODIMM DDR3 1600MT/s         | 1         | 1.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 23        | 50%     |
| DDR4   | 20        | 43.48%  |
| LPDDR4 | 1         | 2.17%   |
| LPDDR3 | 1         | 2.17%   |
| DDR2   | 1         | 2.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 42        | 91.3%   |
| Row Of Chips | 3         | 6.52%   |
| Chip         | 1         | 2.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 21        | 43.75%  |
| 8192  | 15        | 31.25%  |
| 16384 | 7         | 14.58%  |
| 2048  | 5         | 10.42%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 15        | 31.25%  |
| 1600  | 15        | 31.25%  |
| 2133  | 4         | 8.33%   |
| 1333  | 4         | 8.33%   |
| 2400  | 3         | 6.25%   |
| 1334  | 3         | 6.25%   |
| 4267  | 1         | 2.08%   |
| 1067  | 1         | 2.08%   |
| 1066  | 1         | 2.08%   |
| 667   | 1         | 2.08%   |

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
| Chicony Electronics                    | 30        | 33.71%  |
| Microdia                               | 12        | 13.48%  |
| Acer                                   | 10        | 11.24%  |
| Lite-On Technology                     | 7         | 7.87%   |
| IMC Networks                           | 6         | 6.74%   |
| Realtek Semiconductor                  | 4         | 4.49%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 4.49%   |
| Sunplus Innovation Technology          | 3         | 3.37%   |
| Quanta                                 | 3         | 3.37%   |
| Syntek                                 | 2         | 2.25%   |
| Silicon Motion                         | 2         | 2.25%   |
| Microsoft                              | 2         | 2.25%   |
| Suyin                                  | 1         | 1.12%   |
| Sunplus Technology                     | 1         | 1.12%   |
| Intel                                  | 1         | 1.12%   |
| Alcor Micro                            | 1         | 1.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 5         | 5.62%   |
| Acer Integrated Camera                                                   | 4         | 4.49%   |
| Microdia Integrated_Webcam_HD                                            | 3         | 3.37%   |
| Lite-On Integrated Camera                                                | 3         | 3.37%   |
| Lite-On HP HD Camera                                                     | 3         | 3.37%   |
| IMC Networks Integrated Camera                                           | 3         | 3.37%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 3         | 3.37%   |
| Chicony Integrated Camera (1280x720@30)                                  | 3         | 3.37%   |
| Chicony HP TrueVision HD                                                 | 3         | 3.37%   |
| Chicony HP HD Camera                                                     | 3         | 3.37%   |
| Acer Lenovo EasyCamera                                                   | 3         | 3.37%   |
| Microdia Laptop_Integrated_Webcam_HD                                     | 2         | 2.25%   |
| Microdia Laptop_Integrated_Webcam_2M                                     | 2         | 2.25%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 2         | 2.25%   |
| Chicony HP Webcam [2 MP Macro]                                           | 2         | 2.25%   |
| Chicony HP HD Webcam                                                     | 2         | 2.25%   |
| Chicony HD WebCam                                                        | 2         | 2.25%   |
| Syntek USB2.0 UVC PC Camera                                              | 1         | 1.12%   |
| Syntek Lenovo EasyCamera                                                 | 1         | 1.12%   |
| Suyin Sony Visual Communication Camera                                   | 1         | 1.12%   |
| Sunplus 1.3M WebCam                                                      | 1         | 1.12%   |
| Sunplus USB Video Device                                                 | 1         | 1.12%   |
| Sunplus Integrated_Webcam_FHD                                            | 1         | 1.12%   |
| Sunplus HD WebCam                                                        | 1         | 1.12%   |
| Silicon Motion WebCam SC-13HDL11431N                                     | 1         | 1.12%   |
| Silicon Motion ATIV VGA Camera                                           | 1         | 1.12%   |
| Realtek USB Camera                                                       | 1         | 1.12%   |
| Realtek Integrated Webcam                                                | 1         | 1.12%   |
| Realtek HD Webcam - Realtek                                              | 1         | 1.12%   |
| Realtek HD Webcam                                                        | 1         | 1.12%   |
| Quanta HP TrueVision HD Camera                                           | 1         | 1.12%   |
| Quanta HD Webcam                                                         | 1         | 1.12%   |
| Quanta HD User Facing                                                    | 1         | 1.12%   |
| Microsoft LifeCam VX-500 [1357]                                          | 1         | 1.12%   |
| Microsoft LifeCam HD-3000                                                | 1         | 1.12%   |
| Microdia Webcam SC-10HDD12636P                                           | 1         | 1.12%   |
| Microdia Sony Visual Communication Camera                                | 1         | 1.12%   |
| Microdia Laptop_Integrated_Webcam_1.3M                                   | 1         | 1.12%   |
| Microdia Integrated Webcam                                               | 1         | 1.12%   |
| Microdia ACR010 USB Webcam                                               | 1         | 1.12%   |
| Lite-On HP HD Webcam                                                     | 1         | 1.12%   |
| Intel RealSense 3D Camera (Front F200)                                   | 1         | 1.12%   |
| IMC Networks EasyCamera                                                  | 1         | 1.12%   |
| Chicony USB2.0 Camera                                                    | 1         | 1.12%   |
| Chicony USB 2.0 Camera                                                   | 1         | 1.12%   |
| Chicony TOSHIBA Web Camera - HD                                          | 1         | 1.12%   |
| Chicony Sony Visual Communication Camera                                 | 1         | 1.12%   |
| Chicony HP TrueVision HD Camera                                          | 1         | 1.12%   |
| Chicony HP HD Webcam [Fixed]                                             | 1         | 1.12%   |
| Chicony HP Full-HD Camera                                                | 1         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam             | 1         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                            | 1         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                         | 1         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 1         | 1.12%   |
| Alcor Micro Asus Integrated Webcam                                       | 1         | 1.12%   |
| Acer ThinkPad P50 Integrated Camera                                      | 1         | 1.12%   |
| Acer HP Webcam [2 MP Macro]                                              | 1         | 1.12%   |
| Acer BisonCam, NB Pro                                                    | 1         | 1.12%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 18        | 60%     |
| Synaptics                  | 6         | 20%     |
| Upek                       | 2         | 6.67%   |
| Elan Microelectronics      | 2         | 6.67%   |
| Shenzhen Goodix Technology | 1         | 3.33%   |
| AuthenTec                  | 1         | 3.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 7         | 23.33%  |
| Validity Sensors VFS451 Fingerprint Reader             | 3         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 10%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 2         | 6.67%   |
| Validity Sensors VFS491                                | 2         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 6.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 2         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 6.67%   |
| Elan ELAN:Fingerprint                                  | 2         | 6.67%   |
| Validity Sensors Synaptics WBDI                        | 1         | 3.33%   |
| Synaptics  WBDI                                        | 1         | 3.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 3.33%   |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 3.33%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 3.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 80%     |
| Alcor Micro | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 2         | 40%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 51        | 50.5%   |
| 1     | 45        | 44.55%  |
| 2     | 3         | 2.97%   |
| 6     | 1         | 0.99%   |
| 3     | 1         | 0.99%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 30        | 51.72%  |
| Graphics card            | 9         | 15.52%  |
| Net/wireless             | 6         | 10.34%  |
| Multimedia controller    | 3         | 5.17%   |
| Chipcard                 | 3         | 5.17%   |
| Bluetooth                | 2         | 3.45%   |
| Storage                  | 1         | 1.72%   |
| Sound                    | 1         | 1.72%   |
| Net/ethernet             | 1         | 1.72%   |
| Communication controller | 1         | 1.72%   |
| Camera                   | 1         | 1.72%   |

