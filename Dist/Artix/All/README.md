Artix - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Artix.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Artix/Desktop/README.md) and [notebooks](/Dist/Artix/Notebook/README.md).

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

Total: 204

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MOTILE        | M141                        | Notebook    | [59c616a04e](https://linux-hardware.org/?probe=59c616a04e) | Jun 30, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [8ddbebd4b1](https://linux-hardware.org/?probe=8ddbebd4b1) | Jun 28, 2022 |
| AXIOO         | Mybook 14E                  | Notebook    | [499861f5e9](https://linux-hardware.org/?probe=499861f5e9) | Jun 19, 2022 |
| Timi          | RedmiBook 14 II             | Notebook    | [a4b535cdee](https://linux-hardware.org/?probe=a4b535cdee) | Jun 15, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [a4054a2ac8](https://linux-hardware.org/?probe=a4054a2ac8) | Jun 10, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [009ea9b40a](https://linux-hardware.org/?probe=009ea9b40a) | Jun 09, 2022 |
| Lenovo        | ThinkPad T440s 20ARS0MV0... | Notebook    | [3c23c9dfc6](https://linux-hardware.org/?probe=3c23c9dfc6) | Jun 08, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [2a3ac45d9c](https://linux-hardware.org/?probe=2a3ac45d9c) | Jun 05, 2022 |
| Dell          | Precision M6600             | Notebook    | [bb044c066c](https://linux-hardware.org/?probe=bb044c066c) | Jun 05, 2022 |
| Dell          | Latitude 5490               | Notebook    | [630b63edff](https://linux-hardware.org/?probe=630b63edff) | Jun 02, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0e42effbfb](https://linux-hardware.org/?probe=0e42effbfb) | May 17, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [ea492e2997](https://linux-hardware.org/?probe=ea492e2997) | May 13, 2022 |
| LG Electro... | 17Z990-R.AAC9U1             | Notebook    | [dfacdafc7f](https://linux-hardware.org/?probe=dfacdafc7f) | May 11, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [5122079c78](https://linux-hardware.org/?probe=5122079c78) | May 10, 2022 |
| Lenovo        | ThinkPad T480 MFG_IN_GO     | Notebook    | [9792863fc7](https://linux-hardware.org/?probe=9792863fc7) | May 08, 2022 |
| Lenovo        | ThinkPad T480 MFG_IN_GO     | Notebook    | [bba77106b4](https://linux-hardware.org/?probe=bba77106b4) | May 08, 2022 |
| HP            | 15                          | Notebook    | [d9ed47d44c](https://linux-hardware.org/?probe=d9ed47d44c) | Apr 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [85b1934bfd](https://linux-hardware.org/?probe=85b1934bfd) | Apr 21, 2022 |
| ASUSTek       | GX501VIK                    | Notebook    | [076208c6fd](https://linux-hardware.org/?probe=076208c6fd) | Apr 15, 2022 |
| ASUSTek       | GX501VIK                    | Notebook    | [15c4c7877b](https://linux-hardware.org/?probe=15c4c7877b) | Apr 15, 2022 |
| Lenovo        | ThinkPad T430 2350BC6       | Notebook    | [c2ffb2a421](https://linux-hardware.org/?probe=c2ffb2a421) | Apr 14, 2022 |
| HP            | 246                         | Notebook    | [4ef673dd00](https://linux-hardware.org/?probe=4ef673dd00) | Apr 10, 2022 |
| Lenovo        | ThinkPad T430 2347H76       | Notebook    | [493f378237](https://linux-hardware.org/?probe=493f378237) | Mar 10, 2022 |
| Gigabyte      | HA65M-D2H-B3                | Desktop     | [313e83e0ef](https://linux-hardware.org/?probe=313e83e0ef) | Mar 10, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [92db061239](https://linux-hardware.org/?probe=92db061239) | Mar 09, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [299a727e8a](https://linux-hardware.org/?probe=299a727e8a) | Mar 02, 2022 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [604362a51f](https://linux-hardware.org/?probe=604362a51f) | Feb 18, 2022 |
| Notebook      | N141CU                      | Notebook    | [029f48bc53](https://linux-hardware.org/?probe=029f48bc53) | Feb 16, 2022 |
| Acer          | Aspire V3-472PG             | Notebook    | [70c80ae356](https://linux-hardware.org/?probe=70c80ae356) | Feb 16, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [6cf7935dcc](https://linux-hardware.org/?probe=6cf7935dcc) | Feb 14, 2022 |
| Timi          | RedmiBook 14 II             | Notebook    | [3c1248a9d9](https://linux-hardware.org/?probe=3c1248a9d9) | Feb 10, 2022 |
| ASUSTek       | 1225C                       | Notebook    | [b780589dd0](https://linux-hardware.org/?probe=b780589dd0) | Feb 07, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [e02c6336d6](https://linux-hardware.org/?probe=e02c6336d6) | Feb 03, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [b16ba2b14a](https://linux-hardware.org/?probe=b16ba2b14a) | Jan 31, 2022 |
| ASRock        | B150M Pro4S/D3              | Desktop     | [b7a65f897c](https://linux-hardware.org/?probe=b7a65f897c) | Jan 29, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [6a49ff6317](https://linux-hardware.org/?probe=6a49ff6317) | Jan 18, 2022 |
| Lenovo        | G400s 20244                 | Notebook    | [9ac1aa04cc](https://linux-hardware.org/?probe=9ac1aa04cc) | Jan 15, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [29b6159e9c](https://linux-hardware.org/?probe=29b6159e9c) | Jan 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ca93455055](https://linux-hardware.org/?probe=ca93455055) | Jan 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [945649c354](https://linux-hardware.org/?probe=945649c354) | Jan 07, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [1a7ef57da7](https://linux-hardware.org/?probe=1a7ef57da7) | Jan 07, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [bef1d4552a](https://linux-hardware.org/?probe=bef1d4552a) | Jan 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a568bef730](https://linux-hardware.org/?probe=a568bef730) | Jan 05, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [a6c63e1079](https://linux-hardware.org/?probe=a6c63e1079) | Dec 17, 2021 |
| Dell          | Latitude E6440              | Notebook    | [5e572f557c](https://linux-hardware.org/?probe=5e572f557c) | Dec 16, 2021 |
| Dell          | Latitude E6440              | Notebook    | [ac94463e37](https://linux-hardware.org/?probe=ac94463e37) | Dec 16, 2021 |
| ASUSTek       | K50IE                       | Notebook    | [49a6b75a43](https://linux-hardware.org/?probe=49a6b75a43) | Nov 29, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [0e12642e78](https://linux-hardware.org/?probe=0e12642e78) | Nov 27, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [3e700c917e](https://linux-hardware.org/?probe=3e700c917e) | Nov 25, 2021 |
| ASRock        | B450 Steel Legend           | Desktop     | [44ccc8eb49](https://linux-hardware.org/?probe=44ccc8eb49) | Nov 24, 2021 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | Notebook    | [9a5098383d](https://linux-hardware.org/?probe=9a5098383d) | Nov 24, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [9fca12db52](https://linux-hardware.org/?probe=9fca12db52) | Nov 22, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3D40... | Notebook    | [76be488014](https://linux-hardware.org/?probe=76be488014) | Nov 07, 2021 |
| Lenovo        | ThinkPad T480s 20L8S3D40... | Notebook    | [f96363ccf5](https://linux-hardware.org/?probe=f96363ccf5) | Nov 07, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [ded9086b7c](https://linux-hardware.org/?probe=ded9086b7c) | Nov 06, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [038c0ad664](https://linux-hardware.org/?probe=038c0ad664) | Nov 03, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [d8ae8a047c](https://linux-hardware.org/?probe=d8ae8a047c) | Nov 02, 2021 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [65a49b7280](https://linux-hardware.org/?probe=65a49b7280) | Oct 30, 2021 |
| HP            | 1495                        | Desktop     | [e7c0f59f92](https://linux-hardware.org/?probe=e7c0f59f92) | Oct 15, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [e2c619e8dd](https://linux-hardware.org/?probe=e2c619e8dd) | Oct 12, 2021 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [1e612081c8](https://linux-hardware.org/?probe=1e612081c8) | Oct 02, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [c764d879fb](https://linux-hardware.org/?probe=c764d879fb) | Sep 27, 2021 |
| Acer          | Swift SF314-59              | Notebook    | [9426a6d4df](https://linux-hardware.org/?probe=9426a6d4df) | Sep 23, 2021 |
| Acer          | Aspire E5-575               | Notebook    | [d32c769f65](https://linux-hardware.org/?probe=d32c769f65) | Sep 22, 2021 |
| HP            | Laptop 14s-cf3xxx           | Notebook    | [5b9800e687](https://linux-hardware.org/?probe=5b9800e687) | Sep 06, 2021 |
| Dell          | Precision M6600             | Notebook    | [3c06ad8f67](https://linux-hardware.org/?probe=3c06ad8f67) | Sep 06, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [d5871d0e2a](https://linux-hardware.org/?probe=d5871d0e2a) | Aug 25, 2021 |
| ASUSTek       | GL702ZC                     | Notebook    | [7cb34b0a2e](https://linux-hardware.org/?probe=7cb34b0a2e) | Aug 10, 2021 |
| ASUSTek       | GL702ZC                     | Notebook    | [8ab07e196d](https://linux-hardware.org/?probe=8ab07e196d) | Aug 09, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ec331e992a](https://linux-hardware.org/?probe=ec331e992a) | Aug 08, 2021 |
| GPD           | P2 MAX                      | Notebook    | [bf70dbe409](https://linux-hardware.org/?probe=bf70dbe409) | Aug 07, 2021 |
| GPD           | P2 MAX                      | Notebook    | [a4e8eb7d9e](https://linux-hardware.org/?probe=a4e8eb7d9e) | Aug 07, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [558e1369e9](https://linux-hardware.org/?probe=558e1369e9) | Jul 25, 2021 |
| GPD           | P2 MAX                      | Notebook    | [43075e1581](https://linux-hardware.org/?probe=43075e1581) | Jul 23, 2021 |
| HP            | 250 G3                      | Notebook    | [b1a0952727](https://linux-hardware.org/?probe=b1a0952727) | Jul 19, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [156577ba27](https://linux-hardware.org/?probe=156577ba27) | Jul 18, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [a4e06ddea2](https://linux-hardware.org/?probe=a4e06ddea2) | Jul 02, 2021 |
| Lenovo        | LaVie Z 20FF0012US          | Notebook    | [789d556ef6](https://linux-hardware.org/?probe=789d556ef6) | Jul 01, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [f8e9ea8ffa](https://linux-hardware.org/?probe=f8e9ea8ffa) | Jun 26, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [89bbafa02e](https://linux-hardware.org/?probe=89bbafa02e) | Jun 22, 2021 |
| HP            | 15                          | Notebook    | [4f6c5d8c89](https://linux-hardware.org/?probe=4f6c5d8c89) | Jun 22, 2021 |
| MSI           | Z270M MORTAR                | Desktop     | [5c54607559](https://linux-hardware.org/?probe=5c54607559) | Jun 22, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [6a459ac265](https://linux-hardware.org/?probe=6a459ac265) | Jun 16, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [10803bcbc4](https://linux-hardware.org/?probe=10803bcbc4) | Jun 07, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [445e09faa7](https://linux-hardware.org/?probe=445e09faa7) | Jun 07, 2021 |
| Dell          | Precision 7550              | Notebook    | [5d7ecb9bbb](https://linux-hardware.org/?probe=5d7ecb9bbb) | Jun 07, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [181bd83bdd](https://linux-hardware.org/?probe=181bd83bdd) | Jun 02, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [de11ab3cc4](https://linux-hardware.org/?probe=de11ab3cc4) | May 31, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [4688dc5b46](https://linux-hardware.org/?probe=4688dc5b46) | May 29, 2021 |
| Dell          | Precision 7550              | Notebook    | [206eeb06c9](https://linux-hardware.org/?probe=206eeb06c9) | May 23, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [cc7cb4a34e](https://linux-hardware.org/?probe=cc7cb4a34e) | May 22, 2021 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [62d883cffd](https://linux-hardware.org/?probe=62d883cffd) | May 18, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [3f10e6610b](https://linux-hardware.org/?probe=3f10e6610b) | May 18, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [2b91e357ca](https://linux-hardware.org/?probe=2b91e357ca) | May 16, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [85def78a94](https://linux-hardware.org/?probe=85def78a94) | May 02, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [057546c50e](https://linux-hardware.org/?probe=057546c50e) | Apr 30, 2021 |
| HP            | Laptop 17z-ca300            | Notebook    | [ea09357867](https://linux-hardware.org/?probe=ea09357867) | Apr 26, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [d1cf148ec4](https://linux-hardware.org/?probe=d1cf148ec4) | Apr 24, 2021 |
| Acer          | Aspire V3-572PG             | Notebook    | [a874b34c2a](https://linux-hardware.org/?probe=a874b34c2a) | Apr 12, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [132c1a0515](https://linux-hardware.org/?probe=132c1a0515) | Apr 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5527015fb6](https://linux-hardware.org/?probe=5527015fb6) | Apr 08, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [10132d3ee3](https://linux-hardware.org/?probe=10132d3ee3) | Apr 05, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [dbd940a4f3](https://linux-hardware.org/?probe=dbd940a4f3) | Mar 29, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [7f14077ecc](https://linux-hardware.org/?probe=7f14077ecc) | Mar 29, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [666815417c](https://linux-hardware.org/?probe=666815417c) | Mar 28, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [62f6aa5c03](https://linux-hardware.org/?probe=62f6aa5c03) | Mar 27, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [d2027dc1c2](https://linux-hardware.org/?probe=d2027dc1c2) | Mar 24, 2021 |
| MSI           | GP72 7RDX                   | Notebook    | [a60abbdcd4](https://linux-hardware.org/?probe=a60abbdcd4) | Mar 18, 2021 |
| Quanta        | SWH                         | Notebook    | [dc6df30340](https://linux-hardware.org/?probe=dc6df30340) | Mar 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [c2599a37c2](https://linux-hardware.org/?probe=c2599a37c2) | Mar 08, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ce4b5362ed](https://linux-hardware.org/?probe=ce4b5362ed) | Mar 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [76006e9ba5](https://linux-hardware.org/?probe=76006e9ba5) | Mar 01, 2021 |
| Dell          | Precision 7550              | Notebook    | [c1c4fd3b1a](https://linux-hardware.org/?probe=c1c4fd3b1a) | Feb 21, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [91a16f1c67](https://linux-hardware.org/?probe=91a16f1c67) | Feb 21, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [b25144d80b](https://linux-hardware.org/?probe=b25144d80b) | Feb 18, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [c2408f8152](https://linux-hardware.org/?probe=c2408f8152) | Feb 16, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [f93e302542](https://linux-hardware.org/?probe=f93e302542) | Feb 15, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [838f747450](https://linux-hardware.org/?probe=838f747450) | Feb 14, 2021 |
| Alienware     | 02XRCM A01                  | Desktop     | [554d3ebf2f](https://linux-hardware.org/?probe=554d3ebf2f) | Feb 14, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [214d72ae23](https://linux-hardware.org/?probe=214d72ae23) | Feb 12, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b4c4d7f99c](https://linux-hardware.org/?probe=b4c4d7f99c) | Feb 01, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [70eabb568f](https://linux-hardware.org/?probe=70eabb568f) | Jan 30, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [b15b48fb21](https://linux-hardware.org/?probe=b15b48fb21) | Jan 29, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [fb3e2ec12b](https://linux-hardware.org/?probe=fb3e2ec12b) | Jan 24, 2021 |
| ASUSTek       | K53SC                       | Notebook    | [11547cb913](https://linux-hardware.org/?probe=11547cb913) | Jan 22, 2021 |
| ASUSTek       | K53SC                       | Notebook    | [061c52c2ff](https://linux-hardware.org/?probe=061c52c2ff) | Jan 22, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [fda5fabbf5](https://linux-hardware.org/?probe=fda5fabbf5) | Jan 21, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [40e4f5d2fb](https://linux-hardware.org/?probe=40e4f5d2fb) | Jan 21, 2021 |
| Dell          | 0K216C                      | Desktop     | [524206eff9](https://linux-hardware.org/?probe=524206eff9) | Jan 20, 2021 |
| Dell          | 0D9JG3 A00                  | Desktop     | [6c44448201](https://linux-hardware.org/?probe=6c44448201) | Jan 19, 2021 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [c53595bd26](https://linux-hardware.org/?probe=c53595bd26) | Jan 16, 2021 |
| Dell          | Precision 5520              | Notebook    | [a714973647](https://linux-hardware.org/?probe=a714973647) | Jan 16, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [335ee823bd](https://linux-hardware.org/?probe=335ee823bd) | Jan 16, 2021 |
| ASUSTek       | E402NA                      | Notebook    | [ac894b264b](https://linux-hardware.org/?probe=ac894b264b) | Jan 10, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [e8ac486033](https://linux-hardware.org/?probe=e8ac486033) | Jan 09, 2021 |
| ASUSTek       | G11CD                       | Desktop     | [145a13d355](https://linux-hardware.org/?probe=145a13d355) | Jan 07, 2021 |
| ASUSTek       | G11CD                       | Desktop     | [dc70a6fae2](https://linux-hardware.org/?probe=dc70a6fae2) | Jan 07, 2021 |
| HP            | 2B34                        | Desktop     | [e48dc00e0a](https://linux-hardware.org/?probe=e48dc00e0a) | Jan 04, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [6dbd029143](https://linux-hardware.org/?probe=6dbd029143) | Jan 03, 2021 |
| Acer          | Aspire A315-53              | Notebook    | [abac7a5b07](https://linux-hardware.org/?probe=abac7a5b07) | Jan 02, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [7dd04be8aa](https://linux-hardware.org/?probe=7dd04be8aa) | Jan 01, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3f9f87f288](https://linux-hardware.org/?probe=3f9f87f288) | Dec 31, 2020 |
| Dell          | Precision 7550              | Notebook    | [9c8b2f2ad6](https://linux-hardware.org/?probe=9c8b2f2ad6) | Dec 30, 2020 |
| Gigabyte      | B450M DS3H-CF               | Notebook    | [b9c02872aa](https://linux-hardware.org/?probe=b9c02872aa) | Dec 29, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2acc15f485](https://linux-hardware.org/?probe=2acc15f485) | Dec 27, 2020 |
| Dell          | Latitude E6530              | Notebook    | [46704587d1](https://linux-hardware.org/?probe=46704587d1) | Dec 25, 2020 |
| Gigabyte      | B450M DS3H-CF               | Notebook    | [d2701aa534](https://linux-hardware.org/?probe=d2701aa534) | Dec 24, 2020 |
| HP            | 250 G4 Notebook PC          | Notebook    | [178de0b283](https://linux-hardware.org/?probe=178de0b283) | Dec 24, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [a905f1377a](https://linux-hardware.org/?probe=a905f1377a) | Dec 20, 2020 |
| GPD           | P2 MAX                      | Notebook    | [f6249e6387](https://linux-hardware.org/?probe=f6249e6387) | Dec 11, 2020 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [64adbf132b](https://linux-hardware.org/?probe=64adbf132b) | Dec 08, 2020 |
| MSI           | Z87-G45 GAMING              | Desktop     | [cefff6c6c3](https://linux-hardware.org/?probe=cefff6c6c3) | Dec 05, 2020 |
| MSI           | Z87-G45 GAMING              | Desktop     | [cbcb59eb96](https://linux-hardware.org/?probe=cbcb59eb96) | Dec 03, 2020 |
| MSI           | B350M PRO-VDH               | Desktop     | [28b680c91d](https://linux-hardware.org/?probe=28b680c91d) | Nov 29, 2020 |
| Sony          | VPCCB17FG                   | Notebook    | [5a24dc3231](https://linux-hardware.org/?probe=5a24dc3231) | Nov 26, 2020 |
| Acer          | Aspire A315-53              | Notebook    | [bc80dc5050](https://linux-hardware.org/?probe=bc80dc5050) | Nov 25, 2020 |
| Gigabyte      | 990FXA-UD3 R5               | Desktop     | [42a67a5d5e](https://linux-hardware.org/?probe=42a67a5d5e) | Nov 18, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [53a1586791](https://linux-hardware.org/?probe=53a1586791) | Nov 12, 2020 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [61653c183a](https://linux-hardware.org/?probe=61653c183a) | Oct 30, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [f18b33a8f0](https://linux-hardware.org/?probe=f18b33a8f0) | Oct 25, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [acc8c4e663](https://linux-hardware.org/?probe=acc8c4e663) | Oct 25, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [7c29a97dff](https://linux-hardware.org/?probe=7c29a97dff) | Oct 21, 2020 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [961c0be28a](https://linux-hardware.org/?probe=961c0be28a) | Oct 18, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [038ef2ebaa](https://linux-hardware.org/?probe=038ef2ebaa) | Oct 15, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [b877caba0b](https://linux-hardware.org/?probe=b877caba0b) | Oct 13, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [848672f794](https://linux-hardware.org/?probe=848672f794) | Oct 13, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [026a4d80f6](https://linux-hardware.org/?probe=026a4d80f6) | Oct 08, 2020 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [1193653309](https://linux-hardware.org/?probe=1193653309) | Oct 04, 2020 |
| Gigabyte      | P55-USB3                    | Desktop     | [ceeced1246](https://linux-hardware.org/?probe=ceeced1246) | Oct 02, 2020 |
| Dell          | Precision 7550              | Notebook    | [c574758854](https://linux-hardware.org/?probe=c574758854) | Sep 19, 2020 |
| ASUSTek       | H81M-C                      | Desktop     | [b062c35766](https://linux-hardware.org/?probe=b062c35766) | Sep 16, 2020 |
| ASUSTek       | G11CD                       | Desktop     | [962d52b690](https://linux-hardware.org/?probe=962d52b690) | Sep 14, 2020 |
| ASUSTek       | G11CD                       | Desktop     | [a663586db5](https://linux-hardware.org/?probe=a663586db5) | Sep 14, 2020 |
| Dell          | Precision 7550              | Notebook    | [14d1876313](https://linux-hardware.org/?probe=14d1876313) | Aug 31, 2020 |
| Dell          | Precision 7550              | Notebook    | [d44c1dbf60](https://linux-hardware.org/?probe=d44c1dbf60) | Aug 31, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [86215bb4fb](https://linux-hardware.org/?probe=86215bb4fb) | Aug 29, 2020 |
| Dell          | Precision 7550              | Notebook    | [25d7f344e9](https://linux-hardware.org/?probe=25d7f344e9) | Aug 29, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [e988296384](https://linux-hardware.org/?probe=e988296384) | Aug 19, 2020 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [d86cfc12cc](https://linux-hardware.org/?probe=d86cfc12cc) | Aug 19, 2020 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [937f502004](https://linux-hardware.org/?probe=937f502004) | Aug 18, 2020 |
| Acer          | Nitro AN515-51              | Notebook    | [4f2724d5ad](https://linux-hardware.org/?probe=4f2724d5ad) | Aug 16, 2020 |
| MSI           | Z87-G45 GAMING              | Desktop     | [5d992bbc09](https://linux-hardware.org/?probe=5d992bbc09) | Aug 11, 2020 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ff7915ae78](https://linux-hardware.org/?probe=ff7915ae78) | Aug 07, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [aae7fd244a](https://linux-hardware.org/?probe=aae7fd244a) | Aug 06, 2020 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [5e3d9be29a](https://linux-hardware.org/?probe=5e3d9be29a) | Aug 01, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [d5b2c55949](https://linux-hardware.org/?probe=d5b2c55949) | Jul 27, 2020 |
| Lenovo        | ThinkPad T420 4236H45       | Notebook    | [61fd4ce395](https://linux-hardware.org/?probe=61fd4ce395) | Jul 20, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a57e5d7e84](https://linux-hardware.org/?probe=a57e5d7e84) | Jul 08, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [0af3ac770f](https://linux-hardware.org/?probe=0af3ac770f) | Jul 06, 2020 |
| Notebook      | N130BU                      | Notebook    | [e1b81e4880](https://linux-hardware.org/?probe=e1b81e4880) | Jul 05, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [051fa5784a](https://linux-hardware.org/?probe=051fa5784a) | Jul 02, 2020 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [7cb20a8170](https://linux-hardware.org/?probe=7cb20a8170) | Jul 01, 2020 |
| Intel         | DX58SO2 AAG10925-205        | Desktop     | [2e4066d769](https://linux-hardware.org/?probe=2e4066d769) | Jun 30, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9623b5be2b](https://linux-hardware.org/?probe=9623b5be2b) | Jun 16, 2020 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [efaa58fcc8](https://linux-hardware.org/?probe=efaa58fcc8) | Jun 14, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4125763b79](https://linux-hardware.org/?probe=4125763b79) | Jun 12, 2020 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [b5fee1bf94](https://linux-hardware.org/?probe=b5fee1bf94) | Jun 12, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [82af1cec2f](https://linux-hardware.org/?probe=82af1cec2f) | May 30, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [cd633c729b](https://linux-hardware.org/?probe=cd633c729b) | Apr 29, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [40adc1a5f5](https://linux-hardware.org/?probe=40adc1a5f5) | Apr 03, 2020 |
| Dell          | Precision 3540              | Notebook    | [3e582eb1b9](https://linux-hardware.org/?probe=3e582eb1b9) | Mar 30, 2020 |
| Dell          | Precision 3540              | Notebook    | [2a446cd098](https://linux-hardware.org/?probe=2a446cd098) | Feb 15, 2020 |
| Biostar       | G31D-M7                     | Desktop     | [9f6a5c0f39](https://linux-hardware.org/?probe=9f6a5c0f39) | Oct 25, 2018 |
| Lenovo        | B590 20206                  | Notebook    | [a2066c32a9](https://linux-hardware.org/?probe=a2066c32a9) | Oct 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Artix Rolling  | 86        | 60.56%  |
| Artix          | 51        | 35.92%  |
| Artix 20210726 | 2         | 1.41%   |
| Artix 20220123 | 1         | 0.7%    |
| Artix 20201207 | 1         | 0.7%    |
| Artix 20201128 | 1         | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Artix | 135       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.9.14-artix1-1                 | 8         | 4.91%   |
| 5.7.6-artix1-1                  | 5         | 3.07%   |
| 5.7.12-artix1-1                 | 4         | 2.45%   |
| 5.15.12-artix1-1                | 4         | 2.45%   |
| 5.12.12-artix1-1                | 4         | 2.45%   |
| 5.10.4-artix2-1                 | 4         | 2.45%   |
| 5.8.8-artix1-1                  | 3         | 1.84%   |
| 5.8.12-artix1-1                 | 3         | 1.84%   |
| 5.16.3-artix1-1                 | 3         | 1.84%   |
| 5.16.10-artix1-1                | 3         | 1.84%   |
| 5.12.8-artix1-1                 | 3         | 1.84%   |
| 5.12.14-artix1-1                | 3         | 1.84%   |
| 5.10.8-artix1-1                 | 3         | 1.84%   |
| 5.10.6-artix1-1                 | 3         | 1.84%   |
| 5.10.16-artix1-1                | 3         | 1.84%   |
| 5.9.14-zen1-1-zen               | 2         | 1.23%   |
| 5.9.12-artix1-1                 | 2         | 1.23%   |
| 5.8.14-artix1-1                 | 2         | 1.23%   |
| 5.7.2-artix1-1                  | 2         | 1.23%   |
| 5.18.6-artix1-1                 | 2         | 1.23%   |
| 5.18.0-artix1-1                 | 2         | 1.23%   |
| 5.17.4-artix1-1                 | 2         | 1.23%   |
| 5.17.1-artix1-1                 | 2         | 1.23%   |
| 5.16.8-artix1-2                 | 2         | 1.23%   |
| 5.16.1-artix1-1                 | 2         | 1.23%   |
| 5.15.3-zen1-1-zen               | 2         | 1.23%   |
| 5.14.16-artix1-1                | 2         | 1.23%   |
| 5.13.8-artix1-1                 | 2         | 1.23%   |
| 5.12.4-artix1-1                 | 2         | 1.23%   |
| 5.12.12-zen1-1-zen              | 2         | 1.23%   |
| 5.11.6-artix1-1                 | 2         | 1.23%   |
| 5.11.10-artix1-1                | 2         | 1.23%   |
| 5.10.15-artix1-1                | 2         | 1.23%   |
| 4.19.0-1-MANJARO                | 2         | 1.23%   |
| 5.9.8-zen1-1-zen                | 1         | 0.61%   |
| 5.9.6-artix1-1                  | 1         | 0.61%   |
| 5.9.10-artix1-1                 | 1         | 0.61%   |
| 5.9.1-artix1-1                  | 1         | 0.61%   |
| 5.9.0-zen1-1-zen                | 1         | 0.61%   |
| 5.9.0-1-mainline-bootsplash     | 1         | 0.61%   |
| 5.8.5-xanmod1-1-xanmod          | 1         | 0.61%   |
| 5.8.4-artix1-1                  | 1         | 0.61%   |
| 5.8.14-zen1-1-zen               | 1         | 0.61%   |
| 5.8.0-rc7-5-mainline-bootsplash | 1         | 0.61%   |
| 5.7.8-artix1-1                  | 1         | 0.61%   |
| 5.6.7-x86_64                    | 1         | 0.61%   |
| 5.5.3-artix1-1                  | 1         | 0.61%   |
| 5.5.10-artix1-1                 | 1         | 0.61%   |
| 5.4.74-1-lts                    | 1         | 0.61%   |
| 5.4.197-1-lts54                 | 1         | 0.61%   |
| 5.18.5-artix1-1                 | 1         | 0.61%   |
| 5.18.3-zen1-1-zen               | 1         | 0.61%   |
| 5.17.8-258-tkg-pds              | 1         | 0.61%   |
| 5.17.5-256-tkg-pds              | 1         | 0.61%   |
| 5.17.3-zen1-1-zen               | 1         | 0.61%   |
| 5.17.2-artix3-1                 | 1         | 0.61%   |
| 5.17.12-xanmod1-1               | 1         | 0.61%   |
| 5.17.12-lqx1-1-lqx              | 1         | 0.61%   |
| 5.17.1-zen1-1-zen               | 1         | 0.61%   |
| 5.16.8-zen1-1-zen               | 1         | 0.61%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.14  | 10        | 6.13%   |
| 5.12.12 | 6         | 3.68%   |
| 5.7.6   | 5         | 3.07%   |
| 5.15.12 | 5         | 3.07%   |
| 5.7.12  | 4         | 2.45%   |
| 5.12.8  | 4         | 2.45%   |
| 5.12.14 | 4         | 2.45%   |
| 5.10.4  | 4         | 2.45%   |
| 5.8.8   | 3         | 1.84%   |
| 5.8.14  | 3         | 1.84%   |
| 5.8.12  | 3         | 1.84%   |
| 5.17.1  | 3         | 1.84%   |
| 5.16.8  | 3         | 1.84%   |
| 5.16.3  | 3         | 1.84%   |
| 5.16.10 | 3         | 1.84%   |
| 5.13.8  | 3         | 1.84%   |
| 5.10.8  | 3         | 1.84%   |
| 5.10.6  | 3         | 1.84%   |
| 5.10.16 | 3         | 1.84%   |
| 5.10.15 | 3         | 1.84%   |
| 5.9.12  | 2         | 1.23%   |
| 5.9.0   | 2         | 1.23%   |
| 5.7.2   | 2         | 1.23%   |
| 5.18.6  | 2         | 1.23%   |
| 5.18.0  | 2         | 1.23%   |
| 5.17.4  | 2         | 1.23%   |
| 5.17.12 | 2         | 1.23%   |
| 5.16.1  | 2         | 1.23%   |
| 5.15.3  | 2         | 1.23%   |
| 5.14.16 | 2         | 1.23%   |
| 5.14.14 | 2         | 1.23%   |
| 5.12.4  | 2         | 1.23%   |
| 5.11.6  | 2         | 1.23%   |
| 5.11.16 | 2         | 1.23%   |
| 5.11.10 | 2         | 1.23%   |
| 4.19.0  | 2         | 1.23%   |
| 5.9.8   | 1         | 0.61%   |
| 5.9.6   | 1         | 0.61%   |
| 5.9.10  | 1         | 0.61%   |
| 5.9.1   | 1         | 0.61%   |
| 5.8.5   | 1         | 0.61%   |
| 5.8.4   | 1         | 0.61%   |
| 5.8.0   | 1         | 0.61%   |
| 5.7.8   | 1         | 0.61%   |
| 5.6.7   | 1         | 0.61%   |
| 5.5.3   | 1         | 0.61%   |
| 5.5.10  | 1         | 0.61%   |
| 5.4.74  | 1         | 0.61%   |
| 5.4.197 | 1         | 0.61%   |
| 5.18.5  | 1         | 0.61%   |
| 5.18.3  | 1         | 0.61%   |
| 5.17.8  | 1         | 0.61%   |
| 5.17.5  | 1         | 0.61%   |
| 5.17.3  | 1         | 0.61%   |
| 5.17.2  | 1         | 0.61%   |
| 5.16.7  | 1         | 0.61%   |
| 5.16.12 | 1         | 0.61%   |
| 5.16.0  | 1         | 0.61%   |
| 5.15.8  | 1         | 0.61%   |
| 5.15.7  | 1         | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 21        | 13.55%  |
| 5.12    | 19        | 12.26%  |
| 5.9     | 17        | 10.97%  |
| 5.15    | 16        | 10.32%  |
| 5.16    | 13        | 8.39%   |
| 5.11    | 12        | 7.74%   |
| 5.8     | 11        | 7.1%    |
| 5.17    | 11        | 7.1%    |
| 5.7     | 10        | 6.45%   |
| 5.14    | 7         | 4.52%   |
| 5.18    | 6         | 3.87%   |
| 5.13    | 6         | 3.87%   |
| 5.4     | 2         | 1.29%   |
| 4.19    | 2         | 1.29%   |
| 5.6     | 1         | 0.65%   |
| 5.5     | 1         | 0.65%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 135       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| KDE5           | 31        | 21.38%  |
| GNOME          | 25        | 17.24%  |
| XFCE           | 21        | 14.48%  |
| Unknown        | 19        | 13.1%   |
| X-Cinnamon     | 11        | 7.59%   |
| MATE           | 8         | 5.52%   |
| Cinnamon       | 5         | 3.45%   |
| LXQt           | 4         | 2.76%   |
| KDE            | 4         | 2.76%   |
| bspwm          | 4         | 2.76%   |
| Sway           | 2         | 1.38%   |
| LXDE           | 2         | 1.38%   |
| i3             | 2         | 1.38%   |
| xmonad         | 1         | 0.69%   |
| sway-dbus      | 1         | 0.69%   |
| openbox        | 1         | 0.69%   |
| nxde           | 1         | 0.69%   |
| DWM            | 1         | 0.69%   |
| awesomeminimal | 1         | 0.69%   |
| awesome        | 1         | 0.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 97        | 68.79%  |
| Tty     | 22        | 15.6%   |
| Wayland | 15        | 10.64%  |
| Unknown | 7         | 4.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 49        | 34.75%  |
| LightDM | 42        | 29.79%  |
| SDDM    | 40        | 28.37%  |
| GDM     | 4         | 2.84%   |
| XDM     | 2         | 1.42%   |
| LXDM    | 2         | 1.42%   |
| SLiM    | 1         | 0.71%   |
| Ly      | 1         | 0.71%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 61        | 43.57%  |
| Unknown | 16        | 11.43%  |
| ru_RU   | 11        | 7.86%   |
| fr_FR   | 8         | 5.71%   |
| en_GB   | 8         | 5.71%   |
| de_DE   | 6         | 4.29%   |
| C       | 6         | 4.29%   |
| pt_PT   | 3         | 2.14%   |
| es_ES   | 3         | 2.14%   |
| it_IT   | 2         | 1.43%   |
| en_CA   | 2         | 1.43%   |
| en_AU   | 2         | 1.43%   |
| el_GR   | 2         | 1.43%   |
| uk_UA   | 1         | 0.71%   |
| pt_BR   | 1         | 0.71%   |
| pl_PL   | 1         | 0.71%   |
| ja_JP   | 1         | 0.71%   |
| es_MX   | 1         | 0.71%   |
| es_AR   | 1         | 0.71%   |
| en_IN   | 1         | 0.71%   |
| en_IE   | 1         | 0.71%   |
| cs_CZ   | 1         | 0.71%   |
| bg_BG   | 1         | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 100       | 72.99%  |
| BIOS | 37        | 27.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 97        | 71.32%  |
| Btrfs   | 29        | 21.32%  |
| Xfs     | 5         | 3.68%   |
| F2fs    | 3         | 2.21%   |
| Overlay | 1         | 0.74%   |
| Jfs     | 1         | 0.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 103       | 74.64%  |
| Unknown | 21        | 15.22%  |
| MBR     | 14        | 10.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 110       | 80.29%  |
| Yes       | 27        | 19.71%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 99        | 72.79%  |
| Yes       | 37        | 27.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 27        | 20%     |
| ASUSTek Computer    | 23        | 17.04%  |
| Hewlett-Packard     | 15        | 11.11%  |
| Dell                | 13        | 9.63%   |
| Gigabyte Technology | 11        | 8.15%   |
| MSI                 | 10        | 7.41%   |
| Acer                | 9         | 6.67%   |
| ASRock              | 6         | 4.44%   |
| Apple               | 3         | 2.22%   |
| Timi                | 2         | 1.48%   |
| Notebook            | 2         | 1.48%   |
| Intel               | 2         | 1.48%   |
| GPD                 | 2         | 1.48%   |
| UNOWHY              | 1         | 0.74%   |
| Quanta              | 1         | 0.74%   |
| MOTILE              | 1         | 0.74%   |
| Microsoft           | 1         | 0.74%   |
| LG Electronics      | 1         | 0.74%   |
| HUAWEI              | 1         | 0.74%   |
| Biostar             | 1         | 0.74%   |
| AXIOO               | 1         | 0.74%   |
| Alienware           | 1         | 0.74%   |
| Acidanthera         | 1         | 0.74%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Timi RedmiBook 14 II                   | 2         | 1.48%   |
| MSI MS-7C02                            | 2         | 1.48%   |
| MSI MS-7A38                            | 2         | 1.48%   |
| Lenovo IdeaPad 5 15IIL05 81YK          | 2         | 1.48%   |
| HP 15                                  | 2         | 1.48%   |
| GPD P2 MAX                             | 2         | 1.48%   |
| Gigabyte 970A-DS3P                     | 2         | 1.48%   |
| Dell Precision M6600                   | 2         | 1.48%   |
| Dell Precision 7550                    | 2         | 1.48%   |
| Apple MacBookAir7,2                    | 2         | 1.48%   |
| UNOWHY Y13G010S4EI                     | 1         | 0.74%   |
| Quanta SWH                             | 1         | 0.74%   |
| Notebook N141CU                        | 1         | 0.74%   |
| Notebook N130BU                        | 1         | 0.74%   |
| MSI MS-7C56                            | 1         | 0.74%   |
| MSI MS-7C37                            | 1         | 0.74%   |
| MSI MS-7B79                            | 1         | 0.74%   |
| MSI MS-7A69                            | 1         | 0.74%   |
| MSI Modern 15 A11M                     | 1         | 0.74%   |
| MSI GP72 7RDX                          | 1         | 0.74%   |
| MOTILE M141                            | 1         | 0.74%   |
| Microsoft Surface Pro                  | 1         | 0.74%   |
| LG 17Z990-R.AAC9U1                     | 1         | 0.74%   |
| Lenovo ThinkPad W500 4063CJ5           | 1         | 0.74%   |
| Lenovo ThinkPad T480s 20L8S3D400       | 1         | 0.74%   |
| Lenovo ThinkPad T480 MFG_IN_GO         | 1         | 0.74%   |
| Lenovo ThinkPad T440s 20ARS0MV00       | 1         | 0.74%   |
| Lenovo ThinkPad T430 2350BC6           | 1         | 0.74%   |
| Lenovo ThinkPad T430 2347H76           | 1         | 0.74%   |
| Lenovo ThinkPad T420 4236H45           | 1         | 0.74%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00   | 1         | 0.74%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800   | 1         | 0.74%   |
| Lenovo ThinkPad P1 Gen 3 20TH001EMH    | 1         | 0.74%   |
| Lenovo ThinkPad E14 Gen 2 20T6000MCK   | 1         | 0.74%   |
| Lenovo ThinkPad 11e 5th Gen 20LNS0P500 | 1         | 0.74%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 1         | 0.74%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 0.74%   |
| Lenovo LaVie Z 20FF0012US              | 1         | 0.74%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2      | 1         | 0.74%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU      | 1         | 0.74%   |
| Lenovo IdeaPad Y500 20193              | 1         | 0.74%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL  | 1         | 0.74%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG   | 1         | 0.74%   |
| Lenovo IdeaPad 510-15IKB 80SV          | 1         | 0.74%   |
| Lenovo IdeaPad 330-15IKB 81DE          | 1         | 0.74%   |
| Lenovo G400s 20244                     | 1         | 0.74%   |
| Lenovo B590 20206                      | 1         | 0.74%   |
| Lenovo B570e HuronRiver Platform       | 1         | 0.74%   |
| Intel NUC7CJYH                         | 1         | 0.74%   |
| Intel DX58SO2 AAG10925-205             | 1         | 0.74%   |
| HUAWEI WRT-WX9                         | 1         | 0.74%   |
| HP ProBook 450 G6                      | 1         | 0.74%   |
| HP OMEN Laptop 15-en0xxx               | 1         | 0.74%   |
| HP Laptop 17z-ca300                    | 1         | 0.74%   |
| HP Laptop 15-ef1xxx                    | 1         | 0.74%   |
| HP Laptop 14s-dq2xxx                   | 1         | 0.74%   |
| HP Laptop 14s-cf3xxx                   | 1         | 0.74%   |
| HP Compaq 8200 Elite SFF PC            | 1         | 0.74%   |
| HP 280 G1 MT                           | 1         | 0.74%   |
| HP 255 G7 Notebook PC                  | 1         | 0.74%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 12        | 8.89%   |
| Lenovo IdeaPad        | 7         | 5.19%   |
| Dell Precision        | 6         | 4.44%   |
| Acer Aspire           | 6         | 4.44%   |
| HP Laptop             | 4         | 2.96%   |
| HP 250                | 3         | 2.22%   |
| Dell Latitude         | 3         | 2.22%   |
| Dell Inspiron         | 3         | 2.22%   |
| ASUS ROG              | 3         | 2.22%   |
| ASUS PRIME            | 3         | 2.22%   |
| Timi RedmiBook        | 2         | 1.48%   |
| MSI MS-7C02           | 2         | 1.48%   |
| MSI MS-7A38           | 2         | 1.48%   |
| Lenovo IdeaPadFlex    | 2         | 1.48%   |
| HP 15                 | 2         | 1.48%   |
| GPD P2                | 2         | 1.48%   |
| Gigabyte X570         | 2         | 1.48%   |
| Gigabyte 970A-DS3P    | 2         | 1.48%   |
| ASUS TUF              | 2         | 1.48%   |
| Apple MacBookAir7     | 2         | 1.48%   |
| Acer Nitro            | 2         | 1.48%   |
| UNOWHY Y13G010S4EI    | 1         | 0.74%   |
| Quanta SWH            | 1         | 0.74%   |
| Notebook N141CU       | 1         | 0.74%   |
| Notebook N130BU       | 1         | 0.74%   |
| MSI MS-7C56           | 1         | 0.74%   |
| MSI MS-7C37           | 1         | 0.74%   |
| MSI MS-7B79           | 1         | 0.74%   |
| MSI MS-7A69           | 1         | 0.74%   |
| MSI Modern            | 1         | 0.74%   |
| MSI GP72              | 1         | 0.74%   |
| MOTILE M141           | 1         | 0.74%   |
| Microsoft Surface     | 1         | 0.74%   |
| LG 17Z990-R.AAC9U1    | 1         | 0.74%   |
| Lenovo ThinkBook      | 1         | 0.74%   |
| Lenovo Legion         | 1         | 0.74%   |
| Lenovo LaVie          | 1         | 0.74%   |
| Lenovo G400s          | 1         | 0.74%   |
| Lenovo B590           | 1         | 0.74%   |
| Lenovo B570e          | 1         | 0.74%   |
| Intel NUC7CJYH        | 1         | 0.74%   |
| Intel DX58SO2         | 1         | 0.74%   |
| HUAWEI WRT-WX9        | 1         | 0.74%   |
| HP ProBook            | 1         | 0.74%   |
| HP OMEN               | 1         | 0.74%   |
| HP Compaq             | 1         | 0.74%   |
| HP 280                | 1         | 0.74%   |
| HP 255                | 1         | 0.74%   |
| HP 246                | 1         | 0.74%   |
| Gigabyte X399         | 1         | 0.74%   |
| Gigabyte P55-USB3     | 1         | 0.74%   |
| Gigabyte HA65M-D2H-B3 | 1         | 0.74%   |
| Gigabyte B450M        | 1         | 0.74%   |
| Gigabyte AERO         | 1         | 0.74%   |
| Gigabyte 990FXA-UD5   | 1         | 0.74%   |
| Gigabyte 990FXA-UD3   | 1         | 0.74%   |
| Dell OptiPlex         | 1         | 0.74%   |
| Biostar G31D-M7       | 1         | 0.74%   |
| AXIOO Mybook          | 1         | 0.74%   |
| ASUS X553MA           | 1         | 0.74%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 29        | 21.48%  |
| 2019 | 21        | 15.56%  |
| 2018 | 16        | 11.85%  |
| 2017 | 13        | 9.63%   |
| 2012 | 10        | 7.41%   |
| 2011 | 9         | 6.67%   |
| 2014 | 8         | 5.93%   |
| 2013 | 8         | 5.93%   |
| 2016 | 7         | 5.19%   |
| 2015 | 5         | 3.7%    |
| 2021 | 3         | 2.22%   |
| 2010 | 3         | 2.22%   |
| 2008 | 2         | 1.48%   |
| 2009 | 1         | 0.74%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 85        | 62.96%  |
| Desktop     | 45        | 33.33%  |
| Convertible | 2         | 1.48%   |
| Tablet      | 1         | 0.74%   |
| Mini pc     | 1         | 0.74%   |
| All in one  | 1         | 0.74%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 134       | 99.26%  |
| Enabled  | 1         | 0.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 135       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 35        | 25.55%  |
| 8.01-16.0   | 35        | 25.55%  |
| 4.01-8.0    | 25        | 18.25%  |
| 3.01-4.0    | 18        | 13.14%  |
| 32.01-64.0  | 10        | 7.3%    |
| 64.01-256.0 | 7         | 5.11%   |
| 1.01-2.0    | 5         | 3.65%   |
| 24.01-32.0  | 2         | 1.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 39        | 25.32%  |
| 4.01-8.0   | 35        | 22.73%  |
| 2.01-3.0   | 31        | 20.13%  |
| 3.01-4.0   | 25        | 16.23%  |
| 0.51-1.0   | 13        | 8.44%   |
| 8.01-16.0  | 5         | 3.25%   |
| 0.01-0.5   | 4         | 2.6%    |
| 16.01-24.0 | 2         | 1.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 77        | 55.8%   |
| 2      | 39        | 28.26%  |
| 3      | 14        | 10.14%  |
| 4      | 4         | 2.9%    |
| 6      | 2         | 1.45%   |
| 8      | 1         | 0.72%   |
| 7      | 1         | 0.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 99        | 73.33%  |
| Yes       | 36        | 26.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 85.93%  |
| No        | 19        | 14.07%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 110       | 81.48%  |
| No        | 25        | 18.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 90        | 65.69%  |
| No        | 47        | 34.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 27        | 19.85%  |
| Germany     | 15        | 11.03%  |
| Russia      | 12        | 8.82%   |
| France      | 10        | 7.35%   |
| UK          | 5         | 3.68%   |
| Ukraine     | 4         | 2.94%   |
| Turkey      | 4         | 2.94%   |
| Switzerland | 4         | 2.94%   |
| Poland      | 4         | 2.94%   |
| Indonesia   | 4         | 2.94%   |
| Greece      | 4         | 2.94%   |
| Canada      | 4         | 2.94%   |
| Bulgaria    | 4         | 2.94%   |
| Brazil      | 4         | 2.94%   |
| Spain       | 3         | 2.21%   |
| Netherlands | 3         | 2.21%   |
| India       | 3         | 2.21%   |
| Italy       | 2         | 1.47%   |
| Australia   | 2         | 1.47%   |
| Argentina   | 2         | 1.47%   |
| Uzbekistan  | 1         | 0.74%   |
| Sweden      | 1         | 0.74%   |
| Slovenia    | 1         | 0.74%   |
| Mexico      | 1         | 0.74%   |
| Lithuania   | 1         | 0.74%   |
| Japan       | 1         | 0.74%   |
| Iran        | 1         | 0.74%   |
| Hong Kong   | 1         | 0.74%   |
| Finland     | 1         | 0.74%   |
| Czechia     | 1         | 0.74%   |
| China       | 1         | 0.74%   |
| Chile       | 1         | 0.74%   |
| Bangladesh  | 1         | 0.74%   |
| Azerbaijan  | 1         | 0.74%   |
| Austria     | 1         | 0.74%   |
| Algeria     | 1         | 0.74%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Paris                  | 6         | 4.17%   |
| Frankfurt am Main      | 4         | 2.78%   |
| Moscow                 | 3         | 2.08%   |
| Jakarta                | 3         | 2.08%   |
| Dnipro                 | 3         | 2.08%   |
| St Petersburg          | 2         | 1.39%   |
| Sofia                  | 2         | 1.39%   |
| Snohomish              | 2         | 1.39%   |
| San Ramon              | 2         | 1.39%   |
| Omaha                  | 2         | 1.39%   |
| Neuchatel              | 2         | 1.39%   |
| Los Angeles            | 2         | 1.39%   |
| Kłodzko               | 2         | 1.39%   |
| Charlotte              | 2         | 1.39%   |
| Bern                   | 2         | 1.39%   |
| Athens                 | 2         | 1.39%   |
| Amsterdam              | 2         | 1.39%   |
| Zaporizhzhya           | 1         | 0.69%   |
| Wigan                  | 1         | 0.69%   |
| Wettringen             | 1         | 0.69%   |
| Wem                    | 1         | 0.69%   |
| Vilnius                | 1         | 0.69%   |
| Vienna                 | 1         | 0.69%   |
| Varna                  | 1         | 0.69%   |
| Vancouver              | 1         | 0.69%   |
| Upper Norwood          | 1         | 0.69%   |
| Ufa                    | 1         | 0.69%   |
| Toronto                | 1         | 0.69%   |
| Thessaloniki           | 1         | 0.69%   |
| Tehran                 | 1         | 0.69%   |
| Tashkent               | 1         | 0.69%   |
| Syeverodonets'k        | 1         | 0.69%   |
| Sydney                 | 1         | 0.69%   |
| Surgut                 | 1         | 0.69%   |
| Stuttgart              | 1         | 0.69%   |
| Stockholm              | 1         | 0.69%   |
| Stein                  | 1         | 0.69%   |
| Stavropol              | 1         | 0.69%   |
| Statesboro             | 1         | 0.69%   |
| Speichersdorf          | 1         | 0.69%   |
| Skikda                 | 1         | 0.69%   |
| Sigogne                | 1         | 0.69%   |
| Shavertown             | 1         | 0.69%   |
| Seville                | 1         | 0.69%   |
| Semarang               | 1         | 0.69%   |
| Seattle                | 1         | 0.69%   |
| Santiago               | 1         | 0.69%   |
| Santa Fe               | 1         | 0.69%   |
| San Miguel de Tucumán | 1         | 0.69%   |
| Samara                 | 1         | 0.69%   |
| Sainte-Severe          | 1         | 0.69%   |
| Riverview              | 1         | 0.69%   |
| Rio de Janeiro         | 1         | 0.69%   |
| Quincy                 | 1         | 0.69%   |
| Puducherry             | 1         | 0.69%   |
| Prague                 | 1         | 0.69%   |
| Plovdiv                | 1         | 0.69%   |
| Ordu                   | 1         | 0.69%   |
| Onda                   | 1         | 0.69%   |
| Omsk                   | 1         | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 34        | 41     | 15.81%  |
| Samsung Electronics       | 34        | 48     | 15.81%  |
| WDC                       | 27        | 47     | 12.56%  |
| Toshiba                   | 16        | 17     | 7.44%   |
| Kingston                  | 14        | 15     | 6.51%   |
| SanDisk                   | 10        | 12     | 4.65%   |
| Intel                     | 10        | 15     | 4.65%   |
| Crucial                   | 10        | 16     | 4.65%   |
| SK hynix                  | 7         | 13     | 3.26%   |
| HGST                      | 6         | 7      | 2.79%   |
| Hitachi                   | 5         | 6      | 2.33%   |
| China                     | 5         | 5      | 2.33%   |
| Apple                     | 3         | 4      | 1.4%    |
| Unknown                   | 2         | 2      | 0.93%   |
| SPCC                      | 2         | 2      | 0.93%   |
| PNY                       | 2         | 2      | 0.93%   |
| Phison Electronics        | 2         | 3      | 0.93%   |
| Maxtor                    | 2         | 2      | 0.93%   |
| Linux                     | 2         | 2      | 0.93%   |
| JMicron Technology        | 2         | 2      | 0.93%   |
| Corsair                   | 2         | 2      | 0.93%   |
| Union Memory              | 1         | 1      | 0.47%   |
| TS512GMT                  | 1         | 3      | 0.47%   |
| Transcend                 | 1         | 1      | 0.47%   |
| Timetec                   | 1         | 2      | 0.47%   |
| Solid State Storage       | 1         | 1      | 0.47%   |
| Phison                    | 1         | 1      | 0.47%   |
| Patriot                   | 1         | 1      | 0.47%   |
| Netac                     | 1         | 1      | 0.47%   |
| Micron/Crucial Technology | 1         | 1      | 0.47%   |
| LITEON                    | 1         | 1      | 0.47%   |
| Lite-On                   | 1         | 1      | 0.47%   |
| LDLC                      | 1         | 5      | 0.47%   |
| Intenso                   | 1         | 1      | 0.47%   |
| Hewlett-Packard           | 1         | 1      | 0.47%   |
| Goodram                   | 1         | 1      | 0.47%   |
| AMD                       | 1         | 1      | 0.47%   |
| A-DATA Technology         | 1         | 1      | 0.47%   |
| Unknown                   | 1         | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| SanDisk NVMe SSD Drive 512GB         | 4         | 1.69%   |
| Toshiba DT01ACA100 1TB               | 3         | 1.27%   |
| Seagate ST3500418AS 500GB            | 3         | 1.27%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 1.27%   |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 1.27%   |
| Samsung SSD 970 EVO 1TB              | 3         | 1.27%   |
| Samsung SSD 860 EVO 250GB            | 3         | 1.27%   |
| Samsung NVMe SSD Drive 1TB           | 3         | 1.27%   |
| HGST HTS545050A7E680 500GB           | 3         | 1.27%   |
| Crucial CT240BX500SSD1 240GB         | 3         | 1.27%   |
| Crucial CT1000MX500SSD1 1TB          | 3         | 1.27%   |
| China SATA SSD 960GB                 | 3         | 1.27%   |
| WDC WD80EZAZ-11TDBA0 8TB             | 2         | 0.85%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.85%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 0.85%   |
| Toshiba MQ04ABF100 1TB               | 2         | 0.85%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.85%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 0.85%   |
| SanDisk NVMe SSD Drive 500GB         | 2         | 0.85%   |
| Samsung SSD 870 EVO 250GB            | 2         | 0.85%   |
| Samsung MZYTY256HDHP-000L2 256GB SSD | 2         | 0.85%   |
| Samsung MZNLH512HALU-00000 512GB SSD | 2         | 0.85%   |
| Phison PCIe SSD 2TB                  | 2         | 0.85%   |
| Linux scsi_debug 8.3MB               | 2         | 0.85%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 0.85%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 0.85%   |
| Apple SSD SM0256G 256GB              | 2         | 0.85%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.42%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.42%   |
| WDC WDS256G1X0C-00ENX0 256GB         | 1         | 0.42%   |
| WDC WDS200T2B0B-00YS70 2TB SSD       | 1         | 0.42%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 0.42%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 0.42%   |
| WDC WDBNCE5000PNC 500GB SSD          | 1         | 0.42%   |
| WDC WD6001FZWX-00A2VA0 6TB           | 1         | 0.42%   |
| WDC WD5003ABYX-18WERA0 500GB         | 1         | 0.42%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 1         | 0.42%   |
| WDC WD5000LPVX-00V0TT0 500GB         | 1         | 0.42%   |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 0.42%   |
| WDC WD5000AAKX-60U6AA0 500GB         | 1         | 0.42%   |
| WDC WD40EZRZ-00WN9B0 4TB             | 1         | 0.42%   |
| WDC WD4003FZEX-00Z4SA0 4TB           | 1         | 0.42%   |
| WDC WD4003FFBX-68MU3N0 4TB           | 1         | 0.42%   |
| WDC WD3200LPVT-00FMCT0 320GB         | 1         | 0.42%   |
| WDC WD30EZRX-00DC0B0 3TB             | 1         | 0.42%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1         | 0.42%   |
| WDC WD2500HHTZ-04N21V0 250GB         | 1         | 0.42%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 0.42%   |
| WDC WD20EZBX-00AYRA0 2TB             | 1         | 0.42%   |
| WDC WD20EARS-00MVWB0 2TB             | 1         | 0.42%   |
| WDC WD2003FZEX-00SRLA0 2TB           | 1         | 0.42%   |
| WDC WD15EARS-22MVWB0 1TB             | 1         | 0.42%   |
| WDC WD10SPZX-60Z10T0 1TB             | 1         | 0.42%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.42%   |
| WDC WD10EZRZ-00HTKB0 1TB             | 1         | 0.42%   |
| WDC WD10EZEX-00BN5A0 1TB             | 1         | 0.42%   |
| WDC WD100EMAZ-00WJTA0 10TB           | 1         | 0.42%   |
| Unknown SD/MMC/MS PRO 128GB          | 1         | 0.42%   |
| Unknown DA4064  64GB                 | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 34        | 41     | 40%     |
| WDC                | 23        | 37     | 27.06%  |
| Toshiba            | 13        | 14     | 15.29%  |
| HGST               | 6         | 7      | 7.06%   |
| Hitachi            | 5         | 6      | 5.88%   |
| Maxtor             | 2         | 2      | 2.35%   |
| Unknown            | 1         | 1      | 1.18%   |
| JMicron Technology | 1         | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 19     | 20.9%   |
| Kingston            | 10        | 10     | 14.93%  |
| Crucial             | 10        | 16     | 14.93%  |
| China               | 5         | 5      | 7.46%   |
| WDC                 | 4         | 7      | 5.97%   |
| SanDisk             | 3         | 3      | 4.48%   |
| Intel               | 3         | 4      | 4.48%   |
| Apple               | 3         | 4      | 4.48%   |
| SPCC                | 2         | 2      | 2.99%   |
| Linux               | 2         | 2      | 2.99%   |
| Toshiba             | 1         | 1      | 1.49%   |
| SK hynix            | 1         | 1      | 1.49%   |
| PNY                 | 1         | 1      | 1.49%   |
| Patriot             | 1         | 1      | 1.49%   |
| Netac               | 1         | 1      | 1.49%   |
| LDLC                | 1         | 5      | 1.49%   |
| JMicron Technology  | 1         | 1      | 1.49%   |
| Intenso             | 1         | 1      | 1.49%   |
| Goodram             | 1         | 1      | 1.49%   |
| AMD                 | 1         | 1      | 1.49%   |
| A-DATA Technology   | 1         | 1      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 73        | 109    | 38.22%  |
| SSD     | 59        | 87     | 30.89%  |
| NVMe    | 55        | 85     | 28.8%   |
| Unknown | 3         | 6      | 1.57%   |
| MMC     | 1         | 1      | 0.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 102       | 193    | 61.82%  |
| NVMe | 55        | 85     | 33.33%  |
| SAS  | 7         | 9      | 4.24%   |
| MMC  | 1         | 1      | 0.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 68        | 99     | 49.28%  |
| 0.51-1.0   | 47        | 66     | 34.06%  |
| 1.01-2.0   | 12        | 14     | 8.7%    |
| 2.01-3.0   | 4         | 4      | 2.9%    |
| 4.01-10.0  | 4         | 10     | 2.9%    |
| 3.01-4.0   | 3         | 3      | 2.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 36        | 25.9%   |
| 251-500        | 29        | 20.86%  |
| 1001-2000      | 19        | 13.67%  |
| 501-1000       | 17        | 12.23%  |
| More than 3000 | 13        | 9.35%   |
| 2001-3000      | 9         | 6.47%   |
| 51-100         | 7         | 5.04%   |
| Unknown        | 5         | 3.6%    |
| 21-50          | 2         | 1.44%   |
| 1-20           | 2         | 1.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 33        | 22.6%   |
| 101-250        | 24        | 16.44%  |
| 501-1000       | 21        | 14.38%  |
| 251-500        | 15        | 10.27%  |
| 21-50          | 15        | 10.27%  |
| 51-100         | 15        | 10.27%  |
| 1001-2000      | 9         | 6.16%   |
| More than 3000 | 6         | 4.11%   |
| Unknown        | 5         | 3.42%   |
| 2001-3000      | 3         | 2.05%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB           | 2         | 2      | 8.33%   |
| HGST HTS545050A7E680 500GB       | 2         | 2      | 8.33%   |
| WDC WD3200LPVT-00FMCT0 320GB     | 1         | 1      | 4.17%   |
| WDC WD30EZRX-00DC0B0 3TB         | 1         | 1      | 4.17%   |
| Toshiba MK7575GSX 752GB          | 1         | 1      | 4.17%   |
| Toshiba MK5065GSX 500GB          | 1         | 1      | 4.17%   |
| Seagate ST8000DM004-2CX188 8TB   | 1         | 1      | 4.17%   |
| Seagate ST500LT012-9WS142 500GB  | 1         | 1      | 4.17%   |
| Seagate ST500LT012-1DG142 500GB  | 1         | 1      | 4.17%   |
| Seagate ST2000DX002-2DV164 2TB   | 1         | 1      | 4.17%   |
| Seagate ST2000DM006-2DM164 2TB   | 1         | 1      | 4.17%   |
| Seagate ST1000LM035-1RK172 1TB   | 1         | 1      | 4.17%   |
| Maxtor 6Y080M0 81GB              | 1         | 1      | 4.17%   |
| LDLC SSD 120GB                   | 1         | 3      | 4.17%   |
| Kingston SUV400S37240G 240GB SSD | 1         | 1      | 4.17%   |
| Kingston SA400S37120G 120GB SSD  | 1         | 1      | 4.17%   |
| Intel SSDSC2BW480A4 480GB        | 1         | 2      | 4.17%   |
| Intel SSDPEKKW128G7 128GB        | 1         | 1      | 4.17%   |
| Hitachi HTS547550A9E384 500GB    | 1         | 1      | 4.17%   |
| Hitachi HTS542516K9SA00 160GB    | 1         | 1      | 4.17%   |
| HGST HTS541010A9E680 1TB         | 1         | 1      | 4.17%   |
| Hewlett-Packard SSD EX900 250GB  | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 6         | 6      | 25%     |
| Toshiba         | 4         | 4      | 16.67%  |
| HGST            | 3         | 3      | 12.5%   |
| WDC             | 2         | 2      | 8.33%   |
| Kingston        | 2         | 2      | 8.33%   |
| Intel           | 2         | 3      | 8.33%   |
| Hitachi         | 2         | 2      | 8.33%   |
| Maxtor          | 1         | 1      | 4.17%   |
| LDLC            | 1         | 3      | 4.17%   |
| Hewlett-Packard | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 33.33%  |
| Toshiba | 4         | 4      | 22.22%  |
| HGST    | 3         | 3      | 16.67%  |
| WDC     | 2         | 2      | 11.11%  |
| Hitachi | 2         | 2      | 11.11%  |
| Maxtor  | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 18     | 75%     |
| SSD  | 4         | 7      | 16.67%  |
| NVMe | 2         | 2      | 8.33%   |

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
| Works    | 82        | 150    | 52.23%  |
| Detected | 52        | 111    | 33.12%  |
| Malfunc  | 23        | 27     | 14.65%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 76        | 41.53%  |
| AMD                            | 39        | 21.31%  |
| Samsung Electronics            | 24        | 13.11%  |
| SanDisk                        | 9         | 4.92%   |
| SK hynix                       | 6         | 3.28%   |
| Phison Electronics             | 5         | 2.73%   |
| Marvell Technology Group       | 5         | 2.73%   |
| Kingston Technology Company    | 4         | 2.19%   |
| ASMedia Technology             | 3         | 1.64%   |
| Union Memory (Shenzhen)        | 2         | 1.09%   |
| Toshiba America Info Systems   | 2         | 1.09%   |
| Silicon Motion                 | 2         | 1.09%   |
| Solid State Storage Technology | 1         | 0.55%   |
| Nvidia                         | 1         | 0.55%   |
| Micron/Crucial Technology      | 1         | 0.55%   |
| Lite-On Technology             | 1         | 0.55%   |
| JMicron Technology             | 1         | 0.55%   |
| Broadcom / LSI                 | 1         | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 29        | 14.08%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 14        | 6.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 3.88%   |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 3.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 2.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 2.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6         | 2.91%   |
| SK hynix Non-Volatile memory controller                                        | 4         | 1.94%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 1.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.94%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 1.94%   |
| Phison E12 NVMe Controller                                                     | 4         | 1.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 1.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.94%   |
| AMD 300 Series Chipset SATA Controller                                         | 4         | 1.94%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 1.46%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.46%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 1.46%   |
| Intel SSD 660P Series                                                          | 3         | 1.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.46%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.46%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 1.46%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.46%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 0.97%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.97%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.97%   |
| Samsung Electronics SATA controller                                            | 2         | 0.97%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2         | 0.97%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 0.97%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.97%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 0.97%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.97%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 0.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 0.97%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 0.97%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.49%   |
| SK hynix Gold P31 SSD                                                          | 1         | 0.49%   |
| SK hynix BC511                                                                 | 1         | 0.49%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.49%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.49%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.49%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.49%   |
| SanDisk WD Black NVMe SSD                                                      | 1         | 0.49%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.49%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.49%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 1         | 0.49%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.49%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1         | 0.49%   |
| Marvell Group 88SE912x IDE Controller                                          | 1         | 0.49%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 1         | 0.49%   |
| Lite-On Non-Volatile memory controller                                         | 1         | 0.49%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 0.49%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1         | 0.49%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 0.49%   |
| Intel SSD 600P Series                                                          | 1         | 0.49%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.49%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 106       | 58.89%  |
| NVMe | 56        | 31.11%  |
| RAID | 9         | 5%      |
| IDE  | 8         | 4.44%   |
| SAS  | 1         | 0.56%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 92        | 68.15%  |
| AMD    | 43        | 31.85%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor         | 4         | 2.94%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 4         | 2.94%   |
| AMD FX-8350 Eight-Core Processor            | 4         | 2.94%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 2         | 1.47%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2         | 1.47%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.47%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 1.47%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 1.47%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.47%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 1.47%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.47%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2         | 1.47%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 1.47%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 2         | 1.47%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.47%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.47%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 1.47%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.47%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2         | 1.47%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.47%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2         | 1.47%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz        | 1         | 0.74%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.74%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.74%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.74%   |
| Intel Pentium CPU A1018 @ 2.10GHz           | 1         | 0.74%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 0.74%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz            | 1         | 0.74%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.74%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 1         | 0.74%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 0.74%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1         | 0.74%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.74%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.74%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.74%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.74%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.74%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.74%   |
| Intel Core i7-2860QM CPU @ 2.50GHz          | 1         | 0.74%   |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 0.74%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 0.74%   |
| Intel Core i7-10850H CPU @ 2.70GHz          | 1         | 0.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.74%   |
| Intel Core i7 CPU 970 @ 3.20GHz             | 1         | 0.74%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1         | 0.74%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 0.74%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 1         | 0.74%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 0.74%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 0.74%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.74%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1         | 0.74%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 0.74%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1         | 0.74%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 0.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 0.74%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 0.74%   |
| Intel Core i5-4258U CPU @ 2.40GHz           | 1         | 0.74%   |
| Intel Core i5-3360M CPU @ 2.80GHz           | 1         | 0.74%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1         | 0.74%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 24.44%  |
| Intel Core i7           | 22        | 16.3%   |
| AMD Ryzen 7             | 13        | 9.63%   |
| AMD Ryzen 5             | 11        | 8.15%   |
| Intel Core i3           | 10        | 7.41%   |
| Intel Celeron           | 8         | 5.93%   |
| AMD Ryzen 9             | 5         | 3.7%    |
| AMD FX                  | 5         | 3.7%    |
| Other                   | 4         | 2.96%   |
| AMD Ryzen 3             | 4         | 2.96%   |
| Intel Pentium           | 3         | 2.22%   |
| Intel Core m3           | 3         | 2.22%   |
| Intel Core 2 Duo        | 3         | 2.22%   |
| Intel Core i9           | 2         | 1.48%   |
| Intel Xeon              | 1         | 0.74%   |
| Intel Pentium Silver    | 1         | 0.74%   |
| Intel Pentium Dual-Core | 1         | 0.74%   |
| Intel Atom              | 1         | 0.74%   |
| AMD Ryzen Threadripper  | 1         | 0.74%   |
| AMD Ryzen 5 PRO         | 1         | 0.74%   |
| AMD Phenom II X4        | 1         | 0.74%   |
| AMD A6                  | 1         | 0.74%   |
| AMD A10                 | 1         | 0.74%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 48        | 35.56%  |
| 4      | 44        | 32.59%  |
| 8      | 18        | 13.33%  |
| 6      | 17        | 12.59%  |
| 12     | 5         | 3.7%    |
| 3      | 2         | 1.48%   |
| 32     | 1         | 0.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 135       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 98        | 72.59%  |
| 1      | 37        | 27.41%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 135       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 25        | 17.86%  |
| 0x206a7    | 8         | 5.71%   |
| 0x306a9    | 7         | 5%      |
| 0x806e9    | 5         | 3.57%   |
| 0x08701013 | 5         | 3.57%   |
| 0x906ed    | 4         | 2.86%   |
| 0x906e9    | 4         | 2.86%   |
| 0x806ec    | 4         | 2.86%   |
| 0x806ea    | 4         | 2.86%   |
| 0x806c1    | 4         | 2.86%   |
| 0x706a1    | 4         | 2.86%   |
| 0x40651    | 4         | 2.86%   |
| 0x306d4    | 4         | 2.86%   |
| 0x08600106 | 4         | 2.86%   |
| 0xa0652    | 3         | 2.14%   |
| 0x706e5    | 3         | 2.14%   |
| 0x306c3    | 3         | 2.14%   |
| 0x1067a    | 3         | 2.14%   |
| 0x08701021 | 3         | 2.14%   |
| 0x0800820d | 3         | 2.14%   |
| 0x06000822 | 3         | 2.14%   |
| 0x906ea    | 2         | 1.43%   |
| 0x506e3    | 2         | 1.43%   |
| 0x30678    | 2         | 1.43%   |
| 0x08600103 | 2         | 1.43%   |
| 0x06000852 | 2         | 1.43%   |
| 0xa0655    | 1         | 0.71%   |
| 0xa0653    | 1         | 0.71%   |
| 0x806eb    | 1         | 0.71%   |
| 0x6fd      | 1         | 0.71%   |
| 0x506c9    | 1         | 0.71%   |
| 0x406e3    | 1         | 0.71%   |
| 0x206c2    | 1         | 0.71%   |
| 0x20655    | 1         | 0.71%   |
| 0x20652    | 1         | 0.71%   |
| 0x0a50000b | 1         | 0.71%   |
| 0x0a201016 | 1         | 0.71%   |
| 0x0a201009 | 1         | 0.71%   |
| 0x08608103 | 1         | 0.71%   |
| 0x08600104 | 1         | 0.71%   |
| 0x08108102 | 1         | 0.71%   |
| 0x0810100b | 1         | 0.71%   |
| 0x08101007 | 1         | 0.71%   |
| 0x0800820b | 1         | 0.71%   |
| 0x08001138 | 1         | 0.71%   |
| 0x08001137 | 1         | 0.71%   |
| 0x08001129 | 1         | 0.71%   |
| 0x0700010b | 1         | 0.71%   |
| 0x06003106 | 1         | 0.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 31        | 22.96%  |
| Zen 2         | 17        | 12.59%  |
| SandyBridge   | 9         | 6.67%   |
| IvyBridge     | 8         | 5.93%   |
| Haswell       | 8         | 5.93%   |
| Zen+          | 7         | 5.19%   |
| Zen           | 6         | 4.44%   |
| CometLake     | 6         | 4.44%   |
| Piledriver    | 5         | 3.7%    |
| Broadwell     | 5         | 3.7%    |
| Zen 3         | 4         | 2.96%   |
| TigerLake     | 4         | 2.96%   |
| Goldmont plus | 4         | 2.96%   |
| Westmere      | 3         | 2.22%   |
| Skylake       | 3         | 2.22%   |
| Penryn        | 3         | 2.22%   |
| IceLake       | 3         | 2.22%   |
| Silvermont    | 2         | 1.48%   |
| Steamroller   | 1         | 0.74%   |
| K10           | 1         | 0.74%   |
| Jaguar        | 1         | 0.74%   |
| Goldmont      | 1         | 0.74%   |
| Core          | 1         | 0.74%   |
| Bonnell       | 1         | 0.74%   |
| Unknown       | 1         | 0.74%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 72        | 45.57%  |
| AMD    | 46        | 29.11%  |
| Nvidia | 40        | 25.32%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 9         | 5.63%   |
| AMD Renoir                                                                | 7         | 4.38%   |
| Intel HD Graphics 620                                                     | 6         | 3.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 5         | 3.13%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 3.13%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 5         | 3.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 2.5%    |
| Intel UHD Graphics 620                                                    | 4         | 2.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 2.5%    |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 4         | 2.5%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 4         | 2.5%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 1.88%   |
| Intel HD Graphics 5500                                                    | 3         | 1.88%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 1.88%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.25%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 2         | 1.25%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 2         | 1.25%   |
| Nvidia GM206 [GeForce GTX 950]                                            | 2         | 1.25%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 1.25%   |
| Intel UHD Graphics 615                                                    | 2         | 1.25%   |
| Intel HD Graphics 630                                                     | 2         | 1.25%   |
| Intel HD Graphics 6000                                                    | 2         | 1.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 1.25%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                    | 2         | 1.25%   |
| AMD Saturn XT [FirePro M6100]                                             | 2         | 1.25%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.25%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.25%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                | 2         | 1.25%   |
| AMD Cezanne                                                               | 2         | 1.25%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                            | 2         | 1.25%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.63%   |
| Nvidia TU117M                                                             | 1         | 0.63%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1         | 0.63%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.63%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                    | 1         | 0.63%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                    | 1         | 0.63%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                     | 1         | 0.63%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                     | 1         | 0.63%   |
| Nvidia GT218M [GeForce 310M]                                              | 1         | 0.63%   |
| Nvidia GT218 [GeForce 210]                                                | 1         | 0.63%   |
| Nvidia GP108M [GeForce MX330]                                             | 1         | 0.63%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.63%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 1         | 0.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                       | 1         | 0.63%   |
| Nvidia GP104BM [GeForce GTX 1080 Mobile]                                  | 1         | 0.63%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                        | 1         | 0.63%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                         | 1         | 0.63%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                     | 1         | 0.63%   |
| Nvidia GM107 [GeForce 940MX]                                              | 1         | 0.63%   |
| Nvidia GK208B [GeForce GT 710]                                            | 1         | 0.63%   |
| Nvidia GK107M [GeForce GT 650M]                                           | 1         | 0.63%   |
| Nvidia GF119M [GeForce GT 520MX]                                          | 1         | 0.63%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                         | 1         | 0.63%   |
| Nvidia GF108M [GeForce GT 520M]                                           | 1         | 0.63%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 1         | 0.63%   |
| Nvidia GF108 [GeForce GT 630]                                             | 1         | 0.63%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                            | 1         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 53        | 38.69%  |
| 1 x AMD        | 39        | 28.47%  |
| 1 x Nvidia     | 22        | 16.06%  |
| Intel + Nvidia | 15        | 10.95%  |
| Intel + AMD    | 3         | 2.19%   |
| AMD + Nvidia   | 3         | 2.19%   |
| 2 x AMD        | 2         | 1.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 109       | 79.56%  |
| Proprietary | 28        | 20.44%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 74        | 52.48%  |
| 1.01-2.0   | 16        | 11.35%  |
| 7.01-8.0   | 15        | 10.64%  |
| 3.01-4.0   | 12        | 8.51%   |
| 0.01-0.5   | 10        | 7.09%   |
| 0.51-1.0   | 8         | 5.67%   |
| 8.01-16.0  | 3         | 2.13%   |
| 5.01-6.0   | 2         | 1.42%   |
| 2.01-3.0   | 1         | 0.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 17        | 10.06%  |
| AU Optronics            | 17        | 10.06%  |
| Samsung Electronics     | 16        | 9.47%   |
| BOE                     | 16        | 9.47%   |
| Chimei Innolux          | 14        | 8.28%   |
| Acer                    | 10        | 5.92%   |
| Philips                 | 8         | 4.73%   |
| Goldstar                | 8         | 4.73%   |
| Dell                    | 8         | 4.73%   |
| BenQ                    | 7         | 4.14%   |
| AOC                     | 6         | 3.55%   |
| ASUSTek Computer        | 5         | 2.96%   |
| Chi Mei Optoelectronics | 4         | 2.37%   |
| InfoVision              | 3         | 1.78%   |
| Hewlett-Packard         | 3         | 1.78%   |
| Apple                   | 3         | 1.78%   |
| Ancor Communications    | 3         | 1.78%   |
| Sharp                   | 2         | 1.18%   |
| ViewSonic               | 1         | 0.59%   |
| Vestel Elektronik       | 1         | 0.59%   |
| PANDA                   | 1         | 0.59%   |
| Packard Bell            | 1         | 0.59%   |
| MSI                     | 1         | 0.59%   |
| LGD                     | 1         | 0.59%   |
| Lenovo                  | 1         | 0.59%   |
| KTC                     | 1         | 0.59%   |
| KDC                     | 1         | 0.59%   |
| Jean                    | 1         | 0.59%   |
| Iiyama                  | 1         | 0.59%   |
| Idek Iiyama             | 1         | 0.59%   |
| HVR                     | 1         | 0.59%   |
| Hitachi                 | 1         | 0.59%   |
| Envision Peripherals    | 1         | 0.59%   |
| Eizo                    | 1         | 0.59%   |
| CTV                     | 1         | 0.59%   |
| Compal                  | 1         | 0.59%   |
| Belinea                 | 1         | 0.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 1.73%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 1.16%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                   | 2         | 1.16%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch          | 2         | 1.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.16%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 1.16%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 1.16%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 1.16%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 1.16%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 1.16%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 621x341mm 27.9-inch              | 2         | 1.16%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 1.16%   |
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                             | 2         | 1.16%   |
| Ancor Communications ASUS PB277 ACI27B5 2560x1440 597x336mm 27.0-inch     | 2         | 1.16%   |
| ViewSonic LCD Monitor VX2452 Series 3840x1080                             | 1         | 0.58%   |
| Vestel Elektronik 28W_LCD_TV VES3700 1920x540                             | 1         | 0.58%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 0.58%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.58%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch         | 1         | 0.58%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 520x290mm 23.4-inch         | 1         | 0.58%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 0.58%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 340x190mm 15.3-inch         | 1         | 0.58%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 1         | 0.58%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 1         | 0.58%   |
| Samsung Electronics S24A31x SAM7114 1920x1080 527x296mm 23.8-inch         | 1         | 0.58%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch         | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch   | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1872x1053mm 84.6-inch   | 1         | 0.58%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch         | 1         | 0.58%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch         | 1         | 0.58%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch         | 1         | 0.58%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 1         | 0.58%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                  | 1         | 0.58%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                   | 1         | 0.58%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                   | 1         | 0.58%   |
| Philips PHL 220V8 PHLC218 1920x1080 477x268mm 21.5-inch                   | 1         | 0.58%   |
| Philips 247ELH PHLC085 1920x1080 521x293mm 23.5-inch                      | 1         | 0.58%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                       | 1         | 0.58%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                   | 1         | 0.58%   |
| Packard Bell Viseo203DX PKB0378 1600x900 432x240mm 19.5-inch              | 1         | 0.58%   |
| MSI Optix MAG27C MSI1462 1920x1080 598x336mm 27.0-inch                    | 1         | 0.58%   |
| LGD LCD Monitor 1920x1080                                                 | 1         | 0.58%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch               | 1         | 0.58%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 1         | 0.58%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch              | 1         | 0.58%   |
| LG Display LCD Monitor LGD05F8 2560x1600 366x229mm 17.0-inch              | 1         | 0.58%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch              | 1         | 0.58%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch              | 1         | 0.58%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 1         | 0.58%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch              | 1         | 0.58%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch              | 1         | 0.58%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch              | 1         | 0.58%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch               | 1         | 0.58%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch               | 1         | 0.58%   |
| LG Display LCD Monitor LGD03D3 1600x900 309x174mm 14.0-inch               | 1         | 0.58%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch               | 1         | 0.58%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch               | 1         | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 78        | 48.75%  |
| 1366x768 (WXGA)    | 30        | 18.75%  |
| 3840x2160 (4K)     | 15        | 9.38%   |
| 2560x1440 (QHD)    | 8         | 5%      |
| 1600x900 (HD+)     | 4         | 2.5%    |
| 1440x900 (WXGA+)   | 4         | 2.5%    |
| 3440x1440          | 2         | 1.25%   |
| 2560x1600          | 2         | 1.25%   |
| 2560x1080          | 2         | 1.25%   |
| 1920x1200 (WUXGA)  | 2         | 1.25%   |
| 1680x1050 (WSXGA+) | 2         | 1.25%   |
| 1280x1024 (SXGA)   | 2         | 1.25%   |
| Unknown            | 2         | 1.25%   |
| 3840x1080          | 1         | 0.63%   |
| 3600x1080          | 1         | 0.63%   |
| 2736x1824          | 1         | 0.63%   |
| 2160x1440          | 1         | 0.63%   |
| 2160x1200          | 1         | 0.63%   |
| 1280x960           | 1         | 0.63%   |
| 1024x768 (XGA)     | 1         | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 40        | 24.24%  |
| 13      | 19        | 11.52%  |
| 24      | 16        | 9.7%    |
| 27      | 14        | 8.48%   |
| 23      | 14        | 8.48%   |
| 14      | 14        | 8.48%   |
| 21      | 11        | 6.67%   |
| 17      | 7         | 4.24%   |
| Unknown | 5         | 3.03%   |
| 84      | 4         | 2.42%   |
| 34      | 4         | 2.42%   |
| 19      | 4         | 2.42%   |
| 31      | 3         | 1.82%   |
| 32      | 2         | 1.21%   |
| 20      | 2         | 1.21%   |
| 12      | 2         | 1.21%   |
| 11      | 2         | 1.21%   |
| 52      | 1         | 0.61%   |
| 16      | 1         | 0.61%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 66        | 40.49%  |
| 501-600     | 39        | 23.93%  |
| 401-500     | 14        | 8.59%   |
| 351-400     | 12        | 7.36%   |
| 201-300     | 10        | 6.13%   |
| 701-800     | 6         | 3.68%   |
| 601-700     | 6         | 3.68%   |
| Unknown     | 5         | 3.07%   |
| 1501-2000   | 4         | 2.45%   |
| 1001-1500   | 1         | 0.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 117       | 81.82%  |
| 16/10   | 11        | 7.69%   |
| 21/9    | 4         | 2.8%    |
| Unknown | 4         | 2.8%    |
| 5/4     | 3         | 2.1%    |
| 4/3     | 2         | 1.4%    |
| 3/2     | 2         | 1.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 40        | 24.24%  |
| 201-250        | 37        | 22.42%  |
| 81-90          | 27        | 16.36%  |
| 301-350        | 14        | 8.48%   |
| 351-500        | 9         | 5.45%   |
| 71-80          | 7         | 4.24%   |
| 151-200        | 7         | 4.24%   |
| 121-130        | 6         | 3.64%   |
| More than 1000 | 5         | 3.03%   |
| Unknown        | 5         | 3.03%   |
| 251-300        | 3         | 1.82%   |
| 51-60          | 2         | 1.21%   |
| 131-140        | 2         | 1.21%   |
| 61-70          | 1         | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 55        | 34.81%  |
| 51-100        | 48        | 30.38%  |
| 101-120       | 40        | 25.32%  |
| 161-240       | 8         | 5.06%   |
| Unknown       | 5         | 3.16%   |
| More than 240 | 1         | 0.63%   |
| 1-50          | 1         | 0.63%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 107       | 77.54%  |
| 2     | 27        | 19.57%  |
| 3     | 3         | 2.17%   |
| 4     | 1         | 0.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 86        | 41.35%  |
| Intel                                 | 67        | 32.21%  |
| Qualcomm Atheros                      | 20        | 9.62%   |
| Broadcom                              | 8         | 3.85%   |
| Broadcom Limited                      | 4         | 1.92%   |
| D-Link System                         | 3         | 1.44%   |
| Xiaomi                                | 2         | 0.96%   |
| Ralink Technology                     | 2         | 0.96%   |
| Ralink                                | 2         | 0.96%   |
| TP-Link                               | 1         | 0.48%   |
| Sierra Wireless                       | 1         | 0.48%   |
| Qualcomm Atheros Communications       | 1         | 0.48%   |
| Qualcomm                              | 1         | 0.48%   |
| OPPO Electronics                      | 1         | 0.48%   |
| Microsoft                             | 1         | 0.48%   |
| Marvell Technology Group              | 1         | 0.48%   |
| Linksys                               | 1         | 0.48%   |
| Huawei Technologies                   | 1         | 0.48%   |
| Google                                | 1         | 0.48%   |
| DisplayLink                           | 1         | 0.48%   |
| Aquantia                              | 1         | 0.48%   |
| Apple                                 | 1         | 0.48%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59        | 23.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 4.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 3.17%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.38%   |
| Intel Wireless 8265 / 8275                                        | 6         | 2.38%   |
| Intel I211 Gigabit Network Connection                             | 6         | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.98%   |
| Intel Wireless 7265                                               | 5         | 1.98%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 1.98%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.19%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.19%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.19%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 1.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 1.19%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.19%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.79%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.79%   |
| Realtek 802.11ac NIC                                              | 2         | 0.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.79%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.79%   |
| Intel Wireless-AC 9260                                            | 2         | 0.79%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.79%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.79%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 0.79%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 0.79%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.4%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.4%    |
| Sierra Wireless MC7710                                            | 1         | 0.4%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.4%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.4%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.4%    |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.4%    |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.4%    |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.4%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.4%    |
| Ralink RT2561/RT61 802.11g PCI                                    | 1         | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.4%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.4%    |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 0.4%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.4%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.4%    |
| Qualcomm A0001                                                    | 1         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 52        | 44.83%  |
| Realtek Semiconductor                 | 25        | 21.55%  |
| Qualcomm Atheros                      | 17        | 14.66%  |
| Broadcom                              | 7         | 6.03%   |
| Broadcom Limited                      | 4         | 3.45%   |
| Ralink Technology                     | 2         | 1.72%   |
| Ralink                                | 2         | 1.72%   |
| TP-Link                               | 1         | 0.86%   |
| Sierra Wireless                       | 1         | 0.86%   |
| Qualcomm Atheros Communications       | 1         | 0.86%   |
| Microsoft                             | 1         | 0.86%   |
| Marvell Technology Group              | 1         | 0.86%   |
| D-Link System                         | 1         | 0.86%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                               | Computers | Percent |
|-----------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                                 | 7         | 5.98%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                            | 6         | 5.13%   |
| Intel Wireless 8265 / 8275                                                                          | 6         | 5.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                            | 5         | 4.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                          | 5         | 4.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                    | 5         | 4.27%   |
| Intel Wireless 7265                                                                                 | 5         | 4.27%   |
| Intel Comet Lake PCH CNVi WiFi                                                                      | 5         | 4.27%   |
| Intel Wi-Fi 6 AX201                                                                                 | 3         | 2.56%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                        | 3         | 2.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                            | 3         | 2.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                     | 3         | 2.56%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                          | 3         | 2.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                                 | 3         | 2.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                     | 2         | 1.71%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                            | 2         | 1.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                                     | 2         | 1.71%   |
| Realtek RTL8188EE Wireless Network Adapter                                                          | 2         | 1.71%   |
| Realtek 802.11ac NIC                                                                                | 2         | 1.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                          | 2         | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                          | 2         | 1.71%   |
| Intel Wireless-AC 9260                                                                              | 2         | 1.71%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                                     | 2         | 1.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                   | 2         | 1.71%   |
| Broadcom BCM43228 802.11a/b/g/n                                                                     | 2         | 1.71%   |
| Broadcom BCM43142 802.11b/g/n                                                                       | 2         | 1.71%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                         | 1         | 0.85%   |
| Sierra Wireless MC7710                                                                              | 1         | 0.85%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                            | 1         | 0.85%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                                     | 1         | 0.85%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                             | 1         | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                          | 1         | 0.85%   |
| Realtek 802.11n WLAN Adapter                                                                        | 1         | 0.85%   |
| Ralink RT5370 Wireless Adapter                                                                      | 1         | 0.85%   |
| Ralink MT7601U Wireless Adapter                                                                     | 1         | 0.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                           | 1         | 0.85%   |
| Ralink RT2561/RT61 802.11g PCI                                                                      | 1         | 0.85%   |
| Qualcomm Atheros AR9271 802.11n                                                                     | 1         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                    | 1         | 0.85%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                      | 1         | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                      | 1         | 0.85%   |
| Microsoft XBOX ACC                                                                                  | 1         | 0.85%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                                   | 1         | 0.85%   |
| Intel Wireless 8260                                                                                 | 1         | 0.85%   |
| Intel Wireless 7260                                                                                 | 1         | 0.85%   |
| Intel Wireless 3165                                                                                 | 1         | 0.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                              | 1         | 0.85%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                             | 1         | 0.85%   |
| Intel Gemini Lake PCH CNVi WiFi                                                                     | 1         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                    | 1         | 0.85%   |
| Intel Centrino Wireless-N 2230                                                                      | 1         | 0.85%   |
| Intel Centrino Ultimate-N 6300                                                                      | 1         | 0.85%   |
| Intel Centrino Advanced-N 6235                                                                      | 1         | 0.85%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                                                | 1         | 0.85%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104]         | 1         | 0.85%   |
| Broadcom Limited BCM43142 802.11b/g/n                                                               | 1         | 0.85%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB100 v2 RangePlus Wireless Network Adapter [Ralink RT3070] | 1         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 77        | 60.16%  |
| Intel                 | 33        | 25.78%  |
| Qualcomm Atheros      | 6         | 4.69%   |
| Xiaomi                | 2         | 1.56%   |
| D-Link System         | 2         | 1.56%   |
| Qualcomm              | 1         | 0.78%   |
| OPPO Electronics      | 1         | 0.78%   |
| Linksys               | 1         | 0.78%   |
| Huawei Technologies   | 1         | 0.78%   |
| DisplayLink           | 1         | 0.78%   |
| Broadcom              | 1         | 0.78%   |
| Aquantia              | 1         | 0.78%   |
| Apple                 | 1         | 0.78%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 59        | 44.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 8.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 5.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 5.22%   |
| Intel I211 Gigabit Network Connection                             | 6         | 4.48%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.24%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.24%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 2.24%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.49%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.49%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 1.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.75%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.75%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.75%   |
| Qualcomm A0001                                                    | 1         | 0.75%   |
| OPPO Find X2 Lite                                                 | 1         | 0.75%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.75%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.75%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.75%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.75%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.75%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.75%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.75%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.75%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.75%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.75%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.75%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1         | 0.75%   |
| Intel 82562V-2 10/100 Network Connection                          | 1         | 0.75%   |
| Huawei E353/E3131                                                 | 1         | 0.75%   |
| DisplayLink Kensington Dock (Composite Device)                    | 1         | 0.75%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.75%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.75%   |
| Apple iPad 4/Mini1                                                | 1         | 0.75%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 116       | 50.88%  |
| WiFi     | 111       | 48.68%  |
| Modem    | 1         | 0.44%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 82        | 59.85%  |
| Ethernet | 55        | 40.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 82        | 60.29%  |
| 1     | 49        | 36.03%  |
| 4     | 2         | 1.47%   |
| 3     | 2         | 1.47%   |
| 0     | 1         | 0.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 123       | 88.49%  |
| Yes  | 16        | 11.51%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 48.89%  |
| Realtek Semiconductor           | 12        | 13.33%  |
| Broadcom                        | 6         | 6.67%   |
| Qualcomm Atheros Communications | 5         | 5.56%   |
| Lite-On Technology              | 4         | 4.44%   |
| IMC Networks                    | 4         | 4.44%   |
| Cambridge Silicon Radio         | 3         | 3.33%   |
| Apple                           | 3         | 3.33%   |
| Realtek                         | 2         | 2.22%   |
| Foxconn / Hon Hai               | 2         | 2.22%   |
| ASUSTek Computer                | 2         | 2.22%   |
| Ralink                          | 1         | 1.11%   |
| Marvell Semiconductor           | 1         | 1.11%   |
| HTC (High Tech Computer)        | 1         | 1.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 13        | 14.44%  |
| Intel Bluetooth Device                                               | 11        | 12.22%  |
| Realtek Bluetooth Radio                                              | 8         | 8.89%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 8         | 8.89%   |
| Intel AX200 Bluetooth                                                | 7         | 7.78%   |
| Qualcomm Atheros  Bluetooth Device                                   | 4         | 4.44%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 3         | 3.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 3         | 3.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 3         | 3.33%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3         | 3.33%   |
| Realtek Bluetooth Radio                                              | 2         | 2.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2         | 2.22%   |
| IMC Networks Bluetooth Radio                                         | 2         | 2.22%   |
| IMC Networks Bluetooth Device                                        | 2         | 2.22%   |
| Foxconn / Hon Hai BCM20702A0                                         | 2         | 2.22%   |
| Apple Bluetooth USB Host Controller                                  | 2         | 2.22%   |
| Realtek RTL8821A Bluetooth                                           | 1         | 1.11%   |
| Ralink RT3290 Bluetooth                                              | 1         | 1.11%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 1.11%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 1         | 1.11%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                         | 1         | 1.11%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 1         | 1.11%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1         | 1.11%   |
| Intel AX210 Bluetooth                                                | 1         | 1.11%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 1.11%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1         | 1.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 1         | 1.11%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 1         | 1.11%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1         | 1.11%   |
| ASUS Bluetooth Radio                                                 | 1         | 1.11%   |
| Apple Bluetooth Host Controller                                      | 1         | 1.11%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 90        | 43.9%   |
| AMD                                             | 52        | 25.37%  |
| Nvidia                                          | 32        | 15.61%  |
| C-Media Electronics                             | 9         | 4.39%   |
| Realtek Semiconductor                           | 4         | 1.95%   |
| Creative Labs                                   | 3         | 1.46%   |
| Logitech                                        | 2         | 0.98%   |
| Creative Technology                             | 2         | 0.98%   |
| Corsair                                         | 2         | 0.98%   |
| TC Electronic                                   | 1         | 0.49%   |
| SteelSeries ApS                                 | 1         | 0.49%   |
| Razer USA                                       | 1         | 0.49%   |
| Plantronics                                     | 1         | 0.49%   |
| Native Instruments                              | 1         | 0.49%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.49%   |
| Generalplus Technology                          | 1         | 0.49%   |
| Focusrite-Novation                              | 1         | 0.49%   |
| AudioQuest                                      | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 5.95%   |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 5.56%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11        | 4.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 3.57%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 3.57%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9         | 3.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 3.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8         | 3.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 2.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.98%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 1.98%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1.98%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.98%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 1.98%   |
| AMD Navi 10 HDMI Audio                                                     | 5         | 1.98%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.59%   |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 1.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 1.59%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.59%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.59%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.59%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.59%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4         | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.59%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 1.59%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.19%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.19%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.19%   |
| C-Media Electronics USB Audio Device                                       | 3         | 1.19%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.79%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.79%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.79%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.79%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.79%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 0.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 0.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 0.79%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                     | 2         | 0.79%   |
| Corsair HS45 Surround USB Sound Adapter                                    | 2         | 0.79%   |
| AMD Tobago HDMI Audio [Radeon R7 360 / R9 360 OEM]                         | 2         | 0.79%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 0.79%   |
| AMD FCH Azalia Controller                                                  | 2         | 0.79%   |
| TC Electronic VoiceLive Play                                               | 1         | 0.4%    |
| SteelSeries ApS Arctis Pro Wireless                                        | 1         | 0.4%    |
| Realtek Semiconductor Realtek USB2.0 Audio                                 | 1         | 0.4%    |
| Realtek Semiconductor Realtek Audio USB                                    | 1         | 0.4%    |
| Razer USA RZ19-0229 Gaming Microphone                                      | 1         | 0.4%    |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.4%    |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.4%    |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.4%    |
| Nvidia GM200 High Definition Audio                                         | 1         | 0.4%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.4%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.4%    |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 21.99%  |
| SK hynix            | 29        | 20.57%  |
| Kingston            | 16        | 11.35%  |
| Corsair             | 13        | 9.22%   |
| G.Skill             | 9         | 6.38%   |
| Micron Technology   | 8         | 5.67%   |
| Unknown             | 7         | 4.96%   |
| Crucial             | 5         | 3.55%   |
| A-DATA Technology   | 4         | 2.84%   |
| Silicon Power       | 3         | 2.13%   |
| Patriot             | 3         | 2.13%   |
| Unknown (ABCD)      | 2         | 1.42%   |
| Ramaxel Technology  | 2         | 1.42%   |
| Unknown             | 2         | 1.42%   |
| Transcend           | 1         | 0.71%   |
| Team                | 1         | 0.71%   |
| Smart Brazil        | 1         | 0.71%   |
| Smart               | 1         | 0.71%   |
| Nanya Technology    | 1         | 0.71%   |
| ASint Technology    | 1         | 0.71%   |
| AMD                 | 1         | 0.71%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 4         | 2.68%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 2.01%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 2.01%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s             | 3         | 2.01%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 1.34%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.34%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 1.34%   |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 1.34%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 2         | 1.34%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 2         | 1.34%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s         | 2         | 1.34%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s                 | 2         | 1.34%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 2         | 1.34%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 1.34%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 2         | 1.34%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 2         | 1.34%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s           | 2         | 1.34%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.34%   |
| G.Skill RAM F3-10666CL9-4GBNT 4096MB DIMM DDR3 1400MT/s             | 2         | 1.34%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s            | 2         | 1.34%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s               | 2         | 1.34%   |
| Unknown                                                             | 2         | 1.34%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.67%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                         | 1         | 0.67%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 1         | 0.67%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 1         | 0.67%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 1         | 0.67%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                             | 1         | 0.67%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                    | 1         | 0.67%   |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s                 | 1         | 0.67%   |
| Team RAM TEAMGROUP-SD3-1600 4GB SODIMM DDR3 1600MT/s                | 1         | 0.67%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2400MT/s               | 1         | 0.67%   |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 2933MT/s     | 1         | 0.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.67%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.67%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.67%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.67%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.67%   |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.67%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s           | 1         | 0.67%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB Row Of Chips DDR4 3200MT/s     | 1         | 0.67%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 0.67%   |
| SK hynix RAM HMA82GU7CJR8N-VK 16GB DIMM DDR4 2667MT/s               | 1         | 0.67%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.67%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.67%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.67%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s              | 1         | 0.67%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8192MB DIMM DDR4 2465MT/s             | 1         | 0.67%   |
| SK hynix RAM HCNNNBKMBLHR-NEE 1GB Row Of Chips LPDDR4 4267MT/s      | 1         | 0.67%   |
| Silicon Power RAM SP016GBSFU266B02 16GB SODIMM DDR4 2667MT/s        | 1         | 0.67%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 1         | 0.67%   |
| Samsung RAM M471B5273DM0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.67%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.67%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 1         | 0.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 1         | 0.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 0.67%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s           | 1         | 0.67%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 0.67%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 0.67%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 1         | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 66        | 55.93%  |
| DDR3    | 38        | 32.2%   |
| LPDDR4  | 4         | 3.39%   |
| SDRAM   | 3         | 2.54%   |
| LPDDR3  | 3         | 2.54%   |
| Unknown | 3         | 2.54%   |
| DDR2    | 1         | 0.85%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 67        | 56.3%   |
| DIMM         | 41        | 34.45%  |
| Row Of Chips | 9         | 7.56%   |
| Chip         | 1         | 0.84%   |
| Unknown      | 1         | 0.84%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 49        | 37.4%   |
| 8192  | 44        | 33.59%  |
| 16384 | 20        | 15.27%  |
| 2048  | 13        | 9.92%   |
| 32768 | 3         | 2.29%   |
| 1024  | 2         | 1.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 33        | 25.78%  |
| 3200    | 24        | 18.75%  |
| 2667    | 18        | 14.06%  |
| 2400    | 13        | 10.16%  |
| 1333    | 8         | 6.25%   |
| 2133    | 5         | 3.91%   |
| 3600    | 4         | 3.13%   |
| 3533    | 3         | 2.34%   |
| 2933    | 3         | 2.34%   |
| 4199    | 2         | 1.56%   |
| 3266    | 2         | 1.56%   |
| 1400    | 2         | 1.56%   |
| 4267    | 1         | 0.78%   |
| 4133    | 1         | 0.78%   |
| 3466    | 1         | 0.78%   |
| 3400    | 1         | 0.78%   |
| 2481    | 1         | 0.78%   |
| 2465    | 1         | 0.78%   |
| 1334    | 1         | 0.78%   |
| 1328    | 1         | 0.78%   |
| 1066    | 1         | 0.78%   |
| 800     | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Ricoh              | 1         | 33.33%  |
| Hewlett-Packard    | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Ricoh SP 212SUw               | 1         | 33.33%  |
| HP Officejet Pro L7400        | 1         | 33.33%  |
| Brother HL-2030 Laser Printer | 1         | 33.33%  |

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
| Chicony Electronics                    | 18        | 20.45%  |
| Acer                                   | 10        | 11.36%  |
| Realtek Semiconductor                  | 9         | 10.23%  |
| Quanta                                 | 7         | 7.95%   |
| IMC Networks                           | 6         | 6.82%   |
| Suyin                                  | 5         | 5.68%   |
| Syntek                                 | 4         | 4.55%   |
| Sunplus Innovation Technology          | 4         | 4.55%   |
| Logitech                               | 4         | 4.55%   |
| Alcor Micro                            | 4         | 4.55%   |
| Silicon Motion                         | 2         | 2.27%   |
| Microdia                               | 2         | 2.27%   |
| Luxvisions Innotech Limited            | 2         | 2.27%   |
| Creative Technology                    | 2         | 2.27%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.27%   |
| Microsoft                              | 1         | 1.14%   |
| Lite-On Technology                     | 1         | 1.14%   |
| LG Electronics                         | 1         | 1.14%   |
| Lenovo                                 | 1         | 1.14%   |
| KYE Systems (Mouse Systems)            | 1         | 1.14%   |
| GEMBIRD                                | 1         | 1.14%   |
| ARC International                      | 1         | 1.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                                 | 5         | 5.68%   |
| Chicony HD Webcam                                              | 5         | 5.68%   |
| Realtek Integrated_Webcam_HD                                   | 4         | 4.55%   |
| Chicony Integrated Camera                                      | 4         | 4.55%   |
| Acer Integrated Camera                                         | 4         | 4.55%   |
| Syntek Integrated Camera                                       | 2         | 2.27%   |
| Syntek EasyCamera                                              | 2         | 2.27%   |
| Suyin HP Webcam                                                | 2         | 2.27%   |
| Silicon Motion 300k Pixel Camera                               | 2         | 2.27%   |
| Realtek USB2.0 HD UVC WebCam                                   | 2         | 2.27%   |
| Realtek HD WebCam                                              | 2         | 2.27%   |
| Quanta HP Webcam                                               | 2         | 2.27%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 2.27%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 2         | 2.27%   |
| Chicony Integrated Camera (1280x720@30)                        | 2         | 2.27%   |
| Alcor Micro USB 2.0 Camera                                     | 2         | 2.27%   |
| Suyin USB Webcam                                               | 1         | 1.14%   |
| Suyin NEC HD WebCam                                            | 1         | 1.14%   |
| Suyin 1.3M HD WebCam                                           | 1         | 1.14%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 1.14%   |
| Sunplus Integrated_Webcam_HD                                   | 1         | 1.14%   |
| Sunplus HD WebCam                                              | 1         | 1.14%   |
| Sunplus Aukey-PC-LM1E Camera                                   | 1         | 1.14%   |
| Realtek Integrated Webcam                                      | 1         | 1.14%   |
| Quanta VGA WebCam                                              | 1         | 1.14%   |
| Quanta USB2.0 VGA UVC WebCam                                   | 1         | 1.14%   |
| Quanta HD User Facing                                          | 1         | 1.14%   |
| Microsoft LifeCam Cinema                                       | 1         | 1.14%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 1.14%   |
| Microdia Integrated Webcam                                     | 1         | 1.14%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 1.14%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 1.14%   |
| Logitech Webcam C930e                                          | 1         | 1.14%   |
| Logitech Webcam C310                                           | 1         | 1.14%   |
| Logitech Webcam C270                                           | 1         | 1.14%   |
| Logitech HD Webcam C910                                        | 1         | 1.14%   |
| Lite-On HP HD Camera                                           | 1         | 1.14%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)          | 1         | 1.14%   |
| Lenovo UVC Camera                                              | 1         | 1.14%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320                 | 1         | 1.14%   |
| IMC Networks Integrated Webcam                                 | 1         | 1.14%   |
| GEMBIRD USB2.0 PC CAMERA                                       | 1         | 1.14%   |
| Creative Live! Cam Sync HD [VF0770]                            | 1         | 1.14%   |
| Creative Live! Cam Chat HD [VF0700]                            | 1         | 1.14%   |
| Chicony USB2.0 Camera                                          | 1         | 1.14%   |
| Chicony USB2.0 0.3M UVC WebCam                                 | 1         | 1.14%   |
| Chicony Thinkpad T430 camera                                   | 1         | 1.14%   |
| Chicony LG Camera                                              | 1         | 1.14%   |
| Chicony Lenovo EasyCamera                                      | 1         | 1.14%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 1         | 1.14%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.14%   |
| ARC International Camera                                       | 1         | 1.14%   |
| Alcor Micro Lenovo EasyCamera                                  | 1         | 1.14%   |
| Alcor Micro Asus Integrated Webcam                             | 1         | 1.14%   |
| Acer Lenovo Integrated Webcam                                  | 1         | 1.14%   |
| Acer Lenovo EasyCamera                                         | 1         | 1.14%   |
| Acer Integrated 5M Camera                                      | 1         | 1.14%   |
| Acer HD Webcam                                                 | 1         | 1.14%   |
| Acer BisonCam,NB Pro                                           | 1         | 1.14%   |
| Acer BisonCam, NB Pro                                          | 1         | 1.14%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 4         | 50%     |
| Synaptics                  | 3         | 37.5%   |
| AuthenTec                  | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 37.5%   |
| Shenzhen Goodix  FingerPrint Device               | 3         | 37.5%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 12.5%   |
| AuthenTec AES2810                                 | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 5         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
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


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 103       | 75.18%  |
| 1     | 29        | 21.17%  |
| 2     | 5         | 3.65%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 8         | 20.51%  |
| Net/wireless             | 5         | 12.82%  |
| Graphics card            | 5         | 12.82%  |
| Multimedia controller    | 4         | 10.26%  |
| Chipcard                 | 4         | 10.26%  |
| Camera                   | 4         | 10.26%  |
| Storage                  | 2         | 5.13%   |
| Communication controller | 2         | 5.13%   |
| Bluetooth                | 2         | 5.13%   |
| Unassigned class         | 1         | 2.56%   |
| Network                  | 1         | 2.56%   |
| Dvb card                 | 1         | 2.56%   |

