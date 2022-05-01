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

Total: 120

| Vendor   | Model                       | Probe                                                      | Date         |
|----------|-----------------------------|------------------------------------------------------------|--------------|
| HP       | 15                          | [d9ed47d44c](https://linux-hardware.org/?probe=d9ed47d44c) | Apr 23, 2022 |
| Lenovo   | ThinkBook 15 G2 ITL 20VE    | [85b1934bfd](https://linux-hardware.org/?probe=85b1934bfd) | Apr 21, 2022 |
| ASUSTek  | GX501VIK                    | [076208c6fd](https://linux-hardware.org/?probe=076208c6fd) | Apr 15, 2022 |
| ASUSTek  | GX501VIK                    | [15c4c7877b](https://linux-hardware.org/?probe=15c4c7877b) | Apr 15, 2022 |
| Lenovo   | ThinkPad T430 2350BC6       | [c2ffb2a421](https://linux-hardware.org/?probe=c2ffb2a421) | Apr 14, 2022 |
| HP       | 246                         | [4ef673dd00](https://linux-hardware.org/?probe=4ef673dd00) | Apr 10, 2022 |
| Lenovo   | ThinkPad T430 2347H76       | [493f378237](https://linux-hardware.org/?probe=493f378237) | Mar 10, 2022 |
| HP       | Laptop 14s-dq2xxx           | [92db061239](https://linux-hardware.org/?probe=92db061239) | Mar 09, 2022 |
| Lenovo   | IdeaPad Y500 20193          | [604362a51f](https://linux-hardware.org/?probe=604362a51f) | Feb 18, 2022 |
| Notebook | N141CU                      | [029f48bc53](https://linux-hardware.org/?probe=029f48bc53) | Feb 16, 2022 |
| Acer     | Aspire V3-472PG             | [70c80ae356](https://linux-hardware.org/?probe=70c80ae356) | Feb 16, 2022 |
| HP       | Laptop 15-ef1xxx            | [6cf7935dcc](https://linux-hardware.org/?probe=6cf7935dcc) | Feb 14, 2022 |
| Timi     | RedmiBook 14 II             | [3c1248a9d9](https://linux-hardware.org/?probe=3c1248a9d9) | Feb 10, 2022 |
| ASUSTek  | 1225C                       | [b780589dd0](https://linux-hardware.org/?probe=b780589dd0) | Feb 07, 2022 |
| HP       | Laptop 15-ef1xxx            | [6a49ff6317](https://linux-hardware.org/?probe=6a49ff6317) | Jan 18, 2022 |
| Lenovo   | G400s 20244                 | [9ac1aa04cc](https://linux-hardware.org/?probe=9ac1aa04cc) | Jan 15, 2022 |
| Lenovo   | ThinkPad E14 Gen 2 20T60... | [945649c354](https://linux-hardware.org/?probe=945649c354) | Jan 07, 2022 |
| MSI      | Modern 15 A11M              | [bef1d4552a](https://linux-hardware.org/?probe=bef1d4552a) | Jan 07, 2022 |
| Lenovo   | Legion 5 15ARH05H 82B1      | [a568bef730](https://linux-hardware.org/?probe=a568bef730) | Jan 05, 2022 |
| Lenovo   | B570e HuronRiver Platfor... | [a6c63e1079](https://linux-hardware.org/?probe=a6c63e1079) | Dec 17, 2021 |
| Dell     | Latitude E6440              | [5e572f557c](https://linux-hardware.org/?probe=5e572f557c) | Dec 16, 2021 |
| Dell     | Latitude E6440              | [ac94463e37](https://linux-hardware.org/?probe=ac94463e37) | Dec 16, 2021 |
| ASUSTek  | K50IE                       | [49a6b75a43](https://linux-hardware.org/?probe=49a6b75a43) | Nov 29, 2021 |
| Lenovo   | ThinkBook 15 G2 ITL 20VE    | [0e12642e78](https://linux-hardware.org/?probe=0e12642e78) | Nov 27, 2021 |
| Timi     | RedmiBook 14 II             | [3e700c917e](https://linux-hardware.org/?probe=3e700c917e) | Nov 25, 2021 |
| Lenovo   | ThinkPad 11e 5th Gen 20L... | [9a5098383d](https://linux-hardware.org/?probe=9a5098383d) | Nov 24, 2021 |
| Lenovo   | ThinkPad T480s 20L8S3D40... | [76be488014](https://linux-hardware.org/?probe=76be488014) | Nov 07, 2021 |
| Lenovo   | ThinkPad T480s 20L8S3D40... | [f96363ccf5](https://linux-hardware.org/?probe=f96363ccf5) | Nov 07, 2021 |
| HP       | ProBook 450 G6              | [ded9086b7c](https://linux-hardware.org/?probe=ded9086b7c) | Nov 06, 2021 |
| Timi     | RedmiBook 14 II             | [038c0ad664](https://linux-hardware.org/?probe=038c0ad664) | Nov 03, 2021 |
| Timi     | RedmiBook 14 II             | [d8ae8a047c](https://linux-hardware.org/?probe=d8ae8a047c) | Nov 02, 2021 |
| Acer     | Swift SF314-59              | [c764d879fb](https://linux-hardware.org/?probe=c764d879fb) | Sep 27, 2021 |
| Acer     | Swift SF314-59              | [0107549144](https://linux-hardware.org/?probe=0107549144) | Sep 23, 2021 |
| Acer     | Swift SF314-59              | [9426a6d4df](https://linux-hardware.org/?probe=9426a6d4df) | Sep 23, 2021 |
| Acer     | Aspire E5-575               | [d32c769f65](https://linux-hardware.org/?probe=d32c769f65) | Sep 22, 2021 |
| HP       | Laptop 14s-cf3xxx           | [5b9800e687](https://linux-hardware.org/?probe=5b9800e687) | Sep 06, 2021 |
| Dell     | Precision M6600             | [3c06ad8f67](https://linux-hardware.org/?probe=3c06ad8f67) | Sep 06, 2021 |
| ASUSTek  | GL702ZC                     | [7cb34b0a2e](https://linux-hardware.org/?probe=7cb34b0a2e) | Aug 10, 2021 |
| ASUSTek  | GL702ZC                     | [8ab07e196d](https://linux-hardware.org/?probe=8ab07e196d) | Aug 09, 2021 |
| GPD      | P2 MAX                      | [bf70dbe409](https://linux-hardware.org/?probe=bf70dbe409) | Aug 07, 2021 |
| GPD      | P2 MAX                      | [a4e8eb7d9e](https://linux-hardware.org/?probe=a4e8eb7d9e) | Aug 07, 2021 |
| GPD      | P2 MAX                      | [43075e1581](https://linux-hardware.org/?probe=43075e1581) | Jul 23, 2021 |
| HP       | 250 G3                      | [b1a0952727](https://linux-hardware.org/?probe=b1a0952727) | Jul 19, 2021 |
| Dell     | Inspiron 3442               | [a4e06ddea2](https://linux-hardware.org/?probe=a4e06ddea2) | Jul 02, 2021 |
| Lenovo   | LaVie Z 20FF0012US          | [789d556ef6](https://linux-hardware.org/?probe=789d556ef6) | Jul 01, 2021 |
| Lenovo   | ThinkPad W500 4063CJ5       | [89bbafa02e](https://linux-hardware.org/?probe=89bbafa02e) | Jun 22, 2021 |
| HP       | 15                          | [4f6c5d8c89](https://linux-hardware.org/?probe=4f6c5d8c89) | Jun 22, 2021 |
| Apple    | MacBookAir7,2               | [6a459ac265](https://linux-hardware.org/?probe=6a459ac265) | Jun 16, 2021 |
| HP       | 250 G7 Notebook PC          | [10803bcbc4](https://linux-hardware.org/?probe=10803bcbc4) | Jun 07, 2021 |
| HP       | 250 G7 Notebook PC          | [445e09faa7](https://linux-hardware.org/?probe=445e09faa7) | Jun 07, 2021 |
| Dell     | Precision 7550              | [5d7ecb9bbb](https://linux-hardware.org/?probe=5d7ecb9bbb) | Jun 07, 2021 |
| Lenovo   | IdeaPad Gaming 3 15IMH05... | [de11ab3cc4](https://linux-hardware.org/?probe=de11ab3cc4) | May 31, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20UES... | [4688dc5b46](https://linux-hardware.org/?probe=4688dc5b46) | May 29, 2021 |
| Dell     | Precision 7550              | [206eeb06c9](https://linux-hardware.org/?probe=206eeb06c9) | May 23, 2021 |
| Dell     | Precision 7550              | [e7ccee4869](https://linux-hardware.org/?probe=e7ccee4869) | May 23, 2021 |
| UNOWHY   | Y13G010S4EI                 | [62d883cffd](https://linux-hardware.org/?probe=62d883cffd) | May 18, 2021 |
| Lenovo   | ThinkPad W500 4063CJ5       | [85def78a94](https://linux-hardware.org/?probe=85def78a94) | May 02, 2021 |
| HP       | Laptop 17z-ca300            | [ea09357867](https://linux-hardware.org/?probe=ea09357867) | Apr 26, 2021 |
| Acer     | Aspire V3-572PG             | [a874b34c2a](https://linux-hardware.org/?probe=a874b34c2a) | Apr 12, 2021 |
| Apple    | MacBookAir7,2               | [7f14077ecc](https://linux-hardware.org/?probe=7f14077ecc) | Mar 29, 2021 |
| Apple    | MacBookPro11,1              | [666815417c](https://linux-hardware.org/?probe=666815417c) | Mar 28, 2021 |
| Apple    | MacBookPro11,1              | [cc467b4015](https://linux-hardware.org/?probe=cc467b4015) | Mar 27, 2021 |
| Apple    | MacBookPro11,1              | [d2027dc1c2](https://linux-hardware.org/?probe=d2027dc1c2) | Mar 24, 2021 |
| MSI      | GP72 7RDX                   | [a60abbdcd4](https://linux-hardware.org/?probe=a60abbdcd4) | Mar 18, 2021 |
| Quanta   | SWH                         | [dc6df30340](https://linux-hardware.org/?probe=dc6df30340) | Mar 18, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20S1S... | [c2599a37c2](https://linux-hardware.org/?probe=c2599a37c2) | Mar 08, 2021 |
| Lenovo   | ThinkPad T14 Gen 1 20UES... | [76006e9ba5](https://linux-hardware.org/?probe=76006e9ba5) | Mar 01, 2021 |
| Dell     | Precision 7550              | [c1c4fd3b1a](https://linux-hardware.org/?probe=c1c4fd3b1a) | Feb 21, 2021 |
| Lenovo   | ThinkPad W500 4063CJ5       | [b25144d80b](https://linux-hardware.org/?probe=b25144d80b) | Feb 18, 2021 |
| Lenovo   | ThinkPad P1 Gen 3 20TH00... | [c2408f8152](https://linux-hardware.org/?probe=c2408f8152) | Feb 16, 2021 |
| Lenovo   | ThinkPad W500 4063CJ5       | [838f747450](https://linux-hardware.org/?probe=838f747450) | Feb 14, 2021 |
| Lenovo   | ThinkPad W500 4063CJ5       | [214d72ae23](https://linux-hardware.org/?probe=214d72ae23) | Feb 12, 2021 |
| Acer     | Aspire 5733Z                | [b15b48fb21](https://linux-hardware.org/?probe=b15b48fb21) | Jan 29, 2021 |
| Lenovo   | ThinkPad W500 4063CJ5       | [dd81f9c015](https://linux-hardware.org/?probe=dd81f9c015) | Jan 23, 2021 |
| ASUSTek  | K53SC                       | [11547cb913](https://linux-hardware.org/?probe=11547cb913) | Jan 22, 2021 |
| ASUSTek  | K53SC                       | [061c52c2ff](https://linux-hardware.org/?probe=061c52c2ff) | Jan 22, 2021 |
| HP       | ProBook 450 G6              | [40e4f5d2fb](https://linux-hardware.org/?probe=40e4f5d2fb) | Jan 21, 2021 |
| Dell     | Precision 5520              | [a714973647](https://linux-hardware.org/?probe=a714973647) | Jan 16, 2021 |
| ASUSTek  | E402NA                      | [ac894b264b](https://linux-hardware.org/?probe=ac894b264b) | Jan 10, 2021 |
| Apple    | MacBookPro11,1              | [e8ac486033](https://linux-hardware.org/?probe=e8ac486033) | Jan 09, 2021 |
| Acer     | Aspire A315-53              | [abac7a5b07](https://linux-hardware.org/?probe=abac7a5b07) | Jan 02, 2021 |
| Dell     | Precision 7550              | [9c8b2f2ad6](https://linux-hardware.org/?probe=9c8b2f2ad6) | Dec 30, 2020 |
| Gigabyte | B450M DS3H-CF               | [b9c02872aa](https://linux-hardware.org/?probe=b9c02872aa) | Dec 29, 2020 |
| Dell     | Latitude E6530              | [46704587d1](https://linux-hardware.org/?probe=46704587d1) | Dec 25, 2020 |
| Gigabyte | B450M DS3H-CF               | [d2701aa534](https://linux-hardware.org/?probe=d2701aa534) | Dec 24, 2020 |
| HP       | 250 G4 Notebook PC          | [178de0b283](https://linux-hardware.org/?probe=178de0b283) | Dec 24, 2020 |
| Lenovo   | ThinkPad W500 4063CJ5       | [a905f1377a](https://linux-hardware.org/?probe=a905f1377a) | Dec 20, 2020 |
| GPD      | P2 MAX                      | [f6249e6387](https://linux-hardware.org/?probe=f6249e6387) | Dec 11, 2020 |
| Sony     | VPCCB17FG                   | [5a24dc3231](https://linux-hardware.org/?probe=5a24dc3231) | Nov 26, 2020 |
| Acer     | Aspire A315-53              | [bc80dc5050](https://linux-hardware.org/?probe=bc80dc5050) | Nov 25, 2020 |
| Lenovo   | IdeaPad L340-17IRH Gamin... | [53a1586791](https://linux-hardware.org/?probe=53a1586791) | Nov 12, 2020 |
| HP       | OMEN Laptop 15-en0xxx       | [61653c183a](https://linux-hardware.org/?probe=61653c183a) | Oct 30, 2020 |
| ASUSTek  | VivoBook_ASUS Laptop X50... | [f18b33a8f0](https://linux-hardware.org/?probe=f18b33a8f0) | Oct 25, 2020 |
| ASUSTek  | VivoBook_ASUS Laptop X50... | [acc8c4e663](https://linux-hardware.org/?probe=acc8c4e663) | Oct 25, 2020 |
| Lenovo   | ThinkPad W500 4063CJ5       | [7c29a97dff](https://linux-hardware.org/?probe=7c29a97dff) | Oct 21, 2020 |
| Lenovo   | ThinkPad W500 4063CJ5       | [961c0be28a](https://linux-hardware.org/?probe=961c0be28a) | Oct 18, 2020 |
| Dell     | Inspiron 5570               | [038ef2ebaa](https://linux-hardware.org/?probe=038ef2ebaa) | Oct 15, 2020 |
| Lenovo   | IdeaPad 5 15IIL05 81YK      | [b877caba0b](https://linux-hardware.org/?probe=b877caba0b) | Oct 13, 2020 |
| HP       | 255 G7 Notebook PC          | [026a4d80f6](https://linux-hardware.org/?probe=026a4d80f6) | Oct 08, 2020 |
| Dell     | Precision 7550              | [c574758854](https://linux-hardware.org/?probe=c574758854) | Sep 19, 2020 |
| Dell     | Precision 7550              | [4b12417b4c](https://linux-hardware.org/?probe=4b12417b4c) | Sep 15, 2020 |
| Dell     | Precision 7550              | [14d1876313](https://linux-hardware.org/?probe=14d1876313) | Aug 31, 2020 |
| Dell     | Precision 7550              | [d44c1dbf60](https://linux-hardware.org/?probe=d44c1dbf60) | Aug 31, 2020 |
| Dell     | Precision 7550              | [25d7f344e9](https://linux-hardware.org/?probe=25d7f344e9) | Aug 29, 2020 |
| Acer     | Nitro AN515-51              | [4f2724d5ad](https://linux-hardware.org/?probe=4f2724d5ad) | Aug 16, 2020 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | [aae7fd244a](https://linux-hardware.org/?probe=aae7fd244a) | Aug 06, 2020 |
| Lenovo   | IdeaPad 5 15IIL05 81YK      | [5e3d9be29a](https://linux-hardware.org/?probe=5e3d9be29a) | Aug 01, 2020 |
| Lenovo   | IdeaPad 510-15IKB 80SV      | [d5b2c55949](https://linux-hardware.org/?probe=d5b2c55949) | Jul 27, 2020 |
| Lenovo   | ThinkPad T420 4236H45       | [61fd4ce395](https://linux-hardware.org/?probe=61fd4ce395) | Jul 20, 2020 |
| Lenovo   | IdeaPad 510-15IKB 80SV      | [0af3ac770f](https://linux-hardware.org/?probe=0af3ac770f) | Jul 06, 2020 |
| Notebook | N130BU                      | [e1b81e4880](https://linux-hardware.org/?probe=e1b81e4880) | Jul 05, 2020 |
| Lenovo   | IdeaPad 510-15IKB 80SV      | [051fa5784a](https://linux-hardware.org/?probe=051fa5784a) | Jul 02, 2020 |
| Gigabyte | AERO 15-X9                  | [7cb20a8170](https://linux-hardware.org/?probe=7cb20a8170) | Jul 01, 2020 |
| Gigabyte | AERO 15-X9                  | [efaa58fcc8](https://linux-hardware.org/?probe=efaa58fcc8) | Jun 14, 2020 |
| Gigabyte | AERO 15-X9                  | [b5fee1bf94](https://linux-hardware.org/?probe=b5fee1bf94) | Jun 12, 2020 |
| Acer     | Aspire E5-575G              | [cd633c729b](https://linux-hardware.org/?probe=cd633c729b) | Apr 29, 2020 |
| Dell     | Precision 3540              | [3e582eb1b9](https://linux-hardware.org/?probe=3e582eb1b9) | Mar 30, 2020 |
| Dell     | Precision 3540              | [6b57174c98](https://linux-hardware.org/?probe=6b57174c98) | Mar 21, 2020 |
| Dell     | Precision 3540              | [2a446cd098](https://linux-hardware.org/?probe=2a446cd098) | Feb 15, 2020 |
| Lenovo   | B590 20206                  | [a2066c32a9](https://linux-hardware.org/?probe=a2066c32a9) | Oct 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| Artix Rolling  | 47        | 58.75%  |
| Artix          | 31        | 38.75%  |
| Artix 20201207 | 1         | 1.25%   |
| Artix 20201128 | 1         | 1.25%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Artix | 75        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.9.14-artix1-1                 | 6         | 6.38%   |
| 5.7.6-artix1-1                  | 3         | 3.19%   |
| 5.7.12-artix1-1                 | 2         | 2.13%   |
| 5.17.1-artix1-1                 | 2         | 2.13%   |
| 5.16.8-artix1-2                 | 2         | 2.13%   |
| 5.16.10-artix1-1                | 2         | 2.13%   |
| 5.15.12-artix1-1                | 2         | 2.13%   |
| 5.14.16-artix1-1                | 2         | 2.13%   |
| 5.13.8-artix1-1                 | 2         | 2.13%   |
| 5.12.8-artix1-1                 | 2         | 2.13%   |
| 5.12.12-zen1-1-zen              | 2         | 2.13%   |
| 5.12.12-artix1-1                | 2         | 2.13%   |
| 5.11.6-artix1-1                 | 2         | 2.13%   |
| 5.10.6-artix1-1                 | 2         | 2.13%   |
| 5.10.4-artix2-1                 | 2         | 2.13%   |
| 5.10.16-artix1-1                | 2         | 2.13%   |
| 5.9.6-artix1-1                  | 1         | 1.06%   |
| 5.9.14-zen1-1-zen               | 1         | 1.06%   |
| 5.9.12-artix1-1                 | 1         | 1.06%   |
| 5.9.1-artix1-1                  | 1         | 1.06%   |
| 5.9.0-zen1-1-zen                | 1         | 1.06%   |
| 5.9.0-1-mainline-bootsplash     | 1         | 1.06%   |
| 5.8.8-artix1-1                  | 1         | 1.06%   |
| 5.8.4-artix1-1                  | 1         | 1.06%   |
| 5.8.14-zen1-1-zen               | 1         | 1.06%   |
| 5.8.14-artix1-1                 | 1         | 1.06%   |
| 5.8.12-artix1-1                 | 1         | 1.06%   |
| 5.8.0-rc7-5-mainline-bootsplash | 1         | 1.06%   |
| 5.7.8-artix1-1                  | 1         | 1.06%   |
| 5.7.2-artix1-1                  | 1         | 1.06%   |
| 5.6.7-x86_64                    | 1         | 1.06%   |
| 5.5.3-artix1-1                  | 1         | 1.06%   |
| 5.5.10-artix1-1                 | 1         | 1.06%   |
| 5.4.74-1-lts                    | 1         | 1.06%   |
| 5.17.3-zen1-1-zen               | 1         | 1.06%   |
| 5.17.2-artix3-1                 | 1         | 1.06%   |
| 5.17.1-zen1-1-zen               | 1         | 1.06%   |
| 5.16.8-zen1-1-zen               | 1         | 1.06%   |
| 5.16.7-artix1-1                 | 1         | 1.06%   |
| 5.16.3-artix1-1                 | 1         | 1.06%   |
| 5.16.1-artix1-1                 | 1         | 1.06%   |
| 5.16.0-arch1-g400s              | 1         | 1.06%   |
| 5.15.8-artix1-1                 | 1         | 1.06%   |
| 5.15.7-zen1-1-zen               | 1         | 1.06%   |
| 5.15.5-zen1-1-zen               | 1         | 1.06%   |
| 5.15.4-artix1-1                 | 1         | 1.06%   |
| 5.15.3-zen1-1-zen               | 1         | 1.06%   |
| 5.15.16-1-lts                   | 1         | 1.06%   |
| 5.15.12-zen1-1-zen              | 1         | 1.06%   |
| 5.14.7-zen1-1-zen               | 1         | 1.06%   |
| 5.14.14-artix1-1                | 1         | 1.06%   |
| 5.13.13-xanmod1-1               | 1         | 1.06%   |
| 5.13.12-artix1-1                | 1         | 1.06%   |
| 5.12.8-zen1-1-zen               | 1         | 1.06%   |
| 5.12.6-artix1-1                 | 1         | 1.06%   |
| 5.12.5-artix1-1                 | 1         | 1.06%   |
| 5.12.4-artix1-1                 | 1         | 1.06%   |
| 5.12.14-zen1-1-zen              | 1         | 1.06%   |
| 5.12.14-artix1-1                | 1         | 1.06%   |
| 5.12.0-rc8                      | 1         | 1.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.14  | 7         | 7.45%   |
| 5.12.12 | 4         | 4.26%   |
| 5.7.6   | 3         | 3.19%   |
| 5.17.1  | 3         | 3.19%   |
| 5.16.8  | 3         | 3.19%   |
| 5.15.12 | 3         | 3.19%   |
| 5.12.8  | 3         | 3.19%   |
| 5.9.0   | 2         | 2.13%   |
| 5.8.14  | 2         | 2.13%   |
| 5.7.12  | 2         | 2.13%   |
| 5.16.10 | 2         | 2.13%   |
| 5.14.16 | 2         | 2.13%   |
| 5.13.8  | 2         | 2.13%   |
| 5.12.14 | 2         | 2.13%   |
| 5.11.6  | 2         | 2.13%   |
| 5.10.6  | 2         | 2.13%   |
| 5.10.4  | 2         | 2.13%   |
| 5.10.16 | 2         | 2.13%   |
| 5.9.6   | 1         | 1.06%   |
| 5.9.12  | 1         | 1.06%   |
| 5.9.1   | 1         | 1.06%   |
| 5.8.8   | 1         | 1.06%   |
| 5.8.4   | 1         | 1.06%   |
| 5.8.12  | 1         | 1.06%   |
| 5.8.0   | 1         | 1.06%   |
| 5.7.8   | 1         | 1.06%   |
| 5.7.2   | 1         | 1.06%   |
| 5.6.7   | 1         | 1.06%   |
| 5.5.3   | 1         | 1.06%   |
| 5.5.10  | 1         | 1.06%   |
| 5.4.74  | 1         | 1.06%   |
| 5.17.3  | 1         | 1.06%   |
| 5.17.2  | 1         | 1.06%   |
| 5.16.7  | 1         | 1.06%   |
| 5.16.3  | 1         | 1.06%   |
| 5.16.1  | 1         | 1.06%   |
| 5.16.0  | 1         | 1.06%   |
| 5.15.8  | 1         | 1.06%   |
| 5.15.7  | 1         | 1.06%   |
| 5.15.5  | 1         | 1.06%   |
| 5.15.4  | 1         | 1.06%   |
| 5.15.3  | 1         | 1.06%   |
| 5.15.16 | 1         | 1.06%   |
| 5.14.7  | 1         | 1.06%   |
| 5.14.14 | 1         | 1.06%   |
| 5.13.13 | 1         | 1.06%   |
| 5.13.12 | 1         | 1.06%   |
| 5.12.6  | 1         | 1.06%   |
| 5.12.5  | 1         | 1.06%   |
| 5.12.4  | 1         | 1.06%   |
| 5.12.0  | 1         | 1.06%   |
| 5.11.8  | 1         | 1.06%   |
| 5.11.7  | 1         | 1.06%   |
| 5.11.2  | 1         | 1.06%   |
| 5.11.16 | 1         | 1.06%   |
| 5.11.12 | 1         | 1.06%   |
| 5.11.1  | 1         | 1.06%   |
| 5.10.82 | 1         | 1.06%   |
| 5.10.8  | 1         | 1.06%   |
| 5.10.64 | 1         | 1.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.12    | 12        | 13.79%  |
| 5.9     | 11        | 12.64%  |
| 5.10    | 11        | 12.64%  |
| 5.15    | 9         | 10.34%  |
| 5.16    | 8         | 9.2%    |
| 5.11    | 8         | 9.2%    |
| 5.7     | 6         | 6.9%    |
| 5.8     | 5         | 5.75%   |
| 5.17    | 5         | 5.75%   |
| 5.14    | 4         | 4.6%    |
| 5.13    | 4         | 4.6%    |
| 5.6     | 1         | 1.15%   |
| 5.5     | 1         | 1.15%   |
| 5.4     | 1         | 1.15%   |
| 4.19    | 1         | 1.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 75        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| KDE5           | 18        | 22.5%   |
| Unknown        | 13        | 16.25%  |
| XFCE           | 12        | 15%     |
| GNOME          | 12        | 15%     |
| X-Cinnamon     | 5         | 6.25%   |
| MATE           | 4         | 5%      |
| KDE            | 4         | 5%      |
| LXQt           | 3         | 3.75%   |
| Cinnamon       | 3         | 3.75%   |
| xmonad         | 1         | 1.25%   |
| nxde           | 1         | 1.25%   |
| LXDE           | 1         | 1.25%   |
| i3             | 1         | 1.25%   |
| bspwm          | 1         | 1.25%   |
| awesomeminimal | 1         | 1.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 54        | 68.35%  |
| Tty     | 12        | 15.19%  |
| Wayland | 9         | 11.39%  |
| Unknown | 4         | 5.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 27        | 35.53%  |
| LightDM | 24        | 31.58%  |
| SDDM    | 21        | 27.63%  |
| SLiM    | 1         | 1.32%   |
| Ly      | 1         | 1.32%   |
| LXDM    | 1         | 1.32%   |
| GDM     | 1         | 1.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 39        | 49.37%  |
| Unknown | 10        | 12.66%  |
| ru_RU   | 6         | 7.59%   |
| en_GB   | 5         | 6.33%   |
| fr_FR   | 3         | 3.8%    |
| es_ES   | 2         | 2.53%   |
| en_CA   | 2         | 2.53%   |
| C       | 2         | 2.53%   |
| uk_UA   | 1         | 1.27%   |
| pt_PT   | 1         | 1.27%   |
| pt_BR   | 1         | 1.27%   |
| pl_PL   | 1         | 1.27%   |
| it_IT   | 1         | 1.27%   |
| en_IN   | 1         | 1.27%   |
| en_AU   | 1         | 1.27%   |
| el_GR   | 1         | 1.27%   |
| de_DE   | 1         | 1.27%   |
| cs_CZ   | 1         | 1.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 56        | 73.68%  |
| BIOS | 20        | 26.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 55        | 73.33%  |
| Btrfs   | 16        | 21.33%  |
| Xfs     | 2         | 2.67%   |
| Overlay | 1         | 1.33%   |
| F2fs    | 1         | 1.33%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 55        | 72.37%  |
| Unknown | 12        | 15.79%  |
| MBR     | 9         | 11.84%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 62        | 81.58%  |
| Yes       | 14        | 18.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 57        | 76%     |
| Yes       | 18        | 24%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 23        | 30.67%  |
| Hewlett-Packard     | 13        | 17.33%  |
| Dell                | 9         | 12%     |
| Acer                | 8         | 10.67%  |
| ASUSTek Computer    | 7         | 9.33%   |
| Apple               | 3         | 4%      |
| Timi                | 2         | 2.67%   |
| Notebook            | 2         | 2.67%   |
| MSI                 | 2         | 2.67%   |
| GPD                 | 2         | 2.67%   |
| Gigabyte Technology | 2         | 2.67%   |
| UNOWHY              | 1         | 1.33%   |
| Quanta              | 1         | 1.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Timi RedmiBook 14 II                    | 2         | 2.67%   |
| Lenovo IdeaPad 5 15IIL05 81YK           | 2         | 2.67%   |
| HP 15                                   | 2         | 2.67%   |
| GPD P2 MAX                              | 2         | 2.67%   |
| Dell Precision 7550                     | 2         | 2.67%   |
| Apple MacBookAir7,2                     | 2         | 2.67%   |
| UNOWHY Y13G010S4EI                      | 1         | 1.33%   |
| Quanta SWH                              | 1         | 1.33%   |
| Notebook N141CU                         | 1         | 1.33%   |
| Notebook N130BU                         | 1         | 1.33%   |
| MSI Modern 15 A11M                      | 1         | 1.33%   |
| MSI GP72 7RDX                           | 1         | 1.33%   |
| Lenovo ThinkPad W500 4063CJ5            | 1         | 1.33%   |
| Lenovo ThinkPad T480s 20L8S3D400        | 1         | 1.33%   |
| Lenovo ThinkPad T430 2350BC6            | 1         | 1.33%   |
| Lenovo ThinkPad T430 2347H76            | 1         | 1.33%   |
| Lenovo ThinkPad T420 4236H45            | 1         | 1.33%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00    | 1         | 1.33%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800    | 1         | 1.33%   |
| Lenovo ThinkPad P1 Gen 3 20TH001EMH     | 1         | 1.33%   |
| Lenovo ThinkPad E14 Gen 2 20T6000MCK    | 1         | 1.33%   |
| Lenovo ThinkPad 11e 5th Gen 20LNS0P500  | 1         | 1.33%   |
| Lenovo ThinkBook 15 G2 ITL 20VE         | 1         | 1.33%   |
| Lenovo Legion 5 15ARH05H 82B1           | 1         | 1.33%   |
| Lenovo LaVie Z 20FF0012US               | 1         | 1.33%   |
| Lenovo IdeaPad Y500 20193               | 1         | 1.33%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL   | 1         | 1.33%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG    | 1         | 1.33%   |
| Lenovo IdeaPad 510-15IKB 80SV           | 1         | 1.33%   |
| Lenovo IdeaPad 330-15IKB 81DE           | 1         | 1.33%   |
| Lenovo G400s 20244                      | 1         | 1.33%   |
| Lenovo B590 20206                       | 1         | 1.33%   |
| Lenovo B570e HuronRiver Platform        | 1         | 1.33%   |
| HP ProBook 450 G6                       | 1         | 1.33%   |
| HP OMEN Laptop 15-en0xxx                | 1         | 1.33%   |
| HP Laptop 17z-ca300                     | 1         | 1.33%   |
| HP Laptop 15-ef1xxx                     | 1         | 1.33%   |
| HP Laptop 14s-dq2xxx                    | 1         | 1.33%   |
| HP Laptop 14s-cf3xxx                    | 1         | 1.33%   |
| HP 255 G7 Notebook PC                   | 1         | 1.33%   |
| HP 250 G7 Notebook PC                   | 1         | 1.33%   |
| HP 250 G4 Notebook PC                   | 1         | 1.33%   |
| HP 250 G3                               | 1         | 1.33%   |
| HP 246                                  | 1         | 1.33%   |
| Gigabyte B450M DS3H                     | 1         | 1.33%   |
| Gigabyte AERO 15-X9                     | 1         | 1.33%   |
| Dell Precision M6600                    | 1         | 1.33%   |
| Dell Precision 5520                     | 1         | 1.33%   |
| Dell Precision 3540                     | 1         | 1.33%   |
| Dell Latitude E6530                     | 1         | 1.33%   |
| Dell Latitude E6440                     | 1         | 1.33%   |
| Dell Inspiron 5570                      | 1         | 1.33%   |
| Dell Inspiron 3442                      | 1         | 1.33%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA | 1         | 1.33%   |
| ASUS K53SC                              | 1         | 1.33%   |
| ASUS K50IE                              | 1         | 1.33%   |
| ASUS GX501VIK                           | 1         | 1.33%   |
| ASUS GL702ZC                            | 1         | 1.33%   |
| ASUS E402NA                             | 1         | 1.33%   |
| ASUS 1225C                              | 1         | 1.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 10        | 13.33%  |
| Lenovo IdeaPad     | 7         | 9.33%   |
| Acer Aspire        | 6         | 8%      |
| Dell Precision     | 5         | 6.67%   |
| HP Laptop          | 4         | 5.33%   |
| HP 250             | 3         | 4%      |
| Timi RedmiBook     | 2         | 2.67%   |
| HP 15              | 2         | 2.67%   |
| GPD P2             | 2         | 2.67%   |
| Dell Latitude      | 2         | 2.67%   |
| Dell Inspiron      | 2         | 2.67%   |
| Apple MacBookAir7  | 2         | 2.67%   |
| UNOWHY Y13G010S4EI | 1         | 1.33%   |
| Quanta SWH         | 1         | 1.33%   |
| Notebook N141CU    | 1         | 1.33%   |
| Notebook N130BU    | 1         | 1.33%   |
| MSI Modern         | 1         | 1.33%   |
| MSI GP72           | 1         | 1.33%   |
| Lenovo ThinkBook   | 1         | 1.33%   |
| Lenovo Legion      | 1         | 1.33%   |
| Lenovo LaVie       | 1         | 1.33%   |
| Lenovo G400s       | 1         | 1.33%   |
| Lenovo B590        | 1         | 1.33%   |
| Lenovo B570e       | 1         | 1.33%   |
| HP ProBook         | 1         | 1.33%   |
| HP OMEN            | 1         | 1.33%   |
| HP 255             | 1         | 1.33%   |
| HP 246             | 1         | 1.33%   |
| Gigabyte B450M     | 1         | 1.33%   |
| Gigabyte AERO      | 1         | 1.33%   |
| ASUS VivoBook      | 1         | 1.33%   |
| ASUS K53SC         | 1         | 1.33%   |
| ASUS K50IE         | 1         | 1.33%   |
| ASUS GX501VIK      | 1         | 1.33%   |
| ASUS GL702ZC       | 1         | 1.33%   |
| ASUS E402NA        | 1         | 1.33%   |
| ASUS 1225C         | 1         | 1.33%   |
| Apple MacBookPro11 | 1         | 1.33%   |
| Acer Swift         | 1         | 1.33%   |
| Acer Nitro         | 1         | 1.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 20        | 26.67%  |
| 2018 | 8         | 10.67%  |
| 2017 | 8         | 10.67%  |
| 2019 | 7         | 9.33%   |
| 2016 | 6         | 8%      |
| 2012 | 6         | 8%      |
| 2011 | 6         | 8%      |
| 2014 | 5         | 6.67%   |
| 2013 | 4         | 5.33%   |
| 2015 | 2         | 2.67%   |
| 2021 | 1         | 1.33%   |
| 2010 | 1         | 1.33%   |
| 2009 | 1         | 1.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 75        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 74        | 98.67%  |
| Enabled  | 1         | 1.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 75        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 21        | 27.63%  |
| 4.01-8.0    | 20        | 26.32%  |
| 16.01-24.0  | 13        | 17.11%  |
| 3.01-4.0    | 11        | 14.47%  |
| 32.01-64.0  | 4         | 5.26%   |
| 64.01-256.0 | 3         | 3.95%   |
| 1.01-2.0    | 3         | 3.95%   |
| 24.01-32.0  | 1         | 1.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 22        | 25.58%  |
| 2.01-3.0   | 18        | 20.93%  |
| 4.01-8.0   | 17        | 19.77%  |
| 3.01-4.0   | 14        | 16.28%  |
| 0.51-1.0   | 9         | 10.47%  |
| 8.01-16.0  | 4         | 4.65%   |
| 16.01-24.0 | 1         | 1.16%   |
| 0.01-0.5   | 1         | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 56        | 73.68%  |
| 2      | 19        | 25%     |
| 3      | 1         | 1.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 55        | 73.33%  |
| Yes       | 20        | 26.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 60        | 80%     |
| No        | 15        | 20%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 98.67%  |
| No        | 1         | 1.33%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 79.22%  |
| No        | 16        | 20.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 16        | 21.33%  |
| Russia      | 7         | 9.33%   |
| UK          | 4         | 5.33%   |
| Germany     | 4         | 5.33%   |
| Canada      | 4         | 5.33%   |
| Ukraine     | 3         | 4%      |
| Turkey      | 3         | 4%      |
| Netherlands | 3         | 4%      |
| India       | 3         | 4%      |
| France      | 3         | 4%      |
| Brazil      | 3         | 4%      |
| Switzerland | 2         | 2.67%   |
| Spain       | 2         | 2.67%   |
| Poland      | 2         | 2.67%   |
| Indonesia   | 2         | 2.67%   |
| Uzbekistan  | 1         | 1.33%   |
| Sweden      | 1         | 1.33%   |
| Lithuania   | 1         | 1.33%   |
| Italy       | 1         | 1.33%   |
| Greece      | 1         | 1.33%   |
| Czechia     | 1         | 1.33%   |
| China       | 1         | 1.33%   |
| Chile       | 1         | 1.33%   |
| Bulgaria    | 1         | 1.33%   |
| Bangladesh  | 1         | 1.33%   |
| Azerbaijan  | 1         | 1.33%   |
| Australia   | 1         | 1.33%   |
| Argentina   | 1         | 1.33%   |
| Algeria     | 1         | 1.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 3         | 3.75%   |
| St Petersburg     | 2         | 2.5%    |
| San Ramon         | 2         | 2.5%    |
| Neuchatel         | 2         | 2.5%    |
| Los Angeles       | 2         | 2.5%    |
| Kyiv              | 2         | 2.5%    |
| Jakarta           | 2         | 2.5%    |
| Frankfurt am Main | 2         | 2.5%    |
| Amsterdam         | 2         | 2.5%    |
| Г‡orum         | 1         | 1.25%   |
| Zaporizhzhya      | 1         | 1.25%   |
| York              | 1         | 1.25%   |
| Yekaterinburg     | 1         | 1.25%   |
| Xirdalan          | 1         | 1.25%   |
| Wigan             | 1         | 1.25%   |
| Vilnius           | 1         | 1.25%   |
| Vancouver         | 1         | 1.25%   |
| Toronto           | 1         | 1.25%   |
| Thassos           | 1         | 1.25%   |
| Syeverodonets'k   | 1         | 1.25%   |
| Surgut            | 1         | 1.25%   |
| Stuttgart         | 1         | 1.25%   |
| Stockholm         | 1         | 1.25%   |
| Srednyaya Akhtuba | 1         | 1.25%   |
| Sofia             | 1         | 1.25%   |
| Seville           | 1         | 1.25%   |
| Seattle           | 1         | 1.25%   |
| Santiago          | 1         | 1.25%   |
| Santa Fe          | 1         | 1.25%   |
| Sainte-Severe     | 1         | 1.25%   |
| Roseburg          | 1         | 1.25%   |
| Quincy            | 1         | 1.25%   |
| Puducherry        | 1         | 1.25%   |
| Prague            | 1         | 1.25%   |
| Ordu              | 1         | 1.25%   |
| Omsk              | 1         | 1.25%   |
| Nottingham        | 1         | 1.25%   |
| Nantes            | 1         | 1.25%   |
| Mount Pearl       | 1         | 1.25%   |
| Moscow            | 1         | 1.25%   |
| Mississauga       | 1         | 1.25%   |
| Milton            | 1         | 1.25%   |
| Mestre            | 1         | 1.25%   |
| Mesquite          | 1         | 1.25%   |
| Malda             | 1         | 1.25%   |
| Malappuram        | 1         | 1.25%   |
| Lexington         | 1         | 1.25%   |
| Leander           | 1         | 1.25%   |
| Lavras            | 1         | 1.25%   |
| Laurel            | 1         | 1.25%   |
| Klobuck           | 1         | 1.25%   |
| KÅ‚odzko       | 1         | 1.25%   |
| Hinsdale          | 1         | 1.25%   |
| Hampton           | 1         | 1.25%   |
| Guacui            | 1         | 1.25%   |
| Gilbert           | 1         | 1.25%   |
| Edgware           | 1         | 1.25%   |
| Dronten           | 1         | 1.25%   |
| Dhaka             | 1         | 1.25%   |
| Costa Mesa        | 1         | 1.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 26     | 22.34%  |
| Seagate             | 12        | 12     | 12.77%  |
| WDC                 | 8         | 11     | 8.51%   |
| Toshiba             | 8         | 8      | 8.51%   |
| SK Hynix            | 5         | 12     | 5.32%   |
| Intel               | 5         | 7      | 5.32%   |
| HGST                | 5         | 5      | 5.32%   |
| Sandisk             | 4         | 4      | 4.26%   |
| Kingston            | 4         | 5      | 4.26%   |
| Hitachi             | 3         | 4      | 3.19%   |
| China               | 3         | 3      | 3.19%   |
| Apple               | 3         | 4      | 3.19%   |
| Unknown             | 2         | 2      | 2.13%   |
| Phison Electronics  | 2         | 3      | 2.13%   |
| Crucial             | 2         | 2      | 2.13%   |
| Timetec             | 1         | 2      | 1.06%   |
| SPCC                | 1         | 1      | 1.06%   |
| Solid State Storage | 1         | 1      | 1.06%   |
| PNY                 | 1         | 1      | 1.06%   |
| Linux               | 1         | 1      | 1.06%   |
| LDLC                | 1         | 6      | 1.06%   |
| Intenso             | 1         | 1      | 1.06%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB            | 3         | 3.03%   |
| Sandisk NVMe SSD Drive 512GB              | 3         | 3.03%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 2         | 2.02%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 2.02%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 2.02%   |
| Samsung NVMe SSD Drive 1TB                | 2         | 2.02%   |
| Samsung MZNLH512HALU-00000 512GB SSD      | 2         | 2.02%   |
| Phison PCIe SSD 8TB                       | 2         | 2.02%   |
| HGST HTS545050A7E680 500GB                | 2         | 2.02%   |
| China SATA SSD 960GB                      | 2         | 2.02%   |
| Apple SSD SM0256G 256GB                   | 2         | 2.02%   |
| WDC WDS200T2B0B-00YS70 2TB SSD            | 1         | 1.01%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 1.01%   |
| WDC WD5000BPVT-22HXZT3 500GB              | 1         | 1.01%   |
| WDC WD3200LPVT-00FMCT0 320GB              | 1         | 1.01%   |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 1.01%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 1         | 1.01%   |
| Unknown SD/MMC/MS PRO 16GB                | 1         | 1.01%   |
| Unknown DA4064  64GB                      | 1         | 1.01%   |
| Toshiba THNSNH128GMCT 128GB SSD           | 1         | 1.01%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1.01%   |
| Toshiba MK5065GSX 500GB                   | 1         | 1.01%   |
| Toshiba KBG30ZMT256G 256GB                | 1         | 1.01%   |
| Timetec 35TTM8SSATA-512GB                 | 1         | 1.01%   |
| SPCC Solid State Disk 256GB               | 1         | 1.01%   |
| Solid State Storage SSSTC CL1-4D256 256GB | 1         | 1.01%   |
| SK Hynix SKHynix_HFS512GD9TNI-L2B0B 512GB | 1         | 1.01%   |
| SK Hynix SKHynix_HFS512GD9TNI-L2A0B 512GB | 1         | 1.01%   |
| SK Hynix SC311 SATA 256GB SSD             | 1         | 1.01%   |
| SK Hynix NVMe SSD Drive 1TB               | 1         | 1.01%   |
| SK Hynix NVMe SSD Drive 1024GB            | 1         | 1.01%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB   | 1         | 1.01%   |
| Seagate ST9500325AS 500GB                 | 1         | 1.01%   |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 1.01%   |
| Seagate ST500LT012-9WS142 500GB           | 1         | 1.01%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1.01%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 1.01%   |
| Seagate ST2000LM015-2E8174 2TB            | 1         | 1.01%   |
| Seagate ST2000LM003 HN-M201RAD 2TB        | 1         | 1.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1.01%   |
| Seagate BUP Portable 5TB                  | 1         | 1.01%   |
| SanDisk SSD U100 16GB                     | 1         | 1.01%   |
| Samsung SSD 970 EVO Plus 1TB              | 1         | 1.01%   |
| Samsung SSD 970 EVO 1TB                   | 1         | 1.01%   |
| Samsung SSD 870 EVO 250GB                 | 1         | 1.01%   |
| Samsung SSD 850 EVO 250GB                 | 1         | 1.01%   |
| Samsung SM961 NVMe 512GB                  | 1         | 1.01%   |
| Samsung NVMe SSD Drive 2TB                | 1         | 1.01%   |
| Samsung NVMe SSD Drive 256GB              | 1         | 1.01%   |
| Samsung NVMe SSD Drive 1024GB             | 1         | 1.01%   |
| Samsung MZYTY256HDHP-000L2 256GB SSD      | 1         | 1.01%   |
| Samsung MZVPW256HEGL-000L7 256GB          | 1         | 1.01%   |
| Samsung MZVLQ512HALU-00000 512GB          | 1         | 1.01%   |
| Samsung MZVLB512HBJQ-000H1 512GB          | 1         | 1.01%   |
| Samsung MZVLB256HBHQ-00000 256GB          | 1         | 1.01%   |
| Samsung MZVLB1T0HBLR-000L7 1TB            | 1         | 1.01%   |
| Samsung MZVKW512HMJP-00000 512GB          | 1         | 1.01%   |
| Samsung MZNTE256HMHP-000L1 256GB SSD      | 1         | 1.01%   |
| Samsung MZALQ512HALU-000L2 512GB          | 1         | 1.01%   |
| Samsung MZALQ512HALU-000L1 512GB          | 1         | 1.01%   |

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
| Samsung Electronics | 6         | 7      | 23.08%  |
| China               | 3         | 3      | 11.54%  |
| Apple               | 3         | 4      | 11.54%  |
| Kingston            | 2         | 2      | 7.69%   |
| Crucial             | 2         | 2      | 7.69%   |
| WDC                 | 1         | 2      | 3.85%   |
| Toshiba             | 1         | 1      | 3.85%   |
| SPCC                | 1         | 1      | 3.85%   |
| SK Hynix            | 1         | 1      | 3.85%   |
| SanDisk             | 1         | 1      | 3.85%   |
| PNY                 | 1         | 1      | 3.85%   |
| Linux               | 1         | 1      | 3.85%   |
| LDLC                | 1         | 6      | 3.85%   |
| Intenso             | 1         | 1      | 3.85%   |
| Intel               | 1         | 1      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 33        | 37     | 37.5%   |
| NVMe    | 29        | 47     | 32.95%  |
| SSD     | 24        | 34     | 27.27%  |
| MMC     | 1         | 1      | 1.14%   |
| Unknown | 1         | 2      | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 53        | 71     | 62.35%  |
| NVMe | 29        | 47     | 34.12%  |
| SAS  | 2         | 2      | 2.35%   |
| MMC  | 1         | 1      | 1.18%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 32        | 42     | 57.14%  |
| 0.51-1.0   | 20        | 24     | 35.71%  |
| 1.01-2.0   | 3         | 4      | 5.36%   |
| 4.01-10.0  | 1         | 1      | 1.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 21        | 26.92%  |
| 251-500        | 20        | 25.64%  |
| 501-1000       | 11        | 14.1%   |
| 1001-2000      | 10        | 12.82%  |
| 51-100         | 5         | 6.41%   |
| Unknown        | 5         | 6.41%   |
| More than 3000 | 3         | 3.85%   |
| 1-20           | 2         | 2.56%   |
| 2001-3000      | 1         | 1.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 19        | 22.62%  |
| 101-250   | 15        | 17.86%  |
| 51-100    | 13        | 15.48%  |
| 21-50     | 11        | 13.1%   |
| 501-1000  | 10        | 11.9%   |
| 251-500   | 7         | 8.33%   |
| Unknown   | 5         | 5.95%   |
| 1001-2000 | 3         | 3.57%   |
| 2001-3000 | 1         | 1.19%   |

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
| Works    | 42        | 55     | 51.85%  |
| Detected | 27        | 52     | 33.33%  |
| Malfunc  | 12        | 14     | 14.81%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 49        | 52.69%  |
| Samsung Electronics            | 17        | 18.28%  |
| AMD                            | 11        | 11.83%  |
| SK Hynix                       | 4         | 4.3%    |
| Sandisk                        | 3         | 3.23%   |
| Phison Electronics             | 2         | 2.15%   |
| Kingston Technology Company    | 2         | 2.15%   |
| Union Memory (Shenzhen)        | 1         | 1.08%   |
| Toshiba America Info Systems   | 1         | 1.08%   |
| Solid State Storage Technology | 1         | 1.08%   |
| Nvidia                         | 1         | 1.08%   |
| Marvell Technology Group       | 1         | 1.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 10        | 10.31%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 8.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 7.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 6.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 5.15%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 4.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 4.12%   |
| SK Hynix Non-Volatile memory controller                                        | 3         | 3.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 3.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 3.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 3.09%   |
| Sandisk Non-Volatile memory controller                                         | 2         | 2.06%   |
| Samsung Electronics SATA controller                                            | 2         | 2.06%   |
| Phison E12 NVMe Controller                                                     | 2         | 2.06%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 2.06%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 2.06%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 2.06%   |
| Intel SSD 660P Series                                                          | 2         | 2.06%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 2.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 2.06%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 2.06%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 1.03%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 1.03%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 1.03%   |
| SK Hynix BC511                                                                 | 1         | 1.03%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 1         | 1.03%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 1.03%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 1.03%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 1.03%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 1.03%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 1.03%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 1.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 1.03%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 1.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 1.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 1.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 1.03%   |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 1.03%   |
| AMD 300 Series Chipset SATA Controller                                         | 1         | 1.03%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 56        | 60.22%  |
| NVMe | 30        | 32.26%  |
| RAID | 7         | 7.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 62        | 82.67%  |
| AMD    | 13        | 17.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 5.26%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 2.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 2.63%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 2.63%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 2.63%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 2.63%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 2.63%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 2.63%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 2         | 2.63%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 2.63%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 2.63%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 2.63%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 1.32%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 1.32%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 1.32%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 1.32%   |
| Intel Pentium CPU A1018 @ 2.10GHz             | 1         | 1.32%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 1.32%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 1.32%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 1         | 1.32%   |
| Intel Core i7-9750HF CPU @ 2.60GHz            | 1         | 1.32%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 1.32%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 1.32%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 1.32%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 1.32%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 1         | 1.32%   |
| Intel Core i7-2820QM CPU @ 2.30GHz            | 1         | 1.32%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 1.32%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 1.32%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 1.32%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 1         | 1.32%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.32%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1         | 1.32%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 1         | 1.32%   |
| Intel Core i5-4258U CPU @ 2.40GHz             | 1         | 1.32%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 1         | 1.32%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 1.32%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 1         | 1.32%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1         | 1.32%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 1.32%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 1         | 1.32%   |
| Intel Core i3-6100U CPU @ 2.30GHz             | 1         | 1.32%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 1         | 1.32%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 1.32%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 1.32%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.32%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 1         | 1.32%   |
| Intel Core 2 Duo CPU T9550 @ 2.66GHz          | 1         | 1.32%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 1         | 1.32%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 1         | 1.32%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 1         | 1.32%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 1         | 1.32%   |
| Intel Celeron CPU B800 @ 1.50GHz              | 1         | 1.32%   |
| Intel Atom CPU N2800 @ 1.86GHz                | 1         | 1.32%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 1         | 1.32%   |
| AMD Ryzen 7 1700 Eight-Core Processor         | 1         | 1.32%   |
| AMD Ryzen 5 PRO 4650U with Radeon Graphics    | 1         | 1.32%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 1         | 1.32%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 1         | 1.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 19        | 25.33%  |
| Intel Core i7           | 14        | 18.67%  |
| Intel Core i3           | 9         | 12%     |
| AMD Ryzen 7             | 7         | 9.33%   |
| Other                   | 4         | 5.33%   |
| Intel Celeron           | 4         | 5.33%   |
| Intel Pentium           | 3         | 4%      |
| Intel Core m3           | 2         | 2.67%   |
| Intel Core i9           | 2         | 2.67%   |
| AMD Ryzen 3             | 2         | 2.67%   |
| Intel Xeon              | 1         | 1.33%   |
| Intel Pentium Silver    | 1         | 1.33%   |
| Intel Pentium Dual-Core | 1         | 1.33%   |
| Intel Core 2 Duo        | 1         | 1.33%   |
| Intel Atom              | 1         | 1.33%   |
| AMD Ryzen 9             | 1         | 1.33%   |
| AMD Ryzen 5 PRO         | 1         | 1.33%   |
| AMD Ryzen 5             | 1         | 1.33%   |
| AMD A6                  | 1         | 1.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 38        | 50.67%  |
| 4      | 22        | 29.33%  |
| 8      | 9         | 12%     |
| 6      | 5         | 6.67%   |
| 12     | 1         | 1.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 75        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 58        | 77.33%  |
| 1      | 17        | 22.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 75        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 18.18%  |
| 0x306a9    | 6         | 7.79%   |
| 0x806e9    | 5         | 6.49%   |
| 0x206a7    | 5         | 6.49%   |
| 0x806c1    | 4         | 5.19%   |
| 0x306d4    | 4         | 5.19%   |
| 0xa0652    | 3         | 3.9%    |
| 0x906e9    | 3         | 3.9%    |
| 0x806ec    | 3         | 3.9%    |
| 0x706e5    | 3         | 3.9%    |
| 0x40651    | 3         | 3.9%    |
| 0x08600106 | 3         | 3.9%    |
| 0x806ea    | 2         | 2.6%    |
| 0x706a1    | 2         | 2.6%    |
| 0x1067a    | 2         | 2.6%    |
| 0x08600103 | 2         | 2.6%    |
| 0x906ed    | 1         | 1.3%    |
| 0x906ea    | 1         | 1.3%    |
| 0x506c9    | 1         | 1.3%    |
| 0x406e3    | 1         | 1.3%    |
| 0x306c3    | 1         | 1.3%    |
| 0x30678    | 1         | 1.3%    |
| 0x20655    | 1         | 1.3%    |
| 0x08701013 | 1         | 1.3%    |
| 0x08600104 | 1         | 1.3%    |
| 0x0810100b | 1         | 1.3%    |
| 0x08101007 | 1         | 1.3%    |
| 0x08001137 | 1         | 1.3%    |
| 0x0700010b | 1         | 1.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 20        | 26.67%  |
| Zen 2         | 8         | 10.67%  |
| IvyBridge     | 7         | 9.33%   |
| SandyBridge   | 5         | 6.67%   |
| Haswell       | 5         | 6.67%   |
| Broadwell     | 5         | 6.67%   |
| TigerLake     | 4         | 5.33%   |
| CometLake     | 4         | 5.33%   |
| Zen           | 3         | 4%      |
| IceLake       | 3         | 4%      |
| Penryn        | 2         | 2.67%   |
| Goldmont plus | 2         | 2.67%   |
| Zen+          | 1         | 1.33%   |
| Westmere      | 1         | 1.33%   |
| Skylake       | 1         | 1.33%   |
| Silvermont    | 1         | 1.33%   |
| Jaguar        | 1         | 1.33%   |
| Goldmont      | 1         | 1.33%   |
| Bonnell       | 1         | 1.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 56        | 60.22%  |
| Nvidia | 21        | 22.58%  |
| AMD    | 16        | 17.2%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                         | 6         | 6.45%   |
| AMD Renoir                                                                    | 6         | 6.45%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 5         | 5.38%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 4         | 4.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                              | 4         | 4.3%    |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 4.3%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 4.3%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 3         | 3.23%   |
| Intel HD Graphics 5500                                                        | 3         | 3.23%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 2.15%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                              | 2         | 2.15%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 2         | 2.15%   |
| Nvidia GM108M [GeForce 840M]                                                  | 2         | 2.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 2         | 2.15%   |
| Intel UHD Graphics 620                                                        | 2         | 2.15%   |
| Intel UHD Graphics 615                                                        | 2         | 2.15%   |
| Intel HD Graphics 630                                                         | 2         | 2.15%   |
| Intel HD Graphics 6000                                                        | 2         | 2.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 2.15%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 2.15%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 1.08%   |
| Nvidia TU117M                                                                 | 1         | 1.08%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                       | 1         | 1.08%   |
| Nvidia GT218M [GeForce 310M]                                                  | 1         | 1.08%   |
| Nvidia GP108M [GeForce MX330]                                                 | 1         | 1.08%   |
| Nvidia GP108M [GeForce MX150]                                                 | 1         | 1.08%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                      | 1         | 1.08%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                         | 1         | 1.08%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 1         | 1.08%   |
| Nvidia GK107M [GeForce GT 650M]                                               | 1         | 1.08%   |
| Nvidia GF119M [GeForce GT 520MX]                                              | 1         | 1.08%   |
| Nvidia GF108M [GeForce GT 520M]                                               | 1         | 1.08%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 1         | 1.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 1.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 1.08%   |
| Intel HD Graphics P630                                                        | 1         | 1.08%   |
| Intel HD Graphics 500                                                         | 1         | 1.08%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 1.08%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 1         | 1.08%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 1.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 1         | 1.08%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 1.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 1.08%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                             | 1         | 1.08%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 1.08%   |
| AMD Saturn XT [FirePro M6100]                                                 | 1         | 1.08%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                       | 1         | 1.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 1         | 1.08%   |
| AMD Lexa XT [Radeon PRO WX 3100]                                              | 1         | 1.08%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                       | 1         | 1.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 1         | 1.08%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 39        | 51.32%  |
| Intel + Nvidia | 14        | 18.42%  |
| 1 x AMD        | 13        | 17.11%  |
| 1 x Nvidia     | 6         | 7.89%   |
| Intel + AMD    | 3         | 3.95%   |
| AMD + Nvidia   | 1         | 1.32%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 61        | 81.33%  |
| Proprietary | 14        | 18.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 65.79%  |
| 0.01-0.5   | 8         | 10.53%  |
| 1.01-2.0   | 7         | 9.21%   |
| 0.51-1.0   | 4         | 5.26%   |
| 3.01-4.0   | 3         | 3.95%   |
| 7.01-8.0   | 2         | 2.63%   |
| 5.01-6.0   | 1         | 1.32%   |
| 2.01-3.0   | 1         | 1.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 16        | 18.39%  |
| AU Optronics            | 15        | 17.24%  |
| LG Display              | 14        | 16.09%  |
| Chimei Innolux          | 10        | 11.49%  |
| Samsung Electronics     | 6         | 6.9%    |
| Dell                    | 3         | 3.45%   |
| Apple                   | 3         | 3.45%   |
| Sharp                   | 2         | 2.3%    |
| InfoVision              | 2         | 2.3%    |
| Hewlett-Packard         | 2         | 2.3%    |
| Goldstar                | 2         | 2.3%    |
| Chi Mei Optoelectronics | 2         | 2.3%    |
| BenQ                    | 2         | 2.3%    |
| ASUSTek Computer        | 2         | 2.3%    |
| Philips                 | 1         | 1.15%   |
| PANDA                   | 1         | 1.15%   |
| MSI                     | 1         | 1.15%   |
| LGD                     | 1         | 1.15%   |
| Lenovo                  | 1         | 1.15%   |
| Ancor Communications    | 1         | 1.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 3.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 2         | 2.3%    |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 2.3%    |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 2.3%    |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 2.3%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 2.3%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 2.3%    |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 2.3%    |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 1.15%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 1.15%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 1.15%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 1.15%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                   | 1         | 1.15%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                   | 1         | 1.15%   |
| MSI MAG341CQ MSI1462 3440x1440 797x333mm 34.0-inch                        | 1         | 1.15%   |
| LGD LCD Monitor 1920x1080                                                 | 1         | 1.15%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch              | 1         | 1.15%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD03D3 1600x900 309x174mm 14.0-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 1         | 1.15%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch              | 1         | 1.15%   |
| Lenovo LCD Monitor LEN4053 1680x1050 331x207mm 15.4-inch                  | 1         | 1.15%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch              | 1         | 1.15%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch               | 1         | 1.15%   |
| Hewlett-Packard M24f FHD HPN3706 1920x1080 527x296mm 23.8-inch            | 1         | 1.15%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch              | 1         | 1.15%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 1         | 1.15%   |
| Goldstar 24EN33 GSM59D6 1920x1080 521x293mm 23.5-inch                     | 1         | 1.15%   |
| Dell P2720DC DELD0FB 2560x1440 597x336mm 27.0-inch                        | 1         | 1.15%   |
| Dell P1911 DELA074 1440x900 408x255mm 18.9-inch                           | 1         | 1.15%   |
| Dell E2310H DELD033 1920x1080 510x287mm 23.0-inch                         | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN175E 1920x1080 381x214mm 17.2-inch          | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch           | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch          | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch          | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 1         | 1.15%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 1         | 1.15%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 1         | 1.15%   |
| BOE LCD Monitor BOE0991 1920x1080 344x194mm 15.5-inch                     | 1         | 1.15%   |
| BOE LCD Monitor BOE0918 1920x1080 309x174mm 14.0-inch                     | 1         | 1.15%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                     | 1         | 1.15%   |
| BOE LCD Monitor BOE07B5 1366x768 309x173mm 13.9-inch                      | 1         | 1.15%   |
| BOE LCD Monitor BOE0791 1920x1080 309x173mm 13.9-inch                     | 1         | 1.15%   |
| BOE LCD Monitor BOE0754 1366x768 256x144mm 11.6-inch                      | 1         | 1.15%   |
| BOE LCD Monitor BOE072C 1920x1080 309x173mm 13.9-inch                     | 1         | 1.15%   |
| BOE LCD Monitor BOE0618 1366x768 277x156mm 12.5-inch                      | 1         | 1.15%   |
| BenQ ZOWIE XL LCD BNQ7F80 1920x1080 531x299mm 24.0-inch                   | 1         | 1.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 39        | 46.99%  |
| 1366x768 (WXGA)    | 27        | 32.53%  |
| 1440x900 (WXGA+)   | 4         | 4.82%   |
| 3840x2160 (4K)     | 3         | 3.61%   |
| 2560x1440 (QHD)    | 3         | 3.61%   |
| 1600x900 (HD+)     | 3         | 3.61%   |
| 3440x1440          | 1         | 1.2%    |
| 2560x1600          | 1         | 1.2%    |
| 1920x1200 (WUXGA)  | 1         | 1.2%    |
| 1680x1050 (WSXGA+) | 1         | 1.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 37        | 43.02%  |
| 13      | 14        | 16.28%  |
| 14      | 11        | 12.79%  |
| 24      | 5         | 5.81%   |
| 17      | 5         | 5.81%   |
| 27      | 3         | 3.49%   |
| 23      | 2         | 2.33%   |
| 21      | 2         | 2.33%   |
| 11      | 2         | 2.33%   |
| 34      | 1         | 1.16%   |
| 20      | 1         | 1.16%   |
| 19      | 1         | 1.16%   |
| 12      | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 55        | 63.95%  |
| 501-600     | 9         | 10.47%  |
| 201-300     | 8         | 9.3%    |
| 351-400     | 7         | 8.14%   |
| 401-500     | 4         | 4.65%   |
| 701-800     | 1         | 1.16%   |
| 601-700     | 1         | 1.16%   |
| Unknown     | 1         | 1.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 66        | 88%     |
| 16/10   | 7         | 9.33%   |
| 21/9    | 1         | 1.33%   |
| Unknown | 1         | 1.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 37        | 43.02%  |
| 81-90          | 20        | 23.26%  |
| 201-250        | 8         | 9.3%    |
| 71-80          | 5         | 5.81%   |
| 121-130        | 4         | 4.65%   |
| 301-350        | 3         | 3.49%   |
| 51-60          | 2         | 2.33%   |
| 151-200        | 2         | 2.33%   |
| 61-70          | 1         | 1.16%   |
| 351-500        | 1         | 1.16%   |
| 251-300        | 1         | 1.16%   |
| 131-140        | 1         | 1.16%   |
| Unknown        | 1         | 1.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 41        | 48.81%  |
| 101-120       | 24        | 28.57%  |
| 51-100        | 14        | 16.67%  |
| 161-240       | 3         | 3.57%   |
| More than 240 | 1         | 1.19%   |
| Unknown       | 1         | 1.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 64        | 83.12%  |
| 2     | 13        | 16.88%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 49        | 39.52%  |
| Intel                 | 39        | 31.45%  |
| Qualcomm Atheros      | 16        | 12.9%   |
| Broadcom              | 8         | 6.45%   |
| Broadcom Limited      | 3         | 2.42%   |
| Ralink                | 2         | 1.61%   |
| Xiaomi                | 1         | 0.81%   |
| Sierra Wireless       | 1         | 0.81%   |
| Ralink Technology     | 1         | 0.81%   |
| Qualcomm              | 1         | 0.81%   |
| Linksys               | 1         | 0.81%   |
| Huawei Technologies   | 1         | 0.81%   |
| Apple                 | 1         | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 20.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 6.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 4.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 3.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 3.42%   |
| Intel Wireless 8265 / 8275                                        | 5         | 3.42%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 3.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 3.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.74%   |
| Intel Wireless 7265                                               | 4         | 2.74%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 2.74%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 2.05%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 2.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 2.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.37%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 1.37%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.37%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 1.37%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.37%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.68%   |
| Sierra Wireless MC7700                                            | 1         | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.68%   |
| Realtek 802.11ac NIC                                              | 1         | 0.68%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.68%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1         | 0.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.68%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.68%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.68%   |
| Qualcomm A0001                                                    | 1         | 0.68%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.68%   |
| Intel Wireless-AC 9260                                            | 1         | 0.68%   |
| Intel Wireless 3165                                               | 1         | 0.68%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 0.68%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.68%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 0.68%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 0.68%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 0.68%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 1         | 0.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 1         | 0.68%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.68%   |
| Huawei E353/E3131                                                 | 1         | 0.68%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.68%   |
| Apple iPad 4/Mini1                                                | 1         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 46.84%  |
| Realtek Semiconductor | 15        | 18.99%  |
| Qualcomm Atheros      | 13        | 16.46%  |
| Broadcom              | 7         | 8.86%   |
| Broadcom Limited      | 3         | 3.8%    |
| Ralink                | 2         | 2.53%   |
| Sierra Wireless       | 1         | 1.27%   |
| Ralink Technology     | 1         | 1.27%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 6.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 6.33%   |
| Intel Wireless 8265 / 8275                                     | 5         | 6.33%   |
| Intel Wi-Fi 6 AX200                                            | 5         | 6.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 5.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 5.06%   |
| Intel Wireless 7265                                            | 4         | 5.06%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 5.06%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 3.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 3.8%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 3.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 3.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 2.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 2.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.53%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 2.53%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 2.53%   |
| Sierra Wireless MC7700                                         | 1         | 1.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.27%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.27%   |
| Realtek 802.11ac NIC                                           | 1         | 1.27%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.27%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.27%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1         | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 1.27%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.27%   |
| Intel Wireless-AC 9260                                         | 1         | 1.27%   |
| Intel Wireless 3165                                            | 1         | 1.27%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.27%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 1.27%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.27%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 1.27%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 44        | 66.67%  |
| Intel                 | 12        | 18.18%  |
| Qualcomm Atheros      | 4         | 6.06%   |
| Xiaomi                | 1         | 1.52%   |
| Qualcomm              | 1         | 1.52%   |
| Linksys               | 1         | 1.52%   |
| Huawei Technologies   | 1         | 1.52%   |
| Broadcom              | 1         | 1.52%   |
| Apple                 | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 44.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 9         | 13.43%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 8.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 7.46%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 2.99%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.49%   |
| Qualcomm A0001                                                    | 1         | 1.49%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 1.49%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.49%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.49%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.49%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.49%   |
| Huawei E353/E3131                                                 | 1         | 1.49%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.49%   |
| Apple iPad 4/Mini1                                                | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 55.22%  |
| Ethernet | 60        | 44.78%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 74.07%  |
| Ethernet | 21        | 25.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 54        | 71.05%  |
| 1     | 20        | 26.32%  |
| 3     | 2         | 2.63%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 69        | 88.46%  |
| Yes  | 9         | 11.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 31        | 50.82%  |
| Realtek Semiconductor           | 10        | 16.39%  |
| Broadcom                        | 4         | 6.56%   |
| Qualcomm Atheros Communications | 3         | 4.92%   |
| Lite-On Technology              | 3         | 4.92%   |
| Apple                           | 3         | 4.92%   |
| Realtek                         | 2         | 3.28%   |
| Foxconn / Hon Hai               | 2         | 3.28%   |
| Ralink                          | 1         | 1.64%   |
| IMC Networks                    | 1         | 1.64%   |
| Cambridge Silicon Radio         | 1         | 1.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 16.39%  |
| Intel Bluetooth Device                              | 10        | 16.39%  |
| Realtek Bluetooth Radio                             | 6         | 9.84%   |
| Intel AX200 Bluetooth                               | 5         | 8.2%    |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 4.92%   |
| Lite-On Bluetooth Device                            | 3         | 4.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 4.92%   |
| Apple Bluetooth USB Host Controller                 | 3         | 4.92%   |
| Realtek Bluetooth Radio                             | 2         | 3.28%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 3.28%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 3.28%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.64%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.64%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.64%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.64%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.64%   |
| IMC Networks Bluetooth Device                       | 1         | 1.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.64%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.64%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 1.64%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.64%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 61        | 64.21%  |
| AMD                   | 14        | 14.74%  |
| Nvidia                | 13        | 13.68%  |
| C-Media Electronics   | 3         | 3.16%   |
| Realtek Semiconductor | 2         | 2.11%   |
| Plantronics           | 1         | 1.05%   |
| Corsair               | 1         | 1.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 11        | 9.32%   |
| AMD Family 17h/19h HD Audio Controller                                     | 10        | 8.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 5.93%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 4.24%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 4.24%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 4.24%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 4.24%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 3.39%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 3.39%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 3.39%   |
| Intel CM238 HD Audio Controller                                            | 4         | 3.39%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 3.39%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 2.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 2.54%   |
| Realtek Semiconductor USB Audio                                            | 2         | 1.69%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.69%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.69%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.69%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.69%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.69%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.69%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.69%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 1.69%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.85%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.85%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.85%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.85%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.85%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.85%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.85%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 0.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 0.85%   |
| Corsair HS45 Surround USB Sound Adapter                                    | 1         | 0.85%   |
| C-Media Electronics USB Audio Device                                       | 1         | 0.85%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 1         | 0.85%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 1         | 0.85%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 0.85%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 0.85%   |
| AMD FCH Azalia Controller                                                  | 1         | 0.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 0.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 25        | 33.33%  |
| SK Hynix            | 22        | 29.33%  |
| Micron Technology   | 6         | 8%      |
| Kingston            | 6         | 8%      |
| A-DATA Technology   | 3         | 4%      |
| Unknown             | 2         | 2.67%   |
| Silicon Power       | 2         | 2.67%   |
| Ramaxel Technology  | 2         | 2.67%   |
| Unknown (ABCD)      | 1         | 1.33%   |
| Team                | 1         | 1.33%   |
| Smart Brazil        | 1         | 1.33%   |
| Nanya Technology    | 1         | 1.33%   |
| Corsair             | 1         | 1.33%   |
| ASint Technology    | 1         | 1.33%   |
| Unknown             | 1         | 1.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 3.75%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 2.5%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.5%    |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 2.5%    |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 2.5%    |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 2         | 2.5%    |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 2.5%    |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 2.5%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 2.5%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 2.5%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 2.5%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 2.5%    |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 2.5%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 1.25%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 1.25%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 1.25%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 1.25%   |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 2933MT/s  | 1         | 1.25%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.25%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.25%   |
| SK Hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.25%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.25%   |
| SK Hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| SK Hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 1.25%   |
| SK Hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.25%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 1         | 1.25%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.25%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 1.25%   |
| SK Hynix RAM HCNNNBKMBLHR-NEE 1GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.25%   |
| Silicon Power RAM SP016GBSFU266B02 16GB SODIMM DDR4 2667MT/s     | 1         | 1.25%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 1         | 1.25%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.25%   |
| Samsung RAM M471B5273DM0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.25%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.25%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 1         | 1.25%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.25%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.25%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 1.25%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.25%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 1.25%   |
| Samsung RAM K4E6E304EE-EGCE 4096MB 1600MT/s                      | 1         | 1.25%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 1.25%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s          | 1         | 1.25%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 1         | 1.25%   |
| Micron RAM Module 4GB SODIMM DDR4 2400MT/s                       | 1         | 1.25%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 1.25%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 1         | 1.25%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s            | 1         | 1.25%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s        | 1         | 1.25%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16GB SODIMM DDR4 2400MT/s           | 1         | 1.25%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s            | 1         | 1.25%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 1         | 1.25%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s          | 1         | 1.25%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 1         | 1.25%   |
| Kingston RAM 9905469-157.A01LF 4GB SODIMM DDR3 1600MT/s          | 1         | 1.25%   |
| Kingston RAM 9905469-024.A00LF 2048MB SODIMM DDR3 1333MT/s       | 1         | 1.25%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 34        | 53.13%  |
| DDR3    | 22        | 34.38%  |
| LPDDR4  | 3         | 4.69%   |
| SDRAM   | 2         | 3.13%   |
| LPDDR3  | 2         | 3.13%   |
| Unknown | 1         | 1.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 56        | 87.5%   |
| Row Of Chips | 6         | 9.38%   |
| DIMM         | 1         | 1.56%   |
| Unknown      | 1         | 1.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 29        | 41.43%  |
| 8192  | 21        | 30%     |
| 16384 | 9         | 12.86%  |
| 2048  | 8         | 11.43%  |
| 32768 | 2         | 2.86%   |
| 1024  | 1         | 1.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 23        | 33.82%  |
| 3200  | 14        | 20.59%  |
| 2667  | 11        | 16.18%  |
| 2400  | 7         | 10.29%  |
| 1333  | 3         | 4.41%   |
| 4199  | 2         | 2.94%   |
| 2133  | 2         | 2.94%   |
| 4267  | 1         | 1.47%   |
| 3400  | 1         | 1.47%   |
| 3266  | 1         | 1.47%   |
| 2933  | 1         | 1.47%   |
| 1334  | 1         | 1.47%   |
| 1066  | 1         | 1.47%   |

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
| Chicony Electronics                    | 15        | 22.73%  |
| Realtek Semiconductor                  | 8         | 12.12%  |
| Acer                                   | 8         | 12.12%  |
| Quanta                                 | 7         | 10.61%  |
| Suyin                                  | 5         | 7.58%   |
| IMC Networks                           | 5         | 7.58%   |
| Syntek                                 | 3         | 4.55%   |
| Alcor Micro                            | 3         | 4.55%   |
| Silicon Motion                         | 2         | 3.03%   |
| Microdia                               | 2         | 3.03%   |
| Luxvisions Innotech Limited            | 2         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.03%   |
| Sunplus Innovation Technology          | 1         | 1.52%   |
| Lite-On Technology                     | 1         | 1.52%   |
| LG Electronics                         | 1         | 1.52%   |
| Lenovo                                 | 1         | 1.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                   | 4         | 6.06%   |
| IMC Networks Integrated Camera                                 | 4         | 6.06%   |
| Chicony Integrated Camera                                      | 4         | 6.06%   |
| Chicony HD WebCam                                              | 4         | 6.06%   |
| Syntek EasyCamera                                              | 2         | 3.03%   |
| Suyin HP Webcam                                                | 2         | 3.03%   |
| Silicon Motion 300k Pixel Camera                               | 2         | 3.03%   |
| Realtek USB2.0 HD UVC WebCam                                   | 2         | 3.03%   |
| Quanta HP Webcam                                               | 2         | 3.03%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 3.03%   |
| Chicony Integrated Camera (1280x720@30)                        | 2         | 3.03%   |
| Acer Integrated Camera                                         | 2         | 3.03%   |
| Syntek Integrated Camera                                       | 1         | 1.52%   |
| Suyin USB Webcam                                               | 1         | 1.52%   |
| Suyin NEC HD WebCam                                            | 1         | 1.52%   |
| Suyin 1.3M HD WebCam                                           | 1         | 1.52%   |
| Sunplus HD WebCam                                              | 1         | 1.52%   |
| Realtek Integrated Webcam                                      | 1         | 1.52%   |
| Realtek HD WebCam                                              | 1         | 1.52%   |
| Quanta VGA WebCam                                              | 1         | 1.52%   |
| Quanta USB2.0 VGA UVC WebCam                                   | 1         | 1.52%   |
| Quanta HD User Facing                                          | 1         | 1.52%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 1.52%   |
| Microdia Integrated Webcam                                     | 1         | 1.52%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 1.52%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 1.52%   |
| Lite-On HP HD Camera                                           | 1         | 1.52%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)          | 1         | 1.52%   |
| Lenovo UVC Camera                                              | 1         | 1.52%   |
| IMC Networks Integrated Webcam                                 | 1         | 1.52%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 1.52%   |
| Chicony USB2.0 Camera                                          | 1         | 1.52%   |
| Chicony USB2.0 0.3M UVC WebCam                                 | 1         | 1.52%   |
| Chicony Thinkpad T430 camera                                   | 1         | 1.52%   |
| Chicony Lenovo EasyCamera                                      | 1         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 1         | 1.52%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.52%   |
| Alcor Micro USB 2.0 Camera                                     | 1         | 1.52%   |
| Alcor Micro Lenovo EasyCamera                                  | 1         | 1.52%   |
| Alcor Micro Asus Integrated Webcam                             | 1         | 1.52%   |
| Acer Lenovo Integrated Webcam                                  | 1         | 1.52%   |
| Acer Lenovo EasyCamera                                         | 1         | 1.52%   |
| Acer Integrated 5M Camera                                      | 1         | 1.52%   |
| Acer HD Webcam                                                 | 1         | 1.52%   |
| Acer BisonCam,NB Pro                                           | 1         | 1.52%   |
| Acer BisonCam, NB Pro                                          | 1         | 1.52%   |

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
| 0     | 53        | 68.83%  |
| 1     | 20        | 25.97%  |
| 2     | 4         | 5.19%   |

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

