Linux in Vietnam - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Vietnam.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Vietnam/Desktop/README.md) and [notebooks](/Location/Vietnam/Notebook/README.md).

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

Total: 476

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E5430 non-vPro     | Notebook    | [70a0354dba](https://linux-hardware.org/?probe=70a0354dba) | Oct 30, 2022 |
| HP            | 212B                        | Desktop     | [adf4c58f4c](https://linux-hardware.org/?probe=adf4c58f4c) | Oct 22, 2022 |
| Gigabyte      | B360M DS3H                  | Desktop     | [ca57bb441c](https://linux-hardware.org/?probe=ca57bb441c) | Oct 18, 2022 |
| HP            | 158A                        | Desktop     | [6b1d53174a](https://linux-hardware.org/?probe=6b1d53174a) | Oct 12, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4... | Desktop     | [080242408d](https://linux-hardware.org/?probe=080242408d) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| Acer          | Aspire 4739Z                | Notebook    | [b85222f02c](https://linux-hardware.org/?probe=b85222f02c) | Oct 09, 2022 |
| Gigabyte      | H170M-D3H-CF                | Desktop     | [1bff176b39](https://linux-hardware.org/?probe=1bff176b39) | Oct 05, 2022 |
| Dell          | Inspiron 13 5310            | Notebook    | [128725bb4d](https://linux-hardware.org/?probe=128725bb4d) | Oct 04, 2022 |
| Dell          | Latitude E7240              | Notebook    | [84ce32d994](https://linux-hardware.org/?probe=84ce32d994) | Oct 03, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [396f61d294](https://linux-hardware.org/?probe=396f61d294) | Oct 03, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | Notebook    | [403aa5af3e](https://linux-hardware.org/?probe=403aa5af3e) | Oct 01, 2022 |
| Dell          | Vostro 5568                 | Notebook    | [44bf0dbbce](https://linux-hardware.org/?probe=44bf0dbbce) | Oct 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [a31db51878](https://linux-hardware.org/?probe=a31db51878) | Sep 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [2f16f0177f](https://linux-hardware.org/?probe=2f16f0177f) | Sep 21, 2022 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [ba2eadfd53](https://linux-hardware.org/?probe=ba2eadfd53) | Sep 21, 2022 |
| HP            | 158A                        | Desktop     | [428326af76](https://linux-hardware.org/?probe=428326af76) | Sep 21, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Lenovo        | ThinkPad T450s 20BX005GU... | Notebook    | [5c41d03119](https://linux-hardware.org/?probe=5c41d03119) | Sep 15, 2022 |
| Intel         | S1200SP H57533-350          | Server      | [6e17cb41c9](https://linux-hardware.org/?probe=6e17cb41c9) | Sep 15, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [c07c5b31f6](https://linux-hardware.org/?probe=c07c5b31f6) | Sep 13, 2022 |
| HP            | Elite x2 1013 G3            | Tablet      | [25b64af3e9](https://linux-hardware.org/?probe=25b64af3e9) | Sep 13, 2022 |
| Gigabyte      | X570 UD                     | Desktop     | [7e840fc9d0](https://linux-hardware.org/?probe=7e840fc9d0) | Sep 12, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [4b728bc447](https://linux-hardware.org/?probe=4b728bc447) | Sep 12, 2022 |
| Dell          | 0VNM11 A00                  | Desktop     | [9ae0ae5ac4](https://linux-hardware.org/?probe=9ae0ae5ac4) | Sep 10, 2022 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [ecc2f4c975](https://linux-hardware.org/?probe=ecc2f4c975) | Sep 06, 2022 |
| MSI           | H410M PRO                   | Desktop     | [e1184c4522](https://linux-hardware.org/?probe=e1184c4522) | Aug 31, 2022 |
| HP            | 18E7                        | Desktop     | [9344f12eea](https://linux-hardware.org/?probe=9344f12eea) | Aug 31, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3728476d21](https://linux-hardware.org/?probe=3728476d21) | Aug 31, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [46c6096b6e](https://linux-hardware.org/?probe=46c6096b6e) | Aug 23, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [8b1a8497c7](https://linux-hardware.org/?probe=8b1a8497c7) | Aug 21, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [a3d9fca7aa](https://linux-hardware.org/?probe=a3d9fca7aa) | Aug 16, 2022 |
| HP            | 2AE2                        | Desktop     | [1fd0bb70dc](https://linux-hardware.org/?probe=1fd0bb70dc) | Aug 15, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [59b6bdadd3](https://linux-hardware.org/?probe=59b6bdadd3) | Aug 14, 2022 |
| Dell          | Latitude E5540              | Notebook    | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| ASUSTek       | GL552VX                     | Notebook    | [16c1976ac6](https://linux-hardware.org/?probe=16c1976ac6) | Aug 12, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | Notebook    | [aa4b21b3a7](https://linux-hardware.org/?probe=aa4b21b3a7) | Aug 12, 2022 |
| Lenovo        | ThinkPad P50 20EQS4QM00     | Notebook    | [9779cc7396](https://linux-hardware.org/?probe=9779cc7396) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [688ae71abc](https://linux-hardware.org/?probe=688ae71abc) | Aug 12, 2022 |
| ASUSTek       | K55A                        | Notebook    | [fb75627e6c](https://linux-hardware.org/?probe=fb75627e6c) | Aug 10, 2022 |
| Dell          | G3 3500                     | Notebook    | [69f594bb80](https://linux-hardware.org/?probe=69f594bb80) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [a4e02af6d9](https://linux-hardware.org/?probe=a4e02af6d9) | Aug 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [d9c5b6d4c5](https://linux-hardware.org/?probe=d9c5b6d4c5) | Aug 02, 2022 |
| Toshiba       | dynabook Satellite B35/R    | Notebook    | [4600fb0c71](https://linux-hardware.org/?probe=4600fb0c71) | Jul 31, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [2171abfd3d](https://linux-hardware.org/?probe=2171abfd3d) | Jul 30, 2022 |
| HP            | 8455                        | Desktop     | [62b146bca0](https://linux-hardware.org/?probe=62b146bca0) | Jul 08, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| TENKU         | SB14                        | Notebook    | [cbe2900f4f](https://linux-hardware.org/?probe=cbe2900f4f) | Jul 02, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [cacc2464af](https://linux-hardware.org/?probe=cacc2464af) | Jun 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [6eb841aab1](https://linux-hardware.org/?probe=6eb841aab1) | Jun 21, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [58b312c382](https://linux-hardware.org/?probe=58b312c382) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | Notebook    | [a8c7fc9c3a](https://linux-hardware.org/?probe=a8c7fc9c3a) | Jun 07, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [4ae400000f](https://linux-hardware.org/?probe=4ae400000f) | Jun 01, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | Notebook    | [63bc3a2ce5](https://linux-hardware.org/?probe=63bc3a2ce5) | May 27, 2022 |
| Acer          | Aspire A315-57G             | Notebook    | [d0400f8d02](https://linux-hardware.org/?probe=d0400f8d02) | May 26, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [09ba129a3b](https://linux-hardware.org/?probe=09ba129a3b) | May 25, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [9df127ec26](https://linux-hardware.org/?probe=9df127ec26) | May 24, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bb2ffeb78a](https://linux-hardware.org/?probe=bb2ffeb78a) | May 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bb73f6aa37](https://linux-hardware.org/?probe=bb73f6aa37) | May 04, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [51625474b7](https://linux-hardware.org/?probe=51625474b7) | Apr 30, 2022 |
| Foxconn       | H61MD/H61MD-V               | Desktop     | [25b52955ee](https://linux-hardware.org/?probe=25b52955ee) | Apr 29, 2022 |
| ASUSTek       | E402SA                      | Notebook    | [4c5cbe705d](https://linux-hardware.org/?probe=4c5cbe705d) | Apr 27, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [2fcc2371d9](https://linux-hardware.org/?probe=2fcc2371d9) | Apr 25, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [287e344d0e](https://linux-hardware.org/?probe=287e344d0e) | Apr 16, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [7499dbd303](https://linux-hardware.org/?probe=7499dbd303) | Apr 15, 2022 |
| Foxconn       | H61MD/H61MD-V               | Desktop     | [7bb124e322](https://linux-hardware.org/?probe=7bb124e322) | Apr 06, 2022 |
| Dell          | System Vostro 3450          | Notebook    | [78750d86f5](https://linux-hardware.org/?probe=78750d86f5) | Mar 19, 2022 |
| Wistron       | JIG31B3                     | Desktop     | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [5dcc8e2cee](https://linux-hardware.org/?probe=5dcc8e2cee) | Mar 14, 2022 |
| ASUSTek       | ET2013I                     | All in one  | [b20d7593ce](https://linux-hardware.org/?probe=b20d7593ce) | Mar 09, 2022 |
| Dell          | Latitude E5540              | Notebook    | [0948114af7](https://linux-hardware.org/?probe=0948114af7) | Mar 03, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [9cfd9c7142](https://linux-hardware.org/?probe=9cfd9c7142) | Mar 02, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [a93699018b](https://linux-hardware.org/?probe=a93699018b) | Mar 02, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6b0f448d7b](https://linux-hardware.org/?probe=6b0f448d7b) | Feb 24, 2022 |
| Dell          | System XPS L702X            | Notebook    | [e1d4821ec2](https://linux-hardware.org/?probe=e1d4821ec2) | Feb 19, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [64f5921b5b](https://linux-hardware.org/?probe=64f5921b5b) | Feb 13, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [0619812e27](https://linux-hardware.org/?probe=0619812e27) | Feb 11, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [4834a3fe2e](https://linux-hardware.org/?probe=4834a3fe2e) | Feb 09, 2022 |
| Dell          | G3 3500                     | Notebook    | [9001ccacbc](https://linux-hardware.org/?probe=9001ccacbc) | Feb 09, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [2621c151ec](https://linux-hardware.org/?probe=2621c151ec) | Feb 01, 2022 |
| Dell          | Vostro 3578                 | Notebook    | [a95dfa8bc8](https://linux-hardware.org/?probe=a95dfa8bc8) | Jan 26, 2022 |
| Lenovo        | ThinkPad T480 20L5001DUS    | Notebook    | [872bc057f0](https://linux-hardware.org/?probe=872bc057f0) | Jan 10, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [5588a84fcf](https://linux-hardware.org/?probe=5588a84fcf) | Jan 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [d65648c445](https://linux-hardware.org/?probe=d65648c445) | Jan 09, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [3b97b65258](https://linux-hardware.org/?probe=3b97b65258) | Jan 08, 2022 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [be7876abf4](https://linux-hardware.org/?probe=be7876abf4) | Jan 05, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [65c9a87d51](https://linux-hardware.org/?probe=65c9a87d51) | Jan 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [48cfc7d185](https://linux-hardware.org/?probe=48cfc7d185) | Dec 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [b64750f465](https://linux-hardware.org/?probe=b64750f465) | Dec 26, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [1524f751eb](https://linux-hardware.org/?probe=1524f751eb) | Dec 24, 2021 |
| ASUSTek       | P8H61-MX                    | Desktop     | [cee5f081e3](https://linux-hardware.org/?probe=cee5f081e3) | Dec 19, 2021 |
| ASUSTek       | P8H61-MX                    | Desktop     | [297d964b96](https://linux-hardware.org/?probe=297d964b96) | Dec 18, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [717b9f1dd0](https://linux-hardware.org/?probe=717b9f1dd0) | Dec 16, 2021 |
| MSI           | MAG B365M MORTAR            | Desktop     | [bd72de2067](https://linux-hardware.org/?probe=bd72de2067) | Dec 12, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [412accf186](https://linux-hardware.org/?probe=412accf186) | Dec 09, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [21d85302a2](https://linux-hardware.org/?probe=21d85302a2) | Dec 05, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [903f3e93ee](https://linux-hardware.org/?probe=903f3e93ee) | Dec 03, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [70c63b2fb6](https://linux-hardware.org/?probe=70c63b2fb6) | Dec 02, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [c5d4bf5c62](https://linux-hardware.org/?probe=c5d4bf5c62) | Dec 02, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [7a8a79d813](https://linux-hardware.org/?probe=7a8a79d813) | Dec 02, 2021 |
| Timi          | A35S                        | Notebook    | [dbb600147d](https://linux-hardware.org/?probe=dbb600147d) | Nov 30, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [d4cf81aaa5](https://linux-hardware.org/?probe=d4cf81aaa5) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [0368cfb8e2](https://linux-hardware.org/?probe=0368cfb8e2) | Nov 23, 2021 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [fa62ac7a45](https://linux-hardware.org/?probe=fa62ac7a45) | Nov 23, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [10455f4980](https://linux-hardware.org/?probe=10455f4980) | Nov 23, 2021 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [1e15277ce2](https://linux-hardware.org/?probe=1e15277ce2) | Nov 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [17781cb457](https://linux-hardware.org/?probe=17781cb457) | Nov 20, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [f4a646d1f8](https://linux-hardware.org/?probe=f4a646d1f8) | Nov 18, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [5471ce2e2f](https://linux-hardware.org/?probe=5471ce2e2f) | Nov 16, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [96b971a0ed](https://linux-hardware.org/?probe=96b971a0ed) | Nov 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [84c316ee57](https://linux-hardware.org/?probe=84c316ee57) | Nov 08, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [a471ac5d59](https://linux-hardware.org/?probe=a471ac5d59) | Nov 07, 2021 |
| Dell          | Vostro 3478                 | Notebook    | [f88e5eec69](https://linux-hardware.org/?probe=f88e5eec69) | Nov 05, 2021 |
| Dell          | Vostro 3478                 | Notebook    | [8174188077](https://linux-hardware.org/?probe=8174188077) | Nov 05, 2021 |
| ASUSTek       | K45A                        | Notebook    | [f9bc7efe7b](https://linux-hardware.org/?probe=f9bc7efe7b) | Nov 05, 2021 |
| ASUSTek       | K45A                        | Notebook    | [096deec12d](https://linux-hardware.org/?probe=096deec12d) | Nov 05, 2021 |
| Dell          | Precision 7510              | Notebook    | [49f177c1c2](https://linux-hardware.org/?probe=49f177c1c2) | Nov 05, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [5158fb179d](https://linux-hardware.org/?probe=5158fb179d) | Nov 02, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [3296f4587d](https://linux-hardware.org/?probe=3296f4587d) | Nov 02, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [042607d7f1](https://linux-hardware.org/?probe=042607d7f1) | Oct 31, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [11527ae3f9](https://linux-hardware.org/?probe=11527ae3f9) | Oct 31, 2021 |
| Gigabyte      | G31MF-S2                    | Desktop     | [370ad865cf](https://linux-hardware.org/?probe=370ad865cf) | Oct 31, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [f316c0a82e](https://linux-hardware.org/?probe=f316c0a82e) | Oct 25, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6a546c5681](https://linux-hardware.org/?probe=6a546c5681) | Oct 23, 2021 |
| Gigabyte      | EP43T-S3L                   | Desktop     | [8a1adefcb3](https://linux-hardware.org/?probe=8a1adefcb3) | Oct 20, 2021 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [603ccdfb84](https://linux-hardware.org/?probe=603ccdfb84) | Oct 19, 2021 |
| Gigabyte      | G31MF-S2                    | Desktop     | [7459a9ed47](https://linux-hardware.org/?probe=7459a9ed47) | Oct 18, 2021 |
| Dell          | Precision 7510              | Notebook    | [800ca77fe7](https://linux-hardware.org/?probe=800ca77fe7) | Oct 13, 2021 |
| HP            | Notebook                    | Notebook    | [6ac2c09585](https://linux-hardware.org/?probe=6ac2c09585) | Oct 09, 2021 |
| HP            | Laptop 15-bs1xx             | Notebook    | [c9fd6887d4](https://linux-hardware.org/?probe=c9fd6887d4) | Oct 06, 2021 |
| Acer          | Predator PH315-51           | Notebook    | [fb9a605481](https://linux-hardware.org/?probe=fb9a605481) | Oct 05, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [b1fb3d4e88](https://linux-hardware.org/?probe=b1fb3d4e88) | Oct 04, 2021 |
| Dell          | Latitude E7440              | Notebook    | [fe4153e816](https://linux-hardware.org/?probe=fe4153e816) | Oct 04, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [8b3b2655bb](https://linux-hardware.org/?probe=8b3b2655bb) | Oct 03, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [101371762b](https://linux-hardware.org/?probe=101371762b) | Oct 01, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [c1dc59d33f](https://linux-hardware.org/?probe=c1dc59d33f) | Sep 29, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [52fe5aa259](https://linux-hardware.org/?probe=52fe5aa259) | Sep 29, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [d8cde7951e](https://linux-hardware.org/?probe=d8cde7951e) | Sep 29, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [db7c214214](https://linux-hardware.org/?probe=db7c214214) | Sep 28, 2021 |
| Dell          | Latitude 3520               | Notebook    | [2fb41f5f08](https://linux-hardware.org/?probe=2fb41f5f08) | Sep 24, 2021 |
| HP            | 15                          | Notebook    | [0aec7fa603](https://linux-hardware.org/?probe=0aec7fa603) | Sep 22, 2021 |
| Sony          | SVE14A15FGW                 | Notebook    | [f1049f7db1](https://linux-hardware.org/?probe=f1049f7db1) | Sep 21, 2021 |
| Panasonic     | CFSX4-1                     | Notebook    | [d474bc1b91](https://linux-hardware.org/?probe=d474bc1b91) | Sep 03, 2021 |
| Panasonic     | CFSX4-1                     | Notebook    | [bee71431a0](https://linux-hardware.org/?probe=bee71431a0) | Sep 03, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [87b688768a](https://linux-hardware.org/?probe=87b688768a) | Sep 02, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | Notebook    | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| MSI           | GF62 7RD                    | Notebook    | [5a35b145a9](https://linux-hardware.org/?probe=5a35b145a9) | Aug 19, 2021 |
| MSI           | GE66 Raider 11UH            | Notebook    | [df3d4bfff1](https://linux-hardware.org/?probe=df3d4bfff1) | Aug 18, 2021 |
| MSI           | GE66 Raider 11UH            | Notebook    | [dde539e1b1](https://linux-hardware.org/?probe=dde539e1b1) | Aug 18, 2021 |
| HP            | ProBook 4430s               | Notebook    | [0235e3c344](https://linux-hardware.org/?probe=0235e3c344) | Aug 18, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [d3ed4611f3](https://linux-hardware.org/?probe=d3ed4611f3) | Aug 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [f77c5c4c48](https://linux-hardware.org/?probe=f77c5c4c48) | Aug 10, 2021 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [886b00678b](https://linux-hardware.org/?probe=886b00678b) | Aug 09, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [57bf64ac4b](https://linux-hardware.org/?probe=57bf64ac4b) | Aug 09, 2021 |
| Dell          | Inspiron 5502               | Notebook    | [955889f7c8](https://linux-hardware.org/?probe=955889f7c8) | Aug 08, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [5f68a1fdaa](https://linux-hardware.org/?probe=5f68a1fdaa) | Aug 07, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [76e0c19c46](https://linux-hardware.org/?probe=76e0c19c46) | Aug 02, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [ce35fd4a1a](https://linux-hardware.org/?probe=ce35fd4a1a) | Jul 23, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [94aa730eda](https://linux-hardware.org/?probe=94aa730eda) | Jul 23, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [f6fc2c1a8c](https://linux-hardware.org/?probe=f6fc2c1a8c) | Jul 19, 2021 |
| ASUSTek       | PRIME B250M-K               | Desktop     | [10c0149671](https://linux-hardware.org/?probe=10c0149671) | Jul 17, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [aa5fadb321](https://linux-hardware.org/?probe=aa5fadb321) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | Notebook    | [dcc22fa273](https://linux-hardware.org/?probe=dcc22fa273) | Jul 13, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [3d6d3007cf](https://linux-hardware.org/?probe=3d6d3007cf) | Jul 10, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [66d001f315](https://linux-hardware.org/?probe=66d001f315) | Jul 09, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XX0... | Notebook    | [e6cb486cfd](https://linux-hardware.org/?probe=e6cb486cfd) | Jul 07, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XX0... | Notebook    | [58ad5d25b9](https://linux-hardware.org/?probe=58ad5d25b9) | Jul 07, 2021 |
| Dell          | Latitude E6410              | Notebook    | [9a4002aa3d](https://linux-hardware.org/?probe=9a4002aa3d) | Jul 07, 2021 |
| Gigabyte      | H61M-DS2                    | Desktop     | [894db66628](https://linux-hardware.org/?probe=894db66628) | Jul 05, 2021 |
| HP            | Compaq 510                  | Notebook    | [cd27b78fea](https://linux-hardware.org/?probe=cd27b78fea) | Jul 04, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [bec8a61ff4](https://linux-hardware.org/?probe=bec8a61ff4) | Jul 03, 2021 |
| Gigabyte      | P110-D3-CF                  | Desktop     | [37aab1ae76](https://linux-hardware.org/?probe=37aab1ae76) | Jun 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [3fb422fa2e](https://linux-hardware.org/?probe=3fb422fa2e) | Jun 27, 2021 |
| Colorful T... | C.A68M-BTC YV14             | Desktop     | [9b6c7d9e82](https://linux-hardware.org/?probe=9b6c7d9e82) | Jun 23, 2021 |
| ASUSTek       | K46CA                       | Notebook    | [85b912e99c](https://linux-hardware.org/?probe=85b912e99c) | Jun 22, 2021 |
| Huanan        | X79 249PC V2.1              | Desktop     | [b6fd95e48e](https://linux-hardware.org/?probe=b6fd95e48e) | Jun 15, 2021 |
| Acer          | Aspire 4315                 | Notebook    | [ac56c24f68](https://linux-hardware.org/?probe=ac56c24f68) | Jun 15, 2021 |
| Acer          | Aspire 4315                 | Notebook    | [4527ee70c7](https://linux-hardware.org/?probe=4527ee70c7) | Jun 13, 2021 |
| MSI           | B365M PRO-VH                | Desktop     | [ea30bb632e](https://linux-hardware.org/?probe=ea30bb632e) | Jun 10, 2021 |
| Lenovo        | ThinkPad L520 5015A76       | Notebook    | [84b62cbde9](https://linux-hardware.org/?probe=84b62cbde9) | Jun 10, 2021 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [851f20cb74](https://linux-hardware.org/?probe=851f20cb74) | Jun 09, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [428cb5bb99](https://linux-hardware.org/?probe=428cb5bb99) | Jun 05, 2021 |
| Dell          | Vostro 15-3568              | Notebook    | [de3596a9a3](https://linux-hardware.org/?probe=de3596a9a3) | Jun 05, 2021 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [38acf36fce](https://linux-hardware.org/?probe=38acf36fce) | Jun 05, 2021 |
| Dell          | Latitude 7420               | Notebook    | [f417016cf6](https://linux-hardware.org/?probe=f417016cf6) | Jun 04, 2021 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [4401c591ee](https://linux-hardware.org/?probe=4401c591ee) | Jun 01, 2021 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [f1d33c68f6](https://linux-hardware.org/?probe=f1d33c68f6) | Jun 01, 2021 |
| Lenovo        | V130-14IKB 81HQ             | Notebook    | [8995f3c1ad](https://linux-hardware.org/?probe=8995f3c1ad) | Jun 01, 2021 |
| Lenovo        | Z40-70 20366                | Notebook    | [b1b8196f26](https://linux-hardware.org/?probe=b1b8196f26) | May 31, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [35c74e640b](https://linux-hardware.org/?probe=35c74e640b) | May 31, 2021 |
| Lenovo        | ThinkPad X250 20CLCTO1WW    | Notebook    | [a5d677976f](https://linux-hardware.org/?probe=a5d677976f) | May 29, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [b70a62225d](https://linux-hardware.org/?probe=b70a62225d) | May 22, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [ddfb904938](https://linux-hardware.org/?probe=ddfb904938) | May 19, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [35324d2388](https://linux-hardware.org/?probe=35324d2388) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1abefab68f](https://linux-hardware.org/?probe=1abefab68f) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c4ea8f1bab](https://linux-hardware.org/?probe=c4ea8f1bab) | May 19, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [2ce7106efb](https://linux-hardware.org/?probe=2ce7106efb) | May 15, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [b8108b310a](https://linux-hardware.org/?probe=b8108b310a) | May 13, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [c596247722](https://linux-hardware.org/?probe=c596247722) | May 13, 2021 |
| Dell          | Inspiron 3443               | Notebook    | [c84fc5c646](https://linux-hardware.org/?probe=c84fc5c646) | May 12, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [ef73590627](https://linux-hardware.org/?probe=ef73590627) | May 09, 2021 |
| ASUSTek       | PRIME H110M-P               | Desktop     | [63effde8c3](https://linux-hardware.org/?probe=63effde8c3) | May 08, 2021 |
| ASUSTek       | PRIME H110M-P               | Desktop     | [99ac06d5e2](https://linux-hardware.org/?probe=99ac06d5e2) | May 08, 2021 |
| Acer          | Predator G9-793             | Notebook    | [90b04b667a](https://linux-hardware.org/?probe=90b04b667a) | May 03, 2021 |
| ASUSTek       | B75M-A                      | Desktop     | [2fabbbebb9](https://linux-hardware.org/?probe=2fabbbebb9) | Apr 29, 2021 |
| ASUSTek       | B75M-A                      | Desktop     | [23cc5c25c3](https://linux-hardware.org/?probe=23cc5c25c3) | Apr 29, 2021 |
| HP            | Pavilion 15                 | Notebook    | [1ddb966308](https://linux-hardware.org/?probe=1ddb966308) | Apr 28, 2021 |
| Sony          | VPCCW13FX                   | Notebook    | [82e9a1f82a](https://linux-hardware.org/?probe=82e9a1f82a) | Apr 25, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [599315872a](https://linux-hardware.org/?probe=599315872a) | Apr 24, 2021 |
| Dell          | Precision 3520              | Notebook    | [fc2d295c0e](https://linux-hardware.org/?probe=fc2d295c0e) | Apr 24, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [76defcf2f7](https://linux-hardware.org/?probe=76defcf2f7) | Apr 22, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [c941a697c2](https://linux-hardware.org/?probe=c941a697c2) | Apr 22, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e55472cf5f](https://linux-hardware.org/?probe=e55472cf5f) | Apr 18, 2021 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [007ae7cca0](https://linux-hardware.org/?probe=007ae7cca0) | Apr 18, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [07736896f9](https://linux-hardware.org/?probe=07736896f9) | Apr 18, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [abf17f0c92](https://linux-hardware.org/?probe=abf17f0c92) | Apr 17, 2021 |
| HP            | Unknown                     | Notebook    | [2465109965](https://linux-hardware.org/?probe=2465109965) | Apr 13, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [698d0ca8cc](https://linux-hardware.org/?probe=698d0ca8cc) | Apr 08, 2021 |
| Dell          | G3 3579                     | Notebook    | [d5d191947e](https://linux-hardware.org/?probe=d5d191947e) | Apr 06, 2021 |
| Dell          | G3 3579                     | Notebook    | [07fd740efe](https://linux-hardware.org/?probe=07fd740efe) | Apr 06, 2021 |
| Chuwi         | LapBook SE                  | Notebook    | [0e9a03cc48](https://linux-hardware.org/?probe=0e9a03cc48) | Apr 06, 2021 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [d20d2b755f](https://linux-hardware.org/?probe=d20d2b755f) | Apr 04, 2021 |
| Gigabyte      | MZBAYAP-00                  | Desktop     | [cdfb323202](https://linux-hardware.org/?probe=cdfb323202) | Apr 04, 2021 |
| Toshiba       | Satellite E45-B             | Notebook    | [e8c59a070a](https://linux-hardware.org/?probe=e8c59a070a) | Apr 04, 2021 |
| Toshiba       | Satellite E45-B             | Notebook    | [b9324b1b4d](https://linux-hardware.org/?probe=b9324b1b4d) | Apr 04, 2021 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [0984402bad](https://linux-hardware.org/?probe=0984402bad) | Apr 03, 2021 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [eba80415c0](https://linux-hardware.org/?probe=eba80415c0) | Apr 03, 2021 |
| MSI           | GS40 6QE Phantom            | Notebook    | [adbf080ab7](https://linux-hardware.org/?probe=adbf080ab7) | Mar 27, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [12fd74ecdc](https://linux-hardware.org/?probe=12fd74ecdc) | Mar 26, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [43f33bc8e0](https://linux-hardware.org/?probe=43f33bc8e0) | Mar 21, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [c377f57ac8](https://linux-hardware.org/?probe=c377f57ac8) | Mar 21, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [cac842cdbb](https://linux-hardware.org/?probe=cac842cdbb) | Mar 20, 2021 |
| Dell          | 04Y8V0 A02                  | Desktop     | [241289046a](https://linux-hardware.org/?probe=241289046a) | Mar 16, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [66ce284547](https://linux-hardware.org/?probe=66ce284547) | Mar 14, 2021 |
| Lenovo        | ThinkPad Helix 2nd 20CHS... | Tablet      | [5bada8b921](https://linux-hardware.org/?probe=5bada8b921) | Mar 13, 2021 |
| Dell          | Vostro 3460                 | Notebook    | [a8e1128b26](https://linux-hardware.org/?probe=a8e1128b26) | Mar 13, 2021 |
| Gigabyte      | Z390 UD                     | Desktop     | [d56654c11c](https://linux-hardware.org/?probe=d56654c11c) | Mar 12, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [d1bd158872](https://linux-hardware.org/?probe=d1bd158872) | Mar 10, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [f85fc12bff](https://linux-hardware.org/?probe=f85fc12bff) | Mar 09, 2021 |
| ASUSTek       | X202E                       | Notebook    | [cc089d4ddb](https://linux-hardware.org/?probe=cc089d4ddb) | Mar 08, 2021 |
| ZOTAC         | ZBOX-AD04                   | Mini pc     | [3acc3e5a05](https://linux-hardware.org/?probe=3acc3e5a05) | Mar 06, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [647b5fbb43](https://linux-hardware.org/?probe=647b5fbb43) | Mar 06, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [9e8527b842](https://linux-hardware.org/?probe=9e8527b842) | Mar 05, 2021 |
| Gigabyte      | H81M-DS2                    | Desktop     | [96fd52e1f2](https://linux-hardware.org/?probe=96fd52e1f2) | Mar 02, 2021 |
| Acer          | Aspire A515-53              | Notebook    | [637c3ebf75](https://linux-hardware.org/?probe=637c3ebf75) | Feb 28, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [05ad71d3d8](https://linux-hardware.org/?probe=05ad71d3d8) | Feb 24, 2021 |
| Gateway       | LT40                        | Notebook    | [90ae93da93](https://linux-hardware.org/?probe=90ae93da93) | Feb 24, 2021 |
| Gateway       | LT40                        | Notebook    | [98f2ce8032](https://linux-hardware.org/?probe=98f2ce8032) | Feb 24, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [4a441fe0c9](https://linux-hardware.org/?probe=4a441fe0c9) | Feb 21, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [bfb791c2fb](https://linux-hardware.org/?probe=bfb791c2fb) | Feb 19, 2021 |
| Sony          | VGN-NW270F                  | Notebook    | [87b755412e](https://linux-hardware.org/?probe=87b755412e) | Feb 19, 2021 |
| Sony          | VGN-NW270F                  | Notebook    | [8d0bcb0740](https://linux-hardware.org/?probe=8d0bcb0740) | Feb 19, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [bb980a20ea](https://linux-hardware.org/?probe=bb980a20ea) | Feb 18, 2021 |
| ASUSTek       | EB1036                      | Desktop     | [d77c773bc7](https://linux-hardware.org/?probe=d77c773bc7) | Feb 17, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [a79c837a9b](https://linux-hardware.org/?probe=a79c837a9b) | Feb 16, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5cb0f77327](https://linux-hardware.org/?probe=5cb0f77327) | Feb 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [0c70deaac1](https://linux-hardware.org/?probe=0c70deaac1) | Feb 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [0441228ba8](https://linux-hardware.org/?probe=0441228ba8) | Feb 07, 2021 |
| Dell          | Latitude E7450              | Notebook    | [94b0fc1fc8](https://linux-hardware.org/?probe=94b0fc1fc8) | Feb 06, 2021 |
| Acer          | Swift SF315-52              | Notebook    | [b2b00b4390](https://linux-hardware.org/?probe=b2b00b4390) | Jan 30, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [d7f2ee4a81](https://linux-hardware.org/?probe=d7f2ee4a81) | Jan 25, 2021 |
| Dell          | 0CRWCR A01                  | All in one  | [568c3e9797](https://linux-hardware.org/?probe=568c3e9797) | Jan 21, 2021 |
| Shenzhen A... | X96 Max                     | Soc         | [2fed627592](https://linux-hardware.org/?probe=2fed627592) | Jan 18, 2021 |
| Toshiba       | Satellite L840              | Notebook    | [82f5ebd486](https://linux-hardware.org/?probe=82f5ebd486) | Jan 18, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [e9acf54209](https://linux-hardware.org/?probe=e9acf54209) | Jan 15, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [d462b4ca25](https://linux-hardware.org/?probe=d462b4ca25) | Jan 12, 2021 |
| Lenovo        | SHARKBAY SDK0E50515 STD     | Desktop     | [8ae2ef5b3b](https://linux-hardware.org/?probe=8ae2ef5b3b) | Jan 07, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [4a11009c6f](https://linux-hardware.org/?probe=4a11009c6f) | Jan 06, 2021 |
| ASUSTek       | B75M-A                      | Desktop     | [cf3d073aae](https://linux-hardware.org/?probe=cf3d073aae) | Jan 06, 2021 |
| Intel         | DP55WG AAE57269-407         | Desktop     | [8b549321e4](https://linux-hardware.org/?probe=8b549321e4) | Dec 31, 2020 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [540115f336](https://linux-hardware.org/?probe=540115f336) | Dec 28, 2020 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [2e581b986a](https://linux-hardware.org/?probe=2e581b986a) | Dec 28, 2020 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [cd0b939f13](https://linux-hardware.org/?probe=cd0b939f13) | Dec 27, 2020 |
| ASUSTek       | X550CC                      | Notebook    | [6eaddc8157](https://linux-hardware.org/?probe=6eaddc8157) | Dec 21, 2020 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [fb16534a29](https://linux-hardware.org/?probe=fb16534a29) | Dec 17, 2020 |
| Sony          | VGN-NW270F                  | Notebook    | [d8989e5c40](https://linux-hardware.org/?probe=d8989e5c40) | Dec 16, 2020 |
| Apple         | MacBookPro11,4              | Notebook    | [e880800d6f](https://linux-hardware.org/?probe=e880800d6f) | Dec 13, 2020 |
| Dell          | G3 3579                     | Notebook    | [99724b8bd6](https://linux-hardware.org/?probe=99724b8bd6) | Dec 12, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fa10ea29e8](https://linux-hardware.org/?probe=fa10ea29e8) | Dec 11, 2020 |
| HP            | 158A                        | Desktop     | [9c309002d1](https://linux-hardware.org/?probe=9c309002d1) | Dec 10, 2020 |
| Acer          | Predator PH315-51           | Notebook    | [c9539f5932](https://linux-hardware.org/?probe=c9539f5932) | Dec 09, 2020 |
| HP            | 2B2C                        | Desktop     | [ffd83f6d60](https://linux-hardware.org/?probe=ffd83f6d60) | Dec 08, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [ea2bf23a76](https://linux-hardware.org/?probe=ea2bf23a76) | Dec 03, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [2a4ce919e5](https://linux-hardware.org/?probe=2a4ce919e5) | Dec 03, 2020 |
| Acer          | Aspire V5-431P              | Notebook    | [831f0df544](https://linux-hardware.org/?probe=831f0df544) | Dec 03, 2020 |
| HP            | 158A                        | Desktop     | [eaab601c40](https://linux-hardware.org/?probe=eaab601c40) | Dec 02, 2020 |
| HP            | 158A                        | Desktop     | [64320f7764](https://linux-hardware.org/?probe=64320f7764) | Dec 02, 2020 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [4e39668b71](https://linux-hardware.org/?probe=4e39668b71) | Dec 02, 2020 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [dbff453f7e](https://linux-hardware.org/?probe=dbff453f7e) | Dec 02, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [80f3a03fc2](https://linux-hardware.org/?probe=80f3a03fc2) | Nov 22, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [471b375bb8](https://linux-hardware.org/?probe=471b375bb8) | Nov 22, 2020 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [32692a5980](https://linux-hardware.org/?probe=32692a5980) | Nov 18, 2020 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [4019b6c1ff](https://linux-hardware.org/?probe=4019b6c1ff) | Nov 16, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [7fb140838e](https://linux-hardware.org/?probe=7fb140838e) | Nov 12, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [ac263c6ad6](https://linux-hardware.org/?probe=ac263c6ad6) | Nov 10, 2020 |
| Intel         | NUC7i3DNB J57625-504        | Mini pc     | [3b2d445938](https://linux-hardware.org/?probe=3b2d445938) | Nov 07, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [f2a745943a](https://linux-hardware.org/?probe=f2a745943a) | Nov 04, 2020 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [bfa10fd887](https://linux-hardware.org/?probe=bfa10fd887) | Nov 04, 2020 |
| Dell          | Latitude 7490               | Notebook    | [8f0ec25c05](https://linux-hardware.org/?probe=8f0ec25c05) | Oct 29, 2020 |
| Dell          | Latitude E6530              | Notebook    | [1a16aeb4dd](https://linux-hardware.org/?probe=1a16aeb4dd) | Oct 28, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [318f172f36](https://linux-hardware.org/?probe=318f172f36) | Oct 27, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [070dae158a](https://linux-hardware.org/?probe=070dae158a) | Oct 24, 2020 |
| Toshiba       | Satellite L840              | Notebook    | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| ASUSTek       | ASUSPRO P1440UA             | Notebook    | [fa061b6d7e](https://linux-hardware.org/?probe=fa061b6d7e) | Oct 13, 2020 |
| ASUSTek       | ASUSPRO P1440UA             | Notebook    | [dc9b667685](https://linux-hardware.org/?probe=dc9b667685) | Oct 13, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [9bf6f0ba43](https://linux-hardware.org/?probe=9bf6f0ba43) | Oct 09, 2020 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [bcc1019568](https://linux-hardware.org/?probe=bcc1019568) | Oct 07, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [125dd87b84](https://linux-hardware.org/?probe=125dd87b84) | Oct 03, 2020 |
| Dell          | 0215PR A02                  | Desktop     | [a37475889b](https://linux-hardware.org/?probe=a37475889b) | Oct 03, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [204ef3a0f3](https://linux-hardware.org/?probe=204ef3a0f3) | Oct 02, 2020 |
| Lenovo        | ThinkPad T420 4236C95       | Notebook    | [8cf52f76c0](https://linux-hardware.org/?probe=8cf52f76c0) | Oct 02, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [6753d2054d](https://linux-hardware.org/?probe=6753d2054d) | Oct 01, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [6c568247ff](https://linux-hardware.org/?probe=6c568247ff) | Oct 01, 2020 |
| ASUSTek       | X411UA                      | Notebook    | [15bcec7549](https://linux-hardware.org/?probe=15bcec7549) | Sep 28, 2020 |
| Dell          | Vostro 3578                 | Notebook    | [5ff5b89d5e](https://linux-hardware.org/?probe=5ff5b89d5e) | Sep 22, 2020 |
| Koloe         | X58                         | Desktop     | [81d474ab62](https://linux-hardware.org/?probe=81d474ab62) | Sep 20, 2020 |
| ASUSTek       | Z10PE-D8 WS                 | Desktop     | [55e8990643](https://linux-hardware.org/?probe=55e8990643) | Sep 17, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [3a8b43fc2f](https://linux-hardware.org/?probe=3a8b43fc2f) | Sep 16, 2020 |
| ASUSTek       | X411UA                      | Notebook    | [8adea7b2b3](https://linux-hardware.org/?probe=8adea7b2b3) | Sep 15, 2020 |
| Dell          | Vostro 1450                 | Notebook    | [444ddb1aa9](https://linux-hardware.org/?probe=444ddb1aa9) | Sep 15, 2020 |
| Dell          | Precision 3520              | Notebook    | [e8f520c4fa](https://linux-hardware.org/?probe=e8f520c4fa) | Sep 09, 2020 |
| MASSCOM VI... | L133                        | Notebook    | [b356f018b2](https://linux-hardware.org/?probe=b356f018b2) | Sep 09, 2020 |
| HP            | ProBook 440 G6              | Notebook    | [11a8a7e166](https://linux-hardware.org/?probe=11a8a7e166) | Sep 07, 2020 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [42cdde5346](https://linux-hardware.org/?probe=42cdde5346) | Sep 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [6b4eeecb26](https://linux-hardware.org/?probe=6b4eeecb26) | Sep 04, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [190c1e6486](https://linux-hardware.org/?probe=190c1e6486) | Aug 31, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [a9ced30680](https://linux-hardware.org/?probe=a9ced30680) | Aug 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [17c4f51c75](https://linux-hardware.org/?probe=17c4f51c75) | Aug 29, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [08d8dc8d6e](https://linux-hardware.org/?probe=08d8dc8d6e) | Aug 28, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [889530c9b1](https://linux-hardware.org/?probe=889530c9b1) | Aug 28, 2020 |
| Lenovo        | ThinkPad L430 2465CTO       | Notebook    | [e5371d9b58](https://linux-hardware.org/?probe=e5371d9b58) | Aug 26, 2020 |
| Unknown       | SKYBAY                      | Desktop     | [01f13cc1c7](https://linux-hardware.org/?probe=01f13cc1c7) | Aug 25, 2020 |
| Dell          | 0200DY A02                  | Desktop     | [dc862d439b](https://linux-hardware.org/?probe=dc862d439b) | Aug 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4ff005e6d9](https://linux-hardware.org/?probe=4ff005e6d9) | Aug 21, 2020 |
| Lenovo        | ThinkPad T580 20L9001MUS    | Notebook    | [92c940e8c2](https://linux-hardware.org/?probe=92c940e8c2) | Aug 21, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [e7702e2ce8](https://linux-hardware.org/?probe=e7702e2ce8) | Aug 20, 2020 |
| Dell          | G3 3579                     | Notebook    | [8e341b94ae](https://linux-hardware.org/?probe=8e341b94ae) | Aug 18, 2020 |
| Dell          | G3 3579                     | Notebook    | [9a1078144d](https://linux-hardware.org/?probe=9a1078144d) | Aug 18, 2020 |
| MSI           | B85M Night Elf              | Desktop     | [d9fe6d88cd](https://linux-hardware.org/?probe=d9fe6d88cd) | Aug 14, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [52f08d8242](https://linux-hardware.org/?probe=52f08d8242) | Aug 12, 2020 |
| Lenovo        | ThinkPad E480 20KN005GVA    | Notebook    | [f77c6858ad](https://linux-hardware.org/?probe=f77c6858ad) | Jul 24, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [a58d188243](https://linux-hardware.org/?probe=a58d188243) | Jul 19, 2020 |
| HP            | 2B2C                        | Desktop     | [ed031034e8](https://linux-hardware.org/?probe=ed031034e8) | Jul 18, 2020 |
| HP            | 2B2C                        | Desktop     | [dd85e7a5e1](https://linux-hardware.org/?probe=dd85e7a5e1) | Jul 18, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [ab4eff4438](https://linux-hardware.org/?probe=ab4eff4438) | Jul 16, 2020 |
| Dell          | Latitude E5470              | Notebook    | [777b8955c3](https://linux-hardware.org/?probe=777b8955c3) | Jul 12, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [d0dff5e971](https://linux-hardware.org/?probe=d0dff5e971) | Jul 09, 2020 |
| Intel         | NUC7i3DNB J57625-504        | Mini pc     | [7300218f1f](https://linux-hardware.org/?probe=7300218f1f) | Jul 09, 2020 |
| Dell          | Vostro 3590                 | Notebook    | [4f8fb0d621](https://linux-hardware.org/?probe=4f8fb0d621) | Jul 09, 2020 |
| Intel         | NUC7i3DNB J57625-504        | Mini pc     | [dba2423eba](https://linux-hardware.org/?probe=dba2423eba) | Jul 08, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [601726ae15](https://linux-hardware.org/?probe=601726ae15) | Jul 01, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [4e1f771d23](https://linux-hardware.org/?probe=4e1f771d23) | Jun 29, 2020 |
| Dell          | Vostro 3460                 | Notebook    | [2338ae0fde](https://linux-hardware.org/?probe=2338ae0fde) | Jun 28, 2020 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [a3b890c7f1](https://linux-hardware.org/?probe=a3b890c7f1) | Jun 26, 2020 |
| ASUSTek       | A68HM-K                     | Desktop     | [7fc608d8c2](https://linux-hardware.org/?probe=7fc608d8c2) | Jun 21, 2020 |
| HP            | ZBook 17 G2                 | Notebook    | [467e55d0db](https://linux-hardware.org/?probe=467e55d0db) | Jun 20, 2020 |
| MSI           | B85M Night Elf              | Desktop     | [f223bc5b5e](https://linux-hardware.org/?probe=f223bc5b5e) | Jun 19, 2020 |
| MSI           | B85M Night Elf              | Desktop     | [27d008955f](https://linux-hardware.org/?probe=27d008955f) | Jun 19, 2020 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [ce4a203e0f](https://linux-hardware.org/?probe=ce4a203e0f) | Jun 19, 2020 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [652d0e5648](https://linux-hardware.org/?probe=652d0e5648) | Jun 18, 2020 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [3b5f86f3d4](https://linux-hardware.org/?probe=3b5f86f3d4) | Jun 18, 2020 |
| Dell          | Inspiron 5548               | Notebook    | [60a6140ac2](https://linux-hardware.org/?probe=60a6140ac2) | Jun 14, 2020 |
| Dell          | Inspiron 5548               | Notebook    | [ac70aa8a8d](https://linux-hardware.org/?probe=ac70aa8a8d) | Jun 14, 2020 |
| Dell          | Vostro 3590                 | Notebook    | [faca1b4063](https://linux-hardware.org/?probe=faca1b4063) | Jun 14, 2020 |
| HP            | ZBook Studio G3             | Notebook    | [91a0ff7707](https://linux-hardware.org/?probe=91a0ff7707) | Jun 10, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [7b0270fb87](https://linux-hardware.org/?probe=7b0270fb87) | Jun 04, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [be05348be2](https://linux-hardware.org/?probe=be05348be2) | May 29, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [945550a204](https://linux-hardware.org/?probe=945550a204) | May 29, 2020 |
| Gigabyte      | H170-Gaming 3               | Desktop     | [b0f5fc9b10](https://linux-hardware.org/?probe=b0f5fc9b10) | May 26, 2020 |
| Dell          | Latitude E7440              | Notebook    | [26b5908778](https://linux-hardware.org/?probe=26b5908778) | May 20, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [849bf107d8](https://linux-hardware.org/?probe=849bf107d8) | May 18, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [5a938c4186](https://linux-hardware.org/?probe=5a938c4186) | May 17, 2020 |
| Dell          | Inspiron 7520               | Notebook    | [f400730782](https://linux-hardware.org/?probe=f400730782) | May 15, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [ffb18f222a](https://linux-hardware.org/?probe=ffb18f222a) | May 15, 2020 |
| HP            | ProBook 440 G6              | Notebook    | [272430b55d](https://linux-hardware.org/?probe=272430b55d) | May 12, 2020 |
| Toshiba       | PORTEGE T110                | Notebook    | [8c8ec8db54](https://linux-hardware.org/?probe=8c8ec8db54) | May 10, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [7e7b980d96](https://linux-hardware.org/?probe=7e7b980d96) | May 09, 2020 |
| Gigabyte      | B450M GAMING                | Desktop     | [a4ec49073e](https://linux-hardware.org/?probe=a4ec49073e) | May 02, 2020 |
| ASRock        | AOD790GX/128M               | Desktop     | [8ba6b55d11](https://linux-hardware.org/?probe=8ba6b55d11) | Apr 28, 2020 |
| Dell          | Vostro 14-5480              | Notebook    | [3edae78003](https://linux-hardware.org/?probe=3edae78003) | Apr 28, 2020 |
| Dell          | Inspiron 3558               | Notebook    | [8e17ac8b14](https://linux-hardware.org/?probe=8e17ac8b14) | Apr 27, 2020 |
| Gigabyte      | H61M-DS2                    | Desktop     | [1aa80c5f94](https://linux-hardware.org/?probe=1aa80c5f94) | Apr 26, 2020 |
| Acer          | Swift SF315-52              | Notebook    | [a41dc8c7b3](https://linux-hardware.org/?probe=a41dc8c7b3) | Apr 24, 2020 |
| Dell          | Vostro 3478                 | Notebook    | [65a16b0f00](https://linux-hardware.org/?probe=65a16b0f00) | Apr 22, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [985dd25740](https://linux-hardware.org/?probe=985dd25740) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [8b6c1d10a4](https://linux-hardware.org/?probe=8b6c1d10a4) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [9cb006b675](https://linux-hardware.org/?probe=9cb006b675) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [e670bd004a](https://linux-hardware.org/?probe=e670bd004a) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [ed1d4fbd62](https://linux-hardware.org/?probe=ed1d4fbd62) | Apr 19, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [c51238bbe1](https://linux-hardware.org/?probe=c51238bbe1) | Apr 11, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [e421f3a586](https://linux-hardware.org/?probe=e421f3a586) | Apr 10, 2020 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [45b9a81a90](https://linux-hardware.org/?probe=45b9a81a90) | Apr 08, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [9d7415c55e](https://linux-hardware.org/?probe=9d7415c55e) | Apr 04, 2020 |
| Dell          | Precision 5530              | Notebook    | [805db6810c](https://linux-hardware.org/?probe=805db6810c) | Mar 31, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [6093f50362](https://linux-hardware.org/?probe=6093f50362) | Mar 30, 2020 |
| Sony          | VPCEB42EG                   | Notebook    | [d2586cdd17](https://linux-hardware.org/?probe=d2586cdd17) | Mar 25, 2020 |
| Sony          | VPCEB42EG                   | Notebook    | [424402e2b1](https://linux-hardware.org/?probe=424402e2b1) | Mar 25, 2020 |
| ASUSTek       | GL553VE                     | Notebook    | [1238bea224](https://linux-hardware.org/?probe=1238bea224) | Mar 21, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [72a39494c1](https://linux-hardware.org/?probe=72a39494c1) | Mar 18, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [7dddec34d1](https://linux-hardware.org/?probe=7dddec34d1) | Mar 02, 2020 |
| Intel         | S5520HC E26045-457          | Server      | [49d0f0d68c](https://linux-hardware.org/?probe=49d0f0d68c) | Mar 01, 2020 |
| Intel         | S5520HC E26045-457          | Server      | [359532fc26](https://linux-hardware.org/?probe=359532fc26) | Mar 01, 2020 |
| HP            | Compaq Presario CQ45        | Notebook    | [f1e468eec0](https://linux-hardware.org/?probe=f1e468eec0) | Feb 29, 2020 |
| HP            | Laptop 14-bs0xx             | Notebook    | [3740504388](https://linux-hardware.org/?probe=3740504388) | Feb 28, 2020 |
| ASUSTek       | X411UA                      | Notebook    | [284484a6b6](https://linux-hardware.org/?probe=284484a6b6) | Feb 15, 2020 |
| Koompi        | Unknown                     | Notebook    | [46e5e1375d](https://linux-hardware.org/?probe=46e5e1375d) | Feb 12, 2020 |
| Shuttle       | FS81                        | Desktop     | [93c00d64e6](https://linux-hardware.org/?probe=93c00d64e6) | Feb 07, 2020 |
| MSI           | GF63 8RD                    | Notebook    | [6eae1d7ba9](https://linux-hardware.org/?probe=6eae1d7ba9) | Feb 01, 2020 |
| MSI           | GF63 8RD                    | Notebook    | [b7087b6ba5](https://linux-hardware.org/?probe=b7087b6ba5) | Jan 31, 2020 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [e3cbb2da5f](https://linux-hardware.org/?probe=e3cbb2da5f) | Jan 24, 2020 |
| ASUSTek       | K501UX                      | Notebook    | [46c0e495c1](https://linux-hardware.org/?probe=46c0e495c1) | Jan 24, 2020 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [b2bc63b818](https://linux-hardware.org/?probe=b2bc63b818) | Jan 14, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4ea2e33944](https://linux-hardware.org/?probe=4ea2e33944) | Jan 07, 2020 |
| AMI           | Cherry Trail FFD            | Notebook    | [c62d47b2a1](https://linux-hardware.org/?probe=c62d47b2a1) | Dec 22, 2019 |
| ASUSTek       | P9X79 WS                    | Desktop     | [7a8ccfd558](https://linux-hardware.org/?probe=7a8ccfd558) | Nov 21, 2019 |
| Jumper        | EZpad                       | Notebook    | [6dfb4e2274](https://linux-hardware.org/?probe=6dfb4e2274) | Oct 31, 2019 |
| Dell          | System Vostro 3450          | Notebook    | [2017fd9a25](https://linux-hardware.org/?probe=2017fd9a25) | Oct 29, 2019 |
| Dell          | System Vostro 3450          | Notebook    | [90391fe6fe](https://linux-hardware.org/?probe=90391fe6fe) | Sep 19, 2019 |
| Samsung       | NC208/NC108                 | Notebook    | [a99fe6de20](https://linux-hardware.org/?probe=a99fe6de20) | Sep 16, 2019 |
| Dell          | 0CU409                      | Desktop     | [a5aabfdba4](https://linux-hardware.org/?probe=a5aabfdba4) | Sep 09, 2019 |
| Dell          | 0CU409                      | Desktop     | [8efe3a4b92](https://linux-hardware.org/?probe=8efe3a4b92) | Sep 08, 2019 |
| Dell          | Inspiron 3421               | Notebook    | [46a7955491](https://linux-hardware.org/?probe=46a7955491) | Sep 04, 2019 |
| Lenovo        | ThinkPad T410 2522AN6       | Notebook    | [35dfb93d51](https://linux-hardware.org/?probe=35dfb93d51) | Sep 02, 2019 |
| Lenovo        | ThinkPad T410 2522AN6       | Notebook    | [635d10113c](https://linux-hardware.org/?probe=635d10113c) | Sep 02, 2019 |
| Gigabyte      | B360 M AORUS PRO-CF         | Desktop     | [657b0b4115](https://linux-hardware.org/?probe=657b0b4115) | Aug 28, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [f9ed638fe3](https://linux-hardware.org/?probe=f9ed638fe3) | Aug 27, 2019 |
| Dell          | System Inspiron N4110       | Notebook    | [1923c8603b](https://linux-hardware.org/?probe=1923c8603b) | Aug 13, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [6a22791c51](https://linux-hardware.org/?probe=6a22791c51) | Aug 02, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [9394c6057f](https://linux-hardware.org/?probe=9394c6057f) | Aug 01, 2019 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [6cf789df63](https://linux-hardware.org/?probe=6cf789df63) | Jul 26, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [a6040fd25f](https://linux-hardware.org/?probe=a6040fd25f) | Jul 21, 2019 |
| Gigabyte      | B450M GAMING                | Desktop     | [e4ad262a5d](https://linux-hardware.org/?probe=e4ad262a5d) | Jul 18, 2019 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [c52b084692](https://linux-hardware.org/?probe=c52b084692) | Jul 08, 2019 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [06efccb71d](https://linux-hardware.org/?probe=06efccb71d) | Jul 07, 2019 |
| Wistron       | JIH55Y                      | Desktop     | [75d7b2909e](https://linux-hardware.org/?probe=75d7b2909e) | Jul 07, 2019 |
| MSI           | K9A2 Neo2                   | Desktop     | [ab1717a7d5](https://linux-hardware.org/?probe=ab1717a7d5) | Jul 05, 2019 |
| MSI           | K9A2 Neo2                   | Desktop     | [32eed13a8c](https://linux-hardware.org/?probe=32eed13a8c) | Jul 05, 2019 |
| Dell          | Inspiron 3537               | Notebook    | [96b08c73b2](https://linux-hardware.org/?probe=96b08c73b2) | Jul 03, 2019 |
| Dell          | Inspiron 7559               | Notebook    | [9662a59bb6](https://linux-hardware.org/?probe=9662a59bb6) | Jun 19, 2019 |
| ASUSTek       | K46CM                       | Notebook    | [f695a76e03](https://linux-hardware.org/?probe=f695a76e03) | Jun 16, 2019 |
| Lenovo        | ThinkPad X230 2325BK0       | Notebook    | [e3cbad71df](https://linux-hardware.org/?probe=e3cbad71df) | Jun 06, 2019 |
| Dell          | Precision M4800             | Notebook    | [87cd78dbb8](https://linux-hardware.org/?probe=87cd78dbb8) | Jun 06, 2019 |
| Dell          | Inspiron 7559               | Notebook    | [2b022f3e6e](https://linux-hardware.org/?probe=2b022f3e6e) | Jun 06, 2019 |
| HP            | Unknown                     | Notebook    | [5a84e64836](https://linux-hardware.org/?probe=5a84e64836) | Jun 05, 2019 |
| Lenovo        | Unknown                     | Notebook    | [bb521ffe81](https://linux-hardware.org/?probe=bb521ffe81) | May 29, 2019 |
| Lenovo        | Unknown                     | Notebook    | [ded7e33a30](https://linux-hardware.org/?probe=ded7e33a30) | May 29, 2019 |
| ASUSTek       | H81M-K                      | Desktop     | [0142c9d319](https://linux-hardware.org/?probe=0142c9d319) | May 08, 2019 |
| ASUSTek       | H81M-K                      | Desktop     | [eab65462c8](https://linux-hardware.org/?probe=eab65462c8) | May 08, 2019 |
| Lenovo        | ThinkPad X230 2325YN1       | Notebook    | [11b1a757e3](https://linux-hardware.org/?probe=11b1a757e3) | May 07, 2019 |
| Lenovo        | ThinkPad X230 2325YN1       | Notebook    | [48a1bab21b](https://linux-hardware.org/?probe=48a1bab21b) | May 06, 2019 |
| Dell          | Inspiron 3420               | Notebook    | [97669e6bac](https://linux-hardware.org/?probe=97669e6bac) | Apr 28, 2019 |
| Lenovo        | ThinkPad X240 20AMA01LVA    | Notebook    | [60e3dddb8e](https://linux-hardware.org/?probe=60e3dddb8e) | Apr 18, 2019 |
| Lenovo        | ThinkPad X230 2325VEN       | Notebook    | [7de9f34ff3](https://linux-hardware.org/?probe=7de9f34ff3) | Apr 08, 2019 |
| Lenovo        | ThinkPad T61 7661C54        | Notebook    | [f98ce96fd7](https://linux-hardware.org/?probe=f98ce96fd7) | Dec 14, 2018 |
| Lenovo        | ThinkPad T61 7661C54        | Notebook    | [3b2f20eb21](https://linux-hardware.org/?probe=3b2f20eb21) | Dec 14, 2018 |
| Lenovo        | ThinkPad X230 2325BK0       | Notebook    | [eb181d9db4](https://linux-hardware.org/?probe=eb181d9db4) | Nov 17, 2018 |
| Gigabyte      | H61M-DS2                    | Desktop     | [6c2f44420a](https://linux-hardware.org/?probe=6c2f44420a) | Nov 09, 2018 |
| Gigabyte      | H61M-DS2                    | Desktop     | [795142797e](https://linux-hardware.org/?probe=795142797e) | Nov 09, 2018 |
| MSI           | GP62 6QE                    | Notebook    | [0befde2891](https://linux-hardware.org/?probe=0befde2891) | Oct 29, 2018 |
| MSI           | GP62 6QE                    | Notebook    | [6d5cda0177](https://linux-hardware.org/?probe=6d5cda0177) | Oct 29, 2018 |
| ASUSTek       | FX503VM                     | Notebook    | [c3eafeed41](https://linux-hardware.org/?probe=c3eafeed41) | May 23, 2018 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [b73b24ff47](https://linux-hardware.org/?probe=b73b24ff47) | May 16, 2018 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [4ced3a8a3c](https://linux-hardware.org/?probe=4ced3a8a3c) | Feb 04, 2018 |
| HP            | Notebook                    | Notebook    | [8f94426008](https://linux-hardware.org/?probe=8f94426008) | Dec 21, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [96a6c5cbab](https://linux-hardware.org/?probe=96a6c5cbab) | Dec 17, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [f59b817feb](https://linux-hardware.org/?probe=f59b817feb) | Dec 12, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [06a39a2c60](https://linux-hardware.org/?probe=06a39a2c60) | Dec 12, 2017 |
| Lenovo        | ThinkCentre M55e 9389AN1    | Desktop     | [850f4b963c](https://linux-hardware.org/?probe=850f4b963c) | Dec 08, 2017 |
| Dell          | Precision M4600             | Notebook    | [dbbeb2486e](https://linux-hardware.org/?probe=dbbeb2486e) | Dec 03, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [7ee7ca743b](https://linux-hardware.org/?probe=7ee7ca743b) | Dec 03, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | Notebook    | [28ae3d12b8](https://linux-hardware.org/?probe=28ae3d12b8) | Dec 03, 2017 |
| Lenovo        | ThinkCentre M55e 9389AN1    | Desktop     | [e764602f25](https://linux-hardware.org/?probe=e764602f25) | Dec 02, 2017 |
| ASUSTek       | GL552JX                     | Notebook    | [c3e4792075](https://linux-hardware.org/?probe=c3e4792075) | Dec 10, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 83        | 22.99%  |
| Ubuntu 18.04                 | 36        | 9.97%   |
| Arch                         | 17        | 4.71%   |
| Ubuntu 22.04                 | 11        | 3.05%   |
| Arch Rolling                 | 11        | 3.05%   |
| Pop!_OS 20.04                | 7         | 1.94%   |
| Debian 10                    | 7         | 1.94%   |
| Ubuntu 21.04                 | 6         | 1.66%   |
| ArcoLinux Rolling            | 6         | 1.66%   |
| Zorin 16                     | 5         | 1.39%   |
| Ubuntu 16.04                 | 5         | 1.39%   |
| OpenMandriva 4.2             | 5         | 1.39%   |
| Manjaro 20.2                 | 5         | 1.39%   |
| KDE neon 20.04               | 5         | 1.39%   |
| Debian 11                    | 5         | 1.39%   |
| Ubuntu Unity 16.04           | 4         | 1.11%   |
| Ubuntu 21.10                 | 4         | 1.11%   |
| Ubuntu 20.10                 | 4         | 1.11%   |
| Ubuntu 19.10                 | 4         | 1.11%   |
| Ubuntu 19.04                 | 4         | 1.11%   |
| Pop!_OS 21.04                | 4         | 1.11%   |
| Pop!_OS 20.10                | 4         | 1.11%   |
| OpenMandriva 4.3             | 4         | 1.11%   |
| Manjaro                      | 4         | 1.11%   |
| Linux Mint 20.3              | 4         | 1.11%   |
| Fedora 34                    | 4         | 1.11%   |
| Fedora 33                    | 4         | 1.11%   |
| EndeavourOS Rolling          | 4         | 1.11%   |
| Zorin 15                     | 3         | 0.83%   |
| Pop!_OS 22.04                | 3         | 0.83%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.83%   |
| Manjaro 22.0.0               | 3         | 0.83%   |
| Kubuntu 20.04                | 3         | 0.83%   |
| Fedora 36                    | 3         | 0.83%   |
| Elementary 6                 | 3         | 0.83%   |
| Ubuntu Unity 20.04           | 2         | 0.55%   |
| Ubuntu MATE 20.04            | 2         | 0.55%   |
| Pop!_OS 21.10                | 2         | 0.55%   |
| Manjaro 18.0.4               | 2         | 0.55%   |
| Lubuntu 22.04                | 2         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 156       | 44.19%  |
| Arch         | 28        | 7.93%   |
| Pop!_OS      | 20        | 5.67%   |
| Manjaro      | 18        | 5.1%    |
| Fedora       | 14        | 3.97%   |
| Linux Mint   | 12        | 3.4%    |
| Debian       | 12        | 3.4%    |
| OpenMandriva | 9         | 2.55%   |
| Zorin        | 8         | 2.27%   |
| Ubuntu Unity | 8         | 2.27%   |
| Kubuntu      | 7         | 1.98%   |
| Endless      | 7         | 1.98%   |
| KDE neon     | 6         | 1.7%    |
| ArcoLinux    | 6         | 1.7%    |
| openSUSE     | 4         | 1.13%   |
| Lubuntu      | 4         | 1.13%   |
| EndeavourOS  | 4         | 1.13%   |
| Elementary   | 4         | 1.13%   |
| Clear Linux  | 4         | 1.13%   |
| Xubuntu      | 3         | 0.85%   |
| Kali         | 3         | 0.85%   |
| Ubuntu MATE  | 2         | 0.57%   |
| MX           | 2         | 0.57%   |
| LMDE         | 2         | 0.57%   |
| Gentoo       | 2         | 0.57%   |
| CentOS       | 2         | 0.57%   |
| Void Linux   | 1         | 0.28%   |
| Solus        | 1         | 0.28%   |
| ROSA         | 1         | 0.28%   |
| Parrot       | 1         | 0.28%   |
| Nobara       | 1         | 0.28%   |
| Devuan       | 1         | 0.28%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 9         | 2.33%   |
| 5.4.0-37-generic         | 8         | 2.07%   |
| 5.4.0-52-generic         | 7         | 1.81%   |
| 5.4.0-48-generic         | 7         | 1.81%   |
| 5.4.0-58-generic         | 6         | 1.55%   |
| 5.4.0-40-generic         | 6         | 1.55%   |
| 5.8.0-55-generic         | 5         | 1.3%    |
| 5.11.0-38-generic        | 5         | 1.3%    |
| 5.11.0-37-generic        | 5         | 1.3%    |
| 5.10.14-desktop-1omv4002 | 5         | 1.3%    |
| 5.8.0-7642-generic       | 4         | 1.04%   |
| 5.8.0-53-generic         | 4         | 1.04%   |
| 5.8.0-50-generic         | 4         | 1.04%   |
| 5.8.0-43-generic         | 4         | 1.04%   |
| 5.4.0-47-generic         | 4         | 1.04%   |
| 5.4.0-26-generic         | 4         | 1.04%   |
| 5.15.0-48-generic        | 4         | 1.04%   |
| 5.15.0-47-generic        | 4         | 1.04%   |
| 5.11.0-41-generic        | 4         | 1.04%   |
| 5.0.0-23-generic         | 4         | 1.04%   |
| 5.8.0-48-generic         | 3         | 0.78%   |
| 5.8.0-44-generic         | 3         | 0.78%   |
| 5.4.0-72-generic         | 3         | 0.78%   |
| 5.4.0-39-generic         | 3         | 0.78%   |
| 5.16.7-desktop-1omv4003  | 3         | 0.78%   |
| 5.15.0-46-generic        | 3         | 0.78%   |
| 4.18.0-25-generic        | 3         | 0.78%   |
| 4.10.0-28-generic        | 3         | 0.78%   |
| 5.9.14-200.fc33.x86_64   | 2         | 0.52%   |
| 5.9.11-3-MANJARO         | 2         | 0.52%   |
| 5.8.0-59-generic         | 2         | 0.52%   |
| 5.8.0-45-generic         | 2         | 0.52%   |
| 5.8.0-25-generic         | 2         | 0.52%   |
| 5.4.0-90-generic         | 2         | 0.52%   |
| 5.4.0-7642-generic       | 2         | 0.52%   |
| 5.4.0-74-generic         | 2         | 0.52%   |
| 5.4.0-70-generic         | 2         | 0.52%   |
| 5.4.0-45-generic         | 2         | 0.52%   |
| 5.4.0-29-generic         | 2         | 0.52%   |
| 5.4.0-19-generic         | 2         | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 76        | 20.88%  |
| 5.8.0   | 36        | 9.89%   |
| 5.11.0  | 30        | 8.24%   |
| 5.15.0  | 22        | 6.04%   |
| 4.15.0  | 15        | 4.12%   |
| 5.0.0   | 13        | 3.57%   |
| 5.3.0   | 11        | 3.02%   |
| 5.13.0  | 10        | 2.75%   |
| 5.10.0  | 10        | 2.75%   |
| 4.18.0  | 8         | 2.2%    |
| 5.10.14 | 5         | 1.37%   |
| 4.19.0  | 5         | 1.37%   |
| 4.10.0  | 5         | 1.37%   |
| 5.16.7  | 4         | 1.1%    |
| 5.9.0   | 3         | 0.82%   |
| 5.15.60 | 3         | 0.82%   |
| 5.9.14  | 2         | 0.55%   |
| 5.9.11  | 2         | 0.55%   |
| 5.19.12 | 2         | 0.55%   |
| 5.18.16 | 2         | 0.55%   |
| 5.18.10 | 2         | 0.55%   |
| 5.17.9  | 2         | 0.55%   |
| 5.15.55 | 2         | 0.55%   |
| 5.13.16 | 2         | 0.55%   |
| 5.12.8  | 2         | 0.55%   |
| 4.13.0  | 2         | 0.55%   |
| 6.0.5   | 1         | 0.27%   |
| 6.0.2   | 1         | 0.27%   |
| 6.0.0   | 1         | 0.27%   |
| 5.9.3   | 1         | 0.27%   |
| 5.9.13  | 1         | 0.27%   |
| 5.9.12  | 1         | 0.27%   |
| 5.9.1   | 1         | 0.27%   |
| 5.8.16  | 1         | 0.27%   |
| 5.8.14  | 1         | 0.27%   |
| 5.8.12  | 1         | 0.27%   |
| 5.7.16  | 1         | 0.27%   |
| 5.7.13  | 1         | 0.27%   |
| 5.7.12  | 1         | 0.27%   |
| 5.6.15  | 1         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 85        | 23.61%  |
| 5.8     | 39        | 10.83%  |
| 5.15    | 34        | 9.44%   |
| 5.11    | 32        | 8.89%   |
| 5.10    | 23        | 6.39%   |
| 5.13    | 16        | 4.44%   |
| 5.0     | 16        | 4.44%   |
| 4.15    | 16        | 4.44%   |
| 5.9     | 11        | 3.06%   |
| 5.3     | 11        | 3.06%   |
| 5.18    | 8         | 2.22%   |
| 5.16    | 8         | 2.22%   |
| 5.12    | 8         | 2.22%   |
| 4.18    | 8         | 2.22%   |
| 5.19    | 7         | 1.94%   |
| 4.19    | 7         | 1.94%   |
| 5.17    | 5         | 1.39%   |
| 5.14    | 5         | 1.39%   |
| 4.10    | 5         | 1.39%   |
| 6.0     | 3         | 0.83%   |
| 5.7     | 3         | 0.83%   |
| 5.6     | 2         | 0.56%   |
| 5.5     | 2         | 0.56%   |
| 4.13    | 2         | 0.56%   |
| 4.4     | 1         | 0.28%   |
| 4.12    | 1         | 0.28%   |
| 4.1     | 1         | 0.28%   |
| 3.10    | 1         | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 341       | 99.13%  |
| i686    | 2         | 0.58%   |
| aarch64 | 1         | 0.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 186       | 52.39%  |
| Unknown    | 53        | 14.93%  |
| KDE5       | 41        | 11.55%  |
| XFCE       | 20        | 5.63%   |
| KDE        | 11        | 3.1%    |
| X-Cinnamon | 8         | 2.25%   |
| Unity      | 8         | 2.25%   |
| MATE       | 5         | 1.41%   |
| Pantheon   | 4         | 1.13%   |
| LXQt       | 4         | 1.13%   |
| Cinnamon   | 4         | 1.13%   |
| bspwm      | 3         | 0.85%   |
| awesome    | 2         | 0.56%   |
| X-Generic  | 1         | 0.28%   |
| Openbox    | 1         | 0.28%   |
| KDE4       | 1         | 0.28%   |
| i3         | 1         | 0.28%   |
| Deepin     | 1         | 0.28%   |
| Budgie     | 1         | 0.28%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 277       | 78.25%  |
| Wayland | 40        | 11.3%   |
| Unknown | 30        | 8.47%   |
| Tty     | 7         | 1.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 178       | 50.57%  |
| GDM     | 61        | 17.33%  |
| SDDM    | 43        | 12.22%  |
| LightDM | 28        | 7.95%   |
| GDM3    | 22        | 6.25%   |
| TDM     | 16        | 4.55%   |
| XDM     | 2         | 0.57%   |
| SLiM    | 1         | 0.28%   |
| KDM     | 1         | 0.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 265       | 76.81%  |
| Unknown | 45        | 13.04%  |
| vi_VN   | 19        | 5.51%   |
| C       | 6         | 1.74%   |
| ru_RU   | 3         | 0.87%   |
| en_AU   | 3         | 0.87%   |
| en_GB   | 2         | 0.58%   |
| fr_FR   | 1         | 0.29%   |
| de_DE   | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 218       | 61.93%  |
| BIOS | 134       | 38.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 290       | 82.62%  |
| Btrfs   | 21        | 5.98%   |
| Overlay | 16        | 4.56%   |
| Unknown | 14        | 3.99%   |
| Zfs     | 6         | 1.71%   |
| F2fs    | 2         | 0.57%   |
| Xfs     | 1         | 0.28%   |
| Ext3    | 1         | 0.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 177       | 51.16%  |
| GPT     | 139       | 40.17%  |
| MBR     | 30        | 8.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 306       | 87.68%  |
| Yes       | 43        | 12.32%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 193       | 54.83%  |
| Yes       | 159       | 45.17%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Dell                           | 74        | 21.51%  |
| Lenovo                         | 56        | 16.28%  |
| ASUSTek Computer               | 55        | 15.99%  |
| Hewlett-Packard                | 45        | 13.08%  |
| Gigabyte Technology            | 32        | 9.3%    |
| Acer                           | 19        | 5.52%   |
| MSI                            | 18        | 5.23%   |
| Toshiba                        | 5         | 1.45%   |
| Sony                           | 4         | 1.16%   |
| Intel                          | 4         | 1.16%   |
| Apple                          | 4         | 1.16%   |
| Chuwi                          | 3         | 0.87%   |
| Wistron                        | 2         | 0.58%   |
| Samsung Electronics            | 2         | 0.58%   |
| Foxconn                        | 2         | 0.58%   |
| ASRock                         | 2         | 0.58%   |
| ZOTAC                          | 1         | 0.29%   |
| Timi                           | 1         | 0.29%   |
| TENKU                          | 1         | 0.29%   |
| Shuttle                        | 1         | 0.29%   |
| Shenzhen Amediatech Technology | 1         | 0.29%   |
| Panasonic                      | 1         | 0.29%   |
| Microsoft                      | 1         | 0.29%   |
| MASSCOM VIETNAM                | 1         | 0.29%   |
| LG Electronics                 | 1         | 0.29%   |
| Koompi                         | 1         | 0.29%   |
| Koloe                          | 1         | 0.29%   |
| Jumper                         | 1         | 0.29%   |
| Huanan                         | 1         | 0.29%   |
| Gateway                        | 1         | 0.29%   |
| Colorful Technology            | 1         | 0.29%   |
| AMI                            | 1         | 0.29%   |
| Unknown                        | 1         | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Gigabyte H61M-DS2              | 5         | 1.45%   |
| Unknown                        | 5         | 1.45%   |
| Dell Inspiron 3537             | 4         | 1.16%   |
| Lenovo ThinkPad E14 20RAS0KX00 | 3         | 0.87%   |
| Lenovo Legion 5 15ARH05 82B5   | 3         | 0.87%   |
| ASUS X411UA                    | 3         | 0.87%   |
| ASUS All Series                | 3         | 0.87%   |
| Toshiba Satellite L840         | 2         | 0.58%   |
| MSI MS-7B89                    | 2         | 0.58%   |
| MSI MS-7823                    | 2         | 0.58%   |
| MSI GF63 8RD                   | 2         | 0.58%   |
| Lenovo ThinkPad W530 2447EJ9   | 2         | 0.58%   |
| HP Notebook                    | 2         | 0.58%   |
| HP Laptop 14-bs0xx             | 2         | 0.58%   |
| HP EliteBook 8470p             | 2         | 0.58%   |
| HP EliteBook 840 G2            | 2         | 0.58%   |
| Gigabyte G41M-ES2L             | 2         | 0.58%   |
| Gigabyte B450M GAMING          | 2         | 0.58%   |
| Dell XPS 15 9570               | 2         | 0.58%   |
| Dell Vostro 5568               | 2         | 0.58%   |
| Dell Vostro 3590               | 2         | 0.58%   |
| Dell Vostro 3578               | 2         | 0.58%   |
| Dell Vostro 3478               | 2         | 0.58%   |
| Dell Vostro 3460               | 2         | 0.58%   |
| Dell Vostro 15-3568            | 2         | 0.58%   |
| Dell System Vostro 3450        | 2         | 0.58%   |
| Dell Latitude E7440            | 2         | 0.58%   |
| Dell Inspiron 5570             | 2         | 0.58%   |
| Dell G3 3579                   | 2         | 0.58%   |
| Dell G3 3500                   | 2         | 0.58%   |
| Chuwi GemiBook Pro             | 2         | 0.58%   |
| ASUS P8H61-MX R2.0             | 2         | 0.58%   |
| ASUS B75M-A                    | 2         | 0.58%   |
| Acer Swift SF315-52            | 2         | 0.58%   |
| Acer Predator PH315-51         | 2         | 0.58%   |
| Acer Aspire E5-575             | 2         | 0.58%   |
| Acer Aspire A315-42            | 2         | 0.58%   |
| ZOTAC ZBOX-AD04                | 1         | 0.29%   |
| Wistron FMVDD2A0H0             | 1         | 0.29%   |
| Wistron FMVCEG40Y              | 1         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 28        | 8.14%   |
| Dell Inspiron      | 19        | 5.52%   |
| Dell Vostro        | 17        | 4.94%   |
| Dell Latitude      | 13        | 3.78%   |
| Acer Aspire        | 13        | 3.78%   |
| HP EliteBook       | 11        | 3.2%    |
| Lenovo IdeaPad     | 10        | 2.91%   |
| ASUS ROG           | 8         | 2.33%   |
| HP ProBook         | 7         | 2.03%   |
| Dell XPS           | 7         | 2.03%   |
| Lenovo Legion      | 6         | 1.74%   |
| Dell Precision     | 6         | 1.74%   |
| ASUS VivoBook      | 6         | 1.74%   |
| HP Laptop          | 5         | 1.45%   |
| Gigabyte H61M-DS2  | 5         | 1.45%   |
| Unknown            | 5         | 1.45%   |
| Lenovo ThinkBook   | 4         | 1.16%   |
| Dell System        | 4         | 1.16%   |
| Dell OptiPlex      | 4         | 1.16%   |
| Dell G3            | 4         | 1.16%   |
| ASUS PRIME         | 4         | 1.16%   |
| ASUS ASUS          | 4         | 1.16%   |
| Toshiba Satellite  | 3         | 0.87%   |
| HP ZBook           | 3         | 0.87%   |
| HP Pavilion        | 3         | 0.87%   |
| ASUS X411UA        | 3         | 0.87%   |
| ASUS P8H61-MX      | 3         | 0.87%   |
| ASUS All           | 3         | 0.87%   |
| Acer Swift         | 3         | 0.87%   |
| Acer Predator      | 3         | 0.87%   |
| MSI MS-7B89        | 2         | 0.58%   |
| MSI MS-7823        | 2         | 0.58%   |
| MSI GF63           | 2         | 0.58%   |
| Lenovo ThinkCentre | 2         | 0.58%   |
| HP Notebook        | 2         | 0.58%   |
| HP Compaq          | 2         | 0.58%   |
| Gigabyte G41M-ES2L | 2         | 0.58%   |
| Gigabyte B450M     | 2         | 0.58%   |
| Chuwi GemiBook     | 2         | 0.58%   |
| ASUS B75M-A        | 2         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 49        | 14.24%  |
| 2012    | 39        | 11.34%  |
| 2020    | 34        | 9.88%   |
| 2019    | 34        | 9.88%   |
| 2015    | 26        | 7.56%   |
| 2013    | 26        | 7.56%   |
| 2017    | 23        | 6.69%   |
| 2016    | 23        | 6.69%   |
| 2014    | 20        | 5.81%   |
| 2011    | 19        | 5.52%   |
| 2021    | 17        | 4.94%   |
| 2010    | 13        | 3.78%   |
| 2009    | 11        | 3.2%    |
| 2022    | 4         | 1.16%   |
| 2007    | 3         | 0.87%   |
| 2008    | 1         | 0.29%   |
| 2006    | 1         | 0.29%   |
| Unknown | 1         | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 240       | 69.77%  |
| Desktop        | 89        | 25.87%  |
| Tablet         | 6         | 1.74%   |
| Mini pc        | 3         | 0.87%   |
| All in one     | 2         | 0.58%   |
| Server         | 2         | 0.58%   |
| System on chip | 1         | 0.29%   |
| Convertible    | 1         | 0.29%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 316       | 91.07%  |
| Enabled  | 31        | 8.93%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 344       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 92        | 26.44%  |
| 16.01-24.0  | 78        | 22.41%  |
| 8.01-16.0   | 66        | 18.97%  |
| 3.01-4.0    | 61        | 17.53%  |
| 32.01-64.0  | 26        | 7.47%   |
| 1.01-2.0    | 15        | 4.31%   |
| 24.01-32.0  | 6         | 1.72%   |
| 64.01-256.0 | 2         | 0.57%   |
| 2.01-3.0    | 1         | 0.29%   |
| 0.51-1.0    | 1         | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 119       | 32.51%  |
| 1.01-2.0   | 101       | 27.6%   |
| 4.01-8.0   | 61        | 16.67%  |
| 3.01-4.0   | 56        | 15.3%   |
| 8.01-16.0  | 18        | 4.92%   |
| 0.51-1.0   | 8         | 2.19%   |
| 16.01-24.0 | 2         | 0.55%   |
| 0.01-0.5   | 1         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 203       | 58.33%  |
| 2      | 114       | 32.76%  |
| 3      | 20        | 5.75%   |
| 4      | 6         | 1.72%   |
| 5      | 2         | 0.57%   |
| 0      | 2         | 0.57%   |
| 9      | 1         | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 266       | 77.33%  |
| Yes       | 78        | 22.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 295       | 85.26%  |
| No        | 51        | 14.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 290       | 84.3%   |
| No        | 54        | 15.7%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 249       | 71.97%  |
| No        | 97        | 28.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Vietnam | 344       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Ho Chi Minh City | 163       | 45.4%   |
| Hanoi            | 114       | 31.75%  |
| Da Nang          | 7         | 1.95%   |
| Can Tho          | 7         | 1.95%   |
| Bien Hoa         | 5         | 1.39%   |
| Huế            | 4         | 1.11%   |
| Vũng Tàu       | 3         | 0.84%   |
| Thuan An         | 3         | 0.84%   |
| Tay Ninh         | 3         | 0.84%   |
| Nga Bay          | 3         | 0.84%   |
| Nam Định      | 3         | 0.84%   |
| Buon Ma Thuot    | 3         | 0.84%   |
| Vinh Phuc        | 2         | 0.56%   |
| Quảng Ngai     | 2         | 0.56%   |
| Nha Trang        | 2         | 0.56%   |
| Haiphong         | 2         | 0.56%   |
| Hai Duong        | 2         | 0.56%   |
| Dien Ban         | 2         | 0.56%   |
| Binh Hoa         | 2         | 0.56%   |
| Bến Tre        | 2         | 0.56%   |
| Bao Loc          | 2         | 0.56%   |
| Bac Giang        | 2         | 0.56%   |
| Vinh             | 1         | 0.28%   |
| Viet Tri         | 1         | 0.28%   |
| Vi Thanh         | 1         | 0.28%   |
| Tra Vinh         | 1         | 0.28%   |
| Tinh Quang Binh  | 1         | 0.28%   |
| Tinh GJong Nai   | 1         | 0.28%   |
| Thu Duc          | 1         | 0.28%   |
| Thanh Hóa       | 1         | 0.28%   |
| Thai Nguyen      | 1         | 0.28%   |
| Tan An           | 1         | 0.28%   |
| Quang Trung      | 1         | 0.28%   |
| Quan Muoi Mot    | 1         | 0.28%   |
| Quan Muoi        | 1         | 0.28%   |
| Quan Binh Thanh  | 1         | 0.28%   |
| Lien Chieu       | 1         | 0.28%   |
| Hung Yen         | 1         | 0.28%   |
| Hoa Binh         | 1         | 0.28%   |
| Go Vap           | 1         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 84        | 100    | 16.97%  |
| Samsung Electronics   | 68        | 89     | 13.74%  |
| Seagate               | 55        | 68     | 11.11%  |
| Toshiba               | 37        | 48     | 7.47%   |
| HGST                  | 24        | 25     | 4.85%   |
| Kingston              | 21        | 24     | 4.24%   |
| Intel                 | 21        | 22     | 4.24%   |
| SK hynix              | 19        | 21     | 3.84%   |
| Unknown               | 18        | 19     | 3.64%   |
| Crucial               | 14        | 17     | 2.83%   |
| Hitachi               | 13        | 18     | 2.63%   |
| Micron Technology     | 11        | 13     | 2.22%   |
| Sandisk               | 10        | 11     | 2.02%   |
| Plextor               | 7         | 7      | 1.41%   |
| TO Exter              | 6         | 9      | 1.21%   |
| Lexar                 | 6         | 6      | 1.21%   |
| Colorful              | 6         | 6      | 1.21%   |
| Transcend             | 5         | 5      | 1.01%   |
| OSCOO                 | 5         | 6      | 1.01%   |
| OCZ                   | 3         | 3      | 0.61%   |
| Netac                 | 3         | 3      | 0.61%   |
| LITEON                | 3         | 3      | 0.61%   |
| KIOXIA                | 3         | 3      | 0.61%   |
| Gigabyte Technology   | 3         | 3      | 0.61%   |
| ZOTAC                 | 2         | 2      | 0.4%    |
| UMIS                  | 2         | 2      | 0.4%    |
| SPCC                  | 2         | 2      | 0.4%    |
| Phison                | 2         | 3      | 0.4%    |
| Maxtor                | 2         | 3      | 0.4%    |
| Lite-On               | 2         | 4      | 0.4%    |
| KingSpec              | 2         | 2      | 0.4%    |
| KingDian              | 2         | 3      | 0.4%    |
| Hikvision             | 2         | 2      | 0.4%    |
| Fujitsu               | 2         | 2      | 0.4%    |
| FORESEE               | 2         | 2      | 0.4%    |
| Apple                 | 2         | 2      | 0.4%    |
| W800S                 | 1         | 1      | 0.2%    |
| Vaseky                | 1         | 1      | 0.2%    |
| Silicon Motion        | 1         | 3      | 0.2%    |
| Realtek Semiconductor | 1         | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 9         | 1.74%   |
| HGST HTS721010A9E630 1TB                            | 9         | 1.74%   |
| Seagate ST1000LM035-1RK172 1TB                      | 8         | 1.54%   |
| TO Exter nal USB 3.0 1TB                            | 6         | 1.16%   |
| Samsung NVMe SSD Drive 512GB                        | 6         | 1.16%   |
| Toshiba MQ04ABF100 1TB                              | 5         | 0.97%   |
| Toshiba MQ01ABF050 500GB                            | 5         | 0.97%   |
| Samsung SSD 860 EVO 500GB                           | 5         | 0.97%   |
| Samsung SSD 860 EVO 250GB                           | 5         | 0.97%   |
| SK hynix NVMe SSD Drive 256GB                       | 4         | 0.77%   |
| Seagate ST1000LM049-2GH172 1TB                      | 4         | 0.77%   |
| Samsung MZALQ512HALU-000L2 512GB                    | 4         | 0.77%   |
| Lexar 128GB SSD                                     | 4         | 0.77%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 0.77%   |
| Kingston SA400S37120G 120GB SSD                     | 4         | 0.77%   |
| HGST HTS545050A7E680 500GB                          | 4         | 0.77%   |
| Crucial CT240BX500SSD1 240GB                        | 4         | 0.77%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 3         | 0.58%   |
| WDC WD5000LPLX-08ZNTT0 500GB                        | 3         | 0.58%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 3         | 0.58%   |
| WDC WD2500AAKX-00ERMA0 250GB                        | 3         | 0.58%   |
| Unknown MMC Card  32GB                              | 3         | 0.58%   |
| Toshiba MQ01ABD100 1TB                              | 3         | 0.58%   |
| SK hynix NVMe SSD Drive 512GB                       | 3         | 0.58%   |
| Seagate ST9500325AS 500GB                           | 3         | 0.58%   |
| Seagate ST500LT012-9WS142 500GB                     | 3         | 0.58%   |
| Seagate ST1000DM010-2EP102 1TB                      | 3         | 0.58%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 3         | 0.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 0.58%   |
| Kingston NVMe SSD Drive 256GB                       | 3         | 0.58%   |
| Hitachi HTS545050A7E380 500GB                       | 3         | 0.58%   |
| HGST HTS725050A7E630 500GB                          | 3         | 0.58%   |
| Gigabyte GP-GSTFS31120GNTD 120GB                    | 3         | 0.58%   |
| ZOTAC SATA SSD 120GB                                | 2         | 0.39%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                    | 2         | 0.39%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 2         | 0.39%   |
| WDC WD5000LPCX-21VHAT0 500GB                        | 2         | 0.39%   |
| WDC WD3200AAKX-001CA0 320GB                         | 2         | 0.39%   |
| WDC WD3200AAJS-00L7A0 320GB                         | 2         | 0.39%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 57        | 71     | 31.84%  |
| Seagate | 55        | 67     | 30.73%  |
| Toshiba | 27        | 32     | 15.08%  |
| HGST    | 24        | 25     | 13.41%  |
| Hitachi | 13        | 18     | 7.26%   |
| Fujitsu | 2         | 2      | 1.12%   |
| Unknown | 1         | 1      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 36     | 16.48%  |
| WDC                 | 19        | 19     | 10.44%  |
| Kingston            | 15        | 17     | 8.24%   |
| Crucial             | 13        | 14     | 7.14%   |
| Intel               | 12        | 13     | 6.59%   |
| Plextor             | 7         | 7      | 3.85%   |
| TO Exter            | 6         | 9      | 3.3%    |
| SanDisk             | 6         | 7      | 3.3%    |
| Lexar               | 6         | 6      | 3.3%    |
| Transcend           | 5         | 5      | 2.75%   |
| SK hynix            | 5         | 5      | 2.75%   |
| Micron Technology   | 4         | 4      | 2.2%    |
| Colorful            | 4         | 4      | 2.2%    |
| Toshiba             | 3         | 4      | 1.65%   |
| OSCOO               | 3         | 3      | 1.65%   |
| Netac               | 3         | 3      | 1.65%   |
| LITEON              | 3         | 3      | 1.65%   |
| Gigabyte Technology | 3         | 3      | 1.65%   |
| ZOTAC               | 2         | 2      | 1.1%    |
| OCZ                 | 2         | 2      | 1.1%    |
| Maxtor              | 2         | 3      | 1.1%    |
| KingSpec            | 2         | 2      | 1.1%    |
| KingDian            | 2         | 3      | 1.1%    |
| Hikvision           | 2         | 2      | 1.1%    |
| FORESEE             | 2         | 2      | 1.1%    |
| Apple               | 2         | 2      | 1.1%    |
| W800S               | 1         | 1      | 0.55%   |
| Vaseky              | 1         | 1      | 0.55%   |
| Unknown             | 1         | 1      | 0.55%   |
| SPCC                | 1         | 1      | 0.55%   |
| Patriot             | 1         | 1      | 0.55%   |
| OSC                 | 1         | 1      | 0.55%   |
| NGFF                | 1         | 1      | 0.55%   |
| LITEONIT            | 1         | 1      | 0.55%   |
| KLEVV               | 1         | 1      | 0.55%   |
| KIOXIA-EXCERIA      | 1         | 2      | 0.55%   |
| Kingmax             | 1         | 1      | 0.55%   |
| KimMiDi             | 1         | 1      | 0.55%   |
| Indilinx            | 1         | 1      | 0.55%   |
| HXY                 | 1         | 2      | 0.55%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 163       | 216    | 35.21%  |
| SSD     | 162       | 201    | 34.99%  |
| NVMe    | 117       | 150    | 25.27%  |
| MMC     | 12        | 13     | 2.59%   |
| Unknown | 9         | 9      | 1.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 256       | 410    | 64.65%  |
| NVMe | 116       | 149    | 29.29%  |
| SAS  | 12        | 17     | 3.03%   |
| MMC  | 12        | 13     | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 219       | 295    | 69.97%  |
| 0.51-1.0   | 78        | 97     | 24.92%  |
| 1.01-2.0   | 8         | 10     | 2.56%   |
| 4.01-10.0  | 5         | 12     | 1.6%    |
| 3.01-4.0   | 2         | 2      | 0.64%   |
| 2.01-3.0   | 1         | 1      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 128       | 35.75%  |
| 251-500        | 73        | 20.39%  |
| 501-1000       | 36        | 10.06%  |
| 51-100         | 31        | 8.66%   |
| 1001-2000      | 23        | 6.42%   |
| 21-50          | 20        | 5.59%   |
| 1-20           | 19        | 5.31%   |
| Unknown        | 13        | 3.63%   |
| 2001-3000      | 8         | 2.23%   |
| More than 3000 | 7         | 1.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 157       | 43.61%  |
| 21-50          | 64        | 17.78%  |
| 51-100         | 44        | 12.22%  |
| 101-250        | 29        | 8.06%   |
| 251-500        | 25        | 6.94%   |
| 501-1000       | 17        | 4.72%   |
| Unknown        | 13        | 3.61%   |
| More than 3000 | 5         | 1.39%   |
| 1001-2000      | 4         | 1.11%   |
| 2001-3000      | 2         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD             | 2         | 2      | 5.13%   |
| WDC WD3200AAKX-001CA0 320GB                  | 2         | 2      | 5.13%   |
| Seagate ST1000LM035-1RK172 1TB               | 2         | 2      | 5.13%   |
| HGST HTS725050A7E630 500GB                   | 2         | 2      | 5.13%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 2.56%   |
| WDC WD5000LPLX-60ZNTT1 500GB                 | 1         | 1      | 2.56%   |
| WDC WD3200AAJS-00L7A0 320GB                  | 1         | 1      | 2.56%   |
| WDC WD32 00BEVT-24A23 320GB                  | 1         | 1      | 2.56%   |
| WDC WD10JPVX-75JC3T0 1TB                     | 1         | 1      | 2.56%   |
| WDC WD1003FZEX-00MK2A0 1TB                   | 1         | 1      | 2.56%   |
| Unknown Bamba-240GB SSD                      | 1         | 1      | 2.56%   |
| Transcend TS256GSSD230S 256GB                | 1         | 1      | 2.56%   |
| Toshiba MQ01ABD050 500GB                     | 1         | 1      | 2.56%   |
| Toshiba MK8046GSX 80GB                       | 1         | 1      | 2.56%   |
| Toshiba MK3265GSXN 320GB                     | 1         | 1      | 2.56%   |
| Toshiba HDWK105 500GB                        | 1         | 1      | 2.56%   |
| SK hynix HFS032G34MNC-2200A 32GB SSD         | 1         | 1      | 2.56%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 2.56%   |
| Seagate ST500DM002-1BD142 500GB              | 1         | 1      | 2.56%   |
| Seagate ST1000DM003-1ER162 1TB               | 1         | 1      | 2.56%   |
| Samsung Electronics SSD 870 EVO 1TB          | 1         | 1      | 2.56%   |
| Samsung Electronics MZVPW128HEGM-00000 128GB | 1         | 1      | 2.56%   |
| LITEON LCH-256V2S 256GB SSD                  | 1         | 1      | 2.56%   |
| Intel SSDSC2CW120A3 120GB                    | 1         | 1      | 2.56%   |
| Hitachi HUA722020ALA331 2TB                  | 1         | 1      | 2.56%   |
| Hitachi HTS725050A7E635 500GB                | 1         | 1      | 2.56%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 2.56%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 1      | 2.56%   |
| Hitachi HDT725032VLA380 320GB                | 1         | 2      | 2.56%   |
| HGST HTS725032A7E630 320GB                   | 1         | 1      | 2.56%   |
| HGST HTS545050A7E680 500GB                   | 1         | 2      | 2.56%   |
| HGST HTS545050A7 500GB                       | 1         | 1      | 2.56%   |
| HGST HTS541010A7E630 1TB                     | 1         | 1      | 2.56%   |
| Fujitsu MHK2120AT 12GB                       | 1         | 1      | 2.56%   |
| Crucial CT525MX300SSD1 528GB                 | 1         | 1      | 2.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 10     | 25.64%  |
| HGST                | 6         | 7      | 15.38%  |
| Seagate             | 5         | 5      | 12.82%  |
| Hitachi             | 5         | 6      | 12.82%  |
| Toshiba             | 4         | 4      | 10.26%  |
| Samsung Electronics | 2         | 2      | 5.13%   |
| Unknown             | 1         | 1      | 2.56%   |
| Transcend           | 1         | 1      | 2.56%   |
| SK hynix            | 1         | 1      | 2.56%   |
| LITEON              | 1         | 1      | 2.56%   |
| Intel               | 1         | 1      | 2.56%   |
| Fujitsu             | 1         | 1      | 2.56%   |
| Crucial             | 1         | 1      | 2.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 8         | 8      | 27.59%  |
| HGST    | 6         | 7      | 20.69%  |
| Seagate | 5         | 5      | 17.24%  |
| Hitachi | 5         | 6      | 17.24%  |
| Toshiba | 4         | 4      | 13.79%  |
| Fujitsu | 1         | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 31     | 76.32%  |
| SSD  | 8         | 9      | 21.05%  |
| NVMe | 1         | 1      | 2.63%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 193       | 310    | 50.79%  |
| Works    | 150       | 237    | 39.47%  |
| Malfunc  | 36        | 41     | 9.47%   |
| Failed   | 1         | 1      | 0.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 281       | 64.45%  |
| Samsung Electronics            | 46        | 10.55%  |
| AMD                            | 32        | 7.34%   |
| SK hynix                       | 14        | 3.21%   |
| SanDisk                        | 13        | 2.98%   |
| Toshiba America Info Systems   | 8         | 1.83%   |
| Micron Technology              | 7         | 1.61%   |
| Kingston Technology Company    | 6         | 1.38%   |
| Phison Electronics             | 4         | 0.92%   |
| KIOXIA                         | 4         | 0.92%   |
| Silicon Motion                 | 3         | 0.69%   |
| ASMedia Technology             | 3         | 0.69%   |
| Union Memory (Shenzhen)        | 2         | 0.46%   |
| Solid State Storage Technology | 2         | 0.46%   |
| Micron/Crucial Technology      | 2         | 0.46%   |
| Lite-On Technology             | 2         | 0.46%   |
| Realtek Semiconductor          | 1         | 0.23%   |
| OCZ Technology Group           | 1         | 0.23%   |
| Marvell Technology Group       | 1         | 0.23%   |
| LSI Logic / Symbios Logic      | 1         | 0.23%   |
| Lenovo                         | 1         | 0.23%   |
| JMicron Technology             | 1         | 0.23%   |
| Broadcom / LSI                 | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 32        | 6.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 29        | 6.13%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 27        | 5.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 20        | 4.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 18        | 3.81%   |
| Samsung NVMe SSD Controller 980                                                         | 15        | 3.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 14        | 2.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 13        | 2.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 12        | 2.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 12        | 2.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 11        | 2.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 11        | 2.33%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 9         | 1.9%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 8         | 1.69%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 8         | 1.69%   |
| Micron Non-Volatile memory controller                                                   | 7         | 1.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 7         | 1.48%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7         | 1.48%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 6         | 1.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 6         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 6         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6         | 1.27%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 1.27%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 5         | 1.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 1.06%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 1.06%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 5         | 1.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.06%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 4         | 0.85%   |
| SK hynix Gold P31 SSD                                                                   | 4         | 0.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 4         | 0.85%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 4         | 0.85%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 4         | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 0.85%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 0.85%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 0.85%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.63%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 3         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 270       | 61.64%  |
| NVMe | 117       | 26.71%  |
| RAID | 25        | 5.71%   |
| IDE  | 25        | 5.71%   |
| SAS  | 1         | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 304       | 88.37%  |
| AMD    | 39        | 11.34%  |
| ARM    | 1         | 0.29%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 4.36%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 2.33%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 2.03%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 2.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 2.03%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.45%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 1.45%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 1.16%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 4         | 1.16%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.16%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 1.16%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 4         | 1.16%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 4         | 1.16%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.16%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 1.16%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 4         | 1.16%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.16%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 3         | 0.87%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.87%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 3         | 0.87%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 0.87%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.87%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 3         | 0.87%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 3         | 0.87%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 3         | 0.87%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.87%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 0.87%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.58%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.58%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 2         | 0.58%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.58%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.58%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 2         | 0.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.58%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 2         | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 2         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 120       | 34.88%  |
| Intel Core i7           | 66        | 19.19%  |
| Intel Core i3           | 42        | 12.21%  |
| Other                   | 21        | 6.1%    |
| AMD Ryzen 5             | 16        | 4.65%   |
| Intel Core 2 Duo        | 14        | 4.07%   |
| Intel Celeron           | 14        | 4.07%   |
| Intel Xeon              | 11        | 3.2%    |
| AMD Ryzen 7             | 7         | 2.03%   |
| Intel Pentium           | 6         | 1.74%   |
| Intel Atom              | 5         | 1.45%   |
| AMD Ryzen 9             | 3         | 0.87%   |
| AMD Ryzen 3             | 3         | 0.87%   |
| Intel Genuine           | 2         | 0.58%   |
| AMD Ryzen 7 PRO         | 2         | 0.58%   |
| AMD A8                  | 2         | 0.58%   |
| AMD A10                 | 2         | 0.58%   |
| Intel Pentium Dual-Core | 1         | 0.29%   |
| Intel Pentium Dual      | 1         | 0.29%   |
| Intel Core M            | 1         | 0.29%   |
| Intel Core i9           | 1         | 0.29%   |
| AMD Ryzen 5 PRO         | 1         | 0.29%   |
| AMD Phenom II X4        | 1         | 0.29%   |
| AMD E                   | 1         | 0.29%   |
| AMD Athlon II X2        | 1         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 148       | 42.9%   |
| 4      | 133       | 38.55%  |
| 6      | 37        | 10.72%  |
| 8      | 17        | 4.93%   |
| 16     | 3         | 0.87%   |
| 12     | 2         | 0.58%   |
| 1      | 2         | 0.58%   |
| 28     | 1         | 0.29%   |
| 24     | 1         | 0.29%   |
| 14     | 1         | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 341       | 98.84%  |
| 2      | 4         | 1.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 263       | 76.45%  |
| 1      | 81        | 23.55%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 339       | 98.26%  |
| Unknown        | 6         | 1.74%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 61        | 17.28%  |
| 0x306a9    | 33        | 9.35%   |
| 0x806ea    | 21        | 5.95%   |
| 0x206a7    | 20        | 5.67%   |
| 0x306c3    | 16        | 4.53%   |
| 0x906ea    | 14        | 3.97%   |
| 0x806ec    | 13        | 3.68%   |
| 0x40651    | 13        | 3.68%   |
| 0x306d4    | 13        | 3.68%   |
| 0x806e9    | 12        | 3.4%    |
| 0x806c1    | 12        | 3.4%    |
| 0x906e9    | 10        | 2.83%   |
| 0x1067a    | 10        | 2.83%   |
| 0x506e3    | 8         | 2.27%   |
| 0x406e3    | 7         | 1.98%   |
| 0x6fd      | 5         | 1.42%   |
| 0x20655    | 5         | 1.42%   |
| 0xa0652    | 4         | 1.13%   |
| 0x906ed    | 4         | 1.13%   |
| 0x08600106 | 4         | 1.13%   |
| 0x08108102 | 4         | 1.13%   |
| 0x906c0    | 3         | 0.85%   |
| 0x806d1    | 3         | 0.85%   |
| 0x706e5    | 3         | 0.85%   |
| 0x706a1    | 3         | 0.85%   |
| 0x406c4    | 3         | 0.85%   |
| 0x206d7    | 3         | 0.85%   |
| 0x0a50000c | 3         | 0.85%   |
| 0x08600104 | 3         | 0.85%   |
| 0x906eb    | 2         | 0.57%   |
| 0x30678    | 2         | 0.57%   |
| 0x08701021 | 2         | 0.57%   |
| 0x08108109 | 2         | 0.57%   |
| 0x06003106 | 2         | 0.57%   |
| 0xa0653    | 1         | 0.28%   |
| 0x906a3    | 1         | 0.28%   |
| 0x90675    | 1         | 0.28%   |
| 0x90672    | 1         | 0.28%   |
| 0x806eb    | 1         | 0.28%   |
| 0x806c2    | 1         | 0.28%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 89        | 25.87%  |
| Haswell          | 39        | 11.34%  |
| IvyBridge        | 38        | 11.05%  |
| SandyBridge      | 25        | 7.27%   |
| Skylake          | 21        | 6.1%    |
| Broadwell        | 16        | 4.65%   |
| Zen 2            | 14        | 4.07%   |
| TigerLake        | 14        | 4.07%   |
| Penryn           | 12        | 3.49%   |
| Zen+             | 9         | 2.62%   |
| Westmere         | 8         | 2.33%   |
| Zen 3            | 7         | 2.03%   |
| Silvermont       | 7         | 2.03%   |
| Icelake          | 6         | 1.74%   |
| Core             | 6         | 1.74%   |
| CometLake        | 6         | 1.74%   |
| Goldmont plus    | 5         | 1.45%   |
| Tremont          | 3         | 0.87%   |
| Alderlake Hybrid | 3         | 0.87%   |
| Unknown          | 3         | 0.87%   |
| Steamroller      | 2         | 0.58%   |
| Nehalem          | 2         | 0.58%   |
| K10              | 2         | 0.58%   |
| Bonnell          | 2         | 0.58%   |
| Zen              | 1         | 0.29%   |
| Puma             | 1         | 0.29%   |
| Piledriver       | 1         | 0.29%   |
| Goldmont         | 1         | 0.29%   |
| Bobcat           | 1         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 252       | 56.63%  |
| Nvidia                     | 127       | 28.54%  |
| AMD                        | 64        | 14.38%  |
| Matrox Electronics Systems | 1         | 0.22%   |
| ASPEED Technology          | 1         | 0.22%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 27        | 5.99%   |
| Intel UHD Graphics 620                                                                   | 23        | 5.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 3.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 3.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 3.1%    |
| Intel HD Graphics 5500                                                                   | 13        | 2.88%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 2.66%   |
| Intel HD Graphics 620                                                                    | 11        | 2.44%   |
| AMD Renoir                                                                               | 10        | 2.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 9         | 2%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 1.77%   |
| Intel HD Graphics 530                                                                    | 8         | 1.77%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 8         | 1.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 1.55%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 1.33%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 6         | 1.33%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 6         | 1.33%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.33%   |
| Intel HD Graphics 630                                                                    | 6         | 1.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.11%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.11%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.11%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.11%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 5         | 1.11%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 0.89%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 4         | 0.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 4         | 0.89%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 0.89%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 0.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 0.89%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.89%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 0.89%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.89%   |
| AMD Cezanne                                                                              | 4         | 0.89%   |
| Nvidia TU117M                                                                            | 3         | 0.67%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 0.67%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 3         | 0.67%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 3         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 160       | 46.38%  |
| Intel + Nvidia  | 69        | 20%     |
| 1 x Nvidia      | 49        | 14.2%   |
| 1 x AMD         | 34        | 9.86%   |
| Intel + AMD     | 20        | 5.8%    |
| AMD + Nvidia    | 8         | 2.32%   |
| 2 x AMD         | 2         | 0.58%   |
| Other           | 1         | 0.29%   |
| Nvidia + ASPEED | 1         | 0.29%   |
| 1 x Matrox      | 1         | 0.29%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 257       | 73.64%  |
| Proprietary | 88        | 25.21%  |
| Unknown     | 4         | 1.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 203       | 58%     |
| 1.01-2.0   | 54        | 15.43%  |
| 3.01-4.0   | 34        | 9.71%   |
| 0.51-1.0   | 17        | 4.86%   |
| 0.01-0.5   | 17        | 4.86%   |
| 5.01-6.0   | 9         | 2.57%   |
| 7.01-8.0   | 7         | 2%      |
| 8.01-16.0  | 7         | 2%      |
| 2.01-3.0   | 2         | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 50        | 13.59%  |
| AU Optronics            | 45        | 12.23%  |
| LG Display              | 43        | 11.68%  |
| Samsung Electronics     | 41        | 11.14%  |
| Chimei Innolux          | 41        | 11.14%  |
| Dell                    | 39        | 10.6%   |
| Goldstar                | 13        | 3.53%   |
| Sharp                   | 11        | 2.99%   |
| PANDA                   | 10        | 2.72%   |
| Lenovo                  | 7         | 1.9%    |
| Hewlett-Packard         | 6         | 1.63%   |
| ViewSonic               | 5         | 1.36%   |
| InfoVision              | 5         | 1.36%   |
| AOC                     | 5         | 1.36%   |
| LGD                     | 4         | 1.09%   |
| ASUSTek Computer        | 4         | 1.09%   |
| Apple                   | 4         | 1.09%   |
| Ancor Communications    | 4         | 1.09%   |
| Panasonic               | 3         | 0.82%   |
| Chi Mei Optoelectronics | 3         | 0.82%   |
| Sony                    | 2         | 0.54%   |
| Philips                 | 2         | 0.54%   |
| MStar                   | 2         | 0.54%   |
| Gigabyte Technology     | 2         | 0.54%   |
| BenQ                    | 2         | 0.54%   |
| Unknown (ADA)           | 1         | 0.27%   |
| RTK                     | 1         | 0.27%   |
| NEC Computers           | 1         | 0.27%   |
| LG Philips              | 1         | 0.27%   |
| LG Electronics          | 1         | 0.27%   |
| Lenovo Group Limited    | 1         | 0.27%   |
| KVM                     | 1         | 0.27%   |
| HPN                     | 1         | 0.27%   |
| HOP                     | 1         | 0.27%   |
| CSO                     | 1         | 0.27%   |
| CHR                     | 1         | 0.27%   |
| CGC                     | 1         | 0.27%   |
| AUS                     | 1         | 0.27%   |
| Acer                    | 1         | 0.27%   |
| Unknown                 | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 5         | 1.34%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch     | 4         | 1.08%   |
| LGD LCD Monitor 1920x1080                                             | 4         | 1.08%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 4         | 1.08%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 4         | 1.08%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 4         | 1.08%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch  | 3         | 0.81%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 0.81%   |
| Panasonic TV MEIC33B 1366x768 521x293mm 23.5-inch                     | 3         | 0.81%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 3         | 0.81%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 0.81%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 3         | 0.81%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.54%   |
| Samsung Electronics SME1720NR SAM0696 1280x1024 338x270mm 17.0-inch   | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 310x170mm 13.9-inch  | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 2         | 0.54%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch          | 2         | 0.54%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 2         | 0.54%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 2         | 0.54%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 2         | 0.54%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 340x190mm 15.3-inch              | 2         | 0.54%   |
| InfoVision LCD Monitor IVO04E3 1366x768 277x156mm 12.5-inch           | 2         | 0.54%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 2         | 0.54%   |
| Dell U2718Q DELA0EC 3840x2160 609x349mm 27.6-inch                     | 2         | 0.54%   |
| Dell U2417H DEL40E8 1920x1080 527x296mm 23.8-inch                     | 2         | 0.54%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.54%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch      | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch       | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 309x174mm 14.0-inch       | 2         | 0.54%   |
| BOE LCD Monitor BOE08E7 1920x1080 344x193mm 15.5-inch                 | 2         | 0.54%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 2         | 0.54%   |
| BOE LCD Monitor BOE07CB 1920x1080 344x193mm 15.5-inch                 | 2         | 0.54%   |
| BOE LCD Monitor BOE070D 1366x768 309x173mm 13.9-inch                  | 2         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 184       | 51.54%  |
| 1366x768 (WXGA)   | 85        | 23.81%  |
| 3840x2160 (4K)    | 16        | 4.48%   |
| 2560x1440 (QHD)   | 14        | 3.92%   |
| 1600x900 (HD+)    | 10        | 2.8%    |
| 1280x1024 (SXGA)  | 9         | 2.52%   |
| 1280x800 (WXGA)   | 7         | 1.96%   |
| 1920x1200 (WUXGA) | 6         | 1.68%   |
| 1440x900 (WXGA+)  | 4         | 1.12%   |
| Unknown           | 3         | 0.84%   |
| 3440x1440         | 2         | 0.56%   |
| 3200x1800 (QHD+)  | 2         | 0.56%   |
| 2880x1800         | 2         | 0.56%   |
| 2560x1600         | 2         | 0.56%   |
| 2160x1440         | 2         | 0.56%   |
| 3840x1080         | 1         | 0.28%   |
| 3456x2160         | 1         | 0.28%   |
| 3286x1080         | 1         | 0.28%   |
| 3000x2000         | 1         | 0.28%   |
| 2736x1824         | 1         | 0.28%   |
| 2560x1080         | 1         | 0.28%   |
| 1920x1280         | 1         | 0.28%   |
| 1360x768          | 1         | 0.28%   |
| 1024x600          | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 111       | 30.33%  |
| 14      | 51        | 13.93%  |
| 13      | 50        | 13.66%  |
| 23      | 20        | 5.46%   |
| 21      | 20        | 5.46%   |
| Unknown | 19        | 5.19%   |
| 27      | 18        | 4.92%   |
| 24      | 16        | 4.37%   |
| 17      | 11        | 3.01%   |
| 18      | 10        | 2.73%   |
| 12      | 9         | 2.46%   |
| 19      | 6         | 1.64%   |
| 20      | 5         | 1.37%   |
| 84      | 3         | 0.82%   |
| 11      | 3         | 0.82%   |
| 34      | 2         | 0.55%   |
| 31      | 2         | 0.55%   |
| 54      | 1         | 0.27%   |
| 52      | 1         | 0.27%   |
| 46      | 1         | 0.27%   |
| 42      | 1         | 0.27%   |
| 40      | 1         | 0.27%   |
| 28      | 1         | 0.27%   |
| 25      | 1         | 0.27%   |
| 16      | 1         | 0.27%   |
| 10      | 1         | 0.27%   |
| 7       | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 200       | 54.79%  |
| 501-600     | 52        | 14.25%  |
| 401-500     | 38        | 10.41%  |
| 201-300     | 28        | 7.67%   |
| Unknown     | 19        | 5.21%   |
| 351-400     | 12        | 3.29%   |
| 601-700     | 5         | 1.37%   |
| 1501-2000   | 3         | 0.82%   |
| 1001-1500   | 3         | 0.82%   |
| 701-800     | 2         | 0.55%   |
| 801-900     | 1         | 0.27%   |
| 101-200     | 1         | 0.27%   |
| 901-1000    | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 280       | 83.33%  |
| 16/10   | 22        | 6.55%   |
| Unknown | 18        | 5.36%   |
| 5/4     | 7         | 2.08%   |
| 3/2     | 6         | 1.79%   |
| 21/9    | 3         | 0.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 110       | 29.97%  |
| 81-90          | 90        | 24.52%  |
| 201-250        | 50        | 13.62%  |
| Unknown        | 19        | 5.18%   |
| 301-350        | 18        | 4.9%    |
| 151-200        | 16        | 4.36%   |
| 141-150        | 13        | 3.54%   |
| 71-80          | 12        | 3.27%   |
| 61-70          | 8         | 2.18%   |
| 121-130        | 6         | 1.63%   |
| More than 1000 | 5         | 1.36%   |
| 251-300        | 5         | 1.36%   |
| 351-500        | 4         | 1.09%   |
| 51-60          | 3         | 0.82%   |
| 501-1000       | 3         | 0.82%   |
| 41-50          | 1         | 0.27%   |
| 1-40           | 1         | 0.27%   |
| 131-140        | 1         | 0.27%   |
| 111-120        | 1         | 0.27%   |
| 91-100         | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 136       | 37.78%  |
| 101-120       | 98        | 27.22%  |
| 51-100        | 77        | 21.39%  |
| 161-240       | 20        | 5.56%   |
| Unknown       | 19        | 5.28%   |
| More than 240 | 7         | 1.94%   |
| 1-50          | 3         | 0.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 296       | 85.06%  |
| 2     | 38        | 10.92%  |
| 0     | 10        | 2.87%   |
| 3     | 4         | 1.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 199       | 36.85%  |
| Intel                                  | 183       | 33.89%  |
| Qualcomm Atheros                       | 68        | 12.59%  |
| Broadcom                               | 28        | 5.19%   |
| Ralink Technology                      | 9         | 1.67%   |
| Broadcom Limited                       | 8         | 1.48%   |
| MediaTek                               | 7         | 1.3%    |
| Marvell Technology Group               | 6         | 1.11%   |
| TP-Link                                | 5         | 0.93%   |
| ASIX Electronics                       | 4         | 0.74%   |
| Samsung Electronics                    | 3         | 0.56%   |
| Hewlett-Packard                        | 3         | 0.56%   |
| D-Link                                 | 3         | 0.56%   |
| Ralink                                 | 2         | 0.37%   |
| Xiaomi                                 | 1         | 0.19%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.19%   |
| SEGGER                                 | 1         | 0.19%   |
| Qualcomm Atheros Communications        | 1         | 0.19%   |
| Qualcomm                               | 1         | 0.19%   |
| ICS Advent                             | 1         | 0.19%   |
| Huawei Technologies                    | 1         | 0.19%   |
| Foxconn / Hon Hai                      | 1         | 0.19%   |
| Ericsson Business Mobile Networks      | 1         | 0.19%   |
| Edimax Technology                      | 1         | 0.19%   |
| ASUSTek Computer                       | 1         | 0.19%   |
| Aquantia                               | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 145       | 23.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 4.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 16        | 2.57%   |
| Intel Wireless 3165                                               | 16        | 2.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 2.57%   |
| Intel Wi-Fi 6 AX200                                               | 15        | 2.41%   |
| Intel Wireless 8265 / 8275                                        | 14        | 2.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13        | 2.09%   |
| Intel Wireless 7265                                               | 12        | 1.93%   |
| Intel Wi-Fi 6 AX201                                               | 11        | 1.77%   |
| Broadcom BCM43142 802.11b/g/n                                     | 11        | 1.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 10        | 1.61%   |
| Intel Wireless 7260                                               | 9         | 1.45%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8         | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 1.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 8         | 1.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.13%   |
| Intel Centrino Ultimate-N 6300                                    | 7         | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 0.96%   |
| Intel Wireless 8260                                               | 6         | 0.96%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.96%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 0.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5         | 0.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 0.8%    |
| Ralink MT7601U Wireless Adapter                                   | 5         | 0.8%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 0.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 0.64%   |
| Intel Wireless 3160                                               | 4         | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.64%   |
| Intel I210 Gigabit Network Connection                             | 4         | 0.64%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.64%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 3         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 148       | 49.17%  |
| Qualcomm Atheros                | 55        | 18.27%  |
| Realtek Semiconductor           | 38        | 12.62%  |
| Broadcom                        | 22        | 7.31%   |
| Ralink Technology               | 9         | 2.99%   |
| Broadcom Limited                | 8         | 2.66%   |
| MediaTek                        | 6         | 1.99%   |
| TP-Link                         | 5         | 1.66%   |
| D-Link                          | 3         | 1%      |
| Ralink                          | 2         | 0.66%   |
| Xiaomi                          | 1         | 0.33%   |
| Qualcomm Atheros Communications | 1         | 0.33%   |
| Marvell Technology Group        | 1         | 0.33%   |
| Edimax Technology               | 1         | 0.33%   |
| ASUSTek Computer                | 1         | 0.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 16        | 5.3%    |
| Intel Wireless 3165                                            | 16        | 5.3%    |
| Intel Wi-Fi 6 AX200                                            | 15        | 4.97%   |
| Intel Wireless 8265 / 8275                                     | 14        | 4.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 13        | 4.3%    |
| Intel Wireless 7265                                            | 12        | 3.97%   |
| Intel Wi-Fi 6 AX201                                            | 11        | 3.64%   |
| Broadcom BCM43142 802.11b/g/n                                  | 11        | 3.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 10        | 3.31%   |
| Intel Wireless 7260                                            | 9         | 2.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 8         | 2.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 2.65%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 8         | 2.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 2.32%   |
| Intel Centrino Ultimate-N 6300                                 | 7         | 2.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 1.99%   |
| Intel Wireless 8260                                            | 6         | 1.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 1.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 1.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5         | 1.66%   |
| Ralink MT7601U Wireless Adapter                                | 5         | 1.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 1.66%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 1.66%   |
| Intel Wireless 3160                                            | 4         | 1.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.32%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 3         | 0.99%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 0.99%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 3         | 0.99%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 3         | 0.99%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 0.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 0.99%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.66%   |
| Realtek 802.11ac NIC                                           | 2         | 0.66%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 0.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.66%   |
| Intel Wireless-AC 9260                                         | 2         | 0.66%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 184       | 59.16%  |
| Intel                                  | 79        | 25.4%   |
| Qualcomm Atheros                       | 19        | 6.11%   |
| Broadcom                               | 8         | 2.57%   |
| Marvell Technology Group               | 5         | 1.61%   |
| ASIX Electronics                       | 4         | 1.29%   |
| Samsung Electronics                    | 3         | 0.96%   |
| Hewlett-Packard                        | 2         | 0.64%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.32%   |
| Qualcomm                               | 1         | 0.32%   |
| MediaTek                               | 1         | 0.32%   |
| ICS Advent                             | 1         | 0.32%   |
| Huawei Technologies                    | 1         | 0.32%   |
| Foxconn / Hon Hai                      | 1         | 0.32%   |
| Aquantia                               | 1         | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 145       | 45.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 8.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 5.05%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.89%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 1.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.26%   |
| Intel I210 Gigabit Network Connection                             | 4         | 1.26%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.26%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.26%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.26%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 1.26%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.95%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.95%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.95%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.95%   |
| ASIX AX88772A Fast Ethernet                                       | 3         | 0.95%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.63%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2         | 0.63%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.63%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.63%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.63%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.63%   |
| Broadcom NetLink BCM5786 Gigabit Ethernet PCI Express             | 2         | 0.63%   |
| Sony Ericsson Mobile AB D6503                                     | 1         | 0.32%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.32%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.32%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.32%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.32%   |
| Qualcomm Mobile Router                                            | 1         | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 294       | 50.09%  |
| WiFi     | 290       | 49.4%   |
| Modem    | 3         | 0.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 245       | 67.87%  |
| Ethernet | 116       | 32.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 218       | 63.19%  |
| 1     | 117       | 33.91%  |
| 3     | 7         | 2.03%   |
| 0     | 3         | 0.87%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 278       | 79.2%   |
| Yes  | 73        | 20.8%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 124       | 49.01%  |
| Qualcomm Atheros Communications | 29        | 11.46%  |
| Broadcom                        | 22        | 8.7%    |
| Realtek Semiconductor           | 20        | 7.91%   |
| Cambridge Silicon Radio         | 15        | 5.93%   |
| IMC Networks                    | 12        | 4.74%   |
| Lite-On Technology              | 10        | 3.95%   |
| Apple                           | 5         | 1.98%   |
| Hewlett-Packard                 | 4         | 1.58%   |
| Foxconn / Hon Hai               | 4         | 1.58%   |
| Dell                            | 3         | 1.19%   |
| Toshiba                         | 1         | 0.4%    |
| MediaTek                        | 1         | 0.4%    |
| Marvell Semiconductor           | 1         | 0.4%    |
| Conwise Technology              | 1         | 0.4%    |
| Alps Electric                   | 1         | 0.4%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 56        | 22.13%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 22        | 8.7%    |
| Intel AX201 Bluetooth                               | 18        | 7.11%   |
| Qualcomm Atheros  Bluetooth Device                  | 16        | 6.32%   |
| Intel AX200 Bluetooth                               | 15        | 5.93%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 15        | 5.93%   |
| Realtek Bluetooth Radio                             | 11        | 4.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 2.37%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 2.37%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 1.58%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.58%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 1.58%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 1.58%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 1.58%   |
| Apple Bluetooth Host Controller                     | 4         | 1.58%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.19%   |
| Intel AX210 Bluetooth                               | 3         | 1.19%   |
| IMC Networks Wireless_Device                        | 3         | 1.19%   |
| IMC Networks Bluetooth Radio                        | 3         | 1.19%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.19%   |
| Broadcom HP Portable SoftSailing                    | 3         | 1.19%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.79%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.79%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.79%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.79%   |
| Intel Bluetooth Device                              | 2         | 0.79%   |
| IMC Networks Bluetooth Device                       | 2         | 0.79%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.79%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.79%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.79%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.4%    |
| Realtek RTL8723B Bluetooth                          | 1         | 0.4%    |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.4%    |
| MediaTek Wireless_Device                            | 1         | 0.4%    |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 0.4%    |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.4%    |
| Lite-On Bluetooth Radio                             | 1         | 0.4%    |
| Lite-On BCM43142A0                                  | 1         | 0.4%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 298       | 65.07%  |
| Nvidia                    | 84        | 18.34%  |
| AMD                       | 50        | 10.92%  |
| C-Media Electronics       | 4         | 0.87%   |
| Creative Labs             | 3         | 0.66%   |
| Realtek Semiconductor     | 2         | 0.44%   |
| JMTek                     | 2         | 0.44%   |
| Generalplus Technology    | 2         | 0.44%   |
| Apple                     | 2         | 0.44%   |
| Shenzhen Rapoo Technology | 1         | 0.22%   |
| Plantronics               | 1         | 0.22%   |
| OPPO Electronics          | 1         | 0.22%   |
| Nordic Semiconductor ASA  | 1         | 0.22%   |
| Logitech                  | 1         | 0.22%   |
| GYROCOM C&C               | 1         | 0.22%   |
| GN Netcom                 | 1         | 0.22%   |
| Elgato Systems            | 1         | 0.22%   |
| Creative Technology       | 1         | 0.22%   |
| AGPTek                    | 1         | 0.22%   |
| Unknown                   | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 47        | 8.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 34        | 6.39%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 25        | 4.7%    |
| AMD Family 17h/19h HD Audio Controller                                     | 25        | 4.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 22        | 4.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 21        | 3.95%   |
| Intel Broadwell-U Audio Controller                                         | 15        | 2.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14        | 2.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 14        | 2.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 2.63%   |
| Intel Haswell-ULT HD Audio Controller                                      | 14        | 2.63%   |
| Intel 8 Series HD Audio Controller                                         | 14        | 2.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14        | 2.63%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 2.07%   |
| Intel Comet Lake PCH-LP cAVS                                               | 10        | 1.88%   |
| Nvidia TU116 High Definition Audio Controller                              | 9         | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.69%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 9         | 1.69%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8         | 1.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 1.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 1.5%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8         | 1.5%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 1.32%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6         | 1.13%   |
| Nvidia GF108 High Definition Audio Controller                              | 6         | 1.13%   |
| Intel CM238 HD Audio Controller                                            | 6         | 1.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 1.13%   |
| Nvidia High Definition Audio Controller                                    | 5         | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 0.94%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 0.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 0.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 0.94%   |
| Intel 200 Series PCH HD Audio                                              | 5         | 0.94%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 0.94%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 0.75%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 0.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 0.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 0.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 0.75%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 64        | 25.4%   |
| SK hynix              | 47        | 18.65%  |
| Kingston              | 42        | 16.67%  |
| Micron Technology     | 28        | 11.11%  |
| Corsair               | 15        | 5.95%   |
| Unknown               | 11        | 4.37%   |
| G.Skill               | 10        | 3.97%   |
| Crucial               | 10        | 3.97%   |
| Ramaxel Technology    | 7         | 2.78%   |
| Kingmax               | 5         | 1.98%   |
| Elpida                | 3         | 1.19%   |
| A-DATA Technology     | 3         | 1.19%   |
| Team                  | 2         | 0.79%   |
| Apacer                | 2         | 0.79%   |
| Unknown (7FE0)        | 1         | 0.4%    |
| Patriot               | 1         | 0.4%    |
| Kingmax Semiconductor | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 6         | 2.19%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 5         | 1.82%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 4         | 1.46%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 4         | 1.46%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s          | 4         | 1.46%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 4         | 1.46%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 3         | 1.09%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s         | 3         | 1.09%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 3         | 1.09%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 3         | 1.09%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s           | 3         | 1.09%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s           | 3         | 1.09%   |
| Corsair RAM CMK8GX4M1A2666C16 8GB DIMM DDR4 3000MT/s           | 3         | 1.09%   |
| Unknown RAM Module 1GB DIMM 800MT/s                            | 2         | 0.73%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 2         | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.73%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 0.73%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s   | 2         | 0.73%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 2         | 0.73%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s        | 2         | 0.73%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 0.73%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s         | 2         | 0.73%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                 | 2         | 0.73%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s          | 2         | 0.73%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 2         | 0.73%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 0.73%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 2         | 0.73%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s      | 2         | 0.73%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 2         | 0.73%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s           | 2         | 0.73%   |
| Micron RAM 53E1G32D4NQ-046WTE 4GB Row Of Chips LPDDR4 3200MT/s | 2         | 0.73%   |
| Kingston RAM 99U5428-040.A01LF 4GB SODIMM DDR3 1334MT/s        | 2         | 0.73%   |
| G.Skill RAM F4-2666C19-8GRS 8192MB SODIMM DDR4 2667MT/s        | 2         | 0.73%   |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s          | 2         | 0.73%   |
| Crucial RAM CT4G4SFS824A.C8FF 4GB SODIMM DDR4 2400MT/s         | 2         | 0.73%   |
| Crucial RAM BLS8G4D240FSEK.8FBD 8GB DIMM DDR4 2400MT/s         | 2         | 0.73%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s            | 1         | 0.36%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                 | 1         | 0.36%   |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 110       | 54.46%  |
| DDR3    | 70        | 34.65%  |
| LPDDR4  | 7         | 3.47%   |
| LPDDR3  | 5         | 2.48%   |
| DDR2    | 4         | 1.98%   |
| Unknown | 2         | 0.99%   |
| SDRAM   | 1         | 0.5%    |
| LPDDR5  | 1         | 0.5%    |
| DDR5    | 1         | 0.5%    |
| DDR     | 1         | 0.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 136       | 67%     |
| DIMM         | 52        | 25.62%  |
| Row Of Chips | 15        | 7.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 88        | 40.37%  |
| 4096  | 79        | 36.24%  |
| 16384 | 29        | 13.3%   |
| 2048  | 15        | 6.88%   |
| 1024  | 6         | 2.75%   |
| 32768 | 1         | 0.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 50        | 21.55%  |
| 2667    | 47        | 20.26%  |
| 3200    | 39        | 16.81%  |
| 2400    | 22        | 9.48%   |
| 1333    | 14        | 6.03%   |
| 2133    | 10        | 4.31%   |
| 3000    | 6         | 2.59%   |
| 1867    | 6         | 2.59%   |
| 1334    | 6         | 2.59%   |
| 8400    | 3         | 1.29%   |
| 800     | 3         | 1.29%   |
| 4267    | 2         | 0.86%   |
| 2800    | 2         | 0.86%   |
| 2666    | 2         | 0.86%   |
| 1866    | 2         | 0.86%   |
| 1067    | 2         | 0.86%   |
| 667     | 2         | 0.86%   |
| 6400    | 1         | 0.43%   |
| 4800    | 1         | 0.43%   |
| 4199    | 1         | 0.43%   |
| 3666    | 1         | 0.43%   |
| 3600    | 1         | 0.43%   |
| 3466    | 1         | 0.43%   |
| 3334    | 1         | 0.43%   |
| 3266    | 1         | 0.43%   |
| 3007    | 1         | 0.43%   |
| 2933    | 1         | 0.43%   |
| 1066    | 1         | 0.43%   |
| 200     | 1         | 0.43%   |
| 133     | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Ricoh           | 1         | 33.33%  |
| Hewlett-Packard | 1         | 33.33%  |
| Canon           | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Ricoh Printing Support   | 1         | 33.33%  |
| HP LaserJet P3010 Series | 1         | 33.33%  |
| Canon LBP6030w/6018w     | 1         | 33.33%  |

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
| Chicony Electronics                    | 50        | 21.83%  |
| Microdia                               | 34        | 14.85%  |
| IMC Networks                           | 30        | 13.1%   |
| Sunplus Innovation Technology          | 23        | 10.04%  |
| Realtek Semiconductor                  | 18        | 7.86%   |
| Acer                                   | 12        | 5.24%   |
| Syntek                                 | 9         | 3.93%   |
| Quanta                                 | 9         | 3.93%   |
| Logitech                               | 8         | 3.49%   |
| Lite-On Technology                     | 6         | 2.62%   |
| Suyin                                  | 5         | 2.18%   |
| Apple                                  | 5         | 2.18%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 1.75%   |
| Silicon Motion                         | 2         | 0.87%   |
| Ricoh                                  | 2         | 0.87%   |
| Luxvisions Innotech Limited            | 2         | 0.87%   |
| Alcor Micro                            | 2         | 0.87%   |
| Sonix Technology                       | 1         | 0.44%   |
| Samsung Electronics                    | 1         | 0.44%   |
| Lenovo                                 | 1         | 0.44%   |
| KYE Systems (Mouse Systems)            | 1         | 0.44%   |
| Intel                                  | 1         | 0.44%   |
| IDS Imaging Development Systems        | 1         | 0.44%   |
| Denron                                 | 1         | 0.44%   |
| ALi                                    | 1         | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                 | 15        | 6.52%   |
| Chicony Integrated Camera                     | 14        | 6.09%   |
| Sunplus Integrated_Webcam_HD                  | 11        | 4.78%   |
| IMC Networks Integrated Camera                | 8         | 3.48%   |
| Realtek Integrated_Webcam_HD                  | 7         | 3.04%   |
| Microdia Laptop_Integrated_Webcam_HD          | 7         | 3.04%   |
| Chicony HD WebCam                             | 7         | 3.04%   |
| Syntek Integrated Camera                      | 6         | 2.61%   |
| IMC Networks USB2.0 VGA UVC WebCam            | 6         | 2.61%   |
| IMC Networks USB2.0 HD UVC WebCam             | 5         | 2.17%   |
| Chicony HP HD Camera                          | 5         | 2.17%   |
| Realtek Integrated Webcam                     | 4         | 1.74%   |
| Logitech Webcam C270                          | 4         | 1.74%   |
| Chicony HP TrueVision HD Camera               | 4         | 1.74%   |
| Acer ThinkPad Integrated Camera               | 4         | 1.74%   |
| Sunplus Laptop_Integrated_Webcam_FHD          | 3         | 1.3%    |
| Quanta VGA WebCam                             | 3         | 1.3%    |
| Microdia Integrated Webcam                    | 3         | 1.3%    |
| IMC Networks VGA UVC WebCam                   | 3         | 1.3%    |
| IMC Networks USB2.0 UVC HD Webcam             | 3         | 1.3%    |
| Chicony Integrated HP HD Webcam               | 3         | 1.3%    |
| Chicony HP HD Webcam                          | 3         | 1.3%    |
| Apple iPhone 5/5C/5S/6/SE                     | 3         | 1.3%    |
| Acer Integrated Camera                        | 3         | 1.3%    |
| Syntek Lenovo EasyCamera                      | 2         | 0.87%   |
| Sunplus Asus Webcam                           | 2         | 0.87%   |
| Realtek Integrated Webcam HD                  | 2         | 0.87%   |
| Quanta HP TrueVision HD Camera                | 2         | 0.87%   |
| Quanta HP HD Camera                           | 2         | 0.87%   |
| Microdia Webcam Vitade AF                     | 2         | 0.87%   |
| Microdia Integrated Webcam HD                 | 2         | 0.87%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 0.87%   |
| Lite-On Integrated Camera                     | 2         | 0.87%   |
| Lite-On HP HD Camera                          | 2         | 0.87%   |
| IMC Networks USB Camera                       | 2         | 0.87%   |
| Chicony TOSHIBA Web Camera - HD               | 2         | 0.87%   |
| Apple FaceTime HD Camera                      | 2         | 0.87%   |
| Acer SunplusIT Integrated Camera              | 2         | 0.87%   |
| Syntek USB Video Device                       | 1         | 0.43%   |
| Suyin Laptop_Integrated_Webcam_HD             | 1         | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 33        | 55%     |
| Shenzhen Goodix Technology | 11        | 18.33%  |
| Synaptics                  | 10        | 16.67%  |
| LighTuning Technology      | 2         | 3.33%   |
| Elan Microelectronics      | 2         | 3.33%   |
| Upek                       | 1         | 1.67%   |
| STMicroelectronics         | 1         | 1.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 13.33%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 11.67%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 10%     |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 6.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 6.67%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 5%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 5%      |
| Unknown                                                                    | 3         | 5%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 3.33%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 3.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 3.33%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 3.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.33%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.33%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.67%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.67%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.67%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.67%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.67%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 6         | 75%     |
| Upek        | 1         | 12.5%   |
| Alcor Micro | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 241       | 68.86%  |
| 1     | 90        | 25.71%  |
| 2     | 16        | 4.57%   |
| 3     | 2         | 0.57%   |
| 5     | 1         | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 59        | 45.74%  |
| Graphics card            | 22        | 17.05%  |
| Net/wireless             | 12        | 9.3%    |
| Chipcard                 | 8         | 6.2%    |
| Net/ethernet             | 5         | 3.88%   |
| Communication controller | 5         | 3.88%   |
| Multimedia controller    | 4         | 3.1%    |
| Camera                   | 4         | 3.1%    |
| Unassigned class         | 3         | 2.33%   |
| Bluetooth                | 3         | 2.33%   |
| Card reader              | 2         | 1.55%   |
| Storage                  | 1         | 0.78%   |
| Sound                    | 1         | 0.78%   |

