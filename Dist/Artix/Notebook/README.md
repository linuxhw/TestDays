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

Total: 141

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [eeb167d869](https://linux-hardware.org/?probe=eeb167d869) | Nov 02, 2022 |
| MSI           | GF65 Thin 10SDR             | [debce2faa6](https://linux-hardware.org/?probe=debce2faa6) | Oct 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7dce56f55d](https://linux-hardware.org/?probe=7dce56f55d) | Oct 10, 2022 |
| HP            | Pavilion g4                 | [19fe60b14c](https://linux-hardware.org/?probe=19fe60b14c) | Oct 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7d1f20cf17](https://linux-hardware.org/?probe=7d1f20cf17) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [dfd00dd2d1](https://linux-hardware.org/?probe=dfd00dd2d1) | Oct 03, 2022 |
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
| Artix Rolling  | 61        | 59.22%  |
| Artix          | 38        | 36.89%  |
| Artix 20220713 | 1         | 0.97%   |
| Artix 20220123 | 1         | 0.97%   |
| Artix 20201207 | 1         | 0.97%   |
| Artix 20201128 | 1         | 0.97%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Artix | 98        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.9.14-artix1-1                 | 6         | 5.13%   |
| 5.7.6-artix1-1                  | 3         | 2.56%   |
| 5.7.12-artix1-1                 | 2         | 1.71%   |
| 5.19.12-artix1-1                | 2         | 1.71%   |
| 5.18.6-artix1-1                 | 2         | 1.71%   |
| 5.18.0-artix1-1                 | 2         | 1.71%   |
| 5.17.1-artix1-1                 | 2         | 1.71%   |
| 5.16.8-artix1-2                 | 2         | 1.71%   |
| 5.16.10-artix1-1                | 2         | 1.71%   |
| 5.15.12-artix1-1                | 2         | 1.71%   |
| 5.14.16-artix1-1                | 2         | 1.71%   |
| 5.13.8-artix1-1                 | 2         | 1.71%   |
| 5.12.8-artix1-1                 | 2         | 1.71%   |
| 5.12.12-zen1-1-zen              | 2         | 1.71%   |
| 5.12.12-artix1-1                | 2         | 1.71%   |
| 5.11.6-artix1-1                 | 2         | 1.71%   |
| 5.10.6-artix1-1                 | 2         | 1.71%   |
| 5.10.4-artix2-1                 | 2         | 1.71%   |
| 5.10.16-artix1-1                | 2         | 1.71%   |
| 6.0.2-artix1-1.1                | 1         | 0.85%   |
| 5.9.6-artix1-1                  | 1         | 0.85%   |
| 5.9.14-zen1-1-zen               | 1         | 0.85%   |
| 5.9.12-artix1-1                 | 1         | 0.85%   |
| 5.9.1-artix1-1                  | 1         | 0.85%   |
| 5.9.0-zen1-1-zen                | 1         | 0.85%   |
| 5.9.0-1-mainline-bootsplash     | 1         | 0.85%   |
| 5.8.8-artix1-1                  | 1         | 0.85%   |
| 5.8.4-artix1-1                  | 1         | 0.85%   |
| 5.8.14-zen1-1-zen               | 1         | 0.85%   |
| 5.8.14-artix1-1                 | 1         | 0.85%   |
| 5.8.12-artix1-1                 | 1         | 0.85%   |
| 5.8.0-rc7-5-mainline-bootsplash | 1         | 0.85%   |
| 5.7.8-artix1-1                  | 1         | 0.85%   |
| 5.7.2-artix1-1                  | 1         | 0.85%   |
| 5.6.7-x86_64                    | 1         | 0.85%   |
| 5.5.3-artix1-1                  | 1         | 0.85%   |
| 5.5.10-artix1-1                 | 1         | 0.85%   |
| 5.4.74-1-lts                    | 1         | 0.85%   |
| 5.19.8-artix1-1                 | 1         | 0.85%   |
| 5.19.2-artix1-2                 | 1         | 0.85%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.9.14  | 7         | 5.98%   |
| 5.12.12 | 4         | 3.42%   |
| 5.7.6   | 3         | 2.56%   |
| 5.17.1  | 3         | 2.56%   |
| 5.15.12 | 3         | 2.56%   |
| 5.12.8  | 3         | 2.56%   |
| 5.9.0   | 2         | 1.71%   |
| 5.8.14  | 2         | 1.71%   |
| 5.7.12  | 2         | 1.71%   |
| 5.19.12 | 2         | 1.71%   |
| 5.18.6  | 2         | 1.71%   |
| 5.18.0  | 2         | 1.71%   |
| 5.16.8  | 2         | 1.71%   |
| 5.16.10 | 2         | 1.71%   |
| 5.14.16 | 2         | 1.71%   |
| 5.13.8  | 2         | 1.71%   |
| 5.12.14 | 2         | 1.71%   |
| 5.11.6  | 2         | 1.71%   |
| 5.10.6  | 2         | 1.71%   |
| 5.10.4  | 2         | 1.71%   |
| 5.10.16 | 2         | 1.71%   |
| 6.0.2   | 1         | 0.85%   |
| 5.9.6   | 1         | 0.85%   |
| 5.9.12  | 1         | 0.85%   |
| 5.9.1   | 1         | 0.85%   |
| 5.8.8   | 1         | 0.85%   |
| 5.8.4   | 1         | 0.85%   |
| 5.8.12  | 1         | 0.85%   |
| 5.8.0   | 1         | 0.85%   |
| 5.7.8   | 1         | 0.85%   |
| 5.7.2   | 1         | 0.85%   |
| 5.6.7   | 1         | 0.85%   |
| 5.5.3   | 1         | 0.85%   |
| 5.5.10  | 1         | 0.85%   |
| 5.4.74  | 1         | 0.85%   |
| 5.19.8  | 1         | 0.85%   |
| 5.19.2  | 1         | 0.85%   |
| 5.19.13 | 1         | 0.85%   |
| 5.19.11 | 1         | 0.85%   |
| 5.18.9  | 1         | 0.85%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 12        | 10.81%  |
| 5.12    | 12        | 10.81%  |
| 5.9     | 11        | 9.91%   |
| 5.18    | 11        | 9.91%   |
| 5.10    | 11        | 9.91%   |
| 5.17    | 8         | 7.21%   |
| 5.16    | 8         | 7.21%   |
| 5.11    | 8         | 7.21%   |
| 5.7     | 6         | 5.41%   |
| 5.19    | 6         | 5.41%   |
| 5.8     | 5         | 4.5%    |
| 5.14    | 4         | 3.6%    |
| 5.13    | 4         | 3.6%    |
| 6.0     | 1         | 0.9%    |
| 5.6     | 1         | 0.9%    |
| 5.5     | 1         | 0.9%    |
| 5.4     | 1         | 0.9%    |
| 4.19    | 1         | 0.9%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 98        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| KDE5           | 21        | 20.19%  |
| Unknown        | 18        | 17.31%  |
| XFCE           | 17        | 16.35%  |
| GNOME          | 14        | 13.46%  |
| X-Cinnamon     | 7         | 6.73%   |
| MATE           | 4         | 3.85%   |
| LXQt           | 4         | 3.85%   |
| KDE            | 4         | 3.85%   |
| LXDE           | 3         | 2.88%   |
| Cinnamon       | 3         | 2.88%   |
| bspwm          | 2         | 1.92%   |
| xmonad         | 1         | 0.96%   |
| sway-dbus      | 1         | 0.96%   |
| Sway           | 1         | 0.96%   |
| nxde           | 1         | 0.96%   |
| i3             | 1         | 0.96%   |
| awesomeminimal | 1         | 0.96%   |
| awesome        | 1         | 0.96%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 70        | 68.63%  |
| Tty     | 15        | 14.71%  |
| Wayland | 11        | 10.78%  |
| Unknown | 6         | 5.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 36        | 36%     |
| LightDM | 32        | 32%     |
| SDDM    | 27        | 27%     |
| XDM     | 1         | 1%      |
| SLiM    | 1         | 1%      |
| Ly      | 1         | 1%      |
| LXDM    | 1         | 1%      |
| GDM     | 1         | 1%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 51        | 50%     |
| Unknown | 11        | 10.78%  |
| ru_RU   | 8         | 7.84%   |
| en_GB   | 7         | 6.86%   |
| C       | 4         | 3.92%   |
| fr_FR   | 3         | 2.94%   |
| es_ES   | 2         | 1.96%   |
| en_CA   | 2         | 1.96%   |
| uk_UA   | 1         | 0.98%   |
| pt_PT   | 1         | 0.98%   |
| pt_BR   | 1         | 0.98%   |
| pl_PL   | 1         | 0.98%   |
| it_IT   | 1         | 0.98%   |
| es_GT   | 1         | 0.98%   |
| es_CO   | 1         | 0.98%   |
| en_NZ   | 1         | 0.98%   |
| en_IN   | 1         | 0.98%   |
| en_AU   | 1         | 0.98%   |
| en_AG   | 1         | 0.98%   |
| el_GR   | 1         | 0.98%   |
| de_DE   | 1         | 0.98%   |
| cs_CZ   | 1         | 0.98%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 72        | 72.73%  |
| BIOS | 27        | 27.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 73        | 73.74%  |
| Btrfs   | 20        | 20.2%   |
| Xfs     | 3         | 3.03%   |
| Overlay | 2         | 2.02%   |
| F2fs    | 1         | 1.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 71        | 71.72%  |
| MBR     | 14        | 14.14%  |
| Unknown | 14        | 14.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 84        | 84.85%  |
| Yes       | 15        | 15.15%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 73        | 74.49%  |
| Yes       | 25        | 25.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 26        | 26.53%  |
| Hewlett-Packard     | 15        | 15.31%  |
| Dell                | 14        | 14.29%  |
| Acer                | 12        | 12.24%  |
| ASUSTek Computer    | 11        | 11.22%  |
| MSI                 | 3         | 3.06%   |
| Apple               | 3         | 3.06%   |
| Timi                | 2         | 2.04%   |
| Notebook            | 2         | 2.04%   |
| GPD                 | 2         | 2.04%   |
| Gigabyte Technology | 2         | 2.04%   |
| UNOWHY              | 1         | 1.02%   |
| Quanta              | 1         | 1.02%   |
| MOTILE              | 1         | 1.02%   |
| LG Electronics      | 1         | 1.02%   |
| HUAWEI              | 1         | 1.02%   |
| AXIOO               | 1         | 1.02%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Timi RedmiBook 14 II                   | 2         | 2.04%   |
| Lenovo IdeaPad 5 15IIL05 81YK          | 2         | 2.04%   |
| HP 15                                  | 2         | 2.04%   |
| GPD P2 MAX                             | 2         | 2.04%   |
| Dell Precision M6600                   | 2         | 2.04%   |
| Dell Precision 7550                    | 2         | 2.04%   |
| Apple MacBookAir7,2                    | 2         | 2.04%   |
| UNOWHY Y13G010S4EI                     | 1         | 1.02%   |
| Quanta SWH                             | 1         | 1.02%   |
| Notebook N141CU                        | 1         | 1.02%   |
| Notebook N130BU                        | 1         | 1.02%   |
| MSI Modern 15 A11M                     | 1         | 1.02%   |
| MSI GP72 7RDX                          | 1         | 1.02%   |
| MSI GF65 Thin 10SDR                    | 1         | 1.02%   |
| MOTILE M141                            | 1         | 1.02%   |
| LG 17Z990-R.AAC9U1                     | 1         | 1.02%   |
| Lenovo ThinkPad W500 4063CJ5           | 1         | 1.02%   |
| Lenovo ThinkPad T480s 20L8S3D400       | 1         | 1.02%   |
| Lenovo ThinkPad T480 MFG_IN_GO         | 1         | 1.02%   |
| Lenovo ThinkPad T440s 20ARS0MV00       | 1         | 1.02%   |
| Lenovo ThinkPad T430 2350BC6           | 1         | 1.02%   |
| Lenovo ThinkPad T430 2347H76           | 1         | 1.02%   |
| Lenovo ThinkPad T420 4236H45           | 1         | 1.02%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00   | 1         | 1.02%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800   | 1         | 1.02%   |
| Lenovo ThinkPad P1 Gen 3 20TH001EMH    | 1         | 1.02%   |
| Lenovo ThinkPad E14 Gen 2 20T6000MCK   | 1         | 1.02%   |
| Lenovo ThinkPad 11e 5th Gen 20LNS0P500 | 1         | 1.02%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 1         | 1.02%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 1.02%   |
| Lenovo LaVie Z 20FF0012US              | 1         | 1.02%   |
| Lenovo IdeaPad Y500 20193              | 1         | 1.02%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL  | 1         | 1.02%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG   | 1         | 1.02%   |
| Lenovo IdeaPad 510-15IKB 80SV          | 1         | 1.02%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5       | 1         | 1.02%   |
| Lenovo IdeaPad 330-15IKB 81DE          | 1         | 1.02%   |
| Lenovo G400s 20244                     | 1         | 1.02%   |
| Lenovo B590 20206                      | 1         | 1.02%   |
| Lenovo B570e HuronRiver Platform       | 1         | 1.02%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 12        | 12.24%  |
| Lenovo IdeaPad     | 8         | 8.16%   |
| Acer Aspire        | 8         | 8.16%   |
| Dell Precision     | 6         | 6.12%   |
| HP Laptop          | 5         | 5.1%    |
| Dell Latitude      | 4         | 4.08%   |
| Dell Inspiron      | 4         | 4.08%   |
| HP 250             | 3         | 3.06%   |
| Timi RedmiBook     | 2         | 2.04%   |
| HP 15              | 2         | 2.04%   |
| GPD P2             | 2         | 2.04%   |
| ASUS VivoBook      | 2         | 2.04%   |
| ASUS ASUS          | 2         | 2.04%   |
| Apple MacBookAir7  | 2         | 2.04%   |
| Acer Nitro         | 2         | 2.04%   |
| UNOWHY Y13G010S4EI | 1         | 1.02%   |
| Quanta SWH         | 1         | 1.02%   |
| Notebook N141CU    | 1         | 1.02%   |
| Notebook N130BU    | 1         | 1.02%   |
| MSI Modern         | 1         | 1.02%   |
| MSI GP72           | 1         | 1.02%   |
| MSI GF65           | 1         | 1.02%   |
| MOTILE M141        | 1         | 1.02%   |
| LG 17Z990-R.AAC9U1 | 1         | 1.02%   |
| Lenovo ThinkBook   | 1         | 1.02%   |
| Lenovo Legion      | 1         | 1.02%   |
| Lenovo LaVie       | 1         | 1.02%   |
| Lenovo G400s       | 1         | 1.02%   |
| Lenovo B590        | 1         | 1.02%   |
| Lenovo B570e       | 1         | 1.02%   |
| HUAWEI WRT-WX9     | 1         | 1.02%   |
| HP ProBook         | 1         | 1.02%   |
| HP Pavilion        | 1         | 1.02%   |
| HP OMEN            | 1         | 1.02%   |
| HP 255             | 1         | 1.02%   |
| HP 246             | 1         | 1.02%   |
| Gigabyte B450M     | 1         | 1.02%   |
| Gigabyte AERO      | 1         | 1.02%   |
| AXIOO Mybook       | 1         | 1.02%   |
| ASUS X553MA        | 1         | 1.02%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 23        | 23.47%  |
| 2018 | 13        | 13.27%  |
| 2019 | 10        | 10.2%   |
| 2017 | 8         | 8.16%   |
| 2011 | 8         | 8.16%   |
| 2014 | 7         | 7.14%   |
| 2012 | 7         | 7.14%   |
| 2013 | 6         | 6.12%   |
| 2015 | 5         | 5.1%    |
| 2021 | 4         | 4.08%   |
| 2016 | 4         | 4.08%   |
| 2022 | 1         | 1.02%   |
| 2010 | 1         | 1.02%   |
| 2009 | 1         | 1.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 98        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 97        | 98.98%  |
| Enabled  | 1         | 1.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 98        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 28        | 28.28%  |
| 8.01-16.0   | 24        | 24.24%  |
| 16.01-24.0  | 18        | 18.18%  |
| 3.01-4.0    | 16        | 16.16%  |
| 32.01-64.0  | 4         | 4.04%   |
| 1.01-2.0    | 4         | 4.04%   |
| 64.01-256.0 | 3         | 3.03%   |
| 24.01-32.0  | 2         | 2.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 30        | 27.03%  |
| 2.01-3.0   | 26        | 23.42%  |
| 4.01-8.0   | 24        | 21.62%  |
| 3.01-4.0   | 15        | 13.51%  |
| 0.51-1.0   | 9         | 8.11%   |
| 8.01-16.0  | 4         | 3.6%    |
| 0.01-0.5   | 2         | 1.8%    |
| 16.01-24.0 | 1         | 0.9%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 76        | 76.77%  |
| 2      | 22        | 22.22%  |
| 3      | 1         | 1.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 74        | 75.51%  |
| Yes       | 24        | 24.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 78.57%  |
| No        | 21        | 21.43%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 97.96%  |
| No        | 2         | 2.04%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 80%     |
| No        | 20        | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 22        | 22.45%  |
| Russia      | 9         | 9.18%   |
| India       | 6         | 6.12%   |
| Brazil      | 5         | 5.1%    |
| UK          | 4         | 4.08%   |
| Turkey      | 4         | 4.08%   |
| Indonesia   | 4         | 4.08%   |
| Germany     | 4         | 4.08%   |
| Canada      | 4         | 4.08%   |
| Ukraine     | 3         | 3.06%   |
| Netherlands | 3         | 3.06%   |
| France      | 3         | 3.06%   |
| Switzerland | 2         | 2.04%   |
| Spain       | 2         | 2.04%   |
| Poland      | 2         | 2.04%   |
| Italy       | 2         | 2.04%   |
| Czechia     | 2         | 2.04%   |
| Bulgaria    | 2         | 2.04%   |
| Uzbekistan  | 1         | 1.02%   |
| Sweden      | 1         | 1.02%   |
| Romania     | 1         | 1.02%   |
| Peru        | 1         | 1.02%   |
| Lithuania   | 1         | 1.02%   |
| Guatemala   | 1         | 1.02%   |
| Greece      | 1         | 1.02%   |
| Colombia    | 1         | 1.02%   |
| China       | 1         | 1.02%   |
| Chile       | 1         | 1.02%   |
| Bangladesh  | 1         | 1.02%   |
| Azerbaijan  | 1         | 1.02%   |
| Australia   | 1         | 1.02%   |
| Argentina   | 1         | 1.02%   |
| Algeria     | 1         | 1.02%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 3         | 2.88%   |
| Jakarta           | 3         | 2.88%   |
| St Petersburg     | 2         | 1.92%   |
| San Ramon         | 2         | 1.92%   |
| Samara            | 2         | 1.92%   |
| Rio de Janeiro    | 2         | 1.92%   |
| Prague            | 2         | 1.92%   |
| Omaha             | 2         | 1.92%   |
| Neuchatel         | 2         | 1.92%   |
| Los Angeles       | 2         | 1.92%   |
| Frankfurt am Main | 2         | 1.92%   |
| Dnipro            | 2         | 1.92%   |
| Amsterdam         | 2         | 1.92%   |
| Zaporizhzhya      | 1         | 0.96%   |
| Wigan             | 1         | 0.96%   |
| Wem               | 1         | 0.96%   |
| Vilnius           | 1         | 0.96%   |
| Varna             | 1         | 0.96%   |
| Vancouver         | 1         | 0.96%   |
| Toronto           | 1         | 0.96%   |
| Timișoara        | 1         | 0.96%   |
| Tashkent          | 1         | 0.96%   |
| Syeverodonets'k   | 1         | 0.96%   |
| Surgut            | 1         | 0.96%   |
| Stuttgart         | 1         | 0.96%   |
| Stockholm         | 1         | 0.96%   |
| Sofia             | 1         | 0.96%   |
| Snohomish         | 1         | 0.96%   |
| Skikda            | 1         | 0.96%   |
| Sigogne           | 1         | 0.96%   |
| Seville           | 1         | 0.96%   |
| Semarang          | 1         | 0.96%   |
| Seattle           | 1         | 0.96%   |
| Santiago          | 1         | 0.96%   |
| Santa Marta       | 1         | 0.96%   |
| Santa Fe          | 1         | 0.96%   |
| Sainte-Severe     | 1         | 0.96%   |
| Quincy            | 1         | 0.96%   |
| Puducherry        | 1         | 0.96%   |
| Palermo           | 1         | 0.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 25        | 31     | 20.66%  |
| Seagate                   | 15        | 15     | 12.4%   |
| WDC                       | 10        | 13     | 8.26%   |
| Toshiba                   | 9         | 9      | 7.44%   |
| SanDisk                   | 6         | 6      | 4.96%   |
| Kingston                  | 6         | 7      | 4.96%   |
| Intel                     | 6         | 8      | 4.96%   |
| HGST                      | 6         | 6      | 4.96%   |
| SK hynix                  | 5         | 11     | 4.13%   |
| Hitachi                   | 4         | 5      | 3.31%   |
| China                     | 4         | 4      | 3.31%   |
| Apple                     | 3         | 4      | 2.48%   |
| Unknown                   | 2         | 2      | 1.65%   |
| Phison Electronics        | 2         | 3      | 1.65%   |
| Crucial                   | 2         | 2      | 1.65%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.83%   |
| Timetec                   | 1         | 2      | 0.83%   |
| SPCC                      | 1         | 1      | 0.83%   |
| Solid State Storage       | 1         | 1      | 0.83%   |
| PNY                       | 1         | 1      | 0.83%   |
| Phison                    | 1         | 1      | 0.83%   |
| Patriot                   | 1         | 1      | 0.83%   |
| Micron/Crucial Technology | 1         | 1      | 0.83%   |
| Micron Technology         | 1         | 1      | 0.83%   |
| LITEON                    | 1         | 1      | 0.83%   |
| Lite-On                   | 1         | 1      | 0.83%   |
| Linux                     | 1         | 1      | 0.83%   |
| LDLC                      | 1         | 5      | 0.83%   |
| Intenso                   | 1         | 1      | 0.83%   |
| A-DATA Technology         | 1         | 1      | 0.83%   |
| Unknown                   | 1         | 1      | 0.83%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 4         | 3.15%   |
| SanDisk NVMe SSD Drive 512GB                       | 4         | 3.15%   |
| China SATA SSD 960GB                               | 3         | 2.36%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 2         | 1.57%   |
| Toshiba MQ04ABF100 1TB                             | 2         | 1.57%   |
| Toshiba MQ01ABF050 500GB                           | 2         | 1.57%   |
| Toshiba MQ01ABD100 1TB                             | 2         | 1.57%   |
| Seagate ST500LT012-1DG142 500GB                    | 2         | 1.57%   |
| Samsung NVMe SSD Drive 1TB                         | 2         | 1.57%   |
| Samsung MZNLH512HALU-00000 512GB SSD               | 2         | 1.57%   |
| Phison PCIe SSD 512GB                              | 2         | 1.57%   |
| Kingston OM8PCP3512F-AI1 512GB                     | 2         | 1.57%   |
| HGST HTS545050A7E680 500GB                         | 2         | 1.57%   |
| Apple SSD SM0256G 256GB                            | 2         | 1.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 0.79%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                     | 1         | 0.79%   |
| WDC WD5000LPVX-75V0TT0 500GB                       | 1         | 0.79%   |
| WDC WD5000BPVT-22HXZT3 500GB                       | 1         | 0.79%   |
| WDC WD3200LPVT-00FMCT0 320GB                       | 1         | 0.79%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 0.79%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 1         | 0.79%   |
| WDC WD10SPCX-24HWST1 1TB                           | 1         | 0.79%   |
| Unknown SD/MMC/MS PRO 1TB                          | 1         | 0.79%   |
| Unknown DA4064  64GB                               | 1         | 0.79%   |
| Union Memory (Shenzhen) UMIS RPEYJ512VMM2QWY 512GB | 1         | 0.79%   |
| Toshiba THNSNH128GMCT 128GB SSD                    | 1         | 0.79%   |
| Toshiba MK5065GSX 500GB                            | 1         | 0.79%   |
| Toshiba KBG30ZMT256G 256GB                         | 1         | 0.79%   |
| Timetec 35TTM8SSATA-512GB                          | 1         | 0.79%   |
| SPCC Solid State Disk 256GB                        | 1         | 0.79%   |
| Solid State Storage SSSTC CL1-4D256 256GB          | 1         | 0.79%   |
| SK hynix SKHynix_HFS512GD9TNI-L2B0B 512GB          | 1         | 0.79%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB          | 1         | 0.79%   |
| SK hynix SC311 SATA 256GB SSD                      | 1         | 0.79%   |
| SK hynix NVMe SSD Drive 1TB                        | 1         | 0.79%   |
| SK hynix NVMe SSD Drive 1024GB                     | 1         | 0.79%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 0.79%   |
| Seagate ST9500420AS 500GB                          | 1         | 0.79%   |
| Seagate ST9500325AS 500GB                          | 1         | 0.79%   |
| Seagate ST750LM022 HN-M750MBB 752GB                | 1         | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 15        | 15     | 36.59%  |
| WDC     | 8         | 10     | 19.51%  |
| Toshiba | 7         | 7      | 17.07%  |
| HGST    | 6         | 6      | 14.63%  |
| Hitachi | 4         | 5      | 9.76%   |
| Unknown | 1         | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 9         | 10     | 27.27%  |
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
| HDD     | 40        | 44     | 35.4%   |
| NVMe    | 39        | 59     | 34.51%  |
| SSD     | 31        | 40     | 27.43%  |
| Unknown | 2         | 3      | 1.77%   |
| MMC     | 1         | 1      | 0.88%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 66        | 85     | 61.11%  |
| NVMe | 39        | 59     | 36.11%  |
| SAS  | 2         | 2      | 1.85%   |
| MMC  | 1         | 1      | 0.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 39        | 49     | 56.52%  |
| 0.51-1.0   | 26        | 30     | 37.68%  |
| 1.01-2.0   | 3         | 4      | 4.35%   |
| 3.01-4.0   | 1         | 1      | 1.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 28        | 27.72%  |
| 101-250        | 27        | 26.73%  |
| 501-1000       | 15        | 14.85%  |
| 1001-2000      | 11        | 10.89%  |
| 51-100         | 5         | 4.95%   |
| Unknown        | 5         | 4.95%   |
| More than 3000 | 4         | 3.96%   |
| 1-20           | 4         | 3.96%   |
| 21-50          | 1         | 0.99%   |
| 2001-3000      | 1         | 0.99%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 31        | 28.7%   |
| 101-250        | 20        | 18.52%  |
| 51-100         | 15        | 13.89%  |
| 251-500        | 11        | 10.19%  |
| 21-50          | 11        | 10.19%  |
| 501-1000       | 10        | 9.26%   |
| Unknown        | 5         | 4.63%   |
| 1001-2000      | 3         | 2.78%   |
| More than 3000 | 1         | 0.93%   |
| 2001-3000      | 1         | 0.93%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 13.33%  |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 13.33%  |
| WDC WD3200LPVT-00FMCT0 320GB                     | 1         | 1      | 6.67%   |
| WDC WD10SPCX-24HWST1 1TB                         | 1         | 1      | 6.67%   |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 6.67%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 6.67%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 6.67%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 6.67%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 6.67%   |
| LDLC SSD 120GB                                   | 1         | 3      | 6.67%   |
| Hitachi HTS547550A9E384 500GB                    | 1         | 1      | 6.67%   |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 6.67%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 3         | 3      | 20%     |
| Seagate             | 3         | 3      | 20%     |
| HGST                | 3         | 3      | 20%     |
| WDC                 | 2         | 2      | 13.33%  |
| Hitachi             | 2         | 2      | 13.33%  |
| Samsung Electronics | 1         | 1      | 6.67%   |
| LDLC                | 1         | 3      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 23.08%  |
| Seagate | 3         | 3      | 23.08%  |
| HGST    | 3         | 3      | 23.08%  |
| WDC     | 2         | 2      | 15.38%  |
| Hitachi | 2         | 2      | 15.38%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 13     | 86.67%  |
| SSD  | 2         | 4      | 13.33%  |

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
| Works    | 52        | 65     | 49.06%  |
| Detected | 39        | 65     | 36.79%  |
| Malfunc  | 15        | 17     | 14.15%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 63        | 51.64%  |
| Samsung Electronics            | 18        | 14.75%  |
| AMD                            | 16        | 13.11%  |
| SanDisk                        | 5         | 4.1%    |
| SK hynix                       | 4         | 3.28%   |
| Phison Electronics             | 3         | 2.46%   |
| Kingston Technology Company    | 3         | 2.46%   |
| Union Memory (Shenzhen)        | 2         | 1.64%   |
| Toshiba America Info Systems   | 1         | 0.82%   |
| Solid State Storage Technology | 1         | 0.82%   |
| Nvidia                         | 1         | 0.82%   |
| Micron/Crucial Technology      | 1         | 0.82%   |
| Micron Technology              | 1         | 0.82%   |
| Marvell Technology Group       | 1         | 0.82%   |
| Lite-On Technology             | 1         | 0.82%   |
| ADATA Technology               | 1         | 0.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 15        | 11.81%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 9         | 7.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 8         | 6.3%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 8         | 6.3%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 7         | 5.51%   |
| Samsung NVMe SSD Controller 980                                               | 5         | 3.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 5         | 3.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 4         | 3.15%   |
| SK hynix Non-Volatile memory controller                                       | 3         | 2.36%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 3         | 2.36%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 3         | 2.36%   |
| Phison E12 NVMe Controller                                                    | 3         | 2.36%   |
| Kingston Company Company Non-Volatile memory controller                       | 3         | 2.36%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 3         | 2.36%   |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 2.36%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 3         | 2.36%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 3         | 2.36%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                        | 2         | 1.57%   |
| SanDisk Non-Volatile memory controller                                        | 2         | 1.57%   |
| Samsung Electronics SATA controller                                           | 2         | 1.57%   |
| Intel SSD 660P Series                                                         | 2         | 1.57%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 2         | 1.57%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 1.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 1.57%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.57%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 2         | 1.57%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 2         | 1.57%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                          | 1         | 0.79%   |
| Solid State Storage Non-Volatile memory controller                            | 1         | 0.79%   |
| SK hynix BC511                                                                | 1         | 0.79%   |
| Nvidia MCP79 AHCI Controller                                                  | 1         | 0.79%   |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 1         | 0.79%   |
| Micron Non-Volatile memory controller                                         | 1         | 0.79%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                    | 1         | 0.79%   |
| Lite-On Non-Volatile memory controller                                        | 1         | 0.79%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 0.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 0.79%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1         | 0.79%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 71        | 58.2%   |
| NVMe | 40        | 32.79%  |
| RAID | 11        | 9.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 80        | 81.63%  |
| AMD    | 18        | 18.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 7 4700U with Radeon Graphics      | 4         | 4.04%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 2         | 2.02%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 2.02%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 2.02%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 2.02%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 2.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 2.02%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 2.02%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 2.02%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 2.02%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 2         | 2.02%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 2.02%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 2.02%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 2.02%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz        | 1         | 1.01%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 1.01%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 1.01%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 1.01%   |
| Intel Pentium CPU A1018 @ 2.10GHz           | 1         | 1.01%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 1.01%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 1.01%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 1         | 1.01%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 1.01%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 1.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 1.01%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 1.01%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 1.01%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 1.01%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 1.01%   |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 1.01%   |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 1.01%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 1.01%   |
| Intel Core i7-10870H CPU @ 2.20GHz          | 1         | 1.01%   |
| Intel Core i7-10850H CPU @ 2.70GHz          | 1         | 1.01%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 1.01%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 1         | 1.01%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 1.01%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 1.01%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 1.01%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 26        | 26.53%  |
| Intel Core i7           | 21        | 21.43%  |
| Intel Core i3           | 10        | 10.2%   |
| AMD Ryzen 7             | 9         | 9.18%   |
| Intel Celeron           | 6         | 6.12%   |
| Other                   | 5         | 5.1%    |
| Intel Pentium           | 3         | 3.06%   |
| Intel Core m3           | 2         | 2.04%   |
| Intel Core i9           | 2         | 2.04%   |
| AMD Ryzen 5             | 2         | 2.04%   |
| AMD Ryzen 3             | 2         | 2.04%   |
| Intel Xeon              | 1         | 1.02%   |
| Intel Pentium Silver    | 1         | 1.02%   |
| Intel Pentium Dual-Core | 1         | 1.02%   |
| Intel Core 2 Duo        | 1         | 1.02%   |
| Intel Atom              | 1         | 1.02%   |
| AMD Ryzen 9             | 1         | 1.02%   |
| AMD Ryzen 5 PRO         | 1         | 1.02%   |
| AMD E1                  | 1         | 1.02%   |
| AMD Athlon              | 1         | 1.02%   |
| AMD A6                  | 1         | 1.02%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 46        | 46.94%  |
| 4      | 32        | 32.65%  |
| 8      | 11        | 11.22%  |
| 6      | 8         | 8.16%   |
| 12     | 1         | 1.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 98        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 76        | 77.55%  |
| 1      | 22        | 22.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 98        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 17%     |
| 0x306a9    | 7         | 7%      |
| 0x206a7    | 7         | 7%      |
| 0xa0652    | 5         | 5%      |
| 0x806e9    | 5         | 5%      |
| 0x40651    | 5         | 5%      |
| 0x806ec    | 4         | 4%      |
| 0x806ea    | 4         | 4%      |
| 0x806c1    | 4         | 4%      |
| 0x306d4    | 4         | 4%      |
| 0x906ea    | 3         | 3%      |
| 0x906e9    | 3         | 3%      |
| 0x706e5    | 3         | 3%      |
| 0x706a1    | 3         | 3%      |
| 0x08600106 | 3         | 3%      |
| 0x30678    | 2         | 2%      |
| 0x1067a    | 2         | 2%      |
| 0x08600103 | 2         | 2%      |
| 0x08108109 | 2         | 2%      |
| 0x906ed    | 1         | 1%      |
| 0x806eb    | 1         | 1%      |
| 0x506e3    | 1         | 1%      |
| 0x506c9    | 1         | 1%      |
| 0x406e3    | 1         | 1%      |
| 0x306c3    | 1         | 1%      |
| 0x20655    | 1         | 1%      |
| 0x0a50000c | 1         | 1%      |
| 0x08701013 | 1         | 1%      |
| 0x08600104 | 1         | 1%      |
| 0x08108102 | 1         | 1%      |
| 0x0810100b | 1         | 1%      |
| 0x08101007 | 1         | 1%      |
| 0x08001137 | 1         | 1%      |
| 0x0700010b | 1         | 1%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 27        | 27.55%  |
| Zen 2         | 8         | 8.16%   |
| IvyBridge     | 8         | 8.16%   |
| SandyBridge   | 7         | 7.14%   |
| Haswell       | 7         | 7.14%   |
| CometLake     | 6         | 6.12%   |
| Broadwell     | 5         | 5.1%    |
| Zen+          | 4         | 4.08%   |
| TigerLake     | 4         | 4.08%   |
| Zen           | 3         | 3.06%   |
| IceLake       | 3         | 3.06%   |
| Goldmont plus | 3         | 3.06%   |
| Skylake       | 2         | 2.04%   |
| Silvermont    | 2         | 2.04%   |
| Penryn        | 2         | 2.04%   |
| Zen 3         | 1         | 1.02%   |
| Westmere      | 1         | 1.02%   |
| Puma          | 1         | 1.02%   |
| Jaguar        | 1         | 1.02%   |
| Goldmont      | 1         | 1.02%   |
| Bonnell       | 1         | 1.02%   |
| Unknown       | 1         | 1.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 73        | 59.35%  |
| Nvidia | 28        | 22.76%  |
| AMD    | 22        | 17.89%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                     | 6         | 4.88%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 4.88%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 6         | 4.88%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 4.88%   |
| AMD Renoir                                                                | 6         | 4.88%   |
| Intel UHD Graphics 620                                                    | 5         | 4.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 5         | 4.07%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 3.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 3.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 3.25%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 3         | 2.44%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 2.44%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 2.44%   |
| Intel HD Graphics 5500                                                    | 3         | 2.44%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 2.44%   |
| Nvidia TU117M                                                             | 2         | 1.63%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 2         | 1.63%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 1.63%   |
| Intel UHD Graphics 615                                                    | 2         | 1.63%   |
| Intel HD Graphics 630                                                     | 2         | 1.63%   |
| Intel HD Graphics 6000                                                    | 2         | 1.63%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 1.63%   |
| AMD Saturn XT [FirePro M6100]                                             | 2         | 1.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.81%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.81%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.81%   |
| Nvidia GP108M [GeForce MX330]                                             | 1         | 0.81%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.81%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 0.81%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                  | 1         | 0.81%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.81%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.81%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                     | 1         | 0.81%   |
| Nvidia GM107 [GeForce 940MX]                                              | 1         | 0.81%   |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 0.81%   |
| Nvidia GF119M [GeForce GT 520MX]                                          | 1         | 0.81%   |
| Nvidia GF108M [GeForce GT 520M]                                           | 1         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 49        | 49.49%  |
| Intel + Nvidia | 21        | 21.21%  |
| 1 x AMD        | 19        | 19.19%  |
| 1 x Nvidia     | 6         | 6.06%   |
| Intel + AMD    | 3         | 3.03%   |
| AMD + Nvidia   | 1         | 1.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 82        | 83.67%  |
| Proprietary | 16        | 16.33%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 64.65%  |
| 1.01-2.0   | 11        | 11.11%  |
| 0.01-0.5   | 9         | 9.09%   |
| 3.01-4.0   | 5         | 5.05%   |
| 0.51-1.0   | 4         | 4.04%   |
| 5.01-6.0   | 3         | 3.03%   |
| 7.01-8.0   | 2         | 2.02%   |
| 2.01-3.0   | 1         | 1.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 21        | 18.58%  |
| LG Display              | 20        | 17.7%   |
| BOE                     | 18        | 15.93%  |
| Chimei Innolux          | 13        | 11.5%   |
| Samsung Electronics     | 6         | 5.31%   |
| Dell                    | 4         | 3.54%   |
| Chi Mei Optoelectronics | 4         | 3.54%   |
| InfoVision              | 3         | 2.65%   |
| ASUSTek Computer        | 3         | 2.65%   |
| Apple                   | 3         | 2.65%   |
| Sharp                   | 2         | 1.77%   |
| PANDA                   | 2         | 1.77%   |
| Hewlett-Packard         | 2         | 1.77%   |
| Goldstar                | 2         | 1.77%   |
| BenQ                    | 2         | 1.77%   |
| Philips                 | 1         | 0.88%   |
| MSI                     | 1         | 0.88%   |
| LGD                     | 1         | 0.88%   |
| Lenovo                  | 1         | 0.88%   |
| KDC                     | 1         | 0.88%   |
| CSO                     | 1         | 0.88%   |
| Ancor Communications    | 1         | 0.88%   |
| Acer                    | 1         | 0.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 2.65%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 1.77%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 1.77%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 1.77%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.77%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 1.77%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 1.77%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 1.77%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 1.77%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 1.77%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 1.77%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 0.88%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.88%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 0.88%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 0.88%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 0.88%   |
| Philips PHL 245E1 PHLC20B 2560x1440 530x300mm 24.0-inch                   | 1         | 0.88%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 1         | 0.88%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                   | 1         | 0.88%   |
| MSI G241VC MSI1462 1920x1080 521x294mm 23.6-inch                          | 1         | 0.88%   |
| LGD LCD Monitor 1920x1080                                                 | 1         | 0.88%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch               | 1         | 0.88%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch               | 1         | 0.88%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch               | 1         | 0.88%   |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch              | 1         | 0.88%   |
| LG Display LCD Monitor LGD03D3 1600x900 309x174mm 14.0-inch               | 1         | 0.88%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch               | 1         | 0.88%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch               | 1         | 0.88%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch               | 1         | 0.88%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch              | 1         | 0.88%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 51        | 48.11%  |
| 1366x768 (WXGA)    | 35        | 33.02%  |
| 1440x900 (WXGA+)   | 4         | 3.77%   |
| 3840x2160 (4K)     | 3         | 2.83%   |
| 2560x1600          | 3         | 2.83%   |
| 2560x1440 (QHD)    | 3         | 2.83%   |
| 1600x900 (HD+)     | 3         | 2.83%   |
| 3440x1440          | 1         | 0.94%   |
| 2160x1440          | 1         | 0.94%   |
| 1920x1200 (WUXGA)  | 1         | 0.94%   |
| 1680x1050 (WSXGA+) | 1         | 0.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 49        | 43.75%  |
| 13      | 17        | 15.18%  |
| 14      | 16        | 14.29%  |
| 17      | 8         | 7.14%   |
| 24      | 5         | 4.46%   |
| 27      | 4         | 3.57%   |
| 21      | 4         | 3.57%   |
| 23      | 2         | 1.79%   |
| 34      | 1         | 0.89%   |
| 20      | 1         | 0.89%   |
| 19      | 1         | 0.89%   |
| 16      | 1         | 0.89%   |
| 12      | 1         | 0.89%   |
| 11      | 1         | 0.89%   |
| Unknown | 1         | 0.89%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 75        | 66.96%  |
| 501-600     | 10        | 8.93%   |
| 351-400     | 10        | 8.93%   |
| 201-300     | 8         | 7.14%   |
| 401-500     | 6         | 5.36%   |
| 701-800     | 1         | 0.89%   |
| 601-700     | 1         | 0.89%   |
| Unknown     | 1         | 0.89%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 86        | 87.76%  |
| 16/10   | 9         | 9.18%   |
| 3/2     | 1         | 1.02%   |
| 21/9    | 1         | 1.02%   |
| Unknown | 1         | 1.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 49        | 43.75%  |
| 81-90          | 27        | 24.11%  |
| 201-250        | 10        | 8.93%   |
| 121-130        | 7         | 6.25%   |
| 71-80          | 6         | 5.36%   |
| 301-350        | 4         | 3.57%   |
| 151-200        | 2         | 1.79%   |
| 61-70          | 1         | 0.89%   |
| 51-60          | 1         | 0.89%   |
| 351-500        | 1         | 0.89%   |
| 251-300        | 1         | 0.89%   |
| 131-140        | 1         | 0.89%   |
| 111-120        | 1         | 0.89%   |
| Unknown        | 1         | 0.89%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 52        | 47.27%  |
| 101-120       | 34        | 30.91%  |
| 51-100        | 16        | 14.55%  |
| 161-240       | 6         | 5.45%   |
| More than 240 | 1         | 0.91%   |
| Unknown       | 1         | 0.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 85        | 84.16%  |
| 2     | 16        | 15.84%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 64        | 39.26%  |
| Intel                 | 53        | 32.52%  |
| Qualcomm Atheros      | 19        | 11.66%  |
| Broadcom              | 9         | 5.52%   |
| Broadcom Limited      | 4         | 2.45%   |
| Samsung Electronics   | 2         | 1.23%   |
| Ralink                | 2         | 1.23%   |
| MediaTek              | 2         | 1.23%   |
| Xiaomi                | 1         | 0.61%   |
| Sierra Wireless       | 1         | 0.61%   |
| Ralink Technology     | 1         | 0.61%   |
| Qualcomm              | 1         | 0.61%   |
| OPPO Electronics      | 1         | 0.61%   |
| Linksys               | 1         | 0.61%   |
| Huawei Technologies   | 1         | 0.61%   |
| Apple                 | 1         | 0.61%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 20.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 6.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 3.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 3.17%   |
| Intel Wireless 8265 / 8275                                        | 6         | 3.17%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 3.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 2.65%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.12%   |
| Intel Wireless 7265                                               | 4         | 2.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 2.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.59%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.59%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.06%   |
| Realtek 802.11ac NIC                                              | 2         | 1.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.06%   |
| Intel Wireless 7260                                               | 2         | 1.06%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 1.06%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.06%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 1.06%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 1.06%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.53%   |
| Sierra Wireless MC7750                                            | 1         | 0.53%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.53%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 48.04%  |
| Realtek Semiconductor | 19        | 18.63%  |
| Qualcomm Atheros      | 16        | 15.69%  |
| Broadcom              | 8         | 7.84%   |
| Broadcom Limited      | 4         | 3.92%   |
| Ralink                | 2         | 1.96%   |
| MediaTek              | 2         | 1.96%   |
| Sierra Wireless       | 1         | 0.98%   |
| Ralink Technology     | 1         | 0.98%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 5.88%   |
| Intel Wireless 8265 / 8275                                     | 6         | 5.88%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 5.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 4.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 4.9%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 4.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 3.92%   |
| Intel Wireless 7265                                            | 4         | 3.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 3.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2.94%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 2.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 2.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.94%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 2.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.96%   |
| Realtek 802.11ac NIC                                           | 2         | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.96%   |
| Intel Wireless 7260                                            | 2         | 1.96%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.96%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 1.96%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.96%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.96%   |
| Sierra Wireless MC7750                                         | 1         | 0.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.98%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.98%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.98%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.98%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.98%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1         | 0.98%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.98%   |
| Intel Wireless-AC 9260                                         | 1         | 0.98%   |
| Intel Wireless 3165                                            | 1         | 0.98%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 0.98%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 0.98%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 56        | 65.88%  |
| Intel                 | 16        | 18.82%  |
| Qualcomm Atheros      | 4         | 4.71%   |
| Samsung Electronics   | 2         | 2.35%   |
| Xiaomi                | 1         | 1.18%   |
| Qualcomm              | 1         | 1.18%   |
| OPPO Electronics      | 1         | 1.18%   |
| Linksys               | 1         | 1.18%   |
| Huawei Technologies   | 1         | 1.18%   |
| Broadcom              | 1         | 1.18%   |
| Apple                 | 1         | 1.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 44.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 13.79%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 6.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 6.9%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 3.45%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 2.3%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.15%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.15%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.15%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.15%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.15%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.15%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.15%   |
| Qualcomm A0001                                                    | 1         | 1.15%   |
| OPPO RMX2180                                                      | 1         | 1.15%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 1.15%   |
| Intel WiMAX Connection 2400m                                      | 1         | 1.15%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.15%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.15%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.15%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.15%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.15%   |
| Huawei E353/E3131                                                 | 1         | 1.15%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.15%   |
| Apple iPad 4/Mini1                                                | 1         | 1.15%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 96        | 55.49%  |
| Ethernet | 77        | 44.51%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 78.22%  |
| Ethernet | 22        | 21.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 69        | 69.7%   |
| 1     | 27        | 27.27%  |
| 3     | 2         | 2.02%   |
| 0     | 1         | 1.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 87        | 86.14%  |
| Yes  | 14        | 13.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 51.25%  |
| Realtek Semiconductor           | 12        | 15%     |
| Broadcom                        | 6         | 7.5%    |
| Qualcomm Atheros Communications | 4         | 5%      |
| Lite-On Technology              | 4         | 5%      |
| IMC Networks                    | 3         | 3.75%   |
| Foxconn / Hon Hai               | 3         | 3.75%   |
| Apple                           | 3         | 3.75%   |
| Realtek                         | 2         | 2.5%    |
| Ralink                          | 1         | 1.25%   |
| Cambridge Silicon Radio         | 1         | 1.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 15%     |
| Intel AX201 Bluetooth                               | 11        | 13.75%  |
| Realtek Bluetooth Radio                             | 7         | 8.75%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7         | 8.75%   |
| Intel AX200 Bluetooth                               | 6         | 7.5%    |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 5%      |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 3.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 3.75%   |
| Realtek Bluetooth Radio                             | 2         | 2.5%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.5%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.5%    |
| IMC Networks Wireless_Device                        | 2         | 2.5%    |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 2.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.5%    |
| Apple Bluetooth USB Host Controller                 | 2         | 2.5%    |
| Realtek RTL8821A Bluetooth                          | 1         | 1.25%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.25%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.25%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.25%   |
| IMC Networks Bluetooth Device                       | 1         | 1.25%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.25%   |
| Broadcom HP Portable Valentine                      | 1         | 1.25%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.25%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.25%   |
| Apple Bluetooth Host Controller                     | 1         | 1.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 79        | 63.2%   |
| AMD                   | 20        | 16%     |
| Nvidia                | 18        | 14.4%   |
| C-Media Electronics   | 3         | 2.4%    |
| Realtek Semiconductor | 2         | 1.6%    |
| Plantronics           | 1         | 0.8%    |
| Harman                | 1         | 0.8%    |
| Corsair               | 1         | 0.8%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 14        | 9.03%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14        | 9.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 5.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 4.52%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 3.87%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 3.87%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 3.87%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 3.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 3.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 3.23%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 3.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 2.58%   |
| Intel CM238 HD Audio Controller                                            | 4         | 2.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.58%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.58%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.94%   |
| Realtek Semiconductor USB Audio                                            | 2         | 1.29%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.29%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.29%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.29%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 1.29%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 2         | 1.29%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.29%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.29%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.65%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.65%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.65%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.65%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.65%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.65%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.65%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 27.88%  |
| SK hynix            | 28        | 26.92%  |
| Micron Technology   | 10        | 9.62%   |
| Kingston            | 10        | 9.62%   |
| Unknown             | 4         | 3.85%   |
| A-DATA Technology   | 4         | 3.85%   |
| Silicon Power       | 3         | 2.88%   |
| Unknown             | 3         | 2.88%   |
| Unknown (ABCD)      | 2         | 1.92%   |
| Smart               | 2         | 1.92%   |
| Ramaxel Technology  | 2         | 1.92%   |
| Nanya Technology    | 2         | 1.92%   |
| Corsair             | 2         | 1.92%   |
| Team                | 1         | 0.96%   |
| Smart Brazil        | 1         | 0.96%   |
| ASint Technology    | 1         | 0.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 3.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.75%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 2.75%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 2.75%   |
| Unknown                                                          | 3         | 2.75%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.83%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.83%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.83%   |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.83%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.83%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.83%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 2         | 1.83%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 2         | 1.83%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 1.83%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.83%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.83%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 2         | 1.83%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.83%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.92%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.92%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.92%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.92%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.92%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 1         | 0.92%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2400MT/s            | 1         | 0.92%   |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 2933MT/s  | 1         | 0.92%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.92%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.92%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.92%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.92%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.92%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.92%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.92%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.92%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.92%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.92%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.92%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 0.92%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.92%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 47        | 55.29%  |
| DDR3    | 28        | 32.94%  |
| LPDDR4  | 4         | 4.71%   |
| LPDDR3  | 3         | 3.53%   |
| SDRAM   | 2         | 2.35%   |
| Unknown | 1         | 1.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 75        | 87.21%  |
| Row Of Chips | 8         | 9.3%    |
| DIMM         | 1         | 1.16%   |
| Chip         | 1         | 1.16%   |
| Unknown      | 1         | 1.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 39        | 39.39%  |
| 8192  | 32        | 32.32%  |
| 16384 | 14        | 14.14%  |
| 2048  | 11        | 11.11%  |
| 32768 | 2         | 2.02%   |
| 1024  | 1         | 1.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 26        | 28.57%  |
| 3200  | 19        | 20.88%  |
| 2667  | 19        | 20.88%  |
| 2400  | 10        | 10.99%  |
| 1333  | 4         | 4.4%    |
| 2133  | 3         | 3.3%    |
| 1334  | 3         | 3.3%    |
| 4199  | 2         | 2.2%    |
| 4267  | 1         | 1.1%    |
| 3400  | 1         | 1.1%    |
| 3266  | 1         | 1.1%    |
| 2933  | 1         | 1.1%    |
| 1066  | 1         | 1.1%    |

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
| Chicony Electronics                    | 19        | 22.09%  |
| Realtek Semiconductor                  | 9         | 10.47%  |
| Quanta                                 | 9         | 10.47%  |
| Acer                                   | 9         | 10.47%  |
| IMC Networks                           | 8         | 9.3%    |
| Suyin                                  | 6         | 6.98%   |
| Alcor Micro                            | 4         | 4.65%   |
| Syntek                                 | 3         | 3.49%   |
| Sunplus Innovation Technology          | 3         | 3.49%   |
| Microdia                               | 3         | 3.49%   |
| Luxvisions Innotech Limited            | 3         | 3.49%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.49%   |
| Sonix Technology                       | 2         | 2.33%   |
| Silicon Motion                         | 2         | 2.33%   |
| Lite-On Technology                     | 1         | 1.16%   |
| LG Electronics                         | 1         | 1.16%   |
| Lenovo                                 | 1         | 1.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                        | 6         | 6.98%   |
| Chicony HD WebCam                                     | 6         | 6.98%   |
| Realtek Integrated_Webcam_HD                          | 4         | 4.65%   |
| Chicony Integrated Camera                             | 4         | 4.65%   |
| Acer Integrated Camera                                | 3         | 3.49%   |
| Syntek EasyCamera                                     | 2         | 2.33%   |
| Suyin HP Webcam                                       | 2         | 2.33%   |
| Sonix USB2.0 HD UVC WebCam                            | 2         | 2.33%   |
| Silicon Motion 300k Pixel Camera                      | 2         | 2.33%   |
| Realtek USB2.0 HD UVC WebCam                          | 2         | 2.33%   |
| Realtek HD WebCam                                     | 2         | 2.33%   |
| Quanta VGA WebCam                                     | 2         | 2.33%   |
| Quanta HP Webcam                                      | 2         | 2.33%   |
| Quanta HP TrueVision HD Camera                        | 2         | 2.33%   |
| Microdia Integrated Webcam                            | 2         | 2.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera   | 2         | 2.33%   |
| Chicony USB2.0 VGA UVC WebCam                         | 2         | 2.33%   |
| Chicony Integrated Camera (1280x720@30)               | 2         | 2.33%   |
| Syntek Integrated Camera                              | 1         | 1.16%   |
| Suyin USB Webcam                                      | 1         | 1.16%   |
| Suyin NEC HD WebCam                                   | 1         | 1.16%   |
| Suyin Laptop_Integrated_Webcam_HD                     | 1         | 1.16%   |
| Suyin 1.3M HD WebCam                                  | 1         | 1.16%   |
| Sunplus Laptop_Integrated_Webcam_FHD                  | 1         | 1.16%   |
| Sunplus Integrated_Webcam_HD                          | 1         | 1.16%   |
| Sunplus HD WebCam                                     | 1         | 1.16%   |
| Realtek Integrated Webcam                             | 1         | 1.16%   |
| Quanta USB2.0 VGA UVC WebCam                          | 1         | 1.16%   |
| Quanta HD Webcam                                      | 1         | 1.16%   |
| Quanta HD User Facing                                 | 1         | 1.16%   |
| Microdia Integrated_Webcam_HD                         | 1         | 1.16%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera  | 1         | 1.16%   |
| Lite-On HP HD Camera                                  | 1         | 1.16%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1         | 1.16%   |
| Lenovo UVC Camera                                     | 1         | 1.16%   |
| IMC Networks USB2.0 VGA UVC WebCam                    | 1         | 1.16%   |
| IMC Networks Integrated Webcam                        | 1         | 1.16%   |
| Chicony USB2.0 Camera                                 | 1         | 1.16%   |
| Chicony USB2.0 0.3M UVC WebCam                        | 1         | 1.16%   |
| Chicony Thinkpad T430 camera                          | 1         | 1.16%   |

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
| 0     | 68        | 67.33%  |
| 1     | 28        | 27.72%  |
| 2     | 5         | 4.95%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 7         | 17.95%  |
| Net/wireless             | 5         | 12.82%  |
| Graphics card            | 5         | 12.82%  |
| Camera                   | 5         | 12.82%  |
| Multimedia controller    | 4         | 10.26%  |
| Chipcard                 | 4         | 10.26%  |
| Bluetooth                | 4         | 10.26%  |
| Storage                  | 2         | 5.13%   |
| Network                  | 1         | 2.56%   |
| Dvb card                 | 1         | 2.56%   |
| Communication controller | 1         | 2.56%   |

