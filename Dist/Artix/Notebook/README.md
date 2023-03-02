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

Total: 164

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T430 2344BZU       | [245d23aff3](https://linux-hardware.org/?probe=245d23aff3) | Feb 26, 2023 |
| HP            | 245 G8 Notebook PC          | [1236b5c48f](https://linux-hardware.org/?probe=1236b5c48f) | Feb 19, 2023 |
| HUAWEI        | KPR-WX9                     | [1f44fd5a86](https://linux-hardware.org/?probe=1f44fd5a86) | Feb 18, 2023 |
| ONE-NETBOO... | One-Mix3 Pro                | [9869b4dd9c](https://linux-hardware.org/?probe=9869b4dd9c) | Feb 15, 2023 |
| Gigabyte      | RC14UD                      | [cce1ca1ac5](https://linux-hardware.org/?probe=cce1ca1ac5) | Feb 14, 2023 |
| Fujitsu       | LIFEBOOK A512               | [92cac1a802](https://linux-hardware.org/?probe=92cac1a802) | Feb 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U7S... | [84411df81a](https://linux-hardware.org/?probe=84411df81a) | Feb 06, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [bd7e955a3e](https://linux-hardware.org/?probe=bd7e955a3e) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [1f74ea5c27](https://linux-hardware.org/?probe=1f74ea5c27) | Jan 27, 2023 |
| Lenovo        | B50-80 80EW                 | [5f584c387e](https://linux-hardware.org/?probe=5f584c387e) | Jan 25, 2023 |
| Toshiba       | Satellite P775              | [4ac7834c5f](https://linux-hardware.org/?probe=4ac7834c5f) | Jan 16, 2023 |
| Toshiba       | Satellite P775              | [99e632c9a9](https://linux-hardware.org/?probe=99e632c9a9) | Jan 16, 2023 |
| Lenovo        | ThinkPad T430 23427YU       | [3ca2dd056d](https://linux-hardware.org/?probe=3ca2dd056d) | Jan 16, 2023 |
| HONOR         | BMH-WCX9                    | [815525e6d2](https://linux-hardware.org/?probe=815525e6d2) | Dec 27, 2022 |
| ASUSTek       | GL702ZC                     | [de8b2bcfab](https://linux-hardware.org/?probe=de8b2bcfab) | Dec 03, 2022 |
| GPD           | P2 MAX                      | [dce4c87de8](https://linux-hardware.org/?probe=dce4c87de8) | Dec 03, 2022 |
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
| Artix Rolling  | 70        | 57.85%  |
| Artix          | 47        | 38.84%  |
| Artix 20220713 | 1         | 0.83%   |
| Artix 20220123 | 1         | 0.83%   |
| Artix 20201207 | 1         | 0.83%   |
| Artix 20201128 | 1         | 0.83%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Artix | 115       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.9.14-artix1-1             | 6         | 4.41%   |
| 6.0.7-artix1-1              | 3         | 2.21%   |
| 5.7.6-artix1-1              | 3         | 2.21%   |
| 6.1.8-artix1-1              | 2         | 1.47%   |
| 6.1.6-artix1-1              | 2         | 1.47%   |
| 6.1.10-zen1-1-zen           | 2         | 1.47%   |
| 6.0.12-artix1-1             | 2         | 1.47%   |
| 5.7.12-artix1-1             | 2         | 1.47%   |
| 5.19.12-artix1-1            | 2         | 1.47%   |
| 5.18.6-artix1-1             | 2         | 1.47%   |
| 5.18.10-artix1-1            | 2         | 1.47%   |
| 5.18.0-artix1-1             | 2         | 1.47%   |
| 5.17.1-artix1-1             | 2         | 1.47%   |
| 5.16.8-artix1-2             | 2         | 1.47%   |
| 5.16.10-artix1-1            | 2         | 1.47%   |
| 5.15.12-artix1-1            | 2         | 1.47%   |
| 5.14.16-artix1-1            | 2         | 1.47%   |
| 5.13.8-artix1-1             | 2         | 1.47%   |
| 5.12.8-artix1-1             | 2         | 1.47%   |
| 5.12.12-zen1-1-zen          | 2         | 1.47%   |
| 5.12.12-artix1-1            | 2         | 1.47%   |
| 5.11.6-artix1-1             | 2         | 1.47%   |
| 5.10.6-artix1-1             | 2         | 1.47%   |
| 5.10.4-artix2-1             | 2         | 1.47%   |
| 5.10.16-artix1-1            | 2         | 1.47%   |
| 6.1.12-artix1-1             | 1         | 0.74%   |
| 6.1.10-hardened1-1-hardened | 1         | 0.74%   |
| 6.1.10-artix1-1             | 1         | 0.74%   |
| 6.0.9-hardened1-1-hardened  | 1         | 0.74%   |
| 6.0.7-zen1-1-zen            | 1         | 0.74%   |
| 6.0.5.14.realtime1-1-rt     | 1         | 0.74%   |
| 6.0.2-artix1-1.1            | 1         | 0.74%   |
| 5.9.6-artix1-1              | 1         | 0.74%   |
| 5.9.14-zen1-1-zen           | 1         | 0.74%   |
| 5.9.12-artix1-1             | 1         | 0.74%   |
| 5.9.1-artix1-1              | 1         | 0.74%   |
| 5.9.0-zen1-1-zen            | 1         | 0.74%   |
| 5.9.0-1-mainline-bootsplash | 1         | 0.74%   |
| 5.8.8-artix1-1              | 1         | 0.74%   |
| 5.8.4-artix1-1              | 1         | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.9.14   | 7         | 5.15%   |
| 6.1.10   | 4         | 2.94%   |
| 6.0.7    | 4         | 2.94%   |
| 5.12.12  | 4         | 2.94%   |
| 5.7.6    | 3         | 2.21%   |
| 5.17.1   | 3         | 2.21%   |
| 5.15.12  | 3         | 2.21%   |
| 5.12.8   | 3         | 2.21%   |
| 6.1.8    | 2         | 1.47%   |
| 6.1.6    | 2         | 1.47%   |
| 6.0.12   | 2         | 1.47%   |
| 5.9.0    | 2         | 1.47%   |
| 5.8.14   | 2         | 1.47%   |
| 5.7.12   | 2         | 1.47%   |
| 5.19.12  | 2         | 1.47%   |
| 5.18.6   | 2         | 1.47%   |
| 5.18.10  | 2         | 1.47%   |
| 5.18.0   | 2         | 1.47%   |
| 5.16.8   | 2         | 1.47%   |
| 5.16.10  | 2         | 1.47%   |
| 5.14.16  | 2         | 1.47%   |
| 5.13.8   | 2         | 1.47%   |
| 5.12.14  | 2         | 1.47%   |
| 5.11.6   | 2         | 1.47%   |
| 5.10.6   | 2         | 1.47%   |
| 5.10.4   | 2         | 1.47%   |
| 5.10.16  | 2         | 1.47%   |
| 6.1.12   | 1         | 0.74%   |
| 6.0.9    | 1         | 0.74%   |
| 6.0.5.14 | 1         | 0.74%   |
| 6.0.2    | 1         | 0.74%   |
| 5.9.6    | 1         | 0.74%   |
| 5.9.12   | 1         | 0.74%   |
| 5.9.1    | 1         | 0.74%   |
| 5.8.8    | 1         | 0.74%   |
| 5.8.4    | 1         | 0.74%   |
| 5.8.12   | 1         | 0.74%   |
| 5.8.0    | 1         | 0.74%   |
| 5.7.8    | 1         | 0.74%   |
| 5.7.2    | 1         | 0.74%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 13        | 10%     |
| 5.18    | 12        | 9.23%   |
| 5.12    | 12        | 9.23%   |
| 5.9     | 11        | 8.46%   |
| 5.10    | 11        | 8.46%   |
| 6.1     | 9         | 6.92%   |
| 6.0     | 8         | 6.15%   |
| 5.17    | 8         | 6.15%   |
| 5.16    | 8         | 6.15%   |
| 5.11    | 8         | 6.15%   |
| 5.7     | 6         | 4.62%   |
| 5.19    | 6         | 4.62%   |
| 5.8     | 5         | 3.85%   |
| 5.14    | 4         | 3.08%   |
| 5.13    | 4         | 3.08%   |
| 6.0.5   | 1         | 0.77%   |
| 5.6     | 1         | 0.77%   |
| 5.5     | 1         | 0.77%   |
| 5.4     | 1         | 0.77%   |
| 4.19    | 1         | 0.77%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 115       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| KDE5           | 28        | 22.76%  |
| Unknown        | 20        | 16.26%  |
| XFCE           | 19        | 15.45%  |
| GNOME          | 15        | 12.2%   |
| X-Cinnamon     | 7         | 5.69%   |
| MATE           | 7         | 5.69%   |
| LXQt           | 4         | 3.25%   |
| KDE            | 4         | 3.25%   |
| i3             | 4         | 3.25%   |
| LXDE           | 3         | 2.44%   |
| Cinnamon       | 3         | 2.44%   |
| bspwm          | 2         | 1.63%   |
| xmonad         | 1         | 0.81%   |
| xinitrc        | 1         | 0.81%   |
| sway-dbus      | 1         | 0.81%   |
| Sway           | 1         | 0.81%   |
| nxde           | 1         | 0.81%   |
| awesomeminimal | 1         | 0.81%   |
| awesome        | 1         | 0.81%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 82        | 68.91%  |
| Tty     | 17        | 14.29%  |
| Wayland | 13        | 10.92%  |
| Unknown | 7         | 5.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 43        | 36.13%  |
| LightDM | 39        | 32.77%  |
| SDDM    | 32        | 26.89%  |
| XDM     | 1         | 0.84%   |
| SLiM    | 1         | 0.84%   |
| Ly      | 1         | 0.84%   |
| LXDM    | 1         | 0.84%   |
| GDM     | 1         | 0.84%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 60        | 50.42%  |
| Unknown | 13        | 10.92%  |
| ru_RU   | 8         | 6.72%   |
| en_GB   | 8         | 6.72%   |
| C       | 4         | 3.36%   |
| fr_FR   | 3         | 2.52%   |
| pl_PL   | 2         | 1.68%   |
| es_ES   | 2         | 1.68%   |
| en_CA   | 2         | 1.68%   |
| en_AG   | 2         | 1.68%   |
| vi_VN   | 1         | 0.84%   |
| uk_UA   | 1         | 0.84%   |
| tr_TR   | 1         | 0.84%   |
| ro_RO   | 1         | 0.84%   |
| pt_PT   | 1         | 0.84%   |
| pt_BR   | 1         | 0.84%   |
| it_IT   | 1         | 0.84%   |
| es_GT   | 1         | 0.84%   |
| es_CO   | 1         | 0.84%   |
| en_NZ   | 1         | 0.84%   |
| en_IN   | 1         | 0.84%   |
| en_AU   | 1         | 0.84%   |
| el_GR   | 1         | 0.84%   |
| de_DE   | 1         | 0.84%   |
| cs_CZ   | 1         | 0.84%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 80        | 68.97%  |
| BIOS | 36        | 31.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 88        | 75.86%  |
| Btrfs   | 22        | 18.97%  |
| Xfs     | 3         | 2.59%   |
| Overlay | 2         | 1.72%   |
| F2fs    | 1         | 0.86%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 81        | 69.83%  |
| MBR     | 19        | 16.38%  |
| Unknown | 16        | 13.79%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 99        | 85.34%  |
| Yes       | 17        | 14.66%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 84        | 73.04%  |
| Yes       | 31        | 26.96%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 31        | 26.96%  |
| Hewlett-Packard        | 17        | 14.78%  |
| Dell                   | 14        | 12.17%  |
| Acer                   | 13        | 11.3%   |
| ASUSTek Computer       | 12        | 10.43%  |
| MSI                    | 3         | 2.61%   |
| Gigabyte Technology    | 3         | 2.61%   |
| Apple                  | 3         | 2.61%   |
| Timi                   | 2         | 1.74%   |
| Samsung Electronics    | 2         | 1.74%   |
| Notebook               | 2         | 1.74%   |
| HUAWEI                 | 2         | 1.74%   |
| GPD                    | 2         | 1.74%   |
| UNOWHY                 | 1         | 0.87%   |
| Toshiba                | 1         | 0.87%   |
| Quanta                 | 1         | 0.87%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.87%   |
| MOTILE                 | 1         | 0.87%   |
| LG Electronics         | 1         | 0.87%   |
| HONOR                  | 1         | 0.87%   |
| Fujitsu                | 1         | 0.87%   |
| AXIOO                  | 1         | 0.87%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Timi RedmiBook 14 II                   | 2         | 1.74%   |
| Lenovo IdeaPad 5 15IIL05 81YK          | 2         | 1.74%   |
| HP 15                                  | 2         | 1.74%   |
| GPD P2 MAX                             | 2         | 1.74%   |
| Dell Precision M6600                   | 2         | 1.74%   |
| Dell Precision 7550                    | 2         | 1.74%   |
| Apple MacBookAir7,2                    | 2         | 1.74%   |
| UNOWHY Y13G010S4EI                     | 1         | 0.87%   |
| Toshiba Satellite P775                 | 1         | 0.87%   |
| Samsung R425D/R525D                    | 1         | 0.87%   |
| Samsung 350V5C/351V5C/3540VC/3440VC    | 1         | 0.87%   |
| Quanta SWH                             | 1         | 0.87%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 Pro    | 1         | 0.87%   |
| Notebook N141CU                        | 1         | 0.87%   |
| Notebook N130BU                        | 1         | 0.87%   |
| MSI Modern 15 A11M                     | 1         | 0.87%   |
| MSI GP72 7RDX                          | 1         | 0.87%   |
| MSI GF65 Thin 10SDR                    | 1         | 0.87%   |
| MOTILE M141                            | 1         | 0.87%   |
| LG 17Z990-R.AAC9U1                     | 1         | 0.87%   |
| Lenovo ThinkPad W500 4063CJ5           | 1         | 0.87%   |
| Lenovo ThinkPad T480s 20L8S3D400       | 1         | 0.87%   |
| Lenovo ThinkPad T480 MFG_IN_GO         | 1         | 0.87%   |
| Lenovo ThinkPad T440s 20ARS0MV00       | 1         | 0.87%   |
| Lenovo ThinkPad T430 2350BC6           | 1         | 0.87%   |
| Lenovo ThinkPad T430 2347H76           | 1         | 0.87%   |
| Lenovo ThinkPad T430 2344BZU           | 1         | 0.87%   |
| Lenovo ThinkPad T430 23427YU           | 1         | 0.87%   |
| Lenovo ThinkPad T420 4236H45           | 1         | 0.87%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00   | 1         | 0.87%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800   | 1         | 0.87%   |
| Lenovo ThinkPad P1 Gen 3 20TH001EMH    | 1         | 0.87%   |
| Lenovo ThinkPad L15 Gen 1 20U7S06Y00   | 1         | 0.87%   |
| Lenovo ThinkPad E14 Gen 2 20T6000MCK   | 1         | 0.87%   |
| Lenovo ThinkPad 11e 5th Gen 20LNS0P500 | 1         | 0.87%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 1         | 0.87%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 0.87%   |
| Lenovo LaVie Z 20FF0012US              | 1         | 0.87%   |
| Lenovo IdeaPad Y500 20193              | 1         | 0.87%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL  | 1         | 0.87%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Lenovo ThinkPad                 | 15        | 13.04%  |
| Lenovo IdeaPad                  | 9         | 7.83%   |
| Acer Aspire                     | 9         | 7.83%   |
| Dell Precision                  | 6         | 5.22%   |
| HP Laptop                       | 5         | 4.35%   |
| Dell Latitude                   | 4         | 3.48%   |
| Dell Inspiron                   | 4         | 3.48%   |
| HP 250                          | 3         | 2.61%   |
| Timi RedmiBook                  | 2         | 1.74%   |
| HP Pavilion                     | 2         | 1.74%   |
| HP 15                           | 2         | 1.74%   |
| GPD P2                          | 2         | 1.74%   |
| ASUS VivoBook                   | 2         | 1.74%   |
| ASUS ASUS                       | 2         | 1.74%   |
| Apple MacBookAir7               | 2         | 1.74%   |
| Acer Nitro                      | 2         | 1.74%   |
| UNOWHY Y13G010S4EI              | 1         | 0.87%   |
| Toshiba Satellite               | 1         | 0.87%   |
| Samsung R425D                   | 1         | 0.87%   |
| Samsung 350V5C                  | 1         | 0.87%   |
| Quanta SWH                      | 1         | 0.87%   |
| ONE-NETBOOK TECHNOLOGY One-Mix3 | 1         | 0.87%   |
| Notebook N141CU                 | 1         | 0.87%   |
| Notebook N130BU                 | 1         | 0.87%   |
| MSI Modern                      | 1         | 0.87%   |
| MSI GP72                        | 1         | 0.87%   |
| MSI GF65                        | 1         | 0.87%   |
| MOTILE M141                     | 1         | 0.87%   |
| LG 17Z990-R.AAC9U1              | 1         | 0.87%   |
| Lenovo ThinkBook                | 1         | 0.87%   |
| Lenovo Legion                   | 1         | 0.87%   |
| Lenovo LaVie                    | 1         | 0.87%   |
| Lenovo G400s                    | 1         | 0.87%   |
| Lenovo B590                     | 1         | 0.87%   |
| Lenovo B570e                    | 1         | 0.87%   |
| Lenovo B50-80                   | 1         | 0.87%   |
| HUAWEI WRT-WX9                  | 1         | 0.87%   |
| HUAWEI KPR-WX9                  | 1         | 0.87%   |
| HONOR BMH-WCX9                  | 1         | 0.87%   |
| HP ProBook                      | 1         | 0.87%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 26        | 22.61%  |
| 2019 | 13        | 11.3%   |
| 2018 | 13        | 11.3%   |
| 2013 | 9         | 7.83%   |
| 2012 | 9         | 7.83%   |
| 2011 | 9         | 7.83%   |
| 2017 | 8         | 6.96%   |
| 2014 | 7         | 6.09%   |
| 2021 | 6         | 5.22%   |
| 2015 | 6         | 5.22%   |
| 2016 | 4         | 3.48%   |
| 2010 | 3         | 2.61%   |
| 2022 | 1         | 0.87%   |
| 2009 | 1         | 0.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 115       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 114       | 99.13%  |
| Enabled  | 1         | 0.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 115       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 35        | 30.17%  |
| 8.01-16.0   | 26        | 22.41%  |
| 16.01-24.0  | 24        | 20.69%  |
| 3.01-4.0    | 17        | 14.66%  |
| 32.01-64.0  | 4         | 3.45%   |
| 1.01-2.0    | 4         | 3.45%   |
| 24.01-32.0  | 3         | 2.59%   |
| 64.01-256.0 | 3         | 2.59%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 32        | 24.62%  |
| 1.01-2.0   | 31        | 23.85%  |
| 4.01-8.0   | 29        | 22.31%  |
| 3.01-4.0   | 15        | 11.54%  |
| 0.51-1.0   | 14        | 10.77%  |
| 8.01-16.0  | 6         | 4.62%   |
| 0.01-0.5   | 2         | 1.54%   |
| 16.01-24.0 | 1         | 0.77%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 90        | 77.59%  |
| 2      | 23        | 19.83%  |
| 3      | 3         | 2.59%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 84        | 73.04%  |
| Yes       | 31        | 26.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 78.26%  |
| No        | 25        | 21.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 98.26%  |
| No        | 2         | 1.74%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 81.2%   |
| No        | 22        | 18.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 26        | 22.61%  |
| Russia      | 13        | 11.3%   |
| India       | 6         | 5.22%   |
| Turkey      | 5         | 4.35%   |
| Germany     | 5         | 4.35%   |
| Brazil      | 5         | 4.35%   |
| UK          | 4         | 3.48%   |
| Indonesia   | 4         | 3.48%   |
| Canada      | 4         | 3.48%   |
| Ukraine     | 3         | 2.61%   |
| Spain       | 3         | 2.61%   |
| Poland      | 3         | 2.61%   |
| Netherlands | 3         | 2.61%   |
| France      | 3         | 2.61%   |
| Switzerland | 2         | 1.74%   |
| Romania     | 2         | 1.74%   |
| Italy       | 2         | 1.74%   |
| Czechia     | 2         | 1.74%   |
| Bulgaria    | 2         | 1.74%   |
| Vietnam     | 1         | 0.87%   |
| Uzbekistan  | 1         | 0.87%   |
| Sweden      | 1         | 0.87%   |
| Peru        | 1         | 0.87%   |
| Lithuania   | 1         | 0.87%   |
| Japan       | 1         | 0.87%   |
| Israel      | 1         | 0.87%   |
| Iran        | 1         | 0.87%   |
| Guatemala   | 1         | 0.87%   |
| Greece      | 1         | 0.87%   |
| Colombia    | 1         | 0.87%   |
| China       | 1         | 0.87%   |
| Chile       | 1         | 0.87%   |
| Bangladesh  | 1         | 0.87%   |
| Azerbaijan  | 1         | 0.87%   |
| Australia   | 1         | 0.87%   |
| Argentina   | 1         | 0.87%   |
| Algeria     | 1         | 0.87%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| St Petersburg     | 3         | 2.46%   |
| Paris             | 3         | 2.46%   |
| Jakarta           | 3         | 2.46%   |
| San Ramon         | 2         | 1.64%   |
| Samara            | 2         | 1.64%   |
| Rio de Janeiro    | 2         | 1.64%   |
| Prague            | 2         | 1.64%   |
| Omaha             | 2         | 1.64%   |
| Neuchatel         | 2         | 1.64%   |
| Moscow            | 2         | 1.64%   |
| Milton            | 2         | 1.64%   |
| Los Angeles       | 2         | 1.64%   |
| Frankfurt am Main | 2         | 1.64%   |
| Dnipro            | 2         | 1.64%   |
| Ankara            | 2         | 1.64%   |
| Amsterdam         | 2         | 1.64%   |
| Zaporizhzhya      | 1         | 0.82%   |
| Woodbridge        | 1         | 0.82%   |
| Wigan             | 1         | 0.82%   |
| Wem               | 1         | 0.82%   |
| Vilnius           | 1         | 0.82%   |
| Varna             | 1         | 0.82%   |
| Vancouver         | 1         | 0.82%   |
| Toronto           | 1         | 0.82%   |
| Tokyo             | 1         | 0.82%   |
| Timișoara        | 1         | 0.82%   |
| Tel Aviv          | 1         | 0.82%   |
| Tashkent          | 1         | 0.82%   |
| Syeverodonets'k   | 1         | 0.82%   |
| Surgut            | 1         | 0.82%   |
| Sun Prairie       | 1         | 0.82%   |
| Stuttgart         | 1         | 0.82%   |
| Stockholm         | 1         | 0.82%   |
| Sofia             | 1         | 0.82%   |
| Snohomish         | 1         | 0.82%   |
| Skikda            | 1         | 0.82%   |
| Sigogne           | 1         | 0.82%   |
| Seville           | 1         | 0.82%   |
| Semarang          | 1         | 0.82%   |
| Seattle           | 1         | 0.82%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 29        | 36     | 20.28%  |
| Seagate                      | 16        | 16     | 11.19%  |
| WDC                          | 12        | 15     | 8.39%   |
| Toshiba                      | 11        | 11     | 7.69%   |
| SanDisk                      | 8         | 8      | 5.59%   |
| Intel                        | 7         | 9      | 4.9%    |
| HGST                         | 7         | 7      | 4.9%    |
| Kingston                     | 6         | 7      | 4.2%    |
| SK hynix                     | 5         | 11     | 3.5%    |
| Phison Electronics           | 4         | 6      | 2.8%    |
| Hitachi                      | 4         | 5      | 2.8%    |
| Crucial                      | 4         | 5      | 2.8%    |
| China                        | 4         | 4      | 2.8%    |
| Unknown                      | 3         | 3      | 2.1%    |
| Apple                        | 3         | 4      | 2.1%    |
| Union Memory (Shenzhen)      | 1         | 1      | 0.7%    |
| Timetec                      | 1         | 2      | 0.7%    |
| SPCC                         | 1         | 1      | 0.7%    |
| Solid State Storage          | 1         | 1      | 0.7%    |
| Shenzhen Longsys Electronics | 1         | 1      | 0.7%    |
| PNY                          | 1         | 1      | 0.7%    |
| Phison                       | 1         | 1      | 0.7%    |
| Patriot                      | 1         | 1      | 0.7%    |
| Micron/Crucial Technology    | 1         | 1      | 0.7%    |
| Micron Technology            | 1         | 1      | 0.7%    |
| LITEON                       | 1         | 1      | 0.7%    |
| Lite-On                      | 1         | 1      | 0.7%    |
| Linux                        | 1         | 1      | 0.7%    |
| LDLC                         | 1         | 5      | 0.7%    |
| JMicron Technology           | 1         | 1      | 0.7%    |
| Intenso                      | 1         | 1      | 0.7%    |
| Hewlett-Packard              | 1         | 1      | 0.7%    |
| AGI                          | 1         | 1      | 0.7%    |
| A-DATA Technology            | 1         | 1      | 0.7%    |
| Unknown                      | 1         | 1      | 0.7%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 4         | 2.65%   |
| SanDisk NVMe SSD Drive 512GB                        | 4         | 2.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 4         | 2.65%   |
| China SATA SSD 960GB                                | 3         | 1.99%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 1.32%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 1.32%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 1.32%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 1.32%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 1.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 1.32%   |
| Samsung NVMe SSD Drive 1TB                          | 2         | 1.32%   |
| Samsung MZNLH512HALU-00000 512GB SSD                | 2         | 1.32%   |
| Phison PCIe SSD 256GB                               | 2         | 1.32%   |
| Phison E12 NVMe Controller 1024GB                   | 2         | 1.32%   |
| Kingston OM8PCP3512F-AI1 512GB                      | 2         | 1.32%   |
| HGST HTS545050A7E680 500GB                          | 2         | 1.32%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 1.32%   |
| Apple SSD SM0256G 256GB                             | 2         | 1.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.66%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                      | 1         | 0.66%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 0.66%   |
| WDC WD5000LPVX-55V0TT0 500GB                        | 1         | 0.66%   |
| WDC WD5000BPVT-22HXZT3 500GB                        | 1         | 0.66%   |
| WDC WD50 00LPVX-75V0TT0 500GB                       | 1         | 0.66%   |
| WDC WD3200LPVT-00FMCT0 320GB                        | 1         | 0.66%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 0.66%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 1         | 0.66%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 0.66%   |
| Unknown SD/MMC/MS PRO 16GB                          | 1         | 0.66%   |
| Unknown MMC Card  128GB                             | 1         | 0.66%   |
| Unknown DA4064  64GB                                | 1         | 0.66%   |
| Union Memory (Shenzhen) UMIS RPEYJ512VMM2QWY 512GB  | 1         | 0.66%   |
| Toshiba THNSNH128GMCT 128GB SSD                     | 1         | 0.66%   |
| Toshiba MQ01ACF032 320GB                            | 1         | 0.66%   |
| Toshiba MK5065GSX 500GB                             | 1         | 0.66%   |
| Toshiba KBG30ZMT256G 256GB                          | 1         | 0.66%   |
| Toshiba HDWL110 1TB                                 | 1         | 0.66%   |
| Timetec 35TTM8SSATA-512GB                           | 1         | 0.66%   |
| SPCC Solid State Disk 256GB                         | 1         | 0.66%   |
| Solid State Storage SSSTC CL1-4D256 256GB           | 1         | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 16     | 34.04%  |
| WDC     | 10        | 12     | 21.28%  |
| Toshiba | 9         | 9      | 19.15%  |
| HGST    | 7         | 7      | 14.89%  |
| Hitachi | 4         | 5      | 8.51%   |
| Unknown | 1         | 1      | 2.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 28.21%  |
| Crucial             | 4         | 5      | 10.26%  |
| China               | 4         | 4      | 10.26%  |
| Kingston            | 3         | 3      | 7.69%   |
| Apple               | 3         | 4      | 7.69%   |
| WDC                 | 2         | 3      | 5.13%   |
| Toshiba             | 1         | 1      | 2.56%   |
| SPCC                | 1         | 1      | 2.56%   |
| SK hynix            | 1         | 1      | 2.56%   |
| SanDisk             | 1         | 1      | 2.56%   |
| PNY                 | 1         | 1      | 2.56%   |
| Patriot             | 1         | 1      | 2.56%   |
| Linux               | 1         | 1      | 2.56%   |
| LDLC                | 1         | 5      | 2.56%   |
| Intenso             | 1         | 1      | 2.56%   |
| Intel               | 1         | 1      | 2.56%   |
| Hewlett-Packard     | 1         | 1      | 2.56%   |
| AGI                 | 1         | 1      | 2.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 46        | 69     | 34.33%  |
| HDD     | 46        | 50     | 34.33%  |
| SSD     | 37        | 47     | 27.61%  |
| Unknown | 3         | 4      | 2.24%   |
| MMC     | 2         | 2      | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 76        | 97     | 59.84%  |
| NVMe | 46        | 69     | 36.22%  |
| SAS  | 3         | 4      | 2.36%   |
| MMC  | 2         | 2      | 1.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 49        | 59     | 60.49%  |
| 0.51-1.0   | 28        | 33     | 34.57%  |
| 1.01-2.0   | 3         | 4      | 3.7%    |
| 4.01-10.0  | 1         | 1      | 1.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 34        | 28.57%  |
| 101-250        | 29        | 24.37%  |
| 501-1000       | 18        | 15.13%  |
| 1001-2000      | 13        | 10.92%  |
| Unknown        | 7         | 5.88%   |
| 51-100         | 6         | 5.04%   |
| 1-20           | 5         | 4.2%    |
| More than 3000 | 4         | 3.36%   |
| 2001-3000      | 2         | 1.68%   |
| 21-50          | 1         | 0.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 35        | 27.56%  |
| 101-250        | 24        | 18.9%   |
| 51-100         | 17        | 13.39%  |
| 21-50          | 15        | 11.81%  |
| 251-500        | 13        | 10.24%  |
| 501-1000       | 11        | 8.66%   |
| Unknown        | 7         | 5.51%   |
| 1001-2000      | 3         | 2.36%   |
| More than 3000 | 1         | 0.79%   |
| 2001-3000      | 1         | 0.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 11.76%  |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 11.76%  |
| WDC WD5000LPVX-55V0TT0 500GB                     | 1         | 1      | 5.88%   |
| WDC WD3200LPVT-00FMCT0 320GB                     | 1         | 1      | 5.88%   |
| WDC WD10SPCX-24HWST1 1TB                         | 1         | 1      | 5.88%   |
| Toshiba MQ01ACF032 320GB                         | 1         | 1      | 5.88%   |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 5.88%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 5.88%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 5.88%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 5.88%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 5.88%   |
| LDLC SSD 120GB                                   | 1         | 3      | 5.88%   |
| Hitachi HTS547550A9E384 500GB                    | 1         | 1      | 5.88%   |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 5.88%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 4         | 4      | 23.53%  |
| WDC                 | 3         | 3      | 17.65%  |
| Seagate             | 3         | 3      | 17.65%  |
| HGST                | 3         | 3      | 17.65%  |
| Hitachi             | 2         | 2      | 11.76%  |
| Samsung Electronics | 1         | 1      | 5.88%   |
| LDLC                | 1         | 3      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 4         | 4      | 26.67%  |
| WDC     | 3         | 3      | 20%     |
| Seagate | 3         | 3      | 20%     |
| HGST    | 3         | 3      | 20%     |
| Hitachi | 2         | 2      | 13.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 15     | 88.24%  |
| SSD  | 2         | 4      | 11.76%  |

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
| Works    | 63        | 81     | 51.22%  |
| Detected | 43        | 72     | 34.96%  |
| Malfunc  | 17        | 19     | 13.82%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 73        | 52.14%  |
| Samsung Electronics            | 20        | 14.29%  |
| AMD                            | 18        | 12.86%  |
| SanDisk                        | 7         | 5%      |
| SK hynix                       | 4         | 2.86%   |
| Phison Electronics             | 4         | 2.86%   |
| Kingston Technology Company    | 3         | 2.14%   |
| Union Memory (Shenzhen)        | 2         | 1.43%   |
| Toshiba America Info Systems   | 1         | 0.71%   |
| Solid State Storage Technology | 1         | 0.71%   |
| Shenzhen Longsys Electronics   | 1         | 0.71%   |
| Nvidia                         | 1         | 0.71%   |
| Micron/Crucial Technology      | 1         | 0.71%   |
| Micron Technology              | 1         | 0.71%   |
| Marvell Technology Group       | 1         | 0.71%   |
| Lite-On Technology             | 1         | 0.71%   |
| ADATA Technology               | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 16        | 10.96%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 11        | 7.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 10        | 6.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 10        | 6.85%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 8         | 5.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 7         | 4.79%   |
| Samsung NVMe SSD Controller 980                                               | 5         | 3.42%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 4         | 2.74%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 4         | 2.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 4         | 2.74%   |
| SK hynix Non-Volatile memory controller                                       | 3         | 2.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 3         | 2.05%   |
| Phison E12 NVMe Controller                                                    | 3         | 2.05%   |
| Kingston Company Company Non-Volatile memory controller                       | 3         | 2.05%   |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 2.05%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 3         | 2.05%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 3         | 2.05%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 3         | 2.05%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                        | 2         | 1.37%   |
| SanDisk Non-Volatile memory controller                                        | 2         | 1.37%   |
| Samsung Electronics SATA controller                                           | 2         | 1.37%   |
| Intel SSD 660P Series                                                         | 2         | 1.37%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 1.37%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 1.37%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 2         | 1.37%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 2         | 1.37%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                          | 1         | 0.68%   |
| Solid State Storage Non-Volatile memory controller                            | 1         | 0.68%   |
| SK hynix BC511                                                                | 1         | 0.68%   |
| Shenzhen Longsys Non-Volatile memory controller                               | 1         | 0.68%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1         | 0.68%   |
| Phison E16 PCIe4 NVMe Controller                                              | 1         | 0.68%   |
| Nvidia MCP79 AHCI Controller                                                  | 1         | 0.68%   |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 1         | 0.68%   |
| Micron Non-Volatile memory controller                                         | 1         | 0.68%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                    | 1         | 0.68%   |
| Lite-On Non-Volatile memory controller                                        | 1         | 0.68%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 0.68%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 82        | 58.16%  |
| NVMe | 47        | 33.33%  |
| RAID | 11        | 7.8%    |
| IDE  | 1         | 0.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 91        | 79.13%  |
| AMD    | 24        | 20.87%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 4700U with Radeon Graphics        | 4         | 3.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 2.59%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.59%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 1.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 1.72%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.72%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.72%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 1.72%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 1.72%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 1.72%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 1.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 1.72%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.72%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.72%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 2         | 1.72%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 2         | 1.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 1.72%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.72%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.72%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz          | 1         | 0.86%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.86%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.86%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 1         | 0.86%   |
| Intel Pentium CPU A1018 @ 2.10GHz             | 1         | 0.86%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 1         | 0.86%   |
| Intel Core i9-8950HK CPU @ 2.90GHz            | 1         | 0.86%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 1         | 0.86%   |
| Intel Core i7-9750HF CPU @ 2.60GHz            | 1         | 0.86%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.86%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.86%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.86%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.86%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.86%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 1         | 0.86%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.86%   |
| Intel Core i7-2860QM CPU @ 2.50GHz            | 1         | 0.86%   |
| Intel Core i7-2820QM CPU @ 2.30GHz            | 1         | 0.86%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 1         | 0.86%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 0.86%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 31        | 26.96%  |
| Intel Core i7           | 24        | 20.87%  |
| Intel Core i3           | 11        | 9.57%   |
| AMD Ryzen 7             | 10        | 8.7%    |
| Other                   | 7         | 6.09%   |
| Intel Celeron           | 6         | 5.22%   |
| Intel Pentium           | 3         | 2.61%   |
| AMD Ryzen 5             | 3         | 2.61%   |
| AMD Ryzen 3             | 3         | 2.61%   |
| Intel Core m3           | 2         | 1.74%   |
| Intel Core i9           | 2         | 1.74%   |
| Intel Xeon              | 1         | 0.87%   |
| Intel Pentium Silver    | 1         | 0.87%   |
| Intel Pentium Dual-Core | 1         | 0.87%   |
| Intel Core 2 Duo        | 1         | 0.87%   |
| Intel Atom              | 1         | 0.87%   |
| AMD Ryzen 9             | 1         | 0.87%   |
| AMD Ryzen 7 PRO         | 1         | 0.87%   |
| AMD Ryzen 5 PRO         | 1         | 0.87%   |
| AMD Phenom II           | 1         | 0.87%   |
| AMD E1                  | 1         | 0.87%   |
| AMD Athlon              | 1         | 0.87%   |
| AMD A6                  | 1         | 0.87%   |
| AMD A10                 | 1         | 0.87%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 52        | 45.22%  |
| 4      | 41        | 35.65%  |
| 8      | 12        | 10.43%  |
| 6      | 9         | 7.83%   |
| 12     | 1         | 0.87%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 115       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 92        | 80%     |
| 1      | 23        | 20%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 115       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 19        | 16.24%  |
| 0x306a9    | 10        | 8.55%   |
| 0x206a7    | 9         | 7.69%   |
| 0xa0652    | 5         | 4.27%   |
| 0x806ec    | 5         | 4.27%   |
| 0x806e9    | 5         | 4.27%   |
| 0x40651    | 5         | 4.27%   |
| 0x306d4    | 5         | 4.27%   |
| 0x806ea    | 4         | 3.42%   |
| 0x806c1    | 4         | 3.42%   |
| 0x706e5    | 4         | 3.42%   |
| 0x08600106 | 4         | 3.42%   |
| 0x906ea    | 3         | 2.56%   |
| 0x906e9    | 3         | 2.56%   |
| 0x706a1    | 3         | 2.56%   |
| 0x30678    | 2         | 1.71%   |
| 0x1067a    | 2         | 1.71%   |
| 0x08600103 | 2         | 1.71%   |
| 0x08108109 | 2         | 1.71%   |
| 0x08108102 | 2         | 1.71%   |
| 0x906ed    | 1         | 0.85%   |
| 0x806eb    | 1         | 0.85%   |
| 0x806d1    | 1         | 0.85%   |
| 0x806c2    | 1         | 0.85%   |
| 0x506e3    | 1         | 0.85%   |
| 0x506c9    | 1         | 0.85%   |
| 0x406e3    | 1         | 0.85%   |
| 0x306c3    | 1         | 0.85%   |
| 0x20655    | 1         | 0.85%   |
| 0x0a50000c | 1         | 0.85%   |
| 0x08701013 | 1         | 0.85%   |
| 0x08608103 | 1         | 0.85%   |
| 0x08600104 | 1         | 0.85%   |
| 0x0810100b | 1         | 0.85%   |
| 0x08101007 | 1         | 0.85%   |
| 0x08001137 | 1         | 0.85%   |
| 0x0700010b | 1         | 0.85%   |
| 0x06003109 | 1         | 0.85%   |
| 0x010000c8 | 1         | 0.85%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 28        | 24.35%  |
| IvyBridge     | 12        | 10.43%  |
| Zen 2         | 9         | 7.83%   |
| SandyBridge   | 9         | 7.83%   |
| Haswell       | 7         | 6.09%   |
| TigerLake     | 6         | 5.22%   |
| CometLake     | 6         | 5.22%   |
| Broadwell     | 6         | 5.22%   |
| Zen+          | 5         | 4.35%   |
| IceLake       | 4         | 3.48%   |
| Zen           | 3         | 2.61%   |
| Goldmont plus | 3         | 2.61%   |
| Unknown       | 3         | 2.61%   |
| Skylake       | 2         | 1.74%   |
| Silvermont    | 2         | 1.74%   |
| Penryn        | 2         | 1.74%   |
| Zen 3         | 1         | 0.87%   |
| Westmere      | 1         | 0.87%   |
| Steamroller   | 1         | 0.87%   |
| Puma          | 1         | 0.87%   |
| K10           | 1         | 0.87%   |
| Jaguar        | 1         | 0.87%   |
| Goldmont      | 1         | 0.87%   |
| Bonnell       | 1         | 0.87%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 84        | 58.74%  |
| Nvidia | 30        | 20.98%  |
| AMD    | 29        | 20.28%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 10        | 6.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 7         | 4.83%   |
| AMD Renoir                                                                | 7         | 4.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 6         | 4.14%   |
| Intel HD Graphics 620                                                     | 6         | 4.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 4.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 6         | 4.14%   |
| Intel UHD Graphics 620                                                    | 5         | 3.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 3.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 2.76%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 2.76%   |
| Intel HD Graphics 5500                                                    | 4         | 2.76%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 3         | 2.07%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 2.07%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 2.07%   |
| Nvidia TU117M                                                             | 2         | 1.38%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 2         | 1.38%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 1.38%   |
| Intel UHD Graphics 615                                                    | 2         | 1.38%   |
| Intel HD Graphics 630                                                     | 2         | 1.38%   |
| Intel HD Graphics 6000                                                    | 2         | 1.38%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 1.38%   |
| AMD Saturn XT [FirePro M6100]                                             | 2         | 1.38%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.38%   |
| AMD Lucienne                                                              | 2         | 1.38%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.69%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.69%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.69%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.69%   |
| Nvidia GP108M [GeForce MX330]                                             | 1         | 0.69%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.69%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 0.69%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                  | 1         | 0.69%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.69%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.69%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                     | 1         | 0.69%   |
| Nvidia GM107 [GeForce 940MX]                                              | 1         | 0.69%   |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 57        | 49.14%  |
| Intel + Nvidia | 23        | 19.83%  |
| 1 x AMD        | 23        | 19.83%  |
| 1 x Nvidia     | 6         | 5.17%   |
| Intel + AMD    | 4         | 3.45%   |
| 2 x AMD        | 2         | 1.72%   |
| AMD + Nvidia   | 1         | 0.86%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 97        | 84.35%  |
| Proprietary | 18        | 15.65%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 76        | 65.52%  |
| 1.01-2.0   | 13        | 11.21%  |
| 0.01-0.5   | 11        | 9.48%   |
| 3.01-4.0   | 5         | 4.31%   |
| 0.51-1.0   | 5         | 4.31%   |
| 5.01-6.0   | 3         | 2.59%   |
| 7.01-8.0   | 2         | 1.72%   |
| 2.01-3.0   | 1         | 0.86%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 26        | 19.4%   |
| BOE                     | 21        | 15.67%  |
| LG Display              | 20        | 14.93%  |
| Chimei Innolux          | 16        | 11.94%  |
| Samsung Electronics     | 11        | 8.21%   |
| Dell                    | 4         | 2.99%   |
| Chi Mei Optoelectronics | 4         | 2.99%   |
| InfoVision              | 3         | 2.24%   |
| Goldstar                | 3         | 2.24%   |
| ASUSTek Computer        | 3         | 2.24%   |
| Apple                   | 3         | 2.24%   |
| Sharp                   | 2         | 1.49%   |
| PANDA                   | 2         | 1.49%   |
| Hewlett-Packard         | 2         | 1.49%   |
| BenQ                    | 2         | 1.49%   |
| Sony                    | 1         | 0.75%   |
| Philips                 | 1         | 0.75%   |
| MSI                     | 1         | 0.75%   |
| LGD                     | 1         | 0.75%   |
| Lenovo                  | 1         | 0.75%   |
| KDC                     | 1         | 0.75%   |
| HUAWEI                  | 1         | 0.75%   |
| HKC                     | 1         | 0.75%   |
| CSO                     | 1         | 0.75%   |
| AOC                     | 1         | 0.75%   |
| Ancor Communications    | 1         | 0.75%   |
| Acer                    | 1         | 0.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 4         | 2.99%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 2.24%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 1.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 1.49%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.49%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 1.49%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 1.49%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 1.49%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 1.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 1.49%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 2         | 1.49%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 1.49%   |
| Sony BW8 MS_9001 1600x2560 113x181mm 8.4-inch                             | 1         | 0.75%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 0.75%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.75%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 0.75%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch      | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch      | 1         | 0.75%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                   | 1         | 0.75%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 1         | 0.75%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                   | 1         | 0.75%   |
| MSI MAG341CQ MSI1462 3440x1440 797x334mm 34.0-inch                        | 1         | 0.75%   |
| LGD LCD Monitor 1920x1080                                                 | 1         | 0.75%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch               | 1         | 0.75%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 1         | 0.75%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch               | 1         | 0.75%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch               | 1         | 0.75%   |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch              | 1         | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 58        | 45.67%  |
| 1366x768 (WXGA)    | 44        | 34.65%  |
| 1600x900 (HD+)     | 5         | 3.94%   |
| 3840x2160 (4K)     | 4         | 3.15%   |
| 2560x1600          | 4         | 3.15%   |
| 2560x1440 (QHD)    | 4         | 3.15%   |
| 1440x900 (WXGA+)   | 4         | 3.15%   |
| 3440x1440          | 1         | 0.79%   |
| 2160x1440          | 1         | 0.79%   |
| 1920x1200 (WUXGA)  | 1         | 0.79%   |
| 1680x1050 (WSXGA+) | 1         | 0.79%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 58        | 43.61%  |
| 14      | 20        | 15.04%  |
| 13      | 19        | 14.29%  |
| 17      | 9         | 6.77%   |
| 27      | 6         | 4.51%   |
| 21      | 6         | 4.51%   |
| 24      | 5         | 3.76%   |
| 23      | 2         | 1.5%    |
| 34      | 1         | 0.75%   |
| 20      | 1         | 0.75%   |
| 19      | 1         | 0.75%   |
| 16      | 1         | 0.75%   |
| 12      | 1         | 0.75%   |
| 11      | 1         | 0.75%   |
| 8       | 1         | 0.75%   |
| Unknown | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 88        | 66.17%  |
| 351-400     | 13        | 9.77%   |
| 501-600     | 11        | 8.27%   |
| 401-500     | 8         | 6.02%   |
| 201-300     | 8         | 6.02%   |
| 601-700     | 2         | 1.5%    |
| 701-800     | 1         | 0.75%   |
| 101-200     | 1         | 0.75%   |
| Unknown     | 1         | 0.75%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 102       | 88.7%   |
| 16/10   | 9         | 7.83%   |
| 3/2     | 1         | 0.87%   |
| 21/9    | 1         | 0.87%   |
| 0.62    | 1         | 0.87%   |
| Unknown | 1         | 0.87%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 58        | 43.61%  |
| 81-90          | 33        | 24.81%  |
| 201-250        | 11        | 8.27%   |
| 121-130        | 8         | 6.02%   |
| 71-80          | 6         | 4.51%   |
| 301-350        | 6         | 4.51%   |
| 151-200        | 3         | 2.26%   |
| 61-70          | 1         | 0.75%   |
| 51-60          | 1         | 0.75%   |
| 351-500        | 1         | 0.75%   |
| 1-40           | 1         | 0.75%   |
| 251-300        | 1         | 0.75%   |
| 131-140        | 1         | 0.75%   |
| 111-120        | 1         | 0.75%   |
| Unknown        | 1         | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 58        | 45.67%  |
| 101-120       | 42        | 33.07%  |
| 51-100        | 18        | 14.17%  |
| 161-240       | 6         | 4.72%   |
| More than 240 | 2         | 1.57%   |
| Unknown       | 1         | 0.79%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 97        | 82.2%   |
| 2     | 21        | 17.8%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 74        | 38.74%  |
| Intel                    | 64        | 33.51%  |
| Qualcomm Atheros         | 20        | 10.47%  |
| Broadcom                 | 10        | 5.24%   |
| Broadcom Limited         | 4         | 2.09%   |
| Samsung Electronics      | 2         | 1.05%   |
| Ralink                   | 2         | 1.05%   |
| Qualcomm                 | 2         | 1.05%   |
| MediaTek                 | 2         | 1.05%   |
| Xiaomi                   | 1         | 0.52%   |
| TP-Link                  | 1         | 0.52%   |
| Sierra Wireless          | 1         | 0.52%   |
| Ralink Technology        | 1         | 0.52%   |
| OPPO                     | 1         | 0.52%   |
| Marvell Technology Group | 1         | 0.52%   |
| Linksys                  | 1         | 0.52%   |
| Lenovo                   | 1         | 0.52%   |
| Huawei Technologies      | 1         | 0.52%   |
| ASIX Electronics         | 1         | 0.52%   |
| Apple                    | 1         | 0.52%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 20.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 5.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 3.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 3.13%   |
| Intel Wireless 8265 / 8275                                        | 7         | 3.13%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 3.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 2.23%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 2.23%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 2.23%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 2.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 2.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.79%   |
| Intel Wireless 7265                                               | 4         | 1.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.34%   |
| Intel Wireless 7260                                               | 3         | 1.34%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 1.34%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.34%   |
| Intel Centrino Wireless-N 2230                                    | 3         | 1.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.34%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.34%   |
| Realtek 802.11ac NIC                                              | 2         | 0.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.89%   |
| Intel Wireless 3165                                               | 2         | 0.89%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.89%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.89%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.45%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.45%   |
| Sierra Wireless MC7700                                            | 1         | 0.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.45%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 60        | 50%     |
| Realtek Semiconductor | 22        | 18.33%  |
| Qualcomm Atheros      | 17        | 14.17%  |
| Broadcom              | 9         | 7.5%    |
| Broadcom Limited      | 4         | 3.33%   |
| Ralink                | 2         | 1.67%   |
| MediaTek              | 2         | 1.67%   |
| TP-Link               | 1         | 0.83%   |
| Sierra Wireless       | 1         | 0.83%   |
| Ralink Technology     | 1         | 0.83%   |
| Qualcomm              | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 5.74%   |
| Intel Wireless 8265 / 8275                                     | 7         | 5.74%   |
| Intel Wi-Fi 6 AX200                                            | 7         | 5.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 4.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 4.1%    |
| Intel Wi-Fi 6 AX201                                            | 5         | 4.1%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 4.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 4.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 4.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 3.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 3.28%   |
| Intel Wireless 7265                                            | 4         | 3.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2.46%   |
| Intel Wireless 7260                                            | 3         | 2.46%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 2.46%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 2.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 2.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.46%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 2.46%   |
| Realtek 802.11ac NIC                                           | 2         | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.64%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.64%   |
| Intel Wireless 3165                                            | 2         | 1.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.64%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.64%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.64%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.82%   |
| Sierra Wireless MC7700                                         | 1         | 0.82%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.82%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.82%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.82%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.82%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1         | 0.82%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.82%   |
| Intel Wireless-AC 9260                                         | 1         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 66        | 66%     |
| Intel                    | 18        | 18%     |
| Qualcomm Atheros         | 4         | 4%      |
| Samsung Electronics      | 2         | 2%      |
| Xiaomi                   | 1         | 1%      |
| Qualcomm                 | 1         | 1%      |
| OPPO                     | 1         | 1%      |
| Marvell Technology Group | 1         | 1%      |
| Linksys                  | 1         | 1%      |
| Lenovo                   | 1         | 1%      |
| Huawei Technologies      | 1         | 1%      |
| Broadcom                 | 1         | 1%      |
| ASIX Electronics         | 1         | 1%      |
| Apple                    | 1         | 1%      |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 46.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 12.75%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 7.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 5.88%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.94%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 1.96%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.98%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.98%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.98%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.98%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.98%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.98%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.98%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.98%   |
| Qualcomm A0001                                                    | 1         | 0.98%   |
| OPPO CPH1923                                                      | 1         | 0.98%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.98%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.98%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.98%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.98%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.98%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.98%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.98%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.98%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.98%   |
| Huawei E353/E3131                                                 | 1         | 0.98%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.98%   |
| ASIX AX88772                                                      | 1         | 0.98%   |
| Apple iPad 4/Mini1                                                | 1         | 0.98%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 113       | 55.67%  |
| Ethernet | 90        | 44.33%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 94        | 77.05%  |
| Ethernet | 28        | 22.95%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 81        | 69.83%  |
| 1     | 32        | 27.59%  |
| 3     | 2         | 1.72%   |
| 0     | 1         | 0.86%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 101       | 84.87%  |
| Yes  | 18        | 15.13%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 49        | 51.04%  |
| Realtek Semiconductor           | 16        | 16.67%  |
| Broadcom                        | 8         | 8.33%   |
| Qualcomm Atheros Communications | 4         | 4.17%   |
| Lite-On Technology              | 4         | 4.17%   |
| IMC Networks                    | 3         | 3.13%   |
| Foxconn / Hon Hai               | 3         | 3.13%   |
| Apple                           | 3         | 3.13%   |
| Realtek                         | 2         | 2.08%   |
| Cambridge Silicon Radio         | 2         | 2.08%   |
| Ralink                          | 1         | 1.04%   |
| ASUSTek Computer                | 1         | 1.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 15        | 15.46%  |
| Intel AX201 Bluetooth                               | 13        | 13.4%   |
| Realtek Bluetooth Radio                             | 10        | 10.31%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 8.25%   |
| Intel AX200 Bluetooth                               | 7         | 7.22%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 4.12%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 3.09%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 3.09%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 3.09%   |
| Realtek Bluetooth Radio                             | 2         | 2.06%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.06%   |
| IMC Networks Wireless_Device                        | 2         | 2.06%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 2.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.06%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.06%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 2.06%   |
| Apple Bluetooth USB Host Controller                 | 2         | 2.06%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.03%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.03%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.03%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.03%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.03%   |
| Intel AX210 Bluetooth                               | 1         | 1.03%   |
| IMC Networks Bluetooth Device                       | 1         | 1.03%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.03%   |
| Broadcom HP Portable Valentine                      | 1         | 1.03%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.03%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 1.03%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.03%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.03%   |
| Apple Bluetooth Host Controller                     | 1         | 1.03%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 90        | 61.22%  |
| AMD                   | 26        | 17.69%  |
| Nvidia                | 19        | 12.93%  |
| Realtek Semiconductor | 3         | 2.04%   |
| C-Media Electronics   | 3         | 2.04%   |
| Plantronics           | 1         | 0.68%   |
| Lenovo                | 1         | 0.68%   |
| Harman                | 1         | 0.68%   |
| GN Netcom             | 1         | 0.68%   |
| Corsair               | 1         | 0.68%   |
| Arylic                | 1         | 0.68%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 18        | 9.78%   |
| Intel Sunrise Point-LP HD Audio                                            | 15        | 8.15%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 12        | 6.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 4.89%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 4.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 3.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 3.26%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 3.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 3.26%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 3.26%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 3.26%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 3.26%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 2.17%   |
| Intel CM238 HD Audio Controller                                            | 4         | 2.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.17%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.63%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.63%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.63%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.63%   |
| Realtek Semiconductor USB Audio                                            | 2         | 1.09%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.09%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.09%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.09%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 1.09%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 2         | 1.09%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.09%   |
| Realtek Semiconductor USB Condenser Microphone                             | 1         | 0.54%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.54%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.54%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.54%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.54%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.54%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.54%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.54%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.54%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 1         | 0.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 37        | 30.33%  |
| SK hynix            | 31        | 25.41%  |
| Kingston            | 14        | 11.48%  |
| Micron Technology   | 11        | 9.02%   |
| Unknown             | 4         | 3.28%   |
| A-DATA Technology   | 4         | 3.28%   |
| Silicon Power       | 3         | 2.46%   |
| Unknown             | 3         | 2.46%   |
| Unknown (ABCD)      | 2         | 1.64%   |
| Smart               | 2         | 1.64%   |
| Ramaxel Technology  | 2         | 1.64%   |
| Nanya Technology    | 2         | 1.64%   |
| Corsair             | 2         | 1.64%   |
| Team                | 1         | 0.82%   |
| Smart Brazil        | 1         | 0.82%   |
| Crucial             | 1         | 0.82%   |
| ASint Technology    | 1         | 0.82%   |
| AMD                 | 1         | 0.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 3.13%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 3.13%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.34%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.34%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 3         | 2.34%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 2.34%   |
| Unknown                                                          | 3         | 2.34%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.56%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.56%   |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.56%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.56%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 2         | 1.56%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 1.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.56%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.56%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.56%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.56%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.56%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.78%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.78%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.78%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.78%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.78%   |
| Smart RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 3200MT/s         | 1         | 0.78%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2400MT/s            | 1         | 0.78%   |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s     | 1         | 0.78%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.78%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.78%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.78%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.78%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.78%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.78%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 52        | 52%     |
| DDR3    | 37        | 37%     |
| LPDDR4  | 4         | 4%      |
| LPDDR3  | 4         | 4%      |
| SDRAM   | 2         | 2%      |
| Unknown | 1         | 1%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 87        | 86.14%  |
| Row Of Chips | 11        | 10.89%  |
| DIMM         | 1         | 0.99%   |
| Chip         | 1         | 0.99%   |
| Unknown      | 1         | 0.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 44        | 38.6%   |
| 8192  | 41        | 35.96%  |
| 16384 | 14        | 12.28%  |
| 2048  | 11        | 9.65%   |
| 32768 | 3         | 2.63%   |
| 1024  | 1         | 0.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 35        | 32.71%  |
| 3200  | 24        | 22.43%  |
| 2667  | 21        | 19.63%  |
| 2400  | 10        | 9.35%   |
| 1333  | 4         | 3.74%   |
| 2133  | 3         | 2.8%    |
| 1334  | 3         | 2.8%    |
| 4199  | 2         | 1.87%   |
| 4267  | 1         | 0.93%   |
| 3400  | 1         | 0.93%   |
| 3266  | 1         | 0.93%   |
| 1067  | 1         | 0.93%   |
| 1066  | 1         | 0.93%   |

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
| Chicony Electronics                    | 24        | 23.76%  |
| IMC Networks                           | 11        | 10.89%  |
| Acer                                   | 11        | 10.89%  |
| Realtek Semiconductor                  | 10        | 9.9%    |
| Quanta                                 | 10        | 9.9%    |
| Suyin                                  | 6         | 5.94%   |
| Alcor Micro                            | 5         | 4.95%   |
| Microdia                               | 4         | 3.96%   |
| Syntek                                 | 3         | 2.97%   |
| Sunplus Innovation Technology          | 3         | 2.97%   |
| Silicon Motion                         | 3         | 2.97%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.97%   |
| Sonix Technology                       | 2         | 1.98%   |
| DLEQNA19IFK6G2                         | 2         | 1.98%   |
| Luxvisions Innotech Limited            | 1         | 0.99%   |
| Lite-On Technology                     | 1         | 0.99%   |
| LG Electronics                         | 1         | 0.99%   |
| Lenovo                                 | 1         | 0.99%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                       | 7         | 6.93%   |
| Chicony HD WebCam                                    | 6         | 5.94%   |
| Realtek Integrated_Webcam_HD                         | 4         | 3.96%   |
| Chicony Integrated Camera                            | 4         | 3.96%   |
| Acer Integrated Camera                               | 4         | 3.96%   |
| Quanta HP TrueVision HD Camera                       | 3         | 2.97%   |
| Syntek EasyCamera                                    | 2         | 1.98%   |
| Suyin HP Webcam                                      | 2         | 1.98%   |
| Sonix USB2.0 HD UVC WebCam                           | 2         | 1.98%   |
| Silicon Motion 300k Pixel Camera                     | 2         | 1.98%   |
| Realtek USB2.0 HD UVC WebCam                         | 2         | 1.98%   |
| Realtek HD WebCam                                    | 2         | 1.98%   |
| Quanta VGA WebCam                                    | 2         | 1.98%   |
| Quanta HP Webcam                                     | 2         | 1.98%   |
| Microdia Integrated Webcam                           | 2         | 1.98%   |
| DLEQNA19IFK6G2 HP TrueVision HD Camera               | 2         | 1.98%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 1.98%   |
| Chicony USB2.0 Camera                                | 2         | 1.98%   |
| Chicony thinkpad t430s camera                        | 2         | 1.98%   |
| Chicony Integrated Camera (1280x720@30)              | 2         | 1.98%   |
| Alcor Micro USB 2.0 Camera                           | 2         | 1.98%   |
| Acer Lenovo EasyCamera                               | 2         | 1.98%   |
| Syntek Integrated Camera                             | 1         | 0.99%   |
| Suyin USB Webcam                                     | 1         | 0.99%   |
| Suyin NEC HD WebCam                                  | 1         | 0.99%   |
| Suyin Laptop_Integrated_Webcam_HD                    | 1         | 0.99%   |
| Suyin 1.3M HD WebCam                                 | 1         | 0.99%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 0.99%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 0.99%   |
| Sunplus HD WebCam                                    | 1         | 0.99%   |
| Silicon Motion WebCam SCB-0355N                      | 1         | 0.99%   |
| Realtek Integrated Webcam                            | 1         | 0.99%   |
| Realtek HP "Truevision HD" laptop camera             | 1         | 0.99%   |
| Quanta USB2.0 VGA UVC WebCam                         | 1         | 0.99%   |
| Quanta HD Webcam                                     | 1         | 0.99%   |
| Quanta HD User Facing                                | 1         | 0.99%   |
| Microdia WebCam SC-13HDL12639P                       | 1         | 0.99%   |
| Microdia Integrated_Webcam_HD                        | 1         | 0.99%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 0.99%   |
| Lite-On HP HD Camera                                 | 1         | 0.99%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 4         | 44.44%  |
| Synaptics                  | 3         | 33.33%  |
| Validity Sensors           | 1         | 11.11%  |
| AuthenTec                  | 1         | 11.11%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 33.33%  |
| Shenzhen Goodix  FingerPrint Device               | 3         | 33.33%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader                | 1         | 11.11%  |
| AuthenTec AES2810                                 | 1         | 11.11%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 83.33%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |
| Broadcom 58200                                                               | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 77        | 65.25%  |
| 1     | 36        | 30.51%  |
| 2     | 5         | 4.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 9         | 19.15%  |
| Net/wireless             | 6         | 12.77%  |
| Multimedia controller    | 6         | 12.77%  |
| Graphics card            | 5         | 10.64%  |
| Chipcard                 | 5         | 10.64%  |
| Camera                   | 5         | 10.64%  |
| Bluetooth                | 4         | 8.51%   |
| Communication controller | 3         | 6.38%   |
| Storage                  | 2         | 4.26%   |
| Network                  | 1         | 2.13%   |
| Dvb card                 | 1         | 2.13%   |

