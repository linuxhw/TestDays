Linux in Philippines - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Philippines.

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

Total: 332

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Samsung       | 3570R/370R/470R/450R/510... | [443d537d91](https://linux-hardware.org/?probe=443d537d91) | May 05, 2022 |
| Apple         | MacBookAir5,1               | [45c12c8fc4](https://linux-hardware.org/?probe=45c12c8fc4) | Apr 30, 2022 |
| Acer          | TravelMate P249-G2-MG       | [2e0bd790c6](https://linux-hardware.org/?probe=2e0bd790c6) | Apr 26, 2022 |
| Acer          | Aspire E5-551G              | [8dd5e105d1](https://linux-hardware.org/?probe=8dd5e105d1) | Apr 21, 2022 |
| Toshiba       | TECRA R940                  | [e7dc07a41c](https://linux-hardware.org/?probe=e7dc07a41c) | Apr 20, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1f3827f38e](https://linux-hardware.org/?probe=1f3827f38e) | Apr 18, 2022 |
| Unknown       | Unknown                     | [cfd3bd53a8](https://linux-hardware.org/?probe=cfd3bd53a8) | Apr 18, 2022 |
| Acer          | Nitro AN515-57              | [b824b88050](https://linux-hardware.org/?probe=b824b88050) | Apr 15, 2022 |
| Toshiba       | Satellite E45t-A            | [3698a21b91](https://linux-hardware.org/?probe=3698a21b91) | Apr 15, 2022 |
| Toshiba       | dynabook B45/A              | [f430a05b2d](https://linux-hardware.org/?probe=f430a05b2d) | Apr 09, 2022 |
| Samsung       | RC420/RC520/RC720           | [5a576e8488](https://linux-hardware.org/?probe=5a576e8488) | Apr 01, 2022 |
| Samsung       | RC420/RC520/RC720           | [83800436e5](https://linux-hardware.org/?probe=83800436e5) | Mar 31, 2022 |
| Lenovo        | G50-45 80E3                 | [8dbd85ced8](https://linux-hardware.org/?probe=8dbd85ced8) | Mar 25, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [1a9459872a](https://linux-hardware.org/?probe=1a9459872a) | Mar 13, 2022 |
| Lenovo        | ThinkPad E480 20KN002YPH    | [2f136d5bf5](https://linux-hardware.org/?probe=2f136d5bf5) | Mar 11, 2022 |
| Unknown       | Unknown                     | [23c7cd9c12](https://linux-hardware.org/?probe=23c7cd9c12) | Mar 09, 2022 |
| Lenovo        | ThinkPad E480 20KN002YPH    | [4969ce089e](https://linux-hardware.org/?probe=4969ce089e) | Mar 08, 2022 |
| Unknown       | Unknown                     | [dc2ae12852](https://linux-hardware.org/?probe=dc2ae12852) | Mar 07, 2022 |
| Unknown       | Unknown                     | [1b5e705cf1](https://linux-hardware.org/?probe=1b5e705cf1) | Mar 07, 2022 |
| Lenovo        | ThinkPad Edge 0578BBA       | [cf314fb57a](https://linux-hardware.org/?probe=cf314fb57a) | Mar 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [809dad2888](https://linux-hardware.org/?probe=809dad2888) | Mar 01, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [02ea37a7a8](https://linux-hardware.org/?probe=02ea37a7a8) | Feb 28, 2022 |
| Acer          | AOD270                      | [491fbe6832](https://linux-hardware.org/?probe=491fbe6832) | Feb 21, 2022 |
| Acer          | AOD270                      | [90f9f56240](https://linux-hardware.org/?probe=90f9f56240) | Feb 21, 2022 |
| ASUSTek       | 900                         | [8373f78d4e](https://linux-hardware.org/?probe=8373f78d4e) | Feb 19, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [1e700d65ea](https://linux-hardware.org/?probe=1e700d65ea) | Feb 17, 2022 |
| HP            | Unknown                     | [2f4edd8b04](https://linux-hardware.org/?probe=2f4edd8b04) | Feb 13, 2022 |
| HP            | Unknown                     | [1284e8c58f](https://linux-hardware.org/?probe=1284e8c58f) | Feb 13, 2022 |
| Lenovo        | ThinkPad X220 4290MN4       | [c0c3368738](https://linux-hardware.org/?probe=c0c3368738) | Feb 08, 2022 |
| Acer          | Aspire V5-471               | [9bbd70f06c](https://linux-hardware.org/?probe=9bbd70f06c) | Feb 06, 2022 |
| Lenovo        | ThinkPad E480 20KN002YPH    | [c8f0deedbc](https://linux-hardware.org/?probe=c8f0deedbc) | Feb 03, 2022 |
| Acer          | Nitro AN515-55              | [ca4c953595](https://linux-hardware.org/?probe=ca4c953595) | Jan 27, 2022 |
| Acer          | Aspire A315-42              | [e01afda31f](https://linux-hardware.org/?probe=e01afda31f) | Jan 22, 2022 |
| HP            | Notebook                    | [826345f64e](https://linux-hardware.org/?probe=826345f64e) | Jan 13, 2022 |
| HP            | Notebook                    | [889ecc5e86](https://linux-hardware.org/?probe=889ecc5e86) | Jan 13, 2022 |
| Acer          | Aspire A315-41G             | [647b2f2da2](https://linux-hardware.org/?probe=647b2f2da2) | Jan 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [d770cc3fe5](https://linux-hardware.org/?probe=d770cc3fe5) | Jan 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [0cf6f2102c](https://linux-hardware.org/?probe=0cf6f2102c) | Jan 03, 2022 |
| Dell          | Inspiron 5555               | [5f4e7a5f4b](https://linux-hardware.org/?probe=5f4e7a5f4b) | Dec 28, 2021 |
| HP            | Pavilion tx1000             | [a3639ffcd5](https://linux-hardware.org/?probe=a3639ffcd5) | Dec 21, 2021 |
| Unknown       | Unknown                     | [a1b24f9ab7](https://linux-hardware.org/?probe=a1b24f9ab7) | Dec 21, 2021 |
| Unknown       | Unknown                     | [0fb793d2a7](https://linux-hardware.org/?probe=0fb793d2a7) | Dec 21, 2021 |
| Dell          | XPS 15 9570                 | [448cdcb300](https://linux-hardware.org/?probe=448cdcb300) | Dec 17, 2021 |
| HP            | Pavilion tx1000             | [e568b07f70](https://linux-hardware.org/?probe=e568b07f70) | Dec 14, 2021 |
| Dell          | MXG061                      | [72d7e58977](https://linux-hardware.org/?probe=72d7e58977) | Nov 28, 2021 |
| Sony          | SVT13115FGS                 | [a5821de326](https://linux-hardware.org/?probe=a5821de326) | Nov 22, 2021 |
| HP            | ProBook 4730s               | [ffaa64e329](https://linux-hardware.org/?probe=ffaa64e329) | Nov 19, 2021 |
| Acer          | TravelMate P249-G2-M        | [7dbc9e305c](https://linux-hardware.org/?probe=7dbc9e305c) | Nov 11, 2021 |
| Toshiba       | NB255                       | [3c30b0d7ad](https://linux-hardware.org/?probe=3c30b0d7ad) | Nov 09, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | [bfd4d51591](https://linux-hardware.org/?probe=bfd4d51591) | Nov 09, 2021 |
| HP            | Unknown                     | [4ce778dffc](https://linux-hardware.org/?probe=4ce778dffc) | Nov 06, 2021 |
| HP            | Unknown                     | [285c5d9c85](https://linux-hardware.org/?probe=285c5d9c85) | Nov 06, 2021 |
| Acer          | Aspire E5-411               | [0155c64e23](https://linux-hardware.org/?probe=0155c64e23) | Nov 04, 2021 |
| PERSONA       | MYBOOK 14                   | [bf2929c7e3](https://linux-hardware.org/?probe=bf2929c7e3) | Nov 03, 2021 |
| Acer          | Aspire E5-411               | [63287ab4e6](https://linux-hardware.org/?probe=63287ab4e6) | Nov 02, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | [fd3aefd54a](https://linux-hardware.org/?probe=fd3aefd54a) | Oct 27, 2021 |
| Dell          | Vostro 1400                 | [ba2e7123ba](https://linux-hardware.org/?probe=ba2e7123ba) | Oct 24, 2021 |
| Jumper        | EZbook                      | [557738cd7d](https://linux-hardware.org/?probe=557738cd7d) | Oct 23, 2021 |
| HASEE Comp... | HNX4S                       | [aba8e89b9a](https://linux-hardware.org/?probe=aba8e89b9a) | Oct 17, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [ec3329e68a](https://linux-hardware.org/?probe=ec3329e68a) | Oct 17, 2021 |
| HP            | Stream Laptop 14-cb1XX      | [b8292ace4e](https://linux-hardware.org/?probe=b8292ace4e) | Oct 14, 2021 |
| HP            | Unknown                     | [c65be179d9](https://linux-hardware.org/?probe=c65be179d9) | Oct 08, 2021 |
| HP            | 14                          | [71ed61e3e0](https://linux-hardware.org/?probe=71ed61e3e0) | Oct 02, 2021 |
| HP            | 14                          | [8fc4fceaa1](https://linux-hardware.org/?probe=8fc4fceaa1) | Oct 02, 2021 |
| HP            | EliteBook 745 G2            | [d80eb2d42c](https://linux-hardware.org/?probe=d80eb2d42c) | Sep 30, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [6e927dafdd](https://linux-hardware.org/?probe=6e927dafdd) | Sep 28, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [ccccaee5bb](https://linux-hardware.org/?probe=ccccaee5bb) | Sep 28, 2021 |
| HP            | G60                         | [36ad0dc4bc](https://linux-hardware.org/?probe=36ad0dc4bc) | Sep 22, 2021 |
| HP            | Unknown                     | [b0b3846ace](https://linux-hardware.org/?probe=b0b3846ace) | Sep 17, 2021 |
| ASUSTek       | X510UQ                      | [ffeab1f23c](https://linux-hardware.org/?probe=ffeab1f23c) | Sep 16, 2021 |
| Toshiba       | Satellite P845              | [27d8557047](https://linux-hardware.org/?probe=27d8557047) | Sep 12, 2021 |
| Toshiba       | Satellite C55D-B            | [e9f2b0ceda](https://linux-hardware.org/?probe=e9f2b0ceda) | Sep 11, 2021 |
| Dell          | Latitude E7450              | [531e888c8b](https://linux-hardware.org/?probe=531e888c8b) | Sep 04, 2021 |
| Lenovo        | ThinkPad X220 42863MJ       | [68cbfb3edb](https://linux-hardware.org/?probe=68cbfb3edb) | Sep 04, 2021 |
| Cubix         | Morph                       | [ffc9d93c9b](https://linux-hardware.org/?probe=ffc9d93c9b) | Aug 30, 2021 |
| Gigabyte      | Q2006                       | [754a3fc1b5](https://linux-hardware.org/?probe=754a3fc1b5) | Aug 23, 2021 |
| Gigabyte      | Q2006                       | [a384b10b00](https://linux-hardware.org/?probe=a384b10b00) | Aug 23, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [54f7c9deec](https://linux-hardware.org/?probe=54f7c9deec) | Aug 14, 2021 |
| Acer          | Aspire V3-772G              | [58d92680bb](https://linux-hardware.org/?probe=58d92680bb) | Aug 13, 2021 |
| Apple         | MacBookAir4,1               | [cc00e74712](https://linux-hardware.org/?probe=cc00e74712) | Aug 09, 2021 |
| Toshiba       | Satellite C650              | [3b5f090e84](https://linux-hardware.org/?probe=3b5f090e84) | Aug 01, 2021 |
| HP            | EliteBook 745 G2            | [fc11e3da30](https://linux-hardware.org/?probe=fc11e3da30) | Jul 27, 2021 |
| Acer          | Aspire E3-111               | [29d6febd6e](https://linux-hardware.org/?probe=29d6febd6e) | Jul 24, 2021 |
| Acer          | Aspire E3-111               | [f9c8b1d3ff](https://linux-hardware.org/?probe=f9c8b1d3ff) | Jul 24, 2021 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [9576a81942](https://linux-hardware.org/?probe=9576a81942) | Jul 23, 2021 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [d86a6d7c9a](https://linux-hardware.org/?probe=d86a6d7c9a) | Jul 23, 2021 |
| Acer          | Aspire E5-551G              | [519515ce84](https://linux-hardware.org/?probe=519515ce84) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| HP            | EliteBook 745 G2            | [a6ed0e9a60](https://linux-hardware.org/?probe=a6ed0e9a60) | Jul 13, 2021 |
| Lenovo        | ThinkPad X220 4291LL6       | [3e8ed9be02](https://linux-hardware.org/?probe=3e8ed9be02) | Jul 02, 2021 |
| Dell          | XPS 15 9500                 | [ceedeef480](https://linux-hardware.org/?probe=ceedeef480) | Jul 01, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | [5e0e7e2b80](https://linux-hardware.org/?probe=5e0e7e2b80) | Jun 25, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [ca6df82553](https://linux-hardware.org/?probe=ca6df82553) | Jun 22, 2021 |
| Lenovo        | ThinkPad X220 4291LR8       | [69031eda12](https://linux-hardware.org/?probe=69031eda12) | Jun 18, 2021 |
| Lenovo        | ThinkPad X220 4291LR8       | [d7b3c8fc20](https://linux-hardware.org/?probe=d7b3c8fc20) | Jun 18, 2021 |
| Lenovo        | ThinkPad L530 24811K2       | [3517541065](https://linux-hardware.org/?probe=3517541065) | Jun 11, 2021 |
| Toshiba       | Satellite L515              | [72858b36e6](https://linux-hardware.org/?probe=72858b36e6) | Jun 02, 2021 |
| NEC Comput... | PC-VK25MXZCB                | [0a1b7b959f](https://linux-hardware.org/?probe=0a1b7b959f) | May 24, 2021 |
| Lenovo        | ThinkPad E15 20RES0GF00     | [8722c3498e](https://linux-hardware.org/?probe=8722c3498e) | May 14, 2021 |
| Acer          | Aspire 4750                 | [5f6a294b7d](https://linux-hardware.org/?probe=5f6a294b7d) | May 12, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [cbe08b6f59](https://linux-hardware.org/?probe=cbe08b6f59) | May 09, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [b2e6deb92e](https://linux-hardware.org/?probe=b2e6deb92e) | May 09, 2021 |
| ASUSTek       | X450MD                      | [b77e4abcd8](https://linux-hardware.org/?probe=b77e4abcd8) | May 06, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [bb346e5b0c](https://linux-hardware.org/?probe=bb346e5b0c) | Apr 26, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [ff01911cb6](https://linux-hardware.org/?probe=ff01911cb6) | Apr 22, 2021 |
| Acer          | Aspire ES1-132              | [2e91d0c330](https://linux-hardware.org/?probe=2e91d0c330) | Apr 20, 2021 |
| Lenovo        | ThinkPad T530 2394BK7       | [f8a3bc6b1d](https://linux-hardware.org/?probe=f8a3bc6b1d) | Apr 19, 2021 |
| Acer          | Nitro AN715-51              | [1cd3975ffa](https://linux-hardware.org/?probe=1cd3975ffa) | Apr 16, 2021 |
| HP            | Notebook                    | [023066c915](https://linux-hardware.org/?probe=023066c915) | Apr 08, 2021 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [b11b4274e4](https://linux-hardware.org/?probe=b11b4274e4) | Apr 08, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | [2870ee333f](https://linux-hardware.org/?probe=2870ee333f) | Apr 07, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | [43b581a270](https://linux-hardware.org/?probe=43b581a270) | Apr 07, 2021 |
| Dell          | Inspiron 15-3567            | [40b47343b7](https://linux-hardware.org/?probe=40b47343b7) | Mar 28, 2021 |
| Notebook      | NH5x_7xDCx_DDx              | [4f1b6f18bf](https://linux-hardware.org/?probe=4f1b6f18bf) | Mar 26, 2021 |
| Notebook      | NH5x_7xDCx_DDx              | [aec0de9a30](https://linux-hardware.org/?probe=aec0de9a30) | Mar 26, 2021 |
| Acer          | TravelMate B117-M           | [c205b164c5](https://linux-hardware.org/?probe=c205b164c5) | Mar 26, 2021 |
| HP            | Pavilion Laptop 15-cc0xx    | [4b98fb1e80](https://linux-hardware.org/?probe=4b98fb1e80) | Mar 13, 2021 |
| HP            | Pavilion Laptop 15-cc0xx    | [9d7081bb36](https://linux-hardware.org/?probe=9d7081bb36) | Mar 12, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [42dd14b17d](https://linux-hardware.org/?probe=42dd14b17d) | Mar 09, 2021 |
| MSI           | CX62 7QL                    | [8241c594e5](https://linux-hardware.org/?probe=8241c594e5) | Mar 07, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [d833d15864](https://linux-hardware.org/?probe=d833d15864) | Mar 05, 2021 |
| eMachines     | eM250                       | [e20e648698](https://linux-hardware.org/?probe=e20e648698) | Mar 04, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [ec866fbb40](https://linux-hardware.org/?probe=ec866fbb40) | Mar 04, 2021 |
| Lenovo        | ThinkPad T430 2349PS9       | [4f805206d4](https://linux-hardware.org/?probe=4f805206d4) | Mar 03, 2021 |
| Acer          | TravelMate B115-M           | [46b6080608](https://linux-hardware.org/?probe=46b6080608) | Mar 02, 2021 |
| HP            | EliteBook 745 G2            | [e19330f4f2](https://linux-hardware.org/?probe=e19330f4f2) | Mar 02, 2021 |
| Acer          | TravelMate B115-M           | [4567b99e4e](https://linux-hardware.org/?probe=4567b99e4e) | Mar 02, 2021 |
| Acer          | TravelMate B113             | [5ff9f9bb03](https://linux-hardware.org/?probe=5ff9f9bb03) | Feb 23, 2021 |
| Lenovo        | G450 20022                  | [a98aa9041e](https://linux-hardware.org/?probe=a98aa9041e) | Feb 17, 2021 |
| Sony          | VPCEA36FA                   | [050c395bd5](https://linux-hardware.org/?probe=050c395bd5) | Feb 16, 2021 |
| Lenovo        | ThinkPad L530 24812K6       | [d78f3099e4](https://linux-hardware.org/?probe=d78f3099e4) | Feb 14, 2021 |
| Apple         | MacBookPro5,5               | [8b736da7f7](https://linux-hardware.org/?probe=8b736da7f7) | Feb 09, 2021 |
| Acer          | TravelMate B113             | [691f3c3158](https://linux-hardware.org/?probe=691f3c3158) | Feb 04, 2021 |
| Acer          | TravelMate B113             | [7e439b847d](https://linux-hardware.org/?probe=7e439b847d) | Feb 04, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | [4c9b44d2d4](https://linux-hardware.org/?probe=4c9b44d2d4) | Jan 26, 2021 |
| Acer          | Aspire ES1-132              | [1e55ffedfe](https://linux-hardware.org/?probe=1e55ffedfe) | Jan 15, 2021 |
| Acer          | Aspire ES1-132              | [6f9868755e](https://linux-hardware.org/?probe=6f9868755e) | Jan 15, 2021 |
| Toshiba       | dynabook R73/W              | [b84a72cace](https://linux-hardware.org/?probe=b84a72cace) | Jan 02, 2021 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [459afa05c1](https://linux-hardware.org/?probe=459afa05c1) | Dec 26, 2020 |
| HP            | ZBook Create G7 Notebook... | [e40ffb436c](https://linux-hardware.org/?probe=e40ffb436c) | Dec 20, 2020 |
| HP            | ZBook Create G7 Notebook... | [b1a2ee65e0](https://linux-hardware.org/?probe=b1a2ee65e0) | Dec 20, 2020 |
| Acer          | Aspire ES1-431              | [6a99509d25](https://linux-hardware.org/?probe=6a99509d25) | Dec 16, 2020 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [e315898f10](https://linux-hardware.org/?probe=e315898f10) | Dec 16, 2020 |
| Toshiba       | dynabook R73/W              | [96710da884](https://linux-hardware.org/?probe=96710da884) | Dec 14, 2020 |
| Samsung       | RF511/RF411/RF711           | [db8ffa8342](https://linux-hardware.org/?probe=db8ffa8342) | Dec 06, 2020 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [4dd4445d4d](https://linux-hardware.org/?probe=4dd4445d4d) | Nov 29, 2020 |
| Acer          | Aspire A315-53G             | [9498233954](https://linux-hardware.org/?probe=9498233954) | Nov 26, 2020 |
| eMachines     | eM350                       | [2bafdd62aa](https://linux-hardware.org/?probe=2bafdd62aa) | Nov 23, 2020 |
| eMachines     | eM350                       | [03b9a0de29](https://linux-hardware.org/?probe=03b9a0de29) | Nov 23, 2020 |
| Apple         | MacBookPro5,5               | [d63213adad](https://linux-hardware.org/?probe=d63213adad) | Nov 22, 2020 |
| ASUSTek       | K43SD                       | [869c3395e8](https://linux-hardware.org/?probe=869c3395e8) | Nov 20, 2020 |
| ASUSTek       | K43SD                       | [3ce330e163](https://linux-hardware.org/?probe=3ce330e163) | Nov 19, 2020 |
| HP            | Unknown                     | [b525a6fdd2](https://linux-hardware.org/?probe=b525a6fdd2) | Nov 15, 2020 |
| ASUSTek       | X540NA                      | [7c1cb4cac0](https://linux-hardware.org/?probe=7c1cb4cac0) | Nov 02, 2020 |
| Lenovo        | ThinkPad X220 4290MN4       | [f305f22059](https://linux-hardware.org/?probe=f305f22059) | Oct 29, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [80d72786c1](https://linux-hardware.org/?probe=80d72786c1) | Oct 26, 2020 |
| Acer          | Aspire SW3-016              | [e110233803](https://linux-hardware.org/?probe=e110233803) | Oct 24, 2020 |
| Acer          | Aspire ES1-132              | [ecf79444ac](https://linux-hardware.org/?probe=ecf79444ac) | Oct 21, 2020 |
| HP            | EliteBook 840 G6            | [bfe2deec18](https://linux-hardware.org/?probe=bfe2deec18) | Oct 17, 2020 |
| Acer          | Aspire SW3-016              | [2f0952fbb5](https://linux-hardware.org/?probe=2f0952fbb5) | Oct 15, 2020 |
| Lenovo        | ThinkPad X260 20F5S04206    | [147c40fe70](https://linux-hardware.org/?probe=147c40fe70) | Oct 12, 2020 |
| HP            | Notebook                    | [8cbf9133f7](https://linux-hardware.org/?probe=8cbf9133f7) | Oct 11, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [9c83568b79](https://linux-hardware.org/?probe=9c83568b79) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [0053b1ef76](https://linux-hardware.org/?probe=0053b1ef76) | Oct 07, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [e63d95d346](https://linux-hardware.org/?probe=e63d95d346) | Oct 07, 2020 |
| HP            | 15                          | [c44a5eaea1](https://linux-hardware.org/?probe=c44a5eaea1) | Oct 07, 2020 |
| Lenovo        | ThinkPad X230 2325CTO       | [c1812f8ee0](https://linux-hardware.org/?probe=c1812f8ee0) | Oct 05, 2020 |
| Lenovo        | ThinkPad X230 2325CTO       | [4e98739f72](https://linux-hardware.org/?probe=4e98739f72) | Oct 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [73fd7565f6](https://linux-hardware.org/?probe=73fd7565f6) | Oct 05, 2020 |
| HP            | 15                          | [079b48e8d0](https://linux-hardware.org/?probe=079b48e8d0) | Oct 02, 2020 |
| ASUSTek       | X540NA                      | [a2cee62097](https://linux-hardware.org/?probe=a2cee62097) | Oct 02, 2020 |
| Acer          | Aspire A314-32              | [a51d2f268d](https://linux-hardware.org/?probe=a51d2f268d) | Oct 02, 2020 |
| HP            | Pavilion Laptop 15-cc0xx    | [a8678813c5](https://linux-hardware.org/?probe=a8678813c5) | Oct 01, 2020 |
| ASUSTek       | K75DE                       | [b4cb493794](https://linux-hardware.org/?probe=b4cb493794) | Sep 28, 2020 |
| ASUSTek       | TUF Gaming FA506IV_FA506... | [72f627fd0e](https://linux-hardware.org/?probe=72f627fd0e) | Sep 21, 2020 |
| Apple         | MacBookAir3,1               | [73e9128968](https://linux-hardware.org/?probe=73e9128968) | Sep 21, 2020 |
| Fujitsu       | FMVA05008                   | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| Lenovo        | V110-14IAP 80TF             | [f0ac65615d](https://linux-hardware.org/?probe=f0ac65615d) | Sep 14, 2020 |
| Lenovo        | V110-14IAP 80TF             | [5acf002102](https://linux-hardware.org/?probe=5acf002102) | Sep 14, 2020 |
| Lenovo        | V110-14IAP 80TF             | [30b8892ca3](https://linux-hardware.org/?probe=30b8892ca3) | Sep 13, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1cf35a6180](https://linux-hardware.org/?probe=1cf35a6180) | Sep 13, 2020 |
| Lenovo        | V110-14IAP 80TF             | [d2fde2a21e](https://linux-hardware.org/?probe=d2fde2a21e) | Sep 13, 2020 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | [5a3c4a23bb](https://linux-hardware.org/?probe=5a3c4a23bb) | Sep 12, 2020 |
| ASUSTek       | X441URK                     | [f883ed5e4b](https://linux-hardware.org/?probe=f883ed5e4b) | Sep 12, 2020 |
| Dell          | Latitude E4300              | [8b163ddf1e](https://linux-hardware.org/?probe=8b163ddf1e) | Sep 09, 2020 |
| Apple         | MacBookAir2,1               | [c4b26d8019](https://linux-hardware.org/?probe=c4b26d8019) | Sep 08, 2020 |
| HP            | EliteBook 840 G6            | [809af585ab](https://linux-hardware.org/?probe=809af585ab) | Sep 08, 2020 |
| Lenovo        | ThinkPad E580 20KSA00UAU    | [becbbe530b](https://linux-hardware.org/?probe=becbbe530b) | Sep 07, 2020 |
| Acer          | Aspire 4752                 | [9c779dc588](https://linux-hardware.org/?probe=9c779dc588) | Sep 04, 2020 |
| Acer          | Aspire 4752                 | [efeb5dd920](https://linux-hardware.org/?probe=efeb5dd920) | Sep 04, 2020 |
| Acer          | Aspire A315-41G             | [ec1a232ba9](https://linux-hardware.org/?probe=ec1a232ba9) | Sep 03, 2020 |
| Acer          | Aspire A315-41G             | [3cff1527be](https://linux-hardware.org/?probe=3cff1527be) | Sep 03, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [0fda90e55c](https://linux-hardware.org/?probe=0fda90e55c) | Sep 03, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [4a5f93ed76](https://linux-hardware.org/?probe=4a5f93ed76) | Sep 03, 2020 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [e11793b02c](https://linux-hardware.org/?probe=e11793b02c) | Sep 02, 2020 |
| ASUSTek       | X441URK                     | [35b06d497e](https://linux-hardware.org/?probe=35b06d497e) | Sep 02, 2020 |
| Clevo         | M7x0S                       | [100fc7862e](https://linux-hardware.org/?probe=100fc7862e) | Sep 02, 2020 |
| Clevo         | M7x0S                       | [6d9f5403eb](https://linux-hardware.org/?probe=6d9f5403eb) | Sep 02, 2020 |
| Lenovo        | IdeaPad Z460 20059          | [9568d009c0](https://linux-hardware.org/?probe=9568d009c0) | Sep 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS0SA0J    | [5e85d0fa0e](https://linux-hardware.org/?probe=5e85d0fa0e) | Aug 31, 2020 |
| Clevo         | M7x0S                       | [7efc902d33](https://linux-hardware.org/?probe=7efc902d33) | Aug 31, 2020 |
| Clevo         | M7x0S                       | [58b7846f61](https://linux-hardware.org/?probe=58b7846f61) | Aug 30, 2020 |
| Dell          | Latitude E7450              | [7b6b25e684](https://linux-hardware.org/?probe=7b6b25e684) | Aug 27, 2020 |
| Acer          | Swift SF314-41              | [290159761f](https://linux-hardware.org/?probe=290159761f) | Aug 27, 2020 |
| HP            | Pavilion g4                 | [55dec82070](https://linux-hardware.org/?probe=55dec82070) | Aug 26, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [de3f00fc50](https://linux-hardware.org/?probe=de3f00fc50) | Aug 26, 2020 |
| ASUSTek       | X540NA                      | [8747f9eb75](https://linux-hardware.org/?probe=8747f9eb75) | Aug 22, 2020 |
| ASUSTek       | X540NA                      | [b1d91b9932](https://linux-hardware.org/?probe=b1d91b9932) | Aug 21, 2020 |
| Sony          | SVF14216SGP                 | [31495e375f](https://linux-hardware.org/?probe=31495e375f) | Aug 19, 2020 |
| HP            | Pavilion dv6000 (RU700UA... | [56702de7d4](https://linux-hardware.org/?probe=56702de7d4) | Aug 15, 2020 |
| HP            | Pavilion dv6000 (RU700UA... | [d868e4a7f9](https://linux-hardware.org/?probe=d868e4a7f9) | Aug 15, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [eed0bce682](https://linux-hardware.org/?probe=eed0bce682) | Aug 14, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [532d54162a](https://linux-hardware.org/?probe=532d54162a) | Aug 14, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | [a5e0d02669](https://linux-hardware.org/?probe=a5e0d02669) | Aug 12, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | [aa6089eda7](https://linux-hardware.org/?probe=aa6089eda7) | Aug 06, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | [86ee9f7736](https://linux-hardware.org/?probe=86ee9f7736) | Aug 06, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [2ac44f315b](https://linux-hardware.org/?probe=2ac44f315b) | Aug 05, 2020 |
| MSI           | GV62 8RD                    | [0b6cd63268](https://linux-hardware.org/?probe=0b6cd63268) | Aug 04, 2020 |
| HP            | Pavilion g4                 | [4fc16d6e09](https://linux-hardware.org/?probe=4fc16d6e09) | Aug 02, 2020 |
| HP            | Pavilion g4                 | [0b9fc56cd1](https://linux-hardware.org/?probe=0b9fc56cd1) | Aug 02, 2020 |
| HP            | 15                          | [ced39cc310](https://linux-hardware.org/?probe=ced39cc310) | Jul 31, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [3fd417f684](https://linux-hardware.org/?probe=3fd417f684) | Jul 29, 2020 |
| Samsung       | RF511/RF411/RF711           | [868e245d62](https://linux-hardware.org/?probe=868e245d62) | Jul 26, 2020 |
| Acer          | Aspire ES1-521              | [64a762e6b8](https://linux-hardware.org/?probe=64a762e6b8) | Jul 26, 2020 |
| HP            | Notebook                    | [7dd7f12bb9](https://linux-hardware.org/?probe=7dd7f12bb9) | Jul 25, 2020 |
| HP            | Notebook                    | [55ab6c06c5](https://linux-hardware.org/?probe=55ab6c06c5) | Jul 25, 2020 |
| Acer          | Aspire ES1-521              | [23d8c2d2cf](https://linux-hardware.org/?probe=23d8c2d2cf) | Jul 25, 2020 |
| Samsung       | RF511/RF411/RF711           | [ca9dc81053](https://linux-hardware.org/?probe=ca9dc81053) | Jul 25, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | [d486d4bc03](https://linux-hardware.org/?probe=d486d4bc03) | Jul 24, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YD      | [f12d8d16e5](https://linux-hardware.org/?probe=f12d8d16e5) | Jul 16, 2020 |
| Acer          | Aspire ES1-132              | [d1bc3c3a8a](https://linux-hardware.org/?probe=d1bc3c3a8a) | Jul 10, 2020 |
| Acer          | Aspire ES1-132              | [cb26f9925f](https://linux-hardware.org/?probe=cb26f9925f) | Jul 09, 2020 |
| ASUSTek       | X540NA                      | [2e3aac14fe](https://linux-hardware.org/?probe=2e3aac14fe) | Jul 02, 2020 |
| Acer          | Aspire V5-431               | [0287b85983](https://linux-hardware.org/?probe=0287b85983) | Jun 30, 2020 |
| Lenovo        | ThinkPad T530 2429HC3       | [fb0a45d925](https://linux-hardware.org/?probe=fb0a45d925) | Jun 27, 2020 |
| Lenovo        | ThinkPad T530 2429HC3       | [99e750162d](https://linux-hardware.org/?probe=99e750162d) | Jun 27, 2020 |
| eMachines     | eM350                       | [b699bf9fb6](https://linux-hardware.org/?probe=b699bf9fb6) | Jun 25, 2020 |
| HP            | Pavilion Notebook           | [1107791eab](https://linux-hardware.org/?probe=1107791eab) | Jun 22, 2020 |
| Acer          | Aspire ES1-132              | [7c1783588a](https://linux-hardware.org/?probe=7c1783588a) | Jun 12, 2020 |
| Acer          | Aspire ES1-132              | [cbbefff0a6](https://linux-hardware.org/?probe=cbbefff0a6) | Jun 12, 2020 |
| HP            | 15                          | [a4b90e7ad1](https://linux-hardware.org/?probe=a4b90e7ad1) | Jun 05, 2020 |
| ASUSTek       | X540UP                      | [2ec9f9c770](https://linux-hardware.org/?probe=2ec9f9c770) | Jun 05, 2020 |
| Dell          | Latitude 7490               | [b7b69c9cbf](https://linux-hardware.org/?probe=b7b69c9cbf) | Jun 05, 2020 |
| MSI           | MS-N014                     | [e9fd398a70](https://linux-hardware.org/?probe=e9fd398a70) | Jun 04, 2020 |
| Google        | Caroline                    | [4e305a0551](https://linux-hardware.org/?probe=4e305a0551) | May 31, 2020 |
| Samsung       | N150P/N210P/N220P           | [2a2f1b6680](https://linux-hardware.org/?probe=2a2f1b6680) | May 27, 2020 |
| ASUSTek       | N45SF                       | [a73c8a7057](https://linux-hardware.org/?probe=a73c8a7057) | May 24, 2020 |
| Acer          | Aspire A315-51              | [8d5860b41f](https://linux-hardware.org/?probe=8d5860b41f) | May 23, 2020 |
| Acer          | Aspire A315-51              | [931084ae9c](https://linux-hardware.org/?probe=931084ae9c) | May 23, 2020 |
| ASUSTek       | N45SF                       | [e35a078b83](https://linux-hardware.org/?probe=e35a078b83) | May 23, 2020 |
| HP            | EliteBook 745 G3            | [ebd5778f8c](https://linux-hardware.org/?probe=ebd5778f8c) | May 22, 2020 |
| Lenovo        | ThinkPad X280 20KES69A00    | [c1fc46e405](https://linux-hardware.org/?probe=c1fc46e405) | May 21, 2020 |
| Acer          | Aspire ES1-431              | [58ad8d0b01](https://linux-hardware.org/?probe=58ad8d0b01) | May 18, 2020 |
| Samsung       | RF511/RF411/RF711           | [9e80b645d9](https://linux-hardware.org/?probe=9e80b645d9) | May 17, 2020 |
| Toshiba       | Satellite Pro U400          | [7114a6459c](https://linux-hardware.org/?probe=7114a6459c) | May 17, 2020 |
| Acer          | Aspire ES1-431              | [32fb20af11](https://linux-hardware.org/?probe=32fb20af11) | May 16, 2020 |
| Lenovo        | IdeaPad S540-15IML 81NG     | [89e361466e](https://linux-hardware.org/?probe=89e361466e) | May 14, 2020 |
| HP            | Notebook                    | [142457c9ea](https://linux-hardware.org/?probe=142457c9ea) | May 12, 2020 |
| Acer          | Aspire M5-481PT             | [772cc038ae](https://linux-hardware.org/?probe=772cc038ae) | May 09, 2020 |
| Acer          | Aspire M5-481PT             | [332e871ec3](https://linux-hardware.org/?probe=332e871ec3) | May 09, 2020 |
| Samsung       | RF511/RF411/RF711           | [cd1d6eaf32](https://linux-hardware.org/?probe=cd1d6eaf32) | May 06, 2020 |
| Acer          | Aspire ES1-431              | [429d4a7720](https://linux-hardware.org/?probe=429d4a7720) | May 03, 2020 |
| Samsung       | RF511/RF411/RF711           | [028f510367](https://linux-hardware.org/?probe=028f510367) | May 03, 2020 |
| HP            | EliteBook 745 G2            | [84dada1bd0](https://linux-hardware.org/?probe=84dada1bd0) | May 03, 2020 |
| HP            | EliteBook 745 G2            | [60ee09d8aa](https://linux-hardware.org/?probe=60ee09d8aa) | May 02, 2020 |
| Lenovo        | ThinkPad T460s 20F9004FU... | [8eacfd828e](https://linux-hardware.org/?probe=8eacfd828e) | Apr 21, 2020 |
| Clevo         | M7x0S                       | [7ba28306d0](https://linux-hardware.org/?probe=7ba28306d0) | Apr 16, 2020 |
| Clevo         | M7x0S                       | [23aa6b7beb](https://linux-hardware.org/?probe=23aa6b7beb) | Apr 16, 2020 |
| Dell          | Inspiron 3442               | [4d48cc531a](https://linux-hardware.org/?probe=4d48cc531a) | Apr 13, 2020 |
| Dell          | Inspiron 3442               | [ad2f026926](https://linux-hardware.org/?probe=ad2f026926) | Apr 13, 2020 |
| Dell          | Inspiron 3442               | [07a7a6e630](https://linux-hardware.org/?probe=07a7a6e630) | Apr 13, 2020 |
| Clevo         | E412X                       | [0cca012f20](https://linux-hardware.org/?probe=0cca012f20) | Apr 09, 2020 |
| Acer          | Aspire ES1-431              | [3bf24f9dd6](https://linux-hardware.org/?probe=3bf24f9dd6) | Apr 07, 2020 |
| HP            | EliteBook 745 G2            | [68ecbaa367](https://linux-hardware.org/?probe=68ecbaa367) | Apr 03, 2020 |
| Acer          | Aspire V3-772G              | [9e4c202def](https://linux-hardware.org/?probe=9e4c202def) | Apr 03, 2020 |
| Acer          | Aspire ES1-431              | [3959954db3](https://linux-hardware.org/?probe=3959954db3) | Apr 02, 2020 |
| NEC Comput... | PC-VY24GXZ7A                | [bc0996781f](https://linux-hardware.org/?probe=bc0996781f) | Apr 02, 2020 |
| Dell          | Latitude E6430              | [e38eb04918](https://linux-hardware.org/?probe=e38eb04918) | Mar 23, 2020 |
| ASUSTek       | N45SF                       | [17ec9504f1](https://linux-hardware.org/?probe=17ec9504f1) | Mar 22, 2020 |
| Sony          | SVP13215CDB                 | [0aac039fdc](https://linux-hardware.org/?probe=0aac039fdc) | Mar 06, 2020 |
| Dell          | Precision 3540              | [b30c51350c](https://linux-hardware.org/?probe=b30c51350c) | Mar 05, 2020 |
| ASUSTek       | X441SA                      | [e06798387f](https://linux-hardware.org/?probe=e06798387f) | Mar 05, 2020 |
| Acer          | Aspire V3-772G              | [162a9b6da7](https://linux-hardware.org/?probe=162a9b6da7) | Feb 22, 2020 |
| Acer          | Aspire V5-471G              | [85eca92a3b](https://linux-hardware.org/?probe=85eca92a3b) | Feb 22, 2020 |
| Acer          | Aspire ES1-132              | [7994c923a0](https://linux-hardware.org/?probe=7994c923a0) | Feb 21, 2020 |
| Acer          | Aspire V3-772G              | [5cce680c2e](https://linux-hardware.org/?probe=5cce680c2e) | Feb 20, 2020 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [de6eba23f1](https://linux-hardware.org/?probe=de6eba23f1) | Feb 09, 2020 |
| Lenovo        | IdeaPad Y460                | [ece975c659](https://linux-hardware.org/?probe=ece975c659) | Feb 01, 2020 |
| Lenovo        | IdeaPad Y460                | [1a614a42a8](https://linux-hardware.org/?probe=1a614a42a8) | Jan 30, 2020 |
| Lenovo        | ThinkPad T400 2768CC1       | [298e5dbad9](https://linux-hardware.org/?probe=298e5dbad9) | Jan 20, 2020 |
| Dell          | Inspiron N4030              | [f3d828d4b1](https://linux-hardware.org/?probe=f3d828d4b1) | Jan 11, 2020 |
| Dell          | Inspiron 3521               | [600afa3fd4](https://linux-hardware.org/?probe=600afa3fd4) | Jan 11, 2020 |
| Dell          | Inspiron 3521               | [57c3c5d09b](https://linux-hardware.org/?probe=57c3c5d09b) | Jan 11, 2020 |
| ASUSTek       | X540SAA                     | [1e5c712f0b](https://linux-hardware.org/?probe=1e5c712f0b) | Jan 05, 2020 |
| Acer          | Aspire A311-31              | [1db743caaf](https://linux-hardware.org/?probe=1db743caaf) | Dec 24, 2019 |
| Dell          | Inspiron 5567               | [eecdfa47b7](https://linux-hardware.org/?probe=eecdfa47b7) | Dec 15, 2019 |
| Acer          | Aspire A315-51              | [44ecc526a8](https://linux-hardware.org/?probe=44ecc526a8) | Dec 12, 2019 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [afe3135216](https://linux-hardware.org/?probe=afe3135216) | Dec 10, 2019 |
| HP            | ProBook 440 G6              | [20bcca591f](https://linux-hardware.org/?probe=20bcca591f) | Dec 03, 2019 |
| HP            | Stream Laptop 14-ax0XX      | [777d549872](https://linux-hardware.org/?probe=777d549872) | Nov 22, 2019 |
| Acer          | Aspire A315-51              | [c5d4684f24](https://linux-hardware.org/?probe=c5d4684f24) | Nov 11, 2019 |
| Acer          | AO722                       | [a54b8c9315](https://linux-hardware.org/?probe=a54b8c9315) | Nov 08, 2019 |
| Acer          | Aspire A315-51              | [ac217a032c](https://linux-hardware.org/?probe=ac217a032c) | Nov 03, 2019 |
| Toshiba       | PORTEGE R30-A               | [619b0ce294](https://linux-hardware.org/?probe=619b0ce294) | Oct 09, 2019 |
| Toshiba       | PORTEGE R30-A               | [6b566c5c2c](https://linux-hardware.org/?probe=6b566c5c2c) | Sep 28, 2019 |
| Acer          | Aspire A315-51              | [0f199af685](https://linux-hardware.org/?probe=0f199af685) | Sep 22, 2019 |
| Toshiba       | PORTEGE R30-A               | [ed9659bf53](https://linux-hardware.org/?probe=ed9659bf53) | Sep 20, 2019 |
| Toshiba       | PORTEGE R30-A               | [8d497813d1](https://linux-hardware.org/?probe=8d497813d1) | Sep 19, 2019 |
| Acer          | TravelMate P249-G2-M        | [7c06f63670](https://linux-hardware.org/?probe=7c06f63670) | Sep 18, 2019 |
| ASUSTek       | X540NA                      | [36b5c905d1](https://linux-hardware.org/?probe=36b5c905d1) | Sep 16, 2019 |
| Lenovo        | ThinkPad Edge E320 12982... | [35b92b56a8](https://linux-hardware.org/?probe=35b92b56a8) | Sep 03, 2019 |
| Acer          | Aspire A315-51              | [eaadda80df](https://linux-hardware.org/?probe=eaadda80df) | Aug 25, 2019 |
| Lenovo        | ThinkPad Edge E320 12982... | [e57d7bb95a](https://linux-hardware.org/?probe=e57d7bb95a) | Aug 14, 2019 |
| HP            | Pavilion dm4                | [42df53b120](https://linux-hardware.org/?probe=42df53b120) | Jul 28, 2019 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [7957c03703](https://linux-hardware.org/?probe=7957c03703) | Jul 28, 2019 |
| ASUSTek       | X540NA                      | [ac8f1708fb](https://linux-hardware.org/?probe=ac8f1708fb) | Jun 30, 2019 |
| Acer          | Aspire 3935                 | [2288125313](https://linux-hardware.org/?probe=2288125313) | Jun 27, 2019 |
| Acer          | Aspire 3935                 | [813e70a499](https://linux-hardware.org/?probe=813e70a499) | Jun 27, 2019 |
| Acer          | Aspire 3935                 | [fbb934cec8](https://linux-hardware.org/?probe=fbb934cec8) | Jun 27, 2019 |
| Acer          | Aspire 5516                 | [92691e9024](https://linux-hardware.org/?probe=92691e9024) | Jun 13, 2019 |
| ASUSTek       | N550JK                      | [d3769c3f4d](https://linux-hardware.org/?probe=d3769c3f4d) | Apr 16, 2019 |
| ASUSTek       | N550JK                      | [31f0b418f9](https://linux-hardware.org/?probe=31f0b418f9) | Apr 16, 2019 |
| HP            | ENVY 4                      | [97135eda99](https://linux-hardware.org/?probe=97135eda99) | Mar 31, 2019 |
| Dell          | Inspiron 5567               | [18266bd48a](https://linux-hardware.org/?probe=18266bd48a) | Jan 06, 2019 |
| ASUSTek       | X540NA                      | [d3d3b75d21](https://linux-hardware.org/?probe=d3d3b75d21) | Jan 04, 2019 |
| ASUSTek       | X540NA                      | [6f63118ade](https://linux-hardware.org/?probe=6f63118ade) | Jan 04, 2019 |
| Acer          | TravelMate B113             | [fea3b127ea](https://linux-hardware.org/?probe=fea3b127ea) | Dec 25, 2018 |
| ASUSTek       | GL553VD                     | [d43361263c](https://linux-hardware.org/?probe=d43361263c) | Dec 24, 2018 |
| ASUSTek       | X540NA                      | [03eadbe056](https://linux-hardware.org/?probe=03eadbe056) | Nov 20, 2018 |
| ASUSTek       | X540NA                      | [f06d9e94e9](https://linux-hardware.org/?probe=f06d9e94e9) | Nov 20, 2018 |
| MSI           | GT70 2PC                    | [020492bfa1](https://linux-hardware.org/?probe=020492bfa1) | Jul 04, 2017 |
| MSI           | GT70 2PC                    | [a5dafd1181](https://linux-hardware.org/?probe=a5dafd1181) | Jul 04, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 32        | 14.29%  |
| Ubuntu 18.04                 | 15        | 6.7%    |
| Pop!_OS 20.04                | 15        | 6.7%    |
| OpenMandriva 4.2             | 10        | 4.46%   |
| Zorin 15                     | 6         | 2.68%   |
| Pop!_OS 21.04                | 6         | 2.68%   |
| Arch                         | 5         | 2.23%   |
| Manjaro                      | 4         | 1.79%   |
| Linux Mint 20.2              | 4         | 1.79%   |
| KDE neon 20.04               | 4         | 1.79%   |
| Fedora 35                    | 4         | 1.79%   |
| Debian 11                    | 4         | 1.79%   |
| Ubuntu 20.10                 | 3         | 1.34%   |
| Pop!_OS 21.10                | 3         | 1.34%   |
| LMDE 4                       | 3         | 1.34%   |
| Linux Mint 20.1              | 3         | 1.34%   |
| Linux Mint 19.3              | 3         | 1.34%   |
| KDE neon 18.04               | 3         | 1.34%   |
| Fedora 33                    | 3         | 1.34%   |
| EndeavourOS Rolling          | 3         | 1.34%   |
| Zorin 16                     | 2         | 0.89%   |
| Xubuntu 20.04                | 2         | 0.89%   |
| Xubuntu 18.04                | 2         | 0.89%   |
| Ubuntu MATE 20.04            | 2         | 0.89%   |
| Ubuntu 19.10                 | 2         | 0.89%   |
| OpenMandriva 4.3             | 2         | 0.89%   |
| Manjaro 20.1                 | 2         | 0.89%   |
| Linux Mint 20.3              | 2         | 0.89%   |
| Linux Mint 20                | 2         | 0.89%   |
| Fedora 34                    | 2         | 0.89%   |
| Fedora 32                    | 2         | 0.89%   |
| Fedora 31                    | 2         | 0.89%   |
| Endless 3.9.1                | 2         | 0.89%   |
| Endless 3.8.7                | 2         | 0.89%   |
| Endless 3.8.1                | 2         | 0.89%   |
| Endless 3.7.5                | 2         | 0.89%   |
| EndeavourOS                  | 2         | 0.89%   |
| BlackPanther 16.2            | 2         | 0.89%   |
| Arch Rolling                 | 2         | 0.89%   |
| Xubuntu 19.10                | 1         | 0.45%   |
| Ubuntu MATE 18.04            | 1         | 0.45%   |
| Ubuntu Budgie 21.10          | 1         | 0.45%   |
| Ubuntu 21.10                 | 1         | 0.45%   |
| Ubuntu 18.10                 | 1         | 0.45%   |
| Ubuntu 16.04                 | 1         | 0.45%   |
| Sparky 6                     | 1         | 0.45%   |
| Slackware 14.2               | 1         | 0.45%   |
| ROSA R9                      | 1         | 0.45%   |
| Pop!_OS 22.04                | 1         | 0.45%   |
| Pop!_OS 20.10                | 1         | 0.45%   |
| Peppermint 10                | 1         | 0.45%   |
| openSUSE Tumbleweed-20201009 | 1         | 0.45%   |
| openSUSE Leap-15.2           | 1         | 0.45%   |
| openSUSE 20210302            | 1         | 0.45%   |
| MX 19                        | 1         | 0.45%   |
| Manjaro 21.2.3               | 1         | 0.45%   |
| Manjaro 21.0                 | 1         | 0.45%   |
| Manjaro 20.2.1               | 1         | 0.45%   |
| Manjaro 20.2                 | 1         | 0.45%   |
| Lubuntu 20.04                | 1         | 0.45%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 54        | 25.84%  |
| Pop!_OS       | 26        | 12.44%  |
| Linux Mint    | 17        | 8.13%   |
| Endless       | 14        | 6.7%    |
| OpenMandriva  | 12        | 5.74%   |
| Fedora        | 12        | 5.74%   |
| Zorin         | 8         | 3.83%   |
| Manjaro       | 8         | 3.83%   |
| KDE neon      | 7         | 3.35%   |
| Arch          | 7         | 3.35%   |
| Debian        | 6         | 2.87%   |
| Xubuntu       | 5         | 2.39%   |
| EndeavourOS   | 4         | 1.91%   |
| Ubuntu MATE   | 3         | 1.44%   |
| openSUSE      | 3         | 1.44%   |
| LMDE          | 3         | 1.44%   |
| Elementary    | 3         | 1.44%   |
| Kali          | 2         | 0.96%   |
| BlackPanther  | 2         | 0.96%   |
| Ubuntu Budgie | 1         | 0.48%   |
| Sparky        | 1         | 0.48%   |
| Slackware     | 1         | 0.48%   |
| ROSA          | 1         | 0.48%   |
| Peppermint    | 1         | 0.48%   |
| MX            | 1         | 0.48%   |
| Lubuntu       | 1         | 0.48%   |
| Linux Lite    | 1         | 0.48%   |
| Kubuntu       | 1         | 0.48%   |
| Gentoo        | 1         | 0.48%   |
| Clear Linux   | 1         | 0.48%   |
| ArcoLinux     | 1         | 0.48%   |
| Archcraft     | 1         | 0.48%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 18        | 7.44%   |
| 5.10.14-desktop-1omv4002 | 10        | 4.13%   |
| 5.4.0-7634-generic       | 5         | 2.07%   |
| 5.4.0-48-generic         | 5         | 2.07%   |
| 5.4.0-47-generic         | 5         | 2.07%   |
| 5.4.0-19-generic         | 4         | 1.65%   |
| 5.3.0-28-generic         | 4         | 1.65%   |
| 5.11.0-7620-generic      | 4         | 1.65%   |
| 5.8.0-14-generic         | 3         | 1.24%   |
| 5.4.0-7642-generic       | 3         | 1.24%   |
| 5.4.0-45-generic         | 3         | 1.24%   |
| 5.3.0-23-generic         | 3         | 1.24%   |
| 5.13.0-7614-generic      | 3         | 1.24%   |
| 5.13.0-28-generic        | 3         | 1.24%   |
| 5.0.0-37-generic         | 3         | 1.24%   |
| 4.18.0-25-generic        | 3         | 1.24%   |
| 5.9.16-1-MANJARO         | 2         | 0.83%   |
| 5.4.0-90-generic         | 2         | 0.83%   |
| 5.4.0-77-generic         | 2         | 0.83%   |
| 5.4.0-7625-generic       | 2         | 0.83%   |
| 5.4.0-58-generic         | 2         | 0.83%   |
| 5.4.0-54-generic         | 2         | 0.83%   |
| 5.4.0-52-generic         | 2         | 0.83%   |
| 5.4.0-39-generic         | 2         | 0.83%   |
| 5.4.0-31-generic         | 2         | 0.83%   |
| 5.3.0-42-generic         | 2         | 0.83%   |
| 5.3.0-40-generic         | 2         | 0.83%   |
| 5.16.7-desktop-1omv4003  | 2         | 0.83%   |
| 5.13.0-30-generic        | 2         | 0.83%   |
| 5.11.16-arch1-1          | 2         | 0.83%   |
| 5.11.0-7614-generic      | 2         | 0.83%   |
| 5.11.0-34-generic        | 2         | 0.83%   |
| 5.11.0-27-generic        | 2         | 0.83%   |
| 4.9.20-desktop-pae-1bP   | 2         | 0.83%   |
| 4.18.0-15-generic        | 2         | 0.83%   |
| 4.15.0-43-generic        | 2         | 0.83%   |
| 5.9.16-200.fc33.x86_64   | 1         | 0.41%   |
| 5.9.13-200.fc33.x86_64   | 1         | 0.41%   |
| 5.9.11-3-MANJARO         | 1         | 0.41%   |
| 5.9.10-200.fc33.x86_64   | 1         | 0.41%   |
| 5.8.6-1-MANJARO          | 1         | 0.41%   |
| 5.8.3-2-MANJARO          | 1         | 0.41%   |
| 5.8.14-200.fc32.x86_64   | 1         | 0.41%   |
| 5.8.14-1-default         | 1         | 0.41%   |
| 5.8.0-7642-generic       | 1         | 0.41%   |
| 5.8.0-63-generic         | 1         | 0.41%   |
| 5.8.0-59-generic         | 1         | 0.41%   |
| 5.8.0-44-generic         | 1         | 0.41%   |
| 5.8.0-43-generic         | 1         | 0.41%   |
| 5.8.0-25-generic         | 1         | 0.41%   |
| 5.8.0-20-generic         | 1         | 0.41%   |
| 5.7.1-050701-generic     | 1         | 0.41%   |
| 5.6.16-1-MANJARO         | 1         | 0.41%   |
| 5.6.10-antix.1-amd64-smp | 1         | 0.41%   |
| 5.6.0-300.fc32.x86_64    | 1         | 0.41%   |
| 5.4.96-1-lts             | 1         | 0.41%   |
| 5.4.61-1-lts             | 1         | 0.41%   |
| 5.4.60-2-MANJARO         | 1         | 0.41%   |
| 5.4.24-1-MANJARO         | 1         | 0.41%   |
| 5.4.23-1-lts             | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 67        | 29.65%  |
| 5.3.0   | 17        | 7.52%   |
| 5.11.0  | 14        | 6.19%   |
| 5.13.0  | 11        | 4.87%   |
| 5.8.0   | 10        | 4.42%   |
| 5.10.14 | 10        | 4.42%   |
| 4.15.0  | 9         | 3.98%   |
| 5.0.0   | 7         | 3.1%    |
| 4.18.0  | 6         | 2.65%   |
| 4.19.0  | 5         | 2.21%   |
| 5.10.0  | 4         | 1.77%   |
| 5.9.16  | 3         | 1.33%   |
| 4.9.20  | 3         | 1.33%   |
| 4.4.0   | 3         | 1.33%   |
| 5.8.14  | 2         | 0.88%   |
| 5.16.7  | 2         | 0.88%   |
| 5.15.10 | 2         | 0.88%   |
| 5.14.0  | 2         | 0.88%   |
| 5.11.16 | 2         | 0.88%   |
| 5.9.13  | 1         | 0.44%   |
| 5.9.11  | 1         | 0.44%   |
| 5.9.10  | 1         | 0.44%   |
| 5.8.6   | 1         | 0.44%   |
| 5.8.3   | 1         | 0.44%   |
| 5.7.1   | 1         | 0.44%   |
| 5.6.16  | 1         | 0.44%   |
| 5.6.10  | 1         | 0.44%   |
| 5.6.0   | 1         | 0.44%   |
| 5.4.96  | 1         | 0.44%   |
| 5.4.61  | 1         | 0.44%   |
| 5.4.60  | 1         | 0.44%   |
| 5.4.24  | 1         | 0.44%   |
| 5.4.23  | 1         | 0.44%   |
| 5.4.20  | 1         | 0.44%   |
| 5.4.2   | 1         | 0.44%   |
| 5.4.105 | 1         | 0.44%   |
| 5.3.18  | 1         | 0.44%   |
| 5.3.12  | 1         | 0.44%   |
| 5.2.14  | 1         | 0.44%   |
| 5.16.9  | 1         | 0.44%   |
| 5.16.2  | 1         | 0.44%   |
| 5.16.19 | 1         | 0.44%   |
| 5.16.18 | 1         | 0.44%   |
| 5.16.16 | 1         | 0.44%   |
| 5.16.15 | 1         | 0.44%   |
| 5.16.13 | 1         | 0.44%   |
| 5.16.12 | 1         | 0.44%   |
| 5.15.8  | 1         | 0.44%   |
| 5.15.7  | 1         | 0.44%   |
| 5.15.33 | 1         | 0.44%   |
| 5.15.23 | 1         | 0.44%   |
| 5.15.21 | 1         | 0.44%   |
| 5.15.19 | 1         | 0.44%   |
| 5.15.12 | 1         | 0.44%   |
| 5.15.11 | 1         | 0.44%   |
| 5.14.16 | 1         | 0.44%   |
| 5.13.8  | 1         | 0.44%   |
| 5.12.9  | 1         | 0.44%   |
| 5.12.11 | 1         | 0.44%   |
| 5.11.12 | 1         | 0.44%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 75        | 33.33%  |
| 5.3     | 19        | 8.44%   |
| 5.11    | 17        | 7.56%   |
| 5.10    | 17        | 7.56%   |
| 5.8     | 14        | 6.22%   |
| 5.13    | 12        | 5.33%   |
| 5.16    | 10        | 4.44%   |
| 5.15    | 10        | 4.44%   |
| 4.15    | 9         | 4%      |
| 5.0     | 8         | 3.56%   |
| 4.18    | 7         | 3.11%   |
| 5.9     | 5         | 2.22%   |
| 4.19    | 5         | 2.22%   |
| 5.6     | 3         | 1.33%   |
| 5.14    | 3         | 1.33%   |
| 4.9     | 3         | 1.33%   |
| 4.4     | 3         | 1.33%   |
| 5.12    | 2         | 0.89%   |
| 5.7     | 1         | 0.44%   |
| 5.2     | 1         | 0.44%   |
| 3.8     | 1         | 0.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 196       | 95.61%  |
| i686   | 8         | 3.9%    |
| armv7l | 1         | 0.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 104       | 48.83%  |
| KDE5       | 25        | 11.74%  |
| Unknown    | 21        | 9.86%   |
| XFCE       | 18        | 8.45%   |
| X-Cinnamon | 15        | 7.04%   |
| KDE        | 12        | 5.63%   |
| MATE       | 5         | 2.35%   |
| Pantheon   | 3         | 1.41%   |
| Unity      | 1         | 0.47%   |
| sway       | 1         | 0.47%   |
| river      | 1         | 0.47%   |
| Openbox    | 1         | 0.47%   |
| LXQt       | 1         | 0.47%   |
| LXDE       | 1         | 0.47%   |
| default    | 1         | 0.47%   |
| Deepin     | 1         | 0.47%   |
| Cinnamon   | 1         | 0.47%   |
| Budgie     | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 179       | 86.06%  |
| Wayland | 17        | 8.17%   |
| Unknown | 11        | 5.29%   |
| Tty     | 1         | 0.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 129       | 61.43%  |
| GDM     | 29        | 13.81%  |
| SDDM    | 24        | 11.43%  |
| LightDM | 14        | 6.67%   |
| TDM     | 6         | 2.86%   |
| GDM3    | 5         | 2.38%   |
| SLiM    | 1         | 0.48%   |
| MDM     | 1         | 0.48%   |
| LXDM    | 1         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_PH   | 89        | 42.58%  |
| en_US   | 82        | 39.23%  |
| Unknown | 23        | 11%     |
| en_GB   | 5         | 2.39%   |
| C       | 5         | 2.39%   |
| de_DE   | 3         | 1.44%   |
| zh_HK   | 1         | 0.48%   |
| en_NZ   | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 107       | 51.2%   |
| EFI  | 102       | 48.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 163       | 77.62%  |
| Overlay | 19        | 9.05%   |
| Btrfs   | 15        | 7.14%   |
| Unknown | 7         | 3.33%   |
| Ext2    | 3         | 1.43%   |
| Xfs     | 2         | 0.95%   |
| Zfs     | 1         | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 131       | 62.68%  |
| GPT     | 54        | 25.84%  |
| MBR     | 24        | 11.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 188       | 91.26%  |
| Yes       | 18        | 8.74%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 157       | 75.48%  |
| Yes       | 51        | 24.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 48        | 23.53%  |
| Acer                | 43        | 21.08%  |
| Hewlett-Packard     | 25        | 12.25%  |
| ASUSTek Computer    | 20        | 9.8%    |
| Dell                | 18        | 8.82%   |
| Toshiba             | 11        | 5.39%   |
| Apple               | 6         | 2.94%   |
| Samsung Electronics | 5         | 2.45%   |
| MSI                 | 5         | 2.45%   |
| Sony                | 4         | 1.96%   |
| Clevo               | 4         | 1.96%   |
| eMachines           | 3         | 1.47%   |
| NEC Computers       | 2         | 0.98%   |
| Unknown             | 2         | 0.98%   |
| PERSONA             | 1         | 0.49%   |
| Notebook            | 1         | 0.49%   |
| Jumper              | 1         | 0.49%   |
| HASEE Computer      | 1         | 0.49%   |
| Google              | 1         | 0.49%   |
| Gigabyte Technology | 1         | 0.49%   |
| Fujitsu             | 1         | 0.49%   |
| Cubix               | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Acer Aspire ES1-132                      | 6         | 2.94%   |
| Unknown                                  | 5         | 2.45%   |
| HP Notebook                              | 3         | 1.47%   |
| Clevo M7x0S                              | 3         | 1.47%   |
| Lenovo V110-14IAP 80TF                   | 2         | 0.98%   |
| eMachines eM350                          | 2         | 0.98%   |
| Dell Latitude E7450                      | 2         | 0.98%   |
| Dell Inspiron 5567                       | 2         | 0.98%   |
| ASUS X540NA                              | 2         | 0.98%   |
| Apple MacBookPro5,5                      | 2         | 0.98%   |
| Acer TravelMate P249-G2-M                | 2         | 0.98%   |
| Acer TravelMate B113                     | 2         | 0.98%   |
| Acer Aspire E5-551G                      | 2         | 0.98%   |
| Acer Aspire A315-51                      | 2         | 0.98%   |
| Acer Aspire A315-41G                     | 2         | 0.98%   |
| Toshiba TECRA R940                       | 1         | 0.49%   |
| Toshiba Satellite Pro U400               | 1         | 0.49%   |
| Toshiba Satellite P845                   | 1         | 0.49%   |
| Toshiba Satellite L515                   | 1         | 0.49%   |
| Toshiba Satellite E45t-A                 | 1         | 0.49%   |
| Toshiba Satellite C650                   | 1         | 0.49%   |
| Toshiba Satellite C55D-B                 | 1         | 0.49%   |
| Toshiba PORTEGE R30-A                    | 1         | 0.49%   |
| Toshiba NB255                            | 1         | 0.49%   |
| Toshiba dynabook R73/W                   | 1         | 0.49%   |
| Toshiba dynabook B45/A                   | 1         | 0.49%   |
| Sony VPCEA36FA                           | 1         | 0.49%   |
| Sony SVT13115FGS                         | 1         | 0.49%   |
| Sony SVP13215CDB                         | 1         | 0.49%   |
| Sony SVF14216SGP                         | 1         | 0.49%   |
| Samsung RF511/RF411/RF711                | 1         | 0.49%   |
| Samsung RC420/RC520/RC720                | 1         | 0.49%   |
| Samsung N150P/N210P/N220P                | 1         | 0.49%   |
| Samsung 905S3G/906S3G/915S3G/9305SG      | 1         | 0.49%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.49%   |
| PERSONA MYBOOK 14                        | 1         | 0.49%   |
| Notebook NH5x_7xDCx_DDx                  | 1         | 0.49%   |
| NEC Computers PC-VY24GXZ7A               | 1         | 0.49%   |
| NEC Computers PC-VK25MXZCB               | 1         | 0.49%   |
| MSI MS-N014                              | 1         | 0.49%   |
| MSI GV62 8RD                             | 1         | 0.49%   |
| MSI GT70 2PC                             | 1         | 0.49%   |
| MSI CX62 7QL                             | 1         | 0.49%   |
| MSI CX61 0NC/CX61 0ND/CX61 0NF/CX61 0NE  | 1         | 0.49%   |
| Lenovo ThinkPad X280 20KES69A00          | 1         | 0.49%   |
| Lenovo ThinkPad X260 20F5S04206          | 1         | 0.49%   |
| Lenovo ThinkPad X240 20AMS0SA0J          | 1         | 0.49%   |
| Lenovo ThinkPad X230 2325CTO             | 1         | 0.49%   |
| Lenovo ThinkPad X220 4291LR8             | 1         | 0.49%   |
| Lenovo ThinkPad X220 4291LL6             | 1         | 0.49%   |
| Lenovo ThinkPad X220 4290MN4             | 1         | 0.49%   |
| Lenovo ThinkPad X220 42863MJ             | 1         | 0.49%   |
| Lenovo ThinkPad X1 Carbon 7th 20R10015US | 1         | 0.49%   |
| Lenovo ThinkPad T530 2429HC3             | 1         | 0.49%   |
| Lenovo ThinkPad T530 2394BK7             | 1         | 0.49%   |
| Lenovo ThinkPad T460s 20F9004FUS         | 1         | 0.49%   |
| Lenovo ThinkPad T430 2349PS9             | 1         | 0.49%   |
| Lenovo ThinkPad T400 2768CC1             | 1         | 0.49%   |
| Lenovo ThinkPad L530 24812K6             | 1         | 0.49%   |
| Lenovo ThinkPad L530 24811K2             | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Acer Aspire                | 30        | 14.71%  |
| Lenovo ThinkPad            | 23        | 11.27%  |
| Lenovo IdeaPad             | 17        | 8.33%   |
| HP Pavilion                | 7         | 3.43%   |
| Dell Inspiron              | 7         | 3.43%   |
| Acer TravelMate            | 7         | 3.43%   |
| Toshiba Satellite          | 6         | 2.94%   |
| Dell Latitude              | 5         | 2.45%   |
| Unknown                    | 5         | 2.45%   |
| Lenovo Legion              | 3         | 1.47%   |
| HP Notebook                | 3         | 1.47%   |
| HP EliteBook               | 3         | 1.47%   |
| Clevo M7x0S                | 3         | 1.47%   |
| Acer Nitro                 | 3         | 1.47%   |
| Toshiba dynabook           | 2         | 0.98%   |
| Lenovo V110-14IAP          | 2         | 0.98%   |
| HP Stream                  | 2         | 0.98%   |
| HP ProBook                 | 2         | 0.98%   |
| eMachines eM350            | 2         | 0.98%   |
| Dell XPS                   | 2         | 0.98%   |
| ASUS X540NA                | 2         | 0.98%   |
| ASUS VivoBook              | 2         | 0.98%   |
| ASUS TUF                   | 2         | 0.98%   |
| ASUS ROG                   | 2         | 0.98%   |
| Apple MacBookPro5          | 2         | 0.98%   |
| Toshiba TECRA              | 1         | 0.49%   |
| Toshiba PORTEGE            | 1         | 0.49%   |
| Toshiba NB255              | 1         | 0.49%   |
| Sony VPCEA36FA             | 1         | 0.49%   |
| Sony SVT13115FGS           | 1         | 0.49%   |
| Sony SVP13215CDB           | 1         | 0.49%   |
| Sony SVF14216SGP           | 1         | 0.49%   |
| Samsung RF511              | 1         | 0.49%   |
| Samsung RC420              | 1         | 0.49%   |
| Samsung N150P              | 1         | 0.49%   |
| Samsung 905S3G             | 1         | 0.49%   |
| Samsung 3570R              | 1         | 0.49%   |
| PERSONA MYBOOK             | 1         | 0.49%   |
| Notebook NH5x              | 1         | 0.49%   |
| NEC Computers PC-VY24GXZ7A | 1         | 0.49%   |
| NEC Computers PC-VK25MXZCB | 1         | 0.49%   |
| MSI MS-N014                | 1         | 0.49%   |
| MSI GV62                   | 1         | 0.49%   |
| MSI GT70                   | 1         | 0.49%   |
| MSI CX62                   | 1         | 0.49%   |
| MSI CX61                   | 1         | 0.49%   |
| Lenovo IdeaPadFlex         | 1         | 0.49%   |
| Lenovo G50-45              | 1         | 0.49%   |
| Lenovo G450                | 1         | 0.49%   |
| Jumper EZbook              | 1         | 0.49%   |
| HP ZBook                   | 1         | 0.49%   |
| HP G60                     | 1         | 0.49%   |
| HP ENVY                    | 1         | 0.49%   |
| HP 15                      | 1         | 0.49%   |
| HP 14                      | 1         | 0.49%   |
| HASEE HNX4S                | 1         | 0.49%   |
| Google Caroline            | 1         | 0.49%   |
| Gigabyte Q2006             | 1         | 0.49%   |
| Fujitsu FMVA05008          | 1         | 0.49%   |
| eMachines eM250            | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2016    | 24        | 11.76%  |
| 2012    | 24        | 11.76%  |
| 2019    | 17        | 8.33%   |
| 2018    | 17        | 8.33%   |
| 2014    | 17        | 8.33%   |
| 2010    | 17        | 8.33%   |
| 2017    | 16        | 7.84%   |
| 2011    | 15        | 7.35%   |
| 2020    | 11        | 5.39%   |
| 2015    | 11        | 5.39%   |
| 2009    | 11        | 5.39%   |
| 2013    | 10        | 4.9%    |
| 2021    | 5         | 2.45%   |
| 2008    | 5         | 2.45%   |
| 2007    | 2         | 0.98%   |
| 2006    | 1         | 0.49%   |
| Unknown | 1         | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 204       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 178       | 87.25%  |
| Enabled  | 26        | 12.75%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 203       | 99.51%  |
| Yes  | 1         | 0.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 60        | 28.85%  |
| 4.01-8.0   | 45        | 21.63%  |
| 8.01-16.0  | 35        | 16.83%  |
| 1.01-2.0   | 34        | 16.35%  |
| 16.01-24.0 | 18        | 8.65%   |
| 2.01-3.0   | 6         | 2.88%   |
| 32.01-64.0 | 4         | 1.92%   |
| 0.51-1.0   | 4         | 1.92%   |
| 24.01-32.0 | 2         | 0.96%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 92        | 40.17%  |
| 2.01-3.0  | 67        | 29.26%  |
| 3.01-4.0  | 24        | 10.48%  |
| 0.51-1.0  | 23        | 10.04%  |
| 4.01-8.0  | 18        | 7.86%   |
| 8.01-16.0 | 3         | 1.31%   |
| 0.01-0.5  | 1         | 0.44%   |
| Unknown   | 1         | 0.44%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 163       | 77.62%  |
| 2      | 37        | 17.62%  |
| 3      | 8         | 3.81%   |
| 5      | 1         | 0.48%   |
| 4      | 1         | 0.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 123       | 59.71%  |
| Yes       | 83        | 40.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 172       | 84.31%  |
| No        | 32        | 15.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 197       | 96.57%  |
| No        | 7         | 3.43%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 72.46%  |
| No        | 57        | 27.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Philippines | 204       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Cebu City           | 24        | 10.96%  |
| Quezon City         | 23        | 10.5%   |
| Makati City         | 15        | 6.85%   |
| Manila              | 12        | 5.48%   |
| Angeles City        | 11        | 5.02%   |
| Cagayan de Oro      | 10        | 4.57%   |
| Pasig               | 9         | 4.11%   |
| Tarlac City         | 7         | 3.2%    |
| San Miguel          | 7         | 3.2%    |
| Paranaque City      | 7         | 3.2%    |
| Caloocan City       | 7         | 3.2%    |
| Mandaluyong City    | 6         | 2.74%   |
| Davao City          | 6         | 2.74%   |
| Santa Maria         | 5         | 2.28%   |
| Bacoor              | 5         | 2.28%   |
| Imus                | 4         | 1.83%   |
| Baguio City         | 4         | 1.83%   |
| Santa Rosa          | 3         | 1.37%   |
| San Jose del Monte  | 3         | 1.37%   |
| City of Muntinglupa | 3         | 1.37%   |
| Calamba             | 3         | 1.37%   |
| Naga                | 2         | 0.91%   |
| Lucena City         | 2         | 0.91%   |
| Las Pinas           | 2         | 0.91%   |
| Lahug               | 2         | 0.91%   |
| Binangonan          | 2         | 0.91%   |
| Binan               | 2         | 0.91%   |
| Bacolod City        | 2         | 0.91%   |
| Tuguegarao City     | 1         | 0.46%   |
| Tangub              | 1         | 0.46%   |
| Tagbilaran          | 1         | 0.46%   |
| Santolan            | 1         | 0.46%   |
| San Pedro           | 1         | 0.46%   |
| San Pablo City      | 1         | 0.46%   |
| San Juan            | 1         | 0.46%   |
| San Fernando City   | 1         | 0.46%   |
| Roxas City          | 1         | 0.46%   |
| Rosario             | 1         | 0.46%   |
| Quezon              | 1         | 0.46%   |
| Pateros             | 1         | 0.46%   |
| Oroquieta           | 1         | 0.46%   |
| Olongapo City       | 1         | 0.46%   |
| Marikina City       | 1         | 0.46%   |
| Maragondon          | 1         | 0.46%   |
| Manajao             | 1         | 0.46%   |
| Los Banos           | 1         | 0.46%   |
| Iligan City         | 1         | 0.46%   |
| General Trias       | 1         | 0.46%   |
| Dasmarinas          | 1         | 0.46%   |
| Dagupan             | 1         | 0.46%   |
| Cavite City         | 1         | 0.46%   |
| Cainta              | 1         | 0.46%   |
| Butuan              | 1         | 0.46%   |
| Bulacan             | 1         | 0.46%   |
| Bayambang           | 1         | 0.46%   |
| Batangas            | 1         | 0.46%   |
| Antipolo City       | 1         | 0.46%   |
| Angustia            | 1         | 0.46%   |
| Aduas Centro        | 1         | 0.46%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 47        | 52     | 18.95%  |
| Seagate                   | 37        | 56     | 14.92%  |
| Toshiba                   | 36        | 48     | 14.52%  |
| Samsung Electronics       | 18        | 20     | 7.26%   |
| Unknown                   | 15        | 18     | 6.05%   |
| Hitachi                   | 15        | 21     | 6.05%   |
| Sandisk                   | 9         | 9      | 3.63%   |
| Kingston                  | 9         | 9      | 3.63%   |
| SK Hynix                  | 7         | 13     | 2.82%   |
| HGST                      | 7         | 7      | 2.82%   |
| Intel                     | 4         | 4      | 1.61%   |
| A-DATA Technology         | 4         | 6      | 1.61%   |
| Team                      | 3         | 7      | 1.21%   |
| Ramsta                    | 3         | 4      | 1.21%   |
| Micron Technology         | 3         | 3      | 1.21%   |
| Fujitsu                   | 3         | 4      | 1.21%   |
| Apple                     | 3         | 3      | 1.21%   |
| LITEONIT                  | 2         | 3      | 0.81%   |
| HS-SSD-E100               | 2         | 2      | 0.81%   |
| China                     | 2         | 2      | 0.81%   |
| Transcend                 | 1         | 1      | 0.4%    |
| Teclast                   | 1         | 2      | 0.4%    |
| TAMMUZ                    | 1         | 1      | 0.4%    |
| SPCC                      | 1         | 2      | 0.4%    |
| Solid State Storage       | 1         | 1      | 0.4%    |
| Phison                    | 1         | 1      | 0.4%    |
| OCZ                       | 1         | 1      | 0.4%    |
| Micron/Crucial Technology | 1         | 1      | 0.4%    |
| Lite-On                   | 1         | 3      | 0.4%    |
| Lenovo                    | 1         | 1      | 0.4%    |
| KingSpec                  | 1         | 1      | 0.4%    |
| Kingmax                   | 1         | 1      | 0.4%    |
| JMicron                   | 1         | 4      | 0.4%    |
| JetDrive                  | 1         | 1      | 0.4%    |
| Gigabyte Technology       | 1         | 1      | 0.4%    |
| Crucial                   | 1         | 1      | 0.4%    |
| Colorful                  | 1         | 1      | 0.4%    |
| ASUS-PHISON               | 1         | 2      | 0.4%    |
| 16GB SAT                  | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB             | 12        | 4.71%   |
| Seagate ST1000LM035-1RK172 1TB       | 8         | 3.14%   |
| WDC WD5000LPCX-21VHAT0 500GB         | 7         | 2.75%   |
| Toshiba MQ01ABD100 1TB               | 5         | 1.96%   |
| Seagate ST500LT012-9WS142 500GB      | 4         | 1.57%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 3         | 1.18%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 3         | 1.18%   |
| Unknown MMC Card  32GB               | 3         | 1.18%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 1.18%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 1.18%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.78%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 2         | 0.78%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 2         | 0.78%   |
| WDC WD10SPZX-24Z10 1TB               | 2         | 0.78%   |
| WDC WD10JPVX-22JC3T0 1TB             | 2         | 0.78%   |
| Unknown MMC Card  7GB                | 2         | 0.78%   |
| Unknown MMC Card  64GB               | 2         | 0.78%   |
| Toshiba MQ04ABF100 1TB               | 2         | 0.78%   |
| Toshiba MK2555GSX 250GB              | 2         | 0.78%   |
| SK Hynix NVMe SSD Drive 256GB        | 2         | 0.78%   |
| Seagate ST9500325AS 500GB            | 2         | 0.78%   |
| Seagate ST500LM030-2E717D 500GB      | 2         | 0.78%   |
| Seagate ST500LM030-1RK17D 500GB      | 2         | 0.78%   |
| Seagate ST2000LM007-1R8174 2TB       | 2         | 0.78%   |
| Seagate BUP Slim 2TB                 | 2         | 0.78%   |
| SanDisk DF4032  32GB                 | 2         | 0.78%   |
| Samsung SSD 860 EVO 500GB            | 2         | 0.78%   |
| Samsung MZVLB512HBJQ-000L2 512GB     | 2         | 0.78%   |
| Ramsta SSD S800 120GB                | 2         | 0.78%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 0.78%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 0.78%   |
| Kingston SA400S37120G 120GB SSD      | 2         | 0.78%   |
| HS-SSD-E100 SSD 512G                 | 2         | 0.78%   |
| Hitachi HTS545016B9A300 160GB        | 2         | 0.78%   |
| Hitachi HTS543232A7A384 320GB        | 2         | 0.78%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.78%   |
| HGST HTS541010A9E680 1TB             | 2         | 0.78%   |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.39%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 0.39%   |
| WDC WD5000LPVX-80V0TT0 500GB         | 1         | 0.39%   |
| WDC WD5000LPVT-75G33T0 500GB         | 1         | 0.39%   |
| WDC WD5000LPVT-22G33T0 500GB         | 1         | 0.39%   |
| WDC WD5000BPVT-80HXZT3 500GB         | 1         | 0.39%   |
| WDC WD3200LPVX-16V0TT3 320GB         | 1         | 0.39%   |
| WDC WD3200LPVX-08V0TT5 320GB         | 1         | 0.39%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.39%   |
| WDC WD3200BEVT-22A23T0 320GB         | 1         | 0.39%   |
| WDC WD2500BPVT-26JJ5T0 250GB         | 1         | 0.39%   |
| WDC WD2500BEVS-22UST0 250GB          | 1         | 0.39%   |
| WDC WD1600BEVT-24A23T0 160GB         | 1         | 0.39%   |
| WDC WD1600BEVS-2 160GB               | 1         | 0.39%   |
| WDC WD10SPZX-22Z10T1 1TB             | 1         | 0.39%   |
| WDC WD10SPZX-21Z10T0 1TB             | 1         | 0.39%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.39%   |
| WDC WD10SPZX-00Z10T0 1TB             | 1         | 0.39%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.39%   |
| WDC WD10JPVX-60JC3T0 1TB             | 1         | 0.39%   |
| WDC WD10JPVX-08JC3T6 1TB             | 1         | 0.39%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB | 1         | 0.39%   |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB   | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 40        | 45     | 29.41%  |
| Seagate             | 37        | 56     | 27.21%  |
| Toshiba             | 32        | 42     | 23.53%  |
| Hitachi             | 15        | 21     | 11.03%  |
| HGST                | 7         | 7      | 5.15%   |
| Fujitsu             | 3         | 4      | 2.21%   |
| Unknown             | 1         | 1      | 0.74%   |
| Samsung Electronics | 1         | 1      | 0.74%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 14     | 18.46%  |
| Kingston            | 7         | 7      | 10.77%  |
| SanDisk             | 6         | 6      | 9.23%   |
| WDC                 | 3         | 3      | 4.62%   |
| Team                | 3         | 7      | 4.62%   |
| Ramsta              | 3         | 4      | 4.62%   |
| Micron Technology   | 3         | 3      | 4.62%   |
| Apple               | 3         | 3      | 4.62%   |
| A-DATA Technology   | 3         | 5      | 4.62%   |
| Toshiba             | 2         | 4      | 3.08%   |
| LITEONIT            | 2         | 3      | 3.08%   |
| Intel               | 2         | 2      | 3.08%   |
| HS-SSD-E100         | 2         | 2      | 3.08%   |
| China               | 2         | 2      | 3.08%   |
| Transcend           | 1         | 1      | 1.54%   |
| Teclast             | 1         | 2      | 1.54%   |
| TAMMUZ              | 1         | 1      | 1.54%   |
| SK Hynix            | 1         | 6      | 1.54%   |
| Phison              | 1         | 1      | 1.54%   |
| OCZ                 | 1         | 1      | 1.54%   |
| KingSpec            | 1         | 1      | 1.54%   |
| Kingmax             | 1         | 1      | 1.54%   |
| Gigabyte Technology | 1         | 1      | 1.54%   |
| Crucial             | 1         | 1      | 1.54%   |
| Colorful            | 1         | 1      | 1.54%   |
| ASUS-PHISON         | 1         | 2      | 1.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 130       | 177    | 54.85%  |
| SSD     | 62        | 84     | 26.16%  |
| NVMe    | 27        | 33     | 11.39%  |
| MMC     | 15        | 18     | 6.33%   |
| Unknown | 3         | 6      | 1.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 181       | 255    | 78.02%  |
| NVMe | 27        | 33     | 11.64%  |
| MMC  | 15        | 18     | 6.47%   |
| SAS  | 9         | 12     | 3.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 143       | 192    | 73.71%  |
| 0.51-1.0   | 45        | 59     | 23.2%   |
| 1.01-2.0   | 5         | 9      | 2.58%   |
| 4.01-10.0  | 1         | 1      | 0.52%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 63        | 29.86%  |
| 101-250        | 52        | 24.64%  |
| 501-1000       | 35        | 16.59%  |
| 1-20           | 18        | 8.53%   |
| 51-100         | 14        | 6.64%   |
| 1001-2000      | 13        | 6.16%   |
| 21-50          | 9         | 4.27%   |
| Unknown        | 4         | 1.9%    |
| More than 3000 | 2         | 0.95%   |
| 2001-3000      | 1         | 0.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 97        | 43.69%  |
| 21-50    | 41        | 18.47%  |
| 51-100   | 31        | 13.96%  |
| 101-250  | 28        | 12.61%  |
| 251-500  | 15        | 6.76%   |
| 501-1000 | 6         | 2.7%    |
| Unknown  | 4         | 1.8%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM048-2E7172 1TB                 | 2         | 2      | 8.7%    |
| WDC WD5000LPVT-75G33T0 500GB                   | 1         | 1      | 4.35%   |
| WDC WD5000LPVT-22G33T0 500GB                   | 1         | 1      | 4.35%   |
| WDC WD3200BEVT-22A23T0 320GB                   | 1         | 1      | 4.35%   |
| WDC WD1600BEVT-24A23T0 160GB                   | 1         | 1      | 4.35%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 4.35%   |
| Toshiba MK6465GSX 640GB                        | 1         | 1      | 4.35%   |
| Toshiba MK3259GSXP 320GB                       | 1         | 1      | 4.35%   |
| SK Hynix HFS128G3AMNB-2200A 128GB SSD          | 1         | 1      | 4.35%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 4.35%   |
| Seagate ST9120821AS 120GB                      | 1         | 1      | 4.35%   |
| Seagate ST2000LM007-1R8174 2TB                 | 1         | 2      | 4.35%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 4.35%   |
| Kingston SV300S37A120G 120GB SSD               | 1         | 1      | 4.35%   |
| Hitachi HTS723232A7A364 320GB                  | 1         | 2      | 4.35%   |
| Hitachi HTS545050B9SA00 500GB                  | 1         | 1      | 4.35%   |
| Hitachi HTS542525K9SA00 250GB                  | 1         | 1      | 4.35%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 4.35%   |
| Fujitsu MHY2120BH 120GB                        | 1         | 1      | 4.35%   |
| Colorful SL300 128GB SSD                       | 1         | 1      | 4.35%   |
| A-DATA Technology SX6000PNP 512GB              | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 5         | 6      | 21.74%  |
| WDC               | 4         | 4      | 17.39%  |
| Toshiba           | 4         | 4      | 17.39%  |
| Hitachi           | 3         | 4      | 13.04%  |
| SK Hynix          | 1         | 1      | 4.35%   |
| Micron Technology | 1         | 1      | 4.35%   |
| Kingston          | 1         | 1      | 4.35%   |
| HGST              | 1         | 1      | 4.35%   |
| Fujitsu           | 1         | 1      | 4.35%   |
| Colorful          | 1         | 1      | 4.35%   |
| A-DATA Technology | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 6      | 27.78%  |
| WDC     | 4         | 4      | 22.22%  |
| Toshiba | 4         | 4      | 22.22%  |
| Hitachi | 3         | 4      | 16.67%  |
| HGST    | 1         | 1      | 5.56%   |
| Fujitsu | 1         | 1      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 20     | 77.27%  |
| SSD  | 4         | 4      | 18.18%  |
| NVMe | 1         | 1      | 4.55%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 138       | 214    | 63.3%   |
| Works    | 58        | 78     | 26.61%  |
| Malfunc  | 21        | 25     | 9.63%   |
| Failed   | 1         | 1      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 159       | 73.61%  |
| AMD                              | 22        | 10.19%  |
| Nvidia                           | 7         | 3.24%   |
| SK Hynix                         | 6         | 2.78%   |
| Samsung Electronics              | 5         | 2.31%   |
| Silicon Integrated Systems [SiS] | 3         | 1.39%   |
| Sandisk                          | 3         | 1.39%   |
| Toshiba America Info Systems     | 2         | 0.93%   |
| Solid State Storage Technology   | 2         | 0.93%   |
| Kingston Technology Company      | 2         | 0.93%   |
| Realtek Semiconductor            | 1         | 0.46%   |
| Phison Electronics               | 1         | 0.46%   |
| Micron/Crucial Technology        | 1         | 0.46%   |
| Lite-On Technology               | 1         | 0.46%   |
| Lenovo                           | 1         | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 24        | 10.26%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 20        | 8.55%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 20        | 8.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 15        | 6.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 13        | 5.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 12        | 5.13%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 7         | 2.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 2.56%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 2.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 2.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 6         | 2.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 6         | 2.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 2.14%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 2.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 1.71%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 1.71%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 1.28%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 3         | 1.28%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 3         | 1.28%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 1.28%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.28%   |
| Solid State Storage Non-Volatile memory controller                               | 2         | 0.85%   |
| SK Hynix Gold P31 SSD                                                            | 2         | 0.85%   |
| Silicon Integrated Systems [SiS] AHCI IDE Controller (0106)                      | 2         | 0.85%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.85%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 0.85%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.85%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 0.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.85%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 1         | 0.43%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.43%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 0.43%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.43%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 1         | 0.43%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 1         | 0.43%   |
| Sandisk Non-Volatile memory controller                                           | 1         | 0.43%   |
| Realtek Realtek Non-Volatile memory controller                                   | 1         | 0.43%   |
| Phison NVMe Storage Controller                                                   | 1         | 0.43%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 1         | 0.43%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                     | 1         | 0.43%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                 | 1         | 0.43%   |
| Nvidia MCP67 IDE Controller                                                      | 1         | 0.43%   |
| Nvidia MCP67 AHCI Controller                                                     | 1         | 0.43%   |
| Nvidia MCP51 Serial ATA Controller                                               | 1         | 0.43%   |
| Nvidia MCP51 IDE                                                                 | 1         | 0.43%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 1         | 0.43%   |
| Lite-On Non-Volatile memory controller                                           | 1         | 0.43%   |
| Lenovo Non-Volatile memory controller                                            | 1         | 0.43%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.43%   |
| Kingston Company Company Non-Volatile memory controller                          | 1         | 0.43%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 1         | 0.43%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.43%   |
| Intel PROSet/Wireless WiFi Software extension                                    | 1         | 0.43%   |
| Intel Non-Volatile memory controller                                             | 1         | 0.43%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.43%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.43%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 1         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 169       | 74.78%  |
| NVMe | 27        | 11.95%  |
| IDE  | 16        | 7.08%   |
| RAID | 14        | 6.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 175       | 85.78%  |
| AMD    | 28        | 13.73%  |
| ARM    | 1         | 0.49%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 2.94%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 6         | 2.94%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 6         | 2.94%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 2.45%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 1.96%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 4         | 1.96%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 4         | 1.96%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 1.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.47%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.47%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 1.47%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 1.47%   |
| Intel Celeron CPU N3160 @ 1.60GHz             | 3         | 1.47%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 3         | 1.47%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 1.47%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 2         | 0.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.98%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz            | 2         | 0.98%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.98%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.98%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.98%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.98%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.98%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.98%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 0.98%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.98%   |
| Intel Core i3-3227U CPU @ 1.90GHz             | 2         | 0.98%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 0.98%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 2         | 0.98%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.98%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 2         | 0.98%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz          | 2         | 0.98%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.98%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.98%   |
| Intel Celeron CPU N2940 @ 1.83GHz             | 2         | 0.98%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 2         | 0.98%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 2         | 0.98%   |
| AMD Turion 64 X2 Mobile Technology TL-58      | 2         | 0.98%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 0.98%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics   | 2         | 0.98%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.49%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.49%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 1         | 0.49%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 1         | 0.49%   |
| Intel Pentium CPU T4300 @ 2.10GHz             | 1         | 0.49%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.49%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.49%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 0.49%   |
| Intel Pentium CPU B940 @ 2.00GHz              | 1         | 0.49%   |
| Intel Pentium CPU 3825U @ 1.90GHz             | 1         | 0.49%   |
| Intel Genuine CPU T2060 @ 1.60GHz             | 1         | 0.49%   |
| Intel Core m3-6Y30 CPU @ 0.90GHz              | 1         | 0.49%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.49%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.49%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.49%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 1         | 0.49%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.49%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 1         | 0.49%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 1         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 54        | 26.47%  |
| Intel Core i7           | 31        | 15.2%   |
| Intel Celeron           | 31        | 15.2%   |
| Intel Core i3           | 22        | 10.78%  |
| Intel Atom              | 11        | 5.39%   |
| Intel Core 2 Duo        | 8         | 3.92%   |
| Intel Pentium           | 6         | 2.94%   |
| AMD Ryzen 5             | 6         | 2.94%   |
| Intel Pentium Dual-Core | 4         | 1.96%   |
| AMD Ryzen 7             | 4         | 1.96%   |
| AMD A8                  | 4         | 1.96%   |
| Other                   | 3         | 1.47%   |
| AMD Turion 64 X2 Mobile | 2         | 0.98%   |
| AMD Athlon              | 2         | 0.98%   |
| AMD A10                 | 2         | 0.98%   |
| Intel Pentium Silver    | 1         | 0.49%   |
| Intel Pentium Dual      | 1         | 0.49%   |
| Intel Genuine           | 1         | 0.49%   |
| Intel Core m3           | 1         | 0.49%   |
| Intel Core 2            | 1         | 0.49%   |
| Intel Celeron M         | 1         | 0.49%   |
| AMD Ryzen 9             | 1         | 0.49%   |
| AMD Ryzen 3             | 1         | 0.49%   |
| AMD Quad-Core           | 1         | 0.49%   |
| AMD PRO A10             | 1         | 0.49%   |
| AMD FX                  | 1         | 0.49%   |
| AMD E2                  | 1         | 0.49%   |
| AMD E1                  | 1         | 0.49%   |
| AMD C-60                | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 122       | 59.8%   |
| 4      | 61        | 29.9%   |
| 1      | 9         | 4.41%   |
| 8      | 6         | 2.94%   |
| 6      | 6         | 2.94%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 204       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 134       | 65.69%  |
| 1      | 70        | 34.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 196       | 95.61%  |
| Unknown        | 6         | 2.93%   |
| 32-bit         | 3         | 1.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 18.57%  |
| 0x306a9    | 19        | 9.05%   |
| 0x206a7    | 16        | 7.62%   |
| 0x506c9    | 10        | 4.76%   |
| 0x406e3    | 9         | 4.29%   |
| 0x806ea    | 8         | 3.81%   |
| 0x1067a    | 8         | 3.81%   |
| 0x806e9    | 7         | 3.33%   |
| 0x306d4    | 7         | 3.33%   |
| 0x30678    | 7         | 3.33%   |
| 0x806ec    | 6         | 2.86%   |
| 0x406c4    | 5         | 2.38%   |
| 0x40651    | 5         | 2.38%   |
| 0x306c3    | 5         | 2.38%   |
| 0x706a1    | 4         | 1.9%    |
| 0x20655    | 4         | 1.9%    |
| 0x106ca    | 4         | 1.9%    |
| 0x10676    | 4         | 1.9%    |
| 0xa0652    | 3         | 1.43%   |
| 0x906ea    | 3         | 1.43%   |
| 0x406c3    | 3         | 1.43%   |
| 0x20652    | 3         | 1.43%   |
| 0x07030105 | 3         | 1.43%   |
| 0x06003106 | 3         | 1.43%   |
| 0x30661    | 2         | 0.95%   |
| 0x0a50000c | 2         | 0.95%   |
| 0x0700010f | 2         | 0.95%   |
| 0xa0660    | 1         | 0.48%   |
| 0x906e9    | 1         | 0.48%   |
| 0x806c1    | 1         | 0.48%   |
| 0x706a8    | 1         | 0.48%   |
| 0x6fd      | 1         | 0.48%   |
| 0x6f6      | 1         | 0.48%   |
| 0x6ec      | 1         | 0.48%   |
| 0x6d8      | 1         | 0.48%   |
| 0x106c2    | 1         | 0.48%   |
| 0x08608103 | 1         | 0.48%   |
| 0x08600106 | 1         | 0.48%   |
| 0x08600104 | 1         | 0.48%   |
| 0x08600103 | 1         | 0.48%   |
| 0x08108102 | 1         | 0.48%   |
| 0x0810100b | 1         | 0.48%   |
| 0x0600611a | 1         | 0.48%   |
| 0x06001119 | 1         | 0.48%   |
| 0x05000119 | 1         | 0.48%   |
| 0x02000057 | 1         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 33        | 16.18%  |
| IvyBridge       | 22        | 10.78%  |
| SandyBridge     | 17        | 8.33%   |
| Silvermont      | 15        | 7.35%   |
| Penryn          | 14        | 6.86%   |
| Haswell         | 12        | 5.88%   |
| Goldmont        | 12        | 5.88%   |
| Skylake         | 10        | 4.9%    |
| Westmere        | 8         | 3.92%   |
| Bonnell         | 8         | 3.92%   |
| Broadwell       | 7         | 3.43%   |
| CometLake       | 6         | 2.94%   |
| Goldmont plus   | 5         | 2.45%   |
| Puma            | 4         | 1.96%   |
| Zen+            | 3         | 1.47%   |
| Zen 2           | 3         | 1.47%   |
| Zen             | 3         | 1.47%   |
| Steamroller     | 3         | 1.47%   |
| K8 Hammer       | 3         | 1.47%   |
| Unknown         | 3         | 1.47%   |
| Zen 3           | 2         | 0.98%   |
| P6              | 2         | 0.98%   |
| Jaguar          | 2         | 0.98%   |
| Core            | 2         | 0.98%   |
| TigerLake       | 1         | 0.49%   |
| Piledriver      | 1         | 0.49%   |
| K8 & K10 hybrid | 1         | 0.49%   |
| Excavator       | 1         | 0.49%   |
| Bobcat          | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 165       | 64.96%  |
| Nvidia                           | 47        | 18.5%   |
| AMD                              | 39        | 15.35%  |
| Silicon Integrated Systems [SiS] | 3         | 1.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 8.37%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 6.46%   |
| Intel HD Graphics 500                                                                    | 12        | 4.56%   |
| Intel HD Graphics 620                                                                    | 11        | 4.18%   |
| Intel UHD Graphics 620                                                                   | 9         | 3.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 3.04%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 2.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 2.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 2.66%   |
| Intel HD Graphics 5500                                                                   | 6         | 2.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 2.28%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 1.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 1.9%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.9%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 1.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.52%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.52%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 4         | 1.52%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 3         | 1.14%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 1.14%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.14%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 1.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.14%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.14%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.14%   |
| AMD Renoir                                                                               | 3         | 1.14%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.14%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 1.14%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.76%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.76%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.76%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.76%   |
| Intel HD Graphics 630                                                                    | 2         | 0.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.76%   |
| Intel Comet Lake UHD Graphics                                                            | 2         | 0.76%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 2         | 0.76%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.76%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                                  | 2         | 0.76%   |
| AMD Kaveri [Radeon R6/R7 Graphics]                                                       | 2         | 0.76%   |
| AMD Cezanne                                                                              | 2         | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.38%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.38%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.38%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.38%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.38%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.38%   |
| Nvidia GM108M [GeForce 940M]                                                             | 1         | 0.38%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.38%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.38%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.38%   |
| Nvidia GK107M [GeForce GT 645M]                                                          | 1         | 0.38%   |
| Nvidia GK106M [GeForce GTX 760M]                                                         | 1         | 0.38%   |
| Nvidia GK104M [GeForce GTX 870M]                                                         | 1         | 0.38%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 0.38%   |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 0.38%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.38%   |
| Nvidia GF116M [GeForce GT 555M/635M]                                                     | 1         | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 118       | 57.84%  |
| Intel + Nvidia | 34        | 16.67%  |
| 1 x AMD        | 16        | 7.84%   |
| Intel + AMD    | 13        | 6.37%   |
| 1 x Nvidia     | 9         | 4.41%   |
| 2 x AMD        | 6         | 2.94%   |
| AMD + Nvidia   | 4         | 1.96%   |
| 1 x SiS        | 3         | 1.47%   |
| Other          | 1         | 0.49%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 171       | 82.61%  |
| Proprietary | 29        | 14.01%  |
| Unknown     | 7         | 3.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 147       | 70.33%  |
| 0.01-0.5   | 19        | 9.09%   |
| 1.01-2.0   | 18        | 8.61%   |
| 0.51-1.0   | 14        | 6.7%    |
| 3.01-4.0   | 8         | 3.83%   |
| 5.01-6.0   | 2         | 0.96%   |
| 7.01-8.0   | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 41        | 18.72%  |
| AU Optronics            | 37        | 16.89%  |
| BOE                     | 29        | 13.24%  |
| Samsung Electronics     | 25        | 11.42%  |
| LG Display              | 25        | 11.42%  |
| Lenovo                  | 9         | 4.11%   |
| Sharp                   | 5         | 2.28%   |
| InfoVision              | 5         | 2.28%   |
| Apple                   | 5         | 2.28%   |
| Sony                    | 3         | 1.37%   |
| Philips                 | 3         | 1.37%   |
| Goldstar                | 3         | 1.37%   |
| Acer                    | 3         | 1.37%   |
| PANDA                   | 2         | 0.91%   |
| LG Philips              | 2         | 0.91%   |
| InnoLux Display         | 2         | 0.91%   |
| Hewlett-Packard         | 2         | 0.91%   |
| ASUSTek Computer        | 2         | 0.91%   |
| AOC                     | 2         | 0.91%   |
| Ancor Communications    | 2         | 0.91%   |
| ___                     | 1         | 0.46%   |
| Unknown                 | 1         | 0.46%   |
| Toshiba                 | 1         | 0.46%   |
| RTK                     | 1         | 0.46%   |
| Panasonic               | 1         | 0.46%   |
| IPS                     | 1         | 0.46%   |
| HannStar                | 1         | 0.46%   |
| GDH                     | 1         | 0.46%   |
| Dell                    | 1         | 0.46%   |
| COS                     | 1         | 0.46%   |
| Chi Mei Optoelectronics | 1         | 0.46%   |
| BenQ                    | 1         | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 7         | 3.2%    |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 5         | 2.28%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 4         | 1.83%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 3         | 1.37%   |
| BOE LCD Monitor BOE06BD 1366x768 309x173mm 13.9-inch                  | 3         | 1.37%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 1.37%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 3         | 1.37%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 2         | 0.91%   |
| Samsung Electronics LCD Monitor SEC3549 1366x768 309x174mm 14.0-inch  | 2         | 0.91%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 2         | 0.91%   |
| LG Display LP101WSA-TLN1 LGD0295 1024x600 224x126mm 10.1-inch         | 2         | 0.91%   |
| LG Display LCD Monitor LGD0525 1366x768 344x194mm 15.5-inch           | 2         | 0.91%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch           | 2         | 0.91%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch               | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch       | 2         | 0.91%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch         | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO30D2 1024x600 223x125mm 10.1-inch         | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.91%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                  | 2         | 0.91%   |
| ___ LCDTV16 ___9000 1360x768                                          | 1         | 0.46%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.46%   |
| Toshiba LCD Monitor LCD2207 1280x800 287x180mm 13.3-inch              | 1         | 0.46%   |
| Sony TV SNYAB03 1920x1080                                             | 1         | 0.46%   |
| Sony TV SNYA301 1920x1080 1600x900mm 72.3-inch                        | 1         | 0.46%   |
| Sony NvidiaDefault SNY05FA 1366x768 290x170mm 13.2-inch               | 1         | 0.46%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 1         | 0.46%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.46%   |
| Sharp LQ123P1JX31 SHP1471 2400x1600 259x173mm 12.3-inch               | 1         | 0.46%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.46%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.46%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 1         | 0.46%   |
| Samsung Electronics S22R35x SAM103A 1920x1080 476x268mm 21.5-inch     | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4457 1440x900 303x190mm 14.1-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3842 1366x768 309x174mm 14.0-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3441 1366x768 309x174mm 14.0-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3154 1600x900 382x215mm 17.3-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4651 1366x768 344x194mm 15.5-inch  | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 700x390mm 31.5-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SAM07D0 1360x768                      | 1         | 0.46%   |
| RTK 32V3H-H6A RTK4C54 1440x900 697x392mm 31.5-inch                    | 1         | 0.46%   |
| Philips PHL 246E7 PHLC107 1920x1080 521x293mm 23.5-inch               | 1         | 0.46%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1         | 0.46%   |
| Philips 170S PHL082B 1280x1024 338x270mm 17.0-inch                    | 1         | 0.46%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 1         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 110       | 53.4%   |
| 1920x1080 (FHD)   | 57        | 27.67%  |
| 1600x900 (HD+)    | 9         | 4.37%   |
| 1280x800 (WXGA)   | 6         | 2.91%   |
| 1024x600          | 6         | 2.91%   |
| 3840x2160 (4K)    | 3         | 1.46%   |
| 1920x1200 (WUXGA) | 3         | 1.46%   |
| 1440x900 (WXGA+)  | 3         | 1.46%   |
| 1360x768          | 3         | 1.46%   |
| 1280x1024 (SXGA)  | 3         | 1.46%   |
| 2560x1440 (QHD)   | 1         | 0.49%   |
| 2400x1600         | 1         | 0.49%   |
| 1600x1200         | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 71        | 32.57%  |
| 13      | 44        | 20.18%  |
| 14      | 26        | 11.93%  |
| 11      | 17        | 7.8%    |
| 17      | 12        | 5.5%    |
| 18      | 9         | 4.13%   |
| 12      | 9         | 4.13%   |
| 23      | 8         | 3.67%   |
| 10      | 6         | 2.75%   |
| 72      | 4         | 1.83%   |
| 21      | 4         | 1.83%   |
| 27      | 3         | 1.38%   |
| 31      | 2         | 0.92%   |
| 47      | 1         | 0.46%   |
| 20      | 1         | 0.46%   |
| Unknown | 1         | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 127       | 58.8%   |
| 201-300     | 45        | 20.83%  |
| 401-500     | 14        | 6.48%   |
| 351-400     | 11        | 5.09%   |
| 501-600     | 10        | 4.63%   |
| 1501-2000   | 4         | 1.85%   |
| 601-700     | 3         | 1.39%   |
| 1001-1500   | 1         | 0.46%   |
| Unknown     | 1         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 180       | 93.26%  |
| 16/10 | 10        | 5.18%   |
| 5/4   | 2         | 1.04%   |
| 3/2   | 1         | 0.52%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 69        | 31.8%   |
| 81-90          | 58        | 26.73%  |
| 51-60          | 17        | 7.83%   |
| 71-80          | 12        | 5.53%   |
| 141-150        | 11        | 5.07%   |
| 201-250        | 10        | 4.61%   |
| 61-70          | 9         | 4.15%   |
| 121-130        | 9         | 4.15%   |
| 41-50          | 6         | 2.76%   |
| More than 1000 | 4         | 1.84%   |
| 301-350        | 3         | 1.38%   |
| 351-500        | 2         | 0.92%   |
| 151-200        | 2         | 0.92%   |
| 91-100         | 2         | 0.92%   |
| 131-140        | 1         | 0.46%   |
| 501-1000       | 1         | 0.46%   |
| Unknown        | 1         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 106       | 49.07%  |
| 121-160       | 72        | 33.33%  |
| 51-100        | 24        | 11.11%  |
| 1-50          | 6         | 2.78%   |
| 161-240       | 4         | 1.85%   |
| More than 240 | 3         | 1.39%   |
| Unknown       | 1         | 0.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 175       | 83.33%  |
| 2     | 25        | 11.9%   |
| 0     | 8         | 3.81%   |
| 3     | 2         | 0.95%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 112       | 34.78%  |
| Intel                            | 86        | 26.71%  |
| Qualcomm Atheros                 | 61        | 18.94%  |
| Broadcom                         | 33        | 10.25%  |
| Ralink Technology                | 5         | 1.55%   |
| Nvidia                           | 5         | 1.55%   |
| Broadcom Limited                 | 4         | 1.24%   |
| Silicon Integrated Systems [SiS] | 3         | 0.93%   |
| Marvell Technology Group         | 3         | 0.93%   |
| JMicron Technology               | 2         | 0.62%   |
| Qualcomm Atheros Communications  | 1         | 0.31%   |
| NetGear                          | 1         | 0.31%   |
| MEDIATEK                         | 1         | 0.31%   |
| Hewlett-Packard                  | 1         | 0.31%   |
| Encore Electronics               | 1         | 0.31%   |
| Dell                             | 1         | 0.31%   |
| BUFFALO                          | 1         | 0.31%   |
| ASIX Electronics                 | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 67        | 17.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 31        | 8.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 12        | 3.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 3.16%   |
| Intel Wireless 7265                                                     | 12        | 3.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 11        | 2.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 10        | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 2.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 2.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 2.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 2.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 1.58%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 1.32%   |
| Intel Wireless 7260                                                     | 5         | 1.32%   |
| Intel Wireless 3165                                                     | 5         | 1.32%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 1.32%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 4         | 1.05%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.05%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 4         | 1.05%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 3         | 0.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.79%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 3         | 0.79%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 3         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.79%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 0.79%   |
| Intel Centrino Wireless-N 2200                                          | 3         | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 0.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 0.79%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 2         | 0.53%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 2         | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.53%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.53%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.53%   |
| Nvidia MCP79 Ethernet                                                   | 2         | 0.53%   |
| Intel Wireless 8260                                                     | 2         | 0.53%   |
| Intel Ethernet Connection I219-V                                        | 2         | 0.53%   |
| Intel Ethernet Connection (6) I219-LM                                   | 2         | 0.53%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.53%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.53%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.53%   |
| Intel 82577LC Gigabit Network Connection                                | 2         | 0.53%   |
| Intel 82567LM Gigabit Network Connection                                | 2         | 0.53%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 2         | 0.53%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                 | 2         | 0.53%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 0.53%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 0.53%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.26%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.26%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                      | 1         | 0.26%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.26%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 82        | 40.2%   |
| Qualcomm Atheros                | 52        | 25.49%  |
| Realtek Semiconductor           | 32        | 15.69%  |
| Broadcom                        | 25        | 12.25%  |
| Ralink Technology               | 5         | 2.45%   |
| Broadcom Limited                | 2         | 0.98%   |
| Qualcomm Atheros Communications | 1         | 0.49%   |
| NetGear                         | 1         | 0.49%   |
| MEDIATEK                        | 1         | 0.49%   |
| Encore Electronics              | 1         | 0.49%   |
| Dell                            | 1         | 0.49%   |
| BUFFALO                         | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 12        | 5.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 12        | 5.85%   |
| Intel Wireless 7265                                                     | 12        | 5.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 11        | 5.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 4.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 4.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 4.39%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 3.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 6         | 2.93%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 2.44%   |
| Intel Wireless 7260                                                     | 5         | 2.44%   |
| Intel Wireless 3165                                                     | 5         | 2.44%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.44%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.95%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.46%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.46%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 3         | 1.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.46%   |
| Intel Wi-Fi 6 AX200                                                     | 3         | 1.46%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.46%   |
| Intel Centrino Wireless-N 2200                                          | 3         | 1.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.46%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.98%   |
| Intel Wireless 8260                                                     | 2         | 0.98%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 2         | 0.98%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.98%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 0.98%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 0.98%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.49%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.49%   |
| Realtek RTL8192E/RTL8192SE Wireless LAN Controller                      | 1         | 0.49%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.49%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.49%   |
| Realtek 802.11n WLAN Adapter                                            | 1         | 0.49%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.49%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.49%   |
| NetGear WG111v2 54 Mbps Wireless [RealTek RTL8187L]                     | 1         | 0.49%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.49%   |
| Intel Wireless 3160                                                     | 1         | 0.49%   |
| Intel WiFi Link 5100                                                    | 1         | 0.49%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1         | 0.49%   |
| Intel Wi-Fi 6 AX201                                                     | 1         | 0.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 0.49%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.49%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 1         | 0.49%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.49%   |
| Intel Centrino Wireless-N 135                                           | 1         | 0.49%   |
| Intel Centrino Wireless-N 130                                           | 1         | 0.49%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.49%   |
| Encore ENUWI-N3 [802.11n Wireless N150 Adapter]                         | 1         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 102       | 58.96%  |
| Intel                            | 29        | 16.76%  |
| Qualcomm Atheros                 | 16        | 9.25%   |
| Broadcom                         | 10        | 5.78%   |
| Nvidia                           | 5         | 2.89%   |
| Silicon Integrated Systems [SiS] | 3         | 1.73%   |
| Marvell Technology Group         | 3         | 1.73%   |
| JMicron Technology               | 2         | 1.16%   |
| Broadcom Limited                 | 2         | 1.16%   |
| ASIX Electronics                 | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 67        | 38.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 31        | 17.82%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 5.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 4         | 2.3%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 4         | 2.3%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 3         | 1.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 1.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 1.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.15%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 1.15%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 1.15%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 1.15%   |
| Intel Ethernet Connection I219-V                                               | 2         | 1.15%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 1.15%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.15%   |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 1.15%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 1.15%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 1.15%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 1.15%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.57%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 1         | 0.57%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.57%   |
| Nvidia MCP77 Ethernet                                                          | 1         | 0.57%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.57%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.57%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.57%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 1         | 0.57%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.57%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.57%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.57%   |
| Intel PRO/100 VE Network Connection                                            | 1         | 0.57%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.57%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.57%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.57%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.57%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.57%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.57%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.57%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                               | 1         | 0.57%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 1         | 0.57%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 1         | 0.57%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 1         | 0.57%   |
| ASIX AX88772B                                                                  | 1         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 197       | 53.24%  |
| Ethernet | 172       | 46.49%  |
| Modem    | 1         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 178       | 65.68%  |
| Ethernet | 93        | 34.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 158       | 77.45%  |
| 1     | 39        | 19.12%  |
| 0     | 6         | 2.94%   |
| 3     | 1         | 0.49%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 193       | 94.15%  |
| Yes  | 12        | 5.85%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 36.42%  |
| Realtek Semiconductor           | 15        | 9.93%   |
| Lite-On Technology              | 15        | 9.93%   |
| Broadcom                        | 14        | 9.27%   |
| Qualcomm Atheros Communications | 13        | 8.61%   |
| Foxconn / Hon Hai               | 12        | 7.95%   |
| IMC Networks                    | 10        | 6.62%   |
| Apple                           | 6         | 3.97%   |
| Toshiba                         | 3         | 1.99%   |
| Hewlett-Packard                 | 3         | 1.99%   |
| Chicony Electronics             | 2         | 1.32%   |
| Cambridge Silicon Radio         | 2         | 1.32%   |
| Dell                            | 1         | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 28        | 18.54%  |
| Realtek Bluetooth Radio                                                             | 8         | 5.3%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 8         | 5.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 5.3%    |
| Intel AX201 Bluetooth                                                               | 7         | 4.64%   |
| IMC Networks Bluetooth Device                                                       | 6         | 3.97%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 5         | 3.31%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 2.65%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 2.65%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 1.99%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 3         | 1.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.99%   |
| Intel AX200 Bluetooth                                                               | 3         | 1.99%   |
| IMC Networks Bluetooth Radio                                                        | 3         | 1.99%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.99%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 1.32%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 2         | 1.32%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 1.32%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.32%   |
| Lite-On BCM43142A0                                                                  | 2         | 1.32%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 1.32%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.32%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 1.32%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 1.32%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 1.32%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 1.32%   |
| Chicony Bluetooth (RTL8723BE)                                                       | 2         | 1.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 1.32%   |
| Broadcom HP Portable Valentine                                                      | 2         | 1.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.32%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 2         | 1.32%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 1.32%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.32%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.32%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.66%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 1         | 0.66%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.66%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.66%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.66%   |
| Intel Bluetooth Device                                                              | 1         | 0.66%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.66%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.66%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.66%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.66%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.66%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.66%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.66%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.66%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.66%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.66%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 165       | 72.37%  |
| AMD                              | 26        | 11.4%   |
| Nvidia                           | 22        | 9.65%   |
| Silicon Integrated Systems [SiS] | 3         | 1.32%   |
| Plantronics                      | 2         | 0.88%   |
| Logitech                         | 2         | 0.88%   |
| JMTek                            | 2         | 0.88%   |
| SteelSeries ApS                  | 1         | 0.44%   |
| Realtek Semiconductor            | 1         | 0.44%   |
| OPPO Electronics                 | 1         | 0.44%   |
| Generalplus Technology           | 1         | 0.44%   |
| DEXP BK-20                       | 1         | 0.44%   |
| Creative Technology              | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 30        | 11.15%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 8.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 5.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 12        | 4.46%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 12        | 4.46%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 10        | 3.72%   |
| AMD FCH Azalia Controller                                                                         | 10        | 3.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 2.6%    |
| Intel Broadwell-U Audio Controller                                                                | 7         | 2.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 2.6%    |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 2.6%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 6         | 2.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 2.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 2.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2.23%   |
| Intel 8 Series HD Audio Controller                                                                | 6         | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.86%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.86%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.49%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.49%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.49%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.49%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 3         | 1.12%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 1.12%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 1.12%   |
| Nvidia Audio device                                                                               | 3         | 1.12%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 3         | 1.12%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.74%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.74%   |
| SteelSeries ApS SteelSeries Arctis 5                                                              | 1         | 0.37%   |
| Realtek Semiconductor Realtek USB2.0 Audio                                                        | 1         | 0.37%   |
| Plantronics C510-M                                                                                | 1         | 0.37%   |
| Plantronics Audio 628 USB                                                                         | 1         | 0.37%   |
| OPPO Electronics Electronics Multimedia audio controller                                          | 1         | 0.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.37%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.37%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.37%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.37%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.37%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.37%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.37%   |
| Logitech [G533 Wireless Headset Dongle]                                                           | 1         | 0.37%   |
| Logitech USB Headset                                                                              | 1         | 0.37%   |
| JMTek USB Speaker                                                                                 | 1         | 0.37%   |
| JMTek USB PnP Audio Device                                                                        | 1         | 0.37%   |
| Intel USB PnP Sound Device                                                                        | 1         | 0.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 1         | 0.37%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.37%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.37%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 1         | 0.37%   |
| Generalplus Technology Usb Audio Device                                                           | 1         | 0.37%   |
| DEXP BK-20 DEXP BK-20                                                                             | 1         | 0.37%   |
| Creative Technology SB X-Fi Surround 5.1                                                          | 1         | 0.37%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.37%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 25.83%  |
| SK Hynix            | 24        | 20%     |
| Kingston            | 23        | 19.17%  |
| Unknown             | 10        | 8.33%   |
| Micron Technology   | 10        | 8.33%   |
| Ramaxel Technology  | 6         | 5%      |
| Team                | 4         | 3.33%   |
| Crucial             | 4         | 3.33%   |
| Unknown (ABCD)      | 2         | 1.67%   |
| Transcend           | 1         | 0.83%   |
| Nanya Technology    | 1         | 0.83%   |
| G.Skill             | 1         | 0.83%   |
| Elpida              | 1         | 0.83%   |
| ASint Technology    | 1         | 0.83%   |
| A-DATA Technology   | 1         | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 5         | 3.97%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 4         | 3.17%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 3         | 2.38%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 2.38%   |
| Kingston RAM 99U5428-018.A00LF 8192MB SODIMM DDR3 1600MT/s          | 3         | 2.38%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 1.59%   |
| Team RAM TEAMGROUP-SD4-2400 8192MB SODIMM DDR4 8400MT/s             | 2         | 1.59%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 1.59%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 1.59%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                      | 2         | 1.59%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.59%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 1.59%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.59%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 2         | 1.59%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s              | 2         | 1.59%   |
| Kingston RAM 99U5428-101.A00LF 8GB SODIMM DDR3 1600MT/s             | 2         | 1.59%   |
| Kingston RAM 9905700-025.A00G 8GB SODIMM DDR4 2667MT/s              | 2         | 1.59%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                         | 1         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 0.79%   |
| Unknown RAM Module 2048MB SODIMM DRAM 667MT/s                       | 1         | 0.79%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 0.79%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.79%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 0.79%   |
| Unknown RAM Module 2048MB SODIMM 667MT/s                            | 1         | 0.79%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 0.79%   |
| Unknown RAM Module 1024MB SODIMM DDR2 400MT/s                       | 1         | 0.79%   |
| Unknown RAM Module 1024MB SODIMM 667MT/s                            | 1         | 0.79%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s              | 1         | 0.79%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s               | 1         | 0.79%   |
| Team RAM Elite-1600 8GB SODIMM DDR3 1600MT/s                        | 1         | 0.79%   |
| Team RAM Elite-1333 8GB SODIMM DDR3 1334MT/s                        | 1         | 0.79%   |
| SK Hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s             | 1         | 0.79%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.79%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.79%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.79%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.79%   |
| SK Hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.79%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s              | 1         | 0.79%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s           | 1         | 0.79%   |
| SK Hynix RAM HMP125S6EFR8C-S6 2048MB SODIMM DDR2 800MT/s            | 1         | 0.79%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 1         | 0.79%   |
| SK Hynix RAM HMAA1GS6CMR6N-XN 8192MB Row Of Chips DDR4 3200MT/s     | 1         | 0.79%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.79%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 1         | 0.79%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 1         | 0.79%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.79%   |
| Samsung RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 0.79%   |
| Samsung RAM Module 16384MB SODIMM DDR4 3200MT/s                     | 1         | 0.79%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s               | 1         | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 1         | 0.79%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.79%   |
| Samsung RAM M471B2873FHS-CH9 1GB SODIMM DDR3 1334MT/s               | 1         | 0.79%   |
| Samsung RAM M471B2873EH1-CF8 1GB SODIMM DDR3 1067MT/s               | 1         | 0.79%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.79%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.79%   |
| Samsung RAM M471B1G73BH0-CK0 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 1         | 0.79%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 0.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 40        | 42.55%  |
| DDR4    | 38        | 40.43%  |
| DDR2    | 7         | 7.45%   |
| LPDDR4  | 4         | 4.26%   |
| Unknown | 2         | 2.13%   |
| SDRAM   | 1         | 1.06%   |
| LPDDR3  | 1         | 1.06%   |
| DRAM    | 1         | 1.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 89        | 96.74%  |
| Row Of Chips | 3         | 3.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 39        | 35.78%  |
| 4096  | 35        | 32.11%  |
| 2048  | 20        | 18.35%  |
| 1024  | 7         | 6.42%   |
| 16384 | 6         | 5.5%    |
| 32768 | 2         | 1.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 31        | 28.7%   |
| 2667    | 25        | 23.15%  |
| 2400    | 10        | 9.26%   |
| 3200    | 9         | 8.33%   |
| 667     | 8         | 7.41%   |
| 1334    | 7         | 6.48%   |
| 1333    | 6         | 5.56%   |
| 8400    | 2         | 1.85%   |
| 4266    | 1         | 0.93%   |
| 3266    | 1         | 0.93%   |
| 2133    | 1         | 0.93%   |
| 2048    | 1         | 0.93%   |
| 1067    | 1         | 0.93%   |
| 1066    | 1         | 0.93%   |
| 800     | 1         | 0.93%   |
| 533     | 1         | 0.93%   |
| 400     | 1         | 0.93%   |
| Unknown | 1         | 0.93%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 2         | 66.67%  |
| Seiko Epson        | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L222 Series | 1         | 33.33%  |
| Brother DCP-T710W       | 1         | 33.33%  |
| Brother DCP-T310        | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 51        | 29.48%  |
| Realtek Semiconductor                  | 17        | 9.83%   |
| Acer                                   | 14        | 8.09%   |
| IMC Networks                           | 13        | 7.51%   |
| Quanta                                 | 11        | 6.36%   |
| Microdia                               | 10        | 5.78%   |
| Sunplus Innovation Technology          | 9         | 5.2%    |
| Suyin                                  | 6         | 3.47%   |
| Lite-On Technology                     | 6         | 3.47%   |
| Apple                                  | 6         | 3.47%   |
| Silicon Motion                         | 5         | 2.89%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.89%   |
| Alcor Micro                            | 4         | 2.31%   |
| Syntek                                 | 3         | 1.73%   |
| Samsung Electronics                    | 2         | 1.16%   |
| ALi                                    | 2         | 1.16%   |
| Z-Star Microelectronics                | 1         | 0.58%   |
| Ricoh                                  | 1         | 0.58%   |
| OmniVision Technologies                | 1         | 0.58%   |
| Lenovo                                 | 1         | 0.58%   |
| Importek                               | 1         | 0.58%   |
| Goertek Electronics                    | 1         | 0.58%   |
| GEMBIRD                                | 1         | 0.58%   |
| DigiTech                               | 1         | 0.58%   |
| Alpha Imaging Technology               | 1         | 0.58%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 11        | 6.36%   |
| Chicony HD WebCam                                               | 9         | 5.2%    |
| Realtek Acer 640 x 480 laptop camera                            | 6         | 3.47%   |
| Quanta VGA WebCam                                               | 4         | 2.31%   |
| Quanta HD WebCam                                                | 4         | 2.31%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 4         | 2.31%   |
| Realtek Integrated_Webcam_HD                                    | 3         | 1.73%   |
| Microdia Integrated_Webcam_HD                                   | 3         | 1.73%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 3         | 1.73%   |
| Chicony VGA WebCam                                              | 3         | 1.73%   |
| Chicony Lenovo EasyCamera                                       | 3         | 1.73%   |
| Chicony HP Truevision HD                                        | 3         | 1.73%   |
| Apple Built-in iSight                                           | 3         | 1.73%   |
| Acer Lenovo EasyCamera                                          | 3         | 1.73%   |
| Acer EasyCamera                                                 | 3         | 1.73%   |
| Syntek Lenovo EasyCamera                                        | 2         | 1.16%   |
| Suyin HP Webcam                                                 | 2         | 1.16%   |
| Sunplus Laptop Integrated WebCam HD                             | 2         | 1.16%   |
| Sunplus HD WebCam                                               | 2         | 1.16%   |
| Samsung Galaxy A5 (MTP)                                         | 2         | 1.16%   |
| Realtek USB2.0 VGA UVC WebCam                                   | 2         | 1.16%   |
| Quanta HD User Facing                                           | 2         | 1.16%   |
| Lite-On TOSHIBA Web Camera - HD                                 | 2         | 1.16%   |
| Lite-On Integrated Camera                                       | 2         | 1.16%   |
| Lite-On HP HD Camera                                            | 2         | 1.16%   |
| IMC Networks Integrated Camera                                  | 2         | 1.16%   |
| IMC Networks EasyCamera                                         | 2         | 1.16%   |
| Chicony USB 2.0 Camera                                          | 2         | 1.16%   |
| Chicony TOSHIBA Web Camera - HD                                 | 2         | 1.16%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 2         | 1.16%   |
| Chicony Integrated Camera (1280x720@30)                         | 2         | 1.16%   |
| Chicony HP HD Camera                                            | 2         | 1.16%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 1.16%   |
| Apple FaceTime Camera                                           | 2         | 1.16%   |
| ALi WebCam                                                      | 2         | 1.16%   |
| Alcor Micro HD WebCam                                           | 2         | 1.16%   |
| Acer Integrated Camera                                          | 2         | 1.16%   |
| Z-Star Webcam                                                   | 1         | 0.58%   |
| Syntek Integrated Camera                                        | 1         | 0.58%   |
| Suyin UVC HD Webcam                                             | 1         | 0.58%   |
| Suyin USB 2.0 Camera                                            | 1         | 0.58%   |
| Suyin HP Truevision HD                                          | 1         | 0.58%   |
| Suyin Acer/Lenovo Webcam [CN0316]                               | 1         | 0.58%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 0.58%   |
| Sunplus Integrated Webcam                                       | 1         | 0.58%   |
| Sunplus HP Truevision HD                                        | 1         | 0.58%   |
| Sunplus HP HD Webcam [Fixed]                                    | 1         | 0.58%   |
| Sunplus ASUS USB2.0 Webcam                                      | 1         | 0.58%   |
| Silicon Motion WebCam SCB-1100N                                 | 1         | 0.58%   |
| Silicon Motion WebCam SC-10HDD13335N                            | 1         | 0.58%   |
| Silicon Motion WebCam SC-03FFM12339N                            | 1         | 0.58%   |
| Silicon Motion Lenovo EasyCamera                                | 1         | 0.58%   |
| Silicon Motion 720p HD Camera                                   | 1         | 0.58%   |
| Ricoh Pavilion Webcam [R5U870]                                  | 1         | 0.58%   |
| Realtek VGA WebCam                                              | 1         | 0.58%   |
| Realtek USB2.0 HD UVC WebCam                                    | 1         | 0.58%   |
| Realtek MTD Camera                                              | 1         | 0.58%   |
| Realtek Integrated Webcam_HD                                    | 1         | 0.58%   |
| Realtek Integrated Webcam                                       | 1         | 0.58%   |
| Realtek EasyCamera                                              | 1         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 33.33%  |
| Synaptics                  | 5         | 23.81%  |
| Upek                       | 3         | 14.29%  |
| Shenzhen Goodix Technology | 3         | 14.29%  |
| AuthenTec                  | 2         | 9.52%   |
| LighTuning Technology      | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 3         | 14.29%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 9.52%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 2         | 9.52%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 1         | 4.76%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 1         | 4.76%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 4.76%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4.76%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 4.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 4.76%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 4.76%   |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 4.76%   |
| Shenzhen Goodix FingerPrint                                | 1         | 4.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 4.76%   |
| AuthenTec Fingerprint Sensor                               | 1         | 4.76%   |
| AuthenTec AES1600                                          | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Broadcom         | 3         | 42.86%  |
| Upek             | 2         | 28.57%  |
| SCM Microsystems | 1         | 14.29%  |
| O2 Micro         | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 28.57%  |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 14.29%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 159       | 76.08%  |
| 1     | 45        | 21.53%  |
| 2     | 5         | 2.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Fingerprint reader | 21        | 38.89%  |
| Graphics card      | 11        | 20.37%  |
| Chipcard           | 7         | 12.96%  |
| Net/wireless       | 6         | 11.11%  |
| Net/ethernet       | 3         | 5.56%   |
| Camera             | 3         | 5.56%   |
| Storage            | 1         | 1.85%   |
| Sound              | 1         | 1.85%   |
| Modem              | 1         | 1.85%   |

