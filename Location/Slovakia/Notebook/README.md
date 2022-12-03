Linux in Slovakia - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Slovakia.

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

Total: 524

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HUAWEI        | KLVL-WXX9                   | [af7d162434](https://linux-hardware.org/?probe=af7d162434) | Nov 28, 2022 |
| Dell          | XPS 15 7590                 | [2355853fda](https://linux-hardware.org/?probe=2355853fda) | Nov 23, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d7992855ba](https://linux-hardware.org/?probe=d7992855ba) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8e17476123](https://linux-hardware.org/?probe=8e17476123) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f48e29fef2](https://linux-hardware.org/?probe=f48e29fef2) | Nov 16, 2022 |
| Acer          | Aspire VN7-791              | [736c2f5664](https://linux-hardware.org/?probe=736c2f5664) | Nov 14, 2022 |
| Lenovo        | V14-IIL 82C4                | [ca336329c8](https://linux-hardware.org/?probe=ca336329c8) | Nov 12, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [4f40815737](https://linux-hardware.org/?probe=4f40815737) | Nov 12, 2022 |
| GPD           | G1619-04                    | [cf4cb47a12](https://linux-hardware.org/?probe=cf4cb47a12) | Nov 09, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [87cfe8ed2e](https://linux-hardware.org/?probe=87cfe8ed2e) | Oct 11, 2022 |
| HP            | ENVY Laptop 13-ad0xx        | [52658eb393](https://linux-hardware.org/?probe=52658eb393) | Oct 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [19c7d98b00](https://linux-hardware.org/?probe=19c7d98b00) | Oct 06, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [72163c289e](https://linux-hardware.org/?probe=72163c289e) | Oct 05, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [97d1b5e6c5](https://linux-hardware.org/?probe=97d1b5e6c5) | Sep 30, 2022 |
| Dell          | Vostro 5391                 | [61a25cdb83](https://linux-hardware.org/?probe=61a25cdb83) | Sep 28, 2022 |
| ASUSTek       | K55VJ                       | [8e87d041c3](https://linux-hardware.org/?probe=8e87d041c3) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [afd66066bc](https://linux-hardware.org/?probe=afd66066bc) | Sep 21, 2022 |
| Lenovo        | G780                        | [04f924450d](https://linux-hardware.org/?probe=04f924450d) | Sep 17, 2022 |
| Valve         | Jupiter                     | [1dc4620833](https://linux-hardware.org/?probe=1dc4620833) | Sep 10, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [ecaa040ba1](https://linux-hardware.org/?probe=ecaa040ba1) | Sep 04, 2022 |
| Dell          | Latitude 3510               | [9477575b26](https://linux-hardware.org/?probe=9477575b26) | Sep 03, 2022 |
| UMAX          | VisionBook 14Wr Plus        | [6a2cb26049](https://linux-hardware.org/?probe=6a2cb26049) | Sep 02, 2022 |
| Toshiba       | TECRA S5                    | [121c8e110b](https://linux-hardware.org/?probe=121c8e110b) | Aug 31, 2022 |
| Toshiba       | TECRA S5                    | [6ec2bd9539](https://linux-hardware.org/?probe=6ec2bd9539) | Aug 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c407e3a17c](https://linux-hardware.org/?probe=c407e3a17c) | Aug 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [4b56f15871](https://linux-hardware.org/?probe=4b56f15871) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [dd415db306](https://linux-hardware.org/?probe=dd415db306) | Aug 28, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [8756581baa](https://linux-hardware.org/?probe=8756581baa) | Aug 21, 2022 |
| Samsung       | NC210/NC110                 | [3dcdc1dc6a](https://linux-hardware.org/?probe=3dcdc1dc6a) | Aug 15, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [1bcc13e6b4](https://linux-hardware.org/?probe=1bcc13e6b4) | Aug 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9a06c0c10c](https://linux-hardware.org/?probe=9a06c0c10c) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7e5a0c0004](https://linux-hardware.org/?probe=7e5a0c0004) | Aug 06, 2022 |
| Acer          | Aspire VN7-791G             | [3e72040097](https://linux-hardware.org/?probe=3e72040097) | Jul 31, 2022 |
| Dell          | XPS 15 9570                 | [e7f56631b1](https://linux-hardware.org/?probe=e7f56631b1) | Jul 27, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b4a9542143](https://linux-hardware.org/?probe=b4a9542143) | Jul 27, 2022 |
| Dell          | XPS 15 9570                 | [f3972b3a7d](https://linux-hardware.org/?probe=f3972b3a7d) | Jul 26, 2022 |
| HP            | ProBook 440 G3              | [04b2ed9273](https://linux-hardware.org/?probe=04b2ed9273) | Jul 19, 2022 |
| UMAX          | VisionBook-N12R             | [9ccb1f57ab](https://linux-hardware.org/?probe=9ccb1f57ab) | Jul 16, 2022 |
| HP            | ProBook 440 G3              | [c546e3b537](https://linux-hardware.org/?probe=c546e3b537) | Jul 13, 2022 |
| ASUSTek       | N550JK                      | [bc0c9431e1](https://linux-hardware.org/?probe=bc0c9431e1) | Jul 04, 2022 |
| ASUSTek       | N550JK                      | [539ce50149](https://linux-hardware.org/?probe=539ce50149) | Jul 04, 2022 |
| MSI           | EX705                       | [d85dfacff5](https://linux-hardware.org/?probe=d85dfacff5) | Jun 30, 2022 |
| MSI           | EX705                       | [3de108279f](https://linux-hardware.org/?probe=3de108279f) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5ebcb2f152](https://linux-hardware.org/?probe=5ebcb2f152) | Jun 29, 2022 |
| HP            | ZBook 15 G6                 | [2e4663e8c3](https://linux-hardware.org/?probe=2e4663e8c3) | Jun 22, 2022 |
| HP            | Pavilion dv6                | [1ba5e6c491](https://linux-hardware.org/?probe=1ba5e6c491) | Jun 18, 2022 |
| Dell          | Latitude 3510               | [4b6e3aeb9e](https://linux-hardware.org/?probe=4b6e3aeb9e) | Jun 16, 2022 |
| Dell          | Latitude E5570              | [ce4d3bb373](https://linux-hardware.org/?probe=ce4d3bb373) | Jun 09, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [fdda1deb12](https://linux-hardware.org/?probe=fdda1deb12) | Jun 07, 2022 |
| Valve         | Jupiter                     | [cc0a20bb93](https://linux-hardware.org/?probe=cc0a20bb93) | Jun 06, 2022 |
| Dell          | Latitude E6440              | [dd05b883a6](https://linux-hardware.org/?probe=dd05b883a6) | Jun 04, 2022 |
| Dell          | Vostro 5515                 | [ae8649e10b](https://linux-hardware.org/?probe=ae8649e10b) | May 28, 2022 |
| MSI           | GT60 2OC/2OD                | [c3b5eb704d](https://linux-hardware.org/?probe=c3b5eb704d) | May 22, 2022 |
| MSI           | GT60 2OC/2OD                | [96f6fda5d5](https://linux-hardware.org/?probe=96f6fda5d5) | May 22, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [0793a5608a](https://linux-hardware.org/?probe=0793a5608a) | May 15, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [d8361f7895](https://linux-hardware.org/?probe=d8361f7895) | May 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3ba9de57d1](https://linux-hardware.org/?probe=3ba9de57d1) | May 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [96be9cb5e7](https://linux-hardware.org/?probe=96be9cb5e7) | May 12, 2022 |
| Acer          | Aspire E5-575G              | [71e7f1c760](https://linux-hardware.org/?probe=71e7f1c760) | May 09, 2022 |
| MSI           | GT60 2OC/2OD                | [21f08dbab6](https://linux-hardware.org/?probe=21f08dbab6) | May 06, 2022 |
| Dell          | Inspiron 3576               | [85901f28cb](https://linux-hardware.org/?probe=85901f28cb) | May 05, 2022 |
| Acer          | Extensa 5635G               | [6e69a86d63](https://linux-hardware.org/?probe=6e69a86d63) | Apr 28, 2022 |
| HP            | ProBook 4540s               | [17272efb83](https://linux-hardware.org/?probe=17272efb83) | Apr 22, 2022 |
| Dell          | G3 3579                     | [a85e01d9d0](https://linux-hardware.org/?probe=a85e01d9d0) | Apr 20, 2022 |
| Dell          | Latitude E6520              | [33502900d8](https://linux-hardware.org/?probe=33502900d8) | Apr 19, 2022 |
| Fujitsu       | LIFEBOOK E751               | [54de39efb5](https://linux-hardware.org/?probe=54de39efb5) | Apr 12, 2022 |
| HP            | 15                          | [443dd5b9e8](https://linux-hardware.org/?probe=443dd5b9e8) | Apr 02, 2022 |
| Dell          | XPS 13 9333                 | [f4fb42182f](https://linux-hardware.org/?probe=f4fb42182f) | Apr 01, 2022 |
| ASUSTek       | X555LF                      | [35cceb0f0a](https://linux-hardware.org/?probe=35cceb0f0a) | Mar 31, 2022 |
| Fujitsu Si... | AMILO Pi 3525               | [b77907b9b6](https://linux-hardware.org/?probe=b77907b9b6) | Mar 31, 2022 |
| HP            | ProBook 4340s               | [787443949a](https://linux-hardware.org/?probe=787443949a) | Mar 27, 2022 |
| Lenovo        | ThinkPad T420 42364F2       | [d82acaba71](https://linux-hardware.org/?probe=d82acaba71) | Mar 23, 2022 |
| HP            | EliteBook 8740w             | [3ae23e0d6b](https://linux-hardware.org/?probe=3ae23e0d6b) | Mar 22, 2022 |
| ASUSTek       | K50IN                       | [02326ae250](https://linux-hardware.org/?probe=02326ae250) | Mar 22, 2022 |
| ASUSTek       | X555LNB                     | [ae49172b0f](https://linux-hardware.org/?probe=ae49172b0f) | Mar 21, 2022 |
| ASUSTek       | X555LNB                     | [33e081f100](https://linux-hardware.org/?probe=33e081f100) | Mar 21, 2022 |
| Dell          | Latitude 3510               | [f24ba2791e](https://linux-hardware.org/?probe=f24ba2791e) | Mar 19, 2022 |
| ASUSTek       | N53SN                       | [f335baa4a4](https://linux-hardware.org/?probe=f335baa4a4) | Mar 18, 2022 |
| Lenovo        | B580 20144                  | [9918c132f0](https://linux-hardware.org/?probe=9918c132f0) | Mar 13, 2022 |
| Lenovo        | B580 20144                  | [fd9ec44205](https://linux-hardware.org/?probe=fd9ec44205) | Mar 13, 2022 |
| HP            | ProBook 4340s               | [01af2dee98](https://linux-hardware.org/?probe=01af2dee98) | Mar 13, 2022 |
| HP            | EliteBook 8470p             | [76e54baafe](https://linux-hardware.org/?probe=76e54baafe) | Mar 09, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [f78b6db0bd](https://linux-hardware.org/?probe=f78b6db0bd) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [351e05ccc8](https://linux-hardware.org/?probe=351e05ccc8) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [dc09f11788](https://linux-hardware.org/?probe=dc09f11788) | Mar 08, 2022 |
| Dell          | Vostro 5515                 | [7707d7dc14](https://linux-hardware.org/?probe=7707d7dc14) | Feb 23, 2022 |
| Sony          | VPCEH3S6E                   | [334451b6e7](https://linux-hardware.org/?probe=334451b6e7) | Feb 23, 2022 |
| UMAX          | VisionBook 14Wr Plus        | [2e2c2de75c](https://linux-hardware.org/?probe=2e2c2de75c) | Feb 20, 2022 |
| ASUSTek       | K56CM                       | [c6e3cad977](https://linux-hardware.org/?probe=c6e3cad977) | Feb 19, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [9df089b1ef](https://linux-hardware.org/?probe=9df089b1ef) | Feb 19, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [c9b5c461da](https://linux-hardware.org/?probe=c9b5c461da) | Feb 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [b4d07e8ab1](https://linux-hardware.org/?probe=b4d07e8ab1) | Feb 15, 2022 |
| Dell          | Latitude E6500              | [4b35cc763b](https://linux-hardware.org/?probe=4b35cc763b) | Feb 11, 2022 |
| Dell          | Latitude E6500              | [097664c430](https://linux-hardware.org/?probe=097664c430) | Feb 11, 2022 |
| HP            | EliteBook 840 G3            | [383572d5be](https://linux-hardware.org/?probe=383572d5be) | Feb 08, 2022 |
| Toshiba       | Satellite C855-1TT          | [87eacffdb8](https://linux-hardware.org/?probe=87eacffdb8) | Feb 07, 2022 |
| MSI           | VR201                       | [5d514ac721](https://linux-hardware.org/?probe=5d514ac721) | Feb 01, 2022 |
| HP            | ProBook 450 G5              | [39511f4010](https://linux-hardware.org/?probe=39511f4010) | Jan 29, 2022 |
| ASUSTek       | K50C                        | [a285a1e873](https://linux-hardware.org/?probe=a285a1e873) | Jan 27, 2022 |
| Dell          | Latitude E5570              | [7b6a4470d6](https://linux-hardware.org/?probe=7b6a4470d6) | Jan 27, 2022 |
| Acer          | Swift SF314-43              | [11f5908f13](https://linux-hardware.org/?probe=11f5908f13) | Jan 26, 2022 |
| Lenovo        | ThinkPad 20TDZMS            | [143bc3f79b](https://linux-hardware.org/?probe=143bc3f79b) | Jan 23, 2022 |
| MSI           | MS-163B Ver                 | [2e2d0c47bd](https://linux-hardware.org/?probe=2e2d0c47bd) | Jan 23, 2022 |
| Dell          | Latitude 3510               | [47793faf9f](https://linux-hardware.org/?probe=47793faf9f) | Jan 18, 2022 |
| MSI           | EX705                       | [bf23179311](https://linux-hardware.org/?probe=bf23179311) | Jan 17, 2022 |
| ASUSTek       | X553MA                      | [a1f88f8fc7](https://linux-hardware.org/?probe=a1f88f8fc7) | Jan 15, 2022 |
| HP            | Pavilion Gaming Laptop-c... | [bc679e8ef6](https://linux-hardware.org/?probe=bc679e8ef6) | Jan 14, 2022 |
| ASUSTek       | X553MA                      | [3260495670](https://linux-hardware.org/?probe=3260495670) | Jan 13, 2022 |
| HP            | ZBook 15 G3                 | [e91280cb30](https://linux-hardware.org/?probe=e91280cb30) | Dec 31, 2021 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [b5709d8fd1](https://linux-hardware.org/?probe=b5709d8fd1) | Dec 31, 2021 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [b79036063e](https://linux-hardware.org/?probe=b79036063e) | Dec 31, 2021 |
| ASUSTek       | G751JY                      | [e7a5fad002](https://linux-hardware.org/?probe=e7a5fad002) | Dec 29, 2021 |
| HP            | ZBook 15 G3                 | [a2a0923008](https://linux-hardware.org/?probe=a2a0923008) | Dec 20, 2021 |
| HP            | ZBook 15 G3                 | [0cba25aac5](https://linux-hardware.org/?probe=0cba25aac5) | Dec 20, 2021 |
| Lenovo        | G505 20240                  | [e29df1e2a0](https://linux-hardware.org/?probe=e29df1e2a0) | Dec 19, 2021 |
| ASUSTek       | X555BP                      | [770e3752e6](https://linux-hardware.org/?probe=770e3752e6) | Dec 18, 2021 |
| Dell          | Latitude E6430              | [5d4005ae4c](https://linux-hardware.org/?probe=5d4005ae4c) | Dec 13, 2021 |
| Dell          | Latitude 3510               | [e2834c5ef6](https://linux-hardware.org/?probe=e2834c5ef6) | Dec 08, 2021 |
| Dell          | Latitude 5401               | [796c461b16](https://linux-hardware.org/?probe=796c461b16) | Dec 01, 2021 |
| Dell          | Latitude D630               | [6044bc3e07](https://linux-hardware.org/?probe=6044bc3e07) | Nov 28, 2021 |
| Apple         | MacBookPro14,1              | [795a9ffd0f](https://linux-hardware.org/?probe=795a9ffd0f) | Nov 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e1827cbbc6](https://linux-hardware.org/?probe=e1827cbbc6) | Nov 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [6fb3466f59](https://linux-hardware.org/?probe=6fb3466f59) | Nov 23, 2021 |
| Dell          | Latitude 5590               | [d8b69c36bd](https://linux-hardware.org/?probe=d8b69c36bd) | Nov 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6189028e3d](https://linux-hardware.org/?probe=6189028e3d) | Nov 23, 2021 |
| Toshiba       | Satellite Pro C850-1D5      | [22ed560714](https://linux-hardware.org/?probe=22ed560714) | Nov 21, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [55384cc552](https://linux-hardware.org/?probe=55384cc552) | Nov 18, 2021 |
| Lenovo        | Z50-70 20354                | [4c1c718d65](https://linux-hardware.org/?probe=4c1c718d65) | Nov 14, 2021 |
| Toshiba       | Satellite L500              | [82d6b16382](https://linux-hardware.org/?probe=82d6b16382) | Nov 08, 2021 |
| Toshiba       | Satellite L500              | [70e2057cff](https://linux-hardware.org/?probe=70e2057cff) | Nov 07, 2021 |
| Toshiba       | Satellite U400              | [7b2364e53a](https://linux-hardware.org/?probe=7b2364e53a) | Nov 04, 2021 |
| HP            | Presario CQ57               | [8e3ceb5db9](https://linux-hardware.org/?probe=8e3ceb5db9) | Oct 23, 2021 |
| HP            | Presario CQ57               | [78828b2790](https://linux-hardware.org/?probe=78828b2790) | Oct 21, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [644553839a](https://linux-hardware.org/?probe=644553839a) | Oct 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| ASUSTek       | K50C                        | [02e59a3759](https://linux-hardware.org/?probe=02e59a3759) | Oct 16, 2021 |
| ASUSTek       | K50C                        | [c47941a383](https://linux-hardware.org/?probe=c47941a383) | Oct 16, 2021 |
| HP            | Pavilion dv6                | [dbfa388218](https://linux-hardware.org/?probe=dbfa388218) | Oct 10, 2021 |
| HP            | 15                          | [6974f988e3](https://linux-hardware.org/?probe=6974f988e3) | Oct 06, 2021 |
| Dell          | Studio XPS 1340             | [e54daea8f9](https://linux-hardware.org/?probe=e54daea8f9) | Oct 06, 2021 |
| Dell          | Studio XPS 1340             | [ed56dc2a85](https://linux-hardware.org/?probe=ed56dc2a85) | Oct 06, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [0540c800c7](https://linux-hardware.org/?probe=0540c800c7) | Oct 02, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a508d7f60d](https://linux-hardware.org/?probe=a508d7f60d) | Oct 02, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [1e0f7c12ef](https://linux-hardware.org/?probe=1e0f7c12ef) | Oct 01, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [7efbe48343](https://linux-hardware.org/?probe=7efbe48343) | Oct 01, 2021 |
| Dell          | Latitude E6440              | [14a1218871](https://linux-hardware.org/?probe=14a1218871) | Sep 26, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [fd875fbe8c](https://linux-hardware.org/?probe=fd875fbe8c) | Sep 24, 2021 |
| Lenovo        | G580                        | [d7e35103d9](https://linux-hardware.org/?probe=d7e35103d9) | Sep 20, 2021 |
| HP            | Pavilion Notebook           | [835f183d57](https://linux-hardware.org/?probe=835f183d57) | Sep 17, 2021 |
| Toshiba       | Satellite C660              | [b2f55e8760](https://linux-hardware.org/?probe=b2f55e8760) | Sep 16, 2021 |
| Lenovo        | ThinkPad T450 20BV003SMS    | [352b2b53b8](https://linux-hardware.org/?probe=352b2b53b8) | Sep 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| Dell          | Latitude 3510               | [797c9c49c9](https://linux-hardware.org/?probe=797c9c49c9) | Sep 02, 2021 |
| HP            | Pavilion dv6700             | [48ef40abbf](https://linux-hardware.org/?probe=48ef40abbf) | Sep 02, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [05d2b6e067](https://linux-hardware.org/?probe=05d2b6e067) | Sep 01, 2021 |
| Dell          | Latitude E5570              | [7e6202db9d](https://linux-hardware.org/?probe=7e6202db9d) | Aug 31, 2021 |
| Dell          | Latitude E5570              | [95667a8c8f](https://linux-hardware.org/?probe=95667a8c8f) | Aug 31, 2021 |
| HP            | EliteBook 745 G6            | [71e3489cd9](https://linux-hardware.org/?probe=71e3489cd9) | Aug 18, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [9e66245080](https://linux-hardware.org/?probe=9e66245080) | Aug 17, 2021 |
| ASUSTek       | X51R                        | [1d1aad3900](https://linux-hardware.org/?probe=1d1aad3900) | Aug 08, 2021 |
| Teclast       | F15S                        | [49f33bd674](https://linux-hardware.org/?probe=49f33bd674) | Jul 28, 2021 |
| ASUSTek       | N551JM                      | [4334fcb285](https://linux-hardware.org/?probe=4334fcb285) | Jul 27, 2021 |
| Dell          | Latitude E5470              | [f26e3c7b39](https://linux-hardware.org/?probe=f26e3c7b39) | Jul 26, 2021 |
| Timi          | TM1701                      | [2d44d6cccb](https://linux-hardware.org/?probe=2d44d6cccb) | Jul 23, 2021 |
| HP            | Presario CQ57               | [3726c1e8c4](https://linux-hardware.org/?probe=3726c1e8c4) | Jul 15, 2021 |
| HP            | Pavilion dv6                | [4ffd108654](https://linux-hardware.org/?probe=4ffd108654) | Jul 15, 2021 |
| Lenovo        | ThinkPad L560 20F10029MC    | [a96e4cc1a5](https://linux-hardware.org/?probe=a96e4cc1a5) | Jul 12, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [8ed58d00f1](https://linux-hardware.org/?probe=8ed58d00f1) | Jun 19, 2021 |
| HP            | Pavilion dv6700             | [8d86cdfbad](https://linux-hardware.org/?probe=8d86cdfbad) | Jun 19, 2021 |
| Lenovo        | ThinkPad L540 20AUS0DW00    | [a3e83938c3](https://linux-hardware.org/?probe=a3e83938c3) | Jun 19, 2021 |
| HP            | Pavilion dv6700             | [44b174fec2](https://linux-hardware.org/?probe=44b174fec2) | Jun 18, 2021 |
| Unknown       | Unknown                     | [001462994e](https://linux-hardware.org/?probe=001462994e) | Jun 18, 2021 |
| Unknown       | Unknown                     | [049e5221b4](https://linux-hardware.org/?probe=049e5221b4) | Jun 18, 2021 |
| HP            | Pavilion dv6700             | [56342fd485](https://linux-hardware.org/?probe=56342fd485) | Jun 17, 2021 |
| Dell          | Precision 7530              | [3e5d3c4292](https://linux-hardware.org/?probe=3e5d3c4292) | Jun 15, 2021 |
| Sony          | VPCEB3L1E                   | [9048edb5d2](https://linux-hardware.org/?probe=9048edb5d2) | Jun 13, 2021 |
| Sony          | VPCEB3L1E                   | [93557b8c32](https://linux-hardware.org/?probe=93557b8c32) | Jun 13, 2021 |
| Sony          | VPCEB3L1E                   | [b90e553e8e](https://linux-hardware.org/?probe=b90e553e8e) | Jun 11, 2021 |
| Sony          | VPCEB3L1E                   | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| ASUSTek       | K54C                        | [dcdfadb154](https://linux-hardware.org/?probe=dcdfadb154) | May 31, 2021 |
| ASUSTek       | K54C                        | [252cf3ef89](https://linux-hardware.org/?probe=252cf3ef89) | May 31, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [07b30926e1](https://linux-hardware.org/?probe=07b30926e1) | May 29, 2021 |
| ASUSTek       | F3M                         | [05d9306fcc](https://linux-hardware.org/?probe=05d9306fcc) | May 28, 2021 |
| eMachines     | E725                        | [f573488bda](https://linux-hardware.org/?probe=f573488bda) | May 25, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [95b045c1a1](https://linux-hardware.org/?probe=95b045c1a1) | May 25, 2021 |
| ASUSTek       | X550CC                      | [26f506ff94](https://linux-hardware.org/?probe=26f506ff94) | May 23, 2021 |
| HP            | Unknown                     | [3584a13ae5](https://linux-hardware.org/?probe=3584a13ae5) | May 22, 2021 |
| HP            | Laptop 15-bw0xx             | [535d153c75](https://linux-hardware.org/?probe=535d153c75) | May 21, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [01af2920f0](https://linux-hardware.org/?probe=01af2920f0) | May 19, 2021 |
| Acer          | Nitro AN515-54              | [c8ac6c4b93](https://linux-hardware.org/?probe=c8ac6c4b93) | May 16, 2021 |
| Lenovo        | ThinkPad T490 20N20048GE    | [7c9dbf982e](https://linux-hardware.org/?probe=7c9dbf982e) | May 14, 2021 |
| Toshiba       | Satellite L735              | [177d534fdc](https://linux-hardware.org/?probe=177d534fdc) | May 11, 2021 |
| HP            | Pavilion dv6                | [63656472a4](https://linux-hardware.org/?probe=63656472a4) | May 10, 2021 |
| Toshiba       | Satellite L735              | [52e1221ae0](https://linux-hardware.org/?probe=52e1221ae0) | May 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [bc90a54ebf](https://linux-hardware.org/?probe=bc90a54ebf) | May 06, 2021 |
| Dell          | Latitude 5401               | [660bb28d6a](https://linux-hardware.org/?probe=660bb28d6a) | May 04, 2021 |
| Lenovo        | ThinkPad X200T 7449FWG      | [2d8d1beca4](https://linux-hardware.org/?probe=2d8d1beca4) | May 03, 2021 |
| Lenovo        | V110-15IAP 80TG             | [d4307627a7](https://linux-hardware.org/?probe=d4307627a7) | May 01, 2021 |
| Dell          | Latitude 5520               | [d339546263](https://linux-hardware.org/?probe=d339546263) | Apr 30, 2021 |
| Acer          | Aspire 3690                 | [96bd8e49db](https://linux-hardware.org/?probe=96bd8e49db) | Apr 27, 2021 |
| Lenovo        | V110-15IAP 80TG             | [530bf24d20](https://linux-hardware.org/?probe=530bf24d20) | Apr 25, 2021 |
| ASUSTek       | X550CA                      | [103cc770c2](https://linux-hardware.org/?probe=103cc770c2) | Apr 18, 2021 |
| Dell          | System XPS L702X            | [6752a255ca](https://linux-hardware.org/?probe=6752a255ca) | Apr 18, 2021 |
| Dell          | System XPS L702X            | [20c39630ac](https://linux-hardware.org/?probe=20c39630ac) | Apr 18, 2021 |
| HP            | Pavilion 11 x360 PC         | [8aab148f59](https://linux-hardware.org/?probe=8aab148f59) | Apr 17, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [1b8f927465](https://linux-hardware.org/?probe=1b8f927465) | Apr 16, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [7878f15fa6](https://linux-hardware.org/?probe=7878f15fa6) | Apr 15, 2021 |
| Dell          | Latitude 5490               | [bb7e4cf726](https://linux-hardware.org/?probe=bb7e4cf726) | Apr 13, 2021 |
| Sony          | VGN-FW31ZJ                  | [b1bc398f58](https://linux-hardware.org/?probe=b1bc398f58) | Apr 10, 2021 |
| HP            | EliteBook 840 G1            | [c6fc94dd62](https://linux-hardware.org/?probe=c6fc94dd62) | Apr 08, 2021 |
| Sony          | VGN-FW31ZJ                  | [9de66e685f](https://linux-hardware.org/?probe=9de66e685f) | Apr 05, 2021 |
| HP            | ProBook 650 G1              | [051017604f](https://linux-hardware.org/?probe=051017604f) | Apr 04, 2021 |
| Dell          | Latitude E6400              | [f4e375c3e4](https://linux-hardware.org/?probe=f4e375c3e4) | Apr 01, 2021 |
| Dell          | Latitude E5440              | [757746e097](https://linux-hardware.org/?probe=757746e097) | Apr 01, 2021 |
| ASUSTek       | X550CL                      | [72ec76771c](https://linux-hardware.org/?probe=72ec76771c) | Mar 24, 2021 |
| Toshiba       | Satellite C850-13Z          | [f8b44b58ee](https://linux-hardware.org/?probe=f8b44b58ee) | Mar 21, 2021 |
| ASUSTek       | X550CC                      | [67ef60c8b1](https://linux-hardware.org/?probe=67ef60c8b1) | Mar 20, 2021 |
| HP            | Pavilion dv5                | [f84bed8734](https://linux-hardware.org/?probe=f84bed8734) | Mar 19, 2021 |
| ASUSTek       | X550CC                      | [2f2bf700ae](https://linux-hardware.org/?probe=2f2bf700ae) | Mar 18, 2021 |
| ASUSTek       | X550CC                      | [0f7e04c439](https://linux-hardware.org/?probe=0f7e04c439) | Mar 17, 2021 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [60ad7c7aec](https://linux-hardware.org/?probe=60ad7c7aec) | Mar 17, 2021 |
| Dell          | Latitude 3510               | [24bc2a77b2](https://linux-hardware.org/?probe=24bc2a77b2) | Mar 16, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [fbebe98252](https://linux-hardware.org/?probe=fbebe98252) | Mar 13, 2021 |
| HP            | Pavilion dv6500             | [4aae1e6d26](https://linux-hardware.org/?probe=4aae1e6d26) | Mar 11, 2021 |
| HP            | Laptop 15-db1xxx            | [3d4aacd619](https://linux-hardware.org/?probe=3d4aacd619) | Mar 05, 2021 |
| HP            | Pavilion dv6                | [c26d9748f4](https://linux-hardware.org/?probe=c26d9748f4) | Mar 05, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [aedc60a146](https://linux-hardware.org/?probe=aedc60a146) | Mar 04, 2021 |
| Lenovo        | ThinkPad SL 2746AEG         | [4591f5d5af](https://linux-hardware.org/?probe=4591f5d5af) | Mar 03, 2021 |
| Lenovo        | ThinkPad T540p 20BFS14A0... | [5f75eafa25](https://linux-hardware.org/?probe=5f75eafa25) | Feb 28, 2021 |
| Google        | Gnawty                      | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Inspiron 5559               | [eca76d9f64](https://linux-hardware.org/?probe=eca76d9f64) | Feb 25, 2021 |
| Dell          | Latitude D430               | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X101CH                      | [7897616bb0](https://linux-hardware.org/?probe=7897616bb0) | Feb 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [b91a419a64](https://linux-hardware.org/?probe=b91a419a64) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| Dell          | Latitude 3510               | [8a6676e538](https://linux-hardware.org/?probe=8a6676e538) | Feb 25, 2021 |
| Acer          | Extensa 5235                | [48868a0c5e](https://linux-hardware.org/?probe=48868a0c5e) | Feb 24, 2021 |
| ASUSTek       | K52F                        | [1492b277a3](https://linux-hardware.org/?probe=1492b277a3) | Feb 24, 2021 |
| ASUSTek       | K52F                        | [0369d16c88](https://linux-hardware.org/?probe=0369d16c88) | Feb 24, 2021 |
| Lenovo        | ThinkPad T540p 20BFS14A0... | [3103f52c54](https://linux-hardware.org/?probe=3103f52c54) | Feb 24, 2021 |
| Dell          | Inspiron 5559               | [08723d28a4](https://linux-hardware.org/?probe=08723d28a4) | Feb 24, 2021 |
| HP            | Pavilion g6                 | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| eMachines     | eM350                       | [7826551972](https://linux-hardware.org/?probe=7826551972) | Feb 20, 2021 |
| Dell          | Inspiron 5559               | [cc6c16c095](https://linux-hardware.org/?probe=cc6c16c095) | Feb 19, 2021 |
| Dell          | Inspiron 7559               | [4d4377253f](https://linux-hardware.org/?probe=4d4377253f) | Feb 15, 2021 |
| Lenovo        | IdeaPad Z460 20059          | [b0b1eb3196](https://linux-hardware.org/?probe=b0b1eb3196) | Feb 14, 2021 |
| Lenovo        | IdeaPad Z460 20059          | [68fdda8114](https://linux-hardware.org/?probe=68fdda8114) | Feb 14, 2021 |
| Dell          | Inspiron 5559               | [4f0639f7c9](https://linux-hardware.org/?probe=4f0639f7c9) | Feb 10, 2021 |
| Dell          | Inspiron 5559               | [e3d953f88d](https://linux-hardware.org/?probe=e3d953f88d) | Feb 10, 2021 |
| Dell          | XPS 13 7390                 | [9d9da95c79](https://linux-hardware.org/?probe=9d9da95c79) | Feb 10, 2021 |
| Dell          | XPS 13 7390                 | [4b6ec0748c](https://linux-hardware.org/?probe=4b6ec0748c) | Feb 10, 2021 |
| Lenovo        | G500 20236                  | [bef7d62361](https://linux-hardware.org/?probe=bef7d62361) | Feb 03, 2021 |
| Dell          | Latitude D620               | [8f4c2819b9](https://linux-hardware.org/?probe=8f4c2819b9) | Feb 01, 2021 |
| HP            | ProBook 4545s               | [9c55ad844b](https://linux-hardware.org/?probe=9c55ad844b) | Jan 28, 2021 |
| HP            | Laptop 15-db1xxx            | [b38aa1a092](https://linux-hardware.org/?probe=b38aa1a092) | Jan 25, 2021 |
| HP            | Laptop 15-db1xxx            | [7a321f0327](https://linux-hardware.org/?probe=7a321f0327) | Jan 25, 2021 |
| HP            | Presario CQ57               | [7dcbdb9d0d](https://linux-hardware.org/?probe=7dcbdb9d0d) | Jan 25, 2021 |
| Lenovo        | IdeaPad 120S-14IAP          | [1469bc5f96](https://linux-hardware.org/?probe=1469bc5f96) | Jan 21, 2021 |
| Toshiba       | Satellite L850-1HP          | [1e0aa7f353](https://linux-hardware.org/?probe=1e0aa7f353) | Jan 17, 2021 |
| Lenovo        | IdeaPad 120S-14IAP          | [ce71ff03d7](https://linux-hardware.org/?probe=ce71ff03d7) | Jan 16, 2021 |
| HP            | Pavilion g6                 | [c4b4831246](https://linux-hardware.org/?probe=c4b4831246) | Jan 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [989e87e18e](https://linux-hardware.org/?probe=989e87e18e) | Jan 15, 2021 |
| ASUSTek       | X101CH                      | [3dfb714393](https://linux-hardware.org/?probe=3dfb714393) | Jan 15, 2021 |
| Google        | Gnawty                      | [b110360fd0](https://linux-hardware.org/?probe=b110360fd0) | Jan 15, 2021 |
| MSI           | CR500                       | [ff982a100f](https://linux-hardware.org/?probe=ff982a100f) | Jan 14, 2021 |
| MSI           | CR500                       | [509fd7cfd1](https://linux-hardware.org/?probe=509fd7cfd1) | Jan 14, 2021 |
| Dell          | Latitude D430               | [874d8f3925](https://linux-hardware.org/?probe=874d8f3925) | Jan 14, 2021 |
| ASUSTek       | X556UQK                     | [f70c845b60](https://linux-hardware.org/?probe=f70c845b60) | Jan 13, 2021 |
| HP            | ProBook 455 G6              | [da3110fdce](https://linux-hardware.org/?probe=da3110fdce) | Jan 11, 2021 |
| ASUSTek       | X550CC                      | [95a034c1f0](https://linux-hardware.org/?probe=95a034c1f0) | Jan 10, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [77af1025e7](https://linux-hardware.org/?probe=77af1025e7) | Jan 08, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [f3d55068a4](https://linux-hardware.org/?probe=f3d55068a4) | Jan 06, 2021 |
| HP            | EliteBook 8730w (VQ683EA... | [9650848634](https://linux-hardware.org/?probe=9650848634) | Jan 05, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [70b6c077a6](https://linux-hardware.org/?probe=70b6c077a6) | Jan 05, 2021 |
| Acer          | Swift sf514-54t             | [f56b772338](https://linux-hardware.org/?probe=f56b772338) | Jan 05, 2021 |
| HP            | ProBook 4540s               | [03c94ff635](https://linux-hardware.org/?probe=03c94ff635) | Jan 04, 2021 |
| HP            | ProBook 4540s               | [eb99a077b0](https://linux-hardware.org/?probe=eb99a077b0) | Jan 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [caa3d1d91f](https://linux-hardware.org/?probe=caa3d1d91f) | Jan 03, 2021 |
| MSI           | MS-163B Ver                 | [2406d3e9a2](https://linux-hardware.org/?probe=2406d3e9a2) | Jan 02, 2021 |
| Acer          | Aspire A515-51G             | [0440c76ce6](https://linux-hardware.org/?probe=0440c76ce6) | Jan 01, 2021 |
| MSI           | MS-163B Ver                 | [d3f6e8b5b6](https://linux-hardware.org/?probe=d3f6e8b5b6) | Dec 30, 2020 |
| Acer          | Extensa 5635G               | [a089e8fb2a](https://linux-hardware.org/?probe=a089e8fb2a) | Dec 27, 2020 |
| HP            | ProBook 450 G5              | [183d05951e](https://linux-hardware.org/?probe=183d05951e) | Dec 22, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [bab0eb442f](https://linux-hardware.org/?probe=bab0eb442f) | Dec 22, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [e59a36ff39](https://linux-hardware.org/?probe=e59a36ff39) | Dec 22, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [d239275c54](https://linux-hardware.org/?probe=d239275c54) | Dec 21, 2020 |
| Lenovo        | IdeaPad U260 20067          | [f8b68b1481](https://linux-hardware.org/?probe=f8b68b1481) | Dec 19, 2020 |
| ASUSTek       | X200MA                      | [662934e08a](https://linux-hardware.org/?probe=662934e08a) | Dec 18, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [a30ab2cb96](https://linux-hardware.org/?probe=a30ab2cb96) | Dec 16, 2020 |
| Fujitsu       | CELSIUS H760                | [bf6b408b8a](https://linux-hardware.org/?probe=bf6b408b8a) | Dec 15, 2020 |
| Toshiba       | Satellite P300              | [207e6367f2](https://linux-hardware.org/?probe=207e6367f2) | Dec 13, 2020 |
| Toshiba       | Satellite P300              | [3c0a54f9df](https://linux-hardware.org/?probe=3c0a54f9df) | Dec 11, 2020 |
| HP            | ProBook 4330s               | [22a64b85be](https://linux-hardware.org/?probe=22a64b85be) | Dec 06, 2020 |
| Dell          | Precision 7530              | [0d9da6571f](https://linux-hardware.org/?probe=0d9da6571f) | Dec 04, 2020 |
| HP            | ProBook 4330s               | [d7d25ffae4](https://linux-hardware.org/?probe=d7d25ffae4) | Dec 03, 2020 |
| Dell          | Precision 7530              | [2ea7f280b2](https://linux-hardware.org/?probe=2ea7f280b2) | Dec 02, 2020 |
| Acer          | Aspire 5742G                | [c17b4a5c87](https://linux-hardware.org/?probe=c17b4a5c87) | Nov 29, 2020 |
| ASUSTek       | ROG Zephyrus S17 GX701LW... | [f0b41bab99](https://linux-hardware.org/?probe=f0b41bab99) | Nov 28, 2020 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [e89b91cab1](https://linux-hardware.org/?probe=e89b91cab1) | Nov 25, 2020 |
| Dell          | Vostro 5370                 | [653a970a7e](https://linux-hardware.org/?probe=653a970a7e) | Nov 22, 2020 |
| ASUSTek       | X550CC                      | [0d8cea2372](https://linux-hardware.org/?probe=0d8cea2372) | Nov 21, 2020 |
| HP            | Presario CQ57               | [43ffcec233](https://linux-hardware.org/?probe=43ffcec233) | Nov 18, 2020 |
| HP            | Presario CQ57               | [ff87b0c6d6](https://linux-hardware.org/?probe=ff87b0c6d6) | Nov 16, 2020 |
| HP            | ProBook 4330s               | [c9597f3a0d](https://linux-hardware.org/?probe=c9597f3a0d) | Nov 15, 2020 |
| Acer          | Swift SF315-41              | [43d05784be](https://linux-hardware.org/?probe=43d05784be) | Nov 12, 2020 |
| Dell          | Latitude E6540              | [33d4c9409a](https://linux-hardware.org/?probe=33d4c9409a) | Nov 11, 2020 |
| Lenovo        | G780                        | [145d3ccb54](https://linux-hardware.org/?probe=145d3ccb54) | Nov 08, 2020 |
| Lenovo        | G780                        | [56faed1607](https://linux-hardware.org/?probe=56faed1607) | Nov 06, 2020 |
| Dell          | Latitude 5411               | [e880b200a0](https://linux-hardware.org/?probe=e880b200a0) | Nov 06, 2020 |
| ASUSTek       | K75VJ                       | [aa4d1aabd8](https://linux-hardware.org/?probe=aa4d1aabd8) | Nov 03, 2020 |
| MSI           | EX705                       | [4307aff155](https://linux-hardware.org/?probe=4307aff155) | Nov 02, 2020 |
| MSI           | EX705                       | [c93a29a4ec](https://linux-hardware.org/?probe=c93a29a4ec) | Nov 02, 2020 |
| HP            | 15                          | [8d582da744](https://linux-hardware.org/?probe=8d582da744) | Nov 01, 2020 |
| HP            | 15                          | [0f0be86a64](https://linux-hardware.org/?probe=0f0be86a64) | Nov 01, 2020 |
| ASUSTek       | F5GL                        | [03675a2262](https://linux-hardware.org/?probe=03675a2262) | Oct 31, 2020 |
| Packard Be... | EasyNote TK85               | [544a018464](https://linux-hardware.org/?probe=544a018464) | Oct 30, 2020 |
| Dell          | G7 7790                     | [7dd8ac2676](https://linux-hardware.org/?probe=7dd8ac2676) | Oct 30, 2020 |
| ASUSTek       | UX32VD                      | [6c9095c4b8](https://linux-hardware.org/?probe=6c9095c4b8) | Oct 30, 2020 |
| Packard Be... | EasyNote TK85               | [0d1db60c39](https://linux-hardware.org/?probe=0d1db60c39) | Oct 24, 2020 |
| Lenovo        | ThinkPad T480 20L50006XS    | [782fe456b2](https://linux-hardware.org/?probe=782fe456b2) | Oct 16, 2020 |
| Lenovo        | ThinkPad T480 20L50006XS    | [51a31505c0](https://linux-hardware.org/?probe=51a31505c0) | Oct 16, 2020 |
| HP            | Presario CQ57               | [d2883f7a48](https://linux-hardware.org/?probe=d2883f7a48) | Oct 14, 2020 |
| HP            | Presario CQ57               | [3646e51370](https://linux-hardware.org/?probe=3646e51370) | Oct 13, 2020 |
| HP            | ProBook 4540s               | [095196f795](https://linux-hardware.org/?probe=095196f795) | Oct 09, 2020 |
| HP            | ProBook 4540s               | [0272418c87](https://linux-hardware.org/?probe=0272418c87) | Oct 09, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [dd1a01df40](https://linux-hardware.org/?probe=dd1a01df40) | Oct 09, 2020 |
| HP            | EliteBook 8470p             | [51aeeb5a22](https://linux-hardware.org/?probe=51aeeb5a22) | Oct 07, 2020 |
| HP            | EliteBook 8470p             | [6bd0eacb71](https://linux-hardware.org/?probe=6bd0eacb71) | Oct 07, 2020 |
| Toshiba       | Satellite P770              | [9a6b14ab65](https://linux-hardware.org/?probe=9a6b14ab65) | Oct 07, 2020 |
| Fujitsu Si... | LIFEBOOK S6420              | [cea718db3d](https://linux-hardware.org/?probe=cea718db3d) | Sep 30, 2020 |
| Dell          | XPS 13 9380                 | [1bcd88fae1](https://linux-hardware.org/?probe=1bcd88fae1) | Sep 30, 2020 |
| HP            | ProBook 6570b               | [c36d7a3815](https://linux-hardware.org/?probe=c36d7a3815) | Sep 27, 2020 |
| Lenovo        | ThinkPad T460s 20F9003SG... | [5ee1f4ba42](https://linux-hardware.org/?probe=5ee1f4ba42) | Sep 21, 2020 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [25a18b6913](https://linux-hardware.org/?probe=25a18b6913) | Sep 20, 2020 |
| Lenovo        | IdeaPad U260 20067          | [c7ee126272](https://linux-hardware.org/?probe=c7ee126272) | Sep 18, 2020 |
| Lenovo        | G710 20252                  | [bda90e6285](https://linux-hardware.org/?probe=bda90e6285) | Sep 16, 2020 |
| MSI           | Prestige 15 A10SC           | [f9c109d38a](https://linux-hardware.org/?probe=f9c109d38a) | Sep 14, 2020 |
| Lenovo        | B590 20206                  | [241a96fabe](https://linux-hardware.org/?probe=241a96fabe) | Sep 13, 2020 |
| Lenovo        | B590 20206                  | [68c8013cac](https://linux-hardware.org/?probe=68c8013cac) | Sep 13, 2020 |
| ASUSTek       | X550CC                      | [c28899f07f](https://linux-hardware.org/?probe=c28899f07f) | Sep 10, 2020 |
| ASUSTek       | X550CC                      | [3a6d68dfe1](https://linux-hardware.org/?probe=3a6d68dfe1) | Sep 10, 2020 |
| ASUSTek       | X550CC                      | [654281ba17](https://linux-hardware.org/?probe=654281ba17) | Sep 02, 2020 |
| Dell          | Inspiron 7577               | [9243047fd5](https://linux-hardware.org/?probe=9243047fd5) | Aug 30, 2020 |
| ASUSTek       | X550CC                      | [92266759e0](https://linux-hardware.org/?probe=92266759e0) | Aug 29, 2020 |
| ASUSTek       | X550CC                      | [93baa51bda](https://linux-hardware.org/?probe=93baa51bda) | Aug 29, 2020 |
| Acer          | Swift SF314-58              | [3aa1021468](https://linux-hardware.org/?probe=3aa1021468) | Aug 28, 2020 |
| Toshiba       | Satellite C855-1TT          | [7a5dc01f13](https://linux-hardware.org/?probe=7a5dc01f13) | Aug 22, 2020 |
| Toshiba       | Satellite C855-1TT          | [98b59c7ddf](https://linux-hardware.org/?probe=98b59c7ddf) | Aug 21, 2020 |
| Lenovo        | G580                        | [e6435f1530](https://linux-hardware.org/?probe=e6435f1530) | Aug 13, 2020 |
| Sony          | VPCEH1S1E                   | [10c3c1d9d0](https://linux-hardware.org/?probe=10c3c1d9d0) | Aug 13, 2020 |
| MSI           | CR500                       | [6b04b72ba8](https://linux-hardware.org/?probe=6b04b72ba8) | Aug 06, 2020 |
| Lenovo        | ThinkPad T61 7659AB7        | [371a42eb7e](https://linux-hardware.org/?probe=371a42eb7e) | Jul 26, 2020 |
| Acer          | Aspire ES1-523              | [030cf77080](https://linux-hardware.org/?probe=030cf77080) | Jul 20, 2020 |
| Acer          | Aspire ES1-523              | [4d9339959a](https://linux-hardware.org/?probe=4d9339959a) | Jul 20, 2020 |
| HP            | Presario CQ57               | [680685ed32](https://linux-hardware.org/?probe=680685ed32) | Jul 19, 2020 |
| Dell          | Vostro 5370                 | [f8487e0c66](https://linux-hardware.org/?probe=f8487e0c66) | Jul 13, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [51d0966405](https://linux-hardware.org/?probe=51d0966405) | Jul 07, 2020 |
| UMAX          | VisionBook 14Wg Pro         | [5d2b6ed775](https://linux-hardware.org/?probe=5d2b6ed775) | Jul 06, 2020 |
| Fujitsu       | LIFEBOOK U904               | [57ca2c447b](https://linux-hardware.org/?probe=57ca2c447b) | Jul 06, 2020 |
| Lenovo        | IdeaPad Z500 20202          | [dc66cb5caf](https://linux-hardware.org/?probe=dc66cb5caf) | Jun 25, 2020 |
| UMAX          | VisionBook 14Wg Pro         | [a50a75e674](https://linux-hardware.org/?probe=a50a75e674) | Jun 21, 2020 |
| HP            | ProBook 6570b               | [f2370339d5](https://linux-hardware.org/?probe=f2370339d5) | Jun 21, 2020 |
| HP            | ProBook 6570b               | [c477dc5d5b](https://linux-hardware.org/?probe=c477dc5d5b) | Jun 18, 2020 |
| HP            | ProBook 6570b               | [d1f562df2f](https://linux-hardware.org/?probe=d1f562df2f) | Jun 18, 2020 |
| Sony          | VPCEH1L8E                   | [3b8814bf8e](https://linux-hardware.org/?probe=3b8814bf8e) | Jun 15, 2020 |
| Acer          | Aspire 5100                 | [481320cdb6](https://linux-hardware.org/?probe=481320cdb6) | Jun 09, 2020 |
| Acer          | Aspire 5100                 | [0e89938085](https://linux-hardware.org/?probe=0e89938085) | Jun 09, 2020 |
| ASUSTek       | X550CC                      | [d832045294](https://linux-hardware.org/?probe=d832045294) | Jun 06, 2020 |
| Lenovo        | ThinkPad Edge E220s 5038... | [e37f8c0d24](https://linux-hardware.org/?probe=e37f8c0d24) | Jun 05, 2020 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [a570720ce6](https://linux-hardware.org/?probe=a570720ce6) | May 26, 2020 |
| ASUSTek       | X550CC                      | [82c8b62b02](https://linux-hardware.org/?probe=82c8b62b02) | May 24, 2020 |
| ASUSTek       | X550CC                      | [8ebd135c78](https://linux-hardware.org/?probe=8ebd135c78) | May 23, 2020 |
| HP            | EliteBook 745 G3            | [1d082fe95a](https://linux-hardware.org/?probe=1d082fe95a) | May 14, 2020 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | [b8dfa98b13](https://linux-hardware.org/?probe=b8dfa98b13) | May 10, 2020 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [31d9941f79](https://linux-hardware.org/?probe=31d9941f79) | May 05, 2020 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [ddfe727f57](https://linux-hardware.org/?probe=ddfe727f57) | May 04, 2020 |
| HP            | EliteBook 850 G5            | [3e455caa1a](https://linux-hardware.org/?probe=3e455caa1a) | Apr 25, 2020 |
| HP            | Presario CQ57               | [0ba9cb0077](https://linux-hardware.org/?probe=0ba9cb0077) | Apr 25, 2020 |
| Acer          | Swift SF314-41              | [00dcbaa8f0](https://linux-hardware.org/?probe=00dcbaa8f0) | Apr 24, 2020 |
| Lenovo        | Z710 20250                  | [cf3d4e04cc](https://linux-hardware.org/?probe=cf3d4e04cc) | Apr 19, 2020 |
| ASUSTek       | T100TA                      | [ba03f5b5dd](https://linux-hardware.org/?probe=ba03f5b5dd) | Apr 19, 2020 |
| Dell          | Latitude E6540              | [0a2c664d30](https://linux-hardware.org/?probe=0a2c664d30) | Apr 19, 2020 |
| Lenovo        | B51-80 80LM                 | [b54cb44723](https://linux-hardware.org/?probe=b54cb44723) | Apr 17, 2020 |
| HP            | EliteBook 2760p             | [6631b4c0f1](https://linux-hardware.org/?probe=6631b4c0f1) | Apr 17, 2020 |
| HP            | Presario CQ57               | [9e1ad378a1](https://linux-hardware.org/?probe=9e1ad378a1) | Apr 13, 2020 |
| Lenovo        | B51-80 80LM                 | [054456ab1e](https://linux-hardware.org/?probe=054456ab1e) | Apr 12, 2020 |
| Dell          | Latitude E6540              | [1daf9c5f1a](https://linux-hardware.org/?probe=1daf9c5f1a) | Apr 10, 2020 |
| HP            | ProBook 450 G4              | [9c62a9edc6](https://linux-hardware.org/?probe=9c62a9edc6) | Apr 09, 2020 |
| Lenovo        | ThinkPad Edge E531 6885B... | [9dd9a20b65](https://linux-hardware.org/?probe=9dd9a20b65) | Apr 05, 2020 |
| Toshiba       | Satellite L450              | [b18b01a081](https://linux-hardware.org/?probe=b18b01a081) | Apr 04, 2020 |
| Lenovo        | Z710 20250                  | [0f9b8a8fc0](https://linux-hardware.org/?probe=0f9b8a8fc0) | Mar 31, 2020 |
| HP            | EliteBook 850 G6            | [f638a70ec4](https://linux-hardware.org/?probe=f638a70ec4) | Mar 30, 2020 |
| HP            | 530 Notebook PC(KD080AA#... | [aec394a418](https://linux-hardware.org/?probe=aec394a418) | Mar 27, 2020 |
| Packard Be... | EasyNote TE11BZ             | [5aaa403dee](https://linux-hardware.org/?probe=5aaa403dee) | Mar 26, 2020 |
| ASUSTek       | A6Km                        | [2c47a900f8](https://linux-hardware.org/?probe=2c47a900f8) | Mar 25, 2020 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [3f0773955d](https://linux-hardware.org/?probe=3f0773955d) | Mar 25, 2020 |
| ASUSTek       | A6Km                        | [3183eb860e](https://linux-hardware.org/?probe=3183eb860e) | Mar 24, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [56566f3fbb](https://linux-hardware.org/?probe=56566f3fbb) | Mar 23, 2020 |
| Toshiba       | Satellite P300              | [e51afe4271](https://linux-hardware.org/?probe=e51afe4271) | Mar 23, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [d5242f2534](https://linux-hardware.org/?probe=d5242f2534) | Mar 15, 2020 |
| ASUSTek       | X51L                        | [3ce2f3c47e](https://linux-hardware.org/?probe=3ce2f3c47e) | Mar 11, 2020 |
| Lenovo        | 3000 V100 07635CG           | [8c9c933a22](https://linux-hardware.org/?probe=8c9c933a22) | Mar 07, 2020 |
| Dell          | Latitude 5490               | [ab3da12d55](https://linux-hardware.org/?probe=ab3da12d55) | Feb 22, 2020 |
| Dell          | Latitude 5490               | [6b43e4ae7f](https://linux-hardware.org/?probe=6b43e4ae7f) | Feb 22, 2020 |
| ASUSTek       | F3Ke                        | [f1eaad7ea4](https://linux-hardware.org/?probe=f1eaad7ea4) | Feb 22, 2020 |
| Toshiba       | Satellite P300              | [f4642d40d8](https://linux-hardware.org/?probe=f4642d40d8) | Feb 11, 2020 |
| Google        | Gnawty                      | [4a2e211ce1](https://linux-hardware.org/?probe=4a2e211ce1) | Feb 08, 2020 |
| Toshiba       | EQUIUM A300D                | [f77888b435](https://linux-hardware.org/?probe=f77888b435) | Feb 07, 2020 |
| HP            | 635                         | [e1ed2f20e6](https://linux-hardware.org/?probe=e1ed2f20e6) | Feb 07, 2020 |
| HP            | 635                         | [0dbde497ec](https://linux-hardware.org/?probe=0dbde497ec) | Feb 06, 2020 |
| HP            | 635                         | [17396458ac](https://linux-hardware.org/?probe=17396458ac) | Feb 06, 2020 |
| HP            | 635                         | [2b47dfbcac](https://linux-hardware.org/?probe=2b47dfbcac) | Feb 06, 2020 |
| HP            | 635                         | [d980853d87](https://linux-hardware.org/?probe=d980853d87) | Feb 06, 2020 |
| HP            | 250 G3                      | [bdaa75d7d9](https://linux-hardware.org/?probe=bdaa75d7d9) | Feb 04, 2020 |
| HP            | 250 G3                      | [1a62acba2c](https://linux-hardware.org/?probe=1a62acba2c) | Feb 04, 2020 |
| HP            | ProBook 650 G1              | [897b50b880](https://linux-hardware.org/?probe=897b50b880) | Feb 03, 2020 |
| Lenovo        | ThinkPad T490 20N2S2UH00    | [693c5998b1](https://linux-hardware.org/?probe=693c5998b1) | Jan 31, 2020 |
| Timi          | TM1701                      | [921a36a46c](https://linux-hardware.org/?probe=921a36a46c) | Jan 31, 2020 |
| HP            | Pavilion Notebook           | [b677c3926c](https://linux-hardware.org/?probe=b677c3926c) | Jan 29, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [e5af1f2975](https://linux-hardware.org/?probe=e5af1f2975) | Jan 27, 2020 |
| Toshiba       | Satellite C50-A             | [fb518d95db](https://linux-hardware.org/?probe=fb518d95db) | Jan 27, 2020 |
| Toshiba       | Satellite C50-A             | [a4a37c8c40](https://linux-hardware.org/?probe=a4a37c8c40) | Jan 27, 2020 |
| Dell          | Latitude E5470              | [6fb212c97d](https://linux-hardware.org/?probe=6fb212c97d) | Jan 24, 2020 |
| Dell          | Vostro 3700                 | [bb0ea1ffd5](https://linux-hardware.org/?probe=bb0ea1ffd5) | Jan 19, 2020 |
| Acer          | Aspire 3610                 | [93dae491f3](https://linux-hardware.org/?probe=93dae491f3) | Jan 18, 2020 |
| Acer          | Aspire 3610                 | [33bbdb19d0](https://linux-hardware.org/?probe=33bbdb19d0) | Jan 18, 2020 |
| ASUSTek       | N73SV                       | [bafe93eacb](https://linux-hardware.org/?probe=bafe93eacb) | Jan 15, 2020 |
| Dell          | XPS M1530                   | [8ab2f0c35b](https://linux-hardware.org/?probe=8ab2f0c35b) | Jan 05, 2020 |
| ASUSTek       | K50IJ                       | [78b35a3d1d](https://linux-hardware.org/?probe=78b35a3d1d) | Jan 05, 2020 |
| Dell          | Vostro V130                 | [aae8826349](https://linux-hardware.org/?probe=aae8826349) | Jan 03, 2020 |
| Lenovo        | G575 20081                  | [bfd443284d](https://linux-hardware.org/?probe=bfd443284d) | Jan 01, 2020 |
| Lenovo        | G575 20081                  | [ec00d77a1a](https://linux-hardware.org/?probe=ec00d77a1a) | Jan 01, 2020 |
| Dell          | Studio 1535                 | [67d4b75167](https://linux-hardware.org/?probe=67d4b75167) | Dec 29, 2019 |
| Lenovo        | Z710 20250                  | [9ddb10548b](https://linux-hardware.org/?probe=9ddb10548b) | Dec 27, 2019 |
| Acer          | Extensa 5620                | [ba9eff4f3b](https://linux-hardware.org/?probe=ba9eff4f3b) | Dec 26, 2019 |
| Toshiba       | Satellite Pro C660          | [a36fc6a447](https://linux-hardware.org/?probe=a36fc6a447) | Dec 26, 2019 |
| Toshiba       | Satellite P300              | [6108b0c47e](https://linux-hardware.org/?probe=6108b0c47e) | Dec 25, 2019 |
| Google        | Gnawty                      | [2332ed0dd8](https://linux-hardware.org/?probe=2332ed0dd8) | Dec 23, 2019 |
| HP            | Pavilion g6                 | [9c722b6763](https://linux-hardware.org/?probe=9c722b6763) | Dec 21, 2019 |
| Acer          | Aspire 3610                 | [77353d6c03](https://linux-hardware.org/?probe=77353d6c03) | Dec 14, 2019 |
| Sony          | VPCEE2M1E                   | [9afef9e3e5](https://linux-hardware.org/?probe=9afef9e3e5) | Nov 24, 2019 |
| Sony          | SVE1713F1EW                 | [a1de0ea6f8](https://linux-hardware.org/?probe=a1de0ea6f8) | Nov 24, 2019 |
| Acer          | Crane II                    | [50122b9e8e](https://linux-hardware.org/?probe=50122b9e8e) | Nov 22, 2019 |
| Lenovo        | IdeaPad U260 20067          | [f592337622](https://linux-hardware.org/?probe=f592337622) | Nov 17, 2019 |
| eMachines     | E627                        | [874a5386c1](https://linux-hardware.org/?probe=874a5386c1) | Nov 16, 2019 |
| Medion        | E6435 MD60939               | [012a12549f](https://linux-hardware.org/?probe=012a12549f) | Nov 13, 2019 |
| eMachines     | E627                        | [55ba59c740](https://linux-hardware.org/?probe=55ba59c740) | Nov 13, 2019 |
| eMachines     | E627                        | [f984c92be5](https://linux-hardware.org/?probe=f984c92be5) | Nov 09, 2019 |
| Acer          | Crane II                    | [eba60f8297](https://linux-hardware.org/?probe=eba60f8297) | Nov 08, 2019 |
| Acer          | Crane II                    | [6c2e93de66](https://linux-hardware.org/?probe=6c2e93de66) | Nov 08, 2019 |
| eMachines     | E627                        | [0b1acfd5a2](https://linux-hardware.org/?probe=0b1acfd5a2) | Nov 06, 2019 |
| Dell          | Vostro 3700                 | [dc6f95878c](https://linux-hardware.org/?probe=dc6f95878c) | Nov 05, 2019 |
| Lenovo        | ThinkPad X230 2324HZ9       | [faddcc4f2b](https://linux-hardware.org/?probe=faddcc4f2b) | Nov 04, 2019 |
| HP            | Pavilion dv7                | [ff9ced6ef0](https://linux-hardware.org/?probe=ff9ced6ef0) | Nov 04, 2019 |
| ASUSTek       | X101CH                      | [b17de4dbad](https://linux-hardware.org/?probe=b17de4dbad) | Nov 04, 2019 |
| HP            | Notebook                    | [df94931018](https://linux-hardware.org/?probe=df94931018) | Nov 03, 2019 |
| HP            | Notebook                    | [cd5f971a86](https://linux-hardware.org/?probe=cd5f971a86) | Nov 03, 2019 |
| Lenovo        | IdeaPad Y560                | [6ca3597271](https://linux-hardware.org/?probe=6ca3597271) | Nov 03, 2019 |
| HP            | Pavilion g6                 | [2cb09606ed](https://linux-hardware.org/?probe=2cb09606ed) | Nov 01, 2019 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [cb80682975](https://linux-hardware.org/?probe=cb80682975) | Oct 20, 2019 |
| HP            | Pavilion g6                 | [6bde777445](https://linux-hardware.org/?probe=6bde777445) | Oct 20, 2019 |
| Google        | Gnawty                      | [c0b7f226f9](https://linux-hardware.org/?probe=c0b7f226f9) | Oct 20, 2019 |
| Dell          | Vostro 5370                 | [f2c990d6ba](https://linux-hardware.org/?probe=f2c990d6ba) | Oct 12, 2019 |
| Lenovo        | ThinkPad X220 42914BG       | [edfe201446](https://linux-hardware.org/?probe=edfe201446) | Oct 08, 2019 |
| Acer          | Aspire V5-531G              | [396cfb8284](https://linux-hardware.org/?probe=396cfb8284) | Oct 06, 2019 |
| ASUSTek       | X505BA                      | [85cb3c5515](https://linux-hardware.org/?probe=85cb3c5515) | Oct 05, 2019 |
| Lenovo        | ThinkPad X200 Tablet 745... | [fb6e962768](https://linux-hardware.org/?probe=fb6e962768) | Sep 27, 2019 |
| Lenovo        | ThinkPad T430 2349U2B       | [b6b8e23a2d](https://linux-hardware.org/?probe=b6b8e23a2d) | Sep 15, 2019 |
| Lenovo        | ThinkPad T430 2349U2B       | [72825d26f3](https://linux-hardware.org/?probe=72825d26f3) | Sep 15, 2019 |
| ASUSTek       | 1000H                       | [7d83011877](https://linux-hardware.org/?probe=7d83011877) | Aug 31, 2019 |
| ASUSTek       | B400VC                      | [3f5a088240](https://linux-hardware.org/?probe=3f5a088240) | Aug 29, 2019 |
| Sony          | SVE1713F1EW                 | [d5c33713cb](https://linux-hardware.org/?probe=d5c33713cb) | Aug 22, 2019 |
| Sony          | SVE1713F1EW                 | [2aa9a3f6a0](https://linux-hardware.org/?probe=2aa9a3f6a0) | Aug 20, 2019 |
| ASUSTek       | K52Jc                       | [4570331fe2](https://linux-hardware.org/?probe=4570331fe2) | Aug 15, 2019 |
| Apple         | MacBook1,1                  | [c13279cf0f](https://linux-hardware.org/?probe=c13279cf0f) | Aug 14, 2019 |
| Lenovo        | ThinkPad T570 20H90017MC    | [e51b525663](https://linux-hardware.org/?probe=e51b525663) | Aug 10, 2019 |
| Lenovo        | ThinkPad X250 20CLS23500    | [8a4778de5b](https://linux-hardware.org/?probe=8a4778de5b) | Aug 01, 2019 |
| Lenovo        | ThinkPad L470 20J4003TXS    | [6c4dc05e0c](https://linux-hardware.org/?probe=6c4dc05e0c) | Jul 09, 2019 |
| Acer          | Aspire E1-531               | [a396fdf6c6](https://linux-hardware.org/?probe=a396fdf6c6) | Jun 29, 2019 |
| Acer          | Aspire E1-531               | [dbb78eb76e](https://linux-hardware.org/?probe=dbb78eb76e) | Jun 24, 2019 |
| HP            | ProBook 4730s               | [cb342b6572](https://linux-hardware.org/?probe=cb342b6572) | Jun 05, 2019 |
| HP            | Pavilion Notebook           | [5048eb8853](https://linux-hardware.org/?probe=5048eb8853) | May 17, 2019 |
| Acer          | AOD257                      | [d95215116b](https://linux-hardware.org/?probe=d95215116b) | May 06, 2019 |
| Acer          | AOD257                      | [589983c598](https://linux-hardware.org/?probe=589983c598) | May 05, 2019 |
| Sony          | SVE1713F1EW                 | [67b367b96f](https://linux-hardware.org/?probe=67b367b96f) | Apr 23, 2019 |
| ASUSTek       | E200HA                      | [c4e22bb515](https://linux-hardware.org/?probe=c4e22bb515) | Apr 11, 2019 |
| HP            | 510 Notebook PC (RU963AA... | [87f8ef65ae](https://linux-hardware.org/?probe=87f8ef65ae) | Apr 08, 2019 |
| MSI           | GX630/GX633                 | [12132d4ebd](https://linux-hardware.org/?probe=12132d4ebd) | Mar 26, 2019 |
| Lenovo        | ThinkPad T440p 20AW0047M... | [243988734d](https://linux-hardware.org/?probe=243988734d) | Mar 25, 2019 |
| Dell          | Vostro 3700                 | [459c56742e](https://linux-hardware.org/?probe=459c56742e) | Mar 10, 2019 |
| Lenovo        | ThinkPad Edge E545 20B2S... | [d5472dae8e](https://linux-hardware.org/?probe=d5472dae8e) | Feb 21, 2019 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [f422d122fa](https://linux-hardware.org/?probe=f422d122fa) | Feb 16, 2019 |
| HP            | Compaq Presario CQ50        | [7a5481cc61](https://linux-hardware.org/?probe=7a5481cc61) | Feb 11, 2019 |
| ASUSTek       | X51R                        | [67c7bfe084](https://linux-hardware.org/?probe=67c7bfe084) | Jan 30, 2019 |
| ASUSTek       | X51R                        | [c746805402](https://linux-hardware.org/?probe=c746805402) | Jan 30, 2019 |
| HP            | ProBook 4540s               | [e7d5fe03ba](https://linux-hardware.org/?probe=e7d5fe03ba) | Jan 26, 2019 |
| MSI           | GX630/GX633                 | [42e7957235](https://linux-hardware.org/?probe=42e7957235) | Jan 22, 2019 |
| HP            | ProBook 4540s               | [2f0dc95a92](https://linux-hardware.org/?probe=2f0dc95a92) | Dec 27, 2018 |
| Lenovo        | ThinkPad L430 24655K5       | [27aaa085bb](https://linux-hardware.org/?probe=27aaa085bb) | Dec 25, 2018 |
| HP            | Compaq 6720s                | [d7475ab15e](https://linux-hardware.org/?probe=d7475ab15e) | Dec 20, 2018 |
| HP            | Compaq 6720s                | [e5cdafcee2](https://linux-hardware.org/?probe=e5cdafcee2) | Dec 20, 2018 |
| HP            | Compaq 6720s                | [83a7e31dd4](https://linux-hardware.org/?probe=83a7e31dd4) | Dec 20, 2018 |
| Lenovo        | ThinkPad T430 2349Y12       | [27f3486119](https://linux-hardware.org/?probe=27f3486119) | Dec 14, 2018 |
| Lenovo        | ThinkPad T430 2349Y12       | [94d298a37a](https://linux-hardware.org/?probe=94d298a37a) | Dec 14, 2018 |
| ASUSTek       | N55SF                       | [8b49ac8515](https://linux-hardware.org/?probe=8b49ac8515) | Nov 30, 2018 |
| Acer          | Aspire V5-572P              | [46820db730](https://linux-hardware.org/?probe=46820db730) | Nov 08, 2018 |
| Sony          | VGN-NR21J_S                 | [4cce581173](https://linux-hardware.org/?probe=4cce581173) | Oct 31, 2018 |
| Lenovo        | ThinkPad E520 1143ENG       | [107f78f681](https://linux-hardware.org/?probe=107f78f681) | Oct 30, 2018 |
| Lenovo        | ThinkPad E520 1143ENG       | [bfb0367c84](https://linux-hardware.org/?probe=bfb0367c84) | Oct 30, 2018 |
| HP            | ProBook 4330s               | [4ce0dfe7c0](https://linux-hardware.org/?probe=4ce0dfe7c0) | Oct 28, 2018 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [d5c9be9ec4](https://linux-hardware.org/?probe=d5c9be9ec4) | Oct 27, 2018 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [49aacee5b4](https://linux-hardware.org/?probe=49aacee5b4) | Oct 27, 2018 |
| ASUSTek       | X550VB                      | [931d58d353](https://linux-hardware.org/?probe=931d58d353) | Oct 21, 2018 |
| Dell          | Inspiron 7566               | [6682a76496](https://linux-hardware.org/?probe=6682a76496) | Aug 27, 2018 |
| HP            | ProBook 4545s               | [4598e67cd6](https://linux-hardware.org/?probe=4598e67cd6) | Jul 19, 2018 |
| HP            | ProBook 430 G2              | [d62a1df5c6](https://linux-hardware.org/?probe=d62a1df5c6) | May 29, 2018 |
| HP            | ProBook 430 G2              | [80ba1f23b5](https://linux-hardware.org/?probe=80ba1f23b5) | May 19, 2018 |
| Fujitsu Si... | LIFEBOOK S7220              | [d834a892f8](https://linux-hardware.org/?probe=d834a892f8) | Apr 17, 2018 |
| Toshiba       | Satellite P300              | [977054f744](https://linux-hardware.org/?probe=977054f744) | Dec 07, 2017 |
| Lenovo        | IdeaPad 305-15ABM 80NL      | [51938564c0](https://linux-hardware.org/?probe=51938564c0) | Nov 22, 2017 |
| ASUSTek       | X51L                        | [cd24ea4640](https://linux-hardware.org/?probe=cd24ea4640) | May 31, 2017 |
| Lenovo        | IdeaPad 305-15ABM 80NL      | [2524f15422](https://linux-hardware.org/?probe=2524f15422) | Mar 18, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Slovakia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 50        | 13.89%  |
| Ubuntu 18.04      | 38        | 10.56%  |
| BlackPanther 18.1 | 27        | 7.5%    |
| OpenMandriva 4.3  | 13        | 3.61%   |
| OpenMandriva 4.2  | 12        | 3.33%   |
| ROSA R10          | 8         | 2.22%   |
| Linux Mint 20.3   | 8         | 2.22%   |
| Linux Mint 19.3   | 8         | 2.22%   |
| Linux Mint 20.1   | 7         | 1.94%   |
| Fedora 34         | 7         | 1.94%   |
| Arch Rolling      | 7         | 1.94%   |
| Xubuntu 18.04     | 6         | 1.67%   |
| Ubuntu 19.04      | 6         | 1.67%   |
| MX 19             | 6         | 1.67%   |
| Linux Mint 21     | 6         | 1.67%   |
| Ubuntu 20.10      | 5         | 1.39%   |
| Pop!_OS 20.10     | 5         | 1.39%   |
| Linux Mint 20.2   | 5         | 1.39%   |
| Zorin 15          | 4         | 1.11%   |
| Ubuntu 22.04      | 4         | 1.11%   |
| ROSA R11.1        | 4         | 1.11%   |
| Pop!_OS 21.10     | 4         | 1.11%   |
| Linux Mint 19.1   | 4         | 1.11%   |
| Fedora 32         | 4         | 1.11%   |
| Fedora 31         | 4         | 1.11%   |
| Debian 10         | 4         | 1.11%   |
| Arch              | 4         | 1.11%   |
| Xubuntu 20.04     | 3         | 0.83%   |
| Pop!_OS 22.04     | 3         | 0.83%   |
| Manjaro           | 3         | 0.83%   |
| Linux Mint 19.2   | 3         | 0.83%   |
| KDE neon 20.04    | 3         | 0.83%   |
| Fedora 36         | 3         | 0.83%   |
| Fedora 33         | 3         | 0.83%   |
| Debian 11         | 3         | 0.83%   |
| Zorin 12          | 2         | 0.56%   |
| Xubuntu 18.10     | 2         | 0.56%   |
| Ubuntu 21.10      | 2         | 0.56%   |
| Ubuntu 19.10      | 2         | 0.56%   |
| Ubuntu 18.10      | 2         | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 108       | 31.49%  |
| Linux Mint   | 37        | 10.79%  |
| BlackPanther | 28        | 8.16%   |
| Fedora       | 26        | 7.58%   |
| OpenMandriva | 25        | 7.29%   |
| ROSA         | 15        | 4.37%   |
| Pop!_OS      | 13        | 3.79%   |
| Xubuntu      | 11        | 3.21%   |
| Arch         | 11        | 3.21%   |
| Manjaro      | 8         | 2.33%   |
| Kubuntu      | 8         | 2.33%   |
| Debian       | 8         | 2.33%   |
| Zorin        | 7         | 2.04%   |
| MX           | 7         | 2.04%   |
| Ubuntu Unity | 3         | 0.87%   |
| KDE neon     | 3         | 0.87%   |
| Gentoo       | 3         | 0.87%   |
| Endless      | 3         | 0.87%   |
| Ubuntu MATE  | 2         | 0.58%   |
| SteamOS      | 2         | 0.58%   |
| ArcoLinux    | 2         | 0.58%   |
| Rocky Linux  | 1         | 0.29%   |
| openSUSE     | 1         | 0.29%   |
| Lubuntu      | 1         | 0.29%   |
| Linux Lite   | 1         | 0.29%   |
| Kaisen       | 1         | 0.29%   |
| GNOME OS     | 1         | 0.29%   |
| GalliumOS    | 1         | 0.29%   |
| EndeavourOS  | 1         | 0.29%   |
| Elementary   | 1         | 0.29%   |
| Devuan       | 1         | 0.29%   |
| Clear Linux  | 1         | 0.29%   |
| CentOS       | 1         | 0.29%   |
| Alpine       | 1         | 0.29%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 4.18.16-desktop-1bP              | 20        | 5.28%   |
| 5.16.7-desktop-1omv4003          | 13        | 3.43%   |
| 5.10.14-desktop-1omv4002         | 12        | 3.17%   |
| 5.6.14-desktop-2bP               | 10        | 2.64%   |
| 5.4.0-58-generic                 | 8         | 2.11%   |
| 5.4.0-42-generic                 | 7         | 1.85%   |
| 5.4.0-52-generic                 | 5         | 1.32%   |
| 5.11.0-27-generic                | 5         | 1.32%   |
| 5.8.0-43-generic                 | 4         | 1.06%   |
| 5.4.0-73-generic                 | 4         | 1.06%   |
| 5.4.0-47-generic                 | 4         | 1.06%   |
| 4.9.60-nrj-desktop-1rosa-x86_64  | 4         | 1.06%   |
| 4.15.0-66-generic                | 4         | 1.06%   |
| 5.8.0-50-generic                 | 3         | 0.79%   |
| 5.8.0-29-generic                 | 3         | 0.79%   |
| 5.4.0-91-generic                 | 3         | 0.79%   |
| 5.4.0-88-generic                 | 3         | 0.79%   |
| 5.3.0-40-generic                 | 3         | 0.79%   |
| 5.3.0-26-generic                 | 3         | 0.79%   |
| 5.15.0-47-generic                | 3         | 0.79%   |
| 5.13.0-40-generic                | 3         | 0.79%   |
| 5.13.0-35-generic                | 3         | 0.79%   |
| 5.0.0-25-generic                 | 3         | 0.79%   |
| 4.9.124-nrj-desktop-1rosa-x86_64 | 3         | 0.79%   |
| 4.19.0-13-amd64                  | 3         | 0.79%   |
| 4.15.0-55-generic                | 3         | 0.79%   |
| 5.9.16-200.fc33.x86_64           | 2         | 0.53%   |
| 5.8.0-7630-generic               | 2         | 0.53%   |
| 5.8.0-7625-generic               | 2         | 0.53%   |
| 5.4.83-generic-2rosa-x86_64      | 2         | 0.53%   |
| 5.4.0-96-generic                 | 2         | 0.53%   |
| 5.4.0-65-generic                 | 2         | 0.53%   |
| 5.4.0-48-generic                 | 2         | 0.53%   |
| 5.4.0-29-generic                 | 2         | 0.53%   |
| 5.4.0-26-generic                 | 2         | 0.53%   |
| 5.3.0-46-generic                 | 2         | 0.53%   |
| 5.3.0-42-generic                 | 2         | 0.53%   |
| 5.3.0-28-generic                 | 2         | 0.53%   |
| 5.3.0-24-generic                 | 2         | 0.53%   |
| 5.15.0-48-generic                | 2         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 64        | 17.68%  |
| 4.15.0  | 35        | 9.67%   |
| 5.8.0   | 23        | 6.35%   |
| 4.18.16 | 20        | 5.52%   |
| 5.3.0   | 17        | 4.7%    |
| 5.13.0  | 17        | 4.7%    |
| 5.11.0  | 15        | 4.14%   |
| 5.0.0   | 15        | 4.14%   |
| 5.16.7  | 13        | 3.59%   |
| 5.10.14 | 12        | 3.31%   |
| 5.15.0  | 11        | 3.04%   |
| 5.6.14  | 10        | 2.76%   |
| 5.10.0  | 7         | 1.93%   |
| 4.19.0  | 7         | 1.93%   |
| 4.18.0  | 7         | 1.93%   |
| 4.9.60  | 4         | 1.1%    |
| 5.9.16  | 3         | 0.83%   |
| 5.17.5  | 3         | 0.83%   |
| 5.11.11 | 3         | 0.83%   |
| 4.9.124 | 3         | 0.83%   |
| 5.4.83  | 2         | 0.55%   |
| 5.19.0  | 2         | 0.55%   |
| 5.17.1  | 2         | 0.55%   |
| 5.15.75 | 2         | 0.55%   |
| 5.11.3  | 2         | 0.55%   |
| 4.9.20  | 2         | 0.55%   |
| 4.4.0   | 2         | 0.55%   |
| 6.0.6   | 1         | 0.28%   |
| 5.9.4   | 1         | 0.28%   |
| 5.8.9   | 1         | 0.28%   |
| 5.7.19  | 1         | 0.28%   |
| 5.7.12  | 1         | 0.28%   |
| 5.6.13  | 1         | 0.28%   |
| 5.6.11  | 1         | 0.28%   |
| 5.6.0   | 1         | 0.28%   |
| 5.5.8   | 1         | 0.28%   |
| 5.5.5   | 1         | 0.28%   |
| 5.5.17  | 1         | 0.28%   |
| 5.5.11  | 1         | 0.28%   |
| 5.5.0   | 1         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 68        | 18.84%  |
| 4.15    | 35        | 9.7%    |
| 4.18    | 27        | 7.48%   |
| 5.10    | 25        | 6.93%   |
| 5.8     | 24        | 6.65%   |
| 5.15    | 22        | 6.09%   |
| 5.11    | 21        | 5.82%   |
| 5.13    | 20        | 5.54%   |
| 5.3     | 19        | 5.26%   |
| 5.0     | 17        | 4.71%   |
| 5.16    | 15        | 4.16%   |
| 5.6     | 13        | 3.6%    |
| 4.9     | 11        | 3.05%   |
| 4.19    | 8         | 2.22%   |
| 5.17    | 7         | 1.94%   |
| 5.5     | 5         | 1.39%   |
| 5.19    | 5         | 1.39%   |
| 5.9     | 4         | 1.11%   |
| 5.12    | 3         | 0.83%   |
| 5.7     | 2         | 0.55%   |
| 5.18    | 2         | 0.55%   |
| 4.4     | 2         | 0.55%   |
| 6.0     | 1         | 0.28%   |
| 5.2     | 1         | 0.28%   |
| 4.17    | 1         | 0.28%   |
| 4.16    | 1         | 0.28%   |
| 4.12    | 1         | 0.28%   |
| 4.1     | 1         | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 306       | 91.62%  |
| i686   | 28        | 8.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 120       | 34.99%  |
| KDE5            | 80        | 23.32%  |
| Unknown         | 47        | 13.7%   |
| XFCE            | 34        | 9.91%   |
| X-Cinnamon      | 29        | 8.45%   |
| KDE4            | 8         | 2.33%   |
| MATE            | 7         | 2.04%   |
| KDE             | 7         | 2.04%   |
| Unity           | 3         | 0.87%   |
| Cinnamon        | 3         | 0.87%   |
| LXDE            | 2         | 0.58%   |
| Pantheon        | 1         | 0.29%   |
| GNOME Flashback | 1         | 0.29%   |
| awesome         | 1         | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 280       | 83.09%  |
| Wayland | 34        | 10.09%  |
| Unknown | 20        | 5.93%   |
| Tty     | 3         | 0.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 175       | 51.32%  |
| SDDM    | 71        | 20.82%  |
| GDM     | 31        | 9.09%   |
| LightDM | 25        | 7.33%   |
| GDM3    | 19        | 5.57%   |
| TDM     | 11        | 3.23%   |
| KDM     | 8         | 2.35%   |
| XDM     | 1         | 0.29%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 131       | 38.08%  |
| sk_SK   | 98        | 28.49%  |
| Unknown | 87        | 25.29%  |
| cs_CZ   | 10        | 2.91%   |
| hu_HU   | 5         | 1.45%   |
| en_GB   | 4         | 1.16%   |
| C       | 4         | 1.16%   |
| ru_UA   | 1         | 0.29%   |
| ru_RU   | 1         | 0.29%   |
| it_IT   | 1         | 0.29%   |
| en_US  | 1         | 0.29%   |
| C.UTF8  | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 197       | 57.94%  |
| EFI  | 143       | 42.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 237       | 69.3%   |
| Overlay | 55        | 16.08%  |
| Btrfs   | 21        | 6.14%   |
| Unknown | 16        | 4.68%   |
| Zfs     | 5         | 1.46%   |
| Xfs     | 4         | 1.17%   |
| Ext3    | 2         | 0.58%   |
| Ext2    | 2         | 0.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 190       | 55.56%  |
| GPT     | 84        | 24.56%  |
| MBR     | 68        | 19.88%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 286       | 83.63%  |
| Yes       | 56        | 16.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 225       | 66.96%  |
| Yes       | 111       | 33.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 88        | 26.43%  |
| Hewlett-Packard     | 59        | 17.72%  |
| ASUSTek Computer    | 57        | 17.12%  |
| Dell                | 44        | 13.21%  |
| Acer                | 24        | 7.21%   |
| Toshiba             | 16        | 4.8%    |
| Sony                | 8         | 2.4%    |
| MSI                 | 8         | 2.4%    |
| UMAX                | 4         | 1.2%    |
| Fujitsu Siemens     | 4         | 1.2%    |
| Fujitsu             | 3         | 0.9%    |
| eMachines           | 3         | 0.9%    |
| Valve               | 2         | 0.6%    |
| Samsung Electronics | 2         | 0.6%    |
| Packard Bell        | 2         | 0.6%    |
| Apple               | 2         | 0.6%    |
| Timi                | 1         | 0.3%    |
| Teclast             | 1         | 0.3%    |
| Medion              | 1         | 0.3%    |
| HUAWEI              | 1         | 0.3%    |
| GPD                 | 1         | 0.3%    |
| Google              | 1         | 0.3%    |
| Unknown             | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| ASUS X550CC                            | 4         | 1.2%    |
| HP ProBook 4540s                       | 3         | 0.9%    |
| HP Pavilion dv6                        | 3         | 0.9%    |
| Valve Jupiter                          | 2         | 0.6%    |
| UMAX VisionBook 14Wr Plus              | 2         | 0.6%    |
| Toshiba Satellite P300                 | 2         | 0.6%    |
| MSI VR610                              | 2         | 0.6%    |
| Lenovo Yoga Slim 7 Pro 14ITL5 82FX     | 2         | 0.6%    |
| Lenovo IdeaPad U260 20067              | 2         | 0.6%    |
| Lenovo IdeaPad S145-14AST 81ST         | 2         | 0.6%    |
| Lenovo G580                            | 2         | 0.6%    |
| HP ProBook 6570b                       | 2         | 0.6%    |
| HP ProBook 650 G1                      | 2         | 0.6%    |
| HP ProBook 4545s                       | 2         | 0.6%    |
| HP ProBook 450 G5                      | 2         | 0.6%    |
| HP ProBook 4330s                       | 2         | 0.6%    |
| HP EliteBook 8470p                     | 2         | 0.6%    |
| Dell Precision 7530                    | 2         | 0.6%    |
| Dell Latitude E6540                    | 2         | 0.6%    |
| Dell Latitude 5490                     | 2         | 0.6%    |
| Dell Latitude 5401                     | 2         | 0.6%    |
| ASUS X51R                              | 2         | 0.6%    |
| ASUS X51L                              | 2         | 0.6%    |
| ASUS VivoBook_ASUSLaptop X509DJ_D509DJ | 2         | 0.6%    |
| ASUS K50C                              | 2         | 0.6%    |
| Acer Extensa 5635G                     | 2         | 0.6%    |
| Unknown                                | 2         | 0.6%    |
| UMAX VisionBook-N12R                   | 1         | 0.3%    |
| UMAX VisionBook 14Wg Pro               | 1         | 0.3%    |
| Toshiba TECRA S5                       | 1         | 0.3%    |
| Toshiba Satellite U400                 | 1         | 0.3%    |
| Toshiba Satellite Pro C850-1D5         | 1         | 0.3%    |
| Toshiba Satellite Pro C660             | 1         | 0.3%    |
| Toshiba Satellite P770                 | 1         | 0.3%    |
| Toshiba Satellite L850-1HP             | 1         | 0.3%    |
| Toshiba Satellite L735                 | 1         | 0.3%    |
| Toshiba Satellite L500                 | 1         | 0.3%    |
| Toshiba Satellite L450                 | 1         | 0.3%    |
| Toshiba Satellite C855-1TT             | 1         | 0.3%    |
| Toshiba Satellite C850-13Z             | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 40        | 12.01%  |
| Lenovo IdeaPad           | 25        | 7.51%   |
| Dell Latitude            | 21        | 6.31%   |
| HP ProBook               | 20        | 6.01%   |
| Toshiba Satellite        | 14        | 4.2%    |
| HP EliteBook             | 12        | 3.6%    |
| Acer Aspire              | 12        | 3.6%    |
| HP Pavilion              | 11        | 3.3%    |
| Dell XPS                 | 6         | 1.8%    |
| Dell Vostro              | 5         | 1.5%    |
| Dell Inspiron            | 5         | 1.5%    |
| ASUS ROG                 | 5         | 1.5%    |
| Acer Swift               | 5         | 1.5%    |
| ASUS X550CC              | 4         | 1.2%    |
| ASUS VivoBook            | 4         | 1.2%    |
| Acer Extensa             | 4         | 1.2%    |
| UMAX VisionBook          | 3         | 0.9%    |
| Lenovo Yoga              | 3         | 0.9%    |
| Lenovo Legion            | 3         | 0.9%    |
| HP ZBook                 | 3         | 0.9%    |
| Valve Jupiter            | 2         | 0.6%    |
| Packard Bell EasyNote    | 2         | 0.6%    |
| MSI VR610                | 2         | 0.6%    |
| Lenovo G580              | 2         | 0.6%    |
| HP Laptop                | 2         | 0.6%    |
| HP Compaq                | 2         | 0.6%    |
| Fujitsu Siemens LIFEBOOK | 2         | 0.6%    |
| Fujitsu LIFEBOOK         | 2         | 0.6%    |
| Dell Studio              | 2         | 0.6%    |
| Dell Precision           | 2         | 0.6%    |
| ASUS ZenBook             | 2         | 0.6%    |
| ASUS X51R                | 2         | 0.6%    |
| ASUS X51L                | 2         | 0.6%    |
| ASUS K50C                | 2         | 0.6%    |
| Unknown                  | 2         | 0.6%    |
| UMAX VisionBook-N12R     | 1         | 0.3%    |
| Toshiba TECRA            | 1         | 0.3%    |
| Toshiba EQUIUM           | 1         | 0.3%    |
| Timi TM1701              | 1         | 0.3%    |
| Teclast F15S             | 1         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 35        | 10.51%  |
| 2012 | 35        | 10.51%  |
| 2019 | 29        | 8.71%   |
| 2011 | 27        | 8.11%   |
| 2008 | 23        | 6.91%   |
| 2017 | 20        | 6.01%   |
| 2020 | 19        | 5.71%   |
| 2018 | 18        | 5.41%   |
| 2016 | 18        | 5.41%   |
| 2009 | 18        | 5.41%   |
| 2007 | 18        | 5.41%   |
| 2021 | 17        | 5.11%   |
| 2010 | 17        | 5.11%   |
| 2015 | 14        | 4.2%    |
| 2014 | 13        | 3.9%    |
| 2006 | 7         | 2.1%    |
| 2022 | 4         | 1.2%    |
| 2005 | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 333       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 303       | 90.45%  |
| Enabled  | 32        | 9.55%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 332       | 99.7%   |
| Yes  | 1         | 0.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 94        | 27.98%  |
| 4.01-8.0    | 81        | 24.11%  |
| 8.01-16.0   | 54        | 16.07%  |
| 16.01-24.0  | 49        | 14.58%  |
| 1.01-2.0    | 27        | 8.04%   |
| 32.01-64.0  | 13        | 3.87%   |
| 2.01-3.0    | 11        | 3.27%   |
| 0.51-1.0    | 5         | 1.49%   |
| 24.01-32.0  | 1         | 0.3%    |
| 64.01-256.0 | 1         | 0.3%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 141       | 39.28%  |
| 2.01-3.0  | 70        | 19.5%   |
| 0.51-1.0  | 58        | 16.16%  |
| 3.01-4.0  | 36        | 10.03%  |
| 4.01-8.0  | 34        | 9.47%   |
| 8.01-16.0 | 12        | 3.34%   |
| 0.01-0.5  | 8         | 2.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 242       | 69.94%  |
| 2      | 83        | 23.99%  |
| 3      | 15        | 4.34%   |
| 0      | 6         | 1.73%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 186       | 55.69%  |
| Yes       | 148       | 44.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 290       | 86.83%  |
| No        | 44        | 13.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 329       | 98.8%   |
| No        | 4         | 1.2%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 244       | 72.84%  |
| No        | 91        | 27.16%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Slovakia | 333       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Bratislava           | 134       | 37.12%  |
| Banská Bystrica     | 17        | 4.71%   |
| Nitra                | 14        | 3.88%   |
| Košice              | 14        | 3.88%   |
| Trnava               | 6         | 1.66%   |
| Prešov              | 6         | 1.66%   |
| Humenné             | 6         | 1.66%   |
| Martin               | 5         | 1.39%   |
| Zvolen               | 4         | 1.11%   |
| Žilina              | 4         | 1.11%   |
| Trenčín            | 4         | 1.11%   |
| Soblahov             | 4         | 1.11%   |
| Nové Zámky         | 4         | 1.11%   |
| Bardejov             | 4         | 1.11%   |
| Topoľčany          | 3         | 0.83%   |
| Senec                | 3         | 0.83%   |
| Poprad               | 3         | 0.83%   |
| Námestovo           | 3         | 0.83%   |
| Lučenec             | 3         | 0.83%   |
| Levice               | 3         | 0.83%   |
| Kysucké Nové Mesto | 3         | 0.83%   |
| Dunajská Streda     | 3         | 0.83%   |
| Voderady             | 2         | 0.55%   |
| Vlkova               | 2         | 0.55%   |
| Tornaľa             | 2         | 0.55%   |
| Štúrovo            | 2         | 0.55%   |
| Stara Tura           | 2         | 0.55%   |
| Ružomberok          | 2         | 0.55%   |
| Rožňava            | 2         | 0.55%   |
| Rohoznik             | 2         | 0.55%   |
| Podhradie            | 2         | 0.55%   |
| Most pri Bratislave  | 2         | 0.55%   |
| Modra                | 2         | 0.55%   |
| Liptovský Mikuláš | 2         | 0.55%   |
| Krupina              | 2         | 0.55%   |
| Galanta              | 2         | 0.55%   |
| Chorvatsky Grob      | 2         | 0.55%   |
| Cerveny Kamen        | 2         | 0.55%   |
| Cechynce             | 2         | 0.55%   |
| Biely Kostol         | 2         | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 61        | 70     | 14.15%  |
| Seagate             | 60        | 70     | 13.92%  |
| Samsung Electronics | 53        | 63     | 12.3%   |
| Toshiba             | 31        | 43     | 7.19%   |
| Kingston            | 28        | 37     | 6.5%    |
| SanDisk             | 26        | 29     | 6.03%   |
| Unknown             | 23        | 37     | 5.34%   |
| Intel               | 17        | 20     | 3.94%   |
| Hitachi             | 17        | 17     | 3.94%   |
| Patriot             | 15        | 23     | 3.48%   |
| SK hynix            | 12        | 15     | 2.78%   |
| Micron Technology   | 12        | 14     | 2.78%   |
| A-DATA Technology   | 12        | 19     | 2.78%   |
| HGST                | 11        | 15     | 2.55%   |
| Crucial             | 9         | 12     | 2.09%   |
| Fujitsu             | 4         | 4      | 0.93%   |
| LITEON              | 3         | 3      | 0.7%    |
| Unknown             | 3         | 3      | 0.7%    |
| Verbatim            | 2         | 2      | 0.46%   |
| Union Memory        | 2         | 2      | 0.46%   |
| Transcend           | 2         | 2      | 0.46%   |
| Phison              | 2         | 2      | 0.46%   |
| OCZ                 | 2         | 2      | 0.46%   |
| LITEONIT            | 2         | 2      | 0.46%   |
| KIOXIA              | 2         | 10     | 0.46%   |
| Apacer              | 2         | 2      | 0.46%   |
| ZTE                 | 1         | 1      | 0.23%   |
| WDC WDS2            | 1         | 1      | 0.23%   |
| Solid State Storage | 1         | 1      | 0.23%   |
| Phison Electronics  | 1         | 1      | 0.23%   |
| KingSpec            | 1         | 1      | 0.23%   |
| KingDian            | 1         | 3      | 0.23%   |
| JMicron Technology  | 1         | 1      | 0.23%   |
| Intenso             | 1         | 1      | 0.23%   |
| IM3D                | 1         | 1      | 0.23%   |
| IBM/Hitachi         | 1         | 1      | 0.23%   |
| HUAWEI              | 1         | 1      | 0.23%   |
| HS-SSD-E100         | 1         | 1      | 0.23%   |
| Hewlett-Packard     | 1         | 1      | 0.23%   |
| Faspeed             | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB              | 9         | 2%      |
| Patriot Burst 240GB SSD                | 9         | 2%      |
| Patriot Burst 480GB SSD                | 7         | 1.56%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 5         | 1.11%   |
| Unknown MMC Card  64GB                 | 5         | 1.11%   |
| Seagate ST9500420AS 500GB              | 5         | 1.11%   |
| Seagate ST9500325AS 500GB              | 5         | 1.11%   |
| SanDisk NVMe SSD Drive 1024GB          | 5         | 1.11%   |
| Samsung SSD 850 EVO 500GB              | 5         | 1.11%   |
| Kingston SV300S37A120G 120GB SSD       | 5         | 1.11%   |
| Kingston SA400S37240G 240GB SSD        | 5         | 1.11%   |
| Kingston SA400S37120G 120GB SSD        | 5         | 1.11%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 4         | 0.89%   |
| Seagate ST1000LM035-1RK172 1TB         | 4         | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 4         | 0.89%   |
| SanDisk NVMe SSD Drive 512GB           | 4         | 0.89%   |
| HGST HTS725050A7E630 500GB             | 4         | 0.89%   |
| Unknown MMC Card  16GB                 | 3         | 0.67%   |
| Toshiba NVMe SSD Drive 512GB           | 3         | 0.67%   |
| Toshiba MQ01ABF050 500GB               | 3         | 0.67%   |
| Toshiba MQ01ABD100 1TB                 | 3         | 0.67%   |
| SK hynix NVMe SSD Drive 512GB          | 3         | 0.67%   |
| Seagate ST9250827AS 250GB              | 3         | 0.67%   |
| Seagate ST500LT012-9WS142 500GB        | 3         | 0.67%   |
| Seagate ST500LM000-1EJ162 500GB        | 3         | 0.67%   |
| Samsung SSD 860 EVO 250GB              | 3         | 0.67%   |
| Samsung SSD 850 EVO 250GB              | 3         | 0.67%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3         | 0.67%   |
| Samsung NVMe SSD Drive 512GB           | 3         | 0.67%   |
| HGST HTS545050A7E380 500GB             | 3         | 0.67%   |
| Crucial CT120BX500SSD1 120GB           | 3         | 0.67%   |
| Unknown                                | 3         | 0.67%   |
| WDC WD3200BPVT-22ZEST0 320GB           | 2         | 0.45%   |
| WDC WD3200BEVT-22ZCT0 320GB            | 2         | 0.45%   |
| WDC WD10SPZX-80Z10T2 1TB               | 2         | 0.45%   |
| WDC WD10JPLX-00MBPT0 1TB               | 2         | 0.45%   |
| WDC WD10JPCX-24UE4T0 1TB               | 2         | 0.45%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB     | 2         | 0.45%   |
| WDC PC SN730 NVMe 512GB                | 2         | 0.45%   |
| Unknown MMC Card  32GB                 | 2         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 60        | 70     | 37.74%  |
| WDC                 | 41        | 47     | 25.79%  |
| Toshiba             | 24        | 36     | 15.09%  |
| Hitachi             | 17        | 17     | 10.69%  |
| HGST                | 11        | 15     | 6.92%   |
| Fujitsu             | 4         | 4      | 2.52%   |
| Samsung Electronics | 1         | 2      | 0.63%   |
| IBM/Hitachi         | 1         | 1      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 35     | 19.25%  |
| Kingston            | 25        | 34     | 15.53%  |
| Patriot             | 15        | 23     | 9.32%   |
| WDC                 | 13        | 15     | 8.07%   |
| SanDisk             | 12        | 15     | 7.45%   |
| Intel               | 11        | 14     | 6.83%   |
| A-DATA Technology   | 11        | 18     | 6.83%   |
| Crucial             | 9         | 12     | 5.59%   |
| Micron Technology   | 5         | 7      | 3.11%   |
| Toshiba             | 3         | 3      | 1.86%   |
| LITEON              | 3         | 3      | 1.86%   |
| Union Memory        | 2         | 2      | 1.24%   |
| Transcend           | 2         | 2      | 1.24%   |
| SK hynix            | 2         | 2      | 1.24%   |
| OCZ                 | 2         | 2      | 1.24%   |
| LITEONIT            | 2         | 2      | 1.24%   |
| Apacer              | 2         | 2      | 1.24%   |
| WDC WDS2            | 1         | 1      | 0.62%   |
| Verbatim            | 1         | 1      | 0.62%   |
| KingSpec            | 1         | 1      | 0.62%   |
| KingDian            | 1         | 3      | 0.62%   |
| Intenso             | 1         | 1      | 0.62%   |
| IM3D                | 1         | 1      | 0.62%   |
| HS-SSD-E100         | 1         | 1      | 0.62%   |
| Hewlett-Packard     | 1         | 1      | 0.62%   |
| Faspeed             | 1         | 1      | 0.62%   |
| China               | 1         | 2      | 0.62%   |
| 2.5                 | 1         | 1      | 0.62%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 152       | 192    | 37.91%  |
| SSD     | 142       | 205    | 35.41%  |
| NVMe    | 76        | 98     | 18.95%  |
| MMC     | 26        | 40     | 6.48%   |
| Unknown | 5         | 5      | 1.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 257       | 387    | 68.72%  |
| NVMe | 76        | 97     | 20.32%  |
| MMC  | 26        | 40     | 6.95%   |
| SAS  | 15        | 16     | 4.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 214       | 311    | 76.43%  |
| 0.51-1.0   | 58        | 74     | 20.71%  |
| 1.01-2.0   | 8         | 12     | 2.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 92        | 25.92%  |
| 251-500        | 74        | 20.85%  |
| 501-1000       | 45        | 12.68%  |
| 1-20           | 38        | 10.7%   |
| 51-100         | 31        | 8.73%   |
| Unknown        | 29        | 8.17%   |
| 21-50          | 23        | 6.48%   |
| 1001-2000      | 17        | 4.79%   |
| More than 3000 | 4         | 1.13%   |
| 2001-3000      | 2         | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 155       | 43.42%  |
| 21-50          | 54        | 15.13%  |
| 51-100         | 40        | 11.2%   |
| 101-250        | 38        | 10.64%  |
| Unknown        | 29        | 8.12%   |
| 251-500        | 24        | 6.72%   |
| 501-1000       | 10        | 2.8%    |
| 1001-2000      | 5         | 1.4%    |
| More than 3000 | 2         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MK7575GSX 752GB                        | 2         | 3      | 4.88%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1         | 1      | 2.44%   |
| WDC WD7500BPVT-80HXZT3 752GB                   | 1         | 1      | 2.44%   |
| WDC WD5000LPVT-24G33T1 500GB                   | 1         | 1      | 2.44%   |
| WDC WD5000BPVT-00HXZT1 500GB                   | 1         | 1      | 2.44%   |
| WDC WD3200BEVT-75ZCT2 320GB                    | 1         | 1      | 2.44%   |
| WDC WD10JPLX-00MBPT0 1TB                       | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 2.44%   |
| Toshiba MK5056GSY 500GB                        | 1         | 1      | 2.44%   |
| Toshiba MK1646GSX 160GB                        | 1         | 2      | 2.44%   |
| Toshiba MK1637GSX 160GB                        | 1         | 1      | 2.44%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB        | 1         | 1      | 2.44%   |
| Seagate ST980811AS 80GB                        | 1         | 1      | 2.44%   |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 2.44%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 2.44%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 2.44%   |
| Seagate ST9120823ASG 120GB                     | 1         | 1      | 2.44%   |
| Seagate ST500LM000-SSHD-8GB                    | 1         | 1      | 2.44%   |
| Seagate ST500LM000-1EJ162 500GB                | 1         | 1      | 2.44%   |
| Seagate ST320LT020-9YG142 320GB                | 1         | 2      | 2.44%   |
| Seagate ST320LT007-9ZV142 320GB                | 1         | 1      | 2.44%   |
| Seagate ST2000LX001-1RG174 2TB                 | 1         | 1      | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 1      | 2.44%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD            | 1         | 1      | 2.44%   |
| SanDisk iSSD P4 8GB                            | 1         | 2      | 2.44%   |
| Samsung Electronics SSD 960 EVO 500GB          | 1         | 1      | 2.44%   |
| Samsung Electronics HS122JC 120GB              | 1         | 2      | 2.44%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 2.44%   |
| Micron Technology 1100 SATA 256GB SSD          | 1         | 1      | 2.44%   |
| Intel SSDSC2CW060A3 64GB                       | 1         | 1      | 2.44%   |
| Intel SSDSC2BF240A5L 240GB                     | 1         | 1      | 2.44%   |
| IM3D L06B B0KB 120GB SSD                       | 1         | 1      | 2.44%   |
| Hitachi HTS723216L9A360 160GB                  | 1         | 1      | 2.44%   |
| Hitachi HTS547575A9E384 752GB                  | 1         | 1      | 2.44%   |
| Hitachi HTS545050A7E380 500GB                  | 1         | 1      | 2.44%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 2.44%   |
| Hitachi HTS543225L9SA00 250GB                  | 1         | 1      | 2.44%   |
| Hitachi HTS543216L9SA02 160GB                  | 1         | 1      | 2.44%   |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 26.83%  |
| Toshiba             | 7         | 9      | 17.07%  |
| WDC                 | 6         | 6      | 14.63%  |
| Hitachi             | 6         | 6      | 14.63%  |
| SanDisk             | 2         | 3      | 4.88%   |
| Samsung Electronics | 2         | 3      | 4.88%   |
| Micron Technology   | 2         | 2      | 4.88%   |
| Intel               | 2         | 2      | 4.88%   |
| SK hynix            | 1         | 1      | 2.44%   |
| IM3D                | 1         | 1      | 2.44%   |
| HGST                | 1         | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 35.48%  |
| Toshiba             | 7         | 9      | 22.58%  |
| Hitachi             | 6         | 6      | 19.35%  |
| WDC                 | 5         | 5      | 16.13%  |
| Samsung Electronics | 1         | 2      | 3.23%   |
| HGST                | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 35     | 75%     |
| SSD  | 8         | 9      | 20%     |
| NVMe | 2         | 2      | 5%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 204       | 296    | 56.35%  |
| Works    | 117       | 197    | 32.32%  |
| Malfunc  | 40        | 46     | 11.05%  |
| Failed   | 1         | 1      | 0.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 237       | 64.58%  |
| AMD                              | 43        | 11.72%  |
| Samsung Electronics              | 23        | 6.27%   |
| SanDisk                          | 21        | 5.72%   |
| SK hynix                         | 10        | 2.72%   |
| Nvidia                           | 7         | 1.91%   |
| Micron Technology                | 7         | 1.91%   |
| Toshiba America Info Systems     | 4         | 1.09%   |
| Silicon Integrated Systems [SiS] | 3         | 0.82%   |
| Phison Electronics               | 3         | 0.82%   |
| Kingston Technology Company      | 3         | 0.82%   |
| KIOXIA                           | 2         | 0.54%   |
| Solid State Storage Technology   | 1         | 0.27%   |
| Silicon Image                    | 1         | 0.27%   |
| Apple                            | 1         | 0.27%   |
| ADATA Technology                 | 1         | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 40        | 9.59%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 28        | 6.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 22        | 5.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 19        | 4.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 16        | 3.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 16        | 3.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 14        | 3.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 14        | 3.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 14        | 3.36%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 14        | 3.36%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 9         | 2.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 9         | 2.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 9         | 2.16%   |
| Micron Non-Volatile memory controller                                                  | 7         | 1.68%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 7         | 1.68%   |
| SanDisk Non-Volatile memory controller                                                 | 6         | 1.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 6         | 1.44%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 6         | 1.44%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 6         | 1.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 6         | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 6         | 1.44%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 6         | 1.44%   |
| AMD SB600 IDE                                                                          | 6         | 1.44%   |
| Samsung NVMe SSD Controller 980                                                        | 5         | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 5         | 1.2%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 5         | 1.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 5         | 1.2%    |
| SK hynix BC501 NVMe Solid State Drive                                                  | 4         | 0.96%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 4         | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 0.96%   |
| Nvidia MCP79 AHCI Controller                                                           | 4         | 0.96%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 4         | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 4         | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 4         | 0.96%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                         | 3         | 0.72%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 3         | 0.72%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 3         | 0.72%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 0.72%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                               | 3         | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 3         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 241       | 61.32%  |
| NVMe | 77        | 19.59%  |
| IDE  | 58        | 14.76%  |
| RAID | 17        | 4.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 270       | 81.08%  |
| AMD    | 63        | 18.92%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 2.4%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 7         | 2.1%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.5%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 5         | 1.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 1.2%    |
| Intel Core i3-5010U CPU @ 2.10GHz             | 4         | 1.2%    |
| Intel Core i3-3217U CPU @ 1.80GHz             | 4         | 1.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.2%    |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 3         | 0.9%    |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 3         | 0.9%    |
| Intel Pentium CPU P6100 @ 2.00GHz             | 3         | 0.9%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.9%    |
| Intel Pentium CPU B960 @ 2.20GHz              | 3         | 0.9%    |
| Intel Pentium CPU 2117U @ 1.80GHz             | 3         | 0.9%    |
| Intel Core i7-9850H CPU @ 2.60GHz             | 3         | 0.9%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 0.9%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 0.9%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 3         | 0.9%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 3         | 0.9%    |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.9%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.9%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.9%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.9%    |
| Intel Core i5-4300M CPU @ 2.60GHz             | 3         | 0.9%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.9%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.9%    |
| Intel Core i3 CPU U 380 @ 1.33GHz             | 3         | 0.9%    |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 3         | 0.9%    |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 3         | 0.9%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 0.9%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.9%    |
| AMD E-450 APU with Radeon HD Graphics         | 3         | 0.9%    |
| AMD Athlon 64 X2 Dual-Core Processor TK-55    | 3         | 0.9%    |
| Intel Pentium M processor 2.13GHz             | 2         | 0.6%    |
| Intel Pentium CPU N3540 @ 2.16GHz             | 2         | 0.6%    |
| Intel Pentium CPU B970 @ 2.30GHz              | 2         | 0.6%    |
| Intel Pentium CPU 4405U @ 2.10GHz             | 2         | 0.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.6%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 75        | 22.52%  |
| Intel Core i7                        | 59        | 17.72%  |
| Intel Core i3                        | 30        | 9.01%   |
| Intel Core 2 Duo                     | 25        | 7.51%   |
| Intel Pentium                        | 23        | 6.91%   |
| Intel Celeron                        | 17        | 5.11%   |
| Other                                | 11        | 3.3%    |
| AMD Ryzen 7                          | 9         | 2.7%    |
| AMD Ryzen 5                          | 9         | 2.7%    |
| Intel Pentium Dual                   | 8         | 2.4%    |
| Intel Atom                           | 7         | 2.1%    |
| Intel Celeron M                      | 4         | 1.2%    |
| AMD E                                | 4         | 1.2%    |
| AMD A8                               | 4         | 1.2%    |
| AMD A6                               | 4         | 1.2%    |
| Intel Pentium Dual-Core              | 3         | 0.9%    |
| Intel Core 2                         | 3         | 0.9%    |
| Intel Celeron Dual-Core              | 3         | 0.9%    |
| AMD Ryzen 9                          | 3         | 0.9%    |
| AMD Ryzen 7 PRO                      | 3         | 0.9%    |
| AMD Athlon 64 X2                     | 3         | 0.9%    |
| Intel Pentium M                      | 2         | 0.6%    |
| Intel Genuine                        | 2         | 0.6%    |
| AMD Turion 64 Mobile                 | 2         | 0.6%    |
| AMD Ryzen 5 PRO                      | 2         | 0.6%    |
| AMD Ryzen 3                          | 2         | 0.6%    |
| AMD E1                               | 2         | 0.6%    |
| AMD Athlon                           | 2         | 0.6%    |
| AMD A4                               | 2         | 0.6%    |
| Intel Pentium Silver                 | 1         | 0.3%    |
| Intel Core 2 Quad                    | 1         | 0.3%    |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.3%    |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.3%    |
| AMD Turion 64 X2 Mobile              | 1         | 0.3%    |
| AMD PRO A10                          | 1         | 0.3%    |
| AMD Mobile Sempron                   | 1         | 0.3%    |
| AMD E2                               | 1         | 0.3%    |
| AMD Athlon II                        | 1         | 0.3%    |
| AMD A10                              | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 198       | 59.46%  |
| 4       | 87        | 26.13%  |
| 6       | 17        | 5.11%   |
| 1       | 16        | 4.8%    |
| 8       | 14        | 4.2%    |
| Unknown | 1         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 333       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 206       | 61.86%  |
| 1       | 126       | 37.84%  |
| Unknown | 1         | 0.3%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 320       | 94.96%  |
| Unknown        | 9         | 2.67%   |
| 32-bit         | 8         | 2.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 15.04%  |
| 0x306a9    | 33        | 9.73%   |
| 0x206a7    | 27        | 7.96%   |
| 0x1067a    | 17        | 5.01%   |
| 0x806ea    | 13        | 3.83%   |
| 0x6fd      | 11        | 3.24%   |
| 0x306c3    | 11        | 3.24%   |
| 0x406e3    | 10        | 2.95%   |
| 0x906ea    | 9         | 2.65%   |
| 0x20655    | 9         | 2.65%   |
| 0x10676    | 9         | 2.65%   |
| 0x806ec    | 8         | 2.36%   |
| 0x806e9    | 8         | 2.36%   |
| 0x806c1    | 7         | 2.06%   |
| 0x40651    | 6         | 1.77%   |
| 0x506e3    | 5         | 1.47%   |
| 0x30678    | 5         | 1.47%   |
| 0x20652    | 5         | 1.47%   |
| 0x506c9    | 4         | 1.18%   |
| 0x306d4    | 4         | 1.18%   |
| 0x0a50000c | 4         | 1.18%   |
| 0x08108102 | 4         | 1.18%   |
| 0x07030105 | 4         | 1.18%   |
| 0x06006705 | 4         | 1.18%   |
| 0x906ed    | 3         | 0.88%   |
| 0x906e9    | 3         | 0.88%   |
| 0x706a8    | 3         | 0.88%   |
| 0x6d8      | 3         | 0.88%   |
| 0x106ca    | 3         | 0.88%   |
| 0x08608103 | 3         | 0.88%   |
| 0x08600106 | 3         | 0.88%   |
| 0x08108109 | 3         | 0.88%   |
| 0x05000119 | 3         | 0.88%   |
| 0xa0652    | 2         | 0.59%   |
| 0x706a1    | 2         | 0.59%   |
| 0x6fb      | 2         | 0.59%   |
| 0x6f6      | 2         | 0.59%   |
| 0x6f2      | 2         | 0.59%   |
| 0x6ec      | 2         | 0.59%   |
| 0x6e8      | 2         | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 49        | 14.71%  |
| IvyBridge       | 37        | 11.11%  |
| SandyBridge     | 30        | 9.01%   |
| Penryn          | 26        | 7.81%   |
| Haswell         | 24        | 7.21%   |
| Core            | 21        | 6.31%   |
| Skylake         | 17        | 5.11%   |
| Westmere        | 16        | 4.8%    |
| Silvermont      | 10        | 3%      |
| K8 Hammer       | 8         | 2.4%    |
| Excavator       | 8         | 2.4%    |
| Unknown         | 8         | 2.4%    |
| Zen+            | 7         | 2.1%    |
| Zen 3           | 7         | 2.1%    |
| TigerLake       | 7         | 2.1%    |
| P6              | 7         | 2.1%    |
| Zen 2           | 6         | 1.8%    |
| Broadwell       | 6         | 1.8%    |
| Goldmont plus   | 5         | 1.5%    |
| Bonnell         | 5         | 1.5%    |
| Puma            | 4         | 1.2%    |
| Goldmont        | 4         | 1.2%    |
| Bobcat          | 4         | 1.2%    |
| Piledriver      | 3         | 0.9%    |
| K8 & K10 hybrid | 3         | 0.9%    |
| CometLake       | 3         | 0.9%    |
| Zen             | 2         | 0.6%    |
| IceLake         | 2         | 0.6%    |
| Nehalem         | 1         | 0.3%    |
| K10 Llano       | 1         | 0.3%    |
| K10             | 1         | 0.3%    |
| Jaguar          | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 230       | 54.89%  |
| Nvidia                           | 104       | 24.82%  |
| AMD                              | 83        | 19.81%  |
| Silicon Integrated Systems [SiS] | 2         | 0.48%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 34        | 7.66%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 5.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 15        | 3.38%   |
| Intel UHD Graphics 620                                                                   | 13        | 2.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 2.93%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 2.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 2.48%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 2.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 2.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.03%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 1.58%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 1.58%   |
| Intel HD Graphics 620                                                                    | 7         | 1.58%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.58%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 1.58%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 1.58%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 1.35%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 6         | 1.35%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 1.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.35%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 1.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.13%   |
| AMD Renoir                                                                               | 5         | 1.13%   |
| Nvidia GK208M [GeForce GT 720M]                                                          | 4         | 0.9%    |
| Intel HD Graphics 530                                                                    | 4         | 0.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.9%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 0.9%    |
| AMD Lucienne                                                                             | 4         | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.68%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 3         | 0.68%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.68%   |
| Intel HD Graphics 630                                                                    | 3         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.68%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.68%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 3         | 0.68%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 0.68%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 152       | 45.37%  |
| Intel + Nvidia | 66        | 19.7%   |
| 1 x AMD        | 55        | 16.42%  |
| 1 x Nvidia     | 32        | 9.55%   |
| Intel + AMD    | 14        | 4.18%   |
| 2 x AMD        | 8         | 2.39%   |
| AMD + Nvidia   | 6         | 1.79%   |
| 1 x SiS        | 2         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 288       | 85.71%  |
| Proprietary | 38        | 11.31%  |
| Unknown     | 10        | 2.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 161       | 47.63%  |
| 0.01-0.5   | 68        | 20.12%  |
| 1.01-2.0   | 57        | 16.86%  |
| 0.51-1.0   | 26        | 7.69%   |
| 3.01-4.0   | 18        | 5.33%   |
| 2.01-3.0   | 4         | 1.18%   |
| 5.01-6.0   | 3         | 0.89%   |
| 7.01-8.0   | 1         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 71        | 19.03%  |
| LG Display              | 59        | 15.82%  |
| Samsung Electronics     | 47        | 12.6%   |
| Chimei Innolux          | 43        | 11.53%  |
| BOE                     | 35        | 9.38%   |
| Chi Mei Optoelectronics | 23        | 6.17%   |
| Lenovo                  | 12        | 3.22%   |
| Dell                    | 11        | 2.95%   |
| Philips                 | 8         | 2.14%   |
| PANDA                   | 7         | 1.88%   |
| LG Philips              | 7         | 1.88%   |
| Sharp                   | 6         | 1.61%   |
| Hewlett-Packard         | 5         | 1.34%   |
| Apple                   | 5         | 1.34%   |
| Acer                    | 4         | 1.07%   |
| AOC                     | 3         | 0.8%    |
| HannStar                | 2         | 0.54%   |
| Goldstar                | 2         | 0.54%   |
| CSO                     | 2         | 0.54%   |
| CPT                     | 2         | 0.54%   |
| ANX                     | 2         | 0.54%   |
| Ancor Communications    | 2         | 0.54%   |
| ViewSonic               | 1         | 0.27%   |
| TMX                     | 1         | 0.27%   |
| Sony                    | 1         | 0.27%   |
| Seiko/Epson             | 1         | 0.27%   |
| Quanta Display          | 1         | 0.27%   |
| Plain Tree Systems      | 1         | 0.27%   |
| Panasonic               | 1         | 0.27%   |
| LGD                     | 1         | 0.27%   |
| JDI                     | 1         | 0.27%   |
| InnoLux Display         | 1         | 0.27%   |
| InfoVision              | 1         | 0.27%   |
| Iiyama                  | 1         | 0.27%   |
| Fujitsu Siemens         | 1         | 0.27%   |
| BenQ                    | 1         | 0.27%   |
| ASUSTek Computer        | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch           | 6         | 1.59%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 6         | 1.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 5         | 1.33%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 4         | 1.06%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch  | 4         | 1.06%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch      | 3         | 0.8%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 0.8%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 3         | 0.8%    |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 3         | 0.8%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 3         | 0.8%    |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch            | 3         | 0.8%    |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 3         | 0.8%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch      | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch      | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3859 1366x768 293x165mm 13.2-inch      | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch      | 2         | 0.53%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                   | 2         | 0.53%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch               | 2         | 0.53%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch               | 2         | 0.53%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch               | 2         | 0.53%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch               | 2         | 0.53%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 0.53%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch               | 2         | 0.53%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch               | 2         | 0.53%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 600x340mm 27.2-inch                  | 2         | 0.53%   |
| Lenovo LCD Monitor LEN40E0 1366x768 277x156mm 12.5-inch                   | 2         | 0.53%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                   | 2         | 0.53%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                     | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14F5 1920x1080 309x173mm 13.9-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 2         | 0.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO1726 1920x1080 382x215mm 17.3-inch | 2         | 0.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch  | 2         | 0.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO1554 1280x800 331x207mm 15.4-inch  | 2         | 0.53%   |
| BOE LCD Monitor BOE07F1 1920x1080 344x193mm 15.5-inch                     | 2         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 125       | 35.31%  |
| 1366x768 (WXGA)    | 114       | 32.2%   |
| 1280x800 (WXGA)    | 31        | 8.76%   |
| 1600x900 (HD+)     | 21        | 5.93%   |
| 2560x1440 (QHD)    | 11        | 3.11%   |
| 1440x900 (WXGA+)   | 11        | 3.11%   |
| 3840x2160 (4K)     | 8         | 2.26%   |
| 1680x1050 (WSXGA+) | 7         | 1.98%   |
| 1920x1200 (WUXGA)  | 5         | 1.41%   |
| 1024x600           | 4         | 1.13%   |
| 3440x1440          | 3         | 0.85%   |
| 2880x1800          | 3         | 0.85%   |
| 800x1280           | 2         | 0.56%   |
| 2560x1600          | 2         | 0.56%   |
| 3200x1800 (QHD+)   | 1         | 0.28%   |
| 2560x1080          | 1         | 0.28%   |
| 2160x1440          | 1         | 0.28%   |
| 1680x945           | 1         | 0.28%   |
| 1280x720 (HD)      | 1         | 0.28%   |
| 1280x1024 (SXGA)   | 1         | 0.28%   |
| 1024x768 (XGA)     | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 179       | 47.86%  |
| 14      | 41        | 10.96%  |
| 13      | 39        | 10.43%  |
| 17      | 19        | 5.08%   |
| 24      | 13        | 3.48%   |
| 12      | 12        | 3.21%   |
| 23      | 10        | 2.67%   |
| 27      | 8         | 2.14%   |
| 18      | 8         | 2.14%   |
| 11      | 8         | 2.14%   |
| 22      | 6         | 1.6%    |
| Unknown | 6         | 1.6%    |
| 34      | 4         | 1.07%   |
| 10      | 4         | 1.07%   |
| 31      | 3         | 0.8%    |
| 21      | 3         | 0.8%    |
| 20      | 2         | 0.53%   |
| 19      | 2         | 0.53%   |
| 84      | 1         | 0.27%   |
| 54      | 1         | 0.27%   |
| 50      | 1         | 0.27%   |
| 40      | 1         | 0.27%   |
| 33      | 1         | 0.27%   |
| 25      | 1         | 0.27%   |
| 16      | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 237       | 63.88%  |
| 201-300     | 43        | 11.59%  |
| 501-600     | 28        | 7.55%   |
| 351-400     | 24        | 6.47%   |
| 401-500     | 20        | 5.39%   |
| Unknown     | 6         | 1.62%   |
| 701-800     | 5         | 1.35%   |
| 601-700     | 4         | 1.08%   |
| 1001-1500   | 2         | 0.54%   |
| 801-900     | 1         | 0.27%   |
| 1501-2000   | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 266       | 78.7%   |
| 16/10   | 58        | 17.16%  |
| 21/9    | 4         | 1.18%   |
| 3/2     | 3         | 0.89%   |
| Unknown | 3         | 0.89%   |
| 0.62    | 2         | 0.59%   |
| 5/4     | 1         | 0.3%    |
| 4/3     | 1         | 0.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 177       | 47.58%  |
| 81-90          | 64        | 17.2%   |
| 201-250        | 27        | 7.26%   |
| 71-80          | 16        | 4.3%    |
| 121-130        | 13        | 3.49%   |
| 61-70          | 12        | 3.23%   |
| 51-60          | 8         | 2.15%   |
| 351-500        | 8         | 2.15%   |
| 301-350        | 8         | 2.15%   |
| 141-150        | 7         | 1.88%   |
| 151-200        | 6         | 1.61%   |
| Unknown        | 6         | 1.61%   |
| 131-140        | 5         | 1.34%   |
| 41-50          | 4         | 1.08%   |
| 251-300        | 4         | 1.08%   |
| More than 1000 | 3         | 0.81%   |
| 91-100         | 2         | 0.54%   |
| 111-120        | 1         | 0.27%   |
| 501-1000       | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 134       | 36.71%  |
| 101-120       | 110       | 30.14%  |
| 51-100        | 90        | 24.66%  |
| 161-240       | 13        | 3.56%   |
| More than 240 | 9         | 2.47%   |
| Unknown       | 6         | 1.64%   |
| 1-50          | 3         | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 265       | 78.87%  |
| 2     | 58        | 17.26%  |
| 0     | 10        | 2.98%   |
| 3     | 3         | 0.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 170       | 30.3%   |
| Intel                             | 170       | 30.3%   |
| Qualcomm Atheros                  | 100       | 17.83%  |
| Broadcom                          | 39        | 6.95%   |
| Marvell Technology Group          | 13        | 2.32%   |
| Ralink                            | 10        | 1.78%   |
| Broadcom Limited                  | 9         | 1.6%    |
| Nvidia                            | 6         | 1.07%   |
| MediaTek                          | 5         | 0.89%   |
| Xiaomi                            | 3         | 0.53%   |
| Sierra Wireless                   | 3         | 0.53%   |
| Ralink Technology                 | 3         | 0.53%   |
| Qualcomm Atheros Communications   | 3         | 0.53%   |
| Hewlett-Packard                   | 3         | 0.53%   |
| Ericsson Business Mobile Networks | 3         | 0.53%   |
| DisplayLink                       | 3         | 0.53%   |
| TP-Link                           | 2         | 0.36%   |
| Lenovo                            | 2         | 0.36%   |
| JMicron Technology                | 2         | 0.36%   |
| Huawei Technologies               | 2         | 0.36%   |
| Fibocom                           | 2         | 0.36%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.18%   |
| T & A Mobile Phones               | 1         | 0.18%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.18%   |
| Sigma Sport                       | 1         | 0.18%   |
| Nokia Mobile Phones               | 1         | 0.18%   |
| D-Link                            | 1         | 0.18%   |
| Attansic Technology               | 1         | 0.18%   |
| ASIX Electronics                  | 1         | 0.18%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 103       | 15.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 33        | 4.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 27        | 4.08%   |
| Intel Wireless 8265 / 8275                                              | 17        | 2.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 15        | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 2.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 11        | 1.66%   |
| Intel Wireless 7260                                                     | 11        | 1.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 1.51%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 1.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 1.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.21%   |
| Intel Wireless 8260                                                     | 8         | 1.21%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 1.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.21%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 7         | 1.06%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 1.06%   |
| Intel Wireless 7265                                                     | 7         | 1.06%   |
| Intel Wireless 3165                                                     | 7         | 1.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.91%   |
| Intel WiFi Link 5100                                                    | 6         | 0.91%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 0.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 0.91%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 0.91%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.76%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 5         | 0.76%   |
| Intel Wireless-AC 9260                                                  | 5         | 0.76%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 0.76%   |
| Intel Ethernet Connection (7) I219-LM                                   | 5         | 0.76%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.76%   |
| Intel 82567LM Gigabit Network Connection                                | 5         | 0.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 4         | 0.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 159       | 46.49%  |
| Qualcomm Atheros                | 83        | 24.27%  |
| Realtek Semiconductor           | 37        | 10.82%  |
| Broadcom                        | 28        | 8.19%   |
| Ralink                          | 10        | 2.92%   |
| Broadcom Limited                | 7         | 2.05%   |
| MediaTek                        | 5         | 1.46%   |
| Sierra Wireless                 | 3         | 0.88%   |
| Ralink Technology               | 3         | 0.88%   |
| Qualcomm Atheros Communications | 3         | 0.88%   |
| TP-Link                         | 2         | 0.58%   |
| Fibocom                         | 2         | 0.58%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 27        | 7.87%   |
| Intel Wireless 8265 / 8275                                              | 17        | 4.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 4.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 4.08%   |
| Intel Wireless 7260                                                     | 11        | 3.21%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 2.92%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 2.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 2.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 2.33%   |
| Intel Wireless 8260                                                     | 8         | 2.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 2.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 2.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 2.04%   |
| Intel Wireless 7265                                                     | 7         | 2.04%   |
| Intel Wireless 3165                                                     | 7         | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.75%   |
| Intel WiFi Link 5100                                                    | 6         | 1.75%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.75%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 1.75%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.46%   |
| Intel Wireless-AC 9260                                                  | 5         | 1.46%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.46%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 1.17%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 1.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.17%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 1.17%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.17%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.17%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.17%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 1.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.87%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 3         | 0.87%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 3         | 0.87%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 0.87%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 0.87%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 155       | 51.32%  |
| Intel                    | 71        | 23.51%  |
| Qualcomm Atheros         | 26        | 8.61%   |
| Marvell Technology Group | 13        | 4.3%    |
| Broadcom                 | 13        | 4.3%    |
| Nvidia                   | 6         | 1.99%   |
| Xiaomi                   | 3         | 0.99%   |
| DisplayLink              | 3         | 0.99%   |
| Lenovo                   | 2         | 0.66%   |
| JMicron Technology       | 2         | 0.66%   |
| Broadcom Limited         | 2         | 0.66%   |
| T & A Mobile Phones      | 1         | 0.33%   |
| Nokia Mobile Phones      | 1         | 0.33%   |
| Huawei Technologies      | 1         | 0.33%   |
| D-Link                   | 1         | 0.33%   |
| Attansic Technology      | 1         | 0.33%   |
| ASIX Electronics         | 1         | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 103       | 33.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33        | 10.82%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 4.92%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 3.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7         | 2.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.64%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 5         | 1.64%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.64%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 1.64%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 1.64%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 1.31%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 4         | 1.31%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.31%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.31%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.31%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.98%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.98%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.98%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.98%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.98%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.98%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.98%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.98%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.66%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 0.66%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.66%   |
| Nvidia MCP77 Ethernet                                             | 2         | 0.66%   |
| Lenovo USB-C Dock Ethernet                                        | 2         | 0.66%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.66%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.66%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.66%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.66%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.66%   |
| DisplayLink USB-C Dual-4K Dock                                    | 2         | 0.66%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 0.66%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 2         | 0.66%   |
| T & A Mobile Phones ALCATEL ONETOUCH PIXI 3 (4)                   | 1         | 0.33%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 329       | 52.06%  |
| Ethernet | 290       | 45.89%  |
| Modem    | 13        | 2.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 269       | 76.42%  |
| Ethernet | 83        | 23.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 272       | 81.68%  |
| 1     | 53        | 15.92%  |
| 0     | 6         | 1.8%    |
| 3     | 2         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 316       | 94.61%  |
| Yes  | 18        | 5.39%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 96        | 38.87%  |
| IMC Networks                    | 22        | 8.91%   |
| Qualcomm Atheros Communications | 21        | 8.5%    |
| Broadcom                        | 20        | 8.1%    |
| Realtek Semiconductor           | 17        | 6.88%   |
| Lite-On Technology              | 12        | 4.86%   |
| Foxconn / Hon Hai               | 10        | 4.05%   |
| Ralink                          | 7         | 2.83%   |
| Hewlett-Packard                 | 7         | 2.83%   |
| Dell                            | 7         | 2.83%   |
| ASUSTek Computer                | 7         | 2.83%   |
| Toshiba                         | 5         | 2.02%   |
| Cambridge Silicon Radio         | 5         | 2.02%   |
| Foxconn International           | 3         | 1.21%   |
| Apple                           | 3         | 1.21%   |
| Taiyo Yuden                     | 2         | 0.81%   |
| Realtek                         | 1         | 0.4%    |
| Micro Star International        | 1         | 0.4%    |
| Alps Electric                   | 1         | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 48        | 19.43%  |
| Intel AX201 Bluetooth                               | 14        | 5.67%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 13        | 5.26%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 10        | 4.05%   |
| Intel AX200 Bluetooth                               | 10        | 4.05%   |
| Realtek Bluetooth Radio                             | 9         | 3.64%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 8         | 3.24%   |
| Ralink RT3290 Bluetooth                             | 7         | 2.83%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 7         | 2.83%   |
| IMC Networks Bluetooth Radio                        | 6         | 2.43%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 2.02%   |
| Lite-On Bluetooth Device                            | 5         | 2.02%   |
| IMC Networks Bluetooth Device                       | 5         | 2.02%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 2.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 2.02%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 5         | 2.02%   |
| Realtek RTL8821A Bluetooth                          | 4         | 1.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 1.62%   |
| Broadcom HP Portable SoftSailing                    | 4         | 1.62%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 1.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.21%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.21%   |
| IMC Networks Wireless_Device                        | 3         | 1.21%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.21%   |
| Dell Wireless 370 Bluetooth Mini-card               | 3         | 1.21%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 0.81%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 2         | 0.81%   |
| Intel AX210 Bluetooth                               | 2         | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.81%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 2         | 0.81%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.81%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.81%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.81%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.4%    |
| Toshiba Bluetooth Device                            | 1         | 0.4%    |
| Toshiba Askey Bluetooth Module                      | 1         | 0.4%    |
| Realtek RTL8723B Bluetooth                          | 1         | 0.4%    |
| Realtek Bluetooth Radio                             | 1         | 0.4%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.4%    |
| Qualcomm Atheros Bluetooth                          | 1         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 260       | 64.04%  |
| AMD                              | 73        | 17.98%  |
| Nvidia                           | 47        | 11.58%  |
| C-Media Electronics              | 4         | 0.99%   |
| Silicon Integrated Systems [SiS] | 3         | 0.74%   |
| GN Netcom                        | 3         | 0.74%   |
| Samson Technologies              | 2         | 0.49%   |
| Lenovo                           | 2         | 0.49%   |
| JMTek                            | 2         | 0.49%   |
| Trust                            | 1         | 0.25%   |
| Textech International            | 1         | 0.25%   |
| Texas Instruments                | 1         | 0.25%   |
| Realtek Semiconductor            | 1         | 0.25%   |
| Plantronics                      | 1         | 0.25%   |
| Logitech                         | 1         | 0.25%   |
| Hewlett-Packard                  | 1         | 0.25%   |
| Focusrite-Novation               | 1         | 0.25%   |
| Behringer.......                 | 1         | 0.25%   |
| AKAI Professional M.I.           | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 45        | 9.36%   |
| Intel Sunrise Point-LP HD Audio                                            | 33        | 6.86%   |
| AMD Family 17h/19h HD Audio Controller                                     | 27        | 5.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 22        | 4.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 19        | 3.95%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 18        | 3.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 3.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 17        | 3.53%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 15        | 3.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14        | 2.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 13        | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 12        | 2.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 2.29%   |
| AMD FCH Azalia Controller                                                  | 10        | 2.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 1.87%   |
| Nvidia GF108 High Definition Audio Controller                              | 8         | 1.66%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 8         | 1.66%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 1.46%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.46%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 1.46%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.46%   |
| AMD High Definition Audio Controller                                       | 7         | 1.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 1.25%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 6         | 1.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6         | 1.25%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 1.04%   |
| Nvidia MCP79 High Definition Audio                                         | 4         | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 0.83%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 0.83%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.62%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.62%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.62%   |
| Intel CM238 HD Audio Controller                                            | 3         | 0.62%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller           | 3         | 0.62%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 0.62%   |
| AMD Trinity HDMI Audio Controller                                          | 3         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 54        | 23.89%  |
| SK hynix            | 50        | 22.12%  |
| Kingston            | 30        | 13.27%  |
| Unknown             | 26        | 11.5%   |
| Micron Technology   | 26        | 11.5%   |
| Ramaxel Technology  | 6         | 2.65%   |
| Elpida              | 6         | 2.65%   |
| Crucial             | 6         | 2.65%   |
| Unknown (ABCD)      | 4         | 1.77%   |
| Patriot             | 3         | 1.33%   |
| Corsair             | 3         | 1.33%   |
| A-DATA Technology   | 3         | 1.33%   |
| Nanya Technology    | 2         | 0.88%   |
| Unigen              | 1         | 0.44%   |
| SHARETRONIC         | 1         | 0.44%   |
| Atermiter           | 1         | 0.44%   |
| ASint Technology    | 1         | 0.44%   |
| Apacer              | 1         | 0.44%   |
| 48spaces            | 1         | 0.44%   |
| Unknown             | 1         | 0.44%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 6         | 2.45%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 1.63%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 1.63%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.63%   |
| Micron RAM MT8KTF51264HZ-1G6 4GB SODIMM DDR3 1600MT/s            | 4         | 1.63%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.22%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.22%   |
| Patriot RAM PSD34G16002S 4GB SODIMM DDR3 1600MT/s                | 3         | 1.22%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 3         | 1.22%   |
| Kingston RAM KHX1866C11S3L/8G 8GB SODIMM DDR3 1867MT/s           | 3         | 1.22%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.82%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.82%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 2         | 0.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.82%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 2         | 0.82%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.82%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.82%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.82%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.82%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s            | 2         | 0.82%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.82%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.82%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.82%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 0.82%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.82%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR 2048MT/s            | 2         | 0.82%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 2         | 0.82%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.82%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s           | 2         | 0.82%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s            | 2         | 0.82%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 2         | 0.82%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s          | 2         | 0.82%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.41%   |
| Unknown RAM Module 4GB SODIMM 800MT/s                            | 1         | 0.41%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.41%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                     | 1         | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 71        | 39.66%  |
| DDR4    | 58        | 32.4%   |
| DDR2    | 19        | 10.61%  |
| LPDDR4  | 10        | 5.59%   |
| SDRAM   | 8         | 4.47%   |
| Unknown | 5         | 2.79%   |
| LPDDR3  | 4         | 2.23%   |
| DDR     | 2         | 1.12%   |
| LPDDR5  | 1         | 0.56%   |
| DRAM    | 1         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 167       | 92.78%  |
| Row Of Chips | 9         | 5%      |
| Chip         | 3         | 1.67%   |
| DIMM         | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 63        | 30.58%  |
| 8192  | 60        | 29.13%  |
| 2048  | 42        | 20.39%  |
| 16384 | 22        | 10.68%  |
| 1024  | 16        | 7.77%   |
| 512   | 2         | 0.97%   |
| 32768 | 1         | 0.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 51        | 25.37%  |
| 2667    | 28        | 13.93%  |
| 3200    | 19        | 9.45%   |
| 667     | 15        | 7.46%   |
| 2400    | 13        | 6.47%   |
| 2133    | 12        | 5.97%   |
| 1333    | 10        | 4.98%   |
| 1334    | 9         | 4.48%   |
| Unknown | 8         | 3.98%   |
| 2048    | 5         | 2.49%   |
| 800     | 5         | 2.49%   |
| 1067    | 4         | 1.99%   |
| 4199    | 3         | 1.49%   |
| 1867    | 3         | 1.49%   |
| 8400    | 2         | 1%      |
| 4267    | 2         | 1%      |
| 4266    | 2         | 1%      |
| 3266    | 2         | 1%      |
| 533     | 2         | 1%      |
| 6400    | 1         | 0.5%    |
| 4800    | 1         | 0.5%    |
| 1639    | 1         | 0.5%    |
| 1066    | 1         | 0.5%    |
| 975     | 1         | 0.5%    |
| 333     | 1         | 0.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 1         | 33.33%  |
| Lexmark International | 1         | 33.33%  |
| Hewlett-Packard       | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Samsung M2070 Series              | 1         | 33.33%  |
| Lexmark International 2600 Series | 1         | 33.33%  |
| HP LaserJet CP 1025               | 1         | 33.33%  |

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
| Chicony Electronics                    | 97        | 34.4%   |
| IMC Networks                           | 27        | 9.57%   |
| Realtek Semiconductor                  | 24        | 8.51%   |
| Acer                                   | 24        | 8.51%   |
| Microdia                               | 21        | 7.45%   |
| Sunplus Innovation Technology          | 16        | 5.67%   |
| Suyin                                  | 13        | 4.61%   |
| Syntek                                 | 10        | 3.55%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 3.19%   |
| Quanta                                 | 6         | 2.13%   |
| Lite-On Technology                     | 5         | 1.77%   |
| Ricoh                                  | 3         | 1.06%   |
| Logitech                               | 3         | 1.06%   |
| Alcor Micro                            | 3         | 1.06%   |
| Silicon Motion                         | 2         | 0.71%   |
| Samsung Electronics                    | 2         | 0.71%   |
| Luxvisions Innotech Limited            | 2         | 0.71%   |
| GEMBIRD                                | 2         | 0.71%   |
| Apple                                  | 2         | 0.71%   |
| Z-Star Microelectronics                | 1         | 0.35%   |
| USB Camera                             | 1         | 0.35%   |
| Tripath Technology                     | 1         | 0.35%   |
| SN0002                                 | 1         | 0.35%   |
| Primax Electronics                     | 1         | 0.35%   |
| OmniVision Technologies                | 1         | 0.35%   |
| LG Electronics                         | 1         | 0.35%   |
| Lenovo                                 | 1         | 0.35%   |
| Importek                               | 1         | 0.35%   |
| Elecom                                 | 1         | 0.35%   |
| ALi                                    | 1         | 0.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 23        | 8.13%   |
| Microdia Integrated_Webcam_HD            | 11        | 3.89%   |
| Realtek USB2.0 HD UVC WebCam             | 7         | 2.47%   |
| IMC Networks Integrated Camera           | 7         | 2.47%   |
| Chicony HD WebCam                        | 7         | 2.47%   |
| Sunplus Integrated_Webcam_HD             | 6         | 2.12%   |
| Chicony HP HD Webcam [Fixed]             | 6         | 2.12%   |
| Acer Lenovo EasyCamera                   | 6         | 2.12%   |
| Realtek Integrated_Webcam_HD             | 5         | 1.77%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 5         | 1.77%   |
| Acer EasyCamera                          | 5         | 1.77%   |
| Syntek Integrated Camera                 | 4         | 1.41%   |
| Quanta HP HD Camera                      | 4         | 1.41%   |
| Microdia Integrated Webcam               | 4         | 1.41%   |
| Lite-On HP HD Camera                     | 4         | 1.41%   |
| Chicony USB2.0 VGA UVC WebCam            | 4         | 1.41%   |
| Chicony USB 2.0 Camera                   | 4         | 1.41%   |
| Acer Integrated Camera                   | 4         | 1.41%   |
| Syntek Lenovo EasyCamera                 | 3         | 1.06%   |
| Suyin HP Webcam                          | 3         | 1.06%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 3         | 1.06%   |
| Sunplus HP HD Webcam [Fixed]             | 3         | 1.06%   |
| IMC Networks USB2.0 HD UVC WebCam        | 3         | 1.06%   |
| IMC Networks Integrated Webcam           | 3         | 1.06%   |
| Chicony USB2.0 HD UVC WebCam             | 3         | 1.06%   |
| Chicony USB2.0 0.3M UVC WebCam           | 3         | 1.06%   |
| Chicony TOSHIBA Web Camera - HD          | 3         | 1.06%   |
| Chicony Thinkpad T430 camera             | 3         | 1.06%   |
| Chicony Lenovo EasyCamera                | 3         | 1.06%   |
| Chicony HP HD Camera                     | 3         | 1.06%   |
| Chicony CNF9055 Toshiba Webcam           | 3         | 1.06%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 3         | 1.06%   |
| Acer Lenovo Integrated Webcam            | 3         | 1.06%   |
| Syntek EasyCamera                        | 2         | 0.71%   |
| Suyin Sony Visual Communication Camera   | 2         | 0.71%   |
| Sunplus HD WebCam                        | 2         | 0.71%   |
| Samsung Galaxy series, misc. (MTP mode)  | 2         | 0.71%   |
| Ricoh Integrated Webcam                  | 2         | 0.71%   |
| Realtek Lenovo EasyCamera                | 2         | 0.71%   |
| Realtek HD WebCam                        | 2         | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 36        | 51.43%  |
| Synaptics                  | 15        | 21.43%  |
| AuthenTec                  | 7         | 10%     |
| LighTuning Technology      | 4         | 5.71%   |
| Shenzhen Goodix Technology | 3         | 4.29%   |
| STMicroelectronics         | 2         | 2.86%   |
| Elan Microelectronics      | 2         | 2.86%   |
| Upek                       | 1         | 1.43%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 14.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 7.14%   |
| Validity Sensors VFS491                                                    | 4         | 5.71%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 5.71%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 5.71%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 5.71%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 5.71%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 4.29%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 4.29%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 2.86%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 2.86%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.86%   |
| Synaptics  WBDI                                                            | 2         | 2.86%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 2.86%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 2.86%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.86%   |
| AuthenTec AES2810                                                          | 2         | 2.86%   |
| Unknown                                                                    | 2         | 2.86%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.43%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 1.43%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.43%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.43%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.43%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.43%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.43%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.43%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.43%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.43%   |
| AuthenTec AES1600                                                          | 1         | 1.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 14        | 41.18%  |
| Alcor Micro | 11        | 32.35%  |
| O2 Micro    | 5         | 14.71%  |
| Lenovo      | 2         | 5.88%   |
| BIT4ID      | 2         | 5.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 32.35%  |
| Broadcom 5880                                                                | 5         | 14.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 11.76%  |
| Broadcom 58200                                                               | 4         | 11.76%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 8.82%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 5.88%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.88%   |
| BIT4ID miniLector EVO                                                        | 2         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.94%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 188       | 55.46%  |
| 1     | 121       | 35.69%  |
| 2     | 24        | 7.08%   |
| 3     | 5         | 1.47%   |
| 4     | 1         | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 70        | 38.46%  |
| Graphics card            | 29        | 15.93%  |
| Chipcard                 | 27        | 14.84%  |
| Bluetooth                | 9         | 4.95%   |
| Storage                  | 8         | 4.4%    |
| Net/wireless             | 8         | 4.4%    |
| Multimedia controller    | 8         | 4.4%    |
| Modem                    | 6         | 3.3%    |
| Communication controller | 5         | 2.75%   |
| Card reader              | 3         | 1.65%   |
| Camera                   | 3         | 1.65%   |
| Network                  | 2         | 1.1%    |
| Flash memory             | 2         | 1.1%    |
| Storage/ide              | 1         | 0.55%   |
| Sound                    | 1         | 0.55%   |

