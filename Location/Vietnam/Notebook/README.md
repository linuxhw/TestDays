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

Total: 309

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | dynabook Satellite B35/R    | [4600fb0c71](https://linux-hardware.org/?probe=4600fb0c71) | Jul 31, 2022 |
| HP            | EliteBook 8470p             | [2171abfd3d](https://linux-hardware.org/?probe=2171abfd3d) | Jul 30, 2022 |
| Chuwi         | GemiBook Pro                | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| TENKU         | SB14                        | [cbe2900f4f](https://linux-hardware.org/?probe=cbe2900f4f) | Jul 02, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [cacc2464af](https://linux-hardware.org/?probe=cacc2464af) | Jun 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [6eb841aab1](https://linux-hardware.org/?probe=6eb841aab1) | Jun 21, 2022 |
| Acer          | Aspire 5738                 | [58b312c382](https://linux-hardware.org/?probe=58b312c382) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | [2d31db0d12](https://linux-hardware.org/?probe=2d31db0d12) | Jun 07, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | [a8c7fc9c3a](https://linux-hardware.org/?probe=a8c7fc9c3a) | Jun 07, 2022 |
| Chuwi         | GemiBook Pro                | [48738fc474](https://linux-hardware.org/?probe=48738fc474) | Jun 06, 2022 |
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
| ASUSTek       | TUF Gaming FA506II_FA506... | [fa10ea29e8](https://linux-hardware.org/?probe=fa10ea29e8) | Dec 11, 2020 |
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


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 57        | 25%     |
| Ubuntu 18.04                 | 21        | 9.21%   |
| Arch                         | 11        | 4.82%   |
| Pop!_OS 20.04                | 6         | 2.63%   |
| Ubuntu 21.04                 | 5         | 2.19%   |
| Ubuntu 16.04                 | 5         | 2.19%   |
| Debian 10                    | 5         | 2.19%   |
| Ubuntu 22.04                 | 4         | 1.75%   |
| Ubuntu 21.10                 | 4         | 1.75%   |
| Ubuntu 19.10                 | 4         | 1.75%   |
| Pop!_OS 21.04                | 4         | 1.75%   |
| OpenMandriva 4.2             | 4         | 1.75%   |
| KDE neon 20.04               | 4         | 1.75%   |
| Fedora 34                    | 4         | 1.75%   |
| Arch Rolling                 | 4         | 1.75%   |
| OpenMandriva 4.3             | 3         | 1.32%   |
| Manjaro 20.2                 | 3         | 1.32%   |
| Fedora 33                    | 3         | 1.32%   |
| EndeavourOS Rolling          | 3         | 1.32%   |
| ArcoLinux Rolling            | 3         | 1.32%   |
| Zorin 16                     | 2         | 0.88%   |
| Zorin 15                     | 2         | 0.88%   |
| Ubuntu MATE 20.04            | 2         | 0.88%   |
| Ubuntu 19.04                 | 2         | 0.88%   |
| Pop!_OS 21.10                | 2         | 0.88%   |
| Pop!_OS 20.10                | 2         | 0.88%   |
| Manjaro 18.0.4               | 2         | 0.88%   |
| Manjaro                      | 2         | 0.88%   |
| Linux Mint 20.3              | 2         | 0.88%   |
| Linux Mint 20.1              | 2         | 0.88%   |
| Linux Mint 18.3              | 2         | 0.88%   |
| Kubuntu 21.04                | 2         | 0.88%   |
| Endless 3.8.0                | 2         | 0.88%   |
| Elementary 6                 | 2         | 0.88%   |
| Xubuntu 22.04                | 1         | 0.44%   |
| Xubuntu 21.04                | 1         | 0.44%   |
| Void Linux Rolling           | 1         | 0.44%   |
| Ubuntu Core 16               | 1         | 0.44%   |
| Ubuntu 22.10                 | 1         | 0.44%   |
| Ubuntu 20.10                 | 1         | 0.44%   |
| Ubuntu 18.10                 | 1         | 0.44%   |
| Solus 4.3                    | 1         | 0.44%   |
| ROSA R8                      | 1         | 0.44%   |
| Pop!_OS 22.04                | 1         | 0.44%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.44%   |
| openSUSE Leap-15.1           | 1         | 0.44%   |
| MX 20                        | 1         | 0.44%   |
| Manjaro 21.2.6               | 1         | 0.44%   |
| Manjaro 21.0.5               | 1         | 0.44%   |
| Manjaro 20.1.2               | 1         | 0.44%   |
| Manjaro 20.1                 | 1         | 0.44%   |
| Lubuntu 22.04                | 1         | 0.44%   |
| Lubuntu 20.04                | 1         | 0.44%   |
| Linux Mint 20.2              | 1         | 0.44%   |
| Linux Mint 20                | 1         | 0.44%   |
| Linux Mint 19.3              | 1         | 0.44%   |
| Kubuntu 21.10                | 1         | 0.44%   |
| Kubuntu 20.04                | 1         | 0.44%   |
| Kubuntu 2.0                  | 1         | 0.44%   |
| KDE neon 18.04               | 1         | 0.44%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 104       | 46.43%  |
| Pop!_OS      | 15        | 6.7%    |
| Arch         | 15        | 6.7%    |
| Manjaro      | 11        | 4.91%   |
| Fedora       | 10        | 4.46%   |
| Linux Mint   | 9         | 4.02%   |
| OpenMandriva | 7         | 3.13%   |
| Endless      | 7         | 3.13%   |
| Debian       | 6         | 2.68%   |
| Zorin        | 4         | 1.79%   |
| Kubuntu      | 4         | 1.79%   |
| KDE neon     | 4         | 1.79%   |
| EndeavourOS  | 3         | 1.34%   |
| ArcoLinux    | 3         | 1.34%   |
| Xubuntu      | 2         | 0.89%   |
| Ubuntu MATE  | 2         | 0.89%   |
| openSUSE     | 2         | 0.89%   |
| Lubuntu      | 2         | 0.89%   |
| Kali         | 2         | 0.89%   |
| Gentoo       | 2         | 0.89%   |
| Elementary   | 2         | 0.89%   |
| Clear Linux  | 2         | 0.89%   |
| Void Linux   | 1         | 0.45%   |
| Solus        | 1         | 0.45%   |
| ROSA         | 1         | 0.45%   |
| MX           | 1         | 0.45%   |
| Devuan       | 1         | 0.45%   |
| CentOS       | 1         | 0.45%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 7         | 2.83%   |
| 5.4.0-52-generic         | 5         | 2.02%   |
| 5.4.0-48-generic         | 5         | 2.02%   |
| 5.4.0-40-generic         | 5         | 2.02%   |
| 5.4.0-37-generic         | 5         | 2.02%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.62%   |
| 5.8.0-55-generic         | 3         | 1.21%   |
| 5.8.0-53-generic         | 3         | 1.21%   |
| 5.8.0-48-generic         | 3         | 1.21%   |
| 5.11.0-41-generic        | 3         | 1.21%   |
| 5.11.0-37-generic        | 3         | 1.21%   |
| 4.10.0-28-generic        | 3         | 1.21%   |
| 5.9.14-200.fc33.x86_64   | 2         | 0.81%   |
| 5.8.0-7642-generic       | 2         | 0.81%   |
| 5.8.0-50-generic         | 2         | 0.81%   |
| 5.8.0-44-generic         | 2         | 0.81%   |
| 5.8.0-43-generic         | 2         | 0.81%   |
| 5.8.0-25-generic         | 2         | 0.81%   |
| 5.4.0-7642-generic       | 2         | 0.81%   |
| 5.4.0-74-generic         | 2         | 0.81%   |
| 5.4.0-72-generic         | 2         | 0.81%   |
| 5.4.0-70-generic         | 2         | 0.81%   |
| 5.4.0-58-generic         | 2         | 0.81%   |
| 5.4.0-47-generic         | 2         | 0.81%   |
| 5.4.0-45-generic         | 2         | 0.81%   |
| 5.4.0-39-generic         | 2         | 0.81%   |
| 5.4.0-29-generic         | 2         | 0.81%   |
| 5.4.0-19-generic         | 2         | 0.81%   |
| 5.3.0-46-generic         | 2         | 0.81%   |
| 5.3.0-28-generic         | 2         | 0.81%   |
| 5.3.0-18-generic         | 2         | 0.81%   |
| 5.16.7-desktop-1omv4003  | 2         | 0.81%   |
| 5.15.0-35-generic        | 2         | 0.81%   |
| 5.15.0-33-generic        | 2         | 0.81%   |
| 5.13.16-200.fc34.x86_64  | 2         | 0.81%   |
| 5.13.0-7614-generic      | 2         | 0.81%   |
| 5.13.0-28-generic        | 2         | 0.81%   |
| 5.13.0-20-generic        | 2         | 0.81%   |
| 5.11.0-7620-generic      | 2         | 0.81%   |
| 5.11.0-38-generic        | 2         | 0.81%   |
| 5.11.0-27-generic        | 2         | 0.81%   |
| 5.11.0-17-generic        | 2         | 0.81%   |
| 5.0.0-37-generic         | 2         | 0.81%   |
| 4.19.0-8-amd64           | 2         | 0.81%   |
| 4.15.0-96-generic        | 2         | 0.81%   |
| 5.9.3-1-MANJARO          | 1         | 0.4%    |
| 5.9.13-1-MANJARO         | 1         | 0.4%    |
| 5.9.1-1-MANJARO          | 1         | 0.4%    |
| 5.9.0-kali5-amd64        | 1         | 0.4%    |
| 5.8.16-antix.1-amd64-smp | 1         | 0.4%    |
| 5.8.14-amd64-desktop     | 1         | 0.4%    |
| 5.8.12_2                 | 1         | 0.4%    |
| 5.8.0-7625-generic       | 1         | 0.4%    |
| 5.8.0-63-generic         | 1         | 0.4%    |
| 5.8.0-59-generic         | 1         | 0.4%    |
| 5.8.0-45-generic         | 1         | 0.4%    |
| 5.8.0-41-generic         | 1         | 0.4%    |
| 5.8.0-40-generic         | 1         | 0.4%    |
| 5.7.16-200.fc32.x86_64   | 1         | 0.4%    |
| 5.7.13-975.native        | 1         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 51        | 22.17%  |
| 5.8.0   | 23        | 10%     |
| 5.11.0  | 21        | 9.13%   |
| 5.3.0   | 11        | 4.78%   |
| 5.13.0  | 8         | 3.48%   |
| 4.15.0  | 8         | 3.48%   |
| 5.15.0  | 7         | 3.04%   |
| 5.0.0   | 7         | 3.04%   |
| 4.18.0  | 6         | 2.61%   |
| 5.10.0  | 5         | 2.17%   |
| 4.19.0  | 5         | 2.17%   |
| 5.10.14 | 4         | 1.74%   |
| 4.10.0  | 4         | 1.74%   |
| 5.16.7  | 3         | 1.3%    |
| 5.9.14  | 2         | 0.87%   |
| 5.13.16 | 2         | 0.87%   |
| 4.13.0  | 2         | 0.87%   |
| 5.9.3   | 1         | 0.43%   |
| 5.9.13  | 1         | 0.43%   |
| 5.9.1   | 1         | 0.43%   |
| 5.9.0   | 1         | 0.43%   |
| 5.8.16  | 1         | 0.43%   |
| 5.8.14  | 1         | 0.43%   |
| 5.8.12  | 1         | 0.43%   |
| 5.7.16  | 1         | 0.43%   |
| 5.7.13  | 1         | 0.43%   |
| 5.7.12  | 1         | 0.43%   |
| 5.5.2   | 1         | 0.43%   |
| 5.5.10  | 1         | 0.43%   |
| 5.4.98  | 1         | 0.43%   |
| 5.4.97  | 1         | 0.43%   |
| 5.4.80  | 1         | 0.43%   |
| 5.4.60  | 1         | 0.43%   |
| 5.4.17  | 1         | 0.43%   |
| 5.4.13  | 1         | 0.43%   |
| 5.4.118 | 1         | 0.43%   |
| 5.18.6  | 1         | 0.43%   |
| 5.17.9  | 1         | 0.43%   |
| 5.17.5  | 1         | 0.43%   |
| 5.17.4  | 1         | 0.43%   |
| 5.16.9  | 1         | 0.43%   |
| 5.16.8  | 1         | 0.43%   |
| 5.16.13 | 1         | 0.43%   |
| 5.16.0  | 1         | 0.43%   |
| 5.15.8  | 1         | 0.43%   |
| 5.15.55 | 1         | 0.43%   |
| 5.15.5  | 1         | 0.43%   |
| 5.15.49 | 1         | 0.43%   |
| 5.15.32 | 1         | 0.43%   |
| 5.15.11 | 1         | 0.43%   |
| 5.15.10 | 1         | 0.43%   |
| 5.14.8  | 1         | 0.43%   |
| 5.14.2  | 1         | 0.43%   |
| 5.14.15 | 1         | 0.43%   |
| 5.14.14 | 1         | 0.43%   |
| 5.14.11 | 1         | 0.43%   |
| 5.13.9  | 1         | 0.43%   |
| 5.13.6  | 1         | 0.43%   |
| 5.13.4  | 1         | 0.43%   |
| 5.13.13 | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 58        | 25.44%  |
| 5.8     | 26        | 11.4%   |
| 5.11    | 22        | 9.65%   |
| 5.15    | 14        | 6.14%   |
| 5.13    | 14        | 6.14%   |
| 5.10    | 14        | 6.14%   |
| 5.3     | 11        | 4.82%   |
| 5.0     | 10        | 4.39%   |
| 4.15    | 8         | 3.51%   |
| 5.16    | 7         | 3.07%   |
| 5.9     | 6         | 2.63%   |
| 4.19    | 6         | 2.63%   |
| 4.18    | 6         | 2.63%   |
| 5.14    | 4         | 1.75%   |
| 5.12    | 4         | 1.75%   |
| 4.10    | 4         | 1.75%   |
| 5.7     | 3         | 1.32%   |
| 5.17    | 3         | 1.32%   |
| 5.5     | 2         | 0.88%   |
| 4.13    | 2         | 0.88%   |
| 5.18    | 1         | 0.44%   |
| 4.4     | 1         | 0.44%   |
| 4.12    | 1         | 0.44%   |
| 4.1     | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 220       | 99.55%  |
| i686   | 1         | 0.45%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 119       | 52.89%  |
| Unknown    | 33        | 14.67%  |
| KDE5       | 26        | 11.56%  |
| XFCE       | 15        | 6.67%   |
| KDE        | 8         | 3.56%   |
| X-Cinnamon | 4         | 1.78%   |
| Unity      | 4         | 1.78%   |
| Cinnamon   | 3         | 1.33%   |
| Pantheon   | 2         | 0.89%   |
| MATE       | 2         | 0.89%   |
| LXQt       | 2         | 0.89%   |
| bspwm      | 2         | 0.89%   |
| Openbox    | 1         | 0.44%   |
| KDE4       | 1         | 0.44%   |
| Deepin     | 1         | 0.44%   |
| Budgie     | 1         | 0.44%   |
| awesome    | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 182       | 80.89%  |
| Wayland | 23        | 10.22%  |
| Unknown | 18        | 8%      |
| Tty     | 2         | 0.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 122       | 54.22%  |
| GDM     | 40        | 17.78%  |
| SDDM    | 26        | 11.56%  |
| LightDM | 14        | 6.22%   |
| TDM     | 11        | 4.89%   |
| GDM3    | 9         | 4%      |
| XDM     | 1         | 0.44%   |
| SLiM    | 1         | 0.44%   |
| KDM     | 1         | 0.44%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 163       | 73.76%  |
| Unknown | 34        | 15.38%  |
| vi_VN   | 12        | 5.43%   |
| C       | 5         | 2.26%   |
| en_AU   | 3         | 1.36%   |
| en_GB   | 2         | 0.9%    |
| ru_RU   | 1         | 0.45%   |
| fr_FR   | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 146       | 64.6%   |
| BIOS | 80        | 35.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 185       | 83.33%  |
| Btrfs   | 12        | 5.41%   |
| Unknown | 12        | 5.41%   |
| Overlay | 9         | 4.05%   |
| Zfs     | 2         | 0.9%    |
| Xfs     | 1         | 0.45%   |
| Ext3    | 1         | 0.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 120       | 54.05%  |
| GPT     | 87        | 39.19%  |
| MBR     | 15        | 6.76%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 204       | 91.48%  |
| Yes       | 19        | 8.52%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 128       | 57.14%  |
| Yes       | 96        | 42.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 59        | 26.7%   |
| Lenovo              | 44        | 19.91%  |
| Hewlett-Packard     | 37        | 16.74%  |
| ASUSTek Computer    | 28        | 12.67%  |
| Acer                | 17        | 7.69%   |
| MSI                 | 8         | 3.62%   |
| Toshiba             | 5         | 2.26%   |
| Sony                | 4         | 1.81%   |
| Apple               | 4         | 1.81%   |
| Chuwi               | 3         | 1.36%   |
| Samsung Electronics | 2         | 0.9%    |
| Timi                | 1         | 0.45%   |
| TENKU               | 1         | 0.45%   |
| Panasonic           | 1         | 0.45%   |
| MASSCOM VIETNAM     | 1         | 0.45%   |
| LG Electronics      | 1         | 0.45%   |
| Koompi              | 1         | 0.45%   |
| Jumper              | 1         | 0.45%   |
| Gigabyte Technology | 1         | 0.45%   |
| Gateway             | 1         | 0.45%   |
| AMI                 | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Dell Inspiron 3537                       | 4         | 1.81%   |
| Unknown                                  | 4         | 1.81%   |
| Lenovo Legion 5 15ARH05 82B5             | 3         | 1.36%   |
| ASUS X411UA                              | 3         | 1.36%   |
| Toshiba Satellite L840                   | 2         | 0.9%    |
| MSI GF63 8RD                             | 2         | 0.9%    |
| Lenovo ThinkPad W530 2447EJ9             | 2         | 0.9%    |
| Lenovo ThinkPad E14 20RAS0KX00           | 2         | 0.9%    |
| HP Notebook                              | 2         | 0.9%    |
| HP Laptop 14-bs0xx                       | 2         | 0.9%    |
| HP EliteBook 8470p                       | 2         | 0.9%    |
| HP EliteBook 840 G2                      | 2         | 0.9%    |
| Dell XPS 15 9570                         | 2         | 0.9%    |
| Dell Vostro 3590                         | 2         | 0.9%    |
| Dell Vostro 3578                         | 2         | 0.9%    |
| Dell Vostro 3478                         | 2         | 0.9%    |
| Dell Vostro 3460                         | 2         | 0.9%    |
| Dell Vostro 15-3568                      | 2         | 0.9%    |
| Dell System Vostro 3450                  | 2         | 0.9%    |
| Dell Latitude E7440                      | 2         | 0.9%    |
| Dell Inspiron 5570                       | 2         | 0.9%    |
| Dell G3 3579                             | 2         | 0.9%    |
| Chuwi GemiBook Pro                       | 2         | 0.9%    |
| Acer Swift SF315-52                      | 2         | 0.9%    |
| Acer Predator PH315-51                   | 2         | 0.9%    |
| Acer Aspire A315-42                      | 2         | 0.9%    |
| Toshiba Satellite E45-B                  | 1         | 0.45%   |
| Toshiba PORTEGE T110                     | 1         | 0.45%   |
| Toshiba dynabook Satellite B35/R         | 1         | 0.45%   |
| Timi A35S                                | 1         | 0.45%   |
| TENKU SB14                               | 1         | 0.45%   |
| Sony VPCEB42EG                           | 1         | 0.45%   |
| Sony VPCCW13FX                           | 1         | 0.45%   |
| Sony VGN-NW270F                          | 1         | 0.45%   |
| Sony SVE14A15FGW                         | 1         | 0.45%   |
| Samsung NC208/NC108                      | 1         | 0.45%   |
| Samsung 300E4Z/300E5Z/300E7Z             | 1         | 0.45%   |
| Panasonic CFSX4-1                        | 1         | 0.45%   |
| MSI Prestige 15 A11SCX                   | 1         | 0.45%   |
| MSI GS40 6QE Phantom                     | 1         | 0.45%   |
| MSI GP62 6QE                             | 1         | 0.45%   |
| MSI GF62 7RD                             | 1         | 0.45%   |
| MSI GE66 Raider 11UH                     | 1         | 0.45%   |
| MSI Bravo 15 B5DD                        | 1         | 0.45%   |
| MASSCOM VIETNAM L133                     | 1         | 0.45%   |
| LG 17U70N-R.AAS7U1                       | 1         | 0.45%   |
| Lenovo Z40-70 20366                      | 1         | 0.45%   |
| Lenovo Y520-15IKBN 80WK                  | 1         | 0.45%   |
| Lenovo V130-14IKB 81HQ                   | 1         | 0.45%   |
| Lenovo ThinkPad X250 20CLCTO1WW          | 1         | 0.45%   |
| Lenovo ThinkPad X240 20AMA01LVA          | 1         | 0.45%   |
| Lenovo ThinkPad X230 2325YN1             | 1         | 0.45%   |
| Lenovo ThinkPad X230 2325VEN             | 1         | 0.45%   |
| Lenovo ThinkPad X230 2325BK0             | 1         | 0.45%   |
| Lenovo ThinkPad X1C 5th W10DG 20K4002RUS | 1         | 0.45%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS3HX00 | 1         | 0.45%   |
| Lenovo ThinkPad T61 7661C54              | 1         | 0.45%   |
| Lenovo ThinkPad T580 20L9S14S00          | 1         | 0.45%   |
| Lenovo ThinkPad T580 20L9001MUS          | 1         | 0.45%   |
| Lenovo ThinkPad T480 20L5001DUS          | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 24        | 10.86%  |
| Dell Inspiron        | 17        | 7.69%   |
| Dell Vostro          | 15        | 6.79%   |
| HP EliteBook         | 11        | 4.98%   |
| Acer Aspire          | 11        | 4.98%   |
| Dell Latitude        | 10        | 4.52%   |
| Lenovo IdeaPad       | 7         | 3.17%   |
| HP ProBook           | 7         | 3.17%   |
| ASUS VivoBook        | 6         | 2.71%   |
| Lenovo Legion        | 5         | 2.26%   |
| HP Laptop            | 5         | 2.26%   |
| Dell XPS             | 5         | 2.26%   |
| Dell Precision       | 5         | 2.26%   |
| Dell System          | 4         | 1.81%   |
| Unknown              | 4         | 1.81%   |
| Toshiba Satellite    | 3         | 1.36%   |
| Lenovo ThinkBook     | 3         | 1.36%   |
| HP ZBook             | 3         | 1.36%   |
| HP Pavilion          | 3         | 1.36%   |
| Dell G3              | 3         | 1.36%   |
| ASUS X411UA          | 3         | 1.36%   |
| ASUS ROG             | 3         | 1.36%   |
| ASUS ASUS            | 3         | 1.36%   |
| Acer Swift           | 3         | 1.36%   |
| Acer Predator        | 3         | 1.36%   |
| MSI GF63             | 2         | 0.9%    |
| HP Notebook          | 2         | 0.9%    |
| HP Compaq            | 2         | 0.9%    |
| Chuwi GemiBook       | 2         | 0.9%    |
| Toshiba PORTEGE      | 1         | 0.45%   |
| Toshiba dynabook     | 1         | 0.45%   |
| Timi A35S            | 1         | 0.45%   |
| TENKU SB14           | 1         | 0.45%   |
| Sony VPCEB42EG       | 1         | 0.45%   |
| Sony VPCCW13FX       | 1         | 0.45%   |
| Sony VGN-NW270F      | 1         | 0.45%   |
| Sony SVE14A15FGW     | 1         | 0.45%   |
| Samsung NC208        | 1         | 0.45%   |
| Samsung 300E4Z       | 1         | 0.45%   |
| Panasonic CFSX4-1    | 1         | 0.45%   |
| MSI Prestige         | 1         | 0.45%   |
| MSI GS40             | 1         | 0.45%   |
| MSI GP62             | 1         | 0.45%   |
| MSI GF62             | 1         | 0.45%   |
| MSI GE66             | 1         | 0.45%   |
| MSI Bravo            | 1         | 0.45%   |
| MASSCOM VIETNAM L133 | 1         | 0.45%   |
| LG 17U70N-R.AAS7U1   | 1         | 0.45%   |
| Lenovo Z40-70        | 1         | 0.45%   |
| Lenovo Y520-15IKBN   | 1         | 0.45%   |
| Lenovo V130-14IKB    | 1         | 0.45%   |
| Lenovo IdeaPadFlex   | 1         | 0.45%   |
| Jumper EZpad         | 1         | 0.45%   |
| HP ENVY              | 1         | 0.45%   |
| HP 15                | 1         | 0.45%   |
| Gigabyte AERO        | 1         | 0.45%   |
| Gateway LT40         | 1         | 0.45%   |
| Chuwi LapBook        | 1         | 0.45%   |
| ASUS X550LD          | 1         | 0.45%   |
| ASUS X550CC          | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 33        | 14.93%  |
| 2020 | 26        | 11.76%  |
| 2012 | 25        | 11.31%  |
| 2019 | 22        | 9.95%   |
| 2015 | 18        | 8.14%   |
| 2017 | 17        | 7.69%   |
| 2011 | 16        | 7.24%   |
| 2016 | 15        | 6.79%   |
| 2013 | 15        | 6.79%   |
| 2021 | 12        | 5.43%   |
| 2014 | 8         | 3.62%   |
| 2009 | 7         | 3.17%   |
| 2010 | 5         | 2.26%   |
| 2007 | 2         | 0.9%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 221       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 202       | 90.18%  |
| Enabled  | 22        | 9.82%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 221       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 79        | 35.59%  |
| 16.01-24.0 | 44        | 19.82%  |
| 3.01-4.0   | 41        | 18.47%  |
| 8.01-16.0  | 40        | 18.02%  |
| 32.01-64.0 | 9         | 4.05%   |
| 1.01-2.0   | 6         | 2.7%    |
| 24.01-32.0 | 1         | 0.45%   |
| 2.01-3.0   | 1         | 0.45%   |
| 0.51-1.0   | 1         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 83        | 35.17%  |
| 1.01-2.0   | 63        | 26.69%  |
| 4.01-8.0   | 38        | 16.1%   |
| 3.01-4.0   | 38        | 16.1%   |
| 8.01-16.0  | 8         | 3.39%   |
| 0.51-1.0   | 5         | 2.12%   |
| 16.01-24.0 | 1         | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 152       | 68.16%  |
| 2      | 61        | 27.35%  |
| 3      | 8         | 3.59%   |
| 4      | 1         | 0.45%   |
| 0      | 1         | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 167       | 75.57%  |
| Yes       | 54        | 24.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 183       | 82.06%  |
| No        | 40        | 17.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 220       | 99.55%  |
| No        | 1         | 0.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 194       | 87.78%  |
| No        | 27        | 12.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Vietnam | 221       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Ho Chi Minh City | 96        | 41.92%  |
| Hanoi            | 78        | 34.06%  |
| Can Tho          | 6         | 2.62%   |
| Da Nang          | 5         | 2.18%   |
| Huế            | 3         | 1.31%   |
| Bien Hoa         | 3         | 1.31%   |
| Vũng Tàu       | 2         | 0.87%   |
| Vinh Phuc        | 2         | 0.87%   |
| Thuan An         | 2         | 0.87%   |
| Tay Ninh         | 2         | 0.87%   |
| Nam Định      | 2         | 0.87%   |
| Buon Ma Thuot    | 2         | 0.87%   |
| Binh Hoa         | 2         | 0.87%   |
| Bao Loc          | 2         | 0.87%   |
| Vinh             | 1         | 0.44%   |
| Tra Vinh         | 1         | 0.44%   |
| Tinh Quang Binh  | 1         | 0.44%   |
| Tinh GJong Nai   | 1         | 0.44%   |
| Thu Duc          | 1         | 0.44%   |
| Thanh Hóa       | 1         | 0.44%   |
| Thai Nguyen      | 1         | 0.44%   |
| Tan An           | 1         | 0.44%   |
| Quang Trung      | 1         | 0.44%   |
| Quảng Ngai     | 1         | 0.44%   |
| Quan Muoi Mot    | 1         | 0.44%   |
| Quan Muoi        | 1         | 0.44%   |
| Quan Binh Thanh  | 1         | 0.44%   |
| Nha Trang        | 1         | 0.44%   |
| Nga Bay          | 1         | 0.44%   |
| Lien Chieu       | 1         | 0.44%   |
| Haiphong         | 1         | 0.44%   |
| Go Vap           | 1         | 0.44%   |
| Do Son           | 1         | 0.44%   |
| Dien Ban         | 1         | 0.44%   |
| Bến Tre        | 1         | 0.44%   |
| Bac Giang        | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 39        | 48     | 13.36%  |
| WDC                 | 35        | 41     | 11.99%  |
| Toshiba             | 29        | 34     | 9.93%   |
| Seagate             | 27        | 31     | 9.25%   |
| HGST                | 20        | 20     | 6.85%   |
| SK hynix            | 17        | 18     | 5.82%   |
| Intel               | 16        | 17     | 5.48%   |
| Unknown             | 13        | 13     | 4.45%   |
| Kingston            | 11        | 12     | 3.77%   |
| Hitachi             | 9         | 13     | 3.08%   |
| Micron Technology   | 8         | 10     | 2.74%   |
| Crucial             | 8         | 8      | 2.74%   |
| Plextor             | 6         | 6      | 2.05%   |
| OSCOO               | 5         | 6      | 1.71%   |
| TO Exter            | 4         | 5      | 1.37%   |
| SanDisk             | 4         | 5      | 1.37%   |
| Colorful            | 3         | 3      | 1.03%   |
| LITEON              | 2         | 2      | 0.68%   |
| Lexar               | 2         | 2      | 0.68%   |
| KingSpec            | 2         | 2      | 0.68%   |
| KingDian            | 2         | 3      | 0.68%   |
| FORESEE             | 2         | 2      | 0.68%   |
| Apple               | 2         | 2      | 0.68%   |
| W800S               | 1         | 1      | 0.34%   |
| UMIS                | 1         | 1      | 0.34%   |
| Transcend           | 1         | 1      | 0.34%   |
| SPCC                | 1         | 1      | 0.34%   |
| Silicon Motion      | 1         | 2      | 0.34%   |
| Phison              | 1         | 1      | 0.34%   |
| OSC                 | 1         | 1      | 0.34%   |
| NGFF                | 1         | 1      | 0.34%   |
| Netac               | 1         | 1      | 0.34%   |
| Maxtor              | 1         | 1      | 0.34%   |
| LITEONIT            | 1         | 1      | 0.34%   |
| Lite-On             | 1         | 3      | 0.34%   |
| Lenovo              | 1         | 1      | 0.34%   |
| KLEVV               | 1         | 1      | 0.34%   |
| KIOXIA-EXCERIA      | 1         | 2      | 0.34%   |
| KIOXIA              | 1         | 1      | 0.34%   |
| Kingmax             | 1         | 1      | 0.34%   |
| KingFast            | 1         | 1      | 0.34%   |
| Indilinx            | 1         | 1      | 0.34%   |
| HXY                 | 1         | 1      | 0.34%   |
| Hikvision           | 1         | 1      | 0.34%   |
| Hewlett-Packard     | 1         | 1      | 0.34%   |
| Gigabyte Technology | 1         | 1      | 0.34%   |
| China               | 1         | 1      | 0.34%   |
| Apacer              | 1         | 1      | 0.34%   |
| AGI                 | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB             | 7         | 2.36%   |
| Seagate ST1000LM035-1RK172 1TB       | 6         | 2.02%   |
| Toshiba MQ04ABF100 1TB               | 5         | 1.68%   |
| Samsung NVMe SSD Drive 512GB         | 5         | 1.68%   |
| Toshiba MQ01ABF050 500GB             | 4         | 1.35%   |
| TO Exter nal USB 3.0 1TB             | 4         | 1.35%   |
| SK hynix NVMe SSD Drive 256GB        | 4         | 1.35%   |
| Seagate ST1000LM049-2GH172 1TB       | 4         | 1.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 3         | 1.01%   |
| Toshiba MQ01ABD100 1TB               | 3         | 1.01%   |
| SK hynix NVMe SSD Drive 512GB        | 3         | 1.01%   |
| Seagate ST9500325AS 500GB            | 3         | 1.01%   |
| Seagate ST500LT012-9WS142 500GB      | 3         | 1.01%   |
| Samsung MZALQ512HALU-000L2 512GB     | 3         | 1.01%   |
| Kingston SA400S37120G 120GB SSD      | 3         | 1.01%   |
| Kingston NVMe SSD Drive 256GB        | 3         | 1.01%   |
| Hitachi HTS545050A7E380 500GB        | 3         | 1.01%   |
| HGST HTS545050A7E680 500GB           | 3         | 1.01%   |
| Crucial CT240BX500SSD1 240GB         | 3         | 1.01%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 2         | 0.67%   |
| WDC WD5000LPLX-08ZNTT0 500GB         | 2         | 0.67%   |
| WDC WD5000LPCX-21VHAT0 500GB         | 2         | 0.67%   |
| WDC WD10SPZX-21Z10T0 1TB             | 2         | 0.67%   |
| WDC WD10JPVX-75JC3T0 1TB             | 2         | 0.67%   |
| WDC PC SN720 SDAPNTW-256G-1006 256GB | 2         | 0.67%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB | 2         | 0.67%   |
| Unknown NVMe SSD Drive 256GB         | 2         | 0.67%   |
| Unknown MMC Card  32GB               | 2         | 0.67%   |
| Toshiba NVMe SSD Drive 256GB         | 2         | 0.67%   |
| Toshiba MK2035GSS 200GB              | 2         | 0.67%   |
| SanDisk NVMe SSD Drive 500GB         | 2         | 0.67%   |
| Samsung SSD 860 EVO 500GB            | 2         | 0.67%   |
| Samsung SSD 860 EVO 250GB            | 2         | 0.67%   |
| Samsung NVMe SSD Drive 256GB         | 2         | 0.67%   |
| Samsung MZVLQ512HBLU-00B00 512GB     | 2         | 0.67%   |
| Plextor PX-256M8VC 256GB SSD         | 2         | 0.67%   |
| OSCOO OSC SSD 128GB                  | 2         | 0.67%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 0.67%   |
| Lexar 128GB SSD                      | 2         | 0.67%   |
| Kingston NVMe SSD Drive 512GB        | 2         | 0.67%   |
| Intel SSDSC2BW120H6 120GB            | 2         | 0.67%   |
| Hitachi HTS543232A7A384 320GB        | 2         | 0.67%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.67%   |
| HGST HTS541010B7E610 1TB             | 2         | 0.67%   |
| WDC WDS500G2B0A 500GB SSD            | 1         | 0.34%   |
| WDC WDS250G2B0A-00SM50 250GB SSD     | 1         | 0.34%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.34%   |
| WDC WD5000LPLX-60ZNTT1 500GB         | 1         | 0.34%   |
| WDC WD5000LPLX-0 500GB               | 1         | 0.34%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.34%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 1         | 0.34%   |
| WDC WD5000LPCX-22VHAT1 500GB         | 1         | 0.34%   |
| WDC WD5000BPVT-75A1YT0 500GB         | 1         | 0.34%   |
| WDC WD5000BPKT-75PK4T0 500GB         | 1         | 0.34%   |
| WDC WD3200BEKX-75B7WT0 320GB         | 1         | 0.34%   |
| WDC WD3200BEKT-60PVMT0 320GB         | 1         | 0.34%   |
| WDC WD32 00BEVT-24A23 320GB          | 1         | 0.34%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 1         | 0.34%   |
| WDC WD10SPZX-75Z10T1 1TB             | 1         | 0.34%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 27        | 31     | 27.27%  |
| WDC     | 22        | 28     | 22.22%  |
| Toshiba | 21        | 21     | 21.21%  |
| HGST    | 20        | 20     | 20.2%   |
| Hitachi | 9         | 13     | 9.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 15     | 14.14%  |
| Intel               | 8         | 9      | 8.08%   |
| Crucial             | 8         | 8      | 8.08%   |
| WDC                 | 7         | 7      | 7.07%   |
| Plextor             | 6         | 6      | 6.06%   |
| Kingston            | 5         | 6      | 5.05%   |
| TO Exter            | 4         | 5      | 4.04%   |
| SK hynix            | 4         | 4      | 4.04%   |
| OSCOO               | 3         | 3      | 3.03%   |
| Micron Technology   | 3         | 3      | 3.03%   |
| Toshiba             | 2         | 3      | 2.02%   |
| LITEON              | 2         | 2      | 2.02%   |
| Lexar               | 2         | 2      | 2.02%   |
| KingSpec            | 2         | 2      | 2.02%   |
| KingDian            | 2         | 3      | 2.02%   |
| FORESEE             | 2         | 2      | 2.02%   |
| Colorful            | 2         | 2      | 2.02%   |
| Apple               | 2         | 2      | 2.02%   |
| W800S               | 1         | 1      | 1.01%   |
| Unknown             | 1         | 1      | 1.01%   |
| Transcend           | 1         | 1      | 1.01%   |
| SPCC                | 1         | 1      | 1.01%   |
| SanDisk             | 1         | 2      | 1.01%   |
| OSC                 | 1         | 1      | 1.01%   |
| NGFF                | 1         | 1      | 1.01%   |
| Netac               | 1         | 1      | 1.01%   |
| Maxtor              | 1         | 1      | 1.01%   |
| LITEONIT            | 1         | 1      | 1.01%   |
| KLEVV               | 1         | 1      | 1.01%   |
| KIOXIA-EXCERIA      | 1         | 2      | 1.01%   |
| Kingmax             | 1         | 1      | 1.01%   |
| Indilinx            | 1         | 1      | 1.01%   |
| HXY                 | 1         | 1      | 1.01%   |
| Hikvision           | 1         | 1      | 1.01%   |
| Hewlett-Packard     | 1         | 1      | 1.01%   |
| Gigabyte Technology | 1         | 1      | 1.01%   |
| China               | 1         | 1      | 1.01%   |
| Apacer              | 1         | 1      | 1.01%   |
| AGI                 | 1         | 1      | 1.01%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 96        | 113    | 34.04%  |
| SSD     | 91        | 107    | 32.27%  |
| NVMe    | 82        | 100    | 29.08%  |
| MMC     | 9         | 9      | 3.19%   |
| Unknown | 4         | 4      | 1.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 158       | 217    | 61.96%  |
| NVMe | 82        | 100    | 32.16%  |
| MMC  | 9         | 9      | 3.53%   |
| SAS  | 6         | 7      | 2.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 130       | 164    | 72.63%  |
| 0.51-1.0   | 48        | 55     | 26.82%  |
| 1.01-2.0   | 1         | 1      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 86        | 37.89%  |
| 251-500        | 51        | 22.47%  |
| 51-100         | 23        | 10.13%  |
| 501-1000       | 17        | 7.49%   |
| 1001-2000      | 14        | 6.17%   |
| 1-20           | 11        | 4.85%   |
| 21-50          | 10        | 4.41%   |
| Unknown        | 10        | 4.41%   |
| 2001-3000      | 4         | 1.76%   |
| More than 3000 | 1         | 0.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 103       | 44.78%  |
| 21-50          | 43        | 18.7%   |
| 51-100         | 32        | 13.91%  |
| 101-250        | 16        | 6.96%   |
| 251-500        | 14        | 6.09%   |
| 501-1000       | 10        | 4.35%   |
| Unknown        | 10        | 4.35%   |
| More than 3000 | 1         | 0.43%   |
| 1001-2000      | 1         | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB               | 2         | 2      | 8.7%    |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 4.35%   |
| WDC WD5000LPLX-60ZNTT1 500GB                 | 1         | 1      | 4.35%   |
| WDC WD32 00BEVT-24A23 320GB                  | 1         | 1      | 4.35%   |
| WDC WD10JPVX-75JC3T0 1TB                     | 1         | 1      | 4.35%   |
| Unknown Bamba-240GB SSD                      | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD050 500GB                     | 1         | 1      | 4.35%   |
| Toshiba MK8046GSX 80GB                       | 1         | 1      | 4.35%   |
| Toshiba MK3265GSXN 320GB                     | 1         | 1      | 4.35%   |
| Toshiba HDWK105 500GB                        | 1         | 1      | 4.35%   |
| SK hynix HFS032G34MNC-2200A 32GB SSD         | 1         | 1      | 4.35%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 4.35%   |
| Samsung Electronics MZVPW128HEGM-00000 128GB | 1         | 1      | 4.35%   |
| Hitachi HTS725050A7E635 500GB                | 1         | 1      | 4.35%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 4.35%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 1      | 4.35%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 4.35%   |
| HGST HTS725032A7E630 320GB                   | 1         | 1      | 4.35%   |
| HGST HTS545050A7E680 500GB                   | 1         | 1      | 4.35%   |
| HGST HTS545050A7 500GB                       | 1         | 1      | 4.35%   |
| HGST HTS541010A7E630 1TB                     | 1         | 1      | 4.35%   |
| Crucial CT525MX300SSD1 528GB                 | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| HGST                | 5         | 5      | 21.74%  |
| WDC                 | 4         | 4      | 17.39%  |
| Toshiba             | 4         | 4      | 17.39%  |
| Seagate             | 3         | 3      | 13.04%  |
| Hitachi             | 3         | 3      | 13.04%  |
| Unknown             | 1         | 1      | 4.35%   |
| SK hynix            | 1         | 1      | 4.35%   |
| Samsung Electronics | 1         | 1      | 4.35%   |
| Crucial             | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HGST    | 5         | 5      | 26.32%  |
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
| HDD  | 19        | 19     | 82.61%  |
| SSD  | 3         | 3      | 13.04%  |
| NVMe | 1         | 1      | 4.35%   |

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
| Detected | 128       | 186    | 52.67%  |
| Works    | 93        | 124    | 38.27%  |
| Malfunc  | 22        | 23     | 9.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 185       | 66.79%  |
| Samsung Electronics            | 30        | 10.83%  |
| AMD                            | 14        | 5.05%   |
| SK hynix                       | 13        | 4.69%   |
| SanDisk                        | 8         | 2.89%   |
| Toshiba America Info Systems   | 6         | 2.17%   |
| Kingston Technology Company    | 6         | 2.17%   |
| Micron Technology              | 5         | 1.81%   |
| Solid State Storage Technology | 2         | 0.72%   |
| Silicon Motion                 | 2         | 0.72%   |
| KIOXIA                         | 2         | 0.72%   |
| Union Memory (Shenzhen)        | 1         | 0.36%   |
| Phison Electronics             | 1         | 0.36%   |
| Lite-On Technology             | 1         | 0.36%   |
| Lenovo                         | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 29        | 10.14%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 28        | 9.79%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 4.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 4.55%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 12        | 4.2%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 11        | 3.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 3.85%   |
| Samsung NVMe SSD Controller 980                                                  | 10        | 3.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 3.5%    |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 2.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 2.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 7         | 2.45%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 6         | 2.1%    |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 2.1%    |
| Micron Non-Volatile memory controller                                            | 5         | 1.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 1.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 1.75%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 4         | 1.4%    |
| SK hynix Gold P31 SSD                                                            | 4         | 1.4%    |
| Intel Tiger Lake-LP SATA Controller                                              | 4         | 1.4%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 1.4%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 1.05%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.05%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 3         | 1.05%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 3         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.05%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 1.05%   |
| Solid State Storage Non-Volatile memory controller                               | 2         | 0.7%    |
| SK hynix Non-Volatile memory controller                                          | 2         | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.7%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.7%    |
| Samsung Electronics SATA controller                                              | 2         | 0.7%    |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.7%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 0.7%    |
| Intel SSD 660P Series                                                            | 2         | 0.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.7%    |
| Intel Jasper Lake SATA AHCI Controller                                           | 2         | 0.7%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 2         | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 0.7%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.35%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 1         | 0.35%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.35%   |
| SK hynix BC511                                                                   | 1         | 0.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.35%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.35%   |
| Lite-On Non-Volatile memory controller                                           | 1         | 0.35%   |
| Lenovo Non-Volatile memory controller                                            | 1         | 0.35%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.35%   |
| Intel SSD 600P Series                                                            | 1         | 0.35%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.35%   |
| Intel NVMe Optane Memory Series                                                  | 1         | 0.35%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.35%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 1         | 0.35%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 1         | 0.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 179       | 63.25%  |
| NVMe | 83        | 29.33%  |
| RAID | 17        | 6.01%   |
| IDE  | 4         | 1.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 201       | 90.95%  |
| AMD    | 20        | 9.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 6.79%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 3.17%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 3.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 3.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 2.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 2.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 2.26%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 2.26%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.81%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 1.81%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 1.81%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 1.81%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.81%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.36%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 1.36%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 1.36%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 1.36%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 1.36%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 1.36%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.36%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.36%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.36%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.9%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 2         | 0.9%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.9%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.9%    |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.9%    |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.9%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.9%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.9%    |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.9%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.9%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.9%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.9%    |
| Intel Core i3-8145U CPU @ 2.10GHz             | 2         | 0.9%    |
| Intel Core i3-6100U CPU @ 2.30GHz             | 2         | 0.9%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.9%    |
| Intel Core i3-4010U CPU @ 1.70GHz             | 2         | 0.9%    |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 0.9%    |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 2         | 0.9%    |
| Intel Celeron N5100 @ 1.10GHz                 | 2         | 0.9%    |
| Intel Celeron N4100 CPU @ 1.10GHz             | 2         | 0.9%    |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.9%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 0.9%    |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 0.9%    |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.45%   |
| Intel Pentium CPU 6405U @ 2.40GHz             | 1         | 0.45%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 1         | 0.45%   |
| Intel Genuine CPU U2700 @ 1.30GHz             | 1         | 0.45%   |
| Intel Genuine CPU T1400 @ 1.73GHz             | 1         | 0.45%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.45%   |
| Intel Core i7-7560U CPU @ 2.40GHz             | 1         | 0.45%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.45%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.45%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 0.45%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 1         | 0.45%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz            | 1         | 0.45%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 1         | 0.45%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz            | 1         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 88        | 39.82%  |
| Intel Core i7    | 48        | 21.72%  |
| Intel Core i3    | 25        | 11.31%  |
| Other            | 14        | 6.33%   |
| Intel Celeron    | 10        | 4.52%   |
| AMD Ryzen 5      | 9         | 4.07%   |
| Intel Core 2 Duo | 7         | 3.17%   |
| AMD Ryzen 7      | 5         | 2.26%   |
| Intel Atom       | 4         | 1.81%   |
| Intel Pentium    | 2         | 0.9%    |
| Intel Genuine    | 2         | 0.9%    |
| AMD Ryzen 3      | 2         | 0.9%    |
| Intel Xeon       | 1         | 0.45%   |
| AMD Ryzen 9      | 1         | 0.45%   |
| AMD Ryzen 7 PRO  | 1         | 0.45%   |
| AMD Ryzen 5 PRO  | 1         | 0.45%   |
| AMD A8           | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 106       | 47.96%  |
| 4      | 84        | 38.01%  |
| 6      | 20        | 9.05%   |
| 8      | 9         | 4.07%   |
| 1      | 2         | 0.9%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 221       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 194       | 87.78%  |
| 1      | 27        | 12.22%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 217       | 97.75%  |
| Unknown        | 5         | 2.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 14.98%  |
| 0x306a9    | 25        | 11.01%  |
| 0x806ea    | 19        | 8.37%   |
| 0x806ec    | 13        | 5.73%   |
| 0x206a7    | 13        | 5.73%   |
| 0x40651    | 12        | 5.29%   |
| 0x306d4    | 12        | 5.29%   |
| 0x806c1    | 11        | 4.85%   |
| 0x906ea    | 9         | 3.96%   |
| 0x806e9    | 8         | 3.52%   |
| 0x406e3    | 7         | 3.08%   |
| 0x906e9    | 6         | 2.64%   |
| 0x306c3    | 6         | 2.64%   |
| 0x506e3    | 5         | 2.2%    |
| 0x6fd      | 4         | 1.76%   |
| 0x08108102 | 4         | 1.76%   |
| 0xa0652    | 3         | 1.32%   |
| 0x706e5    | 3         | 1.32%   |
| 0x1067a    | 3         | 1.32%   |
| 0x0a50000c | 3         | 1.32%   |
| 0x08600106 | 3         | 1.32%   |
| 0x906c0    | 2         | 0.88%   |
| 0x806d1    | 2         | 0.88%   |
| 0x706a1    | 2         | 0.88%   |
| 0x406c4    | 2         | 0.88%   |
| 0x20655    | 2         | 0.88%   |
| 0x08600104 | 2         | 0.88%   |
| 0x906ed    | 1         | 0.44%   |
| 0x806eb    | 1         | 0.44%   |
| 0x406c3    | 1         | 0.44%   |
| 0x40661    | 1         | 0.44%   |
| 0x30661    | 1         | 0.44%   |
| 0x20652    | 1         | 0.44%   |
| 0x106e5    | 1         | 0.44%   |
| 0x106ca    | 1         | 0.44%   |
| 0x0a50000b | 1         | 0.44%   |
| 0x08600103 | 1         | 0.44%   |
| 0x08108109 | 1         | 0.44%   |
| 0x07030105 | 1         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 64        | 28.96%  |
| IvyBridge     | 26        | 11.76%  |
| Haswell       | 21        | 9.5%    |
| SandyBridge   | 15        | 6.79%   |
| Skylake       | 14        | 6.33%   |
| Broadwell     | 13        | 5.88%   |
| TigerLake     | 12        | 5.43%   |
| Zen 2         | 9         | 4.07%   |
| Zen+          | 6         | 2.71%   |
| IceLake       | 5         | 2.26%   |
| Core          | 5         | 2.26%   |
| Zen 3         | 4         | 1.81%   |
| Silvermont    | 4         | 1.81%   |
| Penryn        | 4         | 1.81%   |
| Goldmont plus | 4         | 1.81%   |
| CometLake     | 4         | 1.81%   |
| Westmere      | 3         | 1.36%   |
| Tremont       | 2         | 0.9%    |
| Bonnell       | 2         | 0.9%    |
| Puma          | 1         | 0.45%   |
| Nehalem       | 1         | 0.45%   |
| Goldmont      | 1         | 0.45%   |
| Unknown       | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 190       | 62.5%   |
| Nvidia | 75        | 24.67%  |
| AMD    | 39        | 12.83%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 25        | 8.12%   |
| Intel UHD Graphics 620                                                                   | 21        | 6.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 4.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 4.22%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 3.9%    |
| Intel HD Graphics 5500                                                                   | 12        | 3.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 3.9%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.92%   |
| Intel HD Graphics 620                                                                    | 8         | 2.6%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 2.6%    |
| AMD Renoir                                                                               | 8         | 2.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 1.95%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.95%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.62%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 5         | 1.62%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 1.3%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 1.3%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 1.3%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.3%    |
| Intel HD Graphics 630                                                                    | 4         | 1.3%    |
| Intel HD Graphics 530                                                                    | 4         | 1.3%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.3%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.3%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.3%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.3%    |
| AMD Cezanne                                                                              | 4         | 1.3%    |
| Nvidia TU117M                                                                            | 3         | 0.97%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.97%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.97%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.65%   |
| Nvidia GP108M [GeForce MX330]                                                            | 2         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Max-Q]                                                | 2         | 0.65%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.65%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 2         | 0.65%   |
| Nvidia GK107GLM [Quadro K1000M]                                                          | 2         | 0.65%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.65%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.65%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.65%   |
| Intel Mobile GME965/GLE960 Integrated Graphics Controller                                | 2         | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.65%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.65%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.65%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 0.65%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 2         | 0.65%   |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 1         | 0.32%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.32%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.32%   |
| Nvidia GT218M [GeForce G210M]                                                            | 1         | 0.32%   |
| Nvidia GT215GLM [Quadro FX 1800M]                                                        | 1         | 0.32%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.32%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.32%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.32%   |
| Nvidia GM204M [GeForce GTX 970M]                                                         | 1         | 0.32%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.32%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 114       | 51.58%  |
| Intel + Nvidia | 56        | 25.34%  |
| Intel + AMD    | 20        | 9.05%   |
| 1 x Nvidia     | 12        | 5.43%   |
| 1 x AMD        | 10        | 4.52%   |
| AMD + Nvidia   | 7         | 3.17%   |
| 2 x AMD        | 2         | 0.9%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 174       | 77.68%  |
| Proprietary | 49        | 21.88%  |
| Unknown     | 1         | 0.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 143       | 63.56%  |
| 1.01-2.0   | 36        | 16%     |
| 3.01-4.0   | 20        | 8.89%   |
| 0.51-1.0   | 11        | 4.89%   |
| 0.01-0.5   | 10        | 4.44%   |
| 5.01-6.0   | 2         | 0.89%   |
| 7.01-8.0   | 1         | 0.44%   |
| 2.01-3.0   | 1         | 0.44%   |
| 8.01-16.0  | 1         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 48        | 19.51%  |
| LG Display              | 38        | 15.45%  |
| AU Optronics            | 38        | 15.45%  |
| Chimei Innolux          | 36        | 14.63%  |
| Samsung Electronics     | 22        | 8.94%   |
| Dell                    | 12        | 4.88%   |
| PANDA                   | 9         | 3.66%   |
| Sharp                   | 8         | 3.25%   |
| Lenovo                  | 6         | 2.44%   |
| InfoVision              | 5         | 2.03%   |
| LGD                     | 4         | 1.63%   |
| Goldstar                | 4         | 1.63%   |
| Apple                   | 4         | 1.63%   |
| Chi Mei Optoelectronics | 3         | 1.22%   |
| ASUSTek Computer        | 2         | 0.81%   |
| ViewSonic               | 1         | 0.41%   |
| Sony                    | 1         | 0.41%   |
| RTK                     | 1         | 0.41%   |
| Philips                 | 1         | 0.41%   |
| MStar                   | 1         | 0.41%   |
| LG Philips              | 1         | 0.41%   |
| AOC                     | 1         | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LGD LCD Monitor 1920x1080                                              | 4         | 1.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 4         | 1.63%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 4         | 1.63%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch   | 3         | 1.22%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 3         | 1.22%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch         | 3         | 1.22%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 2         | 0.81%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch      | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 310x170mm 13.9-inch   | 2         | 0.81%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch  | 2         | 0.81%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 2         | 0.81%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch           | 2         | 0.81%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch           | 2         | 0.81%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch           | 2         | 0.81%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch           | 2         | 0.81%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch            | 2         | 0.81%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch               | 2         | 0.81%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch            | 2         | 0.81%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                   | 2         | 0.81%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2         | 0.81%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch       | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch        | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch       | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch        | 2         | 0.81%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 309x174mm 14.0-inch        | 2         | 0.81%   |
| BOE LCD Monitor BOE08E7 1920x1080 344x193mm 15.5-inch                  | 2         | 0.81%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                  | 2         | 0.81%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                  | 2         | 0.81%   |
| BOE LCD Monitor BOE070D 1366x768 309x173mm 13.9-inch                   | 2         | 0.81%   |
| BOE LCD Monitor BOE06F3 1920x1080 309x173mm 13.9-inch                  | 2         | 0.81%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                   | 2         | 0.81%   |
| BOE LCD Monitor BOE05EA 1366x768 309x173mm 13.9-inch                   | 2         | 0.81%   |
| AU Optronics LCD Monitor AUO71ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.81%   |
| ASUSTek Computer VP249 AUS24AA 1920x1080 527x296mm 23.8-inch           | 2         | 0.81%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 1         | 0.41%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                  | 1         | 0.41%   |
| Sharp LQ156T1JW04 SHP153C 2560x1440 344x194mm 15.5-inch                | 1         | 0.41%   |
| Sharp LQ133M1JW08 SHP1425 1920x1080 294x165mm 13.3-inch                | 1         | 0.41%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                | 1         | 0.41%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 0.41%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                | 1         | 0.41%   |
| Sharp LCD Monitor SHP1420 1920x1080 294x165mm 13.3-inch                | 1         | 0.41%   |
| Samsung Electronics SA300/SA350 SAM078A 1366x768 410x230mm 18.5-inch   | 1         | 0.41%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch      | 1         | 0.41%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch      | 1         | 0.41%   |
| Samsung Electronics S19C170 SAM0B01 1366x768 410x230mm 18.5-inch       | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch   | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch  | 1         | 0.41%   |
| Samsung Electronics LCD Monitor SAM0F39 1920x1080 1210x680mm 54.6-inch | 1         | 0.41%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1         | 0.41%   |
| RTK C-FORCE RTK2A3B 1920x1080 531x299mm 24.0-inch                      | 1         | 0.41%   |
| Philips 190C PHLC037 1440x900 408x255mm 18.9-inch                      | 1         | 0.41%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                | 1         | 0.41%   |
| PANDA LM133LF1L01 NCP13FB 1920x1080 290x170mm 13.2-inch                | 1         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 127       | 54.04%  |
| 1366x768 (WXGA)   | 73        | 31.06%  |
| 3840x2160 (4K)    | 6         | 2.55%   |
| 1280x800 (WXGA)   | 6         | 2.55%   |
| 2560x1440 (QHD)   | 5         | 2.13%   |
| 1600x900 (HD+)    | 4         | 1.7%    |
| 1920x1200 (WUXGA) | 3         | 1.28%   |
| 2560x1600         | 2         | 0.85%   |
| 2160x1440         | 2         | 0.85%   |
| 1440x900 (WXGA+)  | 2         | 0.85%   |
| 3456x2160         | 1         | 0.43%   |
| 3440x1440         | 1         | 0.43%   |
| 3200x1800 (QHD+)  | 1         | 0.43%   |
| 2880x1800         | 1         | 0.43%   |
| 1024x600          | 1         | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 102       | 41.8%   |
| 14      | 46        | 18.85%  |
| 13      | 46        | 18.85%  |
| 21      | 8         | 3.28%   |
| 12      | 6         | 2.46%   |
| 23      | 5         | 2.05%   |
| 18      | 5         | 2.05%   |
| 17      | 5         | 2.05%   |
| Unknown | 5         | 2.05%   |
| 27      | 4         | 1.64%   |
| 24      | 3         | 1.23%   |
| 11      | 2         | 0.82%   |
| 54      | 1         | 0.41%   |
| 52      | 1         | 0.41%   |
| 46      | 1         | 0.41%   |
| 34      | 1         | 0.41%   |
| 31      | 1         | 0.41%   |
| 19      | 1         | 0.41%   |
| 10      | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 180       | 73.77%  |
| 201-300     | 21        | 8.61%   |
| 401-500     | 14        | 5.74%   |
| 501-600     | 11        | 4.51%   |
| 351-400     | 7         | 2.87%   |
| Unknown     | 5         | 2.05%   |
| 1001-1500   | 3         | 1.23%   |
| 601-700     | 2         | 0.82%   |
| 701-800     | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 197       | 89.55%  |
| 16/10   | 15        | 6.82%   |
| Unknown | 5         | 2.27%   |
| 3/2     | 2         | 0.91%   |
| 21/9    | 1         | 0.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 101       | 41.06%  |
| 81-90          | 84        | 34.15%  |
| 201-250        | 15        | 6.1%    |
| 71-80          | 8         | 3.25%   |
| 61-70          | 6         | 2.44%   |
| 121-130        | 5         | 2.03%   |
| Unknown        | 5         | 2.03%   |
| 301-350        | 4         | 1.63%   |
| 141-150        | 4         | 1.63%   |
| 151-200        | 3         | 1.22%   |
| More than 1000 | 2         | 0.81%   |
| 51-60          | 2         | 0.81%   |
| 351-500        | 2         | 0.81%   |
| 251-300        | 2         | 0.81%   |
| 41-50          | 1         | 0.41%   |
| 501-1000       | 1         | 0.41%   |
| 91-100         | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 119       | 49.58%  |
| 101-120       | 76        | 31.67%  |
| 51-100        | 20        | 8.33%   |
| 161-240       | 13        | 5.42%   |
| Unknown       | 5         | 2.08%   |
| More than 240 | 4         | 1.67%   |
| 1-50          | 3         | 1.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 193       | 85.78%  |
| 2     | 26        | 11.56%  |
| 3     | 3         | 1.33%   |
| 0     | 3         | 1.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 128       | 35.96%  |
| Realtek Semiconductor                  | 126       | 35.39%  |
| Qualcomm Atheros                       | 53        | 14.89%  |
| Broadcom                               | 19        | 5.34%   |
| Broadcom Limited                       | 6         | 1.69%   |
| MediaTek                               | 5         | 1.4%    |
| Marvell Technology Group               | 5         | 1.4%    |
| TP-Link                                | 2         | 0.56%   |
| Hewlett-Packard                        | 2         | 0.56%   |
| Xiaomi                                 | 1         | 0.28%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.28%   |
| SEGGER                                 | 1         | 0.28%   |
| Samsung Electronics                    | 1         | 0.28%   |
| Ralink Technology                      | 1         | 0.28%   |
| Qualcomm                               | 1         | 0.28%   |
| Huawei Technologies                    | 1         | 0.28%   |
| Foxconn / Hon Hai                      | 1         | 0.28%   |
| D-Link                                 | 1         | 0.28%   |
| ASUSTek Computer                       | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 86        | 20.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 5.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 3.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 3.34%   |
| Intel Wireless 3165                                               | 13        | 3.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 2.15%   |
| Intel Wireless 8265 / 8275                                        | 9         | 2.15%   |
| Intel Wireless 7265                                               | 9         | 2.15%   |
| Intel Wireless 7260                                               | 9         | 2.15%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 2.15%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 2.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 2.15%   |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 2.15%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8         | 1.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 8         | 1.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.67%   |
| Intel Centrino Ultimate-N 6300                                    | 7         | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.19%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.19%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.95%   |
| Intel Wireless 8260                                               | 4         | 0.95%   |
| Intel Wireless 3160                                               | 4         | 0.95%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 0.95%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.72%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.72%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.72%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.72%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.72%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter       | 3         | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.72%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 2         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.48%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2         | 0.48%   |
| Intel Wireless-AC 9260                                            | 2         | 0.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.48%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.48%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.48%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 2         | 0.48%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.48%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 2         | 0.48%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 0.48%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 0.48%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                 | 1         | 0.24%   |
| Sony Ericsson Mobile AB D6503                                     | 1         | 0.24%   |
| SEGGER J-Link Pro OB                                              | 1         | 0.24%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.24%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 120       | 52.63%  |
| Qualcomm Atheros      | 45        | 19.74%  |
| Realtek Semiconductor | 28        | 12.28%  |
| Broadcom              | 18        | 7.89%   |
| Broadcom Limited      | 6         | 2.63%   |
| MediaTek              | 5         | 2.19%   |
| TP-Link               | 2         | 0.88%   |
| Xiaomi                | 1         | 0.44%   |
| Ralink Technology     | 1         | 0.44%   |
| D-Link                | 1         | 0.44%   |
| ASUSTek Computer      | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 6.14%   |
| Intel Wireless 3165                                                     | 13        | 5.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 3.95%   |
| Intel Wireless 8265 / 8275                                              | 9         | 3.95%   |
| Intel Wireless 7265                                                     | 9         | 3.95%   |
| Intel Wireless 7260                                                     | 9         | 3.95%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 3.95%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 3.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 3.95%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 3.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 8         | 3.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 3.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 3.07%   |
| Intel Centrino Ultimate-N 6300                                          | 7         | 3.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 2.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 2.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 2.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.75%   |
| Intel Wireless 8260                                                     | 4         | 1.75%   |
| Intel Wireless 3160                                                     | 4         | 1.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.75%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.32%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 3         | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.32%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.88%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 2         | 0.88%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.88%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.88%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.88%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 2         | 0.88%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 0.88%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                       | 1         | 0.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.44%   |
| Realtek RTL8187SE Wireless LAN Controller                               | 1         | 0.44%   |
| Ralink MT7601U Wireless Adapter                                         | 1         | 0.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.44%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 1         | 0.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.44%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.44%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 0.44%   |
| Intel Centrino Advanced-N 6235                                          | 1         | 0.44%   |
| D-Link WLAN controller                                                  | 1         | 0.44%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 1         | 0.44%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 1         | 0.44%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 1         | 0.44%   |
| ASUS 802.11ac NIC                                                       | 1         | 0.44%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 115       | 61.5%   |
| Intel                                  | 45        | 24.06%  |
| Qualcomm Atheros                       | 13        | 6.95%   |
| Marvell Technology Group               | 5         | 2.67%   |
| Broadcom                               | 3         | 1.6%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.53%   |
| Samsung Electronics                    | 1         | 0.53%   |
| Qualcomm                               | 1         | 0.53%   |
| Huawei Technologies                    | 1         | 0.53%   |
| Hewlett-Packard                        | 1         | 0.53%   |
| Foxconn / Hon Hai                      | 1         | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 86        | 45.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 24        | 12.7%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 14        | 7.41%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 2.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 4         | 2.12%   |
| Intel Ethernet Connection (4) I219-LM                                          | 4         | 2.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 1.59%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.59%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 1.59%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.59%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 1.06%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 1.06%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 1.06%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 1.06%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.06%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.06%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 1.06%   |
| Sony Ericsson Mobile AB D6503                                                  | 1         | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.53%   |
| Realtek Realtek Ethernet controller                                            | 1         | 0.53%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.53%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1         | 0.53%   |
| Qualcomm BENGAL-QRD _SN:C5464635                                               | 1         | 0.53%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 1         | 0.53%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.53%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.53%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 1         | 0.53%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.53%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.53%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.53%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.53%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.53%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.53%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.53%   |
| Intel 82562GT 10/100 Network Connection                                        | 1         | 0.53%   |
| Huawei HUAWEI                                                                  | 1         | 0.53%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 1         | 0.53%   |
| Foxconn / Hon Hai Nokia 7.1                                                    | 1         | 0.53%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 220       | 54.46%  |
| Ethernet | 182       | 45.05%  |
| Modem    | 2         | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 190       | 81.55%  |
| Ethernet | 43        | 18.45%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 177       | 80.09%  |
| 1     | 42        | 19%     |
| 3     | 1         | 0.45%   |
| 0     | 1         | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 180       | 80%     |
| Yes  | 45        | 20%     |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 98        | 50.26%  |
| Qualcomm Atheros Communications | 25        | 12.82%  |
| Broadcom                        | 18        | 9.23%   |
| Realtek Semiconductor           | 17        | 8.72%   |
| IMC Networks                    | 11        | 5.64%   |
| Lite-On Technology              | 9         | 4.62%   |
| Hewlett-Packard                 | 4         | 2.05%   |
| Apple                           | 4         | 2.05%   |
| Foxconn / Hon Hai               | 3         | 1.54%   |
| Dell                            | 2         | 1.03%   |
| Toshiba                         | 1         | 0.51%   |
| MediaTek                        | 1         | 0.51%   |
| Cambridge Silicon Radio         | 1         | 0.51%   |
| Alps Electric                   | 1         | 0.51%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 45        | 23.08%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 19        | 9.74%   |
| Qualcomm Atheros  Bluetooth Device                  | 17        | 8.72%   |
| Intel AX201 Bluetooth                               | 15        | 7.69%   |
| Intel AX200 Bluetooth                               | 9         | 4.62%   |
| Realtek Bluetooth Radio                             | 8         | 4.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 2.56%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 2.56%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 2.05%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.05%   |
| Intel Bluetooth Device                              | 4         | 2.05%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 1.54%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.54%   |
| IMC Networks Wireless_Device                        | 3         | 1.54%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.54%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 1.54%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.54%   |
| Broadcom HP Portable SoftSailing                    | 3         | 1.54%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 3         | 1.54%   |
| Apple Bluetooth Host Controller                     | 3         | 1.54%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 1.03%   |
| Intel AX210 Bluetooth                               | 2         | 1.03%   |
| IMC Networks Bluetooth Device                       | 2         | 1.03%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.03%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.51%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.51%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.51%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.51%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.51%   |
| MediaTek Wireless_Device                            | 1         | 0.51%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.51%   |
| Lite-On Bluetooth Radio                             | 1         | 0.51%   |
| Lite-On BCM43142A0                                  | 1         | 0.51%   |
| Lite-On Atheros Bluetooth                           | 1         | 0.51%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.51%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.51%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.51%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.51%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.51%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.51%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.51%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.51%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 0.51%   |
| Broadcom BCM43142A0 Bluetooth                       | 1         | 0.51%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 0.51%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.51%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.51%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.51%   |
| Alps Electric BCM2046 Bluetooth Device              | 1         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 199       | 76.83%  |
| Nvidia                 | 35        | 13.51%  |
| AMD                    | 20        | 7.72%   |
| Plantronics            | 1         | 0.39%   |
| OPPO Electronics       | 1         | 0.39%   |
| GN Netcom              | 1         | 0.39%   |
| Generalplus Technology | 1         | 0.39%   |
| Unknown                | 1         | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 40        | 12.94%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 28        | 9.06%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 19        | 6.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 4.21%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 4.21%   |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 4.21%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 4.21%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 4.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 4.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 3.88%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 2.91%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 2.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.59%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.62%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.62%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 1.29%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.29%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.29%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.29%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.65%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.65%   |
| Nvidia Audio device                                                                               | 2         | 0.65%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.65%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.65%   |
| Plantronics Blackwire 5220 Series                                                                 | 1         | 0.32%   |
| OPPO Electronics Electronics Multimedia audio controller                                          | 1         | 0.32%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.32%   |
| Nvidia stereo controller                                                                          | 1         | 0.32%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.32%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.32%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.32%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.32%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.32%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.32%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.32%   |
| GN Netcom Jabra Link 380                                                                          | 1         | 0.32%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.32%   |
| AMD Navi 10 HDMI Audio                                                                            | 1         | 0.32%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.32%   |
| AMD FCH Azalia Controller                                                                         | 1         | 0.32%   |
| Unknown                                                                                           | 1         | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 47        | 28.31%  |
| SK hynix            | 36        | 21.69%  |
| Kingston            | 28        | 16.87%  |
| Micron Technology   | 25        | 15.06%  |
| Ramaxel Technology  | 6         | 3.61%   |
| Crucial             | 5         | 3.01%   |
| Unknown             | 4         | 2.41%   |
| G.Skill             | 3         | 1.81%   |
| Elpida              | 3         | 1.81%   |
| Corsair             | 3         | 1.81%   |
| A-DATA Technology   | 2         | 1.2%    |
| Unknown (7FE0)      | 1         | 0.6%    |
| Team                | 1         | 0.6%    |
| Kingmax             | 1         | 0.6%    |
| Apacer              | 1         | 0.6%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 2.78%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 2.22%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 2.22%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 4         | 2.22%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 2.22%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 2.22%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.67%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.67%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 3         | 1.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.11%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.11%   |
| SK hynix RAM HMA851S6CJR6N-XN 4096MB Row Of Chips DDR4 3200MT/s  | 2         | 1.11%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.11%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 1.11%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 1.11%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 2         | 1.11%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 1.11%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.11%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.11%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 1.11%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 2         | 1.11%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.11%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 2         | 1.11%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 1.11%   |
| Micron RAM 53E1G32D4NQ-046WTE 4GB Row Of Chips LPDDR4 3200MT/s   | 2         | 1.11%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 2         | 1.11%   |
| Kingston RAM 99U5428-040.A01LF 4096MB SODIMM DDR3 1334MT/s       | 2         | 1.11%   |
| G.Skill RAM F4-2666C19-8GRS 8GB SODIMM DDR4 2667MT/s             | 2         | 1.11%   |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 2         | 1.11%   |
| Crucial RAM CT4G4SFS824A.C8FF 4GB SODIMM DDR4 2400MT/s           | 2         | 1.11%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.56%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.56%   |
| Unknown (7FE0) RAM Module 8192MB SODIMM DDR4 2400MT/s            | 1         | 0.56%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 0.56%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                     | 1         | 0.56%   |
| SK hynix RAM Module 4GB SODIMM DDR4 2133MT/s                     | 1         | 0.56%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1867MT/s                  | 1         | 0.56%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.56%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2400MT/s                 | 1         | 0.56%   |
| SK hynix RAM HMT451S6CFR6A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.56%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 1         | 0.56%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.56%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 1         | 0.56%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.56%   |
| SK hynix RAM HMA851S6CJR6N-UH 4096MB SODIMM DDR4 2400MT/s        | 1         | 0.56%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 1         | 0.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.56%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.56%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s | 1         | 0.56%   |
| SK hynix RAM H5AN8G6NCJR-XNC 4GB SODIMM DDR4 3200MT/s            | 1         | 0.56%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.56%   |
| Samsung RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 74        | 57.36%  |
| DDR3   | 44        | 34.11%  |
| LPDDR4 | 5         | 3.88%   |
| LPDDR3 | 3         | 2.33%   |
| DDR2   | 2         | 1.55%   |
| SDRAM  | 1         | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 119       | 92.25%  |
| Row Of Chips | 10        | 7.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 62        | 44.29%  |
| 8192  | 53        | 37.86%  |
| 16384 | 12        | 8.57%   |
| 2048  | 11        | 7.86%   |
| 32768 | 1         | 0.71%   |
| 1024  | 1         | 0.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 41        | 28.47%  |
| 1600    | 33        | 22.92%  |
| 3200    | 28        | 19.44%  |
| 2400    | 13        | 9.03%   |
| 2133    | 6         | 4.17%   |
| 1334    | 6         | 4.17%   |
| 1333    | 5         | 3.47%   |
| 1867    | 4         | 2.78%   |
| 8400    | 2         | 1.39%   |
| 667     | 2         | 1.39%   |
| 4267    | 1         | 0.69%   |
| 4199    | 1         | 0.69%   |
| 3266    | 1         | 0.69%   |
| Unknown | 1         | 0.69%   |

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
| Chicony Electronics                    | 44        | 22.45%  |
| Microdia                               | 28        | 14.29%  |
| IMC Networks                           | 26        | 13.27%  |
| Sunplus Innovation Technology          | 22        | 11.22%  |
| Realtek Semiconductor                  | 15        | 7.65%   |
| Acer                                   | 12        | 6.12%   |
| Quanta                                 | 9         | 4.59%   |
| Syntek                                 | 7         | 3.57%   |
| Lite-On Technology                     | 6         | 3.06%   |
| Suyin                                  | 5         | 2.55%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.04%   |
| Apple                                  | 4         | 2.04%   |
| Logitech                               | 3         | 1.53%   |
| Silicon Motion                         | 2         | 1.02%   |
| Ricoh                                  | 2         | 1.02%   |
| Luxvisions Innotech Limited            | 2         | 1.02%   |
| Alcor Micro                            | 2         | 1.02%   |
| Sonix Technology                       | 1         | 0.51%   |
| Lenovo                                 | 1         | 0.51%   |
| Denron                                 | 1         | 0.51%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                 | 12        | 6.12%   |
| Sunplus Integrated_Webcam_HD                  | 11        | 5.61%   |
| Chicony Integrated Camera                     | 9         | 4.59%   |
| IMC Networks Integrated Camera                | 7         | 3.57%   |
| Realtek Integrated_Webcam_HD                  | 6         | 3.06%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 6         | 3.06%   |
| Chicony HD WebCam                             | 6         | 3.06%   |
| Syntek Integrated Camera                      | 5         | 2.55%   |
| Microdia Laptop_Integrated_Webcam_HD          | 5         | 2.55%   |
| Chicony HP HD Camera                          | 5         | 2.55%   |
| Realtek Integrated Webcam                     | 4         | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam             | 4         | 2.04%   |
| Chicony HP TrueVision HD Camera               | 4         | 2.04%   |
| Acer ThinkPad Integrated Camera               | 4         | 2.04%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 3         | 1.53%   |
| Quanta VGA WebCam                             | 3         | 1.53%   |
| IMC Networks VGA UVC WebCam                   | 3         | 1.53%   |
| Chicony Integrated HP HD Webcam               | 3         | 1.53%   |
| Chicony HP HD Webcam                          | 3         | 1.53%   |
| Acer Integrated Camera                        | 3         | 1.53%   |
| Syntek Lenovo EasyCamera                      | 2         | 1.02%   |
| Suyin Laptop_Integrated_Webcam_HD             | 2         | 1.02%   |
| Quanta HP TrueVision HD Camera                | 2         | 1.02%   |
| Quanta HP HD Camera                           | 2         | 1.02%   |
| Microdia Laptop_Integrated_Webcam_E4HD        | 2         | 1.02%   |
| Microdia Integrated Webcam HD                 | 2         | 1.02%   |
| Microdia Integrated Webcam                    | 2         | 1.02%   |
| Microdia Amcrest AWC2198 USB Webcam           | 2         | 1.02%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 1.02%   |
| Lite-On Integrated Camera                     | 2         | 1.02%   |
| Lite-On HP HD Camera                          | 2         | 1.02%   |
| IMC Networks USB2.0 UVC HD Webcam             | 2         | 1.02%   |
| IMC Networks USB Camera                       | 2         | 1.02%   |
| Chicony TOSHIBA Web Camera - HD               | 2         | 1.02%   |
| Apple iPhone 5/5C/5S/6/SE                     | 2         | 1.02%   |
| Apple FaceTime HD Camera                      | 2         | 1.02%   |
| Acer SunplusIT Integrated Camera              | 2         | 1.02%   |
| Suyin HP webcam [dv6-1190en]                  | 1         | 0.51%   |
| Suyin Acer/Lenovo Webcam [CN0316]             | 1         | 0.51%   |
| Suyin Acer CrystalEye Webcam                  | 1         | 0.51%   |
| Sunplus Laptop_Integrated_Webcam_HD           | 1         | 0.51%   |
| Sunplus Laptop Integrated WebCam HD           | 1         | 0.51%   |
| Sunplus Integrated_Webcam_FHD                 | 1         | 0.51%   |
| Sunplus HP TrueVision HD Camera               | 1         | 0.51%   |
| Sunplus HD WebCam                             | 1         | 0.51%   |
| Sunplus HD User Facing                        | 1         | 0.51%   |
| Sunplus Dell Integrated Webcam                | 1         | 0.51%   |
| Sunplus ASUS USB2.0 Webcam                    | 1         | 0.51%   |
| Sonix USB2.0 HD UVC WebCam                    | 1         | 0.51%   |
| Silicon Motion WebCam SCB-0385N               | 1         | 0.51%   |
| Silicon Motion WebCam SC-03FFL11939N          | 1         | 0.51%   |
| Ricoh Sony Vaio Integrated Webcam             | 1         | 0.51%   |
| Ricoh HD Webcam                               | 1         | 0.51%   |
| Realtek USB2.0 VGA UVC WebCam                 | 1         | 0.51%   |
| Realtek USB2.0 HD UVC WebCam                  | 1         | 0.51%   |
| Realtek USB Camera                            | 1         | 0.51%   |
| Realtek Integrated Webcam HD                  | 1         | 0.51%   |
| Realtek HD WebCam                             | 1         | 0.51%   |
| Quanta HD Webcam                              | 1         | 0.51%   |
| Quanta HD User Facing                         | 1         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 29        | 54.72%  |
| Synaptics                  | 10        | 18.87%  |
| Shenzhen Goodix Technology | 8         | 15.09%  |
| LighTuning Technology      | 2         | 3.77%   |
| Elan Microelectronics      | 2         | 3.77%   |
| Upek                       | 1         | 1.89%   |
| STMicroelectronics         | 1         | 1.89%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 13.21%  |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 11.32%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 9.43%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 7.55%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 5.66%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 5.66%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 5.66%   |
| Unknown                                                                    | 3         | 5.66%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.77%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.77%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.77%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 3.77%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.77%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.77%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.89%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.89%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.89%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.89%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.89%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.89%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.89%   |

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
| 0     | 137       | 60.89%  |
| 1     | 74        | 32.89%  |
| 2     | 11        | 4.89%   |
| 3     | 2         | 0.89%   |
| 5     | 1         | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 52        | 50.49%  |
| Graphics card            | 12        | 11.65%  |
| Net/wireless             | 10        | 9.71%   |
| Chipcard                 | 8         | 7.77%   |
| Net/ethernet             | 4         | 3.88%   |
| Camera                   | 4         | 3.88%   |
| Multimedia controller    | 3         | 2.91%   |
| Communication controller | 3         | 2.91%   |
| Bluetooth                | 3         | 2.91%   |
| Card reader              | 2         | 1.94%   |
| Storage                  | 1         | 0.97%   |
| Sound                    | 1         | 0.97%   |

