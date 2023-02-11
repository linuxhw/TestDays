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

Total: 157

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Artix Rolling  | 68        | 59.65%  |
| Artix          | 42        | 36.84%  |
| Artix 20220713 | 1         | 0.88%   |
| Artix 20220123 | 1         | 0.88%   |
| Artix 20201207 | 1         | 0.88%   |
| Artix 20201128 | 1         | 0.88%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Artix | 108       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.9.14-artix1-1                 | 6         | 4.65%   |
| 6.0.7-artix1-1                  | 3         | 2.33%   |
| 5.7.6-artix1-1                  | 3         | 2.33%   |
| 6.1.6-artix1-1                  | 2         | 1.55%   |
| 6.0.12-artix1-1                 | 2         | 1.55%   |
| 5.7.12-artix1-1                 | 2         | 1.55%   |
| 5.19.12-artix1-1                | 2         | 1.55%   |
| 5.18.6-artix1-1                 | 2         | 1.55%   |
| 5.18.10-artix1-1                | 2         | 1.55%   |
| 5.18.0-artix1-1                 | 2         | 1.55%   |
| 5.17.1-artix1-1                 | 2         | 1.55%   |
| 5.16.8-artix1-2                 | 2         | 1.55%   |
| 5.16.10-artix1-1                | 2         | 1.55%   |
| 5.15.12-artix1-1                | 2         | 1.55%   |
| 5.14.16-artix1-1                | 2         | 1.55%   |
| 5.13.8-artix1-1                 | 2         | 1.55%   |
| 5.12.8-artix1-1                 | 2         | 1.55%   |
| 5.12.12-zen1-1-zen              | 2         | 1.55%   |
| 5.12.12-artix1-1                | 2         | 1.55%   |
| 5.11.6-artix1-1                 | 2         | 1.55%   |
| 5.10.6-artix1-1                 | 2         | 1.55%   |
| 5.10.4-artix2-1                 | 2         | 1.55%   |
| 5.10.16-artix1-1                | 2         | 1.55%   |
| 6.0.9-hardened1-1-hardened      | 1         | 0.78%   |
| 6.0.7-zen1-1-zen                | 1         | 0.78%   |
| 6.0.5.14.realtime1-1-rt         | 1         | 0.78%   |
| 6.0.2-artix1-1.1                | 1         | 0.78%   |
| 5.9.6-artix1-1                  | 1         | 0.78%   |
| 5.9.14-zen1-1-zen               | 1         | 0.78%   |
| 5.9.12-artix1-1                 | 1         | 0.78%   |
| 5.9.1-artix1-1                  | 1         | 0.78%   |
| 5.9.0-zen1-1-zen                | 1         | 0.78%   |
| 5.9.0-1-mainline-bootsplash     | 1         | 0.78%   |
| 5.8.8-artix1-1                  | 1         | 0.78%   |
| 5.8.4-artix1-1                  | 1         | 0.78%   |
| 5.8.14-zen1-1-zen               | 1         | 0.78%   |
| 5.8.14-artix1-1                 | 1         | 0.78%   |
| 5.8.12-artix1-1                 | 1         | 0.78%   |
| 5.8.0-rc7-5-mainline-bootsplash | 1         | 0.78%   |
| 5.7.8-artix1-1                  | 1         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.9.14   | 7         | 5.43%   |
| 6.0.7    | 4         | 3.1%    |
| 5.12.12  | 4         | 3.1%    |
| 5.7.6    | 3         | 2.33%   |
| 5.17.1   | 3         | 2.33%   |
| 5.15.12  | 3         | 2.33%   |
| 5.12.8   | 3         | 2.33%   |
| 6.1.6    | 2         | 1.55%   |
| 6.0.12   | 2         | 1.55%   |
| 5.9.0    | 2         | 1.55%   |
| 5.8.14   | 2         | 1.55%   |
| 5.7.12   | 2         | 1.55%   |
| 5.19.12  | 2         | 1.55%   |
| 5.18.6   | 2         | 1.55%   |
| 5.18.10  | 2         | 1.55%   |
| 5.18.0   | 2         | 1.55%   |
| 5.16.8   | 2         | 1.55%   |
| 5.16.10  | 2         | 1.55%   |
| 5.14.16  | 2         | 1.55%   |
| 5.13.8   | 2         | 1.55%   |
| 5.12.14  | 2         | 1.55%   |
| 5.11.6   | 2         | 1.55%   |
| 5.10.6   | 2         | 1.55%   |
| 5.10.4   | 2         | 1.55%   |
| 5.10.16  | 2         | 1.55%   |
| 6.0.9    | 1         | 0.78%   |
| 6.0.5.14 | 1         | 0.78%   |
| 6.0.2    | 1         | 0.78%   |
| 5.9.6    | 1         | 0.78%   |
| 5.9.12   | 1         | 0.78%   |
| 5.9.1    | 1         | 0.78%   |
| 5.8.8    | 1         | 0.78%   |
| 5.8.4    | 1         | 0.78%   |
| 5.8.12   | 1         | 0.78%   |
| 5.8.0    | 1         | 0.78%   |
| 5.7.8    | 1         | 0.78%   |
| 5.7.2    | 1         | 0.78%   |
| 5.6.7    | 1         | 0.78%   |
| 5.5.3    | 1         | 0.78%   |
| 5.5.10   | 1         | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 13        | 10.57%  |
| 5.18    | 12        | 9.76%   |
| 5.12    | 12        | 9.76%   |
| 5.9     | 11        | 8.94%   |
| 5.10    | 11        | 8.94%   |
| 6.0     | 8         | 6.5%    |
| 5.17    | 8         | 6.5%    |
| 5.16    | 8         | 6.5%    |
| 5.11    | 8         | 6.5%    |
| 5.7     | 6         | 4.88%   |
| 5.19    | 6         | 4.88%   |
| 5.8     | 5         | 4.07%   |
| 5.14    | 4         | 3.25%   |
| 5.13    | 4         | 3.25%   |
| 6.1     | 2         | 1.63%   |
| 6.0.5   | 1         | 0.81%   |
| 5.6     | 1         | 0.81%   |
| 5.5     | 1         | 0.81%   |
| 5.4     | 1         | 0.81%   |
| 4.19    | 1         | 0.81%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 108       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| KDE5           | 26        | 22.41%  |
| XFCE           | 19        | 16.38%  |
| Unknown        | 19        | 16.38%  |
| GNOME          | 14        | 12.07%  |
| X-Cinnamon     | 7         | 6.03%   |
| MATE           | 7         | 6.03%   |
| LXQt           | 4         | 3.45%   |
| KDE            | 4         | 3.45%   |
| LXDE           | 3         | 2.59%   |
| Cinnamon       | 3         | 2.59%   |
| i3             | 2         | 1.72%   |
| bspwm          | 2         | 1.72%   |
| xmonad         | 1         | 0.86%   |
| sway-dbus      | 1         | 0.86%   |
| Sway           | 1         | 0.86%   |
| nxde           | 1         | 0.86%   |
| awesomeminimal | 1         | 0.86%   |
| awesome        | 1         | 0.86%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 79        | 70.54%  |
| Tty     | 16        | 14.29%  |
| Wayland | 11        | 9.82%   |
| Unknown | 6         | 5.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 39        | 34.82%  |
| LightDM | 37        | 33.04%  |
| SDDM    | 31        | 27.68%  |
| XDM     | 1         | 0.89%   |
| SLiM    | 1         | 0.89%   |
| Ly      | 1         | 0.89%   |
| LXDM    | 1         | 0.89%   |
| GDM     | 1         | 0.89%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 56        | 50%     |
| Unknown | 12        | 10.71%  |
| ru_RU   | 8         | 7.14%   |
| en_GB   | 7         | 6.25%   |
| C       | 4         | 3.57%   |
| fr_FR   | 3         | 2.68%   |
| pl_PL   | 2         | 1.79%   |
| es_ES   | 2         | 1.79%   |
| en_CA   | 2         | 1.79%   |
| en_AG   | 2         | 1.79%   |
| uk_UA   | 1         | 0.89%   |
| tr_TR   | 1         | 0.89%   |
| ro_RO   | 1         | 0.89%   |
| pt_PT   | 1         | 0.89%   |
| pt_BR   | 1         | 0.89%   |
| it_IT   | 1         | 0.89%   |
| es_GT   | 1         | 0.89%   |
| es_CO   | 1         | 0.89%   |
| en_NZ   | 1         | 0.89%   |
| en_IN   | 1         | 0.89%   |
| en_AU   | 1         | 0.89%   |
| el_GR   | 1         | 0.89%   |
| de_DE   | 1         | 0.89%   |
| cs_CZ   | 1         | 0.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 77        | 70.64%  |
| BIOS | 32        | 29.36%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 82        | 75.23%  |
| Btrfs   | 21        | 19.27%  |
| Xfs     | 3         | 2.75%   |
| Overlay | 2         | 1.83%   |
| F2fs    | 1         | 0.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 76        | 69.72%  |
| MBR     | 18        | 16.51%  |
| Unknown | 15        | 13.76%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 93        | 85.32%  |
| Yes       | 16        | 14.68%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 80        | 74.07%  |
| Yes       | 28        | 25.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 29        | 26.85%  |
| Hewlett-Packard     | 16        | 14.81%  |
| Dell                | 14        | 12.96%  |
| Acer                | 13        | 12.04%  |
| ASUSTek Computer    | 12        | 11.11%  |
| MSI                 | 3         | 2.78%   |
| Apple               | 3         | 2.78%   |
| Timi                | 2         | 1.85%   |
| Samsung Electronics | 2         | 1.85%   |
| Notebook            | 2         | 1.85%   |
| GPD                 | 2         | 1.85%   |
| Gigabyte Technology | 2         | 1.85%   |
| UNOWHY              | 1         | 0.93%   |
| Toshiba             | 1         | 0.93%   |
| Quanta              | 1         | 0.93%   |
| MOTILE              | 1         | 0.93%   |
| LG Electronics      | 1         | 0.93%   |
| HUAWEI              | 1         | 0.93%   |
| HONOR               | 1         | 0.93%   |
| AXIOO               | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Timi RedmiBook 14 II                   | 2         | 1.85%   |
| Lenovo IdeaPad 5 15IIL05 81YK          | 2         | 1.85%   |
| HP 15                                  | 2         | 1.85%   |
| GPD P2 MAX                             | 2         | 1.85%   |
| Dell Precision M6600                   | 2         | 1.85%   |
| Dell Precision 7550                    | 2         | 1.85%   |
| Apple MacBookAir7,2                    | 2         | 1.85%   |
| UNOWHY Y13G010S4EI                     | 1         | 0.93%   |
| Toshiba Satellite P775                 | 1         | 0.93%   |
| Samsung R425D/R525D                    | 1         | 0.93%   |
| Samsung 350V5C/351V5C/3540VC/3440VC    | 1         | 0.93%   |
| Quanta SWH                             | 1         | 0.93%   |
| Notebook N141CU                        | 1         | 0.93%   |
| Notebook N130BU                        | 1         | 0.93%   |
| MSI Modern 15 A11M                     | 1         | 0.93%   |
| MSI GP72 7RDX                          | 1         | 0.93%   |
| MSI GF65 Thin 10SDR                    | 1         | 0.93%   |
| MOTILE M141                            | 1         | 0.93%   |
| LG 17Z990-R.AAC9U1                     | 1         | 0.93%   |
| Lenovo ThinkPad W500 4063CJ5           | 1         | 0.93%   |
| Lenovo ThinkPad T480s 20L8S3D400       | 1         | 0.93%   |
| Lenovo ThinkPad T480 MFG_IN_GO         | 1         | 0.93%   |
| Lenovo ThinkPad T440s 20ARS0MV00       | 1         | 0.93%   |
| Lenovo ThinkPad T430 2350BC6           | 1         | 0.93%   |
| Lenovo ThinkPad T430 2347H76           | 1         | 0.93%   |
| Lenovo ThinkPad T430 23427YU           | 1         | 0.93%   |
| Lenovo ThinkPad T420 4236H45           | 1         | 0.93%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00   | 1         | 0.93%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800   | 1         | 0.93%   |
| Lenovo ThinkPad P1 Gen 3 20TH001EMH    | 1         | 0.93%   |
| Lenovo ThinkPad E14 Gen 2 20T6000MCK   | 1         | 0.93%   |
| Lenovo ThinkPad 11e 5th Gen 20LNS0P500 | 1         | 0.93%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 1         | 0.93%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 0.93%   |
| Lenovo LaVie Z 20FF0012US              | 1         | 0.93%   |
| Lenovo IdeaPad Y500 20193              | 1         | 0.93%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL  | 1         | 0.93%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG   | 1         | 0.93%   |
| Lenovo IdeaPad 510-15IKB 80SV          | 1         | 0.93%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5       | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 13        | 12.04%  |
| Lenovo IdeaPad     | 9         | 8.33%   |
| Acer Aspire        | 9         | 8.33%   |
| Dell Precision     | 6         | 5.56%   |
| HP Laptop          | 5         | 4.63%   |
| Dell Latitude      | 4         | 3.7%    |
| Dell Inspiron      | 4         | 3.7%    |
| HP 250             | 3         | 2.78%   |
| Timi RedmiBook     | 2         | 1.85%   |
| HP Pavilion        | 2         | 1.85%   |
| HP 15              | 2         | 1.85%   |
| GPD P2             | 2         | 1.85%   |
| ASUS VivoBook      | 2         | 1.85%   |
| ASUS ASUS          | 2         | 1.85%   |
| Apple MacBookAir7  | 2         | 1.85%   |
| Acer Nitro         | 2         | 1.85%   |
| UNOWHY Y13G010S4EI | 1         | 0.93%   |
| Toshiba Satellite  | 1         | 0.93%   |
| Samsung R425D      | 1         | 0.93%   |
| Samsung 350V5C     | 1         | 0.93%   |
| Quanta SWH         | 1         | 0.93%   |
| Notebook N141CU    | 1         | 0.93%   |
| Notebook N130BU    | 1         | 0.93%   |
| MSI Modern         | 1         | 0.93%   |
| MSI GP72           | 1         | 0.93%   |
| MSI GF65           | 1         | 0.93%   |
| MOTILE M141        | 1         | 0.93%   |
| LG 17Z990-R.AAC9U1 | 1         | 0.93%   |
| Lenovo ThinkBook   | 1         | 0.93%   |
| Lenovo Legion      | 1         | 0.93%   |
| Lenovo LaVie       | 1         | 0.93%   |
| Lenovo G400s       | 1         | 0.93%   |
| Lenovo B590        | 1         | 0.93%   |
| Lenovo B570e       | 1         | 0.93%   |
| Lenovo B50-80      | 1         | 0.93%   |
| HUAWEI WRT-WX9     | 1         | 0.93%   |
| HONOR BMH-WCX9     | 1         | 0.93%   |
| HP ProBook         | 1         | 0.93%   |
| HP OMEN            | 1         | 0.93%   |
| HP 255             | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 25        | 23.15%  |
| 2018 | 13        | 12.04%  |
| 2019 | 11        | 10.19%  |
| 2011 | 9         | 8.33%   |
| 2017 | 8         | 7.41%   |
| 2013 | 8         | 7.41%   |
| 2012 | 8         | 7.41%   |
| 2014 | 7         | 6.48%   |
| 2015 | 6         | 5.56%   |
| 2021 | 4         | 3.7%    |
| 2016 | 4         | 3.7%    |
| 2010 | 3         | 2.78%   |
| 2022 | 1         | 0.93%   |
| 2009 | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 108       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 107       | 99.07%  |
| Enabled  | 1         | 0.93%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 108       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 33        | 30.28%  |
| 8.01-16.0   | 25        | 22.94%  |
| 16.01-24.0  | 21        | 19.27%  |
| 3.01-4.0    | 17        | 15.6%   |
| 32.01-64.0  | 4         | 3.67%   |
| 1.01-2.0    | 4         | 3.67%   |
| 64.01-256.0 | 3         | 2.75%   |
| 24.01-32.0  | 2         | 1.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 31        | 25.2%   |
| 1.01-2.0   | 31        | 25.2%   |
| 4.01-8.0   | 27        | 21.95%  |
| 3.01-4.0   | 15        | 12.2%   |
| 0.51-1.0   | 12        | 9.76%   |
| 8.01-16.0  | 4         | 3.25%   |
| 0.01-0.5   | 2         | 1.63%   |
| 16.01-24.0 | 1         | 0.81%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 86        | 78.9%   |
| 2      | 22        | 20.18%  |
| 3      | 1         | 0.92%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 78        | 72.22%  |
| Yes       | 30        | 27.78%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 78.7%   |
| No        | 23        | 21.3%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 98.15%  |
| No        | 2         | 1.85%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 88        | 80%     |
| No        | 22        | 20%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 24        | 22.22%  |
| Russia      | 12        | 11.11%  |
| India       | 6         | 5.56%   |
| Turkey      | 5         | 4.63%   |
| Brazil      | 5         | 4.63%   |
| UK          | 4         | 3.7%    |
| Indonesia   | 4         | 3.7%    |
| Germany     | 4         | 3.7%    |
| Canada      | 4         | 3.7%    |
| Ukraine     | 3         | 2.78%   |
| Poland      | 3         | 2.78%   |
| Netherlands | 3         | 2.78%   |
| France      | 3         | 2.78%   |
| Switzerland | 2         | 1.85%   |
| Spain       | 2         | 1.85%   |
| Romania     | 2         | 1.85%   |
| Italy       | 2         | 1.85%   |
| Czechia     | 2         | 1.85%   |
| Bulgaria    | 2         | 1.85%   |
| Uzbekistan  | 1         | 0.93%   |
| Sweden      | 1         | 0.93%   |
| Peru        | 1         | 0.93%   |
| Lithuania   | 1         | 0.93%   |
| Israel      | 1         | 0.93%   |
| Iran        | 1         | 0.93%   |
| Guatemala   | 1         | 0.93%   |
| Greece      | 1         | 0.93%   |
| Colombia    | 1         | 0.93%   |
| China       | 1         | 0.93%   |
| Chile       | 1         | 0.93%   |
| Bangladesh  | 1         | 0.93%   |
| Azerbaijan  | 1         | 0.93%   |
| Australia   | 1         | 0.93%   |
| Argentina   | 1         | 0.93%   |
| Algeria     | 1         | 0.93%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| St Petersburg     | 3         | 2.61%   |
| Paris             | 3         | 2.61%   |
| Jakarta           | 3         | 2.61%   |
| San Ramon         | 2         | 1.74%   |
| Samara            | 2         | 1.74%   |
| Rio de Janeiro    | 2         | 1.74%   |
| Prague            | 2         | 1.74%   |
| Omaha             | 2         | 1.74%   |
| Neuchatel         | 2         | 1.74%   |
| Moscow            | 2         | 1.74%   |
| Los Angeles       | 2         | 1.74%   |
| Frankfurt am Main | 2         | 1.74%   |
| Dnipro            | 2         | 1.74%   |
| Ankara            | 2         | 1.74%   |
| Amsterdam         | 2         | 1.74%   |
| Zaporizhzhya      | 1         | 0.87%   |
| Woodbridge        | 1         | 0.87%   |
| Wigan             | 1         | 0.87%   |
| Wem               | 1         | 0.87%   |
| Vilnius           | 1         | 0.87%   |
| Varna             | 1         | 0.87%   |
| Vancouver         | 1         | 0.87%   |
| Toronto           | 1         | 0.87%   |
| Timișoara        | 1         | 0.87%   |
| Tel Aviv          | 1         | 0.87%   |
| Tashkent          | 1         | 0.87%   |
| Syeverodonets'k   | 1         | 0.87%   |
| Surgut            | 1         | 0.87%   |
| Stuttgart         | 1         | 0.87%   |
| Stockholm         | 1         | 0.87%   |
| Sofia             | 1         | 0.87%   |
| Snohomish         | 1         | 0.87%   |
| Skikda            | 1         | 0.87%   |
| Sigogne           | 1         | 0.87%   |
| Seville           | 1         | 0.87%   |
| Semarang          | 1         | 0.87%   |
| Seattle           | 1         | 0.87%   |
| Santiago          | 1         | 0.87%   |
| Santa Marta       | 1         | 0.87%   |
| Santa Fe          | 1         | 0.87%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 27        | 34     | 20.45%  |
| Seagate                   | 16        | 16     | 12.12%  |
| WDC                       | 11        | 14     | 8.33%   |
| Toshiba                   | 9         | 9      | 6.82%   |
| SanDisk                   | 7         | 7      | 5.3%    |
| HGST                      | 7         | 7      | 5.3%    |
| Kingston                  | 6         | 7      | 4.55%   |
| Intel                     | 6         | 8      | 4.55%   |
| SK hynix                  | 5         | 11     | 3.79%   |
| Hitachi                   | 4         | 5      | 3.03%   |
| Crucial                   | 4         | 5      | 3.03%   |
| China                     | 4         | 4      | 3.03%   |
| Phison Electronics        | 3         | 5      | 2.27%   |
| Apple                     | 3         | 4      | 2.27%   |
| Unknown                   | 2         | 2      | 1.52%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.76%   |
| Timetec                   | 1         | 2      | 0.76%   |
| SPCC                      | 1         | 1      | 0.76%   |
| Solid State Storage       | 1         | 1      | 0.76%   |
| PNY                       | 1         | 1      | 0.76%   |
| Phison                    | 1         | 1      | 0.76%   |
| Patriot                   | 1         | 1      | 0.76%   |
| Micron/Crucial Technology | 1         | 1      | 0.76%   |
| Micron Technology         | 1         | 1      | 0.76%   |
| LITEON                    | 1         | 1      | 0.76%   |
| Lite-On                   | 1         | 1      | 0.76%   |
| Linux                     | 1         | 1      | 0.76%   |
| LDLC                      | 1         | 5      | 0.76%   |
| Intenso                   | 1         | 1      | 0.76%   |
| Hewlett-Packard           | 1         | 1      | 0.76%   |
| AGI                       | 1         | 1      | 0.76%   |
| A-DATA Technology         | 1         | 1      | 0.76%   |
| Unknown                   | 1         | 1      | 0.76%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 4         | 2.86%   |
| SanDisk NVMe SSD Drive 512GB                        | 4         | 2.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 2.14%   |
| China SATA SSD 960GB                                | 3         | 2.14%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 1.43%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 1.43%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 1.43%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 1.43%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 1.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 1.43%   |
| Samsung NVMe SSD Drive 1TB                          | 2         | 1.43%   |
| Samsung MZNLH512HALU-00000 512GB SSD                | 2         | 1.43%   |
| Phison PCIe SSD 1TB                                 | 2         | 1.43%   |
| Phison E12 NVMe Controller 1TB                      | 2         | 1.43%   |
| Kingston OM8PCP3512F-AI1 512GB                      | 2         | 1.43%   |
| HGST HTS545050A7E680 500GB                          | 2         | 1.43%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 1.43%   |
| Apple SSD SM0256G 256GB                             | 2         | 1.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.71%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                      | 1         | 0.71%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 0.71%   |
| WDC WD5000LPVX-55V0TT0 500GB                        | 1         | 0.71%   |
| WDC WD5000BPVT-22HXZT3 500GB                        | 1         | 0.71%   |
| WDC WD3200LPVT-00FMCT0 320GB                        | 1         | 0.71%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 0.71%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 1         | 0.71%   |
| WDC WD10SPCX-24HWST1 1TB                            | 1         | 0.71%   |
| Unknown SD/MMC/MS PRO 2GB                           | 1         | 0.71%   |
| Unknown DA4064  64GB                                | 1         | 0.71%   |
| Union Memory (Shenzhen) UMIS RPEYJ512VMM2QWY 512GB  | 1         | 0.71%   |
| Toshiba THNSNH128GMCT 128GB SSD                     | 1         | 0.71%   |
| Toshiba MK5065GSX 500GB                             | 1         | 0.71%   |
| Toshiba KBG30ZMT256G 256GB                          | 1         | 0.71%   |
| Timetec 35TTM8SSATA-512GB                           | 1         | 0.71%   |
| SPCC Solid State Disk 256GB                         | 1         | 0.71%   |
| Solid State Storage SSSTC CL1-4D256 256GB           | 1         | 0.71%   |
| SK hynix SKHynix_HFS512GD9TNI-L2B0B 512GB           | 1         | 0.71%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB           | 1         | 0.71%   |
| SK hynix SC311 SATA 256GB SSD                       | 1         | 0.71%   |
| SK hynix NVMe SSD Drive 1TB                         | 1         | 0.71%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 16     | 36.36%  |
| WDC     | 9         | 11     | 20.45%  |
| Toshiba | 7         | 7      | 15.91%  |
| HGST    | 7         | 7      | 15.91%  |
| Hitachi | 4         | 5      | 9.09%   |
| Unknown | 1         | 1      | 2.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 11     | 26.32%  |
| Crucial             | 4         | 5      | 10.53%  |
| China               | 4         | 4      | 10.53%  |
| Kingston            | 3         | 3      | 7.89%   |
| Apple               | 3         | 4      | 7.89%   |
| WDC                 | 2         | 3      | 5.26%   |
| Toshiba             | 1         | 1      | 2.63%   |
| SPCC                | 1         | 1      | 2.63%   |
| SK hynix            | 1         | 1      | 2.63%   |
| SanDisk             | 1         | 1      | 2.63%   |
| PNY                 | 1         | 1      | 2.63%   |
| Patriot             | 1         | 1      | 2.63%   |
| Linux               | 1         | 1      | 2.63%   |
| LDLC                | 1         | 5      | 2.63%   |
| Intenso             | 1         | 1      | 2.63%   |
| Intel               | 1         | 1      | 2.63%   |
| Hewlett-Packard     | 1         | 1      | 2.63%   |
| AGI                 | 1         | 1      | 2.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 43        | 47     | 34.96%  |
| NVMe    | 41        | 64     | 33.33%  |
| SSD     | 36        | 46     | 29.27%  |
| Unknown | 2         | 3      | 1.63%   |
| MMC     | 1         | 1      | 0.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 74        | 94     | 62.71%  |
| NVMe | 41        | 64     | 34.75%  |
| SAS  | 2         | 2      | 1.69%   |
| MMC  | 1         | 1      | 0.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 45        | 55     | 58.44%  |
| 0.51-1.0   | 28        | 33     | 36.36%  |
| 1.01-2.0   | 3         | 4      | 3.9%    |
| 4.01-10.0  | 1         | 1      | 1.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 31        | 27.68%  |
| 101-250        | 29        | 25.89%  |
| 501-1000       | 17        | 15.18%  |
| 1001-2000      | 12        | 10.71%  |
| 51-100         | 6         | 5.36%   |
| Unknown        | 6         | 5.36%   |
| More than 3000 | 4         | 3.57%   |
| 1-20           | 4         | 3.57%   |
| 2001-3000      | 2         | 1.79%   |
| 21-50          | 1         | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 34        | 28.33%  |
| 101-250        | 23        | 19.17%  |
| 51-100         | 16        | 13.33%  |
| 21-50          | 13        | 10.83%  |
| 251-500        | 12        | 10%     |
| 501-1000       | 11        | 9.17%   |
| Unknown        | 6         | 5%      |
| 1001-2000      | 3         | 2.5%    |
| More than 3000 | 1         | 0.83%   |
| 2001-3000      | 1         | 0.83%   |

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
| Works    | 59        | 76     | 50.86%  |
| Detected | 41        | 67     | 35.34%  |
| Malfunc  | 16        | 18     | 13.79%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 69        | 52.27%  |
| Samsung Electronics            | 19        | 14.39%  |
| AMD                            | 18        | 13.64%  |
| SanDisk                        | 6         | 4.55%   |
| SK hynix                       | 4         | 3.03%   |
| Phison Electronics             | 3         | 2.27%   |
| Kingston Technology Company    | 3         | 2.27%   |
| Union Memory (Shenzhen)        | 2         | 1.52%   |
| Toshiba America Info Systems   | 1         | 0.76%   |
| Solid State Storage Technology | 1         | 0.76%   |
| Nvidia                         | 1         | 0.76%   |
| Micron/Crucial Technology      | 1         | 0.76%   |
| Micron Technology              | 1         | 0.76%   |
| Marvell Technology Group       | 1         | 0.76%   |
| Lite-On Technology             | 1         | 0.76%   |
| ADATA Technology               | 1         | 0.76%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                           | 16        | 11.59%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                 | 9         | 6.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                            | 9         | 6.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]              | 9         | 6.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                | 8         | 5.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller  | 7         | 5.07%   |
| Samsung NVMe SSD Controller 980                                               | 5         | 3.62%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                            | 4         | 2.9%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                  | 4         | 2.9%    |
| SK hynix Non-Volatile memory controller                                       | 3         | 2.17%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                    | 3         | 2.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                 | 3         | 2.17%   |
| Phison E12 NVMe Controller                                                    | 3         | 2.17%   |
| Kingston Company Company Non-Volatile memory controller                       | 3         | 2.17%   |
| Intel Volume Management Device NVMe RAID Controller                           | 3         | 2.17%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                       | 3         | 2.17%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                 | 3         | 2.17%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                          | 3         | 2.17%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                        | 2         | 1.45%   |
| SanDisk Non-Volatile memory controller                                        | 2         | 1.45%   |
| Samsung Electronics SATA controller                                           | 2         | 1.45%   |
| Intel SSD 660P Series                                                         | 2         | 1.45%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                         | 2         | 1.45%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                        | 2         | 1.45%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                             | 2         | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                             | 2         | 1.45%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                        | 2         | 1.45%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                          | 1         | 0.72%   |
| Solid State Storage Non-Volatile memory controller                            | 1         | 0.72%   |
| SK hynix BC511                                                                | 1         | 0.72%   |
| SanDisk WD Blue SN550 NVMe SSD                                                | 1         | 0.72%   |
| Nvidia MCP79 AHCI Controller                                                  | 1         | 0.72%   |
| Micron/Crucial P2 NVMe PCIe SSD                                               | 1         | 0.72%   |
| Micron Non-Volatile memory controller                                         | 1         | 0.72%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                    | 1         | 0.72%   |
| Lite-On Non-Volatile memory controller                                        | 1         | 0.72%   |
| Intel Tiger Lake-LP SATA Controller                                           | 1         | 0.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode] | 1         | 0.72%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                            | 1         | 0.72%   |
| Intel Comet Lake SATA AHCI Controller                                         | 1         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 79        | 59.4%   |
| NVMe | 42        | 31.58%  |
| RAID | 11        | 8.27%   |
| IDE  | 1         | 0.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 87        | 80.56%  |
| AMD    | 21        | 19.44%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 7 4700U with Radeon Graphics      | 4         | 3.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 2.75%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 2         | 1.83%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.83%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 1.83%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 2         | 1.83%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1.83%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 1.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.83%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 1.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.83%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.83%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 1.83%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 1.83%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 1.83%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 2         | 1.83%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 1.83%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.83%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 1.83%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz        | 1         | 0.92%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.92%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.92%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.92%   |
| Intel Pentium CPU A1018 @ 2.10GHz           | 1         | 0.92%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 0.92%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.92%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 1         | 0.92%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 0.92%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.92%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.92%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.92%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.92%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.92%   |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 0.92%   |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 0.92%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 0.92%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 0.92%   |
| Intel Core i7-10870H CPU @ 2.20GHz          | 1         | 0.92%   |
| Intel Core i7-10850H CPU @ 2.70GHz          | 1         | 0.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 29        | 26.85%  |
| Intel Core i7           | 23        | 21.3%   |
| Intel Core i3           | 11        | 10.19%  |
| AMD Ryzen 7             | 9         | 8.33%   |
| Other                   | 6         | 5.56%   |
| Intel Celeron           | 6         | 5.56%   |
| Intel Pentium           | 3         | 2.78%   |
| AMD Ryzen 5             | 3         | 2.78%   |
| Intel Core m3           | 2         | 1.85%   |
| Intel Core i9           | 2         | 1.85%   |
| AMD Ryzen 3             | 2         | 1.85%   |
| Intel Xeon              | 1         | 0.93%   |
| Intel Pentium Silver    | 1         | 0.93%   |
| Intel Pentium Dual-Core | 1         | 0.93%   |
| Intel Core 2 Duo        | 1         | 0.93%   |
| Intel Atom              | 1         | 0.93%   |
| AMD Ryzen 9             | 1         | 0.93%   |
| AMD Ryzen 5 PRO         | 1         | 0.93%   |
| AMD Phenom II           | 1         | 0.93%   |
| AMD E1                  | 1         | 0.93%   |
| AMD Athlon              | 1         | 0.93%   |
| AMD A6                  | 1         | 0.93%   |
| AMD A10                 | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 51        | 47.22%  |
| 4      | 36        | 33.33%  |
| 8      | 11        | 10.19%  |
| 6      | 9         | 8.33%   |
| 12     | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 108       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 85        | 78.7%   |
| 1      | 23        | 21.3%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 108       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 15.45%  |
| 0x306a9    | 9         | 8.18%   |
| 0x206a7    | 9         | 8.18%   |
| 0xa0652    | 5         | 4.55%   |
| 0x806e9    | 5         | 4.55%   |
| 0x40651    | 5         | 4.55%   |
| 0x306d4    | 5         | 4.55%   |
| 0x806ec    | 4         | 3.64%   |
| 0x806ea    | 4         | 3.64%   |
| 0x806c1    | 4         | 3.64%   |
| 0x706e5    | 4         | 3.64%   |
| 0x906ea    | 3         | 2.73%   |
| 0x906e9    | 3         | 2.73%   |
| 0x706a1    | 3         | 2.73%   |
| 0x08600106 | 3         | 2.73%   |
| 0x30678    | 2         | 1.82%   |
| 0x1067a    | 2         | 1.82%   |
| 0x08600103 | 2         | 1.82%   |
| 0x08108109 | 2         | 1.82%   |
| 0x906ed    | 1         | 0.91%   |
| 0x806eb    | 1         | 0.91%   |
| 0x806d1    | 1         | 0.91%   |
| 0x506e3    | 1         | 0.91%   |
| 0x506c9    | 1         | 0.91%   |
| 0x406e3    | 1         | 0.91%   |
| 0x306c3    | 1         | 0.91%   |
| 0x20655    | 1         | 0.91%   |
| 0x0a50000c | 1         | 0.91%   |
| 0x08701013 | 1         | 0.91%   |
| 0x08608103 | 1         | 0.91%   |
| 0x08600104 | 1         | 0.91%   |
| 0x08108102 | 1         | 0.91%   |
| 0x0810100b | 1         | 0.91%   |
| 0x08101007 | 1         | 0.91%   |
| 0x08001137 | 1         | 0.91%   |
| 0x0700010b | 1         | 0.91%   |
| 0x06003109 | 1         | 0.91%   |
| 0x010000c8 | 1         | 0.91%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 27        | 25%     |
| IvyBridge     | 10        | 9.26%   |
| SandyBridge   | 9         | 8.33%   |
| Zen 2         | 8         | 7.41%   |
| Haswell       | 7         | 6.48%   |
| CometLake     | 6         | 5.56%   |
| Broadwell     | 6         | 5.56%   |
| TigerLake     | 5         | 4.63%   |
| Zen+          | 4         | 3.7%    |
| IceLake       | 4         | 3.7%    |
| Zen           | 3         | 2.78%   |
| Goldmont plus | 3         | 2.78%   |
| Skylake       | 2         | 1.85%   |
| Silvermont    | 2         | 1.85%   |
| Penryn        | 2         | 1.85%   |
| Unknown       | 2         | 1.85%   |
| Zen 3         | 1         | 0.93%   |
| Westmere      | 1         | 0.93%   |
| Steamroller   | 1         | 0.93%   |
| Puma          | 1         | 0.93%   |
| K10           | 1         | 0.93%   |
| Jaguar        | 1         | 0.93%   |
| Goldmont      | 1         | 0.93%   |
| Bonnell       | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 80        | 58.82%  |
| Nvidia | 30        | 22.06%  |
| AMD    | 26        | 19.12%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 8         | 5.8%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 7         | 5.07%   |
| Intel HD Graphics 620                                                     | 6         | 4.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 4.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 6         | 4.35%   |
| AMD Renoir                                                                | 6         | 4.35%   |
| Intel UHD Graphics 620                                                    | 5         | 3.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 5         | 3.62%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 2.9%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 2.9%    |
| Intel HD Graphics 5500                                                    | 4         | 2.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 2.9%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 3         | 2.17%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 2.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 2.17%   |
| Nvidia TU117M                                                             | 2         | 1.45%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 2         | 1.45%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 1.45%   |
| Intel UHD Graphics 615                                                    | 2         | 1.45%   |
| Intel HD Graphics 630                                                     | 2         | 1.45%   |
| Intel HD Graphics 6000                                                    | 2         | 1.45%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.45%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 1.45%   |
| AMD Saturn XT [FirePro M6100]                                             | 2         | 1.45%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.45%   |
| Nvidia TU117M [GeForce MX450]                                             | 1         | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.72%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.72%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.72%   |
| Nvidia GP108M [GeForce MX330]                                             | 1         | 0.72%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.72%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                   | 1         | 0.72%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                  | 1         | 0.72%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.72%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.72%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                     | 1         | 0.72%   |
| Nvidia GM107 [GeForce 940MX]                                              | 1         | 0.72%   |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 0.72%   |
| Nvidia GF119M [GeForce GT 520MX]                                          | 1         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 53        | 48.62%  |
| Intel + Nvidia | 23        | 21.1%   |
| 1 x AMD        | 20        | 18.35%  |
| 1 x Nvidia     | 6         | 5.5%    |
| Intel + AMD    | 4         | 3.67%   |
| 2 x AMD        | 2         | 1.83%   |
| AMD + Nvidia   | 1         | 0.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 90        | 83.33%  |
| Proprietary | 18        | 16.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 64.22%  |
| 1.01-2.0   | 12        | 11.01%  |
| 0.01-0.5   | 11        | 10.09%  |
| 3.01-4.0   | 5         | 4.59%   |
| 0.51-1.0   | 5         | 4.59%   |
| 5.01-6.0   | 3         | 2.75%   |
| 7.01-8.0   | 2         | 1.83%   |
| 2.01-3.0   | 1         | 0.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 23        | 18.4%   |
| LG Display              | 20        | 16%     |
| BOE                     | 20        | 16%     |
| Chimei Innolux          | 15        | 12%     |
| Samsung Electronics     | 10        | 8%      |
| Dell                    | 4         | 3.2%    |
| Chi Mei Optoelectronics | 4         | 3.2%    |
| InfoVision              | 3         | 2.4%    |
| Goldstar                | 3         | 2.4%    |
| ASUSTek Computer        | 3         | 2.4%    |
| Apple                   | 3         | 2.4%    |
| Sharp                   | 2         | 1.6%    |
| PANDA                   | 2         | 1.6%    |
| Hewlett-Packard         | 2         | 1.6%    |
| BenQ                    | 2         | 1.6%    |
| Philips                 | 1         | 0.8%    |
| MSI                     | 1         | 0.8%    |
| LGD                     | 1         | 0.8%    |
| Lenovo                  | 1         | 0.8%    |
| KDC                     | 1         | 0.8%    |
| HUAWEI                  | 1         | 0.8%    |
| CSO                     | 1         | 0.8%    |
| Ancor Communications    | 1         | 0.8%    |
| Acer                    | 1         | 0.8%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 4         | 3.2%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 2.4%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 1.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 1.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.6%    |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 1.6%    |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 1.6%    |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 1.6%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 1.6%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 1.6%    |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 1.6%    |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 0.8%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.8%    |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 0.8%    |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch      | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch      | 1         | 0.8%    |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                   | 1         | 0.8%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 1         | 0.8%    |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                   | 1         | 0.8%    |
| MSI Optix G241VC MSI1462 1920x1080 521x294mm 23.6-inch                    | 1         | 0.8%    |
| LGD LCD Monitor 1920x1080                                                 | 1         | 0.8%    |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch               | 1         | 0.8%    |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 1         | 0.8%    |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch              | 1         | 0.8%    |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch              | 1         | 0.8%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 1         | 0.8%    |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch              | 1         | 0.8%    |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 0.8%    |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch              | 1         | 0.8%    |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 1         | 0.8%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 1         | 0.8%    |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch               | 1         | 0.8%    |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch               | 1         | 0.8%    |
| LG Display LCD Monitor LGD03EA 1920x1080 309x174mm 14.0-inch              | 1         | 0.8%    |
| LG Display LCD Monitor LGD03D3 1600x900 309x174mm 14.0-inch               | 1         | 0.8%    |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch               | 1         | 0.8%    |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch               | 1         | 0.8%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 54        | 45.76%  |
| 1366x768 (WXGA)    | 42        | 35.59%  |
| 2560x1440 (QHD)    | 4         | 3.39%   |
| 1600x900 (HD+)     | 4         | 3.39%   |
| 1440x900 (WXGA+)   | 4         | 3.39%   |
| 3840x2160 (4K)     | 3         | 2.54%   |
| 2560x1600          | 3         | 2.54%   |
| 3440x1440          | 1         | 0.85%   |
| 2160x1440          | 1         | 0.85%   |
| 1920x1200 (WUXGA)  | 1         | 0.85%   |
| 1680x1050 (WSXGA+) | 1         | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 56        | 45.16%  |
| 13      | 18        | 14.52%  |
| 14      | 17        | 13.71%  |
| 17      | 9         | 7.26%   |
| 27      | 5         | 4.03%   |
| 24      | 5         | 4.03%   |
| 21      | 5         | 4.03%   |
| 23      | 2         | 1.61%   |
| 34      | 1         | 0.81%   |
| 20      | 1         | 0.81%   |
| 19      | 1         | 0.81%   |
| 16      | 1         | 0.81%   |
| 12      | 1         | 0.81%   |
| 11      | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 82        | 66.13%  |
| 351-400     | 13        | 10.48%  |
| 501-600     | 11        | 8.87%   |
| 201-300     | 8         | 6.45%   |
| 401-500     | 7         | 5.65%   |
| 701-800     | 1         | 0.81%   |
| 601-700     | 1         | 0.81%   |
| Unknown     | 1         | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 96        | 88.89%  |
| 16/10   | 9         | 8.33%   |
| 3/2     | 1         | 0.93%   |
| 21/9    | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 56        | 45.16%  |
| 81-90          | 29        | 23.39%  |
| 201-250        | 11        | 8.87%   |
| 121-130        | 8         | 6.45%   |
| 71-80          | 6         | 4.84%   |
| 301-350        | 5         | 4.03%   |
| 151-200        | 2         | 1.61%   |
| 61-70          | 1         | 0.81%   |
| 51-60          | 1         | 0.81%   |
| 351-500        | 1         | 0.81%   |
| 251-300        | 1         | 0.81%   |
| 131-140        | 1         | 0.81%   |
| 111-120        | 1         | 0.81%   |
| Unknown        | 1         | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 54        | 45%     |
| 101-120       | 40        | 33.33%  |
| 51-100        | 18        | 15%     |
| 161-240       | 6         | 5%      |
| More than 240 | 1         | 0.83%   |
| Unknown       | 1         | 0.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 92        | 82.88%  |
| 2     | 19        | 17.12%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 70        | 39.11%  |
| Intel                    | 58        | 32.4%   |
| Qualcomm Atheros         | 20        | 11.17%  |
| Broadcom                 | 10        | 5.59%   |
| Broadcom Limited         | 4         | 2.23%   |
| Samsung Electronics      | 2         | 1.12%   |
| Ralink                   | 2         | 1.12%   |
| Qualcomm                 | 2         | 1.12%   |
| MediaTek                 | 2         | 1.12%   |
| Xiaomi                   | 1         | 0.56%   |
| TP-Link                  | 1         | 0.56%   |
| Sierra Wireless          | 1         | 0.56%   |
| Ralink Technology        | 1         | 0.56%   |
| OPPO Electronics         | 1         | 0.56%   |
| Marvell Technology Group | 1         | 0.56%   |
| Linksys                  | 1         | 0.56%   |
| Huawei Technologies      | 1         | 0.56%   |
| Apple                    | 1         | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 20.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 6.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.86%   |
| Intel Wireless 8265 / 8275                                        | 6         | 2.86%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 2.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 2.38%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 2.38%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.9%    |
| Intel Wireless 7265                                               | 4         | 1.9%    |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.9%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.43%   |
| Intel Wireless 7260                                               | 3         | 1.43%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 1.43%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.43%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.43%   |
| Realtek 802.11ac NIC                                              | 2         | 0.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.95%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.95%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.95%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.95%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.48%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.48%   |
| Sierra Wireless MC7700                                            | 1         | 0.48%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.48%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.48%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 54        | 47.79%  |
| Realtek Semiconductor | 21        | 18.58%  |
| Qualcomm Atheros      | 17        | 15.04%  |
| Broadcom              | 9         | 7.96%   |
| Broadcom Limited      | 4         | 3.54%   |
| Ralink                | 2         | 1.77%   |
| MediaTek              | 2         | 1.77%   |
| TP-Link               | 1         | 0.88%   |
| Sierra Wireless       | 1         | 0.88%   |
| Ralink Technology     | 1         | 0.88%   |
| Qualcomm              | 1         | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 5.22%   |
| Intel Wireless 8265 / 8275                                     | 6         | 5.22%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 5.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 4.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 4.35%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 4.35%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 4.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 3.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 3.48%   |
| Intel Wireless 7265                                            | 4         | 3.48%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 3.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 3.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2.61%   |
| Intel Wireless 7260                                            | 3         | 2.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 2.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 2.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 2.61%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 2.61%   |
| Realtek 802.11ac NIC                                           | 2         | 1.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.74%   |
| Intel Centrino Wireless-N 2230                                 | 2         | 1.74%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.74%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.74%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.87%   |
| Sierra Wireless MC7700                                         | 1         | 0.87%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.87%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1         | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.87%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.87%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.87%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 1         | 0.87%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.87%   |
| Intel Wireless-AC 9260                                         | 1         | 0.87%   |
| Intel Wireless 3165                                            | 1         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 62        | 66.67%  |
| Intel                    | 17        | 18.28%  |
| Qualcomm Atheros         | 4         | 4.3%    |
| Samsung Electronics      | 2         | 2.15%   |
| Xiaomi                   | 1         | 1.08%   |
| Qualcomm                 | 1         | 1.08%   |
| OPPO Electronics         | 1         | 1.08%   |
| Marvell Technology Group | 1         | 1.08%   |
| Linksys                  | 1         | 1.08%   |
| Huawei Technologies      | 1         | 1.08%   |
| Broadcom                 | 1         | 1.08%   |
| Apple                    | 1         | 1.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 44        | 46.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 13.68%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 7.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 6.32%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 3.16%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 2.11%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 1.05%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.05%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 1.05%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 1.05%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 1.05%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.05%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.05%   |
| Qualcomm A0001                                                    | 1         | 1.05%   |
| OPPO SDM710-MTP _SN:2396E2D4                                      | 1         | 1.05%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.05%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 1.05%   |
| Intel WiMAX Connection 2400m                                      | 1         | 1.05%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.05%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.05%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.05%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.05%   |
| Huawei E353/E3131                                                 | 1         | 1.05%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.05%   |
| Apple iPad 4/Mini1                                                | 1         | 1.05%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 106       | 55.5%   |
| Ethernet | 85        | 44.5%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 88        | 78.57%  |
| Ethernet | 24        | 21.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 77        | 70.64%  |
| 1     | 29        | 26.61%  |
| 3     | 2         | 1.83%   |
| 0     | 1         | 0.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 95        | 84.82%  |
| Yes  | 17        | 15.18%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 50%     |
| Realtek Semiconductor           | 14        | 15.91%  |
| Broadcom                        | 7         | 7.95%   |
| Qualcomm Atheros Communications | 4         | 4.55%   |
| Lite-On Technology              | 4         | 4.55%   |
| IMC Networks                    | 3         | 3.41%   |
| Foxconn / Hon Hai               | 3         | 3.41%   |
| Apple                           | 3         | 3.41%   |
| Realtek                         | 2         | 2.27%   |
| Cambridge Silicon Radio         | 2         | 2.27%   |
| Ralink                          | 1         | 1.14%   |
| ASUSTek Computer                | 1         | 1.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 13        | 14.61%  |
| Intel Bluetooth Device                              | 12        | 13.48%  |
| Realtek Bluetooth Radio                             | 8         | 8.99%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 8.99%   |
| Intel AX200 Bluetooth                               | 6         | 6.74%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 4.49%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 3.37%   |
| Lite-On Bluetooth Device                            | 3         | 3.37%   |
| Realtek Bluetooth Radio                             | 2         | 2.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 2.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 2.25%   |
| IMC Networks Wireless_Device                        | 2         | 2.25%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 2.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 2.25%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.25%   |
| Apple Bluetooth USB Host Controller                 | 2         | 2.25%   |
| Realtek RTL8821A Bluetooth                          | 1         | 1.12%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.12%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.12%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.12%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 1.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.12%   |
| Intel AX210 Bluetooth                               | 1         | 1.12%   |
| IMC Networks Bluetooth Device                       | 1         | 1.12%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.12%   |
| Broadcom HP Portable Valentine                      | 1         | 1.12%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.12%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 1.12%   |
| Broadcom BCM2070 Bluetooth Device                   | 1         | 1.12%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.12%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 1.12%   |
| Apple Bluetooth Host Controller                     | 1         | 1.12%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 86        | 62.77%  |
| AMD                   | 23        | 16.79%  |
| Nvidia                | 19        | 13.87%  |
| C-Media Electronics   | 3         | 2.19%   |
| Realtek Semiconductor | 2         | 1.46%   |
| Plantronics           | 1         | 0.73%   |
| Harman                | 1         | 0.73%   |
| Corsair               | 1         | 0.73%   |
| Arylic                | 1         | 0.73%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 8.77%   |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 8.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 5.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 5.26%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 4.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 3.51%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 3.51%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 3.51%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 3.51%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 3.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 3.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 2.92%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 2.34%   |
| Intel CM238 HD Audio Controller                                            | 4         | 2.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.34%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 2.34%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.75%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.75%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.75%   |
| Realtek Semiconductor USB Audio                                            | 2         | 1.17%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.17%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.17%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 1.17%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 2         | 1.17%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 1.17%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.58%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.58%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.58%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.58%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.58%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.58%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.58%   |
| Nvidia GA106 High Definition Audio Controller                              | 1         | 0.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 1         | 0.58%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.58%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 29.57%  |
| SK hynix            | 30        | 26.09%  |
| Kingston            | 13        | 11.3%   |
| Micron Technology   | 11        | 9.57%   |
| Unknown             | 4         | 3.48%   |
| A-DATA Technology   | 4         | 3.48%   |
| Silicon Power       | 3         | 2.61%   |
| Unknown             | 3         | 2.61%   |
| Unknown (ABCD)      | 2         | 1.74%   |
| Smart               | 2         | 1.74%   |
| Ramaxel Technology  | 2         | 1.74%   |
| Nanya Technology    | 2         | 1.74%   |
| Corsair             | 2         | 1.74%   |
| Team                | 1         | 0.87%   |
| Smart Brazil        | 1         | 0.87%   |
| ASint Technology    | 1         | 0.87%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 4         | 3.31%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 3.31%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.48%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 2.48%   |
| Unknown                                                          | 3         | 2.48%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.65%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.65%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.65%   |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.65%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.65%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.65%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 2         | 1.65%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 2         | 1.65%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 1.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.65%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.65%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.65%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.65%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.65%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.83%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.83%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.83%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.83%   |
| Smart RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 3200MT/s         | 1         | 0.83%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2400MT/s            | 1         | 0.83%   |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s     | 1         | 0.83%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.83%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 0.83%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.83%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.83%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.83%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.83%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.83%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 49        | 52.13%  |
| DDR3    | 35        | 37.23%  |
| LPDDR4  | 4         | 4.26%   |
| LPDDR3  | 3         | 3.19%   |
| SDRAM   | 2         | 2.13%   |
| Unknown | 1         | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 83        | 87.37%  |
| Row Of Chips | 9         | 9.47%   |
| DIMM         | 1         | 1.05%   |
| Chip         | 1         | 1.05%   |
| Unknown      | 1         | 1.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 42        | 38.89%  |
| 8192  | 38        | 35.19%  |
| 16384 | 14        | 12.96%  |
| 2048  | 11        | 10.19%  |
| 32768 | 2         | 1.85%   |
| 1024  | 1         | 0.93%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 31        | 30.69%  |
| 3200  | 22        | 21.78%  |
| 2667  | 20        | 19.8%   |
| 2400  | 10        | 9.9%    |
| 1333  | 5         | 4.95%   |
| 2133  | 3         | 2.97%   |
| 1334  | 3         | 2.97%   |
| 4199  | 2         | 1.98%   |
| 4267  | 1         | 0.99%   |
| 3400  | 1         | 0.99%   |
| 3266  | 1         | 0.99%   |
| 1067  | 1         | 0.99%   |
| 1066  | 1         | 0.99%   |

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
| Chicony Electronics                    | 21        | 21.88%  |
| Acer                                   | 11        | 11.46%  |
| Realtek Semiconductor                  | 10        | 10.42%  |
| IMC Networks                           | 10        | 10.42%  |
| Quanta                                 | 9         | 9.38%   |
| Suyin                                  | 6         | 6.25%   |
| Alcor Micro                            | 5         | 5.21%   |
| Microdia                               | 4         | 4.17%   |
| Syntek                                 | 3         | 3.13%   |
| Sunplus Innovation Technology          | 3         | 3.13%   |
| Silicon Motion                         | 3         | 3.13%   |
| Luxvisions Innotech Limited            | 3         | 3.13%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.13%   |
| Sonix Technology                       | 2         | 2.08%   |
| Lite-On Technology                     | 1         | 1.04%   |
| LG Electronics                         | 1         | 1.04%   |
| Lenovo                                 | 1         | 1.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                        | 6         | 6.25%   |
| Chicony HD WebCam                                     | 6         | 6.25%   |
| Realtek Integrated_Webcam_HD                          | 4         | 4.17%   |
| Chicony Integrated Camera                             | 4         | 4.17%   |
| Acer Integrated Camera                                | 4         | 4.17%   |
| Acer Lenovo EasyCamera                                | 3         | 3.13%   |
| Syntek EasyCamera                                     | 2         | 2.08%   |
| Suyin HP Webcam                                       | 2         | 2.08%   |
| Sonix USB2.0 HD UVC WebCam                            | 2         | 2.08%   |
| Silicon Motion 300k Pixel Camera                      | 2         | 2.08%   |
| Realtek USB2.0 HD UVC WebCam                          | 2         | 2.08%   |
| Realtek HD WebCam                                     | 2         | 2.08%   |
| Quanta VGA WebCam                                     | 2         | 2.08%   |
| Quanta HP Webcam                                      | 2         | 2.08%   |
| Quanta HP TrueVision HD Camera                        | 2         | 2.08%   |
| Microdia Integrated Webcam                            | 2         | 2.08%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera   | 2         | 2.08%   |
| Chicony USB2.0 VGA UVC WebCam                         | 2         | 2.08%   |
| Chicony Integrated Camera (1280x720@30)               | 2         | 2.08%   |
| Syntek Integrated Camera                              | 1         | 1.04%   |
| Suyin USB Webcam                                      | 1         | 1.04%   |
| Suyin NEC HD WebCam                                   | 1         | 1.04%   |
| Suyin Laptop_Integrated_Webcam_HD                     | 1         | 1.04%   |
| Suyin 1.3M HD WebCam                                  | 1         | 1.04%   |
| Sunplus Laptop_Integrated_Webcam_FHD                  | 1         | 1.04%   |
| Sunplus Integrated_Webcam_HD                          | 1         | 1.04%   |
| Sunplus HD WebCam                                     | 1         | 1.04%   |
| Silicon Motion WebCam SCB-0355N                       | 1         | 1.04%   |
| Realtek Integrated Webcam                             | 1         | 1.04%   |
| Realtek HP "Truevision HD" laptop camera              | 1         | 1.04%   |
| Quanta USB2.0 VGA UVC WebCam                          | 1         | 1.04%   |
| Quanta HD Webcam                                      | 1         | 1.04%   |
| Quanta HD User Facing                                 | 1         | 1.04%   |
| Microdia WebCam SC-13HDL12639P                        | 1         | 1.04%   |
| Microdia Integrated_Webcam_HD                         | 1         | 1.04%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera  | 1         | 1.04%   |
| Lite-On HP HD Camera                                  | 1         | 1.04%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1         | 1.04%   |
| Lenovo UVC Camera                                     | 1         | 1.04%   |
| IMC Networks USB2.0 VGA UVC WebCam                    | 1         | 1.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 37.5%   |
| Shenzhen Goodix Technology | 3         | 37.5%   |
| Validity Sensors           | 1         | 12.5%   |
| AuthenTec                  | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 37.5%   |
| Shenzhen Goodix  FingerPrint Device               | 3         | 37.5%   |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 12.5%   |
| AuthenTec AES2810                                 | 1         | 12.5%   |

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
| 0     | 74        | 66.67%  |
| 1     | 32        | 28.83%  |
| 2     | 5         | 4.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 8         | 18.6%   |
| Net/wireless             | 6         | 13.95%  |
| Multimedia controller    | 5         | 11.63%  |
| Graphics card            | 5         | 11.63%  |
| Camera                   | 5         | 11.63%  |
| Chipcard                 | 4         | 9.3%    |
| Bluetooth                | 4         | 9.3%    |
| Storage                  | 2         | 4.65%   |
| Communication controller | 2         | 4.65%   |
| Network                  | 1         | 2.33%   |
| Dvb card                 | 1         | 2.33%   |

