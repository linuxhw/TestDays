Artix - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Artix.

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

Total: 118

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| LG Electro... | 17Z990-R.AAC9U1             | [dfacdafc7f](https://linux-hardware.org/?probe=dfacdafc7f) | May 11, 2022 |
| Acer          | Nitro AN515-52              | [5122079c78](https://linux-hardware.org/?probe=5122079c78) | May 10, 2022 |
| Lenovo        | ThinkPad T480 MFG_IN_GO     | [9792863fc7](https://linux-hardware.org/?probe=9792863fc7) | May 08, 2022 |
| Lenovo        | ThinkPad T480 MFG_IN_GO     | [bba77106b4](https://linux-hardware.org/?probe=bba77106b4) | May 08, 2022 |
| HP            | 15                          | [d9ed47d44c](https://linux-hardware.org/?probe=d9ed47d44c) | Apr 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [85b1934bfd](https://linux-hardware.org/?probe=85b1934bfd) | Apr 21, 2022 |
| ASUSTek       | GX501VIK                    | [076208c6fd](https://linux-hardware.org/?probe=076208c6fd) | Apr 15, 2022 |
| ASUSTek       | GX501VIK                    | [15c4c7877b](https://linux-hardware.org/?probe=15c4c7877b) | Apr 15, 2022 |
| Lenovo        | ThinkPad T430 2350BC6       | [c2ffb2a421](https://linux-hardware.org/?probe=c2ffb2a421) | Apr 14, 2022 |
| HP            | 246                         | [4ef673dd00](https://linux-hardware.org/?probe=4ef673dd00) | Apr 10, 2022 |
| Lenovo        | ThinkPad T430 2347H76       | [493f378237](https://linux-hardware.org/?probe=493f378237) | Mar 10, 2022 |
| HP            | Laptop 14s-dq2xxx           | [92db061239](https://linux-hardware.org/?probe=92db061239) | Mar 09, 2022 |
| Lenovo        | IdeaPad Y500 20193          | [604362a51f](https://linux-hardware.org/?probe=604362a51f) | Feb 18, 2022 |
| Notebook      | N141CU                      | [029f48bc53](https://linux-hardware.org/?probe=029f48bc53) | Feb 16, 2022 |
| Acer          | Aspire V3-472PG             | [70c80ae356](https://linux-hardware.org/?probe=70c80ae356) | Feb 16, 2022 |
| HP            | Laptop 15-ef1xxx            | [6cf7935dcc](https://linux-hardware.org/?probe=6cf7935dcc) | Feb 14, 2022 |
| Timi          | RedmiBook 14 II             | [3c1248a9d9](https://linux-hardware.org/?probe=3c1248a9d9) | Feb 10, 2022 |
| ASUSTek       | 1225C                       | [b780589dd0](https://linux-hardware.org/?probe=b780589dd0) | Feb 07, 2022 |
| HP            | Laptop 15-ef1xxx            | [6a49ff6317](https://linux-hardware.org/?probe=6a49ff6317) | Jan 18, 2022 |
| Lenovo        | G400s 20244                 | [9ac1aa04cc](https://linux-hardware.org/?probe=9ac1aa04cc) | Jan 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [945649c354](https://linux-hardware.org/?probe=945649c354) | Jan 07, 2022 |
| MSI           | Modern 15 A11M              | [bef1d4552a](https://linux-hardware.org/?probe=bef1d4552a) | Jan 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [a568bef730](https://linux-hardware.org/?probe=a568bef730) | Jan 05, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [a6c63e1079](https://linux-hardware.org/?probe=a6c63e1079) | Dec 17, 2021 |
| Dell          | Latitude E6440              | [5e572f557c](https://linux-hardware.org/?probe=5e572f557c) | Dec 16, 2021 |
| Dell          | Latitude E6440              | [ac94463e37](https://linux-hardware.org/?probe=ac94463e37) | Dec 16, 2021 |
| ASUSTek       | K50IE                       | [49a6b75a43](https://linux-hardware.org/?probe=49a6b75a43) | Nov 29, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [0e12642e78](https://linux-hardware.org/?probe=0e12642e78) | Nov 27, 2021 |
| Timi          | RedmiBook 14 II             | [3e700c917e](https://linux-hardware.org/?probe=3e700c917e) | Nov 25, 2021 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | [9a5098383d](https://linux-hardware.org/?probe=9a5098383d) | Nov 24, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3D40... | [76be488014](https://linux-hardware.org/?probe=76be488014) | Nov 07, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3D40... | [f96363ccf5](https://linux-hardware.org/?probe=f96363ccf5) | Nov 07, 2021 |
| HP            | ProBook 450 G6              | [ded9086b7c](https://linux-hardware.org/?probe=ded9086b7c) | Nov 06, 2021 |
| Timi          | RedmiBook 14 II             | [038c0ad664](https://linux-hardware.org/?probe=038c0ad664) | Nov 03, 2021 |
| Timi          | RedmiBook 14 II             | [d8ae8a047c](https://linux-hardware.org/?probe=d8ae8a047c) | Nov 02, 2021 |
| Acer          | Swift SF314-59              | [c764d879fb](https://linux-hardware.org/?probe=c764d879fb) | Sep 27, 2021 |
| Acer          | Swift SF314-59              | [9426a6d4df](https://linux-hardware.org/?probe=9426a6d4df) | Sep 23, 2021 |
| Acer          | Aspire E5-575               | [d32c769f65](https://linux-hardware.org/?probe=d32c769f65) | Sep 22, 2021 |
| HP            | Laptop 14s-cf3xxx           | [5b9800e687](https://linux-hardware.org/?probe=5b9800e687) | Sep 06, 2021 |
| Dell          | Precision M6600             | [3c06ad8f67](https://linux-hardware.org/?probe=3c06ad8f67) | Sep 06, 2021 |
| ASUSTek       | GL702ZC                     | [7cb34b0a2e](https://linux-hardware.org/?probe=7cb34b0a2e) | Aug 10, 2021 |
| ASUSTek       | GL702ZC                     | [8ab07e196d](https://linux-hardware.org/?probe=8ab07e196d) | Aug 09, 2021 |
| GPD           | P2 MAX                      | [bf70dbe409](https://linux-hardware.org/?probe=bf70dbe409) | Aug 07, 2021 |
| GPD           | P2 MAX                      | [a4e8eb7d9e](https://linux-hardware.org/?probe=a4e8eb7d9e) | Aug 07, 2021 |
| GPD           | P2 MAX                      | [43075e1581](https://linux-hardware.org/?probe=43075e1581) | Jul 23, 2021 |
| HP            | 250 G3                      | [b1a0952727](https://linux-hardware.org/?probe=b1a0952727) | Jul 19, 2021 |
| Dell          | Inspiron 3442               | [a4e06ddea2](https://linux-hardware.org/?probe=a4e06ddea2) | Jul 02, 2021 |
| Lenovo        | LaVie Z 20FF0012US          | [789d556ef6](https://linux-hardware.org/?probe=789d556ef6) | Jul 01, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | [89bbafa02e](https://linux-hardware.org/?probe=89bbafa02e) | Jun 22, 2021 |
| HP            | 15                          | [4f6c5d8c89](https://linux-hardware.org/?probe=4f6c5d8c89) | Jun 22, 2021 |
| Apple         | MacBookAir7,2               | [6a459ac265](https://linux-hardware.org/?probe=6a459ac265) | Jun 16, 2021 |
| HP            | 250 G7 Notebook PC          | [10803bcbc4](https://linux-hardware.org/?probe=10803bcbc4) | Jun 07, 2021 |
| HP            | 250 G7 Notebook PC          | [445e09faa7](https://linux-hardware.org/?probe=445e09faa7) | Jun 07, 2021 |
| Dell          | Precision 7550              | [5d7ecb9bbb](https://linux-hardware.org/?probe=5d7ecb9bbb) | Jun 07, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [de11ab3cc4](https://linux-hardware.org/?probe=de11ab3cc4) | May 31, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [4688dc5b46](https://linux-hardware.org/?probe=4688dc5b46) | May 29, 2021 |
| Dell          | Precision 7550              | [206eeb06c9](https://linux-hardware.org/?probe=206eeb06c9) | May 23, 2021 |
| UNOWHY        | Y13G010S4EI                 | [62d883cffd](https://linux-hardware.org/?probe=62d883cffd) | May 18, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | [85def78a94](https://linux-hardware.org/?probe=85def78a94) | May 02, 2021 |
| HP            | Laptop 17z-ca300            | [ea09357867](https://linux-hardware.org/?probe=ea09357867) | Apr 26, 2021 |
| Acer          | Aspire V3-572PG             | [a874b34c2a](https://linux-hardware.org/?probe=a874b34c2a) | Apr 12, 2021 |
| Apple         | MacBookAir7,2               | [7f14077ecc](https://linux-hardware.org/?probe=7f14077ecc) | Mar 29, 2021 |
| Apple         | MacBookPro11,1              | [666815417c](https://linux-hardware.org/?probe=666815417c) | Mar 28, 2021 |
| Apple         | MacBookPro11,1              | [d2027dc1c2](https://linux-hardware.org/?probe=d2027dc1c2) | Mar 24, 2021 |
| MSI           | GP72 7RDX                   | [a60abbdcd4](https://linux-hardware.org/?probe=a60abbdcd4) | Mar 18, 2021 |
| Quanta        | SWH                         | [dc6df30340](https://linux-hardware.org/?probe=dc6df30340) | Mar 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [c2599a37c2](https://linux-hardware.org/?probe=c2599a37c2) | Mar 08, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [76006e9ba5](https://linux-hardware.org/?probe=76006e9ba5) | Mar 01, 2021 |
| Dell          | Precision 7550              | [c1c4fd3b1a](https://linux-hardware.org/?probe=c1c4fd3b1a) | Feb 21, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | [b25144d80b](https://linux-hardware.org/?probe=b25144d80b) | Feb 18, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [c2408f8152](https://linux-hardware.org/?probe=c2408f8152) | Feb 16, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | [838f747450](https://linux-hardware.org/?probe=838f747450) | Feb 14, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | [214d72ae23](https://linux-hardware.org/?probe=214d72ae23) | Feb 12, 2021 |
| Acer          | Aspire 5733Z                | [b15b48fb21](https://linux-hardware.org/?probe=b15b48fb21) | Jan 29, 2021 |
| ASUSTek       | K53SC                       | [11547cb913](https://linux-hardware.org/?probe=11547cb913) | Jan 22, 2021 |
| ASUSTek       | K53SC                       | [061c52c2ff](https://linux-hardware.org/?probe=061c52c2ff) | Jan 22, 2021 |
| HP            | ProBook 450 G6              | [40e4f5d2fb](https://linux-hardware.org/?probe=40e4f5d2fb) | Jan 21, 2021 |
| Dell          | Precision 5520              | [a714973647](https://linux-hardware.org/?probe=a714973647) | Jan 16, 2021 |
| ASUSTek       | E402NA                      | [ac894b264b](https://linux-hardware.org/?probe=ac894b264b) | Jan 10, 2021 |
| Apple         | MacBookPro11,1              | [e8ac486033](https://linux-hardware.org/?probe=e8ac486033) | Jan 09, 2021 |
| Acer          | Aspire A315-53              | [abac7a5b07](https://linux-hardware.org/?probe=abac7a5b07) | Jan 02, 2021 |
| Dell          | Precision 7550              | [9c8b2f2ad6](https://linux-hardware.org/?probe=9c8b2f2ad6) | Dec 30, 2020 |
| Gigabyte      | B450M DS3H-CF               | [b9c02872aa](https://linux-hardware.org/?probe=b9c02872aa) | Dec 29, 2020 |
| Dell          | Latitude E6530              | [46704587d1](https://linux-hardware.org/?probe=46704587d1) | Dec 25, 2020 |
| Gigabyte      | B450M DS3H-CF               | [d2701aa534](https://linux-hardware.org/?probe=d2701aa534) | Dec 24, 2020 |
| HP            | 250 G4 Notebook PC          | [178de0b283](https://linux-hardware.org/?probe=178de0b283) | Dec 24, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | [a905f1377a](https://linux-hardware.org/?probe=a905f1377a) | Dec 20, 2020 |
| GPD           | P2 MAX                      | [f6249e6387](https://linux-hardware.org/?probe=f6249e6387) | Dec 11, 2020 |
| Sony          | VPCCB17FG                   | [5a24dc3231](https://linux-hardware.org/?probe=5a24dc3231) | Nov 26, 2020 |
| Acer          | Aspire A315-53              | [bc80dc5050](https://linux-hardware.org/?probe=bc80dc5050) | Nov 25, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [53a1586791](https://linux-hardware.org/?probe=53a1586791) | Nov 12, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | [61653c183a](https://linux-hardware.org/?probe=61653c183a) | Oct 30, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [f18b33a8f0](https://linux-hardware.org/?probe=f18b33a8f0) | Oct 25, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [acc8c4e663](https://linux-hardware.org/?probe=acc8c4e663) | Oct 25, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | [7c29a97dff](https://linux-hardware.org/?probe=7c29a97dff) | Oct 21, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | [961c0be28a](https://linux-hardware.org/?probe=961c0be28a) | Oct 18, 2020 |
| Dell          | Inspiron 5570               | [038ef2ebaa](https://linux-hardware.org/?probe=038ef2ebaa) | Oct 15, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [b877caba0b](https://linux-hardware.org/?probe=b877caba0b) | Oct 13, 2020 |
| HP            | 255 G7 Notebook PC          | [026a4d80f6](https://linux-hardware.org/?probe=026a4d80f6) | Oct 08, 2020 |
| Dell          | Precision 7550              | [c574758854](https://linux-hardware.org/?probe=c574758854) | Sep 19, 2020 |
| Dell          | Precision 7550              | [14d1876313](https://linux-hardware.org/?probe=14d1876313) | Aug 31, 2020 |
| Dell          | Precision 7550              | [d44c1dbf60](https://linux-hardware.org/?probe=d44c1dbf60) | Aug 31, 2020 |
| Dell          | Precision 7550              | [25d7f344e9](https://linux-hardware.org/?probe=25d7f344e9) | Aug 29, 2020 |
| Acer          | Nitro AN515-51              | [4f2724d5ad](https://linux-hardware.org/?probe=4f2724d5ad) | Aug 16, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [aae7fd244a](https://linux-hardware.org/?probe=aae7fd244a) | Aug 06, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [5e3d9be29a](https://linux-hardware.org/?probe=5e3d9be29a) | Aug 01, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [d5b2c55949](https://linux-hardware.org/?probe=d5b2c55949) | Jul 27, 2020 |
| Lenovo        | ThinkPad T420 4236H45       | [61fd4ce395](https://linux-hardware.org/?probe=61fd4ce395) | Jul 20, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [0af3ac770f](https://linux-hardware.org/?probe=0af3ac770f) | Jul 06, 2020 |
| Notebook      | N130BU                      | [e1b81e4880](https://linux-hardware.org/?probe=e1b81e4880) | Jul 05, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [051fa5784a](https://linux-hardware.org/?probe=051fa5784a) | Jul 02, 2020 |
| Gigabyte      | AERO 15-X9                  | [7cb20a8170](https://linux-hardware.org/?probe=7cb20a8170) | Jul 01, 2020 |
| Gigabyte      | AERO 15-X9                  | [efaa58fcc8](https://linux-hardware.org/?probe=efaa58fcc8) | Jun 14, 2020 |
| Gigabyte      | AERO 15-X9                  | [b5fee1bf94](https://linux-hardware.org/?probe=b5fee1bf94) | Jun 12, 2020 |
| Acer          | Aspire E5-575G              | [cd633c729b](https://linux-hardware.org/?probe=cd633c729b) | Apr 29, 2020 |
| Dell          | Precision 3540              | [3e582eb1b9](https://linux-hardware.org/?probe=3e582eb1b9) | Mar 30, 2020 |
| Dell          | Precision 3540              | [2a446cd098](https://linux-hardware.org/?probe=2a446cd098) | Feb 15, 2020 |
| Lenovo        | B590 20206                  | [a2066c32a9](https://linux-hardware.org/?probe=a2066c32a9) | Oct 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Artix Rolling  | 50        | 60.24%  |
| Artix          | 31        | 37.35%  |
| Artix 20201207 | 1         | 1.2%    |
| Artix 20201128 | 1         | 1.2%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Artix | 78        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.9.14-artix1-1                 | 6         | 6.25%   |
| 5.7.6-artix1-1                  | 3         | 3.13%   |
| 5.7.12-artix1-1                 | 2         | 2.08%   |
| 5.17.1-artix1-1                 | 2         | 2.08%   |
| 5.16.8-artix1-2                 | 2         | 2.08%   |
| 5.16.10-artix1-1                | 2         | 2.08%   |
| 5.15.12-artix1-1                | 2         | 2.08%   |
| 5.14.16-artix1-1                | 2         | 2.08%   |
| 5.13.8-artix1-1                 | 2         | 2.08%   |
| 5.12.8-artix1-1                 | 2         | 2.08%   |
| 5.12.12-zen1-1-zen              | 2         | 2.08%   |
| 5.12.12-artix1-1                | 2         | 2.08%   |
| 5.11.6-artix1-1                 | 2         | 2.08%   |
| 5.10.6-artix1-1                 | 2         | 2.08%   |
| 5.10.4-artix2-1                 | 2         | 2.08%   |
| 5.10.16-artix1-1                | 2         | 2.08%   |
| 5.9.6-artix1-1                  | 1         | 1.04%   |
| 5.9.14-zen1-1-zen               | 1         | 1.04%   |
| 5.9.12-artix1-1                 | 1         | 1.04%   |
| 5.9.1-artix1-1                  | 1         | 1.04%   |
| 5.9.0-zen1-1-zen                | 1         | 1.04%   |
| 5.9.0-1-mainline-bootsplash     | 1         | 1.04%   |
| 5.8.8-artix1-1                  | 1         | 1.04%   |
| 5.8.4-artix1-1                  | 1         | 1.04%   |
| 5.8.14-zen1-1-zen               | 1         | 1.04%   |
| 5.8.14-artix1-1                 | 1         | 1.04%   |
| 5.8.12-artix1-1                 | 1         | 1.04%   |
| 5.8.0-rc7-5-mainline-bootsplash | 1         | 1.04%   |
| 5.7.8-artix1-1                  | 1         | 1.04%   |
| 5.7.2-artix1-1                  | 1         | 1.04%   |
| 5.6.7-x86_64                    | 1         | 1.04%   |
| 5.5.3-artix1-1                  | 1         | 1.04%   |
| 5.5.10-artix1-1                 | 1         | 1.04%   |
| 5.4.74-1-lts                    | 1         | 1.04%   |
| 5.17.5-256-tkg-pds              | 1         | 1.04%   |
| 5.17.4-artix1-1                 | 1         | 1.04%   |
| 5.17.3-zen1-1-zen               | 1         | 1.04%   |
| 5.17.2-artix3-1                 | 1         | 1.04%   |
| 5.17.1-zen1-1-zen               | 1         | 1.04%   |
| 5.16.8-zen1-1-zen               | 1         | 1.04%   |
| 5.16.7-artix1-1                 | 1         | 1.04%   |
| 5.16.3-artix1-1                 | 1         | 1.04%   |
| 5.16.1-artix1-1                 | 1         | 1.04%   |
| 5.16.0-arch1-g400s              | 1         | 1.04%   |
| 5.15.8-artix1-1                 | 1         | 1.04%   |
| 5.15.7-zen1-1-zen               | 1         | 1.04%   |
| 5.15.5-zen1-1-zen               | 1         | 1.04%   |
| 5.15.4-artix1-1                 | 1         | 1.04%   |
| 5.15.36-1-lts                   | 1         | 1.04%   |
| 5.15.3-zen1-1-zen               | 1         | 1.04%   |
| 5.15.16-1-lts                   | 1         | 1.04%   |
| 5.15.12-zen1-1-zen              | 1         | 1.04%   |
| 5.14.7-zen1-1-zen               | 1         | 1.04%   |
| 5.14.14-artix1-1                | 1         | 1.04%   |
| 5.13.13-xanmod1-1               | 1         | 1.04%   |
| 5.13.12-artix1-1                | 1         | 1.04%   |
| 5.12.8-zen1-1-zen               | 1         | 1.04%   |
| 5.12.6-artix1-1                 | 1         | 1.04%   |
| 5.12.5-artix1-1                 | 1         | 1.04%   |
| 5.12.4-artix1-1                 | 1         | 1.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.14  | 7         | 7.29%   |
| 5.12.12 | 4         | 4.17%   |
| 5.7.6   | 3         | 3.13%   |
| 5.17.1  | 3         | 3.13%   |
| 5.16.8  | 3         | 3.13%   |
| 5.15.12 | 3         | 3.13%   |
| 5.12.8  | 3         | 3.13%   |
| 5.9.0   | 2         | 2.08%   |
| 5.8.14  | 2         | 2.08%   |
| 5.7.12  | 2         | 2.08%   |
| 5.16.10 | 2         | 2.08%   |
| 5.14.16 | 2         | 2.08%   |
| 5.13.8  | 2         | 2.08%   |
| 5.12.14 | 2         | 2.08%   |
| 5.11.6  | 2         | 2.08%   |
| 5.10.6  | 2         | 2.08%   |
| 5.10.4  | 2         | 2.08%   |
| 5.10.16 | 2         | 2.08%   |
| 5.9.6   | 1         | 1.04%   |
| 5.9.12  | 1         | 1.04%   |
| 5.9.1   | 1         | 1.04%   |
| 5.8.8   | 1         | 1.04%   |
| 5.8.4   | 1         | 1.04%   |
| 5.8.12  | 1         | 1.04%   |
| 5.8.0   | 1         | 1.04%   |
| 5.7.8   | 1         | 1.04%   |
| 5.7.2   | 1         | 1.04%   |
| 5.6.7   | 1         | 1.04%   |
| 5.5.3   | 1         | 1.04%   |
| 5.5.10  | 1         | 1.04%   |
| 5.4.74  | 1         | 1.04%   |
| 5.17.5  | 1         | 1.04%   |
| 5.17.4  | 1         | 1.04%   |
| 5.17.3  | 1         | 1.04%   |
| 5.17.2  | 1         | 1.04%   |
| 5.16.7  | 1         | 1.04%   |
| 5.16.3  | 1         | 1.04%   |
| 5.16.1  | 1         | 1.04%   |
| 5.16.0  | 1         | 1.04%   |
| 5.15.8  | 1         | 1.04%   |
| 5.15.7  | 1         | 1.04%   |
| 5.15.5  | 1         | 1.04%   |
| 5.15.4  | 1         | 1.04%   |
| 5.15.36 | 1         | 1.04%   |
| 5.15.3  | 1         | 1.04%   |
| 5.15.16 | 1         | 1.04%   |
| 5.14.7  | 1         | 1.04%   |
| 5.14.14 | 1         | 1.04%   |
| 5.13.13 | 1         | 1.04%   |
| 5.13.12 | 1         | 1.04%   |
| 5.12.6  | 1         | 1.04%   |
| 5.12.5  | 1         | 1.04%   |
| 5.12.4  | 1         | 1.04%   |
| 5.12.0  | 1         | 1.04%   |
| 5.11.8  | 1         | 1.04%   |
| 5.11.7  | 1         | 1.04%   |
| 5.11.2  | 1         | 1.04%   |
| 5.11.16 | 1         | 1.04%   |
| 5.11.12 | 1         | 1.04%   |
| 5.11.1  | 1         | 1.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.12    | 12        | 13.33%  |
| 5.9     | 11        | 12.22%  |
| 5.10    | 11        | 12.22%  |
| 5.15    | 10        | 11.11%  |
| 5.16    | 8         | 8.89%   |
| 5.11    | 8         | 8.89%   |
| 5.17    | 7         | 7.78%   |
| 5.7     | 6         | 6.67%   |
| 5.8     | 5         | 5.56%   |
| 5.14    | 4         | 4.44%   |
| 5.13    | 4         | 4.44%   |
| 5.6     | 1         | 1.11%   |
| 5.5     | 1         | 1.11%   |
| 5.4     | 1         | 1.11%   |
| 4.19    | 1         | 1.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 78        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| KDE5           | 18        | 21.69%  |
| GNOME          | 14        | 16.87%  |
| Unknown        | 13        | 15.66%  |
| XFCE           | 12        | 14.46%  |
| X-Cinnamon     | 5         | 6.02%   |
| MATE           | 4         | 4.82%   |
| KDE            | 4         | 4.82%   |
| LXQt           | 3         | 3.61%   |
| Cinnamon       | 3         | 3.61%   |
| bspwm          | 2         | 2.41%   |
| xmonad         | 1         | 1.2%    |
| nxde           | 1         | 1.2%    |
| LXDE           | 1         | 1.2%    |
| i3             | 1         | 1.2%    |
| awesomeminimal | 1         | 1.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 56        | 68.29%  |
| Tty     | 12        | 14.63%  |
| Wayland | 10        | 12.2%   |
| Unknown | 4         | 4.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 28        | 35.44%  |
| LightDM | 25        | 31.65%  |
| SDDM    | 22        | 27.85%  |
| SLiM    | 1         | 1.27%   |
| Ly      | 1         | 1.27%   |
| LXDM    | 1         | 1.27%   |
| GDM     | 1         | 1.27%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 41        | 50%     |
| Unknown | 10        | 12.2%   |
| ru_RU   | 6         | 7.32%   |
| en_GB   | 6         | 7.32%   |
| fr_FR   | 3         | 3.66%   |
| es_ES   | 2         | 2.44%   |
| en_CA   | 2         | 2.44%   |
| C       | 2         | 2.44%   |
| uk_UA   | 1         | 1.22%   |
| pt_PT   | 1         | 1.22%   |
| pt_BR   | 1         | 1.22%   |
| pl_PL   | 1         | 1.22%   |
| it_IT   | 1         | 1.22%   |
| en_IN   | 1         | 1.22%   |
| en_AU   | 1         | 1.22%   |
| el_GR   | 1         | 1.22%   |
| de_DE   | 1         | 1.22%   |
| cs_CZ   | 1         | 1.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 59        | 74.68%  |
| BIOS | 20        | 25.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 57        | 73.08%  |
| Btrfs   | 17        | 21.79%  |
| Xfs     | 2         | 2.56%   |
| Overlay | 1         | 1.28%   |
| F2fs    | 1         | 1.28%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 58        | 73.42%  |
| Unknown | 12        | 15.19%  |
| MBR     | 9         | 11.39%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 65        | 82.28%  |
| Yes       | 14        | 17.72%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 58        | 74.36%  |
| Yes       | 20        | 25.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 24        | 30.77%  |
| Hewlett-Packard     | 13        | 16.67%  |
| Dell                | 9         | 11.54%  |
| Acer                | 9         | 11.54%  |
| ASUSTek Computer    | 7         | 8.97%   |
| Apple               | 3         | 3.85%   |
| Timi                | 2         | 2.56%   |
| Notebook            | 2         | 2.56%   |
| MSI                 | 2         | 2.56%   |
| GPD                 | 2         | 2.56%   |
| Gigabyte Technology | 2         | 2.56%   |
| UNOWHY              | 1         | 1.28%   |
| Quanta              | 1         | 1.28%   |
| LG Electronics      | 1         | 1.28%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Timi RedmiBook 14 II                    | 2         | 2.56%   |
| Lenovo IdeaPad 5 15IIL05 81YK           | 2         | 2.56%   |
| HP 15                                   | 2         | 2.56%   |
| GPD P2 MAX                              | 2         | 2.56%   |
| Dell Precision 7550                     | 2         | 2.56%   |
| Apple MacBookAir7,2                     | 2         | 2.56%   |
| UNOWHY Y13G010S4EI                      | 1         | 1.28%   |
| Quanta SWH                              | 1         | 1.28%   |
| Notebook N141CU                         | 1         | 1.28%   |
| Notebook N130BU                         | 1         | 1.28%   |
| MSI Modern 15 A11M                      | 1         | 1.28%   |
| MSI GP72 7RDX                           | 1         | 1.28%   |
| LG 17Z990-R.AAC9U1                      | 1         | 1.28%   |
| Lenovo ThinkPad W500 4063CJ5            | 1         | 1.28%   |
| Lenovo ThinkPad T480s 20L8S3D400        | 1         | 1.28%   |
| Lenovo ThinkPad T480 MFG_IN_GO          | 1         | 1.28%   |
| Lenovo ThinkPad T430 2350BC6            | 1         | 1.28%   |
| Lenovo ThinkPad T430 2347H76            | 1         | 1.28%   |
| Lenovo ThinkPad T420 4236H45            | 1         | 1.28%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00    | 1         | 1.28%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800    | 1         | 1.28%   |
| Lenovo ThinkPad P1 Gen 3 20TH001EMH     | 1         | 1.28%   |
| Lenovo ThinkPad E14 Gen 2 20T6000MCK    | 1         | 1.28%   |
| Lenovo ThinkPad 11e 5th Gen 20LNS0P500  | 1         | 1.28%   |
| Lenovo ThinkBook 15 G2 ITL 20VE         | 1         | 1.28%   |
| Lenovo Legion 5 15ARH05H 82B1           | 1         | 1.28%   |
| Lenovo LaVie Z 20FF0012US               | 1         | 1.28%   |
| Lenovo IdeaPad Y500 20193               | 1         | 1.28%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL   | 1         | 1.28%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG    | 1         | 1.28%   |
| Lenovo IdeaPad 510-15IKB 80SV           | 1         | 1.28%   |
| Lenovo IdeaPad 330-15IKB 81DE           | 1         | 1.28%   |
| Lenovo G400s 20244                      | 1         | 1.28%   |
| Lenovo B590 20206                       | 1         | 1.28%   |
| Lenovo B570e HuronRiver Platform        | 1         | 1.28%   |
| HP ProBook 450 G6                       | 1         | 1.28%   |
| HP OMEN Laptop 15-en0xxx                | 1         | 1.28%   |
| HP Laptop 17z-ca300                     | 1         | 1.28%   |
| HP Laptop 15-ef1xxx                     | 1         | 1.28%   |
| HP Laptop 14s-dq2xxx                    | 1         | 1.28%   |
| HP Laptop 14s-cf3xxx                    | 1         | 1.28%   |
| HP 255 G7 Notebook PC                   | 1         | 1.28%   |
| HP 250 G7 Notebook PC                   | 1         | 1.28%   |
| HP 250 G4 Notebook PC                   | 1         | 1.28%   |
| HP 250 G3                               | 1         | 1.28%   |
| HP 246                                  | 1         | 1.28%   |
| Gigabyte B450M DS3H                     | 1         | 1.28%   |
| Gigabyte AERO 15-X9                     | 1         | 1.28%   |
| Dell Precision M6600                    | 1         | 1.28%   |
| Dell Precision 5520                     | 1         | 1.28%   |
| Dell Precision 3540                     | 1         | 1.28%   |
| Dell Latitude E6530                     | 1         | 1.28%   |
| Dell Latitude E6440                     | 1         | 1.28%   |
| Dell Inspiron 5570                      | 1         | 1.28%   |
| Dell Inspiron 3442                      | 1         | 1.28%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA | 1         | 1.28%   |
| ASUS K53SC                              | 1         | 1.28%   |
| ASUS K50IE                              | 1         | 1.28%   |
| ASUS GX501VIK                           | 1         | 1.28%   |
| ASUS GL702ZC                            | 1         | 1.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 11        | 14.1%   |
| Lenovo IdeaPad     | 7         | 8.97%   |
| Acer Aspire        | 6         | 7.69%   |
| Dell Precision     | 5         | 6.41%   |
| HP Laptop          | 4         | 5.13%   |
| HP 250             | 3         | 3.85%   |
| Timi RedmiBook     | 2         | 2.56%   |
| HP 15              | 2         | 2.56%   |
| GPD P2             | 2         | 2.56%   |
| Dell Latitude      | 2         | 2.56%   |
| Dell Inspiron      | 2         | 2.56%   |
| Apple MacBookAir7  | 2         | 2.56%   |
| Acer Nitro         | 2         | 2.56%   |
| UNOWHY Y13G010S4EI | 1         | 1.28%   |
| Quanta SWH         | 1         | 1.28%   |
| Notebook N141CU    | 1         | 1.28%   |
| Notebook N130BU    | 1         | 1.28%   |
| MSI Modern         | 1         | 1.28%   |
| MSI GP72           | 1         | 1.28%   |
| LG 17Z990-R.AAC9U1 | 1         | 1.28%   |
| Lenovo ThinkBook   | 1         | 1.28%   |
| Lenovo Legion      | 1         | 1.28%   |
| Lenovo LaVie       | 1         | 1.28%   |
| Lenovo G400s       | 1         | 1.28%   |
| Lenovo B590        | 1         | 1.28%   |
| Lenovo B570e       | 1         | 1.28%   |
| HP ProBook         | 1         | 1.28%   |
| HP OMEN            | 1         | 1.28%   |
| HP 255             | 1         | 1.28%   |
| HP 246             | 1         | 1.28%   |
| Gigabyte B450M     | 1         | 1.28%   |
| Gigabyte AERO      | 1         | 1.28%   |
| ASUS VivoBook      | 1         | 1.28%   |
| ASUS K53SC         | 1         | 1.28%   |
| ASUS K50IE         | 1         | 1.28%   |
| ASUS GX501VIK      | 1         | 1.28%   |
| ASUS GL702ZC       | 1         | 1.28%   |
| ASUS E402NA        | 1         | 1.28%   |
| ASUS 1225C         | 1         | 1.28%   |
| Apple MacBookPro11 | 1         | 1.28%   |
| Acer Swift         | 1         | 1.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 20        | 25.64%  |
| 2019 | 9         | 11.54%  |
| 2018 | 9         | 11.54%  |
| 2017 | 8         | 10.26%  |
| 2016 | 6         | 7.69%   |
| 2012 | 6         | 7.69%   |
| 2011 | 6         | 7.69%   |
| 2014 | 5         | 6.41%   |
| 2013 | 4         | 5.13%   |
| 2015 | 2         | 2.56%   |
| 2021 | 1         | 1.28%   |
| 2010 | 1         | 1.28%   |
| 2009 | 1         | 1.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 78        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 77        | 98.72%  |
| Enabled  | 1         | 1.28%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 78        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 21        | 26.58%  |
| 8.01-16.0   | 21        | 26.58%  |
| 16.01-24.0  | 14        | 17.72%  |
| 3.01-4.0    | 11        | 13.92%  |
| 32.01-64.0  | 4         | 5.06%   |
| 64.01-256.0 | 3         | 3.8%    |
| 1.01-2.0    | 3         | 3.8%    |
| 24.01-32.0  | 2         | 2.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 23        | 25.56%  |
| 4.01-8.0   | 20        | 22.22%  |
| 2.01-3.0   | 18        | 20%     |
| 3.01-4.0   | 14        | 15.56%  |
| 0.51-1.0   | 9         | 10%     |
| 8.01-16.0  | 4         | 4.44%   |
| 16.01-24.0 | 1         | 1.11%   |
| 0.01-0.5   | 1         | 1.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 59        | 74.68%  |
| 2      | 19        | 24.05%  |
| 3      | 1         | 1.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 58        | 74.36%  |
| Yes       | 20        | 25.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 62        | 79.49%  |
| No        | 16        | 20.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 98.72%  |
| No        | 1         | 1.28%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 63        | 78.75%  |
| No        | 17        | 21.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 17        | 21.79%  |
| Russia      | 7         | 8.97%   |
| UK          | 4         | 5.13%   |
| Germany     | 4         | 5.13%   |
| Canada      | 4         | 5.13%   |
| Brazil      | 4         | 5.13%   |
| Ukraine     | 3         | 3.85%   |
| Turkey      | 3         | 3.85%   |
| Netherlands | 3         | 3.85%   |
| Indonesia   | 3         | 3.85%   |
| India       | 3         | 3.85%   |
| France      | 3         | 3.85%   |
| Switzerland | 2         | 2.56%   |
| Spain       | 2         | 2.56%   |
| Poland      | 2         | 2.56%   |
| Uzbekistan  | 1         | 1.28%   |
| Sweden      | 1         | 1.28%   |
| Lithuania   | 1         | 1.28%   |
| Italy       | 1         | 1.28%   |
| Greece      | 1         | 1.28%   |
| Czechia     | 1         | 1.28%   |
| China       | 1         | 1.28%   |
| Chile       | 1         | 1.28%   |
| Bulgaria    | 1         | 1.28%   |
| Bangladesh  | 1         | 1.28%   |
| Azerbaijan  | 1         | 1.28%   |
| Australia   | 1         | 1.28%   |
| Argentina   | 1         | 1.28%   |
| Algeria     | 1         | 1.28%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 3         | 3.61%   |
| Jakarta           | 3         | 3.61%   |
| St Petersburg     | 2         | 2.41%   |
| San Ramon         | 2         | 2.41%   |
| Neuchatel         | 2         | 2.41%   |
| Los Angeles       | 2         | 2.41%   |
| Frankfurt am Main | 2         | 2.41%   |
| Dnipro            | 2         | 2.41%   |
| Amsterdam         | 2         | 2.41%   |
| Zaporizhzhya      | 1         | 1.2%    |
| Wigan             | 1         | 1.2%    |
| Wem               | 1         | 1.2%    |
| Vilnius           | 1         | 1.2%    |
| Vancouver         | 1         | 1.2%    |
| Toronto           | 1         | 1.2%    |
| Tashkent          | 1         | 1.2%    |
| Syeverodonets'k   | 1         | 1.2%    |
| Surgut            | 1         | 1.2%    |
| Stuttgart         | 1         | 1.2%    |
| Stockholm         | 1         | 1.2%    |
| Sofia             | 1         | 1.2%    |
| Snohomish         | 1         | 1.2%    |
| Skikda            | 1         | 1.2%    |
| Sigogne           | 1         | 1.2%    |
| Seville           | 1         | 1.2%    |
| Santiago          | 1         | 1.2%    |
| Santa Fe          | 1         | 1.2%    |
| Samara            | 1         | 1.2%    |
| Sainte-Severe     | 1         | 1.2%    |
| Rio de Janeiro    | 1         | 1.2%    |
| Quincy            | 1         | 1.2%    |
| Puducherry        | 1         | 1.2%    |
| Prague            | 1         | 1.2%    |
| Ordu              | 1         | 1.2%    |
| Omsk              | 1         | 1.2%    |
| Omaha             | 1         | 1.2%    |
| Nantes            | 1         | 1.2%    |
| Mount Pearl       | 1         | 1.2%    |
| Moscow            | 1         | 1.2%    |
| Mississauga       | 1         | 1.2%    |
| Milton            | 1         | 1.2%    |
| Malda             | 1         | 1.2%    |
| Malappuram        | 1         | 1.2%    |
| Liverpool         | 1         | 1.2%    |
| Lexington         | 1         | 1.2%    |
| Leander           | 1         | 1.2%    |
| Lavras            | 1         | 1.2%    |
| Laurel            | 1         | 1.2%    |
| Las Vegas         | 1         | 1.2%    |
| Kłodzko          | 1         | 1.2%    |
| Kavala            | 1         | 1.2%    |
| Hangzhou          | 1         | 1.2%    |
| Hampton           | 1         | 1.2%    |
| Guacui            | 1         | 1.2%    |
| Glide             | 1         | 1.2%    |
| Gilbert           | 1         | 1.2%    |
| Edgware           | 1         | 1.2%    |
| Dronten           | 1         | 1.2%    |
| Dhaka             | 1         | 1.2%    |
| Dalachow          | 1         | 1.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 26     | 21.43%  |
| Seagate             | 12        | 12     | 12.24%  |
| WDC                 | 8         | 11     | 8.16%   |
| Toshiba             | 8         | 8      | 8.16%   |
| SK Hynix            | 5         | 11     | 5.1%    |
| Sandisk             | 5         | 5      | 5.1%    |
| Intel               | 5         | 7      | 5.1%    |
| HGST                | 5         | 5      | 5.1%    |
| Kingston            | 4         | 5      | 4.08%   |
| Hitachi             | 3         | 4      | 3.06%   |
| China               | 3         | 3      | 3.06%   |
| Apple               | 3         | 4      | 3.06%   |
| Unknown             | 2         | 2      | 2.04%   |
| Phison Electronics  | 2         | 3      | 2.04%   |
| Crucial             | 2         | 2      | 2.04%   |
| Timetec             | 1         | 2      | 1.02%   |
| SPCC                | 1         | 1      | 1.02%   |
| Solid State Storage | 1         | 1      | 1.02%   |
| PNY                 | 1         | 1      | 1.02%   |
| Patriot             | 1         | 1      | 1.02%   |
| LITEON              | 1         | 1      | 1.02%   |
| Lite-On             | 1         | 1      | 1.02%   |
| Linux               | 1         | 1      | 1.02%   |
| LDLC                | 1         | 5      | 1.02%   |
| Intenso             | 1         | 1      | 1.02%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB            | 3         | 2.91%   |
| Sandisk NVMe SSD Drive 512GB              | 3         | 2.91%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 2         | 1.94%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 1.94%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 1.94%   |
| Samsung NVMe SSD Drive 1TB                | 2         | 1.94%   |
| Samsung MZNLH512HALU-00000 512GB SSD      | 2         | 1.94%   |
| Phison PCIe SSD 2TB                       | 2         | 1.94%   |
| HGST HTS545050A7E680 500GB                | 2         | 1.94%   |
| China SATA SSD 960GB                      | 2         | 1.94%   |
| Apple SSD SM0256G 256GB                   | 2         | 1.94%   |
| WDC WDS200T2B0B-00YS70 2TB SSD            | 1         | 0.97%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 0.97%   |
| WDC WD5000BPVT-22HXZT3 500GB              | 1         | 0.97%   |
| WDC WD3200LPVT-00FMCT0 320GB              | 1         | 0.97%   |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 0.97%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 1         | 0.97%   |
| Unknown SD/MMC/MS PRO 999GB               | 1         | 0.97%   |
| Unknown DA4064  64GB                      | 1         | 0.97%   |
| Toshiba THNSNH128GMCT 128GB SSD           | 1         | 0.97%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 0.97%   |
| Toshiba MK5065GSX 500GB                   | 1         | 0.97%   |
| Toshiba KBG30ZMT256G 256GB                | 1         | 0.97%   |
| Timetec 35TTM8SSATA-512GB                 | 1         | 0.97%   |
| SPCC Solid State Disk 256GB               | 1         | 0.97%   |
| Solid State Storage SSSTC CL1-4D256 256GB | 1         | 0.97%   |
| SK Hynix SKHynix_HFS512GD9TNI-L2B0B 512GB | 1         | 0.97%   |
| SK Hynix SKHynix_HFS512GD9TNI-L2A0B 512GB | 1         | 0.97%   |
| SK Hynix SC311 SATA 256GB SSD             | 1         | 0.97%   |
| SK Hynix NVMe SSD Drive 1TB               | 1         | 0.97%   |
| SK Hynix NVMe SSD Drive 1024GB            | 1         | 0.97%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB   | 1         | 0.97%   |
| Seagate ST9500325AS 500GB                 | 1         | 0.97%   |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 0.97%   |
| Seagate ST500LT012-9WS142 500GB           | 1         | 0.97%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 0.97%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 0.97%   |
| Seagate ST2000LM015-2E8174 2TB            | 1         | 0.97%   |
| Seagate ST2000LM003 HN-M201RAD 2TB        | 1         | 0.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 0.97%   |
| Seagate BUP Portable 5TB                  | 1         | 0.97%   |
| SanDisk SSD U100 16GB                     | 1         | 0.97%   |
| Sandisk NVMe SSD Drive 500GB              | 1         | 0.97%   |
| Samsung SSD 970 EVO Plus 1TB              | 1         | 0.97%   |
| Samsung SSD 970 EVO 1TB                   | 1         | 0.97%   |
| Samsung SSD 870 EVO 250GB                 | 1         | 0.97%   |
| Samsung SSD 850 EVO 250GB                 | 1         | 0.97%   |
| Samsung SM961 NVMe 512GB                  | 1         | 0.97%   |
| Samsung NVMe SSD Drive 2TB                | 1         | 0.97%   |
| Samsung NVMe SSD Drive 256GB              | 1         | 0.97%   |
| Samsung NVMe SSD Drive 1024GB             | 1         | 0.97%   |
| Samsung MZYTY256HDHP-000L2 256GB SSD      | 1         | 0.97%   |
| Samsung MZVPW256HEGL-000L7 256GB          | 1         | 0.97%   |
| Samsung MZVLQ512HALU-00000 512GB          | 1         | 0.97%   |
| Samsung MZVLB512HBJQ-000H1 512GB          | 1         | 0.97%   |
| Samsung MZVLB256HBHQ-00000 256GB          | 1         | 0.97%   |
| Samsung MZVLB1T0HBLR-000L7 1TB            | 1         | 0.97%   |
| Samsung MZVKW512HMJP-00000 512GB          | 1         | 0.97%   |
| Samsung MZNTE256HMHP-000L1 256GB SSD      | 1         | 0.97%   |
| Samsung MZALQ512HALU-000L2 512GB          | 1         | 0.97%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 12        | 12     | 35.29%  |
| WDC     | 7         | 9      | 20.59%  |
| Toshiba | 6         | 6      | 17.65%  |
| HGST    | 5         | 5      | 14.71%  |
| Hitachi | 3         | 4      | 8.82%   |
| Unknown | 1         | 1      | 2.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 7      | 22.22%  |
| China               | 3         | 3      | 11.11%  |
| Apple               | 3         | 4      | 11.11%  |
| Kingston            | 2         | 2      | 7.41%   |
| Crucial             | 2         | 2      | 7.41%   |
| WDC                 | 1         | 2      | 3.7%    |
| Toshiba             | 1         | 1      | 3.7%    |
| SPCC                | 1         | 1      | 3.7%    |
| SK Hynix            | 1         | 1      | 3.7%    |
| SanDisk             | 1         | 1      | 3.7%    |
| PNY                 | 1         | 1      | 3.7%    |
| Patriot             | 1         | 1      | 3.7%    |
| Linux               | 1         | 1      | 3.7%    |
| LDLC                | 1         | 5      | 3.7%    |
| Intenso             | 1         | 1      | 3.7%    |
| Intel               | 1         | 1      | 3.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 33        | 37     | 36.26%  |
| NVMe    | 31        | 49     | 34.07%  |
| SSD     | 25        | 34     | 27.47%  |
| MMC     | 1         | 1      | 1.1%    |
| Unknown | 1         | 2      | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 54        | 71     | 61.36%  |
| NVMe | 31        | 49     | 35.23%  |
| SAS  | 2         | 2      | 2.27%   |
| MMC  | 1         | 1      | 1.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 32        | 41     | 56.14%  |
| 0.51-1.0   | 21        | 25     | 36.84%  |
| 1.01-2.0   | 3         | 4      | 5.26%   |
| 4.01-10.0  | 1         | 1      | 1.75%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 22        | 27.16%  |
| 251-500        | 21        | 25.93%  |
| 501-1000       | 11        | 13.58%  |
| 1001-2000      | 10        | 12.35%  |
| 51-100         | 5         | 6.17%   |
| Unknown        | 5         | 6.17%   |
| More than 3000 | 4         | 4.94%   |
| 1-20           | 2         | 2.47%   |
| 2001-3000      | 1         | 1.23%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 20        | 22.99%  |
| 101-250        | 16        | 18.39%  |
| 51-100         | 13        | 14.94%  |
| 21-50          | 11        | 12.64%  |
| 501-1000       | 10        | 11.49%  |
| 251-500        | 7         | 8.05%   |
| Unknown        | 5         | 5.75%   |
| 1001-2000      | 3         | 3.45%   |
| More than 3000 | 1         | 1.15%   |
| 2001-3000      | 1         | 1.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB          | 2         | 2      | 16.67%  |
| HGST HTS545050A7E680 500GB      | 2         | 2      | 16.67%  |
| WDC WD3200LPVT-00FMCT0 320GB    | 1         | 1      | 8.33%   |
| Toshiba MK5065GSX 500GB         | 1         | 1      | 8.33%   |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 8.33%   |
| Seagate ST1000LM035-1RK172 1TB  | 1         | 1      | 8.33%   |
| LDLC SSD 120GB                  | 1         | 3      | 8.33%   |
| Hitachi HTS547550A9E384 500GB   | 1         | 1      | 8.33%   |
| Hitachi HTS542516K9SA00 160GB   | 1         | 1      | 8.33%   |
| HGST HTS541010A9E680 1TB        | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 25%     |
| HGST    | 3         | 3      | 25%     |
| Seagate | 2         | 2      | 16.67%  |
| Hitachi | 2         | 2      | 16.67%  |
| WDC     | 1         | 1      | 8.33%   |
| LDLC    | 1         | 3      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 27.27%  |
| HGST    | 3         | 3      | 27.27%  |
| Seagate | 2         | 2      | 18.18%  |
| Hitachi | 2         | 2      | 18.18%  |
| WDC     | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 91.67%  |
| SSD  | 1         | 3      | 8.33%   |

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
| Works    | 44        | 56     | 51.76%  |
| Detected | 29        | 53     | 34.12%  |
| Malfunc  | 12        | 14     | 14.12%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 50        | 52.08%  |
| Samsung Electronics            | 17        | 17.71%  |
| AMD                            | 11        | 11.46%  |
| SK Hynix                       | 4         | 4.17%   |
| Sandisk                        | 4         | 4.17%   |
| Phison Electronics             | 2         | 2.08%   |
| Kingston Technology Company    | 2         | 2.08%   |
| Union Memory (Shenzhen)        | 1         | 1.04%   |
| Toshiba America Info Systems   | 1         | 1.04%   |
| Solid State Storage Technology | 1         | 1.04%   |
| Nvidia                         | 1         | 1.04%   |
| Marvell Technology Group       | 1         | 1.04%   |
| Lite-On Technology             | 1         | 1.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 10%     |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 8%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 7%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 6%      |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 5%      |
| Samsung NVMe SSD Controller 980                                                | 4         | 4%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 4%      |
| SK Hynix Non-Volatile memory controller                                        | 3         | 3%      |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 3%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 3%      |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 3%      |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 2%      |
| Sandisk Non-Volatile memory controller                                         | 2         | 2%      |
| Samsung Electronics SATA controller                                            | 2         | 2%      |
| Phison E12 NVMe Controller                                                     | 2         | 2%      |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 2%      |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2%      |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 2%      |
| Intel SSD 660P Series                                                          | 2         | 2%      |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 2%      |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 2%      |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 2%      |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 2%      |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 1%      |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 1%      |
| Solid State Storage Non-Volatile memory controller                             | 1         | 1%      |
| SK Hynix BC511                                                                 | 1         | 1%      |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 1%      |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 1%      |
| Lite-On Non-Volatile memory controller                                         | 1         | 1%      |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 1%      |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1%      |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1%      |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1%      |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1%      |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 1%      |
| AMD 300 Series Chipset SATA Controller                                         | 1         | 1%      |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 57        | 59.38%  |
| NVMe | 32        | 33.33%  |
| RAID | 7         | 7.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 65        | 83.33%  |
| AMD    | 13        | 16.67%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 7 4700U with Radeon Graphics      | 4         | 5.06%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 2         | 2.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 2.53%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 2.53%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 2.53%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.53%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 2.53%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 2.53%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 2.53%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 2         | 2.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 2.53%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 2.53%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 2.53%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz        | 1         | 1.27%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.27%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.27%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 1.27%   |
| Intel Pentium CPU A1018 @ 2.10GHz           | 1         | 1.27%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 1.27%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1.27%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 1         | 1.27%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 1.27%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.27%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.27%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.27%   |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 1.27%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.27%   |
| Intel Core i7-10850H CPU @ 2.70GHz          | 1         | 1.27%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.27%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.27%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 1         | 1.27%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 1.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.27%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 1.27%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 1.27%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.27%   |
| Intel Core i5-4258U CPU @ 2.40GHz           | 1         | 1.27%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 1         | 1.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.27%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.27%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.27%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.27%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 1.27%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 1         | 1.27%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 1         | 1.27%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.27%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 1         | 1.27%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.27%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 1         | 1.27%   |
| Intel Core 2 Duo CPU T9550 @ 2.66GHz        | 1         | 1.27%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 1         | 1.27%   |
| Intel Celeron N4100 CPU @ 1.10GHz           | 1         | 1.27%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 1         | 1.27%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 1         | 1.27%   |
| Intel Celeron CPU B800 @ 1.50GHz            | 1         | 1.27%   |
| Intel Atom CPU N2800 @ 1.86GHz              | 1         | 1.27%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 1         | 1.27%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 1         | 1.27%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics  | 1         | 1.27%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 21        | 26.92%  |
| Intel Core i7           | 15        | 19.23%  |
| Intel Core i3           | 9         | 11.54%  |
| AMD Ryzen 7             | 7         | 8.97%   |
| Other                   | 4         | 5.13%   |
| Intel Celeron           | 4         | 5.13%   |
| Intel Pentium           | 3         | 3.85%   |
| Intel Core m3           | 2         | 2.56%   |
| Intel Core i9           | 2         | 2.56%   |
| AMD Ryzen 3             | 2         | 2.56%   |
| Intel Xeon              | 1         | 1.28%   |
| Intel Pentium Silver    | 1         | 1.28%   |
| Intel Pentium Dual-Core | 1         | 1.28%   |
| Intel Core 2 Duo        | 1         | 1.28%   |
| Intel Atom              | 1         | 1.28%   |
| AMD Ryzen 9             | 1         | 1.28%   |
| AMD Ryzen 5 PRO         | 1         | 1.28%   |
| AMD Ryzen 5             | 1         | 1.28%   |
| AMD A6                  | 1         | 1.28%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 38        | 48.72%  |
| 4      | 25        | 32.05%  |
| 8      | 9         | 11.54%  |
| 6      | 5         | 6.41%   |
| 12     | 1         | 1.28%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 78        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 61        | 78.21%  |
| 1      | 17        | 21.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 78        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 17.5%   |
| 0x306a9    | 6         | 7.5%    |
| 0x806e9    | 5         | 6.25%   |
| 0x206a7    | 5         | 6.25%   |
| 0x806c1    | 4         | 5%      |
| 0x306d4    | 4         | 5%      |
| 0xa0652    | 3         | 3.75%   |
| 0x906e9    | 3         | 3.75%   |
| 0x806ec    | 3         | 3.75%   |
| 0x806ea    | 3         | 3.75%   |
| 0x706e5    | 3         | 3.75%   |
| 0x40651    | 3         | 3.75%   |
| 0x08600106 | 3         | 3.75%   |
| 0x906ea    | 2         | 2.5%    |
| 0x706a1    | 2         | 2.5%    |
| 0x1067a    | 2         | 2.5%    |
| 0x08600103 | 2         | 2.5%    |
| 0x906ed    | 1         | 1.25%   |
| 0x806eb    | 1         | 1.25%   |
| 0x506c9    | 1         | 1.25%   |
| 0x406e3    | 1         | 1.25%   |
| 0x306c3    | 1         | 1.25%   |
| 0x30678    | 1         | 1.25%   |
| 0x20655    | 1         | 1.25%   |
| 0x08701013 | 1         | 1.25%   |
| 0x08600104 | 1         | 1.25%   |
| 0x0810100b | 1         | 1.25%   |
| 0x08101007 | 1         | 1.25%   |
| 0x08001137 | 1         | 1.25%   |
| 0x0700010b | 1         | 1.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 23        | 29.49%  |
| Zen 2         | 8         | 10.26%  |
| IvyBridge     | 7         | 8.97%   |
| SandyBridge   | 5         | 6.41%   |
| Haswell       | 5         | 6.41%   |
| Broadwell     | 5         | 6.41%   |
| TigerLake     | 4         | 5.13%   |
| CometLake     | 4         | 5.13%   |
| Zen           | 3         | 3.85%   |
| IceLake       | 3         | 3.85%   |
| Penryn        | 2         | 2.56%   |
| Goldmont plus | 2         | 2.56%   |
| Zen+          | 1         | 1.28%   |
| Westmere      | 1         | 1.28%   |
| Skylake       | 1         | 1.28%   |
| Silvermont    | 1         | 1.28%   |
| Jaguar        | 1         | 1.28%   |
| Goldmont      | 1         | 1.28%   |
| Bonnell       | 1         | 1.28%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 59        | 60.82%  |
| Nvidia | 22        | 22.68%  |
| AMD    | 16        | 16.49%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                         | 6         | 6.19%   |
| AMD Renoir                                                                    | 6         | 6.19%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 5         | 5.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 4         | 4.12%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 4         | 4.12%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 4.12%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 4.12%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 3         | 3.09%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 3.09%   |
| Intel UHD Graphics 620                                                        | 3         | 3.09%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 3         | 3.09%   |
| Intel HD Graphics 5500                                                        | 3         | 3.09%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 2.06%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                              | 2         | 2.06%   |
| Nvidia GM108M [GeForce 840M]                                                  | 2         | 2.06%   |
| Intel UHD Graphics 615                                                        | 2         | 2.06%   |
| Intel HD Graphics 630                                                         | 2         | 2.06%   |
| Intel HD Graphics 6000                                                        | 2         | 2.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 2.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 2.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 2.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 1.03%   |
| Nvidia TU117M                                                                 | 1         | 1.03%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                       | 1         | 1.03%   |
| Nvidia GT218M [GeForce 310M]                                                  | 1         | 1.03%   |
| Nvidia GP108M [GeForce MX330]                                                 | 1         | 1.03%   |
| Nvidia GP108M [GeForce MX150]                                                 | 1         | 1.03%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                      | 1         | 1.03%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                         | 1         | 1.03%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 1         | 1.03%   |
| Nvidia GK107M [GeForce GT 650M]                                               | 1         | 1.03%   |
| Nvidia GF119M [GeForce GT 520MX]                                              | 1         | 1.03%   |
| Nvidia GF108M [GeForce GT 520M]                                               | 1         | 1.03%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 1         | 1.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 1.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.03%   |
| Intel HD Graphics P630                                                        | 1         | 1.03%   |
| Intel HD Graphics 500                                                         | 1         | 1.03%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 1.03%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.03%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 1.03%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 1.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.03%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                             | 1         | 1.03%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 1.03%   |
| AMD Saturn XT [FirePro M6100]                                                 | 1         | 1.03%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                       | 1         | 1.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.03%   |
| AMD Lexa XT [Radeon PRO WX 3100]                                              | 1         | 1.03%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                       | 1         | 1.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 1         | 1.03%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 41        | 51.9%   |
| Intel + Nvidia | 15        | 18.99%  |
| 1 x AMD        | 13        | 16.46%  |
| 1 x Nvidia     | 6         | 7.59%   |
| Intel + AMD    | 3         | 3.8%    |
| AMD + Nvidia   | 1         | 1.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 63        | 80.77%  |
| Proprietary | 15        | 19.23%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 65.82%  |
| 0.01-0.5   | 8         | 10.13%  |
| 1.01-2.0   | 7         | 8.86%   |
| 3.01-4.0   | 4         | 5.06%   |
| 0.51-1.0   | 4         | 5.06%   |
| 7.01-8.0   | 2         | 2.53%   |
| 5.01-6.0   | 1         | 1.27%   |
| 2.01-3.0   | 1         | 1.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 16        | 17.58%  |
| AU Optronics            | 16        | 17.58%  |
| LG Display              | 15        | 16.48%  |
| Chimei Innolux          | 10        | 10.99%  |
| Samsung Electronics     | 6         | 6.59%   |
| Dell                    | 4         | 4.4%    |
| InfoVision              | 3         | 3.3%    |
| Apple                   | 3         | 3.3%    |
| Sharp                   | 2         | 2.2%    |
| Hewlett-Packard         | 2         | 2.2%    |
| Goldstar                | 2         | 2.2%    |
| Chi Mei Optoelectronics | 2         | 2.2%    |
| BenQ                    | 2         | 2.2%    |
| ASUSTek Computer        | 2         | 2.2%    |
| Philips                 | 1         | 1.1%    |
| PANDA                   | 1         | 1.1%    |
| MSI                     | 1         | 1.1%    |
| LGD                     | 1         | 1.1%    |
| Lenovo                  | 1         | 1.1%    |
| Ancor Communications    | 1         | 1.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 3.3%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 2         | 2.2%    |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 2.2%    |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 2.2%    |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 2.2%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 2.2%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 2.2%    |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 2.2%    |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 1.1%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 1.1%    |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 1.1%    |
| Samsung Electronics SMB1630N SAM0630 1366x768 340x190mm 15.3-inch         | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 1.1%    |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 1.1%    |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                   | 1         | 1.1%    |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                   | 1         | 1.1%    |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch                   | 1         | 1.1%    |
| LGD LCD Monitor 1920x1080                                                 | 1         | 1.1%    |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch               | 1         | 1.1%    |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 1         | 1.1%    |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch              | 1         | 1.1%    |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch              | 1         | 1.1%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 1         | 1.1%    |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 1.1%    |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch              | 1         | 1.1%    |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 1         | 1.1%    |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch               | 1         | 1.1%    |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch               | 1         | 1.1%    |
| LG Display LCD Monitor LGD03D3 1600x900 309x174mm 14.0-inch               | 1         | 1.1%    |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch               | 1         | 1.1%    |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch               | 1         | 1.1%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 1         | 1.1%    |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch              | 1         | 1.1%    |
| Lenovo LCD Monitor LEN4053 1680x1050 331x207mm 15.4-inch                  | 1         | 1.1%    |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch              | 1         | 1.1%    |
| InfoVision LCD Monitor IVO057C 1366x768 309x174mm 14.0-inch               | 1         | 1.1%    |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch               | 1         | 1.1%    |
| Hewlett-Packard M24f FHD HPN3706 1920x1080 527x296mm 23.8-inch            | 1         | 1.1%    |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch              | 1         | 1.1%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 1         | 1.1%    |
| Goldstar 24EN33 GSM59D6 1920x1080 521x293mm 23.5-inch                     | 1         | 1.1%    |
| Dell P2720DC DELD0FB 2560x1440 597x336mm 27.0-inch                        | 1         | 1.1%    |
| Dell P2217H DELA0D9 1920x1080 476x267mm 21.5-inch                         | 1         | 1.1%    |
| Dell P1911 DELA074 1440x900 408x255mm 18.9-inch                           | 1         | 1.1%    |
| Dell E2310H DELD033 1920x1080 510x287mm 23.0-inch                         | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN175E 1920x1080 381x214mm 17.2-inch          | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch           | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch          | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch          | 1         | 1.1%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 1         | 1.1%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.1%    |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 1         | 1.1%    |
| BOE LCD Monitor BOE0991 1920x1080 344x194mm 15.5-inch                     | 1         | 1.1%    |
| BOE LCD Monitor BOE0918 1920x1080 309x174mm 14.0-inch                     | 1         | 1.1%    |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                     | 1         | 1.1%    |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                      | 1         | 1.1%    |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                     | 1         | 1.1%    |
| BOE LCD Monitor BOE0754 1366x768 256x144mm 11.6-inch                      | 1         | 1.1%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 40        | 46.51%  |
| 1366x768 (WXGA)    | 28        | 32.56%  |
| 1440x900 (WXGA+)   | 4         | 4.65%   |
| 3840x2160 (4K)     | 3         | 3.49%   |
| 2560x1440 (QHD)    | 3         | 3.49%   |
| 1600x900 (HD+)     | 3         | 3.49%   |
| 2560x1600          | 2         | 2.33%   |
| 3440x1440          | 1         | 1.16%   |
| 1920x1200 (WUXGA)  | 1         | 1.16%   |
| 1680x1050 (WSXGA+) | 1         | 1.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 38        | 42.22%  |
| 13      | 14        | 15.56%  |
| 14      | 12        | 13.33%  |
| 17      | 6         | 6.67%   |
| 24      | 5         | 5.56%   |
| 27      | 3         | 3.33%   |
| 21      | 3         | 3.33%   |
| 23      | 2         | 2.22%   |
| 11      | 2         | 2.22%   |
| 34      | 1         | 1.11%   |
| 20      | 1         | 1.11%   |
| 19      | 1         | 1.11%   |
| 12      | 1         | 1.11%   |
| Unknown | 1         | 1.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 57        | 63.33%  |
| 501-600     | 9         | 10%     |
| 351-400     | 8         | 8.89%   |
| 201-300     | 8         | 8.89%   |
| 401-500     | 5         | 5.56%   |
| 701-800     | 1         | 1.11%   |
| 601-700     | 1         | 1.11%   |
| Unknown     | 1         | 1.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 68        | 87.18%  |
| 16/10   | 8         | 10.26%  |
| 21/9    | 1         | 1.28%   |
| Unknown | 1         | 1.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 38        | 42.22%  |
| 81-90          | 21        | 23.33%  |
| 201-250        | 9         | 10%     |
| 71-80          | 5         | 5.56%   |
| 121-130        | 5         | 5.56%   |
| 301-350        | 3         | 3.33%   |
| 51-60          | 2         | 2.22%   |
| 151-200        | 2         | 2.22%   |
| 61-70          | 1         | 1.11%   |
| 351-500        | 1         | 1.11%   |
| 251-300        | 1         | 1.11%   |
| 131-140        | 1         | 1.11%   |
| Unknown        | 1         | 1.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 42        | 47.73%  |
| 101-120       | 26        | 29.55%  |
| 51-100        | 14        | 15.91%  |
| 161-240       | 4         | 4.55%   |
| More than 240 | 1         | 1.14%   |
| Unknown       | 1         | 1.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 66        | 82.5%   |
| 2     | 14        | 17.5%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 50        | 38.76%  |
| Intel                 | 42        | 32.56%  |
| Qualcomm Atheros      | 17        | 13.18%  |
| Broadcom              | 8         | 6.2%    |
| Broadcom Limited      | 3         | 2.33%   |
| Ralink                | 2         | 1.55%   |
| Xiaomi                | 1         | 0.78%   |
| Sierra Wireless       | 1         | 0.78%   |
| Ralink Technology     | 1         | 0.78%   |
| Qualcomm              | 1         | 0.78%   |
| Linksys               | 1         | 0.78%   |
| Huawei Technologies   | 1         | 0.78%   |
| Apple                 | 1         | 0.78%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 20.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 5.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 3.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 3.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 3.31%   |
| Intel Wireless 8265 / 8275                                        | 5         | 3.31%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 3.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 3.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.65%   |
| Intel Wireless 7265                                               | 4         | 2.65%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 2.65%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.99%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.99%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.32%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 1.32%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.32%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.32%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.32%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 1.32%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.32%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.66%   |
| Sierra Wireless MC7700                                            | 1         | 0.66%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.66%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.66%   |
| Realtek 802.11ac NIC                                              | 1         | 0.66%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.66%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.66%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1         | 0.66%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.66%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.66%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.66%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.66%   |
| Qualcomm A0001                                                    | 1         | 0.66%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.66%   |
| Intel Wireless-AC 9260                                            | 1         | 0.66%   |
| Intel Wireless 3165                                               | 1         | 0.66%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 0.66%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.66%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.66%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 0.66%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 0.66%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 0.66%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 0.66%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.66%   |
| Huawei E353/E3131                                                 | 1         | 0.66%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.66%   |
| Apple iPad 4/Mini1                                                | 1         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 39        | 47.56%  |
| Realtek Semiconductor | 15        | 18.29%  |
| Qualcomm Atheros      | 14        | 17.07%  |
| Broadcom              | 7         | 8.54%   |
| Broadcom Limited      | 3         | 3.66%   |
| Ralink                | 2         | 2.44%   |
| Sierra Wireless       | 1         | 1.22%   |
| Ralink Technology     | 1         | 1.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 6.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 6.1%    |
| Intel Wireless 8265 / 8275                                     | 5         | 6.1%    |
| Intel Wi-Fi 6 AX200                                            | 5         | 6.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 4.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 4.88%   |
| Intel Wireless 7265                                            | 4         | 4.88%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 4.88%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 3.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 3.66%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 3.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 3.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 2.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 2.44%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 2.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.44%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 2.44%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 2.44%   |
| Sierra Wireless MC7700                                         | 1         | 1.22%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.22%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.22%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.22%   |
| Realtek 802.11ac NIC                                           | 1         | 1.22%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.22%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.22%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1         | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.22%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.22%   |
| Intel Wireless-AC 9260                                         | 1         | 1.22%   |
| Intel Wireless 3165                                            | 1         | 1.22%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.22%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 1.22%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.22%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 45        | 66.18%  |
| Intel                 | 13        | 19.12%  |
| Qualcomm Atheros      | 4         | 5.88%   |
| Xiaomi                | 1         | 1.47%   |
| Qualcomm              | 1         | 1.47%   |
| Linksys               | 1         | 1.47%   |
| Huawei Technologies   | 1         | 1.47%   |
| Broadcom              | 1         | 1.47%   |
| Apple                 | 1         | 1.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 31        | 44.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 13.04%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 8.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 7.25%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.9%    |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 2.9%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.45%   |
| Qualcomm A0001                                                    | 1         | 1.45%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 1.45%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.45%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.45%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.45%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.45%   |
| Huawei E353/E3131                                                 | 1         | 1.45%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.45%   |
| Apple iPad 4/Mini1                                                | 1         | 1.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 77        | 55.4%   |
| Ethernet | 62        | 44.6%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 62        | 79.49%  |
| Ethernet | 16        | 20.51%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 56        | 70.89%  |
| 1     | 21        | 26.58%  |
| 3     | 2         | 2.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 72        | 88.89%  |
| Yes  | 9         | 11.11%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 52.38%  |
| Realtek Semiconductor           | 10        | 15.87%  |
| Broadcom                        | 4         | 6.35%   |
| Qualcomm Atheros Communications | 3         | 4.76%   |
| Lite-On Technology              | 3         | 4.76%   |
| Apple                           | 3         | 4.76%   |
| Realtek                         | 2         | 3.17%   |
| Foxconn / Hon Hai               | 2         | 3.17%   |
| Ralink                          | 1         | 1.59%   |
| IMC Networks                    | 1         | 1.59%   |
| Cambridge Silicon Radio         | 1         | 1.59%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 15.87%  |
| Intel AX201 Bluetooth                               | 10        | 15.87%  |
| Realtek Bluetooth Radio                             | 5         | 7.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 7.94%   |
| Intel AX200 Bluetooth                               | 5         | 7.94%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 4.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 4.76%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 3.17%   |
| Realtek Bluetooth Radio                             | 2         | 3.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 3.17%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 3.17%   |
| Apple Bluetooth USB Host Controller                 | 2         | 3.17%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.59%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.59%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.59%   |
| IMC Networks Bluetooth Device                       | 1         | 1.59%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.59%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.59%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.59%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.59%   |
| Apple Bluetooth Host Controller                     | 1         | 1.59%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 64        | 64.65%  |
| Nvidia                | 14        | 14.14%  |
| AMD                   | 14        | 14.14%  |
| C-Media Electronics   | 3         | 3.03%   |
| Realtek Semiconductor | 2         | 2.02%   |
| Plantronics           | 1         | 1.01%   |
| Corsair               | 1         | 1.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 12        | 9.84%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 8.2%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 5.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 4.1%    |
| Intel Broadwell-U Audio Controller                                         | 5         | 4.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 4.1%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 4.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 3.28%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 3.28%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 3.28%   |
| Intel CM238 HD Audio Controller                                            | 4         | 3.28%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 3.28%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 2.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 3         | 2.46%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.46%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 2.46%   |
| Realtek Semiconductor USB Audio                                            | 2         | 1.64%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.64%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.64%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.64%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.64%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 1.64%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.82%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.82%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.82%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.82%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.82%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.82%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 0.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 0.82%   |
| Corsair HS45 Surround USB Sound Adapter                                    | 1         | 0.82%   |
| C-Media Electronics SADES Luna                                             | 1         | 0.82%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 1         | 0.82%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 1         | 0.82%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 0.82%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 0.82%   |
| AMD FCH Azalia Controller                                                  | 1         | 0.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 0.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 0.82%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 25        | 31.25%  |
| SK Hynix            | 23        | 28.75%  |
| Kingston            | 7         | 8.75%   |
| Micron Technology   | 6         | 7.5%    |
| Unknown             | 3         | 3.75%   |
| A-DATA Technology   | 3         | 3.75%   |
| Silicon Power       | 2         | 2.5%    |
| Ramaxel Technology  | 2         | 2.5%    |
| Corsair             | 2         | 2.5%    |
| Unknown (ABCD)      | 1         | 1.25%   |
| Team                | 1         | 1.25%   |
| Smart Brazil        | 1         | 1.25%   |
| Smart               | 1         | 1.25%   |
| Nanya Technology    | 1         | 1.25%   |
| ASint Technology    | 1         | 1.25%   |
| Unknown             | 1         | 1.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 3         | 3.53%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s          | 3         | 3.53%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 2         | 2.35%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s          | 2         | 2.35%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s    | 2         | 2.35%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s          | 2         | 2.35%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s             | 2         | 2.35%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 2         | 2.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s           | 2         | 2.35%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s           | 2         | 2.35%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s          | 2         | 2.35%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s       | 2         | 2.35%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s          | 2         | 2.35%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s           | 2         | 2.35%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 1.18%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                     | 1         | 1.18%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                | 1         | 1.18%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s  | 1         | 1.18%   |
| Team RAM TEAMGROUP-SD3-1600 4GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2400MT/s           | 1         | 1.18%   |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 2933MT/s | 1         | 1.18%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |
| SK Hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |
| SK Hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s       | 1         | 1.18%   |
| SK Hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8192MB Row Of Chips DDR4 3200MT/s | 1         | 1.18%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s          | 1         | 1.18%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s         | 1         | 1.18%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s       | 1         | 1.18%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s          | 1         | 1.18%   |
| SK Hynix RAM HCNNNBKMBLHR-NEE 1GB Row Of Chips LPDDR4 4267MT/s  | 1         | 1.18%   |
| Silicon Power RAM SP016GBSFU266B02 16GB SODIMM DDR4 2667MT/s    | 1         | 1.18%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s     | 1         | 1.18%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                    | 1         | 1.18%   |
| Samsung RAM M471B5273DM0-CK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s           | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s           | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s          | 1         | 1.18%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s           | 1         | 1.18%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s           | 1         | 1.18%   |
| Samsung RAM K4E6E304EE-EGCE 4096MB 1600MT/s                     | 1         | 1.18%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s         | 1         | 1.18%   |
| Ramaxel RAM RMT3020EC58E9F1333 4096MB SODIMM DDR3 4199MT/s      | 1         | 1.18%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s            | 1         | 1.18%   |
| Micron RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 1.18%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s           | 1         | 1.18%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s           | 1         | 1.18%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4096MB SODIMM DDR4 2133MT/s        | 1         | 1.18%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16GB SODIMM DDR4 2400MT/s          | 1         | 1.18%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s           | 1         | 1.18%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s            | 1         | 1.18%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s         | 1         | 1.18%   |
| Kingston RAM ACR26D4S9S1ME-4 4GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s          | 1         | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 37        | 55.22%  |
| DDR3    | 22        | 32.84%  |
| LPDDR4  | 3         | 4.48%   |
| SDRAM   | 2         | 2.99%   |
| LPDDR3  | 2         | 2.99%   |
| Unknown | 1         | 1.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 59        | 88.06%  |
| Row Of Chips | 6         | 8.96%   |
| DIMM         | 1         | 1.49%   |
| Unknown      | 1         | 1.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 30        | 40%     |
| 8192  | 23        | 30.67%  |
| 16384 | 11        | 14.67%  |
| 2048  | 8         | 10.67%  |
| 32768 | 2         | 2.67%   |
| 1024  | 1         | 1.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 23        | 31.94%  |
| 3200  | 14        | 19.44%  |
| 2667  | 13        | 18.06%  |
| 2400  | 9         | 12.5%   |
| 1333  | 3         | 4.17%   |
| 4199  | 2         | 2.78%   |
| 2133  | 2         | 2.78%   |
| 4267  | 1         | 1.39%   |
| 3400  | 1         | 1.39%   |
| 3266  | 1         | 1.39%   |
| 2933  | 1         | 1.39%   |
| 1334  | 1         | 1.39%   |
| 1066  | 1         | 1.39%   |

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
| Chicony Electronics                    | 16        | 23.19%  |
| Realtek Semiconductor                  | 9         | 13.04%  |
| Acer                                   | 8         | 11.59%  |
| Quanta                                 | 7         | 10.14%  |
| IMC Networks                           | 6         | 8.7%    |
| Suyin                                  | 5         | 7.25%   |
| Syntek                                 | 3         | 4.35%   |
| Alcor Micro                            | 3         | 4.35%   |
| Silicon Motion                         | 2         | 2.9%    |
| Microdia                               | 2         | 2.9%    |
| Luxvisions Innotech Limited            | 2         | 2.9%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.9%    |
| Sunplus Innovation Technology          | 1         | 1.45%   |
| Lite-On Technology                     | 1         | 1.45%   |
| LG Electronics                         | 1         | 1.45%   |
| Lenovo                                 | 1         | 1.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                 | 5         | 7.25%   |
| Realtek Integrated_Webcam_HD                                   | 4         | 5.8%    |
| Chicony Integrated Camera                                      | 4         | 5.8%    |
| Chicony HD WebCam                                              | 4         | 5.8%    |
| Syntek EasyCamera                                              | 2         | 2.9%    |
| Suyin HP Webcam                                                | 2         | 2.9%    |
| Silicon Motion 300k Pixel Camera                               | 2         | 2.9%    |
| Realtek USB2.0 HD UVC WebCam                                   | 2         | 2.9%    |
| Realtek HD WebCam                                              | 2         | 2.9%    |
| Quanta HP Webcam                                               | 2         | 2.9%    |
| Quanta HP TrueVision HD Camera                                 | 2         | 2.9%    |
| Chicony Integrated Camera (1280x720@30)                        | 2         | 2.9%    |
| Acer Integrated Camera                                         | 2         | 2.9%    |
| Syntek Integrated Camera                                       | 1         | 1.45%   |
| Suyin USB Webcam                                               | 1         | 1.45%   |
| Suyin NEC HD WebCam                                            | 1         | 1.45%   |
| Suyin 1.3M HD WebCam                                           | 1         | 1.45%   |
| Sunplus HD WebCam                                              | 1         | 1.45%   |
| Realtek Integrated Webcam                                      | 1         | 1.45%   |
| Quanta VGA WebCam                                              | 1         | 1.45%   |
| Quanta USB2.0 VGA UVC WebCam                                   | 1         | 1.45%   |
| Quanta HD User Facing                                          | 1         | 1.45%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 1.45%   |
| Microdia Integrated Webcam                                     | 1         | 1.45%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 1.45%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 1.45%   |
| Lite-On HP HD Camera                                           | 1         | 1.45%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)          | 1         | 1.45%   |
| Lenovo UVC Camera                                              | 1         | 1.45%   |
| IMC Networks Integrated Webcam                                 | 1         | 1.45%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 1.45%   |
| Chicony USB2.0 Camera                                          | 1         | 1.45%   |
| Chicony USB2.0 0.3M UVC WebCam                                 | 1         | 1.45%   |
| Chicony Thinkpad T430 camera                                   | 1         | 1.45%   |
| Chicony LG Camera                                              | 1         | 1.45%   |
| Chicony Lenovo EasyCamera                                      | 1         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 1         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.45%   |
| Alcor Micro USB 2.0 Camera                                     | 1         | 1.45%   |
| Alcor Micro Lenovo EasyCamera                                  | 1         | 1.45%   |
| Alcor Micro Asus Integrated Webcam                             | 1         | 1.45%   |
| Acer Lenovo Integrated Webcam                                  | 1         | 1.45%   |
| Acer Lenovo EasyCamera                                         | 1         | 1.45%   |
| Acer Integrated 5M Camera                                      | 1         | 1.45%   |
| Acer HD Webcam                                                 | 1         | 1.45%   |
| Acer BisonCam,NB Pro                                           | 1         | 1.45%   |
| Acer BisonCam, NB Pro                                          | 1         | 1.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 42.86%  |
| Shenzhen Goodix Technology | 3         | 42.86%  |
| AuthenTec                  | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 42.86%  |
| Shenzhen Goodix  FingerPrint Device               | 3         | 42.86%  |
| AuthenTec AES2810                                 | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 33.33%  |
| Broadcom 58200                                                               | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 56        | 70%     |
| 1     | 20        | 25%     |
| 2     | 4         | 5%      |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 7         | 24.14%  |
| Net/wireless             | 4         | 13.79%  |
| Multimedia controller    | 4         | 13.79%  |
| Graphics card            | 4         | 13.79%  |
| Camera                   | 4         | 13.79%  |
| Chipcard                 | 2         | 6.9%    |
| Storage                  | 1         | 3.45%   |
| Dvb card                 | 1         | 3.45%   |
| Communication controller | 1         | 3.45%   |
| Bluetooth                | 1         | 3.45%   |

