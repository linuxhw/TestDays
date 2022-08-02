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

Total: 492

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| MSI           | GT60 2OC/2OD                | [954fdc5841](https://linux-hardware.org/?probe=954fdc5841) | May 06, 2022 |
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

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 51        | 15.32%  |
| Ubuntu 18.04       | 38        | 11.41%  |
| BlackPanther 18.1  | 27        | 8.11%   |
| OpenMandriva 4.2   | 12        | 3.6%    |
| OpenMandriva 4.3   | 9         | 2.7%    |
| ROSA R10           | 8         | 2.4%    |
| Linux Mint 20.3    | 8         | 2.4%    |
| Linux Mint 19.3    | 8         | 2.4%    |
| Linux Mint 20.1    | 7         | 2.1%    |
| Fedora 34          | 7         | 2.1%    |
| Arch Rolling       | 7         | 2.1%    |
| Xubuntu 18.04      | 6         | 1.8%    |
| Ubuntu 19.04       | 6         | 1.8%    |
| MX 19              | 6         | 1.8%    |
| Ubuntu 20.10       | 5         | 1.5%    |
| Pop!_OS 20.10      | 5         | 1.5%    |
| Linux Mint 20.2    | 5         | 1.5%    |
| Zorin 15           | 4         | 1.2%    |
| ROSA R11.1         | 4         | 1.2%    |
| Pop!_OS 21.10      | 4         | 1.2%    |
| Linux Mint 19.1    | 4         | 1.2%    |
| Fedora 32          | 4         | 1.2%    |
| Fedora 31          | 4         | 1.2%    |
| Debian 10          | 4         | 1.2%    |
| Xubuntu 20.04      | 3         | 0.9%    |
| Manjaro            | 3         | 0.9%    |
| Linux Mint 19.2    | 3         | 0.9%    |
| KDE neon 20.04     | 3         | 0.9%    |
| Fedora 33          | 3         | 0.9%    |
| Debian 11          | 3         | 0.9%    |
| Arch               | 3         | 0.9%    |
| Zorin 12           | 2         | 0.6%    |
| Xubuntu 18.10      | 2         | 0.6%    |
| Ubuntu 21.04       | 2         | 0.6%    |
| Ubuntu 19.10       | 2         | 0.6%    |
| Ubuntu 18.10       | 2         | 0.6%    |
| Ubuntu 16.04       | 2         | 0.6%    |
| MX 18              | 2         | 0.6%    |
| Linux Mint 20      | 2         | 0.6%    |
| Fedora 36          | 2         | 0.6%    |
| Fedora 35          | 2         | 0.6%    |
| ArcoLinux Rolling  | 2         | 0.6%    |
| Zorin 16           | 1         | 0.3%    |
| Ubuntu MATE 20.04  | 1         | 0.3%    |
| Ubuntu MATE 18.04  | 1         | 0.3%    |
| Ubuntu 22.04       | 1         | 0.3%    |
| Ubuntu 21.10       | 1         | 0.3%    |
| Ubuntu             | 1         | 0.3%    |
| SteamOS 3.2        | 1         | 0.3%    |
| ROSA R9            | 1         | 0.3%    |
| ROSA R8.1          | 1         | 0.3%    |
| ROSA R11           | 1         | 0.3%    |
| Rocky Linux 8.5    | 1         | 0.3%    |
| Pop!_OS 20.04      | 1         | 0.3%    |
| openSUSE Leap-15.1 | 1         | 0.3%    |
| MX 21              | 1         | 0.3%    |
| MX 20              | 1         | 0.3%    |
| Manjaro 21.2.5     | 1         | 0.3%    |
| Manjaro 21.1.4     | 1         | 0.3%    |
| Manjaro 20.2.1     | 1         | 0.3%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 107       | 33.65%  |
| Linux Mint   | 33        | 10.38%  |
| BlackPanther | 28        | 8.81%   |
| Fedora       | 23        | 7.23%   |
| OpenMandriva | 21        | 6.6%    |
| ROSA         | 14        | 4.4%    |
| Xubuntu      | 11        | 3.46%   |
| Pop!_OS      | 10        | 3.14%   |
| Arch         | 10        | 3.14%   |
| Manjaro      | 8         | 2.52%   |
| Debian       | 8         | 2.52%   |
| Zorin        | 7         | 2.2%    |
| MX           | 7         | 2.2%    |
| Kubuntu      | 6         | 1.89%   |
| KDE neon     | 3         | 0.94%   |
| Endless      | 3         | 0.94%   |
| Ubuntu MATE  | 2         | 0.63%   |
| Gentoo       | 2         | 0.63%   |
| ArcoLinux    | 2         | 0.63%   |
| SteamOS      | 1         | 0.31%   |
| Rocky Linux  | 1         | 0.31%   |
| openSUSE     | 1         | 0.31%   |
| Lubuntu      | 1         | 0.31%   |
| Linux Lite   | 1         | 0.31%   |
| Kaisen       | 1         | 0.31%   |
| GNOME OS     | 1         | 0.31%   |
| GalliumOS    | 1         | 0.31%   |
| EndeavourOS  | 1         | 0.31%   |
| Elementary   | 1         | 0.31%   |
| Clear Linux  | 1         | 0.31%   |
| CentOS       | 1         | 0.31%   |
| Alpine       | 1         | 0.31%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 4.18.16-desktop-1bP              | 20        | 5.71%   |
| 5.10.14-desktop-1omv4002         | 12        | 3.43%   |
| 5.6.14-desktop-2bP               | 10        | 2.86%   |
| 5.16.7-desktop-1omv4003          | 9         | 2.57%   |
| 5.4.0-58-generic                 | 8         | 2.29%   |
| 5.4.0-42-generic                 | 7         | 2%      |
| 5.4.0-52-generic                 | 5         | 1.43%   |
| 5.11.0-27-generic                | 5         | 1.43%   |
| 5.8.0-43-generic                 | 4         | 1.14%   |
| 5.4.0-73-generic                 | 4         | 1.14%   |
| 5.4.0-47-generic                 | 4         | 1.14%   |
| 4.9.60-nrj-desktop-1rosa-x86_64  | 4         | 1.14%   |
| 4.15.0-66-generic                | 4         | 1.14%   |
| 5.8.0-50-generic                 | 3         | 0.86%   |
| 5.8.0-29-generic                 | 3         | 0.86%   |
| 5.4.0-91-generic                 | 3         | 0.86%   |
| 5.4.0-88-generic                 | 3         | 0.86%   |
| 5.3.0-40-generic                 | 3         | 0.86%   |
| 5.3.0-26-generic                 | 3         | 0.86%   |
| 5.13.0-35-generic                | 3         | 0.86%   |
| 5.0.0-25-generic                 | 3         | 0.86%   |
| 4.9.124-nrj-desktop-1rosa-x86_64 | 3         | 0.86%   |
| 4.19.0-13-amd64                  | 3         | 0.86%   |
| 4.15.0-55-generic                | 3         | 0.86%   |
| 5.9.16-200.fc33.x86_64           | 2         | 0.57%   |
| 5.8.0-7630-generic               | 2         | 0.57%   |
| 5.8.0-7625-generic               | 2         | 0.57%   |
| 5.4.83-generic-2rosa-x86_64      | 2         | 0.57%   |
| 5.4.0-96-generic                 | 2         | 0.57%   |
| 5.4.0-65-generic                 | 2         | 0.57%   |
| 5.4.0-48-generic                 | 2         | 0.57%   |
| 5.4.0-29-generic                 | 2         | 0.57%   |
| 5.4.0-26-generic                 | 2         | 0.57%   |
| 5.3.0-46-generic                 | 2         | 0.57%   |
| 5.3.0-42-generic                 | 2         | 0.57%   |
| 5.3.0-28-generic                 | 2         | 0.57%   |
| 5.3.0-24-generic                 | 2         | 0.57%   |
| 5.15.0-33-generic                | 2         | 0.57%   |
| 5.13.0-40-generic                | 2         | 0.57%   |
| 5.13.0-27-generic                | 2         | 0.57%   |
| 5.11.3-300.fc34.x86_64           | 2         | 0.57%   |
| 5.11.0-43-generic                | 2         | 0.57%   |
| 5.11.0-40-generic                | 2         | 0.57%   |
| 5.11.0-16-generic                | 2         | 0.57%   |
| 5.10.0-8-amd64                   | 2         | 0.57%   |
| 5.10.0-11-amd64                  | 2         | 0.57%   |
| 5.0.0-37-generic                 | 2         | 0.57%   |
| 5.0.0-36-generic                 | 2         | 0.57%   |
| 5.0.0-31-generic                 | 2         | 0.57%   |
| 5.0.0-29-generic                 | 2         | 0.57%   |
| 5.0.0-23-generic                 | 2         | 0.57%   |
| 4.19.0-6-amd64                   | 2         | 0.57%   |
| 4.19.0-5-amd64                   | 2         | 0.57%   |
| 4.18.0-15-generic                | 2         | 0.57%   |
| 4.15.0-74-generic                | 2         | 0.57%   |
| 4.15.0-58-generic                | 2         | 0.57%   |
| 4.15.0-45-generic                | 2         | 0.57%   |
| 4.15.0-42-generic                | 2         | 0.57%   |
| 4.15.0-38-generic                | 2         | 0.57%   |
| 4.15.0-29-generic                | 2         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 64        | 19.05%  |
| 4.15.0  | 35        | 10.42%  |
| 5.8.0   | 23        | 6.85%   |
| 4.18.16 | 20        | 5.95%   |
| 5.3.0   | 17        | 5.06%   |
| 5.13.0  | 15        | 4.46%   |
| 5.11.0  | 15        | 4.46%   |
| 5.0.0   | 15        | 4.46%   |
| 5.10.14 | 12        | 3.57%   |
| 5.6.14  | 10        | 2.98%   |
| 5.16.7  | 9         | 2.68%   |
| 4.19.0  | 7         | 2.08%   |
| 4.18.0  | 7         | 2.08%   |
| 5.10.0  | 6         | 1.79%   |
| 4.9.60  | 4         | 1.19%   |
| 5.9.16  | 3         | 0.89%   |
| 5.15.0  | 3         | 0.89%   |
| 5.11.11 | 3         | 0.89%   |
| 4.9.124 | 3         | 0.89%   |
| 5.4.83  | 2         | 0.6%    |
| 5.17.5  | 2         | 0.6%    |
| 5.17.1  | 2         | 0.6%    |
| 5.11.3  | 2         | 0.6%    |
| 4.9.20  | 2         | 0.6%    |
| 4.4.0   | 2         | 0.6%    |
| 5.9.4   | 1         | 0.3%    |
| 5.8.9   | 1         | 0.3%    |
| 5.7.19  | 1         | 0.3%    |
| 5.7.12  | 1         | 0.3%    |
| 5.6.13  | 1         | 0.3%    |
| 5.6.11  | 1         | 0.3%    |
| 5.6.0   | 1         | 0.3%    |
| 5.5.8   | 1         | 0.3%    |
| 5.5.5   | 1         | 0.3%    |
| 5.5.17  | 1         | 0.3%    |
| 5.5.11  | 1         | 0.3%    |
| 5.5.0   | 1         | 0.3%    |
| 5.4.40  | 1         | 0.3%    |
| 5.4.32  | 1         | 0.3%    |
| 5.3.6   | 1         | 0.3%    |
| 5.3.13  | 1         | 0.3%    |
| 5.2.21  | 1         | 0.3%    |
| 5.18.12 | 1         | 0.3%    |
| 5.17.8  | 1         | 0.3%    |
| 5.17.0  | 1         | 0.3%    |
| 5.16.9  | 1         | 0.3%    |
| 5.16.11 | 1         | 0.3%    |
| 5.15.8  | 1         | 0.3%    |
| 5.15.52 | 1         | 0.3%    |
| 5.15.50 | 1         | 0.3%    |
| 5.15.41 | 1         | 0.3%    |
| 5.15.4  | 1         | 0.3%    |
| 5.15.3  | 1         | 0.3%    |
| 5.15.28 | 1         | 0.3%    |
| 5.15.23 | 1         | 0.3%    |
| 5.15.13 | 1         | 0.3%    |
| 5.13.9  | 1         | 0.3%    |
| 5.13.4  | 1         | 0.3%    |
| 5.13.19 | 1         | 0.3%    |
| 5.12.9  | 1         | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 68        | 20.3%   |
| 4.15    | 35        | 10.45%  |
| 4.18    | 27        | 8.06%   |
| 5.8     | 24        | 7.16%   |
| 5.10    | 23        | 6.87%   |
| 5.11    | 21        | 6.27%   |
| 5.3     | 19        | 5.67%   |
| 5.13    | 18        | 5.37%   |
| 5.0     | 17        | 5.07%   |
| 5.6     | 13        | 3.88%   |
| 5.15    | 12        | 3.58%   |
| 5.16    | 11        | 3.28%   |
| 4.9     | 11        | 3.28%   |
| 4.19    | 8         | 2.39%   |
| 5.17    | 6         | 1.79%   |
| 5.5     | 5         | 1.49%   |
| 5.9     | 4         | 1.19%   |
| 5.12    | 3         | 0.9%    |
| 5.7     | 2         | 0.6%    |
| 4.4     | 2         | 0.6%    |
| 5.2     | 1         | 0.3%    |
| 5.18    | 1         | 0.3%    |
| 4.17    | 1         | 0.3%    |
| 4.16    | 1         | 0.3%    |
| 4.12    | 1         | 0.3%    |
| 4.1     | 1         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 282       | 90.97%  |
| i686   | 28        | 9.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 110       | 34.7%   |
| KDE5            | 71        | 22.4%   |
| Unknown         | 46        | 14.51%  |
| XFCE            | 33        | 10.41%  |
| X-Cinnamon      | 25        | 7.89%   |
| KDE4            | 8         | 2.52%   |
| KDE             | 7         | 2.21%   |
| MATE            | 6         | 1.89%   |
| Unity           | 3         | 0.95%   |
| Cinnamon        | 3         | 0.95%   |
| LXDE            | 2         | 0.63%   |
| Pantheon        | 1         | 0.32%   |
| GNOME Flashback | 1         | 0.32%   |
| awesome         | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 264       | 84.35%  |
| Wayland | 26        | 8.31%   |
| Unknown | 20        | 6.39%   |
| Tty     | 3         | 0.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 165       | 52.22%  |
| SDDM    | 65        | 20.57%  |
| GDM     | 29        | 9.18%   |
| LightDM | 22        | 6.96%   |
| GDM3    | 15        | 4.75%   |
| TDM     | 11        | 3.48%   |
| KDM     | 8         | 2.53%   |
| XDM     | 1         | 0.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 113       | 35.31%  |
| sk_SK   | 95        | 29.69%  |
| Unknown | 87        | 27.19%  |
| cs_CZ   | 9         | 2.81%   |
| hu_HU   | 5         | 1.56%   |
| C       | 4         | 1.25%   |
| en_GB   | 3         | 0.94%   |
| ru_UA   | 1         | 0.31%   |
| ru_RU   | 1         | 0.31%   |
| it_IT   | 1         | 0.31%   |
| en_US  | 1         | 0.31%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 183       | 58.1%   |
| EFI  | 132       | 41.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 221       | 69.5%   |
| Overlay | 51        | 16.04%  |
| Btrfs   | 17        | 5.35%   |
| Unknown | 16        | 5.03%   |
| Zfs     | 5         | 1.57%   |
| Xfs     | 4         | 1.26%   |
| Ext3    | 2         | 0.63%   |
| Ext2    | 2         | 0.63%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 178       | 56.15%  |
| GPT     | 75        | 23.66%  |
| MBR     | 64        | 20.19%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 267       | 83.96%  |
| Yes       | 51        | 16.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 209       | 66.99%  |
| Yes       | 103       | 33.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 83        | 26.86%  |
| Hewlett-Packard  | 57        | 18.45%  |
| ASUSTek Computer | 50        | 16.18%  |
| Dell             | 42        | 13.59%  |
| Acer             | 23        | 7.44%   |
| Toshiba          | 15        | 4.85%   |
| Sony             | 8         | 2.59%   |
| MSI              | 8         | 2.59%   |
| Fujitsu Siemens  | 4         | 1.29%   |
| UMAX             | 3         | 0.97%   |
| Fujitsu          | 3         | 0.97%   |
| eMachines        | 3         | 0.97%   |
| Packard Bell     | 2         | 0.65%   |
| Apple            | 2         | 0.65%   |
| Valve            | 1         | 0.32%   |
| Timi             | 1         | 0.32%   |
| Teclast          | 1         | 0.32%   |
| Medion           | 1         | 0.32%   |
| Google           | 1         | 0.32%   |
| Unknown          | 1         | 0.32%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Notebooks | Percent |
|------------------------------------|-----------|---------|
| ASUS X550CC                        | 4         | 1.29%   |
| HP ProBook 4540s                   | 3         | 0.97%   |
| HP Pavilion dv6                    | 3         | 0.97%   |
| Toshiba Satellite P300             | 2         | 0.65%   |
| MSI VR610                          | 2         | 0.65%   |
| Lenovo Yoga Slim 7 Pro 14ITL5 82FX | 2         | 0.65%   |
| Lenovo IdeaPad U260 20067          | 2         | 0.65%   |
| Lenovo IdeaPad S145-14AST 81ST     | 2         | 0.65%   |
| Lenovo G580                        | 2         | 0.65%   |
| HP ProBook 6570b                   | 2         | 0.65%   |
| HP ProBook 650 G1                  | 2         | 0.65%   |
| HP ProBook 4545s                   | 2         | 0.65%   |
| HP ProBook 450 G5                  | 2         | 0.65%   |
| HP ProBook 4330s                   | 2         | 0.65%   |
| HP EliteBook 8470p                 | 2         | 0.65%   |
| Dell Precision 7530                | 2         | 0.65%   |
| Dell Latitude E6540                | 2         | 0.65%   |
| Dell Latitude 5490                 | 2         | 0.65%   |
| Dell Latitude 5401                 | 2         | 0.65%   |
| ASUS X51R                          | 2         | 0.65%   |
| ASUS X51L                          | 2         | 0.65%   |
| ASUS K50C                          | 2         | 0.65%   |
| Acer Extensa 5635G                 | 2         | 0.65%   |
| Unknown                            | 2         | 0.65%   |
| Valve Jupiter                      | 1         | 0.32%   |
| UMAX VisionBook-N12R               | 1         | 0.32%   |
| UMAX VisionBook 14Wr Plus          | 1         | 0.32%   |
| UMAX VisionBook 14Wg Pro           | 1         | 0.32%   |
| Toshiba Satellite U400             | 1         | 0.32%   |
| Toshiba Satellite Pro C850-1D5     | 1         | 0.32%   |
| Toshiba Satellite Pro C660         | 1         | 0.32%   |
| Toshiba Satellite P770             | 1         | 0.32%   |
| Toshiba Satellite L850-1HP         | 1         | 0.32%   |
| Toshiba Satellite L735             | 1         | 0.32%   |
| Toshiba Satellite L500             | 1         | 0.32%   |
| Toshiba Satellite L450             | 1         | 0.32%   |
| Toshiba Satellite C855-1TT         | 1         | 0.32%   |
| Toshiba Satellite C850-13Z         | 1         | 0.32%   |
| Toshiba Satellite C660             | 1         | 0.32%   |
| Toshiba Satellite C50-A            | 1         | 0.32%   |
| Toshiba EQUIUM A300D               | 1         | 0.32%   |
| Timi TM1701                        | 1         | 0.32%   |
| Teclast F15S                       | 1         | 0.32%   |
| Sony VPCEH3S6E                     | 1         | 0.32%   |
| Sony VPCEH1S1E                     | 1         | 0.32%   |
| Sony VPCEH1L8E                     | 1         | 0.32%   |
| Sony VPCEE2M1E                     | 1         | 0.32%   |
| Sony VPCEB3L1E                     | 1         | 0.32%   |
| Sony VGN-NR21J_S                   | 1         | 0.32%   |
| Sony VGN-FW31ZJ                    | 1         | 0.32%   |
| Sony SVE1713F1EW                   | 1         | 0.32%   |
| Packard Bell EasyNote TK85         | 1         | 0.32%   |
| Packard Bell EasyNote TE11BZ       | 1         | 0.32%   |
| MSI VR201                          | 1         | 0.32%   |
| MSI Prestige 15 A10SC              | 1         | 0.32%   |
| MSI GX630/GX633                    | 1         | 0.32%   |
| MSI GT60 2OC/2OD                   | 1         | 0.32%   |
| MSI EX705                          | 1         | 0.32%   |
| MSI CR500                          | 1         | 0.32%   |
| Medion E6435 MD60939               | 1         | 0.32%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 38        | 12.3%   |
| Lenovo IdeaPad           | 23        | 7.44%   |
| Dell Latitude            | 21        | 6.8%    |
| HP ProBook               | 20        | 6.47%   |
| Toshiba Satellite        | 14        | 4.53%   |
| HP Pavilion              | 11        | 3.56%   |
| HP EliteBook             | 11        | 3.56%   |
| Acer Aspire              | 11        | 3.56%   |
| Dell XPS                 | 5         | 1.62%   |
| Dell Inspiron            | 5         | 1.62%   |
| Acer Swift               | 5         | 1.62%   |
| Dell Vostro              | 4         | 1.29%   |
| ASUS X550CC              | 4         | 1.29%   |
| Acer Extensa             | 4         | 1.29%   |
| Lenovo Yoga              | 3         | 0.97%   |
| Lenovo Legion            | 3         | 0.97%   |
| HP ZBook                 | 3         | 0.97%   |
| UMAX VisionBook          | 2         | 0.65%   |
| Packard Bell EasyNote    | 2         | 0.65%   |
| MSI VR610                | 2         | 0.65%   |
| Lenovo G580              | 2         | 0.65%   |
| HP Laptop                | 2         | 0.65%   |
| HP Compaq                | 2         | 0.65%   |
| Fujitsu Siemens LIFEBOOK | 2         | 0.65%   |
| Fujitsu LIFEBOOK         | 2         | 0.65%   |
| Dell Studio              | 2         | 0.65%   |
| Dell Precision           | 2         | 0.65%   |
| ASUS ZenBook             | 2         | 0.65%   |
| ASUS X51R                | 2         | 0.65%   |
| ASUS X51L                | 2         | 0.65%   |
| ASUS ROG                 | 2         | 0.65%   |
| ASUS K50C                | 2         | 0.65%   |
| Unknown                  | 2         | 0.65%   |
| Valve Jupiter            | 1         | 0.32%   |
| UMAX VisionBook-N12R     | 1         | 0.32%   |
| Toshiba EQUIUM           | 1         | 0.32%   |
| Timi TM1701              | 1         | 0.32%   |
| Teclast F15S             | 1         | 0.32%   |
| Sony VPCEH3S6E           | 1         | 0.32%   |
| Sony VPCEH1S1E           | 1         | 0.32%   |
| Sony VPCEH1L8E           | 1         | 0.32%   |
| Sony VPCEE2M1E           | 1         | 0.32%   |
| Sony VPCEB3L1E           | 1         | 0.32%   |
| Sony VGN-NR21J           | 1         | 0.32%   |
| Sony VGN-FW31ZJ          | 1         | 0.32%   |
| Sony SVE1713F1EW         | 1         | 0.32%   |
| MSI VR201                | 1         | 0.32%   |
| MSI Prestige             | 1         | 0.32%   |
| MSI GX630                | 1         | 0.32%   |
| MSI GT60                 | 1         | 0.32%   |
| MSI EX705                | 1         | 0.32%   |
| MSI CR500                | 1         | 0.32%   |
| Medion E6435             | 1         | 0.32%   |
| Lenovo Z710              | 1         | 0.32%   |
| Lenovo Z50-70            | 1         | 0.32%   |
| Lenovo Y520-15IKBN       | 1         | 0.32%   |
| Lenovo V110-15IAP        | 1         | 0.32%   |
| Lenovo ThinkBook         | 1         | 0.32%   |
| Lenovo G780              | 1         | 0.32%   |
| Lenovo G710              | 1         | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2013 | 34        | 11%     |
| 2012 | 33        | 10.68%  |
| 2011 | 26        | 8.41%   |
| 2019 | 25        | 8.09%   |
| 2008 | 23        | 7.44%   |
| 2017 | 19        | 6.15%   |
| 2016 | 18        | 5.83%   |
| 2009 | 18        | 5.83%   |
| 2020 | 17        | 5.5%    |
| 2018 | 17        | 5.5%    |
| 2010 | 17        | 5.5%    |
| 2007 | 17        | 5.5%    |
| 2015 | 13        | 4.21%   |
| 2014 | 12        | 3.88%   |
| 2021 | 11        | 3.56%   |
| 2006 | 7         | 2.27%   |
| 2022 | 1         | 0.32%   |
| 2005 | 1         | 0.32%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 309       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 281       | 90.35%  |
| Enabled  | 30        | 9.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 308       | 99.68%  |
| Yes  | 1         | 0.32%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 91        | 29.17%  |
| 4.01-8.0    | 73        | 23.4%   |
| 8.01-16.0   | 48        | 15.38%  |
| 16.01-24.0  | 46        | 14.74%  |
| 1.01-2.0    | 25        | 8.01%   |
| 32.01-64.0  | 12        | 3.85%   |
| 2.01-3.0    | 11        | 3.53%   |
| 0.51-1.0    | 5         | 1.6%    |
| 64.01-256.0 | 1         | 0.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 133       | 39.94%  |
| 2.01-3.0  | 63        | 18.92%  |
| 0.51-1.0  | 56        | 16.82%  |
| 3.01-4.0  | 32        | 9.61%   |
| 4.01-8.0  | 30        | 9.01%   |
| 8.01-16.0 | 12        | 3.6%    |
| 0.01-0.5  | 7         | 2.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 224       | 69.78%  |
| 2      | 79        | 24.61%  |
| 3      | 12        | 3.74%   |
| 0      | 6         | 1.87%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 163       | 52.41%  |
| Yes       | 148       | 47.59%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 276       | 89.32%  |
| No        | 33        | 10.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 305       | 98.71%  |
| No        | 4         | 1.29%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 223       | 71.94%  |
| No        | 87        | 28.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Slovakia | 309       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Bratislava           | 125       | 37.2%   |
| Banská Bystrica     | 17        | 5.06%   |
| Nitra                | 13        | 3.87%   |
| Košice              | 12        | 3.57%   |
| Trnava               | 6         | 1.79%   |
| Prešov              | 6         | 1.79%   |
| Trenčín            | 4         | 1.19%   |
| Soblahov             | 4         | 1.19%   |
| Nové Zámky         | 4         | 1.19%   |
| Humenné             | 4         | 1.19%   |
| Bardejov             | 4         | 1.19%   |
| Zvolen               | 3         | 0.89%   |
| Žilina              | 3         | 0.89%   |
| Topoľčany          | 3         | 0.89%   |
| Senec                | 3         | 0.89%   |
| Martin               | 3         | 0.89%   |
| Lučenec             | 3         | 0.89%   |
| Levice               | 3         | 0.89%   |
| Kysucké Nové Mesto | 3         | 0.89%   |
| Dunajská Streda     | 3         | 0.89%   |
| Voderady             | 2         | 0.6%    |
| Vlkova               | 2         | 0.6%    |
| Tornaľa             | 2         | 0.6%    |
| Štúrovo            | 2         | 0.6%    |
| Stara Tura           | 2         | 0.6%    |
| Ružomberok          | 2         | 0.6%    |
| Rožňava            | 2         | 0.6%    |
| Rohoznik             | 2         | 0.6%    |
| Poprad               | 2         | 0.6%    |
| Podhradie            | 2         | 0.6%    |
| Námestovo           | 2         | 0.6%    |
| Most pri Bratislave  | 2         | 0.6%    |
| Liptovský Mikuláš | 2         | 0.6%    |
| Krupina              | 2         | 0.6%    |
| Galanta              | 2         | 0.6%    |
| Chorvatsky Grob      | 2         | 0.6%    |
| Cerveny Kamen        | 2         | 0.6%    |
| Cechynce             | 2         | 0.6%    |
| Biely Kostol         | 2         | 0.6%    |
| Banovce nad Bebravou | 2         | 0.6%    |
| Abovce               | 2         | 0.6%    |
| Ziar nad Hronom      | 1         | 0.3%    |
| Vlckovce             | 1         | 0.3%    |
| Velky Saris          | 1         | 0.3%    |
| Velky Meder          | 1         | 0.3%    |
| Velky Krtis          | 1         | 0.3%    |
| Velka Maca           | 1         | 0.3%    |
| Vahovce              | 1         | 0.3%    |
| Trstice              | 1         | 0.3%    |
| Trebišov            | 1         | 0.3%    |
| Topolcianky          | 1         | 0.3%    |
| Tekovska Breznica    | 1         | 0.3%    |
| Svit                 | 1         | 0.3%    |
| Svidník             | 1         | 0.3%    |
| Šurany              | 1         | 0.3%    |
| Stropkov             | 1         | 0.3%    |
| Strecno              | 1         | 0.3%    |
| Stará Ľubovňa     | 1         | 0.3%    |
| Spišská Nová Ves  | 1         | 0.3%    |
| Soporna              | 1         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 60        | 69     | 15.15%  |
| WDC                 | 58        | 65     | 14.65%  |
| Samsung Electronics | 51        | 60     | 12.88%  |
| Toshiba             | 28        | 39     | 7.07%   |
| Kingston            | 25        | 33     | 6.31%   |
| SanDisk             | 21        | 23     | 5.3%    |
| Unknown             | 20        | 32     | 5.05%   |
| Hitachi             | 16        | 16     | 4.04%   |
| Intel               | 15        | 18     | 3.79%   |
| Patriot             | 14        | 22     | 3.54%   |
| A-DATA Technology   | 12        | 19     | 3.03%   |
| HGST                | 11        | 15     | 2.78%   |
| SK hynix            | 9         | 11     | 2.27%   |
| Micron Technology   | 9         | 11     | 2.27%   |
| Crucial             | 9         | 12     | 2.27%   |
| Fujitsu             | 4         | 4      | 1.01%   |
| Union Memory        | 2         | 2      | 0.51%   |
| Transcend           | 2         | 2      | 0.51%   |
| OCZ                 | 2         | 2      | 0.51%   |
| LITEONIT            | 2         | 2      | 0.51%   |
| LITEON              | 2         | 2      | 0.51%   |
| KIOXIA              | 2         | 9      | 0.51%   |
| Apacer              | 2         | 2      | 0.51%   |
| Unknown             | 2         | 2      | 0.51%   |
| ZTE                 | 1         | 1      | 0.25%   |
| Verbatim            | 1         | 1      | 0.25%   |
| Solid State Storage | 1         | 1      | 0.25%   |
| Phison              | 1         | 1      | 0.25%   |
| KingSpec            | 1         | 1      | 0.25%   |
| KingDian            | 1         | 3      | 0.25%   |
| JMicron Technology  | 1         | 1      | 0.25%   |
| Intenso             | 1         | 1      | 0.25%   |
| IM3D                | 1         | 1      | 0.25%   |
| IBM/Hitachi         | 1         | 1      | 0.25%   |
| HUAWEI              | 1         | 1      | 0.25%   |
| HS-SSD-E100         | 1         | 1      | 0.25%   |
| Hewlett-Packard     | 1         | 1      | 0.25%   |
| Faspeed             | 1         | 1      | 0.25%   |
| China               | 1         | 2      | 0.25%   |
| ASMT                | 1         | 1      | 0.25%   |
| Apple               | 1         | 2      | 0.25%   |
| 2.5                 | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB           | 9         | 2.18%   |
| Patriot Burst 240GB SSD             | 8         | 1.94%   |
| Patriot Burst 480GB SSD             | 7         | 1.69%   |
| Unknown MMC Card  64GB              | 5         | 1.21%   |
| Seagate ST9500420AS 500GB           | 5         | 1.21%   |
| Seagate ST9500325AS 500GB           | 5         | 1.21%   |
| Samsung SSD 850 EVO 500GB           | 5         | 1.21%   |
| Kingston SV300S37A120G 120GB SSD    | 5         | 1.21%   |
| Kingston SA400S37240G 240GB SSD     | 5         | 1.21%   |
| Kingston SA400S37120G 120GB SSD     | 5         | 1.21%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 4         | 0.97%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 4         | 0.97%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 0.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 4         | 0.97%   |
| SanDisk NVMe SSD Drive 512GB        | 4         | 0.97%   |
| SanDisk NVMe SSD Drive 1024GB       | 4         | 0.97%   |
| HGST HTS725050A7E630 500GB          | 4         | 0.97%   |
| Toshiba NVMe SSD Drive 512GB        | 3         | 0.73%   |
| Toshiba MQ01ABF050 500GB            | 3         | 0.73%   |
| Toshiba MQ01ABD100 1TB              | 3         | 0.73%   |
| SK hynix NVMe SSD Drive 512GB       | 3         | 0.73%   |
| Seagate ST9250827AS 250GB           | 3         | 0.73%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 0.73%   |
| Seagate ST500LM000-1EJ162 500GB     | 3         | 0.73%   |
| Samsung SSD 860 EVO 250GB           | 3         | 0.73%   |
| Samsung SSD 850 EVO 250GB           | 3         | 0.73%   |
| Samsung NVMe SSD Drive 256GB        | 3         | 0.73%   |
| HGST HTS545050A7E380 500GB          | 3         | 0.73%   |
| Crucial CT120BX500SSD1 120GB        | 3         | 0.73%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 2         | 0.48%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2         | 0.48%   |
| WDC WD10JPLX-00MBPT0 1TB            | 2         | 0.48%   |
| WDC WD10JPCX-24UE4T0 1TB            | 2         | 0.48%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB  | 2         | 0.48%   |
| WDC PC SN730 NVMe 512GB             | 2         | 0.48%   |
| Unknown MMC Card  32GB              | 2         | 0.48%   |
| Unknown MMC Card  128GB             | 2         | 0.48%   |
| Union Memory RTOTJ128VGD2EYX 128GB  | 2         | 0.48%   |
| Toshiba MK7575GSX 752GB             | 2         | 0.48%   |
| Toshiba MK2546GSX 250GB             | 2         | 0.48%   |
| SK hynix NVMe SSD Drive 256GB       | 2         | 0.48%   |
| Seagate ST9750420AS 752GB           | 2         | 0.48%   |
| Seagate ST9250315AS 250GB           | 2         | 0.48%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2         | 0.48%   |
| Seagate ST320LT020-9YG142 320GB     | 2         | 0.48%   |
| Seagate ST320LT007-9ZV142 320GB     | 2         | 0.48%   |
| Seagate ST2000LX001-1RG174 2TB      | 2         | 0.48%   |
| Seagate ST2000LM007-1R8174 2TB      | 2         | 0.48%   |
| SanDisk Z400s M.2 2280 128GB SSD    | 2         | 0.48%   |
| Samsung NVMe SSD Drive 512GB        | 2         | 0.48%   |
| Samsung MZVLB512HBJQ-000L7 512GB    | 2         | 0.48%   |
| Patriot P210 256GB SSD              | 2         | 0.48%   |
| Micron NVMe SSD Drive 512GB         | 2         | 0.48%   |
| Kingston SA400S37480G 480GB SSD     | 2         | 0.48%   |
| Intel SSDSC2CW060A3 64GB            | 2         | 0.48%   |
| Intel SSDSA2BW120G3H 120GB          | 2         | 0.48%   |
| Hitachi HTS543232A7A384 320GB       | 2         | 0.48%   |
| Hitachi HTS541612J9SA00 120GB       | 2         | 0.48%   |
| HGST HTS721010A9E630 1TB            | 2         | 0.48%   |
| Crucial CT1000MX500SSD1 1TB         | 2         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 60        | 69     | 39.22%  |
| WDC                 | 39        | 43     | 25.49%  |
| Toshiba             | 21        | 32     | 13.73%  |
| Hitachi             | 16        | 16     | 10.46%  |
| HGST                | 11        | 15     | 7.19%   |
| Fujitsu             | 4         | 4      | 2.61%   |
| Samsung Electronics | 1         | 2      | 0.65%   |
| IBM/Hitachi         | 1         | 1      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 35     | 20.26%  |
| Kingston            | 22        | 30     | 14.38%  |
| Patriot             | 14        | 22     | 9.15%   |
| WDC                 | 12        | 14     | 7.84%   |
| SanDisk             | 11        | 13     | 7.19%   |
| Intel               | 11        | 14     | 7.19%   |
| A-DATA Technology   | 11        | 18     | 7.19%   |
| Crucial             | 9         | 12     | 5.88%   |
| Micron Technology   | 5         | 7      | 3.27%   |
| Toshiba             | 3         | 3      | 1.96%   |
| Union Memory        | 2         | 2      | 1.31%   |
| Transcend           | 2         | 2      | 1.31%   |
| SK hynix            | 2         | 2      | 1.31%   |
| OCZ                 | 2         | 2      | 1.31%   |
| LITEONIT            | 2         | 2      | 1.31%   |
| LITEON              | 2         | 2      | 1.31%   |
| Apacer              | 2         | 2      | 1.31%   |
| Verbatim            | 1         | 1      | 0.65%   |
| KingSpec            | 1         | 1      | 0.65%   |
| KingDian            | 1         | 3      | 0.65%   |
| Intenso             | 1         | 1      | 0.65%   |
| IM3D                | 1         | 1      | 0.65%   |
| HS-SSD-E100         | 1         | 1      | 0.65%   |
| Hewlett-Packard     | 1         | 1      | 0.65%   |
| Faspeed             | 1         | 1      | 0.65%   |
| China               | 1         | 2      | 0.65%   |
| 2.5                 | 1         | 1      | 0.65%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 146       | 182    | 39.57%  |
| SSD     | 136       | 195    | 36.86%  |
| NVMe    | 61        | 79     | 16.53%  |
| MMC     | 22        | 34     | 5.96%   |
| Unknown | 4         | 4      | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 246       | 367    | 71.93%  |
| NVMe | 61        | 79     | 17.84%  |
| MMC  | 22        | 34     | 6.43%   |
| SAS  | 13        | 14     | 3.8%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 208       | 301    | 77.9%   |
| 0.51-1.0   | 52        | 67     | 19.48%  |
| 1.01-2.0   | 7         | 9      | 2.62%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 88        | 26.83%  |
| 251-500        | 69        | 21.04%  |
| 501-1000       | 36        | 10.98%  |
| 1-20           | 34        | 10.37%  |
| 51-100         | 31        | 9.45%   |
| Unknown        | 28        | 8.54%   |
| 21-50          | 23        | 7.01%   |
| 1001-2000      | 13        | 3.96%   |
| More than 3000 | 4         | 1.22%   |
| 2001-3000      | 2         | 0.61%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 146       | 43.84%  |
| 21-50          | 52        | 15.62%  |
| 51-100         | 36        | 10.81%  |
| 101-250        | 34        | 10.21%  |
| Unknown        | 28        | 8.41%   |
| 251-500        | 21        | 6.31%   |
| 501-1000       | 10        | 3%      |
| 1001-2000      | 4         | 1.2%    |
| More than 3000 | 2         | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MK7575GSX 752GB                        | 2         | 3      | 5%      |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1         | 1      | 2.5%    |
| WDC WD7500BPVT-80HXZT3 752GB                   | 1         | 1      | 2.5%    |
| WDC WD5000LPVT-24G33T1 500GB                   | 1         | 1      | 2.5%    |
| WDC WD5000BPVT-00HXZT1 500GB                   | 1         | 1      | 2.5%    |
| WDC WD3200BEVT-75ZCT2 320GB                    | 1         | 1      | 2.5%    |
| WDC WD10JPLX-00MBPT0 1TB                       | 1         | 1      | 2.5%    |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 2.5%    |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 2.5%    |
| Toshiba MK5056GSY 500GB                        | 1         | 1      | 2.5%    |
| Toshiba MK1646GSX 160GB                        | 1         | 2      | 2.5%    |
| Toshiba MK1637GSX 160GB                        | 1         | 1      | 2.5%    |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB        | 1         | 1      | 2.5%    |
| Seagate ST980811AS 80GB                        | 1         | 1      | 2.5%    |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 2.5%    |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 2.5%    |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 2.5%    |
| Seagate ST9120823ASG 120GB                     | 1         | 1      | 2.5%    |
| Seagate ST500LM000-SSHD-8GB                    | 1         | 1      | 2.5%    |
| Seagate ST500LM000-1EJ162 500GB                | 1         | 1      | 2.5%    |
| Seagate ST320LT020-9YG142 320GB                | 1         | 2      | 2.5%    |
| Seagate ST320LT007-9ZV142 320GB                | 1         | 1      | 2.5%    |
| Seagate ST2000LX001-1RG174 2TB                 | 1         | 1      | 2.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 1      | 2.5%    |
| SanDisk SD8SN8U-256G-1006 256GB SSD            | 1         | 1      | 2.5%    |
| Samsung Electronics SSD 960 EVO 500GB          | 1         | 1      | 2.5%    |
| Samsung Electronics HS122JC 120GB              | 1         | 2      | 2.5%    |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 2.5%    |
| Micron Technology 1100 SATA 256GB SSD          | 1         | 1      | 2.5%    |
| Intel SSDSC2CW060A3 64GB                       | 1         | 1      | 2.5%    |
| Intel SSDSC2BF240A5L 240GB                     | 1         | 1      | 2.5%    |
| IM3D L06B B0KB 120GB SSD                       | 1         | 1      | 2.5%    |
| Hitachi HTS723216L9A360 160GB                  | 1         | 1      | 2.5%    |
| Hitachi HTS547575A9E384 752GB                  | 1         | 1      | 2.5%    |
| Hitachi HTS545050A7E380 500GB                  | 1         | 1      | 2.5%    |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 2.5%    |
| Hitachi HTS543225L9SA00 250GB                  | 1         | 1      | 2.5%    |
| Hitachi HTS543216L9SA02 160GB                  | 1         | 1      | 2.5%    |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 27.5%   |
| Toshiba             | 7         | 9      | 17.5%   |
| WDC                 | 6         | 6      | 15%     |
| Hitachi             | 6         | 6      | 15%     |
| Samsung Electronics | 2         | 3      | 5%      |
| Micron Technology   | 2         | 2      | 5%      |
| Intel               | 2         | 2      | 5%      |
| SK hynix            | 1         | 1      | 2.5%    |
| SanDisk             | 1         | 1      | 2.5%    |
| IM3D                | 1         | 1      | 2.5%    |
| HGST                | 1         | 1      | 2.5%    |

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
| HDD  | 30        | 35     | 76.92%  |
| SSD  | 7         | 7      | 17.95%  |
| NVMe | 2         | 2      | 5.13%   |

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
| Detected | 188       | 266    | 56.12%  |
| Works    | 107       | 183    | 31.94%  |
| Malfunc  | 39        | 44     | 11.64%  |
| Failed   | 1         | 1      | 0.3%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 223       | 66.37%  |
| AMD                              | 40        | 11.9%   |
| Samsung Electronics              | 21        | 6.25%   |
| SanDisk                          | 17        | 5.06%   |
| SK hynix                         | 7         | 2.08%   |
| Nvidia                           | 7         | 2.08%   |
| Toshiba America Info Systems     | 4         | 1.19%   |
| Micron Technology                | 4         | 1.19%   |
| Silicon Integrated Systems [SiS] | 3         | 0.89%   |
| Kingston Technology Company      | 3         | 0.89%   |
| KIOXIA                           | 2         | 0.6%    |
| Solid State Storage Technology   | 1         | 0.3%    |
| Silicon Image                    | 1         | 0.3%    |
| Phison Electronics               | 1         | 0.3%    |
| Apple                            | 1         | 0.3%    |
| ADATA Technology                 | 1         | 0.3%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 39        | 10.16%  |
| AMD FCH SATA Controller [AHCI mode]                                                    | 25        | 6.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 21        | 5.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 18        | 4.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 15        | 3.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 15        | 3.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 14        | 3.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 14        | 3.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 14        | 3.65%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 13        | 3.39%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 9         | 2.34%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 9         | 2.34%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 7         | 1.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 6         | 1.56%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 6         | 1.56%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 6         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 6         | 1.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 6         | 1.56%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 6         | 1.56%   |
| AMD SB600 IDE                                                                          | 6         | 1.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 5         | 1.3%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 5         | 1.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 5         | 1.3%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 4         | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 1.04%   |
| Nvidia MCP79 AHCI Controller                                                           | 4         | 1.04%   |
| Micron Non-Volatile memory controller                                                  | 4         | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 4         | 1.04%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 4         | 1.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 4         | 1.04%   |
| SK hynix Gold P31 SSD                                                                  | 3         | 0.78%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 3         | 0.78%   |
| Samsung NVMe SSD Controller 980                                                        | 3         | 0.78%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 3         | 0.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 3         | 0.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 0.78%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                               | 3         | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 3         | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 3         | 0.78%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 2         | 0.52%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.52%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 2         | 0.52%   |
| SanDisk Non-Volatile memory controller                                                 | 2         | 0.52%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                       | 2         | 0.52%   |
| KIOXIA NVMe SSD Controller BG4                                                         | 2         | 0.52%   |
| Kingston Company OM3PDP3 NVMe SSD                                                      | 2         | 0.52%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 2         | 0.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 0.52%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 0.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 0.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 2         | 0.52%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 2         | 0.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 2         | 0.52%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 2         | 0.52%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 2         | 0.52%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 2         | 0.52%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 1         | 0.26%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 1         | 0.26%   |
| Solid State Storage Non-Volatile memory controller                                     | 1         | 0.26%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                            | 1         | 0.26%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 227       | 62.88%  |
| NVMe | 62        | 17.17%  |
| IDE  | 57        | 15.79%  |
| RAID | 15        | 4.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 256       | 82.85%  |
| AMD    | 53        | 17.15%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz           | 8         | 2.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 7         | 2.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 4         | 1.29%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 1.29%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 4         | 1.29%   |
| Intel Core i3-5010U CPU @ 2.10GHz           | 4         | 1.29%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 4         | 1.29%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 4         | 1.29%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 4         | 1.29%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz      | 3         | 0.97%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz      | 3         | 0.97%   |
| Intel Pentium CPU P6100 @ 2.00GHz           | 3         | 0.97%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 3         | 0.97%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 3         | 0.97%   |
| Intel Pentium CPU 2117U @ 1.80GHz           | 3         | 0.97%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 3         | 0.97%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 0.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 0.97%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 3         | 0.97%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 3         | 0.97%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 0.97%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 0.97%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 0.97%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 3         | 0.97%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 3         | 0.97%   |
| Intel Core i3 CPU U 380 @ 1.33GHz           | 3         | 0.97%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz        | 3         | 0.97%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz        | 3         | 0.97%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 3         | 0.97%   |
| AMD E-450 APU with Radeon HD Graphics       | 3         | 0.97%   |
| AMD Athlon 64 X2 Dual-Core Processor TK-55  | 3         | 0.97%   |
| Intel Pentium M processor 2.13GHz           | 2         | 0.65%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 0.65%   |
| Intel Pentium CPU B970 @ 2.30GHz            | 2         | 0.65%   |
| Intel Pentium CPU 4405U @ 2.10GHz           | 2         | 0.65%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 0.65%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 2         | 0.65%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 0.65%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 2         | 0.65%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 0.65%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 2         | 0.65%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 2         | 0.65%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 2         | 0.65%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 0.65%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 0.65%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 0.65%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 0.65%   |
| Intel Core i5 CPU M 430 @ 2.27GHz           | 2         | 0.65%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 0.65%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 0.65%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 2         | 0.65%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz        | 2         | 0.65%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 2         | 0.65%   |
| Intel Celeron Dual-Core CPU T3100 @ 1.90GHz | 2         | 0.65%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 2         | 0.65%   |
| Intel Celeron CPU B820 @ 1.70GHz            | 2         | 0.65%   |
| Intel Celeron CPU 220 @ 1.20GHz             | 2         | 0.65%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics  | 2         | 0.65%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 2         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 71        | 22.98%  |
| Intel Core i7                        | 55        | 17.8%   |
| Intel Core i3                        | 28        | 9.06%   |
| Intel Core 2 Duo                     | 24        | 7.77%   |
| Intel Pentium                        | 23        | 7.44%   |
| Intel Celeron                        | 16        | 5.18%   |
| Other                                | 9         | 2.91%   |
| Intel Pentium Dual                   | 8         | 2.59%   |
| AMD Ryzen 7                          | 7         | 2.27%   |
| Intel Atom                           | 6         | 1.94%   |
| AMD Ryzen 5                          | 6         | 1.94%   |
| Intel Celeron M                      | 4         | 1.29%   |
| AMD E                                | 4         | 1.29%   |
| AMD A8                               | 4         | 1.29%   |
| Intel Pentium Dual-Core              | 3         | 0.97%   |
| Intel Core 2                         | 3         | 0.97%   |
| Intel Celeron Dual-Core              | 3         | 0.97%   |
| AMD Ryzen 7 PRO                      | 3         | 0.97%   |
| AMD Athlon 64 X2                     | 3         | 0.97%   |
| AMD A6                               | 3         | 0.97%   |
| Intel Pentium M                      | 2         | 0.65%   |
| Intel Genuine                        | 2         | 0.65%   |
| AMD Turion 64 Mobile                 | 2         | 0.65%   |
| AMD Ryzen 5 PRO                      | 2         | 0.65%   |
| AMD Ryzen 3                          | 2         | 0.65%   |
| AMD E1                               | 2         | 0.65%   |
| AMD Athlon                           | 2         | 0.65%   |
| AMD A4                               | 2         | 0.65%   |
| Intel Pentium Silver                 | 1         | 0.32%   |
| Intel Core 2 Quad                    | 1         | 0.32%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.32%   |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.32%   |
| AMD Turion 64 X2 Mobile              | 1         | 0.32%   |
| AMD PRO A10                          | 1         | 0.32%   |
| AMD Mobile Sempron                   | 1         | 0.32%   |
| AMD E2                               | 1         | 0.32%   |
| AMD Athlon II                        | 1         | 0.32%   |
| AMD A10                              | 1         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 190       | 61.49%  |
| 4       | 78        | 25.24%  |
| 1       | 16        | 5.18%   |
| 6       | 15        | 4.85%   |
| 8       | 9         | 2.91%   |
| Unknown | 1         | 0.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 309       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 185       | 59.87%  |
| 1       | 123       | 39.81%  |
| Unknown | 1         | 0.32%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 296       | 94.57%  |
| Unknown        | 9         | 2.88%   |
| 32-bit         | 8         | 2.56%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 12.78%  |
| 0x306a9    | 32        | 10.22%  |
| 0x206a7    | 26        | 8.31%   |
| 0x1067a    | 17        | 5.43%   |
| 0x806ea    | 13        | 4.15%   |
| 0x6fd      | 11        | 3.51%   |
| 0x306c3    | 11        | 3.51%   |
| 0x406e3    | 10        | 3.19%   |
| 0x20655    | 9         | 2.88%   |
| 0x10676    | 9         | 2.88%   |
| 0x906ea    | 8         | 2.56%   |
| 0x806ec    | 7         | 2.24%   |
| 0x806e9    | 7         | 2.24%   |
| 0x806c1    | 6         | 1.92%   |
| 0x506e3    | 5         | 1.6%    |
| 0x40651    | 5         | 1.6%    |
| 0x30678    | 5         | 1.6%    |
| 0x20652    | 5         | 1.6%    |
| 0x506c9    | 4         | 1.28%   |
| 0x306d4    | 4         | 1.28%   |
| 0x08108102 | 4         | 1.28%   |
| 0x07030105 | 4         | 1.28%   |
| 0x06006705 | 4         | 1.28%   |
| 0x906ed    | 3         | 0.96%   |
| 0x906e9    | 3         | 0.96%   |
| 0x6d8      | 3         | 0.96%   |
| 0x08608103 | 3         | 0.96%   |
| 0x08600106 | 3         | 0.96%   |
| 0x05000119 | 3         | 0.96%   |
| 0xa0652    | 2         | 0.64%   |
| 0x706a8    | 2         | 0.64%   |
| 0x706a1    | 2         | 0.64%   |
| 0x6f6      | 2         | 0.64%   |
| 0x6f2      | 2         | 0.64%   |
| 0x6ec      | 2         | 0.64%   |
| 0x6e8      | 2         | 0.64%   |
| 0x406c3    | 2         | 0.64%   |
| 0x30673    | 2         | 0.64%   |
| 0x106ca    | 2         | 0.64%   |
| 0x10661    | 2         | 0.64%   |
| 0x0a50000c | 2         | 0.64%   |
| 0x06006704 | 2         | 0.64%   |
| 0x06001119 | 2         | 0.64%   |
| 0x02000032 | 2         | 0.64%   |
| 0xa0660    | 1         | 0.32%   |
| 0x806eb    | 1         | 0.32%   |
| 0x706e5    | 1         | 0.32%   |
| 0x6fb      | 1         | 0.32%   |
| 0x40661    | 1         | 0.32%   |
| 0x30661    | 1         | 0.32%   |
| 0x106e5    | 1         | 0.32%   |
| 0x106c2    | 1         | 0.32%   |
| 0x08608102 | 1         | 0.32%   |
| 0x08600104 | 1         | 0.32%   |
| 0x08600103 | 1         | 0.32%   |
| 0x08108109 | 1         | 0.32%   |
| 0x0810100b | 1         | 0.32%   |
| 0x0700010f | 1         | 0.32%   |
| 0x0600611a | 1         | 0.32%   |
| 0x0600111f | 1         | 0.32%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 45        | 14.56%  |
| IvyBridge       | 36        | 11.65%  |
| SandyBridge     | 29        | 9.39%   |
| Penryn          | 26        | 8.41%   |
| Haswell         | 22        | 7.12%   |
| Core            | 20        | 6.47%   |
| Skylake         | 17        | 5.5%    |
| Westmere        | 16        | 5.18%   |
| Silvermont      | 10        | 3.24%   |
| K8 Hammer       | 8         | 2.59%   |
| P6              | 7         | 2.27%   |
| Excavator       | 7         | 2.27%   |
| TigerLake       | 6         | 1.94%   |
| Zen+            | 5         | 1.62%   |
| Zen 2           | 5         | 1.62%   |
| Broadwell       | 5         | 1.62%   |
| Unknown         | 5         | 1.62%   |
| Zen 3           | 4         | 1.29%   |
| Puma            | 4         | 1.29%   |
| Goldmont plus   | 4         | 1.29%   |
| Goldmont        | 4         | 1.29%   |
| Bonnell         | 4         | 1.29%   |
| Bobcat          | 4         | 1.29%   |
| Piledriver      | 3         | 0.97%   |
| K8 & K10 hybrid | 3         | 0.97%   |
| CometLake       | 3         | 0.97%   |
| Zen             | 2         | 0.65%   |
| Nehalem         | 1         | 0.32%   |
| K10 Llano       | 1         | 0.32%   |
| K10             | 1         | 0.32%   |
| Jaguar          | 1         | 0.32%   |
| IceLake         | 1         | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 217       | 56.81%  |
| Nvidia                           | 91        | 23.82%  |
| AMD                              | 72        | 18.85%  |
| Silicon Integrated Systems [SiS] | 2         | 0.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 33        | 8.11%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25        | 6.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 3.44%   |
| Intel UHD Graphics 620                                                                   | 13        | 3.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 2.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 2.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 2.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 2.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 2.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.21%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 1.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.72%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 1.47%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.47%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 6         | 1.47%   |
| Intel HD Graphics 620                                                                    | 6         | 1.47%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 1.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.23%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 1.23%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.23%   |
| Nvidia GK208M [GeForce GT 720M]                                                          | 4         | 0.98%   |
| Intel HD Graphics 530                                                                    | 4         | 0.98%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 0.98%   |
| AMD Renoir                                                                               | 4         | 0.98%   |
| AMD Lucienne                                                                             | 4         | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.74%   |
| Intel HD Graphics 630                                                                    | 3         | 0.74%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.74%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 0.74%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 3         | 0.74%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.74%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                | 3         | 0.74%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.74%   |
| AMD Cezanne                                                                              | 3         | 0.74%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 2         | 0.49%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.49%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.49%   |
| Nvidia MCP79 [GeForce 8200M G]                                                           | 2         | 0.49%   |
| Nvidia GT218M [GeForce 315M]                                                             | 2         | 0.49%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.49%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.49%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.49%   |
| Nvidia GM107GLM [Quadro M2000M]                                                          | 2         | 0.49%   |
| Nvidia GF119M [GeForce 410M]                                                             | 2         | 0.49%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 2         | 0.49%   |
| Nvidia GF108M [GeForce GT 635M]                                                          | 2         | 0.49%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.49%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.49%   |
| Nvidia G98M [Quadro NVS 160M]                                                            | 2         | 0.49%   |
| Nvidia G98M [GeForce G 105M]                                                             | 2         | 0.49%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 2         | 0.49%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 0.49%   |
| Intel HD Graphics 510                                                                    | 2         | 0.49%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.49%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 146       | 47.1%   |
| Intel + Nvidia | 59        | 19.03%  |
| 1 x AMD        | 50        | 16.13%  |
| 1 x Nvidia     | 31        | 10%     |
| Intel + AMD    | 13        | 4.19%   |
| 2 x AMD        | 8         | 2.58%   |
| 1 x SiS        | 2         | 0.65%   |
| AMD + Nvidia   | 1         | 0.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 271       | 87.14%  |
| Proprietary | 30        | 9.65%   |
| Unknown     | 10        | 3.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 148       | 47.28%  |
| 0.01-0.5   | 65        | 20.77%  |
| 1.01-2.0   | 51        | 16.29%  |
| 0.51-1.0   | 25        | 7.99%   |
| 3.01-4.0   | 18        | 5.75%   |
| 5.01-6.0   | 3         | 0.96%   |
| 2.01-3.0   | 2         | 0.64%   |
| 7.01-8.0   | 1         | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 69        | 19.94%  |
| LG Display              | 56        | 16.18%  |
| Chimei Innolux          | 42        | 12.14%  |
| Samsung Electronics     | 41        | 11.85%  |
| BOE                     | 27        | 7.8%    |
| Chi Mei Optoelectronics | 22        | 6.36%   |
| Lenovo                  | 12        | 3.47%   |
| Dell                    | 11        | 3.18%   |
| Philips                 | 8         | 2.31%   |
| PANDA                   | 7         | 2.02%   |
| LG Philips              | 7         | 2.02%   |
| Sharp                   | 5         | 1.45%   |
| Hewlett-Packard         | 5         | 1.45%   |
| Apple                   | 5         | 1.45%   |
| Acer                    | 3         | 0.87%   |
| HannStar                | 2         | 0.58%   |
| Goldstar                | 2         | 0.58%   |
| CSO                     | 2         | 0.58%   |
| CPT                     | 2         | 0.58%   |
| AOC                     | 2         | 0.58%   |
| Ancor Communications    | 2         | 0.58%   |
| ViewSonic               | 1         | 0.29%   |
| Sony                    | 1         | 0.29%   |
| Seiko/Epson             | 1         | 0.29%   |
| Quanta Display          | 1         | 0.29%   |
| Plain Tree Systems      | 1         | 0.29%   |
| Panasonic               | 1         | 0.29%   |
| LGD                     | 1         | 0.29%   |
| InnoLux Display         | 1         | 0.29%   |
| InfoVision              | 1         | 0.29%   |
| Iiyama                  | 1         | 0.29%   |
| Fujitsu Siemens         | 1         | 0.29%   |
| BenQ                    | 1         | 0.29%   |
| ASUSTek Computer        | 1         | 0.29%   |
| ANX                     | 1         | 0.29%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch           | 6         | 1.71%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 5         | 1.43%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 4         | 1.14%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch  | 4         | 1.14%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 4         | 1.14%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 340x190mm 15.3-inch      | 3         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 0.86%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x194mm 15.5-inch  | 3         | 0.86%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 3         | 0.86%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch            | 3         | 0.86%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 3         | 0.86%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch      | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch      | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3859 1366x768 293x165mm 13.2-inch      | 2         | 0.57%   |
| Samsung Electronics LCD Monitor SEC3051 1366x768 344x194mm 15.5-inch      | 2         | 0.57%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                   | 2         | 0.57%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch               | 2         | 0.57%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch               | 2         | 0.57%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch               | 2         | 0.57%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch              | 2         | 0.57%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch               | 2         | 0.57%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 0.57%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch               | 2         | 0.57%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch               | 2         | 0.57%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 597x336mm 27.0-inch                  | 2         | 0.57%   |
| Lenovo LCD Monitor LEN40E0 1366x768 277x156mm 12.5-inch                   | 2         | 0.57%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                   | 2         | 0.57%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                     | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 2         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch           | 2         | 0.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO1726 1920x1080 381x214mm 17.2-inch | 2         | 0.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch  | 2         | 0.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO1554 1280x800 331x207mm 15.4-inch  | 2         | 0.57%   |
| BOE LCD Monitor BOE07BB 1920x1080 309x173mm 13.9-inch                     | 2         | 0.57%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 2         | 0.57%   |
| BOE LCD Monitor BOE06B3 1920x1080                                         | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO31EC 1366x768 344x193mm 15.5-inch             | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch             | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch             | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch             | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 2         | 0.57%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 2         | 0.57%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch                 | 1         | 0.29%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                     | 1         | 0.29%   |
| Sharp LQ173M1JW03 SHP14DC 1920x1080 382x215mm 17.3-inch                   | 1         | 0.29%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch                   | 1         | 0.29%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch                   | 1         | 0.29%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 1         | 0.29%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                   | 1         | 0.29%   |
| Seiko/Epson LCD Monitor 1280x800                                          | 1         | 0.29%   |
| Samsung Electronics T24E390 SAM0C1F 1920x1080 521x293mm 23.5-inch         | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM05CB 1920x1080 530x300mm 24.0-inch      | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM03F2 1680x1050                          | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM030F 1680x1050 474x296mm 22.0-inch      | 1         | 0.29%   |
| Samsung Electronics SyncMaster SAM0225 1440x900 410x257mm 19.1-inch       | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 112       | 33.94%  |
| 1920x1080 (FHD)    | 111       | 33.64%  |
| 1280x800 (WXGA)    | 31        | 9.39%   |
| 1600x900 (HD+)     | 21        | 6.36%   |
| 1440x900 (WXGA+)   | 11        | 3.33%   |
| 2560x1440 (QHD)    | 9         | 2.73%   |
| 3840x2160 (4K)     | 7         | 2.12%   |
| 1680x1050 (WSXGA+) | 7         | 2.12%   |
| 1920x1200 (WUXGA)  | 5         | 1.52%   |
| 1024x600           | 4         | 1.21%   |
| 2880x1800          | 3         | 0.91%   |
| 3440x1440          | 2         | 0.61%   |
| 800x1280           | 1         | 0.3%    |
| 3200x1800 (QHD+)   | 1         | 0.3%    |
| 2560x1600          | 1         | 0.3%    |
| 2560x1080          | 1         | 0.3%    |
| 1280x720 (HD)      | 1         | 0.3%    |
| 1280x1024 (SXGA)   | 1         | 0.3%    |
| 1024x768 (XGA)     | 1         | 0.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 170       | 48.99%  |
| 13      | 36        | 10.37%  |
| 14      | 34        | 9.8%    |
| 17      | 18        | 5.19%   |
| 24      | 12        | 3.46%   |
| 12      | 12        | 3.46%   |
| 23      | 10        | 2.88%   |
| 27      | 8         | 2.31%   |
| 11      | 8         | 2.31%   |
| 18      | 7         | 2.02%   |
| 22      | 5         | 1.44%   |
| Unknown | 5         | 1.44%   |
| 10      | 4         | 1.15%   |
| 34      | 3         | 0.86%   |
| 31      | 3         | 0.86%   |
| 21      | 2         | 0.58%   |
| 20      | 2         | 0.58%   |
| 19      | 2         | 0.58%   |
| 84      | 1         | 0.29%   |
| 54      | 1         | 0.29%   |
| 50      | 1         | 0.29%   |
| 33      | 1         | 0.29%   |
| 25      | 1         | 0.29%   |
| 16      | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 221       | 64.24%  |
| 201-300     | 40        | 11.63%  |
| 501-600     | 27        | 7.85%   |
| 351-400     | 23        | 6.69%   |
| 401-500     | 17        | 4.94%   |
| Unknown     | 5         | 1.45%   |
| 701-800     | 4         | 1.16%   |
| 601-700     | 4         | 1.16%   |
| 1001-1500   | 2         | 0.58%   |
| 1501-2000   | 1         | 0.29%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 245       | 78.27%  |
| 16/10   | 57        | 18.21%  |
| 21/9    | 3         | 0.96%   |
| Unknown | 3         | 0.96%   |
| 3/2     | 2         | 0.64%   |
| 5/4     | 1         | 0.32%   |
| 4/3     | 1         | 0.32%   |
| 0.62    | 1         | 0.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 168       | 48.7%   |
| 81-90          | 56        | 16.23%  |
| 201-250        | 24        | 6.96%   |
| 71-80          | 14        | 4.06%   |
| 61-70          | 12        | 3.48%   |
| 121-130        | 12        | 3.48%   |
| 51-60          | 8         | 2.32%   |
| 301-350        | 8         | 2.32%   |
| 351-500        | 7         | 2.03%   |
| 151-200        | 6         | 1.74%   |
| 141-150        | 6         | 1.74%   |
| 131-140        | 5         | 1.45%   |
| Unknown        | 5         | 1.45%   |
| 41-50          | 4         | 1.16%   |
| 251-300        | 4         | 1.16%   |
| More than 1000 | 3         | 0.87%   |
| 91-100         | 2         | 0.58%   |
| 111-120        | 1         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 123       | 36.39%  |
| 101-120       | 105       | 31.07%  |
| 51-100        | 86        | 25.44%  |
| More than 240 | 8         | 2.37%   |
| 161-240       | 8         | 2.37%   |
| Unknown       | 5         | 1.48%   |
| 1-50          | 3         | 0.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 245       | 78.53%  |
| 2     | 54        | 17.31%  |
| 0     | 10        | 3.21%   |
| 3     | 3         | 0.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 160       | 30.42%  |
| Realtek Semiconductor             | 157       | 29.85%  |
| Qualcomm Atheros                  | 99        | 18.82%  |
| Broadcom                          | 36        | 6.84%   |
| Marvell Technology Group          | 13        | 2.47%   |
| Ralink                            | 10        | 1.9%    |
| Broadcom Limited                  | 9         | 1.71%   |
| Nvidia                            | 6         | 1.14%   |
| Ralink Technology                 | 3         | 0.57%   |
| Qualcomm Atheros Communications   | 3         | 0.57%   |
| Hewlett-Packard                   | 3         | 0.57%   |
| Ericsson Business Mobile Networks | 3         | 0.57%   |
| DisplayLink                       | 3         | 0.57%   |
| Sierra Wireless                   | 2         | 0.38%   |
| MediaTek                          | 2         | 0.38%   |
| Lenovo                            | 2         | 0.38%   |
| JMicron Technology                | 2         | 0.38%   |
| Huawei Technologies               | 2         | 0.38%   |
| Fibocom                           | 2         | 0.38%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.19%   |
| Xiaomi                            | 1         | 0.19%   |
| TP-Link                           | 1         | 0.19%   |
| T & A Mobile Phones               | 1         | 0.19%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.19%   |
| Sigma Sport                       | 1         | 0.19%   |
| Nokia Mobile Phones               | 1         | 0.19%   |
| Attansic Technology               | 1         | 0.19%   |
| ASIX Electronics                  | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 99        | 15.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 32        | 5.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 27        | 4.36%   |
| Intel Wireless 8265 / 8275                                              | 17        | 2.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 2.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 15        | 2.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 2.26%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 1.62%   |
| Intel Wireless 7260                                                     | 10        | 1.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 9         | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 1.45%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 1.45%   |
| Intel Wireless 8260                                                     | 8         | 1.29%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 1.29%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 7         | 1.13%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.13%   |
| Intel Wireless 3165                                                     | 7         | 1.13%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 1.13%   |
| Intel WiFi Link 5100                                                    | 6         | 0.97%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 0.97%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.81%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 5         | 0.81%   |
| Intel Wireless-AC 9260                                                  | 5         | 0.81%   |
| Intel Wireless 7265                                                     | 5         | 0.81%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 0.81%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 0.81%   |
| Intel Ethernet Connection (7) I219-LM                                   | 5         | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.81%   |
| Intel Centrino Wireless-N 2230                                          | 5         | 0.81%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.81%   |
| Intel 82567LM Gigabit Network Connection                                | 5         | 0.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4         | 0.65%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 4         | 0.65%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.65%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                   | 4         | 0.65%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 0.65%   |
| Intel Ethernet Connection I219-LM                                       | 4         | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 0.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.65%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 0.65%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 4         | 0.65%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 3         | 0.48%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 3         | 0.48%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 3         | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 3         | 0.48%   |
| Nvidia MCP79 Ethernet                                                   | 3         | 0.48%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 0.48%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.48%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.48%   |
| Intel Ethernet Connection I217-V                                        | 3         | 0.48%   |
| Intel Ethernet Connection (4) I219-V                                    | 3         | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                                   | 3         | 0.48%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 0.48%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 3         | 0.48%   |
| HP hs2350 HSPA+ MobileBroadband                                         | 3         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 149       | 47.3%   |
| Qualcomm Atheros                | 82        | 26.03%  |
| Realtek Semiconductor           | 29        | 9.21%   |
| Broadcom                        | 26        | 8.25%   |
| Ralink                          | 10        | 3.17%   |
| Broadcom Limited                | 7         | 2.22%   |
| Ralink Technology               | 3         | 0.95%   |
| Qualcomm Atheros Communications | 3         | 0.95%   |
| Sierra Wireless                 | 2         | 0.63%   |
| MediaTek                        | 2         | 0.63%   |
| TP-Link                         | 1         | 0.32%   |
| Fibocom                         | 1         | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 27        | 8.54%   |
| Intel Wireless 8265 / 8275                                                    | 17        | 5.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 15        | 4.75%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 14        | 4.43%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 10        | 3.16%   |
| Intel Wireless 7260                                                           | 10        | 3.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 9         | 2.85%   |
| Intel Wi-Fi 6 AX200                                                           | 9         | 2.85%   |
| Intel Wireless 8260                                                           | 8         | 2.53%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 8         | 2.53%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 7         | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 7         | 2.22%   |
| Intel Wireless 3165                                                           | 7         | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 7         | 2.22%   |
| Intel WiFi Link 5100                                                          | 6         | 1.9%    |
| Broadcom BCM43142 802.11b/g/n                                                 | 6         | 1.9%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 5         | 1.58%   |
| Intel Wireless-AC 9260                                                        | 5         | 1.58%   |
| Intel Wireless 7265                                                           | 5         | 1.58%   |
| Intel Wi-Fi 6 AX201                                                           | 5         | 1.58%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 5         | 1.58%   |
| Intel Centrino Wireless-N 2230                                                | 5         | 1.58%   |
| Intel Centrino Ultimate-N 6300                                                | 5         | 1.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 5         | 1.58%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 4         | 1.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 4         | 1.27%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 4         | 1.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 4         | 1.27%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 4         | 1.27%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 4         | 1.27%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 3         | 0.95%   |
| Qualcomm Atheros AR9271 802.11n                                               | 3         | 0.95%   |
| Intel Ultimate N WiFi Link 5300                                               | 3         | 0.95%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 3         | 0.95%   |
| Intel Centrino Advanced-N 6235                                                | 3         | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 3         | 0.95%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                      | 2         | 0.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2         | 0.63%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 0.63%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                    | 2         | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 2         | 0.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 2         | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 2         | 0.63%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 2         | 0.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                 | 2         | 0.63%   |
| Intel Wireless 3160                                                           | 2         | 0.63%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 2         | 0.63%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 2         | 0.63%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller   | 2         | 0.63%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 2         | 0.63%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 2         | 0.63%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 2         | 0.63%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                           | 1         | 0.32%   |
| Sierra Wireless EM7345 4G LTE                                                 | 1         | 0.32%   |
| Sierra Wireless EM7305 Modem                                                  | 1         | 0.32%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 1         | 0.32%   |
| Realtek RTL8723AU 802.11n WLAN Adapter                                        | 1         | 0.32%   |
| Realtek RTL8192SE Wireless LAN Controller                                     | 1         | 0.32%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                        | 1         | 0.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 146       | 50.87%  |
| Intel                    | 68        | 23.69%  |
| Qualcomm Atheros         | 26        | 9.06%   |
| Marvell Technology Group | 13        | 4.53%   |
| Broadcom                 | 12        | 4.18%   |
| Nvidia                   | 6         | 2.09%   |
| DisplayLink              | 3         | 1.05%   |
| Lenovo                   | 2         | 0.7%    |
| JMicron Technology       | 2         | 0.7%    |
| Broadcom Limited         | 2         | 0.7%    |
| Xiaomi                   | 1         | 0.35%   |
| T & A Mobile Phones      | 1         | 0.35%   |
| Nokia Mobile Phones      | 1         | 0.35%   |
| Huawei Technologies      | 1         | 0.35%   |
| Fibocom                  | 1         | 0.35%   |
| Attansic Technology      | 1         | 0.35%   |
| ASIX Electronics         | 1         | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 99        | 34.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 32        | 11.03%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 15        | 5.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 9         | 3.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 7         | 2.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 1.72%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 5         | 1.72%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.72%   |
| Intel Ethernet Connection (7) I219-LM                                          | 5         | 1.72%   |
| Intel 82567LM Gigabit Network Connection                                       | 5         | 1.72%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 4         | 1.38%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 4         | 1.38%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 1.38%   |
| Intel Ethernet Connection (4) I219-LM                                          | 4         | 1.38%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 1.03%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 3         | 1.03%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 1.03%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 1.03%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.03%   |
| Intel Ethernet Connection I217-V                                               | 3         | 1.03%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 1.03%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.69%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 2         | 0.69%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 2         | 0.69%   |
| Nvidia MCP77 Ethernet                                                          | 2         | 0.69%   |
| Lenovo USB-C Dock Ethernet                                                     | 2         | 0.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.69%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.69%   |
| Intel Ethernet Connection (6) I219-V                                           | 2         | 0.69%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 0.69%   |
| DisplayLink USB-C Hybrid UHD Video Dock                                        | 2         | 0.69%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 2         | 0.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.69%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.34%   |
| T & A Mobile Phones TCL 30                                                     | 1         | 0.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.34%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1         | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.34%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.34%   |
| Nokia Mobile Phones N900 (PC-Suite Mode)                                       | 1         | 0.34%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.34%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.34%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.34%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.34%   |
| Intel PRO/100 VE Network Connection                                            | 1         | 0.34%   |
| Intel Ethernet Connection (6) I219-LM                                          | 1         | 0.34%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.34%   |
| Intel Ethernet Connection (3) I218-LM                                          | 1         | 0.34%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.34%   |
| Intel Ethernet Connection (13) I219-LM                                         | 1         | 0.34%   |
| Intel Ethernet Connection (11) I219-LM                                         | 1         | 0.34%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.34%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.34%   |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.34%   |
| Intel 82562GT 10/100 Network Connection                                        | 1         | 0.34%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile           | 1         | 0.34%   |
| Huawei LYA-L09                                                                 | 1         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 305       | 51.35%  |
| Ethernet | 276       | 46.46%  |
| Modem    | 13        | 2.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 252       | 77.06%  |
| Ethernet | 75        | 22.94%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 262       | 84.79%  |
| 1     | 40        | 12.94%  |
| 0     | 5         | 1.62%   |
| 3     | 2         | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 293       | 94.52%  |
| Yes  | 17        | 5.48%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 89        | 39.56%  |
| Qualcomm Atheros Communications | 21        | 9.33%   |
| Broadcom                        | 18        | 8%      |
| IMC Networks                    | 15        | 6.67%   |
| Realtek Semiconductor           | 14        | 6.22%   |
| Lite-On Technology              | 11        | 4.89%   |
| Foxconn / Hon Hai               | 9         | 4%      |
| Ralink                          | 7         | 3.11%   |
| Hewlett-Packard                 | 7         | 3.11%   |
| Dell                            | 7         | 3.11%   |
| ASUSTek Computer                | 7         | 3.11%   |
| Toshiba                         | 5         | 2.22%   |
| Cambridge Silicon Radio         | 5         | 2.22%   |
| Foxconn International           | 3         | 1.33%   |
| Apple                           | 3         | 1.33%   |
| Taiyo Yuden                     | 2         | 0.89%   |
| Micro Star International        | 1         | 0.44%   |
| Alps Electric                   | 1         | 0.44%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 47        | 20.89%  |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 13        | 5.78%   |
| Intel AX201 Bluetooth                                                               | 13        | 5.78%   |
| Intel AX200 Bluetooth                                                               | 9         | 4%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 3.56%   |
| Ralink RT3290 Bluetooth                                                             | 7         | 3.11%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 3.11%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 7         | 3.11%   |
| Realtek Bluetooth Radio                                                             | 6         | 2.67%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 2.67%   |
| IMC Networks Bluetooth Device                                                       | 5         | 2.22%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 5         | 2.22%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 2.22%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 5         | 2.22%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 1.78%   |
| Lite-On Bluetooth Device                                                            | 4         | 1.78%   |
| Intel Bluetooth Device                                                              | 4         | 1.78%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 1.78%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 1.78%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 3         | 1.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.33%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 3         | 1.33%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 3         | 1.33%   |
| Toshiba Integrated Bluetooth HCI                                                    | 2         | 0.89%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)                                             | 2         | 0.89%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 0.89%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 0.89%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 0.89%   |
| Broadcom HP Portable Bumble Bee                                                     | 2         | 0.89%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.89%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 0.89%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.44%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.44%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.44%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.44%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.44%   |
| Micro Star International Bluetooth EDR Device                                       | 1         | 0.44%   |
| Lite-On Wireless_Device                                                             | 1         | 0.44%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.44%   |
| Lite-On Bluetooth 4.0 [Broadcom BCM20702A0]                                         | 1         | 0.44%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.44%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.44%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.44%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.44%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                                          | 1         | 0.44%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.44%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.44%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 1         | 0.44%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.44%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.44%   |
| Dell Wireless 365 Bluetooth                                                         | 1         | 0.44%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.44%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.44%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.44%   |
| Broadcom HP Portable Valentine                                                      | 1         | 0.44%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.44%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 1         | 0.44%   |
| Broadcom BCM2045 Bluetooth                                                          | 1         | 0.44%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 246       | 65.95%  |
| AMD                              | 63        | 16.89%  |
| Nvidia                           | 41        | 10.99%  |
| C-Media Electronics              | 4         | 1.07%   |
| Silicon Integrated Systems [SiS] | 3         | 0.8%    |
| Samson Technologies              | 2         | 0.54%   |
| Lenovo                           | 2         | 0.54%   |
| GN Netcom                        | 2         | 0.54%   |
| Textech International            | 1         | 0.27%   |
| Texas Instruments                | 1         | 0.27%   |
| Realtek Semiconductor            | 1         | 0.27%   |
| Plantronics                      | 1         | 0.27%   |
| Logitech                         | 1         | 0.27%   |
| JMTek                            | 1         | 0.27%   |
| Hewlett-Packard                  | 1         | 0.27%   |
| Focusrite-Novation               | 1         | 0.27%   |
| Behringer.......                 | 1         | 0.27%   |
| AKAI Professional M.I.           | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 44        | 10.07%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 32        | 7.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 21        | 4.81%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 4.58%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 19        | 4.35%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 17        | 3.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 17        | 3.89%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 3.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 2.97%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 12        | 2.75%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 2.52%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 2.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 2.29%   |
| AMD FCH Azalia Controller                                                                         | 10        | 2.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 1.6%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.6%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.37%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 1.37%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.37%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 1.37%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 1.37%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.37%   |
| AMD High Definition Audio Controller                                                              | 6         | 1.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.14%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.14%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 0.92%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.92%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.69%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.69%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 0.69%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.69%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.69%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.46%   |
| Samson Technologies Meteor condenser microphone                                                   | 2         | 0.46%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 0.46%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.46%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 0.46%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.46%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.46%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.46%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.46%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 2         | 0.46%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 2         | 0.46%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.46%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 2         | 0.46%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.46%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.46%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 2         | 0.46%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 2         | 0.46%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 2         | 0.46%   |
| Textech International MIDI Interface cable                                                        | 1         | 0.23%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.23%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 1         | 0.23%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.23%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 48        | 22.86%  |
| SK hynix            | 47        | 22.38%  |
| Kingston            | 28        | 13.33%  |
| Unknown             | 26        | 12.38%  |
| Micron Technology   | 25        | 11.9%   |
| Ramaxel Technology  | 6         | 2.86%   |
| Crucial             | 6         | 2.86%   |
| Elpida              | 5         | 2.38%   |
| Unknown (ABCD)      | 3         | 1.43%   |
| Patriot             | 3         | 1.43%   |
| Corsair             | 3         | 1.43%   |
| A-DATA Technology   | 3         | 1.43%   |
| Nanya Technology    | 2         | 0.95%   |
| Unigen              | 1         | 0.48%   |
| SHARETRONIC         | 1         | 0.48%   |
| Atermiter           | 1         | 0.48%   |
| ASint Technology    | 1         | 0.48%   |
| Apacer              | 1         | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 6         | 2.63%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 1.75%   |
| Micron RAM MT8KTF51264HZ-1G6 4GB SODIMM DDR3 1600MT/s            | 4         | 1.75%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 3         | 1.32%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.32%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.32%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.32%   |
| Patriot RAM PSD34G16002S 4GB SODIMM DDR3 1600MT/s                | 3         | 1.32%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 3         | 1.32%   |
| Kingston RAM KHX1866C11S3L/8G 8GB SODIMM DDR3 1867MT/s           | 3         | 1.32%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.88%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 2         | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.88%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.88%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.88%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.88%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.88%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s            | 2         | 0.88%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.88%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 2         | 0.88%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.88%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 0.88%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 2         | 0.88%   |
| Samsung RAM M4 70T5663QZ3-CF7 2048MB SODIMM DDR2 2048MT/s        | 2         | 0.88%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 2         | 0.88%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s           | 2         | 0.88%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s            | 2         | 0.88%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 2         | 0.88%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s          | 2         | 0.88%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.44%   |
| Unknown RAM Module 4GB SODIMM 800MT/s                            | 1         | 0.44%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 0.44%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                     | 1         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR2 333MT/s                    | 1         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM 667MT/s                         | 1         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM 533MT/s                         | 1         | 0.44%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.44%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.44%   |
| Unknown RAM Module 1024MB SODIMM DRAM 667MT/s                    | 1         | 0.44%   |
| Unknown RAM Module 1024MB SODIMM DDR3 1066MT/s                   | 1         | 0.44%   |
| Unknown RAM Module 1024MB SODIMM DDR2 333MT/s                    | 1         | 0.44%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 0.44%   |
| Unknown RAM Module 1024MB SODIMM 667MT/s                         | 1         | 0.44%   |
| Unknown RAM Module 1024MB Chip DDR 533MT/s                       | 1         | 0.44%   |
| Unigen RAM UG25T640xM8SU-8C 2048MB SODIMM DDR 667MT/s            | 1         | 0.44%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                     | 1         | 0.44%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.44%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s                  | 1         | 0.44%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 1         | 0.44%   |
| SK hynix RAM Module 4096MB SODIMM DDR4 2133MT/s                  | 1         | 0.44%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.44%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 1         | 0.44%   |
| SK hynix RAM HYMP564S64CP6-Y5 512MB SODIMM DDR 667MT/s           | 1         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 67        | 40.36%  |
| DDR4    | 53        | 31.93%  |
| DDR2    | 18        | 10.84%  |
| LPDDR4  | 9         | 5.42%   |
| SDRAM   | 8         | 4.82%   |
| Unknown | 5         | 3.01%   |
| LPDDR3  | 3         | 1.81%   |
| DDR     | 2         | 1.2%    |
| DRAM    | 1         | 0.6%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 157       | 94.58%  |
| Row Of Chips | 7         | 4.22%   |
| Chip         | 2         | 1.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 63        | 32.81%  |
| 8192  | 50        | 26.04%  |
| 2048  | 41        | 21.35%  |
| 16384 | 20        | 10.42%  |
| 1024  | 15        | 7.81%   |
| 512   | 2         | 1.04%   |
| 32768 | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 49        | 26.49%  |
| 2667    | 26        | 14.05%  |
| 3200    | 14        | 7.57%   |
| 667     | 13        | 7.03%   |
| 2400    | 12        | 6.49%   |
| 2133    | 11        | 5.95%   |
| 1333    | 9         | 4.86%   |
| 1334    | 8         | 4.32%   |
| Unknown | 8         | 4.32%   |
| 2048    | 5         | 2.7%    |
| 800     | 5         | 2.7%    |
| 1067    | 4         | 2.16%   |
| 4199    | 3         | 1.62%   |
| 1867    | 3         | 1.62%   |
| 8400    | 2         | 1.08%   |
| 4267    | 2         | 1.08%   |
| 4266    | 2         | 1.08%   |
| 3266    | 2         | 1.08%   |
| 533     | 2         | 1.08%   |
| 4800    | 1         | 0.54%   |
| 1639    | 1         | 0.54%   |
| 1066    | 1         | 0.54%   |
| 975     | 1         | 0.54%   |
| 333     | 1         | 0.54%   |

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
| Chicony Electronics                    | 91        | 34.87%  |
| Realtek Semiconductor                  | 23        | 8.81%   |
| Acer                                   | 23        | 8.81%   |
| IMC Networks                           | 21        | 8.05%   |
| Microdia                               | 20        | 7.66%   |
| Sunplus Innovation Technology          | 15        | 5.75%   |
| Suyin                                  | 13        | 4.98%   |
| Syntek                                 | 10        | 3.83%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 3.45%   |
| Quanta                                 | 6         | 2.3%    |
| Lite-On Technology                     | 5         | 1.92%   |
| Ricoh                                  | 3         | 1.15%   |
| Logitech                               | 3         | 1.15%   |
| Alcor Micro                            | 3         | 1.15%   |
| Samsung Electronics                    | 2         | 0.77%   |
| Luxvisions Innotech Limited            | 2         | 0.77%   |
| Apple                                  | 2         | 0.77%   |
| Z-Star Microelectronics                | 1         | 0.38%   |
| Primax Electronics                     | 1         | 0.38%   |
| OmniVision Technologies                | 1         | 0.38%   |
| LG Electronics                         | 1         | 0.38%   |
| Lenovo                                 | 1         | 0.38%   |
| Importek                               | 1         | 0.38%   |
| icSpring                               | 1         | 0.38%   |
| GEMBIRD                                | 1         | 0.38%   |
| Elecom                                 | 1         | 0.38%   |
| ALi                                    | 1         | 0.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 20        | 7.63%   |
| Microdia Integrated_Webcam_HD                               | 10        | 3.82%   |
| Realtek USB2.0 HD UVC WebCam                                | 7         | 2.67%   |
| Sunplus Integrated_Webcam_HD                                | 6         | 2.29%   |
| IMC Networks Integrated Camera                              | 6         | 2.29%   |
| Chicony HP HD Webcam [Fixed]                                | 6         | 2.29%   |
| Chicony HD WebCam                                           | 6         | 2.29%   |
| Acer Lenovo EasyCamera                                      | 6         | 2.29%   |
| Acer EasyCamera                                             | 5         | 1.91%   |
| Syntek Integrated Camera                                    | 4         | 1.53%   |
| Realtek Integrated_Webcam_HD                                | 4         | 1.53%   |
| Quanta HP HD Camera                                         | 4         | 1.53%   |
| Microdia Integrated Webcam                                  | 4         | 1.53%   |
| Lite-On HP HD Camera                                        | 4         | 1.53%   |
| Chicony USB2.0 VGA UVC WebCam                               | 4         | 1.53%   |
| Chicony USB 2.0 Camera                                      | 4         | 1.53%   |
| Syntek Lenovo EasyCamera                                    | 3         | 1.15%   |
| Suyin HP Webcam                                             | 3         | 1.15%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 3         | 1.15%   |
| Sunplus HP HD Webcam [Fixed]                                | 3         | 1.15%   |
| IMC Networks Integrated Webcam                              | 3         | 1.15%   |
| Chicony USB2.0 HD UVC WebCam                                | 3         | 1.15%   |
| Chicony USB2.0 0.3M UVC WebCam                              | 3         | 1.15%   |
| Chicony TOSHIBA Web Camera - HD                             | 3         | 1.15%   |
| Chicony Thinkpad T430 camera                                | 3         | 1.15%   |
| Chicony Lenovo EasyCamera                                   | 3         | 1.15%   |
| Chicony CNF9055 Toshiba Webcam                              | 3         | 1.15%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 3         | 1.15%   |
| Acer Lenovo Integrated Webcam                               | 3         | 1.15%   |
| Acer Integrated Camera                                      | 3         | 1.15%   |
| Syntek EasyCamera                                           | 2         | 0.76%   |
| Suyin Sony Visual Communication Camera                      | 2         | 0.76%   |
| Sunplus HD WebCam                                           | 2         | 0.76%   |
| Samsung Galaxy A5 (MTP)                                     | 2         | 0.76%   |
| Ricoh Integrated Webcam                                     | 2         | 0.76%   |
| Realtek Lenovo EasyCamera                                   | 2         | 0.76%   |
| Realtek HD WebCam                                           | 2         | 0.76%   |
| Microdia Amcrest AWC2198 USB Webcam                         | 2         | 0.76%   |
| Logitech Fujitsu Webcam                                     | 2         | 0.76%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 2         | 0.76%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 0.76%   |
| IMC Networks 2M Integrated Webcam                           | 2         | 0.76%   |
| Chicony WebCam                                              | 2         | 0.76%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 0.76%   |
| Chicony HP HD Webcam                                        | 2         | 0.76%   |
| Chicony HP HD Camera                                        | 2         | 0.76%   |
| Chicony HD User Facing                                      | 2         | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101        | 2         | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 2         | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 2         | 0.76%   |
| Acer HP Webcam                                              | 2         | 0.76%   |
| Z-Star Venus USB2.0 Camera                                  | 1         | 0.38%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera                       | 1         | 0.38%   |
| Suyin HP Truevision HD                                      | 1         | 0.38%   |
| Suyin HP Integrated Webcam                                  | 1         | 0.38%   |
| Suyin Acer CrystalEye Webcam                                | 1         | 0.38%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.38%   |
| Suyin 1.3M HD WebCam                                        | 1         | 0.38%   |
| Sunplus Laptop_Integrated_Webcam_HD                         | 1         | 0.38%   |
| Sunplus HP Universal Camera                                 | 1         | 0.38%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 35        | 53.03%  |
| Synaptics                  | 14        | 21.21%  |
| AuthenTec                  | 7         | 10.61%  |
| LighTuning Technology      | 4         | 6.06%   |
| Shenzhen Goodix Technology | 2         | 3.03%   |
| Elan Microelectronics      | 2         | 3.03%   |
| Upek                       | 1         | 1.52%   |
| STMicroelectronics         | 1         | 1.52%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 15.15%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 7.58%   |
| Validity Sensors VFS491                                                    | 4         | 6.06%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 6.06%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 6.06%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 6.06%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 4.55%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 4.55%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 4.55%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 3.03%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 3.03%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.03%   |
| Synaptics  WBDI                                                            | 2         | 3.03%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.03%   |
| AuthenTec AES2810                                                          | 2         | 3.03%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.52%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 1.52%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.52%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.52%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.52%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.52%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.52%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.52%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.52%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.52%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 1.52%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.52%   |
| AuthenTec AES1600                                                          | 1         | 1.52%   |
| Unknown                                                                    | 1         | 1.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 14        | 43.75%  |
| Alcor Micro | 9         | 28.13%  |
| O2 Micro    | 5         | 15.63%  |
| Lenovo      | 2         | 6.25%   |
| BIT4ID      | 2         | 6.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 28.13%  |
| Broadcom 5880                                                                | 5         | 15.63%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 12.5%   |
| Broadcom 58200                                                               | 4         | 12.5%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 9.38%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 6.25%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 6.25%   |
| BIT4ID miniLector EVO                                                        | 2         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 177       | 56.37%  |
| 1     | 108       | 34.39%  |
| 2     | 23        | 7.32%   |
| 3     | 5         | 1.59%   |
| 4     | 1         | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 66        | 39.52%  |
| Chipcard                 | 26        | 15.57%  |
| Graphics card            | 24        | 14.37%  |
| Bluetooth                | 9         | 5.39%   |
| Storage                  | 8         | 4.79%   |
| Multimedia controller    | 7         | 4.19%   |
| Net/wireless             | 6         | 3.59%   |
| Modem                    | 5         | 2.99%   |
| Communication controller | 4         | 2.4%    |
| Card reader              | 3         | 1.8%    |
| Camera                   | 3         | 1.8%    |
| Network                  | 2         | 1.2%    |
| Flash memory             | 2         | 1.2%    |
| Storage/ide              | 1         | 0.6%    |
| Sound                    | 1         | 0.6%    |

