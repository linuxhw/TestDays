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

Total: 226

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [eeb167d869](https://linux-hardware.org/?probe=eeb167d869) | Nov 02, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [d72c486584](https://linux-hardware.org/?probe=d72c486584) | Oct 22, 2022 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [debce2faa6](https://linux-hardware.org/?probe=debce2faa6) | Oct 20, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [6cbb7cbc35](https://linux-hardware.org/?probe=6cbb7cbc35) | Oct 17, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [ca934ff06b](https://linux-hardware.org/?probe=ca934ff06b) | Oct 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7dce56f55d](https://linux-hardware.org/?probe=7dce56f55d) | Oct 10, 2022 |
| HP            | Pavilion g4                 | Notebook    | [19fe60b14c](https://linux-hardware.org/?probe=19fe60b14c) | Oct 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [7d1f20cf17](https://linux-hardware.org/?probe=7d1f20cf17) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [dfd00dd2d1](https://linux-hardware.org/?probe=dfd00dd2d1) | Oct 03, 2022 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Artix Rolling  | 97        | 60.25%  |
| Artix          | 55        | 34.16%  |
| Artix 20220123 | 3         | 1.86%   |
| Artix 20220713 | 2         | 1.24%   |
| Artix 20210726 | 2         | 1.24%   |
| Artix 20201207 | 1         | 0.62%   |
| Artix 20201128 | 1         | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Artix | 154       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.9.14-artix1-1    | 8         | 4.4%    |
| 5.7.6-artix1-1     | 5         | 2.75%   |
| 5.7.12-artix1-1    | 4         | 2.2%    |
| 5.15.12-artix1-1   | 4         | 2.2%    |
| 5.12.12-artix1-1   | 4         | 2.2%    |
| 5.10.4-artix2-1    | 4         | 2.2%    |
| 5.8.8-artix1-1     | 3         | 1.65%   |
| 5.8.12-artix1-1    | 3         | 1.65%   |
| 5.18.16-artix1-1   | 3         | 1.65%   |
| 5.16.3-artix1-1    | 3         | 1.65%   |
| 5.16.10-artix1-1   | 3         | 1.65%   |
| 5.12.8-artix1-1    | 3         | 1.65%   |
| 5.12.14-artix1-1   | 3         | 1.65%   |
| 5.10.8-artix1-1    | 3         | 1.65%   |
| 5.10.6-artix1-1    | 3         | 1.65%   |
| 5.10.16-artix1-1   | 3         | 1.65%   |
| 5.9.14-zen1-1-zen  | 2         | 1.1%    |
| 5.9.12-artix1-1    | 2         | 1.1%    |
| 5.8.14-artix1-1    | 2         | 1.1%    |
| 5.7.2-artix1-1     | 2         | 1.1%    |
| 5.19.12-artix1-1   | 2         | 1.1%    |
| 5.18.9-zen1-1-zen  | 2         | 1.1%    |
| 5.18.6-artix1-1    | 2         | 1.1%    |
| 5.18.0-artix1-1    | 2         | 1.1%    |
| 5.17.4-artix1-1    | 2         | 1.1%    |
| 5.17.1-artix1-1    | 2         | 1.1%    |
| 5.16.8-artix1-2    | 2         | 1.1%    |
| 5.16.1-artix1-1    | 2         | 1.1%    |
| 5.15.3-zen1-1-zen  | 2         | 1.1%    |
| 5.14.16-artix1-1   | 2         | 1.1%    |
| 5.13.8-artix1-1    | 2         | 1.1%    |
| 5.12.4-artix1-1    | 2         | 1.1%    |
| 5.12.12-zen1-1-zen | 2         | 1.1%    |
| 5.11.6-artix1-1    | 2         | 1.1%    |
| 5.11.10-artix1-1   | 2         | 1.1%    |
| 5.10.15-artix1-1   | 2         | 1.1%    |
| 4.19.0-1-MANJARO   | 2         | 1.1%    |
| 6.0.2-artix1-1.1   | 1         | 0.55%   |
| 6.0.1-arch1-1      | 1         | 0.55%   |
| 5.9.8-zen1-1-zen   | 1         | 0.55%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.14  | 10        | 5.49%   |
| 5.12.12 | 6         | 3.3%    |
| 5.7.6   | 5         | 2.75%   |
| 5.15.12 | 5         | 2.75%   |
| 5.7.12  | 4         | 2.2%    |
| 5.12.8  | 4         | 2.2%    |
| 5.12.14 | 4         | 2.2%    |
| 5.10.4  | 4         | 2.2%    |
| 5.8.8   | 3         | 1.65%   |
| 5.8.14  | 3         | 1.65%   |
| 5.8.12  | 3         | 1.65%   |
| 5.18.16 | 3         | 1.65%   |
| 5.17.1  | 3         | 1.65%   |
| 5.16.3  | 3         | 1.65%   |
| 5.16.10 | 3         | 1.65%   |
| 5.13.8  | 3         | 1.65%   |
| 5.10.8  | 3         | 1.65%   |
| 5.10.6  | 3         | 1.65%   |
| 5.10.16 | 3         | 1.65%   |
| 5.10.15 | 3         | 1.65%   |
| 5.9.12  | 2         | 1.1%    |
| 5.9.0   | 2         | 1.1%    |
| 5.7.2   | 2         | 1.1%    |
| 5.19.12 | 2         | 1.1%    |
| 5.18.9  | 2         | 1.1%    |
| 5.18.6  | 2         | 1.1%    |
| 5.18.0  | 2         | 1.1%    |
| 5.17.4  | 2         | 1.1%    |
| 5.17.12 | 2         | 1.1%    |
| 5.16.8  | 2         | 1.1%    |
| 5.16.1  | 2         | 1.1%    |
| 5.15.3  | 2         | 1.1%    |
| 5.14.16 | 2         | 1.1%    |
| 5.14.14 | 2         | 1.1%    |
| 5.12.4  | 2         | 1.1%    |
| 5.11.6  | 2         | 1.1%    |
| 5.11.16 | 2         | 1.1%    |
| 5.11.10 | 2         | 1.1%    |
| 4.19.0  | 2         | 1.1%    |
| 6.0.2   | 1         | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 21        | 12.07%  |
| 5.15    | 19        | 10.92%  |
| 5.12    | 19        | 10.92%  |
| 5.9     | 17        | 9.77%   |
| 5.18    | 14        | 8.05%   |
| 5.16    | 13        | 7.47%   |
| 5.11    | 12        | 6.9%    |
| 5.8     | 11        | 6.32%   |
| 5.17    | 11        | 6.32%   |
| 5.7     | 10        | 5.75%   |
| 5.14    | 7         | 4.02%   |
| 5.19    | 6         | 3.45%   |
| 5.13    | 6         | 3.45%   |
| 6.0     | 2         | 1.15%   |
| 5.4     | 2         | 1.15%   |
| 4.19    | 2         | 1.15%   |
| 5.6     | 1         | 0.57%   |
| 5.5     | 1         | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 154       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| KDE5           | 35        | 21.34%  |
| GNOME          | 26        | 15.85%  |
| XFCE           | 25        | 15.24%  |
| Unknown        | 23        | 14.02%  |
| X-Cinnamon     | 13        | 7.93%   |
| MATE           | 9         | 5.49%   |
| LXQt           | 5         | 3.05%   |
| Cinnamon       | 5         | 3.05%   |
| LXDE           | 4         | 2.44%   |
| KDE            | 4         | 2.44%   |
| bspwm          | 4         | 2.44%   |
| sway           | 2         | 1.22%   |
| i3             | 2         | 1.22%   |
| xmonad         | 1         | 0.61%   |
| sway-dbus      | 1         | 0.61%   |
| openbox        | 1         | 0.61%   |
| nxde           | 1         | 0.61%   |
| DWM            | 1         | 0.61%   |
| awesomeminimal | 1         | 0.61%   |
| awesome        | 1         | 0.61%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 110       | 68.75%  |
| Tty     | 25        | 15.63%  |
| Wayland | 16        | 10%     |
| Unknown | 9         | 5.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 58        | 36.25%  |
| LightDM | 47        | 29.38%  |
| SDDM    | 44        | 27.5%   |
| GDM     | 4         | 2.5%    |
| XDM     | 2         | 1.25%   |
| SLiM    | 2         | 1.25%   |
| LXDM    | 2         | 1.25%   |
| Ly      | 1         | 0.63%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 68        | 43.04%  |
| Unknown | 16        | 10.13%  |
| ru_RU   | 14        | 8.86%   |
| fr_FR   | 8         | 5.06%   |
| en_GB   | 8         | 5.06%   |
| C       | 8         | 5.06%   |
| de_DE   | 6         | 3.8%    |
| pt_PT   | 3         | 1.9%    |
| es_ES   | 3         | 1.9%    |
| it_IT   | 2         | 1.27%   |
| en_CA   | 2         | 1.27%   |
| en_AU   | 2         | 1.27%   |
| el_GR   | 2         | 1.27%   |
| uk_UA   | 1         | 0.63%   |
| tr_TR   | 1         | 0.63%   |
| pt_BR   | 1         | 0.63%   |
| pl_PL   | 1         | 0.63%   |
| lt_LT   | 1         | 0.63%   |
| ja_JP   | 1         | 0.63%   |
| es_MX   | 1         | 0.63%   |
| es_GT   | 1         | 0.63%   |
| es_CO   | 1         | 0.63%   |
| es_AR   | 1         | 0.63%   |
| en_NZ   | 1         | 0.63%   |
| en_IN   | 1         | 0.63%   |
| en_IE   | 1         | 0.63%   |
| en_AG   | 1         | 0.63%   |
| cs_CZ   | 1         | 0.63%   |
| bg_BG   | 1         | 0.63%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 110       | 70.51%  |
| BIOS | 46        | 29.49%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 109       | 70.32%  |
| Btrfs   | 34        | 21.94%  |
| Xfs     | 6         | 3.87%   |
| F2fs    | 3         | 1.94%   |
| Overlay | 2         | 1.29%   |
| Jfs     | 1         | 0.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 114       | 72.61%  |
| Unknown | 25        | 15.92%  |
| MBR     | 18        | 11.46%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 126       | 80.77%  |
| Yes       | 30        | 19.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 114       | 73.55%  |
| Yes       | 41        | 26.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 28        | 18.18%  |
| ASUSTek Computer    | 26        | 16.88%  |
| Hewlett-Packard     | 17        | 11.04%  |
| Gigabyte Technology | 16        | 10.39%  |
| Dell                | 16        | 10.39%  |
| MSI                 | 12        | 7.79%   |
| Acer                | 12        | 7.79%   |
| ASRock              | 6         | 3.9%    |
| Apple               | 3         | 1.95%   |
| Timi                | 2         | 1.3%    |
| Notebook            | 2         | 1.3%    |
| Intel               | 2         | 1.3%    |
| GPD                 | 2         | 1.3%    |
| UNOWHY              | 1         | 0.65%   |
| Quanta              | 1         | 0.65%   |
| MOTILE              | 1         | 0.65%   |
| Microsoft           | 1         | 0.65%   |
| LG Electronics      | 1         | 0.65%   |
| HUAWEI              | 1         | 0.65%   |
| Biostar             | 1         | 0.65%   |
| AXIOO               | 1         | 0.65%   |
| Alienware           | 1         | 0.65%   |
| Acidanthera         | 1         | 0.65%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Timi RedmiBook 14 II                   | 2         | 1.3%    |
| MSI MS-7C02                            | 2         | 1.3%    |
| MSI MS-7A38                            | 2         | 1.3%    |
| Lenovo IdeaPad 5 15IIL05 81YK          | 2         | 1.3%    |
| HP 15                                  | 2         | 1.3%    |
| GPD P2 MAX                             | 2         | 1.3%    |
| Gigabyte 970A-DS3P                     | 2         | 1.3%    |
| Dell Precision M6600                   | 2         | 1.3%    |
| Dell Precision 7550                    | 2         | 1.3%    |
| Apple MacBookAir7,2                    | 2         | 1.3%    |
| UNOWHY Y13G010S4EI                     | 1         | 0.65%   |
| Quanta SWH                             | 1         | 0.65%   |
| Notebook N141CU                        | 1         | 0.65%   |
| Notebook N130BU                        | 1         | 0.65%   |
| MSI MS-7C89                            | 1         | 0.65%   |
| MSI MS-7C56                            | 1         | 0.65%   |
| MSI MS-7C37                            | 1         | 0.65%   |
| MSI MS-7B79                            | 1         | 0.65%   |
| MSI MS-7A69                            | 1         | 0.65%   |
| MSI Modern 15 A11M                     | 1         | 0.65%   |
| MSI GP72 7RDX                          | 1         | 0.65%   |
| MSI GF65 Thin 10SDR                    | 1         | 0.65%   |
| MOTILE M141                            | 1         | 0.65%   |
| Microsoft Surface Pro                  | 1         | 0.65%   |
| LG 17Z990-R.AAC9U1                     | 1         | 0.65%   |
| Lenovo ThinkPad W500 4063CJ5           | 1         | 0.65%   |
| Lenovo ThinkPad T480s 20L8S3D400       | 1         | 0.65%   |
| Lenovo ThinkPad T480 MFG_IN_GO         | 1         | 0.65%   |
| Lenovo ThinkPad T440s 20ARS0MV00       | 1         | 0.65%   |
| Lenovo ThinkPad T430 2350BC6           | 1         | 0.65%   |
| Lenovo ThinkPad T430 2347H76           | 1         | 0.65%   |
| Lenovo ThinkPad T420 4236H45           | 1         | 0.65%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00   | 1         | 0.65%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800   | 1         | 0.65%   |
| Lenovo ThinkPad P1 Gen 3 20TH001EMH    | 1         | 0.65%   |
| Lenovo ThinkPad E14 Gen 2 20T6000MCK   | 1         | 0.65%   |
| Lenovo ThinkPad 11e 5th Gen 20LNS0P500 | 1         | 0.65%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 1         | 0.65%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 0.65%   |
| Lenovo LaVie Z 20FF0012US              | 1         | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 12        | 7.79%   |
| Lenovo IdeaPad     | 8         | 5.19%   |
| Acer Aspire        | 8         | 5.19%   |
| Dell Precision     | 6         | 3.9%    |
| HP Laptop          | 5         | 3.25%   |
| Dell Inspiron      | 5         | 3.25%   |
| Dell Latitude      | 4         | 2.6%    |
| HP 250             | 3         | 1.95%   |
| ASUS ROG           | 3         | 1.95%   |
| ASUS PRIME         | 3         | 1.95%   |
| Timi RedmiBook     | 2         | 1.3%    |
| MSI MS-7C02        | 2         | 1.3%    |
| MSI MS-7A38        | 2         | 1.3%    |
| Lenovo IdeaPadFlex | 2         | 1.3%    |
| HP 15              | 2         | 1.3%    |
| GPD P2             | 2         | 1.3%    |
| Gigabyte X570      | 2         | 1.3%    |
| Gigabyte 970A-DS3P | 2         | 1.3%    |
| ASUS VivoBook      | 2         | 1.3%    |
| ASUS TUF           | 2         | 1.3%    |
| ASUS ASUS          | 2         | 1.3%    |
| Apple MacBookAir7  | 2         | 1.3%    |
| Acer Nitro         | 2         | 1.3%    |
| UNOWHY Y13G010S4EI | 1         | 0.65%   |
| Quanta SWH         | 1         | 0.65%   |
| Notebook N141CU    | 1         | 0.65%   |
| Notebook N130BU    | 1         | 0.65%   |
| MSI MS-7C89        | 1         | 0.65%   |
| MSI MS-7C56        | 1         | 0.65%   |
| MSI MS-7C37        | 1         | 0.65%   |
| MSI MS-7B79        | 1         | 0.65%   |
| MSI MS-7A69        | 1         | 0.65%   |
| MSI Modern         | 1         | 0.65%   |
| MSI GP72           | 1         | 0.65%   |
| MSI GF65           | 1         | 0.65%   |
| MOTILE M141        | 1         | 0.65%   |
| Microsoft Surface  | 1         | 0.65%   |
| LG 17Z990-R.AAC9U1 | 1         | 0.65%   |
| Lenovo ThinkBook   | 1         | 0.65%   |
| Lenovo Legion      | 1         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 34        | 22.08%  |
| 2019 | 21        | 13.64%  |
| 2018 | 20        | 12.99%  |
| 2017 | 13        | 8.44%   |
| 2012 | 13        | 8.44%   |
| 2013 | 11        | 7.14%   |
| 2011 | 10        | 6.49%   |
| 2015 | 8         | 5.19%   |
| 2014 | 7         | 4.55%   |
| 2021 | 5         | 3.25%   |
| 2016 | 5         | 3.25%   |
| 2010 | 3         | 1.95%   |
| 2008 | 2         | 1.3%    |
| 2022 | 1         | 0.65%   |
| 2009 | 1         | 0.65%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 98        | 63.64%  |
| Desktop     | 51        | 33.12%  |
| Convertible | 2         | 1.3%    |
| Tablet      | 1         | 0.65%   |
| Mini pc     | 1         | 0.65%   |
| All in one  | 1         | 0.65%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 153       | 99.35%  |
| Enabled  | 1         | 0.65%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 154       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 41        | 26.28%  |
| 8.01-16.0   | 38        | 24.36%  |
| 4.01-8.0    | 30        | 19.23%  |
| 3.01-4.0    | 22        | 14.1%   |
| 32.01-64.0  | 11        | 7.05%   |
| 64.01-256.0 | 7         | 4.49%   |
| 1.01-2.0    | 5         | 3.21%   |
| 24.01-32.0  | 2         | 1.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 42        | 24.28%  |
| 2.01-3.0   | 40        | 23.12%  |
| 4.01-8.0   | 39        | 22.54%  |
| 3.01-4.0   | 27        | 15.61%  |
| 0.51-1.0   | 13        | 7.51%   |
| 8.01-16.0  | 6         | 3.47%   |
| 0.01-0.5   | 4         | 2.31%   |
| 16.01-24.0 | 2         | 1.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 88        | 56.05%  |
| 2      | 46        | 29.3%   |
| 3      | 14        | 8.92%   |
| 4      | 5         | 3.18%   |
| 6      | 2         | 1.27%   |
| 8      | 1         | 0.64%   |
| 7      | 1         | 0.64%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 117       | 75.97%  |
| Yes       | 37        | 24.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 131       | 85.06%  |
| No        | 23        | 14.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 125       | 81.17%  |
| No        | 29        | 18.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 67.31%  |
| No        | 51        | 32.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 29        | 18.71%  |
| Russia      | 15        | 9.68%   |
| Germany     | 15        | 9.68%   |
| France      | 10        | 6.45%   |
| India       | 6         | 3.87%   |
| UK          | 5         | 3.23%   |
| Turkey      | 5         | 3.23%   |
| Canada      | 5         | 3.23%   |
| Brazil      | 5         | 3.23%   |
| Ukraine     | 4         | 2.58%   |
| Switzerland | 4         | 2.58%   |
| Poland      | 4         | 2.58%   |
| Indonesia   | 4         | 2.58%   |
| Greece      | 4         | 2.58%   |
| Bulgaria    | 4         | 2.58%   |
| Spain       | 3         | 1.94%   |
| Netherlands | 3         | 1.94%   |
| Italy       | 3         | 1.94%   |
| Lithuania   | 2         | 1.29%   |
| Finland     | 2         | 1.29%   |
| Czechia     | 2         | 1.29%   |
| Australia   | 2         | 1.29%   |
| Argentina   | 2         | 1.29%   |
| Uzbekistan  | 1         | 0.65%   |
| Sweden      | 1         | 0.65%   |
| Slovenia    | 1         | 0.65%   |
| Romania     | 1         | 0.65%   |
| Peru        | 1         | 0.65%   |
| Mexico      | 1         | 0.65%   |
| Japan       | 1         | 0.65%   |
| Iran        | 1         | 0.65%   |
| Hong Kong   | 1         | 0.65%   |
| Guatemala   | 1         | 0.65%   |
| Colombia    | 1         | 0.65%   |
| China       | 1         | 0.65%   |
| Chile       | 1         | 0.65%   |
| Bangladesh  | 1         | 0.65%   |
| Azerbaijan  | 1         | 0.65%   |
| Austria     | 1         | 0.65%   |
| Algeria     | 1         | 0.65%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Paris             | 6         | 3.66%   |
| Frankfurt am Main | 4         | 2.44%   |
| Moscow            | 3         | 1.83%   |
| Jakarta           | 3         | 1.83%   |
| Dnipro            | 3         | 1.83%   |
| Vilnius           | 2         | 1.22%   |
| Toronto           | 2         | 1.22%   |
| St Petersburg     | 2         | 1.22%   |
| Sofia             | 2         | 1.22%   |
| Snohomish         | 2         | 1.22%   |
| San Ramon         | 2         | 1.22%   |
| Samara            | 2         | 1.22%   |
| Rio de Janeiro    | 2         | 1.22%   |
| Prague            | 2         | 1.22%   |
| Omaha             | 2         | 1.22%   |
| Neuchatel         | 2         | 1.22%   |
| Los Angeles       | 2         | 1.22%   |
| Kłodzko          | 2         | 1.22%   |
| Helsinki          | 2         | 1.22%   |
| Charlotte         | 2         | 1.22%   |
| Bern              | 2         | 1.22%   |
| Athens            | 2         | 1.22%   |
| Ankara            | 2         | 1.22%   |
| Amsterdam         | 2         | 1.22%   |
| Zaporizhzhya      | 1         | 0.61%   |
| Wigan             | 1         | 0.61%   |
| Wettringen        | 1         | 0.61%   |
| Wem               | 1         | 0.61%   |
| Vladivostok       | 1         | 0.61%   |
| Vienna            | 1         | 0.61%   |
| Varna             | 1         | 0.61%   |
| Vancouver         | 1         | 0.61%   |
| Upper Norwood     | 1         | 0.61%   |
| Ufa               | 1         | 0.61%   |
| Timișoara        | 1         | 0.61%   |
| Thessaloniki      | 1         | 0.61%   |
| Tehran            | 1         | 0.61%   |
| Tashkent          | 1         | 0.61%   |
| Syeverodonets'k   | 1         | 0.61%   |
| Sydney            | 1         | 0.61%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 39        | 53     | 16.05%  |
| Seagate                   | 37        | 44     | 15.23%  |
| WDC                       | 33        | 54     | 13.58%  |
| Toshiba                   | 17        | 18     | 7%      |
| Kingston                  | 17        | 18     | 7%      |
| SanDisk                   | 11        | 13     | 4.53%   |
| Intel                     | 10        | 15     | 4.12%   |
| Crucial                   | 10        | 16     | 4.12%   |
| SK hynix                  | 7         | 13     | 2.88%   |
| HGST                      | 7         | 8      | 2.88%   |
| Hitachi                   | 6         | 7      | 2.47%   |
| China                     | 5         | 5      | 2.06%   |
| Phison Electronics        | 3         | 4      | 1.23%   |
| Apple                     | 3         | 4      | 1.23%   |
| A-DATA Technology         | 3         | 3      | 1.23%   |
| Unknown                   | 2         | 2      | 0.82%   |
| SPCC                      | 2         | 2      | 0.82%   |
| PNY                       | 2         | 2      | 0.82%   |
| Phison                    | 2         | 2      | 0.82%   |
| Maxtor                    | 2         | 2      | 0.82%   |
| Linux                     | 2         | 2      | 0.82%   |
| JMicron Technology        | 2         | 2      | 0.82%   |
| Corsair                   | 2         | 2      | 0.82%   |
| Union Memory (Shenzhen)   | 1         | 1      | 0.41%   |
| Union Memory              | 1         | 1      | 0.41%   |
| TS512GMT                  | 1         | 3      | 0.41%   |
| Transcend                 | 1         | 1      | 0.41%   |
| Timetec                   | 1         | 2      | 0.41%   |
| Solid State Storage       | 1         | 1      | 0.41%   |
| Plextor                   | 1         | 1      | 0.41%   |
| Patriot                   | 1         | 1      | 0.41%   |
| Netac                     | 1         | 1      | 0.41%   |
| Micron/Crucial Technology | 1         | 1      | 0.41%   |
| Micron Technology         | 1         | 1      | 0.41%   |
| LITEON                    | 1         | 1      | 0.41%   |
| Lite-On                   | 1         | 1      | 0.41%   |
| LDLC                      | 1         | 5      | 0.41%   |
| Intenso                   | 1         | 1      | 0.41%   |
| Hewlett-Packard           | 1         | 1      | 0.41%   |
| Goodram                   | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 4         | 1.5%    |
| SanDisk NVMe SSD Drive 512GB                        | 4         | 1.5%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 3         | 1.13%   |
| Toshiba DT01ACA100 1TB                              | 3         | 1.13%   |
| Seagate ST3500418AS 500GB                           | 3         | 1.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 1.13%   |
| Seagate ST1000DM010-2EP102 1TB                      | 3         | 1.13%   |
| Samsung SSD 970 EVO 1TB                             | 3         | 1.13%   |
| Samsung SSD 860 EVO 250GB                           | 3         | 1.13%   |
| Samsung NVMe SSD Drive 1TB                          | 3         | 1.13%   |
| HGST HTS545050A7E680 500GB                          | 3         | 1.13%   |
| Crucial CT240BX500SSD1 240GB                        | 3         | 1.13%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 1.13%   |
| China SATA SSD 960GB                                | 3         | 1.13%   |
| WDC WD80EZAZ-11TDBA0 8TB                            | 2         | 0.75%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 0.75%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 2         | 0.75%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 0.75%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 0.75%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.75%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 0.75%   |
| Seagate ST500DM002-1BD142 500GB                     | 2         | 0.75%   |
| SanDisk NVMe SSD Drive 500GB                        | 2         | 0.75%   |
| Samsung SSD 870 EVO 250GB                           | 2         | 0.75%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 2         | 0.75%   |
| Samsung MZYTY256HDHP-000L2 256GB SSD                | 2         | 0.75%   |
| Samsung MZNLH512HALU-00000 512GB SSD                | 2         | 0.75%   |
| Phison PCIe SSD 512GB                               | 2         | 0.75%   |
| Linux scsi_debug 8.3MB                              | 2         | 0.75%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 0.75%   |
| Kingston SA400S37120G 120GB SSD                     | 2         | 0.75%   |
| Kingston OM8PCP3512F-AI1 512GB                      | 2         | 0.75%   |
| Apple SSD SM0256G 256GB                             | 2         | 0.75%   |
| WDC WDS500G2B0C-00PXH0 500GB                        | 1         | 0.38%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.38%   |
| WDC WDS256G1X0C-00ENX0 256GB                        | 1         | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 0.38%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                      | 1         | 0.38%   |
| WDC WDS100T2B0C-00PXH0 1TB                          | 1         | 0.38%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Computers | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 37        | 44     | 38.54%  |
| WDC                | 28        | 43     | 29.17%  |
| Toshiba            | 14        | 15     | 14.58%  |
| HGST               | 7         | 8      | 7.29%   |
| Hitachi            | 6         | 7      | 6.25%   |
| Maxtor             | 2         | 2      | 2.08%   |
| Unknown            | 1         | 1      | 1.04%   |
| JMicron Technology | 1         | 1      | 1.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 21     | 22.97%  |
| Kingston            | 12        | 12     | 16.22%  |
| Crucial             | 10        | 16     | 13.51%  |
| WDC                 | 5         | 8      | 6.76%   |
| China               | 5         | 5      | 6.76%   |
| SanDisk             | 3         | 3      | 4.05%   |
| Intel               | 3         | 4      | 4.05%   |
| Apple               | 3         | 4      | 4.05%   |
| SPCC                | 2         | 2      | 2.7%    |
| Linux               | 2         | 2      | 2.7%    |
| A-DATA Technology   | 2         | 2      | 2.7%    |
| Toshiba             | 1         | 1      | 1.35%   |
| SK hynix            | 1         | 1      | 1.35%   |
| PNY                 | 1         | 1      | 1.35%   |
| Plextor             | 1         | 1      | 1.35%   |
| Patriot             | 1         | 1      | 1.35%   |
| Netac               | 1         | 1      | 1.35%   |
| LDLC                | 1         | 5      | 1.35%   |
| Intenso             | 1         | 1      | 1.35%   |
| Goodram             | 1         | 1      | 1.35%   |
| AMD                 | 1         | 1      | 1.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 84        | 121    | 38.36%  |
| SSD     | 67        | 93     | 30.59%  |
| NVMe    | 64        | 96     | 29.22%  |
| Unknown | 3         | 6      | 1.37%   |
| MMC     | 1         | 1      | 0.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 116       | 212    | 62.03%  |
| NVMe | 63        | 95     | 33.69%  |
| SAS  | 7         | 9      | 3.74%   |
| MMC  | 1         | 1      | 0.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 77        | 110    | 49.68%  |
| 0.51-1.0   | 54        | 72     | 34.84%  |
| 1.01-2.0   | 13        | 15     | 8.39%   |
| 3.01-4.0   | 4         | 4      | 2.58%   |
| 2.01-3.0   | 4         | 4      | 2.58%   |
| 4.01-10.0  | 3         | 9      | 1.94%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 39        | 24.68%  |
| 251-500        | 33        | 20.89%  |
| 501-1000       | 23        | 14.56%  |
| 1001-2000      | 21        | 13.29%  |
| More than 3000 | 14        | 8.86%   |
| 2001-3000      | 10        | 6.33%   |
| 51-100         | 7         | 4.43%   |
| Unknown        | 5         | 3.16%   |
| 1-20           | 4         | 2.53%   |
| 21-50          | 2         | 1.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 40        | 24.1%   |
| 101-250        | 27        | 16.27%  |
| 501-1000       | 23        | 13.86%  |
| 251-500        | 20        | 12.05%  |
| 51-100         | 17        | 10.24%  |
| 21-50          | 15        | 9.04%   |
| 1001-2000      | 9         | 5.42%   |
| More than 3000 | 7         | 4.22%   |
| Unknown        | 5         | 3.01%   |
| 2001-3000      | 3         | 1.81%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 7.41%   |
| HGST HTS545050A7E680 500GB                       | 2         | 2      | 7.41%   |
| WDC WD3200LPVT-00FMCT0 320GB                     | 1         | 1      | 3.7%    |
| WDC WD3200AAKX-00ERMA0 320GB                     | 1         | 1      | 3.7%    |
| WDC WD30EZRX-00DC0B0 3TB                         | 1         | 1      | 3.7%    |
| WDC WD10SPCX-24HWST1 1TB                         | 1         | 1      | 3.7%    |
| Toshiba MK7575GSX 752GB                          | 1         | 1      | 3.7%    |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 3.7%    |
| Seagate ST8000DM004-2CX188 8TB                   | 1         | 1      | 3.7%    |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 3.7%    |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 3.7%    |
| Seagate ST2000DX002-2DV164 2TB                   | 1         | 1      | 3.7%    |
| Seagate ST2000DM006-2DM164 2TB                   | 1         | 1      | 3.7%    |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 3.7%    |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 3.7%    |
| Maxtor 6Y080M0 81GB                              | 1         | 1      | 3.7%    |
| LDLC SSD 120GB                                   | 1         | 3      | 3.7%    |
| Kingston SUV400S37240G 240GB SSD                 | 1         | 1      | 3.7%    |
| Kingston SA400S37120G 120GB SSD                  | 1         | 1      | 3.7%    |
| Intel SSDSC2BW480A4 480GB                        | 1         | 2      | 3.7%    |
| Intel SSDPEKKW128G7 128GB                        | 1         | 1      | 3.7%    |
| Hitachi HTS547550A9E384 500GB                    | 1         | 1      | 3.7%    |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 3.7%    |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 3.7%    |
| Hewlett-Packard SSD EX900 250GB                  | 1         | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 22.22%  |
| WDC                 | 4         | 4      | 14.81%  |
| Toshiba             | 4         | 4      | 14.81%  |
| HGST                | 3         | 3      | 11.11%  |
| Kingston            | 2         | 2      | 7.41%   |
| Intel               | 2         | 3      | 7.41%   |
| Hitachi             | 2         | 2      | 7.41%   |
| Samsung Electronics | 1         | 1      | 3.7%    |
| Maxtor              | 1         | 1      | 3.7%    |
| LDLC                | 1         | 3      | 3.7%    |
| Hewlett-Packard     | 1         | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 30%     |
| WDC     | 4         | 4      | 20%     |
| Toshiba | 4         | 4      | 20%     |
| HGST    | 3         | 3      | 15%     |
| Hitachi | 2         | 2      | 10%     |
| Maxtor  | 1         | 1      | 5%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 20        | 20     | 74.07%  |
| SSD  | 5         | 8      | 18.52%  |
| NVMe | 2         | 2      | 7.41%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 88        | 157    | 50%     |
| Detected | 62        | 130    | 35.23%  |
| Malfunc  | 26        | 30     | 14.77%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 87        | 41.23%  |
| AMD                            | 46        | 21.8%   |
| Samsung Electronics            | 26        | 12.32%  |
| SanDisk                        | 10        | 4.74%   |
| Phison Electronics             | 7         | 3.32%   |
| SK hynix                       | 6         | 2.84%   |
| Marvell Technology Group       | 6         | 2.84%   |
| Kingston Technology Company    | 5         | 2.37%   |
| Union Memory (Shenzhen)        | 3         | 1.42%   |
| ASMedia Technology             | 3         | 1.42%   |
| Toshiba America Info Systems   | 2         | 0.95%   |
| Silicon Motion                 | 2         | 0.95%   |
| Solid State Storage Technology | 1         | 0.47%   |
| Nvidia                         | 1         | 0.47%   |
| Micron/Crucial Technology      | 1         | 0.47%   |
| Micron Technology              | 1         | 0.47%   |
| Lite-On Technology             | 1         | 0.47%   |
| JMicron Technology             | 1         | 0.47%   |
| Broadcom / LSI                 | 1         | 0.47%   |
| ADATA Technology               | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 35        | 14.83%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15        | 6.36%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 3.81%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 3.39%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 3.39%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 2.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6         | 2.54%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 2.12%   |
| Phison E12 NVMe Controller                                                     | 5         | 2.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 2.12%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 2.12%   |
| AMD 300 Series Chipset SATA Controller                                         | 5         | 2.12%   |
| SK hynix Non-Volatile memory controller                                        | 4         | 1.69%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 1.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.69%   |
| Kingston Company Company Non-Volatile memory controller                        | 4         | 1.69%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.69%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.69%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 3         | 1.27%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 3         | 1.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.27%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.27%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 1.27%   |
| Intel SSD 660P Series                                                          | 3         | 1.27%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.27%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 3         | 1.27%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.27%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 1.27%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.85%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.85%   |
| Samsung Electronics SATA controller                                            | 2         | 0.85%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 0.85%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.85%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 0.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 2         | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 121       | 58.74%  |
| NVMe | 64        | 31.07%  |
| RAID | 12        | 5.83%   |
| IDE  | 8         | 3.88%   |
| SAS  | 1         | 0.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 104       | 67.53%  |
| AMD    | 50        | 32.47%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor         | 4         | 2.58%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 4         | 2.58%   |
| AMD FX-8350 Eight-Core Processor            | 4         | 2.58%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 3         | 1.94%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 2         | 1.29%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2         | 1.29%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 1.29%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 1.29%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1.29%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 1.29%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.29%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 1.29%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.29%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2         | 1.29%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 2         | 1.29%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 1.29%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 2         | 1.29%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.29%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.29%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 2         | 1.29%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 1.29%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.29%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 2         | 1.29%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2         | 1.29%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.29%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz        | 1         | 0.65%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.65%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.65%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.65%   |
| Intel Pentium CPU A1018 @ 2.10GHz           | 1         | 0.65%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 0.65%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz            | 1         | 0.65%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.65%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 1         | 0.65%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 0.65%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1         | 0.65%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.65%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 39        | 25.32%  |
| Intel Core i7           | 26        | 16.88%  |
| AMD Ryzen 7             | 17        | 11.04%  |
| AMD Ryzen 5             | 12        | 7.79%   |
| Intel Core i3           | 11        | 7.14%   |
| Intel Celeron           | 8         | 5.19%   |
| Other                   | 5         | 3.25%   |
| AMD Ryzen 9             | 5         | 3.25%   |
| AMD FX                  | 5         | 3.25%   |
| AMD Ryzen 3             | 4         | 2.6%    |
| Intel Pentium           | 3         | 1.95%   |
| Intel Core m3           | 3         | 1.95%   |
| Intel Core 2 Duo        | 3         | 1.95%   |
| Intel Core i9           | 2         | 1.3%    |
| Intel Xeon              | 1         | 0.65%   |
| Intel Pentium Silver    | 1         | 0.65%   |
| Intel Pentium Dual-Core | 1         | 0.65%   |
| Intel Atom              | 1         | 0.65%   |
| AMD Ryzen Threadripper  | 1         | 0.65%   |
| AMD Ryzen 5 PRO         | 1         | 0.65%   |
| AMD Phenom II X4        | 1         | 0.65%   |
| AMD E1                  | 1         | 0.65%   |
| AMD Athlon              | 1         | 0.65%   |
| AMD A6                  | 1         | 0.65%   |
| AMD A10                 | 1         | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 54        | 35.06%  |
| 4      | 48        | 31.17%  |
| 8      | 22        | 14.29%  |
| 6      | 22        | 14.29%  |
| 12     | 5         | 3.25%   |
| 3      | 2         | 1.3%    |
| 32     | 1         | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 154       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 113       | 73.38%  |
| 1      | 41        | 26.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 154       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 30        | 18.87%  |
| 0x206a7    | 10        | 6.29%   |
| 0x306a9    | 8         | 5.03%   |
| 0xa0652    | 5         | 3.14%   |
| 0x806e9    | 5         | 3.14%   |
| 0x40651    | 5         | 3.14%   |
| 0x08701013 | 5         | 3.14%   |
| 0x0800820d | 5         | 3.14%   |
| 0x906ed    | 4         | 2.52%   |
| 0x906e9    | 4         | 2.52%   |
| 0x806ec    | 4         | 2.52%   |
| 0x806ea    | 4         | 2.52%   |
| 0x806c1    | 4         | 2.52%   |
| 0x706a1    | 4         | 2.52%   |
| 0x306d4    | 4         | 2.52%   |
| 0x08600106 | 4         | 2.52%   |
| 0x906ea    | 3         | 1.89%   |
| 0x706e5    | 3         | 1.89%   |
| 0x506e3    | 3         | 1.89%   |
| 0x306c3    | 3         | 1.89%   |
| 0x1067a    | 3         | 1.89%   |
| 0x08701021 | 3         | 1.89%   |
| 0x06000822 | 3         | 1.89%   |
| 0xa0655    | 2         | 1.26%   |
| 0x30678    | 2         | 1.26%   |
| 0x08600103 | 2         | 1.26%   |
| 0x08108109 | 2         | 1.26%   |
| 0x06000852 | 2         | 1.26%   |
| 0xa0653    | 1         | 0.63%   |
| 0x806eb    | 1         | 0.63%   |
| 0x6fd      | 1         | 0.63%   |
| 0x506c9    | 1         | 0.63%   |
| 0x406e3    | 1         | 0.63%   |
| 0x206c2    | 1         | 0.63%   |
| 0x20655    | 1         | 0.63%   |
| 0x20652    | 1         | 0.63%   |
| 0x0a50000c | 1         | 0.63%   |
| 0x0a50000b | 1         | 0.63%   |
| 0x0a201016 | 1         | 0.63%   |
| 0x0a201009 | 1         | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 33        | 21.43%  |
| Zen 2         | 17        | 11.04%  |
| Zen+          | 11        | 7.14%   |
| SandyBridge   | 11        | 7.14%   |
| IvyBridge     | 10        | 6.49%   |
| Haswell       | 9         | 5.84%   |
| CometLake     | 9         | 5.84%   |
| Zen 3         | 6         | 3.9%    |
| Zen           | 6         | 3.9%    |
| Piledriver    | 5         | 3.25%   |
| Broadwell     | 5         | 3.25%   |
| TigerLake     | 4         | 2.6%    |
| Skylake       | 4         | 2.6%    |
| Goldmont plus | 4         | 2.6%    |
| Westmere      | 3         | 1.95%   |
| Penryn        | 3         | 1.95%   |
| IceLake       | 3         | 1.95%   |
| Silvermont    | 2         | 1.3%    |
| Unknown       | 2         | 1.3%    |
| Steamroller   | 1         | 0.65%   |
| Puma          | 1         | 0.65%   |
| K10           | 1         | 0.65%   |
| Jaguar        | 1         | 0.65%   |
| Goldmont      | 1         | 0.65%   |
| Core          | 1         | 0.65%   |
| Bonnell       | 1         | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 81        | 44.26%  |
| AMD    | 54        | 29.51%  |
| Nvidia | 48        | 26.23%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 9         | 4.86%   |
| AMD Renoir                                                                | 7         | 3.78%   |
| Intel HD Graphics 620                                                     | 6         | 3.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 3.24%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 6         | 3.24%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 3.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 6         | 3.24%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                   | 6         | 3.24%   |
| Intel UHD Graphics 620                                                    | 5         | 2.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 2.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 2.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 2.16%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 3         | 1.62%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 3         | 1.62%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 3         | 1.62%   |
| Intel HD Graphics 5500                                                    | 3         | 1.62%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 1.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 3         | 1.62%   |
| AMD Cezanne                                                               | 3         | 1.62%   |
| Nvidia TU117M                                                             | 2         | 1.08%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                          | 2         | 1.08%   |
| Nvidia GP104 [GeForce GTX 1080]                                           | 2         | 1.08%   |
| Nvidia GM206 [GeForce GTX 950]                                            | 2         | 1.08%   |
| Nvidia GM108M [GeForce 840M]                                              | 2         | 1.08%   |
| Intel UHD Graphics 615                                                    | 2         | 1.08%   |
| Intel HD Graphics 630                                                     | 2         | 1.08%   |
| Intel HD Graphics 6000                                                    | 2         | 1.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 2         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 1.08%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                    | 2         | 1.08%   |
| AMD Saturn XT [FirePro M6100]                                             | 2         | 1.08%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.08%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                | 2         | 1.08%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                            | 2         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 1         | 0.54%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                     | 1         | 0.54%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 1         | 0.54%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                    | 1         | 0.54%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                    | 1         | 0.54%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                     | 1         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 56        | 35.9%   |
| 1 x AMD        | 47        | 30.13%  |
| 1 x Nvidia     | 24        | 15.38%  |
| Intel + Nvidia | 21        | 13.46%  |
| Intel + AMD    | 3         | 1.92%   |
| AMD + Nvidia   | 3         | 1.92%   |
| 2 x AMD        | 2         | 1.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 126       | 80.77%  |
| Proprietary | 30        | 19.23%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 84        | 52.5%   |
| 1.01-2.0   | 18        | 11.25%  |
| 7.01-8.0   | 16        | 10%     |
| 3.01-4.0   | 14        | 8.75%   |
| 0.01-0.5   | 11        | 6.88%   |
| 0.51-1.0   | 9         | 5.63%   |
| 5.01-6.0   | 4         | 2.5%    |
| 8.01-16.0  | 3         | 1.88%   |
| 2.01-3.0   | 1         | 0.63%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 21        | 11.11%  |
| AU Optronics            | 21        | 11.11%  |
| BOE                     | 18        | 9.52%   |
| Samsung Electronics     | 17        | 8.99%   |
| Chimei Innolux          | 15        | 7.94%   |
| Acer                    | 11        | 5.82%   |
| Philips                 | 8         | 4.23%   |
| Goldstar                | 8         | 4.23%   |
| Dell                    | 8         | 4.23%   |
| BenQ                    | 7         | 3.7%    |
| ASUSTek Computer        | 7         | 3.7%    |
| AOC                     | 7         | 3.7%    |
| Chi Mei Optoelectronics | 4         | 2.12%   |
| InfoVision              | 3         | 1.59%   |
| Hewlett-Packard         | 3         | 1.59%   |
| Apple                   | 3         | 1.59%   |
| Ancor Communications    | 3         | 1.59%   |
| Sharp                   | 2         | 1.06%   |
| PANDA                   | 2         | 1.06%   |
| MSI                     | 2         | 1.06%   |
| ViewSonic               | 1         | 0.53%   |
| Vestel Elektronik       | 1         | 0.53%   |
| Sony                    | 1         | 0.53%   |
| Packard Bell            | 1         | 0.53%   |
| LGD                     | 1         | 0.53%   |
| Lenovo                  | 1         | 0.53%   |
| KTC                     | 1         | 0.53%   |
| KDC                     | 1         | 0.53%   |
| Jean                    | 1         | 0.53%   |
| Iiyama                  | 1         | 0.53%   |
| Idek Iiyama             | 1         | 0.53%   |
| HVR                     | 1         | 0.53%   |
| Hitachi                 | 1         | 0.53%   |
| Envision Peripherals    | 1         | 0.53%   |
| Eizo                    | 1         | 0.53%   |
| CTV                     | 1         | 0.53%   |
| CSO                     | 1         | 0.53%   |
| Compal                  | 1         | 0.53%   |
| Belinea                 | 1         | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 3         | 1.55%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 1.04%   |
| Philips PHL 245E1 PHLC20B 2560x1440 530x300mm 24.0-inch                   | 2         | 1.04%   |
| MSI G241VC MSI1462 1920x1080 521x294mm 23.6-inch                          | 2         | 1.04%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 2         | 1.04%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 1.04%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch          | 2         | 1.04%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 1.04%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                     | 2         | 1.04%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                     | 2         | 1.04%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                     | 2         | 1.04%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                      | 2         | 1.04%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 2         | 1.04%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 621x341mm 27.9-inch              | 2         | 1.04%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 2         | 1.04%   |
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                             | 2         | 1.04%   |
| Ancor Communications ASUS PB277 ACI27B5 2560x1440 597x336mm 27.0-inch     | 2         | 1.04%   |
| ViewSonic LCD Monitor VX2452 Series 3840x1080                             | 1         | 0.52%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch    | 1         | 0.52%   |
| Sony TV SNY7001 1920x1080                                                 | 1         | 0.52%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                   | 1         | 0.52%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 1         | 0.52%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch         | 1         | 0.52%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 521x293mm 23.5-inch         | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM047D 1360x768 410x230mm 18.5-inch       | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch       | 1         | 0.52%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch         | 1         | 0.52%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch         | 1         | 0.52%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch         | 1         | 0.52%   |
| Samsung Electronics S24A31x SAM7114 1920x1080 527x296mm 23.8-inch         | 1         | 0.52%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch         | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch      | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch     | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1872x1053mm 84.6-inch   | 1         | 0.52%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch         | 1         | 0.52%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch         | 1         | 0.52%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch         | 1         | 0.52%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch         | 1         | 0.52%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch                  | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 88        | 49.16%  |
| 1366x768 (WXGA)    | 35        | 19.55%  |
| 3840x2160 (4K)     | 15        | 8.38%   |
| 2560x1440 (QHD)    | 9         | 5.03%   |
| 1600x900 (HD+)     | 4         | 2.23%   |
| 1440x900 (WXGA+)   | 4         | 2.23%   |
| 3440x1440          | 3         | 1.68%   |
| 2560x1600          | 3         | 1.68%   |
| 2560x1080          | 2         | 1.12%   |
| 1920x1200 (WUXGA)  | 2         | 1.12%   |
| 1680x1050 (WSXGA+) | 2         | 1.12%   |
| 1280x1024 (SXGA)   | 2         | 1.12%   |
| Unknown            | 2         | 1.12%   |
| 3840x1080          | 1         | 0.56%   |
| 3600x1080          | 1         | 0.56%   |
| 2736x1824          | 1         | 0.56%   |
| 2160x1440          | 1         | 0.56%   |
| 2160x1200          | 1         | 0.56%   |
| 1360x768           | 1         | 0.56%   |
| 1280x960           | 1         | 0.56%   |
| 1024x768 (XGA)     | 1         | 0.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 50        | 27.03%  |
| 13      | 19        | 10.27%  |
| 27      | 16        | 8.65%   |
| 24      | 16        | 8.65%   |
| 14      | 16        | 8.65%   |
| 23      | 15        | 8.11%   |
| 21      | 12        | 6.49%   |
| 17      | 8         | 4.32%   |
| 34      | 5         | 2.7%    |
| Unknown | 5         | 2.7%    |
| 84      | 4         | 2.16%   |
| 19      | 4         | 2.16%   |
| 31      | 3         | 1.62%   |
| 32      | 2         | 1.08%   |
| 20      | 2         | 1.08%   |
| 16      | 2         | 1.08%   |
| 12      | 2         | 1.08%   |
| 72      | 1         | 0.54%   |
| 52      | 1         | 0.54%   |
| 18      | 1         | 0.54%   |
| 11      | 1         | 0.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 79        | 43.17%  |
| 501-600     | 42        | 22.95%  |
| 401-500     | 16        | 8.74%   |
| 351-400     | 13        | 7.1%    |
| 201-300     | 9         | 4.92%   |
| 701-800     | 7         | 3.83%   |
| 601-700     | 6         | 3.28%   |
| 1501-2000   | 5         | 2.73%   |
| Unknown     | 5         | 2.73%   |
| 1001-1500   | 1         | 0.55%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 134       | 82.72%  |
| 16/10   | 12        | 7.41%   |
| 21/9    | 5         | 3.09%   |
| Unknown | 4         | 2.47%   |
| 5/4     | 3         | 1.85%   |
| 4/3     | 2         | 1.23%   |
| 3/2     | 2         | 1.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 50        | 27.03%  |
| 201-250        | 39        | 21.08%  |
| 81-90          | 29        | 15.68%  |
| 301-350        | 16        | 8.65%   |
| 351-500        | 10        | 5.41%   |
| 71-80          | 7         | 3.78%   |
| 151-200        | 7         | 3.78%   |
| 121-130        | 7         | 3.78%   |
| More than 1000 | 6         | 3.24%   |
| Unknown        | 5         | 2.7%    |
| 251-300        | 3         | 1.62%   |
| 131-140        | 2         | 1.08%   |
| 61-70          | 1         | 0.54%   |
| 51-60          | 1         | 0.54%   |
| 141-150        | 1         | 0.54%   |
| 111-120        | 1         | 0.54%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 61        | 34.27%  |
| 51-100        | 52        | 29.21%  |
| 101-120       | 48        | 26.97%  |
| 161-240       | 9         | 5.06%   |
| Unknown       | 5         | 2.81%   |
| 1-50          | 2         | 1.12%   |
| More than 240 | 1         | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 126       | 79.75%  |
| 2     | 28        | 17.72%  |
| 3     | 3         | 1.9%    |
| 4     | 1         | 0.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 100       | 41.84%  |
| Intel                                 | 75        | 31.38%  |
| Qualcomm Atheros                      | 22        | 9.21%   |
| Broadcom                              | 9         | 3.77%   |
| Broadcom Limited                      | 4         | 1.67%   |
| TP-Link                               | 3         | 1.26%   |
| D-Link System                         | 3         | 1.26%   |
| Xiaomi                                | 2         | 0.84%   |
| Samsung Electronics                   | 2         | 0.84%   |
| Ralink Technology                     | 2         | 0.84%   |
| Ralink                                | 2         | 0.84%   |
| MediaTek                              | 2         | 0.84%   |
| Sierra Wireless                       | 1         | 0.42%   |
| Qualcomm Atheros Communications       | 1         | 0.42%   |
| Qualcomm                              | 1         | 0.42%   |
| OPPO Electronics                      | 1         | 0.42%   |
| Microsoft                             | 1         | 0.42%   |
| Marvell Technology Group              | 1         | 0.42%   |
| Linksys                               | 1         | 0.42%   |
| Huawei Technologies                   | 1         | 0.42%   |
| Google                                | 1         | 0.42%   |
| DisplayLink                           | 1         | 0.42%   |
| Aquantia                              | 1         | 0.42%   |
| Apple                                 | 1         | 0.42%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 69        | 24.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 4.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 2.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.46%   |
| Intel Wireless 8265 / 8275                                        | 7         | 2.46%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.46%   |
| Intel I211 Gigabit Network Connection                             | 7         | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.11%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 2.11%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.75%   |
| Intel Wireless 7265                                               | 5         | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.4%    |
| Realtek 802.11ac NIC                                              | 3         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.05%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.05%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.05%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 1.05%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.05%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 2         | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.7%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.7%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.7%    |
| Intel Wireless-AC 9260                                            | 2         | 0.7%    |
| Intel Wireless 7260                                               | 2         | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.7%    |
| Intel Centrino Wireless-N 2230                                    | 2         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 59        | 44.7%   |
| Realtek Semiconductor                 | 28        | 21.21%  |
| Qualcomm Atheros                      | 18        | 13.64%  |
| Broadcom                              | 8         | 6.06%   |
| Broadcom Limited                      | 4         | 3.03%   |
| TP-Link                               | 3         | 2.27%   |
| Ralink Technology                     | 2         | 1.52%   |
| Ralink                                | 2         | 1.52%   |
| MediaTek                              | 2         | 1.52%   |
| Sierra Wireless                       | 1         | 0.76%   |
| Qualcomm Atheros Communications       | 1         | 0.76%   |
| Microsoft                             | 1         | 0.76%   |
| Marvell Technology Group              | 1         | 0.76%   |
| D-Link System                         | 1         | 0.76%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 7         | 5.26%   |
| Intel Wireless 8265 / 8275                                    | 7         | 5.26%   |
| Intel Wi-Fi 6 AX200                                           | 7         | 5.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 6         | 4.51%   |
| Intel Comet Lake PCH CNVi WiFi                                | 6         | 4.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 5         | 3.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 5         | 3.76%   |
| Intel Wireless 7265                                           | 5         | 3.76%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 3.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 4         | 3.01%   |
| Realtek 802.11ac NIC                                          | 3         | 2.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 2.26%   |
| Intel Wi-Fi 6 AX201                                           | 3         | 2.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 3         | 2.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 3         | 2.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 3         | 2.26%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter    | 3         | 2.26%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 2         | 1.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 2         | 1.5%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 2         | 1.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 2         | 1.5%    |
| Realtek RTL8188EE Wireless Network Adapter                    | 2         | 1.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 2         | 1.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 1.5%    |
| Intel Wireless-AC 9260                                        | 2         | 1.5%    |
| Intel Wireless 7260                                           | 2         | 1.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 2         | 1.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 2         | 1.5%    |
| Intel Centrino Wireless-N 2230                                | 2         | 1.5%    |
| Broadcom BCM43228 802.11a/b/g/n                               | 2         | 1.5%    |
| Broadcom BCM43142 802.11b/g/n                                 | 2         | 1.5%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                           | 1         | 0.75%   |
| Sierra Wireless MC7750                                        | 1         | 0.75%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 1         | 0.75%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 1         | 0.75%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                       | 1         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1         | 0.75%   |
| Realtek 802.11n WLAN Adapter                                  | 1         | 0.75%   |
| Ralink RT5370 Wireless Adapter                                | 1         | 0.75%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 89        | 60.96%  |
| Intel                 | 35        | 23.97%  |
| Qualcomm Atheros      | 7         | 4.79%   |
| Xiaomi                | 2         | 1.37%   |
| Samsung Electronics   | 2         | 1.37%   |
| D-Link System         | 2         | 1.37%   |
| Qualcomm              | 1         | 0.68%   |
| OPPO Electronics      | 1         | 0.68%   |
| Linksys               | 1         | 0.68%   |
| Huawei Technologies   | 1         | 0.68%   |
| Google                | 1         | 0.68%   |
| DisplayLink           | 1         | 0.68%   |
| Broadcom              | 1         | 0.68%   |
| Aquantia              | 1         | 0.68%   |
| Apple                 | 1         | 0.68%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 69        | 45.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 8.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 5.26%   |
| Intel I211 Gigabit Network Connection                             | 7         | 4.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 4.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.97%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.97%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 1.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.32%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 1.32%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.32%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 2         | 1.32%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.66%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.66%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.66%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.66%   |
| Qualcomm A0001                                                    | 1         | 0.66%   |
| OPPO RMX2180                                                      | 1         | 0.66%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.66%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.66%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.66%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.66%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.66%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.66%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.66%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 0.66%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.66%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.66%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1         | 0.66%   |
| Intel 82562V-2 10/100 Network Connection                          | 1         | 0.66%   |
| Huawei E353/E3131                                                 | 1         | 0.66%   |
| Google Nexus/Pixel Device (tether+ debug)                         | 1         | 0.66%   |
| DisplayLink Kensington Dock (Composite Device)                    | 1         | 0.66%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.66%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 131       | 50.97%  |
| WiFi     | 126       | 49.03%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 95        | 60.13%  |
| Ethernet | 63        | 39.87%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 91        | 58.71%  |
| 1     | 59        | 38.06%  |
| 4     | 2         | 1.29%   |
| 3     | 2         | 1.29%   |
| 0     | 1         | 0.65%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 138       | 87.34%  |
| Yes  | 20        | 12.66%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 51        | 48.57%  |
| Realtek Semiconductor           | 14        | 13.33%  |
| Broadcom                        | 7         | 6.67%   |
| IMC Networks                    | 6         | 5.71%   |
| Qualcomm Atheros Communications | 5         | 4.76%   |
| Cambridge Silicon Radio         | 5         | 4.76%   |
| Lite-On Technology              | 4         | 3.81%   |
| Foxconn / Hon Hai               | 3         | 2.86%   |
| Apple                           | 3         | 2.86%   |
| Realtek                         | 2         | 1.9%    |
| ASUSTek Computer                | 2         | 1.9%    |
| Ralink                          | 1         | 0.95%   |
| Marvell Semiconductor           | 1         | 0.95%   |
| HTC (High Tech Computer)        | 1         | 0.95%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 15        | 14.29%  |
| Intel AX201 Bluetooth                                                | 12        | 11.43%  |
| Realtek Bluetooth Radio                                              | 9         | 8.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 9         | 8.57%   |
| Intel AX200 Bluetooth                                                | 7         | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 5         | 4.76%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 4         | 3.81%   |
| Qualcomm Atheros  Bluetooth Device                                   | 4         | 3.81%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 3         | 2.86%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 3         | 2.86%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 3         | 2.86%   |
| Realtek Bluetooth Radio                                              | 2         | 1.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2         | 1.9%    |
| Intel Centrino Bluetooth Wireless Transceiver                        | 2         | 1.9%    |
| IMC Networks Wireless_Device                                         | 2         | 1.9%    |
| IMC Networks Bluetooth Radio                                         | 2         | 1.9%    |
| IMC Networks Bluetooth Device                                        | 2         | 1.9%    |
| Foxconn / Hon Hai BCM20702A0                                         | 2         | 1.9%    |
| Apple Bluetooth USB Host Controller                                  | 2         | 1.9%    |
| Realtek RTL8821A Bluetooth                                           | 1         | 0.95%   |
| Ralink RT3290 Bluetooth                                              | 1         | 0.95%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 0.95%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 1         | 0.95%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                         | 1         | 0.95%   |
| Intel AX210 Bluetooth                                                | 1         | 0.95%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.95%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 1         | 0.95%   |
| Broadcom HP Portable Valentine                                       | 1         | 0.95%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1         | 0.95%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 1         | 0.95%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 1         | 0.95%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1         | 0.95%   |
| ASUS Bluetooth Radio                                                 | 1         | 0.95%   |
| Apple Bluetooth Host Controller                                      | 1         | 0.95%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 102       | 43.4%   |
| AMD                                             | 61        | 25.96%  |
| Nvidia                                          | 38        | 16.17%  |
| C-Media Electronics                             | 10        | 4.26%   |
| Realtek Semiconductor                           | 4         | 1.7%    |
| Creative Labs                                   | 3         | 1.28%   |
| Logitech                                        | 2         | 0.85%   |
| Creative Technology                             | 2         | 0.85%   |
| Corsair                                         | 2         | 0.85%   |
| TC Electronic                                   | 1         | 0.43%   |
| SteelSeries ApS                                 | 1         | 0.43%   |
| Razer USA                                       | 1         | 0.43%   |
| Plantronics                                     | 1         | 0.43%   |
| Native Instruments                              | 1         | 0.43%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.43%   |
| Harman                                          | 1         | 0.43%   |
| Generalplus Technology                          | 1         | 0.43%   |
| Focusrite-Novation                              | 1         | 0.43%   |
| EVGA                                            | 1         | 0.43%   |
| AudioQuest                                      | 1         | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 19        | 6.55%   |
| Intel Sunrise Point-LP HD Audio                                            | 15        | 5.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 3.79%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11        | 3.79%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 3.79%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 3.45%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10        | 3.45%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9         | 3.1%    |
| Intel Comet Lake PCH cAVS                                                  | 7         | 2.41%   |
| AMD Navi 10 HDMI Audio                                                     | 7         | 2.41%   |
| Intel Haswell-ULT HD Audio Controller                                      | 6         | 2.07%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 2.07%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 2.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.07%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 1.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.72%   |
| Intel Cannon Lake PCH cAVS                                                 | 5         | 1.72%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.72%   |
| Nvidia TU116 High Definition Audio Controller                              | 4         | 1.38%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.38%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 1.38%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.38%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.38%   |
| C-Media Electronics USB Audio Device                                       | 4         | 1.38%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4         | 1.38%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 1.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.03%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.03%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 3         | 1.03%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 1.03%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.03%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.69%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.69%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.69%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 33        | 20.63%  |
| SK hynix            | 31        | 19.38%  |
| Kingston            | 21        | 13.13%  |
| Corsair             | 14        | 8.75%   |
| Micron Technology   | 11        | 6.88%   |
| G.Skill             | 10        | 6.25%   |
| Unknown             | 7         | 4.38%   |
| Crucial             | 5         | 3.13%   |
| A-DATA Technology   | 5         | 3.13%   |
| Patriot             | 4         | 2.5%    |
| Silicon Power       | 3         | 1.88%   |
| Unknown             | 3         | 1.88%   |
| Unknown (ABCD)      | 2         | 1.25%   |
| Smart               | 2         | 1.25%   |
| Ramaxel Technology  | 2         | 1.25%   |
| Nanya Technology    | 2         | 1.25%   |
| Transcend           | 1         | 0.63%   |
| Team                | 1         | 0.63%   |
| Smart Brazil        | 1         | 0.63%   |
| ASint Technology    | 1         | 0.63%   |
| AMD                 | 1         | 0.63%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 2.37%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.78%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.78%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 1.78%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 3         | 1.78%   |
| Unknown                                                          | 3         | 1.78%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.18%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.18%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.18%   |
| SK hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.18%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.18%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.18%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 2         | 1.18%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 2         | 1.18%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 1.18%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.18%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 1.18%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 2         | 1.18%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.18%   |
| Kingston RAM 99U5474-026.A00LF 4GB DIMM DDR3 1333MT/s            | 2         | 1.18%   |
| G.Skill RAM F3-10666CL9-4GBNT 4GB DIMM DDR3 1600MT/s             | 2         | 1.18%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s         | 2         | 1.18%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 2         | 1.18%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 2         | 1.18%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.59%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.59%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.59%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.59%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.59%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                          | 1         | 0.59%   |
| Unknown RAM MEM-DOWN 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.59%   |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s              | 1         | 0.59%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.59%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 1         | 0.59%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2400MT/s            | 1         | 0.59%   |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 2933MT/s  | 1         | 0.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.59%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.59%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.59%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 77        | 57.89%  |
| DDR3    | 42        | 31.58%  |
| LPDDR4  | 4         | 3.01%   |
| SDRAM   | 3         | 2.26%   |
| LPDDR3  | 3         | 2.26%   |
| Unknown | 3         | 2.26%   |
| DDR2    | 1         | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 77        | 57.46%  |
| DIMM         | 45        | 33.58%  |
| Row Of Chips | 10        | 7.46%   |
| Chip         | 1         | 0.75%   |
| Unknown      | 1         | 0.75%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 55        | 36.42%  |
| 4096  | 54        | 35.76%  |
| 16384 | 22        | 14.57%  |
| 2048  | 15        | 9.93%   |
| 32768 | 3         | 1.99%   |
| 1024  | 2         | 1.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 34        | 23.78%  |
| 3200    | 30        | 20.98%  |
| 2667    | 22        | 15.38%  |
| 2400    | 14        | 9.79%   |
| 1333    | 9         | 6.29%   |
| 3600    | 7         | 4.9%    |
| 2133    | 5         | 3.5%    |
| 2933    | 3         | 2.1%    |
| 1334    | 3         | 2.1%    |
| 4199    | 2         | 1.4%    |
| 3466    | 2         | 1.4%    |
| 3266    | 2         | 1.4%    |
| 4267    | 1         | 0.7%    |
| 4133    | 1         | 0.7%    |
| 3400    | 1         | 0.7%    |
| 2800    | 1         | 0.7%    |
| 2481    | 1         | 0.7%    |
| 2465    | 1         | 0.7%    |
| 1328    | 1         | 0.7%    |
| 1066    | 1         | 0.7%    |
| 800     | 1         | 0.7%    |
| Unknown | 1         | 0.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Ricoh              | 1         | 33.33%  |
| Hewlett-Packard    | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 19        | 18.81%  |
| Acer                                   | 10        | 9.9%    |
| Realtek Semiconductor                  | 9         | 8.91%   |
| Quanta                                 | 9         | 8.91%   |
| IMC Networks                           | 8         | 7.92%   |
| Suyin                                  | 6         | 5.94%   |
| Logitech                               | 5         | 4.95%   |
| Syntek                                 | 4         | 3.96%   |
| Sunplus Innovation Technology          | 4         | 3.96%   |
| Alcor Micro                            | 4         | 3.96%   |
| Microdia                               | 3         | 2.97%   |
| Luxvisions Innotech Limited            | 3         | 2.97%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.97%   |
| Sonix Technology                       | 2         | 1.98%   |
| Silicon Motion                         | 2         | 1.98%   |
| Creative Technology                    | 2         | 1.98%   |
| WaveRider Communications               | 1         | 0.99%   |
| Microsoft                              | 1         | 0.99%   |
| Lite-On Technology                     | 1         | 0.99%   |
| LG Electronics                         | 1         | 0.99%   |
| Lenovo                                 | 1         | 0.99%   |
| KYE Systems (Mouse Systems)            | 1         | 0.99%   |
| GEMBIRD                                | 1         | 0.99%   |
| ARC International                      | 1         | 0.99%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                       | 6         | 5.94%   |
| Chicony HD WebCam                                    | 6         | 5.94%   |
| Realtek Integrated_Webcam_HD                         | 4         | 3.96%   |
| Chicony Integrated Camera                            | 4         | 3.96%   |
| Acer Integrated Camera                               | 4         | 3.96%   |
| Syntek Integrated Camera                             | 2         | 1.98%   |
| Syntek EasyCamera                                    | 2         | 1.98%   |
| Suyin HP Webcam                                      | 2         | 1.98%   |
| Sonix USB2.0 HD UVC WebCam                           | 2         | 1.98%   |
| Silicon Motion 300k Pixel Camera                     | 2         | 1.98%   |
| Realtek USB2.0 HD UVC WebCam                         | 2         | 1.98%   |
| Realtek HD WebCam                                    | 2         | 1.98%   |
| Quanta VGA WebCam                                    | 2         | 1.98%   |
| Quanta HP Webcam                                     | 2         | 1.98%   |
| Quanta HP TrueVision HD Camera                       | 2         | 1.98%   |
| Microdia Integrated Webcam                           | 2         | 1.98%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 2         | 1.98%   |
| Logitech Webcam C270                                 | 2         | 1.98%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 1.98%   |
| Chicony Integrated Camera (1280x720@30)              | 2         | 1.98%   |
| WaveRider USB 2.0 Camera                             | 1         | 0.99%   |
| Suyin USB Webcam                                     | 1         | 0.99%   |
| Suyin NEC HD WebCam                                  | 1         | 0.99%   |
| Suyin Laptop_Integrated_Webcam_HD                    | 1         | 0.99%   |
| Suyin 1.3M HD WebCam                                 | 1         | 0.99%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 0.99%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 0.99%   |
| Sunplus HD WebCam                                    | 1         | 0.99%   |
| Sunplus Aukey-PC-LM1E Camera                         | 1         | 0.99%   |
| Realtek Integrated Webcam                            | 1         | 0.99%   |
| Quanta USB2.0 VGA UVC WebCam                         | 1         | 0.99%   |
| Quanta HD Webcam                                     | 1         | 0.99%   |
| Quanta HD User Facing                                | 1         | 0.99%   |
| Microsoft LifeCam Cinema                             | 1         | 0.99%   |
| Microdia Integrated_Webcam_HD                        | 1         | 0.99%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 0.99%   |
| Logitech Webcam C930e                                | 1         | 0.99%   |
| Logitech Webcam C310                                 | 1         | 0.99%   |
| Logitech HD Webcam C910                              | 1         | 0.99%   |
| Lite-On HP HD Camera                                 | 1         | 0.99%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 4         | 50%     |
| Synaptics                  | 3         | 37.5%   |
| AuthenTec                  | 1         | 12.5%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 37.5%   |
| Shenzhen Goodix  FingerPrint Device               | 3         | 37.5%   |
| Shenzhen Goodix Fingerprint Reader                | 1         | 12.5%   |
| AuthenTec AES2810                                 | 1         | 12.5%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 5         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 118       | 75.16%  |
| 1     | 34        | 21.66%  |
| 2     | 5         | 3.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 8         | 18.18%  |
| Net/wireless             | 6         | 13.64%  |
| Graphics card            | 6         | 13.64%  |
| Camera                   | 5         | 11.36%  |
| Multimedia controller    | 4         | 9.09%   |
| Chipcard                 | 4         | 9.09%   |
| Bluetooth                | 4         | 9.09%   |
| Storage                  | 2         | 4.55%   |
| Communication controller | 2         | 4.55%   |
| Unassigned class         | 1         | 2.27%   |
| Network                  | 1         | 2.27%   |
| Dvb card                 | 1         | 2.27%   |

