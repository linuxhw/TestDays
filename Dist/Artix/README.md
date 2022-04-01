Artix - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Artix.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Artix/Desktop/README.md) and [notebooks](/Dist/Artix/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 199

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Acer          | Swift SF314-59              | Notebook    | [0107549144](https://linux-hardware.org/?probe=0107549144) | Sep 23, 2021 |
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
| Dell          | Precision 7550              | Notebook    | [e7ccee4869](https://linux-hardware.org/?probe=e7ccee4869) | May 23, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [cc7cb4a34e](https://linux-hardware.org/?probe=cc7cb4a34e) | May 22, 2021 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [62d883cffd](https://linux-hardware.org/?probe=62d883cffd) | May 18, 2021 |
| Lenovo        | IdeaPad Flex 5 14ARE05 8... | Convertible | [3f10e6610b](https://linux-hardware.org/?probe=3f10e6610b) | May 18, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [2b91e357ca](https://linux-hardware.org/?probe=2b91e357ca) | May 16, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [85def78a94](https://linux-hardware.org/?probe=85def78a94) | May 02, 2021 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [057546c50e](https://linux-hardware.org/?probe=057546c50e) | Apr 30, 2021 |
| HP            | Laptop 17z-ca300            | Notebook    | [ea09357867](https://linux-hardware.org/?probe=ea09357867) | Apr 26, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [d1cf148ec4](https://linux-hardware.org/?probe=d1cf148ec4) | Apr 24, 2021 |
| Acer          | Aspire V3-572PG             | Notebook    | [a874b34c2a](https://linux-hardware.org/?probe=a874b34c2a) | Apr 12, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [132c1a0515](https://linux-hardware.org/?probe=132c1a0515) | Apr 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5527015fb6](https://linux-hardware.org/?probe=5527015fb6) | Apr 08, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [1517cb82a3](https://linux-hardware.org/?probe=1517cb82a3) | Apr 08, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [10132d3ee3](https://linux-hardware.org/?probe=10132d3ee3) | Apr 05, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [aa8705aaf3](https://linux-hardware.org/?probe=aa8705aaf3) | Apr 03, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [971fa8e337](https://linux-hardware.org/?probe=971fa8e337) | Mar 29, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [f9085ca63b](https://linux-hardware.org/?probe=f9085ca63b) | Mar 29, 2021 |
| Microsoft     | Surface Pro                 | Tablet      | [dbd940a4f3](https://linux-hardware.org/?probe=dbd940a4f3) | Mar 29, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [7f14077ecc](https://linux-hardware.org/?probe=7f14077ecc) | Mar 29, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [666815417c](https://linux-hardware.org/?probe=666815417c) | Mar 28, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [62f6aa5c03](https://linux-hardware.org/?probe=62f6aa5c03) | Mar 27, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [cc467b4015](https://linux-hardware.org/?probe=cc467b4015) | Mar 27, 2021 |
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
| MSI           | X470 GAMING PLUS            | Desktop     | [249558c27b](https://linux-hardware.org/?probe=249558c27b) | Feb 03, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b4c4d7f99c](https://linux-hardware.org/?probe=b4c4d7f99c) | Feb 01, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [70eabb568f](https://linux-hardware.org/?probe=70eabb568f) | Jan 30, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [b15b48fb21](https://linux-hardware.org/?probe=b15b48fb21) | Jan 29, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [fb3e2ec12b](https://linux-hardware.org/?probe=fb3e2ec12b) | Jan 24, 2021 |
| Lenovo        | ThinkPad W500 4063CJ5       | Notebook    | [dd81f9c015](https://linux-hardware.org/?probe=dd81f9c015) | Jan 23, 2021 |
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
| Pegatron      | 2AC2A                       | Desktop     | [2b102aeb94](https://linux-hardware.org/?probe=2b102aeb94) | Jan 03, 2021 |
| Acer          | Aspire A315-53              | Notebook    | [abac7a5b07](https://linux-hardware.org/?probe=abac7a5b07) | Jan 02, 2021 |
| Pegatron      | 2AC2A                       | Desktop     | [7dd04be8aa](https://linux-hardware.org/?probe=7dd04be8aa) | Jan 01, 2021 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [3f9f87f288](https://linux-hardware.org/?probe=3f9f87f288) | Dec 31, 2020 |
| Dell          | Precision 7550              | Notebook    | [9c8b2f2ad6](https://linux-hardware.org/?probe=9c8b2f2ad6) | Dec 30, 2020 |
| Gigabyte      | B450M DS3H-CF               | Notebook    | [b9c02872aa](https://linux-hardware.org/?probe=b9c02872aa) | Dec 29, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [2acc15f485](https://linux-hardware.org/?probe=2acc15f485) | Dec 27, 2020 |
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
| MSI           | Z87-G45 GAMING              | Desktop     | [de66a21bba](https://linux-hardware.org/?probe=de66a21bba) | Nov 25, 2020 |
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
| Dell          | Precision 7550              | Notebook    | [4b12417b4c](https://linux-hardware.org/?probe=4b12417b4c) | Sep 15, 2020 |
| ASUSTek       | G11CD                       | Desktop     | [962d52b690](https://linux-hardware.org/?probe=962d52b690) | Sep 14, 2020 |
| ASUSTek       | G11CD                       | Desktop     | [a663586db5](https://linux-hardware.org/?probe=a663586db5) | Sep 14, 2020 |
| Dell          | Precision 7550              | Notebook    | [14d1876313](https://linux-hardware.org/?probe=14d1876313) | Aug 31, 2020 |
| Dell          | Precision 7550              | Notebook    | [d44c1dbf60](https://linux-hardware.org/?probe=d44c1dbf60) | Aug 31, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [86215bb4fb](https://linux-hardware.org/?probe=86215bb4fb) | Aug 29, 2020 |
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
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [a57e5d7e84](https://linux-hardware.org/?probe=a57e5d7e84) | Jul 08, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [2e81cb3b86](https://linux-hardware.org/?probe=2e81cb3b86) | Jul 08, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [0af3ac770f](https://linux-hardware.org/?probe=0af3ac770f) | Jul 06, 2020 |
| Notebook      | N130BU                      | Notebook    | [e1b81e4880](https://linux-hardware.org/?probe=e1b81e4880) | Jul 05, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [051fa5784a](https://linux-hardware.org/?probe=051fa5784a) | Jul 02, 2020 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [7cb20a8170](https://linux-hardware.org/?probe=7cb20a8170) | Jul 01, 2020 |
| Intel         | DX58SO2 AAG10925-205        | Desktop     | [2e4066d769](https://linux-hardware.org/?probe=2e4066d769) | Jun 30, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [9623b5be2b](https://linux-hardware.org/?probe=9623b5be2b) | Jun 16, 2020 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [efaa58fcc8](https://linux-hardware.org/?probe=efaa58fcc8) | Jun 14, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [4125763b79](https://linux-hardware.org/?probe=4125763b79) | Jun 12, 2020 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [b5fee1bf94](https://linux-hardware.org/?probe=b5fee1bf94) | Jun 12, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [82af1cec2f](https://linux-hardware.org/?probe=82af1cec2f) | May 30, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [7ef5aff67e](https://linux-hardware.org/?probe=7ef5aff67e) | May 24, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [4d62228056](https://linux-hardware.org/?probe=4d62228056) | May 22, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [0a92fa05fc](https://linux-hardware.org/?probe=0a92fa05fc) | May 22, 2020 |
| Acer          | Aspire E5-575G              | Notebook    | [cd633c729b](https://linux-hardware.org/?probe=cd633c729b) | Apr 29, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [40adc1a5f5](https://linux-hardware.org/?probe=40adc1a5f5) | Apr 03, 2020 |
| Dell          | Precision 3540              | Notebook    | [3e582eb1b9](https://linux-hardware.org/?probe=3e582eb1b9) | Mar 30, 2020 |
| Dell          | Precision 3540              | Notebook    | [6b57174c98](https://linux-hardware.org/?probe=6b57174c98) | Mar 21, 2020 |
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
| Artix Rolling  | 76        | 60.8%   |
| Artix          | 45        | 36%     |
| Artix 20210726 | 2         | 1.6%    |
| Artix 20201207 | 1         | 0.8%    |
| Artix 20201128 | 1         | 0.8%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Artix | 119       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.9.14-artix1-1                 | 8         | 5.52%   |
| 5.7.6-artix1-1                  | 5         | 3.45%   |
| 5.7.12-artix1-1                 | 4         | 2.76%   |
| 5.15.12-artix1-1                | 4         | 2.76%   |
| 5.12.12-artix1-1                | 4         | 2.76%   |
| 5.10.8-artix1-1                 | 4         | 2.76%   |
| 5.10.4-artix2-1                 | 4         | 2.76%   |
| 5.8.8-artix1-1                  | 3         | 2.07%   |
| 5.8.12-artix1-1                 | 3         | 2.07%   |
| 5.16.3-artix1-1                 | 3         | 2.07%   |
| 5.16.10-artix1-1                | 3         | 2.07%   |
| 5.12.8-artix1-1                 | 3         | 2.07%   |
| 5.12.14-artix1-1                | 3         | 2.07%   |
| 5.10.6-artix1-1                 | 3         | 2.07%   |
| 5.10.16-artix1-1                | 3         | 2.07%   |
| 5.9.14-zen1-1-zen               | 2         | 1.38%   |
| 5.9.12-artix1-1                 | 2         | 1.38%   |
| 5.9.10-artix1-1                 | 2         | 1.38%   |
| 5.8.14-artix1-1                 | 2         | 1.38%   |
| 5.7.2-artix1-1                  | 2         | 1.38%   |
| 5.16.8-artix1-2                 | 2         | 1.38%   |
| 5.16.1-artix1-1                 | 2         | 1.38%   |
| 5.15.3-zen1-1-zen               | 2         | 1.38%   |
| 5.14.16-artix1-1                | 2         | 1.38%   |
| 5.13.8-artix1-1                 | 2         | 1.38%   |
| 5.12.4-artix1-1                 | 2         | 1.38%   |
| 5.12.12-zen1-1-zen              | 2         | 1.38%   |
| 5.11.6-artix1-1                 | 2         | 1.38%   |
| 5.11.10-artix1-1                | 2         | 1.38%   |
| 4.19.0-1-MANJARO                | 2         | 1.38%   |
| 5.9.8-zen1-1-zen                | 1         | 0.69%   |
| 5.9.6-artix1-1                  | 1         | 0.69%   |
| 5.9.1-artix1-1                  | 1         | 0.69%   |
| 5.9.0-zen1-1-zen                | 1         | 0.69%   |
| 5.9.0-1-mainline-bootsplash     | 1         | 0.69%   |
| 5.8.5-xanmod1-1-xanmod          | 1         | 0.69%   |
| 5.8.4-artix1-1                  | 1         | 0.69%   |
| 5.8.14-zen1-1-zen               | 1         | 0.69%   |
| 5.8.0-rc7-5-mainline-bootsplash | 1         | 0.69%   |
| 5.7.8-artix1-1                  | 1         | 0.69%   |
| 5.6.7-x86_64                    | 1         | 0.69%   |
| 5.5.3-artix1-1                  | 1         | 0.69%   |
| 5.5.10-artix1-1                 | 1         | 0.69%   |
| 5.4.74-1-lts                    | 1         | 0.69%   |
| 5.16.8-zen1-1-zen               | 1         | 0.69%   |
| 5.16.7-artix1-1                 | 1         | 0.69%   |
| 5.16.12-artix1-1                | 1         | 0.69%   |
| 5.16.0-arch1-g400s              | 1         | 0.69%   |
| 5.15.8-artix1-1                 | 1         | 0.69%   |
| 5.15.7-zen1-1-zen               | 1         | 0.69%   |
| 5.15.5-zen1-1-zen               | 1         | 0.69%   |
| 5.15.4-artix1-1                 | 1         | 0.69%   |
| 5.15.2-zen1-1-zen               | 1         | 0.69%   |
| 5.15.16-1-lts                   | 1         | 0.69%   |
| 5.15.13-zen1-1-zen              | 1         | 0.69%   |
| 5.15.12-zen1-1-zen              | 1         | 0.69%   |
| 5.14.7-zen1-1-zen               | 1         | 0.69%   |
| 5.14.3-198-tkg-bmq              | 1         | 0.69%   |
| 5.14.14-zen1-1-zen              | 1         | 0.69%   |
| 5.14.14-artix1-1                | 1         | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.14  | 10        | 6.9%    |
| 5.12.12 | 6         | 4.14%   |
| 5.7.6   | 5         | 3.45%   |
| 5.15.12 | 5         | 3.45%   |
| 5.7.12  | 4         | 2.76%   |
| 5.12.8  | 4         | 2.76%   |
| 5.12.14 | 4         | 2.76%   |
| 5.10.8  | 4         | 2.76%   |
| 5.10.4  | 4         | 2.76%   |
| 5.8.8   | 3         | 2.07%   |
| 5.8.14  | 3         | 2.07%   |
| 5.8.12  | 3         | 2.07%   |
| 5.16.8  | 3         | 2.07%   |
| 5.16.3  | 3         | 2.07%   |
| 5.16.10 | 3         | 2.07%   |
| 5.13.8  | 3         | 2.07%   |
| 5.10.6  | 3         | 2.07%   |
| 5.10.16 | 3         | 2.07%   |
| 5.9.12  | 2         | 1.38%   |
| 5.9.10  | 2         | 1.38%   |
| 5.9.0   | 2         | 1.38%   |
| 5.7.2   | 2         | 1.38%   |
| 5.16.1  | 2         | 1.38%   |
| 5.15.3  | 2         | 1.38%   |
| 5.14.16 | 2         | 1.38%   |
| 5.14.14 | 2         | 1.38%   |
| 5.12.4  | 2         | 1.38%   |
| 5.11.6  | 2         | 1.38%   |
| 5.11.16 | 2         | 1.38%   |
| 5.11.10 | 2         | 1.38%   |
| 5.10.15 | 2         | 1.38%   |
| 4.19.0  | 2         | 1.38%   |
| 5.9.8   | 1         | 0.69%   |
| 5.9.6   | 1         | 0.69%   |
| 5.9.1   | 1         | 0.69%   |
| 5.8.5   | 1         | 0.69%   |
| 5.8.4   | 1         | 0.69%   |
| 5.8.0   | 1         | 0.69%   |
| 5.7.8   | 1         | 0.69%   |
| 5.6.7   | 1         | 0.69%   |
| 5.5.3   | 1         | 0.69%   |
| 5.5.10  | 1         | 0.69%   |
| 5.4.74  | 1         | 0.69%   |
| 5.16.7  | 1         | 0.69%   |
| 5.16.12 | 1         | 0.69%   |
| 5.16.0  | 1         | 0.69%   |
| 5.15.8  | 1         | 0.69%   |
| 5.15.7  | 1         | 0.69%   |
| 5.15.5  | 1         | 0.69%   |
| 5.15.4  | 1         | 0.69%   |
| 5.15.2  | 1         | 0.69%   |
| 5.15.16 | 1         | 0.69%   |
| 5.15.13 | 1         | 0.69%   |
| 5.14.7  | 1         | 0.69%   |
| 5.14.3  | 1         | 0.69%   |
| 5.14.10 | 1         | 0.69%   |
| 5.13.4  | 1         | 0.69%   |
| 5.13.13 | 1         | 0.69%   |
| 5.13.12 | 1         | 0.69%   |
| 5.12.6  | 1         | 0.69%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 21        | 15.44%  |
| 5.12    | 19        | 13.97%  |
| 5.9     | 18        | 13.24%  |
| 5.15    | 14        | 10.29%  |
| 5.16    | 13        | 9.56%   |
| 5.11    | 12        | 8.82%   |
| 5.8     | 11        | 8.09%   |
| 5.7     | 10        | 7.35%   |
| 5.14    | 7         | 5.15%   |
| 5.13    | 6         | 4.41%   |
| 4.19    | 2         | 1.47%   |
| 5.6     | 1         | 0.74%   |
| 5.5     | 1         | 0.74%   |
| 5.4     | 1         | 0.74%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 119       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| KDE5           | 25        | 19.53%  |
| GNOME          | 23        | 17.97%  |
| XFCE           | 19        | 14.84%  |
| Unknown        | 17        | 13.28%  |
| X-Cinnamon     | 10        | 7.81%   |
| MATE           | 7         | 5.47%   |
| LXQt           | 5         | 3.91%   |
| Cinnamon       | 5         | 3.91%   |
| KDE            | 4         | 3.13%   |
| bspwm          | 3         | 2.34%   |
| LXDE           | 2         | 1.56%   |
| i3             | 2         | 1.56%   |
| xmonad         | 1         | 0.78%   |
| sway           | 1         | 0.78%   |
| openbox        | 1         | 0.78%   |
| nxde           | 1         | 0.78%   |
| dwm            | 1         | 0.78%   |
| awesomeminimal | 1         | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 86        | 68.8%   |
| Tty     | 20        | 16%     |
| Wayland | 12        | 9.6%    |
| Unknown | 7         | 5.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 44        | 35.77%  |
| LightDM | 37        | 30.08%  |
| SDDM    | 33        | 26.83%  |
| GDM     | 4         | 3.25%   |
| LXDM    | 2         | 1.63%   |
| XDM     | 1         | 0.81%   |
| SLiM    | 1         | 0.81%   |
| Ly      | 1         | 0.81%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 55        | 45.08%  |
| Unknown | 15        | 12.3%   |
| ru_RU   | 8         | 6.56%   |
| fr_FR   | 7         | 5.74%   |
| en_GB   | 6         | 4.92%   |
| de_DE   | 6         | 4.92%   |
| C       | 4         | 3.28%   |
| pt_PT   | 3         | 2.46%   |
| es_ES   | 3         | 2.46%   |
| it_IT   | 2         | 1.64%   |
| en_CA   | 2         | 1.64%   |
| el_GR   | 2         | 1.64%   |
| pt_BR   | 1         | 0.82%   |
| pl_PL   | 1         | 0.82%   |
| ja_JP   | 1         | 0.82%   |
| es_MX   | 1         | 0.82%   |
| es_AR   | 1         | 0.82%   |
| en_IE   | 1         | 0.82%   |
| en_AU   | 1         | 0.82%   |
| cs_CZ   | 1         | 0.82%   |
| bg_BG   | 1         | 0.82%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 88        | 72.73%  |
| BIOS | 33        | 27.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 84        | 70.59%  |
| Btrfs   | 25        | 21.01%  |
| Xfs     | 5         | 4.2%    |
| F2fs    | 3         | 2.52%   |
| Overlay | 1         | 0.84%   |
| Jfs     | 1         | 0.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 91        | 74.59%  |
| Unknown | 20        | 16.39%  |
| MBR     | 11        | 9.02%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 94        | 77.69%  |
| Yes       | 27        | 22.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 89        | 74.17%  |
| Yes       | 31        | 25.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 24        | 20.17%  |
| ASUSTek Computer    | 20        | 16.81%  |
| Hewlett-Packard     | 13        | 10.92%  |
| MSI                 | 11        | 9.24%   |
| Dell                | 11        | 9.24%   |
| Gigabyte Technology | 10        | 8.4%    |
| Acer                | 8         | 6.72%   |
| ASRock              | 5         | 4.2%    |
| Apple               | 3         | 2.52%   |
| Timi                | 2         | 1.68%   |
| Notebook            | 2         | 1.68%   |
| Intel               | 2         | 1.68%   |
| GPD                 | 2         | 1.68%   |
| UNOWHY              | 1         | 0.84%   |
| Quanta              | 1         | 0.84%   |
| Microsoft           | 1         | 0.84%   |
| Biostar             | 1         | 0.84%   |
| Alienware           | 1         | 0.84%   |
| Acidanthera         | 1         | 0.84%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Timi RedmiBook 14 II                   | 2         | 1.68%   |
| MSI MS-7C02                            | 2         | 1.68%   |
| MSI MS-7A38                            | 2         | 1.68%   |
| Lenovo IdeaPad 5 15IIL05 81YK          | 2         | 1.68%   |
| GPD P2 MAX                             | 2         | 1.68%   |
| Gigabyte 970A-DS3P                     | 2         | 1.68%   |
| Dell Precision 7550                    | 2         | 1.68%   |
| Apple MacBookAir7,2                    | 2         | 1.68%   |
| UNOWHY Y13G010S4EI                     | 1         | 0.84%   |
| Quanta SWH                             | 1         | 0.84%   |
| Notebook N141CU                        | 1         | 0.84%   |
| Notebook N130BU                        | 1         | 0.84%   |
| MSI MS-7C56                            | 1         | 0.84%   |
| MSI MS-7C37                            | 1         | 0.84%   |
| MSI MS-7B79                            | 1         | 0.84%   |
| MSI MS-7A69                            | 1         | 0.84%   |
| MSI MS-7821                            | 1         | 0.84%   |
| MSI Modern 15 A11M                     | 1         | 0.84%   |
| MSI GP72 7RDX                          | 1         | 0.84%   |
| Microsoft Surface Pro                  | 1         | 0.84%   |
| Lenovo ThinkPad W500 4063CJ5           | 1         | 0.84%   |
| Lenovo ThinkPad T480s 20L8S3D400       | 1         | 0.84%   |
| Lenovo ThinkPad T430 2347H76           | 1         | 0.84%   |
| Lenovo ThinkPad T420 4236H45           | 1         | 0.84%   |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00   | 1         | 0.84%   |
| Lenovo ThinkPad T14 Gen 1 20S1S07800   | 1         | 0.84%   |
| Lenovo ThinkPad P1 Gen 3 20TH001EMH    | 1         | 0.84%   |
| Lenovo ThinkPad E14 Gen 2 20T6000MCK   | 1         | 0.84%   |
| Lenovo ThinkPad 11e 5th Gen 20LNS0P500 | 1         | 0.84%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 1         | 0.84%   |
| Lenovo Legion 5 15ARH05H 82B1          | 1         | 0.84%   |
| Lenovo LaVie Z 20FF0012US              | 1         | 0.84%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU      | 1         | 0.84%   |
| Lenovo IdeaPad Y500 20193              | 1         | 0.84%   |
| Lenovo IdeaPad L340-17IRH Gaming 81LL  | 1         | 0.84%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG   | 1         | 0.84%   |
| Lenovo IdeaPad Flex 5 14ARE05 81X2     | 1         | 0.84%   |
| Lenovo IdeaPad 510-15IKB 80SV          | 1         | 0.84%   |
| Lenovo IdeaPad 330-15IKB 81DE          | 1         | 0.84%   |
| Lenovo G400s 20244                     | 1         | 0.84%   |
| Lenovo B590 20206                      | 1         | 0.84%   |
| Lenovo B570e HuronRiver Platform       | 1         | 0.84%   |
| Intel NUC7CJYH                         | 1         | 0.84%   |
| Intel DX58SO2 AAG10925-205             | 1         | 0.84%   |
| HP ProBook 450 G6                      | 1         | 0.84%   |
| HP OMEN Laptop 15-en0xxx               | 1         | 0.84%   |
| HP Laptop 17z-ca300                    | 1         | 0.84%   |
| HP Laptop 15-ef1xxx                    | 1         | 0.84%   |
| HP Laptop 14s-dq2xxx                   | 1         | 0.84%   |
| HP Laptop 14s-cf3xxx                   | 1         | 0.84%   |
| HP Compaq 8200 Elite SFF PC            | 1         | 0.84%   |
| HP 280 G1 MT                           | 1         | 0.84%   |
| HP 255 G7 Notebook PC                  | 1         | 0.84%   |
| HP 250 G7 Notebook PC                  | 1         | 0.84%   |
| HP 250 G4 Notebook PC                  | 1         | 0.84%   |
| HP 250 G3                              | 1         | 0.84%   |
| HP 15                                  | 1         | 0.84%   |
| Gigabyte X570 AORUS ELITE              | 1         | 0.84%   |
| Gigabyte X399 AORUS XTREME             | 1         | 0.84%   |
| Gigabyte P55-USB3                      | 1         | 0.84%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 9         | 7.56%   |
| Lenovo IdeaPad        | 8         | 6.72%   |
| Acer Aspire           | 6         | 5.04%   |
| Dell Precision        | 5         | 4.2%    |
| HP Laptop             | 4         | 3.36%   |
| HP 250                | 3         | 2.52%   |
| Dell Inspiron         | 3         | 2.52%   |
| ASUS ROG              | 3         | 2.52%   |
| ASUS PRIME            | 3         | 2.52%   |
| Timi RedmiBook        | 2         | 1.68%   |
| MSI MS-7C02           | 2         | 1.68%   |
| MSI MS-7A38           | 2         | 1.68%   |
| GPD P2                | 2         | 1.68%   |
| Gigabyte 970A-DS3P    | 2         | 1.68%   |
| Dell Latitude         | 2         | 1.68%   |
| ASUS TUF              | 2         | 1.68%   |
| Apple MacBookAir7     | 2         | 1.68%   |
| UNOWHY Y13G010S4EI    | 1         | 0.84%   |
| Quanta SWH            | 1         | 0.84%   |
| Notebook N141CU       | 1         | 0.84%   |
| Notebook N130BU       | 1         | 0.84%   |
| MSI MS-7C56           | 1         | 0.84%   |
| MSI MS-7C37           | 1         | 0.84%   |
| MSI MS-7B79           | 1         | 0.84%   |
| MSI MS-7A69           | 1         | 0.84%   |
| MSI MS-7821           | 1         | 0.84%   |
| MSI Modern            | 1         | 0.84%   |
| MSI GP72              | 1         | 0.84%   |
| Microsoft Surface     | 1         | 0.84%   |
| Lenovo ThinkBook      | 1         | 0.84%   |
| Lenovo Legion         | 1         | 0.84%   |
| Lenovo LaVie          | 1         | 0.84%   |
| Lenovo IdeaPadFlex    | 1         | 0.84%   |
| Lenovo G400s          | 1         | 0.84%   |
| Lenovo B590           | 1         | 0.84%   |
| Lenovo B570e          | 1         | 0.84%   |
| Intel NUC7CJYH        | 1         | 0.84%   |
| Intel DX58SO2         | 1         | 0.84%   |
| HP ProBook            | 1         | 0.84%   |
| HP OMEN               | 1         | 0.84%   |
| HP Compaq             | 1         | 0.84%   |
| HP 280                | 1         | 0.84%   |
| HP 255                | 1         | 0.84%   |
| HP 15                 | 1         | 0.84%   |
| Gigabyte X570         | 1         | 0.84%   |
| Gigabyte X399         | 1         | 0.84%   |
| Gigabyte P55-USB3     | 1         | 0.84%   |
| Gigabyte HA65M-D2H-B3 | 1         | 0.84%   |
| Gigabyte B450M        | 1         | 0.84%   |
| Gigabyte AERO         | 1         | 0.84%   |
| Gigabyte 990FXA-UD5   | 1         | 0.84%   |
| Gigabyte 990FXA-UD3   | 1         | 0.84%   |
| Dell OptiPlex         | 1         | 0.84%   |
| Biostar G31D-M7       | 1         | 0.84%   |
| ASUS VivoBook         | 1         | 0.84%   |
| ASUS SABERTOOTH       | 1         | 0.84%   |
| ASUS Pro              | 1         | 0.84%   |
| ASUS P8H61-M          | 1         | 0.84%   |
| ASUS P8B75-M          | 1         | 0.84%   |
| ASUS K53SC            | 1         | 0.84%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 28        | 23.53%  |
| 2019 | 17        | 14.29%  |
| 2018 | 13        | 10.92%  |
| 2017 | 12        | 10.08%  |
| 2013 | 8         | 6.72%   |
| 2012 | 8         | 6.72%   |
| 2011 | 8         | 6.72%   |
| 2016 | 7         | 5.88%   |
| 2015 | 5         | 4.2%    |
| 2014 | 5         | 4.2%    |
| 2010 | 3         | 2.52%   |
| 2021 | 2         | 1.68%   |
| 2008 | 2         | 1.68%   |
| 2009 | 1         | 0.84%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 71        | 59.66%  |
| Desktop     | 43        | 36.13%  |
| Convertible | 2         | 1.68%   |
| Tablet      | 1         | 0.84%   |
| Mini pc     | 1         | 0.84%   |
| All in one  | 1         | 0.84%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 118       | 99.16%  |
| Enabled  | 1         | 0.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 119       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 33        | 27.27%  |
| 8.01-16.0   | 33        | 27.27%  |
| 4.01-8.0    | 20        | 16.53%  |
| 3.01-4.0    | 16        | 13.22%  |
| 32.01-64.0  | 9         | 7.44%   |
| 64.01-256.0 | 7         | 5.79%   |
| 1.01-2.0    | 3         | 2.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 32        | 23.7%   |
| 2.01-3.0   | 30        | 22.22%  |
| 4.01-8.0   | 28        | 20.74%  |
| 3.01-4.0   | 24        | 17.78%  |
| 0.51-1.0   | 11        | 8.15%   |
| 8.01-16.0  | 5         | 3.7%    |
| 0.01-0.5   | 3         | 2.22%   |
| 16.01-24.0 | 2         | 1.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 64        | 52.46%  |
| 2      | 36        | 29.51%  |
| 3      | 14        | 11.48%  |
| 4      | 4         | 3.28%   |
| 6      | 2         | 1.64%   |
| 8      | 1         | 0.82%   |
| 7      | 1         | 0.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 88        | 73.95%  |
| Yes       | 31        | 26.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 102       | 85.71%  |
| No        | 17        | 14.29%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 94        | 78.99%  |
| No        | 25        | 21.01%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 66.12%  |
| No        | 41        | 33.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 22        | 18.49%  |
| Germany     | 15        | 12.61%  |
| Russia      | 10        | 8.4%    |
| France      | 10        | 8.4%    |
| UK          | 5         | 4.2%    |
| Ukraine     | 4         | 3.36%   |
| Switzerland | 4         | 3.36%   |
| Poland      | 4         | 3.36%   |
| Greece      | 4         | 3.36%   |
| Canada      | 4         | 3.36%   |
| Turkey      | 3         | 2.52%   |
| Spain       | 3         | 2.52%   |
| Brazil      | 3         | 2.52%   |
| Netherlands | 2         | 1.68%   |
| Italy       | 2         | 1.68%   |
| Indonesia   | 2         | 1.68%   |
| India       | 2         | 1.68%   |
| Bulgaria    | 2         | 1.68%   |
| Argentina   | 2         | 1.68%   |
| Uzbekistan  | 1         | 0.84%   |
| Sweden      | 1         | 0.84%   |
| Slovenia    | 1         | 0.84%   |
| Mexico      | 1         | 0.84%   |
| Lithuania   | 1         | 0.84%   |
| Japan       | 1         | 0.84%   |
| Iran        | 1         | 0.84%   |
| Hong Kong   | 1         | 0.84%   |
| Czechia     | 1         | 0.84%   |
| China       | 1         | 0.84%   |
| Chile       | 1         | 0.84%   |
| Bangladesh  | 1         | 0.84%   |
| Azerbaijan  | 1         | 0.84%   |
| Austria     | 1         | 0.84%   |
| Australia   | 1         | 0.84%   |
| Algeria     | 1         | 0.84%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Paris                    | 5         | 4%      |
| Frankfurt am Main        | 4         | 3.2%    |
| Seattle                  | 3         | 2.4%    |
| Kyiv                     | 3         | 2.4%    |
| St Petersburg            | 2         | 1.6%    |
| Sofia                    | 2         | 1.6%    |
| San Ramon                | 2         | 1.6%    |
| Neuchatel                | 2         | 1.6%    |
| Moscow                   | 2         | 1.6%    |
| Los Angeles              | 2         | 1.6%    |
| KÅ‚odzko              | 2         | 1.6%    |
| Jakarta                  | 2         | 1.6%    |
| Geneva                   | 2         | 1.6%    |
| Charlotte                | 2         | 1.6%    |
| Berlin                   | 2         | 1.6%    |
| Amsterdam                | 2         | 1.6%    |
| Г‡orum                | 1         | 0.8%    |
| Zaporizhzhya             | 1         | 0.8%    |
| York                     | 1         | 0.8%    |
| Yekaterinburg            | 1         | 0.8%    |
| Xirdalan                 | 1         | 0.8%    |
| Wigan                    | 1         | 0.8%    |
| Vilnius                  | 1         | 0.8%    |
| Villiers-sur-Orge        | 1         | 0.8%    |
| Vienna                   | 1         | 0.8%    |
| Vancouver                | 1         | 0.8%    |
| Valdahon                 | 1         | 0.8%    |
| Utsunomiya               | 1         | 0.8%    |
| Upper Norwood            | 1         | 0.8%    |
| Ufa                      | 1         | 0.8%    |
| Towanda                  | 1         | 0.8%    |
| Toronto                  | 1         | 0.8%    |
| Thessaloniki             | 1         | 0.8%    |
| Thassos                  | 1         | 0.8%    |
| Tehran                   | 1         | 0.8%    |
| Syeverodonets'k          | 1         | 0.8%    |
| Sydney                   | 1         | 0.8%    |
| Surgut                   | 1         | 0.8%    |
| Stuttgart                | 1         | 0.8%    |
| Stockholm                | 1         | 0.8%    |
| Statesboro               | 1         | 0.8%    |
| Srednyaya Akhtuba        | 1         | 0.8%    |
| Seville                  | 1         | 0.8%    |
| Santiago                 | 1         | 0.8%    |
| Santa Fe                 | 1         | 0.8%    |
| Sant'Agata Bolognese     | 1         | 0.8%    |
| San Miguel de TucumГЎn | 1         | 0.8%    |
| Sainte-Severe            | 1         | 0.8%    |
| Roseburg                 | 1         | 0.8%    |
| Riverview                | 1         | 0.8%    |
| Quincy                   | 1         | 0.8%    |
| Prague                   | 1         | 0.8%    |
| Piraeus                  | 1         | 0.8%    |
| Ordu                     | 1         | 0.8%    |
| Onda                     | 1         | 0.8%    |
| Omsk                     | 1         | 0.8%    |
| Obernai                  | 1         | 0.8%    |
| Nuremberg                | 1         | 0.8%    |
| Nottingham               | 1         | 0.8%    |
| Neustadt in Holstein     | 1         | 0.8%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 39     | 16.41%  |
| Samsung Electronics | 32        | 43     | 16.41%  |
| WDC                 | 26        | 46     | 13.33%  |
| Toshiba             | 15        | 16     | 7.69%   |
| Kingston            | 13        | 14     | 6.67%   |
| Crucial             | 10        | 16     | 5.13%   |
| Intel               | 9         | 14     | 4.62%   |
| Sandisk             | 8         | 10     | 4.1%    |
| SK Hynix            | 7         | 14     | 3.59%   |
| Hitachi             | 5         | 6      | 2.56%   |
| HGST                | 4         | 5      | 2.05%   |
| China               | 4         | 4      | 2.05%   |
| Apple               | 3         | 4      | 1.54%   |
| Unknown             | 2         | 2      | 1.03%   |
| SPCC                | 2         | 2      | 1.03%   |
| PNY                 | 2         | 2      | 1.03%   |
| Phison Electronics  | 2         | 3      | 1.03%   |
| MAXTOR              | 2         | 2      | 1.03%   |
| Linux               | 2         | 2      | 1.03%   |
| JMicron             | 2         | 2      | 1.03%   |
| Corsair             | 2         | 2      | 1.03%   |
| Union Memory        | 1         | 1      | 0.51%   |
| TS512GMT            | 1         | 3      | 0.51%   |
| Transcend           | 1         | 1      | 0.51%   |
| Timetec             | 1         | 2      | 0.51%   |
| Solid State Storage | 1         | 1      | 0.51%   |
| Phison              | 1         | 1      | 0.51%   |
| LDLC                | 1         | 6      | 0.51%   |
| Intenso             | 1         | 1      | 0.51%   |
| Hewlett-Packard     | 1         | 1      | 0.51%   |
| GOODRAM             | 1         | 1      | 0.51%   |
| AMD                 | 1         | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB                  | 3         | 1.4%    |
| Seagate ST3500418AS 500GB               | 3         | 1.4%    |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 1.4%    |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 1.4%    |
| Seagate ST1000DM010-2EP102 1TB          | 3         | 1.4%    |
| Sandisk NVMe SSD Drive 512GB            | 3         | 1.4%    |
| Samsung SSD 970 EVO 1TB                 | 3         | 1.4%    |
| Samsung SSD 860 EVO 250GB               | 3         | 1.4%    |
| HGST HTS545050A7E680 500GB              | 3         | 1.4%    |
| Crucial CT240BX500SSD1 240GB            | 3         | 1.4%    |
| Crucial CT1000MX500SSD1 1TB             | 3         | 1.4%    |
| WDC WD80EZAZ-11TDBA0 8TB                | 2         | 0.93%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.93%   |
| WDC WD10EZEX-08WN4A0 1TB                | 2         | 0.93%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 0.93%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.93%   |
| SPCC Solid State Disk 240GB             | 2         | 0.93%   |
| Samsung SSD 870 EVO 250GB               | 2         | 0.93%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 0.93%   |
| Samsung MZYTY256HDHP-000L2 256GB SSD    | 2         | 0.93%   |
| Samsung MZNLH512HALU-00000 512GB SSD    | 2         | 0.93%   |
| Phison PCIe SSD 256GB                   | 2         | 0.93%   |
| Linux scsi_debug 8.3MB                  | 2         | 0.93%   |
| Kingston SA400S37240G 240GB SSD         | 2         | 0.93%   |
| Kingston SA400S37120G 120GB SSD         | 2         | 0.93%   |
| China SATA SSD 960GB                    | 2         | 0.93%   |
| Apple SSD SM0256G 256GB                 | 2         | 0.93%   |
| WDC WDS500G2B0C-00PXH0 500GB            | 1         | 0.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.47%   |
| WDC WDS256G1X0C-00ENX0 256GB            | 1         | 0.47%   |
| WDC WDS200T2B0B-00YS70 2TB SSD          | 1         | 0.47%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.47%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 1         | 0.47%   |
| WDC WDBNCE5000PNC 500GB SSD             | 1         | 0.47%   |
| WDC WD6001FZWX-00A2VA0 6TB              | 1         | 0.47%   |
| WDC WD5003ABYX-18WERA0 500GB            | 1         | 0.47%   |
| WDC WD5000LPVX-75V0TT0 500GB            | 1         | 0.47%   |
| WDC WD5000LPVX-00V0TT0 500GB            | 1         | 0.47%   |
| WDC WD5000BPVT-22HXZT3 500GB            | 1         | 0.47%   |
| WDC WD5000AAKX-60U6AA0 500GB            | 1         | 0.47%   |
| WDC WD40EZRZ-00WN9B0 4TB                | 1         | 0.47%   |
| WDC WD4003FZEX-00Z4SA0 4TB              | 1         | 0.47%   |
| WDC WD4003FFBX-68MU3N0 4TB              | 1         | 0.47%   |
| WDC WD3200LPVT-00FMCT0 320GB            | 1         | 0.47%   |
| WDC WD30EZRX-00DC0B0 3TB                | 1         | 0.47%   |
| WDC WD30EFRX-68EUZN0 3TB                | 1         | 0.47%   |
| WDC WD2500HHTZ-04N21V0 250GB            | 1         | 0.47%   |
| WDC WD20EZRX-00D8PB0 2TB                | 1         | 0.47%   |
| WDC WD20EARS-00MVWB0 2TB                | 1         | 0.47%   |
| WDC WD2003FZEX-00SRLA0 2TB              | 1         | 0.47%   |
| WDC WD15EARS-22MVWB0 1TB                | 1         | 0.47%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 0.47%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.47%   |
| WDC WD10EZRZ-00HTKB0 1TB                | 1         | 0.47%   |
| WDC WD10EZEX-00BN5A0 1TB                | 1         | 0.47%   |
| WDC WD100EMAZ-00WJTA0 10TB              | 1         | 0.47%   |
| Unknown SD/MMC/MS PRO 32GB              | 1         | 0.47%   |
| Unknown DA4064  64GB                    | 1         | 0.47%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB | 1         | 0.47%   |
| TS512GMT S430S 512GB                    | 1         | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 32        | 39     | 40.51%  |
| WDC     | 22        | 36     | 27.85%  |
| Toshiba | 12        | 13     | 15.19%  |
| Hitachi | 5         | 6      | 6.33%   |
| HGST    | 4         | 5      | 5.06%   |
| MAXTOR  | 2         | 2      | 2.53%   |
| Unknown | 1         | 1      | 1.27%   |
| JMicron | 1         | 1      | 1.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 18     | 22.58%  |
| Crucial             | 10        | 16     | 16.13%  |
| Kingston            | 9         | 9      | 14.52%  |
| WDC                 | 4         | 7      | 6.45%   |
| China               | 4         | 4      | 6.45%   |
| SanDisk             | 3         | 3      | 4.84%   |
| Intel               | 3         | 4      | 4.84%   |
| Apple               | 3         | 4      | 4.84%   |
| SPCC                | 2         | 2      | 3.23%   |
| Linux               | 2         | 2      | 3.23%   |
| Toshiba             | 1         | 1      | 1.61%   |
| SK Hynix            | 1         | 1      | 1.61%   |
| PNY                 | 1         | 1      | 1.61%   |
| LDLC                | 1         | 6      | 1.61%   |
| JMicron             | 1         | 1      | 1.61%   |
| Intenso             | 1         | 1      | 1.61%   |
| GOODRAM             | 1         | 1      | 1.61%   |
| AMD                 | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 68        | 103    | 39.08%  |
| SSD     | 55        | 82     | 31.61%  |
| NVMe    | 48        | 76     | 27.59%  |
| Unknown | 2         | 5      | 1.15%   |
| MMC     | 1         | 1      | 0.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 92        | 181    | 62.16%  |
| NVMe | 48        | 76     | 32.43%  |
| SAS  | 7         | 9      | 4.73%   |
| MMC  | 1         | 1      | 0.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 62        | 94     | 48.44%  |
| 0.51-1.0   | 43        | 61     | 33.59%  |
| 1.01-2.0   | 12        | 13     | 9.38%   |
| 3.01-4.0   | 4         | 4      | 3.13%   |
| 2.01-3.0   | 4         | 4      | 3.13%   |
| 4.01-10.0  | 3         | 9      | 2.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 30        | 24.59%  |
| 251-500        | 24        | 19.67%  |
| 1001-2000      | 17        | 13.93%  |
| 501-1000       | 15        | 12.3%   |
| More than 3000 | 12        | 9.84%   |
| 2001-3000      | 9         | 7.38%   |
| 51-100         | 7         | 5.74%   |
| Unknown        | 5         | 4.1%    |
| 1-20           | 2         | 1.64%   |
| 21-50          | 1         | 0.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 27        | 20.93%  |
| 501-1000       | 21        | 16.28%  |
| 101-250        | 19        | 14.73%  |
| 51-100         | 15        | 11.63%  |
| 21-50          | 14        | 10.85%  |
| 251-500        | 12        | 9.3%    |
| 1001-2000      | 9         | 6.98%   |
| More than 3000 | 5         | 3.88%   |
| Unknown        | 5         | 3.88%   |
| 2001-3000      | 2         | 1.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB           | 2         | 2      | 9.09%   |
| HGST HTS545050A7E680 500GB       | 2         | 2      | 9.09%   |
| WDC WD3200LPVT-00FMCT0 320GB     | 1         | 1      | 4.55%   |
| WDC WD30EZRX-00DC0B0 3TB         | 1         | 1      | 4.55%   |
| Toshiba MK7575GSX 752GB          | 1         | 1      | 4.55%   |
| Toshiba MK5065GSX 500GB          | 1         | 1      | 4.55%   |
| Seagate ST8000DM004-2CX188 8TB   | 1         | 1      | 4.55%   |
| Seagate ST500LT012-9WS142 500GB  | 1         | 1      | 4.55%   |
| Seagate ST2000DX002-2DV164 2TB   | 1         | 1      | 4.55%   |
| Seagate ST2000DM006-2DM164 2TB   | 1         | 1      | 4.55%   |
| Seagate ST1000LM035-1RK172 1TB   | 1         | 1      | 4.55%   |
| MAXTOR 6Y080M0 81GB              | 1         | 1      | 4.55%   |
| LDLC SSD 120GB                   | 1         | 3      | 4.55%   |
| Kingston SUV400S37240G 240GB SSD | 1         | 1      | 4.55%   |
| Kingston SA400S37120G 120GB SSD  | 1         | 1      | 4.55%   |
| Intel SSDSC2BW480A4 480GB        | 1         | 2      | 4.55%   |
| Intel SSDPEKKW128G7 128GB        | 1         | 1      | 4.55%   |
| Hitachi HTS547550A9E384 500GB    | 1         | 1      | 4.55%   |
| Hitachi HTS542516K9SA00 160GB    | 1         | 1      | 4.55%   |
| Hewlett-Packard SSD EX900 250GB  | 1         | 1      | 4.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 5         | 5      | 22.73%  |
| Toshiba         | 4         | 4      | 18.18%  |
| WDC             | 2         | 2      | 9.09%   |
| Kingston        | 2         | 2      | 9.09%   |
| Intel           | 2         | 3      | 9.09%   |
| Hitachi         | 2         | 2      | 9.09%   |
| HGST            | 2         | 2      | 9.09%   |
| MAXTOR          | 1         | 1      | 4.55%   |
| LDLC            | 1         | 3      | 4.55%   |
| Hewlett-Packard | 1         | 1      | 4.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 31.25%  |
| Toshiba | 4         | 4      | 25%     |
| WDC     | 2         | 2      | 12.5%   |
| Hitachi | 2         | 2      | 12.5%   |
| HGST    | 2         | 2      | 12.5%   |
| MAXTOR  | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 16     | 72.73%  |
| SSD  | 4         | 7      | 18.18%  |
| NVMe | 2         | 2      | 9.09%   |

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
| Works    | 74        | 138    | 53.62%  |
| Detected | 43        | 104    | 31.16%  |
| Malfunc  | 21        | 25     | 15.22%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 68        | 41.21%  |
| AMD                            | 35        | 21.21%  |
| Samsung Electronics            | 22        | 13.33%  |
| Sandisk                        | 7         | 4.24%   |
| SK Hynix                       | 6         | 3.64%   |
| Phison Electronics             | 5         | 3.03%   |
| Marvell Technology Group       | 5         | 3.03%   |
| Kingston Technology Company    | 4         | 2.42%   |
| ASMedia Technology             | 3         | 1.82%   |
| Union Memory (Shenzhen)        | 2         | 1.21%   |
| Toshiba America Info Systems   | 2         | 1.21%   |
| Silicon Motion                 | 2         | 1.21%   |
| Solid State Storage Technology | 1         | 0.61%   |
| Nvidia                         | 1         | 0.61%   |
| JMicron Technology             | 1         | 0.61%   |
| Broadcom / LSI                 | 1         | 0.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 26        | 13.9%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 6.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 3.74%   |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 3.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 2.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 2.67%   |
| SK Hynix Non-Volatile memory controller                                        | 4         | 2.14%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 2.14%   |
| Phison E12 NVMe Controller                                                     | 4         | 2.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 2.14%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 2.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.14%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 2.14%   |
| AMD 300 Series Chipset SATA Controller                                         | 4         | 2.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.6%    |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 1.6%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.6%    |
| Intel SSD 660P Series                                                          | 3         | 1.6%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.6%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.6%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 1.07%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 1.07%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.07%   |
| Sandisk Non-Volatile memory controller                                         | 2         | 1.07%   |
| Samsung Electronics SATA controller                                            | 2         | 1.07%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2         | 1.07%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.07%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 1.07%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 1.07%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.07%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 1.07%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 1.07%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.07%   |
| AMD 500 Series Chipset SATA Controller                                         | 2         | 1.07%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.53%   |
| SK Hynix Gold P31 SSD                                                          | 1         | 0.53%   |
| SK Hynix BC511                                                                 | 1         | 0.53%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.53%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.53%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.53%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.53%   |
| Sandisk WD Black NVMe SSD                                                      | 1         | 0.53%   |
| Phison E16 PCIe4 NVMe Controller                                               | 1         | 0.53%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.53%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.53%   |
| Marvell Group 88SE9172 SATA III 6Gb/s RAID Controller                          | 1         | 0.53%   |
| Marvell Group 88SE912x IDE Controller                                          | 1         | 0.53%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 1         | 0.53%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 0.53%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1         | 0.53%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 0.53%   |
| Intel SSD 600P Series                                                          | 1         | 0.53%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.53%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.53%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 1         | 0.53%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.53%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 95        | 59.01%  |
| NVMe | 49        | 30.43%  |
| RAID | 8         | 4.97%   |
| IDE  | 8         | 4.97%   |
| SAS  | 1         | 0.62%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 80        | 67.23%  |
| AMD    | 39        | 32.77%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor         | 4         | 3.33%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 4         | 3.33%   |
| AMD FX-8350 Eight-Core Processor            | 3         | 2.5%    |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 2         | 1.67%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2         | 1.67%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 1.67%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.67%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 1.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.67%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 2         | 1.67%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 1.67%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 2         | 1.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.67%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 2         | 1.67%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 2         | 1.67%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.67%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2         | 1.67%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.67%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2         | 1.67%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz        | 1         | 0.83%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.83%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.83%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.83%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 0.83%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz            | 1         | 0.83%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.83%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 1         | 0.83%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 0.83%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1         | 0.83%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.83%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.83%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.83%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.83%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.83%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.83%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.83%   |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 0.83%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 0.83%   |
| Intel Core i7-10850H CPU @ 2.70GHz          | 1         | 0.83%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.83%   |
| Intel Core i7 CPU 970 @ 3.20GHz             | 1         | 0.83%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1         | 0.83%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 0.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.83%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1         | 0.83%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 0.83%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 1         | 0.83%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 0.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 0.83%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1         | 0.83%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 0.83%   |
| Intel Core i5-4258U CPU @ 2.40GHz           | 1         | 0.83%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1         | 0.83%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 0.83%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 0.83%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 0.83%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 0.83%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 1         | 0.83%   |
| Intel Core i5-10500T CPU @ 2.30GHz          | 1         | 0.83%   |
| Intel Core i5 CPU 660 @ 3.33GHz             | 1         | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 29        | 24.37%  |
| Intel Core i7           | 18        | 15.13%  |
| AMD Ryzen 7             | 12        | 10.08%  |
| AMD Ryzen 5             | 10        | 8.4%    |
| Intel Core i3           | 9         | 7.56%   |
| Intel Celeron           | 6         | 5.04%   |
| AMD Ryzen 9             | 5         | 4.2%    |
| Other                   | 4         | 3.36%   |
| AMD Ryzen 3             | 4         | 3.36%   |
| AMD FX                  | 4         | 3.36%   |
| Intel Core m3           | 3         | 2.52%   |
| Intel Core 2 Duo        | 3         | 2.52%   |
| Intel Pentium           | 2         | 1.68%   |
| Intel Core i9           | 2         | 1.68%   |
| Intel Xeon              | 1         | 0.84%   |
| Intel Pentium Silver    | 1         | 0.84%   |
| Intel Pentium Dual-Core | 1         | 0.84%   |
| Intel Atom              | 1         | 0.84%   |
| AMD Ryzen Threadripper  | 1         | 0.84%   |
| AMD Ryzen 5 PRO         | 1         | 0.84%   |
| AMD Phenom II X4        | 1         | 0.84%   |
| AMD A10                 | 1         | 0.84%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 43        | 36.13%  |
| 4      | 35        | 29.41%  |
| 8      | 17        | 14.29%  |
| 6      | 16        | 13.45%  |
| 12     | 5         | 4.2%    |
| 3      | 2         | 1.68%   |
| 32     | 1         | 0.84%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 119       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 85        | 71.43%  |
| 1      | 34        | 28.57%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 119       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 17.89%  |
| 0x206a7    | 7         | 5.69%   |
| 0x806e9    | 5         | 4.07%   |
| 0x306a9    | 5         | 4.07%   |
| 0x08701013 | 5         | 4.07%   |
| 0x906ed    | 4         | 3.25%   |
| 0x906e9    | 4         | 3.25%   |
| 0x806c1    | 4         | 3.25%   |
| 0x306d4    | 4         | 3.25%   |
| 0x306c3    | 4         | 3.25%   |
| 0x08600106 | 4         | 3.25%   |
| 0xa0652    | 3         | 2.44%   |
| 0x806ec    | 3         | 2.44%   |
| 0x706e5    | 3         | 2.44%   |
| 0x706a1    | 3         | 2.44%   |
| 0x40651    | 3         | 2.44%   |
| 0x1067a    | 3         | 2.44%   |
| 0x08701021 | 3         | 2.44%   |
| 0x0800820d | 3         | 2.44%   |
| 0x06000822 | 3         | 2.44%   |
| 0x806ea    | 2         | 1.63%   |
| 0x506e3    | 2         | 1.63%   |
| 0x08600103 | 2         | 1.63%   |
| 0xa0653    | 1         | 0.81%   |
| 0x906ea    | 1         | 0.81%   |
| 0x6fd      | 1         | 0.81%   |
| 0x506c9    | 1         | 0.81%   |
| 0x406e3    | 1         | 0.81%   |
| 0x30678    | 1         | 0.81%   |
| 0x206c2    | 1         | 0.81%   |
| 0x20655    | 1         | 0.81%   |
| 0x20652    | 1         | 0.81%   |
| 0x0a50000b | 1         | 0.81%   |
| 0x0a201016 | 1         | 0.81%   |
| 0x0a201009 | 1         | 0.81%   |
| 0x08608103 | 1         | 0.81%   |
| 0x08600104 | 1         | 0.81%   |
| 0x0810100b | 1         | 0.81%   |
| 0x08101007 | 1         | 0.81%   |
| 0x0800820b | 1         | 0.81%   |
| 0x08001138 | 1         | 0.81%   |
| 0x08001137 | 1         | 0.81%   |
| 0x08001129 | 1         | 0.81%   |
| 0x06003106 | 1         | 0.81%   |
| 0x06000852 | 1         | 0.81%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 25        | 21.01%  |
| Zen 2         | 17        | 14.29%  |
| SandyBridge   | 8         | 6.72%   |
| Haswell       | 8         | 6.72%   |
| Zen+          | 6         | 5.04%   |
| Zen           | 6         | 5.04%   |
| IvyBridge     | 6         | 5.04%   |
| CometLake     | 5         | 4.2%    |
| Broadwell     | 5         | 4.2%    |
| TigerLake     | 4         | 3.36%   |
| Piledriver    | 4         | 3.36%   |
| Zen 3         | 3         | 2.52%   |
| Westmere      | 3         | 2.52%   |
| Skylake       | 3         | 2.52%   |
| Penryn        | 3         | 2.52%   |
| IceLake       | 3         | 2.52%   |
| Goldmont plus | 3         | 2.52%   |
| Steamroller   | 1         | 0.84%   |
| Silvermont    | 1         | 0.84%   |
| K10           | 1         | 0.84%   |
| Goldmont      | 1         | 0.84%   |
| Core          | 1         | 0.84%   |
| Bonnell       | 1         | 0.84%   |
| Unknown       | 1         | 0.84%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 63        | 44.68%  |
| AMD    | 41        | 29.08%  |
| Nvidia | 37        | 26.24%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 8         | 5.59%   |
| AMD Renoir                                                                  | 7         | 4.9%    |
| Intel HD Graphics 620                                                       | 6         | 4.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 3.5%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 2.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                            | 4         | 2.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 4         | 2.8%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4         | 2.8%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 3         | 2.1%    |
| Intel HD Graphics 5500                                                      | 3         | 2.1%    |
| Intel 3rd Gen Core processor Graphics Controller                            | 3         | 2.1%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 2         | 1.4%    |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                            | 2         | 1.4%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 1.4%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 1.4%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 2         | 1.4%    |
| Nvidia GM206 [GeForce GTX 950]                                              | 2         | 1.4%    |
| Nvidia GM108M [GeForce 840M]                                                | 2         | 1.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 1.4%    |
| Intel UHD Graphics 620                                                      | 2         | 1.4%    |
| Intel UHD Graphics 615                                                      | 2         | 1.4%    |
| Intel HD Graphics 630                                                       | 2         | 1.4%    |
| Intel HD Graphics 6000                                                      | 2         | 1.4%    |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 1.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 1.4%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2         | 1.4%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2         | 1.4%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2         | 1.4%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2         | 1.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.7%    |
| Nvidia TU117M                                                               | 1         | 0.7%    |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.7%    |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                     | 1         | 0.7%    |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1         | 0.7%    |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1         | 0.7%    |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1         | 0.7%    |
| Nvidia GT218M [GeForce 310M]                                                | 1         | 0.7%    |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 0.7%    |
| Nvidia GP108M [GeForce MX330]                                               | 1         | 0.7%    |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 0.7%    |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1         | 0.7%    |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1         | 0.7%    |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                       | 1         | 0.7%    |
| Nvidia GM107 [GeForce 940MX]                                                | 1         | 0.7%    |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 0.7%    |
| Nvidia GK107M [GeForce GT 650M]                                             | 1         | 0.7%    |
| Nvidia GF119M [GeForce GT 520MX]                                            | 1         | 0.7%    |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1         | 0.7%    |
| Nvidia GF108M [GeForce GT 520M]                                             | 1         | 0.7%    |
| Nvidia GF108GLM [NVS 5200M]                                                 | 1         | 0.7%    |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 1         | 0.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 0.7%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 0.7%    |
| Intel HD Graphics P630                                                      | 1         | 0.7%    |
| Intel HD Graphics 615                                                       | 1         | 0.7%    |
| Intel HD Graphics 500                                                       | 1         | 0.7%    |
| Intel GeminiLake [UHD Graphics 605]                                         | 1         | 0.7%    |
| Intel Core Processor Integrated Graphics Controller                         | 1         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 44        | 36.36%  |
| 1 x AMD        | 35        | 28.93%  |
| 1 x Nvidia     | 21        | 17.36%  |
| Intel + Nvidia | 14        | 11.57%  |
| Intel + AMD    | 3         | 2.48%   |
| 2 x AMD        | 2         | 1.65%   |
| AMD + Nvidia   | 2         | 1.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 95        | 78.51%  |
| Proprietary | 26        | 21.49%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 50.81%  |
| 1.01-2.0   | 14        | 11.29%  |
| 7.01-8.0   | 13        | 10.48%  |
| 3.01-4.0   | 11        | 8.87%   |
| 0.01-0.5   | 9         | 7.26%   |
| 0.51-1.0   | 7         | 5.65%   |
| 5.01-6.0   | 3         | 2.42%   |
| 8.01-16.0  | 3         | 2.42%   |
| 2.01-3.0   | 1         | 0.81%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 16        | 10.81%  |
| BOE                     | 16        | 10.81%  |
| LG Display              | 13        | 8.78%   |
| AU Optronics            | 13        | 8.78%   |
| Chimei Innolux          | 12        | 8.11%   |
| Philips                 | 8         | 5.41%   |
| Acer                    | 8         | 5.41%   |
| Goldstar                | 7         | 4.73%   |
| BenQ                    | 7         | 4.73%   |
| Dell                    | 6         | 4.05%   |
| ASUSTek Computer        | 5         | 3.38%   |
| AOC                     | 5         | 3.38%   |
| Apple                   | 3         | 2.03%   |
| Ancor Communications    | 3         | 2.03%   |
| Sharp                   | 2         | 1.35%   |
| InfoVision              | 2         | 1.35%   |
| Hewlett-Packard         | 2         | 1.35%   |
| Chi Mei Optoelectronics | 2         | 1.35%   |
| ViewSonic               | 1         | 0.68%   |
| Vestel Elektronik       | 1         | 0.68%   |
| PANDA                   | 1         | 0.68%   |
| Packard Bell            | 1         | 0.68%   |
| MSI                     | 1         | 0.68%   |
| LGD                     | 1         | 0.68%   |
| Lenovo                  | 1         | 0.68%   |
| KTC                     | 1         | 0.68%   |
| Jean                    | 1         | 0.68%   |
| Iiyama                  | 1         | 0.68%   |
| Idek Iiyama             | 1         | 0.68%   |
| HVR                     | 1         | 0.68%   |
| Hitachi                 | 1         | 0.68%   |
| Envision Peripherals    | 1         | 0.68%   |
| Eizo                    | 1         | 0.68%   |
| CTV                     | 1         | 0.68%   |
| Compal                  | 1         | 0.68%   |
| Belinea                 | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 3         | 1.97%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 256x144mm 11.6-inch   | 2         | 1.32%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                | 2         | 1.32%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch       | 2         | 1.32%   |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                  | 2         | 1.32%   |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                  | 2         | 1.32%   |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                  | 2         | 1.32%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                   | 2         | 1.32%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 2         | 1.32%   |
| ASUSTek Computer VG289 AUS28BA 3840x2160 620x340mm 27.8-inch           | 2         | 1.32%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                   | 2         | 1.32%   |
| AOC F22 AOC2200 1920x1080 476x268mm 21.5-inch                          | 2         | 1.32%   |
| Ancor Communications ASUS PB277 ACI27B5 2560x1440 597x336mm 27.0-inch  | 2         | 1.32%   |
| ViewSonic LCD Monitor VX2452 Series 3840x1080                          | 1         | 0.66%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                          | 1         | 0.66%   |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                | 1         | 0.66%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                | 1         | 0.66%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch      | 1         | 0.66%   |
| Samsung Electronics T24B301 SAM098E 1920x1080 520x290mm 23.4-inch      | 1         | 0.66%   |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch    | 1         | 0.66%   |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch      | 1         | 0.66%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 1         | 0.66%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch      | 1         | 0.66%   |
| Samsung Electronics S24A31x SAM7114 1920x1080 527x296mm 23.8-inch      | 1         | 0.66%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch      | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch   | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 700x390mm 31.5-inch  | 1         | 0.66%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1210x680mm 54.6-inch | 1         | 0.66%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch      | 1         | 0.66%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch      | 1         | 0.66%   |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch      | 1         | 0.66%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 1         | 0.66%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch               | 1         | 0.66%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                | 1         | 0.66%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1         | 0.66%   |
| Philips PHL 220V8 PHLC218 1920x1080 477x268mm 21.5-inch                | 1         | 0.66%   |
| Philips 247ELH PHLC085 1920x1080 521x293mm 23.5-inch                   | 1         | 0.66%   |
| Philips 226VL PHLC081 1920x1080 480x268mm 21.6-inch                    | 1         | 0.66%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                | 1         | 0.66%   |
| Packard Bell Viseo203DX PKB0378 1600x900 432x240mm 19.5-inch           | 1         | 0.66%   |
| MSI Optix MAG27C MSI1462 1920x1080 598x336mm 27.0-inch                 | 1         | 0.66%   |
| LGD LCD Monitor 1920x1080                                              | 1         | 0.66%   |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch            | 1         | 0.66%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch           | 1         | 0.66%   |
| LG Display LCD Monitor LGD046B 1366x768 344x194mm 15.5-inch            | 1         | 0.66%   |
| LG Display LCD Monitor LGD03D3 1600x900 309x174mm 14.0-inch            | 1         | 0.66%   |
| LG Display LCD Monitor LGD03B8 1366x768 310x174mm 14.0-inch            | 1         | 0.66%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch            | 1         | 0.66%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch           | 1         | 0.66%   |
| Lenovo LCD Monitor LEN4053 1680x1050 331x207mm 15.4-inch               | 1         | 0.66%   |
| KTC 24'TV KTC2400 1360x768 525x297mm 23.7-inch                         | 1         | 0.66%   |
| Jean JT198x6-7 JEN17C6 1280x1024 376x301mm 19.0-inch                   | 1         | 0.66%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch           | 1         | 0.66%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 70        | 49.65%  |
| 1366x768 (WXGA)    | 25        | 17.73%  |
| 3840x2160 (4K)     | 15        | 10.64%  |
| 2560x1440 (QHD)    | 8         | 5.67%   |
| 1600x900 (HD+)     | 3         | 2.13%   |
| 1440x900 (WXGA+)   | 3         | 2.13%   |
| 3440x1440          | 2         | 1.42%   |
| 1920x1200 (WUXGA)  | 2         | 1.42%   |
| 1680x1050 (WSXGA+) | 2         | 1.42%   |
| 1280x1024 (SXGA)   | 2         | 1.42%   |
| Unknown            | 2         | 1.42%   |
| 3840x1080          | 1         | 0.71%   |
| 3600x1080          | 1         | 0.71%   |
| 2736x1824          | 1         | 0.71%   |
| 2560x1600          | 1         | 0.71%   |
| 2560x1080          | 1         | 0.71%   |
| 2160x1200          | 1         | 0.71%   |
| 1024x768 (XGA)     | 1         | 0.71%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 36        | 25%     |
| 13      | 16        | 11.11%  |
| 24      | 15        | 10.42%  |
| 27      | 14        | 9.72%   |
| 23      | 13        | 9.03%   |
| 21      | 9         | 6.25%   |
| 14      | 9         | 6.25%   |
| 17      | 5         | 3.47%   |
| Unknown | 5         | 3.47%   |
| 84      | 4         | 2.78%   |
| 34      | 3         | 2.08%   |
| 31      | 3         | 2.08%   |
| 32      | 2         | 1.39%   |
| 20      | 2         | 1.39%   |
| 19      | 2         | 1.39%   |
| 12      | 2         | 1.39%   |
| 11      | 2         | 1.39%   |
| 52      | 1         | 0.69%   |
| 16      | 1         | 0.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 55        | 38.73%  |
| 501-600     | 37        | 26.06%  |
| 401-500     | 11        | 7.75%   |
| 351-400     | 9         | 6.34%   |
| 201-300     | 9         | 6.34%   |
| 601-700     | 6         | 4.23%   |
| 701-800     | 5         | 3.52%   |
| Unknown     | 5         | 3.52%   |
| 1501-2000   | 4         | 2.82%   |
| 1001-1500   | 1         | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 103       | 83.06%  |
| 16/10   | 9         | 7.26%   |
| Unknown | 4         | 3.23%   |
| 21/9    | 3         | 2.42%   |
| 5/4     | 2         | 1.61%   |
| 4/3     | 2         | 1.61%   |
| 3/2     | 1         | 0.81%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 36        | 25%     |
| 201-250        | 33        | 22.92%  |
| 81-90          | 20        | 13.89%  |
| 301-350        | 14        | 9.72%   |
| 351-500        | 8         | 5.56%   |
| 71-80          | 6         | 4.17%   |
| More than 1000 | 5         | 3.47%   |
| 151-200        | 5         | 3.47%   |
| Unknown        | 5         | 3.47%   |
| 121-130        | 4         | 2.78%   |
| 251-300        | 3         | 2.08%   |
| 51-60          | 2         | 1.39%   |
| 131-140        | 2         | 1.39%   |
| 61-70          | 1         | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 48        | 34.78%  |
| 51-100        | 42        | 30.43%  |
| 101-120       | 35        | 25.36%  |
| 161-240       | 6         | 4.35%   |
| Unknown       | 5         | 3.62%   |
| More than 240 | 1         | 0.72%   |
| 1-50          | 1         | 0.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 94        | 77.69%  |
| 2     | 23        | 19.01%  |
| 3     | 3         | 2.48%   |
| 4     | 1         | 0.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 78        | 43.09%  |
| Intel                                 | 55        | 30.39%  |
| Qualcomm Atheros                      | 17        | 9.39%   |
| Broadcom                              | 8         | 4.42%   |
| Broadcom Limited                      | 3         | 1.66%   |
| Xiaomi                                | 2         | 1.1%    |
| Ralink Technology                     | 2         | 1.1%    |
| Ralink                                | 2         | 1.1%    |
| D-Link System                         | 2         | 1.1%    |
| TP-Link                               | 1         | 0.55%   |
| Sierra Wireless                       | 1         | 0.55%   |
| Qualcomm Atheros Communications       | 1         | 0.55%   |
| Qualcomm                              | 1         | 0.55%   |
| Microsoft                             | 1         | 0.55%   |
| Marvell Technology Group              | 1         | 0.55%   |
| Linksys                               | 1         | 0.55%   |
| Huawei Technologies                   | 1         | 0.55%   |
| Google                                | 1         | 0.55%   |
| DisplayLink                           | 1         | 0.55%   |
| Aquantia                              | 1         | 0.55%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 56        | 25.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 3.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.29%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.29%   |
| Intel Wireless 7265                                               | 5         | 2.29%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 2.29%   |
| Intel I211 Gigabit Network Connection                             | 5         | 2.29%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 2.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 1.38%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.38%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.38%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 1.38%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.92%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.92%   |
| Realtek 802.11ac NIC                                              | 2         | 0.92%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.92%   |
| Intel Wireless-AC 9260                                            | 2         | 0.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2         | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.92%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.92%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 0.92%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.46%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.46%   |
| Sierra Wireless MC7700                                            | 1         | 0.46%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.46%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.46%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.46%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.46%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.46%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.46%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.46%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1         | 0.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.46%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 0.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.46%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.46%   |
| Qualcomm A0001                                                    | 1         | 0.46%   |
| Microsoft XBOX ACC                                                | 1         | 0.46%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 1         | 0.46%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 42        | 42%     |
| Realtek Semiconductor                 | 24        | 24%     |
| Qualcomm Atheros                      | 13        | 13%     |
| Broadcom                              | 7         | 7%      |
| Broadcom Limited                      | 3         | 3%      |
| Ralink Technology                     | 2         | 2%      |
| Ralink                                | 2         | 2%      |
| TP-Link                               | 1         | 1%      |
| Sierra Wireless                       | 1         | 1%      |
| Qualcomm Atheros Communications       | 1         | 1%      |
| Microsoft                             | 1         | 1%      |
| Marvell Technology Group              | 1         | 1%      |
| D-Link System                         | 1         | 1%      |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 1%      |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                               | Computers | Percent |
|-----------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                            | 6         | 5.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                            | 5         | 4.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                          | 5         | 4.95%   |
| Intel Wireless 8265 / 8275                                                                          | 5         | 4.95%   |
| Intel Wireless 7265                                                                                 | 5         | 4.95%   |
| Intel Wi-Fi 6 AX200                                                                                 | 5         | 4.95%   |
| Intel Comet Lake PCH CNVi WiFi                                                                      | 5         | 4.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                    | 3         | 2.97%   |
| Intel Wi-Fi 6 AX201                                                                                 | 3         | 2.97%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                          | 3         | 2.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                                 | 3         | 2.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                     | 2         | 1.98%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                            | 2         | 1.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                                     | 2         | 1.98%   |
| Realtek RTL8188EE Wireless Network Adapter                                                          | 2         | 1.98%   |
| Realtek 802.11ac NIC                                                                                | 2         | 1.98%   |
| Intel Wireless-AC 9260                                                                              | 2         | 1.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                                     | 2         | 1.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                   | 2         | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                        | 2         | 1.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                     | 2         | 1.98%   |
| Broadcom BCM43228 802.11a/b/g/n                                                                     | 2         | 1.98%   |
| Broadcom BCM43142 802.11b/g/n                                                                       | 2         | 1.98%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                         | 1         | 0.99%   |
| Sierra Wireless MC7700                                                                              | 1         | 0.99%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                            | 1         | 0.99%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                                     | 1         | 0.99%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                             | 1         | 0.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                          | 1         | 0.99%   |
| Ralink RT5370 Wireless Adapter                                                                      | 1         | 0.99%   |
| Ralink MT7601U Wireless Adapter                                                                     | 1         | 0.99%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                           | 1         | 0.99%   |
| Ralink RT2561/RT61 802.11g PCI                                                                      | 1         | 0.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                          | 1         | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                          | 1         | 0.99%   |
| Qualcomm Atheros AR9271 802.11n                                                                     | 1         | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                    | 1         | 0.99%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                      | 1         | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                      | 1         | 0.99%   |
| Microsoft XBOX ACC                                                                                  | 1         | 0.99%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                                   | 1         | 0.99%   |
| Intel Wireless 3165                                                                                 | 1         | 0.99%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                              | 1         | 0.99%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                             | 1         | 0.99%   |
| Intel Gemini Lake PCH CNVi WiFi                                                                     | 1         | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                    | 1         | 0.99%   |
| Intel Centrino Wireless-N 2230                                                                      | 1         | 0.99%   |
| Intel Centrino Ultimate-N 6300                                                                      | 1         | 0.99%   |
| Intel Centrino Advanced-N 6235                                                                      | 1         | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                            | 1         | 0.99%   |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104]         | 1         | 0.99%   |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB100 v2 RangePlus Wireless Network Adapter [Ralink RT3070] | 1         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 70        | 62.5%   |
| Intel                 | 26        | 23.21%  |
| Qualcomm Atheros      | 7         | 6.25%   |
| Xiaomi                | 2         | 1.79%   |
| Qualcomm              | 1         | 0.89%   |
| Linksys               | 1         | 0.89%   |
| Huawei Technologies   | 1         | 0.89%   |
| DisplayLink           | 1         | 0.89%   |
| D-Link System         | 1         | 0.89%   |
| Broadcom              | 1         | 0.89%   |
| Aquantia              | 1         | 0.89%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 56        | 48.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 6.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 5.17%   |
| Intel I211 Gigabit Network Connection                             | 5         | 4.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.31%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.59%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 2.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.72%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.72%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.86%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.86%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.86%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.86%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.86%   |
| Qualcomm A0001                                                    | 1         | 0.86%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.86%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.86%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.86%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.86%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.86%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.86%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.86%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.86%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1         | 0.86%   |
| Intel 82562V-2 10/100 Network Connection                          | 1         | 0.86%   |
| Huawei E353/E3131                                                 | 1         | 0.86%   |
| DisplayLink Kensington Dock (Composite Device)                    | 1         | 0.86%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1         | 0.86%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.86%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 0.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 102       | 51.52%  |
| WiFi     | 95        | 47.98%  |
| Modem    | 1         | 0.51%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 73        | 54.89%  |
| Ethernet | 60        | 45.11%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 69        | 57.5%   |
| 1     | 47        | 39.17%  |
| 4     | 2         | 1.67%   |
| 3     | 2         | 1.67%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 107       | 87.7%   |
| Yes  | 15        | 12.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 46.25%  |
| Realtek Semiconductor           | 12        | 15%     |
| Qualcomm Atheros Communications | 4         | 5%      |
| IMC Networks                    | 4         | 5%      |
| Cambridge Silicon Radio         | 4         | 5%      |
| Broadcom                        | 4         | 5%      |
| Lite-On Technology              | 3         | 3.75%   |
| Apple                           | 3         | 3.75%   |
| Realtek                         | 2         | 2.5%    |
| Foxconn / Hon Hai               | 2         | 2.5%    |
| ASUSTek Computer                | 2         | 2.5%    |
| Ralink                          | 1         | 1.25%   |
| Marvell Semiconductor           | 1         | 1.25%   |
| HTC (High Tech Computer)        | 1         | 1.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 11        | 13.75%  |
| Intel AX201 Bluetooth                               | 11        | 13.75%  |
| Realtek Bluetooth Radio                             | 8         | 10%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 6.25%   |
| Intel AX200 Bluetooth                               | 5         | 6.25%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 5%      |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 3.75%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 3.75%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 3.75%   |
| Realtek Bluetooth Radio                             | 2         | 2.5%    |
| Intel Bluetooth Device                              | 2         | 2.5%    |
| IMC Networks Bluetooth Radio                        | 2         | 2.5%    |
| IMC Networks Bluetooth Device                       | 2         | 2.5%    |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 2.5%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 2.5%    |
| Apple Bluetooth USB Host Controller                 | 2         | 2.5%    |
| Realtek RTL8821A Bluetooth                          | 1         | 1.25%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.25%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.25%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 1.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 1.25%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 1.25%   |
| Intel AX210 Bluetooth                               | 1         | 1.25%   |
| HTC (High Tech Computer) BCM920703 Bluetooth 4.1    | 1         | 1.25%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 1.25%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 1.25%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 1.25%   |
| ASUS Bluetooth Radio                                | 1         | 1.25%   |
| Apple Bluetooth Host Controller                     | 1         | 1.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 78        | 42.86%  |
| AMD                                             | 46        | 25.27%  |
| Nvidia                                          | 29        | 15.93%  |
| C-Media Electronics                             | 7         | 3.85%   |
| Realtek Semiconductor                           | 4         | 2.2%    |
| Creative Labs                                   | 3         | 1.65%   |
| Logitech                                        | 2         | 1.1%    |
| Creative Technology                             | 2         | 1.1%    |
| Corsair                                         | 2         | 1.1%    |
| TC Electronic                                   | 1         | 0.55%   |
| SteelSeries ApS                                 | 1         | 0.55%   |
| Razer USA                                       | 1         | 0.55%   |
| Plantronics                                     | 1         | 0.55%   |
| Native Instruments                              | 1         | 0.55%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.55%   |
| Generalplus Technology                          | 1         | 0.55%   |
| Focusrite-Novation                              | 1         | 0.55%   |
| AudioQuest                                      | 1         | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 13        | 5.75%   |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 5.31%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11        | 4.87%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 3.54%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 8         | 3.54%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 8         | 3.54%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 8         | 3.54%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 2.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 2.21%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 2.21%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 2.21%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 2.21%   |
| AMD Navi 10 HDMI Audio                                                     | 5         | 2.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 1.77%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 1.77%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.77%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.77%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 1.77%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.33%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 1.33%   |
| Nvidia GP104 High Definition Audio Controller                              | 3         | 1.33%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.33%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.33%   |
| C-Media Electronics KLIM Mantis Audio 7.1                                  | 3         | 1.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.33%   |
| Realtek Semiconductor USB Audio                                            | 2         | 0.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.88%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.88%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.88%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.88%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.88%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 2         | 0.88%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 0.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 0.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 0.88%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                     | 2         | 0.88%   |
| Corsair HS45 Surround USB Sound Adapter                                    | 2         | 0.88%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 2         | 0.88%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 2         | 0.88%   |
| TC Electronic VoiceLive Play                                               | 1         | 0.44%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 1         | 0.44%   |
| Realtek Semiconductor Realtek USB2.0 Audio                                 | 1         | 0.44%   |
| Realtek Semiconductor Realtek Audio USB                                    | 1         | 0.44%   |
| Razer USA RZ19-0229 Gaming Microphone                                      | 1         | 0.44%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.44%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.44%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 0.44%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.44%   |
| Nvidia GK107 HDMI Audio Controller                                         | 1         | 0.44%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 0.44%   |
| Nvidia Audio device                                                        | 1         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 23.53%  |
| SK Hynix            | 21        | 17.65%  |
| Kingston            | 13        | 10.92%  |
| Corsair             | 13        | 10.92%  |
| G.Skill             | 9         | 7.56%   |
| Micron Technology   | 7         | 5.88%   |
| Unknown             | 5         | 4.2%    |
| Crucial             | 5         | 4.2%    |
| A-DATA Technology   | 4         | 3.36%   |
| Silicon Power       | 2         | 1.68%   |
| Ramaxel Technology  | 2         | 1.68%   |
| Patriot             | 2         | 1.68%   |
| Unknown (ABCD)      | 1         | 0.84%   |
| Transcend           | 1         | 0.84%   |
| Team                | 1         | 0.84%   |
| Smart Brazil        | 1         | 0.84%   |
| Nanya Technology    | 1         | 0.84%   |
| ASint Technology    | 1         | 0.84%   |
| AMD                 | 1         | 0.84%   |
| Unknown             | 1         | 0.84%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 2         | 1.6%    |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 1.6%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 2         | 1.6%    |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s                 | 2         | 1.6%    |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 2         | 1.6%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.6%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 2         | 1.6%    |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 2         | 1.6%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 1.6%    |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 1.6%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s                | 2         | 1.6%    |
| G.Skill RAM F3-10666CL9-4GBNT 4096MB DIMM DDR3 1400MT/s             | 2         | 1.6%    |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s            | 2         | 1.6%    |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s            | 2         | 1.6%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.8%    |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                         | 1         | 0.8%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                                | 1         | 0.8%    |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 1         | 0.8%    |
| Unknown RAM Module 2048MB DIMM 1328MT/s                             | 1         | 0.8%    |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.8%    |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s                 | 1         | 0.8%    |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s                | 1         | 0.8%    |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 2933MT/s     | 1         | 0.8%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.8%    |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.8%    |
| SK Hynix RAM HMT425S6AFR6A-PB 2048MB SODIMM DDR3 1600MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.8%    |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.8%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.8%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.8%    |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 1         | 0.8%    |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMA82GU7CJR8N-VK 16GB DIMM DDR4 2667MT/s               | 1         | 0.8%    |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.8%    |
| SK Hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2400MT/s           | 1         | 0.8%    |
| SK Hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s                | 1         | 0.8%    |
| SK Hynix RAM HCNNNBKMBLHR-NEE 1GB Row Of Chips LPDDR4 4267MT/s      | 1         | 0.8%    |
| Silicon Power RAM SP016GBSFU266B02 16GB SODIMM DDR4 2667MT/s        | 1         | 0.8%    |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s         | 1         | 0.8%    |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 1         | 0.8%    |
| Samsung RAM M471B5273DM0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.8%    |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.8%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 1         | 0.8%    |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 1         | 0.8%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 1         | 0.8%    |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s           | 1         | 0.8%    |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s           | 1         | 0.8%    |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 0.8%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 0.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 1         | 0.8%    |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s                 | 1         | 0.8%    |
| Samsung RAM M3 78T2863RZS-CF7 1GB DIMM DDR2 800MT/s                 | 1         | 0.8%    |
| Samsung RAM K4E6E304EE-EGCE 4096MB 1600MT/s                         | 1         | 0.8%    |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s             | 1         | 0.8%    |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s             | 1         | 0.8%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 59        | 57.28%  |
| DDR3    | 32        | 31.07%  |
| SDRAM   | 3         | 2.91%   |
| LPDDR4  | 3         | 2.91%   |
| Unknown | 3         | 2.91%   |
| LPDDR3  | 2         | 1.94%   |
| DDR2    | 1         | 0.97%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 54        | 52.43%  |
| DIMM         | 40        | 38.83%  |
| Row Of Chips | 8         | 7.77%   |
| Unknown      | 1         | 0.97%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 42        | 38.18%  |
| 8192  | 38        | 34.55%  |
| 16384 | 16        | 14.55%  |
| 2048  | 9         | 8.18%   |
| 32768 | 3         | 2.73%   |
| 1024  | 2         | 1.82%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 28        | 25%     |
| 3200    | 24        | 21.43%  |
| 2667    | 13        | 11.61%  |
| 2400    | 10        | 8.93%   |
| 1333    | 7         | 6.25%   |
| 3600    | 4         | 3.57%   |
| 2133    | 4         | 3.57%   |
| 2933    | 3         | 2.68%   |
| 4199    | 2         | 1.79%   |
| 3533    | 2         | 1.79%   |
| 3266    | 2         | 1.79%   |
| 1400    | 2         | 1.79%   |
| 4267    | 1         | 0.89%   |
| 4133    | 1         | 0.89%   |
| 3466    | 1         | 0.89%   |
| 3400    | 1         | 0.89%   |
| 2481    | 1         | 0.89%   |
| 2465    | 1         | 0.89%   |
| 1334    | 1         | 0.89%   |
| 1328    | 1         | 0.89%   |
| 1066    | 1         | 0.89%   |
| 800     | 1         | 0.89%   |
| Unknown | 1         | 0.89%   |

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
| Chicony Electronics                    | 15        | 20%     |
| Acer                                   | 8         | 10.67%  |
| Realtek Semiconductor                  | 7         | 9.33%   |
| Quanta                                 | 7         | 9.33%   |
| IMC Networks                           | 5         | 6.67%   |
| Syntek                                 | 4         | 5.33%   |
| Suyin                                  | 4         | 5.33%   |
| Logitech                               | 4         | 5.33%   |
| Alcor Micro                            | 3         | 4%      |
| Sunplus Innovation Technology          | 2         | 2.67%   |
| Silicon Motion                         | 2         | 2.67%   |
| Microdia                               | 2         | 2.67%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.67%   |
| Microsoft                              | 1         | 1.33%   |
| Luxvisions Innotech Limited            | 1         | 1.33%   |
| Lite-On Technology                     | 1         | 1.33%   |
| LG Electronics                         | 1         | 1.33%   |
| Lenovo                                 | 1         | 1.33%   |
| KYE Systems (Mouse Systems)            | 1         | 1.33%   |
| GEMBIRD                                | 1         | 1.33%   |
| DJKANA1BIFZTDM                         | 1         | 1.33%   |
| Creative Technology                    | 1         | 1.33%   |
| ARC International                      | 1         | 1.33%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                   | 4         | 5.33%   |
| IMC Networks Integrated Camera                                 | 4         | 5.33%   |
| Chicony Integrated Camera                                      | 4         | 5.33%   |
| Chicony HD WebCam                                              | 4         | 5.33%   |
| Syntek Integrated Camera                                       | 2         | 2.67%   |
| Syntek EasyCamera                                              | 2         | 2.67%   |
| Silicon Motion 300k Pixel Camera                               | 2         | 2.67%   |
| Quanta HP Webcam                                               | 2         | 2.67%   |
| Quanta HP TrueVision HD Camera                                 | 2         | 2.67%   |
| Chicony Integrated Camera (1280x720@30)                        | 2         | 2.67%   |
| Acer Lenovo EasyCamera                                         | 2         | 2.67%   |
| Acer Integrated Camera                                         | 2         | 2.67%   |
| Suyin USB Webcam                                               | 1         | 1.33%   |
| Suyin NEC HD WebCam                                            | 1         | 1.33%   |
| Suyin HP Webcam                                                | 1         | 1.33%   |
| Suyin 1.3M HD WebCam                                           | 1         | 1.33%   |
| Sunplus HD WebCam                                              | 1         | 1.33%   |
| Sunplus Aukey-PC-LM1E Camera                                   | 1         | 1.33%   |
| Realtek USB2.0 HD UVC WebCam                                   | 1         | 1.33%   |
| Realtek Integrated Webcam                                      | 1         | 1.33%   |
| Realtek HD WebCam                                              | 1         | 1.33%   |
| Quanta VGA WebCam                                              | 1         | 1.33%   |
| Quanta USB2.0 VGA UVC WebCam                                   | 1         | 1.33%   |
| Quanta HD User Facing                                          | 1         | 1.33%   |
| Microsoft LifeCam Cinema                                       | 1         | 1.33%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 1.33%   |
| Microdia Integrated Webcam                                     | 1         | 1.33%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 1         | 1.33%   |
| Logitech Webcam C930e                                          | 1         | 1.33%   |
| Logitech Webcam C310                                           | 1         | 1.33%   |
| Logitech Webcam C270                                           | 1         | 1.33%   |
| Logitech HD Webcam C910                                        | 1         | 1.33%   |
| Lite-On HP HD Camera                                           | 1         | 1.33%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)          | 1         | 1.33%   |
| Lenovo UVC Camera                                              | 1         | 1.33%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320                 | 1         | 1.33%   |
| IMC Networks Integrated Webcam                                 | 1         | 1.33%   |
| GEMBIRD USB2.0 PC CAMERA                                       | 1         | 1.33%   |
| DJKANA1BIFZTDM HP Wide Vision HD Camera                        | 1         | 1.33%   |
| Creative Live! Cam Sync HD [VF0770]                            | 1         | 1.33%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 1.33%   |
| Chicony USB2.0 Camera                                          | 1         | 1.33%   |
| Chicony USB2.0 0.3M UVC WebCam                                 | 1         | 1.33%   |
| Chicony Thinkpad T430 camera                                   | 1         | 1.33%   |
| Chicony Lenovo EasyCamera                                      | 1         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 1         | 1.33%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.33%   |
| ARC International Camera                                       | 1         | 1.33%   |
| Alcor Micro USB 2.0 Camera                                     | 1         | 1.33%   |
| Alcor Micro Lenovo EasyCamera                                  | 1         | 1.33%   |
| Alcor Micro Asus Integrated Webcam                             | 1         | 1.33%   |
| Acer Integrated 5M Camera                                      | 1         | 1.33%   |
| Acer HD Webcam                                                 | 1         | 1.33%   |
| Acer BisonCam,NB Pro                                           | 1         | 1.33%   |
| Acer BisonCam, NB Pro                                          | 1         | 1.33%   |

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
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 33.33%  |
| Broadcom 58200                                                               | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 91        | 75.21%  |
| 1     | 26        | 21.49%  |
| 2     | 4         | 3.31%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 8         | 22.86%  |
| Net/wireless             | 5         | 14.29%  |
| Graphics card            | 5         | 14.29%  |
| Multimedia controller    | 4         | 11.43%  |
| Camera                   | 4         | 11.43%  |
| Communication controller | 2         | 5.71%   |
| Chipcard                 | 2         | 5.71%   |
| Bluetooth                | 2         | 5.71%   |
| Unassigned class         | 1         | 2.86%   |
| Storage                  | 1         | 2.86%   |
| Dvb card                 | 1         | 2.86%   |

