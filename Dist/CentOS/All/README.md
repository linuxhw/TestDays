CentOS - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for CentOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/CentOS/Desktop/README.md) and [notebooks](/Dist/CentOS/Notebook/README.md).

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

Total: 1055

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 03TJ75 A00                  | Desktop     | [e082a50dde](https://linux-hardware.org/?probe=e082a50dde) | Nov 02, 2023 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [249f2a954a](https://linux-hardware.org/?probe=249f2a954a) | Nov 02, 2023 |
| MSI           | MEG Z790 ACE                | Desktop     | [41d0e4fddd](https://linux-hardware.org/?probe=41d0e4fddd) | Oct 24, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [8b5e97d193](https://linux-hardware.org/?probe=8b5e97d193) | Oct 21, 2023 |
| Dell          | 0DT021 A00                  | Server      | [f8f771286c](https://linux-hardware.org/?probe=f8f771286c) | Oct 18, 2023 |
| Dell          | 0CN7X8 A04                  | Server      | [2926458524](https://linux-hardware.org/?probe=2926458524) | Oct 17, 2023 |
| Dell          | 0CN7X8 A04                  | Server      | [10029a3309](https://linux-hardware.org/?probe=10029a3309) | Oct 17, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [97cf97582e](https://linux-hardware.org/?probe=97cf97582e) | Oct 16, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [f23d8804a7](https://linux-hardware.org/?probe=f23d8804a7) | Oct 11, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [21a3b6601a](https://linux-hardware.org/?probe=21a3b6601a) | Oct 10, 2023 |
| Acer          | Aspire XC-830               | Desktop     | [c7453db83a](https://linux-hardware.org/?probe=c7453db83a) | Oct 10, 2023 |
| Dell          | 088DT1 A00                  | Desktop     | [4e85b8e145](https://linux-hardware.org/?probe=4e85b8e145) | Oct 03, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [2867e39109](https://linux-hardware.org/?probe=2867e39109) | Sep 23, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [8d59e8d305](https://linux-hardware.org/?probe=8d59e8d305) | Sep 20, 2023 |
| Fanless Mi... | Rev JSL62                   | Mini pc     | [adbe2f1ead](https://linux-hardware.org/?probe=adbe2f1ead) | Sep 17, 2023 |
| Dell          | 0HJK12 A03                  | Server      | [b4ec3650ef](https://linux-hardware.org/?probe=b4ec3650ef) | Sep 11, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [ecf1a70c5d](https://linux-hardware.org/?probe=ecf1a70c5d) | Sep 08, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [6ffee2798a](https://linux-hardware.org/?probe=6ffee2798a) | Sep 08, 2023 |
| Intel         | NUC12WSBi5 M46425-304       | Mini pc     | [d75c936b50](https://linux-hardware.org/?probe=d75c936b50) | Sep 06, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [b0f558c0a2](https://linux-hardware.org/?probe=b0f558c0a2) | Aug 31, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [61cb58f13b](https://linux-hardware.org/?probe=61cb58f13b) | Aug 23, 2023 |
| Dell          | 0DT021 A00                  | Server      | [8598fe0d4b](https://linux-hardware.org/?probe=8598fe0d4b) | Aug 22, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [149cb27e46](https://linux-hardware.org/?probe=149cb27e46) | Aug 18, 2023 |
| Gigabyte      | H270M-D3H-CF                | Desktop     | [5c8f4ac5c0](https://linux-hardware.org/?probe=5c8f4ac5c0) | Aug 16, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [dfcebaef82](https://linux-hardware.org/?probe=dfcebaef82) | Aug 09, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [b9d8025a54](https://linux-hardware.org/?probe=b9d8025a54) | Aug 05, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [a650338ead](https://linux-hardware.org/?probe=a650338ead) | Aug 04, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [90e7667180](https://linux-hardware.org/?probe=90e7667180) | Aug 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [888c56f232](https://linux-hardware.org/?probe=888c56f232) | Aug 01, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [993a10a30b](https://linux-hardware.org/?probe=993a10a30b) | Aug 01, 2023 |
| Supermicro    | X7DWE                       | Desktop     | [a35080b0e5](https://linux-hardware.org/?probe=a35080b0e5) | Jul 31, 2023 |
| Dell          | 07978V A05                  | Server      | [8e1deb831f](https://linux-hardware.org/?probe=8e1deb831f) | Jul 26, 2023 |
| Gigabyte      | MP32-AR0                    | Server      | [8b0443884b](https://linux-hardware.org/?probe=8b0443884b) | Jul 25, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [bcd4e93239](https://linux-hardware.org/?probe=bcd4e93239) | Jul 22, 2023 |
| Dell          | System XPS L702X            | Notebook    | [21f1d68bc1](https://linux-hardware.org/?probe=21f1d68bc1) | Jul 21, 2023 |
| MSI           | 870-G45                     | Desktop     | [af7442187f](https://linux-hardware.org/?probe=af7442187f) | Jul 20, 2023 |
| ASUSTek       | P5QL-CM                     | Desktop     | [65fe34f4ce](https://linux-hardware.org/?probe=65fe34f4ce) | Jul 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [8ff38f3782](https://linux-hardware.org/?probe=8ff38f3782) | Jul 18, 2023 |
| MSI           | 870-G45                     | Desktop     | [9fff23ac6a](https://linux-hardware.org/?probe=9fff23ac6a) | Jul 14, 2023 |
| Supermicro    | H11DSi                      | Server      | [b52c1f494c](https://linux-hardware.org/?probe=b52c1f494c) | Jul 11, 2023 |
| Intel         | NUC7i3BNB J22859-315        | Mini pc     | [8b2dd0b294](https://linux-hardware.org/?probe=8b2dd0b294) | Jul 07, 2023 |
| Supermicro    | H11DSi                      | Server      | [39710a4809](https://linux-hardware.org/?probe=39710a4809) | Jul 02, 2023 |
| Supermicro    | H11DSi                      | Server      | [04bac4b25f](https://linux-hardware.org/?probe=04bac4b25f) | Jul 01, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [49c764507c](https://linux-hardware.org/?probe=49c764507c) | Jul 01, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [a7bcb95d10](https://linux-hardware.org/?probe=a7bcb95d10) | Jun 30, 2023 |
| IBM           | 69Y1006 SIT                 | Server      | [b34e147b1c](https://linux-hardware.org/?probe=b34e147b1c) | Jun 25, 2023 |
| Intel         | DG35EC AAE29266-209         | Desktop     | [bfdb13f626](https://linux-hardware.org/?probe=bfdb13f626) | Jun 20, 2023 |
| IBM           | 69Y4438                     | Server      | [665f34b5bc](https://linux-hardware.org/?probe=665f34b5bc) | Jun 16, 2023 |
| Dell          | 09HY2Y A00                  | Server      | [812a113fa7](https://linux-hardware.org/?probe=812a113fa7) | Jun 16, 2023 |
| Gateway       | H61H2-AD V1.0               | Desktop     | [9a34a9295c](https://linux-hardware.org/?probe=9a34a9295c) | Jun 15, 2023 |
| Supermicro    | X9DAi                       | Desktop     | [07f73cff06](https://linux-hardware.org/?probe=07f73cff06) | Jun 12, 2023 |
| Supermicro    | X10DRG-Q                    | Desktop     | [c03c5ea1b9](https://linux-hardware.org/?probe=c03c5ea1b9) | Jun 08, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [8dce973d6b](https://linux-hardware.org/?probe=8dce973d6b) | Jun 02, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [d93dbf6db3](https://linux-hardware.org/?probe=d93dbf6db3) | Jun 01, 2023 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [16c7ca187a](https://linux-hardware.org/?probe=16c7ca187a) | Jun 01, 2023 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [a69366e2b7](https://linux-hardware.org/?probe=a69366e2b7) | May 29, 2023 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [07202660b9](https://linux-hardware.org/?probe=07202660b9) | May 26, 2023 |
| Dell          | 08DM12 A05                  | Server      | [a6c10986c9](https://linux-hardware.org/?probe=a6c10986c9) | May 19, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [7dca952cb0](https://linux-hardware.org/?probe=7dca952cb0) | May 16, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [1515a37b97](https://linux-hardware.org/?probe=1515a37b97) | May 06, 2023 |
| Acer          | Predator G3-605             | Desktop     | [6f91022c83](https://linux-hardware.org/?probe=6f91022c83) | May 04, 2023 |
| Colorful T... | CVN Z590 GAMING PRO V20     | Desktop     | [209ec5e477](https://linux-hardware.org/?probe=209ec5e477) | Apr 28, 2023 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | Notebook    | [61408603be](https://linux-hardware.org/?probe=61408603be) | Apr 21, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [8b0573684a](https://linux-hardware.org/?probe=8b0573684a) | Apr 12, 2023 |
| Dell          | 0MW50N A01                  | Desktop     | [dd68ce3b10](https://linux-hardware.org/?probe=dd68ce3b10) | Apr 11, 2023 |
| Lenovo        | ThinkPad T420 4178A4G       | Notebook    | [206861226d](https://linux-hardware.org/?probe=206861226d) | Apr 09, 2023 |
| Lenovo        | ThinkPad X260 20F5S1H800    | Notebook    | [752a80fb19](https://linux-hardware.org/?probe=752a80fb19) | Apr 03, 2023 |
| Intel         | NUC12WSBi5 M63398-302       | Mini pc     | [785a41f4e9](https://linux-hardware.org/?probe=785a41f4e9) | Apr 02, 2023 |
| AZW           | U59                         | Desktop     | [ad59e8fe21](https://linux-hardware.org/?probe=ad59e8fe21) | Apr 02, 2023 |
| HP            | ProLiant DL380 G5           | Server      | [8cf84909e3](https://linux-hardware.org/?probe=8cf84909e3) | Mar 31, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [24b14fa9bb](https://linux-hardware.org/?probe=24b14fa9bb) | Mar 30, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [f99591fe95](https://linux-hardware.org/?probe=f99591fe95) | Mar 26, 2023 |
| MSI           | Z77A-GD80                   | Desktop     | [bcb120034c](https://linux-hardware.org/?probe=bcb120034c) | Mar 21, 2023 |
| Dell          | 0NDYHG A00                  | Desktop     | [f007ab3692](https://linux-hardware.org/?probe=f007ab3692) | Mar 20, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [d148f91b52](https://linux-hardware.org/?probe=d148f91b52) | Mar 15, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [eecf7c5d8b](https://linux-hardware.org/?probe=eecf7c5d8b) | Mar 13, 2023 |
| MSI           | Z77A-GD80                   | Desktop     | [28e364aa1a](https://linux-hardware.org/?probe=28e364aa1a) | Mar 11, 2023 |
| MSI           | Z77A-GD80                   | Desktop     | [932497a278](https://linux-hardware.org/?probe=932497a278) | Mar 11, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [23b5dbe59d](https://linux-hardware.org/?probe=23b5dbe59d) | Mar 11, 2023 |
| MSI           | Z77A-GD80                   | Desktop     | [3b63adee43](https://linux-hardware.org/?probe=3b63adee43) | Mar 09, 2023 |
| MSI           | Z77A-GD80                   | Desktop     | [f447b1afca](https://linux-hardware.org/?probe=f447b1afca) | Mar 09, 2023 |
| Dell          | 03TJ75 A00                  | Desktop     | [305d373dcd](https://linux-hardware.org/?probe=305d373dcd) | Mar 07, 2023 |
| Dell          | 03TJ75 A00                  | Desktop     | [31c6d1fb3e](https://linux-hardware.org/?probe=31c6d1fb3e) | Mar 07, 2023 |
| ASUSTek       | Q550LF                      | Notebook    | [793bf0d1d8](https://linux-hardware.org/?probe=793bf0d1d8) | Mar 06, 2023 |
| Supermicro    | X11SCL-F                    | Server      | [ef92c1fc32](https://linux-hardware.org/?probe=ef92c1fc32) | Mar 03, 2023 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [ca09a29082](https://linux-hardware.org/?probe=ca09a29082) | Mar 01, 2023 |
| Supermicro    | X10DAI                      | Desktop     | [b777ed256f](https://linux-hardware.org/?probe=b777ed256f) | Mar 01, 2023 |
| HP            | 0AECh D                     | Desktop     | [5baf25e8af](https://linux-hardware.org/?probe=5baf25e8af) | Feb 26, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [f82cea1be8](https://linux-hardware.org/?probe=f82cea1be8) | Feb 23, 2023 |
| HP            | 17E2                        | Mini pc     | [4db80b6f90](https://linux-hardware.org/?probe=4db80b6f90) | Feb 21, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [f1b85863bc](https://linux-hardware.org/?probe=f1b85863bc) | Feb 20, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [a7270cf962](https://linux-hardware.org/?probe=a7270cf962) | Feb 19, 2023 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [3406527d4b](https://linux-hardware.org/?probe=3406527d4b) | Feb 17, 2023 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [e112bdfd74](https://linux-hardware.org/?probe=e112bdfd74) | Feb 17, 2023 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [df9a9f0b90](https://linux-hardware.org/?probe=df9a9f0b90) | Feb 14, 2023 |
| Supermicro    | X9DAi                       | Desktop     | [546ea7c2e8](https://linux-hardware.org/?probe=546ea7c2e8) | Feb 09, 2023 |
| HP            | 1494                        | Desktop     | [a582a0d6c7](https://linux-hardware.org/?probe=a582a0d6c7) | Feb 07, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [56e5f689ab](https://linux-hardware.org/?probe=56e5f689ab) | Feb 06, 2023 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | Desktop     | [280dd65788](https://linux-hardware.org/?probe=280dd65788) | Feb 04, 2023 |
| Supermicro    | X8DTL                       | Server      | [a3be5cdf41](https://linux-hardware.org/?probe=a3be5cdf41) | Feb 04, 2023 |
| Supermicro    | X9DBL-3F/X9DBL-iF           | Desktop     | [8f0808edd3](https://linux-hardware.org/?probe=8f0808edd3) | Feb 04, 2023 |
| MSI           | 870-G45                     | Desktop     | [92b840c75e](https://linux-hardware.org/?probe=92b840c75e) | Feb 04, 2023 |
| MSI           | 870-G45                     | Desktop     | [cda1aade14](https://linux-hardware.org/?probe=cda1aade14) | Jan 31, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [830394a75e](https://linux-hardware.org/?probe=830394a75e) | Jan 29, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [684748c9b4](https://linux-hardware.org/?probe=684748c9b4) | Jan 28, 2023 |
| PCChips       | P49G                        | Desktop     | [24a7d0e02b](https://linux-hardware.org/?probe=24a7d0e02b) | Jan 24, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [a67a4d078f](https://linux-hardware.org/?probe=a67a4d078f) | Jan 21, 2023 |
| ASUSTek       | N751JK                      | Notebook    | [259556fd6f](https://linux-hardware.org/?probe=259556fd6f) | Jan 11, 2023 |
| Inspur        | NF5280M6 YZMB-01642-101     | Server      | [22275687f9](https://linux-hardware.org/?probe=22275687f9) | Jan 10, 2023 |
| Lenovo        | ThinkPad T430 2349JN0       | Notebook    | [fceb17b32c](https://linux-hardware.org/?probe=fceb17b32c) | Jan 10, 2023 |
| Lenovo        | ThinkPad T430 2349JN0       | Notebook    | [04a54f4c2f](https://linux-hardware.org/?probe=04a54f4c2f) | Jan 09, 2023 |
| MSI           | H510M PRO-E                 | Desktop     | [762142dfbb](https://linux-hardware.org/?probe=762142dfbb) | Jan 06, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [b9522e3683](https://linux-hardware.org/?probe=b9522e3683) | Jan 02, 2023 |
| Lenovo        | ThinkPad T430 2347DE9       | Notebook    | [7b4305ce5a](https://linux-hardware.org/?probe=7b4305ce5a) | Dec 27, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [b95d3d3c7a](https://linux-hardware.org/?probe=b95d3d3c7a) | Dec 25, 2022 |
| Lenovo        | ThinkPad T430 2347DE9       | Notebook    | [afc91c5da0](https://linux-hardware.org/?probe=afc91c5da0) | Dec 24, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [117f4c04d6](https://linux-hardware.org/?probe=117f4c04d6) | Dec 21, 2022 |
| HP            | ProLiant DL360 G7           | Server      | [37905125fc](https://linux-hardware.org/?probe=37905125fc) | Dec 21, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [1b0b5a798f](https://linux-hardware.org/?probe=1b0b5a798f) | Dec 20, 2022 |
| LG Electro... | 15UD480-GX50K               | Notebook    | [16be4a033d](https://linux-hardware.org/?probe=16be4a033d) | Dec 19, 2022 |
| Lenovo        | ThinkPad X260 20F6007KKR    | Notebook    | [9b788f857e](https://linux-hardware.org/?probe=9b788f857e) | Dec 14, 2022 |
| Dell          | Precision 7720              | Notebook    | [5e8014cc1b](https://linux-hardware.org/?probe=5e8014cc1b) | Dec 08, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [164a07eda1](https://linux-hardware.org/?probe=164a07eda1) | Dec 08, 2022 |
| Dell          | 0NKW6Y A02                  | Desktop     | [f20d5b9289](https://linux-hardware.org/?probe=f20d5b9289) | Dec 07, 2022 |
| HONOR         | BBR-WAX9                    | Notebook    | [d7d701ca15](https://linux-hardware.org/?probe=d7d701ca15) | Dec 06, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [b2aac5194c](https://linux-hardware.org/?probe=b2aac5194c) | Dec 06, 2022 |
| Gigabyte      | D525TUD                     | Desktop     | [cfddc4ddef](https://linux-hardware.org/?probe=cfddc4ddef) | Dec 06, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [6ca3196f35](https://linux-hardware.org/?probe=6ca3196f35) | Dec 05, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [b6cf92da13](https://linux-hardware.org/?probe=b6cf92da13) | Dec 02, 2022 |
| ABIT          | I-45CV                      | Desktop     | [54b95d7794](https://linux-hardware.org/?probe=54b95d7794) | Dec 02, 2022 |
| Panasonic     | CF-19ADNAXDY                | Notebook    | [51120805b1](https://linux-hardware.org/?probe=51120805b1) | Dec 02, 2022 |
| Panasonic     | CF-19ADNAXDY                | Notebook    | [7a809e9dbd](https://linux-hardware.org/?probe=7a809e9dbd) | Dec 02, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [efecce0072](https://linux-hardware.org/?probe=efecce0072) | Nov 30, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [558174d9f4](https://linux-hardware.org/?probe=558174d9f4) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [b79b60e4b3](https://linux-hardware.org/?probe=b79b60e4b3) | Nov 28, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0149d91a8d](https://linux-hardware.org/?probe=0149d91a8d) | Nov 28, 2022 |
| Gigabyte      | 970A-D3                     | Desktop     | [89287418e8](https://linux-hardware.org/?probe=89287418e8) | Nov 23, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [74e3fe80fd](https://linux-hardware.org/?probe=74e3fe80fd) | Nov 23, 2022 |
| Lenovo        | 7X08CTO1WW                  | Server      | [bafb634a37](https://linux-hardware.org/?probe=bafb634a37) | Nov 23, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [efd2a439bd](https://linux-hardware.org/?probe=efd2a439bd) | Nov 21, 2022 |
| Dell          | 09D2HH A00                  | Desktop     | [4cafe39785](https://linux-hardware.org/?probe=4cafe39785) | Nov 19, 2022 |
| MSI           | 870-G45                     | Desktop     | [5d5dabd8ac](https://linux-hardware.org/?probe=5d5dabd8ac) | Nov 16, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [fd017849be](https://linux-hardware.org/?probe=fd017849be) | Nov 13, 2022 |
| HP            | 8717                        | Desktop     | [57479419c9](https://linux-hardware.org/?probe=57479419c9) | Nov 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e840ded8c0](https://linux-hardware.org/?probe=e840ded8c0) | Nov 09, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [b981adc21a](https://linux-hardware.org/?probe=b981adc21a) | Nov 07, 2022 |
| HPE           | ProLiant MicroServer Gen... | Server      | [dd2877fcc2](https://linux-hardware.org/?probe=dd2877fcc2) | Nov 05, 2022 |
| HPE           | ProLiant MicroServer Gen... | Server      | [d95735860b](https://linux-hardware.org/?probe=d95735860b) | Nov 05, 2022 |
| Dell          | Latitude E6230              | Notebook    | [da1e32759d](https://linux-hardware.org/?probe=da1e32759d) | Nov 05, 2022 |
| HP            | 3397                        | Desktop     | [9cb876048a](https://linux-hardware.org/?probe=9cb876048a) | Nov 05, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [8ee7171b61](https://linux-hardware.org/?probe=8ee7171b61) | Nov 03, 2022 |
| MSI           | 870-G45                     | Desktop     | [671a906cbb](https://linux-hardware.org/?probe=671a906cbb) | Nov 03, 2022 |
| HP            | 8717                        | Desktop     | [00cbc9cd2a](https://linux-hardware.org/?probe=00cbc9cd2a) | Nov 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [1b29e58b30](https://linux-hardware.org/?probe=1b29e58b30) | Oct 29, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [acdf2a172f](https://linux-hardware.org/?probe=acdf2a172f) | Oct 28, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [9598c40129](https://linux-hardware.org/?probe=9598c40129) | Oct 27, 2022 |
| Zvezda        | Arctur test_serv            | Server      | [0ace3642f0](https://linux-hardware.org/?probe=0ace3642f0) | Oct 21, 2022 |
| NORCO         | BPC-7951                    | Desktop     | [7612662684](https://linux-hardware.org/?probe=7612662684) | Oct 19, 2022 |
| Lenovo        | 7Z73CTO1WW                  | Server      | [ac182ad6f5](https://linux-hardware.org/?probe=ac182ad6f5) | Oct 18, 2022 |
| Lenovo        | 7X08CTO1WW                  | Server      | [16ab028232](https://linux-hardware.org/?probe=16ab028232) | Oct 18, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [8bd50f112b](https://linux-hardware.org/?probe=8bd50f112b) | Oct 15, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [88497baf29](https://linux-hardware.org/?probe=88497baf29) | Oct 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [f4ce3cf768](https://linux-hardware.org/?probe=f4ce3cf768) | Oct 13, 2022 |
| Intel         | D34010WYK H14771-303        | Desktop     | [e58d9849a5](https://linux-hardware.org/?probe=e58d9849a5) | Oct 06, 2022 |
| Dell          | 082WXT A03                  | Desktop     | [dc5e0c794d](https://linux-hardware.org/?probe=dc5e0c794d) | Oct 04, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [7e41cd4a30](https://linux-hardware.org/?probe=7e41cd4a30) | Oct 03, 2022 |
| ASUSTek       | PRIME B365-PLUS             | Desktop     | [9d811f43d3](https://linux-hardware.org/?probe=9d811f43d3) | Oct 03, 2022 |
| MSI           | 870-G45                     | Desktop     | [082307d0ce](https://linux-hardware.org/?probe=082307d0ce) | Sep 22, 2022 |
| Dell          | 0WCJNT A06                  | Server      | [4cc4b2f914](https://linux-hardware.org/?probe=4cc4b2f914) | Sep 22, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [2293724ae2](https://linux-hardware.org/?probe=2293724ae2) | Sep 19, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [09db514840](https://linux-hardware.org/?probe=09db514840) | Sep 19, 2022 |
| MSI           | 870-G45                     | Desktop     | [f360a57f01](https://linux-hardware.org/?probe=f360a57f01) | Sep 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [e61dc9628f](https://linux-hardware.org/?probe=e61dc9628f) | Sep 17, 2022 |
| Dell          | 03TJ75 A00                  | Desktop     | [70ef579566](https://linux-hardware.org/?probe=70ef579566) | Sep 15, 2022 |
| Intel         | S1200SP H57533-350          | Server      | [6e17cb41c9](https://linux-hardware.org/?probe=6e17cb41c9) | Sep 15, 2022 |
| ASUSTek       | Z87-A                       | Desktop     | [d57a581b09](https://linux-hardware.org/?probe=d57a581b09) | Sep 04, 2022 |
| IBM           | 00AM527                     | Server      | [f562c32fa7](https://linux-hardware.org/?probe=f562c32fa7) | Aug 31, 2022 |
| IBM           | 00AM527                     | Server      | [847f75ac19](https://linux-hardware.org/?probe=847f75ac19) | Aug 31, 2022 |
| Lenovo        | ThinkPad T430 2349DG5       | Notebook    | [740898521d](https://linux-hardware.org/?probe=740898521d) | Aug 27, 2022 |
| Dell          | 0F5C5X A00                  | Desktop     | [80cfa18cfd](https://linux-hardware.org/?probe=80cfa18cfd) | Aug 24, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [738a69419b](https://linux-hardware.org/?probe=738a69419b) | Aug 24, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [c97eb83b9c](https://linux-hardware.org/?probe=c97eb83b9c) | Aug 16, 2022 |
| Lenovo        | 7X06CTO1WW                  | Server      | [1de43750ce](https://linux-hardware.org/?probe=1de43750ce) | Aug 16, 2022 |
| AZW           | SER V01                     | Mini pc     | [873aac6635](https://linux-hardware.org/?probe=873aac6635) | Aug 11, 2022 |
| Timi          | Mi NoteBook Horizon Edit... | Notebook    | [52a0cb298b](https://linux-hardware.org/?probe=52a0cb298b) | Aug 09, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [e115d77240](https://linux-hardware.org/?probe=e115d77240) | Aug 07, 2022 |
| Lenovo        | G410 20237                  | Notebook    | [daea3239f0](https://linux-hardware.org/?probe=daea3239f0) | Aug 05, 2022 |
| ASRock        | X299 Professional Gaming... | Desktop     | [759afd2f9a](https://linux-hardware.org/?probe=759afd2f9a) | Aug 04, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [e9161d7c33](https://linux-hardware.org/?probe=e9161d7c33) | Jul 29, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [46201e4773](https://linux-hardware.org/?probe=46201e4773) | Jul 27, 2022 |
| Dell          | CS24-TY                     | Server      | [230ad2532f](https://linux-hardware.org/?probe=230ad2532f) | Jul 24, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [4eec45d964](https://linux-hardware.org/?probe=4eec45d964) | Jul 21, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [15e71f4f03](https://linux-hardware.org/?probe=15e71f4f03) | Jul 21, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [8bf06ee1c1](https://linux-hardware.org/?probe=8bf06ee1c1) | Jul 21, 2022 |
| NCR           | Pocono BIOS.6.0             | Desktop     | [ae030a0cda](https://linux-hardware.org/?probe=ae030a0cda) | Jul 15, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [0c08648c4d](https://linux-hardware.org/?probe=0c08648c4d) | Jul 15, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [4b7c20d75e](https://linux-hardware.org/?probe=4b7c20d75e) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [6069a015bb](https://linux-hardware.org/?probe=6069a015bb) | Jul 03, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [924537ba87](https://linux-hardware.org/?probe=924537ba87) | Jul 02, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [d5419be6e7](https://linux-hardware.org/?probe=d5419be6e7) | Jun 30, 2022 |
| Intel         | D410PT AAE76528-404         | Desktop     | [b7c62fc4a8](https://linux-hardware.org/?probe=b7c62fc4a8) | Jun 29, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c45dba9246](https://linux-hardware.org/?probe=c45dba9246) | Jun 26, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3d36beed4b](https://linux-hardware.org/?probe=3d36beed4b) | Jun 25, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f0d321b741](https://linux-hardware.org/?probe=f0d321b741) | Jun 22, 2022 |
| Dell          | 0WN7Y6 A02                  | Desktop     | [3e2f6e6e1c](https://linux-hardware.org/?probe=3e2f6e6e1c) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [88a7cd954c](https://linux-hardware.org/?probe=88a7cd954c) | Jun 19, 2022 |
| Unknown       | G41 Series                  | Desktop     | [d257436f52](https://linux-hardware.org/?probe=d257436f52) | Jun 17, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [139ffc0039](https://linux-hardware.org/?probe=139ffc0039) | Jun 16, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [16e086c77f](https://linux-hardware.org/?probe=16e086c77f) | Jun 16, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f339cce523](https://linux-hardware.org/?probe=f339cce523) | Jun 16, 2022 |
| HP            | 8711                        | Mini pc     | [6ceafddb10](https://linux-hardware.org/?probe=6ceafddb10) | Jun 13, 2022 |
| Dell          | G3 3500                     | Notebook    | [3b770a574b](https://linux-hardware.org/?probe=3b770a574b) | Jun 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [29f2cd44d5](https://linux-hardware.org/?probe=29f2cd44d5) | Jun 11, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [27ac9bc8f9](https://linux-hardware.org/?probe=27ac9bc8f9) | Jun 07, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [7fdce576b4](https://linux-hardware.org/?probe=7fdce576b4) | Jun 07, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [4655b6a8ed](https://linux-hardware.org/?probe=4655b6a8ed) | Jun 07, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [a989dee1a0](https://linux-hardware.org/?probe=a989dee1a0) | Jun 06, 2022 |
| HP            | 3397                        | Desktop     | [f2e8417afc](https://linux-hardware.org/?probe=f2e8417afc) | Jun 04, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [0353933c85](https://linux-hardware.org/?probe=0353933c85) | Jun 02, 2022 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [c70d152830](https://linux-hardware.org/?probe=c70d152830) | May 29, 2022 |
| HP            | 1998                        | Desktop     | [d68e99102e](https://linux-hardware.org/?probe=d68e99102e) | May 29, 2022 |
| Unknown       | G41 Series                  | Desktop     | [e9a273726a](https://linux-hardware.org/?probe=e9a273726a) | May 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [8120719b26](https://linux-hardware.org/?probe=8120719b26) | May 26, 2022 |
| Unknown       | G41 Series                  | Desktop     | [f0890bb556](https://linux-hardware.org/?probe=f0890bb556) | May 24, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [81360dffcc](https://linux-hardware.org/?probe=81360dffcc) | May 21, 2022 |
| Unknown       | G41 Series                  | Desktop     | [94dcbec5e7](https://linux-hardware.org/?probe=94dcbec5e7) | May 20, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [9a331b90a5](https://linux-hardware.org/?probe=9a331b90a5) | May 19, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [eb3f9d541e](https://linux-hardware.org/?probe=eb3f9d541e) | May 17, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [4c3a3b2de2](https://linux-hardware.org/?probe=4c3a3b2de2) | May 17, 2022 |
| Dell          | 0R4CNN A01                  | Server      | [b12db2e5d7](https://linux-hardware.org/?probe=b12db2e5d7) | May 16, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [7cbd29cc48](https://linux-hardware.org/?probe=7cbd29cc48) | May 15, 2022 |
| MSI           | Katana GF76 12UE            | Notebook    | [460e78b93a](https://linux-hardware.org/?probe=460e78b93a) | May 15, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [a7fb96d9aa](https://linux-hardware.org/?probe=a7fb96d9aa) | May 13, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [5de8d1f805](https://linux-hardware.org/?probe=5de8d1f805) | May 11, 2022 |
| Dell          | Vostro 5581                 | Notebook    | [cdcb310766](https://linux-hardware.org/?probe=cdcb310766) | Apr 30, 2022 |
| Dell          | 0K068D A00                  | Desktop     | [a73170db03](https://linux-hardware.org/?probe=a73170db03) | Apr 30, 2022 |
| Lenovo        | ThinkPad T61 64665WG        | Notebook    | [ac1bec6053](https://linux-hardware.org/?probe=ac1bec6053) | Apr 26, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | Notebook    | [228ec1a5f7](https://linux-hardware.org/?probe=228ec1a5f7) | Apr 24, 2022 |
| Unknown       | G41 Series                  | Desktop     | [c6040e6638](https://linux-hardware.org/?probe=c6040e6638) | Apr 21, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [db53151112](https://linux-hardware.org/?probe=db53151112) | Apr 19, 2022 |
| HP            | ProLiant DL380 G7           | Server      | [8f3e545e28](https://linux-hardware.org/?probe=8f3e545e28) | Apr 13, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [5b5118db5d](https://linux-hardware.org/?probe=5b5118db5d) | Apr 06, 2022 |
| Lenovo        | ThinkPad X61s 7667DB2       | Notebook    | [34ae68d221](https://linux-hardware.org/?probe=34ae68d221) | Apr 05, 2022 |
| Dell          | 0Y2YM6 A01                  | Desktop     | [4578be5a1e](https://linux-hardware.org/?probe=4578be5a1e) | Mar 30, 2022 |
| Unknown       | G41 Series                  | Desktop     | [4dbde5e06f](https://linux-hardware.org/?probe=4dbde5e06f) | Mar 28, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [309ea240bd](https://linux-hardware.org/?probe=309ea240bd) | Mar 25, 2022 |
| HP            | 0AECh D                     | Desktop     | [2fa93f9b4e](https://linux-hardware.org/?probe=2fa93f9b4e) | Mar 22, 2022 |
| MiTAC         | UltraPoint                  | Desktop     | [5199d92feb](https://linux-hardware.org/?probe=5199d92feb) | Mar 21, 2022 |
| Timi          | RedmiBook 16                | Notebook    | [bef46c5065](https://linux-hardware.org/?probe=bef46c5065) | Mar 20, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [beda807e51](https://linux-hardware.org/?probe=beda807e51) | Mar 20, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [1f84b1e42d](https://linux-hardware.org/?probe=1f84b1e42d) | Mar 11, 2022 |
| HP            | 0A9Ch                       | Desktop     | [0403520776](https://linux-hardware.org/?probe=0403520776) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [6d961af923](https://linux-hardware.org/?probe=6d961af923) | Mar 03, 2022 |
| Dell          | Latitude 5591               | Notebook    | [0bc1368ac5](https://linux-hardware.org/?probe=0bc1368ac5) | Feb 28, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [27513a5e2d](https://linux-hardware.org/?probe=27513a5e2d) | Feb 28, 2022 |
| Intel         | X99                         | Desktop     | [9cc44f0705](https://linux-hardware.org/?probe=9cc44f0705) | Feb 26, 2022 |
| Intel         | S1200SP H57533-210          | Server      | [7c1fa00b21](https://linux-hardware.org/?probe=7c1fa00b21) | Feb 23, 2022 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [cea504b47d](https://linux-hardware.org/?probe=cea504b47d) | Feb 16, 2022 |
| ASUSTek       | PN40                        | Mini pc     | [27bb88805d](https://linux-hardware.org/?probe=27bb88805d) | Feb 10, 2022 |
| ASUSTek       | PN40                        | Mini pc     | [6f558be780](https://linux-hardware.org/?probe=6f558be780) | Feb 10, 2022 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [746ddfc621](https://linux-hardware.org/?probe=746ddfc621) | Feb 09, 2022 |
| Lenovo        | ThinkPad T460s 20FAS5WX0... | Notebook    | [6fa180d5fa](https://linux-hardware.org/?probe=6fa180d5fa) | Feb 06, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [cf90d5430c](https://linux-hardware.org/?probe=cf90d5430c) | Feb 04, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5690460ebd](https://linux-hardware.org/?probe=5690460ebd) | Jan 31, 2022 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [294d18eb2b](https://linux-hardware.org/?probe=294d18eb2b) | Jan 30, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f76e2b6c0f](https://linux-hardware.org/?probe=f76e2b6c0f) | Jan 28, 2022 |
| ASUSTek       | F1A55-M LX PLUS             | Desktop     | [706b5f2fab](https://linux-hardware.org/?probe=706b5f2fab) | Jan 27, 2022 |
| Unknown       | G41 Series                  | Desktop     | [28502ce22e](https://linux-hardware.org/?probe=28502ce22e) | Jan 27, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [6db6689862](https://linux-hardware.org/?probe=6db6689862) | Jan 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [dfe95d1e0a](https://linux-hardware.org/?probe=dfe95d1e0a) | Jan 24, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c7f152495b](https://linux-hardware.org/?probe=c7f152495b) | Jan 21, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [6d015ef040](https://linux-hardware.org/?probe=6d015ef040) | Jan 15, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [010543afde](https://linux-hardware.org/?probe=010543afde) | Jan 13, 2022 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [a355e13859](https://linux-hardware.org/?probe=a355e13859) | Jan 11, 2022 |
| Supermicro    | H11DSi                      | Server      | [2bb4102b1c](https://linux-hardware.org/?probe=2bb4102b1c) | Jan 11, 2022 |
| ASUSTek       | V-P7H55E                    | Desktop     | [7fc2d44a4a](https://linux-hardware.org/?probe=7fc2d44a4a) | Jan 11, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a993fafbf7](https://linux-hardware.org/?probe=a993fafbf7) | Jan 08, 2022 |
| MSI           | Z270 GAMING PLUS            | Desktop     | [bd96b37321](https://linux-hardware.org/?probe=bd96b37321) | Jan 07, 2022 |
| HP            | 3397                        | Desktop     | [3bd3d85718](https://linux-hardware.org/?probe=3bd3d85718) | Jan 03, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [e6e4d232a9](https://linux-hardware.org/?probe=e6e4d232a9) | Jan 02, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [cbb5305dc7](https://linux-hardware.org/?probe=cbb5305dc7) | Dec 30, 2021 |
| MSI           | GP75 Leopard 10SFK          | Notebook    | [f165698d96](https://linux-hardware.org/?probe=f165698d96) | Dec 29, 2021 |
| Quanta        | QSSC-98J_C2 31S98MB0040     | Server      | [23e536f087](https://linux-hardware.org/?probe=23e536f087) | Dec 28, 2021 |
| Quanta        | QSSC-98J_C2 31S98MB0040     | Server      | [1f4a9c160f](https://linux-hardware.org/?probe=1f4a9c160f) | Dec 28, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [a810f7c0fb](https://linux-hardware.org/?probe=a810f7c0fb) | Dec 28, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [195bb81f89](https://linux-hardware.org/?probe=195bb81f89) | Dec 28, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [149083ba5f](https://linux-hardware.org/?probe=149083ba5f) | Dec 28, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d14a949e3d](https://linux-hardware.org/?probe=d14a949e3d) | Dec 27, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [3af644f11a](https://linux-hardware.org/?probe=3af644f11a) | Dec 26, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [aad21a9d66](https://linux-hardware.org/?probe=aad21a9d66) | Dec 21, 2021 |
| Lenovo        | 7Z71CTO1WW                  | Server      | [ff6113b91d](https://linux-hardware.org/?probe=ff6113b91d) | Dec 17, 2021 |
| Supermicro    | X10SDV-6C-TLN4F             | Desktop     | [07aa1e6365](https://linux-hardware.org/?probe=07aa1e6365) | Dec 17, 2021 |
| ASUSTek       | Pro Q570M-C                 | Desktop     | [d868c52b5a](https://linux-hardware.org/?probe=d868c52b5a) | Dec 15, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [fe889c0a84](https://linux-hardware.org/?probe=fe889c0a84) | Dec 15, 2021 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [0ca333f8b0](https://linux-hardware.org/?probe=0ca333f8b0) | Dec 15, 2021 |
| Supermicro    | X10DRH-iT                   | Server      | [50aebe4b28](https://linux-hardware.org/?probe=50aebe4b28) | Dec 14, 2021 |
| Supermicro    | H11DSi                      | Server      | [6b27a3eae9](https://linux-hardware.org/?probe=6b27a3eae9) | Dec 12, 2021 |
| Unknown       | G41 Series                  | Desktop     | [45a2524e2b](https://linux-hardware.org/?probe=45a2524e2b) | Dec 11, 2021 |
| Dell          | Inspiron 5406 2n1           | Convertible | [be9daabc79](https://linux-hardware.org/?probe=be9daabc79) | Dec 10, 2021 |
| Unknown       | G41 Series                  | Desktop     | [77c738bc15](https://linux-hardware.org/?probe=77c738bc15) | Dec 09, 2021 |
| Unknown       | G41 Series                  | Desktop     | [e9846d4aa5](https://linux-hardware.org/?probe=e9846d4aa5) | Dec 05, 2021 |
| Dell          | Vostro 14 5410              | Notebook    | [ef6f4cf593](https://linux-hardware.org/?probe=ef6f4cf593) | Dec 05, 2021 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [646eb8cd7d](https://linux-hardware.org/?probe=646eb8cd7d) | Dec 04, 2021 |
| Supermicro    | H11DSi                      | Server      | [3d2db8f378](https://linux-hardware.org/?probe=3d2db8f378) | Dec 01, 2021 |
| Dell          | Vostro 14 5410              | Notebook    | [6ab102bc84](https://linux-hardware.org/?probe=6ab102bc84) | Nov 30, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [e5e357405c](https://linux-hardware.org/?probe=e5e357405c) | Nov 29, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [cdc7bbd885](https://linux-hardware.org/?probe=cdc7bbd885) | Nov 29, 2021 |
| ASUSTek       | P5QL PRO                    | Desktop     | [ad0c0d07cf](https://linux-hardware.org/?probe=ad0c0d07cf) | Nov 28, 2021 |
| Dell          | Latitude E6430              | Notebook    | [a7435eb4c7](https://linux-hardware.org/?probe=a7435eb4c7) | Nov 28, 2021 |
| Aquarius      | Catfish AQC624CF            | Server      | [168c1506b2](https://linux-hardware.org/?probe=168c1506b2) | Nov 25, 2021 |
| HP            | 8717                        | Desktop     | [a00d17d8c4](https://linux-hardware.org/?probe=a00d17d8c4) | Nov 25, 2021 |
| Dell          | 02K9CR A01                  | Desktop     | [36c6a137fb](https://linux-hardware.org/?probe=36c6a137fb) | Nov 23, 2021 |
| Dell          | Latitude 5590               | Notebook    | [d8b69c36bd](https://linux-hardware.org/?probe=d8b69c36bd) | Nov 23, 2021 |
| Gigabyte      | B360HD3                     | Desktop     | [71a92047fb](https://linux-hardware.org/?probe=71a92047fb) | Nov 23, 2021 |
| Dell          | 0C2KJT A00                  | Desktop     | [b4fb255866](https://linux-hardware.org/?probe=b4fb255866) | Nov 23, 2021 |
| Lenovo        | ThinkPad E15 20RD0066TX     | Notebook    | [7443e6aedb](https://linux-hardware.org/?probe=7443e6aedb) | Nov 21, 2021 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [c40447abe8](https://linux-hardware.org/?probe=c40447abe8) | Nov 20, 2021 |
| Samsung       | 950QDB                      | Convertible | [2b35cd5e57](https://linux-hardware.org/?probe=2b35cd5e57) | Nov 17, 2021 |
| Dell          | 02K9CR A01                  | Desktop     | [7d558b813e](https://linux-hardware.org/?probe=7d558b813e) | Nov 17, 2021 |
| ASUSTek       | N56VJ                       | Notebook    | [f39e92a1f3](https://linux-hardware.org/?probe=f39e92a1f3) | Nov 16, 2021 |
| MSI           | A88X-G43                    | Desktop     | [c546efdb47](https://linux-hardware.org/?probe=c546efdb47) | Nov 16, 2021 |
| MSI           | A88X-G43                    | Desktop     | [3cb4a9134c](https://linux-hardware.org/?probe=3cb4a9134c) | Nov 16, 2021 |
| Supermicro    | H11DSi                      | Server      | [f04297689f](https://linux-hardware.org/?probe=f04297689f) | Nov 16, 2021 |
| Dell          | 06WXJT A01                  | Server      | [fcc6d41c03](https://linux-hardware.org/?probe=fcc6d41c03) | Nov 12, 2021 |
| Acer          | Aspire 5740                 | Notebook    | [0c661cb2d6](https://linux-hardware.org/?probe=0c661cb2d6) | Nov 12, 2021 |
| Dell          | 04YP6J A02                  | Desktop     | [6c41e1551e](https://linux-hardware.org/?probe=6c41e1551e) | Nov 09, 2021 |
| Dell          | 04YP6J A02                  | Desktop     | [736e182a15](https://linux-hardware.org/?probe=736e182a15) | Nov 09, 2021 |
| HP            | 872C                        | Mini pc     | [36f1254c43](https://linux-hardware.org/?probe=36f1254c43) | Nov 08, 2021 |
| HP            | 872C                        | Mini pc     | [e4450bb253](https://linux-hardware.org/?probe=e4450bb253) | Nov 08, 2021 |
| Aquarius      | Catfish AQC624CF            | Server      | [2552b5bb72](https://linux-hardware.org/?probe=2552b5bb72) | Nov 08, 2021 |
| Dell          | 0R038D A00                  | Desktop     | [6b0833e390](https://linux-hardware.org/?probe=6b0833e390) | Nov 05, 2021 |
| Supermicro    | H11DSi                      | Server      | [5c21cdfe50](https://linux-hardware.org/?probe=5c21cdfe50) | Nov 03, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [97ece593e1](https://linux-hardware.org/?probe=97ece593e1) | Nov 01, 2021 |
| ASRock        | Z77 Extreme4                | Desktop     | [bf66e1d281](https://linux-hardware.org/?probe=bf66e1d281) | Oct 29, 2021 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [6fe6c2d416](https://linux-hardware.org/?probe=6fe6c2d416) | Oct 27, 2021 |
| eMachines     | EMCP73VT-PM                 | Desktop     | [22fd625209](https://linux-hardware.org/?probe=22fd625209) | Oct 26, 2021 |
| Lenovo        | ThinkPad T61 6457W35        | Notebook    | [87e69e1105](https://linux-hardware.org/?probe=87e69e1105) | Oct 26, 2021 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9a9b258736](https://linux-hardware.org/?probe=9a9b258736) | Oct 22, 2021 |
| ASRock        | Z77 Extreme4                | Desktop     | [862513b9f6](https://linux-hardware.org/?probe=862513b9f6) | Oct 21, 2021 |
| ASUSTek       | KGPE-D16                    | Desktop     | [b5d2358b76](https://linux-hardware.org/?probe=b5d2358b76) | Oct 21, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [044546d5fa](https://linux-hardware.org/?probe=044546d5fa) | Oct 19, 2021 |
| ASUSTek       | P5BV-M/RS100-E5             | Desktop     | [13134022df](https://linux-hardware.org/?probe=13134022df) | Oct 19, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [60e26c388c](https://linux-hardware.org/?probe=60e26c388c) | Oct 17, 2021 |
| ASRock        | Z77 Extreme4                | Desktop     | [53b29edc51](https://linux-hardware.org/?probe=53b29edc51) | Oct 14, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d0fb953c7e](https://linux-hardware.org/?probe=d0fb953c7e) | Oct 11, 2021 |
| Supermicro    | H11DSi                      | Server      | [fee94d715d](https://linux-hardware.org/?probe=fee94d715d) | Oct 10, 2021 |
| ASRock        | Z77 Extreme4                | Desktop     | [0d69ee2560](https://linux-hardware.org/?probe=0d69ee2560) | Oct 10, 2021 |
| Huanan        | X79                         | Desktop     | [3532bbed3d](https://linux-hardware.org/?probe=3532bbed3d) | Oct 08, 2021 |
| Huanan        | X79                         | Desktop     | [6638a35363](https://linux-hardware.org/?probe=6638a35363) | Oct 08, 2021 |
| Intel         | NUC5i3RYB H41000-504        | Mini pc     | [b979bff593](https://linux-hardware.org/?probe=b979bff593) | Oct 06, 2021 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9a4c250f63](https://linux-hardware.org/?probe=9a4c250f63) | Oct 06, 2021 |
| Dell          | Latitude E6430              | Notebook    | [3d605c2c36](https://linux-hardware.org/?probe=3d605c2c36) | Oct 05, 2021 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [ec92b38160](https://linux-hardware.org/?probe=ec92b38160) | Oct 05, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [2ff5df695f](https://linux-hardware.org/?probe=2ff5df695f) | Oct 05, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [f6ff6eebb3](https://linux-hardware.org/?probe=f6ff6eebb3) | Oct 04, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [21d49c2826](https://linux-hardware.org/?probe=21d49c2826) | Oct 04, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [cb940b924d](https://linux-hardware.org/?probe=cb940b924d) | Sep 30, 2021 |
| HP            | 0AACh                       | Desktop     | [37766217ae](https://linux-hardware.org/?probe=37766217ae) | Sep 30, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [1c1bca9399](https://linux-hardware.org/?probe=1c1bca9399) | Sep 28, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [a68000e142](https://linux-hardware.org/?probe=a68000e142) | Sep 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [7baf2629b9](https://linux-hardware.org/?probe=7baf2629b9) | Sep 26, 2021 |
| Dell          | Latitude E6530              | Notebook    | [41d65e59eb](https://linux-hardware.org/?probe=41d65e59eb) | Sep 26, 2021 |
| ASRock        | Z77 Extreme4                | Desktop     | [b603b360a4](https://linux-hardware.org/?probe=b603b360a4) | Sep 25, 2021 |
| Dell          | Latitude E5470              | Notebook    | [17d97e59de](https://linux-hardware.org/?probe=17d97e59de) | Sep 23, 2021 |
| Supermicro    | H11DSi                      | Server      | [c41338a3bf](https://linux-hardware.org/?probe=c41338a3bf) | Sep 23, 2021 |
| Dell          | 0FM586                      | Desktop     | [5ec44ec202](https://linux-hardware.org/?probe=5ec44ec202) | Sep 20, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [b04783b7e1](https://linux-hardware.org/?probe=b04783b7e1) | Sep 20, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [976ca14e35](https://linux-hardware.org/?probe=976ca14e35) | Sep 19, 2021 |
| ASRock        | Z77 Extreme4                | Desktop     | [36129a77bf](https://linux-hardware.org/?probe=36129a77bf) | Sep 18, 2021 |
| Dell          | 0F0XJ6 A11                  | Server      | [26944912d7](https://linux-hardware.org/?probe=26944912d7) | Sep 17, 2021 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [23324e6aed](https://linux-hardware.org/?probe=23324e6aed) | Sep 17, 2021 |
| Dell          | Latitude E5470              | Notebook    | [82aca1d7b4](https://linux-hardware.org/?probe=82aca1d7b4) | Sep 16, 2021 |
| Dell          | Latitude E5470              | Notebook    | [c898d2b210](https://linux-hardware.org/?probe=c898d2b210) | Sep 16, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [d7ee29aac3](https://linux-hardware.org/?probe=d7ee29aac3) | Sep 15, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [4720c56d37](https://linux-hardware.org/?probe=4720c56d37) | Sep 15, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [e4278d3243](https://linux-hardware.org/?probe=e4278d3243) | Sep 15, 2021 |
| Intel         | AST2600EVB                  | Server      | [aead99f55d](https://linux-hardware.org/?probe=aead99f55d) | Sep 14, 2021 |
| Sony          | SVT11215CGW                 | Notebook    | [0e12747ab1](https://linux-hardware.org/?probe=0e12747ab1) | Sep 12, 2021 |
| HP            | 8750                        | Desktop     | [b5bbf3502f](https://linux-hardware.org/?probe=b5bbf3502f) | Sep 08, 2021 |
| Intel         | EAGLESTREAM E63448-400      | Server      | [7c59811abb](https://linux-hardware.org/?probe=7c59811abb) | Sep 08, 2021 |
| Dell          | Latitude 3420               | Notebook    | [1c1ef48be6](https://linux-hardware.org/?probe=1c1ef48be6) | Sep 06, 2021 |
| ASRock        | Z77 Extreme4                | Desktop     | [5cda73f744](https://linux-hardware.org/?probe=5cda73f744) | Sep 05, 2021 |
| Dell          | Latitude E7450              | Notebook    | [090d2bd5c7](https://linux-hardware.org/?probe=090d2bd5c7) | Sep 05, 2021 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [e5f7233230](https://linux-hardware.org/?probe=e5f7233230) | Sep 04, 2021 |
| Dell          | Latitude E7450              | Notebook    | [c2d943414c](https://linux-hardware.org/?probe=c2d943414c) | Sep 04, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [5d701efa3e](https://linux-hardware.org/?probe=5d701efa3e) | Sep 03, 2021 |
| ASRock        | Z77 Extreme4                | Desktop     | [f754b0f478](https://linux-hardware.org/?probe=f754b0f478) | Sep 03, 2021 |
| ASUSTek       | P5L8L-SE                    | Desktop     | [32e39bbd4f](https://linux-hardware.org/?probe=32e39bbd4f) | Sep 02, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [fd6f5273e3](https://linux-hardware.org/?probe=fd6f5273e3) | Sep 02, 2021 |
| HP            | EliteBook 2740p             | Notebook    | [0beccde57d](https://linux-hardware.org/?probe=0beccde57d) | Sep 01, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [5ae94fc78a](https://linux-hardware.org/?probe=5ae94fc78a) | Aug 28, 2021 |
| Supermicro    | X10DRL-CT                   | Server      | [cc00646768](https://linux-hardware.org/?probe=cc00646768) | Aug 28, 2021 |
| Supermicro    | X8SAX                       | Desktop     | [3795e4ab95](https://linux-hardware.org/?probe=3795e4ab95) | Aug 28, 2021 |
| Supermicro    | X10DRL-CT                   | Server      | [15df3c0fff](https://linux-hardware.org/?probe=15df3c0fff) | Aug 28, 2021 |
| Gigabyte      | B85M-D3PH                   | Desktop     | [01d87985dd](https://linux-hardware.org/?probe=01d87985dd) | Aug 28, 2021 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [bee6b88bab](https://linux-hardware.org/?probe=bee6b88bab) | Aug 27, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [9f3d5555ce](https://linux-hardware.org/?probe=9f3d5555ce) | Aug 26, 2021 |
| HP            | 8751                        | Desktop     | [cdaf5a0ed8](https://linux-hardware.org/?probe=cdaf5a0ed8) | Aug 24, 2021 |
| Lenovo        | 7X06CTO1WW                  | Server      | [928ee22e71](https://linux-hardware.org/?probe=928ee22e71) | Aug 24, 2021 |
| Dell          | 0F0XJ6 A11                  | Server      | [5e08b5eafd](https://linux-hardware.org/?probe=5e08b5eafd) | Aug 22, 2021 |
| HP            | NOTEBOOKE 15-AY084TU        | Notebook    | [fe06a5029a](https://linux-hardware.org/?probe=fe06a5029a) | Aug 22, 2021 |
| Supermicro    | X11SSH-F                    | Server      | [35fff898d1](https://linux-hardware.org/?probe=35fff898d1) | Aug 20, 2021 |
| HP            | EliteBook 8540w             | Notebook    | [6e6d5c8f2c](https://linux-hardware.org/?probe=6e6d5c8f2c) | Aug 20, 2021 |
| HP            | Presario C700               | Notebook    | [fa731abf46](https://linux-hardware.org/?probe=fa731abf46) | Aug 19, 2021 |
| Gigabyte      | Z170MX-Gaming 5             | Desktop     | [461d550db6](https://linux-hardware.org/?probe=461d550db6) | Aug 19, 2021 |
| Lenovo        | ThinkPad P50 20EN001PUS     | Notebook    | [38843da0aa](https://linux-hardware.org/?probe=38843da0aa) | Aug 18, 2021 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [70be38d5e1](https://linux-hardware.org/?probe=70be38d5e1) | Aug 18, 2021 |
| HP            | 2B3C                        | Desktop     | [5e60efc4a4](https://linux-hardware.org/?probe=5e60efc4a4) | Aug 18, 2021 |
| Lenovo        | ThinkPad P50 20EN001PUS     | Notebook    | [322b1fb2ba](https://linux-hardware.org/?probe=322b1fb2ba) | Aug 18, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [cabe0be4fc](https://linux-hardware.org/?probe=cabe0be4fc) | Aug 17, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [3501d4479e](https://linux-hardware.org/?probe=3501d4479e) | Aug 17, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [cf348cec5f](https://linux-hardware.org/?probe=cf348cec5f) | Aug 16, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [4f9bb753aa](https://linux-hardware.org/?probe=4f9bb753aa) | Aug 16, 2021 |
| Dell          | Latitude 7420               | Notebook    | [67165b9d66](https://linux-hardware.org/?probe=67165b9d66) | Aug 12, 2021 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [0cecab8e81](https://linux-hardware.org/?probe=0cecab8e81) | Aug 11, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [d1e968eadd](https://linux-hardware.org/?probe=d1e968eadd) | Aug 11, 2021 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [92336b575c](https://linux-hardware.org/?probe=92336b575c) | Aug 10, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [1778263a70](https://linux-hardware.org/?probe=1778263a70) | Aug 08, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [e329149eb4](https://linux-hardware.org/?probe=e329149eb4) | Aug 06, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [8ddb489f03](https://linux-hardware.org/?probe=8ddb489f03) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [d19976dabe](https://linux-hardware.org/?probe=d19976dabe) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [d56fdac07b](https://linux-hardware.org/?probe=d56fdac07b) | Aug 05, 2021 |
| HP            | ProLiant DL360 G5           | Server      | [58c9a1d28b](https://linux-hardware.org/?probe=58c9a1d28b) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [3eb59a276c](https://linux-hardware.org/?probe=3eb59a276c) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [3d0db6b81f](https://linux-hardware.org/?probe=3d0db6b81f) | Aug 05, 2021 |
| Sun Micros... | S39                         | Server      | [e54a36a0c4](https://linux-hardware.org/?probe=e54a36a0c4) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [1fc2375e54](https://linux-hardware.org/?probe=1fc2375e54) | Aug 05, 2021 |
| Dell          | 0YNVJG A01                  | Desktop     | [7952948421](https://linux-hardware.org/?probe=7952948421) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [a653e9beb2](https://linux-hardware.org/?probe=a653e9beb2) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [9a5d8276bf](https://linux-hardware.org/?probe=9a5d8276bf) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [2165980dd3](https://linux-hardware.org/?probe=2165980dd3) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [4a2adade2a](https://linux-hardware.org/?probe=4a2adade2a) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [78c5e3532b](https://linux-hardware.org/?probe=78c5e3532b) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [10bdaec1ef](https://linux-hardware.org/?probe=10bdaec1ef) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [70fc6a65ef](https://linux-hardware.org/?probe=70fc6a65ef) | Aug 05, 2021 |
| Dell          | 00V62H A01                  | Desktop     | [80244f2809](https://linux-hardware.org/?probe=80244f2809) | Aug 05, 2021 |
| Sun Micros... | Sun Fire X2270 375-3602-... | Server      | [54eaa5139f](https://linux-hardware.org/?probe=54eaa5139f) | Aug 05, 2021 |
| HP            | 8591                        | Desktop     | [6794bdb00e](https://linux-hardware.org/?probe=6794bdb00e) | Aug 05, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [f209feb9c8](https://linux-hardware.org/?probe=f209feb9c8) | Aug 05, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [40b8d28af0](https://linux-hardware.org/?probe=40b8d28af0) | Aug 04, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [80cb2748cf](https://linux-hardware.org/?probe=80cb2748cf) | Aug 02, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [0e9e25f619](https://linux-hardware.org/?probe=0e9e25f619) | Aug 02, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [597de4e10b](https://linux-hardware.org/?probe=597de4e10b) | Aug 01, 2021 |
| HP            | 0AECh D                     | Desktop     | [be8dfa216f](https://linux-hardware.org/?probe=be8dfa216f) | Jul 31, 2021 |
| Gigabyte      | H57M-USB3                   | Desktop     | [642d577f96](https://linux-hardware.org/?probe=642d577f96) | Jul 24, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [59a63323ed](https://linux-hardware.org/?probe=59a63323ed) | Jul 23, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [1232705d62](https://linux-hardware.org/?probe=1232705d62) | Jul 22, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ec0e7ce341](https://linux-hardware.org/?probe=ec0e7ce341) | Jul 19, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [da8382cb33](https://linux-hardware.org/?probe=da8382cb33) | Jul 15, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [146ce74ec9](https://linux-hardware.org/?probe=146ce74ec9) | Jul 15, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [4ac62bb08e](https://linux-hardware.org/?probe=4ac62bb08e) | Jul 13, 2021 |
| Acer          | Nitro AN515-51              | Notebook    | [130fff31f2](https://linux-hardware.org/?probe=130fff31f2) | Jul 12, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [8cf37f7d3d](https://linux-hardware.org/?probe=8cf37f7d3d) | Jul 11, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [3ec82c9dc0](https://linux-hardware.org/?probe=3ec82c9dc0) | Jul 11, 2021 |
| HP            | 2B34                        | Desktop     | [0de82dabad](https://linux-hardware.org/?probe=0de82dabad) | Jul 10, 2021 |
| HP            | 0A9Ch                       | Desktop     | [e3159a6511](https://linux-hardware.org/?probe=e3159a6511) | Jul 07, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | Notebook    | [c0af3fd295](https://linux-hardware.org/?probe=c0af3fd295) | Jul 05, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [a3f3f1e1c0](https://linux-hardware.org/?probe=a3f3f1e1c0) | Jul 02, 2021 |
| COPELION I... | QX-350                      | Notebook    | [6fd40c02da](https://linux-hardware.org/?probe=6fd40c02da) | Jul 01, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [4993490f00](https://linux-hardware.org/?probe=4993490f00) | Jul 01, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [69346a0102](https://linux-hardware.org/?probe=69346a0102) | Jul 01, 2021 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [f4606d038d](https://linux-hardware.org/?probe=f4606d038d) | Jun 29, 2021 |
| ASUSTek       | X455LJ                      | Notebook    | [b8a939ca9c](https://linux-hardware.org/?probe=b8a939ca9c) | Jun 27, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | Notebook    | [32d294ba2a](https://linux-hardware.org/?probe=32d294ba2a) | Jun 23, 2021 |
| HP            | EliteBook 8740w             | Notebook    | [9b54339e9b](https://linux-hardware.org/?probe=9b54339e9b) | Jun 16, 2021 |
| HP            | EliteBook 8740w             | Notebook    | [9ad5884fca](https://linux-hardware.org/?probe=9ad5884fca) | Jun 16, 2021 |
| ASRock        | A320M-HD                    | Desktop     | [e09e4e329c](https://linux-hardware.org/?probe=e09e4e329c) | Jun 14, 2021 |
| HP            | 1494                        | Desktop     | [d34b022996](https://linux-hardware.org/?probe=d34b022996) | Jun 11, 2021 |
| COPELION I... | QX-350                      | Notebook    | [7672d01a80](https://linux-hardware.org/?probe=7672d01a80) | Jun 08, 2021 |
| COPELION I... | QX-350                      | Notebook    | [4181e36f84](https://linux-hardware.org/?probe=4181e36f84) | Jun 07, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [00ce09b473](https://linux-hardware.org/?probe=00ce09b473) | May 31, 2021 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [b9f5cb4e7c](https://linux-hardware.org/?probe=b9f5cb4e7c) | May 31, 2021 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [fa31d6f45c](https://linux-hardware.org/?probe=fa31d6f45c) | May 30, 2021 |
| Intel         | E98683-353                  | Desktop     | [2f0ae62282](https://linux-hardware.org/?probe=2f0ae62282) | May 29, 2021 |
| Dell          | Latitude E6530              | Notebook    | [eaf1c46fce](https://linux-hardware.org/?probe=eaf1c46fce) | May 29, 2021 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [5742c8e4e5](https://linux-hardware.org/?probe=5742c8e4e5) | May 28, 2021 |
| HP            | 872C                        | Mini pc     | [0e48c94f83](https://linux-hardware.org/?probe=0e48c94f83) | May 28, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94        | Desktop     | [de14f99534](https://linux-hardware.org/?probe=de14f99534) | May 24, 2021 |
| Apple         | Mac-7BA5B2D9E42DDD94        | Desktop     | [8ecaed3eb2](https://linux-hardware.org/?probe=8ecaed3eb2) | May 24, 2021 |
| HP            | 1589                        | Desktop     | [a4b0ebbee2](https://linux-hardware.org/?probe=a4b0ebbee2) | May 23, 2021 |
| Dell          | 0200DY A02                  | Desktop     | [340184fb36](https://linux-hardware.org/?probe=340184fb36) | May 23, 2021 |
| ASRock        | J3710M                      | Desktop     | [6f289497fc](https://linux-hardware.org/?probe=6f289497fc) | May 23, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [ef516b4f37](https://linux-hardware.org/?probe=ef516b4f37) | May 17, 2021 |
| HP            | 18E7                        | Desktop     | [3045530e64](https://linux-hardware.org/?probe=3045530e64) | May 17, 2021 |
| HP            | 8710                        | Mini pc     | [b2a212246b](https://linux-hardware.org/?probe=b2a212246b) | May 14, 2021 |
| HP            | 8594                        | Desktop     | [991250b6a8](https://linux-hardware.org/?probe=991250b6a8) | May 14, 2021 |
| HP            | 829A                        | Mini pc     | [c326081d7d](https://linux-hardware.org/?probe=c326081d7d) | May 14, 2021 |
| HP            | 1825                        | Desktop     | [13110a2081](https://linux-hardware.org/?probe=13110a2081) | May 14, 2021 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [ce71038513](https://linux-hardware.org/?probe=ce71038513) | May 14, 2021 |
| Lenovo        | ThinkPad E490 20N8007NTX    | Notebook    | [e9efa41cf8](https://linux-hardware.org/?probe=e9efa41cf8) | May 12, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [640c5adfc3](https://linux-hardware.org/?probe=640c5adfc3) | May 10, 2021 |
| ASUSTek       | U35JC                       | Notebook    | [29ea6520a1](https://linux-hardware.org/?probe=29ea6520a1) | May 08, 2021 |
| Lenovo        | ThinkPad X200 7459ZEJ       | Notebook    | [a4f7ad5736](https://linux-hardware.org/?probe=a4f7ad5736) | May 07, 2021 |
| HP            | ZBook 15 G6                 | Notebook    | [ea363ea07e](https://linux-hardware.org/?probe=ea363ea07e) | May 07, 2021 |
| HP            | 8710                        | Mini pc     | [a9e3962fe5](https://linux-hardware.org/?probe=a9e3962fe5) | May 07, 2021 |
| HP            | 8710                        | Mini pc     | [a862c9d728](https://linux-hardware.org/?probe=a862c9d728) | May 07, 2021 |
| Lenovo        | 01DC328                     | Server      | [3510dd7b10](https://linux-hardware.org/?probe=3510dd7b10) | May 05, 2021 |
| Intel         | S3210SH FRU Ver             | Server      | [591107ec98](https://linux-hardware.org/?probe=591107ec98) | May 04, 2021 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [9eb409c988](https://linux-hardware.org/?probe=9eb409c988) | May 02, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [88b8ca6dbe](https://linux-hardware.org/?probe=88b8ca6dbe) | Apr 30, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [be1a846088](https://linux-hardware.org/?probe=be1a846088) | Apr 30, 2021 |
| HP            | 8591                        | Desktop     | [03b17d692d](https://linux-hardware.org/?probe=03b17d692d) | Apr 26, 2021 |
| Lenovo        | 01GR174                     | Server      | [63ec4551f5](https://linux-hardware.org/?probe=63ec4551f5) | Apr 26, 2021 |
| Lenovo        | 01GR174                     | Server      | [c68b7991a5](https://linux-hardware.org/?probe=c68b7991a5) | Apr 26, 2021 |
| HP            | 213D A01                    | Desktop     | [72e7e27309](https://linux-hardware.org/?probe=72e7e27309) | Apr 26, 2021 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [8524f8f381](https://linux-hardware.org/?probe=8524f8f381) | Apr 16, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [1133f762f5](https://linux-hardware.org/?probe=1133f762f5) | Apr 15, 2021 |
| Dell          | Precision 3551              | Notebook    | [4e9b5b097e](https://linux-hardware.org/?probe=4e9b5b097e) | Apr 15, 2021 |
| Lenovo        | ThinkPad W540 20BHS20700    | Notebook    | [30edeadde3](https://linux-hardware.org/?probe=30edeadde3) | Apr 13, 2021 |
| Lenovo        | ThinkPad T460p 20FXS0220... | Notebook    | [3aef8ed384](https://linux-hardware.org/?probe=3aef8ed384) | Apr 11, 2021 |
| Lenovo        | ThinkPad E15 20RD0066TX     | Notebook    | [c3c1d01480](https://linux-hardware.org/?probe=c3c1d01480) | Apr 09, 2021 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [523b31291c](https://linux-hardware.org/?probe=523b31291c) | Apr 06, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [d4b7cef21b](https://linux-hardware.org/?probe=d4b7cef21b) | Apr 06, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [c974cb6fc7](https://linux-hardware.org/?probe=c974cb6fc7) | Apr 06, 2021 |
| Hyve          | HS-9216Lite2 5411C405005... | Server      | [20edfbf60b](https://linux-hardware.org/?probe=20edfbf60b) | Apr 06, 2021 |
| Gigabyte      | EP43-DS3                    | Desktop     | [3eaab1a9d9](https://linux-hardware.org/?probe=3eaab1a9d9) | Apr 05, 2021 |
| Lenovo        | ThinkPad E15 20RD0066TX     | Notebook    | [3ab392c848](https://linux-hardware.org/?probe=3ab392c848) | Apr 05, 2021 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [4b9332ae3a](https://linux-hardware.org/?probe=4b9332ae3a) | Apr 05, 2021 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [d4a7fbec30](https://linux-hardware.org/?probe=d4a7fbec30) | Apr 01, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [46c15e3b14](https://linux-hardware.org/?probe=46c15e3b14) | Apr 01, 2021 |
| Dell          | 0MWYPT A02                  | Desktop     | [e2e2e6f179](https://linux-hardware.org/?probe=e2e2e6f179) | Mar 31, 2021 |
| Cisco Syst... | UCSB-B200-M4 73-15862-03    | Desktop     | [4c55de0b30](https://linux-hardware.org/?probe=4c55de0b30) | Mar 31, 2021 |
| Unknown       | Unknown                     | Desktop     | [b672c68361](https://linux-hardware.org/?probe=b672c68361) | Mar 30, 2021 |
| HP            | 8591                        | Desktop     | [3c4d055665](https://linux-hardware.org/?probe=3c4d055665) | Mar 30, 2021 |
| HP            | 8591                        | Desktop     | [b436577a94](https://linux-hardware.org/?probe=b436577a94) | Mar 30, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [f8b36f6373](https://linux-hardware.org/?probe=f8b36f6373) | Mar 29, 2021 |
| LG Electro... | Z435-GE40K                  | Notebook    | [41dfc50f20](https://linux-hardware.org/?probe=41dfc50f20) | Mar 27, 2021 |
| Gigabyte      | Z490 GAMING X               | Desktop     | [f37546f14b](https://linux-hardware.org/?probe=f37546f14b) | Mar 26, 2021 |
| Dell          | 0XHGV1 A00                  | Desktop     | [aa8337865d](https://linux-hardware.org/?probe=aa8337865d) | Mar 23, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [3bce30311a](https://linux-hardware.org/?probe=3bce30311a) | Mar 23, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [c724df2a1a](https://linux-hardware.org/?probe=c724df2a1a) | Mar 23, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [c46179b0b2](https://linux-hardware.org/?probe=c46179b0b2) | Mar 22, 2021 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [0473f156a3](https://linux-hardware.org/?probe=0473f156a3) | Mar 22, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ccdc5f822c](https://linux-hardware.org/?probe=ccdc5f822c) | Mar 20, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9fdca2136a](https://linux-hardware.org/?probe=9fdca2136a) | Mar 19, 2021 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [18368633c1](https://linux-hardware.org/?probe=18368633c1) | Mar 19, 2021 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [59681c51ea](https://linux-hardware.org/?probe=59681c51ea) | Mar 19, 2021 |
| MiTAC         | PD10BI PD10BI-702           | Desktop     | [63335e1b88](https://linux-hardware.org/?probe=63335e1b88) | Mar 18, 2021 |
| MiTAC         | PD10BI PD10BI-702           | Desktop     | [5d23375dcd](https://linux-hardware.org/?probe=5d23375dcd) | Mar 18, 2021 |
| Unknown       | Unknown                     | Desktop     | [234c991949](https://linux-hardware.org/?probe=234c991949) | Mar 17, 2021 |
| MSI           | H170A GAMING PRO            | Desktop     | [dd38d014bd](https://linux-hardware.org/?probe=dd38d014bd) | Mar 17, 2021 |
| Dell          | 0NC2VH A01                  | Desktop     | [cc8791aaa6](https://linux-hardware.org/?probe=cc8791aaa6) | Mar 17, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [72df2af331](https://linux-hardware.org/?probe=72df2af331) | Mar 16, 2021 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [096fcfddb5](https://linux-hardware.org/?probe=096fcfddb5) | Mar 14, 2021 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [adac87af3d](https://linux-hardware.org/?probe=adac87af3d) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | Desktop     | [0190551f1e](https://linux-hardware.org/?probe=0190551f1e) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | Desktop     | [1184f695c1](https://linux-hardware.org/?probe=1184f695c1) | Mar 13, 2021 |
| ASUSTek       | P8H77-I                     | Desktop     | [b5658ed87e](https://linux-hardware.org/?probe=b5658ed87e) | Mar 12, 2021 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [7a38c478bb](https://linux-hardware.org/?probe=7a38c478bb) | Mar 12, 2021 |
| HP            | 871C                        | All in one  | [2f7fd6200f](https://linux-hardware.org/?probe=2f7fd6200f) | Mar 10, 2021 |
| HP            | 871C                        | All in one  | [7cbfb86cef](https://linux-hardware.org/?probe=7cbfb86cef) | Mar 10, 2021 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [ba68c7c065](https://linux-hardware.org/?probe=ba68c7c065) | Mar 09, 2021 |
| Dell          | Latitude E7250              | Notebook    | [551399bf55](https://linux-hardware.org/?probe=551399bf55) | Mar 08, 2021 |
| HUAWEI        | BC82AMDDA V200R002C00       | Server      | [63bdabb5a4](https://linux-hardware.org/?probe=63bdabb5a4) | Feb 26, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [774a5efd77](https://linux-hardware.org/?probe=774a5efd77) | Feb 25, 2021 |
| AMI           | PCHK-Z83 Poslab_ECO         | Desktop     | [5dd25822e3](https://linux-hardware.org/?probe=5dd25822e3) | Feb 23, 2021 |
| HP            | 81C6 MVB 0C                 | Server      | [9d6e46eca9](https://linux-hardware.org/?probe=9d6e46eca9) | Feb 23, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1314989a9a](https://linux-hardware.org/?probe=1314989a9a) | Feb 21, 2021 |
| Dell          | 0WR7PY A01                  | Desktop     | [ad06439414](https://linux-hardware.org/?probe=ad06439414) | Feb 19, 2021 |
| Gigabyte      | D525TUD                     | Desktop     | [59b1050f5f](https://linux-hardware.org/?probe=59b1050f5f) | Feb 19, 2021 |
| HP            | ProBook 6560b               | Notebook    | [57004cab16](https://linux-hardware.org/?probe=57004cab16) | Feb 17, 2021 |
| Supermicro    | X9SCI/X9SCA                 | Desktop     | [28940aaa42](https://linux-hardware.org/?probe=28940aaa42) | Feb 16, 2021 |
| Dell          | 07T4MC A06                  | Desktop     | [ae053aa0ed](https://linux-hardware.org/?probe=ae053aa0ed) | Feb 15, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [fcc71c0314](https://linux-hardware.org/?probe=fcc71c0314) | Feb 13, 2021 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [0cf9401181](https://linux-hardware.org/?probe=0cf9401181) | Feb 12, 2021 |
| ASUSTek       | PRIME B360M-D               | Desktop     | [aab84fafeb](https://linux-hardware.org/?probe=aab84fafeb) | Feb 10, 2021 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [754ea78372](https://linux-hardware.org/?probe=754ea78372) | Feb 09, 2021 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [5e6e46d3b1](https://linux-hardware.org/?probe=5e6e46d3b1) | Feb 09, 2021 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [8469853bc1](https://linux-hardware.org/?probe=8469853bc1) | Feb 08, 2021 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [7b44703f86](https://linux-hardware.org/?probe=7b44703f86) | Feb 08, 2021 |
| Fujitsu       | D3488-A1 S26361-D3488-A1    | Server      | [86ab491564](https://linux-hardware.org/?probe=86ab491564) | Feb 08, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [9fc9b672d0](https://linux-hardware.org/?probe=9fc9b672d0) | Feb 07, 2021 |
| HP            | 3397                        | Desktop     | [aba05551cb](https://linux-hardware.org/?probe=aba05551cb) | Feb 05, 2021 |
| Lenovo        | 314D SDK0J40700 WIN 3258... | Mini pc     | [032db5db0f](https://linux-hardware.org/?probe=032db5db0f) | Feb 03, 2021 |
| Lenovo        | 314D SDK0J40700 WIN 3258... | Mini pc     | [91e6c3a3f5](https://linux-hardware.org/?probe=91e6c3a3f5) | Feb 03, 2021 |
| Intel         | S5000PAL0 FRU Ver           | Server      | [390f15b7f9](https://linux-hardware.org/?probe=390f15b7f9) | Feb 03, 2021 |
| HP            | 8755                        | Mini pc     | [334abf8c53](https://linux-hardware.org/?probe=334abf8c53) | Feb 02, 2021 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [b19f88f1bd](https://linux-hardware.org/?probe=b19f88f1bd) | Feb 02, 2021 |
| Dell          | 0T7971 A04                  | Server      | [08919c80e8](https://linux-hardware.org/?probe=08919c80e8) | Jan 28, 2021 |
| Acer          | Aspire V5-571G              | Notebook    | [6f498cb661](https://linux-hardware.org/?probe=6f498cb661) | Jan 27, 2021 |
| ASUSTek       | K54C                        | Notebook    | [ac91a40e03](https://linux-hardware.org/?probe=ac91a40e03) | Jan 24, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [59145ca9e6](https://linux-hardware.org/?probe=59145ca9e6) | Jan 24, 2021 |
| Lenovo        | ThinkPad T520 4243Y1N       | Notebook    | [66b47b2f1e](https://linux-hardware.org/?probe=66b47b2f1e) | Jan 20, 2021 |
| Sony          | VPCEG15FB                   | Notebook    | [badcac9c3d](https://linux-hardware.org/?probe=badcac9c3d) | Jan 17, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [71b67a3764](https://linux-hardware.org/?probe=71b67a3764) | Jan 14, 2021 |
| ASUSTek       | GD30CI                      | Desktop     | [201c54f6b8](https://linux-hardware.org/?probe=201c54f6b8) | Jan 12, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [d798d76c9a](https://linux-hardware.org/?probe=d798d76c9a) | Jan 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [6de78c3913](https://linux-hardware.org/?probe=6de78c3913) | Jan 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [e2cd4bfc82](https://linux-hardware.org/?probe=e2cd4bfc82) | Jan 11, 2021 |
| Dell          | 0HHV7N A00                  | Desktop     | [7b55587c5a](https://linux-hardware.org/?probe=7b55587c5a) | Jan 10, 2021 |
| MSI           | H97 GAMING 3                | Desktop     | [7e25d7549f](https://linux-hardware.org/?probe=7e25d7549f) | Jan 09, 2021 |
| ASUSTek       | GD30CI                      | Desktop     | [4f2d51ec4b](https://linux-hardware.org/?probe=4f2d51ec4b) | Jan 09, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [48d877b127](https://linux-hardware.org/?probe=48d877b127) | Jan 07, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [e105b05883](https://linux-hardware.org/?probe=e105b05883) | Jan 07, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [a448a76b2e](https://linux-hardware.org/?probe=a448a76b2e) | Jan 06, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [58204a920b](https://linux-hardware.org/?probe=58204a920b) | Jan 05, 2021 |
| HP            | 806A                        | Desktop     | [f02a4a5e93](https://linux-hardware.org/?probe=f02a4a5e93) | Jan 05, 2021 |
| Intel         | S1200RP_SE G62252-405       | Server      | [1eaaae85a8](https://linux-hardware.org/?probe=1eaaae85a8) | Jan 04, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [1ad69ae9c9](https://linux-hardware.org/?probe=1ad69ae9c9) | Jan 04, 2021 |
| Gigabyte      | D525TUD                     | Desktop     | [e9f1445d02](https://linux-hardware.org/?probe=e9f1445d02) | Jan 03, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [edbd95264a](https://linux-hardware.org/?probe=edbd95264a) | Jan 02, 2021 |
| Dell          | XPS L521X                   | Notebook    | [c109644955](https://linux-hardware.org/?probe=c109644955) | Dec 28, 2020 |
| Dell          | Latitude E7240              | Notebook    | [39e57b6b18](https://linux-hardware.org/?probe=39e57b6b18) | Dec 28, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [ac785c27e5](https://linux-hardware.org/?probe=ac785c27e5) | Dec 27, 2020 |
| Dell          | 0VD5HY A00                  | Desktop     | [470703f4af](https://linux-hardware.org/?probe=470703f4af) | Dec 27, 2020 |
| Intel         | DQ67OW AAG12528-309         | Desktop     | [5f42b365ae](https://linux-hardware.org/?probe=5f42b365ae) | Dec 26, 2020 |
| ASRock        | X570 Steel Legend           | Desktop     | [c96512d726](https://linux-hardware.org/?probe=c96512d726) | Dec 25, 2020 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [7038da6d94](https://linux-hardware.org/?probe=7038da6d94) | Dec 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [55e2883ca5](https://linux-hardware.org/?probe=55e2883ca5) | Dec 24, 2020 |
| Lenovo        | ThinkPad T460p 20FXS0220... | Notebook    | [048b297665](https://linux-hardware.org/?probe=048b297665) | Dec 23, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [2b7bb243da](https://linux-hardware.org/?probe=2b7bb243da) | Dec 23, 2020 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [46613a5ce9](https://linux-hardware.org/?probe=46613a5ce9) | Dec 20, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | Notebook    | [d87cdee8cb](https://linux-hardware.org/?probe=d87cdee8cb) | Dec 19, 2020 |
| ASUSTek       | PN50                        | Mini pc     | [c286ba7e5e](https://linux-hardware.org/?probe=c286ba7e5e) | Dec 18, 2020 |
| ASUSTek       | PN50                        | Mini pc     | [809fb60059](https://linux-hardware.org/?probe=809fb60059) | Dec 18, 2020 |
| Acer          | Aspire E1-572               | Notebook    | [a06266ed7f](https://linux-hardware.org/?probe=a06266ed7f) | Dec 17, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5f5a111ab2](https://linux-hardware.org/?probe=5f5a111ab2) | Dec 16, 2020 |
| ASUSTek       | X455LJ                      | Notebook    | [54683be664](https://linux-hardware.org/?probe=54683be664) | Dec 15, 2020 |
| Acer          | Aspire A715-75G             | Notebook    | [814f906095](https://linux-hardware.org/?probe=814f906095) | Dec 15, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [813cd07e38](https://linux-hardware.org/?probe=813cd07e38) | Dec 14, 2020 |
| Gigabyte      | Z370 AORUS Gaming WIFI-C... | Desktop     | [5438d83866](https://linux-hardware.org/?probe=5438d83866) | Dec 14, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [da43f75c0c](https://linux-hardware.org/?probe=da43f75c0c) | Dec 14, 2020 |
| Gigabyte      | Z77-D3H                     | Desktop     | [b7c033babd](https://linux-hardware.org/?probe=b7c033babd) | Dec 10, 2020 |
| ASUSTek       | X455LJ                      | Notebook    | [9938aa76cf](https://linux-hardware.org/?probe=9938aa76cf) | Dec 10, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | Notebook    | [9d12f4f222](https://linux-hardware.org/?probe=9d12f4f222) | Dec 10, 2020 |
| Lenovo        | ThinkPad T490s 20NYS0290... | Notebook    | [c26814bfc2](https://linux-hardware.org/?probe=c26814bfc2) | Dec 10, 2020 |
| Lenovo        | G70-70 80HW005XUK           | Notebook    | [a57125fe89](https://linux-hardware.org/?probe=a57125fe89) | Dec 07, 2020 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [4d423f3865](https://linux-hardware.org/?probe=4d423f3865) | Dec 07, 2020 |
| Dell          | 0W7H8C A05                  | Server      | [a4512466f1](https://linux-hardware.org/?probe=a4512466f1) | Dec 06, 2020 |
| Acer          | Aspire V5-431P              | Notebook    | [831f0df544](https://linux-hardware.org/?probe=831f0df544) | Dec 03, 2020 |
| Dell          | Studio 1747                 | Notebook    | [dd0085228f](https://linux-hardware.org/?probe=dd0085228f) | Nov 29, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [a37a75cdcb](https://linux-hardware.org/?probe=a37a75cdcb) | Nov 29, 2020 |
| HP            | ZBook 15                    | Notebook    | [033521235f](https://linux-hardware.org/?probe=033521235f) | Nov 29, 2020 |
| Lenovo        | ThinkPad E595 20NF0000GE    | Notebook    | [c58ad8f5e8](https://linux-hardware.org/?probe=c58ad8f5e8) | Nov 28, 2020 |
| Gigabyte      | D525TUD                     | Desktop     | [0c13d73ba0](https://linux-hardware.org/?probe=0c13d73ba0) | Nov 27, 2020 |
| BESSTAR Te... | AB1A                        | Mini pc     | [4b3cf9cdd0](https://linux-hardware.org/?probe=4b3cf9cdd0) | Nov 25, 2020 |
| ASUSTek       | Z170-A                      | Desktop     | [b4e9865791](https://linux-hardware.org/?probe=b4e9865791) | Nov 25, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [b2cc866da6](https://linux-hardware.org/?probe=b2cc866da6) | Nov 24, 2020 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [bc3bd4ea10](https://linux-hardware.org/?probe=bc3bd4ea10) | Nov 24, 2020 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [3d5c6b679d](https://linux-hardware.org/?probe=3d5c6b679d) | Nov 22, 2020 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [b3f3cd1511](https://linux-hardware.org/?probe=b3f3cd1511) | Nov 22, 2020 |
| Toshiba       | Satellite A135              | Notebook    | [310ddb721f](https://linux-hardware.org/?probe=310ddb721f) | Nov 20, 2020 |
| Lenovo        | ThinkPad X240 20AMS7XW00    | Notebook    | [b7783af763](https://linux-hardware.org/?probe=b7783af763) | Nov 19, 2020 |
| Sony          | VPCEH15FX                   | Notebook    | [cc8c7bc4c9](https://linux-hardware.org/?probe=cc8c7bc4c9) | Nov 19, 2020 |
| HP            | 81C9                        | Desktop     | [ea900ff5b1](https://linux-hardware.org/?probe=ea900ff5b1) | Nov 19, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [574e7cc90c](https://linux-hardware.org/?probe=574e7cc90c) | Nov 18, 2020 |
| Lenovo        | HASWELLREFRESHDT NO DPK     | All in one  | [778d8e5380](https://linux-hardware.org/?probe=778d8e5380) | Nov 18, 2020 |
| Acer          | Aspire V5-571G              | Notebook    | [b8d43abe6e](https://linux-hardware.org/?probe=b8d43abe6e) | Nov 18, 2020 |
| Lenovo        | ThinkPad X200 7459H92       | Notebook    | [242193b8bc](https://linux-hardware.org/?probe=242193b8bc) | Nov 17, 2020 |
| ASUSTek       | Z9PE-D8 WS                  | Server      | [026b32269e](https://linux-hardware.org/?probe=026b32269e) | Nov 17, 2020 |
| Rockwell A... | 6177R A1                    | Desktop     | [a12a2989fd](https://linux-hardware.org/?probe=a12a2989fd) | Nov 16, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [70fc4e5649](https://linux-hardware.org/?probe=70fc4e5649) | Nov 16, 2020 |
| HP            | 1587h                       | Desktop     | [4b1f2221ee](https://linux-hardware.org/?probe=4b1f2221ee) | Nov 16, 2020 |
| Acer          | Aspire V5-571G              | Notebook    | [49707be15c](https://linux-hardware.org/?probe=49707be15c) | Nov 16, 2020 |
| Dell          | Latitude 3440               | Notebook    | [17db1f31f6](https://linux-hardware.org/?probe=17db1f31f6) | Nov 13, 2020 |
| HP            | EliteBook 830 G6            | Notebook    | [0e0009bcfc](https://linux-hardware.org/?probe=0e0009bcfc) | Nov 13, 2020 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a5d5227154](https://linux-hardware.org/?probe=a5d5227154) | Nov 12, 2020 |
| CompuLab      | fit-PC3                     | Mini pc     | [2e92dc00d4](https://linux-hardware.org/?probe=2e92dc00d4) | Nov 12, 2020 |
| Lenovo        | ThinkPad T420 4238AB9       | Notebook    | [9c7ec388e0](https://linux-hardware.org/?probe=9c7ec388e0) | Nov 11, 2020 |
| ASUSTek       | X455LJ                      | Notebook    | [d0085b85ad](https://linux-hardware.org/?probe=d0085b85ad) | Nov 09, 2020 |
| HP            | 1495                        | Desktop     | [931bc038c8](https://linux-hardware.org/?probe=931bc038c8) | Nov 07, 2020 |
| HP            | 1495                        | Desktop     | [a2c50ab08e](https://linux-hardware.org/?probe=a2c50ab08e) | Nov 07, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [ed3c250112](https://linux-hardware.org/?probe=ed3c250112) | Nov 03, 2020 |
| Supermicro    | X8SIL                       | Desktop     | [10b7c06f49](https://linux-hardware.org/?probe=10b7c06f49) | Nov 02, 2020 |
| Supermicro    | X8SIL                       | Desktop     | [e40055e7ca](https://linux-hardware.org/?probe=e40055e7ca) | Nov 01, 2020 |
| ASRock        | G31M-S                      | Desktop     | [1741a29fd6](https://linux-hardware.org/?probe=1741a29fd6) | Nov 01, 2020 |
| ASRock        | G31M-S                      | Desktop     | [e579695cc9](https://linux-hardware.org/?probe=e579695cc9) | Nov 01, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [dbc5336b07](https://linux-hardware.org/?probe=dbc5336b07) | Nov 01, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [d69c97a2c3](https://linux-hardware.org/?probe=d69c97a2c3) | Oct 30, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [4e9d94747a](https://linux-hardware.org/?probe=4e9d94747a) | Oct 30, 2020 |
| Lenovo        | ThinkPad E590 20NBS03S00    | Notebook    | [29ae827508](https://linux-hardware.org/?probe=29ae827508) | Oct 29, 2020 |
| Supermicro    | X8SIL                       | Desktop     | [ff3a4a93df](https://linux-hardware.org/?probe=ff3a4a93df) | Oct 28, 2020 |
| Supermicro    | X8SIL                       | Desktop     | [c6d306f861](https://linux-hardware.org/?probe=c6d306f861) | Oct 27, 2020 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [56d1218104](https://linux-hardware.org/?probe=56d1218104) | Oct 25, 2020 |
| ASUSTek       | Z170-A                      | Desktop     | [e5b6274c3e](https://linux-hardware.org/?probe=e5b6274c3e) | Oct 22, 2020 |
| Dell          | Latitude E6440              | Notebook    | [46a2699a96](https://linux-hardware.org/?probe=46a2699a96) | Oct 21, 2020 |
| Unknown       | Unknown                     | Notebook    | [98cd8695de](https://linux-hardware.org/?probe=98cd8695de) | Oct 21, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [97a2b45d12](https://linux-hardware.org/?probe=97a2b45d12) | Oct 21, 2020 |
| Unknown       | Unknown                     | Notebook    | [a0e3328769](https://linux-hardware.org/?probe=a0e3328769) | Oct 21, 2020 |
| Dell          | 0599V5 A09                  | Server      | [a98d12ad3e](https://linux-hardware.org/?probe=a98d12ad3e) | Oct 20, 2020 |
| Dell          | Latitude E6410              | Notebook    | [926bbbdaf2](https://linux-hardware.org/?probe=926bbbdaf2) | Oct 18, 2020 |
| ASUSTek       | P9X79                       | Desktop     | [e0a6bc45ee](https://linux-hardware.org/?probe=e0a6bc45ee) | Oct 17, 2020 |
| ASUSTek       | P9X79                       | Desktop     | [d14403a73b](https://linux-hardware.org/?probe=d14403a73b) | Oct 17, 2020 |
| HP            | 1495                        | Desktop     | [a678a5caf0](https://linux-hardware.org/?probe=a678a5caf0) | Oct 13, 2020 |
| Dell          | 01NP3N A00                  | Desktop     | [1f5b92d91b](https://linux-hardware.org/?probe=1f5b92d91b) | Oct 12, 2020 |
| ASRock        | X99 Taichi                  | Desktop     | [fabde85a5a](https://linux-hardware.org/?probe=fabde85a5a) | Oct 11, 2020 |
| ASUSTek       | F2A55-M LE                  | Desktop     | [1fc864e04c](https://linux-hardware.org/?probe=1fc864e04c) | Oct 10, 2020 |
| Dell          | 0W7H8C A05                  | Server      | [815d325e62](https://linux-hardware.org/?probe=815d325e62) | Oct 10, 2020 |
| Lenovo        | G500s 20245                 | Notebook    | [8a975cb577](https://linux-hardware.org/?probe=8a975cb577) | Oct 07, 2020 |
| Dell          | Latitude E6410              | Notebook    | [a36dab9e9b](https://linux-hardware.org/?probe=a36dab9e9b) | Oct 06, 2020 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [ff2176937d](https://linux-hardware.org/?probe=ff2176937d) | Oct 03, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [50534bc0e0](https://linux-hardware.org/?probe=50534bc0e0) | Oct 01, 2020 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [b00098bf37](https://linux-hardware.org/?probe=b00098bf37) | Sep 29, 2020 |
| ASUSTek       | X556UB                      | Notebook    | [15790fbe92](https://linux-hardware.org/?probe=15790fbe92) | Sep 28, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [8ead41d349](https://linux-hardware.org/?probe=8ead41d349) | Sep 28, 2020 |
| Dell          | 0W7H8C A05                  | Server      | [e4e1a6fb02](https://linux-hardware.org/?probe=e4e1a6fb02) | Sep 28, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [29fdcb6b00](https://linux-hardware.org/?probe=29fdcb6b00) | Sep 28, 2020 |
| Timi          | TM1709                      | Notebook    | [9d4bd50d80](https://linux-hardware.org/?probe=9d4bd50d80) | Sep 25, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [0c5285cd22](https://linux-hardware.org/?probe=0c5285cd22) | Sep 20, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [bcf59e135b](https://linux-hardware.org/?probe=bcf59e135b) | Sep 19, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [43d38ed1be](https://linux-hardware.org/?probe=43d38ed1be) | Sep 19, 2020 |
| HP            | 0AECh D                     | Desktop     | [d80079cb33](https://linux-hardware.org/?probe=d80079cb33) | Sep 18, 2020 |
| Supermicro    | X11SPW-TF                   | Server      | [94ef768b34](https://linux-hardware.org/?probe=94ef768b34) | Sep 17, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | Desktop     | [b363aea94a](https://linux-hardware.org/?probe=b363aea94a) | Sep 17, 2020 |
| Fujitsu       | D3401-H1 S26361-D3401-H1    | Desktop     | [1896a5c345](https://linux-hardware.org/?probe=1896a5c345) | Sep 17, 2020 |
| Gigabyte      | P35V3                       | Notebook    | [55580f63c2](https://linux-hardware.org/?probe=55580f63c2) | Sep 14, 2020 |
| HP            | ProLiant DL165 G7           | Server      | [91ad975174](https://linux-hardware.org/?probe=91ad975174) | Sep 14, 2020 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [5788667247](https://linux-hardware.org/?probe=5788667247) | Sep 12, 2020 |
| AEWIN         | SCB-1711A                   | Desktop     | [2d8dbb0d3a](https://linux-hardware.org/?probe=2d8dbb0d3a) | Sep 09, 2020 |
| HP            | 8053                        | Desktop     | [b00f600647](https://linux-hardware.org/?probe=b00f600647) | Sep 09, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [daceea1b39](https://linux-hardware.org/?probe=daceea1b39) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [233a83b315](https://linux-hardware.org/?probe=233a83b315) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [fcb2182f02](https://linux-hardware.org/?probe=fcb2182f02) | Sep 08, 2020 |
| Unknown       | 34AS1                       | Notebook    | [cc188d0f25](https://linux-hardware.org/?probe=cc188d0f25) | Sep 08, 2020 |
| Unknown       | 34AS1                       | Notebook    | [0ab59553ea](https://linux-hardware.org/?probe=0ab59553ea) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [751df6a75b](https://linux-hardware.org/?probe=751df6a75b) | Sep 08, 2020 |
| Dell          | Inspiron 3542               | Notebook    | [14680221b6](https://linux-hardware.org/?probe=14680221b6) | Sep 07, 2020 |
| HP            | ProLiant DL360 G5           | Server      | [b3175c4255](https://linux-hardware.org/?probe=b3175c4255) | Sep 05, 2020 |
| Intel         | D54250WYK H13922-303        | Desktop     | [219e110c70](https://linux-hardware.org/?probe=219e110c70) | Sep 03, 2020 |
| HP            | EliteBook 6930p             | Notebook    | [8fdba744ec](https://linux-hardware.org/?probe=8fdba744ec) | Sep 03, 2020 |
| Dell          | Inspiron 5567               | Notebook    | [d7700d73c4](https://linux-hardware.org/?probe=d7700d73c4) | Sep 03, 2020 |
| Zenith        | Orion                       | Desktop     | [9de5e32b25](https://linux-hardware.org/?probe=9de5e32b25) | Sep 02, 2020 |
| Acer          | Spin SP513-51               | Convertible | [95af4b8dc9](https://linux-hardware.org/?probe=95af4b8dc9) | Aug 31, 2020 |
| HP            | 0B54h D                     | Desktop     | [b39f47faf8](https://linux-hardware.org/?probe=b39f47faf8) | Aug 26, 2020 |
| ASUSTek       | P7P55D                      | Desktop     | [4a55c3588b](https://linux-hardware.org/?probe=4a55c3588b) | Aug 26, 2020 |
| Dell          | 0GTK4K A02                  | Desktop     | [81f3fe5ce0](https://linux-hardware.org/?probe=81f3fe5ce0) | Aug 26, 2020 |
| Dell          | 0GTK4K A02                  | Desktop     | [09fb692364](https://linux-hardware.org/?probe=09fb692364) | Aug 26, 2020 |
| Supermicro    | X8DT3                       | Server      | [c3337aa815](https://linux-hardware.org/?probe=c3337aa815) | Aug 24, 2020 |
| ASUSTek       | 1001HA                      | Notebook    | [7935f0bc4a](https://linux-hardware.org/?probe=7935f0bc4a) | Aug 23, 2020 |
| Lenovo        | ThinkPad T430s 2356CZ4      | Notebook    | [585b5cd200](https://linux-hardware.org/?probe=585b5cd200) | Aug 22, 2020 |
| Lenovo        | ThinkPad T430s 2356CZ4      | Notebook    | [b16e78abbf](https://linux-hardware.org/?probe=b16e78abbf) | Aug 21, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [1c28fb67ab](https://linux-hardware.org/?probe=1c28fb67ab) | Aug 20, 2020 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [2377cf4d5e](https://linux-hardware.org/?probe=2377cf4d5e) | Aug 19, 2020 |
| AZW           | U55                         | Mini pc     | [961d8fad80](https://linux-hardware.org/?probe=961d8fad80) | Aug 19, 2020 |
| AZW           | U55                         | Mini pc     | [6ee89b7a33](https://linux-hardware.org/?probe=6ee89b7a33) | Aug 19, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [c51c0d5538](https://linux-hardware.org/?probe=c51c0d5538) | Aug 15, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [f0d9b71d6d](https://linux-hardware.org/?probe=f0d9b71d6d) | Aug 15, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [eeaeff9e52](https://linux-hardware.org/?probe=eeaeff9e52) | Aug 12, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [03abb9daf3](https://linux-hardware.org/?probe=03abb9daf3) | Aug 11, 2020 |
| Lenovo        | ThinkServer TS140           | Desktop     | [2d296ca69c](https://linux-hardware.org/?probe=2d296ca69c) | Aug 11, 2020 |
| ASRockRack    | EP2C622D16-2T               | Server      | [ef434d4b56](https://linux-hardware.org/?probe=ef434d4b56) | Aug 07, 2020 |
| HP            | ProBook 440 G2              | Notebook    | [b19e6b64a7](https://linux-hardware.org/?probe=b19e6b64a7) | Aug 07, 2020 |
| MSI           | B350M PRO-VDH               | Desktop     | [301fe36ff7](https://linux-hardware.org/?probe=301fe36ff7) | Aug 06, 2020 |
| MSI           | GE73VR 7RF                  | Notebook    | [8f05f68c7d](https://linux-hardware.org/?probe=8f05f68c7d) | Aug 04, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [cbcae43afd](https://linux-hardware.org/?probe=cbcae43afd) | Aug 02, 2020 |
| ASUSTek       | Z10PA-D8 Series             | Server      | [da20c4ffdb](https://linux-hardware.org/?probe=da20c4ffdb) | Aug 02, 2020 |
| Dell          | 08HPGT A02                  | Desktop     | [fa6826d636](https://linux-hardware.org/?probe=fa6826d636) | Aug 02, 2020 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [001888ed9c](https://linux-hardware.org/?probe=001888ed9c) | Aug 02, 2020 |
| Gigabyte      | P35-DS4                     | Desktop     | [d9b3b9a12e](https://linux-hardware.org/?probe=d9b3b9a12e) | Aug 02, 2020 |
| Gigabyte      | P35-DS4                     | Desktop     | [3a33cfc73c](https://linux-hardware.org/?probe=3a33cfc73c) | Aug 02, 2020 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [c27cdabb7b](https://linux-hardware.org/?probe=c27cdabb7b) | Aug 02, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [08325f77c1](https://linux-hardware.org/?probe=08325f77c1) | Aug 01, 2020 |
| HP            | Notebook                    | Notebook    | [00a853f189](https://linux-hardware.org/?probe=00a853f189) | Aug 01, 2020 |
| Dell          | 0W23H8 A00                  | Server      | [e752263e49](https://linux-hardware.org/?probe=e752263e49) | Jul 27, 2020 |
| Gigabyte      | H97-HD3                     | Desktop     | [06c68b698e](https://linux-hardware.org/?probe=06c68b698e) | Jul 24, 2020 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [8907cdddd5](https://linux-hardware.org/?probe=8907cdddd5) | Jul 24, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [be78e318ef](https://linux-hardware.org/?probe=be78e318ef) | Jul 23, 2020 |
| Samsung       | R560                        | Notebook    | [4d35b24594](https://linux-hardware.org/?probe=4d35b24594) | Jul 23, 2020 |
| HP            | EliteBook 850 G3            | Notebook    | [529b5be1b5](https://linux-hardware.org/?probe=529b5be1b5) | Jul 14, 2020 |
| HP            | ProBook 640 G2              | Notebook    | [53ba25afcd](https://linux-hardware.org/?probe=53ba25afcd) | Jul 14, 2020 |
| HP            | 0AECh D                     | Desktop     | [c6310b9606](https://linux-hardware.org/?probe=c6310b9606) | Jul 14, 2020 |
| ASUSTek       | Z97-E/USB                   | Desktop     | [f6f4d985ea](https://linux-hardware.org/?probe=f6f4d985ea) | Jul 13, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [2244646450](https://linux-hardware.org/?probe=2244646450) | Jul 11, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [80c07a542a](https://linux-hardware.org/?probe=80c07a542a) | Jul 11, 2020 |
| HP            | 1589                        | Desktop     | [d142f54a38](https://linux-hardware.org/?probe=d142f54a38) | Jul 11, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [8566dd2843](https://linux-hardware.org/?probe=8566dd2843) | Jul 11, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ce6e9cb36](https://linux-hardware.org/?probe=8ce6e9cb36) | Jul 10, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [116cbdcf22](https://linux-hardware.org/?probe=116cbdcf22) | Jul 09, 2020 |
| Dell          | 0YXT71 A02                  | Desktop     | [0d249e4d90](https://linux-hardware.org/?probe=0d249e4d90) | Jul 08, 2020 |
| ASRockRack    | EP2C612 WS                  | Desktop     | [4392ed1437](https://linux-hardware.org/?probe=4392ed1437) | Jul 08, 2020 |
| Dell          | 0JP31P A16                  | Server      | [9d7f34d428](https://linux-hardware.org/?probe=9d7f34d428) | Jul 07, 2020 |
| Dell          | 0JP31P A16                  | Server      | [7e35e837e0](https://linux-hardware.org/?probe=7e35e837e0) | Jul 07, 2020 |
| HP            | Falco                       | Notebook    | [26ace050f7](https://linux-hardware.org/?probe=26ace050f7) | Jul 07, 2020 |
| Dell          | 073MMW A00                  | Desktop     | [115d71c055](https://linux-hardware.org/?probe=115d71c055) | Jul 06, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [2a05830be5](https://linux-hardware.org/?probe=2a05830be5) | Jul 05, 2020 |
| Intel         | H81C                        | Desktop     | [54732275c2](https://linux-hardware.org/?probe=54732275c2) | Jul 04, 2020 |
| Gigabyte      | EP45-DS3R                   | Desktop     | [cfad3da667](https://linux-hardware.org/?probe=cfad3da667) | Jul 03, 2020 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [d014e3ba24](https://linux-hardware.org/?probe=d014e3ba24) | Jul 03, 2020 |
| Dell          | 0PYVT1 A03                  | Server      | [b7f3606e31](https://linux-hardware.org/?probe=b7f3606e31) | Jun 30, 2020 |
| Dell          | 0C8306 A00                  | Server      | [40f9d31598](https://linux-hardware.org/?probe=40f9d31598) | Jun 29, 2020 |
| Dell          | 0C8306 A00                  | Server      | [8448795f6c](https://linux-hardware.org/?probe=8448795f6c) | Jun 28, 2020 |
| Unknown       | IPM31-AK                    | Desktop     | [acd334c9b0](https://linux-hardware.org/?probe=acd334c9b0) | Jun 28, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [670706063d](https://linux-hardware.org/?probe=670706063d) | Jun 25, 2020 |
| Gigabyte      | P85-D3                      | Desktop     | [3be565ccfd](https://linux-hardware.org/?probe=3be565ccfd) | Jun 23, 2020 |
| ASUSTek       | P8Z77-V                     | Desktop     | [f94256b581](https://linux-hardware.org/?probe=f94256b581) | Jun 22, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f9990a3c91](https://linux-hardware.org/?probe=f9990a3c91) | Jun 22, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6d4908178c](https://linux-hardware.org/?probe=6d4908178c) | Jun 22, 2020 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [bdaf8406b2](https://linux-hardware.org/?probe=bdaf8406b2) | Jun 22, 2020 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [f2bfe6bfb3](https://linux-hardware.org/?probe=f2bfe6bfb3) | Jun 22, 2020 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [51b8e4300b](https://linux-hardware.org/?probe=51b8e4300b) | Jun 20, 2020 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [e1184552d0](https://linux-hardware.org/?probe=e1184552d0) | Jun 20, 2020 |
| ASRock        | Z170 Extreme7+              | Desktop     | [56fa210d0c](https://linux-hardware.org/?probe=56fa210d0c) | Jun 20, 2020 |
| ASRock        | Z170 Extreme7+              | Desktop     | [b2d975c2e7](https://linux-hardware.org/?probe=b2d975c2e7) | Jun 20, 2020 |
| HP            | ProLiant DL360 G5           | Server      | [2af0fad914](https://linux-hardware.org/?probe=2af0fad914) | Jun 19, 2020 |
| HP            | ProLiant DL360 G5           | Server      | [908a5e8c78](https://linux-hardware.org/?probe=908a5e8c78) | Jun 19, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [8c28479e2e](https://linux-hardware.org/?probe=8c28479e2e) | Jun 19, 2020 |
| HP            | Laptop 14-bp0xx             | Notebook    | [6efe053f69](https://linux-hardware.org/?probe=6efe053f69) | Jun 18, 2020 |
| HP            | 81C7 MVB 0C                 | Server      | [b5360affff](https://linux-hardware.org/?probe=b5360affff) | Jun 18, 2020 |
| HP            | Laptop 14-bp0xx             | Notebook    | [e1611d4a8f](https://linux-hardware.org/?probe=e1611d4a8f) | Jun 18, 2020 |
| MSI           | 2A9C                        | Desktop     | [9af3bb0a4e](https://linux-hardware.org/?probe=9af3bb0a4e) | Jun 17, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [765261db4d](https://linux-hardware.org/?probe=765261db4d) | Jun 17, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [08a9f86f96](https://linux-hardware.org/?probe=08a9f86f96) | Jun 17, 2020 |
| HP            | ZBook Studio x360 G5        | Convertible | [620453a9dc](https://linux-hardware.org/?probe=620453a9dc) | Jun 16, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [3d59a7abfb](https://linux-hardware.org/?probe=3d59a7abfb) | Jun 14, 2020 |
| Packard Be... | MCP73VT-PM                  | Desktop     | [8cba2e7fa8](https://linux-hardware.org/?probe=8cba2e7fa8) | Jun 14, 2020 |
| Packard Be... | MCP73VT-PM                  | Desktop     | [26f700fbc5](https://linux-hardware.org/?probe=26f700fbc5) | Jun 14, 2020 |
| Supermicro    | X10DRG-H                    | Desktop     | [3bd676846b](https://linux-hardware.org/?probe=3bd676846b) | Jun 12, 2020 |
| Dell          | Inspiron 3520               | Notebook    | [0fe6cc7ec2](https://linux-hardware.org/?probe=0fe6cc7ec2) | Jun 11, 2020 |
| ASRock        | X399 Professional Gaming    | Desktop     | [d313005743](https://linux-hardware.org/?probe=d313005743) | Jun 10, 2020 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [4660651265](https://linux-hardware.org/?probe=4660651265) | Jun 09, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9020f6e51c](https://linux-hardware.org/?probe=9020f6e51c) | Jun 07, 2020 |
| MSI           | B450M MORTAR MAX            | Desktop     | [db0ff5f985](https://linux-hardware.org/?probe=db0ff5f985) | Jun 07, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [edbd2a746d](https://linux-hardware.org/?probe=edbd2a746d) | Jun 06, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [2605330e8c](https://linux-hardware.org/?probe=2605330e8c) | Jun 04, 2020 |
| Intel         | DP45SG AAE27733-405         | Desktop     | [f195015cf8](https://linux-hardware.org/?probe=f195015cf8) | Jun 02, 2020 |
| IBM           | 00W2263                     | Server      | [fc0558920d](https://linux-hardware.org/?probe=fc0558920d) | Jun 01, 2020 |
| Sony          | VPCEG15FB                   | Notebook    | [764c88fff0](https://linux-hardware.org/?probe=764c88fff0) | May 30, 2020 |
| Dell          | 0VRWRC A00                  | Desktop     | [dd7e20baec](https://linux-hardware.org/?probe=dd7e20baec) | May 29, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [cc3e01ff0f](https://linux-hardware.org/?probe=cc3e01ff0f) | May 29, 2020 |
| Dell          | 0VRWRC A00                  | Desktop     | [c27987482d](https://linux-hardware.org/?probe=c27987482d) | May 29, 2020 |
| Lenovo        | ThinkPad E580 20KS001JRT    | Notebook    | [a9b9b6f30e](https://linux-hardware.org/?probe=a9b9b6f30e) | May 29, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d4cbe90b0f](https://linux-hardware.org/?probe=d4cbe90b0f) | May 27, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [8f5cbe37da](https://linux-hardware.org/?probe=8f5cbe37da) | May 26, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [396660cc0e](https://linux-hardware.org/?probe=396660cc0e) | May 26, 2020 |
| Dell          | 0YXT71 A02                  | Desktop     | [e3f86df812](https://linux-hardware.org/?probe=e3f86df812) | May 25, 2020 |
| ASRock        | AM1B-ITX                    | Desktop     | [d0b6f8f474](https://linux-hardware.org/?probe=d0b6f8f474) | May 25, 2020 |
| Supermicro    | X10DAI                      | Desktop     | [c2d45e8975](https://linux-hardware.org/?probe=c2d45e8975) | May 21, 2020 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [a82798aea1](https://linux-hardware.org/?probe=a82798aea1) | May 21, 2020 |
| IBM           | I/O Port                    | Server      | [7c109612b9](https://linux-hardware.org/?probe=7c109612b9) | May 20, 2020 |
| Acer          | Aspire 5750G                | Notebook    | [e99f24b527](https://linux-hardware.org/?probe=e99f24b527) | May 15, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [912c44b0ac](https://linux-hardware.org/?probe=912c44b0ac) | May 15, 2020 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [3f253aecbb](https://linux-hardware.org/?probe=3f253aecbb) | May 15, 2020 |
| ASUSTek       | CM1740                      | Desktop     | [65921c1a5e](https://linux-hardware.org/?probe=65921c1a5e) | May 14, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [3ad583ff3d](https://linux-hardware.org/?probe=3ad583ff3d) | May 14, 2020 |
| HP            | ZBook Studio x360 G5        | Convertible | [0420235572](https://linux-hardware.org/?probe=0420235572) | May 08, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [6a3f0afa07](https://linux-hardware.org/?probe=6a3f0afa07) | May 07, 2020 |
| Acer          | Aspire 5750G                | Notebook    | [1f49c0d636](https://linux-hardware.org/?probe=1f49c0d636) | May 06, 2020 |
| Dell          | Latitude E6220              | Notebook    | [a4db1d31a5](https://linux-hardware.org/?probe=a4db1d31a5) | May 05, 2020 |
| Dell          | Latitude E6220              | Notebook    | [c0152a3b02](https://linux-hardware.org/?probe=c0152a3b02) | May 05, 2020 |
| HP            | 1495                        | Desktop     | [a38478daa1](https://linux-hardware.org/?probe=a38478daa1) | May 05, 2020 |
| HP            | 1495                        | Desktop     | [6fed1750c3](https://linux-hardware.org/?probe=6fed1750c3) | May 05, 2020 |
| Foxconn       | 17A0                        | Desktop     | [167cb26122](https://linux-hardware.org/?probe=167cb26122) | May 03, 2020 |
| Toshiba       | Satellite Radius 12 P20W... | Notebook    | [4f272f1c99](https://linux-hardware.org/?probe=4f272f1c99) | May 03, 2020 |
| ASUSTek       | X556UB                      | Notebook    | [ae412b00e1](https://linux-hardware.org/?probe=ae412b00e1) | May 02, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [5856d8fd4a](https://linux-hardware.org/?probe=5856d8fd4a) | Apr 30, 2020 |
| Medion        | P6622                       | Notebook    | [57721ffc8f](https://linux-hardware.org/?probe=57721ffc8f) | Apr 29, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [0606d60ddb](https://linux-hardware.org/?probe=0606d60ddb) | Apr 29, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [c4f288077d](https://linux-hardware.org/?probe=c4f288077d) | Apr 29, 2020 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [16dbe6c7cf](https://linux-hardware.org/?probe=16dbe6c7cf) | Apr 28, 2020 |
| Dell          | Precision 7510              | Notebook    | [40e5c33fd8](https://linux-hardware.org/?probe=40e5c33fd8) | Apr 27, 2020 |
| Supermicro    | H12SSW-NT                   | Server      | [7027370293](https://linux-hardware.org/?probe=7027370293) | Apr 27, 2020 |
| Supermicro    | X10SDE-DF                   | Desktop     | [54cbea6bb1](https://linux-hardware.org/?probe=54cbea6bb1) | Apr 26, 2020 |
| Supermicro    | X10SDE-DF                   | Desktop     | [3c55fe3c77](https://linux-hardware.org/?probe=3c55fe3c77) | Apr 26, 2020 |
| Lenovo        | ThinkPad T500 2242CTO       | Notebook    | [8d383c8ba6](https://linux-hardware.org/?probe=8d383c8ba6) | Apr 25, 2020 |
| Lenovo        | ThinkPad T500 2242CTO       | Notebook    | [82c9bdc55a](https://linux-hardware.org/?probe=82c9bdc55a) | Apr 25, 2020 |
| Biostar       | A320MH                      | Desktop     | [bc6b5804c2](https://linux-hardware.org/?probe=bc6b5804c2) | Apr 24, 2020 |
| Dell          | Inspiron 3520               | Notebook    | [30d580cc9d](https://linux-hardware.org/?probe=30d580cc9d) | Apr 23, 2020 |
| Dell          | Inspiron 3520               | Notebook    | [e18488f436](https://linux-hardware.org/?probe=e18488f436) | Apr 23, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [64941f8ea2](https://linux-hardware.org/?probe=64941f8ea2) | Apr 21, 2020 |
| Intel         | S5000PSL                    | Server      | [0e19261b88](https://linux-hardware.org/?probe=0e19261b88) | Apr 21, 2020 |
| Sony          | VGN-N19VP_B                 | Notebook    | [a2e6c99940](https://linux-hardware.org/?probe=a2e6c99940) | Apr 20, 2020 |
| ASRockRack    | EP2C612 WS                  | Desktop     | [22419b4efe](https://linux-hardware.org/?probe=22419b4efe) | Apr 20, 2020 |
| Dell          | 0C3YXR A01                  | Desktop     | [b50f6391f3](https://linux-hardware.org/?probe=b50f6391f3) | Apr 19, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [cfed23f08f](https://linux-hardware.org/?probe=cfed23f08f) | Apr 18, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [bf90b17b91](https://linux-hardware.org/?probe=bf90b17b91) | Apr 15, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [d3f96f55f3](https://linux-hardware.org/?probe=d3f96f55f3) | Apr 15, 2020 |
| Lenovo        | ThinkPad T440 20B7004JUS    | Notebook    | [7e54937ed3](https://linux-hardware.org/?probe=7e54937ed3) | Apr 15, 2020 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [a78c0430fb](https://linux-hardware.org/?probe=a78c0430fb) | Apr 15, 2020 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [6e7470b8c3](https://linux-hardware.org/?probe=6e7470b8c3) | Apr 15, 2020 |
| Apple         | MacBookPro12,1              | Notebook    | [e3673127d2](https://linux-hardware.org/?probe=e3673127d2) | Apr 14, 2020 |
| Dell          | 0YXT71 A02                  | Desktop     | [f454033e1f](https://linux-hardware.org/?probe=f454033e1f) | Apr 13, 2020 |
| HP            | EliteBook Folio 9470m       | Notebook    | [9439de5a1c](https://linux-hardware.org/?probe=9439de5a1c) | Apr 12, 2020 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [17ba5a84d9](https://linux-hardware.org/?probe=17ba5a84d9) | Apr 12, 2020 |
| RM Educati... | RM                          | Notebook    | [548492cfc9](https://linux-hardware.org/?probe=548492cfc9) | Apr 11, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c670b78e38](https://linux-hardware.org/?probe=c670b78e38) | Apr 11, 2020 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [5d17d05d00](https://linux-hardware.org/?probe=5d17d05d00) | Apr 11, 2020 |
| HP            | ProBook 430 G5              | Notebook    | [a1f59e373b](https://linux-hardware.org/?probe=a1f59e373b) | Apr 10, 2020 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [95a4ea12d4](https://linux-hardware.org/?probe=95a4ea12d4) | Apr 05, 2020 |
| Unknown       | LakePort                    | Desktop     | [85bfbe1e35](https://linux-hardware.org/?probe=85bfbe1e35) | Apr 02, 2020 |
| Dell          | 01V648 A04                  | Server      | [e27841554a](https://linux-hardware.org/?probe=e27841554a) | Mar 26, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [03322f98e6](https://linux-hardware.org/?probe=03322f98e6) | Mar 24, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b3782f0e54](https://linux-hardware.org/?probe=b3782f0e54) | Mar 20, 2020 |
| Lenovo        | B50-70 80EU                 | Notebook    | [32162d2fcb](https://linux-hardware.org/?probe=32162d2fcb) | Mar 19, 2020 |
| ASRock        | X399 Professional Gaming    | Desktop     | [efe1215f69](https://linux-hardware.org/?probe=efe1215f69) | Mar 19, 2020 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | Notebook    | [2918602e15](https://linux-hardware.org/?probe=2918602e15) | Mar 12, 2020 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | Notebook    | [8376f889c2](https://linux-hardware.org/?probe=8376f889c2) | Mar 12, 2020 |
| HP            | 843F                        | Desktop     | [f76a18754d](https://linux-hardware.org/?probe=f76a18754d) | Mar 12, 2020 |
| Dell          | 040DDP A01                  | Desktop     | [1e1a7753ca](https://linux-hardware.org/?probe=1e1a7753ca) | Mar 10, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [6fc52e234a](https://linux-hardware.org/?probe=6fc52e234a) | Mar 09, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [906db6cad1](https://linux-hardware.org/?probe=906db6cad1) | Mar 09, 2020 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [29d31a8603](https://linux-hardware.org/?probe=29d31a8603) | Mar 08, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d2ab3b608a](https://linux-hardware.org/?probe=d2ab3b608a) | Mar 07, 2020 |
| Dell          | 0X8DXD A01                  | Desktop     | [37012211e0](https://linux-hardware.org/?probe=37012211e0) | Mar 05, 2020 |
| HPE           | ProLiant MicroServer Gen... | Server      | [f3e948ba19](https://linux-hardware.org/?probe=f3e948ba19) | Feb 29, 2020 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [ed0506aa18](https://linux-hardware.org/?probe=ed0506aa18) | Feb 25, 2020 |
| Acer          | One 14 Z2-485               | Notebook    | [d7c11b1573](https://linux-hardware.org/?probe=d7c11b1573) | Feb 24, 2020 |
| Acer          | One 14 Z2-485               | Notebook    | [22a7ce37ed](https://linux-hardware.org/?probe=22a7ce37ed) | Feb 24, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [f2997e7cab](https://linux-hardware.org/?probe=f2997e7cab) | Feb 24, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [d38140cd66](https://linux-hardware.org/?probe=d38140cd66) | Feb 24, 2020 |
| HP            | ProBook 450 G5              | Notebook    | [7d51d0400f](https://linux-hardware.org/?probe=7d51d0400f) | Feb 24, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [54d3d863ad](https://linux-hardware.org/?probe=54d3d863ad) | Feb 23, 2020 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [72895d5cc3](https://linux-hardware.org/?probe=72895d5cc3) | Feb 23, 2020 |
| Dell          | Precision 5510              | Notebook    | [97fdd683cd](https://linux-hardware.org/?probe=97fdd683cd) | Feb 23, 2020 |
| Gigabyte      | EX58-EXTREME                | Desktop     | [2ce62d5ef2](https://linux-hardware.org/?probe=2ce62d5ef2) | Feb 23, 2020 |
| Dell          | 0FRVY0 A06                  | Server      | [40545e3bb0](https://linux-hardware.org/?probe=40545e3bb0) | Feb 21, 2020 |
| Dell          | 0CNCJW A05                  | Server      | [c436f9e67a](https://linux-hardware.org/?probe=c436f9e67a) | Feb 21, 2020 |
| Dell          | 0CNCJW A05                  | Server      | [0b376dd32a](https://linux-hardware.org/?probe=0b376dd32a) | Feb 21, 2020 |
| Supermicro    | X10DAI                      | Desktop     | [8bb87102a9](https://linux-hardware.org/?probe=8bb87102a9) | Feb 20, 2020 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [d256eaa680](https://linux-hardware.org/?probe=d256eaa680) | Feb 16, 2020 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [f86854d517](https://linux-hardware.org/?probe=f86854d517) | Feb 16, 2020 |
| HP            | ZBook 17                    | Notebook    | [5937f48c97](https://linux-hardware.org/?probe=5937f48c97) | Feb 13, 2020 |
| HP            | Laptop 15-bs1xx             | Notebook    | [891cb66753](https://linux-hardware.org/?probe=891cb66753) | Feb 06, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [d45674e336](https://linux-hardware.org/?probe=d45674e336) | Feb 06, 2020 |
| Sony          | VPCSB19GG                   | Notebook    | [cc8806b4ec](https://linux-hardware.org/?probe=cc8806b4ec) | Feb 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [10a7b3c4f3](https://linux-hardware.org/?probe=10a7b3c4f3) | Feb 01, 2020 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [ca1f92519f](https://linux-hardware.org/?probe=ca1f92519f) | Jan 29, 2020 |
| Acer          | TravelMate P257-M           | Notebook    | [5dbe9649a7](https://linux-hardware.org/?probe=5dbe9649a7) | Jan 28, 2020 |
| ASUSTek       | AT4NM10T-I                  | Desktop     | [a0fa3c7ca0](https://linux-hardware.org/?probe=a0fa3c7ca0) | Jan 28, 2020 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [2c5e967e3a](https://linux-hardware.org/?probe=2c5e967e3a) | Jan 25, 2020 |
| Dell          | 00NH4P A14                  | Server      | [ce13a1d7e9](https://linux-hardware.org/?probe=ce13a1d7e9) | Jan 25, 2020 |
| Clevo         | P15xEMx                     | Notebook    | [e41e485e3b](https://linux-hardware.org/?probe=e41e485e3b) | Jan 25, 2020 |
| HP            | 18E4                        | Desktop     | [f6f6dfd341](https://linux-hardware.org/?probe=f6f6dfd341) | Jan 25, 2020 |
| MSI           | H77MA-G43                   | Desktop     | [5a0c6d2f14](https://linux-hardware.org/?probe=5a0c6d2f14) | Jan 24, 2020 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [917bf2b4cf](https://linux-hardware.org/?probe=917bf2b4cf) | Jan 24, 2020 |
| Dell          | 0C27VV A01                  | Desktop     | [01545ea8b0](https://linux-hardware.org/?probe=01545ea8b0) | Jan 24, 2020 |
| Dell          | 081N4V A01                  | Server      | [9a09d720c8](https://linux-hardware.org/?probe=9a09d720c8) | Jan 24, 2020 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [9d92e8ed9d](https://linux-hardware.org/?probe=9d92e8ed9d) | Jan 24, 2020 |
| Dell          | 0M5DCD A00                  | Desktop     | [21e230fb02](https://linux-hardware.org/?probe=21e230fb02) | Jan 24, 2020 |
| Gigabyte      | Z77N-WIFI                   | Desktop     | [94c13c0e97](https://linux-hardware.org/?probe=94c13c0e97) | Jan 11, 2020 |
| ASUSTek       | X550MJ                      | Notebook    | [16470618ab](https://linux-hardware.org/?probe=16470618ab) | Jan 09, 2020 |
| Foxconn       | 2AA9                        | Desktop     | [2b2a941903](https://linux-hardware.org/?probe=2b2a941903) | Jan 07, 2020 |
| Foxconn       | 2AA9                        | Desktop     | [ed7e0428fb](https://linux-hardware.org/?probe=ed7e0428fb) | Jan 07, 2020 |
| Dell          | Inspiron N4010              | Notebook    | [5b5d5fc395](https://linux-hardware.org/?probe=5b5d5fc395) | Jan 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [95488c6be1](https://linux-hardware.org/?probe=95488c6be1) | Jan 02, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [925412ddcd](https://linux-hardware.org/?probe=925412ddcd) | Jan 02, 2020 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [3c407e606c](https://linux-hardware.org/?probe=3c407e606c) | Dec 31, 2019 |
| HP            | EliteBook x360 1040 G6      | Notebook    | [7d1585f3cd](https://linux-hardware.org/?probe=7d1585f3cd) | Dec 28, 2019 |
| Gigabyte      | EP45-DS4                    | Desktop     | [13acec4985](https://linux-hardware.org/?probe=13acec4985) | Dec 25, 2019 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [0b771c098e](https://linux-hardware.org/?probe=0b771c098e) | Dec 20, 2019 |
| AIC           | LIBRA                       | Server      | [2903921aeb](https://linux-hardware.org/?probe=2903921aeb) | Dec 17, 2019 |
| AIC           | LIBRA                       | Server      | [43ee2001e1](https://linux-hardware.org/?probe=43ee2001e1) | Dec 17, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e795735d5b](https://linux-hardware.org/?probe=e795735d5b) | Dec 14, 2019 |
| Dell          | 0VRJCG A05                  | Server      | [0fc3f83656](https://linux-hardware.org/?probe=0fc3f83656) | Dec 14, 2019 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | Notebook    | [46bfb60272](https://linux-hardware.org/?probe=46bfb60272) | Dec 14, 2019 |
| HP            | 0A98h                       | Desktop     | [e68759aa8e](https://linux-hardware.org/?probe=e68759aa8e) | Dec 12, 2019 |
| MSI           | H55M-E33                    | Desktop     | [48d4121155](https://linux-hardware.org/?probe=48d4121155) | Dec 10, 2019 |
| ASRock        | X79 Extreme11               | Desktop     | [1b28cc994f](https://linux-hardware.org/?probe=1b28cc994f) | Dec 07, 2019 |
| Dell          | Studio 1747                 | Notebook    | [e572489472](https://linux-hardware.org/?probe=e572489472) | Dec 05, 2019 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [02eca27578](https://linux-hardware.org/?probe=02eca27578) | Dec 05, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [1bb0047e0e](https://linux-hardware.org/?probe=1bb0047e0e) | Dec 03, 2019 |
| Dell          | System XPS L702X            | Notebook    | [ba096189bc](https://linux-hardware.org/?probe=ba096189bc) | Dec 03, 2019 |
| Toshiba       | Satellite L15W-B            | Notebook    | [c90b14d1e5](https://linux-hardware.org/?probe=c90b14d1e5) | Dec 03, 2019 |
| Dell          | Studio 1747                 | Notebook    | [24d64d118b](https://linux-hardware.org/?probe=24d64d118b) | Dec 02, 2019 |
| MSI           | GL63 8SD                    | Notebook    | [3cef0087aa](https://linux-hardware.org/?probe=3cef0087aa) | Dec 01, 2019 |
| Dell          | 0PC5F7 A01                  | Desktop     | [ba442e31fa](https://linux-hardware.org/?probe=ba442e31fa) | Nov 24, 2019 |
| ASUSTek       | E202SA                      | Notebook    | [e052cf247b](https://linux-hardware.org/?probe=e052cf247b) | Nov 23, 2019 |
| ASUSTek       | Benicia                     | Desktop     | [5d4f2621ec](https://linux-hardware.org/?probe=5d4f2621ec) | Nov 22, 2019 |
| Dell          | 09KPNV A01                  | Desktop     | [0c44bfb480](https://linux-hardware.org/?probe=0c44bfb480) | Nov 22, 2019 |
| Dell          | 0XR1GT A00                  | Desktop     | [76dba7bb94](https://linux-hardware.org/?probe=76dba7bb94) | Nov 22, 2019 |
| Toshiba       | Satellite L15W-B            | Notebook    | [c96da5df5e](https://linux-hardware.org/?probe=c96da5df5e) | Nov 20, 2019 |
| Toshiba       | Satellite L15W-B            | Notebook    | [bf3a6bb4c3](https://linux-hardware.org/?probe=bf3a6bb4c3) | Nov 20, 2019 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [df76fe3ea4](https://linux-hardware.org/?probe=df76fe3ea4) | Nov 14, 2019 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [448a81eb7c](https://linux-hardware.org/?probe=448a81eb7c) | Nov 14, 2019 |
| HP            | ProLiant MicroServer        | Desktop     | [fdfa4ab709](https://linux-hardware.org/?probe=fdfa4ab709) | Nov 14, 2019 |
| Dell          | 07T4MC A06                  | Desktop     | [8fba67a719](https://linux-hardware.org/?probe=8fba67a719) | Nov 14, 2019 |
| Lenovo        | MAHOBAY                     | Desktop     | [652157e27c](https://linux-hardware.org/?probe=652157e27c) | Nov 03, 2019 |
| Lenovo        | MAHOBAY                     | Desktop     | [fd672567d1](https://linux-hardware.org/?probe=fd672567d1) | Nov 03, 2019 |
| HP            | Notebook                    | Notebook    | [4aae147ff7](https://linux-hardware.org/?probe=4aae147ff7) | Nov 01, 2019 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [0c5c6bd0d1](https://linux-hardware.org/?probe=0c5c6bd0d1) | Oct 31, 2019 |
| ASUSTek       | Benicia                     | Desktop     | [764ecc00c4](https://linux-hardware.org/?probe=764ecc00c4) | Oct 30, 2019 |
| ASUSTek       | Benicia                     | Desktop     | [c604466168](https://linux-hardware.org/?probe=c604466168) | Oct 26, 2019 |
| Sony          | VPCEH26EN                   | Notebook    | [28024462ac](https://linux-hardware.org/?probe=28024462ac) | Oct 22, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [17d03076df](https://linux-hardware.org/?probe=17d03076df) | Oct 16, 2019 |
| Dell          | Vostro 5568                 | Notebook    | [a0b3e4d70f](https://linux-hardware.org/?probe=a0b3e4d70f) | Oct 16, 2019 |
| Lenovo        | 3135 SDK0J40697 WIN 3305... | Mini pc     | [aa1be9cbec](https://linux-hardware.org/?probe=aa1be9cbec) | Oct 15, 2019 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [11a89e3f6f](https://linux-hardware.org/?probe=11a89e3f6f) | Oct 13, 2019 |
| ECS           | H55H-M                      | Desktop     | [970477516c](https://linux-hardware.org/?probe=970477516c) | Oct 12, 2019 |
| ECS           | H55H-M                      | Desktop     | [dab03eeec5](https://linux-hardware.org/?probe=dab03eeec5) | Oct 12, 2019 |
| ASUSTek       | P8H67-M                     | Desktop     | [a3522aac75](https://linux-hardware.org/?probe=a3522aac75) | Oct 09, 2019 |
| ASUSTek       | P8H67-M                     | Desktop     | [1c6a686559](https://linux-hardware.org/?probe=1c6a686559) | Oct 08, 2019 |
| ASUSTek       | P8H67-M                     | Desktop     | [8c40634de7](https://linux-hardware.org/?probe=8c40634de7) | Oct 08, 2019 |
| Supermicro    | X7DVL                       | Desktop     | [e4951bb84b](https://linux-hardware.org/?probe=e4951bb84b) | Oct 05, 2019 |
| Gigabyte      | X58A-UD5                    | Desktop     | [c1cd5017a5](https://linux-hardware.org/?probe=c1cd5017a5) | Oct 05, 2019 |
| RM Educati... | RM                          | Notebook    | [4d22671841](https://linux-hardware.org/?probe=4d22671841) | Oct 03, 2019 |
| RM Educati... | RM                          | Notebook    | [43aad9067d](https://linux-hardware.org/?probe=43aad9067d) | Oct 02, 2019 |
| Supermicro    | X8DTN+-F                    | Server      | [cf99aad395](https://linux-hardware.org/?probe=cf99aad395) | Sep 16, 2019 |
| Supermicro    | X8DTN+-F                    | Server      | [de7268071a](https://linux-hardware.org/?probe=de7268071a) | Sep 16, 2019 |
| Supermicro    | X8DTN+-F                    | Server      | [550719b1d2](https://linux-hardware.org/?probe=550719b1d2) | Sep 16, 2019 |
| HP            | Pavilion 15                 | Notebook    | [7e407e7cd4](https://linux-hardware.org/?probe=7e407e7cd4) | Sep 15, 2019 |
| HP            | Pavilion 15                 | Notebook    | [447f75484c](https://linux-hardware.org/?probe=447f75484c) | Sep 11, 2019 |
| HP            | Pavilion 15                 | Notebook    | [9352d1efae](https://linux-hardware.org/?probe=9352d1efae) | Sep 11, 2019 |
| Gigabyte      | B360HD3PLM-CF               | Desktop     | [05d00cc5d7](https://linux-hardware.org/?probe=05d00cc5d7) | Sep 09, 2019 |
| Supermicro    | X8DTL                       | Server      | [f94537400b](https://linux-hardware.org/?probe=f94537400b) | Sep 08, 2019 |
| Gigabyte      | 970A-D3P                    | Desktop     | [6e3666d8c9](https://linux-hardware.org/?probe=6e3666d8c9) | Sep 04, 2019 |
| MSI           | GP62MVR 7RFX                | Notebook    | [5a21834bbd](https://linux-hardware.org/?probe=5a21834bbd) | Sep 01, 2019 |
| Notebook      | WA50SRQ                     | Notebook    | [fd99d2b5e2](https://linux-hardware.org/?probe=fd99d2b5e2) | Aug 09, 2019 |
| AMI           | Cherry Trail CR             | Desktop     | [fe652a02c9](https://linux-hardware.org/?probe=fe652a02c9) | Jul 25, 2019 |
| Dell          | 09KPNV A00                  | Desktop     | [a72c60b73b](https://linux-hardware.org/?probe=a72c60b73b) | Jul 24, 2019 |
| Supermicro    | X8DTL                       | Server      | [e6f0f25fea](https://linux-hardware.org/?probe=e6f0f25fea) | Jul 22, 2019 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [b2fac79afd](https://linux-hardware.org/?probe=b2fac79afd) | Jun 27, 2019 |
| ASRockRack    | E3C242D4U2-2T               | Desktop     | [44eb4c1fed](https://linux-hardware.org/?probe=44eb4c1fed) | Jun 25, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/CentOS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| CentOS 7      | 335       | 45.39%  |
| CentOS 8      | 327       | 44.31%  |
| CentOS 9      | 49        | 6.64%   |
| CentOS Stream | 11        | 1.49%   |
| CentOS 6      | 11        | 1.49%   |
| CentOS 6.9    | 2         | 0.27%   |
| CentOS 5      | 2         | 0.27%   |
| CentOS 6.10   | 1         | 0.14%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| CentOS | 732       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 4.18.0-147.8.1.el8_1.x86_64  | 27        | 3.3%    |
| 4.18.0-193.6.3.el8_2.x86_64  | 23        | 2.81%   |
| 4.18.0-193.28.1.el8_2.x86_64 | 21        | 2.56%   |
| 4.18.0-193.14.2.el8_2.x86_64 | 20        | 2.44%   |
| 4.18.0-240.22.1.el8_3.x86_64 | 17        | 2.08%   |
| 3.10.0-862.14.4.el7.x86_64   | 17        | 2.08%   |
| 4.18.0-80.11.2.el8_0.x86_64  | 16        | 1.95%   |
| 4.18.0-147.5.1.el8_1.x86_64  | 16        | 1.95%   |
| 4.18.0-240.15.1.el8_3.x86_64 | 15        | 1.83%   |
| 4.18.0-193.19.1.el8_2.x86_64 | 15        | 1.83%   |
| 4.18.0-348.2.1.el8_5.x86_64  | 14        | 1.71%   |
| 4.18.0-240.1.1.el8_3.x86_64  | 13        | 1.59%   |
| 3.10.0-1160.25.1.el7.x86_64  | 13        | 1.59%   |
| 3.10.0-1160.45.1.el7.x86_64  | 12        | 1.47%   |
| 3.10.0-1160.31.1.el7.x86_64  | 12        | 1.47%   |
| 3.10.0-1062.12.1.el7.x86_64  | 12        | 1.47%   |
| 4.18.0-240.10.1.el8_3.x86_64 | 10        | 1.22%   |
| 3.10.0-957.10.1.el7.x86_64   | 10        | 1.22%   |
| 3.10.0-1160.66.1.el7.x86_64  | 10        | 1.22%   |
| 3.10.0-1160.36.2.el7.x86_64  | 10        | 1.22%   |
| 4.18.0-348.7.1.el8_5.x86_64  | 9         | 1.1%    |
| 3.10.0-1160.76.1.el7.x86_64  | 9         | 1.1%    |
| 3.10.0-1160.15.2.el7.x86_64  | 9         | 1.1%    |
| 3.10.0-1127.19.1.el7.x86_64  | 9         | 1.1%    |
| 3.10.0-1062.el7.x86_64       | 9         | 1.1%    |
| 4.18.0-305.12.1.el8_4.x86_64 | 8         | 0.98%   |
| 3.10.0-957.1.3.el7.x86_64    | 8         | 0.98%   |
| 3.10.0-1127.el7.x86_64       | 8         | 0.98%   |
| 4.18.0-305.19.1.el8_4.x86_64 | 7         | 0.85%   |
| 4.18.0-301.1.el8.x86_64      | 7         | 0.85%   |
| 4.18.0-147.el8.x86_64        | 7         | 0.85%   |
| 4.18.0-147.3.1.el8_1.x86_64  | 7         | 0.85%   |
| 3.10.0-957.5.1.el7.x86_64    | 7         | 0.85%   |
| 3.10.0-957.27.2.el7.x86_64   | 7         | 0.85%   |
| 3.10.0-1160.83.1.el7.x86_64  | 7         | 0.85%   |
| 3.10.0-1062.9.1.el7.x86_64   | 7         | 0.85%   |
| 4.18.0-408.el8.x86_64        | 6         | 0.73%   |
| 4.18.0-294.el8.x86_64        | 6         | 0.73%   |
| 3.10.0-1160.49.1.el7.x86_64  | 6         | 0.73%   |
| 3.10.0-1127.13.1.el7.x86_64  | 6         | 0.73%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18.0  | 319       | 42.99%  |
| 3.10.0  | 297       | 40.03%  |
| 5.14.0  | 47        | 6.33%   |
| 2.6.32  | 13        | 1.75%   |
| 5.4.118 | 3         | 0.4%    |
| 6.1.1   | 2         | 0.27%   |
| 5.9.12  | 2         | 0.27%   |
| 5.17.2  | 2         | 0.27%   |
| 5.15.11 | 2         | 0.27%   |
| 5.12.0  | 2         | 0.27%   |
| 2.6.18  | 2         | 0.27%   |
| 6.5.6   | 1         | 0.13%   |
| 6.5.2   | 1         | 0.13%   |
| 6.2.2   | 1         | 0.13%   |
| 6.1.8   | 1         | 0.13%   |
| 5.9.1   | 1         | 0.13%   |
| 5.8.13  | 1         | 0.13%   |
| 5.8.11  | 1         | 0.13%   |
| 5.8.0   | 1         | 0.13%   |
| 5.7.7   | 1         | 0.13%   |
| 5.7.10  | 1         | 0.13%   |
| 5.6.8   | 1         | 0.13%   |
| 5.6.10  | 1         | 0.13%   |
| 5.5.0   | 1         | 0.13%   |
| 5.4.96  | 1         | 0.13%   |
| 5.4.61  | 1         | 0.13%   |
| 5.4.6   | 1         | 0.13%   |
| 5.4.249 | 1         | 0.13%   |
| 5.4.234 | 1         | 0.13%   |
| 5.4.225 | 1         | 0.13%   |
| 5.4.158 | 1         | 0.13%   |
| 5.4.142 | 1         | 0.13%   |
| 5.4.125 | 1         | 0.13%   |
| 5.4.121 | 1         | 0.13%   |
| 5.4.119 | 1         | 0.13%   |
| 5.4.113 | 1         | 0.13%   |
| 5.3.11  | 1         | 0.13%   |
| 5.2.13  | 1         | 0.13%   |
| 5.2.1   | 1         | 0.13%   |
| 5.18.13 | 1         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.18    | 320       | 43.24%  |
| 3.10    | 297       | 40.14%  |
| 5.14    | 48        | 6.49%   |
| 2.6     | 15        | 2.03%   |
| 5.4     | 14        | 1.89%   |
| 4.9     | 4         | 0.54%   |
| 6.1     | 3         | 0.41%   |
| 5.9     | 3         | 0.41%   |
| 5.8     | 3         | 0.41%   |
| 5.15    | 3         | 0.41%   |
| 5.10    | 3         | 0.41%   |
| 6.5     | 2         | 0.27%   |
| 5.7     | 2         | 0.27%   |
| 5.6     | 2         | 0.27%   |
| 5.18    | 2         | 0.27%   |
| 5.17    | 2         | 0.27%   |
| 5.13    | 2         | 0.27%   |
| 5.12    | 2         | 0.27%   |
| 4.20    | 2         | 0.27%   |
| 4.19    | 2         | 0.27%   |
| 6.2     | 1         | 0.14%   |
| 5.5     | 1         | 0.14%   |
| 5.3     | 1         | 0.14%   |
| 5.2     | 1         | 0.14%   |
| 5.11    | 1         | 0.14%   |
| 5.1     | 1         | 0.14%   |
| 4.4     | 1         | 0.14%   |
| 4.17    | 1         | 0.14%   |
| 4.14    | 1         | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 725       | 99.04%  |
| i686    | 6         | 0.82%   |
| aarch64 | 1         | 0.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 413       | 55.81%  |
| Unknown       | 188       | 25.41%  |
| GNOME Classic | 51        | 6.89%   |
| KDE4          | 39        | 5.27%   |
| MATE          | 17        | 2.3%    |
| XFCE          | 13        | 1.76%   |
| KDE5          | 8         | 1.08%   |
| Cinnamon      | 7         | 0.95%   |
| X-Cinnamon    | 2         | 0.27%   |
| Xpra          | 1         | 0.14%   |
| KDE           | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 411       | 54.73%  |
| Wayland | 218       | 29.03%  |
| Unknown | 116       | 15.45%  |
| Web     | 4         | 0.53%   |
| Tty     | 2         | 0.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 403       | 54.31%  |
| GDM     | 310       | 41.78%  |
| LightDM | 16        | 2.16%   |
| SDDM    | 8         | 1.08%   |
| TDM     | 4         | 0.54%   |
| KDM     | 1         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 362       | 48.79%  |
| Unknown     | 108       | 14.56%  |
| en_GB       | 36        | 4.85%   |
| ru_RU       | 34        | 4.58%   |
| de_DE       | 28        | 3.77%   |
| pt_BR       | 20        | 2.7%    |
| fr_FR       | 20        | 2.7%    |
| C           | 20        | 2.7%    |
| en_IN       | 11        | 1.48%   |
| en_CA       | 11        | 1.48%   |
| pl_PL       | 10        | 1.35%   |
| zh_CN       | 9         | 1.21%   |
| en_AU       | 8         | 1.08%   |
| de_AT       | 8         | 1.08%   |
| ko_KR       | 6         | 0.81%   |
| it_IT       | 5         | 0.67%   |
| es_ES       | 4         | 0.54%   |
| en_US.utf-8 | 4         | 0.54%   |
| nb_NO       | 3         | 0.4%    |
| ja_JP       | 3         | 0.4%    |
| es_PE       | 3         | 0.4%    |
| fr_CA       | 2         | 0.27%   |
| fi_FI       | 2         | 0.27%   |
| es_MX       | 2         | 0.27%   |
| es_EC       | 2         | 0.27%   |
| es_AR       | 2         | 0.27%   |
| cs_CZ       | 2         | 0.27%   |
| uk_UA       | 1         | 0.13%   |
| tr_TR       | 1         | 0.13%   |
| sv_SE       | 1         | 0.13%   |
| sl_SI       | 1         | 0.13%   |
| sk_SK       | 1         | 0.13%   |
| ru_UA       | 1         | 0.13%   |
| ru_RU.UTF8  | 1         | 0.13%   |
| pt_PT       | 1         | 0.13%   |
| ko_KR.euckr | 1         | 0.13%   |
| hu_HU       | 1         | 0.13%   |
| es_US       | 1         | 0.13%   |
| en_ZA       | 1         | 0.13%   |
| en_SG       | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 378       | 51.36%  |
| BIOS | 358       | 48.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Xfs     | 574       | 77.78%  |
| Ext4    | 135       | 18.29%  |
| Unknown | 23        | 3.12%   |
| Ext3    | 4         | 0.54%   |
| Overlay | 1         | 0.14%   |
| Ext2    | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 318       | 42.68%  |
| Unknown | 260       | 34.9%   |
| MBR     | 167       | 22.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 622       | 84.17%  |
| Yes       | 117       | 15.83%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 639       | 86.59%  |
| Yes       | 99        | 13.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 134       | 18.31%  |
| Hewlett-Packard     | 108       | 14.75%  |
| ASUSTek Computer    | 97        | 13.25%  |
| Lenovo              | 80        | 10.93%  |
| Gigabyte Technology | 58        | 7.92%   |
| Supermicro          | 51        | 6.97%   |
| Intel               | 37        | 5.05%   |
| MSI                 | 29        | 3.96%   |
| Acer                | 18        | 2.46%   |
| ASRock              | 13        | 1.78%   |
| Unknown             | 10        | 1.37%   |
| Samsung Electronics | 7         | 0.96%   |
| Sony                | 6         | 0.82%   |
| IBM                 | 6         | 0.82%   |
| Fujitsu             | 6         | 0.82%   |
| ASRockRack          | 5         | 0.68%   |
| Apple               | 5         | 0.68%   |
| Foxconn             | 4         | 0.55%   |
| AMI                 | 4         | 0.55%   |
| Toshiba             | 3         | 0.41%   |
| Timi                | 3         | 0.41%   |
| AZW                 | 3         | 0.41%   |
| Sun Microsystems    | 2         | 0.27%   |
| Quanta              | 2         | 0.27%   |
| MiTAC               | 2         | 0.27%   |
| LG Electronics      | 2         | 0.27%   |
| HPE                 | 2         | 0.27%   |
| ECS                 | 2         | 0.27%   |
| AIC                 | 2         | 0.27%   |
| Zvezda              | 1         | 0.14%   |
| Zenith              | 1         | 0.14%   |
| TYAN Computer       | 1         | 0.14%   |
| TUXEDO              | 1         | 0.14%   |
| RM Education        | 1         | 0.14%   |
| Razer               | 1         | 0.14%   |
| PCChips             | 1         | 0.14%   |
| Panasonic           | 1         | 0.14%   |
| Packard Bell        | 1         | 0.14%   |
| Notebook            | 1         | 0.14%   |
| NORCO               | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Supermicro Super Server                 | 24        | 3.28%   |
| Unknown                                 | 10        | 1.37%   |
| Dell OptiPlex 9020                      | 9         | 1.23%   |
| Dell OptiPlex 7040                      | 9         | 1.23%   |
| ASUS All Series                         | 8         | 1.09%   |
| Supermicro X8DTN+-F                     | 4         | 0.55%   |
| HP Z800 Workstation                     | 4         | 0.55%   |
| HP Compaq Elite 8300 SFF                | 4         | 0.55%   |
| Lenovo ThinkSystem SR650 -[7X06CTO1WW]- | 3         | 0.41%   |
| HP ProLiant DL360 G5                    | 3         | 0.41%   |
| HP ProDesk 400 G7 Microtower PC         | 3         | 0.41%   |
| HP EliteDesk 800 G6 Desktop Mini PC     | 3         | 0.41%   |
| HP Compaq 8200 Elite SFF PC             | 3         | 0.41%   |
| Dell Precision WorkStation T3500        | 3         | 0.41%   |
| Dell OptiPlex 7010                      | 3         | 0.41%   |
| ASUS M5A78L-M PLUS/USB3                 | 3         | 0.41%   |
| ASRockRack E3C242D4U2-2T                | 3         | 0.41%   |
| Supermicro X8DTL                        | 2         | 0.27%   |
| Supermicro SYS-7048A-T                  | 2         | 0.27%   |
| Supermicro SYS-1028TP-DC1R              | 2         | 0.27%   |
| Quanta QSSC-98J_C2                      | 2         | 0.27%   |
| Lenovo Z50-70 20354                     | 2         | 0.27%   |
| Lenovo ThinkSystem SR530 -[7X08CTO1WW]- | 2         | 0.27%   |
| Lenovo System x3650 M5: -[8871AC1]-     | 2         | 0.27%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK   | 2         | 0.27%   |
| Intel S1200SP                           | 2         | 0.27%   |
| Intel NUC12WSHi5                        | 2         | 0.27%   |
| Intel NUC10i7FNH                        | 2         | 0.27%   |
| IBM System x3550 M3 -[7944AC1]-         | 2         | 0.27%   |
| HPE ProLiant MicroServer Gen10          | 2         | 0.27%   |
| HP Z420 Workstation                     | 2         | 0.27%   |
| HP Z2 Tower G5 Workstation              | 2         | 0.27%   |
| HP ProLiant MicroServer                 | 2         | 0.27%   |
| HP ProBook 450 G5                       | 2         | 0.27%   |
| HP Notebook                             | 2         | 0.27%   |
| HP EliteDesk 805 G6 Desktop Mini PC     | 2         | 0.27%   |
| HP EliteBook 840 G5                     | 2         | 0.27%   |
| Gigabyte X470 AORUS ULTRA GAMING        | 2         | 0.27%   |
| Gigabyte H97N-WIFI                      | 2         | 0.27%   |
| Gigabyte GA-78LMT-USB3                  | 2         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 41        | 5.6%    |
| Dell OptiPlex              | 34        | 4.64%   |
| Dell PowerEdge             | 30        | 4.1%    |
| Supermicro Super           | 24        | 3.28%   |
| Dell Precision             | 20        | 2.73%   |
| HP EliteBook               | 16        | 2.19%   |
| Dell Latitude              | 16        | 2.19%   |
| Dell Inspiron              | 16        | 2.19%   |
| ASUS PRIME                 | 15        | 2.05%   |
| HP EliteDesk               | 12        | 1.64%   |
| HP ProLiant                | 11        | 1.5%    |
| Acer Aspire                | 11        | 1.5%    |
| Unknown                    | 10        | 1.37%   |
| Lenovo IdeaPad             | 9         | 1.23%   |
| HP ProBook                 | 9         | 1.23%   |
| HP Compaq                  | 9         | 1.23%   |
| Dell Vostro                | 8         | 1.09%   |
| ASUS All                   | 8         | 1.09%   |
| Lenovo ThinkSystem         | 7         | 0.96%   |
| ASUS TUF                   | 7         | 0.96%   |
| ASUS ROG                   | 7         | 0.96%   |
| HP Pavilion                | 6         | 0.82%   |
| Lenovo ThinkCentre         | 5         | 0.68%   |
| IBM System                 | 5         | 0.68%   |
| HP ZBook                   | 5         | 0.68%   |
| HP ProDesk                 | 5         | 0.68%   |
| Dell XPS                   | 5         | 0.68%   |
| ASUS M5A78L-M              | 5         | 0.68%   |
| Supermicro X8DTN+-F        | 4         | 0.55%   |
| HP Z800                    | 4         | 0.55%   |
| HP Laptop                  | 4         | 0.55%   |
| Toshiba Satellite          | 3         | 0.41%   |
| HP Z2                      | 3         | 0.41%   |
| Gigabyte GA-78LMT-USB3     | 3         | 0.41%   |
| ASUS VivoBook              | 3         | 0.41%   |
| ASUS P8Z77-V               | 3         | 0.41%   |
| ASRockRack E3C242D4U2-2T   | 3         | 0.41%   |
| Supermicro X8DTL           | 2         | 0.27%   |
| Supermicro SYS-7048A-T     | 2         | 0.27%   |
| Supermicro SYS-1028TP-DC1R | 2         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 78        | 10.66%  |
| 2018    | 67        | 9.15%   |
| 2012    | 62        | 8.47%   |
| 2016    | 60        | 8.2%    |
| 2020    | 59        | 8.06%   |
| 2017    | 58        | 7.92%   |
| 2013    | 56        | 7.65%   |
| 2011    | 50        | 6.83%   |
| 2014    | 48        | 6.56%   |
| 2010    | 47        | 6.42%   |
| 2015    | 37        | 5.05%   |
| 2021    | 35        | 4.78%   |
| 2008    | 26        | 3.55%   |
| 2009    | 20        | 2.73%   |
| 2007    | 11        | 1.5%    |
| 2022    | 9         | 1.23%   |
| 2023    | 3         | 0.41%   |
| 2006    | 3         | 0.41%   |
| Unknown | 2         | 0.27%   |
| 2001    | 1         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 349       | 47.68%  |
| Notebook    | 220       | 30.05%  |
| Server      | 114       | 15.57%  |
| Mini pc     | 39        | 5.33%   |
| Convertible | 7         | 0.96%   |
| All in one  | 3         | 0.41%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 698       | 95.23%  |
| Enabled  | 35        | 4.77%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 730       | 99.73%  |
| Yes  | 2         | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 186       | 25.31%  |
| 32.01-64.0      | 117       | 15.92%  |
| 16.01-24.0      | 114       | 15.51%  |
| 64.01-256.0     | 81        | 11.02%  |
| 8.01-16.0       | 81        | 11.02%  |
| 3.01-4.0        | 75        | 10.2%   |
| More than 256.0 | 39        | 5.31%   |
| 24.01-32.0      | 18        | 2.45%   |
| 1.01-2.0        | 17        | 2.31%   |
| 0.51-1.0        | 4         | 0.54%   |
| 2.01-3.0        | 3         | 0.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 2.01-3.0        | 183       | 23.16%  |
| 1.01-2.0        | 143       | 18.1%   |
| 4.01-8.0        | 139       | 17.59%  |
| 3.01-4.0        | 119       | 15.06%  |
| 8.01-16.0       | 62        | 7.85%   |
| 0.51-1.0        | 61        | 7.72%   |
| 64.01-256.0     | 21        | 2.66%   |
| Unknown         | 15        | 1.9%    |
| 32.01-64.0      | 14        | 1.77%   |
| 0.01-0.5        | 14        | 1.77%   |
| 16.01-24.0      | 9         | 1.14%   |
| 24.01-32.0      | 7         | 0.89%   |
| More than 256.0 | 3         | 0.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 338       | 45.25%  |
| 2       | 172       | 23.03%  |
| 3       | 78        | 10.44%  |
| 4       | 43        | 5.76%   |
| 5       | 23        | 3.08%   |
| Unknown | 21        | 2.81%   |
| 6       | 16        | 2.14%   |
| 0       | 8         | 1.07%   |
| 7       | 7         | 0.94%   |
| 10      | 6         | 0.8%    |
| 8       | 5         | 0.67%   |
| 9       | 4         | 0.54%   |
| 19      | 3         | 0.4%    |
| 15      | 3         | 0.4%    |
| 13      | 3         | 0.4%    |
| 11      | 3         | 0.4%    |
| 97      | 2         | 0.27%   |
| 93      | 2         | 0.27%   |
| 209     | 1         | 0.13%   |
| 71      | 1         | 0.13%   |
| 68      | 1         | 0.13%   |
| 37      | 1         | 0.13%   |
| 27      | 1         | 0.13%   |
| 26      | 1         | 0.13%   |
| 24      | 1         | 0.13%   |
| 18      | 1         | 0.13%   |
| 17      | 1         | 0.13%   |
| 12      | 1         | 0.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 473       | 64.27%  |
| Yes       | 263       | 35.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 698       | 95.36%  |
| No        | 34        | 4.64%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 375       | 51.02%  |
| Yes       | 360       | 48.98%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 441       | 60.16%  |
| Yes       | 292       | 39.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 166       | 22.52%  |
| Russia       | 66        | 8.96%   |
| Germany      | 55        | 7.46%   |
| Brazil       | 33        | 4.48%   |
| Canada       | 31        | 4.21%   |
| France       | 29        | 3.93%   |
| UK           | 28        | 3.8%    |
| India        | 28        | 3.8%    |
| China        | 26        | 3.53%   |
| Poland       | 15        | 2.04%   |
| Sweden       | 14        | 1.9%    |
| Switzerland  | 12        | 1.63%   |
| Belgium      | 12        | 1.63%   |
| Australia    | 12        | 1.63%   |
| Finland      | 11        | 1.49%   |
| Ukraine      | 10        | 1.36%   |
| Spain        | 10        | 1.36%   |
| South Korea  | 10        | 1.36%   |
| Netherlands  | 10        | 1.36%   |
| Mexico       | 10        | 1.36%   |
| Italy        | 10        | 1.36%   |
| Czechia      | 9         | 1.22%   |
| Bulgaria     | 8         | 1.09%   |
| Norway       | 7         | 0.95%   |
| South Africa | 6         | 0.81%   |
| Israel       | 6         | 0.81%   |
| Turkey       | 5         | 0.68%   |
| Kazakhstan   | 5         | 0.68%   |
| Japan        | 5         | 0.68%   |
| Indonesia    | 5         | 0.68%   |
| Romania      | 4         | 0.54%   |
| Peru         | 4         | 0.54%   |
| Malaysia     | 4         | 0.54%   |
| Taiwan       | 3         | 0.41%   |
| Slovakia     | 3         | 0.41%   |
| Serbia       | 3         | 0.41%   |
| Portugal     | 3         | 0.41%   |
| Lithuania    | 3         | 0.41%   |
| Iran         | 3         | 0.41%   |
| Hong Kong    | 3         | 0.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 27        | 3.56%   |
| Rochester         | 19        | 2.51%   |
| Madison           | 17        | 2.24%   |
| Alexandria        | 9         | 1.19%   |
| Sydney            | 7         | 0.92%   |
| Paris             | 7         | 0.92%   |
| Helsinki          | 7         | 0.92%   |
| St Petersburg     | 6         | 0.79%   |
| Sofia             | 6         | 0.79%   |
| Sao Paulo         | 6         | 0.79%   |
| Prague            | 6         | 0.79%   |
| Portland          | 6         | 0.79%   |
| London            | 6         | 0.79%   |
| Frankfurt am Main | 6         | 0.79%   |
| Berlin            | 6         | 0.79%   |
| Toronto           | 5         | 0.66%   |
| Munich            | 5         | 0.66%   |
| Kyiv              | 5         | 0.66%   |
| Guwahati          | 5         | 0.66%   |
| Bern              | 5         | 0.66%   |
| Beijing           | 5         | 0.66%   |
| Vancouver         | 4         | 0.53%   |
| Sollentuna        | 4         | 0.53%   |
| Rio de Janeiro    | 4         | 0.53%   |
| Montreal          | 4         | 0.53%   |
| Lima              | 4         | 0.53%   |
| Guangzhou         | 4         | 0.53%   |
| Yekaterinburg     | 3         | 0.4%    |
| Victoria          | 3         | 0.4%    |
| Tehran            | 3         | 0.4%    |
| Tampa             | 3         | 0.4%    |
| Stockholm         | 3         | 0.4%    |
| Shanghai          | 3         | 0.4%    |
| Phoenix           | 3         | 0.4%    |
| Nur-Sultan        | 3         | 0.4%    |
| New York          | 3         | 0.4%    |
| Mumbai            | 3         | 0.4%    |
| Mexico City       | 3         | 0.4%    |
| Los Angeles       | 3         | 0.4%    |
| Leuven            | 3         | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 187       | 721    | 17.03%  |
| WDC                          | 182       | 645    | 16.58%  |
| Samsung Electronics          | 166       | 324    | 15.12%  |
| Toshiba                      | 73        | 119    | 6.65%   |
| Kingston                     | 67        | 83     | 6.1%    |
| Intel                        | 46        | 97     | 4.19%   |
| SanDisk                      | 42        | 54     | 3.83%   |
| Hitachi                      | 37        | 77     | 3.37%   |
| Unknown                      | 30        | 107    | 2.73%   |
| HGST                         | 30        | 316    | 2.73%   |
| Micron Technology            | 23        | 40     | 2.09%   |
| Crucial                      | 23        | 38     | 2.09%   |
| SK hynix                     | 15        | 16     | 1.37%   |
| A-DATA Technology            | 13        | 18     | 1.18%   |
| Hewlett-Packard              | 12        | 44     | 1.09%   |
| SPCC                         | 10        | 17     | 0.91%   |
| Silicon Motion               | 6         | 6      | 0.55%   |
| Phison                       | 6         | 7      | 0.55%   |
| OCZ                          | 6         | 12     | 0.55%   |
| Plextor                      | 4         | 4      | 0.36%   |
| Micron/Crucial Technology    | 4         | 5      | 0.36%   |
| LITEON                       | 4         | 5      | 0.36%   |
| Lenovo                       | 4         | 6      | 0.36%   |
| Gigabyte Technology          | 4         | 5      | 0.36%   |
| Apple                        | 4         | 5      | 0.36%   |
| Toshiba America Info Systems | 3         | 4      | 0.27%   |
| PNY                          | 3         | 4      | 0.27%   |
| NVMe                         | 3         | 3      | 0.27%   |
| LITEONIT                     | 3         | 3      | 0.27%   |
| Lexar                        | 3         | 4      | 0.27%   |
| KIOXIA                       | 3         | 4      | 0.27%   |
| Fujitsu                      | 3         | 4      | 0.27%   |
| China                        | 3         | 6      | 0.27%   |
| ASMT                         | 3         | 6      | 0.27%   |
| XPG                          | 2         | 2      | 0.18%   |
| Union Memory                 | 2         | 2      | 0.18%   |
| UMIS                         | 2         | 2      | 0.18%   |
| Transcend                    | 2         | 3      | 0.18%   |
| Team                         | 2         | 3      | 0.18%   |
| Sun                          | 2         | 6      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000DM010-2EP102 1TB         | 11        | 0.83%   |
| Kingston SA400S37240G 240GB SSD        | 11        | 0.83%   |
| Toshiba DT01ACA100 1TB                 | 10        | 0.75%   |
| Seagate ST500DM002-1BD142 500GB        | 10        | 0.75%   |
| Toshiba DT01ACA050 500GB               | 9         | 0.68%   |
| WDC WD10EZEX-08WN4A0 1TB               | 8         | 0.6%    |
| Samsung NVMe SSD Drive 512GB           | 8         | 0.6%    |
| Kingston SA400S37120G 120GB SSD        | 8         | 0.6%    |
| WDC WD20EARX-00PASB0 2TB               | 7         | 0.53%   |
| Unknown HUH728080ALE601 8TB            | 7         | 0.53%   |
| Seagate ST6000NM0095 6TB               | 7         | 0.53%   |
| Seagate ST6000NM0034 6TB               | 7         | 0.53%   |
| Seagate ST6000NM0014 6TB               | 7         | 0.53%   |
| Seagate ST500DM002-1SB10A 500GB        | 7         | 0.53%   |
| Seagate ST4000NXCLAR4000 4TB           | 7         | 0.53%   |
| Seagate ST4000NM0023 4TB               | 7         | 0.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 7         | 0.53%   |
| Toshiba MQ01ABD100 1TB                 | 6         | 0.45%   |
| Seagate ST16000NM001G-2KK103 16TB      | 6         | 0.45%   |
| Seagate ST1000LM035-1RK172 1TB         | 6         | 0.45%   |
| Seagate ST1000DM003-1CH162 1TB         | 6         | 0.45%   |
| Samsung SSD 860 EVO 250GB              | 6         | 0.45%   |
| Samsung SSD 850 EVO 250GB              | 6         | 0.45%   |
| Kingston SA400S37480G 480GB SSD        | 6         | 0.45%   |
| HGST HUS726060ALS640 6TB               | 6         | 0.45%   |
| HGST H7280A520SUN8.0T 8TB              | 6         | 0.45%   |
| WDC WD20EZRZ-00Z5HB0 2TB               | 5         | 0.38%   |
| WDC WD20EZRX-00D8PB0 2TB               | 5         | 0.38%   |
| Seagate ST500LT012-1DG142 500GB        | 5         | 0.38%   |
| Seagate ST2000DM006-2DM164 2TB         | 5         | 0.38%   |
| SanDisk NVMe SSD Drive 512GB           | 5         | 0.38%   |
| Samsung SSD 980 1TB                    | 5         | 0.38%   |
| Samsung SSD 860 EVO 500GB              | 5         | 0.38%   |
| Samsung SSD 860 EVO 1TB                | 5         | 0.38%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB | 5         | 0.38%   |
| Micron 9300_MTFDHAL6T4TDR 6.4TB        | 5         | 0.38%   |
| HGST HUH721212ALE600 12TB              | 5         | 0.38%   |
| HGST HUH721010AL4200 10TB              | 5         | 0.38%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 4         | 0.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 4         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 182       | 713    | 34.73%  |
| WDC                 | 163       | 405    | 31.11%  |
| Toshiba             | 61        | 100    | 11.64%  |
| Hitachi             | 37        | 77     | 7.06%   |
| HGST                | 30        | 177    | 5.73%   |
| Samsung Electronics | 19        | 106    | 3.63%   |
| Unknown             | 10        | 83     | 1.91%   |
| Hewlett-Packard     | 7         | 35     | 1.34%   |
| Fujitsu             | 3         | 4      | 0.57%   |
| Apple               | 3         | 3      | 0.57%   |
| Sun                 | 2         | 6      | 0.38%   |
| Dell                | 2         | 2      | 0.38%   |
| WD MediaMax         | 1         | 1      | 0.19%   |
| Maxtor              | 1         | 1      | 0.19%   |
| MARVELL             | 1         | 1      | 0.19%   |
| Lenovo              | 1         | 2      | 0.19%   |
| IBM-ESXS            | 1         | 2      | 0.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 93        | 134    | 24.16%  |
| Kingston            | 63        | 79     | 16.36%  |
| Intel               | 38        | 77     | 9.87%   |
| WDC                 | 21        | 29     | 5.45%   |
| SanDisk             | 21        | 25     | 5.45%   |
| Crucial             | 20        | 35     | 5.19%   |
| Micron Technology   | 13        | 21     | 3.38%   |
| SPCC                | 10        | 17     | 2.6%    |
| SK hynix            | 10        | 11     | 2.6%    |
| A-DATA Technology   | 10        | 13     | 2.6%    |
| Toshiba             | 9         | 13     | 2.34%   |
| OCZ                 | 6         | 12     | 1.56%   |
| Hewlett-Packard     | 5         | 9      | 1.3%    |
| LITEON              | 4         | 5      | 1.04%   |
| PNY                 | 3         | 4      | 0.78%   |
| Plextor             | 3         | 3      | 0.78%   |
| LITEONIT            | 3         | 3      | 0.78%   |
| China               | 3         | 6      | 0.78%   |
| ASMT                | 3         | 6      | 0.78%   |
| Transcend           | 2         | 3      | 0.52%   |
| Team                | 2         | 3      | 0.52%   |
| StoreJet            | 2         | 2      | 0.52%   |
| Smartbuy            | 2         | 3      | 0.52%   |
| Seagate             | 2         | 2      | 0.52%   |
| Patriot             | 2         | 6      | 0.52%   |
| Lexar               | 2         | 3      | 0.52%   |
| Lenovo              | 2         | 3      | 0.52%   |
| KingDian            | 2         | 6      | 0.52%   |
| Intenso             | 2         | 2      | 0.52%   |
| GOODRAM             | 2         | 2      | 0.52%   |
| Apacer              | 2         | 2      | 0.52%   |
| XrayDisk            | 1         | 1      | 0.26%   |
| Verbatim            | 1         | 1      | 0.26%   |
| V-GeN               | 1         | 1      | 0.26%   |
| Unknown (1GB)       | 1         | 1      | 0.26%   |
| UNIC2               | 1         | 1      | 0.26%   |
| TAISU               | 1         | 1      | 0.26%   |
| SSD                 | 1         | 1      | 0.26%   |
| SATADOM-SL          | 1         | 1      | 0.26%   |
| OWC                 | 1         | 1      | 0.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 415       | 1718   | 43.41%  |
| SSD     | 336       | 567    | 35.15%  |
| NVMe    | 167       | 241    | 17.47%  |
| MMC     | 20        | 23     | 2.09%   |
| Unknown | 18        | 356    | 1.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 596       | 1878   | 71.72%  |
| NVMe | 167       | 240    | 20.1%   |
| SAS  | 48        | 764    | 5.78%   |
| MMC  | 20        | 23     | 2.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 407       | 804    | 48.57%  |
| 0.51-1.0   | 237       | 446    | 28.28%  |
| 1.01-2.0   | 82        | 213    | 9.79%   |
| 3.01-4.0   | 38        | 283    | 4.53%   |
| 4.01-10.0  | 35        | 312    | 4.18%   |
| 2.01-3.0   | 24        | 88     | 2.86%   |
| 10.01-20.0 | 15        | 139    | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 161       | 21.44%  |
| 251-500        | 158       | 21.04%  |
| 501-1000       | 123       | 16.38%  |
| More than 3000 | 94        | 12.52%  |
| 1001-2000      | 76        | 10.12%  |
| 51-100         | 41        | 5.46%   |
| Unknown        | 28        | 3.73%   |
| 21-50          | 26        | 3.46%   |
| 2001-3000      | 24        | 3.2%    |
| 1-20           | 20        | 2.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 270       | 35.29%  |
| 21-50          | 103       | 13.46%  |
| 101-250        | 99        | 12.94%  |
| 51-100         | 85        | 11.11%  |
| 251-500        | 56        | 7.32%   |
| 501-1000       | 45        | 5.88%   |
| More than 3000 | 41        | 5.36%   |
| 1001-2000      | 28        | 3.66%   |
| Unknown        | 28        | 3.66%   |
| 2001-3000      | 9         | 1.18%   |
| 0              | 1         | 0.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 4         | 4      | 3.42%   |
| Seagate ST2000DM001-9YN164 2TB        | 3         | 3      | 2.56%   |
| WDC WD20EFRX-68EUZN0 2TB              | 2         | 5      | 1.71%   |
| WDC WD1001FALS-00J7B1 1TB             | 2         | 2      | 1.71%   |
| Toshiba MQ01ABD100 1TB                | 2         | 5      | 1.71%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 1      | 0.85%   |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1      | 0.85%   |
| WDC WD6400AADS-00M2B0 640GB           | 1         | 1      | 0.85%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 0.85%   |
| WDC WD5000LPLX-60ZNTT1 500GB          | 1         | 1      | 0.85%   |
| WDC WD5000AVCS-632DY1 500GB           | 1         | 1      | 0.85%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 1         | 1      | 0.85%   |
| WDC WD5000AACS-00G8B0 500GB           | 1         | 1      | 0.85%   |
| WDC WD3200AVVS-63L2B0 320GB           | 1         | 1      | 0.85%   |
| WDC WD3200AAKS-75L9A0 320GB           | 1         | 1      | 0.85%   |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 3      | 0.85%   |
| WDC WD2500YS-18SHB2 250GB             | 1         | 1      | 0.85%   |
| WDC WD2500HHTZ-04N21V0 250GB          | 1         | 1      | 0.85%   |
| WDC WD20PURX-64PFUY0 2TB              | 1         | 1      | 0.85%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1         | 1      | 0.85%   |
| WDC WD20EARX-00PASB0 2TB              | 1         | 1      | 0.85%   |
| WDC WD20EARS-00MVWB0 2TB              | 1         | 2      | 0.85%   |
| WDC WD10SPZX-21Z10T0 1TB              | 1         | 2      | 0.85%   |
| WDC WD10PURX-64E5EY0 1TB              | 1         | 1      | 0.85%   |
| WDC WD10JPCX-24UE4T0 1TB              | 1         | 1      | 0.85%   |
| WDC WD10EZEX-60WN4A1 1TB              | 1         | 1      | 0.85%   |
| WDC WD10EZEX-60M2NA0 1TB              | 1         | 1      | 0.85%   |
| WDC WD10EADS-00L5B1 1TB               | 1         | 1      | 0.85%   |
| WDC WD1003FBYX-01Y7B0 1TB             | 1         | 1      | 0.85%   |
| WDC WD1002FBYS-18A6B0 1TB             | 1         | 1      | 0.85%   |
| WDC WD1002FAEX-00Y9A0 1TB             | 1         | 1      | 0.85%   |
| WDC RFT030VQFF-KRM5P7 3TB             | 1         | 1      | 0.85%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD  | 1         | 1      | 0.85%   |
| Toshiba MQ04ABF100 1TB                | 1         | 1      | 0.85%   |
| Toshiba MK8032GSX 80GB                | 1         | 1      | 0.85%   |
| Toshiba MK2561GSYN 250GB              | 1         | 1      | 0.85%   |
| Toshiba MK2552GSX 250GB               | 1         | 1      | 0.85%   |
| Smartbuy SSD 120GB                    | 1         | 1      | 0.85%   |
| SK hynix SC210 mSATA 256GB SSD        | 1         | 1      | 0.85%   |
| SK hynix HFS128G32TND-N210A 128GB SSD | 1         | 1      | 0.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 46     | 26.13%  |
| WDC                 | 26        | 38     | 23.42%  |
| Hitachi             | 12        | 12     | 10.81%  |
| Intel               | 11        | 31     | 9.91%   |
| Toshiba             | 7         | 10     | 6.31%   |
| Samsung Electronics | 5         | 7      | 4.5%    |
| SanDisk             | 3         | 3      | 2.7%    |
| Kingston            | 3         | 3      | 2.7%    |
| SK hynix            | 2         | 2      | 1.8%    |
| Micron Technology   | 2         | 2      | 1.8%    |
| LITEONIT            | 2         | 2      | 1.8%    |
| HGST                | 2         | 3      | 1.8%    |
| Crucial             | 2         | 2      | 1.8%    |
| Smartbuy            | 1         | 1      | 0.9%    |
| Maxtor              | 1         | 1      | 0.9%    |
| LITEON              | 1         | 1      | 0.9%    |
| Hewlett-Packard     | 1         | 1      | 0.9%    |
| A-DATA Technology   | 1         | 1      | 0.9%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 29        | 46     | 37.66%  |
| WDC                 | 24        | 36     | 31.17%  |
| Hitachi             | 12        | 12     | 15.58%  |
| Toshiba             | 6         | 9      | 7.79%   |
| Samsung Electronics | 2         | 2      | 2.6%    |
| HGST                | 2         | 3      | 2.6%    |
| Maxtor              | 1         | 1      | 1.3%    |
| Hewlett-Packard     | 1         | 1      | 1.3%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 69        | 110    | 66.99%  |
| SSD  | 34        | 56     | 33.01%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-00A0RT0 500GB | 1         | 1      | 50%     |
| Toshiba DT01ACA100 1TB       | 1         | 2      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Toshiba | 1         | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 408       | 1458   | 50.37%  |
| Detected | 301       | 1278   | 37.16%  |
| Malfunc  | 99        | 166    | 12.22%  |
| Failed   | 2         | 3      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 579       | 55.78%  |
| AMD                              | 105       | 10.12%  |
| Samsung Electronics              | 68        | 6.55%   |
| LSI Logic / Symbios Logic        | 54        | 5.2%    |
| Broadcom / LSI                   | 38        | 3.66%   |
| ASMedia Technology               | 30        | 2.89%   |
| SanDisk                          | 25        | 2.41%   |
| Marvell Technology Group         | 16        | 1.54%   |
| JMicron Technology               | 12        | 1.16%   |
| Micron Technology                | 11        | 1.06%   |
| Phison Electronics               | 10        | 0.96%   |
| Toshiba America Info Systems     | 8         | 0.77%   |
| Hewlett-Packard                  | 8         | 0.77%   |
| Silicon Motion                   | 7         | 0.67%   |
| Kingston Technology Company      | 7         | 0.67%   |
| Adaptec                          | 7         | 0.67%   |
| SK hynix                         | 6         | 0.58%   |
| Micron/Crucial Technology        | 6         | 0.58%   |
| ADATA Technology                 | 6         | 0.58%   |
| Union Memory (Shenzhen)          | 4         | 0.39%   |
| Nvidia                           | 4         | 0.39%   |
| KIOXIA                           | 4         | 0.39%   |
| Silicon Image                    | 3         | 0.29%   |
| Dell                             | 3         | 0.29%   |
| 3ware                            | 3         | 0.29%   |
| Seagate Technology               | 2         | 0.19%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.19%   |
| VIA Technologies                 | 1         | 0.1%    |
| Solid State Storage Technology   | 1         | 0.1%    |
| Silicon Integrated Systems [SiS] | 1         | 0.1%    |
| Shenzhen Longsys Electronics     | 1         | 0.1%    |
| Realtek Semiconductor            | 1         | 0.1%    |
| Lite-On Technology               | 1         | 0.1%    |
| Lenovo                           | 1         | 0.1%    |
| Integrated Technology Express    | 1         | 0.1%    |
| Huawei Technologies              | 1         | 0.1%    |
| Apple                            | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 68        | 5.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 44        | 3.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 36        | 2.92%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 36        | 2.92%   |
| Intel SATA Controller [RAID mode]                                              | 34        | 2.76%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 34        | 2.76%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 33        | 2.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 26        | 2.11%   |
| LSI Logic / Symbios Logic MegaRAID SAS-3 3108 [Invader]                        | 23        | 1.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 22        | 1.79%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 22        | 1.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 21        | 1.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 19        | 1.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 18        | 1.46%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 17        | 1.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 17        | 1.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 17        | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 17        | 1.38%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 16        | 1.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 16        | 1.3%    |
| Intel Comet Lake SATA AHCI Controller                                          | 15        | 1.22%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 15        | 1.22%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 14        | 1.14%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 13        | 1.06%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 13        | 1.06%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                     | 13        | 1.06%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 13        | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 13        | 1.06%   |
| AMD 400 Series Chipset SATA Controller                                         | 12        | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 11        | 0.89%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                     | 11        | 0.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 11        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 11        | 0.89%   |
| Intel 631xESB/632xESB IDE Controller                                           | 10        | 0.81%   |
| Broadcom / LSI MegaRAID SAS-3 3108 [Invader]                                   | 10        | 0.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 9         | 0.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 9         | 0.73%   |
| LSI Logic / Symbios Logic SAS2008 PCI-Express Fusion-MPT SAS-2 [Falcon]        | 8         | 0.65%   |
| Intel C600/X79 series chipset SATA RAID Controller                             | 8         | 0.65%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 8         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 546       | 53.42%  |
| NVMe | 167       | 16.34%  |
| RAID | 159       | 15.56%  |
| IDE  | 110       | 10.76%  |
| SAS  | 27        | 2.64%   |
| SCSI | 13        | 1.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor    | Computers | Percent |
|-----------|-----------|---------|
| Intel     | 624       | 85.25%  |
| AMD       | 107       | 14.62%  |
| Hisilicon | 1         | 0.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Xeon CPU E5-2630 v4 @ 2.20GHz     | 20        | 2.73%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 13        | 1.77%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 9         | 1.23%   |
| Intel Xeon CPU E5620 @ 2.40GHz          | 7         | 0.95%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 7         | 0.95%   |
| Intel Xeon CPU X5650 @ 2.67GHz          | 6         | 0.82%   |
| Intel Xeon CPU E5-2620 v4 @ 2.10GHz     | 6         | 0.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 6         | 0.82%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 6         | 0.82%   |
| AMD Ryzen 5 3600 6-Core Processor       | 6         | 0.82%   |
| AMD FX-6300 Six-Core Processor          | 6         | 0.82%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 5         | 0.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 5         | 0.68%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 5         | 0.68%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 5         | 0.68%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 5         | 0.68%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 5         | 0.68%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 5         | 0.68%   |
| Intel Core i5-10500 CPU @ 3.10GHz       | 5         | 0.68%   |
| Intel Core i3-2330M CPU @ 2.20GHz       | 5         | 0.68%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 0.68%   |
| AMD Ryzen 9 3900X 12-Core Processor     | 5         | 0.68%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 5         | 0.68%   |
| Intel Xeon Silver 4214 CPU @ 2.20GHz    | 4         | 0.55%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 0.55%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 4         | 0.55%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 4         | 0.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 4         | 0.55%   |
| Intel Core i3-6100U CPU @ 2.30GHz       | 4         | 0.55%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz   | 4         | 0.55%   |
| AMD EPYC 7702 64-Core Processor         | 4         | 0.55%   |
| Intel Xeon E-2136 CPU @ 3.30GHz         | 3         | 0.41%   |
| Intel Xeon CPU E5430 @ 2.66GHz          | 3         | 0.41%   |
| Intel Xeon CPU E5-2650 v3 @ 2.30GHz     | 3         | 0.41%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz     | 3         | 0.41%   |
| Intel Xeon CPU E31270 @ 3.40GHz         | 3         | 0.41%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 3         | 0.41%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 3         | 0.41%   |
| Intel Core i7-8700 CPU @ 3.20GHz        | 3         | 0.41%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 3         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 145       | 19.78%  |
| Intel Core i5           | 144       | 19.65%  |
| Intel Xeon              | 138       | 18.83%  |
| Intel Core i3           | 54        | 7.37%   |
| Other                   | 29        | 3.96%   |
| AMD Ryzen 5             | 22        | 3%      |
| Intel Core 2 Duo        | 21        | 2.86%   |
| Intel Pentium           | 17        | 2.32%   |
| Intel Celeron           | 17        | 2.32%   |
| AMD FX                  | 17        | 2.32%   |
| AMD Ryzen 7             | 14        | 1.91%   |
| Intel Core 2 Quad       | 11        | 1.5%    |
| Intel Xeon Silver       | 10        | 1.36%   |
| Intel Atom              | 10        | 1.36%   |
| AMD Ryzen 9             | 10        | 1.36%   |
| Intel Core i9           | 8         | 1.09%   |
| AMD EPYC                | 7         | 0.95%   |
| Intel Xeon Gold         | 6         | 0.82%   |
| AMD Ryzen 3             | 6         | 0.82%   |
| Intel Pentium Dual-Core | 5         | 0.68%   |
| Intel Genuine           | 5         | 0.68%   |
| AMD Ryzen Threadripper  | 4         | 0.55%   |
| AMD Opteron             | 4         | 0.55%   |
| AMD Ryzen 7 PRO         | 3         | 0.41%   |
| Intel Xeon Platinum     | 2         | 0.27%   |
| Intel Pentium Dual      | 2         | 0.27%   |
| AMD Turion II Neo       | 2         | 0.27%   |
| AMD Phenom II X6        | 2         | 0.27%   |
| AMD G                   | 2         | 0.27%   |
| AMD A8                  | 2         | 0.27%   |
| AMD A4                  | 2         | 0.27%   |
| AMD A10                 | 2         | 0.27%   |
| Intel Xeon Bronze       | 1         | 0.14%   |
| Intel Pentium Gold      | 1         | 0.14%   |
| Intel Pentium 4         | 1         | 0.14%   |
| AMD Ryzen 5 PRO         | 1         | 0.14%   |
| AMD Ryzen 3 PRO         | 1         | 0.14%   |
| AMD Phenom II X4        | 1         | 0.14%   |
| AMD GX                  | 1         | 0.14%   |
| AMD E2                  | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 262       | 35.74%  |
| 2      | 205       | 27.97%  |
| 6      | 77        | 10.5%   |
| 8      | 47        | 6.41%   |
| 12     | 36        | 4.91%   |
| 20     | 26        | 3.55%   |
| 16     | 23        | 3.14%   |
| 24     | 9         | 1.23%   |
| 10     | 8         | 1.09%   |
| 3      | 8         | 1.09%   |
| 1      | 8         | 1.09%   |
| 64     | 6         | 0.82%   |
| 32     | 4         | 0.55%   |
| 14     | 4         | 0.55%   |
| 96     | 3         | 0.41%   |
| 40     | 2         | 0.27%   |
| 52     | 1         | 0.14%   |
| 48     | 1         | 0.14%   |
| 36     | 1         | 0.14%   |
| 28     | 1         | 0.14%   |
| 18     | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 628       | 85.79%  |
| 2      | 103       | 14.07%  |
| 0      | 1         | 0.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 512       | 69.75%  |
| 1      | 222       | 30.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 708       | 96.59%  |
| Unknown        | 21        | 2.86%   |
| 32-bit         | 4         | 0.55%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 72        | 9.7%    |
| 0x306c3    | 56        | 7.55%   |
| 0x306a9    | 45        | 6.06%   |
| 0x206a7    | 45        | 6.06%   |
| 0x506e3    | 31        | 4.18%   |
| 0x406f1    | 26        | 3.5%    |
| 0x906ea    | 25        | 3.37%   |
| 0x40651    | 21        | 2.83%   |
| 0x1067a    | 20        | 2.7%    |
| 0x206c2    | 18        | 2.43%   |
| 0x906e9    | 17        | 2.29%   |
| 0x406e3    | 17        | 2.29%   |
| 0x806ea    | 16        | 2.16%   |
| 0x306f2    | 16        | 2.16%   |
| 0x06000852 | 14        | 1.89%   |
| 0x806ec    | 12        | 1.62%   |
| 0x306d4    | 12        | 1.62%   |
| 0x10676    | 12        | 1.62%   |
| 0x08701021 | 12        | 1.62%   |
| 0x206d7    | 11        | 1.48%   |
| 0xa0655    | 10        | 1.35%   |
| 0xa0653    | 10        | 1.35%   |
| 0x20655    | 10        | 1.35%   |
| 0x106e5    | 10        | 1.35%   |
| 0x806e9    | 9         | 1.21%   |
| 0x806c1    | 9         | 1.21%   |
| 0x50654    | 9         | 1.21%   |
| 0x106a5    | 8         | 1.08%   |
| 0x08701013 | 8         | 1.08%   |
| 0x0800820d | 8         | 1.08%   |
| 0x906a3    | 7         | 0.94%   |
| 0x6fb      | 7         | 0.94%   |
| 0x906ed    | 6         | 0.81%   |
| 0x50657    | 6         | 0.81%   |
| 0xa0652    | 5         | 0.67%   |
| 0x706e5    | 5         | 0.67%   |
| 0x6fd      | 5         | 0.67%   |
| 0x406c4    | 5         | 0.67%   |
| 0x306e4    | 5         | 0.67%   |
| 0x606a6    | 4         | 0.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 94        | 12.82%  |
| KabyLake         | 93        | 12.69%  |
| Skylake          | 73        | 9.96%   |
| SandyBridge      | 62        | 8.46%   |
| IvyBridge        | 53        | 7.23%   |
| Broadwell        | 47        | 6.41%   |
| Zen 2            | 40        | 5.46%   |
| Penryn           | 40        | 5.46%   |
| Westmere         | 36        | 4.91%   |
| CometLake        | 27        | 3.68%   |
| Piledriver       | 20        | 2.73%   |
| Nehalem          | 19        | 2.59%   |
| Zen+             | 13        | 1.77%   |
| Core             | 13        | 1.77%   |
| Zen              | 12        | 1.64%   |
| Silvermont       | 12        | 1.64%   |
| TigerLake        | 11        | 1.5%    |
| Alderlake Hybrid | 10        | 1.36%   |
| IceLake          | 8         | 1.09%   |
| Unknown          | 8         | 1.09%   |
| K10              | 6         | 0.82%   |
| Bonnell          | 6         | 0.82%   |
| Zen 3            | 4         | 0.55%   |
| Excavator        | 4         | 0.55%   |
| NetBurst         | 3         | 0.41%   |
| K10 Llano        | 3         | 0.41%   |
| Goldmont plus    | 3         | 0.41%   |
| Sapphire Rapids  | 2         | 0.27%   |
| P6               | 2         | 0.27%   |
| Jaguar           | 2         | 0.27%   |
| Goldmont         | 2         | 0.27%   |
| Bobcat           | 2         | 0.27%   |
| Tremont          | 1         | 0.14%   |
| K8 Hammer        | 1         | 0.14%   |
| Bulldozer        | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 369       | 44.03%  |
| Nvidia                                       | 210       | 25.06%  |
| AMD                                          | 145       | 17.3%   |
| Matrox Electronics Systems                   | 54        | 6.44%   |
| ASPEED Technology                            | 53        | 6.32%   |
| XGI Technology (eXtreme Graphics Innovation) | 2         | 0.24%   |
| S3 Graphics                                  | 2         | 0.24%   |
| Silicon Motion                               | 1         | 0.12%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.12%   |
| Huawei Technologies                          | 1         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| ASPEED Technology ASPEED Graphics Family                                                 | 53        | 6.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 35        | 4.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 23        | 2.7%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 2.58%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 2.35%   |
| Matrox Electronics Systems G200eR2                                                       | 18        | 2.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 18        | 2.11%   |
| Intel HD Graphics 530                                                                    | 17        | 2%      |
| Intel UHD Graphics 620                                                                   | 15        | 1.76%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 14        | 1.64%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 14        | 1.64%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 13        | 1.53%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 13        | 1.53%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 13        | 1.53%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 13        | 1.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 1.29%   |
| Intel HD Graphics 630                                                                    | 11        | 1.29%   |
| Intel HD Graphics 5500                                                                   | 11        | 1.29%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 1.29%   |
| AMD ES1000                                                                               | 11        | 1.29%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 1.17%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 10        | 1.17%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 1.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.06%   |
| Intel HD Graphics 620                                                                    | 8         | 0.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 0.94%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]                        | 8         | 0.94%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 7         | 0.82%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]                    | 7         | 0.82%   |
| Nvidia GT218 [GeForce 210]                                                               | 6         | 0.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 0.7%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 0.7%    |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller                 | 5         | 0.59%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 5         | 0.59%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 5         | 0.59%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.47%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 4         | 0.47%   |
| Nvidia GP107GL [Quadro P400]                                                             | 4         | 0.47%   |
| Nvidia GP106GL [Quadro P2000]                                                            | 4         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 275       | 37.41%  |
| 1 x Nvidia              | 136       | 18.5%   |
| 1 x AMD                 | 116       | 15.78%  |
| Intel + Nvidia          | 61        | 8.3%    |
| 1 x Matrox              | 52        | 7.07%   |
| 1 x ASPEED              | 48        | 6.53%   |
| Intel + AMD             | 21        | 2.86%   |
| 2 x Nvidia              | 3         | 0.41%   |
| 2 x AMD                 | 3         | 0.41%   |
| AMD + Nvidia            | 3         | 0.41%   |
| Other                   | 2         | 0.27%   |
| 1 x XGI                 | 2         | 0.27%   |
| 1 x S3 Graphics         | 2         | 0.27%   |
| Nvidia + Matrox         | 2         | 0.27%   |
| Nvidia + ASPEED         | 2         | 0.27%   |
| 3 x Nvidia + 1 x ASPEED | 1         | 0.14%   |
| 2 x AMD + 1 x ASPEED    | 1         | 0.14%   |
| 1 x SiS                 | 1         | 0.14%   |
| 1 x Silicon Motion      | 1         | 0.14%   |
| Intel + 2 x Nvidia      | 1         | 0.14%   |
| 1 x Huawei Technologies | 1         | 0.14%   |
| AMD + ASPEED            | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 577       | 77.76%  |
| Unknown     | 84        | 11.32%  |
| Proprietary | 81        | 10.92%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 435       | 58.39%  |
| 1.01-2.0   | 94        | 12.62%  |
| 0.51-1.0   | 66        | 8.86%   |
| 0.01-0.5   | 55        | 7.38%   |
| 3.01-4.0   | 42        | 5.64%   |
| 7.01-8.0   | 29        | 3.89%   |
| 5.01-6.0   | 9         | 1.21%   |
| 8.01-16.0  | 6         | 0.81%   |
| 4.01-5.0   | 4         | 0.54%   |
| 2.01-3.0   | 4         | 0.54%   |
| 16.01-24.0 | 1         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 98        | 14.83%  |
| Samsung Electronics     | 86        | 13.01%  |
| AU Optronics            | 48        | 7.26%   |
| Hewlett-Packard         | 44        | 6.66%   |
| LG Display              | 43        | 6.51%   |
| Goldstar                | 41        | 6.2%    |
| Chimei Innolux          | 41        | 6.2%    |
| Acer                    | 30        | 4.54%   |
| BOE                     | 26        | 3.93%   |
| AOC                     | 18        | 2.72%   |
| BenQ                    | 17        | 2.57%   |
| Philips                 | 14        | 2.12%   |
| Lenovo                  | 14        | 2.12%   |
| ViewSonic               | 13        | 1.97%   |
| Ancor Communications    | 13        | 1.97%   |
| Eizo                    | 8         | 1.21%   |
| LG Electronics          | 7         | 1.06%   |
| Iiyama                  | 7         | 1.06%   |
| Sharp                   | 5         | 0.76%   |
| PANDA                   | 5         | 0.76%   |
| Unknown                 | 4         | 0.61%   |
| Sony                    | 4         | 0.61%   |
| Panasonic               | 4         | 0.61%   |
| NEC Computers           | 4         | 0.61%   |
| Apple                   | 4         | 0.61%   |
| Xiaomi                  | 3         | 0.45%   |
| HPN                     | 3         | 0.45%   |
| HannStar                | 3         | 0.45%   |
| ASUSTek Computer        | 3         | 0.45%   |
| ___                     | 2         | 0.3%    |
| Westinghouse            | 2         | 0.3%    |
| Sun                     | 2         | 0.3%    |
| Sceptre Tech            | 2         | 0.3%    |
| MStar                   | 2         | 0.3%    |
| KVM                     | 2         | 0.3%    |
| Insignia                | 2         | 0.3%    |
| InnoLux Display         | 2         | 0.3%    |
| Elo Touch               | 2         | 0.3%    |
| Chi Mei Optoelectronics | 2         | 0.3%    |
| Xerox                   | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Dell P2414H DELA09A 1920x1080 527x297mm 23.8-inch                    | 7         | 0.99%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                    | 7         | 0.99%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                    | 6         | 0.85%   |
| AOC 2436 AOC2436 1920x1080 521x293mm 23.5-inch                       | 5         | 0.7%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 4         | 0.56%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 4         | 0.56%   |
| Xiaomi DPF90435 XMD009A 2224x1668 341x192mm 15.4-inch                | 3         | 0.42%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 3         | 0.42%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch          | 3         | 0.42%   |
| Goldstar Ultra HD GSM5B08 3840x2160 600x340mm 27.2-inch              | 3         | 0.42%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch          | 3         | 0.42%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 3         | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 3         | 0.42%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 3         | 0.42%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 459x296mm 21.5-inch | 2         | 0.28%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch | 2         | 0.28%   |
| Samsung Electronics SyncMaster SAM01D3 1440x900 408x225mm 18.3-inch  | 2         | 0.28%   |
| Samsung Electronics SyncMaster SAM0094 1280x1024 338x270mm 17.0-inch | 2         | 0.28%   |
| Samsung Electronics SMT22A550 SAM07AF 1920x1080 477x268mm 21.5-inch  | 2         | 0.28%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch    | 2         | 0.28%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch     | 2         | 0.28%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 2         | 0.28%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                     | 2         | 0.28%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 2         | 0.28%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 2         | 0.28%   |
| LG Display LCD Monitor LGD021D 1600x900 382x215mm 17.3-inch          | 2         | 0.28%   |
| KVM LCD Monitor 1 1 9" KVM4308 1280x1024 338x270mm 17.0-inch         | 2         | 0.28%   |
| InnoLux Display LCD Monitor INL0014 1366x768 309x174mm 14.0-inch     | 2         | 0.28%   |
| Iiyama PL2888H IVM7106 1920x1080 621x341mm 27.9-inch                 | 2         | 0.28%   |
| Hewlett-Packard ZR2440w HWP2956 1920x1200 518x324mm 24.1-inch        | 2         | 0.28%   |
| Hewlett-Packard ZR2440w HWP2955 1920x1200 520x320mm 24.0-inch        | 2         | 0.28%   |
| Hewlett-Packard Z32x HWP3275 3840x2160 697x392mm 31.5-inch           | 2         | 0.28%   |
| Hewlett-Packard V19b HPN3539 1366x768 410x230mm 18.5-inch            | 2         | 0.28%   |
| Hewlett-Packard LP2465 HWP2676 1920x1200 519x324mm 24.1-inch         | 2         | 0.28%   |
| Hewlett-Packard LE1901w HWP2842 1440x900 410x256mm 19.0-inch         | 2         | 0.28%   |
| Hewlett-Packard 2159 HWP282C 1920x1080 479x269mm 21.6-inch           | 2         | 0.28%   |
| Goldstar W2252 GSM567D 1680x1050 474x296mm 22.0-inch                 | 2         | 0.28%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 2         | 0.28%   |
| Goldstar L1753T GSM4476 1280x1024 338x270mm 17.0-inch                | 2         | 0.28%   |
| Goldstar IPS FULLHD GSM5AB7 1920x1080 480x270mm 21.7-inch            | 2         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 276       | 43.19%  |
| 1366x768 (WXGA)    | 84        | 13.15%  |
| 3840x2160 (4K)     | 46        | 7.2%    |
| 1280x1024 (SXGA)   | 34        | 5.32%   |
| 1680x1050 (WSXGA+) | 26        | 4.07%   |
| 1600x900 (HD+)     | 26        | 4.07%   |
| 1920x1200 (WUXGA)  | 24        | 3.76%   |
| 2560x1440 (QHD)    | 23        | 3.6%    |
| Unknown            | 18        | 2.82%   |
| 1440x900 (WXGA+)   | 14        | 2.19%   |
| 1280x800 (WXGA)    | 10        | 1.56%   |
| 3440x1440          | 8         | 1.25%   |
| 3840x1080          | 7         | 1.1%    |
| 1600x1200          | 7         | 1.1%    |
| 1024x768 (XGA)     | 7         | 1.1%    |
| 2560x1080          | 4         | 0.63%   |
| 3840x1200          | 3         | 0.47%   |
| 2560x1600          | 3         | 0.47%   |
| 1360x768           | 3         | 0.47%   |
| 1280x960           | 2         | 0.31%   |
| 1280x720 (HD)      | 2         | 0.31%   |
| 7680x1080          | 1         | 0.16%   |
| 7280x2160          | 1         | 0.16%   |
| 5760x1080          | 1         | 0.16%   |
| 5520x2160          | 1         | 0.16%   |
| 4480x1440          | 1         | 0.16%   |
| 3640x1920          | 1         | 0.16%   |
| 3456x2160          | 1         | 0.16%   |
| 3200x2000          | 1         | 0.16%   |
| 1920x540           | 1         | 0.16%   |
| 1680x1080          | 1         | 0.16%   |
| 1400x1050          | 1         | 0.16%   |
| 1024x600           | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 113       | 17.02%  |
| 24      | 77        | 11.6%   |
| 21      | 62        | 9.34%   |
| 27      | 61        | 9.19%   |
| 23      | 57        | 8.58%   |
| Unknown | 43        | 6.48%   |
| 17      | 38        | 5.72%   |
| 14      | 36        | 5.42%   |
| 13      | 29        | 4.37%   |
| 19      | 26        | 3.92%   |
| 22      | 15        | 2.26%   |
| 20      | 15        | 2.26%   |
| 18      | 15        | 2.26%   |
| 12      | 13        | 1.96%   |
| 31      | 11        | 1.66%   |
| 34      | 9         | 1.36%   |
| 32      | 6         | 0.9%    |
| 40      | 4         | 0.6%    |
| 25      | 4         | 0.6%    |
| 16      | 4         | 0.6%    |
| 52      | 3         | 0.45%   |
| 26      | 3         | 0.45%   |
| 84      | 2         | 0.3%    |
| 72      | 2         | 0.3%    |
| 65      | 2         | 0.3%    |
| 42      | 2         | 0.3%    |
| 29      | 2         | 0.3%    |
| 11      | 2         | 0.3%    |
| 58      | 1         | 0.15%   |
| 55      | 1         | 0.15%   |
| 49      | 1         | 0.15%   |
| 46      | 1         | 0.15%   |
| 38      | 1         | 0.15%   |
| 36      | 1         | 0.15%   |
| 28      | 1         | 0.15%   |
| 10      | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 183       | 28.46%  |
| 501-600     | 175       | 27.22%  |
| 401-500     | 113       | 17.57%  |
| 351-400     | 44        | 6.84%   |
| Unknown     | 43        | 6.69%   |
| 601-700     | 26        | 4.04%   |
| 201-300     | 23        | 3.58%   |
| 701-800     | 16        | 2.49%   |
| 1001-1500   | 9         | 1.4%    |
| 801-900     | 5         | 0.78%   |
| 1501-2000   | 4         | 0.62%   |
| 901-1000    | 2         | 0.31%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 411       | 69.78%  |
| 16/10   | 76        | 12.9%   |
| Unknown | 38        | 6.45%   |
| 5/4     | 34        | 5.77%   |
| 4/3     | 16        | 2.72%   |
| 21/9    | 9         | 1.53%   |
| 3/2     | 4         | 0.68%   |
| 32/9    | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 164       | 25.08%  |
| 101-110        | 111       | 16.97%  |
| 301-350        | 62        | 9.48%   |
| 81-90          | 60        | 9.17%   |
| 151-200        | 54        | 8.26%   |
| Unknown        | 43        | 6.57%   |
| 251-300        | 33        | 5.05%   |
| 141-150        | 30        | 4.59%   |
| 351-500        | 29        | 4.43%   |
| 121-130        | 18        | 2.75%   |
| 61-70          | 13        | 1.99%   |
| More than 1000 | 12        | 1.83%   |
| 501-1000       | 9         | 1.38%   |
| 71-80          | 5         | 0.76%   |
| 111-120        | 4         | 0.61%   |
| 131-140        | 3         | 0.46%   |
| 51-60          | 2         | 0.31%   |
| 41-50          | 1         | 0.15%   |
| 91-100         | 1         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 276       | 43.74%  |
| 101-120       | 145       | 22.98%  |
| 121-160       | 134       | 21.24%  |
| Unknown       | 43        | 6.81%   |
| 161-240       | 15        | 2.38%   |
| 1-50          | 10        | 1.58%   |
| More than 240 | 8         | 1.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 462       | 61.27%  |
| 0     | 170       | 22.55%  |
| 2     | 106       | 14.06%  |
| 3     | 11        | 1.46%   |
| 4     | 4         | 0.53%   |
| 6     | 1         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 454       | 43.03%  |
| Realtek Semiconductor             | 290       | 27.49%  |
| Qualcomm Atheros                  | 78        | 7.39%   |
| Broadcom                          | 75        | 7.11%   |
| Ralink Technology                 | 17        | 1.61%   |
| IBM                               | 15        | 1.42%   |
| Broadcom Limited                  | 14        | 1.33%   |
| TP-Link                           | 13        | 1.23%   |
| Mellanox Technologies             | 13        | 1.23%   |
| ASIX Electronics                  | 8         | 0.76%   |
| Aquantia                          | 6         | 0.57%   |
| D-Link System                     | 5         | 0.47%   |
| Ralink                            | 4         | 0.38%   |
| Marvell Technology Group          | 4         | 0.38%   |
| D-Link                            | 4         | 0.38%   |
| Xiaomi                            | 3         | 0.28%   |
| Samsung Electronics               | 3         | 0.28%   |
| Huawei Technologies               | 3         | 0.28%   |
| Ericsson Business Mobile Networks | 3         | 0.28%   |
| DisplayLink                       | 3         | 0.28%   |
| Dell                              | 3         | 0.28%   |
| Xilinx                            | 2         | 0.19%   |
| Sierra Wireless                   | 2         | 0.19%   |
| Nvidia                            | 2         | 0.19%   |
| MediaTek                          | 2         | 0.19%   |
| ICS Advent                        | 2         | 0.19%   |
| Emulex                            | 2         | 0.19%   |
| ASUSTek Computer                  | 2         | 0.19%   |
| 3Com                              | 2         | 0.19%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.09%   |
| VIA Technologies                  | 1         | 0.09%   |
| U-Blox                            | 1         | 0.09%   |
| Spreadtrum Communications         | 1         | 0.09%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.09%   |
| Qualcomm Atheros Communications   | 1         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.09%   |
| NetGear                           | 1         | 0.09%   |
| MYRICOM                           | 1         | 0.09%   |
| LSI                               | 1         | 0.09%   |
| Linux 2.6.31.6 with s3c-udc       | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 219       | 16.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 38        | 2.93%   |
| Intel I350 Gigabit Network Connection                             | 31        | 2.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 2.23%   |
| Intel Ethernet Connection I217-LM                                 | 29        | 2.23%   |
| Intel I211 Gigabit Network Connection                             | 25        | 1.93%   |
| Intel Wireless 7260                                               | 24        | 1.85%   |
| Intel Wi-Fi 6 AX200                                               | 23        | 1.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 1.77%   |
| Intel 82574L Gigabit Network Connection                           | 22        | 1.69%   |
| Intel I210 Gigabit Network Connection                             | 21        | 1.62%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 18        | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 15        | 1.16%   |
| Intel Wireless 8260                                               | 15        | 1.16%   |
| IBM RNDIS/Ethernet Gadget                                         | 15        | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 1.08%   |
| Intel Wireless 8265 / 8275                                        | 13        | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 13        | 1%      |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 13        | 1%      |
| Intel Ethernet Connection (7) I219-LM                             | 12        | 0.92%   |
| Intel Ethernet Connection (11) I219-LM                            | 12        | 0.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 11        | 0.85%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 11        | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 11        | 0.85%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 0.77%   |
| Intel Wireless 7265                                               | 10        | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 0.69%   |
| Intel 82576 Gigabit Network Connection                            | 9         | 0.69%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 7         | 0.54%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 7         | 0.54%   |
| Intel Wireless 3165                                               | 7         | 0.54%   |
| Intel Ethernet Controller I225-V                                  | 7         | 0.54%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.54%   |
| Intel Ethernet Connection (2) I218-V                              | 7         | 0.54%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 0.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 0.54%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 206       | 53.51%  |
| Qualcomm Atheros                | 59        | 15.32%  |
| Realtek Semiconductor           | 49        | 12.73%  |
| Broadcom                        | 20        | 5.19%   |
| Ralink Technology               | 17        | 4.42%   |
| TP-Link                         | 11        | 2.86%   |
| Ralink                          | 4         | 1.04%   |
| D-Link                          | 4         | 1.04%   |
| Sierra Wireless                 | 2         | 0.52%   |
| MediaTek                        | 2         | 0.52%   |
| Dell                            | 2         | 0.52%   |
| Broadcom Limited                | 2         | 0.52%   |
| ASUSTek Computer                | 2         | 0.52%   |
| Qualcomm Atheros Communications | 1         | 0.26%   |
| NetGear                         | 1         | 0.26%   |
| Linksys                         | 1         | 0.26%   |
| Edimax Technology               | 1         | 0.26%   |
| D-Link System                   | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                            | 24        | 6.22%   |
| Intel Wi-Fi 6 AX200                                            | 23        | 5.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 15        | 3.89%   |
| Intel Wireless 8260                                            | 15        | 3.89%   |
| Intel Wireless 8265 / 8275                                     | 13        | 3.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 11        | 2.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 11        | 2.85%   |
| Intel Wireless 7265                                            | 10        | 2.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 2.33%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 2.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 1.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 7         | 1.81%   |
| Intel Wireless 3165                                            | 7         | 1.81%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 1.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 7         | 1.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 1.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 1.55%   |
| Intel Wireless-AC 9260                                         | 6         | 1.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 1.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 1.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 5         | 1.3%    |
| Ralink MT7601U Wireless Adapter                                | 5         | 1.3%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 1.3%    |
| Intel Centrino Ultimate-N 6300                                 | 5         | 1.3%    |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 5         | 1.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.04%   |
| Ralink RT5370 Wireless Adapter                                 | 4         | 1.04%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 4         | 1.04%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 4         | 1.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 4         | 1.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.04%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 1.04%   |
| Intel Centrino Advanced-N 6200                                 | 4         | 1.04%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 0.78%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 3         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 357       | 44.46%  |
| Realtek Semiconductor            | 274       | 34.12%  |
| Broadcom                         | 58        | 7.22%   |
| Qualcomm Atheros                 | 27        | 3.36%   |
| IBM                              | 15        | 1.87%   |
| Broadcom Limited                 | 12        | 1.49%   |
| ASIX Electronics                 | 8         | 1%      |
| Aquantia                         | 6         | 0.75%   |
| Marvell Technology Group         | 4         | 0.5%    |
| D-Link System                    | 4         | 0.5%    |
| Xiaomi                           | 3         | 0.37%   |
| Samsung Electronics              | 3         | 0.37%   |
| Mellanox Technologies            | 3         | 0.37%   |
| Huawei Technologies              | 3         | 0.37%   |
| DisplayLink                      | 3         | 0.37%   |
| TP-Link                          | 2         | 0.25%   |
| Nvidia                           | 2         | 0.25%   |
| ICS Advent                       | 2         | 0.25%   |
| 3Com                             | 2         | 0.25%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.12%   |
| Xilinx                           | 1         | 0.12%   |
| VIA Technologies                 | 1         | 0.12%   |
| Spreadtrum Communications        | 1         | 0.12%   |
| Silicon Integrated Systems [SiS] | 1         | 0.12%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.12%   |
| MYRICOM                          | 1         | 0.12%   |
| Lenovo                           | 1         | 0.12%   |
| Emulex                           | 1         | 0.12%   |
| Dell                             | 1         | 0.12%   |
| Cisco Systems                    | 1         | 0.12%   |
| Ceton Technologies               | 1         | 0.12%   |
| Apple                            | 1         | 0.12%   |
| American Megatrends              | 1         | 0.12%   |
| Accton Technology                | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 219       | 24.58%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 38        | 4.26%   |
| Intel I350 Gigabit Network Connection                             | 31        | 3.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 29        | 3.25%   |
| Intel Ethernet Connection I217-LM                                 | 29        | 3.25%   |
| Intel I211 Gigabit Network Connection                             | 25        | 2.81%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 2.58%   |
| Intel 82574L Gigabit Network Connection                           | 22        | 2.47%   |
| Intel I210 Gigabit Network Connection                             | 21        | 2.36%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 18        | 2.02%   |
| IBM RNDIS/Ethernet Gadget                                         | 15        | 1.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 14        | 1.57%   |
| Intel Ethernet Connection (2) I219-V                              | 13        | 1.46%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 13        | 1.46%   |
| Intel Ethernet Connection (7) I219-LM                             | 12        | 1.35%   |
| Intel Ethernet Connection (11) I219-LM                            | 12        | 1.35%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 11        | 1.23%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 1.12%   |
| Intel 82576 Gigabit Network Connection                            | 9         | 1.01%   |
| Intel Ethernet Controller I225-V                                  | 7         | 0.79%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.79%   |
| Intel Ethernet Connection (2) I218-V                              | 7         | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 6         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 0.67%   |
| Intel Ethernet Controller 10-Gigabit X540-AT2                     | 6         | 0.67%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 0.67%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 0.67%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 6         | 0.67%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 6         | 0.67%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 0.67%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 5         | 0.56%   |
| Intel Ethernet Connection I219-V                                  | 5         | 0.56%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 0.56%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.56%   |
| Intel Ethernet Connection (5) I219-LM                             | 5         | 0.56%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 5         | 0.56%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 5         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 697       | 64.6%   |
| WiFi     | 361       | 33.46%  |
| Unknown  | 12        | 1.11%   |
| Modem    | 9         | 0.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 508       | 68.74%  |
| WiFi     | 227       | 30.72%  |
| Unknown  | 4         | 0.54%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 375       | 50.95%  |
| 1     | 241       | 32.74%  |
| 3     | 42        | 5.71%   |
| 4     | 39        | 5.3%    |
| 6     | 19        | 2.58%   |
| 5     | 6         | 0.82%   |
| 8     | 4         | 0.54%   |
| 0     | 4         | 0.54%   |
| 7     | 2         | 0.27%   |
| 42    | 1         | 0.14%   |
| 20    | 1         | 0.14%   |
| 12    | 1         | 0.14%   |
| 10    | 1         | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 665       | 90.23%  |
| Yes  | 72        | 9.77%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 155       | 52.54%  |
| Qualcomm Atheros Communications | 32        | 10.85%  |
| Realtek Semiconductor           | 28        | 9.49%   |
| Cambridge Silicon Radio         | 24        | 8.14%   |
| Broadcom                        | 21        | 7.12%   |
| ASUSTek Computer                | 8         | 2.71%   |
| Lite-On Technology              | 6         | 2.03%   |
| IMC Networks                    | 5         | 1.69%   |
| Apple                           | 4         | 1.36%   |
| Dell                            | 3         | 1.02%   |
| Hewlett-Packard                 | 2         | 0.68%   |
| Foxconn / Hon Hai               | 2         | 0.68%   |
| Toshiba                         | 1         | 0.34%   |
| Ralink                          | 1         | 0.34%   |
| MediaTek                        | 1         | 0.34%   |
| Dynex                           | 1         | 0.34%   |
| Alps Electric                   | 1         | 0.34%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 65        | 22.03%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 24        | 8.14%   |
| Intel AX200 Bluetooth                                                               | 21        | 7.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 6.1%    |
| Intel AX201 Bluetooth                                                               | 18        | 6.1%    |
| Realtek Bluetooth Radio                                                             | 16        | 5.42%   |
| Intel Bluetooth Device                                                              | 12        | 4.07%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 10        | 3.39%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 9         | 3.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 9         | 3.05%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 9         | 3.05%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 6         | 2.03%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 5         | 1.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 5         | 1.69%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 1.69%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 4         | 1.36%   |
| IMC Networks Bluetooth Device                                                       | 4         | 1.36%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.02%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 3         | 1.02%   |
| Apple Bluetooth Host Controller                                                     | 3         | 1.02%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.68%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.68%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.68%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.68%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.68%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 0.68%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.68%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 2         | 0.68%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                               | 2         | 0.68%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.34%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.34%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.34%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.34%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.34%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.34%   |
| MediaTek Wireless_Device                                                            | 1         | 0.34%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 1         | 0.34%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.34%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.34%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 477       | 56.45%  |
| Nvidia                           | 155       | 18.34%  |
| AMD                              | 147       | 17.4%   |
| Logitech                         | 9         | 1.07%   |
| C-Media Electronics              | 8         | 0.95%   |
| Texas Instruments                | 5         | 0.59%   |
| Plantronics                      | 5         | 0.59%   |
| GN Netcom                        | 5         | 0.59%   |
| Creative Labs                    | 5         | 0.59%   |
| SteelSeries ApS                  | 4         | 0.47%   |
| JMTek                            | 2         | 0.24%   |
| Creative Technology              | 2         | 0.24%   |
| Anlya.cn                         | 2         | 0.24%   |
| Tenx Technology                  | 1         | 0.12%   |
| Silicon Integrated Systems [SiS] | 1         | 0.12%   |
| SAVITECH                         | 1         | 0.12%   |
| Realtek Semiconductor            | 1         | 0.12%   |
| NEC Computers                    | 1         | 0.12%   |
| Musical Fidelity                 | 1         | 0.12%   |
| Micro Star International         | 1         | 0.12%   |
| Lynx                             | 1         | 0.12%   |
| Lenovo                           | 1         | 0.12%   |
| KTMicro                          | 1         | 0.12%   |
| Kingston Technology              | 1         | 0.12%   |
| Harman International             | 1         | 0.12%   |
| Fry's Electronics                | 1         | 0.12%   |
| Ensoniq                          | 1         | 0.12%   |
| Corsair                          | 1         | 0.12%   |
| Avid Technology                  | 1         | 0.12%   |
| ASUSTek Computer                 | 1         | 0.12%   |
| Asahi Kasei Microsystems         | 1         | 0.12%   |
| Apple                            | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 48        | 4.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 45        | 4.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 42        | 4.31%   |
| Intel Sunrise Point-LP HD Audio                                            | 40        | 4.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 34        | 3.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 31        | 3.18%   |
| AMD Starship/Matisse HD Audio Controller                                   | 26        | 2.67%   |
| Intel Cannon Lake PCH cAVS                                                 | 24        | 2.46%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 24        | 2.46%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 22        | 2.26%   |
| Intel 8 Series HD Audio Controller                                         | 21        | 2.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 21        | 2.15%   |
| Intel Haswell-ULT HD Audio Controller                                      | 20        | 2.05%   |
| AMD Family 17h/19h HD Audio Controller                                     | 19        | 1.95%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 18        | 1.85%   |
| Intel Comet Lake PCH cAVS                                                  | 17        | 1.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 17        | 1.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 16        | 1.64%   |
| Intel 200 Series PCH HD Audio                                              | 15        | 1.54%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 15        | 1.54%   |
| Nvidia GP107GL High Definition Audio Controller                            | 13        | 1.33%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 13        | 1.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13        | 1.33%   |
| Intel Broadwell-U Audio Controller                                         | 13        | 1.33%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 12        | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 11        | 1.13%   |
| Nvidia High Definition Audio Controller                                    | 11        | 1.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 1.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 1.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 1.13%   |
| Nvidia GK107 HDMI Audio Controller                                         | 10        | 1.03%   |
| Nvidia TU104 HD Audio Controller                                           | 9         | 0.92%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 0.92%   |
| Nvidia GP104 High Definition Audio Controller                              | 8         | 0.82%   |
| Nvidia GF119 HDMI Audio Controller                                         | 8         | 0.82%   |
| Nvidia GF108 High Definition Audio Controller                              | 8         | 0.82%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 8         | 0.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 0.82%   |
| Nvidia GP106 High Definition Audio Controller                              | 7         | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 126       | 21.84%  |
| SK hynix            | 111       | 19.24%  |
| Kingston            | 89        | 15.42%  |
| Micron Technology   | 65        | 11.27%  |
| Unknown             | 63        | 10.92%  |
| Crucial             | 35        | 6.07%   |
| Corsair             | 19        | 3.29%   |
| G.Skill             | 13        | 2.25%   |
| A-DATA Technology   | 12        | 2.08%   |
| Team                | 5         | 0.87%   |
| Patriot             | 5         | 0.87%   |
| Transcend           | 4         | 0.69%   |
| Nanya Technology    | 4         | 0.69%   |
| Elpida              | 4         | 0.69%   |
| Apacer              | 4         | 0.69%   |
| Ramaxel Technology  | 3         | 0.52%   |
| NOT SUPPORT         | 2         | 0.35%   |
| Unknown             | 2         | 0.35%   |
| Wilk                | 1         | 0.17%   |
| Unknown (ABCD)      | 1         | 0.17%   |
| Unknown (9B0D)      | 1         | 0.17%   |
| TwinMOS             | 1         | 0.17%   |
| Smart Brazil        | 1         | 0.17%   |
| SHARETRONIC         | 1         | 0.17%   |
| Qimonda             | 1         | 0.17%   |
| Mushkin             | 1         | 0.17%   |
| Hewlett-Packard     | 1         | 0.17%   |
| Avant               | 1         | 0.17%   |
| AMD                 | 1         | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Micron RAM 36ASF4G72PZ-2G3B1 32GB DIMM DDR4 2400MT/s      | 11        | 1.78%   |
| Samsung RAM M393A4K40BB1-CRC 32GB DIMM DDR4 2400MT/s      | 6         | 0.97%   |
| Samsung RAM M378B5173QH0-YK0 4GB DIMM DDR3 1600MT/s       | 6         | 0.97%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 5         | 0.81%   |
| SK hynix RAM HMAA8GR7AJR4N-XN 64GB DIMM DDR4 3200MT/s     | 4         | 0.65%   |
| Samsung RAM Module 8192MB DIMM DDR4 3200MT/s              | 4         | 0.65%   |
| Samsung RAM Module 8192MB DIMM DDR3 800MT/s               | 4         | 0.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 4         | 0.65%   |
| Samsung RAM M393A8G40MB2-CVF 64GB DIMM DDR4 2933MT/s      | 4         | 0.65%   |
| Micron RAM 4ATF51264AZ-2G3B1 4GB DIMM DDR4 2800MT/s       | 4         | 0.65%   |
| Micron RAM 36ASF4G72PZ-2G6D1 32GB DIMM DDR4 2667MT/s      | 4         | 0.65%   |
| Crucial RAM CT16G4DFD824A.C16FDD 16GB DIMM DDR4 2667MT/s  | 4         | 0.65%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s              | 3         | 0.49%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 3         | 0.49%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 3         | 0.49%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s    | 3         | 0.49%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                | 3         | 0.49%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 3         | 0.49%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s     | 3         | 0.49%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s               | 2         | 0.32%   |
| Unknown RAM Module 8GB DIMM 1600MT/s                      | 2         | 0.32%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s              | 2         | 0.32%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s              | 2         | 0.32%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                   | 2         | 0.32%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 2         | 0.32%   |
| Unknown RAM Module 4096MB FB-DIMM DDR2 667MT/s            | 2         | 0.32%   |
| Unknown RAM Module 2GB DIMM SDRAM                         | 2         | 0.32%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s              | 2         | 0.32%   |
| Unknown RAM Module 2048MB DIMM DDR2                       | 2         | 0.32%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s               | 2         | 0.32%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s              | 2         | 0.32%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s           | 2         | 0.32%   |
| SK hynix RAM Module 64GB DIMM 4800MT/s                    | 2         | 0.32%   |
| SK hynix RAM Module 2048MB DIMM DDR3 1600MT/s             | 2         | 0.32%   |
| SK hynix RAM Module 16GB DIMM DDR4 3200MT/s               | 2         | 0.32%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s      | 2         | 0.32%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 2         | 0.32%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 2         | 0.32%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 2         | 0.32%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 2         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 244       | 47.66%  |
| DDR3         | 186       | 36.33%  |
| DDR2         | 31        | 6.05%   |
| Unknown      | 27        | 5.27%   |
| SDRAM        | 6         | 1.17%   |
| LPDDR4       | 6         | 1.17%   |
| LPDDR3       | 3         | 0.59%   |
| DRAM         | 3         | 0.59%   |
| DDR          | 3         | 0.59%   |
| DDR5         | 2         | 0.39%   |
| DDR2 FB-DIMM | 1         | 0.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 331       | 64.77%  |
| SODIMM       | 162       | 31.7%   |
| Row Of Chips | 9         | 1.76%   |
| FB-DIMM      | 6         | 1.17%   |
| RIMM         | 2         | 0.39%   |
| Chip         | 1         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 160       | 29.2%   |
| 4096  | 152       | 27.74%  |
| 16384 | 95        | 17.34%  |
| 2048  | 59        | 10.77%  |
| 32768 | 55        | 10.04%  |
| 1024  | 14        | 2.55%   |
| 65536 | 12        | 2.19%   |
| 512   | 1         | 0.18%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 101       | 18.23%  |
| 1333    | 73        | 13.18%  |
| 2667    | 72        | 13%     |
| 2400    | 69        | 12.45%  |
| 3200    | 50        | 9.03%   |
| 2133    | 30        | 5.42%   |
| 800     | 23        | 4.15%   |
| 667     | 22        | 3.97%   |
| Unknown | 12        | 2.17%   |
| 3600    | 10        | 1.81%   |
| 2933    | 10        | 1.81%   |
| 2666    | 10        | 1.81%   |
| 1334    | 8         | 1.44%   |
| 2800    | 6         | 1.08%   |
| 1800    | 5         | 0.9%    |
| 3266    | 4         | 0.72%   |
| 1866    | 4         | 0.72%   |
| 1067    | 4         | 0.72%   |
| 400     | 4         | 0.72%   |
| 4800    | 3         | 0.54%   |
| 4267    | 3         | 0.54%   |
| 1066    | 3         | 0.54%   |
| 3466    | 2         | 0.36%   |
| 3000    | 2         | 0.36%   |
| 2134    | 2         | 0.36%   |
| 2000    | 2         | 0.36%   |
| 1867    | 2         | 0.36%   |
| 1648    | 2         | 0.36%   |
| 65535   | 1         | 0.18%   |
| 5600    | 1         | 0.18%   |
| 4333    | 1         | 0.18%   |
| 4199    | 1         | 0.18%   |
| 4000    | 1         | 0.18%   |
| 3733    | 1         | 0.18%   |
| 3533    | 1         | 0.18%   |
| 3500    | 1         | 0.18%   |
| 3100    | 1         | 0.18%   |
| 2733    | 1         | 0.18%   |
| 2500    | 1         | 0.18%   |
| 2465    | 1         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 46.15%  |
| Brother Industries  | 3         | 23.08%  |
| Star Micronics      | 1         | 7.69%   |
| Samsung Electronics | 1         | 7.69%   |
| Kyocera             | 1         | 7.69%   |
| Canon               | 1         | 7.69%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| HP DeskJet 2130 series            | 2         | 15.38%  |
| Star Micronics TSP100ECO/TSP100II | 1         | 7.69%   |
| Samsung M288x Series              | 1         | 7.69%   |
| Kyocera FS-1030D printer          | 1         | 7.69%   |
| HP Smart Install                  | 1         | 7.69%   |
| HP LaserJet 400 M401a             | 1         | 7.69%   |
| HP LaserJet 3030                  | 1         | 7.69%   |
| HP LaserJet 1020                  | 1         | 7.69%   |
| Canon MF210 Series                | 1         | 7.69%   |
| Brother MFC-J450DW                | 1         | 7.69%   |
| Brother MFC-9130CW                | 1         | 7.69%   |
| Brother HL-L2390DW                | 1         | 7.69%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 53        | 22.08%  |
| Microdia                               | 26        | 10.83%  |
| Logitech                               | 18        | 7.5%    |
| Realtek Semiconductor                  | 17        | 7.08%   |
| IMC Networks                           | 17        | 7.08%   |
| Bison Electronics                      | 16        | 6.67%   |
| Sunplus Innovation Technology          | 15        | 6.25%   |
| Lite-On Technology                     | 11        | 4.58%   |
| Quanta                                 | 9         | 3.75%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 3.75%   |
| Syntek                                 | 5         | 2.08%   |
| Suyin                                  | 5         | 2.08%   |
| Acer                                   | 5         | 2.08%   |
| Samsung Electronics                    | 4         | 1.67%   |
| Microsoft                              | 4         | 1.67%   |
| Apple                                  | 4         | 1.67%   |
| Silicon Motion                         | 3         | 1.25%   |
| Generalplus Technology                 | 3         | 1.25%   |
| Ricoh                                  | 2         | 0.83%   |
| Lenovo                                 | 2         | 0.83%   |
| Alcor Micro                            | 2         | 0.83%   |
| Z-Star Microelectronics                | 1         | 0.42%   |
| WaveRider Communications               | 1         | 0.42%   |
| Sunplus Technology                     | 1         | 0.42%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.42%   |
| Luxvisions Innotech Limited            | 1         | 0.42%   |
| Intel                                  | 1         | 0.42%   |
| Hopewin Electronic Material            | 1         | 0.42%   |
| Hewlett-Packard                        | 1         | 0.42%   |
| Cubeternet                             | 1         | 0.42%   |
| Creative Technology                    | 1         | 0.42%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Chicony integrated camera                   | 10        | 4.17%   |
| Microdia Integrated_Webcam_HD               | 9         | 3.75%   |
| IMC Networks Integrated Camera              | 8         | 3.33%   |
| Sunplus Integrated_Webcam_HD                | 6         | 2.5%    |
| Chicony HD WebCam                           | 6         | 2.5%    |
| Lite-On HP HD Camera                        | 5         | 2.08%   |
| Chicony HP HD Camera                        | 5         | 2.08%   |
| Samsung Galaxy series, misc. (MTP mode)     | 4         | 1.67%   |
| Logitech HD Webcam C615                     | 4         | 1.67%   |
| Logitech HD Pro Webcam C920                 | 4         | 1.67%   |
| IMC Networks USB2.0 HD UVC WebCam           | 4         | 1.67%   |
| Chicony HP TrueVision HD                    | 4         | 1.67%   |
| Bison Integrated Camera                     | 4         | 1.67%   |
| Logitech Webcam C270                        | 3         | 1.25%   |
| Lite-On Integrated Camera                   | 3         | 1.25%   |
| Generalplus 808 Camera #9 (web-cam mode)    | 3         | 1.25%   |
| Chicony USB2.0 VGA UVC WebCam               | 3         | 1.25%   |
| Chicony Integrated Camera (1280x720@30)     | 3         | 1.25%   |
| Chicony HP Webcam [2 MP Macro]              | 3         | 1.25%   |
| Bison Lenovo EasyCamera                     | 3         | 1.25%   |
| Bison HD Webcam                             | 3         | 1.25%   |
| Syntek Integrated Camera                    | 2         | 0.83%   |
| Suyin Integrated Webcam                     | 2         | 0.83%   |
| Sunplus Full HD webcam                      | 2         | 0.83%   |
| Realtek USB Camera                          | 2         | 0.83%   |
| Realtek Lenovo EasyCamera                   | 2         | 0.83%   |
| Realtek Integrated_Webcam_HD                | 2         | 0.83%   |
| Quanta Laptop_Integrated_Webcam_2HDM        | 2         | 0.83%   |
| Quanta HP TrueVision HD Camera              | 2         | 0.83%   |
| Microdia Laptop_Integrated_Webcam_HD        | 2         | 0.83%   |
| Microdia Laptop_Integrated_Webcam_2M        | 2         | 0.83%   |
| Microdia Dell Integrated HD Webcam          | 2         | 0.83%   |
| Microdia Defender G-Lens 2577 HD720p Camera | 2         | 0.83%   |
| Microdia Camera                             | 2         | 0.83%   |
| Logitech C922 Pro Stream Webcam             | 2         | 0.83%   |
| Lite-On HP HD Webcam                        | 2         | 0.83%   |
| Lenovo FHD Webcam Audio                     | 2         | 0.83%   |
| Chicony USB2.0 Camera                       | 2         | 0.83%   |
| Chicony TOSHIBA Web Camera - HD             | 2         | 0.83%   |
| Chicony Thinkpad T430 camera                | 2         | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 28        | 48.28%  |
| Synaptics                  | 13        | 22.41%  |
| AuthenTec                  | 5         | 8.62%   |
| Upek                       | 4         | 6.9%    |
| Shenzhen Goodix Technology | 3         | 5.17%   |
| STMicroelectronics         | 2         | 3.45%   |
| Elan Microelectronics      | 2         | 3.45%   |
| Dell                       | 1         | 1.72%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 15.52%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 8.62%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 8.62%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 8.62%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 6.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 5.17%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 5.17%   |
| AuthenTec AES2810                                                          | 3         | 5.17%   |
| Validity Sensors VFS491                                                    | 2         | 3.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.45%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 3.45%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 3.45%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 3.45%   |
| Elan ELAN:Fingerprint                                                      | 2         | 3.45%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 3.45%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.72%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.72%   |
| Synaptics UWP WBDI Device                                                  | 1         | 1.72%   |
| Synaptics  WBDI                                                            | 1         | 1.72%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.72%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.72%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 1         | 1.72%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Broadcom            | 12        | 48%     |
| SCM Microsystems    | 3         | 12%     |
| Upek                | 2         | 8%      |
| Giesecke & Devrient | 2         | 8%      |
| Cherry              | 2         | 8%      |
| O2 Micro            | 1         | 4%      |
| Lenovo              | 1         | 4%      |
| Hewlett-Packard     | 1         | 4%      |
| Alcor Micro         | 1         | 4%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 20%     |
| Broadcom 5880                                                                | 3         | 12%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 8%      |
| Giesecke & Devrient StarSign CUT S                                           | 2         | 8%      |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 8%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 8%      |
| Broadcom 58200                                                               | 2         | 8%      |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 4%      |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 4%      |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 4%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 4%      |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4%      |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 4%      |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 4%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 428       | 57.14%  |
| 1     | 196       | 26.17%  |
| 2     | 75        | 10.01%  |
| 3     | 27        | 3.6%    |
| 4     | 16        | 2.14%   |
| 5     | 6         | 0.8%    |
| 6     | 1         | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 110       | 23.21%  |
| Communication controller | 104       | 21.94%  |
| Unassigned class         | 71        | 14.98%  |
| Fingerprint reader       | 57        | 12.03%  |
| Net/wireless             | 40        | 8.44%   |
| Net/ethernet             | 19        | 4.01%   |
| Sound                    | 13        | 2.74%   |
| Chipcard                 | 13        | 2.74%   |
| Multimedia controller    | 11        | 2.32%   |
| Storage                  | 8         | 1.69%   |
| Storage/ide              | 7         | 1.48%   |
| Storage/raid             | 5         | 1.05%   |
| Network                  | 5         | 1.05%   |
| Bluetooth                | 3         | 0.63%   |
| Storage/ata              | 2         | 0.42%   |
| Dvb card                 | 2         | 0.42%   |
| Camera                   | 2         | 0.42%   |
| Modem                    | 1         | 0.21%   |
| Card reader              | 1         | 0.21%   |

