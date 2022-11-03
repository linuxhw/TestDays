Linux in Greece - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Greece.

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

Total: 824

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15-db0xxx            | [aad6abb936](https://linux-hardware.org/?probe=aad6abb936) | Nov 01, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [9dea1bfedb](https://linux-hardware.org/?probe=9dea1bfedb) | Nov 01, 2022 |
| Acer          | Aspire A315-58              | [7870d9b047](https://linux-hardware.org/?probe=7870d9b047) | Oct 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [0e69671817](https://linux-hardware.org/?probe=0e69671817) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK AH530              | [a3f55b1301](https://linux-hardware.org/?probe=a3f55b1301) | Oct 27, 2022 |
| Fujitsu       | LIFEBOOK AH530              | [285a7d17e3](https://linux-hardware.org/?probe=285a7d17e3) | Oct 27, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [26e7b206ef](https://linux-hardware.org/?probe=26e7b206ef) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [c9393d50b5](https://linux-hardware.org/?probe=c9393d50b5) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [5199be5418](https://linux-hardware.org/?probe=5199be5418) | Oct 24, 2022 |
| Apple         | MacBookPro8,1               | [aaad9f52d4](https://linux-hardware.org/?probe=aaad9f52d4) | Oct 24, 2022 |
| Toshiba       | dynabook Satellite T87/8... | [10f344a2b3](https://linux-hardware.org/?probe=10f344a2b3) | Oct 24, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [ade038c388](https://linux-hardware.org/?probe=ade038c388) | Oct 24, 2022 |
| Toshiba       | Satellite C50-B             | [a9041efc75](https://linux-hardware.org/?probe=a9041efc75) | Oct 23, 2022 |
| Acer          | Aspire A315-58              | [e5b07599e3](https://linux-hardware.org/?probe=e5b07599e3) | Oct 22, 2022 |
| HP            | EliteBook 820 G1            | [7abef2546e](https://linux-hardware.org/?probe=7abef2546e) | Oct 21, 2022 |
| Apple         | MacBookPro8,1               | [f3890a4db1](https://linux-hardware.org/?probe=f3890a4db1) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [de5adb6775](https://linux-hardware.org/?probe=de5adb6775) | Oct 21, 2022 |
| HP            | Pavilion g7                 | [19048aa8f0](https://linux-hardware.org/?probe=19048aa8f0) | Oct 19, 2022 |
| Acer          | Aspire V3-771               | [91e4682f34](https://linux-hardware.org/?probe=91e4682f34) | Oct 17, 2022 |
| Lenovo        | B590 20208                  | [6a3309f753](https://linux-hardware.org/?probe=6a3309f753) | Oct 14, 2022 |
| HP            | Pavilion g6                 | [943ee204e0](https://linux-hardware.org/?probe=943ee204e0) | Oct 10, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [a281cc47e5](https://linux-hardware.org/?probe=a281cc47e5) | Oct 10, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [d1c01a07a2](https://linux-hardware.org/?probe=d1c01a07a2) | Oct 08, 2022 |
| Dell          | Precision M6800             | [802d1dbfcd](https://linux-hardware.org/?probe=802d1dbfcd) | Oct 06, 2022 |
| Apple         | MacBookPro5,2               | [b0a6dc4162](https://linux-hardware.org/?probe=b0a6dc4162) | Oct 02, 2022 |
| Dell          | XPS 13 9370                 | [4e0be93d26](https://linux-hardware.org/?probe=4e0be93d26) | Sep 29, 2022 |
| Purism        | Librem 14                   | [213731b934](https://linux-hardware.org/?probe=213731b934) | Sep 24, 2022 |
| HP            | Notebook                    | [18b9221add](https://linux-hardware.org/?probe=18b9221add) | Sep 22, 2022 |
| Lenovo        | G50-45 80E3                 | [5c9688dac8](https://linux-hardware.org/?probe=5c9688dac8) | Sep 19, 2022 |
| Lenovo        | ThinkPad X230 23252QG       | [4146ff55f9](https://linux-hardware.org/?probe=4146ff55f9) | Sep 10, 2022 |
| Toshiba       | Satellite C55-A-1JL         | [906f27f221](https://linux-hardware.org/?probe=906f27f221) | Sep 10, 2022 |
| Toshiba       | Satellite C55-A-1JL         | [d229fa96f3](https://linux-hardware.org/?probe=d229fa96f3) | Sep 08, 2022 |
| Lenovo        | B5400 20278                 | [1c9d752f91](https://linux-hardware.org/?probe=1c9d752f91) | Sep 07, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [ea93dfd855](https://linux-hardware.org/?probe=ea93dfd855) | Sep 04, 2022 |
| HP            | EliteBook 8470p             | [109d233976](https://linux-hardware.org/?probe=109d233976) | Sep 03, 2022 |
| HP            | 620                         | [34002dc814](https://linux-hardware.org/?probe=34002dc814) | Sep 02, 2022 |
| Lenovo        | V14-ADA 82C6                | [5e98ea70fb](https://linux-hardware.org/?probe=5e98ea70fb) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [4aa935356c](https://linux-hardware.org/?probe=4aa935356c) | Sep 02, 2022 |
| Toshiba       | Satellite C850D-118         | [1950f0aeac](https://linux-hardware.org/?probe=1950f0aeac) | Aug 31, 2022 |
| Toshiba       | Satellite C850D-118         | [07000e4194](https://linux-hardware.org/?probe=07000e4194) | Aug 30, 2022 |
| Dell          | G15 5515                    | [708ef41c02](https://linux-hardware.org/?probe=708ef41c02) | Aug 29, 2022 |
| Plaisio       | Turbo X                     | [ae92ead1ca](https://linux-hardware.org/?probe=ae92ead1ca) | Aug 29, 2022 |
| Lenovo        | B590 20208                  | [7eaabdb9ca](https://linux-hardware.org/?probe=7eaabdb9ca) | Aug 27, 2022 |
| Sony          | VPCEB1S1E                   | [45dbb67d02](https://linux-hardware.org/?probe=45dbb67d02) | Aug 18, 2022 |
| Dell          | G15 5515                    | [3a7c8ea452](https://linux-hardware.org/?probe=3a7c8ea452) | Aug 17, 2022 |
| ASUSTek       | UX310UQ                     | [f058aa0bf2](https://linux-hardware.org/?probe=f058aa0bf2) | Aug 15, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| HP            | Laptop 15-db1xxx            | [0644c9f46c](https://linux-hardware.org/?probe=0644c9f46c) | Aug 12, 2022 |
| Lenovo        | V3000 80KV                  | [32c1aa64cf](https://linux-hardware.org/?probe=32c1aa64cf) | Aug 09, 2022 |
| HP            | Laptop 15-db1xxx            | [9e849a1708](https://linux-hardware.org/?probe=9e849a1708) | Aug 07, 2022 |
| Toshiba       | NB100                       | [b91ee9b36b](https://linux-hardware.org/?probe=b91ee9b36b) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e74155922c](https://linux-hardware.org/?probe=e74155922c) | Aug 04, 2022 |
| HP            | Compaq 6730s                | [5d805b2f5e](https://linux-hardware.org/?probe=5d805b2f5e) | Jul 31, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | [7b0b52e138](https://linux-hardware.org/?probe=7b0b52e138) | Jul 31, 2022 |
| HP            | Laptop 15s-eq1xxx           | [ee5c151c3a](https://linux-hardware.org/?probe=ee5c151c3a) | Jul 30, 2022 |
| HP            | 255 G8 Notebook PC          | [e271ff9bf8](https://linux-hardware.org/?probe=e271ff9bf8) | Jul 29, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | [398fb75cec](https://linux-hardware.org/?probe=398fb75cec) | Jul 29, 2022 |
| HP            | 255 G8 Notebook PC          | [ceb1b7da41](https://linux-hardware.org/?probe=ceb1b7da41) | Jul 28, 2022 |
| Apple         | MacBookPro8,1               | [cf1f919243](https://linux-hardware.org/?probe=cf1f919243) | Jul 27, 2022 |
| HP            | Pavilion g6                 | [a57cf84361](https://linux-hardware.org/?probe=a57cf84361) | Jul 27, 2022 |
| Sony          | VPCF11M1E                   | [97a18303ee](https://linux-hardware.org/?probe=97a18303ee) | Jul 26, 2022 |
| Dynabook      | Satellite Pro C50D-B        | [bd7ef0af73](https://linux-hardware.org/?probe=bd7ef0af73) | Jul 25, 2022 |
| Dell          | Latitude 5420               | [eecbd6aeec](https://linux-hardware.org/?probe=eecbd6aeec) | Jul 22, 2022 |
| HP            | 255 G8 Notebook PC          | [59e9017400](https://linux-hardware.org/?probe=59e9017400) | Jul 19, 2022 |
| Dell          | Inspiron 15 3511            | [257823caa8](https://linux-hardware.org/?probe=257823caa8) | Jul 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [3884be1bc0](https://linux-hardware.org/?probe=3884be1bc0) | Jul 15, 2022 |
| Acer          | Extensa 215-32              | [bd34d99acc](https://linux-hardware.org/?probe=bd34d99acc) | Jul 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [e992a45818](https://linux-hardware.org/?probe=e992a45818) | Jul 15, 2022 |
| Toshiba       | Satellite L550              | [cb3f0e6381](https://linux-hardware.org/?probe=cb3f0e6381) | Jul 13, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [f52d09ef30](https://linux-hardware.org/?probe=f52d09ef30) | Jul 07, 2022 |
| HP            | Compaq CQ58                 | [d46da7be57](https://linux-hardware.org/?probe=d46da7be57) | Jul 05, 2022 |
| Unknown       | Unknown                     | [df0722af87](https://linux-hardware.org/?probe=df0722af87) | Jul 04, 2022 |
| HP            | 255 G8 Notebook PC          | [af74b651d5](https://linux-hardware.org/?probe=af74b651d5) | Jul 04, 2022 |
| Toshiba       | Satellite A200              | [d030e357db](https://linux-hardware.org/?probe=d030e357db) | Jul 02, 2022 |
| HP            | Laptop 17-ca1xxx            | [10620fe30b](https://linux-hardware.org/?probe=10620fe30b) | Jun 29, 2022 |
| Valve         | Jupiter                     | [65e5ab29fd](https://linux-hardware.org/?probe=65e5ab29fd) | Jun 26, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [bb4f0d2bce](https://linux-hardware.org/?probe=bb4f0d2bce) | Jun 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [a2a6f48fe2](https://linux-hardware.org/?probe=a2a6f48fe2) | Jun 22, 2022 |
| ASUSTek       | X550JX                      | [999d6e4735](https://linux-hardware.org/?probe=999d6e4735) | Jun 20, 2022 |
| HP            | EliteBook 840 G4            | [d42c64a985](https://linux-hardware.org/?probe=d42c64a985) | Jun 18, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [ee0b4c4389](https://linux-hardware.org/?probe=ee0b4c4389) | Jun 14, 2022 |
| Dell          | XPS 13 9380                 | [af2362a1e4](https://linux-hardware.org/?probe=af2362a1e4) | Jun 12, 2022 |
| HP            | ProBook 4530s               | [8162a82eba](https://linux-hardware.org/?probe=8162a82eba) | Jun 11, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [039d0b1cdc](https://linux-hardware.org/?probe=039d0b1cdc) | Jun 07, 2022 |
| Dell          | Precision M4800             | [2607169dfe](https://linux-hardware.org/?probe=2607169dfe) | Jun 06, 2022 |
| Dell          | Inspiron 5567               | [3ede7ad313](https://linux-hardware.org/?probe=3ede7ad313) | Jun 02, 2022 |
| Dell          | Inspiron 5567               | [e8e9948f71](https://linux-hardware.org/?probe=e8e9948f71) | Jun 02, 2022 |
| HP            | Unknown                     | [521124e0e2](https://linux-hardware.org/?probe=521124e0e2) | May 28, 2022 |
| Lenovo        | ThinkPad X230 2324FV6       | [6386696f31](https://linux-hardware.org/?probe=6386696f31) | May 25, 2022 |
| Dell          | Vostro 5625                 | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| Dell          | Latitude 5420               | [28c0f1ba96](https://linux-hardware.org/?probe=28c0f1ba96) | May 24, 2022 |
| ASUSTek       | X505BA                      | [685c1f7378](https://linux-hardware.org/?probe=685c1f7378) | May 22, 2022 |
| Pegatron      | A15                         | [335d6a014c](https://linux-hardware.org/?probe=335d6a014c) | May 18, 2022 |
| HP            | Mini 110-1100               | [b93ac7c302](https://linux-hardware.org/?probe=b93ac7c302) | May 16, 2022 |
| HP            | Mini 110-1100               | [4a5f85e53d](https://linux-hardware.org/?probe=4a5f85e53d) | May 16, 2022 |
| HP            | ProBook 645 G1              | [771f25ecc9](https://linux-hardware.org/?probe=771f25ecc9) | May 14, 2022 |
| HP            | EliteBook 8470p             | [2c8d1eec1e](https://linux-hardware.org/?probe=2c8d1eec1e) | May 13, 2022 |
| HP            | EliteBook 8470p             | [074043a5ca](https://linux-hardware.org/?probe=074043a5ca) | May 13, 2022 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [ec5dbcb034](https://linux-hardware.org/?probe=ec5dbcb034) | May 02, 2022 |
| Dell          | Latitude E6500              | [bbd302d9ba](https://linux-hardware.org/?probe=bbd302d9ba) | May 02, 2022 |
| Dell          | Latitude E6500              | [8eb92ca472](https://linux-hardware.org/?probe=8eb92ca472) | May 02, 2022 |
| Lenovo        | ThinkPad T495 20NJ0012GM    | [81f7a796be](https://linux-hardware.org/?probe=81f7a796be) | Apr 28, 2022 |
| Dell          | Inspiron 5567               | [9da2289998](https://linux-hardware.org/?probe=9da2289998) | Apr 24, 2022 |
| Dell          | Inspiron 5559               | [e9676d63f9](https://linux-hardware.org/?probe=e9676d63f9) | Apr 24, 2022 |
| HP            | Notebook                    | [4772a69956](https://linux-hardware.org/?probe=4772a69956) | Apr 23, 2022 |
| HP            | Notebook                    | [e6099e9fd5](https://linux-hardware.org/?probe=e6099e9fd5) | Apr 22, 2022 |
| HP            | Pavilion g7                 | [6bfdb0c3c9](https://linux-hardware.org/?probe=6bfdb0c3c9) | Apr 19, 2022 |
| HP            | Pavilion g7                 | [97e00013eb](https://linux-hardware.org/?probe=97e00013eb) | Apr 19, 2022 |
| Dell          | XPS 15 7590                 | [ee7354dd8d](https://linux-hardware.org/?probe=ee7354dd8d) | Apr 19, 2022 |
| Alienware     | M11x                        | [df72ecbe58](https://linux-hardware.org/?probe=df72ecbe58) | Apr 18, 2022 |
| Acer          | Aspire A315-51              | [a6ae41a1c9](https://linux-hardware.org/?probe=a6ae41a1c9) | Apr 18, 2022 |
| Toshiba       | Satellite L50D-B            | [c5d02ba256](https://linux-hardware.org/?probe=c5d02ba256) | Apr 17, 2022 |
| HP            | Pavilion Notebook           | [217905d42a](https://linux-hardware.org/?probe=217905d42a) | Apr 17, 2022 |
| Toshiba       | Satellite L50D-B            | [912c61bb9b](https://linux-hardware.org/?probe=912c61bb9b) | Apr 15, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [4838334e73](https://linux-hardware.org/?probe=4838334e73) | Apr 14, 2022 |
| Dell          | Latitude D630               | [dbee98e342](https://linux-hardware.org/?probe=dbee98e342) | Apr 13, 2022 |
| HP            | 250 G5 Notebook PC          | [92b78eaf1b](https://linux-hardware.org/?probe=92b78eaf1b) | Apr 13, 2022 |
| Dell          | Inspiron 3542               | [b41fc0fac0](https://linux-hardware.org/?probe=b41fc0fac0) | Apr 13, 2022 |
| Unknown       | Z37S                        | [25d5118843](https://linux-hardware.org/?probe=25d5118843) | Apr 13, 2022 |
| Schenker      | XMG NEO (TGL/M21)           | [eeb87dca9a](https://linux-hardware.org/?probe=eeb87dca9a) | Apr 13, 2022 |
| HP            | G7000                       | [11280d88c6](https://linux-hardware.org/?probe=11280d88c6) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [091e8b72d9](https://linux-hardware.org/?probe=091e8b72d9) | Apr 05, 2022 |
| TUXEDO        | Aura 15 Gen1                | [cda73dafa0](https://linux-hardware.org/?probe=cda73dafa0) | Apr 04, 2022 |
| Acer          | Aspire 5745G                | [4a6e981204](https://linux-hardware.org/?probe=4a6e981204) | Apr 04, 2022 |
| Acer          | Aspire 5750G                | [8aeaa381e8](https://linux-hardware.org/?probe=8aeaa381e8) | Apr 03, 2022 |
| Acer          | Aspire 5750G                | [722346a184](https://linux-hardware.org/?probe=722346a184) | Apr 03, 2022 |
| Sony          | VGN-AW11XU_Q                | [b3f2270d5f](https://linux-hardware.org/?probe=b3f2270d5f) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [6b00b2928a](https://linux-hardware.org/?probe=6b00b2928a) | Apr 01, 2022 |
| HP            | Unknown                     | [e989736b06](https://linux-hardware.org/?probe=e989736b06) | Mar 30, 2022 |
| HP            | Unknown                     | [672d3c8b62](https://linux-hardware.org/?probe=672d3c8b62) | Mar 29, 2022 |
| HP            | 250 G3                      | [22f691edac](https://linux-hardware.org/?probe=22f691edac) | Mar 29, 2022 |
| Dell          | Latitude 7420               | [9ef752b49a](https://linux-hardware.org/?probe=9ef752b49a) | Mar 27, 2022 |
| HP            | ProBook 4530s               | [f4d3c7fddf](https://linux-hardware.org/?probe=f4d3c7fddf) | Mar 25, 2022 |
| HP            | Laptop 15s-eq0xxx           | [22d9e9ead2](https://linux-hardware.org/?probe=22d9e9ead2) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | [09576b4897](https://linux-hardware.org/?probe=09576b4897) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | [610b3ad535](https://linux-hardware.org/?probe=610b3ad535) | Mar 25, 2022 |
| Dell          | Latitude E6220              | [b006a7da3b](https://linux-hardware.org/?probe=b006a7da3b) | Mar 23, 2022 |
| Acer          | Aspire 5930                 | [ac66ce376e](https://linux-hardware.org/?probe=ac66ce376e) | Mar 23, 2022 |
| ASUSTek       | N752VX                      | [9eb7fe04cf](https://linux-hardware.org/?probe=9eb7fe04cf) | Mar 21, 2022 |
| Dell          | Latitude E7470              | [db5eecff9e](https://linux-hardware.org/?probe=db5eecff9e) | Mar 16, 2022 |
| HP            | Laptop 15s-eq0xxx           | [321ad64376](https://linux-hardware.org/?probe=321ad64376) | Mar 13, 2022 |
| HP            | Laptop 15s-eq0xxx           | [d5bc8e4202](https://linux-hardware.org/?probe=d5bc8e4202) | Mar 13, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| Toshiba       | Satellite C50-B             | [6bffc83185](https://linux-hardware.org/?probe=6bffc83185) | Mar 08, 2022 |
| Dell          | Latitude E6430              | [e32f5b40a1](https://linux-hardware.org/?probe=e32f5b40a1) | Mar 07, 2022 |
| ASUSTek       | X101CH                      | [486f5c28ad](https://linux-hardware.org/?probe=486f5c28ad) | Mar 07, 2022 |
| Acer          | Aspire A515-44G             | [7f95a3373c](https://linux-hardware.org/?probe=7f95a3373c) | Mar 06, 2022 |
| Acer          | Aspire A515-44G             | [ea17b9cff2](https://linux-hardware.org/?probe=ea17b9cff2) | Mar 06, 2022 |
| Dell          | Inspiron 3593               | [9e9718070f](https://linux-hardware.org/?probe=9e9718070f) | Mar 02, 2022 |
| Toshiba       | Satellite C50-A-19T         | [daa7733b2d](https://linux-hardware.org/?probe=daa7733b2d) | Feb 28, 2022 |
| ASUSTek       | X550CA                      | [926781b691](https://linux-hardware.org/?probe=926781b691) | Feb 27, 2022 |
| Fujitsu       | LIFEBOOK S752               | [abb12adccc](https://linux-hardware.org/?probe=abb12adccc) | Feb 26, 2022 |
| HP            | 2000                        | [53d7131a3d](https://linux-hardware.org/?probe=53d7131a3d) | Feb 26, 2022 |
| Clevo         | M740TU(N)/M760TU(N)/W7X0... | [810f5ad6fa](https://linux-hardware.org/?probe=810f5ad6fa) | Feb 25, 2022 |
| Fujitsu       | LIFEBOOK AH512              | [d7889a52d1](https://linux-hardware.org/?probe=d7889a52d1) | Feb 24, 2022 |
| ASUSTek       | X550CA                      | [ad54ee0dbe](https://linux-hardware.org/?probe=ad54ee0dbe) | Feb 20, 2022 |
| Dell          | Inspiron 5567               | [1ba170be6a](https://linux-hardware.org/?probe=1ba170be6a) | Feb 20, 2022 |
| ASUSTek       | X550CA                      | [c036f1a977](https://linux-hardware.org/?probe=c036f1a977) | Feb 20, 2022 |
| Teclast       | F7                          | [fccda8fbdc](https://linux-hardware.org/?probe=fccda8fbdc) | Feb 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [b8e767511b](https://linux-hardware.org/?probe=b8e767511b) | Feb 19, 2022 |
| Lenovo        | G700 20251                  | [2e68ddfdd3](https://linux-hardware.org/?probe=2e68ddfdd3) | Feb 18, 2022 |
| TUXEDO        | Aura 15 Gen1                | [536a1e49b0](https://linux-hardware.org/?probe=536a1e49b0) | Feb 17, 2022 |
| E-shop.gr     | V113                        | [e9a1ae2e96](https://linux-hardware.org/?probe=e9a1ae2e96) | Feb 14, 2022 |
| HP            | ProBook 640 G1              | [640d06ac28](https://linux-hardware.org/?probe=640d06ac28) | Feb 12, 2022 |
| E-shop.gr     | V113                        | [6d015f399b](https://linux-hardware.org/?probe=6d015f399b) | Feb 12, 2022 |
| HP            | Pavilion 11 x360 PC         | [dcd0177f71](https://linux-hardware.org/?probe=dcd0177f71) | Feb 07, 2022 |
| ASUSTek       | 900                         | [88ce413793](https://linux-hardware.org/?probe=88ce413793) | Feb 06, 2022 |
| HP            | Pavilion Notebook           | [8f79e4d763](https://linux-hardware.org/?probe=8f79e4d763) | Feb 06, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | [5a3fcd1230](https://linux-hardware.org/?probe=5a3fcd1230) | Feb 05, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [e32abec202](https://linux-hardware.org/?probe=e32abec202) | Feb 03, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | [2227d37e2f](https://linux-hardware.org/?probe=2227d37e2f) | Jan 30, 2022 |
| Sony          | SVE1113M1EB                 | [83220eef23](https://linux-hardware.org/?probe=83220eef23) | Jan 30, 2022 |
| HP            | Pavilion dv3                | [c1abcb66ee](https://linux-hardware.org/?probe=c1abcb66ee) | Jan 29, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [48ad956cc2](https://linux-hardware.org/?probe=48ad956cc2) | Jan 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f7633506c3](https://linux-hardware.org/?probe=f7633506c3) | Jan 26, 2022 |
| HP            | EliteBook 8570p             | [5716cdab2a](https://linux-hardware.org/?probe=5716cdab2a) | Jan 21, 2022 |
| HP            | ProBook 640 G1              | [6261e290d6](https://linux-hardware.org/?probe=6261e290d6) | Jan 13, 2022 |
| Dell          | Latitude E5440              | [e4ec245baf](https://linux-hardware.org/?probe=e4ec245baf) | Jan 12, 2022 |
| Lenovo        | ThinkPad Edge 0301GBG       | [41205188c5](https://linux-hardware.org/?probe=41205188c5) | Jan 12, 2022 |
| Unknown       | Unknown                     | [5557e91853](https://linux-hardware.org/?probe=5557e91853) | Jan 09, 2022 |
| HP            | Notebook                    | [97eb40cec9](https://linux-hardware.org/?probe=97eb40cec9) | Jan 07, 2022 |
| Dell          | Inspiron 3585               | [bd035d052c](https://linux-hardware.org/?probe=bd035d052c) | Jan 07, 2022 |
| Lenovo        | G50-70 20351                | [5467cc6a24](https://linux-hardware.org/?probe=5467cc6a24) | Jan 06, 2022 |
| Apple         | MacBookPro5,5               | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| HP            | Compaq 6730s                | [bd8962f904](https://linux-hardware.org/?probe=bd8962f904) | Dec 30, 2021 |
| Acer          | AOA110                      | [1670ad4a71](https://linux-hardware.org/?probe=1670ad4a71) | Dec 29, 2021 |
| HP            | EliteBook 8570p             | [261883bf38](https://linux-hardware.org/?probe=261883bf38) | Dec 23, 2021 |
| HP            | Notebook                    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| TUXEDO        | Aura 15 Gen1                | [c860a1c3c5](https://linux-hardware.org/?probe=c860a1c3c5) | Dec 22, 2021 |
| Dell          | Vostro 3580                 | [a57edf2ddc](https://linux-hardware.org/?probe=a57edf2ddc) | Dec 22, 2021 |
| Sony          | SVE1113M1EB                 | [09619ba678](https://linux-hardware.org/?probe=09619ba678) | Dec 19, 2021 |
| Dell          | Inspiron 3585               | [e12da201c3](https://linux-hardware.org/?probe=e12da201c3) | Dec 16, 2021 |
| Dell          | Inspiron 3585               | [f8e1e0ea63](https://linux-hardware.org/?probe=f8e1e0ea63) | Dec 16, 2021 |
| Sony          | SVE1113M1EB                 | [a91f9c891f](https://linux-hardware.org/?probe=a91f9c891f) | Dec 15, 2021 |
| HP            | G62                         | [80ca0b53f0](https://linux-hardware.org/?probe=80ca0b53f0) | Dec 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ecc22ad350](https://linux-hardware.org/?probe=ecc22ad350) | Dec 12, 2021 |
| Sony          | SVF1521A1EW                 | [3ffae5f3ba](https://linux-hardware.org/?probe=3ffae5f3ba) | Dec 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [b049c5de44](https://linux-hardware.org/?probe=b049c5de44) | Dec 12, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [191c3b9c7e](https://linux-hardware.org/?probe=191c3b9c7e) | Dec 10, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c7efd05b73](https://linux-hardware.org/?probe=c7efd05b73) | Dec 10, 2021 |
| Toshiba       | Satellite C850D-118         | [b15f2e2c92](https://linux-hardware.org/?probe=b15f2e2c92) | Dec 09, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f0a11b91f5](https://linux-hardware.org/?probe=f0a11b91f5) | Dec 09, 2021 |
| Dell          | Inspiron 3585               | [eea11725bb](https://linux-hardware.org/?probe=eea11725bb) | Dec 06, 2021 |
| Dell          | Inspiron 3585               | [d614f524af](https://linux-hardware.org/?probe=d614f524af) | Dec 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [e2d660554f](https://linux-hardware.org/?probe=e2d660554f) | Dec 05, 2021 |
| Acer          | Aspire 7540                 | [ebaf96fd07](https://linux-hardware.org/?probe=ebaf96fd07) | Dec 04, 2021 |
| Dell          | Inspiron 3541               | [6b187612d2](https://linux-hardware.org/?probe=6b187612d2) | Dec 04, 2021 |
| Sony          | SVE1711Q1EB                 | [a4e4d21671](https://linux-hardware.org/?probe=a4e4d21671) | Dec 04, 2021 |
| HP            | Compaq 6910p (GC021ET#AB... | [677180a63e](https://linux-hardware.org/?probe=677180a63e) | Dec 03, 2021 |
| Lenovo        | V15-ADA 82C7                | [5ade9a0569](https://linux-hardware.org/?probe=5ade9a0569) | Dec 02, 2021 |
| Lenovo        | G70-35 80Q5                 | [a53168ca9d](https://linux-hardware.org/?probe=a53168ca9d) | Nov 30, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [d860ff9858](https://linux-hardware.org/?probe=d860ff9858) | Nov 30, 2021 |
| HP            | Pavilion g7                 | [da6e298046](https://linux-hardware.org/?probe=da6e298046) | Nov 29, 2021 |
| Sony          | SVE1113M1EB                 | [e2df3c29e6](https://linux-hardware.org/?probe=e2df3c29e6) | Nov 29, 2021 |
| Dell          | Latitude 7490               | [c12e537d05](https://linux-hardware.org/?probe=c12e537d05) | Nov 29, 2021 |
| Toshiba       | Satellite C855-27U          | [5974840aa7](https://linux-hardware.org/?probe=5974840aa7) | Nov 27, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [82a3d5c144](https://linux-hardware.org/?probe=82a3d5c144) | Nov 27, 2021 |
| Unknown       | Unknown                     | [72b623d149](https://linux-hardware.org/?probe=72b623d149) | Nov 27, 2021 |
| Toshiba       | Satellite C850D-118         | [db07af607f](https://linux-hardware.org/?probe=db07af607f) | Nov 26, 2021 |
| Sony          | SVF1521A1EW                 | [52bd968f68](https://linux-hardware.org/?probe=52bd968f68) | Nov 25, 2021 |
| Unknown       | Unknown                     | [b6800c14dc](https://linux-hardware.org/?probe=b6800c14dc) | Nov 21, 2021 |
| Unknown       | Unknown                     | [65b01d9a8a](https://linux-hardware.org/?probe=65b01d9a8a) | Nov 21, 2021 |
| ASUSTek       | X550CC                      | [9915f9e908](https://linux-hardware.org/?probe=9915f9e908) | Nov 20, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [709cd419bc](https://linux-hardware.org/?probe=709cd419bc) | Nov 19, 2021 |
| Acer          | TravelMate 5720             | [77b5cad080](https://linux-hardware.org/?probe=77b5cad080) | Nov 18, 2021 |
| Acer          | Aspire 5735                 | [9b2574c5be](https://linux-hardware.org/?probe=9b2574c5be) | Nov 17, 2021 |
| ASUSTek       | X550CC                      | [e39729aec8](https://linux-hardware.org/?probe=e39729aec8) | Nov 14, 2021 |
| Acer          | Aspire E5-553G              | [b22df8f53d](https://linux-hardware.org/?probe=b22df8f53d) | Nov 14, 2021 |
| Acer          | Aspire E5-553G              | [93d20530a1](https://linux-hardware.org/?probe=93d20530a1) | Nov 14, 2021 |
| Acer          | Aspire 5742                 | [4c0a93b88d](https://linux-hardware.org/?probe=4c0a93b88d) | Nov 12, 2021 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [a7998fa53a](https://linux-hardware.org/?probe=a7998fa53a) | Nov 11, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [9dc24197f3](https://linux-hardware.org/?probe=9dc24197f3) | Nov 09, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [dc9fcc92be](https://linux-hardware.org/?probe=dc9fcc92be) | Nov 08, 2021 |
| ASUSTek       | 900                         | [b3f1475dcf](https://linux-hardware.org/?probe=b3f1475dcf) | Nov 08, 2021 |
| HP            | 255 G1                      | [3676d15104](https://linux-hardware.org/?probe=3676d15104) | Nov 06, 2021 |
| Sony          | SVE1513Y1ESI                | [fc86d071c2](https://linux-hardware.org/?probe=fc86d071c2) | Nov 02, 2021 |
| Fujitsu Si... | AMILO Xi 2428               | [3332a4c510](https://linux-hardware.org/?probe=3332a4c510) | Oct 30, 2021 |
| Dell          | Latitude 5520               | [370dda1922](https://linux-hardware.org/?probe=370dda1922) | Oct 28, 2021 |
| HP            | Pavilion dv7                | [d4b81612a8](https://linux-hardware.org/?probe=d4b81612a8) | Oct 28, 2021 |
| Dell          | Latitude 5520               | [2a08ef4aeb](https://linux-hardware.org/?probe=2a08ef4aeb) | Oct 27, 2021 |
| Lenovo        | ThinkPad E595 20NF0002BM    | [52ba950565](https://linux-hardware.org/?probe=52ba950565) | Oct 25, 2021 |
| HP            | EliteBook 840 G1            | [cecd552e89](https://linux-hardware.org/?probe=cecd552e89) | Oct 25, 2021 |
| Lenovo        | G50-30 80G0                 | [4e11b29d08](https://linux-hardware.org/?probe=4e11b29d08) | Oct 23, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [16268db25b](https://linux-hardware.org/?probe=16268db25b) | Oct 22, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | [963b34aa8b](https://linux-hardware.org/?probe=963b34aa8b) | Oct 22, 2021 |
| Toshiba       | Satellite L50-A-1D9         | [cd55b73689](https://linux-hardware.org/?probe=cd55b73689) | Oct 20, 2021 |
| HP            | Notebook                    | [ff690977bf](https://linux-hardware.org/?probe=ff690977bf) | Oct 19, 2021 |
| Dell          | Inspiron 3537               | [255aca010b](https://linux-hardware.org/?probe=255aca010b) | Oct 18, 2021 |
| Dell          | Precision M4800             | [87034ed159](https://linux-hardware.org/?probe=87034ed159) | Oct 16, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [7ba2477e56](https://linux-hardware.org/?probe=7ba2477e56) | Oct 13, 2021 |
| HP            | Laptop 17-ca1xxx            | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| ARIMA         | W651UI                      | [287379af9f](https://linux-hardware.org/?probe=287379af9f) | Oct 10, 2021 |
| MSI           | Alpha 17 A4DEK              | [eca8493d4b](https://linux-hardware.org/?probe=eca8493d4b) | Oct 07, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [415ce3638d](https://linux-hardware.org/?probe=415ce3638d) | Oct 06, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [74e6b1bc07](https://linux-hardware.org/?probe=74e6b1bc07) | Oct 06, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [9e35238cd2](https://linux-hardware.org/?probe=9e35238cd2) | Oct 05, 2021 |
| HP            | 255 G6 Notebook PC          | [6ae274321c](https://linux-hardware.org/?probe=6ae274321c) | Oct 03, 2021 |
| Lenovo        | ThinkPad T420 4236A22       | [e92d8556e9](https://linux-hardware.org/?probe=e92d8556e9) | Sep 29, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | [c5a7069c64](https://linux-hardware.org/?probe=c5a7069c64) | Sep 26, 2021 |
| Apple         | MacBookAir3,1               | [2b14368aed](https://linux-hardware.org/?probe=2b14368aed) | Sep 25, 2021 |
| HP            | Pavilion g6                 | [43a34f4589](https://linux-hardware.org/?probe=43a34f4589) | Sep 23, 2021 |
| Sony          | VGN-FW510F                  | [8f2f403347](https://linux-hardware.org/?probe=8f2f403347) | Sep 19, 2021 |
| Fujitsu Si... | AMILO M7440D                | [e23f21b9b4](https://linux-hardware.org/?probe=e23f21b9b4) | Sep 19, 2021 |
| Fujitsu Si... | AMILO M7440D                | [bce3e66350](https://linux-hardware.org/?probe=bce3e66350) | Sep 19, 2021 |
| Apple         | MacBookPro8,2               | [64a2bd261a](https://linux-hardware.org/?probe=64a2bd261a) | Sep 12, 2021 |
| Acer          | Aspire 5020                 | [54ddef7aa7](https://linux-hardware.org/?probe=54ddef7aa7) | Sep 11, 2021 |
| Acer          | Aspire 5020                 | [8c00427976](https://linux-hardware.org/?probe=8c00427976) | Sep 11, 2021 |
| Acer          | Aspire 3610                 | [fc6953a3f9](https://linux-hardware.org/?probe=fc6953a3f9) | Sep 10, 2021 |
| Acer          | Aspire 3610                 | [3ab0387498](https://linux-hardware.org/?probe=3ab0387498) | Sep 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0bfdb154b9](https://linux-hardware.org/?probe=0bfdb154b9) | Sep 08, 2021 |
| HP            | 255 G3                      | [bd1a8b58da](https://linux-hardware.org/?probe=bd1a8b58da) | Sep 03, 2021 |
| HP            | 255 G3                      | [b5f1c73339](https://linux-hardware.org/?probe=b5f1c73339) | Sep 03, 2021 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [d3f86f70ae](https://linux-hardware.org/?probe=d3f86f70ae) | Sep 03, 2021 |
| HP            | Presario CQ58               | [313af01ef8](https://linux-hardware.org/?probe=313af01ef8) | Sep 01, 2021 |
| Dell          | Inspiron 15 5510            | [cbc1dd6499](https://linux-hardware.org/?probe=cbc1dd6499) | Aug 27, 2021 |
| Sony          | SVT1122B2EW                 | [cb166ff02b](https://linux-hardware.org/?probe=cb166ff02b) | Aug 24, 2021 |
| Sony          | SVT1122B2EW                 | [7ef0a9c54a](https://linux-hardware.org/?probe=7ef0a9c54a) | Aug 21, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [80dfc52333](https://linux-hardware.org/?probe=80dfc52333) | Aug 21, 2021 |
| HP            | 255 G7 Notebook PC          | [1639c4e352](https://linux-hardware.org/?probe=1639c4e352) | Aug 20, 2021 |
| HP            | 255 G7 Notebook PC          | [a7c72d0be5](https://linux-hardware.org/?probe=a7c72d0be5) | Aug 20, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [301da897a6](https://linux-hardware.org/?probe=301da897a6) | Aug 19, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e1467bfa3e](https://linux-hardware.org/?probe=e1467bfa3e) | Aug 18, 2021 |
| HP            | Laptop 14s-fq0xxx           | [0cdcd7cac9](https://linux-hardware.org/?probe=0cdcd7cac9) | Aug 17, 2021 |
| Acer          | Aspire A517-51G             | [6387ddee62](https://linux-hardware.org/?probe=6387ddee62) | Aug 13, 2021 |
| Dell          | Latitude 7420               | [67165b9d66](https://linux-hardware.org/?probe=67165b9d66) | Aug 12, 2021 |
| HP            | Pavilion g6                 | [d4523e209b](https://linux-hardware.org/?probe=d4523e209b) | Aug 09, 2021 |
| HP            | Pavilion g6                 | [4116e486f5](https://linux-hardware.org/?probe=4116e486f5) | Aug 07, 2021 |
| Samsung       | R780                        | [f59b3d2a3f](https://linux-hardware.org/?probe=f59b3d2a3f) | Aug 05, 2021 |
| Dell          | Latitude 5410               | [5f861ac987](https://linux-hardware.org/?probe=5f861ac987) | Aug 04, 2021 |
| Dell          | Latitude 5410               | [aed58623e2](https://linux-hardware.org/?probe=aed58623e2) | Aug 04, 2021 |
| HP            | EliteBook 8460p             | [7243281e28](https://linux-hardware.org/?probe=7243281e28) | Aug 01, 2021 |
| Dell          | Latitude 7390               | [ee6d9cb25f](https://linux-hardware.org/?probe=ee6d9cb25f) | Aug 01, 2021 |
| Dell          | Vostro 5502                 | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| HP            | 255 G7 Notebook PC          | [49e2ef564c](https://linux-hardware.org/?probe=49e2ef564c) | Jul 31, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [4c6cb12482](https://linux-hardware.org/?probe=4c6cb12482) | Jul 30, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [1cd2de69ff](https://linux-hardware.org/?probe=1cd2de69ff) | Jul 29, 2021 |
| Toshiba       | Satellite C850D-119         | [bb3f1b4afa](https://linux-hardware.org/?probe=bb3f1b4afa) | Jul 29, 2021 |
| Dell          | Latitude E7470              | [9d580f1809](https://linux-hardware.org/?probe=9d580f1809) | Jul 28, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e2877b1692](https://linux-hardware.org/?probe=e2877b1692) | Jul 27, 2021 |
| Dell          | Studio 1555                 | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Acer          | Aspire 5735                 | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| HP            | 250 G3                      | [b1a0952727](https://linux-hardware.org/?probe=b1a0952727) | Jul 19, 2021 |
| HP            | ProBook 470 G0              | [0ac8121d51](https://linux-hardware.org/?probe=0ac8121d51) | Jul 14, 2021 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [4ffde7a90a](https://linux-hardware.org/?probe=4ffde7a90a) | Jul 13, 2021 |
| PC Special... | N85_N87,HJ,HJ1,HK1          | [515b7e11d1](https://linux-hardware.org/?probe=515b7e11d1) | Jul 11, 2021 |
| HP            | Laptop 15s-eq1xxx           | [89a5013659](https://linux-hardware.org/?probe=89a5013659) | Jul 09, 2021 |
| Lenovo        | QIQY2                       | [7f8f82feb5](https://linux-hardware.org/?probe=7f8f82feb5) | Jul 07, 2021 |
| Dell          | Latitude D531               | [5a671e0dc0](https://linux-hardware.org/?probe=5a671e0dc0) | Jul 06, 2021 |
| Dell          | Latitude D531               | [bc3e80d306](https://linux-hardware.org/?probe=bc3e80d306) | Jul 06, 2021 |
| ASUSTek       | X540UA                      | [b9169c0ae3](https://linux-hardware.org/?probe=b9169c0ae3) | Jul 05, 2021 |
| HP            | Laptop 15-bs1xx             | [f57bd1d1d8](https://linux-hardware.org/?probe=f57bd1d1d8) | Jul 04, 2021 |
| Chuwi         | GemiBook Pro                | [03f12de5a1](https://linux-hardware.org/?probe=03f12de5a1) | Jun 17, 2021 |
| HP            | 255 G7 Notebook PC          | [22c9d6c7de](https://linux-hardware.org/?probe=22c9d6c7de) | Jun 16, 2021 |
| Dell          | Latitude 7400               | [c58ebb3bf8](https://linux-hardware.org/?probe=c58ebb3bf8) | Jun 15, 2021 |
| HP            | Notebook                    | [611efdde0d](https://linux-hardware.org/?probe=611efdde0d) | Jun 15, 2021 |
| HP            | Pavilion Notebook           | [8d612e77f2](https://linux-hardware.org/?probe=8d612e77f2) | Jun 14, 2021 |
| Chuwi         | GemiBook Pro                | [7a4b730903](https://linux-hardware.org/?probe=7a4b730903) | Jun 13, 2021 |
| Dell          | Vostro 3500                 | [128de02660](https://linux-hardware.org/?probe=128de02660) | Jun 12, 2021 |
| Dell          | Vostro 3500                 | [e8a90de6cd](https://linux-hardware.org/?probe=e8a90de6cd) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [676f8cfa11](https://linux-hardware.org/?probe=676f8cfa11) | Jun 12, 2021 |
| Sony          | VGN-FW510F                  | [88362a4659](https://linux-hardware.org/?probe=88362a4659) | Jun 10, 2021 |
| Sony          | VGN-FW510F                  | [d87f3ea107](https://linux-hardware.org/?probe=d87f3ea107) | Jun 10, 2021 |
| HP            | Compaq 6910p                | [5b4d256824](https://linux-hardware.org/?probe=5b4d256824) | Jun 10, 2021 |
| Dell          | Inspiron 5559               | [356b7fd3c6](https://linux-hardware.org/?probe=356b7fd3c6) | Jun 09, 2021 |
| ASUSTek       | N550JV                      | [7973dc9123](https://linux-hardware.org/?probe=7973dc9123) | Jun 08, 2021 |
| PLAISIO CO... | TURBO-X                     | [44f5d57c9d](https://linux-hardware.org/?probe=44f5d57c9d) | Jun 06, 2021 |
| PLAISIO CO... | TURBO-X                     | [47473943ab](https://linux-hardware.org/?probe=47473943ab) | Jun 06, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [ef4e2ca66f](https://linux-hardware.org/?probe=ef4e2ca66f) | Jun 03, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [2ff583b918](https://linux-hardware.org/?probe=2ff583b918) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [b7f26cced7](https://linux-hardware.org/?probe=b7f26cced7) | Jun 01, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [36f36a1183](https://linux-hardware.org/?probe=36f36a1183) | Jun 01, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [bd16a61719](https://linux-hardware.org/?probe=bd16a61719) | May 31, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [da0e32387a](https://linux-hardware.org/?probe=da0e32387a) | May 31, 2021 |
| Fujitsu Si... | LIFEBOOK S7220              | [b9c73baf1d](https://linux-hardware.org/?probe=b9c73baf1d) | May 25, 2021 |
| Lenovo        | G500 20236                  | [91cf490677](https://linux-hardware.org/?probe=91cf490677) | May 24, 2021 |
| Toshiba       | Satellite A200              | [455915e23a](https://linux-hardware.org/?probe=455915e23a) | May 21, 2021 |
| HP            | G62                         | [72f8505e51](https://linux-hardware.org/?probe=72f8505e51) | May 20, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| HP            | Pavilion Laptop 13-an1xx... | [ead418c0a3](https://linux-hardware.org/?probe=ead418c0a3) | May 17, 2021 |
| HP            | Pavilion Laptop 13-an1xx... | [8312f6899d](https://linux-hardware.org/?probe=8312f6899d) | May 17, 2021 |
| Dell          | Precision 3551              | [a080388baa](https://linux-hardware.org/?probe=a080388baa) | May 16, 2021 |
| Dell          | Precision 3551              | [f9f9852b96](https://linux-hardware.org/?probe=f9f9852b96) | May 16, 2021 |
| HP            | Unknown                     | [554d7cd528](https://linux-hardware.org/?probe=554d7cd528) | May 14, 2021 |
| Dell          | Inspiron 3537               | [3038e4027b](https://linux-hardware.org/?probe=3038e4027b) | May 14, 2021 |
| HP            | Compaq 6735s                | [b3d6b7770a](https://linux-hardware.org/?probe=b3d6b7770a) | May 13, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [e6848fb30e](https://linux-hardware.org/?probe=e6848fb30e) | May 13, 2021 |
| Notebook      | W65_67SF                    | [342074c2e1](https://linux-hardware.org/?probe=342074c2e1) | May 13, 2021 |
| Notebook      | W65_67SF                    | [54aedd8090](https://linux-hardware.org/?probe=54aedd8090) | May 13, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [643481b28f](https://linux-hardware.org/?probe=643481b28f) | May 10, 2021 |
| MSI           | GF75 Thin 10SCSR            | [d88c558cda](https://linux-hardware.org/?probe=d88c558cda) | May 09, 2021 |
| Notebook      | W65_67SF                    | [89628bc0a5](https://linux-hardware.org/?probe=89628bc0a5) | May 07, 2021 |
| Sony          | SVE1513R1EB                 | [e87dd3a1c3](https://linux-hardware.org/?probe=e87dd3a1c3) | May 07, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [0b34a1f92d](https://linux-hardware.org/?probe=0b34a1f92d) | May 04, 2021 |
| Lenovo        | B590 20208                  | [f483fd5a3b](https://linux-hardware.org/?probe=f483fd5a3b) | May 04, 2021 |
| HP            | Compaq 6735s                | [f50dd52975](https://linux-hardware.org/?probe=f50dd52975) | May 03, 2021 |
| Unknown       | Unknown                     | [6f9d6686f3](https://linux-hardware.org/?probe=6f9d6686f3) | May 03, 2021 |
| Apple         | MacBookPro8,1               | [ad00f41e81](https://linux-hardware.org/?probe=ad00f41e81) | May 02, 2021 |
| Toshiba       | NB100                       | [9540e0d0d5](https://linux-hardware.org/?probe=9540e0d0d5) | May 02, 2021 |
| HP            | G62                         | [327a8383cf](https://linux-hardware.org/?probe=327a8383cf) | Apr 30, 2021 |
| Acer          | AO756                       | [f398615a01](https://linux-hardware.org/?probe=f398615a01) | Apr 22, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [eb3e5cf436](https://linux-hardware.org/?probe=eb3e5cf436) | Apr 22, 2021 |
| Lenovo        | ThinkPad T430 2349CV2       | [98063e03b9](https://linux-hardware.org/?probe=98063e03b9) | Apr 21, 2021 |
| Dell          | G3 3590                     | [5fe47837ac](https://linux-hardware.org/?probe=5fe47837ac) | Apr 19, 2021 |
| Toshiba       | Satellite C850D-119         | [7c519e9719](https://linux-hardware.org/?probe=7c519e9719) | Apr 17, 2021 |
| Google        | Coral                       | [d0fef96a1b](https://linux-hardware.org/?probe=d0fef96a1b) | Apr 15, 2021 |
| Toshiba       | Satellite C55-A-1F5         | [d7b4bf2642](https://linux-hardware.org/?probe=d7b4bf2642) | Apr 15, 2021 |
| Toshiba       | Satellite C55-A-1F5         | [aa32e3693a](https://linux-hardware.org/?probe=aa32e3693a) | Apr 14, 2021 |
| Acer          | Predator G3-571             | [2db50fb736](https://linux-hardware.org/?probe=2db50fb736) | Apr 12, 2021 |
| HP            | 255 G1                      | [0244337bdd](https://linux-hardware.org/?probe=0244337bdd) | Apr 12, 2021 |
| HP            | 255 G1                      | [df0d528c9c](https://linux-hardware.org/?probe=df0d528c9c) | Apr 12, 2021 |
| HP            | 255 G8 Notebook PC          | [fd8afa6f02](https://linux-hardware.org/?probe=fd8afa6f02) | Apr 11, 2021 |
| HP            | 255 G8 Notebook PC          | [166de8c643](https://linux-hardware.org/?probe=166de8c643) | Apr 11, 2021 |
| Hampoo        | Cherry Trail CR V200        | [fcbaa285ef](https://linux-hardware.org/?probe=fcbaa285ef) | Apr 07, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [f1c3f62a55](https://linux-hardware.org/?probe=f1c3f62a55) | Apr 04, 2021 |
| MSI           | GF75 Thin 10SCSR            | [4c5b57df0f](https://linux-hardware.org/?probe=4c5b57df0f) | Apr 03, 2021 |
| Acer          | Aspire A315-51              | [a6ad1251de](https://linux-hardware.org/?probe=a6ad1251de) | Mar 30, 2021 |
| Toshiba       | Satellite L500              | [d11d1f9916](https://linux-hardware.org/?probe=d11d1f9916) | Mar 28, 2021 |
| Quest         | GTN1408                     | [e0a15c69a8](https://linux-hardware.org/?probe=e0a15c69a8) | Mar 25, 2021 |
| ASUSTek       | X555QG                      | [9e2fba943d](https://linux-hardware.org/?probe=9e2fba943d) | Mar 25, 2021 |
| Dell          | Latitude D530               | [bd67bc09cd](https://linux-hardware.org/?probe=bd67bc09cd) | Mar 22, 2021 |
| Acer          | Aspire 5750G                | [82fb28dfec](https://linux-hardware.org/?probe=82fb28dfec) | Mar 19, 2021 |
| ASUSTek       | X556UQK                     | [67d33fc829](https://linux-hardware.org/?probe=67d33fc829) | Mar 19, 2021 |
| ASUSTek       | N552VX                      | [79120776d5](https://linux-hardware.org/?probe=79120776d5) | Mar 14, 2021 |
| ASUSTek       | N552VX                      | [2bb101d8ca](https://linux-hardware.org/?probe=2bb101d8ca) | Mar 14, 2021 |
| HP            | G62                         | [f586fad981](https://linux-hardware.org/?probe=f586fad981) | Mar 14, 2021 |
| Teclast       | F15                         | [2a9e97f18c](https://linux-hardware.org/?probe=2a9e97f18c) | Mar 10, 2021 |
| HP            | Notebook                    | [26fdd1f108](https://linux-hardware.org/?probe=26fdd1f108) | Mar 09, 2021 |
| Dell          | Latitude E7250              | [551399bf55](https://linux-hardware.org/?probe=551399bf55) | Mar 08, 2021 |
| Acer          | Aspire E5-771G              | [693347465d](https://linux-hardware.org/?probe=693347465d) | Mar 06, 2021 |
| Info Quest... | GTN1408                     | [571eedb776](https://linux-hardware.org/?probe=571eedb776) | Mar 03, 2021 |
| Toshiba       | NB100                       | [7876cca0bb](https://linux-hardware.org/?probe=7876cca0bb) | Mar 03, 2021 |
| Dell          | Latitude E6400              | [ebe53e8b99](https://linux-hardware.org/?probe=ebe53e8b99) | Feb 28, 2021 |
| Dell          | Inspiron 5567               | [e2ede83088](https://linux-hardware.org/?probe=e2ede83088) | Feb 27, 2021 |
| Dell          | Inspiron 5567               | [951acd6af9](https://linux-hardware.org/?probe=951acd6af9) | Feb 27, 2021 |
| HP            | ProBook 430 G7              | [b4b70424b9](https://linux-hardware.org/?probe=b4b70424b9) | Feb 27, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | [1ecf28a1c8](https://linux-hardware.org/?probe=1ecf28a1c8) | Feb 27, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | [cada48fb79](https://linux-hardware.org/?probe=cada48fb79) | Feb 27, 2021 |
| ASUSTek       | UX305CA                     | [65b536ca2f](https://linux-hardware.org/?probe=65b536ca2f) | Feb 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c501aa1f72](https://linux-hardware.org/?probe=c501aa1f72) | Feb 26, 2021 |
| HP            | Pavilion dv6                | [ffde1aad10](https://linux-hardware.org/?probe=ffde1aad10) | Feb 25, 2021 |
| Dell          | Latitude E6400              | [256426a815](https://linux-hardware.org/?probe=256426a815) | Feb 22, 2021 |
| HP            | Pavilion Notebook           | [e6ea03de75](https://linux-hardware.org/?probe=e6ea03de75) | Feb 21, 2021 |
| HP            | Pavilion AB7                | [410cf90e15](https://linux-hardware.org/?probe=410cf90e15) | Feb 20, 2021 |
| Fujitsu       | LIFEBOOK NH570              | [9b2fc1e55f](https://linux-hardware.org/?probe=9b2fc1e55f) | Feb 19, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | [6e91e6e551](https://linux-hardware.org/?probe=6e91e6e551) | Feb 18, 2021 |
| HP            | Laptop 15-db0xxx            | [9e831f773a](https://linux-hardware.org/?probe=9e831f773a) | Feb 17, 2021 |
| Dell          | Studio 1557                 | [bf361a7ed3](https://linux-hardware.org/?probe=bf361a7ed3) | Feb 16, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [38a0ac2efa](https://linux-hardware.org/?probe=38a0ac2efa) | Feb 16, 2021 |
| Dell          | Precision M6400             | [2bd1a24330](https://linux-hardware.org/?probe=2bd1a24330) | Feb 14, 2021 |
| HP            | ProBook 450 G5              | [3e6fa8f362](https://linux-hardware.org/?probe=3e6fa8f362) | Feb 13, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | [2b5732689b](https://linux-hardware.org/?probe=2b5732689b) | Feb 13, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | [0005b66219](https://linux-hardware.org/?probe=0005b66219) | Feb 13, 2021 |
| Teclast       | F15                         | [1c7d49b0b0](https://linux-hardware.org/?probe=1c7d49b0b0) | Feb 13, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [654141e59d](https://linux-hardware.org/?probe=654141e59d) | Feb 13, 2021 |
| Fujitsu Si... | AMILO Li 1818               | [68c7aa1fa1](https://linux-hardware.org/?probe=68c7aa1fa1) | Feb 09, 2021 |
| Lenovo        | G510 20238                  | [0022cd41e5](https://linux-hardware.org/?probe=0022cd41e5) | Feb 06, 2021 |
| Lenovo        | Y50-70 20378                | [a95bc37d1f](https://linux-hardware.org/?probe=a95bc37d1f) | Feb 03, 2021 |
| HP            | G62                         | [273bf04457](https://linux-hardware.org/?probe=273bf04457) | Feb 03, 2021 |
| HP            | G62                         | [a74ecdb45c](https://linux-hardware.org/?probe=a74ecdb45c) | Feb 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4f64a771ff](https://linux-hardware.org/?probe=4f64a771ff) | Feb 01, 2021 |
| HP            | Pavilion Sleekbook 15       | [bf72f555cb](https://linux-hardware.org/?probe=bf72f555cb) | Jan 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4d8f4f66c7](https://linux-hardware.org/?probe=4d8f4f66c7) | Jan 31, 2021 |
| Acer          | Aspire A517-51G             | [7b7f7244e6](https://linux-hardware.org/?probe=7b7f7244e6) | Jan 28, 2021 |
| Lenovo        | G510 20238                  | [c53a37fb5a](https://linux-hardware.org/?probe=c53a37fb5a) | Jan 28, 2021 |
| HP            | Unknown                     | [437cd35d62](https://linux-hardware.org/?probe=437cd35d62) | Jan 28, 2021 |
| IBM           | ThinkPad T41 2373271        | [71daf2c5b4](https://linux-hardware.org/?probe=71daf2c5b4) | Jan 26, 2021 |
| Fujitsu       | AMILO Pi 3560               | [a54f523eae](https://linux-hardware.org/?probe=a54f523eae) | Jan 26, 2021 |
| HP            | 255 G7 Notebook PC          | [54bfedf54f](https://linux-hardware.org/?probe=54bfedf54f) | Jan 24, 2021 |
| Lenovo        | G40-30 80FY                 | [2ade08670a](https://linux-hardware.org/?probe=2ade08670a) | Jan 22, 2021 |
| HP            | Unknown                     | [db1b52d959](https://linux-hardware.org/?probe=db1b52d959) | Jan 19, 2021 |
| Toshiba       | Satellite L50-B             | [6e7fe8b488](https://linux-hardware.org/?probe=6e7fe8b488) | Jan 18, 2021 |
| Toshiba       | Satellite L50-B             | [df23913572](https://linux-hardware.org/?probe=df23913572) | Jan 18, 2021 |
| HP            | 550                         | [384b3f65ed](https://linux-hardware.org/?probe=384b3f65ed) | Jan 18, 2021 |
| Acer          | Aspire 1410                 | [c7045484b1](https://linux-hardware.org/?probe=c7045484b1) | Jan 16, 2021 |
| Sony          | VPCS11X9E                   | [279fb61afa](https://linux-hardware.org/?probe=279fb61afa) | Jan 16, 2021 |
| Acer          | Aspire E1-571G              | [051b3d5b1b](https://linux-hardware.org/?probe=051b3d5b1b) | Jan 16, 2021 |
| Lenovo        | IdeaPad 320-17IKB 81BJ      | [a137e1b57f](https://linux-hardware.org/?probe=a137e1b57f) | Jan 11, 2021 |
| Medion        | P6612                       | [5e83afdaae](https://linux-hardware.org/?probe=5e83afdaae) | Jan 11, 2021 |
| Dell          | G3 3579                     | [d48d0d6f85](https://linux-hardware.org/?probe=d48d0d6f85) | Jan 11, 2021 |
| HP            | 550                         | [10da4607b5](https://linux-hardware.org/?probe=10da4607b5) | Jan 11, 2021 |
| Lenovo        | ThinkPad T430 2347AG4       | [01c5b6209d](https://linux-hardware.org/?probe=01c5b6209d) | Jan 11, 2021 |
| Dell          | Precision 3551              | [1f3d433e7b](https://linux-hardware.org/?probe=1f3d433e7b) | Jan 07, 2021 |
| Dell          | Precision 3551              | [b9869afb9a](https://linux-hardware.org/?probe=b9869afb9a) | Jan 07, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [2040f17b4e](https://linux-hardware.org/?probe=2040f17b4e) | Jan 07, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [7758717ed0](https://linux-hardware.org/?probe=7758717ed0) | Jan 07, 2021 |
| Unknown       | Unknown                     | [394c90d235](https://linux-hardware.org/?probe=394c90d235) | Jan 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [7fa2f92090](https://linux-hardware.org/?probe=7fa2f92090) | Jan 05, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [1bf71bd97d](https://linux-hardware.org/?probe=1bf71bd97d) | Jan 04, 2021 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [010507185c](https://linux-hardware.org/?probe=010507185c) | Jan 03, 2021 |
| HP            | G62                         | [26fedb2989](https://linux-hardware.org/?probe=26fedb2989) | Jan 03, 2021 |
| Sony          | VGN-CR11S_W                 | [e7b02a15dc](https://linux-hardware.org/?probe=e7b02a15dc) | Dec 30, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | [33e1b7b962](https://linux-hardware.org/?probe=33e1b7b962) | Dec 28, 2020 |
| Fujitsu Si... | AMILO Pi 2530               | [7463092751](https://linux-hardware.org/?probe=7463092751) | Dec 28, 2020 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [cb411462ef](https://linux-hardware.org/?probe=cb411462ef) | Dec 28, 2020 |
| Acer          | Aspire 9410                 | [502b2847a6](https://linux-hardware.org/?probe=502b2847a6) | Dec 28, 2020 |
| Acer          | Aspire 9410                 | [29cadd906c](https://linux-hardware.org/?probe=29cadd906c) | Dec 28, 2020 |
| HP            | Pavilion Notebook           | [4301611dfb](https://linux-hardware.org/?probe=4301611dfb) | Dec 28, 2020 |
| Dell          | Inspiron 5567               | [4bed00686e](https://linux-hardware.org/?probe=4bed00686e) | Dec 27, 2020 |
| Lenovo        | 3000 G530 444624G           | [34e6d98329](https://linux-hardware.org/?probe=34e6d98329) | Dec 27, 2020 |
| Insyde        | CherryTrail                 | [3d9eb0babd](https://linux-hardware.org/?probe=3d9eb0babd) | Dec 26, 2020 |
| HP            | Pavilion dv7                | [cc13d41ddd](https://linux-hardware.org/?probe=cc13d41ddd) | Dec 25, 2020 |
| Dell          | XPS 15 7590                 | [2974690eda](https://linux-hardware.org/?probe=2974690eda) | Dec 25, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [752fb8d0c7](https://linux-hardware.org/?probe=752fb8d0c7) | Dec 25, 2020 |
| HP            | Laptop 15-db0xxx            | [08f4092908](https://linux-hardware.org/?probe=08f4092908) | Dec 21, 2020 |
| Lenovo        | ThinkPad X200 7458Y28       | [508111c39d](https://linux-hardware.org/?probe=508111c39d) | Dec 20, 2020 |
| HP            | Laptop 15-db1xxx            | [c7807b04ff](https://linux-hardware.org/?probe=c7807b04ff) | Dec 20, 2020 |
| Lenovo        | IdeaPad S210 Touch 20257    | [faacb1a39b](https://linux-hardware.org/?probe=faacb1a39b) | Dec 19, 2020 |
| Lenovo        | ThinkPad X220 4291W3B       | [0cb7ed54d1](https://linux-hardware.org/?probe=0cb7ed54d1) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y560                | [c5c8b0a320](https://linux-hardware.org/?probe=c5c8b0a320) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y560                | [1a68fc4e19](https://linux-hardware.org/?probe=1a68fc4e19) | Dec 19, 2020 |
| Toshiba       | NB100                       | [01daa00e87](https://linux-hardware.org/?probe=01daa00e87) | Dec 19, 2020 |
| Dell          | Latitude D520               | [7f5d3e9a40](https://linux-hardware.org/?probe=7f5d3e9a40) | Dec 19, 2020 |
| Lenovo        | 3000 G530 444624G           | [fb187878c5](https://linux-hardware.org/?probe=fb187878c5) | Dec 16, 2020 |
| ASUSTek       | X550CC                      | [d8723f48ef](https://linux-hardware.org/?probe=d8723f48ef) | Dec 15, 2020 |
| Sony          | VPCCB2S1E                   | [dadaeb0257](https://linux-hardware.org/?probe=dadaeb0257) | Dec 14, 2020 |
| Sony          | VPCCB2S1E                   | [b08942a95c](https://linux-hardware.org/?probe=b08942a95c) | Dec 14, 2020 |
| Lenovo        | G50-80 80L0                 | [951a5a280f](https://linux-hardware.org/?probe=951a5a280f) | Dec 11, 2020 |
| Sony          | VGN-CR11S_W                 | [9f07e6181c](https://linux-hardware.org/?probe=9f07e6181c) | Dec 10, 2020 |
| HP            | OMEN by Laptop              | [ae88c5398f](https://linux-hardware.org/?probe=ae88c5398f) | Dec 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b7becb585e](https://linux-hardware.org/?probe=b7becb585e) | Dec 08, 2020 |
| Intel         | CAPELL VALLEY CRB           | [59d2069d40](https://linux-hardware.org/?probe=59d2069d40) | Dec 07, 2020 |
| Intel         | CAPELL VALLEY CRB           | [ce350750e3](https://linux-hardware.org/?probe=ce350750e3) | Dec 05, 2020 |
| Toshiba       | Satellite C850D-119         | [4a0f2ef22e](https://linux-hardware.org/?probe=4a0f2ef22e) | Dec 05, 2020 |
| HP            | Pavilion dv7                | [ea3cf2d030](https://linux-hardware.org/?probe=ea3cf2d030) | Dec 04, 2020 |
| Lenovo        | G70-35 80Q5                 | [455f011c08](https://linux-hardware.org/?probe=455f011c08) | Dec 03, 2020 |
| ASUSTek       | X556UQK                     | [529e0c244d](https://linux-hardware.org/?probe=529e0c244d) | Dec 02, 2020 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [09b180815e](https://linux-hardware.org/?probe=09b180815e) | Dec 01, 2020 |
| Fujitsu       | CELSIUS H710                | [03fea3325c](https://linux-hardware.org/?probe=03fea3325c) | Dec 01, 2020 |
| Lenovo        | G70-35 80Q5                 | [23ee81bd5e](https://linux-hardware.org/?probe=23ee81bd5e) | Dec 01, 2020 |
| HP            | Pavilion Notebook           | [193e7f8bf4](https://linux-hardware.org/?probe=193e7f8bf4) | Dec 01, 2020 |
| Toshiba       | NB100                       | [73e92718a9](https://linux-hardware.org/?probe=73e92718a9) | Dec 01, 2020 |
| HP            | Unknown                     | [6ecc666f9f](https://linux-hardware.org/?probe=6ecc666f9f) | Dec 01, 2020 |
| Sony          | VPCW12J1E                   | [7f54f3a6f0](https://linux-hardware.org/?probe=7f54f3a6f0) | Dec 01, 2020 |
| Fujitsu       | CELSIUS H710                | [1214e804ff](https://linux-hardware.org/?probe=1214e804ff) | Dec 01, 2020 |
| Acer          | Predator G5-793             | [ae170a3127](https://linux-hardware.org/?probe=ae170a3127) | Nov 30, 2020 |
| Acer          | Aspire 5738                 | [c34c324fc5](https://linux-hardware.org/?probe=c34c324fc5) | Nov 28, 2020 |
| HP            | EliteBook 850 G5            | [e261ebbf0e](https://linux-hardware.org/?probe=e261ebbf0e) | Nov 26, 2020 |
| Toshiba       | Satellite P500              | [25e5577463](https://linux-hardware.org/?probe=25e5577463) | Nov 24, 2020 |
| Dell          | Inspiron 5570               | [2074f71e04](https://linux-hardware.org/?probe=2074f71e04) | Nov 24, 2020 |
| Dell          | Inspiron 3537               | [0bc23c46e1](https://linux-hardware.org/?probe=0bc23c46e1) | Nov 23, 2020 |
| Acer          | Aspire 9500                 | [14c016a2f9](https://linux-hardware.org/?probe=14c016a2f9) | Nov 22, 2020 |
| HP            | EliteBook 840 G3            | [4dd618cb59](https://linux-hardware.org/?probe=4dd618cb59) | Nov 21, 2020 |
| HP            | EliteBook 840 G3            | [2543664b54](https://linux-hardware.org/?probe=2543664b54) | Nov 21, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [00c9bbbec5](https://linux-hardware.org/?probe=00c9bbbec5) | Nov 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [baae1bd1ef](https://linux-hardware.org/?probe=baae1bd1ef) | Nov 20, 2020 |
| HP            | 14                          | [99583d854a](https://linux-hardware.org/?probe=99583d854a) | Nov 20, 2020 |
| Dell          | Inspiron 3542               | [6647cfca50](https://linux-hardware.org/?probe=6647cfca50) | Nov 18, 2020 |
| HP            | Pavilion g6                 | [4a521aad50](https://linux-hardware.org/?probe=4a521aad50) | Nov 16, 2020 |
| Clevo         | W55xEU                      | [932e7d8f27](https://linux-hardware.org/?probe=932e7d8f27) | Nov 16, 2020 |
| HP            | Laptop 17-ca1xxx            | [43e0f99b97](https://linux-hardware.org/?probe=43e0f99b97) | Nov 14, 2020 |
| HUAWEI        | KLVL-WXX9                   | [bd2dcac2ac](https://linux-hardware.org/?probe=bd2dcac2ac) | Nov 12, 2020 |
| Fujitsu Si... | AMILO Li1705                | [3233bbc0ec](https://linux-hardware.org/?probe=3233bbc0ec) | Nov 12, 2020 |
| MSI           | GE70 2OC\2OE                | [ba1376cdb9](https://linux-hardware.org/?probe=ba1376cdb9) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | [0c0bf4e794](https://linux-hardware.org/?probe=0c0bf4e794) | Nov 11, 2020 |
| Dell          | Inspiron 3593               | [005da6030a](https://linux-hardware.org/?probe=005da6030a) | Nov 11, 2020 |
| ASUSTek       | X540LJ                      | [3a7e7932f2](https://linux-hardware.org/?probe=3a7e7932f2) | Nov 10, 2020 |
| Dell          | Latitude 7400               | [95aa8c5f82](https://linux-hardware.org/?probe=95aa8c5f82) | Nov 04, 2020 |
| Dell          | Inspiron 3542               | [b30631ff4c](https://linux-hardware.org/?probe=b30631ff4c) | Nov 03, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [5a78c67deb](https://linux-hardware.org/?probe=5a78c67deb) | Oct 30, 2020 |
| HP            | 15                          | [8ebe037b8f](https://linux-hardware.org/?probe=8ebe037b8f) | Oct 29, 2020 |
| Toshiba       | Satellite C850D-119         | [493e216eea](https://linux-hardware.org/?probe=493e216eea) | Oct 25, 2020 |
| HP            | 255 G1                      | [bfd456834c](https://linux-hardware.org/?probe=bfd456834c) | Oct 24, 2020 |
| Toshiba       | Satellite P200              | [84d2d0d8cf](https://linux-hardware.org/?probe=84d2d0d8cf) | Oct 21, 2020 |
| Toshiba       | Satellite P200              | [932b71224c](https://linux-hardware.org/?probe=932b71224c) | Oct 21, 2020 |
| HP            | Pavilion x2 Detachable      | [b7f2a6ef39](https://linux-hardware.org/?probe=b7f2a6ef39) | Oct 21, 2020 |
| Dell          | System XPS L502X            | [dc6eea4b63](https://linux-hardware.org/?probe=dc6eea4b63) | Oct 17, 2020 |
| Clevo         | M550SE/M660SE VT6363A       | [01a8ac7cd9](https://linux-hardware.org/?probe=01a8ac7cd9) | Oct 14, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4974ae8ad2](https://linux-hardware.org/?probe=4974ae8ad2) | Oct 13, 2020 |
| Sony          | VPCCB2S1E                   | [8a80ad4971](https://linux-hardware.org/?probe=8a80ad4971) | Oct 13, 2020 |
| Clevo         | M550SE/M660SE VT6363A       | [9bd883acaa](https://linux-hardware.org/?probe=9bd883acaa) | Oct 12, 2020 |
| Dell          | G3 3590                     | [e710fb7efe](https://linux-hardware.org/?probe=e710fb7efe) | Oct 12, 2020 |
| ASUSTek       | GL702ZC                     | [c90edc1b80](https://linux-hardware.org/?probe=c90edc1b80) | Oct 12, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [33f4f77db5](https://linux-hardware.org/?probe=33f4f77db5) | Oct 10, 2020 |
| Lenovo        | ThinkPad Edge 0301GBG       | [8700c3217b](https://linux-hardware.org/?probe=8700c3217b) | Oct 10, 2020 |
| HP            | Notebook                    | [1e6bba57b7](https://linux-hardware.org/?probe=1e6bba57b7) | Oct 09, 2020 |
| Acer          | AO531h                      | [af1d7d28cc](https://linux-hardware.org/?probe=af1d7d28cc) | Oct 07, 2020 |
| Acer          | Aspire 5738                 | [f814a33c4c](https://linux-hardware.org/?probe=f814a33c4c) | Oct 07, 2020 |
| HP            | Pavilion g6                 | [c1ff9eb372](https://linux-hardware.org/?probe=c1ff9eb372) | Oct 06, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [2436dcb42a](https://linux-hardware.org/?probe=2436dcb42a) | Oct 02, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [815070f834](https://linux-hardware.org/?probe=815070f834) | Oct 02, 2020 |
| Lenovo        | ThinkPad E580 20KS006GUK    | [43cd14b799](https://linux-hardware.org/?probe=43cd14b799) | Oct 01, 2020 |
| HP            | Pavilion Notebook           | [85a733886a](https://linux-hardware.org/?probe=85a733886a) | Sep 29, 2020 |
| Dell          | XPS M1530                   | [dc08069215](https://linux-hardware.org/?probe=dc08069215) | Sep 29, 2020 |
| Sony          | VPCM13M1E                   | [139119fce3](https://linux-hardware.org/?probe=139119fce3) | Sep 28, 2020 |
| Sony          | VPCM13M1E                   | [40da79e9dc](https://linux-hardware.org/?probe=40da79e9dc) | Sep 28, 2020 |
| Lenovo        | ThinkBook 14-IML 20RV       | [f6809ca4e3](https://linux-hardware.org/?probe=f6809ca4e3) | Sep 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [135cb18944](https://linux-hardware.org/?probe=135cb18944) | Sep 26, 2020 |
| Toshiba       | Satellite L750              | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | Pavilion g6                 | [7ed6ea1d8e](https://linux-hardware.org/?probe=7ed6ea1d8e) | Sep 24, 2020 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [301fab4ca7](https://linux-hardware.org/?probe=301fab4ca7) | Sep 17, 2020 |
| HP            | Pavilion Notebook           | [a1e9bd74fd](https://linux-hardware.org/?probe=a1e9bd74fd) | Sep 17, 2020 |
| Toshiba       | Satellite L750              | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| ASUSTek       | TUF Gaming FX505DY          | [9149c8b59c](https://linux-hardware.org/?probe=9149c8b59c) | Sep 11, 2020 |
| ASUSTek       | TUF Gaming FX505DY          | [d549f8665d](https://linux-hardware.org/?probe=d549f8665d) | Sep 11, 2020 |
| ASUSTek       | TUF Gaming FX505DY          | [41a8975f07](https://linux-hardware.org/?probe=41a8975f07) | Sep 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [1f9434f4c9](https://linux-hardware.org/?probe=1f9434f4c9) | Sep 06, 2020 |
| Acer          | Aspire A315-31              | [118b474cc3](https://linux-hardware.org/?probe=118b474cc3) | Sep 06, 2020 |
| Dell          | Latitude 5400               | [1ae84c03c5](https://linux-hardware.org/?probe=1ae84c03c5) | Sep 02, 2020 |
| HP            | 15                          | [5b582297ed](https://linux-hardware.org/?probe=5b582297ed) | Sep 02, 2020 |
| Dell          | Inspiron 7720               | [9f2a48a228](https://linux-hardware.org/?probe=9f2a48a228) | Aug 25, 2020 |
| HP            | Compaq 6735s                | [529e1a4543](https://linux-hardware.org/?probe=529e1a4543) | Aug 21, 2020 |
| HP            | Pavilion Notebook           | [2afa749d39](https://linux-hardware.org/?probe=2afa749d39) | Aug 19, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [5faf279c4f](https://linux-hardware.org/?probe=5faf279c4f) | Aug 17, 2020 |
| Dell          | Inspiron 7559               | [85dd645b39](https://linux-hardware.org/?probe=85dd645b39) | Aug 16, 2020 |
| Lenovo        | V145-15AST 81MT             | [8b03ada262](https://linux-hardware.org/?probe=8b03ada262) | Aug 15, 2020 |
| Lenovo        | V145-15AST 81MT             | [a9262f65c0](https://linux-hardware.org/?probe=a9262f65c0) | Aug 15, 2020 |
| Dell          | Vostro 5481                 | [fc1a36f64d](https://linux-hardware.org/?probe=fc1a36f64d) | Aug 13, 2020 |
| Toshiba       | Satellite P200D             | [9bb94d56ed](https://linux-hardware.org/?probe=9bb94d56ed) | Aug 06, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | [20185e7b49](https://linux-hardware.org/?probe=20185e7b49) | Aug 04, 2020 |
| Hampoo        | Cherry Trail CR V200        | [62925bc138](https://linux-hardware.org/?probe=62925bc138) | Aug 01, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [50226c4586](https://linux-hardware.org/?probe=50226c4586) | Jul 30, 2020 |
| Dell          | Inspiron 5567               | [25489b5aa4](https://linux-hardware.org/?probe=25489b5aa4) | Jul 29, 2020 |
| Dell          | Inspiron 5567               | [d690a1848c](https://linux-hardware.org/?probe=d690a1848c) | Jul 29, 2020 |
| HP            | 250 G6 Notebook PC          | [7b6b423b68](https://linux-hardware.org/?probe=7b6b423b68) | Jul 23, 2020 |
| HP            | ENVY 17 Leap Motion SE N... | [192dd297bd](https://linux-hardware.org/?probe=192dd297bd) | Jul 22, 2020 |
| Dell          | G3 3590                     | [0bfa0fdeb2](https://linux-hardware.org/?probe=0bfa0fdeb2) | Jul 22, 2020 |
| HP            | ENVY 17 Leap Motion SE N... | [b73a34930b](https://linux-hardware.org/?probe=b73a34930b) | Jul 21, 2020 |
| HP            | ElitePad 1000 G2            | [b2c793bfb4](https://linux-hardware.org/?probe=b2c793bfb4) | Jul 09, 2020 |
| Dell          | Inspiron 3543               | [39df7edbea](https://linux-hardware.org/?probe=39df7edbea) | Jul 09, 2020 |
| HP            | ElitePad 1000 G2            | [152f8e9ebd](https://linux-hardware.org/?probe=152f8e9ebd) | Jul 09, 2020 |
| HP            | ElitePad 1000 G2            | [5054174795](https://linux-hardware.org/?probe=5054174795) | Jul 08, 2020 |
| Lenovo        | ThinkBook 14-IML 20RV       | [717049c98f](https://linux-hardware.org/?probe=717049c98f) | Jul 07, 2020 |
| Acer          | Aspire A315-53G             | [b6506c9a23](https://linux-hardware.org/?probe=b6506c9a23) | Jul 07, 2020 |
| Fujitsu       | LIFEBOOK E751               | [6f4a149255](https://linux-hardware.org/?probe=6f4a149255) | Jul 02, 2020 |
| Lenovo        | G40-30 80FY                 | [2e7c3657fb](https://linux-hardware.org/?probe=2e7c3657fb) | Jun 30, 2020 |
| Notebook      | NJ50_70CU                   | [5c9684cdab](https://linux-hardware.org/?probe=5c9684cdab) | Jun 29, 2020 |
| Lenovo        | G40-30 80FY                 | [5cfcbbb4a4](https://linux-hardware.org/?probe=5cfcbbb4a4) | Jun 28, 2020 |
| Notebook      | NJ50_70CU                   | [427a02d3bc](https://linux-hardware.org/?probe=427a02d3bc) | Jun 27, 2020 |
| Dell          | Inspiron 15-3552            | [9b7f2ae65e](https://linux-hardware.org/?probe=9b7f2ae65e) | Jun 25, 2020 |
| HP            | ZBook 15                    | [ac608e1d37](https://linux-hardware.org/?probe=ac608e1d37) | Jun 25, 2020 |
| HP            | ProBook 6560b               | [5db87fcc49](https://linux-hardware.org/?probe=5db87fcc49) | Jun 24, 2020 |
| HP            | ProBook 6560b               | [9a78de8ed6](https://linux-hardware.org/?probe=9a78de8ed6) | Jun 24, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [31b59ae094](https://linux-hardware.org/?probe=31b59ae094) | Jun 24, 2020 |
| Lenovo        | ThinkPad P50 20EQS2CY01     | [68f2706e1c](https://linux-hardware.org/?probe=68f2706e1c) | Jun 22, 2020 |
| Sony          | VGN-N31Z_W                  | [9dbeef64ee](https://linux-hardware.org/?probe=9dbeef64ee) | Jun 22, 2020 |
| ASUSTek       | K52JU                       | [38a9288b85](https://linux-hardware.org/?probe=38a9288b85) | Jun 21, 2020 |
| ASUSTek       | K52JU                       | [a07e2655ec](https://linux-hardware.org/?probe=a07e2655ec) | Jun 21, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [c2f7f39a83](https://linux-hardware.org/?probe=c2f7f39a83) | Jun 20, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [b388cd0a96](https://linux-hardware.org/?probe=b388cd0a96) | Jun 20, 2020 |
| ASUSTek       | X556UQK                     | [c6c57358a6](https://linux-hardware.org/?probe=c6c57358a6) | Jun 18, 2020 |
| Toshiba       | Satellite A300D             | [872199f2c5](https://linux-hardware.org/?probe=872199f2c5) | Jun 17, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [eaccc0249f](https://linux-hardware.org/?probe=eaccc0249f) | Jun 17, 2020 |
| Toshiba       | Satellite A300D             | [8e0f23dc31](https://linux-hardware.org/?probe=8e0f23dc31) | Jun 16, 2020 |
| HP            | 15                          | [7644a7713f](https://linux-hardware.org/?probe=7644a7713f) | Jun 16, 2020 |
| Acer          | Aspire 3935                 | [3957942dc1](https://linux-hardware.org/?probe=3957942dc1) | Jun 10, 2020 |
| HP            | Pavilion dv7                | [27d5196b74](https://linux-hardware.org/?probe=27d5196b74) | May 30, 2020 |
| Lenovo        | V330-14ARR 81B1             | [659d266fe7](https://linux-hardware.org/?probe=659d266fe7) | May 30, 2020 |
| HP            | 255 G7 Notebook PC          | [e4bba31386](https://linux-hardware.org/?probe=e4bba31386) | May 29, 2020 |
| HP            | 255 G7 Notebook PC          | [bd6ea57435](https://linux-hardware.org/?probe=bd6ea57435) | May 29, 2020 |
| Toshiba       | Satellite S855D             | [2b4ff1e9b6](https://linux-hardware.org/?probe=2b4ff1e9b6) | May 29, 2020 |
| Toshiba       | Satellite S855D             | [8e54bbb3e2](https://linux-hardware.org/?probe=8e54bbb3e2) | May 29, 2020 |
| Lenovo        | ThinkPad P50 20EQS2CY01     | [9975194681](https://linux-hardware.org/?probe=9975194681) | May 28, 2020 |
| HP            | Pavilion g6                 | [1fd4402991](https://linux-hardware.org/?probe=1fd4402991) | May 28, 2020 |
| Lenovo        | ThinkPad Edge 0301GBG       | [15696a9c46](https://linux-hardware.org/?probe=15696a9c46) | May 28, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [0508854129](https://linux-hardware.org/?probe=0508854129) | May 27, 2020 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [0d35855885](https://linux-hardware.org/?probe=0d35855885) | May 25, 2020 |
| Lenovo        | ThinkPad T580 20L90023RT    | [a7b6c79ac0](https://linux-hardware.org/?probe=a7b6c79ac0) | May 24, 2020 |
| HP            | Pavilion dv7                | [9d4e0753f6](https://linux-hardware.org/?probe=9d4e0753f6) | May 23, 2020 |
| HP            | Unknown                     | [f8fa416688](https://linux-hardware.org/?probe=f8fa416688) | May 22, 2020 |
| Dell          | Latitude E6410              | [7c8e49e14c](https://linux-hardware.org/?probe=7c8e49e14c) | May 22, 2020 |
| HP            | Compaq Presario C700        | [32ab884c0f](https://linux-hardware.org/?probe=32ab884c0f) | May 21, 2020 |
| HP            | Pavilion g6                 | [31a778de5b](https://linux-hardware.org/?probe=31a778de5b) | May 18, 2020 |
| HP            | Pavilion g6                 | [619ed13a7f](https://linux-hardware.org/?probe=619ed13a7f) | May 18, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [fa51e14d38](https://linux-hardware.org/?probe=fa51e14d38) | May 17, 2020 |
| Intel         | CAPELL VALLEY CRB           | [67b7ec6a84](https://linux-hardware.org/?probe=67b7ec6a84) | May 17, 2020 |
| HP            | Pavilion g6                 | [f5334be644](https://linux-hardware.org/?probe=f5334be644) | May 17, 2020 |
| Notebook      | W65_67SH                    | [497422c9fc](https://linux-hardware.org/?probe=497422c9fc) | May 16, 2020 |
| Notebook      | W65_67SH                    | [9559aff349](https://linux-hardware.org/?probe=9559aff349) | May 16, 2020 |
| Dell          | Latitude E5410              | [b51e124387](https://linux-hardware.org/?probe=b51e124387) | May 13, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [d225d411f9](https://linux-hardware.org/?probe=d225d411f9) | May 13, 2020 |
| HP            | 250 G4                      | [adc4529aff](https://linux-hardware.org/?probe=adc4529aff) | May 12, 2020 |
| Lenovo        | ThinkPad X230 23245D4       | [740b68266b](https://linux-hardware.org/?probe=740b68266b) | May 12, 2020 |
| Dell          | G3 3590                     | [85e10bcd60](https://linux-hardware.org/?probe=85e10bcd60) | May 11, 2020 |
| Toshiba       | NB100                       | [3459eb4984](https://linux-hardware.org/?probe=3459eb4984) | May 11, 2020 |
| HP            | Unknown                     | [b52569877b](https://linux-hardware.org/?probe=b52569877b) | May 11, 2020 |
| HP            | Pavilion Notebook           | [57203b3010](https://linux-hardware.org/?probe=57203b3010) | May 11, 2020 |
| HP            | G5000 (GF767EA#B1A)         | [39fd61954e](https://linux-hardware.org/?probe=39fd61954e) | May 10, 2020 |
| Dell          | Inspiron 3542               | [231fda4e89](https://linux-hardware.org/?probe=231fda4e89) | May 09, 2020 |
| Lenovo        | ThinkPad X250 20CLS0110B    | [9da7641ead](https://linux-hardware.org/?probe=9da7641ead) | May 07, 2020 |
| Pegatron      | D15R                        | [9b128d4d23](https://linux-hardware.org/?probe=9b128d4d23) | May 05, 2020 |
| Pegatron      | D15R                        | [25cf2e91d8](https://linux-hardware.org/?probe=25cf2e91d8) | May 05, 2020 |
| Sony          | VGN-CR590E                  | [cb2c7466cc](https://linux-hardware.org/?probe=cb2c7466cc) | May 04, 2020 |
| Acer          | Aspire 5100                 | [0b4ce05d4b](https://linux-hardware.org/?probe=0b4ce05d4b) | May 03, 2020 |
| Fujitsu Si... | AMILO M1451G Series         | [f77cb5d716](https://linux-hardware.org/?probe=f77cb5d716) | Apr 30, 2020 |
| Lenovo        | G580 20150                  | [158ef386df](https://linux-hardware.org/?probe=158ef386df) | Apr 29, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [7deee5c6f4](https://linux-hardware.org/?probe=7deee5c6f4) | Apr 28, 2020 |
| HP            | ProBook 6560b               | [f7e0abeaf2](https://linux-hardware.org/?probe=f7e0abeaf2) | Apr 27, 2020 |
| HP            | Pavilion g6                 | [166222e5c9](https://linux-hardware.org/?probe=166222e5c9) | Apr 26, 2020 |
| HP            | Pavilion g6                 | [e5e0d5140e](https://linux-hardware.org/?probe=e5e0d5140e) | Apr 25, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [6770cf29bb](https://linux-hardware.org/?probe=6770cf29bb) | Apr 25, 2020 |
| Sony          | VGN-FE41E                   | [1d8645be3f](https://linux-hardware.org/?probe=1d8645be3f) | Apr 24, 2020 |
| Apple         | MacBook5,2                  | [33530c3091](https://linux-hardware.org/?probe=33530c3091) | Apr 21, 2020 |
| Apple         | MacBook5,2                  | [fbb9346ad4](https://linux-hardware.org/?probe=fbb9346ad4) | Apr 21, 2020 |
| Toshiba       | Satellite L450D             | [7f26f2d180](https://linux-hardware.org/?probe=7f26f2d180) | Apr 20, 2020 |
| HP            | Unknown                     | [6cd3c0a036](https://linux-hardware.org/?probe=6cd3c0a036) | Apr 19, 2020 |
| HP            | Unknown                     | [7a5b60f20c](https://linux-hardware.org/?probe=7a5b60f20c) | Apr 19, 2020 |
| HP            | Unknown                     | [97ca26d3d7](https://linux-hardware.org/?probe=97ca26d3d7) | Apr 19, 2020 |
| Toshiba       | Satellite L450D             | [f541e27fef](https://linux-hardware.org/?probe=f541e27fef) | Apr 14, 2020 |
| Toshiba       | Satellite L450D             | [dd6245c9f1](https://linux-hardware.org/?probe=dd6245c9f1) | Apr 14, 2020 |
| HP            | Compaq 6710b (GR680EA#B1... | [fb9d604f9d](https://linux-hardware.org/?probe=fb9d604f9d) | Apr 13, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [20eeb3f580](https://linux-hardware.org/?probe=20eeb3f580) | Apr 12, 2020 |
| Lenovo        | G510 20238                  | [72f97922cc](https://linux-hardware.org/?probe=72f97922cc) | Apr 09, 2020 |
| Lenovo        | G510 20238                  | [126766dead](https://linux-hardware.org/?probe=126766dead) | Apr 09, 2020 |
| Dell          | Inspiron 5558               | [9ecfa320c9](https://linux-hardware.org/?probe=9ecfa320c9) | Apr 08, 2020 |
| Dell          | G3 3590                     | [9466a720ff](https://linux-hardware.org/?probe=9466a720ff) | Apr 07, 2020 |
| HP            | Pavilion dv7                | [88ff5b44b7](https://linux-hardware.org/?probe=88ff5b44b7) | Apr 07, 2020 |
| Dell          | Latitude E6510              | [5f62bf8564](https://linux-hardware.org/?probe=5f62bf8564) | Apr 07, 2020 |
| HP            | Presario CQ62               | [3821156090](https://linux-hardware.org/?probe=3821156090) | Apr 06, 2020 |
| ASUSTek       | X540LJ                      | [3818f5dd9e](https://linux-hardware.org/?probe=3818f5dd9e) | Apr 05, 2020 |
| Dell          | Inspiron 1750               | [3b7ede7bc6](https://linux-hardware.org/?probe=3b7ede7bc6) | Apr 05, 2020 |
| HP            | Pavilion dv7                | [88debf96e8](https://linux-hardware.org/?probe=88debf96e8) | Apr 04, 2020 |
| HP            | Pavilion dv7                | [d64ce74086](https://linux-hardware.org/?probe=d64ce74086) | Apr 04, 2020 |
| Sony          | VGN-CR590E                  | [121394a15c](https://linux-hardware.org/?probe=121394a15c) | Apr 03, 2020 |
| E-shop.gr     | Innovator M1589             | [be146dfa67](https://linux-hardware.org/?probe=be146dfa67) | Mar 31, 2020 |
| Fujitsu       | LIFEBOOK AH531              | [9c2eef7d10](https://linux-hardware.org/?probe=9c2eef7d10) | Mar 31, 2020 |
| Lenovo        | G50-70 20351                | [199d2287e2](https://linux-hardware.org/?probe=199d2287e2) | Mar 30, 2020 |
| Sony          | VPCM13M1E                   | [eb20399d8b](https://linux-hardware.org/?probe=eb20399d8b) | Mar 30, 2020 |
| Apple         | MacBook1,1                  | [27d210b0e2](https://linux-hardware.org/?probe=27d210b0e2) | Mar 30, 2020 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [b9f6bf0ad4](https://linux-hardware.org/?probe=b9f6bf0ad4) | Mar 29, 2020 |
| ASUSTek       | 1101HAGG                    | [1ecc8fa4d3](https://linux-hardware.org/?probe=1ecc8fa4d3) | Mar 29, 2020 |
| ASUSTek       | 1101HAGG                    | [8d2c258ed7](https://linux-hardware.org/?probe=8d2c258ed7) | Mar 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [220c3c60b0](https://linux-hardware.org/?probe=220c3c60b0) | Mar 28, 2020 |
| Dell          | Inspiron 3543               | [5d80035b8d](https://linux-hardware.org/?probe=5d80035b8d) | Mar 27, 2020 |
| HP            | Compaq Mini 110c-1000       | [ba8efb8d78](https://linux-hardware.org/?probe=ba8efb8d78) | Mar 26, 2020 |
| Lenovo        | G50-70 20351                | [d361a95cae](https://linux-hardware.org/?probe=d361a95cae) | Mar 24, 2020 |
| Dell          | G3 3590                     | [ff14d5222d](https://linux-hardware.org/?probe=ff14d5222d) | Mar 24, 2020 |
| Sony          | VGN-NR11Z_S                 | [69fb7aa4d4](https://linux-hardware.org/?probe=69fb7aa4d4) | Mar 23, 2020 |
| HP            | ProBook 6560b               | [40d00a5fb1](https://linux-hardware.org/?probe=40d00a5fb1) | Mar 16, 2020 |
| Lenovo        | ThinkPad T490 20N2000BRT    | [a6b3d80476](https://linux-hardware.org/?probe=a6b3d80476) | Mar 11, 2020 |
| Lenovo        | ThinkPad T470 20HD000LUK    | [9c47172207](https://linux-hardware.org/?probe=9c47172207) | Mar 08, 2020 |
| Lenovo        | ThinkPad T420 4236Q23       | [65d50c61eb](https://linux-hardware.org/?probe=65d50c61eb) | Mar 05, 2020 |
| Acer          | Aspire A315-53G             | [150b9c6b6d](https://linux-hardware.org/?probe=150b9c6b6d) | Feb 25, 2020 |
| Compal        | JHL90 REFERENCE             | [56b05900a0](https://linux-hardware.org/?probe=56b05900a0) | Feb 24, 2020 |
| Dell          | Inspiron 15-3567            | [270e63cceb](https://linux-hardware.org/?probe=270e63cceb) | Feb 23, 2020 |
| Acer          | Aspire A315-51              | [77543de863](https://linux-hardware.org/?probe=77543de863) | Feb 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f3fe28b459](https://linux-hardware.org/?probe=f3fe28b459) | Feb 19, 2020 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [6beff5886c](https://linux-hardware.org/?probe=6beff5886c) | Feb 19, 2020 |
| HP            | EliteBook 6930p (KK082AV... | [55a53b12ce](https://linux-hardware.org/?probe=55a53b12ce) | Feb 15, 2020 |
| HP            | EliteBook 6930p (KK082AV... | [745a30749e](https://linux-hardware.org/?probe=745a30749e) | Feb 15, 2020 |
| HP            | EliteBook 8460p             | [b57c6ec496](https://linux-hardware.org/?probe=b57c6ec496) | Feb 12, 2020 |
| Chuwi         | HeroBook                    | [c63663b03e](https://linux-hardware.org/?probe=c63663b03e) | Feb 09, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [7b350a4e79](https://linux-hardware.org/?probe=7b350a4e79) | Feb 07, 2020 |
| HP            | 15                          | [16b52341f5](https://linux-hardware.org/?probe=16b52341f5) | Feb 04, 2020 |
| Acer          | TravelMate 2490             | [a93e1d86a8](https://linux-hardware.org/?probe=a93e1d86a8) | Jan 27, 2020 |
| VERO          | K147                        | [9f10ca8308](https://linux-hardware.org/?probe=9f10ca8308) | Jan 26, 2020 |
| Lenovo        | ThinkPad E495 20NE001GMH    | [3a02dced23](https://linux-hardware.org/?probe=3a02dced23) | Jan 14, 2020 |
| Lenovo        | ThinkPad L412 0585W28       | [8ba74bb2b0](https://linux-hardware.org/?probe=8ba74bb2b0) | Jan 13, 2020 |
| Sony          | VGN-FW21M                   | [cda530b21f](https://linux-hardware.org/?probe=cda530b21f) | Jan 12, 2020 |
| HP            | 650                         | [41d463f623](https://linux-hardware.org/?probe=41d463f623) | Jan 09, 2020 |
| Acer          | TravelMate 2490             | [b883b5c1af](https://linux-hardware.org/?probe=b883b5c1af) | Jan 09, 2020 |
| Acer          | TravelMate 2490             | [76920bc1b7](https://linux-hardware.org/?probe=76920bc1b7) | Jan 03, 2020 |
| Acer          | Aspire 5755G                | [99f3d96106](https://linux-hardware.org/?probe=99f3d96106) | Dec 31, 2019 |
| HP            | 255 G6 Notebook PC          | [4d572c7a12](https://linux-hardware.org/?probe=4d572c7a12) | Dec 31, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | [1a90ac4588](https://linux-hardware.org/?probe=1a90ac4588) | Dec 26, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | [966b8a2a9a](https://linux-hardware.org/?probe=966b8a2a9a) | Dec 23, 2019 |
| ASUSTek       | X551MA                      | [cc9b263062](https://linux-hardware.org/?probe=cc9b263062) | Dec 23, 2019 |
| HP            | EliteBook 8440p             | [d1c32bf428](https://linux-hardware.org/?probe=d1c32bf428) | Dec 21, 2019 |
| HP            | EliteBook 8460p             | [00c6afae23](https://linux-hardware.org/?probe=00c6afae23) | Dec 19, 2019 |
| Acer          | Aspire A315-31              | [702d379dd6](https://linux-hardware.org/?probe=702d379dd6) | Dec 17, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | [6498ff99ee](https://linux-hardware.org/?probe=6498ff99ee) | Dec 15, 2019 |
| Lenovo        | ThinkPad T400 6475R1G       | [b27320fd81](https://linux-hardware.org/?probe=b27320fd81) | Dec 15, 2019 |
| Insyde        | CherryTrail                 | [deeda709d2](https://linux-hardware.org/?probe=deeda709d2) | Dec 07, 2019 |
| Insyde        | CherryTrail                 | [81201a03c1](https://linux-hardware.org/?probe=81201a03c1) | Dec 07, 2019 |
| HP            | 650                         | [2a96c9ca75](https://linux-hardware.org/?probe=2a96c9ca75) | Dec 03, 2019 |
| HP            | 650                         | [4a1d85a63b](https://linux-hardware.org/?probe=4a1d85a63b) | Dec 03, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [4db92d49fe](https://linux-hardware.org/?probe=4db92d49fe) | Nov 30, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [495e998bda](https://linux-hardware.org/?probe=495e998bda) | Nov 28, 2019 |
| HP            | 255 G7 Notebook PC          | [d73b2ac7d1](https://linux-hardware.org/?probe=d73b2ac7d1) | Nov 28, 2019 |
| HP            | 255 G7 Notebook PC          | [5fd6ae6ef8](https://linux-hardware.org/?probe=5fd6ae6ef8) | Nov 28, 2019 |
| Lenovo        | IdeaPad S210 Touch 20257    | [bf342390e8](https://linux-hardware.org/?probe=bf342390e8) | Nov 24, 2019 |
| Lenovo        | ThinkPad L412 0585W28       | [73073ac3f3](https://linux-hardware.org/?probe=73073ac3f3) | Nov 17, 2019 |
| Dell          | Precision M3800             | [b133f93faa](https://linux-hardware.org/?probe=b133f93faa) | Nov 10, 2019 |
| Toshiba       | Satellite P755              | [673d423adc](https://linux-hardware.org/?probe=673d423adc) | Nov 10, 2019 |
| Toshiba       | Satellite L50D-B            | [eb4b70f853](https://linux-hardware.org/?probe=eb4b70f853) | Nov 03, 2019 |
| Toshiba       | Satellite L50D-B            | [3b759734b2](https://linux-hardware.org/?probe=3b759734b2) | Nov 03, 2019 |
| Toshiba       | Satellite L50D-B            | [fe505beff6](https://linux-hardware.org/?probe=fe505beff6) | Nov 03, 2019 |
| Pegatron      | A15                         | [291f1aae6d](https://linux-hardware.org/?probe=291f1aae6d) | Oct 29, 2019 |
| HP            | Pavilion Notebook           | [87a279150a](https://linux-hardware.org/?probe=87a279150a) | Oct 26, 2019 |
| HP            | 630                         | [99ab4364d4](https://linux-hardware.org/?probe=99ab4364d4) | Oct 26, 2019 |
| Acer          | AOD270                      | [fbe9c7eee3](https://linux-hardware.org/?probe=fbe9c7eee3) | Oct 25, 2019 |
| Acer          | AOD270                      | [cfabf3084a](https://linux-hardware.org/?probe=cfabf3084a) | Oct 25, 2019 |
| HP            | Presario CQ57               | [758c395c78](https://linux-hardware.org/?probe=758c395c78) | Oct 23, 2019 |
| Acer          | AOD270                      | [1ae1144336](https://linux-hardware.org/?probe=1ae1144336) | Oct 19, 2019 |
| Sony          | SVE1512C6EW                 | [cc73d5214f](https://linux-hardware.org/?probe=cc73d5214f) | Sep 23, 2019 |
| Lenovo        | N22 80S6                    | [5850aa007f](https://linux-hardware.org/?probe=5850aa007f) | Sep 09, 2019 |
| Toshiba       | Satellite S855D             | [b0e8c02a13](https://linux-hardware.org/?probe=b0e8c02a13) | Sep 07, 2019 |
| ASUSTek       | X541NA                      | [dad09e76f4](https://linux-hardware.org/?probe=dad09e76f4) | Sep 05, 2019 |
| HP            | Compaq Presario C700        | [f05eb74bea](https://linux-hardware.org/?probe=f05eb74bea) | Aug 31, 2019 |
| HP            | Pavilion 15                 | [2f3cb20593](https://linux-hardware.org/?probe=2f3cb20593) | Aug 30, 2019 |
| Lenovo        | G550 20023                  | [d6126ff072](https://linux-hardware.org/?probe=d6126ff072) | Aug 30, 2019 |
| HP            | Pavilion 15                 | [61616fc1bf](https://linux-hardware.org/?probe=61616fc1bf) | Aug 10, 2019 |
| HP            | Pavilion 15                 | [dc6c804e81](https://linux-hardware.org/?probe=dc6c804e81) | Jul 26, 2019 |
| HP            | Pavilion 15                 | [3652e8f3c6](https://linux-hardware.org/?probe=3652e8f3c6) | Jul 26, 2019 |
| Pegatron      | A15                         | [1b6dcb6a34](https://linux-hardware.org/?probe=1b6dcb6a34) | Jul 20, 2019 |
| Lenovo        | N22 80S6                    | [97f993a2ca](https://linux-hardware.org/?probe=97f993a2ca) | Jul 19, 2019 |
| Packard Be... | EasyNote MH35               | [eb538975bd](https://linux-hardware.org/?probe=eb538975bd) | Jul 13, 2019 |
| HP            | Pavilion zd8000 (EL033EA... | [91c7ae2180](https://linux-hardware.org/?probe=91c7ae2180) | Jul 12, 2019 |
| HP            | Compaq Presario CQ60        | [265a212fdc](https://linux-hardware.org/?probe=265a212fdc) | Jun 02, 2019 |
| Lenovo        | IdeaPad S210 Touch 20257    | [5834730131](https://linux-hardware.org/?probe=5834730131) | May 31, 2019 |
| HP            | Compaq Presario CQ60        | [4e935854b3](https://linux-hardware.org/?probe=4e935854b3) | May 26, 2019 |
| Lenovo        | V510-15IKB 80WQ             | [a8db92bb48](https://linux-hardware.org/?probe=a8db92bb48) | May 23, 2019 |
| MSI           | GE70 2PC                    | [347632684e](https://linux-hardware.org/?probe=347632684e) | May 10, 2019 |
| Dell          | Inspiron 3537               | [b57530d6a4](https://linux-hardware.org/?probe=b57530d6a4) | May 07, 2019 |
| Clevo         | M740TU(N)/M760TU(N)/W7X0... | [bf6bd6c60d](https://linux-hardware.org/?probe=bf6bd6c60d) | May 06, 2019 |
| Fujitsu Si... | AMILO Xi 2428               | [7f4acc9070](https://linux-hardware.org/?probe=7f4acc9070) | May 03, 2019 |
| Dell          | Inspiron 3521               | [5913b022e4](https://linux-hardware.org/?probe=5913b022e4) | May 01, 2019 |
| Toshiba       | Satellite S855D             | [b1213b7b31](https://linux-hardware.org/?probe=b1213b7b31) | Apr 28, 2019 |
| Lenovo        | ThinkPad T400 2768WR2       | [90cf61c66f](https://linux-hardware.org/?probe=90cf61c66f) | Apr 28, 2019 |
| Lenovo        | ThinkPad T400 2768WR2       | [820530546d](https://linux-hardware.org/?probe=820530546d) | Apr 28, 2019 |
| HP            | Pavilion g6                 | [50125f8815](https://linux-hardware.org/?probe=50125f8815) | Apr 25, 2019 |
| Dell          | Inspiron 5323               | [d25db8c5f1](https://linux-hardware.org/?probe=d25db8c5f1) | Apr 24, 2019 |
| Dell          | Inspiron 3543               | [b028e3e4f9](https://linux-hardware.org/?probe=b028e3e4f9) | Apr 18, 2019 |
| Intel         | Calistoga & ICH7M Chipse... | [146663e5c0](https://linux-hardware.org/?probe=146663e5c0) | Apr 17, 2019 |
| Info Quest... | GTN1408                     | [968a29d212](https://linux-hardware.org/?probe=968a29d212) | Apr 06, 2019 |
| HP            | Pavilion x2 Detachable      | [f91e0fbe6b](https://linux-hardware.org/?probe=f91e0fbe6b) | Apr 05, 2019 |
| HP            | Pavilion x2 Detachable      | [7dfc4ddd35](https://linux-hardware.org/?probe=7dfc4ddd35) | Apr 05, 2019 |
| Info Quest... | GTN1408                     | [bfc5bebd38](https://linux-hardware.org/?probe=bfc5bebd38) | Apr 05, 2019 |
| Info Quest... | GTN1408                     | [b0a5ef56cb](https://linux-hardware.org/?probe=b0a5ef56cb) | Apr 05, 2019 |
| ASUSTek       | X551MA                      | [4d7df702b8](https://linux-hardware.org/?probe=4d7df702b8) | Apr 05, 2019 |
| ASUSTek       | X551MA                      | [1b08ea07c0](https://linux-hardware.org/?probe=1b08ea07c0) | Apr 05, 2019 |
| Dell          | Inspiron 3576               | [132c5c22bb](https://linux-hardware.org/?probe=132c5c22bb) | Mar 24, 2019 |
| Dell          | Inspiron 3576               | [df5ad730b4](https://linux-hardware.org/?probe=df5ad730b4) | Mar 18, 2019 |
| Dell          | Inspiron 3576               | [a88f966e70](https://linux-hardware.org/?probe=a88f966e70) | Mar 18, 2019 |
| Toshiba       | Satellite C660D             | [884f236bc9](https://linux-hardware.org/?probe=884f236bc9) | Mar 14, 2019 |
| Toshiba       | Satellite C660D             | [ec10f22ef4](https://linux-hardware.org/?probe=ec10f22ef4) | Mar 12, 2019 |
| Sony          | VGN-SZ71XN_C                | [afbc222743](https://linux-hardware.org/?probe=afbc222743) | Mar 10, 2019 |
| Sony          | VGN-SZ71XN_C                | [75a71aa3ec](https://linux-hardware.org/?probe=75a71aa3ec) | Mar 10, 2019 |
| ASUSTek       | X555BA                      | [79a6f78b23](https://linux-hardware.org/?probe=79a6f78b23) | Mar 07, 2019 |
| Acer          | Aspire 5935                 | [454098b840](https://linux-hardware.org/?probe=454098b840) | Mar 04, 2019 |
| HP            | Pavilion dv5                | [cfd60bad2b](https://linux-hardware.org/?probe=cfd60bad2b) | Feb 23, 2019 |
| Dell          | Inspiron 3543               | [bf3ef7e629](https://linux-hardware.org/?probe=bf3ef7e629) | Feb 17, 2019 |
| Dell          | Inspiron 5555               | [65100107dc](https://linux-hardware.org/?probe=65100107dc) | Feb 16, 2019 |
| HP            | 15                          | [30a42ae5dc](https://linux-hardware.org/?probe=30a42ae5dc) | Feb 13, 2019 |
| Lenovo        | ThinkPad T440p 20AW0000U... | [5a68cab2c0](https://linux-hardware.org/?probe=5a68cab2c0) | Jan 24, 2019 |
| Lenovo        | ThinkPad T440p 20AW0000U... | [103dc16b24](https://linux-hardware.org/?probe=103dc16b24) | Jan 24, 2019 |
| Samsung       | 300E4C/300E5C/300E7C        | [e7121f92f8](https://linux-hardware.org/?probe=e7121f92f8) | Jan 20, 2019 |
| Lenovo        | ThinkPad T420 4236NGG       | [5b72be1d6f](https://linux-hardware.org/?probe=5b72be1d6f) | Jan 01, 2019 |
| Lenovo        | ThinkPad T420 4236NGG       | [ac9ae784ed](https://linux-hardware.org/?probe=ac9ae784ed) | Dec 30, 2018 |
| Lenovo        | ThinkPad T420 4236NGG       | [9947b5b177](https://linux-hardware.org/?probe=9947b5b177) | Dec 28, 2018 |
| Lenovo        | ThinkPad T420 4236NGG       | [3cc96f096e](https://linux-hardware.org/?probe=3cc96f096e) | Dec 28, 2018 |
| Dell          | Inspiron 3542               | [a630fe7049](https://linux-hardware.org/?probe=a630fe7049) | Dec 25, 2018 |
| Dell          | Inspiron 3542               | [cd0695d1aa](https://linux-hardware.org/?probe=cd0695d1aa) | Dec 25, 2018 |
| Dell          | Inspiron 3521               | [f56872fdba](https://linux-hardware.org/?probe=f56872fdba) | Dec 15, 2018 |
| Dell          | Inspiron 3521               | [a3e64442a6](https://linux-hardware.org/?probe=a3e64442a6) | Dec 15, 2018 |
| Acer          | Aspire A315-31              | [03420d4e05](https://linux-hardware.org/?probe=03420d4e05) | Dec 03, 2018 |
| Acer          | Aspire A315-31              | [5afd838dfc](https://linux-hardware.org/?probe=5afd838dfc) | Dec 03, 2018 |
| Sony          | VGN-AR41L                   | [e80a4c81ba](https://linux-hardware.org/?probe=e80a4c81ba) | Nov 17, 2018 |
| Sony          | VGN-AR41L                   | [33c85bd949](https://linux-hardware.org/?probe=33c85bd949) | Nov 17, 2018 |
| HP            | 630                         | [375f1ecc8e](https://linux-hardware.org/?probe=375f1ecc8e) | Nov 11, 2018 |
| Fujitsu       | LIFEBOOK S760               | [e5a9a2740a](https://linux-hardware.org/?probe=e5a9a2740a) | Nov 03, 2018 |
| Lenovo        | ThinkPad X201 3680BW9       | [b2ac9f5577](https://linux-hardware.org/?probe=b2ac9f5577) | Nov 03, 2018 |
| HP            | Notebook                    | [643f8c70bb](https://linux-hardware.org/?probe=643f8c70bb) | Oct 30, 2018 |
| Lenovo        | G700 20251                  | [25cef818bf](https://linux-hardware.org/?probe=25cef818bf) | Oct 22, 2018 |
| HP            | Notebook                    | [8be002c789](https://linux-hardware.org/?probe=8be002c789) | Oct 21, 2018 |
| HP            | EliteBook 820 G1            | [5ffb2eac69](https://linux-hardware.org/?probe=5ffb2eac69) | Jun 12, 2018 |
| Dell          | Latitude D530               | [37fd80baa9](https://linux-hardware.org/?probe=37fd80baa9) | May 18, 2018 |
| Dell          | Latitude D530               | [4a84b665e6](https://linux-hardware.org/?probe=4a84b665e6) | May 18, 2018 |
| Lenovo        | G510 20238                  | [f39685a972](https://linux-hardware.org/?probe=f39685a972) | Apr 22, 2018 |
| HP            | G62                         | [4fd190da5e](https://linux-hardware.org/?probe=4fd190da5e) | Apr 18, 2018 |
| Clevo         | W251ESQ/W270ESQ             | [a9eccff022](https://linux-hardware.org/?probe=a9eccff022) | Aug 01, 2017 |
| ASUSTek       | UX31E                       | [6be30c42a9](https://linux-hardware.org/?probe=6be30c42a9) | Jun 28, 2017 |
| Dell          | Inspiron 5558               | [ffc88e7749](https://linux-hardware.org/?probe=ffc88e7749) | Apr 23, 2017 |
| Toshiba       | TECRA R850                  | [6f44cbe917](https://linux-hardware.org/?probe=6f44cbe917) | Mar 14, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Greece/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 90        | 14.95%  |
| Ubuntu 18.04      | 61        | 10.13%  |
| Ubuntu 22.04      | 15        | 2.49%   |
| KDE neon 20.04    | 15        | 2.49%   |
| OpenMandriva 4.2  | 14        | 2.33%   |
| OpenMandriva 4.3  | 13        | 2.16%   |
| Linux Mint 19.3   | 13        | 2.16%   |
| Debian 11         | 13        | 2.16%   |
| Zorin 15          | 11        | 1.83%   |
| Arch Rolling      | 11        | 1.83%   |
| Ubuntu 19.10      | 10        | 1.66%   |
| Debian 10         | 10        | 1.66%   |
| Zorin 16          | 9         | 1.5%    |
| Xubuntu 20.04     | 9         | 1.5%    |
| Pop!_OS 20.04     | 9         | 1.5%    |
| Manjaro           | 9         | 1.5%    |
| Linux Mint 20.1   | 9         | 1.5%    |
| Fedora 35         | 9         | 1.5%    |
| Xubuntu 18.04     | 8         | 1.33%   |
| Pop!_OS 21.04     | 8         | 1.33%   |
| Linux Mint 20.2   | 8         | 1.33%   |
| Arch              | 8         | 1.33%   |
| Pop!_OS 22.04     | 7         | 1.16%   |
| Pop!_OS 20.10     | 7         | 1.16%   |
| Gentoo 2.7        | 7         | 1.16%   |
| Ubuntu 21.10      | 6         | 1%      |
| Ubuntu 21.04      | 6         | 1%      |
| Ubuntu 19.04      | 6         | 1%      |
| ROSA R10          | 6         | 1%      |
| Linux Mint 20.3   | 6         | 1%      |
| Kubuntu 20.04     | 6         | 1%      |
| ArcoLinux Rolling | 6         | 1%      |
| Ubuntu 20.10      | 5         | 0.83%   |
| Linux Mint 21     | 5         | 0.83%   |
| Linux Mint 20     | 5         | 0.83%   |
| Fedora 33         | 5         | 0.83%   |
| Fedora 32         | 5         | 0.83%   |
| Ubuntu 18.10      | 4         | 0.66%   |
| Pop!_OS 21.10     | 4         | 0.66%   |
| Gentoo 2.8        | 4         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 195       | 34.15%  |
| Linux Mint    | 51        | 8.93%   |
| Pop!_OS       | 33        | 5.78%   |
| OpenMandriva  | 30        | 5.25%   |
| Fedora        | 27        | 4.73%   |
| Debian        | 26        | 4.55%   |
| Manjaro       | 23        | 4.03%   |
| Zorin         | 21        | 3.68%   |
| Xubuntu       | 18        | 3.15%   |
| Arch          | 18        | 3.15%   |
| KDE neon      | 15        | 2.63%   |
| Endless       | 14        | 2.45%   |
| ROSA          | 12        | 2.1%    |
| Kubuntu       | 11        | 1.93%   |
| Gentoo        | 10        | 1.75%   |
| ArcoLinux     | 7         | 1.23%   |
| Ubuntu MATE   | 5         | 0.88%   |
| Ubuntu Unity  | 4         | 0.7%    |
| Ubuntu Budgie | 4         | 0.7%    |
| ALT Linux     | 4         | 0.7%    |
| Lubuntu       | 3         | 0.53%   |
| LMDE          | 3         | 0.53%   |
| LinuxFX       | 3         | 0.53%   |
| Kali          | 3         | 0.53%   |
| EndeavourOS   | 3         | 0.53%   |
| Elementary    | 3         | 0.53%   |
| BlackPanther  | 3         | 0.53%   |
| Xero          | 2         | 0.35%   |
| Peppermint    | 2         | 0.35%   |
| openSUSE      | 2         | 0.35%   |
| CentOS        | 2         | 0.35%   |
| Void Linux    | 1         | 0.18%   |
| SteamOS       | 1         | 0.18%   |
| Solus         | 1         | 0.18%   |
| Parrot        | 1         | 0.18%   |
| MX            | 1         | 0.18%   |
| Mageia        | 1         | 0.18%   |
| GNOME OS      | 1         | 0.18%   |
| GalliumOS     | 1         | 0.18%   |
| Feren OS      | 1         | 0.18%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-58-generic         | 14        | 2.15%   |
| 5.4.0-42-generic         | 13        | 1.99%   |
| 5.16.7-desktop-1omv4003  | 13        | 1.99%   |
| 5.10.14-desktop-1omv4002 | 13        | 1.99%   |
| 5.4.0-29-generic         | 8         | 1.23%   |
| 5.4.0-48-generic         | 7         | 1.07%   |
| 5.4.0-65-generic         | 6         | 0.92%   |
| 5.3.0-46-generic         | 6         | 0.92%   |
| 5.15.0-52-generic        | 6         | 0.92%   |
| 5.15.0-41-generic        | 6         | 0.92%   |
| 5.11.0-38-generic        | 6         | 0.92%   |
| 5.8.0-55-generic         | 5         | 0.77%   |
| 5.4.0-37-generic         | 5         | 0.77%   |
| 5.3.0-45-generic         | 5         | 0.77%   |
| 5.3.0-42-generic         | 5         | 0.77%   |
| 5.15.0-46-generic        | 5         | 0.77%   |
| 5.13.0-39-generic        | 5         | 0.77%   |
| 5.11.0-7620-generic      | 5         | 0.77%   |
| 5.11.0-7614-generic      | 5         | 0.77%   |
| 5.0.0-37-generic         | 5         | 0.77%   |
| 4.15.0-47-generic        | 5         | 0.77%   |
| 5.8.0-7630-generic       | 4         | 0.61%   |
| 5.8.0-48-generic         | 4         | 0.61%   |
| 5.8.0-43-generic         | 4         | 0.61%   |
| 5.4.0-91-generic         | 4         | 0.61%   |
| 5.4.0-72-generic         | 4         | 0.61%   |
| 5.4.0-66-generic         | 4         | 0.61%   |
| 5.4.0-56-generic         | 4         | 0.61%   |
| 5.4.0-54-generic         | 4         | 0.61%   |
| 5.4.0-52-generic         | 4         | 0.61%   |
| 5.18.10-76051810-generic | 4         | 0.61%   |
| 5.15.0-48-generic        | 4         | 0.61%   |
| 5.13.0-30-generic        | 4         | 0.61%   |
| 5.11.0-40-generic        | 4         | 0.61%   |
| 5.11.0-37-generic        | 4         | 0.61%   |
| 5.11.0-35-generic        | 4         | 0.61%   |
| 5.10.88-std-def-alt1     | 4         | 0.61%   |
| 5.0.0-23-generic         | 4         | 0.61%   |
| 5.0.0-13-generic         | 4         | 0.61%   |
| 5.4.0-81-generic         | 3         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 125       | 20.06%  |
| 5.11.0  | 50        | 8.03%   |
| 4.15.0  | 43        | 6.9%    |
| 5.8.0   | 40        | 6.42%   |
| 5.3.0   | 37        | 5.94%   |
| 5.13.0  | 34        | 5.46%   |
| 5.15.0  | 33        | 5.3%    |
| 5.0.0   | 21        | 3.37%   |
| 5.16.7  | 13        | 2.09%   |
| 5.10.14 | 13        | 2.09%   |
| 5.10.0  | 13        | 2.09%   |
| 4.18.0  | 13        | 2.09%   |
| 4.19.0  | 11        | 1.77%   |
| 5.9.11  | 5         | 0.8%    |
| 5.10.88 | 5         | 0.8%    |
| 5.18.10 | 4         | 0.64%   |
| 5.11.12 | 4         | 0.64%   |
| 4.9.20  | 4         | 0.64%   |
| 5.8.18  | 3         | 0.48%   |
| 5.7.2   | 3         | 0.48%   |
| 5.3.18  | 3         | 0.48%   |
| 5.17.5  | 3         | 0.48%   |
| 5.15.5  | 3         | 0.48%   |
| 4.9.60  | 3         | 0.48%   |
| 5.9.16  | 2         | 0.32%   |
| 5.8.6   | 2         | 0.32%   |
| 5.8.16  | 2         | 0.32%   |
| 5.5.13  | 2         | 0.32%   |
| 5.4.77  | 2         | 0.32%   |
| 5.17.1  | 2         | 0.32%   |
| 5.15.32 | 2         | 0.32%   |
| 5.15.19 | 2         | 0.32%   |
| 5.15.16 | 2         | 0.32%   |
| 5.14.14 | 2         | 0.32%   |
| 5.14.10 | 2         | 0.32%   |
| 5.14.0  | 2         | 0.32%   |
| 5.12.4  | 2         | 0.32%   |
| 5.12.14 | 2         | 0.32%   |
| 5.10.70 | 2         | 0.32%   |
| 4.1.38  | 2         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 136       | 21.97%  |
| 5.11    | 61        | 9.85%   |
| 5.8     | 54        | 8.72%   |
| 5.15    | 50        | 8.08%   |
| 5.10    | 45        | 7.27%   |
| 5.3     | 43        | 6.95%   |
| 4.15    | 43        | 6.95%   |
| 5.13    | 39        | 6.3%    |
| 5.0     | 22        | 3.55%   |
| 5.16    | 19        | 3.07%   |
| 4.18    | 14        | 2.26%   |
| 5.9     | 12        | 1.94%   |
| 4.19    | 11        | 1.78%   |
| 4.9     | 9         | 1.45%   |
| 5.17    | 8         | 1.29%   |
| 5.14    | 8         | 1.29%   |
| 5.18    | 7         | 1.13%   |
| 5.12    | 7         | 1.13%   |
| 5.7     | 6         | 0.97%   |
| 5.6     | 6         | 0.97%   |
| 5.5     | 5         | 0.81%   |
| 5.19    | 4         | 0.65%   |
| 6.0     | 2         | 0.32%   |
| 4.1     | 2         | 0.32%   |
| 5.2     | 1         | 0.16%   |
| 4.20    | 1         | 0.16%   |
| 4.16    | 1         | 0.16%   |
| 4.10    | 1         | 0.16%   |
| 3.16    | 1         | 0.16%   |
| 3.10    | 1         | 0.16%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 517       | 93.49%  |
| i686   | 36        | 6.51%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| GNOME               | 253       | 43.7%   |
| KDE5                | 83        | 14.34%  |
| Unknown             | 76        | 13.13%  |
| XFCE                | 54        | 9.33%   |
| X-Cinnamon          | 42        | 7.25%   |
| KDE                 | 19        | 3.28%   |
| MATE                | 18        | 3.11%   |
| KDE4                | 6         | 1.04%   |
| Budgie              | 5         | 0.86%   |
| Unity               | 4         | 0.69%   |
| Pantheon            | 3         | 0.52%   |
| LXQt                | 3         | 0.52%   |
| Cinnamon            | 3         | 0.52%   |
| LXDE                | 2         | 0.35%   |
| i3                  | 2         | 0.35%   |
| GNOME Classic       | 2         | 0.35%   |
| openbox             | 1         | 0.17%   |
| Deepin              | 1         | 0.17%   |
| awesome             | 1         | 0.17%   |
| /usr/bin/startxfce4 | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 460       | 80.56%  |
| Wayland | 58        | 10.16%  |
| Unknown | 41        | 7.18%   |
| Tty     | 12        | 2.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 333       | 58.01%  |
| SDDM    | 70        | 12.2%   |
| GDM     | 58        | 10.1%   |
| LightDM | 49        | 8.54%   |
| GDM3    | 38        | 6.62%   |
| TDM     | 16        | 2.79%   |
| KDM     | 6         | 1.05%   |
| XDM     | 2         | 0.35%   |
| SLiM    | 1         | 0.17%   |
| Ly      | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 310       | 54.58%  |
| el_GR   | 151       | 26.58%  |
| Unknown | 72        | 12.68%  |
| en_GB   | 13        | 2.29%   |
| de_DE   | 5         | 0.88%   |
| C       | 5         | 0.88%   |
| POSIX   | 2         | 0.35%   |
| fr_FR   | 2         | 0.35%   |
| ru_RU   | 1         | 0.18%   |
| pl_PL   | 1         | 0.18%   |
| it_IT   | 1         | 0.18%   |
| hu_HU   | 1         | 0.18%   |
| en_IE   | 1         | 0.18%   |
| en_AG   | 1         | 0.18%   |
| C.UTF8  | 1         | 0.18%   |
| anp_IN  | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 309       | 54.69%  |
| EFI  | 256       | 45.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 451       | 79.82%  |
| Btrfs   | 42        | 7.43%   |
| Overlay | 39        | 6.9%    |
| Unknown | 28        | 4.96%   |
| Zfs     | 3         | 0.53%   |
| Tmpfs   | 1         | 0.18%   |
| F2fs    | 1         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 363       | 64.13%  |
| GPT     | 137       | 24.2%   |
| MBR     | 66        | 11.66%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 484       | 85.97%  |
| Yes       | 79        | 14.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 398       | 71.45%  |
| Yes       | 159       | 28.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 129       | 23.33%  |
| Lenovo                  | 102       | 18.44%  |
| Dell                    | 90        | 16.27%  |
| ASUSTek Computer        | 43        | 7.78%   |
| Acer                    | 43        | 7.78%   |
| Toshiba                 | 28        | 5.06%   |
| Sony                    | 25        | 4.52%   |
| Fujitsu                 | 10        | 1.81%   |
| Fujitsu Siemens         | 9         | 1.63%   |
| Apple                   | 9         | 1.63%   |
| Notebook                | 6         | 1.08%   |
| Unknown                 | 6         | 1.08%   |
| HUAWEI                  | 5         | 0.9%    |
| Clevo                   | 5         | 0.9%    |
| Samsung Electronics     | 4         | 0.72%   |
| MSI                     | 4         | 0.72%   |
| Teclast                 | 3         | 0.54%   |
| Pegatron                | 3         | 0.54%   |
| Intel                   | 2         | 0.36%   |
| Insyde                  | 2         | 0.36%   |
| Info Quest Technologies | 2         | 0.36%   |
| Hampoo                  | 2         | 0.36%   |
| E-shop.gr               | 2         | 0.36%   |
| Chuwi                   | 2         | 0.36%   |
| VERO                    | 1         | 0.18%   |
| Valve                   | 1         | 0.18%   |
| TUXEDO                  | 1         | 0.18%   |
| Schenker                | 1         | 0.18%   |
| Quest                   | 1         | 0.18%   |
| Purism                  | 1         | 0.18%   |
| PLAISIO COMPUTERS SA    | 1         | 0.18%   |
| Plaisio                 | 1         | 0.18%   |
| PC Specialist           | 1         | 0.18%   |
| Packard Bell            | 1         | 0.18%   |
| Medion                  | 1         | 0.18%   |
| IBM                     | 1         | 0.18%   |
| Google                  | 1         | 0.18%   |
| Dynabook                | 1         | 0.18%   |
| Compal                  | 1         | 0.18%   |
| ARIMA                   | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 11        | 1.99%   |
| HP Pavilion g6                         | 8         | 1.45%   |
| HP Notebook                            | 7         | 1.27%   |
| Dell Inspiron 3542                     | 5         | 0.9%    |
| HP G62                                 | 4         | 0.72%   |
| HP 255 G7 Notebook PC                  | 4         | 0.72%   |
| Dell Inspiron 5567                     | 4         | 0.72%   |
| Dell Inspiron 3537                     | 4         | 0.72%   |
| Notebook W54_W94_W955TU,-T,-C          | 3         | 0.54%   |
| Lenovo G510 20238                      | 3         | 0.54%   |
| HP Pavilion dv7                        | 3         | 0.54%   |
| HP 255 G8 Notebook PC                  | 3         | 0.54%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA | 3         | 0.54%   |
| Apple MacBookPro8,1                    | 3         | 0.54%   |
| Acer Aspire A315-51                    | 3         | 0.54%   |
| Acer Aspire A315-31                    | 3         | 0.54%   |
| Toshiba Satellite C850D-119            | 2         | 0.36%   |
| Toshiba Satellite C850D-118            | 2         | 0.36%   |
| Toshiba NB100                          | 2         | 0.36%   |
| Teclast F15                            | 2         | 0.36%   |
| Sony VPCM13M1E                         | 2         | 0.36%   |
| Sony VPCCB2S1E                         | 2         | 0.36%   |
| Pegatron A15                           | 2         | 0.36%   |
| Lenovo Legion Y530-15ICH 81FV          | 2         | 0.36%   |
| Lenovo IdeaPad S540-14API 81NH         | 2         | 0.36%   |
| Lenovo IdeaPad L340-17API 81LY         | 2         | 0.36%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK  | 2         | 0.36%   |
| Lenovo IdeaPad 100-15IBD 80QQ          | 2         | 0.36%   |
| Lenovo G700 20251                      | 2         | 0.36%   |
| Lenovo G70-35 80Q5                     | 2         | 0.36%   |
| Lenovo G50-70 20351                    | 2         | 0.36%   |
| Lenovo G40-30 80FY                     | 2         | 0.36%   |
| Lenovo B590 20208                      | 2         | 0.36%   |
| Intel Calistoga & ICH7M Chipset        | 2         | 0.36%   |
| Insyde CherryTrail                     | 2         | 0.36%   |
| HUAWEI NBLK-WAX9X                      | 2         | 0.36%   |
| HP ProBook 6560b                       | 2         | 0.36%   |
| HP ProBook 4530s                       | 2         | 0.36%   |
| HP Pavilion x2 Detachable              | 2         | 0.36%   |
| HP Pavilion Notebook                   | 2         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 38        | 6.87%   |
| Lenovo ThinkPad       | 34        | 6.15%   |
| Acer Aspire           | 34        | 6.15%   |
| Lenovo IdeaPad        | 32        | 5.79%   |
| HP Pavilion           | 32        | 5.79%   |
| Dell Latitude         | 28        | 5.06%   |
| Toshiba Satellite     | 24        | 4.34%   |
| HP EliteBook          | 12        | 2.17%   |
| HP Compaq             | 12        | 2.17%   |
| HP 255                | 12        | 2.17%   |
| HP Laptop             | 11        | 1.99%   |
| ASUS VivoBook         | 11        | 1.99%   |
| Unknown               | 11        | 1.99%   |
| HP ProBook            | 9         | 1.63%   |
| Fujitsu LIFEBOOK      | 8         | 1.45%   |
| HP Notebook           | 7         | 1.27%   |
| Fujitsu Siemens AMILO | 7         | 1.27%   |
| Dell Precision        | 7         | 1.27%   |
| HP 250                | 5         | 0.9%    |
| Dell XPS              | 5         | 0.9%    |
| Dell Vostro           | 5         | 0.9%    |
| ASUS TUF              | 5         | 0.9%    |
| HP G62                | 4         | 0.72%   |
| Apple MacBookPro8     | 4         | 0.72%   |
| Notebook W54          | 3         | 0.54%   |
| Lenovo Legion         | 3         | 0.54%   |
| Lenovo G510           | 3         | 0.54%   |
| HP Presario           | 3         | 0.54%   |
| HP ENVY               | 3         | 0.54%   |
| Toshiba NB100         | 2         | 0.36%   |
| Teclast F15           | 2         | 0.36%   |
| Sony VPCM13M1E        | 2         | 0.36%   |
| Sony VPCCB2S1E        | 2         | 0.36%   |
| Pegatron A15          | 2         | 0.36%   |
| Notebook W65          | 2         | 0.36%   |
| MSI GE70              | 2         | 0.36%   |
| Lenovo ThinkBook      | 2         | 0.36%   |
| Lenovo G700           | 2         | 0.36%   |
| Lenovo G70-35         | 2         | 0.36%   |
| Lenovo G50-70         | 2         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 55        | 9.95%   |
| 2013 | 46        | 8.32%   |
| 2011 | 45        | 8.14%   |
| 2012 | 41        | 7.41%   |
| 2017 | 40        | 7.23%   |
| 2020 | 39        | 7.05%   |
| 2008 | 38        | 6.87%   |
| 2018 | 36        | 6.51%   |
| 2014 | 34        | 6.15%   |
| 2009 | 32        | 5.79%   |
| 2010 | 30        | 5.42%   |
| 2015 | 29        | 5.24%   |
| 2016 | 26        | 4.7%    |
| 2007 | 25        | 4.52%   |
| 2021 | 19        | 3.44%   |
| 2006 | 8         | 1.45%   |
| 2005 | 6         | 1.08%   |
| 2022 | 2         | 0.36%   |
| 2004 | 2         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 553       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 497       | 89.23%  |
| Enabled  | 60        | 10.77%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 551       | 99.64%  |
| Yes  | 2         | 0.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 162       | 28.98%  |
| 4.01-8.0    | 151       | 27.01%  |
| 8.01-16.0   | 89        | 15.92%  |
| 1.01-2.0    | 55        | 9.84%   |
| 16.01-24.0  | 54        | 9.66%   |
| 2.01-3.0    | 19        | 3.4%    |
| 32.01-64.0  | 14        | 2.5%    |
| 0.51-1.0    | 12        | 2.15%   |
| 24.01-32.0  | 2         | 0.36%   |
| 64.01-256.0 | 1         | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 259       | 42.81%  |
| 2.01-3.0   | 152       | 25.12%  |
| 0.51-1.0   | 63        | 10.41%  |
| 3.01-4.0   | 57        | 9.42%   |
| 4.01-8.0   | 54        | 8.93%   |
| 8.01-16.0  | 9         | 1.49%   |
| 0.01-0.5   | 9         | 1.49%   |
| 24.01-32.0 | 1         | 0.17%   |
| 16.01-24.0 | 1         | 0.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 414       | 73.27%  |
| 2      | 132       | 23.36%  |
| 3      | 11        | 1.95%   |
| 0      | 6         | 1.06%   |
| 6      | 1         | 0.18%   |
| 4      | 1         | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 304       | 54.77%  |
| Yes       | 251       | 45.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 474       | 85.56%  |
| No        | 80        | 14.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 546       | 98.56%  |
| No        | 8         | 1.44%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 417       | 74.33%  |
| No        | 144       | 25.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Greece  | 553       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Athens       | 287       | 48.64%  |
| Thessaloniki | 94        | 15.93%  |
| Heraklion    | 19        | 3.22%   |
| Pátrai      | 13        | 2.2%    |
| Chalcis      | 13        | 2.2%    |
| Kavala       | 9         | 1.53%   |
| Katerini     | 8         | 1.36%   |
| Volos        | 7         | 1.19%   |
| Trikala      | 6         | 1.02%   |
| Rhodes       | 4         | 0.68%   |
| Piraeus      | 4         | 0.68%   |
| Larissa      | 4         | 0.68%   |
| Ioannina     | 4         | 0.68%   |
| Fira         | 4         | 0.68%   |
| Corinth      | 4         | 0.68%   |
| Corfu        | 4         | 0.68%   |
| Chalandri    | 4         | 0.68%   |
| Lamia        | 3         | 0.51%   |
| Koropi       | 3         | 0.51%   |
| Kilkis       | 3         | 0.51%   |
| Kalamata     | 3         | 0.51%   |
| Drama        | 3         | 0.51%   |
| Chania       | 3         | 0.51%   |
| Ano Liosia   | 3         | 0.51%   |
| Agrinio      | 3         | 0.51%   |
| Xanthi       | 2         | 0.34%   |
| Veroia       | 2         | 0.34%   |
| Serres       | 2         | 0.34%   |
| Poros        | 2         | 0.34%   |
| Paros        | 2         | 0.34%   |
| Melissia     | 2         | 0.34%   |
| Lefkada      | 2         | 0.34%   |
| Komotini     | 2         | 0.34%   |
| Kallithea    | 2         | 0.34%   |
| Grevena      | 2         | 0.34%   |
| Elateia      | 2         | 0.34%   |
| Zografou     | 1         | 0.17%   |
| Zografos     | 1         | 0.17%   |
| Zaros        | 1         | 0.17%   |
| Zakynthos    | 1         | 0.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 89        | 115    | 13.03%  |
| Samsung Electronics            | 84        | 99     | 12.3%   |
| Seagate                        | 80        | 98     | 11.71%  |
| Toshiba                        | 65        | 79     | 9.52%   |
| SanDisk                        | 49        | 58     | 7.17%   |
| Kingston                       | 43        | 55     | 6.3%    |
| Unknown                        | 36        | 53     | 5.27%   |
| SK hynix                       | 30        | 40     | 4.39%   |
| Hitachi                        | 24        | 24     | 3.51%   |
| Patriot                        | 23        | 24     | 3.37%   |
| HGST                           | 19        | 22     | 2.78%   |
| Fujitsu                        | 16        | 17     | 2.34%   |
| Micron Technology              | 15        | 18     | 2.2%    |
| Crucial                        | 13        | 14     | 1.9%    |
| Intenso                        | 12        | 15     | 1.76%   |
| Intel                          | 12        | 15     | 1.76%   |
| Team                           | 7         | 12     | 1.02%   |
| KIOXIA                         | 6         | 6      | 0.88%   |
| JMicron Technology             | 5         | 5      | 0.73%   |
| OCZ                            | 4         | 4      | 0.59%   |
| Transcend                      | 3         | 3      | 0.44%   |
| Teclast                        | 3         | 3      | 0.44%   |
| Micron/Crucial Technology      | 3         | 3      | 0.44%   |
| Gigabyte Technology            | 3         | 3      | 0.44%   |
| SPCC                           | 2         | 3      | 0.29%   |
| Phison                         | 2         | 2      | 0.29%   |
| Mushkin                        | 2         | 2      | 0.29%   |
| Apple                          | 2         | 2      | 0.29%   |
| Apacer                         | 2         | 2      | 0.29%   |
| Unknown                        | 2         | 2      | 0.29%   |
| XPG                            | 1         | 1      | 0.15%   |
| WDC WDS                        | 1         | 1      | 0.15%   |
| Verbatim                       | 1         | 1      | 0.15%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.15%   |
| SSSTC                          | 1         | 1      | 0.15%   |
| Solid State Storage Technology | 1         | 1      | 0.15%   |
| SMI                            | 1         | 1      | 0.15%   |
| PNY                            | 1         | 1      | 0.15%   |
| Plextor                        | 1         | 1      | 0.15%   |
| Phison Electronics             | 1         | 1      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 14        | 2%      |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 14        | 2%      |
| SK hynix NVMe SSD Drive 256GB          | 11        | 1.57%   |
| Samsung SSD 860 EVO 500GB              | 11        | 1.57%   |
| Toshiba MQ01ABF050 500GB               | 9         | 1.28%   |
| Seagate ST500LT012-1DG142 500GB        | 8         | 1.14%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 8         | 1.14%   |
| Seagate ST1000LM035-1RK172 1TB         | 8         | 1.14%   |
| SanDisk NVMe SSD Drive 256GB           | 8         | 1.14%   |
| Samsung SSD 860 EVO 250GB              | 8         | 1.14%   |
| Unknown MMC Card  64GB                 | 7         | 1%      |
| Toshiba MQ01ABD100 1TB                 | 7         | 1%      |
| Patriot Burst 120GB SSD                | 7         | 1%      |
| Kingston SA400S37240G 240GB SSD        | 7         | 1%      |
| HGST HTS545050A7E680 500GB             | 7         | 1%      |
| Unknown MMC Card  128GB                | 6         | 0.86%   |
| SanDisk NVMe SSD Drive 512GB           | 5         | 0.71%   |
| Samsung SSD 850 EVO 500GB              | 5         | 0.71%   |
| Samsung SSD 850 EVO 250GB              | 5         | 0.71%   |
| Kingston SA400S37480G 480GB SSD        | 5         | 0.71%   |
| Kingston SA400S37120G 120GB SSD        | 5         | 0.71%   |
| HGST HTS721010A9E630 1TB               | 5         | 0.71%   |
| Fujitsu MHY2200BH 200GB                | 5         | 0.71%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 4         | 0.57%   |
| WDC WD10SPZX-60Z10T0 1TB               | 4         | 0.57%   |
| Toshiba MQ04ABF100 1TB                 | 4         | 0.57%   |
| Toshiba MQ01ABD050 500GB               | 4         | 0.57%   |
| Patriot Burst 480GB SSD                | 4         | 0.57%   |
| JMicron Generic 500GB                  | 4         | 0.57%   |
| Hitachi HTS545032B9A300 320GB          | 4         | 0.57%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 3         | 0.43%   |
| WDC WD10JPVX-75JC3T0 1TB               | 3         | 0.43%   |
| Unknown MMC Card  2GB                  | 3         | 0.43%   |
| Unknown MMC Card  16GB                 | 3         | 0.43%   |
| Seagate ST9500420AS 500GB              | 3         | 0.43%   |
| Seagate ST1000LM048-2E7172 1TB         | 3         | 0.43%   |
| SanDisk SDSSDA120G 120GB               | 3         | 0.43%   |
| SanDisk DF4032  32GB                   | 3         | 0.43%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3         | 0.43%   |
| Samsung NVMe SSD Drive 512GB           | 3         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 78        | 95     | 29.55%  |
| WDC                 | 65        | 80     | 24.62%  |
| Toshiba             | 46        | 58     | 17.42%  |
| Hitachi             | 24        | 24     | 9.09%   |
| HGST                | 19        | 22     | 7.2%    |
| Fujitsu             | 16        | 17     | 6.06%   |
| Samsung Electronics | 9         | 10     | 3.41%   |
| Intenso             | 3         | 4      | 1.14%   |
| Unknown             | 1         | 1      | 0.38%   |
| IBM/Hitachi         | 1         | 1      | 0.38%   |
| ASMT109x            | 1         | 1      | 0.38%   |
| Apple               | 1         | 1      | 0.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 54        | 62     | 21.77%  |
| Kingston            | 36        | 47     | 14.52%  |
| SanDisk             | 31        | 38     | 12.5%   |
| Patriot             | 23        | 24     | 9.27%   |
| WDC                 | 15        | 23     | 6.05%   |
| Crucial             | 11        | 12     | 4.44%   |
| Toshiba             | 10        | 11     | 4.03%   |
| Micron Technology   | 9         | 10     | 3.63%   |
| Intenso             | 8         | 10     | 3.23%   |
| Team                | 7         | 12     | 2.82%   |
| Intel               | 5         | 6      | 2.02%   |
| SK hynix            | 4         | 4      | 1.61%   |
| OCZ                 | 4         | 4      | 1.61%   |
| Transcend           | 3         | 3      | 1.21%   |
| Teclast             | 3         | 3      | 1.21%   |
| Gigabyte Technology | 3         | 3      | 1.21%   |
| SPCC                | 2         | 3      | 0.81%   |
| Mushkin             | 2         | 2      | 0.81%   |
| Apacer              | 2         | 2      | 0.81%   |
| WDC WDS             | 1         | 1      | 0.4%    |
| Verbatim            | 1         | 1      | 0.4%    |
| PNY                 | 1         | 1      | 0.4%    |
| Plextor             | 1         | 1      | 0.4%    |
| OCZ-AGIL            | 1         | 1      | 0.4%    |
| Netac               | 1         | 1      | 0.4%    |
| Leven               | 1         | 1      | 0.4%    |
| KIOXIA-EXCERIA      | 1         | 1      | 0.4%    |
| KingSpec            | 1         | 1      | 0.4%    |
| Hewlett-Packard     | 1         | 1      | 0.4%    |
| Emtec               | 1         | 2      | 0.4%    |
| Drevo               | 1         | 1      | 0.4%    |
| ASUS-PHISON         | 1         | 2      | 0.4%    |
| Apple               | 1         | 1      | 0.4%    |
| A-DATA Technology   | 1         | 1      | 0.4%    |
| Unknown             | 1         | 1      | 0.4%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 257       | 314    | 39.36%  |
| SSD     | 235       | 297    | 35.99%  |
| NVMe    | 117       | 150    | 17.92%  |
| MMC     | 38        | 60     | 5.82%   |
| Unknown | 6         | 7      | 0.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 439       | 594    | 71.5%   |
| NVMe | 115       | 146    | 18.73%  |
| MMC  | 38        | 60     | 6.19%   |
| SAS  | 22        | 28     | 3.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 371       | 478    | 77.45%  |
| 0.51-1.0   | 98        | 121    | 20.46%  |
| 1.01-2.0   | 9         | 11     | 1.88%   |
| 4.01-10.0  | 1         | 1      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 195       | 33.56%  |
| 251-500        | 135       | 23.24%  |
| 501-1000       | 67        | 11.53%  |
| 51-100         | 54        | 9.29%   |
| 1-20           | 44        | 7.57%   |
| 21-50          | 37        | 6.37%   |
| 1001-2000      | 28        | 4.82%   |
| Unknown        | 11        | 1.89%   |
| More than 3000 | 5         | 0.86%   |
| 2001-3000      | 5         | 0.86%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 255       | 42.79%  |
| 21-50          | 113       | 18.96%  |
| 51-100         | 72        | 12.08%  |
| 101-250        | 70        | 11.74%  |
| 251-500        | 41        | 6.88%   |
| 501-1000       | 17        | 2.85%   |
| 1001-2000      | 14        | 2.35%   |
| Unknown        | 11        | 1.85%   |
| More than 3000 | 3         | 0.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB                          | 4         | 4      | 12.12%  |
| WDC WD5000LPCX-24VHAT0 500GB                        | 1         | 1      | 3.03%   |
| WDC WD5000BPVT-60HXZT1 500GB                        | 1         | 1      | 3.03%   |
| WDC WD3200BEVT-26ZCT0 320GB                         | 1         | 1      | 3.03%   |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 3.03%   |
| WDC WD1600BEVS-22RST0 160GB                         | 1         | 1      | 3.03%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 3.03%   |
| Toshiba MQ01ABD100M 1TB                             | 1         | 1      | 3.03%   |
| Toshiba MQ01ABD050 500GB                            | 1         | 3      | 3.03%   |
| SK hynix SC210 mSATA 256GB SSD                      | 1         | 1      | 3.03%   |
| SK hynix BC711 HFM256GD3JX013N 256GB                | 1         | 1      | 3.03%   |
| Seagate ST980811AS 80GB                             | 1         | 1      | 3.03%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 3.03%   |
| Seagate ST9160310AS 160GB                           | 1         | 1      | 3.03%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 3.03%   |
| Seagate ST320LT020-9YG142 320GB                     | 1         | 1      | 3.03%   |
| Seagate ST1000LM049-2GH172 1TB                      | 1         | 1      | 3.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 2      | 3.03%   |
| SanDisk SSD U100 128GB                              | 1         | 1      | 3.03%   |
| SanDisk SSD PLUS 240GB                              | 1         | 1      | 3.03%   |
| Samsung Electronics SSD 970 EVO 500GB               | 1         | 1      | 3.03%   |
| OCZ-AGIL ITY3 120GB SSD                             | 1         | 1      | 3.03%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 3.03%   |
| Kingston RBUSNS8180DS3128GJ 128GB SSD               | 1         | 1      | 3.03%   |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 3.03%   |
| Hitachi HTS723216L9A360 160GB                       | 1         | 1      | 3.03%   |
| Hitachi HTS545032B9A300 320GB                       | 1         | 1      | 3.03%   |
| Hitachi HTS543232A7A384 320GB                       | 1         | 1      | 3.03%   |
| Fujitsu MHT2080BH 80GB                              | 1         | 1      | 3.03%   |
| Crucial CT480M500SSD1 480GB                         | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 8      | 21.21%  |
| WDC                 | 5         | 5      | 15.15%  |
| Hitachi             | 4         | 4      | 12.12%  |
| HGST                | 4         | 4      | 12.12%  |
| Toshiba             | 3         | 5      | 9.09%   |
| SK hynix            | 2         | 2      | 6.06%   |
| SanDisk             | 2         | 2      | 6.06%   |
| Samsung Electronics | 1         | 1      | 3.03%   |
| OCZ-AGIL            | 1         | 1      | 3.03%   |
| Micron Technology   | 1         | 1      | 3.03%   |
| Kingston            | 1         | 1      | 3.03%   |
| Fujitsu             | 1         | 1      | 3.03%   |
| Crucial             | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 8      | 29.17%  |
| WDC     | 5         | 5      | 20.83%  |
| Hitachi | 4         | 4      | 16.67%  |
| HGST    | 4         | 4      | 16.67%  |
| Toshiba | 3         | 5      | 12.5%   |
| Fujitsu | 1         | 1      | 4.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 27     | 72.73%  |
| SSD  | 7         | 7      | 21.21%  |
| NVMe | 2         | 2      | 6.06%   |

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
| Detected | 386       | 568    | 66.44%  |
| Works    | 162       | 224    | 27.88%  |
| Malfunc  | 33        | 36     | 5.68%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 398       | 65.25%  |
| AMD                              | 85        | 13.93%  |
| SK hynix                         | 25        | 4.1%    |
| SanDisk                          | 22        | 3.61%   |
| Samsung Electronics              | 22        | 3.61%   |
| Toshiba America Info Systems     | 9         | 1.48%   |
| Kingston Technology Company      | 8         | 1.31%   |
| KIOXIA                           | 7         | 1.15%   |
| Micron Technology                | 6         | 0.98%   |
| Nvidia                           | 5         | 0.82%   |
| Micron/Crucial Technology        | 4         | 0.66%   |
| VIA Technologies                 | 3         | 0.49%   |
| Phison Electronics               | 3         | 0.49%   |
| Union Memory (Shenzhen)          | 2         | 0.33%   |
| Silicon Image                    | 2         | 0.33%   |
| JMicron Technology               | 2         | 0.33%   |
| Solid State Storage Technology   | 1         | 0.16%   |
| Silicon Integrated Systems [SiS] | 1         | 0.16%   |
| Seagate Technology               | 1         | 0.16%   |
| O2 Micro                         | 1         | 0.16%   |
| Lite-On Technology               | 1         | 0.16%   |
| ASMedia Technology               | 1         | 0.16%   |
| ADATA Technology                 | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 72        | 10.65%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 41        | 6.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 37        | 5.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 35        | 5.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 34        | 5.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 24        | 3.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 22        | 3.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 21        | 3.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 21        | 3.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 17        | 2.51%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 15        | 2.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 13        | 1.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 12        | 1.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 12        | 1.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 12        | 1.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 11        | 1.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 11        | 1.63%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 9         | 1.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 9         | 1.33%   |
| Intel Volume Management Device NVMe RAID Controller                              | 8         | 1.18%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 8         | 1.18%   |
| Samsung NVMe SSD Controller 980                                                  | 7         | 1.04%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 7         | 1.04%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 1.04%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 1.04%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 1.04%   |
| SK hynix Gold P31 SSD                                                            | 6         | 0.89%   |
| SK hynix BC511                                                                   | 6         | 0.89%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 6         | 0.89%   |
| Micron Non-Volatile memory controller                                            | 6         | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 0.89%   |
| SK hynix Non-Volatile memory controller                                          | 5         | 0.74%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 5         | 0.74%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 0.74%   |
| SanDisk PC SN520 NVMe SSD                                                        | 5         | 0.74%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 4         | 0.59%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 4         | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 420       | 64.62%  |
| NVMe | 118       | 18.15%  |
| IDE  | 81        | 12.46%  |
| RAID | 31        | 4.77%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 434       | 78.48%  |
| AMD          | 118       | 21.34%  |
| CentaurHauls | 1         | 0.18%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 13        | 2.35%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 11        | 1.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 1.45%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 8         | 1.45%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 1.27%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 7         | 1.27%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 7         | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.08%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 6         | 1.08%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 6         | 1.08%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 6         | 1.08%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 6         | 1.08%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 6         | 1.08%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 6         | 1.08%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 6         | 1.08%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 5         | 0.9%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 0.9%    |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 5         | 0.9%    |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 5         | 0.9%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 5         | 0.9%    |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 5         | 0.9%    |
| AMD E1-1200 APU with Radeon HD Graphics       | 5         | 0.9%    |
| Intel Pentium CPU N3540 @ 2.16GHz             | 4         | 0.72%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.72%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 0.72%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 4         | 0.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.72%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 4         | 0.72%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.72%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 4         | 0.72%   |
| Intel Core 2 Duo CPU T9600 @ 2.80GHz          | 4         | 0.72%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 4         | 0.72%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 0.72%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 4         | 0.72%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 3         | 0.54%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 3         | 0.54%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 0.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 107       | 19.35%  |
| Intel Core i7                  | 87        | 15.73%  |
| Intel Core 2 Duo               | 51        | 9.22%   |
| Intel Core i3                  | 50        | 9.04%   |
| Intel Celeron                  | 37        | 6.69%   |
| AMD Ryzen 5                    | 29        | 5.24%   |
| Intel Atom                     | 27        | 4.88%   |
| Intel Pentium                  | 20        | 3.62%   |
| Other                          | 19        | 3.44%   |
| AMD Ryzen 7                    | 14        | 2.53%   |
| AMD Ryzen 3                    | 11        | 1.99%   |
| AMD E1                         | 9         | 1.63%   |
| AMD A4                         | 9         | 1.63%   |
| AMD A6                         | 8         | 1.45%   |
| Intel Core 2                   | 7         | 1.27%   |
| AMD A10                        | 7         | 1.27%   |
| Intel Pentium Dual-Core        | 6         | 1.08%   |
| Intel Pentium Dual             | 6         | 1.08%   |
| Intel Celeron M                | 5         | 0.9%    |
| AMD A8                         | 5         | 0.9%    |
| Intel Pentium M                | 4         | 0.72%   |
| Intel Genuine                  | 4         | 0.72%   |
| Intel Celeron Dual-Core        | 4         | 0.72%   |
| AMD Ryzen 7 PRO                | 3         | 0.54%   |
| AMD Athlon                     | 3         | 0.54%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.36%   |
| AMD Turion                     | 2         | 0.36%   |
| AMD Sempron                    | 2         | 0.36%   |
| AMD E                          | 2         | 0.36%   |
| AMD Athlon 64 X2               | 2         | 0.36%   |
| Intel Pentium 4                | 1         | 0.18%   |
| Intel Core m3                  | 1         | 0.18%   |
| Intel Core Duo                 | 1         | 0.18%   |
| Intel Core 2 Extreme           | 1         | 0.18%   |
| CentaurHauls VIA C7            | 1         | 0.18%   |
| AMD V140                       | 1         | 0.18%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.18%   |
| AMD Turion 64 Mobile           | 1         | 0.18%   |
| AMD Ryzen 5 PRO                | 1         | 0.18%   |
| AMD E2                         | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 332       | 60.04%  |
| 4      | 155       | 28.03%  |
| 1      | 32        | 5.79%   |
| 6      | 23        | 4.16%   |
| 8      | 11        | 1.99%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 553       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 334       | 60.4%   |
| 1      | 218       | 39.42%  |
| 8      | 1         | 0.18%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 520       | 93.53%  |
| 32-bit         | 24        | 4.32%   |
| Unknown        | 12        | 2.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 110       | 19.23%  |
| 0x206a7    | 42        | 7.34%   |
| 0x306a9    | 28        | 4.9%    |
| 0x40651    | 23        | 4.02%   |
| 0x1067a    | 21        | 3.67%   |
| 0x306c3    | 18        | 3.15%   |
| 0x806ea    | 17        | 2.97%   |
| 0x6fd      | 16        | 2.8%    |
| 0x08108102 | 15        | 2.62%   |
| 0x806e9    | 14        | 2.45%   |
| 0x30678    | 13        | 2.27%   |
| 0x10676    | 13        | 2.27%   |
| 0x306d4    | 12        | 2.1%    |
| 0x08108109 | 12        | 2.1%    |
| 0x906ea    | 11        | 1.92%   |
| 0x806c1    | 10        | 1.75%   |
| 0x506c9    | 10        | 1.75%   |
| 0x106c2    | 10        | 1.75%   |
| 0x806ec    | 9         | 1.57%   |
| 0x406c4    | 9         | 1.57%   |
| 0x406c3    | 9         | 1.57%   |
| 0x20655    | 9         | 1.57%   |
| 0x20652    | 8         | 1.4%    |
| 0x406e3    | 7         | 1.22%   |
| 0x05000119 | 7         | 1.22%   |
| 0x6d8      | 6         | 1.05%   |
| 0x08600106 | 5         | 0.87%   |
| 0x06006705 | 5         | 0.87%   |
| 0x906e9    | 4         | 0.7%    |
| 0x706e5    | 4         | 0.7%    |
| 0x706a1    | 4         | 0.7%    |
| 0x6fb      | 4         | 0.7%    |
| 0x6f6      | 4         | 0.7%    |
| 0x6ec      | 4         | 0.7%    |
| 0x08600104 | 4         | 0.7%    |
| 0x0810100b | 4         | 0.7%    |
| 0x03000027 | 4         | 0.7%    |
| 0x806eb    | 3         | 0.52%   |
| 0x506e3    | 3         | 0.52%   |
| 0x106e5    | 3         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 71        | 12.84%  |
| SandyBridge     | 48        | 8.68%   |
| Haswell         | 47        | 8.5%    |
| Penryn          | 43        | 7.78%   |
| IvyBridge       | 35        | 6.33%   |
| Core            | 35        | 6.33%   |
| Zen+            | 33        | 5.97%   |
| Silvermont      | 33        | 5.97%   |
| Westmere        | 21        | 3.8%    |
| Skylake         | 15        | 2.71%   |
| TigerLake       | 14        | 2.53%   |
| Bonnell         | 14        | 2.53%   |
| Zen 2           | 13        | 2.35%   |
| P6              | 13        | 2.35%   |
| Excavator       | 13        | 2.35%   |
| Broadwell       | 13        | 2.35%   |
| Goldmont        | 10        | 1.81%   |
| Bobcat          | 10        | 1.81%   |
| Puma            | 9         | 1.63%   |
| Zen             | 8         | 1.45%   |
| Zen 3           | 6         | 1.08%   |
| IceLake         | 6         | 1.08%   |
| Goldmont plus   | 6         | 1.08%   |
| Piledriver      | 5         | 0.9%    |
| K8 Hammer       | 5         | 0.9%    |
| K8 & K10 hybrid | 5         | 0.9%    |
| K10 Llano       | 5         | 0.9%    |
| CometLake       | 5         | 0.9%    |
| Unknown         | 5         | 0.9%    |
| Nehalem         | 3         | 0.54%   |
| K10             | 2         | 0.36%   |
| NetBurst        | 1         | 0.18%   |
| Jaguar          | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 362       | 53.55%  |
| AMD                              | 178       | 26.33%  |
| Nvidia                           | 132       | 19.53%  |
| VIA Technologies                 | 3         | 0.44%   |
| Silicon Integrated Systems [SiS] | 1         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 42        | 5.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 34        | 4.68%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 31        | 4.27%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 24        | 3.31%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 20        | 2.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 2.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 2.62%   |
| Intel UHD Graphics 620                                                                   | 17        | 2.34%   |
| Intel HD Graphics 620                                                                    | 17        | 2.34%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 16        | 2.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 15        | 2.07%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 15        | 2.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 1.93%   |
| AMD Renoir                                                                               | 13        | 1.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 1.65%   |
| Intel HD Graphics 5500                                                                   | 12        | 1.65%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 1.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 1.65%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.24%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 9         | 1.24%   |
| Intel HD Graphics 500                                                                    | 9         | 1.24%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 1.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 1.1%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 8         | 1.1%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 1.1%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 8         | 1.1%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 7         | 0.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 0.96%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 7         | 0.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.83%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 6         | 0.83%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 6         | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.69%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 0.69%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 5         | 0.69%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.69%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 5         | 0.69%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 5         | 0.69%   |
| Intel HD Graphics 530                                                                    | 5         | 0.69%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 5         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 244       | 43.96%  |
| 1 x AMD        | 124       | 22.34%  |
| Intel + Nvidia | 87        | 15.68%  |
| 1 x Nvidia     | 39        | 7.03%   |
| Intel + AMD    | 31        | 5.59%   |
| 2 x AMD        | 18        | 3.24%   |
| AMD + Nvidia   | 5         | 0.9%    |
| 1 x VIA        | 3         | 0.54%   |
| Other          | 1         | 0.18%   |
| 2 x Nvidia     | 1         | 0.18%   |
| 2 x Intel      | 1         | 0.18%   |
| 1 x SiS        | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 488       | 87.61%  |
| Proprietary | 51        | 9.16%   |
| Unknown     | 18        | 3.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 306       | 53.78%  |
| 0.01-0.5   | 96        | 16.87%  |
| 1.01-2.0   | 83        | 14.59%  |
| 0.51-1.0   | 42        | 7.38%   |
| 3.01-4.0   | 35        | 6.15%   |
| 5.01-6.0   | 6         | 1.05%   |
| 2.01-3.0   | 1         | 0.18%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 101       | 17.41%  |
| AU Optronics            | 100       | 17.24%  |
| Chimei Innolux          | 77        | 13.28%  |
| BOE                     | 77        | 13.28%  |
| Samsung Electronics     | 71        | 12.24%  |
| Chi Mei Optoelectronics | 22        | 3.79%   |
| Goldstar                | 19        | 3.28%   |
| LG Philips              | 15        | 2.59%   |
| Dell                    | 14        | 2.41%   |
| Lenovo                  | 11        | 1.9%    |
| Apple                   | 9         | 1.55%   |
| CPT                     | 7         | 1.21%   |
| Sharp                   | 6         | 1.03%   |
| Sony                    | 5         | 0.86%   |
| PANDA                   | 5         | 0.86%   |
| HannStar                | 5         | 0.86%   |
| AOC                     | 5         | 0.86%   |
| InfoVision              | 4         | 0.69%   |
| Vestel Elektronik       | 3         | 0.52%   |
| Quanta Display          | 3         | 0.52%   |
| Philips                 | 2         | 0.34%   |
| Iiyama                  | 2         | 0.34%   |
| Hewlett-Packard         | 2         | 0.34%   |
| CSO                     | 2         | 0.34%   |
| ZLX                     | 1         | 0.17%   |
| TSL                     | 1         | 0.17%   |
| Toshiba                 | 1         | 0.17%   |
| Panasonic               | 1         | 0.17%   |
| Nvidia                  | 1         | 0.17%   |
| LPL                     | 1         | 0.17%   |
| LGD                     | 1         | 0.17%   |
| JRY                     | 1         | 0.17%   |
| InnoLux Display         | 1         | 0.17%   |
| Eizo                    | 1         | 0.17%   |
| BenQ                    | 1         | 0.17%   |
| ASUSTek Computer        | 1         | 0.17%   |
| ANX                     | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 11        | 1.88%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 1.37%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 7         | 1.2%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 7         | 1.2%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 6         | 1.03%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 6         | 1.03%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 5         | 0.86%   |
| CPT LCD Monitor CPT1415 1280x800 331x207mm 15.4-inch                     | 5         | 0.86%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 4         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 4         | 0.68%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 4         | 0.68%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 4         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 4         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 4         | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.68%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 4         | 0.68%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 3         | 0.51%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch        | 3         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 3         | 0.51%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 700x390mm 31.5-inch    | 3         | 0.51%   |
| LG Display LCD Monitor LGD0484 1366x768 344x194mm 15.5-inch              | 3         | 0.51%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 3         | 0.51%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.51%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch              | 3         | 0.51%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 3         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 3         | 0.51%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 3         | 0.51%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 3         | 0.51%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 3         | 0.51%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO333C 1366x768 309x173mm 13.9-inch            | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 3         | 0.51%   |
| Sony TV SNY7001 1920x1080                                                | 2         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 210       | 37.97%  |
| 1366x768 (WXGA)    | 197       | 35.62%  |
| 1280x800 (WXGA)    | 49        | 8.86%   |
| 1600x900 (HD+)     | 24        | 4.34%   |
| 1440x900 (WXGA+)   | 12        | 2.17%   |
| 3840x2160 (4K)     | 11        | 1.99%   |
| 1024x600           | 9         | 1.63%   |
| 2560x1440 (QHD)    | 8         | 1.45%   |
| 1920x1200 (WUXGA)  | 6         | 1.08%   |
| 1280x1024 (SXGA)   | 5         | 0.9%    |
| 1024x768 (XGA)     | 5         | 0.9%    |
| 1360x768           | 3         | 0.54%   |
| 2160x1440          | 2         | 0.36%   |
| 1680x1050 (WSXGA+) | 2         | 0.36%   |
| 1600x1200          | 2         | 0.36%   |
| 800x1280           | 1         | 0.18%   |
| 3200x1800 (QHD+)   | 1         | 0.18%   |
| 2880x1800          | 1         | 0.18%   |
| 2624x900           | 1         | 0.18%   |
| 2560x1600          | 1         | 0.18%   |
| 2560x1080          | 1         | 0.18%   |
| 1680x945           | 1         | 0.18%   |
| 1024x576           | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 303       | 52.15%  |
| 13      | 64        | 11.02%  |
| 14      | 51        | 8.78%   |
| 17      | 44        | 7.57%   |
| 21      | 17        | 2.93%   |
| 27      | 16        | 2.75%   |
| 12      | 11        | 1.89%   |
| 11      | 11        | 1.89%   |
| 23      | 10        | 1.72%   |
| 10      | 10        | 1.72%   |
| 24      | 7         | 1.2%    |
| Unknown | 7         | 1.2%    |
| 84      | 4         | 0.69%   |
| 18      | 4         | 0.69%   |
| 54      | 3         | 0.52%   |
| 8       | 3         | 0.52%   |
| 72      | 2         | 0.34%   |
| 33      | 2         | 0.34%   |
| 31      | 2         | 0.34%   |
| 22      | 2         | 0.34%   |
| 20      | 2         | 0.34%   |
| 16      | 2         | 0.34%   |
| 49      | 1         | 0.17%   |
| 34      | 1         | 0.17%   |
| 25      | 1         | 0.17%   |
| 19      | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 391       | 67.76%  |
| 201-300     | 59        | 10.23%  |
| 351-400     | 46        | 7.97%   |
| 501-600     | 31        | 5.37%   |
| 401-500     | 24        | 4.16%   |
| Unknown     | 7         | 1.21%   |
| 1501-2000   | 6         | 1.04%   |
| 1001-1500   | 4         | 0.69%   |
| 701-800     | 3         | 0.52%   |
| 601-700     | 3         | 0.52%   |
| 101-200     | 3         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 435       | 83.02%  |
| 16/10   | 68        | 12.98%  |
| 4/3     | 7         | 1.34%   |
| 5/4     | 5         | 0.95%   |
| Unknown | 4         | 0.76%   |
| 3/2     | 3         | 0.57%   |
| 21/9    | 1         | 0.19%   |
| 0.62    | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 301       | 51.9%   |
| 81-90          | 94        | 16.21%  |
| 201-250        | 32        | 5.52%   |
| 121-130        | 32        | 5.52%   |
| 71-80          | 21        | 3.62%   |
| 301-350        | 16        | 2.76%   |
| 61-70          | 11        | 1.9%    |
| 51-60          | 11        | 1.9%    |
| More than 1000 | 10        | 1.72%   |
| 41-50          | 10        | 1.72%   |
| 131-140        | 9         | 1.55%   |
| Unknown        | 7         | 1.21%   |
| 151-200        | 6         | 1.03%   |
| 141-150        | 6         | 1.03%   |
| 351-500        | 5         | 0.86%   |
| 1-40           | 3         | 0.52%   |
| 251-300        | 2         | 0.34%   |
| 111-120        | 2         | 0.34%   |
| 91-100         | 2         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 209       | 36.54%  |
| 101-120       | 206       | 36.01%  |
| 51-100        | 116       | 20.28%  |
| 161-240       | 21        | 3.67%   |
| 1-50          | 7         | 1.22%   |
| Unknown       | 7         | 1.22%   |
| More than 240 | 6         | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 478       | 84.3%   |
| 2     | 65        | 11.46%  |
| 0     | 18        | 3.17%   |
| 3     | 6         | 1.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 329       | 35.92%  |
| Intel                                 | 246       | 26.86%  |
| Qualcomm Atheros                      | 140       | 15.28%  |
| Broadcom                              | 72        | 7.86%   |
| Marvell Technology Group              | 23        | 2.51%   |
| Broadcom Limited                      | 19        | 2.07%   |
| Ralink                                | 15        | 1.64%   |
| TP-Link                               | 9         | 0.98%   |
| Ralink Technology                     | 6         | 0.66%   |
| Qualcomm Atheros Communications       | 4         | 0.44%   |
| Nvidia                                | 4         | 0.44%   |
| MediaTek                              | 4         | 0.44%   |
| Ericsson Business Mobile Networks     | 4         | 0.44%   |
| Dell                                  | 4         | 0.44%   |
| Sierra Wireless                       | 3         | 0.33%   |
| JMicron Technology                    | 3         | 0.33%   |
| Huawei Technologies                   | 3         | 0.33%   |
| Hewlett-Packard                       | 3         | 0.33%   |
| VIA Technologies                      | 2         | 0.22%   |
| NetGear                               | 2         | 0.22%   |
| Edimax Technology                     | 2         | 0.22%   |
| D-Link                                | 2         | 0.22%   |
| Xiaomi                                | 1         | 0.11%   |
| Toshiba                               | 1         | 0.11%   |
| Sitecom Europe                        | 1         | 0.11%   |
| Silicon Integrated Systems [SiS]      | 1         | 0.11%   |
| Samsung Electronics                   | 1         | 0.11%   |
| Linksys                               | 1         | 0.11%   |
| InProComm                             | 1         | 0.11%   |
| Google                                | 1         | 0.11%   |
| Fujitsu Siemens Computers             | 1         | 0.11%   |
| DisplayLink                           | 1         | 0.11%   |
| Belkin Components                     | 1         | 0.11%   |
| Attansic Technology                   | 1         | 0.11%   |
| ASUSTek Computer                      | 1         | 0.11%   |
| ASIX Electronics                      | 1         | 0.11%   |
| AMD                                   | 1         | 0.11%   |
| Accton Technology                     | 1         | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 167       | 15.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 103       | 9.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 2.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 26        | 2.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 24        | 2.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 23        | 2.12%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 23        | 2.12%   |
| Intel Wireless 8265 / 8275                                              | 22        | 2.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 19        | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 1.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 17        | 1.56%   |
| Broadcom BCM43142 802.11b/g/n                                           | 17        | 1.56%   |
| Intel Wireless 7260                                                     | 16        | 1.47%   |
| Intel Wireless 3165                                                     | 16        | 1.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 15        | 1.38%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 1.2%    |
| Intel Wi-Fi 6 AX200                                                     | 13        | 1.2%    |
| Intel Wi-Fi 6 AX201                                                     | 12        | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 1.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 11        | 1.01%   |
| Intel Wireless 7265                                                     | 10        | 0.92%   |
| Intel WiFi Link 5100                                                    | 10        | 0.92%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 10        | 0.92%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 10        | 0.92%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 9         | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 9         | 0.83%   |
| Intel Wireless 3160                                                     | 9         | 0.83%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.74%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.74%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 7         | 0.64%   |
| Intel Ethernet Connection I217-LM                                       | 7         | 0.64%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 0.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 0.55%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 6         | 0.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 0.55%   |
| Intel 82567LM Gigabit Network Connection                                | 6         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 235       | 40.17%  |
| Qualcomm Atheros                      | 122       | 20.85%  |
| Realtek Semiconductor                 | 111       | 18.97%  |
| Broadcom                              | 52        | 8.89%   |
| Ralink                                | 15        | 2.56%   |
| Broadcom Limited                      | 9         | 1.54%   |
| TP-Link                               | 8         | 1.37%   |
| Ralink Technology                     | 6         | 1.03%   |
| Qualcomm Atheros Communications       | 4         | 0.68%   |
| Sierra Wireless                       | 3         | 0.51%   |
| MediaTek                              | 3         | 0.51%   |
| NetGear                               | 2         | 0.34%   |
| Hewlett-Packard                       | 2         | 0.34%   |
| Edimax Technology                     | 2         | 0.34%   |
| D-Link                                | 2         | 0.34%   |
| Sitecom Europe                        | 1         | 0.17%   |
| Linksys                               | 1         | 0.17%   |
| InProComm                             | 1         | 0.17%   |
| Fujitsu Siemens Computers             | 1         | 0.17%   |
| Dell                                  | 1         | 0.17%   |
| Belkin Components                     | 1         | 0.17%   |
| ASUSTek Computer                      | 1         | 0.17%   |
| Accton Technology                     | 1         | 0.17%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 4.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 26        | 4.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 24        | 4.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 23        | 3.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 23        | 3.92%   |
| Intel Wireless 8265 / 8275                                              | 22        | 3.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 2.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 17        | 2.9%    |
| Broadcom BCM43142 802.11b/g/n                                           | 17        | 2.9%    |
| Intel Wireless 7260                                                     | 16        | 2.73%   |
| Intel Wireless 3165                                                     | 16        | 2.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 15        | 2.56%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 2.22%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 2.22%   |
| Intel Wi-Fi 6 AX201                                                     | 12        | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 2.05%   |
| Intel Wireless 7265                                                     | 10        | 1.71%   |
| Intel WiFi Link 5100                                                    | 10        | 1.71%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 10        | 1.71%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 10        | 1.71%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 9         | 1.54%   |
| Intel Wireless 3160                                                     | 9         | 1.54%   |
| Intel Ultimate N WiFi Link 5300                                         | 9         | 1.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 1.37%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 1.37%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 7         | 1.19%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.19%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 1.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.02%   |
| Intel Wireless 8260                                                     | 5         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 0.85%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.85%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 4         | 0.68%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 4         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.68%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.68%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 294       | 61.38%  |
| Intel                            | 74        | 15.45%  |
| Qualcomm Atheros                 | 32        | 6.68%   |
| Broadcom                         | 26        | 5.43%   |
| Marvell Technology Group         | 23        | 4.8%    |
| Broadcom Limited                 | 13        | 2.71%   |
| Nvidia                           | 4         | 0.84%   |
| JMicron Technology               | 3         | 0.63%   |
| VIA Technologies                 | 2         | 0.42%   |
| Xiaomi                           | 1         | 0.21%   |
| TP-Link                          | 1         | 0.21%   |
| Silicon Integrated Systems [SiS] | 1         | 0.21%   |
| Samsung Electronics              | 1         | 0.21%   |
| Huawei Technologies              | 1         | 0.21%   |
| DisplayLink                      | 1         | 0.21%   |
| Attansic Technology              | 1         | 0.21%   |
| ASIX Electronics                 | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 167       | 34.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 103       | 21.37%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 19        | 3.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 11        | 2.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 9         | 1.87%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 7         | 1.45%   |
| Intel Ethernet Connection I217-LM                                              | 7         | 1.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 6         | 1.24%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 1.24%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 1.04%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 5         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                                       | 5         | 1.04%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 5         | 1.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 5         | 1.04%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 0.83%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 4         | 0.83%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 0.83%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 0.83%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 4         | 0.83%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.62%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.62%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                        | 3         | 0.62%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                                          | 3         | 0.62%   |
| Intel Ethernet Connection (13) I219-LM                                         | 3         | 0.62%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 0.62%   |
| Broadcom Limited NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 3         | 0.62%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 2         | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2         | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.41%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.41%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 2         | 0.41%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 2         | 0.41%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.41%   |
| Intel Ethernet Connection (11) I219-V                                          | 2         | 0.41%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 546       | 52.55%  |
| Ethernet | 474       | 45.62%  |
| Modem    | 19        | 1.83%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 445       | 76.99%  |
| Ethernet | 133       | 23.01%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 449       | 80.76%  |
| 1     | 91        | 16.37%  |
| 0     | 12        | 2.16%   |
| 3     | 4         | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 438       | 76.98%  |
| Yes  | 131       | 23.02%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 142       | 33.89%  |
| Realtek Semiconductor           | 63        | 15.04%  |
| Qualcomm Atheros Communications | 48        | 11.46%  |
| Broadcom                        | 28        | 6.68%   |
| IMC Networks                    | 19        | 4.53%   |
| Foxconn / Hon Hai               | 18        | 4.3%    |
| Toshiba                         | 16        | 3.82%   |
| Lite-On Technology              | 14        | 3.34%   |
| Hewlett-Packard                 | 13        | 3.1%    |
| Cambridge Silicon Radio         | 9         | 2.15%   |
| Apple                           | 9         | 2.15%   |
| Ralink                          | 8         | 1.91%   |
| Foxconn International           | 6         | 1.43%   |
| Dell                            | 5         | 1.19%   |
| Alps Electric                   | 5         | 1.19%   |
| Realtek                         | 4         | 0.95%   |
| Ralink Technology               | 4         | 0.95%   |
| Askey Computer                  | 4         | 0.95%   |
| ASUSTek Computer                | 2         | 0.48%   |
| Syntek                          | 1         | 0.24%   |
| Chicony Electronics             | 1         | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 73        | 17.42%  |
| Realtek Bluetooth Radio                             | 30        | 7.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 23        | 5.49%   |
| Qualcomm Atheros  Bluetooth Device                  | 21        | 5.01%   |
| Realtek  Bluetooth 4.2 Adapter                      | 17        | 4.06%   |
| Intel AX201 Bluetooth                               | 16        | 3.82%   |
| Intel AX200 Bluetooth                               | 12        | 2.86%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 9         | 2.15%   |
| IMC Networks Bluetooth Radio                        | 9         | 2.15%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 2.15%   |
| Realtek RTL8723B Bluetooth                          | 8         | 1.91%   |
| Ralink RT3290 Bluetooth                             | 8         | 1.91%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 1.91%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 1.91%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 1.67%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.67%   |
| Foxconn International BCM43142A0 Bluetooth module   | 6         | 1.43%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 6         | 1.43%   |
| Toshiba RT Bluetooth Radio                          | 5         | 1.19%   |
| Toshiba Bluetooth Device                            | 5         | 1.19%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 1.19%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 1.19%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 1.19%   |
| Apple Bluetooth Host Controller                     | 5         | 1.19%   |
| Realtek Bluetooth Radio                             | 4         | 0.95%   |
| Qualcomm Atheros Bluetooth                          | 4         | 0.95%   |
| Lite-On Bluetooth Device                            | 4         | 0.95%   |
| HP Broadcom 2070 Bluetooth Combo                    | 4         | 0.95%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.95%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 0.95%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 0.95%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.95%   |
| Askey Bluetooth Device                              | 4         | 0.95%   |
| Realtek RTL8723A Bluetooth                          | 3         | 0.72%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 3         | 0.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 0.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.72%   |
| IMC Networks Bluetooth Device                       | 3         | 0.72%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.72%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 416       | 65.2%   |
| AMD                              | 141       | 22.1%   |
| Nvidia                           | 56        | 8.78%   |
| C-Media Electronics              | 4         | 0.63%   |
| VIA Technologies                 | 3         | 0.47%   |
| Creative Technology              | 3         | 0.47%   |
| Barco Display Systems            | 3         | 0.47%   |
| Logitech                         | 2         | 0.31%   |
| GN Netcom                        | 2         | 0.31%   |
| Texas Instruments                | 1         | 0.16%   |
| Silicon Integrated Systems [SiS] | 1         | 0.16%   |
| Razer USA                        | 1         | 0.16%   |
| Lenovo                           | 1         | 0.16%   |
| Guillemot                        | 1         | 0.16%   |
| CMX Systems                      | 1         | 0.16%   |
| bestechnic                       | 1         | 0.16%   |
| BEHRINGER International          | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 60        | 7.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 47        | 5.86%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 46        | 5.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 40        | 4.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 38        | 4.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 36        | 4.49%   |
| AMD FCH Azalia Controller                                                                         | 29        | 3.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 26        | 3.24%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 25        | 3.12%   |
| Intel 8 Series HD Audio Controller                                                                | 25        | 3.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 24        | 2.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 24        | 2.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 22        | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 20        | 2.49%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 18        | 2.24%   |
| AMD Kabini HDMI/DP Audio                                                                          | 15        | 1.87%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 1.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 1.62%   |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 1.62%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 1.62%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 13        | 1.62%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 13        | 1.62%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 1.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 1.25%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 1.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 1.25%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 1.12%   |
| AMD Wrestler HDMI Audio                                                                           | 9         | 1.12%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 9         | 1.12%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 1%      |
| AMD High Definition Audio Controller                                                              | 8         | 1%      |
| Nvidia High Definition Audio Controller                                                           | 6         | 0.75%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 6         | 0.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.75%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 6         | 0.75%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.62%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 0.62%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 0.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 77        | 26.74%  |
| SK hynix            | 76        | 26.39%  |
| Micron Technology   | 31        | 10.76%  |
| Kingston            | 22        | 7.64%   |
| Unknown             | 21        | 7.29%   |
| Crucial             | 13        | 4.51%   |
| Ramaxel Technology  | 10        | 3.47%   |
| Elpida              | 7         | 2.43%   |
| Transcend           | 6         | 2.08%   |
| Corsair             | 5         | 1.74%   |
| Unknown (ABCD)      | 4         | 1.39%   |
| Nanya Technology    | 4         | 1.39%   |
| A-DATA Technology   | 4         | 1.39%   |
| Team                | 3         | 1.04%   |
| Toshiba             | 1         | 0.35%   |
| Infineon            | 1         | 0.35%   |
| GOODRAM             | 1         | 0.35%   |
| G.Skill             | 1         | 0.35%   |
| Apacer              | 1         | 0.35%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 2.26%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 1.94%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.61%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 1.61%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 1.29%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 1.29%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.29%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.29%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 0.97%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.97%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.97%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.97%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.97%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 3         | 0.97%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.97%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.97%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.97%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.97%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.97%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 3         | 0.97%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 2         | 0.65%   |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 0.65%   |
| Transcend RAM JM667QSU-2G 2GB SODIMM DDR2 667MT/s                | 2         | 0.65%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 2         | 0.65%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.65%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.65%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.65%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.65%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.65%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.65%   |
| Samsung RAM Module 2048MB SODIMM DDR2 533MT/s                    | 2         | 0.65%   |
| Samsung RAM M471B5773CHS-CK0 2GB SODIMM DDR3 1600MT/s            | 2         | 0.65%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.65%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 0.65%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.65%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.65%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.65%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 100       | 40.98%  |
| DDR4    | 97        | 39.75%  |
| DDR2    | 24        | 9.84%   |
| LPDDR4  | 10        | 4.1%    |
| SDRAM   | 5         | 2.05%   |
| LPDDR3  | 4         | 1.64%   |
| DDR     | 2         | 0.82%   |
| DRAM    | 1         | 0.41%   |
| Unknown | 1         | 0.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 226       | 93%     |
| Row Of Chips | 13        | 5.35%   |
| DIMM         | 3         | 1.23%   |
| Unknown      | 1         | 0.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 99        | 37.36%  |
| 8192  | 80        | 30.19%  |
| 2048  | 45        | 16.98%  |
| 16384 | 24        | 9.06%   |
| 1024  | 12        | 4.53%   |
| 512   | 4         | 1.51%   |
| 256   | 1         | 0.38%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 70        | 26.52%  |
| 2667    | 48        | 18.18%  |
| 3200    | 31        | 11.74%  |
| 2400    | 23        | 8.71%   |
| 1334    | 14        | 5.3%    |
| Unknown | 12        | 4.55%   |
| 1333    | 11        | 4.17%   |
| 667     | 11        | 4.17%   |
| 2133    | 9         | 3.41%   |
| 3266    | 6         | 2.27%   |
| 1067    | 6         | 2.27%   |
| 1066    | 5         | 1.89%   |
| 533     | 4         | 1.52%   |
| 4267    | 3         | 1.14%   |
| 4199    | 3         | 1.14%   |
| 1867    | 2         | 0.76%   |
| 800     | 2         | 0.76%   |
| 2048    | 1         | 0.38%   |
| 1639    | 1         | 0.38%   |
| 975     | 1         | 0.38%   |
| 400     | 1         | 0.38%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 50%     |
| Samsung Electronics | 3         | 30%     |
| Konica Minolta      | 1         | 10%     |
| Brother Industries  | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung M2020 Series                 | 3         | 30%     |
| Konica Minolta magicolor 1680MF scan | 1         | 10%     |
| HP OfficeJet 6200                    | 1         | 10%     |
| HP LaserJet P1102                    | 1         | 10%     |
| HP Laser 107w                        | 1         | 10%     |
| HP DeskJet 2620 All-in-One Printer   | 1         | 10%     |
| HP Color Laser 150nw                 | 1         | 10%     |
| Brother HL-2030 Laser Printer        | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Mustek Systems | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Mustek Systems BearPaw 1200 CU Plus | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 117       | 24.53%  |
| IMC Networks                           | 50        | 10.48%  |
| Realtek Semiconductor                  | 46        | 9.64%   |
| Microdia                               | 40        | 8.39%   |
| Acer                                   | 37        | 7.76%   |
| Suyin                                  | 30        | 6.29%   |
| Sunplus Innovation Technology          | 21        | 4.4%    |
| Cheng Uei Precision Industry (Foxlink) | 21        | 4.4%    |
| Quanta                                 | 16        | 3.35%   |
| Ricoh                                  | 14        | 2.94%   |
| Lite-On Technology                     | 13        | 2.73%   |
| Syntek                                 | 12        | 2.52%   |
| Alcor Micro                            | 11        | 2.31%   |
| Apple                                  | 7         | 1.47%   |
| Silicon Motion                         | 6         | 1.26%   |
| Luxvisions Innotech Limited            | 5         | 1.05%   |
| Logitech                               | 5         | 1.05%   |
| Lenovo                                 | 4         | 0.84%   |
| Z-Star Microelectronics                | 3         | 0.63%   |
| Samsung Electronics                    | 3         | 0.63%   |
| Importek                               | 2         | 0.42%   |
| Genesys Logic                          | 2         | 0.42%   |
| ALi                                    | 2         | 0.42%   |
| Sonix Technology                       | 1         | 0.21%   |
| Primax Electronics                     | 1         | 0.21%   |
| Pixart Imaging                         | 1         | 0.21%   |
| OmniVision Technologies                | 1         | 0.21%   |
| Leap Motion                            | 1         | 0.21%   |
| Intel                                  | 1         | 0.21%   |
| Generalplus Technology                 | 1         | 0.21%   |
| GEMBIRD                                | 1         | 0.21%   |
| eMPIA Technology                       | 1         | 0.21%   |
| Arkmicro Technologies                  | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                        | 18        | 3.77%   |
| Microdia Integrated_Webcam_HD                       | 17        | 3.56%   |
| Chicony Integrated Camera                           | 17        | 3.56%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 13        | 2.73%   |
| IMC Networks Integrated Camera                      | 13        | 2.73%   |
| Chicony HP Truevision HD                            | 12        | 2.52%   |
| Sunplus Integrated_Webcam_HD                        | 8         | 1.68%   |
| Chicony TOSHIBA Web Camera - HD                     | 7         | 1.47%   |
| Chicony HP Webcam                                   | 7         | 1.47%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 7         | 1.47%   |
| Acer Lenovo EasyCamera                              | 7         | 1.47%   |
| Realtek 2SF022                                      | 6         | 1.26%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 6         | 1.26%   |
| Chicony USB 2.0 Camera                              | 6         | 1.26%   |
| Acer BisonCam, NB Pro                               | 6         | 1.26%   |
| Syntek Integrated Camera                            | 5         | 1.05%   |
| Suyin Integrated_Webcam_HD                          | 5         | 1.05%   |
| Realtek Lenovo EasyCamera                           | 5         | 1.05%   |
| Quanta VGA WebCam                                   | 5         | 1.05%   |
| Chicony USB2.0 VGA UVC WebCam                       | 5         | 1.05%   |
| Realtek USB2.0 HD UVC WebCam                        | 4         | 0.84%   |
| Realtek Integrated Webcam                           | 4         | 0.84%   |
| Quanta HP TrueVision HD Camera                      | 4         | 0.84%   |
| Microdia Laptop_Integrated_Webcam_HD                | 4         | 0.84%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 4         | 0.84%   |
| Chicony Lenovo EasyCamera                           | 4         | 0.84%   |
| Chicony Integrated Camera (1280x720@30)             | 4         | 0.84%   |
| Chicony HP HD Webcam                                | 4         | 0.84%   |
| Chicony HD Webcam                                   | 4         | 0.84%   |
| Chicony CKF7063 Webcam (HP)                         | 4         | 0.84%   |
| Apple FaceTime HD Camera                            | 4         | 0.84%   |
| Alcor Micro HP Webcam-101                           | 4         | 0.84%   |
| Syntek Lenovo EasyCamera                            | 3         | 0.63%   |
| Syntek EasyCamera                                   | 3         | 0.63%   |
| Suyin HP Truevision HD                              | 3         | 0.63%   |
| Suyin Acer/Lenovo Webcam [CN0316]                   | 3         | 0.63%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 3         | 0.63%   |
| Samsung Galaxy series, misc. (MTP mode)             | 3         | 0.63%   |
| Ricoh Visual Communication Camera VGP-VCC6 [R5U870] | 3         | 0.63%   |
| Ricoh USB2.0 Camera                                 | 3         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 23        | 31.51%  |
| Synaptics                  | 13        | 17.81%  |
| AuthenTec                  | 13        | 17.81%  |
| Upek                       | 11        | 15.07%  |
| Shenzhen Goodix Technology | 9         | 12.33%  |
| Elan Microelectronics      | 2         | 2.74%   |
| STMicroelectronics         | 1         | 1.37%   |
| LighTuning Technology      | 1         | 1.37%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 13.7%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 9.59%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 8.22%   |
| Shenzhen Goodix  Fingerprint Device                                        | 6         | 8.22%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 6.85%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 6.85%   |
| Synaptics  WBDI                                                            | 3         | 4.11%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 4.11%   |
| AuthenTec AES2810                                                          | 3         | 4.11%   |
| Validity Sensors VFS491                                                    | 2         | 2.74%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 2.74%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.74%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.74%   |
| Elan ELAN:ARM-M4                                                           | 2         | 2.74%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 2.74%   |
| Unknown                                                                    | 2         | 2.74%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.37%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.37%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.37%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.37%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.37%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.37%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.37%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.37%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.37%   |
| AuthenTec AES1600                                                          | 1         | 1.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 24        | 61.54%  |
| Alcor Micro | 6         | 15.38%  |
| O2 Micro    | 4         | 10.26%  |
| Upek        | 2         | 5.13%   |
| Lenovo      | 2         | 5.13%   |
| Yubico.com  | 1         | 2.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 10        | 25.64%  |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 23.08%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 15.38%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 10.26%  |
| Broadcom 5880                                                                | 3         | 7.69%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 5.13%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.13%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 5.13%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 2.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 364       | 63.86%  |
| 1     | 165       | 28.95%  |
| 2     | 33        | 5.79%   |
| 3     | 5         | 0.88%   |
| 6     | 2         | 0.35%   |
| 4     | 1         | 0.18%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 73        | 29.67%  |
| Graphics card            | 38        | 15.45%  |
| Chipcard                 | 35        | 14.23%  |
| Net/wireless             | 30        | 12.2%   |
| Bluetooth                | 19        | 7.72%   |
| Multimedia controller    | 14        | 5.69%   |
| Camera                   | 8         | 3.25%   |
| Storage                  | 5         | 2.03%   |
| Modem                    | 5         | 2.03%   |
| Flash memory             | 4         | 1.63%   |
| Communication controller | 4         | 1.63%   |
| Sound                    | 3         | 1.22%   |
| Card reader              | 3         | 1.22%   |
| Net/ethernet             | 2         | 0.81%   |
| Tv card                  | 1         | 0.41%   |
| Network                  | 1         | 0.41%   |
| Firewire controller      | 1         | 0.41%   |

