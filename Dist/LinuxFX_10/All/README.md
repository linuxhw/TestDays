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

Total: 98

| Vendor     | Model                       | Form-Factor | Probe                                                      | Date         |
|------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| 5.4.0-72-generic            | 12        | 17.65%  |
| 5.4.0-52-generic            | 10        | 14.71%  |
| 5.6.15-windowsfx-10-generic | 8         | 11.76%  |
| 5.7.15-050715-generic       | 5         | 7.35%   |
| 5.5.19-050519-generic       | 4         | 5.88%   |
| 5.4.0-65-generic            | 4         | 5.88%   |
| 5.7.8-windowsfx-generic     | 3         | 4.41%   |
| 5.4.0-73-generic            | 3         | 4.41%   |
| 5.4.0-66-generic            | 3         | 4.41%   |
| 5.4.0-42-generic            | 3         | 4.41%   |
| 5.4.0-29-generic            | 3         | 4.41%   |
| 5.4.0-56-generic            | 2         | 2.94%   |
| 5.4.0-54-generic            | 2         | 2.94%   |
| 5.4.0-90-generic            | 1         | 1.47%   |
| 5.4.0-88-generic            | 1         | 1.47%   |
| 5.4.0-67-generic            | 1         | 1.47%   |
| 5.4.0-110-generic           | 1         | 1.47%   |
| 5.4.0-107-generic           | 1         | 1.47%   |
| 5.10.2-051002-generic       | 1         | 1.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 47        | 69.12%  |
| 5.6.15  | 8         | 11.76%  |
| 5.7.15  | 5         | 7.35%   |
| 5.5.19  | 4         | 5.88%   |
| 5.7.8   | 3         | 4.41%   |
| 5.10.2  | 1         | 1.47%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 47        | 69.12%  |
| 5.7     | 8         | 11.76%  |
| 5.6     | 8         | 11.76%  |
| 5.5     | 4         | 5.88%   |
| 5.10    | 1         | 1.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 68        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 54        | 79.41%  |
| KDE        | 8         | 11.76%  |
| Cinnamon   | 3         | 4.41%   |
| Unknown    | 2         | 2.94%   |
| KDE5       | 1         | 1.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 68        | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 40        | 58.82%  |
| SDDM    | 17        | 25%     |
| TDM     | 11        | 16.18%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| pt_BR | 20        | 29.41%  |
| en_US | 12        | 17.65%  |
| fr_FR | 4         | 5.88%   |
| de_DE | 4         | 5.88%   |
| pl_PL | 3         | 4.41%   |
| it_IT | 3         | 4.41%   |
| en_AU | 3         | 4.41%   |
| C     | 3         | 4.41%   |
| es_ES | 2         | 2.94%   |
| es_AR | 2         | 2.94%   |
| en_ZA | 2         | 2.94%   |
| en_CA | 2         | 2.94%   |
| sv_SE | 1         | 1.47%   |
| sr_RS | 1         | 1.47%   |
| ro_RO | 1         | 1.47%   |
| fr_CA | 1         | 1.47%   |
| es_MX | 1         | 1.47%   |
| es_CL | 1         | 1.47%   |
| en_IN | 1         | 1.47%   |
| cs_CZ | 1         | 1.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 46        | 67.65%  |
| EFI  | 22        | 32.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 65        | 95.59%  |
| Xfs     | 1         | 1.47%   |
| Overlay | 1         | 1.47%   |
| Btrfs   | 1         | 1.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 61        | 89.71%  |
| MBR     | 4         | 5.88%   |
| GPT     | 3         | 4.41%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 58        | 85.29%  |
| Yes       | 10        | 14.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 51        | 75%     |
| Yes       | 17        | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 14        | 20.59%  |
| Hewlett-Packard     | 9         | 13.24%  |
| Gigabyte Technology | 6         | 8.82%   |
| Acer                | 6         | 8.82%   |
| Lenovo              | 5         | 7.35%   |
| ASUSTek Computer    | 5         | 7.35%   |
| ASRock              | 4         | 5.88%   |
| MSI                 | 3         | 4.41%   |
| Apple               | 3         | 4.41%   |
| Samsung Electronics | 2         | 2.94%   |
| Intel               | 2         | 2.94%   |
| Toshiba             | 1         | 1.47%   |
| Supermicro          | 1         | 1.47%   |
| Positivo            | 1         | 1.47%   |
| Pegatron            | 1         | 1.47%   |
| PCWare              | 1         | 1.47%   |
| Olivetti            | 1         | 1.47%   |
| Medion              | 1         | 1.47%   |
| Jumper              | 1         | 1.47%   |
| ECS                 | 1         | 1.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell Vostro 1000                         | 2         | 2.94%   |
| Toshiba Satellite C50D-A-12R             | 1         | 1.47%   |
| Supermicro H8DG6/H8DGi                   | 1         | 1.47%   |
| Samsung 340XAA/350XAA/550XAA             | 1         | 1.47%   |
| Samsung 305E4A/305E5A/305E7A             | 1         | 1.47%   |
| Positivo Mobile                          | 1         | 1.47%   |
| Pegatron B34C                            | 1         | 1.47%   |
| PCWare IPMH61R2                          | 1         | 1.47%   |
| Olivetti P55-AEU-323-4G320               | 1         | 1.47%   |
| MSI MS-7B84                              | 1         | 1.47%   |
| MSI MS-7913                              | 1         | 1.47%   |
| MSI MS-7309                              | 1         | 1.47%   |
| Medion S4216                             | 1         | 1.47%   |
| Lenovo Y70-70 Touch 80DU                 | 1         | 1.47%   |
| Lenovo ThinkPad X1 Carbon 2nd F2G3H4J    | 1         | 1.47%   |
| Lenovo ThinkPad T450s 20BWS0YF00         | 1         | 1.47%   |
| Lenovo G550 2958                         | 1         | 1.47%   |
| Lenovo G505 20240                        | 1         | 1.47%   |
| Jumper Ezpad                             | 1         | 1.47%   |
| Intel DG31PR AAD97573-306                | 1         | 1.47%   |
| Intel B75                                | 1         | 1.47%   |
| HP ProBook 6560b                         | 1         | 1.47%   |
| HP Pavilion dv6700                       | 1         | 1.47%   |
| HP Mini 210-1000                         | 1         | 1.47%   |
| HP G42                                   | 1         | 1.47%   |
| HP EliteBook Folio 9470m                 | 1         | 1.47%   |
| HP Compaq Presario CQ50                  | 1         | 1.47%   |
| HP 250 G7 Notebook PC                    | 1         | 1.47%   |
| HP 250 G6 Notebook PC                    | 1         | 1.47%   |
| HP 202 G2 MT                             | 1         | 1.47%   |
| Gigabyte X570 UD                         | 1         | 1.47%   |
| Gigabyte P57V6                           | 1         | 1.47%   |
| Gigabyte GA-78LMT-S2P                    | 1         | 1.47%   |
| Gigabyte G31M-ES2C                       | 1         | 1.47%   |
| Gigabyte B450 AORUS M                    | 1         | 1.47%   |
| Gigabyte 970A-DS3P                       | 1         | 1.47%   |
| ECS A780GM-A                             | 1         | 1.47%   |
| Dell PowerEdge R810                      | 1         | 1.47%   |
| Dell OptiPlex 9010 AIO                   | 1         | 1.47%   |
| Dell OptiPlex 360                        | 1         | 1.47%   |
| Dell OptiPlex 3010                       | 1         | 1.47%   |
| Dell Latitude E6420                      | 1         | 1.47%   |
| Dell Inspiron 5423                       | 1         | 1.47%   |
| Dell Inspiron 3646                       | 1         | 1.47%   |
| Dell Inspiron 3520                       | 1         | 1.47%   |
| Dell Inspiron 3421                       | 1         | 1.47%   |
| Dell Inspiron 1525                       | 1         | 1.47%   |
| Dell Inspiron 1501                       | 1         | 1.47%   |
| Dell Inspiron 15-3567                    | 1         | 1.47%   |
| ASUS P8Z68-V LE                          | 1         | 1.47%   |
| ASUS K72Jr                               | 1         | 1.47%   |
| ASUS K50C                                | 1         | 1.47%   |
| ASUS ASUS TUF Gaming F15 FX506LI_FX506LI | 1         | 1.47%   |
| ASUS All Series                          | 1         | 1.47%   |
| ASRock N68-GE3 UCC                       | 1         | 1.47%   |
| ASRock ConRoe1333-D667                   | 1         | 1.47%   |
| ASRock B450M Steel Legend                | 1         | 1.47%   |
| ASRock 970 Extreme4                      | 1         | 1.47%   |
| Apple MacPro5,1                          | 1         | 1.47%   |
| Apple iMac8,1                            | 1         | 1.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell Inspiron              | 7         | 10.29%  |
| Acer Aspire                | 6         | 8.82%   |
| Dell OptiPlex              | 3         | 4.41%   |
| Lenovo ThinkPad            | 2         | 2.94%   |
| HP 250                     | 2         | 2.94%   |
| Dell Vostro                | 2         | 2.94%   |
| Toshiba Satellite          | 1         | 1.47%   |
| Supermicro H8DG6           | 1         | 1.47%   |
| Samsung 340XAA             | 1         | 1.47%   |
| Samsung 305E4A             | 1         | 1.47%   |
| Positivo Mobile            | 1         | 1.47%   |
| Pegatron B34C              | 1         | 1.47%   |
| PCWare IPMH61R2            | 1         | 1.47%   |
| Olivetti P55-AEU-323-4G320 | 1         | 1.47%   |
| MSI MS-7B84                | 1         | 1.47%   |
| MSI MS-7913                | 1         | 1.47%   |
| MSI MS-7309                | 1         | 1.47%   |
| Medion S4216               | 1         | 1.47%   |
| Lenovo Y70-70              | 1         | 1.47%   |
| Lenovo G550                | 1         | 1.47%   |
| Lenovo G505                | 1         | 1.47%   |
| Jumper Ezpad               | 1         | 1.47%   |
| Intel DG31PR               | 1         | 1.47%   |
| Intel B75                  | 1         | 1.47%   |
| HP ProBook                 | 1         | 1.47%   |
| HP Pavilion                | 1         | 1.47%   |
| HP Mini                    | 1         | 1.47%   |
| HP G42                     | 1         | 1.47%   |
| HP EliteBook               | 1         | 1.47%   |
| HP Compaq                  | 1         | 1.47%   |
| HP 202                     | 1         | 1.47%   |
| Gigabyte X570              | 1         | 1.47%   |
| Gigabyte P57V6             | 1         | 1.47%   |
| Gigabyte GA-78LMT-S2P      | 1         | 1.47%   |
| Gigabyte G31M-ES2C         | 1         | 1.47%   |
| Gigabyte B450              | 1         | 1.47%   |
| Gigabyte 970A-DS3P         | 1         | 1.47%   |
| ECS A780GM-A               | 1         | 1.47%   |
| Dell PowerEdge             | 1         | 1.47%   |
| Dell Latitude              | 1         | 1.47%   |
| ASUS P8Z68-V               | 1         | 1.47%   |
| ASUS K72Jr                 | 1         | 1.47%   |
| ASUS K50C                  | 1         | 1.47%   |
| ASUS ASUS                  | 1         | 1.47%   |
| ASUS All                   | 1         | 1.47%   |
| ASRock N68-GE3             | 1         | 1.47%   |
| ASRock ConRoe1333-D667     | 1         | 1.47%   |
| ASRock B450M               | 1         | 1.47%   |
| ASRock 970                 | 1         | 1.47%   |
| Apple MacPro5              | 1         | 1.47%   |
| Apple iMac8                | 1         | 1.47%   |
| Apple iMac12               | 1         | 1.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 8         | 11.76%  |
| 2011    | 8         | 11.76%  |
| 2014    | 7         | 10.29%  |
| 2012    | 7         | 10.29%  |
| 2009    | 6         | 8.82%   |
| 2018    | 5         | 7.35%   |
| 2008    | 5         | 7.35%   |
| 2010    | 4         | 5.88%   |
| 2007    | 4         | 5.88%   |
| 2019    | 3         | 4.41%   |
| 2015    | 3         | 4.41%   |
| 2006    | 3         | 4.41%   |
| 2017    | 2         | 2.94%   |
| 2020    | 1         | 1.47%   |
| 2016    | 1         | 1.47%   |
| Unknown | 1         | 1.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Notebook   | 39        | 57.35%  |
| Desktop    | 23        | 33.82%  |
| All in one | 3         | 4.41%   |
| Server     | 2         | 2.94%   |
| Tablet     | 1         | 1.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 67        | 97.1%   |
| Enabled  | 2         | 2.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 68        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 28        | 41.18%  |
| 4.01-8.0        | 13        | 19.12%  |
| 16.01-24.0      | 9         | 13.24%  |
| 8.01-16.0       | 6         | 8.82%   |
| 1.01-2.0        | 4         | 5.88%   |
| 32.01-64.0      | 3         | 4.41%   |
| 2.01-3.0        | 3         | 4.41%   |
| More than 256.0 | 1         | 1.47%   |
| 64.01-256.0     | 1         | 1.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 36        | 52.17%  |
| 2.01-3.0  | 14        | 20.29%  |
| 3.01-4.0  | 12        | 17.39%  |
| 4.01-8.0  | 4         | 5.8%    |
| 8.01-16.0 | 2         | 2.9%    |
| 0.51-1.0  | 1         | 1.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 46        | 67.65%  |
| 2       | 12        | 17.65%  |
| 3       | 6         | 8.82%   |
| 7       | 1         | 1.47%   |
| 6       | 1         | 1.47%   |
| 4       | 1         | 1.47%   |
| Unknown | 1         | 1.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 42        | 60.87%  |
| No        | 27        | 39.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 100%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 77.94%  |
| No        | 15        | 22.06%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 39        | 57.35%  |
| Yes       | 29        | 42.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Brazil       | 20        | 29.41%  |
| USA          | 11        | 16.18%  |
| Germany      | 4         | 5.88%   |
| Canada       | 4         | 5.88%   |
| South Africa | 3         | 4.41%   |
| Poland       | 3         | 4.41%   |
| Italy        | 3         | 4.41%   |
| France       | 3         | 4.41%   |
| Australia    | 3         | 4.41%   |
| Spain        | 2         | 2.94%   |
| Argentina    | 2         | 2.94%   |
| Sweden       | 1         | 1.47%   |
| Serbia       | 1         | 1.47%   |
| Russia       | 1         | 1.47%   |
| Romania      | 1         | 1.47%   |
| Mexico       | 1         | 1.47%   |
| India        | 1         | 1.47%   |
| Czechia      | 1         | 1.47%   |
| Croatia      | 1         | 1.47%   |
| Chile        | 1         | 1.47%   |
| Cameroon     | 1         | 1.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Curitiba                   | 3         | 4.35%   |
| Belo Horizonte             | 2         | 2.9%    |
| Zagreb                     | 1         | 1.45%   |
| Zacatecas City             | 1         | 1.45%   |
| Winter Springs             | 1         | 1.45%   |
| Winston-Salem              | 1         | 1.45%   |
| Warsaw                     | 1         | 1.45%   |
| Vila Velha                 | 1         | 1.45%   |
| Val-d'Or                   | 1         | 1.45%   |
| Taboao da Serra            | 1         | 1.45%   |
| Sydney                     | 1         | 1.45%   |
| Södertälje               | 1         | 1.45%   |
| Sidney                     | 1         | 1.45%   |
| Schweinfurt                | 1         | 1.45%   |
| Savona                     | 1         | 1.45%   |
| Sao Paulo                  | 1         | 1.45%   |
| Santa Quiteria do Maranhao | 1         | 1.45%   |
| Salerno                    | 1         | 1.45%   |
| Saint-Germain-en-Laye      | 1         | 1.45%   |
| Rosario                    | 1         | 1.45%   |
| Rio de Janeiro             | 1         | 1.45%   |
| Recife                     | 1         | 1.45%   |
| Pretoria                   | 1         | 1.45%   |
| Porto Alegre               | 1         | 1.45%   |
| Port Elizabeth             | 1         | 1.45%   |
| Piraquara                  | 1         | 1.45%   |
| Paris                      | 1         | 1.45%   |
| Ostrava                    | 1         | 1.45%   |
| Newmarket                  | 1         | 1.45%   |
| Moscow Oblast              | 1         | 1.45%   |
| Moreno Valley              | 1         | 1.45%   |
| Montreal                   | 1         | 1.45%   |
| Massy                      | 1         | 1.45%   |
| Madrid                     | 1         | 1.45%   |
| Londrina                   | 1         | 1.45%   |
| Lipova                     | 1         | 1.45%   |
| Krakow                     | 1         | 1.45%   |
| Katowice                   | 1         | 1.45%   |
| Karlsruhe                  | 1         | 1.45%   |
| Jundiaí                   | 1         | 1.45%   |
| Johannesburg               | 1         | 1.45%   |
| Itatiba                    | 1         | 1.45%   |
| Hobart                     | 1         | 1.45%   |
| Grand Falls                | 1         | 1.45%   |
| Eureka                     | 1         | 1.45%   |
| Embu                       | 1         | 1.45%   |
| East Stroudsburg           | 1         | 1.45%   |
| Douglas                    | 1         | 1.45%   |
| Coos Bay                   | 1         | 1.45%   |
| Cincinnati                 | 1         | 1.45%   |
| Central                    | 1         | 1.45%   |
| Carbonia                   | 1         | 1.45%   |
| Cabo Frio                  | 1         | 1.45%   |
| Bueu                       | 1         | 1.45%   |
| Bonabeerie                 | 1         | 1.45%   |
| Bochum                     | 1         | 1.45%   |
| Bhopal                     | 1         | 1.45%   |
| Bella Vista                | 1         | 1.45%   |
| Belgrade                   | 1         | 1.45%   |
| Belém                     | 1         | 1.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 21     | 18.95%  |
| Seagate             | 16        | 22     | 16.84%  |
| Samsung Electronics | 8         | 9      | 8.42%   |
| Kingston            | 8         | 9      | 8.42%   |
| Toshiba             | 7         | 7      | 7.37%   |
| Hitachi             | 7         | 8      | 7.37%   |
| SanDisk             | 5         | 7      | 5.26%   |
| Unknown             | 3         | 4      | 3.16%   |
| A-DATA Technology   | 3         | 4      | 3.16%   |
| MAXTOR              | 2         | 2      | 2.11%   |
| LITEONIT            | 2         | 2      | 2.11%   |
| HGST                | 2         | 3      | 2.11%   |
| Crucial             | 2         | 2      | 2.11%   |
| XPG                 | 1         | 1      | 1.05%   |
| TO Exter            | 1         | 1      | 1.05%   |
| PNY                 | 1         | 1      | 1.05%   |
| Phison              | 1         | 1      | 1.05%   |
| Patriot             | 1         | 1      | 1.05%   |
| OWC                 | 1         | 1      | 1.05%   |
| OCZ                 | 1         | 1      | 1.05%   |
| Mushkin             | 1         | 1      | 1.05%   |
| Hewlett-Packard     | 1         | 1      | 1.05%   |
| GOODRAM             | 1         | 1      | 1.05%   |
| China               | 1         | 1      | 1.05%   |
| ASMT109x            | 1         | 1      | 1.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 1.94%   |
| Toshiba MQ01ABF050 500GB             | 2         | 1.94%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 1.94%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 1.94%   |
| XPG GAMMIX S11 Pro 256GB             | 1         | 0.97%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.97%   |
| WDC WD5000LPVT-24G33T1 500GB         | 1         | 0.97%   |
| WDC WD5000AAKX-001CA0 500GB          | 1         | 0.97%   |
| WDC WD5000AACS-00G8B1 500GB          | 1         | 0.97%   |
| WDC WD400JD-55MSA1 40GB              | 1         | 0.97%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.97%   |
| WDC WD3200BEVT-80A0RT0 320GB         | 1         | 0.97%   |
| WDC WD2500BEVS-22UST0 250GB          | 1         | 0.97%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 0.97%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 0.97%   |
| WDC WD1200BEVS-75UST0 120GB          | 1         | 0.97%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.97%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.97%   |
| WDC WD10EAVS-00D7B1 1TB              | 1         | 0.97%   |
| WDC WD10EARX-00N0YB0 1TB             | 1         | 0.97%   |
| WDC WD1003FZEX-00MK2A0 1TB           | 1         | 0.97%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB | 1         | 0.97%   |
| Unknown NVMe SSD Drive 512GB         | 1         | 0.97%   |
| Unknown MMC Card  8GB                | 1         | 0.97%   |
| Unknown MMC Card  64GB               | 1         | 0.97%   |
| Toshiba MQ01ACF050 500GB             | 1         | 0.97%   |
| Toshiba MQ01ABF032 320GB             | 1         | 0.97%   |
| Toshiba MQ01ABD050 500GB             | 1         | 0.97%   |
| Toshiba MK5059GSXP 500GB             | 1         | 0.97%   |
| Toshiba MK2561GSYN 250GB             | 1         | 0.97%   |
| TO Exter nal USB 3.0 320GB           | 1         | 0.97%   |
| Seagate ST9320325AS 320GB            | 1         | 0.97%   |
| Seagate ST9160827AS 160GB            | 1         | 0.97%   |
| Seagate ST9160821AS 160GB            | 1         | 0.97%   |
| Seagate ST9160314AS 160GB            | 1         | 0.97%   |
| Seagate ST500LX012-SSHD-8GB          | 1         | 0.97%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 0.97%   |
| Seagate ST500LM021-1KJ152 500GB      | 1         | 0.97%   |
| Seagate ST500DM002-1BD142 500GB      | 1         | 0.97%   |
| Seagate ST4000DM004-2CV104 4TB       | 1         | 0.97%   |
| Seagate ST3200826AS 200GB            | 1         | 0.97%   |
| Seagate ST32000645NS 2TB             | 1         | 0.97%   |
| Seagate ST3160318AS 160GB            | 1         | 0.97%   |
| Seagate ST3160215A 160GB             | 1         | 0.97%   |
| Seagate ST31500341AS 1TB             | 1         | 0.97%   |
| Seagate ST250DM000-1BD141 250GB      | 1         | 0.97%   |
| Seagate ST2000DM001-1CH164 2TB       | 1         | 0.97%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 0.97%   |
| Seagate ST1000DM003-1CH162 1TB       | 1         | 0.97%   |
| Seagate Expansion Desk 10TB          | 1         | 0.97%   |
| SanDisk X400 2.5 7MM 256GB SSD       | 1         | 0.97%   |
| SanDisk Ultra II 480GB SSD           | 1         | 0.97%   |
| SanDisk SSD PLUS 1000GB              | 1         | 0.97%   |
| SanDisk SDSSDHII240G 240GB           | 1         | 0.97%   |
| SanDisk SD9SN8W256G1002 256GB SSD    | 1         | 0.97%   |
| Sandisk NVMe SSD Drive 500GB         | 1         | 0.97%   |
| Samsung SSD SM841 2.5 7mm 128GB      | 1         | 0.97%   |
| Samsung SSD 850 EVO 500GB            | 1         | 0.97%   |
| Samsung SSD 850 EVO 250GB            | 1         | 0.97%   |
| Samsung MZMPC032HBCD-000D1 32GB SSD  | 1         | 0.97%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 19     | 30.36%  |
| Seagate             | 16        | 22     | 28.57%  |
| Toshiba             | 7         | 7      | 12.5%   |
| Hitachi             | 7         | 8      | 12.5%   |
| Samsung Electronics | 4         | 5      | 7.14%   |
| MAXTOR              | 2         | 2      | 3.57%   |
| HGST                | 2         | 3      | 3.57%   |
| ASMT109x            | 1         | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 7         | 8      | 21.88%  |
| SanDisk             | 4         | 6      | 12.5%   |
| Samsung Electronics | 4         | 4      | 12.5%   |
| A-DATA Technology   | 3         | 4      | 9.38%   |
| LITEONIT            | 2         | 2      | 6.25%   |
| Crucial             | 2         | 2      | 6.25%   |
| WDC                 | 1         | 2      | 3.13%   |
| TO Exter            | 1         | 1      | 3.13%   |
| PNY                 | 1         | 1      | 3.13%   |
| Patriot             | 1         | 1      | 3.13%   |
| OWC                 | 1         | 1      | 3.13%   |
| OCZ                 | 1         | 1      | 3.13%   |
| Mushkin             | 1         | 1      | 3.13%   |
| Hewlett-Packard     | 1         | 1      | 3.13%   |
| GOODRAM             | 1         | 1      | 3.13%   |
| China               | 1         | 1      | 3.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 47        | 67     | 55.95%  |
| SSD  | 30        | 37     | 35.71%  |
| NVMe | 5         | 6      | 5.95%   |
| MMC  | 2         | 2      | 2.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 66        | 101    | 86.84%  |
| NVMe | 5         | 6      | 6.58%   |
| SAS  | 3         | 3      | 3.95%   |
| MMC  | 2         | 2      | 2.63%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 62        | 80     | 77.5%   |
| 0.51-1.0   | 12        | 16     | 15%     |
| 1.01-2.0   | 3         | 5      | 3.75%   |
| 3.01-4.0   | 2         | 2      | 2.5%    |
| 4.01-10.0  | 1         | 1      | 1.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 28        | 40.58%  |
| 251-500        | 19        | 27.54%  |
| 1001-2000      | 5         | 7.25%   |
| 51-100         | 5         | 7.25%   |
| 21-50          | 4         | 5.8%    |
| 501-1000       | 4         | 5.8%    |
| 1-20           | 2         | 2.9%    |
| More than 3000 | 1         | 1.45%   |
| 2001-3000      | 1         | 1.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 33        | 47.14%  |
| 21-50    | 19        | 27.14%  |
| 101-250  | 5         | 7.14%   |
| 501-1000 | 5         | 7.14%   |
| 51-100   | 5         | 7.14%   |
| 251-500  | 3         | 4.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB  | 1         | 1      | 33.33%  |
| Samsung Electronics HD081GJ 80GB | 1         | 1      | 33.33%  |
| Hitachi HTS722012K9A300 120GB    | 1         | 1      | 33.33%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| Hitachi             | 1         | 1      | 33.33%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| Hitachi             | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 100%    |

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
| Detected | 63        | 97     | 87.5%   |
| Works    | 6         | 12     | 8.33%   |
| Malfunc  | 3         | 3      | 4.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 45        | 59.21%  |
| AMD                              | 18        | 23.68%  |
| ASMedia Technology               | 3         | 3.95%   |
| Silicon Integrated Systems [SiS] | 2         | 2.63%   |
| Nvidia                           | 2         | 2.63%   |
| ADATA Technology                 | 2         | 2.63%   |
| Sandisk                          | 1         | 1.32%   |
| Phison Electronics               | 1         | 1.32%   |
| LSI Logic / Symbios Logic        | 1         | 1.32%   |
| Kingston Technology Company      | 1         | 1.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 9         | 8.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 6         | 5.83%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5         | 4.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 4         | 3.88%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 4         | 3.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 3.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 4         | 3.88%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 2.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 3         | 2.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 3         | 2.91%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 2.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 2.91%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 3         | 2.91%   |
| AMD SB600 IDE                                                                           | 3         | 2.91%   |
| AMD 400 Series Chipset SATA Controller                                                  | 3         | 2.91%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                             | 2         | 1.94%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 2         | 1.94%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 1.94%   |
| Nvidia MCP61 IDE                                                                        | 2         | 1.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 1.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 2         | 1.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 2         | 1.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 2         | 1.94%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 2         | 1.94%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 2         | 1.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 1.94%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 2         | 1.94%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 1         | 0.97%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 1         | 0.97%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                                 | 1         | 0.97%   |
| Kingston Company Company Non-Volatile memory controller                                 | 1         | 0.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.97%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 1         | 0.97%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 1         | 0.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 1         | 0.97%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 1         | 0.97%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 1         | 0.97%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 1         | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 1         | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 1         | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1         | 0.97%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 1         | 0.97%   |
| ASMedia 106x SATA/RAID Controller                                                       | 1         | 0.97%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 1         | 0.97%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 54        | 62.79%  |
| IDE  | 24        | 27.91%  |
| NVMe | 5         | 5.81%   |
| RAID | 3         | 3.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 48        | 70.59%  |
| AMD    | 20        | 29.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD A4-5000 APU with Radeon HD Graphics     | 3         | 4.41%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 2.94%   |
| Intel Xeon CPU X5680 @ 3.33GHz              | 1         | 1.47%   |
| Intel Xeon CPU E7- 4870 @ 2.40GHz           | 1         | 1.47%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 1.47%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz      | 1         | 1.47%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz      | 1         | 1.47%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz      | 1         | 1.47%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz      | 1         | 1.47%   |
| Intel Pentium CPU J2900 @ 2.41GHz           | 1         | 1.47%   |
| Intel Pentium CPU G3250 @ 3.20GHz           | 1         | 1.47%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 1.47%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 1.47%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.47%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 1.47%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 1         | 1.47%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 1         | 1.47%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 1.47%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.47%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 1.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 1         | 1.47%   |
| Intel Core i5-3570S CPU @ 3.10GHz           | 1         | 1.47%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 1         | 1.47%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 1         | 1.47%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 1         | 1.47%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 1         | 1.47%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 1         | 1.47%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.47%   |
| Intel Core i5-2500S CPU @ 2.70GHz           | 1         | 1.47%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.47%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 1         | 1.47%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 1         | 1.47%   |
| Intel Core i3-3227U CPU @ 1.90GHz           | 1         | 1.47%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 1         | 1.47%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 1         | 1.47%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 1         | 1.47%   |
| Intel Core 2 Quad CPU Q8300 @ 2.50GHz       | 1         | 1.47%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz        | 1         | 1.47%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 1         | 1.47%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 1         | 1.47%   |
| Intel Core 2 Duo CPU E8135 @ 2.40GHz        | 1         | 1.47%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 1         | 1.47%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.47%   |
| Intel Celeron D CPU 220 @ 1.20GHz           | 1         | 1.47%   |
| Intel Celeron CPU N2940 @ 1.83GHz           | 1         | 1.47%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 1         | 1.47%   |
| Intel Atom CPU N450 @ 1.66GHz               | 1         | 1.47%   |
| AMD Turion 64 X2 Mobile Technology TL-60    | 1         | 1.47%   |
| AMD Turion 64 X2 Mobile Technology TL-56    | 1         | 1.47%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1         | 1.47%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 1         | 1.47%   |
| AMD Ryzen 5 3600 6-Core Processor           | 1         | 1.47%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 1         | 1.47%   |
| AMD Phenom 9650 Quad-Core Processor         | 1         | 1.47%   |
| AMD Opteron Processor 6272                  | 1         | 1.47%   |
| AMD FX-8320 Eight-Core Processor            | 1         | 1.47%   |
| AMD FX-6300 Six-Core Processor              | 1         | 1.47%   |
| AMD Athlon II X4 640 Processor              | 1         | 1.47%   |
| AMD Athlon II X2 260 Processor              | 1         | 1.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 11        | 16.18%  |
| Intel Core i7           | 8         | 11.76%  |
| Intel Core i3           | 7         | 10.29%  |
| Intel Core 2 Duo        | 5         | 7.35%   |
| Intel Pentium Dual      | 4         | 5.88%   |
| Intel Pentium           | 4         | 5.88%   |
| AMD A4                  | 3         | 4.41%   |
| Intel Xeon              | 2         | 2.94%   |
| Intel Celeron           | 2         | 2.94%   |
| Intel Atom              | 2         | 2.94%   |
| AMD Turion 64 X2 Mobile | 2         | 2.94%   |
| AMD FX                  | 2         | 2.94%   |
| AMD Athlon 64 X2        | 2         | 2.94%   |
| Intel Pentium Dual-Core | 1         | 1.47%   |
| Intel Core 2 Quad       | 1         | 1.47%   |
| Intel Celeron D         | 1         | 1.47%   |
| AMD Ryzen 9             | 1         | 1.47%   |
| AMD Ryzen 7             | 1         | 1.47%   |
| AMD Ryzen 5             | 1         | 1.47%   |
| AMD Ryzen 3             | 1         | 1.47%   |
| AMD Phenom              | 1         | 1.47%   |
| AMD Opteron             | 1         | 1.47%   |
| AMD Athlon II X4        | 1         | 1.47%   |
| AMD Athlon II X2        | 1         | 1.47%   |
| AMD A8                  | 1         | 1.47%   |
| AMD A6                  | 1         | 1.47%   |
| AMD A10                 | 1         | 1.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 37        | 54.41%  |
| 4      | 21        | 30.88%  |
| 1      | 3         | 4.41%   |
| 12     | 2         | 2.94%   |
| 40     | 1         | 1.47%   |
| 16     | 1         | 1.47%   |
| 8      | 1         | 1.47%   |
| 6      | 1         | 1.47%   |
| 3      | 1         | 1.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 65        | 95.59%  |
| 2      | 2         | 2.94%   |
| 4      | 1         | 1.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 36        | 52.94%  |
| 2      | 32        | 47.06%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 68        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 20.59%  |
| 0x306a9    | 10        | 14.71%  |
| 0x6fd      | 6         | 8.82%   |
| 0x206a7    | 6         | 8.82%   |
| 0x806e9    | 3         | 4.41%   |
| 0x306c3    | 2         | 2.94%   |
| 0x30678    | 2         | 2.94%   |
| 0x20655    | 2         | 2.94%   |
| 0x0700010f | 2         | 2.94%   |
| 0x010000c8 | 2         | 2.94%   |
| 0xa0652    | 1         | 1.47%   |
| 0x806ea    | 1         | 1.47%   |
| 0x706a1    | 1         | 1.47%   |
| 0x506e3    | 1         | 1.47%   |
| 0x406c4    | 1         | 1.47%   |
| 0x40651    | 1         | 1.47%   |
| 0x306d4    | 1         | 1.47%   |
| 0x206f2    | 1         | 1.47%   |
| 0x206c2    | 1         | 1.47%   |
| 0x1067a    | 1         | 1.47%   |
| 0x10676    | 1         | 1.47%   |
| 0x10661    | 1         | 1.47%   |
| 0x08701013 | 1         | 1.47%   |
| 0x08108109 | 1         | 1.47%   |
| 0x07000106 | 1         | 1.47%   |
| 0x06003106 | 1         | 1.47%   |
| 0x06000852 | 1         | 1.47%   |
| 0x03000027 | 1         | 1.47%   |
| 0x01000095 | 1         | 1.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| IvyBridge     | 10        | 14.71%  |
| Core          | 7         | 10.29%  |
| SandyBridge   | 6         | 8.82%   |
| Penryn        | 5         | 7.35%   |
| Westmere      | 4         | 5.88%   |
| KabyLake      | 4         | 5.88%   |
| K8 Hammer     | 4         | 5.88%   |
| Haswell       | 4         | 5.88%   |
| Zen 2         | 3         | 4.41%   |
| Silvermont    | 3         | 4.41%   |
| Piledriver    | 3         | 4.41%   |
| K10           | 3         | 4.41%   |
| Jaguar        | 3         | 4.41%   |
| Zen+          | 1         | 1.47%   |
| Steamroller   | 1         | 1.47%   |
| Skylake       | 1         | 1.47%   |
| K10 Llano     | 1         | 1.47%   |
| Goldmont plus | 1         | 1.47%   |
| CometLake     | 1         | 1.47%   |
| Bulldozer     | 1         | 1.47%   |
| Broadwell     | 1         | 1.47%   |
| Bonnell       | 1         | 1.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 38        | 48.72%  |
| AMD                              | 20        | 25.64%  |
| Nvidia                           | 16        | 20.51%  |
| Silicon Integrated Systems [SiS] | 2         | 2.56%   |
| Matrox Electronics Systems       | 2         | 2.56%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 8.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 6.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 3.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 3.7%    |
| Intel HD Graphics 620                                                                    | 3         | 3.7%    |
| AMD Kabini [Radeon HD 8330]                                                              | 3         | 3.7%    |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 2         | 2.47%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 2         | 2.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 2.47%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 2.47%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 2.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 2.47%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 2         | 2.47%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 2         | 2.47%   |
| AMD RS482M [Mobility Radeon Xpress 200]                                                  | 2         | 2.47%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 1.23%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                                       | 1         | 1.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 1.23%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 1         | 1.23%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 1         | 1.23%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1.23%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 1.23%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 1.23%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 1.23%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 1         | 1.23%   |
| Nvidia GF119M [NVS 4200M]                                                                | 1         | 1.23%   |
| Nvidia GF116 [GeForce GTS 450 Rev. 2]                                                    | 1         | 1.23%   |
| Nvidia GF110 [GeForce GTX 580]                                                           | 1         | 1.23%   |
| Nvidia GF110 [GeForce GTX 570]                                                           | 1         | 1.23%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 1         | 1.23%   |
| Nvidia G84M [GeForce 8600M GT]                                                           | 1         | 1.23%   |
| Intel UHD Graphics 620                                                                   | 1         | 1.23%   |
| Intel HD Graphics 5500                                                                   | 1         | 1.23%   |
| Intel HD Graphics 530                                                                    | 1         | 1.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 1         | 1.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 1         | 1.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1.23%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1.23%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 1         | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 1.23%   |
| AMD Whistler [Radeon HD 6730M/6770M/7690M XT]                                            | 1         | 1.23%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                                        | 1         | 1.23%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 1.23%   |
| AMD RV630/M76 [Mobility Radeon HD 2600 XT/2700]                                          | 1         | 1.23%   |
| AMD RV630 PRO [Radeon HD 2600 PRO]                                                       | 1         | 1.23%   |
| AMD RV610 [Radeon HD 2400 PRO]                                                           | 1         | 1.23%   |
| AMD RS482/RS485 [Radeon Xpress 1100/1150]                                                | 1         | 1.23%   |
| AMD Richland [Radeon HD 8570D]                                                           | 1         | 1.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 1         | 1.23%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 1.23%   |
| AMD Kaveri [Radeon R6 Graphics]                                                          | 1         | 1.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 1         | 1.23%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 1         | 1.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 30        | 44.12%  |
| 1 x AMD         | 20        | 29.41%  |
| 1 x Nvidia      | 8         | 11.76%  |
| Intel + Nvidia  | 6         | 8.82%   |
| 1 x SiS         | 2         | 2.94%   |
| Nvidia + Matrox | 1         | 1.47%   |
| 1 x Matrox      | 1         | 1.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 58        | 84.06%  |
| Unknown     | 8         | 11.59%  |
| Proprietary | 3         | 4.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 43        | 61.43%  |
| 0.01-0.5   | 11        | 15.71%  |
| 1.01-2.0   | 6         | 8.57%   |
| 0.51-1.0   | 5         | 7.14%   |
| 3.01-4.0   | 3         | 4.29%   |
| 5.01-6.0   | 1         | 1.43%   |
| 2.01-3.0   | 1         | 1.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 11        | 16.92%  |
| Samsung Electronics     | 10        | 15.38%  |
| LG Display              | 8         | 12.31%  |
| Chimei Innolux          | 6         | 9.23%   |
| Goldstar                | 5         | 7.69%   |
| Acer                    | 5         | 7.69%   |
| BOE                     | 3         | 4.62%   |
| Philips                 | 2         | 3.08%   |
| Apple                   | 2         | 3.08%   |
| ViewSonic               | 1         | 1.54%   |
| Unknown                 | 1         | 1.54%   |
| Sony                    | 1         | 1.54%   |
| Sceptre Tech            | 1         | 1.54%   |
| NXP                     | 1         | 1.54%   |
| LG Philips              | 1         | 1.54%   |
| Lenovo                  | 1         | 1.54%   |
| Iiyama                  | 1         | 1.54%   |
| Hewlett-Packard         | 1         | 1.54%   |
| CPT                     | 1         | 1.54%   |
| Chi Mei Optoelectronics | 1         | 1.54%   |
| BenQ                    | 1         | 1.54%   |
| Ancor Communications    | 1         | 1.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 2         | 2.99%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 2.99%   |
| Goldstar W2043 GSM4E9D 1600x900 443x249mm 20.0-inch                      | 2         | 2.99%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch          | 2         | 2.99%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch            | 2         | 2.99%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch                | 1         | 1.49%   |
| Unknown LCD Monitor SHI LCD-TV 4640x1080                                 | 1         | 1.49%   |
| Sony LCD Monitor AVSYSTEM                                                | 1         | 1.49%   |
| Sceptre Tech X325BV-FMQR SPT0CB8 1920x1080 700x390mm 31.5-inch           | 1         | 1.49%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch        | 1         | 1.49%   |
| Samsung Electronics SyncMaster SAM0593 1920x1080 477x268mm 21.5-inch     | 1         | 1.49%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch     | 1         | 1.49%   |
| Samsung Electronics SMBX2331 SAM076F 1920x1080 509x286mm 23.0-inch       | 1         | 1.49%   |
| Samsung Electronics S/T 77/76DFX STN0006 1280x1024 312x234mm 15.4-inch   | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch     | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 1         | 1.49%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 1         | 1.49%   |
| Philips LCD Monitor PHLC0BF 1600x900 430x240mm 19.4-inch                 | 1         | 1.49%   |
| Philips 170B PHL081D 1280x1024 338x270mm 17.0-inch                       | 1         | 1.49%   |
| NXP OptiPlex 9010 NXP1111 1920x1080 510x286mm 23.0-inch                  | 1         | 1.49%   |
| LG Philips LCD Monitor LPLA900 1280x800 331x207mm 15.4-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD03B7 1366x768 309x174mm 14.0-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD03B3 1366x768 309x174mm 14.0-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch              | 1         | 1.49%   |
| LG Display LCD Monitor LGD0251 1366x768 310x174mm 14.0-inch              | 1         | 1.49%   |
| Lenovo LEN T2454pA LEN60C9 1920x1200 518x324mm 24.1-inch                 | 1         | 1.49%   |
| Iiyama PLX2481H IVM611D 1920x1080 521x293mm 23.5-inch                    | 1         | 1.49%   |
| Hewlett-Packard LE1851w HWP2840 1366x768 413x234mm 18.7-inch             | 1         | 1.49%   |
| Goldstar W2243 GSM56FF 1920x1080 477x269mm 21.6-inch                     | 1         | 1.49%   |
| Goldstar W1953 GSM4BA6 1360x768 406x229mm 18.4-inch                      | 1         | 1.49%   |
| Goldstar E2441 GSM581F 1920x1080 531x299mm 24.0-inch                     | 1         | 1.49%   |
| CPT LCD Monitor CPT13B1 1280x800 331x207mm 15.4-inch                     | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 1         | 1.49%   |
| Chimei Innolux LCD Monitor CMN1476 1366x768 309x174mm 14.0-inch          | 1         | 1.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 222x125mm 10.0-inch | 1         | 1.49%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                    | 1         | 1.49%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 1         | 1.49%   |
| BOE LCD Monitor BOE0657 1920x1080 344x194mm 15.5-inch                    | 1         | 1.49%   |
| BenQ LCD Monitor GL951A 2880x900                                         | 1         | 1.49%   |
| BenQ LCD Monitor GL951A                                                  | 1         | 1.49%   |
| BenQ GL951A BNQ7897 1440x900 408x255mm 18.9-inch                         | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO253C 1366x768 309x173mm 13.9-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO2374 1280x800 331x207mm 15.4-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 1         | 1.49%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch            | 1         | 1.49%   |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                         | 1         | 1.49%   |
| Apple Color LCD APP9C6A 1680x1050 433x270mm 20.1-inch                    | 1         | 1.49%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch    | 1         | 1.49%   |
| Acer V226WL ACR0339 1680x1050 474x296mm 22.0-inch                        | 1         | 1.49%   |
| Acer P225HQ ACR00EA 1920x1080 477x268mm 21.5-inch                        | 1         | 1.49%   |
| Acer LCD Monitor S230HL                                                  | 1         | 1.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 22        | 33.33%  |
| 1920x1080 (FHD)    | 17        | 25.76%  |
| 1600x900 (HD+)     | 6         | 9.09%   |
| 1280x800 (WXGA)    | 6         | 9.09%   |
| 1280x1024 (SXGA)   | 3         | 4.55%   |
| 2560x1440 (QHD)    | 2         | 3.03%   |
| 1680x1050 (WSXGA+) | 2         | 3.03%   |
| Unknown            | 2         | 3.03%   |
| 4640x1080          | 1         | 1.52%   |
| 3840x2160 (4K)     | 1         | 1.52%   |
| 2880x900           | 1         | 1.52%   |
| 1440x900 (WXGA+)   | 1         | 1.52%   |
| 1360x768           | 1         | 1.52%   |
| 1024x600           | 1         | 1.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 23        | 35.94%  |
| 14      | 8         | 12.5%   |
| 17      | 5         | 7.81%   |
| 23      | 4         | 6.25%   |
| 21      | 4         | 6.25%   |
| 20      | 3         | 4.69%   |
| 18      | 3         | 4.69%   |
| 31      | 2         | 3.13%   |
| 27      | 2         | 3.13%   |
| 24      | 2         | 3.13%   |
| 19      | 2         | 3.13%   |
| 13      | 2         | 3.13%   |
| Unknown | 2         | 3.13%   |
| 22      | 1         | 1.56%   |
| 10      | 1         | 1.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 35        | 54.69%  |
| 401-500     | 13        | 20.31%  |
| 501-600     | 7         | 10.94%  |
| 601-700     | 3         | 4.69%   |
| 351-400     | 3         | 4.69%   |
| Unknown     | 2         | 3.13%   |
| 201-300     | 1         | 1.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 48        | 76.19%  |
| 16/10   | 10        | 15.87%  |
| 5/4     | 2         | 3.17%   |
| Unknown | 2         | 3.17%   |
| 4/3     | 1         | 1.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 22        | 34.38%  |
| 81-90          | 10        | 15.63%  |
| 201-250        | 10        | 15.63%  |
| 151-200        | 5         | 7.81%   |
| 141-150        | 5         | 7.81%   |
| 121-130        | 3         | 4.69%   |
| 351-500        | 2         | 3.13%   |
| 301-350        | 2         | 3.13%   |
| Unknown        | 2         | 3.13%   |
| 41-50          | 1         | 1.56%   |
| 251-300        | 1         | 1.56%   |
| 111-120        | 1         | 1.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 27        | 43.55%  |
| 51-100  | 24        | 38.71%  |
| 121-160 | 9         | 14.52%  |
| Unknown | 2         | 3.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 59        | 86.76%  |
| 0     | 5         | 7.35%   |
| 2     | 3         | 4.41%   |
| 3     | 1         | 1.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 43        | 39.09%  |
| Qualcomm Atheros                  | 20        | 18.18%  |
| Intel                             | 14        | 12.73%  |
| Broadcom                          | 12        | 10.91%  |
| Broadcom Limited                  | 4         | 3.64%   |
| TP-Link                           | 2         | 1.82%   |
| Nvidia                            | 2         | 1.82%   |
| Marvell Technology Group          | 2         | 1.82%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.91%   |
| Samsung Electronics               | 1         | 0.91%   |
| Ralink                            | 1         | 0.91%   |
| Qualcomm                          | 1         | 0.91%   |
| NetGear                           | 1         | 0.91%   |
| Ericsson Business Mobile Networks | 1         | 0.91%   |
| D-Link                            | 1         | 0.91%   |
| CyberTAN Technology               | 1         | 0.91%   |
| AVM                               | 1         | 0.91%   |
| ASIX Electronics                  | 1         | 0.91%   |
| Accton Technology                 | 1         | 0.91%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 29        | 21.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 11        | 8.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 6         | 4.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 3.03%   |
| Realtek 802.11ac NIC                                                                  | 3         | 2.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 3         | 2.27%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 3         | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                                | 2         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 1.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                         | 2         | 1.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 1.52%   |
| Nvidia MCP61 Ethernet                                                                 | 2         | 1.52%   |
| Intel Wireless 7260                                                                   | 2         | 1.52%   |
| Intel Centrino Wireless-N 2230                                                        | 2         | 1.52%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                                | 2         | 1.52%   |
| Broadcom BCM4311 802.11b/g WLAN                                                       | 2         | 1.52%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                 | 1         | 0.76%   |
| TP-Link Archer T4U ver.3                                                              | 1         | 0.76%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                         | 1         | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                                         | 1         | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.76%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1         | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 0.76%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                                  | 1         | 0.76%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 0.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.76%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.76%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                              | 1         | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 1         | 0.76%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                             | 1         | 0.76%   |
| Qualcomm M2012K11AG                                                                   | 1         | 0.76%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 0.76%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                                 | 1         | 0.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                              | 1         | 0.76%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.76%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                            | 1         | 0.76%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                                   | 1         | 0.76%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                               | 1         | 0.76%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                                  | 1         | 0.76%   |
| Intel Wireless 8260                                                                   | 1         | 0.76%   |
| Intel Wireless 7265                                                                   | 1         | 0.76%   |
| Intel Wireless 3165                                                                   | 1         | 0.76%   |
| Intel Ethernet Connection I218-LM                                                     | 1         | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 1         | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 0.76%   |
| Intel Centrino Ultimate-N 6300                                                        | 1         | 0.76%   |
| Intel Centrino Advanced-N 6235                                                        | 1         | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 1         | 0.76%   |
| Intel 82579V Gigabit Network Connection                                               | 1         | 0.76%   |
| Intel 82576 Gigabit Network Connection                                                | 1         | 0.76%   |
| Intel 82574L Gigabit Network Connection                                               | 1         | 0.76%   |
| Ericsson Business Mobile Networks N5321 gw                                            | 1         | 0.76%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]                         | 1         | 0.76%   |
| CyberTAN Siemens S30853-S1031-R351 802.11g Wireless Adapter [Atheros AR5523]          | 1         | 0.76%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                        | 1         | 0.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                                     | 1         | 0.76%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                                   | 1         | 0.76%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                                | 1         | 0.76%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                       | 1         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 19        | 32.76%  |
| Intel                 | 11        | 18.97%  |
| Realtek Semiconductor | 10        | 17.24%  |
| Broadcom              | 7         | 12.07%  |
| Broadcom Limited      | 3         | 5.17%   |
| TP-Link               | 2         | 3.45%   |
| Ralink                | 1         | 1.72%   |
| NetGear               | 1         | 1.72%   |
| D-Link                | 1         | 1.72%   |
| CyberTAN Technology   | 1         | 1.72%   |
| AVM                   | 1         | 1.72%   |
| Accton Technology     | 1         | 1.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 6         | 10.17%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 4         | 6.78%   |
| Realtek 802.11ac NIC                                                                  | 3         | 5.08%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                                     | 3         | 5.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 3.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 3.39%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 2         | 3.39%   |
| Intel Wireless 7260                                                                   | 2         | 3.39%   |
| Intel Centrino Wireless-N 2230                                                        | 2         | 3.39%   |
| Broadcom BCM4311 802.11b/g WLAN                                                       | 2         | 3.39%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                                 | 1         | 1.69%   |
| TP-Link Archer T4U ver.3                                                              | 1         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 1.69%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1         | 1.69%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 1         | 1.69%   |
| Realtek RTL8190 802.11n PCI Wireless Network Adapter                                  | 1         | 1.69%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                                 | 1         | 1.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 1.69%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 1.69%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                              | 1         | 1.69%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                             | 1         | 1.69%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                                      | 1         | 1.69%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 1.69%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                            | 1         | 1.69%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                                   | 1         | 1.69%   |
| Intel Wireless 8260                                                                   | 1         | 1.69%   |
| Intel Wireless 7265                                                                   | 1         | 1.69%   |
| Intel Wireless 3165                                                                   | 1         | 1.69%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 1         | 1.69%   |
| Intel Centrino Ultimate-N 6300                                                        | 1         | 1.69%   |
| Intel Centrino Advanced-N 6235                                                        | 1         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 1         | 1.69%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.A3) [Ralink RT5370]                         | 1         | 1.69%   |
| CyberTAN Siemens S30853-S1031-R351 802.11g Wireless Adapter [Atheros AR5523]          | 1         | 1.69%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                            | 1         | 1.69%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                                | 1         | 1.69%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                             | 1         | 1.69%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 1         | 1.69%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 1         | 1.69%   |
| AVM FRITZ WLAN N v2 [RT5572/rt2870.bin]                                               | 1         | 1.69%   |
| Accton WN7512BEP Wireless LAN adapter                                                 | 1         | 1.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 41        | 56.94%  |
| Intel                            | 8         | 11.11%  |
| Broadcom                         | 7         | 9.72%   |
| Qualcomm Atheros                 | 6         | 8.33%   |
| Nvidia                           | 2         | 2.78%   |
| Marvell Technology Group         | 2         | 2.78%   |
| Broadcom Limited                 | 2         | 2.78%   |
| Silicon Integrated Systems [SiS] | 1         | 1.39%   |
| Samsung Electronics              | 1         | 1.39%   |
| Qualcomm                         | 1         | 1.39%   |
| ASIX Electronics                 | 1         | 1.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 29        | 40.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 15.28%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 4.17%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 2.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 2.78%   |
| Nvidia MCP61 Ethernet                                             | 2         | 2.78%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 2.78%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 1.39%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 1.39%   |
| Qualcomm M2012K11AG                                               | 1         | 1.39%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 1.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.39%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.39%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.39%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 1.39%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.39%   |
| Intel 82576 Gigabit Network Connection                            | 1         | 1.39%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 1.39%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 1         | 1.39%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.39%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.39%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.39%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 1.39%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 1.39%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.39%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 1.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 68        | 55.28%  |
| WiFi     | 54        | 43.9%   |
| Modem    | 1         | 0.81%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 35        | 50%     |
| Ethernet | 35        | 50%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 45        | 66.18%  |
| 1     | 19        | 27.94%  |
| 3     | 2         | 2.94%   |
| 4     | 1         | 1.47%   |
| 0     | 1         | 1.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 62        | 91.18%  |
| Yes  | 6         | 8.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 8         | 25.81%  |
| Intel                           | 6         | 19.35%  |
| Cambridge Silicon Radio         | 4         | 12.9%   |
| Lite-On Technology              | 3         | 9.68%   |
| Apple                           | 3         | 9.68%   |
| Realtek Semiconductor           | 2         | 6.45%   |
| Hewlett-Packard                 | 2         | 6.45%   |
| Ralink Technology               | 1         | 3.23%   |
| Integrated System Solution      | 1         | 3.23%   |
| Foxconn / Hon Hai               | 1         | 3.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 12.9%   |
| Qualcomm Atheros  Bluetooth Device                          | 3         | 9.68%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 9.68%   |
| Intel Bluetooth wireless interface                          | 3         | 9.68%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 6.45%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 6.45%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 6.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 6.45%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                | 1         | 3.23%   |
| Qualcomm Atheros Bluetooth USB Host Controller              | 1         | 3.23%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 3.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 3.23%   |
| Intel AX201 Bluetooth                                       | 1         | 3.23%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter       | 1         | 3.23%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 3.23%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 3.23%   |
| Foxconn / Hon Hai BCM20702A0                                | 1         | 3.23%   |
| Apple Bluetooth HCI                                         | 1         | 3.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 44        | 48.89%  |
| AMD                              | 23        | 25.56%  |
| Nvidia                           | 13        | 14.44%  |
| C-Media Electronics              | 3         | 3.33%   |
| Silicon Integrated Systems [SiS] | 2         | 2.22%   |
| Texas Instruments                | 1         | 1.11%   |
| Logitech                         | 1         | 1.11%   |
| Creative Technology              | 1         | 1.11%   |
| Creative Labs                    | 1         | 1.11%   |
| Corsair                          | 1         | 1.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 9.62%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 6.73%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 5.77%   |
| AMD FCH Azalia Controller                                                  | 6         | 5.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 4.81%   |
| Intel Sunrise Point-LP HD Audio                                            | 4         | 3.85%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 3.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 2.88%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 2.88%   |
| AMD Starship/Matisse HD Audio Controller                                   | 3         | 2.88%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 2.88%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                   | 2         | 1.92%   |
| Nvidia MCP61 High Definition Audio                                         | 2         | 1.92%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.92%   |
| Nvidia GF110 High Definition Audio Controller                              | 2         | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.92%   |
| C-Media Electronics Audio Adapter                                          | 2         | 1.92%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 2         | 1.92%   |
| Texas Instruments PCM2900 Audio Codec                                      | 1         | 0.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 1         | 0.96%   |
| Nvidia TU102 High Definition Audio Controller                              | 1         | 0.96%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.96%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.96%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.96%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.96%   |
| Nvidia GF116 High Definition Audio Controller                              | 1         | 0.96%   |
| Logitech Logitech USB Microphone                                           | 1         | 0.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 1         | 0.96%   |
| Intel Haswell-ULT HD Audio Controller                                      | 1         | 0.96%   |
| Intel Comet Lake PCH cAVS                                                  | 1         | 0.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 1         | 0.96%   |
| Intel Broadwell-U Audio Controller                                         | 1         | 0.96%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 1         | 0.96%   |
| Intel 8 Series HD Audio Controller                                         | 1         | 0.96%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.96%   |
| Creative Technology Sound BlasterX G1                                      | 1         | 0.96%   |
| Creative Labs CA0108/CA10300 [Sound Blaster Audigy Series]                 | 1         | 0.96%   |
| Corsair Corsair VOID PRO Surround USB Adapter                              | 1         | 0.96%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                              | 1         | 0.96%   |
| AMD Trinity HDMI Audio Controller                                          | 1         | 0.96%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 1         | 0.96%   |
| AMD RV630 HDMI Audio [Radeon HD 2600 PRO/XT / HD 3610]                     | 1         | 0.96%   |
| AMD RV610 HDMI Audio [Radeon HD 2350 PRO / 2400 PRO/XT / HD 3410]          | 1         | 0.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 1         | 0.96%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 1         | 0.96%   |
| AMD Family 17h/19h HD Audio Controller                                     | 1         | 0.96%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 0.96%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]        | 1         | 0.96%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Corsair             | 3         | 21.43%  |
| Unknown             | 2         | 14.29%  |
| SK Hynix            | 2         | 14.29%  |
| Samsung Electronics | 2         | 14.29%  |
| Kingston            | 2         | 14.29%  |
| Smart               | 1         | 7.14%   |
| G.Skill             | 1         | 7.14%   |
| Elpida              | 1         | 7.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM SDRAM                     | 1         | 6.67%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                  | 1         | 6.67%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                  | 1         | 6.67%   |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s   | 1         | 6.67%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s  | 1         | 6.67%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s  | 1         | 6.67%   |
| Samsung RAM Module 8192MB DIMM DDR3 1333MT/s            | 1         | 6.67%   |
| Samsung RAM K4B8G1646B-MYK0 4GB SODIMM DDR3 1600MT/s    | 1         | 6.67%   |
| Kingston RAM KHX2400C11D3/8GX 8192MB DIMM DDR3 2400MT/s | 1         | 6.67%   |
| Kingston RAM 9905428-026.A00LF 2GB SODIMM DDR3 1066MT/s | 1         | 6.67%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s     | 1         | 6.67%   |
| Elpida RAM Module 8192MB DIMM DDR3 1333MT/s             | 1         | 6.67%   |
| Corsair RAM CMY8GX3M2C1600C9 4096MB DIMM DDR3 1600MT/s  | 1         | 6.67%   |
| Corsair RAM CMW16GX4M2C3200C16 8GB DIMM DDR4 3266MT/s   | 1         | 6.67%   |
| Corsair RAM CML16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s   | 1         | 6.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 5         | 45.45%  |
| DDR4    | 3         | 27.27%  |
| SDRAM   | 1         | 9.09%   |
| LPDDR4  | 1         | 9.09%   |
| Unknown | 1         | 9.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| DIMM   | 6         | 54.55%  |
| SODIMM | 5         | 45.45%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size | Computers | Percent |
|------|-----------|---------|
| 8192 | 5         | 38.46%  |
| 4096 | 4         | 30.77%  |
| 2048 | 3         | 23.08%  |
| 1024 | 1         | 7.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 3         | 23.08%  |
| 3466    | 1         | 7.69%   |
| 3266    | 1         | 7.69%   |
| 2667    | 1         | 7.69%   |
| 2400    | 1         | 7.69%   |
| 2133    | 1         | 7.69%   |
| 1333    | 1         | 7.69%   |
| 1066    | 1         | 7.69%   |
| 800     | 1         | 7.69%   |
| 667     | 1         | 7.69%   |
| Unknown | 1         | 7.69%   |

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
| 0     | 48        | 68.57%  |
| 1     | 21        | 30%     |
| 2     | 1         | 1.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Computers | Percent |
|--------------------|-----------|---------|
| Net/wireless       | 9         | 37.5%   |
| Graphics card      | 9         | 37.5%   |
| Fingerprint reader | 2         | 8.33%   |
| Chipcard           | 2         | 8.33%   |
| Storage            | 1         | 4.17%   |
| Network            | 1         | 4.17%   |

