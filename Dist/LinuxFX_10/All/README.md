LinuxFX 10 - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for LinuxFX 10.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LinuxFX_10/Desktop/README.md) and [notebooks](/Dist/LinuxFX_10/Notebook/README.md).

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

Total: 101

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek    | P8Z77-V PRO/THUNDERBOLT     | Desktop     | [793f82cda7](https://linux-hardware.org/?probe=793f82cda7) | Sep 03, 2022 |
| ASUSTek    | M5A78L-M/USB3               | Desktop     | [3db0355713](https://linux-hardware.org/?probe=3db0355713) | Aug 12, 2022 |
| Unknown    | 1.0                         | All in one  | [8145704100](https://linux-hardware.org/?probe=8145704100) | Aug 01, 2022 |
| Apple      | Mac-F221BEC8                | Desktop     | [92c20deb50](https://linux-hardware.org/?probe=92c20deb50) | May 17, 2022 |
| Dell       | Vostro 1000                 | Notebook    | [d1fae6443d](https://linux-hardware.org/?probe=d1fae6443d) | May 17, 2022 |
| Gigabyte   | GA-78LMT-S2P                | Desktop     | [b8194d3077](https://linux-hardware.org/?probe=b8194d3077) | May 01, 2022 |
| Gigabyte   | GA-78LMT-S2P                | Desktop     | [3aeeaee161](https://linux-hardware.org/?probe=3aeeaee161) | Apr 23, 2022 |
| Samsung    | 340XAA/350XAA/550XAA        | Notebook    | [cd93e2fd82](https://linux-hardware.org/?probe=cd93e2fd82) | Apr 08, 2022 |
| ASRock     | 970 Extreme4                | Desktop     | [a30d1aa4b9](https://linux-hardware.org/?probe=a30d1aa4b9) | Dec 29, 2021 |
| Gigabyte   | G31M-ES2C                   | Desktop     | [5afa9a7018](https://linux-hardware.org/?probe=5afa9a7018) | Dec 23, 2021 |
| Toshiba    | Satellite C660              | Notebook    | [47b40007ee](https://linux-hardware.org/?probe=47b40007ee) | Dec 04, 2021 |
| Dell       | Inspiron 1501               | Notebook    | [94ca9e7f47](https://linux-hardware.org/?probe=94ca9e7f47) | Nov 12, 2021 |
| ASRock     | 970 Extreme4                | Desktop     | [85b942a5c3](https://linux-hardware.org/?probe=85b942a5c3) | Oct 30, 2021 |
| ASRock     | 970 Extreme4                | Desktop     | [022942c4aa](https://linux-hardware.org/?probe=022942c4aa) | Oct 30, 2021 |
| Dell       | Latitude E6420              | Notebook    | [dc9a1e9c1b](https://linux-hardware.org/?probe=dc9a1e9c1b) | Oct 18, 2021 |
| MSI        | MS-7309                     | Desktop     | [33faf5dbef](https://linux-hardware.org/?probe=33faf5dbef) | Oct 14, 2021 |
| MSI        | MS-7309                     | Desktop     | [b0ddfaaa86](https://linux-hardware.org/?probe=b0ddfaaa86) | Oct 12, 2021 |
| HP         | 250 G7 Notebook PC          | Notebook    | [7368bcaf0a](https://linux-hardware.org/?probe=7368bcaf0a) | Oct 04, 2021 |
| HP         | 250 G7 Notebook PC          | Notebook    | [c7ae2849cc](https://linux-hardware.org/?probe=c7ae2849cc) | Sep 30, 2021 |
| PCWare     | IPMH61R2                    | Desktop     | [62d2476431](https://linux-hardware.org/?probe=62d2476431) | Sep 27, 2021 |
| Gigabyte   | X570 UD                     | Desktop     | [e1777d09cb](https://linux-hardware.org/?probe=e1777d09cb) | Sep 10, 2021 |
| Medion     | S4216                       | Notebook    | [677bd3ecb4](https://linux-hardware.org/?probe=677bd3ecb4) | Aug 27, 2021 |
| Medion     | S4216                       | Notebook    | [a0ae7753cf](https://linux-hardware.org/?probe=a0ae7753cf) | Aug 26, 2021 |
| Dell       | Inspiron 3421               | Notebook    | [06a0a6486b](https://linux-hardware.org/?probe=06a0a6486b) | Aug 26, 2021 |
| MSI        | A88XI AC                    | Desktop     | [1306310e52](https://linux-hardware.org/?probe=1306310e52) | Aug 02, 2021 |
| MSI        | A88XI AC                    | Desktop     | [ebdf5c76be](https://linux-hardware.org/?probe=ebdf5c76be) | Aug 02, 2021 |
| Dell       | Latitude E5520              | Notebook    | [cae8dd2173](https://linux-hardware.org/?probe=cae8dd2173) | Jul 27, 2021 |
| Jumper     | Ezpad                       | Tablet      | [d40961f21f](https://linux-hardware.org/?probe=d40961f21f) | Jul 26, 2021 |
| Jumper     | Ezpad                       | Tablet      | [f80ea7b800](https://linux-hardware.org/?probe=f80ea7b800) | Jul 26, 2021 |
| Dell       | Latitude E5520              | Notebook    | [0112c3a302](https://linux-hardware.org/?probe=0112c3a302) | Jul 22, 2021 |
| Intel      | DG31PR AAD97573-306         | Desktop     | [a81005ef0b](https://linux-hardware.org/?probe=a81005ef0b) | Jul 10, 2021 |
| ASRock     | B450M Steel Legend          | Desktop     | [42869f7bb5](https://linux-hardware.org/?probe=42869f7bb5) | Jun 20, 2021 |
| Samsung    | 305E4A/305E5A/305E7A        | Notebook    | [3db60d4f9a](https://linux-hardware.org/?probe=3db60d4f9a) | Jun 01, 2021 |
| HP         | Pavilion dv6700             | Notebook    | [4e93c68985](https://linux-hardware.org/?probe=4e93c68985) | May 26, 2021 |
| HP         | Pavilion dv6700             | Notebook    | [a114e32ffb](https://linux-hardware.org/?probe=a114e32ffb) | May 26, 2021 |
| Lenovo     | ThinkPad T450s 20BWS0YF0... | Notebook    | [7b1e0f2693](https://linux-hardware.org/?probe=7b1e0f2693) | May 11, 2021 |
| Apple      | Mac-942B59F58194171B iMa... | All in one  | [9707be5d20](https://linux-hardware.org/?probe=9707be5d20) | Apr 24, 2021 |
| Dell       | 0TVR1F A01                  | Desktop     | [4022d93b8a](https://linux-hardware.org/?probe=4022d93b8a) | Apr 18, 2021 |
| Acer       | Aspire E5-551               | Notebook    | [9f023d545c](https://linux-hardware.org/?probe=9f023d545c) | Mar 23, 2021 |
| Acer       | Aspire 5755G                | Notebook    | [0984c7aebc](https://linux-hardware.org/?probe=0984c7aebc) | Mar 18, 2021 |
| Supermicro | H8DG6/H8DGi                 | Server      | [ad61efb931](https://linux-hardware.org/?probe=ad61efb931) | Mar 11, 2021 |
| Acer       | Aspire 5755G                | Notebook    | [861fb95171](https://linux-hardware.org/?probe=861fb95171) | Mar 09, 2021 |
| Acer       | Aspire E1-731               | Notebook    | [747dbbb54d](https://linux-hardware.org/?probe=747dbbb54d) | Mar 07, 2021 |
| Acer       | Aspire E1-731               | Notebook    | [1b82018148](https://linux-hardware.org/?probe=1b82018148) | Mar 02, 2021 |
| ASRock     | N68-GE3 UCC                 | Desktop     | [f2a9721ca5](https://linux-hardware.org/?probe=f2a9721ca5) | Feb 25, 2021 |
| Gigabyte   | G31M-S2C                    | Desktop     | [95c9698f2b](https://linux-hardware.org/?probe=95c9698f2b) | Feb 24, 2021 |
| ASUSTek    | K50C                        | Notebook    | [d6ac6b2de1](https://linux-hardware.org/?probe=d6ac6b2de1) | Feb 18, 2021 |
| ASUSTek    | K50C                        | Notebook    | [a899af5e96](https://linux-hardware.org/?probe=a899af5e96) | Feb 18, 2021 |
| Dell       | Inspiron 1525               | Notebook    | [30d9ab855e](https://linux-hardware.org/?probe=30d9ab855e) | Feb 16, 2021 |
| Dell       | Inspiron 1525               | Notebook    | [a37ef6324c](https://linux-hardware.org/?probe=a37ef6324c) | Feb 16, 2021 |
| Lenovo     | ThinkPad X1 Carbon 2nd F... | Notebook    | [799c301ad6](https://linux-hardware.org/?probe=799c301ad6) | Feb 08, 2021 |
| Pegatron   | B34C                        | Notebook    | [4c3a4f9ad1](https://linux-hardware.org/?probe=4c3a4f9ad1) | Feb 05, 2021 |
| ASRock     | ConRoe1333-D667             | Desktop     | [54121172b8](https://linux-hardware.org/?probe=54121172b8) | Jan 31, 2021 |
| ASUSTek    | ASUS TUF Gaming F15 FX50... | Notebook    | [a22da47202](https://linux-hardware.org/?probe=a22da47202) | Jan 30, 2021 |
| Acer       | Aspire A515-51G             | Notebook    | [3300b2bb9d](https://linux-hardware.org/?probe=3300b2bb9d) | Jan 22, 2021 |
| MSI        | B450M PRO-M2 MAX            | Desktop     | [ecbdfd2c54](https://linux-hardware.org/?probe=ecbdfd2c54) | Jan 17, 2021 |
| HP         | 2B1E                        | Desktop     | [940750f549](https://linux-hardware.org/?probe=940750f549) | Jan 05, 2021 |
| ASUSTek    | P8Z68-V LE                  | Desktop     | [356c40c60b](https://linux-hardware.org/?probe=356c40c60b) | Dec 27, 2020 |
| Lenovo     | Y70-70 Touch 80DU           | Notebook    | [023b353ca8](https://linux-hardware.org/?probe=023b353ca8) | Dec 22, 2020 |
| ASUSTek    | H87-PRO                     | Desktop     | [e2287834ae](https://linux-hardware.org/?probe=e2287834ae) | Dec 10, 2020 |
| ASUSTek    | H87-PRO                     | Desktop     | [17bd61ae55](https://linux-hardware.org/?probe=17bd61ae55) | Dec 09, 2020 |
| Gigabyte   | B450 AORUS M                | Desktop     | [8e3b4356b7](https://linux-hardware.org/?probe=8e3b4356b7) | Dec 03, 2020 |
| Acer       | Aspire 5720Z                | Notebook    | [38045109f8](https://linux-hardware.org/?probe=38045109f8) | Nov 29, 2020 |
| Toshiba    | Satellite C50D-A-12R        | Notebook    | [2b5e2b26b2](https://linux-hardware.org/?probe=2b5e2b26b2) | Nov 23, 2020 |
| Apple      | Mac-F226BEC8 PVT            | All in one  | [ccc5f55191](https://linux-hardware.org/?probe=ccc5f55191) | Nov 21, 2020 |
| Gigabyte   | P57V6                       | Notebook    | [ec76a0907c](https://linux-hardware.org/?probe=ec76a0907c) | Nov 15, 2020 |
| Dell       | 0V6D8J A00                  | Desktop     | [5b4385cd10](https://linux-hardware.org/?probe=5b4385cd10) | Nov 09, 2020 |
| Dell       | 0V6D8J A00                  | Desktop     | [13e1111610](https://linux-hardware.org/?probe=13e1111610) | Nov 09, 2020 |
| Acer       | Aspire TC-105               | Desktop     | [0ee92155a3](https://linux-hardware.org/?probe=0ee92155a3) | Nov 04, 2020 |
| ECS        | A780GM-A                    | Desktop     | [cf03b0c26b](https://linux-hardware.org/?probe=cf03b0c26b) | Nov 04, 2020 |
| Acer       | Aspire ES1-512              | Notebook    | [328c13ce38](https://linux-hardware.org/?probe=328c13ce38) | Oct 25, 2020 |
| Acer       | Aspire ES1-512              | Notebook    | [59368b9e58](https://linux-hardware.org/?probe=59368b9e58) | Oct 24, 2020 |
| Acer       | Makalu                      | Notebook    | [1519ec67b5](https://linux-hardware.org/?probe=1519ec67b5) | Sep 07, 2020 |
| Acer       | Makalu                      | Notebook    | [51b6611d94](https://linux-hardware.org/?probe=51b6611d94) | Sep 06, 2020 |
| Dell       | 0TT6JF A02                  | Server      | [ebfac9e556](https://linux-hardware.org/?probe=ebfac9e556) | Sep 04, 2020 |
| Dell       | Inspiron 15-3567            | Notebook    | [d7fbcdbfbe](https://linux-hardware.org/?probe=d7fbcdbfbe) | Sep 03, 2020 |
| HP         | Compaq Presario CQ50        | Notebook    | [b82778b925](https://linux-hardware.org/?probe=b82778b925) | Sep 01, 2020 |
| Gigabyte   | P57V6                       | Notebook    | [7f8d44d28e](https://linux-hardware.org/?probe=7f8d44d28e) | Aug 30, 2020 |
| HP         | ProBook 6560b               | Notebook    | [99a7a9817b](https://linux-hardware.org/?probe=99a7a9817b) | Aug 26, 2020 |
| HP         | ProBook 6560b               | Notebook    | [b9893a704d](https://linux-hardware.org/?probe=b9893a704d) | Aug 26, 2020 |
| Olivetti   | P55-AEU-323-4G320           | Notebook    | [c08737d73c](https://linux-hardware.org/?probe=c08737d73c) | Aug 23, 2020 |
| Lenovo     | G505 20240                  | Notebook    | [aa6a5c7462](https://linux-hardware.org/?probe=aa6a5c7462) | Aug 22, 2020 |
| ASUSTek    | K72Jr                       | Notebook    | [51cd547219](https://linux-hardware.org/?probe=51cd547219) | Aug 18, 2020 |
| ASUSTek    | K72Jr                       | Notebook    | [d68a58547e](https://linux-hardware.org/?probe=d68a58547e) | Aug 15, 2020 |
| Gigabyte   | 970A-DS3P                   | Desktop     | [c5a0f02633](https://linux-hardware.org/?probe=c5a0f02633) | Jul 24, 2020 |
| Dell       | Inspiron 5423               | Notebook    | [1f3e63e601](https://linux-hardware.org/?probe=1f3e63e601) | Jul 24, 2020 |
| Acer       | Aspire E1-531               | Notebook    | [6104770d46](https://linux-hardware.org/?probe=6104770d46) | Jul 23, 2020 |
| Dell       | Vostro 1000                 | Notebook    | [ffb49e4b86](https://linux-hardware.org/?probe=ffb49e4b86) | Jul 22, 2020 |
| Positivo   | Mobile                      | Notebook    | [7ac9083ae4](https://linux-hardware.org/?probe=7ac9083ae4) | Jul 21, 2020 |
| HP         | Mini 210-1000               | Notebook    | [d1e83a2d9b](https://linux-hardware.org/?probe=d1e83a2d9b) | Jul 19, 2020 |
| Dell       | 0Y644J A02                  | Desktop     | [96f0709424](https://linux-hardware.org/?probe=96f0709424) | Jul 16, 2020 |
| Gigabyte   | B85M-D3H                    | Desktop     | [ab9fa86313](https://linux-hardware.org/?probe=ab9fa86313) | Jul 16, 2020 |
| Intel      | B75                         | Desktop     | [dc59852769](https://linux-hardware.org/?probe=dc59852769) | Jul 11, 2020 |
| HP         | 250 G6 Notebook PC          | Notebook    | [bc9d23a74c](https://linux-hardware.org/?probe=bc9d23a74c) | Jul 02, 2020 |
| HP         | 250 G6 Notebook PC          | Notebook    | [b1757b232f](https://linux-hardware.org/?probe=b1757b232f) | Jul 02, 2020 |
| Dell       | 0CRWCR A01                  | All in one  | [fe89daec6e](https://linux-hardware.org/?probe=fe89daec6e) | Jun 20, 2020 |
| Lenovo     | G550 2958                   | Notebook    | [6cfc44a819](https://linux-hardware.org/?probe=6cfc44a819) | Jun 11, 2020 |
| Lenovo     | G550 2958                   | Notebook    | [95b68a8144](https://linux-hardware.org/?probe=95b68a8144) | Jun 11, 2020 |
| Dell       | Inspiron 3520               | Notebook    | [c78c5e6395](https://linux-hardware.org/?probe=c78c5e6395) | May 16, 2020 |
| HP         | EliteBook Folio 9470m       | Notebook    | [f0b4ebc551](https://linux-hardware.org/?probe=f0b4ebc551) | May 16, 2020 |
| HP         | G42                         | Notebook    | [5c1017a089](https://linux-hardware.org/?probe=5c1017a089) | May 11, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.4.0-72-generic            | 12        | 16.9%   |
| 5.4.0-52-generic            | 10        | 14.08%  |
| 5.6.15-windowsfx-10-generic | 8         | 11.27%  |
| 5.7.15-050715-generic       | 5         | 7.04%   |
| 5.5.19-050519-generic       | 4         | 5.63%   |
| 5.4.0-65-generic            | 4         | 5.63%   |
| 5.7.8-windowsfx-generic     | 3         | 4.23%   |
| 5.4.0-73-generic            | 3         | 4.23%   |
| 5.4.0-66-generic            | 3         | 4.23%   |
| 5.4.0-42-generic            | 3         | 4.23%   |
| 5.4.0-29-generic            | 3         | 4.23%   |
| 5.4.0-56-generic            | 2         | 2.82%   |
| 5.4.0-54-generic            | 2         | 2.82%   |
| 5.4.0-90-generic            | 1         | 1.41%   |
| 5.4.0-88-generic            | 1         | 1.41%   |
| 5.4.0-67-generic            | 1         | 1.41%   |
| 5.4.0-45-generic            | 1         | 1.41%   |
| 5.4.0-125-generic           | 1         | 1.41%   |
| 5.4.0-124-generic           | 1         | 1.41%   |
| 5.4.0-110-generic           | 1         | 1.41%   |
| 5.4.0-107-generic           | 1         | 1.41%   |
| 5.10.2-051002-generic       | 1         | 1.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 50        | 70.42%  |
| 5.6.15  | 8         | 11.27%  |
| 5.7.15  | 5         | 7.04%   |
| 5.5.19  | 4         | 5.63%   |
| 5.7.8   | 3         | 4.23%   |
| 5.10.2  | 1         | 1.41%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 50        | 70.42%  |
| 5.7     | 8         | 11.27%  |
| 5.6     | 8         | 11.27%  |
| 5.5     | 4         | 5.63%   |
| 5.10    | 1         | 1.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 71        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 57        | 80.28%  |
| KDE        | 8         | 11.27%  |
| Cinnamon   | 3         | 4.23%   |
| Unknown    | 2         | 2.82%   |
| KDE5       | 1         | 1.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 71        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 42        | 59.15%  |
| SDDM    | 17        | 23.94%  |
| TDM     | 11        | 15.49%  |
| LightDM | 1         | 1.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| pt_BR | 20        | 28.17%  |
| en_US | 12        | 16.9%   |
| de_DE | 5         | 7.04%   |
| fr_FR | 4         | 5.63%   |
| C     | 4         | 5.63%   |
| pl_PL | 3         | 4.23%   |
| it_IT | 3         | 4.23%   |
| en_AU | 3         | 4.23%   |
| es_ES | 2         | 2.82%   |
| es_CL | 2         | 2.82%   |
| es_AR | 2         | 2.82%   |
| en_ZA | 2         | 2.82%   |
| en_CA | 2         | 2.82%   |
| sv_SE | 1         | 1.41%   |
| sr_RS | 1         | 1.41%   |
| ro_RO | 1         | 1.41%   |
| fr_CA | 1         | 1.41%   |
| es_MX | 1         | 1.41%   |
| en_IN | 1         | 1.41%   |
| cs_CZ | 1         | 1.41%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 48        | 67.61%  |
| EFI  | 23        | 32.39%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 67        | 94.37%  |
| Overlay | 2         | 2.82%   |
| Xfs     | 1         | 1.41%   |
| Btrfs   | 1         | 1.41%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 63        | 88.73%  |
| MBR     | 4         | 5.63%   |
| GPT     | 4         | 5.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 61        | 85.92%  |
| Yes       | 10        | 14.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 53        | 74.65%  |
| Yes       | 18        | 25.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 14        | 19.72%  |
| Hewlett-Packard     | 9         | 12.68%  |
| ASUSTek Computer    | 7         | 9.86%   |
| Gigabyte Technology | 6         | 8.45%   |
| Acer                | 6         | 8.45%   |
| Lenovo              | 5         | 7.04%   |
| ASRock              | 4         | 5.63%   |
| MSI                 | 3         | 4.23%   |
| Apple               | 3         | 4.23%   |
| Samsung Electronics | 2         | 2.82%   |
| Intel               | 2         | 2.82%   |
| Toshiba             | 1         | 1.41%   |
| Supermicro          | 1         | 1.41%   |
| Positivo            | 1         | 1.41%   |
| Pegatron            | 1         | 1.41%   |
| PCWare              | 1         | 1.41%   |
| Olivetti            | 1         | 1.41%   |
| Medion              | 1         | 1.41%   |
| Jumper              | 1         | 1.41%   |
| ECS                 | 1         | 1.41%   |
| Unknown             | 1         | 1.41%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Dell Vostro 1000                      | 2         | 2.82%   |
| Toshiba Satellite C50D-A-12R          | 1         | 1.41%   |
| Supermicro H8DG6/H8DGi                | 1         | 1.41%   |
| Samsung 340XAA/350XAA/550XAA          | 1         | 1.41%   |
| Samsung 305E4A/305E5A/305E7A          | 1         | 1.41%   |
| Positivo Mobile                       | 1         | 1.41%   |
| Pegatron B34C                         | 1         | 1.41%   |
| PCWare IPMH61R2                       | 1         | 1.41%   |
| Olivetti P55-AEU-323-4G320            | 1         | 1.41%   |
| MSI MS-7B84                           | 1         | 1.41%   |
| MSI MS-7913                           | 1         | 1.41%   |
| MSI MS-7309                           | 1         | 1.41%   |
| Medion S4216                          | 1         | 1.41%   |
| Lenovo Y70-70 Touch 80DU              | 1         | 1.41%   |
| Lenovo ThinkPad X1 Carbon 2nd F2G3H4J | 1         | 1.41%   |
| Lenovo ThinkPad T450s 20BWS0YF00      | 1         | 1.41%   |
| Lenovo G550 2958                      | 1         | 1.41%   |
| Lenovo G505 20240                     | 1         | 1.41%   |
| Jumper Ezpad                          | 1         | 1.41%   |
| Intel DG31PR AAD97573-306             | 1         | 1.41%   |
| Intel B75                             | 1         | 1.41%   |
| HP ProBook 6560b                      | 1         | 1.41%   |
| HP Pavilion dv6700                    | 1         | 1.41%   |
| HP Mini 210-1000                      | 1         | 1.41%   |
| HP G42                                | 1         | 1.41%   |
| HP EliteBook Folio 9470m              | 1         | 1.41%   |
| HP Compaq Presario CQ50               | 1         | 1.41%   |
| HP 250 G7 Notebook PC                 | 1         | 1.41%   |
| HP 250 G6 Notebook PC                 | 1         | 1.41%   |
| HP 202 G2 MT                          | 1         | 1.41%   |
| Gigabyte X570 UD                      | 1         | 1.41%   |
| Gigabyte P57V6                        | 1         | 1.41%   |
| Gigabyte GA-78LMT-S2P                 | 1         | 1.41%   |
| Gigabyte G31M-ES2C                    | 1         | 1.41%   |
| Gigabyte B450 AORUS M                 | 1         | 1.41%   |
| Gigabyte 970A-DS3P                    | 1         | 1.41%   |
| ECS A780GM-A                          | 1         | 1.41%   |
| Dell PowerEdge R810                   | 1         | 1.41%   |
| Dell OptiPlex 9010 AIO                | 1         | 1.41%   |
| Dell OptiPlex 360                     | 1         | 1.41%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell Inspiron              | 7         | 9.86%   |
| Acer Aspire                | 6         | 8.45%   |
| Dell OptiPlex              | 3         | 4.23%   |
| Lenovo ThinkPad            | 2         | 2.82%   |
| HP 250                     | 2         | 2.82%   |
| Dell Vostro                | 2         | 2.82%   |
| Toshiba Satellite          | 1         | 1.41%   |
| Supermicro H8DG6           | 1         | 1.41%   |
| Samsung 340XAA             | 1         | 1.41%   |
| Samsung 305E4A             | 1         | 1.41%   |
| Positivo Mobile            | 1         | 1.41%   |
| Pegatron B34C              | 1         | 1.41%   |
| PCWare IPMH61R2            | 1         | 1.41%   |
| Olivetti P55-AEU-323-4G320 | 1         | 1.41%   |
| MSI MS-7B84                | 1         | 1.41%   |
| MSI MS-7913                | 1         | 1.41%   |
| MSI MS-7309                | 1         | 1.41%   |
| Medion S4216               | 1         | 1.41%   |
| Lenovo Y70-70              | 1         | 1.41%   |
| Lenovo G550                | 1         | 1.41%   |
| Lenovo G505                | 1         | 1.41%   |
| Jumper Ezpad               | 1         | 1.41%   |
| Intel DG31PR               | 1         | 1.41%   |
| Intel B75                  | 1         | 1.41%   |
| HP ProBook                 | 1         | 1.41%   |
| HP Pavilion                | 1         | 1.41%   |
| HP Mini                    | 1         | 1.41%   |
| HP G42                     | 1         | 1.41%   |
| HP EliteBook               | 1         | 1.41%   |
| HP Compaq                  | 1         | 1.41%   |
| HP 202                     | 1         | 1.41%   |
| Gigabyte X570              | 1         | 1.41%   |
| Gigabyte P57V6             | 1         | 1.41%   |
| Gigabyte GA-78LMT-S2P      | 1         | 1.41%   |
| Gigabyte G31M-ES2C         | 1         | 1.41%   |
| Gigabyte B450              | 1         | 1.41%   |
| Gigabyte 970A-DS3P         | 1         | 1.41%   |
| ECS A780GM-A               | 1         | 1.41%   |
| Dell PowerEdge             | 1         | 1.41%   |
| Dell Latitude              | 1         | 1.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 9         | 12.68%  |
| 2013    | 8         | 11.27%  |
| 2012    | 8         | 11.27%  |
| 2014    | 7         | 9.86%   |
| 2009    | 6         | 8.45%   |
| 2018    | 5         | 7.04%   |
| 2008    | 5         | 7.04%   |
| 2019    | 4         | 5.63%   |
| 2010    | 4         | 5.63%   |
| 2007    | 4         | 5.63%   |
| 2015    | 3         | 4.23%   |
| 2006    | 3         | 4.23%   |
| 2017    | 2         | 2.82%   |
| 2020    | 1         | 1.41%   |
| 2016    | 1         | 1.41%   |
| Unknown | 1         | 1.41%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 39        | 54.93%  |
| Desktop    | 25        | 35.21%  |
| All in one | 4         | 5.63%   |
| Server     | 2         | 2.82%   |
| Tablet     | 1         | 1.41%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 70        | 97.22%  |
| Enabled  | 2         | 2.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 71        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 29        | 40.85%  |
| 4.01-8.0        | 13        | 18.31%  |
| 16.01-24.0      | 10        | 14.08%  |
| 8.01-16.0       | 7         | 9.86%   |
| 1.01-2.0        | 4         | 5.63%   |
| 32.01-64.0      | 3         | 4.23%   |
| 2.01-3.0        | 3         | 4.23%   |
| More than 256.0 | 1         | 1.41%   |
| 64.01-256.0     | 1         | 1.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 36        | 50%     |
| 2.01-3.0  | 15        | 20.83%  |
| 3.01-4.0  | 13        | 18.06%  |
| 4.01-8.0  | 5         | 6.94%   |
| 8.01-16.0 | 2         | 2.78%   |
| 0.51-1.0  | 1         | 1.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 47        | 66.2%   |
| 2       | 13        | 18.31%  |
| 3       | 6         | 8.45%   |
| 7       | 2         | 2.82%   |
| 6       | 1         | 1.41%   |
| 4       | 1         | 1.41%   |
| Unknown | 1         | 1.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 44        | 61.11%  |
| No        | 28        | 38.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 74.65%  |
| No        | 18        | 25.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 41        | 57.75%  |
| Yes       | 30        | 42.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Brazil       | 21        | 29.58%  |
| USA          | 11        | 15.49%  |
| Germany      | 5         | 7.04%   |
| Canada       | 4         | 5.63%   |
| South Africa | 3         | 4.23%   |
| Poland       | 3         | 4.23%   |
| Italy        | 3         | 4.23%   |
| France       | 3         | 4.23%   |
| Australia    | 3         | 4.23%   |
| Spain        | 2         | 2.82%   |
| Chile        | 2         | 2.82%   |
| Argentina    | 2         | 2.82%   |
| Sweden       | 1         | 1.41%   |
| Serbia       | 1         | 1.41%   |
| Russia       | 1         | 1.41%   |
| Romania      | 1         | 1.41%   |
| Mexico       | 1         | 1.41%   |
| India        | 1         | 1.41%   |
| Czechia      | 1         | 1.41%   |
| Croatia      | 1         | 1.41%   |
| Cameroon     | 1         | 1.41%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Curitiba                   | 3         | 4.17%   |
| Sao Paulo                  | 2         | 2.78%   |
| Belo Horizonte             | 2         | 2.78%   |
| Zagreb                     | 1         | 1.39%   |
| Zacatecas City             | 1         | 1.39%   |
| Winter Springs             | 1         | 1.39%   |
| Winston-Salem              | 1         | 1.39%   |
| Wiesbaden                  | 1         | 1.39%   |
| Warsaw                     | 1         | 1.39%   |
| Vila Velha                 | 1         | 1.39%   |
| Val-d'Or                   | 1         | 1.39%   |
| Taboao da Serra            | 1         | 1.39%   |
| Sydney                     | 1         | 1.39%   |
| Södertälje               | 1         | 1.39%   |
| Sidney                     | 1         | 1.39%   |
| Schweinfurt                | 1         | 1.39%   |
| Savona                     | 1         | 1.39%   |
| Santiago                   | 1         | 1.39%   |
| Santa Quiteria do Maranhao | 1         | 1.39%   |
| Salerno                    | 1         | 1.39%   |
| Saint-Germain-en-Laye      | 1         | 1.39%   |
| Rosario                    | 1         | 1.39%   |
| Rio de Janeiro             | 1         | 1.39%   |
| Recife                     | 1         | 1.39%   |
| Pretoria                   | 1         | 1.39%   |
| Porto Alegre               | 1         | 1.39%   |
| Port Elizabeth             | 1         | 1.39%   |
| Piraquara                  | 1         | 1.39%   |
| Paris                      | 1         | 1.39%   |
| Ostrava                    | 1         | 1.39%   |
| Newmarket                  | 1         | 1.39%   |
| Moscow Oblast              | 1         | 1.39%   |
| Moreno Valley              | 1         | 1.39%   |
| Montreal                   | 1         | 1.39%   |
| Massy                      | 1         | 1.39%   |
| Madrid                     | 1         | 1.39%   |
| Londrina                   | 1         | 1.39%   |
| Lipova                     | 1         | 1.39%   |
| Krakow                     | 1         | 1.39%   |
| Katowice                   | 1         | 1.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 21        | 25     | 20.79%  |
| Seagate             | 17        | 25     | 16.83%  |
| Samsung Electronics | 10        | 12     | 9.9%    |
| Kingston            | 8         | 9      | 7.92%   |
| Toshiba             | 7         | 7      | 6.93%   |
| Hitachi             | 7         | 8      | 6.93%   |
| SanDisk             | 5         | 7      | 4.95%   |
| Unknown             | 3         | 4      | 2.97%   |
| A-DATA Technology   | 3         | 4      | 2.97%   |
| Maxtor              | 2         | 2      | 1.98%   |
| LITEONIT            | 2         | 2      | 1.98%   |
| HGST                | 2         | 3      | 1.98%   |
| Crucial             | 2         | 2      | 1.98%   |
| XPG                 | 1         | 1      | 0.99%   |
| TO Exter            | 1         | 1      | 0.99%   |
| PNY                 | 1         | 1      | 0.99%   |
| Phison              | 1         | 1      | 0.99%   |
| Patriot             | 1         | 1      | 0.99%   |
| OWC                 | 1         | 1      | 0.99%   |
| OCZ                 | 1         | 1      | 0.99%   |
| Mushkin             | 1         | 1      | 0.99%   |
| Hewlett-Packard     | 1         | 1      | 0.99%   |
| GOODRAM             | 1         | 1      | 0.99%   |
| China               | 1         | 1      | 0.99%   |
| ASMT109x            | 1         | 1      | 0.99%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| WDC WD5000AAKX-001CA0 500GB              | 2         | 1.77%   |
| WDC WD10EZEX-08WN4A0 1TB                 | 2         | 1.77%   |
| Toshiba MQ01ABF050 500GB                 | 2         | 1.77%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 1.77%   |
| Kingston SV300S37A120G 120GB SSD         | 2         | 1.77%   |
| XPG GAMMIX S11 Pro 512GB                 | 1         | 0.88%   |
| WDC WD60EZRX-00MVLB1 6TB                 | 1         | 0.88%   |
| WDC WD5000LPVX-22V0TT0 500GB             | 1         | 0.88%   |
| WDC WD5000LPVT-24G33T1 500GB             | 1         | 0.88%   |
| WDC WD5000AACS-00G8B1 500GB              | 1         | 0.88%   |
| WDC WD400JD-55MSA1 40GB                  | 1         | 0.88%   |
| WDC WD4001FAEX-00MJRA0 4TB               | 1         | 0.88%   |
| WDC WD3200BPVT-22JJ5T0 320GB             | 1         | 0.88%   |
| WDC WD3200BEVT-80A0RT0 320GB             | 1         | 0.88%   |
| WDC WD2500BEVS-22UST0 250GB              | 1         | 0.88%   |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1         | 0.88%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1         | 0.88%   |
| WDC WD20EARS-00MVWB0 2TB                 | 1         | 0.88%   |
| WDC WD1200BEVS-75UST0 120GB              | 1         | 0.88%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 0.88%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 0.88%   |
| WDC WD10EAVS-00D7B1 1TB                  | 1         | 0.88%   |
| WDC WD10EARX-00N0YB0 1TB                 | 1         | 0.88%   |
| WDC WD1003FZEX-00MK2A0 1TB               | 1         | 0.88%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB SSD | 1         | 0.88%   |
| Unknown NVMe SSD Drive 512GB             | 1         | 0.88%   |
| Unknown MMC Card  8GB                    | 1         | 0.88%   |
| Unknown MMC Card  64GB                   | 1         | 0.88%   |
| Toshiba MQ01ACF050 500GB                 | 1         | 0.88%   |
| Toshiba MQ01ABF032 320GB                 | 1         | 0.88%   |
| Toshiba MQ01ABD050 500GB                 | 1         | 0.88%   |
| Toshiba MK5059GSXP 500GB                 | 1         | 0.88%   |
| Toshiba MK2561GSYN 250GB                 | 1         | 0.88%   |
| TO Exter nal USB 3.0 180GB               | 1         | 0.88%   |
| Seagate ST9320325AS 320GB                | 1         | 0.88%   |
| Seagate ST9160827AS 160GB                | 1         | 0.88%   |
| Seagate ST9160821AS 160GB                | 1         | 0.88%   |
| Seagate ST9160314AS 160GB                | 1         | 0.88%   |
| Seagate ST8000AS0002-1NA17Z 8TB          | 1         | 0.88%   |
| Seagate ST500LX012-SSHD-8GB              | 1         | 0.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 23     | 32.79%  |
| Seagate             | 17        | 25     | 27.87%  |
| Toshiba             | 7         | 7      | 11.48%  |
| Hitachi             | 7         | 8      | 11.48%  |
| Samsung Electronics | 5         | 6      | 8.2%    |
| Maxtor              | 2         | 2      | 3.28%   |
| HGST                | 2         | 3      | 3.28%   |
| ASMT109x            | 1         | 1      | 1.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 8      | 21.21%  |
| Samsung Electronics | 5         | 6      | 15.15%  |
| SanDisk             | 4         | 6      | 12.12%  |
| A-DATA Technology   | 3         | 4      | 9.09%   |
| LITEONIT            | 2         | 2      | 6.06%   |
| Crucial             | 2         | 2      | 6.06%   |
| WDC                 | 1         | 2      | 3.03%   |
| TO Exter            | 1         | 1      | 3.03%   |
| PNY                 | 1         | 1      | 3.03%   |
| Patriot             | 1         | 1      | 3.03%   |
| OWC                 | 1         | 1      | 3.03%   |
| OCZ                 | 1         | 1      | 3.03%   |
| Mushkin             | 1         | 1      | 3.03%   |
| Hewlett-Packard     | 1         | 1      | 3.03%   |
| GOODRAM             | 1         | 1      | 3.03%   |
| China               | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 50        | 75     | 56.82%  |
| SSD  | 31        | 39     | 35.23%  |
| NVMe | 5         | 6      | 5.68%   |
| MMC  | 2         | 2      | 2.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 69        | 111    | 87.34%  |
| NVMe | 5         | 6      | 6.33%   |
| SAS  | 3         | 3      | 3.8%    |
| MMC  | 2         | 2      | 2.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 64        | 82     | 72.73%  |
| 0.51-1.0   | 14        | 18     | 15.91%  |
| 1.01-2.0   | 5         | 7      | 5.68%   |
| 3.01-4.0   | 3         | 3      | 3.41%   |
| 10.01-20.0 | 1         | 2      | 1.14%   |
| 4.01-10.0  | 1         | 2      | 1.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 29        | 40.28%  |
| 251-500        | 19        | 26.39%  |
| 1001-2000      | 6         | 8.33%   |
| 51-100         | 5         | 6.94%   |
| 21-50          | 4         | 5.56%   |
| 501-1000       | 4         | 5.56%   |
| 2001-3000      | 2         | 2.78%   |
| 1-20           | 2         | 2.78%   |
| More than 3000 | 1         | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 33        | 45.21%  |
| 21-50     | 19        | 26.03%  |
| 101-250   | 6         | 8.22%   |
| 501-1000  | 6         | 8.22%   |
| 51-100    | 5         | 6.85%   |
| 251-500   | 3         | 4.11%   |
| 1001-2000 | 1         | 1.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD4001FAEX-00MJRA0 4TB                   | 1         | 1      | 20%     |
| Seagate ST500LT012-9WS142 500GB              | 1         | 1      | 20%     |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 20%     |
| Samsung Electronics HD081GJ 80GB             | 1         | 1      | 20%     |
| Hitachi HTS722012K9A300 120GB                | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 40%     |
| WDC                 | 1         | 1      | 20%     |
| Seagate             | 1         | 1      | 20%     |
| Hitachi             | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 25%     |
| Seagate             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |
| Hitachi             | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 80%     |
| SSD  | 1         | 1      | 20%     |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 65        | 100    | 85.53%  |
| Works    | 7         | 17     | 9.21%   |
| Malfunc  | 4         | 5      | 5.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 46        | 57.5%   |
| AMD                              | 20        | 25%     |
| ASMedia Technology               | 4         | 5%      |
| Silicon Integrated Systems [SiS] | 2         | 2.5%    |
| Nvidia                           | 2         | 2.5%    |
| ADATA Technology                 | 2         | 2.5%    |
| SanDisk                          | 1         | 1.25%   |
| Phison Electronics               | 1         | 1.25%   |
| LSI Logic / Symbios Logic        | 1         | 1.25%   |
| Kingston Technology Company      | 1         | 1.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 10        | 9.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 6         | 5.5%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 5.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 3.67%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 3.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 3.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 4         | 3.67%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4         | 3.67%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 2.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3         | 2.75%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 2.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3         | 2.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 2.75%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 3         | 2.75%   |
| AMD SB600 IDE                                                                           | 3         | 2.75%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 2.75%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 2         | 1.83%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 2         | 1.83%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 1.83%   |
| Nvidia MCP61 IDE                                                                        | 2         | 1.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 1.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.83%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 1.83%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 2         | 1.83%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 2         | 1.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.83%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2         | 1.83%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.92%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.92%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                                 | 1         | 0.92%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 0.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.92%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1         | 0.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 0.92%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 0.92%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1         | 0.92%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 0.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 0.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 57        | 63.33%  |
| IDE  | 25        | 27.78%  |
| NVMe | 5         | 5.56%   |
| RAID | 3         | 3.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 49        | 69.01%  |
| AMD    | 22        | 30.99%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD A4-5000 APU with Radeon HD Graphics     | 3         | 4.23%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 2.82%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 1.41%   |
| Intel Xeon CPU E7- 4870 @ 2.40GHz           | 1         | 1.41%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.41%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz      | 1         | 1.41%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.41%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 1.41%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 1.41%   |
| Intel Pentium CPU J2900 @ 2.41GHz           | 1         | 1.41%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1         | 1.41%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 1.41%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 1.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.41%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.41%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.41%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 1.41%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 1.41%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 1.41%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.41%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 1         | 1.41%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1.41%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.41%   |
| Intel Core i5-3570S CPU @ 3.10GHz           | 1         | 1.41%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.41%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 1         | 1.41%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.41%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.41%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.41%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.41%   |
| Intel Core i5-2500S CPU @ 2.70GHz           | 1         | 1.41%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.41%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 1.41%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 1.41%   |
| Intel Core i3-3227U CPU @ 1.90GHz           | 1         | 1.41%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1         | 1.41%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.41%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 1.41%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 1         | 1.41%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz        | 1         | 1.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 11        | 15.49%  |
| Intel Core i7           | 9         | 12.68%  |
| Intel Core i3           | 7         | 9.86%   |
| Intel Core 2 Duo        | 5         | 7.04%   |
| Intel Pentium Dual      | 4         | 5.63%   |
| Intel Pentium           | 4         | 5.63%   |
| AMD FX                  | 3         | 4.23%   |
| AMD A4                  | 3         | 4.23%   |
| Intel Xeon              | 2         | 2.82%   |
| Intel Celeron           | 2         | 2.82%   |
| Intel Atom              | 2         | 2.82%   |
| AMD Turion 64 X2 Mobile | 2         | 2.82%   |
| AMD Athlon 64 X2        | 2         | 2.82%   |
| AMD A8                  | 2         | 2.82%   |
| Intel Pentium Dual-Core | 1         | 1.41%   |
| Intel Core 2 Quad       | 1         | 1.41%   |
| Intel Celeron D         | 1         | 1.41%   |
| AMD Ryzen 9             | 1         | 1.41%   |
| AMD Ryzen 7             | 1         | 1.41%   |
| AMD Ryzen 5             | 1         | 1.41%   |
| AMD Ryzen 3             | 1         | 1.41%   |
| AMD Phenom              | 1         | 1.41%   |
| AMD Opteron             | 1         | 1.41%   |
| AMD Athlon II X4        | 1         | 1.41%   |
| AMD Athlon II X2        | 1         | 1.41%   |
| AMD A6                  | 1         | 1.41%   |
| AMD A10                 | 1         | 1.41%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 38        | 53.52%  |
| 4      | 22        | 30.99%  |
| 1      | 3         | 4.23%   |
| 12     | 2         | 2.82%   |
| 3      | 2         | 2.82%   |
| 40     | 1         | 1.41%   |
| 16     | 1         | 1.41%   |
| 8      | 1         | 1.41%   |
| 6      | 1         | 1.41%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 68        | 95.77%  |
| 2      | 2         | 2.82%   |
| 4      | 1         | 1.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 50.7%   |
| 2      | 35        | 49.3%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 71        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 19.72%  |
| 0x306a9    | 11        | 15.49%  |
| 0x6fd      | 6         | 8.45%   |
| 0x206a7    | 6         | 8.45%   |
| 0x806e9    | 3         | 4.23%   |
| 0x306c3    | 2         | 2.82%   |
| 0x30678    | 2         | 2.82%   |
| 0x20655    | 2         | 2.82%   |
| 0x0700010f | 2         | 2.82%   |
| 0x010000c8 | 2         | 2.82%   |
| 0xa0652    | 1         | 1.41%   |
| 0x806ea    | 1         | 1.41%   |
| 0x706a1    | 1         | 1.41%   |
| 0x506e3    | 1         | 1.41%   |
| 0x406c4    | 1         | 1.41%   |
| 0x40651    | 1         | 1.41%   |
| 0x306d4    | 1         | 1.41%   |
| 0x206f2    | 1         | 1.41%   |
| 0x206c2    | 1         | 1.41%   |
| 0x1067a    | 1         | 1.41%   |
| 0x10676    | 1         | 1.41%   |
| 0x10661    | 1         | 1.41%   |
| 0x08701013 | 1         | 1.41%   |
| 0x08108109 | 1         | 1.41%   |
| 0x07000106 | 1         | 1.41%   |
| 0x0600611a | 1         | 1.41%   |
| 0x06003106 | 1         | 1.41%   |
| 0x06000852 | 1         | 1.41%   |
| 0x0600063e | 1         | 1.41%   |
| 0x03000027 | 1         | 1.41%   |
| 0x01000095 | 1         | 1.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| IvyBridge     | 11        | 15.49%  |
| Core          | 7         | 9.86%   |
| SandyBridge   | 6         | 8.45%   |
| Penryn        | 5         | 7.04%   |
| Westmere      | 4         | 5.63%   |
| KabyLake      | 4         | 5.63%   |
| K8 Hammer     | 4         | 5.63%   |
| Haswell       | 4         | 5.63%   |
| Zen 2         | 3         | 4.23%   |
| Silvermont    | 3         | 4.23%   |
| Piledriver    | 3         | 4.23%   |
| K10           | 3         | 4.23%   |
| Jaguar        | 3         | 4.23%   |
| Bulldozer     | 2         | 2.82%   |
| Zen+          | 1         | 1.41%   |
| Steamroller   | 1         | 1.41%   |
| Skylake       | 1         | 1.41%   |
| K10 Llano     | 1         | 1.41%   |
| Goldmont plus | 1         | 1.41%   |
| Excavator     | 1         | 1.41%   |
| CometLake     | 1         | 1.41%   |
| Broadwell     | 1         | 1.41%   |
| Bonnell       | 1         | 1.41%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 38        | 46.91%  |
| AMD                              | 22        | 27.16%  |
| Nvidia                           | 17        | 20.99%  |
| Silicon Integrated Systems [SiS] | 2         | 2.47%   |
| Matrox Electronics Systems       | 2         | 2.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 8.33%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 5.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 3.57%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 3.57%   |
| Intel HD Graphics 620                                                                    | 3         | 3.57%   |
| AMD Kabini [Radeon HD 8330]                                                              | 3         | 3.57%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 2         | 2.38%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 2.38%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.38%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 2.38%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 2.38%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 2.38%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 2.38%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                                  | 2         | 2.38%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 1.19%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                                       | 1         | 1.19%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.19%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.19%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.19%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.19%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.19%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 1.19%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 1         | 1.19%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 1.19%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                    | 1         | 1.19%   |
| Nvidia GF110 [GeForce GTX 580]                                                           | 1         | 1.19%   |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1         | 1.19%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1         | 1.19%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 1.19%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.19%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.19%   |
| Intel HD Graphics 530                                                                    | 1         | 1.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.19%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.19%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.19%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.19%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.19%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 30        | 42.25%  |
| 1 x AMD         | 22        | 30.99%  |
| 1 x Nvidia      | 9         | 12.68%  |
| Intel + Nvidia  | 6         | 8.45%   |
| 1 x SiS         | 2         | 2.82%   |
| Nvidia + Matrox | 1         | 1.41%   |
| 1 x Matrox      | 1         | 1.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 60        | 83.33%  |
| Unknown     | 8         | 11.11%  |
| Proprietary | 4         | 5.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 58.9%   |
| 0.01-0.5   | 12        | 16.44%  |
| 1.01-2.0   | 7         | 9.59%   |
| 0.51-1.0   | 5         | 6.85%   |
| 3.01-4.0   | 3         | 4.11%   |
| 5.01-6.0   | 2         | 2.74%   |
| 2.01-3.0   | 1         | 1.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 11        | 16.18%  |
| AU Optronics            | 11        | 16.18%  |
| LG Display              | 8         | 11.76%  |
| Chimei Innolux          | 6         | 8.82%   |
| Goldstar                | 5         | 7.35%   |
| Acer                    | 5         | 7.35%   |
| BOE                     | 3         | 4.41%   |
| Philips                 | 2         | 2.94%   |
| Apple                   | 2         | 2.94%   |
| ViewSonic               | 1         | 1.47%   |
| Unknown                 | 1         | 1.47%   |
| Sony                    | 1         | 1.47%   |
| Sceptre Tech            | 1         | 1.47%   |
| Panasonic               | 1         | 1.47%   |
| NXP                     | 1         | 1.47%   |
| LG Philips              | 1         | 1.47%   |
| Lenovo                  | 1         | 1.47%   |
| Iiyama                  | 1         | 1.47%   |
| Hewlett-Packard         | 1         | 1.47%   |
| CPT                     | 1         | 1.47%   |
| Chi Mei Optoelectronics | 1         | 1.47%   |
| BenQ                    | 1         | 1.47%   |
| AOC                     | 1         | 1.47%   |
| Ancor Communications    | 1         | 1.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch           | 2         | 2.86%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch            | 2         | 2.86%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                    | 2         | 2.86%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch        | 2         | 2.86%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch          | 2         | 2.86%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch              | 1         | 1.43%   |
| Unknown LCD Monitor SHI LCD-TV 4640x1080                               | 1         | 1.43%   |
| Sony LCD Monitor AVSYSTEM                                              | 1         | 1.43%   |
| Sceptre Tech H32 SPT0CB8 1920x1080 575x323mm 26.0-inch                 | 1         | 1.43%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1         | 1.43%   |
| Samsung Electronics SyncMaster SAM0593 1920x1080 477x268mm 21.5-inch   | 1         | 1.43%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch   | 1         | 1.43%   |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch     | 1         | 1.43%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 509x286mm 23.0-inch     | 1         | 1.43%   |
| Samsung Electronics S/T 77/76DFX STN0006 1280x1024 312x234mm 15.4-inch | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch   | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch   | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch   | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch   | 1         | 1.43%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch   | 1         | 1.43%   |
| Philips 200V4 PHLC0BF 1600x900 432x240mm 19.5-inch                     | 1         | 1.43%   |
| Philips 170B PHL081D 1280x1024 338x270mm 17.0-inch                     | 1         | 1.43%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                     | 1         | 1.43%   |
| NXP OptiPlex 9010 NXP1111 1920x1080 510x286mm 23.0-inch                | 1         | 1.43%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch            | 1         | 1.43%   |
| LG Display LCD Monitor LGD03B7 1366x768 309x174mm 14.0-inch            | 1         | 1.43%   |
| LG Display LCD Monitor LGD03B3 1366x768 310x174mm 14.0-inch            | 1         | 1.43%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch            | 1         | 1.43%   |
| LG Display LCD Monitor LGD0251 1366x768 310x174mm 14.0-inch            | 1         | 1.43%   |
| Lenovo LEN T2454pA LEN60C9 1920x1200 518x324mm 24.1-inch               | 1         | 1.43%   |
| Iiyama PLX2481H IVM611D 1920x1080 520x290mm 23.4-inch                  | 1         | 1.43%   |
| Hewlett-Packard LE1851w HWP2840 1366x768 413x234mm 18.7-inch           | 1         | 1.43%   |
| Goldstar W2243 GSM56FF 1920x1080 477x268mm 21.5-inch                   | 1         | 1.43%   |
| Goldstar W1953 GSM4BA6 1360x768 406x229mm 18.4-inch                    | 1         | 1.43%   |
| Goldstar E2441 GSM581F 1920x1080 531x299mm 24.0-inch                   | 1         | 1.43%   |
| CPT LCD Monitor CPT13B1 1280x800 331x207mm 15.4-inch                   | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch        | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 1         | 1.43%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch        | 1         | 1.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 23        | 33.82%  |
| 1920x1080 (FHD)    | 17        | 25%     |
| 1600x900 (HD+)     | 6         | 8.82%   |
| 1280x800 (WXGA)    | 6         | 8.82%   |
| 1280x1024 (SXGA)   | 3         | 4.41%   |
| 3840x2160 (4K)     | 2         | 2.94%   |
| 2560x1440 (QHD)    | 2         | 2.94%   |
| 1680x1050 (WSXGA+) | 2         | 2.94%   |
| Unknown            | 2         | 2.94%   |
| 4640x1080          | 1         | 1.47%   |
| 2880x900           | 1         | 1.47%   |
| 1440x900 (WXGA+)   | 1         | 1.47%   |
| 1360x768           | 1         | 1.47%   |
| 1024x600           | 1         | 1.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 34.33%  |
| 14      | 8         | 11.94%  |
| 17      | 5         | 7.46%   |
| 23      | 4         | 5.97%   |
| 21      | 4         | 5.97%   |
| 18      | 4         | 5.97%   |
| 27      | 3         | 4.48%   |
| 20      | 3         | 4.48%   |
| 31      | 2         | 2.99%   |
| 24      | 2         | 2.99%   |
| 19      | 2         | 2.99%   |
| 13      | 2         | 2.99%   |
| Unknown | 2         | 2.99%   |
| 84      | 1         | 1.49%   |
| 22      | 1         | 1.49%   |
| 10      | 1         | 1.49%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 35        | 52.24%  |
| 401-500     | 14        | 20.9%   |
| 501-600     | 8         | 11.94%  |
| 601-700     | 3         | 4.48%   |
| 351-400     | 3         | 4.48%   |
| Unknown     | 2         | 2.99%   |
| 201-300     | 1         | 1.49%   |
| 1501-2000   | 1         | 1.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 50        | 76.92%  |
| 16/10   | 10        | 15.38%  |
| 5/4     | 2         | 3.08%   |
| Unknown | 2         | 3.08%   |
| 4/3     | 1         | 1.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 22        | 32.84%  |
| 81-90          | 10        | 14.93%  |
| 201-250        | 10        | 14.93%  |
| 141-150        | 6         | 8.96%   |
| 151-200        | 5         | 7.46%   |
| 301-350        | 3         | 4.48%   |
| 121-130        | 3         | 4.48%   |
| 351-500        | 2         | 2.99%   |
| Unknown        | 2         | 2.99%   |
| More than 1000 | 1         | 1.49%   |
| 41-50          | 1         | 1.49%   |
| 251-300        | 1         | 1.49%   |
| 111-120        | 1         | 1.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 28        | 43.08%  |
| 51-100  | 26        | 40%     |
| 121-160 | 9         | 13.85%  |
| Unknown | 2         | 3.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 61        | 85.92%  |
| 0     | 5         | 7.04%   |
| 2     | 4         | 5.63%   |
| 3     | 1         | 1.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 45        | 39.82%  |
| Qualcomm Atheros                  | 20        | 17.7%   |
| Intel                             | 15        | 13.27%  |
| Broadcom                          | 12        | 10.62%  |
| Broadcom Limited                  | 4         | 3.54%   |
| TP-Link                           | 2         | 1.77%   |
| Nvidia                            | 2         | 1.77%   |
| Marvell Technology Group          | 2         | 1.77%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.88%   |
| Samsung Electronics               | 1         | 0.88%   |
| Ralink                            | 1         | 0.88%   |
| Qualcomm                          | 1         | 0.88%   |
| NetGear                           | 1         | 0.88%   |
| Ericsson Business Mobile Networks | 1         | 0.88%   |
| D-Link                            | 1         | 0.88%   |
| CyberTAN Technology               | 1         | 0.88%   |
| AVM                               | 1         | 0.88%   |
| ASIX Electronics                  | 1         | 0.88%   |
| Accton Technology                 | 1         | 0.88%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 31        | 22.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 11        | 8.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 6         | 4.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 2.96%   |
| Realtek 802.11ac NIC                                                                  | 3         | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 3         | 2.22%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 3         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 2         | 1.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 1.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 2         | 1.48%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 1.48%   |
| Nvidia MCP61 Ethernet                                                                 | 2         | 1.48%   |
| Intel Wireless 7260                                                                   | 2         | 1.48%   |
| Intel Centrino Wireless-N 2230                                                        | 2         | 1.48%   |
| Intel 82579V Gigabit Network Connection                                               | 2         | 1.48%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                                | 2         | 1.48%   |
| Broadcom BCM4311 802.11b/g WLAN                                                       | 2         | 1.48%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                   | 1         | 0.74%   |
| TP-Link Archer T4U ver.3                                                              | 1         | 0.74%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                         | 1         | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                                         | 1         | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.74%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1         | 0.74%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.74%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                                  | 1         | 0.74%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.74%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.74%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                              | 1         | 0.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 0.74%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.74%   |
| Qualcomm Redmi 5 Plus                                                                 | 1         | 0.74%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.74%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                                 | 1         | 0.74%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 1         | 0.74%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.74%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                            | 1         | 0.74%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                                   | 1         | 0.74%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 1         | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Qualcomm Atheros                  | 19        | 32.2%   |
| Intel                             | 11        | 18.64%  |
| Realtek Semiconductor             | 10        | 16.95%  |
| Broadcom                          | 7         | 11.86%  |
| Broadcom Limited                  | 3         | 5.08%   |
| TP-Link                           | 2         | 3.39%   |
| Ralink                            | 1         | 1.69%   |
| NetGear                           | 1         | 1.69%   |
| Ericsson Business Mobile Networks | 1         | 1.69%   |
| D-Link                            | 1         | 1.69%   |
| CyberTAN Technology               | 1         | 1.69%   |
| AVM                               | 1         | 1.69%   |
| Accton Technology                 | 1         | 1.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 6         | 10%     |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 6.67%   |
| Realtek 802.11ac NIC                                                                  | 3         | 5%      |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 3         | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 3.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 3.33%   |
| Intel Wireless 7260                                                                   | 2         | 3.33%   |
| Intel Centrino Wireless-N 2230                                                        | 2         | 3.33%   |
| Broadcom BCM4311 802.11b/g WLAN                                                       | 2         | 3.33%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                                   | 1         | 1.67%   |
| TP-Link Archer T4U ver.3                                                              | 1         | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.67%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1         | 1.67%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 1.67%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                                  | 1         | 1.67%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 1.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.67%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.67%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                              | 1         | 1.67%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                             | 1         | 1.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.67%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.67%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                            | 1         | 1.67%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                                   | 1         | 1.67%   |
| Intel Wireless 8260                                                                   | 1         | 1.67%   |
| Intel Wireless 7265                                                                   | 1         | 1.67%   |
| Intel Wireless 3165                                                                   | 1         | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 1.67%   |
| Intel Centrino Ultimate-N 6300                                                        | 1         | 1.67%   |
| Intel Centrino Advanced-N 6235                                                        | 1         | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 1         | 1.67%   |
| Ericsson Business Mobile Networks N5321 gw                                            | 1         | 1.67%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]                         | 1         | 1.67%   |
| CyberTAN Siemens S30853-S1031-R351 802.11g Wireless Adapter [Atheros AR5523]          | 1         | 1.67%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                            | 1         | 1.67%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                                | 1         | 1.67%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                             | 1         | 1.67%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 1         | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 1.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 43        | 57.33%  |
| Intel                            | 9         | 12%     |
| Broadcom                         | 7         | 9.33%   |
| Qualcomm Atheros                 | 6         | 8%      |
| Nvidia                           | 2         | 2.67%   |
| Marvell Technology Group         | 2         | 2.67%   |
| Broadcom Limited                 | 2         | 2.67%   |
| Silicon Integrated Systems [SiS] | 1         | 1.33%   |
| Samsung Electronics              | 1         | 1.33%   |
| Qualcomm                         | 1         | 1.33%   |
| ASIX Electronics                 | 1         | 1.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 41.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 14.67%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4%      |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 2.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 2.67%   |
| Nvidia MCP61 Ethernet                                             | 2         | 2.67%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 2.67%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 2.67%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.33%   |
| Qualcomm Redmi 5 Plus                                             | 1         | 1.33%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.33%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.33%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.33%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.33%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.33%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.33%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.33%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.33%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 1.33%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.33%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.33%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.33%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.33%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.33%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 71        | 56.8%   |
| WiFi     | 54        | 43.2%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 38        | 52.05%  |
| WiFi     | 35        | 47.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 45        | 63.38%  |
| 1     | 22        | 30.99%  |
| 3     | 2         | 2.82%   |
| 4     | 1         | 1.41%   |
| 0     | 1         | 1.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 64        | 90.14%  |
| Yes  | 7         | 9.86%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 8         | 25%     |
| Intel                           | 6         | 18.75%  |
| Cambridge Silicon Radio         | 5         | 15.63%  |
| Lite-On Technology              | 3         | 9.38%   |
| Apple                           | 3         | 9.38%   |
| Realtek Semiconductor           | 2         | 6.25%   |
| Hewlett-Packard                 | 2         | 6.25%   |
| Ralink Technology               | 1         | 3.13%   |
| Integrated System Solution      | 1         | 3.13%   |
| Foxconn / Hon Hai               | 1         | 3.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 5         | 15.63%  |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 9.38%   |
| Intel Bluetooth wireless interface                          | 3         | 9.38%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 6.25%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 2         | 6.25%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 6.25%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 6.25%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 6.25%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                | 1         | 3.13%   |
| Qualcomm Atheros  Bluetooth Device                          | 1         | 3.13%   |
| Qualcomm Atheros Bluetooth USB Host Controller              | 1         | 3.13%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 3.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 3.13%   |
| Intel AX201 Bluetooth                                       | 1         | 3.13%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter       | 1         | 3.13%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 3.13%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 3.13%   |
| Foxconn / Hon Hai BCM20702A0                                | 1         | 3.13%   |
| Apple Bluetooth HCI                                         | 1         | 3.13%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 45        | 47.87%  |
| AMD                              | 25        | 26.6%   |
| Nvidia                           | 14        | 14.89%  |
| C-Media Electronics              | 3         | 3.19%   |
| Silicon Integrated Systems [SiS] | 2         | 2.13%   |
| Texas Instruments                | 1         | 1.06%   |
| Logitech                         | 1         | 1.06%   |
| Creative Technology              | 1         | 1.06%   |
| Creative Labs                    | 1         | 1.06%   |
| Corsair                          | 1         | 1.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 10%     |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 7.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 5.45%   |
| AMD FCH Azalia Controller                                                  | 6         | 5.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 4.55%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 3.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 3.64%   |
| AMD Kabini HDMI/DP Audio                                                   | 4         | 3.64%   |
| Nvidia GP106 High Definition Audio Controller                              | 3         | 2.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 2.73%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 2.73%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 2.73%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 1.82%   |
| Nvidia MCP61 High Definition Audio                                         | 2         | 1.82%   |
| Nvidia GF110 High Definition Audio Controller                              | 2         | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.82%   |
| C-Media Electronics Audio Adapter                                          | 2         | 1.82%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 1.82%   |
| Texas Instruments PCM2900 Audio Codec                                      | 1         | 0.91%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.91%   |
| Nvidia TU102 High Definition Audio Controller                              | 1         | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.91%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.91%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.91%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.91%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 0.91%   |
| Logitech Logitech USB Microphone                                           | 1         | 0.91%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.91%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 0.91%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.91%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.91%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 0.91%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 0.91%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.91%   |
| Creative Technology Sound BlasterX G1                                      | 1         | 0.91%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1         | 0.91%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Corsair             | 3         | 20%     |
| Unknown             | 2         | 13.33%  |
| SK hynix            | 2         | 13.33%  |
| Samsung Electronics | 2         | 13.33%  |
| Kingston            | 2         | 13.33%  |
| G.Skill             | 2         | 13.33%  |
| Smart               | 1         | 6.67%   |
| Elpida              | 1         | 6.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM SDRAM                     | 1         | 6.25%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 1         | 6.25%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                  | 1         | 6.25%   |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s   | 1         | 6.25%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 1         | 6.25%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s  | 1         | 6.25%   |
| Samsung RAM Module 8192MB DIMM DDR3 1333MT/s            | 1         | 6.25%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s    | 1         | 6.25%   |
| Kingston RAM KHX2400C11D3/8GX 8GB DIMM DDR3 2400MT/s    | 1         | 6.25%   |
| Kingston RAM 9905428-026.A00LF 2GB SODIMM DDR3 1066MT/s | 1         | 6.25%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s     | 1         | 6.25%   |
| G.Skill RAM F3-2400C10-8GTX 8GB DIMM DDR3 2400MT/s      | 1         | 6.25%   |
| Elpida RAM Module 8192MB DIMM DDR3 1333MT/s             | 1         | 6.25%   |
| Corsair RAM CMY8GX3M2C1600C9 4096MB DIMM DDR3 1600MT/s  | 1         | 6.25%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s   | 1         | 6.25%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s   | 1         | 6.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 6         | 50%     |
| DDR4    | 3         | 25%     |
| SDRAM   | 1         | 8.33%   |
| LPDDR4  | 1         | 8.33%   |
| Unknown | 1         | 8.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 7         | 58.33%  |
| SODIMM | 5         | 41.67%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 8192 | 7         | 50%     |
| 4096 | 3         | 21.43%  |
| 2048 | 3         | 21.43%  |
| 1024 | 1         | 7.14%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 3         | 21.43%  |
| 2400    | 2         | 14.29%  |
| 3466    | 1         | 7.14%   |
| 3266    | 1         | 7.14%   |
| 2667    | 1         | 7.14%   |
| 2133    | 1         | 7.14%   |
| 1333    | 1         | 7.14%   |
| 1066    | 1         | 7.14%   |
| 800     | 1         | 7.14%   |
| 667     | 1         | 7.14%   |
| Unknown | 1         | 7.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP LaserJet 3052       | 1         | 50%     |
| Brother HL-2130 series | 1         | 50%     |

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
| Chicony Electronics                    | 6         | 16.22%  |
| Suyin                                  | 5         | 13.51%  |
| Realtek Semiconductor                  | 4         | 10.81%  |
| Microdia                               | 4         | 10.81%  |
| IMC Networks                           | 3         | 8.11%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 8.11%   |
| Silicon Motion                         | 2         | 5.41%   |
| Apple                                  | 2         | 5.41%   |
| Syntek                                 | 1         | 2.7%    |
| Sunplus Innovation Technology          | 1         | 2.7%    |
| Ricoh                                  | 1         | 2.7%    |
| Quanta                                 | 1         | 2.7%    |
| Microsoft                              | 1         | 2.7%    |
| Logitech                               | 1         | 2.7%    |
| Lite-On Technology                     | 1         | 2.7%    |
| Hewlett-Packard                        | 1         | 2.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Microdia Laptop_Integrated_Webcam_HD                        | 2         | 5.41%   |
| Chicony HD WebCam                                           | 2         | 5.41%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 5.41%   |
| Syntek Lenovo EasyCamera                                    | 1         | 2.7%    |
| Suyin HP Webcam-50                                          | 1         | 2.7%    |
| Suyin HP Webcam-101                                         | 1         | 2.7%    |
| Suyin HP Integrated Webcam                                  | 1         | 2.7%    |
| Suyin Acer/Lenovo Webcam [CN0316]                           | 1         | 2.7%    |
| Suyin Acer CrystalEye Webcam                                | 1         | 2.7%    |
| Sunplus HD WebCam                                           | 1         | 2.7%    |
| Silicon Motion WebCam SCB-1100N                             | 1         | 2.7%    |
| Silicon Motion Web Camera                                   | 1         | 2.7%    |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 1         | 2.7%    |
| Realtek Lenovo EasyCamera                                   | 1         | 2.7%    |
| Realtek Laptop_Integrated_Webcam_HD                         | 1         | 2.7%    |
| Realtek Integrated_Webcam_HD                                | 1         | 2.7%    |
| Realtek Acer 640 x 480 laptop camera                        | 1         | 2.7%    |
| Quanta HD Webcam                                            | 1         | 2.7%    |
| Microsoft LifeCam HD-3000                                   | 1         | 2.7%    |
| Microdia Webcam Vitade AF                                   | 1         | 2.7%    |
| Microdia USB 2.0 Camera                                     | 1         | 2.7%    |
| Logitech QuickCam Pro 9000                                  | 1         | 2.7%    |
| Lite-On Integrated Camera                                   | 1         | 2.7%    |
| IMC Networks USB2.0 UVC VGA WebCam                          | 1         | 2.7%    |
| IMC Networks USB2.0 HD UVC WebCam                           | 1         | 2.7%    |
| IMC Networks Integrated Webcam                              | 1         | 2.7%    |
| HP Webcam 3100                                              | 1         | 2.7%    |
| Chicony USB2.0 HD UVC WebCam                                | 1         | 2.7%    |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 2.7%    |
| Chicony Integrated Camera                                   | 1         | 2.7%    |
| Chicony HP TrueVision HD Camera                             | 1         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 2.7%    |
| Apple FaceTime HD Camera (Built-in)                         | 1         | 2.7%    |
| Apple Built-in iSight                                       | 1         | 2.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 2         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Validity Sensors VFS491                      | 1         | 50%     |
| Validity Sensors VFS 5011 fingerprint sensor | 1         | 50%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 50        | 68.49%  |
| 1     | 22        | 30.14%  |
| 2     | 1         | 1.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Graphics card      | 10        | 40%     |
| Net/wireless       | 9         | 36%     |
| Fingerprint reader | 2         | 8%      |
| Chipcard           | 2         | 8%      |
| Storage            | 1         | 4%      |
| Network            | 1         | 4%      |

