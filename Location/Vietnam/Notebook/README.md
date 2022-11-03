Linux in Vietnam - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Vietnam.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 333

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E5430 non-vPro     | [70a0354dba](https://linux-hardware.org/?probe=70a0354dba) | Oct 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| Acer          | Aspire 4739Z                | [b85222f02c](https://linux-hardware.org/?probe=b85222f02c) | Oct 09, 2022 |
| Dell          | Inspiron 13 5310            | [128725bb4d](https://linux-hardware.org/?probe=128725bb4d) | Oct 04, 2022 |
| Dell          | Latitude E7240              | [84ce32d994](https://linux-hardware.org/?probe=84ce32d994) | Oct 03, 2022 |
| Dell          | Vostro 3500                 | [396f61d294](https://linux-hardware.org/?probe=396f61d294) | Oct 03, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [403aa5af3e](https://linux-hardware.org/?probe=403aa5af3e) | Oct 01, 2022 |
| Dell          | Vostro 5568                 | [44bf0dbbce](https://linux-hardware.org/?probe=44bf0dbbce) | Oct 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [a31db51878](https://linux-hardware.org/?probe=a31db51878) | Sep 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2f16f0177f](https://linux-hardware.org/?probe=2f16f0177f) | Sep 21, 2022 |
| Lenovo        | ThinkPad T430 2349A17       | [ba2eadfd53](https://linux-hardware.org/?probe=ba2eadfd53) | Sep 21, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Lenovo        | ThinkPad T450s 20BX005GU... | [5c41d03119](https://linux-hardware.org/?probe=5c41d03119) | Sep 15, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [c07c5b31f6](https://linux-hardware.org/?probe=c07c5b31f6) | Sep 13, 2022 |
| Dell          | XPS 17 9710                 | [4b728bc447](https://linux-hardware.org/?probe=4b728bc447) | Sep 12, 2022 |
| Acer          | Aspire E5-575               | [8b1a8497c7](https://linux-hardware.org/?probe=8b1a8497c7) | Aug 21, 2022 |
| Dell          | Latitude E5540              | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| ASUSTek       | GL552VX                     | [16c1976ac6](https://linux-hardware.org/?probe=16c1976ac6) | Aug 12, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | [aa4b21b3a7](https://linux-hardware.org/?probe=aa4b21b3a7) | Aug 12, 2022 |
| Lenovo        | ThinkPad P50 20EQS4QM00     | [9779cc7396](https://linux-hardware.org/?probe=9779cc7396) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [688ae71abc](https://linux-hardware.org/?probe=688ae71abc) | Aug 12, 2022 |
| ASUSTek       | K55A                        | [fb75627e6c](https://linux-hardware.org/?probe=fb75627e6c) | Aug 10, 2022 |
| Dell          | G3 3500                     | [69f594bb80](https://linux-hardware.org/?probe=69f594bb80) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [a4e02af6d9](https://linux-hardware.org/?probe=a4e02af6d9) | Aug 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [d9c5b6d4c5](https://linux-hardware.org/?probe=d9c5b6d4c5) | Aug 02, 2022 |
| Toshiba       | dynabook Satellite B35/R    | [4600fb0c71](https://linux-hardware.org/?probe=4600fb0c71) | Jul 31, 2022 |
| HP            | EliteBook 8470p             | [2171abfd3d](https://linux-hardware.org/?probe=2171abfd3d) | Jul 30, 2022 |
| Chuwi         | GemiBook Pro                | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| TENKU         | SB14                        | [cbe2900f4f](https://linux-hardware.org/?probe=cbe2900f4f) | Jul 02, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [cacc2464af](https://linux-hardware.org/?probe=cacc2464af) | Jun 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [6eb841aab1](https://linux-hardware.org/?probe=6eb841aab1) | Jun 21, 2022 |
| Acer          | Aspire 5738                 | [58b312c382](https://linux-hardware.org/?probe=58b312c382) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | [a8c7fc9c3a](https://linux-hardware.org/?probe=a8c7fc9c3a) | Jun 07, 2022 |
| Chuwi         | GemiBook Pro                | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| MSI           | Bravo 15 B5DD               | [4ae400000f](https://linux-hardware.org/?probe=4ae400000f) | Jun 01, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | [63bc3a2ce5](https://linux-hardware.org/?probe=63bc3a2ce5) | May 27, 2022 |
| Acer          | Aspire A315-57G             | [d0400f8d02](https://linux-hardware.org/?probe=d0400f8d02) | May 26, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [9df127ec26](https://linux-hardware.org/?probe=9df127ec26) | May 24, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bb2ffeb78a](https://linux-hardware.org/?probe=bb2ffeb78a) | May 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bb73f6aa37](https://linux-hardware.org/?probe=bb73f6aa37) | May 04, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [51625474b7](https://linux-hardware.org/?probe=51625474b7) | Apr 30, 2022 |
| ASUSTek       | E402SA                      | [4c5cbe705d](https://linux-hardware.org/?probe=4c5cbe705d) | Apr 27, 2022 |
| Dell          | Inspiron 3537               | [2fcc2371d9](https://linux-hardware.org/?probe=2fcc2371d9) | Apr 25, 2022 |
| MSI           | GF63 8RD                    | [287e344d0e](https://linux-hardware.org/?probe=287e344d0e) | Apr 16, 2022 |
| HP            | EliteBook 840 G5            | [7499dbd303](https://linux-hardware.org/?probe=7499dbd303) | Apr 15, 2022 |
| Dell          | System Vostro 3450          | [78750d86f5](https://linux-hardware.org/?probe=78750d86f5) | Mar 19, 2022 |
| Dell          | Vostro 3400                 | [5dcc8e2cee](https://linux-hardware.org/?probe=5dcc8e2cee) | Mar 14, 2022 |
| Dell          | Latitude E5540              | [0948114af7](https://linux-hardware.org/?probe=0948114af7) | Mar 03, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [6b0f448d7b](https://linux-hardware.org/?probe=6b0f448d7b) | Feb 24, 2022 |
| Dell          | System XPS L702X            | [e1d4821ec2](https://linux-hardware.org/?probe=e1d4821ec2) | Feb 19, 2022 |
| Dell          | Inspiron N4050              | [0619812e27](https://linux-hardware.org/?probe=0619812e27) | Feb 11, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [4834a3fe2e](https://linux-hardware.org/?probe=4834a3fe2e) | Feb 09, 2022 |
| Dell          | G3 3500                     | [9001ccacbc](https://linux-hardware.org/?probe=9001ccacbc) | Feb 09, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [2621c151ec](https://linux-hardware.org/?probe=2621c151ec) | Feb 01, 2022 |
| Dell          | Vostro 3578                 | [a95dfa8bc8](https://linux-hardware.org/?probe=a95dfa8bc8) | Jan 26, 2022 |
| Lenovo        | ThinkPad T480 20L5001DUS    | [872bc057f0](https://linux-hardware.org/?probe=872bc057f0) | Jan 10, 2022 |
| HP            | EliteBook 840 G2            | [5588a84fcf](https://linux-hardware.org/?probe=5588a84fcf) | Jan 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [d65648c445](https://linux-hardware.org/?probe=d65648c445) | Jan 09, 2022 |
| HP            | EliteBook 840 G2            | [3b97b65258](https://linux-hardware.org/?probe=3b97b65258) | Jan 08, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [65c9a87d51](https://linux-hardware.org/?probe=65c9a87d51) | Jan 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [48cfc7d185](https://linux-hardware.org/?probe=48cfc7d185) | Dec 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [b64750f465](https://linux-hardware.org/?probe=b64750f465) | Dec 26, 2021 |
| Dell          | XPS 15 9500                 | [717b9f1dd0](https://linux-hardware.org/?probe=717b9f1dd0) | Dec 16, 2021 |
| Apple         | MacBookPro9,2               | [21d85302a2](https://linux-hardware.org/?probe=21d85302a2) | Dec 05, 2021 |
| Dell          | Vostro 3500                 | [903f3e93ee](https://linux-hardware.org/?probe=903f3e93ee) | Dec 03, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [70c63b2fb6](https://linux-hardware.org/?probe=70c63b2fb6) | Dec 02, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [c5d4bf5c62](https://linux-hardware.org/?probe=c5d4bf5c62) | Dec 02, 2021 |
| Dell          | Vostro 3500                 | [7a8a79d813](https://linux-hardware.org/?probe=7a8a79d813) | Dec 02, 2021 |
| Timi          | A35S                        | [dbb600147d](https://linux-hardware.org/?probe=dbb600147d) | Nov 30, 2021 |
| HP            | Laptop 15s-du1xxx           | [d4cf81aaa5](https://linux-hardware.org/?probe=d4cf81aaa5) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | [0368cfb8e2](https://linux-hardware.org/?probe=0368cfb8e2) | Nov 23, 2021 |
| Dell          | XPS 15 9500                 | [10455f4980](https://linux-hardware.org/?probe=10455f4980) | Nov 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [17781cb457](https://linux-hardware.org/?probe=17781cb457) | Nov 20, 2021 |
| ASUSTek       | X550LD                      | [f4a646d1f8](https://linux-hardware.org/?probe=f4a646d1f8) | Nov 18, 2021 |
| HP            | EliteBook 840 G5            | [5471ce2e2f](https://linux-hardware.org/?probe=5471ce2e2f) | Nov 16, 2021 |
| HP            | EliteBook 8470p             | [96b971a0ed](https://linux-hardware.org/?probe=96b971a0ed) | Nov 08, 2021 |
| Dell          | Inspiron 5420               | [a471ac5d59](https://linux-hardware.org/?probe=a471ac5d59) | Nov 07, 2021 |
| Dell          | Vostro 3478                 | [f88e5eec69](https://linux-hardware.org/?probe=f88e5eec69) | Nov 05, 2021 |
| Dell          | Vostro 3478                 | [8174188077](https://linux-hardware.org/?probe=8174188077) | Nov 05, 2021 |
| ASUSTek       | K45A                        | [f9bc7efe7b](https://linux-hardware.org/?probe=f9bc7efe7b) | Nov 05, 2021 |
| ASUSTek       | K45A                        | [096deec12d](https://linux-hardware.org/?probe=096deec12d) | Nov 05, 2021 |
| Dell          | Precision 7510              | [49f177c1c2](https://linux-hardware.org/?probe=49f177c1c2) | Nov 05, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [5158fb179d](https://linux-hardware.org/?probe=5158fb179d) | Nov 02, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [3296f4587d](https://linux-hardware.org/?probe=3296f4587d) | Nov 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6a546c5681](https://linux-hardware.org/?probe=6a546c5681) | Oct 23, 2021 |
| HP            | ZBook Firefly 14 inch G8... | [603ccdfb84](https://linux-hardware.org/?probe=603ccdfb84) | Oct 19, 2021 |
| Dell          | Precision 7510              | [800ca77fe7](https://linux-hardware.org/?probe=800ca77fe7) | Oct 13, 2021 |
| HP            | Notebook                    | [6ac2c09585](https://linux-hardware.org/?probe=6ac2c09585) | Oct 09, 2021 |
| HP            | Laptop 15-bs1xx             | [c9fd6887d4](https://linux-hardware.org/?probe=c9fd6887d4) | Oct 06, 2021 |
| Acer          | Predator PH315-51           | [fb9a605481](https://linux-hardware.org/?probe=fb9a605481) | Oct 05, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [b1fb3d4e88](https://linux-hardware.org/?probe=b1fb3d4e88) | Oct 04, 2021 |
| Dell          | Latitude E7440              | [fe4153e816](https://linux-hardware.org/?probe=fe4153e816) | Oct 04, 2021 |
| HP            | EliteBook Folio 9470m       | [101371762b](https://linux-hardware.org/?probe=101371762b) | Oct 01, 2021 |
| Dell          | XPS 13 9350                 | [c1dc59d33f](https://linux-hardware.org/?probe=c1dc59d33f) | Sep 29, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [52fe5aa259](https://linux-hardware.org/?probe=52fe5aa259) | Sep 29, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [d8cde7951e](https://linux-hardware.org/?probe=d8cde7951e) | Sep 29, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [db7c214214](https://linux-hardware.org/?probe=db7c214214) | Sep 28, 2021 |
| Dell          | Latitude 3520               | [2fb41f5f08](https://linux-hardware.org/?probe=2fb41f5f08) | Sep 24, 2021 |
| HP            | 15                          | [0aec7fa603](https://linux-hardware.org/?probe=0aec7fa603) | Sep 22, 2021 |
| Sony          | SVE14A15FGW                 | [f1049f7db1](https://linux-hardware.org/?probe=f1049f7db1) | Sep 21, 2021 |
| Panasonic     | CFSX4-1                     | [d474bc1b91](https://linux-hardware.org/?probe=d474bc1b91) | Sep 03, 2021 |
| Panasonic     | CFSX4-1                     | [bee71431a0](https://linux-hardware.org/?probe=bee71431a0) | Sep 03, 2021 |
| HP            | Laptop 15s-fq2xxx           | [87b688768a](https://linux-hardware.org/?probe=87b688768a) | Sep 02, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| MSI           | GF62 7RD                    | [5a35b145a9](https://linux-hardware.org/?probe=5a35b145a9) | Aug 19, 2021 |
| MSI           | GE66 Raider 11UH            | [df3d4bfff1](https://linux-hardware.org/?probe=df3d4bfff1) | Aug 18, 2021 |
| MSI           | GE66 Raider 11UH            | [dde539e1b1](https://linux-hardware.org/?probe=dde539e1b1) | Aug 18, 2021 |
| HP            | ProBook 4430s               | [0235e3c344](https://linux-hardware.org/?probe=0235e3c344) | Aug 18, 2021 |
| HP            | EliteBook 745 G6            | [d3ed4611f3](https://linux-hardware.org/?probe=d3ed4611f3) | Aug 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [f77c5c4c48](https://linux-hardware.org/?probe=f77c5c4c48) | Aug 10, 2021 |
| Dell          | Inspiron 5502               | [57bf64ac4b](https://linux-hardware.org/?probe=57bf64ac4b) | Aug 09, 2021 |
| Dell          | Inspiron 5502               | [955889f7c8](https://linux-hardware.org/?probe=955889f7c8) | Aug 08, 2021 |
| Dell          | Vostro 15-3568              | [5f68a1fdaa](https://linux-hardware.org/?probe=5f68a1fdaa) | Aug 07, 2021 |
| Acer          | Aspire E5-572G              | [76e0c19c46](https://linux-hardware.org/?probe=76e0c19c46) | Aug 02, 2021 |
| Dell          | Vostro 15-3568              | [94aa730eda](https://linux-hardware.org/?probe=94aa730eda) | Jul 23, 2021 |
| Dell          | Vostro 5568                 | [f6fc2c1a8c](https://linux-hardware.org/?probe=f6fc2c1a8c) | Jul 19, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [aa5fadb321](https://linux-hardware.org/?probe=aa5fadb321) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [dcc22fa273](https://linux-hardware.org/?probe=dcc22fa273) | Jul 13, 2021 |
| Dell          | Vostro 15-3568              | [3d6d3007cf](https://linux-hardware.org/?probe=3d6d3007cf) | Jul 10, 2021 |
| Dell          | Vostro 15-3568              | [66d001f315](https://linux-hardware.org/?probe=66d001f315) | Jul 09, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XX0... | [e6cb486cfd](https://linux-hardware.org/?probe=e6cb486cfd) | Jul 07, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XX0... | [58ad5d25b9](https://linux-hardware.org/?probe=58ad5d25b9) | Jul 07, 2021 |
| Dell          | Latitude E6410              | [9a4002aa3d](https://linux-hardware.org/?probe=9a4002aa3d) | Jul 07, 2021 |
| HP            | Compaq 510                  | [cd27b78fea](https://linux-hardware.org/?probe=cd27b78fea) | Jul 04, 2021 |
| Dell          | Vostro 5568                 | [bec8a61ff4](https://linux-hardware.org/?probe=bec8a61ff4) | Jul 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [3fb422fa2e](https://linux-hardware.org/?probe=3fb422fa2e) | Jun 27, 2021 |
| ASUSTek       | K46CA                       | [85b912e99c](https://linux-hardware.org/?probe=85b912e99c) | Jun 22, 2021 |
| Acer          | Aspire 4315                 | [ac56c24f68](https://linux-hardware.org/?probe=ac56c24f68) | Jun 15, 2021 |
| Acer          | Aspire 4315                 | [4527ee70c7](https://linux-hardware.org/?probe=4527ee70c7) | Jun 13, 2021 |
| Lenovo        | ThinkPad L520 5015A76       | [84b62cbde9](https://linux-hardware.org/?probe=84b62cbde9) | Jun 10, 2021 |
| Dell          | Vostro 15-3568              | [de3596a9a3](https://linux-hardware.org/?probe=de3596a9a3) | Jun 05, 2021 |
| Dell          | Latitude 7420               | [f417016cf6](https://linux-hardware.org/?probe=f417016cf6) | Jun 04, 2021 |
| Lenovo        | V130-14IKB 81HQ             | [8995f3c1ad](https://linux-hardware.org/?probe=8995f3c1ad) | Jun 01, 2021 |
| Lenovo        | Z40-70 20366                | [b1b8196f26](https://linux-hardware.org/?probe=b1b8196f26) | May 31, 2021 |
| Lenovo        | ThinkPad X250 20CLCTO1WW    | [a5d677976f](https://linux-hardware.org/?probe=a5d677976f) | May 29, 2021 |
| Acer          | Swift SF314-59              | [b70a62225d](https://linux-hardware.org/?probe=b70a62225d) | May 22, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [ddfb904938](https://linux-hardware.org/?probe=ddfb904938) | May 19, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [35324d2388](https://linux-hardware.org/?probe=35324d2388) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1abefab68f](https://linux-hardware.org/?probe=1abefab68f) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c4ea8f1bab](https://linux-hardware.org/?probe=c4ea8f1bab) | May 19, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [2ce7106efb](https://linux-hardware.org/?probe=2ce7106efb) | May 15, 2021 |
| HP            | ProBook 450 G4              | [b8108b310a](https://linux-hardware.org/?probe=b8108b310a) | May 13, 2021 |
| HP            | ProBook 450 G4              | [c596247722](https://linux-hardware.org/?probe=c596247722) | May 13, 2021 |
| Dell          | Inspiron 3443               | [c84fc5c646](https://linux-hardware.org/?probe=c84fc5c646) | May 12, 2021 |
| Acer          | Predator G9-793             | [90b04b667a](https://linux-hardware.org/?probe=90b04b667a) | May 03, 2021 |
| HP            | Pavilion 15                 | [1ddb966308](https://linux-hardware.org/?probe=1ddb966308) | Apr 28, 2021 |
| Sony          | VPCCW13FX                   | [82e9a1f82a](https://linux-hardware.org/?probe=82e9a1f82a) | Apr 25, 2021 |
| Dell          | Precision 3520              | [fc2d295c0e](https://linux-hardware.org/?probe=fc2d295c0e) | Apr 24, 2021 |
| HP            | ProBook 445 G7              | [76defcf2f7](https://linux-hardware.org/?probe=76defcf2f7) | Apr 22, 2021 |
| MSI           | Prestige 15 A11SCX          | [007ae7cca0](https://linux-hardware.org/?probe=007ae7cca0) | Apr 18, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [07736896f9](https://linux-hardware.org/?probe=07736896f9) | Apr 18, 2021 |
| HP            | Unknown                     | [2465109965](https://linux-hardware.org/?probe=2465109965) | Apr 13, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [698d0ca8cc](https://linux-hardware.org/?probe=698d0ca8cc) | Apr 08, 2021 |
| Dell          | G3 3579                     | [d5d191947e](https://linux-hardware.org/?probe=d5d191947e) | Apr 06, 2021 |
| Dell          | G3 3579                     | [07fd740efe](https://linux-hardware.org/?probe=07fd740efe) | Apr 06, 2021 |
| Chuwi         | LapBook SE                  | [0e9a03cc48](https://linux-hardware.org/?probe=0e9a03cc48) | Apr 06, 2021 |
| MSI           | Prestige 15 A11SCX          | [d20d2b755f](https://linux-hardware.org/?probe=d20d2b755f) | Apr 04, 2021 |
| Toshiba       | Satellite E45-B             | [e8c59a070a](https://linux-hardware.org/?probe=e8c59a070a) | Apr 04, 2021 |
| Toshiba       | Satellite E45-B             | [b9324b1b4d](https://linux-hardware.org/?probe=b9324b1b4d) | Apr 04, 2021 |
| Gigabyte      | AERO 15-X9                  | [0984402bad](https://linux-hardware.org/?probe=0984402bad) | Apr 03, 2021 |
| Gigabyte      | AERO 15-X9                  | [eba80415c0](https://linux-hardware.org/?probe=eba80415c0) | Apr 03, 2021 |
| MSI           | GS40 6QE Phantom            | [adbf080ab7](https://linux-hardware.org/?probe=adbf080ab7) | Mar 27, 2021 |
| HP            | ProBook 440 G7              | [12fd74ecdc](https://linux-hardware.org/?probe=12fd74ecdc) | Mar 26, 2021 |
| Acer          | Aspire A315-42              | [43f33bc8e0](https://linux-hardware.org/?probe=43f33bc8e0) | Mar 21, 2021 |
| Acer          | Aspire A315-42              | [c377f57ac8](https://linux-hardware.org/?probe=c377f57ac8) | Mar 21, 2021 |
| Dell          | XPS 15 9500                 | [cac842cdbb](https://linux-hardware.org/?probe=cac842cdbb) | Mar 20, 2021 |
| Dell          | Inspiron 3537               | [66ce284547](https://linux-hardware.org/?probe=66ce284547) | Mar 14, 2021 |
| Dell          | Vostro 3460                 | [a8e1128b26](https://linux-hardware.org/?probe=a8e1128b26) | Mar 13, 2021 |
| Dell          | Inspiron 3537               | [f85fc12bff](https://linux-hardware.org/?probe=f85fc12bff) | Mar 09, 2021 |
| ASUSTek       | X202E                       | [cc089d4ddb](https://linux-hardware.org/?probe=cc089d4ddb) | Mar 08, 2021 |
| Dell          | XPS 15 9500                 | [647b5fbb43](https://linux-hardware.org/?probe=647b5fbb43) | Mar 06, 2021 |
| Acer          | Aspire A515-53              | [637c3ebf75](https://linux-hardware.org/?probe=637c3ebf75) | Feb 28, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [05ad71d3d8](https://linux-hardware.org/?probe=05ad71d3d8) | Feb 24, 2021 |
| Gateway       | LT40                        | [90ae93da93](https://linux-hardware.org/?probe=90ae93da93) | Feb 24, 2021 |
| Gateway       | LT40                        | [98f2ce8032](https://linux-hardware.org/?probe=98f2ce8032) | Feb 24, 2021 |
| Acer          | Aspire E5-572G              | [4a441fe0c9](https://linux-hardware.org/?probe=4a441fe0c9) | Feb 21, 2021 |
| Acer          | Aspire A315-42              | [bfb791c2fb](https://linux-hardware.org/?probe=bfb791c2fb) | Feb 19, 2021 |
| Sony          | VGN-NW270F                  | [87b755412e](https://linux-hardware.org/?probe=87b755412e) | Feb 19, 2021 |
| Sony          | VGN-NW270F                  | [8d0bcb0740](https://linux-hardware.org/?probe=8d0bcb0740) | Feb 19, 2021 |
| Dell          | Inspiron 5570               | [a79c837a9b](https://linux-hardware.org/?probe=a79c837a9b) | Feb 16, 2021 |
| Dell          | Inspiron 5570               | [5cb0f77327](https://linux-hardware.org/?probe=5cb0f77327) | Feb 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [0c70deaac1](https://linux-hardware.org/?probe=0c70deaac1) | Feb 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [0441228ba8](https://linux-hardware.org/?probe=0441228ba8) | Feb 07, 2021 |
| Dell          | Latitude E7450              | [94b0fc1fc8](https://linux-hardware.org/?probe=94b0fc1fc8) | Feb 06, 2021 |
| Acer          | Swift SF315-52              | [b2b00b4390](https://linux-hardware.org/?probe=b2b00b4390) | Jan 30, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [d7f2ee4a81](https://linux-hardware.org/?probe=d7f2ee4a81) | Jan 25, 2021 |
| Toshiba       | Satellite L840              | [82f5ebd486](https://linux-hardware.org/?probe=82f5ebd486) | Jan 18, 2021 |
| ASUSTek       | X550CC                      | [6eaddc8157](https://linux-hardware.org/?probe=6eaddc8157) | Dec 21, 2020 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [fb16534a29](https://linux-hardware.org/?probe=fb16534a29) | Dec 17, 2020 |
| Sony          | VGN-NW270F                  | [d8989e5c40](https://linux-hardware.org/?probe=d8989e5c40) | Dec 16, 2020 |
| Apple         | MacBookPro11,4              | [e880800d6f](https://linux-hardware.org/?probe=e880800d6f) | Dec 13, 2020 |
| Dell          | G3 3579                     | [99724b8bd6](https://linux-hardware.org/?probe=99724b8bd6) | Dec 12, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fa10ea29e8](https://linux-hardware.org/?probe=fa10ea29e8) | Dec 11, 2020 |
| Acer          | Predator PH315-51           | [c9539f5932](https://linux-hardware.org/?probe=c9539f5932) | Dec 09, 2020 |
| HP            | EliteBook 840 G2            | [ea2bf23a76](https://linux-hardware.org/?probe=ea2bf23a76) | Dec 03, 2020 |
| HP            | Compaq Presario CQ45        | [2a4ce919e5](https://linux-hardware.org/?probe=2a4ce919e5) | Dec 03, 2020 |
| Acer          | Aspire V5-431P              | [831f0df544](https://linux-hardware.org/?probe=831f0df544) | Dec 03, 2020 |
| Lenovo        | ThinkPad T430 2349A17       | [4e39668b71](https://linux-hardware.org/?probe=4e39668b71) | Dec 02, 2020 |
| Lenovo        | ThinkPad T430 2349A17       | [dbff453f7e](https://linux-hardware.org/?probe=dbff453f7e) | Dec 02, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [80f3a03fc2](https://linux-hardware.org/?probe=80f3a03fc2) | Nov 22, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [471b375bb8](https://linux-hardware.org/?probe=471b375bb8) | Nov 22, 2020 |
| HP            | ENVY Laptop 13-ba0xxx       | [32692a5980](https://linux-hardware.org/?probe=32692a5980) | Nov 18, 2020 |
| HP            | Pavilion Laptop 15-cs3xx... | [4019b6c1ff](https://linux-hardware.org/?probe=4019b6c1ff) | Nov 16, 2020 |
| Dell          | XPS 15 9570                 | [7fb140838e](https://linux-hardware.org/?probe=7fb140838e) | Nov 12, 2020 |
| Dell          | XPS 15 9570                 | [ac263c6ad6](https://linux-hardware.org/?probe=ac263c6ad6) | Nov 10, 2020 |
| HP            | Compaq Presario CQ45        | [f2a745943a](https://linux-hardware.org/?probe=f2a745943a) | Nov 04, 2020 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [bfa10fd887](https://linux-hardware.org/?probe=bfa10fd887) | Nov 04, 2020 |
| Dell          | Latitude 7490               | [8f0ec25c05](https://linux-hardware.org/?probe=8f0ec25c05) | Oct 29, 2020 |
| Dell          | Latitude E6530              | [1a16aeb4dd](https://linux-hardware.org/?probe=1a16aeb4dd) | Oct 28, 2020 |
| HP            | EliteBook 840 G2            | [070dae158a](https://linux-hardware.org/?probe=070dae158a) | Oct 24, 2020 |
| Toshiba       | Satellite L840              | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| ASUSTek       | ASUSPRO P1440UA             | [fa061b6d7e](https://linux-hardware.org/?probe=fa061b6d7e) | Oct 13, 2020 |
| ASUSTek       | ASUSPRO P1440UA             | [dc9b667685](https://linux-hardware.org/?probe=dc9b667685) | Oct 13, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [9bf6f0ba43](https://linux-hardware.org/?probe=9bf6f0ba43) | Oct 09, 2020 |
| HP            | EliteBook 840 G5            | [125dd87b84](https://linux-hardware.org/?probe=125dd87b84) | Oct 03, 2020 |
| Acer          | Aspire E5-575G              | [204ef3a0f3](https://linux-hardware.org/?probe=204ef3a0f3) | Oct 02, 2020 |
| Lenovo        | ThinkPad T420 4236C95       | [8cf52f76c0](https://linux-hardware.org/?probe=8cf52f76c0) | Oct 02, 2020 |
| HP            | ProBook 440 G5              | [6753d2054d](https://linux-hardware.org/?probe=6753d2054d) | Oct 01, 2020 |
| HP            | ProBook 440 G5              | [6c568247ff](https://linux-hardware.org/?probe=6c568247ff) | Oct 01, 2020 |
| ASUSTek       | X411UA                      | [15bcec7549](https://linux-hardware.org/?probe=15bcec7549) | Sep 28, 2020 |
| Dell          | Vostro 3578                 | [5ff5b89d5e](https://linux-hardware.org/?probe=5ff5b89d5e) | Sep 22, 2020 |
| Dell          | Inspiron 5559               | [3a8b43fc2f](https://linux-hardware.org/?probe=3a8b43fc2f) | Sep 16, 2020 |
| ASUSTek       | X411UA                      | [8adea7b2b3](https://linux-hardware.org/?probe=8adea7b2b3) | Sep 15, 2020 |
| Dell          | Vostro 1450                 | [444ddb1aa9](https://linux-hardware.org/?probe=444ddb1aa9) | Sep 15, 2020 |
| Dell          | Precision 3520              | [e8f520c4fa](https://linux-hardware.org/?probe=e8f520c4fa) | Sep 09, 2020 |
| MASSCOM VI... | L133                        | [b356f018b2](https://linux-hardware.org/?probe=b356f018b2) | Sep 09, 2020 |
| HP            | ProBook 440 G6              | [11a8a7e166](https://linux-hardware.org/?probe=11a8a7e166) | Sep 07, 2020 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [42cdde5346](https://linux-hardware.org/?probe=42cdde5346) | Sep 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [6b4eeecb26](https://linux-hardware.org/?probe=6b4eeecb26) | Sep 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [a9ced30680](https://linux-hardware.org/?probe=a9ced30680) | Aug 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [17c4f51c75](https://linux-hardware.org/?probe=17c4f51c75) | Aug 29, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [08d8dc8d6e](https://linux-hardware.org/?probe=08d8dc8d6e) | Aug 28, 2020 |
| Lenovo        | ThinkPad L430 2465CTO       | [e5371d9b58](https://linux-hardware.org/?probe=e5371d9b58) | Aug 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ff005e6d9](https://linux-hardware.org/?probe=4ff005e6d9) | Aug 21, 2020 |
| Lenovo        | ThinkPad T580 20L9001MUS    | [92c940e8c2](https://linux-hardware.org/?probe=92c940e8c2) | Aug 21, 2020 |
| Dell          | Inspiron 3537               | [e7702e2ce8](https://linux-hardware.org/?probe=e7702e2ce8) | Aug 20, 2020 |
| Dell          | G3 3579                     | [8e341b94ae](https://linux-hardware.org/?probe=8e341b94ae) | Aug 18, 2020 |
| Dell          | G3 3579                     | [9a1078144d](https://linux-hardware.org/?probe=9a1078144d) | Aug 18, 2020 |
| HP            | EliteBook 840 G5            | [52f08d8242](https://linux-hardware.org/?probe=52f08d8242) | Aug 12, 2020 |
| Lenovo        | ThinkPad E480 20KN005GVA    | [f77c6858ad](https://linux-hardware.org/?probe=f77c6858ad) | Jul 24, 2020 |
| HP            | EliteBook 840 G5            | [a58d188243](https://linux-hardware.org/?probe=a58d188243) | Jul 19, 2020 |
| Dell          | XPS 15 9570                 | [ab4eff4438](https://linux-hardware.org/?probe=ab4eff4438) | Jul 16, 2020 |
| Dell          | Latitude E5470              | [777b8955c3](https://linux-hardware.org/?probe=777b8955c3) | Jul 12, 2020 |
| Apple         | MacBookPro8,1               | [d0dff5e971](https://linux-hardware.org/?probe=d0dff5e971) | Jul 09, 2020 |
| Dell          | Vostro 3590                 | [4f8fb0d621](https://linux-hardware.org/?probe=4f8fb0d621) | Jul 09, 2020 |
| Dell          | XPS 15 9570                 | [4e1f771d23](https://linux-hardware.org/?probe=4e1f771d23) | Jun 29, 2020 |
| Dell          | Vostro 3460                 | [2338ae0fde](https://linux-hardware.org/?probe=2338ae0fde) | Jun 28, 2020 |
| HP            | ZBook 17 G2                 | [467e55d0db](https://linux-hardware.org/?probe=467e55d0db) | Jun 20, 2020 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [652d0e5648](https://linux-hardware.org/?probe=652d0e5648) | Jun 18, 2020 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [3b5f86f3d4](https://linux-hardware.org/?probe=3b5f86f3d4) | Jun 18, 2020 |
| Dell          | Inspiron 5548               | [60a6140ac2](https://linux-hardware.org/?probe=60a6140ac2) | Jun 14, 2020 |
| Dell          | Inspiron 5548               | [ac70aa8a8d](https://linux-hardware.org/?probe=ac70aa8a8d) | Jun 14, 2020 |
| Dell          | Vostro 3590                 | [faca1b4063](https://linux-hardware.org/?probe=faca1b4063) | Jun 14, 2020 |
| HP            | ZBook Studio G3             | [91a0ff7707](https://linux-hardware.org/?probe=91a0ff7707) | Jun 10, 2020 |
| Dell          | Inspiron 5570               | [be05348be2](https://linux-hardware.org/?probe=be05348be2) | May 29, 2020 |
| Dell          | Inspiron 5570               | [945550a204](https://linux-hardware.org/?probe=945550a204) | May 29, 2020 |
| Dell          | Latitude E7440              | [26b5908778](https://linux-hardware.org/?probe=26b5908778) | May 20, 2020 |
| HP            | EliteBook 8570w             | [849bf107d8](https://linux-hardware.org/?probe=849bf107d8) | May 18, 2020 |
| HP            | EliteBook 8570w             | [5a938c4186](https://linux-hardware.org/?probe=5a938c4186) | May 17, 2020 |
| Dell          | Inspiron 7520               | [f400730782](https://linux-hardware.org/?probe=f400730782) | May 15, 2020 |
| HP            | ProBook 440 G6              | [272430b55d](https://linux-hardware.org/?probe=272430b55d) | May 12, 2020 |
| Toshiba       | PORTEGE T110                | [8c8ec8db54](https://linux-hardware.org/?probe=8c8ec8db54) | May 10, 2020 |
| Acer          | Aspire R3-131T              | [7e7b980d96](https://linux-hardware.org/?probe=7e7b980d96) | May 09, 2020 |
| Dell          | Vostro 14-5480              | [3edae78003](https://linux-hardware.org/?probe=3edae78003) | Apr 28, 2020 |
| Dell          | Inspiron 3558               | [8e17ac8b14](https://linux-hardware.org/?probe=8e17ac8b14) | Apr 27, 2020 |
| Acer          | Swift SF315-52              | [a41dc8c7b3](https://linux-hardware.org/?probe=a41dc8c7b3) | Apr 24, 2020 |
| Dell          | Vostro 3478                 | [65a16b0f00](https://linux-hardware.org/?probe=65a16b0f00) | Apr 22, 2020 |
| HP            | EliteBook 8560w             | [985dd25740](https://linux-hardware.org/?probe=985dd25740) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | [8b6c1d10a4](https://linux-hardware.org/?probe=8b6c1d10a4) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | [9cb006b675](https://linux-hardware.org/?probe=9cb006b675) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | [e670bd004a](https://linux-hardware.org/?probe=e670bd004a) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | [ed1d4fbd62](https://linux-hardware.org/?probe=ed1d4fbd62) | Apr 19, 2020 |
| Acer          | Aspire E5-575               | [c51238bbe1](https://linux-hardware.org/?probe=c51238bbe1) | Apr 11, 2020 |
| Acer          | Aspire E5-575               | [e421f3a586](https://linux-hardware.org/?probe=e421f3a586) | Apr 10, 2020 |
| Dell          | XPS 13 9360                 | [9d7415c55e](https://linux-hardware.org/?probe=9d7415c55e) | Apr 04, 2020 |
| Dell          | Precision 5530              | [805db6810c](https://linux-hardware.org/?probe=805db6810c) | Mar 31, 2020 |
| HP            | EliteBook 8540w             | [6093f50362](https://linux-hardware.org/?probe=6093f50362) | Mar 30, 2020 |
| Sony          | VPCEB42EG                   | [d2586cdd17](https://linux-hardware.org/?probe=d2586cdd17) | Mar 25, 2020 |
| Sony          | VPCEB42EG                   | [424402e2b1](https://linux-hardware.org/?probe=424402e2b1) | Mar 25, 2020 |
| ASUSTek       | GL553VE                     | [1238bea224](https://linux-hardware.org/?probe=1238bea224) | Mar 21, 2020 |
| HP            | Compaq Presario CQ45        | [72a39494c1](https://linux-hardware.org/?probe=72a39494c1) | Mar 18, 2020 |
| HP            | Laptop 14-bs0xx             | [7dddec34d1](https://linux-hardware.org/?probe=7dddec34d1) | Mar 02, 2020 |
| HP            | Compaq Presario CQ45        | [f1e468eec0](https://linux-hardware.org/?probe=f1e468eec0) | Feb 29, 2020 |
| HP            | Laptop 14-bs0xx             | [3740504388](https://linux-hardware.org/?probe=3740504388) | Feb 28, 2020 |
| ASUSTek       | X411UA                      | [284484a6b6](https://linux-hardware.org/?probe=284484a6b6) | Feb 15, 2020 |
| Koompi        | Unknown                     | [46e5e1375d](https://linux-hardware.org/?probe=46e5e1375d) | Feb 12, 2020 |
| MSI           | GF63 8RD                    | [6eae1d7ba9](https://linux-hardware.org/?probe=6eae1d7ba9) | Feb 01, 2020 |
| MSI           | GF63 8RD                    | [b7087b6ba5](https://linux-hardware.org/?probe=b7087b6ba5) | Jan 31, 2020 |
| ASUSTek       | K501UX                      | [46c0e495c1](https://linux-hardware.org/?probe=46c0e495c1) | Jan 24, 2020 |
| HP            | EliteBook Folio 1040 G3     | [b2bc63b818](https://linux-hardware.org/?probe=b2bc63b818) | Jan 14, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [4ea2e33944](https://linux-hardware.org/?probe=4ea2e33944) | Jan 07, 2020 |
| AMI           | Cherry Trail FFD            | [c62d47b2a1](https://linux-hardware.org/?probe=c62d47b2a1) | Dec 22, 2019 |
| Jumper        | EZpad                       | [6dfb4e2274](https://linux-hardware.org/?probe=6dfb4e2274) | Oct 31, 2019 |
| Dell          | System Vostro 3450          | [2017fd9a25](https://linux-hardware.org/?probe=2017fd9a25) | Oct 29, 2019 |
| Dell          | System Vostro 3450          | [90391fe6fe](https://linux-hardware.org/?probe=90391fe6fe) | Sep 19, 2019 |
| Samsung       | NC208/NC108                 | [a99fe6de20](https://linux-hardware.org/?probe=a99fe6de20) | Sep 16, 2019 |
| Dell          | Inspiron 3421               | [46a7955491](https://linux-hardware.org/?probe=46a7955491) | Sep 04, 2019 |
| Lenovo        | ThinkPad T410 2522AN6       | [35dfb93d51](https://linux-hardware.org/?probe=35dfb93d51) | Sep 02, 2019 |
| Lenovo        | ThinkPad T410 2522AN6       | [635d10113c](https://linux-hardware.org/?probe=635d10113c) | Sep 02, 2019 |
| HP            | ProBook 450 G1              | [f9ed638fe3](https://linux-hardware.org/?probe=f9ed638fe3) | Aug 27, 2019 |
| Dell          | System Inspiron N4110       | [1923c8603b](https://linux-hardware.org/?probe=1923c8603b) | Aug 13, 2019 |
| Dell          | Inspiron 3537               | [96b08c73b2](https://linux-hardware.org/?probe=96b08c73b2) | Jul 03, 2019 |
| Dell          | Inspiron 7559               | [9662a59bb6](https://linux-hardware.org/?probe=9662a59bb6) | Jun 19, 2019 |
| ASUSTek       | K46CM                       | [f695a76e03](https://linux-hardware.org/?probe=f695a76e03) | Jun 16, 2019 |
| Lenovo        | ThinkPad X230 2325BK0       | [e3cbad71df](https://linux-hardware.org/?probe=e3cbad71df) | Jun 06, 2019 |
| Dell          | Precision M4800             | [87cd78dbb8](https://linux-hardware.org/?probe=87cd78dbb8) | Jun 06, 2019 |
| Dell          | Inspiron 7559               | [2b022f3e6e](https://linux-hardware.org/?probe=2b022f3e6e) | Jun 06, 2019 |
| HP            | Unknown                     | [5a84e64836](https://linux-hardware.org/?probe=5a84e64836) | Jun 05, 2019 |
| Lenovo        | Unknown                     | [bb521ffe81](https://linux-hardware.org/?probe=bb521ffe81) | May 29, 2019 |
| Lenovo        | Unknown                     | [ded7e33a30](https://linux-hardware.org/?probe=ded7e33a30) | May 29, 2019 |
| Lenovo        | ThinkPad X230 2325YN1       | [11b1a757e3](https://linux-hardware.org/?probe=11b1a757e3) | May 07, 2019 |
| Lenovo        | ThinkPad X230 2325YN1       | [48a1bab21b](https://linux-hardware.org/?probe=48a1bab21b) | May 06, 2019 |
| Dell          | Inspiron 3420               | [97669e6bac](https://linux-hardware.org/?probe=97669e6bac) | Apr 28, 2019 |
| Lenovo        | ThinkPad X240 20AMA01LVA    | [60e3dddb8e](https://linux-hardware.org/?probe=60e3dddb8e) | Apr 18, 2019 |
| Lenovo        | ThinkPad X230 2325VEN       | [7de9f34ff3](https://linux-hardware.org/?probe=7de9f34ff3) | Apr 08, 2019 |
| Lenovo        | ThinkPad T61 7661C54        | [f98ce96fd7](https://linux-hardware.org/?probe=f98ce96fd7) | Dec 14, 2018 |
| Lenovo        | ThinkPad T61 7661C54        | [3b2f20eb21](https://linux-hardware.org/?probe=3b2f20eb21) | Dec 14, 2018 |
| Lenovo        | ThinkPad X230 2325BK0       | [eb181d9db4](https://linux-hardware.org/?probe=eb181d9db4) | Nov 17, 2018 |
| MSI           | GP62 6QE                    | [0befde2891](https://linux-hardware.org/?probe=0befde2891) | Oct 29, 2018 |
| MSI           | GP62 6QE                    | [6d5cda0177](https://linux-hardware.org/?probe=6d5cda0177) | Oct 29, 2018 |
| ASUSTek       | FX503VM                     | [c3eafeed41](https://linux-hardware.org/?probe=c3eafeed41) | May 23, 2018 |
| Lenovo        | ThinkPad W530 2447EJ9       | [b73b24ff47](https://linux-hardware.org/?probe=b73b24ff47) | May 16, 2018 |
| Lenovo        | ThinkPad W530 2447EJ9       | [4ced3a8a3c](https://linux-hardware.org/?probe=4ced3a8a3c) | Feb 04, 2018 |
| HP            | Notebook                    | [8f94426008](https://linux-hardware.org/?probe=8f94426008) | Dec 21, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | [96a6c5cbab](https://linux-hardware.org/?probe=96a6c5cbab) | Dec 17, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | [f59b817feb](https://linux-hardware.org/?probe=f59b817feb) | Dec 12, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | [06a39a2c60](https://linux-hardware.org/?probe=06a39a2c60) | Dec 12, 2017 |
| Dell          | Precision M4600             | [dbbeb2486e](https://linux-hardware.org/?probe=dbbeb2486e) | Dec 03, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | [7ee7ca743b](https://linux-hardware.org/?probe=7ee7ca743b) | Dec 03, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | [28ae3d12b8](https://linux-hardware.org/?probe=28ae3d12b8) | Dec 03, 2017 |
| ASUSTek       | GL552JX                     | [c3e4792075](https://linux-hardware.org/?probe=c3e4792075) | Dec 10, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 58        | 22.83%  |
| Ubuntu 18.04        | 20        | 7.87%   |
| Arch                | 12        | 4.72%   |
| Arch Rolling        | 8         | 3.15%   |
| Ubuntu 22.04        | 6         | 2.36%   |
| Pop!_OS 20.04       | 6         | 2.36%   |
| Ubuntu 21.04        | 5         | 1.97%   |
| Debian 10           | 5         | 1.97%   |
| Ubuntu 21.10        | 4         | 1.57%   |
| Ubuntu 19.10        | 4         | 1.57%   |
| Ubuntu 16.04        | 4         | 1.57%   |
| Pop!_OS 21.04       | 4         | 1.57%   |
| OpenMandriva 4.2    | 4         | 1.57%   |
| KDE neon 20.04      | 4         | 1.57%   |
| Fedora 34           | 4         | 1.57%   |
| Pop!_OS 22.04       | 3         | 1.18%   |
| OpenMandriva 4.3    | 3         | 1.18%   |
| Manjaro 22.0.0      | 3         | 1.18%   |
| Manjaro 20.2        | 3         | 1.18%   |
| Fedora 33           | 3         | 1.18%   |
| EndeavourOS Rolling | 3         | 1.18%   |
| ArcoLinux Rolling   | 3         | 1.18%   |
| Zorin 16            | 2         | 0.79%   |
| Zorin 15            | 2         | 0.79%   |
| Ubuntu Unity 20.04  | 2         | 0.79%   |
| Ubuntu MATE 20.04   | 2         | 0.79%   |
| Ubuntu 20.10        | 2         | 0.79%   |
| Ubuntu 19.04        | 2         | 0.79%   |
| Pop!_OS 21.10       | 2         | 0.79%   |
| Pop!_OS 20.10       | 2         | 0.79%   |
| Manjaro 18.0.4      | 2         | 0.79%   |
| Manjaro             | 2         | 0.79%   |
| Lubuntu 22.04       | 2         | 0.79%   |
| Lubuntu 20.04       | 2         | 0.79%   |
| Linux Mint 20.3     | 2         | 0.79%   |
| Linux Mint 20.1     | 2         | 0.79%   |
| Linux Mint 18.3     | 2         | 0.79%   |
| Kubuntu 21.04       | 2         | 0.79%   |
| Fedora 36           | 2         | 0.79%   |
| Endless 3.8.0       | 2         | 0.79%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 106       | 42.74%  |
| Arch         | 20        | 8.06%   |
| Pop!_OS      | 17        | 6.85%   |
| Manjaro      | 12        | 4.84%   |
| Fedora       | 12        | 4.84%   |
| Linux Mint   | 9         | 3.63%   |
| OpenMandriva | 7         | 2.82%   |
| Endless      | 7         | 2.82%   |
| Debian       | 7         | 2.82%   |
| Ubuntu Unity | 5         | 2.02%   |
| Kubuntu      | 5         | 2.02%   |
| Zorin        | 4         | 1.61%   |
| Lubuntu      | 4         | 1.61%   |
| KDE neon     | 4         | 1.61%   |
| EndeavourOS  | 3         | 1.21%   |
| ArcoLinux    | 3         | 1.21%   |
| Xubuntu      | 2         | 0.81%   |
| Ubuntu MATE  | 2         | 0.81%   |
| openSUSE     | 2         | 0.81%   |
| MX           | 2         | 0.81%   |
| Kali         | 2         | 0.81%   |
| Gentoo       | 2         | 0.81%   |
| Elementary   | 2         | 0.81%   |
| Clear Linux  | 2         | 0.81%   |
| Void Linux   | 1         | 0.4%    |
| Solus        | 1         | 0.4%    |
| ROSA         | 1         | 0.4%    |
| Nobara       | 1         | 0.4%    |
| LMDE         | 1         | 0.4%    |
| Devuan       | 1         | 0.4%    |
| CentOS       | 1         | 0.4%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 7         | 2.56%   |
| 5.4.0-52-generic         | 5         | 1.83%   |
| 5.4.0-48-generic         | 5         | 1.83%   |
| 5.4.0-40-generic         | 5         | 1.83%   |
| 5.4.0-37-generic         | 5         | 1.83%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.47%   |
| 5.8.0-55-generic         | 3         | 1.1%    |
| 5.8.0-53-generic         | 3         | 1.1%    |
| 5.8.0-48-generic         | 3         | 1.1%    |
| 5.8.0-43-generic         | 3         | 1.1%    |
| 5.15.0-48-generic        | 3         | 1.1%    |
| 5.11.0-41-generic        | 3         | 1.1%    |
| 5.11.0-37-generic        | 3         | 1.1%    |
| 4.10.0-28-generic        | 3         | 1.1%    |
| 5.9.14-200.fc33.x86_64   | 2         | 0.73%   |
| 5.8.0-7642-generic       | 2         | 0.73%   |
| 5.8.0-50-generic         | 2         | 0.73%   |
| 5.8.0-44-generic         | 2         | 0.73%   |
| 5.8.0-25-generic         | 2         | 0.73%   |
| 5.4.0-7642-generic       | 2         | 0.73%   |
| 5.4.0-74-generic         | 2         | 0.73%   |
| 5.4.0-72-generic         | 2         | 0.73%   |
| 5.4.0-70-generic         | 2         | 0.73%   |
| 5.4.0-58-generic         | 2         | 0.73%   |
| 5.4.0-47-generic         | 2         | 0.73%   |
| 5.4.0-45-generic         | 2         | 0.73%   |
| 5.4.0-39-generic         | 2         | 0.73%   |
| 5.4.0-29-generic         | 2         | 0.73%   |
| 5.4.0-19-generic         | 2         | 0.73%   |
| 5.3.0-46-generic         | 2         | 0.73%   |
| 5.3.0-28-generic         | 2         | 0.73%   |
| 5.3.0-18-generic         | 2         | 0.73%   |
| 5.19.12-200.fc36.x86_64  | 2         | 0.73%   |
| 5.18.10-76051810-generic | 2         | 0.73%   |
| 5.16.7-desktop-1omv4003  | 2         | 0.73%   |
| 5.15.55-2-lts            | 2         | 0.73%   |
| 5.15.0-47-generic        | 2         | 0.73%   |
| 5.15.0-46-generic        | 2         | 0.73%   |
| 5.15.0-35-generic        | 2         | 0.73%   |
| 5.15.0-33-generic        | 2         | 0.73%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 51        | 20%     |
| 5.8.0   | 24        | 9.41%   |
| 5.11.0  | 21        | 8.24%   |
| 5.15.0  | 15        | 5.88%   |
| 5.3.0   | 11        | 4.31%   |
| 5.13.0  | 8         | 3.14%   |
| 4.15.0  | 8         | 3.14%   |
| 5.10.0  | 7         | 2.75%   |
| 5.0.0   | 7         | 2.75%   |
| 4.18.0  | 6         | 2.35%   |
| 4.19.0  | 5         | 1.96%   |
| 5.10.14 | 4         | 1.57%   |
| 4.10.0  | 4         | 1.57%   |
| 5.16.7  | 3         | 1.18%   |
| 5.9.14  | 2         | 0.78%   |
| 5.19.12 | 2         | 0.78%   |
| 5.18.16 | 2         | 0.78%   |
| 5.18.10 | 2         | 0.78%   |
| 5.15.55 | 2         | 0.78%   |
| 5.13.16 | 2         | 0.78%   |
| 4.13.0  | 2         | 0.78%   |
| 6.0.5   | 1         | 0.39%   |
| 5.9.3   | 1         | 0.39%   |
| 5.9.13  | 1         | 0.39%   |
| 5.9.1   | 1         | 0.39%   |
| 5.9.0   | 1         | 0.39%   |
| 5.8.16  | 1         | 0.39%   |
| 5.8.14  | 1         | 0.39%   |
| 5.8.12  | 1         | 0.39%   |
| 5.7.16  | 1         | 0.39%   |
| 5.7.13  | 1         | 0.39%   |
| 5.7.12  | 1         | 0.39%   |
| 5.5.2   | 1         | 0.39%   |
| 5.5.10  | 1         | 0.39%   |
| 5.4.98  | 1         | 0.39%   |
| 5.4.97  | 1         | 0.39%   |
| 5.4.80  | 1         | 0.39%   |
| 5.4.60  | 1         | 0.39%   |
| 5.4.17  | 1         | 0.39%   |
| 5.4.13  | 1         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 58        | 23.02%  |
| 5.8     | 27        | 10.71%  |
| 5.15    | 25        | 9.92%   |
| 5.11    | 22        | 8.73%   |
| 5.10    | 15        | 5.95%   |
| 5.13    | 14        | 5.56%   |
| 5.3     | 11        | 4.37%   |
| 5.0     | 10        | 3.97%   |
| 4.15    | 8         | 3.17%   |
| 5.18    | 7         | 2.78%   |
| 5.16    | 7         | 2.78%   |
| 5.9     | 6         | 2.38%   |
| 4.19    | 6         | 2.38%   |
| 4.18    | 6         | 2.38%   |
| 5.19    | 4         | 1.59%   |
| 5.14    | 4         | 1.59%   |
| 5.12    | 4         | 1.59%   |
| 4.10    | 4         | 1.59%   |
| 5.7     | 3         | 1.19%   |
| 5.17    | 3         | 1.19%   |
| 5.5     | 2         | 0.79%   |
| 4.13    | 2         | 0.79%   |
| 6.0     | 1         | 0.4%    |
| 4.4     | 1         | 0.4%    |
| 4.12    | 1         | 0.4%    |
| 4.1     | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 239       | 99.58%  |
| i686   | 1         | 0.42%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 131       | 52.61%  |
| Unknown    | 34        | 13.65%  |
| KDE5       | 30        | 12.05%  |
| XFCE       | 16        | 6.43%   |
| KDE        | 8         | 3.21%   |
| X-Cinnamon | 6         | 2.41%   |
| Unity      | 5         | 2.01%   |
| LXQt       | 4         | 1.61%   |
| Cinnamon   | 3         | 1.2%    |
| Pantheon   | 2         | 0.8%    |
| MATE       | 2         | 0.8%    |
| bspwm      | 2         | 0.8%    |
| X-Generic  | 1         | 0.4%    |
| Openbox    | 1         | 0.4%    |
| KDE4       | 1         | 0.4%    |
| Deepin     | 1         | 0.4%    |
| Budgie     | 1         | 0.4%    |
| awesome    | 1         | 0.4%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 198       | 79.84%  |
| Wayland | 28        | 11.29%  |
| Unknown | 19        | 7.66%   |
| Tty     | 3         | 1.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 127       | 51.42%  |
| GDM     | 43        | 17.41%  |
| SDDM    | 32        | 12.96%  |
| LightDM | 18        | 7.29%   |
| GDM3    | 14        | 5.67%   |
| TDM     | 10        | 4.05%   |
| XDM     | 1         | 0.4%    |
| SLiM    | 1         | 0.4%    |
| KDM     | 1         | 0.4%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 182       | 75.83%  |
| Unknown | 34        | 14.17%  |
| vi_VN   | 12        | 5%      |
| C       | 5         | 2.08%   |
| en_AU   | 3         | 1.25%   |
| en_GB   | 2         | 0.83%   |
| ru_RU   | 1         | 0.42%   |
| fr_FR   | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 160       | 64.78%  |
| BIOS | 87        | 35.22%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 201       | 82.04%  |
| Btrfs   | 16        | 6.53%   |
| Unknown | 12        | 4.9%    |
| Overlay | 11        | 4.49%   |
| Zfs     | 2         | 0.82%   |
| Xfs     | 1         | 0.41%   |
| F2fs    | 1         | 0.41%   |
| Ext3    | 1         | 0.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 124       | 51.24%  |
| GPT     | 101       | 41.74%  |
| MBR     | 17        | 7.02%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 220       | 90.16%  |
| Yes       | 24        | 9.84%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 139       | 56.5%   |
| Yes       | 107       | 43.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 65        | 27.08%  |
| Lenovo              | 51        | 21.25%  |
| Hewlett-Packard     | 37        | 15.42%  |
| ASUSTek Computer    | 32        | 13.33%  |
| Acer                | 19        | 7.92%   |
| MSI                 | 8         | 3.33%   |
| Toshiba             | 5         | 2.08%   |
| Sony                | 4         | 1.67%   |
| Apple               | 4         | 1.67%   |
| Chuwi               | 3         | 1.25%   |
| Samsung Electronics | 2         | 0.83%   |
| Timi                | 1         | 0.42%   |
| TENKU               | 1         | 0.42%   |
| Panasonic           | 1         | 0.42%   |
| MASSCOM VIETNAM     | 1         | 0.42%   |
| LG Electronics      | 1         | 0.42%   |
| Koompi              | 1         | 0.42%   |
| Jumper              | 1         | 0.42%   |
| Gigabyte Technology | 1         | 0.42%   |
| Gateway             | 1         | 0.42%   |
| AMI                 | 1         | 0.42%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Dell Inspiron 3537               | 4         | 1.67%   |
| Unknown                          | 4         | 1.67%   |
| Lenovo ThinkPad E14 20RAS0KX00   | 3         | 1.25%   |
| Lenovo Legion 5 15ARH05 82B5     | 3         | 1.25%   |
| ASUS X411UA                      | 3         | 1.25%   |
| Toshiba Satellite L840           | 2         | 0.83%   |
| MSI GF63 8RD                     | 2         | 0.83%   |
| Lenovo ThinkPad W530 2447EJ9     | 2         | 0.83%   |
| HP Notebook                      | 2         | 0.83%   |
| HP Laptop 14-bs0xx               | 2         | 0.83%   |
| HP EliteBook 8470p               | 2         | 0.83%   |
| HP EliteBook 840 G2              | 2         | 0.83%   |
| Dell XPS 15 9570                 | 2         | 0.83%   |
| Dell Vostro 5568                 | 2         | 0.83%   |
| Dell Vostro 3590                 | 2         | 0.83%   |
| Dell Vostro 3578                 | 2         | 0.83%   |
| Dell Vostro 3478                 | 2         | 0.83%   |
| Dell Vostro 3460                 | 2         | 0.83%   |
| Dell Vostro 15-3568              | 2         | 0.83%   |
| Dell System Vostro 3450          | 2         | 0.83%   |
| Dell Latitude E7440              | 2         | 0.83%   |
| Dell Inspiron 5570               | 2         | 0.83%   |
| Dell G3 3579                     | 2         | 0.83%   |
| Dell G3 3500                     | 2         | 0.83%   |
| Chuwi GemiBook Pro               | 2         | 0.83%   |
| Acer Swift SF315-52              | 2         | 0.83%   |
| Acer Predator PH315-51           | 2         | 0.83%   |
| Acer Aspire E5-575               | 2         | 0.83%   |
| Acer Aspire A315-42              | 2         | 0.83%   |
| Toshiba Satellite E45-B          | 1         | 0.42%   |
| Toshiba PORTEGE T110             | 1         | 0.42%   |
| Toshiba dynabook Satellite B35/R | 1         | 0.42%   |
| Timi A35S                        | 1         | 0.42%   |
| TENKU SB14                       | 1         | 0.42%   |
| Sony VPCEB42EG                   | 1         | 0.42%   |
| Sony VPCCW13FX                   | 1         | 0.42%   |
| Sony VGN-NW270F                  | 1         | 0.42%   |
| Sony SVE14A15FGW                 | 1         | 0.42%   |
| Samsung NC208/NC108              | 1         | 0.42%   |
| Samsung 300E4Z/300E5Z/300E7Z     | 1         | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 27        | 11.25%  |
| Dell Inspiron     | 18        | 7.5%    |
| Dell Vostro       | 16        | 6.67%   |
| Acer Aspire       | 13        | 5.42%   |
| Dell Latitude     | 12        | 5%      |
| HP EliteBook      | 11        | 4.58%   |
| Lenovo IdeaPad    | 9         | 3.75%   |
| HP ProBook        | 7         | 2.92%   |
| Lenovo Legion     | 6         | 2.5%    |
| Dell XPS          | 6         | 2.5%    |
| ASUS VivoBook     | 6         | 2.5%    |
| HP Laptop         | 5         | 2.08%   |
| Dell Precision    | 5         | 2.08%   |
| ASUS ROG          | 5         | 2.08%   |
| Lenovo ThinkBook  | 4         | 1.67%   |
| Dell System       | 4         | 1.67%   |
| Dell G3           | 4         | 1.67%   |
| ASUS ASUS         | 4         | 1.67%   |
| Unknown           | 4         | 1.67%   |
| Toshiba Satellite | 3         | 1.25%   |
| HP ZBook          | 3         | 1.25%   |
| HP Pavilion       | 3         | 1.25%   |
| ASUS X411UA       | 3         | 1.25%   |
| Acer Swift        | 3         | 1.25%   |
| Acer Predator     | 3         | 1.25%   |
| MSI GF63          | 2         | 0.83%   |
| HP Notebook       | 2         | 0.83%   |
| HP Compaq         | 2         | 0.83%   |
| Chuwi GemiBook    | 2         | 0.83%   |
| Toshiba PORTEGE   | 1         | 0.42%   |
| Toshiba dynabook  | 1         | 0.42%   |
| Timi A35S         | 1         | 0.42%   |
| TENKU SB14        | 1         | 0.42%   |
| Sony VPCEB42EG    | 1         | 0.42%   |
| Sony VPCCW13FX    | 1         | 0.42%   |
| Sony VGN-NW270F   | 1         | 0.42%   |
| Sony SVE14A15FGW  | 1         | 0.42%   |
| Samsung NC208     | 1         | 0.42%   |
| Samsung 300E4Z    | 1         | 0.42%   |
| Panasonic CFSX4-1 | 1         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 33        | 13.75%  |
| 2020 | 29        | 12.08%  |
| 2012 | 27        | 11.25%  |
| 2019 | 24        | 10%     |
| 2015 | 21        | 8.75%   |
| 2017 | 17        | 7.08%   |
| 2016 | 17        | 7.08%   |
| 2011 | 17        | 7.08%   |
| 2013 | 16        | 6.67%   |
| 2021 | 15        | 6.25%   |
| 2014 | 8         | 3.33%   |
| 2009 | 7         | 2.92%   |
| 2010 | 5         | 2.08%   |
| 2022 | 2         | 0.83%   |
| 2007 | 2         | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 240       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 219       | 90.12%  |
| Enabled  | 24        | 9.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 240       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 80        | 32.92%  |
| 16.01-24.0 | 53        | 21.81%  |
| 3.01-4.0   | 43        | 17.7%   |
| 8.01-16.0  | 43        | 17.7%   |
| 32.01-64.0 | 12        | 4.94%   |
| 1.01-2.0   | 8         | 3.29%   |
| 24.01-32.0 | 2         | 0.82%   |
| 2.01-3.0   | 1         | 0.41%   |
| 0.51-1.0   | 1         | 0.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 90        | 34.62%  |
| 1.01-2.0   | 67        | 25.77%  |
| 4.01-8.0   | 46        | 17.69%  |
| 3.01-4.0   | 40        | 15.38%  |
| 8.01-16.0  | 10        | 3.85%   |
| 0.51-1.0   | 6         | 2.31%   |
| 16.01-24.0 | 1         | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 162       | 66.94%  |
| 2      | 70        | 28.93%  |
| 3      | 8         | 3.31%   |
| 4      | 1         | 0.41%   |
| 0      | 1         | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 183       | 76.25%  |
| Yes       | 57        | 23.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 199       | 82.23%  |
| No        | 43        | 17.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 239       | 99.58%  |
| No        | 1         | 0.42%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 210       | 87.14%  |
| No        | 31        | 12.86%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Vietnam | 240       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Ho Chi Minh City | 104       | 40.94%  |
| Hanoi            | 88        | 34.65%  |
| Can Tho          | 6         | 2.36%   |
| Da Nang          | 5         | 1.97%   |
| Huế            | 4         | 1.57%   |
| Bien Hoa         | 4         | 1.57%   |
| Thuan An         | 3         | 1.18%   |
| Buon Ma Thuot    | 3         | 1.18%   |
| Vũng Tàu       | 2         | 0.79%   |
| Vinh Phuc        | 2         | 0.79%   |
| Tay Ninh         | 2         | 0.79%   |
| Nam Định      | 2         | 0.79%   |
| Binh Hoa         | 2         | 0.79%   |
| Bao Loc          | 2         | 0.79%   |
| Vinh             | 1         | 0.39%   |
| Viet Tri         | 1         | 0.39%   |
| Tra Vinh         | 1         | 0.39%   |
| Tinh Quang Binh  | 1         | 0.39%   |
| Tinh GJong Nai   | 1         | 0.39%   |
| Thu Duc          | 1         | 0.39%   |
| Thanh Hóa       | 1         | 0.39%   |
| Thai Nguyen      | 1         | 0.39%   |
| Tan An           | 1         | 0.39%   |
| Quang Trung      | 1         | 0.39%   |
| Quảng Ngai     | 1         | 0.39%   |
| Quan Muoi Mot    | 1         | 0.39%   |
| Quan Muoi        | 1         | 0.39%   |
| Quan Binh Thanh  | 1         | 0.39%   |
| Nha Trang        | 1         | 0.39%   |
| Nga Bay          | 1         | 0.39%   |
| Lien Chieu       | 1         | 0.39%   |
| Hoa Binh         | 1         | 0.39%   |
| Haiphong         | 1         | 0.39%   |
| Go Vap           | 1         | 0.39%   |
| Do Son           | 1         | 0.39%   |
| Dien Ban         | 1         | 0.39%   |
| Can Duoc         | 1         | 0.39%   |
| Bến Tre        | 1         | 0.39%   |
| Bac Giang        | 1         | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 56     | 14.02%  |
| WDC                 | 40        | 47     | 12.46%  |
| Toshiba             | 29        | 34     | 9.03%   |
| Seagate             | 28        | 33     | 8.72%   |
| HGST                | 21        | 22     | 6.54%   |
| SK hynix            | 18        | 20     | 5.61%   |
| Intel               | 17        | 18     | 5.3%    |
| Unknown             | 13        | 13     | 4.05%   |
| Kingston            | 11        | 13     | 3.43%   |
| Micron Technology   | 10        | 12     | 3.12%   |
| Hitachi             | 9         | 13     | 2.8%    |
| Crucial             | 9         | 9      | 2.8%    |
| Sandisk             | 6         | 7      | 1.87%   |
| Plextor             | 6         | 6      | 1.87%   |
| OSCOO               | 5         | 6      | 1.56%   |
| TO Exter            | 4         | 6      | 1.25%   |
| Transcend           | 3         | 3      | 0.93%   |
| LITEON              | 3         | 3      | 0.93%   |
| KIOXIA              | 3         | 3      | 0.93%   |
| Colorful            | 3         | 3      | 0.93%   |
| UMIS                | 2         | 2      | 0.62%   |
| Lexar               | 2         | 2      | 0.62%   |
| KingSpec            | 2         | 2      | 0.62%   |
| KingDian            | 2         | 3      | 0.62%   |
| Hikvision           | 2         | 2      | 0.62%   |
| FORESEE             | 2         | 2      | 0.62%   |
| Apple               | 2         | 2      | 0.62%   |
| W800S               | 1         | 1      | 0.31%   |
| SPCC                | 1         | 1      | 0.31%   |
| Silicon Motion      | 1         | 3      | 0.31%   |
| Phison              | 1         | 1      | 0.31%   |
| OSC                 | 1         | 1      | 0.31%   |
| NGFF                | 1         | 1      | 0.31%   |
| Netac               | 1         | 1      | 0.31%   |
| Maxtor              | 1         | 2      | 0.31%   |
| LITEONIT            | 1         | 1      | 0.31%   |
| Lite-On             | 1         | 3      | 0.31%   |
| Lenovo              | 1         | 1      | 0.31%   |
| KLEVV               | 1         | 1      | 0.31%   |
| KIOXIA-EXCERIA      | 1         | 2      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB                  | 8         | 2.44%   |
| Seagate ST1000LM035-1RK172 1TB            | 7         | 2.13%   |
| Toshiba MQ04ABF100 1TB                    | 5         | 1.52%   |
| Samsung NVMe SSD Drive 512GB              | 5         | 1.52%   |
| WDC WDS240G2G0A-00JH30 240GB SSD          | 4         | 1.22%   |
| Toshiba MQ01ABF050 500GB                  | 4         | 1.22%   |
| TO Exter nal USB 3.0 1TB                  | 4         | 1.22%   |
| SK hynix NVMe SSD Drive 256GB             | 4         | 1.22%   |
| Seagate ST1000LM049-2GH172 1TB            | 4         | 1.22%   |
| Samsung MZALQ512HALU-000L2 512GB          | 4         | 1.22%   |
| Crucial CT240BX500SSD1 240GB              | 4         | 1.22%   |
| WDC WD5000LPLX-08ZNTT0 500GB              | 3         | 0.91%   |
| Toshiba MQ01ABD100 1TB                    | 3         | 0.91%   |
| SK hynix NVMe SSD Drive 512GB             | 3         | 0.91%   |
| Seagate ST9500325AS 500GB                 | 3         | 0.91%   |
| Seagate ST500LT012-9WS142 500GB           | 3         | 0.91%   |
| Samsung SSD 860 EVO 500GB                 | 3         | 0.91%   |
| Kingston SA400S37120G 120GB SSD           | 3         | 0.91%   |
| Kingston NVMe SSD Drive 256GB             | 3         | 0.91%   |
| Hitachi HTS545050A7E380 500GB             | 3         | 0.91%   |
| HGST HTS545050A7E680 500GB                | 3         | 0.91%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD          | 2         | 0.61%   |
| WDC WD5000LPCX-21VHAT0 500GB              | 2         | 0.61%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 2         | 0.61%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 2         | 0.61%   |
| WDC PC SN720 SDAPNTW-256G-1006 256GB      | 2         | 0.61%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB      | 2         | 0.61%   |
| Unknown NVMe SSD Drive 256GB              | 2         | 0.61%   |
| Unknown MMC Card  32GB                    | 2         | 0.61%   |
| Toshiba NVMe SSD Drive 256GB              | 2         | 0.61%   |
| Toshiba MK2035GSS 200GB                   | 2         | 0.61%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB | 2         | 0.61%   |
| SK hynix BC511 NVMe 512GB                 | 2         | 0.61%   |
| SanDisk NVMe SSD Drive 500GB              | 2         | 0.61%   |
| Samsung SSD 860 EVO 250GB                 | 2         | 0.61%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB    | 2         | 0.61%   |
| Samsung MZVLQ512HBLU-00B00 512GB          | 2         | 0.61%   |
| Plextor PX-256M8VC 256GB SSD              | 2         | 0.61%   |
| OSCOO OSC SSD 128GB                       | 2         | 0.61%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD       | 2         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 28        | 33     | 26.92%  |
| WDC     | 25        | 32     | 24.04%  |
| Toshiba | 21        | 21     | 20.19%  |
| HGST    | 21        | 22     | 20.19%  |
| Hitachi | 9         | 13     | 8.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 17     | 14.55%  |
| WDC                 | 9         | 9      | 8.18%   |
| Crucial             | 9         | 9      | 8.18%   |
| Intel               | 8         | 9      | 7.27%   |
| Plextor             | 6         | 6      | 5.45%   |
| Kingston            | 5         | 6      | 4.55%   |
| TO Exter            | 4         | 6      | 3.64%   |
| SK hynix            | 4         | 4      | 3.64%   |
| Transcend           | 3         | 3      | 2.73%   |
| OSCOO               | 3         | 3      | 2.73%   |
| Micron Technology   | 3         | 3      | 2.73%   |
| LITEON              | 3         | 3      | 2.73%   |
| Toshiba             | 2         | 3      | 1.82%   |
| SanDisk             | 2         | 3      | 1.82%   |
| Lexar               | 2         | 2      | 1.82%   |
| KingSpec            | 2         | 2      | 1.82%   |
| KingDian            | 2         | 3      | 1.82%   |
| Hikvision           | 2         | 2      | 1.82%   |
| FORESEE             | 2         | 2      | 1.82%   |
| Colorful            | 2         | 2      | 1.82%   |
| Apple               | 2         | 2      | 1.82%   |
| W800S               | 1         | 1      | 0.91%   |
| Unknown             | 1         | 1      | 0.91%   |
| SPCC                | 1         | 1      | 0.91%   |
| OSC                 | 1         | 1      | 0.91%   |
| NGFF                | 1         | 1      | 0.91%   |
| Netac               | 1         | 1      | 0.91%   |
| Maxtor              | 1         | 2      | 0.91%   |
| LITEONIT            | 1         | 1      | 0.91%   |
| KLEVV               | 1         | 1      | 0.91%   |
| KIOXIA-EXCERIA      | 1         | 2      | 0.91%   |
| Kingmax             | 1         | 1      | 0.91%   |
| KimMiDi             | 1         | 1      | 0.91%   |
| Indilinx            | 1         | 1      | 0.91%   |
| HXY                 | 1         | 2      | 0.91%   |
| Hewlett-Packard     | 1         | 1      | 0.91%   |
| Gigabyte Technology | 1         | 1      | 0.91%   |
| China               | 1         | 1      | 0.91%   |
| Apacer              | 1         | 1      | 0.91%   |
| AGI                 | 1         | 1      | 0.91%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 101       | 121    | 33.01%  |
| HDD     | 100       | 121    | 32.68%  |
| NVMe    | 92        | 118    | 30.07%  |
| MMC     | 9         | 9      | 2.94%   |
| Unknown | 4         | 4      | 1.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 169       | 238    | 61.23%  |
| NVMe | 92        | 118    | 33.33%  |
| MMC  | 9         | 9      | 3.26%   |
| SAS  | 6         | 8      | 2.17%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 141       | 183    | 73.44%  |
| 0.51-1.0   | 50        | 58     | 26.04%  |
| 1.01-2.0   | 1         | 1      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 94        | 37.6%   |
| 251-500        | 58        | 23.2%   |
| 51-100         | 25        | 10%     |
| 501-1000       | 20        | 8%      |
| 1001-2000      | 15        | 6%      |
| 1-20           | 12        | 4.8%    |
| 21-50          | 11        | 4.4%    |
| Unknown        | 10        | 4%      |
| 2001-3000      | 4         | 1.6%    |
| More than 3000 | 1         | 0.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 112       | 44.27%  |
| 21-50          | 48        | 18.97%  |
| 51-100         | 33        | 13.04%  |
| 101-250        | 22        | 8.7%    |
| 251-500        | 16        | 6.32%   |
| 501-1000       | 10        | 3.95%   |
| Unknown        | 10        | 3.95%   |
| More than 3000 | 1         | 0.4%    |
| 1001-2000      | 1         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB               | 2         | 2      | 8%      |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1         | 1      | 4%      |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 4%      |
| WDC WD5000LPLX-60ZNTT1 500GB                 | 1         | 1      | 4%      |
| WDC WD32 00BEVT-24A23 320GB                  | 1         | 1      | 4%      |
| WDC WD10JPVX-75JC3T0 1TB                     | 1         | 1      | 4%      |
| Unknown Bamba-240GB SSD                      | 1         | 1      | 4%      |
| Toshiba MQ01ABD050 500GB                     | 1         | 1      | 4%      |
| Toshiba MK8046GSX 80GB                       | 1         | 1      | 4%      |
| Toshiba MK3265GSXN 320GB                     | 1         | 1      | 4%      |
| Toshiba HDWK105 500GB                        | 1         | 1      | 4%      |
| SK hynix HFS032G34MNC-2200A 32GB SSD         | 1         | 1      | 4%      |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 4%      |
| Samsung Electronics MZVPW128HEGM-00000 128GB | 1         | 1      | 4%      |
| LITEON LCH-256V2S 256GB SSD                  | 1         | 1      | 4%      |
| Hitachi HTS725050A7E635 500GB                | 1         | 1      | 4%      |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 4%      |
| Hitachi HTS543232A7A384 320GB                | 1         | 1      | 4%      |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 4%      |
| HGST HTS725032A7E630 320GB                   | 1         | 1      | 4%      |
| HGST HTS545050A7E680 500GB                   | 1         | 2      | 4%      |
| HGST HTS545050A7 500GB                       | 1         | 1      | 4%      |
| HGST HTS541010A7E630 1TB                     | 1         | 1      | 4%      |
| Crucial CT525MX300SSD1 528GB                 | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 20%     |
| HGST                | 5         | 6      | 20%     |
| Toshiba             | 4         | 4      | 16%     |
| Seagate             | 3         | 3      | 12%     |
| Hitachi             | 3         | 3      | 12%     |
| Unknown             | 1         | 1      | 4%      |
| SK hynix            | 1         | 1      | 4%      |
| Samsung Electronics | 1         | 1      | 4%      |
| LITEON              | 1         | 1      | 4%      |
| Crucial             | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 5         | 6      | 26.32%  |
| WDC     | 4         | 4      | 21.05%  |
| Toshiba | 4         | 4      | 21.05%  |
| Seagate | 3         | 3      | 15.79%  |
| Hitachi | 3         | 3      | 15.79%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 20     | 76%     |
| SSD  | 5         | 5      | 20%     |
| NVMe | 1         | 1      | 4%      |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 137       | 204    | 51.89%  |
| Works    | 103       | 143    | 39.02%  |
| Malfunc  | 24        | 26     | 9.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 200       | 65.36%  |
| Samsung Electronics            | 34        | 11.11%  |
| AMD                            | 16        | 5.23%   |
| SK hynix                       | 14        | 4.58%   |
| SanDisk                        | 9         | 2.94%   |
| Micron Technology              | 7         | 2.29%   |
| Toshiba America Info Systems   | 6         | 1.96%   |
| Kingston Technology Company    | 6         | 1.96%   |
| KIOXIA                         | 4         | 1.31%   |
| Union Memory (Shenzhen)        | 2         | 0.65%   |
| Solid State Storage Technology | 2         | 0.65%   |
| Silicon Motion                 | 2         | 0.65%   |
| Phison Electronics             | 2         | 0.65%   |
| Lite-On Technology             | 1         | 0.33%   |
| Lenovo                         | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 31        | 9.81%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 29        | 9.18%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 16        | 5.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 4.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 13        | 4.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 4.11%   |
| Samsung NVMe SSD Controller 980                                                | 12        | 3.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 12        | 3.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 12        | 3.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 11        | 3.48%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 2.85%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 2.53%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 8         | 2.53%   |
| Micron Non-Volatile memory controller                                          | 7         | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.22%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 6         | 1.9%    |
| Intel Tiger Lake-LP SATA Controller                                            | 5         | 1.58%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 5         | 1.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 1.58%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 4         | 1.27%   |
| SK hynix Gold P31 SSD                                                          | 4         | 1.27%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 4         | 1.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.27%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 1.27%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3         | 0.95%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 0.95%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 3         | 0.95%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 0.95%   |
| Intel SSD 660P Series                                                          | 3         | 0.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 0.95%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 0.63%   |
| Solid State Storage Non-Volatile memory controller                             | 2         | 0.63%   |
| SK hynix Non-Volatile memory controller                                        | 2         | 0.63%   |
| SK hynix BC511                                                                 | 2         | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 2         | 0.63%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.63%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 193       | 62.26%  |
| NVMe | 93        | 30%     |
| RAID | 20        | 6.45%   |
| IDE  | 4         | 1.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 217       | 90.42%  |
| AMD    | 23        | 9.58%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 6.25%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 3.33%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 2.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 2.92%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 2.92%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 2.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 2.08%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 2.08%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 1.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.67%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 1.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 1.67%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.67%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 1.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.67%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 3         | 1.25%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 1.25%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 1.25%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 1.25%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 1.25%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 1.25%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.25%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.25%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.25%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.83%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.83%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.83%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.83%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.83%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.83%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.83%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.83%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.83%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.83%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.83%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 2         | 0.83%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 2         | 0.83%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 2         | 0.83%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 92        | 38.33%  |
| Intel Core i7    | 53        | 22.08%  |
| Intel Core i3    | 28        | 11.67%  |
| Other            | 18        | 7.5%    |
| Intel Celeron    | 10        | 4.17%   |
| AMD Ryzen 5      | 10        | 4.17%   |
| Intel Core 2 Duo | 7         | 2.92%   |
| AMD Ryzen 7      | 7         | 2.92%   |
| Intel Atom       | 4         | 1.67%   |
| Intel Pentium    | 2         | 0.83%   |
| Intel Genuine    | 2         | 0.83%   |
| AMD Ryzen 3      | 2         | 0.83%   |
| Intel Xeon       | 1         | 0.42%   |
| AMD Ryzen 9      | 1         | 0.42%   |
| AMD Ryzen 7 PRO  | 1         | 0.42%   |
| AMD Ryzen 5 PRO  | 1         | 0.42%   |
| AMD A8           | 1         | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 113       | 47.08%  |
| 4      | 90        | 37.5%   |
| 6      | 22        | 9.17%   |
| 8      | 12        | 5%      |
| 1      | 2         | 0.83%   |
| 14     | 1         | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 240       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 212       | 88.33%  |
| 1      | 28        | 11.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 236       | 97.93%  |
| Unknown        | 5         | 2.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 16.53%  |
| 0x306a9    | 25        | 10.08%  |
| 0x806ea    | 19        | 7.66%   |
| 0x806ec    | 13        | 5.24%   |
| 0x40651    | 13        | 5.24%   |
| 0x206a7    | 13        | 5.24%   |
| 0x806c1    | 12        | 4.84%   |
| 0x306d4    | 12        | 4.84%   |
| 0x806e9    | 10        | 4.03%   |
| 0x906ea    | 9         | 3.63%   |
| 0x406e3    | 7         | 2.82%   |
| 0x906e9    | 6         | 2.42%   |
| 0x506e3    | 6         | 2.42%   |
| 0x306c3    | 6         | 2.42%   |
| 0xa0652    | 4         | 1.61%   |
| 0x6fd      | 4         | 1.61%   |
| 0x08600106 | 4         | 1.61%   |
| 0x08108102 | 4         | 1.61%   |
| 0x806d1    | 3         | 1.21%   |
| 0x706e5    | 3         | 1.21%   |
| 0x20655    | 3         | 1.21%   |
| 0x1067a    | 3         | 1.21%   |
| 0x0a50000c | 3         | 1.21%   |
| 0x08600104 | 3         | 1.21%   |
| 0x906ed    | 2         | 0.81%   |
| 0x906c0    | 2         | 0.81%   |
| 0x706a1    | 2         | 0.81%   |
| 0x406c4    | 2         | 0.81%   |
| 0x906a3    | 1         | 0.4%    |
| 0x806eb    | 1         | 0.4%    |
| 0x806c2    | 1         | 0.4%    |
| 0x406c3    | 1         | 0.4%    |
| 0x40661    | 1         | 0.4%    |
| 0x30661    | 1         | 0.4%    |
| 0x20652    | 1         | 0.4%    |
| 0x106e5    | 1         | 0.4%    |
| 0x106ca    | 1         | 0.4%    |
| 0x0a50000b | 1         | 0.4%    |
| 0x0a404102 | 1         | 0.4%    |
| 0x08600103 | 1         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 68        | 28.33%  |
| IvyBridge        | 28        | 11.67%  |
| Haswell          | 22        | 9.17%   |
| Skylake          | 16        | 6.67%   |
| SandyBridge      | 15        | 6.25%   |
| TigerLake        | 14        | 5.83%   |
| Broadwell        | 14        | 5.83%   |
| Zen 2            | 10        | 4.17%   |
| Zen+             | 6         | 2.5%    |
| IceLake          | 6         | 2.5%    |
| Zen 3            | 5         | 2.08%   |
| Core             | 5         | 2.08%   |
| CometLake        | 5         | 2.08%   |
| Westmere         | 4         | 1.67%   |
| Silvermont       | 4         | 1.67%   |
| Penryn           | 4         | 1.67%   |
| Goldmont plus    | 4         | 1.67%   |
| Tremont          | 2         | 0.83%   |
| Bonnell          | 2         | 0.83%   |
| Unknown          | 2         | 0.83%   |
| Puma             | 1         | 0.42%   |
| Nehalem          | 1         | 0.42%   |
| Goldmont         | 1         | 0.42%   |
| Alderlake Hybrid | 1         | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 205       | 62.12%  |
| Nvidia | 84        | 25.45%  |
| AMD    | 41        | 12.42%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 27        | 8.08%   |
| Intel UHD Graphics 620                                                                   | 21        | 6.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 4.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 4.19%   |
| Intel HD Graphics 5500                                                                   | 13        | 3.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 3.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 3.59%   |
| Intel HD Graphics 620                                                                    | 10        | 2.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.69%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 2.69%   |
| AMD Renoir                                                                               | 9         | 2.69%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 1.8%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 1.8%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.8%    |
| Intel HD Graphics 530                                                                    | 6         | 1.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.5%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.5%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.5%    |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 5         | 1.5%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 1.2%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.2%    |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 1.2%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.2%    |
| Intel HD Graphics 630                                                                    | 4         | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.2%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.2%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.2%    |
| AMD Cezanne                                                                              | 4         | 1.2%    |
| Nvidia TU117M                                                                            | 3         | 0.9%    |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.9%    |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 3         | 0.9%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 3         | 0.9%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.9%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.9%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.9%    |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.6%    |
| Nvidia GP108M [GeForce MX330]                                                            | 2         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 123       | 51.25%  |
| Intel + Nvidia | 62        | 25.83%  |
| Intel + AMD    | 20        | 8.33%   |
| 1 x Nvidia     | 14        | 5.83%   |
| 1 x AMD        | 11        | 4.58%   |
| AMD + Nvidia   | 8         | 3.33%   |
| 2 x AMD        | 2         | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 188       | 77.05%  |
| Proprietary | 55        | 22.54%  |
| Unknown     | 1         | 0.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 156       | 63.67%  |
| 1.01-2.0   | 37        | 15.1%   |
| 3.01-4.0   | 23        | 9.39%   |
| 0.51-1.0   | 11        | 4.49%   |
| 0.01-0.5   | 11        | 4.49%   |
| 5.01-6.0   | 3         | 1.22%   |
| 2.01-3.0   | 2         | 0.82%   |
| 7.01-8.0   | 1         | 0.41%   |
| 8.01-16.0  | 1         | 0.41%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 50        | 18.52%  |
| AU Optronics            | 44        | 16.3%   |
| LG Display              | 41        | 15.19%  |
| Chimei Innolux          | 41        | 15.19%  |
| Samsung Electronics     | 23        | 8.52%   |
| Dell                    | 13        | 4.81%   |
| PANDA                   | 10        | 3.7%    |
| Sharp                   | 9         | 3.33%   |
| Lenovo                  | 6         | 2.22%   |
| InfoVision              | 5         | 1.85%   |
| LGD                     | 4         | 1.48%   |
| Goldstar                | 4         | 1.48%   |
| Apple                   | 4         | 1.48%   |
| Chi Mei Optoelectronics | 3         | 1.11%   |
| ViewSonic               | 2         | 0.74%   |
| ASUSTek Computer        | 2         | 0.74%   |
| AOC                     | 2         | 0.74%   |
| Sony                    | 1         | 0.37%   |
| RTK                     | 1         | 0.37%   |
| Philips                 | 1         | 0.37%   |
| MStar                   | 1         | 0.37%   |
| LG Philips              | 1         | 0.37%   |
| Hewlett-Packard         | 1         | 0.37%   |
| CSO                     | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 5         | 1.85%   |
| LGD LCD Monitor 1920x1080                                             | 4         | 1.48%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 4         | 1.48%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 4         | 1.48%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch  | 3         | 1.11%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 1.11%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 3         | 1.11%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.11%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 3         | 1.11%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.74%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 2         | 0.74%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 310x170mm 13.9-inch  | 2         | 0.74%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 2         | 0.74%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch          | 2         | 0.74%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 2         | 0.74%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 2         | 0.74%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 2         | 0.74%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 2         | 0.74%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch           | 2         | 0.74%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 2         | 0.74%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.74%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch      | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch       | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 309x174mm 14.0-inch       | 2         | 0.74%   |
| BOE LCD Monitor BOE08E7 1920x1080 344x193mm 15.5-inch                 | 2         | 0.74%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 2         | 0.74%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                 | 2         | 0.74%   |
| BOE LCD Monitor BOE070D 1366x768 309x173mm 13.9-inch                  | 2         | 0.74%   |
| BOE LCD Monitor BOE06F3 1920x1080 309x173mm 13.9-inch                 | 2         | 0.74%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 0.74%   |
| BOE LCD Monitor BOE05EA 1366x768 309x173mm 13.9-inch                  | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO71ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 2         | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 139       | 53.88%  |
| 1366x768 (WXGA)   | 77        | 29.84%  |
| 2560x1440 (QHD)   | 7         | 2.71%   |
| 3840x2160 (4K)    | 6         | 2.33%   |
| 1920x1200 (WUXGA) | 6         | 2.33%   |
| 1280x800 (WXGA)   | 6         | 2.33%   |
| 1600x900 (HD+)    | 4         | 1.55%   |
| 2880x1800         | 2         | 0.78%   |
| 2560x1600         | 2         | 0.78%   |
| 2160x1440         | 2         | 0.78%   |
| 1440x900 (WXGA+)  | 2         | 0.78%   |
| 3456x2160         | 1         | 0.39%   |
| 3440x1440         | 1         | 0.39%   |
| 3200x1800 (QHD+)  | 1         | 0.39%   |
| 2560x1080         | 1         | 0.39%   |
| 1024x600          | 1         | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 111       | 41.42%  |
| 14      | 51        | 19.03%  |
| 13      | 48        | 17.91%  |
| 21      | 8         | 2.99%   |
| 23      | 7         | 2.61%   |
| 12      | 7         | 2.61%   |
| 17      | 6         | 2.24%   |
| 27      | 5         | 1.87%   |
| 18      | 5         | 1.87%   |
| Unknown | 5         | 1.87%   |
| 24      | 3         | 1.12%   |
| 31      | 2         | 0.75%   |
| 11      | 2         | 0.75%   |
| 54      | 1         | 0.37%   |
| 52      | 1         | 0.37%   |
| 46      | 1         | 0.37%   |
| 34      | 1         | 0.37%   |
| 28      | 1         | 0.37%   |
| 19      | 1         | 0.37%   |
| 16      | 1         | 0.37%   |
| 10      | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 196       | 73.13%  |
| 201-300     | 23        | 8.58%   |
| 501-600     | 14        | 5.22%   |
| 401-500     | 14        | 5.22%   |
| 351-400     | 8         | 2.99%   |
| Unknown     | 5         | 1.87%   |
| 601-700     | 4         | 1.49%   |
| 1001-1500   | 3         | 1.12%   |
| 701-800     | 1         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 214       | 88.43%  |
| 16/10   | 19        | 7.85%   |
| Unknown | 5         | 2.07%   |
| 3/2     | 2         | 0.83%   |
| 21/9    | 2         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 110       | 40.74%  |
| 81-90          | 90        | 33.33%  |
| 201-250        | 17        | 6.3%    |
| 71-80          | 9         | 3.33%   |
| 61-70          | 7         | 2.59%   |
| 121-130        | 6         | 2.22%   |
| 301-350        | 5         | 1.85%   |
| Unknown        | 5         | 1.85%   |
| 141-150        | 4         | 1.48%   |
| 351-500        | 3         | 1.11%   |
| 251-300        | 3         | 1.11%   |
| 151-200        | 3         | 1.11%   |
| More than 1000 | 2         | 0.74%   |
| 51-60          | 2         | 0.74%   |
| 41-50          | 1         | 0.37%   |
| 111-120        | 1         | 0.37%   |
| 501-1000       | 1         | 0.37%   |
| 91-100         | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 133       | 50.38%  |
| 101-120       | 80        | 30.3%   |
| 51-100        | 24        | 9.09%   |
| 161-240       | 14        | 5.3%    |
| More than 240 | 5         | 1.89%   |
| Unknown       | 5         | 1.89%   |
| 1-50          | 3         | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 207       | 84.84%  |
| 2     | 30        | 12.3%   |
| 3     | 4         | 1.64%   |
| 0     | 3         | 1.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 141       | 36.25%  |
| Realtek Semiconductor                  | 138       | 35.48%  |
| Qualcomm Atheros                       | 56        | 14.4%   |
| Broadcom                               | 20        | 5.14%   |
| Broadcom Limited                       | 8         | 2.06%   |
| MediaTek                               | 6         | 1.54%   |
| Marvell Technology Group               | 5         | 1.29%   |
| TP-Link                                | 2         | 0.51%   |
| Samsung Electronics                    | 2         | 0.51%   |
| Hewlett-Packard                        | 2         | 0.51%   |
| Xiaomi                                 | 1         | 0.26%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.26%   |
| SEGGER                                 | 1         | 0.26%   |
| Ralink Technology                      | 1         | 0.26%   |
| Qualcomm                               | 1         | 0.26%   |
| Huawei Technologies                    | 1         | 0.26%   |
| Foxconn / Hon Hai                      | 1         | 0.26%   |
| D-Link                                 | 1         | 0.26%   |
| ASUSTek Computer                       | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94        | 20.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 15        | 3.29%   |
| Intel Wireless 3165                                               | 14        | 3.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 3.07%   |
| Intel Wi-Fi 6 AX201                                               | 11        | 2.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 10        | 2.19%   |
| Intel Wireless 8265 / 8275                                        | 10        | 2.19%   |
| Intel Wireless 7265                                               | 10        | 2.19%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 2.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 10        | 2.19%   |
| Intel Wireless 7260                                               | 9         | 1.97%   |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 1.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8         | 1.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 8         | 1.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.54%   |
| Intel Centrino Ultimate-N 6300                                    | 7         | 1.54%   |
| Intel Wireless 8260                                               | 6         | 1.32%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 1.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.1%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 0.88%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.88%   |
| Intel Wireless 3160                                               | 4         | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.88%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.66%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.66%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.66%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 3         | 0.66%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 3         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 132       | 53.44%  |
| Qualcomm Atheros      | 48        | 19.43%  |
| Realtek Semiconductor | 29        | 11.74%  |
| Broadcom              | 18        | 7.29%   |
| Broadcom Limited      | 8         | 3.24%   |
| MediaTek              | 6         | 2.43%   |
| TP-Link               | 2         | 0.81%   |
| Xiaomi                | 1         | 0.4%    |
| Ralink Technology     | 1         | 0.4%    |
| D-Link                | 1         | 0.4%    |
| ASUSTek Computer      | 1         | 0.4%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 15        | 6.05%   |
| Intel Wireless 3165                                            | 14        | 5.65%   |
| Intel Wi-Fi 6 AX201                                            | 11        | 4.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10        | 4.03%   |
| Intel Wireless 8265 / 8275                                     | 10        | 4.03%   |
| Intel Wireless 7265                                            | 10        | 4.03%   |
| Intel Wi-Fi 6 AX200                                            | 10        | 4.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 10        | 4.03%   |
| Intel Wireless 7260                                            | 9         | 3.63%   |
| Broadcom BCM43142 802.11b/g/n                                  | 9         | 3.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 8         | 3.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 8         | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 7         | 2.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 2.82%   |
| Intel Centrino Ultimate-N 6300                                 | 7         | 2.82%   |
| Intel Wireless 8260                                            | 6         | 2.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 2.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 2.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 2.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 2.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 2.02%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 2.02%   |
| Intel Wireless 3160                                            | 4         | 1.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.61%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 1.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 1.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.21%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 3         | 1.21%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 3         | 1.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.21%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.81%   |
| Intel Wireless-AC 9260                                         | 2         | 0.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 0.81%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 0.81%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 2         | 0.81%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 0.81%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 2         | 0.81%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 0.81%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 2         | 0.81%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                              | 1         | 0.4%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 126       | 61.76%  |
| Intel                                  | 48        | 23.53%  |
| Qualcomm Atheros                       | 14        | 6.86%   |
| Marvell Technology Group               | 5         | 2.45%   |
| Broadcom                               | 4         | 1.96%   |
| Samsung Electronics                    | 2         | 0.98%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.49%   |
| Qualcomm                               | 1         | 0.49%   |
| Huawei Technologies                    | 1         | 0.49%   |
| Hewlett-Packard                        | 1         | 0.49%   |
| Foxconn / Hon Hai                      | 1         | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 94        | 45.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 24        | 11.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 14        | 6.8%    |
| Intel Ethernet Connection (3) I218-LM                                          | 6         | 2.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 1.94%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 4         | 1.94%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 1.94%   |
| Intel Ethernet Connection (4) I219-LM                                          | 4         | 1.94%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.46%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.46%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.46%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.97%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 2         | 0.97%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.97%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.97%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.97%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 0.97%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.97%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.97%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.97%   |
| Sony Ericsson Mobile AB D6503                                                  | 1         | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.49%   |
| Realtek Realtek Ethernet controller                                            | 1         | 0.49%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.49%   |
| Qualcomm Mobile Router                                                         | 1         | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.49%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.49%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 1         | 0.49%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.49%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.49%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.49%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.49%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.49%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.49%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.49%   |
| Intel 82562GT 10/100 Network Connection                                        | 1         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 239       | 54.44%  |
| Ethernet | 198       | 45.1%   |
| Modem    | 2         | 0.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 206       | 81.42%  |
| Ethernet | 47        | 18.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 192       | 80%     |
| 1     | 46        | 19.17%  |
| 3     | 1         | 0.42%   |
| 0     | 1         | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 193       | 78.46%  |
| Yes  | 53        | 21.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 109       | 51.42%  |
| Qualcomm Atheros Communications | 25        | 11.79%  |
| Broadcom                        | 19        | 8.96%   |
| Realtek Semiconductor           | 18        | 8.49%   |
| IMC Networks                    | 12        | 5.66%   |
| Lite-On Technology              | 10        | 4.72%   |
| Hewlett-Packard                 | 4         | 1.89%   |
| Foxconn / Hon Hai               | 4         | 1.89%   |
| Apple                           | 4         | 1.89%   |
| Dell                            | 3         | 1.42%   |
| Toshiba                         | 1         | 0.47%   |
| MediaTek                        | 1         | 0.47%   |
| Cambridge Silicon Radio         | 1         | 0.47%   |
| Alps Electric                   | 1         | 0.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 49        | 23.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 21        | 9.91%   |
| Intel AX201 Bluetooth                             | 18        | 8.49%   |
| Qualcomm Atheros  Bluetooth Device                | 15        | 7.08%   |
| Intel AX200 Bluetooth                             | 10        | 4.72%   |
| Realtek Bluetooth Radio                           | 9         | 4.25%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 6         | 2.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 6         | 2.83%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter           | 4         | 1.89%   |
| Realtek  Bluetooth 4.2 Adapter                    | 4         | 1.89%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 4         | 1.89%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 3         | 1.42%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 3         | 1.42%   |
| IMC Networks Wireless_Device                      | 3         | 1.42%   |
| IMC Networks Bluetooth Radio                      | 3         | 1.42%   |
| HP Broadcom 2070 Bluetooth Combo                  | 3         | 1.42%   |
| Broadcom HP Portable SoftSailing                  | 3         | 1.42%   |
| Broadcom BCM43142 Bluetooth 4.0                   | 3         | 1.42%   |
| Apple Bluetooth Host Controller                   | 3         | 1.42%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 0.94%   |
| Qualcomm Atheros Bluetooth USB Host Controller    | 2         | 0.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 2         | 0.94%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 2         | 0.94%   |
| Intel AX210 Bluetooth                             | 2         | 0.94%   |
| IMC Networks Bluetooth Device                     | 2         | 0.94%   |
| Foxconn / Hon Hai Wireless_Device                 | 2         | 0.94%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR              | 2         | 0.94%   |
| Toshiba Bluetooth USB Host Controller             | 1         | 0.47%   |
| Realtek RTL8723B Bluetooth                        | 1         | 0.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 1         | 0.47%   |
| Qualcomm Atheros AR3012 Bluetooth                 | 1         | 0.47%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 1         | 0.47%   |
| MediaTek Wireless_Device                          | 1         | 0.47%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device      | 1         | 0.47%   |
| Lite-On Bluetooth Radio                           | 1         | 0.47%   |
| Lite-On BCM43142A0                                | 1         | 0.47%   |
| Lite-On Atheros Bluetooth                         | 1         | 0.47%   |
| Intel Wireless-AC 3168 Bluetooth                  | 1         | 0.47%   |
| Intel Bluetooth Device                            | 1         | 0.47%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 1         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 215       | 74.65%  |
| Nvidia                 | 42        | 14.58%  |
| AMD                    | 23        | 7.99%   |
| Realtek Semiconductor  | 1         | 0.35%   |
| Plantronics            | 1         | 0.35%   |
| OPPO Electronics       | 1         | 0.35%   |
| JMTek                  | 1         | 0.35%   |
| GN Netcom              | 1         | 0.35%   |
| Generalplus Technology | 1         | 0.35%   |
| Apple                  | 1         | 0.35%   |
| Unknown                | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 42        | 12.28%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 30        | 8.77%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 22        | 6.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 14        | 4.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 4.09%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 4.09%   |
| Intel Cannon Lake PCH cAVS                                                                        | 14        | 4.09%   |
| Intel Broadwell-U Audio Controller                                                                | 14        | 4.09%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 4.09%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 3.8%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 2.92%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 2.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 7         | 2.05%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 6         | 1.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 1.75%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.46%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.46%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.17%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.17%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.17%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.88%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 0.88%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.58%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.58%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.58%   |
| Nvidia Audio device                                                                               | 2         | 0.58%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.58%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 0.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.58%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.29%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 54        | 29.35%  |
| SK hynix            | 38        | 20.65%  |
| Kingston            | 31        | 16.85%  |
| Micron Technology   | 27        | 14.67%  |
| Ramaxel Technology  | 6         | 3.26%   |
| Crucial             | 6         | 3.26%   |
| Unknown             | 5         | 2.72%   |
| Corsair             | 4         | 2.17%   |
| G.Skill             | 3         | 1.63%   |
| Elpida              | 3         | 1.63%   |
| Apacer              | 2         | 1.09%   |
| A-DATA Technology   | 2         | 1.09%   |
| Unknown (7FE0)      | 1         | 0.54%   |
| Team                | 1         | 0.54%   |
| Kingmax             | 1         | 0.54%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 5         | 2.5%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 5         | 2.5%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 2%      |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 4         | 2%      |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 4         | 2%      |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 4         | 2%      |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 1.5%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s         | 3         | 1.5%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 3         | 1.5%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s           | 3         | 1.5%    |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s           | 3         | 1.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 1%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 1%      |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 1%      |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 1%      |
| SK hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s   | 2         | 1%      |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 2         | 1%      |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s        | 2         | 1%      |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s         | 2         | 1%      |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                 | 2         | 1%      |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 1%      |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 1%      |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 1%      |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 1%      |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 1%      |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s      | 2         | 1%      |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 2         | 1%      |
| Micron RAM 53E1G32D4NQ-046WTE 4GB Row Of Chips LPDDR4 3200MT/s | 2         | 1%      |
| Kingston RAM 99U5428-040.A01LF 4GB SODIMM DDR3 1334MT/s        | 2         | 1%      |
| G.Skill RAM F4-2666C19-8GRS 8192MB SODIMM DDR4 2667MT/s        | 2         | 1%      |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s          | 2         | 1%      |
| Crucial RAM CT4G4SFS824A.C8FF 4GB SODIMM DDR4 2400MT/s         | 2         | 1%      |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s            | 1         | 0.5%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                 | 1         | 0.5%    |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 0.5%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                 | 1         | 0.5%    |
| Unknown RAM Module 2048MB SODIMM DDR3                          | 1         | 0.5%    |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.5%    |
| Unknown (7FE0) RAM Module 8192MB SODIMM DDR4 2400MT/s          | 1         | 0.5%    |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s          | 1         | 0.5%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 83        | 58.04%  |
| DDR3   | 46        | 32.17%  |
| LPDDR4 | 6         | 4.2%    |
| LPDDR3 | 3         | 2.1%    |
| DDR2   | 2         | 1.4%    |
| SDRAM  | 1         | 0.7%    |
| LPDDR5 | 1         | 0.7%    |
| DDR5   | 1         | 0.7%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 131       | 90.97%  |
| Row Of Chips | 13        | 9.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 63        | 40.38%  |
| 8192  | 61        | 39.1%   |
| 16384 | 18        | 11.54%  |
| 2048  | 12        | 7.69%   |
| 32768 | 1         | 0.64%   |
| 1024  | 1         | 0.64%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 43        | 26.88%  |
| 1600    | 34        | 21.25%  |
| 3200    | 33        | 20.63%  |
| 2400    | 14        | 8.75%   |
| 2133    | 7         | 4.38%   |
| 1334    | 6         | 3.75%   |
| 1333    | 6         | 3.75%   |
| 1867    | 4         | 2.5%    |
| 8400    | 3         | 1.88%   |
| 4267    | 2         | 1.25%   |
| 667     | 2         | 1.25%   |
| 6400    | 1         | 0.63%   |
| 4800    | 1         | 0.63%   |
| 4199    | 1         | 0.63%   |
| 3266    | 1         | 0.63%   |
| 2933    | 1         | 0.63%   |
| Unknown | 1         | 0.63%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Canon LBP6030w/6018w | 1         | 100%    |

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
| Chicony Electronics                    | 49        | 23%     |
| Microdia                               | 32        | 15.02%  |
| IMC Networks                           | 30        | 14.08%  |
| Sunplus Innovation Technology          | 23        | 10.8%   |
| Realtek Semiconductor                  | 15        | 7.04%   |
| Acer                                   | 12        | 5.63%   |
| Quanta                                 | 9         | 4.23%   |
| Syntek                                 | 8         | 3.76%   |
| Lite-On Technology                     | 6         | 2.82%   |
| Suyin                                  | 5         | 2.35%   |
| Apple                                  | 5         | 2.35%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 1.88%   |
| Logitech                               | 3         | 1.41%   |
| Silicon Motion                         | 2         | 0.94%   |
| Ricoh                                  | 2         | 0.94%   |
| Luxvisions Innotech Limited            | 2         | 0.94%   |
| Alcor Micro                            | 2         | 0.94%   |
| Sonix Technology                       | 1         | 0.47%   |
| Lenovo                                 | 1         | 0.47%   |
| Denron                                 | 1         | 0.47%   |
| ALi                                    | 1         | 0.47%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                 | 15        | 7.04%   |
| Chicony Integrated Camera                     | 13        | 6.1%    |
| Sunplus Integrated_Webcam_HD                  | 11        | 5.16%   |
| IMC Networks Integrated Camera                | 8         | 3.76%   |
| Chicony HD WebCam                             | 7         | 3.29%   |
| Syntek Integrated Camera                      | 6         | 2.82%   |
| Realtek Integrated_Webcam_HD                  | 6         | 2.82%   |
| Microdia Laptop_Integrated_Webcam_HD          | 6         | 2.82%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 6         | 2.82%   |
| IMC Networks USB2.0 HD UVC WebCam             | 5         | 2.35%   |
| Chicony HP HD Camera                          | 5         | 2.35%   |
| Realtek Integrated Webcam                     | 4         | 1.88%   |
| Chicony HP TrueVision HD Camera               | 4         | 1.88%   |
| Acer ThinkPad Integrated Camera               | 4         | 1.88%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 3         | 1.41%   |
| Quanta VGA WebCam                             | 3         | 1.41%   |
| Microdia Integrated Webcam                    | 3         | 1.41%   |
| IMC Networks VGA UVC WebCam                   | 3         | 1.41%   |
| IMC Networks USB2.0 UVC HD Webcam             | 3         | 1.41%   |
| Chicony Integrated HP HD Webcam               | 3         | 1.41%   |
| Chicony HP HD Webcam                          | 3         | 1.41%   |
| Apple iPhone 5/5C/5S/6/SE                     | 3         | 1.41%   |
| Acer Integrated Camera                        | 3         | 1.41%   |
| Syntek Lenovo EasyCamera                      | 2         | 0.94%   |
| Sunplus Asus Webcam                           | 2         | 0.94%   |
| Quanta HP TrueVision HD Camera                | 2         | 0.94%   |
| Quanta HP HD Camera                           | 2         | 0.94%   |
| Microdia Webcam Vitade AF                     | 2         | 0.94%   |
| Microdia Integrated Webcam HD                 | 2         | 0.94%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 0.94%   |
| Lite-On Integrated Camera                     | 2         | 0.94%   |
| Lite-On HP HD Camera                          | 2         | 0.94%   |
| IMC Networks USB Camera                       | 2         | 0.94%   |
| Chicony TOSHIBA Web Camera - HD               | 2         | 0.94%   |
| Apple FaceTime HD Camera                      | 2         | 0.94%   |
| Acer SunplusIT Integrated Camera              | 2         | 0.94%   |
| Suyin Laptop_Integrated_Webcam_HD             | 1         | 0.47%   |
| Suyin Integrated_Webcam_HD                    | 1         | 0.47%   |
| Suyin HP webcam [dv6-1190en]                  | 1         | 0.47%   |
| Suyin Acer/Lenovo Webcam [CN0316]             | 1         | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 31        | 53.45%  |
| Shenzhen Goodix Technology | 11        | 18.97%  |
| Synaptics                  | 10        | 17.24%  |
| LighTuning Technology      | 2         | 3.45%   |
| Elan Microelectronics      | 2         | 3.45%   |
| Upek                       | 1         | 1.72%   |
| STMicroelectronics         | 1         | 1.72%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 13.79%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 12.07%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 10.34%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 6.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 6.9%    |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 5.17%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 5.17%   |
| Unknown                                                                    | 3         | 5.17%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.45%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 3.45%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 3.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.45%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.45%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.72%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.72%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.72%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.72%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.72%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.72%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 75%     |
| Upek        | 1         | 12.5%   |
| Alcor Micro | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor             | 3         | 37.5%   |
| Broadcom 5880                                              | 2         | 25%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 12.5%   |
| Broadcom 58200                                             | 1         | 12.5%   |
| Alcor Micro AU9540 Smartcard Reader                        | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 151       | 61.38%  |
| 1     | 78        | 31.71%  |
| 2     | 14        | 5.69%   |
| 3     | 2         | 0.81%   |
| 5     | 1         | 0.41%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 57        | 50.44%  |
| Graphics card            | 16        | 14.16%  |
| Net/wireless             | 10        | 8.85%   |
| Chipcard                 | 8         | 7.08%   |
| Net/ethernet             | 4         | 3.54%   |
| Multimedia controller    | 4         | 3.54%   |
| Camera                   | 4         | 3.54%   |
| Communication controller | 3         | 2.65%   |
| Bluetooth                | 3         | 2.65%   |
| Card reader              | 2         | 1.77%   |
| Storage                  | 1         | 0.88%   |
| Sound                    | 1         | 0.88%   |

