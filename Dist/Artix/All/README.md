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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.9.14-artix1-1                 | 8         | 6.45%   |
| 5.7.6-artix1-1                  | 5         | 4.03%   |
| 5.7.12-artix1-1                 | 4         | 3.23%   |
| 5.12.12-artix1-1                | 4         | 3.23%   |
| 5.10.8-artix1-1                 | 4         | 3.23%   |
| 5.10.4-artix2-1                 | 4         | 3.23%   |
| 5.8.8-artix1-1                  | 3         | 2.42%   |
| 5.8.12-artix1-1                 | 3         | 2.42%   |
| 5.12.8-artix1-1                 | 3         | 2.42%   |
| 5.12.14-artix1-1                | 3         | 2.42%   |
| 5.10.6-artix1-1                 | 3         | 2.42%   |
| 5.10.16-artix1-1                | 3         | 2.42%   |
| 5.9.14-zen1-1-zen               | 2         | 1.61%   |
| 5.9.12-artix1-1                 | 2         | 1.61%   |
| 5.9.10-artix1-1                 | 2         | 1.61%   |
| 5.8.14-artix1-1                 | 2         | 1.61%   |
| 5.7.2-artix1-1                  | 2         | 1.61%   |
| 5.15.3-zen1-1-zen               | 2         | 1.61%   |
| 5.14.16-artix1-1                | 2         | 1.61%   |
| 5.13.8-artix1-1                 | 2         | 1.61%   |
| 5.12.4-artix1-1                 | 2         | 1.61%   |
| 5.12.12-zen1-1-zen              | 2         | 1.61%   |
| 5.11.6-artix1-1                 | 2         | 1.61%   |
| 5.11.10-artix1-1                | 2         | 1.61%   |
| 4.19.0-1-MANJARO                | 2         | 1.61%   |
| 5.9.8-zen1-1-zen                | 1         | 0.81%   |
| 5.9.6-artix1-1                  | 1         | 0.81%   |
| 5.9.1-artix1-1                  | 1         | 0.81%   |
| 5.9.0-zen1-1-zen                | 1         | 0.81%   |
| 5.9.0-1-mainline-bootsplash     | 1         | 0.81%   |
| 5.8.5-xanmod1-1-xanmod          | 1         | 0.81%   |
| 5.8.4-artix1-1                  | 1         | 0.81%   |
| 5.8.14-zen1-1-zen               | 1         | 0.81%   |
| 5.8.0-rc7-5-mainline-bootsplash | 1         | 0.81%   |
| 5.7.8-artix1-1                  | 1         | 0.81%   |
| 5.6.7-x86_64                    | 1         | 0.81%   |
| 5.5.3-artix1-1                  | 1         | 0.81%   |
| 5.5.10-artix1-1                 | 1         | 0.81%   |
| 5.4.74-1-lts                    | 1         | 0.81%   |
| 5.15.8-artix1-1                 | 1         | 0.81%   |
| 5.15.7-zen1-1-zen               | 1         | 0.81%   |
| 5.15.5-zen1-1-zen               | 1         | 0.81%   |
| 5.15.4-artix1-1                 | 1         | 0.81%   |
| 5.15.2-zen1-1-zen               | 1         | 0.81%   |
| 5.14.7-zen1-1-zen               | 1         | 0.81%   |
| 5.14.3-198-tkg-bmq              | 1         | 0.81%   |
| 5.14.14-zen1-1-zen              | 1         | 0.81%   |
| 5.14.14-artix1-1                | 1         | 0.81%   |
| 5.14.10-artix1-1                | 1         | 0.81%   |
| 5.13.8-188-tkg-pds              | 1         | 0.81%   |
| 5.13.4-artix1-1                 | 1         | 0.81%   |
| 5.13.13-xanmod1-1               | 1         | 0.81%   |
| 5.13.12-artix1-1                | 1         | 0.81%   |
| 5.12.8-zen1-1-zen               | 1         | 0.81%   |
| 5.12.6-artix1-1                 | 1         | 0.81%   |
| 5.12.5-artix1-1                 | 1         | 0.81%   |
| 5.12.2-artix1-1                 | 1         | 0.81%   |
| 5.12.14-zen1-1-zen              | 1         | 0.81%   |
| 5.12.0-rc8                      | 1         | 0.81%   |
| 5.11.8-artix1-1                 | 1         | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.14  | 10        | 8.06%   |
| 5.12.12 | 6         | 4.84%   |
| 5.7.6   | 5         | 4.03%   |
| 5.7.12  | 4         | 3.23%   |
| 5.12.8  | 4         | 3.23%   |
| 5.12.14 | 4         | 3.23%   |
| 5.10.8  | 4         | 3.23%   |
| 5.10.4  | 4         | 3.23%   |
| 5.8.8   | 3         | 2.42%   |
| 5.8.14  | 3         | 2.42%   |
| 5.8.12  | 3         | 2.42%   |
| 5.13.8  | 3         | 2.42%   |
| 5.10.6  | 3         | 2.42%   |
| 5.10.16 | 3         | 2.42%   |
| 5.9.12  | 2         | 1.61%   |
| 5.9.10  | 2         | 1.61%   |
| 5.9.0   | 2         | 1.61%   |
| 5.7.2   | 2         | 1.61%   |
| 5.15.3  | 2         | 1.61%   |
| 5.14.16 | 2         | 1.61%   |
| 5.14.14 | 2         | 1.61%   |
| 5.12.4  | 2         | 1.61%   |
| 5.11.6  | 2         | 1.61%   |
| 5.11.16 | 2         | 1.61%   |
| 5.11.10 | 2         | 1.61%   |
| 5.10.15 | 2         | 1.61%   |
| 4.19.0  | 2         | 1.61%   |
| 5.9.8   | 1         | 0.81%   |
| 5.9.6   | 1         | 0.81%   |
| 5.9.1   | 1         | 0.81%   |
| 5.8.5   | 1         | 0.81%   |
| 5.8.4   | 1         | 0.81%   |
| 5.8.0   | 1         | 0.81%   |
| 5.7.8   | 1         | 0.81%   |
| 5.6.7   | 1         | 0.81%   |
| 5.5.3   | 1         | 0.81%   |
| 5.5.10  | 1         | 0.81%   |
| 5.4.74  | 1         | 0.81%   |
| 5.15.8  | 1         | 0.81%   |
| 5.15.7  | 1         | 0.81%   |
| 5.15.5  | 1         | 0.81%   |
| 5.15.4  | 1         | 0.81%   |
| 5.15.2  | 1         | 0.81%   |
| 5.14.7  | 1         | 0.81%   |
| 5.14.3  | 1         | 0.81%   |
| 5.14.10 | 1         | 0.81%   |
| 5.13.4  | 1         | 0.81%   |
| 5.13.13 | 1         | 0.81%   |
| 5.13.12 | 1         | 0.81%   |
| 5.12.6  | 1         | 0.81%   |
| 5.12.5  | 1         | 0.81%   |
| 5.12.2  | 1         | 0.81%   |
| 5.12.0  | 1         | 0.81%   |
| 5.11.8  | 1         | 0.81%   |
| 5.11.7  | 1         | 0.81%   |
| 5.11.2  | 1         | 0.81%   |
| 5.11.12 | 1         | 0.81%   |
| 5.11.11 | 1         | 0.81%   |
| 5.11.1  | 1         | 0.81%   |
| 5.10.82 | 1         | 0.81%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 21        | 18.1%   |
| 5.12    | 19        | 16.38%  |
| 5.9     | 18        | 15.52%  |
| 5.11    | 12        | 10.34%  |
| 5.8     | 11        | 9.48%   |
| 5.7     | 10        | 8.62%   |
| 5.15    | 7         | 6.03%   |
| 5.14    | 7         | 6.03%   |
| 5.13    | 6         | 5.17%   |
| 4.19    | 2         | 1.72%   |
| 5.6     | 1         | 0.86%   |
| 5.5     | 1         | 0.86%   |
| 5.4     | 1         | 0.86%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 100       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 19        | 17.43%  |
| XFCE       | 18        | 16.51%  |
| KDE5       | 17        | 15.6%   |
| Unknown    | 16        | 14.68%  |
| X-Cinnamon | 9         | 8.26%   |
| MATE       | 6         | 5.5%    |
| Cinnamon   | 5         | 4.59%   |
| LXQt       | 4         | 3.67%   |
| KDE        | 4         | 3.67%   |
| bspwm      | 3         | 2.75%   |
| LXDE       | 2         | 1.83%   |
| xmonad     | 1         | 0.92%   |
| sway       | 1         | 0.92%   |
| openbox    | 1         | 0.92%   |
| nxde       | 1         | 0.92%   |
| i3         | 1         | 0.92%   |
| dwm        | 1         | 0.92%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 70        | 66.67%  |
| Tty     | 18        | 17.14%  |
| Wayland | 10        | 9.52%   |
| Unknown | 7         | 6.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 38        | 36.54%  |
| LightDM | 33        | 31.73%  |
| SDDM    | 26        | 25%     |
| GDM     | 4         | 3.85%   |
| XDM     | 1         | 0.96%   |
| SLiM    | 1         | 0.96%   |
| LXDM    | 1         | 0.96%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 45        | 44.12%  |
| Unknown | 14        | 13.73%  |
| ru_RU   | 8         | 7.84%   |
| fr_FR   | 7         | 6.86%   |
| en_GB   | 5         | 4.9%    |
| de_DE   | 4         | 3.92%   |
| C       | 4         | 3.92%   |
| pt_PT   | 3         | 2.94%   |
| it_IT   | 2         | 1.96%   |
| el_GR   | 2         | 1.96%   |
| pt_BR   | 1         | 0.98%   |
| pl_PL   | 1         | 0.98%   |
| ja_JP   | 1         | 0.98%   |
| es_MX   | 1         | 0.98%   |
| es_ES   | 1         | 0.98%   |
| es_AR   | 1         | 0.98%   |
| en_CA   | 1         | 0.98%   |
| bg_BG   | 1         | 0.98%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 74        | 72.55%  |
| BIOS | 28        | 27.45%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 69        | 69%     |
| Btrfs   | 21        | 21%     |
| Xfs     | 5         | 5%      |
| F2fs    | 3         | 3%      |
| Overlay | 1         | 1%      |
| Jfs     | 1         | 1%      |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 76        | 73.79%  |
| Unknown | 17        | 16.5%   |
| MBR     | 10        | 9.71%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 79        | 77.45%  |
| Yes       | 23        | 22.55%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 72        | 71.29%  |
| Yes       | 29        | 28.71%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 19        | 19%     |
| ASUSTek Computer    | 16        | 16%     |
| Hewlett-Packard     | 11        | 11%     |
| Dell                | 11        | 11%     |
| Gigabyte Technology | 9         | 9%      |
| MSI                 | 8         | 8%      |
| Acer                | 7         | 7%      |
| ASRock              | 4         | 4%      |
| Apple               | 3         | 3%      |
| Timi                | 2         | 2%      |
| GPD                 | 2         | 2%      |
| UNOWHY              | 1         | 1%      |
| Quanta              | 1         | 1%      |
| Notebook            | 1         | 1%      |
| Microsoft           | 1         | 1%      |
| Intel               | 1         | 1%      |
| Biostar             | 1         | 1%      |
| Alienware           | 1         | 1%      |
| Acidanthera         | 1         | 1%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Timi RedmiBook 14 II                   | 2         | 2%      |
| MSI MS-7C02                            | 2         | 2%      |
| Lenovo IdeaPad 5 15IIL05 81YK          | 2         | 2%      |
| GPD P2 MAX                             | 2         | 2%      |
| Gigabyte 970A-DS3P                     | 2         | 2%      |
| Dell Precision 7550                    | 2         | 2%      |
| Apple MacBookAir7,2                    | 2         | 2%      |
| UNOWHY Y13G010S4EI                     | 1         | 1%      |
| Quanta SWH                             | 1         | 1%      |
| Notebook N130BU                        | 1         | 1%      |
| MSI MS-7C37                            | 1         | 1%      |
| MSI MS-7B79                            | 1         | 1%      |
| MSI MS-7A69                            | 1         | 1%      |
| MSI MS-7A38                            | 1         | 1%      |
| MSI MS-7821                            | 1         | 1%      |
| MSI GP72 7RDX                          | 1         | 1%      |
| Microsoft Surface Pro                  | 1         | 1%      |
| Lenovo ThinkPad W500 4063CJ5           | 1         | 1%      |
| Lenovo ThinkPad T480s 20L8S3D400       | 1         | 1%      |
| Lenovo ThinkPad T420 4236H45           | 1         | 1%      |
| Lenovo ThinkPad T14 Gen 1 20UES1GC00   | 1         | 1%      |
| Lenovo ThinkPad T14 Gen 1 20S1S07800   | 1         | 1%      |
| Lenovo ThinkPad P1 Gen 3 20TH001EMH    | 1         | 1%      |
| Lenovo ThinkPad 11e 5th Gen 20LNS0P500 | 1         | 1%      |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 1         | 1%      |
| Lenovo LaVie Z 20FF0012US              | 1         | 1%      |
| Lenovo IdeaPadFlex 5 14ALC05 82HU      | 1         | 1%      |
| Lenovo IdeaPad L340-17IRH Gaming 81LL  | 1         | 1%      |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG   | 1         | 1%      |
| Lenovo IdeaPad Flex 5 14ARE05 81X2     | 1         | 1%      |
| Lenovo IdeaPad 510-15IKB 80SV          | 1         | 1%      |
| Lenovo IdeaPad 330-15IKB 81DE          | 1         | 1%      |
| Lenovo B590 20206                      | 1         | 1%      |
| Lenovo B570e HuronRiver Platform       | 1         | 1%      |
| Intel DX58SO2 AAG10925-205             | 1         | 1%      |
| HP ProBook 450 G6                      | 1         | 1%      |
| HP OMEN Laptop 15-en0xxx               | 1         | 1%      |
| HP Laptop 17z-ca300                    | 1         | 1%      |
| HP Laptop 14s-cf3xxx                   | 1         | 1%      |
| HP Compaq 8200 Elite SFF PC            | 1         | 1%      |
| HP 280 G1 MT                           | 1         | 1%      |
| HP 255 G7 Notebook PC                  | 1         | 1%      |
| HP 250 G7 Notebook PC                  | 1         | 1%      |
| HP 250 G4 Notebook PC                  | 1         | 1%      |
| HP 250 G3                              | 1         | 1%      |
| HP 15                                  | 1         | 1%      |
| Gigabyte X570 AORUS ELITE              | 1         | 1%      |
| Gigabyte X399 AORUS XTREME             | 1         | 1%      |
| Gigabyte P55-USB3                      | 1         | 1%      |
| Gigabyte B450M DS3H                    | 1         | 1%      |
| Gigabyte AERO 15-X9                    | 1         | 1%      |
| Gigabyte 990FXA-UD5                    | 1         | 1%      |
| Gigabyte 990FXA-UD3 R5                 | 1         | 1%      |
| Dell Precision M6600                   | 1         | 1%      |
| Dell Precision 5520                    | 1         | 1%      |
| Dell Precision 3540                    | 1         | 1%      |
| Dell OptiPlex 5080                     | 1         | 1%      |
| Dell Latitude E6530                    | 1         | 1%      |
| Dell Latitude E6440                    | 1         | 1%      |
| Dell Inspiron 5570                     | 1         | 1%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 7         | 7%      |
| Lenovo IdeaPad      | 7         | 7%      |
| Dell Precision      | 5         | 5%      |
| Acer Aspire         | 5         | 5%      |
| HP 250              | 3         | 3%      |
| Dell Inspiron       | 3         | 3%      |
| Timi RedmiBook      | 2         | 2%      |
| MSI MS-7C02         | 2         | 2%      |
| HP Laptop           | 2         | 2%      |
| GPD P2              | 2         | 2%      |
| Gigabyte 970A-DS3P  | 2         | 2%      |
| Dell Latitude       | 2         | 2%      |
| ASUS TUF            | 2         | 2%      |
| ASUS ROG            | 2         | 2%      |
| ASUS PRIME          | 2         | 2%      |
| Apple MacBookAir7   | 2         | 2%      |
| UNOWHY Y13G010S4EI  | 1         | 1%      |
| Quanta SWH          | 1         | 1%      |
| Notebook N130BU     | 1         | 1%      |
| MSI MS-7C37         | 1         | 1%      |
| MSI MS-7B79         | 1         | 1%      |
| MSI MS-7A69         | 1         | 1%      |
| MSI MS-7A38         | 1         | 1%      |
| MSI MS-7821         | 1         | 1%      |
| MSI GP72            | 1         | 1%      |
| Microsoft Surface   | 1         | 1%      |
| Lenovo ThinkBook    | 1         | 1%      |
| Lenovo LaVie        | 1         | 1%      |
| Lenovo IdeaPadFlex  | 1         | 1%      |
| Lenovo B590         | 1         | 1%      |
| Lenovo B570e        | 1         | 1%      |
| Intel DX58SO2       | 1         | 1%      |
| HP ProBook          | 1         | 1%      |
| HP OMEN             | 1         | 1%      |
| HP Compaq           | 1         | 1%      |
| HP 280              | 1         | 1%      |
| HP 255              | 1         | 1%      |
| HP 15               | 1         | 1%      |
| Gigabyte X570       | 1         | 1%      |
| Gigabyte X399       | 1         | 1%      |
| Gigabyte P55-USB3   | 1         | 1%      |
| Gigabyte B450M      | 1         | 1%      |
| Gigabyte AERO       | 1         | 1%      |
| Gigabyte 990FXA-UD5 | 1         | 1%      |
| Gigabyte 990FXA-UD3 | 1         | 1%      |
| Dell OptiPlex       | 1         | 1%      |
| Biostar G31D-M7     | 1         | 1%      |
| ASUS VivoBook       | 1         | 1%      |
| ASUS SABERTOOTH     | 1         | 1%      |
| ASUS P8H61-M        | 1         | 1%      |
| ASUS P8B75-M        | 1         | 1%      |
| ASUS K53SC          | 1         | 1%      |
| ASUS K50IE          | 1         | 1%      |
| ASUS GL702ZC        | 1         | 1%      |
| ASUS G11CD          | 1         | 1%      |
| ASUS E402NA         | 1         | 1%      |
| ASUS All            | 1         | 1%      |
| ASRock X570         | 1         | 1%      |
| ASRock H310CM-DVS   | 1         | 1%      |
| ASRock FM2A88X-ITX+ | 1         | 1%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 30        | 30%     |
| 2019 | 22        | 22%     |
| 2021 | 8         | 8%      |
| 2018 | 7         | 7%      |
| 2014 | 6         | 6%      |
| 2017 | 5         | 5%      |
| 2015 | 5         | 5%      |
| 2011 | 5         | 5%      |
| 2012 | 4         | 4%      |
| 2013 | 3         | 3%      |
| 2016 | 2         | 2%      |
| 2010 | 2         | 2%      |
| 2009 | 1         | 1%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 60        | 60%     |
| Desktop     | 36        | 36%     |
| Convertible | 2         | 2%      |
| Tablet      | 1         | 1%      |
| All in one  | 1         | 1%      |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 99        | 99%     |
| Enabled  | 1         | 1%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 100       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 29        | 28.43%  |
| 8.01-16.0   | 26        | 25.49%  |
| 4.01-8.0    | 17        | 16.67%  |
| 3.01-4.0    | 15        | 14.71%  |
| 32.01-64.0  | 7         | 6.86%   |
| 64.01-256.0 | 6         | 5.88%   |
| 1.01-2.0    | 2         | 1.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 28        | 24.35%  |
| 1.01-2.0   | 27        | 23.48%  |
| 3.01-4.0   | 20        | 17.39%  |
| 4.01-8.0   | 19        | 16.52%  |
| 0.51-1.0   | 11        | 9.57%   |
| 8.01-16.0  | 5         | 4.35%   |
| 0.01-0.5   | 3         | 2.61%   |
| 16.01-24.0 | 2         | 1.74%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 53        | 51.46%  |
| 2      | 30        | 29.13%  |
| 3      | 13        | 12.62%  |
| 4      | 3         | 2.91%   |
| 6      | 2         | 1.94%   |
| 8      | 1         | 0.97%   |
| 7      | 1         | 0.97%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 75        | 74.26%  |
| Yes       | 26        | 25.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 85%     |
| No        | 15        | 15%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 78        | 78%     |
| No        | 22        | 22%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 69        | 67.65%  |
| No        | 33        | 32.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 18        | 18%     |
| Germany     | 11        | 11%     |
| Russia      | 9         | 9%      |
| France      | 9         | 9%      |
| Ukraine     | 4         | 4%      |
| UK          | 4         | 4%      |
| Switzerland | 4         | 4%      |
| Poland      | 4         | 4%      |
| Turkey      | 3         | 3%      |
| Greece      | 3         | 3%      |
| Canada      | 3         | 3%      |
| Brazil      | 3         | 3%      |
| Netherlands | 2         | 2%      |
| Italy       | 2         | 2%      |
| Bulgaria    | 2         | 2%      |
| Argentina   | 2         | 2%      |
| Uzbekistan  | 1         | 1%      |
| Sweden      | 1         | 1%      |
| Spain       | 1         | 1%      |
| Slovenia    | 1         | 1%      |
| Mexico      | 1         | 1%      |
| Lithuania   | 1         | 1%      |
| Japan       | 1         | 1%      |
| Iran        | 1         | 1%      |
| Indonesia   | 1         | 1%      |
| India       | 1         | 1%      |
| Hong Kong   | 1         | 1%      |
| China       | 1         | 1%      |
| Chile       | 1         | 1%      |
| Bangladesh  | 1         | 1%      |
| Azerbaijan  | 1         | 1%      |
| Austria     | 1         | 1%      |
| Algeria     | 1         | 1%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Paris                  | 5         | 4.72%   |
| Frankfurt am Main      | 4         | 3.77%   |
| Seattle                | 3         | 2.83%   |
| Kyiv                   | 3         | 2.83%   |
| St Petersburg          | 2         | 1.89%   |
| Sofia                  | 2         | 1.89%   |
| San Ramon              | 2         | 1.89%   |
| Neuchatel              | 2         | 1.89%   |
| Los Angeles            | 2         | 1.89%   |
| K?�odzko               | 2         | 1.89%   |
| Geneva                 | 2         | 1.89%   |
| Berlin                 | 2         | 1.89%   |
| Amsterdam              | 2         | 1.89%   |
| Çorum                 | 1         | 0.94%   |
| Zaporizhzhya           | 1         | 0.94%   |
| York                   | 1         | 0.94%   |
| Yekaterinburg          | 1         | 0.94%   |
| Xirdalan               | 1         | 0.94%   |
| Wigan                  | 1         | 0.94%   |
| Vilnius                | 1         | 0.94%   |
| Villiers-sur-Orge      | 1         | 0.94%   |
| Vienna                 | 1         | 0.94%   |
| Vancouver              | 1         | 0.94%   |
| Valdahon               | 1         | 0.94%   |
| Utsunomiya             | 1         | 0.94%   |
| Upper Norwood          | 1         | 0.94%   |
| Ufa                    | 1         | 0.94%   |
| Towanda                | 1         | 0.94%   |
| Toronto                | 1         | 0.94%   |
| Thessaloniki           | 1         | 0.94%   |
| Thassos                | 1         | 0.94%   |
| Tehran                 | 1         | 0.94%   |
| Syeverodonets'k        | 1         | 0.94%   |
| Surgut                 | 1         | 0.94%   |
| Stuttgart              | 1         | 0.94%   |
| Stockholm              | 1         | 0.94%   |
| Statesboro             | 1         | 0.94%   |
| Srednyaya Akhtuba      | 1         | 0.94%   |
| Santiago               | 1         | 0.94%   |
| Santa Fe               | 1         | 0.94%   |
| Sant'Agata Bolognese   | 1         | 0.94%   |
| San Miguel de Tucumán | 1         | 0.94%   |
| Sainte-Severe          | 1         | 0.94%   |
| Roseburg               | 1         | 0.94%   |
| Riverview              | 1         | 0.94%   |
| Quincy                 | 1         | 0.94%   |
| Piraeus                | 1         | 0.94%   |
| Ordu                   | 1         | 0.94%   |
| Onda                   | 1         | 0.94%   |
| Omsk                   | 1         | 0.94%   |
| Obernai                | 1         | 0.94%   |
| Nuremberg              | 1         | 0.94%   |
| Nottingham             | 1         | 0.94%   |
| Nantes                 | 1         | 0.94%   |
| Mount Pearl            | 1         | 0.94%   |
| Moscow                 | 1         | 0.94%   |
| Milton                 | 1         | 0.94%   |
| Mestre                 | 1         | 0.94%   |
| Mesquite               | 1         | 0.94%   |
| Malda                  | 1         | 0.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 38     | 16.87%  |
| WDC                 | 26        | 46     | 15.66%  |
| Seagate             | 25        | 31     | 15.06%  |
| Toshiba             | 13        | 14     | 7.83%   |
| Crucial             | 9         | 15     | 5.42%   |
| Kingston            | 8         | 9      | 4.82%   |
| Intel               | 7         | 12     | 4.22%   |
| SK Hynix            | 6         | 13     | 3.61%   |
| SanDisk             | 6         | 8      | 3.61%   |
| Hitachi             | 5         | 6      | 3.01%   |
| HGST                | 4         | 5      | 2.41%   |
| China               | 3         | 3      | 1.81%   |
| Apple               | 3         | 4      | 1.81%   |
| Unknown             | 2         | 2      | 1.2%    |
| SPCC                | 2         | 2      | 1.2%    |
| PNY                 | 2         | 2      | 1.2%    |
| Phison Electronics  | 2         | 3      | 1.2%    |
| MAXTOR              | 2         | 2      | 1.2%    |
| Linux               | 2         | 2      | 1.2%    |
| Union Memory        | 1         | 1      | 0.6%    |
| TS512GMT            | 1         | 3      | 0.6%    |
| Transcend           | 1         | 1      | 0.6%    |
| Solid State Storage | 1         | 1      | 0.6%    |
| LDLC                | 1         | 6      | 0.6%    |
| JMicron             | 1         | 1      | 0.6%    |
| Intenso             | 1         | 1      | 0.6%    |
| Hewlett-Packard     | 1         | 1      | 0.6%    |
| GOODRAM             | 1         | 1      | 0.6%    |
| Corsair             | 1         | 1      | 0.6%    |
| AMD                 | 1         | 1      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Toshiba DT01ACA100 1TB                  | 3         | 1.61%   |
| Seagate ST3500418AS 500GB               | 3         | 1.61%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 1.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 1.61%   |
| Sandisk NVMe SSD Drive 512GB            | 3         | 1.61%   |
| Samsung SSD 970 EVO 1TB                 | 3         | 1.61%   |
| Samsung SSD 860 EVO 250GB               | 3         | 1.61%   |
| HGST HTS545050A7E680 500GB              | 3         | 1.61%   |
| Crucial CT1000MX500SSD1 1TB             | 3         | 1.61%   |
| WDC WD80EZAZ-11TDBA0 8TB                | 2         | 1.08%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 1.08%   |
| WDC WD10EZEX-08WN4A0 1TB                | 2         | 1.08%   |
| Toshiba MQ04ABF100 1TB                  | 2         | 1.08%   |
| SPCC Solid State Disk 240GB             | 2         | 1.08%   |
| Samsung NVMe SSD Drive 1TB              | 2         | 1.08%   |
| Samsung MZYTY256HDHP-000L2 256GB SSD    | 2         | 1.08%   |
| Samsung MZNLH512HALU-00000 512GB SSD    | 2         | 1.08%   |
| Phison PCIe SSD 512GB                   | 2         | 1.08%   |
| Linux scsi_debug 8.3MB                  | 2         | 1.08%   |
| Crucial CT240BX500SSD1 240GB            | 2         | 1.08%   |
| China SATA SSD 960GB                    | 2         | 1.08%   |
| Apple SSD SM0256G 256GB                 | 2         | 1.08%   |
| WDC WDS500G2B0C-00PXH0 500GB            | 1         | 0.54%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.54%   |
| WDC WDS256G1X0C-00ENX0 256GB            | 1         | 0.54%   |
| WDC WDS200T2B0B-00YS70 2TB SSD          | 1         | 0.54%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.54%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 1         | 0.54%   |
| WDC WDBNCE5000PNC 500GB SSD             | 1         | 0.54%   |
| WDC WD6001FZWX-00A2VA0 6TB              | 1         | 0.54%   |
| WDC WD5003ABYX-18WERA0 500GB            | 1         | 0.54%   |
| WDC WD5000LPVX-75V0TT0 500GB            | 1         | 0.54%   |
| WDC WD5000LPVX-00V0TT0 500GB            | 1         | 0.54%   |
| WDC WD5000BPVT-22HXZT3 500GB            | 1         | 0.54%   |
| WDC WD5000AAKX-60U6AA0 500GB            | 1         | 0.54%   |
| WDC WD40EZRZ-00WN9B0 4TB                | 1         | 0.54%   |
| WDC WD4003FZEX-00Z4SA0 4TB              | 1         | 0.54%   |
| WDC WD4003FFBX-68MU3N0 4TB              | 1         | 0.54%   |
| WDC WD3200LPVT-00FMCT0 320GB            | 1         | 0.54%   |
| WDC WD30EZRX-00DC0B0 3TB                | 1         | 0.54%   |
| WDC WD30EFRX-68EUZN0 3TB                | 1         | 0.54%   |
| WDC WD2500HHTZ-04N21V0 250GB            | 1         | 0.54%   |
| WDC WD20EZRX-00D8PB0 2TB                | 1         | 0.54%   |
| WDC WD20EARS-00MVWB0 2TB                | 1         | 0.54%   |
| WDC WD2003FZEX-00SRLA0 2TB              | 1         | 0.54%   |
| WDC WD15EARS-22MVWB0 1TB                | 1         | 0.54%   |
| WDC WD10SPZX-60Z10T0 1TB                | 1         | 0.54%   |
| WDC WD10SPZX-21Z10T0 1TB                | 1         | 0.54%   |
| WDC WD10EZRZ-00HTKB0 1TB                | 1         | 0.54%   |
| WDC WD10EZEX-00BN5A0 1TB                | 1         | 0.54%   |
| WDC WD100EMAZ-00WJTA0 10TB              | 1         | 0.54%   |
| Unknown SD/MMC/MS PRO 7GB               | 1         | 0.54%   |
| Unknown DA4064  64GB                    | 1         | 0.54%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB | 1         | 0.54%   |
| TS512GMT S430S 512GB                    | 1         | 0.54%   |
| Transcend TS1TMTE220S 1TB               | 1         | 0.54%   |
| Toshiba THNSNH128GMCT 128GB SSD         | 1         | 0.54%   |
| Toshiba MQ01ABF050 500GB                | 1         | 0.54%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 0.54%   |
| Toshiba MK7575GSX 752GB                 | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 25        | 31     | 35.71%  |
| WDC     | 22        | 36     | 31.43%  |
| Toshiba | 10        | 11     | 14.29%  |
| Hitachi | 5         | 6      | 7.14%   |
| HGST    | 4         | 5      | 5.71%   |
| MAXTOR  | 2         | 2      | 2.86%   |
| Unknown | 1         | 1      | 1.43%   |
| JMicron | 1         | 1      | 1.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 16     | 25%     |
| Crucial             | 9         | 15     | 17.31%  |
| Kingston            | 6         | 6      | 11.54%  |
| WDC                 | 4         | 7      | 7.69%   |
| China               | 3         | 3      | 5.77%   |
| Apple               | 3         | 4      | 5.77%   |
| SPCC                | 2         | 2      | 3.85%   |
| Linux               | 2         | 2      | 3.85%   |
| Intel               | 2         | 3      | 3.85%   |
| Toshiba             | 1         | 1      | 1.92%   |
| SK Hynix            | 1         | 1      | 1.92%   |
| SanDisk             | 1         | 1      | 1.92%   |
| PNY                 | 1         | 1      | 1.92%   |
| LDLC                | 1         | 6      | 1.92%   |
| Intenso             | 1         | 1      | 1.92%   |
| GOODRAM             | 1         | 1      | 1.92%   |
| AMD                 | 1         | 1      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 59        | 93     | 39.86%  |
| SSD     | 47        | 71     | 31.76%  |
| NVMe    | 40        | 67     | 27.03%  |
| MMC     | 1         | 1      | 0.68%   |
| Unknown | 1         | 3      | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 80        | 160    | 63.49%  |
| NVMe | 40        | 67     | 31.75%  |
| SAS  | 5         | 7      | 3.97%   |
| MMC  | 1         | 1      | 0.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 54        | 83     | 48.21%  |
| 0.51-1.0   | 37        | 53     | 33.04%  |
| 1.01-2.0   | 11        | 12     | 9.82%   |
| 3.01-4.0   | 4         | 4      | 3.57%   |
| 2.01-3.0   | 3         | 3      | 2.68%   |
| 4.01-10.0  | 3         | 9      | 2.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 27        | 26.47%  |
| 251-500        | 17        | 16.67%  |
| 1001-2000      | 13        | 12.75%  |
| 501-1000       | 13        | 12.75%  |
| More than 3000 | 9         | 8.82%   |
| 2001-3000      | 8         | 7.84%   |
| 51-100         | 7         | 6.86%   |
| Unknown        | 5         | 4.9%    |
| 1-20           | 2         | 1.96%   |
| 21-50          | 1         | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 25        | 23.15%  |
| 501-1000       | 18        | 16.67%  |
| 51-100         | 15        | 13.89%  |
| 21-50          | 13        | 12.04%  |
| 101-250        | 13        | 12.04%  |
| 1001-2000      | 8         | 7.41%   |
| 251-500        | 6         | 5.56%   |
| More than 3000 | 5         | 4.63%   |
| Unknown        | 5         | 4.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB       | 2         | 2      | 10.53%  |
| WDC WD3200LPVT-00FMCT0 320GB     | 1         | 1      | 5.26%   |
| WDC WD30EZRX-00DC0B0 3TB         | 1         | 1      | 5.26%   |
| Toshiba MQ01ABD100 1TB           | 1         | 1      | 5.26%   |
| Toshiba MK7575GSX 752GB          | 1         | 1      | 5.26%   |
| Toshiba MK5065GSX 500GB          | 1         | 1      | 5.26%   |
| Seagate ST8000DM004-2CX188 8TB   | 1         | 1      | 5.26%   |
| Seagate ST2000DX002-2DV164 2TB   | 1         | 1      | 5.26%   |
| Seagate ST2000DM006-2DM164 2TB   | 1         | 1      | 5.26%   |
| Seagate ST1000LM035-1RK172 1TB   | 1         | 1      | 5.26%   |
| MAXTOR 6Y080M0 80GB              | 1         | 1      | 5.26%   |
| LDLC SSD 120GB                   | 1         | 3      | 5.26%   |
| Kingston SUV400S37240G 240GB SSD | 1         | 1      | 5.26%   |
| Intel SSDSC2BW480A4 480GB        | 1         | 2      | 5.26%   |
| Intel SSDPEKKW128G7 128GB        | 1         | 1      | 5.26%   |
| Hitachi HTS547550A9E384 500GB    | 1         | 1      | 5.26%   |
| Hitachi HTS542516K9SA00 160GB    | 1         | 1      | 5.26%   |
| Hewlett-Packard SSD EX900 250GB  | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor          | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| Seagate         | 4         | 4      | 21.05%  |
| Toshiba         | 3         | 3      | 15.79%  |
| WDC             | 2         | 2      | 10.53%  |
| Intel           | 2         | 3      | 10.53%  |
| Hitachi         | 2         | 2      | 10.53%  |
| HGST            | 2         | 2      | 10.53%  |
| MAXTOR          | 1         | 1      | 5.26%   |
| LDLC            | 1         | 3      | 5.26%   |
| Kingston        | 1         | 1      | 5.26%   |
| Hewlett-Packard | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 28.57%  |
| Toshiba | 3         | 3      | 21.43%  |
| WDC     | 2         | 2      | 14.29%  |
| Hitachi | 2         | 2      | 14.29%  |
| HGST    | 2         | 2      | 14.29%  |
| MAXTOR  | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 14     | 73.68%  |
| SSD  | 3         | 6      | 15.79%  |
| NVMe | 2         | 2      | 10.53%  |

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
| Works    | 62        | 121    | 53.91%  |
| Detected | 35        | 92     | 30.43%  |
| Malfunc  | 18        | 22     | 15.65%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 58        | 41.43%  |
| AMD                            | 28        | 20%     |
| Samsung Electronics            | 19        | 13.57%  |
| Sandisk                        | 7         | 5%      |
| SK Hynix                       | 5         | 3.57%   |
| Phison Electronics             | 4         | 2.86%   |
| Marvell Technology Group       | 4         | 2.86%   |
| ASMedia Technology             | 3         | 2.14%   |
| Union Memory (Shenzhen)        | 2         | 1.43%   |
| Toshiba America Info Systems   | 2         | 1.43%   |
| Silicon Motion                 | 2         | 1.43%   |
| Kingston Technology Company    | 2         | 1.43%   |
| Solid State Storage Technology | 1         | 0.71%   |
| Nvidia                         | 1         | 0.71%   |
| JMicron Technology             | 1         | 0.71%   |
| Broadcom / LSI                 | 1         | 0.71%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 20        | 12.58%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11        | 6.92%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 4.4%    |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 4.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 3.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 3.14%   |
| Phison E12 NVMe Controller                                                     | 4         | 2.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 2.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 2.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 2.52%   |
| SK Hynix Non-Volatile memory controller                                        | 3         | 1.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.89%   |
| Samsung NVMe SSD Controller 980                                                | 3         | 1.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.89%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.89%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 2         | 1.26%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 1.26%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 1.26%   |
| Sandisk Non-Volatile memory controller                                         | 2         | 1.26%   |
| Samsung Electronics SATA controller                                            | 2         | 1.26%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2         | 1.26%   |
| Intel Volume Management Device NVMe RAID Controller                            | 2         | 1.26%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 1.26%   |
| Intel SSD 660P Series                                                          | 2         | 1.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.26%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 1.26%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 2         | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 1.26%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.26%   |
| AMD 300 Series Chipset SATA Controller                                         | 2         | 1.26%   |
| Solid State Storage Non-Volatile memory controller                             | 1         | 0.63%   |
| SK Hynix Gold P31 SSD                                                          | 1         | 0.63%   |
| SK Hynix BC511                                                                 | 1         | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 1         | 0.63%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 1         | 0.63%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 1         | 0.63%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 1         | 0.63%   |
| Sandisk WD Black NVMe SSD                                                      | 1         | 0.63%   |
| Nvidia MCP79 AHCI Controller                                                   | 1         | 0.63%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                     | 1         | 0.63%   |
| Marvell Group 88SE912x IDE Controller                                          | 1         | 0.63%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 1         | 0.63%   |
| Kingston Company Company Non-Volatile memory controller                        | 1         | 0.63%   |
| Kingston Company A2000 NVMe SSD                                                | 1         | 0.63%   |
| JMicron JMB363 SATA/IDE Controller                                             | 1         | 0.63%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 1         | 0.63%   |
| Intel SSD 600P Series                                                          | 1         | 0.63%   |
| Intel SATA Controller [RAID mode]                                              | 1         | 0.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 1         | 0.63%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 1         | 0.63%   |
| Intel Comet Lake SATA AHCI Controller                                          | 1         | 0.63%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 1         | 0.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 1         | 0.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 1         | 0.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 1         | 0.63%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 1         | 0.63%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]            | 1         | 0.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 1         | 0.63%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 1         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 80        | 58.39%  |
| NVMe | 41        | 29.93%  |
| RAID | 8         | 5.84%   |
| IDE  | 7         | 5.11%   |
| SAS  | 1         | 0.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 69        | 69%     |
| AMD    | 31        | 31%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor         | 3         | 2.97%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 3         | 2.97%   |
| AMD FX-8350 Eight-Core Processor            | 3         | 2.97%   |
| Intel Core m3-8100Y CPU @ 1.10GHz           | 2         | 1.98%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2         | 1.98%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.98%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 1.98%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 2         | 1.98%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 2         | 1.98%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 2         | 1.98%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 2         | 1.98%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.98%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2         | 1.98%   |
| Intel Xeon CPU E3-1505M v6 @ 3.00GHz        | 1         | 0.99%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 1         | 0.99%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.99%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.99%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 1         | 0.99%   |
| Intel Core m3-7Y30 CPU @ 1.00GHz            | 1         | 0.99%   |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.99%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 1         | 0.99%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 0.99%   |
| Intel Core i7-9700F CPU @ 3.00GHz           | 1         | 0.99%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.99%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.99%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 1         | 0.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 1         | 0.99%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.99%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 1         | 0.99%   |
| Intel Core i7-2820QM CPU @ 2.30GHz          | 1         | 0.99%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 1         | 0.99%   |
| Intel Core i7-10850H CPU @ 2.70GHz          | 1         | 0.99%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.99%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.99%   |
| Intel Core i7 CPU 970 @ 3.20GHz             | 1         | 0.99%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 1         | 0.99%   |
| Intel Core i5-8365U CPU @ 1.60GHz           | 1         | 0.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 1         | 0.99%   |
| Intel Core i5-7600K CPU @ 3.80GHz           | 1         | 0.99%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 0.99%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 1         | 0.99%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 1         | 0.99%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 1         | 0.99%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 1         | 0.99%   |
| Intel Core i5-4258U CPU @ 2.40GHz           | 1         | 0.99%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 0.99%   |
| Intel Core i5-3330 CPU @ 3.00GHz            | 1         | 0.99%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 1         | 0.99%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 1         | 0.99%   |
| Intel Core i5-2500 CPU @ 3.30GHz            | 1         | 0.99%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 1         | 0.99%   |
| Intel Core i5-2310 CPU @ 2.90GHz            | 1         | 0.99%   |
| Intel Core i5-10500T CPU @ 2.30GHz          | 1         | 0.99%   |
| Intel Core i5 CPU 660 @ 3.33GHz             | 1         | 0.99%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 1         | 0.99%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 1         | 0.99%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 1         | 0.99%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 1         | 0.99%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 1         | 0.99%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 1         | 0.99%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 25        | 25%     |
| Intel Core i7           | 16        | 16%     |
| AMD Ryzen 7             | 9         | 9%      |
| Intel Core i3           | 8         | 8%      |
| AMD Ryzen 5             | 8         | 8%      |
| Intel Celeron           | 5         | 5%      |
| AMD Ryzen 9             | 4         | 4%      |
| AMD FX                  | 4         | 4%      |
| Intel Core m3           | 3         | 3%      |
| Intel Core 2 Duo        | 3         | 3%      |
| Other                   | 2         | 2%      |
| Intel Pentium           | 2         | 2%      |
| Intel Core i9           | 2         | 2%      |
| AMD Ryzen 3             | 2         | 2%      |
| Intel Xeon              | 1         | 1%      |
| Intel Pentium Silver    | 1         | 1%      |
| Intel Pentium Dual-Core | 1         | 1%      |
| AMD Ryzen Threadripper  | 1         | 1%      |
| AMD Ryzen 5 PRO         | 1         | 1%      |
| AMD Phenom II X4        | 1         | 1%      |
| AMD A10                 | 1         | 1%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 37        | 37%     |
| 4      | 27        | 27%     |
| 6      | 15        | 15%     |
| 8      | 14        | 14%     |
| 12     | 4         | 4%      |
| 3      | 2         | 2%      |
| 32     | 1         | 1%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 100       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 71        | 71%     |
| 1      | 29        | 29%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 100       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 17        | 16.35%  |
| 0x206a7    | 6         | 5.77%   |
| 0x806e9    | 5         | 4.81%   |
| 0x906ed    | 4         | 3.85%   |
| 0x906e9    | 4         | 3.85%   |
| 0x306d4    | 4         | 3.85%   |
| 0x306c3    | 4         | 3.85%   |
| 0x08701013 | 4         | 3.85%   |
| 0x08600106 | 4         | 3.85%   |
| 0xa0652    | 3         | 2.88%   |
| 0x806ec    | 3         | 2.88%   |
| 0x706e5    | 3         | 2.88%   |
| 0x306a9    | 3         | 2.88%   |
| 0x1067a    | 3         | 2.88%   |
| 0x08701021 | 3         | 2.88%   |
| 0x0800820d | 3         | 2.88%   |
| 0x06000822 | 3         | 2.88%   |
| 0x806ea    | 2         | 1.92%   |
| 0x806c1    | 2         | 1.92%   |
| 0x706a1    | 2         | 1.92%   |
| 0x40651    | 2         | 1.92%   |
| 0xa0653    | 1         | 0.96%   |
| 0x906ea    | 1         | 0.96%   |
| 0x6fd      | 1         | 0.96%   |
| 0x506e3    | 1         | 0.96%   |
| 0x506c9    | 1         | 0.96%   |
| 0x406e3    | 1         | 0.96%   |
| 0x30678    | 1         | 0.96%   |
| 0x206c2    | 1         | 0.96%   |
| 0x20655    | 1         | 0.96%   |
| 0x20652    | 1         | 0.96%   |
| 0x0a201009 | 1         | 0.96%   |
| 0x08608103 | 1         | 0.96%   |
| 0x08600103 | 1         | 0.96%   |
| 0x0810100b | 1         | 0.96%   |
| 0x08101007 | 1         | 0.96%   |
| 0x0800820b | 1         | 0.96%   |
| 0x08001138 | 1         | 0.96%   |
| 0x08001137 | 1         | 0.96%   |
| 0x06003106 | 1         | 0.96%   |
| 0x06000852 | 1         | 0.96%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 24        | 24%     |
| Zen 2         | 14        | 14%     |
| SandyBridge   | 7         | 7%      |
| Haswell       | 7         | 7%      |
| Zen+          | 5         | 5%      |
| CometLake     | 5         | 5%      |
| Broadwell     | 5         | 5%      |
| Zen           | 4         | 4%      |
| Piledriver    | 4         | 4%      |
| Westmere      | 3         | 3%      |
| Penryn        | 3         | 3%      |
| IvyBridge     | 3         | 3%      |
| IceLake       | 3         | 3%      |
| TigerLake     | 2         | 2%      |
| Skylake       | 2         | 2%      |
| Goldmont plus | 2         | 2%      |
| Zen 3         | 1         | 1%      |
| Steamroller   | 1         | 1%      |
| Silvermont    | 1         | 1%      |
| K10           | 1         | 1%      |
| Goldmont      | 1         | 1%      |
| Core          | 1         | 1%      |
| Unknown       | 1         | 1%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 55        | 45.45%  |
| AMD    | 34        | 28.1%   |
| Nvidia | 32        | 26.45%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 7         | 5.69%   |
| Intel HD Graphics 620                                                       | 6         | 4.88%   |
| AMD Renoir                                                                  | 6         | 4.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 5         | 4.07%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 4         | 3.25%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 4         | 3.25%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 3         | 2.44%   |
| Intel HD Graphics 5500                                                      | 3         | 2.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 3         | 2.44%   |
| Nvidia TU106GLM [Quadro RTX 3000 Mobile / Max-Q]                            | 2         | 1.63%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 1.63%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 1.63%   |
| Nvidia GM206 [GeForce GTX 950]                                              | 2         | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 2         | 1.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 2         | 1.63%   |
| Intel UHD Graphics 620                                                      | 2         | 1.63%   |
| Intel UHD Graphics 615                                                      | 2         | 1.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 2         | 1.63%   |
| Intel HD Graphics 630                                                       | 2         | 1.63%   |
| Intel HD Graphics 6000                                                      | 2         | 1.63%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 2         | 1.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 2         | 1.63%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2         | 1.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 1         | 0.81%   |
| Nvidia TU117M                                                               | 1         | 0.81%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 1         | 0.81%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 1         | 0.81%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                     | 1         | 0.81%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                      | 1         | 0.81%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 1         | 0.81%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 1         | 0.81%   |
| Nvidia GT218M [GeForce 310M]                                                | 1         | 0.81%   |
| Nvidia GT218 [GeForce 210]                                                  | 1         | 0.81%   |
| Nvidia GP108M [GeForce MX330]                                               | 1         | 0.81%   |
| Nvidia GP108M [GeForce MX150]                                               | 1         | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 1         | 0.81%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 1         | 0.81%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 1         | 0.81%   |
| Nvidia GM200 [GeForce GTX 980 Ti]                                           | 1         | 0.81%   |
| Nvidia GM108M [GeForce 840M]                                                | 1         | 0.81%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                       | 1         | 0.81%   |
| Nvidia GM107 [GeForce 940MX]                                                | 1         | 0.81%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 0.81%   |
| Nvidia GF119M [GeForce GT 520MX]                                            | 1         | 0.81%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1         | 0.81%   |
| Nvidia GF108M [GeForce GT 520M]                                             | 1         | 0.81%   |
| Nvidia GF108GLM [NVS 5200M]                                                 | 1         | 0.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 0.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 1         | 0.81%   |
| Intel HD Graphics P630                                                      | 1         | 0.81%   |
| Intel HD Graphics 615                                                       | 1         | 0.81%   |
| Intel HD Graphics 500                                                       | 1         | 0.81%   |
| Intel GeminiLake [UHD Graphics 605]                                         | 1         | 0.81%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 1         | 0.81%   |
| Intel Core Processor Integrated Graphics Controller                         | 1         | 0.81%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 1         | 0.81%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 1         | 0.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 1         | 0.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 1         | 0.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 1         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 37        | 36.27%  |
| 1 x AMD        | 28        | 27.45%  |
| 1 x Nvidia     | 17        | 16.67%  |
| Intel + Nvidia | 13        | 12.75%  |
| Intel + AMD    | 3         | 2.94%   |
| 2 x AMD        | 2         | 1.96%   |
| AMD + Nvidia   | 2         | 1.96%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 81        | 79.41%  |
| Proprietary | 21        | 20.59%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 54        | 51.43%  |
| 7.01-8.0   | 12        | 11.43%  |
| 1.01-2.0   | 10        | 9.52%   |
| 3.01-4.0   | 9         | 8.57%   |
| 0.01-0.5   | 8         | 7.62%   |
| 0.51-1.0   | 7         | 6.67%   |
| 5.01-6.0   | 2         | 1.9%    |
| 8.01-16.0  | 2         | 1.9%    |
| 2.01-3.0   | 1         | 0.95%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 14        | 11.57%  |
| BOE                     | 13        | 10.74%  |
| Chimei Innolux          | 12        | 9.92%   |
| LG Display              | 11        | 9.09%   |
| AU Optronics            | 8         | 6.61%   |
| Acer                    | 7         | 5.79%   |
| Philips                 | 6         | 4.96%   |
| Dell                    | 5         | 4.13%   |
| ASUSTek Computer        | 5         | 4.13%   |
| AOC                     | 5         | 4.13%   |
| Goldstar                | 4         | 3.31%   |
| BenQ                    | 4         | 3.31%   |
| Apple                   | 3         | 2.48%   |
| Ancor Communications    | 3         | 2.48%   |
| Sharp                   | 2         | 1.65%   |
| Chi Mei Optoelectronics | 2         | 1.65%   |
| ViewSonic               | 1         | 0.83%   |
| Vestel Elektronik       | 1         | 0.83%   |
| PANDA                   | 1         | 0.83%   |
| Packard Bell            | 1         | 0.83%   |
| MSI                     | 1         | 0.83%   |
| LGD                     | 1         | 0.83%   |
| Lenovo                  | 1         | 0.83%   |
| KTC                     | 1         | 0.83%   |
| Jean                    | 1         | 0.83%   |
| InfoVision              | 1         | 0.83%   |
| Iiyama                  | 1         | 0.83%   |
| HVR                     | 1         | 0.83%   |
| Hitachi                 | 1         | 0.83%   |
| Hewlett-Packard         | 1         | 0.83%   |
| Envision Peripherals    | 1         | 0.83%   |
| Eizo                    | 1         | 0.83%   |
| Belinea                 | 1         | 0.83%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 3         | 2.4%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 2         | 1.6%    |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                 | 2         | 1.6%    |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch        | 2         | 1.6%    |
| BOE LCD Monitor BOE08EE 1920x1080 309x174mm 14.0-inch                   | 2         | 1.6%    |
| BOE LCD Monitor BOE08CF 1920x1080 344x194mm 15.5-inch                   | 2         | 1.6%    |
| BOE LCD Monitor BOE08BA 1920x1080 344x194mm 15.5-inch                   | 2         | 1.6%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                    | 2         | 1.6%    |
| ASUSTek Computer VG289 AUS28BA 3840x2160 620x340mm 27.8-inch            | 2         | 1.6%    |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                    | 2         | 1.6%    |
| AOC 2200W AOC2200 1920x1080 476x268mm 21.5-inch                         | 2         | 1.6%    |
| Ancor Communications ASUS PB277 ACI27B5 2560x1440 600x340mm 27.2-inch   | 2         | 1.6%    |
| ViewSonic LCD Monitor VX2452 Series 3840x1080                           | 1         | 0.8%    |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 1         | 0.8%    |
| Sharp LQ133T1JW22 SHP1422 2560x1440 294x165mm 13.3-inch                 | 1         | 0.8%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                 | 1         | 0.8%    |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch       | 1         | 0.8%    |
| Samsung Electronics SyncMaster SAM02E3 1440x900 367x229mm 17.0-inch     | 1         | 0.8%    |
| Samsung Electronics SMB1630N SAM0630 1366x768 344x194mm 15.5-inch       | 1         | 0.8%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 0.8%    |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch       | 1         | 0.8%    |
| Samsung Electronics S24A31x SAM7114 1920x1080 527x296mm 23.8-inch       | 1         | 0.8%    |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch       | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch    | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch    | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 950x540mm 43.0-inch   | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1872x1053mm 84.6-inch | 1         | 0.8%    |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 1         | 0.8%    |
| Samsung Electronics C27F591 SAM0D37 1920x1080 598x336mm 27.0-inch       | 1         | 0.8%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch       | 1         | 0.8%    |
| Philips PHL 246V5 PHLC0C5 1920x1080 530x300mm 24.0-inch                 | 1         | 0.8%    |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 1         | 0.8%    |
| Philips PHL 220V8 PHLC218 1920x1080 477x268mm 21.5-inch                 | 1         | 0.8%    |
| Philips LCD Monitor PHLC081 1920x1080 480x270mm 21.7-inch               | 1         | 0.8%    |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                 | 1         | 0.8%    |
| Packard Bell Viseo203DX PKB0378 1600x900 432x240mm 19.5-inch            | 1         | 0.8%    |
| MSI Optix MAG27CQ MSI1462 2560x1440 597x336mm 27.0-inch                 | 1         | 0.8%    |
| LGD LCD Monitor 1920x1080                                               | 1         | 0.8%    |
| LG Display LCD Monitor LGD40A0 1366x768 310x174mm 14.0-inch             | 1         | 0.8%    |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch            | 1         | 0.8%    |
| LG Display LCD Monitor LGD0612 1920x1080 344x194mm 15.5-inch            | 1         | 0.8%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 1         | 0.8%    |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch            | 1         | 0.8%    |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch            | 1         | 0.8%    |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 0.8%    |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch            | 1         | 0.8%    |
| LG Display LCD Monitor LGD046B 1366x768 340x190mm 15.3-inch             | 1         | 0.8%    |
| LG Display LCD Monitor LGD03D3 1600x900 309x174mm 14.0-inch             | 1         | 0.8%    |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch             | 1         | 0.8%    |
| Lenovo LCD Monitor LEN4053 1680x1050 331x207mm 15.4-inch                | 1         | 0.8%    |
| KTC 24'TV KTC2400 1360x768 525x297mm 23.7-inch                          | 1         | 0.8%    |
| Jean JT198x6-7 JEN17C6 1280x1024 376x301mm 19.0-inch                    | 1         | 0.8%    |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch            | 1         | 0.8%    |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                   | 1         | 0.8%    |
| HVR HTC-VIVE HVRAA01 2160x1200                                          | 1         | 0.8%    |
| Hitachi HDMI HEC0030 4096x2160 1150x650mm 52.0-inch                     | 1         | 0.8%    |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch            | 1         | 0.8%    |
| Goldstar MP59G GSM5B35 1920x1080 480x270mm 21.7-inch                    | 1         | 0.8%    |
| Goldstar HDR WFHD GSM7715 2560x1080 798x334mm 34.1-inch                 | 1         | 0.8%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 1         | 0.8%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 57        | 48.31%  |
| 1366x768 (WXGA)    | 21        | 17.8%   |
| 3840x2160 (4K)     | 13        | 11.02%  |
| 2560x1440 (QHD)    | 8         | 6.78%   |
| 1600x900 (HD+)     | 3         | 2.54%   |
| 1440x900 (WXGA+)   | 3         | 2.54%   |
| 3440x1440          | 2         | 1.69%   |
| 1280x1024 (SXGA)   | 2         | 1.69%   |
| 3840x1080          | 1         | 0.85%   |
| 2736x1824          | 1         | 0.85%   |
| 2560x1600          | 1         | 0.85%   |
| 2560x1080          | 1         | 0.85%   |
| 2160x1200          | 1         | 0.85%   |
| 1920x1200 (WUXGA)  | 1         | 0.85%   |
| 1680x1050 (WSXGA+) | 1         | 0.85%   |
| 1024x768 (XGA)     | 1         | 0.85%   |
| Unknown            | 1         | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 33        | 27.73%  |
| 13      | 13        | 10.92%  |
| 27      | 12        | 10.08%  |
| 24      | 11        | 9.24%   |
| 23      | 10        | 8.4%    |
| 21      | 7         | 5.88%   |
| 14      | 6         | 5.04%   |
| 17      | 5         | 4.2%    |
| 84      | 4         | 3.36%   |
| Unknown | 4         | 3.36%   |
| 34      | 3         | 2.52%   |
| 31      | 3         | 2.52%   |
| 32      | 2         | 1.68%   |
| 19      | 2         | 1.68%   |
| 12      | 2         | 1.68%   |
| 20      | 1         | 0.84%   |
| 11      | 1         | 0.84%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 45        | 38.46%  |
| 501-600     | 28        | 23.93%  |
| 351-400     | 9         | 7.69%   |
| 401-500     | 8         | 6.84%   |
| 201-300     | 8         | 6.84%   |
| 601-700     | 6         | 5.13%   |
| 701-800     | 5         | 4.27%   |
| 1501-2000   | 4         | 3.42%   |
| Unknown     | 4         | 3.42%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 87        | 84.47%  |
| 16/10   | 6         | 5.83%   |
| 21/9    | 3         | 2.91%   |
| Unknown | 3         | 2.91%   |
| 5/4     | 2         | 1.94%   |
| 4/3     | 1         | 0.97%   |
| 3/2     | 1         | 0.97%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 33        | 27.73%  |
| 201-250        | 25        | 21.01%  |
| 81-90          | 14        | 11.76%  |
| 301-350        | 12        | 10.08%  |
| 351-500        | 8         | 6.72%   |
| 71-80          | 6         | 5.04%   |
| More than 1000 | 4         | 3.36%   |
| 151-200        | 4         | 3.36%   |
| 121-130        | 4         | 3.36%   |
| Unknown        | 4         | 3.36%   |
| 251-300        | 2         | 1.68%   |
| 61-70          | 1         | 0.84%   |
| 51-60          | 1         | 0.84%   |
| 131-140        | 1         | 0.84%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 40        | 35.09%  |
| 51-100        | 33        | 28.95%  |
| 101-120       | 30        | 26.32%  |
| 161-240       | 5         | 4.39%   |
| Unknown       | 4         | 3.51%   |
| More than 240 | 1         | 0.88%   |
| 1-50          | 1         | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 83        | 81.37%  |
| 2     | 15        | 14.71%  |
| 3     | 3         | 2.94%   |
| 4     | 1         | 0.98%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 63        | 42.28%  |
| Intel                                 | 45        | 30.2%   |
| Qualcomm Atheros                      | 15        | 10.07%  |
| Broadcom                              | 6         | 4.03%   |
| Broadcom Limited                      | 3         | 2.01%   |
| Ralink Technology                     | 2         | 1.34%   |
| Ralink                                | 2         | 1.34%   |
| D-Link System                         | 2         | 1.34%   |
| TP-Link                               | 1         | 0.67%   |
| Sierra Wireless                       | 1         | 0.67%   |
| Qualcomm Atheros Communications       | 1         | 0.67%   |
| Microsoft                             | 1         | 0.67%   |
| Marvell Technology Group              | 1         | 0.67%   |
| Linksys                               | 1         | 0.67%   |
| Huawei Technologies                   | 1         | 0.67%   |
| Google                                | 1         | 0.67%   |
| DisplayLink                           | 1         | 0.67%   |
| Aquantia                              | 1         | 0.67%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.67%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 26.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 3.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 2.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 2.79%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.79%   |
| Intel Wireless 7265                                               | 5         | 2.79%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 2.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 2.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.23%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 1.68%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.68%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 1.68%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 1.12%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 1.12%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 1.12%   |
| Intel Wireless-AC 9260                                            | 2         | 1.12%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 1.12%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 1.12%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 1.12%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 1.12%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2         | 1.12%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 1         | 0.56%   |
| Sierra Wireless MC7700                                            | 1         | 0.56%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 1         | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.56%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.56%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.56%   |
| Ralink RT2561/RT61 802.11g PCI                                    | 1         | 0.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 1         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 1         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.56%   |
| Qualcomm Atheros AR9271 802.11n                                   | 1         | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 1         | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 1         | 0.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.56%   |
| Microsoft XBOX ACC                                                | 1         | 0.56%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 1         | 0.56%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.56%   |
| Intel Wireless 3165                                               | 1         | 0.56%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 1         | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.56%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 1         | 0.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 1         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 34        | 40.96%  |
| Realtek Semiconductor                 | 18        | 21.69%  |
| Qualcomm Atheros                      | 12        | 14.46%  |
| Broadcom                              | 5         | 6.02%   |
| Broadcom Limited                      | 3         | 3.61%   |
| Ralink Technology                     | 2         | 2.41%   |
| Ralink                                | 2         | 2.41%   |
| TP-Link                               | 1         | 1.2%    |
| Sierra Wireless                       | 1         | 1.2%    |
| Qualcomm Atheros Communications       | 1         | 1.2%    |
| Microsoft                             | 1         | 1.2%    |
| Marvell Technology Group              | 1         | 1.2%    |
| D-Link System                         | 1         | 1.2%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 1.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                               | Computers | Percent |
|-----------------------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                            | 5         | 6.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                          | 5         | 6.02%   |
| Intel Wireless 8265 / 8275                                                                          | 5         | 6.02%   |
| Intel Wireless 7265                                                                                 | 5         | 6.02%   |
| Intel Comet Lake PCH CNVi WiFi                                                                      | 5         | 6.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                            | 4         | 4.82%   |
| Intel Wi-Fi 6 AX200                                                                                 | 3         | 3.61%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                                          | 3         | 3.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                                     | 2         | 2.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                                            | 2         | 2.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                                     | 2         | 2.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                                    | 2         | 2.41%   |
| Intel Wireless-AC 9260                                                                              | 2         | 2.41%   |
| Intel Wi-Fi 6 AX201                                                                                 | 2         | 2.41%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                                                     | 2         | 2.41%   |
| Intel Cannon Lake PCH CNVi WiFi                                                                     | 2         | 2.41%   |
| Broadcom BCM43142 802.11b/g/n                                                                       | 2         | 2.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                                 | 2         | 2.41%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                         | 1         | 1.2%    |
| Sierra Wireless MC7700                                                                              | 1         | 1.2%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                                            | 1         | 1.2%    |
| Realtek RTL8188EE Wireless Network Adapter                                                          | 1         | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                          | 1         | 1.2%    |
| Ralink RT5370 Wireless Adapter                                                                      | 1         | 1.2%    |
| Ralink MT7601U Wireless Adapter                                                                     | 1         | 1.2%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                                           | 1         | 1.2%    |
| Ralink RT2561/RT61 802.11g PCI                                                                      | 1         | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                          | 1         | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                          | 1         | 1.2%    |
| Qualcomm Atheros AR9271 802.11n                                                                     | 1         | 1.2%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                                    | 1         | 1.2%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                                      | 1         | 1.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                      | 1         | 1.2%    |
| Microsoft XBOX ACC                                                                                  | 1         | 1.2%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                                                   | 1         | 1.2%    |
| Intel Wireless 3165                                                                                 | 1         | 1.2%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                                             | 1         | 1.2%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                                    | 1         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                                                   | 1         | 1.2%    |
| Intel Centrino Ultimate-N 6300                                                                      | 1         | 1.2%    |
| Intel Centrino Advanced-N 6235                                                                      | 1         | 1.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                        | 1         | 1.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                            | 1         | 1.2%    |
| D-Link System DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.A2) [Atheros AR9170+AR9104]         | 1         | 1.2%    |
| Broadcom BCM43228 802.11a/b/g/n                                                                     | 1         | 1.2%    |
| 802.11g Adapter [Linksys WUSB54GC v3] WUSB100 v2 RangePlus Wireless Network Adapter [Ralink RT3070] | 1         | 1.2%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 58        | 63.74%  |
| Intel                 | 22        | 24.18%  |
| Qualcomm Atheros      | 5         | 5.49%   |
| Linksys               | 1         | 1.1%    |
| Huawei Technologies   | 1         | 1.1%    |
| DisplayLink           | 1         | 1.1%    |
| D-Link System         | 1         | 1.1%    |
| Broadcom              | 1         | 1.1%    |
| Aquantia              | 1         | 1.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 49.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 7.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 5.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.21%   |
| Intel I211 Gigabit Network Connection                             | 3         | 3.16%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 3.16%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 2.11%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 2.11%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 2.11%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 1.05%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.05%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.05%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.05%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 1.05%   |
| Intel I210 Gigabit Network Connection                             | 1         | 1.05%   |
| Intel Ethernet Controller I225-V                                  | 1         | 1.05%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 1.05%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 1.05%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 1.05%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 1.05%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 1.05%   |
| Intel 82567LF-2 Gigabit Network Connection                        | 1         | 1.05%   |
| Intel 82562V-2 10/100 Network Connection                          | 1         | 1.05%   |
| Huawei E353/E3131                                                 | 1         | 1.05%   |
| DisplayLink Kensington Dock (Composite Device)                    | 1         | 1.05%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 1         | 1.05%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.05%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 1         | 1.05%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 85        | 51.52%  |
| WiFi     | 79        | 47.88%  |
| Modem    | 1         | 0.61%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 63        | 54.78%  |
| Ethernet | 52        | 45.22%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 56        | 55.45%  |
| 1     | 41        | 40.59%  |
| 4     | 2         | 1.98%   |
| 3     | 2         | 1.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 92        | 89.32%  |
| Yes  | 11        | 10.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 43.48%  |
| Realtek Semiconductor           | 10        | 14.49%  |
| IMC Networks                    | 4         | 5.8%    |
| Cambridge Silicon Radio         | 4         | 5.8%    |
| Broadcom                        | 4         | 5.8%    |
| Qualcomm Atheros Communications | 3         | 4.35%   |
| Lite-On Technology              | 3         | 4.35%   |
| Apple                           | 3         | 4.35%   |
| Realtek                         | 2         | 2.9%    |
| ASUSTek Computer                | 2         | 2.9%    |
| Ralink                          | 1         | 1.45%   |
| Marvell Semiconductor           | 1         | 1.45%   |
| HTC (High Tech Computer)        | 1         | 1.45%   |
| Foxconn / Hon Hai               | 1         | 1.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 11        | 15.94%  |
| Intel AX201 Bluetooth                                                | 9         | 13.04%  |
| Realtek Bluetooth Radio                                              | 6         | 8.7%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 4         | 5.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 4         | 5.8%    |
| Realtek  Bluetooth 4.2 Adapter                                       | 3         | 4.35%   |
| Qualcomm Atheros  Bluetooth Device                                   | 3         | 4.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 3         | 4.35%   |
| Intel AX200 Bluetooth                                                | 3         | 4.35%   |
| Realtek Bluetooth Radio                                              | 2         | 2.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 2         | 2.9%    |
| IMC Networks Bluetooth Radio                                         | 2         | 2.9%    |
| IMC Networks Bluetooth Device                                        | 2         | 2.9%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 2         | 2.9%    |
| Apple Bluetooth USB Host Controller                                  | 2         | 2.9%    |
| Realtek RTL8821A Bluetooth                                           | 1         | 1.45%   |
| Ralink RT3290 Bluetooth                                              | 1         | 1.45%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 1         | 1.45%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 1         | 1.45%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 1.45%   |
| Foxconn / Hon Hai BCM20702A0                                         | 1         | 1.45%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 1         | 1.45%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 1         | 1.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1         | 1.45%   |
| ASUS Bluetooth Radio                                                 | 1         | 1.45%   |
| Apple Bluetooth Host Controller                                      | 1         | 1.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 67        | 44.08%  |
| AMD                                             | 37        | 24.34%  |
| Nvidia                                          | 25        | 16.45%  |
| C-Media Electronics                             | 6         | 3.95%   |
| Creative Labs                                   | 3         | 1.97%   |
| Realtek Semiconductor                           | 2         | 1.32%   |
| Logitech                                        | 2         | 1.32%   |
| Corsair                                         | 2         | 1.32%   |
| TC Electronic                                   | 1         | 0.66%   |
| SteelSeries ApS                                 | 1         | 0.66%   |
| Razer USA                                       | 1         | 0.66%   |
| Plantronics                                     | 1         | 0.66%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.66%   |
| Focusrite-Novation                              | 1         | 0.66%   |
| Creative Technology                             | 1         | 0.66%   |
| AudioQuest                                      | 1         | 0.66%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 12        | 6.35%   |
| AMD Starship/Matisse HD Audio Controller                                   | 9         | 4.76%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                        | 9         | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 7         | 3.7%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7         | 3.7%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 3.17%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 3.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 2.65%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 2.65%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 2.65%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 5         | 2.65%   |
| AMD Navi 10 HDMI Audio                                                     | 5         | 2.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 2.12%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 2.12%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 1.59%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.59%   |
| Intel Haswell-ULT HD Audio Controller                                      | 3         | 1.59%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.59%   |
| Intel Cannon Lake PCH cAVS                                                 | 3         | 1.59%   |
| Intel 8 Series HD Audio Controller                                         | 3         | 1.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 3         | 1.59%   |
| C-Media Electronics USB Audio Device                                       | 3         | 1.59%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 1.59%   |
| Realtek Semiconductor USB Audio                                            | 2         | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.06%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 1.06%   |
| Nvidia High Definition Audio Controller                                    | 2         | 1.06%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 1.06%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 1.06%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 1.06%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 2         | 1.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.06%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 1.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.06%   |
| Creative Labs CA0110 [Sound Blaster X-Fi Xtreme Audio]                     | 2         | 1.06%   |
| Corsair HS45 Surround USB Sound Adapter                                    | 2         | 1.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.06%   |
| TC Electronic VoiceLive Play                                               | 1         | 0.53%   |
| SteelSeries ApS Arctis Pro Wireless                                        | 1         | 0.53%   |
| Razer USA RZ19-0229 Gaming Microphone                                      | 1         | 0.53%   |
| Plantronics Blackwire 3225 Series                                          | 1         | 0.53%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.53%   |
| Nvidia GM200 High Definition Audio                                         | 1         | 0.53%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.53%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.53%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 0.53%   |
| Logitech G933 Wireless Headset Dongle                                      | 1         | 0.53%   |
| Logitech G432 Gaming Headset                                               | 1         | 0.53%   |
| Licensed by Sony Computer Entertainment America Rocksmith Guitar Adapter   | 1         | 0.53%   |
| Intel USB PnP Sound Device                                                 | 1         | 0.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 1         | 0.53%   |
| Intel Comet Lake PCH-LP cAVS                                               | 1         | 0.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 1         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 25.74%  |
| SK Hynix            | 15        | 14.85%  |
| Kingston            | 12        | 11.88%  |
| Corsair             | 12        | 11.88%  |
| Micron Technology   | 7         | 6.93%   |
| G.Skill             | 6         | 5.94%   |
| Unknown             | 4         | 3.96%   |
| Crucial             | 4         | 3.96%   |
| A-DATA Technology   | 4         | 3.96%   |
| Ramaxel Technology  | 2         | 1.98%   |
| Unknown (ABCD)      | 1         | 0.99%   |
| Transcend           | 1         | 0.99%   |
| Team                | 1         | 0.99%   |
| Smart Brazil        | 1         | 0.99%   |
| Silicon Power       | 1         | 0.99%   |
| Patriot             | 1         | 0.99%   |
| Nanya Technology    | 1         | 0.99%   |
| ASint Technology    | 1         | 0.99%   |
| AMD                 | 1         | 0.99%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 1.94%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8192MB Row Of Chips DDR4 3200MT/s  | 2         | 1.94%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 1.94%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 1600MT/s              | 2         | 1.94%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 1.94%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.94%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 1.94%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.94%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.94%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3533MT/s          | 2         | 1.94%   |
| Crucial RAM BLS16G4D30AESB.M16FE 16GB DIMM DDR4 3200MT/s         | 2         | 1.94%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1.94%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.97%   |
| Unknown RAM Module 4GB SODIMM DDR3 1066MT/s                      | 1         | 0.97%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.97%   |
| Unknown RAM Module 2048MB DIMM 1328MT/s                          | 1         | 0.97%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.97%   |
| Transcend RAM JM2666HLB-16G 16GB DIMM DDR4 2667MT/s              | 1         | 0.97%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 1         | 0.97%   |
| Smart Brazil RAM SMS4WEC8C1K0446FCG 8192MB SODIMM DDR4 2933MT/s  | 1         | 0.97%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK Hynix RAM HMT325S6BFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.97%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.97%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.97%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.97%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.97%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.97%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 1         | 0.97%   |
| SK Hynix RAM HMA41GU6AFR8N-TF 8192MB DIMM DDR4 2465MT/s          | 1         | 0.97%   |
| SK Hynix RAM HCNNNBKMBLHR-NEE 1GB Row Of Chips LPDDR4 4267MT/s   | 1         | 0.97%   |
| Silicon Power RAM SP008GLSTU160N02 8GB SODIMM DDR3 1600MT/s      | 1         | 0.97%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 0.97%   |
| Samsung RAM M471B5273DM0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.97%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 0.97%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 0.97%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 0.97%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 0.97%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s        | 1         | 0.97%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 0.97%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 0.97%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 0.97%   |
| Samsung RAM M378B5173EB0-YK0 4096MB DIMM DDR3 1600MT/s           | 1         | 0.97%   |
| Samsung RAM M3 78T2863RZS-CF7 1GB DIMM DDR2 800MT/s              | 1         | 0.97%   |
| Samsung RAM K4E6E304EE-EGCE 4096MB 1600MT/s                      | 1         | 0.97%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s          | 1         | 0.97%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s          | 1         | 0.97%   |
| Patriot RAM 3000 C16 Series 8GB DIMM DDR4 3200MT/s               | 1         | 0.97%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 1         | 0.97%   |
| Micron RAM Module 4GB SODIMM DDR4 2400MT/s                       | 1         | 0.97%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s         | 1         | 0.97%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 1         | 0.97%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s            | 1         | 0.97%   |
| Micron RAM 16KTF51264HZ-1G6M1 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.97%   |
| Micron RAM 16ATF2G64HZ-2G6J1 16GB SODIMM DDR4 2667MT/s           | 1         | 0.97%   |
| Micron RAM 16ATF2G64HZ-2G3H1 16384MB SODIMM DDR4 2400MT/s        | 1         | 0.97%   |
| Kingston RAM XJ69DF-MIE 8GB DIMM DDR4 2933MT/s                   | 1         | 0.97%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s            | 1         | 0.97%   |
| Kingston RAM KHX2666C15S4/16G 16384MB SODIMM DDR4 2667MT/s       | 1         | 0.97%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s              | 1         | 0.97%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 49        | 56.32%  |
| DDR3    | 27        | 31.03%  |
| SDRAM   | 3         | 3.45%   |
| LPDDR4  | 3         | 3.45%   |
| LPDDR3  | 2         | 2.3%    |
| Unknown | 2         | 2.3%    |
| DDR2    | 1         | 1.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 44        | 50.57%  |
| DIMM         | 34        | 39.08%  |
| Row Of Chips | 8         | 9.2%    |
| Unknown      | 1         | 1.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 35        | 38.89%  |
| 8192  | 30        | 33.33%  |
| 16384 | 13        | 14.44%  |
| 2048  | 7         | 7.78%   |
| 32768 | 3         | 3.33%   |
| 1024  | 2         | 2.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 23        | 24.47%  |
| 3200    | 19        | 20.21%  |
| 2667    | 11        | 11.7%   |
| 2400    | 8         | 8.51%   |
| 1333    | 5         | 5.32%   |
| 2133    | 4         | 4.26%   |
| 3600    | 3         | 3.19%   |
| 2933    | 3         | 3.19%   |
| 4199    | 2         | 2.13%   |
| 3533    | 2         | 2.13%   |
| 3266    | 2         | 2.13%   |
| 4267    | 1         | 1.06%   |
| 4133    | 1         | 1.06%   |
| 3466    | 1         | 1.06%   |
| 3400    | 1         | 1.06%   |
| 2481    | 1         | 1.06%   |
| 2465    | 1         | 1.06%   |
| 1400    | 1         | 1.06%   |
| 1334    | 1         | 1.06%   |
| 1328    | 1         | 1.06%   |
| 1066    | 1         | 1.06%   |
| 800     | 1         | 1.06%   |
| Unknown | 1         | 1.06%   |

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
| Chicony Electronics                    | 9         | 14.52%  |
| Realtek Semiconductor                  | 7         | 11.29%  |
| Quanta                                 | 6         | 9.68%   |
| Acer                                   | 6         | 9.68%   |
| Syntek                                 | 4         | 6.45%   |
| Suyin                                  | 4         | 6.45%   |
| Logitech                               | 4         | 6.45%   |
| IMC Networks                           | 4         | 6.45%   |
| Alcor Micro                            | 3         | 4.84%   |
| Sunplus Innovation Technology          | 2         | 3.23%   |
| Silicon Motion                         | 2         | 3.23%   |
| Microdia                               | 2         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 3.23%   |
| Microsoft                              | 1         | 1.61%   |
| Luxvisions Innotech Limited            | 1         | 1.61%   |
| Lite-On Technology                     | 1         | 1.61%   |
| LG Electronics                         | 1         | 1.61%   |
| Lenovo                                 | 1         | 1.61%   |
| KYE Systems (Mouse Systems)            | 1         | 1.61%   |
| Creative Technology                    | 1         | 1.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                   | 4         | 6.45%   |
| IMC Networks Integrated Camera                                 | 3         | 4.84%   |
| Chicony Integrated Camera                                      | 3         | 4.84%   |
| Chicony HD WebCam                                              | 3         | 4.84%   |
| Syntek Integrated Camera                                       | 2         | 3.23%   |
| Syntek EasyCamera                                              | 2         | 3.23%   |
| Silicon Motion 300k Pixel Camera                               | 2         | 3.23%   |
| Quanta HP Webcam                                               | 2         | 3.23%   |
| Chicony Integrated Camera (1280x720@30)                        | 2         | 3.23%   |
| Acer Integrated Camera                                         | 2         | 3.23%   |
| Suyin USB Webcam                                               | 1         | 1.61%   |
| Suyin NEC HD WebCam                                            | 1         | 1.61%   |
| Suyin HP Webcam                                                | 1         | 1.61%   |
| Suyin 1.3M HD WebCam                                           | 1         | 1.61%   |
| Sunplus HD WebCam                                              | 1         | 1.61%   |
| Sunplus Aukey-PC-LM1E Camera                                   | 1         | 1.61%   |
| Realtek USB2.0 HD UVC WebCam                                   | 1         | 1.61%   |
| Realtek Integrated Webcam                                      | 1         | 1.61%   |
| Realtek HD WebCam                                              | 1         | 1.61%   |
| Quanta VGA WebCam                                              | 1         | 1.61%   |
| Quanta USB2.0 VGA UVC WebCam                                   | 1         | 1.61%   |
| Quanta HP TrueVision HD Camera                                 | 1         | 1.61%   |
| Quanta HD User Facing                                          | 1         | 1.61%   |
| Microsoft LifeCam Cinema                                       | 1         | 1.61%   |
| Microdia Integrated_Webcam_HD                                  | 1         | 1.61%   |
| Microdia Integrated Webcam                                     | 1         | 1.61%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 1         | 1.61%   |
| Logitech Webcam C930e                                          | 1         | 1.61%   |
| Logitech Webcam C310                                           | 1         | 1.61%   |
| Logitech Webcam C270                                           | 1         | 1.61%   |
| Logitech HD Webcam C910                                        | 1         | 1.61%   |
| Lite-On HP HD Camera                                           | 1         | 1.61%   |
| LG LM-X420xxx/G2/G3 Android Phone (MTP/download mode)          | 1         | 1.61%   |
| Lenovo UVC Camera                                              | 1         | 1.61%   |
| KYE Systems (Mouse Systems) Genius FaceCam 320                 | 1         | 1.61%   |
| IMC Networks Integrated Webcam                                 | 1         | 1.61%   |
| Creative Live! Cam Sync HD [VF0770]                            | 1         | 1.61%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 1         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 1         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 1         | 1.61%   |
| Alcor Micro USB 2.0 Camera                                     | 1         | 1.61%   |
| Alcor Micro Lenovo EasyCamera                                  | 1         | 1.61%   |
| Alcor Micro Asus Integrated Webcam                             | 1         | 1.61%   |
| Acer Lenovo Integrated Webcam                                  | 1         | 1.61%   |
| Acer Integrated 5M Camera                                      | 1         | 1.61%   |
| Acer BisonCam,NB Pro                                           | 1         | 1.61%   |
| Acer BisonCam, NB Pro                                          | 1         | 1.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 3         | 42.86%  |
| Shenzhen Goodix Technology | 3         | 42.86%  |
| AuthenTec                  | 1         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 42.86%  |
| Shenzhen Goodix  FingerPrint Device               | 2         | 28.57%  |
| Shenzhen Goodix Fingerprint Reader                | 1         | 14.29%  |
| AuthenTec AES2810                                 | 1         | 14.29%  |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 3         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 77        | 75.49%  |
| 1     | 21        | 20.59%  |
| 2     | 4         | 3.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 7         | 23.33%  |
| Graphics card            | 5         | 16.67%  |
| Net/wireless             | 4         | 13.33%  |
| Multimedia controller    | 4         | 13.33%  |
| Camera                   | 3         | 10%     |
| Chipcard                 | 2         | 6.67%   |
| Bluetooth                | 2         | 6.67%   |
| Storage                  | 1         | 3.33%   |
| Dvb card                 | 1         | 3.33%   |
| Communication controller | 1         | 3.33%   |

