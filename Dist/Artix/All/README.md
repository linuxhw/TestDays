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

Total: 218

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Predator PH315-51           | Notebook    | [68f7384e7a](https://linux-hardware.org/?probe=68f7384e7a) | Sep 30, 2022 |
| Acer          | Aspire VN7-592G             | Notebook    | [cfc28181e5](https://linux-hardware.org/?probe=cfc28181e5) | Sep 25, 2022 |
| Notebook      | N141CU                      | Notebook    | [9a03ce91af](https://linux-hardware.org/?probe=9a03ce91af) | Sep 04, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [a37633e1e2](https://linux-hardware.org/?probe=a37633e1e2) | Aug 24, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [6b03bfc62e](https://linux-hardware.org/?probe=6b03bfc62e) | Aug 13, 2022 |
| MSI           | H410M PRO-VH                | Desktop     | [f632032d8c](https://linux-hardware.org/?probe=f632032d8c) | Aug 13, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [db843c1cae](https://linux-hardware.org/?probe=db843c1cae) | Aug 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [3025bd4ded](https://linux-hardware.org/?probe=3025bd4ded) | Aug 05, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [ab643dc6b0](https://linux-hardware.org/?probe=ab643dc6b0) | Jul 30, 2022 |
| Dell          | Latitude E7440              | Notebook    | [deea307e9b](https://linux-hardware.org/?probe=deea307e9b) | Jul 27, 2022 |
| Dell          | Latitude E7440              | Notebook    | [e2d8510882](https://linux-hardware.org/?probe=e2d8510882) | Jul 27, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [304f750248](https://linux-hardware.org/?probe=304f750248) | Jul 08, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [00d543ee46](https://linux-hardware.org/?probe=00d543ee46) | Jul 07, 2022 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [f07968d013](https://linux-hardware.org/?probe=f07968d013) | Jul 07, 2022 |
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
| Artix Rolling  | 94        | 61.04%  |
| Artix          | 53        | 34.42%  |
| Artix 20220123 | 2         | 1.3%    |
| Artix 20210726 | 2         | 1.3%    |
| Artix 20220713 | 1         | 0.65%   |
| Artix 20201207 | 1         | 0.65%   |
| Artix 20201128 | 1         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Artix | 147       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.9.14-artix1-1    | 8         | 4.55%   |
| 5.7.6-artix1-1     | 5         | 2.84%   |
| 5.7.12-artix1-1    | 4         | 2.27%   |
| 5.15.12-artix1-1   | 4         | 2.27%   |
| 5.12.12-artix1-1   | 4         | 2.27%   |
| 5.10.4-artix2-1    | 4         | 2.27%   |
| 5.8.8-artix1-1     | 3         | 1.7%    |
| 5.8.12-artix1-1    | 3         | 1.7%    |
| 5.18.16-artix1-1   | 3         | 1.7%    |
| 5.16.3-artix1-1    | 3         | 1.7%    |
| 5.16.10-artix1-1   | 3         | 1.7%    |
| 5.12.8-artix1-1    | 3         | 1.7%    |
| 5.12.14-artix1-1   | 3         | 1.7%    |
| 5.10.8-artix1-1    | 3         | 1.7%    |
| 5.10.6-artix1-1    | 3         | 1.7%    |
| 5.10.16-artix1-1   | 3         | 1.7%    |
| 5.9.14-zen1-1-zen  | 2         | 1.14%   |
| 5.9.12-artix1-1    | 2         | 1.14%   |
| 5.8.14-artix1-1    | 2         | 1.14%   |
| 5.7.2-artix1-1     | 2         | 1.14%   |
| 5.18.9-zen1-1-zen  | 2         | 1.14%   |
| 5.18.6-artix1-1    | 2         | 1.14%   |
| 5.18.0-artix1-1    | 2         | 1.14%   |
| 5.17.4-artix1-1    | 2         | 1.14%   |
| 5.17.1-artix1-1    | 2         | 1.14%   |
| 5.16.8-artix1-2    | 2         | 1.14%   |
| 5.16.1-artix1-1    | 2         | 1.14%   |
| 5.15.3-zen1-1-zen  | 2         | 1.14%   |
| 5.14.16-artix1-1   | 2         | 1.14%   |
| 5.13.8-artix1-1    | 2         | 1.14%   |
| 5.12.4-artix1-1    | 2         | 1.14%   |
| 5.12.12-zen1-1-zen | 2         | 1.14%   |
| 5.11.6-artix1-1    | 2         | 1.14%   |
| 5.11.10-artix1-1   | 2         | 1.14%   |
| 5.10.15-artix1-1   | 2         | 1.14%   |
| 4.19.0-1-MANJARO   | 2         | 1.14%   |
| 5.9.8-zen1-1-zen   | 1         | 0.57%   |
| 5.9.6-artix1-1     | 1         | 0.57%   |
| 5.9.10-artix1-1    | 1         | 0.57%   |
| 5.9.1-artix1-1     | 1         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.14  | 10        | 5.68%   |
| 5.12.12 | 6         | 3.41%   |
| 5.7.6   | 5         | 2.84%   |
| 5.15.12 | 5         | 2.84%   |
| 5.7.12  | 4         | 2.27%   |
| 5.12.8  | 4         | 2.27%   |
| 5.12.14 | 4         | 2.27%   |
| 5.10.4  | 4         | 2.27%   |
| 5.8.8   | 3         | 1.7%    |
| 5.8.14  | 3         | 1.7%    |
| 5.8.12  | 3         | 1.7%    |
| 5.18.16 | 3         | 1.7%    |
| 5.17.1  | 3         | 1.7%    |
| 5.16.8  | 3         | 1.7%    |
| 5.16.3  | 3         | 1.7%    |
| 5.16.10 | 3         | 1.7%    |
| 5.13.8  | 3         | 1.7%    |
| 5.10.8  | 3         | 1.7%    |
| 5.10.6  | 3         | 1.7%    |
| 5.10.16 | 3         | 1.7%    |
| 5.10.15 | 3         | 1.7%    |
| 5.9.12  | 2         | 1.14%   |
| 5.9.0   | 2         | 1.14%   |
| 5.7.2   | 2         | 1.14%   |
| 5.18.9  | 2         | 1.14%   |
| 5.18.6  | 2         | 1.14%   |
| 5.18.0  | 2         | 1.14%   |
| 5.17.4  | 2         | 1.14%   |
| 5.17.12 | 2         | 1.14%   |
| 5.16.1  | 2         | 1.14%   |
| 5.15.3  | 2         | 1.14%   |
| 5.14.16 | 2         | 1.14%   |
| 5.14.14 | 2         | 1.14%   |
| 5.12.4  | 2         | 1.14%   |
| 5.11.6  | 2         | 1.14%   |
| 5.11.16 | 2         | 1.14%   |
| 5.11.10 | 2         | 1.14%   |
| 4.19.0  | 2         | 1.14%   |
| 5.9.8   | 1         | 0.57%   |
| 5.9.6   | 1         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 21        | 12.5%   |
| 5.12    | 19        | 11.31%  |
| 5.15    | 18        | 10.71%  |
| 5.9     | 17        | 10.12%  |
| 5.18    | 14        | 8.33%   |
| 5.16    | 13        | 7.74%   |
| 5.11    | 12        | 7.14%   |
| 5.8     | 11        | 6.55%   |
| 5.17    | 11        | 6.55%   |
| 5.7     | 10        | 5.95%   |
| 5.14    | 7         | 4.17%   |
| 5.13    | 6         | 3.57%   |
| 5.19    | 3         | 1.79%   |
| 5.4     | 2         | 1.19%   |
| 4.19    | 2         | 1.19%   |
| 5.6     | 1         | 0.6%    |
| 5.5     | 1         | 0.6%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 147       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| KDE5           | 33        | 21.02%  |
| GNOME          | 26        | 16.56%  |
| XFCE           | 24        | 15.29%  |
| Unknown        | 22        | 14.01%  |
| X-Cinnamon     | 13        | 8.28%   |
| MATE           | 8         | 5.1%    |
| LXQt           | 5         | 3.18%   |
| Cinnamon       | 5         | 3.18%   |
| KDE            | 4         | 2.55%   |
| bspwm          | 4         | 2.55%   |
| Sway           | 2         | 1.27%   |
| LXDE           | 2         | 1.27%   |
| i3             | 2         | 1.27%   |
| xmonad         | 1         | 0.64%   |
| sway-dbus      | 1         | 0.64%   |
| openbox        | 1         | 0.64%   |
| nxde           | 1         | 0.64%   |
| DWM            | 1         | 0.64%   |
| awesomeminimal | 1         | 0.64%   |
| awesome        | 1         | 0.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 105       | 68.18%  |
| Tty     | 24        | 15.58%  |
| Wayland | 16        | 10.39%  |
| Unknown | 9         | 5.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 55        | 35.95%  |
| LightDM | 45        | 29.41%  |
| SDDM    | 42        | 27.45%  |
| GDM     | 4         | 2.61%   |
| XDM     | 2         | 1.31%   |
| SLiM    | 2         | 1.31%   |
| LXDM    | 2         | 1.31%   |
| Ly      | 1         | 0.65%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 64        | 42.11%  |
| Unknown | 17        | 11.18%  |
| ru_RU   | 14        | 9.21%   |
| fr_FR   | 8         | 5.26%   |
| en_GB   | 8         | 5.26%   |
| C       | 7         | 4.61%   |
| de_DE   | 6         | 3.95%   |
| pt_PT   | 3         | 1.97%   |
| es_ES   | 3         | 1.97%   |
| it_IT   | 2         | 1.32%   |
| en_CA   | 2         | 1.32%   |
| en_AU   | 2         | 1.32%   |
| el_GR   | 2         | 1.32%   |
| uk_UA   | 1         | 0.66%   |
| tr_TR   | 1         | 0.66%   |
| pt_BR   | 1         | 0.66%   |
| pl_PL   | 1         | 0.66%   |
| lt_LT   | 1         | 0.66%   |
| ja_JP   | 1         | 0.66%   |
| es_MX   | 1         | 0.66%   |
| es_GT   | 1         | 0.66%   |
| es_AR   | 1         | 0.66%   |
| en_IN   | 1         | 0.66%   |
| en_IE   | 1         | 0.66%   |
| en_AG   | 1         | 0.66%   |
| cs_CZ   | 1         | 0.66%   |
| bg_BG   | 1         | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 108       | 72.48%  |
| BIOS | 41        | 27.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 103       | 69.59%  |
| Btrfs   | 34        | 22.97%  |
| Xfs     | 6         | 4.05%   |
| F2fs    | 3         | 2.03%   |
| Overlay | 1         | 0.68%   |
| Jfs     | 1         | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 110       | 73.33%  |
| Unknown | 23        | 15.33%  |
| MBR     | 17        | 11.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 120       | 80.54%  |
| Yes       | 29        | 19.46%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 109       | 73.65%  |
| Yes       | 39        | 26.35%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 27        | 18.37%  |
| ASUSTek Computer    | 24        | 16.33%  |
| Hewlett-Packard     | 16        | 10.88%  |
| Dell                | 16        | 10.88%  |
| Gigabyte Technology | 14        | 9.52%   |
| Acer                | 12        | 8.16%   |
| MSI                 | 11        | 7.48%   |
| ASRock              | 6         | 4.08%   |
| Apple               | 3         | 2.04%   |
| Timi                | 2         | 1.36%   |
| Notebook            | 2         | 1.36%   |
| Intel               | 2         | 1.36%   |
| GPD                 | 2         | 1.36%   |
| UNOWHY              | 1         | 0.68%   |
| Quanta              | 1         | 0.68%   |
| MOTILE              | 1         | 0.68%   |
| Microsoft           | 1         | 0.68%   |
| LG Electronics      | 1         | 0.68%   |
| HUAWEI              | 1         | 0.68%   |
| Biostar             | 1         | 0.68%   |
| AXIOO               | 1         | 0.68%   |
| Alienware           | 1         | 0.68%   |
| Acidanthera         | 1         | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Timi RedmiBook 14 II                   | 2         | 1.36%   |
| MSI MS-7C02                            | 2         | 1.36%   |
| MSI MS-7A38                            | 2         | 1.36%   |
| Lenovo IdeaPad 5 15IIL05 81YK          | 2         | 1.36%   |
| HP 15                                  | 2         | 1.36%   |
| GPD P2 MAX                             | 2         | 1.36%   |
| Gigabyte 970A-DS3P                     | 2         | 1.36%   |
| Dell Precision M6600                   | 2         | 1.36%   |
| Dell Precision 7550                    | 2         | 1.36%   |
| Apple MacBookAir7,2                    | 2         | 1.36%   |
| UNOWHY Y13G010S4EI                     | 1         | 0.68%   |
| Quanta SWH                             | 1         | 0.68%   |
| Notebook N141CU                        | 1         | 0.68%   |
| Notebook N130BU                        | 1         | 0.68%   |
| MSI MS-7C89                            | 1         | 0.68%   |
| MSI MS-7C56                            | 1         | 0.68%   |
| MSI MS-7C37                            | 1         | 0.68%   |
| MSI MS-7B79                            | 1         | 0.68%   |
| MSI MS-7A69                            | 1         | 0.68%   |
| MSI Modern 15 A11M                     | 1         | 0.68%   |
| MSI GP72 7RDX                          | 1         | 0.68%   |
| MOTILE M141                            | 1         | 0.68%   |
| Microsoft Surface Pro                  | 1         | 0.68%   |
| LG 17Z990-R.AAC9U1                     | 1         | 0.68%   |
| Lenovo ThinkPad W500 4063CJ5           | 1         | 0.68%   |
| Lenovo ThinkPad T480s 20L8S3D400       | 1         | 0.68%   |
| Lenovo ThinkPad T480 MFG_IN_GO         | 1         | 0.68%   |
| Lenovo ThinkPad T440s 20ARS0MV00       | 1         | 0.68%   |
| Lenovo ThinkPad T430 2350BC6           | 1         | 0.68%   |
| Lenovo ThinkPad T430 2347H76           | 1         | 0.68%   |
| Lenovo ThinkPad T420 4236H45           | 1         | 0.68%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00   | 1         | 0.68%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800   | 1         | 0.68%   |
| Lenovo ThinkPad P1 Gen 3 20TH001EMH    | 1         | 0.68%   |
| Lenovo ThinkPad E14 Gen 2 20T6000MCK   | 1         | 0.68%   |
| Lenovo ThinkPad 11e 5th Gen 20LNS0P500 | 1         | 0.68%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 1         | 0.68%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 0.68%   |
| Lenovo LaVie Z 20FF0012US              | 1         | 0.68%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2      | 1         | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 12        | 8.16%   |
| Acer Aspire        | 8         | 5.44%   |
| Lenovo IdeaPad     | 7         | 4.76%   |
| Dell Precision     | 6         | 4.08%   |
| HP Laptop          | 5         | 3.4%    |
| Dell Inspiron      | 5         | 3.4%    |
| Dell Latitude      | 4         | 2.72%   |
| HP 250             | 3         | 2.04%   |
| ASUS ROG           | 3         | 2.04%   |
| ASUS PRIME         | 3         | 2.04%   |
| Timi RedmiBook     | 2         | 1.36%   |
| MSI MS-7C02        | 2         | 1.36%   |
| MSI MS-7A38        | 2         | 1.36%   |
| Lenovo IdeaPadFlex | 2         | 1.36%   |
| HP 15              | 2         | 1.36%   |
| GPD P2             | 2         | 1.36%   |
| Gigabyte X570      | 2         | 1.36%   |
| Gigabyte 970A-DS3P | 2         | 1.36%   |
| ASUS TUF           | 2         | 1.36%   |
| Apple MacBookAir7  | 2         | 1.36%   |
| Acer Nitro         | 2         | 1.36%   |
| UNOWHY Y13G010S4EI | 1         | 0.68%   |
| Quanta SWH         | 1         | 0.68%   |
| Notebook N141CU    | 1         | 0.68%   |
| Notebook N130BU    | 1         | 0.68%   |
| MSI MS-7C89        | 1         | 0.68%   |
| MSI MS-7C56        | 1         | 0.68%   |
| MSI MS-7C37        | 1         | 0.68%   |
| MSI MS-7B79        | 1         | 0.68%   |
| MSI MS-7A69        | 1         | 0.68%   |
| MSI Modern         | 1         | 0.68%   |
| MSI GP72           | 1         | 0.68%   |
| MOTILE M141        | 1         | 0.68%   |
| Microsoft Surface  | 1         | 0.68%   |
| LG 17Z990-R.AAC9U1 | 1         | 0.68%   |
| Lenovo ThinkBook   | 1         | 0.68%   |
| Lenovo Legion      | 1         | 0.68%   |
| Lenovo LaVie       | 1         | 0.68%   |
| Lenovo G400s       | 1         | 0.68%   |
| Lenovo B590        | 1         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 32        | 21.77%  |
| 2019 | 21        | 14.29%  |
| 2018 | 18        | 12.24%  |
| 2017 | 13        | 8.84%   |
| 2012 | 13        | 8.84%   |
| 2013 | 11        | 7.48%   |
| 2011 | 9         | 6.12%   |
| 2015 | 8         | 5.44%   |
| 2014 | 7         | 4.76%   |
| 2016 | 5         | 3.4%    |
| 2021 | 4         | 2.72%   |
| 2010 | 3         | 2.04%   |
| 2008 | 2         | 1.36%   |
| 2009 | 1         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 93        | 63.27%  |
| Desktop     | 49        | 33.33%  |
| Convertible | 2         | 1.36%   |
| Tablet      | 1         | 0.68%   |
| Mini pc     | 1         | 0.68%   |
| All in one  | 1         | 0.68%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 146       | 99.32%  |
| Enabled  | 1         | 0.68%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 147       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 39        | 26.17%  |
| 8.01-16.0   | 37        | 24.83%  |
| 4.01-8.0    | 28        | 18.79%  |
| 3.01-4.0    | 21        | 14.09%  |
| 32.01-64.0  | 10        | 6.71%   |
| 64.01-256.0 | 7         | 4.7%    |
| 1.01-2.0    | 5         | 3.36%   |
| 24.01-32.0  | 2         | 1.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 42        | 25.15%  |
| 4.01-8.0   | 38        | 22.75%  |
| 2.01-3.0   | 36        | 21.56%  |
| 3.01-4.0   | 26        | 15.57%  |
| 0.51-1.0   | 13        | 7.78%   |
| 8.01-16.0  | 6         | 3.59%   |
| 0.01-0.5   | 4         | 2.4%    |
| 16.01-24.0 | 2         | 1.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 84        | 56%     |
| 2      | 44        | 29.33%  |
| 3      | 14        | 9.33%   |
| 4      | 4         | 2.67%   |
| 6      | 2         | 1.33%   |
| 8      | 1         | 0.67%   |
| 7      | 1         | 0.67%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 111       | 75.51%  |
| Yes       | 36        | 24.49%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 126       | 85.71%  |
| No        | 21        | 14.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 119       | 80.95%  |
| No        | 28        | 19.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 98        | 65.77%  |
| No        | 51        | 34.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 27        | 18.24%  |
| Russia      | 15        | 10.14%  |
| Germany     | 15        | 10.14%  |
| France      | 10        | 6.76%   |
| UK          | 5         | 3.38%   |
| Turkey      | 5         | 3.38%   |
| India       | 5         | 3.38%   |
| Brazil      | 5         | 3.38%   |
| Ukraine     | 4         | 2.7%    |
| Switzerland | 4         | 2.7%    |
| Poland      | 4         | 2.7%    |
| Indonesia   | 4         | 2.7%    |
| Greece      | 4         | 2.7%    |
| Canada      | 4         | 2.7%    |
| Bulgaria    | 4         | 2.7%    |
| Spain       | 3         | 2.03%   |
| Netherlands | 3         | 2.03%   |
| Lithuania   | 2         | 1.35%   |
| Italy       | 2         | 1.35%   |
| Finland     | 2         | 1.35%   |
| Czechia     | 2         | 1.35%   |
| Australia   | 2         | 1.35%   |
| Argentina   | 2         | 1.35%   |
| Uzbekistan  | 1         | 0.68%   |
| Sweden      | 1         | 0.68%   |
| Slovenia    | 1         | 0.68%   |
| Romania     | 1         | 0.68%   |
| Mexico      | 1         | 0.68%   |
| Japan       | 1         | 0.68%   |
| Iran        | 1         | 0.68%   |
| Hong Kong   | 1         | 0.68%   |
| Guatemala   | 1         | 0.68%   |
| China       | 1         | 0.68%   |
| Chile       | 1         | 0.68%   |
| Bangladesh  | 1         | 0.68%   |
| Azerbaijan  | 1         | 0.68%   |
| Austria     | 1         | 0.68%   |
| Algeria     | 1         | 0.68%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 6         | 3.82%   |
| Frankfurt am Main | 4         | 2.55%   |
| Moscow            | 3         | 1.91%   |
| Jakarta           | 3         | 1.91%   |
| Dnipro            | 3         | 1.91%   |
| Vilnius           | 2         | 1.27%   |
| St Petersburg     | 2         | 1.27%   |
| Sofia             | 2         | 1.27%   |
| Snohomish         | 2         | 1.27%   |
| San Ramon         | 2         | 1.27%   |
| Samara            | 2         | 1.27%   |
| Rio de Janeiro    | 2         | 1.27%   |
| Prague            | 2         | 1.27%   |
| Omaha             | 2         | 1.27%   |
| Neuchatel         | 2         | 1.27%   |
| Los Angeles       | 2         | 1.27%   |
| Kłodzko          | 2         | 1.27%   |
| Helsinki          | 2         | 1.27%   |
| Charlotte         | 2         | 1.27%   |
| Bern              | 2         | 1.27%   |
| Athens            | 2         | 1.27%   |
| Ankara            | 2         | 1.27%   |
| Amsterdam         | 2         | 1.27%   |
| Zaporizhzhya      | 1         | 0.64%   |
| Wigan             | 1         | 0.64%   |
| Wettringen        | 1         | 0.64%   |
| Wem               | 1         | 0.64%   |
| Vladivostok       | 1         | 0.64%   |
| Vienna            | 1         | 0.64%   |
| Varna             | 1         | 0.64%   |
| Vancouver         | 1         | 0.64%   |
| Upper Norwood     | 1         | 0.64%   |
| Ufa               | 1         | 0.64%   |
| Toronto           | 1         | 0.64%   |
| Timișoara        | 1         | 0.64%   |
| Thessaloniki      | 1         | 0.64%   |
| Tehran            | 1         | 0.64%   |
| Tashkent          | 1         | 0.64%   |
| Syeverodonets'k   | 1         | 0.64%   |
| Sydney            | 1         | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 37        | 52     | 15.95%  |
| Seagate                   | 35        | 42     | 15.09%  |
| WDC                       | 31        | 51     | 13.36%  |
| Toshiba                   | 17        | 18     | 7.33%   |
| Kingston                  | 15        | 16     | 6.47%   |
| SanDisk                   | 11        | 13     | 4.74%   |
| Intel                     | 10        | 15     | 4.31%   |
| Crucial                   | 10        | 16     | 4.31%   |
| SK hynix                  | 7         | 13     | 3.02%   |
| HGST                      | 7         | 8      | 3.02%   |
| Hitachi                   | 6         | 7      | 2.59%   |
| China                     | 5         | 5      | 2.16%   |
| Apple                     | 3         | 4      | 1.29%   |
| A-DATA Technology         | 3         | 3      | 1.29%   |
| Unknown                   | 2         | 2      | 0.86%   |
| SPCC                      | 2         | 2      | 0.86%   |
| PNY                       | 2         | 2      | 0.86%   |
| Phison Electronics        | 2         | 3      | 0.86%   |
| Maxtor                    | 2         | 2      | 0.86%   |
| Linux                     | 2         | 2      | 0.86%   |
| JMicron Technology        | 2         | 2      | 0.86%   |
| Corsair                   | 2         | 2      | 0.86%   |
| Union Memory              | 1         | 1      | 0.43%   |
| TS512GMT                  | 1         | 3      | 0.43%   |
| Transcend                 | 1         | 1      | 0.43%   |
| Timetec                   | 1         | 2      | 0.43%   |
| Solid State Storage       | 1         | 1      | 0.43%   |
| Plextor                   | 1         | 1      | 0.43%   |
| Phison                    | 1         | 1      | 0.43%   |
| Patriot                   | 1         | 1      | 0.43%   |
| Netac                     | 1         | 1      | 0.43%   |
| Micron/Crucial Technology | 1         | 1      | 0.43%   |
| Micron Technology         | 1         | 1      | 0.43%   |
| LITEON                    | 1         | 1      | 0.43%   |
| Lite-On                   | 1         | 1      | 0.43%   |
| LDLC                      | 1         | 5      | 0.43%   |
| Intenso                   | 1         | 1      | 0.43%   |
| Hewlett-Packard           | 1         | 1      | 0.43%   |
| Goodram                   | 1         | 1      | 0.43%   |
| AMD                       | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| SanDisk NVMe SSD Drive 512GB         | 4         | 1.57%   |
| Toshiba DT01ACA100 1TB               | 3         | 1.18%   |
| Seagate ST3500418AS 500GB            | 3         | 1.18%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 1.18%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 1.18%   |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 1.18%   |
| Samsung SSD 970 EVO 1TB              | 3         | 1.18%   |
| Samsung SSD 860 EVO 250GB            | 3         | 1.18%   |
| Samsung NVMe SSD Drive 1TB           | 3         | 1.18%   |
| HGST HTS545050A7E680 500GB           | 3         | 1.18%   |
| Crucial CT240BX500SSD1 240GB         | 3         | 1.18%   |
| Crucial CT1000MX500SSD1 1TB          | 3         | 1.18%   |
| China SATA SSD 960GB                 | 3         | 1.18%   |
| WDC WD80EZAZ-11TDBA0 8TB             | 2         | 0.79%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.79%   |
| WDC WD10EZEX-22MFCA0 1TB             | 2         | 0.79%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 0.79%   |
| Toshiba MQ04ABF100 1TB               | 2         | 0.79%   |
| Toshiba MQ01ABF050 500GB             | 2         | 0.79%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.79%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 0.79%   |
| Seagate ST500DM002-1BD142 500GB      | 2         | 0.79%   |
| SanDisk NVMe SSD Drive 500GB         | 2         | 0.79%   |
| Samsung SSD 870 EVO 250GB            | 2         | 0.79%   |
| Samsung MZYTY256HDHP-000L2 256GB SSD | 2         | 0.79%   |
| Samsung MZNLH512HALU-00000 512GB SSD | 2         | 0.79%   |
| Phison PCIe SSD 240GB                | 2         | 0.79%   |
| Linux scsi_debug 8.3MB               | 2         | 0.79%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 0.79%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 0.79%   |
| Apple SSD SM0256G 256GB              | 2         | 0.79%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.39%   |
| WDC WDS256G1X0C-00ENX0 256GB         | 1         | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 1         | 0.39%   |
| WDC WDS200T2B0B-00YS70 2TB SSD       | 1         | 0.39%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 0.39%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 0.39%   |
| WDC WDBNCE5000PNC 500GB SSD          | 1         | 0.39%   |
| WDC WD6001FZWX-00A2VA0 6TB           | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 35        | 42     | 38.04%  |
| WDC                | 26        | 40     | 28.26%  |
| Toshiba            | 14        | 15     | 15.22%  |
| HGST               | 7         | 8      | 7.61%   |
| Hitachi            | 6         | 7      | 6.52%   |
| Maxtor             | 2         | 2      | 2.17%   |
| Unknown            | 1         | 1      | 1.09%   |
| JMicron Technology | 1         | 1      | 1.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 22     | 23.29%  |
| Kingston            | 11        | 11     | 15.07%  |
| Crucial             | 10        | 16     | 13.7%   |
| WDC                 | 5         | 8      | 6.85%   |
| China               | 5         | 5      | 6.85%   |
| SanDisk             | 3         | 3      | 4.11%   |
| Intel               | 3         | 4      | 4.11%   |
| Apple               | 3         | 4      | 4.11%   |
| SPCC                | 2         | 2      | 2.74%   |
| Linux               | 2         | 2      | 2.74%   |
| A-DATA Technology   | 2         | 2      | 2.74%   |
| Toshiba             | 1         | 1      | 1.37%   |
| SK hynix            | 1         | 1      | 1.37%   |
| PNY                 | 1         | 1      | 1.37%   |
| Plextor             | 1         | 1      | 1.37%   |
| Patriot             | 1         | 1      | 1.37%   |
| Netac               | 1         | 1      | 1.37%   |
| LDLC                | 1         | 5      | 1.37%   |
| Intenso             | 1         | 1      | 1.37%   |
| Goodram             | 1         | 1      | 1.37%   |
| AMD                 | 1         | 1      | 1.37%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 80        | 116    | 38.28%  |
| SSD     | 66        | 93     | 31.58%  |
| NVMe    | 59        | 90     | 28.23%  |
| Unknown | 3         | 6      | 1.44%   |
| MMC     | 1         | 1      | 0.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 112       | 207    | 62.92%  |
| NVMe | 58        | 89     | 32.58%  |
| SAS  | 7         | 9      | 3.93%   |
| MMC  | 1         | 1      | 0.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 77        | 110    | 51.33%  |
| 0.51-1.0   | 51        | 69     | 34%     |
| 1.01-2.0   | 11        | 13     | 7.33%   |
| 3.01-4.0   | 4         | 4      | 2.67%   |
| 2.01-3.0   | 4         | 4      | 2.67%   |
| 4.01-10.0  | 3         | 9      | 2%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 39        | 25.83%  |
| 251-500        | 31        | 20.53%  |
| 501-1000       | 21        | 13.91%  |
| 1001-2000      | 20        | 13.25%  |
| More than 3000 | 14        | 9.27%   |
| 2001-3000      | 9         | 5.96%   |
| 51-100         | 7         | 4.64%   |
| Unknown        | 5         | 3.31%   |
| 1-20           | 3         | 1.99%   |
| 21-50          | 2         | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 37        | 23.27%  |
| 101-250        | 25        | 15.72%  |
| 501-1000       | 22        | 13.84%  |
| 251-500        | 20        | 12.58%  |
| 51-100         | 16        | 10.06%  |
| 21-50          | 15        | 9.43%   |
| 1001-2000      | 9         | 5.66%   |
| More than 3000 | 7         | 4.4%    |
| Unknown        | 5         | 3.14%   |
| 2001-3000      | 3         | 1.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 7.69%   |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 7.69%   |
| WDC WD3200LPVT-00FMCT0 320GB                     | 1         | 1      | 3.85%   |
| WDC WD3200AAKX-00ERMA0 320GB                     | 1         | 1      | 3.85%   |
| WDC WD30EZRX-00DC0B0 3TB                         | 1         | 1      | 3.85%   |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 3.85%   |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 3.85%   |
| Seagate ST8000DM004-2CX188 8TB                   | 1         | 1      | 3.85%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 3.85%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 3.85%   |
| Seagate ST2000DX002-2DV164 2TB                   | 1         | 1      | 3.85%   |
| Seagate ST2000DM006-2DM164 2TB                   | 1         | 1      | 3.85%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 3.85%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 3.85%   |
| Maxtor 6Y080M0 81GB                              | 1         | 1      | 3.85%   |
| LDLC SSD 120GB                                   | 1         | 3      | 3.85%   |
| Kingston SUV400S37240G 240GB SSD                 | 1         | 1      | 3.85%   |
| Kingston SA400S37120G 120GB SSD                  | 1         | 1      | 3.85%   |
| Intel SSDSC2BW480A4 480GB                        | 1         | 2      | 3.85%   |
| Intel SSDPEKKW128G7 128GB                        | 1         | 1      | 3.85%   |
| Hitachi HTS547550A9E384 500GB                    | 1         | 1      | 3.85%   |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 3.85%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 3.85%   |
| Hewlett-Packard SSD EX900 250GB                  | 1         | 1      | 3.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 23.08%  |
| Toshiba             | 4         | 4      | 15.38%  |
| WDC                 | 3         | 3      | 11.54%  |
| HGST                | 3         | 3      | 11.54%  |
| Kingston            | 2         | 2      | 7.69%   |
| Intel               | 2         | 3      | 7.69%   |
| Hitachi             | 2         | 2      | 7.69%   |
| Samsung Electronics | 1         | 1      | 3.85%   |
| Maxtor              | 1         | 1      | 3.85%   |
| LDLC                | 1         | 3      | 3.85%   |
| Hewlett-Packard     | 1         | 1      | 3.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 31.58%  |
| Toshiba | 4         | 4      | 21.05%  |
| WDC     | 3         | 3      | 15.79%  |
| HGST    | 3         | 3      | 15.79%  |
| Hitachi | 2         | 2      | 10.53%  |
| Maxtor  | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 19     | 73.08%  |
| SSD  | 5         | 8      | 19.23%  |
| NVMe | 2         | 2      | 7.69%   |

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
| Works    | 85        | 154    | 50.3%   |
| Detected | 59        | 123    | 34.91%  |
| Malfunc  | 25        | 29     | 14.79%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 84        | 42.21%  |
| AMD                            | 43        | 21.61%  |
| Samsung Electronics            | 24        | 12.06%  |
| SanDisk                        | 10        | 5.03%   |
| SK hynix                       | 6         | 3.02%   |
| Marvell Technology Group       | 6         | 3.02%   |
| Phison Electronics             | 5         | 2.51%   |
| Kingston Technology Company    | 4         | 2.01%   |
| ASMedia Technology             | 3         | 1.51%   |
| Union Memory (Shenzhen)        | 2         | 1.01%   |
| Toshiba America Info Systems   | 2         | 1.01%   |
| Silicon Motion                 | 2         | 1.01%   |
| Solid State Storage Technology | 1         | 0.5%    |
| Nvidia                         | 1         | 0.5%    |
| Micron/Crucial Technology      | 1         | 0.5%    |
| Micron Technology              | 1         | 0.5%    |
| Lite-On Technology             | 1         | 0.5%    |
| JMicron Technology             | 1         | 0.5%    |
| Broadcom / LSI                 | 1         | 0.5%    |
| ADATA Technology               | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 33        | 14.8%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 14        | 6.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 3.59%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 3.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 3.14%   |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 3.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6         | 2.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 2.24%   |
| AMD 300 Series Chipset SATA Controller                                         | 5         | 2.24%   |
| SK hynix Non-Volatile memory controller                                        | 4         | 1.79%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 1.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.79%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 1.79%   |
| Phison E12 NVMe Controller                                                     | 4         | 1.79%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 1.79%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.79%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3         | 1.35%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 1.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.35%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 1.35%   |
| Intel SSD 660P Series                                                          | 3         | 1.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 1.35%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.35%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 0.9%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.9%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.9%    |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.9%    |
| Samsung Electronics SATA controller                                            | 2         | 0.9%    |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 0.9%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 0.9%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 0.9%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 116       | 59.49%  |
| NVMe | 59        | 30.26%  |
| RAID | 11        | 5.64%   |
| IDE  | 8         | 4.1%    |
| SAS  | 1         | 0.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 100       | 68.03%  |
| AMD    | 47        | 31.97%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor         | 4         | 2.7%    |
| AMD Ryzen 7 4700U with Radeon Graphics      | 4         | 2.7%    |
| AMD FX-8350 Eight-Core Processor            | 4         | 2.7%    |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 2         | 1.35%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2         | 1.35%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.35%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 1.35%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 1.35%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.35%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 1.35%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.35%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2         | 1.35%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 2         | 1.35%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 1.35%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 2         | 1.35%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.35%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.35%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 1.35%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.35%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2         | 1.35%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2         | 1.35%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.35%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2         | 1.35%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz        | 1         | 0.68%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.68%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.68%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.68%   |
| Intel Pentium CPU A1018 @ 2.10GHz           | 1         | 0.68%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 0.68%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz            | 1         | 0.68%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.68%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 1         | 0.68%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 0.68%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1         | 0.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.68%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.68%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.68%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.68%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.68%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 38        | 25.85%  |
| Intel Core i7           | 24        | 16.33%  |
| AMD Ryzen 7             | 15        | 10.2%   |
| Intel Core i3           | 11        | 7.48%   |
| AMD Ryzen 5             | 11        | 7.48%   |
| Intel Celeron           | 8         | 5.44%   |
| AMD Ryzen 9             | 5         | 3.4%    |
| AMD FX                  | 5         | 3.4%    |
| Other                   | 4         | 2.72%   |
| AMD Ryzen 3             | 4         | 2.72%   |
| Intel Pentium           | 3         | 2.04%   |
| Intel Core m3           | 3         | 2.04%   |
| Intel Core 2 Duo        | 3         | 2.04%   |
| Intel Core i9           | 2         | 1.36%   |
| Intel Xeon              | 1         | 0.68%   |
| Intel Pentium Silver    | 1         | 0.68%   |
| Intel Pentium Dual-Core | 1         | 0.68%   |
| Intel Atom              | 1         | 0.68%   |
| AMD Ryzen Threadripper  | 1         | 0.68%   |
| AMD Ryzen 5 PRO         | 1         | 0.68%   |
| AMD Phenom II X4        | 1         | 0.68%   |
| AMD E1                  | 1         | 0.68%   |
| AMD Athlon              | 1         | 0.68%   |
| AMD A6                  | 1         | 0.68%   |
| AMD A10                 | 1         | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 53        | 36.05%  |
| 4      | 47        | 31.97%  |
| 8      | 20        | 13.61%  |
| 6      | 19        | 12.93%  |
| 12     | 5         | 3.4%    |
| 3      | 2         | 1.36%   |
| 32     | 1         | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 147       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 107       | 72.79%  |
| 1      | 40        | 27.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 147       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 17.76%  |
| 0x206a7    | 9         | 5.92%   |
| 0x306a9    | 8         | 5.26%   |
| 0x806e9    | 5         | 3.29%   |
| 0x40651    | 5         | 3.29%   |
| 0x08701013 | 5         | 3.29%   |
| 0xa0652    | 4         | 2.63%   |
| 0x906ed    | 4         | 2.63%   |
| 0x906e9    | 4         | 2.63%   |
| 0x806ec    | 4         | 2.63%   |
| 0x806ea    | 4         | 2.63%   |
| 0x806c1    | 4         | 2.63%   |
| 0x706a1    | 4         | 2.63%   |
| 0x306d4    | 4         | 2.63%   |
| 0x08600106 | 4         | 2.63%   |
| 0x0800820d | 4         | 2.63%   |
| 0x906ea    | 3         | 1.97%   |
| 0x706e5    | 3         | 1.97%   |
| 0x506e3    | 3         | 1.97%   |
| 0x306c3    | 3         | 1.97%   |
| 0x1067a    | 3         | 1.97%   |
| 0x08701021 | 3         | 1.97%   |
| 0x06000822 | 3         | 1.97%   |
| 0xa0655    | 2         | 1.32%   |
| 0x30678    | 2         | 1.32%   |
| 0x08600103 | 2         | 1.32%   |
| 0x08108109 | 2         | 1.32%   |
| 0x06000852 | 2         | 1.32%   |
| 0xa0653    | 1         | 0.66%   |
| 0x806eb    | 1         | 0.66%   |
| 0x6fd      | 1         | 0.66%   |
| 0x506c9    | 1         | 0.66%   |
| 0x406e3    | 1         | 0.66%   |
| 0x206c2    | 1         | 0.66%   |
| 0x20655    | 1         | 0.66%   |
| 0x20652    | 1         | 0.66%   |
| 0x0a50000b | 1         | 0.66%   |
| 0x0a201016 | 1         | 0.66%   |
| 0x0a201009 | 1         | 0.66%   |
| 0x08608103 | 1         | 0.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 32        | 21.77%  |
| Zen 2         | 17        | 11.56%  |
| Zen+          | 10        | 6.8%    |
| SandyBridge   | 10        | 6.8%    |
| IvyBridge     | 10        | 6.8%    |
| Haswell       | 9         | 6.12%   |
| CometLake     | 8         | 5.44%   |
| Zen           | 6         | 4.08%   |
| Piledriver    | 5         | 3.4%    |
| Broadwell     | 5         | 3.4%    |
| Zen 3         | 4         | 2.72%   |
| TigerLake     | 4         | 2.72%   |
| Skylake       | 4         | 2.72%   |
| Goldmont plus | 4         | 2.72%   |
| Westmere      | 3         | 2.04%   |
| Penryn        | 3         | 2.04%   |
| IceLake       | 3         | 2.04%   |
| Silvermont    | 2         | 1.36%   |
| Steamroller   | 1         | 0.68%   |
| Puma          | 1         | 0.68%   |
| K10           | 1         | 0.68%   |
| Jaguar        | 1         | 0.68%   |
| Goldmont      | 1         | 0.68%   |
| Core          | 1         | 0.68%   |
| Bonnell       | 1         | 0.68%   |
| Unknown       | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 77        | 44.51%  |
| AMD    | 51        | 29.48%  |
| Nvidia | 45        | 26.01%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 9         | 5.14%   |
| AMD Renoir                                                                | 7         | 4%      |
| Intel HD Graphics 620                                                     | 6         | 3.43%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 3.43%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 3.43%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 5         | 2.86%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 5         | 2.86%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 2.29%   |
| Intel UHD Graphics 620                                                    | 4         | 2.29%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 2.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 2.29%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 4         | 2.29%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.71%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 1.71%   |
| Intel HD Graphics 5500                                                    | 3         | 1.71%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 1.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 1.71%   |
| Nvidia TU117M                                                             | 2         | 1.14%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.14%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 2         | 1.14%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 2         | 1.14%   |
| Nvidia GM206 [GeForce GTX 950]                                            | 2         | 1.14%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 1.14%   |
| Intel UHD Graphics 615                                                    | 2         | 1.14%   |
| Intel HD Graphics 630                                                     | 2         | 1.14%   |
| Intel HD Graphics 6000                                                    | 2         | 1.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 1.14%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                    | 2         | 1.14%   |
| AMD Saturn XT [FirePro M6100]                                             | 2         | 1.14%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.14%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                | 2         | 1.14%   |
| AMD Cezanne                                                               | 2         | 1.14%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                            | 2         | 1.14%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.57%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1         | 0.57%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.57%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                    | 1         | 0.57%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                    | 1         | 0.57%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                     | 1         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 55        | 36.91%  |
| 1 x AMD        | 44        | 29.53%  |
| 1 x Nvidia     | 24        | 16.11%  |
| Intel + Nvidia | 18        | 12.08%  |
| Intel + AMD    | 3         | 2.01%   |
| AMD + Nvidia   | 3         | 2.01%   |
| 2 x AMD        | 2         | 1.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 120       | 80.54%  |
| Proprietary | 29        | 19.46%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 79        | 51.63%  |
| 1.01-2.0   | 18        | 11.76%  |
| 7.01-8.0   | 15        | 9.8%    |
| 3.01-4.0   | 14        | 9.15%   |
| 0.01-0.5   | 11        | 7.19%   |
| 0.51-1.0   | 9         | 5.88%   |
| 5.01-6.0   | 3         | 1.96%   |
| 8.01-16.0  | 3         | 1.96%   |
| 2.01-3.0   | 1         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 20        | 10.99%  |
| AU Optronics            | 19        | 10.44%  |
| Samsung Electronics     | 17        | 9.34%   |
| BOE                     | 17        | 9.34%   |
| Chimei Innolux          | 15        | 8.24%   |
| Acer                    | 10        | 5.49%   |
| Philips                 | 8         | 4.4%    |
| Goldstar                | 8         | 4.4%    |
| Dell                    | 8         | 4.4%    |
| BenQ                    | 7         | 3.85%   |
| AOC                     | 7         | 3.85%   |
| ASUSTek Computer        | 6         | 3.3%    |
| Chi Mei Optoelectronics | 4         | 2.2%    |
| InfoVision              | 3         | 1.65%   |
| Hewlett-Packard         | 3         | 1.65%   |
| Apple                   | 3         | 1.65%   |
| Ancor Communications    | 3         | 1.65%   |
| Sharp                   | 2         | 1.1%    |
| PANDA                   | 2         | 1.1%    |
| MSI                     | 2         | 1.1%    |
| ViewSonic               | 1         | 0.55%   |
| Vestel Elektronik       | 1         | 0.55%   |
| Sony                    | 1         | 0.55%   |
| Packard Bell            | 1         | 0.55%   |
| LGD                     | 1         | 0.55%   |
| Lenovo                  | 1         | 0.55%   |
| KTC                     | 1         | 0.55%   |
| KDC                     | 1         | 0.55%   |
| Jean                    | 1         | 0.55%   |
| Iiyama                  | 1         | 0.55%   |
| Idek Iiyama             | 1         | 0.55%   |
| HVR                     | 1         | 0.55%   |
| Hitachi                 | 1         | 0.55%   |
| Envision Peripherals    | 1         | 0.55%   |
| Eizo                    | 1         | 0.55%   |
| CTV                     | 1         | 0.55%   |
| Compal                  | 1         | 0.55%   |
| Belinea                 | 1         | 0.55%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 1.61%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch      | 2         | 1.08%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                   | 2         | 1.08%   |
| MSI Optix MAG27C MSI1462 1920x1080 598x336mm 27.0-inch                    | 2         | 1.08%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 1.08%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch          | 2         | 1.08%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.08%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 1.08%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 1.08%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 1.08%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 1.08%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 1.08%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 621x341mm 27.9-inch              | 2         | 1.08%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 1.08%   |
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                             | 2         | 1.08%   |
| Ancor Communications ASUS PB277 ACI27B5 2560x1440 597x336mm 27.0-inch     | 2         | 1.08%   |
| ViewSonic LCD Monitor VX2452 Series 3840x1080                             | 1         | 0.54%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch        | 1         | 0.54%   |
| Sony TV SNY7001 1920x1080                                                 | 1         | 0.54%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 0.54%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.54%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch         | 1         | 0.54%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch         | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM047D 1360x768 410x230mm 18.5-inch       | 1         | 0.54%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 0.54%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 0.54%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 1         | 0.54%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 1         | 0.54%   |
| Samsung Electronics S24A31x SAM7114 1920x1080 527x296mm 23.8-inch         | 1         | 0.54%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch         | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch   | 1         | 0.54%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1872x1053mm 84.6-inch   | 1         | 0.54%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch         | 1         | 0.54%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch         | 1         | 0.54%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch         | 1         | 0.54%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch         | 1         | 0.54%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                  | 1         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 84        | 48.84%  |
| 1366x768 (WXGA)    | 33        | 19.19%  |
| 3840x2160 (4K)     | 15        | 8.72%   |
| 2560x1440 (QHD)    | 9         | 5.23%   |
| 1600x900 (HD+)     | 4         | 2.33%   |
| 1440x900 (WXGA+)   | 4         | 2.33%   |
| 3440x1440          | 3         | 1.74%   |
| 2560x1600          | 2         | 1.16%   |
| 2560x1080          | 2         | 1.16%   |
| 1920x1200 (WUXGA)  | 2         | 1.16%   |
| 1680x1050 (WSXGA+) | 2         | 1.16%   |
| 1280x1024 (SXGA)   | 2         | 1.16%   |
| Unknown            | 2         | 1.16%   |
| 3840x1080          | 1         | 0.58%   |
| 3600x1080          | 1         | 0.58%   |
| 2736x1824          | 1         | 0.58%   |
| 2160x1440          | 1         | 0.58%   |
| 2160x1200          | 1         | 0.58%   |
| 1360x768           | 1         | 0.58%   |
| 1280x960           | 1         | 0.58%   |
| 1024x768 (XGA)     | 1         | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 48        | 26.97%  |
| 13      | 19        | 10.67%  |
| 27      | 16        | 8.99%   |
| 24      | 16        | 8.99%   |
| 14      | 15        | 8.43%   |
| 23      | 14        | 7.87%   |
| 21      | 11        | 6.18%   |
| 17      | 7         | 3.93%   |
| 34      | 5         | 2.81%   |
| Unknown | 5         | 2.81%   |
| 84      | 4         | 2.25%   |
| 19      | 4         | 2.25%   |
| 31      | 3         | 1.69%   |
| 32      | 2         | 1.12%   |
| 20      | 2         | 1.12%   |
| 12      | 2         | 1.12%   |
| 72      | 1         | 0.56%   |
| 52      | 1         | 0.56%   |
| 18      | 1         | 0.56%   |
| 16      | 1         | 0.56%   |
| 11      | 1         | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 75        | 42.61%  |
| 501-600     | 41        | 23.3%   |
| 401-500     | 15        | 8.52%   |
| 351-400     | 12        | 6.82%   |
| 201-300     | 9         | 5.11%   |
| 701-800     | 7         | 3.98%   |
| 601-700     | 6         | 3.41%   |
| 1501-2000   | 5         | 2.84%   |
| Unknown     | 5         | 2.84%   |
| 1001-1500   | 1         | 0.57%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 128       | 82.58%  |
| 16/10   | 11        | 7.1%    |
| 21/9    | 5         | 3.23%   |
| Unknown | 4         | 2.58%   |
| 5/4     | 3         | 1.94%   |
| 4/3     | 2         | 1.29%   |
| 3/2     | 2         | 1.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 48        | 26.97%  |
| 201-250        | 37        | 20.79%  |
| 81-90          | 28        | 15.73%  |
| 301-350        | 16        | 8.99%   |
| 351-500        | 10        | 5.62%   |
| 71-80          | 7         | 3.93%   |
| 151-200        | 7         | 3.93%   |
| More than 1000 | 6         | 3.37%   |
| 121-130        | 6         | 3.37%   |
| Unknown        | 5         | 2.81%   |
| 251-300        | 3         | 1.69%   |
| 131-140        | 2         | 1.12%   |
| 61-70          | 1         | 0.56%   |
| 51-60          | 1         | 0.56%   |
| 141-150        | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 59        | 34.5%   |
| 51-100        | 51        | 29.82%  |
| 101-120       | 45        | 26.32%  |
| 161-240       | 8         | 4.68%   |
| Unknown       | 5         | 2.92%   |
| 1-50          | 2         | 1.17%   |
| More than 240 | 1         | 0.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 119       | 78.81%  |
| 2     | 28        | 18.54%  |
| 3     | 3         | 1.99%   |
| 4     | 1         | 0.66%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 95        | 41.67%  |
| Intel                                 | 72        | 31.58%  |
| Qualcomm Atheros                      | 22        | 9.65%   |
| Broadcom                              | 8         | 3.51%   |
| Broadcom Limited                      | 4         | 1.75%   |
| TP-Link                               | 3         | 1.32%   |
| D-Link System                         | 3         | 1.32%   |
| Xiaomi                                | 2         | 0.88%   |
| Ralink Technology                     | 2         | 0.88%   |
| Ralink                                | 2         | 0.88%   |
| Sierra Wireless                       | 1         | 0.44%   |
| Samsung Electronics                   | 1         | 0.44%   |
| Qualcomm Atheros Communications       | 1         | 0.44%   |
| Qualcomm                              | 1         | 0.44%   |
| OPPO Electronics                      | 1         | 0.44%   |
| Microsoft                             | 1         | 0.44%   |
| MediaTek                              | 1         | 0.44%   |
| Marvell Technology Group              | 1         | 0.44%   |
| Linksys                               | 1         | 0.44%   |
| Huawei Technologies                   | 1         | 0.44%   |
| Google                                | 1         | 0.44%   |
| DisplayLink                           | 1         | 0.44%   |
| Aquantia                              | 1         | 0.44%   |
| Apple                                 | 1         | 0.44%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.44%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 24.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 4.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 2.93%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.2%    |
| Intel Wireless 8265 / 8275                                        | 6         | 2.2%    |
| Intel I211 Gigabit Network Connection                             | 6         | 2.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.83%   |
| Intel Wireless 7265                                               | 5         | 1.83%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 1.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.47%   |
| Realtek 802.11ac NIC                                              | 3         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.1%    |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.1%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.1%    |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.1%    |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.1%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.1%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.73%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.73%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.73%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.73%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.73%   |
| Intel Wireless-AC 9260                                            | 2         | 0.73%   |
| Intel Wireless 7260                                               | 2         | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.73%   |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.73%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 56        | 44.44%  |
| Realtek Semiconductor                 | 27        | 21.43%  |
| Qualcomm Atheros                      | 18        | 14.29%  |
| Broadcom                              | 7         | 5.56%   |
| Broadcom Limited                      | 4         | 3.17%   |
| TP-Link                               | 3         | 2.38%   |
| Ralink Technology                     | 2         | 1.59%   |
| Ralink                                | 2         | 1.59%   |
| Sierra Wireless                       | 1         | 0.79%   |
| Qualcomm Atheros Communications       | 1         | 0.79%   |
| Microsoft                             | 1         | 0.79%   |
| MediaTek                              | 1         | 0.79%   |
| Marvell Technology Group              | 1         | 0.79%   |
| D-Link System                         | 1         | 0.79%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.79%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                        | 7         | 5.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 6         | 4.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 6         | 4.72%   |
| Intel Wireless 8265 / 8275                                 | 6         | 4.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 5         | 3.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 5         | 3.94%   |
| Intel Wireless 7265                                        | 5         | 3.94%   |
| Intel Comet Lake PCH CNVi WiFi                             | 5         | 3.94%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 4         | 3.15%   |
| Realtek 802.11ac NIC                                       | 3         | 2.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 3         | 2.36%   |
| Intel Wi-Fi 6 AX201                                        | 3         | 2.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 3         | 2.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 3         | 2.36%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter | 3         | 2.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter        | 3         | 2.36%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                | 2         | 1.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 2         | 1.57%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 2         | 1.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 1.57%   |
| Realtek RTL8188EE Wireless Network Adapter                 | 2         | 1.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 1.57%   |
| Intel Wireless-AC 9260                                     | 2         | 1.57%   |
| Intel Wireless 7260                                        | 2         | 1.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                            | 2         | 1.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]           | 2         | 1.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 2         | 1.57%   |
| Intel Centrino Wireless-N 2230                             | 2         | 1.57%   |
| Broadcom BCM43228 802.11a/b/g/n                            | 2         | 1.57%   |
| Broadcom BCM43142 802.11b/g/n                              | 2         | 1.57%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                        | 1         | 0.79%   |
| Sierra Wireless MC7750                                     | 1         | 0.79%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter   | 1         | 0.79%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter            | 1         | 0.79%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                    | 1         | 0.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                 | 1         | 0.79%   |
| Realtek 802.11n WLAN Adapter                               | 1         | 0.79%   |
| Ralink RT5370 Wireless Adapter                             | 1         | 0.79%   |
| Ralink MT7601U Wireless Adapter                            | 1         | 0.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                  | 1         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 85        | 60.71%  |
| Intel                 | 34        | 24.29%  |
| Qualcomm Atheros      | 7         | 5%      |
| Xiaomi                | 2         | 1.43%   |
| D-Link System         | 2         | 1.43%   |
| Samsung Electronics   | 1         | 0.71%   |
| Qualcomm              | 1         | 0.71%   |
| OPPO Electronics      | 1         | 0.71%   |
| Linksys               | 1         | 0.71%   |
| Huawei Technologies   | 1         | 0.71%   |
| Google                | 1         | 0.71%   |
| DisplayLink           | 1         | 0.71%   |
| Broadcom              | 1         | 0.71%   |
| Aquantia              | 1         | 0.71%   |
| Apple                 | 1         | 0.71%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 66        | 45.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 8.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 5.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 4.79%   |
| Intel I211 Gigabit Network Connection                             | 6         | 4.11%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.05%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.05%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 2.05%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.37%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.37%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 1.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.68%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.68%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.68%   |
| Qualcomm A0001                                                    | 1         | 0.68%   |
| OPPO RMX2117                                                      | 1         | 0.68%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.68%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.68%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.68%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.68%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.68%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.68%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.68%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 0.68%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.68%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.68%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1         | 0.68%   |
| Intel 82562V-2 10/100 Network Connection                          | 1         | 0.68%   |
| Huawei E353/E3131                                                 | 1         | 0.68%   |
| Google Nexus/Pixel Device (tether+ debug)                         | 1         | 0.68%   |
| DisplayLink Kensington Dock (Composite Device)                    | 1         | 0.68%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.68%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 126       | 51.22%  |
| WiFi     | 120       | 48.78%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 90        | 59.6%   |
| Ethernet | 61        | 40.4%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 87        | 58.78%  |
| 1     | 56        | 37.84%  |
| 4     | 2         | 1.35%   |
| 3     | 2         | 1.35%   |
| 0     | 1         | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 133       | 88.08%  |
| Yes  | 18        | 11.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 48        | 48.98%  |
| Realtek Semiconductor           | 13        | 13.27%  |
| Broadcom                        | 6         | 6.12%   |
| Qualcomm Atheros Communications | 5         | 5.1%    |
| IMC Networks                    | 5         | 5.1%    |
| Lite-On Technology              | 4         | 4.08%   |
| Cambridge Silicon Radio         | 4         | 4.08%   |
| Foxconn / Hon Hai               | 3         | 3.06%   |
| Apple                           | 3         | 3.06%   |
| Realtek                         | 2         | 2.04%   |
| ASUSTek Computer                | 2         | 2.04%   |
| Ralink                          | 1         | 1.02%   |
| Marvell Semiconductor           | 1         | 1.02%   |
| HTC (High Tech Computer)        | 1         | 1.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 14        | 14.29%  |
| Intel AX201 Bluetooth                                                | 11        | 11.22%  |
| Realtek Bluetooth Radio                                              | 9         | 9.18%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 9         | 9.18%   |
| Intel AX200 Bluetooth                                                | 7         | 7.14%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 4         | 4.08%   |
| Qualcomm Atheros  Bluetooth Device                                   | 4         | 4.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 4         | 4.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 3         | 3.06%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3         | 3.06%   |
| Realtek Bluetooth Radio                                              | 2         | 2.04%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2         | 2.04%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 2         | 2.04%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 2         | 2.04%   |
| IMC Networks Bluetooth Radio                                         | 2         | 2.04%   |
| IMC Networks Bluetooth Device                                        | 2         | 2.04%   |
| Foxconn / Hon Hai BCM20702A0                                         | 2         | 2.04%   |
| Apple Bluetooth USB Host Controller                                  | 2         | 2.04%   |
| Ralink RT3290 Bluetooth                                              | 1         | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 1.02%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 1         | 1.02%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                         | 1         | 1.02%   |
| Intel AX210 Bluetooth                                                | 1         | 1.02%   |
| IMC Networks Wireless_Device                                         | 1         | 1.02%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 1.02%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 1         | 1.02%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1         | 1.02%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 1         | 1.02%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 1         | 1.02%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1         | 1.02%   |
| ASUS Bluetooth Radio                                                 | 1         | 1.02%   |
| Apple Bluetooth Host Controller                                      | 1         | 1.02%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 98        | 43.75%  |
| AMD                                             | 58        | 25.89%  |
| Nvidia                                          | 36        | 16.07%  |
| C-Media Electronics                             | 9         | 4.02%   |
| Realtek Semiconductor                           | 4         | 1.79%   |
| Creative Labs                                   | 3         | 1.34%   |
| Logitech                                        | 2         | 0.89%   |
| Creative Technology                             | 2         | 0.89%   |
| Corsair                                         | 2         | 0.89%   |
| TC Electronic                                   | 1         | 0.45%   |
| SteelSeries ApS                                 | 1         | 0.45%   |
| Razer USA                                       | 1         | 0.45%   |
| Plantronics                                     | 1         | 0.45%   |
| Native Instruments                              | 1         | 0.45%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.45%   |
| Harman                                          | 1         | 0.45%   |
| Generalplus Technology                          | 1         | 0.45%   |
| Focusrite-Novation                              | 1         | 0.45%   |
| AudioQuest                                      | 1         | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 17        | 6.18%   |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 5.09%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11        | 4%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 3.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 3.64%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 3.27%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 9         | 3.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9         | 3.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 2.18%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 2.18%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 2.18%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 2.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.18%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 1.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 1.82%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.82%   |
| AMD Navi 10 HDMI Audio                                                     | 5         | 1.82%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.45%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 1.45%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.45%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.45%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4         | 1.45%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 1.45%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.09%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.09%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.09%   |
| C-Media Electronics USB Audio Device                                       | 3         | 1.09%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 1.09%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.09%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.73%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.73%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.73%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 20.78%  |
| SK hynix            | 31        | 20.13%  |
| Kingston            | 20        | 12.99%  |
| Corsair             | 13        | 8.44%   |
| G.Skill             | 10        | 6.49%   |
| Micron Technology   | 9         | 5.84%   |
| Unknown             | 7         | 4.55%   |
| Crucial             | 5         | 3.25%   |
| Patriot             | 4         | 2.6%    |
| A-DATA Technology   | 4         | 2.6%    |
| Silicon Power       | 3         | 1.95%   |
| Unknown             | 3         | 1.95%   |
| Unknown (ABCD)      | 2         | 1.3%    |
| Smart               | 2         | 1.3%    |
| Ramaxel Technology  | 2         | 1.3%    |
| Nanya Technology    | 2         | 1.3%    |
| Transcend           | 1         | 0.65%   |
| Team                | 1         | 0.65%   |
| Smart Brazil        | 1         | 0.65%   |
| ASint Technology    | 1         | 0.65%   |
| AMD                 | 1         | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 4         | 2.45%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.84%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.84%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 3         | 1.84%   |
| Unknown                                                          | 3         | 1.84%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 2         | 1.23%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.23%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.23%   |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.23%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.23%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.23%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 2         | 1.23%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 2         | 1.23%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 1.23%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.23%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.23%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.23%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.23%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s            | 2         | 1.23%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1400MT/s             | 2         | 1.23%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s         | 2         | 1.23%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1.23%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                          | 1         | 0.61%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.61%   |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s              | 1         | 0.61%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.61%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 1         | 0.61%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2400MT/s            | 1         | 0.61%   |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 2933MT/s  | 1         | 0.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.61%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.61%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 73        | 57.03%  |
| DDR3    | 41        | 32.03%  |
| LPDDR4  | 4         | 3.13%   |
| SDRAM   | 3         | 2.34%   |
| LPDDR3  | 3         | 2.34%   |
| Unknown | 3         | 2.34%   |
| DDR2    | 1         | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 74        | 57.36%  |
| DIMM         | 44        | 34.11%  |
| Row Of Chips | 9         | 6.98%   |
| Chip         | 1         | 0.78%   |
| Unknown      | 1         | 0.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 54        | 36.99%  |
| 8192  | 50        | 34.25%  |
| 16384 | 22        | 15.07%  |
| 2048  | 15        | 10.27%  |
| 32768 | 3         | 2.05%   |
| 1024  | 2         | 1.37%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 34        | 24.46%  |
| 3200    | 28        | 20.14%  |
| 2667    | 20        | 14.39%  |
| 2400    | 14        | 10.07%  |
| 1333    | 9         | 6.47%   |
| 3600    | 7         | 5.04%   |
| 2133    | 5         | 3.6%    |
| 2933    | 3         | 2.16%   |
| 4199    | 2         | 1.44%   |
| 3266    | 2         | 1.44%   |
| 1400    | 2         | 1.44%   |
| 1334    | 2         | 1.44%   |
| 4267    | 1         | 0.72%   |
| 4133    | 1         | 0.72%   |
| 3466    | 1         | 0.72%   |
| 3400    | 1         | 0.72%   |
| 2800    | 1         | 0.72%   |
| 2481    | 1         | 0.72%   |
| 2465    | 1         | 0.72%   |
| 1328    | 1         | 0.72%   |
| 1066    | 1         | 0.72%   |
| 800     | 1         | 0.72%   |
| Unknown | 1         | 0.72%   |

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
| Chicony Electronics                    | 19        | 20%     |
| Acer                                   | 10        | 10.53%  |
| Realtek Semiconductor                  | 9         | 9.47%   |
| Quanta                                 | 9         | 9.47%   |
| Suyin                                  | 6         | 6.32%   |
| IMC Networks                           | 6         | 6.32%   |
| Syntek                                 | 4         | 4.21%   |
| Sunplus Innovation Technology          | 4         | 4.21%   |
| Logitech                               | 4         | 4.21%   |
| Alcor Micro                            | 4         | 4.21%   |
| Microdia                               | 3         | 3.16%   |
| Luxvisions Innotech Limited            | 3         | 3.16%   |
| Silicon Motion                         | 2         | 2.11%   |
| Creative Technology                    | 2         | 2.11%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.11%   |
| Sonix Technology                       | 1         | 1.05%   |
| Microsoft                              | 1         | 1.05%   |
| Lite-On Technology                     | 1         | 1.05%   |
| LG Electronics                         | 1         | 1.05%   |
| Lenovo                                 | 1         | 1.05%   |
| KYE Systems (Mouse Systems)            | 1         | 1.05%   |
| GEMBIRD                                | 1         | 1.05%   |
| ARC International                      | 1         | 1.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                     | 6         | 6.32%   |
| IMC Networks Integrated Camera                        | 5         | 5.26%   |
| Realtek Integrated_Webcam_HD                          | 4         | 4.21%   |
| Chicony Integrated Camera                             | 4         | 4.21%   |
| Acer Integrated Camera                                | 4         | 4.21%   |
| Syntek Integrated Camera                              | 2         | 2.11%   |
| Syntek EasyCamera                                     | 2         | 2.11%   |
| Suyin HP Webcam                                       | 2         | 2.11%   |
| Silicon Motion 300k Pixel Camera                      | 2         | 2.11%   |
| Realtek USB2.0 HD UVC WebCam                          | 2         | 2.11%   |
| Realtek HD WebCam                                     | 2         | 2.11%   |
| Quanta VGA WebCam                                     | 2         | 2.11%   |
| Quanta HP Webcam                                      | 2         | 2.11%   |
| Quanta HP TrueVision HD Camera                        | 2         | 2.11%   |
| Microdia Integrated Webcam                            | 2         | 2.11%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera   | 2         | 2.11%   |
| Chicony USB2.0 VGA UVC WebCam                         | 2         | 2.11%   |
| Chicony Integrated Camera (1280x720@30)               | 2         | 2.11%   |
| Suyin USB Webcam                                      | 1         | 1.05%   |
| Suyin NEC HD WebCam                                   | 1         | 1.05%   |
| Suyin Laptop_Integrated_Webcam_HD                     | 1         | 1.05%   |
| Suyin 1.3M HD WebCam                                  | 1         | 1.05%   |
| Sunplus Laptop_Integrated_Webcam_FHD                  | 1         | 1.05%   |
| Sunplus Integrated_Webcam_HD                          | 1         | 1.05%   |
| Sunplus HD WebCam                                     | 1         | 1.05%   |
| Sunplus Aukey-PC-LM1E Camera                          | 1         | 1.05%   |
| Sonix USB2.0 HD UVC WebCam                            | 1         | 1.05%   |
| Realtek Integrated Webcam                             | 1         | 1.05%   |
| Quanta USB2.0 VGA UVC WebCam                          | 1         | 1.05%   |
| Quanta HD Webcam                                      | 1         | 1.05%   |
| Quanta HD User Facing                                 | 1         | 1.05%   |
| Microsoft LifeCam Cinema                              | 1         | 1.05%   |
| Microdia Integrated_Webcam_HD                         | 1         | 1.05%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera  | 1         | 1.05%   |
| Logitech Webcam C930e                                 | 1         | 1.05%   |
| Logitech Webcam C310                                  | 1         | 1.05%   |
| Logitech Webcam C270                                  | 1         | 1.05%   |
| Logitech HD Webcam C910                               | 1         | 1.05%   |
| Lite-On HP HD Camera                                  | 1         | 1.05%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode) | 1         | 1.05%   |

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
| 0     | 114       | 76%     |
| 1     | 31        | 20.67%  |
| 2     | 5         | 3.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 8         | 19.51%  |
| Net/wireless             | 6         | 14.63%  |
| Graphics card            | 5         | 12.2%   |
| Multimedia controller    | 4         | 9.76%   |
| Chipcard                 | 4         | 9.76%   |
| Camera                   | 4         | 9.76%   |
| Bluetooth                | 3         | 7.32%   |
| Storage                  | 2         | 4.88%   |
| Communication controller | 2         | 4.88%   |
| Unassigned class         | 1         | 2.44%   |
| Network                  | 1         | 2.44%   |
| Dvb card                 | 1         | 2.44%   |

