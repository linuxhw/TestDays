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

Total: 148

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A315-56              | [a1ec8cb1b2](https://linux-hardware.org/?probe=a1ec8cb1b2) | Nov 29, 2022 |
| ASUSTek       | N53SV                       | [f42473e3f6](https://linux-hardware.org/?probe=f42473e3f6) | Nov 14, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [75c1d24fcd](https://linux-hardware.org/?probe=75c1d24fcd) | Nov 13, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [189dd51cc3](https://linux-hardware.org/?probe=189dd51cc3) | Nov 13, 2022 |
| Samsung       | R425D/R525D                 | [85d17374e7](https://linux-hardware.org/?probe=85d17374e7) | Nov 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [31e940a232](https://linux-hardware.org/?probe=31e940a232) | Nov 10, 2022 |
| HP            | Pavilion 15                 | [93ef42ccbf](https://linux-hardware.org/?probe=93ef42ccbf) | Nov 03, 2022 |
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
| Artix Rolling  | 63        | 58.33%  |
| Artix          | 41        | 37.96%  |
| Artix 20220713 | 1         | 0.93%   |
| Artix 20220123 | 1         | 0.93%   |
| Artix 20201207 | 1         | 0.93%   |
| Artix 20201128 | 1         | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Artix | 103       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.9.14-artix1-1                 | 6         | 4.92%   |
| 5.7.6-artix1-1                  | 3         | 2.46%   |
| 5.7.12-artix1-1                 | 2         | 1.64%   |
| 5.19.12-artix1-1                | 2         | 1.64%   |
| 5.18.6-artix1-1                 | 2         | 1.64%   |
| 5.18.0-artix1-1                 | 2         | 1.64%   |
| 5.17.1-artix1-1                 | 2         | 1.64%   |
| 5.16.8-artix1-2                 | 2         | 1.64%   |
| 5.16.10-artix1-1                | 2         | 1.64%   |
| 5.15.12-artix1-1                | 2         | 1.64%   |
| 5.14.16-artix1-1                | 2         | 1.64%   |
| 5.13.8-artix1-1                 | 2         | 1.64%   |
| 5.12.8-artix1-1                 | 2         | 1.64%   |
| 5.12.12-zen1-1-zen              | 2         | 1.64%   |
| 5.12.12-artix1-1                | 2         | 1.64%   |
| 5.11.6-artix1-1                 | 2         | 1.64%   |
| 5.10.6-artix1-1                 | 2         | 1.64%   |
| 5.10.4-artix2-1                 | 2         | 1.64%   |
| 5.10.16-artix1-1                | 2         | 1.64%   |
| 6.0.9-hardened1-1-hardened      | 1         | 0.82%   |
| 6.0.7-zen1-1-zen                | 1         | 0.82%   |
| 6.0.7-artix1-1                  | 1         | 0.82%   |
| 6.0.5.14.realtime1-1-rt         | 1         | 0.82%   |
| 6.0.2-artix1-1.1                | 1         | 0.82%   |
| 5.9.6-artix1-1                  | 1         | 0.82%   |
| 5.9.14-zen1-1-zen               | 1         | 0.82%   |
| 5.9.12-artix1-1                 | 1         | 0.82%   |
| 5.9.1-artix1-1                  | 1         | 0.82%   |
| 5.9.0-zen1-1-zen                | 1         | 0.82%   |
| 5.9.0-1-mainline-bootsplash     | 1         | 0.82%   |
| 5.8.8-artix1-1                  | 1         | 0.82%   |
| 5.8.4-artix1-1                  | 1         | 0.82%   |
| 5.8.14-zen1-1-zen               | 1         | 0.82%   |
| 5.8.14-artix1-1                 | 1         | 0.82%   |
| 5.8.12-artix1-1                 | 1         | 0.82%   |
| 5.8.0-rc7-5-mainline-bootsplash | 1         | 0.82%   |
| 5.7.8-artix1-1                  | 1         | 0.82%   |
| 5.7.2-artix1-1                  | 1         | 0.82%   |
| 5.6.7-x86_64                    | 1         | 0.82%   |
| 5.5.3-artix1-1                  | 1         | 0.82%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.9.14   | 7         | 5.74%   |
| 5.12.12  | 4         | 3.28%   |
| 5.7.6    | 3         | 2.46%   |
| 5.17.1   | 3         | 2.46%   |
| 5.15.12  | 3         | 2.46%   |
| 5.12.8   | 3         | 2.46%   |
| 6.0.7    | 2         | 1.64%   |
| 5.9.0    | 2         | 1.64%   |
| 5.8.14   | 2         | 1.64%   |
| 5.7.12   | 2         | 1.64%   |
| 5.19.12  | 2         | 1.64%   |
| 5.18.6   | 2         | 1.64%   |
| 5.18.0   | 2         | 1.64%   |
| 5.16.8   | 2         | 1.64%   |
| 5.16.10  | 2         | 1.64%   |
| 5.14.16  | 2         | 1.64%   |
| 5.13.8   | 2         | 1.64%   |
| 5.12.14  | 2         | 1.64%   |
| 5.11.6   | 2         | 1.64%   |
| 5.10.6   | 2         | 1.64%   |
| 5.10.4   | 2         | 1.64%   |
| 5.10.16  | 2         | 1.64%   |
| 6.0.9    | 1         | 0.82%   |
| 6.0.5.14 | 1         | 0.82%   |
| 6.0.2    | 1         | 0.82%   |
| 5.9.6    | 1         | 0.82%   |
| 5.9.12   | 1         | 0.82%   |
| 5.9.1    | 1         | 0.82%   |
| 5.8.8    | 1         | 0.82%   |
| 5.8.4    | 1         | 0.82%   |
| 5.8.12   | 1         | 0.82%   |
| 5.8.0    | 1         | 0.82%   |
| 5.7.8    | 1         | 0.82%   |
| 5.7.2    | 1         | 0.82%   |
| 5.6.7    | 1         | 0.82%   |
| 5.5.3    | 1         | 0.82%   |
| 5.5.10   | 1         | 0.82%   |
| 5.4.74   | 1         | 0.82%   |
| 5.19.8   | 1         | 0.82%   |
| 5.19.2   | 1         | 0.82%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 13        | 11.21%  |
| 5.12    | 12        | 10.34%  |
| 5.9     | 11        | 9.48%   |
| 5.18    | 11        | 9.48%   |
| 5.10    | 11        | 9.48%   |
| 5.17    | 8         | 6.9%    |
| 5.16    | 8         | 6.9%    |
| 5.11    | 8         | 6.9%    |
| 5.7     | 6         | 5.17%   |
| 5.19    | 6         | 5.17%   |
| 5.8     | 5         | 4.31%   |
| 6.0     | 4         | 3.45%   |
| 5.14    | 4         | 3.45%   |
| 5.13    | 4         | 3.45%   |
| 6.0.5   | 1         | 0.86%   |
| 5.6     | 1         | 0.86%   |
| 5.5     | 1         | 0.86%   |
| 5.4     | 1         | 0.86%   |
| 4.19    | 1         | 0.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 103       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| KDE5           | 24        | 22.02%  |
| XFCE           | 18        | 16.51%  |
| Unknown        | 18        | 16.51%  |
| GNOME          | 14        | 12.84%  |
| X-Cinnamon     | 7         | 6.42%   |
| MATE           | 4         | 3.67%   |
| LXQt           | 4         | 3.67%   |
| KDE            | 4         | 3.67%   |
| LXDE           | 3         | 2.75%   |
| Cinnamon       | 3         | 2.75%   |
| i3             | 2         | 1.83%   |
| bspwm          | 2         | 1.83%   |
| xmonad         | 1         | 0.92%   |
| sway-dbus      | 1         | 0.92%   |
| Sway           | 1         | 0.92%   |
| nxde           | 1         | 0.92%   |
| awesomeminimal | 1         | 0.92%   |
| awesome        | 1         | 0.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 75        | 70.09%  |
| Tty     | 15        | 14.02%  |
| Wayland | 11        | 10.28%  |
| Unknown | 6         | 5.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 38        | 36.19%  |
| LightDM | 34        | 32.38%  |
| SDDM    | 28        | 26.67%  |
| XDM     | 1         | 0.95%   |
| SLiM    | 1         | 0.95%   |
| Ly      | 1         | 0.95%   |
| LXDM    | 1         | 0.95%   |
| GDM     | 1         | 0.95%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 53        | 49.53%  |
| Unknown | 12        | 11.21%  |
| ru_RU   | 8         | 7.48%   |
| en_GB   | 7         | 6.54%   |
| C       | 4         | 3.74%   |
| fr_FR   | 3         | 2.8%    |
| es_ES   | 2         | 1.87%   |
| en_CA   | 2         | 1.87%   |
| en_AG   | 2         | 1.87%   |
| uk_UA   | 1         | 0.93%   |
| tr_TR   | 1         | 0.93%   |
| pt_PT   | 1         | 0.93%   |
| pt_BR   | 1         | 0.93%   |
| pl_PL   | 1         | 0.93%   |
| it_IT   | 1         | 0.93%   |
| es_GT   | 1         | 0.93%   |
| es_CO   | 1         | 0.93%   |
| en_NZ   | 1         | 0.93%   |
| en_IN   | 1         | 0.93%   |
| en_AU   | 1         | 0.93%   |
| el_GR   | 1         | 0.93%   |
| de_DE   | 1         | 0.93%   |
| cs_CZ   | 1         | 0.93%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 74        | 71.15%  |
| BIOS | 30        | 28.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 77        | 74.04%  |
| Btrfs   | 21        | 20.19%  |
| Xfs     | 3         | 2.88%   |
| Overlay | 2         | 1.92%   |
| F2fs    | 1         | 0.96%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 73        | 70.19%  |
| MBR     | 16        | 15.38%  |
| Unknown | 15        | 14.42%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 89        | 85.58%  |
| Yes       | 15        | 14.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 77        | 74.76%  |
| Yes       | 26        | 25.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 27        | 26.21%  |
| Hewlett-Packard     | 16        | 15.53%  |
| Dell                | 14        | 13.59%  |
| Acer                | 13        | 12.62%  |
| ASUSTek Computer    | 12        | 11.65%  |
| MSI                 | 3         | 2.91%   |
| Apple               | 3         | 2.91%   |
| Timi                | 2         | 1.94%   |
| Notebook            | 2         | 1.94%   |
| GPD                 | 2         | 1.94%   |
| Gigabyte Technology | 2         | 1.94%   |
| UNOWHY              | 1         | 0.97%   |
| Samsung Electronics | 1         | 0.97%   |
| Quanta              | 1         | 0.97%   |
| MOTILE              | 1         | 0.97%   |
| LG Electronics      | 1         | 0.97%   |
| HUAWEI              | 1         | 0.97%   |
| AXIOO               | 1         | 0.97%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Timi RedmiBook 14 II                   | 2         | 1.94%   |
| Lenovo IdeaPad 5 15IIL05 81YK          | 2         | 1.94%   |
| HP 15                                  | 2         | 1.94%   |
| GPD P2 MAX                             | 2         | 1.94%   |
| Dell Precision M6600                   | 2         | 1.94%   |
| Dell Precision 7550                    | 2         | 1.94%   |
| Apple MacBookAir7,2                    | 2         | 1.94%   |
| UNOWHY Y13G010S4EI                     | 1         | 0.97%   |
| Samsung R425D/R525D                    | 1         | 0.97%   |
| Quanta SWH                             | 1         | 0.97%   |
| Notebook N141CU                        | 1         | 0.97%   |
| Notebook N130BU                        | 1         | 0.97%   |
| MSI Modern 15 A11M                     | 1         | 0.97%   |
| MSI GP72 7RDX                          | 1         | 0.97%   |
| MSI GF65 Thin 10SDR                    | 1         | 0.97%   |
| MOTILE M141                            | 1         | 0.97%   |
| LG 17Z990-R.AAC9U1                     | 1         | 0.97%   |
| Lenovo ThinkPad W500 4063CJ5           | 1         | 0.97%   |
| Lenovo ThinkPad T480s 20L8S3D400       | 1         | 0.97%   |
| Lenovo ThinkPad T480 MFG_IN_GO         | 1         | 0.97%   |
| Lenovo ThinkPad T440s 20ARS0MV00       | 1         | 0.97%   |
| Lenovo ThinkPad T430 2350BC6           | 1         | 0.97%   |
| Lenovo ThinkPad T430 2347H76           | 1         | 0.97%   |
| Lenovo ThinkPad T420 4236H45           | 1         | 0.97%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00   | 1         | 0.97%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800   | 1         | 0.97%   |
| Lenovo ThinkPad P1 Gen 3 20TH001EMH    | 1         | 0.97%   |
| Lenovo ThinkPad E14 Gen 2 20T6000MCK   | 1         | 0.97%   |
| Lenovo ThinkPad 11e 5th Gen 20LNS0P500 | 1         | 0.97%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 1         | 0.97%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 0.97%   |
| Lenovo LaVie Z 20FF0012US              | 1         | 0.97%   |
| Lenovo IdeaPad Y500 20193              | 1         | 0.97%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL  | 1         | 0.97%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG   | 1         | 0.97%   |
| Lenovo IdeaPad 510-15IKB 80SV          | 1         | 0.97%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5       | 1         | 0.97%   |
| Lenovo IdeaPad 5 14ITL05 82FE          | 1         | 0.97%   |
| Lenovo IdeaPad 330-15IKB 81DE          | 1         | 0.97%   |
| Lenovo G400s 20244                     | 1         | 0.97%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 12        | 11.65%  |
| Lenovo IdeaPad     | 9         | 8.74%   |
| Acer Aspire        | 9         | 8.74%   |
| Dell Precision     | 6         | 5.83%   |
| HP Laptop          | 5         | 4.85%   |
| Dell Latitude      | 4         | 3.88%   |
| Dell Inspiron      | 4         | 3.88%   |
| HP 250             | 3         | 2.91%   |
| Timi RedmiBook     | 2         | 1.94%   |
| HP Pavilion        | 2         | 1.94%   |
| HP 15              | 2         | 1.94%   |
| GPD P2             | 2         | 1.94%   |
| ASUS VivoBook      | 2         | 1.94%   |
| ASUS ASUS          | 2         | 1.94%   |
| Apple MacBookAir7  | 2         | 1.94%   |
| Acer Nitro         | 2         | 1.94%   |
| UNOWHY Y13G010S4EI | 1         | 0.97%   |
| Samsung R425D      | 1         | 0.97%   |
| Quanta SWH         | 1         | 0.97%   |
| Notebook N141CU    | 1         | 0.97%   |
| Notebook N130BU    | 1         | 0.97%   |
| MSI Modern         | 1         | 0.97%   |
| MSI GP72           | 1         | 0.97%   |
| MSI GF65           | 1         | 0.97%   |
| MOTILE M141        | 1         | 0.97%   |
| LG 17Z990-R.AAC9U1 | 1         | 0.97%   |
| Lenovo ThinkBook   | 1         | 0.97%   |
| Lenovo Legion      | 1         | 0.97%   |
| Lenovo LaVie       | 1         | 0.97%   |
| Lenovo G400s       | 1         | 0.97%   |
| Lenovo B590        | 1         | 0.97%   |
| Lenovo B570e       | 1         | 0.97%   |
| HUAWEI WRT-WX9     | 1         | 0.97%   |
| HP ProBook         | 1         | 0.97%   |
| HP OMEN            | 1         | 0.97%   |
| HP 255             | 1         | 0.97%   |
| HP 246             | 1         | 0.97%   |
| Gigabyte B450M     | 1         | 0.97%   |
| Gigabyte AERO      | 1         | 0.97%   |
| AXIOO Mybook       | 1         | 0.97%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 25        | 24.27%  |
| 2018 | 13        | 12.62%  |
| 2019 | 10        | 9.71%   |
| 2017 | 8         | 7.77%   |
| 2011 | 8         | 7.77%   |
| 2014 | 7         | 6.8%    |
| 2013 | 7         | 6.8%    |
| 2012 | 7         | 6.8%    |
| 2015 | 5         | 4.85%   |
| 2021 | 4         | 3.88%   |
| 2016 | 4         | 3.88%   |
| 2010 | 3         | 2.91%   |
| 2022 | 1         | 0.97%   |
| 2009 | 1         | 0.97%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 103       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 102       | 99.03%  |
| Enabled  | 1         | 0.97%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 103       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 31        | 29.81%  |
| 8.01-16.0   | 24        | 23.08%  |
| 16.01-24.0  | 19        | 18.27%  |
| 3.01-4.0    | 17        | 16.35%  |
| 32.01-64.0  | 4         | 3.85%   |
| 1.01-2.0    | 4         | 3.85%   |
| 64.01-256.0 | 3         | 2.88%   |
| 24.01-32.0  | 2         | 1.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 31        | 26.72%  |
| 2.01-3.0   | 28        | 24.14%  |
| 4.01-8.0   | 24        | 20.69%  |
| 3.01-4.0   | 15        | 12.93%  |
| 0.51-1.0   | 11        | 9.48%   |
| 8.01-16.0  | 4         | 3.45%   |
| 0.01-0.5   | 2         | 1.72%   |
| 16.01-24.0 | 1         | 0.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 81        | 77.88%  |
| 2      | 22        | 21.15%  |
| 3      | 1         | 0.96%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 76        | 73.79%  |
| Yes       | 27        | 26.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 78.64%  |
| No        | 22        | 21.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 98.06%  |
| No        | 2         | 1.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 80.95%  |
| No        | 20        | 19.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 22        | 21.36%  |
| Russia      | 11        | 10.68%  |
| India       | 6         | 5.83%   |
| Turkey      | 5         | 4.85%   |
| Brazil      | 5         | 4.85%   |
| UK          | 4         | 3.88%   |
| Indonesia   | 4         | 3.88%   |
| Germany     | 4         | 3.88%   |
| Canada      | 4         | 3.88%   |
| Ukraine     | 3         | 2.91%   |
| Netherlands | 3         | 2.91%   |
| France      | 3         | 2.91%   |
| Switzerland | 2         | 1.94%   |
| Spain       | 2         | 1.94%   |
| Poland      | 2         | 1.94%   |
| Italy       | 2         | 1.94%   |
| Czechia     | 2         | 1.94%   |
| Bulgaria    | 2         | 1.94%   |
| Uzbekistan  | 1         | 0.97%   |
| Sweden      | 1         | 0.97%   |
| Romania     | 1         | 0.97%   |
| Peru        | 1         | 0.97%   |
| Lithuania   | 1         | 0.97%   |
| Israel      | 1         | 0.97%   |
| Iran        | 1         | 0.97%   |
| Guatemala   | 1         | 0.97%   |
| Greece      | 1         | 0.97%   |
| Colombia    | 1         | 0.97%   |
| China       | 1         | 0.97%   |
| Chile       | 1         | 0.97%   |
| Bangladesh  | 1         | 0.97%   |
| Azerbaijan  | 1         | 0.97%   |
| Australia   | 1         | 0.97%   |
| Argentina   | 1         | 0.97%   |
| Algeria     | 1         | 0.97%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 3         | 2.75%   |
| Jakarta           | 3         | 2.75%   |
| St Petersburg     | 2         | 1.83%   |
| San Ramon         | 2         | 1.83%   |
| Samara            | 2         | 1.83%   |
| Rio de Janeiro    | 2         | 1.83%   |
| Prague            | 2         | 1.83%   |
| Omaha             | 2         | 1.83%   |
| Neuchatel         | 2         | 1.83%   |
| Moscow            | 2         | 1.83%   |
| Los Angeles       | 2         | 1.83%   |
| Frankfurt am Main | 2         | 1.83%   |
| Dnipro            | 2         | 1.83%   |
| Ankara            | 2         | 1.83%   |
| Amsterdam         | 2         | 1.83%   |
| Zaporizhzhya      | 1         | 0.92%   |
| Wigan             | 1         | 0.92%   |
| Wem               | 1         | 0.92%   |
| Vilnius           | 1         | 0.92%   |
| Varna             | 1         | 0.92%   |
| Vancouver         | 1         | 0.92%   |
| Toronto           | 1         | 0.92%   |
| Timișoara        | 1         | 0.92%   |
| Tel Aviv          | 1         | 0.92%   |
| Tashkent          | 1         | 0.92%   |
| Syeverodonets'k   | 1         | 0.92%   |
| Surgut            | 1         | 0.92%   |
| Stuttgart         | 1         | 0.92%   |
| Stockholm         | 1         | 0.92%   |
| Sofia             | 1         | 0.92%   |
| Snohomish         | 1         | 0.92%   |
| Skikda            | 1         | 0.92%   |
| Sigogne           | 1         | 0.92%   |
| Seville           | 1         | 0.92%   |
| Semarang          | 1         | 0.92%   |
| Seattle           | 1         | 0.92%   |
| Santiago          | 1         | 0.92%   |
| Santa Marta       | 1         | 0.92%   |
| Santa Fe          | 1         | 0.92%   |
| Sainte-Severe     | 1         | 0.92%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 27        | 33     | 21.26%  |
| Seagate                   | 16        | 16     | 12.6%   |
| WDC                       | 11        | 14     | 8.66%   |
| Toshiba                   | 9         | 9      | 7.09%   |
| SanDisk                   | 6         | 6      | 4.72%   |
| Kingston                  | 6         | 7      | 4.72%   |
| Intel                     | 6         | 8      | 4.72%   |
| HGST                      | 6         | 6      | 4.72%   |
| SK hynix                  | 5         | 11     | 3.94%   |
| Hitachi                   | 4         | 5      | 3.15%   |
| China                     | 4         | 4      | 3.15%   |
| Phison Electronics        | 3         | 4      | 2.36%   |
| Apple                     | 3         | 4      | 2.36%   |
| Unknown                   | 2         | 2      | 1.57%   |
| Crucial                   | 2         | 2      | 1.57%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.79%   |
| Timetec                   | 1         | 2      | 0.79%   |
| SPCC                      | 1         | 1      | 0.79%   |
| Solid State Storage       | 1         | 1      | 0.79%   |
| PNY                       | 1         | 1      | 0.79%   |
| Phison                    | 1         | 1      | 0.79%   |
| Patriot                   | 1         | 1      | 0.79%   |
| Micron/Crucial Technology | 1         | 1      | 0.79%   |
| Micron Technology         | 1         | 1      | 0.79%   |
| LITEON                    | 1         | 1      | 0.79%   |
| Lite-On                   | 1         | 1      | 0.79%   |
| Linux                     | 1         | 1      | 0.79%   |
| LDLC                      | 1         | 5      | 0.79%   |
| Intenso                   | 1         | 1      | 0.79%   |
| AGI                       | 1         | 1      | 0.79%   |
| A-DATA Technology         | 1         | 1      | 0.79%   |
| Unknown                   | 1         | 1      | 0.79%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 4         | 3.01%   |
| SanDisk NVMe SSD Drive 512GB                       | 4         | 3.01%   |
| China SATA SSD 960GB                               | 3         | 2.26%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 2         | 1.5%    |
| Toshiba MQ04ABF100 1TB                             | 2         | 1.5%    |
| Toshiba MQ01ABF050 500GB                           | 2         | 1.5%    |
| Toshiba MQ01ABD100 1TB                             | 2         | 1.5%    |
| Seagate ST500LT012-1DG142 500GB                    | 2         | 1.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2         | 1.5%    |
| Samsung NVMe SSD Drive 1TB                         | 2         | 1.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2         | 1.5%    |
| Samsung MZNLH512HALU-00000 512GB SSD               | 2         | 1.5%    |
| Phison PCIe SSD 1TB                                | 2         | 1.5%    |
| Kingston OM8PCP3512F-AI1 512GB                     | 2         | 1.5%    |
| HGST HTS545050A7E680 500GB                         | 2         | 1.5%    |
| Apple SSD SM0256G 256GB                            | 2         | 1.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1         | 0.75%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                     | 1         | 0.75%   |
| WDC WD5000LPVX-75V0TT0 500GB                       | 1         | 0.75%   |
| WDC WD5000LPVX-55V0TT0 500GB                       | 1         | 0.75%   |
| WDC WD5000BPVT-22HXZT3 500GB                       | 1         | 0.75%   |
| WDC WD3200LPVT-00FMCT0 320GB                       | 1         | 0.75%   |
| WDC WD10SPZX-60Z10T0 1TB                           | 1         | 0.75%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 1         | 0.75%   |
| WDC WD10SPCX-24HWST1 1TB                           | 1         | 0.75%   |
| Unknown SD/MMC/MS PRO 8GB                          | 1         | 0.75%   |
| Unknown DA4064  64GB                               | 1         | 0.75%   |
| Union Memory (Shenzhen) UMIS RPEYJ512VMM2QWY 512GB | 1         | 0.75%   |
| Toshiba THNSNH128GMCT 128GB SSD                    | 1         | 0.75%   |
| Toshiba MK5065GSX 500GB                            | 1         | 0.75%   |
| Toshiba KBG30ZMT256G 256GB                         | 1         | 0.75%   |
| Timetec 35TTM8SSATA-512GB                          | 1         | 0.75%   |
| SPCC Solid State Disk 256GB                        | 1         | 0.75%   |
| Solid State Storage SSSTC CL1-4D256 256GB          | 1         | 0.75%   |
| SK hynix SKHynix_HFS512GD9TNI-L2B0B 512GB          | 1         | 0.75%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB          | 1         | 0.75%   |
| SK hynix SC311 SATA 256GB SSD                      | 1         | 0.75%   |
| SK hynix NVMe SSD Drive 1TB                        | 1         | 0.75%   |
| SK hynix NVMe SSD Drive 1024GB                     | 1         | 0.75%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB            | 1         | 0.75%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 16     | 37.21%  |
| WDC     | 9         | 11     | 20.93%  |
| Toshiba | 7         | 7      | 16.28%  |
| HGST    | 6         | 6      | 13.95%  |
| Hitachi | 4         | 5      | 9.3%    |
| Unknown | 1         | 1      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 11     | 28.57%  |
| China               | 4         | 4      | 11.43%  |
| Kingston            | 3         | 3      | 8.57%   |
| Apple               | 3         | 4      | 8.57%   |
| WDC                 | 2         | 3      | 5.71%   |
| Crucial             | 2         | 2      | 5.71%   |
| Toshiba             | 1         | 1      | 2.86%   |
| SPCC                | 1         | 1      | 2.86%   |
| SK hynix            | 1         | 1      | 2.86%   |
| SanDisk             | 1         | 1      | 2.86%   |
| PNY                 | 1         | 1      | 2.86%   |
| Patriot             | 1         | 1      | 2.86%   |
| Linux               | 1         | 1      | 2.86%   |
| LDLC                | 1         | 5      | 2.86%   |
| Intenso             | 1         | 1      | 2.86%   |
| Intel               | 1         | 1      | 2.86%   |
| AGI                 | 1         | 1      | 2.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 42        | 46     | 35.59%  |
| NVMe    | 40        | 61     | 33.9%   |
| SSD     | 33        | 42     | 27.97%  |
| Unknown | 2         | 3      | 1.69%   |
| MMC     | 1         | 1      | 0.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 70        | 89     | 61.95%  |
| NVMe | 40        | 61     | 35.4%   |
| SAS  | 2         | 2      | 1.77%   |
| MMC  | 1         | 1      | 0.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 43        | 53     | 58.9%   |
| 0.51-1.0   | 26        | 30     | 35.62%  |
| 1.01-2.0   | 3         | 4      | 4.11%   |
| 4.01-10.0  | 1         | 1      | 1.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 29        | 27.36%  |
| 101-250        | 29        | 27.36%  |
| 501-1000       | 16        | 15.09%  |
| 1001-2000      | 11        | 10.38%  |
| 51-100         | 5         | 4.72%   |
| Unknown        | 5         | 4.72%   |
| More than 3000 | 4         | 3.77%   |
| 1-20           | 4         | 3.77%   |
| 2001-3000      | 2         | 1.89%   |
| 21-50          | 1         | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 33        | 29.2%   |
| 101-250        | 21        | 18.58%  |
| 51-100         | 16        | 14.16%  |
| 21-50          | 12        | 10.62%  |
| 251-500        | 11        | 9.73%   |
| 501-1000       | 10        | 8.85%   |
| Unknown        | 5         | 4.42%   |
| 1001-2000      | 3         | 2.65%   |
| More than 3000 | 1         | 0.88%   |
| 2001-3000      | 1         | 0.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 12.5%   |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 12.5%   |
| WDC WD5000LPVX-55V0TT0 500GB                     | 1         | 1      | 6.25%   |
| WDC WD3200LPVT-00FMCT0 320GB                     | 1         | 1      | 6.25%   |
| WDC WD10SPCX-24HWST1 1TB                         | 1         | 1      | 6.25%   |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 6.25%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 6.25%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 6.25%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 6.25%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 6.25%   |
| LDLC SSD 120GB                                   | 1         | 3      | 6.25%   |
| Hitachi HTS547550A9E384 500GB                    | 1         | 1      | 6.25%   |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 6.25%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 18.75%  |
| Toshiba             | 3         | 3      | 18.75%  |
| Seagate             | 3         | 3      | 18.75%  |
| HGST                | 3         | 3      | 18.75%  |
| Hitachi             | 2         | 2      | 12.5%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| LDLC                | 1         | 3      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 21.43%  |
| Toshiba | 3         | 3      | 21.43%  |
| Seagate | 3         | 3      | 21.43%  |
| HGST    | 3         | 3      | 21.43%  |
| Hitachi | 2         | 2      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 14     | 87.5%   |
| SSD  | 2         | 4      | 12.5%   |

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
| Works    | 55        | 69     | 49.55%  |
| Detected | 40        | 66     | 36.04%  |
| Malfunc  | 16        | 18     | 14.41%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 65        | 51.18%  |
| Samsung Electronics            | 19        | 14.96%  |
| AMD                            | 18        | 14.17%  |
| SanDisk                        | 5         | 3.94%   |
| SK hynix                       | 4         | 3.15%   |
| Phison Electronics             | 3         | 2.36%   |
| Kingston Technology Company    | 3         | 2.36%   |
| Union Memory (Shenzhen)        | 2         | 1.57%   |
| Toshiba America Info Systems   | 1         | 0.79%   |
| Solid State Storage Technology | 1         | 0.79%   |
| Nvidia                         | 1         | 0.79%   |
| Micron/Crucial Technology      | 1         | 0.79%   |
| Micron Technology              | 1         | 0.79%   |
| Marvell Technology Group       | 1         | 0.79%   |
| Lite-On Technology             | 1         | 0.79%   |
| ADATA Technology               | 1         | 0.79%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 16        | 12.03%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 9         | 6.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 9         | 6.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 8         | 6.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 7         | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 6         | 4.51%   |
| Samsung NVMe SSD Controller 980                                               | 5         | 3.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 4         | 3.01%   |
| SK hynix Non-Volatile memory controller                                       | 3         | 2.26%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 3         | 2.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 3         | 2.26%   |
| Phison E12 NVMe Controller                                                    | 3         | 2.26%   |
| Kingston Company Company Non-Volatile memory controller                       | 3         | 2.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 3         | 2.26%   |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 2.26%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 3         | 2.26%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 3         | 2.26%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 3         | 2.26%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                        | 2         | 1.5%    |
| SanDisk Non-Volatile memory controller                                        | 2         | 1.5%    |
| Samsung Electronics SATA controller                                           | 2         | 1.5%    |
| Intel SSD 660P Series                                                         | 2         | 1.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 1.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 1.5%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 2         | 1.5%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 2         | 1.5%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                          | 1         | 0.75%   |
| Solid State Storage Non-Volatile memory controller                            | 1         | 0.75%   |
| SK hynix BC511                                                                | 1         | 0.75%   |
| Nvidia MCP79 AHCI Controller                                                  | 1         | 0.75%   |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 1         | 0.75%   |
| Micron Non-Volatile memory controller                                         | 1         | 0.75%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                    | 1         | 0.75%   |
| Lite-On Non-Volatile memory controller                                        | 1         | 0.75%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 0.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1         | 0.75%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller      | 1         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 75        | 58.59%  |
| NVMe | 41        | 32.03%  |
| RAID | 11        | 8.59%   |
| IDE  | 1         | 0.78%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 83        | 80.58%  |
| AMD    | 20        | 19.42%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 7 4700U with Radeon Graphics      | 4         | 3.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 2.88%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 2         | 1.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.92%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 1.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1.92%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 1.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.92%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 1.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.92%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 1.92%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 1.92%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 2         | 1.92%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 1.92%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.92%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 1.92%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz        | 1         | 0.96%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.96%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.96%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.96%   |
| Intel Pentium CPU A1018 @ 2.10GHz           | 1         | 0.96%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 0.96%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.96%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 1         | 0.96%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 0.96%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.96%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.96%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.96%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.96%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.96%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.96%   |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 0.96%   |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 0.96%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 0.96%   |
| Intel Core i7-10870H CPU @ 2.20GHz          | 1         | 0.96%   |
| Intel Core i7-10850H CPU @ 2.70GHz          | 1         | 0.96%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 0.96%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 1         | 0.96%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 0.96%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 27        | 26.21%  |
| Intel Core i7           | 21        | 20.39%  |
| Intel Core i3           | 11        | 10.68%  |
| AMD Ryzen 7             | 9         | 8.74%   |
| Other                   | 6         | 5.83%   |
| Intel Celeron           | 6         | 5.83%   |
| Intel Pentium           | 3         | 2.91%   |
| Intel Core m3           | 2         | 1.94%   |
| Intel Core i9           | 2         | 1.94%   |
| AMD Ryzen 5             | 2         | 1.94%   |
| AMD Ryzen 3             | 2         | 1.94%   |
| Intel Xeon              | 1         | 0.97%   |
| Intel Pentium Silver    | 1         | 0.97%   |
| Intel Pentium Dual-Core | 1         | 0.97%   |
| Intel Core 2 Duo        | 1         | 0.97%   |
| Intel Atom              | 1         | 0.97%   |
| AMD Ryzen 9             | 1         | 0.97%   |
| AMD Ryzen 5 PRO         | 1         | 0.97%   |
| AMD Phenom II           | 1         | 0.97%   |
| AMD E1                  | 1         | 0.97%   |
| AMD Athlon              | 1         | 0.97%   |
| AMD A6                  | 1         | 0.97%   |
| AMD A10                 | 1         | 0.97%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 49        | 47.57%  |
| 4      | 34        | 33.01%  |
| 8      | 11        | 10.68%  |
| 6      | 8         | 7.77%   |
| 12     | 1         | 0.97%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 103       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 80        | 77.67%  |
| 1      | 23        | 22.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 103       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 16.19%  |
| 0x206a7    | 8         | 7.62%   |
| 0x306a9    | 7         | 6.67%   |
| 0xa0652    | 5         | 4.76%   |
| 0x806e9    | 5         | 4.76%   |
| 0x40651    | 5         | 4.76%   |
| 0x806ec    | 4         | 3.81%   |
| 0x806ea    | 4         | 3.81%   |
| 0x806c1    | 4         | 3.81%   |
| 0x706e5    | 4         | 3.81%   |
| 0x306d4    | 4         | 3.81%   |
| 0x906ea    | 3         | 2.86%   |
| 0x906e9    | 3         | 2.86%   |
| 0x706a1    | 3         | 2.86%   |
| 0x08600106 | 3         | 2.86%   |
| 0x30678    | 2         | 1.9%    |
| 0x1067a    | 2         | 1.9%    |
| 0x08600103 | 2         | 1.9%    |
| 0x08108109 | 2         | 1.9%    |
| 0x906ed    | 1         | 0.95%   |
| 0x806eb    | 1         | 0.95%   |
| 0x806d1    | 1         | 0.95%   |
| 0x506e3    | 1         | 0.95%   |
| 0x506c9    | 1         | 0.95%   |
| 0x406e3    | 1         | 0.95%   |
| 0x306c3    | 1         | 0.95%   |
| 0x20655    | 1         | 0.95%   |
| 0x0a50000c | 1         | 0.95%   |
| 0x08701013 | 1         | 0.95%   |
| 0x08600104 | 1         | 0.95%   |
| 0x08108102 | 1         | 0.95%   |
| 0x0810100b | 1         | 0.95%   |
| 0x08101007 | 1         | 0.95%   |
| 0x08001137 | 1         | 0.95%   |
| 0x0700010b | 1         | 0.95%   |
| 0x06003109 | 1         | 0.95%   |
| 0x010000c8 | 1         | 0.95%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 27        | 26.21%  |
| Zen 2         | 8         | 7.77%   |
| SandyBridge   | 8         | 7.77%   |
| IvyBridge     | 8         | 7.77%   |
| Haswell       | 7         | 6.8%    |
| CometLake     | 6         | 5.83%   |
| TigerLake     | 5         | 4.85%   |
| Broadwell     | 5         | 4.85%   |
| Zen+          | 4         | 3.88%   |
| IceLake       | 4         | 3.88%   |
| Zen           | 3         | 2.91%   |
| Goldmont plus | 3         | 2.91%   |
| Skylake       | 2         | 1.94%   |
| Silvermont    | 2         | 1.94%   |
| Penryn        | 2         | 1.94%   |
| Zen 3         | 1         | 0.97%   |
| Westmere      | 1         | 0.97%   |
| Steamroller   | 1         | 0.97%   |
| Puma          | 1         | 0.97%   |
| K10           | 1         | 0.97%   |
| Jaguar        | 1         | 0.97%   |
| Goldmont      | 1         | 0.97%   |
| Bonnell       | 1         | 0.97%   |
| Unknown       | 1         | 0.97%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 76        | 58.46%  |
| Nvidia | 30        | 23.08%  |
| AMD    | 24        | 18.46%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                     | 6         | 4.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 4.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 6         | 4.55%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 4.55%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 6         | 4.55%   |
| AMD Renoir                                                                | 6         | 4.55%   |
| Intel UHD Graphics 620                                                    | 5         | 3.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 5         | 3.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 3.03%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 3.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 3.03%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 3         | 2.27%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 2.27%   |
| Intel HD Graphics 5500                                                    | 3         | 2.27%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 2.27%   |
| Nvidia TU117M                                                             | 2         | 1.52%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 2         | 1.52%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 1.52%   |
| Intel UHD Graphics 615                                                    | 2         | 1.52%   |
| Intel HD Graphics 630                                                     | 2         | 1.52%   |
| Intel HD Graphics 6000                                                    | 2         | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.52%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 1.52%   |
| AMD Saturn XT [FirePro M6100]                                             | 2         | 1.52%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.52%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.76%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.76%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.76%   |
| Nvidia GP108M [GeForce MX330]                                             | 1         | 0.76%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.76%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 0.76%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                  | 1         | 0.76%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.76%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.76%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                     | 1         | 0.76%   |
| Nvidia GM107 [GeForce 940MX]                                              | 1         | 0.76%   |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 0.76%   |
| Nvidia GF119M [GeForce GT 520MX]                                          | 1         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 50        | 48.08%  |
| Intel + Nvidia | 23        | 22.12%  |
| 1 x AMD        | 19        | 18.27%  |
| 1 x Nvidia     | 6         | 5.77%   |
| Intel + AMD    | 3         | 2.88%   |
| 2 x AMD        | 2         | 1.92%   |
| AMD + Nvidia   | 1         | 0.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 85        | 82.52%  |
| Proprietary | 18        | 17.48%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 67        | 64.42%  |
| 1.01-2.0   | 11        | 10.58%  |
| 0.01-0.5   | 10        | 9.62%   |
| 3.01-4.0   | 5         | 4.81%   |
| 0.51-1.0   | 5         | 4.81%   |
| 5.01-6.0   | 3         | 2.88%   |
| 7.01-8.0   | 2         | 1.92%   |
| 2.01-3.0   | 1         | 0.96%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 21        | 17.65%  |
| LG Display              | 20        | 16.81%  |
| BOE                     | 19        | 15.97%  |
| Chimei Innolux          | 14        | 11.76%  |
| Samsung Electronics     | 9         | 7.56%   |
| Dell                    | 4         | 3.36%   |
| Chi Mei Optoelectronics | 4         | 3.36%   |
| InfoVision              | 3         | 2.52%   |
| Goldstar                | 3         | 2.52%   |
| ASUSTek Computer        | 3         | 2.52%   |
| Apple                   | 3         | 2.52%   |
| Sharp                   | 2         | 1.68%   |
| PANDA                   | 2         | 1.68%   |
| Hewlett-Packard         | 2         | 1.68%   |
| BenQ                    | 2         | 1.68%   |
| Philips                 | 1         | 0.84%   |
| MSI                     | 1         | 0.84%   |
| LGD                     | 1         | 0.84%   |
| Lenovo                  | 1         | 0.84%   |
| KDC                     | 1         | 0.84%   |
| CSO                     | 1         | 0.84%   |
| Ancor Communications    | 1         | 0.84%   |
| Acer                    | 1         | 0.84%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 4         | 3.36%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 2.52%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 1.68%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 1.68%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.68%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 1.68%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 1.68%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 1.68%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 1.68%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 1.68%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 1.68%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 0.84%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.84%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 0.84%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch      | 1         | 0.84%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                   | 1         | 0.84%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 1         | 0.84%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                   | 1         | 0.84%   |
| MSI PRO 22X 10M MSI1462 1920x1080 595x336mm 26.9-inch                     | 1         | 0.84%   |
| LGD LCD Monitor 1920x1080                                                 | 1         | 0.84%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch               | 1         | 0.84%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch               | 1         | 0.84%   |
| LG Display LCD Monitor LGD045C 1366x768 344x194mm 15.5-inch               | 1         | 0.84%   |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch              | 1         | 0.84%   |
| LG Display LCD Monitor LGD03D3 1600x900 309x174mm 14.0-inch               | 1         | 0.84%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch               | 1         | 0.84%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch               | 1         | 0.84%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch               | 1         | 0.84%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 53        | 47.32%  |
| 1366x768 (WXGA)    | 39        | 34.82%  |
| 1440x900 (WXGA+)   | 4         | 3.57%   |
| 3840x2160 (4K)     | 3         | 2.68%   |
| 2560x1600          | 3         | 2.68%   |
| 2560x1440 (QHD)    | 3         | 2.68%   |
| 1600x900 (HD+)     | 3         | 2.68%   |
| 3440x1440          | 1         | 0.89%   |
| 2160x1440          | 1         | 0.89%   |
| 1920x1200 (WUXGA)  | 1         | 0.89%   |
| 1680x1050 (WSXGA+) | 1         | 0.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 53        | 44.92%  |
| 14      | 17        | 14.41%  |
| 13      | 17        | 14.41%  |
| 17      | 8         | 6.78%   |
| 24      | 5         | 4.24%   |
| 21      | 5         | 4.24%   |
| 27      | 4         | 3.39%   |
| 23      | 2         | 1.69%   |
| 34      | 1         | 0.85%   |
| 20      | 1         | 0.85%   |
| 19      | 1         | 0.85%   |
| 16      | 1         | 0.85%   |
| 12      | 1         | 0.85%   |
| 11      | 1         | 0.85%   |
| Unknown | 1         | 0.85%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 78        | 66.1%   |
| 351-400     | 12        | 10.17%  |
| 501-600     | 10        | 8.47%   |
| 201-300     | 8         | 6.78%   |
| 401-500     | 7         | 5.93%   |
| 701-800     | 1         | 0.85%   |
| 601-700     | 1         | 0.85%   |
| Unknown     | 1         | 0.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 91        | 88.35%  |
| 16/10   | 9         | 8.74%   |
| 3/2     | 1         | 0.97%   |
| 21/9    | 1         | 0.97%   |
| Unknown | 1         | 0.97%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 53        | 44.92%  |
| 81-90          | 28        | 23.73%  |
| 201-250        | 11        | 9.32%   |
| 121-130        | 7         | 5.93%   |
| 71-80          | 6         | 5.08%   |
| 301-350        | 4         | 3.39%   |
| 151-200        | 2         | 1.69%   |
| 61-70          | 1         | 0.85%   |
| 51-60          | 1         | 0.85%   |
| 351-500        | 1         | 0.85%   |
| 251-300        | 1         | 0.85%   |
| 131-140        | 1         | 0.85%   |
| 111-120        | 1         | 0.85%   |
| Unknown        | 1         | 0.85%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 53        | 46.09%  |
| 101-120       | 36        | 31.3%   |
| 51-100        | 18        | 15.65%  |
| 161-240       | 6         | 5.22%   |
| More than 240 | 1         | 0.87%   |
| Unknown       | 1         | 0.87%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 88        | 83.02%  |
| 2     | 18        | 16.98%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 67        | 39.18%  |
| Intel                    | 55        | 32.16%  |
| Qualcomm Atheros         | 20        | 11.7%   |
| Broadcom                 | 10        | 5.85%   |
| Broadcom Limited         | 4         | 2.34%   |
| Samsung Electronics      | 2         | 1.17%   |
| Ralink                   | 2         | 1.17%   |
| MediaTek                 | 2         | 1.17%   |
| Xiaomi                   | 1         | 0.58%   |
| Sierra Wireless          | 1         | 0.58%   |
| Ralink Technology        | 1         | 0.58%   |
| Qualcomm                 | 1         | 0.58%   |
| OPPO Electronics         | 1         | 0.58%   |
| Marvell Technology Group | 1         | 0.58%   |
| Linksys                  | 1         | 0.58%   |
| Huawei Technologies      | 1         | 0.58%   |
| Apple                    | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 20.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 6.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 3.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 3.03%   |
| Intel Wireless 8265 / 8275                                        | 6         | 3.03%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 2.53%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 2.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 2.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 2.02%   |
| Intel Wireless 7265                                               | 4         | 2.02%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 2.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 1.52%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.52%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.52%   |
| Realtek 802.11ac NIC                                              | 2         | 1.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 1.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.01%   |
| Intel Wireless 7260                                               | 2         | 1.01%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 1.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.01%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 1.01%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 1.01%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.01%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.51%   |
| Sierra Wireless MC7700                                            | 1         | 0.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 51        | 47.66%  |
| Realtek Semiconductor | 20        | 18.69%  |
| Qualcomm Atheros      | 17        | 15.89%  |
| Broadcom              | 9         | 8.41%   |
| Broadcom Limited      | 4         | 3.74%   |
| Ralink                | 2         | 1.87%   |
| MediaTek              | 2         | 1.87%   |
| Sierra Wireless       | 1         | 0.93%   |
| Ralink Technology     | 1         | 0.93%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 5.61%   |
| Intel Wireless 8265 / 8275                                     | 6         | 5.61%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 5.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 4.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 4.67%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 4.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 4.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 3.74%   |
| Intel Wireless 7265                                            | 4         | 3.74%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 3.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 2.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 2.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 2.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 2.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.8%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 2.8%    |
| Realtek 802.11ac NIC                                           | 2         | 1.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.87%   |
| Intel Wireless 7260                                            | 2         | 1.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.87%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 1.87%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.87%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.87%   |
| Sierra Wireless MC7700                                         | 1         | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.93%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.93%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.93%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.93%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.93%   |
| Intel Wireless-AC 9260                                         | 1         | 0.93%   |
| Intel Wireless 3165                                            | 1         | 0.93%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 59        | 66.29%  |
| Intel                    | 16        | 17.98%  |
| Qualcomm Atheros         | 4         | 4.49%   |
| Samsung Electronics      | 2         | 2.25%   |
| Xiaomi                   | 1         | 1.12%   |
| Qualcomm                 | 1         | 1.12%   |
| OPPO Electronics         | 1         | 1.12%   |
| Marvell Technology Group | 1         | 1.12%   |
| Linksys                  | 1         | 1.12%   |
| Huawei Technologies      | 1         | 1.12%   |
| Broadcom                 | 1         | 1.12%   |
| Apple                    | 1         | 1.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 45.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 14.29%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 6.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 6.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 3.3%    |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 2.2%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.1%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.1%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.1%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.1%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.1%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.1%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.1%    |
| Qualcomm A0001                                                    | 1         | 1.1%    |
| OPPO SDM665-IDP _SN:18689828                                      | 1         | 1.1%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.1%    |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 1.1%    |
| Intel WiMAX Connection 2400m                                      | 1         | 1.1%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.1%    |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.1%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.1%    |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.1%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.1%    |
| Huawei E353/E3131                                                 | 1         | 1.1%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.1%    |
| Apple iPad 4/Mini1                                                | 1         | 1.1%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 101       | 55.49%  |
| Ethernet | 81        | 44.51%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 84        | 79.25%  |
| Ethernet | 22        | 20.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 73        | 70.19%  |
| 1     | 28        | 26.92%  |
| 3     | 2         | 1.92%   |
| 0     | 1         | 0.96%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 91        | 85.85%  |
| Yes  | 15        | 14.15%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 43        | 50.59%  |
| Realtek Semiconductor           | 13        | 15.29%  |
| Broadcom                        | 7         | 8.24%   |
| Qualcomm Atheros Communications | 4         | 4.71%   |
| Lite-On Technology              | 4         | 4.71%   |
| IMC Networks                    | 3         | 3.53%   |
| Foxconn / Hon Hai               | 3         | 3.53%   |
| Apple                           | 3         | 3.53%   |
| Realtek                         | 2         | 2.35%   |
| Ralink                          | 1         | 1.18%   |
| Cambridge Silicon Radio         | 1         | 1.18%   |
| ASUSTek Computer                | 1         | 1.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 12        | 14.12%  |
| Intel AX201 Bluetooth                               | 12        | 14.12%  |
| Realtek Bluetooth Radio                             | 8         | 9.41%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 9.41%   |
| Intel AX200 Bluetooth                               | 6         | 7.06%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 4.71%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 3.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 3.53%   |
| Realtek Bluetooth Radio                             | 2         | 2.35%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.35%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.35%   |
| IMC Networks Wireless_Device                        | 2         | 2.35%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 2.35%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.35%   |
| Apple Bluetooth USB Host Controller                 | 2         | 2.35%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.18%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.18%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.18%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.18%   |
| IMC Networks Bluetooth Device                       | 1         | 1.18%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.18%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.18%   |
| Broadcom HP Portable Valentine                      | 1         | 1.18%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.18%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.18%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 1.18%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.18%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.18%   |
| Apple Bluetooth Host Controller                     | 1         | 1.18%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 82        | 62.6%   |
| AMD                   | 22        | 16.79%  |
| Nvidia                | 19        | 14.5%   |
| C-Media Electronics   | 3         | 2.29%   |
| Realtek Semiconductor | 2         | 1.53%   |
| Plantronics           | 1         | 0.76%   |
| Harman                | 1         | 0.76%   |
| Corsair               | 1         | 0.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 14        | 8.59%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14        | 8.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 4.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 4.91%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 3.68%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 3.68%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 3.68%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 3.68%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 3.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 3.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 3.07%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 3.07%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 2.45%   |
| Intel CM238 HD Audio Controller                                            | 4         | 2.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.45%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.45%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.84%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.84%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.84%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.84%   |
| Realtek Semiconductor USB Audio                                            | 2         | 1.23%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.23%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.23%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 1.23%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 2         | 1.23%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.23%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.61%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.61%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.61%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.61%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.61%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.61%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.61%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.61%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.61%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 30        | 27.52%  |
| Samsung Electronics | 30        | 27.52%  |
| Kingston            | 12        | 11.01%  |
| Micron Technology   | 10        | 9.17%   |
| Unknown             | 4         | 3.67%   |
| A-DATA Technology   | 4         | 3.67%   |
| Silicon Power       | 3         | 2.75%   |
| Unknown             | 3         | 2.75%   |
| Unknown (ABCD)      | 2         | 1.83%   |
| Smart               | 2         | 1.83%   |
| Ramaxel Technology  | 2         | 1.83%   |
| Nanya Technology    | 2         | 1.83%   |
| Corsair             | 2         | 1.83%   |
| Team                | 1         | 0.92%   |
| Smart Brazil        | 1         | 0.92%   |
| ASint Technology    | 1         | 0.92%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 3.51%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.63%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 3         | 2.63%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 3         | 2.63%   |
| Unknown                                                          | 3         | 2.63%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.75%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.75%   |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.75%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.75%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.75%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 2         | 1.75%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 2         | 1.75%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 1.75%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.75%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.75%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.75%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.75%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.88%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.88%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.88%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.88%   |
| Team RAM TEAMGROUP-SD3-1600 4GB SODIMM DDR3 1600MT/s             | 1         | 0.88%   |
| Smart RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 3200MT/s         | 1         | 0.88%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2400MT/s            | 1         | 0.88%   |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 2933MT/s     | 1         | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.88%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.88%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.88%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.88%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.88%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.88%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.88%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.88%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.88%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.88%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.88%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.88%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 48        | 53.93%  |
| DDR3    | 31        | 34.83%  |
| LPDDR4  | 4         | 4.49%   |
| LPDDR3  | 3         | 3.37%   |
| SDRAM   | 2         | 2.25%   |
| Unknown | 1         | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 79        | 87.78%  |
| Row Of Chips | 8         | 8.89%   |
| DIMM         | 1         | 1.11%   |
| Chip         | 1         | 1.11%   |
| Unknown      | 1         | 1.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 40        | 38.83%  |
| 8192  | 35        | 33.98%  |
| 16384 | 14        | 13.59%  |
| 2048  | 11        | 10.68%  |
| 32768 | 2         | 1.94%   |
| 1024  | 1         | 0.97%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 27        | 28.13%  |
| 3200  | 20        | 20.83%  |
| 2667  | 20        | 20.83%  |
| 2400  | 10        | 10.42%  |
| 1333  | 5         | 5.21%   |
| 2133  | 3         | 3.13%   |
| 1334  | 3         | 3.13%   |
| 4199  | 2         | 2.08%   |
| 4267  | 1         | 1.04%   |
| 3400  | 1         | 1.04%   |
| 3266  | 1         | 1.04%   |
| 2933  | 1         | 1.04%   |
| 1067  | 1         | 1.04%   |
| 1066  | 1         | 1.04%   |

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
| Chicony Electronics                    | 20        | 21.98%  |
| Realtek Semiconductor                  | 10        | 10.99%  |
| Acer                                   | 10        | 10.99%  |
| Quanta                                 | 9         | 9.89%   |
| IMC Networks                           | 9         | 9.89%   |
| Suyin                                  | 6         | 6.59%   |
| Alcor Micro                            | 4         | 4.4%    |
| Syntek                                 | 3         | 3.3%    |
| Sunplus Innovation Technology          | 3         | 3.3%    |
| Silicon Motion                         | 3         | 3.3%    |
| Microdia                               | 3         | 3.3%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.3%    |
| Sonix Technology                       | 2         | 2.2%    |
| Luxvisions Innotech Limited            | 2         | 2.2%    |
| Lite-On Technology                     | 1         | 1.1%    |
| LG Electronics                         | 1         | 1.1%    |
| Lenovo                                 | 1         | 1.1%    |
| DJKANA19IDX53W                         | 1         | 1.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                        | 6         | 6.59%   |
| Chicony HD WebCam                                     | 6         | 6.59%   |
| Realtek Integrated_Webcam_HD                          | 4         | 4.4%    |
| Chicony Integrated Camera                             | 4         | 4.4%    |
| Acer Integrated Camera                                | 4         | 4.4%    |
| Syntek EasyCamera                                     | 2         | 2.2%    |
| Suyin HP Webcam                                       | 2         | 2.2%    |
| Sonix USB2.0 HD UVC WebCam                            | 2         | 2.2%    |
| Silicon Motion 300k Pixel Camera                      | 2         | 2.2%    |
| Realtek USB2.0 HD UVC WebCam                          | 2         | 2.2%    |
| Realtek HD WebCam                                     | 2         | 2.2%    |
| Quanta VGA WebCam                                     | 2         | 2.2%    |
| Quanta HP Webcam                                      | 2         | 2.2%    |
| Quanta HP TrueVision HD Camera                        | 2         | 2.2%    |
| Microdia Integrated Webcam                            | 2         | 2.2%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera   | 2         | 2.2%    |
| Chicony USB2.0 VGA UVC WebCam                         | 2         | 2.2%    |
| Chicony Integrated Camera (1280x720@30)               | 2         | 2.2%    |
| Alcor Micro USB 2.0 Camera                            | 2         | 2.2%    |
| Syntek Integrated Camera                              | 1         | 1.1%    |
| Suyin USB Webcam                                      | 1         | 1.1%    |
| Suyin NEC HD WebCam                                   | 1         | 1.1%    |
| Suyin Laptop_Integrated_Webcam_HD                     | 1         | 1.1%    |
| Suyin 1.3M HD WebCam                                  | 1         | 1.1%    |
| Sunplus Laptop_Integrated_Webcam_FHD                  | 1         | 1.1%    |
| Sunplus Integrated_Webcam_HD                          | 1         | 1.1%    |
| Sunplus HD WebCam                                     | 1         | 1.1%    |
| Silicon Motion WebCam SCB-0355N                       | 1         | 1.1%    |
| Realtek Integrated Webcam                             | 1         | 1.1%    |
| Realtek HP "Truevision HD" laptop camera              | 1         | 1.1%    |
| Quanta USB2.0 VGA UVC WebCam                          | 1         | 1.1%    |
| Quanta HD Webcam                                      | 1         | 1.1%    |
| Quanta HD User Facing                                 | 1         | 1.1%    |
| Microdia Integrated_Webcam_HD                         | 1         | 1.1%    |
| Lite-On HP HD Camera                                  | 1         | 1.1%    |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1         | 1.1%    |
| Lenovo UVC Camera                                     | 1         | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                    | 1         | 1.1%    |
| IMC Networks Integrated Webcam                        | 1         | 1.1%    |
| IMC Networks 2M Integrated Webcam                     | 1         | 1.1%    |

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
| 0     | 72        | 67.92%  |
| 1     | 29        | 27.36%  |
| 2     | 5         | 4.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 7         | 17.5%   |
| Net/wireless             | 5         | 12.5%   |
| Graphics card            | 5         | 12.5%   |
| Camera                   | 5         | 12.5%   |
| Multimedia controller    | 4         | 10%     |
| Chipcard                 | 4         | 10%     |
| Bluetooth                | 4         | 10%     |
| Storage                  | 2         | 5%      |
| Communication controller | 2         | 5%      |
| Network                  | 1         | 2.5%    |
| Dvb card                 | 1         | 2.5%    |

