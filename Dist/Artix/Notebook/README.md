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

Total: 126

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MOTILE        | M141                        | [59c616a04e](https://linux-hardware.org/?probe=59c616a04e) | Jun 30, 2022 |
| HUAWEI        | WRT-WX9                     | [8ddbebd4b1](https://linux-hardware.org/?probe=8ddbebd4b1) | Jun 28, 2022 |
| AXIOO         | Mybook 14E                  | [499861f5e9](https://linux-hardware.org/?probe=499861f5e9) | Jun 19, 2022 |
| Timi          | RedmiBook 14 II             | [a4b535cdee](https://linux-hardware.org/?probe=a4b535cdee) | Jun 15, 2022 |
| Lenovo        | ThinkPad T440s 20ARS0MV0... | [3c23c9dfc6](https://linux-hardware.org/?probe=3c23c9dfc6) | Jun 08, 2022 |
| ASUSTek       | X553MA                      | [2a3ac45d9c](https://linux-hardware.org/?probe=2a3ac45d9c) | Jun 05, 2022 |
| Dell          | Precision M6600             | [bb044c066c](https://linux-hardware.org/?probe=bb044c066c) | Jun 05, 2022 |
| Dell          | Latitude 5490               | [630b63edff](https://linux-hardware.org/?probe=630b63edff) | Jun 02, 2022 |
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
| Artix Rolling  | 53        | 58.89%  |
| Artix          | 35        | 38.89%  |
| Artix 20201207 | 1         | 1.11%   |
| Artix 20201128 | 1         | 1.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Artix | 85        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.9.14-artix1-1                 | 6         | 5.77%   |
| 5.7.6-artix1-1                  | 3         | 2.88%   |
| 5.7.12-artix1-1                 | 2         | 1.92%   |
| 5.18.6-artix1-1                 | 2         | 1.92%   |
| 5.18.0-artix1-1                 | 2         | 1.92%   |
| 5.17.1-artix1-1                 | 2         | 1.92%   |
| 5.16.8-artix1-2                 | 2         | 1.92%   |
| 5.16.10-artix1-1                | 2         | 1.92%   |
| 5.15.12-artix1-1                | 2         | 1.92%   |
| 5.14.16-artix1-1                | 2         | 1.92%   |
| 5.13.8-artix1-1                 | 2         | 1.92%   |
| 5.12.8-artix1-1                 | 2         | 1.92%   |
| 5.12.12-zen1-1-zen              | 2         | 1.92%   |
| 5.12.12-artix1-1                | 2         | 1.92%   |
| 5.11.6-artix1-1                 | 2         | 1.92%   |
| 5.10.6-artix1-1                 | 2         | 1.92%   |
| 5.10.4-artix2-1                 | 2         | 1.92%   |
| 5.10.16-artix1-1                | 2         | 1.92%   |
| 5.9.6-artix1-1                  | 1         | 0.96%   |
| 5.9.14-zen1-1-zen               | 1         | 0.96%   |
| 5.9.12-artix1-1                 | 1         | 0.96%   |
| 5.9.1-artix1-1                  | 1         | 0.96%   |
| 5.9.0-zen1-1-zen                | 1         | 0.96%   |
| 5.9.0-1-mainline-bootsplash     | 1         | 0.96%   |
| 5.8.8-artix1-1                  | 1         | 0.96%   |
| 5.8.4-artix1-1                  | 1         | 0.96%   |
| 5.8.14-zen1-1-zen               | 1         | 0.96%   |
| 5.8.14-artix1-1                 | 1         | 0.96%   |
| 5.8.12-artix1-1                 | 1         | 0.96%   |
| 5.8.0-rc7-5-mainline-bootsplash | 1         | 0.96%   |
| 5.7.8-artix1-1                  | 1         | 0.96%   |
| 5.7.2-artix1-1                  | 1         | 0.96%   |
| 5.6.7-x86_64                    | 1         | 0.96%   |
| 5.5.3-artix1-1                  | 1         | 0.96%   |
| 5.5.10-artix1-1                 | 1         | 0.96%   |
| 5.4.74-1-lts                    | 1         | 0.96%   |
| 5.18.5-artix1-1                 | 1         | 0.96%   |
| 5.18.3-zen1-1-zen               | 1         | 0.96%   |
| 5.17.5-256-tkg-pds              | 1         | 0.96%   |
| 5.17.4-artix1-1                 | 1         | 0.96%   |
| 5.17.3-zen1-1-zen               | 1         | 0.96%   |
| 5.17.2-artix3-1                 | 1         | 0.96%   |
| 5.17.12-xanmod1-1               | 1         | 0.96%   |
| 5.17.1-zen1-1-zen               | 1         | 0.96%   |
| 5.16.8-zen1-1-zen               | 1         | 0.96%   |
| 5.16.7-artix1-1                 | 1         | 0.96%   |
| 5.16.3-artix1-1                 | 1         | 0.96%   |
| 5.16.1-artix1-1                 | 1         | 0.96%   |
| 5.16.0-arch1-g400s              | 1         | 0.96%   |
| 5.15.8-artix1-1                 | 1         | 0.96%   |
| 5.15.7-zen1-1-zen               | 1         | 0.96%   |
| 5.15.5-zen1-1-zen               | 1         | 0.96%   |
| 5.15.43-1-lts                   | 1         | 0.96%   |
| 5.15.4-artix1-1                 | 1         | 0.96%   |
| 5.15.36-1-lts                   | 1         | 0.96%   |
| 5.15.3-zen1-1-zen               | 1         | 0.96%   |
| 5.15.16-1-lts                   | 1         | 0.96%   |
| 5.15.12-zen1-1-zen              | 1         | 0.96%   |
| 5.14.7-zen1-1-zen               | 1         | 0.96%   |
| 5.14.14-artix1-1                | 1         | 0.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.14  | 7         | 6.73%   |
| 5.12.12 | 4         | 3.85%   |
| 5.7.6   | 3         | 2.88%   |
| 5.17.1  | 3         | 2.88%   |
| 5.16.8  | 3         | 2.88%   |
| 5.15.12 | 3         | 2.88%   |
| 5.12.8  | 3         | 2.88%   |
| 5.9.0   | 2         | 1.92%   |
| 5.8.14  | 2         | 1.92%   |
| 5.7.12  | 2         | 1.92%   |
| 5.18.6  | 2         | 1.92%   |
| 5.18.0  | 2         | 1.92%   |
| 5.16.10 | 2         | 1.92%   |
| 5.14.16 | 2         | 1.92%   |
| 5.13.8  | 2         | 1.92%   |
| 5.12.14 | 2         | 1.92%   |
| 5.11.6  | 2         | 1.92%   |
| 5.10.6  | 2         | 1.92%   |
| 5.10.4  | 2         | 1.92%   |
| 5.10.16 | 2         | 1.92%   |
| 5.9.6   | 1         | 0.96%   |
| 5.9.12  | 1         | 0.96%   |
| 5.9.1   | 1         | 0.96%   |
| 5.8.8   | 1         | 0.96%   |
| 5.8.4   | 1         | 0.96%   |
| 5.8.12  | 1         | 0.96%   |
| 5.8.0   | 1         | 0.96%   |
| 5.7.8   | 1         | 0.96%   |
| 5.7.2   | 1         | 0.96%   |
| 5.6.7   | 1         | 0.96%   |
| 5.5.3   | 1         | 0.96%   |
| 5.5.10  | 1         | 0.96%   |
| 5.4.74  | 1         | 0.96%   |
| 5.18.5  | 1         | 0.96%   |
| 5.18.3  | 1         | 0.96%   |
| 5.17.5  | 1         | 0.96%   |
| 5.17.4  | 1         | 0.96%   |
| 5.17.3  | 1         | 0.96%   |
| 5.17.2  | 1         | 0.96%   |
| 5.17.12 | 1         | 0.96%   |
| 5.16.7  | 1         | 0.96%   |
| 5.16.3  | 1         | 0.96%   |
| 5.16.1  | 1         | 0.96%   |
| 5.16.0  | 1         | 0.96%   |
| 5.15.8  | 1         | 0.96%   |
| 5.15.7  | 1         | 0.96%   |
| 5.15.5  | 1         | 0.96%   |
| 5.15.43 | 1         | 0.96%   |
| 5.15.4  | 1         | 0.96%   |
| 5.15.36 | 1         | 0.96%   |
| 5.15.3  | 1         | 0.96%   |
| 5.15.16 | 1         | 0.96%   |
| 5.14.7  | 1         | 0.96%   |
| 5.14.14 | 1         | 0.96%   |
| 5.13.13 | 1         | 0.96%   |
| 5.13.12 | 1         | 0.96%   |
| 5.12.6  | 1         | 0.96%   |
| 5.12.5  | 1         | 0.96%   |
| 5.12.4  | 1         | 0.96%   |
| 5.12.0  | 1         | 0.96%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.12    | 12        | 12.24%  |
| 5.9     | 11        | 11.22%  |
| 5.15    | 11        | 11.22%  |
| 5.10    | 11        | 11.22%  |
| 5.17    | 8         | 8.16%   |
| 5.16    | 8         | 8.16%   |
| 5.11    | 8         | 8.16%   |
| 5.7     | 6         | 6.12%   |
| 5.18    | 6         | 6.12%   |
| 5.8     | 5         | 5.1%    |
| 5.14    | 4         | 4.08%   |
| 5.13    | 4         | 4.08%   |
| 5.6     | 1         | 1.02%   |
| 5.5     | 1         | 1.02%   |
| 5.4     | 1         | 1.02%   |
| 4.19    | 1         | 1.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 85        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| KDE5           | 20        | 21.98%  |
| XFCE           | 14        | 15.38%  |
| GNOME          | 14        | 15.38%  |
| Unknown        | 14        | 15.38%  |
| X-Cinnamon     | 5         | 5.49%   |
| MATE           | 4         | 4.4%    |
| KDE            | 4         | 4.4%    |
| LXQt           | 3         | 3.3%    |
| Cinnamon       | 3         | 3.3%    |
| bspwm          | 2         | 2.2%    |
| xmonad         | 1         | 1.1%    |
| sway-dbus      | 1         | 1.1%    |
| Sway           | 1         | 1.1%    |
| nxde           | 1         | 1.1%    |
| LXDE           | 1         | 1.1%    |
| i3             | 1         | 1.1%    |
| awesomeminimal | 1         | 1.1%    |
| awesome        | 1         | 1.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 61        | 68.54%  |
| Tty     | 13        | 14.61%  |
| Wayland | 11        | 12.36%  |
| Unknown | 4         | 4.49%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 30        | 34.48%  |
| LightDM | 28        | 32.18%  |
| SDDM    | 24        | 27.59%  |
| XDM     | 1         | 1.15%   |
| SLiM    | 1         | 1.15%   |
| Ly      | 1         | 1.15%   |
| LXDM    | 1         | 1.15%   |
| GDM     | 1         | 1.15%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 45        | 50%     |
| Unknown | 11        | 12.22%  |
| ru_RU   | 7         | 7.78%   |
| en_GB   | 7         | 7.78%   |
| fr_FR   | 3         | 3.33%   |
| C       | 3         | 3.33%   |
| es_ES   | 2         | 2.22%   |
| en_CA   | 2         | 2.22%   |
| uk_UA   | 1         | 1.11%   |
| pt_PT   | 1         | 1.11%   |
| pt_BR   | 1         | 1.11%   |
| pl_PL   | 1         | 1.11%   |
| it_IT   | 1         | 1.11%   |
| en_IN   | 1         | 1.11%   |
| en_AU   | 1         | 1.11%   |
| el_GR   | 1         | 1.11%   |
| de_DE   | 1         | 1.11%   |
| cs_CZ   | 1         | 1.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 65        | 75.58%  |
| BIOS | 21        | 24.42%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 64        | 74.42%  |
| Btrfs   | 18        | 20.93%  |
| Xfs     | 2         | 2.33%   |
| Overlay | 1         | 1.16%   |
| F2fs    | 1         | 1.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 64        | 74.42%  |
| Unknown | 12        | 13.95%  |
| MBR     | 10        | 11.63%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 72        | 83.72%  |
| Yes       | 14        | 16.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 74.12%  |
| Yes       | 22        | 25.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 25        | 29.41%  |
| Hewlett-Packard     | 13        | 15.29%  |
| Dell                | 11        | 12.94%  |
| Acer                | 9         | 10.59%  |
| ASUSTek Computer    | 8         | 9.41%   |
| Apple               | 3         | 3.53%   |
| Timi                | 2         | 2.35%   |
| Notebook            | 2         | 2.35%   |
| MSI                 | 2         | 2.35%   |
| GPD                 | 2         | 2.35%   |
| Gigabyte Technology | 2         | 2.35%   |
| UNOWHY              | 1         | 1.18%   |
| Quanta              | 1         | 1.18%   |
| MOTILE              | 1         | 1.18%   |
| LG Electronics      | 1         | 1.18%   |
| HUAWEI              | 1         | 1.18%   |
| AXIOO               | 1         | 1.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Timi RedmiBook 14 II                   | 2         | 2.35%   |
| Lenovo IdeaPad 5 15IIL05 81YK          | 2         | 2.35%   |
| HP 15                                  | 2         | 2.35%   |
| GPD P2 MAX                             | 2         | 2.35%   |
| Dell Precision M6600                   | 2         | 2.35%   |
| Dell Precision 7550                    | 2         | 2.35%   |
| Apple MacBookAir7,2                    | 2         | 2.35%   |
| UNOWHY Y13G010S4EI                     | 1         | 1.18%   |
| Quanta SWH                             | 1         | 1.18%   |
| Notebook N141CU                        | 1         | 1.18%   |
| Notebook N130BU                        | 1         | 1.18%   |
| MSI Modern 15 A11M                     | 1         | 1.18%   |
| MSI GP72 7RDX                          | 1         | 1.18%   |
| MOTILE M141                            | 1         | 1.18%   |
| LG 17Z990-R.AAC9U1                     | 1         | 1.18%   |
| Lenovo ThinkPad W500 4063CJ5           | 1         | 1.18%   |
| Lenovo ThinkPad T480s 20L8S3D400       | 1         | 1.18%   |
| Lenovo ThinkPad T480 MFG_IN_GO         | 1         | 1.18%   |
| Lenovo ThinkPad T440s 20ARS0MV00       | 1         | 1.18%   |
| Lenovo ThinkPad T430 2350BC6           | 1         | 1.18%   |
| Lenovo ThinkPad T430 2347H76           | 1         | 1.18%   |
| Lenovo ThinkPad T420 4236H45           | 1         | 1.18%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00   | 1         | 1.18%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800   | 1         | 1.18%   |
| Lenovo ThinkPad P1 Gen 3 20TH001EMH    | 1         | 1.18%   |
| Lenovo ThinkPad E14 Gen 2 20T6000MCK   | 1         | 1.18%   |
| Lenovo ThinkPad 11e 5th Gen 20LNS0P500 | 1         | 1.18%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 1         | 1.18%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 1.18%   |
| Lenovo LaVie Z 20FF0012US              | 1         | 1.18%   |
| Lenovo IdeaPad Y500 20193              | 1         | 1.18%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL  | 1         | 1.18%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG   | 1         | 1.18%   |
| Lenovo IdeaPad 510-15IKB 80SV          | 1         | 1.18%   |
| Lenovo IdeaPad 330-15IKB 81DE          | 1         | 1.18%   |
| Lenovo G400s 20244                     | 1         | 1.18%   |
| Lenovo B590 20206                      | 1         | 1.18%   |
| Lenovo B570e HuronRiver Platform       | 1         | 1.18%   |
| HUAWEI WRT-WX9                         | 1         | 1.18%   |
| HP ProBook 450 G6                      | 1         | 1.18%   |
| HP OMEN Laptop 15-en0xxx               | 1         | 1.18%   |
| HP Laptop 17z-ca300                    | 1         | 1.18%   |
| HP Laptop 15-ef1xxx                    | 1         | 1.18%   |
| HP Laptop 14s-dq2xxx                   | 1         | 1.18%   |
| HP Laptop 14s-cf3xxx                   | 1         | 1.18%   |
| HP 255 G7 Notebook PC                  | 1         | 1.18%   |
| HP 250 G7 Notebook PC                  | 1         | 1.18%   |
| HP 250 G4 Notebook PC                  | 1         | 1.18%   |
| HP 250 G3                              | 1         | 1.18%   |
| HP 246                                 | 1         | 1.18%   |
| Gigabyte B450M DS3H                    | 1         | 1.18%   |
| Gigabyte AERO 15-X9                    | 1         | 1.18%   |
| Dell Precision 5520                    | 1         | 1.18%   |
| Dell Precision 3540                    | 1         | 1.18%   |
| Dell Latitude E6530                    | 1         | 1.18%   |
| Dell Latitude E6440                    | 1         | 1.18%   |
| Dell Latitude 5490                     | 1         | 1.18%   |
| Dell Inspiron 5570                     | 1         | 1.18%   |
| Dell Inspiron 3442                     | 1         | 1.18%   |
| AXIOO Mybook 14E                       | 1         | 1.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 12        | 14.12%  |
| Lenovo IdeaPad     | 7         | 8.24%   |
| Dell Precision     | 6         | 7.06%   |
| Acer Aspire        | 6         | 7.06%   |
| HP Laptop          | 4         | 4.71%   |
| HP 250             | 3         | 3.53%   |
| Dell Latitude      | 3         | 3.53%   |
| Timi RedmiBook     | 2         | 2.35%   |
| HP 15              | 2         | 2.35%   |
| GPD P2             | 2         | 2.35%   |
| Dell Inspiron      | 2         | 2.35%   |
| Apple MacBookAir7  | 2         | 2.35%   |
| Acer Nitro         | 2         | 2.35%   |
| UNOWHY Y13G010S4EI | 1         | 1.18%   |
| Quanta SWH         | 1         | 1.18%   |
| Notebook N141CU    | 1         | 1.18%   |
| Notebook N130BU    | 1         | 1.18%   |
| MSI Modern         | 1         | 1.18%   |
| MSI GP72           | 1         | 1.18%   |
| MOTILE M141        | 1         | 1.18%   |
| LG 17Z990-R.AAC9U1 | 1         | 1.18%   |
| Lenovo ThinkBook   | 1         | 1.18%   |
| Lenovo Legion      | 1         | 1.18%   |
| Lenovo LaVie       | 1         | 1.18%   |
| Lenovo G400s       | 1         | 1.18%   |
| Lenovo B590        | 1         | 1.18%   |
| Lenovo B570e       | 1         | 1.18%   |
| HUAWEI WRT-WX9     | 1         | 1.18%   |
| HP ProBook         | 1         | 1.18%   |
| HP OMEN            | 1         | 1.18%   |
| HP 255             | 1         | 1.18%   |
| HP 246             | 1         | 1.18%   |
| Gigabyte B450M     | 1         | 1.18%   |
| Gigabyte AERO      | 1         | 1.18%   |
| AXIOO Mybook       | 1         | 1.18%   |
| ASUS X553MA        | 1         | 1.18%   |
| ASUS VivoBook      | 1         | 1.18%   |
| ASUS K53SC         | 1         | 1.18%   |
| ASUS K50IE         | 1         | 1.18%   |
| ASUS GX501VIK      | 1         | 1.18%   |
| ASUS GL702ZC       | 1         | 1.18%   |
| ASUS E402NA        | 1         | 1.18%   |
| ASUS 1225C         | 1         | 1.18%   |
| Apple MacBookPro11 | 1         | 1.18%   |
| Acer Swift         | 1         | 1.18%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 20        | 23.53%  |
| 2018 | 11        | 12.94%  |
| 2019 | 10        | 11.76%  |
| 2017 | 8         | 9.41%   |
| 2014 | 7         | 8.24%   |
| 2011 | 7         | 8.24%   |
| 2016 | 6         | 7.06%   |
| 2012 | 6         | 7.06%   |
| 2013 | 4         | 4.71%   |
| 2021 | 2         | 2.35%   |
| 2015 | 2         | 2.35%   |
| 2010 | 1         | 1.18%   |
| 2009 | 1         | 1.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 85        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 84        | 98.82%  |
| Enabled  | 1         | 1.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 85        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 24        | 27.91%  |
| 8.01-16.0   | 22        | 25.58%  |
| 16.01-24.0  | 15        | 17.44%  |
| 3.01-4.0    | 12        | 13.95%  |
| 32.01-64.0  | 4         | 4.65%   |
| 1.01-2.0    | 4         | 4.65%   |
| 64.01-256.0 | 3         | 3.49%   |
| 24.01-32.0  | 2         | 2.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 28        | 28.57%  |
| 4.01-8.0   | 21        | 21.43%  |
| 2.01-3.0   | 19        | 19.39%  |
| 3.01-4.0   | 14        | 14.29%  |
| 0.51-1.0   | 9         | 9.18%   |
| 8.01-16.0  | 4         | 4.08%   |
| 0.01-0.5   | 2         | 2.04%   |
| 16.01-24.0 | 1         | 1.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 66        | 76.74%  |
| 2      | 19        | 22.09%  |
| 3      | 1         | 1.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 74.12%  |
| Yes       | 22        | 25.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 80%     |
| No        | 17        | 20%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 84        | 98.82%  |
| No        | 1         | 1.18%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 78.16%  |
| No        | 19        | 21.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 21        | 24.71%  |
| Russia      | 7         | 8.24%   |
| UK          | 4         | 4.71%   |
| Turkey      | 4         | 4.71%   |
| Indonesia   | 4         | 4.71%   |
| Germany     | 4         | 4.71%   |
| Canada      | 4         | 4.71%   |
| Brazil      | 4         | 4.71%   |
| Ukraine     | 3         | 3.53%   |
| Netherlands | 3         | 3.53%   |
| India       | 3         | 3.53%   |
| France      | 3         | 3.53%   |
| Switzerland | 2         | 2.35%   |
| Spain       | 2         | 2.35%   |
| Poland      | 2         | 2.35%   |
| Bulgaria    | 2         | 2.35%   |
| Uzbekistan  | 1         | 1.18%   |
| Sweden      | 1         | 1.18%   |
| Lithuania   | 1         | 1.18%   |
| Italy       | 1         | 1.18%   |
| Greece      | 1         | 1.18%   |
| Czechia     | 1         | 1.18%   |
| China       | 1         | 1.18%   |
| Chile       | 1         | 1.18%   |
| Bangladesh  | 1         | 1.18%   |
| Azerbaijan  | 1         | 1.18%   |
| Australia   | 1         | 1.18%   |
| Argentina   | 1         | 1.18%   |
| Algeria     | 1         | 1.18%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 3         | 3.33%   |
| Jakarta           | 3         | 3.33%   |
| St Petersburg     | 2         | 2.22%   |
| San Ramon         | 2         | 2.22%   |
| Omaha             | 2         | 2.22%   |
| Neuchatel         | 2         | 2.22%   |
| Los Angeles       | 2         | 2.22%   |
| Frankfurt am Main | 2         | 2.22%   |
| Dnipro            | 2         | 2.22%   |
| Amsterdam         | 2         | 2.22%   |
| Zaporizhzhya      | 1         | 1.11%   |
| Wigan             | 1         | 1.11%   |
| Wem               | 1         | 1.11%   |
| Vilnius           | 1         | 1.11%   |
| Varna             | 1         | 1.11%   |
| Vancouver         | 1         | 1.11%   |
| Toronto           | 1         | 1.11%   |
| Tashkent          | 1         | 1.11%   |
| Syeverodonets'k   | 1         | 1.11%   |
| Surgut            | 1         | 1.11%   |
| Stuttgart         | 1         | 1.11%   |
| Stockholm         | 1         | 1.11%   |
| Sofia             | 1         | 1.11%   |
| Snohomish         | 1         | 1.11%   |
| Skikda            | 1         | 1.11%   |
| Sigogne           | 1         | 1.11%   |
| Seville           | 1         | 1.11%   |
| Semarang          | 1         | 1.11%   |
| Seattle           | 1         | 1.11%   |
| Santiago          | 1         | 1.11%   |
| Santa Fe          | 1         | 1.11%   |
| Samara            | 1         | 1.11%   |
| Sainte-Severe     | 1         | 1.11%   |
| Rio de Janeiro    | 1         | 1.11%   |
| Quincy            | 1         | 1.11%   |
| Puducherry        | 1         | 1.11%   |
| Prague            | 1         | 1.11%   |
| Ordu              | 1         | 1.11%   |
| Omsk              | 1         | 1.11%   |
| New York          | 1         | 1.11%   |
| Nantes            | 1         | 1.11%   |
| Mount Pearl       | 1         | 1.11%   |
| Moscow            | 1         | 1.11%   |
| Mississauga       | 1         | 1.11%   |
| Minneapolis       | 1         | 1.11%   |
| Milton            | 1         | 1.11%   |
| Malda             | 1         | 1.11%   |
| Malappuram        | 1         | 1.11%   |
| Liverpool         | 1         | 1.11%   |
| Lexington         | 1         | 1.11%   |
| Leander           | 1         | 1.11%   |
| Lavras            | 1         | 1.11%   |
| Laurel            | 1         | 1.11%   |
| Las Vegas         | 1         | 1.11%   |
| Kłodzko          | 1         | 1.11%   |
| Kavala            | 1         | 1.11%   |
| Hangzhou          | 1         | 1.11%   |
| Hampton           | 1         | 1.11%   |
| Guacui            | 1         | 1.11%   |
| Glide             | 1         | 1.11%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 21        | 27     | 20%     |
| Seagate                   | 14        | 14     | 13.33%  |
| WDC                       | 8         | 11     | 7.62%   |
| Toshiba                   | 8         | 8      | 7.62%   |
| SanDisk                   | 6         | 6      | 5.71%   |
| Intel                     | 6         | 8      | 5.71%   |
| SK hynix                  | 5         | 11     | 4.76%   |
| HGST                      | 5         | 5      | 4.76%   |
| Kingston                  | 4         | 5      | 3.81%   |
| China                     | 4         | 4      | 3.81%   |
| Hitachi                   | 3         | 4      | 2.86%   |
| Apple                     | 3         | 4      | 2.86%   |
| Unknown                   | 2         | 2      | 1.9%    |
| Phison Electronics        | 2         | 3      | 1.9%    |
| Crucial                   | 2         | 2      | 1.9%    |
| Timetec                   | 1         | 2      | 0.95%   |
| SPCC                      | 1         | 1      | 0.95%   |
| Solid State Storage       | 1         | 1      | 0.95%   |
| PNY                       | 1         | 1      | 0.95%   |
| Patriot                   | 1         | 1      | 0.95%   |
| Micron/Crucial Technology | 1         | 1      | 0.95%   |
| LITEON                    | 1         | 1      | 0.95%   |
| Lite-On                   | 1         | 1      | 0.95%   |
| Linux                     | 1         | 1      | 0.95%   |
| LDLC                      | 1         | 5      | 0.95%   |
| Intenso                   | 1         | 1      | 0.95%   |
| Unknown                   | 1         | 1      | 0.95%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| SanDisk NVMe SSD Drive 512GB              | 4         | 3.64%   |
| Seagate ST1000LM035-1RK172 1TB            | 3         | 2.73%   |
| China SATA SSD 960GB                      | 3         | 2.73%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 2         | 1.82%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 1.82%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 1.82%   |
| Seagate ST500LT012-1DG142 500GB           | 2         | 1.82%   |
| Samsung NVMe SSD Drive 1TB                | 2         | 1.82%   |
| Samsung MZNLH512HALU-00000 512GB SSD      | 2         | 1.82%   |
| Phison PCIe SSD 2TB                       | 2         | 1.82%   |
| HGST HTS545050A7E680 500GB                | 2         | 1.82%   |
| Apple SSD SM0256G 256GB                   | 2         | 1.82%   |
| WDC WDS200T2B0B-00YS70 2TB SSD            | 1         | 0.91%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 0.91%   |
| WDC WD5000BPVT-22HXZT3 500GB              | 1         | 0.91%   |
| WDC WD3200LPVT-00FMCT0 320GB              | 1         | 0.91%   |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 0.91%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 1         | 0.91%   |
| Unknown SD/MMC/MS PRO 128GB               | 1         | 0.91%   |
| Unknown DA4064  64GB                      | 1         | 0.91%   |
| Toshiba THNSNH128GMCT 128GB SSD           | 1         | 0.91%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 0.91%   |
| Toshiba MK5065GSX 500GB                   | 1         | 0.91%   |
| Toshiba KBG30ZMT256G 256GB                | 1         | 0.91%   |
| Timetec 35TTM8SSATA-512GB                 | 1         | 0.91%   |
| SPCC Solid State Disk 256GB               | 1         | 0.91%   |
| Solid State Storage SSSTC CL1-4D256 256GB | 1         | 0.91%   |
| SK hynix SKHynix_HFS512GD9TNI-L2B0B 512GB | 1         | 0.91%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB | 1         | 0.91%   |
| SK hynix SC311 SATA 256GB SSD             | 1         | 0.91%   |
| SK hynix NVMe SSD Drive 1TB               | 1         | 0.91%   |
| SK hynix NVMe SSD Drive 1024GB            | 1         | 0.91%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB   | 1         | 0.91%   |
| Seagate ST9500420AS 500GB                 | 1         | 0.91%   |
| Seagate ST9500325AS 500GB                 | 1         | 0.91%   |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 0.91%   |
| Seagate ST500LT012-9WS142 500GB           | 1         | 0.91%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 0.91%   |
| Seagate ST2000LM015-2E8174 2TB            | 1         | 0.91%   |
| Seagate ST2000LM003 HN-M201RAD 2TB        | 1         | 0.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 0.91%   |
| Seagate BUP Portable 5TB                  | 1         | 0.91%   |
| SanDisk SSD U100 16GB                     | 1         | 0.91%   |
| SanDisk NVMe SSD Drive 500GB              | 1         | 0.91%   |
| Samsung SSD 970 EVO Plus 1TB              | 1         | 0.91%   |
| Samsung SSD 970 EVO 1TB                   | 1         | 0.91%   |
| Samsung SSD 870 EVO 250GB                 | 1         | 0.91%   |
| Samsung SSD 850 EVO 250GB                 | 1         | 0.91%   |
| Samsung SM961 NVMe 512GB                  | 1         | 0.91%   |
| Samsung NVMe SSD Drive 2TB                | 1         | 0.91%   |
| Samsung NVMe SSD Drive 256GB              | 1         | 0.91%   |
| Samsung NVMe SSD Drive 1024GB             | 1         | 0.91%   |
| Samsung MZYTY256HDHP-000L2 256GB SSD      | 1         | 0.91%   |
| Samsung MZVPW256HEGL-000L7 256GB          | 1         | 0.91%   |
| Samsung MZVLQ512HALU-00000 512GB          | 1         | 0.91%   |
| Samsung MZVLB512HBJQ-000H1 512GB          | 1         | 0.91%   |
| Samsung MZVLB256HBHQ-00000 256GB          | 1         | 0.91%   |
| Samsung MZVLB1T0HBLR-000L7 1TB            | 1         | 0.91%   |
| Samsung MZVKW512HMJP-00000 512GB          | 1         | 0.91%   |
| Samsung MZNTE256HMHP-000L1 256GB SSD      | 1         | 0.91%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 14     | 38.89%  |
| WDC     | 7         | 9      | 19.44%  |
| Toshiba | 6         | 6      | 16.67%  |
| HGST    | 5         | 5      | 13.89%  |
| Hitachi | 3         | 4      | 8.33%   |
| Unknown | 1         | 1      | 2.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 8      | 21.43%  |
| China               | 4         | 4      | 14.29%  |
| Apple               | 3         | 4      | 10.71%  |
| Kingston            | 2         | 2      | 7.14%   |
| Crucial             | 2         | 2      | 7.14%   |
| WDC                 | 1         | 2      | 3.57%   |
| Toshiba             | 1         | 1      | 3.57%   |
| SPCC                | 1         | 1      | 3.57%   |
| SK hynix            | 1         | 1      | 3.57%   |
| SanDisk             | 1         | 1      | 3.57%   |
| PNY                 | 1         | 1      | 3.57%   |
| Patriot             | 1         | 1      | 3.57%   |
| Linux               | 1         | 1      | 3.57%   |
| LDLC                | 1         | 5      | 3.57%   |
| Intenso             | 1         | 1      | 3.57%   |
| Intel               | 1         | 1      | 3.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 35        | 39     | 35.71%  |
| NVMe    | 34        | 52     | 34.69%  |
| SSD     | 26        | 36     | 26.53%  |
| Unknown | 2         | 3      | 2.04%   |
| MMC     | 1         | 1      | 1.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 58        | 76     | 61.05%  |
| NVMe | 34        | 52     | 35.79%  |
| SAS  | 2         | 2      | 2.11%   |
| MMC  | 1         | 1      | 1.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 35        | 44     | 58.33%  |
| 0.51-1.0   | 21        | 26     | 35%     |
| 1.01-2.0   | 3         | 4      | 5%      |
| 4.01-10.0  | 1         | 1      | 1.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 24        | 27.27%  |
| 101-250        | 24        | 27.27%  |
| 501-1000       | 12        | 13.64%  |
| 1001-2000      | 10        | 11.36%  |
| 51-100         | 5         | 5.68%   |
| Unknown        | 5         | 5.68%   |
| More than 3000 | 4         | 4.55%   |
| 1-20           | 2         | 2.27%   |
| 21-50          | 1         | 1.14%   |
| 2001-3000      | 1         | 1.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 24        | 25.53%  |
| 101-250        | 18        | 19.15%  |
| 51-100         | 13        | 13.83%  |
| 21-50          | 11        | 11.7%   |
| 501-1000       | 10        | 10.64%  |
| 251-500        | 8         | 8.51%   |
| Unknown        | 5         | 5.32%   |
| 1001-2000      | 3         | 3.19%   |
| More than 3000 | 1         | 1.06%   |
| 2001-3000      | 1         | 1.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB          | 2         | 2      | 15.38%  |
| HGST HTS545050A7E680 500GB      | 2         | 2      | 15.38%  |
| WDC WD3200LPVT-00FMCT0 320GB    | 1         | 1      | 7.69%   |
| Toshiba MK5065GSX 500GB         | 1         | 1      | 7.69%   |
| Seagate ST500LT012-9WS142 500GB | 1         | 1      | 7.69%   |
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 7.69%   |
| Seagate ST1000LM035-1RK172 1TB  | 1         | 1      | 7.69%   |
| LDLC SSD 120GB                  | 1         | 3      | 7.69%   |
| Hitachi HTS547550A9E384 500GB   | 1         | 1      | 7.69%   |
| Hitachi HTS542516K9SA00 160GB   | 1         | 1      | 7.69%   |
| HGST HTS541010A9E680 1TB        | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 23.08%  |
| Seagate | 3         | 3      | 23.08%  |
| HGST    | 3         | 3      | 23.08%  |
| Hitachi | 2         | 2      | 15.38%  |
| WDC     | 1         | 1      | 7.69%   |
| LDLC    | 1         | 3      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 25%     |
| Seagate | 3         | 3      | 25%     |
| HGST    | 3         | 3      | 25%     |
| Hitachi | 2         | 2      | 16.67%  |
| WDC     | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 92.31%  |
| SSD  | 1         | 3      | 7.69%   |

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
| Works    | 46        | 58     | 49.46%  |
| Detected | 34        | 58     | 36.56%  |
| Malfunc  | 13        | 15     | 13.98%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 55        | 52.88%  |
| Samsung Electronics            | 17        | 16.35%  |
| AMD                            | 12        | 11.54%  |
| SanDisk                        | 5         | 4.81%   |
| SK hynix                       | 4         | 3.85%   |
| Phison Electronics             | 2         | 1.92%   |
| Kingston Technology Company    | 2         | 1.92%   |
| Union Memory (Shenzhen)        | 1         | 0.96%   |
| Toshiba America Info Systems   | 1         | 0.96%   |
| Solid State Storage Technology | 1         | 0.96%   |
| Nvidia                         | 1         | 0.96%   |
| Micron/Crucial Technology      | 1         | 0.96%   |
| Marvell Technology Group       | 1         | 0.96%   |
| Lite-On Technology             | 1         | 0.96%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 10.09%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 8         | 7.34%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 7.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 5.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 5.5%    |
| Samsung NVMe SSD Controller 980                                                | 4         | 3.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 3.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 3.67%   |
| SK hynix Non-Volatile memory controller                                        | 3         | 2.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 3         | 2.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 2.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 2.75%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 2.75%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 1.83%   |
| Samsung Electronics SATA controller                                            | 2         | 1.83%   |
| Phison E12 NVMe Controller                                                     | 2         | 1.83%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 1.83%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.83%   |
| Intel SSD 660P Series                                                          | 2         | 1.83%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 1.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.83%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.83%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 1.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 1.83%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.83%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.92%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 1         | 0.92%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.92%   |
| SK hynix BC511                                                                 | 1         | 0.92%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.92%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 0.92%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.92%   |
| Lite-On Non-Volatile memory controller                                         | 1         | 0.92%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 0.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 1         | 0.92%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 0.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.92%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 0.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.92%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 0.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 1         | 0.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 1         | 0.92%   |
| AMD 400 Series Chipset SATA Controller                                         | 1         | 0.92%   |
| AMD 300 Series Chipset SATA Controller                                         | 1         | 0.92%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 62        | 59.05%  |
| NVMe | 35        | 33.33%  |
| RAID | 8         | 7.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 71        | 83.53%  |
| AMD    | 14        | 16.47%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 7 4700U with Radeon Graphics      | 4         | 4.65%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 2         | 2.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 2.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 2.33%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 2.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.33%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 2.33%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 2.33%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 2.33%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 2         | 2.33%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 2.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 2.33%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 2.33%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz        | 1         | 1.16%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.16%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.16%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 1.16%   |
| Intel Pentium CPU A1018 @ 2.10GHz           | 1         | 1.16%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 1.16%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1.16%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 1         | 1.16%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 1.16%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.16%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.16%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.16%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.16%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.16%   |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 1.16%   |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 1.16%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.16%   |
| Intel Core i7-10850H CPU @ 2.70GHz          | 1         | 1.16%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.16%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.16%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 1         | 1.16%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 1.16%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.16%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 1.16%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 1.16%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 1.16%   |
| Intel Core i5-4258U CPU @ 2.40GHz           | 1         | 1.16%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 1         | 1.16%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 1.16%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 1.16%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 1.16%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 1         | 1.16%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 1.16%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 1         | 1.16%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 1         | 1.16%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 1.16%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 1         | 1.16%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 1.16%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 1         | 1.16%   |
| Intel Core 2 Duo CPU T9550 @ 2.66GHz        | 1         | 1.16%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 1         | 1.16%   |
| Intel Celeron N4100 CPU @ 1.10GHz           | 1         | 1.16%   |
| Intel Celeron N4000 CPU @ 1.10GHz           | 1         | 1.16%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 1         | 1.16%   |
| Intel Celeron CPU N2930 @ 1.83GHz           | 1         | 1.16%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 22        | 25.88%  |
| Intel Core i7           | 17        | 20%     |
| Intel Core i3           | 10        | 11.76%  |
| AMD Ryzen 7             | 7         | 8.24%   |
| Intel Celeron           | 6         | 7.06%   |
| Other                   | 4         | 4.71%   |
| Intel Pentium           | 3         | 3.53%   |
| Intel Core m3           | 2         | 2.35%   |
| Intel Core i9           | 2         | 2.35%   |
| AMD Ryzen 5             | 2         | 2.35%   |
| AMD Ryzen 3             | 2         | 2.35%   |
| Intel Xeon              | 1         | 1.18%   |
| Intel Pentium Silver    | 1         | 1.18%   |
| Intel Pentium Dual-Core | 1         | 1.18%   |
| Intel Core 2 Duo        | 1         | 1.18%   |
| Intel Atom              | 1         | 1.18%   |
| AMD Ryzen 9             | 1         | 1.18%   |
| AMD Ryzen 5 PRO         | 1         | 1.18%   |
| AMD A6                  | 1         | 1.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 41        | 48.24%  |
| 4      | 29        | 34.12%  |
| 8      | 9         | 10.59%  |
| 6      | 5         | 5.88%   |
| 12     | 1         | 1.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 85        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 66        | 77.65%  |
| 1      | 19        | 22.35%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 85        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 14        | 16.09%  |
| 0x306a9    | 6         | 6.9%    |
| 0x206a7    | 6         | 6.9%    |
| 0x806e9    | 5         | 5.75%   |
| 0x806ec    | 4         | 4.6%    |
| 0x806ea    | 4         | 4.6%    |
| 0x806c1    | 4         | 4.6%    |
| 0x40651    | 4         | 4.6%    |
| 0x306d4    | 4         | 4.6%    |
| 0xa0652    | 3         | 3.45%   |
| 0x906e9    | 3         | 3.45%   |
| 0x706e5    | 3         | 3.45%   |
| 0x706a1    | 3         | 3.45%   |
| 0x08600106 | 3         | 3.45%   |
| 0x906ea    | 2         | 2.3%    |
| 0x30678    | 2         | 2.3%    |
| 0x1067a    | 2         | 2.3%    |
| 0x08600103 | 2         | 2.3%    |
| 0x906ed    | 1         | 1.15%   |
| 0x806eb    | 1         | 1.15%   |
| 0x506c9    | 1         | 1.15%   |
| 0x406e3    | 1         | 1.15%   |
| 0x306c3    | 1         | 1.15%   |
| 0x20655    | 1         | 1.15%   |
| 0x08701013 | 1         | 1.15%   |
| 0x08600104 | 1         | 1.15%   |
| 0x08108102 | 1         | 1.15%   |
| 0x0810100b | 1         | 1.15%   |
| 0x08101007 | 1         | 1.15%   |
| 0x08001137 | 1         | 1.15%   |
| 0x0700010b | 1         | 1.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 25        | 29.41%  |
| Zen 2         | 8         | 9.41%   |
| IvyBridge     | 7         | 8.24%   |
| SandyBridge   | 6         | 7.06%   |
| Haswell       | 6         | 7.06%   |
| Broadwell     | 5         | 5.88%   |
| TigerLake     | 4         | 4.71%   |
| CometLake     | 4         | 4.71%   |
| Zen           | 3         | 3.53%   |
| IceLake       | 3         | 3.53%   |
| Goldmont plus | 3         | 3.53%   |
| Zen+          | 2         | 2.35%   |
| Silvermont    | 2         | 2.35%   |
| Penryn        | 2         | 2.35%   |
| Westmere      | 1         | 1.18%   |
| Skylake       | 1         | 1.18%   |
| Jaguar        | 1         | 1.18%   |
| Goldmont      | 1         | 1.18%   |
| Bonnell       | 1         | 1.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 64        | 61.54%  |
| Nvidia | 22        | 21.15%  |
| AMD    | 18        | 17.31%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                         | 6         | 5.77%   |
| AMD Renoir                                                                    | 6         | 5.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 5         | 4.81%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 5         | 4.81%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 4         | 3.85%   |
| Intel UHD Graphics 620                                                        | 4         | 3.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 4         | 3.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 4         | 3.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 3         | 2.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 3         | 2.88%   |
| Intel HD Graphics 5500                                                        | 3         | 2.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 2         | 1.92%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                              | 2         | 1.92%   |
| Nvidia GM108M [GeForce 840M]                                                  | 2         | 1.92%   |
| Intel UHD Graphics 615                                                        | 2         | 1.92%   |
| Intel HD Graphics 630                                                         | 2         | 1.92%   |
| Intel HD Graphics 6000                                                        | 2         | 1.92%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 1.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 2         | 1.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 1.92%   |
| AMD Saturn XT [FirePro M6100]                                                 | 2         | 1.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.96%   |
| Nvidia TU117M                                                                 | 1         | 0.96%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                       | 1         | 0.96%   |
| Nvidia GT218M [GeForce 310M]                                                  | 1         | 0.96%   |
| Nvidia GP108M [GeForce MX330]                                                 | 1         | 0.96%   |
| Nvidia GP108M [GeForce MX150]                                                 | 1         | 0.96%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                      | 1         | 0.96%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                         | 1         | 0.96%   |
| Nvidia GM107 [GeForce 940MX]                                                  | 1         | 0.96%   |
| Nvidia GK107M [GeForce GT 650M]                                               | 1         | 0.96%   |
| Nvidia GF119M [GeForce GT 520MX]                                              | 1         | 0.96%   |
| Nvidia GF108M [GeForce GT 520M]                                               | 1         | 0.96%   |
| Nvidia GF108GLM [NVS 5200M]                                                   | 1         | 0.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 1         | 0.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 1         | 0.96%   |
| Intel HD Graphics P630                                                        | 1         | 0.96%   |
| Intel HD Graphics 500                                                         | 1         | 0.96%   |
| Intel GeminiLake [UHD Graphics 605]                                           | 1         | 0.96%   |
| Intel Core Processor Integrated Graphics Controller                           | 1         | 0.96%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller               | 1         | 0.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 1         | 0.96%   |
| AMD Tahiti XT [Radeon HD 7970/8970 OEM / R9 280X]                             | 1         | 0.96%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 1         | 0.96%   |
| AMD RV635/M86 [Mobility Radeon HD 3650]                                       | 1         | 0.96%   |
| AMD Lexa XT [Radeon PRO WX 3100]                                              | 1         | 0.96%   |
| AMD Kabini [Radeon HD 8400 / R3 Series]                                       | 1         | 0.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 1         | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 46        | 53.49%  |
| Intel + Nvidia | 15        | 17.44%  |
| 1 x AMD        | 15        | 17.44%  |
| 1 x Nvidia     | 6         | 6.98%   |
| Intel + AMD    | 3         | 3.49%   |
| AMD + Nvidia   | 1         | 1.16%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 70        | 82.35%  |
| Proprietary | 15        | 17.65%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 57        | 66.28%  |
| 1.01-2.0   | 9         | 10.47%  |
| 0.01-0.5   | 8         | 9.3%    |
| 3.01-4.0   | 4         | 4.65%   |
| 0.51-1.0   | 4         | 4.65%   |
| 7.01-8.0   | 2         | 2.33%   |
| 5.01-6.0   | 1         | 1.16%   |
| 2.01-3.0   | 1         | 1.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 17        | 17.17%  |
| LG Display              | 16        | 16.16%  |
| BOE                     | 16        | 16.16%  |
| Chimei Innolux          | 12        | 12.12%  |
| Samsung Electronics     | 6         | 6.06%   |
| Dell                    | 4         | 4.04%   |
| Chi Mei Optoelectronics | 4         | 4.04%   |
| InfoVision              | 3         | 3.03%   |
| Apple                   | 3         | 3.03%   |
| Sharp                   | 2         | 2.02%   |
| Hewlett-Packard         | 2         | 2.02%   |
| Goldstar                | 2         | 2.02%   |
| BenQ                    | 2         | 2.02%   |
| ASUSTek Computer        | 2         | 2.02%   |
| Philips                 | 1         | 1.01%   |
| PANDA                   | 1         | 1.01%   |
| MSI                     | 1         | 1.01%   |
| LGD                     | 1         | 1.01%   |
| Lenovo                  | 1         | 1.01%   |
| KDC                     | 1         | 1.01%   |
| Ancor Communications    | 1         | 1.01%   |
| Acer                    | 1         | 1.01%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 3.03%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 2.02%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 2.02%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 2.02%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 2.02%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 2.02%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 2.02%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 2.02%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 2.02%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 2.02%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 1.01%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 1.01%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 1.01%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 340x190mm 15.3-inch         | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 1.01%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                   | 1         | 1.01%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                   | 1         | 1.01%   |
| MSI Optix MAG27C MSI1462 1920x1080 598x336mm 27.0-inch                    | 1         | 1.01%   |
| LGD LCD Monitor 1920x1080                                                 | 1         | 1.01%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch               | 1         | 1.01%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 1         | 1.01%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch              | 1         | 1.01%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch              | 1         | 1.01%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch              | 1         | 1.01%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch              | 1         | 1.01%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 1.01%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch              | 1         | 1.01%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch              | 1         | 1.01%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch               | 1         | 1.01%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch               | 1         | 1.01%   |
| LG Display LCD Monitor LGD03D3 1600x900 309x174mm 14.0-inch               | 1         | 1.01%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch               | 1         | 1.01%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch               | 1         | 1.01%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 1         | 1.01%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch              | 1         | 1.01%   |
| Lenovo LCD Monitor LEN4053 1680x1050 331x207mm 15.4-inch                  | 1         | 1.01%   |
| KDC LCD Monitor KDC0607 1366x768 309x174mm 14.0-inch                      | 1         | 1.01%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch              | 1         | 1.01%   |
| InfoVision LCD Monitor IVO057C 1366x768 309x174mm 14.0-inch               | 1         | 1.01%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch               | 1         | 1.01%   |
| Hewlett-Packard M24f FHD HPN3706 1920x1080 527x296mm 23.8-inch            | 1         | 1.01%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch              | 1         | 1.01%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 1         | 1.01%   |
| Goldstar 24EN33 GSM59D6 1920x1080 521x293mm 23.5-inch                     | 1         | 1.01%   |
| Dell P2720DC DELD0FB 2560x1440 597x336mm 27.0-inch                        | 1         | 1.01%   |
| Dell P2217H DELA0D9 1920x1080 476x267mm 21.5-inch                         | 1         | 1.01%   |
| Dell P1911 DELA074 1440x900 408x255mm 18.9-inch                           | 1         | 1.01%   |
| Dell E2310H DELD033 1920x1080 510x287mm 23.0-inch                         | 1         | 1.01%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch          | 1         | 1.01%   |
| Chimei Innolux LCD Monitor CMN175E 1920x1080 381x214mm 17.2-inch          | 1         | 1.01%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 1         | 1.01%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch           | 1         | 1.01%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch          | 1         | 1.01%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 1         | 1.01%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch          | 1         | 1.01%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 1         | 1.01%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 1         | 1.01%   |
| BOE LCD Monitor BOE0991 1920x1080 344x194mm 15.5-inch                     | 1         | 1.01%   |
| BOE LCD Monitor BOE0918 1920x1080 309x174mm 14.0-inch                     | 1         | 1.01%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 44        | 47.31%  |
| 1366x768 (WXGA)    | 30        | 32.26%  |
| 1440x900 (WXGA+)   | 4         | 4.3%    |
| 3840x2160 (4K)     | 3         | 3.23%   |
| 2560x1440 (QHD)    | 3         | 3.23%   |
| 1600x900 (HD+)     | 3         | 3.23%   |
| 2560x1600          | 2         | 2.15%   |
| 3440x1440          | 1         | 1.08%   |
| 2160x1440          | 1         | 1.08%   |
| 1920x1200 (WUXGA)  | 1         | 1.08%   |
| 1680x1050 (WSXGA+) | 1         | 1.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 39        | 39.8%   |
| 13      | 17        | 17.35%  |
| 14      | 14        | 14.29%  |
| 17      | 7         | 7.14%   |
| 24      | 5         | 5.1%    |
| 21      | 4         | 4.08%   |
| 27      | 3         | 3.06%   |
| 23      | 2         | 2.04%   |
| 11      | 2         | 2.04%   |
| 34      | 1         | 1.02%   |
| 20      | 1         | 1.02%   |
| 19      | 1         | 1.02%   |
| 12      | 1         | 1.02%   |
| Unknown | 1         | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 62        | 63.27%  |
| 501-600     | 9         | 9.18%   |
| 351-400     | 9         | 9.18%   |
| 201-300     | 9         | 9.18%   |
| 401-500     | 6         | 6.12%   |
| 701-800     | 1         | 1.02%   |
| 601-700     | 1         | 1.02%   |
| Unknown     | 1         | 1.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 74        | 87.06%  |
| 16/10   | 8         | 9.41%   |
| 3/2     | 1         | 1.18%   |
| 21/9    | 1         | 1.18%   |
| Unknown | 1         | 1.18%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 39        | 39.8%   |
| 81-90          | 25        | 25.51%  |
| 201-250        | 10        | 10.2%   |
| 71-80          | 6         | 6.12%   |
| 121-130        | 6         | 6.12%   |
| 301-350        | 3         | 3.06%   |
| 51-60          | 2         | 2.04%   |
| 151-200        | 2         | 2.04%   |
| 61-70          | 1         | 1.02%   |
| 351-500        | 1         | 1.02%   |
| 251-300        | 1         | 1.02%   |
| 131-140        | 1         | 1.02%   |
| Unknown        | 1         | 1.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 46        | 47.92%  |
| 101-120       | 28        | 29.17%  |
| 51-100        | 15        | 15.63%  |
| 161-240       | 5         | 5.21%   |
| More than 240 | 1         | 1.04%   |
| Unknown       | 1         | 1.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 72        | 82.76%  |
| 2     | 15        | 17.24%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 53        | 37.86%  |
| Intel                 | 47        | 33.57%  |
| Qualcomm Atheros      | 18        | 12.86%  |
| Broadcom              | 8         | 5.71%   |
| Broadcom Limited      | 4         | 2.86%   |
| Ralink                | 2         | 1.43%   |
| Xiaomi                | 1         | 0.71%   |
| Sierra Wireless       | 1         | 0.71%   |
| Ralink Technology     | 1         | 0.71%   |
| Qualcomm              | 1         | 0.71%   |
| OPPO Electronics      | 1         | 0.71%   |
| Linksys               | 1         | 0.71%   |
| Huawei Technologies   | 1         | 0.71%   |
| Apple                 | 1         | 0.71%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 19.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 6.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 3.64%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 3.03%   |
| Intel Wireless 8265 / 8275                                        | 5         | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.42%   |
| Intel Wireless 7265                                               | 4         | 2.42%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 2.42%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.82%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.82%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 1.21%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 1.21%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.21%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 1.21%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.21%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.61%   |
| Sierra Wireless MC7710                                            | 1         | 0.61%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.61%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.61%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.61%   |
| Realtek 802.11ac NIC                                              | 1         | 0.61%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.61%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1         | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.61%   |
| Qualcomm A0001                                                    | 1         | 0.61%   |
| OPPO Find X2 Lite                                                 | 1         | 0.61%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.61%   |
| Intel Wireless-AC 9260                                            | 1         | 0.61%   |
| Intel Wireless 7260                                               | 1         | 0.61%   |
| Intel Wireless 3165                                               | 1         | 0.61%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.61%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 0.61%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.61%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.61%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.61%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 0.61%   |
| Intel Centrino Wireless-N 2230                                    | 1         | 0.61%   |
| Intel Centrino Ultimate-N 6300                                    | 1         | 0.61%   |
| Intel Centrino Advanced-N 6235                                    | 1         | 0.61%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]              | 1         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 43        | 48.31%  |
| Realtek Semiconductor | 16        | 17.98%  |
| Qualcomm Atheros      | 15        | 16.85%  |
| Broadcom              | 7         | 7.87%   |
| Broadcom Limited      | 4         | 4.49%   |
| Ralink                | 2         | 2.25%   |
| Sierra Wireless       | 1         | 1.12%   |
| Ralink Technology     | 1         | 1.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 6         | 6.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 5.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 5.62%   |
| Intel Wireless 8265 / 8275                                     | 5         | 5.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 4.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 4.49%   |
| Intel Wireless 7265                                            | 4         | 4.49%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 4.49%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 3.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 3.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 3.37%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 3.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 3.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 2.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 2.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 2.25%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 2.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.25%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 2.25%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 2.25%   |
| Sierra Wireless MC7710                                         | 1         | 1.12%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.12%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.12%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 1.12%   |
| Realtek 802.11ac NIC                                           | 1         | 1.12%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.12%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.12%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1         | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.12%   |
| Intel Wireless-AC 9260                                         | 1         | 1.12%   |
| Intel Wireless 7260                                            | 1         | 1.12%   |
| Intel Wireless 3165                                            | 1         | 1.12%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.12%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 1.12%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.12%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 1.12%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]           | 1         | 1.12%   |
| Broadcom Limited BCM43142 802.11b/g/n                          | 1         | 1.12%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 47        | 63.51%  |
| Intel                 | 16        | 21.62%  |
| Qualcomm Atheros      | 4         | 5.41%   |
| Xiaomi                | 1         | 1.35%   |
| Qualcomm              | 1         | 1.35%   |
| OPPO Electronics      | 1         | 1.35%   |
| Linksys               | 1         | 1.35%   |
| Huawei Technologies   | 1         | 1.35%   |
| Broadcom              | 1         | 1.35%   |
| Apple                 | 1         | 1.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 42.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 13.16%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 7.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 7.89%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 3.95%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 2.63%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.32%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.32%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.32%   |
| Qualcomm A0001                                                    | 1         | 1.32%   |
| OPPO Find X2 Lite                                                 | 1         | 1.32%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 1.32%   |
| Intel WiMAX Connection 2400m                                      | 1         | 1.32%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.32%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.32%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.32%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.32%   |
| Huawei E353/E3131                                                 | 1         | 1.32%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.32%   |
| Apple iPad 4/Mini1                                                | 1         | 1.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 84        | 55.26%  |
| Ethernet | 68        | 44.74%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 68        | 79.07%  |
| Ethernet | 18        | 20.93%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 61        | 70.93%  |
| 1     | 22        | 25.58%  |
| 3     | 2         | 2.33%   |
| 0     | 1         | 1.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 78        | 88.64%  |
| Yes  | 10        | 11.36%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 51.47%  |
| Realtek Semiconductor           | 10        | 14.71%  |
| Broadcom                        | 5         | 7.35%   |
| Qualcomm Atheros Communications | 4         | 5.88%   |
| Lite-On Technology              | 4         | 5.88%   |
| Apple                           | 3         | 4.41%   |
| Realtek                         | 2         | 2.94%   |
| Foxconn / Hon Hai               | 2         | 2.94%   |
| Ralink                          | 1         | 1.47%   |
| IMC Networks                    | 1         | 1.47%   |
| Cambridge Silicon Radio         | 1         | 1.47%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 10        | 14.71%  |
| Intel Bluetooth Device                              | 10        | 14.71%  |
| Realtek Bluetooth Radio                             | 6         | 8.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 8.82%   |
| Intel AX200 Bluetooth                               | 6         | 8.82%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 4.41%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 4.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 4.41%   |
| Realtek Bluetooth Radio                             | 2         | 2.94%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 2.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.94%   |
| Apple Bluetooth USB Host Controller                 | 2         | 2.94%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.47%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.47%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.47%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.47%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.47%   |
| IMC Networks Bluetooth Device                       | 1         | 1.47%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.47%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.47%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.47%   |
| Apple Bluetooth Host Controller                     | 1         | 1.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 70        | 65.42%  |
| AMD                   | 16        | 14.95%  |
| Nvidia                | 14        | 13.08%  |
| C-Media Electronics   | 3         | 2.8%    |
| Realtek Semiconductor | 2         | 1.87%   |
| Plantronics           | 1         | 0.93%   |
| Corsair               | 1         | 0.93%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 13        | 9.85%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 8.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 5.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 4.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 3.79%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 3.79%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 3.79%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 3.79%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 3.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 3.03%   |
| Intel Comet Lake PCH cAVS                                                  | 4         | 3.03%   |
| Intel CM238 HD Audio Controller                                            | 4         | 3.03%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 3.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 3.03%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 2.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 2.27%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 2.27%   |
| Realtek Semiconductor USB Audio                                            | 2         | 1.52%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.52%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.52%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.52%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.52%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.52%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 1.52%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 2         | 1.52%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.76%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.76%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.76%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.76%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.76%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 1         | 0.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 1         | 0.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 1         | 0.76%   |
| Corsair HS45 Surround USB Sound Adapter                                    | 1         | 0.76%   |
| C-Media Electronics USB Audio Device                                       | 1         | 0.76%   |
| AMD Tahiti HDMI Audio [Radeon HD 7870 XT / 7950/7970]                      | 1         | 0.76%   |
| AMD Starship/Matisse HD Audio Controller                                   | 1         | 0.76%   |
| AMD Kabini HDMI/DP Audio                                                   | 1         | 0.76%   |
| AMD FCH Azalia Controller                                                  | 1         | 0.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 1         | 0.76%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 1         | 0.76%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 30%     |
| SK hynix            | 26        | 28.89%  |
| Micron Technology   | 7         | 7.78%   |
| Kingston            | 7         | 7.78%   |
| Unknown             | 4         | 4.44%   |
| Silicon Power       | 3         | 3.33%   |
| A-DATA Technology   | 3         | 3.33%   |
| Unknown (ABCD)      | 2         | 2.22%   |
| Ramaxel Technology  | 2         | 2.22%   |
| Corsair             | 2         | 2.22%   |
| Unknown             | 2         | 2.22%   |
| Team                | 1         | 1.11%   |
| Smart Brazil        | 1         | 1.11%   |
| Smart               | 1         | 1.11%   |
| Nanya Technology    | 1         | 1.11%   |
| ASint Technology    | 1         | 1.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 4         | 4.21%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 3.16%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 3.16%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 2.11%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 2.11%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 2.11%   |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 2.11%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 2         | 2.11%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 2         | 2.11%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s         | 2         | 2.11%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s                 | 2         | 2.11%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 2         | 2.11%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 2.11%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 2         | 2.11%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 2         | 2.11%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s           | 2         | 2.11%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 2.11%   |
| Unknown                                                             | 2         | 2.11%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 1.05%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                         | 1         | 1.05%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 1         | 1.05%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                    | 1         | 1.05%   |
| Team RAM TEAMGROUP-SD3-1600 4GB SODIMM DDR3 1600MT/s                | 1         | 1.05%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2400MT/s               | 1         | 1.05%   |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 2933MT/s     | 1         | 1.05%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.05%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.05%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 1.05%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.05%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 1.05%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 1.05%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s           | 1         | 1.05%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB Row Of Chips DDR4 3200MT/s     | 1         | 1.05%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 1.05%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 1.05%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 1.05%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 1         | 1.05%   |
| SK hynix RAM HCNNNBKMBLHR-NEE 1GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.05%   |
| Silicon Power RAM SP016GBSFU266B02 16GB SODIMM DDR4 2667MT/s        | 1         | 1.05%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 1         | 1.05%   |
| Samsung RAM M471B5273DM0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.05%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.05%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 1         | 1.05%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 1.05%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s           | 1         | 1.05%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.05%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 1.05%   |
| Samsung RAM K4E6E304EE-EGCE 4096MB 1600MT/s                         | 1         | 1.05%   |
| Samsung RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.05%   |
| Ramaxel RAM RMT3170EF68F9W1600 4096MB SODIMM DDR3 1600MT/s          | 1         | 1.05%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s             | 1         | 1.05%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                | 1         | 1.05%   |
| Micron RAM MT41K512M16TNA-125 4GB Chip DDR3 1600MT/s                | 1         | 1.05%   |
| Micron RAM Module 4GB SODIMM DDR4 2400MT/s                          | 1         | 1.05%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 1         | 1.05%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 1         | 1.05%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s               | 1         | 1.05%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 1         | 1.05%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16GB SODIMM DDR4 2400MT/s              | 1         | 1.05%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 39        | 52.7%   |
| DDR3    | 25        | 33.78%  |
| LPDDR4  | 4         | 5.41%   |
| LPDDR3  | 3         | 4.05%   |
| SDRAM   | 2         | 2.7%    |
| Unknown | 1         | 1.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 65        | 86.67%  |
| Row Of Chips | 7         | 9.33%   |
| DIMM         | 1         | 1.33%   |
| Chip         | 1         | 1.33%   |
| Unknown      | 1         | 1.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 34        | 40.48%  |
| 8192  | 25        | 29.76%  |
| 16384 | 12        | 14.29%  |
| 2048  | 10        | 11.9%   |
| 32768 | 2         | 2.38%   |
| 1024  | 1         | 1.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 25        | 31.65%  |
| 2667  | 15        | 18.99%  |
| 3200  | 14        | 17.72%  |
| 2400  | 10        | 12.66%  |
| 1333  | 4         | 5.06%   |
| 2133  | 3         | 3.8%    |
| 4199  | 2         | 2.53%   |
| 4267  | 1         | 1.27%   |
| 3400  | 1         | 1.27%   |
| 3266  | 1         | 1.27%   |
| 2933  | 1         | 1.27%   |
| 1334  | 1         | 1.27%   |
| 1066  | 1         | 1.27%   |

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
| Chicony Electronics                    | 18        | 24%     |
| Realtek Semiconductor                  | 9         | 12%     |
| Acer                                   | 9         | 12%     |
| Quanta                                 | 7         | 9.33%   |
| IMC Networks                           | 6         | 8%      |
| Suyin                                  | 5         | 6.67%   |
| Alcor Micro                            | 4         | 5.33%   |
| Syntek                                 | 3         | 4%      |
| Sunplus Innovation Technology          | 3         | 4%      |
| Silicon Motion                         | 2         | 2.67%   |
| Microdia                               | 2         | 2.67%   |
| Luxvisions Innotech Limited            | 2         | 2.67%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.67%   |
| Lite-On Technology                     | 1         | 1.33%   |
| LG Electronics                         | 1         | 1.33%   |
| Lenovo                                 | 1         | 1.33%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                 | 5         | 6.67%   |
| Chicony HD Webcam                                              | 5         | 6.67%   |
| Realtek Integrated_Webcam_HD                                   | 4         | 5.33%   |
| Chicony Integrated Camera                                      | 4         | 5.33%   |
| Acer Integrated Camera                                         | 3         | 4%      |
| Syntek EasyCamera                                              | 2         | 2.67%   |
| Suyin HP Webcam                                                | 2         | 2.67%   |
| Silicon Motion 300k Pixel Camera                               | 2         | 2.67%   |
| Realtek USB2.0 HD UVC WebCam                                   | 2         | 2.67%   |
| Realtek HD WebCam                                              | 2         | 2.67%   |
| Quanta HP Webcam                                               | 2         | 2.67%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 2.67%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 2.67%   |
| Chicony Integrated Camera (1280x720@30)                        | 2         | 2.67%   |
| Alcor Micro USB 2.0 Camera                                     | 2         | 2.67%   |
| Syntek Integrated Camera                                       | 1         | 1.33%   |
| Suyin USB Webcam                                               | 1         | 1.33%   |
| Suyin NEC HD WebCam                                            | 1         | 1.33%   |
| Suyin 1.3M HD WebCam                                           | 1         | 1.33%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.33%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 1.33%   |
| Sunplus HD WebCam                                              | 1         | 1.33%   |
| Realtek Integrated Webcam                                      | 1         | 1.33%   |
| Quanta VGA WebCam                                              | 1         | 1.33%   |
| Quanta USB2.0 VGA UVC WebCam                                   | 1         | 1.33%   |
| Quanta HD User Facing                                          | 1         | 1.33%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 1.33%   |
| Microdia Integrated Webcam                                     | 1         | 1.33%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 1.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 1.33%   |
| Lite-On HP HD Camera                                           | 1         | 1.33%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)          | 1         | 1.33%   |
| Lenovo UVC Camera                                              | 1         | 1.33%   |
| IMC Networks Integrated Webcam                                 | 1         | 1.33%   |
| Chicony USB2.0 Camera                                          | 1         | 1.33%   |
| Chicony USB2.0 0.3M UVC WebCam                                 | 1         | 1.33%   |
| Chicony Thinkpad T430 camera                                   | 1         | 1.33%   |
| Chicony LG Camera                                              | 1         | 1.33%   |
| Chicony Lenovo EasyCamera                                      | 1         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 1         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.33%   |
| Alcor Micro Lenovo EasyCamera                                  | 1         | 1.33%   |
| Alcor Micro Asus Integrated Webcam                             | 1         | 1.33%   |
| Acer Lenovo Integrated Webcam                                  | 1         | 1.33%   |
| Acer Lenovo EasyCamera                                         | 1         | 1.33%   |
| Acer Integrated 5M Camera                                      | 1         | 1.33%   |
| Acer HD Webcam                                                 | 1         | 1.33%   |
| Acer BisonCam,NB Pro                                           | 1         | 1.33%   |
| Acer BisonCam, NB Pro                                          | 1         | 1.33%   |

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
| Broadcom | 5         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 40%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |
| Broadcom 5880                                                                | 1         | 20%     |
| Broadcom 58200                                                               | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 59        | 67.82%  |
| 1     | 23        | 26.44%  |
| 2     | 5         | 5.75%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 7         | 20.59%  |
| Net/wireless             | 4         | 11.76%  |
| Multimedia controller    | 4         | 11.76%  |
| Graphics card            | 4         | 11.76%  |
| Chipcard                 | 4         | 11.76%  |
| Camera                   | 4         | 11.76%  |
| Storage                  | 2         | 5.88%   |
| Bluetooth                | 2         | 5.88%   |
| Network                  | 1         | 2.94%   |
| Dvb card                 | 1         | 2.94%   |
| Communication controller | 1         | 2.94%   |

