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

Total: 136

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Predator PH315-51           | [68f7384e7a](https://linux-hardware.org/?probe=68f7384e7a) | Sep 30, 2022 |
| Acer          | Aspire VN7-592G             | [cfc28181e5](https://linux-hardware.org/?probe=cfc28181e5) | Sep 25, 2022 |
| Notebook      | N141CU                      | [9a03ce91af](https://linux-hardware.org/?probe=9a03ce91af) | Sep 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | [a37633e1e2](https://linux-hardware.org/?probe=a37633e1e2) | Aug 24, 2022 |
| Dell          | Inspiron 5520               | [6b03bfc62e](https://linux-hardware.org/?probe=6b03bfc62e) | Aug 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3025bd4ded](https://linux-hardware.org/?probe=3025bd4ded) | Aug 05, 2022 |
| Dell          | Inspiron 3541               | [ab643dc6b0](https://linux-hardware.org/?probe=ab643dc6b0) | Jul 30, 2022 |
| Dell          | Latitude E7440              | [deea307e9b](https://linux-hardware.org/?probe=deea307e9b) | Jul 27, 2022 |
| Dell          | Latitude E7440              | [e2d8510882](https://linux-hardware.org/?probe=e2d8510882) | Jul 27, 2022 |
| Acer          | Aspire A315-23              | [304f750248](https://linux-hardware.org/?probe=304f750248) | Jul 08, 2022 |
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
| Artix Rolling  | 58        | 59.18%  |
| Artix          | 37        | 37.76%  |
| Artix 20220713 | 1         | 1.02%   |
| Artix 20201207 | 1         | 1.02%   |
| Artix 20201128 | 1         | 1.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Artix | 93        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.9.14-artix1-1                 | 6         | 5.31%   |
| 5.7.6-artix1-1                  | 3         | 2.65%   |
| 5.7.12-artix1-1                 | 2         | 1.77%   |
| 5.18.6-artix1-1                 | 2         | 1.77%   |
| 5.18.0-artix1-1                 | 2         | 1.77%   |
| 5.17.1-artix1-1                 | 2         | 1.77%   |
| 5.16.8-artix1-2                 | 2         | 1.77%   |
| 5.16.10-artix1-1                | 2         | 1.77%   |
| 5.15.12-artix1-1                | 2         | 1.77%   |
| 5.14.16-artix1-1                | 2         | 1.77%   |
| 5.13.8-artix1-1                 | 2         | 1.77%   |
| 5.12.8-artix1-1                 | 2         | 1.77%   |
| 5.12.12-zen1-1-zen              | 2         | 1.77%   |
| 5.12.12-artix1-1                | 2         | 1.77%   |
| 5.11.6-artix1-1                 | 2         | 1.77%   |
| 5.10.6-artix1-1                 | 2         | 1.77%   |
| 5.10.4-artix2-1                 | 2         | 1.77%   |
| 5.10.16-artix1-1                | 2         | 1.77%   |
| 5.9.6-artix1-1                  | 1         | 0.88%   |
| 5.9.14-zen1-1-zen               | 1         | 0.88%   |
| 5.9.12-artix1-1                 | 1         | 0.88%   |
| 5.9.1-artix1-1                  | 1         | 0.88%   |
| 5.9.0-zen1-1-zen                | 1         | 0.88%   |
| 5.9.0-1-mainline-bootsplash     | 1         | 0.88%   |
| 5.8.8-artix1-1                  | 1         | 0.88%   |
| 5.8.4-artix1-1                  | 1         | 0.88%   |
| 5.8.14-zen1-1-zen               | 1         | 0.88%   |
| 5.8.14-artix1-1                 | 1         | 0.88%   |
| 5.8.12-artix1-1                 | 1         | 0.88%   |
| 5.8.0-rc7-5-mainline-bootsplash | 1         | 0.88%   |
| 5.7.8-artix1-1                  | 1         | 0.88%   |
| 5.7.2-artix1-1                  | 1         | 0.88%   |
| 5.6.7-x86_64                    | 1         | 0.88%   |
| 5.5.3-artix1-1                  | 1         | 0.88%   |
| 5.5.10-artix1-1                 | 1         | 0.88%   |
| 5.4.74-1-lts                    | 1         | 0.88%   |
| 5.19.8-artix1-1                 | 1         | 0.88%   |
| 5.19.2-artix1-2                 | 1         | 0.88%   |
| 5.19.11-hardened1-1-hardened    | 1         | 0.88%   |
| 5.18.9-zen1-1-zen               | 1         | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.14  | 7         | 6.19%   |
| 5.12.12 | 4         | 3.54%   |
| 5.7.6   | 3         | 2.65%   |
| 5.17.1  | 3         | 2.65%   |
| 5.16.8  | 3         | 2.65%   |
| 5.15.12 | 3         | 2.65%   |
| 5.12.8  | 3         | 2.65%   |
| 5.9.0   | 2         | 1.77%   |
| 5.8.14  | 2         | 1.77%   |
| 5.7.12  | 2         | 1.77%   |
| 5.18.6  | 2         | 1.77%   |
| 5.18.0  | 2         | 1.77%   |
| 5.16.10 | 2         | 1.77%   |
| 5.14.16 | 2         | 1.77%   |
| 5.13.8  | 2         | 1.77%   |
| 5.12.14 | 2         | 1.77%   |
| 5.11.6  | 2         | 1.77%   |
| 5.10.6  | 2         | 1.77%   |
| 5.10.4  | 2         | 1.77%   |
| 5.10.16 | 2         | 1.77%   |
| 5.9.6   | 1         | 0.88%   |
| 5.9.12  | 1         | 0.88%   |
| 5.9.1   | 1         | 0.88%   |
| 5.8.8   | 1         | 0.88%   |
| 5.8.4   | 1         | 0.88%   |
| 5.8.12  | 1         | 0.88%   |
| 5.8.0   | 1         | 0.88%   |
| 5.7.8   | 1         | 0.88%   |
| 5.7.2   | 1         | 0.88%   |
| 5.6.7   | 1         | 0.88%   |
| 5.5.3   | 1         | 0.88%   |
| 5.5.10  | 1         | 0.88%   |
| 5.4.74  | 1         | 0.88%   |
| 5.19.8  | 1         | 0.88%   |
| 5.19.2  | 1         | 0.88%   |
| 5.19.11 | 1         | 0.88%   |
| 5.18.9  | 1         | 0.88%   |
| 5.18.5  | 1         | 0.88%   |
| 5.18.3  | 1         | 0.88%   |
| 5.18.16 | 1         | 0.88%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 12        | 11.21%  |
| 5.12    | 12        | 11.21%  |
| 5.9     | 11        | 10.28%  |
| 5.18    | 11        | 10.28%  |
| 5.10    | 11        | 10.28%  |
| 5.17    | 8         | 7.48%   |
| 5.16    | 8         | 7.48%   |
| 5.11    | 8         | 7.48%   |
| 5.7     | 6         | 5.61%   |
| 5.8     | 5         | 4.67%   |
| 5.14    | 4         | 3.74%   |
| 5.13    | 4         | 3.74%   |
| 5.19    | 3         | 2.8%    |
| 5.6     | 1         | 0.93%   |
| 5.5     | 1         | 0.93%   |
| 5.4     | 1         | 0.93%   |
| 4.19    | 1         | 0.93%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 93        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| KDE5           | 20        | 20.2%   |
| Unknown        | 17        | 17.17%  |
| XFCE           | 16        | 16.16%  |
| GNOME          | 14        | 14.14%  |
| X-Cinnamon     | 7         | 7.07%   |
| MATE           | 4         | 4.04%   |
| LXQt           | 4         | 4.04%   |
| KDE            | 4         | 4.04%   |
| Cinnamon       | 3         | 3.03%   |
| bspwm          | 2         | 2.02%   |
| xmonad         | 1         | 1.01%   |
| sway-dbus      | 1         | 1.01%   |
| Sway           | 1         | 1.01%   |
| nxde           | 1         | 1.01%   |
| LXDE           | 1         | 1.01%   |
| i3             | 1         | 1.01%   |
| awesomeminimal | 1         | 1.01%   |
| awesome        | 1         | 1.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 67        | 68.37%  |
| Tty     | 14        | 14.29%  |
| Wayland | 11        | 11.22%  |
| Unknown | 6         | 6.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 34        | 35.79%  |
| LightDM | 30        | 31.58%  |
| SDDM    | 26        | 27.37%  |
| XDM     | 1         | 1.05%   |
| SLiM    | 1         | 1.05%   |
| Ly      | 1         | 1.05%   |
| LXDM    | 1         | 1.05%   |
| GDM     | 1         | 1.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 48        | 48.98%  |
| Unknown | 12        | 12.24%  |
| ru_RU   | 8         | 8.16%   |
| en_GB   | 7         | 7.14%   |
| C       | 4         | 4.08%   |
| fr_FR   | 3         | 3.06%   |
| es_ES   | 2         | 2.04%   |
| en_CA   | 2         | 2.04%   |
| uk_UA   | 1         | 1.02%   |
| pt_PT   | 1         | 1.02%   |
| pt_BR   | 1         | 1.02%   |
| pl_PL   | 1         | 1.02%   |
| it_IT   | 1         | 1.02%   |
| es_GT   | 1         | 1.02%   |
| en_IN   | 1         | 1.02%   |
| en_AU   | 1         | 1.02%   |
| en_AG   | 1         | 1.02%   |
| el_GR   | 1         | 1.02%   |
| de_DE   | 1         | 1.02%   |
| cs_CZ   | 1         | 1.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 70        | 74.47%  |
| BIOS | 24        | 25.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 69        | 73.4%   |
| Btrfs   | 20        | 21.28%  |
| Xfs     | 3         | 3.19%   |
| Overlay | 1         | 1.06%   |
| F2fs    | 1         | 1.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 68        | 72.34%  |
| MBR     | 13        | 13.83%  |
| Unknown | 13        | 13.83%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 79        | 84.04%  |
| Yes       | 15        | 15.96%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 69        | 74.19%  |
| Yes       | 24        | 25.81%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 25        | 26.88%  |
| Hewlett-Packard     | 14        | 15.05%  |
| Dell                | 14        | 15.05%  |
| Acer                | 12        | 12.9%   |
| ASUSTek Computer    | 9         | 9.68%   |
| Apple               | 3         | 3.23%   |
| Timi                | 2         | 2.15%   |
| Notebook            | 2         | 2.15%   |
| MSI                 | 2         | 2.15%   |
| GPD                 | 2         | 2.15%   |
| Gigabyte Technology | 2         | 2.15%   |
| UNOWHY              | 1         | 1.08%   |
| Quanta              | 1         | 1.08%   |
| MOTILE              | 1         | 1.08%   |
| LG Electronics      | 1         | 1.08%   |
| HUAWEI              | 1         | 1.08%   |
| AXIOO               | 1         | 1.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Timi RedmiBook 14 II                   | 2         | 2.15%   |
| Lenovo IdeaPad 5 15IIL05 81YK          | 2         | 2.15%   |
| HP 15                                  | 2         | 2.15%   |
| GPD P2 MAX                             | 2         | 2.15%   |
| Dell Precision M6600                   | 2         | 2.15%   |
| Dell Precision 7550                    | 2         | 2.15%   |
| Apple MacBookAir7,2                    | 2         | 2.15%   |
| UNOWHY Y13G010S4EI                     | 1         | 1.08%   |
| Quanta SWH                             | 1         | 1.08%   |
| Notebook N141CU                        | 1         | 1.08%   |
| Notebook N130BU                        | 1         | 1.08%   |
| MSI Modern 15 A11M                     | 1         | 1.08%   |
| MSI GP72 7RDX                          | 1         | 1.08%   |
| MOTILE M141                            | 1         | 1.08%   |
| LG 17Z990-R.AAC9U1                     | 1         | 1.08%   |
| Lenovo ThinkPad W500 4063CJ5           | 1         | 1.08%   |
| Lenovo ThinkPad T480s 20L8S3D400       | 1         | 1.08%   |
| Lenovo ThinkPad T480 MFG_IN_GO         | 1         | 1.08%   |
| Lenovo ThinkPad T440s 20ARS0MV00       | 1         | 1.08%   |
| Lenovo ThinkPad T430 2350BC6           | 1         | 1.08%   |
| Lenovo ThinkPad T430 2347H76           | 1         | 1.08%   |
| Lenovo ThinkPad T420 4236H45           | 1         | 1.08%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00   | 1         | 1.08%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800   | 1         | 1.08%   |
| Lenovo ThinkPad P1 Gen 3 20TH001EMH    | 1         | 1.08%   |
| Lenovo ThinkPad E14 Gen 2 20T6000MCK   | 1         | 1.08%   |
| Lenovo ThinkPad 11e 5th Gen 20LNS0P500 | 1         | 1.08%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 1         | 1.08%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 1.08%   |
| Lenovo LaVie Z 20FF0012US              | 1         | 1.08%   |
| Lenovo IdeaPad Y500 20193              | 1         | 1.08%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL  | 1         | 1.08%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG   | 1         | 1.08%   |
| Lenovo IdeaPad 510-15IKB 80SV          | 1         | 1.08%   |
| Lenovo IdeaPad 330-15IKB 81DE          | 1         | 1.08%   |
| Lenovo G400s 20244                     | 1         | 1.08%   |
| Lenovo B590 20206                      | 1         | 1.08%   |
| Lenovo B570e HuronRiver Platform       | 1         | 1.08%   |
| HUAWEI WRT-WX9                         | 1         | 1.08%   |
| HP ProBook 450 G6                      | 1         | 1.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 12        | 12.9%   |
| Acer Aspire        | 8         | 8.6%    |
| Lenovo IdeaPad     | 7         | 7.53%   |
| Dell Precision     | 6         | 6.45%   |
| HP Laptop          | 5         | 5.38%   |
| Dell Latitude      | 4         | 4.3%    |
| Dell Inspiron      | 4         | 4.3%    |
| HP 250             | 3         | 3.23%   |
| Timi RedmiBook     | 2         | 2.15%   |
| HP 15              | 2         | 2.15%   |
| GPD P2             | 2         | 2.15%   |
| Apple MacBookAir7  | 2         | 2.15%   |
| Acer Nitro         | 2         | 2.15%   |
| UNOWHY Y13G010S4EI | 1         | 1.08%   |
| Quanta SWH         | 1         | 1.08%   |
| Notebook N141CU    | 1         | 1.08%   |
| Notebook N130BU    | 1         | 1.08%   |
| MSI Modern         | 1         | 1.08%   |
| MSI GP72           | 1         | 1.08%   |
| MOTILE M141        | 1         | 1.08%   |
| LG 17Z990-R.AAC9U1 | 1         | 1.08%   |
| Lenovo ThinkBook   | 1         | 1.08%   |
| Lenovo Legion      | 1         | 1.08%   |
| Lenovo LaVie       | 1         | 1.08%   |
| Lenovo G400s       | 1         | 1.08%   |
| Lenovo B590        | 1         | 1.08%   |
| Lenovo B570e       | 1         | 1.08%   |
| HUAWEI WRT-WX9     | 1         | 1.08%   |
| HP ProBook         | 1         | 1.08%   |
| HP OMEN            | 1         | 1.08%   |
| HP 255             | 1         | 1.08%   |
| HP 246             | 1         | 1.08%   |
| Gigabyte B450M     | 1         | 1.08%   |
| Gigabyte AERO      | 1         | 1.08%   |
| AXIOO Mybook       | 1         | 1.08%   |
| ASUS X553MA        | 1         | 1.08%   |
| ASUS VivoBook      | 1         | 1.08%   |
| ASUS K53SC         | 1         | 1.08%   |
| ASUS K50IE         | 1         | 1.08%   |
| ASUS GX501VIK      | 1         | 1.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 22        | 23.66%  |
| 2018 | 12        | 12.9%   |
| 2019 | 10        | 10.75%  |
| 2017 | 8         | 8.6%    |
| 2014 | 7         | 7.53%   |
| 2012 | 7         | 7.53%   |
| 2011 | 7         | 7.53%   |
| 2013 | 6         | 6.45%   |
| 2015 | 5         | 5.38%   |
| 2016 | 4         | 4.3%    |
| 2021 | 3         | 3.23%   |
| 2010 | 1         | 1.08%   |
| 2009 | 1         | 1.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 93        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 92        | 98.92%  |
| Enabled  | 1         | 1.08%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 93        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 26        | 27.66%  |
| 8.01-16.0   | 23        | 24.47%  |
| 16.01-24.0  | 17        | 18.09%  |
| 3.01-4.0    | 15        | 15.96%  |
| 32.01-64.0  | 4         | 4.26%   |
| 1.01-2.0    | 4         | 4.26%   |
| 64.01-256.0 | 3         | 3.19%   |
| 24.01-32.0  | 2         | 2.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 30        | 28.04%  |
| 2.01-3.0   | 24        | 22.43%  |
| 4.01-8.0   | 23        | 21.5%   |
| 3.01-4.0   | 14        | 13.08%  |
| 0.51-1.0   | 9         | 8.41%   |
| 8.01-16.0  | 4         | 3.74%   |
| 0.01-0.5   | 2         | 1.87%   |
| 16.01-24.0 | 1         | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 72        | 76.6%   |
| 2      | 21        | 22.34%  |
| 3      | 1         | 1.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 70        | 75.27%  |
| Yes       | 23        | 24.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 74        | 79.57%  |
| No        | 19        | 20.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 91        | 97.85%  |
| No        | 2         | 2.15%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 75        | 78.95%  |
| No        | 20        | 21.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 21        | 22.58%  |
| Russia      | 9         | 9.68%   |
| India       | 5         | 5.38%   |
| Brazil      | 5         | 5.38%   |
| UK          | 4         | 4.3%    |
| Turkey      | 4         | 4.3%    |
| Indonesia   | 4         | 4.3%    |
| Germany     | 4         | 4.3%    |
| Canada      | 4         | 4.3%    |
| Ukraine     | 3         | 3.23%   |
| Netherlands | 3         | 3.23%   |
| France      | 3         | 3.23%   |
| Switzerland | 2         | 2.15%   |
| Spain       | 2         | 2.15%   |
| Poland      | 2         | 2.15%   |
| Czechia     | 2         | 2.15%   |
| Bulgaria    | 2         | 2.15%   |
| Uzbekistan  | 1         | 1.08%   |
| Sweden      | 1         | 1.08%   |
| Romania     | 1         | 1.08%   |
| Lithuania   | 1         | 1.08%   |
| Italy       | 1         | 1.08%   |
| Guatemala   | 1         | 1.08%   |
| Greece      | 1         | 1.08%   |
| China       | 1         | 1.08%   |
| Chile       | 1         | 1.08%   |
| Bangladesh  | 1         | 1.08%   |
| Azerbaijan  | 1         | 1.08%   |
| Australia   | 1         | 1.08%   |
| Argentina   | 1         | 1.08%   |
| Algeria     | 1         | 1.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 3         | 3.03%   |
| Jakarta           | 3         | 3.03%   |
| St Petersburg     | 2         | 2.02%   |
| San Ramon         | 2         | 2.02%   |
| Samara            | 2         | 2.02%   |
| Rio de Janeiro    | 2         | 2.02%   |
| Prague            | 2         | 2.02%   |
| Omaha             | 2         | 2.02%   |
| Neuchatel         | 2         | 2.02%   |
| Los Angeles       | 2         | 2.02%   |
| Frankfurt am Main | 2         | 2.02%   |
| Dnipro            | 2         | 2.02%   |
| Amsterdam         | 2         | 2.02%   |
| Zaporizhzhya      | 1         | 1.01%   |
| Wigan             | 1         | 1.01%   |
| Wem               | 1         | 1.01%   |
| Vilnius           | 1         | 1.01%   |
| Varna             | 1         | 1.01%   |
| Vancouver         | 1         | 1.01%   |
| Toronto           | 1         | 1.01%   |
| Timișoara        | 1         | 1.01%   |
| Tashkent          | 1         | 1.01%   |
| Syeverodonets'k   | 1         | 1.01%   |
| Surgut            | 1         | 1.01%   |
| Stuttgart         | 1         | 1.01%   |
| Stockholm         | 1         | 1.01%   |
| Sofia             | 1         | 1.01%   |
| Snohomish         | 1         | 1.01%   |
| Skikda            | 1         | 1.01%   |
| Sigogne           | 1         | 1.01%   |
| Seville           | 1         | 1.01%   |
| Semarang          | 1         | 1.01%   |
| Seattle           | 1         | 1.01%   |
| Santiago          | 1         | 1.01%   |
| Santa Fe          | 1         | 1.01%   |
| Sainte-Severe     | 1         | 1.01%   |
| Quincy            | 1         | 1.01%   |
| Puducherry        | 1         | 1.01%   |
| Ordu              | 1         | 1.01%   |
| Omsk              | 1         | 1.01%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 24        | 31     | 20.87%  |
| Seagate                   | 14        | 14     | 12.17%  |
| WDC                       | 9         | 12     | 7.83%   |
| Toshiba                   | 9         | 9      | 7.83%   |
| SanDisk                   | 6         | 6      | 5.22%   |
| Intel                     | 6         | 8      | 5.22%   |
| HGST                      | 6         | 6      | 5.22%   |
| SK hynix                  | 5         | 11     | 4.35%   |
| Kingston                  | 5         | 6      | 4.35%   |
| Hitachi                   | 4         | 5      | 3.48%   |
| China                     | 4         | 4      | 3.48%   |
| Apple                     | 3         | 4      | 2.61%   |
| Unknown                   | 2         | 2      | 1.74%   |
| Phison Electronics        | 2         | 3      | 1.74%   |
| Crucial                   | 2         | 2      | 1.74%   |
| Timetec                   | 1         | 2      | 0.87%   |
| SPCC                      | 1         | 1      | 0.87%   |
| Solid State Storage       | 1         | 1      | 0.87%   |
| PNY                       | 1         | 1      | 0.87%   |
| Patriot                   | 1         | 1      | 0.87%   |
| Micron/Crucial Technology | 1         | 1      | 0.87%   |
| Micron Technology         | 1         | 1      | 0.87%   |
| LITEON                    | 1         | 1      | 0.87%   |
| Lite-On                   | 1         | 1      | 0.87%   |
| Linux                     | 1         | 1      | 0.87%   |
| LDLC                      | 1         | 5      | 0.87%   |
| Intenso                   | 1         | 1      | 0.87%   |
| A-DATA Technology         | 1         | 1      | 0.87%   |
| Unknown                   | 1         | 1      | 0.87%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| SanDisk NVMe SSD Drive 512GB              | 4         | 3.31%   |
| Seagate ST1000LM035-1RK172 1TB            | 3         | 2.48%   |
| China SATA SSD 960GB                      | 3         | 2.48%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 2         | 1.65%   |
| Toshiba MQ04ABF100 1TB                    | 2         | 1.65%   |
| Toshiba MQ01ABF050 500GB                  | 2         | 1.65%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 1.65%   |
| Seagate ST500LT012-1DG142 500GB           | 2         | 1.65%   |
| Samsung NVMe SSD Drive 1TB                | 2         | 1.65%   |
| Samsung MZNLH512HALU-00000 512GB SSD      | 2         | 1.65%   |
| Phison PCIe SSD 240GB                     | 2         | 1.65%   |
| HGST HTS545050A7E680 500GB                | 2         | 1.65%   |
| Apple SSD SM0256G 256GB                   | 2         | 1.65%   |
| WDC WDS240G2G0A-00JH30 240GB SSD          | 1         | 0.83%   |
| WDC WDS200T2B0B-00YS70 2TB SSD            | 1         | 0.83%   |
| WDC WD5000LPVX-75V0TT0 500GB              | 1         | 0.83%   |
| WDC WD5000BPVT-22HXZT3 500GB              | 1         | 0.83%   |
| WDC WD3200LPVT-00FMCT0 320GB              | 1         | 0.83%   |
| WDC WD10SPZX-60Z10T0 1TB                  | 1         | 0.83%   |
| WDC WD10SPZX-21Z10T0 1TB                  | 1         | 0.83%   |
| Unknown SD/MMC/MS PRO 2GB                 | 1         | 0.83%   |
| Unknown DA4064  64GB                      | 1         | 0.83%   |
| Toshiba THNSNH128GMCT 128GB SSD           | 1         | 0.83%   |
| Toshiba MK5065GSX 500GB                   | 1         | 0.83%   |
| Toshiba KBG30ZMT256G 256GB                | 1         | 0.83%   |
| Timetec 35TTM8SSATA-512GB                 | 1         | 0.83%   |
| SPCC Solid State Disk 256GB               | 1         | 0.83%   |
| Solid State Storage SSSTC CL1-4D256 256GB | 1         | 0.83%   |
| SK hynix SKHynix_HFS512GD9TNI-L2B0B 512GB | 1         | 0.83%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB | 1         | 0.83%   |
| SK hynix SC311 SATA 256GB SSD             | 1         | 0.83%   |
| SK hynix NVMe SSD Drive 1TB               | 1         | 0.83%   |
| SK hynix NVMe SSD Drive 1024GB            | 1         | 0.83%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB   | 1         | 0.83%   |
| Seagate ST9500420AS 500GB                 | 1         | 0.83%   |
| Seagate ST9500325AS 500GB                 | 1         | 0.83%   |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 0.83%   |
| Seagate ST500LT012-9WS142 500GB           | 1         | 0.83%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 0.83%   |
| Seagate ST2000LM015-2E8174 2TB            | 1         | 0.83%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 14     | 35.9%   |
| WDC     | 7         | 9      | 17.95%  |
| Toshiba | 7         | 7      | 17.95%  |
| HGST    | 6         | 6      | 15.38%  |
| Hitachi | 4         | 5      | 10.26%  |
| Unknown | 1         | 1      | 2.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 11     | 27.27%  |
| China               | 4         | 4      | 12.12%  |
| Kingston            | 3         | 3      | 9.09%   |
| Apple               | 3         | 4      | 9.09%   |
| WDC                 | 2         | 3      | 6.06%   |
| Crucial             | 2         | 2      | 6.06%   |
| Toshiba             | 1         | 1      | 3.03%   |
| SPCC                | 1         | 1      | 3.03%   |
| SK hynix            | 1         | 1      | 3.03%   |
| SanDisk             | 1         | 1      | 3.03%   |
| PNY                 | 1         | 1      | 3.03%   |
| Patriot             | 1         | 1      | 3.03%   |
| Linux               | 1         | 1      | 3.03%   |
| LDLC                | 1         | 5      | 3.03%   |
| Intenso             | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 38        | 42     | 35.19%  |
| NVMe    | 36        | 55     | 33.33%  |
| SSD     | 31        | 41     | 28.7%   |
| Unknown | 2         | 3      | 1.85%   |
| MMC     | 1         | 1      | 0.93%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 64        | 84     | 62.14%  |
| NVMe | 36        | 55     | 34.95%  |
| SAS  | 2         | 2      | 1.94%   |
| MMC  | 1         | 1      | 0.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 50     | 59.7%   |
| 0.51-1.0   | 23        | 28     | 34.33%  |
| 1.01-2.0   | 3         | 4      | 4.48%   |
| 3.01-4.0   | 1         | 1      | 1.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 27        | 28.13%  |
| 251-500        | 26        | 27.08%  |
| 501-1000       | 13        | 13.54%  |
| 1001-2000      | 11        | 11.46%  |
| 51-100         | 5         | 5.21%   |
| Unknown        | 5         | 5.21%   |
| More than 3000 | 4         | 4.17%   |
| 1-20           | 3         | 3.13%   |
| 21-50          | 1         | 1.04%   |
| 2001-3000      | 1         | 1.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 28        | 27.18%  |
| 101-250        | 19        | 18.45%  |
| 51-100         | 14        | 13.59%  |
| 251-500        | 11        | 10.68%  |
| 21-50          | 11        | 10.68%  |
| 501-1000       | 10        | 9.71%   |
| Unknown        | 5         | 4.85%   |
| 1001-2000      | 3         | 2.91%   |
| More than 3000 | 1         | 0.97%   |
| 2001-3000      | 1         | 0.97%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 14.29%  |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 14.29%  |
| WDC WD3200LPVT-00FMCT0 320GB                     | 1         | 1      | 7.14%   |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 7.14%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 7.14%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 7.14%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 7.14%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 7.14%   |
| LDLC SSD 120GB                                   | 1         | 3      | 7.14%   |
| Hitachi HTS547550A9E384 500GB                    | 1         | 1      | 7.14%   |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 7.14%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 3         | 3      | 21.43%  |
| Seagate             | 3         | 3      | 21.43%  |
| HGST                | 3         | 3      | 21.43%  |
| Hitachi             | 2         | 2      | 14.29%  |
| WDC                 | 1         | 1      | 7.14%   |
| Samsung Electronics | 1         | 1      | 7.14%   |
| LDLC                | 1         | 3      | 7.14%   |

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
| HDD  | 12        | 12     | 85.71%  |
| SSD  | 2         | 4      | 14.29%  |

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
| Works    | 49        | 62     | 48.51%  |
| Detected | 38        | 64     | 37.62%  |
| Malfunc  | 14        | 16     | 13.86%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 60        | 52.63%  |
| Samsung Electronics            | 17        | 14.91%  |
| AMD                            | 15        | 13.16%  |
| SanDisk                        | 5         | 4.39%   |
| SK hynix                       | 4         | 3.51%   |
| Phison Electronics             | 2         | 1.75%   |
| Kingston Technology Company    | 2         | 1.75%   |
| Union Memory (Shenzhen)        | 1         | 0.88%   |
| Toshiba America Info Systems   | 1         | 0.88%   |
| Solid State Storage Technology | 1         | 0.88%   |
| Nvidia                         | 1         | 0.88%   |
| Micron/Crucial Technology      | 1         | 0.88%   |
| Micron Technology              | 1         | 0.88%   |
| Marvell Technology Group       | 1         | 0.88%   |
| Lite-On Technology             | 1         | 0.88%   |
| ADATA Technology               | 1         | 0.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 14        | 11.76%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 8         | 6.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 8         | 6.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 8         | 6.72%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 7         | 5.88%   |
| Samsung NVMe SSD Controller 980                                               | 4         | 3.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 4         | 3.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 4         | 3.36%   |
| SK hynix Non-Volatile memory controller                                       | 3         | 2.52%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 3         | 2.52%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 3         | 2.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 3         | 2.52%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 3         | 2.52%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 3         | 2.52%   |
| SanDisk Non-Volatile memory controller                                        | 2         | 1.68%   |
| Samsung Electronics SATA controller                                           | 2         | 1.68%   |
| Phison E12 NVMe Controller                                                    | 2         | 1.68%   |
| Kingston Company Company Non-Volatile memory controller                       | 2         | 1.68%   |
| Intel Volume Management Device NVMe RAID Controller                           | 2         | 1.68%   |
| Intel SSD 660P Series                                                         | 2         | 1.68%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 2         | 1.68%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 1.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 1.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 2         | 1.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 2         | 1.68%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                        | 1         | 0.84%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                          | 1         | 0.84%   |
| Solid State Storage Non-Volatile memory controller                            | 1         | 0.84%   |
| SK hynix BC511                                                                | 1         | 0.84%   |
| Nvidia MCP79 AHCI Controller                                                  | 1         | 0.84%   |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 1         | 0.84%   |
| Micron Non-Volatile memory controller                                         | 1         | 0.84%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                    | 1         | 0.84%   |
| Lite-On Non-Volatile memory controller                                        | 1         | 0.84%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 0.84%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 0.84%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1         | 0.84%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 0.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1         | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 68        | 59.13%  |
| NVMe | 37        | 32.17%  |
| RAID | 10        | 8.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 76        | 81.72%  |
| AMD    | 17        | 18.28%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 7 4700U with Radeon Graphics      | 4         | 4.26%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 2         | 2.13%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 2.13%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 2.13%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 2.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.13%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 2.13%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 2.13%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 2.13%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 2         | 2.13%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 2.13%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 2.13%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 2.13%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz        | 1         | 1.06%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.06%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.06%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 1.06%   |
| Intel Pentium CPU A1018 @ 2.10GHz           | 1         | 1.06%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 1.06%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1.06%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 1         | 1.06%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 1.06%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.06%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.06%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.06%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.06%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.06%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.06%   |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 1.06%   |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 1.06%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.06%   |
| Intel Core i7-10870H CPU @ 2.20GHz          | 1         | 1.06%   |
| Intel Core i7-10850H CPU @ 2.70GHz          | 1         | 1.06%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 1.06%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.06%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 1         | 1.06%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 1.06%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.06%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.06%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 1.06%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 25        | 26.88%  |
| Intel Core i7           | 19        | 20.43%  |
| Intel Core i3           | 10        | 10.75%  |
| AMD Ryzen 7             | 8         | 8.6%    |
| Intel Celeron           | 6         | 6.45%   |
| Other                   | 4         | 4.3%    |
| Intel Pentium           | 3         | 3.23%   |
| Intel Core m3           | 2         | 2.15%   |
| Intel Core i9           | 2         | 2.15%   |
| AMD Ryzen 5             | 2         | 2.15%   |
| AMD Ryzen 3             | 2         | 2.15%   |
| Intel Xeon              | 1         | 1.08%   |
| Intel Pentium Silver    | 1         | 1.08%   |
| Intel Pentium Dual-Core | 1         | 1.08%   |
| Intel Core 2 Duo        | 1         | 1.08%   |
| Intel Atom              | 1         | 1.08%   |
| AMD Ryzen 9             | 1         | 1.08%   |
| AMD Ryzen 5 PRO         | 1         | 1.08%   |
| AMD E1                  | 1         | 1.08%   |
| AMD Athlon              | 1         | 1.08%   |
| AMD A6                  | 1         | 1.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 45        | 48.39%  |
| 4      | 31        | 33.33%  |
| 8      | 10        | 10.75%  |
| 6      | 6         | 6.45%   |
| 12     | 1         | 1.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 93        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 72        | 77.42%  |
| 1      | 21        | 22.58%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 93        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 15        | 15.79%  |
| 0x306a9    | 7         | 7.37%   |
| 0x206a7    | 6         | 6.32%   |
| 0x806e9    | 5         | 5.26%   |
| 0x40651    | 5         | 5.26%   |
| 0xa0652    | 4         | 4.21%   |
| 0x806ec    | 4         | 4.21%   |
| 0x806ea    | 4         | 4.21%   |
| 0x806c1    | 4         | 4.21%   |
| 0x306d4    | 4         | 4.21%   |
| 0x906ea    | 3         | 3.16%   |
| 0x906e9    | 3         | 3.16%   |
| 0x706e5    | 3         | 3.16%   |
| 0x706a1    | 3         | 3.16%   |
| 0x08600106 | 3         | 3.16%   |
| 0x30678    | 2         | 2.11%   |
| 0x1067a    | 2         | 2.11%   |
| 0x08600103 | 2         | 2.11%   |
| 0x08108109 | 2         | 2.11%   |
| 0x906ed    | 1         | 1.05%   |
| 0x806eb    | 1         | 1.05%   |
| 0x506e3    | 1         | 1.05%   |
| 0x506c9    | 1         | 1.05%   |
| 0x406e3    | 1         | 1.05%   |
| 0x306c3    | 1         | 1.05%   |
| 0x20655    | 1         | 1.05%   |
| 0x08701013 | 1         | 1.05%   |
| 0x08600104 | 1         | 1.05%   |
| 0x08108102 | 1         | 1.05%   |
| 0x0810100b | 1         | 1.05%   |
| 0x08101007 | 1         | 1.05%   |
| 0x08001137 | 1         | 1.05%   |
| 0x0700010b | 1         | 1.05%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 26        | 27.96%  |
| Zen 2         | 8         | 8.6%    |
| IvyBridge     | 8         | 8.6%    |
| Haswell       | 7         | 7.53%   |
| SandyBridge   | 6         | 6.45%   |
| CometLake     | 5         | 5.38%   |
| Broadwell     | 5         | 5.38%   |
| Zen+          | 4         | 4.3%    |
| TigerLake     | 4         | 4.3%    |
| Zen           | 3         | 3.23%   |
| IceLake       | 3         | 3.23%   |
| Goldmont plus | 3         | 3.23%   |
| Skylake       | 2         | 2.15%   |
| Silvermont    | 2         | 2.15%   |
| Penryn        | 2         | 2.15%   |
| Westmere      | 1         | 1.08%   |
| Puma          | 1         | 1.08%   |
| Jaguar        | 1         | 1.08%   |
| Goldmont      | 1         | 1.08%   |
| Bonnell       | 1         | 1.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 69        | 60%     |
| Nvidia | 25        | 21.74%  |
| AMD    | 21        | 18.26%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                     | 6         | 5.22%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 5.22%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 5.22%   |
| AMD Renoir                                                                | 6         | 5.22%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 5         | 4.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 3.48%   |
| Intel UHD Graphics 620                                                    | 4         | 3.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 3.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 3.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 3.48%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 2.61%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 2.61%   |
| Intel HD Graphics 5500                                                    | 3         | 2.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 2.61%   |
| Nvidia TU117M                                                             | 2         | 1.74%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.74%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 2         | 1.74%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 1.74%   |
| Intel UHD Graphics 615                                                    | 2         | 1.74%   |
| Intel HD Graphics 630                                                     | 2         | 1.74%   |
| Intel HD Graphics 6000                                                    | 2         | 1.74%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 1.74%   |
| AMD Saturn XT [FirePro M6100]                                             | 2         | 1.74%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.74%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.87%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.87%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.87%   |
| Nvidia GP108M [GeForce MX330]                                             | 1         | 0.87%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.87%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 0.87%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                  | 1         | 0.87%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.87%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                     | 1         | 0.87%   |
| Nvidia GM107 [GeForce 940MX]                                              | 1         | 0.87%   |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 0.87%   |
| Nvidia GF119M [GeForce GT 520MX]                                          | 1         | 0.87%   |
| Nvidia GF108M [GeForce GT 520M]                                           | 1         | 0.87%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 1         | 0.87%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 48        | 51.06%  |
| Intel + Nvidia | 18        | 19.15%  |
| 1 x AMD        | 18        | 19.15%  |
| 1 x Nvidia     | 6         | 6.38%   |
| Intel + AMD    | 3         | 3.19%   |
| AMD + Nvidia   | 1         | 1.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 78        | 83.87%  |
| Proprietary | 15        | 16.13%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 60        | 63.83%  |
| 1.01-2.0   | 11        | 11.7%   |
| 0.01-0.5   | 9         | 9.57%   |
| 3.01-4.0   | 5         | 5.32%   |
| 0.51-1.0   | 4         | 4.26%   |
| 7.01-8.0   | 2         | 2.13%   |
| 5.01-6.0   | 2         | 2.13%   |
| 2.01-3.0   | 1         | 1.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 19        | 17.59%  |
| AU Optronics            | 19        | 17.59%  |
| BOE                     | 17        | 15.74%  |
| Chimei Innolux          | 13        | 12.04%  |
| Samsung Electronics     | 6         | 5.56%   |
| Dell                    | 4         | 3.7%    |
| Chi Mei Optoelectronics | 4         | 3.7%    |
| InfoVision              | 3         | 2.78%   |
| ASUSTek Computer        | 3         | 2.78%   |
| Apple                   | 3         | 2.78%   |
| Sharp                   | 2         | 1.85%   |
| PANDA                   | 2         | 1.85%   |
| Hewlett-Packard         | 2         | 1.85%   |
| Goldstar                | 2         | 1.85%   |
| BenQ                    | 2         | 1.85%   |
| Philips                 | 1         | 0.93%   |
| MSI                     | 1         | 0.93%   |
| LGD                     | 1         | 0.93%   |
| Lenovo                  | 1         | 0.93%   |
| KDC                     | 1         | 0.93%   |
| Ancor Communications    | 1         | 0.93%   |
| Acer                    | 1         | 0.93%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 2.78%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch      | 2         | 1.85%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 1.85%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 1.85%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.85%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 1.85%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 1.85%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 1.85%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 1.85%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 1.85%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 1.85%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 0.93%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.93%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 0.93%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 0.93%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 0.93%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                   | 1         | 0.93%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 1         | 0.93%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                   | 1         | 0.93%   |
| MSI Optix MAG27C MSI1462 1920x1080 598x336mm 27.0-inch                    | 1         | 0.93%   |
| LGD LCD Monitor 1920x1080                                                 | 1         | 0.93%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch               | 1         | 0.93%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch               | 1         | 0.93%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch               | 1         | 0.93%   |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch              | 1         | 0.93%   |
| LG Display LCD Monitor LGD03D3 1600x900 309x174mm 14.0-inch               | 1         | 0.93%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch               | 1         | 0.93%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch               | 1         | 0.93%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch              | 1         | 0.93%   |
| Lenovo LCD Monitor LEN4053 1680x1050 331x207mm 15.4-inch                  | 1         | 0.93%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 49        | 48.51%  |
| 1366x768 (WXGA)    | 33        | 32.67%  |
| 1440x900 (WXGA+)   | 4         | 3.96%   |
| 3840x2160 (4K)     | 3         | 2.97%   |
| 2560x1440 (QHD)    | 3         | 2.97%   |
| 1600x900 (HD+)     | 3         | 2.97%   |
| 2560x1600          | 2         | 1.98%   |
| 3440x1440          | 1         | 0.99%   |
| 2160x1440          | 1         | 0.99%   |
| 1920x1200 (WUXGA)  | 1         | 0.99%   |
| 1680x1050 (WSXGA+) | 1         | 0.99%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 47        | 43.93%  |
| 13      | 17        | 15.89%  |
| 14      | 15        | 14.02%  |
| 17      | 7         | 6.54%   |
| 24      | 5         | 4.67%   |
| 27      | 4         | 3.74%   |
| 21      | 4         | 3.74%   |
| 23      | 2         | 1.87%   |
| 34      | 1         | 0.93%   |
| 20      | 1         | 0.93%   |
| 19      | 1         | 0.93%   |
| 12      | 1         | 0.93%   |
| 11      | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 71        | 66.36%  |
| 501-600     | 10        | 9.35%   |
| 351-400     | 9         | 8.41%   |
| 201-300     | 8         | 7.48%   |
| 401-500     | 6         | 5.61%   |
| 701-800     | 1         | 0.93%   |
| 601-700     | 1         | 0.93%   |
| Unknown     | 1         | 0.93%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 82        | 88.17%  |
| 16/10   | 8         | 8.6%    |
| 3/2     | 1         | 1.08%   |
| 21/9    | 1         | 1.08%   |
| Unknown | 1         | 1.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 47        | 43.93%  |
| 81-90          | 26        | 24.3%   |
| 201-250        | 10        | 9.35%   |
| 71-80          | 6         | 5.61%   |
| 121-130        | 6         | 5.61%   |
| 301-350        | 4         | 3.74%   |
| 151-200        | 2         | 1.87%   |
| 61-70          | 1         | 0.93%   |
| 51-60          | 1         | 0.93%   |
| 351-500        | 1         | 0.93%   |
| 251-300        | 1         | 0.93%   |
| 131-140        | 1         | 0.93%   |
| Unknown        | 1         | 0.93%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 50        | 47.62%  |
| 101-120       | 32        | 30.48%  |
| 51-100        | 16        | 15.24%  |
| 161-240       | 5         | 4.76%   |
| More than 240 | 1         | 0.95%   |
| Unknown       | 1         | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 80        | 83.33%  |
| 2     | 16        | 16.67%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 60        | 38.96%  |
| Intel                 | 51        | 33.12%  |
| Qualcomm Atheros      | 19        | 12.34%  |
| Broadcom              | 8         | 5.19%   |
| Broadcom Limited      | 4         | 2.6%    |
| Ralink                | 2         | 1.3%    |
| Xiaomi                | 1         | 0.65%   |
| Sierra Wireless       | 1         | 0.65%   |
| Samsung Electronics   | 1         | 0.65%   |
| Ralink Technology     | 1         | 0.65%   |
| Qualcomm              | 1         | 0.65%   |
| OPPO Electronics      | 1         | 0.65%   |
| MediaTek              | 1         | 0.65%   |
| Linksys               | 1         | 0.65%   |
| Huawei Technologies   | 1         | 0.65%   |
| Apple                 | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 20.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 6.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 3.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 3.33%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 2.78%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.22%   |
| Intel Wireless 7265                                               | 4         | 2.22%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 2.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.67%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.67%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.11%   |
| Realtek 802.11ac NIC                                              | 2         | 1.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.11%   |
| Intel Wireless 7260                                               | 2         | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 1.11%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.11%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 1.11%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 1.11%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.11%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.56%   |
| Sierra Wireless MC7750                                            | 1         | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.56%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.56%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 47        | 48.45%  |
| Realtek Semiconductor | 18        | 18.56%  |
| Qualcomm Atheros      | 16        | 16.49%  |
| Broadcom              | 7         | 7.22%   |
| Broadcom Limited      | 4         | 4.12%   |
| Ralink                | 2         | 2.06%   |
| Sierra Wireless       | 1         | 1.03%   |
| Ralink Technology     | 1         | 1.03%   |
| MediaTek              | 1         | 1.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 6.19%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 6.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 5.15%   |
| Intel Wireless 8265 / 8275                                     | 5         | 5.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 4.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 4.12%   |
| Intel Wireless 7265                                            | 4         | 4.12%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 4.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 3.09%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 3.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 3.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 3.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 3.09%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 3.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 3.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 2.06%   |
| Realtek 802.11ac NIC                                           | 2         | 2.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 2.06%   |
| Intel Wireless 7260                                            | 2         | 2.06%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 2.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 2.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.06%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 2.06%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 2.06%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 2.06%   |
| Sierra Wireless MC7750                                         | 1         | 1.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.03%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 1.03%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.03%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.03%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1         | 1.03%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.03%   |
| Intel Wireless-AC 9260                                         | 1         | 1.03%   |
| Intel Wireless 3165                                            | 1         | 1.03%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 1.03%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 1.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 53        | 65.43%  |
| Intel                 | 16        | 19.75%  |
| Qualcomm Atheros      | 4         | 4.94%   |
| Xiaomi                | 1         | 1.23%   |
| Samsung Electronics   | 1         | 1.23%   |
| Qualcomm              | 1         | 1.23%   |
| OPPO Electronics      | 1         | 1.23%   |
| Linksys               | 1         | 1.23%   |
| Huawei Technologies   | 1         | 1.23%   |
| Broadcom              | 1         | 1.23%   |
| Apple                 | 1         | 1.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 44.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 13.25%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 7.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 7.23%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 3.61%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 2.41%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.2%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.2%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.2%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.2%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.2%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.2%    |
| Qualcomm A0001                                                    | 1         | 1.2%    |
| OPPO RMX2117                                                      | 1         | 1.2%    |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 1.2%    |
| Intel WiMAX Connection 2400m                                      | 1         | 1.2%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.2%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.2%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.2%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.2%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.2%    |
| Huawei E353/E3131                                                 | 1         | 1.2%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.2%    |
| Apple iPad 4/Mini1                                                | 1         | 1.2%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 91        | 55.15%  |
| Ethernet | 74        | 44.85%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 75        | 78.13%  |
| Ethernet | 21        | 21.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 66        | 70.21%  |
| 1     | 25        | 26.6%   |
| 3     | 2         | 2.13%   |
| 0     | 1         | 1.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 84        | 87.5%   |
| Yes  | 12        | 12.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 52%     |
| Realtek Semiconductor           | 11        | 14.67%  |
| Broadcom                        | 5         | 6.67%   |
| Qualcomm Atheros Communications | 4         | 5.33%   |
| Lite-On Technology              | 4         | 5.33%   |
| Foxconn / Hon Hai               | 3         | 4%      |
| Apple                           | 3         | 4%      |
| Realtek                         | 2         | 2.67%   |
| IMC Networks                    | 2         | 2.67%   |
| Ralink                          | 1         | 1.33%   |
| Cambridge Silicon Radio         | 1         | 1.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 14.67%  |
| Intel AX201 Bluetooth                               | 10        | 13.33%  |
| Realtek Bluetooth Radio                             | 7         | 9.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 9.33%   |
| Intel AX200 Bluetooth                               | 6         | 8%      |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 5.33%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 4%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 4%      |
| Realtek Bluetooth Radio                             | 2         | 2.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.67%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.67%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 2.67%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.67%   |
| Apple Bluetooth USB Host Controller                 | 2         | 2.67%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.33%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.33%   |
| IMC Networks Wireless_Device                        | 1         | 1.33%   |
| IMC Networks Bluetooth Device                       | 1         | 1.33%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.33%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.33%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.33%   |
| Apple Bluetooth Host Controller                     | 1         | 1.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 75        | 63.56%  |
| AMD                   | 19        | 16.1%   |
| Nvidia                | 16        | 13.56%  |
| C-Media Electronics   | 3         | 2.54%   |
| Realtek Semiconductor | 2         | 1.69%   |
| Plantronics           | 1         | 0.85%   |
| Harman                | 1         | 0.85%   |
| Corsair               | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 13        | 8.84%   |
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 8.84%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 5.44%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 4.08%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 4.08%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 4.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 4.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 3.4%    |
| Intel Comet Lake PCH cAVS                                                  | 5         | 3.4%    |
| Intel Broadwell-U Audio Controller                                         | 5         | 3.4%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 5         | 3.4%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 2.72%   |
| Intel CM238 HD Audio Controller                                            | 4         | 2.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.72%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.04%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 2.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 2.04%   |
| Realtek Semiconductor USB Audio                                            | 2         | 1.36%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.36%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.36%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.36%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.36%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.36%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.36%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 1.36%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 2         | 1.36%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.36%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.36%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.68%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.68%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.68%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.68%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.68%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.68%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.68%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 28        | 28.28%  |
| Samsung Electronics | 28        | 28.28%  |
| Kingston            | 9         | 9.09%   |
| Micron Technology   | 8         | 8.08%   |
| Unknown             | 4         | 4.04%   |
| Silicon Power       | 3         | 3.03%   |
| A-DATA Technology   | 3         | 3.03%   |
| Unknown             | 3         | 3.03%   |
| Unknown (ABCD)      | 2         | 2.02%   |
| Smart               | 2         | 2.02%   |
| Ramaxel Technology  | 2         | 2.02%   |
| Nanya Technology    | 2         | 2.02%   |
| Corsair             | 2         | 2.02%   |
| Team                | 1         | 1.01%   |
| Smart Brazil        | 1         | 1.01%   |
| ASint Technology    | 1         | 1.01%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 4         | 3.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.88%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.88%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 2.88%   |
| Unknown                                                          | 3         | 2.88%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 2         | 1.92%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.92%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.92%   |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.92%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.92%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.92%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 2         | 1.92%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 2         | 1.92%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 1.92%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.92%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.92%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.92%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.92%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.96%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.96%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.96%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.96%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.96%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 1         | 0.96%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2400MT/s            | 1         | 0.96%   |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 2933MT/s  | 1         | 0.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.96%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.96%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.96%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.96%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.96%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.96%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.96%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.96%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.96%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.96%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.96%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 0.96%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 1         | 0.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 44        | 54.32%  |
| DDR3    | 27        | 33.33%  |
| LPDDR4  | 4         | 4.94%   |
| LPDDR3  | 3         | 3.7%    |
| SDRAM   | 2         | 2.47%   |
| Unknown | 1         | 1.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 72        | 87.8%   |
| Row Of Chips | 7         | 8.54%   |
| DIMM         | 1         | 1.22%   |
| Chip         | 1         | 1.22%   |
| Unknown      | 1         | 1.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 38        | 40%     |
| 8192  | 29        | 30.53%  |
| 16384 | 14        | 14.74%  |
| 2048  | 11        | 11.58%  |
| 32768 | 2         | 2.11%   |
| 1024  | 1         | 1.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 26        | 30.23%  |
| 3200  | 17        | 19.77%  |
| 2667  | 17        | 19.77%  |
| 2400  | 10        | 11.63%  |
| 1333  | 4         | 4.65%   |
| 2133  | 3         | 3.49%   |
| 4199  | 2         | 2.33%   |
| 1334  | 2         | 2.33%   |
| 4267  | 1         | 1.16%   |
| 3400  | 1         | 1.16%   |
| 3266  | 1         | 1.16%   |
| 2933  | 1         | 1.16%   |
| 1066  | 1         | 1.16%   |

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
| Chicony Electronics                    | 19        | 23.17%  |
| Realtek Semiconductor                  | 9         | 10.98%  |
| Quanta                                 | 9         | 10.98%  |
| Acer                                   | 9         | 10.98%  |
| Suyin                                  | 6         | 7.32%   |
| IMC Networks                           | 6         | 7.32%   |
| Alcor Micro                            | 4         | 4.88%   |
| Syntek                                 | 3         | 3.66%   |
| Sunplus Innovation Technology          | 3         | 3.66%   |
| Microdia                               | 3         | 3.66%   |
| Luxvisions Innotech Limited            | 3         | 3.66%   |
| Silicon Motion                         | 2         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.44%   |
| Sonix Technology                       | 1         | 1.22%   |
| Lite-On Technology                     | 1         | 1.22%   |
| LG Electronics                         | 1         | 1.22%   |
| Lenovo                                 | 1         | 1.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                     | 6         | 7.32%   |
| IMC Networks Integrated Camera                        | 5         | 6.1%    |
| Realtek Integrated_Webcam_HD                          | 4         | 4.88%   |
| Chicony Integrated Camera                             | 4         | 4.88%   |
| Acer Integrated Camera                                | 3         | 3.66%   |
| Syntek EasyCamera                                     | 2         | 2.44%   |
| Suyin HP Webcam                                       | 2         | 2.44%   |
| Silicon Motion 300k Pixel Camera                      | 2         | 2.44%   |
| Realtek USB2.0 HD UVC WebCam                          | 2         | 2.44%   |
| Realtek HD WebCam                                     | 2         | 2.44%   |
| Quanta VGA WebCam                                     | 2         | 2.44%   |
| Quanta HP Webcam                                      | 2         | 2.44%   |
| Quanta HP TrueVision HD Camera                        | 2         | 2.44%   |
| Microdia Integrated Webcam                            | 2         | 2.44%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera   | 2         | 2.44%   |
| Chicony USB2.0 VGA UVC WebCam                         | 2         | 2.44%   |
| Chicony Integrated Camera (1280x720@30)               | 2         | 2.44%   |
| Syntek Integrated Camera                              | 1         | 1.22%   |
| Suyin USB Webcam                                      | 1         | 1.22%   |
| Suyin NEC HD WebCam                                   | 1         | 1.22%   |
| Suyin Laptop_Integrated_Webcam_HD                     | 1         | 1.22%   |
| Suyin 1.3M HD WebCam                                  | 1         | 1.22%   |
| Sunplus Laptop_Integrated_Webcam_FHD                  | 1         | 1.22%   |
| Sunplus Integrated_Webcam_HD                          | 1         | 1.22%   |
| Sunplus HD WebCam                                     | 1         | 1.22%   |
| Sonix USB2.0 HD UVC WebCam                            | 1         | 1.22%   |
| Realtek Integrated Webcam                             | 1         | 1.22%   |
| Quanta USB2.0 VGA UVC WebCam                          | 1         | 1.22%   |
| Quanta HD Webcam                                      | 1         | 1.22%   |
| Quanta HD User Facing                                 | 1         | 1.22%   |
| Microdia Integrated_Webcam_HD                         | 1         | 1.22%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera  | 1         | 1.22%   |
| Lite-On HP HD Camera                                  | 1         | 1.22%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1         | 1.22%   |
| Lenovo UVC Camera                                     | 1         | 1.22%   |
| IMC Networks Integrated Webcam                        | 1         | 1.22%   |
| Chicony USB2.0 Camera                                 | 1         | 1.22%   |
| Chicony USB2.0 0.3M UVC WebCam                        | 1         | 1.22%   |
| Chicony Thinkpad T430 camera                          | 1         | 1.22%   |
| Chicony LG Camera                                     | 1         | 1.22%   |

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
| 0     | 66        | 68.75%  |
| 1     | 25        | 26.04%  |
| 2     | 5         | 5.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 7         | 19.44%  |
| Net/wireless             | 5         | 13.89%  |
| Multimedia controller    | 4         | 11.11%  |
| Graphics card            | 4         | 11.11%  |
| Chipcard                 | 4         | 11.11%  |
| Camera                   | 4         | 11.11%  |
| Bluetooth                | 3         | 8.33%   |
| Storage                  | 2         | 5.56%   |
| Network                  | 1         | 2.78%   |
| Dvb card                 | 1         | 2.78%   |
| Communication controller | 1         | 2.78%   |

