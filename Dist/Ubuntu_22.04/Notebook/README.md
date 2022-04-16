Ubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 110

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [800aefa57e](https://linux-hardware.org/?probe=800aefa57e) | Apr 16, 2022 |
| MSI           | GF63 8RD                    | [287e344d0e](https://linux-hardware.org/?probe=287e344d0e) | Apr 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [a0ad75fa4b](https://linux-hardware.org/?probe=a0ad75fa4b) | Apr 16, 2022 |
| Google        | Phaser360                   | [ab97623a21](https://linux-hardware.org/?probe=ab97623a21) | Apr 16, 2022 |
| Acer          | Swift SF315-52              | [90c143abed](https://linux-hardware.org/?probe=90c143abed) | Apr 16, 2022 |
| Timi          | A34                         | [ff24fc7e19](https://linux-hardware.org/?probe=ff24fc7e19) | Apr 15, 2022 |
| Sony          | VGN-NS38E_S                 | [1b8177c97a](https://linux-hardware.org/?probe=1b8177c97a) | Apr 14, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | [260c012f44](https://linux-hardware.org/?probe=260c012f44) | Apr 14, 2022 |
| System76      | Serval WS                   | [f02bcd64a2](https://linux-hardware.org/?probe=f02bcd64a2) | Apr 14, 2022 |
| PC Special... | PCx0Dx                      | [6b0f05bf07](https://linux-hardware.org/?probe=6b0f05bf07) | Apr 13, 2022 |
| Lenovo        | Legion 5P 15ARH05H 82GU     | [a31cc5eb3b](https://linux-hardware.org/?probe=a31cc5eb3b) | Apr 13, 2022 |
| Multilaser    | M11W                        | [4be432c77a](https://linux-hardware.org/?probe=4be432c77a) | Apr 13, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [fecdd237a4](https://linux-hardware.org/?probe=fecdd237a4) | Apr 11, 2022 |
| Apple         | MacBookPro14,1              | [1d1ff81694](https://linux-hardware.org/?probe=1d1ff81694) | Apr 11, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ce0316a106](https://linux-hardware.org/?probe=ce0316a106) | Apr 10, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [0def0def83](https://linux-hardware.org/?probe=0def0def83) | Apr 09, 2022 |
| HP            | 840 G6                      | [7f8b25d480](https://linux-hardware.org/?probe=7f8b25d480) | Apr 09, 2022 |
| Toshiba       | Satellite L50-A             | [9a4f7c7381](https://linux-hardware.org/?probe=9a4f7c7381) | Apr 09, 2022 |
| Toshiba       | Satellite L50-A             | [ce1ec01972](https://linux-hardware.org/?probe=ce1ec01972) | Apr 09, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [2240b6c593](https://linux-hardware.org/?probe=2240b6c593) | Apr 09, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [1f799cdbef](https://linux-hardware.org/?probe=1f799cdbef) | Apr 09, 2022 |
| Apple         | MacBookPro14,1              | [470a09fc31](https://linux-hardware.org/?probe=470a09fc31) | Apr 09, 2022 |
| Lenovo        | Yoga Slim 7-14ARE05 82A2    | [ae77218dcf](https://linux-hardware.org/?probe=ae77218dcf) | Apr 07, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [8ab4c1618d](https://linux-hardware.org/?probe=8ab4c1618d) | Apr 07, 2022 |
| Acer          | Nitro AN515-42              | [322440c462](https://linux-hardware.org/?probe=322440c462) | Apr 06, 2022 |
| HUAWEI        | CREM-WXX9                   | [6d57ed5e10](https://linux-hardware.org/?probe=6d57ed5e10) | Apr 06, 2022 |
| HP            | 840 G6                      | [76665316f7](https://linux-hardware.org/?probe=76665316f7) | Apr 06, 2022 |
| Dell          | G5 5590                     | [86d53d1c79](https://linux-hardware.org/?probe=86d53d1c79) | Apr 06, 2022 |
| Framework     | Laptop                      | [59a51973bb](https://linux-hardware.org/?probe=59a51973bb) | Apr 05, 2022 |
| Medion        | E15303                      | [21bdec99bb](https://linux-hardware.org/?probe=21bdec99bb) | Apr 05, 2022 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | [d9cbb34331](https://linux-hardware.org/?probe=d9cbb34331) | Apr 04, 2022 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | [062e604ef0](https://linux-hardware.org/?probe=062e604ef0) | Apr 04, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [43ff476479](https://linux-hardware.org/?probe=43ff476479) | Apr 03, 2022 |
| Samsung       | R580/R590                   | [0b95325a5e](https://linux-hardware.org/?probe=0b95325a5e) | Apr 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [bdb683ff40](https://linux-hardware.org/?probe=bdb683ff40) | Apr 03, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [ad5d38e378](https://linux-hardware.org/?probe=ad5d38e378) | Apr 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e380073189](https://linux-hardware.org/?probe=e380073189) | Apr 02, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | [d103b2cb25](https://linux-hardware.org/?probe=d103b2cb25) | Apr 02, 2022 |
| Dell          | Inspiron N5110              | [eba4514371](https://linux-hardware.org/?probe=eba4514371) | Apr 01, 2022 |
| HUAWEI        | MACH-WX9                    | [a799c6c916](https://linux-hardware.org/?probe=a799c6c916) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | [606eb17f56](https://linux-hardware.org/?probe=606eb17f56) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | [6b0cd44dbb](https://linux-hardware.org/?probe=6b0cd44dbb) | Apr 01, 2022 |
| Alienware     | M11x                        | [f83c01bb34](https://linux-hardware.org/?probe=f83c01bb34) | Apr 01, 2022 |
| Avell High... | A70 MOB                     | [9e095642f0](https://linux-hardware.org/?probe=9e095642f0) | Apr 01, 2022 |
| Dell          | Inspiron 3501               | [a14dde61dc](https://linux-hardware.org/?probe=a14dde61dc) | Apr 01, 2022 |
| HUAWEI        | CREM-WXX9                   | [858142c2ab](https://linux-hardware.org/?probe=858142c2ab) | Apr 01, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [ceee79344c](https://linux-hardware.org/?probe=ceee79344c) | Mar 31, 2022 |
| HUAWEI        | CREM-WXX9                   | [83b60423e1](https://linux-hardware.org/?probe=83b60423e1) | Mar 30, 2022 |
| HP            | 250 G4                      | [69a3535c1a](https://linux-hardware.org/?probe=69a3535c1a) | Mar 30, 2022 |
| HUAWEI        | CREM-WXX9                   | [4626f2aeab](https://linux-hardware.org/?probe=4626f2aeab) | Mar 29, 2022 |
| MSI           | GP76 Leopard 11UG           | [93a6b587c2](https://linux-hardware.org/?probe=93a6b587c2) | Mar 29, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [30c09eec3b](https://linux-hardware.org/?probe=30c09eec3b) | Mar 28, 2022 |
| HUAWEI        | CREM-WXX9                   | [dbdd71e8b8](https://linux-hardware.org/?probe=dbdd71e8b8) | Mar 28, 2022 |
| Dell          | XPS 17 9710                 | [ecf7b98552](https://linux-hardware.org/?probe=ecf7b98552) | Mar 28, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0e93a8600c](https://linux-hardware.org/?probe=0e93a8600c) | Mar 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e5b0f5c259](https://linux-hardware.org/?probe=e5b0f5c259) | Mar 27, 2022 |
| HUAWEI        | MACH-WX9                    | [64e505d8d7](https://linux-hardware.org/?probe=64e505d8d7) | Mar 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [01e83234d9](https://linux-hardware.org/?probe=01e83234d9) | Mar 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [4fb374e78b](https://linux-hardware.org/?probe=4fb374e78b) | Mar 25, 2022 |
| HP            | EliteBook 840 G3            | [f06216a521](https://linux-hardware.org/?probe=f06216a521) | Mar 24, 2022 |
| HP            | Pavilion x2 Detachable      | [a82a2739a8](https://linux-hardware.org/?probe=a82a2739a8) | Mar 22, 2022 |
| Lenovo        | Z50-70 20354                | [b03762a80b](https://linux-hardware.org/?probe=b03762a80b) | Mar 22, 2022 |
| Framework     | Laptop                      | [b8fcafa943](https://linux-hardware.org/?probe=b8fcafa943) | Mar 20, 2022 |
| GPU Compan... | GWTC116-2                   | [3c0450f79e](https://linux-hardware.org/?probe=3c0450f79e) | Mar 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [1c22760a82](https://linux-hardware.org/?probe=1c22760a82) | Mar 12, 2022 |
| MSI           | Creator Z16 A11UET          | [1804e5eb77](https://linux-hardware.org/?probe=1804e5eb77) | Mar 09, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [9fd12bdd29](https://linux-hardware.org/?probe=9fd12bdd29) | Mar 06, 2022 |
| HUAWEI        | BOHB-WAX9                   | [915ca09de4](https://linux-hardware.org/?probe=915ca09de4) | Mar 05, 2022 |
| Toshiba       | Satellite C70D-A            | [c7dfd52f76](https://linux-hardware.org/?probe=c7dfd52f76) | Mar 05, 2022 |
| HP            | ZBook 15 G5                 | [f86a14c16d](https://linux-hardware.org/?probe=f86a14c16d) | Mar 05, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | [206f3a7c01](https://linux-hardware.org/?probe=206f3a7c01) | Mar 02, 2022 |
| HP            | Presario CQ42               | [de34294599](https://linux-hardware.org/?probe=de34294599) | Feb 27, 2022 |
| Shanghai Z... | ZXE CRB                     | [7fe4a3390b](https://linux-hardware.org/?probe=7fe4a3390b) | Feb 25, 2022 |
| Timi          | TM1709                      | [16e699bea8](https://linux-hardware.org/?probe=16e699bea8) | Feb 25, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [076c8f6e01](https://linux-hardware.org/?probe=076c8f6e01) | Feb 23, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [85c09f63f0](https://linux-hardware.org/?probe=85c09f63f0) | Feb 23, 2022 |
| Acer          | Aspire A517-52              | [52976ad94b](https://linux-hardware.org/?probe=52976ad94b) | Feb 23, 2022 |
| MSI           | Stealth GS66 12UHS          | [bb8ef51c23](https://linux-hardware.org/?probe=bb8ef51c23) | Feb 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [da103e44c5](https://linux-hardware.org/?probe=da103e44c5) | Feb 17, 2022 |
| HP            | 620                         | [bd89b469e4](https://linux-hardware.org/?probe=bd89b469e4) | Feb 14, 2022 |
| HP            | Pavilion 15                 | [9246e37578](https://linux-hardware.org/?probe=9246e37578) | Feb 09, 2022 |
| ASUSTek       | K52Je                       | [e1010983cf](https://linux-hardware.org/?probe=e1010983cf) | Feb 09, 2022 |
| Dell          | Latitude 3330               | [c3b39f74b4](https://linux-hardware.org/?probe=c3b39f74b4) | Jan 31, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [0a04b2d1b1](https://linux-hardware.org/?probe=0a04b2d1b1) | Jan 31, 2022 |
| HP            | 15                          | [81961b52a9](https://linux-hardware.org/?probe=81961b52a9) | Jan 29, 2022 |
| HP            | ProBook 445 G7              | [bceca55120](https://linux-hardware.org/?probe=bceca55120) | Jan 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [2de98fb4d8](https://linux-hardware.org/?probe=2de98fb4d8) | Jan 22, 2022 |
| HP            | ProBook 650 G5              | [111cb6822e](https://linux-hardware.org/?probe=111cb6822e) | Jan 21, 2022 |
| HP            | Pavilion Laptop 14-dv1xx... | [e092fc4b26](https://linux-hardware.org/?probe=e092fc4b26) | Jan 20, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [245123d0a8](https://linux-hardware.org/?probe=245123d0a8) | Jan 20, 2022 |
| Dell          | Latitude E6510              | [c0d3a6c31a](https://linux-hardware.org/?probe=c0d3a6c31a) | Jan 16, 2022 |
| Google        | Kefka                       | [e62fa3eea6](https://linux-hardware.org/?probe=e62fa3eea6) | Jan 10, 2022 |
| Timi          | RedmiBook Pro 15S           | [034079628f](https://linux-hardware.org/?probe=034079628f) | Jan 07, 2022 |
| Lenovo        | ThinkPad T400 2768WGB       | [ac0e3dfe29](https://linux-hardware.org/?probe=ac0e3dfe29) | Jan 07, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [666b0b18f5](https://linux-hardware.org/?probe=666b0b18f5) | Dec 30, 2021 |
| MSI           | GT73VR 6RE                  | [0f41e5dd07](https://linux-hardware.org/?probe=0f41e5dd07) | Dec 28, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [be79b3cd82](https://linux-hardware.org/?probe=be79b3cd82) | Dec 26, 2021 |
| Lenovo        | Flex 2-15 20405             | [ccc85b0783](https://linux-hardware.org/?probe=ccc85b0783) | Dec 13, 2021 |
| MSI           | Modern 15 A11MU             | [34b31c53cd](https://linux-hardware.org/?probe=34b31c53cd) | Dec 07, 2021 |
| Toshiba       | PORTEGE Z10T-A              | [5257d76a92](https://linux-hardware.org/?probe=5257d76a92) | Dec 05, 2021 |
| HP            | Laptop 15s-fq1xxx           | [f219ee63ff](https://linux-hardware.org/?probe=f219ee63ff) | Nov 30, 2021 |
| HP            | Laptop 15s-fq1xxx           | [3199d159a4](https://linux-hardware.org/?probe=3199d159a4) | Nov 30, 2021 |
| Lenovo        | Flex 2-15 20405             | [d191e3f97f](https://linux-hardware.org/?probe=d191e3f97f) | Nov 22, 2021 |
| Lenovo        | Flex 2-15 20405             | [6381b11078](https://linux-hardware.org/?probe=6381b11078) | Nov 22, 2021 |
| ASUSTek       | X58L                        | [c3df58b13b](https://linux-hardware.org/?probe=c3df58b13b) | Nov 10, 2021 |
| ASUSTek       | X58L                        | [e1425f037e](https://linux-hardware.org/?probe=e1425f037e) | Nov 10, 2021 |
| ASUSTek       | X58L                        | [f64ba3a9e4](https://linux-hardware.org/?probe=f64ba3a9e4) | Nov 10, 2021 |
| Dell          | Inspiron 1464               | [26f50eb4a8](https://linux-hardware.org/?probe=26f50eb4a8) | Nov 06, 2021 |
| Dell          | Inspiron 11 - 3147          | [6b1a282c17](https://linux-hardware.org/?probe=6b1a282c17) | Nov 05, 2021 |
| Dell          | Inspiron 1464               | [4063779d5a](https://linux-hardware.org/?probe=4063779d5a) | Nov 01, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.15.0-25-generic           | 20        | 23.81%  |
| 5.15.0-23-generic           | 19        | 22.62%  |
| 5.15.0-18-generic           | 12        | 14.29%  |
| 5.15.0-17-generic           | 7         | 8.33%   |
| 5.13.0-19-generic           | 5         | 5.95%   |
| 5.15.0-22-generic           | 4         | 4.76%   |
| 5.17.0-051700-generic       | 2         | 2.38%   |
| 5.17.2-051702-generic       | 1         | 1.19%   |
| 5.17.0-051700rc5-lowlatency | 1         | 1.19%   |
| 5.16.11-76051611-generic    | 1         | 1.19%   |
| 5.16.0-051600-generic       | 1         | 1.19%   |
| 5.15.6-051506-generic       | 1         | 1.19%   |
| 5.15.17-xanmod2             | 1         | 1.19%   |
| 5.15.15-76051515-generic    | 1         | 1.19%   |
| 5.15.12-051512-generic      | 1         | 1.19%   |
| 5.15.11-051511-generic      | 1         | 1.19%   |
| 5.15.10-051510-generic      | 1         | 1.19%   |
| 5.15.0-14-generic           | 1         | 1.19%   |
| 5.15.0-13-generic           | 1         | 1.19%   |
| 5.15.0-12-generic           | 1         | 1.19%   |
| 5.15.0-11-generic           | 1         | 1.19%   |
| 5.13.19                     | 1         | 1.19%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 64        | 78.05%  |
| 5.13.0  | 5         | 6.1%    |
| 5.17.0  | 3         | 3.66%   |
| 5.17.2  | 1         | 1.22%   |
| 5.16.11 | 1         | 1.22%   |
| 5.16.0  | 1         | 1.22%   |
| 5.15.6  | 1         | 1.22%   |
| 5.15.17 | 1         | 1.22%   |
| 5.15.15 | 1         | 1.22%   |
| 5.15.12 | 1         | 1.22%   |
| 5.15.11 | 1         | 1.22%   |
| 5.15.10 | 1         | 1.22%   |
| 5.13.19 | 1         | 1.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 70        | 85.37%  |
| 5.13    | 6         | 7.32%   |
| 5.17    | 4         | 4.88%   |
| 5.16    | 2         | 2.44%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 81        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 74        | 89.16%  |
| Unknown           | 6         | 7.23%   |
| Yaru:ubuntu:GNOME | 1         | 1.2%    |
| GNUstep           | 1         | 1.2%    |
| Cinnamon          | 1         | 1.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 50        | 60.24%  |
| X11     | 26        | 31.33%  |
| Tty     | 5         | 6.02%   |
| Unknown | 2         | 2.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 67        | 81.71%  |
| Unknown | 13        | 15.85%  |
| LightDM | 1         | 1.22%   |
| GDM     | 1         | 1.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 42        | 51.85%  |
| en_IN   | 7         | 8.64%   |
| fr_FR   | 4         | 4.94%   |
| zh_CN   | 3         | 3.7%    |
| pt_BR   | 3         | 3.7%    |
| en_GB   | 3         | 3.7%    |
| en_CA   | 3         | 3.7%    |
| de_DE   | 3         | 3.7%    |
| ru_RU   | 2         | 2.47%   |
| pl_PL   | 2         | 2.47%   |
| hu_HU   | 2         | 2.47%   |
| it_IT   | 1         | 1.23%   |
| es_EC   | 1         | 1.23%   |
| en_SG   | 1         | 1.23%   |
| en_IL   | 1         | 1.23%   |
| en_AU   | 1         | 1.23%   |
| de_IT   | 1         | 1.23%   |
| Unknown | 1         | 1.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 45        | 55.56%  |
| EFI  | 36        | 44.44%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 75        | 92.59%  |
| Zfs     | 2         | 2.47%   |
| Overlay | 2         | 2.47%   |
| Btrfs   | 2         | 2.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 43        | 53.09%  |
| GPT     | 34        | 41.98%  |
| MBR     | 4         | 4.94%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 72        | 88.89%  |
| Yes       | 9         | 11.11%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 52        | 63.41%  |
| Yes       | 30        | 36.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 17        | 20.99%  |
| Lenovo                         | 16        | 19.75%  |
| ASUSTek Computer               | 9         | 11.11%  |
| Dell                           | 7         | 8.64%   |
| MSI                            | 6         | 7.41%   |
| Toshiba                        | 3         | 3.7%    |
| HUAWEI                         | 3         | 3.7%    |
| Acer                           | 3         | 3.7%    |
| Timi                           | 2         | 2.47%   |
| Google                         | 2         | 2.47%   |
| Framework                      | 2         | 2.47%   |
| System76                       | 1         | 1.23%   |
| Sony                           | 1         | 1.23%   |
| Shanghai Zhaoxin Semiconductor | 1         | 1.23%   |
| Samsung Electronics            | 1         | 1.23%   |
| PC Specialist                  | 1         | 1.23%   |
| Multilaser                     | 1         | 1.23%   |
| Medion                         | 1         | 1.23%   |
| GPU Company                    | 1         | 1.23%   |
| Avell High Performance         | 1         | 1.23%   |
| Apple                          | 1         | 1.23%   |
| Alienware                      | 1         | 1.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Framework Laptop                                  | 2         | 2.47%   |
| Toshiba Satellite L50-A                           | 1         | 1.23%   |
| Toshiba Satellite C70D-A                          | 1         | 1.23%   |
| Toshiba PORTEGE Z10T-A                            | 1         | 1.23%   |
| Timi TM1709                                       | 1         | 1.23%   |
| Timi A34                                          | 1         | 1.23%   |
| System76 Serval WS                                | 1         | 1.23%   |
| Sony VGN-NS38E_S                                  | 1         | 1.23%   |
| Shanghai Zhaoxin ZXE CRB                          | 1         | 1.23%   |
| Samsung R580/R590                                 | 1         | 1.23%   |
| PC Specialist PCx0Dx                              | 1         | 1.23%   |
| Multilaser M11W                                   | 1         | 1.23%   |
| MSI Stealth GS66 12UHS                            | 1         | 1.23%   |
| MSI Modern 15 A11MU                               | 1         | 1.23%   |
| MSI GT73VR 6RE                                    | 1         | 1.23%   |
| MSI GP76 Leopard 11UG                             | 1         | 1.23%   |
| MSI GF63 8RD                                      | 1         | 1.23%   |
| MSI Creator Z16 A11UET                            | 1         | 1.23%   |
| Medion E15303                                     | 1         | 1.23%   |
| Lenovo Z50-70 20354                               | 1         | 1.23%   |
| Lenovo Yoga Slim 7-14ARE05 82A2                   | 1         | 1.23%   |
| Lenovo ThinkPad T14s Gen 2a 20XF004WUS            | 1         | 1.23%   |
| Lenovo ThinkPad S1 Yoga 12 20DKS0EU00             | 1         | 1.23%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3004KUS              | 1         | 1.23%   |
| Lenovo ThinkPad E495 20NEA00QUS                   | 1         | 1.23%   |
| Lenovo ThinkPad E15 Gen 2 20TES2H500              | 1         | 1.23%   |
| Lenovo ThinkBook 15 G3 ACL 21A4                   | 1         | 1.23%   |
| Lenovo ThinkBook 14p Gen 2 20YN                   | 1         | 1.23%   |
| Lenovo Legion R7000 2020 82B6                     | 1         | 1.23%   |
| Lenovo Legion 7 16ACHg6 82N6                      | 1         | 1.23%   |
| Lenovo Legion 5P 15ARH05H 82GU                    | 1         | 1.23%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7                  | 1         | 1.23%   |
| Lenovo IdeaPad 5 14ITL05 82FE                     | 1         | 1.23%   |
| Lenovo IdeaPad 330S-15IKB 81F5                    | 1         | 1.23%   |
| Lenovo Flex 2-15 20405                            | 1         | 1.23%   |
| HUAWEI MACH-WX9                                   | 1         | 1.23%   |
| HUAWEI CREM-WXX9                                  | 1         | 1.23%   |
| HUAWEI BOHB-WAX9                                  | 1         | 1.23%   |
| HP ZBook Power 15.6 inch G8 Mobile Workstation PC | 1         | 1.23%   |
| HP ZBook 15 G5                                    | 1         | 1.23%   |
| HP ProBook 650 G5                                 | 1         | 1.23%   |
| HP ProBook 445 G7                                 | 1         | 1.23%   |
| HP Presario CQ42                                  | 1         | 1.23%   |
| HP Pavilion x2 Detachable                         | 1         | 1.23%   |
| HP Pavilion Laptop 14-dv1xxx                      | 1         | 1.23%   |
| HP Pavilion Laptop 14-ce2xxx                      | 1         | 1.23%   |
| HP Pavilion 15                                    | 1         | 1.23%   |
| HP Laptop 15s-fq1xxx                              | 1         | 1.23%   |
| HP ENVY Laptop 13-ad1xx                           | 1         | 1.23%   |
| HP EliteBook 840 G8 Notebook PC                   | 1         | 1.23%   |
| HP EliteBook 840 G3                               | 1         | 1.23%   |
| HP 840 G6                                         | 1         | 1.23%   |
| HP 620                                            | 1         | 1.23%   |
| HP 250 G4                                         | 1         | 1.23%   |
| HP 15                                             | 1         | 1.23%   |
| GPU Company GWTC116-2                             | 1         | 1.23%   |
| Google Phaser360                                  | 1         | 1.23%   |
| Google Kefka                                      | 1         | 1.23%   |
| Dell Latitude E6510                               | 1         | 1.23%   |
| Dell Latitude 3330                                | 1         | 1.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 5         | 6.17%   |
| ASUS ROG                   | 5         | 6.17%   |
| HP Pavilion                | 4         | 4.94%   |
| Dell Inspiron              | 4         | 4.94%   |
| Lenovo Legion              | 3         | 3.7%    |
| Lenovo IdeaPad             | 3         | 3.7%    |
| Toshiba Satellite          | 2         | 2.47%   |
| Lenovo ThinkBook           | 2         | 2.47%   |
| HP ZBook                   | 2         | 2.47%   |
| HP ProBook                 | 2         | 2.47%   |
| HP EliteBook               | 2         | 2.47%   |
| Framework Laptop           | 2         | 2.47%   |
| Dell Latitude              | 2         | 2.47%   |
| Toshiba PORTEGE            | 1         | 1.23%   |
| Timi TM1709                | 1         | 1.23%   |
| Timi A34                   | 1         | 1.23%   |
| System76 Serval            | 1         | 1.23%   |
| Sony VGN-NS38E             | 1         | 1.23%   |
| Shanghai Zhaoxin ZXE       | 1         | 1.23%   |
| Samsung R580               | 1         | 1.23%   |
| PC Specialist PCx0Dx       | 1         | 1.23%   |
| Multilaser M11W            | 1         | 1.23%   |
| MSI Stealth                | 1         | 1.23%   |
| MSI Modern                 | 1         | 1.23%   |
| MSI GT73VR                 | 1         | 1.23%   |
| MSI GP76                   | 1         | 1.23%   |
| MSI GF63                   | 1         | 1.23%   |
| MSI Creator                | 1         | 1.23%   |
| Medion E15303              | 1         | 1.23%   |
| Lenovo Z50-70              | 1         | 1.23%   |
| Lenovo Yoga                | 1         | 1.23%   |
| Lenovo Flex                | 1         | 1.23%   |
| HUAWEI MACH-WX9            | 1         | 1.23%   |
| HUAWEI CREM-WXX9           | 1         | 1.23%   |
| HUAWEI BOHB-WAX9           | 1         | 1.23%   |
| HP Presario                | 1         | 1.23%   |
| HP Laptop                  | 1         | 1.23%   |
| HP ENVY                    | 1         | 1.23%   |
| HP 840                     | 1         | 1.23%   |
| HP 620                     | 1         | 1.23%   |
| HP 250                     | 1         | 1.23%   |
| HP 15                      | 1         | 1.23%   |
| GPU Company GWTC116-2      | 1         | 1.23%   |
| Google Phaser360           | 1         | 1.23%   |
| Google Kefka               | 1         | 1.23%   |
| Dell G5                    | 1         | 1.23%   |
| Avell High Performance A70 | 1         | 1.23%   |
| ASUS X58L                  | 1         | 1.23%   |
| ASUS VivoBook              | 1         | 1.23%   |
| ASUS K52Je                 | 1         | 1.23%   |
| ASUS ASUS                  | 1         | 1.23%   |
| Apple MacBookPro14         | 1         | 1.23%   |
| Alienware M11x             | 1         | 1.23%   |
| Acer Swift                 | 1         | 1.23%   |
| Acer Nitro                 | 1         | 1.23%   |
| Acer Aspire                | 1         | 1.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 26        | 32.1%   |
| 2020 | 13        | 16.05%  |
| 2018 | 8         | 9.88%   |
| 2010 | 7         | 8.64%   |
| 2019 | 6         | 7.41%   |
| 2013 | 6         | 7.41%   |
| 2014 | 4         | 4.94%   |
| 2017 | 3         | 3.7%    |
| 2022 | 2         | 2.47%   |
| 2015 | 2         | 2.47%   |
| 2008 | 2         | 2.47%   |
| 2016 | 1         | 1.23%   |
| 2011 | 1         | 1.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 81        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 71        | 87.65%  |
| Enabled  | 10        | 12.35%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 79        | 97.53%  |
| Yes  | 2         | 2.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 19        | 23.46%  |
| 16.01-24.0  | 14        | 17.28%  |
| 32.01-64.0  | 12        | 14.81%  |
| 3.01-4.0    | 11        | 13.58%  |
| 8.01-16.0   | 11        | 13.58%  |
| 24.01-32.0  | 5         | 6.17%   |
| 64.01-256.0 | 4         | 4.94%   |
| 1.01-2.0    | 3         | 3.7%    |
| 2.01-3.0    | 2         | 2.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 24        | 28.92%  |
| 4.01-8.0   | 22        | 26.51%  |
| 2.01-3.0   | 19        | 22.89%  |
| 3.01-4.0   | 12        | 14.46%  |
| 8.01-16.0  | 2         | 2.41%   |
| 0.01-0.5   | 2         | 2.41%   |
| 24.01-32.0 | 1         | 1.2%    |
| 0.51-1.0   | 1         | 1.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 60        | 74.07%  |
| 2      | 18        | 22.22%  |
| 3      | 2         | 2.47%   |
| 0      | 1         | 1.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 65        | 79.27%  |
| Yes       | 17        | 20.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 53        | 65.43%  |
| No        | 28        | 34.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 98.77%  |
| No        | 1         | 1.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 85.37%  |
| No        | 12        | 14.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 19        | 23.46%  |
| India       | 8         | 9.88%   |
| France      | 7         | 8.64%   |
| Germany     | 5         | 6.17%   |
| Italy       | 4         | 4.94%   |
| China       | 4         | 4.94%   |
| UK          | 3         | 3.7%    |
| Poland      | 3         | 3.7%    |
| Brazil      | 3         | 3.7%    |
| Taiwan      | 2         | 2.47%   |
| Russia      | 2         | 2.47%   |
| Netherlands | 2         | 2.47%   |
| Hungary     | 2         | 2.47%   |
| Egypt       | 2         | 2.47%   |
| Canada      | 2         | 2.47%   |
| Vietnam     | 1         | 1.23%   |
| Thailand    | 1         | 1.23%   |
| Spain       | 1         | 1.23%   |
| Slovenia    | 1         | 1.23%   |
| Singapore   | 1         | 1.23%   |
| Romania     | 1         | 1.23%   |
| Myanmar     | 1         | 1.23%   |
| Mexico      | 1         | 1.23%   |
| Israel      | 1         | 1.23%   |
| Ecuador     | 1         | 1.23%   |
| Colombia    | 1         | 1.23%   |
| Australia   | 1         | 1.23%   |
| Argentina   | 1         | 1.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Moses Lake               | 2         | 2.44%   |
| Kunming                  | 2         | 2.44%   |
| Chennai                  | 2         | 2.44%   |
| Chandigarh               | 2         | 2.44%   |
| Budapest                 | 2         | 2.44%   |
| Boeschepe                | 2         | 2.44%   |
| Yangon                   | 1         | 1.22%   |
| Worms                    | 1         | 1.22%   |
| Wolverhampton            | 1         | 1.22%   |
| Wichita                  | 1         | 1.22%   |
| Warsaw                   | 1         | 1.22%   |
| Wake Forest              | 1         | 1.22%   |
| Vũng Tàu               | 1         | 1.22%   |
| Tubarao                  | 1         | 1.22%   |
| The Hague                | 1         | 1.22%   |
| Tel Aviv                 | 1         | 1.22%   |
| Taoyuan District         | 1         | 1.22%   |
| Tampa                    | 1         | 1.22%   |
| Taipei                   | 1         | 1.22%   |
| Sydney                   | 1         | 1.22%   |
| St Petersburg            | 1         | 1.22%   |
| Singapore                | 1         | 1.22%   |
| Siegen                   | 1         | 1.22%   |
| Seward                   | 1         | 1.22%   |
| San Francisco            | 1         | 1.22%   |
| Saint-Dizier             | 1         | 1.22%   |
| Richland Center          | 1         | 1.22%   |
| Renchen                  | 1         | 1.22%   |
| Pune                     | 1         | 1.22%   |
| Porto Alegre             | 1         | 1.22%   |
| Portland                 | 1         | 1.22%   |
| Ploieşti                | 1         | 1.22%   |
| Paris                    | 1         | 1.22%   |
| Papun                    | 1         | 1.22%   |
| Palermo                  | 1         | 1.22%   |
| Palau-solita i Plegamans | 1         | 1.22%   |
| Oss                      | 1         | 1.22%   |
| Orehova Vas              | 1         | 1.22%   |
| North Bend               | 1         | 1.22%   |
| Mountain Grove           | 1         | 1.22%   |
| Moscow                   | 1         | 1.22%   |
| Milan                    | 1         | 1.22%   |
| Mashtul as Suq           | 1         | 1.22%   |
| Marnaz                   | 1         | 1.22%   |
| Mariposa                 | 1         | 1.22%   |
| Ludhiana                 | 1         | 1.22%   |
| Legionowo                | 1         | 1.22%   |
| Kimberly                 | 1         | 1.22%   |
| Khlong Luang             | 1         | 1.22%   |
| Jacksonville             | 1         | 1.22%   |
| Itanhaem                 | 1         | 1.22%   |
| Hyderabad                | 1         | 1.22%   |
| Henderson                | 1         | 1.22%   |
| Hefei                    | 1         | 1.22%   |
| Gurgaon                  | 1         | 1.22%   |
| Guayaquil                | 1         | 1.22%   |
| Grandview                | 1         | 1.22%   |
| Glasgow                  | 1         | 1.22%   |
| Gdansk                   | 1         | 1.22%   |
| Ensenada                 | 1         | 1.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 30     | 26.32%  |
| WDC                 | 11        | 12     | 11.58%  |
| Seagate             | 10        | 10     | 10.53%  |
| Unknown             | 8         | 9      | 8.42%   |
| SK Hynix            | 6         | 6      | 6.32%   |
| Intel               | 6         | 7      | 6.32%   |
| SanDisk             | 5         | 5      | 5.26%   |
| Toshiba             | 4         | 5      | 4.21%   |
| Kingston            | 4         | 4      | 4.21%   |
| KIOXIA              | 3         | 3      | 3.16%   |
| Hitachi             | 2         | 2      | 2.11%   |
| PNY                 | 1         | 1      | 1.05%   |
| PLEXTOR             | 1         | 1      | 1.05%   |
| OSCOO               | 1         | 1      | 1.05%   |
| OCZ                 | 1         | 1      | 1.05%   |
| Micron Technology   | 1         | 2      | 1.05%   |
| LITEON              | 1         | 1      | 1.05%   |
| KLEVV               | 1         | 1      | 1.05%   |
| HGST                | 1         | 1      | 1.05%   |
| China               | 1         | 1      | 1.05%   |
| BIWIN               | 1         | 1      | 1.05%   |
| ADATA Technology    | 1         | 2      | 1.05%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Samsung PM963 2.5" NVMe PCIe SSD 256GB    | 3         | 3.03%   |
| Samsung NVMe SSD Drive 512GB              | 3         | 3.03%   |
| Intel NVMe SSD Drive 512GB                | 3         | 3.03%   |
| SK Hynix NVMe SSD Drive 256GB             | 2         | 2.02%   |
| Seagate ST9500420AS 500GB                 | 2         | 2.02%   |
| Samsung MZVLB1T0HBLR-000L2 1TB            | 2         | 2.02%   |
| KIOXIA NVMe SSD Drive 256GB               | 2         | 2.02%   |
| WDC WDS100T2B0C-00PXH0 1TB                | 1         | 1.01%   |
| WDC WDS100T1X0E-00AFY0 1TB                | 1         | 1.01%   |
| WDC WDBNCE0010PNC 1TB SSD                 | 1         | 1.01%   |
| WDC WD3200BPVT-75JJ5T0 320GB              | 1         | 1.01%   |
| WDC WD10SPCX-24HWST1 1TB                  | 1         | 1.01%   |
| WDC WD10JPVX-60JC3T0 1TB                  | 1         | 1.01%   |
| WDC PC SN810 SDCPNRZ-2T00-1032 2TB        | 1         | 1.01%   |
| WDC PC SN730 SDBPNTY-512G                 | 1         | 1.01%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB      | 1         | 1.01%   |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB      | 1         | 1.01%   |
| WDC PC SN520 SDAPNUW-256G-1006 256GB      | 1         | 1.01%   |
| Unknown SD/MMC/MS PRO 394GB               | 1         | 1.01%   |
| Unknown SC128  128GB                      | 1         | 1.01%   |
| Unknown SA16G  16GB                       | 1         | 1.01%   |
| Unknown NVMe SSD Drive 512GB              | 1         | 1.01%   |
| Unknown MMC Card  32GB                    | 1         | 1.01%   |
| Unknown MMC Card  16GB                    | 1         | 1.01%   |
| Unknown DA4032  32GB                      | 1         | 1.01%   |
| Unknown Biwin  64GB                       | 1         | 1.01%   |
| Toshiba NVMe SSD Drive 512GB              | 1         | 1.01%   |
| Toshiba NVMe SSD Drive 1TB                | 1         | 1.01%   |
| Toshiba MQ01ABD100M 1TB                   | 1         | 1.01%   |
| Toshiba KXG50ZNV512G 512GB                | 1         | 1.01%   |
| SK Hynix SKHynix_HFS256GD9TNI-L2A0B 256GB | 1         | 1.01%   |
| SK Hynix SKHynix_HFS001TDE9X084N 1TB      | 1         | 1.01%   |
| SK Hynix SKHynix_HFM256GD3HX015N 256GB    | 1         | 1.01%   |
| SK Hynix NVMe SSD Drive 512GB             | 1         | 1.01%   |
| Seagate ST9320423AS 320GB                 | 1         | 1.01%   |
| Seagate ST9320325AS 320GB                 | 1         | 1.01%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1.01%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 1         | 1.01%   |
| Seagate ST320LM001 HN-M320MBB 320GB       | 1         | 1.01%   |
| Seagate ST1000LX015-1U7172 1TB            | 1         | 1.01%   |
| Seagate ST1000LM049-2GH172 1TB            | 1         | 1.01%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 1.01%   |
| SanDisk SSD PLUS 240 GB                   | 1         | 1.01%   |
| SanDisk SDSSDA120G 120GB                  | 1         | 1.01%   |
| Sandisk NVMe SSD Drive 512GB              | 1         | 1.01%   |
| Sandisk NVMe SSD Drive 1024GB             | 1         | 1.01%   |
| SanDisk DF4032  32GB                      | 1         | 1.01%   |
| Samsung SSD 980 PRO 1TB                   | 1         | 1.01%   |
| Samsung SSD 970 EVO Plus 2TB              | 1         | 1.01%   |
| Samsung SSD 860 EVO 500GB                 | 1         | 1.01%   |
| Samsung SSD 860 EVO 1TB                   | 1         | 1.01%   |
| Samsung SSD 850 EVO 500GB                 | 1         | 1.01%   |
| Samsung SSD 750 EVO 250GB                 | 1         | 1.01%   |
| Samsung NVMe SSD Drive 2TB                | 1         | 1.01%   |
| Samsung NVMe SSD Drive 250GB              | 1         | 1.01%   |
| Samsung NVMe SSD Drive 1024GB             | 1         | 1.01%   |
| Samsung MZVLQ256HAJD-000H1 256GB          | 1         | 1.01%   |
| Samsung MZVLB512HAJQ-000H1 512GB          | 1         | 1.01%   |
| Samsung MZVL21T0HCLR-00BL7 1TB            | 1         | 1.01%   |
| Samsung MZVL21T0HCLR-00B00 1TB            | 1         | 1.01%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 47.62%  |
| WDC                 | 3         | 4      | 14.29%  |
| Samsung Electronics | 3         | 3      | 14.29%  |
| Hitachi             | 2         | 2      | 9.52%   |
| Unknown             | 1         | 1      | 4.76%   |
| Toshiba             | 1         | 1      | 4.76%   |
| HGST                | 1         | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 6         | 6      | 37.5%   |
| SanDisk             | 2         | 2      | 12.5%   |
| WDC                 | 1         | 1      | 6.25%   |
| PNY                 | 1         | 1      | 6.25%   |
| PLEXTOR             | 1         | 1      | 6.25%   |
| OCZ                 | 1         | 1      | 6.25%   |
| LITEON              | 1         | 1      | 6.25%   |
| KLEVV               | 1         | 1      | 6.25%   |
| China               | 1         | 1      | 6.25%   |
| BIWIN               | 1         | 1      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 49        | 59     | 53.26%  |
| HDD     | 20        | 22     | 21.74%  |
| SSD     | 15        | 16     | 16.3%   |
| MMC     | 7         | 8      | 7.61%   |
| Unknown | 1         | 1      | 1.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 49        | 59     | 53.26%  |
| SATA | 35        | 38     | 38.04%  |
| MMC  | 7         | 8      | 7.61%   |
| SAS  | 1         | 1      | 1.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 25        | 26     | 69.44%  |
| 0.51-1.0   | 11        | 12     | 30.56%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 30.49%  |
| 251-500        | 20        | 24.39%  |
| 501-1000       | 15        | 18.29%  |
| 51-100         | 6         | 7.32%   |
| 1001-2000      | 5         | 6.1%    |
| 1-20           | 5         | 6.1%    |
| 21-50          | 4         | 4.88%   |
| More than 3000 | 1         | 1.22%   |
| Unknown        | 1         | 1.22%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 28        | 33.33%  |
| 21-50          | 18        | 21.43%  |
| 51-100         | 16        | 19.05%  |
| 101-250        | 11        | 13.1%   |
| 251-500        | 6         | 7.14%   |
| 501-1000       | 3         | 3.57%   |
| More than 3000 | 1         | 1.19%   |
| Unknown        | 1         | 1.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10JPVX-60JC3T0 1TB            | 1         | 1      | 16.67%  |
| Seagate ST9500420AS 500GB           | 1         | 1      | 16.67%  |
| Seagate ST9320325AS 320GB           | 1         | 1      | 16.67%  |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 16.67%  |
| Samsung Electronics HM160HI 160GB   | 1         | 1      | 16.67%  |
| LITEON CV8-8E128-HP 128GB SSD       | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 50%     |
| WDC                 | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 1      | 16.67%  |
| LITEON              | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 60%     |
| WDC                 | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 83.33%  |
| SSD  | 1         | 1      | 16.67%  |

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
| Detected | 47        | 63     | 55.95%  |
| Works    | 31        | 37     | 36.9%   |
| Malfunc  | 6         | 6      | 7.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 45        | 42.45%  |
| Samsung Electronics          | 19        | 17.92%  |
| AMD                          | 14        | 13.21%  |
| Sandisk                      | 9         | 8.49%   |
| SK Hynix                     | 6         | 5.66%   |
| KIOXIA                       | 4         | 3.77%   |
| Kingston Technology Company  | 4         | 3.77%   |
| Zhaoxin                      | 1         | 0.94%   |
| Toshiba America Info Systems | 1         | 0.94%   |
| Shenzhen Longsys Electronics | 1         | 0.94%   |
| Micron Technology            | 1         | 0.94%   |
| ADATA Technology             | 1         | 0.94%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 12.28%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 6.14%   |
| Intel Volume Management Device NVMe RAID Controller                              | 7         | 6.14%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 4.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 5         | 4.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 5         | 4.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 4.39%   |
| Samsung NVMe SSD Controller 980                                                  | 4         | 3.51%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 3.51%   |
| SK Hynix Gold P31 SSD                                                            | 3         | 2.63%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 3         | 2.63%   |
| KIOXIA Non-Volatile memory controller                                            | 3         | 2.63%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 2.63%   |
| Intel SSD 660P Series                                                            | 3         | 2.63%   |
| Intel Non-Volatile memory controller                                             | 3         | 2.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 2.63%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 1.75%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 2         | 1.75%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 1.75%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.75%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 2         | 1.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 2         | 1.75%   |
| Zhaoxin ZX-100/ZX-200/ZX-E StorX AHCI Controller                                 | 1         | 0.88%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.88%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 0.88%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                      | 1         | 0.88%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.88%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 1         | 0.88%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 1         | 0.88%   |
| Micron Non-Volatile memory controller                                            | 1         | 0.88%   |
| KIOXIA NVMe SSD                                                                  | 1         | 0.88%   |
| Kingston Company A2000 NVMe SSD                                                  | 1         | 0.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 1         | 0.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 1         | 0.88%   |
| Intel Comet Lake SATA AHCI Controller                                            | 1         | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 1         | 0.88%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 1         | 0.88%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 1         | 0.88%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 1         | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 1         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 0.88%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 1         | 0.88%   |
| AMD FCH IDE Controller                                                           | 1         | 0.88%   |
| AMD 400 Series Chipset SATA Controller                                           | 1         | 0.88%   |
| ADATA Non-Volatile memory controller                                             | 1         | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 48        | 44.04%  |
| SATA | 46        | 42.2%   |
| RAID | 12        | 11.01%  |
| IDE  | 3         | 2.75%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 60        | 74.07%  |
| AMD          | 20        | 24.69%  |
| CentaurHauls | 1         | 1.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz              | 4         | 4.94%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 4         | 4.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 4         | 4.94%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 3         | 3.7%    |
| AMD Ryzen 7 4800HS with Radeon Graphics        | 3         | 3.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics         | 2         | 2.47%   |
| AMD Ryzen 5 4500U with Radeon Graphics         | 2         | 2.47%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 2         | 2.47%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz    | 1         | 1.23%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz         | 1         | 1.23%   |
| Intel Pentium 3558U @ 1.70GHz                  | 1         | 1.23%   |
| Intel Genuine CPU U7300 @ 1.30GHz              | 1         | 1.23%   |
| Intel Core i7-9750H CPU @ 2.60GHz              | 1         | 1.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 1         | 1.23%   |
| Intel Core i7-8665U CPU @ 1.90GHz              | 1         | 1.23%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 1         | 1.23%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 1         | 1.23%   |
| Intel Core i7-6820HK CPU @ 2.70GHz             | 1         | 1.23%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz             | 1         | 1.23%   |
| Intel Core i7-4510U CPU @ 2.00GHz              | 1         | 1.23%   |
| Intel Core i7-10870H CPU @ 2.20GHz             | 1         | 1.23%   |
| Intel Core i5-8365U CPU @ 1.60GHz              | 1         | 1.23%   |
| Intel Core i5-8300H CPU @ 2.30GHz              | 1         | 1.23%   |
| Intel Core i5-7360U CPU @ 2.30GHz              | 1         | 1.23%   |
| Intel Core i5-6300U CPU @ 2.40GHz              | 1         | 1.23%   |
| Intel Core i5-5300U CPU @ 2.30GHz              | 1         | 1.23%   |
| Intel Core i5-4220Y CPU @ 1.60GHz              | 1         | 1.23%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 1         | 1.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz             | 1         | 1.23%   |
| Intel Core i5 CPU M 560 @ 2.67GHz              | 1         | 1.23%   |
| Intel Core i5 CPU M 520 @ 2.40GHz              | 1         | 1.23%   |
| Intel Core i3-4005U CPU @ 1.70GHz              | 1         | 1.23%   |
| Intel Core i3-3217U CPU @ 1.80GHz              | 1         | 1.23%   |
| Intel Core i3-2330M CPU @ 2.20GHz              | 1         | 1.23%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz             | 1         | 1.23%   |
| Intel Core i3 CPU M 370 @ 2.40GHz              | 1         | 1.23%   |
| Intel Core i3 CPU M 350 @ 2.27GHz              | 1         | 1.23%   |
| Intel Core i3 CPU M 330 @ 2.13GHz              | 1         | 1.23%   |
| Intel Core 2 Duo CPU T6670 @ 2.20GHz           | 1         | 1.23%   |
| Intel Celeron N4020 CPU @ 1.10GHz              | 1         | 1.23%   |
| Intel Celeron N4000 CPU @ 1.10GHz              | 1         | 1.23%   |
| Intel Celeron CPU N3060 @ 1.60GHz              | 1         | 1.23%   |
| Intel Celeron CPU N2840 @ 2.16GHz              | 1         | 1.23%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz              | 1         | 1.23%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz              | 1         | 1.23%   |
| Intel 12th Gen Core i9-12900H                  | 1         | 1.23%   |
| Intel 12th Gen Core i7-12700H                  | 1         | 1.23%   |
| Intel 11th Gen Core i9-11950H @ 2.60GHz        | 1         | 1.23%   |
| Intel 11th Gen Core i9-11900H @ 2.50GHz        | 1         | 1.23%   |
| Intel 11th Gen Core i7-1195G7 @ 2.90GHz        | 1         | 1.23%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz        | 1         | 1.23%   |
| Intel 11th Gen Core i5-1155G7 @ 2.50GHz        | 1         | 1.23%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz        | 1         | 1.23%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 1         | 1.23%   |
| AMD Ryzen 9 5900HX with Radeon Graphics        | 1         | 1.23%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics     | 1         | 1.23%   |
| AMD Ryzen 7 5800U with Radeon Graphics         | 1         | 1.23%   |
| AMD Ryzen 7 5800H with Radeon Graphics         | 1         | 1.23%   |
| AMD Ryzen 7 4700U with Radeon Graphics         | 1         | 1.23%   |
| AMD Ryzen 7 3700X 8-Core Processor             | 1         | 1.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Other                   | 20        | 24.69%  |
| Intel Core i5           | 14        | 17.28%  |
| Intel Core i7           | 9         | 11.11%  |
| AMD Ryzen 7             | 9         | 11.11%  |
| Intel Core i3           | 7         | 8.64%   |
| AMD Ryzen 5             | 7         | 8.64%   |
| Intel Celeron           | 4         | 4.94%   |
| Intel Atom              | 2         | 2.47%   |
| Intel Pentium Dual-Core | 1         | 1.23%   |
| Intel Pentium Dual      | 1         | 1.23%   |
| Intel Pentium           | 1         | 1.23%   |
| Intel Genuine           | 1         | 1.23%   |
| Intel Core 2 Duo        | 1         | 1.23%   |
| AMD Ryzen 9             | 1         | 1.23%   |
| AMD Ryzen 7 PRO         | 1         | 1.23%   |
| AMD A4                  | 1         | 1.23%   |
| AMD A10                 | 1         | 1.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 29        | 35.8%   |
| 2      | 25        | 30.86%  |
| 8      | 18        | 22.22%  |
| 6      | 7         | 8.64%   |
| 14     | 2         | 2.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 81        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 65        | 80.25%  |
| 1      | 16        | 19.75%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 81        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 41        | 50%     |
| 0x806c1    | 6         | 7.32%   |
| 0x806ea    | 4         | 4.88%   |
| 0x806ec    | 3         | 3.66%   |
| 0x806d1    | 3         | 3.66%   |
| 0x0a50000c | 3         | 3.66%   |
| 0x08600104 | 3         | 3.66%   |
| 0x906a3    | 2         | 2.44%   |
| 0x40651    | 2         | 2.44%   |
| 0x20655    | 2         | 2.44%   |
| 0x906ea    | 1         | 1.22%   |
| 0x806e9    | 1         | 1.22%   |
| 0x806c2    | 1         | 1.22%   |
| 0x706e5    | 1         | 1.22%   |
| 0x706a8    | 1         | 1.22%   |
| 0x6fd      | 1         | 1.22%   |
| 0x306a9    | 1         | 1.22%   |
| 0x1067a    | 1         | 1.22%   |
| 0x08701013 | 1         | 1.22%   |
| 0x08608103 | 1         | 1.22%   |
| 0x08600106 | 1         | 1.22%   |
| 0x0810100b | 1         | 1.22%   |
| 0x06001119 | 1         | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 13        | 16.05%  |
| TigerLake        | 10        | 12.35%  |
| Zen 2            | 9         | 11.11%  |
| Haswell          | 6         | 7.41%   |
| Unknown          | 6         | 7.41%   |
| Zen 3            | 5         | 6.17%   |
| Westmere         | 5         | 6.17%   |
| Silvermont       | 4         | 4.94%   |
| Icelake          | 4         | 4.94%   |
| Penryn           | 3         | 3.7%    |
| Zen+             | 2         | 2.47%   |
| Skylake          | 2         | 2.47%   |
| Goldmont plus    | 2         | 2.47%   |
| Alderlake Hybrid | 2         | 2.47%   |
| Zen              | 1         | 1.23%   |
| SandyBridge      | 1         | 1.23%   |
| Piledriver       | 1         | 1.23%   |
| Jaguar           | 1         | 1.23%   |
| IvyBridge        | 1         | 1.23%   |
| Core             | 1         | 1.23%   |
| CometLake        | 1         | 1.23%   |
| Broadwell        | 1         | 1.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 54        | 50.94%  |
| Nvidia  | 30        | 28.3%   |
| AMD     | 21        | 19.81%  |
| Zhaoxin | 1         | 0.94%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 9.26%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 7         | 6.48%   |
| AMD Renoir                                                                               | 6         | 5.56%   |
| Intel UHD Graphics 620                                                                   | 5         | 4.63%   |
| AMD Cezanne                                                                              | 5         | 4.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 3.7%    |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 3         | 2.78%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 2.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 2.78%   |
| Nvidia TU117M                                                                            | 2         | 1.85%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 1.85%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.85%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 1.85%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 1.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.85%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 1.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.85%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 2         | 1.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.85%   |
| Zhaoxin ZX-E C-960 GPU                                                                   | 1         | 0.93%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.93%   |
| Nvidia TU117GLM [T600 Mobile]                                                            | 1         | 0.93%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.93%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 1         | 0.93%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.93%   |
| Nvidia GT215M [GeForce GT 335M]                                                          | 1         | 0.93%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.93%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.93%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Max-Q]                                                | 1         | 0.93%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.93%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.93%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.93%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.93%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.93%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                            | 1         | 0.93%   |
| Nvidia GA103M [GeForce RTX 3080 Ti Mobile]                                               | 1         | 0.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 1         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 0.93%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 0.93%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 0.93%   |
| Intel Iris Plus Graphics 640                                                             | 1         | 0.93%   |
| Intel HD Graphics 5500                                                                   | 1         | 0.93%   |
| Intel Haswell-ULT High Definition Audio Controller [HD Graphics]                         | 1         | 0.93%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 1         | 0.93%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1         | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 1         | 0.93%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 1         | 0.93%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1         | 0.93%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1         | 0.93%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.93%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 1         | 0.93%   |
| AMD RV710/M92 [Mobility Radeon HD 4330/4350/4550]                                        | 1         | 0.93%   |
| AMD Richland [Radeon HD 8610G]                                                           | 1         | 0.93%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1         | 0.93%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 1         | 0.93%   |
| AMD Lucienne                                                                             | 1         | 0.93%   |
| AMD Kabini [Radeon HD 8330]                                                              | 1         | 0.93%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 32        | 39.51%  |
| Intel + Nvidia | 19        | 23.46%  |
| 1 x AMD        | 14        | 17.28%  |
| 1 x Nvidia     | 7         | 8.64%   |
| AMD + Nvidia   | 4         | 4.94%   |
| Intel + AMD    | 2         | 2.47%   |
| Other          | 1         | 1.23%   |
| 2 x AMD        | 1         | 1.23%   |
| 1 x Zhaoxin    | 1         | 1.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 62        | 76.54%  |
| Proprietary | 18        | 22.22%  |
| Unknown     | 1         | 1.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 78.05%  |
| 3.01-4.0   | 5         | 6.1%    |
| 0.01-0.5   | 5         | 6.1%    |
| 1.01-2.0   | 3         | 3.66%   |
| 7.01-8.0   | 2         | 2.44%   |
| 0.51-1.0   | 2         | 2.44%   |
| 5.01-6.0   | 1         | 1.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 20        | 21.74%  |
| AU Optronics        | 18        | 19.57%  |
| Samsung Electronics | 12        | 13.04%  |
| LG Display          | 9         | 9.78%   |
| Chimei Innolux      | 8         | 8.7%    |
| Dell                | 3         | 3.26%   |
| CSO                 | 3         | 3.26%   |
| BenQ                | 3         | 3.26%   |
| AOC                 | 3         | 3.26%   |
| Sharp               | 2         | 2.17%   |
| PANDA               | 2         | 2.17%   |
| Philips             | 1         | 1.09%   |
| OEM                 | 1         | 1.09%   |
| Microstep           | 1         | 1.09%   |
| JDI                 | 1         | 1.09%   |
| InfoVision          | 1         | 1.09%   |
| HUAWEI              | 1         | 1.09%   |
| Hewlett-Packard     | 1         | 1.09%   |
| Goldstar            | 1         | 1.09%   |
| Apple               | 1         | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch    | 2         | 2.15%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                   | 2         | 2.15%   |
| Sharp LQ173M1JW05 SHP14EC 1920x1080 382x215mm 17.3-inch                 | 1         | 1.08%   |
| Sharp LQ156M1JW16 SHP14F4 1920x1080 344x194mm 15.5-inch                 | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch    | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3842 1366x768 309x174mm 14.0-inch    | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 331x207mm 15.4-inch    | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SDC4C51 1366x768 344x194mm 15.5-inch    | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch    | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 344x194mm 15.5-inch    | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SDC3147 1920x1080 276x155mm 12.5-inch   | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SAM0B60 1920x1080 887x500mm 40.1-inch   | 1         | 1.08%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 890x500mm 40.2-inch   | 1         | 1.08%   |
| Philips PHL 245E1 PHLC20B 2560x1440 527x296mm 23.8-inch                 | 1         | 1.08%   |
| PANDA LCD Monitor NCP005C 2560x1600 302x189mm 14.0-inch                 | 1         | 1.08%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                 | 1         | 1.08%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                         | 1         | 1.08%   |
| Microstep LCD Monitor Optix AG32CQ                                      | 1         | 1.08%   |
| LG Display LCD Monitor LGD06AA 3840x2400 344x215mm 16.0-inch            | 1         | 1.08%   |
| LG Display LCD Monitor LGD0671 1920x1080 382x215mm 17.3-inch            | 1         | 1.08%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch            | 1         | 1.08%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch            | 1         | 1.08%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch            | 1         | 1.08%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch            | 1         | 1.08%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 1         | 1.08%   |
| LG Display LCD Monitor LGD02AD 1366x768 344x194mm 15.5-inch             | 1         | 1.08%   |
| LG Display LCD Monitor LGD018B 1366x768 310x174mm 14.0-inch             | 1         | 1.08%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                   | 1         | 1.08%   |
| InfoVision LCD Monitor IVO8C5F 1920x1080 309x174mm 14.0-inch            | 1         | 1.08%   |
| HUAWEI ZQE-CAA HWV6A25 3440x1440 797x334mm 34.0-inch                    | 1         | 1.08%   |
| Hewlett-Packard W2071d HWP299C 1600x900 443x249mm 20.0-inch             | 1         | 1.08%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                | 1         | 1.08%   |
| Dell S2721QS DELA196 3840x2160 597x336mm 27.0-inch                      | 1         | 1.08%   |
| Dell S2240L DELD053 1920x1080 476x267mm 21.5-inch                       | 1         | 1.08%   |
| Dell E178FP DELA027 1280x1024 338x270mm 17.0-inch                       | 1         | 1.08%   |
| CSO LCD Monitor CSO1609 2560x1600 345x215mm 16.0-inch                   | 1         | 1.08%   |
| CSO LCD Monitor CSO140C 2880x1800 302x188mm 14.0-inch                   | 1         | 1.08%   |
| CSO LCD Monitor CSO140C 2880x1800 300x190mm 14.0-inch                   | 1         | 1.08%   |
| CSO LCD Monitor CSO1407 3840x2160 309x174mm 14.0-inch                   | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch        | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15CB 1920x1080 344x193mm 15.5-inch        | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch         | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch        | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN141E 1920x1080 309x173mm 13.9-inch        | 1         | 1.08%   |
| Chimei Innolux LCD Monitor CMN1400 1920x1080 309x173mm 13.9-inch        | 1         | 1.08%   |
| BOE LCD Monitor BOE0A5D 1366x768 256x144mm 11.6-inch                    | 1         | 1.08%   |
| BOE LCD Monitor BOE09D0 1920x1080 309x174mm 14.0-inch                   | 1         | 1.08%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                   | 1         | 1.08%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 1         | 1.08%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                   | 1         | 1.08%   |
| BOE LCD Monitor BOE0919 3840x2160 344x194mm 15.5-inch                   | 1         | 1.08%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                   | 1         | 1.08%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                   | 1         | 1.08%   |
| BOE LCD Monitor BOE0864 1920x1080 344x194mm 15.5-inch                   | 1         | 1.08%   |
| BOE LCD Monitor BOE0852 1920x1080 344x194mm 15.5-inch                   | 1         | 1.08%   |
| BOE LCD Monitor BOE084A 1920x1080 344x194mm 15.5-inch                   | 1         | 1.08%   |
| BOE LCD Monitor BOE07F8 1366x768 256x144mm 11.6-inch                    | 1         | 1.08%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 41        | 45.05%  |
| 1366x768 (WXGA)  | 17        | 18.68%  |
| 3840x2160 (4K)   | 6         | 6.59%   |
| 2560x1600        | 4         | 4.4%    |
| 2560x1440 (QHD)  | 4         | 4.4%    |
| 1600x900 (HD+)   | 3         | 3.3%    |
| 2880x1800        | 2         | 2.2%    |
| 2256x1504        | 2         | 2.2%    |
| 1280x1024 (SXGA) | 2         | 2.2%    |
| 6400x2160        | 1         | 1.1%    |
| 3840x2400        | 1         | 1.1%    |
| 3440x1440        | 1         | 1.1%    |
| 3000x2000        | 1         | 1.1%    |
| 2560x1080        | 1         | 1.1%    |
| 2520x1680        | 1         | 1.1%    |
| 2240x1400        | 1         | 1.1%    |
| 1920x540         | 1         | 1.1%    |
| 1280x800 (WXGA)  | 1         | 1.1%    |
| Unknown          | 1         | 1.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 33        | 36.26%  |
| 13      | 12        | 13.19%  |
| 14      | 11        | 12.09%  |
| 17      | 7         | 7.69%   |
| 16      | 5         | 5.49%   |
| 11      | 5         | 5.49%   |
| 27      | 4         | 4.4%    |
| 24      | 3         | 3.3%    |
| 34      | 2         | 2.2%    |
| 84      | 1         | 1.1%    |
| 54      | 1         | 1.1%    |
| 40      | 1         | 1.1%    |
| 33      | 1         | 1.1%    |
| 21      | 1         | 1.1%    |
| 20      | 1         | 1.1%    |
| 12      | 1         | 1.1%    |
| 10      | 1         | 1.1%    |
| Unknown | 1         | 1.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 52        | 57.78%  |
| 201-300     | 15        | 16.67%  |
| 501-600     | 7         | 7.78%   |
| 351-400     | 7         | 7.78%   |
| 701-800     | 3         | 3.33%   |
| 401-500     | 2         | 2.22%   |
| 801-900     | 1         | 1.11%   |
| 1501-2000   | 1         | 1.11%   |
| 1001-1500   | 1         | 1.11%   |
| Unknown     | 1         | 1.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 64        | 77.11%  |
| 16/10   | 10        | 12.05%  |
| 3/2     | 4         | 4.82%   |
| 5/4     | 2         | 2.41%   |
| 21/9    | 2         | 2.41%   |
| Unknown | 1         | 1.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 33        | 36.26%  |
| 81-90          | 20        | 21.98%  |
| 51-60          | 5         | 5.49%   |
| 121-130        | 5         | 5.49%   |
| 111-120        | 5         | 5.49%   |
| 301-350        | 4         | 4.4%    |
| 71-80          | 3         | 3.3%    |
| 351-500        | 3         | 3.3%    |
| More than 1000 | 2         | 2.2%    |
| 201-250        | 2         | 2.2%    |
| 151-200        | 2         | 2.2%    |
| 141-150        | 2         | 2.2%    |
| 61-70          | 1         | 1.1%    |
| 41-50          | 1         | 1.1%    |
| 251-300        | 1         | 1.1%    |
| 501-1000       | 1         | 1.1%    |
| Unknown        | 1         | 1.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 40        | 44.44%  |
| 51-100        | 15        | 16.67%  |
| 101-120       | 14        | 15.56%  |
| 161-240       | 13        | 14.44%  |
| More than 240 | 6         | 6.67%   |
| 1-50          | 1         | 1.11%   |
| Unknown       | 1         | 1.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 60        | 73.17%  |
| 2     | 17        | 20.73%  |
| 0     | 5         | 6.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 48        | 39.02%  |
| Realtek Semiconductor    | 44        | 35.77%  |
| Qualcomm Atheros         | 16        | 13.01%  |
| Broadcom                 | 5         | 4.07%   |
| Ralink                   | 2         | 1.63%   |
| MEDIATEK                 | 2         | 1.63%   |
| Sierra Wireless          | 1         | 0.81%   |
| Qualcomm                 | 1         | 0.81%   |
| Marvell Technology Group | 1         | 0.81%   |
| JMicron Technology       | 1         | 0.81%   |
| Broadcom Limited         | 1         | 0.81%   |
| ASIX Electronics         | 1         | 0.81%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 19        | 13.97%  |
| Intel Wi-Fi 6 AX200                                                            | 13        | 9.56%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7         | 5.15%   |
| Intel Wi-Fi 6 AX201                                                            | 7         | 5.15%   |
| Intel Wireless 7265                                                            | 5         | 3.68%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                         | 5         | 3.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 2.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                     | 4         | 2.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 3         | 2.21%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 2.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 3         | 2.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                 | 3         | 2.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                                | 3         | 2.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                       | 2         | 1.47%   |
| Realtek RTL8188EE Wireless Network Adapter                                     | 2         | 1.47%   |
| Realtek Realtek Ethernet controller                                            | 2         | 1.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                 | 2         | 1.47%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter                  | 2         | 1.47%   |
| Intel Wireless 3165                                                            | 2         | 1.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 2         | 1.47%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 1.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                               | 2         | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                            | 2         | 1.47%   |
| Sierra Wireless EM7305                                                         | 1         | 0.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                | 1         | 0.74%   |
| Realtek RTL8191SEvA Wireless LAN Controller                                    | 1         | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                            | 1         | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.74%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.74%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1         | 0.74%   |
| Realtek 802.11n WLAN Adapter                                                   | 1         | 0.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.74%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                      | 1         | 0.74%   |
| Qualcomm QCNFA765 Wireless Network Adapter                                     | 1         | 0.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                     | 1         | 0.74%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.74%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.74%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.74%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.74%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.74%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.74%   |
| Intel Wireless-AC 9260                                                         | 1         | 0.74%   |
| Intel Wireless 8265 / 8275                                                     | 1         | 0.74%   |
| Intel Wireless 8260                                                            | 1         | 0.74%   |
| Intel Wireless 7260                                                            | 1         | 0.74%   |
| Intel Gemini Lake PCH CNVi WiFi                                                | 1         | 0.74%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.74%   |
| Intel Ethernet Connection I218-V                                               | 1         | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.74%   |
| Intel Ethernet Connection (14) I219-V                                          | 1         | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                              | 1         | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                       | 1         | 0.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 0.74%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.74%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                      | 1         | 0.74%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter                             | 1         | 0.74%   |
| Broadcom BCM43224 802.11a/b/g/n                                                | 1         | 0.74%   |
| Broadcom BCM43142 802.11b/g/n                                                  | 1         | 0.74%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.74%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 46        | 56.79%  |
| Qualcomm Atheros      | 13        | 16.05%  |
| Realtek Semiconductor | 10        | 12.35%  |
| Broadcom              | 5         | 6.17%   |
| Ralink                | 2         | 2.47%   |
| MEDIATEK              | 2         | 2.47%   |
| Sierra Wireless       | 1         | 1.23%   |
| Qualcomm              | 1         | 1.23%   |
| Broadcom Limited      | 1         | 1.23%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 13        | 15.85%  |
| Intel Wi-Fi 6 AX201                                            | 7         | 8.54%   |
| Intel Wireless 7265                                            | 5         | 6.1%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 6.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 4.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 3.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 3.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 3.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 3.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.44%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 2.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 2.44%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 2.44%   |
| Intel Wireless 3165                                            | 2         | 2.44%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 2.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 2.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 2.44%   |
| Sierra Wireless EM7305                                         | 1         | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.22%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 1         | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.22%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 1.22%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.22%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.22%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.22%   |
| Intel Wireless-AC 9260                                         | 1         | 1.22%   |
| Intel Wireless 8265 / 8275                                     | 1         | 1.22%   |
| Intel Wireless 8260                                            | 1         | 1.22%   |
| Intel Wireless 7260                                            | 1         | 1.22%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.22%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 1         | 1.22%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 1         | 1.22%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                  | 1         | 1.22%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 38        | 70.37%  |
| Intel                    | 8         | 14.81%  |
| Qualcomm Atheros         | 5         | 9.26%   |
| Marvell Technology Group | 1         | 1.85%   |
| JMicron Technology       | 1         | 1.85%   |
| ASIX Electronics         | 1         | 1.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 19        | 35.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 7         | 12.96%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4         | 7.41%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 5.56%   |
| Realtek Realtek Ethernet controller                                            | 2         | 3.7%    |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 3.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 1.85%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 1.85%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1         | 1.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 1.85%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 1.85%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 1.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 1.85%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 1.85%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 1.85%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 1.85%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 1.85%   |
| Intel Ethernet Connection I218-V                                               | 1         | 1.85%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 1.85%   |
| Intel Ethernet Connection (14) I219-V                                          | 1         | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 1.85%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 1.85%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 1.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 80        | 59.7%   |
| Ethernet | 54        | 40.3%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 73        | 73%     |
| Ethernet | 27        | 27%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 49        | 60.49%  |
| 1     | 30        | 37.04%  |
| 0     | 2         | 2.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 57        | 69.51%  |
| Yes  | 25        | 30.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 46        | 65.71%  |
| Qualcomm Atheros Communications | 7         | 10%     |
| Realtek Semiconductor           | 5         | 7.14%   |
| IMC Networks                    | 3         | 4.29%   |
| Toshiba                         | 1         | 1.43%   |
| Realtek                         | 1         | 1.43%   |
| Ralink Technology               | 1         | 1.43%   |
| Ralink                          | 1         | 1.43%   |
| Lite-On Technology              | 1         | 1.43%   |
| Foxconn / Hon Hai               | 1         | 1.43%   |
| Dell                            | 1         | 1.43%   |
| Cambridge Silicon Radio         | 1         | 1.43%   |
| Broadcom                        | 1         | 1.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX200 Bluetooth                               | 13        | 18.57%  |
| Intel Bluetooth wireless interface                  | 10        | 14.29%  |
| Intel Bluetooth Device                              | 9         | 12.86%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 11.43%  |
| Intel AX210 Bluetooth                               | 5         | 7.14%   |
| Realtek Bluetooth Radio                             | 3         | 4.29%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 4.29%   |
| Qualcomm Atheros  Bluetooth Device                  | 2         | 2.86%   |
| IMC Networks Wireless_Device                        | 2         | 2.86%   |
| Toshiba Bluetooth Device                            | 1         | 1.43%   |
| Realtek RTL8723B Bluetooth                          | 1         | 1.43%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 1.43%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 1.43%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 1.43%   |
| Ralink RT3290 Bluetooth                             | 1         | 1.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 1.43%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 1.43%   |
| Lite-On Bluetooth Device                            | 1         | 1.43%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 1.43%   |
| IMC Networks Bluetooth Radio                        | 1         | 1.43%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 1.43%   |
| Dell Wireless 365 Bluetooth                         | 1         | 1.43%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 1.43%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 1         | 1.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 59        | 56.19%  |
| AMD                 | 22        | 20.95%  |
| Nvidia              | 21        | 20%     |
| Zhaoxin             | 1         | 0.95%   |
| Creative Technology | 1         | 0.95%   |
| Corsair             | 1         | 0.95%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 13.18%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 8.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 7.75%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 7         | 5.43%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 7         | 5.43%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 5         | 3.88%   |
| Nvidia Audio device                                                                               | 5         | 3.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 3.88%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 3.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 3.88%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 3.1%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 2.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 2.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 2         | 1.55%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 2         | 1.55%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.55%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1         | 0.78%   |
| Zhaoxin ZX-100/ZX-D/ZX-E High Definition Audio Controller                                         | 1         | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.78%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.78%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.78%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.78%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 1         | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 1         | 0.78%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.78%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series Low Power Engine Audio           | 1         | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 1         | 0.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1         | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 0.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.78%   |
| Creative Technology Sound Blaster Premium HD [SBX]                                                | 1         | 0.78%   |
| Corsair HS80 RGB Wireless Gaming Receiver                                                         | 1         | 0.78%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.78%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1         | 0.78%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.78%   |
| AMD Kabini HDMI/DP Audio                                                                          | 1         | 0.78%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.78%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 30.51%  |
| SK Hynix            | 10        | 16.95%  |
| Micron Technology   | 9         | 15.25%  |
| Kingston            | 5         | 8.47%   |
| Crucial             | 5         | 8.47%   |
| Ramaxel Technology  | 2         | 3.39%   |
| A-DATA Technology   | 2         | 3.39%   |
| Unknown (ABCD)      | 1         | 1.69%   |
| Unknown             | 1         | 1.69%   |
| Team                | 1         | 1.69%   |
| Shenzhen WODPOSIT   | 1         | 1.69%   |
| GOODRAM             | 1         | 1.69%   |
| G.Skill             | 1         | 1.69%   |
| Corsair             | 1         | 1.69%   |
| ASint Technology    | 1         | 1.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 2         | 3.28%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 3.28%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 2         | 3.28%   |
| Samsung RAM M425R2GA3BB0-CQKOD 16GB SODIMM 4800MT/s                 | 2         | 3.28%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 1.64%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 1         | 1.64%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 1.64%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s                | 1         | 1.64%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2667MT/s                        | 1         | 1.64%   |
| SK Hynix RAM Module 2GB DDR3 1600MT/s                               | 1         | 1.64%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 3200MT/s                       | 1         | 1.64%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.64%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s              | 1         | 1.64%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 1.64%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s          | 1         | 1.64%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 1.64%   |
| SK Hynix RAM HMA851S6CJR6N-UH 4GB SODIMM DDR4 2400MT/s              | 1         | 1.64%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 1.64%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s               | 1         | 1.64%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 1         | 1.64%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.64%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 1         | 1.64%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1.64%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 1.64%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 1.64%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 1.64%   |
| Samsung RAM M471A1K43CB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 1         | 1.64%   |
| Samsung RAM K4E6E304EB-EGCF 4GB Row Of Chips LPDDR3 1867MT/s        | 1         | 1.64%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s                | 1         | 1.64%   |
| Ramaxel RAM RMT3020EF48E8W1333 2GB SODIMM DDR3 1334MT/s             | 1         | 1.64%   |
| Ramaxel RAM RMSA3260NA78HAF-2666 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.64%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s                  | 1         | 1.64%   |
| Micron RAM MT53E1G32D4NQ-046WTE 8GB Row Of Chips LPDDR4 4266MT/s    | 1         | 1.64%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 1         | 1.64%   |
| Micron RAM MT40A1G16RC-062E:B 8GB Row Of Chips DDR4 3200MT/s        | 1         | 1.64%   |
| Micron RAM Module 4GB SODIMM LPDDR3 2133MT/s                        | 1         | 1.64%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.64%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 1         | 1.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 1         | 1.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 1         | 1.64%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s                | 1         | 1.64%   |
| Kingston RAM KF3200C20S4/8G 8GB SODIMM DDR4 3200MT/s                | 1         | 1.64%   |
| Kingston RAM 9905700-095.A00G 16GB SODIMM DDR4 3200MT/s             | 1         | 1.64%   |
| Kingston RAM 9905700-046.A00G 16384MB SODIMM DDR4 3200MT/s          | 1         | 1.64%   |
| Kingston RAM 9905624-044.A00G 8GB SODIMM DDR4 2400MT/s              | 1         | 1.64%   |
| GOODRAM RAM GR1333S364L9/4G 4GB SODIMM DDR3 1333MT/s                | 1         | 1.64%   |
| G.Skill RAM F4-3200C22-32GRS 32GB SODIMM DDR4 3200MT/s              | 1         | 1.64%   |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| Crucial RAM CT32G4SFD832A.M16FB 32GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| Crucial RAM CT32G4SFD832A.C16FE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| Crucial RAM CT16G4SFRA32A.C8FE 16GB SODIMM DDR4 3200MT/s            | 1         | 1.64%   |
| Crucial RAM CT16G4SFD832A.M16FR 16GB SODIMM DDR4 3200MT/s           | 1         | 1.64%   |
| Corsair RAM CMSX32GX4M2A2933C19 16GB SODIMM DDR4 2933MT/s           | 1         | 1.64%   |
| ASint RAM SSZ3128M8-EAEEF 2GB SODIMM DDR3 1067MT/s                  | 1         | 1.64%   |
| A-DATA RAM Module 32GB SODIMM DDR4 3200MT/s                         | 1         | 1.64%   |
| A-DATA RAM AO1P26KC8T1-BPXS 8GB SODIMM DDR4 2667MT/s                | 1         | 1.64%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 31        | 63.27%  |
| DDR3    | 8         | 16.33%  |
| LPDDR3  | 3         | 6.12%   |
| SDRAM   | 2         | 4.08%   |
| LPDDR4  | 2         | 4.08%   |
| Unknown | 2         | 4.08%   |
| DDR2    | 1         | 2.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 40        | 83.33%  |
| Row Of Chips | 7         | 14.58%  |
| Unknown      | 1         | 2.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 21        | 37.5%   |
| 16384 | 11        | 19.64%  |
| 4096  | 10        | 17.86%  |
| 32768 | 7         | 12.5%   |
| 2048  | 6         | 10.71%  |
| 1024  | 1         | 1.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 21        | 41.18%  |
| 2667  | 8         | 15.69%  |
| 1600  | 6         | 11.76%  |
| 4800  | 2         | 3.92%   |
| 4199  | 2         | 3.92%   |
| 2400  | 2         | 3.92%   |
| 2133  | 2         | 3.92%   |
| 4266  | 1         | 1.96%   |
| 2933  | 1         | 1.96%   |
| 2666  | 1         | 1.96%   |
| 1867  | 1         | 1.96%   |
| 1334  | 1         | 1.96%   |
| 1333  | 1         | 1.96%   |
| 1067  | 1         | 1.96%   |
| 667   | 1         | 1.96%   |

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
| Chicony Electronics                    | 17        | 25.76%  |
| IMC Networks                           | 8         | 12.12%  |
| Microdia                               | 6         | 9.09%   |
| Acer                                   | 5         | 7.58%   |
| Realtek Semiconductor                  | 4         | 6.06%   |
| Quanta                                 | 4         | 6.06%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 6.06%   |
| Syntek                                 | 3         | 4.55%   |
| Luxvisions Innotech Limited            | 3         | 4.55%   |
| Z-Star Microelectronics                | 1         | 1.52%   |
| Y Media                                | 1         | 1.52%   |
| USB Camera                             | 1         | 1.52%   |
| Suyin                                  | 1         | 1.52%   |
| Sunplus Innovation Technology          | 1         | 1.52%   |
| Sonix Technology                       | 1         | 1.52%   |
| ShineTech                              | 1         | 1.52%   |
| Ricoh                                  | 1         | 1.52%   |
| Lite-On Technology                     | 1         | 1.52%   |
| Importek                               | 1         | 1.52%   |
| DJKANA1BIELN56                         | 1         | 1.52%   |
| Creative Technology                    | 1         | 1.52%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 5         | 7.46%   |
| Chicony HP HD Camera                                         | 4         | 5.97%   |
| Microdia Integrated_Webcam_HD                                | 3         | 4.48%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 3         | 4.48%   |
| IMC Networks Integrated Camera                               | 3         | 4.48%   |
| Syntek Lenovo EasyCamera                                     | 2         | 2.99%   |
| Quanta HP HD Camera                                          | 2         | 2.99%   |
| Chicony TOSHIBA Web Camera - HD                              | 2         | 2.99%   |
| Chicony HD WebCam                                            | 2         | 2.99%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 2         | 2.99%   |
| Acer HD Camera                                               | 2         | 2.99%   |
| Z-Star WebCam SCB-1900N                                      | 1         | 1.49%   |
| Y Media USB Camera                                           | 1         | 1.49%   |
| USB Camera USB Camera                                        | 1         | 1.49%   |
| Syntek Integrated Camera                                     | 1         | 1.49%   |
| Suyin HP Webcam-101                                          | 1         | 1.49%   |
| Sunplus Dell HD Webcam                                       | 1         | 1.49%   |
| Sonix USB2.0 HD UVC WebCam                                   | 1         | 1.49%   |
| ShineTech HD Camera                                          | 1         | 1.49%   |
| Ricoh HD Webcam                                              | 1         | 1.49%   |
| Realtek Laptop Camera                                        | 1         | 1.49%   |
| Realtek Integrated Webcam                                    | 1         | 1.49%   |
| Realtek HP Wide Vision HD Camera                             | 1         | 1.49%   |
| Realtek HP "Truevision HD" laptop camera                     | 1         | 1.49%   |
| Quanta HD Webcam                                             | 1         | 1.49%   |
| Quanta HD User Facing                                        | 1         | 1.49%   |
| Microdia Webcam Vitade AF                                    | 1         | 1.49%   |
| Microdia Laptop_Integrated_Webcam_1.3M                       | 1         | 1.49%   |
| Microdia 1.3 MPixel Integrated Webcam                        | 1         | 1.49%   |
| Luxvisions Innotech Limited Integrated RGB Camera            | 1         | 1.49%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera          | 1         | 1.49%   |
| Luxvisions Innotech Limited EasyCamera 1M                    | 1         | 1.49%   |
| Lite-On HP HD Camera                                         | 1         | 1.49%   |
| Importek TOSHIBA Web Camera - HD                             | 1         | 1.49%   |
| IMC Networks Integrated Webcam                               | 1         | 1.49%   |
| IMC Networks HD Camera                                       | 1         | 1.49%   |
| DJKANA1BIELN56 HP Wide Vision HD Camera                      | 1         | 1.49%   |
| Creative Live! Cam Sync 1080p V2                             | 1         | 1.49%   |
| Chicony USB2.0 Camera                                        | 1         | 1.49%   |
| Chicony TOSHIBA Web Camera - 3M                              | 1         | 1.49%   |
| Chicony HP Wide Vision HD Camera                             | 1         | 1.49%   |
| Chicony HP Webcam                                            | 1         | 1.49%   |
| Chicony HP Truevision HD camera                              | 1         | 1.49%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                | 1         | 1.49%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera             | 1         | 1.49%   |
| Acer Integrated Camera                                       | 1         | 1.49%   |
| Acer HD Webcam                                               | 1         | 1.49%   |
| Acer BisonCam,NB Pro                                         | 1         | 1.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 6         | 37.5%   |
| Synaptics                  | 5         | 31.25%  |
| Validity Sensors           | 2         | 12.5%   |
| Elan Microelectronics      | 2         | 12.5%   |
| LighTuning Technology      | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 5         | 31.25%  |
| Unknown                                                                    | 3         | 18.75%  |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 12.5%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 6.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 6.25%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 6.25%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 6.25%   |
| Elan ELAN:Fingerprint                                                      | 1         | 6.25%   |
| Elan ELAN:ARM-M4                                                           | 1         | 6.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader            | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 49        | 59.76%  |
| 1     | 24        | 29.27%  |
| 2     | 9         | 10.98%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 16        | 40%     |
| Graphics card         | 10        | 25%     |
| Multimedia controller | 4         | 10%     |
| Sound                 | 3         | 7.5%    |
| Chipcard              | 3         | 7.5%    |
| Camera                | 2         | 5%      |
| Net/wireless          | 1         | 2.5%    |
| Bluetooth             | 1         | 2.5%    |

