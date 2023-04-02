Linux in Morocco - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Morocco.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Morocco/Desktop/README.md) and [notebooks](/Location/Morocco/Notebook/README.md).

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

Total: 357

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 89B4 A                      | Desktop     | [cb8136a176](https://linux-hardware.org/?probe=cb8136a176) | Mar 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [9fbd9476b2](https://linux-hardware.org/?probe=9fbd9476b2) | Mar 28, 2023 |
| Dell          | Latitude 5400               | Notebook    | [4e17f4827d](https://linux-hardware.org/?probe=4e17f4827d) | Mar 23, 2023 |
| Dell          | Latitude 5400               | Notebook    | [c85d243d8a](https://linux-hardware.org/?probe=c85d243d8a) | Mar 23, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [2a85ee4871](https://linux-hardware.org/?probe=2a85ee4871) | Mar 15, 2023 |
| Dell          | Latitude E5450              | Notebook    | [2f16482775](https://linux-hardware.org/?probe=2f16482775) | Mar 04, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [9ce5a599cd](https://linux-hardware.org/?probe=9ce5a599cd) | Mar 03, 2023 |
| Dell          | Latitude E6520              | Notebook    | [2774f2cb16](https://linux-hardware.org/?probe=2774f2cb16) | Mar 01, 2023 |
| ASUSTek       | X751LK                      | Notebook    | [f312f303e0](https://linux-hardware.org/?probe=f312f303e0) | Feb 26, 2023 |
| HP            | Pavilion g6                 | Notebook    | [39b27e9850](https://linux-hardware.org/?probe=39b27e9850) | Feb 19, 2023 |
| Dell          | Latitude E7450              | Notebook    | [16f40c9f6a](https://linux-hardware.org/?probe=16f40c9f6a) | Feb 17, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [41f9974254](https://linux-hardware.org/?probe=41f9974254) | Feb 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [b82ad16853](https://linux-hardware.org/?probe=b82ad16853) | Feb 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | Notebook    | [76dd43711a](https://linux-hardware.org/?probe=76dd43711a) | Feb 08, 2023 |
| Toshiba       | Satellite C855-1LG          | Notebook    | [26ce54002a](https://linux-hardware.org/?probe=26ce54002a) | Feb 05, 2023 |
| Dell          | Latitude 3500               | Notebook    | [79cdb991bf](https://linux-hardware.org/?probe=79cdb991bf) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [aa435d7701](https://linux-hardware.org/?probe=aa435d7701) | Feb 03, 2023 |
| Dell          | Latitude D630               | Notebook    | [b191402036](https://linux-hardware.org/?probe=b191402036) | Feb 03, 2023 |
| HP            | 18E7                        | Desktop     | [db4ef3e5f4](https://linux-hardware.org/?probe=db4ef3e5f4) | Jan 30, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [b33f2d5606](https://linux-hardware.org/?probe=b33f2d5606) | Jan 28, 2023 |
| Dell          | Latitude E6410              | Notebook    | [854634fb32](https://linux-hardware.org/?probe=854634fb32) | Jan 24, 2023 |
| Dell          | Latitude E6410              | Notebook    | [a5edbef8d2](https://linux-hardware.org/?probe=a5edbef8d2) | Jan 24, 2023 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [1f238129d8](https://linux-hardware.org/?probe=1f238129d8) | Jan 12, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [c5379f6dc1](https://linux-hardware.org/?probe=c5379f6dc1) | Jan 12, 2023 |
| Dell          | 0MN1TX A02                  | Desktop     | [e0099da561](https://linux-hardware.org/?probe=e0099da561) | Jan 11, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [2c092397ea](https://linux-hardware.org/?probe=2c092397ea) | Jan 05, 2023 |
| Dell          | Latitude 5510               | Notebook    | [68e4810231](https://linux-hardware.org/?probe=68e4810231) | Dec 24, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [15582a281d](https://linux-hardware.org/?probe=15582a281d) | Dec 17, 2022 |
| SINTRONES     | AMB-5000G1                  | Notebook    | [3f9a3badb0](https://linux-hardware.org/?probe=3f9a3badb0) | Dec 17, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [57fa4478d0](https://linux-hardware.org/?probe=57fa4478d0) | Dec 17, 2022 |
| SINTRONES     | AMB-5000G1                  | Notebook    | [b1738a6528](https://linux-hardware.org/?probe=b1738a6528) | Dec 17, 2022 |
| Dell          | Latitude D820               | Notebook    | [29df917188](https://linux-hardware.org/?probe=29df917188) | Dec 16, 2022 |
| Dell          | Latitude D820               | Notebook    | [27f19eafce](https://linux-hardware.org/?probe=27f19eafce) | Dec 16, 2022 |
| Dell          | Latitude E7250              | Notebook    | [3e40466ae4](https://linux-hardware.org/?probe=3e40466ae4) | Dec 13, 2022 |
| HP            | Pavilion 15                 | Notebook    | [5d88eed564](https://linux-hardware.org/?probe=5d88eed564) | Dec 13, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [5bbe558b2f](https://linux-hardware.org/?probe=5bbe558b2f) | Dec 05, 2022 |
| Lenovo        | ThinkPad T560 20FJS3YN00    | Notebook    | [636921b46c](https://linux-hardware.org/?probe=636921b46c) | Nov 24, 2022 |
| HP            | 15                          | Notebook    | [51711b792f](https://linux-hardware.org/?probe=51711b792f) | Nov 20, 2022 |
| HP            | EliteBook 8540w             | Notebook    | [4da059da1b](https://linux-hardware.org/?probe=4da059da1b) | Nov 14, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [c4e67c5f10](https://linux-hardware.org/?probe=c4e67c5f10) | Nov 13, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [d710968897](https://linux-hardware.org/?probe=d710968897) | Nov 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [451acdb910](https://linux-hardware.org/?probe=451acdb910) | Oct 31, 2022 |
| HP            | 15                          | Notebook    | [c356a2b0cd](https://linux-hardware.org/?probe=c356a2b0cd) | Oct 30, 2022 |
| HP            | 15                          | Notebook    | [34e1ac4cbe](https://linux-hardware.org/?probe=34e1ac4cbe) | Oct 30, 2022 |
| HP            | 2AA2                        | Desktop     | [36f40353c8](https://linux-hardware.org/?probe=36f40353c8) | Oct 25, 2022 |
| Linx          | LINX12X64                   | Tablet      | [132f0a1803](https://linux-hardware.org/?probe=132f0a1803) | Oct 24, 2022 |
| Linx          | LINX12X64                   | Tablet      | [5f78d7109f](https://linux-hardware.org/?probe=5f78d7109f) | Oct 24, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [81df2d786a](https://linux-hardware.org/?probe=81df2d786a) | Oct 15, 2022 |
| Dell          | Latitude E4310              | Notebook    | [318726cca9](https://linux-hardware.org/?probe=318726cca9) | Oct 14, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| eMachines     | eME528                      | Notebook    | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| Apple         | MacBookPro10,2              | Notebook    | [379590d053](https://linux-hardware.org/?probe=379590d053) | Oct 09, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [e31d2052e5](https://linux-hardware.org/?probe=e31d2052e5) | Oct 06, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [1bcfb0642f](https://linux-hardware.org/?probe=1bcfb0642f) | Oct 06, 2022 |
| HP            | 1497                        | Desktop     | [17a2f79f3f](https://linux-hardware.org/?probe=17a2f79f3f) | Oct 04, 2022 |
| HP            | 1497                        | Desktop     | [fab365512a](https://linux-hardware.org/?probe=fab365512a) | Oct 04, 2022 |
| HP            | 1497                        | Desktop     | [86ab60b437](https://linux-hardware.org/?probe=86ab60b437) | Sep 30, 2022 |
| Unknown       | 1.0                         | Notebook    | [f5b0e6a742](https://linux-hardware.org/?probe=f5b0e6a742) | Sep 24, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [08793f9065](https://linux-hardware.org/?probe=08793f9065) | Sep 24, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [eb488dae73](https://linux-hardware.org/?probe=eb488dae73) | Sep 17, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [eb406c0e81](https://linux-hardware.org/?probe=eb406c0e81) | Sep 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [805d4161a8](https://linux-hardware.org/?probe=805d4161a8) | Sep 15, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [6b6e4efdfc](https://linux-hardware.org/?probe=6b6e4efdfc) | Sep 13, 2022 |
| Lenovo        | SHARKBAY 0C48431 WIN        | Desktop     | [4598920e84](https://linux-hardware.org/?probe=4598920e84) | Sep 13, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [4083f9d2c9](https://linux-hardware.org/?probe=4083f9d2c9) | Sep 11, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [bd15d55792](https://linux-hardware.org/?probe=bd15d55792) | Sep 07, 2022 |
| HP            | 18E4                        | Desktop     | [2c113164fd](https://linux-hardware.org/?probe=2c113164fd) | Sep 05, 2022 |
| Dell          | Latitude 5490               | Notebook    | [a3f76e546f](https://linux-hardware.org/?probe=a3f76e546f) | Sep 01, 2022 |
| ASUSTek       | K72Jk                       | Notebook    | [d456f7083c](https://linux-hardware.org/?probe=d456f7083c) | Aug 26, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3cca56dc74](https://linux-hardware.org/?probe=3cca56dc74) | Aug 22, 2022 |
| HP            | Compaq 15                   | Notebook    | [c2bdac6148](https://linux-hardware.org/?probe=c2bdac6148) | Aug 21, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [c636c0401e](https://linux-hardware.org/?probe=c636c0401e) | Aug 18, 2022 |
| Dell          | Latitude E5500              | Notebook    | [5d04270674](https://linux-hardware.org/?probe=5d04270674) | Aug 08, 2022 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [90197434fc](https://linux-hardware.org/?probe=90197434fc) | Aug 08, 2022 |
| HP            | 198E                        | Desktop     | [4327be921d](https://linux-hardware.org/?probe=4327be921d) | Aug 06, 2022 |
| HP            | 198E                        | Desktop     | [284e29b3ea](https://linux-hardware.org/?probe=284e29b3ea) | Aug 06, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [d14f053671](https://linux-hardware.org/?probe=d14f053671) | Aug 01, 2022 |
| Lenovo        | S21e-20 80M4                | Notebook    | [bec71c2353](https://linux-hardware.org/?probe=bec71c2353) | Jul 27, 2022 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [02dd3c2357](https://linux-hardware.org/?probe=02dd3c2357) | Jul 21, 2022 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [acb31e0818](https://linux-hardware.org/?probe=acb31e0818) | Jul 18, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [789f614370](https://linux-hardware.org/?probe=789f614370) | Jul 14, 2022 |
| Dell          | Latitude D620               | Notebook    | [70be0d553e](https://linux-hardware.org/?probe=70be0d553e) | Jul 08, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [44b541373b](https://linux-hardware.org/?probe=44b541373b) | Jul 08, 2022 |
| Dell          | Latitude E6420              | Notebook    | [ede3298bf4](https://linux-hardware.org/?probe=ede3298bf4) | Jul 02, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [8c6f371222](https://linux-hardware.org/?probe=8c6f371222) | Jun 19, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [947ca74beb](https://linux-hardware.org/?probe=947ca74beb) | Jun 16, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [70ed4ebad8](https://linux-hardware.org/?probe=70ed4ebad8) | Jun 16, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [334e57a8b2](https://linux-hardware.org/?probe=334e57a8b2) | Jun 14, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [ed68bc8e1d](https://linux-hardware.org/?probe=ed68bc8e1d) | May 31, 2022 |
| Lenovo        | ThinkPad T430 2349BS7       | Notebook    | [2369e183ec](https://linux-hardware.org/?probe=2369e183ec) | May 30, 2022 |
| eMachines     | eM350                       | Notebook    | [2573854a09](https://linux-hardware.org/?probe=2573854a09) | May 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ae7670331c](https://linux-hardware.org/?probe=ae7670331c) | May 22, 2022 |
| Gigabyte      | AERO 15 KC                  | Notebook    | [5ebc19bd4c](https://linux-hardware.org/?probe=5ebc19bd4c) | May 18, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [39bb2b41e5](https://linux-hardware.org/?probe=39bb2b41e5) | May 18, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [427af3e3a0](https://linux-hardware.org/?probe=427af3e3a0) | May 09, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [7d4d1cb642](https://linux-hardware.org/?probe=7d4d1cb642) | May 06, 2022 |
| Dell          | Latitude E5440              | Notebook    | [556fccb6d3](https://linux-hardware.org/?probe=556fccb6d3) | May 06, 2022 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [2eff4001dc](https://linux-hardware.org/?probe=2eff4001dc) | May 06, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [889f1cba36](https://linux-hardware.org/?probe=889f1cba36) | Apr 30, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [f4403056c8](https://linux-hardware.org/?probe=f4403056c8) | Apr 30, 2022 |
| HP            | Pavilion g6                 | Notebook    | [b79730a7af](https://linux-hardware.org/?probe=b79730a7af) | Apr 27, 2022 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [0fad5f6cd2](https://linux-hardware.org/?probe=0fad5f6cd2) | Apr 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [45ad38e728](https://linux-hardware.org/?probe=45ad38e728) | Apr 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d809b304eb](https://linux-hardware.org/?probe=d809b304eb) | Apr 14, 2022 |
| HP            | Presario C500 (GF852EA#A... | Notebook    | [b14e9c5694](https://linux-hardware.org/?probe=b14e9c5694) | Apr 08, 2022 |
| TrekStor      | Surfbook W2                 | Notebook    | [52eb1e4ce9](https://linux-hardware.org/?probe=52eb1e4ce9) | Apr 06, 2022 |
| Medion        | S4401 MD61533               | Convertible | [0017875c99](https://linux-hardware.org/?probe=0017875c99) | Mar 30, 2022 |
| HP            | Notebook                    | Notebook    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ECS           | Nettle2                     | Desktop     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [24664b0486](https://linux-hardware.org/?probe=24664b0486) | Mar 25, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [1cb13706a4](https://linux-hardware.org/?probe=1cb13706a4) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | Notebook    | [5eac01f806](https://linux-hardware.org/?probe=5eac01f806) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | Notebook    | [ce0fa4ee36](https://linux-hardware.org/?probe=ce0fa4ee36) | Mar 25, 2022 |
| Dell          | Latitude E5440              | Notebook    | [6b871a160e](https://linux-hardware.org/?probe=6b871a160e) | Mar 22, 2022 |
| Dell          | Latitude E5440              | Notebook    | [bd5621d6e2](https://linux-hardware.org/?probe=bd5621d6e2) | Mar 21, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [39d48e6d79](https://linux-hardware.org/?probe=39d48e6d79) | Feb 28, 2022 |
| HP            | 18E4                        | Desktop     | [e7d597600e](https://linux-hardware.org/?probe=e7d597600e) | Feb 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [fc6097a447](https://linux-hardware.org/?probe=fc6097a447) | Feb 23, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [6888384b59](https://linux-hardware.org/?probe=6888384b59) | Feb 21, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [074c993361](https://linux-hardware.org/?probe=074c993361) | Feb 19, 2022 |
| Dell          | Latitude E6520              | Notebook    | [f921803f50](https://linux-hardware.org/?probe=f921803f50) | Feb 16, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [ae8afcd09f](https://linux-hardware.org/?probe=ae8afcd09f) | Feb 13, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [4769ae7351](https://linux-hardware.org/?probe=4769ae7351) | Feb 12, 2022 |
| Dell          | Precision M4800             | Notebook    | [8f91ff2d57](https://linux-hardware.org/?probe=8f91ff2d57) | Jan 29, 2022 |
| Dell          | Latitude E6520              | Notebook    | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [a24d99bf3b](https://linux-hardware.org/?probe=a24d99bf3b) | Jan 24, 2022 |
| Clevo         | W24/250CU                   | Notebook    | [64c6f06849](https://linux-hardware.org/?probe=64c6f06849) | Jan 22, 2022 |
| Google        | Banon                       | Notebook    | [3e792337e2](https://linux-hardware.org/?probe=3e792337e2) | Jan 21, 2022 |
| Google        | Banon                       | Notebook    | [c4cfb244b1](https://linux-hardware.org/?probe=c4cfb244b1) | Jan 21, 2022 |
| HP            | 3396                        | Desktop     | [e9486b13b8](https://linux-hardware.org/?probe=e9486b13b8) | Jan 20, 2022 |
| HP            | Pavilion g6                 | Notebook    | [099231b0b3](https://linux-hardware.org/?probe=099231b0b3) | Jan 19, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [8e4f80059d](https://linux-hardware.org/?probe=8e4f80059d) | Jan 14, 2022 |
| HP            | 1589                        | Desktop     | [402f1722ab](https://linux-hardware.org/?probe=402f1722ab) | Jan 09, 2022 |
| Lenovo        | ThinkPad P50 20EQS6J100     | Notebook    | [f366de3acf](https://linux-hardware.org/?probe=f366de3acf) | Jan 03, 2022 |
| Dell          | Precision 5560              | Notebook    | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| HP            | 8054                        | Desktop     | [13d18f87fe](https://linux-hardware.org/?probe=13d18f87fe) | Dec 30, 2021 |
| HP            | 8054                        | Desktop     | [fcf6deb221](https://linux-hardware.org/?probe=fcf6deb221) | Dec 30, 2021 |
| Timi          | TM1701                      | Notebook    | [ce3374e321](https://linux-hardware.org/?probe=ce3374e321) | Dec 23, 2021 |
| HP            | 1998                        | Desktop     | [f8e644ed15](https://linux-hardware.org/?probe=f8e644ed15) | Dec 23, 2021 |
| HP            | 090Ch                       | Desktop     | [bf92e3c728](https://linux-hardware.org/?probe=bf92e3c728) | Dec 22, 2021 |
| Acer          | Aspire One 522              | Notebook    | [7f495fc85b](https://linux-hardware.org/?probe=7f495fc85b) | Dec 21, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [331d419175](https://linux-hardware.org/?probe=331d419175) | Dec 06, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [97aec623b3](https://linux-hardware.org/?probe=97aec623b3) | Dec 04, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [8a415c9db8](https://linux-hardware.org/?probe=8a415c9db8) | Dec 04, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [3027f5288e](https://linux-hardware.org/?probe=3027f5288e) | Dec 04, 2021 |
| HP            | 1998                        | Desktop     | [ffa6c0b239](https://linux-hardware.org/?probe=ffa6c0b239) | Dec 01, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [518ee0b884](https://linux-hardware.org/?probe=518ee0b884) | Nov 30, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [405b87f8bf](https://linux-hardware.org/?probe=405b87f8bf) | Nov 29, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | Notebook    | [816aaebc79](https://linux-hardware.org/?probe=816aaebc79) | Nov 27, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | Notebook    | [162c76040f](https://linux-hardware.org/?probe=162c76040f) | Nov 27, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [7b9f86430d](https://linux-hardware.org/?probe=7b9f86430d) | Nov 25, 2021 |
| Lenovo        | ThinkPad X13 Gen 2i 20WK... | Notebook    | [c5aa70cf8a](https://linux-hardware.org/?probe=c5aa70cf8a) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [73b27d5257](https://linux-hardware.org/?probe=73b27d5257) | Nov 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [915ddf82b5](https://linux-hardware.org/?probe=915ddf82b5) | Nov 23, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [e3a38e431e](https://linux-hardware.org/?probe=e3a38e431e) | Nov 23, 2021 |
| HP            | ZBook 15                    | Notebook    | [6aca3076ac](https://linux-hardware.org/?probe=6aca3076ac) | Nov 22, 2021 |
| HP            | 15                          | Notebook    | [e82411639f](https://linux-hardware.org/?probe=e82411639f) | Nov 20, 2021 |
| Toshiba       | Satellite L50-A-1EL         | Notebook    | [40fff0be70](https://linux-hardware.org/?probe=40fff0be70) | Nov 19, 2021 |
| Dell          | 0MWYPT A01                  | Desktop     | [63385716b2](https://linux-hardware.org/?probe=63385716b2) | Nov 19, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f8670ddd99](https://linux-hardware.org/?probe=f8670ddd99) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b4fb9ffc24](https://linux-hardware.org/?probe=b4fb9ffc24) | Nov 18, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [acb0ed7655](https://linux-hardware.org/?probe=acb0ed7655) | Nov 16, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [b4ebd974c1](https://linux-hardware.org/?probe=b4ebd974c1) | Nov 15, 2021 |
| Apple         | MacBookPro13,3              | Notebook    | [e80b600640](https://linux-hardware.org/?probe=e80b600640) | Nov 12, 2021 |
| HP            | 1589                        | Desktop     | [789cbfc3fa](https://linux-hardware.org/?probe=789cbfc3fa) | Nov 10, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [966b61331a](https://linux-hardware.org/?probe=966b61331a) | Nov 05, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e1c9be9f1d](https://linux-hardware.org/?probe=e1c9be9f1d) | Nov 05, 2021 |
| Pegatron      | 2AD5                        | Desktop     | [70ae8e4cdf](https://linux-hardware.org/?probe=70ae8e4cdf) | Oct 30, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [c1f75f6249](https://linux-hardware.org/?probe=c1f75f6249) | Oct 27, 2021 |
| ASUSTek       | X540LA                      | Notebook    | [c947e5b1ea](https://linux-hardware.org/?probe=c947e5b1ea) | Oct 26, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2de5c74bc0](https://linux-hardware.org/?probe=2de5c74bc0) | Oct 23, 2021 |
| HP            | 18E7                        | Desktop     | [94c750ba4b](https://linux-hardware.org/?probe=94c750ba4b) | Oct 23, 2021 |
| HP            | 250 I3-5005U 15.6           | Notebook    | [94c7602d80](https://linux-hardware.org/?probe=94c7602d80) | Oct 20, 2021 |
| American M... | K7S41GX                     | Desktop     | [b5f8d33cc4](https://linux-hardware.org/?probe=b5f8d33cc4) | Oct 20, 2021 |
| American M... | K7S41GX                     | Desktop     | [920a47f107](https://linux-hardware.org/?probe=920a47f107) | Oct 20, 2021 |
| Sony          | VPCEH1L8E                   | Notebook    | [11ef4d4baf](https://linux-hardware.org/?probe=11ef4d4baf) | Oct 19, 2021 |
| HP            | 3032h                       | Desktop     | [6914386d3d](https://linux-hardware.org/?probe=6914386d3d) | Oct 19, 2021 |
| Sony          | SVE14122CAW                 | Notebook    | [7e20d79b1d](https://linux-hardware.org/?probe=7e20d79b1d) | Oct 16, 2021 |
| HP            | 1589                        | Desktop     | [bb8d8d60cf](https://linux-hardware.org/?probe=bb8d8d60cf) | Oct 10, 2021 |
| Dell          | 0J3C2F A00                  | Desktop     | [565fbea977](https://linux-hardware.org/?probe=565fbea977) | Oct 10, 2021 |
| Razer         | Blade Pro 17 (2019)         | Notebook    | [c0fc32d290](https://linux-hardware.org/?probe=c0fc32d290) | Oct 09, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [92bc4bf86c](https://linux-hardware.org/?probe=92bc4bf86c) | Oct 04, 2021 |
| Dell          | Latitude E5570              | Notebook    | [bfc3702626](https://linux-hardware.org/?probe=bfc3702626) | Oct 04, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [c5f4555ed5](https://linux-hardware.org/?probe=c5f4555ed5) | Sep 29, 2021 |
| Dell          | Latitude E5570              | Notebook    | [b4f22d5062](https://linux-hardware.org/?probe=b4f22d5062) | Sep 27, 2021 |
| Dell          | Latitude E5570              | Notebook    | [42c88d1bb8](https://linux-hardware.org/?probe=42c88d1bb8) | Sep 27, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [37a7444281](https://linux-hardware.org/?probe=37a7444281) | Sep 25, 2021 |
| HP            | EliteBook 8530w             | Notebook    | [326645a221](https://linux-hardware.org/?probe=326645a221) | Sep 25, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| HP            | 18E7                        | Desktop     | [e1aa6d3e49](https://linux-hardware.org/?probe=e1aa6d3e49) | Sep 19, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [554c02e687](https://linux-hardware.org/?probe=554c02e687) | Sep 14, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [e2202296c9](https://linux-hardware.org/?probe=e2202296c9) | Sep 13, 2021 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [99c878cd5e](https://linux-hardware.org/?probe=99c878cd5e) | Sep 04, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [d63a5c07e1](https://linux-hardware.org/?probe=d63a5c07e1) | Aug 28, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [78316d40ea](https://linux-hardware.org/?probe=78316d40ea) | Aug 28, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [cece1a32de](https://linux-hardware.org/?probe=cece1a32de) | Aug 21, 2021 |
| HP            | 0AACh                       | Desktop     | [588b35da24](https://linux-hardware.org/?probe=588b35da24) | Aug 21, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [49eb3e8236](https://linux-hardware.org/?probe=49eb3e8236) | Aug 18, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [3e73238fc6](https://linux-hardware.org/?probe=3e73238fc6) | Aug 13, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [2c09cdd5bd](https://linux-hardware.org/?probe=2c09cdd5bd) | Aug 12, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f0faf00d2f](https://linux-hardware.org/?probe=f0faf00d2f) | Aug 09, 2021 |
| Dell          | 0NX0PH A01                  | Desktop     | [8416267437](https://linux-hardware.org/?probe=8416267437) | Aug 09, 2021 |
| HP            | 15                          | Notebook    | [80ce139934](https://linux-hardware.org/?probe=80ce139934) | Aug 06, 2021 |
| HP            | 15                          | Notebook    | [24c674140c](https://linux-hardware.org/?probe=24c674140c) | Aug 05, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [ea05f5d624](https://linux-hardware.org/?probe=ea05f5d624) | Jul 21, 2021 |
| HP            | 339A                        | Desktop     | [7ea04a15cb](https://linux-hardware.org/?probe=7ea04a15cb) | Jul 18, 2021 |
| HP            | 339A                        | Desktop     | [31018180f8](https://linux-hardware.org/?probe=31018180f8) | Jul 16, 2021 |
| Unknown       | 1.0                         | Notebook    | [d049c76d58](https://linux-hardware.org/?probe=d049c76d58) | Jul 08, 2021 |
| Unknown       | 1.0                         | Notebook    | [deb4346da8](https://linux-hardware.org/?probe=deb4346da8) | Jul 08, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [77e63e8902](https://linux-hardware.org/?probe=77e63e8902) | Jul 06, 2021 |
| HP            | 3396                        | Desktop     | [28e2f6399c](https://linux-hardware.org/?probe=28e2f6399c) | Jul 05, 2021 |
| Unknown       | 1.0                         | Notebook    | [967654bdb6](https://linux-hardware.org/?probe=967654bdb6) | Jul 04, 2021 |
| Unknown       | 1.0                         | Notebook    | [36977bacbe](https://linux-hardware.org/?probe=36977bacbe) | Jul 03, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [19666df61f](https://linux-hardware.org/?probe=19666df61f) | Jun 26, 2021 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [df836c85c5](https://linux-hardware.org/?probe=df836c85c5) | Jun 26, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [dd3d9ede87](https://linux-hardware.org/?probe=dd3d9ede87) | Jun 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [80c0612f78](https://linux-hardware.org/?probe=80c0612f78) | Jun 04, 2021 |
| Unknown       | Unknown                     | Notebook    | [9bac89aecf](https://linux-hardware.org/?probe=9bac89aecf) | Jun 04, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [513f79e441](https://linux-hardware.org/?probe=513f79e441) | May 26, 2021 |
| HP            | 0AACh                       | Desktop     | [92920ff59a](https://linux-hardware.org/?probe=92920ff59a) | May 26, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [3890d7877d](https://linux-hardware.org/?probe=3890d7877d) | May 06, 2021 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [44810c2cc1](https://linux-hardware.org/?probe=44810c2cc1) | May 06, 2021 |
| MSI           | 2A9C                        | Desktop     | [db1be00449](https://linux-hardware.org/?probe=db1be00449) | May 02, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | Notebook    | [c0b9d7bd52](https://linux-hardware.org/?probe=c0b9d7bd52) | Apr 26, 2021 |
| Lenovo        | ThinkPad X220 4291V5K       | Notebook    | [4ec1325f12](https://linux-hardware.org/?probe=4ec1325f12) | Apr 26, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [cf8b627aa4](https://linux-hardware.org/?probe=cf8b627aa4) | Apr 11, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [bd04b1367f](https://linux-hardware.org/?probe=bd04b1367f) | Apr 11, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [522eb62b1a](https://linux-hardware.org/?probe=522eb62b1a) | Apr 03, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [e9df8836cf](https://linux-hardware.org/?probe=e9df8836cf) | Apr 03, 2021 |
| HP            | EliteBook 2540p             | Notebook    | [46c15e3b14](https://linux-hardware.org/?probe=46c15e3b14) | Apr 01, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [e1023ad432](https://linux-hardware.org/?probe=e1023ad432) | Mar 31, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [5c9803ca79](https://linux-hardware.org/?probe=5c9803ca79) | Mar 31, 2021 |
| Foxconn       | 2ACA                        | Desktop     | [04556ec49b](https://linux-hardware.org/?probe=04556ec49b) | Mar 26, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [f973f0f31c](https://linux-hardware.org/?probe=f973f0f31c) | Mar 23, 2021 |
| Dell          | Latitude 5580               | Notebook    | [9fd0e8f6b5](https://linux-hardware.org/?probe=9fd0e8f6b5) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291B66       | Notebook    | [411fb65be7](https://linux-hardware.org/?probe=411fb65be7) | Mar 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [7a6947637a](https://linux-hardware.org/?probe=7a6947637a) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [635fc4a0a2](https://linux-hardware.org/?probe=635fc4a0a2) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6bccb5f740](https://linux-hardware.org/?probe=6bccb5f740) | Mar 15, 2021 |
| Dell          | 0MWYPT A01                  | Desktop     | [1c76380527](https://linux-hardware.org/?probe=1c76380527) | Mar 06, 2021 |
| HP            | 1495                        | Desktop     | [ca9664aff0](https://linux-hardware.org/?probe=ca9664aff0) | Mar 05, 2021 |
| HP            | Notebook                    | Notebook    | [fbc522f5e7](https://linux-hardware.org/?probe=fbc522f5e7) | Feb 24, 2021 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [ab67b7aab9](https://linux-hardware.org/?probe=ab67b7aab9) | Feb 22, 2021 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [aeb3111a93](https://linux-hardware.org/?probe=aeb3111a93) | Feb 20, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [1ffab0446e](https://linux-hardware.org/?probe=1ffab0446e) | Feb 17, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [2ba0a379e8](https://linux-hardware.org/?probe=2ba0a379e8) | Feb 16, 2021 |
| Dell          | Latitude 3480               | Notebook    | [533356cb56](https://linux-hardware.org/?probe=533356cb56) | Feb 15, 2021 |
| HP            | Pavilion dv7                | Notebook    | [17dcac4931](https://linux-hardware.org/?probe=17dcac4931) | Feb 10, 2021 |
| GPD           | MicroPC                     | Notebook    | [ed2233e6ce](https://linux-hardware.org/?probe=ed2233e6ce) | Feb 08, 2021 |
| Dell          | 0M863N A01                  | Desktop     | [c10de13cf0](https://linux-hardware.org/?probe=c10de13cf0) | Feb 05, 2021 |
| Acer          | AO722                       | Notebook    | [24cb20b715](https://linux-hardware.org/?probe=24cb20b715) | Feb 04, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [8da09ed292](https://linux-hardware.org/?probe=8da09ed292) | Feb 04, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [7861f8622e](https://linux-hardware.org/?probe=7861f8622e) | Feb 01, 2021 |
| Lenovo        | ThinkPad E590 20NB002AMB    | Notebook    | [e45b210ee6](https://linux-hardware.org/?probe=e45b210ee6) | Feb 01, 2021 |
| Lenovo        | ThinkPad T460 20FN002SUS    | Notebook    | [6c9654a854](https://linux-hardware.org/?probe=6c9654a854) | Jan 25, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [512f5b5bdc](https://linux-hardware.org/?probe=512f5b5bdc) | Jan 18, 2021 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [3475dcd9b6](https://linux-hardware.org/?probe=3475dcd9b6) | Jan 17, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [8d7a3472b3](https://linux-hardware.org/?probe=8d7a3472b3) | Jan 16, 2021 |
| HP            | Pavilion dv7                | Notebook    | [bc33dda5d6](https://linux-hardware.org/?probe=bc33dda5d6) | Jan 09, 2021 |
| HP            | 650                         | Notebook    | [65c5445c17](https://linux-hardware.org/?probe=65c5445c17) | Jan 08, 2021 |
| Sony          | VGN-FW11L                   | Notebook    | [e99fe042af](https://linux-hardware.org/?probe=e99fe042af) | Jan 06, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [493c807f09](https://linux-hardware.org/?probe=493c807f09) | Jan 06, 2021 |
| Lenovo        | ThinkPad E570 20H50078IX    | Notebook    | [9162d07863](https://linux-hardware.org/?probe=9162d07863) | Dec 31, 2020 |
| Lenovo        | ThinkPad E570 20H50078IX    | Notebook    | [f1f07aecd0](https://linux-hardware.org/?probe=f1f07aecd0) | Dec 31, 2020 |
| HP            | 158A                        | Desktop     | [afd1e7439b](https://linux-hardware.org/?probe=afd1e7439b) | Dec 28, 2020 |
| Dell          | Latitude E6440              | Notebook    | [cec6c1fd51](https://linux-hardware.org/?probe=cec6c1fd51) | Dec 25, 2020 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [4a4ce9f5d2](https://linux-hardware.org/?probe=4a4ce9f5d2) | Dec 25, 2020 |
| HP            | 650                         | Notebook    | [ff87d07205](https://linux-hardware.org/?probe=ff87d07205) | Dec 21, 2020 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [9c31cf187f](https://linux-hardware.org/?probe=9c31cf187f) | Dec 17, 2020 |
| Timi          | TM1701                      | Notebook    | [bc63393a91](https://linux-hardware.org/?probe=bc63393a91) | Dec 13, 2020 |
| Lenovo        | ThinkPad T480s 20L8S3P30... | Notebook    | [1a37278a5b](https://linux-hardware.org/?probe=1a37278a5b) | Dec 13, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [d546d8c598](https://linux-hardware.org/?probe=d546d8c598) | Nov 25, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [9bb315e3ac](https://linux-hardware.org/?probe=9bb315e3ac) | Nov 25, 2020 |
| HP            | 304Ah                       | Desktop     | [d5f7af2482](https://linux-hardware.org/?probe=d5f7af2482) | Nov 23, 2020 |
| Dell          | Latitude E6440              | Notebook    | [6739c087eb](https://linux-hardware.org/?probe=6739c087eb) | Nov 20, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b72558f93c](https://linux-hardware.org/?probe=b72558f93c) | Nov 19, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [193c57b056](https://linux-hardware.org/?probe=193c57b056) | Nov 10, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [e6a667e32c](https://linux-hardware.org/?probe=e6a667e32c) | Nov 08, 2020 |
| TUXEDO        | N13xWU                      | Notebook    | [b4cd820410](https://linux-hardware.org/?probe=b4cd820410) | Nov 08, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | Notebook    | [bb66d36c3e](https://linux-hardware.org/?probe=bb66d36c3e) | Oct 23, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [d4755cc80a](https://linux-hardware.org/?probe=d4755cc80a) | Oct 18, 2020 |
| Dell          | 0MWYPT A01                  | Desktop     | [3134def56f](https://linux-hardware.org/?probe=3134def56f) | Oct 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ef4b4ee1be](https://linux-hardware.org/?probe=ef4b4ee1be) | Oct 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c1d3bd539a](https://linux-hardware.org/?probe=c1d3bd539a) | Oct 09, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [a12e9900c0](https://linux-hardware.org/?probe=a12e9900c0) | Oct 07, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [822c9a0ece](https://linux-hardware.org/?probe=822c9a0ece) | Oct 07, 2020 |
| HP            | Compaq nc6220 (PL814AV)     | Notebook    | [7f042faa64](https://linux-hardware.org/?probe=7f042faa64) | Oct 04, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [a5438c06dc](https://linux-hardware.org/?probe=a5438c06dc) | Oct 02, 2020 |
| HP            | ProBook 6470b               | Notebook    | [0c6e7c5d06](https://linux-hardware.org/?probe=0c6e7c5d06) | Sep 30, 2020 |
| HP            | ProBook 6470b               | Notebook    | [3ab44ecc2c](https://linux-hardware.org/?probe=3ab44ecc2c) | Sep 20, 2020 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [e36d2e46a2](https://linux-hardware.org/?probe=e36d2e46a2) | Sep 16, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | Notebook    | [09ba7a078c](https://linux-hardware.org/?probe=09ba7a078c) | Sep 06, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [1c9467e7ff](https://linux-hardware.org/?probe=1c9467e7ff) | Aug 31, 2020 |
| HP            | 3398                        | Desktop     | [6b7ea8d306](https://linux-hardware.org/?probe=6b7ea8d306) | Aug 27, 2020 |
| Dell          | Latitude E5270              | Notebook    | [b9e93e40f1](https://linux-hardware.org/?probe=b9e93e40f1) | Aug 26, 2020 |
| Toshiba       | Satellite C855-2CF          | Notebook    | [00048c3fd7](https://linux-hardware.org/?probe=00048c3fd7) | Aug 26, 2020 |
| HP            | ProBook 650 G1              | Notebook    | [134ae0f98f](https://linux-hardware.org/?probe=134ae0f98f) | Aug 24, 2020 |
| Lenovo        | ThinkPad X280 20KF001KFR    | Notebook    | [47a6af7e14](https://linux-hardware.org/?probe=47a6af7e14) | Aug 23, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [b51e82eb8b](https://linux-hardware.org/?probe=b51e82eb8b) | Aug 08, 2020 |
| HP            | ProBook 440 G7              | Notebook    | [b2d1e5272e](https://linux-hardware.org/?probe=b2d1e5272e) | Aug 07, 2020 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [8f0c5d78da](https://linux-hardware.org/?probe=8f0c5d78da) | Jul 29, 2020 |
| HP            | 3397                        | Desktop     | [de9945e027](https://linux-hardware.org/?probe=de9945e027) | Jun 30, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [c4b91061bd](https://linux-hardware.org/?probe=c4b91061bd) | Jun 24, 2020 |
| Mediacom      | WinPad 11,6 FullHD- WPU1... | Notebook    | [1d9441c4cb](https://linux-hardware.org/?probe=1d9441c4cb) | Jun 24, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [8f31cacb03](https://linux-hardware.org/?probe=8f31cacb03) | Jun 15, 2020 |
| Dell          | Latitude E6410              | Notebook    | [63006c892d](https://linux-hardware.org/?probe=63006c892d) | Jun 12, 2020 |
| Dell          | Latitude E6540              | Notebook    | [0820a41e4a](https://linux-hardware.org/?probe=0820a41e4a) | Jun 03, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [d4a0f7593f](https://linux-hardware.org/?probe=d4a0f7593f) | May 30, 2020 |
| Packard Be... | EasyNote TK85               | Notebook    | [1ef7f1dccf](https://linux-hardware.org/?probe=1ef7f1dccf) | May 24, 2020 |
| HP            | Unknown                     | Notebook    | [83216ab6f8](https://linux-hardware.org/?probe=83216ab6f8) | May 23, 2020 |
| Dell          | Latitude E5270              | Notebook    | [79c2208ee5](https://linux-hardware.org/?probe=79c2208ee5) | May 16, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [4d933966bb](https://linux-hardware.org/?probe=4d933966bb) | May 16, 2020 |
| HP            | ZBook 15                    | Notebook    | [7fdf5ffeb8](https://linux-hardware.org/?probe=7fdf5ffeb8) | May 10, 2020 |
| HP            | 0A04h                       | Desktop     | [c0b180275b](https://linux-hardware.org/?probe=c0b180275b) | May 05, 2020 |
| HP            | 0A04h                       | Desktop     | [bb34c7e807](https://linux-hardware.org/?probe=bb34c7e807) | May 05, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [fea9f24d5a](https://linux-hardware.org/?probe=fea9f24d5a) | Apr 27, 2020 |
| Lenovo        | G50-70 20351                | Notebook    | [f6609c3613](https://linux-hardware.org/?probe=f6609c3613) | Apr 27, 2020 |
| ASUSTek       | UX31A                       | Notebook    | [2ce7c49619](https://linux-hardware.org/?probe=2ce7c49619) | Apr 16, 2020 |
| ASUSTek       | X542UAR                     | Notebook    | [1597291755](https://linux-hardware.org/?probe=1597291755) | Apr 03, 2020 |
| HP            | 3397                        | Desktop     | [37ddb2349c](https://linux-hardware.org/?probe=37ddb2349c) | Mar 20, 2020 |
| HP            | 250 G3                      | Notebook    | [e92714c5e6](https://linux-hardware.org/?probe=e92714c5e6) | Mar 18, 2020 |
| Dell          | Latitude E6510              | Notebook    | [bc7b29779f](https://linux-hardware.org/?probe=bc7b29779f) | Mar 08, 2020 |
| Packard Be... | EasyNote TK85               | Notebook    | [bf3776568a](https://linux-hardware.org/?probe=bf3776568a) | Feb 23, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [2bc65b9511](https://linux-hardware.org/?probe=2bc65b9511) | Feb 22, 2020 |
| HP            | EliteBook 8440p             | Notebook    | [4ef298fd63](https://linux-hardware.org/?probe=4ef298fd63) | Feb 22, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [98c2d41201](https://linux-hardware.org/?probe=98c2d41201) | Feb 21, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [6b512c0e61](https://linux-hardware.org/?probe=6b512c0e61) | Feb 21, 2020 |
| Dell          | Latitude E5520              | Notebook    | [2994cbb1d2](https://linux-hardware.org/?probe=2994cbb1d2) | Feb 21, 2020 |
| Unknown       | Unknown                     | Phone       | [4ff689998e](https://linux-hardware.org/?probe=4ff689998e) | Feb 11, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [35973fcba8](https://linux-hardware.org/?probe=35973fcba8) | Jan 01, 2020 |
| Medion        | P7615                       | Notebook    | [1402e4bf25](https://linux-hardware.org/?probe=1402e4bf25) | Dec 29, 2019 |
| Toshiba       | Satellite Pro C650          | Notebook    | [984a530b85](https://linux-hardware.org/?probe=984a530b85) | Dec 19, 2019 |
| Medion        | P7615                       | Notebook    | [56fdcbb995](https://linux-hardware.org/?probe=56fdcbb995) | Nov 25, 2019 |
| Medion        | P7615                       | Notebook    | [150034113d](https://linux-hardware.org/?probe=150034113d) | Nov 25, 2019 |
| Acer          | Aspire 7736                 | Notebook    | [64727a44db](https://linux-hardware.org/?probe=64727a44db) | Nov 24, 2019 |
| Acer          | Aspire 7736                 | Notebook    | [3415167cef](https://linux-hardware.org/?probe=3415167cef) | Nov 23, 2019 |
| HP            | 1494                        | Desktop     | [af749848e8](https://linux-hardware.org/?probe=af749848e8) | Nov 23, 2019 |
| Acer          | Aspire ES1-523              | Notebook    | [74c8472d6f](https://linux-hardware.org/?probe=74c8472d6f) | Nov 12, 2019 |
| ASUSTek       | X200MA                      | Notebook    | [860c71f889](https://linux-hardware.org/?probe=860c71f889) | Nov 10, 2019 |
| Acer          | Calpella                    | Notebook    | [6ff918b898](https://linux-hardware.org/?probe=6ff918b898) | Oct 29, 2019 |
| Dell          | Latitude 3590               | Notebook    | [8e1927b00a](https://linux-hardware.org/?probe=8e1927b00a) | Sep 22, 2019 |
| Lenovo        | ThinkPad T440 20B7S2MF01    | Notebook    | [4dc662ddb5](https://linux-hardware.org/?probe=4dc662ddb5) | Sep 04, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [73e92501d3](https://linux-hardware.org/?probe=73e92501d3) | Aug 29, 2019 |
| Dell          | 0D28YY A03                  | Desktop     | [0be7a39100](https://linux-hardware.org/?probe=0be7a39100) | Jul 14, 2019 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [d9903b4749](https://linux-hardware.org/?probe=d9903b4749) | May 14, 2019 |
| Toshiba       | Satellite L50-A-1DG         | Notebook    | [b0e44b3093](https://linux-hardware.org/?probe=b0e44b3093) | Apr 13, 2019 |
| Toshiba       | Satellite L50-A-1DG         | Notebook    | [1103235a87](https://linux-hardware.org/?probe=1103235a87) | Apr 13, 2019 |
| Acer          | Aspire E5-575               | Notebook    | [e7e29b676f](https://linux-hardware.org/?probe=e7e29b676f) | Mar 16, 2019 |
| Acer          | Aspire E5-575               | Notebook    | [4d2d0aa109](https://linux-hardware.org/?probe=4d2d0aa109) | Feb 20, 2019 |
| ASUSTek       | F5VL                        | Notebook    | [8c665a5eb1](https://linux-hardware.org/?probe=8c665a5eb1) | Feb 07, 2019 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [730a048dd9](https://linux-hardware.org/?probe=730a048dd9) | Dec 20, 2018 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [36a6a5ce8c](https://linux-hardware.org/?probe=36a6a5ce8c) | Dec 20, 2018 |
| ASUSTek       | F5VL                        | Notebook    | [d54a4a5d26](https://linux-hardware.org/?probe=d54a4a5d26) | Dec 12, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | Notebook    | [8e1e3b46c5](https://linux-hardware.org/?probe=8e1e3b46c5) | Nov 26, 2018 |
| Lenovo        | ThinkPad X240 20AMA09VFR    | Notebook    | [b14f27a474](https://linux-hardware.org/?probe=b14f27a474) | Nov 26, 2018 |
| Dell          | 0DR845                      | Desktop     | [3e45e16507](https://linux-hardware.org/?probe=3e45e16507) | Sep 23, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 43        | 16.1%   |
| Ubuntu 22.04       | 18        | 6.74%   |
| Ubuntu 18.04       | 17        | 6.37%   |
| Debian 11          | 13        | 4.87%   |
| OpenMandriva 4.2   | 12        | 4.49%   |
| KDE neon 20.04     | 11        | 4.12%   |
| OpenMandriva 4.3   | 9         | 3.37%   |
| Linux Mint 20.2    | 7         | 2.62%   |
| OpenMandriva 23.01 | 6         | 2.25%   |
| Zorin 16           | 5         | 1.87%   |
| Ubuntu Unity 16.04 | 5         | 1.87%   |
| Ubuntu 20.10       | 5         | 1.87%   |
| OpenMandriva 4.50  | 5         | 1.87%   |
| Linux Mint 20.3    | 5         | 1.87%   |
| Fedora 33          | 5         | 1.87%   |
| Ubuntu 19.10       | 4         | 1.5%    |
| Pop!_OS 22.04      | 4         | 1.5%    |
| Linux Mint 21      | 4         | 1.5%    |
| ArcoLinux Rolling  | 4         | 1.5%    |
| Arch               | 4         | 1.5%    |
| Manjaro            | 3         | 1.12%   |
| Linux Mint 19.3    | 3         | 1.12%   |
| Zorin 15           | 2         | 0.75%   |
| Xubuntu 20.04      | 2         | 0.75%   |
| Void Linux         | 2         | 0.75%   |
| Ubuntu 21.10       | 2         | 0.75%   |
| Ubuntu 21.04       | 2         | 0.75%   |
| Ubuntu 16.04       | 2         | 0.75%   |
| Pop!_OS 21.10      | 2         | 0.75%   |
| Pop!_OS 20.10      | 2         | 0.75%   |
| Parrot 5.0         | 2         | 0.75%   |
| Linux Mint 21.1    | 2         | 0.75%   |
| Kali 2019.4        | 2         | 0.75%   |
| Fedora 37          | 2         | 0.75%   |
| Fedora 36          | 2         | 0.75%   |
| Debian 10          | 2         | 0.75%   |
| Xubuntu 18.04      | 1         | 0.37%   |
| Xero Rolling       | 1         | 0.37%   |
| Ubuntu Unity 20.04 | 1         | 0.37%   |
| Ubuntu MATE 22.10  | 1         | 0.37%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 89        | 34.9%   |
| OpenMandriva | 31        | 12.16%  |
| Linux Mint   | 22        | 8.63%   |
| Debian       | 15        | 5.88%   |
| KDE neon     | 12        | 4.71%   |
| Fedora       | 12        | 4.71%   |
| Pop!_OS      | 9         | 3.53%   |
| Zorin        | 7         | 2.75%   |
| Manjaro      | 7         | 2.75%   |
| Kali         | 7         | 2.75%   |
| Ubuntu Unity | 6         | 2.35%   |
| Arch         | 5         | 1.96%   |
| ArcoLinux    | 4         | 1.57%   |
| Xubuntu      | 3         | 1.18%   |
| Endless      | 3         | 1.18%   |
| Void Linux   | 2         | 0.78%   |
| Ubuntu MATE  | 2         | 0.78%   |
| Raspbian     | 2         | 0.78%   |
| Parrot       | 2         | 0.78%   |
| Elementary   | 2         | 0.78%   |
| Xero         | 1         | 0.39%   |
| ROSA         | 1         | 0.39%   |
| RHEL         | 1         | 0.39%   |
| Pear OS      | 1         | 0.39%   |
| openSUSE     | 1         | 0.39%   |
| Nobara       | 1         | 0.39%   |
| Lubuntu      | 1         | 0.39%   |
| Kubuntu      | 1         | 0.39%   |
| EndeavourOS  | 1         | 0.39%   |
| CentOS       | 1         | 0.39%   |
| BunsenLabs   | 1         | 0.39%   |
| BlackPanther | 1         | 0.39%   |
| Android      | 1         | 0.39%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 12        | 4.23%   |
| 5.16.7-desktop-1omv4003  | 10        | 3.52%   |
| 6.1.1-desktop-1omv2290   | 6         | 2.11%   |
| 5.4.0-58-generic         | 5         | 1.76%   |
| 5.4.0-48-generic         | 5         | 1.76%   |
| 5.13.0-40-generic        | 5         | 1.76%   |
| 5.8.0-43-generic         | 4         | 1.41%   |
| 5.4.0-42-generic         | 4         | 1.41%   |
| 5.12.4-desktop-1omv4050  | 4         | 1.41%   |
| 5.11.0-37-generic        | 4         | 1.41%   |
| 5.8.0-38-generic         | 3         | 1.06%   |
| 5.3.0-40-generic         | 3         | 1.06%   |
| 5.17.5-76051705-generic  | 3         | 1.06%   |
| 5.15.0-58-generic        | 3         | 1.06%   |
| 5.15.0-52-generic        | 3         | 1.06%   |
| 5.15.0-46-generic        | 3         | 1.06%   |
| 5.15.0-41-generic        | 3         | 1.06%   |
| 5.13.0-27-generic        | 3         | 1.06%   |
| 5.8.0-48-generic         | 2         | 0.7%    |
| 5.8.0-33-generic         | 2         | 0.7%    |
| 5.4.0-96-generic         | 2         | 0.7%    |
| 5.4.0-90-generic         | 2         | 0.7%    |
| 5.4.0-88-generic         | 2         | 0.7%    |
| 5.4.0-74-generic         | 2         | 0.7%    |
| 5.4.0-65-generic         | 2         | 0.7%    |
| 5.4.0-59-generic         | 2         | 0.7%    |
| 5.4.0-37-generic         | 2         | 0.7%    |
| 5.4.0-33-generic         | 2         | 0.7%    |
| 5.4.0-29-generic         | 2         | 0.7%    |
| 5.3.0-kali2-686-pae      | 2         | 0.7%    |
| 5.3.0-51-generic         | 2         | 0.7%    |
| 5.3.0-28-generic         | 2         | 0.7%    |
| 5.19.0-38-generic        | 2         | 0.7%    |
| 5.18.19_1                | 2         | 0.7%    |
| 5.15.0-57-generic        | 2         | 0.7%    |
| 5.15.0-53-generic        | 2         | 0.7%    |
| 5.15.0-50-generic        | 2         | 0.7%    |
| 5.15.0-48-generic        | 2         | 0.7%    |
| 5.14.14-arch1-1          | 2         | 0.7%    |
| 5.13.0-19-generic        | 2         | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 41        | 15.3%   |
| 5.15.0  | 30        | 11.19%  |
| 5.8.0   | 18        | 6.72%   |
| 4.15.0  | 17        | 6.34%   |
| 5.11.0  | 16        | 5.97%   |
| 5.10.0  | 14        | 5.22%   |
| 5.3.0   | 12        | 4.48%   |
| 5.13.0  | 12        | 4.48%   |
| 5.10.14 | 12        | 4.48%   |
| 5.16.7  | 10        | 3.73%   |
| 6.1.1   | 6         | 2.24%   |
| 5.0.0   | 6         | 2.24%   |
| 5.19.0  | 5         | 1.87%   |
| 5.12.4  | 4         | 1.49%   |
| 4.18.0  | 4         | 1.49%   |
| 5.17.5  | 3         | 1.12%   |
| 5.14.0  | 3         | 1.12%   |
| 4.19.0  | 3         | 1.12%   |
| 5.18.19 | 2         | 0.75%   |
| 5.16.0  | 2         | 0.75%   |
| 5.14.14 | 2         | 0.75%   |
| 6.1.7   | 1         | 0.37%   |
| 6.1.6   | 1         | 0.37%   |
| 6.1.0   | 1         | 0.37%   |
| 6.0.14  | 1         | 0.37%   |
| 6.0.12  | 1         | 0.37%   |
| 6.0.0   | 1         | 0.37%   |
| 5.8.18  | 1         | 0.37%   |
| 5.8.15  | 1         | 0.37%   |
| 5.8.1   | 1         | 0.37%   |
| 5.7.15  | 1         | 0.37%   |
| 5.6.14  | 1         | 0.37%   |
| 5.19.9  | 1         | 0.37%   |
| 5.19.5  | 1         | 0.37%   |
| 5.19.16 | 1         | 0.37%   |
| 5.19.14 | 1         | 0.37%   |
| 5.18.18 | 1         | 0.37%   |
| 5.18.12 | 1         | 0.37%   |
| 5.18.1  | 1         | 0.37%   |
| 5.17.9  | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 41        | 15.36%  |
| 5.15    | 37        | 13.86%  |
| 5.10    | 32        | 11.99%  |
| 5.8     | 21        | 7.87%   |
| 5.11    | 19        | 7.12%   |
| 4.15    | 17        | 6.37%   |
| 5.13    | 14        | 5.24%   |
| 5.16    | 13        | 4.87%   |
| 5.3     | 12        | 4.49%   |
| 6.1     | 9         | 3.37%   |
| 5.19    | 9         | 3.37%   |
| 5.17    | 6         | 2.25%   |
| 5.14    | 6         | 2.25%   |
| 5.0     | 6         | 2.25%   |
| 5.18    | 5         | 1.87%   |
| 5.12    | 4         | 1.5%    |
| 4.18    | 4         | 1.5%    |
| 6.0     | 3         | 1.12%   |
| 4.19    | 3         | 1.12%   |
| 5.7     | 1         | 0.37%   |
| 5.6     | 1         | 0.37%   |
| 4.9     | 1         | 0.37%   |
| 4.4     | 1         | 0.37%   |
| 4.13    | 1         | 0.37%   |
| 3.18    | 1         | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 237       | 94.8%   |
| i686   | 10        | 4%      |
| armv8l | 1         | 0.4%    |
| armv7l | 1         | 0.4%    |
| armv6l | 1         | 0.4%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 127       | 49.22%  |
| KDE5            | 51        | 19.77%  |
| Unknown         | 18        | 6.98%   |
| X-Cinnamon      | 16        | 6.2%    |
| XFCE            | 13        | 5.04%   |
| KDE             | 8         | 3.1%    |
| Unity           | 6         | 2.33%   |
| MATE            | 5         | 1.94%   |
| LXDE            | 3         | 1.16%   |
| Cinnamon        | 3         | 1.16%   |
| Pantheon        | 2         | 0.78%   |
| xmonad          | 1         | 0.39%   |
| qtile           | 1         | 0.39%   |
| KDE4            | 1         | 0.39%   |
| i3              | 1         | 0.39%   |
| GNOME Flashback | 1         | 0.39%   |
| Budgie          | 1         | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 203       | 79.3%   |
| Wayland | 40        | 15.63%  |
| Unknown | 9         | 3.52%   |
| Tty     | 4         | 1.56%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 114       | 43.68%  |
| SDDM    | 49        | 18.77%  |
| GDM     | 37        | 14.18%  |
| LightDM | 29        | 11.11%  |
| GDM3    | 27        | 10.34%  |
| TDM     | 4         | 1.53%   |
| KDM     | 1         | 0.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 136       | 53.75%  |
| fr_FR   | 72        | 28.46%  |
| Unknown | 18        | 7.11%   |
| en_GB   | 12        | 4.74%   |
| de_DE   | 3         | 1.19%   |
| C       | 3         | 1.19%   |
| en_AG   | 2         | 0.79%   |
| ar_MA   | 2         | 0.79%   |
| fr_MA   | 1         | 0.4%    |
| fr_CH   | 1         | 0.4%    |
| fr_BE   | 1         | 0.4%    |
| es_ES   | 1         | 0.4%    |
| ar_EG   | 1         | 0.4%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 147       | 58.57%  |
| EFI  | 104       | 41.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 196       | 78.4%   |
| Overlay | 33        | 13.2%   |
| Btrfs   | 14        | 5.6%    |
| Unknown | 5         | 2%      |
| Xfs     | 2         | 0.8%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 121       | 48.02%  |
| GPT     | 85        | 33.73%  |
| MBR     | 46        | 18.25%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 212       | 84.46%  |
| Yes       | 39        | 15.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 149       | 59.36%  |
| Yes       | 102       | 40.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 88        | 35.34%  |
| Dell                    | 44        | 17.67%  |
| Lenovo                  | 36        | 14.46%  |
| ASUSTek Computer        | 21        | 8.43%   |
| Toshiba                 | 8         | 3.21%   |
| Acer                    | 7         | 2.81%   |
| Apple                   | 4         | 1.61%   |
| Sony                    | 3         | 1.2%    |
| Packard Bell            | 3         | 1.2%    |
| Foxconn                 | 3         | 1.2%    |
| Unknown                 | 3         | 1.2%    |
| Timi                    | 2         | 0.8%    |
| Samsung Electronics     | 2         | 0.8%    |
| Raspberry Pi Foundation | 2         | 0.8%    |
| Medion                  | 2         | 0.8%    |
| Gigabyte Technology     | 2         | 0.8%    |
| eMachines               | 2         | 0.8%    |
| TUXEDO                  | 1         | 0.4%    |
| TrekStor                | 1         | 0.4%    |
| SINTRONES               | 1         | 0.4%    |
| Razer                   | 1         | 0.4%    |
| Pegatron                | 1         | 0.4%    |
| MSI                     | 1         | 0.4%    |
| Mediacom                | 1         | 0.4%    |
| Linx                    | 1         | 0.4%    |
| HUAWEI                  | 1         | 0.4%    |
| GPD                     | 1         | 0.4%    |
| Google                  | 1         | 0.4%    |
| Fujitsu Siemens         | 1         | 0.4%    |
| ECS                     | 1         | 0.4%    |
| Clevo                   | 1         | 0.4%    |
| Casper                  | 1         | 0.4%    |
| ASRock                  | 1         | 0.4%    |
| American Megatrends     | 1         | 0.4%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| HP EliteBook 8440p                     | 4         | 1.61%   |
| Unknown                                | 4         | 1.61%   |
| HP ProDesk 600 G1 TWR                  | 3         | 1.2%    |
| HP Laptop 15-dw3xxx                    | 3         | 1.2%    |
| HP EliteBook 840 G2                    | 3         | 1.2%    |
| Timi TM1701                            | 2         | 0.8%    |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 2         | 0.8%    |
| Lenovo IdeaPad L3 15IML05 81Y3         | 2         | 0.8%    |
| HP ZBook 15                            | 2         | 0.8%    |
| HP ProBook 650 G1                      | 2         | 0.8%    |
| HP ProBook 6470b                       | 2         | 0.8%    |
| HP Pavilion g6                         | 2         | 0.8%    |
| HP Notebook                            | 2         | 0.8%    |
| HP EliteDesk 800 G1 TWR                | 2         | 0.8%    |
| HP EliteDesk 800 G1 SFF                | 2         | 0.8%    |
| HP EliteBook 8460p                     | 2         | 0.8%    |
| HP Compaq Elite 8300 SFF               | 2         | 0.8%    |
| HP Compaq Elite 8300 CMT               | 2         | 0.8%    |
| HP Compaq dc7800 Convertible Minitower | 2         | 0.8%    |
| HP 250 G5 Notebook PC                  | 2         | 0.8%    |
| Dell OptiPlex 790                      | 2         | 0.8%    |
| Dell Latitude E6520                    | 2         | 0.8%    |
| Dell Latitude E6410                    | 2         | 0.8%    |
| ASUS X540LA                            | 2         | 0.8%    |
| Acer Aspire ES1-523                    | 2         | 0.8%    |
| TUXEDO N13xWU                          | 1         | 0.4%    |
| TrekStor Surfbook W2                   | 1         | 0.4%    |
| Toshiba Satellite Pro C650             | 1         | 0.4%    |
| Toshiba Satellite L750                 | 1         | 0.4%    |
| Toshiba Satellite L50-B                | 1         | 0.4%    |
| Toshiba Satellite L50-A-1EL            | 1         | 0.4%    |
| Toshiba Satellite L50-A-1DG            | 1         | 0.4%    |
| Toshiba Satellite C855-2CF             | 1         | 0.4%    |
| Toshiba Satellite C855-1LG             | 1         | 0.4%    |
| Toshiba Satellite C660                 | 1         | 0.4%    |
| Sony VPCEH1L8E                         | 1         | 0.4%    |
| Sony VGN-FW11L                         | 1         | 0.4%    |
| Sony SVE14122CAW                       | 1         | 0.4%    |
| SINTRONES AMB-5000G1                   | 1         | 0.4%    |
| Samsung 355V4C/356V4C/3445VC/3545VC    | 1         | 0.4%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell Latitude          | 27        | 10.84%  |
| Lenovo ThinkPad        | 19        | 7.63%   |
| HP EliteBook           | 18        | 7.23%   |
| HP Compaq              | 15        | 6.02%   |
| HP Pavilion            | 9         | 3.61%   |
| Toshiba Satellite      | 8         | 3.21%   |
| HP ProBook             | 8         | 3.21%   |
| HP Laptop              | 8         | 3.21%   |
| Dell OptiPlex          | 6         | 2.41%   |
| HP EliteDesk           | 5         | 2.01%   |
| Acer Aspire            | 5         | 2.01%   |
| Lenovo IdeaPad         | 4         | 1.61%   |
| HP ProDesk             | 4         | 1.61%   |
| HP 250                 | 4         | 1.61%   |
| Dell Precision         | 4         | 1.61%   |
| ASUS ROG               | 4         | 1.61%   |
| Unknown                | 4         | 1.61%   |
| Packard Bell EasyNote  | 3         | 1.2%    |
| Lenovo ThinkCentre     | 3         | 1.2%    |
| Lenovo ThinkBook       | 3         | 1.2%    |
| HP ZBook               | 3         | 1.2%    |
| Dell Vostro            | 3         | 1.2%    |
| Timi TM1701            | 2         | 0.8%    |
| RPi Raspberry          | 2         | 0.8%    |
| HP Notebook            | 2         | 0.8%    |
| Dell XPS               | 2         | 0.8%    |
| Dell Inspiron          | 2         | 0.8%    |
| ASUS X540LA            | 2         | 0.8%    |
| TUXEDO N13xWU          | 1         | 0.4%    |
| TrekStor Surfbook      | 1         | 0.4%    |
| Sony VPCEH1L8E         | 1         | 0.4%    |
| Sony VGN-FW11L         | 1         | 0.4%    |
| Sony SVE14122CAW       | 1         | 0.4%    |
| SINTRONES AMB-5000G1   | 1         | 0.4%    |
| Samsung 355V4C         | 1         | 0.4%    |
| Samsung 300E4A         | 1         | 0.4%    |
| Razer Blade            | 1         | 0.4%    |
| Pegatron h8-1507ef     | 1         | 0.4%    |
| MSI PPPPP-CCC#MMMMMMMM | 1         | 0.4%    |
| Medion S4401           | 1         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 31        | 12.45%  |
| 2011    | 26        | 10.44%  |
| 2018    | 21        | 8.43%   |
| 2012    | 20        | 8.03%   |
| 2010    | 20        | 8.03%   |
| 2016    | 17        | 6.83%   |
| 2015    | 17        | 6.83%   |
| 2014    | 16        | 6.43%   |
| 2020    | 14        | 5.62%   |
| 2017    | 14        | 5.62%   |
| 2019    | 13        | 5.22%   |
| 2021    | 11        | 4.42%   |
| 2007    | 9         | 3.61%   |
| 2009    | 7         | 2.81%   |
| 2008    | 5         | 2.01%   |
| 2006    | 2         | 0.8%    |
| 2004    | 2         | 0.8%    |
| Unknown | 2         | 0.8%    |
| 2022    | 1         | 0.4%    |
| 2005    | 1         | 0.4%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 182       | 73.09%  |
| Desktop        | 57        | 22.89%  |
| Convertible    | 5         | 2.01%   |
| System on chip | 2         | 0.8%    |
| Phone          | 1         | 0.4%    |
| Tablet         | 1         | 0.4%    |
| All in one     | 1         | 0.4%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 237       | 93.31%  |
| Enabled  | 17        | 6.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 248       | 99.6%   |
| Yes  | 1         | 0.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 82        | 32.8%   |
| 3.01-4.0    | 65        | 26%     |
| 16.01-24.0  | 31        | 12.4%   |
| 8.01-16.0   | 30        | 12%     |
| 1.01-2.0    | 18        | 7.2%    |
| 2.01-3.0    | 6         | 2.4%    |
| 32.01-64.0  | 5         | 2%      |
| 24.01-32.0  | 5         | 2%      |
| 64.01-256.0 | 5         | 2%      |
| 0.51-1.0    | 2         | 0.8%    |
| 0.01-0.5    | 1         | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 110       | 41.04%  |
| 2.01-3.0  | 80        | 29.85%  |
| 3.01-4.0  | 31        | 11.57%  |
| 4.01-8.0  | 30        | 11.19%  |
| 0.51-1.0  | 14        | 5.22%   |
| 0.01-0.5  | 2         | 0.75%   |
| 8.01-16.0 | 1         | 0.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 197       | 78.17%  |
| 2      | 41        | 16.27%  |
| 3      | 12        | 4.76%   |
| 4      | 2         | 0.79%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 126       | 50.6%   |
| Yes       | 123       | 49.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 225       | 90.36%  |
| No        | 24        | 9.64%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 223       | 89.2%   |
| No        | 27        | 10.8%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 60.16%  |
| No        | 100       | 39.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Morocco | 249       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Casablanca       | 67        | 25.38%  |
| Marrakesh        | 26        | 9.85%   |
| Rabat            | 23        | 8.71%   |
| Agadir           | 22        | 8.33%   |
| Fes              | 19        | 7.2%    |
| Salé            | 12        | 4.55%   |
| Kenitra          | 12        | 4.55%   |
| Tangier          | 10        | 3.79%   |
| Meknes           | 9         | 3.41%   |
| Oujda            | 8         | 3.03%   |
| Khouribga        | 7         | 2.65%   |
| Nador            | 5         | 1.89%   |
| Tiznit           | 4         | 1.52%   |
| Temara           | 3         | 1.14%   |
| Taza             | 3         | 1.14%   |
| El Jadida        | 3         | 1.14%   |
| Beni Mellal      | 3         | 1.14%   |
| Youssoufia       | 2         | 0.76%   |
| Tétouan         | 2         | 0.76%   |
| Skhirate         | 2         | 0.76%   |
| Safi             | 2         | 0.76%   |
| Mohammedia       | 2         | 0.76%   |
| Guelmim          | 2         | 0.76%   |
| Targuist         | 1         | 0.38%   |
| Taourirt         | 1         | 0.38%   |
| Taounate         | 1         | 0.38%   |
| Sidi Lmokhtar    | 1         | 0.38%   |
| Sidi Kacem       | 1         | 0.38%   |
| Ouirgane         | 1         | 0.38%   |
| Midelt           | 1         | 0.38%   |
| Ksar El Kebir    | 1         | 0.38%   |
| Khemisset        | 1         | 0.38%   |
| Karia Ba Mohamed | 1         | 0.38%   |
| Douar Kalaa      | 1         | 0.38%   |
| Berrechid        | 1         | 0.38%   |
| Berkane          | 1         | 0.38%   |
| Al Aaroui        | 1         | 0.38%   |
| Agdz             | 1         | 0.38%   |
| Agdal            | 1         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 53        | 69     | 17.79%  |
| WDC                   | 41        | 49     | 13.76%  |
| Samsung Electronics   | 40        | 53     | 13.42%  |
| Toshiba               | 37        | 52     | 12.42%  |
| Hitachi               | 16        | 20     | 5.37%   |
| Unknown               | 15        | 20     | 5.03%   |
| HGST                  | 11        | 11     | 3.69%   |
| Intel                 | 9         | 10     | 3.02%   |
| SanDisk               | 8         | 8      | 2.68%   |
| Kingston              | 6         | 7      | 2.01%   |
| Apple                 | 6         | 6      | 2.01%   |
| SK hynix              | 5         | 5      | 1.68%   |
| Micron Technology     | 4         | 5      | 1.34%   |
| KIOXIA                | 4         | 4      | 1.34%   |
| Fujitsu               | 4         | 4      | 1.34%   |
| Crucial               | 4         | 5      | 1.34%   |
| PNY                   | 3         | 4      | 1.01%   |
| Phison                | 3         | 4      | 1.01%   |
| LITEON                | 3         | 3      | 1.01%   |
| China                 | 3         | 4      | 1.01%   |
| KingDian              | 2         | 5      | 0.67%   |
| GOODRAM               | 2         | 2      | 0.67%   |
| Unknown               | 2         | 2      | 0.67%   |
| TwinMOS               | 1         | 1      | 0.34%   |
| Realtek Semiconductor | 1         | 1      | 0.34%   |
| RCESSD                | 1         | 1      | 0.34%   |
| Mushkin               | 1         | 1      | 0.34%   |
| Magnetic Data         | 1         | 1      | 0.34%   |
| LITEONIT              | 1         | 1      | 0.34%   |
| KingSpec              | 1         | 1      | 0.34%   |
| KingFast              | 1         | 2      | 0.34%   |
| Indilinx              | 1         | 1      | 0.34%   |
| IBM/Hitachi           | 1         | 1      | 0.34%   |
| HS-SSD-E100           | 1         | 1      | 0.34%   |
| HPE                   | 1         | 1      | 0.34%   |
| Hewlett-Packard       | 1         | 1      | 0.34%   |
| BIWIN                 | 1         | 1      | 0.34%   |
| Apacer                | 1         | 1      | 0.34%   |
| A-DATA Technology     | 1         | 1      | 0.34%   |
| 2.5"                  | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB        | 6         | 1.91%   |
| Seagate ST1000LM035-1RK172 1TB         | 5         | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 5         | 1.59%   |
| Toshiba MQ04ABF100 1TB                 | 4         | 1.27%   |
| Samsung NVMe SSD Drive 512GB           | 4         | 1.27%   |
| WDC WD5000AAKX-60U6AA0 500GB           | 3         | 0.96%   |
| Unknown MMC Card  32GB                 | 3         | 0.96%   |
| Toshiba MQ01ACF050 500GB               | 3         | 0.96%   |
| Toshiba MQ01ABF050 500GB               | 3         | 0.96%   |
| Toshiba MQ01ABD050 500GB               | 3         | 0.96%   |
| Seagate ST500LM000-1EJ162 500GB        | 3         | 0.96%   |
| Seagate ST500DM002-1BD142 500GB        | 3         | 0.96%   |
| Seagate ST3250312AS 250GB              | 3         | 0.96%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3         | 0.96%   |
| Intel SSDSC2BF180A4H 180GB             | 3         | 0.96%   |
| HGST HTS725050A7E630 500GB             | 3         | 0.96%   |
| HGST HTS545050A7E680 500GB             | 3         | 0.96%   |
| WDC WD800JD-00LSA0 80GB                | 2         | 0.64%   |
| WDC WD5000LPCX-80VHAT1 500GB           | 2         | 0.64%   |
| WDC WD5000LPCX-60VHAT0 500GB           | 2         | 0.64%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 2         | 0.64%   |
| Unknown MMC Card  64GB                 | 2         | 0.64%   |
| Unknown MMC Card  16GB                 | 2         | 0.64%   |
| Toshiba MQ01ABD100 1TB                 | 2         | 0.64%   |
| Toshiba MQ01ABD050V -63 500GB          | 2         | 0.64%   |
| Seagate ST9500325AS 500GB              | 2         | 0.64%   |
| Seagate ST500VT000-1DK142 500GB        | 2         | 0.64%   |
| Seagate ST500LM021-1KJ152 500GB        | 2         | 0.64%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 2         | 0.64%   |
| Samsung MZVLW256HEHP-000L7 256GB       | 2         | 0.64%   |
| Samsung MZVLB512HAJQ-000L7 512GB       | 2         | 0.64%   |
| Samsung MZVLB1T0HALR-00000 1TB         | 2         | 0.64%   |
| Samsung MZ7LN128HCHP-000H1 128GB SSD   | 2         | 0.64%   |
| PNY CS900 120GB SSD                    | 2         | 0.64%   |
| LITEON IT LCS-128L9S-HP 128GB SSD      | 2         | 0.64%   |
| Hitachi HTS723232A7A364 320GB          | 2         | 0.64%   |
| Hitachi HTS542525K9A300 250GB          | 2         | 0.64%   |
| Hitachi HDS721680PLA380 80GB           | 2         | 0.64%   |
| Crucial CT500MX500SSD1 500GB           | 2         | 0.64%   |
| Unknown                                | 2         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 69     | 32.52%  |
| WDC                 | 37        | 45     | 22.7%   |
| Toshiba             | 31        | 39     | 19.02%  |
| Hitachi             | 16        | 20     | 9.82%   |
| HGST                | 11        | 11     | 6.75%   |
| Samsung Electronics | 6         | 9      | 3.68%   |
| Fujitsu             | 4         | 4      | 2.45%   |
| Apple               | 2         | 2      | 1.23%   |
| Magnetic Data       | 1         | 1      | 0.61%   |
| IBM/Hitachi         | 1         | 1      | 0.61%   |
| HPE                 | 1         | 1      | 0.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 17     | 16.67%  |
| SanDisk             | 7         | 7      | 9.72%   |
| Kingston            | 5         | 6      | 6.94%   |
| Intel               | 5         | 6      | 6.94%   |
| Micron Technology   | 4         | 5      | 5.56%   |
| Crucial             | 4         | 5      | 5.56%   |
| SK hynix            | 3         | 3      | 4.17%   |
| PNY                 | 3         | 4      | 4.17%   |
| LITEON              | 3         | 3      | 4.17%   |
| China               | 3         | 4      | 4.17%   |
| KingDian            | 2         | 5      | 2.78%   |
| GOODRAM             | 2         | 2      | 2.78%   |
| Apple               | 2         | 2      | 2.78%   |
| Unknown             | 2         | 2      | 2.78%   |
| WDC                 | 1         | 1      | 1.39%   |
| TwinMOS             | 1         | 1      | 1.39%   |
| Toshiba             | 1         | 1      | 1.39%   |
| RCESSD              | 1         | 1      | 1.39%   |
| Mushkin             | 1         | 1      | 1.39%   |
| LITEONIT            | 1         | 1      | 1.39%   |
| KingSpec            | 1         | 1      | 1.39%   |
| KingFast            | 1         | 1      | 1.39%   |
| Indilinx            | 1         | 1      | 1.39%   |
| HS-SSD-E100         | 1         | 1      | 1.39%   |
| Hewlett-Packard     | 1         | 1      | 1.39%   |
| BIWIN               | 1         | 1      | 1.39%   |
| Apacer              | 1         | 1      | 1.39%   |
| A-DATA Technology   | 1         | 1      | 1.39%   |
| 2.5"                | 1         | 1      | 1.39%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 152       | 202    | 54.09%  |
| SSD     | 67        | 86     | 23.84%  |
| NVMe    | 46        | 61     | 16.37%  |
| MMC     | 15        | 20     | 5.34%   |
| Unknown | 1         | 1      | 0.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 203       | 287    | 76.6%   |
| NVMe | 46        | 61     | 17.36%  |
| MMC  | 15        | 20     | 5.66%   |
| SAS  | 1         | 2      | 0.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 162       | 212    | 74.31%  |
| 0.51-1.0   | 49        | 68     | 22.48%  |
| 1.01-2.0   | 4         | 4      | 1.83%   |
| 3.01-4.0   | 1         | 1      | 0.46%   |
| 2.01-3.0   | 1         | 2      | 0.46%   |
| 4.01-10.0  | 1         | 1      | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 71        | 27.84%  |
| 251-500        | 65        | 25.49%  |
| 1-20           | 30        | 11.76%  |
| 51-100         | 27        | 10.59%  |
| 501-1000       | 23        | 9.02%   |
| 21-50          | 21        | 8.24%   |
| 1001-2000      | 7         | 2.75%   |
| Unknown        | 6         | 2.35%   |
| More than 3000 | 4         | 1.57%   |
| 2001-3000      | 1         | 0.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 126       | 46.49%  |
| 21-50          | 56        | 20.66%  |
| 51-100         | 33        | 12.18%  |
| 101-250        | 31        | 11.44%  |
| 251-500        | 10        | 3.69%   |
| Unknown        | 6         | 2.21%   |
| More than 3000 | 3         | 1.11%   |
| 501-1000       | 3         | 1.11%   |
| 1001-2000      | 2         | 0.74%   |
| 2001-3000      | 1         | 0.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 3         | 3      | 7.89%   |
| Toshiba MQ01ABD050 500GB                         | 2         | 2      | 5.26%   |
| Seagate ST9500325AS 500GB                        | 2         | 2      | 5.26%   |
| Seagate ST500LM021-1KJ152 500GB                  | 2         | 2      | 5.26%   |
| Hitachi HTS542525K9A300 250GB                    | 2         | 2      | 5.26%   |
| Hitachi HDS721680PLA380 80GB                     | 2         | 3      | 5.26%   |
| WDC WD5000BPVT-22HXZT1 500GB                     | 1         | 1      | 2.63%   |
| WDC WD2500BEKT-60A25T1 250GB                     | 1         | 1      | 2.63%   |
| WDC WD2500AAJS-60Z0A0 250GB                      | 1         | 1      | 2.63%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 4      | 2.63%   |
| Toshiba MQ04ABF100 1TB                           | 1         | 1      | 2.63%   |
| Toshiba MQ01ACF050 500GB                         | 1         | 1      | 2.63%   |
| Toshiba MQ01ABD032 320GB                         | 1         | 1      | 2.63%   |
| Toshiba MK2565GSXN 250GB                         | 1         | 1      | 2.63%   |
| Toshiba MK1237GSX 120GB                          | 1         | 1      | 2.63%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 2.63%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 2.63%   |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 2.63%   |
| Seagate ST340016A 40GB                           | 1         | 1      | 2.63%   |
| Seagate ST3250312AS 250GB                        | 1         | 1      | 2.63%   |
| SanDisk SD7UB3Q256G1001 256GB SSD                | 1         | 1      | 2.63%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 2.63%   |
| Samsung Electronics HD080HJ 80GB                 | 1         | 1      | 2.63%   |
| Micron Technology 1100 SATA 256GB SSD            | 1         | 1      | 2.63%   |
| HPE MM1000GBKAL 1TB                              | 1         | 1      | 2.63%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 2.63%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 2.63%   |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 2.63%   |
| Fujitsu MHX2300BT 304GB                          | 1         | 1      | 2.63%   |
| Fujitsu MHW2120BH 120GB                          | 1         | 1      | 2.63%   |
| Apple HDD HTS541010A9E662 1TB                    | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 31.58%  |
| Toshiba             | 7         | 7      | 18.42%  |
| Hitachi             | 6         | 8      | 15.79%  |
| WDC                 | 4         | 7      | 10.53%  |
| Samsung Electronics | 2         | 2      | 5.26%   |
| Fujitsu             | 2         | 2      | 5.26%   |
| SanDisk             | 1         | 1      | 2.63%   |
| Micron Technology   | 1         | 1      | 2.63%   |
| HPE                 | 1         | 1      | 2.63%   |
| HGST                | 1         | 1      | 2.63%   |
| Apple               | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 34.29%  |
| Toshiba             | 7         | 7      | 20%     |
| Hitachi             | 6         | 8      | 17.14%  |
| WDC                 | 4         | 7      | 11.43%  |
| Fujitsu             | 2         | 2      | 5.71%   |
| Samsung Electronics | 1         | 1      | 2.86%   |
| HPE                 | 1         | 1      | 2.86%   |
| HGST                | 1         | 1      | 2.86%   |
| Apple               | 1         | 1      | 2.86%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 35        | 40     | 92.11%  |
| SSD  | 3         | 3      | 7.89%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| WDC WD800JD-00LSA0 80GB                    | 2         | 3      | 50%     |
| WDC WD2500BEVT-22A23T0 250GB               | 1         | 2      | 25%     |
| Samsung Electronics MZVLB1T0HALR-00000 1TB | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 5      | 75%     |
| Samsung Electronics | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 144       | 203    | 53.14%  |
| Works    | 85        | 118    | 31.37%  |
| Malfunc  | 38        | 43     | 14.02%  |
| Failed   | 4         | 6      | 1.48%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 201       | 74.44%  |
| Samsung Electronics              | 23        | 8.52%   |
| AMD                              | 18        | 6.67%   |
| Toshiba America Info Systems     | 5         | 1.85%   |
| SanDisk                          | 4         | 1.48%   |
| KIOXIA                           | 4         | 1.48%   |
| Phison Electronics               | 3         | 1.11%   |
| Nvidia                           | 3         | 1.11%   |
| SK hynix                         | 2         | 0.74%   |
| Silicon Integrated Systems [SiS] | 2         | 0.74%   |
| Realtek Semiconductor            | 1         | 0.37%   |
| Kingston Technology Company      | 1         | 0.37%   |
| JMicron Technology               | 1         | 0.37%   |
| Broadcom / LSI                   | 1         | 0.37%   |
| Apple                            | 1         | 0.37%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 21        | 6.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 19        | 6.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 17        | 5.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 13        | 4.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 13        | 4.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 12        | 3.91%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 12        | 3.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 12        | 3.91%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 12        | 3.91%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 8         | 2.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 8         | 2.61%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7         | 2.28%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 7         | 2.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 2.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6         | 1.95%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 1.95%   |
| Samsung NVMe SSD Controller 980                                                         | 5         | 1.63%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 1.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 1.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 5         | 1.63%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 3         | 0.98%   |
| Intel SSD 660P Series                                                                   | 3         | 0.98%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3         | 0.98%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3         | 0.98%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.65%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                                    | 2         | 0.65%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 2         | 0.65%   |
| Phison E12 NVMe Controller                                                              | 2         | 0.65%   |
| Nvidia MCP61 SATA Controller                                                            | 2         | 0.65%   |
| Nvidia MCP61 IDE                                                                        | 2         | 0.65%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.65%   |
| Intel C602 chipset 4-Port SATA Storage Control Unit                                     | 2         | 0.65%   |
| Intel C600/X79 series chipset IDE-r Controller                                          | 2         | 0.65%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 2         | 0.65%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 0.65%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 6 port SATA Controller [AHCI mode]                    | 2         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 177       | 61.89%  |
| NVMe | 46        | 16.08%  |
| RAID | 34        | 11.89%  |
| IDE  | 27        | 9.44%   |
| SAS  | 2         | 0.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 221       | 88.76%  |
| AMD    | 25        | 10.04%  |
| ARM    | 3         | 1.2%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 6         | 2.41%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 6         | 2.41%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 5         | 2.01%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 5         | 2.01%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 2.01%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 5         | 2.01%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 4         | 1.61%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 4         | 1.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 4         | 1.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 1.61%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 3         | 1.2%    |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz           | 3         | 1.2%    |
| Intel Core i5-5300U CPU @ 2.30GHz           | 3         | 1.2%    |
| Intel Core i5-4590 CPU @ 3.30GHz            | 3         | 1.2%    |
| Intel Core i5-4300U CPU @ 1.90GHz           | 3         | 1.2%    |
| Intel Core i5-2410M CPU @ 2.30GHz           | 3         | 1.2%    |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 3         | 1.2%    |
| Intel Core i3-4005U CPU @ 1.70GHz           | 3         | 1.2%    |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 1.2%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 1.2%    |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 2         | 0.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.8%    |
| Intel Core i7-7600U CPU @ 2.80GHz           | 2         | 0.8%    |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 2         | 0.8%    |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 0.8%    |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.8%    |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 0.8%    |
| Intel Core i5-4300M CPU @ 2.60GHz           | 2         | 0.8%    |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.8%    |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 0.8%    |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2         | 0.8%    |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 0.8%    |
| Intel Core i5-2400 CPU @ 3.10GHz            | 2         | 0.8%    |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 2         | 0.8%    |
| Intel Core i3-7100U CPU @ 2.40GHz           | 2         | 0.8%    |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 0.8%    |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 0.8%    |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 0.8%    |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 0.8%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 90        | 36.14%  |
| Intel Core i7           | 42        | 16.87%  |
| Intel Core i3           | 32        | 12.85%  |
| Intel Core 2 Duo        | 12        | 4.82%   |
| Other                   | 11        | 4.42%   |
| Intel Celeron           | 8         | 3.21%   |
| Intel Atom              | 6         | 2.41%   |
| Intel Xeon              | 5         | 2.01%   |
| Intel Pentium Dual-Core | 4         | 1.61%   |
| AMD Ryzen 5             | 4         | 1.61%   |
| AMD Ryzen 9             | 3         | 1.2%    |
| AMD E1                  | 3         | 1.2%    |
| Intel Pentium           | 2         | 0.8%    |
| ARM BCM                 | 2         | 0.8%    |
| AMD C-60                | 2         | 0.8%    |
| AMD Athlon 64 X2        | 2         | 0.8%    |
| AMD A8                  | 2         | 0.8%    |
| AMD A6                  | 2         | 0.8%    |
| Intel Pentium M         | 1         | 0.4%    |
| Intel Pentium Gold      | 1         | 0.4%    |
| Intel Pentium Dual      | 1         | 0.4%    |
| Intel Pentium 4         | 1         | 0.4%    |
| Intel Genuine           | 1         | 0.4%    |
| Intel Core i9           | 1         | 0.4%    |
| Intel Core 2 Quad       | 1         | 0.4%    |
| Intel Core 2            | 1         | 0.4%    |
| Intel Celeron M         | 1         | 0.4%    |
| ARM AArch64             | 1         | 0.4%    |
| AMD Ryzen 7 PRO         | 1         | 0.4%    |
| AMD Ryzen 7             | 1         | 0.4%    |
| AMD Ryzen 3             | 1         | 0.4%    |
| AMD Phenom II X6        | 1         | 0.4%    |
| AMD E                   | 1         | 0.4%    |
| AMD Athlon XP           | 1         | 0.4%    |
| AMD A4                  | 1         | 0.4%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 140       | 56.22%  |
| 4      | 83        | 33.33%  |
| 6      | 8         | 3.21%   |
| 1      | 8         | 3.21%   |
| 8      | 5         | 2.01%   |
| 12     | 3         | 1.2%    |
| 16     | 2         | 0.8%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 247       | 99.2%   |
| 2      | 2         | 0.8%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 169       | 67.87%  |
| 1      | 80        | 32.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 240       | 96.39%  |
| 32-bit         | 5         | 2.01%   |
| Unknown        | 4         | 1.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 40        | 15.87%  |
| 0x206a7    | 24        | 9.52%   |
| 0x306c3    | 19        | 7.54%   |
| 0x306a9    | 16        | 6.35%   |
| 0x306d4    | 14        | 5.56%   |
| 0x806ea    | 12        | 4.76%   |
| 0x40651    | 11        | 4.37%   |
| 0x806ec    | 9         | 3.57%   |
| 0x20655    | 8         | 3.17%   |
| 0x806c1    | 7         | 2.78%   |
| 0x506e3    | 7         | 2.78%   |
| 0x1067a    | 7         | 2.78%   |
| 0x806e9    | 6         | 2.38%   |
| 0x406e3    | 6         | 2.38%   |
| 0x6fd      | 5         | 1.98%   |
| 0x20652    | 5         | 1.98%   |
| 0x30678    | 4         | 1.59%   |
| 0x906e9    | 3         | 1.19%   |
| 0x6fb      | 3         | 1.19%   |
| 0x10676    | 3         | 1.19%   |
| 0x08701021 | 3         | 1.19%   |
| 0x906ea    | 2         | 0.79%   |
| 0x706e5    | 2         | 0.79%   |
| 0x406c4    | 2         | 0.79%   |
| 0x406c3    | 2         | 0.79%   |
| 0x206d7    | 2         | 0.79%   |
| 0x0a50000c | 2         | 0.79%   |
| 0x08108102 | 2         | 0.79%   |
| 0x07030105 | 2         | 0.79%   |
| 0x0700010f | 2         | 0.79%   |
| 0x05000119 | 2         | 0.79%   |
| 0xf29      | 1         | 0.4%    |
| 0x90675    | 1         | 0.4%    |
| 0x806eb    | 1         | 0.4%    |
| 0x806d1    | 1         | 0.4%    |
| 0x706a1    | 1         | 0.4%    |
| 0x6ec      | 1         | 0.4%    |
| 0x6e8      | 1         | 0.4%    |
| 0x6d8      | 1         | 0.4%    |
| 0x50654    | 1         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 14.86%  |
| Haswell          | 36        | 14.46%  |
| SandyBridge      | 28        | 11.24%  |
| IvyBridge        | 18        | 7.23%   |
| Skylake          | 17        | 6.83%   |
| Westmere         | 16        | 6.43%   |
| Broadwell        | 15        | 6.02%   |
| Penryn           | 12        | 4.82%   |
| Silvermont       | 10        | 4.02%   |
| TigerLake        | 9         | 3.61%   |
| Core             | 9         | 3.61%   |
| Unknown          | 6         | 2.41%   |
| Bobcat           | 4         | 1.61%   |
| Zen 3            | 3         | 1.2%    |
| Zen 2            | 3         | 1.2%    |
| P6               | 3         | 1.2%    |
| IceLake          | 3         | 1.2%    |
| Zen+             | 2         | 0.8%    |
| Puma             | 2         | 0.8%    |
| K8 Hammer        | 2         | 0.8%    |
| Jaguar           | 2         | 0.8%    |
| Bonnell          | 2         | 0.8%    |
| Piledriver       | 1         | 0.4%    |
| NetBurst         | 1         | 0.4%    |
| Nehalem          | 1         | 0.4%    |
| K6               | 1         | 0.4%    |
| K10 Llano        | 1         | 0.4%    |
| K10              | 1         | 0.4%    |
| Goldmont plus    | 1         | 0.4%    |
| Excavator        | 1         | 0.4%    |
| CometLake        | 1         | 0.4%    |
| Alderlake Hybrid | 1         | 0.4%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 193       | 66.1%   |
| Nvidia                           | 60        | 20.55%  |
| AMD                              | 38        | 13.01%  |
| Silicon Integrated Systems [SiS] | 1         | 0.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 8.08%   |
| Intel HD Graphics 5500                                                                   | 14        | 4.71%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 4.71%   |
| Intel UHD Graphics 620                                                                   | 13        | 4.38%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 4.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 3.03%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 3.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 2.69%   |
| Intel HD Graphics 620                                                                    | 8         | 2.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 2.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 2.36%   |
| Intel HD Graphics 530                                                                    | 7         | 2.36%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 2.02%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.02%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.68%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.35%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 1.01%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 1.01%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 1.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.01%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 1.01%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.01%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.67%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.67%   |
| Nvidia GM204GL [Quadro M4000]                                                            | 2         | 0.67%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.67%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.67%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.67%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.67%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.67%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 2         | 0.67%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 0.67%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.67%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.67%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.67%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.67%   |
| Intel HD Graphics 630                                                                    | 2         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 148       | 59.2%   |
| Intel + Nvidia | 37        | 14.8%   |
| 1 x AMD        | 29        | 11.6%   |
| 1 x Nvidia     | 22        | 8.8%    |
| Intel + AMD    | 7         | 2.8%    |
| Other          | 3         | 1.2%    |
| 2 x Nvidia     | 1         | 0.4%    |
| 2 x AMD        | 1         | 0.4%    |
| 1 x SiS        | 1         | 0.4%    |
| AMD + Nvidia   | 1         | 0.4%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 210       | 83%     |
| Proprietary | 30        | 11.86%  |
| Unknown     | 13        | 5.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 170       | 66.67%  |
| 1.01-2.0   | 33        | 12.94%  |
| 0.01-0.5   | 28        | 10.98%  |
| 0.51-1.0   | 11        | 4.31%   |
| 3.01-4.0   | 9         | 3.53%   |
| 7.01-8.0   | 3         | 1.18%   |
| 2.01-3.0   | 1         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 39        | 16.39%  |
| AU Optronics            | 38        | 15.97%  |
| LG Display              | 36        | 15.13%  |
| Chimei Innolux          | 28        | 11.76%  |
| BOE                     | 23        | 9.66%   |
| Dell                    | 16        | 6.72%   |
| Hewlett-Packard         | 13        | 5.46%   |
| InfoVision              | 6         | 2.52%   |
| Lenovo                  | 4         | 1.68%   |
| Apple                   | 4         | 1.68%   |
| Sharp                   | 3         | 1.26%   |
| LG Philips              | 3         | 1.26%   |
| Goldstar                | 3         | 1.26%   |
| Chi Mei Optoelectronics | 3         | 1.26%   |
| Acer                    | 3         | 1.26%   |
| Philips                 | 2         | 0.84%   |
| Iiyama                  | 2         | 0.84%   |
| BenQ                    | 2         | 0.84%   |
| TMX                     | 1         | 0.42%   |
| RTK                     | 1         | 0.42%   |
| PANDA                   | 1         | 0.42%   |
| MSI                     | 1         | 0.42%   |
| MiTAC                   | 1         | 0.42%   |
| Medion                  | 1         | 0.42%   |
| LGD                     | 1         | 0.42%   |
| IBM                     | 1         | 0.42%   |
| Fujitsu Siemens         | 1         | 0.42%   |
| Ancor Communications    | 1         | 0.42%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 4         | 1.67%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch  | 3         | 1.25%   |
| Dell E2414H DEL4090 1920x1080 531x299mm 24.0-inch                     | 3         | 1.25%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 3         | 1.25%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 1.25%   |
| Samsung Electronics LCD Monitor SDC4D42 1366x768 309x174mm 14.0-inch  | 2         | 0.83%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 2         | 0.83%   |
| LG Display LCD Monitor LGD0504 1366x768 344x194mm 15.5-inch           | 2         | 0.83%   |
| LG Display LCD Monitor LGD03D9 1366x768 345x194mm 15.6-inch           | 2         | 0.83%   |
| Lenovo LEN LT2452pwC LEN1144 1920x1200 518x324mm 24.1-inch            | 2         | 0.83%   |
| Dell 2208WFP DEL403B 1680x1050 473x296mm 22.0-inch                    | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch       | 2         | 0.83%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch        | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch         | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 0.83%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 0.83%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.42%   |
| Sharp LCD Monitor SHP1516 3840x2400 336x210mm 15.6-inch               | 1         | 0.42%   |
| Sharp LCD Monitor SHP14A8 3840x2400 288x180mm 13.4-inch               | 1         | 0.42%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch               | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch   | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM0372 1680x1050 440x300mm 21.0-inch  | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM027E 1680x1050 474x296mm 22.0-inch  | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch  | 1         | 0.42%   |
| Samsung Electronics SyncMaster SAM0161 1280x1024 340x270mm 17.1-inch  | 1         | 0.42%   |
| Samsung Electronics SMBX2440 SAM068A 1920x1080 531x299mm 24.0-inch    | 1         | 0.42%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 1         | 0.42%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch     | 1         | 0.42%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch     | 1         | 0.42%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch     | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SEC434E 1600x900 310x174mm 14.0-inch  | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SEC4143 1400x1050 286x214mm 14.1-inch | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SEC3959 1366x768 344x194mm 15.5-inch  | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SEC3846 1680x1050 331x207mm 15.4-inch | 1         | 0.42%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch  | 1         | 0.42%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 89        | 38.2%   |
| 1920x1080 (FHD)    | 78        | 33.48%  |
| 1600x900 (HD+)     | 16        | 6.87%   |
| 1280x1024 (SXGA)   | 8         | 3.43%   |
| 3840x2160 (4K)     | 7         | 3%      |
| 1680x1050 (WSXGA+) | 7         | 3%      |
| 1440x900 (WXGA+)   | 7         | 3%      |
| 1280x800 (WXGA)    | 6         | 2.58%   |
| 1024x600           | 3         | 1.29%   |
| 3840x2400          | 2         | 0.86%   |
| 2880x1800          | 1         | 0.43%   |
| 2560x1600          | 1         | 0.43%   |
| 2560x1440 (QHD)    | 1         | 0.43%   |
| 1920x1200 (WUXGA)  | 1         | 0.43%   |
| 1680x945           | 1         | 0.43%   |
| 1400x1050          | 1         | 0.43%   |
| 1360x768           | 1         | 0.43%   |
| 1280x720 (HD)      | 1         | 0.43%   |
| 1152x864           | 1         | 0.43%   |
| 1024x768 (XGA)     | 1         | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 103       | 42.92%  |
| 14      | 26        | 10.83%  |
| 13      | 21        | 8.75%   |
| 24      | 14        | 5.83%   |
| 17      | 12        | 5%      |
| 12      | 10        | 4.17%   |
| 19      | 8         | 3.33%   |
| 23      | 7         | 2.92%   |
| 27      | 5         | 2.08%   |
| 22      | 5         | 2.08%   |
| 21      | 5         | 2.08%   |
| 18      | 5         | 2.08%   |
| 20      | 3         | 1.25%   |
| 11      | 3         | 1.25%   |
| Unknown | 3         | 1.25%   |
| 84      | 2         | 0.83%   |
| 10      | 2         | 0.83%   |
| 72      | 1         | 0.42%   |
| 58      | 1         | 0.42%   |
| 54      | 1         | 0.42%   |
| 52      | 1         | 0.42%   |
| 43      | 1         | 0.42%   |
| 31      | 1         | 0.42%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 141       | 59%     |
| 201-300     | 25        | 10.46%  |
| 501-600     | 24        | 10.04%  |
| 401-500     | 22        | 9.21%   |
| 351-400     | 15        | 6.28%   |
| 1501-2000   | 3         | 1.26%   |
| 1001-1500   | 3         | 1.26%   |
| Unknown     | 3         | 1.26%   |
| 601-700     | 2         | 0.84%   |
| 901-1000    | 1         | 0.42%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 191       | 82.68%  |
| 16/10   | 26        | 11.26%  |
| 5/4     | 8         | 3.46%   |
| 4/3     | 3         | 1.3%    |
| Unknown | 3         | 1.3%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 103       | 43.1%   |
| 81-90          | 38        | 15.9%   |
| 201-250        | 26        | 10.88%  |
| 151-200        | 13        | 5.44%   |
| 61-70          | 10        | 4.18%   |
| 141-150        | 9         | 3.77%   |
| 71-80          | 7         | 2.93%   |
| More than 1000 | 6         | 2.51%   |
| 301-350        | 5         | 2.09%   |
| 121-130        | 5         | 2.09%   |
| 51-60          | 3         | 1.26%   |
| 251-300        | 3         | 1.26%   |
| Unknown        | 3         | 1.26%   |
| 41-50          | 2         | 0.84%   |
| 131-140        | 2         | 0.84%   |
| 351-500        | 1         | 0.42%   |
| 111-120        | 1         | 0.42%   |
| 501-1000       | 1         | 0.42%   |
| 91-100         | 1         | 0.42%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 89        | 37.39%  |
| 51-100        | 62        | 26.05%  |
| 121-160       | 61        | 25.63%  |
| 161-240       | 14        | 5.88%   |
| 1-50          | 6         | 2.52%   |
| More than 240 | 3         | 1.26%   |
| Unknown       | 3         | 1.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 226       | 90.04%  |
| 2     | 15        | 5.98%   |
| 0     | 10        | 3.98%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 141       | 36.53%  |
| Realtek Semiconductor            | 101       | 26.17%  |
| Qualcomm Atheros                 | 47        | 12.18%  |
| Broadcom                         | 33        | 8.55%   |
| Ralink Technology                | 18        | 4.66%   |
| Ralink                           | 10        | 2.59%   |
| TP-Link                          | 6         | 1.55%   |
| Broadcom Limited                 | 4         | 1.04%   |
| Xiaomi                           | 3         | 0.78%   |
| Nvidia                           | 3         | 0.78%   |
| Marvell Technology Group         | 2         | 0.52%   |
| Lenovo                           | 2         | 0.52%   |
| Dell                             | 2         | 0.52%   |
| D-Link System                    | 2         | 0.52%   |
| Silicon Integrated Systems [SiS] | 1         | 0.26%   |
| Sierra Wireless                  | 1         | 0.26%   |
| Samsung Electronics              | 1         | 0.26%   |
| Qualcomm Atheros Communications  | 1         | 0.26%   |
| Qualcomm                         | 1         | 0.26%   |
| Microchip Technology             | 1         | 0.26%   |
| MediaTek                         | 1         | 0.26%   |
| JMicron Technology               | 1         | 0.26%   |
| Gemtek                           | 1         | 0.26%   |
| Fibocom                          | 1         | 0.26%   |
| Arduino SA                       | 1         | 0.26%   |
| Aquantia                         | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 63        | 13.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 24        | 5.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 19        | 3.97%   |
| Intel Ethernet Connection I217-LM                                 | 16        | 3.35%   |
| Intel Wireless 8265 / 8275                                        | 11        | 2.3%    |
| Intel Wireless 7265                                               | 10        | 2.09%   |
| Intel 82577LM Gigabit Network Connection                          | 10        | 2.09%   |
| Ralink MT7601U Wireless Adapter                                   | 9         | 1.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 1.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.67%   |
| Ralink RT5370 Wireless Adapter                                    | 8         | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 1.67%   |
| Intel Wireless 8260                                               | 8         | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.46%   |
| Intel Ethernet Connection (3) I218-LM                             | 7         | 1.46%   |
| Intel Centrino Advanced-N 6200                                    | 7         | 1.46%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.26%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 1.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 5         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 5         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.05%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 5         | 1.05%   |
| Intel Wireless 7260                                               | 5         | 1.05%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.05%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.05%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.05%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.84%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 0.84%   |
| Intel I211 Gigabit Network Connection                             | 4         | 0.84%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 4         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 97        | 41.63%  |
| Qualcomm Atheros                | 41        | 17.6%   |
| Realtek Semiconductor           | 28        | 12.02%  |
| Broadcom                        | 23        | 9.87%   |
| Ralink Technology               | 18        | 7.73%   |
| Ralink                          | 10        | 4.29%   |
| TP-Link                         | 6         | 2.58%   |
| Broadcom Limited                | 3         | 1.29%   |
| Sierra Wireless                 | 1         | 0.43%   |
| Qualcomm Atheros Communications | 1         | 0.43%   |
| MediaTek                        | 1         | 0.43%   |
| Gemtek                          | 1         | 0.43%   |
| Fibocom                         | 1         | 0.43%   |
| Dell                            | 1         | 0.43%   |
| D-Link System                   | 1         | 0.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 11        | 4.68%   |
| Intel Wireless 7265                                            | 10        | 4.26%   |
| Ralink MT7601U Wireless Adapter                                | 9         | 3.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 3.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 3.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 3.4%    |
| Ralink RT5370 Wireless Adapter                                 | 8         | 3.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 8         | 3.4%    |
| Intel Wireless 8260                                            | 8         | 3.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 7         | 2.98%   |
| Intel Centrino Advanced-N 6200                                 | 7         | 2.98%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 2.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 2.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 2.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 5         | 2.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 2.13%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 2.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 2.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 2.13%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5         | 2.13%   |
| Intel Wireless 7260                                            | 5         | 2.13%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 2.13%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 2.13%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 1.7%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 1.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.28%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.28%   |
| Intel Wireless 3165                                            | 3         | 1.28%   |
| Intel WiFi Link 5100                                           | 3         | 1.28%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.28%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 1.28%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2         | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 0.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.85%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 0.85%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 0.85%   |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 0.85%   |
| Broadcom BCM4311 802.11b/g WLAN                                | 2         | 0.85%   |
| TP-Link Archer T4U ver.3                                       | 1         | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 102       | 43.22%  |
| Realtek Semiconductor            | 90        | 38.14%  |
| Broadcom                         | 14        | 5.93%   |
| Qualcomm Atheros                 | 12        | 5.08%   |
| Xiaomi                           | 3         | 1.27%   |
| Nvidia                           | 3         | 1.27%   |
| Marvell Technology Group         | 2         | 0.85%   |
| Lenovo                           | 2         | 0.85%   |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |
| Samsung Electronics              | 1         | 0.42%   |
| Qualcomm                         | 1         | 0.42%   |
| Microchip Technology             | 1         | 0.42%   |
| JMicron Technology               | 1         | 0.42%   |
| D-Link System                    | 1         | 0.42%   |
| Broadcom Limited                 | 1         | 0.42%   |
| Aquantia                         | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 63        | 26.25%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 24        | 10%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 19        | 7.92%   |
| Intel Ethernet Connection I217-LM                                              | 16        | 6.67%   |
| Intel 82577LM Gigabit Network Connection                                       | 10        | 4.17%   |
| Intel Ethernet Connection (2) I219-LM                                          | 8         | 3.33%   |
| Intel Ethernet Connection (3) I218-LM                                          | 7         | 2.92%   |
| Intel Ethernet Connection I218-LM                                              | 5         | 2.08%   |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 2.08%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 4         | 1.67%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 1.67%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 1.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 3         | 1.25%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 3         | 1.25%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 1.25%   |
| Intel Ethernet Connection I217-V                                               | 3         | 1.25%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 3         | 1.25%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                        | 3         | 1.25%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 2         | 0.83%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.83%   |
| Nvidia MCP61 Ethernet                                                          | 2         | 0.83%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 2         | 0.83%   |
| Intel I210 Gigabit Network Connection                                          | 2         | 0.83%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.83%   |
| Intel 82574L Gigabit Network Connection                                        | 2         | 0.83%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 2         | 0.83%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 0.83%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 2         | 0.83%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 1         | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.42%   |
| Qualcomm Fairphone 4 5G                                                        | 1         | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.42%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.42%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.42%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.42%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                                  | 1         | 0.42%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.42%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.42%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 224       | 49.78%  |
| WiFi     | 223       | 49.56%  |
| Modem    | 3         | 0.67%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 182       | 73.39%  |
| Ethernet | 66        | 26.61%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 174       | 69.6%   |
| 1     | 63        | 25.2%   |
| 0     | 7         | 2.8%    |
| 3     | 5         | 2%      |
| 7     | 1         | 0.4%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 249       | 100%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 43.05%  |
| Qualcomm Atheros Communications | 19        | 12.58%  |
| Realtek Semiconductor           | 18        | 11.92%  |
| Broadcom                        | 10        | 6.62%   |
| Dell                            | 7         | 4.64%   |
| Ralink                          | 5         | 3.31%   |
| Lite-On Technology              | 5         | 3.31%   |
| IMC Networks                    | 5         | 3.31%   |
| Hewlett-Packard                 | 4         | 2.65%   |
| Cambridge Silicon Radio         | 3         | 1.99%   |
| Apple                           | 3         | 1.99%   |
| Toshiba                         | 2         | 1.32%   |
| ASUSTek Computer                | 2         | 1.32%   |
| Foxconn International           | 1         | 0.66%   |
| Foxconn / Hon Hai               | 1         | 0.66%   |
| Alps Electric                   | 1         | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 35        | 23.18%  |
| Realtek Bluetooth Radio                             | 12        | 7.95%   |
| Intel AX201 Bluetooth                               | 10        | 6.62%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 5.96%   |
| Intel AX200 Bluetooth                               | 6         | 3.97%   |
| Ralink RT3290 Bluetooth                             | 5         | 3.31%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 3.31%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 3.31%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 2.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 2.65%   |
| IMC Networks Bluetooth Device                       | 4         | 2.65%   |
| Dell DW375 Bluetooth Module                         | 4         | 2.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.99%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.99%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 1.99%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 1.99%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.99%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.32%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 1.32%   |
| Dell Wireless 360 Bluetooth                         | 2         | 1.32%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 1.32%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.32%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.32%   |
| Toshiba Bluetooth Device                            | 1         | 0.66%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.66%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.66%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.66%   |
| IMC Networks Wireless_Device                        | 1         | 0.66%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]       | 1         | 0.66%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.66%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.66%   |
| Dell Wireless 350 Bluetooth                         | 1         | 0.66%   |
| Broadcom HP Portable Valentine                      | 1         | 0.66%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.66%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 1         | 0.66%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.66%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.66%   |
| ASUS 2045 Bluetooth 2.0 Device with trace filter    | 1         | 0.66%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 216       | 74.23%  |
| Nvidia                           | 36        | 12.37%  |
| AMD                              | 30        | 10.31%  |
| Silicon Integrated Systems [SiS] | 2         | 0.69%   |
| Lenovo                           | 2         | 0.69%   |
| Logitech                         | 1         | 0.34%   |
| Hewlett-Packard                  | 1         | 0.34%   |
| GN Netcom                        | 1         | 0.34%   |
| GEMBIRD                          | 1         | 0.34%   |
| C-Media Electronics              | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 29        | 8.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 6.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 21        | 5.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 5.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 17        | 4.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 17        | 4.78%   |
| Intel Broadwell-U Audio Controller                                                                | 15        | 4.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 14        | 3.93%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 3.93%   |
| Intel 8 Series HD Audio Controller                                                                | 14        | 3.93%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 3.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 2.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 2.53%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 6         | 1.69%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.69%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.69%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 6         | 1.69%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.4%    |
| Nvidia High Definition Audio Controller                                                           | 4         | 1.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.12%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 4         | 1.12%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 1.12%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.12%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.12%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.84%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 0.84%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.84%   |
| Nvidia MCP61 High Definition Audio                                                                | 2         | 0.56%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.56%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.56%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.56%   |
| Nvidia Audio device                                                                               | 2         | 0.56%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 2         | 0.56%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.56%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 0.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 50        | 27.93%  |
| SK hynix            | 48        | 26.82%  |
| Micron Technology   | 26        | 14.53%  |
| Kingston            | 19        | 10.61%  |
| Unknown             | 6         | 3.35%   |
| Crucial             | 4         | 2.23%   |
| Corsair             | 4         | 2.23%   |
| A-DATA Technology   | 4         | 2.23%   |
| Elpida              | 3         | 1.68%   |
| Ramaxel Technology  | 2         | 1.12%   |
| Nanya Technology    | 2         | 1.12%   |
| Wilk                | 1         | 0.56%   |
| Transcend           | 1         | 0.56%   |
| Toshiba             | 1         | 0.56%   |
| TakeMS              | 1         | 0.56%   |
| Sesame              | 1         | 0.56%   |
| Qimonda             | 1         | 0.56%   |
| G.Skill             | 1         | 0.56%   |
| Avant               | 1         | 0.56%   |
| ASint Technology    | 1         | 0.56%   |
| Apacer              | 1         | 0.56%   |
| Unknown             | 1         | 0.56%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1648MT/s   | 4         | 2.05%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s  | 4         | 2.05%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s | 3         | 1.54%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s | 3         | 1.54%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s  | 3         | 1.54%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s    | 3         | 1.54%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s  | 3         | 1.54%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 3         | 1.54%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s   | 2         | 1.03%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s | 2         | 1.03%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s | 2         | 1.03%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s  | 2         | 1.03%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s  | 2         | 1.03%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 2         | 1.03%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s  | 2         | 1.03%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s  | 2         | 1.03%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s  | 2         | 1.03%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s   | 2         | 1.03%   |
| Kingston RAM HP687515-H66-MCN 4GB SODIMM DDR3 1600MT/s | 2         | 1.03%   |
| Kingston RAM HP16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s  | 2         | 1.03%   |
| Wilk RAM Module 16GB DIMM DDR4 2667MT/s                | 1         | 0.51%   |
| Unknown RAM Module 4GB SODIMM DDR3                     | 1         | 0.51%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s         | 1         | 0.51%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s              | 1         | 0.51%   |
| Unknown RAM Module 2GB DIMM                            | 1         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR2                  | 1         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s               | 1         | 0.51%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s           | 1         | 0.51%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s    | 1         | 0.51%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s      | 1         | 0.51%   |
| TakeMS RAM TMS2GB264C081-665U 2048MB DIMM DDR2 667MT/s | 1         | 0.51%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2667MT/s        | 1         | 0.51%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s        | 1         | 0.51%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM                 | 1         | 0.51%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s   | 1         | 0.51%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s   | 1         | 0.51%   |
| SK hynix RAM HMT451U6AFR8A-PB 4GB DIMM DDR3 1600MT/s   | 1         | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s | 1         | 0.51%   |
| SK hynix RAM HMT425U6AFR6C-PB 2GB DIMM DDR3 1600MT/s   | 1         | 0.51%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s | 1         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 69        | 50%     |
| DDR4    | 44        | 31.88%  |
| SDRAM   | 7         | 5.07%   |
| DDR2    | 7         | 5.07%   |
| LPDDR4  | 4         | 2.9%    |
| LPDDR3  | 3         | 2.17%   |
| Unknown | 3         | 2.17%   |
| DDR     | 1         | 0.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 93        | 71.54%  |
| DIMM         | 31        | 23.85%  |
| Row Of Chips | 4         | 3.08%   |
| RIMM         | 1         | 0.77%   |
| Unknown      | 1         | 0.77%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 63        | 42%     |
| 8192  | 44        | 29.33%  |
| 2048  | 20        | 13.33%  |
| 16384 | 11        | 7.33%   |
| 1024  | 7         | 4.67%   |
| 32768 | 2         | 1.33%   |
| 512   | 1         | 0.67%   |
| 256   | 1         | 0.67%   |
| 128   | 1         | 0.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 51        | 32.69%  |
| 2667    | 20        | 12.82%  |
| 3200    | 13        | 8.33%   |
| 1334    | 12        | 7.69%   |
| 1333    | 10        | 6.41%   |
| 2400    | 8         | 5.13%   |
| 2133    | 6         | 3.85%   |
| 1648    | 4         | 2.56%   |
| 667     | 4         | 2.56%   |
| 1066    | 3         | 1.92%   |
| 800     | 3         | 1.92%   |
| Unknown | 3         | 1.92%   |
| 3600    | 2         | 1.28%   |
| 1867    | 2         | 1.28%   |
| 1067    | 2         | 1.28%   |
| 975     | 2         | 1.28%   |
| 4267    | 1         | 0.64%   |
| 4199    | 1         | 0.64%   |
| 3733    | 1         | 0.64%   |
| 3400    | 1         | 0.64%   |
| 3266    | 1         | 0.64%   |
| 2666    | 1         | 0.64%   |
| 1866    | 1         | 0.64%   |
| 1639    | 1         | 0.64%   |
| 400     | 1         | 0.64%   |
| 333     | 1         | 0.64%   |
| 266     | 1         | 0.64%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Canon           | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| HP Deskjet 3510 series | 1         | 50%     |
| Canon MB2000 series    | 1         | 50%     |

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
| Chicony Electronics                    | 45        | 28.13%  |
| IMC Networks                           | 19        | 11.88%  |
| Realtek Semiconductor                  | 15        | 9.38%   |
| Cheng Uei Precision Industry (Foxlink) | 15        | 9.38%   |
| Sunplus Innovation Technology          | 10        | 6.25%   |
| Suyin                                  | 9         | 5.63%   |
| Lite-On Technology                     | 9         | 5.63%   |
| Microdia                               | 8         | 5%      |
| Ricoh                                  | 4         | 2.5%    |
| Quanta                                 | 4         | 2.5%    |
| Apple                                  | 4         | 2.5%    |
| Acer                                   | 4         | 2.5%    |
| Syntek                                 | 3         | 1.88%   |
| Logitech                               | 3         | 1.88%   |
| Luxvisions Innotech Limited            | 2         | 1.25%   |
| Alcor Micro                            | 2         | 1.25%   |
| Z-Star Microelectronics                | 1         | 0.63%   |
| Sunplus Technology                     | 1         | 0.63%   |
| Silicon Motion                         | 1         | 0.63%   |
| ALi                                    | 1         | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| IMC Networks Integrated Camera                              | 6         | 3.73%   |
| Chicony Integrated Camera                                   | 6         | 3.73%   |
| Chicony HP Webcam [2 MP Macro]                              | 6         | 3.73%   |
| Chicony HP Webcam                                           | 5         | 3.11%   |
| Realtek Integrated_Webcam_HD                                | 4         | 2.48%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam         | 4         | 2.48%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera         | 4         | 2.48%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 3         | 1.86%   |
| Realtek USB Camera                                          | 3         | 1.86%   |
| Microdia Integrated Webcam                                  | 3         | 1.86%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 3         | 1.86%   |
| IMC Networks Lenovo EasyCamera                              | 3         | 1.86%   |
| Chicony HP HD Webcam                                        | 3         | 1.86%   |
| Syntek Lenovo EasyCamera                                    | 2         | 1.24%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 2         | 1.24%   |
| Sunplus Integrated_Webcam_HD                                | 2         | 1.24%   |
| Sunplus HP Universal Camera                                 | 2         | 1.24%   |
| Ricoh Laptop_Integrated_Webcam_FHD                          | 2         | 1.24%   |
| Lite-On TOSHIBA Web Camera - HD                             | 2         | 1.24%   |
| Lite-On HP HD Webcam                                        | 2         | 1.24%   |
| Lite-On HP HD Camera                                        | 2         | 1.24%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 2         | 1.24%   |
| IMC Networks Integrated Webcam                              | 2         | 1.24%   |
| IMC Networks HP TrueVision HD Camera                        | 2         | 1.24%   |
| Chicony TOSHIBA Web Camera - HD                             | 2         | 1.24%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 2         | 1.24%   |
| Chicony Integrated Camera (1280x720@30)                     | 2         | 1.24%   |
| Chicony HP Wide Vision HD Camera                            | 2         | 1.24%   |
| Chicony HP Truevision HD                                    | 2         | 1.24%   |
| Chicony HP HD Webcam [Fixed]                                | 2         | 1.24%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD     | 2         | 1.24%   |
| Apple FaceTime HD Camera (Built-in)                         | 2         | 1.24%   |
| Acer Integrated Camera                                      | 2         | 1.24%   |
| Z-Star Vimicro USB2.0 Camera                                | 1         | 0.62%   |
| Syntek EasyCamera                                           | 1         | 0.62%   |
| Suyin WebCam                                                | 1         | 0.62%   |
| Suyin Sony Visual Communication Camera                      | 1         | 0.62%   |
| Suyin RGBIR Camera                                          | 1         | 0.62%   |
| Suyin Integrated_Webcam_HD                                  | 1         | 0.62%   |
| Suyin Integrated_Webcam_2M                                  | 1         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 28        | 68.29%  |
| Synaptics                  | 6         | 14.63%  |
| Elan Microelectronics      | 4         | 9.76%   |
| Shenzhen Goodix Technology | 2         | 4.88%   |
| Upek                       | 1         | 2.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 24.39%  |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 12.2%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 9.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 7.32%   |
| Validity Sensors VFS491                                                    | 2         | 4.88%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 4.88%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.88%   |
| Elan ELAN:ARM-M4                                                           | 2         | 4.88%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.44%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.44%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 2.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 2.44%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.44%   |
| Synaptics UWP WBDI Device                                                  | 1         | 2.44%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 2.44%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 2.44%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 2.44%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 17        | 65.38%  |
| Alcor Micro | 5         | 19.23%  |
| O2 Micro    | 4         | 15.38%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 38.46%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 19.23%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 11.54%  |
| Broadcom 5880                                                                | 3         | 11.54%  |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 7.69%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 7.69%   |
| Broadcom 58200                                                               | 1         | 3.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 158       | 61.96%  |
| 1     | 77        | 30.2%   |
| 2     | 17        | 6.67%   |
| 3     | 2         | 0.78%   |
| 5     | 1         | 0.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 41        | 34.17%  |
| Chipcard                 | 24        | 20%     |
| Graphics card            | 20        | 16.67%  |
| Net/wireless             | 10        | 8.33%   |
| Bluetooth                | 6         | 5%      |
| Storage                  | 5         | 4.17%   |
| Communication controller | 3         | 2.5%    |
| Unassigned class         | 2         | 1.67%   |
| Sound                    | 2         | 1.67%   |
| Net/ethernet             | 2         | 1.67%   |
| Multimedia controller    | 2         | 1.67%   |
| Camera                   | 2         | 1.67%   |
| Modem                    | 1         | 0.83%   |

